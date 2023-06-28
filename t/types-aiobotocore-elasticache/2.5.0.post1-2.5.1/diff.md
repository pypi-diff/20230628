# Comparing `tmp/types-aiobotocore-elasticache-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-elasticache-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-elasticache-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-elasticache-2.5.1.tar", last modified: Wed Jun 28 01:43:27 2023, max compression
```

## Comparing `types-aiobotocore-elasticache-2.5.0.post1.tar` & `types-aiobotocore-elasticache-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.623175 types-aiobotocore-elasticache-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:02.000000 types-aiobotocore-elasticache-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    27910 2023-03-11 12:26:34.619174 types-aiobotocore-elasticache-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    26323 2023-03-11 12:14:02.000000 types-aiobotocore-elasticache-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.623175 types-aiobotocore-elasticache-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:14:01.000000 types-aiobotocore-elasticache-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.615174 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/
--rw-r--r--   0 runner    (1001) docker     (123)     5698 2023-03-11 12:14:02.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5697 2023-03-11 12:14:02.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:14:02.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    70934 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    70839 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13885 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13883 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    23665 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    23645 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:02.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    86079 2023-03-11 12:14:05.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    86012 2023-03-11 12:14:04.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:02.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     5424 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     5420 2023-03-11 12:14:03.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.619174 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    27910 2023-03-11 12:26:34.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      970 2023-03-11 12:26:34.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:34.000000 types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.078132 types-aiobotocore-elasticache-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    27927 2023-06-28 01:43:27.074132 types-aiobotocore-elasticache-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    26346 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:27.078132 types-aiobotocore-elasticache-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.070132 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/
+-rw-r--r--   0 runner    (1001) docker     (123)     5698 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5697 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    71044 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70949 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14180 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14178 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    23603 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23584 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    86404 2023-06-28 01:30:42.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    86337 2023-06-28 01:30:41.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:38.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5424 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5420 2023-06-28 01:30:39.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.074132 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    27927 2023-06-28 01:43:26.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-28 01:43:26.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:26.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:26.000000 types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/LICENSE` & `types-aiobotocore-elasticache-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/PKG-INFO` & `types-aiobotocore-elasticache-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elasticache
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElastiCache 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElastiCache 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elasticache"></a>
 
 # types-aiobotocore-elasticache
 
 [![PyPI - types-aiobotocore-elasticache](https://img.shields.io/pypi/v/types-aiobotocore-elasticache.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticache)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elasticache.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticache)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elasticache?color=blue)](https://pypistats.org/packages/types-aiobotocore-elasticache)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElastiCache 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
+[aiobotocore.ElastiCache 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
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
 [types-aiobotocore-elasticache docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/).
 
 See how it helps to find and fix potential bugs:
 
@@ -403,14 +403,15 @@
     AuthTokenUpdateStatusType,
     AuthTokenUpdateStrategyTypeType,
     AuthenticationTypeType,
     AutomaticFailoverStatusType,
     CacheClusterAvailableWaiterName,
     CacheClusterDeletedWaiterName,
     ChangeTypeType,
+    ClusterModeType,
     DataTieringStatusType,
     DescribeCacheClustersPaginatorName,
     DescribeCacheEngineVersionsPaginatorName,
     DescribeCacheParameterGroupsPaginatorName,
     DescribeCacheParametersPaginatorName,
     DescribeCacheSecurityGroupsPaginatorName,
     DescribeCacheSubnetGroupsPaginatorName,
@@ -465,15 +466,15 @@
 
 `types_aiobotocore_elasticache.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elasticache.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AllowedNodeTypeModificationsMessageTypeDef,
     AuthenticationModeTypeDef,
     AuthenticationTypeDef,
     AuthorizeCacheSecurityGroupIngressMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     BatchApplyUpdateActionMessageRequestTypeDef,
     BatchStopUpdateActionMessageRequestTypeDef,
     CacheParameterGroupStatusTypeDef,
@@ -481,14 +482,15 @@
     EndpointTypeDef,
     NotificationConfigurationTypeDef,
     SecurityGroupMembershipTypeDef,
     CacheEngineVersionTypeDef,
     CacheNodeTypeSpecificValueTypeDef,
     CacheNodeUpdateStatusTypeDef,
     ParameterTypeDef,
+    CacheParameterGroupNameMessageTypeDef,
     CacheParameterGroupTypeDef,
     EC2SecurityGroupTypeDef,
     CloudWatchLogsDestinationDetailsTypeDef,
     CompleteMigrationMessageRequestTypeDef,
     ConfigureShardTypeDef,
     CreateGlobalReplicationGroupMessageRequestTypeDef,
     NodeGroupConfigurationTypeDef,
@@ -500,71 +502,85 @@
     DeleteCacheSubnetGroupMessageRequestTypeDef,
     DeleteGlobalReplicationGroupMessageRequestTypeDef,
     DeleteReplicationGroupMessageRequestTypeDef,
     DeleteSnapshotMessageRequestTypeDef,
     DeleteUserGroupMessageRequestTypeDef,
     DeleteUserMessageRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef,
     DescribeCacheClustersMessageRequestTypeDef,
+    DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef,
     DescribeCacheEngineVersionsMessageRequestTypeDef,
+    DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef,
     DescribeCacheParameterGroupsMessageRequestTypeDef,
+    DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
     DescribeCacheParametersMessageRequestTypeDef,
+    DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef,
     DescribeCacheSecurityGroupsMessageRequestTypeDef,
+    DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef,
     DescribeCacheSubnetGroupsMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef,
     DescribeGlobalReplicationGroupsMessageRequestTypeDef,
+    DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef,
     DescribeReplicationGroupsMessageRequestTypeDef,
+    DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef,
     DescribeReservedCacheNodesMessageRequestTypeDef,
+    DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef,
     DescribeReservedCacheNodesOfferingsMessageRequestTypeDef,
+    DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef,
     DescribeServiceUpdatesMessageRequestTypeDef,
+    DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsMessageRequestTypeDef,
     TimeRangeFilterTypeDef,
+    DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef,
     DescribeUserGroupsMessageRequestTypeDef,
     FilterTypeDef,
     KinesisFirehoseDestinationDetailsTypeDef,
     DisassociateGlobalReplicationGroupMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventTypeDef,
     FailoverGlobalReplicationGroupMessageRequestTypeDef,
     GlobalNodeGroupTypeDef,
     GlobalReplicationGroupInfoTypeDef,
     GlobalReplicationGroupMemberTypeDef,
     ListAllowedNodeTypeModificationsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ParameterNameValueTypeDef,
     ModifyCacheSubnetGroupMessageRequestTypeDef,
     ModifyGlobalReplicationGroupMessageRequestTypeDef,
     ReshardingConfigurationTypeDef,
     ModifyUserGroupMessageRequestTypeDef,
     NodeGroupMemberUpdateStatusTypeDef,
+    PaginatorConfigTypeDef,
     ProcessedUpdateActionTypeDef,
     RebalanceSlotsInGlobalReplicationGroupMessageRequestTypeDef,
     RebootCacheClusterMessageRequestTypeDef,
     RecurringChargeTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
     UserGroupsUpdateStatusTypeDef,
     SlotMigrationTypeDef,
+    ResponseMetadataTypeDef,
     RevokeCacheSecurityGroupIngressMessageRequestTypeDef,
     ServiceUpdateTypeDef,
     SubnetOutpostTypeDef,
     TestFailoverMessageRequestTypeDef,
     UnprocessedUpdateActionTypeDef,
     UserGroupPendingChangesTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopySnapshotMessageRequestTypeDef,
     CreateCacheParameterGroupMessageRequestTypeDef,
     CreateCacheSecurityGroupMessageRequestTypeDef,
     CreateCacheSubnetGroupMessageRequestTypeDef,
     CreateSnapshotMessageRequestTypeDef,
     CreateUserGroupMessageRequestTypeDef,
     PurchaseReservedCacheNodesOfferingMessageRequestTypeDef,
-    AllowedNodeTypeModificationsMessageTypeDef,
-    CacheParameterGroupNameMessageTypeDef,
-    EmptyResponseMetadataTypeDef,
     TagListMessageTypeDef,
     CreateUserMessageRequestTypeDef,
     ModifyUserMessageRequestTypeDef,
     UserResponseMetadataTypeDef,
     UserTypeDef,
     CacheNodeTypeDef,
     NodeGroupMemberTypeDef,
@@ -577,29 +593,14 @@
     IncreaseReplicaCountMessageRequestTypeDef,
     NodeSnapshotTypeDef,
     StartMigrationMessageRequestTypeDef,
     DescribeCacheClustersMessageCacheClusterAvailableWaitTypeDef,
     DescribeCacheClustersMessageCacheClusterDeletedWaitTypeDef,
     DescribeReplicationGroupsMessageReplicationGroupAvailableWaitTypeDef,
     DescribeReplicationGroupsMessageReplicationGroupDeletedWaitTypeDef,
-    DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef,
-    DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef,
-    DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef,
-    DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
-    DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef,
-    DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef,
-    DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef,
-    DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef,
-    DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef,
-    DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef,
-    DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef,
-    DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef,
     DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef,
     DescribeUpdateActionsMessageRequestTypeDef,
     DescribeUsersMessageDescribeUsersPaginateTypeDef,
     DescribeUsersMessageRequestTypeDef,
     DestinationDetailsTypeDef,
     EventsMessageTypeDef,
     GlobalReplicationGroupTypeDef,
@@ -686,43 +687,43 @@
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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/README.md` & `types-aiobotocore-elasticache-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-elasticache"></a>
 
 # types-aiobotocore-elasticache
 
 [![PyPI - types-aiobotocore-elasticache](https://img.shields.io/pypi/v/types-aiobotocore-elasticache.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticache)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elasticache.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticache)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elasticache?color=blue)](https://pypistats.org/packages/types-aiobotocore-elasticache)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElastiCache 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
+[aiobotocore.ElastiCache 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
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
 [types-aiobotocore-elasticache docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/).
 
 See how it helps to find and fix potential bugs:
 
@@ -370,14 +370,15 @@
     AuthTokenUpdateStatusType,
     AuthTokenUpdateStrategyTypeType,
     AuthenticationTypeType,
     AutomaticFailoverStatusType,
     CacheClusterAvailableWaiterName,
     CacheClusterDeletedWaiterName,
     ChangeTypeType,
+    ClusterModeType,
     DataTieringStatusType,
     DescribeCacheClustersPaginatorName,
     DescribeCacheEngineVersionsPaginatorName,
     DescribeCacheParameterGroupsPaginatorName,
     DescribeCacheParametersPaginatorName,
     DescribeCacheSecurityGroupsPaginatorName,
     DescribeCacheSubnetGroupsPaginatorName,
@@ -432,15 +433,15 @@
 
 `types_aiobotocore_elasticache.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elasticache.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AllowedNodeTypeModificationsMessageTypeDef,
     AuthenticationModeTypeDef,
     AuthenticationTypeDef,
     AuthorizeCacheSecurityGroupIngressMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     BatchApplyUpdateActionMessageRequestTypeDef,
     BatchStopUpdateActionMessageRequestTypeDef,
     CacheParameterGroupStatusTypeDef,
@@ -448,14 +449,15 @@
     EndpointTypeDef,
     NotificationConfigurationTypeDef,
     SecurityGroupMembershipTypeDef,
     CacheEngineVersionTypeDef,
     CacheNodeTypeSpecificValueTypeDef,
     CacheNodeUpdateStatusTypeDef,
     ParameterTypeDef,
+    CacheParameterGroupNameMessageTypeDef,
     CacheParameterGroupTypeDef,
     EC2SecurityGroupTypeDef,
     CloudWatchLogsDestinationDetailsTypeDef,
     CompleteMigrationMessageRequestTypeDef,
     ConfigureShardTypeDef,
     CreateGlobalReplicationGroupMessageRequestTypeDef,
     NodeGroupConfigurationTypeDef,
@@ -467,71 +469,85 @@
     DeleteCacheSubnetGroupMessageRequestTypeDef,
     DeleteGlobalReplicationGroupMessageRequestTypeDef,
     DeleteReplicationGroupMessageRequestTypeDef,
     DeleteSnapshotMessageRequestTypeDef,
     DeleteUserGroupMessageRequestTypeDef,
     DeleteUserMessageRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef,
     DescribeCacheClustersMessageRequestTypeDef,
+    DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef,
     DescribeCacheEngineVersionsMessageRequestTypeDef,
+    DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef,
     DescribeCacheParameterGroupsMessageRequestTypeDef,
+    DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
     DescribeCacheParametersMessageRequestTypeDef,
+    DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef,
     DescribeCacheSecurityGroupsMessageRequestTypeDef,
+    DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef,
     DescribeCacheSubnetGroupsMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef,
     DescribeGlobalReplicationGroupsMessageRequestTypeDef,
+    DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef,
     DescribeReplicationGroupsMessageRequestTypeDef,
+    DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef,
     DescribeReservedCacheNodesMessageRequestTypeDef,
+    DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef,
     DescribeReservedCacheNodesOfferingsMessageRequestTypeDef,
+    DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef,
     DescribeServiceUpdatesMessageRequestTypeDef,
+    DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsMessageRequestTypeDef,
     TimeRangeFilterTypeDef,
+    DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef,
     DescribeUserGroupsMessageRequestTypeDef,
     FilterTypeDef,
     KinesisFirehoseDestinationDetailsTypeDef,
     DisassociateGlobalReplicationGroupMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventTypeDef,
     FailoverGlobalReplicationGroupMessageRequestTypeDef,
     GlobalNodeGroupTypeDef,
     GlobalReplicationGroupInfoTypeDef,
     GlobalReplicationGroupMemberTypeDef,
     ListAllowedNodeTypeModificationsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ParameterNameValueTypeDef,
     ModifyCacheSubnetGroupMessageRequestTypeDef,
     ModifyGlobalReplicationGroupMessageRequestTypeDef,
     ReshardingConfigurationTypeDef,
     ModifyUserGroupMessageRequestTypeDef,
     NodeGroupMemberUpdateStatusTypeDef,
+    PaginatorConfigTypeDef,
     ProcessedUpdateActionTypeDef,
     RebalanceSlotsInGlobalReplicationGroupMessageRequestTypeDef,
     RebootCacheClusterMessageRequestTypeDef,
     RecurringChargeTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
     UserGroupsUpdateStatusTypeDef,
     SlotMigrationTypeDef,
+    ResponseMetadataTypeDef,
     RevokeCacheSecurityGroupIngressMessageRequestTypeDef,
     ServiceUpdateTypeDef,
     SubnetOutpostTypeDef,
     TestFailoverMessageRequestTypeDef,
     UnprocessedUpdateActionTypeDef,
     UserGroupPendingChangesTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopySnapshotMessageRequestTypeDef,
     CreateCacheParameterGroupMessageRequestTypeDef,
     CreateCacheSecurityGroupMessageRequestTypeDef,
     CreateCacheSubnetGroupMessageRequestTypeDef,
     CreateSnapshotMessageRequestTypeDef,
     CreateUserGroupMessageRequestTypeDef,
     PurchaseReservedCacheNodesOfferingMessageRequestTypeDef,
-    AllowedNodeTypeModificationsMessageTypeDef,
-    CacheParameterGroupNameMessageTypeDef,
-    EmptyResponseMetadataTypeDef,
     TagListMessageTypeDef,
     CreateUserMessageRequestTypeDef,
     ModifyUserMessageRequestTypeDef,
     UserResponseMetadataTypeDef,
     UserTypeDef,
     CacheNodeTypeDef,
     NodeGroupMemberTypeDef,
@@ -544,29 +560,14 @@
     IncreaseReplicaCountMessageRequestTypeDef,
     NodeSnapshotTypeDef,
     StartMigrationMessageRequestTypeDef,
     DescribeCacheClustersMessageCacheClusterAvailableWaitTypeDef,
     DescribeCacheClustersMessageCacheClusterDeletedWaitTypeDef,
     DescribeReplicationGroupsMessageReplicationGroupAvailableWaitTypeDef,
     DescribeReplicationGroupsMessageReplicationGroupDeletedWaitTypeDef,
-    DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef,
-    DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef,
-    DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef,
-    DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
-    DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef,
-    DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef,
-    DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef,
-    DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef,
-    DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef,
-    DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef,
-    DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef,
-    DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef,
     DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef,
     DescribeUpdateActionsMessageRequestTypeDef,
     DescribeUsersMessageDescribeUsersPaginateTypeDef,
     DescribeUsersMessageRequestTypeDef,
     DestinationDetailsTypeDef,
     EventsMessageTypeDef,
     GlobalReplicationGroupTypeDef,
@@ -653,43 +654,43 @@
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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/setup.py` & `types-aiobotocore-elasticache-2.5.1/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-elasticache.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-elasticache",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_elasticache"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ElastiCache 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ElastiCache 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/"
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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/__init__.py` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/__init__.pyi` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/__main__.py` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ElastiCache 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ElastiCache 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache\nOther"
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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/client.py` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -20,14 +20,15 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AuthTokenUpdateStrategyTypeType,
     AZModeType,
+    ClusterModeType,
     IpDiscoveryType,
     NetworkTypeType,
     OutpostModeType,
     ServiceUpdateStatusType,
     SourceTypeType,
     TransitEncryptionModeType,
     UpdateActionStatusType,
@@ -456,15 +457,16 @@
         AtRestEncryptionEnabled: bool = ...,
         KmsKeyId: str = ...,
         UserGroupIds: Sequence[str] = ...,
         LogDeliveryConfigurations: Sequence[LogDeliveryConfigurationRequestTypeDef] = ...,
         DataTieringEnabled: bool = ...,
         NetworkType: NetworkTypeType = ...,
         IpDiscovery: IpDiscoveryType = ...,
-        TransitEncryptionMode: TransitEncryptionModeType = ...
+        TransitEncryptionMode: TransitEncryptionModeType = ...,
+        ClusterMode: ClusterModeType = ...
     ) -> CreateReplicationGroupResultTypeDef:
         """
         Creates a Redis (cluster mode disabled) or a Redis (cluster mode enabled)
         replication group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_replication_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#create_replication_group)
@@ -596,15 +598,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#delete_cache_subnet_group)
         """
 
     async def delete_global_replication_group(
         self, *, GlobalReplicationGroupId: str, RetainPrimaryReplicationGroup: bool
     ) -> DeleteGlobalReplicationGroupResultTypeDef:
         """
-        Deleting a Global datastore is a two-step process * First, you must
+        Deleting a Global datastore is a two-step process: * First, you must
         DisassociateGlobalReplicationGroup to remove the secondary clusters in the
         Global datastore.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_global_replication_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#delete_global_replication_group)
         """
 
@@ -1091,15 +1093,16 @@
         AuthTokenUpdateStrategy: AuthTokenUpdateStrategyTypeType = ...,
         UserGroupIdsToAdd: Sequence[str] = ...,
         UserGroupIdsToRemove: Sequence[str] = ...,
         RemoveUserGroups: bool = ...,
         LogDeliveryConfigurations: Sequence[LogDeliveryConfigurationRequestTypeDef] = ...,
         IpDiscovery: IpDiscoveryType = ...,
         TransitEncryptionEnabled: bool = ...,
-        TransitEncryptionMode: TransitEncryptionModeType = ...
+        TransitEncryptionMode: TransitEncryptionModeType = ...,
+        ClusterMode: ClusterModeType = ...
     ) -> ModifyReplicationGroupResultTypeDef:
         """
         Modifies the settings for a replication group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_replication_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#modify_replication_group)
         """
```

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/client.pyi` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -20,14 +20,15 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AuthTokenUpdateStrategyTypeType,
     AZModeType,
+    ClusterModeType,
     IpDiscoveryType,
     NetworkTypeType,
     OutpostModeType,
     ServiceUpdateStatusType,
     SourceTypeType,
     TransitEncryptionModeType,
     UpdateActionStatusType,
@@ -438,15 +439,16 @@
         AtRestEncryptionEnabled: bool = ...,
         KmsKeyId: str = ...,
         UserGroupIds: Sequence[str] = ...,
         LogDeliveryConfigurations: Sequence[LogDeliveryConfigurationRequestTypeDef] = ...,
         DataTieringEnabled: bool = ...,
         NetworkType: NetworkTypeType = ...,
         IpDiscovery: IpDiscoveryType = ...,
-        TransitEncryptionMode: TransitEncryptionModeType = ...
+        TransitEncryptionMode: TransitEncryptionModeType = ...,
+        ClusterMode: ClusterModeType = ...
     ) -> CreateReplicationGroupResultTypeDef:
         """
         Creates a Redis (cluster mode disabled) or a Redis (cluster mode enabled)
         replication group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.create_replication_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#create_replication_group)
@@ -568,15 +570,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_cache_subnet_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#delete_cache_subnet_group)
         """
     async def delete_global_replication_group(
         self, *, GlobalReplicationGroupId: str, RetainPrimaryReplicationGroup: bool
     ) -> DeleteGlobalReplicationGroupResultTypeDef:
         """
-        Deleting a Global datastore is a two-step process * First, you must
+        Deleting a Global datastore is a two-step process: * First, you must
         DisassociateGlobalReplicationGroup to remove the secondary clusters in the
         Global datastore.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.delete_global_replication_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#delete_global_replication_group)
         """
     async def delete_replication_group(
@@ -1030,15 +1032,16 @@
         AuthTokenUpdateStrategy: AuthTokenUpdateStrategyTypeType = ...,
         UserGroupIdsToAdd: Sequence[str] = ...,
         UserGroupIdsToRemove: Sequence[str] = ...,
         RemoveUserGroups: bool = ...,
         LogDeliveryConfigurations: Sequence[LogDeliveryConfigurationRequestTypeDef] = ...,
         IpDiscovery: IpDiscoveryType = ...,
         TransitEncryptionEnabled: bool = ...,
-        TransitEncryptionMode: TransitEncryptionModeType = ...
+        TransitEncryptionMode: TransitEncryptionModeType = ...,
+        ClusterMode: ClusterModeType = ...
     ) -> ModifyReplicationGroupResultTypeDef:
         """
         Modifies the settings for a replication group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Client.modify_replication_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/client/#modify_replication_group)
         """
```

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/literals.py` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -24,14 +24,15 @@
     "AuthTokenUpdateStatusType",
     "AuthTokenUpdateStrategyTypeType",
     "AuthenticationTypeType",
     "AutomaticFailoverStatusType",
     "CacheClusterAvailableWaiterName",
     "CacheClusterDeletedWaiterName",
     "ChangeTypeType",
+    "ClusterModeType",
     "DataTieringStatusType",
     "DescribeCacheClustersPaginatorName",
     "DescribeCacheEngineVersionsPaginatorName",
     "DescribeCacheParameterGroupsPaginatorName",
     "DescribeCacheParametersPaginatorName",
     "DescribeCacheSecurityGroupsPaginatorName",
     "DescribeCacheSubnetGroupsPaginatorName",
@@ -80,14 +81,15 @@
 AuthTokenUpdateStatusType = Literal["ROTATING", "SETTING"]
 AuthTokenUpdateStrategyTypeType = Literal["DELETE", "ROTATE", "SET"]
 AuthenticationTypeType = Literal["iam", "no-password", "password"]
 AutomaticFailoverStatusType = Literal["disabled", "disabling", "enabled", "enabling"]
 CacheClusterAvailableWaiterName = Literal["cache_cluster_available"]
 CacheClusterDeletedWaiterName = Literal["cache_cluster_deleted"]
 ChangeTypeType = Literal["immediate", "requires-reboot"]
+ClusterModeType = Literal["compatible", "disabled", "enabled"]
 DataTieringStatusType = Literal["disabled", "enabled"]
 DescribeCacheClustersPaginatorName = Literal["describe_cache_clusters"]
 DescribeCacheEngineVersionsPaginatorName = Literal["describe_cache_engine_versions"]
 DescribeCacheParameterGroupsPaginatorName = Literal["describe_cache_parameter_groups"]
 DescribeCacheParametersPaginatorName = Literal["describe_cache_parameters"]
 DescribeCacheSecurityGroupsPaginatorName = Literal["describe_cache_security_groups"]
 DescribeCacheSubnetGroupsPaginatorName = Literal["describe_cache_subnet_groups"]
@@ -206,14 +208,15 @@
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
@@ -292,14 +295,15 @@
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
@@ -310,14 +314,15 @@
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
@@ -353,14 +358,15 @@
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
@@ -379,16 +385,19 @@
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
@@ -472,15 +481,17 @@
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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/literals.pyi` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -23,14 +23,15 @@
     "AuthTokenUpdateStatusType",
     "AuthTokenUpdateStrategyTypeType",
     "AuthenticationTypeType",
     "AutomaticFailoverStatusType",
     "CacheClusterAvailableWaiterName",
     "CacheClusterDeletedWaiterName",
     "ChangeTypeType",
+    "ClusterModeType",
     "DataTieringStatusType",
     "DescribeCacheClustersPaginatorName",
     "DescribeCacheEngineVersionsPaginatorName",
     "DescribeCacheParameterGroupsPaginatorName",
     "DescribeCacheParametersPaginatorName",
     "DescribeCacheSecurityGroupsPaginatorName",
     "DescribeCacheSubnetGroupsPaginatorName",
@@ -78,14 +79,15 @@
 AuthTokenUpdateStatusType = Literal["ROTATING", "SETTING"]
 AuthTokenUpdateStrategyTypeType = Literal["DELETE", "ROTATE", "SET"]
 AuthenticationTypeType = Literal["iam", "no-password", "password"]
 AutomaticFailoverStatusType = Literal["disabled", "disabling", "enabled", "enabling"]
 CacheClusterAvailableWaiterName = Literal["cache_cluster_available"]
 CacheClusterDeletedWaiterName = Literal["cache_cluster_deleted"]
 ChangeTypeType = Literal["immediate", "requires-reboot"]
+ClusterModeType = Literal["compatible", "disabled", "enabled"]
 DataTieringStatusType = Literal["disabled", "enabled"]
 DescribeCacheClustersPaginatorName = Literal["describe_cache_clusters"]
 DescribeCacheEngineVersionsPaginatorName = Literal["describe_cache_engine_versions"]
 DescribeCacheParameterGroupsPaginatorName = Literal["describe_cache_parameter_groups"]
 DescribeCacheParametersPaginatorName = Literal["describe_cache_parameters"]
 DescribeCacheSecurityGroupsPaginatorName = Literal["describe_cache_security_groups"]
 DescribeCacheSubnetGroupsPaginatorName = Literal["describe_cache_subnet_groups"]
@@ -204,14 +206,15 @@
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
@@ -290,14 +293,15 @@
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
@@ -308,14 +312,15 @@
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
@@ -351,14 +356,15 @@
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
@@ -377,16 +383,19 @@
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
@@ -470,15 +479,17 @@
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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/paginator.py` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -48,17 +48,16 @@
         describe_service_updates_paginator: DescribeServiceUpdatesPaginator = client.get_paginator("describe_service_updates")
         describe_snapshots_paginator: DescribeSnapshotsPaginator = client.get_paginator("describe_snapshots")
         describe_update_actions_paginator: DescribeUpdateActionsPaginator = client.get_paginator("describe_update_actions")
         describe_user_groups_paginator: DescribeUserGroupsPaginator = client.get_paginator("describe_user_groups")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ServiceUpdateStatusType, SourceTypeType, UpdateActionStatusType
 from .type_defs import (
     CacheClusterMessageTypeDef,
@@ -79,20 +78,14 @@
     ReservedCacheNodeMessageTypeDef,
     ReservedCacheNodesOfferingMessageTypeDef,
     ServiceUpdatesMessageTypeDef,
     TimeRangeFilterTypeDef,
     UpdateActionsMessageTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeCacheClustersPaginator",
     "DescribeCacheEngineVersionsPaginator",
     "DescribeCacheParameterGroupsPaginator",
     "DescribeCacheParametersPaginator",
     "DescribeCacheSecurityGroupsPaginator",
     "DescribeCacheSubnetGroupsPaginator",
@@ -105,201 +98,191 @@
     "DescribeServiceUpdatesPaginator",
     "DescribeSnapshotsPaginator",
     "DescribeUpdateActionsPaginator",
     "DescribeUserGroupsPaginator",
     "DescribeUsersPaginator",
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
 class DescribeCacheClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheclusterspaginator)
     """
 
     def paginate(
         self,
         *,
         CacheClusterId: str = ...,
         ShowCacheNodeInfo: bool = ...,
         ShowCacheClustersNotInReplicationGroups: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheClusterMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheclusterspaginator)
         """
 
-
 class DescribeCacheEngineVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheEngineVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheengineversionspaginator)
     """
 
     def paginate(
         self,
         *,
         Engine: str = ...,
         EngineVersion: str = ...,
         CacheParameterGroupFamily: str = ...,
         DefaultOnly: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheEngineVersionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheengineversionspaginator)
         """
 
-
 class DescribeCacheParameterGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameterGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparametergroupspaginator)
     """
 
     def paginate(
-        self, *, CacheParameterGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        CacheParameterGroupName: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheParameterGroupsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparametergroupspaginator)
         """
 
-
 class DescribeCacheParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparameterspaginator)
     """
 
     def paginate(
         self,
         *,
         CacheParameterGroupName: str,
         Source: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheParameterGroupDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparameterspaginator)
         """
 
-
 class DescribeCacheSecurityGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSecurityGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesecuritygroupspaginator)
     """
 
     def paginate(
-        self, *, CacheSecurityGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CacheSecurityGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheSecurityGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSecurityGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesecuritygroupspaginator)
         """
 
-
 class DescribeCacheSubnetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSubnetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesubnetgroupspaginator)
     """
 
     def paginate(
-        self, *, CacheSubnetGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CacheSubnetGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheSubnetGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesubnetgroupspaginator)
         """
 
-
 class DescribeEngineDefaultParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEngineDefaultParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeenginedefaultparameterspaginator)
     """
 
     def paginate(
-        self, *, CacheParameterGroupFamily: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CacheParameterGroupFamily: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineDefaultParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEngineDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeenginedefaultparameterspaginator)
         """
 
-
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         SourceIdentifier: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeeventspaginator)
         """
 
-
 class DescribeGlobalReplicationGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeGlobalReplicationGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeglobalreplicationgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalReplicationGroupId: str = ...,
         ShowMemberInfo: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGlobalReplicationGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeGlobalReplicationGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeglobalreplicationgroupspaginator)
         """
 
-
 class DescribeReplicationGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReplicationGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereplicationgroupspaginator)
     """
 
     def paginate(
-        self, *, ReplicationGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ReplicationGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReplicationGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReplicationGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereplicationgroupspaginator)
         """
 
-
 class DescribeReservedCacheNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodespaginator)
     """
 
     def paginate(
@@ -307,85 +290,81 @@
         *,
         ReservedCacheNodeId: str = ...,
         ReservedCacheNodesOfferingId: str = ...,
         CacheNodeType: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedCacheNodeMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodespaginator)
         """
 
-
 class DescribeReservedCacheNodesOfferingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodesOfferings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodesofferingspaginator)
     """
 
     def paginate(
         self,
         *,
         ReservedCacheNodesOfferingId: str = ...,
         CacheNodeType: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedCacheNodesOfferingMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodesOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodesofferingspaginator)
         """
 
-
 class DescribeServiceUpdatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeServiceUpdates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeserviceupdatespaginator)
     """
 
     def paginate(
         self,
         *,
         ServiceUpdateName: str = ...,
         ServiceUpdateStatus: Sequence[ServiceUpdateStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ServiceUpdatesMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeServiceUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeserviceupdatespaginator)
         """
 
-
 class DescribeSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describesnapshotspaginator)
     """
 
     def paginate(
         self,
         *,
         ReplicationGroupId: str = ...,
         CacheClusterId: str = ...,
         SnapshotName: str = ...,
         SnapshotSource: str = ...,
         ShowNodeGroupConfig: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSnapshotsListMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describesnapshotspaginator)
         """
 
-
 class DescribeUpdateActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUpdateActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeupdateactionspaginator)
     """
 
     def paginate(
@@ -395,48 +374,46 @@
         ReplicationGroupIds: Sequence[str] = ...,
         CacheClusterIds: Sequence[str] = ...,
         Engine: str = ...,
         ServiceUpdateStatus: Sequence[ServiceUpdateStatusType] = ...,
         ServiceUpdateTimeRange: TimeRangeFilterTypeDef = ...,
         UpdateActionStatus: Sequence[UpdateActionStatusType] = ...,
         ShowNodeLevelUpdateStatus: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[UpdateActionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUpdateActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeupdateactionspaginator)
         """
 
-
 class DescribeUserGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUserGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeusergroupspaginator)
     """
 
     def paginate(
-        self, *, UserGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUserGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUserGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeusergroupspaginator)
         """
 
-
 class DescribeUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeuserspaginator)
     """
 
     def paginate(
         self,
         *,
         Engine: str = ...,
         UserId: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeuserspaginator)
         """
```

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/paginator.pyi` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/paginator.py`

 * *Files 11% similar despite different names*

```diff
@@ -48,17 +48,16 @@
         describe_service_updates_paginator: DescribeServiceUpdatesPaginator = client.get_paginator("describe_service_updates")
         describe_snapshots_paginator: DescribeSnapshotsPaginator = client.get_paginator("describe_snapshots")
         describe_update_actions_paginator: DescribeUpdateActionsPaginator = client.get_paginator("describe_update_actions")
         describe_user_groups_paginator: DescribeUserGroupsPaginator = client.get_paginator("describe_user_groups")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ServiceUpdateStatusType, SourceTypeType, UpdateActionStatusType
 from .type_defs import (
     CacheClusterMessageTypeDef,
@@ -79,19 +78,14 @@
     ReservedCacheNodeMessageTypeDef,
     ReservedCacheNodesOfferingMessageTypeDef,
     ServiceUpdatesMessageTypeDef,
     TimeRangeFilterTypeDef,
     UpdateActionsMessageTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeCacheClustersPaginator",
     "DescribeCacheEngineVersionsPaginator",
     "DescribeCacheParameterGroupsPaginator",
     "DescribeCacheParametersPaginator",
     "DescribeCacheSecurityGroupsPaginator",
     "DescribeCacheSubnetGroupsPaginator",
@@ -104,188 +98,204 @@
     "DescribeServiceUpdatesPaginator",
     "DescribeSnapshotsPaginator",
     "DescribeUpdateActionsPaginator",
     "DescribeUserGroupsPaginator",
     "DescribeUsersPaginator",
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
 class DescribeCacheClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheclusterspaginator)
     """
 
     def paginate(
         self,
         *,
         CacheClusterId: str = ...,
         ShowCacheNodeInfo: bool = ...,
         ShowCacheClustersNotInReplicationGroups: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheClusterMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheclusterspaginator)
         """
 
+
 class DescribeCacheEngineVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheEngineVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheengineversionspaginator)
     """
 
     def paginate(
         self,
         *,
         Engine: str = ...,
         EngineVersion: str = ...,
         CacheParameterGroupFamily: str = ...,
         DefaultOnly: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheEngineVersionMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheengineversionspaginator)
         """
 
+
 class DescribeCacheParameterGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameterGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparametergroupspaginator)
     """
 
     def paginate(
-        self, *, CacheParameterGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        CacheParameterGroupName: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheParameterGroupsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparametergroupspaginator)
         """
 
+
 class DescribeCacheParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparameterspaginator)
     """
 
     def paginate(
         self,
         *,
         CacheParameterGroupName: str,
         Source: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheParameterGroupDetailsTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecacheparameterspaginator)
         """
 
+
 class DescribeCacheSecurityGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSecurityGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesecuritygroupspaginator)
     """
 
     def paginate(
-        self, *, CacheSecurityGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CacheSecurityGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheSecurityGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSecurityGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesecuritygroupspaginator)
         """
 
+
 class DescribeCacheSubnetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSubnetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesubnetgroupspaginator)
     """
 
     def paginate(
-        self, *, CacheSubnetGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CacheSubnetGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[CacheSubnetGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeCacheSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describecachesubnetgroupspaginator)
         """
 
+
 class DescribeEngineDefaultParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEngineDefaultParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeenginedefaultparameterspaginator)
     """
 
     def paginate(
-        self, *, CacheParameterGroupFamily: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CacheParameterGroupFamily: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineDefaultParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEngineDefaultParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeenginedefaultparameterspaginator)
         """
 
+
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         SourceIdentifier: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeeventspaginator)
         """
 
+
 class DescribeGlobalReplicationGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeGlobalReplicationGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeglobalreplicationgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         GlobalReplicationGroupId: str = ...,
         ShowMemberInfo: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGlobalReplicationGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeGlobalReplicationGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeglobalreplicationgroupspaginator)
         """
 
+
 class DescribeReplicationGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReplicationGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereplicationgroupspaginator)
     """
 
     def paginate(
-        self, *, ReplicationGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ReplicationGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReplicationGroupMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReplicationGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereplicationgroupspaginator)
         """
 
+
 class DescribeReservedCacheNodesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodespaginator)
     """
 
     def paginate(
@@ -293,81 +303,85 @@
         *,
         ReservedCacheNodeId: str = ...,
         ReservedCacheNodesOfferingId: str = ...,
         CacheNodeType: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedCacheNodeMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodespaginator)
         """
 
+
 class DescribeReservedCacheNodesOfferingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodesOfferings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodesofferingspaginator)
     """
 
     def paginate(
         self,
         *,
         ReservedCacheNodesOfferingId: str = ...,
         CacheNodeType: str = ...,
         Duration: str = ...,
         ProductDescription: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ReservedCacheNodesOfferingMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeReservedCacheNodesOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describereservedcachenodesofferingspaginator)
         """
 
+
 class DescribeServiceUpdatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeServiceUpdates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeserviceupdatespaginator)
     """
 
     def paginate(
         self,
         *,
         ServiceUpdateName: str = ...,
         ServiceUpdateStatus: Sequence[ServiceUpdateStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ServiceUpdatesMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeServiceUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeserviceupdatespaginator)
         """
 
+
 class DescribeSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describesnapshotspaginator)
     """
 
     def paginate(
         self,
         *,
         ReplicationGroupId: str = ...,
         CacheClusterId: str = ...,
         SnapshotName: str = ...,
         SnapshotSource: str = ...,
         ShowNodeGroupConfig: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSnapshotsListMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describesnapshotspaginator)
         """
 
+
 class DescribeUpdateActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUpdateActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeupdateactionspaginator)
     """
 
     def paginate(
@@ -377,46 +391,48 @@
         ReplicationGroupIds: Sequence[str] = ...,
         CacheClusterIds: Sequence[str] = ...,
         Engine: str = ...,
         ServiceUpdateStatus: Sequence[ServiceUpdateStatusType] = ...,
         ServiceUpdateTimeRange: TimeRangeFilterTypeDef = ...,
         UpdateActionStatus: Sequence[UpdateActionStatusType] = ...,
         ShowNodeLevelUpdateStatus: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[UpdateActionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUpdateActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeupdateactionspaginator)
         """
 
+
 class DescribeUserGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUserGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeusergroupspaginator)
     """
 
     def paginate(
-        self, *, UserGroupId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, UserGroupId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUserGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUserGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeusergroupspaginator)
         """
 
+
 class DescribeUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeuserspaginator)
     """
 
     def paginate(
         self,
         *,
         Engine: str = ...,
         UserId: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/paginators/#describeuserspaginator)
         """
```

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/type_defs.py` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from .literals import (
     AuthenticationTypeType,
     AuthTokenUpdateStatusType,
     AuthTokenUpdateStrategyTypeType,
     AutomaticFailoverStatusType,
     AZModeType,
     ChangeTypeType,
+    ClusterModeType,
     DataTieringStatusType,
     DestinationTypeType,
     InputAuthenticationTypeType,
     IpDiscoveryType,
     LogDeliveryConfigurationStatusType,
     LogFormatType,
     LogTypeType,
@@ -51,15 +52,15 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "AllowedNodeTypeModificationsMessageTypeDef",
     "AuthenticationModeTypeDef",
     "AuthenticationTypeDef",
     "AuthorizeCacheSecurityGroupIngressMessageRequestTypeDef",
     "AvailabilityZoneTypeDef",
     "BatchApplyUpdateActionMessageRequestTypeDef",
     "BatchStopUpdateActionMessageRequestTypeDef",
     "CacheParameterGroupStatusTypeDef",
@@ -67,14 +68,15 @@
     "EndpointTypeDef",
     "NotificationConfigurationTypeDef",
     "SecurityGroupMembershipTypeDef",
     "CacheEngineVersionTypeDef",
     "CacheNodeTypeSpecificValueTypeDef",
     "CacheNodeUpdateStatusTypeDef",
     "ParameterTypeDef",
+    "CacheParameterGroupNameMessageTypeDef",
     "CacheParameterGroupTypeDef",
     "EC2SecurityGroupTypeDef",
     "CloudWatchLogsDestinationDetailsTypeDef",
     "CompleteMigrationMessageRequestTypeDef",
     "ConfigureShardTypeDef",
     "CreateGlobalReplicationGroupMessageRequestTypeDef",
     "NodeGroupConfigurationTypeDef",
@@ -86,71 +88,85 @@
     "DeleteCacheSubnetGroupMessageRequestTypeDef",
     "DeleteGlobalReplicationGroupMessageRequestTypeDef",
     "DeleteReplicationGroupMessageRequestTypeDef",
     "DeleteSnapshotMessageRequestTypeDef",
     "DeleteUserGroupMessageRequestTypeDef",
     "DeleteUserMessageRequestTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
     "DescribeCacheClustersMessageRequestTypeDef",
+    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
     "DescribeCacheEngineVersionsMessageRequestTypeDef",
+    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
     "DescribeCacheParameterGroupsMessageRequestTypeDef",
+    "DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
     "DescribeCacheParametersMessageRequestTypeDef",
+    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
     "DescribeCacheSecurityGroupsMessageRequestTypeDef",
+    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
     "DescribeCacheSubnetGroupsMessageRequestTypeDef",
+    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     "DescribeEngineDefaultParametersMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
     "DescribeGlobalReplicationGroupsMessageRequestTypeDef",
+    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
     "DescribeReplicationGroupsMessageRequestTypeDef",
+    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
     "DescribeReservedCacheNodesMessageRequestTypeDef",
+    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
     "DescribeReservedCacheNodesOfferingsMessageRequestTypeDef",
+    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
     "DescribeServiceUpdatesMessageRequestTypeDef",
+    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
     "DescribeSnapshotsMessageRequestTypeDef",
     "TimeRangeFilterTypeDef",
+    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
     "DescribeUserGroupsMessageRequestTypeDef",
     "FilterTypeDef",
     "KinesisFirehoseDestinationDetailsTypeDef",
     "DisassociateGlobalReplicationGroupMessageRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventTypeDef",
     "FailoverGlobalReplicationGroupMessageRequestTypeDef",
     "GlobalNodeGroupTypeDef",
     "GlobalReplicationGroupInfoTypeDef",
     "GlobalReplicationGroupMemberTypeDef",
     "ListAllowedNodeTypeModificationsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
     "ParameterNameValueTypeDef",
     "ModifyCacheSubnetGroupMessageRequestTypeDef",
     "ModifyGlobalReplicationGroupMessageRequestTypeDef",
     "ReshardingConfigurationTypeDef",
     "ModifyUserGroupMessageRequestTypeDef",
     "NodeGroupMemberUpdateStatusTypeDef",
+    "PaginatorConfigTypeDef",
     "ProcessedUpdateActionTypeDef",
     "RebalanceSlotsInGlobalReplicationGroupMessageRequestTypeDef",
     "RebootCacheClusterMessageRequestTypeDef",
     "RecurringChargeTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
     "UserGroupsUpdateStatusTypeDef",
     "SlotMigrationTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeCacheSecurityGroupIngressMessageRequestTypeDef",
     "ServiceUpdateTypeDef",
     "SubnetOutpostTypeDef",
     "TestFailoverMessageRequestTypeDef",
     "UnprocessedUpdateActionTypeDef",
     "UserGroupPendingChangesTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CopySnapshotMessageRequestTypeDef",
     "CreateCacheParameterGroupMessageRequestTypeDef",
     "CreateCacheSecurityGroupMessageRequestTypeDef",
     "CreateCacheSubnetGroupMessageRequestTypeDef",
     "CreateSnapshotMessageRequestTypeDef",
     "CreateUserGroupMessageRequestTypeDef",
     "PurchaseReservedCacheNodesOfferingMessageRequestTypeDef",
-    "AllowedNodeTypeModificationsMessageTypeDef",
-    "CacheParameterGroupNameMessageTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "TagListMessageTypeDef",
     "CreateUserMessageRequestTypeDef",
     "ModifyUserMessageRequestTypeDef",
     "UserResponseMetadataTypeDef",
     "UserTypeDef",
     "CacheNodeTypeDef",
     "NodeGroupMemberTypeDef",
@@ -163,29 +179,14 @@
     "IncreaseReplicaCountMessageRequestTypeDef",
     "NodeSnapshotTypeDef",
     "StartMigrationMessageRequestTypeDef",
     "DescribeCacheClustersMessageCacheClusterAvailableWaitTypeDef",
     "DescribeCacheClustersMessageCacheClusterDeletedWaitTypeDef",
     "DescribeReplicationGroupsMessageReplicationGroupAvailableWaitTypeDef",
     "DescribeReplicationGroupsMessageReplicationGroupDeletedWaitTypeDef",
-    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
-    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
-    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
-    "DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
-    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
-    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
-    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
-    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
-    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
-    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
-    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
-    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
-    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
     "DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef",
     "DescribeUpdateActionsMessageRequestTypeDef",
     "DescribeUsersMessageDescribeUsersPaginateTypeDef",
     "DescribeUsersMessageRequestTypeDef",
     "DestinationDetailsTypeDef",
     "EventsMessageTypeDef",
     "GlobalReplicationGroupTypeDef",
@@ -269,22 +270,20 @@
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AllowedNodeTypeModificationsMessageTypeDef = TypedDict(
+    "AllowedNodeTypeModificationsMessageTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScaleUpModifications": List[str],
+        "ScaleDownModifications": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthenticationModeTypeDef = TypedDict(
     "AuthenticationModeTypeDef",
     {
         "Type": InputAuthenticationTypeType,
@@ -459,14 +458,22 @@
         "IsModifiable": bool,
         "MinimumEngineVersion": str,
         "ChangeType": ChangeTypeType,
     },
     total=False,
 )
 
+CacheParameterGroupNameMessageTypeDef = TypedDict(
+    "CacheParameterGroupNameMessageTypeDef",
+    {
+        "CacheParameterGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CacheParameterGroupTypeDef = TypedDict(
     "CacheParameterGroupTypeDef",
     {
         "CacheParameterGroupName": str,
         "CacheParameterGroupFamily": str,
         "Description": str,
         "IsGlobal": bool,
@@ -706,20 +713,21 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef = TypedDict(
+    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CacheClusterId": str,
+        "ShowCacheNodeInfo": bool,
+        "ShowCacheClustersNotInReplicationGroups": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeCacheClustersMessageRequestTypeDef = TypedDict(
     "DescribeCacheClustersMessageRequestTypeDef",
     {
@@ -728,37 +736,81 @@
         "Marker": str,
         "ShowCacheNodeInfo": bool,
         "ShowCacheClustersNotInReplicationGroups": bool,
     },
     total=False,
 )
 
+DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef = TypedDict(
+    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
+    {
+        "Engine": str,
+        "EngineVersion": str,
+        "CacheParameterGroupFamily": str,
+        "DefaultOnly": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheEngineVersionsMessageRequestTypeDef = TypedDict(
     "DescribeCacheEngineVersionsMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "CacheParameterGroupFamily": str,
         "MaxRecords": int,
         "Marker": str,
         "DefaultOnly": bool,
     },
     total=False,
 )
 
+DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
+    {
+        "CacheParameterGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheParameterGroupsMessageRequestTypeDef = TypedDict(
     "DescribeCacheParameterGroupsMessageRequestTypeDef",
     {
         "CacheParameterGroupName": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
+    {
+        "CacheParameterGroupName": str,
+    },
+)
+_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
+    {
+        "Source": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef(
+    _RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
+    _OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeCacheParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeCacheParametersMessageRequestTypeDef",
     {
         "CacheParameterGroupName": str,
     },
 )
 _OptionalDescribeCacheParametersMessageRequestTypeDef = TypedDict(
@@ -775,34 +827,74 @@
 class DescribeCacheParametersMessageRequestTypeDef(
     _RequiredDescribeCacheParametersMessageRequestTypeDef,
     _OptionalDescribeCacheParametersMessageRequestTypeDef,
 ):
     pass
 
 
+DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef = TypedDict(
+    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
+    {
+        "CacheSecurityGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheSecurityGroupsMessageRequestTypeDef = TypedDict(
     "DescribeCacheSecurityGroupsMessageRequestTypeDef",
     {
         "CacheSecurityGroupName": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
+    {
+        "CacheSubnetGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheSubnetGroupsMessageRequestTypeDef = TypedDict(
     "DescribeCacheSubnetGroupsMessageRequestTypeDef",
     {
         "CacheSubnetGroupName": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
+    {
+        "CacheParameterGroupFamily": str,
+    },
+)
+_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
+    {
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
         "CacheParameterGroupFamily": str,
     },
 )
 _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
@@ -818,49 +910,95 @@
 class DescribeEngineDefaultParametersMessageRequestTypeDef(
     _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef,
     _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef,
 ):
     pass
 
 
+DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+    {
+        "SourceIdentifier": str,
+        "SourceType": SourceTypeType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
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
         "Duration": int,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef = TypedDict(
+    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
+    {
+        "GlobalReplicationGroupId": str,
+        "ShowMemberInfo": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGlobalReplicationGroupsMessageRequestTypeDef = TypedDict(
     "DescribeGlobalReplicationGroupsMessageRequestTypeDef",
     {
         "GlobalReplicationGroupId": str,
         "MaxRecords": int,
         "Marker": str,
         "ShowMemberInfo": bool,
     },
     total=False,
 )
 
+DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef = TypedDict(
+    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
+    {
+        "ReplicationGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReplicationGroupsMessageRequestTypeDef = TypedDict(
     "DescribeReplicationGroupsMessageRequestTypeDef",
     {
         "ReplicationGroupId": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef = TypedDict(
+    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
+    {
+        "ReservedCacheNodeId": str,
+        "ReservedCacheNodesOfferingId": str,
+        "CacheNodeType": str,
+        "Duration": str,
+        "ProductDescription": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedCacheNodesMessageRequestTypeDef = TypedDict(
     "DescribeReservedCacheNodesMessageRequestTypeDef",
     {
         "ReservedCacheNodeId": str,
         "ReservedCacheNodesOfferingId": str,
         "CacheNodeType": str,
         "Duration": str,
@@ -868,39 +1006,75 @@
         "OfferingType": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef = TypedDict(
+    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
+    {
+        "ReservedCacheNodesOfferingId": str,
+        "CacheNodeType": str,
+        "Duration": str,
+        "ProductDescription": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedCacheNodesOfferingsMessageRequestTypeDef = TypedDict(
     "DescribeReservedCacheNodesOfferingsMessageRequestTypeDef",
     {
         "ReservedCacheNodesOfferingId": str,
         "CacheNodeType": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef = TypedDict(
+    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
+    {
+        "ServiceUpdateName": str,
+        "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeServiceUpdatesMessageRequestTypeDef = TypedDict(
     "DescribeServiceUpdatesMessageRequestTypeDef",
     {
         "ServiceUpdateName": str,
         "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
+    {
+        "ReplicationGroupId": str,
+        "CacheClusterId": str,
+        "SnapshotName": str,
+        "SnapshotSource": str,
+        "ShowNodeGroupConfig": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSnapshotsMessageRequestTypeDef = TypedDict(
     "DescribeSnapshotsMessageRequestTypeDef",
     {
         "ReplicationGroupId": str,
         "CacheClusterId": str,
         "SnapshotName": str,
         "SnapshotSource": str,
@@ -916,14 +1090,23 @@
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
     total=False,
 )
 
+DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef = TypedDict(
+    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
+    {
+        "UserGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeUserGroupsMessageRequestTypeDef = TypedDict(
     "DescribeUserGroupsMessageRequestTypeDef",
     {
         "UserGroupId": str,
         "MaxRecords": int,
         "Marker": str,
     },
@@ -951,14 +1134,21 @@
     {
         "GlobalReplicationGroupId": str,
         "ReplicationGroupId": str,
         "ReplicationGroupRegion": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventTypeDef = TypedDict(
     "EventTypeDef",
     {
         "SourceIdentifier": str,
         "SourceType": SourceTypeType,
         "Message": str,
         "Date": datetime,
@@ -1123,14 +1313,24 @@
         "NodeUpdateInitiatedBy": NodeUpdateInitiatedByType,
         "NodeUpdateInitiatedDate": datetime,
         "NodeUpdateStatusModifiedDate": datetime,
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
 ProcessedUpdateActionTypeDef = TypedDict(
     "ProcessedUpdateActionTypeDef",
     {
         "ReplicationGroupId": str,
         "CacheClusterId": str,
         "ServiceUpdateName": str,
         "UpdateActionStatus": UpdateActionStatusType,
@@ -1184,14 +1384,25 @@
     "SlotMigrationTypeDef",
     {
         "ProgressPercentage": float,
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
 RevokeCacheSecurityGroupIngressMessageRequestTypeDef = TypedDict(
     "RevokeCacheSecurityGroupIngressMessageRequestTypeDef",
     {
         "CacheSecurityGroupName": str,
         "EC2SecurityGroupName": str,
         "EC2SecurityGroupOwnerId": str,
     },
@@ -1423,43 +1634,19 @@
 class PurchaseReservedCacheNodesOfferingMessageRequestTypeDef(
     _RequiredPurchaseReservedCacheNodesOfferingMessageRequestTypeDef,
     _OptionalPurchaseReservedCacheNodesOfferingMessageRequestTypeDef,
 ):
     pass
 
 
-AllowedNodeTypeModificationsMessageTypeDef = TypedDict(
-    "AllowedNodeTypeModificationsMessageTypeDef",
-    {
-        "ScaleUpModifications": List[str],
-        "ScaleDownModifications": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CacheParameterGroupNameMessageTypeDef = TypedDict(
-    "CacheParameterGroupNameMessageTypeDef",
-    {
-        "CacheParameterGroupName": str,
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
 TagListMessageTypeDef = TypedDict(
     "TagListMessageTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserMessageRequestTypeDef = TypedDict(
     "_RequiredCreateUserMessageRequestTypeDef",
     {
         "UserId": str,
@@ -1519,15 +1706,15 @@
         "Status": str,
         "Engine": str,
         "MinimumEngineVersion": str,
         "AccessString": str,
         "UserGroupIds": List[str],
         "Authentication": AuthenticationTypeDef,
         "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserTypeDef = TypedDict(
     "UserTypeDef",
     {
         "UserId": str,
@@ -1572,15 +1759,15 @@
 )
 
 CacheEngineVersionMessageTypeDef = TypedDict(
     "CacheEngineVersionMessageTypeDef",
     {
         "Marker": str,
         "CacheEngineVersions": List[CacheEngineVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheNodeTypeSpecificParameterTypeDef = TypedDict(
     "CacheNodeTypeSpecificParameterTypeDef",
     {
         "ParameterName": str,
@@ -1597,23 +1784,23 @@
 )
 
 CacheParameterGroupsMessageTypeDef = TypedDict(
     "CacheParameterGroupsMessageTypeDef",
     {
         "Marker": str,
         "CacheParameterGroups": List[CacheParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheParameterGroupResultTypeDef = TypedDict(
     "CreateCacheParameterGroupResultTypeDef",
     {
         "CacheParameterGroup": CacheParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSecurityGroupTypeDef = TypedDict(
     "CacheSecurityGroupTypeDef",
     {
         "OwnerId": str,
@@ -1740,212 +1927,26 @@
         "MaxRecords": int,
         "Marker": str,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef = TypedDict(
-    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
-    {
-        "CacheClusterId": str,
-        "ShowCacheNodeInfo": bool,
-        "ShowCacheClustersNotInReplicationGroups": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef = TypedDict(
-    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
-    {
-        "Engine": str,
-        "EngineVersion": str,
-        "CacheParameterGroupFamily": str,
-        "DefaultOnly": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
-    {
-        "CacheParameterGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
-    {
-        "CacheParameterGroupName": str,
-    },
-)
-_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
-    {
-        "Source": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef(
-    _RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
-    _OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
-):
-    pass
-
-
-DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef = TypedDict(
-    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
-    {
-        "CacheSecurityGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
-    {
-        "CacheSubnetGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    {
-        "CacheParameterGroupFamily": str,
-    },
-)
-_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    {
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
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    {
-        "SourceIdentifier": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef = TypedDict(
-    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
-    {
-        "GlobalReplicationGroupId": str,
-        "ShowMemberInfo": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef = TypedDict(
-    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
-    {
-        "ReplicationGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef = TypedDict(
-    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
-    {
-        "ReservedCacheNodeId": str,
-        "ReservedCacheNodesOfferingId": str,
-        "CacheNodeType": str,
-        "Duration": str,
-        "ProductDescription": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef = TypedDict(
-    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
-    {
-        "ReservedCacheNodesOfferingId": str,
-        "CacheNodeType": str,
-        "Duration": str,
-        "ProductDescription": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef = TypedDict(
-    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
-    {
-        "ServiceUpdateName": str,
-        "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
-    {
-        "ReplicationGroupId": str,
-        "CacheClusterId": str,
-        "SnapshotName": str,
-        "SnapshotSource": str,
-        "ShowNodeGroupConfig": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef = TypedDict(
-    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
-    {
-        "UserGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef = TypedDict(
     "DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef",
     {
         "ServiceUpdateName": str,
         "ReplicationGroupIds": Sequence[str],
         "CacheClusterIds": Sequence[str],
         "Engine": str,
         "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
         "ServiceUpdateTimeRange": TimeRangeFilterTypeDef,
         "UpdateActionStatus": Sequence[UpdateActionStatusType],
         "ShowNodeLevelUpdateStatus": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeUpdateActionsMessageRequestTypeDef = TypedDict(
     "DescribeUpdateActionsMessageRequestTypeDef",
     {
@@ -1965,15 +1966,15 @@
 
 DescribeUsersMessageDescribeUsersPaginateTypeDef = TypedDict(
     "DescribeUsersMessageDescribeUsersPaginateTypeDef",
     {
         "Engine": str,
         "UserId": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeUsersMessageRequestTypeDef = TypedDict(
     "DescribeUsersMessageRequestTypeDef",
     {
@@ -1996,15 +1997,15 @@
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
 
 GlobalReplicationGroupTypeDef = TypedDict(
     "GlobalReplicationGroupTypeDef",
     {
         "GlobalReplicationGroupId": str,
@@ -2143,15 +2144,15 @@
 )
 
 ServiceUpdatesMessageTypeDef = TypedDict(
     "ServiceUpdatesMessageTypeDef",
     {
         "Marker": str,
         "ServiceUpdates": List[ServiceUpdateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubnetTypeDef = TypedDict(
     "SubnetTypeDef",
     {
         "SubnetIdentifier": str,
@@ -2163,30 +2164,30 @@
 )
 
 UpdateActionResultsMessageTypeDef = TypedDict(
     "UpdateActionResultsMessageTypeDef",
     {
         "ProcessedUpdateActions": List[ProcessedUpdateActionTypeDef],
         "UnprocessedUpdateActions": List[UnprocessedUpdateActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserGroupResponseMetadataTypeDef = TypedDict(
     "UserGroupResponseMetadataTypeDef",
     {
         "UserGroupId": str,
         "Status": str,
         "Engine": str,
         "UserIds": List[str],
         "MinimumEngineVersion": str,
         "PendingChanges": UserGroupPendingChangesTypeDef,
         "ReplicationGroups": List[str],
         "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserGroupTypeDef = TypedDict(
     "UserGroupTypeDef",
     {
         "UserGroupId": str,
@@ -2202,15 +2203,15 @@
 )
 
 DescribeUsersResultTypeDef = TypedDict(
     "DescribeUsersResultTypeDef",
     {
         "Users": List[UserTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodeGroupTypeDef = TypedDict(
     "NodeGroupTypeDef",
     {
         "NodeGroupId": str,
@@ -2225,15 +2226,15 @@
 
 CacheParameterGroupDetailsTypeDef = TypedDict(
     "CacheParameterGroupDetailsTypeDef",
     {
         "Marker": str,
         "Parameters": List[ParameterTypeDef],
         "CacheNodeTypeSpecificParameters": List[CacheNodeTypeSpecificParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EngineDefaultsTypeDef = TypedDict(
     "EngineDefaultsTypeDef",
     {
         "CacheParameterGroupFamily": str,
@@ -2244,40 +2245,40 @@
     total=False,
 )
 
 AuthorizeCacheSecurityGroupIngressResultTypeDef = TypedDict(
     "AuthorizeCacheSecurityGroupIngressResultTypeDef",
     {
         "CacheSecurityGroup": CacheSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSecurityGroupMessageTypeDef = TypedDict(
     "CacheSecurityGroupMessageTypeDef",
     {
         "Marker": str,
         "CacheSecurityGroups": List[CacheSecurityGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheSecurityGroupResultTypeDef = TypedDict(
     "CreateCacheSecurityGroupResultTypeDef",
     {
         "CacheSecurityGroup": CacheSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RevokeCacheSecurityGroupIngressResultTypeDef = TypedDict(
     "RevokeCacheSecurityGroupIngressResultTypeDef",
     {
         "CacheSecurityGroup": CacheSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SnapshotTypeDef = TypedDict(
     "SnapshotTypeDef",
     {
         "SnapshotName": str,
@@ -2348,80 +2349,80 @@
     total=False,
 )
 
 CreateGlobalReplicationGroupResultTypeDef = TypedDict(
     "CreateGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DecreaseNodeGroupsInGlobalReplicationGroupResultTypeDef = TypedDict(
     "DecreaseNodeGroupsInGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGlobalReplicationGroupResultTypeDef = TypedDict(
     "DeleteGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGlobalReplicationGroupsResultTypeDef = TypedDict(
     "DescribeGlobalReplicationGroupsResultTypeDef",
     {
         "Marker": str,
         "GlobalReplicationGroups": List[GlobalReplicationGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateGlobalReplicationGroupResultTypeDef = TypedDict(
     "DisassociateGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverGlobalReplicationGroupResultTypeDef = TypedDict(
     "FailoverGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IncreaseNodeGroupsInGlobalReplicationGroupResultTypeDef = TypedDict(
     "IncreaseNodeGroupsInGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyGlobalReplicationGroupResultTypeDef = TypedDict(
     "ModifyGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebalanceSlotsInGlobalReplicationGroupResultTypeDef = TypedDict(
     "RebalanceSlotsInGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIncreaseNodeGroupsInGlobalReplicationGroupMessageRequestTypeDef = TypedDict(
     "_RequiredIncreaseNodeGroupsInGlobalReplicationGroupMessageRequestTypeDef",
     {
         "GlobalReplicationGroupId": str,
@@ -2469,33 +2470,33 @@
     total=False,
 )
 
 PurchaseReservedCacheNodesOfferingResultTypeDef = TypedDict(
     "PurchaseReservedCacheNodesOfferingResultTypeDef",
     {
         "ReservedCacheNode": ReservedCacheNodeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedCacheNodeMessageTypeDef = TypedDict(
     "ReservedCacheNodeMessageTypeDef",
     {
         "Marker": str,
         "ReservedCacheNodes": List[ReservedCacheNodeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedCacheNodesOfferingMessageTypeDef = TypedDict(
     "ReservedCacheNodesOfferingMessageTypeDef",
     {
         "Marker": str,
         "ReservedCacheNodesOfferings": List[ReservedCacheNodesOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSubnetGroupTypeDef = TypedDict(
     "CacheSubnetGroupTypeDef",
     {
         "CacheSubnetGroupName": str,
@@ -2509,56 +2510,56 @@
 )
 
 DescribeUserGroupsResultTypeDef = TypedDict(
     "DescribeUserGroupsResultTypeDef",
     {
         "UserGroups": List[UserGroupTypeDef],
         "Marker": str,
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
 
 CopySnapshotResultTypeDef = TypedDict(
     "CopySnapshotResultTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResultTypeDef = TypedDict(
     "CreateSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSnapshotResultTypeDef = TypedDict(
     "DeleteSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsListMessageTypeDef = TypedDict(
     "DescribeSnapshotsListMessageTypeDef",
     {
         "Marker": str,
         "Snapshots": List[SnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCacheClusterMessageRequestTypeDef = TypedDict(
     "_RequiredCreateCacheClusterMessageRequestTypeDef",
     {
         "CacheClusterId": str,
@@ -2649,14 +2650,15 @@
         "KmsKeyId": str,
         "UserGroupIds": Sequence[str],
         "LogDeliveryConfigurations": Sequence[LogDeliveryConfigurationRequestTypeDef],
         "DataTieringEnabled": bool,
         "NetworkType": NetworkTypeType,
         "IpDiscovery": IpDiscoveryType,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 
 class CreateReplicationGroupMessageRequestTypeDef(
     _RequiredCreateReplicationGroupMessageRequestTypeDef,
@@ -2738,14 +2740,15 @@
         "UserGroupIdsToAdd": Sequence[str],
         "UserGroupIdsToRemove": Sequence[str],
         "RemoveUserGroups": bool,
         "LogDeliveryConfigurations": Sequence[LogDeliveryConfigurationRequestTypeDef],
         "IpDiscovery": IpDiscoveryType,
         "TransitEncryptionEnabled": bool,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 
 class ModifyReplicationGroupMessageRequestTypeDef(
     _RequiredModifyReplicationGroupMessageRequestTypeDef,
@@ -2776,49 +2779,50 @@
         "AutomaticFailoverStatus": PendingAutomaticFailoverStatusType,
         "Resharding": ReshardingStatusTypeDef,
         "AuthTokenStatus": AuthTokenUpdateStatusType,
         "UserGroups": UserGroupsUpdateStatusTypeDef,
         "LogDeliveryConfigurations": List[PendingLogDeliveryConfigurationTypeDef],
         "TransitEncryptionEnabled": bool,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 UpdateActionsMessageTypeDef = TypedDict(
     "UpdateActionsMessageTypeDef",
     {
         "Marker": str,
         "UpdateActions": List[UpdateActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSubnetGroupMessageTypeDef = TypedDict(
     "CacheSubnetGroupMessageTypeDef",
     {
         "Marker": str,
         "CacheSubnetGroups": List[CacheSubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheSubnetGroupResultTypeDef = TypedDict(
     "CreateCacheSubnetGroupResultTypeDef",
     {
         "CacheSubnetGroup": CacheSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyCacheSubnetGroupResultTypeDef = TypedDict(
     "ModifyCacheSubnetGroupResultTypeDef",
     {
         "CacheSubnetGroup": CacheSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheClusterTypeDef = TypedDict(
     "CacheClusterTypeDef",
     {
         "CacheClusterId": str,
@@ -2887,132 +2891,133 @@
         "LogDeliveryConfigurations": List[LogDeliveryConfigurationTypeDef],
         "ReplicationGroupCreateTime": datetime,
         "DataTiering": DataTieringStatusType,
         "AutoMinorVersionUpgrade": bool,
         "NetworkType": NetworkTypeType,
         "IpDiscovery": IpDiscoveryType,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 CacheClusterMessageTypeDef = TypedDict(
     "CacheClusterMessageTypeDef",
     {
         "Marker": str,
         "CacheClusters": List[CacheClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheClusterResultTypeDef = TypedDict(
     "CreateCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCacheClusterResultTypeDef = TypedDict(
     "DeleteCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyCacheClusterResultTypeDef = TypedDict(
     "ModifyCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootCacheClusterResultTypeDef = TypedDict(
     "RebootCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CompleteMigrationResponseTypeDef = TypedDict(
     "CompleteMigrationResponseTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReplicationGroupResultTypeDef = TypedDict(
     "CreateReplicationGroupResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DecreaseReplicaCountResultTypeDef = TypedDict(
     "DecreaseReplicaCountResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationGroupResultTypeDef = TypedDict(
     "DeleteReplicationGroupResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IncreaseReplicaCountResultTypeDef = TypedDict(
     "IncreaseReplicaCountResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationGroupResultTypeDef = TypedDict(
     "ModifyReplicationGroupResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationGroupShardConfigurationResultTypeDef = TypedDict(
     "ModifyReplicationGroupShardConfigurationResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationGroupMessageTypeDef = TypedDict(
     "ReplicationGroupMessageTypeDef",
     {
         "Marker": str,
         "ReplicationGroups": List[ReplicationGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMigrationResponseTypeDef = TypedDict(
     "StartMigrationResponseTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestFailoverResultTypeDef = TypedDict(
     "TestFailoverResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/type_defs.pyi` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from .literals import (
     AuthenticationTypeType,
     AuthTokenUpdateStatusType,
     AuthTokenUpdateStrategyTypeType,
     AutomaticFailoverStatusType,
     AZModeType,
     ChangeTypeType,
+    ClusterModeType,
     DataTieringStatusType,
     DestinationTypeType,
     InputAuthenticationTypeType,
     IpDiscoveryType,
     LogDeliveryConfigurationStatusType,
     LogFormatType,
     LogTypeType,
@@ -50,15 +51,15 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "AllowedNodeTypeModificationsMessageTypeDef",
     "AuthenticationModeTypeDef",
     "AuthenticationTypeDef",
     "AuthorizeCacheSecurityGroupIngressMessageRequestTypeDef",
     "AvailabilityZoneTypeDef",
     "BatchApplyUpdateActionMessageRequestTypeDef",
     "BatchStopUpdateActionMessageRequestTypeDef",
     "CacheParameterGroupStatusTypeDef",
@@ -66,14 +67,15 @@
     "EndpointTypeDef",
     "NotificationConfigurationTypeDef",
     "SecurityGroupMembershipTypeDef",
     "CacheEngineVersionTypeDef",
     "CacheNodeTypeSpecificValueTypeDef",
     "CacheNodeUpdateStatusTypeDef",
     "ParameterTypeDef",
+    "CacheParameterGroupNameMessageTypeDef",
     "CacheParameterGroupTypeDef",
     "EC2SecurityGroupTypeDef",
     "CloudWatchLogsDestinationDetailsTypeDef",
     "CompleteMigrationMessageRequestTypeDef",
     "ConfigureShardTypeDef",
     "CreateGlobalReplicationGroupMessageRequestTypeDef",
     "NodeGroupConfigurationTypeDef",
@@ -85,71 +87,85 @@
     "DeleteCacheSubnetGroupMessageRequestTypeDef",
     "DeleteGlobalReplicationGroupMessageRequestTypeDef",
     "DeleteReplicationGroupMessageRequestTypeDef",
     "DeleteSnapshotMessageRequestTypeDef",
     "DeleteUserGroupMessageRequestTypeDef",
     "DeleteUserMessageRequestTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
     "DescribeCacheClustersMessageRequestTypeDef",
+    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
     "DescribeCacheEngineVersionsMessageRequestTypeDef",
+    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
     "DescribeCacheParameterGroupsMessageRequestTypeDef",
+    "DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
     "DescribeCacheParametersMessageRequestTypeDef",
+    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
     "DescribeCacheSecurityGroupsMessageRequestTypeDef",
+    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
     "DescribeCacheSubnetGroupsMessageRequestTypeDef",
+    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
     "DescribeEngineDefaultParametersMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
     "DescribeGlobalReplicationGroupsMessageRequestTypeDef",
+    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
     "DescribeReplicationGroupsMessageRequestTypeDef",
+    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
     "DescribeReservedCacheNodesMessageRequestTypeDef",
+    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
     "DescribeReservedCacheNodesOfferingsMessageRequestTypeDef",
+    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
     "DescribeServiceUpdatesMessageRequestTypeDef",
+    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
     "DescribeSnapshotsMessageRequestTypeDef",
     "TimeRangeFilterTypeDef",
+    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
     "DescribeUserGroupsMessageRequestTypeDef",
     "FilterTypeDef",
     "KinesisFirehoseDestinationDetailsTypeDef",
     "DisassociateGlobalReplicationGroupMessageRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventTypeDef",
     "FailoverGlobalReplicationGroupMessageRequestTypeDef",
     "GlobalNodeGroupTypeDef",
     "GlobalReplicationGroupInfoTypeDef",
     "GlobalReplicationGroupMemberTypeDef",
     "ListAllowedNodeTypeModificationsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
     "ParameterNameValueTypeDef",
     "ModifyCacheSubnetGroupMessageRequestTypeDef",
     "ModifyGlobalReplicationGroupMessageRequestTypeDef",
     "ReshardingConfigurationTypeDef",
     "ModifyUserGroupMessageRequestTypeDef",
     "NodeGroupMemberUpdateStatusTypeDef",
+    "PaginatorConfigTypeDef",
     "ProcessedUpdateActionTypeDef",
     "RebalanceSlotsInGlobalReplicationGroupMessageRequestTypeDef",
     "RebootCacheClusterMessageRequestTypeDef",
     "RecurringChargeTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
     "UserGroupsUpdateStatusTypeDef",
     "SlotMigrationTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeCacheSecurityGroupIngressMessageRequestTypeDef",
     "ServiceUpdateTypeDef",
     "SubnetOutpostTypeDef",
     "TestFailoverMessageRequestTypeDef",
     "UnprocessedUpdateActionTypeDef",
     "UserGroupPendingChangesTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CopySnapshotMessageRequestTypeDef",
     "CreateCacheParameterGroupMessageRequestTypeDef",
     "CreateCacheSecurityGroupMessageRequestTypeDef",
     "CreateCacheSubnetGroupMessageRequestTypeDef",
     "CreateSnapshotMessageRequestTypeDef",
     "CreateUserGroupMessageRequestTypeDef",
     "PurchaseReservedCacheNodesOfferingMessageRequestTypeDef",
-    "AllowedNodeTypeModificationsMessageTypeDef",
-    "CacheParameterGroupNameMessageTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "TagListMessageTypeDef",
     "CreateUserMessageRequestTypeDef",
     "ModifyUserMessageRequestTypeDef",
     "UserResponseMetadataTypeDef",
     "UserTypeDef",
     "CacheNodeTypeDef",
     "NodeGroupMemberTypeDef",
@@ -162,29 +178,14 @@
     "IncreaseReplicaCountMessageRequestTypeDef",
     "NodeSnapshotTypeDef",
     "StartMigrationMessageRequestTypeDef",
     "DescribeCacheClustersMessageCacheClusterAvailableWaitTypeDef",
     "DescribeCacheClustersMessageCacheClusterDeletedWaitTypeDef",
     "DescribeReplicationGroupsMessageReplicationGroupAvailableWaitTypeDef",
     "DescribeReplicationGroupsMessageReplicationGroupDeletedWaitTypeDef",
-    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
-    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
-    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
-    "DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
-    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
-    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
-    "DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
-    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
-    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
-    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
-    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
-    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
-    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
     "DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef",
     "DescribeUpdateActionsMessageRequestTypeDef",
     "DescribeUsersMessageDescribeUsersPaginateTypeDef",
     "DescribeUsersMessageRequestTypeDef",
     "DestinationDetailsTypeDef",
     "EventsMessageTypeDef",
     "GlobalReplicationGroupTypeDef",
@@ -268,22 +269,20 @@
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AllowedNodeTypeModificationsMessageTypeDef = TypedDict(
+    "AllowedNodeTypeModificationsMessageTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScaleUpModifications": List[str],
+        "ScaleDownModifications": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthenticationModeTypeDef = TypedDict(
     "AuthenticationModeTypeDef",
     {
         "Type": InputAuthenticationTypeType,
@@ -454,14 +453,22 @@
         "IsModifiable": bool,
         "MinimumEngineVersion": str,
         "ChangeType": ChangeTypeType,
     },
     total=False,
 )
 
+CacheParameterGroupNameMessageTypeDef = TypedDict(
+    "CacheParameterGroupNameMessageTypeDef",
+    {
+        "CacheParameterGroupName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CacheParameterGroupTypeDef = TypedDict(
     "CacheParameterGroupTypeDef",
     {
         "CacheParameterGroupName": str,
         "CacheParameterGroupFamily": str,
         "Description": str,
         "IsGlobal": bool,
@@ -689,20 +696,21 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef = TypedDict(
+    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CacheClusterId": str,
+        "ShowCacheNodeInfo": bool,
+        "ShowCacheClustersNotInReplicationGroups": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeCacheClustersMessageRequestTypeDef = TypedDict(
     "DescribeCacheClustersMessageRequestTypeDef",
     {
@@ -711,37 +719,79 @@
         "Marker": str,
         "ShowCacheNodeInfo": bool,
         "ShowCacheClustersNotInReplicationGroups": bool,
     },
     total=False,
 )
 
+DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef = TypedDict(
+    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
+    {
+        "Engine": str,
+        "EngineVersion": str,
+        "CacheParameterGroupFamily": str,
+        "DefaultOnly": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheEngineVersionsMessageRequestTypeDef = TypedDict(
     "DescribeCacheEngineVersionsMessageRequestTypeDef",
     {
         "Engine": str,
         "EngineVersion": str,
         "CacheParameterGroupFamily": str,
         "MaxRecords": int,
         "Marker": str,
         "DefaultOnly": bool,
     },
     total=False,
 )
 
+DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
+    {
+        "CacheParameterGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheParameterGroupsMessageRequestTypeDef = TypedDict(
     "DescribeCacheParameterGroupsMessageRequestTypeDef",
     {
         "CacheParameterGroupName": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
+    {
+        "CacheParameterGroupName": str,
+    },
+)
+_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
+    {
+        "Source": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef(
+    _RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
+    _OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeCacheParametersMessageRequestTypeDef = TypedDict(
     "_RequiredDescribeCacheParametersMessageRequestTypeDef",
     {
         "CacheParameterGroupName": str,
     },
 )
 _OptionalDescribeCacheParametersMessageRequestTypeDef = TypedDict(
@@ -756,34 +806,72 @@
 
 class DescribeCacheParametersMessageRequestTypeDef(
     _RequiredDescribeCacheParametersMessageRequestTypeDef,
     _OptionalDescribeCacheParametersMessageRequestTypeDef,
 ):
     pass
 
+DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef = TypedDict(
+    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
+    {
+        "CacheSecurityGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheSecurityGroupsMessageRequestTypeDef = TypedDict(
     "DescribeCacheSecurityGroupsMessageRequestTypeDef",
     {
         "CacheSecurityGroupName": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
+    {
+        "CacheSubnetGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeCacheSubnetGroupsMessageRequestTypeDef = TypedDict(
     "DescribeCacheSubnetGroupsMessageRequestTypeDef",
     {
         "CacheSubnetGroupName": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
+    {
+        "CacheParameterGroupFamily": str,
+    },
+)
+_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
+    {
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
         "CacheParameterGroupFamily": str,
     },
 )
 _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef = TypedDict(
@@ -797,49 +885,95 @@
 
 class DescribeEngineDefaultParametersMessageRequestTypeDef(
     _RequiredDescribeEngineDefaultParametersMessageRequestTypeDef,
     _OptionalDescribeEngineDefaultParametersMessageRequestTypeDef,
 ):
     pass
 
+DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+    {
+        "SourceIdentifier": str,
+        "SourceType": SourceTypeType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
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
         "Duration": int,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef = TypedDict(
+    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
+    {
+        "GlobalReplicationGroupId": str,
+        "ShowMemberInfo": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGlobalReplicationGroupsMessageRequestTypeDef = TypedDict(
     "DescribeGlobalReplicationGroupsMessageRequestTypeDef",
     {
         "GlobalReplicationGroupId": str,
         "MaxRecords": int,
         "Marker": str,
         "ShowMemberInfo": bool,
     },
     total=False,
 )
 
+DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef = TypedDict(
+    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
+    {
+        "ReplicationGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReplicationGroupsMessageRequestTypeDef = TypedDict(
     "DescribeReplicationGroupsMessageRequestTypeDef",
     {
         "ReplicationGroupId": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef = TypedDict(
+    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
+    {
+        "ReservedCacheNodeId": str,
+        "ReservedCacheNodesOfferingId": str,
+        "CacheNodeType": str,
+        "Duration": str,
+        "ProductDescription": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedCacheNodesMessageRequestTypeDef = TypedDict(
     "DescribeReservedCacheNodesMessageRequestTypeDef",
     {
         "ReservedCacheNodeId": str,
         "ReservedCacheNodesOfferingId": str,
         "CacheNodeType": str,
         "Duration": str,
@@ -847,39 +981,75 @@
         "OfferingType": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef = TypedDict(
+    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
+    {
+        "ReservedCacheNodesOfferingId": str,
+        "CacheNodeType": str,
+        "Duration": str,
+        "ProductDescription": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedCacheNodesOfferingsMessageRequestTypeDef = TypedDict(
     "DescribeReservedCacheNodesOfferingsMessageRequestTypeDef",
     {
         "ReservedCacheNodesOfferingId": str,
         "CacheNodeType": str,
         "Duration": str,
         "ProductDescription": str,
         "OfferingType": str,
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef = TypedDict(
+    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
+    {
+        "ServiceUpdateName": str,
+        "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeServiceUpdatesMessageRequestTypeDef = TypedDict(
     "DescribeServiceUpdatesMessageRequestTypeDef",
     {
         "ServiceUpdateName": str,
         "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
         "MaxRecords": int,
         "Marker": str,
     },
     total=False,
 )
 
+DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
+    {
+        "ReplicationGroupId": str,
+        "CacheClusterId": str,
+        "SnapshotName": str,
+        "SnapshotSource": str,
+        "ShowNodeGroupConfig": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSnapshotsMessageRequestTypeDef = TypedDict(
     "DescribeSnapshotsMessageRequestTypeDef",
     {
         "ReplicationGroupId": str,
         "CacheClusterId": str,
         "SnapshotName": str,
         "SnapshotSource": str,
@@ -895,14 +1065,23 @@
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
     },
     total=False,
 )
 
+DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef = TypedDict(
+    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
+    {
+        "UserGroupId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeUserGroupsMessageRequestTypeDef = TypedDict(
     "DescribeUserGroupsMessageRequestTypeDef",
     {
         "UserGroupId": str,
         "MaxRecords": int,
         "Marker": str,
     },
@@ -930,14 +1109,21 @@
     {
         "GlobalReplicationGroupId": str,
         "ReplicationGroupId": str,
         "ReplicationGroupRegion": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventTypeDef = TypedDict(
     "EventTypeDef",
     {
         "SourceIdentifier": str,
         "SourceType": SourceTypeType,
         "Message": str,
         "Date": datetime,
@@ -1096,14 +1282,24 @@
         "NodeUpdateInitiatedBy": NodeUpdateInitiatedByType,
         "NodeUpdateInitiatedDate": datetime,
         "NodeUpdateStatusModifiedDate": datetime,
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
 ProcessedUpdateActionTypeDef = TypedDict(
     "ProcessedUpdateActionTypeDef",
     {
         "ReplicationGroupId": str,
         "CacheClusterId": str,
         "ServiceUpdateName": str,
         "UpdateActionStatus": UpdateActionStatusType,
@@ -1157,14 +1353,25 @@
     "SlotMigrationTypeDef",
     {
         "ProgressPercentage": float,
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
 RevokeCacheSecurityGroupIngressMessageRequestTypeDef = TypedDict(
     "RevokeCacheSecurityGroupIngressMessageRequestTypeDef",
     {
         "CacheSecurityGroupName": str,
         "EC2SecurityGroupName": str,
         "EC2SecurityGroupOwnerId": str,
     },
@@ -1382,43 +1589,19 @@
 
 class PurchaseReservedCacheNodesOfferingMessageRequestTypeDef(
     _RequiredPurchaseReservedCacheNodesOfferingMessageRequestTypeDef,
     _OptionalPurchaseReservedCacheNodesOfferingMessageRequestTypeDef,
 ):
     pass
 
-AllowedNodeTypeModificationsMessageTypeDef = TypedDict(
-    "AllowedNodeTypeModificationsMessageTypeDef",
-    {
-        "ScaleUpModifications": List[str],
-        "ScaleDownModifications": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CacheParameterGroupNameMessageTypeDef = TypedDict(
-    "CacheParameterGroupNameMessageTypeDef",
-    {
-        "CacheParameterGroupName": str,
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
 TagListMessageTypeDef = TypedDict(
     "TagListMessageTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserMessageRequestTypeDef = TypedDict(
     "_RequiredCreateUserMessageRequestTypeDef",
     {
         "UserId": str,
@@ -1474,15 +1657,15 @@
         "Status": str,
         "Engine": str,
         "MinimumEngineVersion": str,
         "AccessString": str,
         "UserGroupIds": List[str],
         "Authentication": AuthenticationTypeDef,
         "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserTypeDef = TypedDict(
     "UserTypeDef",
     {
         "UserId": str,
@@ -1527,15 +1710,15 @@
 )
 
 CacheEngineVersionMessageTypeDef = TypedDict(
     "CacheEngineVersionMessageTypeDef",
     {
         "Marker": str,
         "CacheEngineVersions": List[CacheEngineVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheNodeTypeSpecificParameterTypeDef = TypedDict(
     "CacheNodeTypeSpecificParameterTypeDef",
     {
         "ParameterName": str,
@@ -1552,23 +1735,23 @@
 )
 
 CacheParameterGroupsMessageTypeDef = TypedDict(
     "CacheParameterGroupsMessageTypeDef",
     {
         "Marker": str,
         "CacheParameterGroups": List[CacheParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheParameterGroupResultTypeDef = TypedDict(
     "CreateCacheParameterGroupResultTypeDef",
     {
         "CacheParameterGroup": CacheParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSecurityGroupTypeDef = TypedDict(
     "CacheSecurityGroupTypeDef",
     {
         "OwnerId": str,
@@ -1691,208 +1874,26 @@
         "MaxRecords": int,
         "Marker": str,
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef = TypedDict(
-    "DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef",
-    {
-        "CacheClusterId": str,
-        "ShowCacheNodeInfo": bool,
-        "ShowCacheClustersNotInReplicationGroups": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef = TypedDict(
-    "DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef",
-    {
-        "Engine": str,
-        "EngineVersion": str,
-        "CacheParameterGroupFamily": str,
-        "DefaultOnly": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef",
-    {
-        "CacheParameterGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
-    {
-        "CacheParameterGroupName": str,
-    },
-)
-_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef",
-    {
-        "Source": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef(
-    _RequiredDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
-    _OptionalDescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
-):
-    pass
-
-DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef = TypedDict(
-    "DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef",
-    {
-        "CacheSecurityGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef",
-    {
-        "CacheSubnetGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    {
-        "CacheParameterGroupFamily": str,
-    },
-)
-_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef",
-    {
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
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    {
-        "SourceIdentifier": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef = TypedDict(
-    "DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef",
-    {
-        "GlobalReplicationGroupId": str,
-        "ShowMemberInfo": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef = TypedDict(
-    "DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef",
-    {
-        "ReplicationGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef = TypedDict(
-    "DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef",
-    {
-        "ReservedCacheNodeId": str,
-        "ReservedCacheNodesOfferingId": str,
-        "CacheNodeType": str,
-        "Duration": str,
-        "ProductDescription": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef = TypedDict(
-    "DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef",
-    {
-        "ReservedCacheNodesOfferingId": str,
-        "CacheNodeType": str,
-        "Duration": str,
-        "ProductDescription": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef = TypedDict(
-    "DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef",
-    {
-        "ServiceUpdateName": str,
-        "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef",
-    {
-        "ReplicationGroupId": str,
-        "CacheClusterId": str,
-        "SnapshotName": str,
-        "SnapshotSource": str,
-        "ShowNodeGroupConfig": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef = TypedDict(
-    "DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef",
-    {
-        "UserGroupId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef = TypedDict(
     "DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef",
     {
         "ServiceUpdateName": str,
         "ReplicationGroupIds": Sequence[str],
         "CacheClusterIds": Sequence[str],
         "Engine": str,
         "ServiceUpdateStatus": Sequence[ServiceUpdateStatusType],
         "ServiceUpdateTimeRange": TimeRangeFilterTypeDef,
         "UpdateActionStatus": Sequence[UpdateActionStatusType],
         "ShowNodeLevelUpdateStatus": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeUpdateActionsMessageRequestTypeDef = TypedDict(
     "DescribeUpdateActionsMessageRequestTypeDef",
     {
@@ -1912,15 +1913,15 @@
 
 DescribeUsersMessageDescribeUsersPaginateTypeDef = TypedDict(
     "DescribeUsersMessageDescribeUsersPaginateTypeDef",
     {
         "Engine": str,
         "UserId": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeUsersMessageRequestTypeDef = TypedDict(
     "DescribeUsersMessageRequestTypeDef",
     {
@@ -1943,15 +1944,15 @@
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
 
 GlobalReplicationGroupTypeDef = TypedDict(
     "GlobalReplicationGroupTypeDef",
     {
         "GlobalReplicationGroupId": str,
@@ -2086,15 +2087,15 @@
 )
 
 ServiceUpdatesMessageTypeDef = TypedDict(
     "ServiceUpdatesMessageTypeDef",
     {
         "Marker": str,
         "ServiceUpdates": List[ServiceUpdateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubnetTypeDef = TypedDict(
     "SubnetTypeDef",
     {
         "SubnetIdentifier": str,
@@ -2106,30 +2107,30 @@
 )
 
 UpdateActionResultsMessageTypeDef = TypedDict(
     "UpdateActionResultsMessageTypeDef",
     {
         "ProcessedUpdateActions": List[ProcessedUpdateActionTypeDef],
         "UnprocessedUpdateActions": List[UnprocessedUpdateActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserGroupResponseMetadataTypeDef = TypedDict(
     "UserGroupResponseMetadataTypeDef",
     {
         "UserGroupId": str,
         "Status": str,
         "Engine": str,
         "UserIds": List[str],
         "MinimumEngineVersion": str,
         "PendingChanges": UserGroupPendingChangesTypeDef,
         "ReplicationGroups": List[str],
         "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserGroupTypeDef = TypedDict(
     "UserGroupTypeDef",
     {
         "UserGroupId": str,
@@ -2145,15 +2146,15 @@
 )
 
 DescribeUsersResultTypeDef = TypedDict(
     "DescribeUsersResultTypeDef",
     {
         "Users": List[UserTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodeGroupTypeDef = TypedDict(
     "NodeGroupTypeDef",
     {
         "NodeGroupId": str,
@@ -2168,15 +2169,15 @@
 
 CacheParameterGroupDetailsTypeDef = TypedDict(
     "CacheParameterGroupDetailsTypeDef",
     {
         "Marker": str,
         "Parameters": List[ParameterTypeDef],
         "CacheNodeTypeSpecificParameters": List[CacheNodeTypeSpecificParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EngineDefaultsTypeDef = TypedDict(
     "EngineDefaultsTypeDef",
     {
         "CacheParameterGroupFamily": str,
@@ -2187,40 +2188,40 @@
     total=False,
 )
 
 AuthorizeCacheSecurityGroupIngressResultTypeDef = TypedDict(
     "AuthorizeCacheSecurityGroupIngressResultTypeDef",
     {
         "CacheSecurityGroup": CacheSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSecurityGroupMessageTypeDef = TypedDict(
     "CacheSecurityGroupMessageTypeDef",
     {
         "Marker": str,
         "CacheSecurityGroups": List[CacheSecurityGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheSecurityGroupResultTypeDef = TypedDict(
     "CreateCacheSecurityGroupResultTypeDef",
     {
         "CacheSecurityGroup": CacheSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RevokeCacheSecurityGroupIngressResultTypeDef = TypedDict(
     "RevokeCacheSecurityGroupIngressResultTypeDef",
     {
         "CacheSecurityGroup": CacheSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SnapshotTypeDef = TypedDict(
     "SnapshotTypeDef",
     {
         "SnapshotName": str,
@@ -2291,80 +2292,80 @@
     total=False,
 )
 
 CreateGlobalReplicationGroupResultTypeDef = TypedDict(
     "CreateGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DecreaseNodeGroupsInGlobalReplicationGroupResultTypeDef = TypedDict(
     "DecreaseNodeGroupsInGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGlobalReplicationGroupResultTypeDef = TypedDict(
     "DeleteGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGlobalReplicationGroupsResultTypeDef = TypedDict(
     "DescribeGlobalReplicationGroupsResultTypeDef",
     {
         "Marker": str,
         "GlobalReplicationGroups": List[GlobalReplicationGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateGlobalReplicationGroupResultTypeDef = TypedDict(
     "DisassociateGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverGlobalReplicationGroupResultTypeDef = TypedDict(
     "FailoverGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IncreaseNodeGroupsInGlobalReplicationGroupResultTypeDef = TypedDict(
     "IncreaseNodeGroupsInGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyGlobalReplicationGroupResultTypeDef = TypedDict(
     "ModifyGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebalanceSlotsInGlobalReplicationGroupResultTypeDef = TypedDict(
     "RebalanceSlotsInGlobalReplicationGroupResultTypeDef",
     {
         "GlobalReplicationGroup": GlobalReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIncreaseNodeGroupsInGlobalReplicationGroupMessageRequestTypeDef = TypedDict(
     "_RequiredIncreaseNodeGroupsInGlobalReplicationGroupMessageRequestTypeDef",
     {
         "GlobalReplicationGroupId": str,
@@ -2410,33 +2411,33 @@
     total=False,
 )
 
 PurchaseReservedCacheNodesOfferingResultTypeDef = TypedDict(
     "PurchaseReservedCacheNodesOfferingResultTypeDef",
     {
         "ReservedCacheNode": ReservedCacheNodeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedCacheNodeMessageTypeDef = TypedDict(
     "ReservedCacheNodeMessageTypeDef",
     {
         "Marker": str,
         "ReservedCacheNodes": List[ReservedCacheNodeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReservedCacheNodesOfferingMessageTypeDef = TypedDict(
     "ReservedCacheNodesOfferingMessageTypeDef",
     {
         "Marker": str,
         "ReservedCacheNodesOfferings": List[ReservedCacheNodesOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSubnetGroupTypeDef = TypedDict(
     "CacheSubnetGroupTypeDef",
     {
         "CacheSubnetGroupName": str,
@@ -2450,56 +2451,56 @@
 )
 
 DescribeUserGroupsResultTypeDef = TypedDict(
     "DescribeUserGroupsResultTypeDef",
     {
         "UserGroups": List[UserGroupTypeDef],
         "Marker": str,
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
 
 CopySnapshotResultTypeDef = TypedDict(
     "CopySnapshotResultTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResultTypeDef = TypedDict(
     "CreateSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSnapshotResultTypeDef = TypedDict(
     "DeleteSnapshotResultTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsListMessageTypeDef = TypedDict(
     "DescribeSnapshotsListMessageTypeDef",
     {
         "Marker": str,
         "Snapshots": List[SnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCacheClusterMessageRequestTypeDef = TypedDict(
     "_RequiredCreateCacheClusterMessageRequestTypeDef",
     {
         "CacheClusterId": str,
@@ -2588,14 +2589,15 @@
         "KmsKeyId": str,
         "UserGroupIds": Sequence[str],
         "LogDeliveryConfigurations": Sequence[LogDeliveryConfigurationRequestTypeDef],
         "DataTieringEnabled": bool,
         "NetworkType": NetworkTypeType,
         "IpDiscovery": IpDiscoveryType,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 class CreateReplicationGroupMessageRequestTypeDef(
     _RequiredCreateReplicationGroupMessageRequestTypeDef,
     _OptionalCreateReplicationGroupMessageRequestTypeDef,
@@ -2673,14 +2675,15 @@
         "UserGroupIdsToAdd": Sequence[str],
         "UserGroupIdsToRemove": Sequence[str],
         "RemoveUserGroups": bool,
         "LogDeliveryConfigurations": Sequence[LogDeliveryConfigurationRequestTypeDef],
         "IpDiscovery": IpDiscoveryType,
         "TransitEncryptionEnabled": bool,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 class ModifyReplicationGroupMessageRequestTypeDef(
     _RequiredModifyReplicationGroupMessageRequestTypeDef,
     _OptionalModifyReplicationGroupMessageRequestTypeDef,
@@ -2709,49 +2712,50 @@
         "AutomaticFailoverStatus": PendingAutomaticFailoverStatusType,
         "Resharding": ReshardingStatusTypeDef,
         "AuthTokenStatus": AuthTokenUpdateStatusType,
         "UserGroups": UserGroupsUpdateStatusTypeDef,
         "LogDeliveryConfigurations": List[PendingLogDeliveryConfigurationTypeDef],
         "TransitEncryptionEnabled": bool,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 UpdateActionsMessageTypeDef = TypedDict(
     "UpdateActionsMessageTypeDef",
     {
         "Marker": str,
         "UpdateActions": List[UpdateActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSubnetGroupMessageTypeDef = TypedDict(
     "CacheSubnetGroupMessageTypeDef",
     {
         "Marker": str,
         "CacheSubnetGroups": List[CacheSubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheSubnetGroupResultTypeDef = TypedDict(
     "CreateCacheSubnetGroupResultTypeDef",
     {
         "CacheSubnetGroup": CacheSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyCacheSubnetGroupResultTypeDef = TypedDict(
     "ModifyCacheSubnetGroupResultTypeDef",
     {
         "CacheSubnetGroup": CacheSubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheClusterTypeDef = TypedDict(
     "CacheClusterTypeDef",
     {
         "CacheClusterId": str,
@@ -2820,132 +2824,133 @@
         "LogDeliveryConfigurations": List[LogDeliveryConfigurationTypeDef],
         "ReplicationGroupCreateTime": datetime,
         "DataTiering": DataTieringStatusType,
         "AutoMinorVersionUpgrade": bool,
         "NetworkType": NetworkTypeType,
         "IpDiscovery": IpDiscoveryType,
         "TransitEncryptionMode": TransitEncryptionModeType,
+        "ClusterMode": ClusterModeType,
     },
     total=False,
 )
 
 CacheClusterMessageTypeDef = TypedDict(
     "CacheClusterMessageTypeDef",
     {
         "Marker": str,
         "CacheClusters": List[CacheClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCacheClusterResultTypeDef = TypedDict(
     "CreateCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCacheClusterResultTypeDef = TypedDict(
     "DeleteCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyCacheClusterResultTypeDef = TypedDict(
     "ModifyCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootCacheClusterResultTypeDef = TypedDict(
     "RebootCacheClusterResultTypeDef",
     {
         "CacheCluster": CacheClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CompleteMigrationResponseTypeDef = TypedDict(
     "CompleteMigrationResponseTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReplicationGroupResultTypeDef = TypedDict(
     "CreateReplicationGroupResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DecreaseReplicaCountResultTypeDef = TypedDict(
     "DecreaseReplicaCountResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteReplicationGroupResultTypeDef = TypedDict(
     "DeleteReplicationGroupResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IncreaseReplicaCountResultTypeDef = TypedDict(
     "IncreaseReplicaCountResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationGroupResultTypeDef = TypedDict(
     "ModifyReplicationGroupResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyReplicationGroupShardConfigurationResultTypeDef = TypedDict(
     "ModifyReplicationGroupShardConfigurationResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationGroupMessageTypeDef = TypedDict(
     "ReplicationGroupMessageTypeDef",
     {
         "Marker": str,
         "ReplicationGroups": List[ReplicationGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMigrationResponseTypeDef = TypedDict(
     "StartMigrationResponseTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestFailoverResultTypeDef = TypedDict(
     "TestFailoverResultTypeDef",
     {
         "ReplicationGroup": ReplicationGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/waiter.py` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache/waiter.pyi` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/PKG-INFO` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elasticache
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElastiCache 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElastiCache 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elasticache"></a>
 
 # types-aiobotocore-elasticache
 
 [![PyPI - types-aiobotocore-elasticache](https://img.shields.io/pypi/v/types-aiobotocore-elasticache.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticache)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elasticache.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticache)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elasticache?color=blue)](https://pypistats.org/packages/types-aiobotocore-elasticache)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElastiCache 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
+[aiobotocore.ElastiCache 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticache.html#ElastiCache)
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
 [types-aiobotocore-elasticache docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticache/).
 
 See how it helps to find and fix potential bugs:
 
@@ -403,14 +403,15 @@
     AuthTokenUpdateStatusType,
     AuthTokenUpdateStrategyTypeType,
     AuthenticationTypeType,
     AutomaticFailoverStatusType,
     CacheClusterAvailableWaiterName,
     CacheClusterDeletedWaiterName,
     ChangeTypeType,
+    ClusterModeType,
     DataTieringStatusType,
     DescribeCacheClustersPaginatorName,
     DescribeCacheEngineVersionsPaginatorName,
     DescribeCacheParameterGroupsPaginatorName,
     DescribeCacheParametersPaginatorName,
     DescribeCacheSecurityGroupsPaginatorName,
     DescribeCacheSubnetGroupsPaginatorName,
@@ -465,15 +466,15 @@
 
 `types_aiobotocore_elasticache.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elasticache.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    AllowedNodeTypeModificationsMessageTypeDef,
     AuthenticationModeTypeDef,
     AuthenticationTypeDef,
     AuthorizeCacheSecurityGroupIngressMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     BatchApplyUpdateActionMessageRequestTypeDef,
     BatchStopUpdateActionMessageRequestTypeDef,
     CacheParameterGroupStatusTypeDef,
@@ -481,14 +482,15 @@
     EndpointTypeDef,
     NotificationConfigurationTypeDef,
     SecurityGroupMembershipTypeDef,
     CacheEngineVersionTypeDef,
     CacheNodeTypeSpecificValueTypeDef,
     CacheNodeUpdateStatusTypeDef,
     ParameterTypeDef,
+    CacheParameterGroupNameMessageTypeDef,
     CacheParameterGroupTypeDef,
     EC2SecurityGroupTypeDef,
     CloudWatchLogsDestinationDetailsTypeDef,
     CompleteMigrationMessageRequestTypeDef,
     ConfigureShardTypeDef,
     CreateGlobalReplicationGroupMessageRequestTypeDef,
     NodeGroupConfigurationTypeDef,
@@ -500,71 +502,85 @@
     DeleteCacheSubnetGroupMessageRequestTypeDef,
     DeleteGlobalReplicationGroupMessageRequestTypeDef,
     DeleteReplicationGroupMessageRequestTypeDef,
     DeleteSnapshotMessageRequestTypeDef,
     DeleteUserGroupMessageRequestTypeDef,
     DeleteUserMessageRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef,
     DescribeCacheClustersMessageRequestTypeDef,
+    DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef,
     DescribeCacheEngineVersionsMessageRequestTypeDef,
+    DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef,
     DescribeCacheParameterGroupsMessageRequestTypeDef,
+    DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
     DescribeCacheParametersMessageRequestTypeDef,
+    DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef,
     DescribeCacheSecurityGroupsMessageRequestTypeDef,
+    DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef,
     DescribeCacheSubnetGroupsMessageRequestTypeDef,
+    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
     DescribeEngineDefaultParametersMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef,
     DescribeGlobalReplicationGroupsMessageRequestTypeDef,
+    DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef,
     DescribeReplicationGroupsMessageRequestTypeDef,
+    DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef,
     DescribeReservedCacheNodesMessageRequestTypeDef,
+    DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef,
     DescribeReservedCacheNodesOfferingsMessageRequestTypeDef,
+    DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef,
     DescribeServiceUpdatesMessageRequestTypeDef,
+    DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsMessageRequestTypeDef,
     TimeRangeFilterTypeDef,
+    DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef,
     DescribeUserGroupsMessageRequestTypeDef,
     FilterTypeDef,
     KinesisFirehoseDestinationDetailsTypeDef,
     DisassociateGlobalReplicationGroupMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventTypeDef,
     FailoverGlobalReplicationGroupMessageRequestTypeDef,
     GlobalNodeGroupTypeDef,
     GlobalReplicationGroupInfoTypeDef,
     GlobalReplicationGroupMemberTypeDef,
     ListAllowedNodeTypeModificationsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ParameterNameValueTypeDef,
     ModifyCacheSubnetGroupMessageRequestTypeDef,
     ModifyGlobalReplicationGroupMessageRequestTypeDef,
     ReshardingConfigurationTypeDef,
     ModifyUserGroupMessageRequestTypeDef,
     NodeGroupMemberUpdateStatusTypeDef,
+    PaginatorConfigTypeDef,
     ProcessedUpdateActionTypeDef,
     RebalanceSlotsInGlobalReplicationGroupMessageRequestTypeDef,
     RebootCacheClusterMessageRequestTypeDef,
     RecurringChargeTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
     UserGroupsUpdateStatusTypeDef,
     SlotMigrationTypeDef,
+    ResponseMetadataTypeDef,
     RevokeCacheSecurityGroupIngressMessageRequestTypeDef,
     ServiceUpdateTypeDef,
     SubnetOutpostTypeDef,
     TestFailoverMessageRequestTypeDef,
     UnprocessedUpdateActionTypeDef,
     UserGroupPendingChangesTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopySnapshotMessageRequestTypeDef,
     CreateCacheParameterGroupMessageRequestTypeDef,
     CreateCacheSecurityGroupMessageRequestTypeDef,
     CreateCacheSubnetGroupMessageRequestTypeDef,
     CreateSnapshotMessageRequestTypeDef,
     CreateUserGroupMessageRequestTypeDef,
     PurchaseReservedCacheNodesOfferingMessageRequestTypeDef,
-    AllowedNodeTypeModificationsMessageTypeDef,
-    CacheParameterGroupNameMessageTypeDef,
-    EmptyResponseMetadataTypeDef,
     TagListMessageTypeDef,
     CreateUserMessageRequestTypeDef,
     ModifyUserMessageRequestTypeDef,
     UserResponseMetadataTypeDef,
     UserTypeDef,
     CacheNodeTypeDef,
     NodeGroupMemberTypeDef,
@@ -577,29 +593,14 @@
     IncreaseReplicaCountMessageRequestTypeDef,
     NodeSnapshotTypeDef,
     StartMigrationMessageRequestTypeDef,
     DescribeCacheClustersMessageCacheClusterAvailableWaitTypeDef,
     DescribeCacheClustersMessageCacheClusterDeletedWaitTypeDef,
     DescribeReplicationGroupsMessageReplicationGroupAvailableWaitTypeDef,
     DescribeReplicationGroupsMessageReplicationGroupDeletedWaitTypeDef,
-    DescribeCacheClustersMessageDescribeCacheClustersPaginateTypeDef,
-    DescribeCacheEngineVersionsMessageDescribeCacheEngineVersionsPaginateTypeDef,
-    DescribeCacheParameterGroupsMessageDescribeCacheParameterGroupsPaginateTypeDef,
-    DescribeCacheParametersMessageDescribeCacheParametersPaginateTypeDef,
-    DescribeCacheSecurityGroupsMessageDescribeCacheSecurityGroupsPaginateTypeDef,
-    DescribeCacheSubnetGroupsMessageDescribeCacheSubnetGroupsPaginateTypeDef,
-    DescribeEngineDefaultParametersMessageDescribeEngineDefaultParametersPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
-    DescribeGlobalReplicationGroupsMessageDescribeGlobalReplicationGroupsPaginateTypeDef,
-    DescribeReplicationGroupsMessageDescribeReplicationGroupsPaginateTypeDef,
-    DescribeReservedCacheNodesMessageDescribeReservedCacheNodesPaginateTypeDef,
-    DescribeReservedCacheNodesOfferingsMessageDescribeReservedCacheNodesOfferingsPaginateTypeDef,
-    DescribeServiceUpdatesMessageDescribeServiceUpdatesPaginateTypeDef,
-    DescribeSnapshotsMessageDescribeSnapshotsPaginateTypeDef,
-    DescribeUserGroupsMessageDescribeUserGroupsPaginateTypeDef,
     DescribeUpdateActionsMessageDescribeUpdateActionsPaginateTypeDef,
     DescribeUpdateActionsMessageRequestTypeDef,
     DescribeUsersMessageDescribeUsersPaginateTypeDef,
     DescribeUsersMessageRequestTypeDef,
     DestinationDetailsTypeDef,
     EventsMessageTypeDef,
     GlobalReplicationGroupTypeDef,
@@ -686,43 +687,43 @@
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

### Comparing `types-aiobotocore-elasticache-2.5.0.post1/types_aiobotocore_elasticache.egg-info/SOURCES.txt` & `types-aiobotocore-elasticache-2.5.1/types_aiobotocore_elasticache.egg-info/SOURCES.txt`

 * *Files identical despite different names*

