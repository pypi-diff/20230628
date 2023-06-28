# Comparing `tmp/types-aiobotocore-efs-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-efs-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-efs-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-efs-2.5.1.tar", last modified: Wed Jun 28 01:43:26 2023, max compression
```

## Comparing `types-aiobotocore-efs-2.5.0.post1.tar` & `types-aiobotocore-efs-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.411172 types-aiobotocore-efs-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16045 2023-03-11 12:26:34.411172 types-aiobotocore-efs-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14490 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.411172 types-aiobotocore-efs-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.411172 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/
--rw-r--r--   0 runner    (1001) docker     (123)     1077 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1076 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25287 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    25245 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9233 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9231 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4450 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4444 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    24246 2023-03-11 12:13:56.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    24217 2023-03-11 12:13:56.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:13:55.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.411172 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16045 2023-03-11 12:26:34.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:34.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:34.000000 types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.926132 types-aiobotocore-efs-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16033 2023-06-28 01:43:26.926132 types-aiobotocore-efs-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14484 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:26.926132 types-aiobotocore-efs-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.918132 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/
+-rw-r--r--   0 runner    (1001) docker     (123)     1077 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1076 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25287 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25245 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9485 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9483 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4336 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4331 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    24286 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24257 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:32.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.926132 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16033 2023-06-28 01:43:26.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:26.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:26.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:26.000000 types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-efs-2.5.0.post1/LICENSE` & `types-aiobotocore-efs-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-efs-2.5.0.post1/PKG-INFO` & `types-aiobotocore-efs-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-efs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EFS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EFS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-efs"></a>
 
 # types-aiobotocore-efs
 
 [![PyPI - types-aiobotocore-efs](https://img.shields.io/pypi/v/types-aiobotocore-efs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-efs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-efs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-efs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-efs?color=blue)](https://pypistats.org/packages/types-aiobotocore-efs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EFS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS)
+[aiobotocore.EFS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS)
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
 [types-aiobotocore-efs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,15 +334,14 @@
 
 `types_aiobotocore_efs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_efs.type_defs import (
     PosixUserTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     BackupPolicyTypeDef,
     CreateMountTargetRequestRequestTypeDef,
     DestinationToCreateTypeDef,
     CreationInfoTypeDef,
     DeleteAccessPointRequestRequestTypeDef,
     DeleteFileSystemPolicyRequestRequestTypeDef,
@@ -351,49 +350,50 @@
     DeleteReplicationConfigurationRequestRequestTypeDef,
     DeleteTagsRequestRequestTypeDef,
     DescribeAccessPointsRequestRequestTypeDef,
     DescribeAccountPreferencesRequestRequestTypeDef,
     ResourceIdPreferenceTypeDef,
     DescribeBackupPolicyRequestRequestTypeDef,
     DescribeFileSystemPolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
     DescribeFileSystemsRequestRequestTypeDef,
     DescribeLifecycleConfigurationRequestRequestTypeDef,
     DescribeMountTargetSecurityGroupsRequestRequestTypeDef,
+    DescribeMountTargetSecurityGroupsResponseTypeDef,
+    DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef,
     DescribeMountTargetsRequestRequestTypeDef,
     MountTargetDescriptionTypeDef,
     DescribeReplicationConfigurationsRequestRequestTypeDef,
+    DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeTagsRequestRequestTypeDef,
     DestinationTypeDef,
+    EmptyResponseMetadataTypeDef,
     FileSystemSizeTypeDef,
+    FileSystemPolicyDescriptionTypeDef,
     LifecyclePolicyTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModifyMountTargetSecurityGroupsRequestRequestTypeDef,
+    MountTargetDescriptionResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
     PutAccountPreferencesRequestRequestTypeDef,
     PutFileSystemPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFileSystemRequestRequestTypeDef,
-    DescribeMountTargetSecurityGroupsResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    FileSystemPolicyDescriptionTypeDef,
-    MountTargetDescriptionResponseMetadataTypeDef,
     CreateFileSystemRequestRequestTypeDef,
     CreateTagsRequestRequestTypeDef,
     DescribeTagsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     BackupPolicyDescriptionTypeDef,
     PutBackupPolicyRequestRequestTypeDef,
     CreateReplicationConfigurationRequestRequestTypeDef,
     RootDirectoryTypeDef,
     DescribeAccountPreferencesResponseTypeDef,
     PutAccountPreferencesResponseTypeDef,
-    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
-    DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef,
-    DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeMountTargetsResponseTypeDef,
     ReplicationConfigurationDescriptionResponseMetadataTypeDef,
     ReplicationConfigurationDescriptionTypeDef,
     FileSystemDescriptionResponseMetadataTypeDef,
     FileSystemDescriptionTypeDef,
     LifecycleConfigurationDescriptionTypeDef,
     PutLifecycleConfigurationRequestRequestTypeDef,
@@ -413,43 +413,43 @@
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

### Comparing `types-aiobotocore-efs-2.5.0.post1/README.md` & `types-aiobotocore-efs-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-efs"></a>
 
 # types-aiobotocore-efs
 
 [![PyPI - types-aiobotocore-efs](https://img.shields.io/pypi/v/types-aiobotocore-efs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-efs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-efs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-efs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-efs?color=blue)](https://pypistats.org/packages/types-aiobotocore-efs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EFS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS)
+[aiobotocore.EFS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS)
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
 [types-aiobotocore-efs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -301,15 +301,14 @@
 
 `types_aiobotocore_efs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_efs.type_defs import (
     PosixUserTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     BackupPolicyTypeDef,
     CreateMountTargetRequestRequestTypeDef,
     DestinationToCreateTypeDef,
     CreationInfoTypeDef,
     DeleteAccessPointRequestRequestTypeDef,
     DeleteFileSystemPolicyRequestRequestTypeDef,
@@ -318,49 +317,50 @@
     DeleteReplicationConfigurationRequestRequestTypeDef,
     DeleteTagsRequestRequestTypeDef,
     DescribeAccessPointsRequestRequestTypeDef,
     DescribeAccountPreferencesRequestRequestTypeDef,
     ResourceIdPreferenceTypeDef,
     DescribeBackupPolicyRequestRequestTypeDef,
     DescribeFileSystemPolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
     DescribeFileSystemsRequestRequestTypeDef,
     DescribeLifecycleConfigurationRequestRequestTypeDef,
     DescribeMountTargetSecurityGroupsRequestRequestTypeDef,
+    DescribeMountTargetSecurityGroupsResponseTypeDef,
+    DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef,
     DescribeMountTargetsRequestRequestTypeDef,
     MountTargetDescriptionTypeDef,
     DescribeReplicationConfigurationsRequestRequestTypeDef,
+    DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeTagsRequestRequestTypeDef,
     DestinationTypeDef,
+    EmptyResponseMetadataTypeDef,
     FileSystemSizeTypeDef,
+    FileSystemPolicyDescriptionTypeDef,
     LifecyclePolicyTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModifyMountTargetSecurityGroupsRequestRequestTypeDef,
+    MountTargetDescriptionResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
     PutAccountPreferencesRequestRequestTypeDef,
     PutFileSystemPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFileSystemRequestRequestTypeDef,
-    DescribeMountTargetSecurityGroupsResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    FileSystemPolicyDescriptionTypeDef,
-    MountTargetDescriptionResponseMetadataTypeDef,
     CreateFileSystemRequestRequestTypeDef,
     CreateTagsRequestRequestTypeDef,
     DescribeTagsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     BackupPolicyDescriptionTypeDef,
     PutBackupPolicyRequestRequestTypeDef,
     CreateReplicationConfigurationRequestRequestTypeDef,
     RootDirectoryTypeDef,
     DescribeAccountPreferencesResponseTypeDef,
     PutAccountPreferencesResponseTypeDef,
-    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
-    DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef,
-    DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeMountTargetsResponseTypeDef,
     ReplicationConfigurationDescriptionResponseMetadataTypeDef,
     ReplicationConfigurationDescriptionTypeDef,
     FileSystemDescriptionResponseMetadataTypeDef,
     FileSystemDescriptionTypeDef,
     LifecycleConfigurationDescriptionTypeDef,
     PutLifecycleConfigurationRequestRequestTypeDef,
@@ -380,43 +380,43 @@
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

### Comparing `types-aiobotocore-efs-2.5.0.post1/setup.py` & `types-aiobotocore-efs-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-efs.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-efs",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_efs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EFS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.EFS 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/",
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

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/__init__.py` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/__init__.pyi` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/__main__.py` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EFS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EFS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS\nOther"
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

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/client.py` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/client.pyi` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/literals.py` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -41,15 +41,15 @@
 
 
 DescribeFileSystemsPaginatorName = Literal["describe_file_systems"]
 DescribeMountTargetsPaginatorName = Literal["describe_mount_targets"]
 DescribeTagsPaginatorName = Literal["describe_tags"]
 LifeCycleStateType = Literal["available", "creating", "deleted", "deleting", "error", "updating"]
 PerformanceModeType = Literal["generalPurpose", "maxIO"]
-ReplicationStatusType = Literal["DELETING", "ENABLED", "ENABLING", "ERROR"]
+ReplicationStatusType = Literal["DELETING", "ENABLED", "ENABLING", "ERROR", "PAUSED", "PAUSING"]
 ResourceIdTypeType = Literal["LONG_ID", "SHORT_ID"]
 ResourceType = Literal["FILE_SYSTEM", "MOUNT_TARGET"]
 StatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLING"]
 ThroughputModeType = Literal["bursting", "elastic", "provisioned"]
 TransitionToIARulesType = Literal[
     "AFTER_14_DAYS",
     "AFTER_1_DAY",
@@ -118,14 +118,15 @@
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
@@ -204,14 +205,15 @@
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
@@ -222,14 +224,15 @@
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
@@ -265,14 +268,15 @@
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
@@ -291,16 +295,19 @@
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
@@ -384,15 +391,17 @@
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
@@ -422,14 +431,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/literals.pyi` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -39,15 +39,15 @@
 )
 
 DescribeFileSystemsPaginatorName = Literal["describe_file_systems"]
 DescribeMountTargetsPaginatorName = Literal["describe_mount_targets"]
 DescribeTagsPaginatorName = Literal["describe_tags"]
 LifeCycleStateType = Literal["available", "creating", "deleted", "deleting", "error", "updating"]
 PerformanceModeType = Literal["generalPurpose", "maxIO"]
-ReplicationStatusType = Literal["DELETING", "ENABLED", "ENABLING", "ERROR"]
+ReplicationStatusType = Literal["DELETING", "ENABLED", "ENABLING", "ERROR", "PAUSED", "PAUSING"]
 ResourceIdTypeType = Literal["LONG_ID", "SHORT_ID"]
 ResourceType = Literal["FILE_SYSTEM", "MOUNT_TARGET"]
 StatusType = Literal["DISABLED", "DISABLING", "ENABLED", "ENABLING"]
 ThroughputModeType = Literal["bursting", "elastic", "provisioned"]
 TransitionToIARulesType = Literal[
     "AFTER_14_DAYS",
     "AFTER_1_DAY",
@@ -116,14 +116,15 @@
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
@@ -202,14 +203,15 @@
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
@@ -220,14 +222,15 @@
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
@@ -263,14 +266,15 @@
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
@@ -289,16 +293,19 @@
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
@@ -382,15 +389,17 @@
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
@@ -420,14 +429,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/paginator.py` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: EFSClient
 
         describe_file_systems_paginator: DescribeFileSystemsPaginator = client.get_paginator("describe_file_systems")
         describe_mount_targets_paginator: DescribeMountTargetsPaginator = client.get_paginator("describe_mount_targets")
         describe_tags_paginator: DescribeTagsPaginator = client.get_paginator("describe_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeFileSystemsResponseTypeDef,
     DescribeMountTargetsResponseTypeDef,
     DescribeTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeFileSystemsPaginator", "DescribeMountTargetsPaginator", "DescribeTagsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -63,15 +56,15 @@
     """
 
     def paginate(
         self,
         *,
         CreationToken: str = ...,
         FileSystemId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFileSystemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeFileSystems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describefilesystemspaginator)
         """
 
 
@@ -83,28 +76,28 @@
 
     def paginate(
         self,
         *,
         FileSystemId: str = ...,
         MountTargetId: str = ...,
         AccessPointId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMountTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeMountTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describemounttargetspaginator)
         """
 
 
 class DescribeTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describetagspaginator)
     """
 
     def paginate(
-        self, *, FileSystemId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FileSystemId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describetagspaginator)
         """
```

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/paginator.pyi` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/paginator.pyi`

 * *Files 14% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: EFSClient
 
         describe_file_systems_paginator: DescribeFileSystemsPaginator = client.get_paginator("describe_file_systems")
         describe_mount_targets_paginator: DescribeMountTargetsPaginator = client.get_paginator("describe_mount_targets")
         describe_tags_paginator: DescribeTagsPaginator = client.get_paginator("describe_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeFileSystemsResponseTypeDef,
     DescribeMountTargetsResponseTypeDef,
     DescribeTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeFileSystemsPaginator", "DescribeMountTargetsPaginator", "DescribeTagsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -59,15 +53,15 @@
     """
 
     def paginate(
         self,
         *,
         CreationToken: str = ...,
         FileSystemId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFileSystemsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeFileSystems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describefilesystemspaginator)
         """
 
 class DescribeMountTargetsPaginator(AioPaginator):
@@ -78,27 +72,27 @@
 
     def paginate(
         self,
         *,
         FileSystemId: str = ...,
         MountTargetId: str = ...,
         AccessPointId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMountTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeMountTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describemounttargetspaginator)
         """
 
 class DescribeTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describetagspaginator)
     """
 
     def paginate(
-        self, *, FileSystemId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FileSystemId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS.Paginator.DescribeTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/paginators/#describetagspaginator)
         """
```

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/type_defs.py` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,15 +34,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "PosixUserTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "BackupPolicyTypeDef",
     "CreateMountTargetRequestRequestTypeDef",
     "DestinationToCreateTypeDef",
     "CreationInfoTypeDef",
     "DeleteAccessPointRequestRequestTypeDef",
     "DeleteFileSystemPolicyRequestRequestTypeDef",
@@ -51,49 +50,50 @@
     "DeleteReplicationConfigurationRequestRequestTypeDef",
     "DeleteTagsRequestRequestTypeDef",
     "DescribeAccessPointsRequestRequestTypeDef",
     "DescribeAccountPreferencesRequestRequestTypeDef",
     "ResourceIdPreferenceTypeDef",
     "DescribeBackupPolicyRequestRequestTypeDef",
     "DescribeFileSystemPolicyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
     "DescribeFileSystemsRequestRequestTypeDef",
     "DescribeLifecycleConfigurationRequestRequestTypeDef",
     "DescribeMountTargetSecurityGroupsRequestRequestTypeDef",
+    "DescribeMountTargetSecurityGroupsResponseTypeDef",
+    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
     "DescribeMountTargetsRequestRequestTypeDef",
     "MountTargetDescriptionTypeDef",
     "DescribeReplicationConfigurationsRequestRequestTypeDef",
+    "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     "DescribeTagsRequestRequestTypeDef",
     "DestinationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FileSystemSizeTypeDef",
+    "FileSystemPolicyDescriptionTypeDef",
     "LifecyclePolicyTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ModifyMountTargetSecurityGroupsRequestRequestTypeDef",
+    "MountTargetDescriptionResponseMetadataTypeDef",
+    "PaginatorConfigTypeDef",
     "PutAccountPreferencesRequestRequestTypeDef",
     "PutFileSystemPolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFileSystemRequestRequestTypeDef",
-    "DescribeMountTargetSecurityGroupsResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "FileSystemPolicyDescriptionTypeDef",
-    "MountTargetDescriptionResponseMetadataTypeDef",
     "CreateFileSystemRequestRequestTypeDef",
     "CreateTagsRequestRequestTypeDef",
     "DescribeTagsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "BackupPolicyDescriptionTypeDef",
     "PutBackupPolicyRequestRequestTypeDef",
     "CreateReplicationConfigurationRequestRequestTypeDef",
     "RootDirectoryTypeDef",
     "DescribeAccountPreferencesResponseTypeDef",
     "PutAccountPreferencesResponseTypeDef",
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
-    "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     "DescribeMountTargetsResponseTypeDef",
     "ReplicationConfigurationDescriptionResponseMetadataTypeDef",
     "ReplicationConfigurationDescriptionTypeDef",
     "FileSystemDescriptionResponseMetadataTypeDef",
     "FileSystemDescriptionTypeDef",
     "LifecycleConfigurationDescriptionTypeDef",
     "PutLifecycleConfigurationRequestRequestTypeDef",
@@ -121,25 +121,14 @@
 )
 
 
 class PosixUserTypeDef(_RequiredPosixUserTypeDef, _OptionalPosixUserTypeDef):
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -275,20 +264,20 @@
 DescribeFileSystemPolicyRequestRequestTypeDef = TypedDict(
     "DescribeFileSystemPolicyRequestRequestTypeDef",
     {
         "FileSystemId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CreationToken": str,
+        "FileSystemId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeFileSystemsRequestRequestTypeDef = TypedDict(
     "DescribeFileSystemsRequestRequestTypeDef",
     {
@@ -310,14 +299,33 @@
 DescribeMountTargetSecurityGroupsRequestRequestTypeDef = TypedDict(
     "DescribeMountTargetSecurityGroupsRequestRequestTypeDef",
     {
         "MountTargetId": str,
     },
 )
 
+DescribeMountTargetSecurityGroupsResponseTypeDef = TypedDict(
+    "DescribeMountTargetSecurityGroupsResponseTypeDef",
+    {
+        "SecurityGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef = TypedDict(
+    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
+    {
+        "FileSystemId": str,
+        "MountTargetId": str,
+        "AccessPointId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMountTargetsRequestRequestTypeDef = TypedDict(
     "DescribeMountTargetsRequestRequestTypeDef",
     {
         "MaxItems": int,
         "Marker": str,
         "FileSystemId": str,
         "MountTargetId": str,
@@ -361,14 +369,36 @@
         "FileSystemId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef",
+    {
+        "FileSystemId": str,
+    },
+)
+_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeTagsRequestDescribeTagsPaginateTypeDef(
+    _RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef,
+    _OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeTagsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeTagsRequestRequestTypeDef",
     {
         "FileSystemId": str,
     },
 )
 _OptionalDescribeTagsRequestRequestTypeDef = TypedDict(
@@ -404,14 +434,21 @@
 )
 
 
 class DestinationTypeDef(_RequiredDestinationTypeDef, _OptionalDestinationTypeDef):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFileSystemSizeTypeDef = TypedDict(
     "_RequiredFileSystemSizeTypeDef",
     {
         "Value": int,
     },
 )
 _OptionalFileSystemSizeTypeDef = TypedDict(
@@ -425,14 +462,23 @@
 )
 
 
 class FileSystemSizeTypeDef(_RequiredFileSystemSizeTypeDef, _OptionalFileSystemSizeTypeDef):
     pass
 
 
+FileSystemPolicyDescriptionTypeDef = TypedDict(
+    "FileSystemPolicyDescriptionTypeDef",
+    {
+        "FileSystemId": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecyclePolicyTypeDef = TypedDict(
     "LifecyclePolicyTypeDef",
     {
         "TransitionToIA": TransitionToIARulesType,
         "TransitionToPrimaryStorageClass": Literal["AFTER_1_ACCESS"],
     },
     total=False,
@@ -479,14 +525,41 @@
 class ModifyMountTargetSecurityGroupsRequestRequestTypeDef(
     _RequiredModifyMountTargetSecurityGroupsRequestRequestTypeDef,
     _OptionalModifyMountTargetSecurityGroupsRequestRequestTypeDef,
 ):
     pass
 
 
+MountTargetDescriptionResponseMetadataTypeDef = TypedDict(
+    "MountTargetDescriptionResponseMetadataTypeDef",
+    {
+        "OwnerId": str,
+        "MountTargetId": str,
+        "FileSystemId": str,
+        "SubnetId": str,
+        "LifeCycleState": LifeCycleStateType,
+        "IpAddress": str,
+        "NetworkInterfaceId": str,
+        "AvailabilityZoneId": str,
+        "AvailabilityZoneName": str,
+        "VpcId": str,
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
 PutAccountPreferencesRequestRequestTypeDef = TypedDict(
     "PutAccountPreferencesRequestRequestTypeDef",
     {
         "ResourceIdType": ResourceIdTypeType,
     },
 )
 
@@ -509,14 +582,25 @@
 class PutFileSystemPolicyRequestRequestTypeDef(
     _RequiredPutFileSystemPolicyRequestRequestTypeDef,
     _OptionalPutFileSystemPolicyRequestRequestTypeDef,
 ):
     pass
 
 
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -539,55 +623,14 @@
 
 class UpdateFileSystemRequestRequestTypeDef(
     _RequiredUpdateFileSystemRequestRequestTypeDef, _OptionalUpdateFileSystemRequestRequestTypeDef
 ):
     pass
 
 
-DescribeMountTargetSecurityGroupsResponseTypeDef = TypedDict(
-    "DescribeMountTargetSecurityGroupsResponseTypeDef",
-    {
-        "SecurityGroups": List[str],
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
-FileSystemPolicyDescriptionTypeDef = TypedDict(
-    "FileSystemPolicyDescriptionTypeDef",
-    {
-        "FileSystemId": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-MountTargetDescriptionResponseMetadataTypeDef = TypedDict(
-    "MountTargetDescriptionResponseMetadataTypeDef",
-    {
-        "OwnerId": str,
-        "MountTargetId": str,
-        "FileSystemId": str,
-        "SubnetId": str,
-        "LifeCycleState": LifeCycleStateType,
-        "IpAddress": str,
-        "NetworkInterfaceId": str,
-        "AvailabilityZoneId": str,
-        "AvailabilityZoneName": str,
-        "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateFileSystemRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFileSystemRequestRequestTypeDef",
     {
         "CreationToken": str,
     },
 )
 _OptionalCreateFileSystemRequestRequestTypeDef = TypedDict(
@@ -622,24 +665,24 @@
 
 DescribeTagsResponseTypeDef = TypedDict(
     "DescribeTagsResponseTypeDef",
     {
         "Marker": str,
         "Tags": List[TagTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
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
         "ResourceId": str,
@@ -647,15 +690,15 @@
     },
 )
 
 BackupPolicyDescriptionTypeDef = TypedDict(
     "BackupPolicyDescriptionTypeDef",
     {
         "BackupPolicy": BackupPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBackupPolicyRequestRequestTypeDef = TypedDict(
     "PutBackupPolicyRequestRequestTypeDef",
     {
         "FileSystemId": str,
@@ -681,89 +724,46 @@
 )
 
 DescribeAccountPreferencesResponseTypeDef = TypedDict(
     "DescribeAccountPreferencesResponseTypeDef",
     {
         "ResourceIdPreference": ResourceIdPreferenceTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountPreferencesResponseTypeDef = TypedDict(
     "PutAccountPreferencesResponseTypeDef",
     {
         "ResourceIdPreference": ResourceIdPreferenceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    {
-        "CreationToken": str,
-        "FileSystemId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef = TypedDict(
-    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
-    {
-        "FileSystemId": str,
-        "MountTargetId": str,
-        "AccessPointId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef",
-    {
-        "FileSystemId": str,
-    },
-)
-_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeTagsRequestDescribeTagsPaginateTypeDef(
-    _RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef,
-    _OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef,
-):
-    pass
-
-
 DescribeMountTargetsResponseTypeDef = TypedDict(
     "DescribeMountTargetsResponseTypeDef",
     {
         "Marker": str,
         "MountTargets": List[MountTargetDescriptionTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationConfigurationDescriptionResponseMetadataTypeDef = TypedDict(
     "ReplicationConfigurationDescriptionResponseMetadataTypeDef",
     {
         "SourceFileSystemId": str,
         "SourceFileSystemRegion": str,
         "SourceFileSystemArn": str,
         "OriginalSourceFileSystemArn": str,
         "CreationTime": datetime,
         "Destinations": List[DestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationConfigurationDescriptionTypeDef = TypedDict(
     "ReplicationConfigurationDescriptionTypeDef",
     {
         "SourceFileSystemId": str,
@@ -791,15 +791,15 @@
         "Encrypted": bool,
         "KmsKeyId": str,
         "ThroughputMode": ThroughputModeType,
         "ProvisionedThroughputInMibps": float,
         "AvailabilityZoneName": str,
         "AvailabilityZoneId": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFileSystemDescriptionTypeDef = TypedDict(
     "_RequiredFileSystemDescriptionTypeDef",
     {
         "OwnerId": str,
@@ -835,15 +835,15 @@
     pass
 
 
 LifecycleConfigurationDescriptionTypeDef = TypedDict(
     "LifecycleConfigurationDescriptionTypeDef",
     {
         "LifecyclePolicies": List[LifecyclePolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLifecycleConfigurationRequestRequestTypeDef = TypedDict(
     "PutLifecycleConfigurationRequestRequestTypeDef",
     {
         "FileSystemId": str,
@@ -860,15 +860,15 @@
         "AccessPointId": str,
         "AccessPointArn": str,
         "FileSystemId": str,
         "PosixUser": PosixUserTypeDef,
         "RootDirectory": RootDirectoryTypeDef,
         "OwnerId": str,
         "LifeCycleState": LifeCycleStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AccessPointDescriptionTypeDef = TypedDict(
     "AccessPointDescriptionTypeDef",
     {
         "ClientToken": str,
@@ -910,29 +910,29 @@
 
 
 DescribeReplicationConfigurationsResponseTypeDef = TypedDict(
     "DescribeReplicationConfigurationsResponseTypeDef",
     {
         "Replications": List[ReplicationConfigurationDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFileSystemsResponseTypeDef = TypedDict(
     "DescribeFileSystemsResponseTypeDef",
     {
         "Marker": str,
         "FileSystems": List[FileSystemDescriptionTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccessPointsResponseTypeDef = TypedDict(
     "DescribeAccessPointsResponseTypeDef",
     {
         "AccessPoints": List[AccessPointDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs/type_defs.pyi` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -33,15 +33,14 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "PosixUserTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
     "BackupPolicyTypeDef",
     "CreateMountTargetRequestRequestTypeDef",
     "DestinationToCreateTypeDef",
     "CreationInfoTypeDef",
     "DeleteAccessPointRequestRequestTypeDef",
     "DeleteFileSystemPolicyRequestRequestTypeDef",
@@ -50,49 +49,50 @@
     "DeleteReplicationConfigurationRequestRequestTypeDef",
     "DeleteTagsRequestRequestTypeDef",
     "DescribeAccessPointsRequestRequestTypeDef",
     "DescribeAccountPreferencesRequestRequestTypeDef",
     "ResourceIdPreferenceTypeDef",
     "DescribeBackupPolicyRequestRequestTypeDef",
     "DescribeFileSystemPolicyRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
     "DescribeFileSystemsRequestRequestTypeDef",
     "DescribeLifecycleConfigurationRequestRequestTypeDef",
     "DescribeMountTargetSecurityGroupsRequestRequestTypeDef",
+    "DescribeMountTargetSecurityGroupsResponseTypeDef",
+    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
     "DescribeMountTargetsRequestRequestTypeDef",
     "MountTargetDescriptionTypeDef",
     "DescribeReplicationConfigurationsRequestRequestTypeDef",
+    "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     "DescribeTagsRequestRequestTypeDef",
     "DestinationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FileSystemSizeTypeDef",
+    "FileSystemPolicyDescriptionTypeDef",
     "LifecyclePolicyTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ModifyMountTargetSecurityGroupsRequestRequestTypeDef",
+    "MountTargetDescriptionResponseMetadataTypeDef",
+    "PaginatorConfigTypeDef",
     "PutAccountPreferencesRequestRequestTypeDef",
     "PutFileSystemPolicyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFileSystemRequestRequestTypeDef",
-    "DescribeMountTargetSecurityGroupsResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "FileSystemPolicyDescriptionTypeDef",
-    "MountTargetDescriptionResponseMetadataTypeDef",
     "CreateFileSystemRequestRequestTypeDef",
     "CreateTagsRequestRequestTypeDef",
     "DescribeTagsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "BackupPolicyDescriptionTypeDef",
     "PutBackupPolicyRequestRequestTypeDef",
     "CreateReplicationConfigurationRequestRequestTypeDef",
     "RootDirectoryTypeDef",
     "DescribeAccountPreferencesResponseTypeDef",
     "PutAccountPreferencesResponseTypeDef",
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
-    "DescribeTagsRequestDescribeTagsPaginateTypeDef",
     "DescribeMountTargetsResponseTypeDef",
     "ReplicationConfigurationDescriptionResponseMetadataTypeDef",
     "ReplicationConfigurationDescriptionTypeDef",
     "FileSystemDescriptionResponseMetadataTypeDef",
     "FileSystemDescriptionTypeDef",
     "LifecycleConfigurationDescriptionTypeDef",
     "PutLifecycleConfigurationRequestRequestTypeDef",
@@ -118,25 +118,14 @@
     },
     total=False,
 )
 
 class PosixUserTypeDef(_RequiredPosixUserTypeDef, _OptionalPosixUserTypeDef):
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -270,20 +259,20 @@
 DescribeFileSystemPolicyRequestRequestTypeDef = TypedDict(
     "DescribeFileSystemPolicyRequestRequestTypeDef",
     {
         "FileSystemId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
+    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CreationToken": str,
+        "FileSystemId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeFileSystemsRequestRequestTypeDef = TypedDict(
     "DescribeFileSystemsRequestRequestTypeDef",
     {
@@ -305,14 +294,33 @@
 DescribeMountTargetSecurityGroupsRequestRequestTypeDef = TypedDict(
     "DescribeMountTargetSecurityGroupsRequestRequestTypeDef",
     {
         "MountTargetId": str,
     },
 )
 
+DescribeMountTargetSecurityGroupsResponseTypeDef = TypedDict(
+    "DescribeMountTargetSecurityGroupsResponseTypeDef",
+    {
+        "SecurityGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef = TypedDict(
+    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
+    {
+        "FileSystemId": str,
+        "MountTargetId": str,
+        "AccessPointId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMountTargetsRequestRequestTypeDef = TypedDict(
     "DescribeMountTargetsRequestRequestTypeDef",
     {
         "MaxItems": int,
         "Marker": str,
         "FileSystemId": str,
         "MountTargetId": str,
@@ -354,14 +362,34 @@
         "FileSystemId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef",
+    {
+        "FileSystemId": str,
+    },
+)
+_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeTagsRequestDescribeTagsPaginateTypeDef(
+    _RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef,
+    _OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeTagsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeTagsRequestRequestTypeDef",
     {
         "FileSystemId": str,
     },
 )
 _OptionalDescribeTagsRequestRequestTypeDef = TypedDict(
@@ -393,14 +421,21 @@
     },
     total=False,
 )
 
 class DestinationTypeDef(_RequiredDestinationTypeDef, _OptionalDestinationTypeDef):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFileSystemSizeTypeDef = TypedDict(
     "_RequiredFileSystemSizeTypeDef",
     {
         "Value": int,
     },
 )
 _OptionalFileSystemSizeTypeDef = TypedDict(
@@ -412,14 +447,23 @@
     },
     total=False,
 )
 
 class FileSystemSizeTypeDef(_RequiredFileSystemSizeTypeDef, _OptionalFileSystemSizeTypeDef):
     pass
 
+FileSystemPolicyDescriptionTypeDef = TypedDict(
+    "FileSystemPolicyDescriptionTypeDef",
+    {
+        "FileSystemId": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecyclePolicyTypeDef = TypedDict(
     "LifecyclePolicyTypeDef",
     {
         "TransitionToIA": TransitionToIARulesType,
         "TransitionToPrimaryStorageClass": Literal["AFTER_1_ACCESS"],
     },
     total=False,
@@ -462,14 +506,41 @@
 
 class ModifyMountTargetSecurityGroupsRequestRequestTypeDef(
     _RequiredModifyMountTargetSecurityGroupsRequestRequestTypeDef,
     _OptionalModifyMountTargetSecurityGroupsRequestRequestTypeDef,
 ):
     pass
 
+MountTargetDescriptionResponseMetadataTypeDef = TypedDict(
+    "MountTargetDescriptionResponseMetadataTypeDef",
+    {
+        "OwnerId": str,
+        "MountTargetId": str,
+        "FileSystemId": str,
+        "SubnetId": str,
+        "LifeCycleState": LifeCycleStateType,
+        "IpAddress": str,
+        "NetworkInterfaceId": str,
+        "AvailabilityZoneId": str,
+        "AvailabilityZoneName": str,
+        "VpcId": str,
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
 PutAccountPreferencesRequestRequestTypeDef = TypedDict(
     "PutAccountPreferencesRequestRequestTypeDef",
     {
         "ResourceIdType": ResourceIdTypeType,
     },
 )
 
@@ -490,14 +561,25 @@
 
 class PutFileSystemPolicyRequestRequestTypeDef(
     _RequiredPutFileSystemPolicyRequestRequestTypeDef,
     _OptionalPutFileSystemPolicyRequestRequestTypeDef,
 ):
     pass
 
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -518,55 +600,14 @@
 )
 
 class UpdateFileSystemRequestRequestTypeDef(
     _RequiredUpdateFileSystemRequestRequestTypeDef, _OptionalUpdateFileSystemRequestRequestTypeDef
 ):
     pass
 
-DescribeMountTargetSecurityGroupsResponseTypeDef = TypedDict(
-    "DescribeMountTargetSecurityGroupsResponseTypeDef",
-    {
-        "SecurityGroups": List[str],
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
-FileSystemPolicyDescriptionTypeDef = TypedDict(
-    "FileSystemPolicyDescriptionTypeDef",
-    {
-        "FileSystemId": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-MountTargetDescriptionResponseMetadataTypeDef = TypedDict(
-    "MountTargetDescriptionResponseMetadataTypeDef",
-    {
-        "OwnerId": str,
-        "MountTargetId": str,
-        "FileSystemId": str,
-        "SubnetId": str,
-        "LifeCycleState": LifeCycleStateType,
-        "IpAddress": str,
-        "NetworkInterfaceId": str,
-        "AvailabilityZoneId": str,
-        "AvailabilityZoneName": str,
-        "VpcId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateFileSystemRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFileSystemRequestRequestTypeDef",
     {
         "CreationToken": str,
     },
 )
 _OptionalCreateFileSystemRequestRequestTypeDef = TypedDict(
@@ -599,24 +640,24 @@
 
 DescribeTagsResponseTypeDef = TypedDict(
     "DescribeTagsResponseTypeDef",
     {
         "Marker": str,
         "Tags": List[TagTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
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
         "ResourceId": str,
@@ -624,15 +665,15 @@
     },
 )
 
 BackupPolicyDescriptionTypeDef = TypedDict(
     "BackupPolicyDescriptionTypeDef",
     {
         "BackupPolicy": BackupPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBackupPolicyRequestRequestTypeDef = TypedDict(
     "PutBackupPolicyRequestRequestTypeDef",
     {
         "FileSystemId": str,
@@ -658,87 +699,46 @@
 )
 
 DescribeAccountPreferencesResponseTypeDef = TypedDict(
     "DescribeAccountPreferencesResponseTypeDef",
     {
         "ResourceIdPreference": ResourceIdPreferenceTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountPreferencesResponseTypeDef = TypedDict(
     "PutAccountPreferencesResponseTypeDef",
     {
         "ResourceIdPreference": ResourceIdPreferenceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef = TypedDict(
-    "DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef",
-    {
-        "CreationToken": str,
-        "FileSystemId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef = TypedDict(
-    "DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef",
-    {
-        "FileSystemId": str,
-        "MountTargetId": str,
-        "AccessPointId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef",
-    {
-        "FileSystemId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeTagsRequestDescribeTagsPaginateTypeDef(
-    _RequiredDescribeTagsRequestDescribeTagsPaginateTypeDef,
-    _OptionalDescribeTagsRequestDescribeTagsPaginateTypeDef,
-):
-    pass
 
 DescribeMountTargetsResponseTypeDef = TypedDict(
     "DescribeMountTargetsResponseTypeDef",
     {
         "Marker": str,
         "MountTargets": List[MountTargetDescriptionTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationConfigurationDescriptionResponseMetadataTypeDef = TypedDict(
     "ReplicationConfigurationDescriptionResponseMetadataTypeDef",
     {
         "SourceFileSystemId": str,
         "SourceFileSystemRegion": str,
         "SourceFileSystemArn": str,
         "OriginalSourceFileSystemArn": str,
         "CreationTime": datetime,
         "Destinations": List[DestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationConfigurationDescriptionTypeDef = TypedDict(
     "ReplicationConfigurationDescriptionTypeDef",
     {
         "SourceFileSystemId": str,
@@ -766,15 +766,15 @@
         "Encrypted": bool,
         "KmsKeyId": str,
         "ThroughputMode": ThroughputModeType,
         "ProvisionedThroughputInMibps": float,
         "AvailabilityZoneName": str,
         "AvailabilityZoneId": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFileSystemDescriptionTypeDef = TypedDict(
     "_RequiredFileSystemDescriptionTypeDef",
     {
         "OwnerId": str,
@@ -808,15 +808,15 @@
 ):
     pass
 
 LifecycleConfigurationDescriptionTypeDef = TypedDict(
     "LifecycleConfigurationDescriptionTypeDef",
     {
         "LifecyclePolicies": List[LifecyclePolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLifecycleConfigurationRequestRequestTypeDef = TypedDict(
     "PutLifecycleConfigurationRequestRequestTypeDef",
     {
         "FileSystemId": str,
@@ -833,15 +833,15 @@
         "AccessPointId": str,
         "AccessPointArn": str,
         "FileSystemId": str,
         "PosixUser": PosixUserTypeDef,
         "RootDirectory": RootDirectoryTypeDef,
         "OwnerId": str,
         "LifeCycleState": LifeCycleStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AccessPointDescriptionTypeDef = TypedDict(
     "AccessPointDescriptionTypeDef",
     {
         "ClientToken": str,
@@ -881,29 +881,29 @@
     pass
 
 DescribeReplicationConfigurationsResponseTypeDef = TypedDict(
     "DescribeReplicationConfigurationsResponseTypeDef",
     {
         "Replications": List[ReplicationConfigurationDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFileSystemsResponseTypeDef = TypedDict(
     "DescribeFileSystemsResponseTypeDef",
     {
         "Marker": str,
         "FileSystems": List[FileSystemDescriptionTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccessPointsResponseTypeDef = TypedDict(
     "DescribeAccessPointsResponseTypeDef",
     {
         "AccessPoints": List[AccessPointDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/PKG-INFO` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-efs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EFS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EFS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-efs"></a>
 
 # types-aiobotocore-efs
 
 [![PyPI - types-aiobotocore-efs](https://img.shields.io/pypi/v/types-aiobotocore-efs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-efs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-efs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-efs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-efs?color=blue)](https://pypistats.org/packages/types-aiobotocore-efs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EFS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS)
+[aiobotocore.EFS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/efs.html#EFS)
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
 [types-aiobotocore-efs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_efs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,15 +334,14 @@
 
 `types_aiobotocore_efs.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_efs.type_defs import (
     PosixUserTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
     BackupPolicyTypeDef,
     CreateMountTargetRequestRequestTypeDef,
     DestinationToCreateTypeDef,
     CreationInfoTypeDef,
     DeleteAccessPointRequestRequestTypeDef,
     DeleteFileSystemPolicyRequestRequestTypeDef,
@@ -351,49 +350,50 @@
     DeleteReplicationConfigurationRequestRequestTypeDef,
     DeleteTagsRequestRequestTypeDef,
     DescribeAccessPointsRequestRequestTypeDef,
     DescribeAccountPreferencesRequestRequestTypeDef,
     ResourceIdPreferenceTypeDef,
     DescribeBackupPolicyRequestRequestTypeDef,
     DescribeFileSystemPolicyRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
     DescribeFileSystemsRequestRequestTypeDef,
     DescribeLifecycleConfigurationRequestRequestTypeDef,
     DescribeMountTargetSecurityGroupsRequestRequestTypeDef,
+    DescribeMountTargetSecurityGroupsResponseTypeDef,
+    DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef,
     DescribeMountTargetsRequestRequestTypeDef,
     MountTargetDescriptionTypeDef,
     DescribeReplicationConfigurationsRequestRequestTypeDef,
+    DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeTagsRequestRequestTypeDef,
     DestinationTypeDef,
+    EmptyResponseMetadataTypeDef,
     FileSystemSizeTypeDef,
+    FileSystemPolicyDescriptionTypeDef,
     LifecyclePolicyTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ModifyMountTargetSecurityGroupsRequestRequestTypeDef,
+    MountTargetDescriptionResponseMetadataTypeDef,
+    PaginatorConfigTypeDef,
     PutAccountPreferencesRequestRequestTypeDef,
     PutFileSystemPolicyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFileSystemRequestRequestTypeDef,
-    DescribeMountTargetSecurityGroupsResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    FileSystemPolicyDescriptionTypeDef,
-    MountTargetDescriptionResponseMetadataTypeDef,
     CreateFileSystemRequestRequestTypeDef,
     CreateTagsRequestRequestTypeDef,
     DescribeTagsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     BackupPolicyDescriptionTypeDef,
     PutBackupPolicyRequestRequestTypeDef,
     CreateReplicationConfigurationRequestRequestTypeDef,
     RootDirectoryTypeDef,
     DescribeAccountPreferencesResponseTypeDef,
     PutAccountPreferencesResponseTypeDef,
-    DescribeFileSystemsRequestDescribeFileSystemsPaginateTypeDef,
-    DescribeMountTargetsRequestDescribeMountTargetsPaginateTypeDef,
-    DescribeTagsRequestDescribeTagsPaginateTypeDef,
     DescribeMountTargetsResponseTypeDef,
     ReplicationConfigurationDescriptionResponseMetadataTypeDef,
     ReplicationConfigurationDescriptionTypeDef,
     FileSystemDescriptionResponseMetadataTypeDef,
     FileSystemDescriptionTypeDef,
     LifecycleConfigurationDescriptionTypeDef,
     PutLifecycleConfigurationRequestRequestTypeDef,
@@ -413,43 +413,43 @@
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

### Comparing `types-aiobotocore-efs-2.5.0.post1/types_aiobotocore_efs.egg-info/SOURCES.txt` & `types-aiobotocore-efs-2.5.1/types_aiobotocore_efs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

