# Comparing `tmp/types-aiobotocore-mgn-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mgn-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mgn-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-mgn-2.5.1.tar", last modified: Wed Jun 28 01:43:52 2023, max compression
```

## Comparing `types-aiobotocore-mgn-2.5.0.post1.tar` & `types-aiobotocore-mgn-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.135441 types-aiobotocore-mgn-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21610 2023-03-11 12:27:01.135441 types-aiobotocore-mgn-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20055 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.135441 types-aiobotocore-mgn-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.135441 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/
--rw-r--r--   0 runner    (1001) docker     (123)     2839 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2838 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    45621 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    45547 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14067 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14065 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13302 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    13289 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    57451 2023-03-11 12:18:48.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    57400 2023-03-11 12:18:46.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:45.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.135441 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21610 2023-03-11 12:27:00.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:00.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:00.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:00.000000 types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.062179 types-aiobotocore-mgn-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    23468 2023-06-28 01:43:52.062179 types-aiobotocore-mgn-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21919 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:52.062179 types-aiobotocore-mgn-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.062179 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/
+-rw-r--r--   0 runner    (1001) docker     (123)     3591 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3590 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    51153 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    51069 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15390 2023-06-28 01:35:30.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15388 2023-06-28 01:35:30.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17578 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17562 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    68638 2023-06-28 01:35:31.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    68573 2023-06-28 01:35:30.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:29.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.062179 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23468 2023-06-28 01:43:51.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:51.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:51.000000 types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/LICENSE` & `types-aiobotocore-mgn-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mgn-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mgn-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mgn
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.mgn 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.mgn 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mgn"></a>
 
 # types-aiobotocore-mgn
 
 [![PyPI - types-aiobotocore-mgn](https://img.shields.io/pypi/v/types-aiobotocore-mgn.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgn)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mgn.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgn)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mgn?color=blue)](https://pypistats.org/packages/types-aiobotocore-mgn)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.mgn 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn)
+[aiobotocore.mgn 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn)
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
 [types-aiobotocore-mgn docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/).
 
 See how it helps to find and fix potential bugs:
 
@@ -278,14 +278,18 @@
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
     DescribeLaunchConfigurationTemplatesPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
     DescribeSourceServersPaginator,
     DescribeVcenterClientsPaginator,
     ListApplicationsPaginator,
+    ListExportErrorsPaginator,
+    ListExportsPaginator,
+    ListImportErrorsPaginator,
+    ListImportsPaginator,
     ListSourceServerActionsPaginator,
     ListTemplateActionsPaginator,
     ListWavesPaginator,
 )
 
 session = get_session()
 async with session.create_client("mgn") as client:
@@ -308,14 +312,22 @@
     )
     describe_vcenter_clients_paginator: DescribeVcenterClientsPaginator = client.get_paginator(
         "describe_vcenter_clients"
     )
     list_applications_paginator: ListApplicationsPaginator = client.get_paginator(
         "list_applications"
     )
+    list_export_errors_paginator: ListExportErrorsPaginator = client.get_paginator(
+        "list_export_errors"
+    )
+    list_exports_paginator: ListExportsPaginator = client.get_paginator("list_exports")
+    list_import_errors_paginator: ListImportErrorsPaginator = client.get_paginator(
+        "list_import_errors"
+    )
+    list_imports_paginator: ListImportsPaginator = client.get_paginator("list_imports")
     list_source_server_actions_paginator: ListSourceServerActionsPaginator = client.get_paginator(
         "list_source_server_actions"
     )
     list_template_actions_paginator: ListTemplateActionsPaginator = client.get_paginator(
         "list_template_actions"
     )
     list_waves_paginator: ListWavesPaginator = client.get_paginator("list_waves")
@@ -326,37 +338,45 @@
 ### Literals
 
 `types_aiobotocore_mgn.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mgn.literals import (
+    ActionCategoryType,
     ApplicationHealthStatusType,
     ApplicationProgressStatusType,
     BootModeType,
     ChangeServerLifeCycleStateSourceServerLifecycleStateType,
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
     DescribeJobLogItemsPaginatorName,
     DescribeJobsPaginatorName,
     DescribeLaunchConfigurationTemplatesPaginatorName,
     DescribeReplicationConfigurationTemplatesPaginatorName,
     DescribeSourceServersPaginatorName,
     DescribeVcenterClientsPaginatorName,
+    ExportStatusType,
     FirstBootType,
+    ImportErrorTypeType,
+    ImportStatusType,
     InitiatedByType,
     JobLogEventType,
     JobStatusType,
     JobTypeType,
     LaunchDispositionType,
     LaunchStatusType,
     LifeCycleStateType,
     ListApplicationsPaginatorName,
+    ListExportErrorsPaginatorName,
+    ListExportsPaginatorName,
+    ListImportErrorsPaginatorName,
+    ListImportsPaginatorName,
     ListSourceServerActionsPaginatorName,
     ListTemplateActionsPaginatorName,
     ListWavesPaginatorName,
     PostLaunchActionExecutionStatusType,
     PostLaunchActionsDeploymentTypeType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
@@ -373,29 +393,28 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: ApplicationHealthStatusType) -> bool:
+def check_value(value: ActionCategoryType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_mgn.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mgn.type_defs import (
     ApplicationAggregatedStatusTypeDef,
-    ResponseMetadataTypeDef,
     ArchiveApplicationRequestRequestTypeDef,
     ArchiveWaveRequestRequestTypeDef,
     AssociateApplicationsRequestRequestTypeDef,
     AssociateSourceServersRequestRequestTypeDef,
     CPUTypeDef,
     ChangeServerLifeCycleStateSourceServerLifecycleTypeDef,
     CreateApplicationRequestRequestTypeDef,
@@ -409,87 +428,112 @@
     DeleteApplicationRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
     DeleteLaunchConfigurationTemplateRequestRequestTypeDef,
     DeleteReplicationConfigurationTemplateRequestRequestTypeDef,
     DeleteSourceServerRequestRequestTypeDef,
     DeleteVcenterClientRequestRequestTypeDef,
     DeleteWaveRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
     DescribeJobLogItemsRequestRequestTypeDef,
     DescribeJobsRequestFiltersTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
     DescribeLaunchConfigurationTemplatesRequestRequestTypeDef,
+    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
     DescribeReplicationConfigurationTemplatesRequestRequestTypeDef,
     ReplicationConfigurationTemplateTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
+    DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef,
     DescribeVcenterClientsRequestRequestTypeDef,
     VcenterClientTypeDef,
     DisassociateApplicationsRequestRequestTypeDef,
     DisassociateSourceServersRequestRequestTypeDef,
     DisconnectFromServiceRequestRequestTypeDef,
     DiskTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ExportErrorDataTypeDef,
+    ExportTaskSummaryTypeDef,
     FinalizeCutoverRequestRequestTypeDef,
     GetLaunchConfigurationRequestRequestTypeDef,
     GetReplicationConfigurationRequestRequestTypeDef,
     IdentificationHintsTypeDef,
+    ImportErrorDataTypeDef,
+    ImportTaskSummaryApplicationsTypeDef,
+    ImportTaskSummaryServersTypeDef,
+    ImportTaskSummaryWavesTypeDef,
+    S3BucketSourceTypeDef,
     JobLogEventDataTypeDef,
     LaunchedInstanceTypeDef,
     LifeCycleLastCutoverFinalizedTypeDef,
     LifeCycleLastCutoverInitiatedTypeDef,
     LifeCycleLastCutoverRevertedTypeDef,
     LifeCycleLastTestFinalizedTypeDef,
     LifeCycleLastTestInitiatedTypeDef,
     LifeCycleLastTestRevertedTypeDef,
     ListApplicationsRequestFiltersTypeDef,
+    ListExportErrorsRequestListExportErrorsPaginateTypeDef,
+    ListExportErrorsRequestRequestTypeDef,
+    ListExportsRequestFiltersTypeDef,
+    ListImportErrorsRequestListImportErrorsPaginateTypeDef,
+    ListImportErrorsRequestRequestTypeDef,
+    ListImportsRequestFiltersTypeDef,
     SourceServerActionsRequestFiltersTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TemplateActionsRequestFiltersTypeDef,
     ListWavesRequestFiltersTypeDef,
     MarkAsArchivedRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
     OSTypeDef,
+    PaginatorConfigTypeDef,
+    SsmExternalParameterTypeDef,
     SsmParameterStoreParameterTypeDef,
     RemoveSourceServerActionRequestRequestTypeDef,
     RemoveTemplateActionRequestRequestTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
+    ReplicationConfigurationTemplateResponseMetadataTypeDef,
+    ResponseMetadataTypeDef,
     RetryDataReplicationRequestRequestTypeDef,
     StartCutoverRequestRequestTypeDef,
+    StartExportRequestRequestTypeDef,
     StartReplicationRequestRequestTypeDef,
     StartTestRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateTargetInstancesRequestRequestTypeDef,
     UnarchiveApplicationRequestRequestTypeDef,
     UnarchiveWaveRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     UpdateSourceServerReplicationTypeRequestRequestTypeDef,
     UpdateWaveRequestRequestTypeDef,
     WaveAggregatedStatusTypeDef,
-    ApplicationTypeDef,
     ApplicationResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ReplicationConfigurationTemplateResponseMetadataTypeDef,
+    ApplicationTypeDef,
     ChangeServerLifeCycleStateRequestRequestTypeDef,
     DataReplicationInitiationTypeDef,
-    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
-    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
-    DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef,
     DescribeJobsRequestDescribeJobsPaginateTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef,
     DescribeSourceServersRequestRequestTypeDef,
     DescribeVcenterClientsResponseTypeDef,
+    ExportTaskErrorTypeDef,
+    ExportTaskTypeDef,
+    ImportTaskErrorTypeDef,
+    ImportTaskSummaryTypeDef,
+    StartImportRequestRequestTypeDef,
     JobLogTypeDef,
     LifeCycleLastCutoverTypeDef,
     LifeCycleLastTestTypeDef,
     ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListExportsRequestListExportsPaginateTypeDef,
+    ListExportsRequestRequestTypeDef,
+    ListImportsRequestListImportsPaginateTypeDef,
+    ListImportsRequestRequestTypeDef,
     ListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef,
     ListSourceServerActionsRequestRequestTypeDef,
     ListTemplateActionsRequestListTemplateActionsPaginateTypeDef,
     ListTemplateActionsRequestRequestTypeDef,
     ListWavesRequestListWavesPaginateTypeDef,
     ListWavesRequestRequestTypeDef,
     SourcePropertiesTypeDef,
@@ -502,21 +546,28 @@
     TemplateActionDocumentTypeDef,
     ReplicationConfigurationTypeDef,
     UpdateReplicationConfigurationRequestRequestTypeDef,
     WaveResponseMetadataTypeDef,
     WaveTypeDef,
     ListApplicationsResponseTypeDef,
     DataReplicationInfoTypeDef,
+    ListExportErrorsResponseTypeDef,
+    ListExportsResponseTypeDef,
+    StartExportResponseTypeDef,
+    ListImportErrorsResponseTypeDef,
+    ImportTaskTypeDef,
     DescribeJobLogItemsResponseTypeDef,
     LifeCycleTypeDef,
     ListSourceServerActionsResponseTypeDef,
     JobPostLaunchActionsLaunchStatusTypeDef,
     PostLaunchActionsTypeDef,
     ListTemplateActionsResponseTypeDef,
     ListWavesResponseTypeDef,
+    ListImportsResponseTypeDef,
+    StartImportResponseTypeDef,
     SourceServerResponseMetadataTypeDef,
     SourceServerTypeDef,
     PostLaunchActionsStatusTypeDef,
     CreateLaunchConfigurationTemplateRequestRequestTypeDef,
     LaunchConfigurationTemplateResponseMetadataTypeDef,
     LaunchConfigurationTemplateTypeDef,
     LaunchConfigurationTypeDef,
@@ -540,43 +591,43 @@
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

### Comparing `types-aiobotocore-mgn-2.5.0.post1/README.md` & `types-aiobotocore-mgn-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mgn"></a>
 
 # types-aiobotocore-mgn
 
 [![PyPI - types-aiobotocore-mgn](https://img.shields.io/pypi/v/types-aiobotocore-mgn.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgn)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mgn.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgn)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mgn?color=blue)](https://pypistats.org/packages/types-aiobotocore-mgn)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.mgn 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn)
+[aiobotocore.mgn 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn)
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
 [types-aiobotocore-mgn docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/).
 
 See how it helps to find and fix potential bugs:
 
@@ -245,14 +245,18 @@
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
     DescribeLaunchConfigurationTemplatesPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
     DescribeSourceServersPaginator,
     DescribeVcenterClientsPaginator,
     ListApplicationsPaginator,
+    ListExportErrorsPaginator,
+    ListExportsPaginator,
+    ListImportErrorsPaginator,
+    ListImportsPaginator,
     ListSourceServerActionsPaginator,
     ListTemplateActionsPaginator,
     ListWavesPaginator,
 )
 
 session = get_session()
 async with session.create_client("mgn") as client:
@@ -275,14 +279,22 @@
     )
     describe_vcenter_clients_paginator: DescribeVcenterClientsPaginator = client.get_paginator(
         "describe_vcenter_clients"
     )
     list_applications_paginator: ListApplicationsPaginator = client.get_paginator(
         "list_applications"
     )
+    list_export_errors_paginator: ListExportErrorsPaginator = client.get_paginator(
+        "list_export_errors"
+    )
+    list_exports_paginator: ListExportsPaginator = client.get_paginator("list_exports")
+    list_import_errors_paginator: ListImportErrorsPaginator = client.get_paginator(
+        "list_import_errors"
+    )
+    list_imports_paginator: ListImportsPaginator = client.get_paginator("list_imports")
     list_source_server_actions_paginator: ListSourceServerActionsPaginator = client.get_paginator(
         "list_source_server_actions"
     )
     list_template_actions_paginator: ListTemplateActionsPaginator = client.get_paginator(
         "list_template_actions"
     )
     list_waves_paginator: ListWavesPaginator = client.get_paginator("list_waves")
@@ -293,37 +305,45 @@
 ### Literals
 
 `types_aiobotocore_mgn.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mgn.literals import (
+    ActionCategoryType,
     ApplicationHealthStatusType,
     ApplicationProgressStatusType,
     BootModeType,
     ChangeServerLifeCycleStateSourceServerLifecycleStateType,
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
     DescribeJobLogItemsPaginatorName,
     DescribeJobsPaginatorName,
     DescribeLaunchConfigurationTemplatesPaginatorName,
     DescribeReplicationConfigurationTemplatesPaginatorName,
     DescribeSourceServersPaginatorName,
     DescribeVcenterClientsPaginatorName,
+    ExportStatusType,
     FirstBootType,
+    ImportErrorTypeType,
+    ImportStatusType,
     InitiatedByType,
     JobLogEventType,
     JobStatusType,
     JobTypeType,
     LaunchDispositionType,
     LaunchStatusType,
     LifeCycleStateType,
     ListApplicationsPaginatorName,
+    ListExportErrorsPaginatorName,
+    ListExportsPaginatorName,
+    ListImportErrorsPaginatorName,
+    ListImportsPaginatorName,
     ListSourceServerActionsPaginatorName,
     ListTemplateActionsPaginatorName,
     ListWavesPaginatorName,
     PostLaunchActionExecutionStatusType,
     PostLaunchActionsDeploymentTypeType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
@@ -340,29 +360,28 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: ApplicationHealthStatusType) -> bool:
+def check_value(value: ActionCategoryType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_mgn.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mgn.type_defs import (
     ApplicationAggregatedStatusTypeDef,
-    ResponseMetadataTypeDef,
     ArchiveApplicationRequestRequestTypeDef,
     ArchiveWaveRequestRequestTypeDef,
     AssociateApplicationsRequestRequestTypeDef,
     AssociateSourceServersRequestRequestTypeDef,
     CPUTypeDef,
     ChangeServerLifeCycleStateSourceServerLifecycleTypeDef,
     CreateApplicationRequestRequestTypeDef,
@@ -376,87 +395,112 @@
     DeleteApplicationRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
     DeleteLaunchConfigurationTemplateRequestRequestTypeDef,
     DeleteReplicationConfigurationTemplateRequestRequestTypeDef,
     DeleteSourceServerRequestRequestTypeDef,
     DeleteVcenterClientRequestRequestTypeDef,
     DeleteWaveRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
     DescribeJobLogItemsRequestRequestTypeDef,
     DescribeJobsRequestFiltersTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
     DescribeLaunchConfigurationTemplatesRequestRequestTypeDef,
+    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
     DescribeReplicationConfigurationTemplatesRequestRequestTypeDef,
     ReplicationConfigurationTemplateTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
+    DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef,
     DescribeVcenterClientsRequestRequestTypeDef,
     VcenterClientTypeDef,
     DisassociateApplicationsRequestRequestTypeDef,
     DisassociateSourceServersRequestRequestTypeDef,
     DisconnectFromServiceRequestRequestTypeDef,
     DiskTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ExportErrorDataTypeDef,
+    ExportTaskSummaryTypeDef,
     FinalizeCutoverRequestRequestTypeDef,
     GetLaunchConfigurationRequestRequestTypeDef,
     GetReplicationConfigurationRequestRequestTypeDef,
     IdentificationHintsTypeDef,
+    ImportErrorDataTypeDef,
+    ImportTaskSummaryApplicationsTypeDef,
+    ImportTaskSummaryServersTypeDef,
+    ImportTaskSummaryWavesTypeDef,
+    S3BucketSourceTypeDef,
     JobLogEventDataTypeDef,
     LaunchedInstanceTypeDef,
     LifeCycleLastCutoverFinalizedTypeDef,
     LifeCycleLastCutoverInitiatedTypeDef,
     LifeCycleLastCutoverRevertedTypeDef,
     LifeCycleLastTestFinalizedTypeDef,
     LifeCycleLastTestInitiatedTypeDef,
     LifeCycleLastTestRevertedTypeDef,
     ListApplicationsRequestFiltersTypeDef,
+    ListExportErrorsRequestListExportErrorsPaginateTypeDef,
+    ListExportErrorsRequestRequestTypeDef,
+    ListExportsRequestFiltersTypeDef,
+    ListImportErrorsRequestListImportErrorsPaginateTypeDef,
+    ListImportErrorsRequestRequestTypeDef,
+    ListImportsRequestFiltersTypeDef,
     SourceServerActionsRequestFiltersTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TemplateActionsRequestFiltersTypeDef,
     ListWavesRequestFiltersTypeDef,
     MarkAsArchivedRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
     OSTypeDef,
+    PaginatorConfigTypeDef,
+    SsmExternalParameterTypeDef,
     SsmParameterStoreParameterTypeDef,
     RemoveSourceServerActionRequestRequestTypeDef,
     RemoveTemplateActionRequestRequestTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
+    ReplicationConfigurationTemplateResponseMetadataTypeDef,
+    ResponseMetadataTypeDef,
     RetryDataReplicationRequestRequestTypeDef,
     StartCutoverRequestRequestTypeDef,
+    StartExportRequestRequestTypeDef,
     StartReplicationRequestRequestTypeDef,
     StartTestRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateTargetInstancesRequestRequestTypeDef,
     UnarchiveApplicationRequestRequestTypeDef,
     UnarchiveWaveRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     UpdateSourceServerReplicationTypeRequestRequestTypeDef,
     UpdateWaveRequestRequestTypeDef,
     WaveAggregatedStatusTypeDef,
-    ApplicationTypeDef,
     ApplicationResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ReplicationConfigurationTemplateResponseMetadataTypeDef,
+    ApplicationTypeDef,
     ChangeServerLifeCycleStateRequestRequestTypeDef,
     DataReplicationInitiationTypeDef,
-    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
-    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
-    DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef,
     DescribeJobsRequestDescribeJobsPaginateTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef,
     DescribeSourceServersRequestRequestTypeDef,
     DescribeVcenterClientsResponseTypeDef,
+    ExportTaskErrorTypeDef,
+    ExportTaskTypeDef,
+    ImportTaskErrorTypeDef,
+    ImportTaskSummaryTypeDef,
+    StartImportRequestRequestTypeDef,
     JobLogTypeDef,
     LifeCycleLastCutoverTypeDef,
     LifeCycleLastTestTypeDef,
     ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListExportsRequestListExportsPaginateTypeDef,
+    ListExportsRequestRequestTypeDef,
+    ListImportsRequestListImportsPaginateTypeDef,
+    ListImportsRequestRequestTypeDef,
     ListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef,
     ListSourceServerActionsRequestRequestTypeDef,
     ListTemplateActionsRequestListTemplateActionsPaginateTypeDef,
     ListTemplateActionsRequestRequestTypeDef,
     ListWavesRequestListWavesPaginateTypeDef,
     ListWavesRequestRequestTypeDef,
     SourcePropertiesTypeDef,
@@ -469,21 +513,28 @@
     TemplateActionDocumentTypeDef,
     ReplicationConfigurationTypeDef,
     UpdateReplicationConfigurationRequestRequestTypeDef,
     WaveResponseMetadataTypeDef,
     WaveTypeDef,
     ListApplicationsResponseTypeDef,
     DataReplicationInfoTypeDef,
+    ListExportErrorsResponseTypeDef,
+    ListExportsResponseTypeDef,
+    StartExportResponseTypeDef,
+    ListImportErrorsResponseTypeDef,
+    ImportTaskTypeDef,
     DescribeJobLogItemsResponseTypeDef,
     LifeCycleTypeDef,
     ListSourceServerActionsResponseTypeDef,
     JobPostLaunchActionsLaunchStatusTypeDef,
     PostLaunchActionsTypeDef,
     ListTemplateActionsResponseTypeDef,
     ListWavesResponseTypeDef,
+    ListImportsResponseTypeDef,
+    StartImportResponseTypeDef,
     SourceServerResponseMetadataTypeDef,
     SourceServerTypeDef,
     PostLaunchActionsStatusTypeDef,
     CreateLaunchConfigurationTemplateRequestRequestTypeDef,
     LaunchConfigurationTemplateResponseMetadataTypeDef,
     LaunchConfigurationTemplateTypeDef,
     LaunchConfigurationTypeDef,
@@ -507,43 +558,43 @@
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

### Comparing `types-aiobotocore-mgn-2.5.0.post1/setup.py` & `types-aiobotocore-mgn-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mgn.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mgn",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mgn"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.mgn 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.mgn 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/",
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

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/__init__.py` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/__init__.pyi`

 * *Files 21% similar despite different names*

```diff
@@ -10,14 +10,18 @@
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
         DescribeLaunchConfigurationTemplatesPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
         DescribeSourceServersPaginator,
         DescribeVcenterClientsPaginator,
         ListApplicationsPaginator,
+        ListExportErrorsPaginator,
+        ListExportsPaginator,
+        ListImportErrorsPaginator,
+        ListImportsPaginator,
         ListSourceServerActionsPaginator,
         ListTemplateActionsPaginator,
         ListWavesPaginator,
         mgnClient,
     )
 
     session = get_session()
@@ -29,43 +33,54 @@
     describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
     describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
     describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
     describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
     describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
     describe_vcenter_clients_paginator: DescribeVcenterClientsPaginator = client.get_paginator("describe_vcenter_clients")
     list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
+    list_export_errors_paginator: ListExportErrorsPaginator = client.get_paginator("list_export_errors")
+    list_exports_paginator: ListExportsPaginator = client.get_paginator("list_exports")
+    list_import_errors_paginator: ListImportErrorsPaginator = client.get_paginator("list_import_errors")
+    list_imports_paginator: ListImportsPaginator = client.get_paginator("list_imports")
     list_source_server_actions_paginator: ListSourceServerActionsPaginator = client.get_paginator("list_source_server_actions")
     list_template_actions_paginator: ListTemplateActionsPaginator = client.get_paginator("list_template_actions")
     list_waves_paginator: ListWavesPaginator = client.get_paginator("list_waves")
     ```
 """
 from .client import mgnClient
 from .paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
     DescribeLaunchConfigurationTemplatesPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
     DescribeSourceServersPaginator,
     DescribeVcenterClientsPaginator,
     ListApplicationsPaginator,
+    ListExportErrorsPaginator,
+    ListExportsPaginator,
+    ListImportErrorsPaginator,
+    ListImportsPaginator,
     ListSourceServerActionsPaginator,
     ListTemplateActionsPaginator,
     ListWavesPaginator,
 )
 
 Client = mgnClient
 
-
 __all__ = (
     "Client",
     "DescribeJobLogItemsPaginator",
     "DescribeJobsPaginator",
     "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
     "DescribeSourceServersPaginator",
     "DescribeVcenterClientsPaginator",
     "ListApplicationsPaginator",
+    "ListExportErrorsPaginator",
+    "ListExportsPaginator",
+    "ListImportErrorsPaginator",
+    "ListImportsPaginator",
     "ListSourceServerActionsPaginator",
     "ListTemplateActionsPaginator",
     "ListWavesPaginator",
     "mgnClient",
 )
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/__init__.pyi` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/__init__.py`

 * *Files 22% similar despite different names*

```diff
@@ -10,14 +10,18 @@
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
         DescribeLaunchConfigurationTemplatesPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
         DescribeSourceServersPaginator,
         DescribeVcenterClientsPaginator,
         ListApplicationsPaginator,
+        ListExportErrorsPaginator,
+        ListExportsPaginator,
+        ListImportErrorsPaginator,
+        ListImportsPaginator,
         ListSourceServerActionsPaginator,
         ListTemplateActionsPaginator,
         ListWavesPaginator,
         mgnClient,
     )
 
     session = get_session()
@@ -29,42 +33,55 @@
     describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
     describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
     describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
     describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
     describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
     describe_vcenter_clients_paginator: DescribeVcenterClientsPaginator = client.get_paginator("describe_vcenter_clients")
     list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
+    list_export_errors_paginator: ListExportErrorsPaginator = client.get_paginator("list_export_errors")
+    list_exports_paginator: ListExportsPaginator = client.get_paginator("list_exports")
+    list_import_errors_paginator: ListImportErrorsPaginator = client.get_paginator("list_import_errors")
+    list_imports_paginator: ListImportsPaginator = client.get_paginator("list_imports")
     list_source_server_actions_paginator: ListSourceServerActionsPaginator = client.get_paginator("list_source_server_actions")
     list_template_actions_paginator: ListTemplateActionsPaginator = client.get_paginator("list_template_actions")
     list_waves_paginator: ListWavesPaginator = client.get_paginator("list_waves")
     ```
 """
 from .client import mgnClient
 from .paginator import (
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
     DescribeLaunchConfigurationTemplatesPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
     DescribeSourceServersPaginator,
     DescribeVcenterClientsPaginator,
     ListApplicationsPaginator,
+    ListExportErrorsPaginator,
+    ListExportsPaginator,
+    ListImportErrorsPaginator,
+    ListImportsPaginator,
     ListSourceServerActionsPaginator,
     ListTemplateActionsPaginator,
     ListWavesPaginator,
 )
 
 Client = mgnClient
 
+
 __all__ = (
     "Client",
     "DescribeJobLogItemsPaginator",
     "DescribeJobsPaginator",
     "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
     "DescribeSourceServersPaginator",
     "DescribeVcenterClientsPaginator",
     "ListApplicationsPaginator",
+    "ListExportErrorsPaginator",
+    "ListExportsPaginator",
+    "ListImportErrorsPaginator",
+    "ListImportsPaginator",
     "ListSourceServerActionsPaginator",
     "ListTemplateActionsPaginator",
     "ListWavesPaginator",
     "mgnClient",
 )
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/__main__.py` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.mgn 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.mgn 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn\nOther"
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

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/client.py` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    ActionCategoryType,
     BootModeType,
     LaunchDispositionType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     ReplicationTypeType,
     TargetInstanceTypeRightSizingMethodType,
@@ -33,14 +34,18 @@
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
     DescribeLaunchConfigurationTemplatesPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
     DescribeSourceServersPaginator,
     DescribeVcenterClientsPaginator,
     ListApplicationsPaginator,
+    ListExportErrorsPaginator,
+    ListExportsPaginator,
+    ListImportErrorsPaginator,
+    ListImportsPaginator,
     ListSourceServerActionsPaginator,
     ListTemplateActionsPaginator,
     ListWavesPaginator,
 )
 from .type_defs import (
     ApplicationResponseMetadataTypeDef,
     ChangeServerLifeCycleStateSourceServerLifecycleTypeDef,
@@ -55,28 +60,38 @@
     EmptyResponseMetadataTypeDef,
     LaunchConfigurationTemplateResponseMetadataTypeDef,
     LaunchConfigurationTypeDef,
     LaunchTemplateDiskConfTypeDef,
     LicensingTypeDef,
     ListApplicationsRequestFiltersTypeDef,
     ListApplicationsResponseTypeDef,
+    ListExportErrorsResponseTypeDef,
+    ListExportsRequestFiltersTypeDef,
+    ListExportsResponseTypeDef,
+    ListImportErrorsResponseTypeDef,
+    ListImportsRequestFiltersTypeDef,
+    ListImportsResponseTypeDef,
     ListSourceServerActionsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTemplateActionsResponseTypeDef,
     ListWavesRequestFiltersTypeDef,
     ListWavesResponseTypeDef,
     PostLaunchActionsTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
     ReplicationConfigurationTemplateResponseMetadataTypeDef,
     ReplicationConfigurationTypeDef,
+    S3BucketSourceTypeDef,
     SourceServerActionDocumentResponseMetadataTypeDef,
     SourceServerActionsRequestFiltersTypeDef,
     SourceServerResponseMetadataTypeDef,
+    SsmExternalParameterTypeDef,
     SsmParameterStoreParameterTypeDef,
     StartCutoverResponseTypeDef,
+    StartExportResponseTypeDef,
+    StartImportResponseTypeDef,
     StartTestResponseTypeDef,
     TemplateActionDocumentResponseMetadataTypeDef,
     TemplateActionsRequestFiltersTypeDef,
     TerminateTargetInstancesResponseTypeDef,
     WaveResponseMetadataTypeDef,
 )
 
@@ -490,14 +505,62 @@
         """
         Retrieves all applications or multiple applications by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_applications)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_applications)
         """
 
+    async def list_export_errors(
+        self, *, exportID: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListExportErrorsResponseTypeDef:
+        """
+        List export errors.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_export_errors)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_export_errors)
+        """
+
+    async def list_exports(
+        self,
+        *,
+        filters: ListExportsRequestFiltersTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListExportsResponseTypeDef:
+        """
+        List exports.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_exports)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_exports)
+        """
+
+    async def list_import_errors(
+        self, *, importID: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListImportErrorsResponseTypeDef:
+        """
+        List import errors.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_import_errors)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_import_errors)
+        """
+
+    async def list_imports(
+        self,
+        *,
+        filters: ListImportsRequestFiltersTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListImportsResponseTypeDef:
+        """
+        List imports.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_imports)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_imports)
+        """
+
     async def list_source_server_actions(
         self,
         *,
         sourceServerID: str,
         filters: SourceServerActionsRequestFiltersTypeDef = ...,
         maxResults: int = ...,
         nextToken: str = ...
@@ -562,15 +625,18 @@
         *,
         actionID: str,
         actionName: str,
         documentIdentifier: str,
         order: int,
         sourceServerID: str,
         active: bool = ...,
+        category: ActionCategoryType = ...,
+        description: str = ...,
         documentVersion: str = ...,
+        externalParameters: Mapping[str, SsmExternalParameterTypeDef] = ...,
         mustSucceedForCutover: bool = ...,
         parameters: Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]] = ...,
         timeoutSeconds: int = ...
     ) -> SourceServerActionDocumentResponseMetadataTypeDef:
         """
         Put source server post migration custom action.
 
@@ -583,15 +649,18 @@
         *,
         actionID: str,
         actionName: str,
         documentIdentifier: str,
         launchConfigurationTemplateID: str,
         order: int,
         active: bool = ...,
+        category: ActionCategoryType = ...,
+        description: str = ...,
         documentVersion: str = ...,
+        externalParameters: Mapping[str, SsmExternalParameterTypeDef] = ...,
         mustSucceedForCutover: bool = ...,
         operatingSystem: str = ...,
         parameters: Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]] = ...,
         timeoutSeconds: int = ...
     ) -> TemplateActionDocumentResponseMetadataTypeDef:
         """
         Put template post migration custom action.
@@ -638,14 +707,34 @@
         """
         Launches a Cutover Instance for specific Source Servers.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_cutover)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#start_cutover)
         """
 
+    async def start_export(
+        self, *, s3Bucket: str, s3Key: str, s3BucketOwner: str = ...
+    ) -> StartExportResponseTypeDef:
+        """
+        Start export.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_export)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#start_export)
+        """
+
+    async def start_import(
+        self, *, s3BucketSource: S3BucketSourceTypeDef, clientToken: str = ...
+    ) -> StartImportResponseTypeDef:
+        """
+        Start import.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_import)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#start_import)
+        """
+
     async def start_replication(
         self, *, sourceServerID: str
     ) -> SourceServerResponseMetadataTypeDef:
         """
         Starts replication for SNAPSHOT_SHIPPING agents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_replication)
@@ -900,14 +989,46 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_export_errors"]
+    ) -> ListExportErrorsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_exports"]) -> ListExportsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_import_errors"]
+    ) -> ListImportErrorsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(self, operation_name: Literal["list_imports"]) -> ListImportsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_source_server_actions"]
     ) -> ListSourceServerActionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
         """
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/client.pyi` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/client.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    ActionCategoryType,
     BootModeType,
     LaunchDispositionType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
     ReplicationConfigurationEbsEncryptionType,
     ReplicationTypeType,
     TargetInstanceTypeRightSizingMethodType,
@@ -33,14 +34,18 @@
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
     DescribeLaunchConfigurationTemplatesPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
     DescribeSourceServersPaginator,
     DescribeVcenterClientsPaginator,
     ListApplicationsPaginator,
+    ListExportErrorsPaginator,
+    ListExportsPaginator,
+    ListImportErrorsPaginator,
+    ListImportsPaginator,
     ListSourceServerActionsPaginator,
     ListTemplateActionsPaginator,
     ListWavesPaginator,
 )
 from .type_defs import (
     ApplicationResponseMetadataTypeDef,
     ChangeServerLifeCycleStateSourceServerLifecycleTypeDef,
@@ -55,28 +60,38 @@
     EmptyResponseMetadataTypeDef,
     LaunchConfigurationTemplateResponseMetadataTypeDef,
     LaunchConfigurationTypeDef,
     LaunchTemplateDiskConfTypeDef,
     LicensingTypeDef,
     ListApplicationsRequestFiltersTypeDef,
     ListApplicationsResponseTypeDef,
+    ListExportErrorsResponseTypeDef,
+    ListExportsRequestFiltersTypeDef,
+    ListExportsResponseTypeDef,
+    ListImportErrorsResponseTypeDef,
+    ListImportsRequestFiltersTypeDef,
+    ListImportsResponseTypeDef,
     ListSourceServerActionsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTemplateActionsResponseTypeDef,
     ListWavesRequestFiltersTypeDef,
     ListWavesResponseTypeDef,
     PostLaunchActionsTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
     ReplicationConfigurationTemplateResponseMetadataTypeDef,
     ReplicationConfigurationTypeDef,
+    S3BucketSourceTypeDef,
     SourceServerActionDocumentResponseMetadataTypeDef,
     SourceServerActionsRequestFiltersTypeDef,
     SourceServerResponseMetadataTypeDef,
+    SsmExternalParameterTypeDef,
     SsmParameterStoreParameterTypeDef,
     StartCutoverResponseTypeDef,
+    StartExportResponseTypeDef,
+    StartImportResponseTypeDef,
     StartTestResponseTypeDef,
     TemplateActionDocumentResponseMetadataTypeDef,
     TemplateActionsRequestFiltersTypeDef,
     TerminateTargetInstancesResponseTypeDef,
     WaveResponseMetadataTypeDef,
 )
 
@@ -452,14 +467,58 @@
     ) -> ListApplicationsResponseTypeDef:
         """
         Retrieves all applications or multiple applications by ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_applications)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_applications)
         """
+    async def list_export_errors(
+        self, *, exportID: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListExportErrorsResponseTypeDef:
+        """
+        List export errors.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_export_errors)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_export_errors)
+        """
+    async def list_exports(
+        self,
+        *,
+        filters: ListExportsRequestFiltersTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListExportsResponseTypeDef:
+        """
+        List exports.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_exports)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_exports)
+        """
+    async def list_import_errors(
+        self, *, importID: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListImportErrorsResponseTypeDef:
+        """
+        List import errors.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_import_errors)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_import_errors)
+        """
+    async def list_imports(
+        self,
+        *,
+        filters: ListImportsRequestFiltersTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListImportsResponseTypeDef:
+        """
+        List imports.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.list_imports)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#list_imports)
+        """
     async def list_source_server_actions(
         self,
         *,
         sourceServerID: str,
         filters: SourceServerActionsRequestFiltersTypeDef = ...,
         maxResults: int = ...,
         nextToken: str = ...
@@ -519,15 +578,18 @@
         *,
         actionID: str,
         actionName: str,
         documentIdentifier: str,
         order: int,
         sourceServerID: str,
         active: bool = ...,
+        category: ActionCategoryType = ...,
+        description: str = ...,
         documentVersion: str = ...,
+        externalParameters: Mapping[str, SsmExternalParameterTypeDef] = ...,
         mustSucceedForCutover: bool = ...,
         parameters: Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]] = ...,
         timeoutSeconds: int = ...
     ) -> SourceServerActionDocumentResponseMetadataTypeDef:
         """
         Put source server post migration custom action.
 
@@ -539,15 +601,18 @@
         *,
         actionID: str,
         actionName: str,
         documentIdentifier: str,
         launchConfigurationTemplateID: str,
         order: int,
         active: bool = ...,
+        category: ActionCategoryType = ...,
+        description: str = ...,
         documentVersion: str = ...,
+        externalParameters: Mapping[str, SsmExternalParameterTypeDef] = ...,
         mustSucceedForCutover: bool = ...,
         operatingSystem: str = ...,
         parameters: Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]] = ...,
         timeoutSeconds: int = ...
     ) -> TemplateActionDocumentResponseMetadataTypeDef:
         """
         Put template post migration custom action.
@@ -589,14 +654,32 @@
     ) -> StartCutoverResponseTypeDef:
         """
         Launches a Cutover Instance for specific Source Servers.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_cutover)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#start_cutover)
         """
+    async def start_export(
+        self, *, s3Bucket: str, s3Key: str, s3BucketOwner: str = ...
+    ) -> StartExportResponseTypeDef:
+        """
+        Start export.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_export)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#start_export)
+        """
+    async def start_import(
+        self, *, s3BucketSource: S3BucketSourceTypeDef, clientToken: str = ...
+    ) -> StartImportResponseTypeDef:
+        """
+        Start import.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_import)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#start_import)
+        """
     async def start_replication(
         self, *, sourceServerID: str
     ) -> SourceServerResponseMetadataTypeDef:
         """
         Starts replication for SNAPSHOT_SHIPPING agents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.start_replication)
@@ -830,14 +913,42 @@
     ) -> ListApplicationsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_export_errors"]
+    ) -> ListExportErrorsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_exports"]) -> ListExportsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_import_errors"]
+    ) -> ListImportErrorsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(self, operation_name: Literal["list_imports"]) -> ListImportsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_source_server_actions"]
     ) -> ListSourceServerActionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/client/#get_paginator)
         """
     @overload
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/literals.py` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,51 +2,59 @@
 Type annotations for mgn service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_mgn.literals import ApplicationHealthStatusType
+    from types_aiobotocore_mgn.literals import ActionCategoryType
 
-    data: ApplicationHealthStatusType = "ERROR"
+    data: ActionCategoryType = "BACKUP"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "ActionCategoryType",
     "ApplicationHealthStatusType",
     "ApplicationProgressStatusType",
     "BootModeType",
     "ChangeServerLifeCycleStateSourceServerLifecycleStateType",
     "DataReplicationErrorStringType",
     "DataReplicationInitiationStepNameType",
     "DataReplicationInitiationStepStatusType",
     "DataReplicationStateType",
     "DescribeJobLogItemsPaginatorName",
     "DescribeJobsPaginatorName",
     "DescribeLaunchConfigurationTemplatesPaginatorName",
     "DescribeReplicationConfigurationTemplatesPaginatorName",
     "DescribeSourceServersPaginatorName",
     "DescribeVcenterClientsPaginatorName",
+    "ExportStatusType",
     "FirstBootType",
+    "ImportErrorTypeType",
+    "ImportStatusType",
     "InitiatedByType",
     "JobLogEventType",
     "JobStatusType",
     "JobTypeType",
     "LaunchDispositionType",
     "LaunchStatusType",
     "LifeCycleStateType",
     "ListApplicationsPaginatorName",
+    "ListExportErrorsPaginatorName",
+    "ListExportsPaginatorName",
+    "ListImportErrorsPaginatorName",
+    "ListImportsPaginatorName",
     "ListSourceServerActionsPaginatorName",
     "ListTemplateActionsPaginatorName",
     "ListWavesPaginatorName",
     "PostLaunchActionExecutionStatusType",
     "PostLaunchActionsDeploymentTypeType",
     "ReplicationConfigurationDataPlaneRoutingType",
     "ReplicationConfigurationDefaultLargeStagingDiskTypeType",
@@ -63,14 +71,26 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
+ActionCategoryType = Literal[
+    "BACKUP",
+    "CONFIGURATION",
+    "DISASTER_RECOVERY",
+    "LICENSE_AND_SUBSCRIPTION",
+    "NETWORKING",
+    "OBSERVABILITY",
+    "OPERATING_SYSTEM",
+    "OTHER",
+    "SECURITY",
+    "VALIDATION",
+]
 ApplicationHealthStatusType = Literal["ERROR", "HEALTHY", "LAGGING"]
 ApplicationProgressStatusType = Literal["COMPLETED", "IN_PROGRESS", "NOT_STARTED"]
 BootModeType = Literal["LEGACY_BIOS", "UEFI"]
 ChangeServerLifeCycleStateSourceServerLifecycleStateType = Literal[
     "CUTOVER", "READY_FOR_CUTOVER", "READY_FOR_TEST"
 ]
 DataReplicationErrorStringType = Literal[
@@ -127,15 +147,18 @@
     "describe_launch_configuration_templates"
 ]
 DescribeReplicationConfigurationTemplatesPaginatorName = Literal[
     "describe_replication_configuration_templates"
 ]
 DescribeSourceServersPaginatorName = Literal["describe_source_servers"]
 DescribeVcenterClientsPaginatorName = Literal["describe_vcenter_clients"]
+ExportStatusType = Literal["FAILED", "PENDING", "STARTED", "SUCCEEDED"]
 FirstBootType = Literal["STOPPED", "SUCCEEDED", "UNKNOWN", "WAITING"]
+ImportErrorTypeType = Literal["PROCESSING_ERROR", "VALIDATION_ERROR"]
+ImportStatusType = Literal["FAILED", "PENDING", "STARTED", "SUCCEEDED"]
 InitiatedByType = Literal["DIAGNOSTIC", "START_CUTOVER", "START_TEST", "TERMINATE"]
 JobLogEventType = Literal[
     "CLEANUP_END",
     "CLEANUP_FAIL",
     "CLEANUP_START",
     "CONVERSION_END",
     "CONVERSION_FAIL",
@@ -157,20 +180,25 @@
 LaunchStatusType = Literal["FAILED", "IN_PROGRESS", "LAUNCHED", "PENDING", "TERMINATED"]
 LifeCycleStateType = Literal[
     "CUTOVER",
     "CUTTING_OVER",
     "DISCONNECTED",
     "DISCOVERED",
     "NOT_READY",
+    "PENDING_INSTALLATION",
     "READY_FOR_CUTOVER",
     "READY_FOR_TEST",
     "STOPPED",
     "TESTING",
 ]
 ListApplicationsPaginatorName = Literal["list_applications"]
+ListExportErrorsPaginatorName = Literal["list_export_errors"]
+ListExportsPaginatorName = Literal["list_exports"]
+ListImportErrorsPaginatorName = Literal["list_import_errors"]
+ListImportsPaginatorName = Literal["list_imports"]
 ListSourceServerActionsPaginatorName = Literal["list_source_server_actions"]
 ListTemplateActionsPaginatorName = Literal["list_template_actions"]
 ListWavesPaginatorName = Literal["list_waves"]
 PostLaunchActionExecutionStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCESS"]
 PostLaunchActionsDeploymentTypeType = Literal["CUTOVER_ONLY", "TEST_AND_CUTOVER", "TEST_ONLY"]
 ReplicationConfigurationDataPlaneRoutingType = Literal["PRIVATE_IP", "PUBLIC_IP"]
 ReplicationConfigurationDefaultLargeStagingDiskTypeType = Literal["GP2", "GP3", "ST1"]
@@ -244,14 +272,15 @@
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
@@ -330,14 +359,15 @@
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
@@ -348,14 +378,15 @@
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
@@ -391,14 +422,15 @@
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
@@ -417,16 +449,19 @@
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
@@ -510,15 +545,17 @@
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
@@ -544,35 +581,44 @@
     "describe_job_log_items",
     "describe_jobs",
     "describe_launch_configuration_templates",
     "describe_replication_configuration_templates",
     "describe_source_servers",
     "describe_vcenter_clients",
     "list_applications",
+    "list_export_errors",
+    "list_exports",
+    "list_import_errors",
+    "list_imports",
     "list_source_server_actions",
     "list_template_actions",
     "list_waves",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/literals.pyi` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -2,50 +2,58 @@
 Type annotations for mgn service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_mgn.literals import ApplicationHealthStatusType
+    from types_aiobotocore_mgn.literals import ActionCategoryType
 
-    data: ApplicationHealthStatusType = "ERROR"
+    data: ActionCategoryType = "BACKUP"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "ActionCategoryType",
     "ApplicationHealthStatusType",
     "ApplicationProgressStatusType",
     "BootModeType",
     "ChangeServerLifeCycleStateSourceServerLifecycleStateType",
     "DataReplicationErrorStringType",
     "DataReplicationInitiationStepNameType",
     "DataReplicationInitiationStepStatusType",
     "DataReplicationStateType",
     "DescribeJobLogItemsPaginatorName",
     "DescribeJobsPaginatorName",
     "DescribeLaunchConfigurationTemplatesPaginatorName",
     "DescribeReplicationConfigurationTemplatesPaginatorName",
     "DescribeSourceServersPaginatorName",
     "DescribeVcenterClientsPaginatorName",
+    "ExportStatusType",
     "FirstBootType",
+    "ImportErrorTypeType",
+    "ImportStatusType",
     "InitiatedByType",
     "JobLogEventType",
     "JobStatusType",
     "JobTypeType",
     "LaunchDispositionType",
     "LaunchStatusType",
     "LifeCycleStateType",
     "ListApplicationsPaginatorName",
+    "ListExportErrorsPaginatorName",
+    "ListExportsPaginatorName",
+    "ListImportErrorsPaginatorName",
+    "ListImportsPaginatorName",
     "ListSourceServerActionsPaginatorName",
     "ListTemplateActionsPaginatorName",
     "ListWavesPaginatorName",
     "PostLaunchActionExecutionStatusType",
     "PostLaunchActionsDeploymentTypeType",
     "ReplicationConfigurationDataPlaneRoutingType",
     "ReplicationConfigurationDefaultLargeStagingDiskTypeType",
@@ -61,14 +69,26 @@
     "mgnServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+ActionCategoryType = Literal[
+    "BACKUP",
+    "CONFIGURATION",
+    "DISASTER_RECOVERY",
+    "LICENSE_AND_SUBSCRIPTION",
+    "NETWORKING",
+    "OBSERVABILITY",
+    "OPERATING_SYSTEM",
+    "OTHER",
+    "SECURITY",
+    "VALIDATION",
+]
 ApplicationHealthStatusType = Literal["ERROR", "HEALTHY", "LAGGING"]
 ApplicationProgressStatusType = Literal["COMPLETED", "IN_PROGRESS", "NOT_STARTED"]
 BootModeType = Literal["LEGACY_BIOS", "UEFI"]
 ChangeServerLifeCycleStateSourceServerLifecycleStateType = Literal[
     "CUTOVER", "READY_FOR_CUTOVER", "READY_FOR_TEST"
 ]
 DataReplicationErrorStringType = Literal[
@@ -125,15 +145,18 @@
     "describe_launch_configuration_templates"
 ]
 DescribeReplicationConfigurationTemplatesPaginatorName = Literal[
     "describe_replication_configuration_templates"
 ]
 DescribeSourceServersPaginatorName = Literal["describe_source_servers"]
 DescribeVcenterClientsPaginatorName = Literal["describe_vcenter_clients"]
+ExportStatusType = Literal["FAILED", "PENDING", "STARTED", "SUCCEEDED"]
 FirstBootType = Literal["STOPPED", "SUCCEEDED", "UNKNOWN", "WAITING"]
+ImportErrorTypeType = Literal["PROCESSING_ERROR", "VALIDATION_ERROR"]
+ImportStatusType = Literal["FAILED", "PENDING", "STARTED", "SUCCEEDED"]
 InitiatedByType = Literal["DIAGNOSTIC", "START_CUTOVER", "START_TEST", "TERMINATE"]
 JobLogEventType = Literal[
     "CLEANUP_END",
     "CLEANUP_FAIL",
     "CLEANUP_START",
     "CONVERSION_END",
     "CONVERSION_FAIL",
@@ -155,20 +178,25 @@
 LaunchStatusType = Literal["FAILED", "IN_PROGRESS", "LAUNCHED", "PENDING", "TERMINATED"]
 LifeCycleStateType = Literal[
     "CUTOVER",
     "CUTTING_OVER",
     "DISCONNECTED",
     "DISCOVERED",
     "NOT_READY",
+    "PENDING_INSTALLATION",
     "READY_FOR_CUTOVER",
     "READY_FOR_TEST",
     "STOPPED",
     "TESTING",
 ]
 ListApplicationsPaginatorName = Literal["list_applications"]
+ListExportErrorsPaginatorName = Literal["list_export_errors"]
+ListExportsPaginatorName = Literal["list_exports"]
+ListImportErrorsPaginatorName = Literal["list_import_errors"]
+ListImportsPaginatorName = Literal["list_imports"]
 ListSourceServerActionsPaginatorName = Literal["list_source_server_actions"]
 ListTemplateActionsPaginatorName = Literal["list_template_actions"]
 ListWavesPaginatorName = Literal["list_waves"]
 PostLaunchActionExecutionStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCESS"]
 PostLaunchActionsDeploymentTypeType = Literal["CUTOVER_ONLY", "TEST_AND_CUTOVER", "TEST_ONLY"]
 ReplicationConfigurationDataPlaneRoutingType = Literal["PRIVATE_IP", "PUBLIC_IP"]
 ReplicationConfigurationDefaultLargeStagingDiskTypeType = Literal["GP2", "GP3", "ST1"]
@@ -242,14 +270,15 @@
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
@@ -328,14 +357,15 @@
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
@@ -346,14 +376,15 @@
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
@@ -389,14 +420,15 @@
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
@@ -415,16 +447,19 @@
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
@@ -508,15 +543,17 @@
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
@@ -542,35 +579,44 @@
     "describe_job_log_items",
     "describe_jobs",
     "describe_launch_configuration_templates",
     "describe_replication_configuration_templates",
     "describe_source_servers",
     "describe_vcenter_clients",
     "list_applications",
+    "list_export_errors",
+    "list_exports",
+    "list_import_errors",
+    "list_imports",
     "list_source_server_actions",
     "list_template_actions",
     "list_waves",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/paginator.py` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/paginator.pyi`

 * *Files 16% similar despite different names*

```diff
@@ -13,14 +13,18 @@
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
         DescribeLaunchConfigurationTemplatesPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
         DescribeSourceServersPaginator,
         DescribeVcenterClientsPaginator,
         ListApplicationsPaginator,
+        ListExportErrorsPaginator,
+        ListExportsPaginator,
+        ListImportErrorsPaginator,
+        ListImportsPaginator,
         ListSourceServerActionsPaginator,
         ListTemplateActionsPaginator,
         ListWavesPaginator,
     )
 
     session = get_session()
     with session.create_client("mgn") as client:
@@ -29,21 +33,24 @@
         describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
         describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
         describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
         describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
         describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
         describe_vcenter_clients_paginator: DescribeVcenterClientsPaginator = client.get_paginator("describe_vcenter_clients")
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
+        list_export_errors_paginator: ListExportErrorsPaginator = client.get_paginator("list_export_errors")
+        list_exports_paginator: ListExportsPaginator = client.get_paginator("list_exports")
+        list_import_errors_paginator: ListImportErrorsPaginator = client.get_paginator("list_import_errors")
+        list_imports_paginator: ListImportsPaginator = client.get_paginator("list_imports")
         list_source_server_actions_paginator: ListSourceServerActionsPaginator = client.get_paginator("list_source_server_actions")
         list_template_actions_paginator: ListTemplateActionsPaginator = client.get_paginator("list_template_actions")
         list_waves_paginator: ListWavesPaginator = client.get_paginator("list_waves")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeJobLogItemsResponseTypeDef,
     DescribeJobsRequestFiltersTypeDef,
@@ -51,220 +58,274 @@
     DescribeLaunchConfigurationTemplatesResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DescribeSourceServersResponseTypeDef,
     DescribeVcenterClientsResponseTypeDef,
     ListApplicationsRequestFiltersTypeDef,
     ListApplicationsResponseTypeDef,
+    ListExportErrorsResponseTypeDef,
+    ListExportsRequestFiltersTypeDef,
+    ListExportsResponseTypeDef,
+    ListImportErrorsResponseTypeDef,
+    ListImportsRequestFiltersTypeDef,
+    ListImportsResponseTypeDef,
     ListSourceServerActionsResponseTypeDef,
     ListTemplateActionsResponseTypeDef,
     ListWavesRequestFiltersTypeDef,
     ListWavesResponseTypeDef,
     PaginatorConfigTypeDef,
     SourceServerActionsRequestFiltersTypeDef,
     TemplateActionsRequestFiltersTypeDef,
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
     "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
     "DescribeSourceServersPaginator",
     "DescribeVcenterClientsPaginator",
     "ListApplicationsPaginator",
+    "ListExportErrorsPaginator",
+    "ListExportsPaginator",
+    "ListImportErrorsPaginator",
+    "ListImportsPaginator",
     "ListSourceServerActionsPaginator",
     "ListTemplateActionsPaginator",
     "ListWavesPaginator",
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
 class DescribeJobLogItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobLogItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejoblogitemspaginator)
     """
 
     def paginate(
-        self, *, jobID: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobLogItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobLogItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejoblogitemspaginator)
         """
 
-
 class DescribeJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeJobsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejobspaginator)
         """
 
-
 class DescribeLaunchConfigurationTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeLaunchConfigurationTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describelaunchconfigurationtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         launchConfigurationTemplateIDs: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLaunchConfigurationTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeLaunchConfigurationTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describelaunchconfigurationtemplatespaginator)
         """
 
-
 class DescribeReplicationConfigurationTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeReplicationConfigurationTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describereplicationconfigurationtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         replicationConfigurationTemplateIDs: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationConfigurationTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeReplicationConfigurationTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describereplicationconfigurationtemplatespaginator)
         """
 
-
 class DescribeSourceServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeSourceServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describesourceserverspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeSourceServersRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSourceServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeSourceServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describesourceserverspaginator)
         """
 
-
 class DescribeVcenterClientsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeVcenterClients)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describevcenterclientspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeVcenterClientsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeVcenterClients.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describevcenterclientspaginator)
         """
 
-
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: ListApplicationsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listapplicationspaginator)
         """
 
+class ListExportErrorsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExportErrors)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexporterrorspaginator)
+    """
+
+    def paginate(
+        self, *, exportID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListExportErrorsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExportErrors.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexporterrorspaginator)
+        """
+
+class ListExportsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExports)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexportspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        filters: ListExportsRequestFiltersTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListExportsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExports.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexportspaginator)
+        """
+
+class ListImportErrorsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImportErrors)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimporterrorspaginator)
+    """
+
+    def paginate(
+        self, *, importID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListImportErrorsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImportErrors.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimporterrorspaginator)
+        """
+
+class ListImportsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImports)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimportspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        filters: ListImportsRequestFiltersTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListImportsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImports.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimportspaginator)
+        """
 
 class ListSourceServerActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListSourceServerActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listsourceserveractionspaginator)
     """
 
     def paginate(
         self,
         *,
         sourceServerID: str,
         filters: SourceServerActionsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceServerActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListSourceServerActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listsourceserveractionspaginator)
         """
 
-
 class ListTemplateActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListTemplateActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listtemplateactionspaginator)
     """
 
     def paginate(
         self,
         *,
         launchConfigurationTemplateID: str,
         filters: TemplateActionsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplateActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListTemplateActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listtemplateactionspaginator)
         """
 
-
 class ListWavesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListWaves)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listwavespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: ListWavesRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWavesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListWaves.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listwavespaginator)
         """
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/paginator.pyi` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/paginator.py`

 * *Files 13% similar despite different names*

```diff
@@ -13,14 +13,18 @@
         DescribeJobLogItemsPaginator,
         DescribeJobsPaginator,
         DescribeLaunchConfigurationTemplatesPaginator,
         DescribeReplicationConfigurationTemplatesPaginator,
         DescribeSourceServersPaginator,
         DescribeVcenterClientsPaginator,
         ListApplicationsPaginator,
+        ListExportErrorsPaginator,
+        ListExportsPaginator,
+        ListImportErrorsPaginator,
+        ListImportsPaginator,
         ListSourceServerActionsPaginator,
         ListTemplateActionsPaginator,
         ListWavesPaginator,
     )
 
     session = get_session()
     with session.create_client("mgn") as client:
@@ -29,21 +33,24 @@
         describe_job_log_items_paginator: DescribeJobLogItemsPaginator = client.get_paginator("describe_job_log_items")
         describe_jobs_paginator: DescribeJobsPaginator = client.get_paginator("describe_jobs")
         describe_launch_configuration_templates_paginator: DescribeLaunchConfigurationTemplatesPaginator = client.get_paginator("describe_launch_configuration_templates")
         describe_replication_configuration_templates_paginator: DescribeReplicationConfigurationTemplatesPaginator = client.get_paginator("describe_replication_configuration_templates")
         describe_source_servers_paginator: DescribeSourceServersPaginator = client.get_paginator("describe_source_servers")
         describe_vcenter_clients_paginator: DescribeVcenterClientsPaginator = client.get_paginator("describe_vcenter_clients")
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
+        list_export_errors_paginator: ListExportErrorsPaginator = client.get_paginator("list_export_errors")
+        list_exports_paginator: ListExportsPaginator = client.get_paginator("list_exports")
+        list_import_errors_paginator: ListImportErrorsPaginator = client.get_paginator("list_import_errors")
+        list_imports_paginator: ListImportsPaginator = client.get_paginator("list_imports")
         list_source_server_actions_paginator: ListSourceServerActionsPaginator = client.get_paginator("list_source_server_actions")
         list_template_actions_paginator: ListTemplateActionsPaginator = client.get_paginator("list_template_actions")
         list_waves_paginator: ListWavesPaginator = client.get_paginator("list_waves")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeJobLogItemsResponseTypeDef,
     DescribeJobsRequestFiltersTypeDef,
@@ -51,207 +58,290 @@
     DescribeLaunchConfigurationTemplatesResponseTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
     DescribeSourceServersResponseTypeDef,
     DescribeVcenterClientsResponseTypeDef,
     ListApplicationsRequestFiltersTypeDef,
     ListApplicationsResponseTypeDef,
+    ListExportErrorsResponseTypeDef,
+    ListExportsRequestFiltersTypeDef,
+    ListExportsResponseTypeDef,
+    ListImportErrorsResponseTypeDef,
+    ListImportsRequestFiltersTypeDef,
+    ListImportsResponseTypeDef,
     ListSourceServerActionsResponseTypeDef,
     ListTemplateActionsResponseTypeDef,
     ListWavesRequestFiltersTypeDef,
     ListWavesResponseTypeDef,
     PaginatorConfigTypeDef,
     SourceServerActionsRequestFiltersTypeDef,
     TemplateActionsRequestFiltersTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeJobLogItemsPaginator",
     "DescribeJobsPaginator",
     "DescribeLaunchConfigurationTemplatesPaginator",
     "DescribeReplicationConfigurationTemplatesPaginator",
     "DescribeSourceServersPaginator",
     "DescribeVcenterClientsPaginator",
     "ListApplicationsPaginator",
+    "ListExportErrorsPaginator",
+    "ListExportsPaginator",
+    "ListImportErrorsPaginator",
+    "ListImportsPaginator",
     "ListSourceServerActionsPaginator",
     "ListTemplateActionsPaginator",
     "ListWavesPaginator",
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
 class DescribeJobLogItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobLogItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejoblogitemspaginator)
     """
 
     def paginate(
-        self, *, jobID: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobLogItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobLogItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejoblogitemspaginator)
         """
 
+
 class DescribeJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejobspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeJobsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describejobspaginator)
         """
 
+
 class DescribeLaunchConfigurationTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeLaunchConfigurationTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describelaunchconfigurationtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         launchConfigurationTemplateIDs: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLaunchConfigurationTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeLaunchConfigurationTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describelaunchconfigurationtemplatespaginator)
         """
 
+
 class DescribeReplicationConfigurationTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeReplicationConfigurationTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describereplicationconfigurationtemplatespaginator)
     """
 
     def paginate(
         self,
         *,
         replicationConfigurationTemplateIDs: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeReplicationConfigurationTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeReplicationConfigurationTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describereplicationconfigurationtemplatespaginator)
         """
 
+
 class DescribeSourceServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeSourceServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describesourceserverspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: DescribeSourceServersRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSourceServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeSourceServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describesourceserverspaginator)
         """
 
+
 class DescribeVcenterClientsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeVcenterClients)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describevcenterclientspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeVcenterClientsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.DescribeVcenterClients.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#describevcenterclientspaginator)
         """
 
+
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listapplicationspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: ListApplicationsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listapplicationspaginator)
         """
 
+
+class ListExportErrorsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExportErrors)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexporterrorspaginator)
+    """
+
+    def paginate(
+        self, *, exportID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListExportErrorsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExportErrors.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexporterrorspaginator)
+        """
+
+
+class ListExportsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExports)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexportspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        filters: ListExportsRequestFiltersTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListExportsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListExports.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listexportspaginator)
+        """
+
+
+class ListImportErrorsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImportErrors)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimporterrorspaginator)
+    """
+
+    def paginate(
+        self, *, importID: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListImportErrorsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImportErrors.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimporterrorspaginator)
+        """
+
+
+class ListImportsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImports)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimportspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        filters: ListImportsRequestFiltersTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListImportsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListImports.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listimportspaginator)
+        """
+
+
 class ListSourceServerActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListSourceServerActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listsourceserveractionspaginator)
     """
 
     def paginate(
         self,
         *,
         sourceServerID: str,
         filters: SourceServerActionsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceServerActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListSourceServerActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listsourceserveractionspaginator)
         """
 
+
 class ListTemplateActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListTemplateActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listtemplateactionspaginator)
     """
 
     def paginate(
         self,
         *,
         launchConfigurationTemplateID: str,
         filters: TemplateActionsRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTemplateActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListTemplateActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listtemplateactionspaginator)
         """
 
+
 class ListWavesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListWaves)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listwavespaginator)
     """
 
     def paginate(
         self,
         *,
         filters: ListWavesRequestFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWavesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn.Paginator.ListWaves.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/paginators/#listwavespaginator)
         """
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/type_defs.py` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/type_defs.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -11,23 +11,27 @@
     data: ApplicationAggregatedStatusTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
+    ActionCategoryType,
     ApplicationHealthStatusType,
     ApplicationProgressStatusType,
     BootModeType,
     ChangeServerLifeCycleStateSourceServerLifecycleStateType,
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
+    ExportStatusType,
     FirstBootType,
+    ImportErrorTypeType,
+    ImportStatusType,
     InitiatedByType,
     JobLogEventType,
     JobStatusType,
     JobTypeType,
     LaunchDispositionType,
     LaunchStatusType,
     LifeCycleStateType,
@@ -50,18 +54,16 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ApplicationAggregatedStatusTypeDef",
-    "ResponseMetadataTypeDef",
     "ArchiveApplicationRequestRequestTypeDef",
     "ArchiveWaveRequestRequestTypeDef",
     "AssociateApplicationsRequestRequestTypeDef",
     "AssociateSourceServersRequestRequestTypeDef",
     "CPUTypeDef",
     "ChangeServerLifeCycleStateSourceServerLifecycleTypeDef",
     "CreateApplicationRequestRequestTypeDef",
@@ -75,87 +77,112 @@
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteJobRequestRequestTypeDef",
     "DeleteLaunchConfigurationTemplateRequestRequestTypeDef",
     "DeleteReplicationConfigurationTemplateRequestRequestTypeDef",
     "DeleteSourceServerRequestRequestTypeDef",
     "DeleteVcenterClientRequestRequestTypeDef",
     "DeleteWaveRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
     "DescribeJobLogItemsRequestRequestTypeDef",
     "DescribeJobsRequestFiltersTypeDef",
+    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
     "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
+    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
     "DescribeReplicationConfigurationTemplatesRequestRequestTypeDef",
     "ReplicationConfigurationTemplateTypeDef",
     "DescribeSourceServersRequestFiltersTypeDef",
+    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
     "DescribeVcenterClientsRequestRequestTypeDef",
     "VcenterClientTypeDef",
     "DisassociateApplicationsRequestRequestTypeDef",
     "DisassociateSourceServersRequestRequestTypeDef",
     "DisconnectFromServiceRequestRequestTypeDef",
     "DiskTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ExportErrorDataTypeDef",
+    "ExportTaskSummaryTypeDef",
     "FinalizeCutoverRequestRequestTypeDef",
     "GetLaunchConfigurationRequestRequestTypeDef",
     "GetReplicationConfigurationRequestRequestTypeDef",
     "IdentificationHintsTypeDef",
+    "ImportErrorDataTypeDef",
+    "ImportTaskSummaryApplicationsTypeDef",
+    "ImportTaskSummaryServersTypeDef",
+    "ImportTaskSummaryWavesTypeDef",
+    "S3BucketSourceTypeDef",
     "JobLogEventDataTypeDef",
     "LaunchedInstanceTypeDef",
     "LifeCycleLastCutoverFinalizedTypeDef",
     "LifeCycleLastCutoverInitiatedTypeDef",
     "LifeCycleLastCutoverRevertedTypeDef",
     "LifeCycleLastTestFinalizedTypeDef",
     "LifeCycleLastTestInitiatedTypeDef",
     "LifeCycleLastTestRevertedTypeDef",
     "ListApplicationsRequestFiltersTypeDef",
+    "ListExportErrorsRequestListExportErrorsPaginateTypeDef",
+    "ListExportErrorsRequestRequestTypeDef",
+    "ListExportsRequestFiltersTypeDef",
+    "ListImportErrorsRequestListImportErrorsPaginateTypeDef",
+    "ListImportErrorsRequestRequestTypeDef",
+    "ListImportsRequestFiltersTypeDef",
     "SourceServerActionsRequestFiltersTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TemplateActionsRequestFiltersTypeDef",
     "ListWavesRequestFiltersTypeDef",
     "MarkAsArchivedRequestRequestTypeDef",
     "NetworkInterfaceTypeDef",
     "OSTypeDef",
+    "PaginatorConfigTypeDef",
+    "SsmExternalParameterTypeDef",
     "SsmParameterStoreParameterTypeDef",
     "RemoveSourceServerActionRequestRequestTypeDef",
     "RemoveTemplateActionRequestRequestTypeDef",
     "ReplicationConfigurationReplicatedDiskTypeDef",
+    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryDataReplicationRequestRequestTypeDef",
     "StartCutoverRequestRequestTypeDef",
+    "StartExportRequestRequestTypeDef",
     "StartReplicationRequestRequestTypeDef",
     "StartTestRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TerminateTargetInstancesRequestRequestTypeDef",
     "UnarchiveApplicationRequestRequestTypeDef",
     "UnarchiveWaveRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     "UpdateSourceServerReplicationTypeRequestRequestTypeDef",
     "UpdateWaveRequestRequestTypeDef",
     "WaveAggregatedStatusTypeDef",
-    "ApplicationTypeDef",
     "ApplicationResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
+    "ApplicationTypeDef",
     "ChangeServerLifeCycleStateRequestRequestTypeDef",
     "DataReplicationInitiationTypeDef",
-    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
-    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
-    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
     "DescribeJobsRequestDescribeJobsPaginateTypeDef",
     "DescribeJobsRequestRequestTypeDef",
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     "DescribeSourceServersRequestRequestTypeDef",
     "DescribeVcenterClientsResponseTypeDef",
+    "ExportTaskErrorTypeDef",
+    "ExportTaskTypeDef",
+    "ImportTaskErrorTypeDef",
+    "ImportTaskSummaryTypeDef",
+    "StartImportRequestRequestTypeDef",
     "JobLogTypeDef",
     "LifeCycleLastCutoverTypeDef",
     "LifeCycleLastTestTypeDef",
     "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListExportsRequestListExportsPaginateTypeDef",
+    "ListExportsRequestRequestTypeDef",
+    "ListImportsRequestListImportsPaginateTypeDef",
+    "ListImportsRequestRequestTypeDef",
     "ListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef",
     "ListSourceServerActionsRequestRequestTypeDef",
     "ListTemplateActionsRequestListTemplateActionsPaginateTypeDef",
     "ListTemplateActionsRequestRequestTypeDef",
     "ListWavesRequestListWavesPaginateTypeDef",
     "ListWavesRequestRequestTypeDef",
     "SourcePropertiesTypeDef",
@@ -168,21 +195,28 @@
     "TemplateActionDocumentTypeDef",
     "ReplicationConfigurationTypeDef",
     "UpdateReplicationConfigurationRequestRequestTypeDef",
     "WaveResponseMetadataTypeDef",
     "WaveTypeDef",
     "ListApplicationsResponseTypeDef",
     "DataReplicationInfoTypeDef",
+    "ListExportErrorsResponseTypeDef",
+    "ListExportsResponseTypeDef",
+    "StartExportResponseTypeDef",
+    "ListImportErrorsResponseTypeDef",
+    "ImportTaskTypeDef",
     "DescribeJobLogItemsResponseTypeDef",
     "LifeCycleTypeDef",
     "ListSourceServerActionsResponseTypeDef",
     "JobPostLaunchActionsLaunchStatusTypeDef",
     "PostLaunchActionsTypeDef",
     "ListTemplateActionsResponseTypeDef",
     "ListWavesResponseTypeDef",
+    "ListImportsResponseTypeDef",
+    "StartImportResponseTypeDef",
     "SourceServerResponseMetadataTypeDef",
     "SourceServerTypeDef",
     "PostLaunchActionsStatusTypeDef",
     "CreateLaunchConfigurationTemplateRequestRequestTypeDef",
     "LaunchConfigurationTemplateResponseMetadataTypeDef",
     "LaunchConfigurationTemplateTypeDef",
     "LaunchConfigurationTypeDef",
@@ -205,25 +239,14 @@
         "lastUpdateDateTime": str,
         "progressStatus": ApplicationProgressStatusType,
         "totalSourceServers": int,
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
 ArchiveApplicationRequestRequestTypeDef = TypedDict(
     "ArchiveApplicationRequestRequestTypeDef",
     {
         "applicationID": str,
     },
 )
 
@@ -277,21 +300,19 @@
     {
         "description": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
-
 LaunchTemplateDiskConfTypeDef = TypedDict(
     "LaunchTemplateDiskConfTypeDef",
     {
         "iops": int,
         "throughput": int,
         "volumeType": VolumeTypeType,
     },
@@ -327,22 +348,20 @@
     {
         "ebsEncryptionKeyArn": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateReplicationConfigurationTemplateRequestRequestTypeDef(
     _RequiredCreateReplicationConfigurationTemplateRequestRequestTypeDef,
     _OptionalCreateReplicationConfigurationTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateWaveRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWaveRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateWaveRequestRequestTypeDef = TypedDict(
@@ -350,21 +369,19 @@
     {
         "description": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateWaveRequestRequestTypeDef(
     _RequiredCreateWaveRequestRequestTypeDef, _OptionalCreateWaveRequestRequestTypeDef
 ):
     pass
 
-
 DataReplicationErrorTypeDef = TypedDict(
     "DataReplicationErrorTypeDef",
     {
         "error": DataReplicationErrorStringType,
         "rawError": str,
     },
     total=False,
@@ -436,24 +453,34 @@
 DeleteWaveRequestRequestTypeDef = TypedDict(
     "DeleteWaveRequestRequestTypeDef",
     {
         "waveID": str,
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
@@ -461,42 +488,58 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class DescribeJobLogItemsRequestRequestTypeDef(
     _RequiredDescribeJobLogItemsRequestRequestTypeDef,
     _OptionalDescribeJobLogItemsRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeJobsRequestFiltersTypeDef = TypedDict(
     "DescribeJobsRequestFiltersTypeDef",
     {
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
 DescribeLaunchConfigurationTemplatesRequestRequestTypeDef = TypedDict(
     "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
     {
         "launchConfigurationTemplateIDs": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
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
@@ -526,34 +569,40 @@
         "stagingAreaTags": Dict[str, str],
         "tags": Dict[str, str],
         "useDedicatedReplicationServer": bool,
     },
     total=False,
 )
 
-
 class ReplicationConfigurationTemplateTypeDef(
     _RequiredReplicationConfigurationTemplateTypeDef,
     _OptionalReplicationConfigurationTemplateTypeDef,
 ):
     pass
 
-
 DescribeSourceServersRequestFiltersTypeDef = TypedDict(
     "DescribeSourceServersRequestFiltersTypeDef",
     {
         "applicationIDs": Sequence[str],
         "isArchived": bool,
         "lifeCycleStates": Sequence[LifeCycleStateType],
         "replicationTypes": Sequence[ReplicationTypeType],
         "sourceServerIDs": Sequence[str],
     },
     total=False,
 )
 
+DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef = TypedDict(
+    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeVcenterClientsRequestRequestTypeDef = TypedDict(
     "DescribeVcenterClientsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -602,14 +651,39 @@
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
+ExportErrorDataTypeDef = TypedDict(
+    "ExportErrorDataTypeDef",
+    {
+        "rawError": str,
+    },
+    total=False,
+)
+
+ExportTaskSummaryTypeDef = TypedDict(
+    "ExportTaskSummaryTypeDef",
+    {
+        "applicationsCount": int,
+        "serversCount": int,
+        "wavesCount": int,
+    },
+    total=False,
+)
+
 FinalizeCutoverRequestRequestTypeDef = TypedDict(
     "FinalizeCutoverRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
@@ -635,14 +709,72 @@
         "hostname": str,
         "vmPath": str,
         "vmWareUuid": str,
     },
     total=False,
 )
 
+ImportErrorDataTypeDef = TypedDict(
+    "ImportErrorDataTypeDef",
+    {
+        "applicationID": str,
+        "ec2LaunchTemplateID": str,
+        "rawError": str,
+        "rowNumber": int,
+        "sourceServerID": str,
+        "waveID": str,
+    },
+    total=False,
+)
+
+ImportTaskSummaryApplicationsTypeDef = TypedDict(
+    "ImportTaskSummaryApplicationsTypeDef",
+    {
+        "createdCount": int,
+        "modifiedCount": int,
+    },
+    total=False,
+)
+
+ImportTaskSummaryServersTypeDef = TypedDict(
+    "ImportTaskSummaryServersTypeDef",
+    {
+        "createdCount": int,
+        "modifiedCount": int,
+    },
+    total=False,
+)
+
+ImportTaskSummaryWavesTypeDef = TypedDict(
+    "ImportTaskSummaryWavesTypeDef",
+    {
+        "createdCount": int,
+        "modifiedCount": int,
+    },
+    total=False,
+)
+
+_RequiredS3BucketSourceTypeDef = TypedDict(
+    "_RequiredS3BucketSourceTypeDef",
+    {
+        "s3Bucket": str,
+        "s3Key": str,
+    },
+)
+_OptionalS3BucketSourceTypeDef = TypedDict(
+    "_OptionalS3BucketSourceTypeDef",
+    {
+        "s3BucketOwner": str,
+    },
+    total=False,
+)
+
+class S3BucketSourceTypeDef(_RequiredS3BucketSourceTypeDef, _OptionalS3BucketSourceTypeDef):
+    pass
+
 JobLogEventDataTypeDef = TypedDict(
     "JobLogEventDataTypeDef",
     {
         "conversionServerID": str,
         "rawError": str,
         "sourceServerID": str,
         "targetInstanceID": str,
@@ -716,14 +848,110 @@
         "applicationIDs": Sequence[str],
         "isArchived": bool,
         "waveIDs": Sequence[str],
     },
     total=False,
 )
 
+_RequiredListExportErrorsRequestListExportErrorsPaginateTypeDef = TypedDict(
+    "_RequiredListExportErrorsRequestListExportErrorsPaginateTypeDef",
+    {
+        "exportID": str,
+    },
+)
+_OptionalListExportErrorsRequestListExportErrorsPaginateTypeDef = TypedDict(
+    "_OptionalListExportErrorsRequestListExportErrorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListExportErrorsRequestListExportErrorsPaginateTypeDef(
+    _RequiredListExportErrorsRequestListExportErrorsPaginateTypeDef,
+    _OptionalListExportErrorsRequestListExportErrorsPaginateTypeDef,
+):
+    pass
+
+_RequiredListExportErrorsRequestRequestTypeDef = TypedDict(
+    "_RequiredListExportErrorsRequestRequestTypeDef",
+    {
+        "exportID": str,
+    },
+)
+_OptionalListExportErrorsRequestRequestTypeDef = TypedDict(
+    "_OptionalListExportErrorsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+class ListExportErrorsRequestRequestTypeDef(
+    _RequiredListExportErrorsRequestRequestTypeDef, _OptionalListExportErrorsRequestRequestTypeDef
+):
+    pass
+
+ListExportsRequestFiltersTypeDef = TypedDict(
+    "ListExportsRequestFiltersTypeDef",
+    {
+        "exportIDs": Sequence[str],
+    },
+    total=False,
+)
+
+_RequiredListImportErrorsRequestListImportErrorsPaginateTypeDef = TypedDict(
+    "_RequiredListImportErrorsRequestListImportErrorsPaginateTypeDef",
+    {
+        "importID": str,
+    },
+)
+_OptionalListImportErrorsRequestListImportErrorsPaginateTypeDef = TypedDict(
+    "_OptionalListImportErrorsRequestListImportErrorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListImportErrorsRequestListImportErrorsPaginateTypeDef(
+    _RequiredListImportErrorsRequestListImportErrorsPaginateTypeDef,
+    _OptionalListImportErrorsRequestListImportErrorsPaginateTypeDef,
+):
+    pass
+
+_RequiredListImportErrorsRequestRequestTypeDef = TypedDict(
+    "_RequiredListImportErrorsRequestRequestTypeDef",
+    {
+        "importID": str,
+    },
+)
+_OptionalListImportErrorsRequestRequestTypeDef = TypedDict(
+    "_OptionalListImportErrorsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+class ListImportErrorsRequestRequestTypeDef(
+    _RequiredListImportErrorsRequestRequestTypeDef, _OptionalListImportErrorsRequestRequestTypeDef
+):
+    pass
+
+ListImportsRequestFiltersTypeDef = TypedDict(
+    "ListImportsRequestFiltersTypeDef",
+    {
+        "importIDs": Sequence[str],
+    },
+    total=False,
+)
+
 SourceServerActionsRequestFiltersTypeDef = TypedDict(
     "SourceServerActionsRequestFiltersTypeDef",
     {
         "actionIDs": Sequence[str],
     },
     total=False,
 )
@@ -731,14 +959,22 @@
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
 TemplateActionsRequestFiltersTypeDef = TypedDict(
     "TemplateActionsRequestFiltersTypeDef",
     {
         "actionIDs": Sequence[str],
     },
     total=False,
 )
@@ -773,14 +1009,32 @@
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
+SsmExternalParameterTypeDef = TypedDict(
+    "SsmExternalParameterTypeDef",
+    {
+        "dynamicPath": str,
+    },
+    total=False,
+)
+
 SsmParameterStoreParameterTypeDef = TypedDict(
     "SsmParameterStoreParameterTypeDef",
     {
         "parameterName": str,
         "parameterType": Literal["STRING"],
     },
 )
@@ -809,14 +1063,47 @@
         "isBootDisk": bool,
         "stagingDiskType": ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
         "throughput": int,
     },
     total=False,
 )
 
+ReplicationConfigurationTemplateResponseMetadataTypeDef = TypedDict(
+    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
+    {
+        "arn": str,
+        "associateDefaultSecurityGroup": bool,
+        "bandwidthThrottling": int,
+        "createPublicIP": bool,
+        "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
+        "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
+        "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
+        "ebsEncryptionKeyArn": str,
+        "replicationConfigurationTemplateID": str,
+        "replicationServerInstanceType": str,
+        "replicationServersSecurityGroupsIDs": List[str],
+        "stagingAreaSubnetId": str,
+        "stagingAreaTags": Dict[str, str],
+        "tags": Dict[str, str],
+        "useDedicatedReplicationServer": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 
@@ -830,20 +1117,38 @@
     "_OptionalStartCutoverRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class StartCutoverRequestRequestTypeDef(
     _RequiredStartCutoverRequestRequestTypeDef, _OptionalStartCutoverRequestRequestTypeDef
 ):
     pass
 
+_RequiredStartExportRequestRequestTypeDef = TypedDict(
+    "_RequiredStartExportRequestRequestTypeDef",
+    {
+        "s3Bucket": str,
+        "s3Key": str,
+    },
+)
+_OptionalStartExportRequestRequestTypeDef = TypedDict(
+    "_OptionalStartExportRequestRequestTypeDef",
+    {
+        "s3BucketOwner": str,
+    },
+    total=False,
+)
+
+class StartExportRequestRequestTypeDef(
+    _RequiredStartExportRequestRequestTypeDef, _OptionalStartExportRequestRequestTypeDef
+):
+    pass
 
 StartReplicationRequestRequestTypeDef = TypedDict(
     "StartReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
@@ -858,21 +1163,19 @@
     "_OptionalStartTestRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class StartTestRequestRequestTypeDef(
     _RequiredStartTestRequestRequestTypeDef, _OptionalStartTestRequestRequestTypeDef
 ):
     pass
 
-
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -887,22 +1190,20 @@
     "_OptionalTerminateTargetInstancesRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class TerminateTargetInstancesRequestRequestTypeDef(
     _RequiredTerminateTargetInstancesRequestRequestTypeDef,
     _OptionalTerminateTargetInstancesRequestRequestTypeDef,
 ):
     pass
 
-
 UnarchiveApplicationRequestRequestTypeDef = TypedDict(
     "UnarchiveApplicationRequestRequestTypeDef",
     {
         "applicationID": str,
     },
 )
 
@@ -932,21 +1233,19 @@
     {
         "description": str,
         "name": str,
     },
     total=False,
 )
 
-
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "replicationConfigurationTemplateID": str,
     },
 )
 _OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
@@ -965,22 +1264,20 @@
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Mapping[str, str],
         "useDedicatedReplicationServer": bool,
     },
     total=False,
 )
 
-
 class UpdateReplicationConfigurationTemplateRequestRequestTypeDef(
     _RequiredUpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     _OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateSourceServerReplicationTypeRequestRequestTypeDef = TypedDict(
     "UpdateSourceServerReplicationTypeRequestRequestTypeDef",
     {
         "replicationType": ReplicationTypeType,
         "sourceServerID": str,
     },
 )
@@ -996,102 +1293,63 @@
     {
         "description": str,
         "name": str,
     },
     total=False,
 )
 
-
 class UpdateWaveRequestRequestTypeDef(
     _RequiredUpdateWaveRequestRequestTypeDef, _OptionalUpdateWaveRequestRequestTypeDef
 ):
     pass
 
-
 WaveAggregatedStatusTypeDef = TypedDict(
     "WaveAggregatedStatusTypeDef",
     {
         "healthStatus": WaveHealthStatusType,
         "lastUpdateDateTime": str,
         "progressStatus": WaveProgressStatusType,
         "replicationStartedDateTime": str,
         "totalApplications": int,
     },
     total=False,
 )
 
-ApplicationTypeDef = TypedDict(
-    "ApplicationTypeDef",
+ApplicationResponseMetadataTypeDef = TypedDict(
+    "ApplicationResponseMetadataTypeDef",
     {
         "applicationAggregatedStatus": ApplicationAggregatedStatusTypeDef,
         "applicationID": str,
         "arn": str,
         "creationDateTime": str,
         "description": str,
         "isArchived": bool,
         "lastModifiedDateTime": str,
         "name": str,
         "tags": Dict[str, str],
         "waveID": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ApplicationResponseMetadataTypeDef = TypedDict(
-    "ApplicationResponseMetadataTypeDef",
+ApplicationTypeDef = TypedDict(
+    "ApplicationTypeDef",
     {
         "applicationAggregatedStatus": ApplicationAggregatedStatusTypeDef,
         "applicationID": str,
         "arn": str,
         "creationDateTime": str,
         "description": str,
         "isArchived": bool,
         "lastModifiedDateTime": str,
         "name": str,
         "tags": Dict[str, str],
         "waveID": str,
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReplicationConfigurationTemplateResponseMetadataTypeDef = TypedDict(
-    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
-    {
-        "arn": str,
-        "associateDefaultSecurityGroup": bool,
-        "bandwidthThrottling": int,
-        "createPublicIP": bool,
-        "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
-        "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
-        "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
-        "ebsEncryptionKeyArn": str,
-        "replicationConfigurationTemplateID": str,
-        "replicationServerInstanceType": str,
-        "replicationServersSecurityGroupsIDs": List[str],
-        "stagingAreaSubnetId": str,
-        "stagingAreaTags": Dict[str, str],
-        "tags": Dict[str, str],
-        "useDedicatedReplicationServer": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
 ChangeServerLifeCycleStateRequestRequestTypeDef = TypedDict(
     "ChangeServerLifeCycleStateRequestRequestTypeDef",
     {
         "lifeCycle": ChangeServerLifeCycleStateSourceServerLifecycleTypeDef,
         "sourceServerID": str,
@@ -1104,67 +1362,19 @@
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
-DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef = TypedDict(
-    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
-    {
-        "launchConfigurationTemplateIDs": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
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
-DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef = TypedDict(
-    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
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
@@ -1176,23 +1386,23 @@
 )
 
 DescribeReplicationConfigurationTemplatesResponseTypeDef = TypedDict(
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     {
         "items": List[ReplicationConfigurationTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef = TypedDict(
     "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     {
         "filters": DescribeSourceServersRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeSourceServersRequestRequestTypeDef = TypedDict(
     "DescribeSourceServersRequestRequestTypeDef",
     {
@@ -1204,18 +1414,82 @@
 )
 
 DescribeVcenterClientsResponseTypeDef = TypedDict(
     "DescribeVcenterClientsResponseTypeDef",
     {
         "items": List[VcenterClientTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ExportTaskErrorTypeDef = TypedDict(
+    "ExportTaskErrorTypeDef",
+    {
+        "errorData": ExportErrorDataTypeDef,
+        "errorDateTime": str,
     },
+    total=False,
+)
+
+ExportTaskTypeDef = TypedDict(
+    "ExportTaskTypeDef",
+    {
+        "creationDateTime": str,
+        "endDateTime": str,
+        "exportID": str,
+        "progressPercentage": float,
+        "s3Bucket": str,
+        "s3BucketOwner": str,
+        "s3Key": str,
+        "status": ExportStatusType,
+        "summary": ExportTaskSummaryTypeDef,
+    },
+    total=False,
+)
+
+ImportTaskErrorTypeDef = TypedDict(
+    "ImportTaskErrorTypeDef",
+    {
+        "errorData": ImportErrorDataTypeDef,
+        "errorDateTime": str,
+        "errorType": ImportErrorTypeType,
+    },
+    total=False,
+)
+
+ImportTaskSummaryTypeDef = TypedDict(
+    "ImportTaskSummaryTypeDef",
+    {
+        "applications": ImportTaskSummaryApplicationsTypeDef,
+        "servers": ImportTaskSummaryServersTypeDef,
+        "waves": ImportTaskSummaryWavesTypeDef,
+    },
+    total=False,
 )
 
+_RequiredStartImportRequestRequestTypeDef = TypedDict(
+    "_RequiredStartImportRequestRequestTypeDef",
+    {
+        "s3BucketSource": S3BucketSourceTypeDef,
+    },
+)
+_OptionalStartImportRequestRequestTypeDef = TypedDict(
+    "_OptionalStartImportRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+class StartImportRequestRequestTypeDef(
+    _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
+):
+    pass
+
 JobLogTypeDef = TypedDict(
     "JobLogTypeDef",
     {
         "event": JobLogEventType,
         "eventData": JobLogEventDataTypeDef,
         "logDateTime": str,
     },
@@ -1242,52 +1516,88 @@
     total=False,
 )
 
 ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
     "ListApplicationsRequestListApplicationsPaginateTypeDef",
     {
         "filters": ListApplicationsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "filters": ListApplicationsRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListExportsRequestListExportsPaginateTypeDef = TypedDict(
+    "ListExportsRequestListExportsPaginateTypeDef",
+    {
+        "filters": ListExportsRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListExportsRequestRequestTypeDef = TypedDict(
+    "ListExportsRequestRequestTypeDef",
+    {
+        "filters": ListExportsRequestFiltersTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+ListImportsRequestListImportsPaginateTypeDef = TypedDict(
+    "ListImportsRequestListImportsPaginateTypeDef",
+    {
+        "filters": ListImportsRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListImportsRequestRequestTypeDef = TypedDict(
+    "ListImportsRequestRequestTypeDef",
+    {
+        "filters": ListImportsRequestFiltersTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 _RequiredListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef = TypedDict(
     "_RequiredListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef",
     {
         "sourceServerID": str,
     },
 )
 _OptionalListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef = TypedDict(
     "_OptionalListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef",
     {
         "filters": SourceServerActionsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef(
     _RequiredListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef,
     _OptionalListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListSourceServerActionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSourceServerActionsRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 _OptionalListSourceServerActionsRequestRequestTypeDef = TypedDict(
@@ -1296,45 +1606,41 @@
         "filters": SourceServerActionsRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListSourceServerActionsRequestRequestTypeDef(
     _RequiredListSourceServerActionsRequestRequestTypeDef,
     _OptionalListSourceServerActionsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListTemplateActionsRequestListTemplateActionsPaginateTypeDef = TypedDict(
     "_RequiredListTemplateActionsRequestListTemplateActionsPaginateTypeDef",
     {
         "launchConfigurationTemplateID": str,
     },
 )
 _OptionalListTemplateActionsRequestListTemplateActionsPaginateTypeDef = TypedDict(
     "_OptionalListTemplateActionsRequestListTemplateActionsPaginateTypeDef",
     {
         "filters": TemplateActionsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListTemplateActionsRequestListTemplateActionsPaginateTypeDef(
     _RequiredListTemplateActionsRequestListTemplateActionsPaginateTypeDef,
     _OptionalListTemplateActionsRequestListTemplateActionsPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListTemplateActionsRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplateActionsRequestRequestTypeDef",
     {
         "launchConfigurationTemplateID": str,
     },
 )
 _OptionalListTemplateActionsRequestRequestTypeDef = TypedDict(
@@ -1343,27 +1649,25 @@
         "filters": TemplateActionsRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListTemplateActionsRequestRequestTypeDef(
     _RequiredListTemplateActionsRequestRequestTypeDef,
     _OptionalListTemplateActionsRequestRequestTypeDef,
 ):
     pass
 
-
 ListWavesRequestListWavesPaginateTypeDef = TypedDict(
     "ListWavesRequestListWavesPaginateTypeDef",
     {
         "filters": ListWavesRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListWavesRequestRequestTypeDef = TypedDict(
     "ListWavesRequestRequestTypeDef",
     {
@@ -1399,84 +1703,92 @@
         "sourceServerID": str,
     },
 )
 _OptionalPutSourceServerActionRequestRequestTypeDef = TypedDict(
     "_OptionalPutSourceServerActionRequestRequestTypeDef",
     {
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentVersion": str,
+        "externalParameters": Mapping[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "parameters": Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
 
-
 class PutSourceServerActionRequestRequestTypeDef(
     _RequiredPutSourceServerActionRequestRequestTypeDef,
     _OptionalPutSourceServerActionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredPutTemplateActionRequestRequestTypeDef = TypedDict(
     "_RequiredPutTemplateActionRequestRequestTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "documentIdentifier": str,
         "launchConfigurationTemplateID": str,
         "order": int,
     },
 )
 _OptionalPutTemplateActionRequestRequestTypeDef = TypedDict(
     "_OptionalPutTemplateActionRequestRequestTypeDef",
     {
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentVersion": str,
+        "externalParameters": Mapping[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "operatingSystem": str,
         "parameters": Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
 
-
 class PutTemplateActionRequestRequestTypeDef(
     _RequiredPutTemplateActionRequestRequestTypeDef, _OptionalPutTemplateActionRequestRequestTypeDef
 ):
     pass
 
-
 SourceServerActionDocumentResponseMetadataTypeDef = TypedDict(
     "SourceServerActionDocumentResponseMetadataTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerActionDocumentTypeDef = TypedDict(
     "SourceServerActionDocumentTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
@@ -1487,51 +1799,56 @@
         "actionName": str,
         "ssmDocumentName": str,
     },
 )
 _OptionalSsmDocumentTypeDef = TypedDict(
     "_OptionalSsmDocumentTypeDef",
     {
+        "externalParameters": Mapping[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "parameters": Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
 
-
 class SsmDocumentTypeDef(_RequiredSsmDocumentTypeDef, _OptionalSsmDocumentTypeDef):
     pass
 
-
 TemplateActionDocumentResponseMetadataTypeDef = TypedDict(
     "TemplateActionDocumentResponseMetadataTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "operatingSystem": str,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TemplateActionDocumentTypeDef = TypedDict(
     "TemplateActionDocumentTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "operatingSystem": str,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
@@ -1551,15 +1868,15 @@
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
@@ -1582,35 +1899,33 @@
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Mapping[str, str],
         "useDedicatedReplicationServer": bool,
     },
     total=False,
 )
 
-
 class UpdateReplicationConfigurationRequestRequestTypeDef(
     _RequiredUpdateReplicationConfigurationRequestRequestTypeDef,
     _OptionalUpdateReplicationConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 WaveResponseMetadataTypeDef = TypedDict(
     "WaveResponseMetadataTypeDef",
     {
         "arn": str,
         "creationDateTime": str,
         "description": str,
         "isArchived": bool,
         "lastModifiedDateTime": str,
         "name": str,
         "tags": Dict[str, str],
         "waveAggregatedStatus": WaveAggregatedStatusTypeDef,
         "waveID": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WaveTypeDef = TypedDict(
     "WaveTypeDef",
     {
         "arn": str,
@@ -1627,15 +1942,15 @@
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "items": List[ApplicationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataReplicationInfoTypeDef = TypedDict(
     "DataReplicationInfoTypeDef",
     {
         "dataReplicationError": DataReplicationErrorTypeDef,
@@ -1645,20 +1960,69 @@
         "lagDuration": str,
         "lastSnapshotDateTime": str,
         "replicatedDisks": List[DataReplicationInfoReplicatedDiskTypeDef],
     },
     total=False,
 )
 
+ListExportErrorsResponseTypeDef = TypedDict(
+    "ListExportErrorsResponseTypeDef",
+    {
+        "items": List[ExportTaskErrorTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListExportsResponseTypeDef = TypedDict(
+    "ListExportsResponseTypeDef",
+    {
+        "items": List[ExportTaskTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartExportResponseTypeDef = TypedDict(
+    "StartExportResponseTypeDef",
+    {
+        "exportTask": ExportTaskTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImportErrorsResponseTypeDef = TypedDict(
+    "ListImportErrorsResponseTypeDef",
+    {
+        "items": List[ImportTaskErrorTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ImportTaskTypeDef = TypedDict(
+    "ImportTaskTypeDef",
+    {
+        "creationDateTime": str,
+        "endDateTime": str,
+        "importID": str,
+        "progressPercentage": float,
+        "s3BucketSource": S3BucketSourceTypeDef,
+        "status": ImportStatusType,
+        "summary": ImportTaskSummaryTypeDef,
+    },
+    total=False,
+)
+
 DescribeJobLogItemsResponseTypeDef = TypedDict(
     "DescribeJobLogItemsResponseTypeDef",
     {
         "items": List[JobLogTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifeCycleTypeDef = TypedDict(
     "LifeCycleTypeDef",
     {
         "addedToServiceDateTime": str,
@@ -1673,15 +2037,15 @@
 )
 
 ListSourceServerActionsResponseTypeDef = TypedDict(
     "ListSourceServerActionsResponseTypeDef",
     {
         "items": List[SourceServerActionDocumentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobPostLaunchActionsLaunchStatusTypeDef = TypedDict(
     "JobPostLaunchActionsLaunchStatusTypeDef",
     {
         "executionID": str,
@@ -1706,58 +2070,79 @@
 )
 
 ListTemplateActionsResponseTypeDef = TypedDict(
     "ListTemplateActionsResponseTypeDef",
     {
         "items": List[TemplateActionDocumentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWavesResponseTypeDef = TypedDict(
     "ListWavesResponseTypeDef",
     {
         "items": List[WaveTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImportsResponseTypeDef = TypedDict(
+    "ListImportsResponseTypeDef",
+    {
+        "items": List[ImportTaskTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartImportResponseTypeDef = TypedDict(
+    "StartImportResponseTypeDef",
+    {
+        "importTask": ImportTaskTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerResponseMetadataTypeDef = TypedDict(
     "SourceServerResponseMetadataTypeDef",
     {
         "applicationID": str,
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
+        "fqdnForActionFramework": str,
         "isArchived": bool,
         "launchedInstance": LaunchedInstanceTypeDef,
         "lifeCycle": LifeCycleTypeDef,
         "replicationType": ReplicationTypeType,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "tags": Dict[str, str],
+        "userProvidedID": str,
         "vcenterClientID": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerTypeDef = TypedDict(
     "SourceServerTypeDef",
     {
         "applicationID": str,
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
+        "fqdnForActionFramework": str,
         "isArchived": bool,
         "launchedInstance": LaunchedInstanceTypeDef,
         "lifeCycle": LifeCycleTypeDef,
         "replicationType": ReplicationTypeType,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "tags": Dict[str, str],
+        "userProvidedID": str,
         "vcenterClientID": str,
     },
     total=False,
 )
 
 PostLaunchActionsStatusTypeDef = TypedDict(
     "PostLaunchActionsStatusTypeDef",
@@ -1805,15 +2190,15 @@
         "licensing": LicensingTypeDef,
         "mapAutoTaggingMpeID": str,
         "postLaunchActions": PostLaunchActionsTypeDef,
         "smallVolumeConf": LaunchTemplateDiskConfTypeDef,
         "smallVolumeMaxSize": int,
         "tags": Dict[str, str],
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLaunchConfigurationTemplateTypeDef = TypedDict(
     "_RequiredLaunchConfigurationTemplateTypeDef",
     {
         "launchConfigurationTemplateID": str,
@@ -1838,21 +2223,19 @@
         "smallVolumeMaxSize": int,
         "tags": Dict[str, str],
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
-
 class LaunchConfigurationTemplateTypeDef(
     _RequiredLaunchConfigurationTemplateTypeDef, _OptionalLaunchConfigurationTemplateTypeDef
 ):
     pass
 
-
 LaunchConfigurationTypeDef = TypedDict(
     "LaunchConfigurationTypeDef",
     {
         "bootMode": BootModeType,
         "copyPrivateIp": bool,
         "copyTags": bool,
         "ec2LaunchTemplateID": str,
@@ -1860,15 +2243,15 @@
         "launchDisposition": LaunchDispositionType,
         "licensing": LicensingTypeDef,
         "mapAutoTaggingMpeID": str,
         "name": str,
         "postLaunchActions": PostLaunchActionsTypeDef,
         "sourceServerID": str,
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLaunchConfigurationRequestRequestTypeDef",
     {
         "sourceServerID": str,
@@ -1887,22 +2270,20 @@
         "name": str,
         "postLaunchActions": PostLaunchActionsTypeDef,
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
-
 class UpdateLaunchConfigurationRequestRequestTypeDef(
     _RequiredUpdateLaunchConfigurationRequestRequestTypeDef,
     _OptionalUpdateLaunchConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef",
     {
         "launchConfigurationTemplateID": str,
     },
 )
 _OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
@@ -1921,28 +2302,26 @@
         "smallVolumeConf": LaunchTemplateDiskConfTypeDef,
         "smallVolumeMaxSize": int,
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
-
 class UpdateLaunchConfigurationTemplateRequestRequestTypeDef(
     _RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
     _OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeSourceServersResponseTypeDef = TypedDict(
     "DescribeSourceServersResponseTypeDef",
     {
         "items": List[SourceServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredParticipatingServerTypeDef = TypedDict(
     "_RequiredParticipatingServerTypeDef",
     {
         "sourceServerID": str,
@@ -1954,27 +2333,25 @@
         "launchStatus": LaunchStatusType,
         "launchedEc2InstanceID": str,
         "postLaunchActionsStatus": PostLaunchActionsStatusTypeDef,
     },
     total=False,
 )
 
-
 class ParticipatingServerTypeDef(
     _RequiredParticipatingServerTypeDef, _OptionalParticipatingServerTypeDef
 ):
     pass
 
-
 DescribeLaunchConfigurationTemplatesResponseTypeDef = TypedDict(
     "DescribeLaunchConfigurationTemplatesResponseTypeDef",
     {
         "items": List[LaunchConfigurationTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJobTypeDef = TypedDict(
     "_RequiredJobTypeDef",
     {
         "jobID": str,
@@ -1991,44 +2368,42 @@
         "status": JobStatusType,
         "tags": Dict[str, str],
         "type": JobTypeType,
     },
     total=False,
 )
 
-
 class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
     pass
 
-
 DescribeJobsResponseTypeDef = TypedDict(
     "DescribeJobsResponseTypeDef",
     {
         "items": List[JobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartCutoverResponseTypeDef = TypedDict(
     "StartCutoverResponseTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTestResponseTypeDef = TypedDict(
     "StartTestResponseTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TerminateTargetInstancesResponseTypeDef = TypedDict(
     "TerminateTargetInstancesResponseTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn/type_defs.pyi` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -11,23 +11,27 @@
     data: ApplicationAggregatedStatusTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
+    ActionCategoryType,
     ApplicationHealthStatusType,
     ApplicationProgressStatusType,
     BootModeType,
     ChangeServerLifeCycleStateSourceServerLifecycleStateType,
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
+    ExportStatusType,
     FirstBootType,
+    ImportErrorTypeType,
+    ImportStatusType,
     InitiatedByType,
     JobLogEventType,
     JobStatusType,
     JobTypeType,
     LaunchDispositionType,
     LaunchStatusType,
     LifeCycleStateType,
@@ -50,17 +54,17 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ApplicationAggregatedStatusTypeDef",
-    "ResponseMetadataTypeDef",
     "ArchiveApplicationRequestRequestTypeDef",
     "ArchiveWaveRequestRequestTypeDef",
     "AssociateApplicationsRequestRequestTypeDef",
     "AssociateSourceServersRequestRequestTypeDef",
     "CPUTypeDef",
     "ChangeServerLifeCycleStateSourceServerLifecycleTypeDef",
     "CreateApplicationRequestRequestTypeDef",
@@ -74,87 +78,112 @@
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteJobRequestRequestTypeDef",
     "DeleteLaunchConfigurationTemplateRequestRequestTypeDef",
     "DeleteReplicationConfigurationTemplateRequestRequestTypeDef",
     "DeleteSourceServerRequestRequestTypeDef",
     "DeleteVcenterClientRequestRequestTypeDef",
     "DeleteWaveRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
     "DescribeJobLogItemsRequestRequestTypeDef",
     "DescribeJobsRequestFiltersTypeDef",
+    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
     "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
+    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
     "DescribeReplicationConfigurationTemplatesRequestRequestTypeDef",
     "ReplicationConfigurationTemplateTypeDef",
     "DescribeSourceServersRequestFiltersTypeDef",
+    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
     "DescribeVcenterClientsRequestRequestTypeDef",
     "VcenterClientTypeDef",
     "DisassociateApplicationsRequestRequestTypeDef",
     "DisassociateSourceServersRequestRequestTypeDef",
     "DisconnectFromServiceRequestRequestTypeDef",
     "DiskTypeDef",
+    "EmptyResponseMetadataTypeDef",
+    "ExportErrorDataTypeDef",
+    "ExportTaskSummaryTypeDef",
     "FinalizeCutoverRequestRequestTypeDef",
     "GetLaunchConfigurationRequestRequestTypeDef",
     "GetReplicationConfigurationRequestRequestTypeDef",
     "IdentificationHintsTypeDef",
+    "ImportErrorDataTypeDef",
+    "ImportTaskSummaryApplicationsTypeDef",
+    "ImportTaskSummaryServersTypeDef",
+    "ImportTaskSummaryWavesTypeDef",
+    "S3BucketSourceTypeDef",
     "JobLogEventDataTypeDef",
     "LaunchedInstanceTypeDef",
     "LifeCycleLastCutoverFinalizedTypeDef",
     "LifeCycleLastCutoverInitiatedTypeDef",
     "LifeCycleLastCutoverRevertedTypeDef",
     "LifeCycleLastTestFinalizedTypeDef",
     "LifeCycleLastTestInitiatedTypeDef",
     "LifeCycleLastTestRevertedTypeDef",
     "ListApplicationsRequestFiltersTypeDef",
+    "ListExportErrorsRequestListExportErrorsPaginateTypeDef",
+    "ListExportErrorsRequestRequestTypeDef",
+    "ListExportsRequestFiltersTypeDef",
+    "ListImportErrorsRequestListImportErrorsPaginateTypeDef",
+    "ListImportErrorsRequestRequestTypeDef",
+    "ListImportsRequestFiltersTypeDef",
     "SourceServerActionsRequestFiltersTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TemplateActionsRequestFiltersTypeDef",
     "ListWavesRequestFiltersTypeDef",
     "MarkAsArchivedRequestRequestTypeDef",
     "NetworkInterfaceTypeDef",
     "OSTypeDef",
+    "PaginatorConfigTypeDef",
+    "SsmExternalParameterTypeDef",
     "SsmParameterStoreParameterTypeDef",
     "RemoveSourceServerActionRequestRequestTypeDef",
     "RemoveTemplateActionRequestRequestTypeDef",
     "ReplicationConfigurationReplicatedDiskTypeDef",
+    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryDataReplicationRequestRequestTypeDef",
     "StartCutoverRequestRequestTypeDef",
+    "StartExportRequestRequestTypeDef",
     "StartReplicationRequestRequestTypeDef",
     "StartTestRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TerminateTargetInstancesRequestRequestTypeDef",
     "UnarchiveApplicationRequestRequestTypeDef",
     "UnarchiveWaveRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     "UpdateSourceServerReplicationTypeRequestRequestTypeDef",
     "UpdateWaveRequestRequestTypeDef",
     "WaveAggregatedStatusTypeDef",
-    "ApplicationTypeDef",
     "ApplicationResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
+    "ApplicationTypeDef",
     "ChangeServerLifeCycleStateRequestRequestTypeDef",
     "DataReplicationInitiationTypeDef",
-    "DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef",
-    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
-    "DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef",
-    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
     "DescribeJobsRequestDescribeJobsPaginateTypeDef",
     "DescribeJobsRequestRequestTypeDef",
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     "DescribeSourceServersRequestRequestTypeDef",
     "DescribeVcenterClientsResponseTypeDef",
+    "ExportTaskErrorTypeDef",
+    "ExportTaskTypeDef",
+    "ImportTaskErrorTypeDef",
+    "ImportTaskSummaryTypeDef",
+    "StartImportRequestRequestTypeDef",
     "JobLogTypeDef",
     "LifeCycleLastCutoverTypeDef",
     "LifeCycleLastTestTypeDef",
     "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "ListExportsRequestListExportsPaginateTypeDef",
+    "ListExportsRequestRequestTypeDef",
+    "ListImportsRequestListImportsPaginateTypeDef",
+    "ListImportsRequestRequestTypeDef",
     "ListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef",
     "ListSourceServerActionsRequestRequestTypeDef",
     "ListTemplateActionsRequestListTemplateActionsPaginateTypeDef",
     "ListTemplateActionsRequestRequestTypeDef",
     "ListWavesRequestListWavesPaginateTypeDef",
     "ListWavesRequestRequestTypeDef",
     "SourcePropertiesTypeDef",
@@ -167,21 +196,28 @@
     "TemplateActionDocumentTypeDef",
     "ReplicationConfigurationTypeDef",
     "UpdateReplicationConfigurationRequestRequestTypeDef",
     "WaveResponseMetadataTypeDef",
     "WaveTypeDef",
     "ListApplicationsResponseTypeDef",
     "DataReplicationInfoTypeDef",
+    "ListExportErrorsResponseTypeDef",
+    "ListExportsResponseTypeDef",
+    "StartExportResponseTypeDef",
+    "ListImportErrorsResponseTypeDef",
+    "ImportTaskTypeDef",
     "DescribeJobLogItemsResponseTypeDef",
     "LifeCycleTypeDef",
     "ListSourceServerActionsResponseTypeDef",
     "JobPostLaunchActionsLaunchStatusTypeDef",
     "PostLaunchActionsTypeDef",
     "ListTemplateActionsResponseTypeDef",
     "ListWavesResponseTypeDef",
+    "ListImportsResponseTypeDef",
+    "StartImportResponseTypeDef",
     "SourceServerResponseMetadataTypeDef",
     "SourceServerTypeDef",
     "PostLaunchActionsStatusTypeDef",
     "CreateLaunchConfigurationTemplateRequestRequestTypeDef",
     "LaunchConfigurationTemplateResponseMetadataTypeDef",
     "LaunchConfigurationTemplateTypeDef",
     "LaunchConfigurationTypeDef",
@@ -204,25 +240,14 @@
         "lastUpdateDateTime": str,
         "progressStatus": ApplicationProgressStatusType,
         "totalSourceServers": int,
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
 ArchiveApplicationRequestRequestTypeDef = TypedDict(
     "ArchiveApplicationRequestRequestTypeDef",
     {
         "applicationID": str,
     },
 )
 
@@ -276,19 +301,21 @@
     {
         "description": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
     pass
 
+
 LaunchTemplateDiskConfTypeDef = TypedDict(
     "LaunchTemplateDiskConfTypeDef",
     {
         "iops": int,
         "throughput": int,
         "volumeType": VolumeTypeType,
     },
@@ -324,20 +351,22 @@
     {
         "ebsEncryptionKeyArn": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateReplicationConfigurationTemplateRequestRequestTypeDef(
     _RequiredCreateReplicationConfigurationTemplateRequestRequestTypeDef,
     _OptionalCreateReplicationConfigurationTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateWaveRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWaveRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateWaveRequestRequestTypeDef = TypedDict(
@@ -345,19 +374,21 @@
     {
         "description": str,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateWaveRequestRequestTypeDef(
     _RequiredCreateWaveRequestRequestTypeDef, _OptionalCreateWaveRequestRequestTypeDef
 ):
     pass
 
+
 DataReplicationErrorTypeDef = TypedDict(
     "DataReplicationErrorTypeDef",
     {
         "error": DataReplicationErrorStringType,
         "rawError": str,
     },
     total=False,
@@ -429,24 +460,36 @@
 DeleteWaveRequestRequestTypeDef = TypedDict(
     "DeleteWaveRequestRequestTypeDef",
     {
         "waveID": str,
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
@@ -454,40 +497,60 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class DescribeJobLogItemsRequestRequestTypeDef(
     _RequiredDescribeJobLogItemsRequestRequestTypeDef,
     _OptionalDescribeJobLogItemsRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeJobsRequestFiltersTypeDef = TypedDict(
     "DescribeJobsRequestFiltersTypeDef",
     {
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
 DescribeLaunchConfigurationTemplatesRequestRequestTypeDef = TypedDict(
     "DescribeLaunchConfigurationTemplatesRequestRequestTypeDef",
     {
         "launchConfigurationTemplateIDs": Sequence[str],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
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
@@ -517,32 +580,42 @@
         "stagingAreaTags": Dict[str, str],
         "tags": Dict[str, str],
         "useDedicatedReplicationServer": bool,
     },
     total=False,
 )
 
+
 class ReplicationConfigurationTemplateTypeDef(
     _RequiredReplicationConfigurationTemplateTypeDef,
     _OptionalReplicationConfigurationTemplateTypeDef,
 ):
     pass
 
+
 DescribeSourceServersRequestFiltersTypeDef = TypedDict(
     "DescribeSourceServersRequestFiltersTypeDef",
     {
         "applicationIDs": Sequence[str],
         "isArchived": bool,
         "lifeCycleStates": Sequence[LifeCycleStateType],
         "replicationTypes": Sequence[ReplicationTypeType],
         "sourceServerIDs": Sequence[str],
     },
     total=False,
 )
 
+DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef = TypedDict(
+    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeVcenterClientsRequestRequestTypeDef = TypedDict(
     "DescribeVcenterClientsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -591,14 +664,39 @@
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
+ExportErrorDataTypeDef = TypedDict(
+    "ExportErrorDataTypeDef",
+    {
+        "rawError": str,
+    },
+    total=False,
+)
+
+ExportTaskSummaryTypeDef = TypedDict(
+    "ExportTaskSummaryTypeDef",
+    {
+        "applicationsCount": int,
+        "serversCount": int,
+        "wavesCount": int,
+    },
+    total=False,
+)
+
 FinalizeCutoverRequestRequestTypeDef = TypedDict(
     "FinalizeCutoverRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
@@ -624,14 +722,74 @@
         "hostname": str,
         "vmPath": str,
         "vmWareUuid": str,
     },
     total=False,
 )
 
+ImportErrorDataTypeDef = TypedDict(
+    "ImportErrorDataTypeDef",
+    {
+        "applicationID": str,
+        "ec2LaunchTemplateID": str,
+        "rawError": str,
+        "rowNumber": int,
+        "sourceServerID": str,
+        "waveID": str,
+    },
+    total=False,
+)
+
+ImportTaskSummaryApplicationsTypeDef = TypedDict(
+    "ImportTaskSummaryApplicationsTypeDef",
+    {
+        "createdCount": int,
+        "modifiedCount": int,
+    },
+    total=False,
+)
+
+ImportTaskSummaryServersTypeDef = TypedDict(
+    "ImportTaskSummaryServersTypeDef",
+    {
+        "createdCount": int,
+        "modifiedCount": int,
+    },
+    total=False,
+)
+
+ImportTaskSummaryWavesTypeDef = TypedDict(
+    "ImportTaskSummaryWavesTypeDef",
+    {
+        "createdCount": int,
+        "modifiedCount": int,
+    },
+    total=False,
+)
+
+_RequiredS3BucketSourceTypeDef = TypedDict(
+    "_RequiredS3BucketSourceTypeDef",
+    {
+        "s3Bucket": str,
+        "s3Key": str,
+    },
+)
+_OptionalS3BucketSourceTypeDef = TypedDict(
+    "_OptionalS3BucketSourceTypeDef",
+    {
+        "s3BucketOwner": str,
+    },
+    total=False,
+)
+
+
+class S3BucketSourceTypeDef(_RequiredS3BucketSourceTypeDef, _OptionalS3BucketSourceTypeDef):
+    pass
+
+
 JobLogEventDataTypeDef = TypedDict(
     "JobLogEventDataTypeDef",
     {
         "conversionServerID": str,
         "rawError": str,
         "sourceServerID": str,
         "targetInstanceID": str,
@@ -705,14 +863,118 @@
         "applicationIDs": Sequence[str],
         "isArchived": bool,
         "waveIDs": Sequence[str],
     },
     total=False,
 )
 
+_RequiredListExportErrorsRequestListExportErrorsPaginateTypeDef = TypedDict(
+    "_RequiredListExportErrorsRequestListExportErrorsPaginateTypeDef",
+    {
+        "exportID": str,
+    },
+)
+_OptionalListExportErrorsRequestListExportErrorsPaginateTypeDef = TypedDict(
+    "_OptionalListExportErrorsRequestListExportErrorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListExportErrorsRequestListExportErrorsPaginateTypeDef(
+    _RequiredListExportErrorsRequestListExportErrorsPaginateTypeDef,
+    _OptionalListExportErrorsRequestListExportErrorsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListExportErrorsRequestRequestTypeDef = TypedDict(
+    "_RequiredListExportErrorsRequestRequestTypeDef",
+    {
+        "exportID": str,
+    },
+)
+_OptionalListExportErrorsRequestRequestTypeDef = TypedDict(
+    "_OptionalListExportErrorsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+
+class ListExportErrorsRequestRequestTypeDef(
+    _RequiredListExportErrorsRequestRequestTypeDef, _OptionalListExportErrorsRequestRequestTypeDef
+):
+    pass
+
+
+ListExportsRequestFiltersTypeDef = TypedDict(
+    "ListExportsRequestFiltersTypeDef",
+    {
+        "exportIDs": Sequence[str],
+    },
+    total=False,
+)
+
+_RequiredListImportErrorsRequestListImportErrorsPaginateTypeDef = TypedDict(
+    "_RequiredListImportErrorsRequestListImportErrorsPaginateTypeDef",
+    {
+        "importID": str,
+    },
+)
+_OptionalListImportErrorsRequestListImportErrorsPaginateTypeDef = TypedDict(
+    "_OptionalListImportErrorsRequestListImportErrorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListImportErrorsRequestListImportErrorsPaginateTypeDef(
+    _RequiredListImportErrorsRequestListImportErrorsPaginateTypeDef,
+    _OptionalListImportErrorsRequestListImportErrorsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListImportErrorsRequestRequestTypeDef = TypedDict(
+    "_RequiredListImportErrorsRequestRequestTypeDef",
+    {
+        "importID": str,
+    },
+)
+_OptionalListImportErrorsRequestRequestTypeDef = TypedDict(
+    "_OptionalListImportErrorsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+
+class ListImportErrorsRequestRequestTypeDef(
+    _RequiredListImportErrorsRequestRequestTypeDef, _OptionalListImportErrorsRequestRequestTypeDef
+):
+    pass
+
+
+ListImportsRequestFiltersTypeDef = TypedDict(
+    "ListImportsRequestFiltersTypeDef",
+    {
+        "importIDs": Sequence[str],
+    },
+    total=False,
+)
+
 SourceServerActionsRequestFiltersTypeDef = TypedDict(
     "SourceServerActionsRequestFiltersTypeDef",
     {
         "actionIDs": Sequence[str],
     },
     total=False,
 )
@@ -720,14 +982,22 @@
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
 TemplateActionsRequestFiltersTypeDef = TypedDict(
     "TemplateActionsRequestFiltersTypeDef",
     {
         "actionIDs": Sequence[str],
     },
     total=False,
 )
@@ -762,14 +1032,32 @@
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
+SsmExternalParameterTypeDef = TypedDict(
+    "SsmExternalParameterTypeDef",
+    {
+        "dynamicPath": str,
+    },
+    total=False,
+)
+
 SsmParameterStoreParameterTypeDef = TypedDict(
     "SsmParameterStoreParameterTypeDef",
     {
         "parameterName": str,
         "parameterType": Literal["STRING"],
     },
 )
@@ -798,14 +1086,47 @@
         "isBootDisk": bool,
         "stagingDiskType": ReplicationConfigurationReplicatedDiskStagingDiskTypeType,
         "throughput": int,
     },
     total=False,
 )
 
+ReplicationConfigurationTemplateResponseMetadataTypeDef = TypedDict(
+    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
+    {
+        "arn": str,
+        "associateDefaultSecurityGroup": bool,
+        "bandwidthThrottling": int,
+        "createPublicIP": bool,
+        "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
+        "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
+        "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
+        "ebsEncryptionKeyArn": str,
+        "replicationConfigurationTemplateID": str,
+        "replicationServerInstanceType": str,
+        "replicationServersSecurityGroupsIDs": List[str],
+        "stagingAreaSubnetId": str,
+        "stagingAreaTags": Dict[str, str],
+        "tags": Dict[str, str],
+        "useDedicatedReplicationServer": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 
@@ -819,19 +1140,43 @@
     "_OptionalStartCutoverRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class StartCutoverRequestRequestTypeDef(
     _RequiredStartCutoverRequestRequestTypeDef, _OptionalStartCutoverRequestRequestTypeDef
 ):
     pass
 
+
+_RequiredStartExportRequestRequestTypeDef = TypedDict(
+    "_RequiredStartExportRequestRequestTypeDef",
+    {
+        "s3Bucket": str,
+        "s3Key": str,
+    },
+)
+_OptionalStartExportRequestRequestTypeDef = TypedDict(
+    "_OptionalStartExportRequestRequestTypeDef",
+    {
+        "s3BucketOwner": str,
+    },
+    total=False,
+)
+
+
+class StartExportRequestRequestTypeDef(
+    _RequiredStartExportRequestRequestTypeDef, _OptionalStartExportRequestRequestTypeDef
+):
+    pass
+
+
 StartReplicationRequestRequestTypeDef = TypedDict(
     "StartReplicationRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 
@@ -845,19 +1190,21 @@
     "_OptionalStartTestRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class StartTestRequestRequestTypeDef(
     _RequiredStartTestRequestRequestTypeDef, _OptionalStartTestRequestRequestTypeDef
 ):
     pass
 
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -872,20 +1219,22 @@
     "_OptionalTerminateTargetInstancesRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class TerminateTargetInstancesRequestRequestTypeDef(
     _RequiredTerminateTargetInstancesRequestRequestTypeDef,
     _OptionalTerminateTargetInstancesRequestRequestTypeDef,
 ):
     pass
 
+
 UnarchiveApplicationRequestRequestTypeDef = TypedDict(
     "UnarchiveApplicationRequestRequestTypeDef",
     {
         "applicationID": str,
     },
 )
 
@@ -915,19 +1264,21 @@
     {
         "description": str,
         "name": str,
     },
     total=False,
 )
 
+
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateReplicationConfigurationTemplateRequestRequestTypeDef",
     {
         "replicationConfigurationTemplateID": str,
     },
 )
 _OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef = TypedDict(
@@ -946,20 +1297,22 @@
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Mapping[str, str],
         "useDedicatedReplicationServer": bool,
     },
     total=False,
 )
 
+
 class UpdateReplicationConfigurationTemplateRequestRequestTypeDef(
     _RequiredUpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     _OptionalUpdateReplicationConfigurationTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateSourceServerReplicationTypeRequestRequestTypeDef = TypedDict(
     "UpdateSourceServerReplicationTypeRequestRequestTypeDef",
     {
         "replicationType": ReplicationTypeType,
         "sourceServerID": str,
     },
 )
@@ -975,100 +1328,65 @@
     {
         "description": str,
         "name": str,
     },
     total=False,
 )
 
+
 class UpdateWaveRequestRequestTypeDef(
     _RequiredUpdateWaveRequestRequestTypeDef, _OptionalUpdateWaveRequestRequestTypeDef
 ):
     pass
 
+
 WaveAggregatedStatusTypeDef = TypedDict(
     "WaveAggregatedStatusTypeDef",
     {
         "healthStatus": WaveHealthStatusType,
         "lastUpdateDateTime": str,
         "progressStatus": WaveProgressStatusType,
         "replicationStartedDateTime": str,
         "totalApplications": int,
     },
     total=False,
 )
 
-ApplicationTypeDef = TypedDict(
-    "ApplicationTypeDef",
+ApplicationResponseMetadataTypeDef = TypedDict(
+    "ApplicationResponseMetadataTypeDef",
     {
         "applicationAggregatedStatus": ApplicationAggregatedStatusTypeDef,
         "applicationID": str,
         "arn": str,
         "creationDateTime": str,
         "description": str,
         "isArchived": bool,
         "lastModifiedDateTime": str,
         "name": str,
         "tags": Dict[str, str],
         "waveID": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ApplicationResponseMetadataTypeDef = TypedDict(
-    "ApplicationResponseMetadataTypeDef",
+ApplicationTypeDef = TypedDict(
+    "ApplicationTypeDef",
     {
         "applicationAggregatedStatus": ApplicationAggregatedStatusTypeDef,
         "applicationID": str,
         "arn": str,
         "creationDateTime": str,
         "description": str,
         "isArchived": bool,
         "lastModifiedDateTime": str,
         "name": str,
         "tags": Dict[str, str],
         "waveID": str,
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReplicationConfigurationTemplateResponseMetadataTypeDef = TypedDict(
-    "ReplicationConfigurationTemplateResponseMetadataTypeDef",
-    {
-        "arn": str,
-        "associateDefaultSecurityGroup": bool,
-        "bandwidthThrottling": int,
-        "createPublicIP": bool,
-        "dataPlaneRouting": ReplicationConfigurationDataPlaneRoutingType,
-        "defaultLargeStagingDiskType": ReplicationConfigurationDefaultLargeStagingDiskTypeType,
-        "ebsEncryption": ReplicationConfigurationEbsEncryptionType,
-        "ebsEncryptionKeyArn": str,
-        "replicationConfigurationTemplateID": str,
-        "replicationServerInstanceType": str,
-        "replicationServersSecurityGroupsIDs": List[str],
-        "stagingAreaSubnetId": str,
-        "stagingAreaTags": Dict[str, str],
-        "tags": Dict[str, str],
-        "useDedicatedReplicationServer": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
 ChangeServerLifeCycleStateRequestRequestTypeDef = TypedDict(
     "ChangeServerLifeCycleStateRequestRequestTypeDef",
     {
         "lifeCycle": ChangeServerLifeCycleStateSourceServerLifecycleTypeDef,
         "sourceServerID": str,
@@ -1081,65 +1399,19 @@
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
-DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef = TypedDict(
-    "DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef",
-    {
-        "launchConfigurationTemplateIDs": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
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
-DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef = TypedDict(
-    "DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef",
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
@@ -1151,23 +1423,23 @@
 )
 
 DescribeReplicationConfigurationTemplatesResponseTypeDef = TypedDict(
     "DescribeReplicationConfigurationTemplatesResponseTypeDef",
     {
         "items": List[ReplicationConfigurationTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef = TypedDict(
     "DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef",
     {
         "filters": DescribeSourceServersRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeSourceServersRequestRequestTypeDef = TypedDict(
     "DescribeSourceServersRequestRequestTypeDef",
     {
@@ -1179,18 +1451,84 @@
 )
 
 DescribeVcenterClientsResponseTypeDef = TypedDict(
     "DescribeVcenterClientsResponseTypeDef",
     {
         "items": List[VcenterClientTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ExportTaskErrorTypeDef = TypedDict(
+    "ExportTaskErrorTypeDef",
+    {
+        "errorData": ExportErrorDataTypeDef,
+        "errorDateTime": str,
+    },
+    total=False,
+)
+
+ExportTaskTypeDef = TypedDict(
+    "ExportTaskTypeDef",
+    {
+        "creationDateTime": str,
+        "endDateTime": str,
+        "exportID": str,
+        "progressPercentage": float,
+        "s3Bucket": str,
+        "s3BucketOwner": str,
+        "s3Key": str,
+        "status": ExportStatusType,
+        "summary": ExportTaskSummaryTypeDef,
+    },
+    total=False,
+)
+
+ImportTaskErrorTypeDef = TypedDict(
+    "ImportTaskErrorTypeDef",
+    {
+        "errorData": ImportErrorDataTypeDef,
+        "errorDateTime": str,
+        "errorType": ImportErrorTypeType,
     },
+    total=False,
 )
 
+ImportTaskSummaryTypeDef = TypedDict(
+    "ImportTaskSummaryTypeDef",
+    {
+        "applications": ImportTaskSummaryApplicationsTypeDef,
+        "servers": ImportTaskSummaryServersTypeDef,
+        "waves": ImportTaskSummaryWavesTypeDef,
+    },
+    total=False,
+)
+
+_RequiredStartImportRequestRequestTypeDef = TypedDict(
+    "_RequiredStartImportRequestRequestTypeDef",
+    {
+        "s3BucketSource": S3BucketSourceTypeDef,
+    },
+)
+_OptionalStartImportRequestRequestTypeDef = TypedDict(
+    "_OptionalStartImportRequestRequestTypeDef",
+    {
+        "clientToken": str,
+    },
+    total=False,
+)
+
+
+class StartImportRequestRequestTypeDef(
+    _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
+):
+    pass
+
+
 JobLogTypeDef = TypedDict(
     "JobLogTypeDef",
     {
         "event": JobLogEventType,
         "eventData": JobLogEventDataTypeDef,
         "logDateTime": str,
     },
@@ -1217,50 +1555,90 @@
     total=False,
 )
 
 ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
     "ListApplicationsRequestListApplicationsPaginateTypeDef",
     {
         "filters": ListApplicationsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "filters": ListApplicationsRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListExportsRequestListExportsPaginateTypeDef = TypedDict(
+    "ListExportsRequestListExportsPaginateTypeDef",
+    {
+        "filters": ListExportsRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListExportsRequestRequestTypeDef = TypedDict(
+    "ListExportsRequestRequestTypeDef",
+    {
+        "filters": ListExportsRequestFiltersTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+ListImportsRequestListImportsPaginateTypeDef = TypedDict(
+    "ListImportsRequestListImportsPaginateTypeDef",
+    {
+        "filters": ListImportsRequestFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListImportsRequestRequestTypeDef = TypedDict(
+    "ListImportsRequestRequestTypeDef",
+    {
+        "filters": ListImportsRequestFiltersTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
 _RequiredListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef = TypedDict(
     "_RequiredListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef",
     {
         "sourceServerID": str,
     },
 )
 _OptionalListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef = TypedDict(
     "_OptionalListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef",
     {
         "filters": SourceServerActionsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef(
     _RequiredListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef,
     _OptionalListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListSourceServerActionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSourceServerActionsRequestRequestTypeDef",
     {
         "sourceServerID": str,
     },
 )
 _OptionalListSourceServerActionsRequestRequestTypeDef = TypedDict(
@@ -1269,41 +1647,45 @@
         "filters": SourceServerActionsRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListSourceServerActionsRequestRequestTypeDef(
     _RequiredListSourceServerActionsRequestRequestTypeDef,
     _OptionalListSourceServerActionsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListTemplateActionsRequestListTemplateActionsPaginateTypeDef = TypedDict(
     "_RequiredListTemplateActionsRequestListTemplateActionsPaginateTypeDef",
     {
         "launchConfigurationTemplateID": str,
     },
 )
 _OptionalListTemplateActionsRequestListTemplateActionsPaginateTypeDef = TypedDict(
     "_OptionalListTemplateActionsRequestListTemplateActionsPaginateTypeDef",
     {
         "filters": TemplateActionsRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListTemplateActionsRequestListTemplateActionsPaginateTypeDef(
     _RequiredListTemplateActionsRequestListTemplateActionsPaginateTypeDef,
     _OptionalListTemplateActionsRequestListTemplateActionsPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListTemplateActionsRequestRequestTypeDef = TypedDict(
     "_RequiredListTemplateActionsRequestRequestTypeDef",
     {
         "launchConfigurationTemplateID": str,
     },
 )
 _OptionalListTemplateActionsRequestRequestTypeDef = TypedDict(
@@ -1312,25 +1694,27 @@
         "filters": TemplateActionsRequestFiltersTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListTemplateActionsRequestRequestTypeDef(
     _RequiredListTemplateActionsRequestRequestTypeDef,
     _OptionalListTemplateActionsRequestRequestTypeDef,
 ):
     pass
 
+
 ListWavesRequestListWavesPaginateTypeDef = TypedDict(
     "ListWavesRequestListWavesPaginateTypeDef",
     {
         "filters": ListWavesRequestFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListWavesRequestRequestTypeDef = TypedDict(
     "ListWavesRequestRequestTypeDef",
     {
@@ -1366,80 +1750,96 @@
         "sourceServerID": str,
     },
 )
 _OptionalPutSourceServerActionRequestRequestTypeDef = TypedDict(
     "_OptionalPutSourceServerActionRequestRequestTypeDef",
     {
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentVersion": str,
+        "externalParameters": Mapping[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "parameters": Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
 
+
 class PutSourceServerActionRequestRequestTypeDef(
     _RequiredPutSourceServerActionRequestRequestTypeDef,
     _OptionalPutSourceServerActionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredPutTemplateActionRequestRequestTypeDef = TypedDict(
     "_RequiredPutTemplateActionRequestRequestTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "documentIdentifier": str,
         "launchConfigurationTemplateID": str,
         "order": int,
     },
 )
 _OptionalPutTemplateActionRequestRequestTypeDef = TypedDict(
     "_OptionalPutTemplateActionRequestRequestTypeDef",
     {
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentVersion": str,
+        "externalParameters": Mapping[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "operatingSystem": str,
         "parameters": Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
 
+
 class PutTemplateActionRequestRequestTypeDef(
     _RequiredPutTemplateActionRequestRequestTypeDef, _OptionalPutTemplateActionRequestRequestTypeDef
 ):
     pass
 
+
 SourceServerActionDocumentResponseMetadataTypeDef = TypedDict(
     "SourceServerActionDocumentResponseMetadataTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerActionDocumentTypeDef = TypedDict(
     "SourceServerActionDocumentTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
@@ -1450,49 +1850,58 @@
         "actionName": str,
         "ssmDocumentName": str,
     },
 )
 _OptionalSsmDocumentTypeDef = TypedDict(
     "_OptionalSsmDocumentTypeDef",
     {
+        "externalParameters": Mapping[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "parameters": Mapping[str, Sequence[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
 )
 
+
 class SsmDocumentTypeDef(_RequiredSsmDocumentTypeDef, _OptionalSsmDocumentTypeDef):
     pass
 
+
 TemplateActionDocumentResponseMetadataTypeDef = TypedDict(
     "TemplateActionDocumentResponseMetadataTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "operatingSystem": str,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TemplateActionDocumentTypeDef = TypedDict(
     "TemplateActionDocumentTypeDef",
     {
         "actionID": str,
         "actionName": str,
         "active": bool,
+        "category": ActionCategoryType,
+        "description": str,
         "documentIdentifier": str,
         "documentVersion": str,
+        "externalParameters": Dict[str, SsmExternalParameterTypeDef],
         "mustSucceedForCutover": bool,
         "operatingSystem": str,
         "order": int,
         "parameters": Dict[str, List[SsmParameterStoreParameterTypeDef]],
         "timeoutSeconds": int,
     },
     total=False,
@@ -1512,15 +1921,15 @@
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
@@ -1543,33 +1952,35 @@
         "stagingAreaSubnetId": str,
         "stagingAreaTags": Mapping[str, str],
         "useDedicatedReplicationServer": bool,
     },
     total=False,
 )
 
+
 class UpdateReplicationConfigurationRequestRequestTypeDef(
     _RequiredUpdateReplicationConfigurationRequestRequestTypeDef,
     _OptionalUpdateReplicationConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 WaveResponseMetadataTypeDef = TypedDict(
     "WaveResponseMetadataTypeDef",
     {
         "arn": str,
         "creationDateTime": str,
         "description": str,
         "isArchived": bool,
         "lastModifiedDateTime": str,
         "name": str,
         "tags": Dict[str, str],
         "waveAggregatedStatus": WaveAggregatedStatusTypeDef,
         "waveID": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WaveTypeDef = TypedDict(
     "WaveTypeDef",
     {
         "arn": str,
@@ -1586,15 +1997,15 @@
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "items": List[ApplicationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataReplicationInfoTypeDef = TypedDict(
     "DataReplicationInfoTypeDef",
     {
         "dataReplicationError": DataReplicationErrorTypeDef,
@@ -1604,20 +2015,69 @@
         "lagDuration": str,
         "lastSnapshotDateTime": str,
         "replicatedDisks": List[DataReplicationInfoReplicatedDiskTypeDef],
     },
     total=False,
 )
 
+ListExportErrorsResponseTypeDef = TypedDict(
+    "ListExportErrorsResponseTypeDef",
+    {
+        "items": List[ExportTaskErrorTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListExportsResponseTypeDef = TypedDict(
+    "ListExportsResponseTypeDef",
+    {
+        "items": List[ExportTaskTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartExportResponseTypeDef = TypedDict(
+    "StartExportResponseTypeDef",
+    {
+        "exportTask": ExportTaskTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImportErrorsResponseTypeDef = TypedDict(
+    "ListImportErrorsResponseTypeDef",
+    {
+        "items": List[ImportTaskErrorTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ImportTaskTypeDef = TypedDict(
+    "ImportTaskTypeDef",
+    {
+        "creationDateTime": str,
+        "endDateTime": str,
+        "importID": str,
+        "progressPercentage": float,
+        "s3BucketSource": S3BucketSourceTypeDef,
+        "status": ImportStatusType,
+        "summary": ImportTaskSummaryTypeDef,
+    },
+    total=False,
+)
+
 DescribeJobLogItemsResponseTypeDef = TypedDict(
     "DescribeJobLogItemsResponseTypeDef",
     {
         "items": List[JobLogTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifeCycleTypeDef = TypedDict(
     "LifeCycleTypeDef",
     {
         "addedToServiceDateTime": str,
@@ -1632,15 +2092,15 @@
 )
 
 ListSourceServerActionsResponseTypeDef = TypedDict(
     "ListSourceServerActionsResponseTypeDef",
     {
         "items": List[SourceServerActionDocumentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobPostLaunchActionsLaunchStatusTypeDef = TypedDict(
     "JobPostLaunchActionsLaunchStatusTypeDef",
     {
         "executionID": str,
@@ -1665,58 +2125,79 @@
 )
 
 ListTemplateActionsResponseTypeDef = TypedDict(
     "ListTemplateActionsResponseTypeDef",
     {
         "items": List[TemplateActionDocumentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWavesResponseTypeDef = TypedDict(
     "ListWavesResponseTypeDef",
     {
         "items": List[WaveTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListImportsResponseTypeDef = TypedDict(
+    "ListImportsResponseTypeDef",
+    {
+        "items": List[ImportTaskTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartImportResponseTypeDef = TypedDict(
+    "StartImportResponseTypeDef",
+    {
+        "importTask": ImportTaskTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerResponseMetadataTypeDef = TypedDict(
     "SourceServerResponseMetadataTypeDef",
     {
         "applicationID": str,
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
+        "fqdnForActionFramework": str,
         "isArchived": bool,
         "launchedInstance": LaunchedInstanceTypeDef,
         "lifeCycle": LifeCycleTypeDef,
         "replicationType": ReplicationTypeType,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "tags": Dict[str, str],
+        "userProvidedID": str,
         "vcenterClientID": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceServerTypeDef = TypedDict(
     "SourceServerTypeDef",
     {
         "applicationID": str,
         "arn": str,
         "dataReplicationInfo": DataReplicationInfoTypeDef,
+        "fqdnForActionFramework": str,
         "isArchived": bool,
         "launchedInstance": LaunchedInstanceTypeDef,
         "lifeCycle": LifeCycleTypeDef,
         "replicationType": ReplicationTypeType,
         "sourceProperties": SourcePropertiesTypeDef,
         "sourceServerID": str,
         "tags": Dict[str, str],
+        "userProvidedID": str,
         "vcenterClientID": str,
     },
     total=False,
 )
 
 PostLaunchActionsStatusTypeDef = TypedDict(
     "PostLaunchActionsStatusTypeDef",
@@ -1764,15 +2245,15 @@
         "licensing": LicensingTypeDef,
         "mapAutoTaggingMpeID": str,
         "postLaunchActions": PostLaunchActionsTypeDef,
         "smallVolumeConf": LaunchTemplateDiskConfTypeDef,
         "smallVolumeMaxSize": int,
         "tags": Dict[str, str],
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLaunchConfigurationTemplateTypeDef = TypedDict(
     "_RequiredLaunchConfigurationTemplateTypeDef",
     {
         "launchConfigurationTemplateID": str,
@@ -1797,19 +2278,21 @@
         "smallVolumeMaxSize": int,
         "tags": Dict[str, str],
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
+
 class LaunchConfigurationTemplateTypeDef(
     _RequiredLaunchConfigurationTemplateTypeDef, _OptionalLaunchConfigurationTemplateTypeDef
 ):
     pass
 
+
 LaunchConfigurationTypeDef = TypedDict(
     "LaunchConfigurationTypeDef",
     {
         "bootMode": BootModeType,
         "copyPrivateIp": bool,
         "copyTags": bool,
         "ec2LaunchTemplateID": str,
@@ -1817,15 +2300,15 @@
         "launchDisposition": LaunchDispositionType,
         "licensing": LicensingTypeDef,
         "mapAutoTaggingMpeID": str,
         "name": str,
         "postLaunchActions": PostLaunchActionsTypeDef,
         "sourceServerID": str,
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateLaunchConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLaunchConfigurationRequestRequestTypeDef",
     {
         "sourceServerID": str,
@@ -1844,20 +2327,22 @@
         "name": str,
         "postLaunchActions": PostLaunchActionsTypeDef,
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
+
 class UpdateLaunchConfigurationRequestRequestTypeDef(
     _RequiredUpdateLaunchConfigurationRequestRequestTypeDef,
     _OptionalUpdateLaunchConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef",
     {
         "launchConfigurationTemplateID": str,
     },
 )
 _OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef = TypedDict(
@@ -1876,26 +2361,28 @@
         "smallVolumeConf": LaunchTemplateDiskConfTypeDef,
         "smallVolumeMaxSize": int,
         "targetInstanceTypeRightSizingMethod": TargetInstanceTypeRightSizingMethodType,
     },
     total=False,
 )
 
+
 class UpdateLaunchConfigurationTemplateRequestRequestTypeDef(
     _RequiredUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
     _OptionalUpdateLaunchConfigurationTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeSourceServersResponseTypeDef = TypedDict(
     "DescribeSourceServersResponseTypeDef",
     {
         "items": List[SourceServerTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredParticipatingServerTypeDef = TypedDict(
     "_RequiredParticipatingServerTypeDef",
     {
         "sourceServerID": str,
@@ -1907,25 +2394,27 @@
         "launchStatus": LaunchStatusType,
         "launchedEc2InstanceID": str,
         "postLaunchActionsStatus": PostLaunchActionsStatusTypeDef,
     },
     total=False,
 )
 
+
 class ParticipatingServerTypeDef(
     _RequiredParticipatingServerTypeDef, _OptionalParticipatingServerTypeDef
 ):
     pass
 
+
 DescribeLaunchConfigurationTemplatesResponseTypeDef = TypedDict(
     "DescribeLaunchConfigurationTemplatesResponseTypeDef",
     {
         "items": List[LaunchConfigurationTemplateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJobTypeDef = TypedDict(
     "_RequiredJobTypeDef",
     {
         "jobID": str,
@@ -1942,42 +2431,44 @@
         "status": JobStatusType,
         "tags": Dict[str, str],
         "type": JobTypeType,
     },
     total=False,
 )
 
+
 class JobTypeDef(_RequiredJobTypeDef, _OptionalJobTypeDef):
     pass
 
+
 DescribeJobsResponseTypeDef = TypedDict(
     "DescribeJobsResponseTypeDef",
     {
         "items": List[JobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartCutoverResponseTypeDef = TypedDict(
     "StartCutoverResponseTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTestResponseTypeDef = TypedDict(
     "StartTestResponseTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TerminateTargetInstancesResponseTypeDef = TypedDict(
     "TerminateTargetInstancesResponseTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/PKG-INFO` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mgn
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.mgn 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.mgn 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mgn"></a>
 
 # types-aiobotocore-mgn
 
 [![PyPI - types-aiobotocore-mgn](https://img.shields.io/pypi/v/types-aiobotocore-mgn.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgn)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mgn.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgn)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mgn?color=blue)](https://pypistats.org/packages/types-aiobotocore-mgn)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.mgn 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn)
+[aiobotocore.mgn 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgn.html#mgn)
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
 [types-aiobotocore-mgn docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgn/).
 
 See how it helps to find and fix potential bugs:
 
@@ -278,14 +278,18 @@
     DescribeJobLogItemsPaginator,
     DescribeJobsPaginator,
     DescribeLaunchConfigurationTemplatesPaginator,
     DescribeReplicationConfigurationTemplatesPaginator,
     DescribeSourceServersPaginator,
     DescribeVcenterClientsPaginator,
     ListApplicationsPaginator,
+    ListExportErrorsPaginator,
+    ListExportsPaginator,
+    ListImportErrorsPaginator,
+    ListImportsPaginator,
     ListSourceServerActionsPaginator,
     ListTemplateActionsPaginator,
     ListWavesPaginator,
 )
 
 session = get_session()
 async with session.create_client("mgn") as client:
@@ -308,14 +312,22 @@
     )
     describe_vcenter_clients_paginator: DescribeVcenterClientsPaginator = client.get_paginator(
         "describe_vcenter_clients"
     )
     list_applications_paginator: ListApplicationsPaginator = client.get_paginator(
         "list_applications"
     )
+    list_export_errors_paginator: ListExportErrorsPaginator = client.get_paginator(
+        "list_export_errors"
+    )
+    list_exports_paginator: ListExportsPaginator = client.get_paginator("list_exports")
+    list_import_errors_paginator: ListImportErrorsPaginator = client.get_paginator(
+        "list_import_errors"
+    )
+    list_imports_paginator: ListImportsPaginator = client.get_paginator("list_imports")
     list_source_server_actions_paginator: ListSourceServerActionsPaginator = client.get_paginator(
         "list_source_server_actions"
     )
     list_template_actions_paginator: ListTemplateActionsPaginator = client.get_paginator(
         "list_template_actions"
     )
     list_waves_paginator: ListWavesPaginator = client.get_paginator("list_waves")
@@ -326,37 +338,45 @@
 ### Literals
 
 `types_aiobotocore_mgn.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_mgn.literals import (
+    ActionCategoryType,
     ApplicationHealthStatusType,
     ApplicationProgressStatusType,
     BootModeType,
     ChangeServerLifeCycleStateSourceServerLifecycleStateType,
     DataReplicationErrorStringType,
     DataReplicationInitiationStepNameType,
     DataReplicationInitiationStepStatusType,
     DataReplicationStateType,
     DescribeJobLogItemsPaginatorName,
     DescribeJobsPaginatorName,
     DescribeLaunchConfigurationTemplatesPaginatorName,
     DescribeReplicationConfigurationTemplatesPaginatorName,
     DescribeSourceServersPaginatorName,
     DescribeVcenterClientsPaginatorName,
+    ExportStatusType,
     FirstBootType,
+    ImportErrorTypeType,
+    ImportStatusType,
     InitiatedByType,
     JobLogEventType,
     JobStatusType,
     JobTypeType,
     LaunchDispositionType,
     LaunchStatusType,
     LifeCycleStateType,
     ListApplicationsPaginatorName,
+    ListExportErrorsPaginatorName,
+    ListExportsPaginatorName,
+    ListImportErrorsPaginatorName,
+    ListImportsPaginatorName,
     ListSourceServerActionsPaginatorName,
     ListTemplateActionsPaginatorName,
     ListWavesPaginatorName,
     PostLaunchActionExecutionStatusType,
     PostLaunchActionsDeploymentTypeType,
     ReplicationConfigurationDataPlaneRoutingType,
     ReplicationConfigurationDefaultLargeStagingDiskTypeType,
@@ -373,29 +393,28 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: ApplicationHealthStatusType) -> bool:
+def check_value(value: ActionCategoryType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_mgn.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mgn.type_defs import (
     ApplicationAggregatedStatusTypeDef,
-    ResponseMetadataTypeDef,
     ArchiveApplicationRequestRequestTypeDef,
     ArchiveWaveRequestRequestTypeDef,
     AssociateApplicationsRequestRequestTypeDef,
     AssociateSourceServersRequestRequestTypeDef,
     CPUTypeDef,
     ChangeServerLifeCycleStateSourceServerLifecycleTypeDef,
     CreateApplicationRequestRequestTypeDef,
@@ -409,87 +428,112 @@
     DeleteApplicationRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
     DeleteLaunchConfigurationTemplateRequestRequestTypeDef,
     DeleteReplicationConfigurationTemplateRequestRequestTypeDef,
     DeleteSourceServerRequestRequestTypeDef,
     DeleteVcenterClientRequestRequestTypeDef,
     DeleteWaveRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
     DescribeJobLogItemsRequestRequestTypeDef,
     DescribeJobsRequestFiltersTypeDef,
+    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
     DescribeLaunchConfigurationTemplatesRequestRequestTypeDef,
+    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
     DescribeReplicationConfigurationTemplatesRequestRequestTypeDef,
     ReplicationConfigurationTemplateTypeDef,
     DescribeSourceServersRequestFiltersTypeDef,
+    DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef,
     DescribeVcenterClientsRequestRequestTypeDef,
     VcenterClientTypeDef,
     DisassociateApplicationsRequestRequestTypeDef,
     DisassociateSourceServersRequestRequestTypeDef,
     DisconnectFromServiceRequestRequestTypeDef,
     DiskTypeDef,
+    EmptyResponseMetadataTypeDef,
+    ExportErrorDataTypeDef,
+    ExportTaskSummaryTypeDef,
     FinalizeCutoverRequestRequestTypeDef,
     GetLaunchConfigurationRequestRequestTypeDef,
     GetReplicationConfigurationRequestRequestTypeDef,
     IdentificationHintsTypeDef,
+    ImportErrorDataTypeDef,
+    ImportTaskSummaryApplicationsTypeDef,
+    ImportTaskSummaryServersTypeDef,
+    ImportTaskSummaryWavesTypeDef,
+    S3BucketSourceTypeDef,
     JobLogEventDataTypeDef,
     LaunchedInstanceTypeDef,
     LifeCycleLastCutoverFinalizedTypeDef,
     LifeCycleLastCutoverInitiatedTypeDef,
     LifeCycleLastCutoverRevertedTypeDef,
     LifeCycleLastTestFinalizedTypeDef,
     LifeCycleLastTestInitiatedTypeDef,
     LifeCycleLastTestRevertedTypeDef,
     ListApplicationsRequestFiltersTypeDef,
+    ListExportErrorsRequestListExportErrorsPaginateTypeDef,
+    ListExportErrorsRequestRequestTypeDef,
+    ListExportsRequestFiltersTypeDef,
+    ListImportErrorsRequestListImportErrorsPaginateTypeDef,
+    ListImportErrorsRequestRequestTypeDef,
+    ListImportsRequestFiltersTypeDef,
     SourceServerActionsRequestFiltersTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TemplateActionsRequestFiltersTypeDef,
     ListWavesRequestFiltersTypeDef,
     MarkAsArchivedRequestRequestTypeDef,
     NetworkInterfaceTypeDef,
     OSTypeDef,
+    PaginatorConfigTypeDef,
+    SsmExternalParameterTypeDef,
     SsmParameterStoreParameterTypeDef,
     RemoveSourceServerActionRequestRequestTypeDef,
     RemoveTemplateActionRequestRequestTypeDef,
     ReplicationConfigurationReplicatedDiskTypeDef,
+    ReplicationConfigurationTemplateResponseMetadataTypeDef,
+    ResponseMetadataTypeDef,
     RetryDataReplicationRequestRequestTypeDef,
     StartCutoverRequestRequestTypeDef,
+    StartExportRequestRequestTypeDef,
     StartReplicationRequestRequestTypeDef,
     StartTestRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TerminateTargetInstancesRequestRequestTypeDef,
     UnarchiveApplicationRequestRequestTypeDef,
     UnarchiveWaveRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateReplicationConfigurationTemplateRequestRequestTypeDef,
     UpdateSourceServerReplicationTypeRequestRequestTypeDef,
     UpdateWaveRequestRequestTypeDef,
     WaveAggregatedStatusTypeDef,
-    ApplicationTypeDef,
     ApplicationResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ReplicationConfigurationTemplateResponseMetadataTypeDef,
+    ApplicationTypeDef,
     ChangeServerLifeCycleStateRequestRequestTypeDef,
     DataReplicationInitiationTypeDef,
-    DescribeJobLogItemsRequestDescribeJobLogItemsPaginateTypeDef,
-    DescribeLaunchConfigurationTemplatesRequestDescribeLaunchConfigurationTemplatesPaginateTypeDef,
-    DescribeReplicationConfigurationTemplatesRequestDescribeReplicationConfigurationTemplatesPaginateTypeDef,
-    DescribeVcenterClientsRequestDescribeVcenterClientsPaginateTypeDef,
     DescribeJobsRequestDescribeJobsPaginateTypeDef,
     DescribeJobsRequestRequestTypeDef,
     DescribeReplicationConfigurationTemplatesResponseTypeDef,
     DescribeSourceServersRequestDescribeSourceServersPaginateTypeDef,
     DescribeSourceServersRequestRequestTypeDef,
     DescribeVcenterClientsResponseTypeDef,
+    ExportTaskErrorTypeDef,
+    ExportTaskTypeDef,
+    ImportTaskErrorTypeDef,
+    ImportTaskSummaryTypeDef,
+    StartImportRequestRequestTypeDef,
     JobLogTypeDef,
     LifeCycleLastCutoverTypeDef,
     LifeCycleLastTestTypeDef,
     ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    ListExportsRequestListExportsPaginateTypeDef,
+    ListExportsRequestRequestTypeDef,
+    ListImportsRequestListImportsPaginateTypeDef,
+    ListImportsRequestRequestTypeDef,
     ListSourceServerActionsRequestListSourceServerActionsPaginateTypeDef,
     ListSourceServerActionsRequestRequestTypeDef,
     ListTemplateActionsRequestListTemplateActionsPaginateTypeDef,
     ListTemplateActionsRequestRequestTypeDef,
     ListWavesRequestListWavesPaginateTypeDef,
     ListWavesRequestRequestTypeDef,
     SourcePropertiesTypeDef,
@@ -502,21 +546,28 @@
     TemplateActionDocumentTypeDef,
     ReplicationConfigurationTypeDef,
     UpdateReplicationConfigurationRequestRequestTypeDef,
     WaveResponseMetadataTypeDef,
     WaveTypeDef,
     ListApplicationsResponseTypeDef,
     DataReplicationInfoTypeDef,
+    ListExportErrorsResponseTypeDef,
+    ListExportsResponseTypeDef,
+    StartExportResponseTypeDef,
+    ListImportErrorsResponseTypeDef,
+    ImportTaskTypeDef,
     DescribeJobLogItemsResponseTypeDef,
     LifeCycleTypeDef,
     ListSourceServerActionsResponseTypeDef,
     JobPostLaunchActionsLaunchStatusTypeDef,
     PostLaunchActionsTypeDef,
     ListTemplateActionsResponseTypeDef,
     ListWavesResponseTypeDef,
+    ListImportsResponseTypeDef,
+    StartImportResponseTypeDef,
     SourceServerResponseMetadataTypeDef,
     SourceServerTypeDef,
     PostLaunchActionsStatusTypeDef,
     CreateLaunchConfigurationTemplateRequestRequestTypeDef,
     LaunchConfigurationTemplateResponseMetadataTypeDef,
     LaunchConfigurationTemplateTypeDef,
     LaunchConfigurationTypeDef,
@@ -540,43 +591,43 @@
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

### Comparing `types-aiobotocore-mgn-2.5.0.post1/types_aiobotocore_mgn.egg-info/SOURCES.txt` & `types-aiobotocore-mgn-2.5.1/types_aiobotocore_mgn.egg-info/SOURCES.txt`

 * *Files identical despite different names*

