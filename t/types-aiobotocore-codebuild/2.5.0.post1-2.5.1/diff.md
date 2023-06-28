# Comparing `tmp/types-aiobotocore-codebuild-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codebuild-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codebuild-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:22 2023, max compression
+gzip compressed data, was "types-aiobotocore-codebuild-2.5.1.tar", last modified: Wed Jun 28 01:43:15 2023, max compression
```

## Comparing `types-aiobotocore-codebuild-2.5.0.post1.tar` & `types-aiobotocore-codebuild-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.363048 types-aiobotocore-codebuild-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21521 2023-03-11 12:26:22.359048 types-aiobotocore-codebuild-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19942 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:22.363048 types-aiobotocore-codebuild-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:11:08.000000 types-aiobotocore-codebuild-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.359048 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/
--rw-r--r--   0 runner    (1001) docker     (123)     3083 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3082 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    43760 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    43694 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13821 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13819 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    16070 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    16055 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    57199 2023-03-11 12:11:11.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    57140 2023-03-11 12:11:10.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:09.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.359048 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21521 2023-03-11 12:26:22.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:26:22.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:22.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:22.000000 types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.662111 types-aiobotocore-codebuild-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21515 2023-06-28 01:43:15.658111 types-aiobotocore-codebuild-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19942 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:15.662111 types-aiobotocore-codebuild-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.658111 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/
+-rw-r--r--   0 runner    (1001) docker     (123)     3083 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3082 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43759 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43693 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14108 2023-06-28 01:27:46.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14106 2023-06-28 01:27:46.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15998 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15984 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    57301 2023-06-28 01:27:47.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    57242 2023-06-28 01:27:47.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:45.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.658111 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21515 2023-06-28 01:43:15.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:43:15.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:15.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:15.000000 types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/LICENSE` & `types-aiobotocore-codebuild-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codebuild-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codebuild
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeBuild 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeBuild 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codebuild"></a>
 
 # types-aiobotocore-codebuild
 
 [![PyPI - types-aiobotocore-codebuild](https://img.shields.io/pypi/v/types-aiobotocore-codebuild.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codebuild)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codebuild.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codebuild)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codebuild?color=blue)](https://pypistats.org/packages/types-aiobotocore-codebuild)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeBuild 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild)
+[aiobotocore.CodeBuild 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild)
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
 [types-aiobotocore-codebuild docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/).
 
 See how it helps to find and fix potential bugs:
 
@@ -407,15 +407,14 @@
 `types_aiobotocore_codebuild.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codebuild.type_defs import (
     BatchDeleteBuildsInputRequestTypeDef,
     BuildNotDeletedTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetBuildBatchesInputRequestTypeDef,
     BatchGetBuildsInputRequestTypeDef,
     BatchGetProjectsInputRequestTypeDef,
     BatchGetReportGroupsInputRequestTypeDef,
     BatchGetReportsInputRequestTypeDef,
     BatchRestrictionsTypeDef,
     BuildArtifactsTypeDef,
@@ -438,84 +437,85 @@
     WebhookFilterTypeDef,
     DeleteBuildBatchInputRequestTypeDef,
     DeleteProjectInputRequestTypeDef,
     DeleteReportGroupInputRequestTypeDef,
     DeleteReportInputRequestTypeDef,
     DeleteResourcePolicyInputRequestTypeDef,
     DeleteSourceCredentialsInputRequestTypeDef,
+    DeleteSourceCredentialsOutputTypeDef,
     DeleteWebhookInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
     DescribeCodeCoveragesInputRequestTypeDef,
     TestCaseFilterTypeDef,
     TestCaseTypeDef,
     EnvironmentImageTypeDef,
     EnvironmentVariableTypeDef,
     GetReportGroupTrendInputRequestTypeDef,
     ReportGroupTrendStatsTypeDef,
     ReportWithRawDataTypeDef,
     GetResourcePolicyInputRequestTypeDef,
+    GetResourcePolicyOutputTypeDef,
     GitSubmodulesConfigTypeDef,
     ImportSourceCredentialsInputRequestTypeDef,
+    ImportSourceCredentialsOutputTypeDef,
     InvalidateProjectCacheInputRequestTypeDef,
+    ListBuildBatchesForProjectOutputTypeDef,
+    ListBuildBatchesOutputTypeDef,
+    ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
     ListBuildsForProjectInputRequestTypeDef,
+    ListBuildsForProjectOutputTypeDef,
+    ListBuildsInputListBuildsPaginateTypeDef,
     ListBuildsInputRequestTypeDef,
+    ListBuildsOutputTypeDef,
+    ListProjectsInputListProjectsPaginateTypeDef,
     ListProjectsInputRequestTypeDef,
+    ListProjectsOutputTypeDef,
+    ListReportGroupsInputListReportGroupsPaginateTypeDef,
     ListReportGroupsInputRequestTypeDef,
+    ListReportGroupsOutputTypeDef,
     ReportFilterTypeDef,
+    ListReportsForReportGroupOutputTypeDef,
+    ListReportsOutputTypeDef,
+    ListSharedProjectsInputListSharedProjectsPaginateTypeDef,
     ListSharedProjectsInputRequestTypeDef,
+    ListSharedProjectsOutputTypeDef,
+    ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef,
     ListSharedReportGroupsInputRequestTypeDef,
+    ListSharedReportGroupsOutputTypeDef,
     SourceCredentialsInfoTypeDef,
     S3LogsConfigTypeDef,
+    PaginatorConfigTypeDef,
     ProjectBadgeTypeDef,
     RegistryCredentialTypeDef,
     SourceAuthTypeDef,
     PutResourcePolicyInputRequestTypeDef,
+    PutResourcePolicyOutputTypeDef,
     S3ReportExportConfigTypeDef,
     TestReportSummaryTypeDef,
+    ResponseMetadataTypeDef,
     RetryBuildBatchInputRequestTypeDef,
     RetryBuildInputRequestTypeDef,
     StopBuildBatchInputRequestTypeDef,
     StopBuildInputRequestTypeDef,
     UpdateProjectVisibilityInputRequestTypeDef,
+    UpdateProjectVisibilityOutputTypeDef,
     BatchDeleteBuildsOutputTypeDef,
     DeleteBuildBatchOutputTypeDef,
-    DeleteSourceCredentialsOutputTypeDef,
-    GetResourcePolicyOutputTypeDef,
-    ImportSourceCredentialsOutputTypeDef,
-    ListBuildBatchesForProjectOutputTypeDef,
-    ListBuildBatchesOutputTypeDef,
-    ListBuildsForProjectOutputTypeDef,
-    ListBuildsOutputTypeDef,
-    ListProjectsOutputTypeDef,
-    ListReportGroupsOutputTypeDef,
-    ListReportsForReportGroupOutputTypeDef,
-    ListReportsOutputTypeDef,
-    ListSharedProjectsOutputTypeDef,
-    ListSharedReportGroupsOutputTypeDef,
-    PutResourcePolicyOutputTypeDef,
-    UpdateProjectVisibilityOutputTypeDef,
     ProjectBuildBatchConfigTypeDef,
+    ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef,
     ListBuildBatchesForProjectInputRequestTypeDef,
+    ListBuildBatchesInputListBuildBatchesPaginateTypeDef,
     ListBuildBatchesInputRequestTypeDef,
     BuildBatchPhaseTypeDef,
     BuildPhaseTypeDef,
     BuildSummaryTypeDef,
     DescribeCodeCoveragesOutputTypeDef,
     CreateWebhookInputRequestTypeDef,
     UpdateWebhookInputRequestTypeDef,
     WebhookTypeDef,
-    DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
-    ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef,
-    ListBuildBatchesInputListBuildBatchesPaginateTypeDef,
-    ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
-    ListBuildsInputListBuildsPaginateTypeDef,
-    ListProjectsInputListProjectsPaginateTypeDef,
-    ListReportGroupsInputListReportGroupsPaginateTypeDef,
-    ListSharedProjectsInputListSharedProjectsPaginateTypeDef,
-    ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef,
     DescribeTestCasesInputDescribeTestCasesPaginateTypeDef,
     DescribeTestCasesInputRequestTypeDef,
     DescribeTestCasesOutputTypeDef,
     EnvironmentLanguageTypeDef,
     GetReportGroupTrendOutputTypeDef,
     ListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef,
     ListReportsForReportGroupInputRequestTypeDef,
@@ -568,43 +568,43 @@
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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/README.md` & `types-aiobotocore-codebuild-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codebuild"></a>
 
 # types-aiobotocore-codebuild
 
 [![PyPI - types-aiobotocore-codebuild](https://img.shields.io/pypi/v/types-aiobotocore-codebuild.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codebuild)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codebuild.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codebuild)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codebuild?color=blue)](https://pypistats.org/packages/types-aiobotocore-codebuild)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeBuild 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild)
+[aiobotocore.CodeBuild 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild)
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
 [types-aiobotocore-codebuild docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/).
 
 See how it helps to find and fix potential bugs:
 
@@ -374,15 +374,14 @@
 `types_aiobotocore_codebuild.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codebuild.type_defs import (
     BatchDeleteBuildsInputRequestTypeDef,
     BuildNotDeletedTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetBuildBatchesInputRequestTypeDef,
     BatchGetBuildsInputRequestTypeDef,
     BatchGetProjectsInputRequestTypeDef,
     BatchGetReportGroupsInputRequestTypeDef,
     BatchGetReportsInputRequestTypeDef,
     BatchRestrictionsTypeDef,
     BuildArtifactsTypeDef,
@@ -405,84 +404,85 @@
     WebhookFilterTypeDef,
     DeleteBuildBatchInputRequestTypeDef,
     DeleteProjectInputRequestTypeDef,
     DeleteReportGroupInputRequestTypeDef,
     DeleteReportInputRequestTypeDef,
     DeleteResourcePolicyInputRequestTypeDef,
     DeleteSourceCredentialsInputRequestTypeDef,
+    DeleteSourceCredentialsOutputTypeDef,
     DeleteWebhookInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
     DescribeCodeCoveragesInputRequestTypeDef,
     TestCaseFilterTypeDef,
     TestCaseTypeDef,
     EnvironmentImageTypeDef,
     EnvironmentVariableTypeDef,
     GetReportGroupTrendInputRequestTypeDef,
     ReportGroupTrendStatsTypeDef,
     ReportWithRawDataTypeDef,
     GetResourcePolicyInputRequestTypeDef,
+    GetResourcePolicyOutputTypeDef,
     GitSubmodulesConfigTypeDef,
     ImportSourceCredentialsInputRequestTypeDef,
+    ImportSourceCredentialsOutputTypeDef,
     InvalidateProjectCacheInputRequestTypeDef,
+    ListBuildBatchesForProjectOutputTypeDef,
+    ListBuildBatchesOutputTypeDef,
+    ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
     ListBuildsForProjectInputRequestTypeDef,
+    ListBuildsForProjectOutputTypeDef,
+    ListBuildsInputListBuildsPaginateTypeDef,
     ListBuildsInputRequestTypeDef,
+    ListBuildsOutputTypeDef,
+    ListProjectsInputListProjectsPaginateTypeDef,
     ListProjectsInputRequestTypeDef,
+    ListProjectsOutputTypeDef,
+    ListReportGroupsInputListReportGroupsPaginateTypeDef,
     ListReportGroupsInputRequestTypeDef,
+    ListReportGroupsOutputTypeDef,
     ReportFilterTypeDef,
+    ListReportsForReportGroupOutputTypeDef,
+    ListReportsOutputTypeDef,
+    ListSharedProjectsInputListSharedProjectsPaginateTypeDef,
     ListSharedProjectsInputRequestTypeDef,
+    ListSharedProjectsOutputTypeDef,
+    ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef,
     ListSharedReportGroupsInputRequestTypeDef,
+    ListSharedReportGroupsOutputTypeDef,
     SourceCredentialsInfoTypeDef,
     S3LogsConfigTypeDef,
+    PaginatorConfigTypeDef,
     ProjectBadgeTypeDef,
     RegistryCredentialTypeDef,
     SourceAuthTypeDef,
     PutResourcePolicyInputRequestTypeDef,
+    PutResourcePolicyOutputTypeDef,
     S3ReportExportConfigTypeDef,
     TestReportSummaryTypeDef,
+    ResponseMetadataTypeDef,
     RetryBuildBatchInputRequestTypeDef,
     RetryBuildInputRequestTypeDef,
     StopBuildBatchInputRequestTypeDef,
     StopBuildInputRequestTypeDef,
     UpdateProjectVisibilityInputRequestTypeDef,
+    UpdateProjectVisibilityOutputTypeDef,
     BatchDeleteBuildsOutputTypeDef,
     DeleteBuildBatchOutputTypeDef,
-    DeleteSourceCredentialsOutputTypeDef,
-    GetResourcePolicyOutputTypeDef,
-    ImportSourceCredentialsOutputTypeDef,
-    ListBuildBatchesForProjectOutputTypeDef,
-    ListBuildBatchesOutputTypeDef,
-    ListBuildsForProjectOutputTypeDef,
-    ListBuildsOutputTypeDef,
-    ListProjectsOutputTypeDef,
-    ListReportGroupsOutputTypeDef,
-    ListReportsForReportGroupOutputTypeDef,
-    ListReportsOutputTypeDef,
-    ListSharedProjectsOutputTypeDef,
-    ListSharedReportGroupsOutputTypeDef,
-    PutResourcePolicyOutputTypeDef,
-    UpdateProjectVisibilityOutputTypeDef,
     ProjectBuildBatchConfigTypeDef,
+    ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef,
     ListBuildBatchesForProjectInputRequestTypeDef,
+    ListBuildBatchesInputListBuildBatchesPaginateTypeDef,
     ListBuildBatchesInputRequestTypeDef,
     BuildBatchPhaseTypeDef,
     BuildPhaseTypeDef,
     BuildSummaryTypeDef,
     DescribeCodeCoveragesOutputTypeDef,
     CreateWebhookInputRequestTypeDef,
     UpdateWebhookInputRequestTypeDef,
     WebhookTypeDef,
-    DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
-    ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef,
-    ListBuildBatchesInputListBuildBatchesPaginateTypeDef,
-    ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
-    ListBuildsInputListBuildsPaginateTypeDef,
-    ListProjectsInputListProjectsPaginateTypeDef,
-    ListReportGroupsInputListReportGroupsPaginateTypeDef,
-    ListSharedProjectsInputListSharedProjectsPaginateTypeDef,
-    ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef,
     DescribeTestCasesInputDescribeTestCasesPaginateTypeDef,
     DescribeTestCasesInputRequestTypeDef,
     DescribeTestCasesOutputTypeDef,
     EnvironmentLanguageTypeDef,
     GetReportGroupTrendOutputTypeDef,
     ListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef,
     ListReportsForReportGroupInputRequestTypeDef,
@@ -535,43 +535,43 @@
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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/setup.py` & `types-aiobotocore-codebuild-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codebuild.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codebuild",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codebuild"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeBuild 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.CodeBuild 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/"
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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/__init__.py` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/__init__.pyi` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/__main__.py` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeBuild 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeBuild 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild\nOther"
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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/client.py` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -554,15 +554,15 @@
         reportGroupArn: str,
         nextToken: str = ...,
         sortOrder: SortOrderTypeType = ...,
         maxResults: int = ...,
         filter: ReportFilterTypeDef = ...
     ) -> ListReportsForReportGroupOutputTypeDef:
         """
-        Returns a list of ARNs for the reports that belong to a `ReportGroup` .
+        Returns a list of ARNs for the reports that belong to a `ReportGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Client.list_reports_for_report_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/client/#list_reports_for_report_group)
         """
 
     async def list_shared_projects(
         self,
```

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/client.pyi` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -516,15 +516,15 @@
         reportGroupArn: str,
         nextToken: str = ...,
         sortOrder: SortOrderTypeType = ...,
         maxResults: int = ...,
         filter: ReportFilterTypeDef = ...
     ) -> ListReportsForReportGroupOutputTypeDef:
         """
-        Returns a list of ARNs for the reports that belong to a `ReportGroup` .
+        Returns a list of ARNs for the reports that belong to a `ReportGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Client.list_reports_for_report_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/client/#list_reports_for_report_group)
         """
     async def list_shared_projects(
         self,
         *,
```

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/literals.py` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -234,14 +234,15 @@
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
@@ -320,14 +321,15 @@
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
@@ -338,14 +340,15 @@
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
@@ -381,14 +384,15 @@
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
@@ -407,16 +411,19 @@
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
@@ -500,15 +507,17 @@
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
@@ -547,21 +556,25 @@
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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/literals.pyi` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -232,14 +232,15 @@
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
@@ -318,14 +319,15 @@
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
@@ -336,14 +338,15 @@
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
@@ -379,14 +382,15 @@
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
@@ -405,16 +409,19 @@
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
@@ -498,15 +505,17 @@
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
@@ -545,21 +554,25 @@
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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/paginator.py` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -38,16 +38,15 @@
         list_report_groups_paginator: ListReportGroupsPaginator = client.get_paginator("list_report_groups")
         list_reports_paginator: ListReportsPaginator = client.get_paginator("list_reports")
         list_reports_for_report_group_paginator: ListReportsForReportGroupPaginator = client.get_paginator("list_reports_for_report_group")
         list_shared_projects_paginator: ListSharedProjectsPaginator = client.get_paginator("list_shared_projects")
         list_shared_report_groups_paginator: ListSharedReportGroupsPaginator = client.get_paginator("list_shared_report_groups")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ProjectSortByTypeType,
     ReportCodeCoverageSortByTypeType,
@@ -70,20 +69,14 @@
     ListSharedProjectsOutputTypeDef,
     ListSharedReportGroupsOutputTypeDef,
     PaginatorConfigTypeDef,
     ReportFilterTypeDef,
     TestCaseFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeCodeCoveragesPaginator",
     "DescribeTestCasesPaginator",
     "ListBuildBatchesPaginator",
     "ListBuildBatchesForProjectPaginator",
     "ListBuildsPaginator",
     "ListBuildsForProjectPaginator",
@@ -116,15 +109,15 @@
         self,
         *,
         reportArn: str,
         sortOrder: SortOrderTypeType = ...,
         sortBy: ReportCodeCoverageSortByTypeType = ...,
         minLineCoveragePercentage: float = ...,
         maxLineCoveragePercentage: float = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCodeCoveragesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.DescribeCodeCoverages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#describecodecoveragespaginator)
         """
 
 
@@ -135,15 +128,15 @@
     """
 
     def paginate(
         self,
         *,
         reportArn: str,
         filter: TestCaseFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTestCasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.DescribeTestCases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#describetestcasespaginator)
         """
 
 
@@ -154,15 +147,15 @@
     """
 
     def paginate(
         self,
         *,
         filter: BuildBatchFilterTypeDef = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildBatchesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuildBatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildbatchespaginator)
         """
 
 
@@ -174,30 +167,33 @@
 
     def paginate(
         self,
         *,
         projectName: str = ...,
         filter: BuildBatchFilterTypeDef = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildBatchesForProjectOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuildBatchesForProject.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildbatchesforprojectpaginator)
         """
 
 
 class ListBuildsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuilds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildspaginator)
     """
 
     def paginate(
-        self, *, sortOrder: SortOrderTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        sortOrder: SortOrderTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuilds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildspaginator)
         """
 
 
@@ -208,15 +204,15 @@
     """
 
     def paginate(
         self,
         *,
         projectName: str,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildsForProjectOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuildsForProject.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildsforprojectpaginator)
         """
 
 
@@ -227,15 +223,15 @@
     """
 
     def paginate(
         self,
         *,
         sortBy: ProjectSortByTypeType = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listprojectspaginator)
         """
 
 
@@ -246,15 +242,15 @@
     """
 
     def paginate(
         self,
         *,
         sortOrder: SortOrderTypeType = ...,
         sortBy: ReportGroupSortByTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListReportGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listreportgroupspaginator)
         """
 
 
@@ -265,15 +261,15 @@
     """
 
     def paginate(
         self,
         *,
         sortOrder: SortOrderTypeType = ...,
         filter: ReportFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listreportspaginator)
         """
 
 
@@ -285,15 +281,15 @@
 
     def paginate(
         self,
         *,
         reportGroupArn: str,
         sortOrder: SortOrderTypeType = ...,
         filter: ReportFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportsForReportGroupOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListReportsForReportGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listreportsforreportgrouppaginator)
         """
 
 
@@ -304,15 +300,15 @@
     """
 
     def paginate(
         self,
         *,
         sortBy: SharedResourceSortByTypeType = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSharedProjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListSharedProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listsharedprojectspaginator)
         """
 
 
@@ -323,13 +319,13 @@
     """
 
     def paginate(
         self,
         *,
         sortOrder: SortOrderTypeType = ...,
         sortBy: SharedResourceSortByTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSharedReportGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListSharedReportGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listsharedreportgroupspaginator)
         """
```

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/paginator.pyi` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -38,16 +38,15 @@
         list_report_groups_paginator: ListReportGroupsPaginator = client.get_paginator("list_report_groups")
         list_reports_paginator: ListReportsPaginator = client.get_paginator("list_reports")
         list_reports_for_report_group_paginator: ListReportsForReportGroupPaginator = client.get_paginator("list_reports_for_report_group")
         list_shared_projects_paginator: ListSharedProjectsPaginator = client.get_paginator("list_shared_projects")
         list_shared_report_groups_paginator: ListSharedReportGroupsPaginator = client.get_paginator("list_shared_report_groups")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ProjectSortByTypeType,
     ReportCodeCoverageSortByTypeType,
@@ -70,19 +69,14 @@
     ListSharedProjectsOutputTypeDef,
     ListSharedReportGroupsOutputTypeDef,
     PaginatorConfigTypeDef,
     ReportFilterTypeDef,
     TestCaseFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeCodeCoveragesPaginator",
     "DescribeTestCasesPaginator",
     "ListBuildBatchesPaginator",
     "ListBuildBatchesForProjectPaginator",
     "ListBuildsPaginator",
     "ListBuildsForProjectPaginator",
@@ -112,15 +106,15 @@
         self,
         *,
         reportArn: str,
         sortOrder: SortOrderTypeType = ...,
         sortBy: ReportCodeCoverageSortByTypeType = ...,
         minLineCoveragePercentage: float = ...,
         maxLineCoveragePercentage: float = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCodeCoveragesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.DescribeCodeCoverages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#describecodecoveragespaginator)
         """
 
 class DescribeTestCasesPaginator(AioPaginator):
@@ -130,15 +124,15 @@
     """
 
     def paginate(
         self,
         *,
         reportArn: str,
         filter: TestCaseFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeTestCasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.DescribeTestCases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#describetestcasespaginator)
         """
 
 class ListBuildBatchesPaginator(AioPaginator):
@@ -148,15 +142,15 @@
     """
 
     def paginate(
         self,
         *,
         filter: BuildBatchFilterTypeDef = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildBatchesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuildBatches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildbatchespaginator)
         """
 
 class ListBuildBatchesForProjectPaginator(AioPaginator):
@@ -167,29 +161,32 @@
 
     def paginate(
         self,
         *,
         projectName: str = ...,
         filter: BuildBatchFilterTypeDef = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildBatchesForProjectOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuildBatchesForProject.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildbatchesforprojectpaginator)
         """
 
 class ListBuildsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuilds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildspaginator)
     """
 
     def paginate(
-        self, *, sortOrder: SortOrderTypeType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        sortOrder: SortOrderTypeType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuilds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildspaginator)
         """
 
 class ListBuildsForProjectPaginator(AioPaginator):
@@ -199,15 +196,15 @@
     """
 
     def paginate(
         self,
         *,
         projectName: str,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildsForProjectOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListBuildsForProject.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listbuildsforprojectpaginator)
         """
 
 class ListProjectsPaginator(AioPaginator):
@@ -217,15 +214,15 @@
     """
 
     def paginate(
         self,
         *,
         sortBy: ProjectSortByTypeType = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listprojectspaginator)
         """
 
 class ListReportGroupsPaginator(AioPaginator):
@@ -235,15 +232,15 @@
     """
 
     def paginate(
         self,
         *,
         sortOrder: SortOrderTypeType = ...,
         sortBy: ReportGroupSortByTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListReportGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listreportgroupspaginator)
         """
 
 class ListReportsPaginator(AioPaginator):
@@ -253,15 +250,15 @@
     """
 
     def paginate(
         self,
         *,
         sortOrder: SortOrderTypeType = ...,
         filter: ReportFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listreportspaginator)
         """
 
 class ListReportsForReportGroupPaginator(AioPaginator):
@@ -272,15 +269,15 @@
 
     def paginate(
         self,
         *,
         reportGroupArn: str,
         sortOrder: SortOrderTypeType = ...,
         filter: ReportFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReportsForReportGroupOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListReportsForReportGroup.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listreportsforreportgrouppaginator)
         """
 
 class ListSharedProjectsPaginator(AioPaginator):
@@ -290,15 +287,15 @@
     """
 
     def paginate(
         self,
         *,
         sortBy: SharedResourceSortByTypeType = ...,
         sortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSharedProjectsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListSharedProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listsharedprojectspaginator)
         """
 
 class ListSharedReportGroupsPaginator(AioPaginator):
@@ -308,13 +305,13 @@
     """
 
     def paginate(
         self,
         *,
         sortOrder: SortOrderTypeType = ...,
         sortBy: SharedResourceSortByTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSharedReportGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild.Paginator.ListSharedReportGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/paginators/#listsharedreportgroupspaginator)
         """
```

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/type_defs.py` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -58,19 +58,17 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "BatchDeleteBuildsInputRequestTypeDef",
     "BuildNotDeletedTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetBuildBatchesInputRequestTypeDef",
     "BatchGetBuildsInputRequestTypeDef",
     "BatchGetProjectsInputRequestTypeDef",
     "BatchGetReportGroupsInputRequestTypeDef",
     "BatchGetReportsInputRequestTypeDef",
     "BatchRestrictionsTypeDef",
     "BuildArtifactsTypeDef",
@@ -93,84 +91,85 @@
     "WebhookFilterTypeDef",
     "DeleteBuildBatchInputRequestTypeDef",
     "DeleteProjectInputRequestTypeDef",
     "DeleteReportGroupInputRequestTypeDef",
     "DeleteReportInputRequestTypeDef",
     "DeleteResourcePolicyInputRequestTypeDef",
     "DeleteSourceCredentialsInputRequestTypeDef",
+    "DeleteSourceCredentialsOutputTypeDef",
     "DeleteWebhookInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
     "DescribeCodeCoveragesInputRequestTypeDef",
     "TestCaseFilterTypeDef",
     "TestCaseTypeDef",
     "EnvironmentImageTypeDef",
     "EnvironmentVariableTypeDef",
     "GetReportGroupTrendInputRequestTypeDef",
     "ReportGroupTrendStatsTypeDef",
     "ReportWithRawDataTypeDef",
     "GetResourcePolicyInputRequestTypeDef",
+    "GetResourcePolicyOutputTypeDef",
     "GitSubmodulesConfigTypeDef",
     "ImportSourceCredentialsInputRequestTypeDef",
+    "ImportSourceCredentialsOutputTypeDef",
     "InvalidateProjectCacheInputRequestTypeDef",
+    "ListBuildBatchesForProjectOutputTypeDef",
+    "ListBuildBatchesOutputTypeDef",
+    "ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
     "ListBuildsForProjectInputRequestTypeDef",
+    "ListBuildsForProjectOutputTypeDef",
+    "ListBuildsInputListBuildsPaginateTypeDef",
     "ListBuildsInputRequestTypeDef",
+    "ListBuildsOutputTypeDef",
+    "ListProjectsInputListProjectsPaginateTypeDef",
     "ListProjectsInputRequestTypeDef",
+    "ListProjectsOutputTypeDef",
+    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
     "ListReportGroupsInputRequestTypeDef",
+    "ListReportGroupsOutputTypeDef",
     "ReportFilterTypeDef",
+    "ListReportsForReportGroupOutputTypeDef",
+    "ListReportsOutputTypeDef",
+    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
     "ListSharedProjectsInputRequestTypeDef",
+    "ListSharedProjectsOutputTypeDef",
+    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
     "ListSharedReportGroupsInputRequestTypeDef",
+    "ListSharedReportGroupsOutputTypeDef",
     "SourceCredentialsInfoTypeDef",
     "S3LogsConfigTypeDef",
+    "PaginatorConfigTypeDef",
     "ProjectBadgeTypeDef",
     "RegistryCredentialTypeDef",
     "SourceAuthTypeDef",
     "PutResourcePolicyInputRequestTypeDef",
+    "PutResourcePolicyOutputTypeDef",
     "S3ReportExportConfigTypeDef",
     "TestReportSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryBuildBatchInputRequestTypeDef",
     "RetryBuildInputRequestTypeDef",
     "StopBuildBatchInputRequestTypeDef",
     "StopBuildInputRequestTypeDef",
     "UpdateProjectVisibilityInputRequestTypeDef",
+    "UpdateProjectVisibilityOutputTypeDef",
     "BatchDeleteBuildsOutputTypeDef",
     "DeleteBuildBatchOutputTypeDef",
-    "DeleteSourceCredentialsOutputTypeDef",
-    "GetResourcePolicyOutputTypeDef",
-    "ImportSourceCredentialsOutputTypeDef",
-    "ListBuildBatchesForProjectOutputTypeDef",
-    "ListBuildBatchesOutputTypeDef",
-    "ListBuildsForProjectOutputTypeDef",
-    "ListBuildsOutputTypeDef",
-    "ListProjectsOutputTypeDef",
-    "ListReportGroupsOutputTypeDef",
-    "ListReportsForReportGroupOutputTypeDef",
-    "ListReportsOutputTypeDef",
-    "ListSharedProjectsOutputTypeDef",
-    "ListSharedReportGroupsOutputTypeDef",
-    "PutResourcePolicyOutputTypeDef",
-    "UpdateProjectVisibilityOutputTypeDef",
     "ProjectBuildBatchConfigTypeDef",
+    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
     "ListBuildBatchesForProjectInputRequestTypeDef",
+    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
     "ListBuildBatchesInputRequestTypeDef",
     "BuildBatchPhaseTypeDef",
     "BuildPhaseTypeDef",
     "BuildSummaryTypeDef",
     "DescribeCodeCoveragesOutputTypeDef",
     "CreateWebhookInputRequestTypeDef",
     "UpdateWebhookInputRequestTypeDef",
     "WebhookTypeDef",
-    "DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
-    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
-    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
-    "ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    "ListProjectsInputListProjectsPaginateTypeDef",
-    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
-    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
-    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
     "DescribeTestCasesInputDescribeTestCasesPaginateTypeDef",
     "DescribeTestCasesInputRequestTypeDef",
     "DescribeTestCasesOutputTypeDef",
     "EnvironmentLanguageTypeDef",
     "GetReportGroupTrendOutputTypeDef",
     "ListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef",
     "ListReportsForReportGroupInputRequestTypeDef",
@@ -227,25 +226,14 @@
     {
         "id": str,
         "statusCode": str,
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
 BatchGetBuildBatchesInputRequestTypeDef = TypedDict(
     "BatchGetBuildBatchesInputRequestTypeDef",
     {
         "ids": Sequence[str],
     },
 )
 
@@ -328,19 +316,17 @@
     {
         "location": str,
         "modes": List[CacheModeType],
     },
     total=False,
 )
 
-
 class ProjectCacheTypeDef(_RequiredProjectCacheTypeDef, _OptionalProjectCacheTypeDef):
     pass
 
-
 ProjectFileSystemLocationTypeDef = TypedDict(
     "ProjectFileSystemLocationTypeDef",
     {
         "type": Literal["EFS"],
         "location": str,
         "mountPoint": str,
         "identifier": str,
@@ -424,21 +410,19 @@
     {
         "groupName": str,
         "streamName": str,
     },
     total=False,
 )
 
-
 class CloudWatchLogsConfigTypeDef(
     _RequiredCloudWatchLogsConfigTypeDef, _OptionalCloudWatchLogsConfigTypeDef
 ):
     pass
 
-
 CodeCoverageReportSummaryTypeDef = TypedDict(
     "CodeCoverageReportSummaryTypeDef",
     {
         "lineCoveragePercentage": float,
         "linesCovered": int,
         "linesMissed": int,
         "branchCoveragePercentage": float,
@@ -483,19 +467,17 @@
         "encryptionDisabled": bool,
         "artifactIdentifier": str,
         "bucketOwnerAccess": BucketOwnerAccessType,
     },
     total=False,
 )
 
-
 class ProjectArtifactsTypeDef(_RequiredProjectArtifactsTypeDef, _OptionalProjectArtifactsTypeDef):
     pass
 
-
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
     total=False,
@@ -512,19 +494,17 @@
     "_OptionalWebhookFilterTypeDef",
     {
         "excludeMatchedPattern": bool,
     },
     total=False,
 )
 
-
 class WebhookFilterTypeDef(_RequiredWebhookFilterTypeDef, _OptionalWebhookFilterTypeDef):
     pass
 
-
 DeleteBuildBatchInputRequestTypeDef = TypedDict(
     "DeleteBuildBatchInputRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -545,21 +525,19 @@
     "_OptionalDeleteReportGroupInputRequestTypeDef",
     {
         "deleteReports": bool,
     },
     total=False,
 )
 
-
 class DeleteReportGroupInputRequestTypeDef(
     _RequiredDeleteReportGroupInputRequestTypeDef, _OptionalDeleteReportGroupInputRequestTypeDef
 ):
     pass
 
-
 DeleteReportInputRequestTypeDef = TypedDict(
     "DeleteReportInputRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -573,31 +551,53 @@
 DeleteSourceCredentialsInputRequestTypeDef = TypedDict(
     "DeleteSourceCredentialsInputRequestTypeDef",
     {
         "arn": str,
     },
 )
 
+DeleteSourceCredentialsOutputTypeDef = TypedDict(
+    "DeleteSourceCredentialsOutputTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWebhookInputRequestTypeDef = TypedDict(
     "DeleteWebhookInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "reportArn": str,
+    },
+)
+_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "sortBy": ReportCodeCoverageSortByTypeType,
+        "minLineCoveragePercentage": float,
+        "maxLineCoveragePercentage": float,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef(
+    _RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
+    _OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeCodeCoveragesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeCodeCoveragesInputRequestTypeDef",
     {
         "reportArn": str,
     },
 )
 _OptionalDescribeCodeCoveragesInputRequestTypeDef = TypedDict(
@@ -609,22 +609,20 @@
         "sortBy": ReportCodeCoverageSortByTypeType,
         "minLineCoveragePercentage": float,
         "maxLineCoveragePercentage": float,
     },
     total=False,
 )
 
-
 class DescribeCodeCoveragesInputRequestTypeDef(
     _RequiredDescribeCodeCoveragesInputRequestTypeDef,
     _OptionalDescribeCodeCoveragesInputRequestTypeDef,
 ):
     pass
 
-
 TestCaseFilterTypeDef = TypedDict(
     "TestCaseFilterTypeDef",
     {
         "status": str,
         "keyword": str,
     },
     total=False,
@@ -666,21 +664,19 @@
     "_OptionalEnvironmentVariableTypeDef",
     {
         "type": EnvironmentVariableTypeType,
     },
     total=False,
 )
 
-
 class EnvironmentVariableTypeDef(
     _RequiredEnvironmentVariableTypeDef, _OptionalEnvironmentVariableTypeDef
 ):
     pass
 
-
 _RequiredGetReportGroupTrendInputRequestTypeDef = TypedDict(
     "_RequiredGetReportGroupTrendInputRequestTypeDef",
     {
         "reportGroupArn": str,
         "trendField": ReportGroupTrendFieldTypeType,
     },
 )
@@ -688,21 +684,19 @@
     "_OptionalGetReportGroupTrendInputRequestTypeDef",
     {
         "numOfReports": int,
     },
     total=False,
 )
 
-
 class GetReportGroupTrendInputRequestTypeDef(
     _RequiredGetReportGroupTrendInputRequestTypeDef, _OptionalGetReportGroupTrendInputRequestTypeDef
 ):
     pass
 
-
 ReportGroupTrendStatsTypeDef = TypedDict(
     "ReportGroupTrendStatsTypeDef",
     {
         "average": str,
         "max": str,
         "min": str,
     },
@@ -721,14 +715,22 @@
 GetResourcePolicyInputRequestTypeDef = TypedDict(
     "GetResourcePolicyInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+GetResourcePolicyOutputTypeDef = TypedDict(
+    "GetResourcePolicyOutputTypeDef",
+    {
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GitSubmodulesConfigTypeDef = TypedDict(
     "GitSubmodulesConfigTypeDef",
     {
         "fetchSubmodules": bool,
     },
 )
 
@@ -745,29 +747,74 @@
     {
         "username": str,
         "shouldOverwrite": bool,
     },
     total=False,
 )
 
-
 class ImportSourceCredentialsInputRequestTypeDef(
     _RequiredImportSourceCredentialsInputRequestTypeDef,
     _OptionalImportSourceCredentialsInputRequestTypeDef,
 ):
     pass
 
+ImportSourceCredentialsOutputTypeDef = TypedDict(
+    "ImportSourceCredentialsOutputTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 InvalidateProjectCacheInputRequestTypeDef = TypedDict(
     "InvalidateProjectCacheInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 
+ListBuildBatchesForProjectOutputTypeDef = TypedDict(
+    "ListBuildBatchesForProjectOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBuildBatchesOutputTypeDef = TypedDict(
+    "ListBuildBatchesOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
+    "_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
+    {
+        "projectName": str,
+    },
+)
+_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
+    "_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef(
+    _RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
+    _OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
+):
+    pass
+
 _RequiredListBuildsForProjectInputRequestTypeDef = TypedDict(
     "_RequiredListBuildsForProjectInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalListBuildsForProjectInputRequestTypeDef = TypedDict(
@@ -775,82 +822,201 @@
     {
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListBuildsForProjectInputRequestTypeDef(
     _RequiredListBuildsForProjectInputRequestTypeDef,
     _OptionalListBuildsForProjectInputRequestTypeDef,
 ):
     pass
 
+ListBuildsForProjectOutputTypeDef = TypedDict(
+    "ListBuildsForProjectOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
+    "ListBuildsInputListBuildsPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListBuildsInputRequestTypeDef = TypedDict(
     "ListBuildsInputRequestTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
+ListBuildsOutputTypeDef = TypedDict(
+    "ListBuildsOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProjectsInputListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsInputListProjectsPaginateTypeDef",
+    {
+        "sortBy": ProjectSortByTypeType,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsInputRequestTypeDef = TypedDict(
     "ListProjectsInputRequestTypeDef",
     {
         "sortBy": ProjectSortByTypeType,
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
+ListProjectsOutputTypeDef = TypedDict(
+    "ListProjectsOutputTypeDef",
+    {
+        "nextToken": str,
+        "projects": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReportGroupsInputListReportGroupsPaginateTypeDef = TypedDict(
+    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "sortBy": ReportGroupSortByTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReportGroupsInputRequestTypeDef = TypedDict(
     "ListReportGroupsInputRequestTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "sortBy": ReportGroupSortByTypeType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListReportGroupsOutputTypeDef = TypedDict(
+    "ListReportGroupsOutputTypeDef",
+    {
+        "nextToken": str,
+        "reportGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ReportFilterTypeDef = TypedDict(
     "ReportFilterTypeDef",
     {
         "status": ReportStatusTypeType,
     },
     total=False,
 )
 
+ListReportsForReportGroupOutputTypeDef = TypedDict(
+    "ListReportsForReportGroupOutputTypeDef",
+    {
+        "nextToken": str,
+        "reports": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReportsOutputTypeDef = TypedDict(
+    "ListReportsOutputTypeDef",
+    {
+        "nextToken": str,
+        "reports": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListSharedProjectsInputListSharedProjectsPaginateTypeDef = TypedDict(
+    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
+    {
+        "sortBy": SharedResourceSortByTypeType,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSharedProjectsInputRequestTypeDef = TypedDict(
     "ListSharedProjectsInputRequestTypeDef",
     {
         "sortBy": SharedResourceSortByTypeType,
         "sortOrder": SortOrderTypeType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListSharedProjectsOutputTypeDef = TypedDict(
+    "ListSharedProjectsOutputTypeDef",
+    {
+        "nextToken": str,
+        "projects": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef = TypedDict(
+    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "sortBy": SharedResourceSortByTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSharedReportGroupsInputRequestTypeDef = TypedDict(
     "ListSharedReportGroupsInputRequestTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "sortBy": SharedResourceSortByTypeType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListSharedReportGroupsOutputTypeDef = TypedDict(
+    "ListSharedReportGroupsOutputTypeDef",
+    {
+        "nextToken": str,
+        "reportGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SourceCredentialsInfoTypeDef = TypedDict(
     "SourceCredentialsInfoTypeDef",
     {
         "arn": str,
         "serverType": ServerTypeType,
         "authType": AuthTypeType,
     },
@@ -869,18 +1035,26 @@
         "location": str,
         "encryptionDisabled": bool,
         "bucketOwnerAccess": BucketOwnerAccessType,
     },
     total=False,
 )
 
-
 class S3LogsConfigTypeDef(_RequiredS3LogsConfigTypeDef, _OptionalS3LogsConfigTypeDef):
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
 
 ProjectBadgeTypeDef = TypedDict(
     "ProjectBadgeTypeDef",
     {
         "badgeEnabled": bool,
         "badgeRequestUrl": str,
     },
@@ -905,27 +1079,33 @@
     "_OptionalSourceAuthTypeDef",
     {
         "resource": str,
     },
     total=False,
 )
 
-
 class SourceAuthTypeDef(_RequiredSourceAuthTypeDef, _OptionalSourceAuthTypeDef):
     pass
 
-
 PutResourcePolicyInputRequestTypeDef = TypedDict(
     "PutResourcePolicyInputRequestTypeDef",
     {
         "policy": str,
         "resourceArn": str,
     },
 )
 
+PutResourcePolicyOutputTypeDef = TypedDict(
+    "PutResourcePolicyOutputTypeDef",
+    {
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3ReportExportConfigTypeDef = TypedDict(
     "S3ReportExportConfigTypeDef",
     {
         "bucket": str,
         "bucketOwner": str,
         "path": str,
         "packaging": ReportPackagingTypeType,
@@ -940,14 +1120,25 @@
     {
         "total": int,
         "statusCounts": Dict[str, int],
         "durationInNanoSeconds": int,
     },
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
 RetryBuildBatchInputRequestTypeDef = TypedDict(
     "RetryBuildBatchInputRequestTypeDef",
     {
         "id": str,
         "idempotencyToken": str,
         "retryType": RetryBuildBatchTypeType,
     },
@@ -988,170 +1179,46 @@
     "_OptionalUpdateProjectVisibilityInputRequestTypeDef",
     {
         "resourceAccessRole": str,
     },
     total=False,
 )
 
-
 class UpdateProjectVisibilityInputRequestTypeDef(
     _RequiredUpdateProjectVisibilityInputRequestTypeDef,
     _OptionalUpdateProjectVisibilityInputRequestTypeDef,
 ):
     pass
 
+UpdateProjectVisibilityOutputTypeDef = TypedDict(
+    "UpdateProjectVisibilityOutputTypeDef",
+    {
+        "projectArn": str,
+        "publicProjectAlias": str,
+        "projectVisibility": ProjectVisibilityTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 BatchDeleteBuildsOutputTypeDef = TypedDict(
     "BatchDeleteBuildsOutputTypeDef",
     {
         "buildsDeleted": List[str],
         "buildsNotDeleted": List[BuildNotDeletedTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBuildBatchOutputTypeDef = TypedDict(
     "DeleteBuildBatchOutputTypeDef",
     {
         "statusCode": str,
         "buildsDeleted": List[str],
         "buildsNotDeleted": List[BuildNotDeletedTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSourceCredentialsOutputTypeDef = TypedDict(
-    "DeleteSourceCredentialsOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyOutputTypeDef = TypedDict(
-    "GetResourcePolicyOutputTypeDef",
-    {
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportSourceCredentialsOutputTypeDef = TypedDict(
-    "ImportSourceCredentialsOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildBatchesForProjectOutputTypeDef = TypedDict(
-    "ListBuildBatchesForProjectOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildBatchesOutputTypeDef = TypedDict(
-    "ListBuildBatchesOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildsForProjectOutputTypeDef = TypedDict(
-    "ListBuildsForProjectOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildsOutputTypeDef = TypedDict(
-    "ListBuildsOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListProjectsOutputTypeDef = TypedDict(
-    "ListProjectsOutputTypeDef",
-    {
-        "nextToken": str,
-        "projects": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReportGroupsOutputTypeDef = TypedDict(
-    "ListReportGroupsOutputTypeDef",
-    {
-        "nextToken": str,
-        "reportGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReportsForReportGroupOutputTypeDef = TypedDict(
-    "ListReportsForReportGroupOutputTypeDef",
-    {
-        "nextToken": str,
-        "reports": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReportsOutputTypeDef = TypedDict(
-    "ListReportsOutputTypeDef",
-    {
-        "nextToken": str,
-        "reports": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSharedProjectsOutputTypeDef = TypedDict(
-    "ListSharedProjectsOutputTypeDef",
-    {
-        "nextToken": str,
-        "projects": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSharedReportGroupsOutputTypeDef = TypedDict(
-    "ListSharedReportGroupsOutputTypeDef",
-    {
-        "nextToken": str,
-        "reportGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyOutputTypeDef = TypedDict(
-    "PutResourcePolicyOutputTypeDef",
-    {
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateProjectVisibilityOutputTypeDef = TypedDict(
-    "UpdateProjectVisibilityOutputTypeDef",
-    {
-        "projectArn": str,
-        "publicProjectAlias": str,
-        "projectVisibility": ProjectVisibilityTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProjectBuildBatchConfigTypeDef = TypedDict(
     "ProjectBuildBatchConfigTypeDef",
     {
         "serviceRole": str,
@@ -1159,26 +1226,47 @@
         "restrictions": BatchRestrictionsTypeDef,
         "timeoutInMins": int,
         "batchReportMode": BatchReportModeTypeType,
     },
     total=False,
 )
 
+ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef = TypedDict(
+    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
+    {
+        "projectName": str,
+        "filter": BuildBatchFilterTypeDef,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBuildBatchesForProjectInputRequestTypeDef = TypedDict(
     "ListBuildBatchesForProjectInputRequestTypeDef",
     {
         "projectName": str,
         "filter": BuildBatchFilterTypeDef,
         "maxResults": int,
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
+ListBuildBatchesInputListBuildBatchesPaginateTypeDef = TypedDict(
+    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
+    {
+        "filter": BuildBatchFilterTypeDef,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBuildBatchesInputRequestTypeDef = TypedDict(
     "ListBuildBatchesInputRequestTypeDef",
     {
         "filter": BuildBatchFilterTypeDef,
         "maxResults": int,
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
@@ -1225,15 +1313,15 @@
 )
 
 DescribeCodeCoveragesOutputTypeDef = TypedDict(
     "DescribeCodeCoveragesOutputTypeDef",
     {
         "nextToken": str,
         "codeCoverages": List[CodeCoverageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWebhookInputRequestTypeDef = TypedDict(
     "_RequiredCreateWebhookInputRequestTypeDef",
     {
         "projectName": str,
@@ -1245,21 +1333,19 @@
         "branchFilter": str,
         "filterGroups": Sequence[Sequence[WebhookFilterTypeDef]],
         "buildType": WebhookBuildTypeType,
     },
     total=False,
 )
 
-
 class CreateWebhookInputRequestTypeDef(
     _RequiredCreateWebhookInputRequestTypeDef, _OptionalCreateWebhookInputRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateWebhookInputRequestTypeDef = TypedDict(
     "_RequiredUpdateWebhookInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalUpdateWebhookInputRequestTypeDef = TypedDict(
@@ -1269,177 +1355,54 @@
         "rotateSecret": bool,
         "filterGroups": Sequence[Sequence[WebhookFilterTypeDef]],
         "buildType": WebhookBuildTypeType,
     },
     total=False,
 )
 
-
 class UpdateWebhookInputRequestTypeDef(
     _RequiredUpdateWebhookInputRequestTypeDef, _OptionalUpdateWebhookInputRequestTypeDef
 ):
     pass
 
-
 WebhookTypeDef = TypedDict(
     "WebhookTypeDef",
     {
         "url": str,
         "payloadUrl": str,
         "secret": str,
         "branchFilter": str,
         "filterGroups": List[List[WebhookFilterTypeDef]],
         "buildType": WebhookBuildTypeType,
         "lastModifiedSecret": datetime,
     },
     total=False,
 )
 
-_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
-    {
-        "reportArn": str,
-    },
-)
-_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "sortBy": ReportCodeCoverageSortByTypeType,
-        "minLineCoveragePercentage": float,
-        "maxLineCoveragePercentage": float,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef(
-    _RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
-    _OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
-):
-    pass
-
-
-ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef = TypedDict(
-    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
-    {
-        "projectName": str,
-        "filter": BuildBatchFilterTypeDef,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBuildBatchesInputListBuildBatchesPaginateTypeDef = TypedDict(
-    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
-    {
-        "filter": BuildBatchFilterTypeDef,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
-    "_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
-    {
-        "projectName": str,
-    },
-)
-_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
-    "_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef(
-    _RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
-    _OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
-):
-    pass
-
-
-ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProjectsInputListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsInputListProjectsPaginateTypeDef",
-    {
-        "sortBy": ProjectSortByTypeType,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReportGroupsInputListReportGroupsPaginateTypeDef = TypedDict(
-    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "sortBy": ReportGroupSortByTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSharedProjectsInputListSharedProjectsPaginateTypeDef = TypedDict(
-    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
-    {
-        "sortBy": SharedResourceSortByTypeType,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef = TypedDict(
-    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "sortBy": SharedResourceSortByTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeTestCasesInputDescribeTestCasesPaginateTypeDef = TypedDict(
     "_RequiredDescribeTestCasesInputDescribeTestCasesPaginateTypeDef",
     {
         "reportArn": str,
     },
 )
 _OptionalDescribeTestCasesInputDescribeTestCasesPaginateTypeDef = TypedDict(
     "_OptionalDescribeTestCasesInputDescribeTestCasesPaginateTypeDef",
     {
         "filter": TestCaseFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class DescribeTestCasesInputDescribeTestCasesPaginateTypeDef(
     _RequiredDescribeTestCasesInputDescribeTestCasesPaginateTypeDef,
     _OptionalDescribeTestCasesInputDescribeTestCasesPaginateTypeDef,
 ):
     pass
 
-
 _RequiredDescribeTestCasesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeTestCasesInputRequestTypeDef",
     {
         "reportArn": str,
     },
 )
 _OptionalDescribeTestCasesInputRequestTypeDef = TypedDict(
@@ -1448,27 +1411,25 @@
         "nextToken": str,
         "maxResults": int,
         "filter": TestCaseFilterTypeDef,
     },
     total=False,
 )
 
-
 class DescribeTestCasesInputRequestTypeDef(
     _RequiredDescribeTestCasesInputRequestTypeDef, _OptionalDescribeTestCasesInputRequestTypeDef
 ):
     pass
 
-
 DescribeTestCasesOutputTypeDef = TypedDict(
     "DescribeTestCasesOutputTypeDef",
     {
         "nextToken": str,
         "testCases": List[TestCaseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentLanguageTypeDef = TypedDict(
     "EnvironmentLanguageTypeDef",
     {
         "language": LanguageTypeType,
@@ -1478,42 +1439,40 @@
 )
 
 GetReportGroupTrendOutputTypeDef = TypedDict(
     "GetReportGroupTrendOutputTypeDef",
     {
         "stats": ReportGroupTrendStatsTypeDef,
         "rawData": List[ReportWithRawDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef = TypedDict(
     "_RequiredListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef",
     {
         "reportGroupArn": str,
     },
 )
 _OptionalListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef = TypedDict(
     "_OptionalListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "filter": ReportFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef(
     _RequiredListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef,
     _OptionalListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListReportsForReportGroupInputRequestTypeDef = TypedDict(
     "_RequiredListReportsForReportGroupInputRequestTypeDef",
     {
         "reportGroupArn": str,
     },
 )
 _OptionalListReportsForReportGroupInputRequestTypeDef = TypedDict(
@@ -1523,28 +1482,26 @@
         "sortOrder": SortOrderTypeType,
         "maxResults": int,
         "filter": ReportFilterTypeDef,
     },
     total=False,
 )
 
-
 class ListReportsForReportGroupInputRequestTypeDef(
     _RequiredListReportsForReportGroupInputRequestTypeDef,
     _OptionalListReportsForReportGroupInputRequestTypeDef,
 ):
     pass
 
-
 ListReportsInputListReportsPaginateTypeDef = TypedDict(
     "ListReportsInputListReportsPaginateTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "filter": ReportFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListReportsInputRequestTypeDef = TypedDict(
     "ListReportsInputRequestTypeDef",
     {
@@ -1556,15 +1513,15 @@
     total=False,
 )
 
 ListSourceCredentialsOutputTypeDef = TypedDict(
     "ListSourceCredentialsOutputTypeDef",
     {
         "sourceCredentialsInfos": List[SourceCredentialsInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LogsConfigTypeDef = TypedDict(
     "LogsConfigTypeDef",
     {
         "cloudWatchLogs": CloudWatchLogsConfigTypeDef,
@@ -1604,21 +1561,19 @@
         "certificate": str,
         "registryCredential": RegistryCredentialTypeDef,
         "imagePullCredentialsType": ImagePullCredentialsTypeType,
     },
     total=False,
 )
 
-
 class ProjectEnvironmentTypeDef(
     _RequiredProjectEnvironmentTypeDef, _OptionalProjectEnvironmentTypeDef
 ):
     pass
 
-
 _RequiredProjectSourceTypeDef = TypedDict(
     "_RequiredProjectSourceTypeDef",
     {
         "type": SourceTypeType,
     },
 )
 _OptionalProjectSourceTypeDef = TypedDict(
@@ -1633,19 +1588,17 @@
         "buildStatusConfig": BuildStatusConfigTypeDef,
         "insecureSsl": bool,
         "sourceIdentifier": str,
     },
     total=False,
 )
 
-
 class ProjectSourceTypeDef(_RequiredProjectSourceTypeDef, _OptionalProjectSourceTypeDef):
     pass
 
-
 ReportExportConfigTypeDef = TypedDict(
     "ReportExportConfigTypeDef",
     {
         "exportConfigType": ReportExportConfigTypeType,
         "s3Destination": S3ReportExportConfigTypeDef,
     },
     total=False,
@@ -1663,23 +1616,23 @@
     total=False,
 )
 
 CreateWebhookOutputTypeDef = TypedDict(
     "CreateWebhookOutputTypeDef",
     {
         "webhook": WebhookTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWebhookOutputTypeDef = TypedDict(
     "UpdateWebhookOutputTypeDef",
     {
         "webhook": WebhookTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentPlatformTypeDef = TypedDict(
     "EnvironmentPlatformTypeDef",
     {
         "platform": PlatformTypeType,
@@ -1756,21 +1709,19 @@
         "fileSystemLocations": Sequence[ProjectFileSystemLocationTypeDef],
         "buildBatchConfig": ProjectBuildBatchConfigTypeDef,
         "concurrentBuildLimit": int,
     },
     total=False,
 )
 
-
 class CreateProjectInputRequestTypeDef(
     _RequiredCreateProjectInputRequestTypeDef, _OptionalCreateProjectInputRequestTypeDef
 ):
     pass
 
-
 ProjectTypeDef = TypedDict(
     "ProjectTypeDef",
     {
         "name": str,
         "arn": str,
         "description": str,
         "source": ProjectSourceTypeDef,
@@ -1841,21 +1792,19 @@
         "imagePullCredentialsTypeOverride": ImagePullCredentialsTypeType,
         "buildBatchConfigOverride": ProjectBuildBatchConfigTypeDef,
         "debugSessionEnabled": bool,
     },
     total=False,
 )
 
-
 class StartBuildBatchInputRequestTypeDef(
     _RequiredStartBuildBatchInputRequestTypeDef, _OptionalStartBuildBatchInputRequestTypeDef
 ):
     pass
 
-
 _RequiredStartBuildInputRequestTypeDef = TypedDict(
     "_RequiredStartBuildInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalStartBuildInputRequestTypeDef = TypedDict(
@@ -1891,21 +1840,19 @@
         "registryCredentialOverride": RegistryCredentialTypeDef,
         "imagePullCredentialsTypeOverride": ImagePullCredentialsTypeType,
         "debugSessionEnabled": bool,
     },
     total=False,
 )
 
-
 class StartBuildInputRequestTypeDef(
     _RequiredStartBuildInputRequestTypeDef, _OptionalStartBuildInputRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateProjectInputRequestTypeDef = TypedDict(
     "_RequiredUpdateProjectInputRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalUpdateProjectInputRequestTypeDef = TypedDict(
@@ -1931,21 +1878,19 @@
         "fileSystemLocations": Sequence[ProjectFileSystemLocationTypeDef],
         "buildBatchConfig": ProjectBuildBatchConfigTypeDef,
         "concurrentBuildLimit": int,
     },
     total=False,
 )
 
-
 class UpdateProjectInputRequestTypeDef(
     _RequiredUpdateProjectInputRequestTypeDef, _OptionalUpdateProjectInputRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateReportGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateReportGroupInputRequestTypeDef",
     {
         "name": str,
         "type": ReportTypeType,
         "exportConfig": ReportExportConfigTypeDef,
     },
@@ -1954,21 +1899,19 @@
     "_OptionalCreateReportGroupInputRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateReportGroupInputRequestTypeDef(
     _RequiredCreateReportGroupInputRequestTypeDef, _OptionalCreateReportGroupInputRequestTypeDef
 ):
     pass
 
-
 ReportGroupTypeDef = TypedDict(
     "ReportGroupTypeDef",
     {
         "arn": str,
         "name": str,
         "type": ReportTypeType,
         "exportConfig": ReportExportConfigTypeDef,
@@ -2010,21 +1953,19 @@
     {
         "exportConfig": ReportExportConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class UpdateReportGroupInputRequestTypeDef(
     _RequiredUpdateReportGroupInputRequestTypeDef, _OptionalUpdateReportGroupInputRequestTypeDef
 ):
     pass
 
-
 BuildBatchTypeDef = TypedDict(
     "BuildBatchTypeDef",
     {
         "id": str,
         "arn": str,
         "startTime": datetime,
         "endTime": datetime,
@@ -2058,135 +1999,135 @@
     total=False,
 )
 
 ListCuratedEnvironmentImagesOutputTypeDef = TypedDict(
     "ListCuratedEnvironmentImagesOutputTypeDef",
     {
         "platforms": List[EnvironmentPlatformTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetBuildsOutputTypeDef = TypedDict(
     "BatchGetBuildsOutputTypeDef",
     {
         "builds": List[BuildTypeDef],
         "buildsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RetryBuildOutputTypeDef = TypedDict(
     "RetryBuildOutputTypeDef",
     {
         "build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartBuildOutputTypeDef = TypedDict(
     "StartBuildOutputTypeDef",
     {
         "build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopBuildOutputTypeDef = TypedDict(
     "StopBuildOutputTypeDef",
     {
         "build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetProjectsOutputTypeDef = TypedDict(
     "BatchGetProjectsOutputTypeDef",
     {
         "projects": List[ProjectTypeDef],
         "projectsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProjectOutputTypeDef = TypedDict(
     "CreateProjectOutputTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProjectOutputTypeDef = TypedDict(
     "UpdateProjectOutputTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetReportGroupsOutputTypeDef = TypedDict(
     "BatchGetReportGroupsOutputTypeDef",
     {
         "reportGroups": List[ReportGroupTypeDef],
         "reportGroupsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReportGroupOutputTypeDef = TypedDict(
     "CreateReportGroupOutputTypeDef",
     {
         "reportGroup": ReportGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateReportGroupOutputTypeDef = TypedDict(
     "UpdateReportGroupOutputTypeDef",
     {
         "reportGroup": ReportGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetReportsOutputTypeDef = TypedDict(
     "BatchGetReportsOutputTypeDef",
     {
         "reports": List[ReportTypeDef],
         "reportsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetBuildBatchesOutputTypeDef = TypedDict(
     "BatchGetBuildBatchesOutputTypeDef",
     {
         "buildBatches": List[BuildBatchTypeDef],
         "buildBatchesNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RetryBuildBatchOutputTypeDef = TypedDict(
     "RetryBuildBatchOutputTypeDef",
     {
         "buildBatch": BuildBatchTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartBuildBatchOutputTypeDef = TypedDict(
     "StartBuildBatchOutputTypeDef",
     {
         "buildBatch": BuildBatchTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopBuildBatchOutputTypeDef = TypedDict(
     "StopBuildBatchOutputTypeDef",
     {
         "buildBatch": BuildBatchTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild/type_defs.pyi` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -58,18 +58,18 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "BatchDeleteBuildsInputRequestTypeDef",
     "BuildNotDeletedTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetBuildBatchesInputRequestTypeDef",
     "BatchGetBuildsInputRequestTypeDef",
     "BatchGetProjectsInputRequestTypeDef",
     "BatchGetReportGroupsInputRequestTypeDef",
     "BatchGetReportsInputRequestTypeDef",
     "BatchRestrictionsTypeDef",
     "BuildArtifactsTypeDef",
@@ -92,84 +92,85 @@
     "WebhookFilterTypeDef",
     "DeleteBuildBatchInputRequestTypeDef",
     "DeleteProjectInputRequestTypeDef",
     "DeleteReportGroupInputRequestTypeDef",
     "DeleteReportInputRequestTypeDef",
     "DeleteResourcePolicyInputRequestTypeDef",
     "DeleteSourceCredentialsInputRequestTypeDef",
+    "DeleteSourceCredentialsOutputTypeDef",
     "DeleteWebhookInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
     "DescribeCodeCoveragesInputRequestTypeDef",
     "TestCaseFilterTypeDef",
     "TestCaseTypeDef",
     "EnvironmentImageTypeDef",
     "EnvironmentVariableTypeDef",
     "GetReportGroupTrendInputRequestTypeDef",
     "ReportGroupTrendStatsTypeDef",
     "ReportWithRawDataTypeDef",
     "GetResourcePolicyInputRequestTypeDef",
+    "GetResourcePolicyOutputTypeDef",
     "GitSubmodulesConfigTypeDef",
     "ImportSourceCredentialsInputRequestTypeDef",
+    "ImportSourceCredentialsOutputTypeDef",
     "InvalidateProjectCacheInputRequestTypeDef",
+    "ListBuildBatchesForProjectOutputTypeDef",
+    "ListBuildBatchesOutputTypeDef",
+    "ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
     "ListBuildsForProjectInputRequestTypeDef",
+    "ListBuildsForProjectOutputTypeDef",
+    "ListBuildsInputListBuildsPaginateTypeDef",
     "ListBuildsInputRequestTypeDef",
+    "ListBuildsOutputTypeDef",
+    "ListProjectsInputListProjectsPaginateTypeDef",
     "ListProjectsInputRequestTypeDef",
+    "ListProjectsOutputTypeDef",
+    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
     "ListReportGroupsInputRequestTypeDef",
+    "ListReportGroupsOutputTypeDef",
     "ReportFilterTypeDef",
+    "ListReportsForReportGroupOutputTypeDef",
+    "ListReportsOutputTypeDef",
+    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
     "ListSharedProjectsInputRequestTypeDef",
+    "ListSharedProjectsOutputTypeDef",
+    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
     "ListSharedReportGroupsInputRequestTypeDef",
+    "ListSharedReportGroupsOutputTypeDef",
     "SourceCredentialsInfoTypeDef",
     "S3LogsConfigTypeDef",
+    "PaginatorConfigTypeDef",
     "ProjectBadgeTypeDef",
     "RegistryCredentialTypeDef",
     "SourceAuthTypeDef",
     "PutResourcePolicyInputRequestTypeDef",
+    "PutResourcePolicyOutputTypeDef",
     "S3ReportExportConfigTypeDef",
     "TestReportSummaryTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryBuildBatchInputRequestTypeDef",
     "RetryBuildInputRequestTypeDef",
     "StopBuildBatchInputRequestTypeDef",
     "StopBuildInputRequestTypeDef",
     "UpdateProjectVisibilityInputRequestTypeDef",
+    "UpdateProjectVisibilityOutputTypeDef",
     "BatchDeleteBuildsOutputTypeDef",
     "DeleteBuildBatchOutputTypeDef",
-    "DeleteSourceCredentialsOutputTypeDef",
-    "GetResourcePolicyOutputTypeDef",
-    "ImportSourceCredentialsOutputTypeDef",
-    "ListBuildBatchesForProjectOutputTypeDef",
-    "ListBuildBatchesOutputTypeDef",
-    "ListBuildsForProjectOutputTypeDef",
-    "ListBuildsOutputTypeDef",
-    "ListProjectsOutputTypeDef",
-    "ListReportGroupsOutputTypeDef",
-    "ListReportsForReportGroupOutputTypeDef",
-    "ListReportsOutputTypeDef",
-    "ListSharedProjectsOutputTypeDef",
-    "ListSharedReportGroupsOutputTypeDef",
-    "PutResourcePolicyOutputTypeDef",
-    "UpdateProjectVisibilityOutputTypeDef",
     "ProjectBuildBatchConfigTypeDef",
+    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
     "ListBuildBatchesForProjectInputRequestTypeDef",
+    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
     "ListBuildBatchesInputRequestTypeDef",
     "BuildBatchPhaseTypeDef",
     "BuildPhaseTypeDef",
     "BuildSummaryTypeDef",
     "DescribeCodeCoveragesOutputTypeDef",
     "CreateWebhookInputRequestTypeDef",
     "UpdateWebhookInputRequestTypeDef",
     "WebhookTypeDef",
-    "DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
-    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
-    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
-    "ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    "ListProjectsInputListProjectsPaginateTypeDef",
-    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
-    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
-    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
     "DescribeTestCasesInputDescribeTestCasesPaginateTypeDef",
     "DescribeTestCasesInputRequestTypeDef",
     "DescribeTestCasesOutputTypeDef",
     "EnvironmentLanguageTypeDef",
     "GetReportGroupTrendOutputTypeDef",
     "ListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef",
     "ListReportsForReportGroupInputRequestTypeDef",
@@ -226,25 +227,14 @@
     {
         "id": str,
         "statusCode": str,
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
 BatchGetBuildBatchesInputRequestTypeDef = TypedDict(
     "BatchGetBuildBatchesInputRequestTypeDef",
     {
         "ids": Sequence[str],
     },
 )
 
@@ -327,17 +317,19 @@
     {
         "location": str,
         "modes": List[CacheModeType],
     },
     total=False,
 )
 
+
 class ProjectCacheTypeDef(_RequiredProjectCacheTypeDef, _OptionalProjectCacheTypeDef):
     pass
 
+
 ProjectFileSystemLocationTypeDef = TypedDict(
     "ProjectFileSystemLocationTypeDef",
     {
         "type": Literal["EFS"],
         "location": str,
         "mountPoint": str,
         "identifier": str,
@@ -421,19 +413,21 @@
     {
         "groupName": str,
         "streamName": str,
     },
     total=False,
 )
 
+
 class CloudWatchLogsConfigTypeDef(
     _RequiredCloudWatchLogsConfigTypeDef, _OptionalCloudWatchLogsConfigTypeDef
 ):
     pass
 
+
 CodeCoverageReportSummaryTypeDef = TypedDict(
     "CodeCoverageReportSummaryTypeDef",
     {
         "lineCoveragePercentage": float,
         "linesCovered": int,
         "linesMissed": int,
         "branchCoveragePercentage": float,
@@ -478,17 +472,19 @@
         "encryptionDisabled": bool,
         "artifactIdentifier": str,
         "bucketOwnerAccess": BucketOwnerAccessType,
     },
     total=False,
 )
 
+
 class ProjectArtifactsTypeDef(_RequiredProjectArtifactsTypeDef, _OptionalProjectArtifactsTypeDef):
     pass
 
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
     total=False,
@@ -505,17 +501,19 @@
     "_OptionalWebhookFilterTypeDef",
     {
         "excludeMatchedPattern": bool,
     },
     total=False,
 )
 
+
 class WebhookFilterTypeDef(_RequiredWebhookFilterTypeDef, _OptionalWebhookFilterTypeDef):
     pass
 
+
 DeleteBuildBatchInputRequestTypeDef = TypedDict(
     "DeleteBuildBatchInputRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -536,19 +534,21 @@
     "_OptionalDeleteReportGroupInputRequestTypeDef",
     {
         "deleteReports": bool,
     },
     total=False,
 )
 
+
 class DeleteReportGroupInputRequestTypeDef(
     _RequiredDeleteReportGroupInputRequestTypeDef, _OptionalDeleteReportGroupInputRequestTypeDef
 ):
     pass
 
+
 DeleteReportInputRequestTypeDef = TypedDict(
     "DeleteReportInputRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -562,31 +562,55 @@
 DeleteSourceCredentialsInputRequestTypeDef = TypedDict(
     "DeleteSourceCredentialsInputRequestTypeDef",
     {
         "arn": str,
     },
 )
 
+DeleteSourceCredentialsOutputTypeDef = TypedDict(
+    "DeleteSourceCredentialsOutputTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWebhookInputRequestTypeDef = TypedDict(
     "DeleteWebhookInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "reportArn": str,
+    },
+)
+_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "sortBy": ReportCodeCoverageSortByTypeType,
+        "minLineCoveragePercentage": float,
+        "maxLineCoveragePercentage": float,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef(
+    _RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
+    _OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeCodeCoveragesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeCodeCoveragesInputRequestTypeDef",
     {
         "reportArn": str,
     },
 )
 _OptionalDescribeCodeCoveragesInputRequestTypeDef = TypedDict(
@@ -598,20 +622,22 @@
         "sortBy": ReportCodeCoverageSortByTypeType,
         "minLineCoveragePercentage": float,
         "maxLineCoveragePercentage": float,
     },
     total=False,
 )
 
+
 class DescribeCodeCoveragesInputRequestTypeDef(
     _RequiredDescribeCodeCoveragesInputRequestTypeDef,
     _OptionalDescribeCodeCoveragesInputRequestTypeDef,
 ):
     pass
 
+
 TestCaseFilterTypeDef = TypedDict(
     "TestCaseFilterTypeDef",
     {
         "status": str,
         "keyword": str,
     },
     total=False,
@@ -653,19 +679,21 @@
     "_OptionalEnvironmentVariableTypeDef",
     {
         "type": EnvironmentVariableTypeType,
     },
     total=False,
 )
 
+
 class EnvironmentVariableTypeDef(
     _RequiredEnvironmentVariableTypeDef, _OptionalEnvironmentVariableTypeDef
 ):
     pass
 
+
 _RequiredGetReportGroupTrendInputRequestTypeDef = TypedDict(
     "_RequiredGetReportGroupTrendInputRequestTypeDef",
     {
         "reportGroupArn": str,
         "trendField": ReportGroupTrendFieldTypeType,
     },
 )
@@ -673,19 +701,21 @@
     "_OptionalGetReportGroupTrendInputRequestTypeDef",
     {
         "numOfReports": int,
     },
     total=False,
 )
 
+
 class GetReportGroupTrendInputRequestTypeDef(
     _RequiredGetReportGroupTrendInputRequestTypeDef, _OptionalGetReportGroupTrendInputRequestTypeDef
 ):
     pass
 
+
 ReportGroupTrendStatsTypeDef = TypedDict(
     "ReportGroupTrendStatsTypeDef",
     {
         "average": str,
         "max": str,
         "min": str,
     },
@@ -704,14 +734,22 @@
 GetResourcePolicyInputRequestTypeDef = TypedDict(
     "GetResourcePolicyInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+GetResourcePolicyOutputTypeDef = TypedDict(
+    "GetResourcePolicyOutputTypeDef",
+    {
+        "policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GitSubmodulesConfigTypeDef = TypedDict(
     "GitSubmodulesConfigTypeDef",
     {
         "fetchSubmodules": bool,
     },
 )
 
@@ -728,27 +766,78 @@
     {
         "username": str,
         "shouldOverwrite": bool,
     },
     total=False,
 )
 
+
 class ImportSourceCredentialsInputRequestTypeDef(
     _RequiredImportSourceCredentialsInputRequestTypeDef,
     _OptionalImportSourceCredentialsInputRequestTypeDef,
 ):
     pass
 
+
+ImportSourceCredentialsOutputTypeDef = TypedDict(
+    "ImportSourceCredentialsOutputTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InvalidateProjectCacheInputRequestTypeDef = TypedDict(
     "InvalidateProjectCacheInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 
+ListBuildBatchesForProjectOutputTypeDef = TypedDict(
+    "ListBuildBatchesForProjectOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBuildBatchesOutputTypeDef = TypedDict(
+    "ListBuildBatchesOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
+    "_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
+    {
+        "projectName": str,
+    },
+)
+_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
+    "_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef(
+    _RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
+    _OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListBuildsForProjectInputRequestTypeDef = TypedDict(
     "_RequiredListBuildsForProjectInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalListBuildsForProjectInputRequestTypeDef = TypedDict(
@@ -756,80 +845,203 @@
     {
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListBuildsForProjectInputRequestTypeDef(
     _RequiredListBuildsForProjectInputRequestTypeDef,
     _OptionalListBuildsForProjectInputRequestTypeDef,
 ):
     pass
 
+
+ListBuildsForProjectOutputTypeDef = TypedDict(
+    "ListBuildsForProjectOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
+    "ListBuildsInputListBuildsPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBuildsInputRequestTypeDef = TypedDict(
     "ListBuildsInputRequestTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
+ListBuildsOutputTypeDef = TypedDict(
+    "ListBuildsOutputTypeDef",
+    {
+        "ids": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProjectsInputListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsInputListProjectsPaginateTypeDef",
+    {
+        "sortBy": ProjectSortByTypeType,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsInputRequestTypeDef = TypedDict(
     "ListProjectsInputRequestTypeDef",
     {
         "sortBy": ProjectSortByTypeType,
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
+ListProjectsOutputTypeDef = TypedDict(
+    "ListProjectsOutputTypeDef",
+    {
+        "nextToken": str,
+        "projects": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReportGroupsInputListReportGroupsPaginateTypeDef = TypedDict(
+    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "sortBy": ReportGroupSortByTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReportGroupsInputRequestTypeDef = TypedDict(
     "ListReportGroupsInputRequestTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "sortBy": ReportGroupSortByTypeType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListReportGroupsOutputTypeDef = TypedDict(
+    "ListReportGroupsOutputTypeDef",
+    {
+        "nextToken": str,
+        "reportGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ReportFilterTypeDef = TypedDict(
     "ReportFilterTypeDef",
     {
         "status": ReportStatusTypeType,
     },
     total=False,
 )
 
+ListReportsForReportGroupOutputTypeDef = TypedDict(
+    "ListReportsForReportGroupOutputTypeDef",
+    {
+        "nextToken": str,
+        "reports": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReportsOutputTypeDef = TypedDict(
+    "ListReportsOutputTypeDef",
+    {
+        "nextToken": str,
+        "reports": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListSharedProjectsInputListSharedProjectsPaginateTypeDef = TypedDict(
+    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
+    {
+        "sortBy": SharedResourceSortByTypeType,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSharedProjectsInputRequestTypeDef = TypedDict(
     "ListSharedProjectsInputRequestTypeDef",
     {
         "sortBy": SharedResourceSortByTypeType,
         "sortOrder": SortOrderTypeType,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListSharedProjectsOutputTypeDef = TypedDict(
+    "ListSharedProjectsOutputTypeDef",
+    {
+        "nextToken": str,
+        "projects": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef = TypedDict(
+    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
+    {
+        "sortOrder": SortOrderTypeType,
+        "sortBy": SharedResourceSortByTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSharedReportGroupsInputRequestTypeDef = TypedDict(
     "ListSharedReportGroupsInputRequestTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "sortBy": SharedResourceSortByTypeType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListSharedReportGroupsOutputTypeDef = TypedDict(
+    "ListSharedReportGroupsOutputTypeDef",
+    {
+        "nextToken": str,
+        "reportGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SourceCredentialsInfoTypeDef = TypedDict(
     "SourceCredentialsInfoTypeDef",
     {
         "arn": str,
         "serverType": ServerTypeType,
         "authType": AuthTypeType,
     },
@@ -848,17 +1060,29 @@
         "location": str,
         "encryptionDisabled": bool,
         "bucketOwnerAccess": BucketOwnerAccessType,
     },
     total=False,
 )
 
+
 class S3LogsConfigTypeDef(_RequiredS3LogsConfigTypeDef, _OptionalS3LogsConfigTypeDef):
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
 ProjectBadgeTypeDef = TypedDict(
     "ProjectBadgeTypeDef",
     {
         "badgeEnabled": bool,
         "badgeRequestUrl": str,
     },
     total=False,
@@ -882,25 +1106,35 @@
     "_OptionalSourceAuthTypeDef",
     {
         "resource": str,
     },
     total=False,
 )
 
+
 class SourceAuthTypeDef(_RequiredSourceAuthTypeDef, _OptionalSourceAuthTypeDef):
     pass
 
+
 PutResourcePolicyInputRequestTypeDef = TypedDict(
     "PutResourcePolicyInputRequestTypeDef",
     {
         "policy": str,
         "resourceArn": str,
     },
 )
 
+PutResourcePolicyOutputTypeDef = TypedDict(
+    "PutResourcePolicyOutputTypeDef",
+    {
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3ReportExportConfigTypeDef = TypedDict(
     "S3ReportExportConfigTypeDef",
     {
         "bucket": str,
         "bucketOwner": str,
         "path": str,
         "packaging": ReportPackagingTypeType,
@@ -915,14 +1149,25 @@
     {
         "total": int,
         "statusCounts": Dict[str, int],
         "durationInNanoSeconds": int,
     },
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
 RetryBuildBatchInputRequestTypeDef = TypedDict(
     "RetryBuildBatchInputRequestTypeDef",
     {
         "id": str,
         "idempotencyToken": str,
         "retryType": RetryBuildBatchTypeType,
     },
@@ -963,168 +1208,48 @@
     "_OptionalUpdateProjectVisibilityInputRequestTypeDef",
     {
         "resourceAccessRole": str,
     },
     total=False,
 )
 
+
 class UpdateProjectVisibilityInputRequestTypeDef(
     _RequiredUpdateProjectVisibilityInputRequestTypeDef,
     _OptionalUpdateProjectVisibilityInputRequestTypeDef,
 ):
     pass
 
+
+UpdateProjectVisibilityOutputTypeDef = TypedDict(
+    "UpdateProjectVisibilityOutputTypeDef",
+    {
+        "projectArn": str,
+        "publicProjectAlias": str,
+        "projectVisibility": ProjectVisibilityTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchDeleteBuildsOutputTypeDef = TypedDict(
     "BatchDeleteBuildsOutputTypeDef",
     {
         "buildsDeleted": List[str],
         "buildsNotDeleted": List[BuildNotDeletedTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBuildBatchOutputTypeDef = TypedDict(
     "DeleteBuildBatchOutputTypeDef",
     {
         "statusCode": str,
         "buildsDeleted": List[str],
         "buildsNotDeleted": List[BuildNotDeletedTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSourceCredentialsOutputTypeDef = TypedDict(
-    "DeleteSourceCredentialsOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyOutputTypeDef = TypedDict(
-    "GetResourcePolicyOutputTypeDef",
-    {
-        "policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ImportSourceCredentialsOutputTypeDef = TypedDict(
-    "ImportSourceCredentialsOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildBatchesForProjectOutputTypeDef = TypedDict(
-    "ListBuildBatchesForProjectOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildBatchesOutputTypeDef = TypedDict(
-    "ListBuildBatchesOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildsForProjectOutputTypeDef = TypedDict(
-    "ListBuildsForProjectOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBuildsOutputTypeDef = TypedDict(
-    "ListBuildsOutputTypeDef",
-    {
-        "ids": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListProjectsOutputTypeDef = TypedDict(
-    "ListProjectsOutputTypeDef",
-    {
-        "nextToken": str,
-        "projects": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReportGroupsOutputTypeDef = TypedDict(
-    "ListReportGroupsOutputTypeDef",
-    {
-        "nextToken": str,
-        "reportGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReportsForReportGroupOutputTypeDef = TypedDict(
-    "ListReportsForReportGroupOutputTypeDef",
-    {
-        "nextToken": str,
-        "reports": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReportsOutputTypeDef = TypedDict(
-    "ListReportsOutputTypeDef",
-    {
-        "nextToken": str,
-        "reports": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSharedProjectsOutputTypeDef = TypedDict(
-    "ListSharedProjectsOutputTypeDef",
-    {
-        "nextToken": str,
-        "projects": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSharedReportGroupsOutputTypeDef = TypedDict(
-    "ListSharedReportGroupsOutputTypeDef",
-    {
-        "nextToken": str,
-        "reportGroups": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyOutputTypeDef = TypedDict(
-    "PutResourcePolicyOutputTypeDef",
-    {
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateProjectVisibilityOutputTypeDef = TypedDict(
-    "UpdateProjectVisibilityOutputTypeDef",
-    {
-        "projectArn": str,
-        "publicProjectAlias": str,
-        "projectVisibility": ProjectVisibilityTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProjectBuildBatchConfigTypeDef = TypedDict(
     "ProjectBuildBatchConfigTypeDef",
     {
         "serviceRole": str,
@@ -1132,26 +1257,47 @@
         "restrictions": BatchRestrictionsTypeDef,
         "timeoutInMins": int,
         "batchReportMode": BatchReportModeTypeType,
     },
     total=False,
 )
 
+ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef = TypedDict(
+    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
+    {
+        "projectName": str,
+        "filter": BuildBatchFilterTypeDef,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBuildBatchesForProjectInputRequestTypeDef = TypedDict(
     "ListBuildBatchesForProjectInputRequestTypeDef",
     {
         "projectName": str,
         "filter": BuildBatchFilterTypeDef,
         "maxResults": int,
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
     },
     total=False,
 )
 
+ListBuildBatchesInputListBuildBatchesPaginateTypeDef = TypedDict(
+    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
+    {
+        "filter": BuildBatchFilterTypeDef,
+        "sortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBuildBatchesInputRequestTypeDef = TypedDict(
     "ListBuildBatchesInputRequestTypeDef",
     {
         "filter": BuildBatchFilterTypeDef,
         "maxResults": int,
         "sortOrder": SortOrderTypeType,
         "nextToken": str,
@@ -1198,15 +1344,15 @@
 )
 
 DescribeCodeCoveragesOutputTypeDef = TypedDict(
     "DescribeCodeCoveragesOutputTypeDef",
     {
         "nextToken": str,
         "codeCoverages": List[CodeCoverageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWebhookInputRequestTypeDef = TypedDict(
     "_RequiredCreateWebhookInputRequestTypeDef",
     {
         "projectName": str,
@@ -1218,19 +1364,21 @@
         "branchFilter": str,
         "filterGroups": Sequence[Sequence[WebhookFilterTypeDef]],
         "buildType": WebhookBuildTypeType,
     },
     total=False,
 )
 
+
 class CreateWebhookInputRequestTypeDef(
     _RequiredCreateWebhookInputRequestTypeDef, _OptionalCreateWebhookInputRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateWebhookInputRequestTypeDef = TypedDict(
     "_RequiredUpdateWebhookInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalUpdateWebhookInputRequestTypeDef = TypedDict(
@@ -1240,169 +1388,58 @@
         "rotateSecret": bool,
         "filterGroups": Sequence[Sequence[WebhookFilterTypeDef]],
         "buildType": WebhookBuildTypeType,
     },
     total=False,
 )
 
+
 class UpdateWebhookInputRequestTypeDef(
     _RequiredUpdateWebhookInputRequestTypeDef, _OptionalUpdateWebhookInputRequestTypeDef
 ):
     pass
 
+
 WebhookTypeDef = TypedDict(
     "WebhookTypeDef",
     {
         "url": str,
         "payloadUrl": str,
         "secret": str,
         "branchFilter": str,
         "filterGroups": List[List[WebhookFilterTypeDef]],
         "buildType": WebhookBuildTypeType,
         "lastModifiedSecret": datetime,
     },
     total=False,
 )
 
-_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
-    {
-        "reportArn": str,
-    },
-)
-_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "sortBy": ReportCodeCoverageSortByTypeType,
-        "minLineCoveragePercentage": float,
-        "maxLineCoveragePercentage": float,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef(
-    _RequiredDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
-    _OptionalDescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
-):
-    pass
-
-ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef = TypedDict(
-    "ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef",
-    {
-        "projectName": str,
-        "filter": BuildBatchFilterTypeDef,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBuildBatchesInputListBuildBatchesPaginateTypeDef = TypedDict(
-    "ListBuildBatchesInputListBuildBatchesPaginateTypeDef",
-    {
-        "filter": BuildBatchFilterTypeDef,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
-    "_RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
-    {
-        "projectName": str,
-    },
-)
-_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef = TypedDict(
-    "_OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef(
-    _RequiredListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
-    _OptionalListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
-):
-    pass
-
-ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProjectsInputListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsInputListProjectsPaginateTypeDef",
-    {
-        "sortBy": ProjectSortByTypeType,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReportGroupsInputListReportGroupsPaginateTypeDef = TypedDict(
-    "ListReportGroupsInputListReportGroupsPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "sortBy": ReportGroupSortByTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSharedProjectsInputListSharedProjectsPaginateTypeDef = TypedDict(
-    "ListSharedProjectsInputListSharedProjectsPaginateTypeDef",
-    {
-        "sortBy": SharedResourceSortByTypeType,
-        "sortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef = TypedDict(
-    "ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef",
-    {
-        "sortOrder": SortOrderTypeType,
-        "sortBy": SharedResourceSortByTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeTestCasesInputDescribeTestCasesPaginateTypeDef = TypedDict(
     "_RequiredDescribeTestCasesInputDescribeTestCasesPaginateTypeDef",
     {
         "reportArn": str,
     },
 )
 _OptionalDescribeTestCasesInputDescribeTestCasesPaginateTypeDef = TypedDict(
     "_OptionalDescribeTestCasesInputDescribeTestCasesPaginateTypeDef",
     {
         "filter": TestCaseFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class DescribeTestCasesInputDescribeTestCasesPaginateTypeDef(
     _RequiredDescribeTestCasesInputDescribeTestCasesPaginateTypeDef,
     _OptionalDescribeTestCasesInputDescribeTestCasesPaginateTypeDef,
 ):
     pass
 
+
 _RequiredDescribeTestCasesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeTestCasesInputRequestTypeDef",
     {
         "reportArn": str,
     },
 )
 _OptionalDescribeTestCasesInputRequestTypeDef = TypedDict(
@@ -1411,25 +1448,27 @@
         "nextToken": str,
         "maxResults": int,
         "filter": TestCaseFilterTypeDef,
     },
     total=False,
 )
 
+
 class DescribeTestCasesInputRequestTypeDef(
     _RequiredDescribeTestCasesInputRequestTypeDef, _OptionalDescribeTestCasesInputRequestTypeDef
 ):
     pass
 
+
 DescribeTestCasesOutputTypeDef = TypedDict(
     "DescribeTestCasesOutputTypeDef",
     {
         "nextToken": str,
         "testCases": List[TestCaseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentLanguageTypeDef = TypedDict(
     "EnvironmentLanguageTypeDef",
     {
         "language": LanguageTypeType,
@@ -1439,40 +1478,42 @@
 )
 
 GetReportGroupTrendOutputTypeDef = TypedDict(
     "GetReportGroupTrendOutputTypeDef",
     {
         "stats": ReportGroupTrendStatsTypeDef,
         "rawData": List[ReportWithRawDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef = TypedDict(
     "_RequiredListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef",
     {
         "reportGroupArn": str,
     },
 )
 _OptionalListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef = TypedDict(
     "_OptionalListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "filter": ReportFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef(
     _RequiredListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef,
     _OptionalListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListReportsForReportGroupInputRequestTypeDef = TypedDict(
     "_RequiredListReportsForReportGroupInputRequestTypeDef",
     {
         "reportGroupArn": str,
     },
 )
 _OptionalListReportsForReportGroupInputRequestTypeDef = TypedDict(
@@ -1482,26 +1523,28 @@
         "sortOrder": SortOrderTypeType,
         "maxResults": int,
         "filter": ReportFilterTypeDef,
     },
     total=False,
 )
 
+
 class ListReportsForReportGroupInputRequestTypeDef(
     _RequiredListReportsForReportGroupInputRequestTypeDef,
     _OptionalListReportsForReportGroupInputRequestTypeDef,
 ):
     pass
 
+
 ListReportsInputListReportsPaginateTypeDef = TypedDict(
     "ListReportsInputListReportsPaginateTypeDef",
     {
         "sortOrder": SortOrderTypeType,
         "filter": ReportFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListReportsInputRequestTypeDef = TypedDict(
     "ListReportsInputRequestTypeDef",
     {
@@ -1513,15 +1556,15 @@
     total=False,
 )
 
 ListSourceCredentialsOutputTypeDef = TypedDict(
     "ListSourceCredentialsOutputTypeDef",
     {
         "sourceCredentialsInfos": List[SourceCredentialsInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LogsConfigTypeDef = TypedDict(
     "LogsConfigTypeDef",
     {
         "cloudWatchLogs": CloudWatchLogsConfigTypeDef,
@@ -1561,19 +1604,21 @@
         "certificate": str,
         "registryCredential": RegistryCredentialTypeDef,
         "imagePullCredentialsType": ImagePullCredentialsTypeType,
     },
     total=False,
 )
 
+
 class ProjectEnvironmentTypeDef(
     _RequiredProjectEnvironmentTypeDef, _OptionalProjectEnvironmentTypeDef
 ):
     pass
 
+
 _RequiredProjectSourceTypeDef = TypedDict(
     "_RequiredProjectSourceTypeDef",
     {
         "type": SourceTypeType,
     },
 )
 _OptionalProjectSourceTypeDef = TypedDict(
@@ -1588,17 +1633,19 @@
         "buildStatusConfig": BuildStatusConfigTypeDef,
         "insecureSsl": bool,
         "sourceIdentifier": str,
     },
     total=False,
 )
 
+
 class ProjectSourceTypeDef(_RequiredProjectSourceTypeDef, _OptionalProjectSourceTypeDef):
     pass
 
+
 ReportExportConfigTypeDef = TypedDict(
     "ReportExportConfigTypeDef",
     {
         "exportConfigType": ReportExportConfigTypeType,
         "s3Destination": S3ReportExportConfigTypeDef,
     },
     total=False,
@@ -1616,23 +1663,23 @@
     total=False,
 )
 
 CreateWebhookOutputTypeDef = TypedDict(
     "CreateWebhookOutputTypeDef",
     {
         "webhook": WebhookTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWebhookOutputTypeDef = TypedDict(
     "UpdateWebhookOutputTypeDef",
     {
         "webhook": WebhookTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentPlatformTypeDef = TypedDict(
     "EnvironmentPlatformTypeDef",
     {
         "platform": PlatformTypeType,
@@ -1709,19 +1756,21 @@
         "fileSystemLocations": Sequence[ProjectFileSystemLocationTypeDef],
         "buildBatchConfig": ProjectBuildBatchConfigTypeDef,
         "concurrentBuildLimit": int,
     },
     total=False,
 )
 
+
 class CreateProjectInputRequestTypeDef(
     _RequiredCreateProjectInputRequestTypeDef, _OptionalCreateProjectInputRequestTypeDef
 ):
     pass
 
+
 ProjectTypeDef = TypedDict(
     "ProjectTypeDef",
     {
         "name": str,
         "arn": str,
         "description": str,
         "source": ProjectSourceTypeDef,
@@ -1792,19 +1841,21 @@
         "imagePullCredentialsTypeOverride": ImagePullCredentialsTypeType,
         "buildBatchConfigOverride": ProjectBuildBatchConfigTypeDef,
         "debugSessionEnabled": bool,
     },
     total=False,
 )
 
+
 class StartBuildBatchInputRequestTypeDef(
     _RequiredStartBuildBatchInputRequestTypeDef, _OptionalStartBuildBatchInputRequestTypeDef
 ):
     pass
 
+
 _RequiredStartBuildInputRequestTypeDef = TypedDict(
     "_RequiredStartBuildInputRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalStartBuildInputRequestTypeDef = TypedDict(
@@ -1840,19 +1891,21 @@
         "registryCredentialOverride": RegistryCredentialTypeDef,
         "imagePullCredentialsTypeOverride": ImagePullCredentialsTypeType,
         "debugSessionEnabled": bool,
     },
     total=False,
 )
 
+
 class StartBuildInputRequestTypeDef(
     _RequiredStartBuildInputRequestTypeDef, _OptionalStartBuildInputRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateProjectInputRequestTypeDef = TypedDict(
     "_RequiredUpdateProjectInputRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalUpdateProjectInputRequestTypeDef = TypedDict(
@@ -1878,19 +1931,21 @@
         "fileSystemLocations": Sequence[ProjectFileSystemLocationTypeDef],
         "buildBatchConfig": ProjectBuildBatchConfigTypeDef,
         "concurrentBuildLimit": int,
     },
     total=False,
 )
 
+
 class UpdateProjectInputRequestTypeDef(
     _RequiredUpdateProjectInputRequestTypeDef, _OptionalUpdateProjectInputRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateReportGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateReportGroupInputRequestTypeDef",
     {
         "name": str,
         "type": ReportTypeType,
         "exportConfig": ReportExportConfigTypeDef,
     },
@@ -1899,19 +1954,21 @@
     "_OptionalCreateReportGroupInputRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateReportGroupInputRequestTypeDef(
     _RequiredCreateReportGroupInputRequestTypeDef, _OptionalCreateReportGroupInputRequestTypeDef
 ):
     pass
 
+
 ReportGroupTypeDef = TypedDict(
     "ReportGroupTypeDef",
     {
         "arn": str,
         "name": str,
         "type": ReportTypeType,
         "exportConfig": ReportExportConfigTypeDef,
@@ -1953,19 +2010,21 @@
     {
         "exportConfig": ReportExportConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class UpdateReportGroupInputRequestTypeDef(
     _RequiredUpdateReportGroupInputRequestTypeDef, _OptionalUpdateReportGroupInputRequestTypeDef
 ):
     pass
 
+
 BuildBatchTypeDef = TypedDict(
     "BuildBatchTypeDef",
     {
         "id": str,
         "arn": str,
         "startTime": datetime,
         "endTime": datetime,
@@ -1999,135 +2058,135 @@
     total=False,
 )
 
 ListCuratedEnvironmentImagesOutputTypeDef = TypedDict(
     "ListCuratedEnvironmentImagesOutputTypeDef",
     {
         "platforms": List[EnvironmentPlatformTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetBuildsOutputTypeDef = TypedDict(
     "BatchGetBuildsOutputTypeDef",
     {
         "builds": List[BuildTypeDef],
         "buildsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RetryBuildOutputTypeDef = TypedDict(
     "RetryBuildOutputTypeDef",
     {
         "build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartBuildOutputTypeDef = TypedDict(
     "StartBuildOutputTypeDef",
     {
         "build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopBuildOutputTypeDef = TypedDict(
     "StopBuildOutputTypeDef",
     {
         "build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetProjectsOutputTypeDef = TypedDict(
     "BatchGetProjectsOutputTypeDef",
     {
         "projects": List[ProjectTypeDef],
         "projectsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProjectOutputTypeDef = TypedDict(
     "CreateProjectOutputTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProjectOutputTypeDef = TypedDict(
     "UpdateProjectOutputTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetReportGroupsOutputTypeDef = TypedDict(
     "BatchGetReportGroupsOutputTypeDef",
     {
         "reportGroups": List[ReportGroupTypeDef],
         "reportGroupsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateReportGroupOutputTypeDef = TypedDict(
     "CreateReportGroupOutputTypeDef",
     {
         "reportGroup": ReportGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateReportGroupOutputTypeDef = TypedDict(
     "UpdateReportGroupOutputTypeDef",
     {
         "reportGroup": ReportGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetReportsOutputTypeDef = TypedDict(
     "BatchGetReportsOutputTypeDef",
     {
         "reports": List[ReportTypeDef],
         "reportsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetBuildBatchesOutputTypeDef = TypedDict(
     "BatchGetBuildBatchesOutputTypeDef",
     {
         "buildBatches": List[BuildBatchTypeDef],
         "buildBatchesNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RetryBuildBatchOutputTypeDef = TypedDict(
     "RetryBuildBatchOutputTypeDef",
     {
         "buildBatch": BuildBatchTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartBuildBatchOutputTypeDef = TypedDict(
     "StartBuildBatchOutputTypeDef",
     {
         "buildBatch": BuildBatchTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopBuildBatchOutputTypeDef = TypedDict(
     "StopBuildBatchOutputTypeDef",
     {
         "buildBatch": BuildBatchTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/PKG-INFO` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codebuild
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeBuild 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeBuild 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codebuild"></a>
 
 # types-aiobotocore-codebuild
 
 [![PyPI - types-aiobotocore-codebuild](https://img.shields.io/pypi/v/types-aiobotocore-codebuild.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codebuild)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codebuild.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codebuild)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codebuild?color=blue)](https://pypistats.org/packages/types-aiobotocore-codebuild)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeBuild 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild)
+[aiobotocore.CodeBuild 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codebuild.html#CodeBuild)
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
 [types-aiobotocore-codebuild docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codebuild/).
 
 See how it helps to find and fix potential bugs:
 
@@ -407,15 +407,14 @@
 `types_aiobotocore_codebuild.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codebuild.type_defs import (
     BatchDeleteBuildsInputRequestTypeDef,
     BuildNotDeletedTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetBuildBatchesInputRequestTypeDef,
     BatchGetBuildsInputRequestTypeDef,
     BatchGetProjectsInputRequestTypeDef,
     BatchGetReportGroupsInputRequestTypeDef,
     BatchGetReportsInputRequestTypeDef,
     BatchRestrictionsTypeDef,
     BuildArtifactsTypeDef,
@@ -438,84 +437,85 @@
     WebhookFilterTypeDef,
     DeleteBuildBatchInputRequestTypeDef,
     DeleteProjectInputRequestTypeDef,
     DeleteReportGroupInputRequestTypeDef,
     DeleteReportInputRequestTypeDef,
     DeleteResourcePolicyInputRequestTypeDef,
     DeleteSourceCredentialsInputRequestTypeDef,
+    DeleteSourceCredentialsOutputTypeDef,
     DeleteWebhookInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
     DescribeCodeCoveragesInputRequestTypeDef,
     TestCaseFilterTypeDef,
     TestCaseTypeDef,
     EnvironmentImageTypeDef,
     EnvironmentVariableTypeDef,
     GetReportGroupTrendInputRequestTypeDef,
     ReportGroupTrendStatsTypeDef,
     ReportWithRawDataTypeDef,
     GetResourcePolicyInputRequestTypeDef,
+    GetResourcePolicyOutputTypeDef,
     GitSubmodulesConfigTypeDef,
     ImportSourceCredentialsInputRequestTypeDef,
+    ImportSourceCredentialsOutputTypeDef,
     InvalidateProjectCacheInputRequestTypeDef,
+    ListBuildBatchesForProjectOutputTypeDef,
+    ListBuildBatchesOutputTypeDef,
+    ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
     ListBuildsForProjectInputRequestTypeDef,
+    ListBuildsForProjectOutputTypeDef,
+    ListBuildsInputListBuildsPaginateTypeDef,
     ListBuildsInputRequestTypeDef,
+    ListBuildsOutputTypeDef,
+    ListProjectsInputListProjectsPaginateTypeDef,
     ListProjectsInputRequestTypeDef,
+    ListProjectsOutputTypeDef,
+    ListReportGroupsInputListReportGroupsPaginateTypeDef,
     ListReportGroupsInputRequestTypeDef,
+    ListReportGroupsOutputTypeDef,
     ReportFilterTypeDef,
+    ListReportsForReportGroupOutputTypeDef,
+    ListReportsOutputTypeDef,
+    ListSharedProjectsInputListSharedProjectsPaginateTypeDef,
     ListSharedProjectsInputRequestTypeDef,
+    ListSharedProjectsOutputTypeDef,
+    ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef,
     ListSharedReportGroupsInputRequestTypeDef,
+    ListSharedReportGroupsOutputTypeDef,
     SourceCredentialsInfoTypeDef,
     S3LogsConfigTypeDef,
+    PaginatorConfigTypeDef,
     ProjectBadgeTypeDef,
     RegistryCredentialTypeDef,
     SourceAuthTypeDef,
     PutResourcePolicyInputRequestTypeDef,
+    PutResourcePolicyOutputTypeDef,
     S3ReportExportConfigTypeDef,
     TestReportSummaryTypeDef,
+    ResponseMetadataTypeDef,
     RetryBuildBatchInputRequestTypeDef,
     RetryBuildInputRequestTypeDef,
     StopBuildBatchInputRequestTypeDef,
     StopBuildInputRequestTypeDef,
     UpdateProjectVisibilityInputRequestTypeDef,
+    UpdateProjectVisibilityOutputTypeDef,
     BatchDeleteBuildsOutputTypeDef,
     DeleteBuildBatchOutputTypeDef,
-    DeleteSourceCredentialsOutputTypeDef,
-    GetResourcePolicyOutputTypeDef,
-    ImportSourceCredentialsOutputTypeDef,
-    ListBuildBatchesForProjectOutputTypeDef,
-    ListBuildBatchesOutputTypeDef,
-    ListBuildsForProjectOutputTypeDef,
-    ListBuildsOutputTypeDef,
-    ListProjectsOutputTypeDef,
-    ListReportGroupsOutputTypeDef,
-    ListReportsForReportGroupOutputTypeDef,
-    ListReportsOutputTypeDef,
-    ListSharedProjectsOutputTypeDef,
-    ListSharedReportGroupsOutputTypeDef,
-    PutResourcePolicyOutputTypeDef,
-    UpdateProjectVisibilityOutputTypeDef,
     ProjectBuildBatchConfigTypeDef,
+    ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef,
     ListBuildBatchesForProjectInputRequestTypeDef,
+    ListBuildBatchesInputListBuildBatchesPaginateTypeDef,
     ListBuildBatchesInputRequestTypeDef,
     BuildBatchPhaseTypeDef,
     BuildPhaseTypeDef,
     BuildSummaryTypeDef,
     DescribeCodeCoveragesOutputTypeDef,
     CreateWebhookInputRequestTypeDef,
     UpdateWebhookInputRequestTypeDef,
     WebhookTypeDef,
-    DescribeCodeCoveragesInputDescribeCodeCoveragesPaginateTypeDef,
-    ListBuildBatchesForProjectInputListBuildBatchesForProjectPaginateTypeDef,
-    ListBuildBatchesInputListBuildBatchesPaginateTypeDef,
-    ListBuildsForProjectInputListBuildsForProjectPaginateTypeDef,
-    ListBuildsInputListBuildsPaginateTypeDef,
-    ListProjectsInputListProjectsPaginateTypeDef,
-    ListReportGroupsInputListReportGroupsPaginateTypeDef,
-    ListSharedProjectsInputListSharedProjectsPaginateTypeDef,
-    ListSharedReportGroupsInputListSharedReportGroupsPaginateTypeDef,
     DescribeTestCasesInputDescribeTestCasesPaginateTypeDef,
     DescribeTestCasesInputRequestTypeDef,
     DescribeTestCasesOutputTypeDef,
     EnvironmentLanguageTypeDef,
     GetReportGroupTrendOutputTypeDef,
     ListReportsForReportGroupInputListReportsForReportGroupPaginateTypeDef,
     ListReportsForReportGroupInputRequestTypeDef,
@@ -568,43 +568,43 @@
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

### Comparing `types-aiobotocore-codebuild-2.5.0.post1/types_aiobotocore_codebuild.egg-info/SOURCES.txt` & `types-aiobotocore-codebuild-2.5.1/types_aiobotocore_codebuild.egg-info/SOURCES.txt`

 * *Files identical despite different names*

