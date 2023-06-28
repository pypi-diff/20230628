# Comparing `tmp/types-aiobotocore-codecatalyst-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codecatalyst-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codecatalyst-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:22 2023, max compression
+gzip compressed data, was "types-aiobotocore-codecatalyst-2.5.1.tar", last modified: Wed Jun 28 01:43:15 2023, max compression
```

## Comparing `types-aiobotocore-codecatalyst-2.5.0.post1.tar` & `types-aiobotocore-codecatalyst-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.451049 types-aiobotocore-codecatalyst-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17489 2023-03-11 12:26:22.451049 types-aiobotocore-codecatalyst-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15898 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:22.451049 types-aiobotocore-codecatalyst-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.443049 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/
--rw-r--r--   0 runner    (1001) docker     (123)     1995 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1994 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23946 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23906 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9009 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9007 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9581 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9571 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    31864 2023-03-11 12:11:13.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    31805 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:12.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.451049 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17489 2023-03-11 12:26:22.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:22.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:22.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:22.000000 types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.730111 types-aiobotocore-codecatalyst-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18044 2023-06-28 01:43:15.730111 types-aiobotocore-codecatalyst-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16459 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:15.730111 types-aiobotocore-codecatalyst-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.726111 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/
+-rw-r--r--   0 runner    (1001) docker     (123)     2261 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2260 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25879 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25836 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9385 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9383 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10810 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10800 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    34784 2023-06-28 01:27:49.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34721 2023-06-28 01:27:49.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:48.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.730111 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18044 2023-06-28 01:43:15.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:15.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:15.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:15.000000 types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/LICENSE` & `types-aiobotocore-codecatalyst-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codecatalyst-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codecatalyst
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeCatalyst 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeCatalyst 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codecatalyst"></a>
 
 # types-aiobotocore-codecatalyst
 
 [![PyPI - types-aiobotocore-codecatalyst](https://img.shields.io/pypi/v/types-aiobotocore-codecatalyst.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codecatalyst)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codecatalyst.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codecatalyst)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codecatalyst?color=blue)](https://pypistats.org/packages/types-aiobotocore-codecatalyst)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeCatalyst 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst)
+[aiobotocore.CodeCatalyst 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst)
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
 [types-aiobotocore-codecatalyst docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,14 +274,15 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_codecatalyst import CodeCatalystClient
 from types_aiobotocore_codecatalyst.paginator import (
     ListAccessTokensPaginator,
+    ListDevEnvironmentSessionsPaginator,
     ListDevEnvironmentsPaginator,
     ListEventLogsPaginator,
     ListProjectsPaginator,
     ListSourceRepositoriesPaginator,
     ListSourceRepositoryBranchesPaginator,
     ListSpacesPaginator,
 )
@@ -291,14 +292,17 @@
     client: CodeCatalystClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_access_tokens_paginator: ListAccessTokensPaginator = client.get_paginator(
         "list_access_tokens"
     )
+    list_dev_environment_sessions_paginator: ListDevEnvironmentSessionsPaginator = (
+        client.get_paginator("list_dev_environment_sessions")
+    )
     list_dev_environments_paginator: ListDevEnvironmentsPaginator = client.get_paginator(
         "list_dev_environments"
     )
     list_event_logs_paginator: ListEventLogsPaginator = client.get_paginator("list_event_logs")
     list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     list_source_repositories_paginator: ListSourceRepositoriesPaginator = client.get_paginator(
         "list_source_repositories"
@@ -320,14 +324,15 @@
 from types_aiobotocore_codecatalyst.literals import (
     ComparisonOperatorType,
     DevEnvironmentSessionTypeType,
     DevEnvironmentStatusType,
     FilterKeyType,
     InstanceTypeType,
     ListAccessTokensPaginatorName,
+    ListDevEnvironmentSessionsPaginatorName,
     ListDevEnvironmentsPaginatorName,
     ListEventLogsPaginatorName,
     ListProjectsPaginatorName,
     ListSourceRepositoriesPaginatorName,
     ListSourceRepositoryBranchesPaginatorName,
     ListSpacesPaginatorName,
     OperationTypeType,
@@ -350,80 +355,86 @@
 `types_aiobotocore_codecatalyst.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codecatalyst.type_defs import (
     AccessTokenSummaryTypeDef,
     CreateAccessTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessTokenResponseTypeDef,
     IdeConfigurationTypeDef,
     PersistentStorageConfigurationTypeDef,
     RepositoryInputTypeDef,
+    CreateDevEnvironmentResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
     CreateSourceRepositoryBranchRequestRequestTypeDef,
+    CreateSourceRepositoryBranchResponseTypeDef,
     DeleteAccessTokenRequestRequestTypeDef,
     DeleteDevEnvironmentRequestRequestTypeDef,
+    DeleteDevEnvironmentResponseTypeDef,
     DevEnvironmentAccessDetailsTypeDef,
     DevEnvironmentRepositorySummaryTypeDef,
     ExecuteCommandSessionConfigurationTypeDef,
+    DevEnvironmentSessionSummaryTypeDef,
     IdeTypeDef,
     PersistentStorageTypeDef,
     EmailAddressTypeDef,
     EventPayloadTypeDef,
     ProjectInformationTypeDef,
     UserIdentityTypeDef,
     FilterTypeDef,
     GetDevEnvironmentRequestRequestTypeDef,
     GetProjectRequestRequestTypeDef,
+    GetProjectResponseTypeDef,
     GetSourceRepositoryCloneUrlsRequestRequestTypeDef,
+    GetSourceRepositoryCloneUrlsResponseTypeDef,
     GetSpaceRequestRequestTypeDef,
+    GetSpaceResponseTypeDef,
     GetSubscriptionRequestRequestTypeDef,
+    GetSubscriptionResponseTypeDef,
     GetUserDetailsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessTokensRequestListAccessTokensPaginateTypeDef,
     ListAccessTokensRequestRequestTypeDef,
+    ListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef,
+    ListDevEnvironmentSessionsRequestRequestTypeDef,
+    ListEventLogsRequestListEventLogsPaginateTypeDef,
     ListEventLogsRequestRequestTypeDef,
     ProjectListFilterTypeDef,
     ProjectSummaryTypeDef,
     ListSourceRepositoriesItemTypeDef,
+    ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
     ListSourceRepositoriesRequestRequestTypeDef,
     ListSourceRepositoryBranchesItemTypeDef,
+    ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
     ListSourceRepositoryBranchesRequestRequestTypeDef,
+    ListSpacesRequestListSpacesPaginateTypeDef,
     ListSpacesRequestRequestTypeDef,
     SpaceSummaryTypeDef,
-    StopDevEnvironmentRequestRequestTypeDef,
-    CreateAccessTokenResponseTypeDef,
-    CreateDevEnvironmentResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    CreateSourceRepositoryBranchResponseTypeDef,
-    DeleteDevEnvironmentResponseTypeDef,
-    GetProjectResponseTypeDef,
-    GetSourceRepositoryCloneUrlsResponseTypeDef,
-    GetSpaceResponseTypeDef,
-    GetSubscriptionResponseTypeDef,
-    ListAccessTokensResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentRequestRequestTypeDef,
     StopDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentSessionRequestRequestTypeDef,
+    StopDevEnvironmentSessionResponseTypeDef,
     VerifySessionResponseTypeDef,
+    ListAccessTokensResponseTypeDef,
     StartDevEnvironmentRequestRequestTypeDef,
     UpdateDevEnvironmentRequestRequestTypeDef,
     UpdateDevEnvironmentResponseTypeDef,
     CreateDevEnvironmentRequestRequestTypeDef,
     StartDevEnvironmentSessionResponseTypeDef,
     DevEnvironmentSessionConfigurationTypeDef,
+    ListDevEnvironmentSessionsResponseTypeDef,
     DevEnvironmentSummaryTypeDef,
     GetDevEnvironmentResponseTypeDef,
     GetUserDetailsResponseTypeDef,
     EventLogEntryTypeDef,
-    ListDevEnvironmentsRequestRequestTypeDef,
-    ListAccessTokensRequestListAccessTokensPaginateTypeDef,
     ListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef,
-    ListEventLogsRequestListEventLogsPaginateTypeDef,
-    ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
-    ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
-    ListSpacesRequestListSpacesPaginateTypeDef,
+    ListDevEnvironmentsRequestRequestTypeDef,
     ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ListProjectsResponseTypeDef,
     ListSourceRepositoriesResponseTypeDef,
     ListSourceRepositoryBranchesResponseTypeDef,
     ListSpacesResponseTypeDef,
     StartDevEnvironmentSessionRequestRequestTypeDef,
@@ -439,43 +450,43 @@
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

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/README.md` & `types-aiobotocore-codecatalyst-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codecatalyst"></a>
 
 # types-aiobotocore-codecatalyst
 
 [![PyPI - types-aiobotocore-codecatalyst](https://img.shields.io/pypi/v/types-aiobotocore-codecatalyst.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codecatalyst)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codecatalyst.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codecatalyst)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codecatalyst?color=blue)](https://pypistats.org/packages/types-aiobotocore-codecatalyst)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeCatalyst 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst)
+[aiobotocore.CodeCatalyst 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst)
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
 [types-aiobotocore-codecatalyst docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/).
 
 See how it helps to find and fix potential bugs:
 
@@ -241,14 +241,15 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_codecatalyst import CodeCatalystClient
 from types_aiobotocore_codecatalyst.paginator import (
     ListAccessTokensPaginator,
+    ListDevEnvironmentSessionsPaginator,
     ListDevEnvironmentsPaginator,
     ListEventLogsPaginator,
     ListProjectsPaginator,
     ListSourceRepositoriesPaginator,
     ListSourceRepositoryBranchesPaginator,
     ListSpacesPaginator,
 )
@@ -258,14 +259,17 @@
     client: CodeCatalystClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_access_tokens_paginator: ListAccessTokensPaginator = client.get_paginator(
         "list_access_tokens"
     )
+    list_dev_environment_sessions_paginator: ListDevEnvironmentSessionsPaginator = (
+        client.get_paginator("list_dev_environment_sessions")
+    )
     list_dev_environments_paginator: ListDevEnvironmentsPaginator = client.get_paginator(
         "list_dev_environments"
     )
     list_event_logs_paginator: ListEventLogsPaginator = client.get_paginator("list_event_logs")
     list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     list_source_repositories_paginator: ListSourceRepositoriesPaginator = client.get_paginator(
         "list_source_repositories"
@@ -287,14 +291,15 @@
 from types_aiobotocore_codecatalyst.literals import (
     ComparisonOperatorType,
     DevEnvironmentSessionTypeType,
     DevEnvironmentStatusType,
     FilterKeyType,
     InstanceTypeType,
     ListAccessTokensPaginatorName,
+    ListDevEnvironmentSessionsPaginatorName,
     ListDevEnvironmentsPaginatorName,
     ListEventLogsPaginatorName,
     ListProjectsPaginatorName,
     ListSourceRepositoriesPaginatorName,
     ListSourceRepositoryBranchesPaginatorName,
     ListSpacesPaginatorName,
     OperationTypeType,
@@ -317,80 +322,86 @@
 `types_aiobotocore_codecatalyst.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codecatalyst.type_defs import (
     AccessTokenSummaryTypeDef,
     CreateAccessTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessTokenResponseTypeDef,
     IdeConfigurationTypeDef,
     PersistentStorageConfigurationTypeDef,
     RepositoryInputTypeDef,
+    CreateDevEnvironmentResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
     CreateSourceRepositoryBranchRequestRequestTypeDef,
+    CreateSourceRepositoryBranchResponseTypeDef,
     DeleteAccessTokenRequestRequestTypeDef,
     DeleteDevEnvironmentRequestRequestTypeDef,
+    DeleteDevEnvironmentResponseTypeDef,
     DevEnvironmentAccessDetailsTypeDef,
     DevEnvironmentRepositorySummaryTypeDef,
     ExecuteCommandSessionConfigurationTypeDef,
+    DevEnvironmentSessionSummaryTypeDef,
     IdeTypeDef,
     PersistentStorageTypeDef,
     EmailAddressTypeDef,
     EventPayloadTypeDef,
     ProjectInformationTypeDef,
     UserIdentityTypeDef,
     FilterTypeDef,
     GetDevEnvironmentRequestRequestTypeDef,
     GetProjectRequestRequestTypeDef,
+    GetProjectResponseTypeDef,
     GetSourceRepositoryCloneUrlsRequestRequestTypeDef,
+    GetSourceRepositoryCloneUrlsResponseTypeDef,
     GetSpaceRequestRequestTypeDef,
+    GetSpaceResponseTypeDef,
     GetSubscriptionRequestRequestTypeDef,
+    GetSubscriptionResponseTypeDef,
     GetUserDetailsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessTokensRequestListAccessTokensPaginateTypeDef,
     ListAccessTokensRequestRequestTypeDef,
+    ListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef,
+    ListDevEnvironmentSessionsRequestRequestTypeDef,
+    ListEventLogsRequestListEventLogsPaginateTypeDef,
     ListEventLogsRequestRequestTypeDef,
     ProjectListFilterTypeDef,
     ProjectSummaryTypeDef,
     ListSourceRepositoriesItemTypeDef,
+    ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
     ListSourceRepositoriesRequestRequestTypeDef,
     ListSourceRepositoryBranchesItemTypeDef,
+    ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
     ListSourceRepositoryBranchesRequestRequestTypeDef,
+    ListSpacesRequestListSpacesPaginateTypeDef,
     ListSpacesRequestRequestTypeDef,
     SpaceSummaryTypeDef,
-    StopDevEnvironmentRequestRequestTypeDef,
-    CreateAccessTokenResponseTypeDef,
-    CreateDevEnvironmentResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    CreateSourceRepositoryBranchResponseTypeDef,
-    DeleteDevEnvironmentResponseTypeDef,
-    GetProjectResponseTypeDef,
-    GetSourceRepositoryCloneUrlsResponseTypeDef,
-    GetSpaceResponseTypeDef,
-    GetSubscriptionResponseTypeDef,
-    ListAccessTokensResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentRequestRequestTypeDef,
     StopDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentSessionRequestRequestTypeDef,
+    StopDevEnvironmentSessionResponseTypeDef,
     VerifySessionResponseTypeDef,
+    ListAccessTokensResponseTypeDef,
     StartDevEnvironmentRequestRequestTypeDef,
     UpdateDevEnvironmentRequestRequestTypeDef,
     UpdateDevEnvironmentResponseTypeDef,
     CreateDevEnvironmentRequestRequestTypeDef,
     StartDevEnvironmentSessionResponseTypeDef,
     DevEnvironmentSessionConfigurationTypeDef,
+    ListDevEnvironmentSessionsResponseTypeDef,
     DevEnvironmentSummaryTypeDef,
     GetDevEnvironmentResponseTypeDef,
     GetUserDetailsResponseTypeDef,
     EventLogEntryTypeDef,
-    ListDevEnvironmentsRequestRequestTypeDef,
-    ListAccessTokensRequestListAccessTokensPaginateTypeDef,
     ListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef,
-    ListEventLogsRequestListEventLogsPaginateTypeDef,
-    ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
-    ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
-    ListSpacesRequestListSpacesPaginateTypeDef,
+    ListDevEnvironmentsRequestRequestTypeDef,
     ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ListProjectsResponseTypeDef,
     ListSourceRepositoriesResponseTypeDef,
     ListSourceRepositoryBranchesResponseTypeDef,
     ListSpacesResponseTypeDef,
     StartDevEnvironmentSessionRequestRequestTypeDef,
@@ -406,43 +417,43 @@
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

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/setup.py` & `types-aiobotocore-codecatalyst-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codecatalyst.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codecatalyst",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codecatalyst"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeCatalyst 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodeCatalyst 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/"
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

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/__init__.py` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/__init__.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_codecatalyst import (
         Client,
         CodeCatalystClient,
         ListAccessTokensPaginator,
+        ListDevEnvironmentSessionsPaginator,
         ListDevEnvironmentsPaginator,
         ListEventLogsPaginator,
         ListProjectsPaginator,
         ListSourceRepositoriesPaginator,
         ListSourceRepositoryBranchesPaginator,
         ListSpacesPaginator,
     )
@@ -20,40 +21,42 @@
     session = get_session()
     async with session.create_client("codecatalyst") as client:
         client: CodeCatalystClient
         ...
 
 
     list_access_tokens_paginator: ListAccessTokensPaginator = client.get_paginator("list_access_tokens")
+    list_dev_environment_sessions_paginator: ListDevEnvironmentSessionsPaginator = client.get_paginator("list_dev_environment_sessions")
     list_dev_environments_paginator: ListDevEnvironmentsPaginator = client.get_paginator("list_dev_environments")
     list_event_logs_paginator: ListEventLogsPaginator = client.get_paginator("list_event_logs")
     list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     list_source_repositories_paginator: ListSourceRepositoriesPaginator = client.get_paginator("list_source_repositories")
     list_source_repository_branches_paginator: ListSourceRepositoryBranchesPaginator = client.get_paginator("list_source_repository_branches")
     list_spaces_paginator: ListSpacesPaginator = client.get_paginator("list_spaces")
     ```
 """
 from .client import CodeCatalystClient
 from .paginator import (
     ListAccessTokensPaginator,
+    ListDevEnvironmentSessionsPaginator,
     ListDevEnvironmentsPaginator,
     ListEventLogsPaginator,
     ListProjectsPaginator,
     ListSourceRepositoriesPaginator,
     ListSourceRepositoryBranchesPaginator,
     ListSpacesPaginator,
 )
 
 Client = CodeCatalystClient
 
-
 __all__ = (
     "Client",
     "CodeCatalystClient",
     "ListAccessTokensPaginator",
+    "ListDevEnvironmentSessionsPaginator",
     "ListDevEnvironmentsPaginator",
     "ListEventLogsPaginator",
     "ListProjectsPaginator",
     "ListSourceRepositoriesPaginator",
     "ListSourceRepositoryBranchesPaginator",
     "ListSpacesPaginator",
 )
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/__init__.pyi` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_codecatalyst import (
         Client,
         CodeCatalystClient,
         ListAccessTokensPaginator,
+        ListDevEnvironmentSessionsPaginator,
         ListDevEnvironmentsPaginator,
         ListEventLogsPaginator,
         ListProjectsPaginator,
         ListSourceRepositoriesPaginator,
         ListSourceRepositoryBranchesPaginator,
         ListSpacesPaginator,
     )
@@ -20,39 +21,43 @@
     session = get_session()
     async with session.create_client("codecatalyst") as client:
         client: CodeCatalystClient
         ...
 
 
     list_access_tokens_paginator: ListAccessTokensPaginator = client.get_paginator("list_access_tokens")
+    list_dev_environment_sessions_paginator: ListDevEnvironmentSessionsPaginator = client.get_paginator("list_dev_environment_sessions")
     list_dev_environments_paginator: ListDevEnvironmentsPaginator = client.get_paginator("list_dev_environments")
     list_event_logs_paginator: ListEventLogsPaginator = client.get_paginator("list_event_logs")
     list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     list_source_repositories_paginator: ListSourceRepositoriesPaginator = client.get_paginator("list_source_repositories")
     list_source_repository_branches_paginator: ListSourceRepositoryBranchesPaginator = client.get_paginator("list_source_repository_branches")
     list_spaces_paginator: ListSpacesPaginator = client.get_paginator("list_spaces")
     ```
 """
 from .client import CodeCatalystClient
 from .paginator import (
     ListAccessTokensPaginator,
+    ListDevEnvironmentSessionsPaginator,
     ListDevEnvironmentsPaginator,
     ListEventLogsPaginator,
     ListProjectsPaginator,
     ListSourceRepositoriesPaginator,
     ListSourceRepositoryBranchesPaginator,
     ListSpacesPaginator,
 )
 
 Client = CodeCatalystClient
 
+
 __all__ = (
     "Client",
     "CodeCatalystClient",
     "ListAccessTokensPaginator",
+    "ListDevEnvironmentSessionsPaginator",
     "ListDevEnvironmentsPaginator",
     "ListEventLogsPaginator",
     "ListProjectsPaginator",
     "ListSourceRepositoriesPaginator",
     "ListSourceRepositoryBranchesPaginator",
     "ListSpacesPaginator",
 )
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/__main__.py` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeCatalyst 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeCatalyst 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst\nOther"
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

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/client.py` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,14 +20,15 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import InstanceTypeType
 from .paginator import (
     ListAccessTokensPaginator,
+    ListDevEnvironmentSessionsPaginator,
     ListDevEnvironmentsPaginator,
     ListEventLogsPaginator,
     ListProjectsPaginator,
     ListSourceRepositoriesPaginator,
     ListSourceRepositoryBranchesPaginator,
     ListSpacesPaginator,
 )
@@ -43,26 +44,28 @@
     GetProjectResponseTypeDef,
     GetSourceRepositoryCloneUrlsResponseTypeDef,
     GetSpaceResponseTypeDef,
     GetSubscriptionResponseTypeDef,
     GetUserDetailsResponseTypeDef,
     IdeConfigurationTypeDef,
     ListAccessTokensResponseTypeDef,
+    ListDevEnvironmentSessionsResponseTypeDef,
     ListDevEnvironmentsResponseTypeDef,
     ListEventLogsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListSourceRepositoriesResponseTypeDef,
     ListSourceRepositoryBranchesResponseTypeDef,
     ListSpacesResponseTypeDef,
     PersistentStorageConfigurationTypeDef,
     ProjectListFilterTypeDef,
     RepositoryInputTypeDef,
     StartDevEnvironmentResponseTypeDef,
     StartDevEnvironmentSessionResponseTypeDef,
     StopDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentSessionResponseTypeDef,
     UpdateDevEnvironmentResponseTypeDef,
     VerifySessionResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -143,16 +146,16 @@
         repositories: Sequence[RepositoryInputTypeDef] = ...,
         clientToken: str = ...,
         alias: str = ...,
         ides: Sequence[IdeConfigurationTypeDef] = ...,
         inactivityTimeoutMinutes: int = ...
     ) -> CreateDevEnvironmentResponseTypeDef:
         """
-        Creates a Dev Environment in Amazon CodeCatalyst, a cloud-based development Dev
-        Environment that you can use to quickly work on the code stored in the source
+        Creates a Dev Environment in Amazon CodeCatalyst, a cloud-based development
+        environment that you can use to quickly work on the code stored in the source
         repositories of your project.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.create_dev_environment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#create_dev_environment)
         """
 
     async def create_project(
@@ -277,25 +280,41 @@
         Lists all personal access tokens (PATs) associated with the user who calls the
         API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.list_access_tokens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#list_access_tokens)
         """
 
+    async def list_dev_environment_sessions(
+        self,
+        *,
+        spaceName: str,
+        projectName: str,
+        devEnvironmentId: str,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListDevEnvironmentSessionsResponseTypeDef:
+        """
+        Retrieves a list of active sessions for a Dev Environment in a project.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.list_dev_environment_sessions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#list_dev_environment_sessions)
+        """
+
     async def list_dev_environments(
         self,
         *,
         spaceName: str,
         projectName: str,
         filters: Sequence[FilterTypeDef] = ...,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> ListDevEnvironmentsResponseTypeDef:
         """
-        Retrives a list of Dev Environments in a project.
+        Retrieves a list of Dev Environments in a project.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.list_dev_environments)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#list_dev_environments)
         """
 
     async def list_event_logs(
         self,
@@ -402,14 +421,24 @@
         """
         Pauses a specified Dev Environment and places it in a non-running state.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.stop_dev_environment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#stop_dev_environment)
         """
 
+    async def stop_dev_environment_session(
+        self, *, spaceName: str, projectName: str, id: str, sessionId: str
+    ) -> StopDevEnvironmentSessionResponseTypeDef:
+        """
+        Stops a session for a specified Dev Environment.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.stop_dev_environment_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#stop_dev_environment_session)
+        """
+
     async def update_dev_environment(
         self,
         *,
         spaceName: str,
         projectName: str,
         id: str,
         alias: str = ...,
@@ -441,14 +470,23 @@
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#get_paginator)
         """
 
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_dev_environment_sessions"]
+    ) -> ListDevEnvironmentSessionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_dev_environments"]
     ) -> ListDevEnvironmentsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#get_paginator)
         """
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/client.pyi` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/client.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -20,14 +20,15 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import InstanceTypeType
 from .paginator import (
     ListAccessTokensPaginator,
+    ListDevEnvironmentSessionsPaginator,
     ListDevEnvironmentsPaginator,
     ListEventLogsPaginator,
     ListProjectsPaginator,
     ListSourceRepositoriesPaginator,
     ListSourceRepositoryBranchesPaginator,
     ListSpacesPaginator,
 )
@@ -43,26 +44,28 @@
     GetProjectResponseTypeDef,
     GetSourceRepositoryCloneUrlsResponseTypeDef,
     GetSpaceResponseTypeDef,
     GetSubscriptionResponseTypeDef,
     GetUserDetailsResponseTypeDef,
     IdeConfigurationTypeDef,
     ListAccessTokensResponseTypeDef,
+    ListDevEnvironmentSessionsResponseTypeDef,
     ListDevEnvironmentsResponseTypeDef,
     ListEventLogsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListSourceRepositoriesResponseTypeDef,
     ListSourceRepositoryBranchesResponseTypeDef,
     ListSpacesResponseTypeDef,
     PersistentStorageConfigurationTypeDef,
     ProjectListFilterTypeDef,
     RepositoryInputTypeDef,
     StartDevEnvironmentResponseTypeDef,
     StartDevEnvironmentSessionResponseTypeDef,
     StopDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentSessionResponseTypeDef,
     UpdateDevEnvironmentResponseTypeDef,
     VerifySessionResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -135,16 +138,16 @@
         repositories: Sequence[RepositoryInputTypeDef] = ...,
         clientToken: str = ...,
         alias: str = ...,
         ides: Sequence[IdeConfigurationTypeDef] = ...,
         inactivityTimeoutMinutes: int = ...
     ) -> CreateDevEnvironmentResponseTypeDef:
         """
-        Creates a Dev Environment in Amazon CodeCatalyst, a cloud-based development Dev
-        Environment that you can use to quickly work on the code stored in the source
+        Creates a Dev Environment in Amazon CodeCatalyst, a cloud-based development
+        environment that you can use to quickly work on the code stored in the source
         repositories of your project.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.create_dev_environment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#create_dev_environment)
         """
     async def create_project(
         self, *, spaceName: str, displayName: str, description: str = ...
@@ -256,25 +259,40 @@
         """
         Lists all personal access tokens (PATs) associated with the user who calls the
         API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.list_access_tokens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#list_access_tokens)
         """
+    async def list_dev_environment_sessions(
+        self,
+        *,
+        spaceName: str,
+        projectName: str,
+        devEnvironmentId: str,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListDevEnvironmentSessionsResponseTypeDef:
+        """
+        Retrieves a list of active sessions for a Dev Environment in a project.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.list_dev_environment_sessions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#list_dev_environment_sessions)
+        """
     async def list_dev_environments(
         self,
         *,
         spaceName: str,
         projectName: str,
         filters: Sequence[FilterTypeDef] = ...,
         nextToken: str = ...,
         maxResults: int = ...
     ) -> ListDevEnvironmentsResponseTypeDef:
         """
-        Retrives a list of Dev Environments in a project.
+        Retrieves a list of Dev Environments in a project.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.list_dev_environments)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#list_dev_environments)
         """
     async def list_event_logs(
         self,
         *,
@@ -372,14 +390,23 @@
     ) -> StopDevEnvironmentResponseTypeDef:
         """
         Pauses a specified Dev Environment and places it in a non-running state.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.stop_dev_environment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#stop_dev_environment)
         """
+    async def stop_dev_environment_session(
+        self, *, spaceName: str, projectName: str, id: str, sessionId: str
+    ) -> StopDevEnvironmentSessionResponseTypeDef:
+        """
+        Stops a session for a specified Dev Environment.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.stop_dev_environment_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#stop_dev_environment_session)
+        """
     async def update_dev_environment(
         self,
         *,
         spaceName: str,
         projectName: str,
         id: str,
         alias: str = ...,
@@ -408,14 +435,22 @@
     ) -> ListAccessTokensPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#get_paginator)
         """
     @overload
     def get_paginator(
+        self, operation_name: Literal["list_dev_environment_sessions"]
+    ) -> ListDevEnvironmentSessionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
         self, operation_name: Literal["list_dev_environments"]
     ) -> ListDevEnvironmentsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/client/#get_paginator)
         """
     @overload
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/literals.py` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 __all__ = (
     "ComparisonOperatorType",
     "DevEnvironmentSessionTypeType",
     "DevEnvironmentStatusType",
     "FilterKeyType",
     "InstanceTypeType",
     "ListAccessTokensPaginatorName",
+    "ListDevEnvironmentSessionsPaginatorName",
     "ListDevEnvironmentsPaginatorName",
     "ListEventLogsPaginatorName",
     "ListProjectsPaginatorName",
     "ListSourceRepositoriesPaginatorName",
     "ListSourceRepositoryBranchesPaginatorName",
     "ListSpacesPaginatorName",
     "OperationTypeType",
@@ -47,14 +48,15 @@
     "DELETED", "DELETING", "FAILED", "PENDING", "RUNNING", "STARTING", "STOPPED", "STOPPING"
 ]
 FilterKeyType = Literal["hasAccessTo"]
 InstanceTypeType = Literal[
     "dev.standard1.large", "dev.standard1.medium", "dev.standard1.small", "dev.standard1.xlarge"
 ]
 ListAccessTokensPaginatorName = Literal["list_access_tokens"]
+ListDevEnvironmentSessionsPaginatorName = Literal["list_dev_environment_sessions"]
 ListDevEnvironmentsPaginatorName = Literal["list_dev_environments"]
 ListEventLogsPaginatorName = Literal["list_event_logs"]
 ListProjectsPaginatorName = Literal["list_projects"]
 ListSourceRepositoriesPaginatorName = Literal["list_source_repositories"]
 ListSourceRepositoryBranchesPaginatorName = Literal["list_source_repository_branches"]
 ListSpacesPaginatorName = Literal["list_spaces"]
 OperationTypeType = Literal["MUTATION", "READONLY"]
@@ -118,14 +120,15 @@
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
@@ -204,14 +207,15 @@
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
@@ -222,14 +226,15 @@
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
@@ -265,14 +270,15 @@
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
@@ -291,16 +297,19 @@
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
@@ -384,15 +393,17 @@
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
@@ -412,14 +423,15 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_access_tokens",
+    "list_dev_environment_sessions",
     "list_dev_environments",
     "list_event_logs",
     "list_projects",
     "list_source_repositories",
     "list_source_repository_branches",
     "list_spaces",
 ]
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/literals.pyi` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/literals.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -21,14 +21,15 @@
 __all__ = (
     "ComparisonOperatorType",
     "DevEnvironmentSessionTypeType",
     "DevEnvironmentStatusType",
     "FilterKeyType",
     "InstanceTypeType",
     "ListAccessTokensPaginatorName",
+    "ListDevEnvironmentSessionsPaginatorName",
     "ListDevEnvironmentsPaginatorName",
     "ListEventLogsPaginatorName",
     "ListProjectsPaginatorName",
     "ListSourceRepositoriesPaginatorName",
     "ListSourceRepositoryBranchesPaginatorName",
     "ListSpacesPaginatorName",
     "OperationTypeType",
@@ -45,14 +46,15 @@
     "DELETED", "DELETING", "FAILED", "PENDING", "RUNNING", "STARTING", "STOPPED", "STOPPING"
 ]
 FilterKeyType = Literal["hasAccessTo"]
 InstanceTypeType = Literal[
     "dev.standard1.large", "dev.standard1.medium", "dev.standard1.small", "dev.standard1.xlarge"
 ]
 ListAccessTokensPaginatorName = Literal["list_access_tokens"]
+ListDevEnvironmentSessionsPaginatorName = Literal["list_dev_environment_sessions"]
 ListDevEnvironmentsPaginatorName = Literal["list_dev_environments"]
 ListEventLogsPaginatorName = Literal["list_event_logs"]
 ListProjectsPaginatorName = Literal["list_projects"]
 ListSourceRepositoriesPaginatorName = Literal["list_source_repositories"]
 ListSourceRepositoryBranchesPaginatorName = Literal["list_source_repository_branches"]
 ListSpacesPaginatorName = Literal["list_spaces"]
 OperationTypeType = Literal["MUTATION", "READONLY"]
@@ -116,14 +118,15 @@
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
@@ -202,14 +205,15 @@
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
@@ -220,14 +224,15 @@
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
@@ -263,14 +268,15 @@
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
@@ -289,16 +295,19 @@
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
@@ -382,15 +391,17 @@
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
@@ -410,14 +421,15 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "list_access_tokens",
+    "list_dev_environment_sessions",
     "list_dev_environments",
     "list_event_logs",
     "list_projects",
     "list_source_repositories",
     "list_source_repository_branches",
     "list_spaces",
 ]
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/paginator.py` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -7,198 +7,205 @@
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_codecatalyst.client import CodeCatalystClient
     from types_aiobotocore_codecatalyst.paginator import (
         ListAccessTokensPaginator,
+        ListDevEnvironmentSessionsPaginator,
         ListDevEnvironmentsPaginator,
         ListEventLogsPaginator,
         ListProjectsPaginator,
         ListSourceRepositoriesPaginator,
         ListSourceRepositoryBranchesPaginator,
         ListSpacesPaginator,
     )
 
     session = get_session()
     with session.create_client("codecatalyst") as client:
         client: CodeCatalystClient
 
         list_access_tokens_paginator: ListAccessTokensPaginator = client.get_paginator("list_access_tokens")
+        list_dev_environment_sessions_paginator: ListDevEnvironmentSessionsPaginator = client.get_paginator("list_dev_environment_sessions")
         list_dev_environments_paginator: ListDevEnvironmentsPaginator = client.get_paginator("list_dev_environments")
         list_event_logs_paginator: ListEventLogsPaginator = client.get_paginator("list_event_logs")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
         list_source_repositories_paginator: ListSourceRepositoriesPaginator = client.get_paginator("list_source_repositories")
         list_source_repository_branches_paginator: ListSourceRepositoryBranchesPaginator = client.get_paginator("list_source_repository_branches")
         list_spaces_paginator: ListSpacesPaginator = client.get_paginator("list_spaces")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListAccessTokensResponseTypeDef,
+    ListDevEnvironmentSessionsResponseTypeDef,
     ListDevEnvironmentsResponseTypeDef,
     ListEventLogsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListSourceRepositoriesResponseTypeDef,
     ListSourceRepositoryBranchesResponseTypeDef,
     ListSpacesResponseTypeDef,
     PaginatorConfigTypeDef,
     ProjectListFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAccessTokensPaginator",
+    "ListDevEnvironmentSessionsPaginator",
     "ListDevEnvironmentsPaginator",
     "ListEventLogsPaginator",
     "ListProjectsPaginator",
     "ListSourceRepositoriesPaginator",
     "ListSourceRepositoryBranchesPaginator",
     "ListSpacesPaginator",
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
 class ListAccessTokensPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListAccessTokens)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listaccesstokenspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessTokensResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListAccessTokens.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listaccesstokenspaginator)
         """
 
+class ListDevEnvironmentSessionsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironmentSessions)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentsessionspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        spaceName: str,
+        projectName: str,
+        devEnvironmentId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListDevEnvironmentSessionsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironmentSessions.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentsessionspaginator)
+        """
 
 class ListDevEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentspaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         projectName: str,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentspaginator)
         """
 
-
 class ListEventLogsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListEventLogs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listeventlogspaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         eventName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventLogsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListEventLogs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listeventlogspaginator)
         """
 
-
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listprojectspaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         filters: Sequence[ProjectListFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listprojectspaginator)
         """
 
-
 class ListSourceRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositoriespaginator)
     """
 
     def paginate(
-        self, *, spaceName: str, projectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, spaceName: str, projectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceRepositoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositoriespaginator)
         """
 
-
 class ListSourceRepositoryBranchesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositoryBranches)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositorybranchespaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         projectName: str,
         sourceRepositoryName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceRepositoryBranchesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositoryBranches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositorybranchespaginator)
         """
 
-
 class ListSpacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSpaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listspacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSpaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listspacespaginator)
         """
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/paginator.pyi` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -7,188 +7,215 @@
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_codecatalyst.client import CodeCatalystClient
     from types_aiobotocore_codecatalyst.paginator import (
         ListAccessTokensPaginator,
+        ListDevEnvironmentSessionsPaginator,
         ListDevEnvironmentsPaginator,
         ListEventLogsPaginator,
         ListProjectsPaginator,
         ListSourceRepositoriesPaginator,
         ListSourceRepositoryBranchesPaginator,
         ListSpacesPaginator,
     )
 
     session = get_session()
     with session.create_client("codecatalyst") as client:
         client: CodeCatalystClient
 
         list_access_tokens_paginator: ListAccessTokensPaginator = client.get_paginator("list_access_tokens")
+        list_dev_environment_sessions_paginator: ListDevEnvironmentSessionsPaginator = client.get_paginator("list_dev_environment_sessions")
         list_dev_environments_paginator: ListDevEnvironmentsPaginator = client.get_paginator("list_dev_environments")
         list_event_logs_paginator: ListEventLogsPaginator = client.get_paginator("list_event_logs")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
         list_source_repositories_paginator: ListSourceRepositoriesPaginator = client.get_paginator("list_source_repositories")
         list_source_repository_branches_paginator: ListSourceRepositoryBranchesPaginator = client.get_paginator("list_source_repository_branches")
         list_spaces_paginator: ListSpacesPaginator = client.get_paginator("list_spaces")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     FilterTypeDef,
     ListAccessTokensResponseTypeDef,
+    ListDevEnvironmentSessionsResponseTypeDef,
     ListDevEnvironmentsResponseTypeDef,
     ListEventLogsResponseTypeDef,
     ListProjectsResponseTypeDef,
     ListSourceRepositoriesResponseTypeDef,
     ListSourceRepositoryBranchesResponseTypeDef,
     ListSpacesResponseTypeDef,
     PaginatorConfigTypeDef,
     ProjectListFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAccessTokensPaginator",
+    "ListDevEnvironmentSessionsPaginator",
     "ListDevEnvironmentsPaginator",
     "ListEventLogsPaginator",
     "ListProjectsPaginator",
     "ListSourceRepositoriesPaginator",
     "ListSourceRepositoryBranchesPaginator",
     "ListSpacesPaginator",
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
 class ListAccessTokensPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListAccessTokens)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listaccesstokenspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccessTokensResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListAccessTokens.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listaccesstokenspaginator)
         """
 
+
+class ListDevEnvironmentSessionsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironmentSessions)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentsessionspaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        spaceName: str,
+        projectName: str,
+        devEnvironmentId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListDevEnvironmentSessionsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironmentSessions.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentsessionspaginator)
+        """
+
+
 class ListDevEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentspaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         projectName: str,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevEnvironmentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListDevEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listdevenvironmentspaginator)
         """
 
+
 class ListEventLogsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListEventLogs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listeventlogspaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         startTime: Union[datetime, str],
         endTime: Union[datetime, str],
         eventName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventLogsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListEventLogs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listeventlogspaginator)
         """
 
+
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listprojectspaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         filters: Sequence[ProjectListFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listprojectspaginator)
         """
 
+
 class ListSourceRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositoriespaginator)
     """
 
     def paginate(
-        self, *, spaceName: str, projectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, spaceName: str, projectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceRepositoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositoriespaginator)
         """
 
+
 class ListSourceRepositoryBranchesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositoryBranches)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositorybranchespaginator)
     """
 
     def paginate(
         self,
         *,
         spaceName: str,
         projectName: str,
         sourceRepositoryName: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSourceRepositoryBranchesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSourceRepositoryBranches.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listsourcerepositorybranchespaginator)
         """
 
+
 class ListSpacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSpaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listspacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSpacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst.Paginator.ListSpaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/paginators/#listspacespaginator)
         """
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/type_defs.py` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -29,84 +29,89 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AccessTokenSummaryTypeDef",
     "CreateAccessTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAccessTokenResponseTypeDef",
     "IdeConfigurationTypeDef",
     "PersistentStorageConfigurationTypeDef",
     "RepositoryInputTypeDef",
+    "CreateDevEnvironmentResponseTypeDef",
     "CreateProjectRequestRequestTypeDef",
+    "CreateProjectResponseTypeDef",
     "CreateSourceRepositoryBranchRequestRequestTypeDef",
+    "CreateSourceRepositoryBranchResponseTypeDef",
     "DeleteAccessTokenRequestRequestTypeDef",
     "DeleteDevEnvironmentRequestRequestTypeDef",
+    "DeleteDevEnvironmentResponseTypeDef",
     "DevEnvironmentAccessDetailsTypeDef",
     "DevEnvironmentRepositorySummaryTypeDef",
     "ExecuteCommandSessionConfigurationTypeDef",
+    "DevEnvironmentSessionSummaryTypeDef",
     "IdeTypeDef",
     "PersistentStorageTypeDef",
     "EmailAddressTypeDef",
     "EventPayloadTypeDef",
     "ProjectInformationTypeDef",
     "UserIdentityTypeDef",
     "FilterTypeDef",
     "GetDevEnvironmentRequestRequestTypeDef",
     "GetProjectRequestRequestTypeDef",
+    "GetProjectResponseTypeDef",
     "GetSourceRepositoryCloneUrlsRequestRequestTypeDef",
+    "GetSourceRepositoryCloneUrlsResponseTypeDef",
     "GetSpaceRequestRequestTypeDef",
+    "GetSpaceResponseTypeDef",
     "GetSubscriptionRequestRequestTypeDef",
+    "GetSubscriptionResponseTypeDef",
     "GetUserDetailsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
     "ListAccessTokensRequestRequestTypeDef",
+    "ListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef",
+    "ListDevEnvironmentSessionsRequestRequestTypeDef",
+    "ListEventLogsRequestListEventLogsPaginateTypeDef",
     "ListEventLogsRequestRequestTypeDef",
     "ProjectListFilterTypeDef",
     "ProjectSummaryTypeDef",
     "ListSourceRepositoriesItemTypeDef",
+    "ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
     "ListSourceRepositoriesRequestRequestTypeDef",
     "ListSourceRepositoryBranchesItemTypeDef",
+    "ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
     "ListSourceRepositoryBranchesRequestRequestTypeDef",
+    "ListSpacesRequestListSpacesPaginateTypeDef",
     "ListSpacesRequestRequestTypeDef",
     "SpaceSummaryTypeDef",
-    "StopDevEnvironmentRequestRequestTypeDef",
-    "CreateAccessTokenResponseTypeDef",
-    "CreateDevEnvironmentResponseTypeDef",
-    "CreateProjectResponseTypeDef",
-    "CreateSourceRepositoryBranchResponseTypeDef",
-    "DeleteDevEnvironmentResponseTypeDef",
-    "GetProjectResponseTypeDef",
-    "GetSourceRepositoryCloneUrlsResponseTypeDef",
-    "GetSpaceResponseTypeDef",
-    "GetSubscriptionResponseTypeDef",
-    "ListAccessTokensResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDevEnvironmentResponseTypeDef",
+    "StopDevEnvironmentRequestRequestTypeDef",
     "StopDevEnvironmentResponseTypeDef",
+    "StopDevEnvironmentSessionRequestRequestTypeDef",
+    "StopDevEnvironmentSessionResponseTypeDef",
     "VerifySessionResponseTypeDef",
+    "ListAccessTokensResponseTypeDef",
     "StartDevEnvironmentRequestRequestTypeDef",
     "UpdateDevEnvironmentRequestRequestTypeDef",
     "UpdateDevEnvironmentResponseTypeDef",
     "CreateDevEnvironmentRequestRequestTypeDef",
     "StartDevEnvironmentSessionResponseTypeDef",
     "DevEnvironmentSessionConfigurationTypeDef",
+    "ListDevEnvironmentSessionsResponseTypeDef",
     "DevEnvironmentSummaryTypeDef",
     "GetDevEnvironmentResponseTypeDef",
     "GetUserDetailsResponseTypeDef",
     "EventLogEntryTypeDef",
-    "ListDevEnvironmentsRequestRequestTypeDef",
-    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
     "ListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef",
-    "ListEventLogsRequestListEventLogsPaginateTypeDef",
-    "ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
-    "ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
-    "ListSpacesRequestListSpacesPaginateTypeDef",
+    "ListDevEnvironmentsRequestRequestTypeDef",
     "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ListProjectsResponseTypeDef",
     "ListSourceRepositoriesResponseTypeDef",
     "ListSourceRepositoryBranchesResponseTypeDef",
     "ListSpacesResponseTypeDef",
     "StartDevEnvironmentSessionRequestRequestTypeDef",
@@ -125,50 +130,46 @@
     "_OptionalAccessTokenSummaryTypeDef",
     {
         "expiresTime": datetime,
     },
     total=False,
 )
 
-
 class AccessTokenSummaryTypeDef(
     _RequiredAccessTokenSummaryTypeDef, _OptionalAccessTokenSummaryTypeDef
 ):
     pass
 
-
 _RequiredCreateAccessTokenRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAccessTokenRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateAccessTokenRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAccessTokenRequestRequestTypeDef",
     {
         "expiresTime": Union[datetime, str],
     },
     total=False,
 )
 
-
 class CreateAccessTokenRequestRequestTypeDef(
     _RequiredCreateAccessTokenRequestRequestTypeDef, _OptionalCreateAccessTokenRequestRequestTypeDef
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAccessTokenResponseTypeDef = TypedDict(
+    "CreateAccessTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "secret": str,
+        "name": str,
+        "expiresTime": datetime,
+        "accessTokenId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IdeConfigurationTypeDef = TypedDict(
     "IdeConfigurationTypeDef",
     {
         "runtime": str,
@@ -194,18 +195,26 @@
     "_OptionalRepositoryInputTypeDef",
     {
         "branchName": str,
     },
     total=False,
 )
 
-
 class RepositoryInputTypeDef(_RequiredRepositoryInputTypeDef, _OptionalRepositoryInputTypeDef):
     pass
 
+CreateDevEnvironmentResponseTypeDef = TypedDict(
+    "CreateDevEnvironmentResponseTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProjectRequestRequestTypeDef",
     {
         "spaceName": str,
         "displayName": str,
     },
@@ -214,20 +223,29 @@
     "_OptionalCreateProjectRequestRequestTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
-
 class CreateProjectRequestRequestTypeDef(
     _RequiredCreateProjectRequestRequestTypeDef, _OptionalCreateProjectRequestRequestTypeDef
 ):
     pass
 
+CreateProjectResponseTypeDef = TypedDict(
+    "CreateProjectResponseTypeDef",
+    {
+        "spaceName": str,
+        "name": str,
+        "displayName": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateSourceRepositoryBranchRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSourceRepositoryBranchRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "sourceRepositoryName": str,
@@ -238,21 +256,30 @@
     "_OptionalCreateSourceRepositoryBranchRequestRequestTypeDef",
     {
         "headCommitId": str,
     },
     total=False,
 )
 
-
 class CreateSourceRepositoryBranchRequestRequestTypeDef(
     _RequiredCreateSourceRepositoryBranchRequestRequestTypeDef,
     _OptionalCreateSourceRepositoryBranchRequestRequestTypeDef,
 ):
     pass
 
+CreateSourceRepositoryBranchResponseTypeDef = TypedDict(
+    "CreateSourceRepositoryBranchResponseTypeDef",
+    {
+        "ref": str,
+        "name": str,
+        "lastUpdatedTime": datetime,
+        "headCommitId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteAccessTokenRequestRequestTypeDef = TypedDict(
     "DeleteAccessTokenRequestRequestTypeDef",
     {
         "id": str,
     },
 )
@@ -262,14 +289,24 @@
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
     },
 )
 
+DeleteDevEnvironmentResponseTypeDef = TypedDict(
+    "DeleteDevEnvironmentResponseTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DevEnvironmentAccessDetailsTypeDef = TypedDict(
     "DevEnvironmentAccessDetailsTypeDef",
     {
         "streamUrl": str,
         "tokenValue": str,
     },
 )
@@ -284,42 +321,49 @@
     "_OptionalDevEnvironmentRepositorySummaryTypeDef",
     {
         "branchName": str,
     },
     total=False,
 )
 
-
 class DevEnvironmentRepositorySummaryTypeDef(
     _RequiredDevEnvironmentRepositorySummaryTypeDef, _OptionalDevEnvironmentRepositorySummaryTypeDef
 ):
     pass
 
-
 _RequiredExecuteCommandSessionConfigurationTypeDef = TypedDict(
     "_RequiredExecuteCommandSessionConfigurationTypeDef",
     {
         "command": str,
     },
 )
 _OptionalExecuteCommandSessionConfigurationTypeDef = TypedDict(
     "_OptionalExecuteCommandSessionConfigurationTypeDef",
     {
         "arguments": Sequence[str],
     },
     total=False,
 )
 
-
 class ExecuteCommandSessionConfigurationTypeDef(
     _RequiredExecuteCommandSessionConfigurationTypeDef,
     _OptionalExecuteCommandSessionConfigurationTypeDef,
 ):
     pass
 
+DevEnvironmentSessionSummaryTypeDef = TypedDict(
+    "DevEnvironmentSessionSummaryTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "devEnvironmentId": str,
+        "startedTime": datetime,
+        "id": str,
+    },
+)
 
 IdeTypeDef = TypedDict(
     "IdeTypeDef",
     {
         "runtime": str,
         "name": str,
     },
@@ -372,19 +416,17 @@
     {
         "userName": str,
         "awsAccountId": str,
     },
     total=False,
 )
 
-
 class UserIdentityTypeDef(_RequiredUserIdentityTypeDef, _OptionalUserIdentityTypeDef):
     pass
 
-
 _RequiredFilterTypeDef = TypedDict(
     "_RequiredFilterTypeDef",
     {
         "key": str,
         "values": Sequence[str],
     },
 )
@@ -392,19 +434,17 @@
     "_OptionalFilterTypeDef",
     {
         "comparisonOperator": str,
     },
     total=False,
 )
 
-
 class FilterTypeDef(_RequiredFilterTypeDef, _OptionalFilterTypeDef):
     pass
 
-
 GetDevEnvironmentRequestRequestTypeDef = TypedDict(
     "GetDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
     },
@@ -414,65 +454,170 @@
     "GetProjectRequestRequestTypeDef",
     {
         "spaceName": str,
         "name": str,
     },
 )
 
+GetProjectResponseTypeDef = TypedDict(
+    "GetProjectResponseTypeDef",
+    {
+        "spaceName": str,
+        "name": str,
+        "displayName": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSourceRepositoryCloneUrlsRequestRequestTypeDef = TypedDict(
     "GetSourceRepositoryCloneUrlsRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "sourceRepositoryName": str,
     },
 )
 
+GetSourceRepositoryCloneUrlsResponseTypeDef = TypedDict(
+    "GetSourceRepositoryCloneUrlsResponseTypeDef",
+    {
+        "https": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSpaceRequestRequestTypeDef = TypedDict(
     "GetSpaceRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+GetSpaceResponseTypeDef = TypedDict(
+    "GetSpaceResponseTypeDef",
+    {
+        "name": str,
+        "regionName": str,
+        "displayName": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSubscriptionRequestRequestTypeDef = TypedDict(
     "GetSubscriptionRequestRequestTypeDef",
     {
         "spaceName": str,
     },
 )
 
+GetSubscriptionResponseTypeDef = TypedDict(
+    "GetSubscriptionResponseTypeDef",
+    {
+        "subscriptionType": str,
+        "awsAccountName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetUserDetailsRequestRequestTypeDef = TypedDict(
     "GetUserDetailsRequestRequestTypeDef",
     {
         "id": str,
         "userName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccessTokensRequestListAccessTokensPaginateTypeDef = TypedDict(
+    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccessTokensRequestRequestTypeDef = TypedDict(
     "ListAccessTokensRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef = TypedDict(
+    "_RequiredListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "devEnvironmentId": str,
+    },
+)
+_OptionalListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef = TypedDict(
+    "_OptionalListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef(
+    _RequiredListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef,
+    _OptionalListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef,
+):
+    pass
+
+_RequiredListDevEnvironmentSessionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListDevEnvironmentSessionsRequestRequestTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "devEnvironmentId": str,
+    },
+)
+_OptionalListDevEnvironmentSessionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListDevEnvironmentSessionsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+class ListDevEnvironmentSessionsRequestRequestTypeDef(
+    _RequiredListDevEnvironmentSessionsRequestRequestTypeDef,
+    _OptionalListDevEnvironmentSessionsRequestRequestTypeDef,
+):
+    pass
+
+_RequiredListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
+    "_RequiredListEventLogsRequestListEventLogsPaginateTypeDef",
+    {
+        "spaceName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
+    "_OptionalListEventLogsRequestListEventLogsPaginateTypeDef",
+    {
+        "eventName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEventLogsRequestListEventLogsPaginateTypeDef(
+    _RequiredListEventLogsRequestListEventLogsPaginateTypeDef,
+    _OptionalListEventLogsRequestListEventLogsPaginateTypeDef,
+):
+    pass
+
 _RequiredListEventLogsRequestRequestTypeDef = TypedDict(
     "_RequiredListEventLogsRequestRequestTypeDef",
     {
         "spaceName": str,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
@@ -483,21 +628,19 @@
         "eventName": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class ListEventLogsRequestRequestTypeDef(
     _RequiredListEventLogsRequestRequestTypeDef, _OptionalListEventLogsRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredProjectListFilterTypeDef = TypedDict(
     "_RequiredProjectListFilterTypeDef",
     {
         "key": Literal["hasAccessTo"],
         "values": Sequence[str],
     },
 )
@@ -505,21 +648,19 @@
     "_OptionalProjectListFilterTypeDef",
     {
         "comparisonOperator": ComparisonOperatorType,
     },
     total=False,
 )
 
-
 class ProjectListFilterTypeDef(
     _RequiredProjectListFilterTypeDef, _OptionalProjectListFilterTypeDef
 ):
     pass
 
-
 _RequiredProjectSummaryTypeDef = TypedDict(
     "_RequiredProjectSummaryTypeDef",
     {
         "name": str,
     },
 )
 _OptionalProjectSummaryTypeDef = TypedDict(
@@ -527,19 +668,17 @@
     {
         "displayName": str,
         "description": str,
     },
     total=False,
 )
 
-
 class ProjectSummaryTypeDef(_RequiredProjectSummaryTypeDef, _OptionalProjectSummaryTypeDef):
     pass
 
-
 _RequiredListSourceRepositoriesItemTypeDef = TypedDict(
     "_RequiredListSourceRepositoriesItemTypeDef",
     {
         "id": str,
         "name": str,
         "lastUpdatedTime": datetime,
         "createdTime": datetime,
@@ -549,20 +688,39 @@
     "_OptionalListSourceRepositoriesItemTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
-
 class ListSourceRepositoriesItemTypeDef(
     _RequiredListSourceRepositoriesItemTypeDef, _OptionalListSourceRepositoriesItemTypeDef
 ):
     pass
 
+_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
+    "_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+    },
+)
+_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
+    "_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef(
+    _RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
+    _OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
+):
+    pass
 
 _RequiredListSourceRepositoriesRequestRequestTypeDef = TypedDict(
     "_RequiredListSourceRepositoriesRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
     },
@@ -572,33 +730,53 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class ListSourceRepositoriesRequestRequestTypeDef(
     _RequiredListSourceRepositoriesRequestRequestTypeDef,
     _OptionalListSourceRepositoriesRequestRequestTypeDef,
 ):
     pass
 
-
 ListSourceRepositoryBranchesItemTypeDef = TypedDict(
     "ListSourceRepositoryBranchesItemTypeDef",
     {
         "ref": str,
         "name": str,
         "lastUpdatedTime": datetime,
         "headCommitId": str,
     },
     total=False,
 )
 
+_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
+    "_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "sourceRepositoryName": str,
+    },
+)
+_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
+    "_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef(
+    _RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
+    _OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
+):
+    pass
+
 _RequiredListSourceRepositoryBranchesRequestRequestTypeDef = TypedDict(
     "_RequiredListSourceRepositoryBranchesRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "sourceRepositoryName": str,
     },
@@ -608,21 +786,27 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class ListSourceRepositoryBranchesRequestRequestTypeDef(
     _RequiredListSourceRepositoryBranchesRequestRequestTypeDef,
     _OptionalListSourceRepositoryBranchesRequestRequestTypeDef,
 ):
     pass
 
+ListSpacesRequestListSpacesPaginateTypeDef = TypedDict(
+    "ListSpacesRequestListSpacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListSpacesRequestRequestTypeDef = TypedDict(
     "ListSpacesRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
@@ -640,155 +824,104 @@
     {
         "displayName": str,
         "description": str,
     },
     total=False,
 )
 
-
 class SpaceSummaryTypeDef(_RequiredSpaceSummaryTypeDef, _OptionalSpaceSummaryTypeDef):
     pass
 
-
-StopDevEnvironmentRequestRequestTypeDef = TypedDict(
-    "StopDevEnvironmentRequestRequestTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "spaceName": str,
-        "projectName": str,
-        "id": str,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-CreateAccessTokenResponseTypeDef = TypedDict(
-    "CreateAccessTokenResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "secret": str,
-        "name": str,
-        "expiresTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-CreateDevEnvironmentResponseTypeDef = TypedDict(
-    "CreateDevEnvironmentResponseTypeDef",
+StartDevEnvironmentResponseTypeDef = TypedDict(
+    "StartDevEnvironmentResponseTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProjectResponseTypeDef = TypedDict(
-    "CreateProjectResponseTypeDef",
-    {
-        "spaceName": str,
-        "name": str,
-        "displayName": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSourceRepositoryBranchResponseTypeDef = TypedDict(
-    "CreateSourceRepositoryBranchResponseTypeDef",
-    {
-        "ref": str,
-        "name": str,
-        "lastUpdatedTime": datetime,
-        "headCommitId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "status": DevEnvironmentStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteDevEnvironmentResponseTypeDef = TypedDict(
-    "DeleteDevEnvironmentResponseTypeDef",
+StopDevEnvironmentRequestRequestTypeDef = TypedDict(
+    "StopDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-GetProjectResponseTypeDef = TypedDict(
-    "GetProjectResponseTypeDef",
+StopDevEnvironmentResponseTypeDef = TypedDict(
+    "StopDevEnvironmentResponseTypeDef",
     {
         "spaceName": str,
-        "name": str,
-        "displayName": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSourceRepositoryCloneUrlsResponseTypeDef = TypedDict(
-    "GetSourceRepositoryCloneUrlsResponseTypeDef",
-    {
-        "https": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSpaceResponseTypeDef = TypedDict(
-    "GetSpaceResponseTypeDef",
-    {
-        "name": str,
-        "regionName": str,
-        "displayName": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSubscriptionResponseTypeDef = TypedDict(
-    "GetSubscriptionResponseTypeDef",
-    {
-        "subscriptionType": str,
-        "awsAccountName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccessTokensResponseTypeDef = TypedDict(
-    "ListAccessTokensResponseTypeDef",
-    {
-        "items": List[AccessTokenSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "projectName": str,
+        "id": str,
+        "status": DevEnvironmentStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartDevEnvironmentResponseTypeDef = TypedDict(
-    "StartDevEnvironmentResponseTypeDef",
+StopDevEnvironmentSessionRequestRequestTypeDef = TypedDict(
+    "StopDevEnvironmentSessionRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "status": DevEnvironmentStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sessionId": str,
     },
 )
 
-StopDevEnvironmentResponseTypeDef = TypedDict(
-    "StopDevEnvironmentResponseTypeDef",
+StopDevEnvironmentSessionResponseTypeDef = TypedDict(
+    "StopDevEnvironmentSessionResponseTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "status": DevEnvironmentStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VerifySessionResponseTypeDef = TypedDict(
     "VerifySessionResponseTypeDef",
     {
         "identity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAccessTokensResponseTypeDef = TypedDict(
+    "ListAccessTokensResponseTypeDef",
+    {
+        "items": List[AccessTokenSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartDevEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredStartDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
@@ -802,22 +935,20 @@
         "ides": Sequence[IdeConfigurationTypeDef],
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
     },
     total=False,
 )
 
-
 class StartDevEnvironmentRequestRequestTypeDef(
     _RequiredStartDevEnvironmentRequestRequestTypeDef,
     _OptionalStartDevEnvironmentRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateDevEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
     },
@@ -830,34 +961,32 @@
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
         "clientToken": str,
     },
     total=False,
 )
 
-
 class UpdateDevEnvironmentRequestRequestTypeDef(
     _RequiredUpdateDevEnvironmentRequestRequestTypeDef,
     _OptionalUpdateDevEnvironmentRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateDevEnvironmentResponseTypeDef = TypedDict(
     "UpdateDevEnvironmentResponseTypeDef",
     {
         "id": str,
         "spaceName": str,
         "projectName": str,
         "alias": str,
         "ides": List[IdeConfigurationTypeDef],
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDevEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
@@ -874,31 +1003,29 @@
         "alias": str,
         "ides": Sequence[IdeConfigurationTypeDef],
         "inactivityTimeoutMinutes": int,
     },
     total=False,
 )
 
-
 class CreateDevEnvironmentRequestRequestTypeDef(
     _RequiredCreateDevEnvironmentRequestRequestTypeDef,
     _OptionalCreateDevEnvironmentRequestRequestTypeDef,
 ):
     pass
 
-
 StartDevEnvironmentSessionResponseTypeDef = TypedDict(
     "StartDevEnvironmentSessionResponseTypeDef",
     {
         "accessDetails": DevEnvironmentAccessDetailsTypeDef,
         "sessionId": str,
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDevEnvironmentSessionConfigurationTypeDef = TypedDict(
     "_RequiredDevEnvironmentSessionConfigurationTypeDef",
     {
         "sessionType": DevEnvironmentSessionTypeType,
@@ -908,21 +1035,28 @@
     "_OptionalDevEnvironmentSessionConfigurationTypeDef",
     {
         "executeCommandSessionConfiguration": ExecuteCommandSessionConfigurationTypeDef,
     },
     total=False,
 )
 
-
 class DevEnvironmentSessionConfigurationTypeDef(
     _RequiredDevEnvironmentSessionConfigurationTypeDef,
     _OptionalDevEnvironmentSessionConfigurationTypeDef,
 ):
     pass
 
+ListDevEnvironmentSessionsResponseTypeDef = TypedDict(
+    "ListDevEnvironmentSessionsResponseTypeDef",
+    {
+        "items": List[DevEnvironmentSessionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredDevEnvironmentSummaryTypeDef = TypedDict(
     "_RequiredDevEnvironmentSummaryTypeDef",
     {
         "id": str,
         "lastUpdatedTime": datetime,
         "creatorId": str,
@@ -941,21 +1075,19 @@
         "statusReason": str,
         "alias": str,
         "ides": List[IdeTypeDef],
     },
     total=False,
 )
 
-
 class DevEnvironmentSummaryTypeDef(
     _RequiredDevEnvironmentSummaryTypeDef, _OptionalDevEnvironmentSummaryTypeDef
 ):
     pass
 
-
 GetDevEnvironmentResponseTypeDef = TypedDict(
     "GetDevEnvironmentResponseTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
         "lastUpdatedTime": datetime,
@@ -964,27 +1096,27 @@
         "statusReason": str,
         "repositories": List[DevEnvironmentRepositorySummaryTypeDef],
         "alias": str,
         "ides": List[IdeTypeDef],
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
         "persistentStorage": PersistentStorageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserDetailsResponseTypeDef = TypedDict(
     "GetUserDetailsResponseTypeDef",
     {
         "userId": str,
         "userName": str,
         "displayName": str,
         "primaryEmail": EmailAddressTypeDef,
         "version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEventLogEntryTypeDef = TypedDict(
     "_RequiredEventLogEntryTypeDef",
     {
         "id": str,
@@ -1007,179 +1139,83 @@
         "errorCode": str,
         "sourceIpAddress": str,
         "userAgent": str,
     },
     total=False,
 )
 
-
 class EventLogEntryTypeDef(_RequiredEventLogEntryTypeDef, _OptionalEventLogEntryTypeDef):
     pass
 
-
-_RequiredListDevEnvironmentsRequestRequestTypeDef = TypedDict(
-    "_RequiredListDevEnvironmentsRequestRequestTypeDef",
-    {
-        "spaceName": str,
-        "projectName": str,
-    },
-)
-_OptionalListDevEnvironmentsRequestRequestTypeDef = TypedDict(
-    "_OptionalListDevEnvironmentsRequestRequestTypeDef",
-    {
-        "filters": Sequence[FilterTypeDef],
-        "nextToken": str,
-        "maxResults": int,
-    },
-    total=False,
-)
-
-
-class ListDevEnvironmentsRequestRequestTypeDef(
-    _RequiredListDevEnvironmentsRequestRequestTypeDef,
-    _OptionalListDevEnvironmentsRequestRequestTypeDef,
-):
-    pass
-
-
-ListAccessTokensRequestListAccessTokensPaginateTypeDef = TypedDict(
-    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef = TypedDict(
     "_RequiredListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef",
     {
         "spaceName": str,
         "projectName": str,
     },
 )
 _OptionalListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef = TypedDict(
     "_OptionalListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef(
     _RequiredListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef,
     _OptionalListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef,
 ):
     pass
 
-
-_RequiredListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
-    "_RequiredListEventLogsRequestListEventLogsPaginateTypeDef",
-    {
-        "spaceName": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
-    "_OptionalListEventLogsRequestListEventLogsPaginateTypeDef",
-    {
-        "eventName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEventLogsRequestListEventLogsPaginateTypeDef(
-    _RequiredListEventLogsRequestListEventLogsPaginateTypeDef,
-    _OptionalListEventLogsRequestListEventLogsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
-    "_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
-    {
-        "spaceName": str,
-        "projectName": str,
-    },
-)
-_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
-    "_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef(
-    _RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
-    _OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
-    "_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
+_RequiredListDevEnvironmentsRequestRequestTypeDef = TypedDict(
+    "_RequiredListDevEnvironmentsRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
-        "sourceRepositoryName": str,
     },
 )
-_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
-    "_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
+_OptionalListDevEnvironmentsRequestRequestTypeDef = TypedDict(
+    "_OptionalListDevEnvironmentsRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filters": Sequence[FilterTypeDef],
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-
-class ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef(
-    _RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
-    _OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
+class ListDevEnvironmentsRequestRequestTypeDef(
+    _RequiredListDevEnvironmentsRequestRequestTypeDef,
+    _OptionalListDevEnvironmentsRequestRequestTypeDef,
 ):
     pass
 
-
-ListSpacesRequestListSpacesPaginateTypeDef = TypedDict(
-    "ListSpacesRequestListSpacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
     "_RequiredListProjectsRequestListProjectsPaginateTypeDef",
     {
         "spaceName": str,
     },
 )
 _OptionalListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
     "_OptionalListProjectsRequestListProjectsPaginateTypeDef",
     {
         "filters": Sequence[ProjectListFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class ListProjectsRequestListProjectsPaginateTypeDef(
     _RequiredListProjectsRequestListProjectsPaginateTypeDef,
     _OptionalListProjectsRequestListProjectsPaginateTypeDef,
 ):
     pass
 
-
 _RequiredListProjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectsRequestRequestTypeDef",
     {
         "spaceName": str,
     },
 )
 _OptionalListProjectsRequestRequestTypeDef = TypedDict(
@@ -1188,54 +1224,52 @@
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[ProjectListFilterTypeDef],
     },
     total=False,
 )
 
-
 class ListProjectsRequestRequestTypeDef(
     _RequiredListProjectsRequestRequestTypeDef, _OptionalListProjectsRequestRequestTypeDef
 ):
     pass
 
-
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "nextToken": str,
         "items": List[ProjectSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSourceRepositoriesResponseTypeDef = TypedDict(
     "ListSourceRepositoriesResponseTypeDef",
     {
         "items": List[ListSourceRepositoriesItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSourceRepositoryBranchesResponseTypeDef = TypedDict(
     "ListSourceRepositoryBranchesResponseTypeDef",
     {
         "nextToken": str,
         "items": List[ListSourceRepositoryBranchesItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSpacesResponseTypeDef = TypedDict(
     "ListSpacesResponseTypeDef",
     {
         "nextToken": str,
         "items": List[SpaceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDevEnvironmentSessionRequestRequestTypeDef = TypedDict(
     "StartDevEnvironmentSessionRequestRequestTypeDef",
     {
         "spaceName": str,
@@ -1246,19 +1280,19 @@
 )
 
 ListDevEnvironmentsResponseTypeDef = TypedDict(
     "ListDevEnvironmentsResponseTypeDef",
     {
         "items": List[DevEnvironmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventLogsResponseTypeDef = TypedDict(
     "ListEventLogsResponseTypeDef",
     {
         "nextToken": str,
         "items": List[EventLogEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst/type_defs.pyi` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst/type_defs.py`

 * *Files 15% similar despite different names*

```diff
@@ -29,83 +29,90 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AccessTokenSummaryTypeDef",
     "CreateAccessTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAccessTokenResponseTypeDef",
     "IdeConfigurationTypeDef",
     "PersistentStorageConfigurationTypeDef",
     "RepositoryInputTypeDef",
+    "CreateDevEnvironmentResponseTypeDef",
     "CreateProjectRequestRequestTypeDef",
+    "CreateProjectResponseTypeDef",
     "CreateSourceRepositoryBranchRequestRequestTypeDef",
+    "CreateSourceRepositoryBranchResponseTypeDef",
     "DeleteAccessTokenRequestRequestTypeDef",
     "DeleteDevEnvironmentRequestRequestTypeDef",
+    "DeleteDevEnvironmentResponseTypeDef",
     "DevEnvironmentAccessDetailsTypeDef",
     "DevEnvironmentRepositorySummaryTypeDef",
     "ExecuteCommandSessionConfigurationTypeDef",
+    "DevEnvironmentSessionSummaryTypeDef",
     "IdeTypeDef",
     "PersistentStorageTypeDef",
     "EmailAddressTypeDef",
     "EventPayloadTypeDef",
     "ProjectInformationTypeDef",
     "UserIdentityTypeDef",
     "FilterTypeDef",
     "GetDevEnvironmentRequestRequestTypeDef",
     "GetProjectRequestRequestTypeDef",
+    "GetProjectResponseTypeDef",
     "GetSourceRepositoryCloneUrlsRequestRequestTypeDef",
+    "GetSourceRepositoryCloneUrlsResponseTypeDef",
     "GetSpaceRequestRequestTypeDef",
+    "GetSpaceResponseTypeDef",
     "GetSubscriptionRequestRequestTypeDef",
+    "GetSubscriptionResponseTypeDef",
     "GetUserDetailsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
     "ListAccessTokensRequestRequestTypeDef",
+    "ListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef",
+    "ListDevEnvironmentSessionsRequestRequestTypeDef",
+    "ListEventLogsRequestListEventLogsPaginateTypeDef",
     "ListEventLogsRequestRequestTypeDef",
     "ProjectListFilterTypeDef",
     "ProjectSummaryTypeDef",
     "ListSourceRepositoriesItemTypeDef",
+    "ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
     "ListSourceRepositoriesRequestRequestTypeDef",
     "ListSourceRepositoryBranchesItemTypeDef",
+    "ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
     "ListSourceRepositoryBranchesRequestRequestTypeDef",
+    "ListSpacesRequestListSpacesPaginateTypeDef",
     "ListSpacesRequestRequestTypeDef",
     "SpaceSummaryTypeDef",
-    "StopDevEnvironmentRequestRequestTypeDef",
-    "CreateAccessTokenResponseTypeDef",
-    "CreateDevEnvironmentResponseTypeDef",
-    "CreateProjectResponseTypeDef",
-    "CreateSourceRepositoryBranchResponseTypeDef",
-    "DeleteDevEnvironmentResponseTypeDef",
-    "GetProjectResponseTypeDef",
-    "GetSourceRepositoryCloneUrlsResponseTypeDef",
-    "GetSpaceResponseTypeDef",
-    "GetSubscriptionResponseTypeDef",
-    "ListAccessTokensResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDevEnvironmentResponseTypeDef",
+    "StopDevEnvironmentRequestRequestTypeDef",
     "StopDevEnvironmentResponseTypeDef",
+    "StopDevEnvironmentSessionRequestRequestTypeDef",
+    "StopDevEnvironmentSessionResponseTypeDef",
     "VerifySessionResponseTypeDef",
+    "ListAccessTokensResponseTypeDef",
     "StartDevEnvironmentRequestRequestTypeDef",
     "UpdateDevEnvironmentRequestRequestTypeDef",
     "UpdateDevEnvironmentResponseTypeDef",
     "CreateDevEnvironmentRequestRequestTypeDef",
     "StartDevEnvironmentSessionResponseTypeDef",
     "DevEnvironmentSessionConfigurationTypeDef",
+    "ListDevEnvironmentSessionsResponseTypeDef",
     "DevEnvironmentSummaryTypeDef",
     "GetDevEnvironmentResponseTypeDef",
     "GetUserDetailsResponseTypeDef",
     "EventLogEntryTypeDef",
-    "ListDevEnvironmentsRequestRequestTypeDef",
-    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
     "ListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef",
-    "ListEventLogsRequestListEventLogsPaginateTypeDef",
-    "ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
-    "ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
-    "ListSpacesRequestListSpacesPaginateTypeDef",
+    "ListDevEnvironmentsRequestRequestTypeDef",
     "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ListProjectsResponseTypeDef",
     "ListSourceRepositoriesResponseTypeDef",
     "ListSourceRepositoryBranchesResponseTypeDef",
     "ListSpacesResponseTypeDef",
     "StartDevEnvironmentSessionRequestRequestTypeDef",
@@ -124,46 +131,50 @@
     "_OptionalAccessTokenSummaryTypeDef",
     {
         "expiresTime": datetime,
     },
     total=False,
 )
 
+
 class AccessTokenSummaryTypeDef(
     _RequiredAccessTokenSummaryTypeDef, _OptionalAccessTokenSummaryTypeDef
 ):
     pass
 
+
 _RequiredCreateAccessTokenRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAccessTokenRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateAccessTokenRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAccessTokenRequestRequestTypeDef",
     {
         "expiresTime": Union[datetime, str],
     },
     total=False,
 )
 
+
 class CreateAccessTokenRequestRequestTypeDef(
     _RequiredCreateAccessTokenRequestRequestTypeDef, _OptionalCreateAccessTokenRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+CreateAccessTokenResponseTypeDef = TypedDict(
+    "CreateAccessTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "secret": str,
+        "name": str,
+        "expiresTime": datetime,
+        "accessTokenId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IdeConfigurationTypeDef = TypedDict(
     "IdeConfigurationTypeDef",
     {
         "runtime": str,
@@ -189,17 +200,29 @@
     "_OptionalRepositoryInputTypeDef",
     {
         "branchName": str,
     },
     total=False,
 )
 
+
 class RepositoryInputTypeDef(_RequiredRepositoryInputTypeDef, _OptionalRepositoryInputTypeDef):
     pass
 
+
+CreateDevEnvironmentResponseTypeDef = TypedDict(
+    "CreateDevEnvironmentResponseTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProjectRequestRequestTypeDef",
     {
         "spaceName": str,
         "displayName": str,
     },
 )
@@ -207,19 +230,32 @@
     "_OptionalCreateProjectRequestRequestTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
+
 class CreateProjectRequestRequestTypeDef(
     _RequiredCreateProjectRequestRequestTypeDef, _OptionalCreateProjectRequestRequestTypeDef
 ):
     pass
 
+
+CreateProjectResponseTypeDef = TypedDict(
+    "CreateProjectResponseTypeDef",
+    {
+        "spaceName": str,
+        "name": str,
+        "displayName": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSourceRepositoryBranchRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSourceRepositoryBranchRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "sourceRepositoryName": str,
         "name": str,
@@ -229,20 +265,33 @@
     "_OptionalCreateSourceRepositoryBranchRequestRequestTypeDef",
     {
         "headCommitId": str,
     },
     total=False,
 )
 
+
 class CreateSourceRepositoryBranchRequestRequestTypeDef(
     _RequiredCreateSourceRepositoryBranchRequestRequestTypeDef,
     _OptionalCreateSourceRepositoryBranchRequestRequestTypeDef,
 ):
     pass
 
+
+CreateSourceRepositoryBranchResponseTypeDef = TypedDict(
+    "CreateSourceRepositoryBranchResponseTypeDef",
+    {
+        "ref": str,
+        "name": str,
+        "lastUpdatedTime": datetime,
+        "headCommitId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAccessTokenRequestRequestTypeDef = TypedDict(
     "DeleteAccessTokenRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -251,14 +300,24 @@
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
     },
 )
 
+DeleteDevEnvironmentResponseTypeDef = TypedDict(
+    "DeleteDevEnvironmentResponseTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DevEnvironmentAccessDetailsTypeDef = TypedDict(
     "DevEnvironmentAccessDetailsTypeDef",
     {
         "streamUrl": str,
         "tokenValue": str,
     },
 )
@@ -273,39 +332,54 @@
     "_OptionalDevEnvironmentRepositorySummaryTypeDef",
     {
         "branchName": str,
     },
     total=False,
 )
 
+
 class DevEnvironmentRepositorySummaryTypeDef(
     _RequiredDevEnvironmentRepositorySummaryTypeDef, _OptionalDevEnvironmentRepositorySummaryTypeDef
 ):
     pass
 
+
 _RequiredExecuteCommandSessionConfigurationTypeDef = TypedDict(
     "_RequiredExecuteCommandSessionConfigurationTypeDef",
     {
         "command": str,
     },
 )
 _OptionalExecuteCommandSessionConfigurationTypeDef = TypedDict(
     "_OptionalExecuteCommandSessionConfigurationTypeDef",
     {
         "arguments": Sequence[str],
     },
     total=False,
 )
 
+
 class ExecuteCommandSessionConfigurationTypeDef(
     _RequiredExecuteCommandSessionConfigurationTypeDef,
     _OptionalExecuteCommandSessionConfigurationTypeDef,
 ):
     pass
 
+
+DevEnvironmentSessionSummaryTypeDef = TypedDict(
+    "DevEnvironmentSessionSummaryTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "devEnvironmentId": str,
+        "startedTime": datetime,
+        "id": str,
+    },
+)
+
 IdeTypeDef = TypedDict(
     "IdeTypeDef",
     {
         "runtime": str,
         "name": str,
     },
     total=False,
@@ -357,17 +431,19 @@
     {
         "userName": str,
         "awsAccountId": str,
     },
     total=False,
 )
 
+
 class UserIdentityTypeDef(_RequiredUserIdentityTypeDef, _OptionalUserIdentityTypeDef):
     pass
 
+
 _RequiredFilterTypeDef = TypedDict(
     "_RequiredFilterTypeDef",
     {
         "key": str,
         "values": Sequence[str],
     },
 )
@@ -375,17 +451,19 @@
     "_OptionalFilterTypeDef",
     {
         "comparisonOperator": str,
     },
     total=False,
 )
 
+
 class FilterTypeDef(_RequiredFilterTypeDef, _OptionalFilterTypeDef):
     pass
 
+
 GetDevEnvironmentRequestRequestTypeDef = TypedDict(
     "GetDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
     },
@@ -395,65 +473,176 @@
     "GetProjectRequestRequestTypeDef",
     {
         "spaceName": str,
         "name": str,
     },
 )
 
+GetProjectResponseTypeDef = TypedDict(
+    "GetProjectResponseTypeDef",
+    {
+        "spaceName": str,
+        "name": str,
+        "displayName": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSourceRepositoryCloneUrlsRequestRequestTypeDef = TypedDict(
     "GetSourceRepositoryCloneUrlsRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "sourceRepositoryName": str,
     },
 )
 
+GetSourceRepositoryCloneUrlsResponseTypeDef = TypedDict(
+    "GetSourceRepositoryCloneUrlsResponseTypeDef",
+    {
+        "https": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSpaceRequestRequestTypeDef = TypedDict(
     "GetSpaceRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 
+GetSpaceResponseTypeDef = TypedDict(
+    "GetSpaceResponseTypeDef",
+    {
+        "name": str,
+        "regionName": str,
+        "displayName": str,
+        "description": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSubscriptionRequestRequestTypeDef = TypedDict(
     "GetSubscriptionRequestRequestTypeDef",
     {
         "spaceName": str,
     },
 )
 
+GetSubscriptionResponseTypeDef = TypedDict(
+    "GetSubscriptionResponseTypeDef",
+    {
+        "subscriptionType": str,
+        "awsAccountName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetUserDetailsRequestRequestTypeDef = TypedDict(
     "GetUserDetailsRequestRequestTypeDef",
     {
         "id": str,
         "userName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccessTokensRequestListAccessTokensPaginateTypeDef = TypedDict(
+    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccessTokensRequestRequestTypeDef = TypedDict(
     "ListAccessTokensRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef = TypedDict(
+    "_RequiredListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "devEnvironmentId": str,
+    },
+)
+_OptionalListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef = TypedDict(
+    "_OptionalListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef(
+    _RequiredListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef,
+    _OptionalListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListDevEnvironmentSessionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListDevEnvironmentSessionsRequestRequestTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "devEnvironmentId": str,
+    },
+)
+_OptionalListDevEnvironmentSessionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListDevEnvironmentSessionsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+
+class ListDevEnvironmentSessionsRequestRequestTypeDef(
+    _RequiredListDevEnvironmentSessionsRequestRequestTypeDef,
+    _OptionalListDevEnvironmentSessionsRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
+    "_RequiredListEventLogsRequestListEventLogsPaginateTypeDef",
+    {
+        "spaceName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+_OptionalListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
+    "_OptionalListEventLogsRequestListEventLogsPaginateTypeDef",
+    {
+        "eventName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEventLogsRequestListEventLogsPaginateTypeDef(
+    _RequiredListEventLogsRequestListEventLogsPaginateTypeDef,
+    _OptionalListEventLogsRequestListEventLogsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEventLogsRequestRequestTypeDef = TypedDict(
     "_RequiredListEventLogsRequestRequestTypeDef",
     {
         "spaceName": str,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
     },
@@ -464,19 +653,21 @@
         "eventName": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class ListEventLogsRequestRequestTypeDef(
     _RequiredListEventLogsRequestRequestTypeDef, _OptionalListEventLogsRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredProjectListFilterTypeDef = TypedDict(
     "_RequiredProjectListFilterTypeDef",
     {
         "key": Literal["hasAccessTo"],
         "values": Sequence[str],
     },
 )
@@ -484,19 +675,21 @@
     "_OptionalProjectListFilterTypeDef",
     {
         "comparisonOperator": ComparisonOperatorType,
     },
     total=False,
 )
 
+
 class ProjectListFilterTypeDef(
     _RequiredProjectListFilterTypeDef, _OptionalProjectListFilterTypeDef
 ):
     pass
 
+
 _RequiredProjectSummaryTypeDef = TypedDict(
     "_RequiredProjectSummaryTypeDef",
     {
         "name": str,
     },
 )
 _OptionalProjectSummaryTypeDef = TypedDict(
@@ -504,17 +697,19 @@
     {
         "displayName": str,
         "description": str,
     },
     total=False,
 )
 
+
 class ProjectSummaryTypeDef(_RequiredProjectSummaryTypeDef, _OptionalProjectSummaryTypeDef):
     pass
 
+
 _RequiredListSourceRepositoriesItemTypeDef = TypedDict(
     "_RequiredListSourceRepositoriesItemTypeDef",
     {
         "id": str,
         "name": str,
         "lastUpdatedTime": datetime,
         "createdTime": datetime,
@@ -524,19 +719,44 @@
     "_OptionalListSourceRepositoriesItemTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
+
 class ListSourceRepositoriesItemTypeDef(
     _RequiredListSourceRepositoriesItemTypeDef, _OptionalListSourceRepositoriesItemTypeDef
 ):
     pass
 
+
+_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
+    "_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+    },
+)
+_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
+    "_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef(
+    _RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
+    _OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSourceRepositoriesRequestRequestTypeDef = TypedDict(
     "_RequiredListSourceRepositoriesRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
     },
 )
@@ -545,31 +765,57 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class ListSourceRepositoriesRequestRequestTypeDef(
     _RequiredListSourceRepositoriesRequestRequestTypeDef,
     _OptionalListSourceRepositoriesRequestRequestTypeDef,
 ):
     pass
 
+
 ListSourceRepositoryBranchesItemTypeDef = TypedDict(
     "ListSourceRepositoryBranchesItemTypeDef",
     {
         "ref": str,
         "name": str,
         "lastUpdatedTime": datetime,
         "headCommitId": str,
     },
     total=False,
 )
 
+_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
+    "_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
+    {
+        "spaceName": str,
+        "projectName": str,
+        "sourceRepositoryName": str,
+    },
+)
+_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
+    "_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef(
+    _RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
+    _OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSourceRepositoryBranchesRequestRequestTypeDef = TypedDict(
     "_RequiredListSourceRepositoryBranchesRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "sourceRepositoryName": str,
     },
@@ -579,20 +825,30 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class ListSourceRepositoryBranchesRequestRequestTypeDef(
     _RequiredListSourceRepositoryBranchesRequestRequestTypeDef,
     _OptionalListSourceRepositoryBranchesRequestRequestTypeDef,
 ):
     pass
 
+
+ListSpacesRequestListSpacesPaginateTypeDef = TypedDict(
+    "ListSpacesRequestListSpacesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSpacesRequestRequestTypeDef = TypedDict(
     "ListSpacesRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
@@ -609,153 +865,106 @@
     {
         "displayName": str,
         "description": str,
     },
     total=False,
 )
 
+
 class SpaceSummaryTypeDef(_RequiredSpaceSummaryTypeDef, _OptionalSpaceSummaryTypeDef):
     pass
 
-StopDevEnvironmentRequestRequestTypeDef = TypedDict(
-    "StopDevEnvironmentRequestRequestTypeDef",
+
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "spaceName": str,
-        "projectName": str,
-        "id": str,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-CreateAccessTokenResponseTypeDef = TypedDict(
-    "CreateAccessTokenResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "secret": str,
-        "name": str,
-        "expiresTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-CreateDevEnvironmentResponseTypeDef = TypedDict(
-    "CreateDevEnvironmentResponseTypeDef",
+StartDevEnvironmentResponseTypeDef = TypedDict(
+    "StartDevEnvironmentResponseTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProjectResponseTypeDef = TypedDict(
-    "CreateProjectResponseTypeDef",
-    {
-        "spaceName": str,
-        "name": str,
-        "displayName": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSourceRepositoryBranchResponseTypeDef = TypedDict(
-    "CreateSourceRepositoryBranchResponseTypeDef",
-    {
-        "ref": str,
-        "name": str,
-        "lastUpdatedTime": datetime,
-        "headCommitId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "status": DevEnvironmentStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteDevEnvironmentResponseTypeDef = TypedDict(
-    "DeleteDevEnvironmentResponseTypeDef",
+StopDevEnvironmentRequestRequestTypeDef = TypedDict(
+    "StopDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-GetProjectResponseTypeDef = TypedDict(
-    "GetProjectResponseTypeDef",
+StopDevEnvironmentResponseTypeDef = TypedDict(
+    "StopDevEnvironmentResponseTypeDef",
     {
         "spaceName": str,
-        "name": str,
-        "displayName": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSourceRepositoryCloneUrlsResponseTypeDef = TypedDict(
-    "GetSourceRepositoryCloneUrlsResponseTypeDef",
-    {
-        "https": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSpaceResponseTypeDef = TypedDict(
-    "GetSpaceResponseTypeDef",
-    {
-        "name": str,
-        "regionName": str,
-        "displayName": str,
-        "description": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSubscriptionResponseTypeDef = TypedDict(
-    "GetSubscriptionResponseTypeDef",
-    {
-        "subscriptionType": str,
-        "awsAccountName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccessTokensResponseTypeDef = TypedDict(
-    "ListAccessTokensResponseTypeDef",
-    {
-        "items": List[AccessTokenSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "projectName": str,
+        "id": str,
+        "status": DevEnvironmentStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartDevEnvironmentResponseTypeDef = TypedDict(
-    "StartDevEnvironmentResponseTypeDef",
+StopDevEnvironmentSessionRequestRequestTypeDef = TypedDict(
+    "StopDevEnvironmentSessionRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "status": DevEnvironmentStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sessionId": str,
     },
 )
 
-StopDevEnvironmentResponseTypeDef = TypedDict(
-    "StopDevEnvironmentResponseTypeDef",
+StopDevEnvironmentSessionResponseTypeDef = TypedDict(
+    "StopDevEnvironmentSessionResponseTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "status": DevEnvironmentStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sessionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VerifySessionResponseTypeDef = TypedDict(
     "VerifySessionResponseTypeDef",
     {
         "identity": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAccessTokensResponseTypeDef = TypedDict(
+    "ListAccessTokensResponseTypeDef",
+    {
+        "items": List[AccessTokenSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartDevEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredStartDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
@@ -769,20 +978,22 @@
         "ides": Sequence[IdeConfigurationTypeDef],
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
     },
     total=False,
 )
 
+
 class StartDevEnvironmentRequestRequestTypeDef(
     _RequiredStartDevEnvironmentRequestRequestTypeDef,
     _OptionalStartDevEnvironmentRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateDevEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
     },
@@ -795,32 +1006,34 @@
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
         "clientToken": str,
     },
     total=False,
 )
 
+
 class UpdateDevEnvironmentRequestRequestTypeDef(
     _RequiredUpdateDevEnvironmentRequestRequestTypeDef,
     _OptionalUpdateDevEnvironmentRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateDevEnvironmentResponseTypeDef = TypedDict(
     "UpdateDevEnvironmentResponseTypeDef",
     {
         "id": str,
         "spaceName": str,
         "projectName": str,
         "alias": str,
         "ides": List[IdeConfigurationTypeDef],
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
         "clientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDevEnvironmentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDevEnvironmentRequestRequestTypeDef",
     {
         "spaceName": str,
@@ -837,29 +1050,31 @@
         "alias": str,
         "ides": Sequence[IdeConfigurationTypeDef],
         "inactivityTimeoutMinutes": int,
     },
     total=False,
 )
 
+
 class CreateDevEnvironmentRequestRequestTypeDef(
     _RequiredCreateDevEnvironmentRequestRequestTypeDef,
     _OptionalCreateDevEnvironmentRequestRequestTypeDef,
 ):
     pass
 
+
 StartDevEnvironmentSessionResponseTypeDef = TypedDict(
     "StartDevEnvironmentSessionResponseTypeDef",
     {
         "accessDetails": DevEnvironmentAccessDetailsTypeDef,
         "sessionId": str,
         "spaceName": str,
         "projectName": str,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDevEnvironmentSessionConfigurationTypeDef = TypedDict(
     "_RequiredDevEnvironmentSessionConfigurationTypeDef",
     {
         "sessionType": DevEnvironmentSessionTypeType,
@@ -869,20 +1084,31 @@
     "_OptionalDevEnvironmentSessionConfigurationTypeDef",
     {
         "executeCommandSessionConfiguration": ExecuteCommandSessionConfigurationTypeDef,
     },
     total=False,
 )
 
+
 class DevEnvironmentSessionConfigurationTypeDef(
     _RequiredDevEnvironmentSessionConfigurationTypeDef,
     _OptionalDevEnvironmentSessionConfigurationTypeDef,
 ):
     pass
 
+
+ListDevEnvironmentSessionsResponseTypeDef = TypedDict(
+    "ListDevEnvironmentSessionsResponseTypeDef",
+    {
+        "items": List[DevEnvironmentSessionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDevEnvironmentSummaryTypeDef = TypedDict(
     "_RequiredDevEnvironmentSummaryTypeDef",
     {
         "id": str,
         "lastUpdatedTime": datetime,
         "creatorId": str,
         "status": DevEnvironmentStatusType,
@@ -900,19 +1126,21 @@
         "statusReason": str,
         "alias": str,
         "ides": List[IdeTypeDef],
     },
     total=False,
 )
 
+
 class DevEnvironmentSummaryTypeDef(
     _RequiredDevEnvironmentSummaryTypeDef, _OptionalDevEnvironmentSummaryTypeDef
 ):
     pass
 
+
 GetDevEnvironmentResponseTypeDef = TypedDict(
     "GetDevEnvironmentResponseTypeDef",
     {
         "spaceName": str,
         "projectName": str,
         "id": str,
         "lastUpdatedTime": datetime,
@@ -921,27 +1149,27 @@
         "statusReason": str,
         "repositories": List[DevEnvironmentRepositorySummaryTypeDef],
         "alias": str,
         "ides": List[IdeTypeDef],
         "instanceType": InstanceTypeType,
         "inactivityTimeoutMinutes": int,
         "persistentStorage": PersistentStorageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserDetailsResponseTypeDef = TypedDict(
     "GetUserDetailsResponseTypeDef",
     {
         "userId": str,
         "userName": str,
         "displayName": str,
         "primaryEmail": EmailAddressTypeDef,
         "version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEventLogEntryTypeDef = TypedDict(
     "_RequiredEventLogEntryTypeDef",
     {
         "id": str,
@@ -964,165 +1192,91 @@
         "errorCode": str,
         "sourceIpAddress": str,
         "userAgent": str,
     },
     total=False,
 )
 
-class EventLogEntryTypeDef(_RequiredEventLogEntryTypeDef, _OptionalEventLogEntryTypeDef):
-    pass
 
-_RequiredListDevEnvironmentsRequestRequestTypeDef = TypedDict(
-    "_RequiredListDevEnvironmentsRequestRequestTypeDef",
-    {
-        "spaceName": str,
-        "projectName": str,
-    },
-)
-_OptionalListDevEnvironmentsRequestRequestTypeDef = TypedDict(
-    "_OptionalListDevEnvironmentsRequestRequestTypeDef",
-    {
-        "filters": Sequence[FilterTypeDef],
-        "nextToken": str,
-        "maxResults": int,
-    },
-    total=False,
-)
-
-class ListDevEnvironmentsRequestRequestTypeDef(
-    _RequiredListDevEnvironmentsRequestRequestTypeDef,
-    _OptionalListDevEnvironmentsRequestRequestTypeDef,
-):
+class EventLogEntryTypeDef(_RequiredEventLogEntryTypeDef, _OptionalEventLogEntryTypeDef):
     pass
 
-ListAccessTokensRequestListAccessTokensPaginateTypeDef = TypedDict(
-    "ListAccessTokensRequestListAccessTokensPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 _RequiredListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef = TypedDict(
     "_RequiredListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef",
     {
         "spaceName": str,
         "projectName": str,
     },
 )
 _OptionalListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef = TypedDict(
     "_OptionalListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef(
     _RequiredListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef,
     _OptionalListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef,
 ):
     pass
 
-_RequiredListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
-    "_RequiredListEventLogsRequestListEventLogsPaginateTypeDef",
-    {
-        "spaceName": str,
-        "startTime": Union[datetime, str],
-        "endTime": Union[datetime, str],
-    },
-)
-_OptionalListEventLogsRequestListEventLogsPaginateTypeDef = TypedDict(
-    "_OptionalListEventLogsRequestListEventLogsPaginateTypeDef",
-    {
-        "eventName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEventLogsRequestListEventLogsPaginateTypeDef(
-    _RequiredListEventLogsRequestListEventLogsPaginateTypeDef,
-    _OptionalListEventLogsRequestListEventLogsPaginateTypeDef,
-):
-    pass
 
-_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
-    "_RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
+_RequiredListDevEnvironmentsRequestRequestTypeDef = TypedDict(
+    "_RequiredListDevEnvironmentsRequestRequestTypeDef",
     {
         "spaceName": str,
         "projectName": str,
     },
 )
-_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef = TypedDict(
-    "_OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef",
+_OptionalListDevEnvironmentsRequestRequestTypeDef = TypedDict(
+    "_OptionalListDevEnvironmentsRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "filters": Sequence[FilterTypeDef],
+        "nextToken": str,
+        "maxResults": int,
     },
     total=False,
 )
 
-class ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef(
-    _RequiredListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
-    _OptionalListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
-):
-    pass
-
-_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
-    "_RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
-    {
-        "spaceName": str,
-        "projectName": str,
-        "sourceRepositoryName": str,
-    },
-)
-_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef = TypedDict(
-    "_OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-class ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef(
-    _RequiredListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
-    _OptionalListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
+class ListDevEnvironmentsRequestRequestTypeDef(
+    _RequiredListDevEnvironmentsRequestRequestTypeDef,
+    _OptionalListDevEnvironmentsRequestRequestTypeDef,
 ):
     pass
 
-ListSpacesRequestListSpacesPaginateTypeDef = TypedDict(
-    "ListSpacesRequestListSpacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 _RequiredListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
     "_RequiredListProjectsRequestListProjectsPaginateTypeDef",
     {
         "spaceName": str,
     },
 )
 _OptionalListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
     "_OptionalListProjectsRequestListProjectsPaginateTypeDef",
     {
         "filters": Sequence[ProjectListFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class ListProjectsRequestListProjectsPaginateTypeDef(
     _RequiredListProjectsRequestListProjectsPaginateTypeDef,
     _OptionalListProjectsRequestListProjectsPaginateTypeDef,
 ):
     pass
 
+
 _RequiredListProjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListProjectsRequestRequestTypeDef",
     {
         "spaceName": str,
     },
 )
 _OptionalListProjectsRequestRequestTypeDef = TypedDict(
@@ -1131,52 +1285,54 @@
         "nextToken": str,
         "maxResults": int,
         "filters": Sequence[ProjectListFilterTypeDef],
     },
     total=False,
 )
 
+
 class ListProjectsRequestRequestTypeDef(
     _RequiredListProjectsRequestRequestTypeDef, _OptionalListProjectsRequestRequestTypeDef
 ):
     pass
 
+
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "nextToken": str,
         "items": List[ProjectSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSourceRepositoriesResponseTypeDef = TypedDict(
     "ListSourceRepositoriesResponseTypeDef",
     {
         "items": List[ListSourceRepositoriesItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSourceRepositoryBranchesResponseTypeDef = TypedDict(
     "ListSourceRepositoryBranchesResponseTypeDef",
     {
         "nextToken": str,
         "items": List[ListSourceRepositoryBranchesItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSpacesResponseTypeDef = TypedDict(
     "ListSpacesResponseTypeDef",
     {
         "nextToken": str,
         "items": List[SpaceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDevEnvironmentSessionRequestRequestTypeDef = TypedDict(
     "StartDevEnvironmentSessionRequestRequestTypeDef",
     {
         "spaceName": str,
@@ -1187,19 +1343,19 @@
 )
 
 ListDevEnvironmentsResponseTypeDef = TypedDict(
     "ListDevEnvironmentsResponseTypeDef",
     {
         "items": List[DevEnvironmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventLogsResponseTypeDef = TypedDict(
     "ListEventLogsResponseTypeDef",
     {
         "nextToken": str,
         "items": List[EventLogEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/PKG-INFO` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codecatalyst
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeCatalyst 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeCatalyst 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codecatalyst"></a>
 
 # types-aiobotocore-codecatalyst
 
 [![PyPI - types-aiobotocore-codecatalyst](https://img.shields.io/pypi/v/types-aiobotocore-codecatalyst.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codecatalyst)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codecatalyst.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codecatalyst)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codecatalyst?color=blue)](https://pypistats.org/packages/types-aiobotocore-codecatalyst)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeCatalyst 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst)
+[aiobotocore.CodeCatalyst 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codecatalyst.html#CodeCatalyst)
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
 [types-aiobotocore-codecatalyst docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codecatalyst/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,14 +274,15 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_codecatalyst import CodeCatalystClient
 from types_aiobotocore_codecatalyst.paginator import (
     ListAccessTokensPaginator,
+    ListDevEnvironmentSessionsPaginator,
     ListDevEnvironmentsPaginator,
     ListEventLogsPaginator,
     ListProjectsPaginator,
     ListSourceRepositoriesPaginator,
     ListSourceRepositoryBranchesPaginator,
     ListSpacesPaginator,
 )
@@ -291,14 +292,17 @@
     client: CodeCatalystClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     list_access_tokens_paginator: ListAccessTokensPaginator = client.get_paginator(
         "list_access_tokens"
     )
+    list_dev_environment_sessions_paginator: ListDevEnvironmentSessionsPaginator = (
+        client.get_paginator("list_dev_environment_sessions")
+    )
     list_dev_environments_paginator: ListDevEnvironmentsPaginator = client.get_paginator(
         "list_dev_environments"
     )
     list_event_logs_paginator: ListEventLogsPaginator = client.get_paginator("list_event_logs")
     list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     list_source_repositories_paginator: ListSourceRepositoriesPaginator = client.get_paginator(
         "list_source_repositories"
@@ -320,14 +324,15 @@
 from types_aiobotocore_codecatalyst.literals import (
     ComparisonOperatorType,
     DevEnvironmentSessionTypeType,
     DevEnvironmentStatusType,
     FilterKeyType,
     InstanceTypeType,
     ListAccessTokensPaginatorName,
+    ListDevEnvironmentSessionsPaginatorName,
     ListDevEnvironmentsPaginatorName,
     ListEventLogsPaginatorName,
     ListProjectsPaginatorName,
     ListSourceRepositoriesPaginatorName,
     ListSourceRepositoryBranchesPaginatorName,
     ListSpacesPaginatorName,
     OperationTypeType,
@@ -350,80 +355,86 @@
 `types_aiobotocore_codecatalyst.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codecatalyst.type_defs import (
     AccessTokenSummaryTypeDef,
     CreateAccessTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAccessTokenResponseTypeDef,
     IdeConfigurationTypeDef,
     PersistentStorageConfigurationTypeDef,
     RepositoryInputTypeDef,
+    CreateDevEnvironmentResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
+    CreateProjectResponseTypeDef,
     CreateSourceRepositoryBranchRequestRequestTypeDef,
+    CreateSourceRepositoryBranchResponseTypeDef,
     DeleteAccessTokenRequestRequestTypeDef,
     DeleteDevEnvironmentRequestRequestTypeDef,
+    DeleteDevEnvironmentResponseTypeDef,
     DevEnvironmentAccessDetailsTypeDef,
     DevEnvironmentRepositorySummaryTypeDef,
     ExecuteCommandSessionConfigurationTypeDef,
+    DevEnvironmentSessionSummaryTypeDef,
     IdeTypeDef,
     PersistentStorageTypeDef,
     EmailAddressTypeDef,
     EventPayloadTypeDef,
     ProjectInformationTypeDef,
     UserIdentityTypeDef,
     FilterTypeDef,
     GetDevEnvironmentRequestRequestTypeDef,
     GetProjectRequestRequestTypeDef,
+    GetProjectResponseTypeDef,
     GetSourceRepositoryCloneUrlsRequestRequestTypeDef,
+    GetSourceRepositoryCloneUrlsResponseTypeDef,
     GetSpaceRequestRequestTypeDef,
+    GetSpaceResponseTypeDef,
     GetSubscriptionRequestRequestTypeDef,
+    GetSubscriptionResponseTypeDef,
     GetUserDetailsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccessTokensRequestListAccessTokensPaginateTypeDef,
     ListAccessTokensRequestRequestTypeDef,
+    ListDevEnvironmentSessionsRequestListDevEnvironmentSessionsPaginateTypeDef,
+    ListDevEnvironmentSessionsRequestRequestTypeDef,
+    ListEventLogsRequestListEventLogsPaginateTypeDef,
     ListEventLogsRequestRequestTypeDef,
     ProjectListFilterTypeDef,
     ProjectSummaryTypeDef,
     ListSourceRepositoriesItemTypeDef,
+    ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
     ListSourceRepositoriesRequestRequestTypeDef,
     ListSourceRepositoryBranchesItemTypeDef,
+    ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
     ListSourceRepositoryBranchesRequestRequestTypeDef,
+    ListSpacesRequestListSpacesPaginateTypeDef,
     ListSpacesRequestRequestTypeDef,
     SpaceSummaryTypeDef,
-    StopDevEnvironmentRequestRequestTypeDef,
-    CreateAccessTokenResponseTypeDef,
-    CreateDevEnvironmentResponseTypeDef,
-    CreateProjectResponseTypeDef,
-    CreateSourceRepositoryBranchResponseTypeDef,
-    DeleteDevEnvironmentResponseTypeDef,
-    GetProjectResponseTypeDef,
-    GetSourceRepositoryCloneUrlsResponseTypeDef,
-    GetSpaceResponseTypeDef,
-    GetSubscriptionResponseTypeDef,
-    ListAccessTokensResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentRequestRequestTypeDef,
     StopDevEnvironmentResponseTypeDef,
+    StopDevEnvironmentSessionRequestRequestTypeDef,
+    StopDevEnvironmentSessionResponseTypeDef,
     VerifySessionResponseTypeDef,
+    ListAccessTokensResponseTypeDef,
     StartDevEnvironmentRequestRequestTypeDef,
     UpdateDevEnvironmentRequestRequestTypeDef,
     UpdateDevEnvironmentResponseTypeDef,
     CreateDevEnvironmentRequestRequestTypeDef,
     StartDevEnvironmentSessionResponseTypeDef,
     DevEnvironmentSessionConfigurationTypeDef,
+    ListDevEnvironmentSessionsResponseTypeDef,
     DevEnvironmentSummaryTypeDef,
     GetDevEnvironmentResponseTypeDef,
     GetUserDetailsResponseTypeDef,
     EventLogEntryTypeDef,
-    ListDevEnvironmentsRequestRequestTypeDef,
-    ListAccessTokensRequestListAccessTokensPaginateTypeDef,
     ListDevEnvironmentsRequestListDevEnvironmentsPaginateTypeDef,
-    ListEventLogsRequestListEventLogsPaginateTypeDef,
-    ListSourceRepositoriesRequestListSourceRepositoriesPaginateTypeDef,
-    ListSourceRepositoryBranchesRequestListSourceRepositoryBranchesPaginateTypeDef,
-    ListSpacesRequestListSpacesPaginateTypeDef,
+    ListDevEnvironmentsRequestRequestTypeDef,
     ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ListProjectsResponseTypeDef,
     ListSourceRepositoriesResponseTypeDef,
     ListSourceRepositoryBranchesResponseTypeDef,
     ListSpacesResponseTypeDef,
     StartDevEnvironmentSessionRequestRequestTypeDef,
@@ -439,43 +450,43 @@
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

### Comparing `types-aiobotocore-codecatalyst-2.5.0.post1/types_aiobotocore_codecatalyst.egg-info/SOURCES.txt` & `types-aiobotocore-codecatalyst-2.5.1/types_aiobotocore_codecatalyst.egg-info/SOURCES.txt`

 * *Files identical despite different names*

