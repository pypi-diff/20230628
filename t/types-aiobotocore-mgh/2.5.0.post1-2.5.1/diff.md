# Comparing `tmp/types-aiobotocore-mgh-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mgh-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mgh-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-mgh-2.5.1.tar", last modified: Wed Jun 28 01:43:52 2023, max compression
```

## Comparing `types-aiobotocore-mgh-2.5.0.post1.tar` & `types-aiobotocore-mgh-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.995439 types-aiobotocore-mgh-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15433 2023-03-11 12:27:00.991439 types-aiobotocore-mgh-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13869 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:00.995439 types-aiobotocore-mgh-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2081 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.983439 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/
--rw-r--r--   0 runner    (1001) docker     (123)     1678 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1677 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      934 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18658 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18627 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8743 2023-03-11 12:18:44.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8741 2023-03-11 12:18:44.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6984 2023-03-11 12:18:44.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6976 2023-03-11 12:18:44.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    17684 2023-03-11 12:18:44.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17649 2023-03-11 12:18:44.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:43.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.991439 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15433 2023-03-11 12:27:00.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:27:00.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:00.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:27:00.000000 types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.038179 types-aiobotocore-mgh-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15421 2023-06-28 01:43:52.038179 types-aiobotocore-mgh-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13863 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:52.038179 types-aiobotocore-mgh-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2075 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.038179 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/
+-rw-r--r--   0 runner    (1001) docker     (123)     1678 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1677 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      922 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18657 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18626 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8952 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8950 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6898 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6891 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    17708 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17673 2023-06-28 01:35:28.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:27.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.038179 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15421 2023-06-28 01:43:51.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:51.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:51.000000 types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mgh-2.5.0.post1/LICENSE` & `types-aiobotocore-mgh-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mgh-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mgh
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mgh"></a>
 
 # types-aiobotocore-mgh
 
 [![PyPI - types-aiobotocore-mgh](https://img.shields.io/pypi/v/types-aiobotocore-mgh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgh)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mgh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgh)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mgh?color=blue)](https://pypistats.org/packages/types-aiobotocore-mgh)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub)
+[aiobotocore.MigrationHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub)
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
 [types-aiobotocore-mgh docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/).
 
 See how it helps to find and fix potential bugs:
 
@@ -345,41 +345,41 @@
 from types_aiobotocore_mgh.type_defs import (
     ApplicationStateTypeDef,
     CreatedArtifactTypeDef,
     DiscoveredResourceTypeDef,
     CreateProgressUpdateStreamRequestRequestTypeDef,
     DeleteProgressUpdateStreamRequestRequestTypeDef,
     DescribeApplicationStateRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeApplicationStateResultTypeDef,
     DescribeMigrationTaskRequestRequestTypeDef,
     DisassociateCreatedArtifactRequestRequestTypeDef,
     DisassociateDiscoveredResourceRequestRequestTypeDef,
     ImportMigrationTaskRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationStatesRequestListApplicationStatesPaginateTypeDef,
     ListApplicationStatesRequestRequestTypeDef,
+    ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
     ListCreatedArtifactsRequestRequestTypeDef,
+    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
+    ListMigrationTasksRequestListMigrationTasksPaginateTypeDef,
     ListMigrationTasksRequestRequestTypeDef,
     MigrationTaskSummaryTypeDef,
+    ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef,
     ListProgressUpdateStreamsRequestRequestTypeDef,
     ProgressUpdateStreamSummaryTypeDef,
     ResourceAttributeTypeDef,
     TaskTypeDef,
     NotifyApplicationStateRequestRequestTypeDef,
-    AssociateCreatedArtifactRequestRequestTypeDef,
-    AssociateDiscoveredResourceRequestRequestTypeDef,
-    DescribeApplicationStateResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ListApplicationStatesResultTypeDef,
+    AssociateCreatedArtifactRequestRequestTypeDef,
     ListCreatedArtifactsResultTypeDef,
+    AssociateDiscoveredResourceRequestRequestTypeDef,
     ListDiscoveredResourcesResultTypeDef,
-    ListApplicationStatesRequestListApplicationStatesPaginateTypeDef,
-    ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
-    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    ListMigrationTasksRequestListMigrationTasksPaginateTypeDef,
-    ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef,
     ListMigrationTasksResultTypeDef,
     ListProgressUpdateStreamsResultTypeDef,
     PutResourceAttributesRequestRequestTypeDef,
     MigrationTaskTypeDef,
     NotifyMigrationTaskStateRequestRequestTypeDef,
     DescribeMigrationTaskResultTypeDef,
 )
@@ -392,43 +392,43 @@
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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/README.md` & `types-aiobotocore-mgh-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mgh"></a>
 
 # types-aiobotocore-mgh
 
 [![PyPI - types-aiobotocore-mgh](https://img.shields.io/pypi/v/types-aiobotocore-mgh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgh)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mgh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgh)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mgh?color=blue)](https://pypistats.org/packages/types-aiobotocore-mgh)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub)
+[aiobotocore.MigrationHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub)
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
 [types-aiobotocore-mgh docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/).
 
 See how it helps to find and fix potential bugs:
 
@@ -312,41 +312,41 @@
 from types_aiobotocore_mgh.type_defs import (
     ApplicationStateTypeDef,
     CreatedArtifactTypeDef,
     DiscoveredResourceTypeDef,
     CreateProgressUpdateStreamRequestRequestTypeDef,
     DeleteProgressUpdateStreamRequestRequestTypeDef,
     DescribeApplicationStateRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeApplicationStateResultTypeDef,
     DescribeMigrationTaskRequestRequestTypeDef,
     DisassociateCreatedArtifactRequestRequestTypeDef,
     DisassociateDiscoveredResourceRequestRequestTypeDef,
     ImportMigrationTaskRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationStatesRequestListApplicationStatesPaginateTypeDef,
     ListApplicationStatesRequestRequestTypeDef,
+    ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
     ListCreatedArtifactsRequestRequestTypeDef,
+    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
+    ListMigrationTasksRequestListMigrationTasksPaginateTypeDef,
     ListMigrationTasksRequestRequestTypeDef,
     MigrationTaskSummaryTypeDef,
+    ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef,
     ListProgressUpdateStreamsRequestRequestTypeDef,
     ProgressUpdateStreamSummaryTypeDef,
     ResourceAttributeTypeDef,
     TaskTypeDef,
     NotifyApplicationStateRequestRequestTypeDef,
-    AssociateCreatedArtifactRequestRequestTypeDef,
-    AssociateDiscoveredResourceRequestRequestTypeDef,
-    DescribeApplicationStateResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ListApplicationStatesResultTypeDef,
+    AssociateCreatedArtifactRequestRequestTypeDef,
     ListCreatedArtifactsResultTypeDef,
+    AssociateDiscoveredResourceRequestRequestTypeDef,
     ListDiscoveredResourcesResultTypeDef,
-    ListApplicationStatesRequestListApplicationStatesPaginateTypeDef,
-    ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
-    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    ListMigrationTasksRequestListMigrationTasksPaginateTypeDef,
-    ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef,
     ListMigrationTasksResultTypeDef,
     ListProgressUpdateStreamsResultTypeDef,
     PutResourceAttributesRequestRequestTypeDef,
     MigrationTaskTypeDef,
     NotifyMigrationTaskStateRequestRequestTypeDef,
     DescribeMigrationTaskResultTypeDef,
 )
@@ -359,43 +359,43 @@
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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/setup.py` & `types-aiobotocore-mgh-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mgh.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mgh",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mgh"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MigrationHub 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MigrationHub 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/",
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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/__init__.py` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/__init__.pyi` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/__main__.py` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MigrationHub 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MigrationHub 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub\nOther"
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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/client.py` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -270,15 +270,15 @@
         *,
         ProgressUpdateStream: str,
         MigrationTaskName: str,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDiscoveredResourcesResultTypeDef:
         """
-        Lists discovered resources associated with the given `MigrationTask` .
+        Lists discovered resources associated with the given `MigrationTask`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Client.list_discovered_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/client/#list_discovered_resources)
         """
 
     async def list_migration_tasks(
         self, *, NextToken: str = ..., MaxResults: int = ..., ResourceName: str = ...
```

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/client.pyi` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -251,15 +251,15 @@
         *,
         ProgressUpdateStream: str,
         MigrationTaskName: str,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDiscoveredResourcesResultTypeDef:
         """
-        Lists discovered resources associated with the given `MigrationTask` .
+        Lists discovered resources associated with the given `MigrationTask`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Client.list_discovered_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/client/#list_discovered_resources)
         """
     async def list_migration_tasks(
         self, *, NextToken: str = ..., MaxResults: int = ..., ResourceName: str = ...
     ) -> ListMigrationTasksResultTypeDef:
```

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/literals.py` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ApplicationStatusType",
     "ListApplicationStatesPaginatorName",
     "ListCreatedArtifactsPaginatorName",
     "ListDiscoveredResourcesPaginatorName",
     "ListMigrationTasksPaginatorName",
     "ListProgressUpdateStreamsPaginatorName",
@@ -31,15 +30,14 @@
     "MigrationHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ApplicationStatusType = Literal["COMPLETED", "IN_PROGRESS", "NOT_STARTED"]
 ListApplicationStatesPaginatorName = Literal["list_application_states"]
 ListCreatedArtifactsPaginatorName = Literal["list_created_artifacts"]
 ListDiscoveredResourcesPaginatorName = Literal["list_discovered_resources"]
 ListMigrationTasksPaginatorName = Literal["list_migration_tasks"]
 ListProgressUpdateStreamsPaginatorName = Literal["list_progress_update_streams"]
 ResourceAttributeTypeType = Literal[
@@ -114,14 +112,15 @@
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
@@ -200,14 +199,15 @@
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
@@ -218,14 +218,15 @@
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
@@ -261,14 +262,15 @@
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
@@ -287,16 +289,19 @@
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
@@ -380,15 +385,17 @@
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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/literals.pyi` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/literals.py`

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
     "ApplicationStatusType",
     "ListApplicationStatesPaginatorName",
     "ListCreatedArtifactsPaginatorName",
     "ListDiscoveredResourcesPaginatorName",
     "ListMigrationTasksPaginatorName",
     "ListProgressUpdateStreamsPaginatorName",
@@ -30,14 +31,15 @@
     "MigrationHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ApplicationStatusType = Literal["COMPLETED", "IN_PROGRESS", "NOT_STARTED"]
 ListApplicationStatesPaginatorName = Literal["list_application_states"]
 ListCreatedArtifactsPaginatorName = Literal["list_created_artifacts"]
 ListDiscoveredResourcesPaginatorName = Literal["list_discovered_resources"]
 ListMigrationTasksPaginatorName = Literal["list_migration_tasks"]
 ListProgressUpdateStreamsPaginatorName = Literal["list_progress_update_streams"]
 ResourceAttributeTypeType = Literal[
@@ -112,14 +114,15 @@
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
@@ -198,14 +201,15 @@
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
@@ -216,14 +220,15 @@
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
@@ -259,14 +264,15 @@
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
@@ -285,16 +291,19 @@
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
@@ -378,15 +387,17 @@
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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/paginator.py` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         list_application_states_paginator: ListApplicationStatesPaginator = client.get_paginator("list_application_states")
         list_created_artifacts_paginator: ListCreatedArtifactsPaginator = client.get_paginator("list_created_artifacts")
         list_discovered_resources_paginator: ListDiscoveredResourcesPaginator = client.get_paginator("list_discovered_resources")
         list_migration_tasks_paginator: ListMigrationTasksPaginator = client.get_paginator("list_migration_tasks")
         list_progress_update_streams_paginator: ListProgressUpdateStreamsPaginator = client.get_paginator("list_progress_update_streams")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationStatesResultTypeDef,
     ListCreatedArtifactsResultTypeDef,
     ListDiscoveredResourcesResultTypeDef,
     ListMigrationTasksResultTypeDef,
     ListProgressUpdateStreamsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApplicationStatesPaginator",
     "ListCreatedArtifactsPaginator",
     "ListDiscoveredResourcesPaginator",
     "ListMigrationTasksPaginator",
     "ListProgressUpdateStreamsPaginator",
 )
@@ -71,15 +64,18 @@
 class ListApplicationStatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListApplicationStates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listapplicationstatespaginator)
     """
 
     def paginate(
-        self, *, ApplicationIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ApplicationIds: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationStatesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListApplicationStates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listapplicationstatespaginator)
         """
 
 
@@ -90,15 +86,15 @@
     """
 
     def paginate(
         self,
         *,
         ProgressUpdateStream: str,
         MigrationTaskName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCreatedArtifactsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListCreatedArtifacts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listcreatedartifactspaginator)
         """
 
 
@@ -109,43 +105,43 @@
     """
 
     def paginate(
         self,
         *,
         ProgressUpdateStream: str,
         MigrationTaskName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDiscoveredResourcesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListDiscoveredResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listdiscoveredresourcespaginator)
         """
 
 
 class ListMigrationTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListMigrationTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listmigrationtaskspaginator)
     """
 
     def paginate(
-        self, *, ResourceName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMigrationTasksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListMigrationTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listmigrationtaskspaginator)
         """
 
 
 class ListProgressUpdateStreamsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListProgressUpdateStreams)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listprogressupdatestreamspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProgressUpdateStreamsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListProgressUpdateStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listprogressupdatestreamspaginator)
         """
```

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/paginator.pyi` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         list_application_states_paginator: ListApplicationStatesPaginator = client.get_paginator("list_application_states")
         list_created_artifacts_paginator: ListCreatedArtifactsPaginator = client.get_paginator("list_created_artifacts")
         list_discovered_resources_paginator: ListDiscoveredResourcesPaginator = client.get_paginator("list_discovered_resources")
         list_migration_tasks_paginator: ListMigrationTasksPaginator = client.get_paginator("list_migration_tasks")
         list_progress_update_streams_paginator: ListProgressUpdateStreamsPaginator = client.get_paginator("list_progress_update_streams")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationStatesResultTypeDef,
     ListCreatedArtifactsResultTypeDef,
     ListDiscoveredResourcesResultTypeDef,
     ListMigrationTasksResultTypeDef,
     ListProgressUpdateStreamsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApplicationStatesPaginator",
     "ListCreatedArtifactsPaginator",
     "ListDiscoveredResourcesPaginator",
     "ListMigrationTasksPaginator",
     "ListProgressUpdateStreamsPaginator",
 )
@@ -67,15 +61,18 @@
 class ListApplicationStatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListApplicationStates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listapplicationstatespaginator)
     """
 
     def paginate(
-        self, *, ApplicationIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ApplicationIds: Sequence[str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationStatesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListApplicationStates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listapplicationstatespaginator)
         """
 
 class ListCreatedArtifactsPaginator(AioPaginator):
@@ -85,15 +82,15 @@
     """
 
     def paginate(
         self,
         *,
         ProgressUpdateStream: str,
         MigrationTaskName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCreatedArtifactsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListCreatedArtifacts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listcreatedartifactspaginator)
         """
 
 class ListDiscoveredResourcesPaginator(AioPaginator):
@@ -103,41 +100,41 @@
     """
 
     def paginate(
         self,
         *,
         ProgressUpdateStream: str,
         MigrationTaskName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDiscoveredResourcesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListDiscoveredResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listdiscoveredresourcespaginator)
         """
 
 class ListMigrationTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListMigrationTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listmigrationtaskspaginator)
     """
 
     def paginate(
-        self, *, ResourceName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMigrationTasksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListMigrationTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listmigrationtaskspaginator)
         """
 
 class ListProgressUpdateStreamsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListProgressUpdateStreams)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listprogressupdatestreamspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProgressUpdateStreamsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub.Paginator.ListProgressUpdateStreams.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/paginators/#listprogressupdatestreamspaginator)
         """
```

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/type_defs.py` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -26,41 +26,41 @@
 __all__ = (
     "ApplicationStateTypeDef",
     "CreatedArtifactTypeDef",
     "DiscoveredResourceTypeDef",
     "CreateProgressUpdateStreamRequestRequestTypeDef",
     "DeleteProgressUpdateStreamRequestRequestTypeDef",
     "DescribeApplicationStateRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeApplicationStateResultTypeDef",
     "DescribeMigrationTaskRequestRequestTypeDef",
     "DisassociateCreatedArtifactRequestRequestTypeDef",
     "DisassociateDiscoveredResourceRequestRequestTypeDef",
     "ImportMigrationTaskRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
     "ListApplicationStatesRequestRequestTypeDef",
+    "ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
     "ListCreatedArtifactsRequestRequestTypeDef",
+    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
     "ListDiscoveredResourcesRequestRequestTypeDef",
+    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
     "ListMigrationTasksRequestRequestTypeDef",
     "MigrationTaskSummaryTypeDef",
+    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
     "ListProgressUpdateStreamsRequestRequestTypeDef",
     "ProgressUpdateStreamSummaryTypeDef",
     "ResourceAttributeTypeDef",
     "TaskTypeDef",
     "NotifyApplicationStateRequestRequestTypeDef",
-    "AssociateCreatedArtifactRequestRequestTypeDef",
-    "AssociateDiscoveredResourceRequestRequestTypeDef",
-    "DescribeApplicationStateResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ListApplicationStatesResultTypeDef",
+    "AssociateCreatedArtifactRequestRequestTypeDef",
     "ListCreatedArtifactsResultTypeDef",
+    "AssociateDiscoveredResourceRequestRequestTypeDef",
     "ListDiscoveredResourcesResultTypeDef",
-    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
-    "ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
-    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
-    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
     "ListMigrationTasksResultTypeDef",
     "ListProgressUpdateStreamsResultTypeDef",
     "PutResourceAttributesRequestRequestTypeDef",
     "MigrationTaskTypeDef",
     "NotifyMigrationTaskStateRequestRequestTypeDef",
     "DescribeMigrationTaskResultTypeDef",
 )
@@ -162,22 +162,20 @@
 DescribeApplicationStateRequestRequestTypeDef = TypedDict(
     "DescribeApplicationStateRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DescribeApplicationStateResultTypeDef = TypedDict(
+    "DescribeApplicationStateResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ApplicationStatus": ApplicationStatusType,
+        "LastUpdatedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMigrationTaskRequestRequestTypeDef = TypedDict(
     "DescribeMigrationTaskRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
@@ -252,34 +250,56 @@
 class ImportMigrationTaskRequestRequestTypeDef(
     _RequiredImportMigrationTaskRequestRequestTypeDef,
     _OptionalImportMigrationTaskRequestRequestTypeDef,
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListApplicationStatesRequestListApplicationStatesPaginateTypeDef = TypedDict(
+    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationStatesRequestRequestTypeDef = TypedDict(
     "ListApplicationStatesRequestRequestTypeDef",
     {
         "ApplicationIds": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
+    "_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
+    {
+        "ProgressUpdateStream": str,
+        "MigrationTaskName": str,
+    },
+)
+_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
+    "_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef(
+    _RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
+    _OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListCreatedArtifactsRequestRequestTypeDef = TypedDict(
     "_RequiredListCreatedArtifactsRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
     },
 )
@@ -296,14 +316,37 @@
 class ListCreatedArtifactsRequestRequestTypeDef(
     _RequiredListCreatedArtifactsRequestRequestTypeDef,
     _OptionalListCreatedArtifactsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "ProgressUpdateStream": str,
+        "MigrationTaskName": str,
+    },
+)
+_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
+    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDiscoveredResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListDiscoveredResourcesRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
     },
 )
@@ -320,14 +363,23 @@
 class ListDiscoveredResourcesRequestRequestTypeDef(
     _RequiredListDiscoveredResourcesRequestRequestTypeDef,
     _OptionalListDiscoveredResourcesRequestRequestTypeDef,
 ):
     pass
 
 
+ListMigrationTasksRequestListMigrationTasksPaginateTypeDef = TypedDict(
+    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
+    {
+        "ResourceName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMigrationTasksRequestRequestTypeDef = TypedDict(
     "ListMigrationTasksRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResourceName": str,
     },
@@ -343,14 +395,22 @@
         "ProgressPercent": int,
         "StatusDetail": str,
         "UpdateDateTime": datetime,
     },
     total=False,
 )
 
+ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef = TypedDict(
+    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProgressUpdateStreamsRequestRequestTypeDef = TypedDict(
     "ListProgressUpdateStreamsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -412,14 +472,44 @@
 class NotifyApplicationStateRequestRequestTypeDef(
     _RequiredNotifyApplicationStateRequestRequestTypeDef,
     _OptionalNotifyApplicationStateRequestRequestTypeDef,
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
+
+ListApplicationStatesResultTypeDef = TypedDict(
+    "ListApplicationStatesResultTypeDef",
+    {
+        "ApplicationStateList": List[ApplicationStateTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateCreatedArtifactRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateCreatedArtifactRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
         "CreatedArtifact": CreatedArtifactTypeDef,
     },
@@ -436,14 +526,23 @@
 class AssociateCreatedArtifactRequestRequestTypeDef(
     _RequiredAssociateCreatedArtifactRequestRequestTypeDef,
     _OptionalAssociateCreatedArtifactRequestRequestTypeDef,
 ):
     pass
 
 
+ListCreatedArtifactsResultTypeDef = TypedDict(
+    "ListCreatedArtifactsResultTypeDef",
+    {
+        "NextToken": str,
+        "CreatedArtifactList": List[CreatedArtifactTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateDiscoveredResourceRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateDiscoveredResourceRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
         "DiscoveredResource": DiscoveredResourceTypeDef,
     },
@@ -460,137 +559,38 @@
 class AssociateDiscoveredResourceRequestRequestTypeDef(
     _RequiredAssociateDiscoveredResourceRequestRequestTypeDef,
     _OptionalAssociateDiscoveredResourceRequestRequestTypeDef,
 ):
     pass
 
 
-DescribeApplicationStateResultTypeDef = TypedDict(
-    "DescribeApplicationStateResultTypeDef",
-    {
-        "ApplicationStatus": ApplicationStatusType,
-        "LastUpdatedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationStatesResultTypeDef = TypedDict(
-    "ListApplicationStatesResultTypeDef",
-    {
-        "ApplicationStateList": List[ApplicationStateTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCreatedArtifactsResultTypeDef = TypedDict(
-    "ListCreatedArtifactsResultTypeDef",
-    {
-        "NextToken": str,
-        "CreatedArtifactList": List[CreatedArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListDiscoveredResourcesResultTypeDef = TypedDict(
     "ListDiscoveredResourcesResultTypeDef",
     {
         "NextToken": str,
         "DiscoveredResourceList": List[DiscoveredResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationStatesRequestListApplicationStatesPaginateTypeDef = TypedDict(
-    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
-    {
-        "ApplicationIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
-    "_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
-    {
-        "ProgressUpdateStream": str,
-        "MigrationTaskName": str,
-    },
-)
-_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
-    "_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef(
-    _RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
-    _OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "ProgressUpdateStream": str,
-        "MigrationTaskName": str,
-    },
-)
-_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
-    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-):
-    pass
-
-
-ListMigrationTasksRequestListMigrationTasksPaginateTypeDef = TypedDict(
-    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
-    {
-        "ResourceName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef = TypedDict(
-    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListMigrationTasksResultTypeDef = TypedDict(
     "ListMigrationTasksResultTypeDef",
     {
         "NextToken": str,
         "MigrationTaskSummaryList": List[MigrationTaskSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProgressUpdateStreamsResultTypeDef = TypedDict(
     "ListProgressUpdateStreamsResultTypeDef",
     {
         "ProgressUpdateStreamSummaryList": List[ProgressUpdateStreamSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutResourceAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourceAttributesRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
@@ -652,10 +652,10 @@
     pass
 
 
 DescribeMigrationTaskResultTypeDef = TypedDict(
     "DescribeMigrationTaskResultTypeDef",
     {
         "MigrationTask": MigrationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh/type_defs.pyi` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -25,41 +25,41 @@
 __all__ = (
     "ApplicationStateTypeDef",
     "CreatedArtifactTypeDef",
     "DiscoveredResourceTypeDef",
     "CreateProgressUpdateStreamRequestRequestTypeDef",
     "DeleteProgressUpdateStreamRequestRequestTypeDef",
     "DescribeApplicationStateRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeApplicationStateResultTypeDef",
     "DescribeMigrationTaskRequestRequestTypeDef",
     "DisassociateCreatedArtifactRequestRequestTypeDef",
     "DisassociateDiscoveredResourceRequestRequestTypeDef",
     "ImportMigrationTaskRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
     "ListApplicationStatesRequestRequestTypeDef",
+    "ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
     "ListCreatedArtifactsRequestRequestTypeDef",
+    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
     "ListDiscoveredResourcesRequestRequestTypeDef",
+    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
     "ListMigrationTasksRequestRequestTypeDef",
     "MigrationTaskSummaryTypeDef",
+    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
     "ListProgressUpdateStreamsRequestRequestTypeDef",
     "ProgressUpdateStreamSummaryTypeDef",
     "ResourceAttributeTypeDef",
     "TaskTypeDef",
     "NotifyApplicationStateRequestRequestTypeDef",
-    "AssociateCreatedArtifactRequestRequestTypeDef",
-    "AssociateDiscoveredResourceRequestRequestTypeDef",
-    "DescribeApplicationStateResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ListApplicationStatesResultTypeDef",
+    "AssociateCreatedArtifactRequestRequestTypeDef",
     "ListCreatedArtifactsResultTypeDef",
+    "AssociateDiscoveredResourceRequestRequestTypeDef",
     "ListDiscoveredResourcesResultTypeDef",
-    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
-    "ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
-    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
-    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
     "ListMigrationTasksResultTypeDef",
     "ListProgressUpdateStreamsResultTypeDef",
     "PutResourceAttributesRequestRequestTypeDef",
     "MigrationTaskTypeDef",
     "NotifyMigrationTaskStateRequestRequestTypeDef",
     "DescribeMigrationTaskResultTypeDef",
 )
@@ -153,22 +153,20 @@
 DescribeApplicationStateRequestRequestTypeDef = TypedDict(
     "DescribeApplicationStateRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DescribeApplicationStateResultTypeDef = TypedDict(
+    "DescribeApplicationStateResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ApplicationStatus": ApplicationStatusType,
+        "LastUpdatedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMigrationTaskRequestRequestTypeDef = TypedDict(
     "DescribeMigrationTaskRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
@@ -237,34 +235,54 @@
 
 class ImportMigrationTaskRequestRequestTypeDef(
     _RequiredImportMigrationTaskRequestRequestTypeDef,
     _OptionalImportMigrationTaskRequestRequestTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListApplicationStatesRequestListApplicationStatesPaginateTypeDef = TypedDict(
+    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationStatesRequestRequestTypeDef = TypedDict(
     "ListApplicationStatesRequestRequestTypeDef",
     {
         "ApplicationIds": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
+    "_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
+    {
+        "ProgressUpdateStream": str,
+        "MigrationTaskName": str,
+    },
+)
+_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
+    "_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef(
+    _RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
+    _OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
+):
+    pass
+
 _RequiredListCreatedArtifactsRequestRequestTypeDef = TypedDict(
     "_RequiredListCreatedArtifactsRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
     },
 )
@@ -279,14 +297,35 @@
 
 class ListCreatedArtifactsRequestRequestTypeDef(
     _RequiredListCreatedArtifactsRequestRequestTypeDef,
     _OptionalListCreatedArtifactsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "ProgressUpdateStream": str,
+        "MigrationTaskName": str,
+    },
+)
+_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
+    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDiscoveredResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListDiscoveredResourcesRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
     },
 )
@@ -301,14 +340,23 @@
 
 class ListDiscoveredResourcesRequestRequestTypeDef(
     _RequiredListDiscoveredResourcesRequestRequestTypeDef,
     _OptionalListDiscoveredResourcesRequestRequestTypeDef,
 ):
     pass
 
+ListMigrationTasksRequestListMigrationTasksPaginateTypeDef = TypedDict(
+    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
+    {
+        "ResourceName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMigrationTasksRequestRequestTypeDef = TypedDict(
     "ListMigrationTasksRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ResourceName": str,
     },
@@ -324,14 +372,22 @@
         "ProgressPercent": int,
         "StatusDetail": str,
         "UpdateDateTime": datetime,
     },
     total=False,
 )
 
+ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef = TypedDict(
+    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProgressUpdateStreamsRequestRequestTypeDef = TypedDict(
     "ListProgressUpdateStreamsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -389,14 +445,44 @@
 
 class NotifyApplicationStateRequestRequestTypeDef(
     _RequiredNotifyApplicationStateRequestRequestTypeDef,
     _OptionalNotifyApplicationStateRequestRequestTypeDef,
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
+
+ListApplicationStatesResultTypeDef = TypedDict(
+    "ListApplicationStatesResultTypeDef",
+    {
+        "ApplicationStateList": List[ApplicationStateTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateCreatedArtifactRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateCreatedArtifactRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
         "CreatedArtifact": CreatedArtifactTypeDef,
     },
@@ -411,14 +497,23 @@
 
 class AssociateCreatedArtifactRequestRequestTypeDef(
     _RequiredAssociateCreatedArtifactRequestRequestTypeDef,
     _OptionalAssociateCreatedArtifactRequestRequestTypeDef,
 ):
     pass
 
+ListCreatedArtifactsResultTypeDef = TypedDict(
+    "ListCreatedArtifactsResultTypeDef",
+    {
+        "NextToken": str,
+        "CreatedArtifactList": List[CreatedArtifactTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateDiscoveredResourceRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateDiscoveredResourceRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
         "MigrationTaskName": str,
         "DiscoveredResource": DiscoveredResourceTypeDef,
     },
@@ -433,133 +528,38 @@
 
 class AssociateDiscoveredResourceRequestRequestTypeDef(
     _RequiredAssociateDiscoveredResourceRequestRequestTypeDef,
     _OptionalAssociateDiscoveredResourceRequestRequestTypeDef,
 ):
     pass
 
-DescribeApplicationStateResultTypeDef = TypedDict(
-    "DescribeApplicationStateResultTypeDef",
-    {
-        "ApplicationStatus": ApplicationStatusType,
-        "LastUpdatedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationStatesResultTypeDef = TypedDict(
-    "ListApplicationStatesResultTypeDef",
-    {
-        "ApplicationStateList": List[ApplicationStateTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCreatedArtifactsResultTypeDef = TypedDict(
-    "ListCreatedArtifactsResultTypeDef",
-    {
-        "NextToken": str,
-        "CreatedArtifactList": List[CreatedArtifactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListDiscoveredResourcesResultTypeDef = TypedDict(
     "ListDiscoveredResourcesResultTypeDef",
     {
         "NextToken": str,
         "DiscoveredResourceList": List[DiscoveredResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListApplicationStatesRequestListApplicationStatesPaginateTypeDef = TypedDict(
-    "ListApplicationStatesRequestListApplicationStatesPaginateTypeDef",
-    {
-        "ApplicationIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
-    "_RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
-    {
-        "ProgressUpdateStream": str,
-        "MigrationTaskName": str,
-    },
-)
-_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef = TypedDict(
-    "_OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef(
-    _RequiredListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
-    _OptionalListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
-):
-    pass
-
-_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "ProgressUpdateStream": str,
-        "MigrationTaskName": str,
-    },
-)
-_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
-    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-):
-    pass
-
-ListMigrationTasksRequestListMigrationTasksPaginateTypeDef = TypedDict(
-    "ListMigrationTasksRequestListMigrationTasksPaginateTypeDef",
-    {
-        "ResourceName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef = TypedDict(
-    "ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListMigrationTasksResultTypeDef = TypedDict(
     "ListMigrationTasksResultTypeDef",
     {
         "NextToken": str,
         "MigrationTaskSummaryList": List[MigrationTaskSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProgressUpdateStreamsResultTypeDef = TypedDict(
     "ListProgressUpdateStreamsResultTypeDef",
     {
         "ProgressUpdateStreamSummaryList": List[ProgressUpdateStreamSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutResourceAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourceAttributesRequestRequestTypeDef",
     {
         "ProgressUpdateStream": str,
@@ -617,10 +617,10 @@
 ):
     pass
 
 DescribeMigrationTaskResultTypeDef = TypedDict(
     "DescribeMigrationTaskResultTypeDef",
     {
         "MigrationTask": MigrationTaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/PKG-INFO` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mgh
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mgh"></a>
 
 # types-aiobotocore-mgh
 
 [![PyPI - types-aiobotocore-mgh](https://img.shields.io/pypi/v/types-aiobotocore-mgh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgh)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mgh.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mgh)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mgh?color=blue)](https://pypistats.org/packages/types-aiobotocore-mgh)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub)
+[aiobotocore.MigrationHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mgh.html#MigrationHub)
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
 [types-aiobotocore-mgh docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mgh/).
 
 See how it helps to find and fix potential bugs:
 
@@ -345,41 +345,41 @@
 from types_aiobotocore_mgh.type_defs import (
     ApplicationStateTypeDef,
     CreatedArtifactTypeDef,
     DiscoveredResourceTypeDef,
     CreateProgressUpdateStreamRequestRequestTypeDef,
     DeleteProgressUpdateStreamRequestRequestTypeDef,
     DescribeApplicationStateRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeApplicationStateResultTypeDef,
     DescribeMigrationTaskRequestRequestTypeDef,
     DisassociateCreatedArtifactRequestRequestTypeDef,
     DisassociateDiscoveredResourceRequestRequestTypeDef,
     ImportMigrationTaskRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationStatesRequestListApplicationStatesPaginateTypeDef,
     ListApplicationStatesRequestRequestTypeDef,
+    ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
     ListCreatedArtifactsRequestRequestTypeDef,
+    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
+    ListMigrationTasksRequestListMigrationTasksPaginateTypeDef,
     ListMigrationTasksRequestRequestTypeDef,
     MigrationTaskSummaryTypeDef,
+    ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef,
     ListProgressUpdateStreamsRequestRequestTypeDef,
     ProgressUpdateStreamSummaryTypeDef,
     ResourceAttributeTypeDef,
     TaskTypeDef,
     NotifyApplicationStateRequestRequestTypeDef,
-    AssociateCreatedArtifactRequestRequestTypeDef,
-    AssociateDiscoveredResourceRequestRequestTypeDef,
-    DescribeApplicationStateResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ListApplicationStatesResultTypeDef,
+    AssociateCreatedArtifactRequestRequestTypeDef,
     ListCreatedArtifactsResultTypeDef,
+    AssociateDiscoveredResourceRequestRequestTypeDef,
     ListDiscoveredResourcesResultTypeDef,
-    ListApplicationStatesRequestListApplicationStatesPaginateTypeDef,
-    ListCreatedArtifactsRequestListCreatedArtifactsPaginateTypeDef,
-    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    ListMigrationTasksRequestListMigrationTasksPaginateTypeDef,
-    ListProgressUpdateStreamsRequestListProgressUpdateStreamsPaginateTypeDef,
     ListMigrationTasksResultTypeDef,
     ListProgressUpdateStreamsResultTypeDef,
     PutResourceAttributesRequestRequestTypeDef,
     MigrationTaskTypeDef,
     NotifyMigrationTaskStateRequestRequestTypeDef,
     DescribeMigrationTaskResultTypeDef,
 )
@@ -392,43 +392,43 @@
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

### Comparing `types-aiobotocore-mgh-2.5.0.post1/types_aiobotocore_mgh.egg-info/SOURCES.txt` & `types-aiobotocore-mgh-2.5.1/types_aiobotocore_mgh.egg-info/SOURCES.txt`

 * *Files identical despite different names*

