# Comparing `tmp/types-aiobotocore-codestar-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codestar-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codestar-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-codestar-2.5.1.tar", last modified: Wed Jun 28 01:43:18 2023, max compression
```

## Comparing `types-aiobotocore-codestar-2.5.0.post1.tar` & `types-aiobotocore-codestar-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.755072 types-aiobotocore-codestar-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15284 2023-03-11 12:26:24.751072 types-aiobotocore-codestar-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13709 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:24.755072 types-aiobotocore-codestar-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.747072 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/
--rw-r--r--   0 runner    (1001) docker     (123)     1253 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1252 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17208 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17177 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8126 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8124 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5343 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5336 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    17990 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    17958 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:26.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.751072 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15284 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.990115 types-aiobotocore-codestar-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15277 2023-06-28 01:43:17.982115 types-aiobotocore-codestar-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13708 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:17.990115 types-aiobotocore-codestar-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.982115 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/
+-rw-r--r--   0 runner    (1001) docker     (123)     1253 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1252 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17208 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17177 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8335 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8333 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5231 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5225 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    18028 2023-06-28 01:28:04.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17996 2023-06-28 01:28:04.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:03.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.982115 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15277 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codestar-2.5.0.post1/LICENSE` & `types-aiobotocore-codestar-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codestar-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codestar
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeStar 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeStar 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codestar"></a>
 
 # types-aiobotocore-codestar
 
 [![PyPI - types-aiobotocore-codestar](https://img.shields.io/pypi/v/types-aiobotocore-codestar.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStar 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
+[aiobotocore.CodeStar 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
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
 [types-aiobotocore-codestar docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/).
 
 See how it helps to find and fix potential bugs:
 
@@ -329,58 +329,58 @@
 
 `types_aiobotocore_codestar.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar.type_defs import (
     AssociateTeamMemberRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateTeamMemberResultTypeDef,
     CodeCommitCodeDestinationTypeDef,
     GitHubCodeDestinationTypeDef,
     S3LocationTypeDef,
+    CreateProjectResultTypeDef,
     CreateUserProfileRequestRequestTypeDef,
+    CreateUserProfileResultTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResultTypeDef,
     DeleteUserProfileRequestRequestTypeDef,
+    DeleteUserProfileResultTypeDef,
     DescribeProjectRequestRequestTypeDef,
     ProjectStatusTypeDef,
     DescribeUserProfileRequestRequestTypeDef,
+    DescribeUserProfileResultTypeDef,
     DisassociateTeamMemberRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListTagsForProjectRequestRequestTypeDef,
+    ListTagsForProjectResultTypeDef,
+    ListTeamMembersRequestListTeamMembersPaginateTypeDef,
     ListTeamMembersRequestRequestTypeDef,
     TeamMemberTypeDef,
+    ListUserProfilesRequestListUserProfilesPaginateTypeDef,
     ListUserProfilesRequestRequestTypeDef,
     UserProfileSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagProjectRequestRequestTypeDef,
+    TagProjectResultTypeDef,
     UntagProjectRequestRequestTypeDef,
     UpdateProjectRequestRequestTypeDef,
     UpdateTeamMemberRequestRequestTypeDef,
-    UpdateUserProfileRequestRequestTypeDef,
-    AssociateTeamMemberResultTypeDef,
-    CreateProjectResultTypeDef,
-    CreateUserProfileResultTypeDef,
-    DeleteProjectResultTypeDef,
-    DeleteUserProfileResultTypeDef,
-    DescribeUserProfileResultTypeDef,
-    ListTagsForProjectResultTypeDef,
-    TagProjectResultTypeDef,
     UpdateTeamMemberResultTypeDef,
+    UpdateUserProfileRequestRequestTypeDef,
     UpdateUserProfileResultTypeDef,
     CodeDestinationTypeDef,
     CodeSourceTypeDef,
     ToolchainSourceTypeDef,
     DescribeProjectResultTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
-    ListTeamMembersRequestListTeamMembersPaginateTypeDef,
-    ListUserProfilesRequestListUserProfilesPaginateTypeDef,
     ListProjectsResultTypeDef,
     ListResourcesResultTypeDef,
     ListTeamMembersResultTypeDef,
     ListUserProfilesResultTypeDef,
     CodeTypeDef,
     ToolchainTypeDef,
     CreateProjectRequestRequestTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/README.md` & `types-aiobotocore-codestar-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codestar"></a>
 
 # types-aiobotocore-codestar
 
 [![PyPI - types-aiobotocore-codestar](https://img.shields.io/pypi/v/types-aiobotocore-codestar.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStar 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
+[aiobotocore.CodeStar 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
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
 [types-aiobotocore-codestar docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/).
 
 See how it helps to find and fix potential bugs:
 
@@ -296,58 +296,58 @@
 
 `types_aiobotocore_codestar.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar.type_defs import (
     AssociateTeamMemberRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateTeamMemberResultTypeDef,
     CodeCommitCodeDestinationTypeDef,
     GitHubCodeDestinationTypeDef,
     S3LocationTypeDef,
+    CreateProjectResultTypeDef,
     CreateUserProfileRequestRequestTypeDef,
+    CreateUserProfileResultTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResultTypeDef,
     DeleteUserProfileRequestRequestTypeDef,
+    DeleteUserProfileResultTypeDef,
     DescribeProjectRequestRequestTypeDef,
     ProjectStatusTypeDef,
     DescribeUserProfileRequestRequestTypeDef,
+    DescribeUserProfileResultTypeDef,
     DisassociateTeamMemberRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListTagsForProjectRequestRequestTypeDef,
+    ListTagsForProjectResultTypeDef,
+    ListTeamMembersRequestListTeamMembersPaginateTypeDef,
     ListTeamMembersRequestRequestTypeDef,
     TeamMemberTypeDef,
+    ListUserProfilesRequestListUserProfilesPaginateTypeDef,
     ListUserProfilesRequestRequestTypeDef,
     UserProfileSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagProjectRequestRequestTypeDef,
+    TagProjectResultTypeDef,
     UntagProjectRequestRequestTypeDef,
     UpdateProjectRequestRequestTypeDef,
     UpdateTeamMemberRequestRequestTypeDef,
-    UpdateUserProfileRequestRequestTypeDef,
-    AssociateTeamMemberResultTypeDef,
-    CreateProjectResultTypeDef,
-    CreateUserProfileResultTypeDef,
-    DeleteProjectResultTypeDef,
-    DeleteUserProfileResultTypeDef,
-    DescribeUserProfileResultTypeDef,
-    ListTagsForProjectResultTypeDef,
-    TagProjectResultTypeDef,
     UpdateTeamMemberResultTypeDef,
+    UpdateUserProfileRequestRequestTypeDef,
     UpdateUserProfileResultTypeDef,
     CodeDestinationTypeDef,
     CodeSourceTypeDef,
     ToolchainSourceTypeDef,
     DescribeProjectResultTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
-    ListTeamMembersRequestListTeamMembersPaginateTypeDef,
-    ListUserProfilesRequestListUserProfilesPaginateTypeDef,
     ListProjectsResultTypeDef,
     ListResourcesResultTypeDef,
     ListTeamMembersResultTypeDef,
     ListUserProfilesResultTypeDef,
     CodeTypeDef,
     ToolchainTypeDef,
     CreateProjectRequestRequestTypeDef,
@@ -361,43 +361,43 @@
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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/setup.py` & `types-aiobotocore-codestar-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codestar.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codestar",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codestar"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeStar 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.CodeStar 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/"
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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/__init__.py` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/__init__.pyi` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/__main__.py` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeStar 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeStar 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar\nOther"
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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/client.py` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/client.pyi` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/literals.py` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -95,14 +95,15 @@
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
@@ -181,14 +182,15 @@
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
@@ -199,14 +201,15 @@
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
@@ -242,14 +245,15 @@
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
@@ -268,16 +272,19 @@
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
@@ -361,15 +368,17 @@
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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/literals.pyi` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -93,14 +93,15 @@
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
@@ -179,14 +180,15 @@
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
@@ -197,14 +199,15 @@
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
@@ -240,14 +243,15 @@
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
@@ -266,16 +270,19 @@
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
@@ -359,15 +366,17 @@
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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/paginator.py` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,34 +22,27 @@
 
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
         list_team_members_paginator: ListTeamMembersPaginator = client.get_paginator("list_team_members")
         list_user_profiles_paginator: ListUserProfilesPaginator = client.get_paginator("list_user_profiles")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListProjectsResultTypeDef,
     ListResourcesResultTypeDef,
     ListTeamMembersResultTypeDef,
     ListUserProfilesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListProjectsPaginator",
     "ListResourcesPaginator",
     "ListTeamMembersPaginator",
     "ListUserProfilesPaginator",
 )
 
@@ -67,58 +60,58 @@
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listprojectspaginator)
         """
 
 
 class ListResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listresourcespaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listresourcespaginator)
         """
 
 
 class ListTeamMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListTeamMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listteammemberspaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTeamMembersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListTeamMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listteammemberspaginator)
         """
 
 
 class ListUserProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListUserProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listuserprofilespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserProfilesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListUserProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listuserprofilespaginator)
         """
```

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/paginator.pyi` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -22,33 +22,27 @@
 
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
         list_resources_paginator: ListResourcesPaginator = client.get_paginator("list_resources")
         list_team_members_paginator: ListTeamMembersPaginator = client.get_paginator("list_team_members")
         list_user_profiles_paginator: ListUserProfilesPaginator = client.get_paginator("list_user_profiles")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListProjectsResultTypeDef,
     ListResourcesResultTypeDef,
     ListTeamMembersResultTypeDef,
     ListUserProfilesResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListProjectsPaginator",
     "ListResourcesPaginator",
     "ListTeamMembersPaginator",
     "ListUserProfilesPaginator",
 )
 
@@ -63,55 +57,55 @@
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listprojectspaginator)
         """
 
 class ListResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listresourcespaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourcesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listresourcespaginator)
         """
 
 class ListTeamMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListTeamMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listteammemberspaginator)
     """
 
     def paginate(
-        self, *, projectId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTeamMembersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListTeamMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listteammemberspaginator)
         """
 
 class ListUserProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListUserProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listuserprofilespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUserProfilesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar.Paginator.ListUserProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/paginators/#listuserprofilespaginator)
         """
```

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/type_defs.py` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,58 +19,58 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateTeamMemberRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateTeamMemberResultTypeDef",
     "CodeCommitCodeDestinationTypeDef",
     "GitHubCodeDestinationTypeDef",
     "S3LocationTypeDef",
+    "CreateProjectResultTypeDef",
     "CreateUserProfileRequestRequestTypeDef",
+    "CreateUserProfileResultTypeDef",
     "DeleteProjectRequestRequestTypeDef",
+    "DeleteProjectResultTypeDef",
     "DeleteUserProfileRequestRequestTypeDef",
+    "DeleteUserProfileResultTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "ProjectStatusTypeDef",
     "DescribeUserProfileRequestRequestTypeDef",
+    "DescribeUserProfileResultTypeDef",
     "DisassociateTeamMemberRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
+    "ListResourcesRequestListResourcesPaginateTypeDef",
     "ListResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
     "ListTagsForProjectRequestRequestTypeDef",
+    "ListTagsForProjectResultTypeDef",
+    "ListTeamMembersRequestListTeamMembersPaginateTypeDef",
     "ListTeamMembersRequestRequestTypeDef",
     "TeamMemberTypeDef",
+    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
     "ListUserProfilesRequestRequestTypeDef",
     "UserProfileSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagProjectRequestRequestTypeDef",
+    "TagProjectResultTypeDef",
     "UntagProjectRequestRequestTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "UpdateTeamMemberRequestRequestTypeDef",
-    "UpdateUserProfileRequestRequestTypeDef",
-    "AssociateTeamMemberResultTypeDef",
-    "CreateProjectResultTypeDef",
-    "CreateUserProfileResultTypeDef",
-    "DeleteProjectResultTypeDef",
-    "DeleteUserProfileResultTypeDef",
-    "DescribeUserProfileResultTypeDef",
-    "ListTagsForProjectResultTypeDef",
-    "TagProjectResultTypeDef",
     "UpdateTeamMemberResultTypeDef",
+    "UpdateUserProfileRequestRequestTypeDef",
     "UpdateUserProfileResultTypeDef",
     "CodeDestinationTypeDef",
     "CodeSourceTypeDef",
     "ToolchainSourceTypeDef",
     "DescribeProjectResultTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    "ListResourcesRequestListResourcesPaginateTypeDef",
-    "ListTeamMembersRequestListTeamMembersPaginateTypeDef",
-    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
     "ListProjectsResultTypeDef",
     "ListResourcesResultTypeDef",
     "ListTeamMembersResultTypeDef",
     "ListUserProfilesResultTypeDef",
     "CodeTypeDef",
     "ToolchainTypeDef",
     "CreateProjectRequestRequestTypeDef",
@@ -97,22 +97,19 @@
 class AssociateTeamMemberRequestRequestTypeDef(
     _RequiredAssociateTeamMemberRequestRequestTypeDef,
     _OptionalAssociateTeamMemberRequestRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateTeamMemberResultTypeDef = TypedDict(
+    "AssociateTeamMemberResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "clientRequestToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeCommitCodeDestinationTypeDef = TypedDict(
     "CodeCommitCodeDestinationTypeDef",
     {
         "name": str,
@@ -150,14 +147,25 @@
     {
         "bucketName": str,
         "bucketKey": str,
     },
     total=False,
 )
 
+CreateProjectResultTypeDef = TypedDict(
+    "CreateProjectResultTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "clientRequestToken": str,
+        "projectTemplateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
         "displayName": str,
         "emailAddress": str,
     },
@@ -173,14 +181,27 @@
 
 class CreateUserProfileRequestRequestTypeDef(
     _RequiredCreateUserProfileRequestRequestTypeDef, _OptionalCreateUserProfileRequestRequestTypeDef
 ):
     pass
 
 
+CreateUserProfileResultTypeDef = TypedDict(
+    "CreateUserProfileResultTypeDef",
+    {
+        "userArn": str,
+        "displayName": str,
+        "emailAddress": str,
+        "sshPublicKey": str,
+        "createdTimestamp": datetime,
+        "lastModifiedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteProjectRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteProjectRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalDeleteProjectRequestRequestTypeDef = TypedDict(
@@ -195,21 +216,38 @@
 
 class DeleteProjectRequestRequestTypeDef(
     _RequiredDeleteProjectRequestRequestTypeDef, _OptionalDeleteProjectRequestRequestTypeDef
 ):
     pass
 
 
+DeleteProjectResultTypeDef = TypedDict(
+    "DeleteProjectResultTypeDef",
+    {
+        "stackId": str,
+        "projectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteUserProfileRequestRequestTypeDef = TypedDict(
     "DeleteUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
     },
 )
 
+DeleteUserProfileResultTypeDef = TypedDict(
+    "DeleteUserProfileResultTypeDef",
+    {
+        "userArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeProjectRequestRequestTypeDef = TypedDict(
     "DescribeProjectRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -235,28 +273,39 @@
 DescribeUserProfileRequestRequestTypeDef = TypedDict(
     "DescribeUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
     },
 )
 
+DescribeUserProfileResultTypeDef = TypedDict(
+    "DescribeUserProfileResultTypeDef",
+    {
+        "userArn": str,
+        "displayName": str,
+        "emailAddress": str,
+        "sshPublicKey": str,
+        "createdTimestamp": datetime,
+        "lastModifiedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateTeamMemberRequestRequestTypeDef = TypedDict(
     "DisassociateTeamMemberRequestRequestTypeDef",
     {
         "projectId": str,
         "userArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
@@ -271,14 +320,36 @@
     {
         "projectId": str,
         "projectArn": str,
     },
     total=False,
 )
 
+_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourcesRequestListResourcesPaginateTypeDef(
+    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
+    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListResourcesRequestRequestTypeDef = TypedDict(
@@ -323,14 +394,45 @@
 class ListTagsForProjectRequestRequestTypeDef(
     _RequiredListTagsForProjectRequestRequestTypeDef,
     _OptionalListTagsForProjectRequestRequestTypeDef,
 ):
     pass
 
 
+ListTagsForProjectResultTypeDef = TypedDict(
+    "ListTagsForProjectResultTypeDef",
+    {
+        "tags": Dict[str, str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
+    "_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
+    "_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTeamMembersRequestListTeamMembersPaginateTypeDef(
+    _RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef,
+    _OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTeamMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListTeamMembersRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListTeamMembersRequestRequestTypeDef = TypedDict(
@@ -365,14 +467,22 @@
 )
 
 
 class TeamMemberTypeDef(_RequiredTeamMemberTypeDef, _OptionalTeamMemberTypeDef):
     pass
 
 
+ListUserProfilesRequestListUserProfilesPaginateTypeDef = TypedDict(
+    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListUserProfilesRequestRequestTypeDef = TypedDict(
     "ListUserProfilesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -385,22 +495,51 @@
         "displayName": str,
         "emailAddress": str,
         "sshPublicKey": str,
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
 TagProjectRequestRequestTypeDef = TypedDict(
     "TagProjectRequestRequestTypeDef",
     {
         "id": str,
         "tags": Mapping[str, str],
     },
 )
 
+TagProjectResultTypeDef = TypedDict(
+    "TagProjectResultTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagProjectRequestRequestTypeDef = TypedDict(
     "UntagProjectRequestRequestTypeDef",
     {
         "id": str,
         "tags": Sequence[str],
     },
 )
@@ -446,14 +585,24 @@
 
 class UpdateTeamMemberRequestRequestTypeDef(
     _RequiredUpdateTeamMemberRequestRequestTypeDef, _OptionalUpdateTeamMemberRequestRequestTypeDef
 ):
     pass
 
 
+UpdateTeamMemberResultTypeDef = TypedDict(
+    "UpdateTeamMemberResultTypeDef",
+    {
+        "userArn": str,
+        "projectRole": str,
+        "remoteAccessAllowed": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateUserProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
     },
 )
 _OptionalUpdateUserProfileRequestRequestTypeDef = TypedDict(
@@ -469,113 +618,24 @@
 
 class UpdateUserProfileRequestRequestTypeDef(
     _RequiredUpdateUserProfileRequestRequestTypeDef, _OptionalUpdateUserProfileRequestRequestTypeDef
 ):
     pass
 
 
-AssociateTeamMemberResultTypeDef = TypedDict(
-    "AssociateTeamMemberResultTypeDef",
-    {
-        "clientRequestToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProjectResultTypeDef = TypedDict(
-    "CreateProjectResultTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "clientRequestToken": str,
-        "projectTemplateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserProfileResultTypeDef = TypedDict(
-    "CreateUserProfileResultTypeDef",
-    {
-        "userArn": str,
-        "displayName": str,
-        "emailAddress": str,
-        "sshPublicKey": str,
-        "createdTimestamp": datetime,
-        "lastModifiedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProjectResultTypeDef = TypedDict(
-    "DeleteProjectResultTypeDef",
-    {
-        "stackId": str,
-        "projectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteUserProfileResultTypeDef = TypedDict(
-    "DeleteUserProfileResultTypeDef",
-    {
-        "userArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeUserProfileResultTypeDef = TypedDict(
-    "DescribeUserProfileResultTypeDef",
-    {
-        "userArn": str,
-        "displayName": str,
-        "emailAddress": str,
-        "sshPublicKey": str,
-        "createdTimestamp": datetime,
-        "lastModifiedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForProjectResultTypeDef = TypedDict(
-    "ListTagsForProjectResultTypeDef",
-    {
-        "tags": Dict[str, str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagProjectResultTypeDef = TypedDict(
-    "TagProjectResultTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTeamMemberResultTypeDef = TypedDict(
-    "UpdateTeamMemberResultTypeDef",
-    {
-        "userArn": str,
-        "projectRole": str,
-        "remoteAccessAllowed": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateUserProfileResultTypeDef = TypedDict(
     "UpdateUserProfileResultTypeDef",
     {
         "userArn": str,
         "displayName": str,
         "emailAddress": str,
         "sshPublicKey": str,
         "createdTimestamp": datetime,
         "lastModifiedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeDestinationTypeDef = TypedDict(
     "CodeDestinationTypeDef",
     {
         "codeCommit": CodeCommitCodeDestinationTypeDef,
@@ -606,111 +666,51 @@
         "arn": str,
         "description": str,
         "clientRequestToken": str,
         "createdTimeStamp": datetime,
         "stackId": str,
         "projectTemplateId": str,
         "status": ProjectStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResourcesRequestListResourcesPaginateTypeDef(
-    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
-    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
-    "_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
-    "_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTeamMembersRequestListTeamMembersPaginateTypeDef(
-    _RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef,
-    _OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef,
-):
-    pass
-
-
-ListUserProfilesRequestListUserProfilesPaginateTypeDef = TypedDict(
-    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListProjectsResultTypeDef = TypedDict(
     "ListProjectsResultTypeDef",
     {
         "projects": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResultTypeDef = TypedDict(
     "ListResourcesResultTypeDef",
     {
         "resources": List[ResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTeamMembersResultTypeDef = TypedDict(
     "ListTeamMembersResultTypeDef",
     {
         "teamMembers": List[TeamMemberTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserProfilesResultTypeDef = TypedDict(
     "ListUserProfilesResultTypeDef",
     {
         "userProfiles": List[UserProfileSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeTypeDef = TypedDict(
     "CodeTypeDef",
     {
         "source": CodeSourceTypeDef,
```

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar/type_defs.pyi` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -18,58 +18,58 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateTeamMemberRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateTeamMemberResultTypeDef",
     "CodeCommitCodeDestinationTypeDef",
     "GitHubCodeDestinationTypeDef",
     "S3LocationTypeDef",
+    "CreateProjectResultTypeDef",
     "CreateUserProfileRequestRequestTypeDef",
+    "CreateUserProfileResultTypeDef",
     "DeleteProjectRequestRequestTypeDef",
+    "DeleteProjectResultTypeDef",
     "DeleteUserProfileRequestRequestTypeDef",
+    "DeleteUserProfileResultTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "ProjectStatusTypeDef",
     "DescribeUserProfileRequestRequestTypeDef",
+    "DescribeUserProfileResultTypeDef",
     "DisassociateTeamMemberRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
+    "ListResourcesRequestListResourcesPaginateTypeDef",
     "ListResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
     "ListTagsForProjectRequestRequestTypeDef",
+    "ListTagsForProjectResultTypeDef",
+    "ListTeamMembersRequestListTeamMembersPaginateTypeDef",
     "ListTeamMembersRequestRequestTypeDef",
     "TeamMemberTypeDef",
+    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
     "ListUserProfilesRequestRequestTypeDef",
     "UserProfileSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagProjectRequestRequestTypeDef",
+    "TagProjectResultTypeDef",
     "UntagProjectRequestRequestTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "UpdateTeamMemberRequestRequestTypeDef",
-    "UpdateUserProfileRequestRequestTypeDef",
-    "AssociateTeamMemberResultTypeDef",
-    "CreateProjectResultTypeDef",
-    "CreateUserProfileResultTypeDef",
-    "DeleteProjectResultTypeDef",
-    "DeleteUserProfileResultTypeDef",
-    "DescribeUserProfileResultTypeDef",
-    "ListTagsForProjectResultTypeDef",
-    "TagProjectResultTypeDef",
     "UpdateTeamMemberResultTypeDef",
+    "UpdateUserProfileRequestRequestTypeDef",
     "UpdateUserProfileResultTypeDef",
     "CodeDestinationTypeDef",
     "CodeSourceTypeDef",
     "ToolchainSourceTypeDef",
     "DescribeProjectResultTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    "ListResourcesRequestListResourcesPaginateTypeDef",
-    "ListTeamMembersRequestListTeamMembersPaginateTypeDef",
-    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
     "ListProjectsResultTypeDef",
     "ListResourcesResultTypeDef",
     "ListTeamMembersResultTypeDef",
     "ListUserProfilesResultTypeDef",
     "CodeTypeDef",
     "ToolchainTypeDef",
     "CreateProjectRequestRequestTypeDef",
@@ -94,22 +94,19 @@
 
 class AssociateTeamMemberRequestRequestTypeDef(
     _RequiredAssociateTeamMemberRequestRequestTypeDef,
     _OptionalAssociateTeamMemberRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateTeamMemberResultTypeDef = TypedDict(
+    "AssociateTeamMemberResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "clientRequestToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeCommitCodeDestinationTypeDef = TypedDict(
     "CodeCommitCodeDestinationTypeDef",
     {
         "name": str,
@@ -145,14 +142,25 @@
     {
         "bucketName": str,
         "bucketKey": str,
     },
     total=False,
 )
 
+CreateProjectResultTypeDef = TypedDict(
+    "CreateProjectResultTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "clientRequestToken": str,
+        "projectTemplateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
         "displayName": str,
         "emailAddress": str,
     },
@@ -166,14 +174,27 @@
 )
 
 class CreateUserProfileRequestRequestTypeDef(
     _RequiredCreateUserProfileRequestRequestTypeDef, _OptionalCreateUserProfileRequestRequestTypeDef
 ):
     pass
 
+CreateUserProfileResultTypeDef = TypedDict(
+    "CreateUserProfileResultTypeDef",
+    {
+        "userArn": str,
+        "displayName": str,
+        "emailAddress": str,
+        "sshPublicKey": str,
+        "createdTimestamp": datetime,
+        "lastModifiedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteProjectRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteProjectRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalDeleteProjectRequestRequestTypeDef = TypedDict(
@@ -186,21 +207,38 @@
 )
 
 class DeleteProjectRequestRequestTypeDef(
     _RequiredDeleteProjectRequestRequestTypeDef, _OptionalDeleteProjectRequestRequestTypeDef
 ):
     pass
 
+DeleteProjectResultTypeDef = TypedDict(
+    "DeleteProjectResultTypeDef",
+    {
+        "stackId": str,
+        "projectArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteUserProfileRequestRequestTypeDef = TypedDict(
     "DeleteUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
     },
 )
 
+DeleteUserProfileResultTypeDef = TypedDict(
+    "DeleteUserProfileResultTypeDef",
+    {
+        "userArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeProjectRequestRequestTypeDef = TypedDict(
     "DescribeProjectRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -224,28 +262,39 @@
 DescribeUserProfileRequestRequestTypeDef = TypedDict(
     "DescribeUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
     },
 )
 
+DescribeUserProfileResultTypeDef = TypedDict(
+    "DescribeUserProfileResultTypeDef",
+    {
+        "userArn": str,
+        "displayName": str,
+        "emailAddress": str,
+        "sshPublicKey": str,
+        "createdTimestamp": datetime,
+        "lastModifiedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DisassociateTeamMemberRequestRequestTypeDef = TypedDict(
     "DisassociateTeamMemberRequestRequestTypeDef",
     {
         "projectId": str,
         "userArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
@@ -260,14 +309,34 @@
     {
         "projectId": str,
         "projectArn": str,
     },
     total=False,
 )
 
+_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourcesRequestListResourcesPaginateTypeDef(
+    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
+    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListResourcesRequestRequestTypeDef = TypedDict(
@@ -308,14 +377,43 @@
 
 class ListTagsForProjectRequestRequestTypeDef(
     _RequiredListTagsForProjectRequestRequestTypeDef,
     _OptionalListTagsForProjectRequestRequestTypeDef,
 ):
     pass
 
+ListTagsForProjectResultTypeDef = TypedDict(
+    "ListTagsForProjectResultTypeDef",
+    {
+        "tags": Dict[str, str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
+    "_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef",
+    {
+        "projectId": str,
+    },
+)
+_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
+    "_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTeamMembersRequestListTeamMembersPaginateTypeDef(
+    _RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef,
+    _OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef,
+):
+    pass
+
 _RequiredListTeamMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListTeamMembersRequestRequestTypeDef",
     {
         "projectId": str,
     },
 )
 _OptionalListTeamMembersRequestRequestTypeDef = TypedDict(
@@ -346,14 +444,22 @@
     },
     total=False,
 )
 
 class TeamMemberTypeDef(_RequiredTeamMemberTypeDef, _OptionalTeamMemberTypeDef):
     pass
 
+ListUserProfilesRequestListUserProfilesPaginateTypeDef = TypedDict(
+    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListUserProfilesRequestRequestTypeDef = TypedDict(
     "ListUserProfilesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -366,22 +472,51 @@
         "displayName": str,
         "emailAddress": str,
         "sshPublicKey": str,
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
 TagProjectRequestRequestTypeDef = TypedDict(
     "TagProjectRequestRequestTypeDef",
     {
         "id": str,
         "tags": Mapping[str, str],
     },
 )
 
+TagProjectResultTypeDef = TypedDict(
+    "TagProjectResultTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagProjectRequestRequestTypeDef = TypedDict(
     "UntagProjectRequestRequestTypeDef",
     {
         "id": str,
         "tags": Sequence[str],
     },
 )
@@ -423,14 +558,24 @@
 )
 
 class UpdateTeamMemberRequestRequestTypeDef(
     _RequiredUpdateTeamMemberRequestRequestTypeDef, _OptionalUpdateTeamMemberRequestRequestTypeDef
 ):
     pass
 
+UpdateTeamMemberResultTypeDef = TypedDict(
+    "UpdateTeamMemberResultTypeDef",
+    {
+        "userArn": str,
+        "projectRole": str,
+        "remoteAccessAllowed": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateUserProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUserProfileRequestRequestTypeDef",
     {
         "userArn": str,
     },
 )
 _OptionalUpdateUserProfileRequestRequestTypeDef = TypedDict(
@@ -444,113 +589,24 @@
 )
 
 class UpdateUserProfileRequestRequestTypeDef(
     _RequiredUpdateUserProfileRequestRequestTypeDef, _OptionalUpdateUserProfileRequestRequestTypeDef
 ):
     pass
 
-AssociateTeamMemberResultTypeDef = TypedDict(
-    "AssociateTeamMemberResultTypeDef",
-    {
-        "clientRequestToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProjectResultTypeDef = TypedDict(
-    "CreateProjectResultTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "clientRequestToken": str,
-        "projectTemplateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserProfileResultTypeDef = TypedDict(
-    "CreateUserProfileResultTypeDef",
-    {
-        "userArn": str,
-        "displayName": str,
-        "emailAddress": str,
-        "sshPublicKey": str,
-        "createdTimestamp": datetime,
-        "lastModifiedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProjectResultTypeDef = TypedDict(
-    "DeleteProjectResultTypeDef",
-    {
-        "stackId": str,
-        "projectArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteUserProfileResultTypeDef = TypedDict(
-    "DeleteUserProfileResultTypeDef",
-    {
-        "userArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeUserProfileResultTypeDef = TypedDict(
-    "DescribeUserProfileResultTypeDef",
-    {
-        "userArn": str,
-        "displayName": str,
-        "emailAddress": str,
-        "sshPublicKey": str,
-        "createdTimestamp": datetime,
-        "lastModifiedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForProjectResultTypeDef = TypedDict(
-    "ListTagsForProjectResultTypeDef",
-    {
-        "tags": Dict[str, str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagProjectResultTypeDef = TypedDict(
-    "TagProjectResultTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateTeamMemberResultTypeDef = TypedDict(
-    "UpdateTeamMemberResultTypeDef",
-    {
-        "userArn": str,
-        "projectRole": str,
-        "remoteAccessAllowed": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateUserProfileResultTypeDef = TypedDict(
     "UpdateUserProfileResultTypeDef",
     {
         "userArn": str,
         "displayName": str,
         "emailAddress": str,
         "sshPublicKey": str,
         "createdTimestamp": datetime,
         "lastModifiedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeDestinationTypeDef = TypedDict(
     "CodeDestinationTypeDef",
     {
         "codeCommit": CodeCommitCodeDestinationTypeDef,
@@ -581,107 +637,51 @@
         "arn": str,
         "description": str,
         "clientRequestToken": str,
         "createdTimeStamp": datetime,
         "stackId": str,
         "projectTemplateId": str,
         "status": ProjectStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-_RequiredListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListResourcesRequestListResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListResourcesRequestListResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResourcesRequestListResourcesPaginateTypeDef(
-    _RequiredListResourcesRequestListResourcesPaginateTypeDef,
-    _OptionalListResourcesRequestListResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
-    "_RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef",
-    {
-        "projectId": str,
-    },
-)
-_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef = TypedDict(
-    "_OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTeamMembersRequestListTeamMembersPaginateTypeDef(
-    _RequiredListTeamMembersRequestListTeamMembersPaginateTypeDef,
-    _OptionalListTeamMembersRequestListTeamMembersPaginateTypeDef,
-):
-    pass
-
-ListUserProfilesRequestListUserProfilesPaginateTypeDef = TypedDict(
-    "ListUserProfilesRequestListUserProfilesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListProjectsResultTypeDef = TypedDict(
     "ListProjectsResultTypeDef",
     {
         "projects": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourcesResultTypeDef = TypedDict(
     "ListResourcesResultTypeDef",
     {
         "resources": List[ResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTeamMembersResultTypeDef = TypedDict(
     "ListTeamMembersResultTypeDef",
     {
         "teamMembers": List[TeamMemberTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUserProfilesResultTypeDef = TypedDict(
     "ListUserProfilesResultTypeDef",
     {
         "userProfiles": List[UserProfileSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeTypeDef = TypedDict(
     "CodeTypeDef",
     {
         "source": CodeSourceTypeDef,
```

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/PKG-INFO` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codestar
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeStar 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeStar 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codestar"></a>
 
 # types-aiobotocore-codestar
 
 [![PyPI - types-aiobotocore-codestar](https://img.shields.io/pypi/v/types-aiobotocore-codestar.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStar 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
+[aiobotocore.CodeStar 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar.html#CodeStar)
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
 [types-aiobotocore-codestar docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar/).
 
 See how it helps to find and fix potential bugs:
 
@@ -329,58 +329,58 @@
 
 `types_aiobotocore_codestar.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar.type_defs import (
     AssociateTeamMemberRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateTeamMemberResultTypeDef,
     CodeCommitCodeDestinationTypeDef,
     GitHubCodeDestinationTypeDef,
     S3LocationTypeDef,
+    CreateProjectResultTypeDef,
     CreateUserProfileRequestRequestTypeDef,
+    CreateUserProfileResultTypeDef,
     DeleteProjectRequestRequestTypeDef,
+    DeleteProjectResultTypeDef,
     DeleteUserProfileRequestRequestTypeDef,
+    DeleteUserProfileResultTypeDef,
     DescribeProjectRequestRequestTypeDef,
     ProjectStatusTypeDef,
     DescribeUserProfileRequestRequestTypeDef,
+    DescribeUserProfileResultTypeDef,
     DisassociateTeamMemberRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
+    ListResourcesRequestListResourcesPaginateTypeDef,
     ListResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListTagsForProjectRequestRequestTypeDef,
+    ListTagsForProjectResultTypeDef,
+    ListTeamMembersRequestListTeamMembersPaginateTypeDef,
     ListTeamMembersRequestRequestTypeDef,
     TeamMemberTypeDef,
+    ListUserProfilesRequestListUserProfilesPaginateTypeDef,
     ListUserProfilesRequestRequestTypeDef,
     UserProfileSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagProjectRequestRequestTypeDef,
+    TagProjectResultTypeDef,
     UntagProjectRequestRequestTypeDef,
     UpdateProjectRequestRequestTypeDef,
     UpdateTeamMemberRequestRequestTypeDef,
-    UpdateUserProfileRequestRequestTypeDef,
-    AssociateTeamMemberResultTypeDef,
-    CreateProjectResultTypeDef,
-    CreateUserProfileResultTypeDef,
-    DeleteProjectResultTypeDef,
-    DeleteUserProfileResultTypeDef,
-    DescribeUserProfileResultTypeDef,
-    ListTagsForProjectResultTypeDef,
-    TagProjectResultTypeDef,
     UpdateTeamMemberResultTypeDef,
+    UpdateUserProfileRequestRequestTypeDef,
     UpdateUserProfileResultTypeDef,
     CodeDestinationTypeDef,
     CodeSourceTypeDef,
     ToolchainSourceTypeDef,
     DescribeProjectResultTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListResourcesRequestListResourcesPaginateTypeDef,
-    ListTeamMembersRequestListTeamMembersPaginateTypeDef,
-    ListUserProfilesRequestListUserProfilesPaginateTypeDef,
     ListProjectsResultTypeDef,
     ListResourcesResultTypeDef,
     ListTeamMembersResultTypeDef,
     ListUserProfilesResultTypeDef,
     CodeTypeDef,
     ToolchainTypeDef,
     CreateProjectRequestRequestTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-codestar-2.5.0.post1/types_aiobotocore_codestar.egg-info/SOURCES.txt` & `types-aiobotocore-codestar-2.5.1/types_aiobotocore_codestar.egg-info/SOURCES.txt`

 * *Files identical despite different names*

