# Comparing `tmp/types-aiobotocore-athena-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-athena-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-athena-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-athena-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-athena-2.5.0.post1.tar` & `types-aiobotocore-athena-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.018972 types-aiobotocore-athena-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20576 2023-03-11 12:26:15.014972 types-aiobotocore-athena-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19009 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.018972 types-aiobotocore-athena-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.014972 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/
--rw-r--r--   0 runner    (1001) docker     (123)     1919 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1918 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    44263 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    44187 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9944 2023-03-11 12:09:53.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9942 2023-03-11 12:09:53.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8810 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8800 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    57683 2023-03-11 12:09:54.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    57600 2023-03-11 12:09:53.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:52.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.014972 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20576 2023-03-11 12:26:14.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:26:14.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:14.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:14.000000 types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.670098 types-aiobotocore-athena-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21325 2023-06-28 01:43:08.670098 types-aiobotocore-athena-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19764 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.670098 types-aiobotocore-athena-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.670098 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/
+-rw-r--r--   0 runner    (1001) docker     (123)     1919 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1918 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48904 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48820 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10421 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10419 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8704 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8695 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    62824 2023-06-28 01:26:31.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    62735 2023-06-28 01:26:30.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:29.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.670098 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21325 2023-06-28 01:43:08.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:08.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:08.000000 types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-athena-2.5.0.post1/LICENSE` & `types-aiobotocore-athena-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-athena-2.5.0.post1/PKG-INFO` & `types-aiobotocore-athena-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-athena
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Athena 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Athena 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-athena"></a>
 
 # types-aiobotocore-athena
 
 [![PyPI - types-aiobotocore-athena](https://img.shields.io/pypi/v/types-aiobotocore-athena.svg?color=blue)](https://pypi.org/project/types-aiobotocore-athena)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-athena.svg?color=blue)](https://pypi.org/project/types-aiobotocore-athena)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-athena?color=blue)](https://pypistats.org/packages/types-aiobotocore-athena)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Athena 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena)
+[aiobotocore.Athena 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena)
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
 [types-aiobotocore-athena docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,14 +318,16 @@
 
 `types_aiobotocore_athena.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_athena.literals import (
     CalculationExecutionStateType,
+    CapacityAllocationStatusType,
+    CapacityReservationStatusType,
     ColumnNullableType,
     DataCatalogTypeType,
     EncryptionOptionType,
     ExecutorStateType,
     ExecutorTypeType,
     GetQueryResultsPaginatorName,
     ListDataCatalogsPaginatorName,
@@ -362,124 +364,143 @@
 ```python
 from types_aiobotocore_athena.type_defs import (
     AclConfigurationTypeDef,
     ApplicationDPUSizesTypeDef,
     AthenaErrorTypeDef,
     BatchGetNamedQueryInputRequestTypeDef,
     NamedQueryTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedNamedQueryIdTypeDef,
     BatchGetPreparedStatementInputRequestTypeDef,
     PreparedStatementTypeDef,
     UnprocessedPreparedStatementNameTypeDef,
     BatchGetQueryExecutionInputRequestTypeDef,
     UnprocessedQueryExecutionIdTypeDef,
     CalculationConfigurationTypeDef,
     CalculationResultTypeDef,
     CalculationStatisticsTypeDef,
     CalculationStatusTypeDef,
+    CancelCapacityReservationInputRequestTypeDef,
+    CapacityAllocationTypeDef,
+    CapacityAssignmentTypeDef,
     ColumnInfoTypeDef,
     ColumnTypeDef,
     TagTypeDef,
     CreateNamedQueryInputRequestTypeDef,
+    CreateNamedQueryOutputTypeDef,
     CreateNotebookInputRequestTypeDef,
+    CreateNotebookOutputTypeDef,
     CreatePreparedStatementInputRequestTypeDef,
     CreatePresignedNotebookUrlRequestRequestTypeDef,
+    CreatePresignedNotebookUrlResponseTypeDef,
     CustomerContentEncryptionConfigurationTypeDef,
     DataCatalogSummaryTypeDef,
     DataCatalogTypeDef,
     DatabaseTypeDef,
     DatumTypeDef,
+    DeleteCapacityReservationInputRequestTypeDef,
     DeleteDataCatalogInputRequestTypeDef,
     DeleteNamedQueryInputRequestTypeDef,
     DeleteNotebookInputRequestTypeDef,
     DeletePreparedStatementInputRequestTypeDef,
     DeleteWorkGroupInputRequestTypeDef,
     EncryptionConfigurationTypeDef,
     EngineConfigurationTypeDef,
     EngineVersionTypeDef,
     ExecutorsSummaryTypeDef,
     ExportNotebookInputRequestTypeDef,
     NotebookMetadataTypeDef,
     FilterDefinitionTypeDef,
     GetCalculationExecutionCodeRequestRequestTypeDef,
+    GetCalculationExecutionCodeResponseTypeDef,
     GetCalculationExecutionRequestRequestTypeDef,
     GetCalculationExecutionStatusRequestRequestTypeDef,
+    GetCapacityAssignmentConfigurationInputRequestTypeDef,
+    GetCapacityReservationInputRequestTypeDef,
     GetDataCatalogInputRequestTypeDef,
     GetDatabaseInputRequestTypeDef,
     GetNamedQueryInputRequestTypeDef,
     GetNotebookMetadataInputRequestTypeDef,
     GetPreparedStatementInputRequestTypeDef,
     GetQueryExecutionInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetQueryResultsInputGetQueryResultsPaginateTypeDef,
     GetQueryResultsInputRequestTypeDef,
     GetQueryRuntimeStatisticsInputRequestTypeDef,
     GetSessionRequestRequestTypeDef,
     SessionStatisticsTypeDef,
     SessionStatusTypeDef,
     GetSessionStatusRequestRequestTypeDef,
     GetTableMetadataInputRequestTypeDef,
     GetWorkGroupInputRequestTypeDef,
     ImportNotebookInputRequestTypeDef,
+    ImportNotebookOutputTypeDef,
     ListApplicationDPUSizesInputRequestTypeDef,
     ListCalculationExecutionsRequestRequestTypeDef,
+    ListCapacityReservationsInputRequestTypeDef,
+    ListDataCatalogsInputListDataCatalogsPaginateTypeDef,
     ListDataCatalogsInputRequestTypeDef,
+    ListDatabasesInputListDatabasesPaginateTypeDef,
     ListDatabasesInputRequestTypeDef,
     ListEngineVersionsInputRequestTypeDef,
     ListExecutorsRequestRequestTypeDef,
+    ListNamedQueriesInputListNamedQueriesPaginateTypeDef,
     ListNamedQueriesInputRequestTypeDef,
+    ListNamedQueriesOutputTypeDef,
     ListNotebookSessionsRequestRequestTypeDef,
     NotebookSessionSummaryTypeDef,
     ListPreparedStatementsInputRequestTypeDef,
     PreparedStatementSummaryTypeDef,
+    ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef,
     ListQueryExecutionsInputRequestTypeDef,
+    ListQueryExecutionsOutputTypeDef,
     ListSessionsRequestRequestTypeDef,
+    ListTableMetadataInputListTableMetadataPaginateTypeDef,
     ListTableMetadataInputRequestTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     ListWorkGroupsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     QueryExecutionContextTypeDef,
     ResultReuseInformationTypeDef,
     QueryRuntimeStatisticsRowsTypeDef,
     QueryRuntimeStatisticsTimelineTypeDef,
     QueryStagePlanNodeTypeDef,
     QueryStageTypeDef,
+    ResponseMetadataTypeDef,
     ResultReuseByAgeConfigurationTypeDef,
+    StartCalculationExecutionResponseTypeDef,
+    StartQueryExecutionOutputTypeDef,
+    StartSessionResponseTypeDef,
     StopCalculationExecutionRequestRequestTypeDef,
+    StopCalculationExecutionResponseTypeDef,
     StopQueryExecutionInputRequestTypeDef,
     TerminateSessionRequestRequestTypeDef,
+    TerminateSessionResponseTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateCapacityReservationInputRequestTypeDef,
     UpdateDataCatalogInputRequestTypeDef,
     UpdateNamedQueryInputRequestTypeDef,
     UpdateNotebookInputRequestTypeDef,
     UpdateNotebookMetadataInputRequestTypeDef,
     UpdatePreparedStatementInputRequestTypeDef,
+    ListApplicationDPUSizesOutputTypeDef,
     QueryExecutionStatusTypeDef,
-    CreateNamedQueryOutputTypeDef,
-    CreateNotebookOutputTypeDef,
-    CreatePresignedNotebookUrlResponseTypeDef,
-    GetCalculationExecutionCodeResponseTypeDef,
     GetNamedQueryOutputTypeDef,
-    ImportNotebookOutputTypeDef,
-    ListApplicationDPUSizesOutputTypeDef,
-    ListNamedQueriesOutputTypeDef,
-    ListQueryExecutionsOutputTypeDef,
-    StartCalculationExecutionResponseTypeDef,
-    StartQueryExecutionOutputTypeDef,
-    StartSessionResponseTypeDef,
-    StopCalculationExecutionResponseTypeDef,
-    TerminateSessionResponseTypeDef,
     BatchGetNamedQueryOutputTypeDef,
     GetPreparedStatementOutputTypeDef,
     BatchGetPreparedStatementOutputTypeDef,
     StartCalculationExecutionRequestRequestTypeDef,
     CalculationSummaryTypeDef,
     GetCalculationExecutionResponseTypeDef,
     GetCalculationExecutionStatusResponseTypeDef,
+    CapacityReservationTypeDef,
+    CapacityAssignmentConfigurationTypeDef,
+    PutCapacityAssignmentConfigurationInputRequestTypeDef,
     ResultSetMetadataTypeDef,
     TableMetadataTypeDef,
+    CreateCapacityReservationInputRequestTypeDef,
     CreateDataCatalogInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     ListDataCatalogsOutputTypeDef,
     GetDataCatalogOutputTypeDef,
     GetDatabaseOutputTypeDef,
     ListDatabasesOutputTypeDef,
@@ -491,29 +512,25 @@
     ListEngineVersionsOutputTypeDef,
     WorkGroupSummaryTypeDef,
     ListExecutorsResponseTypeDef,
     ExportNotebookOutputTypeDef,
     GetNotebookMetadataOutputTypeDef,
     ListNotebookMetadataOutputTypeDef,
     ListNotebookMetadataInputRequestTypeDef,
-    GetQueryResultsInputGetQueryResultsPaginateTypeDef,
-    ListDataCatalogsInputListDataCatalogsPaginateTypeDef,
-    ListDatabasesInputListDatabasesPaginateTypeDef,
-    ListNamedQueriesInputListNamedQueriesPaginateTypeDef,
-    ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef,
-    ListTableMetadataInputListTableMetadataPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     GetSessionStatusResponseTypeDef,
     SessionSummaryTypeDef,
     ListNotebookSessionsResponseTypeDef,
     ListPreparedStatementsOutputTypeDef,
     QueryExecutionStatisticsTypeDef,
     QueryRuntimeStatisticsTypeDef,
     ResultReuseConfigurationTypeDef,
     ListCalculationExecutionsResponseTypeDef,
+    GetCapacityReservationOutputTypeDef,
+    ListCapacityReservationsOutputTypeDef,
+    GetCapacityAssignmentConfigurationOutputTypeDef,
     GetTableMetadataOutputTypeDef,
     ListTableMetadataOutputTypeDef,
     ResultSetTypeDef,
     WorkGroupConfigurationTypeDef,
     WorkGroupConfigurationUpdatesTypeDef,
     GetSessionResponseTypeDef,
     ListWorkGroupsOutputTypeDef,
@@ -538,43 +555,43 @@
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

### Comparing `types-aiobotocore-athena-2.5.0.post1/README.md` & `types-aiobotocore-athena-2.5.1/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-athena"></a>
 
 # types-aiobotocore-athena
 
 [![PyPI - types-aiobotocore-athena](https://img.shields.io/pypi/v/types-aiobotocore-athena.svg?color=blue)](https://pypi.org/project/types-aiobotocore-athena)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-athena.svg?color=blue)](https://pypi.org/project/types-aiobotocore-athena)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-athena?color=blue)](https://pypistats.org/packages/types-aiobotocore-athena)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Athena 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena)
+[aiobotocore.Athena 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena)
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
 [types-aiobotocore-athena docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/).
 
 See how it helps to find and fix potential bugs:
 
@@ -285,14 +285,16 @@
 
 `types_aiobotocore_athena.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_athena.literals import (
     CalculationExecutionStateType,
+    CapacityAllocationStatusType,
+    CapacityReservationStatusType,
     ColumnNullableType,
     DataCatalogTypeType,
     EncryptionOptionType,
     ExecutorStateType,
     ExecutorTypeType,
     GetQueryResultsPaginatorName,
     ListDataCatalogsPaginatorName,
@@ -329,124 +331,143 @@
 ```python
 from types_aiobotocore_athena.type_defs import (
     AclConfigurationTypeDef,
     ApplicationDPUSizesTypeDef,
     AthenaErrorTypeDef,
     BatchGetNamedQueryInputRequestTypeDef,
     NamedQueryTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedNamedQueryIdTypeDef,
     BatchGetPreparedStatementInputRequestTypeDef,
     PreparedStatementTypeDef,
     UnprocessedPreparedStatementNameTypeDef,
     BatchGetQueryExecutionInputRequestTypeDef,
     UnprocessedQueryExecutionIdTypeDef,
     CalculationConfigurationTypeDef,
     CalculationResultTypeDef,
     CalculationStatisticsTypeDef,
     CalculationStatusTypeDef,
+    CancelCapacityReservationInputRequestTypeDef,
+    CapacityAllocationTypeDef,
+    CapacityAssignmentTypeDef,
     ColumnInfoTypeDef,
     ColumnTypeDef,
     TagTypeDef,
     CreateNamedQueryInputRequestTypeDef,
+    CreateNamedQueryOutputTypeDef,
     CreateNotebookInputRequestTypeDef,
+    CreateNotebookOutputTypeDef,
     CreatePreparedStatementInputRequestTypeDef,
     CreatePresignedNotebookUrlRequestRequestTypeDef,
+    CreatePresignedNotebookUrlResponseTypeDef,
     CustomerContentEncryptionConfigurationTypeDef,
     DataCatalogSummaryTypeDef,
     DataCatalogTypeDef,
     DatabaseTypeDef,
     DatumTypeDef,
+    DeleteCapacityReservationInputRequestTypeDef,
     DeleteDataCatalogInputRequestTypeDef,
     DeleteNamedQueryInputRequestTypeDef,
     DeleteNotebookInputRequestTypeDef,
     DeletePreparedStatementInputRequestTypeDef,
     DeleteWorkGroupInputRequestTypeDef,
     EncryptionConfigurationTypeDef,
     EngineConfigurationTypeDef,
     EngineVersionTypeDef,
     ExecutorsSummaryTypeDef,
     ExportNotebookInputRequestTypeDef,
     NotebookMetadataTypeDef,
     FilterDefinitionTypeDef,
     GetCalculationExecutionCodeRequestRequestTypeDef,
+    GetCalculationExecutionCodeResponseTypeDef,
     GetCalculationExecutionRequestRequestTypeDef,
     GetCalculationExecutionStatusRequestRequestTypeDef,
+    GetCapacityAssignmentConfigurationInputRequestTypeDef,
+    GetCapacityReservationInputRequestTypeDef,
     GetDataCatalogInputRequestTypeDef,
     GetDatabaseInputRequestTypeDef,
     GetNamedQueryInputRequestTypeDef,
     GetNotebookMetadataInputRequestTypeDef,
     GetPreparedStatementInputRequestTypeDef,
     GetQueryExecutionInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetQueryResultsInputGetQueryResultsPaginateTypeDef,
     GetQueryResultsInputRequestTypeDef,
     GetQueryRuntimeStatisticsInputRequestTypeDef,
     GetSessionRequestRequestTypeDef,
     SessionStatisticsTypeDef,
     SessionStatusTypeDef,
     GetSessionStatusRequestRequestTypeDef,
     GetTableMetadataInputRequestTypeDef,
     GetWorkGroupInputRequestTypeDef,
     ImportNotebookInputRequestTypeDef,
+    ImportNotebookOutputTypeDef,
     ListApplicationDPUSizesInputRequestTypeDef,
     ListCalculationExecutionsRequestRequestTypeDef,
+    ListCapacityReservationsInputRequestTypeDef,
+    ListDataCatalogsInputListDataCatalogsPaginateTypeDef,
     ListDataCatalogsInputRequestTypeDef,
+    ListDatabasesInputListDatabasesPaginateTypeDef,
     ListDatabasesInputRequestTypeDef,
     ListEngineVersionsInputRequestTypeDef,
     ListExecutorsRequestRequestTypeDef,
+    ListNamedQueriesInputListNamedQueriesPaginateTypeDef,
     ListNamedQueriesInputRequestTypeDef,
+    ListNamedQueriesOutputTypeDef,
     ListNotebookSessionsRequestRequestTypeDef,
     NotebookSessionSummaryTypeDef,
     ListPreparedStatementsInputRequestTypeDef,
     PreparedStatementSummaryTypeDef,
+    ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef,
     ListQueryExecutionsInputRequestTypeDef,
+    ListQueryExecutionsOutputTypeDef,
     ListSessionsRequestRequestTypeDef,
+    ListTableMetadataInputListTableMetadataPaginateTypeDef,
     ListTableMetadataInputRequestTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     ListWorkGroupsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     QueryExecutionContextTypeDef,
     ResultReuseInformationTypeDef,
     QueryRuntimeStatisticsRowsTypeDef,
     QueryRuntimeStatisticsTimelineTypeDef,
     QueryStagePlanNodeTypeDef,
     QueryStageTypeDef,
+    ResponseMetadataTypeDef,
     ResultReuseByAgeConfigurationTypeDef,
+    StartCalculationExecutionResponseTypeDef,
+    StartQueryExecutionOutputTypeDef,
+    StartSessionResponseTypeDef,
     StopCalculationExecutionRequestRequestTypeDef,
+    StopCalculationExecutionResponseTypeDef,
     StopQueryExecutionInputRequestTypeDef,
     TerminateSessionRequestRequestTypeDef,
+    TerminateSessionResponseTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateCapacityReservationInputRequestTypeDef,
     UpdateDataCatalogInputRequestTypeDef,
     UpdateNamedQueryInputRequestTypeDef,
     UpdateNotebookInputRequestTypeDef,
     UpdateNotebookMetadataInputRequestTypeDef,
     UpdatePreparedStatementInputRequestTypeDef,
+    ListApplicationDPUSizesOutputTypeDef,
     QueryExecutionStatusTypeDef,
-    CreateNamedQueryOutputTypeDef,
-    CreateNotebookOutputTypeDef,
-    CreatePresignedNotebookUrlResponseTypeDef,
-    GetCalculationExecutionCodeResponseTypeDef,
     GetNamedQueryOutputTypeDef,
-    ImportNotebookOutputTypeDef,
-    ListApplicationDPUSizesOutputTypeDef,
-    ListNamedQueriesOutputTypeDef,
-    ListQueryExecutionsOutputTypeDef,
-    StartCalculationExecutionResponseTypeDef,
-    StartQueryExecutionOutputTypeDef,
-    StartSessionResponseTypeDef,
-    StopCalculationExecutionResponseTypeDef,
-    TerminateSessionResponseTypeDef,
     BatchGetNamedQueryOutputTypeDef,
     GetPreparedStatementOutputTypeDef,
     BatchGetPreparedStatementOutputTypeDef,
     StartCalculationExecutionRequestRequestTypeDef,
     CalculationSummaryTypeDef,
     GetCalculationExecutionResponseTypeDef,
     GetCalculationExecutionStatusResponseTypeDef,
+    CapacityReservationTypeDef,
+    CapacityAssignmentConfigurationTypeDef,
+    PutCapacityAssignmentConfigurationInputRequestTypeDef,
     ResultSetMetadataTypeDef,
     TableMetadataTypeDef,
+    CreateCapacityReservationInputRequestTypeDef,
     CreateDataCatalogInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     ListDataCatalogsOutputTypeDef,
     GetDataCatalogOutputTypeDef,
     GetDatabaseOutputTypeDef,
     ListDatabasesOutputTypeDef,
@@ -458,29 +479,25 @@
     ListEngineVersionsOutputTypeDef,
     WorkGroupSummaryTypeDef,
     ListExecutorsResponseTypeDef,
     ExportNotebookOutputTypeDef,
     GetNotebookMetadataOutputTypeDef,
     ListNotebookMetadataOutputTypeDef,
     ListNotebookMetadataInputRequestTypeDef,
-    GetQueryResultsInputGetQueryResultsPaginateTypeDef,
-    ListDataCatalogsInputListDataCatalogsPaginateTypeDef,
-    ListDatabasesInputListDatabasesPaginateTypeDef,
-    ListNamedQueriesInputListNamedQueriesPaginateTypeDef,
-    ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef,
-    ListTableMetadataInputListTableMetadataPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     GetSessionStatusResponseTypeDef,
     SessionSummaryTypeDef,
     ListNotebookSessionsResponseTypeDef,
     ListPreparedStatementsOutputTypeDef,
     QueryExecutionStatisticsTypeDef,
     QueryRuntimeStatisticsTypeDef,
     ResultReuseConfigurationTypeDef,
     ListCalculationExecutionsResponseTypeDef,
+    GetCapacityReservationOutputTypeDef,
+    ListCapacityReservationsOutputTypeDef,
+    GetCapacityAssignmentConfigurationOutputTypeDef,
     GetTableMetadataOutputTypeDef,
     ListTableMetadataOutputTypeDef,
     ResultSetTypeDef,
     WorkGroupConfigurationTypeDef,
     WorkGroupConfigurationUpdatesTypeDef,
     GetSessionResponseTypeDef,
     ListWorkGroupsOutputTypeDef,
@@ -505,43 +522,43 @@
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

### Comparing `types-aiobotocore-athena-2.5.0.post1/setup.py` & `types-aiobotocore-athena-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-athena.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-athena",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_athena"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Athena 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Athena 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/"
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

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/__init__.py` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/__init__.pyi` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/__main__.py` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/__main__.py`

 * *Files 27% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Athena 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Athena 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena\nOther"
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

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/client.py` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -37,23 +37,26 @@
     ListTagsForResourcePaginator,
 )
 from .type_defs import (
     BatchGetNamedQueryOutputTypeDef,
     BatchGetPreparedStatementOutputTypeDef,
     BatchGetQueryExecutionOutputTypeDef,
     CalculationConfigurationTypeDef,
+    CapacityAssignmentTypeDef,
     CreateNamedQueryOutputTypeDef,
     CreateNotebookOutputTypeDef,
     CreatePresignedNotebookUrlResponseTypeDef,
     EngineConfigurationTypeDef,
     ExportNotebookOutputTypeDef,
     FilterDefinitionTypeDef,
     GetCalculationExecutionCodeResponseTypeDef,
     GetCalculationExecutionResponseTypeDef,
     GetCalculationExecutionStatusResponseTypeDef,
+    GetCapacityAssignmentConfigurationOutputTypeDef,
+    GetCapacityReservationOutputTypeDef,
     GetDatabaseOutputTypeDef,
     GetDataCatalogOutputTypeDef,
     GetNamedQueryOutputTypeDef,
     GetNotebookMetadataOutputTypeDef,
     GetPreparedStatementOutputTypeDef,
     GetQueryExecutionOutputTypeDef,
     GetQueryResultsOutputTypeDef,
@@ -61,14 +64,15 @@
     GetSessionResponseTypeDef,
     GetSessionStatusResponseTypeDef,
     GetTableMetadataOutputTypeDef,
     GetWorkGroupOutputTypeDef,
     ImportNotebookOutputTypeDef,
     ListApplicationDPUSizesOutputTypeDef,
     ListCalculationExecutionsResponseTypeDef,
+    ListCapacityReservationsOutputTypeDef,
     ListDatabasesOutputTypeDef,
     ListDataCatalogsOutputTypeDef,
     ListEngineVersionsOutputTypeDef,
     ListExecutorsResponseTypeDef,
     ListNamedQueriesOutputTypeDef,
     ListNotebookMetadataOutputTypeDef,
     ListNotebookSessionsResponseTypeDef,
@@ -92,36 +96,32 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("AthenaClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidRequestException: Type[BotocoreClientError]
     MetadataException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     SessionAlreadyExistsException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
 
-
 class AthenaClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/)
     """
 
     meta: ClientMeta
@@ -130,64 +130,75 @@
     def exceptions(self) -> Exceptions:
         """
         AthenaClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#exceptions)
         """
-
     async def batch_get_named_query(
         self, *, NamedQueryIds: Sequence[str]
     ) -> BatchGetNamedQueryOutputTypeDef:
         """
         Returns the details of a single named query or a list of up to 50 queries, which
         you provide as an array of query ID strings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.batch_get_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#batch_get_named_query)
         """
-
     async def batch_get_prepared_statement(
         self, *, PreparedStatementNames: Sequence[str], WorkGroup: str
     ) -> BatchGetPreparedStatementOutputTypeDef:
         """
         Returns the details of a single prepared statement or a list of up to 256
         prepared statements for the array of prepared statement names that you provide.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.batch_get_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#batch_get_prepared_statement)
         """
-
     async def batch_get_query_execution(
         self, *, QueryExecutionIds: Sequence[str]
     ) -> BatchGetQueryExecutionOutputTypeDef:
         """
         Returns the details of a single query execution or a list of up to 50 query
         executions, which you provide as an array of query execution ID strings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.batch_get_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#batch_get_query_execution)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#can_paginate)
         """
+    async def cancel_capacity_reservation(self, *, Name: str) -> Dict[str, Any]:
+        """
+        Cancels the capacity reservation with the specified name.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.cancel_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#cancel_capacity_reservation)
+        """
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#close)
         """
+    async def create_capacity_reservation(
+        self, *, TargetDpus: int, Name: str, Tags: Sequence[TagTypeDef] = ...
+    ) -> Dict[str, Any]:
+        """
+        Creates a capacity reservation with the specified name and number of requested
+        data processing units.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_capacity_reservation)
+        """
     async def create_data_catalog(
         self,
         *,
         Name: str,
         Type: DataCatalogTypeType,
         Description: str = ...,
         Parameters: Mapping[str, str] = ...,
@@ -195,15 +206,14 @@
     ) -> Dict[str, Any]:
         """
         Creates (registers) a data catalog with the specified name and properties.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_data_catalog)
         """
-
     async def create_named_query(
         self,
         *,
         Name: str,
         Database: str,
         QueryString: str,
         Description: str = ...,
@@ -212,270 +222,266 @@
     ) -> CreateNamedQueryOutputTypeDef:
         """
         Creates a named query in the specified workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_named_query)
         """
-
     async def create_notebook(
         self, *, WorkGroup: str, Name: str, ClientRequestToken: str = ...
     ) -> CreateNotebookOutputTypeDef:
         """
         Creates an empty `ipynb` file in the specified Apache Spark enabled workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_notebook)
         """
-
     async def create_prepared_statement(
         self, *, StatementName: str, WorkGroup: str, QueryStatement: str, Description: str = ...
     ) -> Dict[str, Any]:
         """
         Creates a prepared statement for use with SQL queries in Athena.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_prepared_statement)
         """
-
     async def create_presigned_notebook_url(
         self, *, SessionId: str
     ) -> CreatePresignedNotebookUrlResponseTypeDef:
         """
         Gets an authentication token and the URL at which the notebook can be accessed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_presigned_notebook_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_presigned_notebook_url)
         """
-
     async def create_work_group(
         self,
         *,
         Name: str,
         Configuration: WorkGroupConfigurationTypeDef = ...,
         Description: str = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> Dict[str, Any]:
         """
         Creates a workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_work_group)
         """
+    async def delete_capacity_reservation(self, *, Name: str) -> Dict[str, Any]:
+        """
+        Deletes a cancelled capacity reservation.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_capacity_reservation)
+        """
     async def delete_data_catalog(self, *, Name: str) -> Dict[str, Any]:
         """
         Deletes a data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_data_catalog)
         """
-
     async def delete_named_query(self, *, NamedQueryId: str) -> Dict[str, Any]:
         """
         Deletes the named query if you have access to the workgroup in which the query
         was saved.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_named_query)
         """
-
     async def delete_notebook(self, *, NotebookId: str) -> Dict[str, Any]:
         """
         Deletes the specified notebook.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_notebook)
         """
-
     async def delete_prepared_statement(
         self, *, StatementName: str, WorkGroup: str
     ) -> Dict[str, Any]:
         """
         Deletes the prepared statement with the specified name from the specified
         workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_prepared_statement)
         """
-
     async def delete_work_group(
         self, *, WorkGroup: str, RecursiveDeleteOption: bool = ...
     ) -> Dict[str, Any]:
         """
         Deletes the workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_work_group)
         """
-
     async def export_notebook(self, *, NotebookId: str) -> ExportNotebookOutputTypeDef:
         """
         Exports the specified notebook and its metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.export_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#export_notebook)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#generate_presigned_url)
         """
-
     async def get_calculation_execution(
         self, *, CalculationExecutionId: str
     ) -> GetCalculationExecutionResponseTypeDef:
         """
         Describes a previously submitted calculation execution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_calculation_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_calculation_execution)
         """
-
     async def get_calculation_execution_code(
         self, *, CalculationExecutionId: str
     ) -> GetCalculationExecutionCodeResponseTypeDef:
         """
-        Retrieves a pre-signed URL to a copy of the code that was executed for the
-        calculation.
+        Retrieves the unencrypted code that was executed for the calculation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_calculation_execution_code)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_calculation_execution_code)
         """
-
     async def get_calculation_execution_status(
         self, *, CalculationExecutionId: str
     ) -> GetCalculationExecutionStatusResponseTypeDef:
         """
         Gets the status of a current calculation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_calculation_execution_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_calculation_execution_status)
         """
+    async def get_capacity_assignment_configuration(
+        self, *, CapacityReservationName: str
+    ) -> GetCapacityAssignmentConfigurationOutputTypeDef:
+        """
+        Gets the capacity assignment configuration for a capacity reservation, if one
+        exists.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_capacity_assignment_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_capacity_assignment_configuration)
+        """
+    async def get_capacity_reservation(self, *, Name: str) -> GetCapacityReservationOutputTypeDef:
+        """
+        Returns information about the capacity reservation with the specified name.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_capacity_reservation)
+        """
     async def get_data_catalog(self, *, Name: str) -> GetDataCatalogOutputTypeDef:
         """
         Returns the specified data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_data_catalog)
         """
-
     async def get_database(
         self, *, CatalogName: str, DatabaseName: str
     ) -> GetDatabaseOutputTypeDef:
         """
         Returns a database object for the specified database and data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_database)
         """
-
     async def get_named_query(self, *, NamedQueryId: str) -> GetNamedQueryOutputTypeDef:
         """
         Returns information about a single query.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_named_query)
         """
-
     async def get_notebook_metadata(self, *, NotebookId: str) -> GetNotebookMetadataOutputTypeDef:
         """
         Retrieves notebook metadata for the specified notebook ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_notebook_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_notebook_metadata)
         """
-
     async def get_prepared_statement(
         self, *, StatementName: str, WorkGroup: str
     ) -> GetPreparedStatementOutputTypeDef:
         """
         Retrieves the prepared statement with the specified name from the specified
         workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_prepared_statement)
         """
-
     async def get_query_execution(self, *, QueryExecutionId: str) -> GetQueryExecutionOutputTypeDef:
         """
         Returns information about a single execution of a query if you have access to
         the workgroup in which the query ran.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_query_execution)
         """
-
     async def get_query_results(
         self, *, QueryExecutionId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> GetQueryResultsOutputTypeDef:
         """
         Streams the results of a single query execution specified by `QueryExecutionId`
         from the Athena query results location in Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_query_results)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_query_results)
         """
-
     async def get_query_runtime_statistics(
         self, *, QueryExecutionId: str
     ) -> GetQueryRuntimeStatisticsOutputTypeDef:
         """
         Returns query execution runtime statistics related to a single execution of a
         query if you have access to the workgroup in which the query ran.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_query_runtime_statistics)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_query_runtime_statistics)
         """
-
     async def get_session(self, *, SessionId: str) -> GetSessionResponseTypeDef:
         """
         Gets the full details of a previously created session, including the session
         status and configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_session)
         """
-
     async def get_session_status(self, *, SessionId: str) -> GetSessionStatusResponseTypeDef:
         """
         Gets the current status of a session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_session_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_session_status)
         """
-
     async def get_table_metadata(
         self, *, CatalogName: str, DatabaseName: str, TableName: str
     ) -> GetTableMetadataOutputTypeDef:
         """
         Returns table metadata for the specified catalog, database, and table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_table_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_table_metadata)
         """
-
     async def get_work_group(self, *, WorkGroup: str) -> GetWorkGroupOutputTypeDef:
         """
         Returns information about the workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_work_group)
         """
-
     async def import_notebook(
         self,
         *,
         WorkGroup: str,
         Name: str,
         Payload: str,
         Type: Literal["IPYNB"],
@@ -483,26 +489,24 @@
     ) -> ImportNotebookOutputTypeDef:
         """
         Imports a single `ipynb` file to a Spark enabled workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.import_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#import_notebook)
         """
-
     async def list_application_dpu_sizes(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListApplicationDPUSizesOutputTypeDef:
         """
         Returns the supported DPU sizes for the supported application runtimes (for
-        example, `Jupyter 1.0` ).
+        example, `Athena notebook version 1`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_application_dpu_sizes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_application_dpu_sizes)
         """
-
     async def list_calculation_executions(
         self,
         *,
         SessionId: str,
         StateFilter: CalculationExecutionStateType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
@@ -510,135 +514,133 @@
         """
         Lists the calculations that have been submitted to a session in descending
         order.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_calculation_executions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_calculation_executions)
         """
+    async def list_capacity_reservations(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListCapacityReservationsOutputTypeDef:
+        """
+        Lists the capacity reservations for the current account.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_capacity_reservations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_capacity_reservations)
+        """
     async def list_data_catalogs(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDataCatalogsOutputTypeDef:
         """
         Lists the data catalogs in the current Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_data_catalogs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_data_catalogs)
         """
-
     async def list_databases(
         self, *, CatalogName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDatabasesOutputTypeDef:
         """
         Lists the databases in the specified data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_databases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_databases)
         """
-
     async def list_engine_versions(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEngineVersionsOutputTypeDef:
         """
         Returns a list of engine versions that are available to choose from, including
         the Auto option.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_engine_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_engine_versions)
         """
-
     async def list_executors(
         self,
         *,
         SessionId: str,
         ExecutorStateFilter: ExecutorStateType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListExecutorsResponseTypeDef:
         """
-        Lists, in descending order, the executors that have been submitted to a session.
+        Lists, in descending order, the executors that joined a session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_executors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_executors)
         """
-
     async def list_named_queries(
         self, *, NextToken: str = ..., MaxResults: int = ..., WorkGroup: str = ...
     ) -> ListNamedQueriesOutputTypeDef:
         """
         Provides a list of available query IDs only for queries saved in the specified
         workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_named_queries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_named_queries)
         """
-
     async def list_notebook_metadata(
         self,
         *,
         WorkGroup: str,
         Filters: FilterDefinitionTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListNotebookMetadataOutputTypeDef:
         """
         Displays the notebook files for the specified workgroup in paginated format.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_notebook_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_notebook_metadata)
         """
-
     async def list_notebook_sessions(
         self, *, NotebookId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListNotebookSessionsResponseTypeDef:
         """
         Lists, in descending order, the sessions that have been created in a notebook
-        that are in an active state like `CREATING` , `CREATED` , `IDLE` or `BUSY`.
+        that are in an active state like `CREATING`, `CREATED`, `IDLE` or `BUSY`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_notebook_sessions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_notebook_sessions)
         """
-
     async def list_prepared_statements(
         self, *, WorkGroup: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPreparedStatementsOutputTypeDef:
         """
         Lists the prepared statements in the specified workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_prepared_statements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_prepared_statements)
         """
-
     async def list_query_executions(
         self, *, NextToken: str = ..., MaxResults: int = ..., WorkGroup: str = ...
     ) -> ListQueryExecutionsOutputTypeDef:
         """
         Provides a list of available query execution IDs for the queries in the
         specified workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_query_executions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_query_executions)
         """
-
     async def list_sessions(
         self,
         *,
         WorkGroup: str,
         StateFilter: SessionStateType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListSessionsResponseTypeDef:
         """
-        Lists the sessions in a workgroup that are in an active state like `CREATING` ,
-        `CREATED` , `IDLE` , or `BUSY`.
+        Lists the sessions in a workgroup that are in an active state like `CREATING`,
+        `CREATED`, `IDLE`, or `BUSY`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_sessions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_sessions)
         """
-
     async def list_table_metadata(
         self,
         *,
         CatalogName: str,
         DatabaseName: str,
         Expression: str = ...,
         NextToken: str = ...,
@@ -646,35 +648,45 @@
     ) -> ListTableMetadataOutputTypeDef:
         """
         Lists the metadata for the tables in the specified data catalog database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_table_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_table_metadata)
         """
-
     async def list_tags_for_resource(
         self, *, ResourceARN: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListTagsForResourceOutputTypeDef:
         """
-        Lists the tags associated with an Athena workgroup or data catalog resource.
+        Lists the tags associated with an Athena resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_tags_for_resource)
         """
-
     async def list_work_groups(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListWorkGroupsOutputTypeDef:
         """
         Lists available workgroups for the account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_work_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_work_groups)
         """
+    async def put_capacity_assignment_configuration(
+        self,
+        *,
+        CapacityReservationName: str,
+        CapacityAssignments: Sequence[CapacityAssignmentTypeDef]
+    ) -> Dict[str, Any]:
+        """
+        Puts a new capacity assignment configuration for a specified capacity
+        reservation.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.put_capacity_assignment_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#put_capacity_assignment_configuration)
+        """
     async def start_calculation_execution(
         self,
         *,
         SessionId: str,
         Description: str = ...,
         CalculationConfiguration: CalculationConfigurationTypeDef = ...,
         CodeBlock: str = ...,
@@ -682,15 +694,14 @@
     ) -> StartCalculationExecutionResponseTypeDef:
         """
         Submits calculations for execution within a session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.start_calculation_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#start_calculation_execution)
         """
-
     async def start_query_execution(
         self,
         *,
         QueryString: str,
         ClientRequestToken: str = ...,
         QueryExecutionContext: QueryExecutionContextTypeDef = ...,
         ResultConfiguration: ResultConfigurationTypeDef = ...,
@@ -700,15 +711,14 @@
     ) -> StartQueryExecutionOutputTypeDef:
         """
         Runs the SQL query statements contained in the `Query`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.start_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#start_query_execution)
         """
-
     async def start_session(
         self,
         *,
         WorkGroup: str,
         EngineConfiguration: EngineConfigurationTypeDef,
         Description: str = ...,
         NotebookVersion: str = ...,
@@ -717,82 +727,82 @@
     ) -> StartSessionResponseTypeDef:
         """
         Creates a session for running calculations within a workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.start_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#start_session)
         """
-
     async def stop_calculation_execution(
         self, *, CalculationExecutionId: str
     ) -> StopCalculationExecutionResponseTypeDef:
         """
         Requests the cancellation of a calculation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.stop_calculation_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#stop_calculation_execution)
         """
-
     async def stop_query_execution(self, *, QueryExecutionId: str) -> Dict[str, Any]:
         """
         Stops a query execution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.stop_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#stop_query_execution)
         """
-
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Adds one or more tags to an Athena resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#tag_resource)
         """
-
     async def terminate_session(self, *, SessionId: str) -> TerminateSessionResponseTypeDef:
         """
         Terminates an active session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.terminate_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#terminate_session)
         """
-
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Removes one or more tags from a data catalog or workgroup resource.
+        Removes one or more tags from an Athena resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#untag_resource)
         """
+    async def update_capacity_reservation(self, *, TargetDpus: int, Name: str) -> Dict[str, Any]:
+        """
+        Updates the number of requested data processing units for the capacity
+        reservation with the specified name.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_capacity_reservation)
+        """
     async def update_data_catalog(
         self,
         *,
         Name: str,
         Type: DataCatalogTypeType,
         Description: str = ...,
         Parameters: Mapping[str, str] = ...
     ) -> Dict[str, Any]:
         """
         Updates the data catalog that has the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_data_catalog)
         """
-
     async def update_named_query(
         self, *, NamedQueryId: str, Name: str, QueryString: str, Description: str = ...
     ) -> Dict[str, Any]:
         """
         Updates a  NamedQuery object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_named_query)
         """
-
     async def update_notebook(
         self,
         *,
         NotebookId: str,
         Payload: str,
         Type: Literal["IPYNB"],
         SessionId: str = ...,
@@ -800,115 +810,103 @@
     ) -> Dict[str, Any]:
         """
         Updates the contents of a Spark notebook.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_notebook)
         """
-
     async def update_notebook_metadata(
         self, *, NotebookId: str, Name: str, ClientRequestToken: str = ...
     ) -> Dict[str, Any]:
         """
         Updates the metadata for a notebook.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_notebook_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_notebook_metadata)
         """
-
     async def update_prepared_statement(
         self, *, StatementName: str, WorkGroup: str, QueryStatement: str, Description: str = ...
     ) -> Dict[str, Any]:
         """
         Updates a prepared statement.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_prepared_statement)
         """
-
     async def update_work_group(
         self,
         *,
         WorkGroup: str,
         Description: str = ...,
         ConfigurationUpdates: WorkGroupConfigurationUpdatesTypeDef = ...,
         State: WorkGroupStateType = ...
     ) -> Dict[str, Any]:
         """
         Updates the workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_work_group)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["get_query_results"]
     ) -> GetQueryResultsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_data_catalogs"]
     ) -> ListDataCatalogsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_databases"]) -> ListDatabasesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_named_queries"]
     ) -> ListNamedQueriesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_query_executions"]
     ) -> ListQueryExecutionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_table_metadata"]
     ) -> ListTableMetadataPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_tags_for_resource"]
     ) -> ListTagsForResourcePaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "AthenaClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/)
         """
```

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/client.pyi` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/client.py`

 * *Files 3% similar despite different names*

```diff
@@ -37,23 +37,26 @@
     ListTagsForResourcePaginator,
 )
 from .type_defs import (
     BatchGetNamedQueryOutputTypeDef,
     BatchGetPreparedStatementOutputTypeDef,
     BatchGetQueryExecutionOutputTypeDef,
     CalculationConfigurationTypeDef,
+    CapacityAssignmentTypeDef,
     CreateNamedQueryOutputTypeDef,
     CreateNotebookOutputTypeDef,
     CreatePresignedNotebookUrlResponseTypeDef,
     EngineConfigurationTypeDef,
     ExportNotebookOutputTypeDef,
     FilterDefinitionTypeDef,
     GetCalculationExecutionCodeResponseTypeDef,
     GetCalculationExecutionResponseTypeDef,
     GetCalculationExecutionStatusResponseTypeDef,
+    GetCapacityAssignmentConfigurationOutputTypeDef,
+    GetCapacityReservationOutputTypeDef,
     GetDatabaseOutputTypeDef,
     GetDataCatalogOutputTypeDef,
     GetNamedQueryOutputTypeDef,
     GetNotebookMetadataOutputTypeDef,
     GetPreparedStatementOutputTypeDef,
     GetQueryExecutionOutputTypeDef,
     GetQueryResultsOutputTypeDef,
@@ -61,14 +64,15 @@
     GetSessionResponseTypeDef,
     GetSessionStatusResponseTypeDef,
     GetTableMetadataOutputTypeDef,
     GetWorkGroupOutputTypeDef,
     ImportNotebookOutputTypeDef,
     ListApplicationDPUSizesOutputTypeDef,
     ListCalculationExecutionsResponseTypeDef,
+    ListCapacityReservationsOutputTypeDef,
     ListDatabasesOutputTypeDef,
     ListDataCatalogsOutputTypeDef,
     ListEngineVersionsOutputTypeDef,
     ListExecutorsResponseTypeDef,
     ListNamedQueriesOutputTypeDef,
     ListNotebookMetadataOutputTypeDef,
     ListNotebookSessionsResponseTypeDef,
@@ -92,32 +96,36 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("AthenaClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidRequestException: Type[BotocoreClientError]
     MetadataException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     SessionAlreadyExistsException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
 
+
 class AthenaClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/)
     """
 
     meta: ClientMeta
@@ -126,58 +134,83 @@
     def exceptions(self) -> Exceptions:
         """
         AthenaClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#exceptions)
         """
+
     async def batch_get_named_query(
         self, *, NamedQueryIds: Sequence[str]
     ) -> BatchGetNamedQueryOutputTypeDef:
         """
         Returns the details of a single named query or a list of up to 50 queries, which
         you provide as an array of query ID strings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.batch_get_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#batch_get_named_query)
         """
+
     async def batch_get_prepared_statement(
         self, *, PreparedStatementNames: Sequence[str], WorkGroup: str
     ) -> BatchGetPreparedStatementOutputTypeDef:
         """
         Returns the details of a single prepared statement or a list of up to 256
         prepared statements for the array of prepared statement names that you provide.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.batch_get_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#batch_get_prepared_statement)
         """
+
     async def batch_get_query_execution(
         self, *, QueryExecutionIds: Sequence[str]
     ) -> BatchGetQueryExecutionOutputTypeDef:
         """
         Returns the details of a single query execution or a list of up to 50 query
         executions, which you provide as an array of query execution ID strings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.batch_get_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#batch_get_query_execution)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#can_paginate)
         """
+
+    async def cancel_capacity_reservation(self, *, Name: str) -> Dict[str, Any]:
+        """
+        Cancels the capacity reservation with the specified name.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.cancel_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#cancel_capacity_reservation)
+        """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#close)
         """
+
+    async def create_capacity_reservation(
+        self, *, TargetDpus: int, Name: str, Tags: Sequence[TagTypeDef] = ...
+    ) -> Dict[str, Any]:
+        """
+        Creates a capacity reservation with the specified name and number of requested
+        data processing units.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_capacity_reservation)
+        """
+
     async def create_data_catalog(
         self,
         *,
         Name: str,
         Type: DataCatalogTypeType,
         Description: str = ...,
         Parameters: Mapping[str, str] = ...,
@@ -185,14 +218,15 @@
     ) -> Dict[str, Any]:
         """
         Creates (registers) a data catalog with the specified name and properties.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_data_catalog)
         """
+
     async def create_named_query(
         self,
         *,
         Name: str,
         Database: str,
         QueryString: str,
         Description: str = ...,
@@ -201,243 +235,296 @@
     ) -> CreateNamedQueryOutputTypeDef:
         """
         Creates a named query in the specified workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_named_query)
         """
+
     async def create_notebook(
         self, *, WorkGroup: str, Name: str, ClientRequestToken: str = ...
     ) -> CreateNotebookOutputTypeDef:
         """
         Creates an empty `ipynb` file in the specified Apache Spark enabled workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_notebook)
         """
+
     async def create_prepared_statement(
         self, *, StatementName: str, WorkGroup: str, QueryStatement: str, Description: str = ...
     ) -> Dict[str, Any]:
         """
         Creates a prepared statement for use with SQL queries in Athena.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_prepared_statement)
         """
+
     async def create_presigned_notebook_url(
         self, *, SessionId: str
     ) -> CreatePresignedNotebookUrlResponseTypeDef:
         """
         Gets an authentication token and the URL at which the notebook can be accessed.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_presigned_notebook_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_presigned_notebook_url)
         """
+
     async def create_work_group(
         self,
         *,
         Name: str,
         Configuration: WorkGroupConfigurationTypeDef = ...,
         Description: str = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> Dict[str, Any]:
         """
         Creates a workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.create_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#create_work_group)
         """
+
+    async def delete_capacity_reservation(self, *, Name: str) -> Dict[str, Any]:
+        """
+        Deletes a cancelled capacity reservation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_capacity_reservation)
+        """
+
     async def delete_data_catalog(self, *, Name: str) -> Dict[str, Any]:
         """
         Deletes a data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_data_catalog)
         """
+
     async def delete_named_query(self, *, NamedQueryId: str) -> Dict[str, Any]:
         """
         Deletes the named query if you have access to the workgroup in which the query
         was saved.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_named_query)
         """
+
     async def delete_notebook(self, *, NotebookId: str) -> Dict[str, Any]:
         """
         Deletes the specified notebook.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_notebook)
         """
+
     async def delete_prepared_statement(
         self, *, StatementName: str, WorkGroup: str
     ) -> Dict[str, Any]:
         """
         Deletes the prepared statement with the specified name from the specified
         workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_prepared_statement)
         """
+
     async def delete_work_group(
         self, *, WorkGroup: str, RecursiveDeleteOption: bool = ...
     ) -> Dict[str, Any]:
         """
         Deletes the workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.delete_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#delete_work_group)
         """
+
     async def export_notebook(self, *, NotebookId: str) -> ExportNotebookOutputTypeDef:
         """
         Exports the specified notebook and its metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.export_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#export_notebook)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#generate_presigned_url)
         """
+
     async def get_calculation_execution(
         self, *, CalculationExecutionId: str
     ) -> GetCalculationExecutionResponseTypeDef:
         """
         Describes a previously submitted calculation execution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_calculation_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_calculation_execution)
         """
+
     async def get_calculation_execution_code(
         self, *, CalculationExecutionId: str
     ) -> GetCalculationExecutionCodeResponseTypeDef:
         """
-        Retrieves a pre-signed URL to a copy of the code that was executed for the
-        calculation.
+        Retrieves the unencrypted code that was executed for the calculation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_calculation_execution_code)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_calculation_execution_code)
         """
+
     async def get_calculation_execution_status(
         self, *, CalculationExecutionId: str
     ) -> GetCalculationExecutionStatusResponseTypeDef:
         """
         Gets the status of a current calculation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_calculation_execution_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_calculation_execution_status)
         """
+
+    async def get_capacity_assignment_configuration(
+        self, *, CapacityReservationName: str
+    ) -> GetCapacityAssignmentConfigurationOutputTypeDef:
+        """
+        Gets the capacity assignment configuration for a capacity reservation, if one
+        exists.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_capacity_assignment_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_capacity_assignment_configuration)
+        """
+
+    async def get_capacity_reservation(self, *, Name: str) -> GetCapacityReservationOutputTypeDef:
+        """
+        Returns information about the capacity reservation with the specified name.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_capacity_reservation)
+        """
+
     async def get_data_catalog(self, *, Name: str) -> GetDataCatalogOutputTypeDef:
         """
         Returns the specified data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_data_catalog)
         """
+
     async def get_database(
         self, *, CatalogName: str, DatabaseName: str
     ) -> GetDatabaseOutputTypeDef:
         """
         Returns a database object for the specified database and data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_database)
         """
+
     async def get_named_query(self, *, NamedQueryId: str) -> GetNamedQueryOutputTypeDef:
         """
         Returns information about a single query.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_named_query)
         """
+
     async def get_notebook_metadata(self, *, NotebookId: str) -> GetNotebookMetadataOutputTypeDef:
         """
         Retrieves notebook metadata for the specified notebook ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_notebook_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_notebook_metadata)
         """
+
     async def get_prepared_statement(
         self, *, StatementName: str, WorkGroup: str
     ) -> GetPreparedStatementOutputTypeDef:
         """
         Retrieves the prepared statement with the specified name from the specified
         workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_prepared_statement)
         """
+
     async def get_query_execution(self, *, QueryExecutionId: str) -> GetQueryExecutionOutputTypeDef:
         """
         Returns information about a single execution of a query if you have access to
         the workgroup in which the query ran.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_query_execution)
         """
+
     async def get_query_results(
         self, *, QueryExecutionId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> GetQueryResultsOutputTypeDef:
         """
         Streams the results of a single query execution specified by `QueryExecutionId`
         from the Athena query results location in Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_query_results)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_query_results)
         """
+
     async def get_query_runtime_statistics(
         self, *, QueryExecutionId: str
     ) -> GetQueryRuntimeStatisticsOutputTypeDef:
         """
         Returns query execution runtime statistics related to a single execution of a
         query if you have access to the workgroup in which the query ran.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_query_runtime_statistics)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_query_runtime_statistics)
         """
+
     async def get_session(self, *, SessionId: str) -> GetSessionResponseTypeDef:
         """
         Gets the full details of a previously created session, including the session
         status and configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_session)
         """
+
     async def get_session_status(self, *, SessionId: str) -> GetSessionStatusResponseTypeDef:
         """
         Gets the current status of a session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_session_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_session_status)
         """
+
     async def get_table_metadata(
         self, *, CatalogName: str, DatabaseName: str, TableName: str
     ) -> GetTableMetadataOutputTypeDef:
         """
         Returns table metadata for the specified catalog, database, and table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_table_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_table_metadata)
         """
+
     async def get_work_group(self, *, WorkGroup: str) -> GetWorkGroupOutputTypeDef:
         """
         Returns information about the workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_work_group)
         """
+
     async def import_notebook(
         self,
         *,
         WorkGroup: str,
         Name: str,
         Payload: str,
         Type: Literal["IPYNB"],
@@ -445,24 +532,26 @@
     ) -> ImportNotebookOutputTypeDef:
         """
         Imports a single `ipynb` file to a Spark enabled workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.import_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#import_notebook)
         """
+
     async def list_application_dpu_sizes(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListApplicationDPUSizesOutputTypeDef:
         """
         Returns the supported DPU sizes for the supported application runtimes (for
-        example, `Jupyter 1.0` ).
+        example, `Athena notebook version 1`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_application_dpu_sizes)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_application_dpu_sizes)
         """
+
     async def list_calculation_executions(
         self,
         *,
         SessionId: str,
         StateFilter: CalculationExecutionStateType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
@@ -470,124 +559,145 @@
         """
         Lists the calculations that have been submitted to a session in descending
         order.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_calculation_executions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_calculation_executions)
         """
+
+    async def list_capacity_reservations(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListCapacityReservationsOutputTypeDef:
+        """
+        Lists the capacity reservations for the current account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_capacity_reservations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_capacity_reservations)
+        """
+
     async def list_data_catalogs(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDataCatalogsOutputTypeDef:
         """
         Lists the data catalogs in the current Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_data_catalogs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_data_catalogs)
         """
+
     async def list_databases(
         self, *, CatalogName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDatabasesOutputTypeDef:
         """
         Lists the databases in the specified data catalog.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_databases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_databases)
         """
+
     async def list_engine_versions(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEngineVersionsOutputTypeDef:
         """
         Returns a list of engine versions that are available to choose from, including
         the Auto option.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_engine_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_engine_versions)
         """
+
     async def list_executors(
         self,
         *,
         SessionId: str,
         ExecutorStateFilter: ExecutorStateType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListExecutorsResponseTypeDef:
         """
-        Lists, in descending order, the executors that have been submitted to a session.
+        Lists, in descending order, the executors that joined a session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_executors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_executors)
         """
+
     async def list_named_queries(
         self, *, NextToken: str = ..., MaxResults: int = ..., WorkGroup: str = ...
     ) -> ListNamedQueriesOutputTypeDef:
         """
         Provides a list of available query IDs only for queries saved in the specified
         workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_named_queries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_named_queries)
         """
+
     async def list_notebook_metadata(
         self,
         *,
         WorkGroup: str,
         Filters: FilterDefinitionTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListNotebookMetadataOutputTypeDef:
         """
         Displays the notebook files for the specified workgroup in paginated format.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_notebook_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_notebook_metadata)
         """
+
     async def list_notebook_sessions(
         self, *, NotebookId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListNotebookSessionsResponseTypeDef:
         """
         Lists, in descending order, the sessions that have been created in a notebook
-        that are in an active state like `CREATING` , `CREATED` , `IDLE` or `BUSY`.
+        that are in an active state like `CREATING`, `CREATED`, `IDLE` or `BUSY`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_notebook_sessions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_notebook_sessions)
         """
+
     async def list_prepared_statements(
         self, *, WorkGroup: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListPreparedStatementsOutputTypeDef:
         """
         Lists the prepared statements in the specified workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_prepared_statements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_prepared_statements)
         """
+
     async def list_query_executions(
         self, *, NextToken: str = ..., MaxResults: int = ..., WorkGroup: str = ...
     ) -> ListQueryExecutionsOutputTypeDef:
         """
         Provides a list of available query execution IDs for the queries in the
         specified workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_query_executions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_query_executions)
         """
+
     async def list_sessions(
         self,
         *,
         WorkGroup: str,
         StateFilter: SessionStateType = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListSessionsResponseTypeDef:
         """
-        Lists the sessions in a workgroup that are in an active state like `CREATING` ,
-        `CREATED` , `IDLE` , or `BUSY`.
+        Lists the sessions in a workgroup that are in an active state like `CREATING`,
+        `CREATED`, `IDLE`, or `BUSY`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_sessions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_sessions)
         """
+
     async def list_table_metadata(
         self,
         *,
         CatalogName: str,
         DatabaseName: str,
         Expression: str = ...,
         NextToken: str = ...,
@@ -595,32 +705,49 @@
     ) -> ListTableMetadataOutputTypeDef:
         """
         Lists the metadata for the tables in the specified data catalog database.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_table_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_table_metadata)
         """
+
     async def list_tags_for_resource(
         self, *, ResourceARN: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListTagsForResourceOutputTypeDef:
         """
-        Lists the tags associated with an Athena workgroup or data catalog resource.
+        Lists the tags associated with an Athena resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_tags_for_resource)
         """
+
     async def list_work_groups(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListWorkGroupsOutputTypeDef:
         """
         Lists available workgroups for the account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.list_work_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#list_work_groups)
         """
+
+    async def put_capacity_assignment_configuration(
+        self,
+        *,
+        CapacityReservationName: str,
+        CapacityAssignments: Sequence[CapacityAssignmentTypeDef]
+    ) -> Dict[str, Any]:
+        """
+        Puts a new capacity assignment configuration for a specified capacity
+        reservation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.put_capacity_assignment_configuration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#put_capacity_assignment_configuration)
+        """
+
     async def start_calculation_execution(
         self,
         *,
         SessionId: str,
         Description: str = ...,
         CalculationConfiguration: CalculationConfigurationTypeDef = ...,
         CodeBlock: str = ...,
@@ -628,14 +755,15 @@
     ) -> StartCalculationExecutionResponseTypeDef:
         """
         Submits calculations for execution within a session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.start_calculation_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#start_calculation_execution)
         """
+
     async def start_query_execution(
         self,
         *,
         QueryString: str,
         ClientRequestToken: str = ...,
         QueryExecutionContext: QueryExecutionContextTypeDef = ...,
         ResultConfiguration: ResultConfigurationTypeDef = ...,
@@ -645,14 +773,15 @@
     ) -> StartQueryExecutionOutputTypeDef:
         """
         Runs the SQL query statements contained in the `Query`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.start_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#start_query_execution)
         """
+
     async def start_session(
         self,
         *,
         WorkGroup: str,
         EngineConfiguration: EngineConfigurationTypeDef,
         Description: str = ...,
         NotebookVersion: str = ...,
@@ -661,74 +790,91 @@
     ) -> StartSessionResponseTypeDef:
         """
         Creates a session for running calculations within a workgroup.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.start_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#start_session)
         """
+
     async def stop_calculation_execution(
         self, *, CalculationExecutionId: str
     ) -> StopCalculationExecutionResponseTypeDef:
         """
         Requests the cancellation of a calculation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.stop_calculation_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#stop_calculation_execution)
         """
+
     async def stop_query_execution(self, *, QueryExecutionId: str) -> Dict[str, Any]:
         """
         Stops a query execution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.stop_query_execution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#stop_query_execution)
         """
+
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Adds one or more tags to an Athena resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#tag_resource)
         """
+
     async def terminate_session(self, *, SessionId: str) -> TerminateSessionResponseTypeDef:
         """
         Terminates an active session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.terminate_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#terminate_session)
         """
+
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Removes one or more tags from a data catalog or workgroup resource.
+        Removes one or more tags from an Athena resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#untag_resource)
         """
+
+    async def update_capacity_reservation(self, *, TargetDpus: int, Name: str) -> Dict[str, Any]:
+        """
+        Updates the number of requested data processing units for the capacity
+        reservation with the specified name.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_capacity_reservation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_capacity_reservation)
+        """
+
     async def update_data_catalog(
         self,
         *,
         Name: str,
         Type: DataCatalogTypeType,
         Description: str = ...,
         Parameters: Mapping[str, str] = ...
     ) -> Dict[str, Any]:
         """
         Updates the data catalog that has the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_data_catalog)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_data_catalog)
         """
+
     async def update_named_query(
         self, *, NamedQueryId: str, Name: str, QueryString: str, Description: str = ...
     ) -> Dict[str, Any]:
         """
         Updates a  NamedQuery object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_named_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_named_query)
         """
+
     async def update_notebook(
         self,
         *,
         NotebookId: str,
         Payload: str,
         Type: Literal["IPYNB"],
         SessionId: str = ...,
@@ -736,103 +882,115 @@
     ) -> Dict[str, Any]:
         """
         Updates the contents of a Spark notebook.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_notebook)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_notebook)
         """
+
     async def update_notebook_metadata(
         self, *, NotebookId: str, Name: str, ClientRequestToken: str = ...
     ) -> Dict[str, Any]:
         """
         Updates the metadata for a notebook.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_notebook_metadata)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_notebook_metadata)
         """
+
     async def update_prepared_statement(
         self, *, StatementName: str, WorkGroup: str, QueryStatement: str, Description: str = ...
     ) -> Dict[str, Any]:
         """
         Updates a prepared statement.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_prepared_statement)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_prepared_statement)
         """
+
     async def update_work_group(
         self,
         *,
         WorkGroup: str,
         Description: str = ...,
         ConfigurationUpdates: WorkGroupConfigurationUpdatesTypeDef = ...,
         State: WorkGroupStateType = ...
     ) -> Dict[str, Any]:
         """
         Updates the workgroup with the specified name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.update_work_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#update_work_group)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["get_query_results"]
     ) -> GetQueryResultsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_data_catalogs"]
     ) -> ListDataCatalogsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_databases"]) -> ListDatabasesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_named_queries"]
     ) -> ListNamedQueriesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_query_executions"]
     ) -> ListQueryExecutionsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_table_metadata"]
     ) -> ListTableMetadataPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_tags_for_resource"]
     ) -> ListTagsForResourcePaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "AthenaClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/client/)
         """
```

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/literals.py` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -17,14 +17,16 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "CalculationExecutionStateType",
+    "CapacityAllocationStatusType",
+    "CapacityReservationStatusType",
     "ColumnNullableType",
     "DataCatalogTypeType",
     "EncryptionOptionType",
     "ExecutorStateType",
     "ExecutorTypeType",
     "GetQueryResultsPaginatorName",
     "ListDataCatalogsPaginatorName",
@@ -46,14 +48,18 @@
     "RegionName",
 )
 
 
 CalculationExecutionStateType = Literal[
     "CANCELED", "CANCELING", "COMPLETED", "CREATED", "CREATING", "FAILED", "QUEUED", "RUNNING"
 ]
+CapacityAllocationStatusType = Literal["FAILED", "PENDING", "SUCCEEDED"]
+CapacityReservationStatusType = Literal[
+    "ACTIVE", "CANCELLED", "CANCELLING", "FAILED", "PENDING", "UPDATE_PENDING"
+]
 ColumnNullableType = Literal["NOT_NULL", "NULLABLE", "UNKNOWN"]
 DataCatalogTypeType = Literal["GLUE", "HIVE", "LAMBDA"]
 EncryptionOptionType = Literal["CSE_KMS", "SSE_KMS", "SSE_S3"]
 ExecutorStateType = Literal[
     "CREATED", "CREATING", "FAILED", "REGISTERED", "TERMINATED", "TERMINATING"
 ]
 ExecutorTypeType = Literal["COORDINATOR", "GATEWAY", "WORKER"]
@@ -131,14 +137,15 @@
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
@@ -217,14 +224,15 @@
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
@@ -235,14 +243,15 @@
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
@@ -278,14 +287,15 @@
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
@@ -304,16 +314,19 @@
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
@@ -397,15 +410,17 @@
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

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/literals.pyi` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,14 +16,16 @@
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "CalculationExecutionStateType",
+    "CapacityAllocationStatusType",
+    "CapacityReservationStatusType",
     "ColumnNullableType",
     "DataCatalogTypeType",
     "EncryptionOptionType",
     "ExecutorStateType",
     "ExecutorTypeType",
     "GetQueryResultsPaginatorName",
     "ListDataCatalogsPaginatorName",
@@ -44,14 +46,18 @@
     "PaginatorName",
     "RegionName",
 )
 
 CalculationExecutionStateType = Literal[
     "CANCELED", "CANCELING", "COMPLETED", "CREATED", "CREATING", "FAILED", "QUEUED", "RUNNING"
 ]
+CapacityAllocationStatusType = Literal["FAILED", "PENDING", "SUCCEEDED"]
+CapacityReservationStatusType = Literal[
+    "ACTIVE", "CANCELLED", "CANCELLING", "FAILED", "PENDING", "UPDATE_PENDING"
+]
 ColumnNullableType = Literal["NOT_NULL", "NULLABLE", "UNKNOWN"]
 DataCatalogTypeType = Literal["GLUE", "HIVE", "LAMBDA"]
 EncryptionOptionType = Literal["CSE_KMS", "SSE_KMS", "SSE_S3"]
 ExecutorStateType = Literal[
     "CREATED", "CREATING", "FAILED", "REGISTERED", "TERMINATED", "TERMINATING"
 ]
 ExecutorTypeType = Literal["COORDINATOR", "GATEWAY", "WORKER"]
@@ -129,14 +135,15 @@
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
@@ -215,14 +222,15 @@
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
@@ -233,14 +241,15 @@
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
@@ -276,14 +285,15 @@
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
@@ -302,16 +312,19 @@
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
@@ -395,15 +408,17 @@
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

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/paginator.py` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_databases_paginator: ListDatabasesPaginator = client.get_paginator("list_databases")
         list_named_queries_paginator: ListNamedQueriesPaginator = client.get_paginator("list_named_queries")
         list_query_executions_paginator: ListQueryExecutionsPaginator = client.get_paginator("list_query_executions")
         list_table_metadata_paginator: ListTableMetadataPaginator = client.get_paginator("list_table_metadata")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetQueryResultsOutputTypeDef,
     ListDatabasesOutputTypeDef,
@@ -45,142 +44,127 @@
     ListNamedQueriesOutputTypeDef,
     ListQueryExecutionsOutputTypeDef,
     ListTableMetadataOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetQueryResultsPaginator",
     "ListDataCatalogsPaginator",
     "ListDatabasesPaginator",
     "ListNamedQueriesPaginator",
     "ListQueryExecutionsPaginator",
     "ListTableMetadataPaginator",
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
 class GetQueryResultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.GetQueryResults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#getqueryresultspaginator)
     """
 
     def paginate(
-        self, *, QueryExecutionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueryExecutionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetQueryResultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.GetQueryResults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#getqueryresultspaginator)
         """
 
-
 class ListDataCatalogsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDataCatalogs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatacatalogspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataCatalogsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDataCatalogs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatacatalogspaginator)
         """
 
-
 class ListDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatabasespaginator)
     """
 
     def paginate(
-        self, *, CatalogName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CatalogName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatabasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatabasespaginator)
         """
 
-
 class ListNamedQueriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListNamedQueries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listnamedqueriespaginator)
     """
 
     def paginate(
-        self, *, WorkGroup: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, WorkGroup: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNamedQueriesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListNamedQueries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listnamedqueriespaginator)
         """
 
-
 class ListQueryExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListQueryExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listqueryexecutionspaginator)
     """
 
     def paginate(
-        self, *, WorkGroup: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, WorkGroup: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueryExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListQueryExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listqueryexecutionspaginator)
         """
 
-
 class ListTableMetadataPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTableMetadata)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtablemetadatapaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogName: str,
         DatabaseName: str,
         Expression: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableMetadataOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTableMetadata.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtablemetadatapaginator)
         """
 
-
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/paginator.pyi` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_databases_paginator: ListDatabasesPaginator = client.get_paginator("list_databases")
         list_named_queries_paginator: ListNamedQueriesPaginator = client.get_paginator("list_named_queries")
         list_query_executions_paginator: ListQueryExecutionsPaginator = client.get_paginator("list_query_executions")
         list_table_metadata_paginator: ListTableMetadataPaginator = client.get_paginator("list_table_metadata")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetQueryResultsOutputTypeDef,
     ListDatabasesOutputTypeDef,
@@ -45,132 +44,136 @@
     ListNamedQueriesOutputTypeDef,
     ListQueryExecutionsOutputTypeDef,
     ListTableMetadataOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetQueryResultsPaginator",
     "ListDataCatalogsPaginator",
     "ListDatabasesPaginator",
     "ListNamedQueriesPaginator",
     "ListQueryExecutionsPaginator",
     "ListTableMetadataPaginator",
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
 class GetQueryResultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.GetQueryResults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#getqueryresultspaginator)
     """
 
     def paginate(
-        self, *, QueryExecutionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QueryExecutionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetQueryResultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.GetQueryResults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#getqueryresultspaginator)
         """
 
+
 class ListDataCatalogsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDataCatalogs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatacatalogspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataCatalogsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDataCatalogs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatacatalogspaginator)
         """
 
+
 class ListDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatabasespaginator)
     """
 
     def paginate(
-        self, *, CatalogName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CatalogName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatabasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listdatabasespaginator)
         """
 
+
 class ListNamedQueriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListNamedQueries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listnamedqueriespaginator)
     """
 
     def paginate(
-        self, *, WorkGroup: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, WorkGroup: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNamedQueriesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListNamedQueries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listnamedqueriespaginator)
         """
 
+
 class ListQueryExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListQueryExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listqueryexecutionspaginator)
     """
 
     def paginate(
-        self, *, WorkGroup: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, WorkGroup: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQueryExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListQueryExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listqueryexecutionspaginator)
         """
 
+
 class ListTableMetadataPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTableMetadata)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtablemetadatapaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogName: str,
         DatabaseName: str,
         Expression: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTableMetadataOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTableMetadata.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtablemetadatapaginator)
         """
 
+
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceARN: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceARN: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/type_defs.py` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -13,14 +13,16 @@
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
     CalculationExecutionStateType,
+    CapacityAllocationStatusType,
+    CapacityReservationStatusType,
     ColumnNullableType,
     DataCatalogTypeType,
     EncryptionOptionType,
     ExecutorStateType,
     ExecutorTypeType,
     QueryExecutionStateType,
     SessionStateType,
@@ -40,124 +42,143 @@
 
 __all__ = (
     "AclConfigurationTypeDef",
     "ApplicationDPUSizesTypeDef",
     "AthenaErrorTypeDef",
     "BatchGetNamedQueryInputRequestTypeDef",
     "NamedQueryTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedNamedQueryIdTypeDef",
     "BatchGetPreparedStatementInputRequestTypeDef",
     "PreparedStatementTypeDef",
     "UnprocessedPreparedStatementNameTypeDef",
     "BatchGetQueryExecutionInputRequestTypeDef",
     "UnprocessedQueryExecutionIdTypeDef",
     "CalculationConfigurationTypeDef",
     "CalculationResultTypeDef",
     "CalculationStatisticsTypeDef",
     "CalculationStatusTypeDef",
+    "CancelCapacityReservationInputRequestTypeDef",
+    "CapacityAllocationTypeDef",
+    "CapacityAssignmentTypeDef",
     "ColumnInfoTypeDef",
     "ColumnTypeDef",
     "TagTypeDef",
     "CreateNamedQueryInputRequestTypeDef",
+    "CreateNamedQueryOutputTypeDef",
     "CreateNotebookInputRequestTypeDef",
+    "CreateNotebookOutputTypeDef",
     "CreatePreparedStatementInputRequestTypeDef",
     "CreatePresignedNotebookUrlRequestRequestTypeDef",
+    "CreatePresignedNotebookUrlResponseTypeDef",
     "CustomerContentEncryptionConfigurationTypeDef",
     "DataCatalogSummaryTypeDef",
     "DataCatalogTypeDef",
     "DatabaseTypeDef",
     "DatumTypeDef",
+    "DeleteCapacityReservationInputRequestTypeDef",
     "DeleteDataCatalogInputRequestTypeDef",
     "DeleteNamedQueryInputRequestTypeDef",
     "DeleteNotebookInputRequestTypeDef",
     "DeletePreparedStatementInputRequestTypeDef",
     "DeleteWorkGroupInputRequestTypeDef",
     "EncryptionConfigurationTypeDef",
     "EngineConfigurationTypeDef",
     "EngineVersionTypeDef",
     "ExecutorsSummaryTypeDef",
     "ExportNotebookInputRequestTypeDef",
     "NotebookMetadataTypeDef",
     "FilterDefinitionTypeDef",
     "GetCalculationExecutionCodeRequestRequestTypeDef",
+    "GetCalculationExecutionCodeResponseTypeDef",
     "GetCalculationExecutionRequestRequestTypeDef",
     "GetCalculationExecutionStatusRequestRequestTypeDef",
+    "GetCapacityAssignmentConfigurationInputRequestTypeDef",
+    "GetCapacityReservationInputRequestTypeDef",
     "GetDataCatalogInputRequestTypeDef",
     "GetDatabaseInputRequestTypeDef",
     "GetNamedQueryInputRequestTypeDef",
     "GetNotebookMetadataInputRequestTypeDef",
     "GetPreparedStatementInputRequestTypeDef",
     "GetQueryExecutionInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetQueryResultsInputGetQueryResultsPaginateTypeDef",
     "GetQueryResultsInputRequestTypeDef",
     "GetQueryRuntimeStatisticsInputRequestTypeDef",
     "GetSessionRequestRequestTypeDef",
     "SessionStatisticsTypeDef",
     "SessionStatusTypeDef",
     "GetSessionStatusRequestRequestTypeDef",
     "GetTableMetadataInputRequestTypeDef",
     "GetWorkGroupInputRequestTypeDef",
     "ImportNotebookInputRequestTypeDef",
+    "ImportNotebookOutputTypeDef",
     "ListApplicationDPUSizesInputRequestTypeDef",
     "ListCalculationExecutionsRequestRequestTypeDef",
+    "ListCapacityReservationsInputRequestTypeDef",
+    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
     "ListDataCatalogsInputRequestTypeDef",
+    "ListDatabasesInputListDatabasesPaginateTypeDef",
     "ListDatabasesInputRequestTypeDef",
     "ListEngineVersionsInputRequestTypeDef",
     "ListExecutorsRequestRequestTypeDef",
+    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
     "ListNamedQueriesInputRequestTypeDef",
+    "ListNamedQueriesOutputTypeDef",
     "ListNotebookSessionsRequestRequestTypeDef",
     "NotebookSessionSummaryTypeDef",
     "ListPreparedStatementsInputRequestTypeDef",
     "PreparedStatementSummaryTypeDef",
+    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
     "ListQueryExecutionsInputRequestTypeDef",
+    "ListQueryExecutionsOutputTypeDef",
     "ListSessionsRequestRequestTypeDef",
+    "ListTableMetadataInputListTableMetadataPaginateTypeDef",
     "ListTableMetadataInputRequestTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "ListWorkGroupsInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "QueryExecutionContextTypeDef",
     "ResultReuseInformationTypeDef",
     "QueryRuntimeStatisticsRowsTypeDef",
     "QueryRuntimeStatisticsTimelineTypeDef",
     "QueryStagePlanNodeTypeDef",
     "QueryStageTypeDef",
+    "ResponseMetadataTypeDef",
     "ResultReuseByAgeConfigurationTypeDef",
+    "StartCalculationExecutionResponseTypeDef",
+    "StartQueryExecutionOutputTypeDef",
+    "StartSessionResponseTypeDef",
     "StopCalculationExecutionRequestRequestTypeDef",
+    "StopCalculationExecutionResponseTypeDef",
     "StopQueryExecutionInputRequestTypeDef",
     "TerminateSessionRequestRequestTypeDef",
+    "TerminateSessionResponseTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "UpdateCapacityReservationInputRequestTypeDef",
     "UpdateDataCatalogInputRequestTypeDef",
     "UpdateNamedQueryInputRequestTypeDef",
     "UpdateNotebookInputRequestTypeDef",
     "UpdateNotebookMetadataInputRequestTypeDef",
     "UpdatePreparedStatementInputRequestTypeDef",
+    "ListApplicationDPUSizesOutputTypeDef",
     "QueryExecutionStatusTypeDef",
-    "CreateNamedQueryOutputTypeDef",
-    "CreateNotebookOutputTypeDef",
-    "CreatePresignedNotebookUrlResponseTypeDef",
-    "GetCalculationExecutionCodeResponseTypeDef",
     "GetNamedQueryOutputTypeDef",
-    "ImportNotebookOutputTypeDef",
-    "ListApplicationDPUSizesOutputTypeDef",
-    "ListNamedQueriesOutputTypeDef",
-    "ListQueryExecutionsOutputTypeDef",
-    "StartCalculationExecutionResponseTypeDef",
-    "StartQueryExecutionOutputTypeDef",
-    "StartSessionResponseTypeDef",
-    "StopCalculationExecutionResponseTypeDef",
-    "TerminateSessionResponseTypeDef",
     "BatchGetNamedQueryOutputTypeDef",
     "GetPreparedStatementOutputTypeDef",
     "BatchGetPreparedStatementOutputTypeDef",
     "StartCalculationExecutionRequestRequestTypeDef",
     "CalculationSummaryTypeDef",
     "GetCalculationExecutionResponseTypeDef",
     "GetCalculationExecutionStatusResponseTypeDef",
+    "CapacityReservationTypeDef",
+    "CapacityAssignmentConfigurationTypeDef",
+    "PutCapacityAssignmentConfigurationInputRequestTypeDef",
     "ResultSetMetadataTypeDef",
     "TableMetadataTypeDef",
+    "CreateCapacityReservationInputRequestTypeDef",
     "CreateDataCatalogInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "ListDataCatalogsOutputTypeDef",
     "GetDataCatalogOutputTypeDef",
     "GetDatabaseOutputTypeDef",
     "ListDatabasesOutputTypeDef",
@@ -169,29 +190,25 @@
     "ListEngineVersionsOutputTypeDef",
     "WorkGroupSummaryTypeDef",
     "ListExecutorsResponseTypeDef",
     "ExportNotebookOutputTypeDef",
     "GetNotebookMetadataOutputTypeDef",
     "ListNotebookMetadataOutputTypeDef",
     "ListNotebookMetadataInputRequestTypeDef",
-    "GetQueryResultsInputGetQueryResultsPaginateTypeDef",
-    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
-    "ListDatabasesInputListDatabasesPaginateTypeDef",
-    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
-    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
-    "ListTableMetadataInputListTableMetadataPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "GetSessionStatusResponseTypeDef",
     "SessionSummaryTypeDef",
     "ListNotebookSessionsResponseTypeDef",
     "ListPreparedStatementsOutputTypeDef",
     "QueryExecutionStatisticsTypeDef",
     "QueryRuntimeStatisticsTypeDef",
     "ResultReuseConfigurationTypeDef",
     "ListCalculationExecutionsResponseTypeDef",
+    "GetCapacityReservationOutputTypeDef",
+    "ListCapacityReservationsOutputTypeDef",
+    "GetCapacityAssignmentConfigurationOutputTypeDef",
     "GetTableMetadataOutputTypeDef",
     "ListTableMetadataOutputTypeDef",
     "ResultSetTypeDef",
     "WorkGroupConfigurationTypeDef",
     "WorkGroupConfigurationUpdatesTypeDef",
     "GetSessionResponseTypeDef",
     "ListWorkGroupsOutputTypeDef",
@@ -261,25 +278,14 @@
 )
 
 
 class NamedQueryTypeDef(_RequiredNamedQueryTypeDef, _OptionalNamedQueryTypeDef):
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
 UnprocessedNamedQueryIdTypeDef = TypedDict(
     "UnprocessedNamedQueryIdTypeDef",
     {
         "NamedQueryId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
@@ -368,14 +374,52 @@
         "CompletionDateTime": datetime,
         "State": CalculationExecutionStateType,
         "StateChangeReason": str,
     },
     total=False,
 )
 
+CancelCapacityReservationInputRequestTypeDef = TypedDict(
+    "CancelCapacityReservationInputRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+
+_RequiredCapacityAllocationTypeDef = TypedDict(
+    "_RequiredCapacityAllocationTypeDef",
+    {
+        "Status": CapacityAllocationStatusType,
+        "RequestTime": datetime,
+    },
+)
+_OptionalCapacityAllocationTypeDef = TypedDict(
+    "_OptionalCapacityAllocationTypeDef",
+    {
+        "StatusMessage": str,
+        "RequestCompletionTime": datetime,
+    },
+    total=False,
+)
+
+
+class CapacityAllocationTypeDef(
+    _RequiredCapacityAllocationTypeDef, _OptionalCapacityAllocationTypeDef
+):
+    pass
+
+
+CapacityAssignmentTypeDef = TypedDict(
+    "CapacityAssignmentTypeDef",
+    {
+        "WorkGroupNames": List[str],
+    },
+    total=False,
+)
+
 _RequiredColumnInfoTypeDef = TypedDict(
     "_RequiredColumnInfoTypeDef",
     {
         "Name": str,
         "Type": str,
     },
 )
@@ -449,14 +493,22 @@
 
 class CreateNamedQueryInputRequestTypeDef(
     _RequiredCreateNamedQueryInputRequestTypeDef, _OptionalCreateNamedQueryInputRequestTypeDef
 ):
     pass
 
 
+CreateNamedQueryOutputTypeDef = TypedDict(
+    "CreateNamedQueryOutputTypeDef",
+    {
+        "NamedQueryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateNotebookInputRequestTypeDef = TypedDict(
     "_RequiredCreateNotebookInputRequestTypeDef",
     {
         "WorkGroup": str,
         "Name": str,
     },
 )
@@ -471,14 +523,22 @@
 
 class CreateNotebookInputRequestTypeDef(
     _RequiredCreateNotebookInputRequestTypeDef, _OptionalCreateNotebookInputRequestTypeDef
 ):
     pass
 
 
+CreateNotebookOutputTypeDef = TypedDict(
+    "CreateNotebookOutputTypeDef",
+    {
+        "NotebookId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePreparedStatementInputRequestTypeDef = TypedDict(
     "_RequiredCreatePreparedStatementInputRequestTypeDef",
     {
         "StatementName": str,
         "WorkGroup": str,
         "QueryStatement": str,
     },
@@ -502,14 +562,24 @@
 CreatePresignedNotebookUrlRequestRequestTypeDef = TypedDict(
     "CreatePresignedNotebookUrlRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+CreatePresignedNotebookUrlResponseTypeDef = TypedDict(
+    "CreatePresignedNotebookUrlResponseTypeDef",
+    {
+        "NotebookUrl": str,
+        "AuthToken": str,
+        "AuthTokenExpirationTime": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomerContentEncryptionConfigurationTypeDef = TypedDict(
     "CustomerContentEncryptionConfigurationTypeDef",
     {
         "KmsKey": str,
     },
 )
 
@@ -567,14 +637,21 @@
     "DatumTypeDef",
     {
         "VarCharValue": str,
     },
     total=False,
 )
 
+DeleteCapacityReservationInputRequestTypeDef = TypedDict(
+    "DeleteCapacityReservationInputRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+
 DeleteDataCatalogInputRequestTypeDef = TypedDict(
     "DeleteDataCatalogInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -650,14 +727,15 @@
 )
 _OptionalEngineConfigurationTypeDef = TypedDict(
     "_OptionalEngineConfigurationTypeDef",
     {
         "CoordinatorDpuSize": int,
         "DefaultExecutorDpuSize": int,
         "AdditionalConfigs": Dict[str, str],
+        "SparkProperties": Dict[str, str],
     },
     total=False,
 )
 
 
 class EngineConfigurationTypeDef(
     _RequiredEngineConfigurationTypeDef, _OptionalEngineConfigurationTypeDef
@@ -728,28 +806,50 @@
 GetCalculationExecutionCodeRequestRequestTypeDef = TypedDict(
     "GetCalculationExecutionCodeRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
+GetCalculationExecutionCodeResponseTypeDef = TypedDict(
+    "GetCalculationExecutionCodeResponseTypeDef",
+    {
+        "CodeBlock": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCalculationExecutionRequestRequestTypeDef = TypedDict(
     "GetCalculationExecutionRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
 GetCalculationExecutionStatusRequestRequestTypeDef = TypedDict(
     "GetCalculationExecutionStatusRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
+GetCapacityAssignmentConfigurationInputRequestTypeDef = TypedDict(
+    "GetCapacityAssignmentConfigurationInputRequestTypeDef",
+    {
+        "CapacityReservationName": str,
+    },
+)
+
+GetCapacityReservationInputRequestTypeDef = TypedDict(
+    "GetCapacityReservationInputRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+
 GetDataCatalogInputRequestTypeDef = TypedDict(
     "GetDataCatalogInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -786,24 +886,36 @@
 GetQueryExecutionInputRequestTypeDef = TypedDict(
     "GetQueryExecutionInputRequestTypeDef",
     {
         "QueryExecutionId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
+    "_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "QueryExecutionId": str,
+    },
+)
+_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
+    "_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetQueryResultsInputGetQueryResultsPaginateTypeDef(
+    _RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef,
+    _OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetQueryResultsInputRequestTypeDef = TypedDict(
     "_RequiredGetQueryResultsInputRequestTypeDef",
     {
         "QueryExecutionId": str,
     },
 )
 _OptionalGetQueryResultsInputRequestTypeDef = TypedDict(
@@ -900,14 +1012,22 @@
 
 class ImportNotebookInputRequestTypeDef(
     _RequiredImportNotebookInputRequestTypeDef, _OptionalImportNotebookInputRequestTypeDef
 ):
     pass
 
 
+ImportNotebookOutputTypeDef = TypedDict(
+    "ImportNotebookOutputTypeDef",
+    {
+        "NotebookId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListApplicationDPUSizesInputRequestTypeDef = TypedDict(
     "ListApplicationDPUSizesInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -933,23 +1053,62 @@
 class ListCalculationExecutionsRequestRequestTypeDef(
     _RequiredListCalculationExecutionsRequestRequestTypeDef,
     _OptionalListCalculationExecutionsRequestRequestTypeDef,
 ):
     pass
 
 
+ListCapacityReservationsInputRequestTypeDef = TypedDict(
+    "ListCapacityReservationsInputRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListDataCatalogsInputListDataCatalogsPaginateTypeDef = TypedDict(
+    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDataCatalogsInputRequestTypeDef = TypedDict(
     "ListDataCatalogsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
+    "_RequiredListDatabasesInputListDatabasesPaginateTypeDef",
+    {
+        "CatalogName": str,
+    },
+)
+_OptionalListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
+    "_OptionalListDatabasesInputListDatabasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDatabasesInputListDatabasesPaginateTypeDef(
+    _RequiredListDatabasesInputListDatabasesPaginateTypeDef,
+    _OptionalListDatabasesInputListDatabasesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDatabasesInputRequestTypeDef = TypedDict(
     "_RequiredListDatabasesInputRequestTypeDef",
     {
         "CatalogName": str,
     },
 )
 _OptionalListDatabasesInputRequestTypeDef = TypedDict(
@@ -996,24 +1155,42 @@
 
 class ListExecutorsRequestRequestTypeDef(
     _RequiredListExecutorsRequestRequestTypeDef, _OptionalListExecutorsRequestRequestTypeDef
 ):
     pass
 
 
+ListNamedQueriesInputListNamedQueriesPaginateTypeDef = TypedDict(
+    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
+    {
+        "WorkGroup": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListNamedQueriesInputRequestTypeDef = TypedDict(
     "ListNamedQueriesInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "WorkGroup": str,
     },
     total=False,
 )
 
+ListNamedQueriesOutputTypeDef = TypedDict(
+    "ListNamedQueriesOutputTypeDef",
+    {
+        "NamedQueryIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListNotebookSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListNotebookSessionsRequestRequestTypeDef",
     {
         "NotebookId": str,
     },
 )
 _OptionalListNotebookSessionsRequestRequestTypeDef = TypedDict(
@@ -1070,24 +1247,42 @@
     {
         "StatementName": str,
         "LastModifiedTime": datetime,
     },
     total=False,
 )
 
+ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef = TypedDict(
+    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
+    {
+        "WorkGroup": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueryExecutionsInputRequestTypeDef = TypedDict(
     "ListQueryExecutionsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "WorkGroup": str,
     },
     total=False,
 )
 
+ListQueryExecutionsOutputTypeDef = TypedDict(
+    "ListQueryExecutionsOutputTypeDef",
+    {
+        "QueryExecutionIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSessionsRequestRequestTypeDef",
     {
         "WorkGroup": str,
     },
 )
 _OptionalListSessionsRequestRequestTypeDef = TypedDict(
@@ -1103,14 +1298,38 @@
 
 class ListSessionsRequestRequestTypeDef(
     _RequiredListSessionsRequestRequestTypeDef, _OptionalListSessionsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
+    "_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef",
+    {
+        "CatalogName": str,
+        "DatabaseName": str,
+    },
+)
+_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
+    "_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef",
+    {
+        "Expression": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTableMetadataInputListTableMetadataPaginateTypeDef(
+    _RequiredListTableMetadataInputListTableMetadataPaginateTypeDef,
+    _OptionalListTableMetadataInputListTableMetadataPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTableMetadataInputRequestTypeDef = TypedDict(
     "_RequiredListTableMetadataInputRequestTypeDef",
     {
         "CatalogName": str,
         "DatabaseName": str,
     },
 )
@@ -1127,14 +1346,36 @@
 
 class ListTableMetadataInputRequestTypeDef(
     _RequiredListTableMetadataInputRequestTypeDef, _OptionalListTableMetadataInputRequestTypeDef
 ):
     pass
 
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -1158,14 +1399,24 @@
     {
         "NextToken": str,
         "MaxResults": int,
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
 QueryExecutionContextTypeDef = TypedDict(
     "QueryExecutionContextTypeDef",
     {
         "Database": str,
         "Catalog": str,
     },
     total=False,
@@ -1224,14 +1475,25 @@
         "ExecutionTime": int,
         "QueryStagePlan": "QueryStagePlanNodeTypeDef",
         "SubStages": List[Dict[str, Any]],
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
 _RequiredResultReuseByAgeConfigurationTypeDef = TypedDict(
     "_RequiredResultReuseByAgeConfigurationTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalResultReuseByAgeConfigurationTypeDef = TypedDict(
@@ -1245,43 +1507,93 @@
 
 class ResultReuseByAgeConfigurationTypeDef(
     _RequiredResultReuseByAgeConfigurationTypeDef, _OptionalResultReuseByAgeConfigurationTypeDef
 ):
     pass
 
 
+StartCalculationExecutionResponseTypeDef = TypedDict(
+    "StartCalculationExecutionResponseTypeDef",
+    {
+        "CalculationExecutionId": str,
+        "State": CalculationExecutionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartQueryExecutionOutputTypeDef = TypedDict(
+    "StartQueryExecutionOutputTypeDef",
+    {
+        "QueryExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSessionResponseTypeDef = TypedDict(
+    "StartSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "State": SessionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopCalculationExecutionRequestRequestTypeDef = TypedDict(
     "StopCalculationExecutionRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
+StopCalculationExecutionResponseTypeDef = TypedDict(
+    "StopCalculationExecutionResponseTypeDef",
+    {
+        "State": CalculationExecutionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopQueryExecutionInputRequestTypeDef = TypedDict(
     "StopQueryExecutionInputRequestTypeDef",
     {
         "QueryExecutionId": str,
     },
 )
 
 TerminateSessionRequestRequestTypeDef = TypedDict(
     "TerminateSessionRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+TerminateSessionResponseTypeDef = TypedDict(
+    "TerminateSessionResponseTypeDef",
+    {
+        "State": SessionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateCapacityReservationInputRequestTypeDef = TypedDict(
+    "UpdateCapacityReservationInputRequestTypeDef",
+    {
+        "TargetDpus": int,
+        "Name": str,
+    },
+)
+
 _RequiredUpdateDataCatalogInputRequestTypeDef = TypedDict(
     "_RequiredUpdateDataCatalogInputRequestTypeDef",
     {
         "Name": str,
         "Type": DataCatalogTypeType,
     },
 )
@@ -1391,168 +1703,66 @@
 class UpdatePreparedStatementInputRequestTypeDef(
     _RequiredUpdatePreparedStatementInputRequestTypeDef,
     _OptionalUpdatePreparedStatementInputRequestTypeDef,
 ):
     pass
 
 
+ListApplicationDPUSizesOutputTypeDef = TypedDict(
+    "ListApplicationDPUSizesOutputTypeDef",
+    {
+        "ApplicationDPUSizes": List[ApplicationDPUSizesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 QueryExecutionStatusTypeDef = TypedDict(
     "QueryExecutionStatusTypeDef",
     {
         "State": QueryExecutionStateType,
         "StateChangeReason": str,
         "SubmissionDateTime": datetime,
         "CompletionDateTime": datetime,
         "AthenaError": AthenaErrorTypeDef,
     },
     total=False,
 )
 
-CreateNamedQueryOutputTypeDef = TypedDict(
-    "CreateNamedQueryOutputTypeDef",
-    {
-        "NamedQueryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNotebookOutputTypeDef = TypedDict(
-    "CreateNotebookOutputTypeDef",
-    {
-        "NotebookId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePresignedNotebookUrlResponseTypeDef = TypedDict(
-    "CreatePresignedNotebookUrlResponseTypeDef",
-    {
-        "NotebookUrl": str,
-        "AuthToken": str,
-        "AuthTokenExpirationTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCalculationExecutionCodeResponseTypeDef = TypedDict(
-    "GetCalculationExecutionCodeResponseTypeDef",
-    {
-        "CodeBlock": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetNamedQueryOutputTypeDef = TypedDict(
     "GetNamedQueryOutputTypeDef",
     {
         "NamedQuery": NamedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportNotebookOutputTypeDef = TypedDict(
-    "ImportNotebookOutputTypeDef",
-    {
-        "NotebookId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationDPUSizesOutputTypeDef = TypedDict(
-    "ListApplicationDPUSizesOutputTypeDef",
-    {
-        "ApplicationDPUSizes": List[ApplicationDPUSizesTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListNamedQueriesOutputTypeDef = TypedDict(
-    "ListNamedQueriesOutputTypeDef",
-    {
-        "NamedQueryIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListQueryExecutionsOutputTypeDef = TypedDict(
-    "ListQueryExecutionsOutputTypeDef",
-    {
-        "QueryExecutionIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartCalculationExecutionResponseTypeDef = TypedDict(
-    "StartCalculationExecutionResponseTypeDef",
-    {
-        "CalculationExecutionId": str,
-        "State": CalculationExecutionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartQueryExecutionOutputTypeDef = TypedDict(
-    "StartQueryExecutionOutputTypeDef",
-    {
-        "QueryExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSessionResponseTypeDef = TypedDict(
-    "StartSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "State": SessionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopCalculationExecutionResponseTypeDef = TypedDict(
-    "StopCalculationExecutionResponseTypeDef",
-    {
-        "State": CalculationExecutionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateSessionResponseTypeDef = TypedDict(
-    "TerminateSessionResponseTypeDef",
-    {
-        "State": SessionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetNamedQueryOutputTypeDef = TypedDict(
     "BatchGetNamedQueryOutputTypeDef",
     {
         "NamedQueries": List[NamedQueryTypeDef],
         "UnprocessedNamedQueryIds": List[UnprocessedNamedQueryIdTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPreparedStatementOutputTypeDef = TypedDict(
     "GetPreparedStatementOutputTypeDef",
     {
         "PreparedStatement": PreparedStatementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetPreparedStatementOutputTypeDef = TypedDict(
     "BatchGetPreparedStatementOutputTypeDef",
     {
         "PreparedStatements": List[PreparedStatementTypeDef],
         "UnprocessedPreparedStatementNames": List[UnprocessedPreparedStatementNameTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartCalculationExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredStartCalculationExecutionRequestRequestTypeDef",
     {
         "SessionId": str,
@@ -1593,24 +1803,67 @@
         "CalculationExecutionId": str,
         "SessionId": str,
         "Description": str,
         "WorkingDirectory": str,
         "Status": CalculationStatusTypeDef,
         "Statistics": CalculationStatisticsTypeDef,
         "Result": CalculationResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCalculationExecutionStatusResponseTypeDef = TypedDict(
     "GetCalculationExecutionStatusResponseTypeDef",
     {
         "Status": CalculationStatusTypeDef,
         "Statistics": CalculationStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCapacityReservationTypeDef = TypedDict(
+    "_RequiredCapacityReservationTypeDef",
+    {
+        "Name": str,
+        "Status": CapacityReservationStatusType,
+        "TargetDpus": int,
+        "AllocatedDpus": int,
+        "CreationTime": datetime,
+    },
+)
+_OptionalCapacityReservationTypeDef = TypedDict(
+    "_OptionalCapacityReservationTypeDef",
+    {
+        "LastAllocation": CapacityAllocationTypeDef,
+        "LastSuccessfulAllocationTime": datetime,
+    },
+    total=False,
+)
+
+
+class CapacityReservationTypeDef(
+    _RequiredCapacityReservationTypeDef, _OptionalCapacityReservationTypeDef
+):
+    pass
+
+
+CapacityAssignmentConfigurationTypeDef = TypedDict(
+    "CapacityAssignmentConfigurationTypeDef",
+    {
+        "CapacityReservationName": str,
+        "CapacityAssignments": List[CapacityAssignmentTypeDef],
+    },
+    total=False,
+)
+
+PutCapacityAssignmentConfigurationInputRequestTypeDef = TypedDict(
+    "PutCapacityAssignmentConfigurationInputRequestTypeDef",
+    {
+        "CapacityReservationName": str,
+        "CapacityAssignments": Sequence[CapacityAssignmentTypeDef],
     },
 )
 
 ResultSetMetadataTypeDef = TypedDict(
     "ResultSetMetadataTypeDef",
     {
         "ColumnInfo": List[ColumnInfoTypeDef],
@@ -1638,14 +1891,37 @@
 )
 
 
 class TableMetadataTypeDef(_RequiredTableMetadataTypeDef, _OptionalTableMetadataTypeDef):
     pass
 
 
+_RequiredCreateCapacityReservationInputRequestTypeDef = TypedDict(
+    "_RequiredCreateCapacityReservationInputRequestTypeDef",
+    {
+        "TargetDpus": int,
+        "Name": str,
+    },
+)
+_OptionalCreateCapacityReservationInputRequestTypeDef = TypedDict(
+    "_OptionalCreateCapacityReservationInputRequestTypeDef",
+    {
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreateCapacityReservationInputRequestTypeDef(
+    _RequiredCreateCapacityReservationInputRequestTypeDef,
+    _OptionalCreateCapacityReservationInputRequestTypeDef,
+):
+    pass
+
+
 _RequiredCreateDataCatalogInputRequestTypeDef = TypedDict(
     "_RequiredCreateDataCatalogInputRequestTypeDef",
     {
         "Name": str,
         "Type": DataCatalogTypeType,
     },
 )
@@ -1667,15 +1943,15 @@
 
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
@@ -1684,40 +1960,40 @@
 )
 
 ListDataCatalogsOutputTypeDef = TypedDict(
     "ListDataCatalogsOutputTypeDef",
     {
         "DataCatalogsSummary": List[DataCatalogSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataCatalogOutputTypeDef = TypedDict(
     "GetDataCatalogOutputTypeDef",
     {
         "DataCatalog": DataCatalogTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDatabaseOutputTypeDef = TypedDict(
     "GetDatabaseOutputTypeDef",
     {
         "Database": DatabaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatabasesOutputTypeDef = TypedDict(
     "ListDatabasesOutputTypeDef",
     {
         "DatabaseList": List[DatabaseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RowTypeDef = TypedDict(
     "RowTypeDef",
     {
         "Data": List[DatumTypeDef],
@@ -1788,15 +2064,15 @@
 
 
 ListEngineVersionsOutputTypeDef = TypedDict(
     "ListEngineVersionsOutputTypeDef",
     {
         "EngineVersions": List[EngineVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkGroupSummaryTypeDef = TypedDict(
     "WorkGroupSummaryTypeDef",
     {
         "Name": str,
@@ -1810,41 +2086,41 @@
 
 ListExecutorsResponseTypeDef = TypedDict(
     "ListExecutorsResponseTypeDef",
     {
         "SessionId": str,
         "NextToken": str,
         "ExecutorsSummary": List[ExecutorsSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportNotebookOutputTypeDef = TypedDict(
     "ExportNotebookOutputTypeDef",
     {
         "NotebookMetadata": NotebookMetadataTypeDef,
         "Payload": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNotebookMetadataOutputTypeDef = TypedDict(
     "GetNotebookMetadataOutputTypeDef",
     {
         "NotebookMetadata": NotebookMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNotebookMetadataOutputTypeDef = TypedDict(
     "ListNotebookMetadataOutputTypeDef",
     {
         "NextToken": str,
         "NotebookMetadataList": List[NotebookMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListNotebookMetadataInputRequestTypeDef = TypedDict(
     "_RequiredListNotebookMetadataInputRequestTypeDef",
     {
         "WorkGroup": str,
@@ -1864,136 +2140,20 @@
 class ListNotebookMetadataInputRequestTypeDef(
     _RequiredListNotebookMetadataInputRequestTypeDef,
     _OptionalListNotebookMetadataInputRequestTypeDef,
 ):
     pass
 
 
-_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
-    "_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef",
-    {
-        "QueryExecutionId": str,
-    },
-)
-_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
-    "_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetQueryResultsInputGetQueryResultsPaginateTypeDef(
-    _RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef,
-    _OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef,
-):
-    pass
-
-
-ListDataCatalogsInputListDataCatalogsPaginateTypeDef = TypedDict(
-    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
-    "_RequiredListDatabasesInputListDatabasesPaginateTypeDef",
-    {
-        "CatalogName": str,
-    },
-)
-_OptionalListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
-    "_OptionalListDatabasesInputListDatabasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDatabasesInputListDatabasesPaginateTypeDef(
-    _RequiredListDatabasesInputListDatabasesPaginateTypeDef,
-    _OptionalListDatabasesInputListDatabasesPaginateTypeDef,
-):
-    pass
-
-
-ListNamedQueriesInputListNamedQueriesPaginateTypeDef = TypedDict(
-    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
-    {
-        "WorkGroup": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef = TypedDict(
-    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
-    {
-        "WorkGroup": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
-    "_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef",
-    {
-        "CatalogName": str,
-        "DatabaseName": str,
-    },
-)
-_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
-    "_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef",
-    {
-        "Expression": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTableMetadataInputListTableMetadataPaginateTypeDef(
-    _RequiredListTableMetadataInputListTableMetadataPaginateTypeDef,
-    _OptionalListTableMetadataInputListTableMetadataPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
 GetSessionStatusResponseTypeDef = TypedDict(
     "GetSessionStatusResponseTypeDef",
     {
         "SessionId": str,
         "Status": SessionStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SessionSummaryTypeDef = TypedDict(
     "SessionSummaryTypeDef",
     {
         "SessionId": str,
@@ -2006,24 +2166,24 @@
 )
 
 ListNotebookSessionsResponseTypeDef = TypedDict(
     "ListNotebookSessionsResponseTypeDef",
     {
         "NotebookSessionsList": List[NotebookSessionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPreparedStatementsOutputTypeDef = TypedDict(
     "ListPreparedStatementsOutputTypeDef",
     {
         "PreparedStatements": List[PreparedStatementSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryExecutionStatisticsTypeDef = TypedDict(
     "QueryExecutionStatisticsTypeDef",
     {
         "EngineExecutionTimeInMillis": int,
@@ -2057,32 +2217,57 @@
 )
 
 ListCalculationExecutionsResponseTypeDef = TypedDict(
     "ListCalculationExecutionsResponseTypeDef",
     {
         "NextToken": str,
         "Calculations": List[CalculationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCapacityReservationOutputTypeDef = TypedDict(
+    "GetCapacityReservationOutputTypeDef",
+    {
+        "CapacityReservation": CapacityReservationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCapacityReservationsOutputTypeDef = TypedDict(
+    "ListCapacityReservationsOutputTypeDef",
+    {
+        "NextToken": str,
+        "CapacityReservations": List[CapacityReservationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCapacityAssignmentConfigurationOutputTypeDef = TypedDict(
+    "GetCapacityAssignmentConfigurationOutputTypeDef",
+    {
+        "CapacityAssignmentConfiguration": CapacityAssignmentConfigurationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableMetadataOutputTypeDef = TypedDict(
     "GetTableMetadataOutputTypeDef",
     {
         "TableMetadata": TableMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTableMetadataOutputTypeDef = TypedDict(
     "ListTableMetadataOutputTypeDef",
     {
         "TableMetadataList": List[TableMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResultSetTypeDef = TypedDict(
     "ResultSetTypeDef",
     {
         "Rows": List[RowTypeDef],
@@ -2099,14 +2284,15 @@
         "PublishCloudWatchMetricsEnabled": bool,
         "BytesScannedCutoffPerQuery": int,
         "RequesterPaysEnabled": bool,
         "EngineVersion": EngineVersionTypeDef,
         "AdditionalConfiguration": str,
         "ExecutionRole": str,
         "CustomerContentEncryptionConfiguration": CustomerContentEncryptionConfigurationTypeDef,
+        "EnableMinimumEncryptionConfiguration": bool,
     },
     total=False,
 )
 
 WorkGroupConfigurationUpdatesTypeDef = TypedDict(
     "WorkGroupConfigurationUpdatesTypeDef",
     {
@@ -2117,14 +2303,15 @@
         "RemoveBytesScannedCutoffPerQuery": bool,
         "RequesterPaysEnabled": bool,
         "EngineVersion": EngineVersionTypeDef,
         "RemoveCustomerContentEncryptionConfiguration": bool,
         "AdditionalConfiguration": str,
         "ExecutionRole": str,
         "CustomerContentEncryptionConfiguration": CustomerContentEncryptionConfigurationTypeDef,
+        "EnableMinimumEncryptionConfiguration": bool,
     },
     total=False,
 )
 
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
@@ -2133,41 +2320,41 @@
         "WorkGroup": str,
         "EngineVersion": str,
         "EngineConfiguration": EngineConfigurationTypeDef,
         "NotebookVersion": str,
         "SessionConfiguration": SessionConfigurationTypeDef,
         "Status": SessionStatusTypeDef,
         "Statistics": SessionStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkGroupsOutputTypeDef = TypedDict(
     "ListWorkGroupsOutputTypeDef",
     {
         "WorkGroups": List[WorkGroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSessionsResponseTypeDef = TypedDict(
     "ListSessionsResponseTypeDef",
     {
         "NextToken": str,
         "Sessions": List[SessionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueryRuntimeStatisticsOutputTypeDef = TypedDict(
     "GetQueryRuntimeStatisticsOutputTypeDef",
     {
         "QueryRuntimeStatistics": QueryRuntimeStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryExecutionTypeDef = TypedDict(
     "QueryExecutionTypeDef",
     {
         "QueryExecutionId": str,
@@ -2177,14 +2364,15 @@
         "ResultReuseConfiguration": ResultReuseConfigurationTypeDef,
         "QueryExecutionContext": QueryExecutionContextTypeDef,
         "Status": QueryExecutionStatusTypeDef,
         "Statistics": QueryExecutionStatisticsTypeDef,
         "WorkGroup": str,
         "EngineVersion": EngineVersionTypeDef,
         "ExecutionParameters": List[str],
+        "SubstatementType": str,
     },
     total=False,
 )
 
 _RequiredStartQueryExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStartQueryExecutionInputRequestTypeDef",
     {
@@ -2213,15 +2401,15 @@
 
 GetQueryResultsOutputTypeDef = TypedDict(
     "GetQueryResultsOutputTypeDef",
     {
         "UpdateCount": int,
         "ResultSet": ResultSetTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateWorkGroupInputRequestTypeDef",
     {
         "Name": str,
@@ -2290,26 +2478,26 @@
 
 
 BatchGetQueryExecutionOutputTypeDef = TypedDict(
     "BatchGetQueryExecutionOutputTypeDef",
     {
         "QueryExecutions": List[QueryExecutionTypeDef],
         "UnprocessedQueryExecutionIds": List[UnprocessedQueryExecutionIdTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueryExecutionOutputTypeDef = TypedDict(
     "GetQueryExecutionOutputTypeDef",
     {
         "QueryExecution": QueryExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkGroupOutputTypeDef = TypedDict(
     "GetWorkGroupOutputTypeDef",
     {
         "WorkGroup": WorkGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena/type_defs.pyi` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -13,14 +13,16 @@
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
     CalculationExecutionStateType,
+    CapacityAllocationStatusType,
+    CapacityReservationStatusType,
     ColumnNullableType,
     DataCatalogTypeType,
     EncryptionOptionType,
     ExecutorStateType,
     ExecutorTypeType,
     QueryExecutionStateType,
     SessionStateType,
@@ -39,124 +41,143 @@
 
 __all__ = (
     "AclConfigurationTypeDef",
     "ApplicationDPUSizesTypeDef",
     "AthenaErrorTypeDef",
     "BatchGetNamedQueryInputRequestTypeDef",
     "NamedQueryTypeDef",
-    "ResponseMetadataTypeDef",
     "UnprocessedNamedQueryIdTypeDef",
     "BatchGetPreparedStatementInputRequestTypeDef",
     "PreparedStatementTypeDef",
     "UnprocessedPreparedStatementNameTypeDef",
     "BatchGetQueryExecutionInputRequestTypeDef",
     "UnprocessedQueryExecutionIdTypeDef",
     "CalculationConfigurationTypeDef",
     "CalculationResultTypeDef",
     "CalculationStatisticsTypeDef",
     "CalculationStatusTypeDef",
+    "CancelCapacityReservationInputRequestTypeDef",
+    "CapacityAllocationTypeDef",
+    "CapacityAssignmentTypeDef",
     "ColumnInfoTypeDef",
     "ColumnTypeDef",
     "TagTypeDef",
     "CreateNamedQueryInputRequestTypeDef",
+    "CreateNamedQueryOutputTypeDef",
     "CreateNotebookInputRequestTypeDef",
+    "CreateNotebookOutputTypeDef",
     "CreatePreparedStatementInputRequestTypeDef",
     "CreatePresignedNotebookUrlRequestRequestTypeDef",
+    "CreatePresignedNotebookUrlResponseTypeDef",
     "CustomerContentEncryptionConfigurationTypeDef",
     "DataCatalogSummaryTypeDef",
     "DataCatalogTypeDef",
     "DatabaseTypeDef",
     "DatumTypeDef",
+    "DeleteCapacityReservationInputRequestTypeDef",
     "DeleteDataCatalogInputRequestTypeDef",
     "DeleteNamedQueryInputRequestTypeDef",
     "DeleteNotebookInputRequestTypeDef",
     "DeletePreparedStatementInputRequestTypeDef",
     "DeleteWorkGroupInputRequestTypeDef",
     "EncryptionConfigurationTypeDef",
     "EngineConfigurationTypeDef",
     "EngineVersionTypeDef",
     "ExecutorsSummaryTypeDef",
     "ExportNotebookInputRequestTypeDef",
     "NotebookMetadataTypeDef",
     "FilterDefinitionTypeDef",
     "GetCalculationExecutionCodeRequestRequestTypeDef",
+    "GetCalculationExecutionCodeResponseTypeDef",
     "GetCalculationExecutionRequestRequestTypeDef",
     "GetCalculationExecutionStatusRequestRequestTypeDef",
+    "GetCapacityAssignmentConfigurationInputRequestTypeDef",
+    "GetCapacityReservationInputRequestTypeDef",
     "GetDataCatalogInputRequestTypeDef",
     "GetDatabaseInputRequestTypeDef",
     "GetNamedQueryInputRequestTypeDef",
     "GetNotebookMetadataInputRequestTypeDef",
     "GetPreparedStatementInputRequestTypeDef",
     "GetQueryExecutionInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetQueryResultsInputGetQueryResultsPaginateTypeDef",
     "GetQueryResultsInputRequestTypeDef",
     "GetQueryRuntimeStatisticsInputRequestTypeDef",
     "GetSessionRequestRequestTypeDef",
     "SessionStatisticsTypeDef",
     "SessionStatusTypeDef",
     "GetSessionStatusRequestRequestTypeDef",
     "GetTableMetadataInputRequestTypeDef",
     "GetWorkGroupInputRequestTypeDef",
     "ImportNotebookInputRequestTypeDef",
+    "ImportNotebookOutputTypeDef",
     "ListApplicationDPUSizesInputRequestTypeDef",
     "ListCalculationExecutionsRequestRequestTypeDef",
+    "ListCapacityReservationsInputRequestTypeDef",
+    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
     "ListDataCatalogsInputRequestTypeDef",
+    "ListDatabasesInputListDatabasesPaginateTypeDef",
     "ListDatabasesInputRequestTypeDef",
     "ListEngineVersionsInputRequestTypeDef",
     "ListExecutorsRequestRequestTypeDef",
+    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
     "ListNamedQueriesInputRequestTypeDef",
+    "ListNamedQueriesOutputTypeDef",
     "ListNotebookSessionsRequestRequestTypeDef",
     "NotebookSessionSummaryTypeDef",
     "ListPreparedStatementsInputRequestTypeDef",
     "PreparedStatementSummaryTypeDef",
+    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
     "ListQueryExecutionsInputRequestTypeDef",
+    "ListQueryExecutionsOutputTypeDef",
     "ListSessionsRequestRequestTypeDef",
+    "ListTableMetadataInputListTableMetadataPaginateTypeDef",
     "ListTableMetadataInputRequestTypeDef",
+    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "ListWorkGroupsInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "QueryExecutionContextTypeDef",
     "ResultReuseInformationTypeDef",
     "QueryRuntimeStatisticsRowsTypeDef",
     "QueryRuntimeStatisticsTimelineTypeDef",
     "QueryStagePlanNodeTypeDef",
     "QueryStageTypeDef",
+    "ResponseMetadataTypeDef",
     "ResultReuseByAgeConfigurationTypeDef",
+    "StartCalculationExecutionResponseTypeDef",
+    "StartQueryExecutionOutputTypeDef",
+    "StartSessionResponseTypeDef",
     "StopCalculationExecutionRequestRequestTypeDef",
+    "StopCalculationExecutionResponseTypeDef",
     "StopQueryExecutionInputRequestTypeDef",
     "TerminateSessionRequestRequestTypeDef",
+    "TerminateSessionResponseTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "UpdateCapacityReservationInputRequestTypeDef",
     "UpdateDataCatalogInputRequestTypeDef",
     "UpdateNamedQueryInputRequestTypeDef",
     "UpdateNotebookInputRequestTypeDef",
     "UpdateNotebookMetadataInputRequestTypeDef",
     "UpdatePreparedStatementInputRequestTypeDef",
+    "ListApplicationDPUSizesOutputTypeDef",
     "QueryExecutionStatusTypeDef",
-    "CreateNamedQueryOutputTypeDef",
-    "CreateNotebookOutputTypeDef",
-    "CreatePresignedNotebookUrlResponseTypeDef",
-    "GetCalculationExecutionCodeResponseTypeDef",
     "GetNamedQueryOutputTypeDef",
-    "ImportNotebookOutputTypeDef",
-    "ListApplicationDPUSizesOutputTypeDef",
-    "ListNamedQueriesOutputTypeDef",
-    "ListQueryExecutionsOutputTypeDef",
-    "StartCalculationExecutionResponseTypeDef",
-    "StartQueryExecutionOutputTypeDef",
-    "StartSessionResponseTypeDef",
-    "StopCalculationExecutionResponseTypeDef",
-    "TerminateSessionResponseTypeDef",
     "BatchGetNamedQueryOutputTypeDef",
     "GetPreparedStatementOutputTypeDef",
     "BatchGetPreparedStatementOutputTypeDef",
     "StartCalculationExecutionRequestRequestTypeDef",
     "CalculationSummaryTypeDef",
     "GetCalculationExecutionResponseTypeDef",
     "GetCalculationExecutionStatusResponseTypeDef",
+    "CapacityReservationTypeDef",
+    "CapacityAssignmentConfigurationTypeDef",
+    "PutCapacityAssignmentConfigurationInputRequestTypeDef",
     "ResultSetMetadataTypeDef",
     "TableMetadataTypeDef",
+    "CreateCapacityReservationInputRequestTypeDef",
     "CreateDataCatalogInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
     "TagResourceInputRequestTypeDef",
     "ListDataCatalogsOutputTypeDef",
     "GetDataCatalogOutputTypeDef",
     "GetDatabaseOutputTypeDef",
     "ListDatabasesOutputTypeDef",
@@ -168,29 +189,25 @@
     "ListEngineVersionsOutputTypeDef",
     "WorkGroupSummaryTypeDef",
     "ListExecutorsResponseTypeDef",
     "ExportNotebookOutputTypeDef",
     "GetNotebookMetadataOutputTypeDef",
     "ListNotebookMetadataOutputTypeDef",
     "ListNotebookMetadataInputRequestTypeDef",
-    "GetQueryResultsInputGetQueryResultsPaginateTypeDef",
-    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
-    "ListDatabasesInputListDatabasesPaginateTypeDef",
-    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
-    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
-    "ListTableMetadataInputListTableMetadataPaginateTypeDef",
-    "ListTagsForResourceInputListTagsForResourcePaginateTypeDef",
     "GetSessionStatusResponseTypeDef",
     "SessionSummaryTypeDef",
     "ListNotebookSessionsResponseTypeDef",
     "ListPreparedStatementsOutputTypeDef",
     "QueryExecutionStatisticsTypeDef",
     "QueryRuntimeStatisticsTypeDef",
     "ResultReuseConfigurationTypeDef",
     "ListCalculationExecutionsResponseTypeDef",
+    "GetCapacityReservationOutputTypeDef",
+    "ListCapacityReservationsOutputTypeDef",
+    "GetCapacityAssignmentConfigurationOutputTypeDef",
     "GetTableMetadataOutputTypeDef",
     "ListTableMetadataOutputTypeDef",
     "ResultSetTypeDef",
     "WorkGroupConfigurationTypeDef",
     "WorkGroupConfigurationUpdatesTypeDef",
     "GetSessionResponseTypeDef",
     "ListWorkGroupsOutputTypeDef",
@@ -258,25 +275,14 @@
     },
     total=False,
 )
 
 class NamedQueryTypeDef(_RequiredNamedQueryTypeDef, _OptionalNamedQueryTypeDef):
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
 UnprocessedNamedQueryIdTypeDef = TypedDict(
     "UnprocessedNamedQueryIdTypeDef",
     {
         "NamedQueryId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
@@ -365,14 +371,50 @@
         "CompletionDateTime": datetime,
         "State": CalculationExecutionStateType,
         "StateChangeReason": str,
     },
     total=False,
 )
 
+CancelCapacityReservationInputRequestTypeDef = TypedDict(
+    "CancelCapacityReservationInputRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+
+_RequiredCapacityAllocationTypeDef = TypedDict(
+    "_RequiredCapacityAllocationTypeDef",
+    {
+        "Status": CapacityAllocationStatusType,
+        "RequestTime": datetime,
+    },
+)
+_OptionalCapacityAllocationTypeDef = TypedDict(
+    "_OptionalCapacityAllocationTypeDef",
+    {
+        "StatusMessage": str,
+        "RequestCompletionTime": datetime,
+    },
+    total=False,
+)
+
+class CapacityAllocationTypeDef(
+    _RequiredCapacityAllocationTypeDef, _OptionalCapacityAllocationTypeDef
+):
+    pass
+
+CapacityAssignmentTypeDef = TypedDict(
+    "CapacityAssignmentTypeDef",
+    {
+        "WorkGroupNames": List[str],
+    },
+    total=False,
+)
+
 _RequiredColumnInfoTypeDef = TypedDict(
     "_RequiredColumnInfoTypeDef",
     {
         "Name": str,
         "Type": str,
     },
 )
@@ -440,14 +482,22 @@
 )
 
 class CreateNamedQueryInputRequestTypeDef(
     _RequiredCreateNamedQueryInputRequestTypeDef, _OptionalCreateNamedQueryInputRequestTypeDef
 ):
     pass
 
+CreateNamedQueryOutputTypeDef = TypedDict(
+    "CreateNamedQueryOutputTypeDef",
+    {
+        "NamedQueryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateNotebookInputRequestTypeDef = TypedDict(
     "_RequiredCreateNotebookInputRequestTypeDef",
     {
         "WorkGroup": str,
         "Name": str,
     },
 )
@@ -460,14 +510,22 @@
 )
 
 class CreateNotebookInputRequestTypeDef(
     _RequiredCreateNotebookInputRequestTypeDef, _OptionalCreateNotebookInputRequestTypeDef
 ):
     pass
 
+CreateNotebookOutputTypeDef = TypedDict(
+    "CreateNotebookOutputTypeDef",
+    {
+        "NotebookId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePreparedStatementInputRequestTypeDef = TypedDict(
     "_RequiredCreatePreparedStatementInputRequestTypeDef",
     {
         "StatementName": str,
         "WorkGroup": str,
         "QueryStatement": str,
     },
@@ -489,14 +547,24 @@
 CreatePresignedNotebookUrlRequestRequestTypeDef = TypedDict(
     "CreatePresignedNotebookUrlRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+CreatePresignedNotebookUrlResponseTypeDef = TypedDict(
+    "CreatePresignedNotebookUrlResponseTypeDef",
+    {
+        "NotebookUrl": str,
+        "AuthToken": str,
+        "AuthTokenExpirationTime": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomerContentEncryptionConfigurationTypeDef = TypedDict(
     "CustomerContentEncryptionConfigurationTypeDef",
     {
         "KmsKey": str,
     },
 )
 
@@ -550,14 +618,21 @@
     "DatumTypeDef",
     {
         "VarCharValue": str,
     },
     total=False,
 )
 
+DeleteCapacityReservationInputRequestTypeDef = TypedDict(
+    "DeleteCapacityReservationInputRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+
 DeleteDataCatalogInputRequestTypeDef = TypedDict(
     "DeleteDataCatalogInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -629,14 +704,15 @@
 )
 _OptionalEngineConfigurationTypeDef = TypedDict(
     "_OptionalEngineConfigurationTypeDef",
     {
         "CoordinatorDpuSize": int,
         "DefaultExecutorDpuSize": int,
         "AdditionalConfigs": Dict[str, str],
+        "SparkProperties": Dict[str, str],
     },
     total=False,
 )
 
 class EngineConfigurationTypeDef(
     _RequiredEngineConfigurationTypeDef, _OptionalEngineConfigurationTypeDef
 ):
@@ -703,28 +779,50 @@
 GetCalculationExecutionCodeRequestRequestTypeDef = TypedDict(
     "GetCalculationExecutionCodeRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
+GetCalculationExecutionCodeResponseTypeDef = TypedDict(
+    "GetCalculationExecutionCodeResponseTypeDef",
+    {
+        "CodeBlock": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCalculationExecutionRequestRequestTypeDef = TypedDict(
     "GetCalculationExecutionRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
 GetCalculationExecutionStatusRequestRequestTypeDef = TypedDict(
     "GetCalculationExecutionStatusRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
+GetCapacityAssignmentConfigurationInputRequestTypeDef = TypedDict(
+    "GetCapacityAssignmentConfigurationInputRequestTypeDef",
+    {
+        "CapacityReservationName": str,
+    },
+)
+
+GetCapacityReservationInputRequestTypeDef = TypedDict(
+    "GetCapacityReservationInputRequestTypeDef",
+    {
+        "Name": str,
+    },
+)
+
 GetDataCatalogInputRequestTypeDef = TypedDict(
     "GetDataCatalogInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -761,24 +859,34 @@
 GetQueryExecutionInputRequestTypeDef = TypedDict(
     "GetQueryExecutionInputRequestTypeDef",
     {
         "QueryExecutionId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
+    "_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "QueryExecutionId": str,
+    },
+)
+_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
+    "_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetQueryResultsInputGetQueryResultsPaginateTypeDef(
+    _RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef,
+    _OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetQueryResultsInputRequestTypeDef = TypedDict(
     "_RequiredGetQueryResultsInputRequestTypeDef",
     {
         "QueryExecutionId": str,
     },
 )
 _OptionalGetQueryResultsInputRequestTypeDef = TypedDict(
@@ -871,14 +979,22 @@
 )
 
 class ImportNotebookInputRequestTypeDef(
     _RequiredImportNotebookInputRequestTypeDef, _OptionalImportNotebookInputRequestTypeDef
 ):
     pass
 
+ImportNotebookOutputTypeDef = TypedDict(
+    "ImportNotebookOutputTypeDef",
+    {
+        "NotebookId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListApplicationDPUSizesInputRequestTypeDef = TypedDict(
     "ListApplicationDPUSizesInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -902,23 +1018,60 @@
 
 class ListCalculationExecutionsRequestRequestTypeDef(
     _RequiredListCalculationExecutionsRequestRequestTypeDef,
     _OptionalListCalculationExecutionsRequestRequestTypeDef,
 ):
     pass
 
+ListCapacityReservationsInputRequestTypeDef = TypedDict(
+    "ListCapacityReservationsInputRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListDataCatalogsInputListDataCatalogsPaginateTypeDef = TypedDict(
+    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDataCatalogsInputRequestTypeDef = TypedDict(
     "ListDataCatalogsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
+    "_RequiredListDatabasesInputListDatabasesPaginateTypeDef",
+    {
+        "CatalogName": str,
+    },
+)
+_OptionalListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
+    "_OptionalListDatabasesInputListDatabasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDatabasesInputListDatabasesPaginateTypeDef(
+    _RequiredListDatabasesInputListDatabasesPaginateTypeDef,
+    _OptionalListDatabasesInputListDatabasesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDatabasesInputRequestTypeDef = TypedDict(
     "_RequiredListDatabasesInputRequestTypeDef",
     {
         "CatalogName": str,
     },
 )
 _OptionalListDatabasesInputRequestTypeDef = TypedDict(
@@ -961,24 +1114,42 @@
 )
 
 class ListExecutorsRequestRequestTypeDef(
     _RequiredListExecutorsRequestRequestTypeDef, _OptionalListExecutorsRequestRequestTypeDef
 ):
     pass
 
+ListNamedQueriesInputListNamedQueriesPaginateTypeDef = TypedDict(
+    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
+    {
+        "WorkGroup": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListNamedQueriesInputRequestTypeDef = TypedDict(
     "ListNamedQueriesInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "WorkGroup": str,
     },
     total=False,
 )
 
+ListNamedQueriesOutputTypeDef = TypedDict(
+    "ListNamedQueriesOutputTypeDef",
+    {
+        "NamedQueryIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListNotebookSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListNotebookSessionsRequestRequestTypeDef",
     {
         "NotebookId": str,
     },
 )
 _OptionalListNotebookSessionsRequestRequestTypeDef = TypedDict(
@@ -1031,24 +1202,42 @@
     {
         "StatementName": str,
         "LastModifiedTime": datetime,
     },
     total=False,
 )
 
+ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef = TypedDict(
+    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
+    {
+        "WorkGroup": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQueryExecutionsInputRequestTypeDef = TypedDict(
     "ListQueryExecutionsInputRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "WorkGroup": str,
     },
     total=False,
 )
 
+ListQueryExecutionsOutputTypeDef = TypedDict(
+    "ListQueryExecutionsOutputTypeDef",
+    {
+        "QueryExecutionIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListSessionsRequestRequestTypeDef",
     {
         "WorkGroup": str,
     },
 )
 _OptionalListSessionsRequestRequestTypeDef = TypedDict(
@@ -1062,14 +1251,36 @@
 )
 
 class ListSessionsRequestRequestTypeDef(
     _RequiredListSessionsRequestRequestTypeDef, _OptionalListSessionsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
+    "_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef",
+    {
+        "CatalogName": str,
+        "DatabaseName": str,
+    },
+)
+_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
+    "_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef",
+    {
+        "Expression": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTableMetadataInputListTableMetadataPaginateTypeDef(
+    _RequiredListTableMetadataInputListTableMetadataPaginateTypeDef,
+    _OptionalListTableMetadataInputListTableMetadataPaginateTypeDef,
+):
+    pass
+
 _RequiredListTableMetadataInputRequestTypeDef = TypedDict(
     "_RequiredListTableMetadataInputRequestTypeDef",
     {
         "CatalogName": str,
         "DatabaseName": str,
     },
 )
@@ -1084,14 +1295,34 @@
 )
 
 class ListTableMetadataInputRequestTypeDef(
     _RequiredListTableMetadataInputRequestTypeDef, _OptionalListTableMetadataInputRequestTypeDef
 ):
     pass
 
+_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -1113,14 +1344,24 @@
     {
         "NextToken": str,
         "MaxResults": int,
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
 QueryExecutionContextTypeDef = TypedDict(
     "QueryExecutionContextTypeDef",
     {
         "Database": str,
         "Catalog": str,
     },
     total=False,
@@ -1179,14 +1420,25 @@
         "ExecutionTime": int,
         "QueryStagePlan": "QueryStagePlanNodeTypeDef",
         "SubStages": List[Dict[str, Any]],
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
 _RequiredResultReuseByAgeConfigurationTypeDef = TypedDict(
     "_RequiredResultReuseByAgeConfigurationTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalResultReuseByAgeConfigurationTypeDef = TypedDict(
@@ -1198,43 +1450,93 @@
 )
 
 class ResultReuseByAgeConfigurationTypeDef(
     _RequiredResultReuseByAgeConfigurationTypeDef, _OptionalResultReuseByAgeConfigurationTypeDef
 ):
     pass
 
+StartCalculationExecutionResponseTypeDef = TypedDict(
+    "StartCalculationExecutionResponseTypeDef",
+    {
+        "CalculationExecutionId": str,
+        "State": CalculationExecutionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartQueryExecutionOutputTypeDef = TypedDict(
+    "StartQueryExecutionOutputTypeDef",
+    {
+        "QueryExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSessionResponseTypeDef = TypedDict(
+    "StartSessionResponseTypeDef",
+    {
+        "SessionId": str,
+        "State": SessionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopCalculationExecutionRequestRequestTypeDef = TypedDict(
     "StopCalculationExecutionRequestRequestTypeDef",
     {
         "CalculationExecutionId": str,
     },
 )
 
+StopCalculationExecutionResponseTypeDef = TypedDict(
+    "StopCalculationExecutionResponseTypeDef",
+    {
+        "State": CalculationExecutionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopQueryExecutionInputRequestTypeDef = TypedDict(
     "StopQueryExecutionInputRequestTypeDef",
     {
         "QueryExecutionId": str,
     },
 )
 
 TerminateSessionRequestRequestTypeDef = TypedDict(
     "TerminateSessionRequestRequestTypeDef",
     {
         "SessionId": str,
     },
 )
 
+TerminateSessionResponseTypeDef = TypedDict(
+    "TerminateSessionResponseTypeDef",
+    {
+        "State": SessionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateCapacityReservationInputRequestTypeDef = TypedDict(
+    "UpdateCapacityReservationInputRequestTypeDef",
+    {
+        "TargetDpus": int,
+        "Name": str,
+    },
+)
+
 _RequiredUpdateDataCatalogInputRequestTypeDef = TypedDict(
     "_RequiredUpdateDataCatalogInputRequestTypeDef",
     {
         "Name": str,
         "Type": DataCatalogTypeType,
     },
 )
@@ -1334,168 +1636,66 @@
 
 class UpdatePreparedStatementInputRequestTypeDef(
     _RequiredUpdatePreparedStatementInputRequestTypeDef,
     _OptionalUpdatePreparedStatementInputRequestTypeDef,
 ):
     pass
 
+ListApplicationDPUSizesOutputTypeDef = TypedDict(
+    "ListApplicationDPUSizesOutputTypeDef",
+    {
+        "ApplicationDPUSizes": List[ApplicationDPUSizesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 QueryExecutionStatusTypeDef = TypedDict(
     "QueryExecutionStatusTypeDef",
     {
         "State": QueryExecutionStateType,
         "StateChangeReason": str,
         "SubmissionDateTime": datetime,
         "CompletionDateTime": datetime,
         "AthenaError": AthenaErrorTypeDef,
     },
     total=False,
 )
 
-CreateNamedQueryOutputTypeDef = TypedDict(
-    "CreateNamedQueryOutputTypeDef",
-    {
-        "NamedQueryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNotebookOutputTypeDef = TypedDict(
-    "CreateNotebookOutputTypeDef",
-    {
-        "NotebookId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePresignedNotebookUrlResponseTypeDef = TypedDict(
-    "CreatePresignedNotebookUrlResponseTypeDef",
-    {
-        "NotebookUrl": str,
-        "AuthToken": str,
-        "AuthTokenExpirationTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCalculationExecutionCodeResponseTypeDef = TypedDict(
-    "GetCalculationExecutionCodeResponseTypeDef",
-    {
-        "CodeBlock": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetNamedQueryOutputTypeDef = TypedDict(
     "GetNamedQueryOutputTypeDef",
     {
         "NamedQuery": NamedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportNotebookOutputTypeDef = TypedDict(
-    "ImportNotebookOutputTypeDef",
-    {
-        "NotebookId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationDPUSizesOutputTypeDef = TypedDict(
-    "ListApplicationDPUSizesOutputTypeDef",
-    {
-        "ApplicationDPUSizes": List[ApplicationDPUSizesTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListNamedQueriesOutputTypeDef = TypedDict(
-    "ListNamedQueriesOutputTypeDef",
-    {
-        "NamedQueryIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListQueryExecutionsOutputTypeDef = TypedDict(
-    "ListQueryExecutionsOutputTypeDef",
-    {
-        "QueryExecutionIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartCalculationExecutionResponseTypeDef = TypedDict(
-    "StartCalculationExecutionResponseTypeDef",
-    {
-        "CalculationExecutionId": str,
-        "State": CalculationExecutionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartQueryExecutionOutputTypeDef = TypedDict(
-    "StartQueryExecutionOutputTypeDef",
-    {
-        "QueryExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSessionResponseTypeDef = TypedDict(
-    "StartSessionResponseTypeDef",
-    {
-        "SessionId": str,
-        "State": SessionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopCalculationExecutionResponseTypeDef = TypedDict(
-    "StopCalculationExecutionResponseTypeDef",
-    {
-        "State": CalculationExecutionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TerminateSessionResponseTypeDef = TypedDict(
-    "TerminateSessionResponseTypeDef",
-    {
-        "State": SessionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetNamedQueryOutputTypeDef = TypedDict(
     "BatchGetNamedQueryOutputTypeDef",
     {
         "NamedQueries": List[NamedQueryTypeDef],
         "UnprocessedNamedQueryIds": List[UnprocessedNamedQueryIdTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPreparedStatementOutputTypeDef = TypedDict(
     "GetPreparedStatementOutputTypeDef",
     {
         "PreparedStatement": PreparedStatementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetPreparedStatementOutputTypeDef = TypedDict(
     "BatchGetPreparedStatementOutputTypeDef",
     {
         "PreparedStatements": List[PreparedStatementTypeDef],
         "UnprocessedPreparedStatementNames": List[UnprocessedPreparedStatementNameTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartCalculationExecutionRequestRequestTypeDef = TypedDict(
     "_RequiredStartCalculationExecutionRequestRequestTypeDef",
     {
         "SessionId": str,
@@ -1534,24 +1734,65 @@
         "CalculationExecutionId": str,
         "SessionId": str,
         "Description": str,
         "WorkingDirectory": str,
         "Status": CalculationStatusTypeDef,
         "Statistics": CalculationStatisticsTypeDef,
         "Result": CalculationResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCalculationExecutionStatusResponseTypeDef = TypedDict(
     "GetCalculationExecutionStatusResponseTypeDef",
     {
         "Status": CalculationStatusTypeDef,
         "Statistics": CalculationStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCapacityReservationTypeDef = TypedDict(
+    "_RequiredCapacityReservationTypeDef",
+    {
+        "Name": str,
+        "Status": CapacityReservationStatusType,
+        "TargetDpus": int,
+        "AllocatedDpus": int,
+        "CreationTime": datetime,
+    },
+)
+_OptionalCapacityReservationTypeDef = TypedDict(
+    "_OptionalCapacityReservationTypeDef",
+    {
+        "LastAllocation": CapacityAllocationTypeDef,
+        "LastSuccessfulAllocationTime": datetime,
+    },
+    total=False,
+)
+
+class CapacityReservationTypeDef(
+    _RequiredCapacityReservationTypeDef, _OptionalCapacityReservationTypeDef
+):
+    pass
+
+CapacityAssignmentConfigurationTypeDef = TypedDict(
+    "CapacityAssignmentConfigurationTypeDef",
+    {
+        "CapacityReservationName": str,
+        "CapacityAssignments": List[CapacityAssignmentTypeDef],
+    },
+    total=False,
+)
+
+PutCapacityAssignmentConfigurationInputRequestTypeDef = TypedDict(
+    "PutCapacityAssignmentConfigurationInputRequestTypeDef",
+    {
+        "CapacityReservationName": str,
+        "CapacityAssignments": Sequence[CapacityAssignmentTypeDef],
     },
 )
 
 ResultSetMetadataTypeDef = TypedDict(
     "ResultSetMetadataTypeDef",
     {
         "ColumnInfo": List[ColumnInfoTypeDef],
@@ -1577,14 +1818,35 @@
     },
     total=False,
 )
 
 class TableMetadataTypeDef(_RequiredTableMetadataTypeDef, _OptionalTableMetadataTypeDef):
     pass
 
+_RequiredCreateCapacityReservationInputRequestTypeDef = TypedDict(
+    "_RequiredCreateCapacityReservationInputRequestTypeDef",
+    {
+        "TargetDpus": int,
+        "Name": str,
+    },
+)
+_OptionalCreateCapacityReservationInputRequestTypeDef = TypedDict(
+    "_OptionalCreateCapacityReservationInputRequestTypeDef",
+    {
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreateCapacityReservationInputRequestTypeDef(
+    _RequiredCreateCapacityReservationInputRequestTypeDef,
+    _OptionalCreateCapacityReservationInputRequestTypeDef,
+):
+    pass
+
 _RequiredCreateDataCatalogInputRequestTypeDef = TypedDict(
     "_RequiredCreateDataCatalogInputRequestTypeDef",
     {
         "Name": str,
         "Type": DataCatalogTypeType,
     },
 )
@@ -1604,15 +1866,15 @@
     pass
 
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceARN": str,
@@ -1621,40 +1883,40 @@
 )
 
 ListDataCatalogsOutputTypeDef = TypedDict(
     "ListDataCatalogsOutputTypeDef",
     {
         "DataCatalogsSummary": List[DataCatalogSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataCatalogOutputTypeDef = TypedDict(
     "GetDataCatalogOutputTypeDef",
     {
         "DataCatalog": DataCatalogTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDatabaseOutputTypeDef = TypedDict(
     "GetDatabaseOutputTypeDef",
     {
         "Database": DatabaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatabasesOutputTypeDef = TypedDict(
     "ListDatabasesOutputTypeDef",
     {
         "DatabaseList": List[DatabaseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RowTypeDef = TypedDict(
     "RowTypeDef",
     {
         "Data": List[DatumTypeDef],
@@ -1723,15 +1985,15 @@
     pass
 
 ListEngineVersionsOutputTypeDef = TypedDict(
     "ListEngineVersionsOutputTypeDef",
     {
         "EngineVersions": List[EngineVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkGroupSummaryTypeDef = TypedDict(
     "WorkGroupSummaryTypeDef",
     {
         "Name": str,
@@ -1745,41 +2007,41 @@
 
 ListExecutorsResponseTypeDef = TypedDict(
     "ListExecutorsResponseTypeDef",
     {
         "SessionId": str,
         "NextToken": str,
         "ExecutorsSummary": List[ExecutorsSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportNotebookOutputTypeDef = TypedDict(
     "ExportNotebookOutputTypeDef",
     {
         "NotebookMetadata": NotebookMetadataTypeDef,
         "Payload": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNotebookMetadataOutputTypeDef = TypedDict(
     "GetNotebookMetadataOutputTypeDef",
     {
         "NotebookMetadata": NotebookMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNotebookMetadataOutputTypeDef = TypedDict(
     "ListNotebookMetadataOutputTypeDef",
     {
         "NextToken": str,
         "NotebookMetadataList": List[NotebookMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListNotebookMetadataInputRequestTypeDef = TypedDict(
     "_RequiredListNotebookMetadataInputRequestTypeDef",
     {
         "WorkGroup": str,
@@ -1797,128 +2059,20 @@
 
 class ListNotebookMetadataInputRequestTypeDef(
     _RequiredListNotebookMetadataInputRequestTypeDef,
     _OptionalListNotebookMetadataInputRequestTypeDef,
 ):
     pass
 
-_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
-    "_RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef",
-    {
-        "QueryExecutionId": str,
-    },
-)
-_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef = TypedDict(
-    "_OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetQueryResultsInputGetQueryResultsPaginateTypeDef(
-    _RequiredGetQueryResultsInputGetQueryResultsPaginateTypeDef,
-    _OptionalGetQueryResultsInputGetQueryResultsPaginateTypeDef,
-):
-    pass
-
-ListDataCatalogsInputListDataCatalogsPaginateTypeDef = TypedDict(
-    "ListDataCatalogsInputListDataCatalogsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
-    "_RequiredListDatabasesInputListDatabasesPaginateTypeDef",
-    {
-        "CatalogName": str,
-    },
-)
-_OptionalListDatabasesInputListDatabasesPaginateTypeDef = TypedDict(
-    "_OptionalListDatabasesInputListDatabasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDatabasesInputListDatabasesPaginateTypeDef(
-    _RequiredListDatabasesInputListDatabasesPaginateTypeDef,
-    _OptionalListDatabasesInputListDatabasesPaginateTypeDef,
-):
-    pass
-
-ListNamedQueriesInputListNamedQueriesPaginateTypeDef = TypedDict(
-    "ListNamedQueriesInputListNamedQueriesPaginateTypeDef",
-    {
-        "WorkGroup": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef = TypedDict(
-    "ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef",
-    {
-        "WorkGroup": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
-    "_RequiredListTableMetadataInputListTableMetadataPaginateTypeDef",
-    {
-        "CatalogName": str,
-        "DatabaseName": str,
-    },
-)
-_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef = TypedDict(
-    "_OptionalListTableMetadataInputListTableMetadataPaginateTypeDef",
-    {
-        "Expression": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTableMetadataInputListTableMetadataPaginateTypeDef(
-    _RequiredListTableMetadataInputListTableMetadataPaginateTypeDef,
-    _OptionalListTableMetadataInputListTableMetadataPaginateTypeDef,
-):
-    pass
-
-_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceARN": str,
-    },
-)
-_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceInputListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceInputListTagsForResourcePaginateTypeDef,
-):
-    pass
-
 GetSessionStatusResponseTypeDef = TypedDict(
     "GetSessionStatusResponseTypeDef",
     {
         "SessionId": str,
         "Status": SessionStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SessionSummaryTypeDef = TypedDict(
     "SessionSummaryTypeDef",
     {
         "SessionId": str,
@@ -1931,24 +2085,24 @@
 )
 
 ListNotebookSessionsResponseTypeDef = TypedDict(
     "ListNotebookSessionsResponseTypeDef",
     {
         "NotebookSessionsList": List[NotebookSessionSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPreparedStatementsOutputTypeDef = TypedDict(
     "ListPreparedStatementsOutputTypeDef",
     {
         "PreparedStatements": List[PreparedStatementSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryExecutionStatisticsTypeDef = TypedDict(
     "QueryExecutionStatisticsTypeDef",
     {
         "EngineExecutionTimeInMillis": int,
@@ -1982,32 +2136,57 @@
 )
 
 ListCalculationExecutionsResponseTypeDef = TypedDict(
     "ListCalculationExecutionsResponseTypeDef",
     {
         "NextToken": str,
         "Calculations": List[CalculationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCapacityReservationOutputTypeDef = TypedDict(
+    "GetCapacityReservationOutputTypeDef",
+    {
+        "CapacityReservation": CapacityReservationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCapacityReservationsOutputTypeDef = TypedDict(
+    "ListCapacityReservationsOutputTypeDef",
+    {
+        "NextToken": str,
+        "CapacityReservations": List[CapacityReservationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCapacityAssignmentConfigurationOutputTypeDef = TypedDict(
+    "GetCapacityAssignmentConfigurationOutputTypeDef",
+    {
+        "CapacityAssignmentConfiguration": CapacityAssignmentConfigurationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableMetadataOutputTypeDef = TypedDict(
     "GetTableMetadataOutputTypeDef",
     {
         "TableMetadata": TableMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTableMetadataOutputTypeDef = TypedDict(
     "ListTableMetadataOutputTypeDef",
     {
         "TableMetadataList": List[TableMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResultSetTypeDef = TypedDict(
     "ResultSetTypeDef",
     {
         "Rows": List[RowTypeDef],
@@ -2024,14 +2203,15 @@
         "PublishCloudWatchMetricsEnabled": bool,
         "BytesScannedCutoffPerQuery": int,
         "RequesterPaysEnabled": bool,
         "EngineVersion": EngineVersionTypeDef,
         "AdditionalConfiguration": str,
         "ExecutionRole": str,
         "CustomerContentEncryptionConfiguration": CustomerContentEncryptionConfigurationTypeDef,
+        "EnableMinimumEncryptionConfiguration": bool,
     },
     total=False,
 )
 
 WorkGroupConfigurationUpdatesTypeDef = TypedDict(
     "WorkGroupConfigurationUpdatesTypeDef",
     {
@@ -2042,14 +2222,15 @@
         "RemoveBytesScannedCutoffPerQuery": bool,
         "RequesterPaysEnabled": bool,
         "EngineVersion": EngineVersionTypeDef,
         "RemoveCustomerContentEncryptionConfiguration": bool,
         "AdditionalConfiguration": str,
         "ExecutionRole": str,
         "CustomerContentEncryptionConfiguration": CustomerContentEncryptionConfigurationTypeDef,
+        "EnableMinimumEncryptionConfiguration": bool,
     },
     total=False,
 )
 
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
@@ -2058,41 +2239,41 @@
         "WorkGroup": str,
         "EngineVersion": str,
         "EngineConfiguration": EngineConfigurationTypeDef,
         "NotebookVersion": str,
         "SessionConfiguration": SessionConfigurationTypeDef,
         "Status": SessionStatusTypeDef,
         "Statistics": SessionStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkGroupsOutputTypeDef = TypedDict(
     "ListWorkGroupsOutputTypeDef",
     {
         "WorkGroups": List[WorkGroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSessionsResponseTypeDef = TypedDict(
     "ListSessionsResponseTypeDef",
     {
         "NextToken": str,
         "Sessions": List[SessionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueryRuntimeStatisticsOutputTypeDef = TypedDict(
     "GetQueryRuntimeStatisticsOutputTypeDef",
     {
         "QueryRuntimeStatistics": QueryRuntimeStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryExecutionTypeDef = TypedDict(
     "QueryExecutionTypeDef",
     {
         "QueryExecutionId": str,
@@ -2102,14 +2283,15 @@
         "ResultReuseConfiguration": ResultReuseConfigurationTypeDef,
         "QueryExecutionContext": QueryExecutionContextTypeDef,
         "Status": QueryExecutionStatusTypeDef,
         "Statistics": QueryExecutionStatisticsTypeDef,
         "WorkGroup": str,
         "EngineVersion": EngineVersionTypeDef,
         "ExecutionParameters": List[str],
+        "SubstatementType": str,
     },
     total=False,
 )
 
 _RequiredStartQueryExecutionInputRequestTypeDef = TypedDict(
     "_RequiredStartQueryExecutionInputRequestTypeDef",
     {
@@ -2136,15 +2318,15 @@
 
 GetQueryResultsOutputTypeDef = TypedDict(
     "GetQueryResultsOutputTypeDef",
     {
         "UpdateCount": int,
         "ResultSet": ResultSetTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateWorkGroupInputRequestTypeDef",
     {
         "Name": str,
@@ -2207,26 +2389,26 @@
     pass
 
 BatchGetQueryExecutionOutputTypeDef = TypedDict(
     "BatchGetQueryExecutionOutputTypeDef",
     {
         "QueryExecutions": List[QueryExecutionTypeDef],
         "UnprocessedQueryExecutionIds": List[UnprocessedQueryExecutionIdTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQueryExecutionOutputTypeDef = TypedDict(
     "GetQueryExecutionOutputTypeDef",
     {
         "QueryExecution": QueryExecutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkGroupOutputTypeDef = TypedDict(
     "GetWorkGroupOutputTypeDef",
     {
         "WorkGroup": WorkGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/PKG-INFO` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-athena
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Athena 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Athena 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-athena"></a>
 
 # types-aiobotocore-athena
 
 [![PyPI - types-aiobotocore-athena](https://img.shields.io/pypi/v/types-aiobotocore-athena.svg?color=blue)](https://pypi.org/project/types-aiobotocore-athena)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-athena.svg?color=blue)](https://pypi.org/project/types-aiobotocore-athena)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-athena?color=blue)](https://pypistats.org/packages/types-aiobotocore-athena)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Athena 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena)
+[aiobotocore.Athena 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/athena.html#Athena)
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
 [types-aiobotocore-athena docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_athena/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,14 +318,16 @@
 
 `types_aiobotocore_athena.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_athena.literals import (
     CalculationExecutionStateType,
+    CapacityAllocationStatusType,
+    CapacityReservationStatusType,
     ColumnNullableType,
     DataCatalogTypeType,
     EncryptionOptionType,
     ExecutorStateType,
     ExecutorTypeType,
     GetQueryResultsPaginatorName,
     ListDataCatalogsPaginatorName,
@@ -362,124 +364,143 @@
 ```python
 from types_aiobotocore_athena.type_defs import (
     AclConfigurationTypeDef,
     ApplicationDPUSizesTypeDef,
     AthenaErrorTypeDef,
     BatchGetNamedQueryInputRequestTypeDef,
     NamedQueryTypeDef,
-    ResponseMetadataTypeDef,
     UnprocessedNamedQueryIdTypeDef,
     BatchGetPreparedStatementInputRequestTypeDef,
     PreparedStatementTypeDef,
     UnprocessedPreparedStatementNameTypeDef,
     BatchGetQueryExecutionInputRequestTypeDef,
     UnprocessedQueryExecutionIdTypeDef,
     CalculationConfigurationTypeDef,
     CalculationResultTypeDef,
     CalculationStatisticsTypeDef,
     CalculationStatusTypeDef,
+    CancelCapacityReservationInputRequestTypeDef,
+    CapacityAllocationTypeDef,
+    CapacityAssignmentTypeDef,
     ColumnInfoTypeDef,
     ColumnTypeDef,
     TagTypeDef,
     CreateNamedQueryInputRequestTypeDef,
+    CreateNamedQueryOutputTypeDef,
     CreateNotebookInputRequestTypeDef,
+    CreateNotebookOutputTypeDef,
     CreatePreparedStatementInputRequestTypeDef,
     CreatePresignedNotebookUrlRequestRequestTypeDef,
+    CreatePresignedNotebookUrlResponseTypeDef,
     CustomerContentEncryptionConfigurationTypeDef,
     DataCatalogSummaryTypeDef,
     DataCatalogTypeDef,
     DatabaseTypeDef,
     DatumTypeDef,
+    DeleteCapacityReservationInputRequestTypeDef,
     DeleteDataCatalogInputRequestTypeDef,
     DeleteNamedQueryInputRequestTypeDef,
     DeleteNotebookInputRequestTypeDef,
     DeletePreparedStatementInputRequestTypeDef,
     DeleteWorkGroupInputRequestTypeDef,
     EncryptionConfigurationTypeDef,
     EngineConfigurationTypeDef,
     EngineVersionTypeDef,
     ExecutorsSummaryTypeDef,
     ExportNotebookInputRequestTypeDef,
     NotebookMetadataTypeDef,
     FilterDefinitionTypeDef,
     GetCalculationExecutionCodeRequestRequestTypeDef,
+    GetCalculationExecutionCodeResponseTypeDef,
     GetCalculationExecutionRequestRequestTypeDef,
     GetCalculationExecutionStatusRequestRequestTypeDef,
+    GetCapacityAssignmentConfigurationInputRequestTypeDef,
+    GetCapacityReservationInputRequestTypeDef,
     GetDataCatalogInputRequestTypeDef,
     GetDatabaseInputRequestTypeDef,
     GetNamedQueryInputRequestTypeDef,
     GetNotebookMetadataInputRequestTypeDef,
     GetPreparedStatementInputRequestTypeDef,
     GetQueryExecutionInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetQueryResultsInputGetQueryResultsPaginateTypeDef,
     GetQueryResultsInputRequestTypeDef,
     GetQueryRuntimeStatisticsInputRequestTypeDef,
     GetSessionRequestRequestTypeDef,
     SessionStatisticsTypeDef,
     SessionStatusTypeDef,
     GetSessionStatusRequestRequestTypeDef,
     GetTableMetadataInputRequestTypeDef,
     GetWorkGroupInputRequestTypeDef,
     ImportNotebookInputRequestTypeDef,
+    ImportNotebookOutputTypeDef,
     ListApplicationDPUSizesInputRequestTypeDef,
     ListCalculationExecutionsRequestRequestTypeDef,
+    ListCapacityReservationsInputRequestTypeDef,
+    ListDataCatalogsInputListDataCatalogsPaginateTypeDef,
     ListDataCatalogsInputRequestTypeDef,
+    ListDatabasesInputListDatabasesPaginateTypeDef,
     ListDatabasesInputRequestTypeDef,
     ListEngineVersionsInputRequestTypeDef,
     ListExecutorsRequestRequestTypeDef,
+    ListNamedQueriesInputListNamedQueriesPaginateTypeDef,
     ListNamedQueriesInputRequestTypeDef,
+    ListNamedQueriesOutputTypeDef,
     ListNotebookSessionsRequestRequestTypeDef,
     NotebookSessionSummaryTypeDef,
     ListPreparedStatementsInputRequestTypeDef,
     PreparedStatementSummaryTypeDef,
+    ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef,
     ListQueryExecutionsInputRequestTypeDef,
+    ListQueryExecutionsOutputTypeDef,
     ListSessionsRequestRequestTypeDef,
+    ListTableMetadataInputListTableMetadataPaginateTypeDef,
     ListTableMetadataInputRequestTypeDef,
+    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     ListWorkGroupsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     QueryExecutionContextTypeDef,
     ResultReuseInformationTypeDef,
     QueryRuntimeStatisticsRowsTypeDef,
     QueryRuntimeStatisticsTimelineTypeDef,
     QueryStagePlanNodeTypeDef,
     QueryStageTypeDef,
+    ResponseMetadataTypeDef,
     ResultReuseByAgeConfigurationTypeDef,
+    StartCalculationExecutionResponseTypeDef,
+    StartQueryExecutionOutputTypeDef,
+    StartSessionResponseTypeDef,
     StopCalculationExecutionRequestRequestTypeDef,
+    StopCalculationExecutionResponseTypeDef,
     StopQueryExecutionInputRequestTypeDef,
     TerminateSessionRequestRequestTypeDef,
+    TerminateSessionResponseTypeDef,
     UntagResourceInputRequestTypeDef,
+    UpdateCapacityReservationInputRequestTypeDef,
     UpdateDataCatalogInputRequestTypeDef,
     UpdateNamedQueryInputRequestTypeDef,
     UpdateNotebookInputRequestTypeDef,
     UpdateNotebookMetadataInputRequestTypeDef,
     UpdatePreparedStatementInputRequestTypeDef,
+    ListApplicationDPUSizesOutputTypeDef,
     QueryExecutionStatusTypeDef,
-    CreateNamedQueryOutputTypeDef,
-    CreateNotebookOutputTypeDef,
-    CreatePresignedNotebookUrlResponseTypeDef,
-    GetCalculationExecutionCodeResponseTypeDef,
     GetNamedQueryOutputTypeDef,
-    ImportNotebookOutputTypeDef,
-    ListApplicationDPUSizesOutputTypeDef,
-    ListNamedQueriesOutputTypeDef,
-    ListQueryExecutionsOutputTypeDef,
-    StartCalculationExecutionResponseTypeDef,
-    StartQueryExecutionOutputTypeDef,
-    StartSessionResponseTypeDef,
-    StopCalculationExecutionResponseTypeDef,
-    TerminateSessionResponseTypeDef,
     BatchGetNamedQueryOutputTypeDef,
     GetPreparedStatementOutputTypeDef,
     BatchGetPreparedStatementOutputTypeDef,
     StartCalculationExecutionRequestRequestTypeDef,
     CalculationSummaryTypeDef,
     GetCalculationExecutionResponseTypeDef,
     GetCalculationExecutionStatusResponseTypeDef,
+    CapacityReservationTypeDef,
+    CapacityAssignmentConfigurationTypeDef,
+    PutCapacityAssignmentConfigurationInputRequestTypeDef,
     ResultSetMetadataTypeDef,
     TableMetadataTypeDef,
+    CreateCapacityReservationInputRequestTypeDef,
     CreateDataCatalogInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
     TagResourceInputRequestTypeDef,
     ListDataCatalogsOutputTypeDef,
     GetDataCatalogOutputTypeDef,
     GetDatabaseOutputTypeDef,
     ListDatabasesOutputTypeDef,
@@ -491,29 +512,25 @@
     ListEngineVersionsOutputTypeDef,
     WorkGroupSummaryTypeDef,
     ListExecutorsResponseTypeDef,
     ExportNotebookOutputTypeDef,
     GetNotebookMetadataOutputTypeDef,
     ListNotebookMetadataOutputTypeDef,
     ListNotebookMetadataInputRequestTypeDef,
-    GetQueryResultsInputGetQueryResultsPaginateTypeDef,
-    ListDataCatalogsInputListDataCatalogsPaginateTypeDef,
-    ListDatabasesInputListDatabasesPaginateTypeDef,
-    ListNamedQueriesInputListNamedQueriesPaginateTypeDef,
-    ListQueryExecutionsInputListQueryExecutionsPaginateTypeDef,
-    ListTableMetadataInputListTableMetadataPaginateTypeDef,
-    ListTagsForResourceInputListTagsForResourcePaginateTypeDef,
     GetSessionStatusResponseTypeDef,
     SessionSummaryTypeDef,
     ListNotebookSessionsResponseTypeDef,
     ListPreparedStatementsOutputTypeDef,
     QueryExecutionStatisticsTypeDef,
     QueryRuntimeStatisticsTypeDef,
     ResultReuseConfigurationTypeDef,
     ListCalculationExecutionsResponseTypeDef,
+    GetCapacityReservationOutputTypeDef,
+    ListCapacityReservationsOutputTypeDef,
+    GetCapacityAssignmentConfigurationOutputTypeDef,
     GetTableMetadataOutputTypeDef,
     ListTableMetadataOutputTypeDef,
     ResultSetTypeDef,
     WorkGroupConfigurationTypeDef,
     WorkGroupConfigurationUpdatesTypeDef,
     GetSessionResponseTypeDef,
     ListWorkGroupsOutputTypeDef,
@@ -538,43 +555,43 @@
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

### Comparing `types-aiobotocore-athena-2.5.0.post1/types_aiobotocore_athena.egg-info/SOURCES.txt` & `types-aiobotocore-athena-2.5.1/types_aiobotocore_athena.egg-info/SOURCES.txt`

 * *Files identical despite different names*

