# Comparing `tmp/types-aiobotocore-cloudhsmv2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudhsmv2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudhsmv2-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudhsmv2-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1.tar` & `types-aiobotocore-cloudhsmv2-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:20.075025 types-aiobotocore-cloudhsmv2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14830 2023-03-11 12:26:20.067025 types-aiobotocore-cloudhsmv2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13247 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:20.075025 types-aiobotocore-cloudhsmv2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:20.067025 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/
--rw-r--r--   0 runner    (1001) docker     (123)     1040 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1039 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14707 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14680 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8801 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8799 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4465 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4459 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    13050 2023-03-11 12:10:56.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    13033 2023-03-11 12:10:56.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:55.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:20.067025 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14830 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:19.000000 types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.502107 types-aiobotocore-cloudhsmv2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14825 2023-06-28 01:43:13.498107 types-aiobotocore-cloudhsmv2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13248 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.502107 types-aiobotocore-cloudhsmv2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.490107 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1040 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1039 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14707 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14680 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9010 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9008 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4351 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4346 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    13082 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13065 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:32.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.498107 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14825 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:13.000000 types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudhsmv2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudhsmv2-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudhsmv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudHSMV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudHSMV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudhsmv2"></a>
 
 # types-aiobotocore-cloudhsmv2
 
 [![PyPI - types-aiobotocore-cloudhsmv2](https://img.shields.io/pypi/v/types-aiobotocore-cloudhsmv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsmv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudhsmv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsmv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudhsmv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudhsmv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudHSMV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2)
+[aiobotocore.CloudHSMV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2)
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
 [types-aiobotocore-cloudhsmv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,41 +334,41 @@
 ```python
 from types_aiobotocore_cloudhsmv2.type_defs import (
     BackupRetentionPolicyTypeDef,
     TagTypeDef,
     CertificatesTypeDef,
     HsmTypeDef,
     DestinationBackupTypeDef,
-    ResponseMetadataTypeDef,
     CreateHsmRequestRequestTypeDef,
     DeleteBackupRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteHsmRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeleteHsmResponseTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
     InitializeClusterRequestRequestTypeDef,
+    InitializeClusterResponseTypeDef,
+    ListTagsRequestListTagsPaginateTypeDef,
     ListTagsRequestRequestTypeDef,
     ModifyBackupAttributesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreBackupRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ModifyClusterRequestRequestTypeDef,
     BackupTypeDef,
     CopyBackupToRegionRequestRequestTypeDef,
     CreateClusterRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ClusterTypeDef,
-    CopyBackupToRegionResponseTypeDef,
     CreateHsmResponseTypeDef,
-    DeleteHsmResponseTypeDef,
-    InitializeClusterResponseTypeDef,
-    ListTagsResponseTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    ListTagsRequestListTagsPaginateTypeDef,
+    CopyBackupToRegionResponseTypeDef,
     DeleteBackupResponseTypeDef,
     DescribeBackupsResponseTypeDef,
     ModifyBackupAttributesResponseTypeDef,
     RestoreBackupResponseTypeDef,
     CreateClusterResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DescribeClustersResponseTypeDef,
@@ -383,43 +383,43 @@
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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/README.md` & `types-aiobotocore-cloudhsmv2-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudhsmv2"></a>
 
 # types-aiobotocore-cloudhsmv2
 
 [![PyPI - types-aiobotocore-cloudhsmv2](https://img.shields.io/pypi/v/types-aiobotocore-cloudhsmv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsmv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudhsmv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsmv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudhsmv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudhsmv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudHSMV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2)
+[aiobotocore.CloudHSMV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2)
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
 [types-aiobotocore-cloudhsmv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -301,41 +301,41 @@
 ```python
 from types_aiobotocore_cloudhsmv2.type_defs import (
     BackupRetentionPolicyTypeDef,
     TagTypeDef,
     CertificatesTypeDef,
     HsmTypeDef,
     DestinationBackupTypeDef,
-    ResponseMetadataTypeDef,
     CreateHsmRequestRequestTypeDef,
     DeleteBackupRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteHsmRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeleteHsmResponseTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
     InitializeClusterRequestRequestTypeDef,
+    InitializeClusterResponseTypeDef,
+    ListTagsRequestListTagsPaginateTypeDef,
     ListTagsRequestRequestTypeDef,
     ModifyBackupAttributesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreBackupRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ModifyClusterRequestRequestTypeDef,
     BackupTypeDef,
     CopyBackupToRegionRequestRequestTypeDef,
     CreateClusterRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ClusterTypeDef,
-    CopyBackupToRegionResponseTypeDef,
     CreateHsmResponseTypeDef,
-    DeleteHsmResponseTypeDef,
-    InitializeClusterResponseTypeDef,
-    ListTagsResponseTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    ListTagsRequestListTagsPaginateTypeDef,
+    CopyBackupToRegionResponseTypeDef,
     DeleteBackupResponseTypeDef,
     DescribeBackupsResponseTypeDef,
     ModifyBackupAttributesResponseTypeDef,
     RestoreBackupResponseTypeDef,
     CreateClusterResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DescribeClustersResponseTypeDef,
@@ -350,43 +350,43 @@
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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/setup.py` & `types-aiobotocore-cloudhsmv2-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudhsmv2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudhsmv2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudhsmv2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudHSMV2 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudHSMV2 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/"
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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/__init__.py` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/__init__.pyi` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/__main__.py` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudHSMV2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudHSMV2 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2\nOther"
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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/client.py` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/client.pyi` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/literals.py` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -113,14 +113,15 @@
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
@@ -199,14 +200,15 @@
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
@@ -217,14 +219,15 @@
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
@@ -260,14 +263,15 @@
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
@@ -286,16 +290,19 @@
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
@@ -379,15 +386,17 @@
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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/literals.pyi` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -111,14 +111,15 @@
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
@@ -197,14 +198,15 @@
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
@@ -215,14 +217,15 @@
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
@@ -258,14 +261,15 @@
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
@@ -284,16 +288,19 @@
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
@@ -377,15 +384,17 @@
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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/paginator.py` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: CloudHSMV2Client
 
         describe_backups_paginator: DescribeBackupsPaginator = client.get_paginator("describe_backups")
         describe_clusters_paginator: DescribeClustersPaginator = client.get_paginator("describe_clusters")
         list_tags_paginator: ListTagsPaginator = client.get_paginator("list_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBackupsResponseTypeDef,
     DescribeClustersResponseTypeDef,
     ListTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeBackupsPaginator", "DescribeClustersPaginator", "ListTagsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -63,15 +56,15 @@
     """
 
     def paginate(
         self,
         *,
         Filters: Mapping[str, Sequence[str]] = ...,
         SortAscending: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.DescribeBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#describebackupspaginator)
         """
 
 
@@ -81,28 +74,28 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#describeclusterspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Mapping[str, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.DescribeClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#describeclusterspaginator)
         """
 
 
 class ListTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.ListTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#listtagspaginator)
     """
 
     def paginate(
-        self, *, ResourceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.ListTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#listtagspaginator)
         """
```

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/paginator.pyi` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: CloudHSMV2Client
 
         describe_backups_paginator: DescribeBackupsPaginator = client.get_paginator("describe_backups")
         describe_clusters_paginator: DescribeClustersPaginator = client.get_paginator("describe_clusters")
         list_tags_paginator: ListTagsPaginator = client.get_paginator("list_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBackupsResponseTypeDef,
     DescribeClustersResponseTypeDef,
     ListTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeBackupsPaginator", "DescribeClustersPaginator", "ListTagsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -59,15 +53,15 @@
     """
 
     def paginate(
         self,
         *,
         Filters: Mapping[str, Sequence[str]] = ...,
         SortAscending: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.DescribeBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#describebackupspaginator)
         """
 
 class DescribeClustersPaginator(AioPaginator):
@@ -76,27 +70,27 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#describeclusterspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Mapping[str, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.DescribeClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#describeclusterspaginator)
         """
 
 class ListTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.ListTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#listtagspaginator)
     """
 
     def paginate(
-        self, *, ResourceId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2.Paginator.ListTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/paginators/#listtagspaginator)
         """
```

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/type_defs.py` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -29,41 +29,41 @@
 
 __all__ = (
     "BackupRetentionPolicyTypeDef",
     "TagTypeDef",
     "CertificatesTypeDef",
     "HsmTypeDef",
     "DestinationBackupTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateHsmRequestRequestTypeDef",
     "DeleteBackupRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteHsmRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DeleteHsmResponseTypeDef",
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     "DescribeBackupsRequestRequestTypeDef",
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
     "DescribeClustersRequestRequestTypeDef",
     "InitializeClusterRequestRequestTypeDef",
+    "InitializeClusterResponseTypeDef",
+    "ListTagsRequestListTagsPaginateTypeDef",
     "ListTagsRequestRequestTypeDef",
     "ModifyBackupAttributesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreBackupRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ModifyClusterRequestRequestTypeDef",
     "BackupTypeDef",
     "CopyBackupToRegionRequestRequestTypeDef",
     "CreateClusterRequestRequestTypeDef",
+    "ListTagsResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ClusterTypeDef",
-    "CopyBackupToRegionResponseTypeDef",
     "CreateHsmResponseTypeDef",
-    "DeleteHsmResponseTypeDef",
-    "InitializeClusterResponseTypeDef",
-    "ListTagsResponseTypeDef",
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    "ListTagsRequestListTagsPaginateTypeDef",
+    "CopyBackupToRegionResponseTypeDef",
     "DeleteBackupResponseTypeDef",
     "DescribeBackupsResponseTypeDef",
     "ModifyBackupAttributesResponseTypeDef",
     "RestoreBackupResponseTypeDef",
     "CreateClusterResponseTypeDef",
     "DeleteClusterResponseTypeDef",
     "DescribeClustersResponseTypeDef",
@@ -131,25 +131,14 @@
         "SourceRegion": str,
         "SourceBackup": str,
         "SourceCluster": str,
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
 _RequiredCreateHsmRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHsmRequestRequestTypeDef",
     {
         "ClusterId": str,
         "AvailabilityZone": str,
     },
 )
@@ -201,20 +190,28 @@
 
 class DeleteHsmRequestRequestTypeDef(
     _RequiredDeleteHsmRequestRequestTypeDef, _OptionalDeleteHsmRequestRequestTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DeleteHsmResponseTypeDef = TypedDict(
+    "DeleteHsmResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "HsmId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
+    {
+        "Filters": Mapping[str, Sequence[str]],
+        "SortAscending": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeBackupsRequestRequestTypeDef = TypedDict(
     "DescribeBackupsRequestRequestTypeDef",
     {
@@ -222,14 +219,23 @@
         "MaxResults": int,
         "Filters": Mapping[str, Sequence[str]],
         "SortAscending": bool,
     },
     total=False,
 )
 
+DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
+    {
+        "Filters": Mapping[str, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "Filters": Mapping[str, Sequence[str]],
         "NextToken": str,
         "MaxResults": int,
     },
@@ -241,14 +247,44 @@
     {
         "ClusterId": str,
         "SignedCert": str,
         "TrustAnchor": str,
     },
 )
 
+InitializeClusterResponseTypeDef = TypedDict(
+    "InitializeClusterResponseTypeDef",
+    {
+        "State": ClusterStateType,
+        "StateMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_RequiredListTagsRequestListTagsPaginateTypeDef",
+    {
+        "ResourceId": str,
+    },
+)
+_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_OptionalListTagsRequestListTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsRequestListTagsPaginateTypeDef(
+    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
+):
+    pass
+
+
 _RequiredListTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsRequestRequestTypeDef",
     {
         "ResourceId": str,
     },
 )
 _OptionalListTagsRequestRequestTypeDef = TypedDict(
@@ -271,14 +307,35 @@
     "ModifyBackupAttributesRequestRequestTypeDef",
     {
         "BackupId": str,
         "NeverExpires": bool,
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
 RestoreBackupRequestRequestTypeDef = TypedDict(
     "RestoreBackupRequestRequestTypeDef",
     {
         "BackupId": str,
     },
 )
 
@@ -369,14 +426,23 @@
 
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
 ):
     pass
 
 
+ListTagsResponseTypeDef = TypedDict(
+    "ListTagsResponseTypeDef",
+    {
+        "TagList": List[TagTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceId": str,
         "TagList": Sequence[TagTypeDef],
     },
 )
@@ -399,154 +465,88 @@
         "VpcId": str,
         "Certificates": CertificatesTypeDef,
         "TagList": List[TagTypeDef],
     },
     total=False,
 )
 
-CopyBackupToRegionResponseTypeDef = TypedDict(
-    "CopyBackupToRegionResponseTypeDef",
-    {
-        "DestinationBackup": DestinationBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateHsmResponseTypeDef = TypedDict(
     "CreateHsmResponseTypeDef",
     {
         "Hsm": HsmTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHsmResponseTypeDef = TypedDict(
-    "DeleteHsmResponseTypeDef",
-    {
-        "HsmId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitializeClusterResponseTypeDef = TypedDict(
-    "InitializeClusterResponseTypeDef",
-    {
-        "State": ClusterStateType,
-        "StateMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsResponseTypeDef = TypedDict(
-    "ListTagsResponseTypeDef",
-    {
-        "TagList": List[TagTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    {
-        "Filters": Mapping[str, Sequence[str]],
-        "SortAscending": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    {
-        "Filters": Mapping[str, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_RequiredListTagsRequestListTagsPaginateTypeDef",
-    {
-        "ResourceId": str,
-    },
-)
-_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_OptionalListTagsRequestListTagsPaginateTypeDef",
+CopyBackupToRegionResponseTypeDef = TypedDict(
+    "CopyBackupToRegionResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "DestinationBackup": DestinationBackupTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListTagsRequestListTagsPaginateTypeDef(
-    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
-):
-    pass
-
-
 DeleteBackupResponseTypeDef = TypedDict(
     "DeleteBackupResponseTypeDef",
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
 
 ModifyBackupAttributesResponseTypeDef = TypedDict(
     "ModifyBackupAttributesResponseTypeDef",
     {
         "Backup": BackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreBackupResponseTypeDef = TypedDict(
     "RestoreBackupResponseTypeDef",
     {
         "Backup": BackupTypeDef,
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
         "Clusters": List[ClusterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyClusterResponseTypeDef = TypedDict(
     "ModifyClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2/type_defs.pyi` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2/type_defs.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -28,41 +28,41 @@
 
 __all__ = (
     "BackupRetentionPolicyTypeDef",
     "TagTypeDef",
     "CertificatesTypeDef",
     "HsmTypeDef",
     "DestinationBackupTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateHsmRequestRequestTypeDef",
     "DeleteBackupRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteHsmRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DeleteHsmResponseTypeDef",
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     "DescribeBackupsRequestRequestTypeDef",
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
     "DescribeClustersRequestRequestTypeDef",
     "InitializeClusterRequestRequestTypeDef",
+    "InitializeClusterResponseTypeDef",
+    "ListTagsRequestListTagsPaginateTypeDef",
     "ListTagsRequestRequestTypeDef",
     "ModifyBackupAttributesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreBackupRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ModifyClusterRequestRequestTypeDef",
     "BackupTypeDef",
     "CopyBackupToRegionRequestRequestTypeDef",
     "CreateClusterRequestRequestTypeDef",
+    "ListTagsResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ClusterTypeDef",
-    "CopyBackupToRegionResponseTypeDef",
     "CreateHsmResponseTypeDef",
-    "DeleteHsmResponseTypeDef",
-    "InitializeClusterResponseTypeDef",
-    "ListTagsResponseTypeDef",
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    "ListTagsRequestListTagsPaginateTypeDef",
+    "CopyBackupToRegionResponseTypeDef",
     "DeleteBackupResponseTypeDef",
     "DescribeBackupsResponseTypeDef",
     "ModifyBackupAttributesResponseTypeDef",
     "RestoreBackupResponseTypeDef",
     "CreateClusterResponseTypeDef",
     "DeleteClusterResponseTypeDef",
     "DescribeClustersResponseTypeDef",
@@ -128,25 +128,14 @@
         "SourceRegion": str,
         "SourceBackup": str,
         "SourceCluster": str,
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
 _RequiredCreateHsmRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHsmRequestRequestTypeDef",
     {
         "ClusterId": str,
         "AvailabilityZone": str,
     },
 )
@@ -194,20 +183,28 @@
 )
 
 class DeleteHsmRequestRequestTypeDef(
     _RequiredDeleteHsmRequestRequestTypeDef, _OptionalDeleteHsmRequestRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DeleteHsmResponseTypeDef = TypedDict(
+    "DeleteHsmResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "HsmId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
+    {
+        "Filters": Mapping[str, Sequence[str]],
+        "SortAscending": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeBackupsRequestRequestTypeDef = TypedDict(
     "DescribeBackupsRequestRequestTypeDef",
     {
@@ -215,14 +212,23 @@
         "MaxResults": int,
         "Filters": Mapping[str, Sequence[str]],
         "SortAscending": bool,
     },
     total=False,
 )
 
+DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
+    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
+    {
+        "Filters": Mapping[str, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "Filters": Mapping[str, Sequence[str]],
         "NextToken": str,
         "MaxResults": int,
     },
@@ -234,14 +240,42 @@
     {
         "ClusterId": str,
         "SignedCert": str,
         "TrustAnchor": str,
     },
 )
 
+InitializeClusterResponseTypeDef = TypedDict(
+    "InitializeClusterResponseTypeDef",
+    {
+        "State": ClusterStateType,
+        "StateMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_RequiredListTagsRequestListTagsPaginateTypeDef",
+    {
+        "ResourceId": str,
+    },
+)
+_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
+    "_OptionalListTagsRequestListTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsRequestListTagsPaginateTypeDef(
+    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
+):
+    pass
+
 _RequiredListTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsRequestRequestTypeDef",
     {
         "ResourceId": str,
     },
 )
 _OptionalListTagsRequestRequestTypeDef = TypedDict(
@@ -262,14 +296,35 @@
     "ModifyBackupAttributesRequestRequestTypeDef",
     {
         "BackupId": str,
         "NeverExpires": bool,
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
 RestoreBackupRequestRequestTypeDef = TypedDict(
     "RestoreBackupRequestRequestTypeDef",
     {
         "BackupId": str,
     },
 )
 
@@ -354,14 +409,23 @@
 )
 
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
 ):
     pass
 
+ListTagsResponseTypeDef = TypedDict(
+    "ListTagsResponseTypeDef",
+    {
+        "TagList": List[TagTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceId": str,
         "TagList": Sequence[TagTypeDef],
     },
 )
@@ -384,152 +448,88 @@
         "VpcId": str,
         "Certificates": CertificatesTypeDef,
         "TagList": List[TagTypeDef],
     },
     total=False,
 )
 
-CopyBackupToRegionResponseTypeDef = TypedDict(
-    "CopyBackupToRegionResponseTypeDef",
-    {
-        "DestinationBackup": DestinationBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateHsmResponseTypeDef = TypedDict(
     "CreateHsmResponseTypeDef",
     {
         "Hsm": HsmTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteHsmResponseTypeDef = TypedDict(
-    "DeleteHsmResponseTypeDef",
-    {
-        "HsmId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitializeClusterResponseTypeDef = TypedDict(
-    "InitializeClusterResponseTypeDef",
-    {
-        "State": ClusterStateType,
-        "StateMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsResponseTypeDef = TypedDict(
-    "ListTagsResponseTypeDef",
-    {
-        "TagList": List[TagTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    {
-        "Filters": Mapping[str, Sequence[str]],
-        "SortAscending": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-DescribeClustersRequestDescribeClustersPaginateTypeDef = TypedDict(
-    "DescribeClustersRequestDescribeClustersPaginateTypeDef",
-    {
-        "Filters": Mapping[str, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_RequiredListTagsRequestListTagsPaginateTypeDef",
-    {
-        "ResourceId": str,
-    },
-)
-_OptionalListTagsRequestListTagsPaginateTypeDef = TypedDict(
-    "_OptionalListTagsRequestListTagsPaginateTypeDef",
+CopyBackupToRegionResponseTypeDef = TypedDict(
+    "CopyBackupToRegionResponseTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "DestinationBackup": DestinationBackupTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListTagsRequestListTagsPaginateTypeDef(
-    _RequiredListTagsRequestListTagsPaginateTypeDef, _OptionalListTagsRequestListTagsPaginateTypeDef
-):
-    pass
-
 DeleteBackupResponseTypeDef = TypedDict(
     "DeleteBackupResponseTypeDef",
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
 
 ModifyBackupAttributesResponseTypeDef = TypedDict(
     "ModifyBackupAttributesResponseTypeDef",
     {
         "Backup": BackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreBackupResponseTypeDef = TypedDict(
     "RestoreBackupResponseTypeDef",
     {
         "Backup": BackupTypeDef,
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
         "Clusters": List[ClusterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModifyClusterResponseTypeDef = TypedDict(
     "ModifyClusterResponseTypeDef",
     {
         "Cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/PKG-INFO` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudhsmv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudHSMV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudHSMV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudhsmv2"></a>
 
 # types-aiobotocore-cloudhsmv2
 
 [![PyPI - types-aiobotocore-cloudhsmv2](https://img.shields.io/pypi/v/types-aiobotocore-cloudhsmv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsmv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudhsmv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudhsmv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudhsmv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudhsmv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudHSMV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2)
+[aiobotocore.CloudHSMV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudhsmv2.html#CloudHSMV2)
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
 [types-aiobotocore-cloudhsmv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudhsmv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,41 +334,41 @@
 ```python
 from types_aiobotocore_cloudhsmv2.type_defs import (
     BackupRetentionPolicyTypeDef,
     TagTypeDef,
     CertificatesTypeDef,
     HsmTypeDef,
     DestinationBackupTypeDef,
-    ResponseMetadataTypeDef,
     CreateHsmRequestRequestTypeDef,
     DeleteBackupRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteHsmRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeleteHsmResponseTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
+    DescribeClustersRequestDescribeClustersPaginateTypeDef,
     DescribeClustersRequestRequestTypeDef,
     InitializeClusterRequestRequestTypeDef,
+    InitializeClusterResponseTypeDef,
+    ListTagsRequestListTagsPaginateTypeDef,
     ListTagsRequestRequestTypeDef,
     ModifyBackupAttributesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreBackupRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ModifyClusterRequestRequestTypeDef,
     BackupTypeDef,
     CopyBackupToRegionRequestRequestTypeDef,
     CreateClusterRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ClusterTypeDef,
-    CopyBackupToRegionResponseTypeDef,
     CreateHsmResponseTypeDef,
-    DeleteHsmResponseTypeDef,
-    InitializeClusterResponseTypeDef,
-    ListTagsResponseTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeClustersRequestDescribeClustersPaginateTypeDef,
-    ListTagsRequestListTagsPaginateTypeDef,
+    CopyBackupToRegionResponseTypeDef,
     DeleteBackupResponseTypeDef,
     DescribeBackupsResponseTypeDef,
     ModifyBackupAttributesResponseTypeDef,
     RestoreBackupResponseTypeDef,
     CreateClusterResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DescribeClustersResponseTypeDef,
@@ -383,43 +383,43 @@
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

### Comparing `types-aiobotocore-cloudhsmv2-2.5.0.post1/types_aiobotocore_cloudhsmv2.egg-info/SOURCES.txt` & `types-aiobotocore-cloudhsmv2-2.5.1/types_aiobotocore_cloudhsmv2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

