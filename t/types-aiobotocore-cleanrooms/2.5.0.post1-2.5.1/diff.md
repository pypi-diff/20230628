# Comparing `tmp/types-aiobotocore-cleanrooms-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cleanrooms-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cleanrooms-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:19 2023, max compression
+gzip compressed data, was "types-aiobotocore-cleanrooms-2.5.1.tar", last modified: Wed Jun 28 01:43:12 2023, max compression
```

## Comparing `types-aiobotocore-cleanrooms-2.5.0.post1.tar` & `types-aiobotocore-cleanrooms-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.823023 types-aiobotocore-cleanrooms-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19129 2023-03-11 12:26:19.811022 types-aiobotocore-cleanrooms-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17539 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:19.823023 types-aiobotocore-cleanrooms-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.811022 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/
--rw-r--r--   0 runner    (1001) docker     (123)     2046 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2045 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    30266 2023-03-11 12:10:35.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    30216 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10373 2023-03-11 12:10:35.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10371 2023-03-11 12:10:35.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9610 2023-03-11 12:10:35.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9600 2023-03-11 12:10:35.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    39957 2023-03-11 12:10:36.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    39906 2023-03-11 12:10:35.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:34.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.811022 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19129 2023-03-11 12:26:19.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:19.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:19.000000 types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:12.414105 types-aiobotocore-cleanrooms-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19280 2023-06-28 01:43:12.414105 types-aiobotocore-cleanrooms-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17696 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:12.414105 types-aiobotocore-cleanrooms-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:12.414105 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/
+-rw-r--r--   0 runner    (1001) docker     (123)     2046 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2045 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31966 2023-06-28 01:27:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31913 2023-06-28 01:27:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10582 2023-06-28 01:27:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10580 2023-06-28 01:27:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9541 2023-06-28 01:27:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9531 2023-06-28 01:27:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    41309 2023-06-28 01:27:13.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41256 2023-06-28 01:27:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:11.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:12.414105 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19280 2023-06-28 01:43:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:12.000000 types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/LICENSE` & `types-aiobotocore-cleanrooms-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cleanrooms-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cleanrooms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CleanRoomsService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CleanRoomsService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cleanrooms"></a>
 
 # types-aiobotocore-cleanrooms
 
 [![PyPI - types-aiobotocore-cleanrooms](https://img.shields.io/pypi/v/types-aiobotocore-cleanrooms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cleanrooms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cleanrooms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cleanrooms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cleanrooms?color=blue)](https://pypistats.org/packages/types-aiobotocore-cleanrooms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CleanRoomsService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService)
+[aiobotocore.CleanRoomsService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService)
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
 [types-aiobotocore-cleanrooms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -365,15 +365,14 @@
 ```python
 from types_aiobotocore_cleanrooms.type_defs import (
     AggregateColumnTypeDef,
     AggregationConstraintTypeDef,
     AnalysisRuleListTypeDef,
     BatchGetSchemaErrorTypeDef,
     BatchGetSchemaInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     CollaborationSummaryTypeDef,
     DataEncryptionMetadataTypeDef,
     ColumnTypeDef,
     ConfiguredTableAssociationSummaryTypeDef,
     ConfiguredTableAssociationTypeDef,
     ConfiguredTableSummaryTypeDef,
     MemberSpecificationTypeDef,
@@ -391,31 +390,43 @@
     GetConfiguredTableAssociationInputRequestTypeDef,
     GetConfiguredTableInputRequestTypeDef,
     GetMembershipInputRequestTypeDef,
     GetProtectedQueryInputRequestTypeDef,
     GetSchemaAnalysisRuleInputRequestTypeDef,
     GetSchemaInputRequestTypeDef,
     GlueTableReferenceTypeDef,
-    PaginatorConfigTypeDef,
+    ListCollaborationsInputListCollaborationsPaginateTypeDef,
     ListCollaborationsInputRequestTypeDef,
+    ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
     ListConfiguredTableAssociationsInputRequestTypeDef,
+    ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef,
     ListConfiguredTablesInputRequestTypeDef,
+    ListMembersInputListMembersPaginateTypeDef,
     ListMembersInputRequestTypeDef,
     MemberSummaryTypeDef,
+    ListMembershipsInputListMembershipsPaginateTypeDef,
     ListMembershipsInputRequestTypeDef,
     MembershipSummaryTypeDef,
+    ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
     ListProtectedQueriesInputRequestTypeDef,
     ProtectedQuerySummaryTypeDef,
+    ListSchemasInputListSchemasPaginateTypeDef,
     ListSchemasInputRequestTypeDef,
     SchemaSummaryTypeDef,
+    ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     ProtectedQueryErrorTypeDef,
     ProtectedQueryS3OutputConfigurationTypeDef,
     ProtectedQueryS3OutputTypeDef,
     ProtectedQuerySQLParametersTypeDef,
     ProtectedQueryStatisticsTypeDef,
+    ResponseMetadataTypeDef,
+    TagResourceInputRequestTypeDef,
+    UntagResourceInputRequestTypeDef,
     UpdateCollaborationInputRequestTypeDef,
     UpdateConfiguredTableAssociationInputRequestTypeDef,
     UpdateConfiguredTableInputRequestTypeDef,
     UpdateMembershipInputRequestTypeDef,
     UpdateProtectedQueryInputRequestTypeDef,
     AnalysisRuleAggregationTypeDef,
     ListCollaborationsOutputTypeDef,
@@ -427,21 +438,14 @@
     UpdateConfiguredTableAssociationOutputTypeDef,
     ListConfiguredTablesOutputTypeDef,
     CreateCollaborationInputRequestTypeDef,
     CreateMembershipOutputTypeDef,
     GetMembershipOutputTypeDef,
     UpdateMembershipOutputTypeDef,
     TableReferenceTypeDef,
-    ListCollaborationsInputListCollaborationsPaginateTypeDef,
-    ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
-    ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef,
-    ListMembersInputListMembersPaginateTypeDef,
-    ListMembershipsInputListMembershipsPaginateTypeDef,
-    ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
-    ListSchemasInputListSchemasPaginateTypeDef,
     ListMembersOutputTypeDef,
     ListMembershipsOutputTypeDef,
     ListProtectedQueriesOutputTypeDef,
     ListSchemasOutputTypeDef,
     ProtectedQueryOutputConfigurationTypeDef,
     ProtectedQueryOutputTypeDef,
     AnalysisRulePolicyV1TypeDef,
@@ -483,43 +487,43 @@
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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/README.md` & `types-aiobotocore-cleanrooms-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cleanrooms"></a>
 
 # types-aiobotocore-cleanrooms
 
 [![PyPI - types-aiobotocore-cleanrooms](https://img.shields.io/pypi/v/types-aiobotocore-cleanrooms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cleanrooms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cleanrooms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cleanrooms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cleanrooms?color=blue)](https://pypistats.org/packages/types-aiobotocore-cleanrooms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CleanRoomsService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService)
+[aiobotocore.CleanRoomsService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService)
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
 [types-aiobotocore-cleanrooms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,15 +332,14 @@
 ```python
 from types_aiobotocore_cleanrooms.type_defs import (
     AggregateColumnTypeDef,
     AggregationConstraintTypeDef,
     AnalysisRuleListTypeDef,
     BatchGetSchemaErrorTypeDef,
     BatchGetSchemaInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     CollaborationSummaryTypeDef,
     DataEncryptionMetadataTypeDef,
     ColumnTypeDef,
     ConfiguredTableAssociationSummaryTypeDef,
     ConfiguredTableAssociationTypeDef,
     ConfiguredTableSummaryTypeDef,
     MemberSpecificationTypeDef,
@@ -358,31 +357,43 @@
     GetConfiguredTableAssociationInputRequestTypeDef,
     GetConfiguredTableInputRequestTypeDef,
     GetMembershipInputRequestTypeDef,
     GetProtectedQueryInputRequestTypeDef,
     GetSchemaAnalysisRuleInputRequestTypeDef,
     GetSchemaInputRequestTypeDef,
     GlueTableReferenceTypeDef,
-    PaginatorConfigTypeDef,
+    ListCollaborationsInputListCollaborationsPaginateTypeDef,
     ListCollaborationsInputRequestTypeDef,
+    ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
     ListConfiguredTableAssociationsInputRequestTypeDef,
+    ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef,
     ListConfiguredTablesInputRequestTypeDef,
+    ListMembersInputListMembersPaginateTypeDef,
     ListMembersInputRequestTypeDef,
     MemberSummaryTypeDef,
+    ListMembershipsInputListMembershipsPaginateTypeDef,
     ListMembershipsInputRequestTypeDef,
     MembershipSummaryTypeDef,
+    ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
     ListProtectedQueriesInputRequestTypeDef,
     ProtectedQuerySummaryTypeDef,
+    ListSchemasInputListSchemasPaginateTypeDef,
     ListSchemasInputRequestTypeDef,
     SchemaSummaryTypeDef,
+    ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     ProtectedQueryErrorTypeDef,
     ProtectedQueryS3OutputConfigurationTypeDef,
     ProtectedQueryS3OutputTypeDef,
     ProtectedQuerySQLParametersTypeDef,
     ProtectedQueryStatisticsTypeDef,
+    ResponseMetadataTypeDef,
+    TagResourceInputRequestTypeDef,
+    UntagResourceInputRequestTypeDef,
     UpdateCollaborationInputRequestTypeDef,
     UpdateConfiguredTableAssociationInputRequestTypeDef,
     UpdateConfiguredTableInputRequestTypeDef,
     UpdateMembershipInputRequestTypeDef,
     UpdateProtectedQueryInputRequestTypeDef,
     AnalysisRuleAggregationTypeDef,
     ListCollaborationsOutputTypeDef,
@@ -394,21 +405,14 @@
     UpdateConfiguredTableAssociationOutputTypeDef,
     ListConfiguredTablesOutputTypeDef,
     CreateCollaborationInputRequestTypeDef,
     CreateMembershipOutputTypeDef,
     GetMembershipOutputTypeDef,
     UpdateMembershipOutputTypeDef,
     TableReferenceTypeDef,
-    ListCollaborationsInputListCollaborationsPaginateTypeDef,
-    ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
-    ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef,
-    ListMembersInputListMembersPaginateTypeDef,
-    ListMembershipsInputListMembershipsPaginateTypeDef,
-    ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
-    ListSchemasInputListSchemasPaginateTypeDef,
     ListMembersOutputTypeDef,
     ListMembershipsOutputTypeDef,
     ListProtectedQueriesOutputTypeDef,
     ListSchemasOutputTypeDef,
     ProtectedQueryOutputConfigurationTypeDef,
     ProtectedQueryOutputTypeDef,
     AnalysisRulePolicyV1TypeDef,
@@ -450,43 +454,43 @@
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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/setup.py` & `types-aiobotocore-cleanrooms-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cleanrooms.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cleanrooms",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cleanrooms"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CleanRoomsService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CleanRoomsService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/"
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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/__init__.py` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/__init__.pyi` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/__main__.py` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CleanRoomsService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CleanRoomsService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService\nOther"
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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/client.py` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/client.py`

 * *Files 3% similar despite different names*

```diff
@@ -59,14 +59,15 @@
     ListCollaborationsOutputTypeDef,
     ListConfiguredTableAssociationsOutputTypeDef,
     ListConfiguredTablesOutputTypeDef,
     ListMembershipsOutputTypeDef,
     ListMembersOutputTypeDef,
     ListProtectedQueriesOutputTypeDef,
     ListSchemasOutputTypeDef,
+    ListTagsForResourceOutputTypeDef,
     MemberSpecificationTypeDef,
     ProtectedQueryResultConfigurationTypeDef,
     ProtectedQuerySQLParametersTypeDef,
     StartProtectedQueryOutputTypeDef,
     TableReferenceTypeDef,
     UpdateCollaborationOutputTypeDef,
     UpdateConfiguredTableAnalysisRuleOutputTypeDef,
@@ -152,15 +153,16 @@
         *,
         members: Sequence[MemberSpecificationTypeDef],
         name: str,
         description: str,
         creatorMemberAbilities: Sequence[MemberAbilityType],
         creatorDisplayName: str,
         queryLogStatus: CollaborationQueryLogStatusType,
-        dataEncryptionMetadata: DataEncryptionMetadataTypeDef = ...
+        dataEncryptionMetadata: DataEncryptionMetadataTypeDef = ...,
+        tags: Mapping[str, str] = ...
     ) -> CreateCollaborationOutputTypeDef:
         """
         Creates a new collaboration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_collaboration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_collaboration)
         """
@@ -168,15 +170,16 @@
     async def create_configured_table(
         self,
         *,
         name: str,
         tableReference: TableReferenceTypeDef,
         allowedColumns: Sequence[str],
         analysisMethod: Literal["DIRECT_QUERY"],
-        description: str = ...
+        description: str = ...,
+        tags: Mapping[str, str] = ...
     ) -> CreateConfiguredTableOutputTypeDef:
         """
         Creates a new configured table resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_configured_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_configured_table)
         """
@@ -198,25 +201,30 @@
     async def create_configured_table_association(
         self,
         *,
         name: str,
         membershipIdentifier: str,
         configuredTableIdentifier: str,
         roleArn: str,
-        description: str = ...
+        description: str = ...,
+        tags: Mapping[str, str] = ...
     ) -> CreateConfiguredTableAssociationOutputTypeDef:
         """
         Creates a configured table association.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_configured_table_association)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_configured_table_association)
         """
 
     async def create_membership(
-        self, *, collaborationIdentifier: str, queryLogStatus: MembershipQueryLogStatusType
+        self,
+        *,
+        collaborationIdentifier: str,
+        queryLogStatus: MembershipQueryLogStatusType,
+        tags: Mapping[str, str] = ...
     ) -> CreateMembershipOutputTypeDef:
         """
         Creates a membership for a specific collaboration identifier and joins the
         collaboration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_membership)
@@ -454,14 +462,22 @@
         """
         Lists the schemas for relations within a collaboration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.list_schemas)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#list_schemas)
         """
 
+    async def list_tags_for_resource(self, *, resourceArn: str) -> ListTagsForResourceOutputTypeDef:
+        """
+        Lists all of the tags that have been added to a resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.list_tags_for_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#list_tags_for_resource)
+        """
+
     async def start_protected_query(
         self,
         *,
         type: Literal["SQL"],
         membershipIdentifier: str,
         sqlParameters: ProtectedQuerySQLParametersTypeDef,
         resultConfiguration: ProtectedQueryResultConfigurationTypeDef
@@ -469,14 +485,30 @@
         """
         Creates a protected query that is started by AWS Clean Rooms.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.start_protected_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#start_protected_query)
         """
 
+    async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
+        """
+        Tags a resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.tag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#tag_resource)
+        """
+
+    async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
+        """
+        Removes a tag or list of tags from a resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.untag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#untag_resource)
+        """
+
     async def update_collaboration(
         self, *, collaborationIdentifier: str, name: str = ..., description: str = ...
     ) -> UpdateCollaborationOutputTypeDef:
         """
         Updates collaboration metadata and can only be called by the collaboration
         owner.
```

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/client.pyi` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/client.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -59,14 +59,15 @@
     ListCollaborationsOutputTypeDef,
     ListConfiguredTableAssociationsOutputTypeDef,
     ListConfiguredTablesOutputTypeDef,
     ListMembershipsOutputTypeDef,
     ListMembersOutputTypeDef,
     ListProtectedQueriesOutputTypeDef,
     ListSchemasOutputTypeDef,
+    ListTagsForResourceOutputTypeDef,
     MemberSpecificationTypeDef,
     ProtectedQueryResultConfigurationTypeDef,
     ProtectedQuerySQLParametersTypeDef,
     StartProtectedQueryOutputTypeDef,
     TableReferenceTypeDef,
     UpdateCollaborationOutputTypeDef,
     UpdateConfiguredTableAnalysisRuleOutputTypeDef,
@@ -144,30 +145,32 @@
         *,
         members: Sequence[MemberSpecificationTypeDef],
         name: str,
         description: str,
         creatorMemberAbilities: Sequence[MemberAbilityType],
         creatorDisplayName: str,
         queryLogStatus: CollaborationQueryLogStatusType,
-        dataEncryptionMetadata: DataEncryptionMetadataTypeDef = ...
+        dataEncryptionMetadata: DataEncryptionMetadataTypeDef = ...,
+        tags: Mapping[str, str] = ...
     ) -> CreateCollaborationOutputTypeDef:
         """
         Creates a new collaboration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_collaboration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_collaboration)
         """
     async def create_configured_table(
         self,
         *,
         name: str,
         tableReference: TableReferenceTypeDef,
         allowedColumns: Sequence[str],
         analysisMethod: Literal["DIRECT_QUERY"],
-        description: str = ...
+        description: str = ...,
+        tags: Mapping[str, str] = ...
     ) -> CreateConfiguredTableOutputTypeDef:
         """
         Creates a new configured table resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_configured_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_configured_table)
         """
@@ -187,24 +190,29 @@
     async def create_configured_table_association(
         self,
         *,
         name: str,
         membershipIdentifier: str,
         configuredTableIdentifier: str,
         roleArn: str,
-        description: str = ...
+        description: str = ...,
+        tags: Mapping[str, str] = ...
     ) -> CreateConfiguredTableAssociationOutputTypeDef:
         """
         Creates a configured table association.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_configured_table_association)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_configured_table_association)
         """
     async def create_membership(
-        self, *, collaborationIdentifier: str, queryLogStatus: MembershipQueryLogStatusType
+        self,
+        *,
+        collaborationIdentifier: str,
+        queryLogStatus: MembershipQueryLogStatusType,
+        tags: Mapping[str, str] = ...
     ) -> CreateMembershipOutputTypeDef:
         """
         Creates a membership for a specific collaboration identifier and joins the
         collaboration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.create_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#create_membership)
@@ -419,28 +427,49 @@
     ) -> ListSchemasOutputTypeDef:
         """
         Lists the schemas for relations within a collaboration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.list_schemas)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#list_schemas)
         """
+    async def list_tags_for_resource(self, *, resourceArn: str) -> ListTagsForResourceOutputTypeDef:
+        """
+        Lists all of the tags that have been added to a resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.list_tags_for_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#list_tags_for_resource)
+        """
     async def start_protected_query(
         self,
         *,
         type: Literal["SQL"],
         membershipIdentifier: str,
         sqlParameters: ProtectedQuerySQLParametersTypeDef,
         resultConfiguration: ProtectedQueryResultConfigurationTypeDef
     ) -> StartProtectedQueryOutputTypeDef:
         """
         Creates a protected query that is started by AWS Clean Rooms.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.start_protected_query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#start_protected_query)
         """
+    async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
+        """
+        Tags a resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.tag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#tag_resource)
+        """
+    async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
+        """
+        Removes a tag or list of tags from a resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Client.untag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/client/#untag_resource)
+        """
     async def update_collaboration(
         self, *, collaborationIdentifier: str, name: str = ..., description: str = ...
     ) -> UpdateCollaborationOutputTypeDef:
         """
         Updates collaboration metadata and can only be called by the collaboration
         owner.
```

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/literals.py` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -153,14 +153,15 @@
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
@@ -239,14 +240,15 @@
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
@@ -257,14 +259,15 @@
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
@@ -300,14 +303,15 @@
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
@@ -326,16 +330,19 @@
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
@@ -419,15 +426,17 @@
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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/literals.pyi` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -151,14 +151,15 @@
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
@@ -237,14 +238,15 @@
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
@@ -255,14 +257,15 @@
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
@@ -298,14 +301,15 @@
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
@@ -324,16 +328,19 @@
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
@@ -417,15 +424,17 @@
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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/paginator.py` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -29,15 +29,15 @@
         list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
         list_memberships_paginator: ListMembershipsPaginator = client.get_paginator("list_memberships")
         list_protected_queries_paginator: ListProtectedQueriesPaginator = client.get_paginator("list_protected_queries")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import FilterableMemberStatusType, MembershipStatusType, ProtectedQueryStatusType
 from .type_defs import (
     ListCollaborationsOutputTypeDef,
@@ -46,152 +46,141 @@
     ListMembershipsOutputTypeDef,
     ListMembersOutputTypeDef,
     ListProtectedQueriesOutputTypeDef,
     ListSchemasOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ListCollaborationsPaginator",
     "ListConfiguredTableAssociationsPaginator",
     "ListConfiguredTablesPaginator",
     "ListMembersPaginator",
     "ListMembershipsPaginator",
     "ListProtectedQueriesPaginator",
     "ListSchemasPaginator",
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
 class ListCollaborationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListCollaborations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listcollaborationspaginator)
     """
 
     def paginate(
         self,
         *,
         memberStatus: FilterableMemberStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCollaborationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListCollaborations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listcollaborationspaginator)
         """
 
-
 class ListConfiguredTableAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTableAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtableassociationspaginator)
     """
 
     def paginate(
-        self, *, membershipIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, membershipIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfiguredTableAssociationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTableAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtableassociationspaginator)
         """
 
-
 class ListConfiguredTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtablespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfiguredTablesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtablespaginator)
         """
 
-
 class ListMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmemberspaginator)
     """
 
     def paginate(
-        self, *, collaborationIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, collaborationIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmemberspaginator)
         """
 
-
 class ListMembershipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMemberships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmembershipspaginator)
     """
 
     def paginate(
-        self, *, status: MembershipStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        status: MembershipStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembershipsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMemberships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmembershipspaginator)
         """
 
-
 class ListProtectedQueriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListProtectedQueries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listprotectedqueriespaginator)
     """
 
     def paginate(
         self,
         *,
         membershipIdentifier: str,
         status: ProtectedQueryStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtectedQueriesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListProtectedQueries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listprotectedqueriespaginator)
         """
 
-
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listschemaspaginator)
     """
 
     def paginate(
         self,
         *,
         collaborationIdentifier: str,
         schemaType: Literal["TABLE"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listschemaspaginator)
         """
```

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/paginator.pyi` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -29,15 +29,15 @@
         list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
         list_memberships_paginator: ListMembershipsPaginator = client.get_paginator("list_memberships")
         list_protected_queries_paginator: ListProtectedQueriesPaginator = client.get_paginator("list_protected_queries")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import FilterableMemberStatusType, MembershipStatusType, ProtectedQueryStatusType
 from .type_defs import (
     ListCollaborationsOutputTypeDef,
@@ -46,142 +46,151 @@
     ListMembershipsOutputTypeDef,
     ListMembersOutputTypeDef,
     ListProtectedQueriesOutputTypeDef,
     ListSchemasOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ListCollaborationsPaginator",
     "ListConfiguredTableAssociationsPaginator",
     "ListConfiguredTablesPaginator",
     "ListMembersPaginator",
     "ListMembershipsPaginator",
     "ListProtectedQueriesPaginator",
     "ListSchemasPaginator",
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
 class ListCollaborationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListCollaborations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listcollaborationspaginator)
     """
 
     def paginate(
         self,
         *,
         memberStatus: FilterableMemberStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCollaborationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListCollaborations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listcollaborationspaginator)
         """
 
+
 class ListConfiguredTableAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTableAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtableassociationspaginator)
     """
 
     def paginate(
-        self, *, membershipIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, membershipIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfiguredTableAssociationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTableAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtableassociationspaginator)
         """
 
+
 class ListConfiguredTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtablespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfiguredTablesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListConfiguredTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listconfiguredtablespaginator)
         """
 
+
 class ListMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmemberspaginator)
     """
 
     def paginate(
-        self, *, collaborationIdentifier: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, collaborationIdentifier: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmemberspaginator)
         """
 
+
 class ListMembershipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMemberships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmembershipspaginator)
     """
 
     def paginate(
-        self, *, status: MembershipStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        status: MembershipStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembershipsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListMemberships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listmembershipspaginator)
         """
 
+
 class ListProtectedQueriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListProtectedQueries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listprotectedqueriespaginator)
     """
 
     def paginate(
         self,
         *,
         membershipIdentifier: str,
         status: ProtectedQueryStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtectedQueriesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListProtectedQueries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listprotectedqueriespaginator)
         """
 
+
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listschemaspaginator)
     """
 
     def paginate(
         self,
         *,
         collaborationIdentifier: str,
         schemaType: Literal["TABLE"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/paginators/#listschemaspaginator)
         """
```

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/type_defs.py` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_cleanrooms.type_defs import AggregateColumnTypeDef
 
     data: AggregateColumnTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Sequence
+from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AggregateFunctionNameType,
     AnalysisRuleTypeType,
     CollaborationQueryLogStatusType,
     ConfiguredTableAnalysisRuleTypeType,
     FilterableMemberStatusType,
@@ -42,15 +42,14 @@
 
 __all__ = (
     "AggregateColumnTypeDef",
     "AggregationConstraintTypeDef",
     "AnalysisRuleListTypeDef",
     "BatchGetSchemaErrorTypeDef",
     "BatchGetSchemaInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CollaborationSummaryTypeDef",
     "DataEncryptionMetadataTypeDef",
     "ColumnTypeDef",
     "ConfiguredTableAssociationSummaryTypeDef",
     "ConfiguredTableAssociationTypeDef",
     "ConfiguredTableSummaryTypeDef",
     "MemberSpecificationTypeDef",
@@ -68,31 +67,43 @@
     "GetConfiguredTableAssociationInputRequestTypeDef",
     "GetConfiguredTableInputRequestTypeDef",
     "GetMembershipInputRequestTypeDef",
     "GetProtectedQueryInputRequestTypeDef",
     "GetSchemaAnalysisRuleInputRequestTypeDef",
     "GetSchemaInputRequestTypeDef",
     "GlueTableReferenceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
     "ListCollaborationsInputRequestTypeDef",
+    "ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
     "ListConfiguredTableAssociationsInputRequestTypeDef",
+    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
     "ListConfiguredTablesInputRequestTypeDef",
+    "ListMembersInputListMembersPaginateTypeDef",
     "ListMembersInputRequestTypeDef",
     "MemberSummaryTypeDef",
+    "ListMembershipsInputListMembershipsPaginateTypeDef",
     "ListMembershipsInputRequestTypeDef",
     "MembershipSummaryTypeDef",
+    "ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
     "ListProtectedQueriesInputRequestTypeDef",
     "ProtectedQuerySummaryTypeDef",
+    "ListSchemasInputListSchemasPaginateTypeDef",
     "ListSchemasInputRequestTypeDef",
     "SchemaSummaryTypeDef",
+    "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "ProtectedQueryErrorTypeDef",
     "ProtectedQueryS3OutputConfigurationTypeDef",
     "ProtectedQueryS3OutputTypeDef",
     "ProtectedQuerySQLParametersTypeDef",
     "ProtectedQueryStatisticsTypeDef",
+    "ResponseMetadataTypeDef",
+    "TagResourceInputRequestTypeDef",
+    "UntagResourceInputRequestTypeDef",
     "UpdateCollaborationInputRequestTypeDef",
     "UpdateConfiguredTableAssociationInputRequestTypeDef",
     "UpdateConfiguredTableInputRequestTypeDef",
     "UpdateMembershipInputRequestTypeDef",
     "UpdateProtectedQueryInputRequestTypeDef",
     "AnalysisRuleAggregationTypeDef",
     "ListCollaborationsOutputTypeDef",
@@ -104,21 +115,14 @@
     "UpdateConfiguredTableAssociationOutputTypeDef",
     "ListConfiguredTablesOutputTypeDef",
     "CreateCollaborationInputRequestTypeDef",
     "CreateMembershipOutputTypeDef",
     "GetMembershipOutputTypeDef",
     "UpdateMembershipOutputTypeDef",
     "TableReferenceTypeDef",
-    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
-    "ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
-    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
-    "ListMembersInputListMembersPaginateTypeDef",
-    "ListMembershipsInputListMembershipsPaginateTypeDef",
-    "ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
-    "ListSchemasInputListSchemasPaginateTypeDef",
     "ListMembersOutputTypeDef",
     "ListMembershipsOutputTypeDef",
     "ListProtectedQueriesOutputTypeDef",
     "ListSchemasOutputTypeDef",
     "ProtectedQueryOutputConfigurationTypeDef",
     "ProtectedQueryOutputTypeDef",
     "AnalysisRulePolicyV1TypeDef",
@@ -190,25 +194,14 @@
     "BatchGetSchemaInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
         "names": Sequence[str],
     },
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
 _RequiredCollaborationSummaryTypeDef = TypedDict(
     "_RequiredCollaborationSummaryTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
         "creatorAccountId": str,
@@ -327,33 +320,48 @@
         "roleArn": str,
     },
 )
 _OptionalCreateConfiguredTableAssociationInputRequestTypeDef = TypedDict(
     "_OptionalCreateConfiguredTableAssociationInputRequestTypeDef",
     {
         "description": str,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class CreateConfiguredTableAssociationInputRequestTypeDef(
     _RequiredCreateConfiguredTableAssociationInputRequestTypeDef,
     _OptionalCreateConfiguredTableAssociationInputRequestTypeDef,
 ):
     pass
 
 
-CreateMembershipInputRequestTypeDef = TypedDict(
-    "CreateMembershipInputRequestTypeDef",
+_RequiredCreateMembershipInputRequestTypeDef = TypedDict(
+    "_RequiredCreateMembershipInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
         "queryLogStatus": MembershipQueryLogStatusType,
     },
 )
+_OptionalCreateMembershipInputRequestTypeDef = TypedDict(
+    "_OptionalCreateMembershipInputRequestTypeDef",
+    {
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class CreateMembershipInputRequestTypeDef(
+    _RequiredCreateMembershipInputRequestTypeDef, _OptionalCreateMembershipInputRequestTypeDef
+):
+    pass
+
 
 MembershipTypeDef = TypedDict(
     "MembershipTypeDef",
     {
         "id": str,
         "arn": str,
         "collaborationArn": str,
@@ -480,34 +488,55 @@
     "GlueTableReferenceTypeDef",
     {
         "tableName": str,
         "databaseName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListCollaborationsInputListCollaborationsPaginateTypeDef = TypedDict(
+    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "memberStatus": FilterableMemberStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCollaborationsInputRequestTypeDef = TypedDict(
     "ListCollaborationsInputRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "memberStatus": FilterableMemberStatusType,
     },
     total=False,
 )
 
+_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
+    {
+        "membershipIdentifier": str,
+    },
+)
+_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef(
+    _RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
+    _OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListConfiguredTableAssociationsInputRequestTypeDef = TypedDict(
     "_RequiredListConfiguredTableAssociationsInputRequestTypeDef",
     {
         "membershipIdentifier": str,
     },
 )
 _OptionalListConfiguredTableAssociationsInputRequestTypeDef = TypedDict(
@@ -523,23 +552,53 @@
 class ListConfiguredTableAssociationsInputRequestTypeDef(
     _RequiredListConfiguredTableAssociationsInputRequestTypeDef,
     _OptionalListConfiguredTableAssociationsInputRequestTypeDef,
 ):
     pass
 
 
+ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef = TypedDict(
+    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConfiguredTablesInputRequestTypeDef = TypedDict(
     "ListConfiguredTablesInputRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListMembersInputListMembersPaginateTypeDef = TypedDict(
+    "_RequiredListMembersInputListMembersPaginateTypeDef",
+    {
+        "collaborationIdentifier": str,
+    },
+)
+_OptionalListMembersInputListMembersPaginateTypeDef = TypedDict(
+    "_OptionalListMembersInputListMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMembersInputListMembersPaginateTypeDef(
+    _RequiredListMembersInputListMembersPaginateTypeDef,
+    _OptionalListMembersInputListMembersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMembersInputRequestTypeDef = TypedDict(
     "_RequiredListMembersInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
     },
 )
 _OptionalListMembersInputRequestTypeDef = TypedDict(
@@ -579,14 +638,23 @@
 )
 
 
 class MemberSummaryTypeDef(_RequiredMemberSummaryTypeDef, _OptionalMemberSummaryTypeDef):
     pass
 
 
+ListMembershipsInputListMembershipsPaginateTypeDef = TypedDict(
+    "ListMembershipsInputListMembershipsPaginateTypeDef",
+    {
+        "status": MembershipStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMembershipsInputRequestTypeDef = TypedDict(
     "ListMembershipsInputRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "status": MembershipStatusType,
     },
@@ -606,14 +674,37 @@
         "createTime": datetime,
         "updateTime": datetime,
         "status": MembershipStatusType,
         "memberAbilities": List[MemberAbilityType],
     },
 )
 
+_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
+    "_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
+    {
+        "membershipIdentifier": str,
+    },
+)
+_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
+    "_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
+    {
+        "status": ProtectedQueryStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef(
+    _RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
+    _OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProtectedQueriesInputRequestTypeDef = TypedDict(
     "_RequiredListProtectedQueriesInputRequestTypeDef",
     {
         "membershipIdentifier": str,
     },
 )
 _OptionalListProtectedQueriesInputRequestTypeDef = TypedDict(
@@ -641,14 +732,37 @@
         "membershipId": str,
         "membershipArn": str,
         "createTime": datetime,
         "status": ProtectedQueryStatusType,
     },
 )
 
+_RequiredListSchemasInputListSchemasPaginateTypeDef = TypedDict(
+    "_RequiredListSchemasInputListSchemasPaginateTypeDef",
+    {
+        "collaborationIdentifier": str,
+    },
+)
+_OptionalListSchemasInputListSchemasPaginateTypeDef = TypedDict(
+    "_OptionalListSchemasInputListSchemasPaginateTypeDef",
+    {
+        "schemaType": Literal["TABLE"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSchemasInputListSchemasPaginateTypeDef(
+    _RequiredListSchemasInputListSchemasPaginateTypeDef,
+    _OptionalListSchemasInputListSchemasPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSchemasInputRequestTypeDef = TypedDict(
     "_RequiredListSchemasInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
     },
 )
 _OptionalListSchemasInputRequestTypeDef = TypedDict(
@@ -690,14 +804,39 @@
 )
 
 
 class SchemaSummaryTypeDef(_RequiredSchemaSummaryTypeDef, _OptionalSchemaSummaryTypeDef):
     pass
 
 
+ListTagsForResourceInputRequestTypeDef = TypedDict(
+    "ListTagsForResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "tags": Dict[str, str],
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
 ProtectedQueryErrorTypeDef = TypedDict(
     "ProtectedQueryErrorTypeDef",
     {
         "message": str,
         "code": str,
     },
 )
@@ -743,14 +882,41 @@
     "ProtectedQueryStatisticsTypeDef",
     {
         "totalDurationInMillis": int,
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
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tags": Mapping[str, str],
+    },
+)
+
+UntagResourceInputRequestTypeDef = TypedDict(
+    "UntagResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
+    },
+)
+
 _RequiredUpdateCollaborationInputRequestTypeDef = TypedDict(
     "_RequiredUpdateCollaborationInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
     },
 )
 _OptionalUpdateCollaborationInputRequestTypeDef = TypedDict(
@@ -872,15 +1038,15 @@
 
 
 ListCollaborationsOutputTypeDef = TypedDict(
     "ListCollaborationsOutputTypeDef",
     {
         "nextToken": str,
         "collaborationList": List[CollaborationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCollaborationTypeDef = TypedDict(
     "_RequiredCollaborationTypeDef",
     {
         "id": str,
@@ -940,48 +1106,48 @@
 
 
 ListConfiguredTableAssociationsOutputTypeDef = TypedDict(
     "ListConfiguredTableAssociationsOutputTypeDef",
     {
         "configuredTableAssociationSummaries": List[ConfiguredTableAssociationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConfiguredTableAssociationOutputTypeDef = TypedDict(
     "CreateConfiguredTableAssociationOutputTypeDef",
     {
         "configuredTableAssociation": ConfiguredTableAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConfiguredTableAssociationOutputTypeDef = TypedDict(
     "GetConfiguredTableAssociationOutputTypeDef",
     {
         "configuredTableAssociation": ConfiguredTableAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfiguredTableAssociationOutputTypeDef = TypedDict(
     "UpdateConfiguredTableAssociationOutputTypeDef",
     {
         "configuredTableAssociation": ConfiguredTableAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConfiguredTablesOutputTypeDef = TypedDict(
     "ListConfiguredTablesOutputTypeDef",
     {
         "configuredTableSummaries": List[ConfiguredTableSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCollaborationInputRequestTypeDef = TypedDict(
     "_RequiredCreateCollaborationInputRequestTypeDef",
     {
         "members": Sequence[MemberSpecificationTypeDef],
@@ -992,14 +1158,15 @@
         "queryLogStatus": CollaborationQueryLogStatusType,
     },
 )
 _OptionalCreateCollaborationInputRequestTypeDef = TypedDict(
     "_OptionalCreateCollaborationInputRequestTypeDef",
     {
         "dataEncryptionMetadata": DataEncryptionMetadataTypeDef,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class CreateCollaborationInputRequestTypeDef(
     _RequiredCreateCollaborationInputRequestTypeDef, _OptionalCreateCollaborationInputRequestTypeDef
@@ -1007,191 +1174,75 @@
     pass
 
 
 CreateMembershipOutputTypeDef = TypedDict(
     "CreateMembershipOutputTypeDef",
     {
         "membership": MembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMembershipOutputTypeDef = TypedDict(
     "GetMembershipOutputTypeDef",
     {
         "membership": MembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMembershipOutputTypeDef = TypedDict(
     "UpdateMembershipOutputTypeDef",
     {
         "membership": MembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TableReferenceTypeDef = TypedDict(
     "TableReferenceTypeDef",
     {
         "glue": GlueTableReferenceTypeDef,
     },
     total=False,
 )
 
-ListCollaborationsInputListCollaborationsPaginateTypeDef = TypedDict(
-    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
-    {
-        "memberStatus": FilterableMemberStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
-    {
-        "membershipIdentifier": str,
-    },
-)
-_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef(
-    _RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
-    _OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
-):
-    pass
-
-
-ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef = TypedDict(
-    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMembersInputListMembersPaginateTypeDef = TypedDict(
-    "_RequiredListMembersInputListMembersPaginateTypeDef",
-    {
-        "collaborationIdentifier": str,
-    },
-)
-_OptionalListMembersInputListMembersPaginateTypeDef = TypedDict(
-    "_OptionalListMembersInputListMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListMembersInputListMembersPaginateTypeDef(
-    _RequiredListMembersInputListMembersPaginateTypeDef,
-    _OptionalListMembersInputListMembersPaginateTypeDef,
-):
-    pass
-
-
-ListMembershipsInputListMembershipsPaginateTypeDef = TypedDict(
-    "ListMembershipsInputListMembershipsPaginateTypeDef",
-    {
-        "status": MembershipStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
-    "_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
-    {
-        "membershipIdentifier": str,
-    },
-)
-_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
-    "_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
-    {
-        "status": ProtectedQueryStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef(
-    _RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
-    _OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSchemasInputListSchemasPaginateTypeDef = TypedDict(
-    "_RequiredListSchemasInputListSchemasPaginateTypeDef",
-    {
-        "collaborationIdentifier": str,
-    },
-)
-_OptionalListSchemasInputListSchemasPaginateTypeDef = TypedDict(
-    "_OptionalListSchemasInputListSchemasPaginateTypeDef",
-    {
-        "schemaType": Literal["TABLE"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSchemasInputListSchemasPaginateTypeDef(
-    _RequiredListSchemasInputListSchemasPaginateTypeDef,
-    _OptionalListSchemasInputListSchemasPaginateTypeDef,
-):
-    pass
-
-
 ListMembersOutputTypeDef = TypedDict(
     "ListMembersOutputTypeDef",
     {
         "nextToken": str,
         "memberSummaries": List[MemberSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembershipsOutputTypeDef = TypedDict(
     "ListMembershipsOutputTypeDef",
     {
         "nextToken": str,
         "membershipSummaries": List[MembershipSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtectedQueriesOutputTypeDef = TypedDict(
     "ListProtectedQueriesOutputTypeDef",
     {
         "nextToken": str,
         "protectedQueries": List[ProtectedQuerySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasOutputTypeDef = TypedDict(
     "ListSchemasOutputTypeDef",
     {
         "schemaSummaries": List[SchemaSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProtectedQueryOutputConfigurationTypeDef = TypedDict(
     "ProtectedQueryOutputConfigurationTypeDef",
     {
         "s3": ProtectedQueryS3OutputConfigurationTypeDef,
@@ -1225,48 +1276,48 @@
     total=False,
 )
 
 CreateCollaborationOutputTypeDef = TypedDict(
     "CreateCollaborationOutputTypeDef",
     {
         "collaboration": CollaborationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCollaborationOutputTypeDef = TypedDict(
     "GetCollaborationOutputTypeDef",
     {
         "collaboration": CollaborationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCollaborationOutputTypeDef = TypedDict(
     "UpdateCollaborationOutputTypeDef",
     {
         "collaboration": CollaborationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetSchemaOutputTypeDef = TypedDict(
     "BatchGetSchemaOutputTypeDef",
     {
         "schemas": List[SchemaTypeDef],
         "errors": List[BatchGetSchemaErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSchemaOutputTypeDef = TypedDict(
     "GetSchemaOutputTypeDef",
     {
         "schema": SchemaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConfiguredTableTypeDef = TypedDict(
     "_RequiredConfiguredTableTypeDef",
     {
         "id": str,
@@ -1302,14 +1353,15 @@
         "analysisMethod": Literal["DIRECT_QUERY"],
     },
 )
 _OptionalCreateConfiguredTableInputRequestTypeDef = TypedDict(
     "_OptionalCreateConfiguredTableInputRequestTypeDef",
     {
         "description": str,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class CreateConfiguredTableInputRequestTypeDef(
     _RequiredCreateConfiguredTableInputRequestTypeDef,
@@ -1348,31 +1400,31 @@
     total=False,
 )
 
 CreateConfiguredTableOutputTypeDef = TypedDict(
     "CreateConfiguredTableOutputTypeDef",
     {
         "configuredTable": ConfiguredTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConfiguredTableOutputTypeDef = TypedDict(
     "GetConfiguredTableOutputTypeDef",
     {
         "configuredTable": ConfiguredTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfiguredTableOutputTypeDef = TypedDict(
     "UpdateConfiguredTableOutputTypeDef",
     {
         "configuredTable": ConfiguredTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartProtectedQueryInputRequestTypeDef = TypedDict(
     "StartProtectedQueryInputRequestTypeDef",
     {
         "type": Literal["SQL"],
@@ -1451,58 +1503,58 @@
     },
 )
 
 GetProtectedQueryOutputTypeDef = TypedDict(
     "GetProtectedQueryOutputTypeDef",
     {
         "protectedQuery": ProtectedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartProtectedQueryOutputTypeDef = TypedDict(
     "StartProtectedQueryOutputTypeDef",
     {
         "protectedQuery": ProtectedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProtectedQueryOutputTypeDef = TypedDict(
     "UpdateProtectedQueryOutputTypeDef",
     {
         "protectedQuery": ProtectedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSchemaAnalysisRuleOutputTypeDef = TypedDict(
     "GetSchemaAnalysisRuleOutputTypeDef",
     {
         "analysisRule": AnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConfiguredTableAnalysisRuleOutputTypeDef = TypedDict(
     "CreateConfiguredTableAnalysisRuleOutputTypeDef",
     {
         "analysisRule": ConfiguredTableAnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConfiguredTableAnalysisRuleOutputTypeDef = TypedDict(
     "GetConfiguredTableAnalysisRuleOutputTypeDef",
     {
         "analysisRule": ConfiguredTableAnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfiguredTableAnalysisRuleOutputTypeDef = TypedDict(
     "UpdateConfiguredTableAnalysisRuleOutputTypeDef",
     {
         "analysisRule": ConfiguredTableAnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms/type_defs.pyi` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_cleanrooms.type_defs import AggregateColumnTypeDef
 
     data: AggregateColumnTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Sequence
+from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AggregateFunctionNameType,
     AnalysisRuleTypeType,
     CollaborationQueryLogStatusType,
     ConfiguredTableAnalysisRuleTypeType,
     FilterableMemberStatusType,
@@ -41,15 +41,14 @@
 
 __all__ = (
     "AggregateColumnTypeDef",
     "AggregationConstraintTypeDef",
     "AnalysisRuleListTypeDef",
     "BatchGetSchemaErrorTypeDef",
     "BatchGetSchemaInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CollaborationSummaryTypeDef",
     "DataEncryptionMetadataTypeDef",
     "ColumnTypeDef",
     "ConfiguredTableAssociationSummaryTypeDef",
     "ConfiguredTableAssociationTypeDef",
     "ConfiguredTableSummaryTypeDef",
     "MemberSpecificationTypeDef",
@@ -67,31 +66,43 @@
     "GetConfiguredTableAssociationInputRequestTypeDef",
     "GetConfiguredTableInputRequestTypeDef",
     "GetMembershipInputRequestTypeDef",
     "GetProtectedQueryInputRequestTypeDef",
     "GetSchemaAnalysisRuleInputRequestTypeDef",
     "GetSchemaInputRequestTypeDef",
     "GlueTableReferenceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
     "ListCollaborationsInputRequestTypeDef",
+    "ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
     "ListConfiguredTableAssociationsInputRequestTypeDef",
+    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
     "ListConfiguredTablesInputRequestTypeDef",
+    "ListMembersInputListMembersPaginateTypeDef",
     "ListMembersInputRequestTypeDef",
     "MemberSummaryTypeDef",
+    "ListMembershipsInputListMembershipsPaginateTypeDef",
     "ListMembershipsInputRequestTypeDef",
     "MembershipSummaryTypeDef",
+    "ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
     "ListProtectedQueriesInputRequestTypeDef",
     "ProtectedQuerySummaryTypeDef",
+    "ListSchemasInputListSchemasPaginateTypeDef",
     "ListSchemasInputRequestTypeDef",
     "SchemaSummaryTypeDef",
+    "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "ProtectedQueryErrorTypeDef",
     "ProtectedQueryS3OutputConfigurationTypeDef",
     "ProtectedQueryS3OutputTypeDef",
     "ProtectedQuerySQLParametersTypeDef",
     "ProtectedQueryStatisticsTypeDef",
+    "ResponseMetadataTypeDef",
+    "TagResourceInputRequestTypeDef",
+    "UntagResourceInputRequestTypeDef",
     "UpdateCollaborationInputRequestTypeDef",
     "UpdateConfiguredTableAssociationInputRequestTypeDef",
     "UpdateConfiguredTableInputRequestTypeDef",
     "UpdateMembershipInputRequestTypeDef",
     "UpdateProtectedQueryInputRequestTypeDef",
     "AnalysisRuleAggregationTypeDef",
     "ListCollaborationsOutputTypeDef",
@@ -103,21 +114,14 @@
     "UpdateConfiguredTableAssociationOutputTypeDef",
     "ListConfiguredTablesOutputTypeDef",
     "CreateCollaborationInputRequestTypeDef",
     "CreateMembershipOutputTypeDef",
     "GetMembershipOutputTypeDef",
     "UpdateMembershipOutputTypeDef",
     "TableReferenceTypeDef",
-    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
-    "ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
-    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
-    "ListMembersInputListMembersPaginateTypeDef",
-    "ListMembershipsInputListMembershipsPaginateTypeDef",
-    "ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
-    "ListSchemasInputListSchemasPaginateTypeDef",
     "ListMembersOutputTypeDef",
     "ListMembershipsOutputTypeDef",
     "ListProtectedQueriesOutputTypeDef",
     "ListSchemasOutputTypeDef",
     "ProtectedQueryOutputConfigurationTypeDef",
     "ProtectedQueryOutputTypeDef",
     "AnalysisRulePolicyV1TypeDef",
@@ -189,25 +193,14 @@
     "BatchGetSchemaInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
         "names": Sequence[str],
     },
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
 _RequiredCollaborationSummaryTypeDef = TypedDict(
     "_RequiredCollaborationSummaryTypeDef",
     {
         "id": str,
         "arn": str,
         "name": str,
         "creatorAccountId": str,
@@ -322,31 +315,44 @@
         "roleArn": str,
     },
 )
 _OptionalCreateConfiguredTableAssociationInputRequestTypeDef = TypedDict(
     "_OptionalCreateConfiguredTableAssociationInputRequestTypeDef",
     {
         "description": str,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateConfiguredTableAssociationInputRequestTypeDef(
     _RequiredCreateConfiguredTableAssociationInputRequestTypeDef,
     _OptionalCreateConfiguredTableAssociationInputRequestTypeDef,
 ):
     pass
 
-CreateMembershipInputRequestTypeDef = TypedDict(
-    "CreateMembershipInputRequestTypeDef",
+_RequiredCreateMembershipInputRequestTypeDef = TypedDict(
+    "_RequiredCreateMembershipInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
         "queryLogStatus": MembershipQueryLogStatusType,
     },
 )
+_OptionalCreateMembershipInputRequestTypeDef = TypedDict(
+    "_OptionalCreateMembershipInputRequestTypeDef",
+    {
+        "tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+class CreateMembershipInputRequestTypeDef(
+    _RequiredCreateMembershipInputRequestTypeDef, _OptionalCreateMembershipInputRequestTypeDef
+):
+    pass
 
 MembershipTypeDef = TypedDict(
     "MembershipTypeDef",
     {
         "id": str,
         "arn": str,
         "collaborationArn": str,
@@ -473,34 +479,53 @@
     "GlueTableReferenceTypeDef",
     {
         "tableName": str,
         "databaseName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListCollaborationsInputListCollaborationsPaginateTypeDef = TypedDict(
+    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "memberStatus": FilterableMemberStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCollaborationsInputRequestTypeDef = TypedDict(
     "ListCollaborationsInputRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "memberStatus": FilterableMemberStatusType,
     },
     total=False,
 )
 
+_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
+    {
+        "membershipIdentifier": str,
+    },
+)
+_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef(
+    _RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
+    _OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListConfiguredTableAssociationsInputRequestTypeDef = TypedDict(
     "_RequiredListConfiguredTableAssociationsInputRequestTypeDef",
     {
         "membershipIdentifier": str,
     },
 )
 _OptionalListConfiguredTableAssociationsInputRequestTypeDef = TypedDict(
@@ -514,23 +539,51 @@
 
 class ListConfiguredTableAssociationsInputRequestTypeDef(
     _RequiredListConfiguredTableAssociationsInputRequestTypeDef,
     _OptionalListConfiguredTableAssociationsInputRequestTypeDef,
 ):
     pass
 
+ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef = TypedDict(
+    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConfiguredTablesInputRequestTypeDef = TypedDict(
     "ListConfiguredTablesInputRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListMembersInputListMembersPaginateTypeDef = TypedDict(
+    "_RequiredListMembersInputListMembersPaginateTypeDef",
+    {
+        "collaborationIdentifier": str,
+    },
+)
+_OptionalListMembersInputListMembersPaginateTypeDef = TypedDict(
+    "_OptionalListMembersInputListMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMembersInputListMembersPaginateTypeDef(
+    _RequiredListMembersInputListMembersPaginateTypeDef,
+    _OptionalListMembersInputListMembersPaginateTypeDef,
+):
+    pass
+
 _RequiredListMembersInputRequestTypeDef = TypedDict(
     "_RequiredListMembersInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
     },
 )
 _OptionalListMembersInputRequestTypeDef = TypedDict(
@@ -566,14 +619,23 @@
     },
     total=False,
 )
 
 class MemberSummaryTypeDef(_RequiredMemberSummaryTypeDef, _OptionalMemberSummaryTypeDef):
     pass
 
+ListMembershipsInputListMembershipsPaginateTypeDef = TypedDict(
+    "ListMembershipsInputListMembershipsPaginateTypeDef",
+    {
+        "status": MembershipStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMembershipsInputRequestTypeDef = TypedDict(
     "ListMembershipsInputRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "status": MembershipStatusType,
     },
@@ -593,14 +655,35 @@
         "createTime": datetime,
         "updateTime": datetime,
         "status": MembershipStatusType,
         "memberAbilities": List[MemberAbilityType],
     },
 )
 
+_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
+    "_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
+    {
+        "membershipIdentifier": str,
+    },
+)
+_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
+    "_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
+    {
+        "status": ProtectedQueryStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef(
+    _RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
+    _OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
+):
+    pass
+
 _RequiredListProtectedQueriesInputRequestTypeDef = TypedDict(
     "_RequiredListProtectedQueriesInputRequestTypeDef",
     {
         "membershipIdentifier": str,
     },
 )
 _OptionalListProtectedQueriesInputRequestTypeDef = TypedDict(
@@ -626,14 +709,35 @@
         "membershipId": str,
         "membershipArn": str,
         "createTime": datetime,
         "status": ProtectedQueryStatusType,
     },
 )
 
+_RequiredListSchemasInputListSchemasPaginateTypeDef = TypedDict(
+    "_RequiredListSchemasInputListSchemasPaginateTypeDef",
+    {
+        "collaborationIdentifier": str,
+    },
+)
+_OptionalListSchemasInputListSchemasPaginateTypeDef = TypedDict(
+    "_OptionalListSchemasInputListSchemasPaginateTypeDef",
+    {
+        "schemaType": Literal["TABLE"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSchemasInputListSchemasPaginateTypeDef(
+    _RequiredListSchemasInputListSchemasPaginateTypeDef,
+    _OptionalListSchemasInputListSchemasPaginateTypeDef,
+):
+    pass
+
 _RequiredListSchemasInputRequestTypeDef = TypedDict(
     "_RequiredListSchemasInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
     },
 )
 _OptionalListSchemasInputRequestTypeDef = TypedDict(
@@ -671,14 +775,39 @@
     },
     total=False,
 )
 
 class SchemaSummaryTypeDef(_RequiredSchemaSummaryTypeDef, _OptionalSchemaSummaryTypeDef):
     pass
 
+ListTagsForResourceInputRequestTypeDef = TypedDict(
+    "ListTagsForResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "tags": Dict[str, str],
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
 ProtectedQueryErrorTypeDef = TypedDict(
     "ProtectedQueryErrorTypeDef",
     {
         "message": str,
         "code": str,
     },
 )
@@ -722,14 +851,41 @@
     "ProtectedQueryStatisticsTypeDef",
     {
         "totalDurationInMillis": int,
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
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tags": Mapping[str, str],
+    },
+)
+
+UntagResourceInputRequestTypeDef = TypedDict(
+    "UntagResourceInputRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
+    },
+)
+
 _RequiredUpdateCollaborationInputRequestTypeDef = TypedDict(
     "_RequiredUpdateCollaborationInputRequestTypeDef",
     {
         "collaborationIdentifier": str,
     },
 )
 _OptionalUpdateCollaborationInputRequestTypeDef = TypedDict(
@@ -841,15 +997,15 @@
     pass
 
 ListCollaborationsOutputTypeDef = TypedDict(
     "ListCollaborationsOutputTypeDef",
     {
         "nextToken": str,
         "collaborationList": List[CollaborationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCollaborationTypeDef = TypedDict(
     "_RequiredCollaborationTypeDef",
     {
         "id": str,
@@ -905,48 +1061,48 @@
     pass
 
 ListConfiguredTableAssociationsOutputTypeDef = TypedDict(
     "ListConfiguredTableAssociationsOutputTypeDef",
     {
         "configuredTableAssociationSummaries": List[ConfiguredTableAssociationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConfiguredTableAssociationOutputTypeDef = TypedDict(
     "CreateConfiguredTableAssociationOutputTypeDef",
     {
         "configuredTableAssociation": ConfiguredTableAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConfiguredTableAssociationOutputTypeDef = TypedDict(
     "GetConfiguredTableAssociationOutputTypeDef",
     {
         "configuredTableAssociation": ConfiguredTableAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfiguredTableAssociationOutputTypeDef = TypedDict(
     "UpdateConfiguredTableAssociationOutputTypeDef",
     {
         "configuredTableAssociation": ConfiguredTableAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConfiguredTablesOutputTypeDef = TypedDict(
     "ListConfiguredTablesOutputTypeDef",
     {
         "configuredTableSummaries": List[ConfiguredTableSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCollaborationInputRequestTypeDef = TypedDict(
     "_RequiredCreateCollaborationInputRequestTypeDef",
     {
         "members": Sequence[MemberSpecificationTypeDef],
@@ -957,196 +1113,89 @@
         "queryLogStatus": CollaborationQueryLogStatusType,
     },
 )
 _OptionalCreateCollaborationInputRequestTypeDef = TypedDict(
     "_OptionalCreateCollaborationInputRequestTypeDef",
     {
         "dataEncryptionMetadata": DataEncryptionMetadataTypeDef,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateCollaborationInputRequestTypeDef(
     _RequiredCreateCollaborationInputRequestTypeDef, _OptionalCreateCollaborationInputRequestTypeDef
 ):
     pass
 
 CreateMembershipOutputTypeDef = TypedDict(
     "CreateMembershipOutputTypeDef",
     {
         "membership": MembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMembershipOutputTypeDef = TypedDict(
     "GetMembershipOutputTypeDef",
     {
         "membership": MembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMembershipOutputTypeDef = TypedDict(
     "UpdateMembershipOutputTypeDef",
     {
         "membership": MembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TableReferenceTypeDef = TypedDict(
     "TableReferenceTypeDef",
     {
         "glue": GlueTableReferenceTypeDef,
     },
     total=False,
 )
 
-ListCollaborationsInputListCollaborationsPaginateTypeDef = TypedDict(
-    "ListCollaborationsInputListCollaborationsPaginateTypeDef",
-    {
-        "memberStatus": FilterableMemberStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
-    {
-        "membershipIdentifier": str,
-    },
-)
-_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef(
-    _RequiredListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
-    _OptionalListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
-):
-    pass
-
-ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef = TypedDict(
-    "ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMembersInputListMembersPaginateTypeDef = TypedDict(
-    "_RequiredListMembersInputListMembersPaginateTypeDef",
-    {
-        "collaborationIdentifier": str,
-    },
-)
-_OptionalListMembersInputListMembersPaginateTypeDef = TypedDict(
-    "_OptionalListMembersInputListMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListMembersInputListMembersPaginateTypeDef(
-    _RequiredListMembersInputListMembersPaginateTypeDef,
-    _OptionalListMembersInputListMembersPaginateTypeDef,
-):
-    pass
-
-ListMembershipsInputListMembershipsPaginateTypeDef = TypedDict(
-    "ListMembershipsInputListMembershipsPaginateTypeDef",
-    {
-        "status": MembershipStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
-    "_RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
-    {
-        "membershipIdentifier": str,
-    },
-)
-_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef = TypedDict(
-    "_OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef",
-    {
-        "status": ProtectedQueryStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef(
-    _RequiredListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
-    _OptionalListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
-):
-    pass
-
-_RequiredListSchemasInputListSchemasPaginateTypeDef = TypedDict(
-    "_RequiredListSchemasInputListSchemasPaginateTypeDef",
-    {
-        "collaborationIdentifier": str,
-    },
-)
-_OptionalListSchemasInputListSchemasPaginateTypeDef = TypedDict(
-    "_OptionalListSchemasInputListSchemasPaginateTypeDef",
-    {
-        "schemaType": Literal["TABLE"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSchemasInputListSchemasPaginateTypeDef(
-    _RequiredListSchemasInputListSchemasPaginateTypeDef,
-    _OptionalListSchemasInputListSchemasPaginateTypeDef,
-):
-    pass
-
 ListMembersOutputTypeDef = TypedDict(
     "ListMembersOutputTypeDef",
     {
         "nextToken": str,
         "memberSummaries": List[MemberSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembershipsOutputTypeDef = TypedDict(
     "ListMembershipsOutputTypeDef",
     {
         "nextToken": str,
         "membershipSummaries": List[MembershipSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtectedQueriesOutputTypeDef = TypedDict(
     "ListProtectedQueriesOutputTypeDef",
     {
         "nextToken": str,
         "protectedQueries": List[ProtectedQuerySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasOutputTypeDef = TypedDict(
     "ListSchemasOutputTypeDef",
     {
         "schemaSummaries": List[SchemaSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProtectedQueryOutputConfigurationTypeDef = TypedDict(
     "ProtectedQueryOutputConfigurationTypeDef",
     {
         "s3": ProtectedQueryS3OutputConfigurationTypeDef,
@@ -1180,48 +1229,48 @@
     total=False,
 )
 
 CreateCollaborationOutputTypeDef = TypedDict(
     "CreateCollaborationOutputTypeDef",
     {
         "collaboration": CollaborationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCollaborationOutputTypeDef = TypedDict(
     "GetCollaborationOutputTypeDef",
     {
         "collaboration": CollaborationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCollaborationOutputTypeDef = TypedDict(
     "UpdateCollaborationOutputTypeDef",
     {
         "collaboration": CollaborationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetSchemaOutputTypeDef = TypedDict(
     "BatchGetSchemaOutputTypeDef",
     {
         "schemas": List[SchemaTypeDef],
         "errors": List[BatchGetSchemaErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSchemaOutputTypeDef = TypedDict(
     "GetSchemaOutputTypeDef",
     {
         "schema": SchemaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConfiguredTableTypeDef = TypedDict(
     "_RequiredConfiguredTableTypeDef",
     {
         "id": str,
@@ -1255,14 +1304,15 @@
         "analysisMethod": Literal["DIRECT_QUERY"],
     },
 )
 _OptionalCreateConfiguredTableInputRequestTypeDef = TypedDict(
     "_OptionalCreateConfiguredTableInputRequestTypeDef",
     {
         "description": str,
+        "tags": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateConfiguredTableInputRequestTypeDef(
     _RequiredCreateConfiguredTableInputRequestTypeDef,
     _OptionalCreateConfiguredTableInputRequestTypeDef,
@@ -1299,31 +1349,31 @@
     total=False,
 )
 
 CreateConfiguredTableOutputTypeDef = TypedDict(
     "CreateConfiguredTableOutputTypeDef",
     {
         "configuredTable": ConfiguredTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConfiguredTableOutputTypeDef = TypedDict(
     "GetConfiguredTableOutputTypeDef",
     {
         "configuredTable": ConfiguredTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfiguredTableOutputTypeDef = TypedDict(
     "UpdateConfiguredTableOutputTypeDef",
     {
         "configuredTable": ConfiguredTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartProtectedQueryInputRequestTypeDef = TypedDict(
     "StartProtectedQueryInputRequestTypeDef",
     {
         "type": Literal["SQL"],
@@ -1400,58 +1450,58 @@
     },
 )
 
 GetProtectedQueryOutputTypeDef = TypedDict(
     "GetProtectedQueryOutputTypeDef",
     {
         "protectedQuery": ProtectedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartProtectedQueryOutputTypeDef = TypedDict(
     "StartProtectedQueryOutputTypeDef",
     {
         "protectedQuery": ProtectedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProtectedQueryOutputTypeDef = TypedDict(
     "UpdateProtectedQueryOutputTypeDef",
     {
         "protectedQuery": ProtectedQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSchemaAnalysisRuleOutputTypeDef = TypedDict(
     "GetSchemaAnalysisRuleOutputTypeDef",
     {
         "analysisRule": AnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateConfiguredTableAnalysisRuleOutputTypeDef = TypedDict(
     "CreateConfiguredTableAnalysisRuleOutputTypeDef",
     {
         "analysisRule": ConfiguredTableAnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConfiguredTableAnalysisRuleOutputTypeDef = TypedDict(
     "GetConfiguredTableAnalysisRuleOutputTypeDef",
     {
         "analysisRule": ConfiguredTableAnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateConfiguredTableAnalysisRuleOutputTypeDef = TypedDict(
     "UpdateConfiguredTableAnalysisRuleOutputTypeDef",
     {
         "analysisRule": ConfiguredTableAnalysisRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/PKG-INFO` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cleanrooms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CleanRoomsService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CleanRoomsService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cleanrooms"></a>
 
 # types-aiobotocore-cleanrooms
 
 [![PyPI - types-aiobotocore-cleanrooms](https://img.shields.io/pypi/v/types-aiobotocore-cleanrooms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cleanrooms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cleanrooms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cleanrooms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cleanrooms?color=blue)](https://pypistats.org/packages/types-aiobotocore-cleanrooms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CleanRoomsService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService)
+[aiobotocore.CleanRoomsService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cleanrooms.html#CleanRoomsService)
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
 [types-aiobotocore-cleanrooms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cleanrooms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -365,15 +365,14 @@
 ```python
 from types_aiobotocore_cleanrooms.type_defs import (
     AggregateColumnTypeDef,
     AggregationConstraintTypeDef,
     AnalysisRuleListTypeDef,
     BatchGetSchemaErrorTypeDef,
     BatchGetSchemaInputRequestTypeDef,
-    ResponseMetadataTypeDef,
     CollaborationSummaryTypeDef,
     DataEncryptionMetadataTypeDef,
     ColumnTypeDef,
     ConfiguredTableAssociationSummaryTypeDef,
     ConfiguredTableAssociationTypeDef,
     ConfiguredTableSummaryTypeDef,
     MemberSpecificationTypeDef,
@@ -391,31 +390,43 @@
     GetConfiguredTableAssociationInputRequestTypeDef,
     GetConfiguredTableInputRequestTypeDef,
     GetMembershipInputRequestTypeDef,
     GetProtectedQueryInputRequestTypeDef,
     GetSchemaAnalysisRuleInputRequestTypeDef,
     GetSchemaInputRequestTypeDef,
     GlueTableReferenceTypeDef,
-    PaginatorConfigTypeDef,
+    ListCollaborationsInputListCollaborationsPaginateTypeDef,
     ListCollaborationsInputRequestTypeDef,
+    ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
     ListConfiguredTableAssociationsInputRequestTypeDef,
+    ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef,
     ListConfiguredTablesInputRequestTypeDef,
+    ListMembersInputListMembersPaginateTypeDef,
     ListMembersInputRequestTypeDef,
     MemberSummaryTypeDef,
+    ListMembershipsInputListMembershipsPaginateTypeDef,
     ListMembershipsInputRequestTypeDef,
     MembershipSummaryTypeDef,
+    ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
     ListProtectedQueriesInputRequestTypeDef,
     ProtectedQuerySummaryTypeDef,
+    ListSchemasInputListSchemasPaginateTypeDef,
     ListSchemasInputRequestTypeDef,
     SchemaSummaryTypeDef,
+    ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    PaginatorConfigTypeDef,
     ProtectedQueryErrorTypeDef,
     ProtectedQueryS3OutputConfigurationTypeDef,
     ProtectedQueryS3OutputTypeDef,
     ProtectedQuerySQLParametersTypeDef,
     ProtectedQueryStatisticsTypeDef,
+    ResponseMetadataTypeDef,
+    TagResourceInputRequestTypeDef,
+    UntagResourceInputRequestTypeDef,
     UpdateCollaborationInputRequestTypeDef,
     UpdateConfiguredTableAssociationInputRequestTypeDef,
     UpdateConfiguredTableInputRequestTypeDef,
     UpdateMembershipInputRequestTypeDef,
     UpdateProtectedQueryInputRequestTypeDef,
     AnalysisRuleAggregationTypeDef,
     ListCollaborationsOutputTypeDef,
@@ -427,21 +438,14 @@
     UpdateConfiguredTableAssociationOutputTypeDef,
     ListConfiguredTablesOutputTypeDef,
     CreateCollaborationInputRequestTypeDef,
     CreateMembershipOutputTypeDef,
     GetMembershipOutputTypeDef,
     UpdateMembershipOutputTypeDef,
     TableReferenceTypeDef,
-    ListCollaborationsInputListCollaborationsPaginateTypeDef,
-    ListConfiguredTableAssociationsInputListConfiguredTableAssociationsPaginateTypeDef,
-    ListConfiguredTablesInputListConfiguredTablesPaginateTypeDef,
-    ListMembersInputListMembersPaginateTypeDef,
-    ListMembershipsInputListMembershipsPaginateTypeDef,
-    ListProtectedQueriesInputListProtectedQueriesPaginateTypeDef,
-    ListSchemasInputListSchemasPaginateTypeDef,
     ListMembersOutputTypeDef,
     ListMembershipsOutputTypeDef,
     ListProtectedQueriesOutputTypeDef,
     ListSchemasOutputTypeDef,
     ProtectedQueryOutputConfigurationTypeDef,
     ProtectedQueryOutputTypeDef,
     AnalysisRulePolicyV1TypeDef,
@@ -483,43 +487,43 @@
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

### Comparing `types-aiobotocore-cleanrooms-2.5.0.post1/types_aiobotocore_cleanrooms.egg-info/SOURCES.txt` & `types-aiobotocore-cleanrooms-2.5.1/types_aiobotocore_cleanrooms.egg-info/SOURCES.txt`

 * *Files identical despite different names*

