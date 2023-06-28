# Comparing `tmp/types-aiobotocore-memorydb-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-memorydb-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-memorydb-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:00 2023, max compression
+gzip compressed data, was "types-aiobotocore-memorydb-2.5.1.tar", last modified: Wed Jun 28 01:43:51 2023, max compression
```

## Comparing `types-aiobotocore-memorydb-2.5.0.post1.tar` & `types-aiobotocore-memorydb-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.819438 types-aiobotocore-memorydb-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20107 2023-03-11 12:27:00.815438 types-aiobotocore-memorydb-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18532 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:00.819438 types-aiobotocore-memorydb-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.815438 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/
--rw-r--r--   0 runner    (1001) docker     (123)     3143 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3142 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    38451 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    38392 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9997 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9995 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15944 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    15929 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    41329 2023-03-11 12:18:42.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    41294 2023-03-11 12:18:42.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:41.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.815438 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20107 2023-03-11 12:27:00.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:27:00.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:00.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:00.000000 types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.686178 types-aiobotocore-memorydb-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20100 2023-06-28 01:43:51.686178 types-aiobotocore-memorydb-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18531 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:51.686178 types-aiobotocore-memorydb-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:35:23.000000 types-aiobotocore-memorydb-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.686178 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/
+-rw-r--r--   0 runner    (1001) docker     (123)     3143 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3142 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38451 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38392 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10220 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10218 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15848 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15834 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    41470 2023-06-28 01:35:25.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41435 2023-06-28 01:35:25.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:24.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.686178 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20100 2023-06-28 01:43:51.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:43:51.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:51.000000 types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/LICENSE` & `types-aiobotocore-memorydb-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/PKG-INFO` & `types-aiobotocore-memorydb-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-memorydb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MemoryDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MemoryDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-memorydb"></a>
 
 # types-aiobotocore-memorydb
 
 [![PyPI - types-aiobotocore-memorydb](https://img.shields.io/pypi/v/types-aiobotocore-memorydb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-memorydb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-memorydb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-memorydb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-memorydb?color=blue)](https://pypistats.org/packages/types-aiobotocore-memorydb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MemoryDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB)
+[aiobotocore.MemoryDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB)
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
 [types-aiobotocore-memorydb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -379,63 +379,74 @@
 from types_aiobotocore_memorydb.type_defs import (
     ACLPendingChangesTypeDef,
     ACLsUpdateStatusTypeDef,
     AuthenticationModeTypeDef,
     AuthenticationTypeDef,
     AvailabilityZoneTypeDef,
     ServiceUpdateRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedClusterTypeDef,
     PendingModifiedServiceUpdateTypeDef,
     EndpointTypeDef,
     SecurityGroupMembershipTypeDef,
     TagTypeDef,
     ParameterGroupTypeDef,
     DeleteACLRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteParameterGroupRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
     DeleteSubnetGroupRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeACLsRequestDescribeACLsPaginateTypeDef,
     DescribeACLsRequestRequestTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
+    DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef,
     DescribeEngineVersionsRequestRequestTypeDef,
     EngineVersionInfoTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     EventTypeDef,
+    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
     DescribeParameterGroupsRequestRequestTypeDef,
+    DescribeParametersRequestDescribeParametersPaginateTypeDef,
     DescribeParametersRequestRequestTypeDef,
     ParameterTypeDef,
+    DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef,
     DescribeReservedNodesOfferingsRequestRequestTypeDef,
+    DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef,
     DescribeReservedNodesRequestRequestTypeDef,
+    DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef,
     DescribeServiceUpdatesRequestRequestTypeDef,
     ServiceUpdateTypeDef,
+    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
+    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeSubnetGroupsRequestRequestTypeDef,
     FilterTypeDef,
     FailoverShardRequestRequestTypeDef,
     ListAllowedNodeTypeUpdatesRequestRequestTypeDef,
+    ListAllowedNodeTypeUpdatesResponseTypeDef,
     ListTagsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterNameValueTypeDef,
     RecurringChargeTypeDef,
     ReplicaConfigurationRequestTypeDef,
     ResetParameterGroupRequestRequestTypeDef,
     SlotMigrationTypeDef,
+    ResponseMetadataTypeDef,
     ShardConfigurationRequestTypeDef,
     ShardConfigurationTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateACLRequestRequestTypeDef,
     UpdateSubnetGroupRequestRequestTypeDef,
     ACLTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserTypeDef,
     SubnetTypeDef,
     BatchUpdateClusterRequestRequestTypeDef,
-    ListAllowedNodeTypeUpdatesResponseTypeDef,
     NodeTypeDef,
     CopySnapshotRequestRequestTypeDef,
     CreateACLRequestRequestTypeDef,
     CreateClusterRequestRequestTypeDef,
     CreateParameterGroupRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateSubnetGroupRequestRequestTypeDef,
@@ -446,25 +457,14 @@
     TagResourceResponseTypeDef,
     UntagResourceResponseTypeDef,
     CreateParameterGroupResponseTypeDef,
     DeleteParameterGroupResponseTypeDef,
     DescribeParameterGroupsResponseTypeDef,
     ResetParameterGroupResponseTypeDef,
     UpdateParameterGroupResponseTypeDef,
-    DescribeACLsRequestDescribeACLsPaginateTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
-    DescribeParametersRequestDescribeParametersPaginateTypeDef,
-    DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef,
-    DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef,
-    DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef,
-    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
-    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeEngineVersionsResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeParametersResponseTypeDef,
     DescribeServiceUpdatesResponseTypeDef,
     DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
     UpdateParameterGroupRequestRequestTypeDef,
@@ -514,43 +514,43 @@
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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/README.md` & `types-aiobotocore-memorydb-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-memorydb"></a>
 
 # types-aiobotocore-memorydb
 
 [![PyPI - types-aiobotocore-memorydb](https://img.shields.io/pypi/v/types-aiobotocore-memorydb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-memorydb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-memorydb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-memorydb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-memorydb?color=blue)](https://pypistats.org/packages/types-aiobotocore-memorydb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MemoryDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB)
+[aiobotocore.MemoryDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB)
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
 [types-aiobotocore-memorydb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -346,63 +346,74 @@
 from types_aiobotocore_memorydb.type_defs import (
     ACLPendingChangesTypeDef,
     ACLsUpdateStatusTypeDef,
     AuthenticationModeTypeDef,
     AuthenticationTypeDef,
     AvailabilityZoneTypeDef,
     ServiceUpdateRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedClusterTypeDef,
     PendingModifiedServiceUpdateTypeDef,
     EndpointTypeDef,
     SecurityGroupMembershipTypeDef,
     TagTypeDef,
     ParameterGroupTypeDef,
     DeleteACLRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteParameterGroupRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
     DeleteSubnetGroupRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeACLsRequestDescribeACLsPaginateTypeDef,
     DescribeACLsRequestRequestTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
+    DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef,
     DescribeEngineVersionsRequestRequestTypeDef,
     EngineVersionInfoTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     EventTypeDef,
+    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
     DescribeParameterGroupsRequestRequestTypeDef,
+    DescribeParametersRequestDescribeParametersPaginateTypeDef,
     DescribeParametersRequestRequestTypeDef,
     ParameterTypeDef,
+    DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef,
     DescribeReservedNodesOfferingsRequestRequestTypeDef,
+    DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef,
     DescribeReservedNodesRequestRequestTypeDef,
+    DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef,
     DescribeServiceUpdatesRequestRequestTypeDef,
     ServiceUpdateTypeDef,
+    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
+    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeSubnetGroupsRequestRequestTypeDef,
     FilterTypeDef,
     FailoverShardRequestRequestTypeDef,
     ListAllowedNodeTypeUpdatesRequestRequestTypeDef,
+    ListAllowedNodeTypeUpdatesResponseTypeDef,
     ListTagsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterNameValueTypeDef,
     RecurringChargeTypeDef,
     ReplicaConfigurationRequestTypeDef,
     ResetParameterGroupRequestRequestTypeDef,
     SlotMigrationTypeDef,
+    ResponseMetadataTypeDef,
     ShardConfigurationRequestTypeDef,
     ShardConfigurationTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateACLRequestRequestTypeDef,
     UpdateSubnetGroupRequestRequestTypeDef,
     ACLTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserTypeDef,
     SubnetTypeDef,
     BatchUpdateClusterRequestRequestTypeDef,
-    ListAllowedNodeTypeUpdatesResponseTypeDef,
     NodeTypeDef,
     CopySnapshotRequestRequestTypeDef,
     CreateACLRequestRequestTypeDef,
     CreateClusterRequestRequestTypeDef,
     CreateParameterGroupRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateSubnetGroupRequestRequestTypeDef,
@@ -413,25 +424,14 @@
     TagResourceResponseTypeDef,
     UntagResourceResponseTypeDef,
     CreateParameterGroupResponseTypeDef,
     DeleteParameterGroupResponseTypeDef,
     DescribeParameterGroupsResponseTypeDef,
     ResetParameterGroupResponseTypeDef,
     UpdateParameterGroupResponseTypeDef,
-    DescribeACLsRequestDescribeACLsPaginateTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
-    DescribeParametersRequestDescribeParametersPaginateTypeDef,
-    DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef,
-    DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef,
-    DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef,
-    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
-    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeEngineVersionsResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeParametersResponseTypeDef,
     DescribeServiceUpdatesResponseTypeDef,
     DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
     UpdateParameterGroupRequestRequestTypeDef,
@@ -481,43 +481,43 @@
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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/setup.py` & `types-aiobotocore-memorydb-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-memorydb.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-memorydb",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_memorydb"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MemoryDB 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.MemoryDB 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/"
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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/__init__.py` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/__init__.pyi` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/__main__.py` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/__main__.py`

 * *Files 26% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MemoryDB 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MemoryDB 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB\nOther"
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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/client.py` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/client.pyi` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/literals.py` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -44,29 +44,29 @@
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 AZStatusType = Literal["multiaz", "singleaz"]
-AuthenticationTypeType = Literal["no-password", "password"]
+AuthenticationTypeType = Literal["iam", "no-password", "password"]
 DataTieringStatusType = Literal["false", "true"]
 DescribeACLsPaginatorName = Literal["describe_acls"]
 DescribeClustersPaginatorName = Literal["describe_clusters"]
 DescribeEngineVersionsPaginatorName = Literal["describe_engine_versions"]
 DescribeEventsPaginatorName = Literal["describe_events"]
 DescribeParameterGroupsPaginatorName = Literal["describe_parameter_groups"]
 DescribeParametersPaginatorName = Literal["describe_parameters"]
 DescribeReservedNodesOfferingsPaginatorName = Literal["describe_reserved_nodes_offerings"]
 DescribeReservedNodesPaginatorName = Literal["describe_reserved_nodes"]
 DescribeServiceUpdatesPaginatorName = Literal["describe_service_updates"]
 DescribeSnapshotsPaginatorName = Literal["describe_snapshots"]
 DescribeSubnetGroupsPaginatorName = Literal["describe_subnet_groups"]
 DescribeUsersPaginatorName = Literal["describe_users"]
-InputAuthenticationTypeType = Literal["password"]
+InputAuthenticationTypeType = Literal["iam", "password"]
 ServiceUpdateStatusType = Literal["available", "complete", "in-progress", "scheduled"]
 ServiceUpdateTypeType = Literal["security-update"]
 SourceTypeType = Literal["acl", "cluster", "node", "parameter-group", "subnet-group", "user"]
 MemoryDBServiceName = Literal["memorydb"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -125,14 +125,15 @@
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
@@ -211,14 +212,15 @@
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
@@ -229,14 +231,15 @@
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
@@ -272,14 +275,15 @@
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
@@ -298,16 +302,19 @@
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
@@ -391,15 +398,17 @@
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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/literals.pyi` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -42,29 +42,29 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 AZStatusType = Literal["multiaz", "singleaz"]
-AuthenticationTypeType = Literal["no-password", "password"]
+AuthenticationTypeType = Literal["iam", "no-password", "password"]
 DataTieringStatusType = Literal["false", "true"]
 DescribeACLsPaginatorName = Literal["describe_acls"]
 DescribeClustersPaginatorName = Literal["describe_clusters"]
 DescribeEngineVersionsPaginatorName = Literal["describe_engine_versions"]
 DescribeEventsPaginatorName = Literal["describe_events"]
 DescribeParameterGroupsPaginatorName = Literal["describe_parameter_groups"]
 DescribeParametersPaginatorName = Literal["describe_parameters"]
 DescribeReservedNodesOfferingsPaginatorName = Literal["describe_reserved_nodes_offerings"]
 DescribeReservedNodesPaginatorName = Literal["describe_reserved_nodes"]
 DescribeServiceUpdatesPaginatorName = Literal["describe_service_updates"]
 DescribeSnapshotsPaginatorName = Literal["describe_snapshots"]
 DescribeSubnetGroupsPaginatorName = Literal["describe_subnet_groups"]
 DescribeUsersPaginatorName = Literal["describe_users"]
-InputAuthenticationTypeType = Literal["password"]
+InputAuthenticationTypeType = Literal["iam", "password"]
 ServiceUpdateStatusType = Literal["available", "complete", "in-progress", "scheduled"]
 ServiceUpdateTypeType = Literal["security-update"]
 SourceTypeType = Literal["acl", "cluster", "node", "parameter-group", "subnet-group", "user"]
 MemoryDBServiceName = Literal["memorydb"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -123,14 +123,15 @@
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
@@ -209,14 +210,15 @@
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
@@ -227,14 +229,15 @@
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
@@ -270,14 +273,15 @@
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
@@ -296,16 +300,19 @@
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
@@ -389,15 +396,17 @@
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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/paginator.py` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/paginator.py`

 * *Files 9% similar despite different names*

```diff
@@ -38,17 +38,16 @@
         describe_reserved_nodes_offerings_paginator: DescribeReservedNodesOfferingsPaginator = client.get_paginator("describe_reserved_nodes_offerings")
         describe_service_updates_paginator: DescribeServiceUpdatesPaginator = client.get_paginator("describe_service_updates")
         describe_snapshots_paginator: DescribeSnapshotsPaginator = client.get_paginator("describe_snapshots")
         describe_subnet_groups_paginator: DescribeSubnetGroupsPaginator = client.get_paginator("describe_subnet_groups")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ServiceUpdateStatusType, SourceTypeType
 from .type_defs import (
     DescribeACLsResponseTypeDef,
@@ -63,20 +62,14 @@
     DescribeSnapshotsResponseTypeDef,
     DescribeSubnetGroupsResponseTypeDef,
     DescribeUsersResponseTypeDef,
     FilterTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeACLsPaginator",
     "DescribeClustersPaginator",
     "DescribeEngineVersionsPaginator",
     "DescribeEventsPaginator",
     "DescribeParameterGroupsPaginator",
     "DescribeParametersPaginator",
@@ -102,15 +95,15 @@
 class DescribeACLsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeACLs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeaclspaginator)
     """
 
     def paginate(
-        self, *, ACLName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ACLName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeACLsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeACLs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeaclspaginator)
         """
 
 
@@ -121,15 +114,15 @@
     """
 
     def paginate(
         self,
         *,
         ClusterName: str = ...,
         ShowShardDetails: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeclusterspaginator)
         """
 
 
@@ -141,15 +134,15 @@
 
     def paginate(
         self,
         *,
         EngineVersion: str = ...,
         ParameterGroupFamily: str = ...,
         DefaultOnly: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeengineversionspaginator)
         """
 
 
@@ -163,45 +156,45 @@
         self,
         *,
         SourceName: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeeventspaginator)
         """
 
 
 class DescribeParameterGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameterGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparametergroupspaginator)
     """
 
     def paginate(
-        self, *, ParameterGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParameterGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParameterGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparametergroupspaginator)
         """
 
 
 class DescribeParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparameterspaginator)
     """
 
     def paginate(
-        self, *, ParameterGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParameterGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParametersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparameterspaginator)
         """
 
 
@@ -215,15 +208,15 @@
         self,
         *,
         ReservationId: str = ...,
         ReservedNodesOfferingId: str = ...,
         NodeType: str = ...,
         Duration: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedNodesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeReservedNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describereservednodespaginator)
         """
 
 
@@ -236,15 +229,15 @@
     def paginate(
         self,
         *,
         ReservedNodesOfferingId: str = ...,
         NodeType: str = ...,
         Duration: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedNodesOfferingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeReservedNodesOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describereservednodesofferingspaginator)
         """
 
 
@@ -256,15 +249,15 @@
 
     def paginate(
         self,
         *,
         ServiceUpdateName: str = ...,
         ClusterNames: Sequence[str] = ...,
         Status: Sequence[ServiceUpdateStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeServiceUpdatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeServiceUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeserviceupdatespaginator)
         """
 
 
@@ -277,30 +270,30 @@
     def paginate(
         self,
         *,
         ClusterName: str = ...,
         SnapshotName: str = ...,
         Source: str = ...,
         ShowDetail: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describesnapshotspaginator)
         """
 
 
 class DescribeSubnetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeSubnetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describesubnetgroupspaginator)
     """
 
     def paginate(
-        self, *, SubnetGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SubnetGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSubnetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describesubnetgroupspaginator)
         """
 
 
@@ -311,13 +304,13 @@
     """
 
     def paginate(
         self,
         *,
         UserName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeuserspaginator)
         """
```

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/paginator.pyi` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -38,17 +38,16 @@
         describe_reserved_nodes_offerings_paginator: DescribeReservedNodesOfferingsPaginator = client.get_paginator("describe_reserved_nodes_offerings")
         describe_service_updates_paginator: DescribeServiceUpdatesPaginator = client.get_paginator("describe_service_updates")
         describe_snapshots_paginator: DescribeSnapshotsPaginator = client.get_paginator("describe_snapshots")
         describe_subnet_groups_paginator: DescribeSubnetGroupsPaginator = client.get_paginator("describe_subnet_groups")
         describe_users_paginator: DescribeUsersPaginator = client.get_paginator("describe_users")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ServiceUpdateStatusType, SourceTypeType
 from .type_defs import (
     DescribeACLsResponseTypeDef,
@@ -63,19 +62,14 @@
     DescribeSnapshotsResponseTypeDef,
     DescribeSubnetGroupsResponseTypeDef,
     DescribeUsersResponseTypeDef,
     FilterTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeACLsPaginator",
     "DescribeClustersPaginator",
     "DescribeEngineVersionsPaginator",
     "DescribeEventsPaginator",
     "DescribeParameterGroupsPaginator",
     "DescribeParametersPaginator",
@@ -98,15 +92,15 @@
 class DescribeACLsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeACLs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeaclspaginator)
     """
 
     def paginate(
-        self, *, ACLName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ACLName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeACLsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeACLs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeaclspaginator)
         """
 
 class DescribeClustersPaginator(AioPaginator):
@@ -116,15 +110,15 @@
     """
 
     def paginate(
         self,
         *,
         ClusterName: str = ...,
         ShowShardDetails: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeclusterspaginator)
         """
 
 class DescribeEngineVersionsPaginator(AioPaginator):
@@ -135,15 +129,15 @@
 
     def paginate(
         self,
         *,
         EngineVersion: str = ...,
         ParameterGroupFamily: str = ...,
         DefaultOnly: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEngineVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeengineversionspaginator)
         """
 
 class DescribeEventsPaginator(AioPaginator):
@@ -156,43 +150,43 @@
         self,
         *,
         SourceName: str = ...,
         SourceType: SourceTypeType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
         Duration: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeeventspaginator)
         """
 
 class DescribeParameterGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameterGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparametergroupspaginator)
     """
 
     def paginate(
-        self, *, ParameterGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParameterGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParameterGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparametergroupspaginator)
         """
 
 class DescribeParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparameterspaginator)
     """
 
     def paginate(
-        self, *, ParameterGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ParameterGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParametersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeparameterspaginator)
         """
 
 class DescribeReservedNodesPaginator(AioPaginator):
@@ -205,15 +199,15 @@
         self,
         *,
         ReservationId: str = ...,
         ReservedNodesOfferingId: str = ...,
         NodeType: str = ...,
         Duration: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedNodesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeReservedNodes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describereservednodespaginator)
         """
 
 class DescribeReservedNodesOfferingsPaginator(AioPaginator):
@@ -225,15 +219,15 @@
     def paginate(
         self,
         *,
         ReservedNodesOfferingId: str = ...,
         NodeType: str = ...,
         Duration: str = ...,
         OfferingType: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReservedNodesOfferingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeReservedNodesOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describereservednodesofferingspaginator)
         """
 
 class DescribeServiceUpdatesPaginator(AioPaginator):
@@ -244,15 +238,15 @@
 
     def paginate(
         self,
         *,
         ServiceUpdateName: str = ...,
         ClusterNames: Sequence[str] = ...,
         Status: Sequence[ServiceUpdateStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeServiceUpdatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeServiceUpdates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeserviceupdatespaginator)
         """
 
 class DescribeSnapshotsPaginator(AioPaginator):
@@ -264,29 +258,29 @@
     def paginate(
         self,
         *,
         ClusterName: str = ...,
         SnapshotName: str = ...,
         Source: str = ...,
         ShowDetail: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describesnapshotspaginator)
         """
 
 class DescribeSubnetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeSubnetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describesubnetgroupspaginator)
     """
 
     def paginate(
-        self, *, SubnetGroupName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SubnetGroupName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSubnetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describesubnetgroupspaginator)
         """
 
 class DescribeUsersPaginator(AioPaginator):
@@ -296,13 +290,13 @@
     """
 
     def paginate(
         self,
         *,
         UserName: str = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB.Paginator.DescribeUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/paginators/#describeuserspaginator)
         """
```

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/type_defs.py` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
 from .literals import (
     AuthenticationTypeType,
     AZStatusType,
     DataTieringStatusType,
+    InputAuthenticationTypeType,
     ServiceUpdateStatusType,
     SourceTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -36,63 +37,74 @@
 __all__ = (
     "ACLPendingChangesTypeDef",
     "ACLsUpdateStatusTypeDef",
     "AuthenticationModeTypeDef",
     "AuthenticationTypeDef",
     "AvailabilityZoneTypeDef",
     "ServiceUpdateRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedClusterTypeDef",
     "PendingModifiedServiceUpdateTypeDef",
     "EndpointTypeDef",
     "SecurityGroupMembershipTypeDef",
     "TagTypeDef",
     "ParameterGroupTypeDef",
     "DeleteACLRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteParameterGroupRequestRequestTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
     "DeleteSubnetGroupRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
     "DescribeACLsRequestRequestTypeDef",
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
     "DescribeClustersRequestRequestTypeDef",
+    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
     "DescribeEngineVersionsRequestRequestTypeDef",
     "EngineVersionInfoTypeDef",
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     "DescribeEventsRequestRequestTypeDef",
     "EventTypeDef",
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
     "DescribeParameterGroupsRequestRequestTypeDef",
+    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
     "DescribeParametersRequestRequestTypeDef",
     "ParameterTypeDef",
+    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
     "DescribeReservedNodesOfferingsRequestRequestTypeDef",
+    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
     "DescribeReservedNodesRequestRequestTypeDef",
+    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
     "DescribeServiceUpdatesRequestRequestTypeDef",
     "ServiceUpdateTypeDef",
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
     "DescribeSnapshotsRequestRequestTypeDef",
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
     "DescribeSubnetGroupsRequestRequestTypeDef",
     "FilterTypeDef",
     "FailoverShardRequestRequestTypeDef",
     "ListAllowedNodeTypeUpdatesRequestRequestTypeDef",
+    "ListAllowedNodeTypeUpdatesResponseTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterNameValueTypeDef",
     "RecurringChargeTypeDef",
     "ReplicaConfigurationRequestTypeDef",
     "ResetParameterGroupRequestRequestTypeDef",
     "SlotMigrationTypeDef",
+    "ResponseMetadataTypeDef",
     "ShardConfigurationRequestTypeDef",
     "ShardConfigurationTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateACLRequestRequestTypeDef",
     "UpdateSubnetGroupRequestRequestTypeDef",
     "ACLTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UserTypeDef",
     "SubnetTypeDef",
     "BatchUpdateClusterRequestRequestTypeDef",
-    "ListAllowedNodeTypeUpdatesResponseTypeDef",
     "NodeTypeDef",
     "CopySnapshotRequestRequestTypeDef",
     "CreateACLRequestRequestTypeDef",
     "CreateClusterRequestRequestTypeDef",
     "CreateParameterGroupRequestRequestTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "CreateSubnetGroupRequestRequestTypeDef",
@@ -103,25 +115,14 @@
     "TagResourceResponseTypeDef",
     "UntagResourceResponseTypeDef",
     "CreateParameterGroupResponseTypeDef",
     "DeleteParameterGroupResponseTypeDef",
     "DescribeParameterGroupsResponseTypeDef",
     "ResetParameterGroupResponseTypeDef",
     "UpdateParameterGroupResponseTypeDef",
-    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
-    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
-    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
-    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
     "DescribeEngineVersionsResponseTypeDef",
     "DescribeEventsResponseTypeDef",
     "DescribeParametersResponseTypeDef",
     "DescribeServiceUpdatesResponseTypeDef",
     "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeUsersRequestRequestTypeDef",
     "UpdateParameterGroupRequestRequestTypeDef",
@@ -179,15 +180,15 @@
     },
     total=False,
 )
 
 AuthenticationModeTypeDef = TypedDict(
     "AuthenticationModeTypeDef",
     {
-        "Type": Literal["password"],
+        "Type": InputAuthenticationTypeType,
         "Passwords": Sequence[str],
     },
     total=False,
 )
 
 AuthenticationTypeDef = TypedDict(
     "AuthenticationTypeDef",
@@ -210,25 +211,14 @@
     "ServiceUpdateRequestTypeDef",
     {
         "ServiceUpdateNameToApply": str,
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
 UnprocessedClusterTypeDef = TypedDict(
     "UnprocessedClusterTypeDef",
     {
         "ClusterName": str,
         "ErrorType": str,
         "ErrorMessage": str,
     },
@@ -334,45 +324,65 @@
 DeleteUserRequestRequestTypeDef = TypedDict(
     "DeleteUserRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeACLsRequestDescribeACLsPaginateTypeDef = TypedDict(
+    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ACLName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeACLsRequestRequestTypeDef = TypedDict(
     "DescribeACLsRequestRequestTypeDef",
     {
         "ACLName": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
+    {
+        "ClusterName": str,
+        "ShowShardDetails": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "ClusterName": str,
         "MaxResults": int,
         "NextToken": str,
         "ShowShardDetails": bool,
     },
     total=False,
 )
 
+DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef = TypedDict(
+    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
+    {
+        "EngineVersion": str,
+        "ParameterGroupFamily": str,
+        "DefaultOnly": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEngineVersionsRequestRequestTypeDef = TypedDict(
     "DescribeEngineVersionsRequestRequestTypeDef",
     {
         "EngineVersion": str,
         "ParameterGroupFamily": str,
         "MaxResults": int,
         "NextToken": str,
@@ -387,14 +397,27 @@
         "EngineVersion": str,
         "EnginePatchVersion": str,
         "ParameterGroupFamily": str,
     },
     total=False,
 )
 
+DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "SourceName": str,
+        "SourceType": SourceTypeType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsRequestRequestTypeDef = TypedDict(
     "DescribeEventsRequestRequestTypeDef",
     {
         "SourceName": str,
         "SourceType": SourceTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -412,24 +435,55 @@
         "SourceType": SourceTypeType,
         "Message": str,
         "Date": datetime,
     },
     total=False,
 )
 
+DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
+    {
+        "ParameterGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeParameterGroupsRequestRequestTypeDef = TypedDict(
     "DescribeParameterGroupsRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "ParameterGroupName": str,
+    },
+)
+_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeParametersRequestDescribeParametersPaginateTypeDef(
+    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
+    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeParametersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeParametersRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 _OptionalDescribeParametersRequestRequestTypeDef = TypedDict(
@@ -458,41 +512,77 @@
         "DataType": str,
         "AllowedValues": str,
         "MinimumEngineVersion": str,
     },
     total=False,
 )
 
+DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef = TypedDict(
+    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
+    {
+        "ReservedNodesOfferingId": str,
+        "NodeType": str,
+        "Duration": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedNodesOfferingsRequestRequestTypeDef = TypedDict(
     "DescribeReservedNodesOfferingsRequestRequestTypeDef",
     {
         "ReservedNodesOfferingId": str,
         "NodeType": str,
         "Duration": str,
         "OfferingType": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef = TypedDict(
+    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
+    {
+        "ReservationId": str,
+        "ReservedNodesOfferingId": str,
+        "NodeType": str,
+        "Duration": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedNodesRequestRequestTypeDef = TypedDict(
     "DescribeReservedNodesRequestRequestTypeDef",
     {
         "ReservationId": str,
         "ReservedNodesOfferingId": str,
         "NodeType": str,
         "Duration": str,
         "OfferingType": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef = TypedDict(
+    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
+    {
+        "ServiceUpdateName": str,
+        "ClusterNames": Sequence[str],
+        "Status": Sequence[ServiceUpdateStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeServiceUpdatesRequestRequestTypeDef = TypedDict(
     "DescribeServiceUpdatesRequestRequestTypeDef",
     {
         "ServiceUpdateName": str,
         "ClusterNames": Sequence[str],
         "Status": Sequence[ServiceUpdateStatusType],
         "MaxResults": int,
@@ -512,27 +602,48 @@
         "Type": Literal["security-update"],
         "NodesUpdated": str,
         "AutoUpdateStartDate": datetime,
     },
     total=False,
 )
 
+DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
+    {
+        "ClusterName": str,
+        "SnapshotName": str,
+        "Source": str,
+        "ShowDetail": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSnapshotsRequestRequestTypeDef = TypedDict(
     "DescribeSnapshotsRequestRequestTypeDef",
     {
         "ClusterName": str,
         "SnapshotName": str,
         "Source": str,
         "NextToken": str,
         "MaxResults": int,
         "ShowDetail": bool,
     },
     total=False,
 )
 
+DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
+    {
+        "SubnetGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSubnetGroupsRequestRequestTypeDef = TypedDict(
     "DescribeSubnetGroupsRequestRequestTypeDef",
     {
         "SubnetGroupName": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -558,21 +669,40 @@
 ListAllowedNodeTypeUpdatesRequestRequestTypeDef = TypedDict(
     "ListAllowedNodeTypeUpdatesRequestRequestTypeDef",
     {
         "ClusterName": str,
     },
 )
 
+ListAllowedNodeTypeUpdatesResponseTypeDef = TypedDict(
+    "ListAllowedNodeTypeUpdatesResponseTypeDef",
+    {
+        "ScaleUpNodeTypes": List[str],
+        "ScaleDownNodeTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
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
 ParameterNameValueTypeDef = TypedDict(
     "ParameterNameValueTypeDef",
     {
         "ParameterName": str,
         "ParameterValue": str,
     },
     total=False,
@@ -622,14 +752,25 @@
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
 ShardConfigurationRequestTypeDef = TypedDict(
     "ShardConfigurationRequestTypeDef",
     {
         "ShardCount": int,
     },
     total=False,
 )
@@ -772,23 +913,14 @@
 class BatchUpdateClusterRequestRequestTypeDef(
     _RequiredBatchUpdateClusterRequestRequestTypeDef,
     _OptionalBatchUpdateClusterRequestRequestTypeDef,
 ):
     pass
 
 
-ListAllowedNodeTypeUpdatesResponseTypeDef = TypedDict(
-    "ListAllowedNodeTypeUpdatesResponseTypeDef",
-    {
-        "ScaleUpNodeTypes": List[str],
-        "ScaleDownNodeTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 NodeTypeDef = TypedDict(
     "NodeTypeDef",
     {
         "Name": str,
         "Status": str,
         "AvailabilityZone": str,
         "CreateTime": datetime,
@@ -977,15 +1109,15 @@
     pass
 
 
 ListTagsResponseTypeDef = TypedDict(
     "ListTagsResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPurchaseReservedNodesOfferingRequestRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedNodesOfferingRequestRequestTypeDef",
     {
         "ReservedNodesOfferingId": str,
@@ -1017,240 +1149,109 @@
     },
 )
 
 TagResourceResponseTypeDef = TypedDict(
     "TagResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourceResponseTypeDef = TypedDict(
     "UntagResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateParameterGroupResponseTypeDef = TypedDict(
     "CreateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteParameterGroupResponseTypeDef = TypedDict(
     "DeleteParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParameterGroupsResponseTypeDef = TypedDict(
     "DescribeParameterGroupsResponseTypeDef",
     {
         "NextToken": str,
         "ParameterGroups": List[ParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetParameterGroupResponseTypeDef = TypedDict(
     "ResetParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateParameterGroupResponseTypeDef = TypedDict(
     "UpdateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeACLsRequestDescribeACLsPaginateTypeDef = TypedDict(
-    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
-    {
-        "ACLName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    {
-        "ClusterName": str,
-        "ShowShardDetails": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef = TypedDict(
-    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
-    {
-        "EngineVersion": str,
-        "ParameterGroupFamily": str,
-        "DefaultOnly": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "SourceName": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    {
-        "ParameterGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "ParameterGroupName": str,
-    },
-)
-_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeParametersRequestDescribeParametersPaginateTypeDef(
-    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
-    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
-):
-    pass
-
-
-DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef = TypedDict(
-    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
-    {
-        "ReservedNodesOfferingId": str,
-        "NodeType": str,
-        "Duration": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef = TypedDict(
-    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
-    {
-        "ReservationId": str,
-        "ReservedNodesOfferingId": str,
-        "NodeType": str,
-        "Duration": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef = TypedDict(
-    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
-    {
-        "ServiceUpdateName": str,
-        "ClusterNames": Sequence[str],
-        "Status": Sequence[ServiceUpdateStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    {
-        "ClusterName": str,
-        "SnapshotName": str,
-        "Source": str,
-        "ShowDetail": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
-    {
-        "SubnetGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeEngineVersionsResponseTypeDef = TypedDict(
     "DescribeEngineVersionsResponseTypeDef",
     {
         "NextToken": str,
         "EngineVersions": List[EngineVersionInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "NextToken": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParametersResponseTypeDef = TypedDict(
     "DescribeParametersResponseTypeDef",
     {
         "NextToken": str,
         "Parameters": List[ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceUpdatesResponseTypeDef = TypedDict(
     "DescribeServiceUpdatesResponseTypeDef",
     {
         "NextToken": str,
         "ServiceUpdates": List[ServiceUpdateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
     "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     {
         "UserName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeUsersRequestRequestTypeDef = TypedDict(
     "DescribeUsersRequestRequestTypeDef",
     {
@@ -1353,73 +1354,73 @@
     total=False,
 )
 
 CreateACLResponseTypeDef = TypedDict(
     "CreateACLResponseTypeDef",
     {
         "ACL": ACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteACLResponseTypeDef = TypedDict(
     "DeleteACLResponseTypeDef",
     {
         "ACL": ACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeACLsResponseTypeDef = TypedDict(
     "DescribeACLsResponseTypeDef",
     {
         "ACLs": List[ACLTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateACLResponseTypeDef = TypedDict(
     "UpdateACLResponseTypeDef",
     {
         "ACL": ACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteUserResponseTypeDef = TypedDict(
     "DeleteUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsersResponseTypeDef = TypedDict(
     "DescribeUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubnetGroupTypeDef = TypedDict(
     "SubnetGroupTypeDef",
     {
         "Name": str,
@@ -1444,32 +1445,32 @@
 )
 
 DescribeReservedNodesResponseTypeDef = TypedDict(
     "DescribeReservedNodesResponseTypeDef",
     {
         "NextToken": str,
         "ReservedNodes": List[ReservedNodeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseReservedNodesOfferingResponseTypeDef = TypedDict(
     "PurchaseReservedNodesOfferingResponseTypeDef",
     {
         "ReservedNode": ReservedNodeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedNodesOfferingsResponseTypeDef = TypedDict(
     "DescribeReservedNodesOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "ReservedNodesOfferings": List[ReservedNodesOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterPendingUpdatesTypeDef = TypedDict(
     "ClusterPendingUpdatesTypeDef",
     {
         "Resharding": ReshardingStatusTypeDef,
@@ -1500,40 +1501,40 @@
     total=False,
 )
 
 CreateSubnetGroupResponseTypeDef = TypedDict(
     "CreateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSubnetGroupResponseTypeDef = TypedDict(
     "DeleteSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSubnetGroupsResponseTypeDef = TypedDict(
     "DescribeSubnetGroupsResponseTypeDef",
     {
         "NextToken": str,
         "SubnetGroups": List[SubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSubnetGroupResponseTypeDef = TypedDict(
     "UpdateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterTypeDef = TypedDict(
     "ClusterTypeDef",
     {
         "Name": str,
@@ -1581,84 +1582,84 @@
 )
 
 BatchUpdateClusterResponseTypeDef = TypedDict(
     "BatchUpdateClusterResponseTypeDef",
     {
         "ProcessedClusters": List[ClusterTypeDef],
         "UnprocessedClusters": List[UnprocessedClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClustersResponseTypeDef = TypedDict(
     "DescribeClustersResponseTypeDef",
     {
         "NextToken": str,
         "Clusters": List[ClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverShardResponseTypeDef = TypedDict(
     "FailoverShardResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterResponseTypeDef = TypedDict(
     "UpdateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopySnapshotResponseTypeDef = TypedDict(
     "CopySnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResponseTypeDef = TypedDict(
     "CreateSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSnapshotResponseTypeDef = TypedDict(
     "DeleteSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsResponseTypeDef = TypedDict(
     "DescribeSnapshotsResponseTypeDef",
     {
         "NextToken": str,
         "Snapshots": List[SnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb/type_defs.pyi` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
 from .literals import (
     AuthenticationTypeType,
     AZStatusType,
     DataTieringStatusType,
+    InputAuthenticationTypeType,
     ServiceUpdateStatusType,
     SourceTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -35,63 +36,74 @@
 __all__ = (
     "ACLPendingChangesTypeDef",
     "ACLsUpdateStatusTypeDef",
     "AuthenticationModeTypeDef",
     "AuthenticationTypeDef",
     "AvailabilityZoneTypeDef",
     "ServiceUpdateRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedClusterTypeDef",
     "PendingModifiedServiceUpdateTypeDef",
     "EndpointTypeDef",
     "SecurityGroupMembershipTypeDef",
     "TagTypeDef",
     "ParameterGroupTypeDef",
     "DeleteACLRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteParameterGroupRequestRequestTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
     "DeleteSubnetGroupRequestRequestTypeDef",
     "DeleteUserRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
     "DescribeACLsRequestRequestTypeDef",
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
     "DescribeClustersRequestRequestTypeDef",
+    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
     "DescribeEngineVersionsRequestRequestTypeDef",
     "EngineVersionInfoTypeDef",
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     "DescribeEventsRequestRequestTypeDef",
     "EventTypeDef",
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
     "DescribeParameterGroupsRequestRequestTypeDef",
+    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
     "DescribeParametersRequestRequestTypeDef",
     "ParameterTypeDef",
+    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
     "DescribeReservedNodesOfferingsRequestRequestTypeDef",
+    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
     "DescribeReservedNodesRequestRequestTypeDef",
+    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
     "DescribeServiceUpdatesRequestRequestTypeDef",
     "ServiceUpdateTypeDef",
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
     "DescribeSnapshotsRequestRequestTypeDef",
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
     "DescribeSubnetGroupsRequestRequestTypeDef",
     "FilterTypeDef",
     "FailoverShardRequestRequestTypeDef",
     "ListAllowedNodeTypeUpdatesRequestRequestTypeDef",
+    "ListAllowedNodeTypeUpdatesResponseTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterNameValueTypeDef",
     "RecurringChargeTypeDef",
     "ReplicaConfigurationRequestTypeDef",
     "ResetParameterGroupRequestRequestTypeDef",
     "SlotMigrationTypeDef",
+    "ResponseMetadataTypeDef",
     "ShardConfigurationRequestTypeDef",
     "ShardConfigurationTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateACLRequestRequestTypeDef",
     "UpdateSubnetGroupRequestRequestTypeDef",
     "ACLTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UserTypeDef",
     "SubnetTypeDef",
     "BatchUpdateClusterRequestRequestTypeDef",
-    "ListAllowedNodeTypeUpdatesResponseTypeDef",
     "NodeTypeDef",
     "CopySnapshotRequestRequestTypeDef",
     "CreateACLRequestRequestTypeDef",
     "CreateClusterRequestRequestTypeDef",
     "CreateParameterGroupRequestRequestTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "CreateSubnetGroupRequestRequestTypeDef",
@@ -102,25 +114,14 @@
     "TagResourceResponseTypeDef",
     "UntagResourceResponseTypeDef",
     "CreateParameterGroupResponseTypeDef",
     "DeleteParameterGroupResponseTypeDef",
     "DescribeParameterGroupsResponseTypeDef",
     "ResetParameterGroupResponseTypeDef",
     "UpdateParameterGroupResponseTypeDef",
-    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    "DescribeParametersRequestDescribeParametersPaginateTypeDef",
-    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
-    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
-    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
     "DescribeEngineVersionsResponseTypeDef",
     "DescribeEventsResponseTypeDef",
     "DescribeParametersResponseTypeDef",
     "DescribeServiceUpdatesResponseTypeDef",
     "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     "DescribeUsersRequestRequestTypeDef",
     "UpdateParameterGroupRequestRequestTypeDef",
@@ -178,15 +179,15 @@
     },
     total=False,
 )
 
 AuthenticationModeTypeDef = TypedDict(
     "AuthenticationModeTypeDef",
     {
-        "Type": Literal["password"],
+        "Type": InputAuthenticationTypeType,
         "Passwords": Sequence[str],
     },
     total=False,
 )
 
 AuthenticationTypeDef = TypedDict(
     "AuthenticationTypeDef",
@@ -209,25 +210,14 @@
     "ServiceUpdateRequestTypeDef",
     {
         "ServiceUpdateNameToApply": str,
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
 UnprocessedClusterTypeDef = TypedDict(
     "UnprocessedClusterTypeDef",
     {
         "ClusterName": str,
         "ErrorType": str,
         "ErrorMessage": str,
     },
@@ -331,45 +321,65 @@
 DeleteUserRequestRequestTypeDef = TypedDict(
     "DeleteUserRequestRequestTypeDef",
     {
         "UserName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeACLsRequestDescribeACLsPaginateTypeDef = TypedDict(
+    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ACLName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeACLsRequestRequestTypeDef = TypedDict(
     "DescribeACLsRequestRequestTypeDef",
     {
         "ACLName": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
+    {
+        "ClusterName": str,
+        "ShowShardDetails": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "ClusterName": str,
         "MaxResults": int,
         "NextToken": str,
         "ShowShardDetails": bool,
     },
     total=False,
 )
 
+DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef = TypedDict(
+    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
+    {
+        "EngineVersion": str,
+        "ParameterGroupFamily": str,
+        "DefaultOnly": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEngineVersionsRequestRequestTypeDef = TypedDict(
     "DescribeEngineVersionsRequestRequestTypeDef",
     {
         "EngineVersion": str,
         "ParameterGroupFamily": str,
         "MaxResults": int,
         "NextToken": str,
@@ -384,14 +394,27 @@
         "EngineVersion": str,
         "EnginePatchVersion": str,
         "ParameterGroupFamily": str,
     },
     total=False,
 )
 
+DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "SourceName": str,
+        "SourceType": SourceTypeType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "Duration": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsRequestRequestTypeDef = TypedDict(
     "DescribeEventsRequestRequestTypeDef",
     {
         "SourceName": str,
         "SourceType": SourceTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -409,24 +432,53 @@
         "SourceType": SourceTypeType,
         "Message": str,
         "Date": datetime,
     },
     total=False,
 )
 
+DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
+    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
+    {
+        "ParameterGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeParameterGroupsRequestRequestTypeDef = TypedDict(
     "DescribeParameterGroupsRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "ParameterGroupName": str,
+    },
+)
+_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeParametersRequestDescribeParametersPaginateTypeDef(
+    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
+    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeParametersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeParametersRequestRequestTypeDef",
     {
         "ParameterGroupName": str,
     },
 )
 _OptionalDescribeParametersRequestRequestTypeDef = TypedDict(
@@ -453,41 +505,77 @@
         "DataType": str,
         "AllowedValues": str,
         "MinimumEngineVersion": str,
     },
     total=False,
 )
 
+DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef = TypedDict(
+    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
+    {
+        "ReservedNodesOfferingId": str,
+        "NodeType": str,
+        "Duration": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedNodesOfferingsRequestRequestTypeDef = TypedDict(
     "DescribeReservedNodesOfferingsRequestRequestTypeDef",
     {
         "ReservedNodesOfferingId": str,
         "NodeType": str,
         "Duration": str,
         "OfferingType": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef = TypedDict(
+    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
+    {
+        "ReservationId": str,
+        "ReservedNodesOfferingId": str,
+        "NodeType": str,
+        "Duration": str,
+        "OfferingType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReservedNodesRequestRequestTypeDef = TypedDict(
     "DescribeReservedNodesRequestRequestTypeDef",
     {
         "ReservationId": str,
         "ReservedNodesOfferingId": str,
         "NodeType": str,
         "Duration": str,
         "OfferingType": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef = TypedDict(
+    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
+    {
+        "ServiceUpdateName": str,
+        "ClusterNames": Sequence[str],
+        "Status": Sequence[ServiceUpdateStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeServiceUpdatesRequestRequestTypeDef = TypedDict(
     "DescribeServiceUpdatesRequestRequestTypeDef",
     {
         "ServiceUpdateName": str,
         "ClusterNames": Sequence[str],
         "Status": Sequence[ServiceUpdateStatusType],
         "MaxResults": int,
@@ -507,27 +595,48 @@
         "Type": Literal["security-update"],
         "NodesUpdated": str,
         "AutoUpdateStartDate": datetime,
     },
     total=False,
 )
 
+DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
+    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
+    {
+        "ClusterName": str,
+        "SnapshotName": str,
+        "Source": str,
+        "ShowDetail": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSnapshotsRequestRequestTypeDef = TypedDict(
     "DescribeSnapshotsRequestRequestTypeDef",
     {
         "ClusterName": str,
         "SnapshotName": str,
         "Source": str,
         "NextToken": str,
         "MaxResults": int,
         "ShowDetail": bool,
     },
     total=False,
 )
 
+DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
+    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
+    {
+        "SubnetGroupName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeSubnetGroupsRequestRequestTypeDef = TypedDict(
     "DescribeSubnetGroupsRequestRequestTypeDef",
     {
         "SubnetGroupName": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -553,21 +662,40 @@
 ListAllowedNodeTypeUpdatesRequestRequestTypeDef = TypedDict(
     "ListAllowedNodeTypeUpdatesRequestRequestTypeDef",
     {
         "ClusterName": str,
     },
 )
 
+ListAllowedNodeTypeUpdatesResponseTypeDef = TypedDict(
+    "ListAllowedNodeTypeUpdatesResponseTypeDef",
+    {
+        "ScaleUpNodeTypes": List[str],
+        "ScaleDownNodeTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
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
 ParameterNameValueTypeDef = TypedDict(
     "ParameterNameValueTypeDef",
     {
         "ParameterName": str,
         "ParameterValue": str,
     },
     total=False,
@@ -615,14 +743,25 @@
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
 ShardConfigurationRequestTypeDef = TypedDict(
     "ShardConfigurationRequestTypeDef",
     {
         "ShardCount": int,
     },
     total=False,
 )
@@ -757,23 +896,14 @@
 
 class BatchUpdateClusterRequestRequestTypeDef(
     _RequiredBatchUpdateClusterRequestRequestTypeDef,
     _OptionalBatchUpdateClusterRequestRequestTypeDef,
 ):
     pass
 
-ListAllowedNodeTypeUpdatesResponseTypeDef = TypedDict(
-    "ListAllowedNodeTypeUpdatesResponseTypeDef",
-    {
-        "ScaleUpNodeTypes": List[str],
-        "ScaleDownNodeTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 NodeTypeDef = TypedDict(
     "NodeTypeDef",
     {
         "Name": str,
         "Status": str,
         "AvailabilityZone": str,
         "CreateTime": datetime,
@@ -948,15 +1078,15 @@
 ):
     pass
 
 ListTagsResponseTypeDef = TypedDict(
     "ListTagsResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPurchaseReservedNodesOfferingRequestRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedNodesOfferingRequestRequestTypeDef",
     {
         "ReservedNodesOfferingId": str,
@@ -986,238 +1116,109 @@
     },
 )
 
 TagResourceResponseTypeDef = TypedDict(
     "TagResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourceResponseTypeDef = TypedDict(
     "UntagResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateParameterGroupResponseTypeDef = TypedDict(
     "CreateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteParameterGroupResponseTypeDef = TypedDict(
     "DeleteParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParameterGroupsResponseTypeDef = TypedDict(
     "DescribeParameterGroupsResponseTypeDef",
     {
         "NextToken": str,
         "ParameterGroups": List[ParameterGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetParameterGroupResponseTypeDef = TypedDict(
     "ResetParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateParameterGroupResponseTypeDef = TypedDict(
     "UpdateParameterGroupResponseTypeDef",
     {
         "ParameterGroup": ParameterGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeACLsRequestDescribeACLsPaginateTypeDef = TypedDict(
-    "DescribeACLsRequestDescribeACLsPaginateTypeDef",
-    {
-        "ACLName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    {
-        "ClusterName": str,
-        "ShowShardDetails": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef = TypedDict(
-    "DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef",
-    {
-        "EngineVersion": str,
-        "ParameterGroupFamily": str,
-        "DefaultOnly": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "SourceName": str,
-        "SourceType": SourceTypeType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "Duration": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef = TypedDict(
-    "DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef",
-    {
-        "ParameterGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "ParameterGroupName": str,
-    },
-)
-_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeParametersRequestDescribeParametersPaginateTypeDef(
-    _RequiredDescribeParametersRequestDescribeParametersPaginateTypeDef,
-    _OptionalDescribeParametersRequestDescribeParametersPaginateTypeDef,
-):
-    pass
-
-DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef = TypedDict(
-    "DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef",
-    {
-        "ReservedNodesOfferingId": str,
-        "NodeType": str,
-        "Duration": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef = TypedDict(
-    "DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef",
-    {
-        "ReservationId": str,
-        "ReservedNodesOfferingId": str,
-        "NodeType": str,
-        "Duration": str,
-        "OfferingType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef = TypedDict(
-    "DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef",
-    {
-        "ServiceUpdateName": str,
-        "ClusterNames": Sequence[str],
-        "Status": Sequence[ServiceUpdateStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef = TypedDict(
-    "DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef",
-    {
-        "ClusterName": str,
-        "SnapshotName": str,
-        "Source": str,
-        "ShowDetail": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef = TypedDict(
-    "DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef",
-    {
-        "SubnetGroupName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeEngineVersionsResponseTypeDef = TypedDict(
     "DescribeEngineVersionsResponseTypeDef",
     {
         "NextToken": str,
         "EngineVersions": List[EngineVersionInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "NextToken": str,
         "Events": List[EventTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParametersResponseTypeDef = TypedDict(
     "DescribeParametersResponseTypeDef",
     {
         "NextToken": str,
         "Parameters": List[ParameterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceUpdatesResponseTypeDef = TypedDict(
     "DescribeServiceUpdatesResponseTypeDef",
     {
         "NextToken": str,
         "ServiceUpdates": List[ServiceUpdateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsersRequestDescribeUsersPaginateTypeDef = TypedDict(
     "DescribeUsersRequestDescribeUsersPaginateTypeDef",
     {
         "UserName": str,
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeUsersRequestRequestTypeDef = TypedDict(
     "DescribeUsersRequestRequestTypeDef",
     {
@@ -1318,73 +1319,73 @@
     total=False,
 )
 
 CreateACLResponseTypeDef = TypedDict(
     "CreateACLResponseTypeDef",
     {
         "ACL": ACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteACLResponseTypeDef = TypedDict(
     "DeleteACLResponseTypeDef",
     {
         "ACL": ACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeACLsResponseTypeDef = TypedDict(
     "DescribeACLsResponseTypeDef",
     {
         "ACLs": List[ACLTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateACLResponseTypeDef = TypedDict(
     "UpdateACLResponseTypeDef",
     {
         "ACL": ACLTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteUserResponseTypeDef = TypedDict(
     "DeleteUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUsersResponseTypeDef = TypedDict(
     "DescribeUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubnetGroupTypeDef = TypedDict(
     "SubnetGroupTypeDef",
     {
         "Name": str,
@@ -1409,32 +1410,32 @@
 )
 
 DescribeReservedNodesResponseTypeDef = TypedDict(
     "DescribeReservedNodesResponseTypeDef",
     {
         "NextToken": str,
         "ReservedNodes": List[ReservedNodeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseReservedNodesOfferingResponseTypeDef = TypedDict(
     "PurchaseReservedNodesOfferingResponseTypeDef",
     {
         "ReservedNode": ReservedNodeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedNodesOfferingsResponseTypeDef = TypedDict(
     "DescribeReservedNodesOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "ReservedNodesOfferings": List[ReservedNodesOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterPendingUpdatesTypeDef = TypedDict(
     "ClusterPendingUpdatesTypeDef",
     {
         "Resharding": ReshardingStatusTypeDef,
@@ -1465,40 +1466,40 @@
     total=False,
 )
 
 CreateSubnetGroupResponseTypeDef = TypedDict(
     "CreateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSubnetGroupResponseTypeDef = TypedDict(
     "DeleteSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSubnetGroupsResponseTypeDef = TypedDict(
     "DescribeSubnetGroupsResponseTypeDef",
     {
         "NextToken": str,
         "SubnetGroups": List[SubnetGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSubnetGroupResponseTypeDef = TypedDict(
     "UpdateSubnetGroupResponseTypeDef",
     {
         "SubnetGroup": SubnetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterTypeDef = TypedDict(
     "ClusterTypeDef",
     {
         "Name": str,
@@ -1546,84 +1547,84 @@
 )
 
 BatchUpdateClusterResponseTypeDef = TypedDict(
     "BatchUpdateClusterResponseTypeDef",
     {
         "ProcessedClusters": List[ClusterTypeDef],
         "UnprocessedClusters": List[UnprocessedClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClustersResponseTypeDef = TypedDict(
     "DescribeClustersResponseTypeDef",
     {
         "NextToken": str,
         "Clusters": List[ClusterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverShardResponseTypeDef = TypedDict(
     "FailoverShardResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterResponseTypeDef = TypedDict(
     "UpdateClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopySnapshotResponseTypeDef = TypedDict(
     "CopySnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSnapshotResponseTypeDef = TypedDict(
     "CreateSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSnapshotResponseTypeDef = TypedDict(
     "DeleteSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsResponseTypeDef = TypedDict(
     "DescribeSnapshotsResponseTypeDef",
     {
         "NextToken": str,
         "Snapshots": List[SnapshotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/PKG-INFO` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-memorydb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MemoryDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MemoryDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-memorydb"></a>
 
 # types-aiobotocore-memorydb
 
 [![PyPI - types-aiobotocore-memorydb](https://img.shields.io/pypi/v/types-aiobotocore-memorydb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-memorydb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-memorydb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-memorydb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-memorydb?color=blue)](https://pypistats.org/packages/types-aiobotocore-memorydb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MemoryDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB)
+[aiobotocore.MemoryDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/memorydb.html#MemoryDB)
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
 [types-aiobotocore-memorydb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_memorydb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -379,63 +379,74 @@
 from types_aiobotocore_memorydb.type_defs import (
     ACLPendingChangesTypeDef,
     ACLsUpdateStatusTypeDef,
     AuthenticationModeTypeDef,
     AuthenticationTypeDef,
     AvailabilityZoneTypeDef,
     ServiceUpdateRequestTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedClusterTypeDef,
     PendingModifiedServiceUpdateTypeDef,
     EndpointTypeDef,
     SecurityGroupMembershipTypeDef,
     TagTypeDef,
     ParameterGroupTypeDef,
     DeleteACLRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteParameterGroupRequestRequestTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
     DeleteSubnetGroupRequestRequestTypeDef,
     DeleteUserRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeACLsRequestDescribeACLsPaginateTypeDef,
     DescribeACLsRequestRequestTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
+    DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef,
     DescribeEngineVersionsRequestRequestTypeDef,
     EngineVersionInfoTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     EventTypeDef,
+    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
     DescribeParameterGroupsRequestRequestTypeDef,
+    DescribeParametersRequestDescribeParametersPaginateTypeDef,
     DescribeParametersRequestRequestTypeDef,
     ParameterTypeDef,
+    DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef,
     DescribeReservedNodesOfferingsRequestRequestTypeDef,
+    DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef,
     DescribeReservedNodesRequestRequestTypeDef,
+    DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef,
     DescribeServiceUpdatesRequestRequestTypeDef,
     ServiceUpdateTypeDef,
+    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
+    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeSubnetGroupsRequestRequestTypeDef,
     FilterTypeDef,
     FailoverShardRequestRequestTypeDef,
     ListAllowedNodeTypeUpdatesRequestRequestTypeDef,
+    ListAllowedNodeTypeUpdatesResponseTypeDef,
     ListTagsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterNameValueTypeDef,
     RecurringChargeTypeDef,
     ReplicaConfigurationRequestTypeDef,
     ResetParameterGroupRequestRequestTypeDef,
     SlotMigrationTypeDef,
+    ResponseMetadataTypeDef,
     ShardConfigurationRequestTypeDef,
     ShardConfigurationTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateACLRequestRequestTypeDef,
     UpdateSubnetGroupRequestRequestTypeDef,
     ACLTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserTypeDef,
     SubnetTypeDef,
     BatchUpdateClusterRequestRequestTypeDef,
-    ListAllowedNodeTypeUpdatesResponseTypeDef,
     NodeTypeDef,
     CopySnapshotRequestRequestTypeDef,
     CreateACLRequestRequestTypeDef,
     CreateClusterRequestRequestTypeDef,
     CreateParameterGroupRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     CreateSubnetGroupRequestRequestTypeDef,
@@ -446,25 +457,14 @@
     TagResourceResponseTypeDef,
     UntagResourceResponseTypeDef,
     CreateParameterGroupResponseTypeDef,
     DeleteParameterGroupResponseTypeDef,
     DescribeParameterGroupsResponseTypeDef,
     ResetParameterGroupResponseTypeDef,
     UpdateParameterGroupResponseTypeDef,
-    DescribeACLsRequestDescribeACLsPaginateTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    DescribeEngineVersionsRequestDescribeEngineVersionsPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeParameterGroupsRequestDescribeParameterGroupsPaginateTypeDef,
-    DescribeParametersRequestDescribeParametersPaginateTypeDef,
-    DescribeReservedNodesOfferingsRequestDescribeReservedNodesOfferingsPaginateTypeDef,
-    DescribeReservedNodesRequestDescribeReservedNodesPaginateTypeDef,
-    DescribeServiceUpdatesRequestDescribeServiceUpdatesPaginateTypeDef,
-    DescribeSnapshotsRequestDescribeSnapshotsPaginateTypeDef,
-    DescribeSubnetGroupsRequestDescribeSubnetGroupsPaginateTypeDef,
     DescribeEngineVersionsResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeParametersResponseTypeDef,
     DescribeServiceUpdatesResponseTypeDef,
     DescribeUsersRequestDescribeUsersPaginateTypeDef,
     DescribeUsersRequestRequestTypeDef,
     UpdateParameterGroupRequestRequestTypeDef,
@@ -514,43 +514,43 @@
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

### Comparing `types-aiobotocore-memorydb-2.5.0.post1/types_aiobotocore_memorydb.egg-info/SOURCES.txt` & `types-aiobotocore-memorydb-2.5.1/types_aiobotocore_memorydb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

