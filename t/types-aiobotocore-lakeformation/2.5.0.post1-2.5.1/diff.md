# Comparing `tmp/types-aiobotocore-lakeformation-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lakeformation-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lakeformation-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:52 2023, max compression
+gzip compressed data, was "types-aiobotocore-lakeformation-2.5.1.tar", last modified: Wed Jun 28 01:43:44 2023, max compression
```

## Comparing `types-aiobotocore-lakeformation-2.5.0.post1.tar` & `types-aiobotocore-lakeformation-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:52.411354 types-aiobotocore-lakeformation-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19009 2023-03-11 12:26:52.411354 types-aiobotocore-lakeformation-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17414 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:52.411354 types-aiobotocore-lakeformation-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:52.411354 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/
--rw-r--r--   0 runner    (1001) docker     (123)     1583 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1582 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    38168 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    38109 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10043 2023-03-11 12:17:09.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10041 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7189 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7181 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    47029 2023-03-11 12:17:09.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    46946 2023-03-11 12:17:09.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:08.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:52.411354 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19009 2023-03-11 12:26:52.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:26:52.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:52.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:52.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:52.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:52.000000 types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.590165 types-aiobotocore-lakeformation-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19139 2023-06-28 01:43:44.590165 types-aiobotocore-lakeformation-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17550 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:44.590165 types-aiobotocore-lakeformation-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2160 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.574165 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/
+-rw-r--r--   0 runner    (1001) docker     (123)     1583 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1582 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39391 2023-06-28 01:33:49.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39330 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10332 2023-06-28 01:33:50.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10330 2023-06-28 01:33:50.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7079 2023-06-28 01:33:49.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7072 2023-06-28 01:33:49.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    48272 2023-06-28 01:33:51.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48187 2023-06-28 01:33:50.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:48.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.590165 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19139 2023-06-28 01:43:44.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:43:44.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:44.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:44.000000 types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/LICENSE` & `types-aiobotocore-lakeformation-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lakeformation-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lakeformation
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LakeFormation 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LakeFormation 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lakeformation"></a>
 
 # types-aiobotocore-lakeformation
 
 [![PyPI - types-aiobotocore-lakeformation](https://img.shields.io/pypi/v/types-aiobotocore-lakeformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lakeformation)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lakeformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lakeformation)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lakeformation?color=blue)](https://pypistats.org/packages/types-aiobotocore-lakeformation)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LakeFormation 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
+[aiobotocore.LakeFormation 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
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
 [types-aiobotocore-lakeformation docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/).
 
 See how it helps to find and fix potential bugs:
 
@@ -347,23 +347,24 @@
 
 `types_aiobotocore_lakeformation.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lakeformation.type_defs import (
     LFTagPairTypeDef,
-    ResponseMetadataTypeDef,
     AddObjectInputTypeDef,
     AssumeDecoratedRoleWithSAMLRequestRequestTypeDef,
+    AssumeDecoratedRoleWithSAMLResponseTypeDef,
     AuditContextTypeDef,
     ErrorDetailTypeDef,
     DataLakePrincipalTypeDef,
     CancelTransactionRequestRequestTypeDef,
     ColumnWildcardTypeDef,
     CommitTransactionRequestRequestTypeDef,
+    CommitTransactionResponseTypeDef,
     CreateLFTagRequestRequestTypeDef,
     DataCellsFilterResourceTypeDef,
     RowFilterTypeDef,
     DataLocationResourceTypeDef,
     DatabaseResourceTypeDef,
     DeleteDataCellsFilterRequestRequestTypeDef,
     DeleteLFTagRequestRequestTypeDef,
@@ -374,52 +375,54 @@
     ResourceInfoTypeDef,
     DescribeTransactionRequestRequestTypeDef,
     TransactionDescriptionTypeDef,
     DetailsMapTypeDef,
     ExecutionStatisticsTypeDef,
     ExtendTransactionRequestRequestTypeDef,
     FilterConditionTypeDef,
+    GetDataCellsFilterRequestRequestTypeDef,
     GetDataLakeSettingsRequestRequestTypeDef,
     GetEffectivePermissionsForPathRequestRequestTypeDef,
     GetLFTagRequestRequestTypeDef,
+    GetLFTagResponseTypeDef,
     GetQueryStateRequestRequestTypeDef,
+    GetQueryStateResponseTypeDef,
     GetQueryStatisticsRequestRequestTypeDef,
     PlanningStatisticsTypeDef,
     GetTableObjectsRequestRequestTypeDef,
     PartitionValueListTypeDef,
+    GetTemporaryGluePartitionCredentialsResponseTypeDef,
+    GetTemporaryGlueTableCredentialsResponseTypeDef,
     GetWorkUnitResultsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorkUnitResultsResponseTypeDef,
+    GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
     GetWorkUnitsRequestRequestTypeDef,
     WorkUnitRangeTypeDef,
     LFTagKeyResourceTypeDef,
     LFTagTypeDef,
     TableResourceTypeDef,
+    ListLFTagsRequestListLFTagsPaginateTypeDef,
     ListLFTagsRequestRequestTypeDef,
     ListTableStorageOptimizersRequestRequestTypeDef,
     StorageOptimizerTypeDef,
     ListTransactionsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     TableObjectTypeDef,
     QueryPlanningContextTypeDef,
     RegisterResourceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    StartQueryPlanningResponseTypeDef,
     StartTransactionRequestRequestTypeDef,
+    StartTransactionResponseTypeDef,
     UpdateLFTagRequestRequestTypeDef,
     UpdateResourceRequestRequestTypeDef,
     UpdateTableStorageOptimizerRequestRequestTypeDef,
+    UpdateTableStorageOptimizerResponseTypeDef,
     ColumnLFTagTypeDef,
-    AssumeDecoratedRoleWithSAMLResponseTypeDef,
-    CommitTransactionResponseTypeDef,
-    GetLFTagResponseTypeDef,
-    GetQueryStateResponseTypeDef,
-    GetTemporaryGluePartitionCredentialsResponseTypeDef,
-    GetTemporaryGlueTableCredentialsResponseTypeDef,
-    GetWorkUnitResultsResponseTypeDef,
     ListLFTagsResponseTypeDef,
-    StartQueryPlanningResponseTypeDef,
-    StartTransactionResponseTypeDef,
-    UpdateTableStorageOptimizerResponseTypeDef,
     GetTemporaryGlueTableCredentialsRequestRequestTypeDef,
     LFTagErrorTypeDef,
     PrincipalPermissionsTypeDef,
     TableWithColumnsResourceTypeDef,
     DataCellsFilterTypeDef,
     TaggedDatabaseTypeDef,
     WriteOperationTypeDef,
@@ -427,16 +430,14 @@
     DescribeResourceResponseTypeDef,
     ListResourcesResponseTypeDef,
     DescribeTransactionResponseTypeDef,
     ListTransactionsResponseTypeDef,
     ListResourcesRequestRequestTypeDef,
     GetQueryStatisticsResponseTypeDef,
     GetTemporaryGluePartitionCredentialsRequestRequestTypeDef,
-    GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
-    ListLFTagsRequestListLFTagsPaginateTypeDef,
     GetWorkUnitsResponseTypeDef,
     LFTagPolicyResourceTypeDef,
     SearchDatabasesByLFTagsRequestRequestTypeDef,
     SearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef,
     SearchTablesByLFTagsRequestRequestTypeDef,
     SearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef,
     ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef,
@@ -446,15 +447,17 @@
     StartQueryPlanningRequestRequestTypeDef,
     GetResourceLFTagsResponseTypeDef,
     TaggedTableTypeDef,
     AddLFTagsToResourceResponseTypeDef,
     RemoveLFTagsFromResourceResponseTypeDef,
     DataLakeSettingsTypeDef,
     CreateDataCellsFilterRequestRequestTypeDef,
+    GetDataCellsFilterResponseTypeDef,
     ListDataCellsFilterResponseTypeDef,
+    UpdateDataCellsFilterRequestRequestTypeDef,
     SearchDatabasesByLFTagsResponseTypeDef,
     UpdateTableObjectsRequestRequestTypeDef,
     ResourceTypeDef,
     GetTableObjectsResponseTypeDef,
     SearchTablesByLFTagsResponseTypeDef,
     GetDataLakeSettingsResponseTypeDef,
     PutDataLakeSettingsRequestRequestTypeDef,
@@ -483,43 +486,43 @@
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

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/README.md` & `types-aiobotocore-lakeformation-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lakeformation"></a>
 
 # types-aiobotocore-lakeformation
 
 [![PyPI - types-aiobotocore-lakeformation](https://img.shields.io/pypi/v/types-aiobotocore-lakeformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lakeformation)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lakeformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lakeformation)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lakeformation?color=blue)](https://pypistats.org/packages/types-aiobotocore-lakeformation)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LakeFormation 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
+[aiobotocore.LakeFormation 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
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
 [types-aiobotocore-lakeformation docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/).
 
 See how it helps to find and fix potential bugs:
 
@@ -314,23 +314,24 @@
 
 `types_aiobotocore_lakeformation.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lakeformation.type_defs import (
     LFTagPairTypeDef,
-    ResponseMetadataTypeDef,
     AddObjectInputTypeDef,
     AssumeDecoratedRoleWithSAMLRequestRequestTypeDef,
+    AssumeDecoratedRoleWithSAMLResponseTypeDef,
     AuditContextTypeDef,
     ErrorDetailTypeDef,
     DataLakePrincipalTypeDef,
     CancelTransactionRequestRequestTypeDef,
     ColumnWildcardTypeDef,
     CommitTransactionRequestRequestTypeDef,
+    CommitTransactionResponseTypeDef,
     CreateLFTagRequestRequestTypeDef,
     DataCellsFilterResourceTypeDef,
     RowFilterTypeDef,
     DataLocationResourceTypeDef,
     DatabaseResourceTypeDef,
     DeleteDataCellsFilterRequestRequestTypeDef,
     DeleteLFTagRequestRequestTypeDef,
@@ -341,52 +342,54 @@
     ResourceInfoTypeDef,
     DescribeTransactionRequestRequestTypeDef,
     TransactionDescriptionTypeDef,
     DetailsMapTypeDef,
     ExecutionStatisticsTypeDef,
     ExtendTransactionRequestRequestTypeDef,
     FilterConditionTypeDef,
+    GetDataCellsFilterRequestRequestTypeDef,
     GetDataLakeSettingsRequestRequestTypeDef,
     GetEffectivePermissionsForPathRequestRequestTypeDef,
     GetLFTagRequestRequestTypeDef,
+    GetLFTagResponseTypeDef,
     GetQueryStateRequestRequestTypeDef,
+    GetQueryStateResponseTypeDef,
     GetQueryStatisticsRequestRequestTypeDef,
     PlanningStatisticsTypeDef,
     GetTableObjectsRequestRequestTypeDef,
     PartitionValueListTypeDef,
+    GetTemporaryGluePartitionCredentialsResponseTypeDef,
+    GetTemporaryGlueTableCredentialsResponseTypeDef,
     GetWorkUnitResultsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorkUnitResultsResponseTypeDef,
+    GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
     GetWorkUnitsRequestRequestTypeDef,
     WorkUnitRangeTypeDef,
     LFTagKeyResourceTypeDef,
     LFTagTypeDef,
     TableResourceTypeDef,
+    ListLFTagsRequestListLFTagsPaginateTypeDef,
     ListLFTagsRequestRequestTypeDef,
     ListTableStorageOptimizersRequestRequestTypeDef,
     StorageOptimizerTypeDef,
     ListTransactionsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     TableObjectTypeDef,
     QueryPlanningContextTypeDef,
     RegisterResourceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    StartQueryPlanningResponseTypeDef,
     StartTransactionRequestRequestTypeDef,
+    StartTransactionResponseTypeDef,
     UpdateLFTagRequestRequestTypeDef,
     UpdateResourceRequestRequestTypeDef,
     UpdateTableStorageOptimizerRequestRequestTypeDef,
+    UpdateTableStorageOptimizerResponseTypeDef,
     ColumnLFTagTypeDef,
-    AssumeDecoratedRoleWithSAMLResponseTypeDef,
-    CommitTransactionResponseTypeDef,
-    GetLFTagResponseTypeDef,
-    GetQueryStateResponseTypeDef,
-    GetTemporaryGluePartitionCredentialsResponseTypeDef,
-    GetTemporaryGlueTableCredentialsResponseTypeDef,
-    GetWorkUnitResultsResponseTypeDef,
     ListLFTagsResponseTypeDef,
-    StartQueryPlanningResponseTypeDef,
-    StartTransactionResponseTypeDef,
-    UpdateTableStorageOptimizerResponseTypeDef,
     GetTemporaryGlueTableCredentialsRequestRequestTypeDef,
     LFTagErrorTypeDef,
     PrincipalPermissionsTypeDef,
     TableWithColumnsResourceTypeDef,
     DataCellsFilterTypeDef,
     TaggedDatabaseTypeDef,
     WriteOperationTypeDef,
@@ -394,16 +397,14 @@
     DescribeResourceResponseTypeDef,
     ListResourcesResponseTypeDef,
     DescribeTransactionResponseTypeDef,
     ListTransactionsResponseTypeDef,
     ListResourcesRequestRequestTypeDef,
     GetQueryStatisticsResponseTypeDef,
     GetTemporaryGluePartitionCredentialsRequestRequestTypeDef,
-    GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
-    ListLFTagsRequestListLFTagsPaginateTypeDef,
     GetWorkUnitsResponseTypeDef,
     LFTagPolicyResourceTypeDef,
     SearchDatabasesByLFTagsRequestRequestTypeDef,
     SearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef,
     SearchTablesByLFTagsRequestRequestTypeDef,
     SearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef,
     ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef,
@@ -413,15 +414,17 @@
     StartQueryPlanningRequestRequestTypeDef,
     GetResourceLFTagsResponseTypeDef,
     TaggedTableTypeDef,
     AddLFTagsToResourceResponseTypeDef,
     RemoveLFTagsFromResourceResponseTypeDef,
     DataLakeSettingsTypeDef,
     CreateDataCellsFilterRequestRequestTypeDef,
+    GetDataCellsFilterResponseTypeDef,
     ListDataCellsFilterResponseTypeDef,
+    UpdateDataCellsFilterRequestRequestTypeDef,
     SearchDatabasesByLFTagsResponseTypeDef,
     UpdateTableObjectsRequestRequestTypeDef,
     ResourceTypeDef,
     GetTableObjectsResponseTypeDef,
     SearchTablesByLFTagsResponseTypeDef,
     GetDataLakeSettingsResponseTypeDef,
     PutDataLakeSettingsRequestRequestTypeDef,
@@ -450,43 +453,43 @@
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

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/setup.py` & `types-aiobotocore-lakeformation-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lakeformation.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lakeformation",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lakeformation"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LakeFormation 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LakeFormation 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/"
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

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/__init__.py` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/__init__.pyi` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/client.py` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -47,14 +47,15 @@
     CommitTransactionResponseTypeDef,
     DataCellsFilterTypeDef,
     DataLakePrincipalTypeDef,
     DataLakeSettingsTypeDef,
     DescribeResourceResponseTypeDef,
     DescribeTransactionResponseTypeDef,
     FilterConditionTypeDef,
+    GetDataCellsFilterResponseTypeDef,
     GetDataLakeSettingsResponseTypeDef,
     GetEffectivePermissionsForPathResponseTypeDef,
     GetLFTagResponseTypeDef,
     GetQueryStateResponseTypeDef,
     GetQueryStatisticsResponseTypeDef,
     GetResourceLFTagsResponseTypeDef,
     GetTableObjectsResponseTypeDef,
@@ -321,14 +322,24 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#generate_presigned_url)
         """
 
+    async def get_data_cells_filter(
+        self, *, TableCatalogId: str, DatabaseName: str, TableName: str, Name: str
+    ) -> GetDataCellsFilterResponseTypeDef:
+        """
+        Returns a data cells filter.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_data_cells_filter)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#get_data_cells_filter)
+        """
+
     async def get_data_lake_settings(
         self, *, CatalogId: str = ...
     ) -> GetDataLakeSettingsResponseTypeDef:
         """
         Retrieves the list of the data lake administrators of a Lake Formation-managed
         data lake.
 
@@ -571,15 +582,20 @@
         resources managed by Lake Formation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.put_data_lake_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#put_data_lake_settings)
         """
 
     async def register_resource(
-        self, *, ResourceArn: str, UseServiceLinkedRole: bool = ..., RoleArn: str = ...
+        self,
+        *,
+        ResourceArn: str,
+        UseServiceLinkedRole: bool = ...,
+        RoleArn: str = ...,
+        WithFederation: bool = ...
     ) -> Dict[str, Any]:
         """
         Registers the resource as managed by the Data Catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.register_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#register_resource)
         """
@@ -631,15 +647,15 @@
         *,
         Expression: Sequence[LFTagTypeDef],
         NextToken: str = ...,
         MaxResults: int = ...,
         CatalogId: str = ...
     ) -> SearchTablesByLFTagsResponseTypeDef:
         """
-        This operation allows a search on `TABLE` resources by `LFTag` s.
+        This operation allows a search on `TABLE` resources by `LFTag`s.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.search_tables_by_lf_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#search_tables_by_lf_tags)
         """
 
     async def start_query_planning(
         self, *, QueryPlanningContext: QueryPlanningContextTypeDef, QueryString: str
@@ -657,14 +673,24 @@
         """
         Starts a new transaction and returns its transaction ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.start_transaction)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#start_transaction)
         """
 
+    async def update_data_cells_filter(
+        self, *, TableData: DataCellsFilterTypeDef
+    ) -> Dict[str, Any]:
+        """
+        Updates a data cell filter.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_data_cells_filter)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#update_data_cells_filter)
+        """
+
     async def update_lf_tag(
         self,
         *,
         TagKey: str,
         CatalogId: str = ...,
         TagValuesToDelete: Sequence[str] = ...,
         TagValuesToAdd: Sequence[str] = ...
@@ -672,15 +698,17 @@
         """
         Updates the list of possible values for the specified LF-tag key.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_lf_tag)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#update_lf_tag)
         """
 
-    async def update_resource(self, *, RoleArn: str, ResourceArn: str) -> Dict[str, Any]:
+    async def update_resource(
+        self, *, RoleArn: str, ResourceArn: str, WithFederation: bool = ...
+    ) -> Dict[str, Any]:
         """
         Updates the data access role used for vending access to the given (registered)
         resource in Lake Formation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#update_resource)
         """
```

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/client.pyi` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -47,14 +47,15 @@
     CommitTransactionResponseTypeDef,
     DataCellsFilterTypeDef,
     DataLakePrincipalTypeDef,
     DataLakeSettingsTypeDef,
     DescribeResourceResponseTypeDef,
     DescribeTransactionResponseTypeDef,
     FilterConditionTypeDef,
+    GetDataCellsFilterResponseTypeDef,
     GetDataLakeSettingsResponseTypeDef,
     GetEffectivePermissionsForPathResponseTypeDef,
     GetLFTagResponseTypeDef,
     GetQueryStateResponseTypeDef,
     GetQueryStatisticsResponseTypeDef,
     GetResourceLFTagsResponseTypeDef,
     GetTableObjectsResponseTypeDef,
@@ -298,14 +299,23 @@
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#generate_presigned_url)
         """
+    async def get_data_cells_filter(
+        self, *, TableCatalogId: str, DatabaseName: str, TableName: str, Name: str
+    ) -> GetDataCellsFilterResponseTypeDef:
+        """
+        Returns a data cells filter.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.get_data_cells_filter)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#get_data_cells_filter)
+        """
     async def get_data_lake_settings(
         self, *, CatalogId: str = ...
     ) -> GetDataLakeSettingsResponseTypeDef:
         """
         Retrieves the list of the data lake administrators of a Lake Formation-managed
         data lake.
 
@@ -529,15 +539,20 @@
         Sets the list of data lake administrators who have admin privileges on all
         resources managed by Lake Formation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.put_data_lake_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#put_data_lake_settings)
         """
     async def register_resource(
-        self, *, ResourceArn: str, UseServiceLinkedRole: bool = ..., RoleArn: str = ...
+        self,
+        *,
+        ResourceArn: str,
+        UseServiceLinkedRole: bool = ...,
+        RoleArn: str = ...,
+        WithFederation: bool = ...
     ) -> Dict[str, Any]:
         """
         Registers the resource as managed by the Data Catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.register_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#register_resource)
         """
@@ -585,15 +600,15 @@
         *,
         Expression: Sequence[LFTagTypeDef],
         NextToken: str = ...,
         MaxResults: int = ...,
         CatalogId: str = ...
     ) -> SearchTablesByLFTagsResponseTypeDef:
         """
-        This operation allows a search on `TABLE` resources by `LFTag` s.
+        This operation allows a search on `TABLE` resources by `LFTag`s.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.search_tables_by_lf_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#search_tables_by_lf_tags)
         """
     async def start_query_planning(
         self, *, QueryPlanningContext: QueryPlanningContextTypeDef, QueryString: str
     ) -> StartQueryPlanningResponseTypeDef:
@@ -608,29 +623,40 @@
     ) -> StartTransactionResponseTypeDef:
         """
         Starts a new transaction and returns its transaction ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.start_transaction)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#start_transaction)
         """
+    async def update_data_cells_filter(
+        self, *, TableData: DataCellsFilterTypeDef
+    ) -> Dict[str, Any]:
+        """
+        Updates a data cell filter.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_data_cells_filter)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#update_data_cells_filter)
+        """
     async def update_lf_tag(
         self,
         *,
         TagKey: str,
         CatalogId: str = ...,
         TagValuesToDelete: Sequence[str] = ...,
         TagValuesToAdd: Sequence[str] = ...
     ) -> Dict[str, Any]:
         """
         Updates the list of possible values for the specified LF-tag key.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_lf_tag)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#update_lf_tag)
         """
-    async def update_resource(self, *, RoleArn: str, ResourceArn: str) -> Dict[str, Any]:
+    async def update_resource(
+        self, *, RoleArn: str, ResourceArn: str, WithFederation: bool = ...
+    ) -> Dict[str, Any]:
         """
         Updates the data access role used for vending access to the given (registered)
         resource in Lake Formation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Client.update_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/client/#update_resource)
         """
```

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/literals.py` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -145,14 +145,15 @@
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
@@ -231,14 +232,15 @@
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
@@ -249,14 +251,15 @@
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
@@ -292,14 +295,15 @@
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
@@ -318,16 +322,19 @@
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
@@ -411,15 +418,17 @@
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
@@ -453,21 +462,25 @@
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
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

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/literals.pyi` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -143,14 +143,15 @@
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
@@ -229,14 +230,15 @@
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
@@ -247,14 +249,15 @@
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
@@ -290,14 +293,15 @@
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
@@ -316,16 +320,19 @@
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
@@ -409,15 +416,17 @@
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
@@ -451,21 +460,25 @@
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
+    "ap-southeast-3",
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

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/paginator.py` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         get_work_units_paginator: GetWorkUnitsPaginator = client.get_paginator("get_work_units")
         list_data_cells_filter_paginator: ListDataCellsFilterPaginator = client.get_paginator("list_data_cells_filter")
         list_lf_tags_paginator: ListLFTagsPaginator = client.get_paginator("list_lf_tags")
         search_databases_by_lf_tags_paginator: SearchDatabasesByLFTagsPaginator = client.get_paginator("search_databases_by_lf_tags")
         search_tables_by_lf_tags_paginator: SearchTablesByLFTagsPaginator = client.get_paginator("search_tables_by_lf_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceShareTypeType
 from .type_defs import (
     GetWorkUnitsResponseTypeDef,
@@ -42,117 +41,104 @@
     ListLFTagsResponseTypeDef,
     PaginatorConfigTypeDef,
     SearchDatabasesByLFTagsResponseTypeDef,
     SearchTablesByLFTagsResponseTypeDef,
     TableResourceTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetWorkUnitsPaginator",
     "ListDataCellsFilterPaginator",
     "ListLFTagsPaginator",
     "SearchDatabasesByLFTagsPaginator",
     "SearchTablesByLFTagsPaginator",
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
 class GetWorkUnitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.GetWorkUnits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#getworkunitspaginator)
     """
 
     def paginate(
-        self, *, QueryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetWorkUnitsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.GetWorkUnits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#getworkunitspaginator)
         """
 
-
 class ListDataCellsFilterPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListDataCellsFilter)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listdatacellsfilterpaginator)
     """
 
     def paginate(
-        self, *, Table: TableResourceTypeDef = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Table: TableResourceTypeDef = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataCellsFilterResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListDataCellsFilter.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listdatacellsfilterpaginator)
         """
 
-
 class ListLFTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListLFTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listlftagspaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogId: str = ...,
         ResourceShareType: ResourceShareTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLFTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListLFTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listlftagspaginator)
         """
 
-
 class SearchDatabasesByLFTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchDatabasesByLFTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchdatabasesbylftagspaginator)
     """
 
     def paginate(
         self,
         *,
         Expression: Sequence[LFTagTypeDef],
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchDatabasesByLFTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchDatabasesByLFTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchdatabasesbylftagspaginator)
         """
 
-
 class SearchTablesByLFTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchTablesByLFTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchtablesbylftagspaginator)
     """
 
     def paginate(
         self,
         *,
         Expression: Sequence[LFTagTypeDef],
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchTablesByLFTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchTablesByLFTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchtablesbylftagspaginator)
         """
```

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/paginator.pyi` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         get_work_units_paginator: GetWorkUnitsPaginator = client.get_paginator("get_work_units")
         list_data_cells_filter_paginator: ListDataCellsFilterPaginator = client.get_paginator("list_data_cells_filter")
         list_lf_tags_paginator: ListLFTagsPaginator = client.get_paginator("list_lf_tags")
         search_databases_by_lf_tags_paginator: SearchDatabasesByLFTagsPaginator = client.get_paginator("search_databases_by_lf_tags")
         search_tables_by_lf_tags_paginator: SearchTablesByLFTagsPaginator = client.get_paginator("search_tables_by_lf_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceShareTypeType
 from .type_defs import (
     GetWorkUnitsResponseTypeDef,
@@ -42,109 +41,111 @@
     ListLFTagsResponseTypeDef,
     PaginatorConfigTypeDef,
     SearchDatabasesByLFTagsResponseTypeDef,
     SearchTablesByLFTagsResponseTypeDef,
     TableResourceTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetWorkUnitsPaginator",
     "ListDataCellsFilterPaginator",
     "ListLFTagsPaginator",
     "SearchDatabasesByLFTagsPaginator",
     "SearchTablesByLFTagsPaginator",
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
 class GetWorkUnitsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.GetWorkUnits)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#getworkunitspaginator)
     """
 
     def paginate(
-        self, *, QueryId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueryId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetWorkUnitsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.GetWorkUnits.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#getworkunitspaginator)
         """
 
+
 class ListDataCellsFilterPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListDataCellsFilter)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listdatacellsfilterpaginator)
     """
 
     def paginate(
-        self, *, Table: TableResourceTypeDef = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Table: TableResourceTypeDef = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataCellsFilterResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListDataCellsFilter.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listdatacellsfilterpaginator)
         """
 
+
 class ListLFTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListLFTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listlftagspaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogId: str = ...,
         ResourceShareType: ResourceShareTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLFTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.ListLFTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#listlftagspaginator)
         """
 
+
 class SearchDatabasesByLFTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchDatabasesByLFTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchdatabasesbylftagspaginator)
     """
 
     def paginate(
         self,
         *,
         Expression: Sequence[LFTagTypeDef],
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchDatabasesByLFTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchDatabasesByLFTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchdatabasesbylftagspaginator)
         """
 
+
 class SearchTablesByLFTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchTablesByLFTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchtablesbylftagspaginator)
     """
 
     def paginate(
         self,
         *,
         Expression: Sequence[LFTagTypeDef],
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchTablesByLFTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation.Paginator.SearchTablesByLFTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/paginators/#searchtablesbylftagspaginator)
         """
```

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/type_defs.py` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -36,23 +36,24 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "LFTagPairTypeDef",
-    "ResponseMetadataTypeDef",
     "AddObjectInputTypeDef",
     "AssumeDecoratedRoleWithSAMLRequestRequestTypeDef",
+    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
     "AuditContextTypeDef",
     "ErrorDetailTypeDef",
     "DataLakePrincipalTypeDef",
     "CancelTransactionRequestRequestTypeDef",
     "ColumnWildcardTypeDef",
     "CommitTransactionRequestRequestTypeDef",
+    "CommitTransactionResponseTypeDef",
     "CreateLFTagRequestRequestTypeDef",
     "DataCellsFilterResourceTypeDef",
     "RowFilterTypeDef",
     "DataLocationResourceTypeDef",
     "DatabaseResourceTypeDef",
     "DeleteDataCellsFilterRequestRequestTypeDef",
     "DeleteLFTagRequestRequestTypeDef",
@@ -63,52 +64,54 @@
     "ResourceInfoTypeDef",
     "DescribeTransactionRequestRequestTypeDef",
     "TransactionDescriptionTypeDef",
     "DetailsMapTypeDef",
     "ExecutionStatisticsTypeDef",
     "ExtendTransactionRequestRequestTypeDef",
     "FilterConditionTypeDef",
+    "GetDataCellsFilterRequestRequestTypeDef",
     "GetDataLakeSettingsRequestRequestTypeDef",
     "GetEffectivePermissionsForPathRequestRequestTypeDef",
     "GetLFTagRequestRequestTypeDef",
+    "GetLFTagResponseTypeDef",
     "GetQueryStateRequestRequestTypeDef",
+    "GetQueryStateResponseTypeDef",
     "GetQueryStatisticsRequestRequestTypeDef",
     "PlanningStatisticsTypeDef",
     "GetTableObjectsRequestRequestTypeDef",
     "PartitionValueListTypeDef",
+    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
+    "GetTemporaryGlueTableCredentialsResponseTypeDef",
     "GetWorkUnitResultsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetWorkUnitResultsResponseTypeDef",
+    "GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
     "GetWorkUnitsRequestRequestTypeDef",
     "WorkUnitRangeTypeDef",
     "LFTagKeyResourceTypeDef",
     "LFTagTypeDef",
     "TableResourceTypeDef",
+    "ListLFTagsRequestListLFTagsPaginateTypeDef",
     "ListLFTagsRequestRequestTypeDef",
     "ListTableStorageOptimizersRequestRequestTypeDef",
     "StorageOptimizerTypeDef",
     "ListTransactionsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "TableObjectTypeDef",
     "QueryPlanningContextTypeDef",
     "RegisterResourceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartQueryPlanningResponseTypeDef",
     "StartTransactionRequestRequestTypeDef",
+    "StartTransactionResponseTypeDef",
     "UpdateLFTagRequestRequestTypeDef",
     "UpdateResourceRequestRequestTypeDef",
     "UpdateTableStorageOptimizerRequestRequestTypeDef",
+    "UpdateTableStorageOptimizerResponseTypeDef",
     "ColumnLFTagTypeDef",
-    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
-    "CommitTransactionResponseTypeDef",
-    "GetLFTagResponseTypeDef",
-    "GetQueryStateResponseTypeDef",
-    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
-    "GetTemporaryGlueTableCredentialsResponseTypeDef",
-    "GetWorkUnitResultsResponseTypeDef",
     "ListLFTagsResponseTypeDef",
-    "StartQueryPlanningResponseTypeDef",
-    "StartTransactionResponseTypeDef",
-    "UpdateTableStorageOptimizerResponseTypeDef",
     "GetTemporaryGlueTableCredentialsRequestRequestTypeDef",
     "LFTagErrorTypeDef",
     "PrincipalPermissionsTypeDef",
     "TableWithColumnsResourceTypeDef",
     "DataCellsFilterTypeDef",
     "TaggedDatabaseTypeDef",
     "WriteOperationTypeDef",
@@ -116,16 +119,14 @@
     "DescribeResourceResponseTypeDef",
     "ListResourcesResponseTypeDef",
     "DescribeTransactionResponseTypeDef",
     "ListTransactionsResponseTypeDef",
     "ListResourcesRequestRequestTypeDef",
     "GetQueryStatisticsResponseTypeDef",
     "GetTemporaryGluePartitionCredentialsRequestRequestTypeDef",
-    "GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
-    "ListLFTagsRequestListLFTagsPaginateTypeDef",
     "GetWorkUnitsResponseTypeDef",
     "LFTagPolicyResourceTypeDef",
     "SearchDatabasesByLFTagsRequestRequestTypeDef",
     "SearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef",
     "SearchTablesByLFTagsRequestRequestTypeDef",
     "SearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef",
     "ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef",
@@ -135,15 +136,17 @@
     "StartQueryPlanningRequestRequestTypeDef",
     "GetResourceLFTagsResponseTypeDef",
     "TaggedTableTypeDef",
     "AddLFTagsToResourceResponseTypeDef",
     "RemoveLFTagsFromResourceResponseTypeDef",
     "DataLakeSettingsTypeDef",
     "CreateDataCellsFilterRequestRequestTypeDef",
+    "GetDataCellsFilterResponseTypeDef",
     "ListDataCellsFilterResponseTypeDef",
+    "UpdateDataCellsFilterRequestRequestTypeDef",
     "SearchDatabasesByLFTagsResponseTypeDef",
     "UpdateTableObjectsRequestRequestTypeDef",
     "ResourceTypeDef",
     "GetTableObjectsResponseTypeDef",
     "SearchTablesByLFTagsResponseTypeDef",
     "GetDataLakeSettingsResponseTypeDef",
     "PutDataLakeSettingsRequestRequestTypeDef",
@@ -180,25 +183,14 @@
 )
 
 
 class LFTagPairTypeDef(_RequiredLFTagPairTypeDef, _OptionalLFTagPairTypeDef):
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
 _RequiredAddObjectInputTypeDef = TypedDict(
     "_RequiredAddObjectInputTypeDef",
     {
         "Uri": str,
         "ETag": str,
         "Size": int,
     },
@@ -236,14 +228,25 @@
 class AssumeDecoratedRoleWithSAMLRequestRequestTypeDef(
     _RequiredAssumeDecoratedRoleWithSAMLRequestRequestTypeDef,
     _OptionalAssumeDecoratedRoleWithSAMLRequestRequestTypeDef,
 ):
     pass
 
 
+AssumeDecoratedRoleWithSAMLResponseTypeDef = TypedDict(
+    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
+    {
+        "AccessKeyId": str,
+        "SecretAccessKey": str,
+        "SessionToken": str,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AuditContextTypeDef = TypedDict(
     "AuditContextTypeDef",
     {
         "AdditionalAuditContext": str,
     },
     total=False,
 )
@@ -283,14 +286,22 @@
 CommitTransactionRequestRequestTypeDef = TypedDict(
     "CommitTransactionRequestRequestTypeDef",
     {
         "TransactionId": str,
     },
 )
 
+CommitTransactionResponseTypeDef = TypedDict(
+    "CommitTransactionResponseTypeDef",
+    {
+        "TransactionStatus": TransactionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateLFTagRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLFTagRequestRequestTypeDef",
     {
         "TagKey": str,
         "TagValues": Sequence[str],
     },
 )
@@ -458,14 +469,15 @@
 
 ResourceInfoTypeDef = TypedDict(
     "ResourceInfoTypeDef",
     {
         "ResourceArn": str,
         "RoleArn": str,
         "LastModified": datetime,
+        "WithFederation": bool,
     },
     total=False,
 )
 
 DescribeTransactionRequestRequestTypeDef = TypedDict(
     "DescribeTransactionRequestRequestTypeDef",
     {
@@ -516,14 +528,24 @@
         "Field": FieldNameStringType,
         "ComparisonOperator": ComparisonOperatorType,
         "StringValueList": Sequence[str],
     },
     total=False,
 )
 
+GetDataCellsFilterRequestRequestTypeDef = TypedDict(
+    "GetDataCellsFilterRequestRequestTypeDef",
+    {
+        "TableCatalogId": str,
+        "DatabaseName": str,
+        "TableName": str,
+        "Name": str,
+    },
+)
+
 GetDataLakeSettingsRequestRequestTypeDef = TypedDict(
     "GetDataLakeSettingsRequestRequestTypeDef",
     {
         "CatalogId": str,
     },
     total=False,
 )
@@ -569,21 +591,40 @@
 
 class GetLFTagRequestRequestTypeDef(
     _RequiredGetLFTagRequestRequestTypeDef, _OptionalGetLFTagRequestRequestTypeDef
 ):
     pass
 
 
+GetLFTagResponseTypeDef = TypedDict(
+    "GetLFTagResponseTypeDef",
+    {
+        "CatalogId": str,
+        "TagKey": str,
+        "TagValues": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetQueryStateRequestRequestTypeDef = TypedDict(
     "GetQueryStateRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 
+GetQueryStateResponseTypeDef = TypedDict(
+    "GetQueryStateResponseTypeDef",
+    {
+        "Error": str,
+        "State": QueryStateStringType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetQueryStatisticsRequestRequestTypeDef = TypedDict(
     "GetQueryStatisticsRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 
@@ -628,33 +669,75 @@
 PartitionValueListTypeDef = TypedDict(
     "PartitionValueListTypeDef",
     {
         "Values": Sequence[str],
     },
 )
 
+GetTemporaryGluePartitionCredentialsResponseTypeDef = TypedDict(
+    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
+    {
+        "AccessKeyId": str,
+        "SecretAccessKey": str,
+        "SessionToken": str,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetTemporaryGlueTableCredentialsResponseTypeDef = TypedDict(
+    "GetTemporaryGlueTableCredentialsResponseTypeDef",
+    {
+        "AccessKeyId": str,
+        "SecretAccessKey": str,
+        "SessionToken": str,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkUnitResultsRequestRequestTypeDef = TypedDict(
     "GetWorkUnitResultsRequestRequestTypeDef",
     {
         "QueryId": str,
         "WorkUnitId": int,
         "WorkUnitToken": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetWorkUnitResultsResponseTypeDef = TypedDict(
+    "GetWorkUnitResultsResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ResultStream": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
+    "_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
+    {
+        "QueryId": str,
+    },
+)
+_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
+    "_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef(
+    _RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
+    _OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetWorkUnitsRequestRequestTypeDef = TypedDict(
     "_RequiredGetWorkUnitsRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 _OptionalGetWorkUnitsRequestRequestTypeDef = TypedDict(
@@ -727,14 +810,24 @@
 )
 
 
 class TableResourceTypeDef(_RequiredTableResourceTypeDef, _OptionalTableResourceTypeDef):
     pass
 
 
+ListLFTagsRequestListLFTagsPaginateTypeDef = TypedDict(
+    "ListLFTagsRequestListLFTagsPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "ResourceShareType": ResourceShareTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLFTagsRequestRequestTypeDef = TypedDict(
     "ListLFTagsRequestRequestTypeDef",
     {
         "CatalogId": str,
         "ResourceShareType": ResourceShareTypeType,
         "MaxResults": int,
         "NextToken": str,
@@ -787,14 +880,24 @@
         "StatusFilter": TransactionStatusFilterType,
         "MaxResults": int,
         "NextToken": str,
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
 TableObjectTypeDef = TypedDict(
     "TableObjectTypeDef",
     {
         "Uri": str,
         "ETag": str,
         "Size": int,
     },
@@ -832,33 +935,61 @@
     },
 )
 _OptionalRegisterResourceRequestRequestTypeDef = TypedDict(
     "_OptionalRegisterResourceRequestRequestTypeDef",
     {
         "UseServiceLinkedRole": bool,
         "RoleArn": str,
+        "WithFederation": bool,
     },
     total=False,
 )
 
 
 class RegisterResourceRequestRequestTypeDef(
     _RequiredRegisterResourceRequestRequestTypeDef, _OptionalRegisterResourceRequestRequestTypeDef
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
+StartQueryPlanningResponseTypeDef = TypedDict(
+    "StartQueryPlanningResponseTypeDef",
+    {
+        "QueryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartTransactionRequestRequestTypeDef = TypedDict(
     "StartTransactionRequestRequestTypeDef",
     {
         "TransactionType": TransactionTypeType,
     },
     total=False,
 )
 
+StartTransactionResponseTypeDef = TypedDict(
+    "StartTransactionResponseTypeDef",
+    {
+        "TransactionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateLFTagRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLFTagRequestRequestTypeDef",
     {
         "TagKey": str,
     },
 )
 _OptionalUpdateLFTagRequestRequestTypeDef = TypedDict(
@@ -874,21 +1005,35 @@
 
 class UpdateLFTagRequestRequestTypeDef(
     _RequiredUpdateLFTagRequestRequestTypeDef, _OptionalUpdateLFTagRequestRequestTypeDef
 ):
     pass
 
 
-UpdateResourceRequestRequestTypeDef = TypedDict(
-    "UpdateResourceRequestRequestTypeDef",
+_RequiredUpdateResourceRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateResourceRequestRequestTypeDef",
     {
         "RoleArn": str,
         "ResourceArn": str,
     },
 )
+_OptionalUpdateResourceRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateResourceRequestRequestTypeDef",
+    {
+        "WithFederation": bool,
+    },
+    total=False,
+)
+
+
+class UpdateResourceRequestRequestTypeDef(
+    _RequiredUpdateResourceRequestRequestTypeDef, _OptionalUpdateResourceRequestRequestTypeDef
+):
+    pass
+
 
 _RequiredUpdateTableStorageOptimizerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTableStorageOptimizerRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
         "StorageOptimizerConfig": Mapping[OptimizerTypeType, Mapping[str, str]],
@@ -906,121 +1051,37 @@
 class UpdateTableStorageOptimizerRequestRequestTypeDef(
     _RequiredUpdateTableStorageOptimizerRequestRequestTypeDef,
     _OptionalUpdateTableStorageOptimizerRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateTableStorageOptimizerResponseTypeDef = TypedDict(
+    "UpdateTableStorageOptimizerResponseTypeDef",
+    {
+        "Result": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ColumnLFTagTypeDef = TypedDict(
     "ColumnLFTagTypeDef",
     {
         "Name": str,
         "LFTags": List[LFTagPairTypeDef],
     },
     total=False,
 )
 
-AssumeDecoratedRoleWithSAMLResponseTypeDef = TypedDict(
-    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
-    {
-        "AccessKeyId": str,
-        "SecretAccessKey": str,
-        "SessionToken": str,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CommitTransactionResponseTypeDef = TypedDict(
-    "CommitTransactionResponseTypeDef",
-    {
-        "TransactionStatus": TransactionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLFTagResponseTypeDef = TypedDict(
-    "GetLFTagResponseTypeDef",
-    {
-        "CatalogId": str,
-        "TagKey": str,
-        "TagValues": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetQueryStateResponseTypeDef = TypedDict(
-    "GetQueryStateResponseTypeDef",
-    {
-        "Error": str,
-        "State": QueryStateStringType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemporaryGluePartitionCredentialsResponseTypeDef = TypedDict(
-    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
-    {
-        "AccessKeyId": str,
-        "SecretAccessKey": str,
-        "SessionToken": str,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemporaryGlueTableCredentialsResponseTypeDef = TypedDict(
-    "GetTemporaryGlueTableCredentialsResponseTypeDef",
-    {
-        "AccessKeyId": str,
-        "SecretAccessKey": str,
-        "SessionToken": str,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkUnitResultsResponseTypeDef = TypedDict(
-    "GetWorkUnitResultsResponseTypeDef",
-    {
-        "ResultStream": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListLFTagsResponseTypeDef = TypedDict(
     "ListLFTagsResponseTypeDef",
     {
         "LFTags": List[LFTagPairTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartQueryPlanningResponseTypeDef = TypedDict(
-    "StartQueryPlanningResponseTypeDef",
-    {
-        "QueryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTransactionResponseTypeDef = TypedDict(
-    "StartTransactionResponseTypeDef",
-    {
-        "TransactionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTableStorageOptimizerResponseTypeDef = TypedDict(
-    "UpdateTableStorageOptimizerResponseTypeDef",
-    {
-        "Result": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTemporaryGlueTableCredentialsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTemporaryGlueTableCredentialsRequestRequestTypeDef",
     {
         "TableArn": str,
@@ -1098,14 +1159,15 @@
 )
 _OptionalDataCellsFilterTypeDef = TypedDict(
     "_OptionalDataCellsFilterTypeDef",
     {
         "RowFilter": RowFilterTypeDef,
         "ColumnNames": Sequence[str],
         "ColumnWildcard": ColumnWildcardTypeDef,
+        "VersionId": str,
     },
     total=False,
 )
 
 
 class DataCellsFilterTypeDef(_RequiredDataCellsFilterTypeDef, _OptionalDataCellsFilterTypeDef):
     pass
@@ -1154,41 +1216,41 @@
     pass
 
 
 DescribeResourceResponseTypeDef = TypedDict(
     "DescribeResourceResponseTypeDef",
     {
         "ResourceInfo": ResourceInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResponseTypeDef = TypedDict(
     "ListResourcesResponseTypeDef",
     {
         "ResourceInfoList": List[ResourceInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTransactionResponseTypeDef = TypedDict(
     "DescribeTransactionResponseTypeDef",
     {
         "TransactionDescription": TransactionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTransactionsResponseTypeDef = TypedDict(
     "ListTransactionsResponseTypeDef",
     {
         "Transactions": List[TransactionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesRequestRequestTypeDef = TypedDict(
     "ListResourcesRequestRequestTypeDef",
     {
         "FilterConditionList": Sequence[FilterConditionTypeDef],
@@ -1200,15 +1262,15 @@
 
 GetQueryStatisticsResponseTypeDef = TypedDict(
     "GetQueryStatisticsResponseTypeDef",
     {
         "ExecutionStatistics": ExecutionStatisticsTypeDef,
         "PlanningStatistics": PlanningStatisticsTypeDef,
         "QuerySubmissionTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTemporaryGluePartitionCredentialsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTemporaryGluePartitionCredentialsRequestRequestTypeDef",
     {
         "TableArn": str,
@@ -1230,53 +1292,21 @@
 class GetTemporaryGluePartitionCredentialsRequestRequestTypeDef(
     _RequiredGetTemporaryGluePartitionCredentialsRequestRequestTypeDef,
     _OptionalGetTemporaryGluePartitionCredentialsRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
-    "_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
-    {
-        "QueryId": str,
-    },
-)
-_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
-    "_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef(
-    _RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
-    _OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
-):
-    pass
-
-
-ListLFTagsRequestListLFTagsPaginateTypeDef = TypedDict(
-    "ListLFTagsRequestListLFTagsPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "ResourceShareType": ResourceShareTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetWorkUnitsResponseTypeDef = TypedDict(
     "GetWorkUnitsResponseTypeDef",
     {
         "NextToken": str,
         "QueryId": str,
         "WorkUnitRanges": List[WorkUnitRangeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLFTagPolicyResourceTypeDef = TypedDict(
     "_RequiredLFTagPolicyResourceTypeDef",
     {
         "ResourceType": ResourceTypeType,
@@ -1328,15 +1358,15 @@
         "Expression": Sequence[LFTagTypeDef],
     },
 )
 _OptionalSearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef = TypedDict(
     "_OptionalSearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef",
     {
         "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class SearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef(
     _RequiredSearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef,
@@ -1375,15 +1405,15 @@
         "Expression": Sequence[LFTagTypeDef],
     },
 )
 _OptionalSearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef = TypedDict(
     "_OptionalSearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef",
     {
         "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class SearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef(
     _RequiredSearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef,
@@ -1392,15 +1422,15 @@
     pass
 
 
 ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef = TypedDict(
     "ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef",
     {
         "Table": TableResourceTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDataCellsFilterRequestRequestTypeDef = TypedDict(
     "ListDataCellsFilterRequestRequestTypeDef",
     {
@@ -1412,15 +1442,15 @@
 )
 
 ListTableStorageOptimizersResponseTypeDef = TypedDict(
     "ListTableStorageOptimizersResponseTypeDef",
     {
         "StorageOptimizerList": List[StorageOptimizerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PartitionObjectsTypeDef = TypedDict(
     "PartitionObjectsTypeDef",
     {
         "PartitionValues": List[str],
@@ -1439,15 +1469,15 @@
 
 GetResourceLFTagsResponseTypeDef = TypedDict(
     "GetResourceLFTagsResponseTypeDef",
     {
         "LFTagOnDatabase": List[LFTagPairTypeDef],
         "LFTagsOnTable": List[LFTagPairTypeDef],
         "LFTagsOnColumns": List[ColumnLFTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TaggedTableTypeDef = TypedDict(
     "TaggedTableTypeDef",
     {
         "Table": TableResourceTypeDef,
@@ -1458,23 +1488,23 @@
     total=False,
 )
 
 AddLFTagsToResourceResponseTypeDef = TypedDict(
     "AddLFTagsToResourceResponseTypeDef",
     {
         "Failures": List[LFTagErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveLFTagsFromResourceResponseTypeDef = TypedDict(
     "RemoveLFTagsFromResourceResponseTypeDef",
     {
         "Failures": List[LFTagErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataLakeSettingsTypeDef = TypedDict(
     "DataLakeSettingsTypeDef",
     {
         "DataLakeAdmins": List[DataLakePrincipalTypeDef],
@@ -1492,29 +1522,44 @@
 CreateDataCellsFilterRequestRequestTypeDef = TypedDict(
     "CreateDataCellsFilterRequestRequestTypeDef",
     {
         "TableData": DataCellsFilterTypeDef,
     },
 )
 
+GetDataCellsFilterResponseTypeDef = TypedDict(
+    "GetDataCellsFilterResponseTypeDef",
+    {
+        "DataCellsFilter": DataCellsFilterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListDataCellsFilterResponseTypeDef = TypedDict(
     "ListDataCellsFilterResponseTypeDef",
     {
         "DataCellsFilters": List[DataCellsFilterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateDataCellsFilterRequestRequestTypeDef = TypedDict(
+    "UpdateDataCellsFilterRequestRequestTypeDef",
+    {
+        "TableData": DataCellsFilterTypeDef,
     },
 )
 
 SearchDatabasesByLFTagsResponseTypeDef = TypedDict(
     "SearchDatabasesByLFTagsResponseTypeDef",
     {
         "NextToken": str,
         "DatabaseList": List[TaggedDatabaseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTableObjectsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTableObjectsRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -1555,32 +1600,32 @@
 )
 
 GetTableObjectsResponseTypeDef = TypedDict(
     "GetTableObjectsResponseTypeDef",
     {
         "Objects": List[PartitionObjectsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchTablesByLFTagsResponseTypeDef = TypedDict(
     "SearchTablesByLFTagsResponseTypeDef",
     {
         "NextToken": str,
         "TableList": List[TaggedTableTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataLakeSettingsResponseTypeDef = TypedDict(
     "GetDataLakeSettingsResponseTypeDef",
     {
         "DataLakeSettings": DataLakeSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutDataLakeSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredPutDataLakeSettingsRequestRequestTypeDef",
     {
         "DataLakeSettings": DataLakeSettingsTypeDef,
@@ -1822,35 +1867,35 @@
 
 
 GetEffectivePermissionsForPathResponseTypeDef = TypedDict(
     "GetEffectivePermissionsForPathResponseTypeDef",
     {
         "Permissions": List[PrincipalResourcePermissionsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPermissionsResponseTypeDef = TypedDict(
     "ListPermissionsResponseTypeDef",
     {
         "PrincipalResourcePermissions": List[PrincipalResourcePermissionsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGrantPermissionsResponseTypeDef = TypedDict(
     "BatchGrantPermissionsResponseTypeDef",
     {
         "Failures": List[BatchPermissionsFailureEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchRevokePermissionsResponseTypeDef = TypedDict(
     "BatchRevokePermissionsResponseTypeDef",
     {
         "Failures": List[BatchPermissionsFailureEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation/type_defs.pyi` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -35,23 +35,24 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "LFTagPairTypeDef",
-    "ResponseMetadataTypeDef",
     "AddObjectInputTypeDef",
     "AssumeDecoratedRoleWithSAMLRequestRequestTypeDef",
+    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
     "AuditContextTypeDef",
     "ErrorDetailTypeDef",
     "DataLakePrincipalTypeDef",
     "CancelTransactionRequestRequestTypeDef",
     "ColumnWildcardTypeDef",
     "CommitTransactionRequestRequestTypeDef",
+    "CommitTransactionResponseTypeDef",
     "CreateLFTagRequestRequestTypeDef",
     "DataCellsFilterResourceTypeDef",
     "RowFilterTypeDef",
     "DataLocationResourceTypeDef",
     "DatabaseResourceTypeDef",
     "DeleteDataCellsFilterRequestRequestTypeDef",
     "DeleteLFTagRequestRequestTypeDef",
@@ -62,52 +63,54 @@
     "ResourceInfoTypeDef",
     "DescribeTransactionRequestRequestTypeDef",
     "TransactionDescriptionTypeDef",
     "DetailsMapTypeDef",
     "ExecutionStatisticsTypeDef",
     "ExtendTransactionRequestRequestTypeDef",
     "FilterConditionTypeDef",
+    "GetDataCellsFilterRequestRequestTypeDef",
     "GetDataLakeSettingsRequestRequestTypeDef",
     "GetEffectivePermissionsForPathRequestRequestTypeDef",
     "GetLFTagRequestRequestTypeDef",
+    "GetLFTagResponseTypeDef",
     "GetQueryStateRequestRequestTypeDef",
+    "GetQueryStateResponseTypeDef",
     "GetQueryStatisticsRequestRequestTypeDef",
     "PlanningStatisticsTypeDef",
     "GetTableObjectsRequestRequestTypeDef",
     "PartitionValueListTypeDef",
+    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
+    "GetTemporaryGlueTableCredentialsResponseTypeDef",
     "GetWorkUnitResultsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetWorkUnitResultsResponseTypeDef",
+    "GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
     "GetWorkUnitsRequestRequestTypeDef",
     "WorkUnitRangeTypeDef",
     "LFTagKeyResourceTypeDef",
     "LFTagTypeDef",
     "TableResourceTypeDef",
+    "ListLFTagsRequestListLFTagsPaginateTypeDef",
     "ListLFTagsRequestRequestTypeDef",
     "ListTableStorageOptimizersRequestRequestTypeDef",
     "StorageOptimizerTypeDef",
     "ListTransactionsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "TableObjectTypeDef",
     "QueryPlanningContextTypeDef",
     "RegisterResourceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartQueryPlanningResponseTypeDef",
     "StartTransactionRequestRequestTypeDef",
+    "StartTransactionResponseTypeDef",
     "UpdateLFTagRequestRequestTypeDef",
     "UpdateResourceRequestRequestTypeDef",
     "UpdateTableStorageOptimizerRequestRequestTypeDef",
+    "UpdateTableStorageOptimizerResponseTypeDef",
     "ColumnLFTagTypeDef",
-    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
-    "CommitTransactionResponseTypeDef",
-    "GetLFTagResponseTypeDef",
-    "GetQueryStateResponseTypeDef",
-    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
-    "GetTemporaryGlueTableCredentialsResponseTypeDef",
-    "GetWorkUnitResultsResponseTypeDef",
     "ListLFTagsResponseTypeDef",
-    "StartQueryPlanningResponseTypeDef",
-    "StartTransactionResponseTypeDef",
-    "UpdateTableStorageOptimizerResponseTypeDef",
     "GetTemporaryGlueTableCredentialsRequestRequestTypeDef",
     "LFTagErrorTypeDef",
     "PrincipalPermissionsTypeDef",
     "TableWithColumnsResourceTypeDef",
     "DataCellsFilterTypeDef",
     "TaggedDatabaseTypeDef",
     "WriteOperationTypeDef",
@@ -115,16 +118,14 @@
     "DescribeResourceResponseTypeDef",
     "ListResourcesResponseTypeDef",
     "DescribeTransactionResponseTypeDef",
     "ListTransactionsResponseTypeDef",
     "ListResourcesRequestRequestTypeDef",
     "GetQueryStatisticsResponseTypeDef",
     "GetTemporaryGluePartitionCredentialsRequestRequestTypeDef",
-    "GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
-    "ListLFTagsRequestListLFTagsPaginateTypeDef",
     "GetWorkUnitsResponseTypeDef",
     "LFTagPolicyResourceTypeDef",
     "SearchDatabasesByLFTagsRequestRequestTypeDef",
     "SearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef",
     "SearchTablesByLFTagsRequestRequestTypeDef",
     "SearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef",
     "ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef",
@@ -134,15 +135,17 @@
     "StartQueryPlanningRequestRequestTypeDef",
     "GetResourceLFTagsResponseTypeDef",
     "TaggedTableTypeDef",
     "AddLFTagsToResourceResponseTypeDef",
     "RemoveLFTagsFromResourceResponseTypeDef",
     "DataLakeSettingsTypeDef",
     "CreateDataCellsFilterRequestRequestTypeDef",
+    "GetDataCellsFilterResponseTypeDef",
     "ListDataCellsFilterResponseTypeDef",
+    "UpdateDataCellsFilterRequestRequestTypeDef",
     "SearchDatabasesByLFTagsResponseTypeDef",
     "UpdateTableObjectsRequestRequestTypeDef",
     "ResourceTypeDef",
     "GetTableObjectsResponseTypeDef",
     "SearchTablesByLFTagsResponseTypeDef",
     "GetDataLakeSettingsResponseTypeDef",
     "PutDataLakeSettingsRequestRequestTypeDef",
@@ -177,25 +180,14 @@
     },
     total=False,
 )
 
 class LFTagPairTypeDef(_RequiredLFTagPairTypeDef, _OptionalLFTagPairTypeDef):
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
 _RequiredAddObjectInputTypeDef = TypedDict(
     "_RequiredAddObjectInputTypeDef",
     {
         "Uri": str,
         "ETag": str,
         "Size": int,
     },
@@ -229,14 +221,25 @@
 
 class AssumeDecoratedRoleWithSAMLRequestRequestTypeDef(
     _RequiredAssumeDecoratedRoleWithSAMLRequestRequestTypeDef,
     _OptionalAssumeDecoratedRoleWithSAMLRequestRequestTypeDef,
 ):
     pass
 
+AssumeDecoratedRoleWithSAMLResponseTypeDef = TypedDict(
+    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
+    {
+        "AccessKeyId": str,
+        "SecretAccessKey": str,
+        "SessionToken": str,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AuditContextTypeDef = TypedDict(
     "AuditContextTypeDef",
     {
         "AdditionalAuditContext": str,
     },
     total=False,
 )
@@ -276,14 +279,22 @@
 CommitTransactionRequestRequestTypeDef = TypedDict(
     "CommitTransactionRequestRequestTypeDef",
     {
         "TransactionId": str,
     },
 )
 
+CommitTransactionResponseTypeDef = TypedDict(
+    "CommitTransactionResponseTypeDef",
+    {
+        "TransactionStatus": TransactionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateLFTagRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLFTagRequestRequestTypeDef",
     {
         "TagKey": str,
         "TagValues": Sequence[str],
     },
 )
@@ -439,14 +450,15 @@
 
 ResourceInfoTypeDef = TypedDict(
     "ResourceInfoTypeDef",
     {
         "ResourceArn": str,
         "RoleArn": str,
         "LastModified": datetime,
+        "WithFederation": bool,
     },
     total=False,
 )
 
 DescribeTransactionRequestRequestTypeDef = TypedDict(
     "DescribeTransactionRequestRequestTypeDef",
     {
@@ -497,14 +509,24 @@
         "Field": FieldNameStringType,
         "ComparisonOperator": ComparisonOperatorType,
         "StringValueList": Sequence[str],
     },
     total=False,
 )
 
+GetDataCellsFilterRequestRequestTypeDef = TypedDict(
+    "GetDataCellsFilterRequestRequestTypeDef",
+    {
+        "TableCatalogId": str,
+        "DatabaseName": str,
+        "TableName": str,
+        "Name": str,
+    },
+)
+
 GetDataLakeSettingsRequestRequestTypeDef = TypedDict(
     "GetDataLakeSettingsRequestRequestTypeDef",
     {
         "CatalogId": str,
     },
     total=False,
 )
@@ -546,21 +568,40 @@
 )
 
 class GetLFTagRequestRequestTypeDef(
     _RequiredGetLFTagRequestRequestTypeDef, _OptionalGetLFTagRequestRequestTypeDef
 ):
     pass
 
+GetLFTagResponseTypeDef = TypedDict(
+    "GetLFTagResponseTypeDef",
+    {
+        "CatalogId": str,
+        "TagKey": str,
+        "TagValues": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetQueryStateRequestRequestTypeDef = TypedDict(
     "GetQueryStateRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 
+GetQueryStateResponseTypeDef = TypedDict(
+    "GetQueryStateResponseTypeDef",
+    {
+        "Error": str,
+        "State": QueryStateStringType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetQueryStatisticsRequestRequestTypeDef = TypedDict(
     "GetQueryStatisticsRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 
@@ -603,33 +644,73 @@
 PartitionValueListTypeDef = TypedDict(
     "PartitionValueListTypeDef",
     {
         "Values": Sequence[str],
     },
 )
 
+GetTemporaryGluePartitionCredentialsResponseTypeDef = TypedDict(
+    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
+    {
+        "AccessKeyId": str,
+        "SecretAccessKey": str,
+        "SessionToken": str,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetTemporaryGlueTableCredentialsResponseTypeDef = TypedDict(
+    "GetTemporaryGlueTableCredentialsResponseTypeDef",
+    {
+        "AccessKeyId": str,
+        "SecretAccessKey": str,
+        "SessionToken": str,
+        "Expiration": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkUnitResultsRequestRequestTypeDef = TypedDict(
     "GetWorkUnitResultsRequestRequestTypeDef",
     {
         "QueryId": str,
         "WorkUnitId": int,
         "WorkUnitToken": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetWorkUnitResultsResponseTypeDef = TypedDict(
+    "GetWorkUnitResultsResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ResultStream": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
+    "_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
+    {
+        "QueryId": str,
+    },
+)
+_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
+    "_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef(
+    _RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
+    _OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetWorkUnitsRequestRequestTypeDef = TypedDict(
     "_RequiredGetWorkUnitsRequestRequestTypeDef",
     {
         "QueryId": str,
     },
 )
 _OptionalGetWorkUnitsRequestRequestTypeDef = TypedDict(
@@ -696,14 +777,24 @@
     },
     total=False,
 )
 
 class TableResourceTypeDef(_RequiredTableResourceTypeDef, _OptionalTableResourceTypeDef):
     pass
 
+ListLFTagsRequestListLFTagsPaginateTypeDef = TypedDict(
+    "ListLFTagsRequestListLFTagsPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "ResourceShareType": ResourceShareTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLFTagsRequestRequestTypeDef = TypedDict(
     "ListLFTagsRequestRequestTypeDef",
     {
         "CatalogId": str,
         "ResourceShareType": ResourceShareTypeType,
         "MaxResults": int,
         "NextToken": str,
@@ -754,14 +845,24 @@
         "StatusFilter": TransactionStatusFilterType,
         "MaxResults": int,
         "NextToken": str,
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
 TableObjectTypeDef = TypedDict(
     "TableObjectTypeDef",
     {
         "Uri": str,
         "ETag": str,
         "Size": int,
     },
@@ -797,31 +898,59 @@
     },
 )
 _OptionalRegisterResourceRequestRequestTypeDef = TypedDict(
     "_OptionalRegisterResourceRequestRequestTypeDef",
     {
         "UseServiceLinkedRole": bool,
         "RoleArn": str,
+        "WithFederation": bool,
     },
     total=False,
 )
 
 class RegisterResourceRequestRequestTypeDef(
     _RequiredRegisterResourceRequestRequestTypeDef, _OptionalRegisterResourceRequestRequestTypeDef
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
+StartQueryPlanningResponseTypeDef = TypedDict(
+    "StartQueryPlanningResponseTypeDef",
+    {
+        "QueryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartTransactionRequestRequestTypeDef = TypedDict(
     "StartTransactionRequestRequestTypeDef",
     {
         "TransactionType": TransactionTypeType,
     },
     total=False,
 )
 
+StartTransactionResponseTypeDef = TypedDict(
+    "StartTransactionResponseTypeDef",
+    {
+        "TransactionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateLFTagRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateLFTagRequestRequestTypeDef",
     {
         "TagKey": str,
     },
 )
 _OptionalUpdateLFTagRequestRequestTypeDef = TypedDict(
@@ -835,21 +964,33 @@
 )
 
 class UpdateLFTagRequestRequestTypeDef(
     _RequiredUpdateLFTagRequestRequestTypeDef, _OptionalUpdateLFTagRequestRequestTypeDef
 ):
     pass
 
-UpdateResourceRequestRequestTypeDef = TypedDict(
-    "UpdateResourceRequestRequestTypeDef",
+_RequiredUpdateResourceRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateResourceRequestRequestTypeDef",
     {
         "RoleArn": str,
         "ResourceArn": str,
     },
 )
+_OptionalUpdateResourceRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateResourceRequestRequestTypeDef",
+    {
+        "WithFederation": bool,
+    },
+    total=False,
+)
+
+class UpdateResourceRequestRequestTypeDef(
+    _RequiredUpdateResourceRequestRequestTypeDef, _OptionalUpdateResourceRequestRequestTypeDef
+):
+    pass
 
 _RequiredUpdateTableStorageOptimizerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTableStorageOptimizerRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
         "StorageOptimizerConfig": Mapping[OptimizerTypeType, Mapping[str, str]],
@@ -865,121 +1006,37 @@
 
 class UpdateTableStorageOptimizerRequestRequestTypeDef(
     _RequiredUpdateTableStorageOptimizerRequestRequestTypeDef,
     _OptionalUpdateTableStorageOptimizerRequestRequestTypeDef,
 ):
     pass
 
+UpdateTableStorageOptimizerResponseTypeDef = TypedDict(
+    "UpdateTableStorageOptimizerResponseTypeDef",
+    {
+        "Result": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ColumnLFTagTypeDef = TypedDict(
     "ColumnLFTagTypeDef",
     {
         "Name": str,
         "LFTags": List[LFTagPairTypeDef],
     },
     total=False,
 )
 
-AssumeDecoratedRoleWithSAMLResponseTypeDef = TypedDict(
-    "AssumeDecoratedRoleWithSAMLResponseTypeDef",
-    {
-        "AccessKeyId": str,
-        "SecretAccessKey": str,
-        "SessionToken": str,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CommitTransactionResponseTypeDef = TypedDict(
-    "CommitTransactionResponseTypeDef",
-    {
-        "TransactionStatus": TransactionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLFTagResponseTypeDef = TypedDict(
-    "GetLFTagResponseTypeDef",
-    {
-        "CatalogId": str,
-        "TagKey": str,
-        "TagValues": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetQueryStateResponseTypeDef = TypedDict(
-    "GetQueryStateResponseTypeDef",
-    {
-        "Error": str,
-        "State": QueryStateStringType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemporaryGluePartitionCredentialsResponseTypeDef = TypedDict(
-    "GetTemporaryGluePartitionCredentialsResponseTypeDef",
-    {
-        "AccessKeyId": str,
-        "SecretAccessKey": str,
-        "SessionToken": str,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTemporaryGlueTableCredentialsResponseTypeDef = TypedDict(
-    "GetTemporaryGlueTableCredentialsResponseTypeDef",
-    {
-        "AccessKeyId": str,
-        "SecretAccessKey": str,
-        "SessionToken": str,
-        "Expiration": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkUnitResultsResponseTypeDef = TypedDict(
-    "GetWorkUnitResultsResponseTypeDef",
-    {
-        "ResultStream": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListLFTagsResponseTypeDef = TypedDict(
     "ListLFTagsResponseTypeDef",
     {
         "LFTags": List[LFTagPairTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartQueryPlanningResponseTypeDef = TypedDict(
-    "StartQueryPlanningResponseTypeDef",
-    {
-        "QueryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTransactionResponseTypeDef = TypedDict(
-    "StartTransactionResponseTypeDef",
-    {
-        "TransactionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTableStorageOptimizerResponseTypeDef = TypedDict(
-    "UpdateTableStorageOptimizerResponseTypeDef",
-    {
-        "Result": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTemporaryGlueTableCredentialsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTemporaryGlueTableCredentialsRequestRequestTypeDef",
     {
         "TableArn": str,
@@ -1053,14 +1110,15 @@
 )
 _OptionalDataCellsFilterTypeDef = TypedDict(
     "_OptionalDataCellsFilterTypeDef",
     {
         "RowFilter": RowFilterTypeDef,
         "ColumnNames": Sequence[str],
         "ColumnWildcard": ColumnWildcardTypeDef,
+        "VersionId": str,
     },
     total=False,
 )
 
 class DataCellsFilterTypeDef(_RequiredDataCellsFilterTypeDef, _OptionalDataCellsFilterTypeDef):
     pass
 
@@ -1105,41 +1163,41 @@
 ):
     pass
 
 DescribeResourceResponseTypeDef = TypedDict(
     "DescribeResourceResponseTypeDef",
     {
         "ResourceInfo": ResourceInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResponseTypeDef = TypedDict(
     "ListResourcesResponseTypeDef",
     {
         "ResourceInfoList": List[ResourceInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTransactionResponseTypeDef = TypedDict(
     "DescribeTransactionResponseTypeDef",
     {
         "TransactionDescription": TransactionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTransactionsResponseTypeDef = TypedDict(
     "ListTransactionsResponseTypeDef",
     {
         "Transactions": List[TransactionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesRequestRequestTypeDef = TypedDict(
     "ListResourcesRequestRequestTypeDef",
     {
         "FilterConditionList": Sequence[FilterConditionTypeDef],
@@ -1151,15 +1209,15 @@
 
 GetQueryStatisticsResponseTypeDef = TypedDict(
     "GetQueryStatisticsResponseTypeDef",
     {
         "ExecutionStatistics": ExecutionStatisticsTypeDef,
         "PlanningStatistics": PlanningStatisticsTypeDef,
         "QuerySubmissionTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetTemporaryGluePartitionCredentialsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTemporaryGluePartitionCredentialsRequestRequestTypeDef",
     {
         "TableArn": str,
@@ -1179,51 +1237,21 @@
 
 class GetTemporaryGluePartitionCredentialsRequestRequestTypeDef(
     _RequiredGetTemporaryGluePartitionCredentialsRequestRequestTypeDef,
     _OptionalGetTemporaryGluePartitionCredentialsRequestRequestTypeDef,
 ):
     pass
 
-_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
-    "_RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
-    {
-        "QueryId": str,
-    },
-)
-_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef = TypedDict(
-    "_OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef(
-    _RequiredGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
-    _OptionalGetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
-):
-    pass
-
-ListLFTagsRequestListLFTagsPaginateTypeDef = TypedDict(
-    "ListLFTagsRequestListLFTagsPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "ResourceShareType": ResourceShareTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetWorkUnitsResponseTypeDef = TypedDict(
     "GetWorkUnitsResponseTypeDef",
     {
         "NextToken": str,
         "QueryId": str,
         "WorkUnitRanges": List[WorkUnitRangeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredLFTagPolicyResourceTypeDef = TypedDict(
     "_RequiredLFTagPolicyResourceTypeDef",
     {
         "ResourceType": ResourceTypeType,
@@ -1271,15 +1299,15 @@
         "Expression": Sequence[LFTagTypeDef],
     },
 )
 _OptionalSearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef = TypedDict(
     "_OptionalSearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef",
     {
         "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class SearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef(
     _RequiredSearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef,
     _OptionalSearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef,
@@ -1314,30 +1342,30 @@
         "Expression": Sequence[LFTagTypeDef],
     },
 )
 _OptionalSearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef = TypedDict(
     "_OptionalSearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef",
     {
         "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class SearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef(
     _RequiredSearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef,
     _OptionalSearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef,
 ):
     pass
 
 ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef = TypedDict(
     "ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef",
     {
         "Table": TableResourceTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDataCellsFilterRequestRequestTypeDef = TypedDict(
     "ListDataCellsFilterRequestRequestTypeDef",
     {
@@ -1349,15 +1377,15 @@
 )
 
 ListTableStorageOptimizersResponseTypeDef = TypedDict(
     "ListTableStorageOptimizersResponseTypeDef",
     {
         "StorageOptimizerList": List[StorageOptimizerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PartitionObjectsTypeDef = TypedDict(
     "PartitionObjectsTypeDef",
     {
         "PartitionValues": List[str],
@@ -1376,15 +1404,15 @@
 
 GetResourceLFTagsResponseTypeDef = TypedDict(
     "GetResourceLFTagsResponseTypeDef",
     {
         "LFTagOnDatabase": List[LFTagPairTypeDef],
         "LFTagsOnTable": List[LFTagPairTypeDef],
         "LFTagsOnColumns": List[ColumnLFTagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TaggedTableTypeDef = TypedDict(
     "TaggedTableTypeDef",
     {
         "Table": TableResourceTypeDef,
@@ -1395,23 +1423,23 @@
     total=False,
 )
 
 AddLFTagsToResourceResponseTypeDef = TypedDict(
     "AddLFTagsToResourceResponseTypeDef",
     {
         "Failures": List[LFTagErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveLFTagsFromResourceResponseTypeDef = TypedDict(
     "RemoveLFTagsFromResourceResponseTypeDef",
     {
         "Failures": List[LFTagErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataLakeSettingsTypeDef = TypedDict(
     "DataLakeSettingsTypeDef",
     {
         "DataLakeAdmins": List[DataLakePrincipalTypeDef],
@@ -1429,29 +1457,44 @@
 CreateDataCellsFilterRequestRequestTypeDef = TypedDict(
     "CreateDataCellsFilterRequestRequestTypeDef",
     {
         "TableData": DataCellsFilterTypeDef,
     },
 )
 
+GetDataCellsFilterResponseTypeDef = TypedDict(
+    "GetDataCellsFilterResponseTypeDef",
+    {
+        "DataCellsFilter": DataCellsFilterTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListDataCellsFilterResponseTypeDef = TypedDict(
     "ListDataCellsFilterResponseTypeDef",
     {
         "DataCellsFilters": List[DataCellsFilterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateDataCellsFilterRequestRequestTypeDef = TypedDict(
+    "UpdateDataCellsFilterRequestRequestTypeDef",
+    {
+        "TableData": DataCellsFilterTypeDef,
     },
 )
 
 SearchDatabasesByLFTagsResponseTypeDef = TypedDict(
     "SearchDatabasesByLFTagsResponseTypeDef",
     {
         "NextToken": str,
         "DatabaseList": List[TaggedDatabaseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTableObjectsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateTableObjectsRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -1490,32 +1533,32 @@
 )
 
 GetTableObjectsResponseTypeDef = TypedDict(
     "GetTableObjectsResponseTypeDef",
     {
         "Objects": List[PartitionObjectsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchTablesByLFTagsResponseTypeDef = TypedDict(
     "SearchTablesByLFTagsResponseTypeDef",
     {
         "NextToken": str,
         "TableList": List[TaggedTableTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataLakeSettingsResponseTypeDef = TypedDict(
     "GetDataLakeSettingsResponseTypeDef",
     {
         "DataLakeSettings": DataLakeSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutDataLakeSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredPutDataLakeSettingsRequestRequestTypeDef",
     {
         "DataLakeSettings": DataLakeSettingsTypeDef,
@@ -1739,35 +1782,35 @@
     pass
 
 GetEffectivePermissionsForPathResponseTypeDef = TypedDict(
     "GetEffectivePermissionsForPathResponseTypeDef",
     {
         "Permissions": List[PrincipalResourcePermissionsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPermissionsResponseTypeDef = TypedDict(
     "ListPermissionsResponseTypeDef",
     {
         "PrincipalResourcePermissions": List[PrincipalResourcePermissionsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGrantPermissionsResponseTypeDef = TypedDict(
     "BatchGrantPermissionsResponseTypeDef",
     {
         "Failures": List[BatchPermissionsFailureEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchRevokePermissionsResponseTypeDef = TypedDict(
     "BatchRevokePermissionsResponseTypeDef",
     {
         "Failures": List[BatchPermissionsFailureEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/PKG-INFO` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lakeformation
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LakeFormation 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LakeFormation 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lakeformation"></a>
 
 # types-aiobotocore-lakeformation
 
 [![PyPI - types-aiobotocore-lakeformation](https://img.shields.io/pypi/v/types-aiobotocore-lakeformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lakeformation)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lakeformation.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lakeformation)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lakeformation?color=blue)](https://pypistats.org/packages/types-aiobotocore-lakeformation)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LakeFormation 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
+[aiobotocore.LakeFormation 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lakeformation.html#LakeFormation)
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
 [types-aiobotocore-lakeformation docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lakeformation/).
 
 See how it helps to find and fix potential bugs:
 
@@ -347,23 +347,24 @@
 
 `types_aiobotocore_lakeformation.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lakeformation.type_defs import (
     LFTagPairTypeDef,
-    ResponseMetadataTypeDef,
     AddObjectInputTypeDef,
     AssumeDecoratedRoleWithSAMLRequestRequestTypeDef,
+    AssumeDecoratedRoleWithSAMLResponseTypeDef,
     AuditContextTypeDef,
     ErrorDetailTypeDef,
     DataLakePrincipalTypeDef,
     CancelTransactionRequestRequestTypeDef,
     ColumnWildcardTypeDef,
     CommitTransactionRequestRequestTypeDef,
+    CommitTransactionResponseTypeDef,
     CreateLFTagRequestRequestTypeDef,
     DataCellsFilterResourceTypeDef,
     RowFilterTypeDef,
     DataLocationResourceTypeDef,
     DatabaseResourceTypeDef,
     DeleteDataCellsFilterRequestRequestTypeDef,
     DeleteLFTagRequestRequestTypeDef,
@@ -374,52 +375,54 @@
     ResourceInfoTypeDef,
     DescribeTransactionRequestRequestTypeDef,
     TransactionDescriptionTypeDef,
     DetailsMapTypeDef,
     ExecutionStatisticsTypeDef,
     ExtendTransactionRequestRequestTypeDef,
     FilterConditionTypeDef,
+    GetDataCellsFilterRequestRequestTypeDef,
     GetDataLakeSettingsRequestRequestTypeDef,
     GetEffectivePermissionsForPathRequestRequestTypeDef,
     GetLFTagRequestRequestTypeDef,
+    GetLFTagResponseTypeDef,
     GetQueryStateRequestRequestTypeDef,
+    GetQueryStateResponseTypeDef,
     GetQueryStatisticsRequestRequestTypeDef,
     PlanningStatisticsTypeDef,
     GetTableObjectsRequestRequestTypeDef,
     PartitionValueListTypeDef,
+    GetTemporaryGluePartitionCredentialsResponseTypeDef,
+    GetTemporaryGlueTableCredentialsResponseTypeDef,
     GetWorkUnitResultsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorkUnitResultsResponseTypeDef,
+    GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
     GetWorkUnitsRequestRequestTypeDef,
     WorkUnitRangeTypeDef,
     LFTagKeyResourceTypeDef,
     LFTagTypeDef,
     TableResourceTypeDef,
+    ListLFTagsRequestListLFTagsPaginateTypeDef,
     ListLFTagsRequestRequestTypeDef,
     ListTableStorageOptimizersRequestRequestTypeDef,
     StorageOptimizerTypeDef,
     ListTransactionsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     TableObjectTypeDef,
     QueryPlanningContextTypeDef,
     RegisterResourceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    StartQueryPlanningResponseTypeDef,
     StartTransactionRequestRequestTypeDef,
+    StartTransactionResponseTypeDef,
     UpdateLFTagRequestRequestTypeDef,
     UpdateResourceRequestRequestTypeDef,
     UpdateTableStorageOptimizerRequestRequestTypeDef,
+    UpdateTableStorageOptimizerResponseTypeDef,
     ColumnLFTagTypeDef,
-    AssumeDecoratedRoleWithSAMLResponseTypeDef,
-    CommitTransactionResponseTypeDef,
-    GetLFTagResponseTypeDef,
-    GetQueryStateResponseTypeDef,
-    GetTemporaryGluePartitionCredentialsResponseTypeDef,
-    GetTemporaryGlueTableCredentialsResponseTypeDef,
-    GetWorkUnitResultsResponseTypeDef,
     ListLFTagsResponseTypeDef,
-    StartQueryPlanningResponseTypeDef,
-    StartTransactionResponseTypeDef,
-    UpdateTableStorageOptimizerResponseTypeDef,
     GetTemporaryGlueTableCredentialsRequestRequestTypeDef,
     LFTagErrorTypeDef,
     PrincipalPermissionsTypeDef,
     TableWithColumnsResourceTypeDef,
     DataCellsFilterTypeDef,
     TaggedDatabaseTypeDef,
     WriteOperationTypeDef,
@@ -427,16 +430,14 @@
     DescribeResourceResponseTypeDef,
     ListResourcesResponseTypeDef,
     DescribeTransactionResponseTypeDef,
     ListTransactionsResponseTypeDef,
     ListResourcesRequestRequestTypeDef,
     GetQueryStatisticsResponseTypeDef,
     GetTemporaryGluePartitionCredentialsRequestRequestTypeDef,
-    GetWorkUnitsRequestGetWorkUnitsPaginateTypeDef,
-    ListLFTagsRequestListLFTagsPaginateTypeDef,
     GetWorkUnitsResponseTypeDef,
     LFTagPolicyResourceTypeDef,
     SearchDatabasesByLFTagsRequestRequestTypeDef,
     SearchDatabasesByLFTagsRequestSearchDatabasesByLFTagsPaginateTypeDef,
     SearchTablesByLFTagsRequestRequestTypeDef,
     SearchTablesByLFTagsRequestSearchTablesByLFTagsPaginateTypeDef,
     ListDataCellsFilterRequestListDataCellsFilterPaginateTypeDef,
@@ -446,15 +447,17 @@
     StartQueryPlanningRequestRequestTypeDef,
     GetResourceLFTagsResponseTypeDef,
     TaggedTableTypeDef,
     AddLFTagsToResourceResponseTypeDef,
     RemoveLFTagsFromResourceResponseTypeDef,
     DataLakeSettingsTypeDef,
     CreateDataCellsFilterRequestRequestTypeDef,
+    GetDataCellsFilterResponseTypeDef,
     ListDataCellsFilterResponseTypeDef,
+    UpdateDataCellsFilterRequestRequestTypeDef,
     SearchDatabasesByLFTagsResponseTypeDef,
     UpdateTableObjectsRequestRequestTypeDef,
     ResourceTypeDef,
     GetTableObjectsResponseTypeDef,
     SearchTablesByLFTagsResponseTypeDef,
     GetDataLakeSettingsResponseTypeDef,
     PutDataLakeSettingsRequestRequestTypeDef,
@@ -483,43 +486,43 @@
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

### Comparing `types-aiobotocore-lakeformation-2.5.0.post1/types_aiobotocore_lakeformation.egg-info/SOURCES.txt` & `types-aiobotocore-lakeformation-2.5.1/types_aiobotocore_lakeformation.egg-info/SOURCES.txt`

 * *Files identical despite different names*

