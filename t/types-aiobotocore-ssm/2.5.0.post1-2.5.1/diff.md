# Comparing `tmp/types-aiobotocore-ssm-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ssm-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ssm-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-ssm-2.5.1.tar", last modified: Wed Jun 28 01:44:14 2023, max compression
```

## Comparing `types-aiobotocore-ssm-2.5.0.post1.tar` & `types-aiobotocore-ssm-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.451657 types-aiobotocore-ssm-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    47006 2023-03-11 12:27:23.451657 types-aiobotocore-ssm-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    45451 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:23.451657 types-aiobotocore-ssm-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.447657 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/
--rw-r--r--   0 runner    (1001) docker     (123)    12771 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12770 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)   136641 2023-03-11 12:24:30.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/client.py
--rw-r--r--   0 runner    (1001) docker     (123)   136446 2023-03-11 12:24:30.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    27845 2023-03-11 12:24:31.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    27843 2023-03-11 12:24:31.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    61541 2023-03-11 12:24:31.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    61491 2023-03-11 12:24:31.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   204175 2023-03-11 12:24:38.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   203947 2023-03-11 12:24:33.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:29.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1571 2023-03-11 12:24:31.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1570 2023-03-11 12:24:31.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.451657 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    47006 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.402221 types-aiobotocore-ssm-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    46994 2023-06-28 01:44:14.402221 types-aiobotocore-ssm-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    45445 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:14.402221 types-aiobotocore-ssm-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:41:16.000000 types-aiobotocore-ssm-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.390221 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/
+-rw-r--r--   0 runner    (1001) docker     (123)    12771 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12770 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   136641 2023-06-28 01:41:18.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)   136446 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    28097 2023-06-28 01:41:21.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28095 2023-06-28 01:41:21.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    61515 2023-06-28 01:41:21.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    61466 2023-06-28 01:41:18.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   204499 2023-06-28 01:41:25.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   204271 2023-06-28 01:41:23.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:17.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1571 2023-06-28 01:41:21.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1570 2023-06-28 01:41:21.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:14.402221 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    46994 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:44:14.000000 types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ssm-2.5.0.post1/LICENSE` & `types-aiobotocore-ssm-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ssm-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm"></a>
 
 # types-aiobotocore-ssm
 
 [![PyPI - types-aiobotocore-ssm](https://img.shields.io/pypi/v/types-aiobotocore-ssm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
+[aiobotocore.SSM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
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
 [types-aiobotocore-ssm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -653,15 +653,15 @@
 ```python
 from types_aiobotocore_ssm.type_defs import (
     AccountSharingInfoTypeDef,
     TagTypeDef,
     AlarmTypeDef,
     AlarmStateInformationTypeDef,
     AssociateOpsItemRelatedItemRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateOpsItemRelatedItemResponseTypeDef,
     AssociationOverviewTypeDef,
     AssociationStatusTypeDef,
     TargetTypeDef,
     AssociationExecutionFilterTypeDef,
     OutputSourceTypeDef,
     AssociationExecutionTargetsFilterTypeDef,
     AssociationFilterTypeDef,
@@ -670,267 +670,267 @@
     AttachmentsSourceTypeDef,
     AutomationExecutionFilterTypeDef,
     ResolvedTargetsTypeDef,
     ProgressCountersTypeDef,
     PatchSourceTypeDef,
     CancelCommandRequestRequestTypeDef,
     CancelMaintenanceWindowExecutionRequestRequestTypeDef,
+    CancelMaintenanceWindowExecutionResultTypeDef,
     CloudWatchOutputConfigTypeDef,
     CommandFilterTypeDef,
     CommandPluginTypeDef,
     NotificationConfigTypeDef,
     ComplianceExecutionSummaryTypeDef,
     ComplianceItemEntryTypeDef,
     ComplianceStringFilterTypeDef,
     SeveritySummaryTypeDef,
     RegistrationMetadataItemTypeDef,
+    CreateActivationResultTypeDef,
     DocumentRequiresTypeDef,
+    CreateMaintenanceWindowResultTypeDef,
     OpsItemDataValueTypeDef,
     OpsItemNotificationTypeDef,
     RelatedOpsItemTypeDef,
+    CreateOpsItemResponseTypeDef,
     MetadataValueTypeDef,
+    CreateOpsMetadataResultTypeDef,
+    CreatePatchBaselineResultTypeDef,
     DeleteActivationRequestRequestTypeDef,
     DeleteAssociationRequestRequestTypeDef,
     DeleteDocumentRequestRequestTypeDef,
     DeleteInventoryRequestRequestTypeDef,
     DeleteMaintenanceWindowRequestRequestTypeDef,
+    DeleteMaintenanceWindowResultTypeDef,
     DeleteOpsMetadataRequestRequestTypeDef,
     DeleteParameterRequestRequestTypeDef,
     DeleteParametersRequestRequestTypeDef,
+    DeleteParametersResultTypeDef,
     DeletePatchBaselineRequestRequestTypeDef,
+    DeletePatchBaselineResultTypeDef,
     DeleteResourceDataSyncRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeregisterManagedInstanceRequestRequestTypeDef,
     DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef,
+    DeregisterPatchBaselineForPatchGroupResultTypeDef,
     DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef,
+    DeregisterTargetFromMaintenanceWindowResultTypeDef,
     DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef,
+    DeregisterTaskFromMaintenanceWindowResultTypeDef,
     DescribeActivationsFilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeAssociationRequestRequestTypeDef,
     StepExecutionFilterTypeDef,
     PatchOrchestratorFilterTypeDef,
     PatchTypeDef,
     DescribeDocumentPermissionRequestRequestTypeDef,
     DescribeDocumentRequestRequestTypeDef,
+    DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
     DescribeEffectiveInstanceAssociationsRequestRequestTypeDef,
     InstanceAssociationTypeDef,
+    DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
     DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef,
+    DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
     DescribeInstanceAssociationsStatusRequestRequestTypeDef,
     InstanceInformationFilterTypeDef,
     InstanceInformationStringFilterTypeDef,
     InstancePatchStateFilterTypeDef,
     InstancePatchStateTypeDef,
+    DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
     DescribeInstancePatchStatesRequestRequestTypeDef,
     PatchComplianceDataTypeDef,
+    DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef,
     DescribeInventoryDeletionsRequestRequestTypeDef,
     MaintenanceWindowFilterTypeDef,
     MaintenanceWindowExecutionTaskInvocationIdentityTypeDef,
     MaintenanceWindowExecutionTypeDef,
     ScheduledWindowExecutionTypeDef,
     MaintenanceWindowIdentityForTargetTypeDef,
     MaintenanceWindowIdentityTypeDef,
     OpsItemFilterTypeDef,
     ParameterStringFilterTypeDef,
     ParametersFilterTypeDef,
     PatchBaselineIdentityTypeDef,
     DescribePatchGroupStateRequestRequestTypeDef,
+    DescribePatchGroupStateResultTypeDef,
+    DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
     DescribePatchPropertiesRequestRequestTypeDef,
+    DescribePatchPropertiesResultTypeDef,
     SessionFilterTypeDef,
     DisassociateOpsItemRelatedItemRequestRequestTypeDef,
     DocumentDefaultVersionDescriptionTypeDef,
     DocumentParameterTypeDef,
     ReviewInformationTypeDef,
     DocumentFilterTypeDef,
     DocumentKeyValuesFilterTypeDef,
     DocumentReviewCommentSourceTypeDef,
     DocumentVersionInfoTypeDef,
     PatchStatusTypeDef,
     FailureDetailsTypeDef,
     GetAutomationExecutionRequestRequestTypeDef,
     GetCalendarStateRequestRequestTypeDef,
+    GetCalendarStateResponseTypeDef,
     WaiterConfigTypeDef,
     GetCommandInvocationRequestRequestTypeDef,
     GetConnectionStatusRequestRequestTypeDef,
+    GetConnectionStatusResponseTypeDef,
     GetDefaultPatchBaselineRequestRequestTypeDef,
+    GetDefaultPatchBaselineResultTypeDef,
+    GetDeployablePatchSnapshotForInstanceResultTypeDef,
     GetDocumentRequestRequestTypeDef,
     InventoryFilterTypeDef,
     ResultAttributeTypeDef,
+    GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef,
     GetInventorySchemaRequestRequestTypeDef,
     GetMaintenanceWindowExecutionRequestRequestTypeDef,
+    GetMaintenanceWindowExecutionResultTypeDef,
     GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef,
+    GetMaintenanceWindowExecutionTaskInvocationResultTypeDef,
     GetMaintenanceWindowExecutionTaskRequestRequestTypeDef,
     MaintenanceWindowTaskParameterValueExpressionTypeDef,
     GetMaintenanceWindowRequestRequestTypeDef,
+    GetMaintenanceWindowResultTypeDef,
     GetMaintenanceWindowTaskRequestRequestTypeDef,
     LoggingInfoTypeDef,
     GetOpsItemRequestRequestTypeDef,
     GetOpsMetadataRequestRequestTypeDef,
     OpsFilterTypeDef,
     OpsResultAttributeTypeDef,
+    GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
     GetParameterHistoryRequestRequestTypeDef,
     GetParameterRequestRequestTypeDef,
     ParameterTypeDef,
     GetParametersRequestRequestTypeDef,
     GetPatchBaselineForPatchGroupRequestRequestTypeDef,
+    GetPatchBaselineForPatchGroupResultTypeDef,
     GetPatchBaselineRequestRequestTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
     GetResourcePoliciesResponseEntryTypeDef,
     GetServiceSettingRequestRequestTypeDef,
     ServiceSettingTypeDef,
     InstanceAggregatedAssociationOverviewTypeDef,
     S3OutputLocationTypeDef,
     S3OutputUrlTypeDef,
     InventoryDeletionSummaryItemTypeDef,
     InventoryItemAttributeTypeDef,
     InventoryItemTypeDef,
     InventoryResultItemTypeDef,
     LabelParameterVersionRequestRequestTypeDef,
+    LabelParameterVersionResultTypeDef,
+    ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
     ListAssociationVersionsRequestRequestTypeDef,
     ListDocumentMetadataHistoryRequestRequestTypeDef,
+    ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
     ListDocumentVersionsRequestRequestTypeDef,
+    ListInventoryEntriesResultTypeDef,
     OpsItemEventFilterTypeDef,
     OpsItemRelatedItemsFilterTypeDef,
     OpsMetadataFilterTypeDef,
     OpsMetadataTypeDef,
+    ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef,
     ListResourceDataSyncRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MaintenanceWindowAutomationParametersTypeDef,
     MaintenanceWindowLambdaParametersTypeDef,
     MaintenanceWindowStepFunctionsParametersTypeDef,
     ModifyDocumentPermissionRequestRequestTypeDef,
     OpsEntityItemTypeDef,
     OpsItemIdentityTypeDef,
+    PaginatorConfigTypeDef,
     ParameterInlinePolicyTypeDef,
     PatchFilterTypeDef,
+    PutInventoryResultTypeDef,
+    PutParameterResultTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
     RegisterDefaultPatchBaselineRequestRequestTypeDef,
+    RegisterDefaultPatchBaselineResultTypeDef,
     RegisterPatchBaselineForPatchGroupRequestRequestTypeDef,
+    RegisterPatchBaselineForPatchGroupResultTypeDef,
+    RegisterTargetWithMaintenanceWindowResultTypeDef,
+    RegisterTaskWithMaintenanceWindowResultTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
     ResetServiceSettingRequestRequestTypeDef,
     ResourceDataSyncOrganizationalUnitTypeDef,
     ResourceDataSyncDestinationDataSharingTypeDef,
+    ResponseMetadataTypeDef,
     ResumeSessionRequestRequestTypeDef,
+    ResumeSessionResponseTypeDef,
     SendAutomationSignalRequestRequestTypeDef,
     SessionManagerOutputUrlTypeDef,
     StartAssociationsOnceRequestRequestTypeDef,
+    StartAutomationExecutionResultTypeDef,
+    StartChangeRequestExecutionResultTypeDef,
     StartSessionRequestRequestTypeDef,
+    StartSessionResponseTypeDef,
     StopAutomationExecutionRequestRequestTypeDef,
     TerminateSessionRequestRequestTypeDef,
+    TerminateSessionResponseTypeDef,
     UnlabelParameterVersionRequestRequestTypeDef,
+    UnlabelParameterVersionResultTypeDef,
     UpdateDocumentDefaultVersionRequestRequestTypeDef,
     UpdateMaintenanceWindowRequestRequestTypeDef,
+    UpdateMaintenanceWindowResultTypeDef,
     UpdateManagedInstanceRoleRequestRequestTypeDef,
+    UpdateOpsMetadataResultTypeDef,
     UpdateServiceSettingRequestRequestTypeDef,
+    DescribeDocumentPermissionResponseTypeDef,
     ActivationTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
     CreateMaintenanceWindowRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     PutParameterRequestRequestTypeDef,
     AlarmConfigurationTypeDef,
-    AssociateOpsItemRelatedItemResponseTypeDef,
-    CancelMaintenanceWindowExecutionResultTypeDef,
-    CreateActivationResultTypeDef,
-    CreateMaintenanceWindowResultTypeDef,
-    CreateOpsItemResponseTypeDef,
-    CreateOpsMetadataResultTypeDef,
-    CreatePatchBaselineResultTypeDef,
-    DeleteMaintenanceWindowResultTypeDef,
-    DeleteParametersResultTypeDef,
-    DeletePatchBaselineResultTypeDef,
-    DeregisterPatchBaselineForPatchGroupResultTypeDef,
-    DeregisterTargetFromMaintenanceWindowResultTypeDef,
-    DeregisterTaskFromMaintenanceWindowResultTypeDef,
-    DescribeDocumentPermissionResponseTypeDef,
-    DescribePatchGroupStateResultTypeDef,
-    DescribePatchPropertiesResultTypeDef,
-    GetCalendarStateResponseTypeDef,
-    GetConnectionStatusResponseTypeDef,
-    GetDefaultPatchBaselineResultTypeDef,
-    GetDeployablePatchSnapshotForInstanceResultTypeDef,
-    GetMaintenanceWindowExecutionResultTypeDef,
-    GetMaintenanceWindowExecutionTaskInvocationResultTypeDef,
-    GetMaintenanceWindowResultTypeDef,
-    GetPatchBaselineForPatchGroupResultTypeDef,
-    LabelParameterVersionResultTypeDef,
-    ListInventoryEntriesResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    PutInventoryResultTypeDef,
-    PutParameterResultTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    RegisterDefaultPatchBaselineResultTypeDef,
-    RegisterPatchBaselineForPatchGroupResultTypeDef,
-    RegisterTargetWithMaintenanceWindowResultTypeDef,
-    RegisterTaskWithMaintenanceWindowResultTypeDef,
-    ResumeSessionResponseTypeDef,
-    StartAutomationExecutionResultTypeDef,
-    StartChangeRequestExecutionResultTypeDef,
-    StartSessionResponseTypeDef,
-    TerminateSessionResponseTypeDef,
-    UnlabelParameterVersionResultTypeDef,
-    UpdateMaintenanceWindowResultTypeDef,
-    UpdateOpsMetadataResultTypeDef,
     UpdateAssociationStatusRequestRequestTypeDef,
     AssociationTypeDef,
+    DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
     DescribeMaintenanceWindowsForTargetRequestRequestTypeDef,
     MaintenanceWindowTargetTypeDef,
     RegisterTargetWithMaintenanceWindowRequestRequestTypeDef,
     UpdateMaintenanceWindowTargetRequestRequestTypeDef,
     UpdateMaintenanceWindowTargetResultTypeDef,
+    DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
     DescribeAssociationExecutionsRequestRequestTypeDef,
     AssociationExecutionTargetTypeDef,
+    DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
     DescribeAssociationExecutionTargetsRequestRequestTypeDef,
+    ListAssociationsRequestListAssociationsPaginateTypeDef,
     ListAssociationsRequestRequestTypeDef,
     UpdateDocumentRequestRequestTypeDef,
+    DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef,
     DescribeAutomationExecutionsRequestRequestTypeDef,
     GetCommandInvocationResultTypeDef,
+    ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef,
     ListCommandInvocationsRequestRequestTypeDef,
+    ListCommandsRequestListCommandsPaginateTypeDef,
     ListCommandsRequestRequestTypeDef,
     CommandInvocationTypeDef,
     MaintenanceWindowRunCommandParametersTypeDef,
     ComplianceItemTypeDef,
     PutComplianceItemsRequestRequestTypeDef,
+    ListComplianceItemsRequestListComplianceItemsPaginateTypeDef,
     ListComplianceItemsRequestRequestTypeDef,
+    ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef,
     ListComplianceSummariesRequestRequestTypeDef,
+    ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef,
     ListResourceComplianceSummariesRequestRequestTypeDef,
     CompliantSummaryTypeDef,
     NonCompliantSummaryTypeDef,
     CreateActivationRequestRequestTypeDef,
     CreateDocumentRequestRequestTypeDef,
     DocumentIdentifierTypeDef,
     GetDocumentResultTypeDef,
     OpsItemSummaryTypeDef,
     CreateOpsItemRequestRequestTypeDef,
     OpsItemTypeDef,
     UpdateOpsItemRequestRequestTypeDef,
     CreateOpsMetadataRequestRequestTypeDef,
     GetOpsMetadataResultTypeDef,
     UpdateOpsMetadataRequestRequestTypeDef,
-    DescribeActivationsRequestRequestTypeDef,
     DescribeActivationsRequestDescribeActivationsPaginateTypeDef,
-    DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
-    DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
-    DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef,
-    DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
-    DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
-    DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
-    DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
-    DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef,
-    DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
-    DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
-    GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef,
-    GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
-    ListAssociationsRequestListAssociationsPaginateTypeDef,
-    ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef,
-    ListCommandsRequestListCommandsPaginateTypeDef,
-    ListComplianceItemsRequestListComplianceItemsPaginateTypeDef,
-    ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef,
-    ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
-    ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef,
-    ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef,
+    DescribeActivationsRequestRequestTypeDef,
     DescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef,
     DescribeAutomationStepExecutionsRequestRequestTypeDef,
     DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef,
     DescribeAvailablePatchesRequestRequestTypeDef,
     DescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef,
     DescribeInstancePatchesRequestRequestTypeDef,
     DescribeMaintenanceWindowScheduleRequestDescribeMaintenanceWindowSchedulePaginateTypeDef,
@@ -1119,43 +1119,43 @@
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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/README.md` & `types-aiobotocore-ssm-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ssm"></a>
 
 # types-aiobotocore-ssm
 
 [![PyPI - types-aiobotocore-ssm](https://img.shields.io/pypi/v/types-aiobotocore-ssm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
+[aiobotocore.SSM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
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
 [types-aiobotocore-ssm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -620,15 +620,15 @@
 ```python
 from types_aiobotocore_ssm.type_defs import (
     AccountSharingInfoTypeDef,
     TagTypeDef,
     AlarmTypeDef,
     AlarmStateInformationTypeDef,
     AssociateOpsItemRelatedItemRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateOpsItemRelatedItemResponseTypeDef,
     AssociationOverviewTypeDef,
     AssociationStatusTypeDef,
     TargetTypeDef,
     AssociationExecutionFilterTypeDef,
     OutputSourceTypeDef,
     AssociationExecutionTargetsFilterTypeDef,
     AssociationFilterTypeDef,
@@ -637,267 +637,267 @@
     AttachmentsSourceTypeDef,
     AutomationExecutionFilterTypeDef,
     ResolvedTargetsTypeDef,
     ProgressCountersTypeDef,
     PatchSourceTypeDef,
     CancelCommandRequestRequestTypeDef,
     CancelMaintenanceWindowExecutionRequestRequestTypeDef,
+    CancelMaintenanceWindowExecutionResultTypeDef,
     CloudWatchOutputConfigTypeDef,
     CommandFilterTypeDef,
     CommandPluginTypeDef,
     NotificationConfigTypeDef,
     ComplianceExecutionSummaryTypeDef,
     ComplianceItemEntryTypeDef,
     ComplianceStringFilterTypeDef,
     SeveritySummaryTypeDef,
     RegistrationMetadataItemTypeDef,
+    CreateActivationResultTypeDef,
     DocumentRequiresTypeDef,
+    CreateMaintenanceWindowResultTypeDef,
     OpsItemDataValueTypeDef,
     OpsItemNotificationTypeDef,
     RelatedOpsItemTypeDef,
+    CreateOpsItemResponseTypeDef,
     MetadataValueTypeDef,
+    CreateOpsMetadataResultTypeDef,
+    CreatePatchBaselineResultTypeDef,
     DeleteActivationRequestRequestTypeDef,
     DeleteAssociationRequestRequestTypeDef,
     DeleteDocumentRequestRequestTypeDef,
     DeleteInventoryRequestRequestTypeDef,
     DeleteMaintenanceWindowRequestRequestTypeDef,
+    DeleteMaintenanceWindowResultTypeDef,
     DeleteOpsMetadataRequestRequestTypeDef,
     DeleteParameterRequestRequestTypeDef,
     DeleteParametersRequestRequestTypeDef,
+    DeleteParametersResultTypeDef,
     DeletePatchBaselineRequestRequestTypeDef,
+    DeletePatchBaselineResultTypeDef,
     DeleteResourceDataSyncRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeregisterManagedInstanceRequestRequestTypeDef,
     DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef,
+    DeregisterPatchBaselineForPatchGroupResultTypeDef,
     DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef,
+    DeregisterTargetFromMaintenanceWindowResultTypeDef,
     DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef,
+    DeregisterTaskFromMaintenanceWindowResultTypeDef,
     DescribeActivationsFilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeAssociationRequestRequestTypeDef,
     StepExecutionFilterTypeDef,
     PatchOrchestratorFilterTypeDef,
     PatchTypeDef,
     DescribeDocumentPermissionRequestRequestTypeDef,
     DescribeDocumentRequestRequestTypeDef,
+    DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
     DescribeEffectiveInstanceAssociationsRequestRequestTypeDef,
     InstanceAssociationTypeDef,
+    DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
     DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef,
+    DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
     DescribeInstanceAssociationsStatusRequestRequestTypeDef,
     InstanceInformationFilterTypeDef,
     InstanceInformationStringFilterTypeDef,
     InstancePatchStateFilterTypeDef,
     InstancePatchStateTypeDef,
+    DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
     DescribeInstancePatchStatesRequestRequestTypeDef,
     PatchComplianceDataTypeDef,
+    DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef,
     DescribeInventoryDeletionsRequestRequestTypeDef,
     MaintenanceWindowFilterTypeDef,
     MaintenanceWindowExecutionTaskInvocationIdentityTypeDef,
     MaintenanceWindowExecutionTypeDef,
     ScheduledWindowExecutionTypeDef,
     MaintenanceWindowIdentityForTargetTypeDef,
     MaintenanceWindowIdentityTypeDef,
     OpsItemFilterTypeDef,
     ParameterStringFilterTypeDef,
     ParametersFilterTypeDef,
     PatchBaselineIdentityTypeDef,
     DescribePatchGroupStateRequestRequestTypeDef,
+    DescribePatchGroupStateResultTypeDef,
+    DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
     DescribePatchPropertiesRequestRequestTypeDef,
+    DescribePatchPropertiesResultTypeDef,
     SessionFilterTypeDef,
     DisassociateOpsItemRelatedItemRequestRequestTypeDef,
     DocumentDefaultVersionDescriptionTypeDef,
     DocumentParameterTypeDef,
     ReviewInformationTypeDef,
     DocumentFilterTypeDef,
     DocumentKeyValuesFilterTypeDef,
     DocumentReviewCommentSourceTypeDef,
     DocumentVersionInfoTypeDef,
     PatchStatusTypeDef,
     FailureDetailsTypeDef,
     GetAutomationExecutionRequestRequestTypeDef,
     GetCalendarStateRequestRequestTypeDef,
+    GetCalendarStateResponseTypeDef,
     WaiterConfigTypeDef,
     GetCommandInvocationRequestRequestTypeDef,
     GetConnectionStatusRequestRequestTypeDef,
+    GetConnectionStatusResponseTypeDef,
     GetDefaultPatchBaselineRequestRequestTypeDef,
+    GetDefaultPatchBaselineResultTypeDef,
+    GetDeployablePatchSnapshotForInstanceResultTypeDef,
     GetDocumentRequestRequestTypeDef,
     InventoryFilterTypeDef,
     ResultAttributeTypeDef,
+    GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef,
     GetInventorySchemaRequestRequestTypeDef,
     GetMaintenanceWindowExecutionRequestRequestTypeDef,
+    GetMaintenanceWindowExecutionResultTypeDef,
     GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef,
+    GetMaintenanceWindowExecutionTaskInvocationResultTypeDef,
     GetMaintenanceWindowExecutionTaskRequestRequestTypeDef,
     MaintenanceWindowTaskParameterValueExpressionTypeDef,
     GetMaintenanceWindowRequestRequestTypeDef,
+    GetMaintenanceWindowResultTypeDef,
     GetMaintenanceWindowTaskRequestRequestTypeDef,
     LoggingInfoTypeDef,
     GetOpsItemRequestRequestTypeDef,
     GetOpsMetadataRequestRequestTypeDef,
     OpsFilterTypeDef,
     OpsResultAttributeTypeDef,
+    GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
     GetParameterHistoryRequestRequestTypeDef,
     GetParameterRequestRequestTypeDef,
     ParameterTypeDef,
     GetParametersRequestRequestTypeDef,
     GetPatchBaselineForPatchGroupRequestRequestTypeDef,
+    GetPatchBaselineForPatchGroupResultTypeDef,
     GetPatchBaselineRequestRequestTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
     GetResourcePoliciesResponseEntryTypeDef,
     GetServiceSettingRequestRequestTypeDef,
     ServiceSettingTypeDef,
     InstanceAggregatedAssociationOverviewTypeDef,
     S3OutputLocationTypeDef,
     S3OutputUrlTypeDef,
     InventoryDeletionSummaryItemTypeDef,
     InventoryItemAttributeTypeDef,
     InventoryItemTypeDef,
     InventoryResultItemTypeDef,
     LabelParameterVersionRequestRequestTypeDef,
+    LabelParameterVersionResultTypeDef,
+    ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
     ListAssociationVersionsRequestRequestTypeDef,
     ListDocumentMetadataHistoryRequestRequestTypeDef,
+    ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
     ListDocumentVersionsRequestRequestTypeDef,
+    ListInventoryEntriesResultTypeDef,
     OpsItemEventFilterTypeDef,
     OpsItemRelatedItemsFilterTypeDef,
     OpsMetadataFilterTypeDef,
     OpsMetadataTypeDef,
+    ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef,
     ListResourceDataSyncRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MaintenanceWindowAutomationParametersTypeDef,
     MaintenanceWindowLambdaParametersTypeDef,
     MaintenanceWindowStepFunctionsParametersTypeDef,
     ModifyDocumentPermissionRequestRequestTypeDef,
     OpsEntityItemTypeDef,
     OpsItemIdentityTypeDef,
+    PaginatorConfigTypeDef,
     ParameterInlinePolicyTypeDef,
     PatchFilterTypeDef,
+    PutInventoryResultTypeDef,
+    PutParameterResultTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
     RegisterDefaultPatchBaselineRequestRequestTypeDef,
+    RegisterDefaultPatchBaselineResultTypeDef,
     RegisterPatchBaselineForPatchGroupRequestRequestTypeDef,
+    RegisterPatchBaselineForPatchGroupResultTypeDef,
+    RegisterTargetWithMaintenanceWindowResultTypeDef,
+    RegisterTaskWithMaintenanceWindowResultTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
     ResetServiceSettingRequestRequestTypeDef,
     ResourceDataSyncOrganizationalUnitTypeDef,
     ResourceDataSyncDestinationDataSharingTypeDef,
+    ResponseMetadataTypeDef,
     ResumeSessionRequestRequestTypeDef,
+    ResumeSessionResponseTypeDef,
     SendAutomationSignalRequestRequestTypeDef,
     SessionManagerOutputUrlTypeDef,
     StartAssociationsOnceRequestRequestTypeDef,
+    StartAutomationExecutionResultTypeDef,
+    StartChangeRequestExecutionResultTypeDef,
     StartSessionRequestRequestTypeDef,
+    StartSessionResponseTypeDef,
     StopAutomationExecutionRequestRequestTypeDef,
     TerminateSessionRequestRequestTypeDef,
+    TerminateSessionResponseTypeDef,
     UnlabelParameterVersionRequestRequestTypeDef,
+    UnlabelParameterVersionResultTypeDef,
     UpdateDocumentDefaultVersionRequestRequestTypeDef,
     UpdateMaintenanceWindowRequestRequestTypeDef,
+    UpdateMaintenanceWindowResultTypeDef,
     UpdateManagedInstanceRoleRequestRequestTypeDef,
+    UpdateOpsMetadataResultTypeDef,
     UpdateServiceSettingRequestRequestTypeDef,
+    DescribeDocumentPermissionResponseTypeDef,
     ActivationTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
     CreateMaintenanceWindowRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     PutParameterRequestRequestTypeDef,
     AlarmConfigurationTypeDef,
-    AssociateOpsItemRelatedItemResponseTypeDef,
-    CancelMaintenanceWindowExecutionResultTypeDef,
-    CreateActivationResultTypeDef,
-    CreateMaintenanceWindowResultTypeDef,
-    CreateOpsItemResponseTypeDef,
-    CreateOpsMetadataResultTypeDef,
-    CreatePatchBaselineResultTypeDef,
-    DeleteMaintenanceWindowResultTypeDef,
-    DeleteParametersResultTypeDef,
-    DeletePatchBaselineResultTypeDef,
-    DeregisterPatchBaselineForPatchGroupResultTypeDef,
-    DeregisterTargetFromMaintenanceWindowResultTypeDef,
-    DeregisterTaskFromMaintenanceWindowResultTypeDef,
-    DescribeDocumentPermissionResponseTypeDef,
-    DescribePatchGroupStateResultTypeDef,
-    DescribePatchPropertiesResultTypeDef,
-    GetCalendarStateResponseTypeDef,
-    GetConnectionStatusResponseTypeDef,
-    GetDefaultPatchBaselineResultTypeDef,
-    GetDeployablePatchSnapshotForInstanceResultTypeDef,
-    GetMaintenanceWindowExecutionResultTypeDef,
-    GetMaintenanceWindowExecutionTaskInvocationResultTypeDef,
-    GetMaintenanceWindowResultTypeDef,
-    GetPatchBaselineForPatchGroupResultTypeDef,
-    LabelParameterVersionResultTypeDef,
-    ListInventoryEntriesResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    PutInventoryResultTypeDef,
-    PutParameterResultTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    RegisterDefaultPatchBaselineResultTypeDef,
-    RegisterPatchBaselineForPatchGroupResultTypeDef,
-    RegisterTargetWithMaintenanceWindowResultTypeDef,
-    RegisterTaskWithMaintenanceWindowResultTypeDef,
-    ResumeSessionResponseTypeDef,
-    StartAutomationExecutionResultTypeDef,
-    StartChangeRequestExecutionResultTypeDef,
-    StartSessionResponseTypeDef,
-    TerminateSessionResponseTypeDef,
-    UnlabelParameterVersionResultTypeDef,
-    UpdateMaintenanceWindowResultTypeDef,
-    UpdateOpsMetadataResultTypeDef,
     UpdateAssociationStatusRequestRequestTypeDef,
     AssociationTypeDef,
+    DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
     DescribeMaintenanceWindowsForTargetRequestRequestTypeDef,
     MaintenanceWindowTargetTypeDef,
     RegisterTargetWithMaintenanceWindowRequestRequestTypeDef,
     UpdateMaintenanceWindowTargetRequestRequestTypeDef,
     UpdateMaintenanceWindowTargetResultTypeDef,
+    DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
     DescribeAssociationExecutionsRequestRequestTypeDef,
     AssociationExecutionTargetTypeDef,
+    DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
     DescribeAssociationExecutionTargetsRequestRequestTypeDef,
+    ListAssociationsRequestListAssociationsPaginateTypeDef,
     ListAssociationsRequestRequestTypeDef,
     UpdateDocumentRequestRequestTypeDef,
+    DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef,
     DescribeAutomationExecutionsRequestRequestTypeDef,
     GetCommandInvocationResultTypeDef,
+    ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef,
     ListCommandInvocationsRequestRequestTypeDef,
+    ListCommandsRequestListCommandsPaginateTypeDef,
     ListCommandsRequestRequestTypeDef,
     CommandInvocationTypeDef,
     MaintenanceWindowRunCommandParametersTypeDef,
     ComplianceItemTypeDef,
     PutComplianceItemsRequestRequestTypeDef,
+    ListComplianceItemsRequestListComplianceItemsPaginateTypeDef,
     ListComplianceItemsRequestRequestTypeDef,
+    ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef,
     ListComplianceSummariesRequestRequestTypeDef,
+    ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef,
     ListResourceComplianceSummariesRequestRequestTypeDef,
     CompliantSummaryTypeDef,
     NonCompliantSummaryTypeDef,
     CreateActivationRequestRequestTypeDef,
     CreateDocumentRequestRequestTypeDef,
     DocumentIdentifierTypeDef,
     GetDocumentResultTypeDef,
     OpsItemSummaryTypeDef,
     CreateOpsItemRequestRequestTypeDef,
     OpsItemTypeDef,
     UpdateOpsItemRequestRequestTypeDef,
     CreateOpsMetadataRequestRequestTypeDef,
     GetOpsMetadataResultTypeDef,
     UpdateOpsMetadataRequestRequestTypeDef,
-    DescribeActivationsRequestRequestTypeDef,
     DescribeActivationsRequestDescribeActivationsPaginateTypeDef,
-    DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
-    DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
-    DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef,
-    DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
-    DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
-    DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
-    DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
-    DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef,
-    DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
-    DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
-    GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef,
-    GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
-    ListAssociationsRequestListAssociationsPaginateTypeDef,
-    ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef,
-    ListCommandsRequestListCommandsPaginateTypeDef,
-    ListComplianceItemsRequestListComplianceItemsPaginateTypeDef,
-    ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef,
-    ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
-    ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef,
-    ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef,
+    DescribeActivationsRequestRequestTypeDef,
     DescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef,
     DescribeAutomationStepExecutionsRequestRequestTypeDef,
     DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef,
     DescribeAvailablePatchesRequestRequestTypeDef,
     DescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef,
     DescribeInstancePatchesRequestRequestTypeDef,
     DescribeMaintenanceWindowScheduleRequestDescribeMaintenanceWindowSchedulePaginateTypeDef,
@@ -1086,43 +1086,43 @@
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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/setup.py` & `types-aiobotocore-ssm-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ssm.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ssm",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ssm"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SSM 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SSM 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/",
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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/__init__.py` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/__init__.pyi` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/__main__.py` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SSM 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SSM 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM\nOther"
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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/client.py` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/client.pyi` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/literals.py` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -358,17 +358,19 @@
 ]
 MaintenanceWindowResourceTypeType = Literal["INSTANCE", "RESOURCE_GROUP"]
 MaintenanceWindowTaskCutoffBehaviorType = Literal["CANCEL_TASK", "CONTINUE_TASK"]
 MaintenanceWindowTaskTypeType = Literal["AUTOMATION", "LAMBDA", "RUN_COMMAND", "STEP_FUNCTIONS"]
 NotificationEventType = Literal["All", "Cancelled", "Failed", "InProgress", "Success", "TimedOut"]
 NotificationTypeType = Literal["Command", "Invocation"]
 OperatingSystemType = Literal[
+    "ALMA_LINUX",
     "AMAZON_LINUX",
     "AMAZON_LINUX_2",
     "AMAZON_LINUX_2022",
+    "AMAZON_LINUX_2023",
     "CENTOS",
     "DEBIAN",
     "MACOS",
     "ORACLE_LINUX",
     "RASPBIAN",
     "REDHAT_ENTERPRISE_LINUX",
     "ROCKY_LINUX",
@@ -575,14 +577,15 @@
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
@@ -661,14 +664,15 @@
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
@@ -679,14 +683,15 @@
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
@@ -722,14 +727,15 @@
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
@@ -748,16 +754,19 @@
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
@@ -841,15 +850,17 @@
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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/literals.pyi` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -356,17 +356,19 @@
 ]
 MaintenanceWindowResourceTypeType = Literal["INSTANCE", "RESOURCE_GROUP"]
 MaintenanceWindowTaskCutoffBehaviorType = Literal["CANCEL_TASK", "CONTINUE_TASK"]
 MaintenanceWindowTaskTypeType = Literal["AUTOMATION", "LAMBDA", "RUN_COMMAND", "STEP_FUNCTIONS"]
 NotificationEventType = Literal["All", "Cancelled", "Failed", "InProgress", "Success", "TimedOut"]
 NotificationTypeType = Literal["Command", "Invocation"]
 OperatingSystemType = Literal[
+    "ALMA_LINUX",
     "AMAZON_LINUX",
     "AMAZON_LINUX_2",
     "AMAZON_LINUX_2022",
+    "AMAZON_LINUX_2023",
     "CENTOS",
     "DEBIAN",
     "MACOS",
     "ORACLE_LINUX",
     "RASPBIAN",
     "REDHAT_ENTERPRISE_LINUX",
     "ROCKY_LINUX",
@@ -573,14 +575,15 @@
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
@@ -659,14 +662,15 @@
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
@@ -677,14 +681,15 @@
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
@@ -720,14 +725,15 @@
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
@@ -746,16 +752,19 @@
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
@@ -839,15 +848,17 @@
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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/paginator.py` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -108,16 +108,15 @@
         list_ops_item_events_paginator: ListOpsItemEventsPaginator = client.get_paginator("list_ops_item_events")
         list_ops_item_related_items_paginator: ListOpsItemRelatedItemsPaginator = client.get_paginator("list_ops_item_related_items")
         list_ops_metadata_paginator: ListOpsMetadataPaginator = client.get_paginator("list_ops_metadata")
         list_resource_compliance_summaries_paginator: ListResourceComplianceSummariesPaginator = client.get_paginator("list_resource_compliance_summaries")
         list_resource_data_sync_paginator: ListResourceDataSyncPaginator = client.get_paginator("list_resource_data_sync")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     MaintenanceWindowResourceTypeType,
     OperatingSystemType,
@@ -201,20 +200,14 @@
     PatchOrchestratorFilterTypeDef,
     ResultAttributeTypeDef,
     SessionFilterTypeDef,
     StepExecutionFilterTypeDef,
     TargetTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeActivationsPaginator",
     "DescribeAssociationExecutionTargetsPaginator",
     "DescribeAssociationExecutionsPaginator",
     "DescribeAutomationExecutionsPaginator",
     "DescribeAutomationStepExecutionsPaginator",
     "DescribeAvailablePatchesPaginator",
@@ -278,15 +271,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeactivationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[DescribeActivationsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeActivationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeActivations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeactivationspaginator)
         """
 
 
@@ -298,15 +291,15 @@
 
     def paginate(
         self,
         *,
         AssociationId: str,
         ExecutionId: str,
         Filters: Sequence[AssociationExecutionTargetsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAssociationExecutionTargetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAssociationExecutionTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeassociationexecutiontargetspaginator)
         """
 
 
@@ -317,15 +310,15 @@
     """
 
     def paginate(
         self,
         *,
         AssociationId: str,
         Filters: Sequence[AssociationExecutionFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAssociationExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAssociationExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeassociationexecutionspaginator)
         """
 
 
@@ -335,15 +328,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeautomationexecutionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[AutomationExecutionFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAutomationExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAutomationExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeautomationexecutionspaginator)
         """
 
 
@@ -355,15 +348,15 @@
 
     def paginate(
         self,
         *,
         AutomationExecutionId: str,
         Filters: Sequence[StepExecutionFilterTypeDef] = ...,
         ReverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAutomationStepExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAutomationStepExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeautomationstepexecutionspaginator)
         """
 
 
@@ -373,60 +366,60 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeavailablepatchespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAvailablePatchesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAvailablePatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeavailablepatchespaginator)
         """
 
 
 class DescribeEffectiveInstanceAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectiveInstanceAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectiveinstanceassociationspaginator)
     """
 
     def paginate(
-        self, *, InstanceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEffectiveInstanceAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectiveInstanceAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectiveinstanceassociationspaginator)
         """
 
 
 class DescribeEffectivePatchesForPatchBaselinePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectivePatchesForPatchBaseline)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectivepatchesforpatchbaselinepaginator)
     """
 
     def paginate(
-        self, *, BaselineId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, BaselineId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEffectivePatchesForPatchBaselineResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectivePatchesForPatchBaseline.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectivepatchesforpatchbaselinepaginator)
         """
 
 
 class DescribeInstanceAssociationsStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceAssociationsStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstanceassociationsstatuspaginator)
     """
 
     def paginate(
-        self, *, InstanceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstanceAssociationsStatusResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceAssociationsStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstanceassociationsstatuspaginator)
         """
 
 
@@ -437,30 +430,30 @@
     """
 
     def paginate(
         self,
         *,
         InstanceInformationFilterList: Sequence[InstanceInformationFilterTypeDef] = ...,
         Filters: Sequence[InstanceInformationStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstanceInformationResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceInformation.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstanceinformationpaginator)
         """
 
 
 class DescribeInstancePatchStatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchstatespaginator)
     """
 
     def paginate(
-        self, *, InstanceIds: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceIds: Sequence[str], PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancePatchStatesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchstatespaginator)
         """
 
 
@@ -471,15 +464,15 @@
     """
 
     def paginate(
         self,
         *,
         PatchGroup: str,
         Filters: Sequence[InstancePatchStateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancePatchStatesForPatchGroupResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStatesForPatchGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchstatesforpatchgrouppaginator)
         """
 
 
@@ -490,30 +483,30 @@
     """
 
     def paginate(
         self,
         *,
         InstanceId: str,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancePatchesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchespaginator)
         """
 
 
 class DescribeInventoryDeletionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInventoryDeletions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinventorydeletionspaginator)
     """
 
     def paginate(
-        self, *, DeletionId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DeletionId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInventoryDeletionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInventoryDeletions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinventorydeletionspaginator)
         """
 
 
@@ -525,15 +518,15 @@
 
     def paginate(
         self,
         *,
         WindowExecutionId: str,
         TaskId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutionTaskInvocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowexecutiontaskinvocationspaginator)
         """
 
 
@@ -544,15 +537,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowExecutionId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowExecutionTasksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutionTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowexecutiontaskspaginator)
         """
 
 
@@ -563,15 +556,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowexecutionspaginator)
         """
 
 
@@ -584,15 +577,15 @@
     def paginate(
         self,
         *,
         WindowId: str = ...,
         Targets: Sequence[TargetTypeDef] = ...,
         ResourceType: MaintenanceWindowResourceTypeType = ...,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowScheduleResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowSchedule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowschedulepaginator)
         """
 
 
@@ -603,15 +596,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowTargetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowtargetspaginator)
         """
 
 
@@ -622,15 +615,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowTasksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowtaskspaginator)
         """
 
 
@@ -640,15 +633,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowspaginator)
         """
 
 
@@ -659,15 +652,15 @@
     """
 
     def paginate(
         self,
         *,
         Targets: Sequence[TargetTypeDef],
         ResourceType: MaintenanceWindowResourceTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowsForTargetResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowsForTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowsfortargetpaginator)
         """
 
 
@@ -677,15 +670,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeopsitemspaginator)
     """
 
     def paginate(
         self,
         *,
         OpsItemFilters: Sequence[OpsItemFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOpsItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeOpsItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeopsitemspaginator)
         """
 
 
@@ -696,15 +689,15 @@
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ParametersFilterTypeDef] = ...,
         ParameterFilters: Sequence[ParameterStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeparameterspaginator)
         """
 
 
@@ -714,15 +707,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchbaselinespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePatchBaselinesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchBaselines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchbaselinespaginator)
         """
 
 
@@ -732,15 +725,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePatchGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchgroupspaginator)
         """
 
 
@@ -752,15 +745,15 @@
 
     def paginate(
         self,
         *,
         OperatingSystem: OperatingSystemType,
         Property: PatchPropertyType,
         PatchSet: PatchSetType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePatchPropertiesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchProperties.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchpropertiespaginator)
         """
 
 
@@ -771,15 +764,15 @@
     """
 
     def paginate(
         self,
         *,
         State: SessionStateType,
         Filters: Sequence[SessionFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSessionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describesessionspaginator)
         """
 
 
@@ -791,15 +784,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[InventoryFilterTypeDef] = ...,
         Aggregators: Sequence["InventoryAggregatorTypeDef"] = ...,
         ResultAttributes: Sequence[ResultAttributeTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInventoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetInventory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getinventorypaginator)
         """
 
 
@@ -811,15 +804,15 @@
 
     def paginate(
         self,
         *,
         TypeName: str = ...,
         Aggregator: bool = ...,
         SubType: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInventorySchemaResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetInventorySchema.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getinventoryschemapaginator)
         """
 
 
@@ -832,15 +825,15 @@
     def paginate(
         self,
         *,
         SyncName: str = ...,
         Filters: Sequence[OpsFilterTypeDef] = ...,
         Aggregators: Sequence["OpsAggregatorTypeDef"] = ...,
         ResultAttributes: Sequence[OpsResultAttributeTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOpsSummaryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetOpsSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getopssummarypaginator)
         """
 
 
@@ -851,15 +844,15 @@
     """
 
     def paginate(
         self,
         *,
         Name: str,
         WithDecryption: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetParameterHistoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetParameterHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getparameterhistorypaginator)
         """
 
 
@@ -872,45 +865,45 @@
     def paginate(
         self,
         *,
         Path: str,
         Recursive: bool = ...,
         ParameterFilters: Sequence[ParameterStringFilterTypeDef] = ...,
         WithDecryption: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetParametersByPathResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetParametersByPath.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getparametersbypathpaginator)
         """
 
 
 class GetResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getresourcepoliciespaginator)
         """
 
 
 class ListAssociationVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociationVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationversionspaginator)
     """
 
     def paginate(
-        self, *, AssociationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AssociationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociationVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationversionspaginator)
         """
 
 
@@ -920,15 +913,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         AssociationFilterList: Sequence[AssociationFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationspaginator)
         """
 
 
@@ -941,15 +934,15 @@
     def paginate(
         self,
         *,
         CommandId: str = ...,
         InstanceId: str = ...,
         Filters: Sequence[CommandFilterTypeDef] = ...,
         Details: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCommandInvocationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListCommandInvocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcommandinvocationspaginator)
         """
 
 
@@ -961,15 +954,15 @@
 
     def paginate(
         self,
         *,
         CommandId: str = ...,
         InstanceId: str = ...,
         Filters: Sequence[CommandFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCommandsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListCommands.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcommandspaginator)
         """
 
 
@@ -981,15 +974,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[ComplianceStringFilterTypeDef] = ...,
         ResourceIds: Sequence[str] = ...,
         ResourceTypes: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComplianceItemsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListComplianceItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcomplianceitemspaginator)
         """
 
 
@@ -999,30 +992,30 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcompliancesummariespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ComplianceStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComplianceSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListComplianceSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcompliancesummariespaginator)
         """
 
 
 class ListDocumentVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocumentVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listdocumentversionspaginator)
     """
 
     def paginate(
-        self, *, Name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocumentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listdocumentversionspaginator)
         """
 
 
@@ -1033,15 +1026,15 @@
     """
 
     def paginate(
         self,
         *,
         DocumentFilterList: Sequence[DocumentFilterTypeDef] = ...,
         Filters: Sequence[DocumentKeyValuesFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocuments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listdocumentspaginator)
         """
 
 
@@ -1051,15 +1044,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsitemeventspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[OpsItemEventFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOpsItemEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsItemEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsitemeventspaginator)
         """
 
 
@@ -1070,15 +1063,15 @@
     """
 
     def paginate(
         self,
         *,
         OpsItemId: str = ...,
         Filters: Sequence[OpsItemRelatedItemsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOpsItemRelatedItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsItemRelatedItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsitemrelateditemspaginator)
         """
 
 
@@ -1088,15 +1081,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsmetadatapaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[OpsMetadataFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOpsMetadataResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsMetadata.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsmetadatapaginator)
         """
 
 
@@ -1106,28 +1099,28 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcecompliancesummariespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ComplianceStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceComplianceSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceComplianceSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcecompliancesummariespaginator)
         """
 
 
 class ListResourceDataSyncPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceDataSync)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcedatasyncpaginator)
     """
 
     def paginate(
-        self, *, SyncType: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SyncType: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceDataSyncResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceDataSync.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcedatasyncpaginator)
         """
```

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/paginator.pyi` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -108,16 +108,15 @@
         list_ops_item_events_paginator: ListOpsItemEventsPaginator = client.get_paginator("list_ops_item_events")
         list_ops_item_related_items_paginator: ListOpsItemRelatedItemsPaginator = client.get_paginator("list_ops_item_related_items")
         list_ops_metadata_paginator: ListOpsMetadataPaginator = client.get_paginator("list_ops_metadata")
         list_resource_compliance_summaries_paginator: ListResourceComplianceSummariesPaginator = client.get_paginator("list_resource_compliance_summaries")
         list_resource_data_sync_paginator: ListResourceDataSyncPaginator = client.get_paginator("list_resource_data_sync")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     MaintenanceWindowResourceTypeType,
     OperatingSystemType,
@@ -201,19 +200,14 @@
     PatchOrchestratorFilterTypeDef,
     ResultAttributeTypeDef,
     SessionFilterTypeDef,
     StepExecutionFilterTypeDef,
     TargetTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeActivationsPaginator",
     "DescribeAssociationExecutionTargetsPaginator",
     "DescribeAssociationExecutionsPaginator",
     "DescribeAutomationExecutionsPaginator",
     "DescribeAutomationStepExecutionsPaginator",
     "DescribeAvailablePatchesPaginator",
@@ -274,15 +268,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeactivationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[DescribeActivationsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeActivationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeActivations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeactivationspaginator)
         """
 
 class DescribeAssociationExecutionTargetsPaginator(AioPaginator):
@@ -293,15 +287,15 @@
 
     def paginate(
         self,
         *,
         AssociationId: str,
         ExecutionId: str,
         Filters: Sequence[AssociationExecutionTargetsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAssociationExecutionTargetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAssociationExecutionTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeassociationexecutiontargetspaginator)
         """
 
 class DescribeAssociationExecutionsPaginator(AioPaginator):
@@ -311,15 +305,15 @@
     """
 
     def paginate(
         self,
         *,
         AssociationId: str,
         Filters: Sequence[AssociationExecutionFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAssociationExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAssociationExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeassociationexecutionspaginator)
         """
 
 class DescribeAutomationExecutionsPaginator(AioPaginator):
@@ -328,15 +322,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeautomationexecutionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[AutomationExecutionFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAutomationExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAutomationExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeautomationexecutionspaginator)
         """
 
 class DescribeAutomationStepExecutionsPaginator(AioPaginator):
@@ -347,15 +341,15 @@
 
     def paginate(
         self,
         *,
         AutomationExecutionId: str,
         Filters: Sequence[StepExecutionFilterTypeDef] = ...,
         ReverseOrder: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAutomationStepExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAutomationStepExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeautomationstepexecutionspaginator)
         """
 
 class DescribeAvailablePatchesPaginator(AioPaginator):
@@ -364,57 +358,57 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeavailablepatchespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAvailablePatchesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeAvailablePatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeavailablepatchespaginator)
         """
 
 class DescribeEffectiveInstanceAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectiveInstanceAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectiveinstanceassociationspaginator)
     """
 
     def paginate(
-        self, *, InstanceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEffectiveInstanceAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectiveInstanceAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectiveinstanceassociationspaginator)
         """
 
 class DescribeEffectivePatchesForPatchBaselinePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectivePatchesForPatchBaseline)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectivepatchesforpatchbaselinepaginator)
     """
 
     def paginate(
-        self, *, BaselineId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, BaselineId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEffectivePatchesForPatchBaselineResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeEffectivePatchesForPatchBaseline.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeeffectivepatchesforpatchbaselinepaginator)
         """
 
 class DescribeInstanceAssociationsStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceAssociationsStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstanceassociationsstatuspaginator)
     """
 
     def paginate(
-        self, *, InstanceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstanceAssociationsStatusResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceAssociationsStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstanceassociationsstatuspaginator)
         """
 
 class DescribeInstanceInformationPaginator(AioPaginator):
@@ -424,29 +418,29 @@
     """
 
     def paginate(
         self,
         *,
         InstanceInformationFilterList: Sequence[InstanceInformationFilterTypeDef] = ...,
         Filters: Sequence[InstanceInformationStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstanceInformationResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstanceInformation.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstanceinformationpaginator)
         """
 
 class DescribeInstancePatchStatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchstatespaginator)
     """
 
     def paginate(
-        self, *, InstanceIds: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceIds: Sequence[str], PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancePatchStatesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchstatespaginator)
         """
 
 class DescribeInstancePatchStatesForPatchGroupPaginator(AioPaginator):
@@ -456,15 +450,15 @@
     """
 
     def paginate(
         self,
         *,
         PatchGroup: str,
         Filters: Sequence[InstancePatchStateFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancePatchStatesForPatchGroupResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatchStatesForPatchGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchstatesforpatchgrouppaginator)
         """
 
 class DescribeInstancePatchesPaginator(AioPaginator):
@@ -474,29 +468,29 @@
     """
 
     def paginate(
         self,
         *,
         InstanceId: str,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancePatchesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInstancePatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinstancepatchespaginator)
         """
 
 class DescribeInventoryDeletionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInventoryDeletions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinventorydeletionspaginator)
     """
 
     def paginate(
-        self, *, DeletionId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DeletionId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInventoryDeletionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeInventoryDeletions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeinventorydeletionspaginator)
         """
 
 class DescribeMaintenanceWindowExecutionTaskInvocationsPaginator(AioPaginator):
@@ -507,15 +501,15 @@
 
     def paginate(
         self,
         *,
         WindowExecutionId: str,
         TaskId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutionTaskInvocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowexecutiontaskinvocationspaginator)
         """
 
 class DescribeMaintenanceWindowExecutionTasksPaginator(AioPaginator):
@@ -525,15 +519,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowExecutionId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowExecutionTasksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutionTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowexecutiontaskspaginator)
         """
 
 class DescribeMaintenanceWindowExecutionsPaginator(AioPaginator):
@@ -543,15 +537,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowExecutionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowexecutionspaginator)
         """
 
 class DescribeMaintenanceWindowSchedulePaginator(AioPaginator):
@@ -563,15 +557,15 @@
     def paginate(
         self,
         *,
         WindowId: str = ...,
         Targets: Sequence[TargetTypeDef] = ...,
         ResourceType: MaintenanceWindowResourceTypeType = ...,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowScheduleResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowSchedule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowschedulepaginator)
         """
 
 class DescribeMaintenanceWindowTargetsPaginator(AioPaginator):
@@ -581,15 +575,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowTargetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowtargetspaginator)
         """
 
 class DescribeMaintenanceWindowTasksPaginator(AioPaginator):
@@ -599,15 +593,15 @@
     """
 
     def paginate(
         self,
         *,
         WindowId: str,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowTasksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowtaskspaginator)
         """
 
 class DescribeMaintenanceWindowsPaginator(AioPaginator):
@@ -616,15 +610,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[MaintenanceWindowFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindows.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowspaginator)
         """
 
 class DescribeMaintenanceWindowsForTargetPaginator(AioPaginator):
@@ -634,15 +628,15 @@
     """
 
     def paginate(
         self,
         *,
         Targets: Sequence[TargetTypeDef],
         ResourceType: MaintenanceWindowResourceTypeType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMaintenanceWindowsForTargetResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeMaintenanceWindowsForTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describemaintenancewindowsfortargetpaginator)
         """
 
 class DescribeOpsItemsPaginator(AioPaginator):
@@ -651,15 +645,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeopsitemspaginator)
     """
 
     def paginate(
         self,
         *,
         OpsItemFilters: Sequence[OpsItemFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOpsItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeOpsItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeopsitemspaginator)
         """
 
 class DescribeParametersPaginator(AioPaginator):
@@ -669,15 +663,15 @@
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ParametersFilterTypeDef] = ...,
         ParameterFilters: Sequence[ParameterStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describeparameterspaginator)
         """
 
 class DescribePatchBaselinesPaginator(AioPaginator):
@@ -686,15 +680,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchbaselinespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePatchBaselinesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchBaselines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchbaselinespaginator)
         """
 
 class DescribePatchGroupsPaginator(AioPaginator):
@@ -703,15 +697,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PatchOrchestratorFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePatchGroupsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchgroupspaginator)
         """
 
 class DescribePatchPropertiesPaginator(AioPaginator):
@@ -722,15 +716,15 @@
 
     def paginate(
         self,
         *,
         OperatingSystem: OperatingSystemType,
         Property: PatchPropertyType,
         PatchSet: PatchSetType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePatchPropertiesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribePatchProperties.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describepatchpropertiespaginator)
         """
 
 class DescribeSessionsPaginator(AioPaginator):
@@ -740,15 +734,15 @@
     """
 
     def paginate(
         self,
         *,
         State: SessionStateType,
         Filters: Sequence[SessionFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSessionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.DescribeSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#describesessionspaginator)
         """
 
 class GetInventoryPaginator(AioPaginator):
@@ -759,15 +753,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[InventoryFilterTypeDef] = ...,
         Aggregators: Sequence["InventoryAggregatorTypeDef"] = ...,
         ResultAttributes: Sequence[ResultAttributeTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInventoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetInventory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getinventorypaginator)
         """
 
 class GetInventorySchemaPaginator(AioPaginator):
@@ -778,15 +772,15 @@
 
     def paginate(
         self,
         *,
         TypeName: str = ...,
         Aggregator: bool = ...,
         SubType: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInventorySchemaResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetInventorySchema.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getinventoryschemapaginator)
         """
 
 class GetOpsSummaryPaginator(AioPaginator):
@@ -798,15 +792,15 @@
     def paginate(
         self,
         *,
         SyncName: str = ...,
         Filters: Sequence[OpsFilterTypeDef] = ...,
         Aggregators: Sequence["OpsAggregatorTypeDef"] = ...,
         ResultAttributes: Sequence[OpsResultAttributeTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOpsSummaryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetOpsSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getopssummarypaginator)
         """
 
 class GetParameterHistoryPaginator(AioPaginator):
@@ -816,15 +810,15 @@
     """
 
     def paginate(
         self,
         *,
         Name: str,
         WithDecryption: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetParameterHistoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetParameterHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getparameterhistorypaginator)
         """
 
 class GetParametersByPathPaginator(AioPaginator):
@@ -836,43 +830,43 @@
     def paginate(
         self,
         *,
         Path: str,
         Recursive: bool = ...,
         ParameterFilters: Sequence[ParameterStringFilterTypeDef] = ...,
         WithDecryption: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetParametersByPathResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetParametersByPath.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getparametersbypathpaginator)
         """
 
 class GetResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#getresourcepoliciespaginator)
         """
 
 class ListAssociationVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociationVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationversionspaginator)
     """
 
     def paginate(
-        self, *, AssociationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AssociationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociationVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationversionspaginator)
         """
 
 class ListAssociationsPaginator(AioPaginator):
@@ -881,15 +875,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationspaginator)
     """
 
     def paginate(
         self,
         *,
         AssociationFilterList: Sequence[AssociationFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssociationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listassociationspaginator)
         """
 
 class ListCommandInvocationsPaginator(AioPaginator):
@@ -901,15 +895,15 @@
     def paginate(
         self,
         *,
         CommandId: str = ...,
         InstanceId: str = ...,
         Filters: Sequence[CommandFilterTypeDef] = ...,
         Details: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCommandInvocationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListCommandInvocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcommandinvocationspaginator)
         """
 
 class ListCommandsPaginator(AioPaginator):
@@ -920,15 +914,15 @@
 
     def paginate(
         self,
         *,
         CommandId: str = ...,
         InstanceId: str = ...,
         Filters: Sequence[CommandFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCommandsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListCommands.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcommandspaginator)
         """
 
 class ListComplianceItemsPaginator(AioPaginator):
@@ -939,15 +933,15 @@
 
     def paginate(
         self,
         *,
         Filters: Sequence[ComplianceStringFilterTypeDef] = ...,
         ResourceIds: Sequence[str] = ...,
         ResourceTypes: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComplianceItemsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListComplianceItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcomplianceitemspaginator)
         """
 
 class ListComplianceSummariesPaginator(AioPaginator):
@@ -956,29 +950,29 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcompliancesummariespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ComplianceStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComplianceSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListComplianceSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listcompliancesummariespaginator)
         """
 
 class ListDocumentVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocumentVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listdocumentversionspaginator)
     """
 
     def paginate(
-        self, *, Name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocumentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listdocumentversionspaginator)
         """
 
 class ListDocumentsPaginator(AioPaginator):
@@ -988,15 +982,15 @@
     """
 
     def paginate(
         self,
         *,
         DocumentFilterList: Sequence[DocumentFilterTypeDef] = ...,
         Filters: Sequence[DocumentKeyValuesFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListDocuments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listdocumentspaginator)
         """
 
 class ListOpsItemEventsPaginator(AioPaginator):
@@ -1005,15 +999,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsitemeventspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[OpsItemEventFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOpsItemEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsItemEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsitemeventspaginator)
         """
 
 class ListOpsItemRelatedItemsPaginator(AioPaginator):
@@ -1023,15 +1017,15 @@
     """
 
     def paginate(
         self,
         *,
         OpsItemId: str = ...,
         Filters: Sequence[OpsItemRelatedItemsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOpsItemRelatedItemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsItemRelatedItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsitemrelateditemspaginator)
         """
 
 class ListOpsMetadataPaginator(AioPaginator):
@@ -1040,15 +1034,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsmetadatapaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[OpsMetadataFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOpsMetadataResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListOpsMetadata.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listopsmetadatapaginator)
         """
 
 class ListResourceComplianceSummariesPaginator(AioPaginator):
@@ -1057,27 +1051,27 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcecompliancesummariespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ComplianceStringFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceComplianceSummariesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceComplianceSummaries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcecompliancesummariespaginator)
         """
 
 class ListResourceDataSyncPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceDataSync)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcedatasyncpaginator)
     """
 
     def paginate(
-        self, *, SyncType: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SyncType: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceDataSyncResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM.Paginator.ListResourceDataSync.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/paginators/#listresourcedatasyncpaginator)
         """
```

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/type_defs.py` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -106,15 +106,15 @@
 
 __all__ = (
     "AccountSharingInfoTypeDef",
     "TagTypeDef",
     "AlarmTypeDef",
     "AlarmStateInformationTypeDef",
     "AssociateOpsItemRelatedItemRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateOpsItemRelatedItemResponseTypeDef",
     "AssociationOverviewTypeDef",
     "AssociationStatusTypeDef",
     "TargetTypeDef",
     "AssociationExecutionFilterTypeDef",
     "OutputSourceTypeDef",
     "AssociationExecutionTargetsFilterTypeDef",
     "AssociationFilterTypeDef",
@@ -123,267 +123,267 @@
     "AttachmentsSourceTypeDef",
     "AutomationExecutionFilterTypeDef",
     "ResolvedTargetsTypeDef",
     "ProgressCountersTypeDef",
     "PatchSourceTypeDef",
     "CancelCommandRequestRequestTypeDef",
     "CancelMaintenanceWindowExecutionRequestRequestTypeDef",
+    "CancelMaintenanceWindowExecutionResultTypeDef",
     "CloudWatchOutputConfigTypeDef",
     "CommandFilterTypeDef",
     "CommandPluginTypeDef",
     "NotificationConfigTypeDef",
     "ComplianceExecutionSummaryTypeDef",
     "ComplianceItemEntryTypeDef",
     "ComplianceStringFilterTypeDef",
     "SeveritySummaryTypeDef",
     "RegistrationMetadataItemTypeDef",
+    "CreateActivationResultTypeDef",
     "DocumentRequiresTypeDef",
+    "CreateMaintenanceWindowResultTypeDef",
     "OpsItemDataValueTypeDef",
     "OpsItemNotificationTypeDef",
     "RelatedOpsItemTypeDef",
+    "CreateOpsItemResponseTypeDef",
     "MetadataValueTypeDef",
+    "CreateOpsMetadataResultTypeDef",
+    "CreatePatchBaselineResultTypeDef",
     "DeleteActivationRequestRequestTypeDef",
     "DeleteAssociationRequestRequestTypeDef",
     "DeleteDocumentRequestRequestTypeDef",
     "DeleteInventoryRequestRequestTypeDef",
     "DeleteMaintenanceWindowRequestRequestTypeDef",
+    "DeleteMaintenanceWindowResultTypeDef",
     "DeleteOpsMetadataRequestRequestTypeDef",
     "DeleteParameterRequestRequestTypeDef",
     "DeleteParametersRequestRequestTypeDef",
+    "DeleteParametersResultTypeDef",
     "DeletePatchBaselineRequestRequestTypeDef",
+    "DeletePatchBaselineResultTypeDef",
     "DeleteResourceDataSyncRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeregisterManagedInstanceRequestRequestTypeDef",
     "DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef",
+    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
     "DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef",
+    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
     "DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef",
+    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
     "DescribeActivationsFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeAssociationRequestRequestTypeDef",
     "StepExecutionFilterTypeDef",
     "PatchOrchestratorFilterTypeDef",
     "PatchTypeDef",
     "DescribeDocumentPermissionRequestRequestTypeDef",
     "DescribeDocumentRequestRequestTypeDef",
+    "DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
     "DescribeEffectiveInstanceAssociationsRequestRequestTypeDef",
     "InstanceAssociationTypeDef",
+    "DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
     "DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef",
+    "DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
     "DescribeInstanceAssociationsStatusRequestRequestTypeDef",
     "InstanceInformationFilterTypeDef",
     "InstanceInformationStringFilterTypeDef",
     "InstancePatchStateFilterTypeDef",
     "InstancePatchStateTypeDef",
+    "DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
     "DescribeInstancePatchStatesRequestRequestTypeDef",
     "PatchComplianceDataTypeDef",
+    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
     "DescribeInventoryDeletionsRequestRequestTypeDef",
     "MaintenanceWindowFilterTypeDef",
     "MaintenanceWindowExecutionTaskInvocationIdentityTypeDef",
     "MaintenanceWindowExecutionTypeDef",
     "ScheduledWindowExecutionTypeDef",
     "MaintenanceWindowIdentityForTargetTypeDef",
     "MaintenanceWindowIdentityTypeDef",
     "OpsItemFilterTypeDef",
     "ParameterStringFilterTypeDef",
     "ParametersFilterTypeDef",
     "PatchBaselineIdentityTypeDef",
     "DescribePatchGroupStateRequestRequestTypeDef",
+    "DescribePatchGroupStateResultTypeDef",
+    "DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
     "DescribePatchPropertiesRequestRequestTypeDef",
+    "DescribePatchPropertiesResultTypeDef",
     "SessionFilterTypeDef",
     "DisassociateOpsItemRelatedItemRequestRequestTypeDef",
     "DocumentDefaultVersionDescriptionTypeDef",
     "DocumentParameterTypeDef",
     "ReviewInformationTypeDef",
     "DocumentFilterTypeDef",
     "DocumentKeyValuesFilterTypeDef",
     "DocumentReviewCommentSourceTypeDef",
     "DocumentVersionInfoTypeDef",
     "PatchStatusTypeDef",
     "FailureDetailsTypeDef",
     "GetAutomationExecutionRequestRequestTypeDef",
     "GetCalendarStateRequestRequestTypeDef",
+    "GetCalendarStateResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetCommandInvocationRequestRequestTypeDef",
     "GetConnectionStatusRequestRequestTypeDef",
+    "GetConnectionStatusResponseTypeDef",
     "GetDefaultPatchBaselineRequestRequestTypeDef",
+    "GetDefaultPatchBaselineResultTypeDef",
+    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
     "GetDocumentRequestRequestTypeDef",
     "InventoryFilterTypeDef",
     "ResultAttributeTypeDef",
+    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
     "GetInventorySchemaRequestRequestTypeDef",
     "GetMaintenanceWindowExecutionRequestRequestTypeDef",
+    "GetMaintenanceWindowExecutionResultTypeDef",
     "GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef",
+    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
     "GetMaintenanceWindowExecutionTaskRequestRequestTypeDef",
     "MaintenanceWindowTaskParameterValueExpressionTypeDef",
     "GetMaintenanceWindowRequestRequestTypeDef",
+    "GetMaintenanceWindowResultTypeDef",
     "GetMaintenanceWindowTaskRequestRequestTypeDef",
     "LoggingInfoTypeDef",
     "GetOpsItemRequestRequestTypeDef",
     "GetOpsMetadataRequestRequestTypeDef",
     "OpsFilterTypeDef",
     "OpsResultAttributeTypeDef",
+    "GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
     "GetParameterHistoryRequestRequestTypeDef",
     "GetParameterRequestRequestTypeDef",
     "ParameterTypeDef",
     "GetParametersRequestRequestTypeDef",
     "GetPatchBaselineForPatchGroupRequestRequestTypeDef",
+    "GetPatchBaselineForPatchGroupResultTypeDef",
     "GetPatchBaselineRequestRequestTypeDef",
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesRequestRequestTypeDef",
     "GetResourcePoliciesResponseEntryTypeDef",
     "GetServiceSettingRequestRequestTypeDef",
     "ServiceSettingTypeDef",
     "InstanceAggregatedAssociationOverviewTypeDef",
     "S3OutputLocationTypeDef",
     "S3OutputUrlTypeDef",
     "InventoryDeletionSummaryItemTypeDef",
     "InventoryItemAttributeTypeDef",
     "InventoryItemTypeDef",
     "InventoryResultItemTypeDef",
     "LabelParameterVersionRequestRequestTypeDef",
+    "LabelParameterVersionResultTypeDef",
+    "ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
     "ListAssociationVersionsRequestRequestTypeDef",
     "ListDocumentMetadataHistoryRequestRequestTypeDef",
+    "ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
     "ListDocumentVersionsRequestRequestTypeDef",
+    "ListInventoryEntriesResultTypeDef",
     "OpsItemEventFilterTypeDef",
     "OpsItemRelatedItemsFilterTypeDef",
     "OpsMetadataFilterTypeDef",
     "OpsMetadataTypeDef",
+    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
     "ListResourceDataSyncRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MaintenanceWindowAutomationParametersTypeDef",
     "MaintenanceWindowLambdaParametersTypeDef",
     "MaintenanceWindowStepFunctionsParametersTypeDef",
     "ModifyDocumentPermissionRequestRequestTypeDef",
     "OpsEntityItemTypeDef",
     "OpsItemIdentityTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterInlinePolicyTypeDef",
     "PatchFilterTypeDef",
+    "PutInventoryResultTypeDef",
+    "PutParameterResultTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
     "RegisterDefaultPatchBaselineRequestRequestTypeDef",
+    "RegisterDefaultPatchBaselineResultTypeDef",
     "RegisterPatchBaselineForPatchGroupRequestRequestTypeDef",
+    "RegisterPatchBaselineForPatchGroupResultTypeDef",
+    "RegisterTargetWithMaintenanceWindowResultTypeDef",
+    "RegisterTaskWithMaintenanceWindowResultTypeDef",
     "RemoveTagsFromResourceRequestRequestTypeDef",
     "ResetServiceSettingRequestRequestTypeDef",
     "ResourceDataSyncOrganizationalUnitTypeDef",
     "ResourceDataSyncDestinationDataSharingTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeSessionRequestRequestTypeDef",
+    "ResumeSessionResponseTypeDef",
     "SendAutomationSignalRequestRequestTypeDef",
     "SessionManagerOutputUrlTypeDef",
     "StartAssociationsOnceRequestRequestTypeDef",
+    "StartAutomationExecutionResultTypeDef",
+    "StartChangeRequestExecutionResultTypeDef",
     "StartSessionRequestRequestTypeDef",
+    "StartSessionResponseTypeDef",
     "StopAutomationExecutionRequestRequestTypeDef",
     "TerminateSessionRequestRequestTypeDef",
+    "TerminateSessionResponseTypeDef",
     "UnlabelParameterVersionRequestRequestTypeDef",
+    "UnlabelParameterVersionResultTypeDef",
     "UpdateDocumentDefaultVersionRequestRequestTypeDef",
     "UpdateMaintenanceWindowRequestRequestTypeDef",
+    "UpdateMaintenanceWindowResultTypeDef",
     "UpdateManagedInstanceRoleRequestRequestTypeDef",
+    "UpdateOpsMetadataResultTypeDef",
     "UpdateServiceSettingRequestRequestTypeDef",
+    "DescribeDocumentPermissionResponseTypeDef",
     "ActivationTypeDef",
     "AddTagsToResourceRequestRequestTypeDef",
     "CreateMaintenanceWindowRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
     "PutParameterRequestRequestTypeDef",
     "AlarmConfigurationTypeDef",
-    "AssociateOpsItemRelatedItemResponseTypeDef",
-    "CancelMaintenanceWindowExecutionResultTypeDef",
-    "CreateActivationResultTypeDef",
-    "CreateMaintenanceWindowResultTypeDef",
-    "CreateOpsItemResponseTypeDef",
-    "CreateOpsMetadataResultTypeDef",
-    "CreatePatchBaselineResultTypeDef",
-    "DeleteMaintenanceWindowResultTypeDef",
-    "DeleteParametersResultTypeDef",
-    "DeletePatchBaselineResultTypeDef",
-    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
-    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
-    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
-    "DescribeDocumentPermissionResponseTypeDef",
-    "DescribePatchGroupStateResultTypeDef",
-    "DescribePatchPropertiesResultTypeDef",
-    "GetCalendarStateResponseTypeDef",
-    "GetConnectionStatusResponseTypeDef",
-    "GetDefaultPatchBaselineResultTypeDef",
-    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
-    "GetMaintenanceWindowExecutionResultTypeDef",
-    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
-    "GetMaintenanceWindowResultTypeDef",
-    "GetPatchBaselineForPatchGroupResultTypeDef",
-    "LabelParameterVersionResultTypeDef",
-    "ListInventoryEntriesResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "PutInventoryResultTypeDef",
-    "PutParameterResultTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "RegisterDefaultPatchBaselineResultTypeDef",
-    "RegisterPatchBaselineForPatchGroupResultTypeDef",
-    "RegisterTargetWithMaintenanceWindowResultTypeDef",
-    "RegisterTaskWithMaintenanceWindowResultTypeDef",
-    "ResumeSessionResponseTypeDef",
-    "StartAutomationExecutionResultTypeDef",
-    "StartChangeRequestExecutionResultTypeDef",
-    "StartSessionResponseTypeDef",
-    "TerminateSessionResponseTypeDef",
-    "UnlabelParameterVersionResultTypeDef",
-    "UpdateMaintenanceWindowResultTypeDef",
-    "UpdateOpsMetadataResultTypeDef",
     "UpdateAssociationStatusRequestRequestTypeDef",
     "AssociationTypeDef",
+    "DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
     "DescribeMaintenanceWindowsForTargetRequestRequestTypeDef",
     "MaintenanceWindowTargetTypeDef",
     "RegisterTargetWithMaintenanceWindowRequestRequestTypeDef",
     "UpdateMaintenanceWindowTargetRequestRequestTypeDef",
     "UpdateMaintenanceWindowTargetResultTypeDef",
+    "DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
     "DescribeAssociationExecutionsRequestRequestTypeDef",
     "AssociationExecutionTargetTypeDef",
+    "DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
     "DescribeAssociationExecutionTargetsRequestRequestTypeDef",
+    "ListAssociationsRequestListAssociationsPaginateTypeDef",
     "ListAssociationsRequestRequestTypeDef",
     "UpdateDocumentRequestRequestTypeDef",
+    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
     "DescribeAutomationExecutionsRequestRequestTypeDef",
     "GetCommandInvocationResultTypeDef",
+    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
     "ListCommandInvocationsRequestRequestTypeDef",
+    "ListCommandsRequestListCommandsPaginateTypeDef",
     "ListCommandsRequestRequestTypeDef",
     "CommandInvocationTypeDef",
     "MaintenanceWindowRunCommandParametersTypeDef",
     "ComplianceItemTypeDef",
     "PutComplianceItemsRequestRequestTypeDef",
+    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
     "ListComplianceItemsRequestRequestTypeDef",
+    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
     "ListComplianceSummariesRequestRequestTypeDef",
+    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
     "ListResourceComplianceSummariesRequestRequestTypeDef",
     "CompliantSummaryTypeDef",
     "NonCompliantSummaryTypeDef",
     "CreateActivationRequestRequestTypeDef",
     "CreateDocumentRequestRequestTypeDef",
     "DocumentIdentifierTypeDef",
     "GetDocumentResultTypeDef",
     "OpsItemSummaryTypeDef",
     "CreateOpsItemRequestRequestTypeDef",
     "OpsItemTypeDef",
     "UpdateOpsItemRequestRequestTypeDef",
     "CreateOpsMetadataRequestRequestTypeDef",
     "GetOpsMetadataResultTypeDef",
     "UpdateOpsMetadataRequestRequestTypeDef",
-    "DescribeActivationsRequestRequestTypeDef",
     "DescribeActivationsRequestDescribeActivationsPaginateTypeDef",
-    "DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
-    "DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
-    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
-    "DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
-    "DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
-    "DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
-    "DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
-    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
-    "DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
-    "DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
-    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
-    "GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    "ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
-    "ListAssociationsRequestListAssociationsPaginateTypeDef",
-    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
-    "ListCommandsRequestListCommandsPaginateTypeDef",
-    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
-    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
-    "ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
-    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
-    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
+    "DescribeActivationsRequestRequestTypeDef",
     "DescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef",
     "DescribeAutomationStepExecutionsRequestRequestTypeDef",
     "DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef",
     "DescribeAvailablePatchesRequestRequestTypeDef",
     "DescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef",
     "DescribeInstancePatchesRequestRequestTypeDef",
     "DescribeMaintenanceWindowScheduleRequestDescribeMaintenanceWindowSchedulePaginateTypeDef",
@@ -602,22 +602,19 @@
         "OpsItemId": str,
         "AssociationType": str,
         "ResourceType": str,
         "ResourceUri": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateOpsItemRelatedItemResponseTypeDef = TypedDict(
+    "AssociateOpsItemRelatedItemResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AssociationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociationOverviewTypeDef = TypedDict(
     "AssociationOverviewTypeDef",
     {
         "Status": str,
@@ -785,14 +782,22 @@
 CancelMaintenanceWindowExecutionRequestRequestTypeDef = TypedDict(
     "CancelMaintenanceWindowExecutionRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
     },
 )
 
+CancelMaintenanceWindowExecutionResultTypeDef = TypedDict(
+    "CancelMaintenanceWindowExecutionResultTypeDef",
+    {
+        "WindowExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CloudWatchOutputConfigTypeDef = TypedDict(
     "CloudWatchOutputConfigTypeDef",
     {
         "CloudWatchLogGroupName": str,
         "CloudWatchOutputEnabled": bool,
     },
     total=False,
@@ -908,14 +913,23 @@
     "RegistrationMetadataItemTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateActivationResultTypeDef = TypedDict(
+    "CreateActivationResultTypeDef",
+    {
+        "ActivationId": str,
+        "ActivationCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDocumentRequiresTypeDef = TypedDict(
     "_RequiredDocumentRequiresTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDocumentRequiresTypeDef = TypedDict(
@@ -929,14 +943,22 @@
 )
 
 
 class DocumentRequiresTypeDef(_RequiredDocumentRequiresTypeDef, _OptionalDocumentRequiresTypeDef):
     pass
 
 
+CreateMaintenanceWindowResultTypeDef = TypedDict(
+    "CreateMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OpsItemDataValueTypeDef = TypedDict(
     "OpsItemDataValueTypeDef",
     {
         "Value": str,
         "Type": OpsItemDataTypeType,
     },
     total=False,
@@ -953,22 +975,47 @@
 RelatedOpsItemTypeDef = TypedDict(
     "RelatedOpsItemTypeDef",
     {
         "OpsItemId": str,
     },
 )
 
+CreateOpsItemResponseTypeDef = TypedDict(
+    "CreateOpsItemResponseTypeDef",
+    {
+        "OpsItemId": str,
+        "OpsItemArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MetadataValueTypeDef = TypedDict(
     "MetadataValueTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
+CreateOpsMetadataResultTypeDef = TypedDict(
+    "CreateOpsMetadataResultTypeDef",
+    {
+        "OpsMetadataArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePatchBaselineResultTypeDef = TypedDict(
+    "CreatePatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteActivationRequestRequestTypeDef = TypedDict(
     "DeleteActivationRequestRequestTypeDef",
     {
         "ActivationId": str,
     },
 )
 
@@ -1031,14 +1078,22 @@
 DeleteMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "DeleteMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
     },
 )
 
+DeleteMaintenanceWindowResultTypeDef = TypedDict(
+    "DeleteMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteOpsMetadataRequestRequestTypeDef = TypedDict(
     "DeleteOpsMetadataRequestRequestTypeDef",
     {
         "OpsMetadataArn": str,
     },
 )
 
@@ -1052,21 +1107,38 @@
 DeleteParametersRequestRequestTypeDef = TypedDict(
     "DeleteParametersRequestRequestTypeDef",
     {
         "Names": Sequence[str],
     },
 )
 
+DeleteParametersResultTypeDef = TypedDict(
+    "DeleteParametersResultTypeDef",
+    {
+        "DeletedParameters": List[str],
+        "InvalidParameters": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePatchBaselineRequestRequestTypeDef = TypedDict(
     "DeletePatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 
+DeletePatchBaselineResultTypeDef = TypedDict(
+    "DeletePatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteResourceDataSyncRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourceDataSyncRequestRequestTypeDef",
     {
         "SyncName": str,
     },
 )
 _OptionalDeleteResourceDataSyncRequestRequestTypeDef = TypedDict(
@@ -1105,14 +1177,23 @@
     "DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef",
     {
         "BaselineId": str,
         "PatchGroup": str,
     },
 )
 
+DeregisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
+    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
+    {
+        "BaselineId": str,
+        "PatchGroup": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "_RequiredDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
         "WindowTargetId": str,
     },
 )
@@ -1128,37 +1209,45 @@
 class DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef(
     _RequiredDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef,
     _OptionalDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef,
 ):
     pass
 
 
+DeregisterTargetFromMaintenanceWindowResultTypeDef = TypedDict(
+    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "WindowTargetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
         "WindowTaskId": str,
     },
 )
 
-DescribeActivationsFilterTypeDef = TypedDict(
-    "DescribeActivationsFilterTypeDef",
+DeregisterTaskFromMaintenanceWindowResultTypeDef = TypedDict(
+    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
     {
-        "FilterKey": DescribeActivationsFilterKeysType,
-        "FilterValues": Sequence[str],
+        "WindowId": str,
+        "WindowTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeActivationsFilterTypeDef = TypedDict(
+    "DescribeActivationsFilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FilterKey": DescribeActivationsFilterKeysType,
+        "FilterValues": Sequence[str],
     },
     total=False,
 )
 
 DescribeAssociationRequestRequestTypeDef = TypedDict(
     "DescribeAssociationRequestRequestTypeDef",
     {
@@ -1259,14 +1348,36 @@
 
 class DescribeDocumentRequestRequestTypeDef(
     _RequiredDescribeDocumentRequestRequestTypeDef, _OptionalDescribeDocumentRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
+    {
+        "InstanceId": str,
+    },
+)
+_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef(
+    _RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
+    _OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeEffectiveInstanceAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEffectiveInstanceAssociationsRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 _OptionalDescribeEffectiveInstanceAssociationsRequestRequestTypeDef = TypedDict(
@@ -1293,14 +1404,36 @@
         "InstanceId": str,
         "Content": str,
         "AssociationVersion": str,
     },
     total=False,
 )
 
+_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
+    "_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
+    {
+        "BaselineId": str,
+    },
+)
+_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
+    "_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef(
+    _RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
+    _OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 _OptionalDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef = TypedDict(
@@ -1316,14 +1449,36 @@
 class DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef(
     _RequiredDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef,
     _OptionalDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
+    "_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
+    {
+        "InstanceId": str,
+    },
+)
+_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
+    "_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef(
+    _RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
+    _OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeInstanceAssociationsStatusRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeInstanceAssociationsStatusRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 _OptionalDescribeInstanceAssociationsStatusRequestRequestTypeDef = TypedDict(
@@ -1405,14 +1560,36 @@
 
 class InstancePatchStateTypeDef(
     _RequiredInstancePatchStateTypeDef, _OptionalInstancePatchStateTypeDef
 ):
     pass
 
 
+_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
+    {
+        "InstanceIds": Sequence[str],
+    },
+)
+_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef(
+    _RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
+    _OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeInstancePatchStatesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeInstancePatchStatesRequestRequestTypeDef",
     {
         "InstanceIds": Sequence[str],
     },
 )
 _OptionalDescribeInstancePatchStatesRequestRequestTypeDef = TypedDict(
@@ -1454,14 +1631,23 @@
 
 class PatchComplianceDataTypeDef(
     _RequiredPatchComplianceDataTypeDef, _OptionalPatchComplianceDataTypeDef
 ):
     pass
 
 
+DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef = TypedDict(
+    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
+    {
+        "DeletionId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeInventoryDeletionsRequestRequestTypeDef = TypedDict(
     "DescribeInventoryDeletionsRequestRequestTypeDef",
     {
         "DeletionId": str,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -1601,14 +1787,57 @@
 DescribePatchGroupStateRequestRequestTypeDef = TypedDict(
     "DescribePatchGroupStateRequestRequestTypeDef",
     {
         "PatchGroup": str,
     },
 )
 
+DescribePatchGroupStateResultTypeDef = TypedDict(
+    "DescribePatchGroupStateResultTypeDef",
+    {
+        "Instances": int,
+        "InstancesWithInstalledPatches": int,
+        "InstancesWithInstalledOtherPatches": int,
+        "InstancesWithInstalledPendingRebootPatches": int,
+        "InstancesWithInstalledRejectedPatches": int,
+        "InstancesWithMissingPatches": int,
+        "InstancesWithFailedPatches": int,
+        "InstancesWithNotApplicablePatches": int,
+        "InstancesWithUnreportedNotApplicablePatches": int,
+        "InstancesWithCriticalNonCompliantPatches": int,
+        "InstancesWithSecurityNonCompliantPatches": int,
+        "InstancesWithOtherNonCompliantPatches": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
+    "_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
+    {
+        "OperatingSystem": OperatingSystemType,
+        "Property": PatchPropertyType,
+    },
+)
+_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
+    "_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
+    {
+        "PatchSet": PatchSetType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef(
+    _RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
+    _OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribePatchPropertiesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribePatchPropertiesRequestRequestTypeDef",
     {
         "OperatingSystem": OperatingSystemType,
         "Property": PatchPropertyType,
     },
 )
@@ -1626,14 +1855,23 @@
 class DescribePatchPropertiesRequestRequestTypeDef(
     _RequiredDescribePatchPropertiesRequestRequestTypeDef,
     _OptionalDescribePatchPropertiesRequestRequestTypeDef,
 ):
     pass
 
 
+DescribePatchPropertiesResultTypeDef = TypedDict(
+    "DescribePatchPropertiesResultTypeDef",
+    {
+        "Properties": List[Dict[str, str]],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SessionFilterTypeDef = TypedDict(
     "SessionFilterTypeDef",
     {
         "key": SessionFilterKeyType,
         "value": str,
     },
 )
@@ -1764,14 +2002,24 @@
 
 class GetCalendarStateRequestRequestTypeDef(
     _RequiredGetCalendarStateRequestRequestTypeDef, _OptionalGetCalendarStateRequestRequestTypeDef
 ):
     pass
 
 
+GetCalendarStateResponseTypeDef = TypedDict(
+    "GetCalendarStateResponseTypeDef",
+    {
+        "State": CalendarStateType,
+        "AtTime": str,
+        "NextTransitionTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -1803,22 +2051,51 @@
 GetConnectionStatusRequestRequestTypeDef = TypedDict(
     "GetConnectionStatusRequestRequestTypeDef",
     {
         "Target": str,
     },
 )
 
+GetConnectionStatusResponseTypeDef = TypedDict(
+    "GetConnectionStatusResponseTypeDef",
+    {
+        "Target": str,
+        "Status": ConnectionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDefaultPatchBaselineRequestRequestTypeDef = TypedDict(
     "GetDefaultPatchBaselineRequestRequestTypeDef",
     {
         "OperatingSystem": OperatingSystemType,
     },
     total=False,
 )
 
+GetDefaultPatchBaselineResultTypeDef = TypedDict(
+    "GetDefaultPatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "OperatingSystem": OperatingSystemType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetDeployablePatchSnapshotForInstanceResultTypeDef = TypedDict(
+    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
+    {
+        "InstanceId": str,
+        "SnapshotId": str,
+        "SnapshotDownloadUrl": str,
+        "Product": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDocumentRequestRequestTypeDef = TypedDict(
     "_RequiredGetDocumentRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGetDocumentRequestRequestTypeDef = TypedDict(
@@ -1861,14 +2138,25 @@
 ResultAttributeTypeDef = TypedDict(
     "ResultAttributeTypeDef",
     {
         "TypeName": str,
     },
 )
 
+GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef = TypedDict(
+    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
+    {
+        "TypeName": str,
+        "Aggregator": bool,
+        "SubType": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInventorySchemaRequestRequestTypeDef = TypedDict(
     "GetInventorySchemaRequestRequestTypeDef",
     {
         "TypeName": str,
         "NextToken": str,
         "MaxResults": int,
         "Aggregator": bool,
@@ -1880,23 +2168,55 @@
 GetMaintenanceWindowExecutionRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowExecutionRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
     },
 )
 
+GetMaintenanceWindowExecutionResultTypeDef = TypedDict(
+    "GetMaintenanceWindowExecutionResultTypeDef",
+    {
+        "WindowExecutionId": str,
+        "TaskIds": List[str],
+        "Status": MaintenanceWindowExecutionStatusType,
+        "StatusDetails": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
         "TaskId": str,
         "InvocationId": str,
     },
 )
 
+GetMaintenanceWindowExecutionTaskInvocationResultTypeDef = TypedDict(
+    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
+    {
+        "WindowExecutionId": str,
+        "TaskExecutionId": str,
+        "InvocationId": str,
+        "ExecutionId": str,
+        "TaskType": MaintenanceWindowTaskTypeType,
+        "Parameters": str,
+        "Status": MaintenanceWindowExecutionStatusType,
+        "StatusDetails": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "OwnerInformation": str,
+        "WindowTargetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMaintenanceWindowExecutionTaskRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowExecutionTaskRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
         "TaskId": str,
     },
 )
@@ -1912,14 +2232,36 @@
 GetMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
     },
 )
 
+GetMaintenanceWindowResultTypeDef = TypedDict(
+    "GetMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "Name": str,
+        "Description": str,
+        "StartDate": str,
+        "EndDate": str,
+        "Schedule": str,
+        "ScheduleTimezone": str,
+        "ScheduleOffset": int,
+        "NextExecutionTime": str,
+        "Duration": int,
+        "Cutoff": int,
+        "AllowUnassociatedTargets": bool,
+        "Enabled": bool,
+        "CreatedDate": datetime,
+        "ModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMaintenanceWindowTaskRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowTaskRequestRequestTypeDef",
     {
         "WindowId": str,
         "WindowTaskId": str,
     },
 )
@@ -2010,14 +2352,37 @@
 OpsResultAttributeTypeDef = TypedDict(
     "OpsResultAttributeTypeDef",
     {
         "TypeName": str,
     },
 )
 
+_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
+    {
+        "WithDecryption": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef(
+    _RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
+    _OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetParameterHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetParameterHistoryRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGetParameterHistoryRequestRequestTypeDef = TypedDict(
@@ -2114,21 +2479,53 @@
 class GetPatchBaselineForPatchGroupRequestRequestTypeDef(
     _RequiredGetPatchBaselineForPatchGroupRequestRequestTypeDef,
     _OptionalGetPatchBaselineForPatchGroupRequestRequestTypeDef,
 ):
     pass
 
 
+GetPatchBaselineForPatchGroupResultTypeDef = TypedDict(
+    "GetPatchBaselineForPatchGroupResultTypeDef",
+    {
+        "BaselineId": str,
+        "PatchGroup": str,
+        "OperatingSystem": OperatingSystemType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPatchBaselineRequestRequestTypeDef = TypedDict(
     "GetPatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 
+_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
+    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetResourcePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourcePoliciesRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalGetResourcePoliciesRequestRequestTypeDef = TypedDict(
@@ -2289,14 +2686,45 @@
 class LabelParameterVersionRequestRequestTypeDef(
     _RequiredLabelParameterVersionRequestRequestTypeDef,
     _OptionalLabelParameterVersionRequestRequestTypeDef,
 ):
     pass
 
 
+LabelParameterVersionResultTypeDef = TypedDict(
+    "LabelParameterVersionResultTypeDef",
+    {
+        "InvalidLabels": List[str],
+        "ParameterVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
+    {
+        "AssociationId": str,
+    },
+)
+_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef(
+    _RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
+    _OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssociationVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociationVersionsRequestRequestTypeDef",
     {
         "AssociationId": str,
     },
 )
 _OptionalListAssociationVersionsRequestRequestTypeDef = TypedDict(
@@ -2337,14 +2765,36 @@
 class ListDocumentMetadataHistoryRequestRequestTypeDef(
     _RequiredListDocumentMetadataHistoryRequestRequestTypeDef,
     _OptionalListDocumentMetadataHistoryRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef(
+    _RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
+    _OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDocumentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListDocumentVersionsRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalListDocumentVersionsRequestRequestTypeDef = TypedDict(
@@ -2360,14 +2810,27 @@
 class ListDocumentVersionsRequestRequestTypeDef(
     _RequiredListDocumentVersionsRequestRequestTypeDef,
     _OptionalListDocumentVersionsRequestRequestTypeDef,
 ):
     pass
 
 
+ListInventoryEntriesResultTypeDef = TypedDict(
+    "ListInventoryEntriesResultTypeDef",
+    {
+        "TypeName": str,
+        "InstanceId": str,
+        "SchemaVersion": str,
+        "CaptureTime": str,
+        "Entries": List[Dict[str, str]],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OpsItemEventFilterTypeDef = TypedDict(
     "OpsItemEventFilterTypeDef",
     {
         "Key": Literal["OpsItemId"],
         "Values": Sequence[str],
         "Operator": Literal["Equal"],
     },
@@ -2398,14 +2861,23 @@
         "LastModifiedDate": datetime,
         "LastModifiedUser": str,
         "CreationDate": datetime,
     },
     total=False,
 )
 
+ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef = TypedDict(
+    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
+    {
+        "SyncType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceDataSyncRequestRequestTypeDef = TypedDict(
     "ListResourceDataSyncRequestRequestTypeDef",
     {
         "SyncType": str,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -2486,14 +2958,24 @@
     "OpsItemIdentityTypeDef",
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
 ParameterInlinePolicyTypeDef = TypedDict(
     "ParameterInlinePolicyTypeDef",
     {
         "PolicyText": str,
         "PolicyType": str,
         "PolicyStatus": str,
     },
@@ -2504,14 +2986,31 @@
     "PatchFilterTypeDef",
     {
         "Key": PatchFilterKeyType,
         "Values": Sequence[str],
     },
 )
 
+PutInventoryResultTypeDef = TypedDict(
+    "PutInventoryResultTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutParameterResultTypeDef = TypedDict(
+    "PutParameterResultTypeDef",
+    {
+        "Version": int,
+        "Tier": ParameterTierType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Policy": str,
     },
 )
@@ -2527,29 +3026,71 @@
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "PolicyId": str,
+        "PolicyHash": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterDefaultPatchBaselineRequestRequestTypeDef = TypedDict(
     "RegisterDefaultPatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 
+RegisterDefaultPatchBaselineResultTypeDef = TypedDict(
+    "RegisterDefaultPatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterPatchBaselineForPatchGroupRequestRequestTypeDef = TypedDict(
     "RegisterPatchBaselineForPatchGroupRequestRequestTypeDef",
     {
         "BaselineId": str,
         "PatchGroup": str,
     },
 )
 
+RegisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
+    "RegisterPatchBaselineForPatchGroupResultTypeDef",
+    {
+        "BaselineId": str,
+        "PatchGroup": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterTargetWithMaintenanceWindowResultTypeDef = TypedDict(
+    "RegisterTargetWithMaintenanceWindowResultTypeDef",
+    {
+        "WindowTargetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterTaskWithMaintenanceWindowResultTypeDef = TypedDict(
+    "RegisterTaskWithMaintenanceWindowResultTypeDef",
+    {
+        "WindowTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsFromResourceRequestRequestTypeDef = TypedDict(
     "RemoveTagsFromResourceRequestRequestTypeDef",
     {
         "ResourceType": ResourceTypeForTaggingType,
         "ResourceId": str,
         "TagKeys": Sequence[str],
     },
@@ -2574,21 +3115,42 @@
     "ResourceDataSyncDestinationDataSharingTypeDef",
     {
         "DestinationDataSharingType": str,
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
 ResumeSessionRequestRequestTypeDef = TypedDict(
     "ResumeSessionRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+ResumeSessionResponseTypeDef = TypedDict(
+    "ResumeSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "TokenValue": str,
+        "StreamUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendAutomationSignalRequestRequestTypeDef = TypedDict(
     "_RequiredSendAutomationSignalRequestRequestTypeDef",
     {
         "AutomationExecutionId": str,
         "SignalType": SignalTypeType,
     },
 )
@@ -2620,14 +3182,30 @@
 StartAssociationsOnceRequestRequestTypeDef = TypedDict(
     "StartAssociationsOnceRequestRequestTypeDef",
     {
         "AssociationIds": Sequence[str],
     },
 )
 
+StartAutomationExecutionResultTypeDef = TypedDict(
+    "StartAutomationExecutionResultTypeDef",
+    {
+        "AutomationExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartChangeRequestExecutionResultTypeDef = TypedDict(
+    "StartChangeRequestExecutionResultTypeDef",
+    {
+        "AutomationExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartSessionRequestRequestTypeDef = TypedDict(
     "_RequiredStartSessionRequestRequestTypeDef",
     {
         "Target": str,
     },
 )
 _OptionalStartSessionRequestRequestTypeDef = TypedDict(
@@ -2643,14 +3221,24 @@
 
 class StartSessionRequestRequestTypeDef(
     _RequiredStartSessionRequestRequestTypeDef, _OptionalStartSessionRequestRequestTypeDef
 ):
     pass
 
 
+StartSessionResponseTypeDef = TypedDict(
+    "StartSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "TokenValue": str,
+        "StreamUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopAutomationExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredStopAutomationExecutionRequestRequestTypeDef",
     {
         "AutomationExecutionId": str,
     },
 )
 _OptionalStopAutomationExecutionRequestRequestTypeDef = TypedDict(
@@ -2672,23 +3260,40 @@
 TerminateSessionRequestRequestTypeDef = TypedDict(
     "TerminateSessionRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+TerminateSessionResponseTypeDef = TypedDict(
+    "TerminateSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnlabelParameterVersionRequestRequestTypeDef = TypedDict(
     "UnlabelParameterVersionRequestRequestTypeDef",
     {
         "Name": str,
         "ParameterVersion": int,
         "Labels": Sequence[str],
     },
 )
 
+UnlabelParameterVersionResultTypeDef = TypedDict(
+    "UnlabelParameterVersionResultTypeDef",
+    {
+        "RemovedLabels": List[str],
+        "InvalidLabels": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateDocumentDefaultVersionRequestRequestTypeDef = TypedDict(
     "UpdateDocumentDefaultVersionRequestRequestTypeDef",
     {
         "Name": str,
         "DocumentVersion": str,
     },
 )
@@ -2722,30 +3327,67 @@
 class UpdateMaintenanceWindowRequestRequestTypeDef(
     _RequiredUpdateMaintenanceWindowRequestRequestTypeDef,
     _OptionalUpdateMaintenanceWindowRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateMaintenanceWindowResultTypeDef = TypedDict(
+    "UpdateMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "Name": str,
+        "Description": str,
+        "StartDate": str,
+        "EndDate": str,
+        "Schedule": str,
+        "ScheduleTimezone": str,
+        "ScheduleOffset": int,
+        "Duration": int,
+        "Cutoff": int,
+        "AllowUnassociatedTargets": bool,
+        "Enabled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateManagedInstanceRoleRequestRequestTypeDef = TypedDict(
     "UpdateManagedInstanceRoleRequestRequestTypeDef",
     {
         "InstanceId": str,
         "IamRole": str,
     },
 )
 
+UpdateOpsMetadataResultTypeDef = TypedDict(
+    "UpdateOpsMetadataResultTypeDef",
+    {
+        "OpsMetadataArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateServiceSettingRequestRequestTypeDef = TypedDict(
     "UpdateServiceSettingRequestRequestTypeDef",
     {
         "SettingId": str,
         "SettingValue": str,
     },
 )
 
+DescribeDocumentPermissionResponseTypeDef = TypedDict(
+    "DescribeDocumentPermissionResponseTypeDef",
+    {
+        "AccountIds": List[str],
+        "AccountSharingInfoList": List[AccountSharingInfoTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActivationTypeDef = TypedDict(
     "ActivationTypeDef",
     {
         "ActivationId": str,
         "Description": str,
         "DefaultInstanceName": str,
         "IamRole": str,
@@ -2796,14 +3438,22 @@
 class CreateMaintenanceWindowRequestRequestTypeDef(
     _RequiredCreateMaintenanceWindowRequestRequestTypeDef,
     _OptionalCreateMaintenanceWindowRequestRequestTypeDef,
 ):
     pass
 
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "TagList": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutParameterRequestRequestTypeDef = TypedDict(
     "_RequiredPutParameterRequestRequestTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
@@ -2847,434 +3497,14 @@
 
 class AlarmConfigurationTypeDef(
     _RequiredAlarmConfigurationTypeDef, _OptionalAlarmConfigurationTypeDef
 ):
     pass
 
 
-AssociateOpsItemRelatedItemResponseTypeDef = TypedDict(
-    "AssociateOpsItemRelatedItemResponseTypeDef",
-    {
-        "AssociationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelMaintenanceWindowExecutionResultTypeDef = TypedDict(
-    "CancelMaintenanceWindowExecutionResultTypeDef",
-    {
-        "WindowExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateActivationResultTypeDef = TypedDict(
-    "CreateActivationResultTypeDef",
-    {
-        "ActivationId": str,
-        "ActivationCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMaintenanceWindowResultTypeDef = TypedDict(
-    "CreateMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOpsItemResponseTypeDef = TypedDict(
-    "CreateOpsItemResponseTypeDef",
-    {
-        "OpsItemId": str,
-        "OpsItemArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOpsMetadataResultTypeDef = TypedDict(
-    "CreateOpsMetadataResultTypeDef",
-    {
-        "OpsMetadataArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePatchBaselineResultTypeDef = TypedDict(
-    "CreatePatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMaintenanceWindowResultTypeDef = TypedDict(
-    "DeleteMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteParametersResultTypeDef = TypedDict(
-    "DeleteParametersResultTypeDef",
-    {
-        "DeletedParameters": List[str],
-        "InvalidParameters": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePatchBaselineResultTypeDef = TypedDict(
-    "DeletePatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
-    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
-    {
-        "BaselineId": str,
-        "PatchGroup": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterTargetFromMaintenanceWindowResultTypeDef = TypedDict(
-    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "WindowTargetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterTaskFromMaintenanceWindowResultTypeDef = TypedDict(
-    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "WindowTaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDocumentPermissionResponseTypeDef = TypedDict(
-    "DescribeDocumentPermissionResponseTypeDef",
-    {
-        "AccountIds": List[str],
-        "AccountSharingInfoList": List[AccountSharingInfoTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePatchGroupStateResultTypeDef = TypedDict(
-    "DescribePatchGroupStateResultTypeDef",
-    {
-        "Instances": int,
-        "InstancesWithInstalledPatches": int,
-        "InstancesWithInstalledOtherPatches": int,
-        "InstancesWithInstalledPendingRebootPatches": int,
-        "InstancesWithInstalledRejectedPatches": int,
-        "InstancesWithMissingPatches": int,
-        "InstancesWithFailedPatches": int,
-        "InstancesWithNotApplicablePatches": int,
-        "InstancesWithUnreportedNotApplicablePatches": int,
-        "InstancesWithCriticalNonCompliantPatches": int,
-        "InstancesWithSecurityNonCompliantPatches": int,
-        "InstancesWithOtherNonCompliantPatches": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePatchPropertiesResultTypeDef = TypedDict(
-    "DescribePatchPropertiesResultTypeDef",
-    {
-        "Properties": List[Dict[str, str]],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCalendarStateResponseTypeDef = TypedDict(
-    "GetCalendarStateResponseTypeDef",
-    {
-        "State": CalendarStateType,
-        "AtTime": str,
-        "NextTransitionTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetConnectionStatusResponseTypeDef = TypedDict(
-    "GetConnectionStatusResponseTypeDef",
-    {
-        "Target": str,
-        "Status": ConnectionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDefaultPatchBaselineResultTypeDef = TypedDict(
-    "GetDefaultPatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "OperatingSystem": OperatingSystemType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeployablePatchSnapshotForInstanceResultTypeDef = TypedDict(
-    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
-    {
-        "InstanceId": str,
-        "SnapshotId": str,
-        "SnapshotDownloadUrl": str,
-        "Product": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMaintenanceWindowExecutionResultTypeDef = TypedDict(
-    "GetMaintenanceWindowExecutionResultTypeDef",
-    {
-        "WindowExecutionId": str,
-        "TaskIds": List[str],
-        "Status": MaintenanceWindowExecutionStatusType,
-        "StatusDetails": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMaintenanceWindowExecutionTaskInvocationResultTypeDef = TypedDict(
-    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
-    {
-        "WindowExecutionId": str,
-        "TaskExecutionId": str,
-        "InvocationId": str,
-        "ExecutionId": str,
-        "TaskType": MaintenanceWindowTaskTypeType,
-        "Parameters": str,
-        "Status": MaintenanceWindowExecutionStatusType,
-        "StatusDetails": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "OwnerInformation": str,
-        "WindowTargetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMaintenanceWindowResultTypeDef = TypedDict(
-    "GetMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "Name": str,
-        "Description": str,
-        "StartDate": str,
-        "EndDate": str,
-        "Schedule": str,
-        "ScheduleTimezone": str,
-        "ScheduleOffset": int,
-        "NextExecutionTime": str,
-        "Duration": int,
-        "Cutoff": int,
-        "AllowUnassociatedTargets": bool,
-        "Enabled": bool,
-        "CreatedDate": datetime,
-        "ModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPatchBaselineForPatchGroupResultTypeDef = TypedDict(
-    "GetPatchBaselineForPatchGroupResultTypeDef",
-    {
-        "BaselineId": str,
-        "PatchGroup": str,
-        "OperatingSystem": OperatingSystemType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-LabelParameterVersionResultTypeDef = TypedDict(
-    "LabelParameterVersionResultTypeDef",
-    {
-        "InvalidLabels": List[str],
-        "ParameterVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListInventoryEntriesResultTypeDef = TypedDict(
-    "ListInventoryEntriesResultTypeDef",
-    {
-        "TypeName": str,
-        "InstanceId": str,
-        "SchemaVersion": str,
-        "CaptureTime": str,
-        "Entries": List[Dict[str, str]],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutInventoryResultTypeDef = TypedDict(
-    "PutInventoryResultTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutParameterResultTypeDef = TypedDict(
-    "PutParameterResultTypeDef",
-    {
-        "Version": int,
-        "Tier": ParameterTierType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "PolicyId": str,
-        "PolicyHash": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterDefaultPatchBaselineResultTypeDef = TypedDict(
-    "RegisterDefaultPatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
-    "RegisterPatchBaselineForPatchGroupResultTypeDef",
-    {
-        "BaselineId": str,
-        "PatchGroup": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterTargetWithMaintenanceWindowResultTypeDef = TypedDict(
-    "RegisterTargetWithMaintenanceWindowResultTypeDef",
-    {
-        "WindowTargetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterTaskWithMaintenanceWindowResultTypeDef = TypedDict(
-    "RegisterTaskWithMaintenanceWindowResultTypeDef",
-    {
-        "WindowTaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResumeSessionResponseTypeDef = TypedDict(
-    "ResumeSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "TokenValue": str,
-        "StreamUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAutomationExecutionResultTypeDef = TypedDict(
-    "StartAutomationExecutionResultTypeDef",
-    {
-        "AutomationExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartChangeRequestExecutionResultTypeDef = TypedDict(
-    "StartChangeRequestExecutionResultTypeDef",
-    {
-        "AutomationExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSessionResponseTypeDef = TypedDict(
-    "StartSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "TokenValue": str,
-        "StreamUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateSessionResponseTypeDef = TypedDict(
-    "TerminateSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UnlabelParameterVersionResultTypeDef = TypedDict(
-    "UnlabelParameterVersionResultTypeDef",
-    {
-        "RemovedLabels": List[str],
-        "InvalidLabels": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMaintenanceWindowResultTypeDef = TypedDict(
-    "UpdateMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "Name": str,
-        "Description": str,
-        "StartDate": str,
-        "EndDate": str,
-        "Schedule": str,
-        "ScheduleTimezone": str,
-        "ScheduleOffset": int,
-        "Duration": int,
-        "Cutoff": int,
-        "AllowUnassociatedTargets": bool,
-        "Enabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateOpsMetadataResultTypeDef = TypedDict(
-    "UpdateOpsMetadataResultTypeDef",
-    {
-        "OpsMetadataArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateAssociationStatusRequestRequestTypeDef = TypedDict(
     "UpdateAssociationStatusRequestRequestTypeDef",
     {
         "Name": str,
         "InstanceId": str,
         "AssociationStatus": AssociationStatusTypeDef,
     },
@@ -3295,14 +3525,37 @@
         "AssociationName": str,
         "ScheduleOffset": int,
         "TargetMaps": List[Dict[str, List[str]]],
     },
     total=False,
 )
 
+_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
+    {
+        "Targets": Sequence[TargetTypeDef],
+        "ResourceType": MaintenanceWindowResourceTypeType,
+    },
+)
+_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef(
+    _RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
+    _OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeMaintenanceWindowsForTargetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeMaintenanceWindowsForTargetRequestRequestTypeDef",
     {
         "Targets": Sequence[TargetTypeDef],
         "ResourceType": MaintenanceWindowResourceTypeType,
     },
 )
@@ -3396,18 +3649,45 @@
     {
         "WindowId": str,
         "WindowTargetId": str,
         "Targets": List[TargetTypeDef],
         "OwnerInformation": str,
         "Name": str,
         "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
+        {
+            "AssociationId": str,
+        },
+    )
+)
+_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
+        {
+            "Filters": Sequence[AssociationExecutionFilterTypeDef],
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef(
+    _RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
+    _OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeAssociationExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAssociationExecutionsRequestRequestTypeDef",
     {
         "AssociationId": str,
     },
 )
 _OptionalDescribeAssociationExecutionsRequestRequestTypeDef = TypedDict(
@@ -3440,14 +3720,38 @@
         "DetailedStatus": str,
         "LastExecutionDate": datetime,
         "OutputSource": OutputSourceTypeDef,
     },
     total=False,
 )
 
+_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
+    {
+        "AssociationId": str,
+        "ExecutionId": str,
+    },
+)
+_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
+    {
+        "Filters": Sequence[AssociationExecutionTargetsFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef(
+    _RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
+    _OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeAssociationExecutionTargetsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAssociationExecutionTargetsRequestRequestTypeDef",
     {
         "AssociationId": str,
         "ExecutionId": str,
     },
 )
@@ -3465,14 +3769,23 @@
 class DescribeAssociationExecutionTargetsRequestRequestTypeDef(
     _RequiredDescribeAssociationExecutionTargetsRequestRequestTypeDef,
     _OptionalDescribeAssociationExecutionTargetsRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssociationsRequestListAssociationsPaginateTypeDef = TypedDict(
+    "ListAssociationsRequestListAssociationsPaginateTypeDef",
+    {
+        "AssociationFilterList": Sequence[AssociationFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssociationsRequestRequestTypeDef = TypedDict(
     "ListAssociationsRequestRequestTypeDef",
     {
         "AssociationFilterList": Sequence[AssociationFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -3502,14 +3815,23 @@
 
 class UpdateDocumentRequestRequestTypeDef(
     _RequiredUpdateDocumentRequestRequestTypeDef, _OptionalUpdateDocumentRequestRequestTypeDef
 ):
     pass
 
 
+DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef = TypedDict(
+    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
+    {
+        "Filters": Sequence[AutomationExecutionFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAutomationExecutionsRequestRequestTypeDef = TypedDict(
     "DescribeAutomationExecutionsRequestRequestTypeDef",
     {
         "Filters": Sequence[AutomationExecutionFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -3532,31 +3854,54 @@
         "Status": CommandInvocationStatusType,
         "StatusDetails": str,
         "StandardOutputContent": str,
         "StandardOutputUrl": str,
         "StandardErrorContent": str,
         "StandardErrorUrl": str,
         "CloudWatchOutputConfig": CloudWatchOutputConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef = TypedDict(
+    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
+    {
+        "CommandId": str,
+        "InstanceId": str,
+        "Filters": Sequence[CommandFilterTypeDef],
+        "Details": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCommandInvocationsRequestRequestTypeDef = TypedDict(
     "ListCommandInvocationsRequestRequestTypeDef",
     {
         "CommandId": str,
         "InstanceId": str,
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[CommandFilterTypeDef],
         "Details": bool,
     },
     total=False,
 )
 
+ListCommandsRequestListCommandsPaginateTypeDef = TypedDict(
+    "ListCommandsRequestListCommandsPaginateTypeDef",
+    {
+        "CommandId": str,
+        "InstanceId": str,
+        "Filters": Sequence[CommandFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCommandsRequestRequestTypeDef = TypedDict(
     "ListCommandsRequestRequestTypeDef",
     {
         "CommandId": str,
         "InstanceId": str,
         "MaxResults": int,
         "NextToken": str,
@@ -3645,36 +3990,65 @@
 class PutComplianceItemsRequestRequestTypeDef(
     _RequiredPutComplianceItemsRequestRequestTypeDef,
     _OptionalPutComplianceItemsRequestRequestTypeDef,
 ):
     pass
 
 
+ListComplianceItemsRequestListComplianceItemsPaginateTypeDef = TypedDict(
+    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
+    {
+        "Filters": Sequence[ComplianceStringFilterTypeDef],
+        "ResourceIds": Sequence[str],
+        "ResourceTypes": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComplianceItemsRequestRequestTypeDef = TypedDict(
     "ListComplianceItemsRequestRequestTypeDef",
     {
         "Filters": Sequence[ComplianceStringFilterTypeDef],
         "ResourceIds": Sequence[str],
         "ResourceTypes": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef = TypedDict(
+    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
+    {
+        "Filters": Sequence[ComplianceStringFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComplianceSummariesRequestRequestTypeDef = TypedDict(
     "ListComplianceSummariesRequestRequestTypeDef",
     {
         "Filters": Sequence[ComplianceStringFilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef = TypedDict(
+    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
+    {
+        "Filters": Sequence[ComplianceStringFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceComplianceSummariesRequestRequestTypeDef = TypedDict(
     "ListResourceComplianceSummariesRequestRequestTypeDef",
     {
         "Filters": Sequence[ComplianceStringFilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
@@ -3788,15 +4162,15 @@
         "StatusInformation": str,
         "Content": str,
         "DocumentType": DocumentTypeType,
         "DocumentFormat": DocumentFormatType,
         "Requires": List[DocumentRequiresTypeDef],
         "AttachmentsContent": List[AttachmentContentTypeDef],
         "ReviewStatus": ReviewStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpsItemSummaryTypeDef = TypedDict(
     "OpsItemSummaryTypeDef",
     {
         "CreatedBy": str,
@@ -3943,15 +4317,15 @@
 
 GetOpsMetadataResultTypeDef = TypedDict(
     "GetOpsMetadataResultTypeDef",
     {
         "ResourceId": str,
         "Metadata": Dict[str, MetadataValueTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateOpsMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateOpsMetadataRequestRequestTypeDef",
     {
         "OpsMetadataArn": str,
@@ -3969,403 +4343,29 @@
 
 class UpdateOpsMetadataRequestRequestTypeDef(
     _RequiredUpdateOpsMetadataRequestRequestTypeDef, _OptionalUpdateOpsMetadataRequestRequestTypeDef
 ):
     pass
 
 
-DescribeActivationsRequestRequestTypeDef = TypedDict(
-    "DescribeActivationsRequestRequestTypeDef",
-    {
-        "Filters": Sequence[DescribeActivationsFilterTypeDef],
-        "MaxResults": int,
-        "NextToken": str,
-    },
-    total=False,
-)
-
 DescribeActivationsRequestDescribeActivationsPaginateTypeDef = TypedDict(
     "DescribeActivationsRequestDescribeActivationsPaginateTypeDef",
     {
         "Filters": Sequence[DescribeActivationsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
-    {
-        "AssociationId": str,
-        "ExecutionId": str,
-    },
-)
-_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
-    {
-        "Filters": Sequence[AssociationExecutionTargetsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
-class DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef(
-    _RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
-    _OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
-        {
-            "AssociationId": str,
-        },
-    )
-)
-_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
-        {
-            "Filters": Sequence[AssociationExecutionFilterTypeDef],
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef(
-    _RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
-    _OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
-):
-    pass
-
-
-DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef = TypedDict(
-    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
-    {
-        "Filters": Sequence[AutomationExecutionFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
-    {
-        "InstanceId": str,
-    },
-)
-_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef(
-    _RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
-    _OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
-    "_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
-    {
-        "BaselineId": str,
-    },
-)
-_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
-    "_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef(
-    _RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
-    _OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
-    "_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
-    {
-        "InstanceId": str,
-    },
-)
-_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
-    "_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef(
-    _RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
-    _OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
-    {
-        "InstanceIds": Sequence[str],
-    },
-)
-_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef(
-    _RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
-    _OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
-):
-    pass
-
-
-DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef = TypedDict(
-    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
-    {
-        "DeletionId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
-    {
-        "Targets": Sequence[TargetTypeDef],
-        "ResourceType": MaintenanceWindowResourceTypeType,
-    },
-)
-_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef(
-    _RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
-    _OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
-    "_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
-    {
-        "OperatingSystem": OperatingSystemType,
-        "Property": PatchPropertyType,
-    },
-)
-_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
-    "_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
-    {
-        "PatchSet": PatchSetType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef(
-    _RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
-    _OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
-):
-    pass
-
-
-GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef = TypedDict(
-    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
-    {
-        "TypeName": str,
-        "Aggregator": bool,
-        "SubType": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
-    {
-        "WithDecryption": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef(
-    _RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
-    _OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
-    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
-    {
-        "AssociationId": str,
-    },
-)
-_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef(
-    _RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
-    _OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListAssociationsRequestListAssociationsPaginateTypeDef = TypedDict(
-    "ListAssociationsRequestListAssociationsPaginateTypeDef",
-    {
-        "AssociationFilterList": Sequence[AssociationFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef = TypedDict(
-    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
-    {
-        "CommandId": str,
-        "InstanceId": str,
-        "Filters": Sequence[CommandFilterTypeDef],
-        "Details": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCommandsRequestListCommandsPaginateTypeDef = TypedDict(
-    "ListCommandsRequestListCommandsPaginateTypeDef",
-    {
-        "CommandId": str,
-        "InstanceId": str,
-        "Filters": Sequence[CommandFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListComplianceItemsRequestListComplianceItemsPaginateTypeDef = TypedDict(
-    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
-    {
-        "Filters": Sequence[ComplianceStringFilterTypeDef],
-        "ResourceIds": Sequence[str],
-        "ResourceTypes": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef = TypedDict(
-    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
-    {
-        "Filters": Sequence[ComplianceStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef(
-    _RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
-    _OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef = TypedDict(
-    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
-    {
-        "Filters": Sequence[ComplianceStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef = TypedDict(
-    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
+DescribeActivationsRequestRequestTypeDef = TypedDict(
+    "DescribeActivationsRequestRequestTypeDef",
     {
-        "SyncType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": Sequence[DescribeActivationsFilterTypeDef],
+        "MaxResults": int,
+        "NextToken": str,
     },
     total=False,
 )
 
 _RequiredDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef = TypedDict(
     "_RequiredDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef",
     {
@@ -4373,15 +4373,15 @@
     },
 )
 _OptionalDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef = TypedDict(
     "_OptionalDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef",
     {
         "Filters": Sequence[StepExecutionFilterTypeDef],
         "ReverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef(
     _RequiredDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef,
@@ -4415,15 +4415,15 @@
     pass
 
 
 DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef = TypedDict(
     "DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAvailablePatchesRequestRequestTypeDef = TypedDict(
     "DescribeAvailablePatchesRequestRequestTypeDef",
     {
@@ -4440,15 +4440,15 @@
         "InstanceId": str,
     },
 )
 _OptionalDescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef = TypedDict(
     "_OptionalDescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef(
     _RequiredDescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef,
@@ -4485,15 +4485,15 @@
     TypedDict(
         "DescribeMaintenanceWindowScheduleRequestDescribeMaintenanceWindowSchedulePaginateTypeDef",
         {
             "WindowId": str,
             "Targets": Sequence[TargetTypeDef],
             "ResourceType": MaintenanceWindowResourceTypeType,
             "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-            "PaginationConfig": PaginatorConfigTypeDef,
+            "PaginationConfig": "PaginatorConfigTypeDef",
         },
         total=False,
     )
 )
 
 DescribeMaintenanceWindowScheduleRequestRequestTypeDef = TypedDict(
     "DescribeMaintenanceWindowScheduleRequestRequestTypeDef",
@@ -4508,15 +4508,15 @@
     total=False,
 )
 
 DescribePatchBaselinesRequestDescribePatchBaselinesPaginateTypeDef = TypedDict(
     "DescribePatchBaselinesRequestDescribePatchBaselinesPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribePatchBaselinesRequestRequestTypeDef = TypedDict(
     "DescribePatchBaselinesRequestRequestTypeDef",
     {
@@ -4527,15 +4527,15 @@
     total=False,
 )
 
 DescribePatchGroupsRequestDescribePatchGroupsPaginateTypeDef = TypedDict(
     "DescribePatchGroupsRequestDescribePatchGroupsPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribePatchGroupsRequestRequestTypeDef = TypedDict(
     "DescribePatchGroupsRequestRequestTypeDef",
     {
@@ -4547,33 +4547,33 @@
 )
 
 DescribeAvailablePatchesResultTypeDef = TypedDict(
     "DescribeAvailablePatchesResultTypeDef",
     {
         "Patches": List[PatchTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEffectiveInstanceAssociationsResultTypeDef = TypedDict(
     "DescribeEffectiveInstanceAssociationsResultTypeDef",
     {
         "Associations": List[InstanceAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstanceInformationRequestDescribeInstanceInformationPaginateTypeDef = TypedDict(
     "DescribeInstanceInformationRequestDescribeInstanceInformationPaginateTypeDef",
     {
         "InstanceInformationFilterList": Sequence[InstanceInformationFilterTypeDef],
         "Filters": Sequence[InstanceInformationStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeInstanceInformationRequestRequestTypeDef = TypedDict(
     "DescribeInstanceInformationRequestRequestTypeDef",
     {
@@ -4591,15 +4591,15 @@
         "PatchGroup": str,
     },
 )
 _OptionalDescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef = TypedDict(
     "_OptionalDescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef",
     {
         "Filters": Sequence[InstancePatchStateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef(
     _RequiredDescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef,
@@ -4633,48 +4633,48 @@
 
 
 DescribeInstancePatchStatesForPatchGroupResultTypeDef = TypedDict(
     "DescribeInstancePatchStatesForPatchGroupResultTypeDef",
     {
         "InstancePatchStates": List[InstancePatchStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancePatchStatesResultTypeDef = TypedDict(
     "DescribeInstancePatchStatesResultTypeDef",
     {
         "InstancePatchStates": List[InstancePatchStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancePatchesResultTypeDef = TypedDict(
     "DescribeInstancePatchesResultTypeDef",
     {
         "Patches": List[PatchComplianceDataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef = TypedDict(
     "_RequiredDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef",
     {
         "WindowExecutionId": str,
         "TaskId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef,
@@ -4714,15 +4714,15 @@
         "WindowExecutionId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef,
@@ -4761,15 +4761,15 @@
         "WindowId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef,
@@ -4808,15 +4808,15 @@
         "WindowId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef,
@@ -4855,15 +4855,15 @@
         "WindowId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef,
@@ -4896,15 +4896,15 @@
     pass
 
 
 DescribeMaintenanceWindowsRequestDescribeMaintenanceWindowsPaginateTypeDef = TypedDict(
     "DescribeMaintenanceWindowsRequestDescribeMaintenanceWindowsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeMaintenanceWindowsRequestRequestTypeDef = TypedDict(
     "DescribeMaintenanceWindowsRequestRequestTypeDef",
     {
@@ -4918,59 +4918,59 @@
 DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef",
     {
         "WindowExecutionTaskInvocationIdentities": List[
             MaintenanceWindowExecutionTaskInvocationIdentityTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowExecutionsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowExecutionsResultTypeDef",
     {
         "WindowExecutions": List[MaintenanceWindowExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowScheduleResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowScheduleResultTypeDef",
     {
         "ScheduledWindowExecutions": List[ScheduledWindowExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowsForTargetResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowsForTargetResultTypeDef",
     {
         "WindowIdentities": List[MaintenanceWindowIdentityForTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowsResultTypeDef",
     {
         "WindowIdentities": List[MaintenanceWindowIdentityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOpsItemsRequestDescribeOpsItemsPaginateTypeDef = TypedDict(
     "DescribeOpsItemsRequestDescribeOpsItemsPaginateTypeDef",
     {
         "OpsItemFilters": Sequence[OpsItemFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeOpsItemsRequestRequestTypeDef = TypedDict(
     "DescribeOpsItemsRequestRequestTypeDef",
     {
@@ -4989,15 +4989,15 @@
 )
 _OptionalGetParametersByPathRequestGetParametersByPathPaginateTypeDef = TypedDict(
     "_OptionalGetParametersByPathRequestGetParametersByPathPaginateTypeDef",
     {
         "Recursive": bool,
         "ParameterFilters": Sequence[ParameterStringFilterTypeDef],
         "WithDecryption": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetParametersByPathRequestGetParametersByPathPaginateTypeDef(
     _RequiredGetParametersByPathRequestGetParametersByPathPaginateTypeDef,
@@ -5033,15 +5033,15 @@
 
 
 DescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
     "DescribeParametersRequestDescribeParametersPaginateTypeDef",
     {
         "Filters": Sequence[ParametersFilterTypeDef],
         "ParameterFilters": Sequence[ParameterStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeParametersRequestRequestTypeDef = TypedDict(
     "DescribeParametersRequestRequestTypeDef",
     {
@@ -5054,15 +5054,15 @@
 )
 
 DescribePatchBaselinesResultTypeDef = TypedDict(
     "DescribePatchBaselinesResultTypeDef",
     {
         "BaselineIdentities": List[PatchBaselineIdentityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PatchGroupPatchBaselineMappingTypeDef = TypedDict(
     "PatchGroupPatchBaselineMappingTypeDef",
     {
         "PatchGroup": str,
@@ -5077,15 +5077,15 @@
         "State": SessionStateType,
     },
 )
 _OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
     "_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
     {
         "Filters": Sequence[SessionFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeSessionsRequestDescribeSessionsPaginateTypeDef(
     _RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
@@ -5117,15 +5117,15 @@
     pass
 
 
 UpdateDocumentDefaultVersionResultTypeDef = TypedDict(
     "UpdateDocumentDefaultVersionResultTypeDef",
     {
         "Description": DocumentDefaultVersionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentDescriptionTypeDef = TypedDict(
     "DocumentDescriptionTypeDef",
     {
         "Sha1": str,
@@ -5163,15 +5163,15 @@
 )
 
 ListDocumentsRequestListDocumentsPaginateTypeDef = TypedDict(
     "ListDocumentsRequestListDocumentsPaginateTypeDef",
     {
         "DocumentFilterList": Sequence[DocumentFilterTypeDef],
         "Filters": Sequence[DocumentKeyValuesFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDocumentsRequestRequestTypeDef = TypedDict(
     "ListDocumentsRequestRequestTypeDef",
     {
@@ -5215,15 +5215,15 @@
 
 
 ListDocumentVersionsResultTypeDef = TypedDict(
     "ListDocumentVersionsResultTypeDef",
     {
         "DocumentVersions": List[DocumentVersionInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EffectivePatchTypeDef = TypedDict(
     "EffectivePatchTypeDef",
     {
         "Patch": PatchTypeDef,
@@ -5291,15 +5291,15 @@
 
 GetInventoryRequestGetInventoryPaginateTypeDef = TypedDict(
     "GetInventoryRequestGetInventoryPaginateTypeDef",
     {
         "Filters": Sequence[InventoryFilterTypeDef],
         "Aggregators": Sequence["InventoryAggregatorTypeDef"],
         "ResultAttributes": Sequence[ResultAttributeTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetInventoryRequestRequestTypeDef = TypedDict(
     "GetInventoryRequestRequestTypeDef",
     {
@@ -5328,15 +5328,15 @@
 GetOpsSummaryRequestGetOpsSummaryPaginateTypeDef = TypedDict(
     "GetOpsSummaryRequestGetOpsSummaryPaginateTypeDef",
     {
         "SyncName": str,
         "Filters": Sequence[OpsFilterTypeDef],
         "Aggregators": Sequence["OpsAggregatorTypeDef"],
         "ResultAttributes": Sequence[OpsResultAttributeTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetOpsSummaryRequestRequestTypeDef = TypedDict(
     "GetOpsSummaryRequestRequestTypeDef",
     {
@@ -5350,58 +5350,58 @@
     total=False,
 )
 
 GetParameterResultTypeDef = TypedDict(
     "GetParameterResultTypeDef",
     {
         "Parameter": ParameterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParametersByPathResultTypeDef = TypedDict(
     "GetParametersByPathResultTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParametersResultTypeDef = TypedDict(
     "GetParametersResultTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "InvalidParameters": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcePoliciesResponseTypeDef = TypedDict(
     "GetResourcePoliciesResponseTypeDef",
     {
         "NextToken": str,
         "Policies": List[GetResourcePoliciesResponseEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceSettingResultTypeDef = TypedDict(
     "GetServiceSettingResultTypeDef",
     {
         "ServiceSetting": ServiceSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetServiceSettingResultTypeDef = TypedDict(
     "ResetServiceSettingResultTypeDef",
     {
         "ServiceSetting": ServiceSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceInformationTypeDef = TypedDict(
     "InstanceInformationTypeDef",
     {
         "InstanceId": str,
@@ -5495,15 +5495,15 @@
     total=False,
 )
 
 ListOpsItemEventsRequestListOpsItemEventsPaginateTypeDef = TypedDict(
     "ListOpsItemEventsRequestListOpsItemEventsPaginateTypeDef",
     {
         "Filters": Sequence[OpsItemEventFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOpsItemEventsRequestRequestTypeDef = TypedDict(
     "ListOpsItemEventsRequestRequestTypeDef",
     {
@@ -5515,15 +5515,15 @@
 )
 
 ListOpsItemRelatedItemsRequestListOpsItemRelatedItemsPaginateTypeDef = TypedDict(
     "ListOpsItemRelatedItemsRequestListOpsItemRelatedItemsPaginateTypeDef",
     {
         "OpsItemId": str,
         "Filters": Sequence[OpsItemRelatedItemsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOpsItemRelatedItemsRequestRequestTypeDef = TypedDict(
     "ListOpsItemRelatedItemsRequestRequestTypeDef",
     {
@@ -5535,15 +5535,15 @@
     total=False,
 )
 
 ListOpsMetadataRequestListOpsMetadataPaginateTypeDef = TypedDict(
     "ListOpsMetadataRequestListOpsMetadataPaginateTypeDef",
     {
         "Filters": Sequence[OpsMetadataFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOpsMetadataRequestRequestTypeDef = TypedDict(
     "ListOpsMetadataRequestRequestTypeDef",
     {
@@ -5555,15 +5555,15 @@
 )
 
 ListOpsMetadataResultTypeDef = TypedDict(
     "ListOpsMetadataResultTypeDef",
     {
         "OpsMetadataList": List[OpsMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpsEntityTypeDef = TypedDict(
     "OpsEntityTypeDef",
     {
         "Id": str,
@@ -5713,15 +5713,15 @@
 )
 
 DescribeActivationsResultTypeDef = TypedDict(
     "DescribeActivationsResultTypeDef",
     {
         "ActivationList": List[ActivationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociationExecutionTypeDef = TypedDict(
     "AssociationExecutionTypeDef",
     {
         "AssociationId": str,
@@ -5785,15 +5785,15 @@
         "MaxErrors": str,
         "Status": MaintenanceWindowExecutionStatusType,
         "StatusDetails": str,
         "StartTime": datetime,
         "EndTime": datetime,
         "AlarmConfiguration": AlarmConfigurationTypeDef,
         "TriggeredAlarms": List[AlarmStateInformationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MaintenanceWindowExecutionTaskIdentityTypeDef = TypedDict(
     "MaintenanceWindowExecutionTaskIdentityTypeDef",
     {
         "WindowExecutionId": str,
@@ -5883,42 +5883,42 @@
 )
 
 ListAssociationsResultTypeDef = TypedDict(
     "ListAssociationsResultTypeDef",
     {
         "Associations": List[AssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowTargetsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowTargetsResultTypeDef",
     {
         "Targets": List[MaintenanceWindowTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssociationExecutionTargetsResultTypeDef = TypedDict(
     "DescribeAssociationExecutionTargetsResultTypeDef",
     {
         "AssociationExecutionTargets": List[AssociationExecutionTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCommandInvocationsResultTypeDef = TypedDict(
     "ListCommandInvocationsResultTypeDef",
     {
         "CommandInvocations": List[CommandInvocationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MaintenanceWindowTaskInvocationParametersTypeDef = TypedDict(
     "MaintenanceWindowTaskInvocationParametersTypeDef",
     {
         "RunCommand": MaintenanceWindowRunCommandParametersTypeDef,
@@ -5930,15 +5930,15 @@
 )
 
 ListComplianceItemsResultTypeDef = TypedDict(
     "ListComplianceItemsResultTypeDef",
     {
         "ComplianceItems": List[ComplianceItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComplianceSummaryItemTypeDef = TypedDict(
     "ComplianceSummaryItemTypeDef",
     {
         "ComplianceType": str,
@@ -5964,65 +5964,65 @@
 )
 
 ListDocumentsResultTypeDef = TypedDict(
     "ListDocumentsResultTypeDef",
     {
         "DocumentIdentifiers": List[DocumentIdentifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOpsItemsResponseTypeDef = TypedDict(
     "DescribeOpsItemsResponseTypeDef",
     {
         "NextToken": str,
         "OpsItemSummaries": List[OpsItemSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOpsItemResponseTypeDef = TypedDict(
     "GetOpsItemResponseTypeDef",
     {
         "OpsItem": OpsItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePatchGroupsResultTypeDef = TypedDict(
     "DescribePatchGroupsResultTypeDef",
     {
         "Mappings": List[PatchGroupPatchBaselineMappingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDocumentResultTypeDef = TypedDict(
     "CreateDocumentResultTypeDef",
     {
         "DocumentDescription": DocumentDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDocumentResultTypeDef = TypedDict(
     "DescribeDocumentResultTypeDef",
     {
         "Document": DocumentDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDocumentResultTypeDef = TypedDict(
     "UpdateDocumentResultTypeDef",
     {
         "DocumentDescription": DocumentDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentMetadataResponseInfoTypeDef = TypedDict(
     "DocumentMetadataResponseInfoTypeDef",
     {
         "ReviewerResponse": List[DocumentReviewerResponseSourceTypeDef],
@@ -6054,15 +6054,15 @@
 
 
 DescribeEffectivePatchesForPatchBaselineResultTypeDef = TypedDict(
     "DescribeEffectivePatchesForPatchBaselineResultTypeDef",
     {
         "EffectivePatches": List[EffectivePatchTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InventoryAggregatorTypeDef = TypedDict(
     "InventoryAggregatorTypeDef",
     {
         "Expression": str,
@@ -6073,15 +6073,15 @@
 )
 
 DescribeInstanceInformationResultTypeDef = TypedDict(
     "DescribeInstanceInformationResultTypeDef",
     {
         "InstanceInformationList": List[InstanceInformationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceAssociationStatusInfoTypeDef = TypedDict(
     "InstanceAssociationStatusInfoTypeDef",
     {
         "AssociationId": str,
@@ -6102,15 +6102,15 @@
 
 DeleteInventoryResultTypeDef = TypedDict(
     "DeleteInventoryResultTypeDef",
     {
         "DeletionId": str,
         "TypeName": str,
         "DeletionSummary": InventoryDeletionSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InventoryDeletionStatusItemTypeDef = TypedDict(
     "InventoryDeletionStatusItemTypeDef",
     {
         "DeletionId": str,
@@ -6125,69 +6125,69 @@
 )
 
 GetInventorySchemaResultTypeDef = TypedDict(
     "GetInventorySchemaResultTypeDef",
     {
         "Schemas": List[InventoryItemSchemaTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInventoryResultTypeDef = TypedDict(
     "GetInventoryResultTypeDef",
     {
         "Entities": List[InventoryResultEntityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOpsSummaryResultTypeDef = TypedDict(
     "GetOpsSummaryResultTypeDef",
     {
         "Entities": List[OpsEntityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpsItemEventsResponseTypeDef = TypedDict(
     "ListOpsItemEventsResponseTypeDef",
     {
         "NextToken": str,
         "Summaries": List[OpsItemEventSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpsItemRelatedItemsResponseTypeDef = TypedDict(
     "ListOpsItemRelatedItemsResponseTypeDef",
     {
         "NextToken": str,
         "Summaries": List[OpsItemRelatedItemSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParameterHistoryResultTypeDef = TypedDict(
     "GetParameterHistoryResultTypeDef",
     {
         "Parameters": List[ParameterHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParametersResultTypeDef = TypedDict(
     "DescribeParametersResultTypeDef",
     {
         "Parameters": List[ParameterMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPatchRuleTypeDef = TypedDict(
     "_RequiredPatchRuleTypeDef",
     {
         "PatchFilterGroup": PatchFilterGroupTypeDef,
@@ -6247,59 +6247,59 @@
 )
 
 DescribeSessionsResponseTypeDef = TypedDict(
     "DescribeSessionsResponseTypeDef",
     {
         "Sessions": List[SessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssociationExecutionsResultTypeDef = TypedDict(
     "DescribeAssociationExecutionsResultTypeDef",
     {
         "AssociationExecutions": List[AssociationExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCommandsResultTypeDef = TypedDict(
     "ListCommandsResultTypeDef",
     {
         "Commands": List[CommandTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendCommandResultTypeDef = TypedDict(
     "SendCommandResultTypeDef",
     {
         "Command": CommandTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowExecutionTasksResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowExecutionTasksResultTypeDef",
     {
         "WindowExecutionTaskIdentities": List[MaintenanceWindowExecutionTaskIdentityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowTasksResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowTasksResultTypeDef",
     {
         "Tasks": List[MaintenanceWindowTaskTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociationDescriptionTypeDef = TypedDict(
     "AssociationDescriptionTypeDef",
     {
         "Name": str,
@@ -6581,15 +6581,15 @@
         "MaxConcurrency": str,
         "MaxErrors": str,
         "LoggingInfo": LoggingInfoTypeDef,
         "Name": str,
         "Description": str,
         "CutoffBehavior": MaintenanceWindowTaskCutoffBehaviorType,
         "AlarmConfiguration": AlarmConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterTaskWithMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterTaskWithMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
@@ -6675,63 +6675,63 @@
         "MaxConcurrency": str,
         "MaxErrors": str,
         "LoggingInfo": LoggingInfoTypeDef,
         "Name": str,
         "Description": str,
         "CutoffBehavior": MaintenanceWindowTaskCutoffBehaviorType,
         "AlarmConfiguration": AlarmConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComplianceSummariesResultTypeDef = TypedDict(
     "ListComplianceSummariesResultTypeDef",
     {
         "ComplianceSummaryItems": List[ComplianceSummaryItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceComplianceSummariesResultTypeDef = TypedDict(
     "ListResourceComplianceSummariesResultTypeDef",
     {
         "ResourceComplianceSummaryItems": List[ResourceComplianceSummaryItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDocumentMetadataHistoryResponseTypeDef = TypedDict(
     "ListDocumentMetadataHistoryResponseTypeDef",
     {
         "Name": str,
         "DocumentVersion": str,
         "Author": str,
         "Metadata": DocumentMetadataResponseInfoTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstanceAssociationsStatusResultTypeDef = TypedDict(
     "DescribeInstanceAssociationsStatusResultTypeDef",
     {
         "InstanceAssociationStatusInfos": List[InstanceAssociationStatusInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInventoryDeletionsResultTypeDef = TypedDict(
     "DescribeInventoryDeletionsResultTypeDef",
     {
         "InventoryDeletions": List[InventoryDeletionStatusItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PatchRuleGroupTypeDef = TypedDict(
     "PatchRuleGroupTypeDef",
     {
         "PatchRules": Sequence[PatchRuleTypeDef],
@@ -6788,48 +6788,48 @@
     total=False,
 )
 
 CreateAssociationResultTypeDef = TypedDict(
     "CreateAssociationResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssociationResultTypeDef = TypedDict(
     "DescribeAssociationResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssociationResultTypeDef = TypedDict(
     "UpdateAssociationResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssociationStatusResultTypeDef = TypedDict(
     "UpdateAssociationStatusResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssociationVersionsResultTypeDef = TypedDict(
     "ListAssociationVersionsResultTypeDef",
     {
         "AssociationVersions": List[AssociationVersionInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssociationBatchRequestRequestTypeDef = TypedDict(
     "CreateAssociationBatchRequestRequestTypeDef",
     {
         "Entries": Sequence[CreateAssociationBatchRequestEntryTypeDef],
@@ -6955,15 +6955,15 @@
 )
 
 DescribeAutomationStepExecutionsResultTypeDef = TypedDict(
     "DescribeAutomationStepExecutionsResultTypeDef",
     {
         "StepExecutions": List[StepExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BaselineOverrideTypeDef = TypedDict(
     "BaselineOverrideTypeDef",
     {
         "OperatingSystem": OperatingSystemType,
@@ -7026,15 +7026,15 @@
         "RejectedPatches": List[str],
         "RejectedPatchesAction": PatchActionType,
         "PatchGroups": List[str],
         "CreatedDate": datetime,
         "ModifiedDate": datetime,
         "Description": str,
         "Sources": List[PatchSourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePatchBaselineRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
@@ -7079,50 +7079,50 @@
         "ApprovedPatchesEnableNonSecurity": bool,
         "RejectedPatches": List[str],
         "RejectedPatchesAction": PatchActionType,
         "CreatedDate": datetime,
         "ModifiedDate": datetime,
         "Description": str,
         "Sources": List[PatchSourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceDataSyncResultTypeDef = TypedDict(
     "ListResourceDataSyncResultTypeDef",
     {
         "ResourceDataSyncItems": List[ResourceDataSyncItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssociationBatchResultTypeDef = TypedDict(
     "CreateAssociationBatchResultTypeDef",
     {
         "Successful": List[AssociationDescriptionTypeDef],
         "Failed": List[FailedCreateAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAutomationExecutionsResultTypeDef = TypedDict(
     "DescribeAutomationExecutionsResultTypeDef",
     {
         "AutomationExecutionMetadataList": List[AutomationExecutionMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAutomationExecutionResultTypeDef = TypedDict(
     "GetAutomationExecutionResultTypeDef",
     {
         "AutomationExecution": AutomationExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetDeployablePatchSnapshotForInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredGetDeployablePatchSnapshotForInstanceRequestRequestTypeDef",
     {
         "InstanceId": str,
```

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/type_defs.pyi` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -105,15 +105,15 @@
 
 __all__ = (
     "AccountSharingInfoTypeDef",
     "TagTypeDef",
     "AlarmTypeDef",
     "AlarmStateInformationTypeDef",
     "AssociateOpsItemRelatedItemRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateOpsItemRelatedItemResponseTypeDef",
     "AssociationOverviewTypeDef",
     "AssociationStatusTypeDef",
     "TargetTypeDef",
     "AssociationExecutionFilterTypeDef",
     "OutputSourceTypeDef",
     "AssociationExecutionTargetsFilterTypeDef",
     "AssociationFilterTypeDef",
@@ -122,267 +122,267 @@
     "AttachmentsSourceTypeDef",
     "AutomationExecutionFilterTypeDef",
     "ResolvedTargetsTypeDef",
     "ProgressCountersTypeDef",
     "PatchSourceTypeDef",
     "CancelCommandRequestRequestTypeDef",
     "CancelMaintenanceWindowExecutionRequestRequestTypeDef",
+    "CancelMaintenanceWindowExecutionResultTypeDef",
     "CloudWatchOutputConfigTypeDef",
     "CommandFilterTypeDef",
     "CommandPluginTypeDef",
     "NotificationConfigTypeDef",
     "ComplianceExecutionSummaryTypeDef",
     "ComplianceItemEntryTypeDef",
     "ComplianceStringFilterTypeDef",
     "SeveritySummaryTypeDef",
     "RegistrationMetadataItemTypeDef",
+    "CreateActivationResultTypeDef",
     "DocumentRequiresTypeDef",
+    "CreateMaintenanceWindowResultTypeDef",
     "OpsItemDataValueTypeDef",
     "OpsItemNotificationTypeDef",
     "RelatedOpsItemTypeDef",
+    "CreateOpsItemResponseTypeDef",
     "MetadataValueTypeDef",
+    "CreateOpsMetadataResultTypeDef",
+    "CreatePatchBaselineResultTypeDef",
     "DeleteActivationRequestRequestTypeDef",
     "DeleteAssociationRequestRequestTypeDef",
     "DeleteDocumentRequestRequestTypeDef",
     "DeleteInventoryRequestRequestTypeDef",
     "DeleteMaintenanceWindowRequestRequestTypeDef",
+    "DeleteMaintenanceWindowResultTypeDef",
     "DeleteOpsMetadataRequestRequestTypeDef",
     "DeleteParameterRequestRequestTypeDef",
     "DeleteParametersRequestRequestTypeDef",
+    "DeleteParametersResultTypeDef",
     "DeletePatchBaselineRequestRequestTypeDef",
+    "DeletePatchBaselineResultTypeDef",
     "DeleteResourceDataSyncRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "DeregisterManagedInstanceRequestRequestTypeDef",
     "DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef",
+    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
     "DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef",
+    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
     "DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef",
+    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
     "DescribeActivationsFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeAssociationRequestRequestTypeDef",
     "StepExecutionFilterTypeDef",
     "PatchOrchestratorFilterTypeDef",
     "PatchTypeDef",
     "DescribeDocumentPermissionRequestRequestTypeDef",
     "DescribeDocumentRequestRequestTypeDef",
+    "DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
     "DescribeEffectiveInstanceAssociationsRequestRequestTypeDef",
     "InstanceAssociationTypeDef",
+    "DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
     "DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef",
+    "DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
     "DescribeInstanceAssociationsStatusRequestRequestTypeDef",
     "InstanceInformationFilterTypeDef",
     "InstanceInformationStringFilterTypeDef",
     "InstancePatchStateFilterTypeDef",
     "InstancePatchStateTypeDef",
+    "DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
     "DescribeInstancePatchStatesRequestRequestTypeDef",
     "PatchComplianceDataTypeDef",
+    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
     "DescribeInventoryDeletionsRequestRequestTypeDef",
     "MaintenanceWindowFilterTypeDef",
     "MaintenanceWindowExecutionTaskInvocationIdentityTypeDef",
     "MaintenanceWindowExecutionTypeDef",
     "ScheduledWindowExecutionTypeDef",
     "MaintenanceWindowIdentityForTargetTypeDef",
     "MaintenanceWindowIdentityTypeDef",
     "OpsItemFilterTypeDef",
     "ParameterStringFilterTypeDef",
     "ParametersFilterTypeDef",
     "PatchBaselineIdentityTypeDef",
     "DescribePatchGroupStateRequestRequestTypeDef",
+    "DescribePatchGroupStateResultTypeDef",
+    "DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
     "DescribePatchPropertiesRequestRequestTypeDef",
+    "DescribePatchPropertiesResultTypeDef",
     "SessionFilterTypeDef",
     "DisassociateOpsItemRelatedItemRequestRequestTypeDef",
     "DocumentDefaultVersionDescriptionTypeDef",
     "DocumentParameterTypeDef",
     "ReviewInformationTypeDef",
     "DocumentFilterTypeDef",
     "DocumentKeyValuesFilterTypeDef",
     "DocumentReviewCommentSourceTypeDef",
     "DocumentVersionInfoTypeDef",
     "PatchStatusTypeDef",
     "FailureDetailsTypeDef",
     "GetAutomationExecutionRequestRequestTypeDef",
     "GetCalendarStateRequestRequestTypeDef",
+    "GetCalendarStateResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetCommandInvocationRequestRequestTypeDef",
     "GetConnectionStatusRequestRequestTypeDef",
+    "GetConnectionStatusResponseTypeDef",
     "GetDefaultPatchBaselineRequestRequestTypeDef",
+    "GetDefaultPatchBaselineResultTypeDef",
+    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
     "GetDocumentRequestRequestTypeDef",
     "InventoryFilterTypeDef",
     "ResultAttributeTypeDef",
+    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
     "GetInventorySchemaRequestRequestTypeDef",
     "GetMaintenanceWindowExecutionRequestRequestTypeDef",
+    "GetMaintenanceWindowExecutionResultTypeDef",
     "GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef",
+    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
     "GetMaintenanceWindowExecutionTaskRequestRequestTypeDef",
     "MaintenanceWindowTaskParameterValueExpressionTypeDef",
     "GetMaintenanceWindowRequestRequestTypeDef",
+    "GetMaintenanceWindowResultTypeDef",
     "GetMaintenanceWindowTaskRequestRequestTypeDef",
     "LoggingInfoTypeDef",
     "GetOpsItemRequestRequestTypeDef",
     "GetOpsMetadataRequestRequestTypeDef",
     "OpsFilterTypeDef",
     "OpsResultAttributeTypeDef",
+    "GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
     "GetParameterHistoryRequestRequestTypeDef",
     "GetParameterRequestRequestTypeDef",
     "ParameterTypeDef",
     "GetParametersRequestRequestTypeDef",
     "GetPatchBaselineForPatchGroupRequestRequestTypeDef",
+    "GetPatchBaselineForPatchGroupResultTypeDef",
     "GetPatchBaselineRequestRequestTypeDef",
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesRequestRequestTypeDef",
     "GetResourcePoliciesResponseEntryTypeDef",
     "GetServiceSettingRequestRequestTypeDef",
     "ServiceSettingTypeDef",
     "InstanceAggregatedAssociationOverviewTypeDef",
     "S3OutputLocationTypeDef",
     "S3OutputUrlTypeDef",
     "InventoryDeletionSummaryItemTypeDef",
     "InventoryItemAttributeTypeDef",
     "InventoryItemTypeDef",
     "InventoryResultItemTypeDef",
     "LabelParameterVersionRequestRequestTypeDef",
+    "LabelParameterVersionResultTypeDef",
+    "ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
     "ListAssociationVersionsRequestRequestTypeDef",
     "ListDocumentMetadataHistoryRequestRequestTypeDef",
+    "ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
     "ListDocumentVersionsRequestRequestTypeDef",
+    "ListInventoryEntriesResultTypeDef",
     "OpsItemEventFilterTypeDef",
     "OpsItemRelatedItemsFilterTypeDef",
     "OpsMetadataFilterTypeDef",
     "OpsMetadataTypeDef",
+    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
     "ListResourceDataSyncRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MaintenanceWindowAutomationParametersTypeDef",
     "MaintenanceWindowLambdaParametersTypeDef",
     "MaintenanceWindowStepFunctionsParametersTypeDef",
     "ModifyDocumentPermissionRequestRequestTypeDef",
     "OpsEntityItemTypeDef",
     "OpsItemIdentityTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterInlinePolicyTypeDef",
     "PatchFilterTypeDef",
+    "PutInventoryResultTypeDef",
+    "PutParameterResultTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
     "RegisterDefaultPatchBaselineRequestRequestTypeDef",
+    "RegisterDefaultPatchBaselineResultTypeDef",
     "RegisterPatchBaselineForPatchGroupRequestRequestTypeDef",
+    "RegisterPatchBaselineForPatchGroupResultTypeDef",
+    "RegisterTargetWithMaintenanceWindowResultTypeDef",
+    "RegisterTaskWithMaintenanceWindowResultTypeDef",
     "RemoveTagsFromResourceRequestRequestTypeDef",
     "ResetServiceSettingRequestRequestTypeDef",
     "ResourceDataSyncOrganizationalUnitTypeDef",
     "ResourceDataSyncDestinationDataSharingTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeSessionRequestRequestTypeDef",
+    "ResumeSessionResponseTypeDef",
     "SendAutomationSignalRequestRequestTypeDef",
     "SessionManagerOutputUrlTypeDef",
     "StartAssociationsOnceRequestRequestTypeDef",
+    "StartAutomationExecutionResultTypeDef",
+    "StartChangeRequestExecutionResultTypeDef",
     "StartSessionRequestRequestTypeDef",
+    "StartSessionResponseTypeDef",
     "StopAutomationExecutionRequestRequestTypeDef",
     "TerminateSessionRequestRequestTypeDef",
+    "TerminateSessionResponseTypeDef",
     "UnlabelParameterVersionRequestRequestTypeDef",
+    "UnlabelParameterVersionResultTypeDef",
     "UpdateDocumentDefaultVersionRequestRequestTypeDef",
     "UpdateMaintenanceWindowRequestRequestTypeDef",
+    "UpdateMaintenanceWindowResultTypeDef",
     "UpdateManagedInstanceRoleRequestRequestTypeDef",
+    "UpdateOpsMetadataResultTypeDef",
     "UpdateServiceSettingRequestRequestTypeDef",
+    "DescribeDocumentPermissionResponseTypeDef",
     "ActivationTypeDef",
     "AddTagsToResourceRequestRequestTypeDef",
     "CreateMaintenanceWindowRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
     "PutParameterRequestRequestTypeDef",
     "AlarmConfigurationTypeDef",
-    "AssociateOpsItemRelatedItemResponseTypeDef",
-    "CancelMaintenanceWindowExecutionResultTypeDef",
-    "CreateActivationResultTypeDef",
-    "CreateMaintenanceWindowResultTypeDef",
-    "CreateOpsItemResponseTypeDef",
-    "CreateOpsMetadataResultTypeDef",
-    "CreatePatchBaselineResultTypeDef",
-    "DeleteMaintenanceWindowResultTypeDef",
-    "DeleteParametersResultTypeDef",
-    "DeletePatchBaselineResultTypeDef",
-    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
-    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
-    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
-    "DescribeDocumentPermissionResponseTypeDef",
-    "DescribePatchGroupStateResultTypeDef",
-    "DescribePatchPropertiesResultTypeDef",
-    "GetCalendarStateResponseTypeDef",
-    "GetConnectionStatusResponseTypeDef",
-    "GetDefaultPatchBaselineResultTypeDef",
-    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
-    "GetMaintenanceWindowExecutionResultTypeDef",
-    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
-    "GetMaintenanceWindowResultTypeDef",
-    "GetPatchBaselineForPatchGroupResultTypeDef",
-    "LabelParameterVersionResultTypeDef",
-    "ListInventoryEntriesResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "PutInventoryResultTypeDef",
-    "PutParameterResultTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "RegisterDefaultPatchBaselineResultTypeDef",
-    "RegisterPatchBaselineForPatchGroupResultTypeDef",
-    "RegisterTargetWithMaintenanceWindowResultTypeDef",
-    "RegisterTaskWithMaintenanceWindowResultTypeDef",
-    "ResumeSessionResponseTypeDef",
-    "StartAutomationExecutionResultTypeDef",
-    "StartChangeRequestExecutionResultTypeDef",
-    "StartSessionResponseTypeDef",
-    "TerminateSessionResponseTypeDef",
-    "UnlabelParameterVersionResultTypeDef",
-    "UpdateMaintenanceWindowResultTypeDef",
-    "UpdateOpsMetadataResultTypeDef",
     "UpdateAssociationStatusRequestRequestTypeDef",
     "AssociationTypeDef",
+    "DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
     "DescribeMaintenanceWindowsForTargetRequestRequestTypeDef",
     "MaintenanceWindowTargetTypeDef",
     "RegisterTargetWithMaintenanceWindowRequestRequestTypeDef",
     "UpdateMaintenanceWindowTargetRequestRequestTypeDef",
     "UpdateMaintenanceWindowTargetResultTypeDef",
+    "DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
     "DescribeAssociationExecutionsRequestRequestTypeDef",
     "AssociationExecutionTargetTypeDef",
+    "DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
     "DescribeAssociationExecutionTargetsRequestRequestTypeDef",
+    "ListAssociationsRequestListAssociationsPaginateTypeDef",
     "ListAssociationsRequestRequestTypeDef",
     "UpdateDocumentRequestRequestTypeDef",
+    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
     "DescribeAutomationExecutionsRequestRequestTypeDef",
     "GetCommandInvocationResultTypeDef",
+    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
     "ListCommandInvocationsRequestRequestTypeDef",
+    "ListCommandsRequestListCommandsPaginateTypeDef",
     "ListCommandsRequestRequestTypeDef",
     "CommandInvocationTypeDef",
     "MaintenanceWindowRunCommandParametersTypeDef",
     "ComplianceItemTypeDef",
     "PutComplianceItemsRequestRequestTypeDef",
+    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
     "ListComplianceItemsRequestRequestTypeDef",
+    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
     "ListComplianceSummariesRequestRequestTypeDef",
+    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
     "ListResourceComplianceSummariesRequestRequestTypeDef",
     "CompliantSummaryTypeDef",
     "NonCompliantSummaryTypeDef",
     "CreateActivationRequestRequestTypeDef",
     "CreateDocumentRequestRequestTypeDef",
     "DocumentIdentifierTypeDef",
     "GetDocumentResultTypeDef",
     "OpsItemSummaryTypeDef",
     "CreateOpsItemRequestRequestTypeDef",
     "OpsItemTypeDef",
     "UpdateOpsItemRequestRequestTypeDef",
     "CreateOpsMetadataRequestRequestTypeDef",
     "GetOpsMetadataResultTypeDef",
     "UpdateOpsMetadataRequestRequestTypeDef",
-    "DescribeActivationsRequestRequestTypeDef",
     "DescribeActivationsRequestDescribeActivationsPaginateTypeDef",
-    "DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
-    "DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
-    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
-    "DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
-    "DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
-    "DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
-    "DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
-    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
-    "DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
-    "DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
-    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
-    "GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    "ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
-    "ListAssociationsRequestListAssociationsPaginateTypeDef",
-    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
-    "ListCommandsRequestListCommandsPaginateTypeDef",
-    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
-    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
-    "ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
-    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
-    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
+    "DescribeActivationsRequestRequestTypeDef",
     "DescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef",
     "DescribeAutomationStepExecutionsRequestRequestTypeDef",
     "DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef",
     "DescribeAvailablePatchesRequestRequestTypeDef",
     "DescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef",
     "DescribeInstancePatchesRequestRequestTypeDef",
     "DescribeMaintenanceWindowScheduleRequestDescribeMaintenanceWindowSchedulePaginateTypeDef",
@@ -601,22 +601,19 @@
         "OpsItemId": str,
         "AssociationType": str,
         "ResourceType": str,
         "ResourceUri": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateOpsItemRelatedItemResponseTypeDef = TypedDict(
+    "AssociateOpsItemRelatedItemResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AssociationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociationOverviewTypeDef = TypedDict(
     "AssociationOverviewTypeDef",
     {
         "Status": str,
@@ -780,14 +777,22 @@
 CancelMaintenanceWindowExecutionRequestRequestTypeDef = TypedDict(
     "CancelMaintenanceWindowExecutionRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
     },
 )
 
+CancelMaintenanceWindowExecutionResultTypeDef = TypedDict(
+    "CancelMaintenanceWindowExecutionResultTypeDef",
+    {
+        "WindowExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CloudWatchOutputConfigTypeDef = TypedDict(
     "CloudWatchOutputConfigTypeDef",
     {
         "CloudWatchLogGroupName": str,
         "CloudWatchOutputEnabled": bool,
     },
     total=False,
@@ -899,14 +904,23 @@
     "RegistrationMetadataItemTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateActivationResultTypeDef = TypedDict(
+    "CreateActivationResultTypeDef",
+    {
+        "ActivationId": str,
+        "ActivationCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDocumentRequiresTypeDef = TypedDict(
     "_RequiredDocumentRequiresTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDocumentRequiresTypeDef = TypedDict(
@@ -918,14 +932,22 @@
     },
     total=False,
 )
 
 class DocumentRequiresTypeDef(_RequiredDocumentRequiresTypeDef, _OptionalDocumentRequiresTypeDef):
     pass
 
+CreateMaintenanceWindowResultTypeDef = TypedDict(
+    "CreateMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OpsItemDataValueTypeDef = TypedDict(
     "OpsItemDataValueTypeDef",
     {
         "Value": str,
         "Type": OpsItemDataTypeType,
     },
     total=False,
@@ -942,22 +964,47 @@
 RelatedOpsItemTypeDef = TypedDict(
     "RelatedOpsItemTypeDef",
     {
         "OpsItemId": str,
     },
 )
 
+CreateOpsItemResponseTypeDef = TypedDict(
+    "CreateOpsItemResponseTypeDef",
+    {
+        "OpsItemId": str,
+        "OpsItemArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MetadataValueTypeDef = TypedDict(
     "MetadataValueTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
+CreateOpsMetadataResultTypeDef = TypedDict(
+    "CreateOpsMetadataResultTypeDef",
+    {
+        "OpsMetadataArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePatchBaselineResultTypeDef = TypedDict(
+    "CreatePatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteActivationRequestRequestTypeDef = TypedDict(
     "DeleteActivationRequestRequestTypeDef",
     {
         "ActivationId": str,
     },
 )
 
@@ -1016,14 +1063,22 @@
 DeleteMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "DeleteMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
     },
 )
 
+DeleteMaintenanceWindowResultTypeDef = TypedDict(
+    "DeleteMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteOpsMetadataRequestRequestTypeDef = TypedDict(
     "DeleteOpsMetadataRequestRequestTypeDef",
     {
         "OpsMetadataArn": str,
     },
 )
 
@@ -1037,21 +1092,38 @@
 DeleteParametersRequestRequestTypeDef = TypedDict(
     "DeleteParametersRequestRequestTypeDef",
     {
         "Names": Sequence[str],
     },
 )
 
+DeleteParametersResultTypeDef = TypedDict(
+    "DeleteParametersResultTypeDef",
+    {
+        "DeletedParameters": List[str],
+        "InvalidParameters": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeletePatchBaselineRequestRequestTypeDef = TypedDict(
     "DeletePatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 
+DeletePatchBaselineResultTypeDef = TypedDict(
+    "DeletePatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteResourceDataSyncRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourceDataSyncRequestRequestTypeDef",
     {
         "SyncName": str,
     },
 )
 _OptionalDeleteResourceDataSyncRequestRequestTypeDef = TypedDict(
@@ -1088,14 +1160,23 @@
     "DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef",
     {
         "BaselineId": str,
         "PatchGroup": str,
     },
 )
 
+DeregisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
+    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
+    {
+        "BaselineId": str,
+        "PatchGroup": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "_RequiredDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
         "WindowTargetId": str,
     },
 )
@@ -1109,37 +1190,45 @@
 
 class DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef(
     _RequiredDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef,
     _OptionalDeregisterTargetFromMaintenanceWindowRequestRequestTypeDef,
 ):
     pass
 
+DeregisterTargetFromMaintenanceWindowResultTypeDef = TypedDict(
+    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "WindowTargetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
         "WindowTaskId": str,
     },
 )
 
-DescribeActivationsFilterTypeDef = TypedDict(
-    "DescribeActivationsFilterTypeDef",
+DeregisterTaskFromMaintenanceWindowResultTypeDef = TypedDict(
+    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
     {
-        "FilterKey": DescribeActivationsFilterKeysType,
-        "FilterValues": Sequence[str],
+        "WindowId": str,
+        "WindowTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeActivationsFilterTypeDef = TypedDict(
+    "DescribeActivationsFilterTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FilterKey": DescribeActivationsFilterKeysType,
+        "FilterValues": Sequence[str],
     },
     total=False,
 )
 
 DescribeAssociationRequestRequestTypeDef = TypedDict(
     "DescribeAssociationRequestRequestTypeDef",
     {
@@ -1236,14 +1325,34 @@
 )
 
 class DescribeDocumentRequestRequestTypeDef(
     _RequiredDescribeDocumentRequestRequestTypeDef, _OptionalDescribeDocumentRequestRequestTypeDef
 ):
     pass
 
+_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
+    {
+        "InstanceId": str,
+    },
+)
+_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef(
+    _RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
+    _OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeEffectiveInstanceAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEffectiveInstanceAssociationsRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 _OptionalDescribeEffectiveInstanceAssociationsRequestRequestTypeDef = TypedDict(
@@ -1268,14 +1377,34 @@
         "InstanceId": str,
         "Content": str,
         "AssociationVersion": str,
     },
     total=False,
 )
 
+_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
+    "_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
+    {
+        "BaselineId": str,
+    },
+)
+_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
+    "_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef(
+    _RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
+    _OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 _OptionalDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef = TypedDict(
@@ -1289,14 +1418,34 @@
 
 class DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef(
     _RequiredDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef,
     _OptionalDescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
+    "_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
+    {
+        "InstanceId": str,
+    },
+)
+_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
+    "_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef(
+    _RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
+    _OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeInstanceAssociationsStatusRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeInstanceAssociationsStatusRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 _OptionalDescribeInstanceAssociationsStatusRequestRequestTypeDef = TypedDict(
@@ -1374,14 +1523,34 @@
 )
 
 class InstancePatchStateTypeDef(
     _RequiredInstancePatchStateTypeDef, _OptionalInstancePatchStateTypeDef
 ):
     pass
 
+_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
+    {
+        "InstanceIds": Sequence[str],
+    },
+)
+_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef(
+    _RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
+    _OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeInstancePatchStatesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeInstancePatchStatesRequestRequestTypeDef",
     {
         "InstanceIds": Sequence[str],
     },
 )
 _OptionalDescribeInstancePatchStatesRequestRequestTypeDef = TypedDict(
@@ -1419,14 +1588,23 @@
 )
 
 class PatchComplianceDataTypeDef(
     _RequiredPatchComplianceDataTypeDef, _OptionalPatchComplianceDataTypeDef
 ):
     pass
 
+DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef = TypedDict(
+    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
+    {
+        "DeletionId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeInventoryDeletionsRequestRequestTypeDef = TypedDict(
     "DescribeInventoryDeletionsRequestRequestTypeDef",
     {
         "DeletionId": str,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -1564,14 +1742,55 @@
 DescribePatchGroupStateRequestRequestTypeDef = TypedDict(
     "DescribePatchGroupStateRequestRequestTypeDef",
     {
         "PatchGroup": str,
     },
 )
 
+DescribePatchGroupStateResultTypeDef = TypedDict(
+    "DescribePatchGroupStateResultTypeDef",
+    {
+        "Instances": int,
+        "InstancesWithInstalledPatches": int,
+        "InstancesWithInstalledOtherPatches": int,
+        "InstancesWithInstalledPendingRebootPatches": int,
+        "InstancesWithInstalledRejectedPatches": int,
+        "InstancesWithMissingPatches": int,
+        "InstancesWithFailedPatches": int,
+        "InstancesWithNotApplicablePatches": int,
+        "InstancesWithUnreportedNotApplicablePatches": int,
+        "InstancesWithCriticalNonCompliantPatches": int,
+        "InstancesWithSecurityNonCompliantPatches": int,
+        "InstancesWithOtherNonCompliantPatches": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
+    "_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
+    {
+        "OperatingSystem": OperatingSystemType,
+        "Property": PatchPropertyType,
+    },
+)
+_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
+    "_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
+    {
+        "PatchSet": PatchSetType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef(
+    _RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
+    _OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribePatchPropertiesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribePatchPropertiesRequestRequestTypeDef",
     {
         "OperatingSystem": OperatingSystemType,
         "Property": PatchPropertyType,
     },
 )
@@ -1587,14 +1806,23 @@
 
 class DescribePatchPropertiesRequestRequestTypeDef(
     _RequiredDescribePatchPropertiesRequestRequestTypeDef,
     _OptionalDescribePatchPropertiesRequestRequestTypeDef,
 ):
     pass
 
+DescribePatchPropertiesResultTypeDef = TypedDict(
+    "DescribePatchPropertiesResultTypeDef",
+    {
+        "Properties": List[Dict[str, str]],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SessionFilterTypeDef = TypedDict(
     "SessionFilterTypeDef",
     {
         "key": SessionFilterKeyType,
         "value": str,
     },
 )
@@ -1723,14 +1951,24 @@
 )
 
 class GetCalendarStateRequestRequestTypeDef(
     _RequiredGetCalendarStateRequestRequestTypeDef, _OptionalGetCalendarStateRequestRequestTypeDef
 ):
     pass
 
+GetCalendarStateResponseTypeDef = TypedDict(
+    "GetCalendarStateResponseTypeDef",
+    {
+        "State": CalendarStateType,
+        "AtTime": str,
+        "NextTransitionTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -1760,22 +1998,51 @@
 GetConnectionStatusRequestRequestTypeDef = TypedDict(
     "GetConnectionStatusRequestRequestTypeDef",
     {
         "Target": str,
     },
 )
 
+GetConnectionStatusResponseTypeDef = TypedDict(
+    "GetConnectionStatusResponseTypeDef",
+    {
+        "Target": str,
+        "Status": ConnectionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDefaultPatchBaselineRequestRequestTypeDef = TypedDict(
     "GetDefaultPatchBaselineRequestRequestTypeDef",
     {
         "OperatingSystem": OperatingSystemType,
     },
     total=False,
 )
 
+GetDefaultPatchBaselineResultTypeDef = TypedDict(
+    "GetDefaultPatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "OperatingSystem": OperatingSystemType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetDeployablePatchSnapshotForInstanceResultTypeDef = TypedDict(
+    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
+    {
+        "InstanceId": str,
+        "SnapshotId": str,
+        "SnapshotDownloadUrl": str,
+        "Product": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetDocumentRequestRequestTypeDef = TypedDict(
     "_RequiredGetDocumentRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGetDocumentRequestRequestTypeDef = TypedDict(
@@ -1814,14 +2081,25 @@
 ResultAttributeTypeDef = TypedDict(
     "ResultAttributeTypeDef",
     {
         "TypeName": str,
     },
 )
 
+GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef = TypedDict(
+    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
+    {
+        "TypeName": str,
+        "Aggregator": bool,
+        "SubType": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInventorySchemaRequestRequestTypeDef = TypedDict(
     "GetInventorySchemaRequestRequestTypeDef",
     {
         "TypeName": str,
         "NextToken": str,
         "MaxResults": int,
         "Aggregator": bool,
@@ -1833,23 +2111,55 @@
 GetMaintenanceWindowExecutionRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowExecutionRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
     },
 )
 
+GetMaintenanceWindowExecutionResultTypeDef = TypedDict(
+    "GetMaintenanceWindowExecutionResultTypeDef",
+    {
+        "WindowExecutionId": str,
+        "TaskIds": List[str],
+        "Status": MaintenanceWindowExecutionStatusType,
+        "StatusDetails": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
         "TaskId": str,
         "InvocationId": str,
     },
 )
 
+GetMaintenanceWindowExecutionTaskInvocationResultTypeDef = TypedDict(
+    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
+    {
+        "WindowExecutionId": str,
+        "TaskExecutionId": str,
+        "InvocationId": str,
+        "ExecutionId": str,
+        "TaskType": MaintenanceWindowTaskTypeType,
+        "Parameters": str,
+        "Status": MaintenanceWindowExecutionStatusType,
+        "StatusDetails": str,
+        "StartTime": datetime,
+        "EndTime": datetime,
+        "OwnerInformation": str,
+        "WindowTargetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMaintenanceWindowExecutionTaskRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowExecutionTaskRequestRequestTypeDef",
     {
         "WindowExecutionId": str,
         "TaskId": str,
     },
 )
@@ -1865,14 +2175,36 @@
 GetMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
     },
 )
 
+GetMaintenanceWindowResultTypeDef = TypedDict(
+    "GetMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "Name": str,
+        "Description": str,
+        "StartDate": str,
+        "EndDate": str,
+        "Schedule": str,
+        "ScheduleTimezone": str,
+        "ScheduleOffset": int,
+        "NextExecutionTime": str,
+        "Duration": int,
+        "Cutoff": int,
+        "AllowUnassociatedTargets": bool,
+        "Enabled": bool,
+        "CreatedDate": datetime,
+        "ModifiedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMaintenanceWindowTaskRequestRequestTypeDef = TypedDict(
     "GetMaintenanceWindowTaskRequestRequestTypeDef",
     {
         "WindowId": str,
         "WindowTaskId": str,
     },
 )
@@ -1955,14 +2287,35 @@
 OpsResultAttributeTypeDef = TypedDict(
     "OpsResultAttributeTypeDef",
     {
         "TypeName": str,
     },
 )
 
+_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
+    {
+        "WithDecryption": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef(
+    _RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
+    _OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetParameterHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetParameterHistoryRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGetParameterHistoryRequestRequestTypeDef = TypedDict(
@@ -2051,21 +2404,51 @@
 
 class GetPatchBaselineForPatchGroupRequestRequestTypeDef(
     _RequiredGetPatchBaselineForPatchGroupRequestRequestTypeDef,
     _OptionalGetPatchBaselineForPatchGroupRequestRequestTypeDef,
 ):
     pass
 
+GetPatchBaselineForPatchGroupResultTypeDef = TypedDict(
+    "GetPatchBaselineForPatchGroupResultTypeDef",
+    {
+        "BaselineId": str,
+        "PatchGroup": str,
+        "OperatingSystem": OperatingSystemType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPatchBaselineRequestRequestTypeDef = TypedDict(
     "GetPatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 
+_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
+    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetResourcePoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourcePoliciesRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalGetResourcePoliciesRequestRequestTypeDef = TypedDict(
@@ -2218,14 +2601,43 @@
 
 class LabelParameterVersionRequestRequestTypeDef(
     _RequiredLabelParameterVersionRequestRequestTypeDef,
     _OptionalLabelParameterVersionRequestRequestTypeDef,
 ):
     pass
 
+LabelParameterVersionResultTypeDef = TypedDict(
+    "LabelParameterVersionResultTypeDef",
+    {
+        "InvalidLabels": List[str],
+        "ParameterVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
+    {
+        "AssociationId": str,
+    },
+)
+_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef(
+    _RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
+    _OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssociationVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssociationVersionsRequestRequestTypeDef",
     {
         "AssociationId": str,
     },
 )
 _OptionalListAssociationVersionsRequestRequestTypeDef = TypedDict(
@@ -2262,14 +2674,34 @@
 
 class ListDocumentMetadataHistoryRequestRequestTypeDef(
     _RequiredListDocumentMetadataHistoryRequestRequestTypeDef,
     _OptionalListDocumentMetadataHistoryRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
+    {
+        "Name": str,
+    },
+)
+_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef(
+    _RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
+    _OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDocumentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListDocumentVersionsRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalListDocumentVersionsRequestRequestTypeDef = TypedDict(
@@ -2283,14 +2715,27 @@
 
 class ListDocumentVersionsRequestRequestTypeDef(
     _RequiredListDocumentVersionsRequestRequestTypeDef,
     _OptionalListDocumentVersionsRequestRequestTypeDef,
 ):
     pass
 
+ListInventoryEntriesResultTypeDef = TypedDict(
+    "ListInventoryEntriesResultTypeDef",
+    {
+        "TypeName": str,
+        "InstanceId": str,
+        "SchemaVersion": str,
+        "CaptureTime": str,
+        "Entries": List[Dict[str, str]],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OpsItemEventFilterTypeDef = TypedDict(
     "OpsItemEventFilterTypeDef",
     {
         "Key": Literal["OpsItemId"],
         "Values": Sequence[str],
         "Operator": Literal["Equal"],
     },
@@ -2321,14 +2766,23 @@
         "LastModifiedDate": datetime,
         "LastModifiedUser": str,
         "CreationDate": datetime,
     },
     total=False,
 )
 
+ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef = TypedDict(
+    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
+    {
+        "SyncType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceDataSyncRequestRequestTypeDef = TypedDict(
     "ListResourceDataSyncRequestRequestTypeDef",
     {
         "SyncType": str,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -2407,14 +2861,24 @@
     "OpsItemIdentityTypeDef",
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
 ParameterInlinePolicyTypeDef = TypedDict(
     "ParameterInlinePolicyTypeDef",
     {
         "PolicyText": str,
         "PolicyType": str,
         "PolicyStatus": str,
     },
@@ -2425,14 +2889,31 @@
     "PatchFilterTypeDef",
     {
         "Key": PatchFilterKeyType,
         "Values": Sequence[str],
     },
 )
 
+PutInventoryResultTypeDef = TypedDict(
+    "PutInventoryResultTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutParameterResultTypeDef = TypedDict(
+    "PutParameterResultTypeDef",
+    {
+        "Version": int,
+        "Tier": ParameterTierType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Policy": str,
     },
 )
@@ -2446,29 +2927,71 @@
 )
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "PolicyId": str,
+        "PolicyHash": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterDefaultPatchBaselineRequestRequestTypeDef = TypedDict(
     "RegisterDefaultPatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
     },
 )
 
+RegisterDefaultPatchBaselineResultTypeDef = TypedDict(
+    "RegisterDefaultPatchBaselineResultTypeDef",
+    {
+        "BaselineId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterPatchBaselineForPatchGroupRequestRequestTypeDef = TypedDict(
     "RegisterPatchBaselineForPatchGroupRequestRequestTypeDef",
     {
         "BaselineId": str,
         "PatchGroup": str,
     },
 )
 
+RegisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
+    "RegisterPatchBaselineForPatchGroupResultTypeDef",
+    {
+        "BaselineId": str,
+        "PatchGroup": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterTargetWithMaintenanceWindowResultTypeDef = TypedDict(
+    "RegisterTargetWithMaintenanceWindowResultTypeDef",
+    {
+        "WindowTargetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterTaskWithMaintenanceWindowResultTypeDef = TypedDict(
+    "RegisterTaskWithMaintenanceWindowResultTypeDef",
+    {
+        "WindowTaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsFromResourceRequestRequestTypeDef = TypedDict(
     "RemoveTagsFromResourceRequestRequestTypeDef",
     {
         "ResourceType": ResourceTypeForTaggingType,
         "ResourceId": str,
         "TagKeys": Sequence[str],
     },
@@ -2493,21 +3016,42 @@
     "ResourceDataSyncDestinationDataSharingTypeDef",
     {
         "DestinationDataSharingType": str,
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
 ResumeSessionRequestRequestTypeDef = TypedDict(
     "ResumeSessionRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+ResumeSessionResponseTypeDef = TypedDict(
+    "ResumeSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "TokenValue": str,
+        "StreamUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendAutomationSignalRequestRequestTypeDef = TypedDict(
     "_RequiredSendAutomationSignalRequestRequestTypeDef",
     {
         "AutomationExecutionId": str,
         "SignalType": SignalTypeType,
     },
 )
@@ -2537,14 +3081,30 @@
 StartAssociationsOnceRequestRequestTypeDef = TypedDict(
     "StartAssociationsOnceRequestRequestTypeDef",
     {
         "AssociationIds": Sequence[str],
     },
 )
 
+StartAutomationExecutionResultTypeDef = TypedDict(
+    "StartAutomationExecutionResultTypeDef",
+    {
+        "AutomationExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartChangeRequestExecutionResultTypeDef = TypedDict(
+    "StartChangeRequestExecutionResultTypeDef",
+    {
+        "AutomationExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartSessionRequestRequestTypeDef = TypedDict(
     "_RequiredStartSessionRequestRequestTypeDef",
     {
         "Target": str,
     },
 )
 _OptionalStartSessionRequestRequestTypeDef = TypedDict(
@@ -2558,14 +3118,24 @@
 )
 
 class StartSessionRequestRequestTypeDef(
     _RequiredStartSessionRequestRequestTypeDef, _OptionalStartSessionRequestRequestTypeDef
 ):
     pass
 
+StartSessionResponseTypeDef = TypedDict(
+    "StartSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "TokenValue": str,
+        "StreamUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopAutomationExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredStopAutomationExecutionRequestRequestTypeDef",
     {
         "AutomationExecutionId": str,
     },
 )
 _OptionalStopAutomationExecutionRequestRequestTypeDef = TypedDict(
@@ -2585,23 +3155,40 @@
 TerminateSessionRequestRequestTypeDef = TypedDict(
     "TerminateSessionRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+TerminateSessionResponseTypeDef = TypedDict(
+    "TerminateSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnlabelParameterVersionRequestRequestTypeDef = TypedDict(
     "UnlabelParameterVersionRequestRequestTypeDef",
     {
         "Name": str,
         "ParameterVersion": int,
         "Labels": Sequence[str],
     },
 )
 
+UnlabelParameterVersionResultTypeDef = TypedDict(
+    "UnlabelParameterVersionResultTypeDef",
+    {
+        "RemovedLabels": List[str],
+        "InvalidLabels": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateDocumentDefaultVersionRequestRequestTypeDef = TypedDict(
     "UpdateDocumentDefaultVersionRequestRequestTypeDef",
     {
         "Name": str,
         "DocumentVersion": str,
     },
 )
@@ -2633,30 +3220,67 @@
 
 class UpdateMaintenanceWindowRequestRequestTypeDef(
     _RequiredUpdateMaintenanceWindowRequestRequestTypeDef,
     _OptionalUpdateMaintenanceWindowRequestRequestTypeDef,
 ):
     pass
 
+UpdateMaintenanceWindowResultTypeDef = TypedDict(
+    "UpdateMaintenanceWindowResultTypeDef",
+    {
+        "WindowId": str,
+        "Name": str,
+        "Description": str,
+        "StartDate": str,
+        "EndDate": str,
+        "Schedule": str,
+        "ScheduleTimezone": str,
+        "ScheduleOffset": int,
+        "Duration": int,
+        "Cutoff": int,
+        "AllowUnassociatedTargets": bool,
+        "Enabled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateManagedInstanceRoleRequestRequestTypeDef = TypedDict(
     "UpdateManagedInstanceRoleRequestRequestTypeDef",
     {
         "InstanceId": str,
         "IamRole": str,
     },
 )
 
+UpdateOpsMetadataResultTypeDef = TypedDict(
+    "UpdateOpsMetadataResultTypeDef",
+    {
+        "OpsMetadataArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateServiceSettingRequestRequestTypeDef = TypedDict(
     "UpdateServiceSettingRequestRequestTypeDef",
     {
         "SettingId": str,
         "SettingValue": str,
     },
 )
 
+DescribeDocumentPermissionResponseTypeDef = TypedDict(
+    "DescribeDocumentPermissionResponseTypeDef",
+    {
+        "AccountIds": List[str],
+        "AccountSharingInfoList": List[AccountSharingInfoTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ActivationTypeDef = TypedDict(
     "ActivationTypeDef",
     {
         "ActivationId": str,
         "Description": str,
         "DefaultInstanceName": str,
         "IamRole": str,
@@ -2705,14 +3329,22 @@
 
 class CreateMaintenanceWindowRequestRequestTypeDef(
     _RequiredCreateMaintenanceWindowRequestRequestTypeDef,
     _OptionalCreateMaintenanceWindowRequestRequestTypeDef,
 ):
     pass
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "TagList": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutParameterRequestRequestTypeDef = TypedDict(
     "_RequiredPutParameterRequestRequestTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
@@ -2752,434 +3384,14 @@
 )
 
 class AlarmConfigurationTypeDef(
     _RequiredAlarmConfigurationTypeDef, _OptionalAlarmConfigurationTypeDef
 ):
     pass
 
-AssociateOpsItemRelatedItemResponseTypeDef = TypedDict(
-    "AssociateOpsItemRelatedItemResponseTypeDef",
-    {
-        "AssociationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelMaintenanceWindowExecutionResultTypeDef = TypedDict(
-    "CancelMaintenanceWindowExecutionResultTypeDef",
-    {
-        "WindowExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateActivationResultTypeDef = TypedDict(
-    "CreateActivationResultTypeDef",
-    {
-        "ActivationId": str,
-        "ActivationCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMaintenanceWindowResultTypeDef = TypedDict(
-    "CreateMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOpsItemResponseTypeDef = TypedDict(
-    "CreateOpsItemResponseTypeDef",
-    {
-        "OpsItemId": str,
-        "OpsItemArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateOpsMetadataResultTypeDef = TypedDict(
-    "CreateOpsMetadataResultTypeDef",
-    {
-        "OpsMetadataArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePatchBaselineResultTypeDef = TypedDict(
-    "CreatePatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMaintenanceWindowResultTypeDef = TypedDict(
-    "DeleteMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteParametersResultTypeDef = TypedDict(
-    "DeleteParametersResultTypeDef",
-    {
-        "DeletedParameters": List[str],
-        "InvalidParameters": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePatchBaselineResultTypeDef = TypedDict(
-    "DeletePatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
-    "DeregisterPatchBaselineForPatchGroupResultTypeDef",
-    {
-        "BaselineId": str,
-        "PatchGroup": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterTargetFromMaintenanceWindowResultTypeDef = TypedDict(
-    "DeregisterTargetFromMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "WindowTargetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeregisterTaskFromMaintenanceWindowResultTypeDef = TypedDict(
-    "DeregisterTaskFromMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "WindowTaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDocumentPermissionResponseTypeDef = TypedDict(
-    "DescribeDocumentPermissionResponseTypeDef",
-    {
-        "AccountIds": List[str],
-        "AccountSharingInfoList": List[AccountSharingInfoTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePatchGroupStateResultTypeDef = TypedDict(
-    "DescribePatchGroupStateResultTypeDef",
-    {
-        "Instances": int,
-        "InstancesWithInstalledPatches": int,
-        "InstancesWithInstalledOtherPatches": int,
-        "InstancesWithInstalledPendingRebootPatches": int,
-        "InstancesWithInstalledRejectedPatches": int,
-        "InstancesWithMissingPatches": int,
-        "InstancesWithFailedPatches": int,
-        "InstancesWithNotApplicablePatches": int,
-        "InstancesWithUnreportedNotApplicablePatches": int,
-        "InstancesWithCriticalNonCompliantPatches": int,
-        "InstancesWithSecurityNonCompliantPatches": int,
-        "InstancesWithOtherNonCompliantPatches": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePatchPropertiesResultTypeDef = TypedDict(
-    "DescribePatchPropertiesResultTypeDef",
-    {
-        "Properties": List[Dict[str, str]],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCalendarStateResponseTypeDef = TypedDict(
-    "GetCalendarStateResponseTypeDef",
-    {
-        "State": CalendarStateType,
-        "AtTime": str,
-        "NextTransitionTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetConnectionStatusResponseTypeDef = TypedDict(
-    "GetConnectionStatusResponseTypeDef",
-    {
-        "Target": str,
-        "Status": ConnectionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDefaultPatchBaselineResultTypeDef = TypedDict(
-    "GetDefaultPatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "OperatingSystem": OperatingSystemType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeployablePatchSnapshotForInstanceResultTypeDef = TypedDict(
-    "GetDeployablePatchSnapshotForInstanceResultTypeDef",
-    {
-        "InstanceId": str,
-        "SnapshotId": str,
-        "SnapshotDownloadUrl": str,
-        "Product": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMaintenanceWindowExecutionResultTypeDef = TypedDict(
-    "GetMaintenanceWindowExecutionResultTypeDef",
-    {
-        "WindowExecutionId": str,
-        "TaskIds": List[str],
-        "Status": MaintenanceWindowExecutionStatusType,
-        "StatusDetails": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMaintenanceWindowExecutionTaskInvocationResultTypeDef = TypedDict(
-    "GetMaintenanceWindowExecutionTaskInvocationResultTypeDef",
-    {
-        "WindowExecutionId": str,
-        "TaskExecutionId": str,
-        "InvocationId": str,
-        "ExecutionId": str,
-        "TaskType": MaintenanceWindowTaskTypeType,
-        "Parameters": str,
-        "Status": MaintenanceWindowExecutionStatusType,
-        "StatusDetails": str,
-        "StartTime": datetime,
-        "EndTime": datetime,
-        "OwnerInformation": str,
-        "WindowTargetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMaintenanceWindowResultTypeDef = TypedDict(
-    "GetMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "Name": str,
-        "Description": str,
-        "StartDate": str,
-        "EndDate": str,
-        "Schedule": str,
-        "ScheduleTimezone": str,
-        "ScheduleOffset": int,
-        "NextExecutionTime": str,
-        "Duration": int,
-        "Cutoff": int,
-        "AllowUnassociatedTargets": bool,
-        "Enabled": bool,
-        "CreatedDate": datetime,
-        "ModifiedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPatchBaselineForPatchGroupResultTypeDef = TypedDict(
-    "GetPatchBaselineForPatchGroupResultTypeDef",
-    {
-        "BaselineId": str,
-        "PatchGroup": str,
-        "OperatingSystem": OperatingSystemType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-LabelParameterVersionResultTypeDef = TypedDict(
-    "LabelParameterVersionResultTypeDef",
-    {
-        "InvalidLabels": List[str],
-        "ParameterVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListInventoryEntriesResultTypeDef = TypedDict(
-    "ListInventoryEntriesResultTypeDef",
-    {
-        "TypeName": str,
-        "InstanceId": str,
-        "SchemaVersion": str,
-        "CaptureTime": str,
-        "Entries": List[Dict[str, str]],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutInventoryResultTypeDef = TypedDict(
-    "PutInventoryResultTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutParameterResultTypeDef = TypedDict(
-    "PutParameterResultTypeDef",
-    {
-        "Version": int,
-        "Tier": ParameterTierType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "PolicyId": str,
-        "PolicyHash": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterDefaultPatchBaselineResultTypeDef = TypedDict(
-    "RegisterDefaultPatchBaselineResultTypeDef",
-    {
-        "BaselineId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterPatchBaselineForPatchGroupResultTypeDef = TypedDict(
-    "RegisterPatchBaselineForPatchGroupResultTypeDef",
-    {
-        "BaselineId": str,
-        "PatchGroup": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterTargetWithMaintenanceWindowResultTypeDef = TypedDict(
-    "RegisterTargetWithMaintenanceWindowResultTypeDef",
-    {
-        "WindowTargetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterTaskWithMaintenanceWindowResultTypeDef = TypedDict(
-    "RegisterTaskWithMaintenanceWindowResultTypeDef",
-    {
-        "WindowTaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResumeSessionResponseTypeDef = TypedDict(
-    "ResumeSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "TokenValue": str,
-        "StreamUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAutomationExecutionResultTypeDef = TypedDict(
-    "StartAutomationExecutionResultTypeDef",
-    {
-        "AutomationExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartChangeRequestExecutionResultTypeDef = TypedDict(
-    "StartChangeRequestExecutionResultTypeDef",
-    {
-        "AutomationExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSessionResponseTypeDef = TypedDict(
-    "StartSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "TokenValue": str,
-        "StreamUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateSessionResponseTypeDef = TypedDict(
-    "TerminateSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UnlabelParameterVersionResultTypeDef = TypedDict(
-    "UnlabelParameterVersionResultTypeDef",
-    {
-        "RemovedLabels": List[str],
-        "InvalidLabels": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMaintenanceWindowResultTypeDef = TypedDict(
-    "UpdateMaintenanceWindowResultTypeDef",
-    {
-        "WindowId": str,
-        "Name": str,
-        "Description": str,
-        "StartDate": str,
-        "EndDate": str,
-        "Schedule": str,
-        "ScheduleTimezone": str,
-        "ScheduleOffset": int,
-        "Duration": int,
-        "Cutoff": int,
-        "AllowUnassociatedTargets": bool,
-        "Enabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateOpsMetadataResultTypeDef = TypedDict(
-    "UpdateOpsMetadataResultTypeDef",
-    {
-        "OpsMetadataArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateAssociationStatusRequestRequestTypeDef = TypedDict(
     "UpdateAssociationStatusRequestRequestTypeDef",
     {
         "Name": str,
         "InstanceId": str,
         "AssociationStatus": AssociationStatusTypeDef,
     },
@@ -3200,14 +3412,35 @@
         "AssociationName": str,
         "ScheduleOffset": int,
         "TargetMaps": List[Dict[str, List[str]]],
     },
     total=False,
 )
 
+_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
+    {
+        "Targets": Sequence[TargetTypeDef],
+        "ResourceType": MaintenanceWindowResourceTypeType,
+    },
+)
+_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef(
+    _RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
+    _OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeMaintenanceWindowsForTargetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeMaintenanceWindowsForTargetRequestRequestTypeDef",
     {
         "Targets": Sequence[TargetTypeDef],
         "ResourceType": MaintenanceWindowResourceTypeType,
     },
 )
@@ -3295,18 +3528,43 @@
     {
         "WindowId": str,
         "WindowTargetId": str,
         "Targets": List[TargetTypeDef],
         "OwnerInformation": str,
         "Name": str,
         "Description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
+        {
+            "AssociationId": str,
+        },
+    )
+)
+_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
+        {
+            "Filters": Sequence[AssociationExecutionFilterTypeDef],
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef(
+    _RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
+    _OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeAssociationExecutionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAssociationExecutionsRequestRequestTypeDef",
     {
         "AssociationId": str,
     },
 )
 _OptionalDescribeAssociationExecutionsRequestRequestTypeDef = TypedDict(
@@ -3337,14 +3595,36 @@
         "DetailedStatus": str,
         "LastExecutionDate": datetime,
         "OutputSource": OutputSourceTypeDef,
     },
     total=False,
 )
 
+_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
+    {
+        "AssociationId": str,
+        "ExecutionId": str,
+    },
+)
+_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
+    {
+        "Filters": Sequence[AssociationExecutionTargetsFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef(
+    _RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
+    _OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeAssociationExecutionTargetsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAssociationExecutionTargetsRequestRequestTypeDef",
     {
         "AssociationId": str,
         "ExecutionId": str,
     },
 )
@@ -3360,14 +3640,23 @@
 
 class DescribeAssociationExecutionTargetsRequestRequestTypeDef(
     _RequiredDescribeAssociationExecutionTargetsRequestRequestTypeDef,
     _OptionalDescribeAssociationExecutionTargetsRequestRequestTypeDef,
 ):
     pass
 
+ListAssociationsRequestListAssociationsPaginateTypeDef = TypedDict(
+    "ListAssociationsRequestListAssociationsPaginateTypeDef",
+    {
+        "AssociationFilterList": Sequence[AssociationFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssociationsRequestRequestTypeDef = TypedDict(
     "ListAssociationsRequestRequestTypeDef",
     {
         "AssociationFilterList": Sequence[AssociationFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -3395,14 +3684,23 @@
 )
 
 class UpdateDocumentRequestRequestTypeDef(
     _RequiredUpdateDocumentRequestRequestTypeDef, _OptionalUpdateDocumentRequestRequestTypeDef
 ):
     pass
 
+DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef = TypedDict(
+    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
+    {
+        "Filters": Sequence[AutomationExecutionFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAutomationExecutionsRequestRequestTypeDef = TypedDict(
     "DescribeAutomationExecutionsRequestRequestTypeDef",
     {
         "Filters": Sequence[AutomationExecutionFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -3425,31 +3723,54 @@
         "Status": CommandInvocationStatusType,
         "StatusDetails": str,
         "StandardOutputContent": str,
         "StandardOutputUrl": str,
         "StandardErrorContent": str,
         "StandardErrorUrl": str,
         "CloudWatchOutputConfig": CloudWatchOutputConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef = TypedDict(
+    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
+    {
+        "CommandId": str,
+        "InstanceId": str,
+        "Filters": Sequence[CommandFilterTypeDef],
+        "Details": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCommandInvocationsRequestRequestTypeDef = TypedDict(
     "ListCommandInvocationsRequestRequestTypeDef",
     {
         "CommandId": str,
         "InstanceId": str,
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[CommandFilterTypeDef],
         "Details": bool,
     },
     total=False,
 )
 
+ListCommandsRequestListCommandsPaginateTypeDef = TypedDict(
+    "ListCommandsRequestListCommandsPaginateTypeDef",
+    {
+        "CommandId": str,
+        "InstanceId": str,
+        "Filters": Sequence[CommandFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCommandsRequestRequestTypeDef = TypedDict(
     "ListCommandsRequestRequestTypeDef",
     {
         "CommandId": str,
         "InstanceId": str,
         "MaxResults": int,
         "NextToken": str,
@@ -3536,36 +3857,65 @@
 
 class PutComplianceItemsRequestRequestTypeDef(
     _RequiredPutComplianceItemsRequestRequestTypeDef,
     _OptionalPutComplianceItemsRequestRequestTypeDef,
 ):
     pass
 
+ListComplianceItemsRequestListComplianceItemsPaginateTypeDef = TypedDict(
+    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
+    {
+        "Filters": Sequence[ComplianceStringFilterTypeDef],
+        "ResourceIds": Sequence[str],
+        "ResourceTypes": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComplianceItemsRequestRequestTypeDef = TypedDict(
     "ListComplianceItemsRequestRequestTypeDef",
     {
         "Filters": Sequence[ComplianceStringFilterTypeDef],
         "ResourceIds": Sequence[str],
         "ResourceTypes": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef = TypedDict(
+    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
+    {
+        "Filters": Sequence[ComplianceStringFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListComplianceSummariesRequestRequestTypeDef = TypedDict(
     "ListComplianceSummariesRequestRequestTypeDef",
     {
         "Filters": Sequence[ComplianceStringFilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef = TypedDict(
+    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
+    {
+        "Filters": Sequence[ComplianceStringFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceComplianceSummariesRequestRequestTypeDef = TypedDict(
     "ListResourceComplianceSummariesRequestRequestTypeDef",
     {
         "Filters": Sequence[ComplianceStringFilterTypeDef],
         "NextToken": str,
         "MaxResults": int,
     },
@@ -3675,15 +4025,15 @@
         "StatusInformation": str,
         "Content": str,
         "DocumentType": DocumentTypeType,
         "DocumentFormat": DocumentFormatType,
         "Requires": List[DocumentRequiresTypeDef],
         "AttachmentsContent": List[AttachmentContentTypeDef],
         "ReviewStatus": ReviewStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpsItemSummaryTypeDef = TypedDict(
     "OpsItemSummaryTypeDef",
     {
         "CreatedBy": str,
@@ -3824,15 +4174,15 @@
 
 GetOpsMetadataResultTypeDef = TypedDict(
     "GetOpsMetadataResultTypeDef",
     {
         "ResourceId": str,
         "Metadata": Dict[str, MetadataValueTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateOpsMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateOpsMetadataRequestRequestTypeDef",
     {
         "OpsMetadataArn": str,
@@ -3848,379 +4198,29 @@
 )
 
 class UpdateOpsMetadataRequestRequestTypeDef(
     _RequiredUpdateOpsMetadataRequestRequestTypeDef, _OptionalUpdateOpsMetadataRequestRequestTypeDef
 ):
     pass
 
-DescribeActivationsRequestRequestTypeDef = TypedDict(
-    "DescribeActivationsRequestRequestTypeDef",
-    {
-        "Filters": Sequence[DescribeActivationsFilterTypeDef],
-        "MaxResults": int,
-        "NextToken": str,
-    },
-    total=False,
-)
-
 DescribeActivationsRequestDescribeActivationsPaginateTypeDef = TypedDict(
     "DescribeActivationsRequestDescribeActivationsPaginateTypeDef",
     {
         "Filters": Sequence[DescribeActivationsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
-    {
-        "AssociationId": str,
-        "ExecutionId": str,
-    },
-)
-_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef",
-    {
-        "Filters": Sequence[AssociationExecutionTargetsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef(
-    _RequiredDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
-    _OptionalDescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
-        {
-            "AssociationId": str,
-        },
-    )
-)
-_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef",
-        {
-            "Filters": Sequence[AssociationExecutionFilterTypeDef],
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef(
-    _RequiredDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
-    _OptionalDescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
-):
-    pass
-
-DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef = TypedDict(
-    "DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef",
-    {
-        "Filters": Sequence[AutomationExecutionFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
-    {
-        "InstanceId": str,
-    },
-)
-_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef(
-    _RequiredDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
-    _OptionalDescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
-    "_RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
-    {
-        "BaselineId": str,
-    },
-)
-_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef = TypedDict(
-    "_OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef(
-    _RequiredDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
-    _OptionalDescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
-    "_RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
-    {
-        "InstanceId": str,
-    },
-)
-_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef = TypedDict(
-    "_OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef(
-    _RequiredDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
-    _OptionalDescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
-    {
-        "InstanceIds": Sequence[str],
-    },
-)
-_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef(
-    _RequiredDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
-    _OptionalDescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
-):
-    pass
-
-DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef = TypedDict(
-    "DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef",
-    {
-        "DeletionId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
-    {
-        "Targets": Sequence[TargetTypeDef],
-        "ResourceType": MaintenanceWindowResourceTypeType,
-    },
-)
-_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef(
-    _RequiredDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
-    _OptionalDescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
-    "_RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
-    {
-        "OperatingSystem": OperatingSystemType,
-        "Property": PatchPropertyType,
-    },
-)
-_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef = TypedDict(
-    "_OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef",
-    {
-        "PatchSet": PatchSetType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef(
-    _RequiredDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
-    _OptionalDescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
-):
-    pass
-
-GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef = TypedDict(
-    "GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef",
-    {
-        "TypeName": str,
-        "Aggregator": bool,
-        "SubType": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef",
-    {
-        "WithDecryption": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef(
-    _RequiredGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
-    _OptionalGetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
-):
-    pass
-
-_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef(
-    _RequiredGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    _OptionalGetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
-    {
-        "AssociationId": str,
-    },
-)
-_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef(
-    _RequiredListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
-    _OptionalListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
-):
-    pass
-
-ListAssociationsRequestListAssociationsPaginateTypeDef = TypedDict(
-    "ListAssociationsRequestListAssociationsPaginateTypeDef",
-    {
-        "AssociationFilterList": Sequence[AssociationFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef = TypedDict(
-    "ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef",
-    {
-        "CommandId": str,
-        "InstanceId": str,
-        "Filters": Sequence[CommandFilterTypeDef],
-        "Details": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCommandsRequestListCommandsPaginateTypeDef = TypedDict(
-    "ListCommandsRequestListCommandsPaginateTypeDef",
-    {
-        "CommandId": str,
-        "InstanceId": str,
-        "Filters": Sequence[CommandFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListComplianceItemsRequestListComplianceItemsPaginateTypeDef = TypedDict(
-    "ListComplianceItemsRequestListComplianceItemsPaginateTypeDef",
-    {
-        "Filters": Sequence[ComplianceStringFilterTypeDef],
-        "ResourceIds": Sequence[str],
-        "ResourceTypes": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef = TypedDict(
-    "ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef",
-    {
-        "Filters": Sequence[ComplianceStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
-    {
-        "Name": str,
-    },
-)
-_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef(
-    _RequiredListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
-    _OptionalListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
-):
-    pass
-
-ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef = TypedDict(
-    "ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef",
-    {
-        "Filters": Sequence[ComplianceStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef = TypedDict(
-    "ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef",
+DescribeActivationsRequestRequestTypeDef = TypedDict(
+    "DescribeActivationsRequestRequestTypeDef",
     {
-        "SyncType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": Sequence[DescribeActivationsFilterTypeDef],
+        "MaxResults": int,
+        "NextToken": str,
     },
     total=False,
 )
 
 _RequiredDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef = TypedDict(
     "_RequiredDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef",
     {
@@ -4228,15 +4228,15 @@
     },
 )
 _OptionalDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef = TypedDict(
     "_OptionalDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef",
     {
         "Filters": Sequence[StepExecutionFilterTypeDef],
         "ReverseOrder": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef(
     _RequiredDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef,
     _OptionalDescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef,
@@ -4266,15 +4266,15 @@
 ):
     pass
 
 DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef = TypedDict(
     "DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAvailablePatchesRequestRequestTypeDef = TypedDict(
     "DescribeAvailablePatchesRequestRequestTypeDef",
     {
@@ -4291,15 +4291,15 @@
         "InstanceId": str,
     },
 )
 _OptionalDescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef = TypedDict(
     "_OptionalDescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef(
     _RequiredDescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef,
     _OptionalDescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef,
@@ -4332,15 +4332,15 @@
     TypedDict(
         "DescribeMaintenanceWindowScheduleRequestDescribeMaintenanceWindowSchedulePaginateTypeDef",
         {
             "WindowId": str,
             "Targets": Sequence[TargetTypeDef],
             "ResourceType": MaintenanceWindowResourceTypeType,
             "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-            "PaginationConfig": PaginatorConfigTypeDef,
+            "PaginationConfig": "PaginatorConfigTypeDef",
         },
         total=False,
     )
 )
 
 DescribeMaintenanceWindowScheduleRequestRequestTypeDef = TypedDict(
     "DescribeMaintenanceWindowScheduleRequestRequestTypeDef",
@@ -4355,15 +4355,15 @@
     total=False,
 )
 
 DescribePatchBaselinesRequestDescribePatchBaselinesPaginateTypeDef = TypedDict(
     "DescribePatchBaselinesRequestDescribePatchBaselinesPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribePatchBaselinesRequestRequestTypeDef = TypedDict(
     "DescribePatchBaselinesRequestRequestTypeDef",
     {
@@ -4374,15 +4374,15 @@
     total=False,
 )
 
 DescribePatchGroupsRequestDescribePatchGroupsPaginateTypeDef = TypedDict(
     "DescribePatchGroupsRequestDescribePatchGroupsPaginateTypeDef",
     {
         "Filters": Sequence[PatchOrchestratorFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribePatchGroupsRequestRequestTypeDef = TypedDict(
     "DescribePatchGroupsRequestRequestTypeDef",
     {
@@ -4394,33 +4394,33 @@
 )
 
 DescribeAvailablePatchesResultTypeDef = TypedDict(
     "DescribeAvailablePatchesResultTypeDef",
     {
         "Patches": List[PatchTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEffectiveInstanceAssociationsResultTypeDef = TypedDict(
     "DescribeEffectiveInstanceAssociationsResultTypeDef",
     {
         "Associations": List[InstanceAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstanceInformationRequestDescribeInstanceInformationPaginateTypeDef = TypedDict(
     "DescribeInstanceInformationRequestDescribeInstanceInformationPaginateTypeDef",
     {
         "InstanceInformationFilterList": Sequence[InstanceInformationFilterTypeDef],
         "Filters": Sequence[InstanceInformationStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeInstanceInformationRequestRequestTypeDef = TypedDict(
     "DescribeInstanceInformationRequestRequestTypeDef",
     {
@@ -4438,15 +4438,15 @@
         "PatchGroup": str,
     },
 )
 _OptionalDescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef = TypedDict(
     "_OptionalDescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef",
     {
         "Filters": Sequence[InstancePatchStateFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef(
     _RequiredDescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef,
     _OptionalDescribeInstancePatchStatesForPatchGroupRequestDescribeInstancePatchStatesForPatchGroupPaginateTypeDef,
@@ -4476,48 +4476,48 @@
     pass
 
 DescribeInstancePatchStatesForPatchGroupResultTypeDef = TypedDict(
     "DescribeInstancePatchStatesForPatchGroupResultTypeDef",
     {
         "InstancePatchStates": List[InstancePatchStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancePatchStatesResultTypeDef = TypedDict(
     "DescribeInstancePatchStatesResultTypeDef",
     {
         "InstancePatchStates": List[InstancePatchStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancePatchesResultTypeDef = TypedDict(
     "DescribeInstancePatchesResultTypeDef",
     {
         "Patches": List[PatchComplianceDataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef = TypedDict(
     "_RequiredDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef",
     {
         "WindowExecutionId": str,
         "TaskId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef,
     _OptionalDescribeMaintenanceWindowExecutionTaskInvocationsRequestDescribeMaintenanceWindowExecutionTaskInvocationsPaginateTypeDef,
@@ -4553,15 +4553,15 @@
         "WindowExecutionId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef,
     _OptionalDescribeMaintenanceWindowExecutionTasksRequestDescribeMaintenanceWindowExecutionTasksPaginateTypeDef,
@@ -4596,15 +4596,15 @@
         "WindowId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef,
     _OptionalDescribeMaintenanceWindowExecutionsRequestDescribeMaintenanceWindowExecutionsPaginateTypeDef,
@@ -4639,15 +4639,15 @@
         "WindowId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef,
     _OptionalDescribeMaintenanceWindowTargetsRequestDescribeMaintenanceWindowTargetsPaginateTypeDef,
@@ -4682,15 +4682,15 @@
         "WindowId": str,
     },
 )
 _OptionalDescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef = TypedDict(
     "_OptionalDescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef(
     _RequiredDescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef,
     _OptionalDescribeMaintenanceWindowTasksRequestDescribeMaintenanceWindowTasksPaginateTypeDef,
@@ -4719,15 +4719,15 @@
 ):
     pass
 
 DescribeMaintenanceWindowsRequestDescribeMaintenanceWindowsPaginateTypeDef = TypedDict(
     "DescribeMaintenanceWindowsRequestDescribeMaintenanceWindowsPaginateTypeDef",
     {
         "Filters": Sequence[MaintenanceWindowFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeMaintenanceWindowsRequestRequestTypeDef = TypedDict(
     "DescribeMaintenanceWindowsRequestRequestTypeDef",
     {
@@ -4741,59 +4741,59 @@
 DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowExecutionTaskInvocationsResultTypeDef",
     {
         "WindowExecutionTaskInvocationIdentities": List[
             MaintenanceWindowExecutionTaskInvocationIdentityTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowExecutionsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowExecutionsResultTypeDef",
     {
         "WindowExecutions": List[MaintenanceWindowExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowScheduleResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowScheduleResultTypeDef",
     {
         "ScheduledWindowExecutions": List[ScheduledWindowExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowsForTargetResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowsForTargetResultTypeDef",
     {
         "WindowIdentities": List[MaintenanceWindowIdentityForTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowsResultTypeDef",
     {
         "WindowIdentities": List[MaintenanceWindowIdentityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOpsItemsRequestDescribeOpsItemsPaginateTypeDef = TypedDict(
     "DescribeOpsItemsRequestDescribeOpsItemsPaginateTypeDef",
     {
         "OpsItemFilters": Sequence[OpsItemFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeOpsItemsRequestRequestTypeDef = TypedDict(
     "DescribeOpsItemsRequestRequestTypeDef",
     {
@@ -4812,15 +4812,15 @@
 )
 _OptionalGetParametersByPathRequestGetParametersByPathPaginateTypeDef = TypedDict(
     "_OptionalGetParametersByPathRequestGetParametersByPathPaginateTypeDef",
     {
         "Recursive": bool,
         "ParameterFilters": Sequence[ParameterStringFilterTypeDef],
         "WithDecryption": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetParametersByPathRequestGetParametersByPathPaginateTypeDef(
     _RequiredGetParametersByPathRequestGetParametersByPathPaginateTypeDef,
     _OptionalGetParametersByPathRequestGetParametersByPathPaginateTypeDef,
@@ -4852,15 +4852,15 @@
     pass
 
 DescribeParametersRequestDescribeParametersPaginateTypeDef = TypedDict(
     "DescribeParametersRequestDescribeParametersPaginateTypeDef",
     {
         "Filters": Sequence[ParametersFilterTypeDef],
         "ParameterFilters": Sequence[ParameterStringFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeParametersRequestRequestTypeDef = TypedDict(
     "DescribeParametersRequestRequestTypeDef",
     {
@@ -4873,15 +4873,15 @@
 )
 
 DescribePatchBaselinesResultTypeDef = TypedDict(
     "DescribePatchBaselinesResultTypeDef",
     {
         "BaselineIdentities": List[PatchBaselineIdentityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PatchGroupPatchBaselineMappingTypeDef = TypedDict(
     "PatchGroupPatchBaselineMappingTypeDef",
     {
         "PatchGroup": str,
@@ -4896,15 +4896,15 @@
         "State": SessionStateType,
     },
 )
 _OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef = TypedDict(
     "_OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef",
     {
         "Filters": Sequence[SessionFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeSessionsRequestDescribeSessionsPaginateTypeDef(
     _RequiredDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
     _OptionalDescribeSessionsRequestDescribeSessionsPaginateTypeDef,
@@ -4932,15 +4932,15 @@
 ):
     pass
 
 UpdateDocumentDefaultVersionResultTypeDef = TypedDict(
     "UpdateDocumentDefaultVersionResultTypeDef",
     {
         "Description": DocumentDefaultVersionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentDescriptionTypeDef = TypedDict(
     "DocumentDescriptionTypeDef",
     {
         "Sha1": str,
@@ -4978,15 +4978,15 @@
 )
 
 ListDocumentsRequestListDocumentsPaginateTypeDef = TypedDict(
     "ListDocumentsRequestListDocumentsPaginateTypeDef",
     {
         "DocumentFilterList": Sequence[DocumentFilterTypeDef],
         "Filters": Sequence[DocumentKeyValuesFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDocumentsRequestRequestTypeDef = TypedDict(
     "ListDocumentsRequestRequestTypeDef",
     {
@@ -5028,15 +5028,15 @@
     pass
 
 ListDocumentVersionsResultTypeDef = TypedDict(
     "ListDocumentVersionsResultTypeDef",
     {
         "DocumentVersions": List[DocumentVersionInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EffectivePatchTypeDef = TypedDict(
     "EffectivePatchTypeDef",
     {
         "Patch": PatchTypeDef,
@@ -5100,15 +5100,15 @@
 
 GetInventoryRequestGetInventoryPaginateTypeDef = TypedDict(
     "GetInventoryRequestGetInventoryPaginateTypeDef",
     {
         "Filters": Sequence[InventoryFilterTypeDef],
         "Aggregators": Sequence["InventoryAggregatorTypeDef"],
         "ResultAttributes": Sequence[ResultAttributeTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetInventoryRequestRequestTypeDef = TypedDict(
     "GetInventoryRequestRequestTypeDef",
     {
@@ -5137,15 +5137,15 @@
 GetOpsSummaryRequestGetOpsSummaryPaginateTypeDef = TypedDict(
     "GetOpsSummaryRequestGetOpsSummaryPaginateTypeDef",
     {
         "SyncName": str,
         "Filters": Sequence[OpsFilterTypeDef],
         "Aggregators": Sequence["OpsAggregatorTypeDef"],
         "ResultAttributes": Sequence[OpsResultAttributeTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetOpsSummaryRequestRequestTypeDef = TypedDict(
     "GetOpsSummaryRequestRequestTypeDef",
     {
@@ -5159,58 +5159,58 @@
     total=False,
 )
 
 GetParameterResultTypeDef = TypedDict(
     "GetParameterResultTypeDef",
     {
         "Parameter": ParameterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParametersByPathResultTypeDef = TypedDict(
     "GetParametersByPathResultTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParametersResultTypeDef = TypedDict(
     "GetParametersResultTypeDef",
     {
         "Parameters": List[ParameterTypeDef],
         "InvalidParameters": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcePoliciesResponseTypeDef = TypedDict(
     "GetResourcePoliciesResponseTypeDef",
     {
         "NextToken": str,
         "Policies": List[GetResourcePoliciesResponseEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceSettingResultTypeDef = TypedDict(
     "GetServiceSettingResultTypeDef",
     {
         "ServiceSetting": ServiceSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetServiceSettingResultTypeDef = TypedDict(
     "ResetServiceSettingResultTypeDef",
     {
         "ServiceSetting": ServiceSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceInformationTypeDef = TypedDict(
     "InstanceInformationTypeDef",
     {
         "InstanceId": str,
@@ -5302,15 +5302,15 @@
     total=False,
 )
 
 ListOpsItemEventsRequestListOpsItemEventsPaginateTypeDef = TypedDict(
     "ListOpsItemEventsRequestListOpsItemEventsPaginateTypeDef",
     {
         "Filters": Sequence[OpsItemEventFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOpsItemEventsRequestRequestTypeDef = TypedDict(
     "ListOpsItemEventsRequestRequestTypeDef",
     {
@@ -5322,15 +5322,15 @@
 )
 
 ListOpsItemRelatedItemsRequestListOpsItemRelatedItemsPaginateTypeDef = TypedDict(
     "ListOpsItemRelatedItemsRequestListOpsItemRelatedItemsPaginateTypeDef",
     {
         "OpsItemId": str,
         "Filters": Sequence[OpsItemRelatedItemsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOpsItemRelatedItemsRequestRequestTypeDef = TypedDict(
     "ListOpsItemRelatedItemsRequestRequestTypeDef",
     {
@@ -5342,15 +5342,15 @@
     total=False,
 )
 
 ListOpsMetadataRequestListOpsMetadataPaginateTypeDef = TypedDict(
     "ListOpsMetadataRequestListOpsMetadataPaginateTypeDef",
     {
         "Filters": Sequence[OpsMetadataFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListOpsMetadataRequestRequestTypeDef = TypedDict(
     "ListOpsMetadataRequestRequestTypeDef",
     {
@@ -5362,15 +5362,15 @@
 )
 
 ListOpsMetadataResultTypeDef = TypedDict(
     "ListOpsMetadataResultTypeDef",
     {
         "OpsMetadataList": List[OpsMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpsEntityTypeDef = TypedDict(
     "OpsEntityTypeDef",
     {
         "Id": str,
@@ -5516,15 +5516,15 @@
 )
 
 DescribeActivationsResultTypeDef = TypedDict(
     "DescribeActivationsResultTypeDef",
     {
         "ActivationList": List[ActivationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociationExecutionTypeDef = TypedDict(
     "AssociationExecutionTypeDef",
     {
         "AssociationId": str,
@@ -5588,15 +5588,15 @@
         "MaxErrors": str,
         "Status": MaintenanceWindowExecutionStatusType,
         "StatusDetails": str,
         "StartTime": datetime,
         "EndTime": datetime,
         "AlarmConfiguration": AlarmConfigurationTypeDef,
         "TriggeredAlarms": List[AlarmStateInformationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MaintenanceWindowExecutionTaskIdentityTypeDef = TypedDict(
     "MaintenanceWindowExecutionTaskIdentityTypeDef",
     {
         "WindowExecutionId": str,
@@ -5684,42 +5684,42 @@
 )
 
 ListAssociationsResultTypeDef = TypedDict(
     "ListAssociationsResultTypeDef",
     {
         "Associations": List[AssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowTargetsResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowTargetsResultTypeDef",
     {
         "Targets": List[MaintenanceWindowTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssociationExecutionTargetsResultTypeDef = TypedDict(
     "DescribeAssociationExecutionTargetsResultTypeDef",
     {
         "AssociationExecutionTargets": List[AssociationExecutionTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCommandInvocationsResultTypeDef = TypedDict(
     "ListCommandInvocationsResultTypeDef",
     {
         "CommandInvocations": List[CommandInvocationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MaintenanceWindowTaskInvocationParametersTypeDef = TypedDict(
     "MaintenanceWindowTaskInvocationParametersTypeDef",
     {
         "RunCommand": MaintenanceWindowRunCommandParametersTypeDef,
@@ -5731,15 +5731,15 @@
 )
 
 ListComplianceItemsResultTypeDef = TypedDict(
     "ListComplianceItemsResultTypeDef",
     {
         "ComplianceItems": List[ComplianceItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComplianceSummaryItemTypeDef = TypedDict(
     "ComplianceSummaryItemTypeDef",
     {
         "ComplianceType": str,
@@ -5765,65 +5765,65 @@
 )
 
 ListDocumentsResultTypeDef = TypedDict(
     "ListDocumentsResultTypeDef",
     {
         "DocumentIdentifiers": List[DocumentIdentifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOpsItemsResponseTypeDef = TypedDict(
     "DescribeOpsItemsResponseTypeDef",
     {
         "NextToken": str,
         "OpsItemSummaries": List[OpsItemSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOpsItemResponseTypeDef = TypedDict(
     "GetOpsItemResponseTypeDef",
     {
         "OpsItem": OpsItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePatchGroupsResultTypeDef = TypedDict(
     "DescribePatchGroupsResultTypeDef",
     {
         "Mappings": List[PatchGroupPatchBaselineMappingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDocumentResultTypeDef = TypedDict(
     "CreateDocumentResultTypeDef",
     {
         "DocumentDescription": DocumentDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDocumentResultTypeDef = TypedDict(
     "DescribeDocumentResultTypeDef",
     {
         "Document": DocumentDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDocumentResultTypeDef = TypedDict(
     "UpdateDocumentResultTypeDef",
     {
         "DocumentDescription": DocumentDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentMetadataResponseInfoTypeDef = TypedDict(
     "DocumentMetadataResponseInfoTypeDef",
     {
         "ReviewerResponse": List[DocumentReviewerResponseSourceTypeDef],
@@ -5853,15 +5853,15 @@
     pass
 
 DescribeEffectivePatchesForPatchBaselineResultTypeDef = TypedDict(
     "DescribeEffectivePatchesForPatchBaselineResultTypeDef",
     {
         "EffectivePatches": List[EffectivePatchTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InventoryAggregatorTypeDef = TypedDict(
     "InventoryAggregatorTypeDef",
     {
         "Expression": str,
@@ -5872,15 +5872,15 @@
 )
 
 DescribeInstanceInformationResultTypeDef = TypedDict(
     "DescribeInstanceInformationResultTypeDef",
     {
         "InstanceInformationList": List[InstanceInformationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceAssociationStatusInfoTypeDef = TypedDict(
     "InstanceAssociationStatusInfoTypeDef",
     {
         "AssociationId": str,
@@ -5901,15 +5901,15 @@
 
 DeleteInventoryResultTypeDef = TypedDict(
     "DeleteInventoryResultTypeDef",
     {
         "DeletionId": str,
         "TypeName": str,
         "DeletionSummary": InventoryDeletionSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InventoryDeletionStatusItemTypeDef = TypedDict(
     "InventoryDeletionStatusItemTypeDef",
     {
         "DeletionId": str,
@@ -5924,69 +5924,69 @@
 )
 
 GetInventorySchemaResultTypeDef = TypedDict(
     "GetInventorySchemaResultTypeDef",
     {
         "Schemas": List[InventoryItemSchemaTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInventoryResultTypeDef = TypedDict(
     "GetInventoryResultTypeDef",
     {
         "Entities": List[InventoryResultEntityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOpsSummaryResultTypeDef = TypedDict(
     "GetOpsSummaryResultTypeDef",
     {
         "Entities": List[OpsEntityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpsItemEventsResponseTypeDef = TypedDict(
     "ListOpsItemEventsResponseTypeDef",
     {
         "NextToken": str,
         "Summaries": List[OpsItemEventSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOpsItemRelatedItemsResponseTypeDef = TypedDict(
     "ListOpsItemRelatedItemsResponseTypeDef",
     {
         "NextToken": str,
         "Summaries": List[OpsItemRelatedItemSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParameterHistoryResultTypeDef = TypedDict(
     "GetParameterHistoryResultTypeDef",
     {
         "Parameters": List[ParameterHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeParametersResultTypeDef = TypedDict(
     "DescribeParametersResultTypeDef",
     {
         "Parameters": List[ParameterMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPatchRuleTypeDef = TypedDict(
     "_RequiredPatchRuleTypeDef",
     {
         "PatchFilterGroup": PatchFilterGroupTypeDef,
@@ -6042,59 +6042,59 @@
 )
 
 DescribeSessionsResponseTypeDef = TypedDict(
     "DescribeSessionsResponseTypeDef",
     {
         "Sessions": List[SessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssociationExecutionsResultTypeDef = TypedDict(
     "DescribeAssociationExecutionsResultTypeDef",
     {
         "AssociationExecutions": List[AssociationExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCommandsResultTypeDef = TypedDict(
     "ListCommandsResultTypeDef",
     {
         "Commands": List[CommandTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendCommandResultTypeDef = TypedDict(
     "SendCommandResultTypeDef",
     {
         "Command": CommandTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowExecutionTasksResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowExecutionTasksResultTypeDef",
     {
         "WindowExecutionTaskIdentities": List[MaintenanceWindowExecutionTaskIdentityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMaintenanceWindowTasksResultTypeDef = TypedDict(
     "DescribeMaintenanceWindowTasksResultTypeDef",
     {
         "Tasks": List[MaintenanceWindowTaskTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociationDescriptionTypeDef = TypedDict(
     "AssociationDescriptionTypeDef",
     {
         "Name": str,
@@ -6366,15 +6366,15 @@
         "MaxConcurrency": str,
         "MaxErrors": str,
         "LoggingInfo": LoggingInfoTypeDef,
         "Name": str,
         "Description": str,
         "CutoffBehavior": MaintenanceWindowTaskCutoffBehaviorType,
         "AlarmConfiguration": AlarmConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterTaskWithMaintenanceWindowRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterTaskWithMaintenanceWindowRequestRequestTypeDef",
     {
         "WindowId": str,
@@ -6456,63 +6456,63 @@
         "MaxConcurrency": str,
         "MaxErrors": str,
         "LoggingInfo": LoggingInfoTypeDef,
         "Name": str,
         "Description": str,
         "CutoffBehavior": MaintenanceWindowTaskCutoffBehaviorType,
         "AlarmConfiguration": AlarmConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComplianceSummariesResultTypeDef = TypedDict(
     "ListComplianceSummariesResultTypeDef",
     {
         "ComplianceSummaryItems": List[ComplianceSummaryItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceComplianceSummariesResultTypeDef = TypedDict(
     "ListResourceComplianceSummariesResultTypeDef",
     {
         "ResourceComplianceSummaryItems": List[ResourceComplianceSummaryItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDocumentMetadataHistoryResponseTypeDef = TypedDict(
     "ListDocumentMetadataHistoryResponseTypeDef",
     {
         "Name": str,
         "DocumentVersion": str,
         "Author": str,
         "Metadata": DocumentMetadataResponseInfoTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstanceAssociationsStatusResultTypeDef = TypedDict(
     "DescribeInstanceAssociationsStatusResultTypeDef",
     {
         "InstanceAssociationStatusInfos": List[InstanceAssociationStatusInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInventoryDeletionsResultTypeDef = TypedDict(
     "DescribeInventoryDeletionsResultTypeDef",
     {
         "InventoryDeletions": List[InventoryDeletionStatusItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PatchRuleGroupTypeDef = TypedDict(
     "PatchRuleGroupTypeDef",
     {
         "PatchRules": Sequence[PatchRuleTypeDef],
@@ -6567,48 +6567,48 @@
     total=False,
 )
 
 CreateAssociationResultTypeDef = TypedDict(
     "CreateAssociationResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAssociationResultTypeDef = TypedDict(
     "DescribeAssociationResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssociationResultTypeDef = TypedDict(
     "UpdateAssociationResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssociationStatusResultTypeDef = TypedDict(
     "UpdateAssociationStatusResultTypeDef",
     {
         "AssociationDescription": AssociationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssociationVersionsResultTypeDef = TypedDict(
     "ListAssociationVersionsResultTypeDef",
     {
         "AssociationVersions": List[AssociationVersionInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssociationBatchRequestRequestTypeDef = TypedDict(
     "CreateAssociationBatchRequestRequestTypeDef",
     {
         "Entries": Sequence[CreateAssociationBatchRequestEntryTypeDef],
@@ -6732,15 +6732,15 @@
 )
 
 DescribeAutomationStepExecutionsResultTypeDef = TypedDict(
     "DescribeAutomationStepExecutionsResultTypeDef",
     {
         "StepExecutions": List[StepExecutionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BaselineOverrideTypeDef = TypedDict(
     "BaselineOverrideTypeDef",
     {
         "OperatingSystem": OperatingSystemType,
@@ -6801,15 +6801,15 @@
         "RejectedPatches": List[str],
         "RejectedPatchesAction": PatchActionType,
         "PatchGroups": List[str],
         "CreatedDate": datetime,
         "ModifiedDate": datetime,
         "Description": str,
         "Sources": List[PatchSourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePatchBaselineRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePatchBaselineRequestRequestTypeDef",
     {
         "BaselineId": str,
@@ -6852,50 +6852,50 @@
         "ApprovedPatchesEnableNonSecurity": bool,
         "RejectedPatches": List[str],
         "RejectedPatchesAction": PatchActionType,
         "CreatedDate": datetime,
         "ModifiedDate": datetime,
         "Description": str,
         "Sources": List[PatchSourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceDataSyncResultTypeDef = TypedDict(
     "ListResourceDataSyncResultTypeDef",
     {
         "ResourceDataSyncItems": List[ResourceDataSyncItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssociationBatchResultTypeDef = TypedDict(
     "CreateAssociationBatchResultTypeDef",
     {
         "Successful": List[AssociationDescriptionTypeDef],
         "Failed": List[FailedCreateAssociationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAutomationExecutionsResultTypeDef = TypedDict(
     "DescribeAutomationExecutionsResultTypeDef",
     {
         "AutomationExecutionMetadataList": List[AutomationExecutionMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAutomationExecutionResultTypeDef = TypedDict(
     "GetAutomationExecutionResultTypeDef",
     {
         "AutomationExecution": AutomationExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetDeployablePatchSnapshotForInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredGetDeployablePatchSnapshotForInstanceRequestRequestTypeDef",
     {
         "InstanceId": str,
```

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/waiter.py` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm/waiter.pyi` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/PKG-INFO` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm"></a>
 
 # types-aiobotocore-ssm
 
 [![PyPI - types-aiobotocore-ssm](https://img.shields.io/pypi/v/types-aiobotocore-ssm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
+[aiobotocore.SSM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm.html#SSM)
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
 [types-aiobotocore-ssm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -653,15 +653,15 @@
 ```python
 from types_aiobotocore_ssm.type_defs import (
     AccountSharingInfoTypeDef,
     TagTypeDef,
     AlarmTypeDef,
     AlarmStateInformationTypeDef,
     AssociateOpsItemRelatedItemRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateOpsItemRelatedItemResponseTypeDef,
     AssociationOverviewTypeDef,
     AssociationStatusTypeDef,
     TargetTypeDef,
     AssociationExecutionFilterTypeDef,
     OutputSourceTypeDef,
     AssociationExecutionTargetsFilterTypeDef,
     AssociationFilterTypeDef,
@@ -670,267 +670,267 @@
     AttachmentsSourceTypeDef,
     AutomationExecutionFilterTypeDef,
     ResolvedTargetsTypeDef,
     ProgressCountersTypeDef,
     PatchSourceTypeDef,
     CancelCommandRequestRequestTypeDef,
     CancelMaintenanceWindowExecutionRequestRequestTypeDef,
+    CancelMaintenanceWindowExecutionResultTypeDef,
     CloudWatchOutputConfigTypeDef,
     CommandFilterTypeDef,
     CommandPluginTypeDef,
     NotificationConfigTypeDef,
     ComplianceExecutionSummaryTypeDef,
     ComplianceItemEntryTypeDef,
     ComplianceStringFilterTypeDef,
     SeveritySummaryTypeDef,
     RegistrationMetadataItemTypeDef,
+    CreateActivationResultTypeDef,
     DocumentRequiresTypeDef,
+    CreateMaintenanceWindowResultTypeDef,
     OpsItemDataValueTypeDef,
     OpsItemNotificationTypeDef,
     RelatedOpsItemTypeDef,
+    CreateOpsItemResponseTypeDef,
     MetadataValueTypeDef,
+    CreateOpsMetadataResultTypeDef,
+    CreatePatchBaselineResultTypeDef,
     DeleteActivationRequestRequestTypeDef,
     DeleteAssociationRequestRequestTypeDef,
     DeleteDocumentRequestRequestTypeDef,
     DeleteInventoryRequestRequestTypeDef,
     DeleteMaintenanceWindowRequestRequestTypeDef,
+    DeleteMaintenanceWindowResultTypeDef,
     DeleteOpsMetadataRequestRequestTypeDef,
     DeleteParameterRequestRequestTypeDef,
     DeleteParametersRequestRequestTypeDef,
+    DeleteParametersResultTypeDef,
     DeletePatchBaselineRequestRequestTypeDef,
+    DeletePatchBaselineResultTypeDef,
     DeleteResourceDataSyncRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     DeregisterManagedInstanceRequestRequestTypeDef,
     DeregisterPatchBaselineForPatchGroupRequestRequestTypeDef,
+    DeregisterPatchBaselineForPatchGroupResultTypeDef,
     DeregisterTargetFromMaintenanceWindowRequestRequestTypeDef,
+    DeregisterTargetFromMaintenanceWindowResultTypeDef,
     DeregisterTaskFromMaintenanceWindowRequestRequestTypeDef,
+    DeregisterTaskFromMaintenanceWindowResultTypeDef,
     DescribeActivationsFilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeAssociationRequestRequestTypeDef,
     StepExecutionFilterTypeDef,
     PatchOrchestratorFilterTypeDef,
     PatchTypeDef,
     DescribeDocumentPermissionRequestRequestTypeDef,
     DescribeDocumentRequestRequestTypeDef,
+    DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
     DescribeEffectiveInstanceAssociationsRequestRequestTypeDef,
     InstanceAssociationTypeDef,
+    DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
     DescribeEffectivePatchesForPatchBaselineRequestRequestTypeDef,
+    DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
     DescribeInstanceAssociationsStatusRequestRequestTypeDef,
     InstanceInformationFilterTypeDef,
     InstanceInformationStringFilterTypeDef,
     InstancePatchStateFilterTypeDef,
     InstancePatchStateTypeDef,
+    DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
     DescribeInstancePatchStatesRequestRequestTypeDef,
     PatchComplianceDataTypeDef,
+    DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef,
     DescribeInventoryDeletionsRequestRequestTypeDef,
     MaintenanceWindowFilterTypeDef,
     MaintenanceWindowExecutionTaskInvocationIdentityTypeDef,
     MaintenanceWindowExecutionTypeDef,
     ScheduledWindowExecutionTypeDef,
     MaintenanceWindowIdentityForTargetTypeDef,
     MaintenanceWindowIdentityTypeDef,
     OpsItemFilterTypeDef,
     ParameterStringFilterTypeDef,
     ParametersFilterTypeDef,
     PatchBaselineIdentityTypeDef,
     DescribePatchGroupStateRequestRequestTypeDef,
+    DescribePatchGroupStateResultTypeDef,
+    DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
     DescribePatchPropertiesRequestRequestTypeDef,
+    DescribePatchPropertiesResultTypeDef,
     SessionFilterTypeDef,
     DisassociateOpsItemRelatedItemRequestRequestTypeDef,
     DocumentDefaultVersionDescriptionTypeDef,
     DocumentParameterTypeDef,
     ReviewInformationTypeDef,
     DocumentFilterTypeDef,
     DocumentKeyValuesFilterTypeDef,
     DocumentReviewCommentSourceTypeDef,
     DocumentVersionInfoTypeDef,
     PatchStatusTypeDef,
     FailureDetailsTypeDef,
     GetAutomationExecutionRequestRequestTypeDef,
     GetCalendarStateRequestRequestTypeDef,
+    GetCalendarStateResponseTypeDef,
     WaiterConfigTypeDef,
     GetCommandInvocationRequestRequestTypeDef,
     GetConnectionStatusRequestRequestTypeDef,
+    GetConnectionStatusResponseTypeDef,
     GetDefaultPatchBaselineRequestRequestTypeDef,
+    GetDefaultPatchBaselineResultTypeDef,
+    GetDeployablePatchSnapshotForInstanceResultTypeDef,
     GetDocumentRequestRequestTypeDef,
     InventoryFilterTypeDef,
     ResultAttributeTypeDef,
+    GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef,
     GetInventorySchemaRequestRequestTypeDef,
     GetMaintenanceWindowExecutionRequestRequestTypeDef,
+    GetMaintenanceWindowExecutionResultTypeDef,
     GetMaintenanceWindowExecutionTaskInvocationRequestRequestTypeDef,
+    GetMaintenanceWindowExecutionTaskInvocationResultTypeDef,
     GetMaintenanceWindowExecutionTaskRequestRequestTypeDef,
     MaintenanceWindowTaskParameterValueExpressionTypeDef,
     GetMaintenanceWindowRequestRequestTypeDef,
+    GetMaintenanceWindowResultTypeDef,
     GetMaintenanceWindowTaskRequestRequestTypeDef,
     LoggingInfoTypeDef,
     GetOpsItemRequestRequestTypeDef,
     GetOpsMetadataRequestRequestTypeDef,
     OpsFilterTypeDef,
     OpsResultAttributeTypeDef,
+    GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
     GetParameterHistoryRequestRequestTypeDef,
     GetParameterRequestRequestTypeDef,
     ParameterTypeDef,
     GetParametersRequestRequestTypeDef,
     GetPatchBaselineForPatchGroupRequestRequestTypeDef,
+    GetPatchBaselineForPatchGroupResultTypeDef,
     GetPatchBaselineRequestRequestTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
     GetResourcePoliciesResponseEntryTypeDef,
     GetServiceSettingRequestRequestTypeDef,
     ServiceSettingTypeDef,
     InstanceAggregatedAssociationOverviewTypeDef,
     S3OutputLocationTypeDef,
     S3OutputUrlTypeDef,
     InventoryDeletionSummaryItemTypeDef,
     InventoryItemAttributeTypeDef,
     InventoryItemTypeDef,
     InventoryResultItemTypeDef,
     LabelParameterVersionRequestRequestTypeDef,
+    LabelParameterVersionResultTypeDef,
+    ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
     ListAssociationVersionsRequestRequestTypeDef,
     ListDocumentMetadataHistoryRequestRequestTypeDef,
+    ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
     ListDocumentVersionsRequestRequestTypeDef,
+    ListInventoryEntriesResultTypeDef,
     OpsItemEventFilterTypeDef,
     OpsItemRelatedItemsFilterTypeDef,
     OpsMetadataFilterTypeDef,
     OpsMetadataTypeDef,
+    ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef,
     ListResourceDataSyncRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MaintenanceWindowAutomationParametersTypeDef,
     MaintenanceWindowLambdaParametersTypeDef,
     MaintenanceWindowStepFunctionsParametersTypeDef,
     ModifyDocumentPermissionRequestRequestTypeDef,
     OpsEntityItemTypeDef,
     OpsItemIdentityTypeDef,
+    PaginatorConfigTypeDef,
     ParameterInlinePolicyTypeDef,
     PatchFilterTypeDef,
+    PutInventoryResultTypeDef,
+    PutParameterResultTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
     RegisterDefaultPatchBaselineRequestRequestTypeDef,
+    RegisterDefaultPatchBaselineResultTypeDef,
     RegisterPatchBaselineForPatchGroupRequestRequestTypeDef,
+    RegisterPatchBaselineForPatchGroupResultTypeDef,
+    RegisterTargetWithMaintenanceWindowResultTypeDef,
+    RegisterTaskWithMaintenanceWindowResultTypeDef,
     RemoveTagsFromResourceRequestRequestTypeDef,
     ResetServiceSettingRequestRequestTypeDef,
     ResourceDataSyncOrganizationalUnitTypeDef,
     ResourceDataSyncDestinationDataSharingTypeDef,
+    ResponseMetadataTypeDef,
     ResumeSessionRequestRequestTypeDef,
+    ResumeSessionResponseTypeDef,
     SendAutomationSignalRequestRequestTypeDef,
     SessionManagerOutputUrlTypeDef,
     StartAssociationsOnceRequestRequestTypeDef,
+    StartAutomationExecutionResultTypeDef,
+    StartChangeRequestExecutionResultTypeDef,
     StartSessionRequestRequestTypeDef,
+    StartSessionResponseTypeDef,
     StopAutomationExecutionRequestRequestTypeDef,
     TerminateSessionRequestRequestTypeDef,
+    TerminateSessionResponseTypeDef,
     UnlabelParameterVersionRequestRequestTypeDef,
+    UnlabelParameterVersionResultTypeDef,
     UpdateDocumentDefaultVersionRequestRequestTypeDef,
     UpdateMaintenanceWindowRequestRequestTypeDef,
+    UpdateMaintenanceWindowResultTypeDef,
     UpdateManagedInstanceRoleRequestRequestTypeDef,
+    UpdateOpsMetadataResultTypeDef,
     UpdateServiceSettingRequestRequestTypeDef,
+    DescribeDocumentPermissionResponseTypeDef,
     ActivationTypeDef,
     AddTagsToResourceRequestRequestTypeDef,
     CreateMaintenanceWindowRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     PutParameterRequestRequestTypeDef,
     AlarmConfigurationTypeDef,
-    AssociateOpsItemRelatedItemResponseTypeDef,
-    CancelMaintenanceWindowExecutionResultTypeDef,
-    CreateActivationResultTypeDef,
-    CreateMaintenanceWindowResultTypeDef,
-    CreateOpsItemResponseTypeDef,
-    CreateOpsMetadataResultTypeDef,
-    CreatePatchBaselineResultTypeDef,
-    DeleteMaintenanceWindowResultTypeDef,
-    DeleteParametersResultTypeDef,
-    DeletePatchBaselineResultTypeDef,
-    DeregisterPatchBaselineForPatchGroupResultTypeDef,
-    DeregisterTargetFromMaintenanceWindowResultTypeDef,
-    DeregisterTaskFromMaintenanceWindowResultTypeDef,
-    DescribeDocumentPermissionResponseTypeDef,
-    DescribePatchGroupStateResultTypeDef,
-    DescribePatchPropertiesResultTypeDef,
-    GetCalendarStateResponseTypeDef,
-    GetConnectionStatusResponseTypeDef,
-    GetDefaultPatchBaselineResultTypeDef,
-    GetDeployablePatchSnapshotForInstanceResultTypeDef,
-    GetMaintenanceWindowExecutionResultTypeDef,
-    GetMaintenanceWindowExecutionTaskInvocationResultTypeDef,
-    GetMaintenanceWindowResultTypeDef,
-    GetPatchBaselineForPatchGroupResultTypeDef,
-    LabelParameterVersionResultTypeDef,
-    ListInventoryEntriesResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    PutInventoryResultTypeDef,
-    PutParameterResultTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    RegisterDefaultPatchBaselineResultTypeDef,
-    RegisterPatchBaselineForPatchGroupResultTypeDef,
-    RegisterTargetWithMaintenanceWindowResultTypeDef,
-    RegisterTaskWithMaintenanceWindowResultTypeDef,
-    ResumeSessionResponseTypeDef,
-    StartAutomationExecutionResultTypeDef,
-    StartChangeRequestExecutionResultTypeDef,
-    StartSessionResponseTypeDef,
-    TerminateSessionResponseTypeDef,
-    UnlabelParameterVersionResultTypeDef,
-    UpdateMaintenanceWindowResultTypeDef,
-    UpdateOpsMetadataResultTypeDef,
     UpdateAssociationStatusRequestRequestTypeDef,
     AssociationTypeDef,
+    DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
     DescribeMaintenanceWindowsForTargetRequestRequestTypeDef,
     MaintenanceWindowTargetTypeDef,
     RegisterTargetWithMaintenanceWindowRequestRequestTypeDef,
     UpdateMaintenanceWindowTargetRequestRequestTypeDef,
     UpdateMaintenanceWindowTargetResultTypeDef,
+    DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
     DescribeAssociationExecutionsRequestRequestTypeDef,
     AssociationExecutionTargetTypeDef,
+    DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
     DescribeAssociationExecutionTargetsRequestRequestTypeDef,
+    ListAssociationsRequestListAssociationsPaginateTypeDef,
     ListAssociationsRequestRequestTypeDef,
     UpdateDocumentRequestRequestTypeDef,
+    DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef,
     DescribeAutomationExecutionsRequestRequestTypeDef,
     GetCommandInvocationResultTypeDef,
+    ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef,
     ListCommandInvocationsRequestRequestTypeDef,
+    ListCommandsRequestListCommandsPaginateTypeDef,
     ListCommandsRequestRequestTypeDef,
     CommandInvocationTypeDef,
     MaintenanceWindowRunCommandParametersTypeDef,
     ComplianceItemTypeDef,
     PutComplianceItemsRequestRequestTypeDef,
+    ListComplianceItemsRequestListComplianceItemsPaginateTypeDef,
     ListComplianceItemsRequestRequestTypeDef,
+    ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef,
     ListComplianceSummariesRequestRequestTypeDef,
+    ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef,
     ListResourceComplianceSummariesRequestRequestTypeDef,
     CompliantSummaryTypeDef,
     NonCompliantSummaryTypeDef,
     CreateActivationRequestRequestTypeDef,
     CreateDocumentRequestRequestTypeDef,
     DocumentIdentifierTypeDef,
     GetDocumentResultTypeDef,
     OpsItemSummaryTypeDef,
     CreateOpsItemRequestRequestTypeDef,
     OpsItemTypeDef,
     UpdateOpsItemRequestRequestTypeDef,
     CreateOpsMetadataRequestRequestTypeDef,
     GetOpsMetadataResultTypeDef,
     UpdateOpsMetadataRequestRequestTypeDef,
-    DescribeActivationsRequestRequestTypeDef,
     DescribeActivationsRequestDescribeActivationsPaginateTypeDef,
-    DescribeAssociationExecutionTargetsRequestDescribeAssociationExecutionTargetsPaginateTypeDef,
-    DescribeAssociationExecutionsRequestDescribeAssociationExecutionsPaginateTypeDef,
-    DescribeAutomationExecutionsRequestDescribeAutomationExecutionsPaginateTypeDef,
-    DescribeEffectiveInstanceAssociationsRequestDescribeEffectiveInstanceAssociationsPaginateTypeDef,
-    DescribeEffectivePatchesForPatchBaselineRequestDescribeEffectivePatchesForPatchBaselinePaginateTypeDef,
-    DescribeInstanceAssociationsStatusRequestDescribeInstanceAssociationsStatusPaginateTypeDef,
-    DescribeInstancePatchStatesRequestDescribeInstancePatchStatesPaginateTypeDef,
-    DescribeInventoryDeletionsRequestDescribeInventoryDeletionsPaginateTypeDef,
-    DescribeMaintenanceWindowsForTargetRequestDescribeMaintenanceWindowsForTargetPaginateTypeDef,
-    DescribePatchPropertiesRequestDescribePatchPropertiesPaginateTypeDef,
-    GetInventorySchemaRequestGetInventorySchemaPaginateTypeDef,
-    GetParameterHistoryRequestGetParameterHistoryPaginateTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    ListAssociationVersionsRequestListAssociationVersionsPaginateTypeDef,
-    ListAssociationsRequestListAssociationsPaginateTypeDef,
-    ListCommandInvocationsRequestListCommandInvocationsPaginateTypeDef,
-    ListCommandsRequestListCommandsPaginateTypeDef,
-    ListComplianceItemsRequestListComplianceItemsPaginateTypeDef,
-    ListComplianceSummariesRequestListComplianceSummariesPaginateTypeDef,
-    ListDocumentVersionsRequestListDocumentVersionsPaginateTypeDef,
-    ListResourceComplianceSummariesRequestListResourceComplianceSummariesPaginateTypeDef,
-    ListResourceDataSyncRequestListResourceDataSyncPaginateTypeDef,
+    DescribeActivationsRequestRequestTypeDef,
     DescribeAutomationStepExecutionsRequestDescribeAutomationStepExecutionsPaginateTypeDef,
     DescribeAutomationStepExecutionsRequestRequestTypeDef,
     DescribeAvailablePatchesRequestDescribeAvailablePatchesPaginateTypeDef,
     DescribeAvailablePatchesRequestRequestTypeDef,
     DescribeInstancePatchesRequestDescribeInstancePatchesPaginateTypeDef,
     DescribeInstancePatchesRequestRequestTypeDef,
     DescribeMaintenanceWindowScheduleRequestDescribeMaintenanceWindowSchedulePaginateTypeDef,
@@ -1119,43 +1119,43 @@
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

### Comparing `types-aiobotocore-ssm-2.5.0.post1/types_aiobotocore_ssm.egg-info/SOURCES.txt` & `types-aiobotocore-ssm-2.5.1/types_aiobotocore_ssm.egg-info/SOURCES.txt`

 * *Files identical despite different names*

