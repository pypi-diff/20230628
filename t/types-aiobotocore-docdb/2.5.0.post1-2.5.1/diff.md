# Comparing `tmp/types-aiobotocore-docdb-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-docdb-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-docdb-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:31 2023, max compression
+gzip compressed data, was "types-aiobotocore-docdb-2.5.1.tar", last modified: Wed Jun 28 01:43:24 2023, max compression
```

## Comparing `types-aiobotocore-docdb-2.5.0.post1.tar` & `types-aiobotocore-docdb-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.943146 types-aiobotocore-docdb-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    23237 2023-03-11 12:26:31.935146 types-aiobotocore-docdb-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    21674 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:31.943146 types-aiobotocore-docdb-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.935146 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/
--rw-r--r--   0 runner    (1001) docker     (123)     4193 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4192 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    53668 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    53591 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10522 2023-03-11 12:12:39.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10520 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    18214 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    18198 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    60403 2023-03-11 12:12:41.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    60350 2023-03-11 12:12:39.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2863 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2861 2023-03-11 12:12:38.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.935146 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    23237 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      844 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:26:31.000000 types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.606127 types-aiobotocore-docdb-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    23227 2023-06-28 01:43:24.606127 types-aiobotocore-docdb-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21670 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:24.606127 types-aiobotocore-docdb-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.602127 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/
+-rw-r--r--   0 runner    (1001) docker     (123)     4193 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4192 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53716 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53639 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10731 2023-06-28 01:29:18.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10729 2023-06-28 01:29:18.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    18120 2023-06-28 01:29:18.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18105 2023-06-28 01:29:18.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    60571 2023-06-28 01:29:19.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60518 2023-06-28 01:29:18.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:17.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2863 2023-06-28 01:29:18.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2861 2023-06-28 01:29:18.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.606127 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23227 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      844 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:43:24.000000 types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-docdb-2.5.0.post1/LICENSE` & `types-aiobotocore-docdb-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/PKG-INFO` & `types-aiobotocore-docdb-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-docdb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DocDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DocDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-docdb"></a>
 
 # types-aiobotocore-docdb
 
 [![PyPI - types-aiobotocore-docdb](https://img.shields.io/pypi/v/types-aiobotocore-docdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-docdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-docdb?color=blue)](https://pypistats.org/packages/types-aiobotocore-docdb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DocDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB)
+[aiobotocore.DocDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB)
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
 [types-aiobotocore-docdb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -407,64 +407,64 @@
 `types_aiobotocore_docdb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_docdb.type_defs import (
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     CertificateTypeDef,
     CloudwatchLogsExportConfigurationTypeDef,
     DBClusterParameterGroupTypeDef,
     DBClusterSnapshotTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     DBClusterMemberTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     UpgradeTargetTypeDef,
     DBInstanceStatusInfoTypeDef,
     EndpointTypeDef,
     DeleteDBClusterMessageRequestTypeDef,
     DeleteDBClusterParameterGroupMessageRequestTypeDef,
     DeleteDBClusterSnapshotMessageRequestTypeDef,
     DeleteDBInstanceMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     GlobalClusterMemberTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBInstanceMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
+    PaginatorConfigTypeDef,
     PendingCloudwatchLogsExportsTypeDef,
     PendingMaintenanceActionTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StopDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
     CreateEventSubscriptionResultTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
     DeleteEventSubscriptionResultTypeDef,
-    EmptyResponseMetadataTypeDef,
     EventSubscriptionsMessageTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopyDBClusterParameterGroupMessageRequestTypeDef,
     CopyDBClusterSnapshotMessageRequestTypeDef,
     CreateDBClusterMessageRequestTypeDef,
@@ -490,43 +490,43 @@
     DBClusterParameterGroupDetailsTypeDef,
     EngineDefaultsTypeDef,
     ModifyDBClusterParameterGroupMessageRequestTypeDef,
     ResetDBClusterParameterGroupMessageRequestTypeDef,
     DBClusterSnapshotAttributesResultTypeDef,
     DBClusterTypeDef,
     DBEngineVersionTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
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
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
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
     PendingModifiedValuesTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
@@ -571,43 +571,43 @@
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/README.md` & `types-aiobotocore-docdb-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-docdb"></a>
 
 # types-aiobotocore-docdb
 
 [![PyPI - types-aiobotocore-docdb](https://img.shields.io/pypi/v/types-aiobotocore-docdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-docdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-docdb?color=blue)](https://pypistats.org/packages/types-aiobotocore-docdb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DocDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB)
+[aiobotocore.DocDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB)
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
 [types-aiobotocore-docdb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -374,64 +374,64 @@
 `types_aiobotocore_docdb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_docdb.type_defs import (
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     CertificateTypeDef,
     CloudwatchLogsExportConfigurationTypeDef,
     DBClusterParameterGroupTypeDef,
     DBClusterSnapshotTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     DBClusterMemberTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     UpgradeTargetTypeDef,
     DBInstanceStatusInfoTypeDef,
     EndpointTypeDef,
     DeleteDBClusterMessageRequestTypeDef,
     DeleteDBClusterParameterGroupMessageRequestTypeDef,
     DeleteDBClusterSnapshotMessageRequestTypeDef,
     DeleteDBInstanceMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     GlobalClusterMemberTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBInstanceMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
+    PaginatorConfigTypeDef,
     PendingCloudwatchLogsExportsTypeDef,
     PendingMaintenanceActionTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StopDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
     CreateEventSubscriptionResultTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
     DeleteEventSubscriptionResultTypeDef,
-    EmptyResponseMetadataTypeDef,
     EventSubscriptionsMessageTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopyDBClusterParameterGroupMessageRequestTypeDef,
     CopyDBClusterSnapshotMessageRequestTypeDef,
     CreateDBClusterMessageRequestTypeDef,
@@ -457,43 +457,43 @@
     DBClusterParameterGroupDetailsTypeDef,
     EngineDefaultsTypeDef,
     ModifyDBClusterParameterGroupMessageRequestTypeDef,
     ResetDBClusterParameterGroupMessageRequestTypeDef,
     DBClusterSnapshotAttributesResultTypeDef,
     DBClusterTypeDef,
     DBEngineVersionTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
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
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
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
     PendingModifiedValuesTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
@@ -538,43 +538,43 @@
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/setup.py` & `types-aiobotocore-docdb-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-docdb.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-docdb",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_docdb"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DocDB 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.DocDB 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/"
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/__init__.py` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/__init__.pyi` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/__main__.py` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DocDB 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DocDB 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB\nOther"
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/client.py` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -949,15 +949,16 @@
         EngineVersion: str = ...,
         Port: int = ...,
         DBSubnetGroupName: str = ...,
         VpcSecurityGroupIds: Sequence[str] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         KmsKeyId: str = ...,
         EnableCloudwatchLogsExports: Sequence[str] = ...,
-        DeletionProtection: bool = ...
+        DeletionProtection: bool = ...,
+        DBClusterParameterGroupName: str = ...
     ) -> RestoreDBClusterFromSnapshotResultTypeDef:
         """
         Creates a new cluster from a snapshot or cluster snapshot.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Client.restore_db_cluster_from_snapshot)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/client/#restore_db_cluster_from_snapshot)
         """
```

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/client.pyi` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -892,15 +892,16 @@
         EngineVersion: str = ...,
         Port: int = ...,
         DBSubnetGroupName: str = ...,
         VpcSecurityGroupIds: Sequence[str] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         KmsKeyId: str = ...,
         EnableCloudwatchLogsExports: Sequence[str] = ...,
-        DeletionProtection: bool = ...
+        DeletionProtection: bool = ...,
+        DBClusterParameterGroupName: str = ...
     ) -> RestoreDBClusterFromSnapshotResultTypeDef:
         """
         Creates a new cluster from a snapshot or cluster snapshot.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Client.restore_db_cluster_from_snapshot)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/client/#restore_db_cluster_from_snapshot)
         """
```

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/literals.py` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -129,14 +129,15 @@
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
@@ -215,14 +216,15 @@
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
@@ -233,14 +235,15 @@
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
@@ -276,14 +279,15 @@
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
@@ -302,16 +306,19 @@
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
@@ -395,15 +402,17 @@
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/literals.pyi` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -127,14 +127,15 @@
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
@@ -213,14 +214,15 @@
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
@@ -231,14 +233,15 @@
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
@@ -274,14 +277,15 @@
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
@@ -300,16 +304,19 @@
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
@@ -393,15 +400,17 @@
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/paginator.py` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -40,17 +40,16 @@
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
     CertificateMessageTypeDef,
@@ -66,20 +65,14 @@
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
     "DescribeCertificatesPaginator",
     "DescribeDBClusterParameterGroupsPaginator",
     "DescribeDBClusterParametersPaginator",
     "DescribeDBClusterSnapshotsPaginator",
     "DescribeDBClustersPaginator",
     "DescribeDBEngineVersionsPaginator",
@@ -110,15 +103,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describecertificatespaginator)
         """
 
 
@@ -129,15 +122,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclusterparametergroupspaginator)
         """
 
 
@@ -149,15 +142,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclusterparameterspaginator)
         """
 
 
@@ -172,15 +165,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclustersnapshotspaginator)
         """
 
 
@@ -191,15 +184,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclusterspaginator)
         """
 
 
@@ -215,15 +208,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbengineversionspaginator)
         """
 
 
@@ -234,15 +227,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbinstancespaginator)
         """
 
 
@@ -253,15 +246,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbsubnetgroupspaginator)
         """
 
 
@@ -272,15 +265,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeeventsubscriptionspaginator)
         """
 
 
@@ -296,15 +289,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeeventspaginator)
         """
 
 
@@ -315,15 +308,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeGlobalClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeglobalclusterspaginator)
         """
 
 
@@ -338,15 +331,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeOrderableDBInstanceOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeorderabledbinstanceoptionspaginator)
         """
 
 
@@ -357,13 +350,13 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribePendingMaintenanceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describependingmaintenanceactionspaginator)
         """
```

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/paginator.pyi` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -40,17 +40,16 @@
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
     CertificateMessageTypeDef,
@@ -66,19 +65,14 @@
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
     "DescribeCertificatesPaginator",
     "DescribeDBClusterParameterGroupsPaginator",
     "DescribeDBClusterParametersPaginator",
     "DescribeDBClusterSnapshotsPaginator",
     "DescribeDBClustersPaginator",
     "DescribeDBEngineVersionsPaginator",
@@ -106,15 +100,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeCertificates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describecertificatespaginator)
         """
 
 class DescribeDBClusterParameterGroupsPaginator(AioPaginator):
@@ -124,15 +118,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterParameterGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclusterparametergroupspaginator)
         """
 
 class DescribeDBClusterParametersPaginator(AioPaginator):
@@ -143,15 +137,15 @@
 
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclusterparameterspaginator)
         """
 
 class DescribeDBClusterSnapshotsPaginator(AioPaginator):
@@ -165,15 +159,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusterSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclustersnapshotspaginator)
         """
 
 class DescribeDBClustersPaginator(AioPaginator):
@@ -183,15 +177,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbclusterspaginator)
         """
 
 class DescribeDBEngineVersionsPaginator(AioPaginator):
@@ -206,15 +200,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBEngineVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbengineversionspaginator)
         """
 
 class DescribeDBInstancesPaginator(AioPaginator):
@@ -224,15 +218,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbinstancespaginator)
         """
 
 class DescribeDBSubnetGroupsPaginator(AioPaginator):
@@ -242,15 +236,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeDBSubnetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describedbsubnetgroupspaginator)
         """
 
 class DescribeEventSubscriptionsPaginator(AioPaginator):
@@ -260,15 +254,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeeventsubscriptionspaginator)
         """
 
 class DescribeEventsPaginator(AioPaginator):
@@ -283,15 +277,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeeventspaginator)
         """
 
 class DescribeGlobalClustersPaginator(AioPaginator):
@@ -301,15 +295,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeGlobalClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeglobalclusterspaginator)
         """
 
 class DescribeOrderableDBInstanceOptionsPaginator(AioPaginator):
@@ -323,15 +317,15 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribeOrderableDBInstanceOptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describeorderabledbinstanceoptionspaginator)
         """
 
 class DescribePendingMaintenanceActionsPaginator(AioPaginator):
@@ -341,13 +335,13 @@
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
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB.Paginator.DescribePendingMaintenanceActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/paginators/#describependingmaintenanceactionspaginator)
         """
```

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/type_defs.py` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,64 +22,64 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AddSourceIdentifierToSubscriptionMessageRequestTypeDef",
     "EventSubscriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
     "AvailabilityZoneTypeDef",
     "CertificateTypeDef",
     "CloudwatchLogsExportConfigurationTypeDef",
     "DBClusterParameterGroupTypeDef",
     "DBClusterSnapshotTypeDef",
     "CreateGlobalClusterMessageRequestTypeDef",
     "DBClusterMemberTypeDef",
     "ParameterTypeDef",
+    "DBClusterParameterGroupNameMessageTypeDef",
     "DBClusterRoleTypeDef",
     "DBClusterSnapshotAttributeTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "UpgradeTargetTypeDef",
     "DBInstanceStatusInfoTypeDef",
     "EndpointTypeDef",
     "DeleteDBClusterMessageRequestTypeDef",
     "DeleteDBClusterParameterGroupMessageRequestTypeDef",
     "DeleteDBClusterSnapshotMessageRequestTypeDef",
     "DeleteDBInstanceMessageRequestTypeDef",
     "DeleteDBSubnetGroupMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteGlobalClusterMessageRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     "WaiterConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventCategoriesMapTypeDef",
     "EventTypeDef",
     "FailoverDBClusterMessageRequestTypeDef",
     "GlobalClusterMemberTypeDef",
     "ModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBInstanceMessageRequestTypeDef",
     "ModifyDBSubnetGroupMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyGlobalClusterMessageRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingCloudwatchLogsExportsTypeDef",
     "PendingMaintenanceActionTypeDef",
     "RebootDBInstanceMessageRequestTypeDef",
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     "RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDBClusterMessageRequestTypeDef",
     "StopDBClusterMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     "CreateEventSubscriptionResultTypeDef",
-    "DBClusterParameterGroupNameMessageTypeDef",
     "DeleteEventSubscriptionResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EventSubscriptionsMessageTypeDef",
     "ModifyEventSubscriptionResultTypeDef",
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CopyDBClusterParameterGroupMessageRequestTypeDef",
     "CopyDBClusterSnapshotMessageRequestTypeDef",
     "CreateDBClusterMessageRequestTypeDef",
@@ -105,43 +105,43 @@
     "DBClusterParameterGroupDetailsTypeDef",
     "EngineDefaultsTypeDef",
     "ModifyDBClusterParameterGroupMessageRequestTypeDef",
     "ResetDBClusterParameterGroupMessageRequestTypeDef",
     "DBClusterSnapshotAttributesResultTypeDef",
     "DBClusterTypeDef",
     "DBEngineVersionTypeDef",
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
     "DescribeCertificatesMessageRequestTypeDef",
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
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
     "DescribeDBSubnetGroupsMessageRequestTypeDef",
     "DescribeEngineDefaultClusterParametersMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
     "DescribeGlobalClustersMessageRequestTypeDef",
+    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
     "DescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
-    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
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
     "PendingModifiedValuesTypeDef",
     "ResourcePendingMaintenanceActionsTypeDef",
@@ -199,25 +199,14 @@
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
@@ -348,14 +337,22 @@
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
     },
     total=False,
@@ -480,24 +477,14 @@
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
 
@@ -506,14 +493,21 @@
     {
         "Delay": int,
         "MaxAttempts": int,
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
@@ -672,14 +666,24 @@
 class ModifyGlobalClusterMessageRequestTypeDef(
     _RequiredModifyGlobalClusterMessageRequestTypeDef,
     _OptionalModifyGlobalClusterMessageRequestTypeDef,
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
+
 PendingCloudwatchLogsExportsTypeDef = TypedDict(
     "PendingCloudwatchLogsExportsTypeDef",
     {
         "LogTypesToEnable": List[str],
         "LogTypesToDisable": List[str],
     },
     total=False,
@@ -739,14 +743,25 @@
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
 
@@ -757,71 +772,56 @@
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
-    },
-)
-
-DBClusterParameterGroupNameMessageTypeDef = TypedDict(
-    "DBClusterParameterGroupNameMessageTypeDef",
-    {
-        "DBClusterParameterGroupName": str,
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
@@ -1065,14 +1065,15 @@
         "Port": int,
         "DBSubnetGroupName": str,
         "VpcSecurityGroupIds": Sequence[str],
         "Tags": Sequence[TagTypeDef],
         "KmsKeyId": str,
         "EnableCloudwatchLogsExports": Sequence[str],
         "DeletionProtection": bool,
+        "DBClusterParameterGroupName": str,
     },
     total=False,
 )
 
 
 class RestoreDBClusterFromSnapshotMessageRequestTypeDef(
     _RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef,
@@ -1113,15 +1114,15 @@
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
@@ -1145,15 +1146,15 @@
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
 
 _RequiredModifyDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
@@ -1185,74 +1186,74 @@
     pass
 
 
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
 
 DBClusterParameterGroupDetailsTypeDef = TypedDict(
     "DBClusterParameterGroupDetailsTypeDef",
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
@@ -1352,36 +1353,80 @@
         "ValidUpgradeTarget": List[UpgradeTargetTypeDef],
         "ExportableLogTypes": List[str],
         "SupportsLogExportsToCloudwatchLogs": bool,
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
@@ -1399,14 +1444,28 @@
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
@@ -1414,25 +1473,50 @@
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
@@ -1441,25 +1525,45 @@
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
@@ -1496,25 +1600,50 @@
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
@@ -1523,25 +1652,62 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
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
@@ -1562,14 +1728,26 @@
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
@@ -1595,191 +1773,14 @@
 class ListTagsForResourceMessageRequestTypeDef(
     _RequiredListTagsForResourceMessageRequestTypeDef,
     _OptionalListTagsForResourceMessageRequestTypeDef,
 ):
     pass
 
 
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
-        "Filters": Sequence[FilterTypeDef],
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
@@ -1800,24 +1801,24 @@
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
@@ -1865,15 +1866,15 @@
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
@@ -1886,179 +1887,179 @@
     total=False,
 )
 
 DescribeEngineDefaultClusterParametersResultTypeDef = TypedDict(
     "DescribeEngineDefaultClusterParametersResultTypeDef",
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
@@ -2093,59 +2094,59 @@
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/type_defs.pyi` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -21,64 +21,64 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AddSourceIdentifierToSubscriptionMessageRequestTypeDef",
     "EventSubscriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "ApplyPendingMaintenanceActionMessageRequestTypeDef",
     "AvailabilityZoneTypeDef",
     "CertificateTypeDef",
     "CloudwatchLogsExportConfigurationTypeDef",
     "DBClusterParameterGroupTypeDef",
     "DBClusterSnapshotTypeDef",
     "CreateGlobalClusterMessageRequestTypeDef",
     "DBClusterMemberTypeDef",
     "ParameterTypeDef",
+    "DBClusterParameterGroupNameMessageTypeDef",
     "DBClusterRoleTypeDef",
     "DBClusterSnapshotAttributeTypeDef",
     "VpcSecurityGroupMembershipTypeDef",
     "UpgradeTargetTypeDef",
     "DBInstanceStatusInfoTypeDef",
     "EndpointTypeDef",
     "DeleteDBClusterMessageRequestTypeDef",
     "DeleteDBClusterParameterGroupMessageRequestTypeDef",
     "DeleteDBClusterSnapshotMessageRequestTypeDef",
     "DeleteDBInstanceMessageRequestTypeDef",
     "DeleteDBSubnetGroupMessageRequestTypeDef",
     "DeleteEventSubscriptionMessageRequestTypeDef",
     "DeleteGlobalClusterMessageRequestTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeDBClusterSnapshotAttributesMessageRequestTypeDef",
     "WaiterConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventCategoriesMapTypeDef",
     "EventTypeDef",
     "FailoverDBClusterMessageRequestTypeDef",
     "GlobalClusterMemberTypeDef",
     "ModifyDBClusterSnapshotAttributeMessageRequestTypeDef",
     "ModifyDBInstanceMessageRequestTypeDef",
     "ModifyDBSubnetGroupMessageRequestTypeDef",
     "ModifyEventSubscriptionMessageRequestTypeDef",
     "ModifyGlobalClusterMessageRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingCloudwatchLogsExportsTypeDef",
     "PendingMaintenanceActionTypeDef",
     "RebootDBInstanceMessageRequestTypeDef",
     "RemoveFromGlobalClusterMessageRequestTypeDef",
     "RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef",
     "RemoveTagsFromResourceMessageRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDBClusterMessageRequestTypeDef",
     "StopDBClusterMessageRequestTypeDef",
     "AddSourceIdentifierToSubscriptionResultTypeDef",
     "CreateEventSubscriptionResultTypeDef",
-    "DBClusterParameterGroupNameMessageTypeDef",
     "DeleteEventSubscriptionResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EventSubscriptionsMessageTypeDef",
     "ModifyEventSubscriptionResultTypeDef",
     "RemoveSourceIdentifierFromSubscriptionResultTypeDef",
     "AddTagsToResourceMessageRequestTypeDef",
     "CopyDBClusterParameterGroupMessageRequestTypeDef",
     "CopyDBClusterSnapshotMessageRequestTypeDef",
     "CreateDBClusterMessageRequestTypeDef",
@@ -104,43 +104,43 @@
     "DBClusterParameterGroupDetailsTypeDef",
     "EngineDefaultsTypeDef",
     "ModifyDBClusterParameterGroupMessageRequestTypeDef",
     "ResetDBClusterParameterGroupMessageRequestTypeDef",
     "DBClusterSnapshotAttributesResultTypeDef",
     "DBClusterTypeDef",
     "DBEngineVersionTypeDef",
+    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
     "DescribeCertificatesMessageRequestTypeDef",
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
+    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
     "DescribeDBSubnetGroupsMessageRequestTypeDef",
     "DescribeEngineDefaultClusterParametersMessageRequestTypeDef",
     "DescribeEventCategoriesMessageRequestTypeDef",
+    "DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef",
     "DescribeEventSubscriptionsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
+    "DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef",
     "DescribeGlobalClustersMessageRequestTypeDef",
+    "DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef",
     "DescribeOrderableDBInstanceOptionsMessageRequestTypeDef",
+    "DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef",
     "DescribePendingMaintenanceActionsMessageRequestTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
-    "DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef",
-    "DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef",
-    "DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef",
-    "DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef",
-    "DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef",
-    "DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef",
-    "DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef",
-    "DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef",
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
     "PendingModifiedValuesTypeDef",
     "ResourcePendingMaintenanceActionsTypeDef",
@@ -198,25 +198,14 @@
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
@@ -345,14 +334,22 @@
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
     },
     total=False,
@@ -475,24 +472,14 @@
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
 
@@ -501,14 +488,21 @@
     {
         "Delay": int,
         "MaxAttempts": int,
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
@@ -657,14 +651,24 @@
 
 class ModifyGlobalClusterMessageRequestTypeDef(
     _RequiredModifyGlobalClusterMessageRequestTypeDef,
     _OptionalModifyGlobalClusterMessageRequestTypeDef,
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
+
 PendingCloudwatchLogsExportsTypeDef = TypedDict(
     "PendingCloudwatchLogsExportsTypeDef",
     {
         "LogTypesToEnable": List[str],
         "LogTypesToDisable": List[str],
     },
     total=False,
@@ -722,14 +726,25 @@
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
 
@@ -740,71 +755,56 @@
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
-    },
-)
-
-DBClusterParameterGroupNameMessageTypeDef = TypedDict(
-    "DBClusterParameterGroupNameMessageTypeDef",
-    {
-        "DBClusterParameterGroupName": str,
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
@@ -1032,14 +1032,15 @@
         "Port": int,
         "DBSubnetGroupName": str,
         "VpcSecurityGroupIds": Sequence[str],
         "Tags": Sequence[TagTypeDef],
         "KmsKeyId": str,
         "EnableCloudwatchLogsExports": Sequence[str],
         "DeletionProtection": bool,
+        "DBClusterParameterGroupName": str,
     },
     total=False,
 )
 
 class RestoreDBClusterFromSnapshotMessageRequestTypeDef(
     _RequiredRestoreDBClusterFromSnapshotMessageRequestTypeDef,
     _OptionalRestoreDBClusterFromSnapshotMessageRequestTypeDef,
@@ -1076,15 +1077,15 @@
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
@@ -1108,15 +1109,15 @@
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
 
 _RequiredModifyDBClusterMessageRequestTypeDef = TypedDict(
     "_RequiredModifyDBClusterMessageRequestTypeDef",
     {
         "DBClusterIdentifier": str,
@@ -1146,74 +1147,74 @@
 ):
     pass
 
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
 
 DBClusterParameterGroupDetailsTypeDef = TypedDict(
     "DBClusterParameterGroupDetailsTypeDef",
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
@@ -1311,36 +1312,78 @@
         "ValidUpgradeTarget": List[UpgradeTargetTypeDef],
         "ExportableLogTypes": List[str],
         "SupportsLogExportsToCloudwatchLogs": bool,
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
@@ -1356,14 +1399,28 @@
 
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
@@ -1371,25 +1428,50 @@
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
@@ -1398,25 +1480,45 @@
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
@@ -1451,25 +1553,50 @@
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
@@ -1478,25 +1605,60 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxRecords": int,
         "Marker": str,
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
@@ -1515,14 +1677,26 @@
 
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
@@ -1546,187 +1720,14 @@
 
 class ListTagsForResourceMessageRequestTypeDef(
     _RequiredListTagsForResourceMessageRequestTypeDef,
     _OptionalListTagsForResourceMessageRequestTypeDef,
 ):
     pass
 
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
-        "Filters": Sequence[FilterTypeDef],
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
@@ -1747,24 +1748,24 @@
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
@@ -1812,15 +1813,15 @@
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
@@ -1833,179 +1834,179 @@
     total=False,
 )
 
 DescribeEngineDefaultClusterParametersResultTypeDef = TypedDict(
     "DescribeEngineDefaultClusterParametersResultTypeDef",
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
@@ -2040,59 +2041,59 @@
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/waiter.py` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb/waiter.pyi` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/PKG-INFO` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-docdb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DocDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DocDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-docdb"></a>
 
 # types-aiobotocore-docdb
 
 [![PyPI - types-aiobotocore-docdb](https://img.shields.io/pypi/v/types-aiobotocore-docdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-docdb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-docdb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-docdb?color=blue)](https://pypistats.org/packages/types-aiobotocore-docdb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DocDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB)
+[aiobotocore.DocDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/docdb.html#DocDB)
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
 [types-aiobotocore-docdb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_docdb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -407,64 +407,64 @@
 `types_aiobotocore_docdb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_docdb.type_defs import (
     AddSourceIdentifierToSubscriptionMessageRequestTypeDef,
     EventSubscriptionTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     ApplyPendingMaintenanceActionMessageRequestTypeDef,
     AvailabilityZoneTypeDef,
     CertificateTypeDef,
     CloudwatchLogsExportConfigurationTypeDef,
     DBClusterParameterGroupTypeDef,
     DBClusterSnapshotTypeDef,
     CreateGlobalClusterMessageRequestTypeDef,
     DBClusterMemberTypeDef,
     ParameterTypeDef,
+    DBClusterParameterGroupNameMessageTypeDef,
     DBClusterRoleTypeDef,
     DBClusterSnapshotAttributeTypeDef,
     VpcSecurityGroupMembershipTypeDef,
     UpgradeTargetTypeDef,
     DBInstanceStatusInfoTypeDef,
     EndpointTypeDef,
     DeleteDBClusterMessageRequestTypeDef,
     DeleteDBClusterParameterGroupMessageRequestTypeDef,
     DeleteDBClusterSnapshotMessageRequestTypeDef,
     DeleteDBInstanceMessageRequestTypeDef,
     DeleteDBSubnetGroupMessageRequestTypeDef,
     DeleteEventSubscriptionMessageRequestTypeDef,
     DeleteGlobalClusterMessageRequestTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeDBClusterSnapshotAttributesMessageRequestTypeDef,
     WaiterConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventCategoriesMapTypeDef,
     EventTypeDef,
     FailoverDBClusterMessageRequestTypeDef,
     GlobalClusterMemberTypeDef,
     ModifyDBClusterSnapshotAttributeMessageRequestTypeDef,
     ModifyDBInstanceMessageRequestTypeDef,
     ModifyDBSubnetGroupMessageRequestTypeDef,
     ModifyEventSubscriptionMessageRequestTypeDef,
     ModifyGlobalClusterMessageRequestTypeDef,
+    PaginatorConfigTypeDef,
     PendingCloudwatchLogsExportsTypeDef,
     PendingMaintenanceActionTypeDef,
     RebootDBInstanceMessageRequestTypeDef,
     RemoveFromGlobalClusterMessageRequestTypeDef,
     RemoveSourceIdentifierFromSubscriptionMessageRequestTypeDef,
     RemoveTagsFromResourceMessageRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartDBClusterMessageRequestTypeDef,
     StopDBClusterMessageRequestTypeDef,
     AddSourceIdentifierToSubscriptionResultTypeDef,
     CreateEventSubscriptionResultTypeDef,
-    DBClusterParameterGroupNameMessageTypeDef,
     DeleteEventSubscriptionResultTypeDef,
-    EmptyResponseMetadataTypeDef,
     EventSubscriptionsMessageTypeDef,
     ModifyEventSubscriptionResultTypeDef,
     RemoveSourceIdentifierFromSubscriptionResultTypeDef,
     AddTagsToResourceMessageRequestTypeDef,
     CopyDBClusterParameterGroupMessageRequestTypeDef,
     CopyDBClusterSnapshotMessageRequestTypeDef,
     CreateDBClusterMessageRequestTypeDef,
@@ -490,43 +490,43 @@
     DBClusterParameterGroupDetailsTypeDef,
     EngineDefaultsTypeDef,
     ModifyDBClusterParameterGroupMessageRequestTypeDef,
     ResetDBClusterParameterGroupMessageRequestTypeDef,
     DBClusterSnapshotAttributesResultTypeDef,
     DBClusterTypeDef,
     DBEngineVersionTypeDef,
+    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
     DescribeCertificatesMessageRequestTypeDef,
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
+    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
     DescribeDBSubnetGroupsMessageRequestTypeDef,
     DescribeEngineDefaultClusterParametersMessageRequestTypeDef,
     DescribeEventCategoriesMessageRequestTypeDef,
+    DescribeEventSubscriptionsMessageDescribeEventSubscriptionsPaginateTypeDef,
     DescribeEventSubscriptionsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
+    DescribeGlobalClustersMessageDescribeGlobalClustersPaginateTypeDef,
     DescribeGlobalClustersMessageRequestTypeDef,
+    DescribeOrderableDBInstanceOptionsMessageDescribeOrderableDBInstanceOptionsPaginateTypeDef,
     DescribeOrderableDBInstanceOptionsMessageRequestTypeDef,
+    DescribePendingMaintenanceActionsMessageDescribePendingMaintenanceActionsPaginateTypeDef,
     DescribePendingMaintenanceActionsMessageRequestTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
-    DescribeCertificatesMessageDescribeCertificatesPaginateTypeDef,
-    DescribeDBClusterParameterGroupsMessageDescribeDBClusterParameterGroupsPaginateTypeDef,
-    DescribeDBClusterParametersMessageDescribeDBClusterParametersPaginateTypeDef,
-    DescribeDBClusterSnapshotsMessageDescribeDBClusterSnapshotsPaginateTypeDef,
-    DescribeDBClustersMessageDescribeDBClustersPaginateTypeDef,
-    DescribeDBEngineVersionsMessageDescribeDBEngineVersionsPaginateTypeDef,
-    DescribeDBInstancesMessageDescribeDBInstancesPaginateTypeDef,
-    DescribeDBSubnetGroupsMessageDescribeDBSubnetGroupsPaginateTypeDef,
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
     PendingModifiedValuesTypeDef,
     ResourcePendingMaintenanceActionsTypeDef,
@@ -571,43 +571,43 @@
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

### Comparing `types-aiobotocore-docdb-2.5.0.post1/types_aiobotocore_docdb.egg-info/SOURCES.txt` & `types-aiobotocore-docdb-2.5.1/types_aiobotocore_docdb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

