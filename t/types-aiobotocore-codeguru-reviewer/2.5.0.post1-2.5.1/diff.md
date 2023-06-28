# Comparing `tmp/types-aiobotocore-codeguru-reviewer-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codeguru-reviewer-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codeguru-reviewer-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-codeguru-reviewer-2.5.1.tar", last modified: Wed Jun 28 01:43:15 2023, max compression
```

## Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1.tar` & `types-aiobotocore-codeguru-reviewer-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:23.699062 types-aiobotocore-codeguru-reviewer-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16970 2023-03-11 12:26:23.699062 types-aiobotocore-codeguru-reviewer-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15360 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:23.699062 types-aiobotocore-codeguru-reviewer-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:23.699062 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/
--rw-r--r--   0 runner    (1001) docker     (123)     1297 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1296 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16599 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16573 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9458 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9456 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2662 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2658 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    21001 2023-03-11 12:11:22.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20979 2023-03-11 12:11:22.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2858 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2856 2023-03-11 12:11:20.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:23.699062 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16970 2023-03-11 12:26:23.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-03-11 12:26:23.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:23.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:23.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:23.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:23.000000 types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.750111 types-aiobotocore-codeguru-reviewer-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16972 2023-06-28 01:43:15.746111 types-aiobotocore-codeguru-reviewer-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15368 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:15.750111 types-aiobotocore-codeguru-reviewer-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2203 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.746111 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/
+-rw-r--r--   0 runner    (1001) docker     (123)     1297 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1296 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16599 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16573 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9667 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9665 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2544 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2541 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21025 2023-06-28 01:27:58.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21003 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2858 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2856 2023-06-28 01:27:57.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.746111 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16972 2023-06-28 01:43:15.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1096 2023-06-28 01:43:15.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:15.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:15.000000 types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/LICENSE` & `types-aiobotocore-codeguru-reviewer-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codeguru-reviewer-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codeguru-reviewer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeGuruReviewer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeGuruReviewer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codeguru-reviewer"></a>
 
 # types-aiobotocore-codeguru-reviewer
 
 [![PyPI - types-aiobotocore-codeguru-reviewer](https://img.shields.io/pypi/v/types-aiobotocore-codeguru-reviewer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguru-reviewer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeguru-reviewer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguru-reviewer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeguru-reviewer?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeguru-reviewer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeGuruReviewer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer)
+[aiobotocore.CodeGuruReviewer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer)
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
 [types-aiobotocore-codeguru-reviewer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -362,15 +362,14 @@
 
 `types_aiobotocore_codeguru_reviewer.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeguru_reviewer.type_defs import (
     KMSKeyDetailsTypeDef,
-    ResponseMetadataTypeDef,
     BranchDiffSourceCodeTypeTypeDef,
     CodeArtifactsTypeDef,
     CodeCommitRepositoryTypeDef,
     MetricsSummaryTypeDef,
     MetricsTypeDef,
     CommitDiffSourceCodeTypeTypeDef,
     WaiterConfigTypeDef,
@@ -380,33 +379,34 @@
     DescribeRepositoryAssociationRequestRequestTypeDef,
     DisassociateRepositoryRequestRequestTypeDef,
     EventInfoTypeDef,
     ListCodeReviewsRequestRequestTypeDef,
     ListRecommendationFeedbackRequestRequestTypeDef,
     RecommendationFeedbackSummaryTypeDef,
     ListRecommendationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef,
     ListRepositoryAssociationsRequestRequestTypeDef,
     RepositoryAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutRecommendationFeedbackRequestRequestTypeDef,
     RuleMetadataTypeDef,
     RepositoryHeadSourceCodeTypeTypeDef,
     S3RepositoryTypeDef,
     ThirdPartySourceRepositoryTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
     S3RepositoryDetailsTypeDef,
     DescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef,
     DescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef,
     DescribeRecommendationFeedbackResponseTypeDef,
     RequestMetadataTypeDef,
     ListRecommendationFeedbackResponseTypeDef,
-    ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef,
     ListRepositoryAssociationsResponseTypeDef,
     RecommendationSummaryTypeDef,
     RepositoryTypeDef,
     RepositoryAssociationTypeDef,
     S3BucketRepositoryTypeDef,
     ListRecommendationsResponseTypeDef,
     AssociateRepositoryRequestRequestTypeDef,
@@ -432,43 +432,43 @@
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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/README.md` & `types-aiobotocore-codeguru-reviewer-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codeguru-reviewer"></a>
 
 # types-aiobotocore-codeguru-reviewer
 
 [![PyPI - types-aiobotocore-codeguru-reviewer](https://img.shields.io/pypi/v/types-aiobotocore-codeguru-reviewer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguru-reviewer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeguru-reviewer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguru-reviewer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeguru-reviewer?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeguru-reviewer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeGuruReviewer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer)
+[aiobotocore.CodeGuruReviewer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer)
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
 [types-aiobotocore-codeguru-reviewer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -329,15 +329,14 @@
 
 `types_aiobotocore_codeguru_reviewer.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeguru_reviewer.type_defs import (
     KMSKeyDetailsTypeDef,
-    ResponseMetadataTypeDef,
     BranchDiffSourceCodeTypeTypeDef,
     CodeArtifactsTypeDef,
     CodeCommitRepositoryTypeDef,
     MetricsSummaryTypeDef,
     MetricsTypeDef,
     CommitDiffSourceCodeTypeTypeDef,
     WaiterConfigTypeDef,
@@ -347,33 +346,34 @@
     DescribeRepositoryAssociationRequestRequestTypeDef,
     DisassociateRepositoryRequestRequestTypeDef,
     EventInfoTypeDef,
     ListCodeReviewsRequestRequestTypeDef,
     ListRecommendationFeedbackRequestRequestTypeDef,
     RecommendationFeedbackSummaryTypeDef,
     ListRecommendationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef,
     ListRepositoryAssociationsRequestRequestTypeDef,
     RepositoryAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutRecommendationFeedbackRequestRequestTypeDef,
     RuleMetadataTypeDef,
     RepositoryHeadSourceCodeTypeTypeDef,
     S3RepositoryTypeDef,
     ThirdPartySourceRepositoryTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
     S3RepositoryDetailsTypeDef,
     DescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef,
     DescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef,
     DescribeRecommendationFeedbackResponseTypeDef,
     RequestMetadataTypeDef,
     ListRecommendationFeedbackResponseTypeDef,
-    ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef,
     ListRepositoryAssociationsResponseTypeDef,
     RecommendationSummaryTypeDef,
     RepositoryTypeDef,
     RepositoryAssociationTypeDef,
     S3BucketRepositoryTypeDef,
     ListRecommendationsResponseTypeDef,
     AssociateRepositoryRequestRequestTypeDef,
@@ -399,43 +399,43 @@
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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/setup.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codeguru-reviewer.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codeguru-reviewer",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codeguru_reviewer"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeGuruReviewer 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodeGuruReviewer 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/"
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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/__init__.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/__init__.pyi` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/__main__.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeGuruReviewer 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeGuruReviewer 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer\nOther"
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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/client.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/client.pyi` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/literals.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -132,14 +132,15 @@
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
@@ -218,14 +219,15 @@
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
@@ -236,14 +238,15 @@
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
@@ -279,14 +282,15 @@
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
@@ -305,16 +309,19 @@
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
@@ -398,15 +405,17 @@
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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/literals.pyi` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -130,14 +130,15 @@
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
@@ -216,14 +217,15 @@
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
@@ -234,14 +236,15 @@
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
@@ -277,14 +280,15 @@
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
@@ -303,16 +307,19 @@
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
@@ -396,15 +403,17 @@
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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/paginator.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,29 +16,22 @@
     session = get_session()
     with session.create_client("codeguru-reviewer") as client:
         client: CodeGuruReviewerClient
 
         list_repository_associations_paginator: ListRepositoryAssociationsPaginator = client.get_paginator("list_repository_associations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ProviderTypeType, RepositoryAssociationStateType
 from .type_defs import ListRepositoryAssociationsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListRepositoryAssociationsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -57,13 +50,13 @@
     def paginate(
         self,
         *,
         ProviderTypes: Sequence[ProviderTypeType] = ...,
         States: Sequence[RepositoryAssociationStateType] = ...,
         Names: Sequence[str] = ...,
         Owners: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoryAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer.Paginator.ListRepositoryAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/paginators/#listrepositoryassociationspaginator)
         """
```

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/paginator.pyi` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -16,28 +16,22 @@
     session = get_session()
     with session.create_client("codeguru-reviewer") as client:
         client: CodeGuruReviewerClient
 
         list_repository_associations_paginator: ListRepositoryAssociationsPaginator = client.get_paginator("list_repository_associations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ProviderTypeType, RepositoryAssociationStateType
 from .type_defs import ListRepositoryAssociationsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListRepositoryAssociationsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -53,13 +47,13 @@
     def paginate(
         self,
         *,
         ProviderTypes: Sequence[ProviderTypeType] = ...,
         States: Sequence[RepositoryAssociationStateType] = ...,
         Names: Sequence[str] = ...,
         Owners: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRepositoryAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer.Paginator.ListRepositoryAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/paginators/#listrepositoryassociationspaginator)
         """
```

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/type_defs.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -30,18 +30,16 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "KMSKeyDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "BranchDiffSourceCodeTypeTypeDef",
     "CodeArtifactsTypeDef",
     "CodeCommitRepositoryTypeDef",
     "MetricsSummaryTypeDef",
     "MetricsTypeDef",
     "CommitDiffSourceCodeTypeTypeDef",
     "WaiterConfigTypeDef",
@@ -51,33 +49,34 @@
     "DescribeRepositoryAssociationRequestRequestTypeDef",
     "DisassociateRepositoryRequestRequestTypeDef",
     "EventInfoTypeDef",
     "ListCodeReviewsRequestRequestTypeDef",
     "ListRecommendationFeedbackRequestRequestTypeDef",
     "RecommendationFeedbackSummaryTypeDef",
     "ListRecommendationsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
     "ListRepositoryAssociationsRequestRequestTypeDef",
     "RepositoryAssociationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutRecommendationFeedbackRequestRequestTypeDef",
     "RuleMetadataTypeDef",
     "RepositoryHeadSourceCodeTypeTypeDef",
     "S3RepositoryTypeDef",
     "ThirdPartySourceRepositoryTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "S3RepositoryDetailsTypeDef",
     "DescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef",
     "DescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef",
     "DescribeRecommendationFeedbackResponseTypeDef",
     "RequestMetadataTypeDef",
     "ListRecommendationFeedbackResponseTypeDef",
-    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
     "ListRepositoryAssociationsResponseTypeDef",
     "RecommendationSummaryTypeDef",
     "RepositoryTypeDef",
     "RepositoryAssociationTypeDef",
     "S3BucketRepositoryTypeDef",
     "ListRecommendationsResponseTypeDef",
     "AssociateRepositoryRequestRequestTypeDef",
@@ -100,25 +99,14 @@
     {
         "KMSKeyId": str,
         "EncryptionOption": EncryptionOptionType,
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
 BranchDiffSourceCodeTypeTypeDef = TypedDict(
     "BranchDiffSourceCodeTypeTypeDef",
     {
         "SourceBranchName": str,
         "DestinationBranchName": str,
     },
 )
@@ -133,19 +121,17 @@
     "_OptionalCodeArtifactsTypeDef",
     {
         "BuildArtifactsObjectKey": str,
     },
     total=False,
 )
 
-
 class CodeArtifactsTypeDef(_RequiredCodeArtifactsTypeDef, _OptionalCodeArtifactsTypeDef):
     pass
 
-
 CodeCommitRepositoryTypeDef = TypedDict(
     "CodeCommitRepositoryTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -206,22 +192,20 @@
     "_OptionalDescribeRecommendationFeedbackRequestRequestTypeDef",
     {
         "UserId": str,
     },
     total=False,
 )
 
-
 class DescribeRecommendationFeedbackRequestRequestTypeDef(
     _RequiredDescribeRecommendationFeedbackRequestRequestTypeDef,
     _OptionalDescribeRecommendationFeedbackRequestRequestTypeDef,
 ):
     pass
 
-
 RecommendationFeedbackTypeDef = TypedDict(
     "RecommendationFeedbackTypeDef",
     {
         "CodeReviewArn": str,
         "RecommendationId": str,
         "Reactions": List[ReactionType],
         "UserId": str,
@@ -268,21 +252,19 @@
         "RepositoryNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListCodeReviewsRequestRequestTypeDef(
     _RequiredListCodeReviewsRequestRequestTypeDef, _OptionalListCodeReviewsRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredListRecommendationFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredListRecommendationFeedbackRequestRequestTypeDef",
     {
         "CodeReviewArn": str,
     },
 )
 _OptionalListRecommendationFeedbackRequestRequestTypeDef = TypedDict(
@@ -292,22 +274,20 @@
         "MaxResults": int,
         "UserIds": Sequence[str],
         "RecommendationIds": Sequence[str],
     },
     total=False,
 )
 
-
 class ListRecommendationFeedbackRequestRequestTypeDef(
     _RequiredListRecommendationFeedbackRequestRequestTypeDef,
     _OptionalListRecommendationFeedbackRequestRequestTypeDef,
 ):
     pass
 
-
 RecommendationFeedbackSummaryTypeDef = TypedDict(
     "RecommendationFeedbackSummaryTypeDef",
     {
         "RecommendationId": str,
         "Reactions": List[ReactionType],
         "UserId": str,
     },
@@ -325,28 +305,28 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListRecommendationsRequestRequestTypeDef(
     _RequiredListRecommendationsRequestRequestTypeDef,
     _OptionalListRecommendationsRequestRequestTypeDef,
 ):
     pass
 
-
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef = TypedDict(
+    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProviderTypes": Sequence[ProviderTypeType],
+        "States": Sequence[RepositoryAssociationStateType],
+        "Names": Sequence[str],
+        "Owners": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRepositoryAssociationsRequestRequestTypeDef = TypedDict(
     "ListRepositoryAssociationsRequestRequestTypeDef",
     {
@@ -378,14 +358,32 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
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
 PutRecommendationFeedbackRequestRequestTypeDef = TypedDict(
     "PutRecommendationFeedbackRequestRequestTypeDef",
     {
         "CodeReviewArn": str,
         "RecommendationId": str,
         "Reactions": Sequence[ReactionType],
     },
@@ -423,14 +421,25 @@
     {
         "Name": str,
         "ConnectionArn": str,
         "Owner": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -439,22 +448,14 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 S3RepositoryDetailsTypeDef = TypedDict(
     "S3RepositoryDetailsTypeDef",
     {
         "BucketName": str,
         "CodeArtifacts": CodeArtifactsTypeDef,
     },
     total=False,
@@ -470,49 +471,45 @@
     "_OptionalDescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef(
     _RequiredDescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef,
     _OptionalDescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef = TypedDict(
     "_RequiredDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef",
     {
         "AssociationArn": str,
     },
 )
 _OptionalDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef = TypedDict(
     "_OptionalDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef(
     _RequiredDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef,
     _OptionalDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef,
 ):
     pass
 
-
 DescribeRecommendationFeedbackResponseTypeDef = TypedDict(
     "DescribeRecommendationFeedbackResponseTypeDef",
     {
         "RecommendationFeedback": RecommendationFeedbackTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RequestMetadataTypeDef = TypedDict(
     "RequestMetadataTypeDef",
     {
         "RequestId": str,
@@ -524,36 +521,24 @@
 )
 
 ListRecommendationFeedbackResponseTypeDef = TypedDict(
     "ListRecommendationFeedbackResponseTypeDef",
     {
         "RecommendationFeedbackSummaries": List[RecommendationFeedbackSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef = TypedDict(
-    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
-    {
-        "ProviderTypes": Sequence[ProviderTypeType],
-        "States": Sequence[RepositoryAssociationStateType],
-        "Names": Sequence[str],
-        "Owners": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListRepositoryAssociationsResponseTypeDef = TypedDict(
     "ListRepositoryAssociationsResponseTypeDef",
     {
         "RepositoryAssociationSummaries": List[RepositoryAssociationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecommendationSummaryTypeDef = TypedDict(
     "RecommendationSummaryTypeDef",
     {
         "FilePath": str,
@@ -608,27 +593,25 @@
     "_OptionalS3BucketRepositoryTypeDef",
     {
         "Details": S3RepositoryDetailsTypeDef,
     },
     total=False,
 )
 
-
 class S3BucketRepositoryTypeDef(
     _RequiredS3BucketRepositoryTypeDef, _OptionalS3BucketRepositoryTypeDef
 ):
     pass
 
-
 ListRecommendationsResponseTypeDef = TypedDict(
     "ListRecommendationsResponseTypeDef",
     {
         "RecommendationSummaries": List[RecommendationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateRepositoryRequestRequestTypeDef",
     {
         "Repository": RepositoryTypeDef,
@@ -640,46 +623,44 @@
         "ClientRequestToken": str,
         "Tags": Mapping[str, str],
         "KMSKeyDetails": KMSKeyDetailsTypeDef,
     },
     total=False,
 )
 
-
 class AssociateRepositoryRequestRequestTypeDef(
     _RequiredAssociateRepositoryRequestRequestTypeDef,
     _OptionalAssociateRepositoryRequestRequestTypeDef,
 ):
     pass
 
-
 AssociateRepositoryResponseTypeDef = TypedDict(
     "AssociateRepositoryResponseTypeDef",
     {
         "RepositoryAssociation": RepositoryAssociationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoryAssociationResponseTypeDef = TypedDict(
     "DescribeRepositoryAssociationResponseTypeDef",
     {
         "RepositoryAssociation": RepositoryAssociationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateRepositoryResponseTypeDef = TypedDict(
     "DisassociateRepositoryResponseTypeDef",
     {
         "RepositoryAssociation": RepositoryAssociationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceCodeTypeTypeDef = TypedDict(
     "SourceCodeTypeTypeDef",
     {
         "CommitDiff": CommitDiffSourceCodeTypeTypeDef,
@@ -743,31 +724,31 @@
 )
 
 ListCodeReviewsResponseTypeDef = TypedDict(
     "ListCodeReviewsResponseTypeDef",
     {
         "CodeReviewSummaries": List[CodeReviewSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCodeReviewResponseTypeDef = TypedDict(
     "CreateCodeReviewResponseTypeDef",
     {
         "CodeReview": CodeReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCodeReviewResponseTypeDef = TypedDict(
     "DescribeCodeReviewResponseTypeDef",
     {
         "CodeReview": CodeReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCodeReviewTypeTypeDef = TypedDict(
     "_RequiredCodeReviewTypeTypeDef",
     {
         "RepositoryAnalysis": RepositoryAnalysisTypeDef,
@@ -777,19 +758,17 @@
     "_OptionalCodeReviewTypeTypeDef",
     {
         "AnalysisTypes": Sequence[AnalysisTypeType],
     },
     total=False,
 )
 
-
 class CodeReviewTypeTypeDef(_RequiredCodeReviewTypeTypeDef, _OptionalCodeReviewTypeTypeDef):
     pass
 
-
 _RequiredCreateCodeReviewRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCodeReviewRequestRequestTypeDef",
     {
         "Name": str,
         "RepositoryAssociationArn": str,
         "Type": CodeReviewTypeTypeDef,
     },
@@ -798,12 +777,11 @@
     "_OptionalCreateCodeReviewRequestRequestTypeDef",
     {
         "ClientRequestToken": str,
     },
     total=False,
 )
 
-
 class CreateCodeReviewRequestRequestTypeDef(
     _RequiredCreateCodeReviewRequestRequestTypeDef, _OptionalCreateCodeReviewRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/type_defs.pyi` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -30,17 +30,17 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "KMSKeyDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "BranchDiffSourceCodeTypeTypeDef",
     "CodeArtifactsTypeDef",
     "CodeCommitRepositoryTypeDef",
     "MetricsSummaryTypeDef",
     "MetricsTypeDef",
     "CommitDiffSourceCodeTypeTypeDef",
     "WaiterConfigTypeDef",
@@ -50,33 +50,34 @@
     "DescribeRepositoryAssociationRequestRequestTypeDef",
     "DisassociateRepositoryRequestRequestTypeDef",
     "EventInfoTypeDef",
     "ListCodeReviewsRequestRequestTypeDef",
     "ListRecommendationFeedbackRequestRequestTypeDef",
     "RecommendationFeedbackSummaryTypeDef",
     "ListRecommendationsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
     "ListRepositoryAssociationsRequestRequestTypeDef",
     "RepositoryAssociationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PutRecommendationFeedbackRequestRequestTypeDef",
     "RuleMetadataTypeDef",
     "RepositoryHeadSourceCodeTypeTypeDef",
     "S3RepositoryTypeDef",
     "ThirdPartySourceRepositoryTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "S3RepositoryDetailsTypeDef",
     "DescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef",
     "DescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef",
     "DescribeRecommendationFeedbackResponseTypeDef",
     "RequestMetadataTypeDef",
     "ListRecommendationFeedbackResponseTypeDef",
-    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
     "ListRepositoryAssociationsResponseTypeDef",
     "RecommendationSummaryTypeDef",
     "RepositoryTypeDef",
     "RepositoryAssociationTypeDef",
     "S3BucketRepositoryTypeDef",
     "ListRecommendationsResponseTypeDef",
     "AssociateRepositoryRequestRequestTypeDef",
@@ -99,25 +100,14 @@
     {
         "KMSKeyId": str,
         "EncryptionOption": EncryptionOptionType,
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
 BranchDiffSourceCodeTypeTypeDef = TypedDict(
     "BranchDiffSourceCodeTypeTypeDef",
     {
         "SourceBranchName": str,
         "DestinationBranchName": str,
     },
 )
@@ -132,17 +122,19 @@
     "_OptionalCodeArtifactsTypeDef",
     {
         "BuildArtifactsObjectKey": str,
     },
     total=False,
 )
 
+
 class CodeArtifactsTypeDef(_RequiredCodeArtifactsTypeDef, _OptionalCodeArtifactsTypeDef):
     pass
 
+
 CodeCommitRepositoryTypeDef = TypedDict(
     "CodeCommitRepositoryTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -203,20 +195,22 @@
     "_OptionalDescribeRecommendationFeedbackRequestRequestTypeDef",
     {
         "UserId": str,
     },
     total=False,
 )
 
+
 class DescribeRecommendationFeedbackRequestRequestTypeDef(
     _RequiredDescribeRecommendationFeedbackRequestRequestTypeDef,
     _OptionalDescribeRecommendationFeedbackRequestRequestTypeDef,
 ):
     pass
 
+
 RecommendationFeedbackTypeDef = TypedDict(
     "RecommendationFeedbackTypeDef",
     {
         "CodeReviewArn": str,
         "RecommendationId": str,
         "Reactions": List[ReactionType],
         "UserId": str,
@@ -263,19 +257,21 @@
         "RepositoryNames": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListCodeReviewsRequestRequestTypeDef(
     _RequiredListCodeReviewsRequestRequestTypeDef, _OptionalListCodeReviewsRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredListRecommendationFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredListRecommendationFeedbackRequestRequestTypeDef",
     {
         "CodeReviewArn": str,
     },
 )
 _OptionalListRecommendationFeedbackRequestRequestTypeDef = TypedDict(
@@ -285,20 +281,22 @@
         "MaxResults": int,
         "UserIds": Sequence[str],
         "RecommendationIds": Sequence[str],
     },
     total=False,
 )
 
+
 class ListRecommendationFeedbackRequestRequestTypeDef(
     _RequiredListRecommendationFeedbackRequestRequestTypeDef,
     _OptionalListRecommendationFeedbackRequestRequestTypeDef,
 ):
     pass
 
+
 RecommendationFeedbackSummaryTypeDef = TypedDict(
     "RecommendationFeedbackSummaryTypeDef",
     {
         "RecommendationId": str,
         "Reactions": List[ReactionType],
         "UserId": str,
     },
@@ -316,26 +314,30 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListRecommendationsRequestRequestTypeDef(
     _RequiredListRecommendationsRequestRequestTypeDef,
     _OptionalListRecommendationsRequestRequestTypeDef,
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+
+ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef = TypedDict(
+    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ProviderTypes": Sequence[ProviderTypeType],
+        "States": Sequence[RepositoryAssociationStateType],
+        "Names": Sequence[str],
+        "Owners": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRepositoryAssociationsRequestRequestTypeDef = TypedDict(
     "ListRepositoryAssociationsRequestRequestTypeDef",
     {
@@ -367,14 +369,32 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
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
 PutRecommendationFeedbackRequestRequestTypeDef = TypedDict(
     "PutRecommendationFeedbackRequestRequestTypeDef",
     {
         "CodeReviewArn": str,
         "RecommendationId": str,
         "Reactions": Sequence[ReactionType],
     },
@@ -412,14 +432,25 @@
     {
         "Name": str,
         "ConnectionArn": str,
         "Owner": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -428,22 +459,14 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 S3RepositoryDetailsTypeDef = TypedDict(
     "S3RepositoryDetailsTypeDef",
     {
         "BucketName": str,
         "CodeArtifacts": CodeArtifactsTypeDef,
     },
     total=False,
@@ -459,45 +482,49 @@
     "_OptionalDescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef(
     _RequiredDescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef,
     _OptionalDescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef = TypedDict(
     "_RequiredDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef",
     {
         "AssociationArn": str,
     },
 )
 _OptionalDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef = TypedDict(
     "_OptionalDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef(
     _RequiredDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef,
     _OptionalDescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef,
 ):
     pass
 
+
 DescribeRecommendationFeedbackResponseTypeDef = TypedDict(
     "DescribeRecommendationFeedbackResponseTypeDef",
     {
         "RecommendationFeedback": RecommendationFeedbackTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RequestMetadataTypeDef = TypedDict(
     "RequestMetadataTypeDef",
     {
         "RequestId": str,
@@ -509,36 +536,24 @@
 )
 
 ListRecommendationFeedbackResponseTypeDef = TypedDict(
     "ListRecommendationFeedbackResponseTypeDef",
     {
         "RecommendationFeedbackSummaries": List[RecommendationFeedbackSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef = TypedDict(
-    "ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef",
-    {
-        "ProviderTypes": Sequence[ProviderTypeType],
-        "States": Sequence[RepositoryAssociationStateType],
-        "Names": Sequence[str],
-        "Owners": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListRepositoryAssociationsResponseTypeDef = TypedDict(
     "ListRepositoryAssociationsResponseTypeDef",
     {
         "RepositoryAssociationSummaries": List[RepositoryAssociationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecommendationSummaryTypeDef = TypedDict(
     "RecommendationSummaryTypeDef",
     {
         "FilePath": str,
@@ -593,25 +608,27 @@
     "_OptionalS3BucketRepositoryTypeDef",
     {
         "Details": S3RepositoryDetailsTypeDef,
     },
     total=False,
 )
 
+
 class S3BucketRepositoryTypeDef(
     _RequiredS3BucketRepositoryTypeDef, _OptionalS3BucketRepositoryTypeDef
 ):
     pass
 
+
 ListRecommendationsResponseTypeDef = TypedDict(
     "ListRecommendationsResponseTypeDef",
     {
         "RecommendationSummaries": List[RecommendationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssociateRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateRepositoryRequestRequestTypeDef",
     {
         "Repository": RepositoryTypeDef,
@@ -623,44 +640,46 @@
         "ClientRequestToken": str,
         "Tags": Mapping[str, str],
         "KMSKeyDetails": KMSKeyDetailsTypeDef,
     },
     total=False,
 )
 
+
 class AssociateRepositoryRequestRequestTypeDef(
     _RequiredAssociateRepositoryRequestRequestTypeDef,
     _OptionalAssociateRepositoryRequestRequestTypeDef,
 ):
     pass
 
+
 AssociateRepositoryResponseTypeDef = TypedDict(
     "AssociateRepositoryResponseTypeDef",
     {
         "RepositoryAssociation": RepositoryAssociationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoryAssociationResponseTypeDef = TypedDict(
     "DescribeRepositoryAssociationResponseTypeDef",
     {
         "RepositoryAssociation": RepositoryAssociationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateRepositoryResponseTypeDef = TypedDict(
     "DisassociateRepositoryResponseTypeDef",
     {
         "RepositoryAssociation": RepositoryAssociationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SourceCodeTypeTypeDef = TypedDict(
     "SourceCodeTypeTypeDef",
     {
         "CommitDiff": CommitDiffSourceCodeTypeTypeDef,
@@ -724,31 +743,31 @@
 )
 
 ListCodeReviewsResponseTypeDef = TypedDict(
     "ListCodeReviewsResponseTypeDef",
     {
         "CodeReviewSummaries": List[CodeReviewSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCodeReviewResponseTypeDef = TypedDict(
     "CreateCodeReviewResponseTypeDef",
     {
         "CodeReview": CodeReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCodeReviewResponseTypeDef = TypedDict(
     "DescribeCodeReviewResponseTypeDef",
     {
         "CodeReview": CodeReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCodeReviewTypeTypeDef = TypedDict(
     "_RequiredCodeReviewTypeTypeDef",
     {
         "RepositoryAnalysis": RepositoryAnalysisTypeDef,
@@ -758,17 +777,19 @@
     "_OptionalCodeReviewTypeTypeDef",
     {
         "AnalysisTypes": Sequence[AnalysisTypeType],
     },
     total=False,
 )
 
+
 class CodeReviewTypeTypeDef(_RequiredCodeReviewTypeTypeDef, _OptionalCodeReviewTypeTypeDef):
     pass
 
+
 _RequiredCreateCodeReviewRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCodeReviewRequestRequestTypeDef",
     {
         "Name": str,
         "RepositoryAssociationArn": str,
         "Type": CodeReviewTypeTypeDef,
     },
@@ -777,11 +798,12 @@
     "_OptionalCreateCodeReviewRequestRequestTypeDef",
     {
         "ClientRequestToken": str,
     },
     total=False,
 )
 
+
 class CreateCodeReviewRequestRequestTypeDef(
     _RequiredCreateCodeReviewRequestRequestTypeDef, _OptionalCreateCodeReviewRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/waiter.py` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer/waiter.pyi` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/PKG-INFO` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codeguru-reviewer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeGuruReviewer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeGuruReviewer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codeguru-reviewer"></a>
 
 # types-aiobotocore-codeguru-reviewer
 
 [![PyPI - types-aiobotocore-codeguru-reviewer](https://img.shields.io/pypi/v/types-aiobotocore-codeguru-reviewer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguru-reviewer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codeguru-reviewer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codeguru-reviewer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codeguru-reviewer?color=blue)](https://pypistats.org/packages/types-aiobotocore-codeguru-reviewer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeGuruReviewer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer)
+[aiobotocore.CodeGuruReviewer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codeguru-reviewer.html#CodeGuruReviewer)
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
 [types-aiobotocore-codeguru-reviewer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -362,15 +362,14 @@
 
 `types_aiobotocore_codeguru_reviewer.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codeguru_reviewer.type_defs import (
     KMSKeyDetailsTypeDef,
-    ResponseMetadataTypeDef,
     BranchDiffSourceCodeTypeTypeDef,
     CodeArtifactsTypeDef,
     CodeCommitRepositoryTypeDef,
     MetricsSummaryTypeDef,
     MetricsTypeDef,
     CommitDiffSourceCodeTypeTypeDef,
     WaiterConfigTypeDef,
@@ -380,33 +379,34 @@
     DescribeRepositoryAssociationRequestRequestTypeDef,
     DisassociateRepositoryRequestRequestTypeDef,
     EventInfoTypeDef,
     ListCodeReviewsRequestRequestTypeDef,
     ListRecommendationFeedbackRequestRequestTypeDef,
     RecommendationFeedbackSummaryTypeDef,
     ListRecommendationsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef,
     ListRepositoryAssociationsRequestRequestTypeDef,
     RepositoryAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PutRecommendationFeedbackRequestRequestTypeDef,
     RuleMetadataTypeDef,
     RepositoryHeadSourceCodeTypeTypeDef,
     S3RepositoryTypeDef,
     ThirdPartySourceRepositoryTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
     S3RepositoryDetailsTypeDef,
     DescribeCodeReviewRequestCodeReviewCompletedWaitTypeDef,
     DescribeRepositoryAssociationRequestRepositoryAssociationSucceededWaitTypeDef,
     DescribeRecommendationFeedbackResponseTypeDef,
     RequestMetadataTypeDef,
     ListRecommendationFeedbackResponseTypeDef,
-    ListRepositoryAssociationsRequestListRepositoryAssociationsPaginateTypeDef,
     ListRepositoryAssociationsResponseTypeDef,
     RecommendationSummaryTypeDef,
     RepositoryTypeDef,
     RepositoryAssociationTypeDef,
     S3BucketRepositoryTypeDef,
     ListRecommendationsResponseTypeDef,
     AssociateRepositoryRequestRequestTypeDef,
@@ -432,43 +432,43 @@
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

### Comparing `types-aiobotocore-codeguru-reviewer-2.5.0.post1/types_aiobotocore_codeguru_reviewer.egg-info/SOURCES.txt` & `types-aiobotocore-codeguru-reviewer-2.5.1/types_aiobotocore_codeguru_reviewer.egg-info/SOURCES.txt`

 * *Files identical despite different names*

