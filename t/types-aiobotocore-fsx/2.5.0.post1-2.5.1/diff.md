# Comparing `tmp/types-aiobotocore-fsx-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-fsx-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-fsx-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:39 2023, max compression
+gzip compressed data, was "types-aiobotocore-fsx-2.5.1.tar", last modified: Wed Jun 28 01:43:31 2023, max compression
```

## Comparing `types-aiobotocore-fsx-2.5.0.post1.tar` & `types-aiobotocore-fsx-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.623226 types-aiobotocore-fsx-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22343 2023-03-11 12:26:39.619226 types-aiobotocore-fsx-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20788 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:39.623226 types-aiobotocore-fsx-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.619226 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/
--rw-r--r--   0 runner    (1001) docker     (123)     1577 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1576 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    40818 2023-03-11 12:14:51.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    40763 2023-03-11 12:14:51.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14583 2023-03-11 12:14:51.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14581 2023-03-11 12:14:51.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7050 2023-03-11 12:14:51.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7042 2023-03-11 12:14:51.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    79146 2023-03-11 12:14:54.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    79049 2023-03-11 12:14:53.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:50.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.619226 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22343 2023-03-11 12:26:39.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:39.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:39.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:39.000000 types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.694141 types-aiobotocore-fsx-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22331 2023-06-28 01:43:31.694141 types-aiobotocore-fsx-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20782 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:31.694141 types-aiobotocore-fsx-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.686141 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/
+-rw-r--r--   0 runner    (1001) docker     (123)     1577 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1576 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40811 2023-06-28 01:31:28.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40756 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14870 2023-06-28 01:31:28.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14868 2023-06-28 01:31:28.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6964 2023-06-28 01:31:28.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6957 2023-06-28 01:31:28.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    79420 2023-06-28 01:31:30.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    79323 2023-06-28 01:31:29.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:27.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.694141 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22331 2023-06-28 01:43:31.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:31.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:31.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:31.000000 types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-fsx-2.5.0.post1/LICENSE` & `types-aiobotocore-fsx-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/PKG-INFO` & `types-aiobotocore-fsx-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-fsx
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FSx 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FSx 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-fsx"></a>
 
 # types-aiobotocore-fsx
 
 [![PyPI - types-aiobotocore-fsx](https://img.shields.io/pypi/v/types-aiobotocore-fsx.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fsx)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fsx.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fsx)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fsx?color=blue)](https://pypistats.org/packages/types-aiobotocore-fsx)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FSx 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
+[aiobotocore.FSx 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
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
 [types-aiobotocore-fsx docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/).
 
 See how it helps to find and fix potential bugs:
 
@@ -388,82 +388,84 @@
 
 ```python
 from types_aiobotocore_fsx.type_defs import (
     ActiveDirectoryBackupAttributesTypeDef,
     AdministrativeActionFailureDetailsTypeDef,
     AliasTypeDef,
     AssociateFileSystemAliasesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AutoExportPolicyTypeDef,
     AutoImportPolicyTypeDef,
     BackupFailureDetailsTypeDef,
     TagTypeDef,
     CancelDataRepositoryTaskRequestRequestTypeDef,
+    CancelDataRepositoryTaskResponseTypeDef,
     CompletionReportTypeDef,
     FileCacheLustreMetadataConfigurationTypeDef,
+    CreateFileSystemFromBackupResponseTypeDef,
     LustreLogCreateConfigurationTypeDef,
     LustreRootSquashConfigurationTypeDef,
     DiskIopsConfigurationTypeDef,
+    CreateFileSystemResponseTypeDef,
     SelfManagedActiveDirectoryConfigurationTypeDef,
     WindowsAuditLogCreateConfigurationTypeDef,
     TieringPolicyTypeDef,
     CreateOpenZFSOriginSnapshotConfigurationTypeDef,
     OpenZFSUserOrGroupQuotaTypeDef,
     DataRepositoryFailureDetailsTypeDef,
     DataRepositoryTaskFailureDetailsTypeDef,
     DataRepositoryTaskFilterTypeDef,
     DataRepositoryTaskStatusTypeDef,
     DeleteBackupRequestRequestTypeDef,
+    DeleteBackupResponseTypeDef,
     DeleteDataRepositoryAssociationRequestRequestTypeDef,
+    DeleteDataRepositoryAssociationResponseTypeDef,
     DeleteFileCacheRequestRequestTypeDef,
+    DeleteFileCacheResponseTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
+    DeleteSnapshotResponseTypeDef,
     DeleteStorageVirtualMachineRequestRequestTypeDef,
+    DeleteStorageVirtualMachineResponseTypeDef,
     DeleteVolumeOpenZFSConfigurationTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeFileCachesRequestRequestTypeDef,
     DescribeFileSystemAliasesRequestRequestTypeDef,
+    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
     DescribeFileSystemsRequestRequestTypeDef,
+    DescribeFileSystemsResponseTypeDef,
     SnapshotFilterTypeDef,
     StorageVirtualMachineFilterTypeDef,
     VolumeFilterTypeDef,
     DisassociateFileSystemAliasesRequestRequestTypeDef,
     FileCacheFailureDetailsTypeDef,
     FileCacheNFSConfigurationTypeDef,
     LustreLogConfigurationTypeDef,
     FileSystemEndpointTypeDef,
     FileSystemFailureDetailsTypeDef,
     LifecycleTransitionReasonTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OpenZFSClientConfigurationTypeDef,
     OpenZFSOriginSnapshotConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ReleaseFileSystemNfsV3LocksRequestRequestTypeDef,
+    ReleaseFileSystemNfsV3LocksResponseTypeDef,
+    ResponseMetadataTypeDef,
     RestoreVolumeFromSnapshotRequestRequestTypeDef,
+    RestoreVolumeFromSnapshotResponseTypeDef,
     SelfManagedActiveDirectoryAttributesTypeDef,
     SelfManagedActiveDirectoryConfigurationUpdatesTypeDef,
     SvmEndpointTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFileCacheLustreConfigurationTypeDef,
+    UpdateFileSystemResponseTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     WindowsAuditLogConfigurationTypeDef,
     AssociateFileSystemAliasesResponseTypeDef,
-    CancelDataRepositoryTaskResponseTypeDef,
-    CreateFileSystemFromBackupResponseTypeDef,
-    CreateFileSystemResponseTypeDef,
-    DeleteBackupResponseTypeDef,
-    DeleteDataRepositoryAssociationResponseTypeDef,
-    DeleteFileCacheResponseTypeDef,
-    DeleteSnapshotResponseTypeDef,
-    DeleteStorageVirtualMachineResponseTypeDef,
     DescribeFileSystemAliasesResponseTypeDef,
-    DescribeFileSystemsResponseTypeDef,
     DisassociateFileSystemAliasesResponseTypeDef,
-    ReleaseFileSystemNfsV3LocksResponseTypeDef,
-    RestoreVolumeFromSnapshotResponseTypeDef,
-    UpdateFileSystemResponseTypeDef,
     NFSDataRepositoryConfigurationTypeDef,
     S3DataRepositoryConfigurationTypeDef,
     CopyBackupRequestRequestTypeDef,
     CreateBackupRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     DeleteFileSystemLustreConfigurationTypeDef,
     DeleteFileSystemLustreResponseTypeDef,
@@ -487,19 +489,17 @@
     CreateFileSystemWindowsConfigurationTypeDef,
     CreateOntapVolumeConfigurationTypeDef,
     OntapVolumeConfigurationTypeDef,
     UpdateOntapVolumeConfigurationTypeDef,
     DataRepositoryConfigurationTypeDef,
     DescribeDataRepositoryTasksRequestRequestTypeDef,
     DataRepositoryTaskTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
     DescribeDataRepositoryAssociationsRequestRequestTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
     DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef,
     DescribeStorageVirtualMachinesRequestRequestTypeDef,
     DescribeVolumesRequestDescribeVolumesPaginateTypeDef,
     DescribeVolumesRequestRequestTypeDef,
     FileCacheDataRepositoryAssociationTypeDef,
     FileCacheLustreConfigurationTypeDef,
@@ -573,43 +573,43 @@
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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/README.md` & `types-aiobotocore-fsx-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-fsx"></a>
 
 # types-aiobotocore-fsx
 
 [![PyPI - types-aiobotocore-fsx](https://img.shields.io/pypi/v/types-aiobotocore-fsx.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fsx)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fsx.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fsx)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fsx?color=blue)](https://pypistats.org/packages/types-aiobotocore-fsx)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FSx 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
+[aiobotocore.FSx 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
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
 [types-aiobotocore-fsx docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/).
 
 See how it helps to find and fix potential bugs:
 
@@ -355,82 +355,84 @@
 
 ```python
 from types_aiobotocore_fsx.type_defs import (
     ActiveDirectoryBackupAttributesTypeDef,
     AdministrativeActionFailureDetailsTypeDef,
     AliasTypeDef,
     AssociateFileSystemAliasesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AutoExportPolicyTypeDef,
     AutoImportPolicyTypeDef,
     BackupFailureDetailsTypeDef,
     TagTypeDef,
     CancelDataRepositoryTaskRequestRequestTypeDef,
+    CancelDataRepositoryTaskResponseTypeDef,
     CompletionReportTypeDef,
     FileCacheLustreMetadataConfigurationTypeDef,
+    CreateFileSystemFromBackupResponseTypeDef,
     LustreLogCreateConfigurationTypeDef,
     LustreRootSquashConfigurationTypeDef,
     DiskIopsConfigurationTypeDef,
+    CreateFileSystemResponseTypeDef,
     SelfManagedActiveDirectoryConfigurationTypeDef,
     WindowsAuditLogCreateConfigurationTypeDef,
     TieringPolicyTypeDef,
     CreateOpenZFSOriginSnapshotConfigurationTypeDef,
     OpenZFSUserOrGroupQuotaTypeDef,
     DataRepositoryFailureDetailsTypeDef,
     DataRepositoryTaskFailureDetailsTypeDef,
     DataRepositoryTaskFilterTypeDef,
     DataRepositoryTaskStatusTypeDef,
     DeleteBackupRequestRequestTypeDef,
+    DeleteBackupResponseTypeDef,
     DeleteDataRepositoryAssociationRequestRequestTypeDef,
+    DeleteDataRepositoryAssociationResponseTypeDef,
     DeleteFileCacheRequestRequestTypeDef,
+    DeleteFileCacheResponseTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
+    DeleteSnapshotResponseTypeDef,
     DeleteStorageVirtualMachineRequestRequestTypeDef,
+    DeleteStorageVirtualMachineResponseTypeDef,
     DeleteVolumeOpenZFSConfigurationTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeFileCachesRequestRequestTypeDef,
     DescribeFileSystemAliasesRequestRequestTypeDef,
+    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
     DescribeFileSystemsRequestRequestTypeDef,
+    DescribeFileSystemsResponseTypeDef,
     SnapshotFilterTypeDef,
     StorageVirtualMachineFilterTypeDef,
     VolumeFilterTypeDef,
     DisassociateFileSystemAliasesRequestRequestTypeDef,
     FileCacheFailureDetailsTypeDef,
     FileCacheNFSConfigurationTypeDef,
     LustreLogConfigurationTypeDef,
     FileSystemEndpointTypeDef,
     FileSystemFailureDetailsTypeDef,
     LifecycleTransitionReasonTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OpenZFSClientConfigurationTypeDef,
     OpenZFSOriginSnapshotConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ReleaseFileSystemNfsV3LocksRequestRequestTypeDef,
+    ReleaseFileSystemNfsV3LocksResponseTypeDef,
+    ResponseMetadataTypeDef,
     RestoreVolumeFromSnapshotRequestRequestTypeDef,
+    RestoreVolumeFromSnapshotResponseTypeDef,
     SelfManagedActiveDirectoryAttributesTypeDef,
     SelfManagedActiveDirectoryConfigurationUpdatesTypeDef,
     SvmEndpointTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFileCacheLustreConfigurationTypeDef,
+    UpdateFileSystemResponseTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     WindowsAuditLogConfigurationTypeDef,
     AssociateFileSystemAliasesResponseTypeDef,
-    CancelDataRepositoryTaskResponseTypeDef,
-    CreateFileSystemFromBackupResponseTypeDef,
-    CreateFileSystemResponseTypeDef,
-    DeleteBackupResponseTypeDef,
-    DeleteDataRepositoryAssociationResponseTypeDef,
-    DeleteFileCacheResponseTypeDef,
-    DeleteSnapshotResponseTypeDef,
-    DeleteStorageVirtualMachineResponseTypeDef,
     DescribeFileSystemAliasesResponseTypeDef,
-    DescribeFileSystemsResponseTypeDef,
     DisassociateFileSystemAliasesResponseTypeDef,
-    ReleaseFileSystemNfsV3LocksResponseTypeDef,
-    RestoreVolumeFromSnapshotResponseTypeDef,
-    UpdateFileSystemResponseTypeDef,
     NFSDataRepositoryConfigurationTypeDef,
     S3DataRepositoryConfigurationTypeDef,
     CopyBackupRequestRequestTypeDef,
     CreateBackupRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     DeleteFileSystemLustreConfigurationTypeDef,
     DeleteFileSystemLustreResponseTypeDef,
@@ -454,19 +456,17 @@
     CreateFileSystemWindowsConfigurationTypeDef,
     CreateOntapVolumeConfigurationTypeDef,
     OntapVolumeConfigurationTypeDef,
     UpdateOntapVolumeConfigurationTypeDef,
     DataRepositoryConfigurationTypeDef,
     DescribeDataRepositoryTasksRequestRequestTypeDef,
     DataRepositoryTaskTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
     DescribeDataRepositoryAssociationsRequestRequestTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
     DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef,
     DescribeStorageVirtualMachinesRequestRequestTypeDef,
     DescribeVolumesRequestDescribeVolumesPaginateTypeDef,
     DescribeVolumesRequestRequestTypeDef,
     FileCacheDataRepositoryAssociationTypeDef,
     FileCacheLustreConfigurationTypeDef,
@@ -540,43 +540,43 @@
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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/setup.py` & `types-aiobotocore-fsx-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-fsx.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-fsx",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_fsx"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.FSx 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.FSx 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/",
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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/__init__.py` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/__init__.pyi` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/__main__.py` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.FSx 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.FSx 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx\nOther"
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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/client.py` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -790,15 +790,15 @@
         *,
         StorageVirtualMachineId: str,
         ActiveDirectoryConfiguration: UpdateSvmActiveDirectoryConfigurationTypeDef = ...,
         ClientRequestToken: str = ...,
         SvmAdminPassword: str = ...
     ) -> UpdateStorageVirtualMachineResponseTypeDef:
         """
-        Updates an Amazon FSx for ONTAP storage virtual machine (SVM).
+        Updates an FSx for ONTAP storage virtual machine (SVM).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.update_storage_virtual_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/client/#update_storage_virtual_machine)
         """
 
     async def update_volume(
         self,
```

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/client.pyi` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -743,15 +743,15 @@
         *,
         StorageVirtualMachineId: str,
         ActiveDirectoryConfiguration: UpdateSvmActiveDirectoryConfigurationTypeDef = ...,
         ClientRequestToken: str = ...,
         SvmAdminPassword: str = ...
     ) -> UpdateStorageVirtualMachineResponseTypeDef:
         """
-        Updates an Amazon FSx for ONTAP storage virtual machine (SVM).
+        Updates an FSx for ONTAP storage virtual machine (SVM).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Client.update_storage_virtual_machine)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/client/#update_storage_virtual_machine)
         """
     async def update_volume(
         self,
         *,
```

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/literals.py` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AdministrativeActionTypeType",
     "AliasLifecycleType",
     "AutoImportPolicyTypeType",
     "BackupLifecycleType",
     "BackupTypeType",
     "DataCompressionTypeType",
@@ -80,15 +79,14 @@
     "FSxServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 AdministrativeActionTypeType = Literal[
     "FILE_SYSTEM_ALIAS_ASSOCIATION",
     "FILE_SYSTEM_ALIAS_DISASSOCIATION",
     "FILE_SYSTEM_UPDATE",
     "RELEASE_NFS_V3_LOCKS",
     "SNAPSHOT_UPDATE",
     "STORAGE_OPTIMIZATION",
@@ -247,14 +245,15 @@
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
@@ -333,14 +332,15 @@
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
@@ -351,14 +351,15 @@
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
@@ -394,14 +395,15 @@
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
@@ -420,16 +422,19 @@
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
@@ -513,15 +518,17 @@
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
@@ -553,21 +560,25 @@
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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/literals.pyi` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AdministrativeActionTypeType",
     "AliasLifecycleType",
     "AutoImportPolicyTypeType",
     "BackupLifecycleType",
     "BackupTypeType",
     "DataCompressionTypeType",
@@ -79,14 +80,15 @@
     "FSxServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 AdministrativeActionTypeType = Literal[
     "FILE_SYSTEM_ALIAS_ASSOCIATION",
     "FILE_SYSTEM_ALIAS_DISASSOCIATION",
     "FILE_SYSTEM_UPDATE",
     "RELEASE_NFS_V3_LOCKS",
     "SNAPSHOT_UPDATE",
     "STORAGE_OPTIMIZATION",
@@ -245,14 +247,15 @@
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
@@ -331,14 +334,15 @@
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
@@ -349,14 +353,15 @@
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
@@ -392,14 +397,15 @@
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
@@ -418,16 +424,19 @@
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
@@ -511,15 +520,17 @@
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
@@ -551,21 +562,25 @@
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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/paginator.py` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         describe_backups_paginator: DescribeBackupsPaginator = client.get_paginator("describe_backups")
         describe_file_systems_paginator: DescribeFileSystemsPaginator = client.get_paginator("describe_file_systems")
         describe_storage_virtual_machines_paginator: DescribeStorageVirtualMachinesPaginator = client.get_paginator("describe_storage_virtual_machines")
         describe_volumes_paginator: DescribeVolumesPaginator = client.get_paginator("describe_volumes")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBackupsResponseTypeDef,
     DescribeFileSystemsResponseTypeDef,
@@ -42,20 +41,14 @@
     FilterTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     StorageVirtualMachineFilterTypeDef,
     VolumeFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeBackupsPaginator",
     "DescribeFileSystemsPaginator",
     "DescribeStorageVirtualMachinesPaginator",
     "DescribeVolumesPaginator",
     "ListTagsForResourcePaginator",
 )
@@ -78,30 +71,33 @@
     """
 
     def paginate(
         self,
         *,
         BackupIds: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describebackupspaginator)
         """
 
 
 class DescribeFileSystemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeFileSystems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describefilesystemspaginator)
     """
 
     def paginate(
-        self, *, FileSystemIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        FileSystemIds: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFileSystemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeFileSystems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describefilesystemspaginator)
         """
 
 
@@ -112,15 +108,15 @@
     """
 
     def paginate(
         self,
         *,
         StorageVirtualMachineIds: Sequence[str] = ...,
         Filters: Sequence[StorageVirtualMachineFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStorageVirtualMachinesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeStorageVirtualMachines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describestoragevirtualmachinespaginator)
         """
 
 
@@ -131,28 +127,28 @@
     """
 
     def paginate(
         self,
         *,
         VolumeIds: Sequence[str] = ...,
         Filters: Sequence[VolumeFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeVolumesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeVolumes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describevolumespaginator)
         """
 
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/paginator.pyi` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         describe_backups_paginator: DescribeBackupsPaginator = client.get_paginator("describe_backups")
         describe_file_systems_paginator: DescribeFileSystemsPaginator = client.get_paginator("describe_file_systems")
         describe_storage_virtual_machines_paginator: DescribeStorageVirtualMachinesPaginator = client.get_paginator("describe_storage_virtual_machines")
         describe_volumes_paginator: DescribeVolumesPaginator = client.get_paginator("describe_volumes")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBackupsResponseTypeDef,
     DescribeFileSystemsResponseTypeDef,
@@ -42,19 +41,14 @@
     FilterTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
     StorageVirtualMachineFilterTypeDef,
     VolumeFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeBackupsPaginator",
     "DescribeFileSystemsPaginator",
     "DescribeStorageVirtualMachinesPaginator",
     "DescribeVolumesPaginator",
     "ListTagsForResourcePaginator",
 )
@@ -74,29 +68,32 @@
     """
 
     def paginate(
         self,
         *,
         BackupIds: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describebackupspaginator)
         """
 
 class DescribeFileSystemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeFileSystems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describefilesystemspaginator)
     """
 
     def paginate(
-        self, *, FileSystemIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        FileSystemIds: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFileSystemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeFileSystems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describefilesystemspaginator)
         """
 
 class DescribeStorageVirtualMachinesPaginator(AioPaginator):
@@ -106,15 +103,15 @@
     """
 
     def paginate(
         self,
         *,
         StorageVirtualMachineIds: Sequence[str] = ...,
         Filters: Sequence[StorageVirtualMachineFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStorageVirtualMachinesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeStorageVirtualMachines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describestoragevirtualmachinespaginator)
         """
 
 class DescribeVolumesPaginator(AioPaginator):
@@ -124,27 +121,27 @@
     """
 
     def paginate(
         self,
         *,
         VolumeIds: Sequence[str] = ...,
         Filters: Sequence[VolumeFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeVolumesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.DescribeVolumes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#describevolumespaginator)
         """
 
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/type_defs.py` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/type_defs.py`

 * *Files 0% similar despite different names*

```diff
@@ -73,82 +73,84 @@
 
 
 __all__ = (
     "ActiveDirectoryBackupAttributesTypeDef",
     "AdministrativeActionFailureDetailsTypeDef",
     "AliasTypeDef",
     "AssociateFileSystemAliasesRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AutoExportPolicyTypeDef",
     "AutoImportPolicyTypeDef",
     "BackupFailureDetailsTypeDef",
     "TagTypeDef",
     "CancelDataRepositoryTaskRequestRequestTypeDef",
+    "CancelDataRepositoryTaskResponseTypeDef",
     "CompletionReportTypeDef",
     "FileCacheLustreMetadataConfigurationTypeDef",
+    "CreateFileSystemFromBackupResponseTypeDef",
     "LustreLogCreateConfigurationTypeDef",
     "LustreRootSquashConfigurationTypeDef",
     "DiskIopsConfigurationTypeDef",
+    "CreateFileSystemResponseTypeDef",
     "SelfManagedActiveDirectoryConfigurationTypeDef",
     "WindowsAuditLogCreateConfigurationTypeDef",
     "TieringPolicyTypeDef",
     "CreateOpenZFSOriginSnapshotConfigurationTypeDef",
     "OpenZFSUserOrGroupQuotaTypeDef",
     "DataRepositoryFailureDetailsTypeDef",
     "DataRepositoryTaskFailureDetailsTypeDef",
     "DataRepositoryTaskFilterTypeDef",
     "DataRepositoryTaskStatusTypeDef",
     "DeleteBackupRequestRequestTypeDef",
+    "DeleteBackupResponseTypeDef",
     "DeleteDataRepositoryAssociationRequestRequestTypeDef",
+    "DeleteDataRepositoryAssociationResponseTypeDef",
     "DeleteFileCacheRequestRequestTypeDef",
+    "DeleteFileCacheResponseTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
+    "DeleteSnapshotResponseTypeDef",
     "DeleteStorageVirtualMachineRequestRequestTypeDef",
+    "DeleteStorageVirtualMachineResponseTypeDef",
     "DeleteVolumeOpenZFSConfigurationTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeFileCachesRequestRequestTypeDef",
     "DescribeFileSystemAliasesRequestRequestTypeDef",
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
     "DescribeFileSystemsRequestRequestTypeDef",
+    "DescribeFileSystemsResponseTypeDef",
     "SnapshotFilterTypeDef",
     "StorageVirtualMachineFilterTypeDef",
     "VolumeFilterTypeDef",
     "DisassociateFileSystemAliasesRequestRequestTypeDef",
     "FileCacheFailureDetailsTypeDef",
     "FileCacheNFSConfigurationTypeDef",
     "LustreLogConfigurationTypeDef",
     "FileSystemEndpointTypeDef",
     "FileSystemFailureDetailsTypeDef",
     "LifecycleTransitionReasonTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "OpenZFSClientConfigurationTypeDef",
     "OpenZFSOriginSnapshotConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "ReleaseFileSystemNfsV3LocksRequestRequestTypeDef",
+    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreVolumeFromSnapshotRequestRequestTypeDef",
+    "RestoreVolumeFromSnapshotResponseTypeDef",
     "SelfManagedActiveDirectoryAttributesTypeDef",
     "SelfManagedActiveDirectoryConfigurationUpdatesTypeDef",
     "SvmEndpointTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFileCacheLustreConfigurationTypeDef",
+    "UpdateFileSystemResponseTypeDef",
     "UpdateSnapshotRequestRequestTypeDef",
     "WindowsAuditLogConfigurationTypeDef",
     "AssociateFileSystemAliasesResponseTypeDef",
-    "CancelDataRepositoryTaskResponseTypeDef",
-    "CreateFileSystemFromBackupResponseTypeDef",
-    "CreateFileSystemResponseTypeDef",
-    "DeleteBackupResponseTypeDef",
-    "DeleteDataRepositoryAssociationResponseTypeDef",
-    "DeleteFileCacheResponseTypeDef",
-    "DeleteSnapshotResponseTypeDef",
-    "DeleteStorageVirtualMachineResponseTypeDef",
     "DescribeFileSystemAliasesResponseTypeDef",
-    "DescribeFileSystemsResponseTypeDef",
     "DisassociateFileSystemAliasesResponseTypeDef",
-    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
-    "RestoreVolumeFromSnapshotResponseTypeDef",
-    "UpdateFileSystemResponseTypeDef",
     "NFSDataRepositoryConfigurationTypeDef",
     "S3DataRepositoryConfigurationTypeDef",
     "CopyBackupRequestRequestTypeDef",
     "CreateBackupRequestRequestTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "DeleteFileSystemLustreConfigurationTypeDef",
     "DeleteFileSystemLustreResponseTypeDef",
@@ -172,19 +174,17 @@
     "CreateFileSystemWindowsConfigurationTypeDef",
     "CreateOntapVolumeConfigurationTypeDef",
     "OntapVolumeConfigurationTypeDef",
     "UpdateOntapVolumeConfigurationTypeDef",
     "DataRepositoryConfigurationTypeDef",
     "DescribeDataRepositoryTasksRequestRequestTypeDef",
     "DataRepositoryTaskTypeDef",
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     "DescribeBackupsRequestRequestTypeDef",
     "DescribeDataRepositoryAssociationsRequestRequestTypeDef",
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "DescribeSnapshotsRequestRequestTypeDef",
     "DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef",
     "DescribeStorageVirtualMachinesRequestRequestTypeDef",
     "DescribeVolumesRequestDescribeVolumesPaginateTypeDef",
     "DescribeVolumesRequestRequestTypeDef",
     "FileCacheDataRepositoryAssociationTypeDef",
     "FileCacheLustreConfigurationTypeDef",
@@ -296,25 +296,14 @@
 class AssociateFileSystemAliasesRequestRequestTypeDef(
     _RequiredAssociateFileSystemAliasesRequestRequestTypeDef,
     _OptionalAssociateFileSystemAliasesRequestRequestTypeDef,
 ):
     pass
 
 
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
 AutoExportPolicyTypeDef = TypedDict(
     "AutoExportPolicyTypeDef",
     {
         "Events": Sequence[EventTypeType],
     },
     total=False,
 )
@@ -346,14 +335,23 @@
 CancelDataRepositoryTaskRequestRequestTypeDef = TypedDict(
     "CancelDataRepositoryTaskRequestRequestTypeDef",
     {
         "TaskId": str,
     },
 )
 
+CancelDataRepositoryTaskResponseTypeDef = TypedDict(
+    "CancelDataRepositoryTaskResponseTypeDef",
+    {
+        "Lifecycle": DataRepositoryTaskLifecycleType,
+        "TaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCompletionReportTypeDef = TypedDict(
     "_RequiredCompletionReportTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalCompletionReportTypeDef = TypedDict(
@@ -374,14 +372,22 @@
 FileCacheLustreMetadataConfigurationTypeDef = TypedDict(
     "FileCacheLustreMetadataConfigurationTypeDef",
     {
         "StorageCapacity": int,
     },
 )
 
+CreateFileSystemFromBackupResponseTypeDef = TypedDict(
+    "CreateFileSystemFromBackupResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredLustreLogCreateConfigurationTypeDef = TypedDict(
     "_RequiredLustreLogCreateConfigurationTypeDef",
     {
         "Level": LustreAccessAuditLogLevelType,
     },
 )
 _OptionalLustreLogCreateConfigurationTypeDef = TypedDict(
@@ -413,14 +419,22 @@
     {
         "Mode": DiskIopsConfigurationModeType,
         "Iops": int,
     },
     total=False,
 )
 
+CreateFileSystemResponseTypeDef = TypedDict(
+    "CreateFileSystemResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSelfManagedActiveDirectoryConfigurationTypeDef = TypedDict(
     "_RequiredSelfManagedActiveDirectoryConfigurationTypeDef",
     {
         "DomainName": str,
         "UserName": str,
         "Password": str,
         "DnsIps": Sequence[str],
@@ -546,14 +560,23 @@
 
 class DeleteBackupRequestRequestTypeDef(
     _RequiredDeleteBackupRequestRequestTypeDef, _OptionalDeleteBackupRequestRequestTypeDef
 ):
     pass
 
 
+DeleteBackupResponseTypeDef = TypedDict(
+    "DeleteBackupResponseTypeDef",
+    {
+        "BackupId": str,
+        "Lifecycle": BackupLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteDataRepositoryAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteDataRepositoryAssociationRequestRequestTypeDef",
     {
         "AssociationId": str,
     },
 )
 _OptionalDeleteDataRepositoryAssociationRequestRequestTypeDef = TypedDict(
@@ -569,14 +592,24 @@
 class DeleteDataRepositoryAssociationRequestRequestTypeDef(
     _RequiredDeleteDataRepositoryAssociationRequestRequestTypeDef,
     _OptionalDeleteDataRepositoryAssociationRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteDataRepositoryAssociationResponseTypeDef = TypedDict(
+    "DeleteDataRepositoryAssociationResponseTypeDef",
+    {
+        "AssociationId": str,
+        "Lifecycle": DataRepositoryLifecycleType,
+        "DeleteDataInFileSystem": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteFileCacheRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteFileCacheRequestRequestTypeDef",
     {
         "FileCacheId": str,
     },
 )
 _OptionalDeleteFileCacheRequestRequestTypeDef = TypedDict(
@@ -590,14 +623,23 @@
 
 class DeleteFileCacheRequestRequestTypeDef(
     _RequiredDeleteFileCacheRequestRequestTypeDef, _OptionalDeleteFileCacheRequestRequestTypeDef
 ):
     pass
 
 
+DeleteFileCacheResponseTypeDef = TypedDict(
+    "DeleteFileCacheResponseTypeDef",
+    {
+        "FileCacheId": str,
+        "Lifecycle": FileCacheLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteSnapshotRequestRequestTypeDef",
     {
         "SnapshotId": str,
     },
 )
 _OptionalDeleteSnapshotRequestRequestTypeDef = TypedDict(
@@ -611,14 +653,23 @@
 
 class DeleteSnapshotRequestRequestTypeDef(
     _RequiredDeleteSnapshotRequestRequestTypeDef, _OptionalDeleteSnapshotRequestRequestTypeDef
 ):
     pass
 
 
+DeleteSnapshotResponseTypeDef = TypedDict(
+    "DeleteSnapshotResponseTypeDef",
+    {
+        "SnapshotId": str,
+        "Lifecycle": SnapshotLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteStorageVirtualMachineRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteStorageVirtualMachineRequestRequestTypeDef",
     {
         "StorageVirtualMachineId": str,
     },
 )
 _OptionalDeleteStorageVirtualMachineRequestRequestTypeDef = TypedDict(
@@ -633,14 +684,23 @@
 class DeleteStorageVirtualMachineRequestRequestTypeDef(
     _RequiredDeleteStorageVirtualMachineRequestRequestTypeDef,
     _OptionalDeleteStorageVirtualMachineRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteStorageVirtualMachineResponseTypeDef = TypedDict(
+    "DeleteStorageVirtualMachineResponseTypeDef",
+    {
+        "StorageVirtualMachineId": str,
+        "Lifecycle": StorageVirtualMachineLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteVolumeOpenZFSConfigurationTypeDef = TypedDict(
     "DeleteVolumeOpenZFSConfigurationTypeDef",
     {
         "Options": Sequence[Literal["DELETE_CHILD_VOLUMES_AND_SNAPSHOTS"]],
     },
     total=False,
 )
@@ -650,24 +710,14 @@
     {
         "Name": FilterNameType,
         "Values": Sequence[str],
     },
     total=False,
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
 DescribeFileCachesRequestRequestTypeDef = TypedDict(
     "DescribeFileCachesRequestRequestTypeDef",
     {
         "FileCacheIds": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -694,24 +744,42 @@
 class DescribeFileSystemAliasesRequestRequestTypeDef(
     _RequiredDescribeFileSystemAliasesRequestRequestTypeDef,
     _OptionalDescribeFileSystemAliasesRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
+    {
+        "FileSystemIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeFileSystemsRequestRequestTypeDef = TypedDict(
     "DescribeFileSystemsRequestRequestTypeDef",
     {
         "FileSystemIds": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeFileSystemsResponseTypeDef = TypedDict(
+    "DescribeFileSystemsResponseTypeDef",
+    {
+        "FileSystems": List["FileSystemTypeDef"],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SnapshotFilterTypeDef = TypedDict(
     "SnapshotFilterTypeDef",
     {
         "Name": SnapshotFilterNameType,
         "Values": Sequence[str],
     },
     total=False,
@@ -829,14 +897,36 @@
     "LifecycleTransitionReasonTypeDef",
     {
         "Message": str,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -869,14 +959,24 @@
     {
         "SnapshotARN": str,
         "CopyStrategy": OpenZFSCopyStrategyType,
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
 _RequiredReleaseFileSystemNfsV3LocksRequestRequestTypeDef = TypedDict(
     "_RequiredReleaseFileSystemNfsV3LocksRequestRequestTypeDef",
     {
         "FileSystemId": str,
     },
 )
 _OptionalReleaseFileSystemNfsV3LocksRequestRequestTypeDef = TypedDict(
@@ -891,14 +991,33 @@
 class ReleaseFileSystemNfsV3LocksRequestRequestTypeDef(
     _RequiredReleaseFileSystemNfsV3LocksRequestRequestTypeDef,
     _OptionalReleaseFileSystemNfsV3LocksRequestRequestTypeDef,
 ):
     pass
 
 
+ReleaseFileSystemNfsV3LocksResponseTypeDef = TypedDict(
+    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
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
 _RequiredRestoreVolumeFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreVolumeFromSnapshotRequestRequestTypeDef",
     {
         "VolumeId": str,
         "SnapshotId": str,
     },
 )
@@ -915,14 +1034,24 @@
 class RestoreVolumeFromSnapshotRequestRequestTypeDef(
     _RequiredRestoreVolumeFromSnapshotRequestRequestTypeDef,
     _OptionalRestoreVolumeFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
 
+RestoreVolumeFromSnapshotResponseTypeDef = TypedDict(
+    "RestoreVolumeFromSnapshotResponseTypeDef",
+    {
+        "VolumeId": str,
+        "Lifecycle": VolumeLifecycleType,
+        "AdministrativeActions": List["AdministrativeActionTypeDef"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SelfManagedActiveDirectoryAttributesTypeDef = TypedDict(
     "SelfManagedActiveDirectoryAttributesTypeDef",
     {
         "DomainName": str,
         "OrganizationalUnitDistinguishedName": str,
         "FileSystemAdministratorsGroup": str,
         "UserName": str,
@@ -933,14 +1062,17 @@
 
 SelfManagedActiveDirectoryConfigurationUpdatesTypeDef = TypedDict(
     "SelfManagedActiveDirectoryConfigurationUpdatesTypeDef",
     {
         "UserName": str,
         "Password": str,
         "DnsIps": Sequence[str],
+        "DomainName": str,
+        "OrganizationalUnitDistinguishedName": str,
+        "FileSystemAdministratorsGroup": str,
     },
     total=False,
 )
 
 SvmEndpointTypeDef = TypedDict(
     "SvmEndpointTypeDef",
     {
@@ -962,14 +1094,22 @@
     "UpdateFileCacheLustreConfigurationTypeDef",
     {
         "WeeklyMaintenanceStartTime": str,
     },
     total=False,
 )
 
+UpdateFileSystemResponseTypeDef = TypedDict(
+    "UpdateFileSystemResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSnapshotRequestRequestTypeDef",
     {
         "Name": str,
         "SnapshotId": str,
     },
 )
@@ -1010,138 +1150,32 @@
     pass
 
 
 AssociateFileSystemAliasesResponseTypeDef = TypedDict(
     "AssociateFileSystemAliasesResponseTypeDef",
     {
         "Aliases": List[AliasTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelDataRepositoryTaskResponseTypeDef = TypedDict(
-    "CancelDataRepositoryTaskResponseTypeDef",
-    {
-        "Lifecycle": DataRepositoryTaskLifecycleType,
-        "TaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFileSystemFromBackupResponseTypeDef = TypedDict(
-    "CreateFileSystemFromBackupResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFileSystemResponseTypeDef = TypedDict(
-    "CreateFileSystemResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBackupResponseTypeDef = TypedDict(
-    "DeleteBackupResponseTypeDef",
-    {
-        "BackupId": str,
-        "Lifecycle": BackupLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDataRepositoryAssociationResponseTypeDef = TypedDict(
-    "DeleteDataRepositoryAssociationResponseTypeDef",
-    {
-        "AssociationId": str,
-        "Lifecycle": DataRepositoryLifecycleType,
-        "DeleteDataInFileSystem": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteFileCacheResponseTypeDef = TypedDict(
-    "DeleteFileCacheResponseTypeDef",
-    {
-        "FileCacheId": str,
-        "Lifecycle": FileCacheLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSnapshotResponseTypeDef = TypedDict(
-    "DeleteSnapshotResponseTypeDef",
-    {
-        "SnapshotId": str,
-        "Lifecycle": SnapshotLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteStorageVirtualMachineResponseTypeDef = TypedDict(
-    "DeleteStorageVirtualMachineResponseTypeDef",
-    {
-        "StorageVirtualMachineId": str,
-        "Lifecycle": StorageVirtualMachineLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFileSystemAliasesResponseTypeDef = TypedDict(
     "DescribeFileSystemAliasesResponseTypeDef",
     {
         "Aliases": List[AliasTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFileSystemsResponseTypeDef = TypedDict(
-    "DescribeFileSystemsResponseTypeDef",
-    {
-        "FileSystems": List["FileSystemTypeDef"],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateFileSystemAliasesResponseTypeDef = TypedDict(
     "DisassociateFileSystemAliasesResponseTypeDef",
     {
         "Aliases": List[AliasTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReleaseFileSystemNfsV3LocksResponseTypeDef = TypedDict(
-    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreVolumeFromSnapshotResponseTypeDef = TypedDict(
-    "RestoreVolumeFromSnapshotResponseTypeDef",
-    {
-        "VolumeId": str,
-        "Lifecycle": VolumeLifecycleType,
-        "AdministrativeActions": List["AdministrativeActionTypeDef"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFileSystemResponseTypeDef = TypedDict(
-    "UpdateFileSystemResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNFSDataRepositoryConfigurationTypeDef = TypedDict(
     "_RequiredNFSDataRepositoryConfigurationTypeDef",
     {
         "Version": Literal["NFS3"],
@@ -1305,15 +1339,15 @@
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -1650,14 +1684,24 @@
 
 class DataRepositoryTaskTypeDef(
     _RequiredDataRepositoryTaskTypeDef, _OptionalDataRepositoryTaskTypeDef
 ):
     pass
 
 
+DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
+    {
+        "BackupIds": Sequence[str],
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeBackupsRequestRequestTypeDef = TypedDict(
     "DescribeBackupsRequestRequestTypeDef",
     {
         "BackupIds": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
@@ -1672,55 +1716,14 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    {
-        "BackupIds": Sequence[str],
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    {
-        "FileSystemIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
 DescribeSnapshotsRequestRequestTypeDef = TypedDict(
     "DescribeSnapshotsRequestRequestTypeDef",
     {
         "SnapshotIds": Sequence[str],
         "Filters": Sequence[SnapshotFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
@@ -1729,15 +1732,15 @@
 )
 
 DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef = TypedDict(
     "DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef",
     {
         "StorageVirtualMachineIds": Sequence[str],
         "Filters": Sequence[StorageVirtualMachineFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeStorageVirtualMachinesRequestRequestTypeDef = TypedDict(
     "DescribeStorageVirtualMachinesRequestRequestTypeDef",
     {
@@ -1750,15 +1753,15 @@
 )
 
 DescribeVolumesRequestDescribeVolumesPaginateTypeDef = TypedDict(
     "DescribeVolumesRequestDescribeVolumesPaginateTypeDef",
     {
         "VolumeIds": Sequence[str],
         "Filters": Sequence[VolumeFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeVolumesRequestRequestTypeDef = TypedDict(
     "DescribeVolumesRequestRequestTypeDef",
     {
@@ -1865,14 +1868,15 @@
 
 UpdateSvmActiveDirectoryConfigurationTypeDef = TypedDict(
     "UpdateSvmActiveDirectoryConfigurationTypeDef",
     {
         "SelfManagedActiveDirectoryConfiguration": (
             SelfManagedActiveDirectoryConfigurationUpdatesTypeDef
         ),
+        "NetBiosName": str,
     },
     total=False,
 )
 
 SvmEndpointsTypeDef = TypedDict(
     "SvmEndpointsTypeDef",
     {
@@ -2030,15 +2034,15 @@
     "DeleteFileSystemResponseTypeDef",
     {
         "FileSystemId": str,
         "Lifecycle": FileSystemLifecycleType,
         "WindowsResponse": DeleteFileSystemWindowsResponseTypeDef,
         "LustreResponse": DeleteFileSystemLustreResponseTypeDef,
         "OpenZFSResponse": DeleteFileSystemOpenZFSResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeleteVolumeRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteVolumeRequestRequestTypeDef",
     {
         "VolumeId": str,
@@ -2063,15 +2067,15 @@
 
 DeleteVolumeResponseTypeDef = TypedDict(
     "DeleteVolumeResponseTypeDef",
     {
         "VolumeId": str,
         "Lifecycle": VolumeLifecycleType,
         "OntapResponse": DeleteVolumeOntapResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStorageVirtualMachineRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStorageVirtualMachineRequestRequestTypeDef",
     {
         "FileSystemId": str,
@@ -2142,24 +2146,24 @@
     total=False,
 )
 
 CreateDataRepositoryTaskResponseTypeDef = TypedDict(
     "CreateDataRepositoryTaskResponseTypeDef",
     {
         "DataRepositoryTask": DataRepositoryTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataRepositoryTasksResponseTypeDef = TypedDict(
     "DescribeDataRepositoryTasksResponseTypeDef",
     {
         "DataRepositoryTasks": List[DataRepositoryTaskTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFileCacheRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFileCacheRequestRequestTypeDef",
     {
         "FileCacheType": Literal["LUSTRE"],
@@ -2246,40 +2250,41 @@
         "EndpointIpAddressRange": str,
         "Endpoints": FileSystemEndpointsTypeDef,
         "DiskIopsConfiguration": DiskIopsConfigurationTypeDef,
         "PreferredSubnetId": str,
         "RouteTableIds": List[str],
         "ThroughputCapacity": int,
         "WeeklyMaintenanceStartTime": str,
+        "FsxAdminPassword": str,
     },
     total=False,
 )
 
 CreateSnapshotResponseTypeDef = TypedDict(
     "CreateSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsResponseTypeDef = TypedDict(
     "DescribeSnapshotsResponseTypeDef",
     {
         "Snapshots": List[SnapshotTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSnapshotResponseTypeDef = TypedDict(
     "UpdateSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateOpenZFSVolumeConfigurationTypeDef = TypedDict(
     "_RequiredCreateOpenZFSVolumeConfigurationTypeDef",
     {
         "ParentVolumeId": str,
@@ -2427,57 +2432,57 @@
     total=False,
 )
 
 CreateDataRepositoryAssociationResponseTypeDef = TypedDict(
     "CreateDataRepositoryAssociationResponseTypeDef",
     {
         "Association": DataRepositoryAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataRepositoryAssociationsResponseTypeDef = TypedDict(
     "DescribeDataRepositoryAssociationsResponseTypeDef",
     {
         "Associations": List[DataRepositoryAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDataRepositoryAssociationResponseTypeDef = TypedDict(
     "UpdateDataRepositoryAssociationResponseTypeDef",
     {
         "Association": DataRepositoryAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFileCacheResponseTypeDef = TypedDict(
     "CreateFileCacheResponseTypeDef",
     {
         "FileCache": FileCacheCreatingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFileCachesResponseTypeDef = TypedDict(
     "DescribeFileCachesResponseTypeDef",
     {
         "FileCaches": List[FileCacheTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFileCacheResponseTypeDef = TypedDict(
     "UpdateFileCacheResponseTypeDef",
     {
         "FileCache": FileCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FileSystemTypeDef = TypedDict(
     "FileSystemTypeDef",
     {
         "OwnerId": str,
@@ -2602,32 +2607,32 @@
     pass
 
 
 CreateStorageVirtualMachineResponseTypeDef = TypedDict(
     "CreateStorageVirtualMachineResponseTypeDef",
     {
         "StorageVirtualMachine": StorageVirtualMachineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStorageVirtualMachinesResponseTypeDef = TypedDict(
     "DescribeStorageVirtualMachinesResponseTypeDef",
     {
         "StorageVirtualMachines": List[StorageVirtualMachineTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStorageVirtualMachineResponseTypeDef = TypedDict(
     "UpdateStorageVirtualMachineResponseTypeDef",
     {
         "StorageVirtualMachine": StorageVirtualMachineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFileSystemFromBackupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFileSystemFromBackupRequestRequestTypeDef",
     {
         "BackupId": str,
@@ -2739,60 +2744,60 @@
     pass
 
 
 CreateVolumeFromBackupResponseTypeDef = TypedDict(
     "CreateVolumeFromBackupResponseTypeDef",
     {
         "Volume": VolumeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVolumeResponseTypeDef = TypedDict(
     "CreateVolumeResponseTypeDef",
     {
         "Volume": VolumeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVolumesResponseTypeDef = TypedDict(
     "DescribeVolumesResponseTypeDef",
     {
         "Volumes": List[VolumeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVolumeResponseTypeDef = TypedDict(
     "UpdateVolumeResponseTypeDef",
     {
         "Volume": VolumeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyBackupResponseTypeDef = TypedDict(
     "CopyBackupResponseTypeDef",
     {
         "Backup": BackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBackupResponseTypeDef = TypedDict(
     "CreateBackupResponseTypeDef",
     {
         "Backup": BackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBackupsResponseTypeDef = TypedDict(
     "DescribeBackupsResponseTypeDef",
     {
         "Backups": List[BackupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx/type_defs.pyi` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx/type_defs.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -72,82 +72,84 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "ActiveDirectoryBackupAttributesTypeDef",
     "AdministrativeActionFailureDetailsTypeDef",
     "AliasTypeDef",
     "AssociateFileSystemAliasesRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AutoExportPolicyTypeDef",
     "AutoImportPolicyTypeDef",
     "BackupFailureDetailsTypeDef",
     "TagTypeDef",
     "CancelDataRepositoryTaskRequestRequestTypeDef",
+    "CancelDataRepositoryTaskResponseTypeDef",
     "CompletionReportTypeDef",
     "FileCacheLustreMetadataConfigurationTypeDef",
+    "CreateFileSystemFromBackupResponseTypeDef",
     "LustreLogCreateConfigurationTypeDef",
     "LustreRootSquashConfigurationTypeDef",
     "DiskIopsConfigurationTypeDef",
+    "CreateFileSystemResponseTypeDef",
     "SelfManagedActiveDirectoryConfigurationTypeDef",
     "WindowsAuditLogCreateConfigurationTypeDef",
     "TieringPolicyTypeDef",
     "CreateOpenZFSOriginSnapshotConfigurationTypeDef",
     "OpenZFSUserOrGroupQuotaTypeDef",
     "DataRepositoryFailureDetailsTypeDef",
     "DataRepositoryTaskFailureDetailsTypeDef",
     "DataRepositoryTaskFilterTypeDef",
     "DataRepositoryTaskStatusTypeDef",
     "DeleteBackupRequestRequestTypeDef",
+    "DeleteBackupResponseTypeDef",
     "DeleteDataRepositoryAssociationRequestRequestTypeDef",
+    "DeleteDataRepositoryAssociationResponseTypeDef",
     "DeleteFileCacheRequestRequestTypeDef",
+    "DeleteFileCacheResponseTypeDef",
     "DeleteSnapshotRequestRequestTypeDef",
+    "DeleteSnapshotResponseTypeDef",
     "DeleteStorageVirtualMachineRequestRequestTypeDef",
+    "DeleteStorageVirtualMachineResponseTypeDef",
     "DeleteVolumeOpenZFSConfigurationTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeFileCachesRequestRequestTypeDef",
     "DescribeFileSystemAliasesRequestRequestTypeDef",
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
     "DescribeFileSystemsRequestRequestTypeDef",
+    "DescribeFileSystemsResponseTypeDef",
     "SnapshotFilterTypeDef",
     "StorageVirtualMachineFilterTypeDef",
     "VolumeFilterTypeDef",
     "DisassociateFileSystemAliasesRequestRequestTypeDef",
     "FileCacheFailureDetailsTypeDef",
     "FileCacheNFSConfigurationTypeDef",
     "LustreLogConfigurationTypeDef",
     "FileSystemEndpointTypeDef",
     "FileSystemFailureDetailsTypeDef",
     "LifecycleTransitionReasonTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "OpenZFSClientConfigurationTypeDef",
     "OpenZFSOriginSnapshotConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "ReleaseFileSystemNfsV3LocksRequestRequestTypeDef",
+    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreVolumeFromSnapshotRequestRequestTypeDef",
+    "RestoreVolumeFromSnapshotResponseTypeDef",
     "SelfManagedActiveDirectoryAttributesTypeDef",
     "SelfManagedActiveDirectoryConfigurationUpdatesTypeDef",
     "SvmEndpointTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFileCacheLustreConfigurationTypeDef",
+    "UpdateFileSystemResponseTypeDef",
     "UpdateSnapshotRequestRequestTypeDef",
     "WindowsAuditLogConfigurationTypeDef",
     "AssociateFileSystemAliasesResponseTypeDef",
-    "CancelDataRepositoryTaskResponseTypeDef",
-    "CreateFileSystemFromBackupResponseTypeDef",
-    "CreateFileSystemResponseTypeDef",
-    "DeleteBackupResponseTypeDef",
-    "DeleteDataRepositoryAssociationResponseTypeDef",
-    "DeleteFileCacheResponseTypeDef",
-    "DeleteSnapshotResponseTypeDef",
-    "DeleteStorageVirtualMachineResponseTypeDef",
     "DescribeFileSystemAliasesResponseTypeDef",
-    "DescribeFileSystemsResponseTypeDef",
     "DisassociateFileSystemAliasesResponseTypeDef",
-    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
-    "RestoreVolumeFromSnapshotResponseTypeDef",
-    "UpdateFileSystemResponseTypeDef",
     "NFSDataRepositoryConfigurationTypeDef",
     "S3DataRepositoryConfigurationTypeDef",
     "CopyBackupRequestRequestTypeDef",
     "CreateBackupRequestRequestTypeDef",
     "CreateSnapshotRequestRequestTypeDef",
     "DeleteFileSystemLustreConfigurationTypeDef",
     "DeleteFileSystemLustreResponseTypeDef",
@@ -171,19 +173,17 @@
     "CreateFileSystemWindowsConfigurationTypeDef",
     "CreateOntapVolumeConfigurationTypeDef",
     "OntapVolumeConfigurationTypeDef",
     "UpdateOntapVolumeConfigurationTypeDef",
     "DataRepositoryConfigurationTypeDef",
     "DescribeDataRepositoryTasksRequestRequestTypeDef",
     "DataRepositoryTaskTypeDef",
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     "DescribeBackupsRequestRequestTypeDef",
     "DescribeDataRepositoryAssociationsRequestRequestTypeDef",
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "DescribeSnapshotsRequestRequestTypeDef",
     "DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef",
     "DescribeStorageVirtualMachinesRequestRequestTypeDef",
     "DescribeVolumesRequestDescribeVolumesPaginateTypeDef",
     "DescribeVolumesRequestRequestTypeDef",
     "FileCacheDataRepositoryAssociationTypeDef",
     "FileCacheLustreConfigurationTypeDef",
@@ -293,25 +293,14 @@
 
 class AssociateFileSystemAliasesRequestRequestTypeDef(
     _RequiredAssociateFileSystemAliasesRequestRequestTypeDef,
     _OptionalAssociateFileSystemAliasesRequestRequestTypeDef,
 ):
     pass
 
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
 AutoExportPolicyTypeDef = TypedDict(
     "AutoExportPolicyTypeDef",
     {
         "Events": Sequence[EventTypeType],
     },
     total=False,
 )
@@ -343,14 +332,23 @@
 CancelDataRepositoryTaskRequestRequestTypeDef = TypedDict(
     "CancelDataRepositoryTaskRequestRequestTypeDef",
     {
         "TaskId": str,
     },
 )
 
+CancelDataRepositoryTaskResponseTypeDef = TypedDict(
+    "CancelDataRepositoryTaskResponseTypeDef",
+    {
+        "Lifecycle": DataRepositoryTaskLifecycleType,
+        "TaskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCompletionReportTypeDef = TypedDict(
     "_RequiredCompletionReportTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalCompletionReportTypeDef = TypedDict(
@@ -369,14 +367,22 @@
 FileCacheLustreMetadataConfigurationTypeDef = TypedDict(
     "FileCacheLustreMetadataConfigurationTypeDef",
     {
         "StorageCapacity": int,
     },
 )
 
+CreateFileSystemFromBackupResponseTypeDef = TypedDict(
+    "CreateFileSystemFromBackupResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredLustreLogCreateConfigurationTypeDef = TypedDict(
     "_RequiredLustreLogCreateConfigurationTypeDef",
     {
         "Level": LustreAccessAuditLogLevelType,
     },
 )
 _OptionalLustreLogCreateConfigurationTypeDef = TypedDict(
@@ -406,14 +412,22 @@
     {
         "Mode": DiskIopsConfigurationModeType,
         "Iops": int,
     },
     total=False,
 )
 
+CreateFileSystemResponseTypeDef = TypedDict(
+    "CreateFileSystemResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSelfManagedActiveDirectoryConfigurationTypeDef = TypedDict(
     "_RequiredSelfManagedActiveDirectoryConfigurationTypeDef",
     {
         "DomainName": str,
         "UserName": str,
         "Password": str,
         "DnsIps": Sequence[str],
@@ -533,14 +547,23 @@
 )
 
 class DeleteBackupRequestRequestTypeDef(
     _RequiredDeleteBackupRequestRequestTypeDef, _OptionalDeleteBackupRequestRequestTypeDef
 ):
     pass
 
+DeleteBackupResponseTypeDef = TypedDict(
+    "DeleteBackupResponseTypeDef",
+    {
+        "BackupId": str,
+        "Lifecycle": BackupLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteDataRepositoryAssociationRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteDataRepositoryAssociationRequestRequestTypeDef",
     {
         "AssociationId": str,
     },
 )
 _OptionalDeleteDataRepositoryAssociationRequestRequestTypeDef = TypedDict(
@@ -554,14 +577,24 @@
 
 class DeleteDataRepositoryAssociationRequestRequestTypeDef(
     _RequiredDeleteDataRepositoryAssociationRequestRequestTypeDef,
     _OptionalDeleteDataRepositoryAssociationRequestRequestTypeDef,
 ):
     pass
 
+DeleteDataRepositoryAssociationResponseTypeDef = TypedDict(
+    "DeleteDataRepositoryAssociationResponseTypeDef",
+    {
+        "AssociationId": str,
+        "Lifecycle": DataRepositoryLifecycleType,
+        "DeleteDataInFileSystem": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteFileCacheRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteFileCacheRequestRequestTypeDef",
     {
         "FileCacheId": str,
     },
 )
 _OptionalDeleteFileCacheRequestRequestTypeDef = TypedDict(
@@ -573,14 +606,23 @@
 )
 
 class DeleteFileCacheRequestRequestTypeDef(
     _RequiredDeleteFileCacheRequestRequestTypeDef, _OptionalDeleteFileCacheRequestRequestTypeDef
 ):
     pass
 
+DeleteFileCacheResponseTypeDef = TypedDict(
+    "DeleteFileCacheResponseTypeDef",
+    {
+        "FileCacheId": str,
+        "Lifecycle": FileCacheLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteSnapshotRequestRequestTypeDef",
     {
         "SnapshotId": str,
     },
 )
 _OptionalDeleteSnapshotRequestRequestTypeDef = TypedDict(
@@ -592,14 +634,23 @@
 )
 
 class DeleteSnapshotRequestRequestTypeDef(
     _RequiredDeleteSnapshotRequestRequestTypeDef, _OptionalDeleteSnapshotRequestRequestTypeDef
 ):
     pass
 
+DeleteSnapshotResponseTypeDef = TypedDict(
+    "DeleteSnapshotResponseTypeDef",
+    {
+        "SnapshotId": str,
+        "Lifecycle": SnapshotLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteStorageVirtualMachineRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteStorageVirtualMachineRequestRequestTypeDef",
     {
         "StorageVirtualMachineId": str,
     },
 )
 _OptionalDeleteStorageVirtualMachineRequestRequestTypeDef = TypedDict(
@@ -612,14 +663,23 @@
 
 class DeleteStorageVirtualMachineRequestRequestTypeDef(
     _RequiredDeleteStorageVirtualMachineRequestRequestTypeDef,
     _OptionalDeleteStorageVirtualMachineRequestRequestTypeDef,
 ):
     pass
 
+DeleteStorageVirtualMachineResponseTypeDef = TypedDict(
+    "DeleteStorageVirtualMachineResponseTypeDef",
+    {
+        "StorageVirtualMachineId": str,
+        "Lifecycle": StorageVirtualMachineLifecycleType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteVolumeOpenZFSConfigurationTypeDef = TypedDict(
     "DeleteVolumeOpenZFSConfigurationTypeDef",
     {
         "Options": Sequence[Literal["DELETE_CHILD_VOLUMES_AND_SNAPSHOTS"]],
     },
     total=False,
 )
@@ -629,24 +689,14 @@
     {
         "Name": FilterNameType,
         "Values": Sequence[str],
     },
     total=False,
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
 DescribeFileCachesRequestRequestTypeDef = TypedDict(
     "DescribeFileCachesRequestRequestTypeDef",
     {
         "FileCacheIds": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -671,24 +721,42 @@
 
 class DescribeFileSystemAliasesRequestRequestTypeDef(
     _RequiredDescribeFileSystemAliasesRequestRequestTypeDef,
     _OptionalDescribeFileSystemAliasesRequestRequestTypeDef,
 ):
     pass
 
+DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
+    {
+        "FileSystemIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeFileSystemsRequestRequestTypeDef = TypedDict(
     "DescribeFileSystemsRequestRequestTypeDef",
     {
         "FileSystemIds": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeFileSystemsResponseTypeDef = TypedDict(
+    "DescribeFileSystemsResponseTypeDef",
+    {
+        "FileSystems": List["FileSystemTypeDef"],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SnapshotFilterTypeDef = TypedDict(
     "SnapshotFilterTypeDef",
     {
         "Name": SnapshotFilterNameType,
         "Values": Sequence[str],
     },
     total=False,
@@ -800,14 +868,34 @@
     "LifecycleTransitionReasonTypeDef",
     {
         "Message": str,
     },
     total=False,
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -838,14 +926,24 @@
     {
         "SnapshotARN": str,
         "CopyStrategy": OpenZFSCopyStrategyType,
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
 _RequiredReleaseFileSystemNfsV3LocksRequestRequestTypeDef = TypedDict(
     "_RequiredReleaseFileSystemNfsV3LocksRequestRequestTypeDef",
     {
         "FileSystemId": str,
     },
 )
 _OptionalReleaseFileSystemNfsV3LocksRequestRequestTypeDef = TypedDict(
@@ -858,14 +956,33 @@
 
 class ReleaseFileSystemNfsV3LocksRequestRequestTypeDef(
     _RequiredReleaseFileSystemNfsV3LocksRequestRequestTypeDef,
     _OptionalReleaseFileSystemNfsV3LocksRequestRequestTypeDef,
 ):
     pass
 
+ReleaseFileSystemNfsV3LocksResponseTypeDef = TypedDict(
+    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
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
 _RequiredRestoreVolumeFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreVolumeFromSnapshotRequestRequestTypeDef",
     {
         "VolumeId": str,
         "SnapshotId": str,
     },
 )
@@ -880,14 +997,24 @@
 
 class RestoreVolumeFromSnapshotRequestRequestTypeDef(
     _RequiredRestoreVolumeFromSnapshotRequestRequestTypeDef,
     _OptionalRestoreVolumeFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
+RestoreVolumeFromSnapshotResponseTypeDef = TypedDict(
+    "RestoreVolumeFromSnapshotResponseTypeDef",
+    {
+        "VolumeId": str,
+        "Lifecycle": VolumeLifecycleType,
+        "AdministrativeActions": List["AdministrativeActionTypeDef"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SelfManagedActiveDirectoryAttributesTypeDef = TypedDict(
     "SelfManagedActiveDirectoryAttributesTypeDef",
     {
         "DomainName": str,
         "OrganizationalUnitDistinguishedName": str,
         "FileSystemAdministratorsGroup": str,
         "UserName": str,
@@ -898,14 +1025,17 @@
 
 SelfManagedActiveDirectoryConfigurationUpdatesTypeDef = TypedDict(
     "SelfManagedActiveDirectoryConfigurationUpdatesTypeDef",
     {
         "UserName": str,
         "Password": str,
         "DnsIps": Sequence[str],
+        "DomainName": str,
+        "OrganizationalUnitDistinguishedName": str,
+        "FileSystemAdministratorsGroup": str,
     },
     total=False,
 )
 
 SvmEndpointTypeDef = TypedDict(
     "SvmEndpointTypeDef",
     {
@@ -927,14 +1057,22 @@
     "UpdateFileCacheLustreConfigurationTypeDef",
     {
         "WeeklyMaintenanceStartTime": str,
     },
     total=False,
 )
 
+UpdateFileSystemResponseTypeDef = TypedDict(
+    "UpdateFileSystemResponseTypeDef",
+    {
+        "FileSystem": "FileSystemTypeDef",
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSnapshotRequestRequestTypeDef",
     {
         "Name": str,
         "SnapshotId": str,
     },
 )
@@ -971,138 +1109,32 @@
 ):
     pass
 
 AssociateFileSystemAliasesResponseTypeDef = TypedDict(
     "AssociateFileSystemAliasesResponseTypeDef",
     {
         "Aliases": List[AliasTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelDataRepositoryTaskResponseTypeDef = TypedDict(
-    "CancelDataRepositoryTaskResponseTypeDef",
-    {
-        "Lifecycle": DataRepositoryTaskLifecycleType,
-        "TaskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFileSystemFromBackupResponseTypeDef = TypedDict(
-    "CreateFileSystemFromBackupResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFileSystemResponseTypeDef = TypedDict(
-    "CreateFileSystemResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBackupResponseTypeDef = TypedDict(
-    "DeleteBackupResponseTypeDef",
-    {
-        "BackupId": str,
-        "Lifecycle": BackupLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDataRepositoryAssociationResponseTypeDef = TypedDict(
-    "DeleteDataRepositoryAssociationResponseTypeDef",
-    {
-        "AssociationId": str,
-        "Lifecycle": DataRepositoryLifecycleType,
-        "DeleteDataInFileSystem": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteFileCacheResponseTypeDef = TypedDict(
-    "DeleteFileCacheResponseTypeDef",
-    {
-        "FileCacheId": str,
-        "Lifecycle": FileCacheLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSnapshotResponseTypeDef = TypedDict(
-    "DeleteSnapshotResponseTypeDef",
-    {
-        "SnapshotId": str,
-        "Lifecycle": SnapshotLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteStorageVirtualMachineResponseTypeDef = TypedDict(
-    "DeleteStorageVirtualMachineResponseTypeDef",
-    {
-        "StorageVirtualMachineId": str,
-        "Lifecycle": StorageVirtualMachineLifecycleType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFileSystemAliasesResponseTypeDef = TypedDict(
     "DescribeFileSystemAliasesResponseTypeDef",
     {
         "Aliases": List[AliasTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFileSystemsResponseTypeDef = TypedDict(
-    "DescribeFileSystemsResponseTypeDef",
-    {
-        "FileSystems": List["FileSystemTypeDef"],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateFileSystemAliasesResponseTypeDef = TypedDict(
     "DisassociateFileSystemAliasesResponseTypeDef",
     {
         "Aliases": List[AliasTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReleaseFileSystemNfsV3LocksResponseTypeDef = TypedDict(
-    "ReleaseFileSystemNfsV3LocksResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreVolumeFromSnapshotResponseTypeDef = TypedDict(
-    "RestoreVolumeFromSnapshotResponseTypeDef",
-    {
-        "VolumeId": str,
-        "Lifecycle": VolumeLifecycleType,
-        "AdministrativeActions": List["AdministrativeActionTypeDef"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFileSystemResponseTypeDef = TypedDict(
-    "UpdateFileSystemResponseTypeDef",
-    {
-        "FileSystem": "FileSystemTypeDef",
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredNFSDataRepositoryConfigurationTypeDef = TypedDict(
     "_RequiredNFSDataRepositoryConfigurationTypeDef",
     {
         "Version": Literal["NFS3"],
@@ -1260,15 +1292,15 @@
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
@@ -1591,14 +1623,24 @@
 )
 
 class DataRepositoryTaskTypeDef(
     _RequiredDataRepositoryTaskTypeDef, _OptionalDataRepositoryTaskTypeDef
 ):
     pass
 
+DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
+    {
+        "BackupIds": Sequence[str],
+        "Filters": Sequence[FilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeBackupsRequestRequestTypeDef = TypedDict(
     "DescribeBackupsRequestRequestTypeDef",
     {
         "BackupIds": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
@@ -1613,53 +1655,14 @@
         "Filters": Sequence[FilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    {
-        "BackupIds": Sequence[str],
-        "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    {
-        "FileSystemIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
 DescribeSnapshotsRequestRequestTypeDef = TypedDict(
     "DescribeSnapshotsRequestRequestTypeDef",
     {
         "SnapshotIds": Sequence[str],
         "Filters": Sequence[SnapshotFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
@@ -1668,15 +1671,15 @@
 )
 
 DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef = TypedDict(
     "DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef",
     {
         "StorageVirtualMachineIds": Sequence[str],
         "Filters": Sequence[StorageVirtualMachineFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeStorageVirtualMachinesRequestRequestTypeDef = TypedDict(
     "DescribeStorageVirtualMachinesRequestRequestTypeDef",
     {
@@ -1689,15 +1692,15 @@
 )
 
 DescribeVolumesRequestDescribeVolumesPaginateTypeDef = TypedDict(
     "DescribeVolumesRequestDescribeVolumesPaginateTypeDef",
     {
         "VolumeIds": Sequence[str],
         "Filters": Sequence[VolumeFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeVolumesRequestRequestTypeDef = TypedDict(
     "DescribeVolumesRequestRequestTypeDef",
     {
@@ -1802,14 +1805,15 @@
 
 UpdateSvmActiveDirectoryConfigurationTypeDef = TypedDict(
     "UpdateSvmActiveDirectoryConfigurationTypeDef",
     {
         "SelfManagedActiveDirectoryConfiguration": (
             SelfManagedActiveDirectoryConfigurationUpdatesTypeDef
         ),
+        "NetBiosName": str,
     },
     total=False,
 )
 
 SvmEndpointsTypeDef = TypedDict(
     "SvmEndpointsTypeDef",
     {
@@ -1959,15 +1963,15 @@
     "DeleteFileSystemResponseTypeDef",
     {
         "FileSystemId": str,
         "Lifecycle": FileSystemLifecycleType,
         "WindowsResponse": DeleteFileSystemWindowsResponseTypeDef,
         "LustreResponse": DeleteFileSystemLustreResponseTypeDef,
         "OpenZFSResponse": DeleteFileSystemOpenZFSResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDeleteVolumeRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteVolumeRequestRequestTypeDef",
     {
         "VolumeId": str,
@@ -1990,15 +1994,15 @@
 
 DeleteVolumeResponseTypeDef = TypedDict(
     "DeleteVolumeResponseTypeDef",
     {
         "VolumeId": str,
         "Lifecycle": VolumeLifecycleType,
         "OntapResponse": DeleteVolumeOntapResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStorageVirtualMachineRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStorageVirtualMachineRequestRequestTypeDef",
     {
         "FileSystemId": str,
@@ -2065,24 +2069,24 @@
     total=False,
 )
 
 CreateDataRepositoryTaskResponseTypeDef = TypedDict(
     "CreateDataRepositoryTaskResponseTypeDef",
     {
         "DataRepositoryTask": DataRepositoryTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataRepositoryTasksResponseTypeDef = TypedDict(
     "DescribeDataRepositoryTasksResponseTypeDef",
     {
         "DataRepositoryTasks": List[DataRepositoryTaskTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFileCacheRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFileCacheRequestRequestTypeDef",
     {
         "FileCacheType": Literal["LUSTRE"],
@@ -2167,40 +2171,41 @@
         "EndpointIpAddressRange": str,
         "Endpoints": FileSystemEndpointsTypeDef,
         "DiskIopsConfiguration": DiskIopsConfigurationTypeDef,
         "PreferredSubnetId": str,
         "RouteTableIds": List[str],
         "ThroughputCapacity": int,
         "WeeklyMaintenanceStartTime": str,
+        "FsxAdminPassword": str,
     },
     total=False,
 )
 
 CreateSnapshotResponseTypeDef = TypedDict(
     "CreateSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSnapshotsResponseTypeDef = TypedDict(
     "DescribeSnapshotsResponseTypeDef",
     {
         "Snapshots": List[SnapshotTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSnapshotResponseTypeDef = TypedDict(
     "UpdateSnapshotResponseTypeDef",
     {
         "Snapshot": SnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateOpenZFSVolumeConfigurationTypeDef = TypedDict(
     "_RequiredCreateOpenZFSVolumeConfigurationTypeDef",
     {
         "ParentVolumeId": str,
@@ -2342,57 +2347,57 @@
     total=False,
 )
 
 CreateDataRepositoryAssociationResponseTypeDef = TypedDict(
     "CreateDataRepositoryAssociationResponseTypeDef",
     {
         "Association": DataRepositoryAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDataRepositoryAssociationsResponseTypeDef = TypedDict(
     "DescribeDataRepositoryAssociationsResponseTypeDef",
     {
         "Associations": List[DataRepositoryAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDataRepositoryAssociationResponseTypeDef = TypedDict(
     "UpdateDataRepositoryAssociationResponseTypeDef",
     {
         "Association": DataRepositoryAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFileCacheResponseTypeDef = TypedDict(
     "CreateFileCacheResponseTypeDef",
     {
         "FileCache": FileCacheCreatingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFileCachesResponseTypeDef = TypedDict(
     "DescribeFileCachesResponseTypeDef",
     {
         "FileCaches": List[FileCacheTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFileCacheResponseTypeDef = TypedDict(
     "UpdateFileCacheResponseTypeDef",
     {
         "FileCache": FileCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FileSystemTypeDef = TypedDict(
     "FileSystemTypeDef",
     {
         "OwnerId": str,
@@ -2511,32 +2516,32 @@
 ):
     pass
 
 CreateStorageVirtualMachineResponseTypeDef = TypedDict(
     "CreateStorageVirtualMachineResponseTypeDef",
     {
         "StorageVirtualMachine": StorageVirtualMachineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStorageVirtualMachinesResponseTypeDef = TypedDict(
     "DescribeStorageVirtualMachinesResponseTypeDef",
     {
         "StorageVirtualMachines": List[StorageVirtualMachineTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStorageVirtualMachineResponseTypeDef = TypedDict(
     "UpdateStorageVirtualMachineResponseTypeDef",
     {
         "StorageVirtualMachine": StorageVirtualMachineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFileSystemFromBackupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFileSystemFromBackupRequestRequestTypeDef",
     {
         "BackupId": str,
@@ -2642,60 +2647,60 @@
 class BackupTypeDef(_RequiredBackupTypeDef, _OptionalBackupTypeDef):
     pass
 
 CreateVolumeFromBackupResponseTypeDef = TypedDict(
     "CreateVolumeFromBackupResponseTypeDef",
     {
         "Volume": VolumeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVolumeResponseTypeDef = TypedDict(
     "CreateVolumeResponseTypeDef",
     {
         "Volume": VolumeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVolumesResponseTypeDef = TypedDict(
     "DescribeVolumesResponseTypeDef",
     {
         "Volumes": List[VolumeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVolumeResponseTypeDef = TypedDict(
     "UpdateVolumeResponseTypeDef",
     {
         "Volume": VolumeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopyBackupResponseTypeDef = TypedDict(
     "CopyBackupResponseTypeDef",
     {
         "Backup": BackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBackupResponseTypeDef = TypedDict(
     "CreateBackupResponseTypeDef",
     {
         "Backup": BackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBackupsResponseTypeDef = TypedDict(
     "DescribeBackupsResponseTypeDef",
     {
         "Backups": List[BackupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/PKG-INFO` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-fsx
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FSx 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FSx 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-fsx"></a>
 
 # types-aiobotocore-fsx
 
 [![PyPI - types-aiobotocore-fsx](https://img.shields.io/pypi/v/types-aiobotocore-fsx.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fsx)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fsx.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fsx)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fsx?color=blue)](https://pypistats.org/packages/types-aiobotocore-fsx)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FSx 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
+[aiobotocore.FSx 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fsx.html#FSx)
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
 [types-aiobotocore-fsx docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fsx/).
 
 See how it helps to find and fix potential bugs:
 
@@ -388,82 +388,84 @@
 
 ```python
 from types_aiobotocore_fsx.type_defs import (
     ActiveDirectoryBackupAttributesTypeDef,
     AdministrativeActionFailureDetailsTypeDef,
     AliasTypeDef,
     AssociateFileSystemAliasesRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AutoExportPolicyTypeDef,
     AutoImportPolicyTypeDef,
     BackupFailureDetailsTypeDef,
     TagTypeDef,
     CancelDataRepositoryTaskRequestRequestTypeDef,
+    CancelDataRepositoryTaskResponseTypeDef,
     CompletionReportTypeDef,
     FileCacheLustreMetadataConfigurationTypeDef,
+    CreateFileSystemFromBackupResponseTypeDef,
     LustreLogCreateConfigurationTypeDef,
     LustreRootSquashConfigurationTypeDef,
     DiskIopsConfigurationTypeDef,
+    CreateFileSystemResponseTypeDef,
     SelfManagedActiveDirectoryConfigurationTypeDef,
     WindowsAuditLogCreateConfigurationTypeDef,
     TieringPolicyTypeDef,
     CreateOpenZFSOriginSnapshotConfigurationTypeDef,
     OpenZFSUserOrGroupQuotaTypeDef,
     DataRepositoryFailureDetailsTypeDef,
     DataRepositoryTaskFailureDetailsTypeDef,
     DataRepositoryTaskFilterTypeDef,
     DataRepositoryTaskStatusTypeDef,
     DeleteBackupRequestRequestTypeDef,
+    DeleteBackupResponseTypeDef,
     DeleteDataRepositoryAssociationRequestRequestTypeDef,
+    DeleteDataRepositoryAssociationResponseTypeDef,
     DeleteFileCacheRequestRequestTypeDef,
+    DeleteFileCacheResponseTypeDef,
     DeleteSnapshotRequestRequestTypeDef,
+    DeleteSnapshotResponseTypeDef,
     DeleteStorageVirtualMachineRequestRequestTypeDef,
+    DeleteStorageVirtualMachineResponseTypeDef,
     DeleteVolumeOpenZFSConfigurationTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     DescribeFileCachesRequestRequestTypeDef,
     DescribeFileSystemAliasesRequestRequestTypeDef,
+    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
     DescribeFileSystemsRequestRequestTypeDef,
+    DescribeFileSystemsResponseTypeDef,
     SnapshotFilterTypeDef,
     StorageVirtualMachineFilterTypeDef,
     VolumeFilterTypeDef,
     DisassociateFileSystemAliasesRequestRequestTypeDef,
     FileCacheFailureDetailsTypeDef,
     FileCacheNFSConfigurationTypeDef,
     LustreLogConfigurationTypeDef,
     FileSystemEndpointTypeDef,
     FileSystemFailureDetailsTypeDef,
     LifecycleTransitionReasonTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OpenZFSClientConfigurationTypeDef,
     OpenZFSOriginSnapshotConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     ReleaseFileSystemNfsV3LocksRequestRequestTypeDef,
+    ReleaseFileSystemNfsV3LocksResponseTypeDef,
+    ResponseMetadataTypeDef,
     RestoreVolumeFromSnapshotRequestRequestTypeDef,
+    RestoreVolumeFromSnapshotResponseTypeDef,
     SelfManagedActiveDirectoryAttributesTypeDef,
     SelfManagedActiveDirectoryConfigurationUpdatesTypeDef,
     SvmEndpointTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFileCacheLustreConfigurationTypeDef,
+    UpdateFileSystemResponseTypeDef,
     UpdateSnapshotRequestRequestTypeDef,
     WindowsAuditLogConfigurationTypeDef,
     AssociateFileSystemAliasesResponseTypeDef,
-    CancelDataRepositoryTaskResponseTypeDef,
-    CreateFileSystemFromBackupResponseTypeDef,
-    CreateFileSystemResponseTypeDef,
-    DeleteBackupResponseTypeDef,
-    DeleteDataRepositoryAssociationResponseTypeDef,
-    DeleteFileCacheResponseTypeDef,
-    DeleteSnapshotResponseTypeDef,
-    DeleteStorageVirtualMachineResponseTypeDef,
     DescribeFileSystemAliasesResponseTypeDef,
-    DescribeFileSystemsResponseTypeDef,
     DisassociateFileSystemAliasesResponseTypeDef,
-    ReleaseFileSystemNfsV3LocksResponseTypeDef,
-    RestoreVolumeFromSnapshotResponseTypeDef,
-    UpdateFileSystemResponseTypeDef,
     NFSDataRepositoryConfigurationTypeDef,
     S3DataRepositoryConfigurationTypeDef,
     CopyBackupRequestRequestTypeDef,
     CreateBackupRequestRequestTypeDef,
     CreateSnapshotRequestRequestTypeDef,
     DeleteFileSystemLustreConfigurationTypeDef,
     DeleteFileSystemLustreResponseTypeDef,
@@ -487,19 +489,17 @@
     CreateFileSystemWindowsConfigurationTypeDef,
     CreateOntapVolumeConfigurationTypeDef,
     OntapVolumeConfigurationTypeDef,
     UpdateOntapVolumeConfigurationTypeDef,
     DataRepositoryConfigurationTypeDef,
     DescribeDataRepositoryTasksRequestRequestTypeDef,
     DataRepositoryTaskTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
     DescribeDataRepositoryAssociationsRequestRequestTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeSnapshotsRequestRequestTypeDef,
     DescribeStorageVirtualMachinesRequestDescribeStorageVirtualMachinesPaginateTypeDef,
     DescribeStorageVirtualMachinesRequestRequestTypeDef,
     DescribeVolumesRequestDescribeVolumesPaginateTypeDef,
     DescribeVolumesRequestRequestTypeDef,
     FileCacheDataRepositoryAssociationTypeDef,
     FileCacheLustreConfigurationTypeDef,
@@ -573,43 +573,43 @@
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

### Comparing `types-aiobotocore-fsx-2.5.0.post1/types_aiobotocore_fsx.egg-info/SOURCES.txt` & `types-aiobotocore-fsx-2.5.1/types_aiobotocore_fsx.egg-info/SOURCES.txt`

 * *Files identical despite different names*

