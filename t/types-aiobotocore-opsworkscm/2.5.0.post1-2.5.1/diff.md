# Comparing `tmp/types-aiobotocore-opsworkscm-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-opsworkscm-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-opsworkscm-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:05 2023, max compression
+gzip compressed data, was "types-aiobotocore-opsworkscm-2.5.1.tar", last modified: Wed Jun 28 01:43:56 2023, max compression
```

## Comparing `types-aiobotocore-opsworkscm-2.5.0.post1.tar` & `types-aiobotocore-opsworkscm-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.559483 types-aiobotocore-opsworkscm-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16238 2023-03-11 12:27:05.555483 types-aiobotocore-opsworkscm-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14655 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:05.559483 types-aiobotocore-opsworkscm-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.555483 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/
--rw-r--r--   0 runner    (1001) docker     (123)     1499 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1498 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19185 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    19152 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8839 2023-03-11 12:19:32.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8837 2023-03-11 12:19:32.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5607 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5600 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    18778 2023-03-11 12:19:32.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    18751 2023-03-11 12:19:32.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1638 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1637 2023-03-11 12:19:31.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.555483 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16238 2023-03-11 12:27:05.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      949 2023-03-11 12:27:05.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:05.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:27:05.000000 types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.210187 types-aiobotocore-opsworkscm-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16233 2023-06-28 01:43:56.202187 types-aiobotocore-opsworkscm-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14656 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:56.210187 types-aiobotocore-opsworkscm-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.202187 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/
+-rw-r--r--   0 runner    (1001) docker     (123)     1499 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1498 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19181 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19148 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9048 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9046 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5495 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5489 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    18816 2023-06-28 01:36:17.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18789 2023-06-28 01:36:17.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1638 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1637 2023-06-28 01:36:16.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.202187 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16233 2023-06-28 01:43:56.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:43:56.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:56.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:56.000000 types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/LICENSE` & `types-aiobotocore-opsworkscm-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/PKG-INFO` & `types-aiobotocore-opsworkscm-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opsworkscm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpsWorksCM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpsWorksCM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opsworkscm"></a>
 
 # types-aiobotocore-opsworkscm
 
 [![PyPI - types-aiobotocore-opsworkscm](https://img.shields.io/pypi/v/types-aiobotocore-opsworkscm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworkscm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opsworkscm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworkscm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opsworkscm?color=blue)](https://pypistats.org/packages/types-aiobotocore-opsworkscm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpsWorksCM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM)
+[aiobotocore.OpsWorksCM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM)
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
 [types-aiobotocore-opsworkscm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -359,51 +359,51 @@
 `types_aiobotocore_opsworkscm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_opsworkscm.type_defs import (
     AccountAttributeTypeDef,
     EngineAttributeTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateNodeResponseTypeDef,
     BackupTypeDef,
     TagTypeDef,
     DeleteBackupRequestRequestTypeDef,
     DeleteServerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     ServerEventTypeDef,
     WaiterConfigTypeDef,
     DescribeNodeAssociationStatusRequestRequestTypeDef,
+    DescribeServersRequestDescribeServersPaginateTypeDef,
     DescribeServersRequestRequestTypeDef,
+    DisassociateNodeResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreServerRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateServerEngineAttributesRequestRequestTypeDef,
     UpdateServerRequestRequestTypeDef,
+    DescribeAccountAttributesResponseTypeDef,
     AssociateNodeRequestRequestTypeDef,
+    DescribeNodeAssociationStatusResponseTypeDef,
     DisassociateNodeRequestRequestTypeDef,
     ExportServerEngineAttributeRequestRequestTypeDef,
+    ExportServerEngineAttributeResponseTypeDef,
     ServerTypeDef,
     StartMaintenanceRequestRequestTypeDef,
-    AssociateNodeResponseTypeDef,
-    DescribeAccountAttributesResponseTypeDef,
-    DescribeNodeAssociationStatusResponseTypeDef,
-    DisassociateNodeResponseTypeDef,
-    ExportServerEngineAttributeResponseTypeDef,
     CreateBackupResponseTypeDef,
     DescribeBackupsResponseTypeDef,
     CreateBackupRequestRequestTypeDef,
     CreateServerRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeServersRequestDescribeServersPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef,
     CreateServerResponseTypeDef,
     DescribeServersResponseTypeDef,
     RestoreServerResponseTypeDef,
     StartMaintenanceResponseTypeDef,
     UpdateServerEngineAttributesResponseTypeDef,
@@ -418,43 +418,43 @@
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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/README.md` & `types-aiobotocore-opsworkscm-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-opsworkscm"></a>
 
 # types-aiobotocore-opsworkscm
 
 [![PyPI - types-aiobotocore-opsworkscm](https://img.shields.io/pypi/v/types-aiobotocore-opsworkscm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworkscm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opsworkscm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworkscm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opsworkscm?color=blue)](https://pypistats.org/packages/types-aiobotocore-opsworkscm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpsWorksCM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM)
+[aiobotocore.OpsWorksCM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM)
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
 [types-aiobotocore-opsworkscm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -326,51 +326,51 @@
 `types_aiobotocore_opsworkscm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_opsworkscm.type_defs import (
     AccountAttributeTypeDef,
     EngineAttributeTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateNodeResponseTypeDef,
     BackupTypeDef,
     TagTypeDef,
     DeleteBackupRequestRequestTypeDef,
     DeleteServerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     ServerEventTypeDef,
     WaiterConfigTypeDef,
     DescribeNodeAssociationStatusRequestRequestTypeDef,
+    DescribeServersRequestDescribeServersPaginateTypeDef,
     DescribeServersRequestRequestTypeDef,
+    DisassociateNodeResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreServerRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateServerEngineAttributesRequestRequestTypeDef,
     UpdateServerRequestRequestTypeDef,
+    DescribeAccountAttributesResponseTypeDef,
     AssociateNodeRequestRequestTypeDef,
+    DescribeNodeAssociationStatusResponseTypeDef,
     DisassociateNodeRequestRequestTypeDef,
     ExportServerEngineAttributeRequestRequestTypeDef,
+    ExportServerEngineAttributeResponseTypeDef,
     ServerTypeDef,
     StartMaintenanceRequestRequestTypeDef,
-    AssociateNodeResponseTypeDef,
-    DescribeAccountAttributesResponseTypeDef,
-    DescribeNodeAssociationStatusResponseTypeDef,
-    DisassociateNodeResponseTypeDef,
-    ExportServerEngineAttributeResponseTypeDef,
     CreateBackupResponseTypeDef,
     DescribeBackupsResponseTypeDef,
     CreateBackupRequestRequestTypeDef,
     CreateServerRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeServersRequestDescribeServersPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef,
     CreateServerResponseTypeDef,
     DescribeServersResponseTypeDef,
     RestoreServerResponseTypeDef,
     StartMaintenanceResponseTypeDef,
     UpdateServerEngineAttributesResponseTypeDef,
@@ -385,43 +385,43 @@
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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/setup.py` & `types-aiobotocore-opsworkscm-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-opsworkscm.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-opsworkscm",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_opsworkscm"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.OpsWorksCM 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.OpsWorksCM 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/"
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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/__init__.py` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/__init__.pyi` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/__main__.py` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/__main__.py`

 * *Files 3% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.OpsWorksCM 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.OpsWorksCM 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM\nOther"
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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/client.py` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -284,16 +284,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/client/#list_tags_for_resource)
         """
 
     async def restore_server(
         self, *, BackupId: str, ServerName: str, InstanceType: str = ..., KeyPair: str = ...
     ) -> RestoreServerResponseTypeDef:
         """
-        Restores a backup to a server that is in a `CONNECTION_LOST` , `HEALTHY` ,
-        `RUNNING` , `UNHEALTHY` , or `TERMINATED` state.
+        Restores a backup to a server that is in a `CONNECTION_LOST`, `HEALTHY`,
+        `RUNNING`, `UNHEALTHY`, or `TERMINATED` state.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Client.restore_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/client/#restore_server)
         """
 
     async def start_maintenance(
         self, *, ServerName: str, EngineAttributes: Sequence[EngineAttributeTypeDef] = ...
```

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/client.pyi` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -263,16 +263,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/client/#list_tags_for_resource)
         """
     async def restore_server(
         self, *, BackupId: str, ServerName: str, InstanceType: str = ..., KeyPair: str = ...
     ) -> RestoreServerResponseTypeDef:
         """
-        Restores a backup to a server that is in a `CONNECTION_LOST` , `HEALTHY` ,
-        `RUNNING` , `UNHEALTHY` , or `TERMINATED` state.
+        Restores a backup to a server that is in a `CONNECTION_LOST`, `HEALTHY`,
+        `RUNNING`, `UNHEALTHY`, or `TERMINATED` state.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Client.restore_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/client/#restore_server)
         """
     async def start_maintenance(
         self, *, ServerName: str, EngineAttributes: Sequence[EngineAttributeTypeDef] = ...
     ) -> StartMaintenanceResponseTypeDef:
```

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/literals.py` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -122,14 +122,15 @@
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
@@ -208,14 +209,15 @@
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
@@ -226,14 +228,15 @@
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
@@ -269,14 +272,15 @@
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
@@ -295,16 +299,19 @@
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
@@ -388,15 +395,17 @@
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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/literals.pyi` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -120,14 +120,15 @@
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
@@ -206,14 +207,15 @@
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
@@ -224,14 +226,15 @@
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
@@ -267,14 +270,15 @@
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
@@ -293,16 +297,19 @@
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
@@ -386,15 +393,17 @@
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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/paginator.py` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -22,107 +22,94 @@
 
         describe_backups_paginator: DescribeBackupsPaginator = client.get_paginator("describe_backups")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_servers_paginator: DescribeServersPaginator = client.get_paginator("describe_servers")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBackupsResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeServersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeBackupsPaginator",
     "DescribeEventsPaginator",
     "DescribeServersPaginator",
     "ListTagsForResourcePaginator",
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
 class DescribeBackupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeBackups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describebackupspaginator)
     """
 
     def paginate(
         self,
         *,
         BackupId: str = ...,
         ServerName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describebackupspaginator)
         """
 
-
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeeventspaginator)
     """
 
     def paginate(
-        self, *, ServerName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeeventspaginator)
         """
 
-
 class DescribeServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeserverspaginator)
     """
 
     def paginate(
-        self, *, ServerName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeserverspaginator)
         """
 
-
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/paginator.pyi` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,100 +22,100 @@
 
         describe_backups_paginator: DescribeBackupsPaginator = client.get_paginator("describe_backups")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_servers_paginator: DescribeServersPaginator = client.get_paginator("describe_servers")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBackupsResponseTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeServersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeBackupsPaginator",
     "DescribeEventsPaginator",
     "DescribeServersPaginator",
     "ListTagsForResourcePaginator",
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
 class DescribeBackupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeBackups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describebackupspaginator)
     """
 
     def paginate(
         self,
         *,
         BackupId: str = ...,
         ServerName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describebackupspaginator)
         """
 
+
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeeventspaginator)
     """
 
     def paginate(
-        self, *, ServerName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeeventspaginator)
         """
 
+
 class DescribeServersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeServers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeserverspaginator)
     """
 
     def paginate(
-        self, *, ServerName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ServerName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.DescribeServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#describeserverspaginator)
         """
 
+
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/type_defs.py` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -24,55 +24,54 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AccountAttributeTypeDef",
     "EngineAttributeTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateNodeResponseTypeDef",
     "BackupTypeDef",
     "TagTypeDef",
     "DeleteBackupRequestRequestTypeDef",
     "DeleteServerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     "DescribeBackupsRequestRequestTypeDef",
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     "DescribeEventsRequestRequestTypeDef",
     "ServerEventTypeDef",
     "WaiterConfigTypeDef",
     "DescribeNodeAssociationStatusRequestRequestTypeDef",
+    "DescribeServersRequestDescribeServersPaginateTypeDef",
     "DescribeServersRequestRequestTypeDef",
+    "DisassociateNodeResponseTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreServerRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateServerEngineAttributesRequestRequestTypeDef",
     "UpdateServerRequestRequestTypeDef",
+    "DescribeAccountAttributesResponseTypeDef",
     "AssociateNodeRequestRequestTypeDef",
+    "DescribeNodeAssociationStatusResponseTypeDef",
     "DisassociateNodeRequestRequestTypeDef",
     "ExportServerEngineAttributeRequestRequestTypeDef",
+    "ExportServerEngineAttributeResponseTypeDef",
     "ServerTypeDef",
     "StartMaintenanceRequestRequestTypeDef",
-    "AssociateNodeResponseTypeDef",
-    "DescribeAccountAttributesResponseTypeDef",
-    "DescribeNodeAssociationStatusResponseTypeDef",
-    "DisassociateNodeResponseTypeDef",
-    "ExportServerEngineAttributeResponseTypeDef",
     "CreateBackupResponseTypeDef",
     "DescribeBackupsResponseTypeDef",
     "CreateBackupRequestRequestTypeDef",
     "CreateServerRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    "DescribeServersRequestDescribeServersPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "DescribeEventsResponseTypeDef",
     "DescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef",
     "CreateServerResponseTypeDef",
     "DescribeServersResponseTypeDef",
     "RestoreServerResponseTypeDef",
     "StartMaintenanceResponseTypeDef",
     "UpdateServerEngineAttributesResponseTypeDef",
@@ -94,22 +93,19 @@
     {
         "Name": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateNodeResponseTypeDef = TypedDict(
+    "AssociateNodeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "NodeAssociationStatusToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BackupTypeDef = TypedDict(
     "BackupTypeDef",
     {
         "BackupArn": str,
@@ -158,20 +154,20 @@
 DeleteServerRequestRequestTypeDef = TypedDict(
     "DeleteServerRequestRequestTypeDef",
     {
         "ServerName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "BackupId": str,
+        "ServerName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeBackupsRequestRequestTypeDef = TypedDict(
     "DescribeBackupsRequestRequestTypeDef",
     {
@@ -179,14 +175,34 @@
         "ServerName": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "ServerName": str,
+    },
+)
+_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeEventsRequestDescribeEventsPaginateTypeDef(
+    _RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef,
+    _OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeEventsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEventsRequestRequestTypeDef",
     {
         "ServerName": str,
     },
 )
 _OptionalDescribeEventsRequestRequestTypeDef = TypedDict(
@@ -194,21 +210,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class DescribeEventsRequestRequestTypeDef(
     _RequiredDescribeEventsRequestRequestTypeDef, _OptionalDescribeEventsRequestRequestTypeDef
 ):
     pass
 
-
 ServerEventTypeDef = TypedDict(
     "ServerEventTypeDef",
     {
         "CreatedAt": datetime,
         "ServerName": str,
         "Message": str,
         "LogUrl": str,
@@ -229,24 +243,61 @@
     "DescribeNodeAssociationStatusRequestRequestTypeDef",
     {
         "NodeAssociationStatusToken": str,
         "ServerName": str,
     },
 )
 
+DescribeServersRequestDescribeServersPaginateTypeDef = TypedDict(
+    "DescribeServersRequestDescribeServersPaginateTypeDef",
+    {
+        "ServerName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeServersRequestRequestTypeDef = TypedDict(
     "DescribeServersRequestRequestTypeDef",
     {
         "ServerName": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+DisassociateNodeResponseTypeDef = TypedDict(
+    "DisassociateNodeResponseTypeDef",
+    {
+        "NodeAssociationStatusToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
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
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -254,21 +305,40 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
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
 
 _RequiredRestoreServerRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreServerRequestRequestTypeDef",
     {
         "BackupId": str,
         "ServerName": str,
     },
@@ -278,21 +348,19 @@
     {
         "InstanceType": str,
         "KeyPair": str,
     },
     total=False,
 )
 
-
 class RestoreServerRequestRequestTypeDef(
     _RequiredRestoreServerRequestRequestTypeDef, _OptionalRestoreServerRequestRequestTypeDef
 ):
     pass
 
-
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -308,22 +376,20 @@
     "_OptionalUpdateServerEngineAttributesRequestRequestTypeDef",
     {
         "AttributeValue": str,
     },
     total=False,
 )
 
-
 class UpdateServerEngineAttributesRequestRequestTypeDef(
     _RequiredUpdateServerEngineAttributesRequestRequestTypeDef,
     _OptionalUpdateServerEngineAttributesRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateServerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateServerRequestRequestTypeDef",
     {
         "ServerName": str,
     },
 )
 _OptionalUpdateServerRequestRequestTypeDef = TypedDict(
@@ -333,30 +399,45 @@
         "BackupRetentionCount": int,
         "PreferredMaintenanceWindow": str,
         "PreferredBackupWindow": str,
     },
     total=False,
 )
 
-
 class UpdateServerRequestRequestTypeDef(
     _RequiredUpdateServerRequestRequestTypeDef, _OptionalUpdateServerRequestRequestTypeDef
 ):
     pass
 
+DescribeAccountAttributesResponseTypeDef = TypedDict(
+    "DescribeAccountAttributesResponseTypeDef",
+    {
+        "Attributes": List[AccountAttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 AssociateNodeRequestRequestTypeDef = TypedDict(
     "AssociateNodeRequestRequestTypeDef",
     {
         "ServerName": str,
         "NodeName": str,
         "EngineAttributes": Sequence[EngineAttributeTypeDef],
     },
 )
 
+DescribeNodeAssociationStatusResponseTypeDef = TypedDict(
+    "DescribeNodeAssociationStatusResponseTypeDef",
+    {
+        "NodeAssociationStatus": NodeAssociationStatusType,
+        "EngineAttributes": List[EngineAttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateNodeRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateNodeRequestRequestTypeDef",
     {
         "ServerName": str,
         "NodeName": str,
     },
 )
@@ -364,21 +445,19 @@
     "_OptionalDisassociateNodeRequestRequestTypeDef",
     {
         "EngineAttributes": Sequence[EngineAttributeTypeDef],
     },
     total=False,
 )
 
-
 class DisassociateNodeRequestRequestTypeDef(
     _RequiredDisassociateNodeRequestRequestTypeDef, _OptionalDisassociateNodeRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredExportServerEngineAttributeRequestRequestTypeDef = TypedDict(
     "_RequiredExportServerEngineAttributeRequestRequestTypeDef",
     {
         "ExportAttributeName": str,
         "ServerName": str,
     },
 )
@@ -386,21 +465,28 @@
     "_OptionalExportServerEngineAttributeRequestRequestTypeDef",
     {
         "InputAttributes": Sequence[EngineAttributeTypeDef],
     },
     total=False,
 )
 
-
 class ExportServerEngineAttributeRequestRequestTypeDef(
     _RequiredExportServerEngineAttributeRequestRequestTypeDef,
     _OptionalExportServerEngineAttributeRequestRequestTypeDef,
 ):
     pass
 
+ExportServerEngineAttributeResponseTypeDef = TypedDict(
+    "ExportServerEngineAttributeResponseTypeDef",
+    {
+        "EngineAttribute": EngineAttributeTypeDef,
+        "ServerName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ServerTypeDef = TypedDict(
     "ServerTypeDef",
     {
         "AssociatePublicIpAddress": bool,
         "BackupRetentionCount": int,
         "ServerName": str,
@@ -439,77 +525,33 @@
     "_OptionalStartMaintenanceRequestRequestTypeDef",
     {
         "EngineAttributes": Sequence[EngineAttributeTypeDef],
     },
     total=False,
 )
 
-
 class StartMaintenanceRequestRequestTypeDef(
     _RequiredStartMaintenanceRequestRequestTypeDef, _OptionalStartMaintenanceRequestRequestTypeDef
 ):
     pass
 
-
-AssociateNodeResponseTypeDef = TypedDict(
-    "AssociateNodeResponseTypeDef",
-    {
-        "NodeAssociationStatusToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountAttributesResponseTypeDef = TypedDict(
-    "DescribeAccountAttributesResponseTypeDef",
-    {
-        "Attributes": List[AccountAttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeNodeAssociationStatusResponseTypeDef = TypedDict(
-    "DescribeNodeAssociationStatusResponseTypeDef",
-    {
-        "NodeAssociationStatus": NodeAssociationStatusType,
-        "EngineAttributes": List[EngineAttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateNodeResponseTypeDef = TypedDict(
-    "DisassociateNodeResponseTypeDef",
-    {
-        "NodeAssociationStatusToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportServerEngineAttributeResponseTypeDef = TypedDict(
-    "ExportServerEngineAttributeResponseTypeDef",
-    {
-        "EngineAttribute": EngineAttributeTypeDef,
-        "ServerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
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
 
 _RequiredCreateBackupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBackupRequestRequestTypeDef",
     {
         "ServerName": str,
@@ -520,21 +562,19 @@
     {
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateBackupRequestRequestTypeDef(
     _RequiredCreateBackupRequestRequestTypeDef, _OptionalCreateBackupRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateServerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateServerRequestRequestTypeDef",
     {
         "Engine": str,
         "ServerName": str,
         "InstanceProfileArn": str,
         "InstanceType": str,
@@ -560,107 +600,42 @@
         "SubnetIds": Sequence[str],
         "Tags": Sequence[TagTypeDef],
         "BackupId": str,
     },
     total=False,
 )
 
-
 class CreateServerRequestRequestTypeDef(
     _RequiredCreateServerRequestRequestTypeDef, _OptionalCreateServerRequestRequestTypeDef
 ):
     pass
 
-
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
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    {
-        "BackupId": str,
-        "ServerName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "ServerName": str,
-    },
-)
-_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeEventsRequestDescribeEventsPaginateTypeDef(
-    _RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef,
-    _OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef,
-):
-    pass
-
-
-DescribeServersRequestDescribeServersPaginateTypeDef = TypedDict(
-    "DescribeServersRequestDescribeServersPaginateTypeDef",
-    {
-        "ServerName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
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
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "ServerEvents": List[ServerEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef = TypedDict(
     "_RequiredDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef",
     {
         "NodeAssociationStatusToken": str,
@@ -671,63 +646,61 @@
     "_OptionalDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef(
     _RequiredDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef,
     _OptionalDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef,
 ):
     pass
 
-
 CreateServerResponseTypeDef = TypedDict(
     "CreateServerResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServersResponseTypeDef = TypedDict(
     "DescribeServersResponseTypeDef",
     {
         "Servers": List[ServerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreServerResponseTypeDef = TypedDict(
     "RestoreServerResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMaintenanceResponseTypeDef = TypedDict(
     "StartMaintenanceResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServerEngineAttributesResponseTypeDef = TypedDict(
     "UpdateServerEngineAttributesResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServerResponseTypeDef = TypedDict(
     "UpdateServerResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/type_defs.pyi` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -24,54 +24,55 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AccountAttributeTypeDef",
     "EngineAttributeTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateNodeResponseTypeDef",
     "BackupTypeDef",
     "TagTypeDef",
     "DeleteBackupRequestRequestTypeDef",
     "DeleteServerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     "DescribeBackupsRequestRequestTypeDef",
+    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     "DescribeEventsRequestRequestTypeDef",
     "ServerEventTypeDef",
     "WaiterConfigTypeDef",
     "DescribeNodeAssociationStatusRequestRequestTypeDef",
+    "DescribeServersRequestDescribeServersPaginateTypeDef",
     "DescribeServersRequestRequestTypeDef",
+    "DisassociateNodeResponseTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreServerRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateServerEngineAttributesRequestRequestTypeDef",
     "UpdateServerRequestRequestTypeDef",
+    "DescribeAccountAttributesResponseTypeDef",
     "AssociateNodeRequestRequestTypeDef",
+    "DescribeNodeAssociationStatusResponseTypeDef",
     "DisassociateNodeRequestRequestTypeDef",
     "ExportServerEngineAttributeRequestRequestTypeDef",
+    "ExportServerEngineAttributeResponseTypeDef",
     "ServerTypeDef",
     "StartMaintenanceRequestRequestTypeDef",
-    "AssociateNodeResponseTypeDef",
-    "DescribeAccountAttributesResponseTypeDef",
-    "DescribeNodeAssociationStatusResponseTypeDef",
-    "DisassociateNodeResponseTypeDef",
-    "ExportServerEngineAttributeResponseTypeDef",
     "CreateBackupResponseTypeDef",
     "DescribeBackupsResponseTypeDef",
     "CreateBackupRequestRequestTypeDef",
     "CreateServerRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    "DescribeEventsRequestDescribeEventsPaginateTypeDef",
-    "DescribeServersRequestDescribeServersPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "DescribeEventsResponseTypeDef",
     "DescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef",
     "CreateServerResponseTypeDef",
     "DescribeServersResponseTypeDef",
     "RestoreServerResponseTypeDef",
     "StartMaintenanceResponseTypeDef",
     "UpdateServerEngineAttributesResponseTypeDef",
@@ -93,22 +94,19 @@
     {
         "Name": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateNodeResponseTypeDef = TypedDict(
+    "AssociateNodeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "NodeAssociationStatusToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BackupTypeDef = TypedDict(
     "BackupTypeDef",
     {
         "BackupArn": str,
@@ -157,20 +155,20 @@
 DeleteServerRequestRequestTypeDef = TypedDict(
     "DeleteServerRequestRequestTypeDef",
     {
         "ServerName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
+    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "BackupId": str,
+        "ServerName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeBackupsRequestRequestTypeDef = TypedDict(
     "DescribeBackupsRequestRequestTypeDef",
     {
@@ -178,14 +176,36 @@
         "ServerName": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "ServerName": str,
+    },
+)
+_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeEventsRequestDescribeEventsPaginateTypeDef(
+    _RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef,
+    _OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeEventsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEventsRequestRequestTypeDef",
     {
         "ServerName": str,
     },
 )
 _OptionalDescribeEventsRequestRequestTypeDef = TypedDict(
@@ -193,19 +213,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class DescribeEventsRequestRequestTypeDef(
     _RequiredDescribeEventsRequestRequestTypeDef, _OptionalDescribeEventsRequestRequestTypeDef
 ):
     pass
 
+
 ServerEventTypeDef = TypedDict(
     "ServerEventTypeDef",
     {
         "CreatedAt": datetime,
         "ServerName": str,
         "Message": str,
         "LogUrl": str,
@@ -226,24 +248,63 @@
     "DescribeNodeAssociationStatusRequestRequestTypeDef",
     {
         "NodeAssociationStatusToken": str,
         "ServerName": str,
     },
 )
 
+DescribeServersRequestDescribeServersPaginateTypeDef = TypedDict(
+    "DescribeServersRequestDescribeServersPaginateTypeDef",
+    {
+        "ServerName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeServersRequestRequestTypeDef = TypedDict(
     "DescribeServersRequestRequestTypeDef",
     {
         "ServerName": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+DisassociateNodeResponseTypeDef = TypedDict(
+    "DisassociateNodeResponseTypeDef",
+    {
+        "NodeAssociationStatusToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
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
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -251,20 +312,43 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
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
 _RequiredRestoreServerRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreServerRequestRequestTypeDef",
     {
         "BackupId": str,
         "ServerName": str,
     },
 )
@@ -273,19 +357,21 @@
     {
         "InstanceType": str,
         "KeyPair": str,
     },
     total=False,
 )
 
+
 class RestoreServerRequestRequestTypeDef(
     _RequiredRestoreServerRequestRequestTypeDef, _OptionalRestoreServerRequestRequestTypeDef
 ):
     pass
 
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -301,20 +387,22 @@
     "_OptionalUpdateServerEngineAttributesRequestRequestTypeDef",
     {
         "AttributeValue": str,
     },
     total=False,
 )
 
+
 class UpdateServerEngineAttributesRequestRequestTypeDef(
     _RequiredUpdateServerEngineAttributesRequestRequestTypeDef,
     _OptionalUpdateServerEngineAttributesRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateServerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateServerRequestRequestTypeDef",
     {
         "ServerName": str,
     },
 )
 _OptionalUpdateServerRequestRequestTypeDef = TypedDict(
@@ -324,28 +412,47 @@
         "BackupRetentionCount": int,
         "PreferredMaintenanceWindow": str,
         "PreferredBackupWindow": str,
     },
     total=False,
 )
 
+
 class UpdateServerRequestRequestTypeDef(
     _RequiredUpdateServerRequestRequestTypeDef, _OptionalUpdateServerRequestRequestTypeDef
 ):
     pass
 
+
+DescribeAccountAttributesResponseTypeDef = TypedDict(
+    "DescribeAccountAttributesResponseTypeDef",
+    {
+        "Attributes": List[AccountAttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateNodeRequestRequestTypeDef = TypedDict(
     "AssociateNodeRequestRequestTypeDef",
     {
         "ServerName": str,
         "NodeName": str,
         "EngineAttributes": Sequence[EngineAttributeTypeDef],
     },
 )
 
+DescribeNodeAssociationStatusResponseTypeDef = TypedDict(
+    "DescribeNodeAssociationStatusResponseTypeDef",
+    {
+        "NodeAssociationStatus": NodeAssociationStatusType,
+        "EngineAttributes": List[EngineAttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateNodeRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateNodeRequestRequestTypeDef",
     {
         "ServerName": str,
         "NodeName": str,
     },
 )
@@ -353,19 +460,21 @@
     "_OptionalDisassociateNodeRequestRequestTypeDef",
     {
         "EngineAttributes": Sequence[EngineAttributeTypeDef],
     },
     total=False,
 )
 
+
 class DisassociateNodeRequestRequestTypeDef(
     _RequiredDisassociateNodeRequestRequestTypeDef, _OptionalDisassociateNodeRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredExportServerEngineAttributeRequestRequestTypeDef = TypedDict(
     "_RequiredExportServerEngineAttributeRequestRequestTypeDef",
     {
         "ExportAttributeName": str,
         "ServerName": str,
     },
 )
@@ -373,20 +482,31 @@
     "_OptionalExportServerEngineAttributeRequestRequestTypeDef",
     {
         "InputAttributes": Sequence[EngineAttributeTypeDef],
     },
     total=False,
 )
 
+
 class ExportServerEngineAttributeRequestRequestTypeDef(
     _RequiredExportServerEngineAttributeRequestRequestTypeDef,
     _OptionalExportServerEngineAttributeRequestRequestTypeDef,
 ):
     pass
 
+
+ExportServerEngineAttributeResponseTypeDef = TypedDict(
+    "ExportServerEngineAttributeResponseTypeDef",
+    {
+        "EngineAttribute": EngineAttributeTypeDef,
+        "ServerName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ServerTypeDef = TypedDict(
     "ServerTypeDef",
     {
         "AssociatePublicIpAddress": bool,
         "BackupRetentionCount": int,
         "ServerName": str,
         "CreatedAt": datetime,
@@ -424,75 +544,35 @@
     "_OptionalStartMaintenanceRequestRequestTypeDef",
     {
         "EngineAttributes": Sequence[EngineAttributeTypeDef],
     },
     total=False,
 )
 
+
 class StartMaintenanceRequestRequestTypeDef(
     _RequiredStartMaintenanceRequestRequestTypeDef, _OptionalStartMaintenanceRequestRequestTypeDef
 ):
     pass
 
-AssociateNodeResponseTypeDef = TypedDict(
-    "AssociateNodeResponseTypeDef",
-    {
-        "NodeAssociationStatusToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountAttributesResponseTypeDef = TypedDict(
-    "DescribeAccountAttributesResponseTypeDef",
-    {
-        "Attributes": List[AccountAttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeNodeAssociationStatusResponseTypeDef = TypedDict(
-    "DescribeNodeAssociationStatusResponseTypeDef",
-    {
-        "NodeAssociationStatus": NodeAssociationStatusType,
-        "EngineAttributes": List[EngineAttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateNodeResponseTypeDef = TypedDict(
-    "DisassociateNodeResponseTypeDef",
-    {
-        "NodeAssociationStatusToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExportServerEngineAttributeResponseTypeDef = TypedDict(
-    "ExportServerEngineAttributeResponseTypeDef",
-    {
-        "EngineAttribute": EngineAttributeTypeDef,
-        "ServerName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
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
 
 _RequiredCreateBackupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBackupRequestRequestTypeDef",
     {
         "ServerName": str,
@@ -503,19 +583,21 @@
     {
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateBackupRequestRequestTypeDef(
     _RequiredCreateBackupRequestRequestTypeDef, _OptionalCreateBackupRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateServerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateServerRequestRequestTypeDef",
     {
         "Engine": str,
         "ServerName": str,
         "InstanceProfileArn": str,
         "InstanceType": str,
@@ -541,101 +623,44 @@
         "SubnetIds": Sequence[str],
         "Tags": Sequence[TagTypeDef],
         "BackupId": str,
     },
     total=False,
 )
 
+
 class CreateServerRequestRequestTypeDef(
     _RequiredCreateServerRequestRequestTypeDef, _OptionalCreateServerRequestRequestTypeDef
 ):
     pass
 
+
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
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-DescribeBackupsRequestDescribeBackupsPaginateTypeDef = TypedDict(
-    "DescribeBackupsRequestDescribeBackupsPaginateTypeDef",
-    {
-        "BackupId": str,
-        "ServerName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "ServerName": str,
-    },
-)
-_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeEventsRequestDescribeEventsPaginateTypeDef(
-    _RequiredDescribeEventsRequestDescribeEventsPaginateTypeDef,
-    _OptionalDescribeEventsRequestDescribeEventsPaginateTypeDef,
-):
-    pass
-
-DescribeServersRequestDescribeServersPaginateTypeDef = TypedDict(
-    "DescribeServersRequestDescribeServersPaginateTypeDef",
-    {
-        "ServerName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
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
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "ServerEvents": List[ServerEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef = TypedDict(
     "_RequiredDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef",
     {
         "NodeAssociationStatusToken": str,
@@ -646,61 +671,63 @@
     "_OptionalDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef(
     _RequiredDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef,
     _OptionalDescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef,
 ):
     pass
 
+
 CreateServerResponseTypeDef = TypedDict(
     "CreateServerResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServersResponseTypeDef = TypedDict(
     "DescribeServersResponseTypeDef",
     {
         "Servers": List[ServerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreServerResponseTypeDef = TypedDict(
     "RestoreServerResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMaintenanceResponseTypeDef = TypedDict(
     "StartMaintenanceResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServerEngineAttributesResponseTypeDef = TypedDict(
     "UpdateServerEngineAttributesResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServerResponseTypeDef = TypedDict(
     "UpdateServerResponseTypeDef",
     {
         "Server": ServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/waiter.py` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm/waiter.pyi` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/PKG-INFO` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opsworkscm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpsWorksCM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpsWorksCM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opsworkscm"></a>
 
 # types-aiobotocore-opsworkscm
 
 [![PyPI - types-aiobotocore-opsworkscm](https://img.shields.io/pypi/v/types-aiobotocore-opsworkscm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworkscm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opsworkscm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworkscm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opsworkscm?color=blue)](https://pypistats.org/packages/types-aiobotocore-opsworkscm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpsWorksCM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM)
+[aiobotocore.OpsWorksCM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworkscm.html#OpsWorksCM)
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
 [types-aiobotocore-opsworkscm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -359,51 +359,51 @@
 `types_aiobotocore_opsworkscm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_opsworkscm.type_defs import (
     AccountAttributeTypeDef,
     EngineAttributeTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateNodeResponseTypeDef,
     BackupTypeDef,
     TagTypeDef,
     DeleteBackupRequestRequestTypeDef,
     DeleteServerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
     DescribeBackupsRequestRequestTypeDef,
+    DescribeEventsRequestDescribeEventsPaginateTypeDef,
     DescribeEventsRequestRequestTypeDef,
     ServerEventTypeDef,
     WaiterConfigTypeDef,
     DescribeNodeAssociationStatusRequestRequestTypeDef,
+    DescribeServersRequestDescribeServersPaginateTypeDef,
     DescribeServersRequestRequestTypeDef,
+    DisassociateNodeResponseTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RestoreServerRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateServerEngineAttributesRequestRequestTypeDef,
     UpdateServerRequestRequestTypeDef,
+    DescribeAccountAttributesResponseTypeDef,
     AssociateNodeRequestRequestTypeDef,
+    DescribeNodeAssociationStatusResponseTypeDef,
     DisassociateNodeRequestRequestTypeDef,
     ExportServerEngineAttributeRequestRequestTypeDef,
+    ExportServerEngineAttributeResponseTypeDef,
     ServerTypeDef,
     StartMaintenanceRequestRequestTypeDef,
-    AssociateNodeResponseTypeDef,
-    DescribeAccountAttributesResponseTypeDef,
-    DescribeNodeAssociationStatusResponseTypeDef,
-    DisassociateNodeResponseTypeDef,
-    ExportServerEngineAttributeResponseTypeDef,
     CreateBackupResponseTypeDef,
     DescribeBackupsResponseTypeDef,
     CreateBackupRequestRequestTypeDef,
     CreateServerRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
-    DescribeBackupsRequestDescribeBackupsPaginateTypeDef,
-    DescribeEventsRequestDescribeEventsPaginateTypeDef,
-    DescribeServersRequestDescribeServersPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     DescribeEventsResponseTypeDef,
     DescribeNodeAssociationStatusRequestNodeAssociatedWaitTypeDef,
     CreateServerResponseTypeDef,
     DescribeServersResponseTypeDef,
     RestoreServerResponseTypeDef,
     StartMaintenanceResponseTypeDef,
     UpdateServerEngineAttributesResponseTypeDef,
@@ -418,43 +418,43 @@
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

### Comparing `types-aiobotocore-opsworkscm-2.5.0.post1/types_aiobotocore_opsworkscm.egg-info/SOURCES.txt` & `types-aiobotocore-opsworkscm-2.5.1/types_aiobotocore_opsworkscm.egg-info/SOURCES.txt`

 * *Files identical despite different names*

