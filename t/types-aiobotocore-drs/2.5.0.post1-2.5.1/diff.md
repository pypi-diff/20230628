# Comparing `tmp/types-aiobotocore-drs-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-drs-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-drs-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:31 2023, max compression
+gzip compressed data, was "types-aiobotocore-drs-2.5.1.tar", last modified: Wed Jun 28 01:43:24 2023, max compression
```

## Comparing `types-aiobotocore-drs-2.5.0.post1.tar` & `types-aiobotocore-drs-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.939146 types-aiobotocore-drs-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20020 2023-03-11 12:26:31.935146 types-aiobotocore-drs-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18465 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:31.939146 types-aiobotocore-drs-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.935146 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/
--rw-r--r--   0 runner    (1001) docker     (123)     2451 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2450 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    32526 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    32474 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15680 2023-03-11 12:12:43.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    15678 2023-03-11 12:12:43.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11024 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11013 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    44596 2023-03-11 12:12:43.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    44557 2023-03-11 12:12:43.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:42.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:31.935146 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20020 2023-03-11 12:26:31.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:31.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:31.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:31.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:31.000000 types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.654127 types-aiobotocore-drs-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22218 2023-06-28 01:43:24.654127 types-aiobotocore-drs-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20669 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:24.654127 types-aiobotocore-drs-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.650127 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/
+-rw-r--r--   0 runner    (1001) docker     (123)     3017 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3016 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42020 2023-06-28 01:29:22.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41954 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17043 2023-06-28 01:29:22.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17041 2023-06-28 01:29:22.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13568 2023-06-28 01:29:22.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13556 2023-06-28 01:29:22.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    56978 2023-06-28 01:29:23.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    56931 2023-06-28 01:29:22.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:21.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.654127 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22218 2023-06-28 01:43:24.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:24.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:24.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:24.000000 types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/LICENSE` & `types-aiobotocore-drs-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-drs-2.5.0.post1/PKG-INFO` & `types-aiobotocore-drs-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-drs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.drs 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore drs type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-drs"></a>
 
 # types-aiobotocore-drs
 
 [![PyPI - types-aiobotocore-drs](https://img.shields.io/pypi/v/types-aiobotocore-drs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-drs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-drs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-drs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-drs?color=blue)](https://pypistats.org/packages/types-aiobotocore-drs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.drs 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs)
+[aiobotocore.drs 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs)
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
 [types-aiobotocore-drs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,17 +240,19 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_drs import drsClient
 from types_aiobotocore_drs.paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
+    DescribeLaunchConfigurationTemplatesPaginator,
     DescribeRecoveryInstancesPaginator,
     DescribeRecoverySnapshotsPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
+    DescribeSourceNetworksPaginator,
     DescribeSourceServersPaginator,
     ListExtensibleSourceServersPaginator,
     ListStagingAccountsPaginator,
 )
 
 session = get_session()
 async with session.create_client("drs") as client:
@@ -291,23 +260,29 @@
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator(
         "describe_job_log_items"
     )
     describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
+    describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator(
+        "describe_launch_configuration_templates"
+    )
     describe_recovery_instances_paginator: DescribeRecoveryInstancesPaginator = (
         client.get_paginator("describe_recovery_instances")
     )
     describe_recovery_snapshots_paginator: DescribeRecoverySnapshotsPaginator = (
         client.get_paginator("describe_recovery_snapshots")
     )
     describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator(
         "describe_replication_configuration_templates"
     )
+    describe_source_networks_paginator: DescribeSourceNetworksPaginator = client.get_paginator(
+        "describe_source_networks"
+    )
     describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator(
         "describe_source_servers"
     )
     list_extensible_source_servers_paginator: ListExtensibleSourceServersPaginator = (
         client.get_paginator("list_extensible_source_servers")
     )
     list_staging_accounts_paginator: ListStagingAccountsPaginator = client.get_paginator(
@@ -326,17 +301,19 @@
 from types_aiobotocore_drs.literals import (
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
     DescribeJobLogItemsPaginatorName,
     DescribeJobsPaginatorName,
+    DescribeLaunchConfigurationTemplatesPaginatorName,
     DescribeRecoveryInstancesPaginatorName,
     DescribeRecoverySnapshotsPaginatorName,
     DescribeReplicationConfigurationTemplatesPaginatorName,
+    DescribeSourceNetworksPaginatorName,
     DescribeSourceServersPaginatorName,
     EC2InstanceStateType,
     ExtensionStatusType,
     FailbackLaunchTypeType,
     FailbackReplicationErrorType,
     FailbackStateType,
     InitiatedByType,
@@ -350,20 +327,22 @@
     ListExtensibleSourceServersPaginatorName,
     ListStagingAccountsPaginatorName,
     OriginEnvironmentType,
     PITPolicyRuleUnitsType,
     RecoveryInstanceDataReplicationInitiationStepNameType,
     RecoveryInstanceDataReplicationInitiationStepStatusType,
     RecoveryInstanceDataReplicationStateType,
+    RecoveryResultType,
     RecoverySnapshotsOrderType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
     ReplicationDirectionType,
+    ReplicationStatusType,
     TargetInstanceTypeRightSizingMethodType,
     drsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -379,117 +358,150 @@
 
 `types_aiobotocore_drs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_drs.type_defs import (
     AccountTypeDef,
+    AssociateSourceNetworkStackRequestRequestTypeDef,
     CPUTypeDef,
     ConversionPropertiesTypeDef,
     CreateExtendedSourceServerRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    LicensingTypeDef,
     PITPolicyRuleTypeDef,
+    CreateSourceNetworkRequestRequestTypeDef,
+    CreateSourceNetworkResponseTypeDef,
     DataReplicationErrorTypeDef,
     DataReplicationInfoReplicatedDiskTypeDef,
     DataReplicationInitiationStepTypeDef,
     DeleteJobRequestRequestTypeDef,
+    DeleteLaunchConfigurationTemplateRequestRequestTypeDef,
     DeleteRecoveryInstanceRequestRequestTypeDef,
     DeleteReplicationConfigurationTemplateRequestRequestTypeDef,
+    DeleteSourceNetworkRequestRequestTypeDef,
     DeleteSourceServerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
     DescribeJobLogItemsRequestRequestTypeDef,
     DescribeJobsRequestFiltersTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestRequestTypeDef,
     DescribeRecoveryInstancesRequestFiltersTypeDef,
     DescribeRecoverySnapshotsRequestFiltersTypeDef,
     RecoverySnapshotTypeDef,
+    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
     DescribeReplicationConfigurationTemplatesRequestRequestTypeDef,
+    DescribeSourceNetworksRequestFiltersTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DisconnectRecoveryInstanceRequestRequestTypeDef,
     DisconnectSourceServerRequestRequestTypeDef,
     DiskTypeDef,
+    EmptyResponseMetadataTypeDef,
+    SourceNetworkDataTypeDef,
+    ExportSourceNetworkCfnTemplateRequestRequestTypeDef,
+    ExportSourceNetworkCfnTemplateResponseTypeDef,
     GetFailbackReplicationConfigurationRequestRequestTypeDef,
+    GetFailbackReplicationConfigurationResponseTypeDef,
     GetLaunchConfigurationRequestRequestTypeDef,
     GetReplicationConfigurationRequestRequestTypeDef,
     IdentificationHintsTypeDef,
     ParticipatingServerTypeDef,
-    LicensingTypeDef,
     LifeCycleLastLaunchInitiatedTypeDef,
+    ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
     ListExtensibleSourceServersRequestRequestTypeDef,
     StagingSourceServerTypeDef,
+    ListStagingAccountsRequestListStagingAccountsPaginateTypeDef,
     ListStagingAccountsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NetworkInterfaceTypeDef,
     OSTypeDef,
+    PaginatorConfigTypeDef,
+    ParticipatingResourceIDTypeDef,
     RecoveryInstanceDataReplicationErrorTypeDef,
     RecoveryInstanceDataReplicationInfoReplicatedDiskTypeDef,
     RecoveryInstanceDataReplicationInitiationStepTypeDef,
     RecoveryInstanceDiskTypeDef,
     RecoveryInstanceFailbackTypeDef,
+    RecoveryLifeCycleTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
+    ResponseMetadataTypeDef,
     RetryDataReplicationRequestRequestTypeDef,
     ReverseReplicationRequestRequestTypeDef,
+    ReverseReplicationResponseTypeDef,
     SourceCloudPropertiesTypeDef,
     StagingAreaTypeDef,
     StartFailbackLaunchRequestRequestTypeDef,
     StartRecoveryRequestSourceServerTypeDef,
     StartReplicationRequestRequestTypeDef,
+    StartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+    StartSourceNetworkReplicationRequestRequestTypeDef,
     StopFailbackRequestRequestTypeDef,
     StopReplicationRequestRequestTypeDef,
+    StopSourceNetworkReplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateRecoveryInstancesRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFailbackReplicationConfigurationRequestRequestTypeDef,
-    JobLogEventDataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetFailbackReplicationConfigurationResponseTypeDef,
     ListStagingAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ReverseReplicationResponseTypeDef,
+    CreateLaunchConfigurationTemplateRequestRequestTypeDef,
+    LaunchConfigurationTemplateTypeDef,
+    LaunchConfigurationTypeDef,
+    UpdateLaunchConfigurationRequestRequestTypeDef,
+    UpdateLaunchConfigurationTemplateRequestRequestTypeDef,
     CreateReplicationConfigurationTemplateRequestRequestTypeDef,
     ReplicationConfigurationTemplateResponseMetadataTypeDef,
     ReplicationConfigurationTemplateTypeDef,
     UpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     DataReplicationInitiationTypeDef,
-    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
-    ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
-    ListStagingAccountsRequestListStagingAccountsPaginateTypeDef,
     DescribeJobsRequestDescribeJobsPaginateTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef,
     DescribeRecoveryInstancesRequestRequestTypeDef,
     DescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef,
     DescribeRecoverySnapshotsRequestRequestTypeDef,
     DescribeRecoverySnapshotsResponseTypeDef,
+    DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef,
+    DescribeSourceNetworksRequestRequestTypeDef,
     DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef,
     DescribeSourceServersRequestRequestTypeDef,
-    JobTypeDef,
-    LaunchConfigurationTypeDef,
-    UpdateLaunchConfigurationRequestRequestTypeDef,
+    EventResourceDataTypeDef,
     LifeCycleLastLaunchTypeDef,
     ListExtensibleSourceServersResponseTypeDef,
     SourcePropertiesTypeDef,
+    ParticipatingResourceTypeDef,
     RecoveryInstanceDataReplicationInitiationTypeDef,
     RecoveryInstancePropertiesTypeDef,
+    SourceNetworkTypeDef,
     ReplicationConfigurationTypeDef,
     UpdateReplicationConfigurationRequestRequestTypeDef,
     StartRecoveryRequestRequestTypeDef,
-    JobLogTypeDef,
+    StartSourceNetworkRecoveryRequestRequestTypeDef,
+    CreateLaunchConfigurationTemplateResponseTypeDef,
+    DescribeLaunchConfigurationTemplatesResponseTypeDef,
+    UpdateLaunchConfigurationTemplateResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DataReplicationInfoTypeDef,
-    DescribeJobsResponseTypeDef,
-    StartFailbackLaunchResponseTypeDef,
-    StartRecoveryResponseTypeDef,
-    TerminateRecoveryInstancesResponseTypeDef,
+    JobLogEventDataTypeDef,
     LifeCycleTypeDef,
+    JobTypeDef,
     RecoveryInstanceDataReplicationInfoTypeDef,
-    DescribeJobLogItemsResponseTypeDef,
+    DescribeSourceNetworksResponseTypeDef,
+    StartSourceNetworkReplicationResponseTypeDef,
+    StopSourceNetworkReplicationResponseTypeDef,
+    JobLogTypeDef,
     SourceServerResponseMetadataTypeDef,
     SourceServerTypeDef,
+    AssociateSourceNetworkStackResponseTypeDef,
+    DescribeJobsResponseTypeDef,
+    StartFailbackLaunchResponseTypeDef,
+    StartRecoveryResponseTypeDef,
+    StartSourceNetworkRecoveryResponseTypeDef,
+    TerminateRecoveryInstancesResponseTypeDef,
     RecoveryInstanceTypeDef,
+    DescribeJobLogItemsResponseTypeDef,
     CreateExtendedSourceServerResponseTypeDef,
     DescribeSourceServersResponseTypeDef,
     StartReplicationResponseTypeDef,
     StopReplicationResponseTypeDef,
     DescribeRecoveryInstancesResponseTypeDef,
 )
 
@@ -501,43 +513,43 @@
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

### Comparing `types-aiobotocore-drs-2.5.0.post1/README.md` & `types-aiobotocore-drs-2.5.1/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-drs
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.drs 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore drs type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-drs"></a>
 
 # types-aiobotocore-drs
 
 [![PyPI - types-aiobotocore-drs](https://img.shields.io/pypi/v/types-aiobotocore-drs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-drs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-drs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-drs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-drs?color=blue)](https://pypistats.org/packages/types-aiobotocore-drs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.drs 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs)
+[aiobotocore.drs 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs)
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
 [types-aiobotocore-drs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -240,17 +273,19 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_drs import drsClient
 from types_aiobotocore_drs.paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
+    DescribeLaunchConfigurationTemplatesPaginator,
     DescribeRecoveryInstancesPaginator,
     DescribeRecoverySnapshotsPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
+    DescribeSourceNetworksPaginator,
     DescribeSourceServersPaginator,
     ListExtensibleSourceServersPaginator,
     ListStagingAccountsPaginator,
 )
 
 session = get_session()
 async with session.create_client("drs") as client:
@@ -258,23 +293,29 @@
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator(
         "describe_job_log_items"
     )
     describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
+    describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator(
+        "describe_launch_configuration_templates"
+    )
     describe_recovery_instances_paginator: DescribeRecoveryInstancesPaginator = (
         client.get_paginator("describe_recovery_instances")
     )
     describe_recovery_snapshots_paginator: DescribeRecoverySnapshotsPaginator = (
         client.get_paginator("describe_recovery_snapshots")
     )
     describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator(
         "describe_replication_configuration_templates"
     )
+    describe_source_networks_paginator: DescribeSourceNetworksPaginator = client.get_paginator(
+        "describe_source_networks"
+    )
     describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator(
         "describe_source_servers"
     )
     list_extensible_source_servers_paginator: ListExtensibleSourceServersPaginator = (
         client.get_paginator("list_extensible_source_servers")
     )
     list_staging_accounts_paginator: ListStagingAccountsPaginator = client.get_paginator(
@@ -293,17 +334,19 @@
 from types_aiobotocore_drs.literals import (
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
     DescribeJobLogItemsPaginatorName,
     DescribeJobsPaginatorName,
+    DescribeLaunchConfigurationTemplatesPaginatorName,
     DescribeRecoveryInstancesPaginatorName,
     DescribeRecoverySnapshotsPaginatorName,
     DescribeReplicationConfigurationTemplatesPaginatorName,
+    DescribeSourceNetworksPaginatorName,
     DescribeSourceServersPaginatorName,
     EC2InstanceStateType,
     ExtensionStatusType,
     FailbackLaunchTypeType,
     FailbackReplicationErrorType,
     FailbackStateType,
     InitiatedByType,
@@ -317,20 +360,22 @@
     ListExtensibleSourceServersPaginatorName,
     ListStagingAccountsPaginatorName,
     OriginEnvironmentType,
     PITPolicyRuleUnitsType,
     RecoveryInstanceDataReplicationInitiationStepNameType,
     RecoveryInstanceDataReplicationInitiationStepStatusType,
     RecoveryInstanceDataReplicationStateType,
+    RecoveryResultType,
     RecoverySnapshotsOrderType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
     ReplicationDirectionType,
+    ReplicationStatusType,
     TargetInstanceTypeRightSizingMethodType,
     drsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -346,117 +391,150 @@
 
 `types_aiobotocore_drs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_drs.type_defs import (
     AccountTypeDef,
+    AssociateSourceNetworkStackRequestRequestTypeDef,
     CPUTypeDef,
     ConversionPropertiesTypeDef,
     CreateExtendedSourceServerRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    LicensingTypeDef,
     PITPolicyRuleTypeDef,
+    CreateSourceNetworkRequestRequestTypeDef,
+    CreateSourceNetworkResponseTypeDef,
     DataReplicationErrorTypeDef,
     DataReplicationInfoReplicatedDiskTypeDef,
     DataReplicationInitiationStepTypeDef,
     DeleteJobRequestRequestTypeDef,
+    DeleteLaunchConfigurationTemplateRequestRequestTypeDef,
     DeleteRecoveryInstanceRequestRequestTypeDef,
     DeleteReplicationConfigurationTemplateRequestRequestTypeDef,
+    DeleteSourceNetworkRequestRequestTypeDef,
     DeleteSourceServerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
     DescribeJobLogItemsRequestRequestTypeDef,
     DescribeJobsRequestFiltersTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestRequestTypeDef,
     DescribeRecoveryInstancesRequestFiltersTypeDef,
     DescribeRecoverySnapshotsRequestFiltersTypeDef,
     RecoverySnapshotTypeDef,
+    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
     DescribeReplicationConfigurationTemplatesRequestRequestTypeDef,
+    DescribeSourceNetworksRequestFiltersTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DisconnectRecoveryInstanceRequestRequestTypeDef,
     DisconnectSourceServerRequestRequestTypeDef,
     DiskTypeDef,
+    EmptyResponseMetadataTypeDef,
+    SourceNetworkDataTypeDef,
+    ExportSourceNetworkCfnTemplateRequestRequestTypeDef,
+    ExportSourceNetworkCfnTemplateResponseTypeDef,
     GetFailbackReplicationConfigurationRequestRequestTypeDef,
+    GetFailbackReplicationConfigurationResponseTypeDef,
     GetLaunchConfigurationRequestRequestTypeDef,
     GetReplicationConfigurationRequestRequestTypeDef,
     IdentificationHintsTypeDef,
     ParticipatingServerTypeDef,
-    LicensingTypeDef,
     LifeCycleLastLaunchInitiatedTypeDef,
+    ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
     ListExtensibleSourceServersRequestRequestTypeDef,
     StagingSourceServerTypeDef,
+    ListStagingAccountsRequestListStagingAccountsPaginateTypeDef,
     ListStagingAccountsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NetworkInterfaceTypeDef,
     OSTypeDef,
+    PaginatorConfigTypeDef,
+    ParticipatingResourceIDTypeDef,
     RecoveryInstanceDataReplicationErrorTypeDef,
     RecoveryInstanceDataReplicationInfoReplicatedDiskTypeDef,
     RecoveryInstanceDataReplicationInitiationStepTypeDef,
     RecoveryInstanceDiskTypeDef,
     RecoveryInstanceFailbackTypeDef,
+    RecoveryLifeCycleTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
+    ResponseMetadataTypeDef,
     RetryDataReplicationRequestRequestTypeDef,
     ReverseReplicationRequestRequestTypeDef,
+    ReverseReplicationResponseTypeDef,
     SourceCloudPropertiesTypeDef,
     StagingAreaTypeDef,
     StartFailbackLaunchRequestRequestTypeDef,
     StartRecoveryRequestSourceServerTypeDef,
     StartReplicationRequestRequestTypeDef,
+    StartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+    StartSourceNetworkReplicationRequestRequestTypeDef,
     StopFailbackRequestRequestTypeDef,
     StopReplicationRequestRequestTypeDef,
+    StopSourceNetworkReplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateRecoveryInstancesRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFailbackReplicationConfigurationRequestRequestTypeDef,
-    JobLogEventDataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetFailbackReplicationConfigurationResponseTypeDef,
     ListStagingAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ReverseReplicationResponseTypeDef,
+    CreateLaunchConfigurationTemplateRequestRequestTypeDef,
+    LaunchConfigurationTemplateTypeDef,
+    LaunchConfigurationTypeDef,
+    UpdateLaunchConfigurationRequestRequestTypeDef,
+    UpdateLaunchConfigurationTemplateRequestRequestTypeDef,
     CreateReplicationConfigurationTemplateRequestRequestTypeDef,
     ReplicationConfigurationTemplateResponseMetadataTypeDef,
     ReplicationConfigurationTemplateTypeDef,
     UpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     DataReplicationInitiationTypeDef,
-    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
-    ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
-    ListStagingAccountsRequestListStagingAccountsPaginateTypeDef,
     DescribeJobsRequestDescribeJobsPaginateTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef,
     DescribeRecoveryInstancesRequestRequestTypeDef,
     DescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef,
     DescribeRecoverySnapshotsRequestRequestTypeDef,
     DescribeRecoverySnapshotsResponseTypeDef,
+    DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef,
+    DescribeSourceNetworksRequestRequestTypeDef,
     DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef,
     DescribeSourceServersRequestRequestTypeDef,
-    JobTypeDef,
-    LaunchConfigurationTypeDef,
-    UpdateLaunchConfigurationRequestRequestTypeDef,
+    EventResourceDataTypeDef,
     LifeCycleLastLaunchTypeDef,
     ListExtensibleSourceServersResponseTypeDef,
     SourcePropertiesTypeDef,
+    ParticipatingResourceTypeDef,
     RecoveryInstanceDataReplicationInitiationTypeDef,
     RecoveryInstancePropertiesTypeDef,
+    SourceNetworkTypeDef,
     ReplicationConfigurationTypeDef,
     UpdateReplicationConfigurationRequestRequestTypeDef,
     StartRecoveryRequestRequestTypeDef,
-    JobLogTypeDef,
+    StartSourceNetworkRecoveryRequestRequestTypeDef,
+    CreateLaunchConfigurationTemplateResponseTypeDef,
+    DescribeLaunchConfigurationTemplatesResponseTypeDef,
+    UpdateLaunchConfigurationTemplateResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DataReplicationInfoTypeDef,
-    DescribeJobsResponseTypeDef,
-    StartFailbackLaunchResponseTypeDef,
-    StartRecoveryResponseTypeDef,
-    TerminateRecoveryInstancesResponseTypeDef,
+    JobLogEventDataTypeDef,
     LifeCycleTypeDef,
+    JobTypeDef,
     RecoveryInstanceDataReplicationInfoTypeDef,
-    DescribeJobLogItemsResponseTypeDef,
+    DescribeSourceNetworksResponseTypeDef,
+    StartSourceNetworkReplicationResponseTypeDef,
+    StopSourceNetworkReplicationResponseTypeDef,
+    JobLogTypeDef,
     SourceServerResponseMetadataTypeDef,
     SourceServerTypeDef,
+    AssociateSourceNetworkStackResponseTypeDef,
+    DescribeJobsResponseTypeDef,
+    StartFailbackLaunchResponseTypeDef,
+    StartRecoveryResponseTypeDef,
+    StartSourceNetworkRecoveryResponseTypeDef,
+    TerminateRecoveryInstancesResponseTypeDef,
     RecoveryInstanceTypeDef,
+    DescribeJobLogItemsResponseTypeDef,
     CreateExtendedSourceServerResponseTypeDef,
     DescribeSourceServersResponseTypeDef,
     StartReplicationResponseTypeDef,
     StopReplicationResponseTypeDef,
     DescribeRecoveryInstancesResponseTypeDef,
 )
 
@@ -468,43 +546,43 @@
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

### Comparing `types-aiobotocore-drs-2.5.0.post1/setup.py` & `types-aiobotocore-drs-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-drs.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-drs",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_drs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.drs 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.drs 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/",
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

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/__init__.py` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/__init__.py`

 * *Files 11% similar despite different names*

```diff
@@ -5,59 +5,67 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_drs import (
         Client,
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
+        DescribeLaunchConfigurationTemplatesPaginator,
         DescribeRecoveryInstancesPaginator,
         DescribeRecoverySnapshotsPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
+        DescribeSourceNetworksPaginator,
         DescribeSourceServersPaginator,
         ListExtensibleSourceServersPaginator,
         ListStagingAccountsPaginator,
         drsClient,
     )
 
     session = get_session()
     async with session.create_client("drs") as client:
         client: drsClient
         ...
 
 
     describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
     describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
+    describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
     describe_recovery_instances_paginator: DescribeRecoveryInstancesPaginator = client.get_paginator("describe_recovery_instances")
     describe_recovery_snapshots_paginator: DescribeRecoverySnapshotsPaginator = client.get_paginator("describe_recovery_snapshots")
     describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
+    describe_source_networks_paginator: DescribeSourceNetworksPaginator = client.get_paginator("describe_source_networks")
     describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
     list_extensible_source_servers_paginator: ListExtensibleSourceServersPaginator = client.get_paginator("list_extensible_source_servers")
     list_staging_accounts_paginator: ListStagingAccountsPaginator = client.get_paginator("list_staging_accounts")
     ```
 """
 from .client import drsClient
 from .paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
+    DescribeLaunchConfigurationTemplatesPaginator,
     DescribeRecoveryInstancesPaginator,
     DescribeRecoverySnapshotsPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
+    DescribeSourceNetworksPaginator,
     DescribeSourceServersPaginator,
     ListExtensibleSourceServersPaginator,
     ListStagingAccountsPaginator,
 )
 
 Client = drsClient
 
 
 __all__ = (
     "Client",
     "DescribeJobLogItemsPaginator",
     "DescribeJobsPaginator",
+    "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeRecoveryInstancesPaginator",
     "DescribeRecoverySnapshotsPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
+    "DescribeSourceNetworksPaginator",
     "DescribeSourceServersPaginator",
     "ListExtensibleSourceServersPaginator",
     "ListStagingAccountsPaginator",
     "drsClient",
 )
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/__init__.pyi` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/__init__.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -5,58 +5,66 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_drs import (
         Client,
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
+        DescribeLaunchConfigurationTemplatesPaginator,
         DescribeRecoveryInstancesPaginator,
         DescribeRecoverySnapshotsPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
+        DescribeSourceNetworksPaginator,
         DescribeSourceServersPaginator,
         ListExtensibleSourceServersPaginator,
         ListStagingAccountsPaginator,
         drsClient,
     )
 
     session = get_session()
     async with session.create_client("drs") as client:
         client: drsClient
         ...
 
 
     describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
     describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
+    describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
     describe_recovery_instances_paginator: DescribeRecoveryInstancesPaginator = client.get_paginator("describe_recovery_instances")
     describe_recovery_snapshots_paginator: DescribeRecoverySnapshotsPaginator = client.get_paginator("describe_recovery_snapshots")
     describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
+    describe_source_networks_paginator: DescribeSourceNetworksPaginator = client.get_paginator("describe_source_networks")
     describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
     list_extensible_source_servers_paginator: ListExtensibleSourceServersPaginator = client.get_paginator("list_extensible_source_servers")
     list_staging_accounts_paginator: ListStagingAccountsPaginator = client.get_paginator("list_staging_accounts")
     ```
 """
 from .client import drsClient
 from .paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
+    DescribeLaunchConfigurationTemplatesPaginator,
     DescribeRecoveryInstancesPaginator,
     DescribeRecoverySnapshotsPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
+    DescribeSourceNetworksPaginator,
     DescribeSourceServersPaginator,
     ListExtensibleSourceServersPaginator,
     ListStagingAccountsPaginator,
 )
 
 Client = drsClient
 
 __all__ = (
     "Client",
     "DescribeJobLogItemsPaginator",
     "DescribeJobsPaginator",
+    "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeRecoveryInstancesPaginator",
     "DescribeRecoverySnapshotsPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
+    "DescribeSourceNetworksPaginator",
     "DescribeSourceServersPaginator",
     "ListExtensibleSourceServersPaginator",
     "ListStagingAccountsPaginator",
     "drsClient",
 )
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/__main__.py` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.drs 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.drs 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs\nOther"
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

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/client.py` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/client.py`

 * *Files 16% similar despite different names*

```diff
@@ -27,34 +27,43 @@
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     TargetInstanceTypeRightSizingMethodType,
 )
 from .paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
+    DescribeLaunchConfigurationTemplatesPaginator,
     DescribeRecoveryInstancesPaginator,
     DescribeRecoverySnapshotsPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
+    DescribeSourceNetworksPaginator,
     DescribeSourceServersPaginator,
     ListExtensibleSourceServersPaginator,
     ListStagingAccountsPaginator,
 )
 from .type_defs import (
+    AssociateSourceNetworkStackResponseTypeDef,
     CreateExtendedSourceServerResponseTypeDef,
+    CreateLaunchConfigurationTemplateResponseTypeDef,
+    CreateSourceNetworkResponseTypeDef,
     DescribeJobLogItemsResponseTypeDef,
     DescribeJobsRequestFiltersTypeDef,
     DescribeJobsResponseTypeDef,
+    DescribeLaunchConfigurationTemplatesResponseTypeDef,
     DescribeRecoveryInstancesRequestFiltersTypeDef,
     DescribeRecoveryInstancesResponseTypeDef,
     DescribeRecoverySnapshotsRequestFiltersTypeDef,
     DescribeRecoverySnapshotsResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
+    DescribeSourceNetworksRequestFiltersTypeDef,
+    DescribeSourceNetworksResponseTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DescribeSourceServersResponseTypeDef,
     EmptyResponseMetadataTypeDef,
+    ExportSourceNetworkCfnTemplateResponseTypeDef,
     GetFailbackReplicationConfigurationResponseTypeDef,
     LaunchConfigurationTypeDef,
     LicensingTypeDef,
     ListExtensibleSourceServersResponseTypeDef,
     ListStagingAccountsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PITPolicyRuleTypeDef,
@@ -63,16 +72,21 @@
     ReplicationConfigurationTypeDef,
     ReverseReplicationResponseTypeDef,
     SourceServerResponseMetadataTypeDef,
     StartFailbackLaunchResponseTypeDef,
     StartRecoveryRequestSourceServerTypeDef,
     StartRecoveryResponseTypeDef,
     StartReplicationResponseTypeDef,
+    StartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+    StartSourceNetworkRecoveryResponseTypeDef,
+    StartSourceNetworkReplicationResponseTypeDef,
     StopReplicationResponseTypeDef,
+    StopSourceNetworkReplicationResponseTypeDef,
     TerminateRecoveryInstancesResponseTypeDef,
+    UpdateLaunchConfigurationTemplateResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -113,14 +127,25 @@
         """
         drsClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#exceptions)
         """
 
+    async def associate_source_network_stack(
+        self, *, cfnStackName: str, sourceNetworkID: str
+    ) -> AssociateSourceNetworkStackResponseTypeDef:
+        """
+        Associate a Source Network to an existing CloudFormation Stack and modify launch
+        templates to use this network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.associate_source_network_stack)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#associate_source_network_stack)
+        """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#can_paginate)
         """
@@ -140,14 +165,32 @@
         Create an extended source server in the target Account based on the source
         server in staging account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_extended_source_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_extended_source_server)
         """
 
+    async def create_launch_configuration_template(
+        self,
+        *,
+        copyPrivateIp: bool = ...,
+        copyTags: bool = ...,
+        exportBucketArn: str = ...,
+        launchDisposition: LaunchDispositionType = ...,
+        licensing: LicensingTypeDef = ...,
+        tags: Mapping[str, str] = ...,
+        targetInstanceTypeRightSizingMethod: TargetInstanceTypeRightSizingMethodType = ...
+    ) -> CreateLaunchConfigurationTemplateResponseTypeDef:
+        """
+        Creates a new Launch Configuration Template.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_launch_configuration_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_launch_configuration_template)
+        """
+
     async def create_replication_configuration_template(
         self,
         *,
         associateDefaultSecurityGroup: bool,
         bandwidthThrottling: int,
         createPublicIP: bool,
         dataPlaneRouting: ReplicationConfigurationDataPlaneRoutingType,
@@ -155,32 +198,53 @@
         ebsEncryption: ReplicationConfigurationEbsEncryptionType,
         pitPolicy: Sequence[PITPolicyRuleTypeDef],
         replicationServerInstanceType: str,
         replicationServersSecurityGroupsIDs: Sequence[str],
         stagingAreaSubnetId: str,
         stagingAreaTags: Mapping[str, str],
         useDedicatedReplicationServer: bool,
+        autoReplicateNewDisks: bool = ...,
         ebsEncryptionKeyArn: str = ...,
         tags: Mapping[str, str] = ...
     ) -> ReplicationConfigurationTemplateResponseMetadataTypeDef:
         """
         Creates a new ReplicationConfigurationTemplate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_replication_configuration_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_replication_configuration_template)
         """
 
+    async def create_source_network(
+        self, *, originAccountID: str, originRegion: str, vpcID: str, tags: Mapping[str, str] = ...
+    ) -> CreateSourceNetworkResponseTypeDef:
+        """
+        Create a new Source Network resource for a provided VPC ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_source_network)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_source_network)
+        """
+
     async def delete_job(self, *, jobID: str) -> Dict[str, Any]:
         """
         Deletes a single Job by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_job)
         """
 
+    async def delete_launch_configuration_template(
+        self, *, launchConfigurationTemplateID: str
+    ) -> Dict[str, Any]:
+        """
+        Deletes a single Launch Configuration Template by ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_launch_configuration_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_launch_configuration_template)
+        """
+
     async def delete_recovery_instance(
         self, *, recoveryInstanceID: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a single Recovery Instance by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_recovery_instance)
@@ -194,14 +258,22 @@
         Deletes a single Replication Configuration Template by ID See also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/drs-2020-02-26/DeleteReplicationConfigurationTemplate).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_replication_configuration_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_replication_configuration_template)
         """
 
+    async def delete_source_network(self, *, sourceNetworkID: str) -> Dict[str, Any]:
+        """
+        Delete Source Network resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_source_network)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_source_network)
+        """
+
     async def delete_source_server(self, *, sourceServerID: str) -> Dict[str, Any]:
         """
         Deletes a single Source Server by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_source_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_source_server)
         """
@@ -226,14 +298,30 @@
         """
         Returns a list of Jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_jobs)
         """
 
+    async def describe_launch_configuration_templates(
+        self,
+        *,
+        launchConfigurationTemplateIDs: Sequence[str] = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> DescribeLaunchConfigurationTemplatesResponseTypeDef:
+        """
+        Lists all Launch Configuration Templates, filtered by Launch Configuration
+        Template IDs See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/drs-2020-02-26/DescribeLaunchConfigurationTemplates).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_launch_configuration_templates)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_launch_configuration_templates)
+        """
+
     async def describe_recovery_instances(
         self,
         *,
         filters: DescribeRecoveryInstancesRequestFiltersTypeDef = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeRecoveryInstancesResponseTypeDef:
@@ -270,14 +358,28 @@
         """
         Lists all ReplicationConfigurationTemplates, filtered by Source Server IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_replication_configuration_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_replication_configuration_templates)
         """
 
+    async def describe_source_networks(
+        self,
+        *,
+        filters: DescribeSourceNetworksRequestFiltersTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> DescribeSourceNetworksResponseTypeDef:
+        """
+        Lists all Source Networks or multiple Source Networks filtered by ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_source_networks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_source_networks)
+        """
+
     async def describe_source_servers(
         self,
         *,
         filters: DescribeSourceServersRequestFiltersTypeDef = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeSourceServersResponseTypeDef:
@@ -304,14 +406,24 @@
         """
         Disconnects a specific Source Server from Elastic Disaster Recovery.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.disconnect_source_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#disconnect_source_server)
         """
 
+    async def export_source_network_cfn_template(
+        self, *, sourceNetworkID: str
+    ) -> ExportSourceNetworkCfnTemplateResponseTypeDef:
+        """
+        Export the Source Network CloudFormation template to an S3 bucket.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.export_source_network_cfn_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#export_source_network_cfn_template)
+        """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
@@ -389,17 +501,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#list_tags_for_resource)
         """
 
     async def retry_data_replication(
         self, *, sourceServerID: str
     ) -> SourceServerResponseMetadataTypeDef:
         """
-        Causes the data replication initiation sequence to begin immediately upon next
-        Handshake for the specified Source Server ID, regardless of when the previous
-        initiation started.
+        WARNING: RetryDataReplication is deprecated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.retry_data_replication)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#retry_data_replication)
         """
 
     async def reverse_replication(
         self, *, recoveryInstanceID: str
@@ -441,14 +551,39 @@
         """
         Starts replication for a stopped Source Server.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_replication)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#start_replication)
         """
 
+    async def start_source_network_recovery(
+        self,
+        *,
+        sourceNetworks: Sequence[StartSourceNetworkRecoveryRequestNetworkEntryTypeDef],
+        deployAsNew: bool = ...,
+        tags: Mapping[str, str] = ...
+    ) -> StartSourceNetworkRecoveryResponseTypeDef:
+        """
+        Deploy VPC for the specified Source Network and modify launch templates to use
+        this network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_source_network_recovery)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#start_source_network_recovery)
+        """
+
+    async def start_source_network_replication(
+        self, *, sourceNetworkID: str
+    ) -> StartSourceNetworkReplicationResponseTypeDef:
+        """
+        Starts replication for a Source Network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_source_network_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#start_source_network_replication)
+        """
+
     async def stop_failback(self, *, recoveryInstanceID: str) -> EmptyResponseMetadataTypeDef:
         """
         Stops the failback process for a specified Recovery Instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.stop_failback)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#stop_failback)
         """
@@ -457,14 +592,24 @@
         """
         Stops replication for a Source Server.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.stop_replication)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#stop_replication)
         """
 
+    async def stop_source_network_replication(
+        self, *, sourceNetworkID: str
+    ) -> StopSourceNetworkReplicationResponseTypeDef:
+        """
+        Stops replication for a Source Network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.stop_source_network_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#stop_source_network_replication)
+        """
+
     async def tag_resource(
         self, *, resourceArn: str, tags: Mapping[str, str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Adds or overwrites only the specified tags for the specified Elastic Disaster
         Recovery resource or resources.
 
@@ -525,19 +670,38 @@
         """
         Updates a LaunchConfiguration by Source Server ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_launch_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#update_launch_configuration)
         """
 
+    async def update_launch_configuration_template(
+        self,
+        *,
+        launchConfigurationTemplateID: str,
+        copyPrivateIp: bool = ...,
+        copyTags: bool = ...,
+        exportBucketArn: str = ...,
+        launchDisposition: LaunchDispositionType = ...,
+        licensing: LicensingTypeDef = ...,
+        targetInstanceTypeRightSizingMethod: TargetInstanceTypeRightSizingMethodType = ...
+    ) -> UpdateLaunchConfigurationTemplateResponseTypeDef:
+        """
+        Updates an existing Launch Configuration Template by ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_launch_configuration_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#update_launch_configuration_template)
+        """
+
     async def update_replication_configuration(
         self,
         *,
         sourceServerID: str,
         associateDefaultSecurityGroup: bool = ...,
+        autoReplicateNewDisks: bool = ...,
         bandwidthThrottling: int = ...,
         createPublicIP: bool = ...,
         dataPlaneRouting: ReplicationConfigurationDataPlaneRoutingType = ...,
         defaultLargeStagingDiskType: ReplicationConfigurationDefaultLargeStagingDiskTypeType = ...,
         ebsEncryption: ReplicationConfigurationEbsEncryptionType = ...,
         ebsEncryptionKeyArn: str = ...,
         name: str = ...,
@@ -558,14 +722,15 @@
 
     async def update_replication_configuration_template(
         self,
         *,
         replicationConfigurationTemplateID: str,
         arn: str = ...,
         associateDefaultSecurityGroup: bool = ...,
+        autoReplicateNewDisks: bool = ...,
         bandwidthThrottling: int = ...,
         createPublicIP: bool = ...,
         dataPlaneRouting: ReplicationConfigurationDataPlaneRoutingType = ...,
         defaultLargeStagingDiskType: ReplicationConfigurationDefaultLargeStagingDiskTypeType = ...,
         ebsEncryption: ReplicationConfigurationEbsEncryptionType = ...,
         ebsEncryptionKeyArn: str = ...,
         pitPolicy: Sequence[PITPolicyRuleTypeDef] = ...,
@@ -596,14 +761,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["describe_launch_configuration_templates"]
+    ) -> DescribeLaunchConfigurationTemplatesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["describe_recovery_instances"]
     ) -> DescribeRecoveryInstancesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
 
@@ -623,14 +797,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["describe_source_networks"]
+    ) -> DescribeSourceNetworksPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["describe_source_servers"]
     ) -> DescribeSourceServersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/client.pyi` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/client.pyi`

 * *Files 16% similar despite different names*

```diff
@@ -27,34 +27,43 @@
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     TargetInstanceTypeRightSizingMethodType,
 )
 from .paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
+    DescribeLaunchConfigurationTemplatesPaginator,
     DescribeRecoveryInstancesPaginator,
     DescribeRecoverySnapshotsPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
+    DescribeSourceNetworksPaginator,
     DescribeSourceServersPaginator,
     ListExtensibleSourceServersPaginator,
     ListStagingAccountsPaginator,
 )
 from .type_defs import (
+    AssociateSourceNetworkStackResponseTypeDef,
     CreateExtendedSourceServerResponseTypeDef,
+    CreateLaunchConfigurationTemplateResponseTypeDef,
+    CreateSourceNetworkResponseTypeDef,
     DescribeJobLogItemsResponseTypeDef,
     DescribeJobsRequestFiltersTypeDef,
     DescribeJobsResponseTypeDef,
+    DescribeLaunchConfigurationTemplatesResponseTypeDef,
     DescribeRecoveryInstancesRequestFiltersTypeDef,
     DescribeRecoveryInstancesResponseTypeDef,
     DescribeRecoverySnapshotsRequestFiltersTypeDef,
     DescribeRecoverySnapshotsResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
+    DescribeSourceNetworksRequestFiltersTypeDef,
+    DescribeSourceNetworksResponseTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DescribeSourceServersResponseTypeDef,
     EmptyResponseMetadataTypeDef,
+    ExportSourceNetworkCfnTemplateResponseTypeDef,
     GetFailbackReplicationConfigurationResponseTypeDef,
     LaunchConfigurationTypeDef,
     LicensingTypeDef,
     ListExtensibleSourceServersResponseTypeDef,
     ListStagingAccountsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PITPolicyRuleTypeDef,
@@ -63,16 +72,21 @@
     ReplicationConfigurationTypeDef,
     ReverseReplicationResponseTypeDef,
     SourceServerResponseMetadataTypeDef,
     StartFailbackLaunchResponseTypeDef,
     StartRecoveryRequestSourceServerTypeDef,
     StartRecoveryResponseTypeDef,
     StartReplicationResponseTypeDef,
+    StartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+    StartSourceNetworkRecoveryResponseTypeDef,
+    StartSourceNetworkReplicationResponseTypeDef,
     StopReplicationResponseTypeDef,
+    StopSourceNetworkReplicationResponseTypeDef,
     TerminateRecoveryInstancesResponseTypeDef,
+    UpdateLaunchConfigurationTemplateResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
@@ -108,14 +122,24 @@
     def exceptions(self) -> Exceptions:
         """
         drsClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#exceptions)
         """
+    async def associate_source_network_stack(
+        self, *, cfnStackName: str, sourceNetworkID: str
+    ) -> AssociateSourceNetworkStackResponseTypeDef:
+        """
+        Associate a Source Network to an existing CloudFormation Stack and modify launch
+        templates to use this network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.associate_source_network_stack)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#associate_source_network_stack)
+        """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#can_paginate)
         """
@@ -132,14 +156,31 @@
         """
         Create an extended source server in the target Account based on the source
         server in staging account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_extended_source_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_extended_source_server)
         """
+    async def create_launch_configuration_template(
+        self,
+        *,
+        copyPrivateIp: bool = ...,
+        copyTags: bool = ...,
+        exportBucketArn: str = ...,
+        launchDisposition: LaunchDispositionType = ...,
+        licensing: LicensingTypeDef = ...,
+        tags: Mapping[str, str] = ...,
+        targetInstanceTypeRightSizingMethod: TargetInstanceTypeRightSizingMethodType = ...
+    ) -> CreateLaunchConfigurationTemplateResponseTypeDef:
+        """
+        Creates a new Launch Configuration Template.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_launch_configuration_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_launch_configuration_template)
+        """
     async def create_replication_configuration_template(
         self,
         *,
         associateDefaultSecurityGroup: bool,
         bandwidthThrottling: int,
         createPublicIP: bool,
         dataPlaneRouting: ReplicationConfigurationDataPlaneRoutingType,
@@ -147,30 +188,49 @@
         ebsEncryption: ReplicationConfigurationEbsEncryptionType,
         pitPolicy: Sequence[PITPolicyRuleTypeDef],
         replicationServerInstanceType: str,
         replicationServersSecurityGroupsIDs: Sequence[str],
         stagingAreaSubnetId: str,
         stagingAreaTags: Mapping[str, str],
         useDedicatedReplicationServer: bool,
+        autoReplicateNewDisks: bool = ...,
         ebsEncryptionKeyArn: str = ...,
         tags: Mapping[str, str] = ...
     ) -> ReplicationConfigurationTemplateResponseMetadataTypeDef:
         """
         Creates a new ReplicationConfigurationTemplate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_replication_configuration_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_replication_configuration_template)
         """
+    async def create_source_network(
+        self, *, originAccountID: str, originRegion: str, vpcID: str, tags: Mapping[str, str] = ...
+    ) -> CreateSourceNetworkResponseTypeDef:
+        """
+        Create a new Source Network resource for a provided VPC ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.create_source_network)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#create_source_network)
+        """
     async def delete_job(self, *, jobID: str) -> Dict[str, Any]:
         """
         Deletes a single Job by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_job)
         """
+    async def delete_launch_configuration_template(
+        self, *, launchConfigurationTemplateID: str
+    ) -> Dict[str, Any]:
+        """
+        Deletes a single Launch Configuration Template by ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_launch_configuration_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_launch_configuration_template)
+        """
     async def delete_recovery_instance(
         self, *, recoveryInstanceID: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a single Recovery Instance by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_recovery_instance)
@@ -182,14 +242,21 @@
         """
         Deletes a single Replication Configuration Template by ID See also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/drs-2020-02-26/DeleteReplicationConfigurationTemplate).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_replication_configuration_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_replication_configuration_template)
         """
+    async def delete_source_network(self, *, sourceNetworkID: str) -> Dict[str, Any]:
+        """
+        Delete Source Network resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_source_network)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_source_network)
+        """
     async def delete_source_server(self, *, sourceServerID: str) -> Dict[str, Any]:
         """
         Deletes a single Source Server by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.delete_source_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#delete_source_server)
         """
@@ -211,14 +278,29 @@
     ) -> DescribeJobsResponseTypeDef:
         """
         Returns a list of Jobs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_jobs)
         """
+    async def describe_launch_configuration_templates(
+        self,
+        *,
+        launchConfigurationTemplateIDs: Sequence[str] = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> DescribeLaunchConfigurationTemplatesResponseTypeDef:
+        """
+        Lists all Launch Configuration Templates, filtered by Launch Configuration
+        Template IDs See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/drs-2020-02-26/DescribeLaunchConfigurationTemplates).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_launch_configuration_templates)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_launch_configuration_templates)
+        """
     async def describe_recovery_instances(
         self,
         *,
         filters: DescribeRecoveryInstancesRequestFiltersTypeDef = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeRecoveryInstancesResponseTypeDef:
@@ -252,14 +334,27 @@
     ) -> DescribeReplicationConfigurationTemplatesResponseTypeDef:
         """
         Lists all ReplicationConfigurationTemplates, filtered by Source Server IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_replication_configuration_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_replication_configuration_templates)
         """
+    async def describe_source_networks(
+        self,
+        *,
+        filters: DescribeSourceNetworksRequestFiltersTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> DescribeSourceNetworksResponseTypeDef:
+        """
+        Lists all Source Networks or multiple Source Networks filtered by ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.describe_source_networks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#describe_source_networks)
+        """
     async def describe_source_servers(
         self,
         *,
         filters: DescribeSourceServersRequestFiltersTypeDef = ...,
         maxResults: int = ...,
         nextToken: str = ...
     ) -> DescribeSourceServersResponseTypeDef:
@@ -283,14 +378,23 @@
     ) -> SourceServerResponseMetadataTypeDef:
         """
         Disconnects a specific Source Server from Elastic Disaster Recovery.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.disconnect_source_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#disconnect_source_server)
         """
+    async def export_source_network_cfn_template(
+        self, *, sourceNetworkID: str
+    ) -> ExportSourceNetworkCfnTemplateResponseTypeDef:
+        """
+        Export the Source Network CloudFormation template to an S3 bucket.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.export_source_network_cfn_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#export_source_network_cfn_template)
+        """
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
@@ -360,17 +464,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#list_tags_for_resource)
         """
     async def retry_data_replication(
         self, *, sourceServerID: str
     ) -> SourceServerResponseMetadataTypeDef:
         """
-        Causes the data replication initiation sequence to begin immediately upon next
-        Handshake for the specified Source Server ID, regardless of when the previous
-        initiation started.
+        WARNING: RetryDataReplication is deprecated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.retry_data_replication)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#retry_data_replication)
         """
     async def reverse_replication(
         self, *, recoveryInstanceID: str
     ) -> ReverseReplicationResponseTypeDef:
@@ -407,28 +509,60 @@
     async def start_replication(self, *, sourceServerID: str) -> StartReplicationResponseTypeDef:
         """
         Starts replication for a stopped Source Server.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_replication)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#start_replication)
         """
+    async def start_source_network_recovery(
+        self,
+        *,
+        sourceNetworks: Sequence[StartSourceNetworkRecoveryRequestNetworkEntryTypeDef],
+        deployAsNew: bool = ...,
+        tags: Mapping[str, str] = ...
+    ) -> StartSourceNetworkRecoveryResponseTypeDef:
+        """
+        Deploy VPC for the specified Source Network and modify launch templates to use
+        this network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_source_network_recovery)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#start_source_network_recovery)
+        """
+    async def start_source_network_replication(
+        self, *, sourceNetworkID: str
+    ) -> StartSourceNetworkReplicationResponseTypeDef:
+        """
+        Starts replication for a Source Network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.start_source_network_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#start_source_network_replication)
+        """
     async def stop_failback(self, *, recoveryInstanceID: str) -> EmptyResponseMetadataTypeDef:
         """
         Stops the failback process for a specified Recovery Instance.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.stop_failback)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#stop_failback)
         """
     async def stop_replication(self, *, sourceServerID: str) -> StopReplicationResponseTypeDef:
         """
         Stops replication for a Source Server.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.stop_replication)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#stop_replication)
         """
+    async def stop_source_network_replication(
+        self, *, sourceNetworkID: str
+    ) -> StopSourceNetworkReplicationResponseTypeDef:
+        """
+        Stops replication for a Source Network.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.stop_source_network_replication)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#stop_source_network_replication)
+        """
     async def tag_resource(
         self, *, resourceArn: str, tags: Mapping[str, str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Adds or overwrites only the specified tags for the specified Elastic Disaster
         Recovery resource or resources.
 
@@ -484,19 +618,37 @@
     ) -> LaunchConfigurationTypeDef:
         """
         Updates a LaunchConfiguration by Source Server ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_launch_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#update_launch_configuration)
         """
+    async def update_launch_configuration_template(
+        self,
+        *,
+        launchConfigurationTemplateID: str,
+        copyPrivateIp: bool = ...,
+        copyTags: bool = ...,
+        exportBucketArn: str = ...,
+        launchDisposition: LaunchDispositionType = ...,
+        licensing: LicensingTypeDef = ...,
+        targetInstanceTypeRightSizingMethod: TargetInstanceTypeRightSizingMethodType = ...
+    ) -> UpdateLaunchConfigurationTemplateResponseTypeDef:
+        """
+        Updates an existing Launch Configuration Template by ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.update_launch_configuration_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#update_launch_configuration_template)
+        """
     async def update_replication_configuration(
         self,
         *,
         sourceServerID: str,
         associateDefaultSecurityGroup: bool = ...,
+        autoReplicateNewDisks: bool = ...,
         bandwidthThrottling: int = ...,
         createPublicIP: bool = ...,
         dataPlaneRouting: ReplicationConfigurationDataPlaneRoutingType = ...,
         defaultLargeStagingDiskType: ReplicationConfigurationDefaultLargeStagingDiskTypeType = ...,
         ebsEncryption: ReplicationConfigurationEbsEncryptionType = ...,
         ebsEncryptionKeyArn: str = ...,
         name: str = ...,
@@ -516,14 +668,15 @@
         """
     async def update_replication_configuration_template(
         self,
         *,
         replicationConfigurationTemplateID: str,
         arn: str = ...,
         associateDefaultSecurityGroup: bool = ...,
+        autoReplicateNewDisks: bool = ...,
         bandwidthThrottling: int = ...,
         createPublicIP: bool = ...,
         dataPlaneRouting: ReplicationConfigurationDataPlaneRoutingType = ...,
         defaultLargeStagingDiskType: ReplicationConfigurationDefaultLargeStagingDiskTypeType = ...,
         ebsEncryption: ReplicationConfigurationEbsEncryptionType = ...,
         ebsEncryptionKeyArn: str = ...,
         pitPolicy: Sequence[PITPolicyRuleTypeDef] = ...,
@@ -551,14 +704,22 @@
     def get_paginator(self, operation_name: Literal["describe_jobs"]) -> DescribeJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["describe_launch_configuration_templates"]
+    ) -> DescribeLaunchConfigurationTemplatesPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["describe_recovery_instances"]
     ) -> DescribeRecoveryInstancesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
     @overload
@@ -575,14 +736,22 @@
     ) -> DescribeReplicationConfigurationTemplatesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["describe_source_networks"]
+    ) -> DescribeSourceNetworksPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["describe_source_servers"]
     ) -> DescribeSourceServersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/client/#get_paginator)
         """
     @overload
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/literals.py` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,17 +22,19 @@
 __all__ = (
     "DataReplicationErrorStringType",
     "DataReplicationInitiationStepNameType",
     "DataReplicationInitiationStepStatusType",
     "DataReplicationStateType",
     "DescribeJobLogItemsPaginatorName",
     "DescribeJobsPaginatorName",
+    "DescribeLaunchConfigurationTemplatesPaginatorName",
     "DescribeRecoveryInstancesPaginatorName",
     "DescribeRecoverySnapshotsPaginatorName",
     "DescribeReplicationConfigurationTemplatesPaginatorName",
+    "DescribeSourceNetworksPaginatorName",
     "DescribeSourceServersPaginatorName",
     "EC2InstanceStateType",
     "ExtensionStatusType",
     "FailbackLaunchTypeType",
     "FailbackReplicationErrorType",
     "FailbackStateType",
     "InitiatedByType",
@@ -46,20 +48,22 @@
     "ListExtensibleSourceServersPaginatorName",
     "ListStagingAccountsPaginatorName",
     "OriginEnvironmentType",
     "PITPolicyRuleUnitsType",
     "RecoveryInstanceDataReplicationInitiationStepNameType",
     "RecoveryInstanceDataReplicationInitiationStepStatusType",
     "RecoveryInstanceDataReplicationStateType",
+    "RecoveryResultType",
     "RecoverySnapshotsOrderType",
     "ReplicationConfigurationDataPlaneRoutingType",
     "ReplicationConfigurationDefaultLargeStagingDiskTypeType",
     "ReplicationConfigurationEbsEncryptionType",
     "ReplicationConfigurationReplicatedDiskStagingDiskTypeType",
     "ReplicationDirectionType",
+    "ReplicationStatusType",
     "TargetInstanceTypeRightSizingMethodType",
     "drsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -107,19 +111,23 @@
     "PAUSED",
     "RESCAN",
     "STALLED",
     "STOPPED",
 ]
 DescribeJobLogItemsPaginatorName = Literal["describe_job_log_items"]
 DescribeJobsPaginatorName = Literal["describe_jobs"]
+DescribeLaunchConfigurationTemplatesPaginatorName = Literal[
+    "describe_launch_configuration_templates"
+]
 DescribeRecoveryInstancesPaginatorName = Literal["describe_recovery_instances"]
 DescribeRecoverySnapshotsPaginatorName = Literal["describe_recovery_snapshots"]
 DescribeReplicationConfigurationTemplatesPaginatorName = Literal[
     "describe_replication_configuration_templates"
 ]
+DescribeSourceNetworksPaginatorName = Literal["describe_source_networks"]
 DescribeSourceServersPaginatorName = Literal["describe_source_servers"]
 EC2InstanceStateType = Literal[
     "NOT_FOUND", "PENDING", "RUNNING", "SHUTTING-DOWN", "STOPPED", "STOPPING", "TERMINATED"
 ]
 ExtensionStatusType = Literal["EXTENDED", "EXTENSION_ERROR", "NOT_EXTENDED"]
 FailbackLaunchTypeType = Literal["DRILL", "RECOVERY"]
 FailbackReplicationErrorType = Literal[
@@ -151,37 +159,50 @@
     "FAILBACK_IN_PROGRESS",
     "FAILBACK_LAUNCH_STATE_NOT_AVAILABLE",
     "FAILBACK_NOT_READY_FOR_LAUNCH",
     "FAILBACK_NOT_STARTED",
     "FAILBACK_READY_FOR_LAUNCH",
 ]
 InitiatedByType = Literal[
+    "ASSOCIATE_NETWORK_RECOVERY",
+    "CREATE_NETWORK_RECOVERY",
     "DIAGNOSTIC",
     "FAILBACK",
     "START_DRILL",
     "START_RECOVERY",
     "TARGET_ACCOUNT",
     "TERMINATE_RECOVERY_INSTANCES",
+    "UPDATE_NETWORK_RECOVERY",
 ]
 JobLogEventType = Literal[
     "CLEANUP_END",
     "CLEANUP_FAIL",
     "CLEANUP_START",
     "CONVERSION_END",
     "CONVERSION_FAIL",
     "CONVERSION_START",
+    "DEPLOY_NETWORK_CONFIGURATION_END",
+    "DEPLOY_NETWORK_CONFIGURATION_FAILED",
+    "DEPLOY_NETWORK_CONFIGURATION_START",
     "JOB_CANCEL",
     "JOB_END",
     "JOB_START",
     "LAUNCH_FAILED",
     "LAUNCH_START",
+    "NETWORK_RECOVERY_FAIL",
     "SERVER_SKIPPED",
     "SNAPSHOT_END",
     "SNAPSHOT_FAIL",
     "SNAPSHOT_START",
+    "UPDATE_LAUNCH_TEMPLATE_END",
+    "UPDATE_LAUNCH_TEMPLATE_FAILED",
+    "UPDATE_LAUNCH_TEMPLATE_START",
+    "UPDATE_NETWORK_CONFIGURATION_END",
+    "UPDATE_NETWORK_CONFIGURATION_FAILED",
+    "UPDATE_NETWORK_CONFIGURATION_START",
     "USING_PREVIOUS_SNAPSHOT",
     "USING_PREVIOUS_SNAPSHOT_FAILED",
 ]
 JobStatusType = Literal["COMPLETED", "PENDING", "STARTED"]
 JobTypeType = Literal["CREATE_CONVERTED_SNAPSHOT", "LAUNCH", "TERMINATE"]
 LastLaunchResultType = Literal["FAILED", "NOT_STARTED", "PENDING", "SUCCEEDED"]
 LastLaunchTypeType = Literal["DRILL", "RECOVERY"]
@@ -224,22 +245,32 @@
     "NOT_STARTED",
     "PAUSED",
     "REPLICATION_STATE_NOT_AVAILABLE",
     "RESCAN",
     "STALLED",
     "STOPPED",
 ]
+RecoveryResultType = Literal[
+    "ASSOCIATE_FAIL",
+    "ASSOCIATE_SUCCESS",
+    "FAIL",
+    "IN_PROGRESS",
+    "NOT_STARTED",
+    "PARTIAL_SUCCESS",
+    "SUCCESS",
+]
 RecoverySnapshotsOrderType = Literal["ASC", "DESC"]
 ReplicationConfigurationDataPlaneRoutingType = Literal["PRIVATE_IP", "PUBLIC_IP"]
 ReplicationConfigurationDefaultLargeStagingDiskTypeType = Literal["AUTO", "GP2", "GP3", "ST1"]
-ReplicationConfigurationEbsEncryptionType = Literal["CUSTOM", "DEFAULT"]
+ReplicationConfigurationEbsEncryptionType = Literal["CUSTOM", "DEFAULT", "NONE"]
 ReplicationConfigurationReplicatedDiskStagingDiskTypeType = Literal[
     "AUTO", "GP2", "GP3", "IO1", "SC1", "ST1", "STANDARD"
 ]
 ReplicationDirectionType = Literal["FAILBACK", "FAILOVER"]
+ReplicationStatusType = Literal["ERROR", "IN_PROGRESS", "PROTECTED", "STOPPED"]
 TargetInstanceTypeRightSizingMethodType = Literal["BASIC", "NONE"]
 drsServiceName = Literal["drs"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -296,14 +327,15 @@
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
@@ -382,14 +414,15 @@
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
@@ -400,14 +433,15 @@
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
@@ -443,14 +477,15 @@
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
@@ -469,16 +504,19 @@
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
@@ -562,15 +600,17 @@
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
@@ -591,17 +631,19 @@
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "describe_job_log_items",
     "describe_jobs",
+    "describe_launch_configuration_templates",
     "describe_recovery_instances",
     "describe_recovery_snapshots",
     "describe_replication_configuration_templates",
+    "describe_source_networks",
     "describe_source_servers",
     "list_extensible_source_servers",
     "list_staging_accounts",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/literals.pyi` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -21,17 +21,19 @@
 __all__ = (
     "DataReplicationErrorStringType",
     "DataReplicationInitiationStepNameType",
     "DataReplicationInitiationStepStatusType",
     "DataReplicationStateType",
     "DescribeJobLogItemsPaginatorName",
     "DescribeJobsPaginatorName",
+    "DescribeLaunchConfigurationTemplatesPaginatorName",
     "DescribeRecoveryInstancesPaginatorName",
     "DescribeRecoverySnapshotsPaginatorName",
     "DescribeReplicationConfigurationTemplatesPaginatorName",
+    "DescribeSourceNetworksPaginatorName",
     "DescribeSourceServersPaginatorName",
     "EC2InstanceStateType",
     "ExtensionStatusType",
     "FailbackLaunchTypeType",
     "FailbackReplicationErrorType",
     "FailbackStateType",
     "InitiatedByType",
@@ -45,20 +47,22 @@
     "ListExtensibleSourceServersPaginatorName",
     "ListStagingAccountsPaginatorName",
     "OriginEnvironmentType",
     "PITPolicyRuleUnitsType",
     "RecoveryInstanceDataReplicationInitiationStepNameType",
     "RecoveryInstanceDataReplicationInitiationStepStatusType",
     "RecoveryInstanceDataReplicationStateType",
+    "RecoveryResultType",
     "RecoverySnapshotsOrderType",
     "ReplicationConfigurationDataPlaneRoutingType",
     "ReplicationConfigurationDefaultLargeStagingDiskTypeType",
     "ReplicationConfigurationEbsEncryptionType",
     "ReplicationConfigurationReplicatedDiskStagingDiskTypeType",
     "ReplicationDirectionType",
+    "ReplicationStatusType",
     "TargetInstanceTypeRightSizingMethodType",
     "drsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -105,19 +109,23 @@
     "PAUSED",
     "RESCAN",
     "STALLED",
     "STOPPED",
 ]
 DescribeJobLogItemsPaginatorName = Literal["describe_job_log_items"]
 DescribeJobsPaginatorName = Literal["describe_jobs"]
+DescribeLaunchConfigurationTemplatesPaginatorName = Literal[
+    "describe_launch_configuration_templates"
+]
 DescribeRecoveryInstancesPaginatorName = Literal["describe_recovery_instances"]
 DescribeRecoverySnapshotsPaginatorName = Literal["describe_recovery_snapshots"]
 DescribeReplicationConfigurationTemplatesPaginatorName = Literal[
     "describe_replication_configuration_templates"
 ]
+DescribeSourceNetworksPaginatorName = Literal["describe_source_networks"]
 DescribeSourceServersPaginatorName = Literal["describe_source_servers"]
 EC2InstanceStateType = Literal[
     "NOT_FOUND", "PENDING", "RUNNING", "SHUTTING-DOWN", "STOPPED", "STOPPING", "TERMINATED"
 ]
 ExtensionStatusType = Literal["EXTENDED", "EXTENSION_ERROR", "NOT_EXTENDED"]
 FailbackLaunchTypeType = Literal["DRILL", "RECOVERY"]
 FailbackReplicationErrorType = Literal[
@@ -149,37 +157,50 @@
     "FAILBACK_IN_PROGRESS",
     "FAILBACK_LAUNCH_STATE_NOT_AVAILABLE",
     "FAILBACK_NOT_READY_FOR_LAUNCH",
     "FAILBACK_NOT_STARTED",
     "FAILBACK_READY_FOR_LAUNCH",
 ]
 InitiatedByType = Literal[
+    "ASSOCIATE_NETWORK_RECOVERY",
+    "CREATE_NETWORK_RECOVERY",
     "DIAGNOSTIC",
     "FAILBACK",
     "START_DRILL",
     "START_RECOVERY",
     "TARGET_ACCOUNT",
     "TERMINATE_RECOVERY_INSTANCES",
+    "UPDATE_NETWORK_RECOVERY",
 ]
 JobLogEventType = Literal[
     "CLEANUP_END",
     "CLEANUP_FAIL",
     "CLEANUP_START",
     "CONVERSION_END",
     "CONVERSION_FAIL",
     "CONVERSION_START",
+    "DEPLOY_NETWORK_CONFIGURATION_END",
+    "DEPLOY_NETWORK_CONFIGURATION_FAILED",
+    "DEPLOY_NETWORK_CONFIGURATION_START",
     "JOB_CANCEL",
     "JOB_END",
     "JOB_START",
     "LAUNCH_FAILED",
     "LAUNCH_START",
+    "NETWORK_RECOVERY_FAIL",
     "SERVER_SKIPPED",
     "SNAPSHOT_END",
     "SNAPSHOT_FAIL",
     "SNAPSHOT_START",
+    "UPDATE_LAUNCH_TEMPLATE_END",
+    "UPDATE_LAUNCH_TEMPLATE_FAILED",
+    "UPDATE_LAUNCH_TEMPLATE_START",
+    "UPDATE_NETWORK_CONFIGURATION_END",
+    "UPDATE_NETWORK_CONFIGURATION_FAILED",
+    "UPDATE_NETWORK_CONFIGURATION_START",
     "USING_PREVIOUS_SNAPSHOT",
     "USING_PREVIOUS_SNAPSHOT_FAILED",
 ]
 JobStatusType = Literal["COMPLETED", "PENDING", "STARTED"]
 JobTypeType = Literal["CREATE_CONVERTED_SNAPSHOT", "LAUNCH", "TERMINATE"]
 LastLaunchResultType = Literal["FAILED", "NOT_STARTED", "PENDING", "SUCCEEDED"]
 LastLaunchTypeType = Literal["DRILL", "RECOVERY"]
@@ -222,22 +243,32 @@
     "NOT_STARTED",
     "PAUSED",
     "REPLICATION_STATE_NOT_AVAILABLE",
     "RESCAN",
     "STALLED",
     "STOPPED",
 ]
+RecoveryResultType = Literal[
+    "ASSOCIATE_FAIL",
+    "ASSOCIATE_SUCCESS",
+    "FAIL",
+    "IN_PROGRESS",
+    "NOT_STARTED",
+    "PARTIAL_SUCCESS",
+    "SUCCESS",
+]
 RecoverySnapshotsOrderType = Literal["ASC", "DESC"]
 ReplicationConfigurationDataPlaneRoutingType = Literal["PRIVATE_IP", "PUBLIC_IP"]
 ReplicationConfigurationDefaultLargeStagingDiskTypeType = Literal["AUTO", "GP2", "GP3", "ST1"]
-ReplicationConfigurationEbsEncryptionType = Literal["CUSTOM", "DEFAULT"]
+ReplicationConfigurationEbsEncryptionType = Literal["CUSTOM", "DEFAULT", "NONE"]
 ReplicationConfigurationReplicatedDiskStagingDiskTypeType = Literal[
     "AUTO", "GP2", "GP3", "IO1", "SC1", "ST1", "STANDARD"
 ]
 ReplicationDirectionType = Literal["FAILBACK", "FAILOVER"]
+ReplicationStatusType = Literal["ERROR", "IN_PROGRESS", "PROTECTED", "STOPPED"]
 TargetInstanceTypeRightSizingMethodType = Literal["BASIC", "NONE"]
 drsServiceName = Literal["drs"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -294,14 +325,15 @@
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
@@ -380,14 +412,15 @@
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
@@ -398,14 +431,15 @@
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
@@ -441,14 +475,15 @@
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
@@ -467,16 +502,19 @@
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
@@ -560,15 +598,17 @@
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
@@ -589,17 +629,19 @@
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "describe_job_log_items",
     "describe_jobs",
+    "describe_launch_configuration_templates",
     "describe_recovery_instances",
     "describe_recovery_snapshots",
     "describe_replication_configuration_templates",
+    "describe_source_networks",
     "describe_source_servers",
     "list_extensible_source_servers",
     "list_staging_accounts",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/paginator.py` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/paginator.py`

 * *Files 15% similar despite different names*

```diff
@@ -8,71 +8,73 @@
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_drs.client import drsClient
     from types_aiobotocore_drs.paginator import (
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
+        DescribeLaunchConfigurationTemplatesPaginator,
         DescribeRecoveryInstancesPaginator,
         DescribeRecoverySnapshotsPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
+        DescribeSourceNetworksPaginator,
         DescribeSourceServersPaginator,
         ListExtensibleSourceServersPaginator,
         ListStagingAccountsPaginator,
     )
 
     session = get_session()
     with session.create_client("drs") as client:
         client: drsClient
 
         describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
         describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
+        describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
         describe_recovery_instances_paginator: DescribeRecoveryInstancesPaginator = client.get_paginator("describe_recovery_instances")
         describe_recovery_snapshots_paginator: DescribeRecoverySnapshotsPaginator = client.get_paginator("describe_recovery_snapshots")
         describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
+        describe_source_networks_paginator: DescribeSourceNetworksPaginator = client.get_paginator("describe_source_networks")
         describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
         list_extensible_source_servers_paginator: ListExtensibleSourceServersPaginator = client.get_paginator("list_extensible_source_servers")
         list_staging_accounts_paginator: ListStagingAccountsPaginator = client.get_paginator("list_staging_accounts")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import RecoverySnapshotsOrderType
 from .type_defs import (
     DescribeJobLogItemsResponseTypeDef,
     DescribeJobsRequestFiltersTypeDef,
     DescribeJobsResponseTypeDef,
+    DescribeLaunchConfigurationTemplatesResponseTypeDef,
     DescribeRecoveryInstancesRequestFiltersTypeDef,
     DescribeRecoveryInstancesResponseTypeDef,
     DescribeRecoverySnapshotsRequestFiltersTypeDef,
     DescribeRecoverySnapshotsResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
+    DescribeSourceNetworksRequestFiltersTypeDef,
+    DescribeSourceNetworksResponseTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DescribeSourceServersResponseTypeDef,
     ListExtensibleSourceServersResponseTypeDef,
     ListStagingAccountsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeJobLogItemsPaginator",
     "DescribeJobsPaginator",
+    "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeRecoveryInstancesPaginator",
     "DescribeRecoverySnapshotsPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
+    "DescribeSourceNetworksPaginator",
     "DescribeSourceServersPaginator",
     "ListExtensibleSourceServersPaginator",
     "ListStagingAccountsPaginator",
 )
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
@@ -88,15 +90,15 @@
 class DescribeJobLogItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeJobLogItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejoblogitemspaginator)
     """
 
     def paginate(
-        self, *, jobID: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobLogItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeJobLogItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejoblogitemspaginator)
         """
 
 
@@ -106,33 +108,51 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeJobsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejobspaginator)
         """
 
 
+class DescribeLaunchConfigurationTemplatesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeLaunchConfigurationTemplates)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describelaunchconfigurationtemplatespaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        launchConfigurationTemplateIDs: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[DescribeLaunchConfigurationTemplatesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeLaunchConfigurationTemplates.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describelaunchconfigurationtemplatespaginator)
+        """
+
+
 class DescribeRecoveryInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeRecoveryInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describerecoveryinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeRecoveryInstancesRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRecoveryInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeRecoveryInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describerecoveryinstancespaginator)
         """
 
 
@@ -144,15 +164,15 @@
 
     def paginate(
         self,
         *,
         sourceServerID: str,
         filters: DescribeRecoverySnapshotsRequestFiltersTypeDef = ...,
         order: RecoverySnapshotsOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRecoverySnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeRecoverySnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describerecoverysnapshotspaginator)
         """
 
 
@@ -162,61 +182,79 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describereplicationconfigurationtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         replicationConfigurationTemplateIDs: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationConfigurationTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeReplicationConfigurationTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describereplicationconfigurationtemplatespaginator)
         """
 
 
+class DescribeSourceNetworksPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceNetworks)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourcenetworkspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        filters: DescribeSourceNetworksRequestFiltersTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[DescribeSourceNetworksResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceNetworks.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourcenetworkspaginator)
+        """
+
+
 class DescribeSourceServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourceserverspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeSourceServersRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSourceServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourceserverspaginator)
         """
 
 
 class ListExtensibleSourceServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListExtensibleSourceServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#listextensiblesourceserverspaginator)
     """
 
     def paginate(
-        self, *, stagingAccountID: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, stagingAccountID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExtensibleSourceServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListExtensibleSourceServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#listextensiblesourceserverspaginator)
         """
 
 
 class ListStagingAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListStagingAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#liststagingaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStagingAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListStagingAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#liststagingaccountspaginator)
         """
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/paginator.pyi` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/paginator.pyi`

 * *Files 15% similar despite different names*

```diff
@@ -8,70 +8,73 @@
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_drs.client import drsClient
     from types_aiobotocore_drs.paginator import (
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
+        DescribeLaunchConfigurationTemplatesPaginator,
         DescribeRecoveryInstancesPaginator,
         DescribeRecoverySnapshotsPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
+        DescribeSourceNetworksPaginator,
         DescribeSourceServersPaginator,
         ListExtensibleSourceServersPaginator,
         ListStagingAccountsPaginator,
     )
 
     session = get_session()
     with session.create_client("drs") as client:
         client: drsClient
 
         describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
         describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
+        describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
         describe_recovery_instances_paginator: DescribeRecoveryInstancesPaginator = client.get_paginator("describe_recovery_instances")
         describe_recovery_snapshots_paginator: DescribeRecoverySnapshotsPaginator = client.get_paginator("describe_recovery_snapshots")
         describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
+        describe_source_networks_paginator: DescribeSourceNetworksPaginator = client.get_paginator("describe_source_networks")
         describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
         list_extensible_source_servers_paginator: ListExtensibleSourceServersPaginator = client.get_paginator("list_extensible_source_servers")
         list_staging_accounts_paginator: ListStagingAccountsPaginator = client.get_paginator("list_staging_accounts")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import RecoverySnapshotsOrderType
 from .type_defs import (
     DescribeJobLogItemsResponseTypeDef,
     DescribeJobsRequestFiltersTypeDef,
     DescribeJobsResponseTypeDef,
+    DescribeLaunchConfigurationTemplatesResponseTypeDef,
     DescribeRecoveryInstancesRequestFiltersTypeDef,
     DescribeRecoveryInstancesResponseTypeDef,
     DescribeRecoverySnapshotsRequestFiltersTypeDef,
     DescribeRecoverySnapshotsResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
+    DescribeSourceNetworksRequestFiltersTypeDef,
+    DescribeSourceNetworksResponseTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DescribeSourceServersResponseTypeDef,
     ListExtensibleSourceServersResponseTypeDef,
     ListStagingAccountsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeJobLogItemsPaginator",
     "DescribeJobsPaginator",
+    "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeRecoveryInstancesPaginator",
     "DescribeRecoverySnapshotsPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
+    "DescribeSourceNetworksPaginator",
     "DescribeSourceServersPaginator",
     "ListExtensibleSourceServersPaginator",
     "ListStagingAccountsPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
@@ -84,15 +87,15 @@
 class DescribeJobLogItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeJobLogItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejoblogitemspaginator)
     """
 
     def paginate(
-        self, *, jobID: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobLogItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeJobLogItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejoblogitemspaginator)
         """
 
 class DescribeJobsPaginator(AioPaginator):
@@ -101,32 +104,49 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeJobsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describejobspaginator)
         """
 
+class DescribeLaunchConfigurationTemplatesPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeLaunchConfigurationTemplates)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describelaunchconfigurationtemplatespaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        launchConfigurationTemplateIDs: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[DescribeLaunchConfigurationTemplatesResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeLaunchConfigurationTemplates.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describelaunchconfigurationtemplatespaginator)
+        """
+
 class DescribeRecoveryInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeRecoveryInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describerecoveryinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeRecoveryInstancesRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRecoveryInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeRecoveryInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describerecoveryinstancespaginator)
         """
 
 class DescribeRecoverySnapshotsPaginator(AioPaginator):
@@ -137,15 +157,15 @@
 
     def paginate(
         self,
         *,
         sourceServerID: str,
         filters: DescribeRecoverySnapshotsRequestFiltersTypeDef = ...,
         order: RecoverySnapshotsOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRecoverySnapshotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeRecoverySnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describerecoverysnapshotspaginator)
         """
 
 class DescribeReplicationConfigurationTemplatesPaginator(AioPaginator):
@@ -154,58 +174,75 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describereplicationconfigurationtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         replicationConfigurationTemplateIDs: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationConfigurationTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeReplicationConfigurationTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describereplicationconfigurationtemplatespaginator)
         """
 
+class DescribeSourceNetworksPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceNetworks)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourcenetworkspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        filters: DescribeSourceNetworksRequestFiltersTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[DescribeSourceNetworksResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceNetworks.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourcenetworkspaginator)
+        """
+
 class DescribeSourceServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourceserverspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeSourceServersRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSourceServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.DescribeSourceServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#describesourceserverspaginator)
         """
 
 class ListExtensibleSourceServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListExtensibleSourceServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#listextensiblesourceserverspaginator)
     """
 
     def paginate(
-        self, *, stagingAccountID: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, stagingAccountID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExtensibleSourceServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListExtensibleSourceServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#listextensiblesourceserverspaginator)
         """
 
 class ListStagingAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListStagingAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#liststagingaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStagingAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs.Paginator.ListStagingAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/paginators/#liststagingaccountspaginator)
         """
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/type_defs.py` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/type_defs.py`

 * *Files 16% similar despite different names*

```diff
@@ -8,14 +8,15 @@
     ```python
     from types_aiobotocore_drs.type_defs import AccountTypeDef
 
     data: AccountTypeDef = {...}
     ```
 """
 import sys
+from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
@@ -33,134 +34,169 @@
     LaunchDispositionType,
     LaunchStatusType,
     OriginEnvironmentType,
     PITPolicyRuleUnitsType,
     RecoveryInstanceDataReplicationInitiationStepNameType,
     RecoveryInstanceDataReplicationInitiationStepStatusType,
     RecoveryInstanceDataReplicationStateType,
+    RecoveryResultType,
     RecoverySnapshotsOrderType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
     ReplicationDirectionType,
+    ReplicationStatusType,
     TargetInstanceTypeRightSizingMethodType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccountTypeDef",
+    "AssociateSourceNetworkStackRequestRequestTypeDef",
     "CPUTypeDef",
     "ConversionPropertiesTypeDef",
     "CreateExtendedSourceServerRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "LicensingTypeDef",
     "PITPolicyRuleTypeDef",
+    "CreateSourceNetworkRequestRequestTypeDef",
+    "CreateSourceNetworkResponseTypeDef",
     "DataReplicationErrorTypeDef",
     "DataReplicationInfoReplicatedDiskTypeDef",
     "DataReplicationInitiationStepTypeDef",
     "DeleteJobRequestRequestTypeDef",
+    "DeleteLaunchConfigurationTemplateRequestRequestTypeDef",
     "DeleteRecoveryInstanceRequestRequestTypeDef",
     "DeleteReplicationConfigurationTemplateRequestRequestTypeDef",
+    "DeleteSourceNetworkRequestRequestTypeDef",
     "DeleteSourceServerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
     "DescribeJobLogItemsRequestRequestTypeDef",
     "DescribeJobsRequestFiltersTypeDef",
+    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
+    "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
     "DescribeRecoveryInstancesRequestFiltersTypeDef",
     "DescribeRecoverySnapshotsRequestFiltersTypeDef",
     "RecoverySnapshotTypeDef",
+    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
     "DescribeReplicationConfigurationTemplatesRequestRequestTypeDef",
+    "DescribeSourceNetworksRequestFiltersTypeDef",
     "DescribeSourceServersRequestFiltersTypeDef",
     "DisconnectRecoveryInstanceRequestRequestTypeDef",
     "DisconnectSourceServerRequestRequestTypeDef",
     "DiskTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "SourceNetworkDataTypeDef",
+    "ExportSourceNetworkCfnTemplateRequestRequestTypeDef",
+    "ExportSourceNetworkCfnTemplateResponseTypeDef",
     "GetFailbackReplicationConfigurationRequestRequestTypeDef",
+    "GetFailbackReplicationConfigurationResponseTypeDef",
     "GetLaunchConfigurationRequestRequestTypeDef",
     "GetReplicationConfigurationRequestRequestTypeDef",
     "IdentificationHintsTypeDef",
     "ParticipatingServerTypeDef",
-    "LicensingTypeDef",
     "LifeCycleLastLaunchInitiatedTypeDef",
+    "ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
     "ListExtensibleSourceServersRequestRequestTypeDef",
     "StagingSourceServerTypeDef",
+    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
     "ListStagingAccountsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NetworkInterfaceTypeDef",
     "OSTypeDef",
+    "PaginatorConfigTypeDef",
+    "ParticipatingResourceIDTypeDef",
     "RecoveryInstanceDataReplicationErrorTypeDef",
     "RecoveryInstanceDataReplicationInfoReplicatedDiskTypeDef",
     "RecoveryInstanceDataReplicationInitiationStepTypeDef",
     "RecoveryInstanceDiskTypeDef",
     "RecoveryInstanceFailbackTypeDef",
+    "RecoveryLifeCycleTypeDef",
     "ReplicationConfigurationReplicatedDiskTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryDataReplicationRequestRequestTypeDef",
     "ReverseReplicationRequestRequestTypeDef",
+    "ReverseReplicationResponseTypeDef",
     "SourceCloudPropertiesTypeDef",
     "StagingAreaTypeDef",
     "StartFailbackLaunchRequestRequestTypeDef",
     "StartRecoveryRequestSourceServerTypeDef",
     "StartReplicationRequestRequestTypeDef",
+    "StartSourceNetworkRecoveryRequestNetworkEntryTypeDef",
+    "StartSourceNetworkReplicationRequestRequestTypeDef",
     "StopFailbackRequestRequestTypeDef",
     "StopReplicationRequestRequestTypeDef",
+    "StopSourceNetworkReplicationRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TerminateRecoveryInstancesRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFailbackReplicationConfigurationRequestRequestTypeDef",
-    "JobLogEventDataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetFailbackReplicationConfigurationResponseTypeDef",
     "ListStagingAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ReverseReplicationResponseTypeDef",
+    "CreateLaunchConfigurationTemplateRequestRequestTypeDef",
+    "LaunchConfigurationTemplateTypeDef",
+    "LaunchConfigurationTypeDef",
+    "UpdateLaunchConfigurationRequestRequestTypeDef",
+    "UpdateLaunchConfigurationTemplateRequestRequestTypeDef",
     "CreateReplicationConfigurationTemplateRequestRequestTypeDef",
     "ReplicationConfigurationTemplateResponseMetadataTypeDef",
     "ReplicationConfigurationTemplateTypeDef",
     "UpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     "DataReplicationInitiationTypeDef",
-    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
-    "ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
-    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
     "DescribeJobsRequestDescribeJobsPaginateTypeDef",
     "DescribeJobsRequestRequestTypeDef",
     "DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef",
     "DescribeRecoveryInstancesRequestRequestTypeDef",
     "DescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef",
     "DescribeRecoverySnapshotsRequestRequestTypeDef",
     "DescribeRecoverySnapshotsResponseTypeDef",
+    "DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef",
+    "DescribeSourceNetworksRequestRequestTypeDef",
     "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     "DescribeSourceServersRequestRequestTypeDef",
-    "JobTypeDef",
-    "LaunchConfigurationTypeDef",
-    "UpdateLaunchConfigurationRequestRequestTypeDef",
+    "EventResourceDataTypeDef",
     "LifeCycleLastLaunchTypeDef",
     "ListExtensibleSourceServersResponseTypeDef",
     "SourcePropertiesTypeDef",
+    "ParticipatingResourceTypeDef",
     "RecoveryInstanceDataReplicationInitiationTypeDef",
     "RecoveryInstancePropertiesTypeDef",
+    "SourceNetworkTypeDef",
     "ReplicationConfigurationTypeDef",
     "UpdateReplicationConfigurationRequestRequestTypeDef",
     "StartRecoveryRequestRequestTypeDef",
-    "JobLogTypeDef",
+    "StartSourceNetworkRecoveryRequestRequestTypeDef",
+    "CreateLaunchConfigurationTemplateResponseTypeDef",
+    "DescribeLaunchConfigurationTemplatesResponseTypeDef",
+    "UpdateLaunchConfigurationTemplateResponseTypeDef",
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     "DataReplicationInfoTypeDef",
-    "DescribeJobsResponseTypeDef",
-    "StartFailbackLaunchResponseTypeDef",
-    "StartRecoveryResponseTypeDef",
-    "TerminateRecoveryInstancesResponseTypeDef",
+    "JobLogEventDataTypeDef",
     "LifeCycleTypeDef",
+    "JobTypeDef",
     "RecoveryInstanceDataReplicationInfoTypeDef",
-    "DescribeJobLogItemsResponseTypeDef",
+    "DescribeSourceNetworksResponseTypeDef",
+    "StartSourceNetworkReplicationResponseTypeDef",
+    "StopSourceNetworkReplicationResponseTypeDef",
+    "JobLogTypeDef",
     "SourceServerResponseMetadataTypeDef",
     "SourceServerTypeDef",
+    "AssociateSourceNetworkStackResponseTypeDef",
+    "DescribeJobsResponseTypeDef",
+    "StartFailbackLaunchResponseTypeDef",
+    "StartRecoveryResponseTypeDef",
+    "StartSourceNetworkRecoveryResponseTypeDef",
+    "TerminateRecoveryInstancesResponseTypeDef",
     "RecoveryInstanceTypeDef",
+    "DescribeJobLogItemsResponseTypeDef",
     "CreateExtendedSourceServerResponseTypeDef",
     "DescribeSourceServersResponseTypeDef",
     "StartReplicationResponseTypeDef",
     "StopReplicationResponseTypeDef",
     "DescribeRecoveryInstancesResponseTypeDef",
 )
 
@@ -168,14 +204,22 @@
     "AccountTypeDef",
     {
         "accountID": str,
     },
     total=False,
 )
 
+AssociateSourceNetworkStackRequestRequestTypeDef = TypedDict(
+    "AssociateSourceNetworkStackRequestRequestTypeDef",
+    {
+        "cfnStackName": str,
+        "sourceNetworkID": str,
+    },
+)
+
 CPUTypeDef = TypedDict(
     "CPUTypeDef",
     {
         "cores": int,
         "modelName": str,
     },
     total=False,
@@ -211,23 +255,20 @@
 class CreateExtendedSourceServerRequestRequestTypeDef(
     _RequiredCreateExtendedSourceServerRequestRequestTypeDef,
     _OptionalCreateExtendedSourceServerRequestRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+LicensingTypeDef = TypedDict(
+    "LicensingTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "osByol": bool,
     },
+    total=False,
 )
 
 _RequiredPITPolicyRuleTypeDef = TypedDict(
     "_RequiredPITPolicyRuleTypeDef",
     {
         "interval": int,
         "retentionDuration": int,
@@ -244,14 +285,46 @@
 )
 
 
 class PITPolicyRuleTypeDef(_RequiredPITPolicyRuleTypeDef, _OptionalPITPolicyRuleTypeDef):
     pass
 
 
+_RequiredCreateSourceNetworkRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateSourceNetworkRequestRequestTypeDef",
+    {
+        "originAccountID": str,
+        "originRegion": str,
+        "vpcID": str,
+    },
+)
+_OptionalCreateSourceNetworkRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateSourceNetworkRequestRequestTypeDef",
+    {
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class CreateSourceNetworkRequestRequestTypeDef(
+    _RequiredCreateSourceNetworkRequestRequestTypeDef,
+    _OptionalCreateSourceNetworkRequestRequestTypeDef,
+):
+    pass
+
+
+CreateSourceNetworkResponseTypeDef = TypedDict(
+    "CreateSourceNetworkResponseTypeDef",
+    {
+        "sourceNetworkID": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataReplicationErrorTypeDef = TypedDict(
     "DataReplicationErrorTypeDef",
     {
         "error": DataReplicationErrorStringType,
         "rawError": str,
     },
     total=False,
@@ -281,45 +354,71 @@
 DeleteJobRequestRequestTypeDef = TypedDict(
     "DeleteJobRequestRequestTypeDef",
     {
         "jobID": str,
     },
 )
 
+DeleteLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "DeleteLaunchConfigurationTemplateRequestRequestTypeDef",
+    {
+        "launchConfigurationTemplateID": str,
+    },
+)
+
 DeleteRecoveryInstanceRequestRequestTypeDef = TypedDict(
     "DeleteRecoveryInstanceRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
 DeleteReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "DeleteReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "replicationConfigurationTemplateID": str,
     },
 )
 
+DeleteSourceNetworkRequestRequestTypeDef = TypedDict(
+    "DeleteSourceNetworkRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+
 DeleteSourceServerRequestRequestTypeDef = TypedDict(
     "DeleteSourceServerRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "jobID": str,
+    },
+)
+_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef(
+    _RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
+    _OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeJobLogItemsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeJobLogItemsRequestRequestTypeDef",
     {
         "jobID": str,
     },
 )
 _OptionalDescribeJobLogItemsRequestRequestTypeDef = TypedDict(
@@ -345,14 +444,33 @@
         "fromDate": str,
         "jobIDs": Sequence[str],
         "toDate": str,
     },
     total=False,
 )
 
+DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef = TypedDict(
+    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
+    {
+        "launchConfigurationTemplateIDs": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+DescribeLaunchConfigurationTemplatesRequestRequestTypeDef = TypedDict(
+    "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
+    {
+        "launchConfigurationTemplateIDs": Sequence[str],
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 DescribeRecoveryInstancesRequestFiltersTypeDef = TypedDict(
     "DescribeRecoveryInstancesRequestFiltersTypeDef",
     {
         "recoveryInstanceIDs": Sequence[str],
         "sourceServerIDs": Sequence[str],
     },
     total=False,
@@ -385,24 +503,43 @@
 )
 
 
 class RecoverySnapshotTypeDef(_RequiredRecoverySnapshotTypeDef, _OptionalRecoverySnapshotTypeDef):
     pass
 
 
+DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef = TypedDict(
+    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
+    {
+        "replicationConfigurationTemplateIDs": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReplicationConfigurationTemplatesRequestRequestTypeDef = TypedDict(
     "DescribeReplicationConfigurationTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "replicationConfigurationTemplateIDs": Sequence[str],
     },
     total=False,
 )
 
+DescribeSourceNetworksRequestFiltersTypeDef = TypedDict(
+    "DescribeSourceNetworksRequestFiltersTypeDef",
+    {
+        "originAccountID": str,
+        "originRegion": str,
+        "sourceNetworkIDs": Sequence[str],
+    },
+    total=False,
+)
+
 DescribeSourceServersRequestFiltersTypeDef = TypedDict(
     "DescribeSourceServersRequestFiltersTypeDef",
     {
         "hardwareId": str,
         "sourceServerIDs": Sequence[str],
         "stagingAccountIDs": Sequence[str],
     },
@@ -428,21 +565,65 @@
     {
         "bytes": int,
         "deviceName": str,
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
+SourceNetworkDataTypeDef = TypedDict(
+    "SourceNetworkDataTypeDef",
+    {
+        "sourceNetworkID": str,
+        "sourceVpc": str,
+        "stackName": str,
+        "targetVpc": str,
+    },
+    total=False,
+)
+
+ExportSourceNetworkCfnTemplateRequestRequestTypeDef = TypedDict(
+    "ExportSourceNetworkCfnTemplateRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+
+ExportSourceNetworkCfnTemplateResponseTypeDef = TypedDict(
+    "ExportSourceNetworkCfnTemplateResponseTypeDef",
+    {
+        "s3DestinationUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFailbackReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "GetFailbackReplicationConfigurationRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
+GetFailbackReplicationConfigurationResponseTypeDef = TypedDict(
+    "GetFailbackReplicationConfigurationResponseTypeDef",
+    {
+        "bandwidthThrottling": int,
+        "name": str,
+        "recoveryInstanceID": str,
+        "usePrivateIP": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "GetLaunchConfigurationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
@@ -470,32 +651,46 @@
         "launchStatus": LaunchStatusType,
         "recoveryInstanceID": str,
         "sourceServerID": str,
     },
     total=False,
 )
 
-LicensingTypeDef = TypedDict(
-    "LicensingTypeDef",
-    {
-        "osByol": bool,
-    },
-    total=False,
-)
-
 LifeCycleLastLaunchInitiatedTypeDef = TypedDict(
     "LifeCycleLastLaunchInitiatedTypeDef",
     {
         "apiCallDateTime": str,
         "jobID": str,
         "type": LastLaunchTypeType,
     },
     total=False,
 )
 
+_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
+    "_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
+    {
+        "stagingAccountID": str,
+    },
+)
+_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
+    "_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef(
+    _RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
+    _OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListExtensibleSourceServersRequestRequestTypeDef = TypedDict(
     "_RequiredListExtensibleSourceServersRequestRequestTypeDef",
     {
         "stagingAccountID": str,
     },
 )
 _OptionalListExtensibleSourceServersRequestRequestTypeDef = TypedDict(
@@ -521,14 +716,22 @@
         "arn": str,
         "hostname": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+ListStagingAccountsRequestListStagingAccountsPaginateTypeDef = TypedDict(
+    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStagingAccountsRequestRequestTypeDef = TypedDict(
     "ListStagingAccountsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -537,14 +740,22 @@
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
 NetworkInterfaceTypeDef = TypedDict(
     "NetworkInterfaceTypeDef",
     {
         "ips": List[str],
         "isPrimary": bool,
         "macAddress": str,
     },
@@ -555,14 +766,32 @@
     "OSTypeDef",
     {
         "fullString": str,
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
+ParticipatingResourceIDTypeDef = TypedDict(
+    "ParticipatingResourceIDTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+    total=False,
+)
+
 RecoveryInstanceDataReplicationErrorTypeDef = TypedDict(
     "RecoveryInstanceDataReplicationErrorTypeDef",
     {
         "error": FailbackReplicationErrorType,
         "rawError": str,
     },
     total=False,
@@ -612,41 +841,70 @@
         "failbackToOriginalServer": bool,
         "firstByteDateTime": str,
         "state": FailbackStateType,
     },
     total=False,
 )
 
+RecoveryLifeCycleTypeDef = TypedDict(
+    "RecoveryLifeCycleTypeDef",
+    {
+        "apiCallDateTime": datetime,
+        "jobID": str,
+        "lastRecoveryResult": RecoveryResultType,
+    },
+    total=False,
+)
+
 ReplicationConfigurationReplicatedDiskTypeDef = TypedDict(
     "ReplicationConfigurationReplicatedDiskTypeDef",
     {
         "deviceName": str,
         "iops": int,
         "isBootDisk": bool,
         "optimizedStagingDiskType": ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
         "stagingDiskType": ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
         "throughput": int,
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
 RetryDataReplicationRequestRequestTypeDef = TypedDict(
     "RetryDataReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
 ReverseReplicationRequestRequestTypeDef = TypedDict(
     "ReverseReplicationRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
+ReverseReplicationResponseTypeDef = TypedDict(
+    "ReverseReplicationResponseTypeDef",
+    {
+        "reversedDirectionSourceServerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SourceCloudPropertiesTypeDef = TypedDict(
     "SourceCloudPropertiesTypeDef",
     {
         "originAccountID": str,
         "originAvailabilityZone": str,
         "originRegion": str,
     },
@@ -711,28 +969,64 @@
 StartReplicationRequestRequestTypeDef = TypedDict(
     "StartReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
+_RequiredStartSourceNetworkRecoveryRequestNetworkEntryTypeDef = TypedDict(
+    "_RequiredStartSourceNetworkRecoveryRequestNetworkEntryTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+_OptionalStartSourceNetworkRecoveryRequestNetworkEntryTypeDef = TypedDict(
+    "_OptionalStartSourceNetworkRecoveryRequestNetworkEntryTypeDef",
+    {
+        "cfnStackName": str,
+    },
+    total=False,
+)
+
+
+class StartSourceNetworkRecoveryRequestNetworkEntryTypeDef(
+    _RequiredStartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+    _OptionalStartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+):
+    pass
+
+
+StartSourceNetworkReplicationRequestRequestTypeDef = TypedDict(
+    "StartSourceNetworkReplicationRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+
 StopFailbackRequestRequestTypeDef = TypedDict(
     "StopFailbackRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
 StopReplicationRequestRequestTypeDef = TypedDict(
     "StopReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
+StopSourceNetworkReplicationRequestRequestTypeDef = TypedDict(
+    "StopSourceNetworkReplicationRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
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
@@ -772,68 +1066,121 @@
 class UpdateFailbackReplicationConfigurationRequestRequestTypeDef(
     _RequiredUpdateFailbackReplicationConfigurationRequestRequestTypeDef,
     _OptionalUpdateFailbackReplicationConfigurationRequestRequestTypeDef,
 ):
     pass
 
 
-JobLogEventDataTypeDef = TypedDict(
-    "JobLogEventDataTypeDef",
+ListStagingAccountsResponseTypeDef = TypedDict(
+    "ListStagingAccountsResponseTypeDef",
     {
-        "conversionProperties": ConversionPropertiesTypeDef,
-        "conversionServerID": str,
-        "rawError": str,
-        "sourceServerID": str,
-        "targetInstanceID": str,
+        "accounts": List[AccountTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "CreateLaunchConfigurationTemplateRequestRequestTypeDef",
+    {
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "exportBucketArn": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "tags": Mapping[str, str],
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+LaunchConfigurationTemplateTypeDef = TypedDict(
+    "LaunchConfigurationTemplateTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "arn": str,
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "exportBucketArn": str,
+        "launchConfigurationTemplateID": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "tags": Dict[str, str],
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
+    total=False,
 )
 
-GetFailbackReplicationConfigurationResponseTypeDef = TypedDict(
-    "GetFailbackReplicationConfigurationResponseTypeDef",
+LaunchConfigurationTypeDef = TypedDict(
+    "LaunchConfigurationTypeDef",
     {
-        "bandwidthThrottling": int,
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "ec2LaunchTemplateID": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
         "name": str,
-        "recoveryInstanceID": str,
-        "usePrivateIP": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sourceServerID": str,
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListStagingAccountsResponseTypeDef = TypedDict(
-    "ListStagingAccountsResponseTypeDef",
+_RequiredUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateLaunchConfigurationRequestRequestTypeDef",
     {
-        "accounts": List[AccountTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sourceServerID": str,
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_OptionalUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateLaunchConfigurationRequestRequestTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "name": str,
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
+    total=False,
 )
 
-ReverseReplicationResponseTypeDef = TypedDict(
-    "ReverseReplicationResponseTypeDef",
+
+class UpdateLaunchConfigurationRequestRequestTypeDef(
+    _RequiredUpdateLaunchConfigurationRequestRequestTypeDef,
+    _OptionalUpdateLaunchConfigurationRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef",
     {
-        "reversedDirectionSourceServerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "launchConfigurationTemplateID": str,
     },
 )
+_OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef",
+    {
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "exportBucketArn": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
+    },
+    total=False,
+)
+
+
+class UpdateLaunchConfigurationTemplateRequestRequestTypeDef(
+    _RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
+    _OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
+):
+    pass
+
 
 _RequiredCreateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "associateDefaultSecurityGroup": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
@@ -847,14 +1194,15 @@
         "stagingAreaTags": Mapping[str, str],
         "useDedicatedReplicationServer": bool,
     },
 )
 _OptionalCreateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalCreateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
+        "autoReplicateNewDisks": bool,
         "ebsEncryptionKeyArn": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
@@ -866,43 +1214,45 @@
 
 
 ReplicationConfigurationTemplateResponseMetadataTypeDef = TypedDict(
     "ReplicationConfigurationTemplateResponseMetadataTypeDef",
     {
         "arn": str,
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "pitPolicy": List[PITPolicyRuleTypeDef],
         "replicationConfigurationTemplateID": str,
         "replicationServerInstanceType": str,
         "replicationServersSecurityGroupsIDs": List[str],
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Dict[str, str],
         "tags": Dict[str, str],
         "useDedicatedReplicationServer": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredReplicationConfigurationTemplateTypeDef = TypedDict(
     "_RequiredReplicationConfigurationTemplateTypeDef",
     {
         "replicationConfigurationTemplateID": str,
     },
 )
 _OptionalReplicationConfigurationTemplateTypeDef = TypedDict(
     "_OptionalReplicationConfigurationTemplateTypeDef",
     {
         "arn": str,
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "pitPolicy": List[PITPolicyRuleTypeDef],
@@ -931,14 +1281,15 @@
     },
 )
 _OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "arn": str,
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "pitPolicy": Sequence[PITPolicyRuleTypeDef],
@@ -965,80 +1316,19 @@
         "nextAttemptDateTime": str,
         "startDateTime": str,
         "steps": List[DataReplicationInitiationStepTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    {
-        "jobID": str,
-    },
-)
-_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef(
-    _RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    _OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-):
-    pass
-
-
-DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef = TypedDict(
-    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
-    {
-        "replicationConfigurationTemplateIDs": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
-    "_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
-    {
-        "stagingAccountID": str,
-    },
-)
-_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
-    "_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef(
-    _RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
-    _OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
-):
-    pass
-
-
-ListStagingAccountsRequestListStagingAccountsPaginateTypeDef = TypedDict(
-    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeJobsRequestDescribeJobsPaginateTypeDef = TypedDict(
     "DescribeJobsRequestDescribeJobsPaginateTypeDef",
     {
         "filters": DescribeJobsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeJobsRequestRequestTypeDef = TypedDict(
     "DescribeJobsRequestRequestTypeDef",
     {
@@ -1049,15 +1339,15 @@
     total=False,
 )
 
 DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef = TypedDict(
     "DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef",
     {
         "filters": DescribeRecoveryInstancesRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeRecoveryInstancesRequestRequestTypeDef = TypedDict(
     "DescribeRecoveryInstancesRequestRequestTypeDef",
     {
@@ -1075,15 +1365,15 @@
     },
 )
 _OptionalDescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef = TypedDict(
     "_OptionalDescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef",
     {
         "filters": DescribeRecoverySnapshotsRequestFiltersTypeDef,
         "order": RecoverySnapshotsOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef(
     _RequiredDescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef,
@@ -1118,133 +1408,103 @@
 
 
 DescribeRecoverySnapshotsResponseTypeDef = TypedDict(
     "DescribeRecoverySnapshotsResponseTypeDef",
     {
         "items": List[RecoverySnapshotTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef = TypedDict(
-    "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
+DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef = TypedDict(
+    "DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef",
     {
-        "filters": DescribeSourceServersRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filters": DescribeSourceNetworksRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeSourceServersRequestRequestTypeDef = TypedDict(
-    "DescribeSourceServersRequestRequestTypeDef",
+DescribeSourceNetworksRequestRequestTypeDef = TypedDict(
+    "DescribeSourceNetworksRequestRequestTypeDef",
     {
-        "filters": DescribeSourceServersRequestFiltersTypeDef,
+        "filters": DescribeSourceNetworksRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-_RequiredJobTypeDef = TypedDict(
-    "_RequiredJobTypeDef",
-    {
-        "jobID": str,
-    },
-)
-_OptionalJobTypeDef = TypedDict(
-    "_OptionalJobTypeDef",
+DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef = TypedDict(
+    "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     {
-        "arn": str,
-        "creationDateTime": str,
-        "endDateTime": str,
-        "initiatedBy": InitiatedByType,
-        "participatingServers": List[ParticipatingServerTypeDef],
-        "status": JobStatusType,
-        "tags": Dict[str, str],
-        "type": JobTypeType,
+        "filters": DescribeSourceServersRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
-    pass
-
-
-LaunchConfigurationTypeDef = TypedDict(
-    "LaunchConfigurationTypeDef",
+DescribeSourceServersRequestRequestTypeDef = TypedDict(
+    "DescribeSourceServersRequestRequestTypeDef",
     {
-        "copyPrivateIp": bool,
-        "copyTags": bool,
-        "ec2LaunchTemplateID": str,
-        "launchDisposition": LaunchDispositionType,
-        "licensing": LicensingTypeDef,
-        "name": str,
-        "sourceServerID": str,
-        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "filters": DescribeSourceServersRequestFiltersTypeDef,
+        "maxResults": int,
+        "nextToken": str,
     },
+    total=False,
 )
 
-_RequiredUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateLaunchConfigurationRequestRequestTypeDef",
-    {
-        "sourceServerID": str,
-    },
-)
-_OptionalUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateLaunchConfigurationRequestRequestTypeDef",
+EventResourceDataTypeDef = TypedDict(
+    "EventResourceDataTypeDef",
     {
-        "copyPrivateIp": bool,
-        "copyTags": bool,
-        "launchDisposition": LaunchDispositionType,
-        "licensing": LicensingTypeDef,
-        "name": str,
-        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
+        "sourceNetworkData": SourceNetworkDataTypeDef,
     },
     total=False,
 )
 
-
-class UpdateLaunchConfigurationRequestRequestTypeDef(
-    _RequiredUpdateLaunchConfigurationRequestRequestTypeDef,
-    _OptionalUpdateLaunchConfigurationRequestRequestTypeDef,
-):
-    pass
-
-
 LifeCycleLastLaunchTypeDef = TypedDict(
     "LifeCycleLastLaunchTypeDef",
     {
         "initiated": LifeCycleLastLaunchInitiatedTypeDef,
+        "status": LaunchStatusType,
     },
     total=False,
 )
 
 ListExtensibleSourceServersResponseTypeDef = TypedDict(
     "ListExtensibleSourceServersResponseTypeDef",
     {
         "items": List[StagingSourceServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourcePropertiesTypeDef = TypedDict(
     "SourcePropertiesTypeDef",
     {
         "cpus": List[CPUTypeDef],
         "disks": List[DiskTypeDef],
         "identificationHints": IdentificationHintsTypeDef,
         "lastUpdatedDateTime": str,
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "os": OSTypeDef,
         "ramBytes": int,
         "recommendedInstanceType": str,
+        "supportsNitroInstances": bool,
+    },
+    total=False,
+)
+
+ParticipatingResourceTypeDef = TypedDict(
+    "ParticipatingResourceTypeDef",
+    {
+        "launchStatus": LaunchStatusType,
+        "participatingResourceID": ParticipatingResourceIDTypeDef,
     },
     total=False,
 )
 
 RecoveryInstanceDataReplicationInitiationTypeDef = TypedDict(
     "RecoveryInstanceDataReplicationInitiationTypeDef",
     {
@@ -1264,18 +1524,37 @@
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "os": OSTypeDef,
         "ramBytes": int,
     },
     total=False,
 )
 
+SourceNetworkTypeDef = TypedDict(
+    "SourceNetworkTypeDef",
+    {
+        "arn": str,
+        "cfnStackName": str,
+        "lastRecovery": RecoveryLifeCycleTypeDef,
+        "launchedVpcID": str,
+        "replicationStatus": ReplicationStatusType,
+        "replicationStatusDetails": str,
+        "sourceAccountID": str,
+        "sourceNetworkID": str,
+        "sourceRegion": str,
+        "sourceVpcID": str,
+        "tags": Dict[str, str],
+    },
+    total=False,
+)
+
 ReplicationConfigurationTypeDef = TypedDict(
     "ReplicationConfigurationTypeDef",
     {
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "name": str,
@@ -1283,28 +1562,29 @@
         "replicatedDisks": List[ReplicationConfigurationReplicatedDiskTypeDef],
         "replicationServerInstanceType": str,
         "replicationServersSecurityGroupsIDs": List[str],
         "sourceServerID": str,
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Dict[str, str],
         "useDedicatedReplicationServer": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateReplicationConfigurationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 _OptionalUpdateReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateReplicationConfigurationRequestRequestTypeDef",
     {
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "name": str,
@@ -1345,205 +1625,339 @@
 
 class StartRecoveryRequestRequestTypeDef(
     _RequiredStartRecoveryRequestRequestTypeDef, _OptionalStartRecoveryRequestRequestTypeDef
 ):
     pass
 
 
-JobLogTypeDef = TypedDict(
-    "JobLogTypeDef",
+_RequiredStartSourceNetworkRecoveryRequestRequestTypeDef = TypedDict(
+    "_RequiredStartSourceNetworkRecoveryRequestRequestTypeDef",
     {
-        "event": JobLogEventType,
-        "eventData": JobLogEventDataTypeDef,
-        "logDateTime": str,
+        "sourceNetworks": Sequence[StartSourceNetworkRecoveryRequestNetworkEntryTypeDef],
+    },
+)
+_OptionalStartSourceNetworkRecoveryRequestRequestTypeDef = TypedDict(
+    "_OptionalStartSourceNetworkRecoveryRequestRequestTypeDef",
+    {
+        "deployAsNew": bool,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
+class StartSourceNetworkRecoveryRequestRequestTypeDef(
+    _RequiredStartSourceNetworkRecoveryRequestRequestTypeDef,
+    _OptionalStartSourceNetworkRecoveryRequestRequestTypeDef,
+):
+    pass
+
+
+CreateLaunchConfigurationTemplateResponseTypeDef = TypedDict(
+    "CreateLaunchConfigurationTemplateResponseTypeDef",
+    {
+        "launchConfigurationTemplate": LaunchConfigurationTemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeLaunchConfigurationTemplatesResponseTypeDef = TypedDict(
+    "DescribeLaunchConfigurationTemplatesResponseTypeDef",
+    {
+        "items": List[LaunchConfigurationTemplateTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateLaunchConfigurationTemplateResponseTypeDef = TypedDict(
+    "UpdateLaunchConfigurationTemplateResponseTypeDef",
+    {
+        "launchConfigurationTemplate": LaunchConfigurationTemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeReplicationConfigurationTemplatesResponseTypeDef = TypedDict(
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     {
         "items": List[ReplicationConfigurationTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataReplicationInfoTypeDef = TypedDict(
     "DataReplicationInfoTypeDef",
     {
         "dataReplicationError": DataReplicationErrorTypeDef,
         "dataReplicationInitiation": DataReplicationInitiationTypeDef,
         "dataReplicationState": DataReplicationStateType,
         "etaDateTime": str,
         "lagDuration": str,
         "replicatedDisks": List[DataReplicationInfoReplicatedDiskTypeDef],
+        "stagingAvailabilityZone": str,
     },
     total=False,
 )
 
-DescribeJobsResponseTypeDef = TypedDict(
-    "DescribeJobsResponseTypeDef",
-    {
-        "items": List[JobTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFailbackLaunchResponseTypeDef = TypedDict(
-    "StartFailbackLaunchResponseTypeDef",
-    {
-        "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRecoveryResponseTypeDef = TypedDict(
-    "StartRecoveryResponseTypeDef",
-    {
-        "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateRecoveryInstancesResponseTypeDef = TypedDict(
-    "TerminateRecoveryInstancesResponseTypeDef",
+JobLogEventDataTypeDef = TypedDict(
+    "JobLogEventDataTypeDef",
     {
-        "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "conversionProperties": ConversionPropertiesTypeDef,
+        "conversionServerID": str,
+        "eventResourceData": EventResourceDataTypeDef,
+        "rawError": str,
+        "sourceServerID": str,
+        "targetInstanceID": str,
     },
+    total=False,
 )
 
 LifeCycleTypeDef = TypedDict(
     "LifeCycleTypeDef",
     {
         "addedToServiceDateTime": str,
         "elapsedReplicationDuration": str,
         "firstByteDateTime": str,
         "lastLaunch": LifeCycleLastLaunchTypeDef,
         "lastSeenByServiceDateTime": str,
     },
     total=False,
 )
 
+_RequiredJobTypeDef = TypedDict(
+    "_RequiredJobTypeDef",
+    {
+        "jobID": str,
+    },
+)
+_OptionalJobTypeDef = TypedDict(
+    "_OptionalJobTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": str,
+        "endDateTime": str,
+        "initiatedBy": InitiatedByType,
+        "participatingResources": List[ParticipatingResourceTypeDef],
+        "participatingServers": List[ParticipatingServerTypeDef],
+        "status": JobStatusType,
+        "tags": Dict[str, str],
+        "type": JobTypeType,
+    },
+    total=False,
+)
+
+
+class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
+    pass
+
+
 RecoveryInstanceDataReplicationInfoTypeDef = TypedDict(
     "RecoveryInstanceDataReplicationInfoTypeDef",
     {
         "dataReplicationError": RecoveryInstanceDataReplicationErrorTypeDef,
         "dataReplicationInitiation": RecoveryInstanceDataReplicationInitiationTypeDef,
         "dataReplicationState": RecoveryInstanceDataReplicationStateType,
         "etaDateTime": str,
         "lagDuration": str,
         "replicatedDisks": List[RecoveryInstanceDataReplicationInfoReplicatedDiskTypeDef],
+        "stagingAvailabilityZone": str,
     },
     total=False,
 )
 
-DescribeJobLogItemsResponseTypeDef = TypedDict(
-    "DescribeJobLogItemsResponseTypeDef",
+DescribeSourceNetworksResponseTypeDef = TypedDict(
+    "DescribeSourceNetworksResponseTypeDef",
     {
-        "items": List[JobLogTypeDef],
+        "items": List[SourceNetworkTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSourceNetworkReplicationResponseTypeDef = TypedDict(
+    "StartSourceNetworkReplicationResponseTypeDef",
+    {
+        "sourceNetwork": SourceNetworkTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+StopSourceNetworkReplicationResponseTypeDef = TypedDict(
+    "StopSourceNetworkReplicationResponseTypeDef",
+    {
+        "sourceNetwork": SourceNetworkTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+JobLogTypeDef = TypedDict(
+    "JobLogTypeDef",
+    {
+        "event": JobLogEventType,
+        "eventData": JobLogEventDataTypeDef,
+        "logDateTime": str,
+    },
+    total=False,
+)
+
 SourceServerResponseMetadataTypeDef = TypedDict(
     "SourceServerResponseMetadataTypeDef",
     {
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
         "lastLaunchResult": LastLaunchResultType,
         "lifeCycle": LifeCycleTypeDef,
         "recoveryInstanceId": str,
         "replicationDirection": ReplicationDirectionType,
         "reversedDirectionSourceServerArn": str,
         "sourceCloudProperties": SourceCloudPropertiesTypeDef,
+        "sourceNetworkID": str,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "stagingArea": StagingAreaTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerTypeDef = TypedDict(
     "SourceServerTypeDef",
     {
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
         "lastLaunchResult": LastLaunchResultType,
         "lifeCycle": LifeCycleTypeDef,
         "recoveryInstanceId": str,
         "replicationDirection": ReplicationDirectionType,
         "reversedDirectionSourceServerArn": str,
         "sourceCloudProperties": SourceCloudPropertiesTypeDef,
+        "sourceNetworkID": str,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "stagingArea": StagingAreaTypeDef,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+AssociateSourceNetworkStackResponseTypeDef = TypedDict(
+    "AssociateSourceNetworkStackResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeJobsResponseTypeDef = TypedDict(
+    "DescribeJobsResponseTypeDef",
+    {
+        "items": List[JobTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartFailbackLaunchResponseTypeDef = TypedDict(
+    "StartFailbackLaunchResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartRecoveryResponseTypeDef = TypedDict(
+    "StartRecoveryResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSourceNetworkRecoveryResponseTypeDef = TypedDict(
+    "StartSourceNetworkRecoveryResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TerminateRecoveryInstancesResponseTypeDef = TypedDict(
+    "TerminateRecoveryInstancesResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecoveryInstanceTypeDef = TypedDict(
     "RecoveryInstanceTypeDef",
     {
         "arn": str,
         "dataReplicationInfo": RecoveryInstanceDataReplicationInfoTypeDef,
         "ec2InstanceID": str,
         "ec2InstanceState": EC2InstanceStateType,
         "failback": RecoveryInstanceFailbackTypeDef,
         "isDrill": bool,
         "jobID": str,
+        "originAvailabilityZone": str,
         "originEnvironment": OriginEnvironmentType,
         "pointInTimeSnapshotDateTime": str,
         "recoveryInstanceID": str,
         "recoveryInstanceProperties": RecoveryInstancePropertiesTypeDef,
         "sourceServerID": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+DescribeJobLogItemsResponseTypeDef = TypedDict(
+    "DescribeJobLogItemsResponseTypeDef",
+    {
+        "items": List[JobLogTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateExtendedSourceServerResponseTypeDef = TypedDict(
     "CreateExtendedSourceServerResponseTypeDef",
     {
         "sourceServer": SourceServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSourceServersResponseTypeDef = TypedDict(
     "DescribeSourceServersResponseTypeDef",
     {
         "items": List[SourceServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationResponseTypeDef = TypedDict(
     "StartReplicationResponseTypeDef",
     {
         "sourceServer": SourceServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopReplicationResponseTypeDef = TypedDict(
     "StopReplicationResponseTypeDef",
     {
         "sourceServer": SourceServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRecoveryInstancesResponseTypeDef = TypedDict(
     "DescribeRecoveryInstancesResponseTypeDef",
     {
         "items": List[RecoveryInstanceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs/type_defs.pyi` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs/type_defs.pyi`

 * *Files 22% similar despite different names*

```diff
@@ -8,14 +8,15 @@
     ```python
     from types_aiobotocore_drs.type_defs import AccountTypeDef
 
     data: AccountTypeDef = {...}
     ```
 """
 import sys
+from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
@@ -33,133 +34,168 @@
     LaunchDispositionType,
     LaunchStatusType,
     OriginEnvironmentType,
     PITPolicyRuleUnitsType,
     RecoveryInstanceDataReplicationInitiationStepNameType,
     RecoveryInstanceDataReplicationInitiationStepStatusType,
     RecoveryInstanceDataReplicationStateType,
+    RecoveryResultType,
     RecoverySnapshotsOrderType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
     ReplicationDirectionType,
+    ReplicationStatusType,
     TargetInstanceTypeRightSizingMethodType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccountTypeDef",
+    "AssociateSourceNetworkStackRequestRequestTypeDef",
     "CPUTypeDef",
     "ConversionPropertiesTypeDef",
     "CreateExtendedSourceServerRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "LicensingTypeDef",
     "PITPolicyRuleTypeDef",
+    "CreateSourceNetworkRequestRequestTypeDef",
+    "CreateSourceNetworkResponseTypeDef",
     "DataReplicationErrorTypeDef",
     "DataReplicationInfoReplicatedDiskTypeDef",
     "DataReplicationInitiationStepTypeDef",
     "DeleteJobRequestRequestTypeDef",
+    "DeleteLaunchConfigurationTemplateRequestRequestTypeDef",
     "DeleteRecoveryInstanceRequestRequestTypeDef",
     "DeleteReplicationConfigurationTemplateRequestRequestTypeDef",
+    "DeleteSourceNetworkRequestRequestTypeDef",
     "DeleteSourceServerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
     "DescribeJobLogItemsRequestRequestTypeDef",
     "DescribeJobsRequestFiltersTypeDef",
+    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
+    "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
     "DescribeRecoveryInstancesRequestFiltersTypeDef",
     "DescribeRecoverySnapshotsRequestFiltersTypeDef",
     "RecoverySnapshotTypeDef",
+    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
     "DescribeReplicationConfigurationTemplatesRequestRequestTypeDef",
+    "DescribeSourceNetworksRequestFiltersTypeDef",
     "DescribeSourceServersRequestFiltersTypeDef",
     "DisconnectRecoveryInstanceRequestRequestTypeDef",
     "DisconnectSourceServerRequestRequestTypeDef",
     "DiskTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "SourceNetworkDataTypeDef",
+    "ExportSourceNetworkCfnTemplateRequestRequestTypeDef",
+    "ExportSourceNetworkCfnTemplateResponseTypeDef",
     "GetFailbackReplicationConfigurationRequestRequestTypeDef",
+    "GetFailbackReplicationConfigurationResponseTypeDef",
     "GetLaunchConfigurationRequestRequestTypeDef",
     "GetReplicationConfigurationRequestRequestTypeDef",
     "IdentificationHintsTypeDef",
     "ParticipatingServerTypeDef",
-    "LicensingTypeDef",
     "LifeCycleLastLaunchInitiatedTypeDef",
+    "ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
     "ListExtensibleSourceServersRequestRequestTypeDef",
     "StagingSourceServerTypeDef",
+    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
     "ListStagingAccountsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NetworkInterfaceTypeDef",
     "OSTypeDef",
+    "PaginatorConfigTypeDef",
+    "ParticipatingResourceIDTypeDef",
     "RecoveryInstanceDataReplicationErrorTypeDef",
     "RecoveryInstanceDataReplicationInfoReplicatedDiskTypeDef",
     "RecoveryInstanceDataReplicationInitiationStepTypeDef",
     "RecoveryInstanceDiskTypeDef",
     "RecoveryInstanceFailbackTypeDef",
+    "RecoveryLifeCycleTypeDef",
     "ReplicationConfigurationReplicatedDiskTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryDataReplicationRequestRequestTypeDef",
     "ReverseReplicationRequestRequestTypeDef",
+    "ReverseReplicationResponseTypeDef",
     "SourceCloudPropertiesTypeDef",
     "StagingAreaTypeDef",
     "StartFailbackLaunchRequestRequestTypeDef",
     "StartRecoveryRequestSourceServerTypeDef",
     "StartReplicationRequestRequestTypeDef",
+    "StartSourceNetworkRecoveryRequestNetworkEntryTypeDef",
+    "StartSourceNetworkReplicationRequestRequestTypeDef",
     "StopFailbackRequestRequestTypeDef",
     "StopReplicationRequestRequestTypeDef",
+    "StopSourceNetworkReplicationRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TerminateRecoveryInstancesRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFailbackReplicationConfigurationRequestRequestTypeDef",
-    "JobLogEventDataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetFailbackReplicationConfigurationResponseTypeDef",
     "ListStagingAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ReverseReplicationResponseTypeDef",
+    "CreateLaunchConfigurationTemplateRequestRequestTypeDef",
+    "LaunchConfigurationTemplateTypeDef",
+    "LaunchConfigurationTypeDef",
+    "UpdateLaunchConfigurationRequestRequestTypeDef",
+    "UpdateLaunchConfigurationTemplateRequestRequestTypeDef",
     "CreateReplicationConfigurationTemplateRequestRequestTypeDef",
     "ReplicationConfigurationTemplateResponseMetadataTypeDef",
     "ReplicationConfigurationTemplateTypeDef",
     "UpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     "DataReplicationInitiationTypeDef",
-    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
-    "ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
-    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
     "DescribeJobsRequestDescribeJobsPaginateTypeDef",
     "DescribeJobsRequestRequestTypeDef",
     "DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef",
     "DescribeRecoveryInstancesRequestRequestTypeDef",
     "DescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef",
     "DescribeRecoverySnapshotsRequestRequestTypeDef",
     "DescribeRecoverySnapshotsResponseTypeDef",
+    "DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef",
+    "DescribeSourceNetworksRequestRequestTypeDef",
     "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     "DescribeSourceServersRequestRequestTypeDef",
-    "JobTypeDef",
-    "LaunchConfigurationTypeDef",
-    "UpdateLaunchConfigurationRequestRequestTypeDef",
+    "EventResourceDataTypeDef",
     "LifeCycleLastLaunchTypeDef",
     "ListExtensibleSourceServersResponseTypeDef",
     "SourcePropertiesTypeDef",
+    "ParticipatingResourceTypeDef",
     "RecoveryInstanceDataReplicationInitiationTypeDef",
     "RecoveryInstancePropertiesTypeDef",
+    "SourceNetworkTypeDef",
     "ReplicationConfigurationTypeDef",
     "UpdateReplicationConfigurationRequestRequestTypeDef",
     "StartRecoveryRequestRequestTypeDef",
-    "JobLogTypeDef",
+    "StartSourceNetworkRecoveryRequestRequestTypeDef",
+    "CreateLaunchConfigurationTemplateResponseTypeDef",
+    "DescribeLaunchConfigurationTemplatesResponseTypeDef",
+    "UpdateLaunchConfigurationTemplateResponseTypeDef",
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     "DataReplicationInfoTypeDef",
-    "DescribeJobsResponseTypeDef",
-    "StartFailbackLaunchResponseTypeDef",
-    "StartRecoveryResponseTypeDef",
-    "TerminateRecoveryInstancesResponseTypeDef",
+    "JobLogEventDataTypeDef",
     "LifeCycleTypeDef",
+    "JobTypeDef",
     "RecoveryInstanceDataReplicationInfoTypeDef",
-    "DescribeJobLogItemsResponseTypeDef",
+    "DescribeSourceNetworksResponseTypeDef",
+    "StartSourceNetworkReplicationResponseTypeDef",
+    "StopSourceNetworkReplicationResponseTypeDef",
+    "JobLogTypeDef",
     "SourceServerResponseMetadataTypeDef",
     "SourceServerTypeDef",
+    "AssociateSourceNetworkStackResponseTypeDef",
+    "DescribeJobsResponseTypeDef",
+    "StartFailbackLaunchResponseTypeDef",
+    "StartRecoveryResponseTypeDef",
+    "StartSourceNetworkRecoveryResponseTypeDef",
+    "TerminateRecoveryInstancesResponseTypeDef",
     "RecoveryInstanceTypeDef",
+    "DescribeJobLogItemsResponseTypeDef",
     "CreateExtendedSourceServerResponseTypeDef",
     "DescribeSourceServersResponseTypeDef",
     "StartReplicationResponseTypeDef",
     "StopReplicationResponseTypeDef",
     "DescribeRecoveryInstancesResponseTypeDef",
 )
 
@@ -167,14 +203,22 @@
     "AccountTypeDef",
     {
         "accountID": str,
     },
     total=False,
 )
 
+AssociateSourceNetworkStackRequestRequestTypeDef = TypedDict(
+    "AssociateSourceNetworkStackRequestRequestTypeDef",
+    {
+        "cfnStackName": str,
+        "sourceNetworkID": str,
+    },
+)
+
 CPUTypeDef = TypedDict(
     "CPUTypeDef",
     {
         "cores": int,
         "modelName": str,
     },
     total=False,
@@ -208,23 +252,20 @@
 
 class CreateExtendedSourceServerRequestRequestTypeDef(
     _RequiredCreateExtendedSourceServerRequestRequestTypeDef,
     _OptionalCreateExtendedSourceServerRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+LicensingTypeDef = TypedDict(
+    "LicensingTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "osByol": bool,
     },
+    total=False,
 )
 
 _RequiredPITPolicyRuleTypeDef = TypedDict(
     "_RequiredPITPolicyRuleTypeDef",
     {
         "interval": int,
         "retentionDuration": int,
@@ -239,14 +280,44 @@
     },
     total=False,
 )
 
 class PITPolicyRuleTypeDef(_RequiredPITPolicyRuleTypeDef, _OptionalPITPolicyRuleTypeDef):
     pass
 
+_RequiredCreateSourceNetworkRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateSourceNetworkRequestRequestTypeDef",
+    {
+        "originAccountID": str,
+        "originRegion": str,
+        "vpcID": str,
+    },
+)
+_OptionalCreateSourceNetworkRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateSourceNetworkRequestRequestTypeDef",
+    {
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+class CreateSourceNetworkRequestRequestTypeDef(
+    _RequiredCreateSourceNetworkRequestRequestTypeDef,
+    _OptionalCreateSourceNetworkRequestRequestTypeDef,
+):
+    pass
+
+CreateSourceNetworkResponseTypeDef = TypedDict(
+    "CreateSourceNetworkResponseTypeDef",
+    {
+        "sourceNetworkID": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataReplicationErrorTypeDef = TypedDict(
     "DataReplicationErrorTypeDef",
     {
         "error": DataReplicationErrorStringType,
         "rawError": str,
     },
     total=False,
@@ -276,45 +347,69 @@
 DeleteJobRequestRequestTypeDef = TypedDict(
     "DeleteJobRequestRequestTypeDef",
     {
         "jobID": str,
     },
 )
 
+DeleteLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "DeleteLaunchConfigurationTemplateRequestRequestTypeDef",
+    {
+        "launchConfigurationTemplateID": str,
+    },
+)
+
 DeleteRecoveryInstanceRequestRequestTypeDef = TypedDict(
     "DeleteRecoveryInstanceRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
 DeleteReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "DeleteReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "replicationConfigurationTemplateID": str,
     },
 )
 
+DeleteSourceNetworkRequestRequestTypeDef = TypedDict(
+    "DeleteSourceNetworkRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+
 DeleteSourceServerRequestRequestTypeDef = TypedDict(
     "DeleteSourceServerRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "jobID": str,
+    },
+)
+_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef(
+    _RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
+    _OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeJobLogItemsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeJobLogItemsRequestRequestTypeDef",
     {
         "jobID": str,
     },
 )
 _OptionalDescribeJobLogItemsRequestRequestTypeDef = TypedDict(
@@ -338,14 +433,33 @@
         "fromDate": str,
         "jobIDs": Sequence[str],
         "toDate": str,
     },
     total=False,
 )
 
+DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef = TypedDict(
+    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
+    {
+        "launchConfigurationTemplateIDs": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+DescribeLaunchConfigurationTemplatesRequestRequestTypeDef = TypedDict(
+    "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
+    {
+        "launchConfigurationTemplateIDs": Sequence[str],
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 DescribeRecoveryInstancesRequestFiltersTypeDef = TypedDict(
     "DescribeRecoveryInstancesRequestFiltersTypeDef",
     {
         "recoveryInstanceIDs": Sequence[str],
         "sourceServerIDs": Sequence[str],
     },
     total=False,
@@ -376,24 +490,43 @@
     },
     total=False,
 )
 
 class RecoverySnapshotTypeDef(_RequiredRecoverySnapshotTypeDef, _OptionalRecoverySnapshotTypeDef):
     pass
 
+DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef = TypedDict(
+    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
+    {
+        "replicationConfigurationTemplateIDs": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeReplicationConfigurationTemplatesRequestRequestTypeDef = TypedDict(
     "DescribeReplicationConfigurationTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "replicationConfigurationTemplateIDs": Sequence[str],
     },
     total=False,
 )
 
+DescribeSourceNetworksRequestFiltersTypeDef = TypedDict(
+    "DescribeSourceNetworksRequestFiltersTypeDef",
+    {
+        "originAccountID": str,
+        "originRegion": str,
+        "sourceNetworkIDs": Sequence[str],
+    },
+    total=False,
+)
+
 DescribeSourceServersRequestFiltersTypeDef = TypedDict(
     "DescribeSourceServersRequestFiltersTypeDef",
     {
         "hardwareId": str,
         "sourceServerIDs": Sequence[str],
         "stagingAccountIDs": Sequence[str],
     },
@@ -419,21 +552,65 @@
     {
         "bytes": int,
         "deviceName": str,
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
+SourceNetworkDataTypeDef = TypedDict(
+    "SourceNetworkDataTypeDef",
+    {
+        "sourceNetworkID": str,
+        "sourceVpc": str,
+        "stackName": str,
+        "targetVpc": str,
+    },
+    total=False,
+)
+
+ExportSourceNetworkCfnTemplateRequestRequestTypeDef = TypedDict(
+    "ExportSourceNetworkCfnTemplateRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+
+ExportSourceNetworkCfnTemplateResponseTypeDef = TypedDict(
+    "ExportSourceNetworkCfnTemplateResponseTypeDef",
+    {
+        "s3DestinationUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFailbackReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "GetFailbackReplicationConfigurationRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
+GetFailbackReplicationConfigurationResponseTypeDef = TypedDict(
+    "GetFailbackReplicationConfigurationResponseTypeDef",
+    {
+        "bandwidthThrottling": int,
+        "name": str,
+        "recoveryInstanceID": str,
+        "usePrivateIP": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "GetLaunchConfigurationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
@@ -461,32 +638,44 @@
         "launchStatus": LaunchStatusType,
         "recoveryInstanceID": str,
         "sourceServerID": str,
     },
     total=False,
 )
 
-LicensingTypeDef = TypedDict(
-    "LicensingTypeDef",
-    {
-        "osByol": bool,
-    },
-    total=False,
-)
-
 LifeCycleLastLaunchInitiatedTypeDef = TypedDict(
     "LifeCycleLastLaunchInitiatedTypeDef",
     {
         "apiCallDateTime": str,
         "jobID": str,
         "type": LastLaunchTypeType,
     },
     total=False,
 )
 
+_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
+    "_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
+    {
+        "stagingAccountID": str,
+    },
+)
+_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
+    "_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef(
+    _RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
+    _OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
+):
+    pass
+
 _RequiredListExtensibleSourceServersRequestRequestTypeDef = TypedDict(
     "_RequiredListExtensibleSourceServersRequestRequestTypeDef",
     {
         "stagingAccountID": str,
     },
 )
 _OptionalListExtensibleSourceServersRequestRequestTypeDef = TypedDict(
@@ -510,14 +699,22 @@
         "arn": str,
         "hostname": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+ListStagingAccountsRequestListStagingAccountsPaginateTypeDef = TypedDict(
+    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStagingAccountsRequestRequestTypeDef = TypedDict(
     "ListStagingAccountsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -526,14 +723,22 @@
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
 NetworkInterfaceTypeDef = TypedDict(
     "NetworkInterfaceTypeDef",
     {
         "ips": List[str],
         "isPrimary": bool,
         "macAddress": str,
     },
@@ -544,14 +749,32 @@
     "OSTypeDef",
     {
         "fullString": str,
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
+ParticipatingResourceIDTypeDef = TypedDict(
+    "ParticipatingResourceIDTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+    total=False,
+)
+
 RecoveryInstanceDataReplicationErrorTypeDef = TypedDict(
     "RecoveryInstanceDataReplicationErrorTypeDef",
     {
         "error": FailbackReplicationErrorType,
         "rawError": str,
     },
     total=False,
@@ -601,41 +824,70 @@
         "failbackToOriginalServer": bool,
         "firstByteDateTime": str,
         "state": FailbackStateType,
     },
     total=False,
 )
 
+RecoveryLifeCycleTypeDef = TypedDict(
+    "RecoveryLifeCycleTypeDef",
+    {
+        "apiCallDateTime": datetime,
+        "jobID": str,
+        "lastRecoveryResult": RecoveryResultType,
+    },
+    total=False,
+)
+
 ReplicationConfigurationReplicatedDiskTypeDef = TypedDict(
     "ReplicationConfigurationReplicatedDiskTypeDef",
     {
         "deviceName": str,
         "iops": int,
         "isBootDisk": bool,
         "optimizedStagingDiskType": ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
         "stagingDiskType": ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
         "throughput": int,
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
 RetryDataReplicationRequestRequestTypeDef = TypedDict(
     "RetryDataReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
 ReverseReplicationRequestRequestTypeDef = TypedDict(
     "ReverseReplicationRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
+ReverseReplicationResponseTypeDef = TypedDict(
+    "ReverseReplicationResponseTypeDef",
+    {
+        "reversedDirectionSourceServerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SourceCloudPropertiesTypeDef = TypedDict(
     "SourceCloudPropertiesTypeDef",
     {
         "originAccountID": str,
         "originAvailabilityZone": str,
         "originRegion": str,
     },
@@ -696,28 +948,62 @@
 StartReplicationRequestRequestTypeDef = TypedDict(
     "StartReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
+_RequiredStartSourceNetworkRecoveryRequestNetworkEntryTypeDef = TypedDict(
+    "_RequiredStartSourceNetworkRecoveryRequestNetworkEntryTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+_OptionalStartSourceNetworkRecoveryRequestNetworkEntryTypeDef = TypedDict(
+    "_OptionalStartSourceNetworkRecoveryRequestNetworkEntryTypeDef",
+    {
+        "cfnStackName": str,
+    },
+    total=False,
+)
+
+class StartSourceNetworkRecoveryRequestNetworkEntryTypeDef(
+    _RequiredStartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+    _OptionalStartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+):
+    pass
+
+StartSourceNetworkReplicationRequestRequestTypeDef = TypedDict(
+    "StartSourceNetworkReplicationRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
+    },
+)
+
 StopFailbackRequestRequestTypeDef = TypedDict(
     "StopFailbackRequestRequestTypeDef",
     {
         "recoveryInstanceID": str,
     },
 )
 
 StopReplicationRequestRequestTypeDef = TypedDict(
     "StopReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
+StopSourceNetworkReplicationRequestRequestTypeDef = TypedDict(
+    "StopSourceNetworkReplicationRequestRequestTypeDef",
+    {
+        "sourceNetworkID": str,
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
@@ -755,68 +1041,117 @@
 
 class UpdateFailbackReplicationConfigurationRequestRequestTypeDef(
     _RequiredUpdateFailbackReplicationConfigurationRequestRequestTypeDef,
     _OptionalUpdateFailbackReplicationConfigurationRequestRequestTypeDef,
 ):
     pass
 
-JobLogEventDataTypeDef = TypedDict(
-    "JobLogEventDataTypeDef",
+ListStagingAccountsResponseTypeDef = TypedDict(
+    "ListStagingAccountsResponseTypeDef",
     {
-        "conversionProperties": ConversionPropertiesTypeDef,
-        "conversionServerID": str,
-        "rawError": str,
-        "sourceServerID": str,
-        "targetInstanceID": str,
+        "accounts": List[AccountTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "CreateLaunchConfigurationTemplateRequestRequestTypeDef",
+    {
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "exportBucketArn": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "tags": Mapping[str, str],
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+LaunchConfigurationTemplateTypeDef = TypedDict(
+    "LaunchConfigurationTemplateTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "arn": str,
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "exportBucketArn": str,
+        "launchConfigurationTemplateID": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "tags": Dict[str, str],
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
+    total=False,
 )
 
-GetFailbackReplicationConfigurationResponseTypeDef = TypedDict(
-    "GetFailbackReplicationConfigurationResponseTypeDef",
+LaunchConfigurationTypeDef = TypedDict(
+    "LaunchConfigurationTypeDef",
     {
-        "bandwidthThrottling": int,
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "ec2LaunchTemplateID": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
         "name": str,
-        "recoveryInstanceID": str,
-        "usePrivateIP": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sourceServerID": str,
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListStagingAccountsResponseTypeDef = TypedDict(
-    "ListStagingAccountsResponseTypeDef",
+_RequiredUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateLaunchConfigurationRequestRequestTypeDef",
     {
-        "accounts": List[AccountTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sourceServerID": str,
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_OptionalUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateLaunchConfigurationRequestRequestTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "name": str,
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
+    total=False,
 )
 
-ReverseReplicationResponseTypeDef = TypedDict(
-    "ReverseReplicationResponseTypeDef",
+class UpdateLaunchConfigurationRequestRequestTypeDef(
+    _RequiredUpdateLaunchConfigurationRequestRequestTypeDef,
+    _OptionalUpdateLaunchConfigurationRequestRequestTypeDef,
+):
+    pass
+
+_RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef",
     {
-        "reversedDirectionSourceServerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "launchConfigurationTemplateID": str,
     },
 )
+_OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef",
+    {
+        "copyPrivateIp": bool,
+        "copyTags": bool,
+        "exportBucketArn": str,
+        "launchDisposition": LaunchDispositionType,
+        "licensing": LicensingTypeDef,
+        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
+    },
+    total=False,
+)
+
+class UpdateLaunchConfigurationTemplateRequestRequestTypeDef(
+    _RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
+    _OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
+):
+    pass
 
 _RequiredCreateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "associateDefaultSecurityGroup": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
@@ -830,14 +1165,15 @@
         "stagingAreaTags": Mapping[str, str],
         "useDedicatedReplicationServer": bool,
     },
 )
 _OptionalCreateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalCreateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
+        "autoReplicateNewDisks": bool,
         "ebsEncryptionKeyArn": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateReplicationConfigurationTemplateRequestRequestTypeDef(
@@ -847,43 +1183,45 @@
     pass
 
 ReplicationConfigurationTemplateResponseMetadataTypeDef = TypedDict(
     "ReplicationConfigurationTemplateResponseMetadataTypeDef",
     {
         "arn": str,
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "pitPolicy": List[PITPolicyRuleTypeDef],
         "replicationConfigurationTemplateID": str,
         "replicationServerInstanceType": str,
         "replicationServersSecurityGroupsIDs": List[str],
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Dict[str, str],
         "tags": Dict[str, str],
         "useDedicatedReplicationServer": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredReplicationConfigurationTemplateTypeDef = TypedDict(
     "_RequiredReplicationConfigurationTemplateTypeDef",
     {
         "replicationConfigurationTemplateID": str,
     },
 )
 _OptionalReplicationConfigurationTemplateTypeDef = TypedDict(
     "_OptionalReplicationConfigurationTemplateTypeDef",
     {
         "arn": str,
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "pitPolicy": List[PITPolicyRuleTypeDef],
@@ -910,14 +1248,15 @@
     },
 )
 _OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "arn": str,
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "pitPolicy": Sequence[PITPolicyRuleTypeDef],
@@ -942,76 +1281,19 @@
         "nextAttemptDateTime": str,
         "startDateTime": str,
         "steps": List[DataReplicationInitiationStepTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    {
-        "jobID": str,
-    },
-)
-_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef(
-    _RequiredDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    _OptionalDescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-):
-    pass
-
-DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef = TypedDict(
-    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
-    {
-        "replicationConfigurationTemplateIDs": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
-    "_RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
-    {
-        "stagingAccountID": str,
-    },
-)
-_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef = TypedDict(
-    "_OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef(
-    _RequiredListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
-    _OptionalListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
-):
-    pass
-
-ListStagingAccountsRequestListStagingAccountsPaginateTypeDef = TypedDict(
-    "ListStagingAccountsRequestListStagingAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeJobsRequestDescribeJobsPaginateTypeDef = TypedDict(
     "DescribeJobsRequestDescribeJobsPaginateTypeDef",
     {
         "filters": DescribeJobsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeJobsRequestRequestTypeDef = TypedDict(
     "DescribeJobsRequestRequestTypeDef",
     {
@@ -1022,15 +1304,15 @@
     total=False,
 )
 
 DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef = TypedDict(
     "DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef",
     {
         "filters": DescribeRecoveryInstancesRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeRecoveryInstancesRequestRequestTypeDef = TypedDict(
     "DescribeRecoveryInstancesRequestRequestTypeDef",
     {
@@ -1048,15 +1330,15 @@
     },
 )
 _OptionalDescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef = TypedDict(
     "_OptionalDescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef",
     {
         "filters": DescribeRecoverySnapshotsRequestFiltersTypeDef,
         "order": RecoverySnapshotsOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef(
     _RequiredDescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef,
     _OptionalDescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef,
@@ -1087,129 +1369,103 @@
     pass
 
 DescribeRecoverySnapshotsResponseTypeDef = TypedDict(
     "DescribeRecoverySnapshotsResponseTypeDef",
     {
         "items": List[RecoverySnapshotTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef = TypedDict(
-    "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
+DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef = TypedDict(
+    "DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef",
     {
-        "filters": DescribeSourceServersRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filters": DescribeSourceNetworksRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeSourceServersRequestRequestTypeDef = TypedDict(
-    "DescribeSourceServersRequestRequestTypeDef",
+DescribeSourceNetworksRequestRequestTypeDef = TypedDict(
+    "DescribeSourceNetworksRequestRequestTypeDef",
     {
-        "filters": DescribeSourceServersRequestFiltersTypeDef,
+        "filters": DescribeSourceNetworksRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-_RequiredJobTypeDef = TypedDict(
-    "_RequiredJobTypeDef",
-    {
-        "jobID": str,
-    },
-)
-_OptionalJobTypeDef = TypedDict(
-    "_OptionalJobTypeDef",
+DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef = TypedDict(
+    "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     {
-        "arn": str,
-        "creationDateTime": str,
-        "endDateTime": str,
-        "initiatedBy": InitiatedByType,
-        "participatingServers": List[ParticipatingServerTypeDef],
-        "status": JobStatusType,
-        "tags": Dict[str, str],
-        "type": JobTypeType,
+        "filters": DescribeSourceServersRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
-    pass
-
-LaunchConfigurationTypeDef = TypedDict(
-    "LaunchConfigurationTypeDef",
+DescribeSourceServersRequestRequestTypeDef = TypedDict(
+    "DescribeSourceServersRequestRequestTypeDef",
     {
-        "copyPrivateIp": bool,
-        "copyTags": bool,
-        "ec2LaunchTemplateID": str,
-        "launchDisposition": LaunchDispositionType,
-        "licensing": LicensingTypeDef,
-        "name": str,
-        "sourceServerID": str,
-        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "filters": DescribeSourceServersRequestFiltersTypeDef,
+        "maxResults": int,
+        "nextToken": str,
     },
+    total=False,
 )
 
-_RequiredUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateLaunchConfigurationRequestRequestTypeDef",
+EventResourceDataTypeDef = TypedDict(
+    "EventResourceDataTypeDef",
     {
-        "sourceServerID": str,
-    },
-)
-_OptionalUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateLaunchConfigurationRequestRequestTypeDef",
-    {
-        "copyPrivateIp": bool,
-        "copyTags": bool,
-        "launchDisposition": LaunchDispositionType,
-        "licensing": LicensingTypeDef,
-        "name": str,
-        "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
+        "sourceNetworkData": SourceNetworkDataTypeDef,
     },
     total=False,
 )
 
-class UpdateLaunchConfigurationRequestRequestTypeDef(
-    _RequiredUpdateLaunchConfigurationRequestRequestTypeDef,
-    _OptionalUpdateLaunchConfigurationRequestRequestTypeDef,
-):
-    pass
-
 LifeCycleLastLaunchTypeDef = TypedDict(
     "LifeCycleLastLaunchTypeDef",
     {
         "initiated": LifeCycleLastLaunchInitiatedTypeDef,
+        "status": LaunchStatusType,
     },
     total=False,
 )
 
 ListExtensibleSourceServersResponseTypeDef = TypedDict(
     "ListExtensibleSourceServersResponseTypeDef",
     {
         "items": List[StagingSourceServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourcePropertiesTypeDef = TypedDict(
     "SourcePropertiesTypeDef",
     {
         "cpus": List[CPUTypeDef],
         "disks": List[DiskTypeDef],
         "identificationHints": IdentificationHintsTypeDef,
         "lastUpdatedDateTime": str,
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "os": OSTypeDef,
         "ramBytes": int,
         "recommendedInstanceType": str,
+        "supportsNitroInstances": bool,
+    },
+    total=False,
+)
+
+ParticipatingResourceTypeDef = TypedDict(
+    "ParticipatingResourceTypeDef",
+    {
+        "launchStatus": LaunchStatusType,
+        "participatingResourceID": ParticipatingResourceIDTypeDef,
     },
     total=False,
 )
 
 RecoveryInstanceDataReplicationInitiationTypeDef = TypedDict(
     "RecoveryInstanceDataReplicationInitiationTypeDef",
     {
@@ -1229,18 +1485,37 @@
         "networkInterfaces": List[NetworkInterfaceTypeDef],
         "os": OSTypeDef,
         "ramBytes": int,
     },
     total=False,
 )
 
+SourceNetworkTypeDef = TypedDict(
+    "SourceNetworkTypeDef",
+    {
+        "arn": str,
+        "cfnStackName": str,
+        "lastRecovery": RecoveryLifeCycleTypeDef,
+        "launchedVpcID": str,
+        "replicationStatus": ReplicationStatusType,
+        "replicationStatusDetails": str,
+        "sourceAccountID": str,
+        "sourceNetworkID": str,
+        "sourceRegion": str,
+        "sourceVpcID": str,
+        "tags": Dict[str, str],
+    },
+    total=False,
+)
+
 ReplicationConfigurationTypeDef = TypedDict(
     "ReplicationConfigurationTypeDef",
     {
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "name": str,
@@ -1248,28 +1523,29 @@
         "replicatedDisks": List[ReplicationConfigurationReplicatedDiskTypeDef],
         "replicationServerInstanceType": str,
         "replicationServersSecurityGroupsIDs": List[str],
         "sourceServerID": str,
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Dict[str, str],
         "useDedicatedReplicationServer": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateReplicationConfigurationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 _OptionalUpdateReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateReplicationConfigurationRequestRequestTypeDef",
     {
         "associateDefaultSecurityGroup": bool,
+        "autoReplicateNewDisks": bool,
         "bandwidthThrottling": int,
         "createPublicIP": bool,
         "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
         "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
         "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
         "ebsEncryptionKeyArn": str,
         "name": str,
@@ -1306,205 +1582,335 @@
 )
 
 class StartRecoveryRequestRequestTypeDef(
     _RequiredStartRecoveryRequestRequestTypeDef, _OptionalStartRecoveryRequestRequestTypeDef
 ):
     pass
 
-JobLogTypeDef = TypedDict(
-    "JobLogTypeDef",
+_RequiredStartSourceNetworkRecoveryRequestRequestTypeDef = TypedDict(
+    "_RequiredStartSourceNetworkRecoveryRequestRequestTypeDef",
     {
-        "event": JobLogEventType,
-        "eventData": JobLogEventDataTypeDef,
-        "logDateTime": str,
+        "sourceNetworks": Sequence[StartSourceNetworkRecoveryRequestNetworkEntryTypeDef],
+    },
+)
+_OptionalStartSourceNetworkRecoveryRequestRequestTypeDef = TypedDict(
+    "_OptionalStartSourceNetworkRecoveryRequestRequestTypeDef",
+    {
+        "deployAsNew": bool,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
+class StartSourceNetworkRecoveryRequestRequestTypeDef(
+    _RequiredStartSourceNetworkRecoveryRequestRequestTypeDef,
+    _OptionalStartSourceNetworkRecoveryRequestRequestTypeDef,
+):
+    pass
+
+CreateLaunchConfigurationTemplateResponseTypeDef = TypedDict(
+    "CreateLaunchConfigurationTemplateResponseTypeDef",
+    {
+        "launchConfigurationTemplate": LaunchConfigurationTemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeLaunchConfigurationTemplatesResponseTypeDef = TypedDict(
+    "DescribeLaunchConfigurationTemplatesResponseTypeDef",
+    {
+        "items": List[LaunchConfigurationTemplateTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateLaunchConfigurationTemplateResponseTypeDef = TypedDict(
+    "UpdateLaunchConfigurationTemplateResponseTypeDef",
+    {
+        "launchConfigurationTemplate": LaunchConfigurationTemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeReplicationConfigurationTemplatesResponseTypeDef = TypedDict(
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     {
         "items": List[ReplicationConfigurationTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataReplicationInfoTypeDef = TypedDict(
     "DataReplicationInfoTypeDef",
     {
         "dataReplicationError": DataReplicationErrorTypeDef,
         "dataReplicationInitiation": DataReplicationInitiationTypeDef,
         "dataReplicationState": DataReplicationStateType,
         "etaDateTime": str,
         "lagDuration": str,
         "replicatedDisks": List[DataReplicationInfoReplicatedDiskTypeDef],
+        "stagingAvailabilityZone": str,
     },
     total=False,
 )
 
-DescribeJobsResponseTypeDef = TypedDict(
-    "DescribeJobsResponseTypeDef",
-    {
-        "items": List[JobTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartFailbackLaunchResponseTypeDef = TypedDict(
-    "StartFailbackLaunchResponseTypeDef",
-    {
-        "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRecoveryResponseTypeDef = TypedDict(
-    "StartRecoveryResponseTypeDef",
-    {
-        "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateRecoveryInstancesResponseTypeDef = TypedDict(
-    "TerminateRecoveryInstancesResponseTypeDef",
+JobLogEventDataTypeDef = TypedDict(
+    "JobLogEventDataTypeDef",
     {
-        "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "conversionProperties": ConversionPropertiesTypeDef,
+        "conversionServerID": str,
+        "eventResourceData": EventResourceDataTypeDef,
+        "rawError": str,
+        "sourceServerID": str,
+        "targetInstanceID": str,
     },
+    total=False,
 )
 
 LifeCycleTypeDef = TypedDict(
     "LifeCycleTypeDef",
     {
         "addedToServiceDateTime": str,
         "elapsedReplicationDuration": str,
         "firstByteDateTime": str,
         "lastLaunch": LifeCycleLastLaunchTypeDef,
         "lastSeenByServiceDateTime": str,
     },
     total=False,
 )
 
+_RequiredJobTypeDef = TypedDict(
+    "_RequiredJobTypeDef",
+    {
+        "jobID": str,
+    },
+)
+_OptionalJobTypeDef = TypedDict(
+    "_OptionalJobTypeDef",
+    {
+        "arn": str,
+        "creationDateTime": str,
+        "endDateTime": str,
+        "initiatedBy": InitiatedByType,
+        "participatingResources": List[ParticipatingResourceTypeDef],
+        "participatingServers": List[ParticipatingServerTypeDef],
+        "status": JobStatusType,
+        "tags": Dict[str, str],
+        "type": JobTypeType,
+    },
+    total=False,
+)
+
+class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
+    pass
+
 RecoveryInstanceDataReplicationInfoTypeDef = TypedDict(
     "RecoveryInstanceDataReplicationInfoTypeDef",
     {
         "dataReplicationError": RecoveryInstanceDataReplicationErrorTypeDef,
         "dataReplicationInitiation": RecoveryInstanceDataReplicationInitiationTypeDef,
         "dataReplicationState": RecoveryInstanceDataReplicationStateType,
         "etaDateTime": str,
         "lagDuration": str,
         "replicatedDisks": List[RecoveryInstanceDataReplicationInfoReplicatedDiskTypeDef],
+        "stagingAvailabilityZone": str,
     },
     total=False,
 )
 
-DescribeJobLogItemsResponseTypeDef = TypedDict(
-    "DescribeJobLogItemsResponseTypeDef",
+DescribeSourceNetworksResponseTypeDef = TypedDict(
+    "DescribeSourceNetworksResponseTypeDef",
     {
-        "items": List[JobLogTypeDef],
+        "items": List[SourceNetworkTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSourceNetworkReplicationResponseTypeDef = TypedDict(
+    "StartSourceNetworkReplicationResponseTypeDef",
+    {
+        "sourceNetwork": SourceNetworkTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StopSourceNetworkReplicationResponseTypeDef = TypedDict(
+    "StopSourceNetworkReplicationResponseTypeDef",
+    {
+        "sourceNetwork": SourceNetworkTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+JobLogTypeDef = TypedDict(
+    "JobLogTypeDef",
+    {
+        "event": JobLogEventType,
+        "eventData": JobLogEventDataTypeDef,
+        "logDateTime": str,
+    },
+    total=False,
+)
+
 SourceServerResponseMetadataTypeDef = TypedDict(
     "SourceServerResponseMetadataTypeDef",
     {
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
         "lastLaunchResult": LastLaunchResultType,
         "lifeCycle": LifeCycleTypeDef,
         "recoveryInstanceId": str,
         "replicationDirection": ReplicationDirectionType,
         "reversedDirectionSourceServerArn": str,
         "sourceCloudProperties": SourceCloudPropertiesTypeDef,
+        "sourceNetworkID": str,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "stagingArea": StagingAreaTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerTypeDef = TypedDict(
     "SourceServerTypeDef",
     {
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
         "lastLaunchResult": LastLaunchResultType,
         "lifeCycle": LifeCycleTypeDef,
         "recoveryInstanceId": str,
         "replicationDirection": ReplicationDirectionType,
         "reversedDirectionSourceServerArn": str,
         "sourceCloudProperties": SourceCloudPropertiesTypeDef,
+        "sourceNetworkID": str,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "stagingArea": StagingAreaTypeDef,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+AssociateSourceNetworkStackResponseTypeDef = TypedDict(
+    "AssociateSourceNetworkStackResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeJobsResponseTypeDef = TypedDict(
+    "DescribeJobsResponseTypeDef",
+    {
+        "items": List[JobTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartFailbackLaunchResponseTypeDef = TypedDict(
+    "StartFailbackLaunchResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartRecoveryResponseTypeDef = TypedDict(
+    "StartRecoveryResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSourceNetworkRecoveryResponseTypeDef = TypedDict(
+    "StartSourceNetworkRecoveryResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TerminateRecoveryInstancesResponseTypeDef = TypedDict(
+    "TerminateRecoveryInstancesResponseTypeDef",
+    {
+        "job": JobTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecoveryInstanceTypeDef = TypedDict(
     "RecoveryInstanceTypeDef",
     {
         "arn": str,
         "dataReplicationInfo": RecoveryInstanceDataReplicationInfoTypeDef,
         "ec2InstanceID": str,
         "ec2InstanceState": EC2InstanceStateType,
         "failback": RecoveryInstanceFailbackTypeDef,
         "isDrill": bool,
         "jobID": str,
+        "originAvailabilityZone": str,
         "originEnvironment": OriginEnvironmentType,
         "pointInTimeSnapshotDateTime": str,
         "recoveryInstanceID": str,
         "recoveryInstanceProperties": RecoveryInstancePropertiesTypeDef,
         "sourceServerID": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+DescribeJobLogItemsResponseTypeDef = TypedDict(
+    "DescribeJobLogItemsResponseTypeDef",
+    {
+        "items": List[JobLogTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateExtendedSourceServerResponseTypeDef = TypedDict(
     "CreateExtendedSourceServerResponseTypeDef",
     {
         "sourceServer": SourceServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSourceServersResponseTypeDef = TypedDict(
     "DescribeSourceServersResponseTypeDef",
     {
         "items": List[SourceServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartReplicationResponseTypeDef = TypedDict(
     "StartReplicationResponseTypeDef",
     {
         "sourceServer": SourceServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopReplicationResponseTypeDef = TypedDict(
     "StopReplicationResponseTypeDef",
     {
         "sourceServer": SourceServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRecoveryInstancesResponseTypeDef = TypedDict(
     "DescribeRecoveryInstancesResponseTypeDef",
     {
         "items": List[RecoveryInstanceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/PKG-INFO` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-drs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.drs 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.drs 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-drs"></a>
 
 # types-aiobotocore-drs
 
 [![PyPI - types-aiobotocore-drs](https://img.shields.io/pypi/v/types-aiobotocore-drs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-drs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-drs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-drs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-drs?color=blue)](https://pypistats.org/packages/types-aiobotocore-drs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.drs 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs)
+[aiobotocore.drs 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/drs.html#drs)
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
 [types-aiobotocore-drs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_drs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,17 +273,19 @@
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_drs import drsClient
 from types_aiobotocore_drs.paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
+    DescribeLaunchConfigurationTemplatesPaginator,
     DescribeRecoveryInstancesPaginator,
     DescribeRecoverySnapshotsPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
+    DescribeSourceNetworksPaginator,
     DescribeSourceServersPaginator,
     ListExtensibleSourceServersPaginator,
     ListStagingAccountsPaginator,
 )
 
 session = get_session()
 async with session.create_client("drs") as client:
@@ -291,23 +293,29 @@
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator(
         "describe_job_log_items"
     )
     describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
+    describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator(
+        "describe_launch_configuration_templates"
+    )
     describe_recovery_instances_paginator: DescribeRecoveryInstancesPaginator = (
         client.get_paginator("describe_recovery_instances")
     )
     describe_recovery_snapshots_paginator: DescribeRecoverySnapshotsPaginator = (
         client.get_paginator("describe_recovery_snapshots")
     )
     describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator(
         "describe_replication_configuration_templates"
     )
+    describe_source_networks_paginator: DescribeSourceNetworksPaginator = client.get_paginator(
+        "describe_source_networks"
+    )
     describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator(
         "describe_source_servers"
     )
     list_extensible_source_servers_paginator: ListExtensibleSourceServersPaginator = (
         client.get_paginator("list_extensible_source_servers")
     )
     list_staging_accounts_paginator: ListStagingAccountsPaginator = client.get_paginator(
@@ -326,17 +334,19 @@
 from types_aiobotocore_drs.literals import (
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
     DescribeJobLogItemsPaginatorName,
     DescribeJobsPaginatorName,
+    DescribeLaunchConfigurationTemplatesPaginatorName,
     DescribeRecoveryInstancesPaginatorName,
     DescribeRecoverySnapshotsPaginatorName,
     DescribeReplicationConfigurationTemplatesPaginatorName,
+    DescribeSourceNetworksPaginatorName,
     DescribeSourceServersPaginatorName,
     EC2InstanceStateType,
     ExtensionStatusType,
     FailbackLaunchTypeType,
     FailbackReplicationErrorType,
     FailbackStateType,
     InitiatedByType,
@@ -350,20 +360,22 @@
     ListExtensibleSourceServersPaginatorName,
     ListStagingAccountsPaginatorName,
     OriginEnvironmentType,
     PITPolicyRuleUnitsType,
     RecoveryInstanceDataReplicationInitiationStepNameType,
     RecoveryInstanceDataReplicationInitiationStepStatusType,
     RecoveryInstanceDataReplicationStateType,
+    RecoveryResultType,
     RecoverySnapshotsOrderType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
     ReplicationDirectionType,
+    ReplicationStatusType,
     TargetInstanceTypeRightSizingMethodType,
     drsServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -379,117 +391,150 @@
 
 `types_aiobotocore_drs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_drs.type_defs import (
     AccountTypeDef,
+    AssociateSourceNetworkStackRequestRequestTypeDef,
     CPUTypeDef,
     ConversionPropertiesTypeDef,
     CreateExtendedSourceServerRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    LicensingTypeDef,
     PITPolicyRuleTypeDef,
+    CreateSourceNetworkRequestRequestTypeDef,
+    CreateSourceNetworkResponseTypeDef,
     DataReplicationErrorTypeDef,
     DataReplicationInfoReplicatedDiskTypeDef,
     DataReplicationInitiationStepTypeDef,
     DeleteJobRequestRequestTypeDef,
+    DeleteLaunchConfigurationTemplateRequestRequestTypeDef,
     DeleteRecoveryInstanceRequestRequestTypeDef,
     DeleteReplicationConfigurationTemplateRequestRequestTypeDef,
+    DeleteSourceNetworkRequestRequestTypeDef,
     DeleteSourceServerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
     DescribeJobLogItemsRequestRequestTypeDef,
     DescribeJobsRequestFiltersTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestRequestTypeDef,
     DescribeRecoveryInstancesRequestFiltersTypeDef,
     DescribeRecoverySnapshotsRequestFiltersTypeDef,
     RecoverySnapshotTypeDef,
+    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
     DescribeReplicationConfigurationTemplatesRequestRequestTypeDef,
+    DescribeSourceNetworksRequestFiltersTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DisconnectRecoveryInstanceRequestRequestTypeDef,
     DisconnectSourceServerRequestRequestTypeDef,
     DiskTypeDef,
+    EmptyResponseMetadataTypeDef,
+    SourceNetworkDataTypeDef,
+    ExportSourceNetworkCfnTemplateRequestRequestTypeDef,
+    ExportSourceNetworkCfnTemplateResponseTypeDef,
     GetFailbackReplicationConfigurationRequestRequestTypeDef,
+    GetFailbackReplicationConfigurationResponseTypeDef,
     GetLaunchConfigurationRequestRequestTypeDef,
     GetReplicationConfigurationRequestRequestTypeDef,
     IdentificationHintsTypeDef,
     ParticipatingServerTypeDef,
-    LicensingTypeDef,
     LifeCycleLastLaunchInitiatedTypeDef,
+    ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
     ListExtensibleSourceServersRequestRequestTypeDef,
     StagingSourceServerTypeDef,
+    ListStagingAccountsRequestListStagingAccountsPaginateTypeDef,
     ListStagingAccountsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NetworkInterfaceTypeDef,
     OSTypeDef,
+    PaginatorConfigTypeDef,
+    ParticipatingResourceIDTypeDef,
     RecoveryInstanceDataReplicationErrorTypeDef,
     RecoveryInstanceDataReplicationInfoReplicatedDiskTypeDef,
     RecoveryInstanceDataReplicationInitiationStepTypeDef,
     RecoveryInstanceDiskTypeDef,
     RecoveryInstanceFailbackTypeDef,
+    RecoveryLifeCycleTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
+    ResponseMetadataTypeDef,
     RetryDataReplicationRequestRequestTypeDef,
     ReverseReplicationRequestRequestTypeDef,
+    ReverseReplicationResponseTypeDef,
     SourceCloudPropertiesTypeDef,
     StagingAreaTypeDef,
     StartFailbackLaunchRequestRequestTypeDef,
     StartRecoveryRequestSourceServerTypeDef,
     StartReplicationRequestRequestTypeDef,
+    StartSourceNetworkRecoveryRequestNetworkEntryTypeDef,
+    StartSourceNetworkReplicationRequestRequestTypeDef,
     StopFailbackRequestRequestTypeDef,
     StopReplicationRequestRequestTypeDef,
+    StopSourceNetworkReplicationRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateRecoveryInstancesRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFailbackReplicationConfigurationRequestRequestTypeDef,
-    JobLogEventDataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetFailbackReplicationConfigurationResponseTypeDef,
     ListStagingAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ReverseReplicationResponseTypeDef,
+    CreateLaunchConfigurationTemplateRequestRequestTypeDef,
+    LaunchConfigurationTemplateTypeDef,
+    LaunchConfigurationTypeDef,
+    UpdateLaunchConfigurationRequestRequestTypeDef,
+    UpdateLaunchConfigurationTemplateRequestRequestTypeDef,
     CreateReplicationConfigurationTemplateRequestRequestTypeDef,
     ReplicationConfigurationTemplateResponseMetadataTypeDef,
     ReplicationConfigurationTemplateTypeDef,
     UpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     DataReplicationInitiationTypeDef,
-    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
-    ListExtensibleSourceServersRequestListExtensibleSourceServersPaginateTypeDef,
-    ListStagingAccountsRequestListStagingAccountsPaginateTypeDef,
     DescribeJobsRequestDescribeJobsPaginateTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeRecoveryInstancesRequestDescribeRecoveryInstancesPaginateTypeDef,
     DescribeRecoveryInstancesRequestRequestTypeDef,
     DescribeRecoverySnapshotsRequestDescribeRecoverySnapshotsPaginateTypeDef,
     DescribeRecoverySnapshotsRequestRequestTypeDef,
     DescribeRecoverySnapshotsResponseTypeDef,
+    DescribeSourceNetworksRequestDescribeSourceNetworksPaginateTypeDef,
+    DescribeSourceNetworksRequestRequestTypeDef,
     DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef,
     DescribeSourceServersRequestRequestTypeDef,
-    JobTypeDef,
-    LaunchConfigurationTypeDef,
-    UpdateLaunchConfigurationRequestRequestTypeDef,
+    EventResourceDataTypeDef,
     LifeCycleLastLaunchTypeDef,
     ListExtensibleSourceServersResponseTypeDef,
     SourcePropertiesTypeDef,
+    ParticipatingResourceTypeDef,
     RecoveryInstanceDataReplicationInitiationTypeDef,
     RecoveryInstancePropertiesTypeDef,
+    SourceNetworkTypeDef,
     ReplicationConfigurationTypeDef,
     UpdateReplicationConfigurationRequestRequestTypeDef,
     StartRecoveryRequestRequestTypeDef,
-    JobLogTypeDef,
+    StartSourceNetworkRecoveryRequestRequestTypeDef,
+    CreateLaunchConfigurationTemplateResponseTypeDef,
+    DescribeLaunchConfigurationTemplatesResponseTypeDef,
+    UpdateLaunchConfigurationTemplateResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DataReplicationInfoTypeDef,
-    DescribeJobsResponseTypeDef,
-    StartFailbackLaunchResponseTypeDef,
-    StartRecoveryResponseTypeDef,
-    TerminateRecoveryInstancesResponseTypeDef,
+    JobLogEventDataTypeDef,
     LifeCycleTypeDef,
+    JobTypeDef,
     RecoveryInstanceDataReplicationInfoTypeDef,
-    DescribeJobLogItemsResponseTypeDef,
+    DescribeSourceNetworksResponseTypeDef,
+    StartSourceNetworkReplicationResponseTypeDef,
+    StopSourceNetworkReplicationResponseTypeDef,
+    JobLogTypeDef,
     SourceServerResponseMetadataTypeDef,
     SourceServerTypeDef,
+    AssociateSourceNetworkStackResponseTypeDef,
+    DescribeJobsResponseTypeDef,
+    StartFailbackLaunchResponseTypeDef,
+    StartRecoveryResponseTypeDef,
+    StartSourceNetworkRecoveryResponseTypeDef,
+    TerminateRecoveryInstancesResponseTypeDef,
     RecoveryInstanceTypeDef,
+    DescribeJobLogItemsResponseTypeDef,
     CreateExtendedSourceServerResponseTypeDef,
     DescribeSourceServersResponseTypeDef,
     StartReplicationResponseTypeDef,
     StopReplicationResponseTypeDef,
     DescribeRecoveryInstancesResponseTypeDef,
 )
 
@@ -501,43 +546,43 @@
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

### Comparing `types-aiobotocore-drs-2.5.0.post1/types_aiobotocore_drs.egg-info/SOURCES.txt` & `types-aiobotocore-drs-2.5.1/types_aiobotocore_drs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

