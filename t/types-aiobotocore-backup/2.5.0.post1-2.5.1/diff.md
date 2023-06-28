# Comparing `tmp/types-aiobotocore-backup-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-backup-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-backup-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-backup-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-backup-2.5.0.post1.tar` & `types-aiobotocore-backup-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.186974 types-aiobotocore-backup-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22487 2023-03-11 12:26:15.178974 types-aiobotocore-backup-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20920 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.186974 types-aiobotocore-backup-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.170973 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/
--rw-r--r--   0 runner    (1001) docker     (123)     3463 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3462 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    57845 2023-03-11 12:10:04.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    57751 2023-03-11 12:10:03.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10998 2023-03-11 12:10:04.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10996 2023-03-11 12:10:04.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17387 2023-03-11 12:10:04.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    17371 2023-03-11 12:10:04.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    67601 2023-03-11 12:10:05.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    67526 2023-03-11 12:10:05.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:02.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.178974 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22487 2023-03-11 12:26:14.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:26:15.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:15.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:15.000000 types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.874099 types-aiobotocore-backup-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22478 2023-06-28 01:43:08.874099 types-aiobotocore-backup-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20917 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.874099 types-aiobotocore-backup-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.874099 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/
+-rw-r--r--   0 runner    (1001) docker     (123)     3463 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3462 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    57895 2023-06-28 01:26:40.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    57801 2023-06-28 01:26:40.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11285 2023-06-28 01:26:40.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11283 2023-06-28 01:26:40.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17293 2023-06-28 01:26:40.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17278 2023-06-28 01:26:40.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    67874 2023-06-28 01:26:42.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    67799 2023-06-28 01:26:41.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:39.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.874099 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22478 2023-06-28 01:43:08.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:08.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:08.000000 types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/LICENSE` & `types-aiobotocore-backup-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-backup-2.5.0.post1/PKG-INFO` & `types-aiobotocore-backup-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-backup
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Backup 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Backup 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-backup"></a>
 
 # types-aiobotocore-backup
 
 [![PyPI - types-aiobotocore-backup](https://img.shields.io/pypi/v/types-aiobotocore-backup.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backup.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backup?color=blue)](https://pypistats.org/packages/types-aiobotocore-backup)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Backup 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
+[aiobotocore.Backup 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
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
 [types-aiobotocore-backup docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/).
 
 See how it helps to find and fix potential bugs:
 
@@ -391,143 +391,143 @@
     BackupSelectionsListMemberTypeDef,
     BackupVaultListMemberTypeDef,
     CalculatedLifecycleTypeDef,
     CancelLegalHoldInputRequestTypeDef,
     ConditionParameterTypeDef,
     ControlInputParameterTypeDef,
     ControlScopeTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBackupSelectionOutputTypeDef,
     CreateBackupVaultInputRequestTypeDef,
+    CreateBackupVaultOutputTypeDef,
+    CreateFrameworkOutputTypeDef,
     ReportDeliveryChannelTypeDef,
     ReportSettingTypeDef,
+    CreateReportPlanOutputTypeDef,
     DateRangeTypeDef,
     DeleteBackupPlanInputRequestTypeDef,
+    DeleteBackupPlanOutputTypeDef,
     DeleteBackupSelectionInputRequestTypeDef,
     DeleteBackupVaultAccessPolicyInputRequestTypeDef,
     DeleteBackupVaultInputRequestTypeDef,
     DeleteBackupVaultLockConfigurationInputRequestTypeDef,
     DeleteBackupVaultNotificationsInputRequestTypeDef,
     DeleteFrameworkInputRequestTypeDef,
     DeleteRecoveryPointInputRequestTypeDef,
     DeleteReportPlanInputRequestTypeDef,
     DescribeBackupJobInputRequestTypeDef,
     DescribeBackupVaultInputRequestTypeDef,
+    DescribeBackupVaultOutputTypeDef,
     DescribeCopyJobInputRequestTypeDef,
     DescribeFrameworkInputRequestTypeDef,
+    DescribeGlobalSettingsOutputTypeDef,
     DescribeProtectedResourceInputRequestTypeDef,
+    DescribeProtectedResourceOutputTypeDef,
     DescribeRecoveryPointInputRequestTypeDef,
+    DescribeRegionSettingsOutputTypeDef,
     DescribeReportJobInputRequestTypeDef,
     DescribeReportPlanInputRequestTypeDef,
     DescribeRestoreJobInputRequestTypeDef,
+    DescribeRestoreJobOutputTypeDef,
     DisassociateRecoveryPointFromParentInputRequestTypeDef,
     DisassociateRecoveryPointInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportBackupPlanTemplateInputRequestTypeDef,
+    ExportBackupPlanTemplateOutputTypeDef,
     FrameworkTypeDef,
     GetBackupPlanFromJSONInputRequestTypeDef,
     GetBackupPlanFromTemplateInputRequestTypeDef,
     GetBackupPlanInputRequestTypeDef,
     GetBackupSelectionInputRequestTypeDef,
     GetBackupVaultAccessPolicyInputRequestTypeDef,
+    GetBackupVaultAccessPolicyOutputTypeDef,
     GetBackupVaultNotificationsInputRequestTypeDef,
+    GetBackupVaultNotificationsOutputTypeDef,
     GetLegalHoldInputRequestTypeDef,
     GetRecoveryPointRestoreMetadataInputRequestTypeDef,
+    GetRecoveryPointRestoreMetadataOutputTypeDef,
+    GetSupportedResourceTypesOutputTypeDef,
     LegalHoldTypeDef,
-    PaginatorConfigTypeDef,
+    ListBackupJobsInputListBackupJobsPaginateTypeDef,
     ListBackupJobsInputRequestTypeDef,
+    ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef,
     ListBackupPlanTemplatesInputRequestTypeDef,
+    ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
     ListBackupPlanVersionsInputRequestTypeDef,
+    ListBackupPlansInputListBackupPlansPaginateTypeDef,
     ListBackupPlansInputRequestTypeDef,
+    ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
     ListBackupSelectionsInputRequestTypeDef,
+    ListBackupVaultsInputListBackupVaultsPaginateTypeDef,
     ListBackupVaultsInputRequestTypeDef,
+    ListCopyJobsInputListCopyJobsPaginateTypeDef,
     ListCopyJobsInputRequestTypeDef,
     ListFrameworksInputRequestTypeDef,
+    ListLegalHoldsInputListLegalHoldsPaginateTypeDef,
     ListLegalHoldsInputRequestTypeDef,
+    ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef,
     ListProtectedResourcesInputRequestTypeDef,
     ProtectedResourceTypeDef,
+    ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
     ListRecoveryPointsByBackupVaultInputRequestTypeDef,
+    ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
     ListRecoveryPointsByLegalHoldInputRequestTypeDef,
     RecoveryPointMemberTypeDef,
+    ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
     ListRecoveryPointsByResourceInputRequestTypeDef,
     RecoveryPointByResourceTypeDef,
     ListReportJobsInputRequestTypeDef,
     ListReportPlansInputRequestTypeDef,
+    ListRestoreJobsInputListRestoreJobsPaginateTypeDef,
     ListRestoreJobsInputRequestTypeDef,
     RestoreJobsListMemberTypeDef,
     ListTagsInputRequestTypeDef,
+    ListTagsOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutBackupVaultAccessPolicyInputRequestTypeDef,
     PutBackupVaultLockConfigurationInputRequestTypeDef,
     PutBackupVaultNotificationsInputRequestTypeDef,
     ReportDestinationTypeDef,
+    ResponseMetadataTypeDef,
+    StartBackupJobOutputTypeDef,
+    StartCopyJobOutputTypeDef,
     StartReportJobInputRequestTypeDef,
+    StartReportJobOutputTypeDef,
     StartRestoreJobInputRequestTypeDef,
+    StartRestoreJobOutputTypeDef,
     StopBackupJobInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateFrameworkOutputTypeDef,
     UpdateGlobalSettingsInputRequestTypeDef,
     UpdateRegionSettingsInputRequestTypeDef,
+    UpdateReportPlanOutputTypeDef,
     BackupPlansListMemberTypeDef,
+    CreateBackupPlanOutputTypeDef,
+    UpdateBackupPlanOutputTypeDef,
     BackupJobTypeDef,
     CopyJobTypeDef,
+    DescribeBackupJobOutputTypeDef,
+    ListBackupPlanTemplatesOutputTypeDef,
     CopyActionTypeDef,
     StartBackupJobInputRequestTypeDef,
     StartCopyJobInputRequestTypeDef,
     UpdateRecoveryPointLifecycleInputRequestTypeDef,
-    RecoveryPointByBackupVaultTypeDef,
-    ConditionsTypeDef,
-    FrameworkControlTypeDef,
-    CreateBackupPlanOutputTypeDef,
-    CreateBackupSelectionOutputTypeDef,
-    CreateBackupVaultOutputTypeDef,
-    CreateFrameworkOutputTypeDef,
-    CreateReportPlanOutputTypeDef,
-    DeleteBackupPlanOutputTypeDef,
-    DescribeBackupJobOutputTypeDef,
-    DescribeBackupVaultOutputTypeDef,
-    DescribeGlobalSettingsOutputTypeDef,
-    DescribeProtectedResourceOutputTypeDef,
-    DescribeRecoveryPointOutputTypeDef,
-    DescribeRegionSettingsOutputTypeDef,
-    DescribeRestoreJobOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportBackupPlanTemplateOutputTypeDef,
-    GetBackupVaultAccessPolicyOutputTypeDef,
-    GetBackupVaultNotificationsOutputTypeDef,
-    GetRecoveryPointRestoreMetadataOutputTypeDef,
-    GetSupportedResourceTypesOutputTypeDef,
-    ListBackupPlanTemplatesOutputTypeDef,
     ListBackupSelectionsOutputTypeDef,
     ListBackupVaultsOutputTypeDef,
-    ListTagsOutputTypeDef,
-    StartBackupJobOutputTypeDef,
-    StartCopyJobOutputTypeDef,
-    StartReportJobOutputTypeDef,
-    StartRestoreJobOutputTypeDef,
-    UpdateBackupPlanOutputTypeDef,
-    UpdateFrameworkOutputTypeDef,
+    DescribeRecoveryPointOutputTypeDef,
+    RecoveryPointByBackupVaultTypeDef,
     UpdateRecoveryPointLifecycleOutputTypeDef,
-    UpdateReportPlanOutputTypeDef,
+    ConditionsTypeDef,
+    FrameworkControlTypeDef,
     CreateReportPlanInputRequestTypeDef,
     ReportPlanTypeDef,
     UpdateReportPlanInputRequestTypeDef,
     RecoveryPointSelectionTypeDef,
     ListFrameworksOutputTypeDef,
     ListLegalHoldsOutputTypeDef,
-    ListBackupJobsInputListBackupJobsPaginateTypeDef,
-    ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef,
-    ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
-    ListBackupPlansInputListBackupPlansPaginateTypeDef,
-    ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
-    ListBackupVaultsInputListBackupVaultsPaginateTypeDef,
-    ListCopyJobsInputListCopyJobsPaginateTypeDef,
-    ListLegalHoldsInputListLegalHoldsPaginateTypeDef,
-    ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef,
-    ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
-    ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
-    ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
-    ListRestoreJobsInputListRestoreJobsPaginateTypeDef,
     ListProtectedResourcesOutputTypeDef,
     ListRecoveryPointsByLegalHoldOutputTypeDef,
     ListRecoveryPointsByResourceOutputTypeDef,
     ListRestoreJobsOutputTypeDef,
     ReportJobTypeDef,
     ListBackupPlanVersionsOutputTypeDef,
     ListBackupPlansOutputTypeDef,
@@ -567,43 +567,43 @@
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

### Comparing `types-aiobotocore-backup-2.5.0.post1/README.md` & `types-aiobotocore-backup-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-backup"></a>
 
 # types-aiobotocore-backup
 
 [![PyPI - types-aiobotocore-backup](https://img.shields.io/pypi/v/types-aiobotocore-backup.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backup.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backup?color=blue)](https://pypistats.org/packages/types-aiobotocore-backup)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Backup 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
+[aiobotocore.Backup 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
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
 [types-aiobotocore-backup docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,143 +358,143 @@
     BackupSelectionsListMemberTypeDef,
     BackupVaultListMemberTypeDef,
     CalculatedLifecycleTypeDef,
     CancelLegalHoldInputRequestTypeDef,
     ConditionParameterTypeDef,
     ControlInputParameterTypeDef,
     ControlScopeTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBackupSelectionOutputTypeDef,
     CreateBackupVaultInputRequestTypeDef,
+    CreateBackupVaultOutputTypeDef,
+    CreateFrameworkOutputTypeDef,
     ReportDeliveryChannelTypeDef,
     ReportSettingTypeDef,
+    CreateReportPlanOutputTypeDef,
     DateRangeTypeDef,
     DeleteBackupPlanInputRequestTypeDef,
+    DeleteBackupPlanOutputTypeDef,
     DeleteBackupSelectionInputRequestTypeDef,
     DeleteBackupVaultAccessPolicyInputRequestTypeDef,
     DeleteBackupVaultInputRequestTypeDef,
     DeleteBackupVaultLockConfigurationInputRequestTypeDef,
     DeleteBackupVaultNotificationsInputRequestTypeDef,
     DeleteFrameworkInputRequestTypeDef,
     DeleteRecoveryPointInputRequestTypeDef,
     DeleteReportPlanInputRequestTypeDef,
     DescribeBackupJobInputRequestTypeDef,
     DescribeBackupVaultInputRequestTypeDef,
+    DescribeBackupVaultOutputTypeDef,
     DescribeCopyJobInputRequestTypeDef,
     DescribeFrameworkInputRequestTypeDef,
+    DescribeGlobalSettingsOutputTypeDef,
     DescribeProtectedResourceInputRequestTypeDef,
+    DescribeProtectedResourceOutputTypeDef,
     DescribeRecoveryPointInputRequestTypeDef,
+    DescribeRegionSettingsOutputTypeDef,
     DescribeReportJobInputRequestTypeDef,
     DescribeReportPlanInputRequestTypeDef,
     DescribeRestoreJobInputRequestTypeDef,
+    DescribeRestoreJobOutputTypeDef,
     DisassociateRecoveryPointFromParentInputRequestTypeDef,
     DisassociateRecoveryPointInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportBackupPlanTemplateInputRequestTypeDef,
+    ExportBackupPlanTemplateOutputTypeDef,
     FrameworkTypeDef,
     GetBackupPlanFromJSONInputRequestTypeDef,
     GetBackupPlanFromTemplateInputRequestTypeDef,
     GetBackupPlanInputRequestTypeDef,
     GetBackupSelectionInputRequestTypeDef,
     GetBackupVaultAccessPolicyInputRequestTypeDef,
+    GetBackupVaultAccessPolicyOutputTypeDef,
     GetBackupVaultNotificationsInputRequestTypeDef,
+    GetBackupVaultNotificationsOutputTypeDef,
     GetLegalHoldInputRequestTypeDef,
     GetRecoveryPointRestoreMetadataInputRequestTypeDef,
+    GetRecoveryPointRestoreMetadataOutputTypeDef,
+    GetSupportedResourceTypesOutputTypeDef,
     LegalHoldTypeDef,
-    PaginatorConfigTypeDef,
+    ListBackupJobsInputListBackupJobsPaginateTypeDef,
     ListBackupJobsInputRequestTypeDef,
+    ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef,
     ListBackupPlanTemplatesInputRequestTypeDef,
+    ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
     ListBackupPlanVersionsInputRequestTypeDef,
+    ListBackupPlansInputListBackupPlansPaginateTypeDef,
     ListBackupPlansInputRequestTypeDef,
+    ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
     ListBackupSelectionsInputRequestTypeDef,
+    ListBackupVaultsInputListBackupVaultsPaginateTypeDef,
     ListBackupVaultsInputRequestTypeDef,
+    ListCopyJobsInputListCopyJobsPaginateTypeDef,
     ListCopyJobsInputRequestTypeDef,
     ListFrameworksInputRequestTypeDef,
+    ListLegalHoldsInputListLegalHoldsPaginateTypeDef,
     ListLegalHoldsInputRequestTypeDef,
+    ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef,
     ListProtectedResourcesInputRequestTypeDef,
     ProtectedResourceTypeDef,
+    ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
     ListRecoveryPointsByBackupVaultInputRequestTypeDef,
+    ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
     ListRecoveryPointsByLegalHoldInputRequestTypeDef,
     RecoveryPointMemberTypeDef,
+    ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
     ListRecoveryPointsByResourceInputRequestTypeDef,
     RecoveryPointByResourceTypeDef,
     ListReportJobsInputRequestTypeDef,
     ListReportPlansInputRequestTypeDef,
+    ListRestoreJobsInputListRestoreJobsPaginateTypeDef,
     ListRestoreJobsInputRequestTypeDef,
     RestoreJobsListMemberTypeDef,
     ListTagsInputRequestTypeDef,
+    ListTagsOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutBackupVaultAccessPolicyInputRequestTypeDef,
     PutBackupVaultLockConfigurationInputRequestTypeDef,
     PutBackupVaultNotificationsInputRequestTypeDef,
     ReportDestinationTypeDef,
+    ResponseMetadataTypeDef,
+    StartBackupJobOutputTypeDef,
+    StartCopyJobOutputTypeDef,
     StartReportJobInputRequestTypeDef,
+    StartReportJobOutputTypeDef,
     StartRestoreJobInputRequestTypeDef,
+    StartRestoreJobOutputTypeDef,
     StopBackupJobInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateFrameworkOutputTypeDef,
     UpdateGlobalSettingsInputRequestTypeDef,
     UpdateRegionSettingsInputRequestTypeDef,
+    UpdateReportPlanOutputTypeDef,
     BackupPlansListMemberTypeDef,
+    CreateBackupPlanOutputTypeDef,
+    UpdateBackupPlanOutputTypeDef,
     BackupJobTypeDef,
     CopyJobTypeDef,
+    DescribeBackupJobOutputTypeDef,
+    ListBackupPlanTemplatesOutputTypeDef,
     CopyActionTypeDef,
     StartBackupJobInputRequestTypeDef,
     StartCopyJobInputRequestTypeDef,
     UpdateRecoveryPointLifecycleInputRequestTypeDef,
-    RecoveryPointByBackupVaultTypeDef,
-    ConditionsTypeDef,
-    FrameworkControlTypeDef,
-    CreateBackupPlanOutputTypeDef,
-    CreateBackupSelectionOutputTypeDef,
-    CreateBackupVaultOutputTypeDef,
-    CreateFrameworkOutputTypeDef,
-    CreateReportPlanOutputTypeDef,
-    DeleteBackupPlanOutputTypeDef,
-    DescribeBackupJobOutputTypeDef,
-    DescribeBackupVaultOutputTypeDef,
-    DescribeGlobalSettingsOutputTypeDef,
-    DescribeProtectedResourceOutputTypeDef,
-    DescribeRecoveryPointOutputTypeDef,
-    DescribeRegionSettingsOutputTypeDef,
-    DescribeRestoreJobOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportBackupPlanTemplateOutputTypeDef,
-    GetBackupVaultAccessPolicyOutputTypeDef,
-    GetBackupVaultNotificationsOutputTypeDef,
-    GetRecoveryPointRestoreMetadataOutputTypeDef,
-    GetSupportedResourceTypesOutputTypeDef,
-    ListBackupPlanTemplatesOutputTypeDef,
     ListBackupSelectionsOutputTypeDef,
     ListBackupVaultsOutputTypeDef,
-    ListTagsOutputTypeDef,
-    StartBackupJobOutputTypeDef,
-    StartCopyJobOutputTypeDef,
-    StartReportJobOutputTypeDef,
-    StartRestoreJobOutputTypeDef,
-    UpdateBackupPlanOutputTypeDef,
-    UpdateFrameworkOutputTypeDef,
+    DescribeRecoveryPointOutputTypeDef,
+    RecoveryPointByBackupVaultTypeDef,
     UpdateRecoveryPointLifecycleOutputTypeDef,
-    UpdateReportPlanOutputTypeDef,
+    ConditionsTypeDef,
+    FrameworkControlTypeDef,
     CreateReportPlanInputRequestTypeDef,
     ReportPlanTypeDef,
     UpdateReportPlanInputRequestTypeDef,
     RecoveryPointSelectionTypeDef,
     ListFrameworksOutputTypeDef,
     ListLegalHoldsOutputTypeDef,
-    ListBackupJobsInputListBackupJobsPaginateTypeDef,
-    ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef,
-    ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
-    ListBackupPlansInputListBackupPlansPaginateTypeDef,
-    ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
-    ListBackupVaultsInputListBackupVaultsPaginateTypeDef,
-    ListCopyJobsInputListCopyJobsPaginateTypeDef,
-    ListLegalHoldsInputListLegalHoldsPaginateTypeDef,
-    ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef,
-    ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
-    ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
-    ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
-    ListRestoreJobsInputListRestoreJobsPaginateTypeDef,
     ListProtectedResourcesOutputTypeDef,
     ListRecoveryPointsByLegalHoldOutputTypeDef,
     ListRecoveryPointsByResourceOutputTypeDef,
     ListRestoreJobsOutputTypeDef,
     ReportJobTypeDef,
     ListBackupPlanVersionsOutputTypeDef,
     ListBackupPlansOutputTypeDef,
@@ -534,43 +534,43 @@
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

### Comparing `types-aiobotocore-backup-2.5.0.post1/setup.py` & `types-aiobotocore-backup-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-backup.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-backup",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_backup"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Backup 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Backup 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/"
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

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/__init__.py` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/__init__.pyi` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/__main__.py` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Backup 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Backup 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup\nOther"
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

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/client.py` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -282,15 +282,15 @@
         """
 
     async def delete_backup_selection(
         self, *, BackupPlanId: str, SelectionId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the resource selection associated with a backup plan that is specified
-        by the `SelectionId` .
+        by the `SelectionId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_selection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#delete_backup_selection)
         """
 
     async def delete_backup_vault(self, *, BackupVaultName: str) -> EmptyResponseMetadataTypeDef:
         """
@@ -354,15 +354,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_report_plan)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#delete_report_plan)
         """
 
     async def describe_backup_job(self, *, BackupJobId: str) -> DescribeBackupJobOutputTypeDef:
         """
-        Returns backup job details for the specified `BackupJobId` .
+        Returns backup job details for the specified `BackupJobId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_backup_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_backup_job)
         """
 
     async def describe_backup_vault(
         self, *, BackupVaultName: str
@@ -380,15 +380,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_copy_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_copy_job)
         """
 
     async def describe_framework(self, *, FrameworkName: str) -> DescribeFrameworkOutputTypeDef:
         """
-        Returns the framework details for the specified `FrameworkName` .
+        Returns the framework details for the specified `FrameworkName`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_framework)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_framework)
         """
 
     async def describe_global_settings(self) -> DescribeGlobalSettingsOutputTypeDef:
         """
@@ -429,15 +429,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_region_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_region_settings)
         """
 
     async def describe_report_job(self, *, ReportJobId: str) -> DescribeReportJobOutputTypeDef:
         """
         Returns the details associated with creating a report as specified by its
-        `ReportJobId` .
+        `ReportJobId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_report_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_report_job)
         """
 
     async def describe_report_plan(self, *, ReportPlanName: str) -> DescribeReportPlanOutputTypeDef:
         """
@@ -916,15 +916,16 @@
     async def start_restore_job(
         self,
         *,
         RecoveryPointArn: str,
         Metadata: Mapping[str, str],
         IamRoleArn: str = ...,
         IdempotencyToken: str = ...,
-        ResourceType: str = ...
+        ResourceType: str = ...,
+        CopySourceTagsToRestoredResource: bool = ...
     ) -> StartRestoreJobOutputTypeDef:
         """
         Recovers the saved resource identified by an Amazon Resource Name (ARN).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.start_restore_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#start_restore_job)
         """
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/client.pyi` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -267,15 +267,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#delete_backup_plan)
         """
     async def delete_backup_selection(
         self, *, BackupPlanId: str, SelectionId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the resource selection associated with a backup plan that is specified
-        by the `SelectionId` .
+        by the `SelectionId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_backup_selection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#delete_backup_selection)
         """
     async def delete_backup_vault(self, *, BackupVaultName: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the backup vault identified by its name.
@@ -331,15 +331,15 @@
         Deletes the report plan specified by a report plan name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.delete_report_plan)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#delete_report_plan)
         """
     async def describe_backup_job(self, *, BackupJobId: str) -> DescribeBackupJobOutputTypeDef:
         """
-        Returns backup job details for the specified `BackupJobId` .
+        Returns backup job details for the specified `BackupJobId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_backup_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_backup_job)
         """
     async def describe_backup_vault(
         self, *, BackupVaultName: str
     ) -> DescribeBackupVaultOutputTypeDef:
@@ -354,15 +354,15 @@
         Returns metadata associated with creating a copy of a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_copy_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_copy_job)
         """
     async def describe_framework(self, *, FrameworkName: str) -> DescribeFrameworkOutputTypeDef:
         """
-        Returns the framework details for the specified `FrameworkName` .
+        Returns the framework details for the specified `FrameworkName`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_framework)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_framework)
         """
     async def describe_global_settings(self) -> DescribeGlobalSettingsOutputTypeDef:
         """
         Describes whether the Amazon Web Services account is opted in to cross-account
@@ -398,15 +398,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_region_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_region_settings)
         """
     async def describe_report_job(self, *, ReportJobId: str) -> DescribeReportJobOutputTypeDef:
         """
         Returns the details associated with creating a report as specified by its
-        `ReportJobId` .
+        `ReportJobId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.describe_report_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#describe_report_job)
         """
     async def describe_report_plan(self, *, ReportPlanName: str) -> DescribeReportPlanOutputTypeDef:
         """
         Returns a list of all report plans for an Amazon Web Services account and Amazon
@@ -846,15 +846,16 @@
     async def start_restore_job(
         self,
         *,
         RecoveryPointArn: str,
         Metadata: Mapping[str, str],
         IamRoleArn: str = ...,
         IdempotencyToken: str = ...,
-        ResourceType: str = ...
+        ResourceType: str = ...,
+        CopySourceTagsToRestoredResource: bool = ...
     ) -> StartRestoreJobOutputTypeDef:
         """
         Recovers the saved resource identified by an Amazon Resource Name (ARN).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Client.start_restore_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/client/#start_restore_job)
         """
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/literals.py` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -157,14 +157,15 @@
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
@@ -243,14 +244,15 @@
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
@@ -261,14 +263,15 @@
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
@@ -304,14 +307,15 @@
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
@@ -330,16 +334,19 @@
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
@@ -423,15 +430,17 @@
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
@@ -471,21 +480,25 @@
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
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/literals.pyi` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -155,14 +155,15 @@
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
@@ -241,14 +242,15 @@
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
@@ -259,14 +261,15 @@
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
@@ -302,14 +305,15 @@
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
@@ -328,16 +332,19 @@
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
@@ -421,15 +428,17 @@
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
@@ -469,21 +478,25 @@
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
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/paginator.py` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -40,17 +40,16 @@
         list_protected_resources_paginator: ListProtectedResourcesPaginator = client.get_paginator("list_protected_resources")
         list_recovery_points_by_backup_vault_paginator: ListRecoveryPointsByBackupVaultPaginator = client.get_paginator("list_recovery_points_by_backup_vault")
         list_recovery_points_by_legal_hold_paginator: ListRecoveryPointsByLegalHoldPaginator = client.get_paginator("list_recovery_points_by_legal_hold")
         list_recovery_points_by_resource_paginator: ListRecoveryPointsByResourcePaginator = client.get_paginator("list_recovery_points_by_resource")
         list_restore_jobs_paginator: ListRestoreJobsPaginator = client.get_paginator("list_restore_jobs")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import BackupJobStateType, CopyJobStateType, RestoreJobStatusType
 from .type_defs import (
     ListBackupJobsOutputTypeDef,
@@ -65,20 +64,14 @@
     ListRecoveryPointsByBackupVaultOutputTypeDef,
     ListRecoveryPointsByLegalHoldOutputTypeDef,
     ListRecoveryPointsByResourceOutputTypeDef,
     ListRestoreJobsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListBackupJobsPaginator",
     "ListBackupPlanTemplatesPaginator",
     "ListBackupPlanVersionsPaginator",
     "ListBackupPlansPaginator",
     "ListBackupSelectionsPaginator",
     "ListBackupVaultsPaginator",
@@ -117,90 +110,90 @@
         ByCreatedBefore: Union[datetime, str] = ...,
         ByCreatedAfter: Union[datetime, str] = ...,
         ByResourceType: str = ...,
         ByAccountId: str = ...,
         ByCompleteAfter: Union[datetime, str] = ...,
         ByCompleteBefore: Union[datetime, str] = ...,
         ByParentJobId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupjobspaginator)
         """
 
 
 class ListBackupPlanTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplantemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupPlanTemplatesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplantemplatespaginator)
         """
 
 
 class ListBackupPlanVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanversionspaginator)
     """
 
     def paginate(
-        self, *, BackupPlanId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, BackupPlanId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupPlanVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanversionspaginator)
         """
 
 
 class ListBackupPlansPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlans)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanspaginator)
     """
 
     def paginate(
-        self, *, IncludeDeleted: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, IncludeDeleted: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupPlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanspaginator)
         """
 
 
 class ListBackupSelectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupSelections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupselectionspaginator)
     """
 
     def paginate(
-        self, *, BackupPlanId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, BackupPlanId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupSelectionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupSelections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupselectionspaginator)
         """
 
 
 class ListBackupVaultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupVaults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupvaultspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupVaultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupVaults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupvaultspaginator)
         """
 
 
@@ -219,45 +212,45 @@
         ByCreatedAfter: Union[datetime, str] = ...,
         ByResourceType: str = ...,
         ByDestinationVaultArn: str = ...,
         ByAccountId: str = ...,
         ByCompleteBefore: Union[datetime, str] = ...,
         ByCompleteAfter: Union[datetime, str] = ...,
         ByParentJobId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCopyJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListCopyJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listcopyjobspaginator)
         """
 
 
 class ListLegalHoldsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListLegalHolds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listlegalholdspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLegalHoldsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListLegalHolds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listlegalholdspaginator)
         """
 
 
 class ListProtectedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListProtectedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listprotectedresourcespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtectedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListProtectedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listprotectedresourcespaginator)
         """
 
 
@@ -273,45 +266,45 @@
         BackupVaultName: str,
         ByResourceArn: str = ...,
         ByResourceType: str = ...,
         ByBackupPlanId: str = ...,
         ByCreatedBefore: Union[datetime, str] = ...,
         ByCreatedAfter: Union[datetime, str] = ...,
         ByParentRecoveryPointArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsByBackupVaultOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByBackupVault.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbybackupvaultpaginator)
         """
 
 
 class ListRecoveryPointsByLegalHoldPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByLegalHold)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbylegalholdpaginator)
     """
 
     def paginate(
-        self, *, LegalHoldId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, LegalHoldId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsByLegalHoldOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByLegalHold.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbylegalholdpaginator)
         """
 
 
 class ListRecoveryPointsByResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbyresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsByResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbyresourcepaginator)
         """
 
 
@@ -326,13 +319,13 @@
         *,
         ByAccountId: str = ...,
         ByCreatedBefore: Union[datetime, str] = ...,
         ByCreatedAfter: Union[datetime, str] = ...,
         ByStatus: RestoreJobStatusType = ...,
         ByCompleteBefore: Union[datetime, str] = ...,
         ByCompleteAfter: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRestoreJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRestoreJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrestorejobspaginator)
         """
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/paginator.pyi` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -40,17 +40,16 @@
         list_protected_resources_paginator: ListProtectedResourcesPaginator = client.get_paginator("list_protected_resources")
         list_recovery_points_by_backup_vault_paginator: ListRecoveryPointsByBackupVaultPaginator = client.get_paginator("list_recovery_points_by_backup_vault")
         list_recovery_points_by_legal_hold_paginator: ListRecoveryPointsByLegalHoldPaginator = client.get_paginator("list_recovery_points_by_legal_hold")
         list_recovery_points_by_resource_paginator: ListRecoveryPointsByResourcePaginator = client.get_paginator("list_recovery_points_by_resource")
         list_restore_jobs_paginator: ListRestoreJobsPaginator = client.get_paginator("list_restore_jobs")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import BackupJobStateType, CopyJobStateType, RestoreJobStatusType
 from .type_defs import (
     ListBackupJobsOutputTypeDef,
@@ -65,19 +64,14 @@
     ListRecoveryPointsByBackupVaultOutputTypeDef,
     ListRecoveryPointsByLegalHoldOutputTypeDef,
     ListRecoveryPointsByResourceOutputTypeDef,
     ListRestoreJobsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListBackupJobsPaginator",
     "ListBackupPlanTemplatesPaginator",
     "ListBackupPlanVersionsPaginator",
     "ListBackupPlansPaginator",
     "ListBackupSelectionsPaginator",
     "ListBackupVaultsPaginator",
@@ -113,85 +107,85 @@
         ByCreatedBefore: Union[datetime, str] = ...,
         ByCreatedAfter: Union[datetime, str] = ...,
         ByResourceType: str = ...,
         ByAccountId: str = ...,
         ByCompleteAfter: Union[datetime, str] = ...,
         ByCompleteBefore: Union[datetime, str] = ...,
         ByParentJobId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupjobspaginator)
         """
 
 class ListBackupPlanTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplantemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupPlanTemplatesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplantemplatespaginator)
         """
 
 class ListBackupPlanVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanversionspaginator)
     """
 
     def paginate(
-        self, *, BackupPlanId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, BackupPlanId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupPlanVersionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlanVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanversionspaginator)
         """
 
 class ListBackupPlansPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlans)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanspaginator)
     """
 
     def paginate(
-        self, *, IncludeDeleted: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, IncludeDeleted: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupPlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupplanspaginator)
         """
 
 class ListBackupSelectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupSelections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupselectionspaginator)
     """
 
     def paginate(
-        self, *, BackupPlanId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, BackupPlanId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupSelectionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupSelections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupselectionspaginator)
         """
 
 class ListBackupVaultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupVaults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupvaultspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupVaultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListBackupVaults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listbackupvaultspaginator)
         """
 
 class ListCopyJobsPaginator(AioPaginator):
@@ -209,43 +203,43 @@
         ByCreatedAfter: Union[datetime, str] = ...,
         ByResourceType: str = ...,
         ByDestinationVaultArn: str = ...,
         ByAccountId: str = ...,
         ByCompleteBefore: Union[datetime, str] = ...,
         ByCompleteAfter: Union[datetime, str] = ...,
         ByParentJobId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCopyJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListCopyJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listcopyjobspaginator)
         """
 
 class ListLegalHoldsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListLegalHolds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listlegalholdspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLegalHoldsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListLegalHolds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listlegalholdspaginator)
         """
 
 class ListProtectedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListProtectedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listprotectedresourcespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtectedResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListProtectedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listprotectedresourcespaginator)
         """
 
 class ListRecoveryPointsByBackupVaultPaginator(AioPaginator):
@@ -260,43 +254,43 @@
         BackupVaultName: str,
         ByResourceArn: str = ...,
         ByResourceType: str = ...,
         ByBackupPlanId: str = ...,
         ByCreatedBefore: Union[datetime, str] = ...,
         ByCreatedAfter: Union[datetime, str] = ...,
         ByParentRecoveryPointArn: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsByBackupVaultOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByBackupVault.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbybackupvaultpaginator)
         """
 
 class ListRecoveryPointsByLegalHoldPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByLegalHold)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbylegalholdpaginator)
     """
 
     def paginate(
-        self, *, LegalHoldId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, LegalHoldId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsByLegalHoldOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByLegalHold.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbylegalholdpaginator)
         """
 
 class ListRecoveryPointsByResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbyresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryPointsByResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRecoveryPointsByResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrecoverypointsbyresourcepaginator)
         """
 
 class ListRestoreJobsPaginator(AioPaginator):
@@ -310,13 +304,13 @@
         *,
         ByAccountId: str = ...,
         ByCreatedBefore: Union[datetime, str] = ...,
         ByCreatedAfter: Union[datetime, str] = ...,
         ByStatus: RestoreJobStatusType = ...,
         ByCompleteBefore: Union[datetime, str] = ...,
         ByCompleteAfter: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRestoreJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup.Paginator.ListRestoreJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/paginators/#listrestorejobspaginator)
         """
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/type_defs.py` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -44,143 +44,143 @@
     "BackupSelectionsListMemberTypeDef",
     "BackupVaultListMemberTypeDef",
     "CalculatedLifecycleTypeDef",
     "CancelLegalHoldInputRequestTypeDef",
     "ConditionParameterTypeDef",
     "ControlInputParameterTypeDef",
     "ControlScopeTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBackupSelectionOutputTypeDef",
     "CreateBackupVaultInputRequestTypeDef",
+    "CreateBackupVaultOutputTypeDef",
+    "CreateFrameworkOutputTypeDef",
     "ReportDeliveryChannelTypeDef",
     "ReportSettingTypeDef",
+    "CreateReportPlanOutputTypeDef",
     "DateRangeTypeDef",
     "DeleteBackupPlanInputRequestTypeDef",
+    "DeleteBackupPlanOutputTypeDef",
     "DeleteBackupSelectionInputRequestTypeDef",
     "DeleteBackupVaultAccessPolicyInputRequestTypeDef",
     "DeleteBackupVaultInputRequestTypeDef",
     "DeleteBackupVaultLockConfigurationInputRequestTypeDef",
     "DeleteBackupVaultNotificationsInputRequestTypeDef",
     "DeleteFrameworkInputRequestTypeDef",
     "DeleteRecoveryPointInputRequestTypeDef",
     "DeleteReportPlanInputRequestTypeDef",
     "DescribeBackupJobInputRequestTypeDef",
     "DescribeBackupVaultInputRequestTypeDef",
+    "DescribeBackupVaultOutputTypeDef",
     "DescribeCopyJobInputRequestTypeDef",
     "DescribeFrameworkInputRequestTypeDef",
+    "DescribeGlobalSettingsOutputTypeDef",
     "DescribeProtectedResourceInputRequestTypeDef",
+    "DescribeProtectedResourceOutputTypeDef",
     "DescribeRecoveryPointInputRequestTypeDef",
+    "DescribeRegionSettingsOutputTypeDef",
     "DescribeReportJobInputRequestTypeDef",
     "DescribeReportPlanInputRequestTypeDef",
     "DescribeRestoreJobInputRequestTypeDef",
+    "DescribeRestoreJobOutputTypeDef",
     "DisassociateRecoveryPointFromParentInputRequestTypeDef",
     "DisassociateRecoveryPointInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportBackupPlanTemplateInputRequestTypeDef",
+    "ExportBackupPlanTemplateOutputTypeDef",
     "FrameworkTypeDef",
     "GetBackupPlanFromJSONInputRequestTypeDef",
     "GetBackupPlanFromTemplateInputRequestTypeDef",
     "GetBackupPlanInputRequestTypeDef",
     "GetBackupSelectionInputRequestTypeDef",
     "GetBackupVaultAccessPolicyInputRequestTypeDef",
+    "GetBackupVaultAccessPolicyOutputTypeDef",
     "GetBackupVaultNotificationsInputRequestTypeDef",
+    "GetBackupVaultNotificationsOutputTypeDef",
     "GetLegalHoldInputRequestTypeDef",
     "GetRecoveryPointRestoreMetadataInputRequestTypeDef",
+    "GetRecoveryPointRestoreMetadataOutputTypeDef",
+    "GetSupportedResourceTypesOutputTypeDef",
     "LegalHoldTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
     "ListBackupJobsInputRequestTypeDef",
+    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
     "ListBackupPlanTemplatesInputRequestTypeDef",
+    "ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
     "ListBackupPlanVersionsInputRequestTypeDef",
+    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
     "ListBackupPlansInputRequestTypeDef",
+    "ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
     "ListBackupSelectionsInputRequestTypeDef",
+    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
     "ListBackupVaultsInputRequestTypeDef",
+    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
     "ListCopyJobsInputRequestTypeDef",
     "ListFrameworksInputRequestTypeDef",
+    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
     "ListLegalHoldsInputRequestTypeDef",
+    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
     "ListProtectedResourcesInputRequestTypeDef",
     "ProtectedResourceTypeDef",
+    "ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
     "ListRecoveryPointsByBackupVaultInputRequestTypeDef",
+    "ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
     "ListRecoveryPointsByLegalHoldInputRequestTypeDef",
     "RecoveryPointMemberTypeDef",
+    "ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
     "ListRecoveryPointsByResourceInputRequestTypeDef",
     "RecoveryPointByResourceTypeDef",
     "ListReportJobsInputRequestTypeDef",
     "ListReportPlansInputRequestTypeDef",
+    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
     "ListRestoreJobsInputRequestTypeDef",
     "RestoreJobsListMemberTypeDef",
     "ListTagsInputRequestTypeDef",
+    "ListTagsOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutBackupVaultAccessPolicyInputRequestTypeDef",
     "PutBackupVaultLockConfigurationInputRequestTypeDef",
     "PutBackupVaultNotificationsInputRequestTypeDef",
     "ReportDestinationTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartBackupJobOutputTypeDef",
+    "StartCopyJobOutputTypeDef",
     "StartReportJobInputRequestTypeDef",
+    "StartReportJobOutputTypeDef",
     "StartRestoreJobInputRequestTypeDef",
+    "StartRestoreJobOutputTypeDef",
     "StopBackupJobInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "UpdateFrameworkOutputTypeDef",
     "UpdateGlobalSettingsInputRequestTypeDef",
     "UpdateRegionSettingsInputRequestTypeDef",
+    "UpdateReportPlanOutputTypeDef",
     "BackupPlansListMemberTypeDef",
+    "CreateBackupPlanOutputTypeDef",
+    "UpdateBackupPlanOutputTypeDef",
     "BackupJobTypeDef",
     "CopyJobTypeDef",
+    "DescribeBackupJobOutputTypeDef",
+    "ListBackupPlanTemplatesOutputTypeDef",
     "CopyActionTypeDef",
     "StartBackupJobInputRequestTypeDef",
     "StartCopyJobInputRequestTypeDef",
     "UpdateRecoveryPointLifecycleInputRequestTypeDef",
-    "RecoveryPointByBackupVaultTypeDef",
-    "ConditionsTypeDef",
-    "FrameworkControlTypeDef",
-    "CreateBackupPlanOutputTypeDef",
-    "CreateBackupSelectionOutputTypeDef",
-    "CreateBackupVaultOutputTypeDef",
-    "CreateFrameworkOutputTypeDef",
-    "CreateReportPlanOutputTypeDef",
-    "DeleteBackupPlanOutputTypeDef",
-    "DescribeBackupJobOutputTypeDef",
-    "DescribeBackupVaultOutputTypeDef",
-    "DescribeGlobalSettingsOutputTypeDef",
-    "DescribeProtectedResourceOutputTypeDef",
-    "DescribeRecoveryPointOutputTypeDef",
-    "DescribeRegionSettingsOutputTypeDef",
-    "DescribeRestoreJobOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportBackupPlanTemplateOutputTypeDef",
-    "GetBackupVaultAccessPolicyOutputTypeDef",
-    "GetBackupVaultNotificationsOutputTypeDef",
-    "GetRecoveryPointRestoreMetadataOutputTypeDef",
-    "GetSupportedResourceTypesOutputTypeDef",
-    "ListBackupPlanTemplatesOutputTypeDef",
     "ListBackupSelectionsOutputTypeDef",
     "ListBackupVaultsOutputTypeDef",
-    "ListTagsOutputTypeDef",
-    "StartBackupJobOutputTypeDef",
-    "StartCopyJobOutputTypeDef",
-    "StartReportJobOutputTypeDef",
-    "StartRestoreJobOutputTypeDef",
-    "UpdateBackupPlanOutputTypeDef",
-    "UpdateFrameworkOutputTypeDef",
+    "DescribeRecoveryPointOutputTypeDef",
+    "RecoveryPointByBackupVaultTypeDef",
     "UpdateRecoveryPointLifecycleOutputTypeDef",
-    "UpdateReportPlanOutputTypeDef",
+    "ConditionsTypeDef",
+    "FrameworkControlTypeDef",
     "CreateReportPlanInputRequestTypeDef",
     "ReportPlanTypeDef",
     "UpdateReportPlanInputRequestTypeDef",
     "RecoveryPointSelectionTypeDef",
     "ListFrameworksOutputTypeDef",
     "ListLegalHoldsOutputTypeDef",
-    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
-    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
-    "ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
-    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
-    "ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
-    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
-    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
-    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
-    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
-    "ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
-    "ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
-    "ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
-    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
     "ListProtectedResourcesOutputTypeDef",
     "ListRecoveryPointsByLegalHoldOutputTypeDef",
     "ListRecoveryPointsByResourceOutputTypeDef",
     "ListRestoreJobsOutputTypeDef",
     "ReportJobTypeDef",
     "ListBackupPlanVersionsOutputTypeDef",
     "ListBackupPlansOutputTypeDef",
@@ -344,22 +344,21 @@
         "ComplianceResourceIds": Sequence[str],
         "ComplianceResourceTypes": Sequence[str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBackupSelectionOutputTypeDef = TypedDict(
+    "CreateBackupSelectionOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "SelectionId": str,
+        "BackupPlanId": str,
+        "CreationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBackupVaultInputRequestTypeDef = TypedDict(
     "_RequiredCreateBackupVaultInputRequestTypeDef",
     {
         "BackupVaultName": str,
@@ -378,14 +377,33 @@
 
 class CreateBackupVaultInputRequestTypeDef(
     _RequiredCreateBackupVaultInputRequestTypeDef, _OptionalCreateBackupVaultInputRequestTypeDef
 ):
     pass
 
 
+CreateBackupVaultOutputTypeDef = TypedDict(
+    "CreateBackupVaultOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "CreationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFrameworkOutputTypeDef = TypedDict(
+    "CreateFrameworkOutputTypeDef",
+    {
+        "FrameworkName": str,
+        "FrameworkArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredReportDeliveryChannelTypeDef = TypedDict(
     "_RequiredReportDeliveryChannelTypeDef",
     {
         "S3BucketName": str,
     },
 )
 _OptionalReportDeliveryChannelTypeDef = TypedDict(
@@ -423,14 +441,24 @@
 )
 
 
 class ReportSettingTypeDef(_RequiredReportSettingTypeDef, _OptionalReportSettingTypeDef):
     pass
 
 
+CreateReportPlanOutputTypeDef = TypedDict(
+    "CreateReportPlanOutputTypeDef",
+    {
+        "ReportPlanName": str,
+        "ReportPlanArn": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DateRangeTypeDef = TypedDict(
     "DateRangeTypeDef",
     {
         "FromDate": Union[datetime, str],
         "ToDate": Union[datetime, str],
     },
 )
@@ -438,14 +466,25 @@
 DeleteBackupPlanInputRequestTypeDef = TypedDict(
     "DeleteBackupPlanInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 
+DeleteBackupPlanOutputTypeDef = TypedDict(
+    "DeleteBackupPlanOutputTypeDef",
+    {
+        "BackupPlanId": str,
+        "BackupPlanArn": str,
+        "DeletionDate": datetime,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteBackupSelectionInputRequestTypeDef = TypedDict(
     "DeleteBackupSelectionInputRequestTypeDef",
     {
         "BackupPlanId": str,
         "SelectionId": str,
     },
 )
@@ -510,43 +549,89 @@
 DescribeBackupVaultInputRequestTypeDef = TypedDict(
     "DescribeBackupVaultInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 
+DescribeBackupVaultOutputTypeDef = TypedDict(
+    "DescribeBackupVaultOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "EncryptionKeyArn": str,
+        "CreationDate": datetime,
+        "CreatorRequestId": str,
+        "NumberOfRecoveryPoints": int,
+        "Locked": bool,
+        "MinRetentionDays": int,
+        "MaxRetentionDays": int,
+        "LockDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeCopyJobInputRequestTypeDef = TypedDict(
     "DescribeCopyJobInputRequestTypeDef",
     {
         "CopyJobId": str,
     },
 )
 
 DescribeFrameworkInputRequestTypeDef = TypedDict(
     "DescribeFrameworkInputRequestTypeDef",
     {
         "FrameworkName": str,
     },
 )
 
+DescribeGlobalSettingsOutputTypeDef = TypedDict(
+    "DescribeGlobalSettingsOutputTypeDef",
+    {
+        "GlobalSettings": Dict[str, str],
+        "LastUpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeProtectedResourceInputRequestTypeDef = TypedDict(
     "DescribeProtectedResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+DescribeProtectedResourceOutputTypeDef = TypedDict(
+    "DescribeProtectedResourceOutputTypeDef",
+    {
+        "ResourceArn": str,
+        "ResourceType": str,
+        "LastBackupTime": datetime,
+        "ResourceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRecoveryPointInputRequestTypeDef = TypedDict(
     "DescribeRecoveryPointInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
 
+DescribeRegionSettingsOutputTypeDef = TypedDict(
+    "DescribeRegionSettingsOutputTypeDef",
+    {
+        "ResourceTypeOptInPreference": Dict[str, bool],
+        "ResourceTypeManagementPreference": Dict[str, bool],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeReportJobInputRequestTypeDef = TypedDict(
     "DescribeReportJobInputRequestTypeDef",
     {
         "ReportJobId": str,
     },
 )
 
@@ -560,14 +645,34 @@
 DescribeRestoreJobInputRequestTypeDef = TypedDict(
     "DescribeRestoreJobInputRequestTypeDef",
     {
         "RestoreJobId": str,
     },
 )
 
+DescribeRestoreJobOutputTypeDef = TypedDict(
+    "DescribeRestoreJobOutputTypeDef",
+    {
+        "AccountId": str,
+        "RestoreJobId": str,
+        "RecoveryPointArn": str,
+        "CreationDate": datetime,
+        "CompletionDate": datetime,
+        "Status": RestoreJobStatusType,
+        "StatusMessage": str,
+        "PercentDone": str,
+        "BackupSizeInBytes": int,
+        "IamRoleArn": str,
+        "ExpectedCompletionTimeMinutes": int,
+        "CreatedResourceArn": str,
+        "ResourceType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateRecoveryPointFromParentInputRequestTypeDef = TypedDict(
     "DisassociateRecoveryPointFromParentInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
@@ -576,21 +681,36 @@
     "DisassociateRecoveryPointInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportBackupPlanTemplateInputRequestTypeDef = TypedDict(
     "ExportBackupPlanTemplateInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 
+ExportBackupPlanTemplateOutputTypeDef = TypedDict(
+    "ExportBackupPlanTemplateOutputTypeDef",
+    {
+        "BackupPlanTemplateJson": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FrameworkTypeDef = TypedDict(
     "FrameworkTypeDef",
     {
         "FrameworkName": str,
         "FrameworkArn": str,
         "FrameworkDescription": str,
         "NumberOfControls": int,
@@ -646,21 +766,42 @@
 GetBackupVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "GetBackupVaultAccessPolicyInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 
+GetBackupVaultAccessPolicyOutputTypeDef = TypedDict(
+    "GetBackupVaultAccessPolicyOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBackupVaultNotificationsInputRequestTypeDef = TypedDict(
     "GetBackupVaultNotificationsInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 
+GetBackupVaultNotificationsOutputTypeDef = TypedDict(
+    "GetBackupVaultNotificationsOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "SNSTopicArn": str,
+        "BackupVaultEvents": List[BackupVaultEventType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLegalHoldInputRequestTypeDef = TypedDict(
     "GetLegalHoldInputRequestTypeDef",
     {
         "LegalHoldId": str,
     },
 )
 
@@ -668,34 +809,60 @@
     "GetRecoveryPointRestoreMetadataInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
 
+GetRecoveryPointRestoreMetadataOutputTypeDef = TypedDict(
+    "GetRecoveryPointRestoreMetadataOutputTypeDef",
+    {
+        "BackupVaultArn": str,
+        "RecoveryPointArn": str,
+        "RestoreMetadata": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSupportedResourceTypesOutputTypeDef = TypedDict(
+    "GetSupportedResourceTypesOutputTypeDef",
+    {
+        "ResourceTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LegalHoldTypeDef = TypedDict(
     "LegalHoldTypeDef",
     {
         "Title": str,
         "Status": LegalHoldStatusType,
         "Description": str,
         "LegalHoldId": str,
         "LegalHoldArn": str,
         "CreationDate": datetime,
         "CancellationDate": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListBackupJobsInputListBackupJobsPaginateTypeDef = TypedDict(
+    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ByResourceArn": str,
+        "ByState": BackupJobStateType,
+        "ByBackupVaultName": str,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByResourceType": str,
+        "ByAccountId": str,
+        "ByCompleteAfter": Union[datetime, str],
+        "ByCompleteBefore": Union[datetime, str],
+        "ByParentJobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBackupJobsInputRequestTypeDef = TypedDict(
     "ListBackupJobsInputRequestTypeDef",
     {
@@ -711,23 +878,53 @@
         "ByCompleteAfter": Union[datetime, str],
         "ByCompleteBefore": Union[datetime, str],
         "ByParentJobId": str,
     },
     total=False,
 )
 
+ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef = TypedDict(
+    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBackupPlanTemplatesInputRequestTypeDef = TypedDict(
     "ListBackupPlanTemplatesInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
+    {
+        "BackupPlanId": str,
+    },
+)
+_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef(
+    _RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
+    _OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListBackupPlanVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListBackupPlanVersionsInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 _OptionalListBackupPlanVersionsInputRequestTypeDef = TypedDict(
@@ -743,24 +940,55 @@
 class ListBackupPlanVersionsInputRequestTypeDef(
     _RequiredListBackupPlanVersionsInputRequestTypeDef,
     _OptionalListBackupPlanVersionsInputRequestTypeDef,
 ):
     pass
 
 
+ListBackupPlansInputListBackupPlansPaginateTypeDef = TypedDict(
+    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
+    {
+        "IncludeDeleted": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBackupPlansInputRequestTypeDef = TypedDict(
     "ListBackupPlansInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "IncludeDeleted": bool,
     },
     total=False,
 )
 
+_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
+    "_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
+    {
+        "BackupPlanId": str,
+    },
+)
+_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
+    "_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef(
+    _RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
+    _OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListBackupSelectionsInputRequestTypeDef = TypedDict(
     "_RequiredListBackupSelectionsInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 _OptionalListBackupSelectionsInputRequestTypeDef = TypedDict(
@@ -776,23 +1004,49 @@
 class ListBackupSelectionsInputRequestTypeDef(
     _RequiredListBackupSelectionsInputRequestTypeDef,
     _OptionalListBackupSelectionsInputRequestTypeDef,
 ):
     pass
 
 
+ListBackupVaultsInputListBackupVaultsPaginateTypeDef = TypedDict(
+    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBackupVaultsInputRequestTypeDef = TypedDict(
     "ListBackupVaultsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListCopyJobsInputListCopyJobsPaginateTypeDef = TypedDict(
+    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
+    {
+        "ByResourceArn": str,
+        "ByState": CopyJobStateType,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByResourceType": str,
+        "ByDestinationVaultArn": str,
+        "ByAccountId": str,
+        "ByCompleteBefore": Union[datetime, str],
+        "ByCompleteAfter": Union[datetime, str],
+        "ByParentJobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCopyJobsInputRequestTypeDef = TypedDict(
     "ListCopyJobsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ByResourceArn": str,
         "ByState": CopyJobStateType,
@@ -813,23 +1067,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListLegalHoldsInputListLegalHoldsPaginateTypeDef = TypedDict(
+    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLegalHoldsInputRequestTypeDef = TypedDict(
     "ListLegalHoldsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef = TypedDict(
+    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProtectedResourcesInputRequestTypeDef = TypedDict(
     "ListProtectedResourcesInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -842,14 +1112,42 @@
         "ResourceType": str,
         "LastBackupTime": datetime,
         "ResourceName": str,
     },
     total=False,
 )
 
+_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
+    "_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
+    {
+        "BackupVaultName": str,
+    },
+)
+_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
+    "_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
+    {
+        "ByResourceArn": str,
+        "ByResourceType": str,
+        "ByBackupPlanId": str,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByParentRecoveryPointArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef(
+    _RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
+    _OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRecoveryPointsByBackupVaultInputRequestTypeDef = TypedDict(
     "_RequiredListRecoveryPointsByBackupVaultInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 _OptionalListRecoveryPointsByBackupVaultInputRequestTypeDef = TypedDict(
@@ -871,14 +1169,36 @@
 class ListRecoveryPointsByBackupVaultInputRequestTypeDef(
     _RequiredListRecoveryPointsByBackupVaultInputRequestTypeDef,
     _OptionalListRecoveryPointsByBackupVaultInputRequestTypeDef,
 ):
     pass
 
 
+_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
+    "_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
+    {
+        "LegalHoldId": str,
+    },
+)
+_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
+    "_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef(
+    _RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
+    _OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRecoveryPointsByLegalHoldInputRequestTypeDef = TypedDict(
     "_RequiredListRecoveryPointsByLegalHoldInputRequestTypeDef",
     {
         "LegalHoldId": str,
     },
 )
 _OptionalListRecoveryPointsByLegalHoldInputRequestTypeDef = TypedDict(
@@ -898,18 +1218,43 @@
     pass
 
 
 RecoveryPointMemberTypeDef = TypedDict(
     "RecoveryPointMemberTypeDef",
     {
         "RecoveryPointArn": str,
+        "ResourceArn": str,
+        "ResourceType": str,
+        "BackupVaultName": str,
     },
     total=False,
 )
 
+_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
+    "_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
+    "_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef(
+    _RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
+    _OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRecoveryPointsByResourceInputRequestTypeDef = TypedDict(
     "_RequiredListRecoveryPointsByResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListRecoveryPointsByResourceInputRequestTypeDef = TypedDict(
@@ -964,14 +1309,28 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListRestoreJobsInputListRestoreJobsPaginateTypeDef = TypedDict(
+    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
+    {
+        "ByAccountId": str,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByStatus": RestoreJobStatusType,
+        "ByCompleteBefore": Union[datetime, str],
+        "ByCompleteAfter": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRestoreJobsInputRequestTypeDef = TypedDict(
     "ListRestoreJobsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ByAccountId": str,
         "ByCreatedBefore": Union[datetime, str],
@@ -1021,14 +1380,33 @@
 
 class ListTagsInputRequestTypeDef(
     _RequiredListTagsInputRequestTypeDef, _OptionalListTagsInputRequestTypeDef
 ):
     pass
 
 
+ListTagsOutputTypeDef = TypedDict(
+    "ListTagsOutputTypeDef",
+    {
+        "NextToken": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 _RequiredPutBackupVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredPutBackupVaultAccessPolicyInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 _OptionalPutBackupVaultAccessPolicyInputRequestTypeDef = TypedDict(
@@ -1085,14 +1463,46 @@
     {
         "S3BucketName": str,
         "S3Keys": List[str],
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
+StartBackupJobOutputTypeDef = TypedDict(
+    "StartBackupJobOutputTypeDef",
+    {
+        "BackupJobId": str,
+        "RecoveryPointArn": str,
+        "CreationDate": datetime,
+        "IsParent": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartCopyJobOutputTypeDef = TypedDict(
+    "StartCopyJobOutputTypeDef",
+    {
+        "CopyJobId": str,
+        "CreationDate": datetime,
+        "IsParent": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartReportJobInputRequestTypeDef = TypedDict(
     "_RequiredStartReportJobInputRequestTypeDef",
     {
         "ReportPlanName": str,
     },
 )
 _OptionalStartReportJobInputRequestTypeDef = TypedDict(
@@ -1106,38 +1516,55 @@
 
 class StartReportJobInputRequestTypeDef(
     _RequiredStartReportJobInputRequestTypeDef, _OptionalStartReportJobInputRequestTypeDef
 ):
     pass
 
 
+StartReportJobOutputTypeDef = TypedDict(
+    "StartReportJobOutputTypeDef",
+    {
+        "ReportJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartRestoreJobInputRequestTypeDef = TypedDict(
     "_RequiredStartRestoreJobInputRequestTypeDef",
     {
         "RecoveryPointArn": str,
         "Metadata": Mapping[str, str],
     },
 )
 _OptionalStartRestoreJobInputRequestTypeDef = TypedDict(
     "_OptionalStartRestoreJobInputRequestTypeDef",
     {
         "IamRoleArn": str,
         "IdempotencyToken": str,
         "ResourceType": str,
+        "CopySourceTagsToRestoredResource": bool,
     },
     total=False,
 )
 
 
 class StartRestoreJobInputRequestTypeDef(
     _RequiredStartRestoreJobInputRequestTypeDef, _OptionalStartRestoreJobInputRequestTypeDef
 ):
     pass
 
 
+StartRestoreJobOutputTypeDef = TypedDict(
+    "StartRestoreJobOutputTypeDef",
+    {
+        "RestoreJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopBackupJobInputRequestTypeDef = TypedDict(
     "StopBackupJobInputRequestTypeDef",
     {
         "BackupJobId": str,
     },
 )
 
@@ -1153,14 +1580,24 @@
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeyList": Sequence[str],
     },
 )
 
+UpdateFrameworkOutputTypeDef = TypedDict(
+    "UpdateFrameworkOutputTypeDef",
+    {
+        "FrameworkName": str,
+        "FrameworkArn": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateGlobalSettingsInputRequestTypeDef = TypedDict(
     "UpdateGlobalSettingsInputRequestTypeDef",
     {
         "GlobalSettings": Mapping[str, str],
     },
     total=False,
 )
@@ -1170,14 +1607,24 @@
     {
         "ResourceTypeOptInPreference": Mapping[str, bool],
         "ResourceTypeManagementPreference": Mapping[str, bool],
     },
     total=False,
 )
 
+UpdateReportPlanOutputTypeDef = TypedDict(
+    "UpdateReportPlanOutputTypeDef",
+    {
+        "ReportPlanName": str,
+        "ReportPlanArn": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BackupPlansListMemberTypeDef = TypedDict(
     "BackupPlansListMemberTypeDef",
     {
         "BackupPlanArn": str,
         "BackupPlanId": str,
         "CreationDate": datetime,
         "DeletionDate": datetime,
@@ -1186,14 +1633,38 @@
         "CreatorRequestId": str,
         "LastExecutionDate": datetime,
         "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
     },
     total=False,
 )
 
+CreateBackupPlanOutputTypeDef = TypedDict(
+    "CreateBackupPlanOutputTypeDef",
+    {
+        "BackupPlanId": str,
+        "BackupPlanArn": str,
+        "CreationDate": datetime,
+        "VersionId": str,
+        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBackupPlanOutputTypeDef = TypedDict(
+    "UpdateBackupPlanOutputTypeDef",
+    {
+        "BackupPlanId": str,
+        "BackupPlanArn": str,
+        "CreationDate": datetime,
+        "VersionId": str,
+        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BackupJobTypeDef = TypedDict(
     "BackupJobTypeDef",
     {
         "AccountId": str,
         "BackupJobId": str,
         "BackupVaultName": str,
         "BackupVaultArn": str,
@@ -1244,14 +1715,55 @@
         "NumberOfChildJobs": int,
         "ChildJobsInState": Dict[CopyJobStateType, int],
         "ResourceName": str,
     },
     total=False,
 )
 
+DescribeBackupJobOutputTypeDef = TypedDict(
+    "DescribeBackupJobOutputTypeDef",
+    {
+        "AccountId": str,
+        "BackupJobId": str,
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "RecoveryPointArn": str,
+        "ResourceArn": str,
+        "CreationDate": datetime,
+        "CompletionDate": datetime,
+        "State": BackupJobStateType,
+        "StatusMessage": str,
+        "PercentDone": str,
+        "BackupSizeInBytes": int,
+        "IamRoleArn": str,
+        "CreatedBy": RecoveryPointCreatorTypeDef,
+        "ResourceType": str,
+        "BytesTransferred": int,
+        "ExpectedCompletionDate": datetime,
+        "StartBy": datetime,
+        "BackupOptions": Dict[str, str],
+        "BackupType": str,
+        "ParentJobId": str,
+        "IsParent": bool,
+        "NumberOfChildJobs": int,
+        "ChildJobsInState": Dict[BackupJobStateType, int],
+        "ResourceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBackupPlanTemplatesOutputTypeDef = TypedDict(
+    "ListBackupPlanTemplatesOutputTypeDef",
+    {
+        "NextToken": str,
+        "BackupPlanTemplatesList": List[BackupPlanTemplatesListMemberTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCopyActionTypeDef = TypedDict(
     "_RequiredCopyActionTypeDef",
     {
         "DestinationBackupVaultArn": str,
     },
 )
 _OptionalCopyActionTypeDef = TypedDict(
@@ -1339,16 +1851,34 @@
 class UpdateRecoveryPointLifecycleInputRequestTypeDef(
     _RequiredUpdateRecoveryPointLifecycleInputRequestTypeDef,
     _OptionalUpdateRecoveryPointLifecycleInputRequestTypeDef,
 ):
     pass
 
 
-RecoveryPointByBackupVaultTypeDef = TypedDict(
-    "RecoveryPointByBackupVaultTypeDef",
+ListBackupSelectionsOutputTypeDef = TypedDict(
+    "ListBackupSelectionsOutputTypeDef",
+    {
+        "NextToken": str,
+        "BackupSelectionsList": List[BackupSelectionsListMemberTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBackupVaultsOutputTypeDef = TypedDict(
+    "ListBackupVaultsOutputTypeDef",
+    {
+        "BackupVaultList": List[BackupVaultListMemberTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeRecoveryPointOutputTypeDef = TypedDict(
+    "DescribeRecoveryPointOutputTypeDef",
     {
         "RecoveryPointArn": str,
         "BackupVaultName": str,
         "BackupVaultArn": str,
         "SourceBackupVaultArn": str,
         "ResourceArn": str,
         "ResourceType": str,
@@ -1359,187 +1889,26 @@
         "CreationDate": datetime,
         "CompletionDate": datetime,
         "BackupSizeInBytes": int,
         "CalculatedLifecycle": CalculatedLifecycleTypeDef,
         "Lifecycle": LifecycleTypeDef,
         "EncryptionKeyArn": str,
         "IsEncrypted": bool,
+        "StorageClass": StorageClassType,
         "LastRestoreTime": datetime,
         "ParentRecoveryPointArn": str,
         "CompositeMemberIdentifier": str,
         "IsParent": bool,
         "ResourceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ConditionsTypeDef = TypedDict(
-    "ConditionsTypeDef",
-    {
-        "StringEquals": Sequence[ConditionParameterTypeDef],
-        "StringNotEquals": Sequence[ConditionParameterTypeDef],
-        "StringLike": Sequence[ConditionParameterTypeDef],
-        "StringNotLike": Sequence[ConditionParameterTypeDef],
-    },
-    total=False,
-)
-
-_RequiredFrameworkControlTypeDef = TypedDict(
-    "_RequiredFrameworkControlTypeDef",
-    {
-        "ControlName": str,
-    },
-)
-_OptionalFrameworkControlTypeDef = TypedDict(
-    "_OptionalFrameworkControlTypeDef",
-    {
-        "ControlInputParameters": Sequence[ControlInputParameterTypeDef],
-        "ControlScope": ControlScopeTypeDef,
-    },
-    total=False,
 )
 
-
-class FrameworkControlTypeDef(_RequiredFrameworkControlTypeDef, _OptionalFrameworkControlTypeDef):
-    pass
-
-
-CreateBackupPlanOutputTypeDef = TypedDict(
-    "CreateBackupPlanOutputTypeDef",
-    {
-        "BackupPlanId": str,
-        "BackupPlanArn": str,
-        "CreationDate": datetime,
-        "VersionId": str,
-        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBackupSelectionOutputTypeDef = TypedDict(
-    "CreateBackupSelectionOutputTypeDef",
-    {
-        "SelectionId": str,
-        "BackupPlanId": str,
-        "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBackupVaultOutputTypeDef = TypedDict(
-    "CreateBackupVaultOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFrameworkOutputTypeDef = TypedDict(
-    "CreateFrameworkOutputTypeDef",
-    {
-        "FrameworkName": str,
-        "FrameworkArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateReportPlanOutputTypeDef = TypedDict(
-    "CreateReportPlanOutputTypeDef",
-    {
-        "ReportPlanName": str,
-        "ReportPlanArn": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBackupPlanOutputTypeDef = TypedDict(
-    "DeleteBackupPlanOutputTypeDef",
-    {
-        "BackupPlanId": str,
-        "BackupPlanArn": str,
-        "DeletionDate": datetime,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBackupJobOutputTypeDef = TypedDict(
-    "DescribeBackupJobOutputTypeDef",
-    {
-        "AccountId": str,
-        "BackupJobId": str,
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "RecoveryPointArn": str,
-        "ResourceArn": str,
-        "CreationDate": datetime,
-        "CompletionDate": datetime,
-        "State": BackupJobStateType,
-        "StatusMessage": str,
-        "PercentDone": str,
-        "BackupSizeInBytes": int,
-        "IamRoleArn": str,
-        "CreatedBy": RecoveryPointCreatorTypeDef,
-        "ResourceType": str,
-        "BytesTransferred": int,
-        "ExpectedCompletionDate": datetime,
-        "StartBy": datetime,
-        "BackupOptions": Dict[str, str],
-        "BackupType": str,
-        "ParentJobId": str,
-        "IsParent": bool,
-        "NumberOfChildJobs": int,
-        "ChildJobsInState": Dict[BackupJobStateType, int],
-        "ResourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBackupVaultOutputTypeDef = TypedDict(
-    "DescribeBackupVaultOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "EncryptionKeyArn": str,
-        "CreationDate": datetime,
-        "CreatorRequestId": str,
-        "NumberOfRecoveryPoints": int,
-        "Locked": bool,
-        "MinRetentionDays": int,
-        "MaxRetentionDays": int,
-        "LockDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGlobalSettingsOutputTypeDef = TypedDict(
-    "DescribeGlobalSettingsOutputTypeDef",
-    {
-        "GlobalSettings": Dict[str, str],
-        "LastUpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProtectedResourceOutputTypeDef = TypedDict(
-    "DescribeProtectedResourceOutputTypeDef",
-    {
-        "ResourceArn": str,
-        "ResourceType": str,
-        "LastBackupTime": datetime,
-        "ResourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRecoveryPointOutputTypeDef = TypedDict(
-    "DescribeRecoveryPointOutputTypeDef",
+RecoveryPointByBackupVaultTypeDef = TypedDict(
+    "RecoveryPointByBackupVaultTypeDef",
     {
         "RecoveryPointArn": str,
         "BackupVaultName": str,
         "BackupVaultArn": str,
         "SourceBackupVaultArn": str,
         "ResourceArn": str,
         "ResourceType": str,
@@ -1550,222 +1919,64 @@
         "CreationDate": datetime,
         "CompletionDate": datetime,
         "BackupSizeInBytes": int,
         "CalculatedLifecycle": CalculatedLifecycleTypeDef,
         "Lifecycle": LifecycleTypeDef,
         "EncryptionKeyArn": str,
         "IsEncrypted": bool,
-        "StorageClass": StorageClassType,
         "LastRestoreTime": datetime,
         "ParentRecoveryPointArn": str,
         "CompositeMemberIdentifier": str,
         "IsParent": bool,
         "ResourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRegionSettingsOutputTypeDef = TypedDict(
-    "DescribeRegionSettingsOutputTypeDef",
-    {
-        "ResourceTypeOptInPreference": Dict[str, bool],
-        "ResourceTypeManagementPreference": Dict[str, bool],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRestoreJobOutputTypeDef = TypedDict(
-    "DescribeRestoreJobOutputTypeDef",
-    {
-        "AccountId": str,
-        "RestoreJobId": str,
-        "RecoveryPointArn": str,
-        "CreationDate": datetime,
-        "CompletionDate": datetime,
-        "Status": RestoreJobStatusType,
-        "StatusMessage": str,
-        "PercentDone": str,
-        "BackupSizeInBytes": int,
-        "IamRoleArn": str,
-        "ExpectedCompletionTimeMinutes": int,
-        "CreatedResourceArn": str,
-        "ResourceType": str,
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
-ExportBackupPlanTemplateOutputTypeDef = TypedDict(
-    "ExportBackupPlanTemplateOutputTypeDef",
-    {
-        "BackupPlanTemplateJson": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBackupVaultAccessPolicyOutputTypeDef = TypedDict(
-    "GetBackupVaultAccessPolicyOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBackupVaultNotificationsOutputTypeDef = TypedDict(
-    "GetBackupVaultNotificationsOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "SNSTopicArn": str,
-        "BackupVaultEvents": List[BackupVaultEventType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-GetRecoveryPointRestoreMetadataOutputTypeDef = TypedDict(
-    "GetRecoveryPointRestoreMetadataOutputTypeDef",
+UpdateRecoveryPointLifecycleOutputTypeDef = TypedDict(
+    "UpdateRecoveryPointLifecycleOutputTypeDef",
     {
         "BackupVaultArn": str,
         "RecoveryPointArn": str,
-        "RestoreMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSupportedResourceTypesOutputTypeDef = TypedDict(
-    "GetSupportedResourceTypesOutputTypeDef",
-    {
-        "ResourceTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupPlanTemplatesOutputTypeDef = TypedDict(
-    "ListBackupPlanTemplatesOutputTypeDef",
-    {
-        "NextToken": str,
-        "BackupPlanTemplatesList": List[BackupPlanTemplatesListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupSelectionsOutputTypeDef = TypedDict(
-    "ListBackupSelectionsOutputTypeDef",
-    {
-        "NextToken": str,
-        "BackupSelectionsList": List[BackupSelectionsListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupVaultsOutputTypeDef = TypedDict(
-    "ListBackupVaultsOutputTypeDef",
-    {
-        "BackupVaultList": List[BackupVaultListMemberTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsOutputTypeDef = TypedDict(
-    "ListTagsOutputTypeDef",
-    {
-        "NextToken": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartBackupJobOutputTypeDef = TypedDict(
-    "StartBackupJobOutputTypeDef",
-    {
-        "BackupJobId": str,
-        "RecoveryPointArn": str,
-        "CreationDate": datetime,
-        "IsParent": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartCopyJobOutputTypeDef = TypedDict(
-    "StartCopyJobOutputTypeDef",
-    {
-        "CopyJobId": str,
-        "CreationDate": datetime,
-        "IsParent": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Lifecycle": LifecycleTypeDef,
+        "CalculatedLifecycle": CalculatedLifecycleTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartReportJobOutputTypeDef = TypedDict(
-    "StartReportJobOutputTypeDef",
+ConditionsTypeDef = TypedDict(
+    "ConditionsTypeDef",
     {
-        "ReportJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StringEquals": Sequence[ConditionParameterTypeDef],
+        "StringNotEquals": Sequence[ConditionParameterTypeDef],
+        "StringLike": Sequence[ConditionParameterTypeDef],
+        "StringNotLike": Sequence[ConditionParameterTypeDef],
     },
+    total=False,
 )
 
-StartRestoreJobOutputTypeDef = TypedDict(
-    "StartRestoreJobOutputTypeDef",
+_RequiredFrameworkControlTypeDef = TypedDict(
+    "_RequiredFrameworkControlTypeDef",
     {
-        "RestoreJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ControlName": str,
     },
 )
-
-UpdateBackupPlanOutputTypeDef = TypedDict(
-    "UpdateBackupPlanOutputTypeDef",
+_OptionalFrameworkControlTypeDef = TypedDict(
+    "_OptionalFrameworkControlTypeDef",
     {
-        "BackupPlanId": str,
-        "BackupPlanArn": str,
-        "CreationDate": datetime,
-        "VersionId": str,
-        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ControlInputParameters": Sequence[ControlInputParameterTypeDef],
+        "ControlScope": ControlScopeTypeDef,
     },
+    total=False,
 )
 
-UpdateFrameworkOutputTypeDef = TypedDict(
-    "UpdateFrameworkOutputTypeDef",
-    {
-        "FrameworkName": str,
-        "FrameworkArn": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateRecoveryPointLifecycleOutputTypeDef = TypedDict(
-    "UpdateRecoveryPointLifecycleOutputTypeDef",
-    {
-        "BackupVaultArn": str,
-        "RecoveryPointArn": str,
-        "Lifecycle": LifecycleTypeDef,
-        "CalculatedLifecycle": CalculatedLifecycleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class FrameworkControlTypeDef(_RequiredFrameworkControlTypeDef, _OptionalFrameworkControlTypeDef):
+    pass
 
-UpdateReportPlanOutputTypeDef = TypedDict(
-    "UpdateReportPlanOutputTypeDef",
-    {
-        "ReportPlanName": str,
-        "ReportPlanArn": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 _RequiredCreateReportPlanInputRequestTypeDef = TypedDict(
     "_RequiredCreateReportPlanInputRequestTypeDef",
     {
         "ReportPlanName": str,
         "ReportDeliveryChannel": ReportDeliveryChannelTypeDef,
         "ReportSetting": ReportSettingTypeDef,
@@ -1839,267 +2050,60 @@
 )
 
 ListFrameworksOutputTypeDef = TypedDict(
     "ListFrameworksOutputTypeDef",
     {
         "Frameworks": List[FrameworkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLegalHoldsOutputTypeDef = TypedDict(
     "ListLegalHoldsOutputTypeDef",
     {
         "NextToken": str,
         "LegalHolds": List[LegalHoldTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupJobsInputListBackupJobsPaginateTypeDef = TypedDict(
-    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
-    {
-        "ByResourceArn": str,
-        "ByState": BackupJobStateType,
-        "ByBackupVaultName": str,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByResourceType": str,
-        "ByAccountId": str,
-        "ByCompleteAfter": Union[datetime, str],
-        "ByCompleteBefore": Union[datetime, str],
-        "ByParentJobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef = TypedDict(
-    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
-    {
-        "BackupPlanId": str,
-    },
-)
-_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef(
-    _RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
-    _OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListBackupPlansInputListBackupPlansPaginateTypeDef = TypedDict(
-    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
-    {
-        "IncludeDeleted": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
-    "_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
-    {
-        "BackupPlanId": str,
-    },
-)
-_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
-    "_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef(
-    _RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
-    _OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
-):
-    pass
-
-
-ListBackupVaultsInputListBackupVaultsPaginateTypeDef = TypedDict(
-    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCopyJobsInputListCopyJobsPaginateTypeDef = TypedDict(
-    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
-    {
-        "ByResourceArn": str,
-        "ByState": CopyJobStateType,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByResourceType": str,
-        "ByDestinationVaultArn": str,
-        "ByAccountId": str,
-        "ByCompleteBefore": Union[datetime, str],
-        "ByCompleteAfter": Union[datetime, str],
-        "ByParentJobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListLegalHoldsInputListLegalHoldsPaginateTypeDef = TypedDict(
-    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef = TypedDict(
-    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
-    "_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
-    {
-        "BackupVaultName": str,
-    },
-)
-_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
-    "_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
-    {
-        "ByResourceArn": str,
-        "ByResourceType": str,
-        "ByBackupPlanId": str,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByParentRecoveryPointArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef(
-    _RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
-    _OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
-    "_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
-    {
-        "LegalHoldId": str,
-    },
-)
-_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
-    "_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef(
-    _RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
-    _OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
-    "_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
-    "_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef(
-    _RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
-    _OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
-):
-    pass
-
-
-ListRestoreJobsInputListRestoreJobsPaginateTypeDef = TypedDict(
-    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
-    {
-        "ByAccountId": str,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByStatus": RestoreJobStatusType,
-        "ByCompleteBefore": Union[datetime, str],
-        "ByCompleteAfter": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListProtectedResourcesOutputTypeDef = TypedDict(
     "ListProtectedResourcesOutputTypeDef",
     {
         "Results": List[ProtectedResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryPointsByLegalHoldOutputTypeDef = TypedDict(
     "ListRecoveryPointsByLegalHoldOutputTypeDef",
     {
         "RecoveryPoints": List[RecoveryPointMemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryPointsByResourceOutputTypeDef = TypedDict(
     "ListRecoveryPointsByResourceOutputTypeDef",
     {
         "NextToken": str,
         "RecoveryPoints": List[RecoveryPointByResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRestoreJobsOutputTypeDef = TypedDict(
     "ListRestoreJobsOutputTypeDef",
     {
         "RestoreJobs": List[RestoreJobsListMemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReportJobTypeDef = TypedDict(
     "ReportJobTypeDef",
     {
         "ReportJobId": str,
@@ -2115,50 +2119,50 @@
 )
 
 ListBackupPlanVersionsOutputTypeDef = TypedDict(
     "ListBackupPlanVersionsOutputTypeDef",
     {
         "NextToken": str,
         "BackupPlanVersionsList": List[BackupPlansListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupPlansOutputTypeDef = TypedDict(
     "ListBackupPlansOutputTypeDef",
     {
         "NextToken": str,
         "BackupPlansList": List[BackupPlansListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupJobsOutputTypeDef = TypedDict(
     "ListBackupJobsOutputTypeDef",
     {
         "BackupJobs": List[BackupJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCopyJobOutputTypeDef = TypedDict(
     "DescribeCopyJobOutputTypeDef",
     {
         "CopyJob": CopyJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCopyJobsOutputTypeDef = TypedDict(
     "ListCopyJobsOutputTypeDef",
     {
         "CopyJobs": List[CopyJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBackupRuleInputTypeDef = TypedDict(
     "_RequiredBackupRuleInputTypeDef",
     {
         "RuleName": str,
@@ -2212,15 +2216,15 @@
 
 
 ListRecoveryPointsByBackupVaultOutputTypeDef = TypedDict(
     "ListRecoveryPointsByBackupVaultOutputTypeDef",
     {
         "NextToken": str,
         "RecoveryPoints": List[RecoveryPointByBackupVaultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBackupSelectionTypeDef = TypedDict(
     "_RequiredBackupSelectionTypeDef",
     {
         "SelectionName": str,
@@ -2274,15 +2278,15 @@
         "FrameworkArn": str,
         "FrameworkDescription": str,
         "FrameworkControls": List[FrameworkControlTypeDef],
         "CreationTime": datetime,
         "DeploymentStatus": str,
         "FrameworkStatus": str,
         "IdempotencyToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFrameworkInputRequestTypeDef = TypedDict(
     "_RequiredUpdateFrameworkInputRequestTypeDef",
     {
         "FrameworkName": str,
@@ -2305,24 +2309,24 @@
     pass
 
 
 DescribeReportPlanOutputTypeDef = TypedDict(
     "DescribeReportPlanOutputTypeDef",
     {
         "ReportPlan": ReportPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReportPlansOutputTypeDef = TypedDict(
     "ListReportPlansOutputTypeDef",
     {
         "ReportPlans": List[ReportPlanTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLegalHoldInputRequestTypeDef = TypedDict(
     "_RequiredCreateLegalHoldInputRequestTypeDef",
     {
         "Title": str,
@@ -2352,15 +2356,15 @@
         "Title": str,
         "Status": LegalHoldStatusType,
         "Description": str,
         "LegalHoldId": str,
         "LegalHoldArn": str,
         "CreationDate": datetime,
         "RecoveryPointSelection": RecoveryPointSelectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLegalHoldOutputTypeDef = TypedDict(
     "GetLegalHoldOutputTypeDef",
     {
         "Title": str,
@@ -2369,32 +2373,32 @@
         "CancelDescription": str,
         "LegalHoldId": str,
         "LegalHoldArn": str,
         "CreationDate": datetime,
         "CancellationDate": datetime,
         "RetainRecordUntil": datetime,
         "RecoveryPointSelection": RecoveryPointSelectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReportJobOutputTypeDef = TypedDict(
     "DescribeReportJobOutputTypeDef",
     {
         "ReportJob": ReportJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReportJobsOutputTypeDef = TypedDict(
     "ListReportJobsOutputTypeDef",
     {
         "ReportJobs": List[ReportJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBackupPlanInputTypeDef = TypedDict(
     "_RequiredBackupPlanInputTypeDef",
     {
         "BackupPlanName": str,
@@ -2461,15 +2465,15 @@
     "GetBackupSelectionOutputTypeDef",
     {
         "BackupSelection": BackupSelectionTypeDef,
         "SelectionId": str,
         "BackupPlanId": str,
         "CreationDate": datetime,
         "CreatorRequestId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBackupPlanInputRequestTypeDef = TypedDict(
     "_RequiredCreateBackupPlanInputRequestTypeDef",
     {
         "BackupPlan": BackupPlanInputTypeDef,
@@ -2499,23 +2503,23 @@
     },
 )
 
 GetBackupPlanFromJSONOutputTypeDef = TypedDict(
     "GetBackupPlanFromJSONOutputTypeDef",
     {
         "BackupPlan": BackupPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBackupPlanFromTemplateOutputTypeDef = TypedDict(
     "GetBackupPlanFromTemplateOutputTypeDef",
     {
         "BackupPlanDocument": BackupPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBackupPlanOutputTypeDef = TypedDict(
     "GetBackupPlanOutputTypeDef",
     {
         "BackupPlan": BackupPlanTypeDef,
@@ -2523,10 +2527,10 @@
         "BackupPlanArn": str,
         "VersionId": str,
         "CreatorRequestId": str,
         "CreationDate": datetime,
         "DeletionDate": datetime,
         "LastExecutionDate": datetime,
         "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup/type_defs.pyi` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -43,143 +43,143 @@
     "BackupSelectionsListMemberTypeDef",
     "BackupVaultListMemberTypeDef",
     "CalculatedLifecycleTypeDef",
     "CancelLegalHoldInputRequestTypeDef",
     "ConditionParameterTypeDef",
     "ControlInputParameterTypeDef",
     "ControlScopeTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBackupSelectionOutputTypeDef",
     "CreateBackupVaultInputRequestTypeDef",
+    "CreateBackupVaultOutputTypeDef",
+    "CreateFrameworkOutputTypeDef",
     "ReportDeliveryChannelTypeDef",
     "ReportSettingTypeDef",
+    "CreateReportPlanOutputTypeDef",
     "DateRangeTypeDef",
     "DeleteBackupPlanInputRequestTypeDef",
+    "DeleteBackupPlanOutputTypeDef",
     "DeleteBackupSelectionInputRequestTypeDef",
     "DeleteBackupVaultAccessPolicyInputRequestTypeDef",
     "DeleteBackupVaultInputRequestTypeDef",
     "DeleteBackupVaultLockConfigurationInputRequestTypeDef",
     "DeleteBackupVaultNotificationsInputRequestTypeDef",
     "DeleteFrameworkInputRequestTypeDef",
     "DeleteRecoveryPointInputRequestTypeDef",
     "DeleteReportPlanInputRequestTypeDef",
     "DescribeBackupJobInputRequestTypeDef",
     "DescribeBackupVaultInputRequestTypeDef",
+    "DescribeBackupVaultOutputTypeDef",
     "DescribeCopyJobInputRequestTypeDef",
     "DescribeFrameworkInputRequestTypeDef",
+    "DescribeGlobalSettingsOutputTypeDef",
     "DescribeProtectedResourceInputRequestTypeDef",
+    "DescribeProtectedResourceOutputTypeDef",
     "DescribeRecoveryPointInputRequestTypeDef",
+    "DescribeRegionSettingsOutputTypeDef",
     "DescribeReportJobInputRequestTypeDef",
     "DescribeReportPlanInputRequestTypeDef",
     "DescribeRestoreJobInputRequestTypeDef",
+    "DescribeRestoreJobOutputTypeDef",
     "DisassociateRecoveryPointFromParentInputRequestTypeDef",
     "DisassociateRecoveryPointInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportBackupPlanTemplateInputRequestTypeDef",
+    "ExportBackupPlanTemplateOutputTypeDef",
     "FrameworkTypeDef",
     "GetBackupPlanFromJSONInputRequestTypeDef",
     "GetBackupPlanFromTemplateInputRequestTypeDef",
     "GetBackupPlanInputRequestTypeDef",
     "GetBackupSelectionInputRequestTypeDef",
     "GetBackupVaultAccessPolicyInputRequestTypeDef",
+    "GetBackupVaultAccessPolicyOutputTypeDef",
     "GetBackupVaultNotificationsInputRequestTypeDef",
+    "GetBackupVaultNotificationsOutputTypeDef",
     "GetLegalHoldInputRequestTypeDef",
     "GetRecoveryPointRestoreMetadataInputRequestTypeDef",
+    "GetRecoveryPointRestoreMetadataOutputTypeDef",
+    "GetSupportedResourceTypesOutputTypeDef",
     "LegalHoldTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
     "ListBackupJobsInputRequestTypeDef",
+    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
     "ListBackupPlanTemplatesInputRequestTypeDef",
+    "ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
     "ListBackupPlanVersionsInputRequestTypeDef",
+    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
     "ListBackupPlansInputRequestTypeDef",
+    "ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
     "ListBackupSelectionsInputRequestTypeDef",
+    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
     "ListBackupVaultsInputRequestTypeDef",
+    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
     "ListCopyJobsInputRequestTypeDef",
     "ListFrameworksInputRequestTypeDef",
+    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
     "ListLegalHoldsInputRequestTypeDef",
+    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
     "ListProtectedResourcesInputRequestTypeDef",
     "ProtectedResourceTypeDef",
+    "ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
     "ListRecoveryPointsByBackupVaultInputRequestTypeDef",
+    "ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
     "ListRecoveryPointsByLegalHoldInputRequestTypeDef",
     "RecoveryPointMemberTypeDef",
+    "ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
     "ListRecoveryPointsByResourceInputRequestTypeDef",
     "RecoveryPointByResourceTypeDef",
     "ListReportJobsInputRequestTypeDef",
     "ListReportPlansInputRequestTypeDef",
+    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
     "ListRestoreJobsInputRequestTypeDef",
     "RestoreJobsListMemberTypeDef",
     "ListTagsInputRequestTypeDef",
+    "ListTagsOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "PutBackupVaultAccessPolicyInputRequestTypeDef",
     "PutBackupVaultLockConfigurationInputRequestTypeDef",
     "PutBackupVaultNotificationsInputRequestTypeDef",
     "ReportDestinationTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartBackupJobOutputTypeDef",
+    "StartCopyJobOutputTypeDef",
     "StartReportJobInputRequestTypeDef",
+    "StartReportJobOutputTypeDef",
     "StartRestoreJobInputRequestTypeDef",
+    "StartRestoreJobOutputTypeDef",
     "StopBackupJobInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "UpdateFrameworkOutputTypeDef",
     "UpdateGlobalSettingsInputRequestTypeDef",
     "UpdateRegionSettingsInputRequestTypeDef",
+    "UpdateReportPlanOutputTypeDef",
     "BackupPlansListMemberTypeDef",
+    "CreateBackupPlanOutputTypeDef",
+    "UpdateBackupPlanOutputTypeDef",
     "BackupJobTypeDef",
     "CopyJobTypeDef",
+    "DescribeBackupJobOutputTypeDef",
+    "ListBackupPlanTemplatesOutputTypeDef",
     "CopyActionTypeDef",
     "StartBackupJobInputRequestTypeDef",
     "StartCopyJobInputRequestTypeDef",
     "UpdateRecoveryPointLifecycleInputRequestTypeDef",
-    "RecoveryPointByBackupVaultTypeDef",
-    "ConditionsTypeDef",
-    "FrameworkControlTypeDef",
-    "CreateBackupPlanOutputTypeDef",
-    "CreateBackupSelectionOutputTypeDef",
-    "CreateBackupVaultOutputTypeDef",
-    "CreateFrameworkOutputTypeDef",
-    "CreateReportPlanOutputTypeDef",
-    "DeleteBackupPlanOutputTypeDef",
-    "DescribeBackupJobOutputTypeDef",
-    "DescribeBackupVaultOutputTypeDef",
-    "DescribeGlobalSettingsOutputTypeDef",
-    "DescribeProtectedResourceOutputTypeDef",
-    "DescribeRecoveryPointOutputTypeDef",
-    "DescribeRegionSettingsOutputTypeDef",
-    "DescribeRestoreJobOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportBackupPlanTemplateOutputTypeDef",
-    "GetBackupVaultAccessPolicyOutputTypeDef",
-    "GetBackupVaultNotificationsOutputTypeDef",
-    "GetRecoveryPointRestoreMetadataOutputTypeDef",
-    "GetSupportedResourceTypesOutputTypeDef",
-    "ListBackupPlanTemplatesOutputTypeDef",
     "ListBackupSelectionsOutputTypeDef",
     "ListBackupVaultsOutputTypeDef",
-    "ListTagsOutputTypeDef",
-    "StartBackupJobOutputTypeDef",
-    "StartCopyJobOutputTypeDef",
-    "StartReportJobOutputTypeDef",
-    "StartRestoreJobOutputTypeDef",
-    "UpdateBackupPlanOutputTypeDef",
-    "UpdateFrameworkOutputTypeDef",
+    "DescribeRecoveryPointOutputTypeDef",
+    "RecoveryPointByBackupVaultTypeDef",
     "UpdateRecoveryPointLifecycleOutputTypeDef",
-    "UpdateReportPlanOutputTypeDef",
+    "ConditionsTypeDef",
+    "FrameworkControlTypeDef",
     "CreateReportPlanInputRequestTypeDef",
     "ReportPlanTypeDef",
     "UpdateReportPlanInputRequestTypeDef",
     "RecoveryPointSelectionTypeDef",
     "ListFrameworksOutputTypeDef",
     "ListLegalHoldsOutputTypeDef",
-    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
-    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
-    "ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
-    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
-    "ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
-    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
-    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
-    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
-    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
-    "ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
-    "ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
-    "ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
-    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
     "ListProtectedResourcesOutputTypeDef",
     "ListRecoveryPointsByLegalHoldOutputTypeDef",
     "ListRecoveryPointsByResourceOutputTypeDef",
     "ListRestoreJobsOutputTypeDef",
     "ReportJobTypeDef",
     "ListBackupPlanVersionsOutputTypeDef",
     "ListBackupPlansOutputTypeDef",
@@ -341,22 +341,21 @@
         "ComplianceResourceIds": Sequence[str],
         "ComplianceResourceTypes": Sequence[str],
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBackupSelectionOutputTypeDef = TypedDict(
+    "CreateBackupSelectionOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "SelectionId": str,
+        "BackupPlanId": str,
+        "CreationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBackupVaultInputRequestTypeDef = TypedDict(
     "_RequiredCreateBackupVaultInputRequestTypeDef",
     {
         "BackupVaultName": str,
@@ -373,14 +372,33 @@
 )
 
 class CreateBackupVaultInputRequestTypeDef(
     _RequiredCreateBackupVaultInputRequestTypeDef, _OptionalCreateBackupVaultInputRequestTypeDef
 ):
     pass
 
+CreateBackupVaultOutputTypeDef = TypedDict(
+    "CreateBackupVaultOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "CreationDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFrameworkOutputTypeDef = TypedDict(
+    "CreateFrameworkOutputTypeDef",
+    {
+        "FrameworkName": str,
+        "FrameworkArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredReportDeliveryChannelTypeDef = TypedDict(
     "_RequiredReportDeliveryChannelTypeDef",
     {
         "S3BucketName": str,
     },
 )
 _OptionalReportDeliveryChannelTypeDef = TypedDict(
@@ -414,14 +432,24 @@
     },
     total=False,
 )
 
 class ReportSettingTypeDef(_RequiredReportSettingTypeDef, _OptionalReportSettingTypeDef):
     pass
 
+CreateReportPlanOutputTypeDef = TypedDict(
+    "CreateReportPlanOutputTypeDef",
+    {
+        "ReportPlanName": str,
+        "ReportPlanArn": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DateRangeTypeDef = TypedDict(
     "DateRangeTypeDef",
     {
         "FromDate": Union[datetime, str],
         "ToDate": Union[datetime, str],
     },
 )
@@ -429,14 +457,25 @@
 DeleteBackupPlanInputRequestTypeDef = TypedDict(
     "DeleteBackupPlanInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 
+DeleteBackupPlanOutputTypeDef = TypedDict(
+    "DeleteBackupPlanOutputTypeDef",
+    {
+        "BackupPlanId": str,
+        "BackupPlanArn": str,
+        "DeletionDate": datetime,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteBackupSelectionInputRequestTypeDef = TypedDict(
     "DeleteBackupSelectionInputRequestTypeDef",
     {
         "BackupPlanId": str,
         "SelectionId": str,
     },
 )
@@ -501,43 +540,89 @@
 DescribeBackupVaultInputRequestTypeDef = TypedDict(
     "DescribeBackupVaultInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 
+DescribeBackupVaultOutputTypeDef = TypedDict(
+    "DescribeBackupVaultOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "EncryptionKeyArn": str,
+        "CreationDate": datetime,
+        "CreatorRequestId": str,
+        "NumberOfRecoveryPoints": int,
+        "Locked": bool,
+        "MinRetentionDays": int,
+        "MaxRetentionDays": int,
+        "LockDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeCopyJobInputRequestTypeDef = TypedDict(
     "DescribeCopyJobInputRequestTypeDef",
     {
         "CopyJobId": str,
     },
 )
 
 DescribeFrameworkInputRequestTypeDef = TypedDict(
     "DescribeFrameworkInputRequestTypeDef",
     {
         "FrameworkName": str,
     },
 )
 
+DescribeGlobalSettingsOutputTypeDef = TypedDict(
+    "DescribeGlobalSettingsOutputTypeDef",
+    {
+        "GlobalSettings": Dict[str, str],
+        "LastUpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeProtectedResourceInputRequestTypeDef = TypedDict(
     "DescribeProtectedResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+DescribeProtectedResourceOutputTypeDef = TypedDict(
+    "DescribeProtectedResourceOutputTypeDef",
+    {
+        "ResourceArn": str,
+        "ResourceType": str,
+        "LastBackupTime": datetime,
+        "ResourceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeRecoveryPointInputRequestTypeDef = TypedDict(
     "DescribeRecoveryPointInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
 
+DescribeRegionSettingsOutputTypeDef = TypedDict(
+    "DescribeRegionSettingsOutputTypeDef",
+    {
+        "ResourceTypeOptInPreference": Dict[str, bool],
+        "ResourceTypeManagementPreference": Dict[str, bool],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeReportJobInputRequestTypeDef = TypedDict(
     "DescribeReportJobInputRequestTypeDef",
     {
         "ReportJobId": str,
     },
 )
 
@@ -551,14 +636,34 @@
 DescribeRestoreJobInputRequestTypeDef = TypedDict(
     "DescribeRestoreJobInputRequestTypeDef",
     {
         "RestoreJobId": str,
     },
 )
 
+DescribeRestoreJobOutputTypeDef = TypedDict(
+    "DescribeRestoreJobOutputTypeDef",
+    {
+        "AccountId": str,
+        "RestoreJobId": str,
+        "RecoveryPointArn": str,
+        "CreationDate": datetime,
+        "CompletionDate": datetime,
+        "Status": RestoreJobStatusType,
+        "StatusMessage": str,
+        "PercentDone": str,
+        "BackupSizeInBytes": int,
+        "IamRoleArn": str,
+        "ExpectedCompletionTimeMinutes": int,
+        "CreatedResourceArn": str,
+        "ResourceType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateRecoveryPointFromParentInputRequestTypeDef = TypedDict(
     "DisassociateRecoveryPointFromParentInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
@@ -567,21 +672,36 @@
     "DisassociateRecoveryPointInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportBackupPlanTemplateInputRequestTypeDef = TypedDict(
     "ExportBackupPlanTemplateInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 
+ExportBackupPlanTemplateOutputTypeDef = TypedDict(
+    "ExportBackupPlanTemplateOutputTypeDef",
+    {
+        "BackupPlanTemplateJson": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FrameworkTypeDef = TypedDict(
     "FrameworkTypeDef",
     {
         "FrameworkName": str,
         "FrameworkArn": str,
         "FrameworkDescription": str,
         "NumberOfControls": int,
@@ -635,21 +755,42 @@
 GetBackupVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "GetBackupVaultAccessPolicyInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 
+GetBackupVaultAccessPolicyOutputTypeDef = TypedDict(
+    "GetBackupVaultAccessPolicyOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBackupVaultNotificationsInputRequestTypeDef = TypedDict(
     "GetBackupVaultNotificationsInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 
+GetBackupVaultNotificationsOutputTypeDef = TypedDict(
+    "GetBackupVaultNotificationsOutputTypeDef",
+    {
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "SNSTopicArn": str,
+        "BackupVaultEvents": List[BackupVaultEventType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLegalHoldInputRequestTypeDef = TypedDict(
     "GetLegalHoldInputRequestTypeDef",
     {
         "LegalHoldId": str,
     },
 )
 
@@ -657,34 +798,60 @@
     "GetRecoveryPointRestoreMetadataInputRequestTypeDef",
     {
         "BackupVaultName": str,
         "RecoveryPointArn": str,
     },
 )
 
+GetRecoveryPointRestoreMetadataOutputTypeDef = TypedDict(
+    "GetRecoveryPointRestoreMetadataOutputTypeDef",
+    {
+        "BackupVaultArn": str,
+        "RecoveryPointArn": str,
+        "RestoreMetadata": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSupportedResourceTypesOutputTypeDef = TypedDict(
+    "GetSupportedResourceTypesOutputTypeDef",
+    {
+        "ResourceTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LegalHoldTypeDef = TypedDict(
     "LegalHoldTypeDef",
     {
         "Title": str,
         "Status": LegalHoldStatusType,
         "Description": str,
         "LegalHoldId": str,
         "LegalHoldArn": str,
         "CreationDate": datetime,
         "CancellationDate": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListBackupJobsInputListBackupJobsPaginateTypeDef = TypedDict(
+    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ByResourceArn": str,
+        "ByState": BackupJobStateType,
+        "ByBackupVaultName": str,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByResourceType": str,
+        "ByAccountId": str,
+        "ByCompleteAfter": Union[datetime, str],
+        "ByCompleteBefore": Union[datetime, str],
+        "ByParentJobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBackupJobsInputRequestTypeDef = TypedDict(
     "ListBackupJobsInputRequestTypeDef",
     {
@@ -700,23 +867,51 @@
         "ByCompleteAfter": Union[datetime, str],
         "ByCompleteBefore": Union[datetime, str],
         "ByParentJobId": str,
     },
     total=False,
 )
 
+ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef = TypedDict(
+    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBackupPlanTemplatesInputRequestTypeDef = TypedDict(
     "ListBackupPlanTemplatesInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
+    {
+        "BackupPlanId": str,
+    },
+)
+_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef(
+    _RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
+    _OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListBackupPlanVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListBackupPlanVersionsInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 _OptionalListBackupPlanVersionsInputRequestTypeDef = TypedDict(
@@ -730,24 +925,53 @@
 
 class ListBackupPlanVersionsInputRequestTypeDef(
     _RequiredListBackupPlanVersionsInputRequestTypeDef,
     _OptionalListBackupPlanVersionsInputRequestTypeDef,
 ):
     pass
 
+ListBackupPlansInputListBackupPlansPaginateTypeDef = TypedDict(
+    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
+    {
+        "IncludeDeleted": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBackupPlansInputRequestTypeDef = TypedDict(
     "ListBackupPlansInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "IncludeDeleted": bool,
     },
     total=False,
 )
 
+_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
+    "_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
+    {
+        "BackupPlanId": str,
+    },
+)
+_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
+    "_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef(
+    _RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
+    _OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListBackupSelectionsInputRequestTypeDef = TypedDict(
     "_RequiredListBackupSelectionsInputRequestTypeDef",
     {
         "BackupPlanId": str,
     },
 )
 _OptionalListBackupSelectionsInputRequestTypeDef = TypedDict(
@@ -761,23 +985,49 @@
 
 class ListBackupSelectionsInputRequestTypeDef(
     _RequiredListBackupSelectionsInputRequestTypeDef,
     _OptionalListBackupSelectionsInputRequestTypeDef,
 ):
     pass
 
+ListBackupVaultsInputListBackupVaultsPaginateTypeDef = TypedDict(
+    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBackupVaultsInputRequestTypeDef = TypedDict(
     "ListBackupVaultsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListCopyJobsInputListCopyJobsPaginateTypeDef = TypedDict(
+    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
+    {
+        "ByResourceArn": str,
+        "ByState": CopyJobStateType,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByResourceType": str,
+        "ByDestinationVaultArn": str,
+        "ByAccountId": str,
+        "ByCompleteBefore": Union[datetime, str],
+        "ByCompleteAfter": Union[datetime, str],
+        "ByParentJobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCopyJobsInputRequestTypeDef = TypedDict(
     "ListCopyJobsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ByResourceArn": str,
         "ByState": CopyJobStateType,
@@ -798,23 +1048,39 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListLegalHoldsInputListLegalHoldsPaginateTypeDef = TypedDict(
+    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLegalHoldsInputRequestTypeDef = TypedDict(
     "ListLegalHoldsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef = TypedDict(
+    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProtectedResourcesInputRequestTypeDef = TypedDict(
     "ListProtectedResourcesInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -827,14 +1093,40 @@
         "ResourceType": str,
         "LastBackupTime": datetime,
         "ResourceName": str,
     },
     total=False,
 )
 
+_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
+    "_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
+    {
+        "BackupVaultName": str,
+    },
+)
+_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
+    "_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
+    {
+        "ByResourceArn": str,
+        "ByResourceType": str,
+        "ByBackupPlanId": str,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByParentRecoveryPointArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef(
+    _RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
+    _OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
+):
+    pass
+
 _RequiredListRecoveryPointsByBackupVaultInputRequestTypeDef = TypedDict(
     "_RequiredListRecoveryPointsByBackupVaultInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 _OptionalListRecoveryPointsByBackupVaultInputRequestTypeDef = TypedDict(
@@ -854,14 +1146,34 @@
 
 class ListRecoveryPointsByBackupVaultInputRequestTypeDef(
     _RequiredListRecoveryPointsByBackupVaultInputRequestTypeDef,
     _OptionalListRecoveryPointsByBackupVaultInputRequestTypeDef,
 ):
     pass
 
+_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
+    "_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
+    {
+        "LegalHoldId": str,
+    },
+)
+_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
+    "_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef(
+    _RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
+    _OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
+):
+    pass
+
 _RequiredListRecoveryPointsByLegalHoldInputRequestTypeDef = TypedDict(
     "_RequiredListRecoveryPointsByLegalHoldInputRequestTypeDef",
     {
         "LegalHoldId": str,
     },
 )
 _OptionalListRecoveryPointsByLegalHoldInputRequestTypeDef = TypedDict(
@@ -879,18 +1191,41 @@
 ):
     pass
 
 RecoveryPointMemberTypeDef = TypedDict(
     "RecoveryPointMemberTypeDef",
     {
         "RecoveryPointArn": str,
+        "ResourceArn": str,
+        "ResourceType": str,
+        "BackupVaultName": str,
     },
     total=False,
 )
 
+_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
+    "_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
+    "_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef(
+    _RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
+    _OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListRecoveryPointsByResourceInputRequestTypeDef = TypedDict(
     "_RequiredListRecoveryPointsByResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListRecoveryPointsByResourceInputRequestTypeDef = TypedDict(
@@ -943,14 +1278,28 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListRestoreJobsInputListRestoreJobsPaginateTypeDef = TypedDict(
+    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
+    {
+        "ByAccountId": str,
+        "ByCreatedBefore": Union[datetime, str],
+        "ByCreatedAfter": Union[datetime, str],
+        "ByStatus": RestoreJobStatusType,
+        "ByCompleteBefore": Union[datetime, str],
+        "ByCompleteAfter": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRestoreJobsInputRequestTypeDef = TypedDict(
     "ListRestoreJobsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ByAccountId": str,
         "ByCreatedBefore": Union[datetime, str],
@@ -998,14 +1347,33 @@
 )
 
 class ListTagsInputRequestTypeDef(
     _RequiredListTagsInputRequestTypeDef, _OptionalListTagsInputRequestTypeDef
 ):
     pass
 
+ListTagsOutputTypeDef = TypedDict(
+    "ListTagsOutputTypeDef",
+    {
+        "NextToken": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
 _RequiredPutBackupVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredPutBackupVaultAccessPolicyInputRequestTypeDef",
     {
         "BackupVaultName": str,
     },
 )
 _OptionalPutBackupVaultAccessPolicyInputRequestTypeDef = TypedDict(
@@ -1058,14 +1426,46 @@
     {
         "S3BucketName": str,
         "S3Keys": List[str],
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
+StartBackupJobOutputTypeDef = TypedDict(
+    "StartBackupJobOutputTypeDef",
+    {
+        "BackupJobId": str,
+        "RecoveryPointArn": str,
+        "CreationDate": datetime,
+        "IsParent": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartCopyJobOutputTypeDef = TypedDict(
+    "StartCopyJobOutputTypeDef",
+    {
+        "CopyJobId": str,
+        "CreationDate": datetime,
+        "IsParent": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartReportJobInputRequestTypeDef = TypedDict(
     "_RequiredStartReportJobInputRequestTypeDef",
     {
         "ReportPlanName": str,
     },
 )
 _OptionalStartReportJobInputRequestTypeDef = TypedDict(
@@ -1077,36 +1477,53 @@
 )
 
 class StartReportJobInputRequestTypeDef(
     _RequiredStartReportJobInputRequestTypeDef, _OptionalStartReportJobInputRequestTypeDef
 ):
     pass
 
+StartReportJobOutputTypeDef = TypedDict(
+    "StartReportJobOutputTypeDef",
+    {
+        "ReportJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartRestoreJobInputRequestTypeDef = TypedDict(
     "_RequiredStartRestoreJobInputRequestTypeDef",
     {
         "RecoveryPointArn": str,
         "Metadata": Mapping[str, str],
     },
 )
 _OptionalStartRestoreJobInputRequestTypeDef = TypedDict(
     "_OptionalStartRestoreJobInputRequestTypeDef",
     {
         "IamRoleArn": str,
         "IdempotencyToken": str,
         "ResourceType": str,
+        "CopySourceTagsToRestoredResource": bool,
     },
     total=False,
 )
 
 class StartRestoreJobInputRequestTypeDef(
     _RequiredStartRestoreJobInputRequestTypeDef, _OptionalStartRestoreJobInputRequestTypeDef
 ):
     pass
 
+StartRestoreJobOutputTypeDef = TypedDict(
+    "StartRestoreJobOutputTypeDef",
+    {
+        "RestoreJobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopBackupJobInputRequestTypeDef = TypedDict(
     "StopBackupJobInputRequestTypeDef",
     {
         "BackupJobId": str,
     },
 )
 
@@ -1122,14 +1539,24 @@
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeyList": Sequence[str],
     },
 )
 
+UpdateFrameworkOutputTypeDef = TypedDict(
+    "UpdateFrameworkOutputTypeDef",
+    {
+        "FrameworkName": str,
+        "FrameworkArn": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateGlobalSettingsInputRequestTypeDef = TypedDict(
     "UpdateGlobalSettingsInputRequestTypeDef",
     {
         "GlobalSettings": Mapping[str, str],
     },
     total=False,
 )
@@ -1139,14 +1566,24 @@
     {
         "ResourceTypeOptInPreference": Mapping[str, bool],
         "ResourceTypeManagementPreference": Mapping[str, bool],
     },
     total=False,
 )
 
+UpdateReportPlanOutputTypeDef = TypedDict(
+    "UpdateReportPlanOutputTypeDef",
+    {
+        "ReportPlanName": str,
+        "ReportPlanArn": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BackupPlansListMemberTypeDef = TypedDict(
     "BackupPlansListMemberTypeDef",
     {
         "BackupPlanArn": str,
         "BackupPlanId": str,
         "CreationDate": datetime,
         "DeletionDate": datetime,
@@ -1155,14 +1592,38 @@
         "CreatorRequestId": str,
         "LastExecutionDate": datetime,
         "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
     },
     total=False,
 )
 
+CreateBackupPlanOutputTypeDef = TypedDict(
+    "CreateBackupPlanOutputTypeDef",
+    {
+        "BackupPlanId": str,
+        "BackupPlanArn": str,
+        "CreationDate": datetime,
+        "VersionId": str,
+        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateBackupPlanOutputTypeDef = TypedDict(
+    "UpdateBackupPlanOutputTypeDef",
+    {
+        "BackupPlanId": str,
+        "BackupPlanArn": str,
+        "CreationDate": datetime,
+        "VersionId": str,
+        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BackupJobTypeDef = TypedDict(
     "BackupJobTypeDef",
     {
         "AccountId": str,
         "BackupJobId": str,
         "BackupVaultName": str,
         "BackupVaultArn": str,
@@ -1213,14 +1674,55 @@
         "NumberOfChildJobs": int,
         "ChildJobsInState": Dict[CopyJobStateType, int],
         "ResourceName": str,
     },
     total=False,
 )
 
+DescribeBackupJobOutputTypeDef = TypedDict(
+    "DescribeBackupJobOutputTypeDef",
+    {
+        "AccountId": str,
+        "BackupJobId": str,
+        "BackupVaultName": str,
+        "BackupVaultArn": str,
+        "RecoveryPointArn": str,
+        "ResourceArn": str,
+        "CreationDate": datetime,
+        "CompletionDate": datetime,
+        "State": BackupJobStateType,
+        "StatusMessage": str,
+        "PercentDone": str,
+        "BackupSizeInBytes": int,
+        "IamRoleArn": str,
+        "CreatedBy": RecoveryPointCreatorTypeDef,
+        "ResourceType": str,
+        "BytesTransferred": int,
+        "ExpectedCompletionDate": datetime,
+        "StartBy": datetime,
+        "BackupOptions": Dict[str, str],
+        "BackupType": str,
+        "ParentJobId": str,
+        "IsParent": bool,
+        "NumberOfChildJobs": int,
+        "ChildJobsInState": Dict[BackupJobStateType, int],
+        "ResourceName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBackupPlanTemplatesOutputTypeDef = TypedDict(
+    "ListBackupPlanTemplatesOutputTypeDef",
+    {
+        "NextToken": str,
+        "BackupPlanTemplatesList": List[BackupPlanTemplatesListMemberTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCopyActionTypeDef = TypedDict(
     "_RequiredCopyActionTypeDef",
     {
         "DestinationBackupVaultArn": str,
     },
 )
 _OptionalCopyActionTypeDef = TypedDict(
@@ -1300,16 +1802,34 @@
 
 class UpdateRecoveryPointLifecycleInputRequestTypeDef(
     _RequiredUpdateRecoveryPointLifecycleInputRequestTypeDef,
     _OptionalUpdateRecoveryPointLifecycleInputRequestTypeDef,
 ):
     pass
 
-RecoveryPointByBackupVaultTypeDef = TypedDict(
-    "RecoveryPointByBackupVaultTypeDef",
+ListBackupSelectionsOutputTypeDef = TypedDict(
+    "ListBackupSelectionsOutputTypeDef",
+    {
+        "NextToken": str,
+        "BackupSelectionsList": List[BackupSelectionsListMemberTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBackupVaultsOutputTypeDef = TypedDict(
+    "ListBackupVaultsOutputTypeDef",
+    {
+        "BackupVaultList": List[BackupVaultListMemberTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeRecoveryPointOutputTypeDef = TypedDict(
+    "DescribeRecoveryPointOutputTypeDef",
     {
         "RecoveryPointArn": str,
         "BackupVaultName": str,
         "BackupVaultArn": str,
         "SourceBackupVaultArn": str,
         "ResourceArn": str,
         "ResourceType": str,
@@ -1320,185 +1840,26 @@
         "CreationDate": datetime,
         "CompletionDate": datetime,
         "BackupSizeInBytes": int,
         "CalculatedLifecycle": CalculatedLifecycleTypeDef,
         "Lifecycle": LifecycleTypeDef,
         "EncryptionKeyArn": str,
         "IsEncrypted": bool,
+        "StorageClass": StorageClassType,
         "LastRestoreTime": datetime,
         "ParentRecoveryPointArn": str,
         "CompositeMemberIdentifier": str,
         "IsParent": bool,
         "ResourceName": str,
-    },
-    total=False,
-)
-
-ConditionsTypeDef = TypedDict(
-    "ConditionsTypeDef",
-    {
-        "StringEquals": Sequence[ConditionParameterTypeDef],
-        "StringNotEquals": Sequence[ConditionParameterTypeDef],
-        "StringLike": Sequence[ConditionParameterTypeDef],
-        "StringNotLike": Sequence[ConditionParameterTypeDef],
-    },
-    total=False,
-)
-
-_RequiredFrameworkControlTypeDef = TypedDict(
-    "_RequiredFrameworkControlTypeDef",
-    {
-        "ControlName": str,
-    },
-)
-_OptionalFrameworkControlTypeDef = TypedDict(
-    "_OptionalFrameworkControlTypeDef",
-    {
-        "ControlInputParameters": Sequence[ControlInputParameterTypeDef],
-        "ControlScope": ControlScopeTypeDef,
-    },
-    total=False,
-)
-
-class FrameworkControlTypeDef(_RequiredFrameworkControlTypeDef, _OptionalFrameworkControlTypeDef):
-    pass
-
-CreateBackupPlanOutputTypeDef = TypedDict(
-    "CreateBackupPlanOutputTypeDef",
-    {
-        "BackupPlanId": str,
-        "BackupPlanArn": str,
-        "CreationDate": datetime,
-        "VersionId": str,
-        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBackupSelectionOutputTypeDef = TypedDict(
-    "CreateBackupSelectionOutputTypeDef",
-    {
-        "SelectionId": str,
-        "BackupPlanId": str,
-        "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBackupVaultOutputTypeDef = TypedDict(
-    "CreateBackupVaultOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "CreationDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFrameworkOutputTypeDef = TypedDict(
-    "CreateFrameworkOutputTypeDef",
-    {
-        "FrameworkName": str,
-        "FrameworkArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateReportPlanOutputTypeDef = TypedDict(
-    "CreateReportPlanOutputTypeDef",
-    {
-        "ReportPlanName": str,
-        "ReportPlanArn": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBackupPlanOutputTypeDef = TypedDict(
-    "DeleteBackupPlanOutputTypeDef",
-    {
-        "BackupPlanId": str,
-        "BackupPlanArn": str,
-        "DeletionDate": datetime,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBackupJobOutputTypeDef = TypedDict(
-    "DescribeBackupJobOutputTypeDef",
-    {
-        "AccountId": str,
-        "BackupJobId": str,
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "RecoveryPointArn": str,
-        "ResourceArn": str,
-        "CreationDate": datetime,
-        "CompletionDate": datetime,
-        "State": BackupJobStateType,
-        "StatusMessage": str,
-        "PercentDone": str,
-        "BackupSizeInBytes": int,
-        "IamRoleArn": str,
-        "CreatedBy": RecoveryPointCreatorTypeDef,
-        "ResourceType": str,
-        "BytesTransferred": int,
-        "ExpectedCompletionDate": datetime,
-        "StartBy": datetime,
-        "BackupOptions": Dict[str, str],
-        "BackupType": str,
-        "ParentJobId": str,
-        "IsParent": bool,
-        "NumberOfChildJobs": int,
-        "ChildJobsInState": Dict[BackupJobStateType, int],
-        "ResourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBackupVaultOutputTypeDef = TypedDict(
-    "DescribeBackupVaultOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "EncryptionKeyArn": str,
-        "CreationDate": datetime,
-        "CreatorRequestId": str,
-        "NumberOfRecoveryPoints": int,
-        "Locked": bool,
-        "MinRetentionDays": int,
-        "MaxRetentionDays": int,
-        "LockDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGlobalSettingsOutputTypeDef = TypedDict(
-    "DescribeGlobalSettingsOutputTypeDef",
-    {
-        "GlobalSettings": Dict[str, str],
-        "LastUpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeProtectedResourceOutputTypeDef = TypedDict(
-    "DescribeProtectedResourceOutputTypeDef",
-    {
-        "ResourceArn": str,
-        "ResourceType": str,
-        "LastBackupTime": datetime,
-        "ResourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeRecoveryPointOutputTypeDef = TypedDict(
-    "DescribeRecoveryPointOutputTypeDef",
+RecoveryPointByBackupVaultTypeDef = TypedDict(
+    "RecoveryPointByBackupVaultTypeDef",
     {
         "RecoveryPointArn": str,
         "BackupVaultName": str,
         "BackupVaultArn": str,
         "SourceBackupVaultArn": str,
         "ResourceArn": str,
         "ResourceType": str,
@@ -1509,222 +1870,62 @@
         "CreationDate": datetime,
         "CompletionDate": datetime,
         "BackupSizeInBytes": int,
         "CalculatedLifecycle": CalculatedLifecycleTypeDef,
         "Lifecycle": LifecycleTypeDef,
         "EncryptionKeyArn": str,
         "IsEncrypted": bool,
-        "StorageClass": StorageClassType,
         "LastRestoreTime": datetime,
         "ParentRecoveryPointArn": str,
         "CompositeMemberIdentifier": str,
         "IsParent": bool,
         "ResourceName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRegionSettingsOutputTypeDef = TypedDict(
-    "DescribeRegionSettingsOutputTypeDef",
-    {
-        "ResourceTypeOptInPreference": Dict[str, bool],
-        "ResourceTypeManagementPreference": Dict[str, bool],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRestoreJobOutputTypeDef = TypedDict(
-    "DescribeRestoreJobOutputTypeDef",
-    {
-        "AccountId": str,
-        "RestoreJobId": str,
-        "RecoveryPointArn": str,
-        "CreationDate": datetime,
-        "CompletionDate": datetime,
-        "Status": RestoreJobStatusType,
-        "StatusMessage": str,
-        "PercentDone": str,
-        "BackupSizeInBytes": int,
-        "IamRoleArn": str,
-        "ExpectedCompletionTimeMinutes": int,
-        "CreatedResourceArn": str,
-        "ResourceType": str,
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
-ExportBackupPlanTemplateOutputTypeDef = TypedDict(
-    "ExportBackupPlanTemplateOutputTypeDef",
-    {
-        "BackupPlanTemplateJson": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBackupVaultAccessPolicyOutputTypeDef = TypedDict(
-    "GetBackupVaultAccessPolicyOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBackupVaultNotificationsOutputTypeDef = TypedDict(
-    "GetBackupVaultNotificationsOutputTypeDef",
-    {
-        "BackupVaultName": str,
-        "BackupVaultArn": str,
-        "SNSTopicArn": str,
-        "BackupVaultEvents": List[BackupVaultEventType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-GetRecoveryPointRestoreMetadataOutputTypeDef = TypedDict(
-    "GetRecoveryPointRestoreMetadataOutputTypeDef",
+UpdateRecoveryPointLifecycleOutputTypeDef = TypedDict(
+    "UpdateRecoveryPointLifecycleOutputTypeDef",
     {
         "BackupVaultArn": str,
         "RecoveryPointArn": str,
-        "RestoreMetadata": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSupportedResourceTypesOutputTypeDef = TypedDict(
-    "GetSupportedResourceTypesOutputTypeDef",
-    {
-        "ResourceTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupPlanTemplatesOutputTypeDef = TypedDict(
-    "ListBackupPlanTemplatesOutputTypeDef",
-    {
-        "NextToken": str,
-        "BackupPlanTemplatesList": List[BackupPlanTemplatesListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupSelectionsOutputTypeDef = TypedDict(
-    "ListBackupSelectionsOutputTypeDef",
-    {
-        "NextToken": str,
-        "BackupSelectionsList": List[BackupSelectionsListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupVaultsOutputTypeDef = TypedDict(
-    "ListBackupVaultsOutputTypeDef",
-    {
-        "BackupVaultList": List[BackupVaultListMemberTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsOutputTypeDef = TypedDict(
-    "ListTagsOutputTypeDef",
-    {
-        "NextToken": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartBackupJobOutputTypeDef = TypedDict(
-    "StartBackupJobOutputTypeDef",
-    {
-        "BackupJobId": str,
-        "RecoveryPointArn": str,
-        "CreationDate": datetime,
-        "IsParent": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartCopyJobOutputTypeDef = TypedDict(
-    "StartCopyJobOutputTypeDef",
-    {
-        "CopyJobId": str,
-        "CreationDate": datetime,
-        "IsParent": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartReportJobOutputTypeDef = TypedDict(
-    "StartReportJobOutputTypeDef",
-    {
-        "ReportJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRestoreJobOutputTypeDef = TypedDict(
-    "StartRestoreJobOutputTypeDef",
-    {
-        "RestoreJobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Lifecycle": LifecycleTypeDef,
+        "CalculatedLifecycle": CalculatedLifecycleTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateBackupPlanOutputTypeDef = TypedDict(
-    "UpdateBackupPlanOutputTypeDef",
+ConditionsTypeDef = TypedDict(
+    "ConditionsTypeDef",
     {
-        "BackupPlanId": str,
-        "BackupPlanArn": str,
-        "CreationDate": datetime,
-        "VersionId": str,
-        "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StringEquals": Sequence[ConditionParameterTypeDef],
+        "StringNotEquals": Sequence[ConditionParameterTypeDef],
+        "StringLike": Sequence[ConditionParameterTypeDef],
+        "StringNotLike": Sequence[ConditionParameterTypeDef],
     },
+    total=False,
 )
 
-UpdateFrameworkOutputTypeDef = TypedDict(
-    "UpdateFrameworkOutputTypeDef",
+_RequiredFrameworkControlTypeDef = TypedDict(
+    "_RequiredFrameworkControlTypeDef",
     {
-        "FrameworkName": str,
-        "FrameworkArn": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ControlName": str,
     },
 )
-
-UpdateRecoveryPointLifecycleOutputTypeDef = TypedDict(
-    "UpdateRecoveryPointLifecycleOutputTypeDef",
+_OptionalFrameworkControlTypeDef = TypedDict(
+    "_OptionalFrameworkControlTypeDef",
     {
-        "BackupVaultArn": str,
-        "RecoveryPointArn": str,
-        "Lifecycle": LifecycleTypeDef,
-        "CalculatedLifecycle": CalculatedLifecycleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ControlInputParameters": Sequence[ControlInputParameterTypeDef],
+        "ControlScope": ControlScopeTypeDef,
     },
+    total=False,
 )
 
-UpdateReportPlanOutputTypeDef = TypedDict(
-    "UpdateReportPlanOutputTypeDef",
-    {
-        "ReportPlanName": str,
-        "ReportPlanArn": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class FrameworkControlTypeDef(_RequiredFrameworkControlTypeDef, _OptionalFrameworkControlTypeDef):
+    pass
 
 _RequiredCreateReportPlanInputRequestTypeDef = TypedDict(
     "_RequiredCreateReportPlanInputRequestTypeDef",
     {
         "ReportPlanName": str,
         "ReportDeliveryChannel": ReportDeliveryChannelTypeDef,
         "ReportSetting": ReportSettingTypeDef,
@@ -1794,257 +1995,60 @@
 )
 
 ListFrameworksOutputTypeDef = TypedDict(
     "ListFrameworksOutputTypeDef",
     {
         "Frameworks": List[FrameworkTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLegalHoldsOutputTypeDef = TypedDict(
     "ListLegalHoldsOutputTypeDef",
     {
         "NextToken": str,
         "LegalHolds": List[LegalHoldTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBackupJobsInputListBackupJobsPaginateTypeDef = TypedDict(
-    "ListBackupJobsInputListBackupJobsPaginateTypeDef",
-    {
-        "ByResourceArn": str,
-        "ByState": BackupJobStateType,
-        "ByBackupVaultName": str,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByResourceType": str,
-        "ByAccountId": str,
-        "ByCompleteAfter": Union[datetime, str],
-        "ByCompleteBefore": Union[datetime, str],
-        "ByParentJobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef = TypedDict(
-    "ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
-    {
-        "BackupPlanId": str,
-    },
-)
-_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef(
-    _RequiredListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
-    _OptionalListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
-):
-    pass
-
-ListBackupPlansInputListBackupPlansPaginateTypeDef = TypedDict(
-    "ListBackupPlansInputListBackupPlansPaginateTypeDef",
-    {
-        "IncludeDeleted": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
-    "_RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
-    {
-        "BackupPlanId": str,
-    },
-)
-_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef = TypedDict(
-    "_OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef(
-    _RequiredListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
-    _OptionalListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
-):
-    pass
-
-ListBackupVaultsInputListBackupVaultsPaginateTypeDef = TypedDict(
-    "ListBackupVaultsInputListBackupVaultsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCopyJobsInputListCopyJobsPaginateTypeDef = TypedDict(
-    "ListCopyJobsInputListCopyJobsPaginateTypeDef",
-    {
-        "ByResourceArn": str,
-        "ByState": CopyJobStateType,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByResourceType": str,
-        "ByDestinationVaultArn": str,
-        "ByAccountId": str,
-        "ByCompleteBefore": Union[datetime, str],
-        "ByCompleteAfter": Union[datetime, str],
-        "ByParentJobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListLegalHoldsInputListLegalHoldsPaginateTypeDef = TypedDict(
-    "ListLegalHoldsInputListLegalHoldsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef = TypedDict(
-    "ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
-    "_RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
-    {
-        "BackupVaultName": str,
-    },
-)
-_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef = TypedDict(
-    "_OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef",
-    {
-        "ByResourceArn": str,
-        "ByResourceType": str,
-        "ByBackupPlanId": str,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByParentRecoveryPointArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef(
-    _RequiredListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
-    _OptionalListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
-):
-    pass
-
-_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
-    "_RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
-    {
-        "LegalHoldId": str,
-    },
-)
-_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef = TypedDict(
-    "_OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef(
-    _RequiredListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
-    _OptionalListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
-):
-    pass
-
-_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
-    "_RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef = TypedDict(
-    "_OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef(
-    _RequiredListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
-    _OptionalListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
-):
-    pass
-
-ListRestoreJobsInputListRestoreJobsPaginateTypeDef = TypedDict(
-    "ListRestoreJobsInputListRestoreJobsPaginateTypeDef",
-    {
-        "ByAccountId": str,
-        "ByCreatedBefore": Union[datetime, str],
-        "ByCreatedAfter": Union[datetime, str],
-        "ByStatus": RestoreJobStatusType,
-        "ByCompleteBefore": Union[datetime, str],
-        "ByCompleteAfter": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 ListProtectedResourcesOutputTypeDef = TypedDict(
     "ListProtectedResourcesOutputTypeDef",
     {
         "Results": List[ProtectedResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryPointsByLegalHoldOutputTypeDef = TypedDict(
     "ListRecoveryPointsByLegalHoldOutputTypeDef",
     {
         "RecoveryPoints": List[RecoveryPointMemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryPointsByResourceOutputTypeDef = TypedDict(
     "ListRecoveryPointsByResourceOutputTypeDef",
     {
         "NextToken": str,
         "RecoveryPoints": List[RecoveryPointByResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRestoreJobsOutputTypeDef = TypedDict(
     "ListRestoreJobsOutputTypeDef",
     {
         "RestoreJobs": List[RestoreJobsListMemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReportJobTypeDef = TypedDict(
     "ReportJobTypeDef",
     {
         "ReportJobId": str,
@@ -2060,50 +2064,50 @@
 )
 
 ListBackupPlanVersionsOutputTypeDef = TypedDict(
     "ListBackupPlanVersionsOutputTypeDef",
     {
         "NextToken": str,
         "BackupPlanVersionsList": List[BackupPlansListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupPlansOutputTypeDef = TypedDict(
     "ListBackupPlansOutputTypeDef",
     {
         "NextToken": str,
         "BackupPlansList": List[BackupPlansListMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupJobsOutputTypeDef = TypedDict(
     "ListBackupJobsOutputTypeDef",
     {
         "BackupJobs": List[BackupJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCopyJobOutputTypeDef = TypedDict(
     "DescribeCopyJobOutputTypeDef",
     {
         "CopyJob": CopyJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCopyJobsOutputTypeDef = TypedDict(
     "ListCopyJobsOutputTypeDef",
     {
         "CopyJobs": List[CopyJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBackupRuleInputTypeDef = TypedDict(
     "_RequiredBackupRuleInputTypeDef",
     {
         "RuleName": str,
@@ -2153,15 +2157,15 @@
     pass
 
 ListRecoveryPointsByBackupVaultOutputTypeDef = TypedDict(
     "ListRecoveryPointsByBackupVaultOutputTypeDef",
     {
         "NextToken": str,
         "RecoveryPoints": List[RecoveryPointByBackupVaultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBackupSelectionTypeDef = TypedDict(
     "_RequiredBackupSelectionTypeDef",
     {
         "SelectionName": str,
@@ -2211,15 +2215,15 @@
         "FrameworkArn": str,
         "FrameworkDescription": str,
         "FrameworkControls": List[FrameworkControlTypeDef],
         "CreationTime": datetime,
         "DeploymentStatus": str,
         "FrameworkStatus": str,
         "IdempotencyToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFrameworkInputRequestTypeDef = TypedDict(
     "_RequiredUpdateFrameworkInputRequestTypeDef",
     {
         "FrameworkName": str,
@@ -2240,24 +2244,24 @@
 ):
     pass
 
 DescribeReportPlanOutputTypeDef = TypedDict(
     "DescribeReportPlanOutputTypeDef",
     {
         "ReportPlan": ReportPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReportPlansOutputTypeDef = TypedDict(
     "ListReportPlansOutputTypeDef",
     {
         "ReportPlans": List[ReportPlanTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLegalHoldInputRequestTypeDef = TypedDict(
     "_RequiredCreateLegalHoldInputRequestTypeDef",
     {
         "Title": str,
@@ -2285,15 +2289,15 @@
         "Title": str,
         "Status": LegalHoldStatusType,
         "Description": str,
         "LegalHoldId": str,
         "LegalHoldArn": str,
         "CreationDate": datetime,
         "RecoveryPointSelection": RecoveryPointSelectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLegalHoldOutputTypeDef = TypedDict(
     "GetLegalHoldOutputTypeDef",
     {
         "Title": str,
@@ -2302,32 +2306,32 @@
         "CancelDescription": str,
         "LegalHoldId": str,
         "LegalHoldArn": str,
         "CreationDate": datetime,
         "CancellationDate": datetime,
         "RetainRecordUntil": datetime,
         "RecoveryPointSelection": RecoveryPointSelectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReportJobOutputTypeDef = TypedDict(
     "DescribeReportJobOutputTypeDef",
     {
         "ReportJob": ReportJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReportJobsOutputTypeDef = TypedDict(
     "ListReportJobsOutputTypeDef",
     {
         "ReportJobs": List[ReportJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBackupPlanInputTypeDef = TypedDict(
     "_RequiredBackupPlanInputTypeDef",
     {
         "BackupPlanName": str,
@@ -2388,15 +2392,15 @@
     "GetBackupSelectionOutputTypeDef",
     {
         "BackupSelection": BackupSelectionTypeDef,
         "SelectionId": str,
         "BackupPlanId": str,
         "CreationDate": datetime,
         "CreatorRequestId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBackupPlanInputRequestTypeDef = TypedDict(
     "_RequiredCreateBackupPlanInputRequestTypeDef",
     {
         "BackupPlan": BackupPlanInputTypeDef,
@@ -2424,23 +2428,23 @@
     },
 )
 
 GetBackupPlanFromJSONOutputTypeDef = TypedDict(
     "GetBackupPlanFromJSONOutputTypeDef",
     {
         "BackupPlan": BackupPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBackupPlanFromTemplateOutputTypeDef = TypedDict(
     "GetBackupPlanFromTemplateOutputTypeDef",
     {
         "BackupPlanDocument": BackupPlanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBackupPlanOutputTypeDef = TypedDict(
     "GetBackupPlanOutputTypeDef",
     {
         "BackupPlan": BackupPlanTypeDef,
@@ -2448,10 +2452,10 @@
         "BackupPlanArn": str,
         "VersionId": str,
         "CreatorRequestId": str,
         "CreationDate": datetime,
         "DeletionDate": datetime,
         "LastExecutionDate": datetime,
         "AdvancedBackupSettings": List[AdvancedBackupSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/PKG-INFO` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-backup
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Backup 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Backup 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-backup"></a>
 
 # types-aiobotocore-backup
 
 [![PyPI - types-aiobotocore-backup](https://img.shields.io/pypi/v/types-aiobotocore-backup.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backup.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backup)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backup?color=blue)](https://pypistats.org/packages/types-aiobotocore-backup)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Backup 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
+[aiobotocore.Backup 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backup.html#Backup)
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
 [types-aiobotocore-backup docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backup/).
 
 See how it helps to find and fix potential bugs:
 
@@ -391,143 +391,143 @@
     BackupSelectionsListMemberTypeDef,
     BackupVaultListMemberTypeDef,
     CalculatedLifecycleTypeDef,
     CancelLegalHoldInputRequestTypeDef,
     ConditionParameterTypeDef,
     ControlInputParameterTypeDef,
     ControlScopeTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBackupSelectionOutputTypeDef,
     CreateBackupVaultInputRequestTypeDef,
+    CreateBackupVaultOutputTypeDef,
+    CreateFrameworkOutputTypeDef,
     ReportDeliveryChannelTypeDef,
     ReportSettingTypeDef,
+    CreateReportPlanOutputTypeDef,
     DateRangeTypeDef,
     DeleteBackupPlanInputRequestTypeDef,
+    DeleteBackupPlanOutputTypeDef,
     DeleteBackupSelectionInputRequestTypeDef,
     DeleteBackupVaultAccessPolicyInputRequestTypeDef,
     DeleteBackupVaultInputRequestTypeDef,
     DeleteBackupVaultLockConfigurationInputRequestTypeDef,
     DeleteBackupVaultNotificationsInputRequestTypeDef,
     DeleteFrameworkInputRequestTypeDef,
     DeleteRecoveryPointInputRequestTypeDef,
     DeleteReportPlanInputRequestTypeDef,
     DescribeBackupJobInputRequestTypeDef,
     DescribeBackupVaultInputRequestTypeDef,
+    DescribeBackupVaultOutputTypeDef,
     DescribeCopyJobInputRequestTypeDef,
     DescribeFrameworkInputRequestTypeDef,
+    DescribeGlobalSettingsOutputTypeDef,
     DescribeProtectedResourceInputRequestTypeDef,
+    DescribeProtectedResourceOutputTypeDef,
     DescribeRecoveryPointInputRequestTypeDef,
+    DescribeRegionSettingsOutputTypeDef,
     DescribeReportJobInputRequestTypeDef,
     DescribeReportPlanInputRequestTypeDef,
     DescribeRestoreJobInputRequestTypeDef,
+    DescribeRestoreJobOutputTypeDef,
     DisassociateRecoveryPointFromParentInputRequestTypeDef,
     DisassociateRecoveryPointInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportBackupPlanTemplateInputRequestTypeDef,
+    ExportBackupPlanTemplateOutputTypeDef,
     FrameworkTypeDef,
     GetBackupPlanFromJSONInputRequestTypeDef,
     GetBackupPlanFromTemplateInputRequestTypeDef,
     GetBackupPlanInputRequestTypeDef,
     GetBackupSelectionInputRequestTypeDef,
     GetBackupVaultAccessPolicyInputRequestTypeDef,
+    GetBackupVaultAccessPolicyOutputTypeDef,
     GetBackupVaultNotificationsInputRequestTypeDef,
+    GetBackupVaultNotificationsOutputTypeDef,
     GetLegalHoldInputRequestTypeDef,
     GetRecoveryPointRestoreMetadataInputRequestTypeDef,
+    GetRecoveryPointRestoreMetadataOutputTypeDef,
+    GetSupportedResourceTypesOutputTypeDef,
     LegalHoldTypeDef,
-    PaginatorConfigTypeDef,
+    ListBackupJobsInputListBackupJobsPaginateTypeDef,
     ListBackupJobsInputRequestTypeDef,
+    ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef,
     ListBackupPlanTemplatesInputRequestTypeDef,
+    ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
     ListBackupPlanVersionsInputRequestTypeDef,
+    ListBackupPlansInputListBackupPlansPaginateTypeDef,
     ListBackupPlansInputRequestTypeDef,
+    ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
     ListBackupSelectionsInputRequestTypeDef,
+    ListBackupVaultsInputListBackupVaultsPaginateTypeDef,
     ListBackupVaultsInputRequestTypeDef,
+    ListCopyJobsInputListCopyJobsPaginateTypeDef,
     ListCopyJobsInputRequestTypeDef,
     ListFrameworksInputRequestTypeDef,
+    ListLegalHoldsInputListLegalHoldsPaginateTypeDef,
     ListLegalHoldsInputRequestTypeDef,
+    ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef,
     ListProtectedResourcesInputRequestTypeDef,
     ProtectedResourceTypeDef,
+    ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
     ListRecoveryPointsByBackupVaultInputRequestTypeDef,
+    ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
     ListRecoveryPointsByLegalHoldInputRequestTypeDef,
     RecoveryPointMemberTypeDef,
+    ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
     ListRecoveryPointsByResourceInputRequestTypeDef,
     RecoveryPointByResourceTypeDef,
     ListReportJobsInputRequestTypeDef,
     ListReportPlansInputRequestTypeDef,
+    ListRestoreJobsInputListRestoreJobsPaginateTypeDef,
     ListRestoreJobsInputRequestTypeDef,
     RestoreJobsListMemberTypeDef,
     ListTagsInputRequestTypeDef,
+    ListTagsOutputTypeDef,
+    PaginatorConfigTypeDef,
     PutBackupVaultAccessPolicyInputRequestTypeDef,
     PutBackupVaultLockConfigurationInputRequestTypeDef,
     PutBackupVaultNotificationsInputRequestTypeDef,
     ReportDestinationTypeDef,
+    ResponseMetadataTypeDef,
+    StartBackupJobOutputTypeDef,
+    StartCopyJobOutputTypeDef,
     StartReportJobInputRequestTypeDef,
+    StartReportJobOutputTypeDef,
     StartRestoreJobInputRequestTypeDef,
+    StartRestoreJobOutputTypeDef,
     StopBackupJobInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateFrameworkOutputTypeDef,
     UpdateGlobalSettingsInputRequestTypeDef,
     UpdateRegionSettingsInputRequestTypeDef,
+    UpdateReportPlanOutputTypeDef,
     BackupPlansListMemberTypeDef,
+    CreateBackupPlanOutputTypeDef,
+    UpdateBackupPlanOutputTypeDef,
     BackupJobTypeDef,
     CopyJobTypeDef,
+    DescribeBackupJobOutputTypeDef,
+    ListBackupPlanTemplatesOutputTypeDef,
     CopyActionTypeDef,
     StartBackupJobInputRequestTypeDef,
     StartCopyJobInputRequestTypeDef,
     UpdateRecoveryPointLifecycleInputRequestTypeDef,
-    RecoveryPointByBackupVaultTypeDef,
-    ConditionsTypeDef,
-    FrameworkControlTypeDef,
-    CreateBackupPlanOutputTypeDef,
-    CreateBackupSelectionOutputTypeDef,
-    CreateBackupVaultOutputTypeDef,
-    CreateFrameworkOutputTypeDef,
-    CreateReportPlanOutputTypeDef,
-    DeleteBackupPlanOutputTypeDef,
-    DescribeBackupJobOutputTypeDef,
-    DescribeBackupVaultOutputTypeDef,
-    DescribeGlobalSettingsOutputTypeDef,
-    DescribeProtectedResourceOutputTypeDef,
-    DescribeRecoveryPointOutputTypeDef,
-    DescribeRegionSettingsOutputTypeDef,
-    DescribeRestoreJobOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportBackupPlanTemplateOutputTypeDef,
-    GetBackupVaultAccessPolicyOutputTypeDef,
-    GetBackupVaultNotificationsOutputTypeDef,
-    GetRecoveryPointRestoreMetadataOutputTypeDef,
-    GetSupportedResourceTypesOutputTypeDef,
-    ListBackupPlanTemplatesOutputTypeDef,
     ListBackupSelectionsOutputTypeDef,
     ListBackupVaultsOutputTypeDef,
-    ListTagsOutputTypeDef,
-    StartBackupJobOutputTypeDef,
-    StartCopyJobOutputTypeDef,
-    StartReportJobOutputTypeDef,
-    StartRestoreJobOutputTypeDef,
-    UpdateBackupPlanOutputTypeDef,
-    UpdateFrameworkOutputTypeDef,
+    DescribeRecoveryPointOutputTypeDef,
+    RecoveryPointByBackupVaultTypeDef,
     UpdateRecoveryPointLifecycleOutputTypeDef,
-    UpdateReportPlanOutputTypeDef,
+    ConditionsTypeDef,
+    FrameworkControlTypeDef,
     CreateReportPlanInputRequestTypeDef,
     ReportPlanTypeDef,
     UpdateReportPlanInputRequestTypeDef,
     RecoveryPointSelectionTypeDef,
     ListFrameworksOutputTypeDef,
     ListLegalHoldsOutputTypeDef,
-    ListBackupJobsInputListBackupJobsPaginateTypeDef,
-    ListBackupPlanTemplatesInputListBackupPlanTemplatesPaginateTypeDef,
-    ListBackupPlanVersionsInputListBackupPlanVersionsPaginateTypeDef,
-    ListBackupPlansInputListBackupPlansPaginateTypeDef,
-    ListBackupSelectionsInputListBackupSelectionsPaginateTypeDef,
-    ListBackupVaultsInputListBackupVaultsPaginateTypeDef,
-    ListCopyJobsInputListCopyJobsPaginateTypeDef,
-    ListLegalHoldsInputListLegalHoldsPaginateTypeDef,
-    ListProtectedResourcesInputListProtectedResourcesPaginateTypeDef,
-    ListRecoveryPointsByBackupVaultInputListRecoveryPointsByBackupVaultPaginateTypeDef,
-    ListRecoveryPointsByLegalHoldInputListRecoveryPointsByLegalHoldPaginateTypeDef,
-    ListRecoveryPointsByResourceInputListRecoveryPointsByResourcePaginateTypeDef,
-    ListRestoreJobsInputListRestoreJobsPaginateTypeDef,
     ListProtectedResourcesOutputTypeDef,
     ListRecoveryPointsByLegalHoldOutputTypeDef,
     ListRecoveryPointsByResourceOutputTypeDef,
     ListRestoreJobsOutputTypeDef,
     ReportJobTypeDef,
     ListBackupPlanVersionsOutputTypeDef,
     ListBackupPlansOutputTypeDef,
@@ -567,43 +567,43 @@
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

### Comparing `types-aiobotocore-backup-2.5.0.post1/types_aiobotocore_backup.egg-info/SOURCES.txt` & `types-aiobotocore-backup-2.5.1/types_aiobotocore_backup.egg-info/SOURCES.txt`

 * *Files identical despite different names*

