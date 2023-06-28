# Comparing `tmp/types-aiobotocore-serverlessrepo-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-serverlessrepo-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-serverlessrepo-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-serverlessrepo-2.5.1.tar", last modified: Wed Jun 28 01:44:09 2023, max compression
```

## Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1.tar` & `types-aiobotocore-serverlessrepo-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.747612 types-aiobotocore-serverlessrepo-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15668 2023-03-11 12:27:18.747612 types-aiobotocore-serverlessrepo-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14052 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:18.747612 types-aiobotocore-serverlessrepo-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2190 2023-03-11 12:23:54.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.747612 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/
--rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1005 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16558 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16532 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8479 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8477 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4937 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4931 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19295 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19265 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:55.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.747612 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15668 2023-03-11 12:27:18.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:27:18.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:18.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:18.000000 types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.938212 types-aiobotocore-serverlessrepo-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15667 2023-06-28 01:44:09.934212 types-aiobotocore-serverlessrepo-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14057 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:09.938212 types-aiobotocore-serverlessrepo-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2184 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.934212 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/
+-rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1339 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      993 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16558 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16532 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8688 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8686 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4823 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4818 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19327 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19297 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:44.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.934212 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15667 2023-06-28 01:44:09.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:44:09.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:09.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:09.000000 types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/LICENSE` & `types-aiobotocore-serverlessrepo-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/PKG-INFO` & `types-aiobotocore-serverlessrepo-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-serverlessrepo
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-serverlessrepo"></a>
 
 # types-aiobotocore-serverlessrepo
 
 [![PyPI - types-aiobotocore-serverlessrepo](https://img.shields.io/pypi/v/types-aiobotocore-serverlessrepo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-serverlessrepo)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-serverlessrepo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-serverlessrepo)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-serverlessrepo?color=blue)](https://pypistats.org/packages/types-aiobotocore-serverlessrepo)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServerlessApplicationRepository 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository)
+[aiobotocore.ServerlessApplicationRepository 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository)
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
 [types-aiobotocore-serverlessrepo docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,46 +334,46 @@
 
 ```python
 from types_aiobotocore_serverlessrepo.type_defs import (
     ApplicationDependencySummaryTypeDef,
     ApplicationPolicyStatementTypeDef,
     ApplicationSummaryTypeDef,
     CreateApplicationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateApplicationVersionRequestRequestTypeDef,
     ParameterDefinitionTypeDef,
     ParameterValueTypeDef,
     TagTypeDef,
+    CreateCloudFormationChangeSetResponseTypeDef,
     CreateCloudFormationTemplateRequestRequestTypeDef,
+    CreateCloudFormationTemplateResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetApplicationPolicyRequestRequestTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetCloudFormationTemplateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetCloudFormationTemplateResponseTypeDef,
+    ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
     ListApplicationDependenciesRequestRequestTypeDef,
+    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
     VersionSummaryTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTriggerTypeDef,
     UnshareApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    PutApplicationPolicyRequestRequestTypeDef,
-    CreateCloudFormationChangeSetResponseTypeDef,
-    CreateCloudFormationTemplateResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetApplicationPolicyResponseTypeDef,
-    GetCloudFormationTemplateResponseTypeDef,
     ListApplicationDependenciesResponseTypeDef,
-    ListApplicationsResponseTypeDef,
+    GetApplicationPolicyResponseTypeDef,
+    PutApplicationPolicyRequestRequestTypeDef,
     PutApplicationPolicyResponseTypeDef,
+    ListApplicationsResponseTypeDef,
     CreateApplicationVersionResponseTypeDef,
     VersionTypeDef,
-    ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
-    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationVersionsResponseTypeDef,
     RollbackConfigurationTypeDef,
     CreateApplicationResponseTypeDef,
     GetApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
     CreateCloudFormationChangeSetRequestRequestTypeDef,
 )
@@ -386,43 +386,43 @@
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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/README.md` & `types-aiobotocore-serverlessrepo-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-serverlessrepo"></a>
 
 # types-aiobotocore-serverlessrepo
 
 [![PyPI - types-aiobotocore-serverlessrepo](https://img.shields.io/pypi/v/types-aiobotocore-serverlessrepo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-serverlessrepo)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-serverlessrepo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-serverlessrepo)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-serverlessrepo?color=blue)](https://pypistats.org/packages/types-aiobotocore-serverlessrepo)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServerlessApplicationRepository 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository)
+[aiobotocore.ServerlessApplicationRepository 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository)
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
 [types-aiobotocore-serverlessrepo docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/).
 
 See how it helps to find and fix potential bugs:
 
@@ -301,46 +301,46 @@
 
 ```python
 from types_aiobotocore_serverlessrepo.type_defs import (
     ApplicationDependencySummaryTypeDef,
     ApplicationPolicyStatementTypeDef,
     ApplicationSummaryTypeDef,
     CreateApplicationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateApplicationVersionRequestRequestTypeDef,
     ParameterDefinitionTypeDef,
     ParameterValueTypeDef,
     TagTypeDef,
+    CreateCloudFormationChangeSetResponseTypeDef,
     CreateCloudFormationTemplateRequestRequestTypeDef,
+    CreateCloudFormationTemplateResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetApplicationPolicyRequestRequestTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetCloudFormationTemplateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetCloudFormationTemplateResponseTypeDef,
+    ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
     ListApplicationDependenciesRequestRequestTypeDef,
+    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
     VersionSummaryTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTriggerTypeDef,
     UnshareApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    PutApplicationPolicyRequestRequestTypeDef,
-    CreateCloudFormationChangeSetResponseTypeDef,
-    CreateCloudFormationTemplateResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetApplicationPolicyResponseTypeDef,
-    GetCloudFormationTemplateResponseTypeDef,
     ListApplicationDependenciesResponseTypeDef,
-    ListApplicationsResponseTypeDef,
+    GetApplicationPolicyResponseTypeDef,
+    PutApplicationPolicyRequestRequestTypeDef,
     PutApplicationPolicyResponseTypeDef,
+    ListApplicationsResponseTypeDef,
     CreateApplicationVersionResponseTypeDef,
     VersionTypeDef,
-    ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
-    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationVersionsResponseTypeDef,
     RollbackConfigurationTypeDef,
     CreateApplicationResponseTypeDef,
     GetApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
     CreateCloudFormationChangeSetRequestRequestTypeDef,
 )
@@ -353,43 +353,43 @@
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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/setup.py` & `types-aiobotocore-serverlessrepo-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-serverlessrepo.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-serverlessrepo",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_serverlessrepo"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.0 service generated"
-        " with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.1 service generated"
+        " with mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/"
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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/__init__.py` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/__init__.pyi` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/__main__.py` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository\nOther"
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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/client.py` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/client.pyi` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/literals.py` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -99,14 +99,15 @@
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
@@ -185,14 +186,15 @@
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
@@ -203,14 +205,15 @@
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
@@ -246,14 +249,15 @@
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
@@ -272,16 +276,19 @@
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
@@ -365,15 +372,17 @@
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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/literals.pyi` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -97,14 +97,15 @@
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
@@ -183,14 +184,15 @@
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
@@ -201,14 +203,15 @@
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
@@ -244,14 +247,15 @@
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
@@ -270,16 +274,19 @@
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
@@ -363,15 +370,17 @@
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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/paginator.py` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -20,90 +20,78 @@
         client: ServerlessApplicationRepositoryClient
 
         list_application_dependencies_paginator: ListApplicationDependenciesPaginator = client.get_paginator("list_application_dependencies")
         list_application_versions_paginator: ListApplicationVersionsPaginator = client.get_paginator("list_application_versions")
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationDependenciesResponseTypeDef,
     ListApplicationsResponseTypeDef,
     ListApplicationVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApplicationDependenciesPaginator",
     "ListApplicationVersionsPaginator",
     "ListApplicationsPaginator",
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
 class ListApplicationDependenciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationDependencies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationdependenciespaginator)
     """
 
     def paginate(
         self,
         *,
         ApplicationId: str,
         SemanticVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationDependenciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationDependencies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationdependenciespaginator)
         """
 
-
 class ListApplicationVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationversionspaginator)
     """
 
     def paginate(
-        self, *, ApplicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApplicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationversionspaginator)
         """
 
-
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationspaginator)
         """
```

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/paginator.pyi` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -20,84 +20,83 @@
         client: ServerlessApplicationRepositoryClient
 
         list_application_dependencies_paginator: ListApplicationDependenciesPaginator = client.get_paginator("list_application_dependencies")
         list_application_versions_paginator: ListApplicationVersionsPaginator = client.get_paginator("list_application_versions")
         list_applications_paginator: ListApplicationsPaginator = client.get_paginator("list_applications")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListApplicationDependenciesResponseTypeDef,
     ListApplicationsResponseTypeDef,
     ListApplicationVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApplicationDependenciesPaginator",
     "ListApplicationVersionsPaginator",
     "ListApplicationsPaginator",
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
 class ListApplicationDependenciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationDependencies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationdependenciespaginator)
     """
 
     def paginate(
         self,
         *,
         ApplicationId: str,
         SemanticVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationDependenciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationDependencies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationdependenciespaginator)
         """
 
+
 class ListApplicationVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationversionspaginator)
     """
 
     def paginate(
-        self, *, ApplicationId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ApplicationId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplicationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationversionspaginator)
         """
 
+
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/paginators/#listapplicationspaginator)
         """
```

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/type_defs.py` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -23,46 +23,46 @@
 
 
 __all__ = (
     "ApplicationDependencySummaryTypeDef",
     "ApplicationPolicyStatementTypeDef",
     "ApplicationSummaryTypeDef",
     "CreateApplicationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateApplicationVersionRequestRequestTypeDef",
     "ParameterDefinitionTypeDef",
     "ParameterValueTypeDef",
     "TagTypeDef",
+    "CreateCloudFormationChangeSetResponseTypeDef",
     "CreateCloudFormationTemplateRequestRequestTypeDef",
+    "CreateCloudFormationTemplateResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetApplicationPolicyRequestRequestTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetCloudFormationTemplateRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetCloudFormationTemplateResponseTypeDef",
+    "ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
     "ListApplicationDependenciesRequestRequestTypeDef",
+    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
     "ListApplicationVersionsRequestRequestTypeDef",
     "VersionSummaryTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackTriggerTypeDef",
     "UnshareApplicationRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "PutApplicationPolicyRequestRequestTypeDef",
-    "CreateCloudFormationChangeSetResponseTypeDef",
-    "CreateCloudFormationTemplateResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetApplicationPolicyResponseTypeDef",
-    "GetCloudFormationTemplateResponseTypeDef",
     "ListApplicationDependenciesResponseTypeDef",
-    "ListApplicationsResponseTypeDef",
+    "GetApplicationPolicyResponseTypeDef",
+    "PutApplicationPolicyRequestRequestTypeDef",
     "PutApplicationPolicyResponseTypeDef",
+    "ListApplicationsResponseTypeDef",
     "CreateApplicationVersionResponseTypeDef",
     "VersionTypeDef",
-    "ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
-    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationVersionsResponseTypeDef",
     "RollbackConfigurationTypeDef",
     "CreateApplicationResponseTypeDef",
     "GetApplicationResponseTypeDef",
     "UpdateApplicationResponseTypeDef",
     "CreateCloudFormationChangeSetRequestRequestTypeDef",
 )
@@ -155,25 +155,14 @@
 
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
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
 _RequiredCreateApplicationVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationVersionRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "SemanticVersion": str,
     },
 )
@@ -240,14 +229,25 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateCloudFormationChangeSetResponseTypeDef = TypedDict(
+    "CreateCloudFormationChangeSetResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "ChangeSetId": str,
+        "SemanticVersion": str,
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateCloudFormationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCloudFormationTemplateRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalCreateCloudFormationTemplateRequestRequestTypeDef = TypedDict(
@@ -262,21 +262,42 @@
 class CreateCloudFormationTemplateRequestRequestTypeDef(
     _RequiredCreateCloudFormationTemplateRequestRequestTypeDef,
     _OptionalCreateCloudFormationTemplateRequestRequestTypeDef,
 ):
     pass
 
 
+CreateCloudFormationTemplateResponseTypeDef = TypedDict(
+    "CreateCloudFormationTemplateResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "CreationTime": str,
+        "ExpirationTime": str,
+        "SemanticVersion": str,
+        "Status": StatusType,
+        "TemplateId": str,
+        "TemplateUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetApplicationPolicyRequestRequestTypeDef = TypedDict(
     "GetApplicationPolicyRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -305,24 +326,51 @@
     "GetCloudFormationTemplateRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "TemplateId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetCloudFormationTemplateResponseTypeDef = TypedDict(
+    "GetCloudFormationTemplateResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationId": str,
+        "CreationTime": str,
+        "ExpirationTime": str,
+        "SemanticVersion": str,
+        "Status": StatusType,
+        "TemplateId": str,
+        "TemplateUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
+    {
+        "ApplicationId": str,
+    },
+)
+_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
+    {
+        "SemanticVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef(
+    _RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
+    _OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListApplicationDependenciesRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationDependenciesRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalListApplicationDependenciesRequestRequestTypeDef = TypedDict(
@@ -339,14 +387,36 @@
 class ListApplicationDependenciesRequestRequestTypeDef(
     _RequiredListApplicationDependenciesRequestRequestTypeDef,
     _OptionalListApplicationDependenciesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
+    {
+        "ApplicationId": str,
+    },
+)
+_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
+    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListApplicationVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationVersionsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalListApplicationVersionsRequestRequestTypeDef = TypedDict(
@@ -383,23 +453,52 @@
 )
 
 
 class VersionSummaryTypeDef(_RequiredVersionSummaryTypeDef, _OptionalVersionSummaryTypeDef):
     pass
 
 
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "MaxItems": int,
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
 RollbackTriggerTypeDef = TypedDict(
     "RollbackTriggerTypeDef",
     {
         "Arn": str,
         "Type": str,
     },
 )
@@ -434,99 +533,53 @@
 
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
 
-PutApplicationPolicyRequestRequestTypeDef = TypedDict(
-    "PutApplicationPolicyRequestRequestTypeDef",
-    {
-        "ApplicationId": str,
-        "Statements": Sequence[ApplicationPolicyStatementTypeDef],
-    },
-)
-
-CreateCloudFormationChangeSetResponseTypeDef = TypedDict(
-    "CreateCloudFormationChangeSetResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "ChangeSetId": str,
-        "SemanticVersion": str,
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCloudFormationTemplateResponseTypeDef = TypedDict(
-    "CreateCloudFormationTemplateResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "CreationTime": str,
-        "ExpirationTime": str,
-        "SemanticVersion": str,
-        "Status": StatusType,
-        "TemplateId": str,
-        "TemplateUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+ListApplicationDependenciesResponseTypeDef = TypedDict(
+    "ListApplicationDependenciesResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Dependencies": List[ApplicationDependencySummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationPolicyResponseTypeDef = TypedDict(
     "GetApplicationPolicyResponseTypeDef",
     {
         "Statements": List[ApplicationPolicyStatementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetCloudFormationTemplateResponseTypeDef = TypedDict(
-    "GetCloudFormationTemplateResponseTypeDef",
+PutApplicationPolicyRequestRequestTypeDef = TypedDict(
+    "PutApplicationPolicyRequestRequestTypeDef",
     {
         "ApplicationId": str,
-        "CreationTime": str,
-        "ExpirationTime": str,
-        "SemanticVersion": str,
-        "Status": StatusType,
-        "TemplateId": str,
-        "TemplateUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Statements": Sequence[ApplicationPolicyStatementTypeDef],
     },
 )
 
-ListApplicationDependenciesResponseTypeDef = TypedDict(
-    "ListApplicationDependenciesResponseTypeDef",
+PutApplicationPolicyResponseTypeDef = TypedDict(
+    "PutApplicationPolicyResponseTypeDef",
     {
-        "Dependencies": List[ApplicationDependencySummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Statements": List[ApplicationPolicyStatementTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "Applications": List[ApplicationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutApplicationPolicyResponseTypeDef = TypedDict(
-    "PutApplicationPolicyResponseTypeDef",
-    {
-        "Statements": List[ApplicationPolicyStatementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateApplicationVersionResponseTypeDef = TypedDict(
     "CreateApplicationVersionResponseTypeDef",
     {
         "ApplicationId": str,
@@ -534,15 +587,15 @@
         "ParameterDefinitions": List[ParameterDefinitionTypeDef],
         "RequiredCapabilities": List[CapabilityType],
         "ResourcesSupported": bool,
         "SemanticVersion": str,
         "SourceCodeArchiveUrl": str,
         "SourceCodeUrl": str,
         "TemplateUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVersionTypeDef = TypedDict(
     "_RequiredVersionTypeDef",
     {
         "ApplicationId": str,
@@ -564,73 +617,20 @@
 )
 
 
 class VersionTypeDef(_RequiredVersionTypeDef, _OptionalVersionTypeDef):
     pass
 
 
-_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
-    {
-        "ApplicationId": str,
-    },
-)
-_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
-    {
-        "SemanticVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef(
-    _RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
-    _OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "ApplicationId": str,
-    },
-)
-_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
-    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListApplicationVersionsResponseTypeDef = TypedDict(
     "ListApplicationVersionsResponseTypeDef",
     {
         "NextToken": str,
         "Versions": List[VersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RollbackConfigurationTypeDef = TypedDict(
     "RollbackConfigurationTypeDef",
     {
         "MonitoringTimeInMinutes": int,
@@ -651,15 +651,15 @@
         "Labels": List[str],
         "LicenseUrl": str,
         "Name": str,
         "ReadmeUrl": str,
         "SpdxLicenseId": str,
         "VerifiedAuthorUrl": str,
         "Version": VersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationResponseTypeDef = TypedDict(
     "GetApplicationResponseTypeDef",
     {
         "ApplicationId": str,
@@ -671,15 +671,15 @@
         "Labels": List[str],
         "LicenseUrl": str,
         "Name": str,
         "ReadmeUrl": str,
         "SpdxLicenseId": str,
         "VerifiedAuthorUrl": str,
         "Version": VersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "ApplicationId": str,
@@ -691,15 +691,15 @@
         "Labels": List[str],
         "LicenseUrl": str,
         "Name": str,
         "ReadmeUrl": str,
         "SpdxLicenseId": str,
         "VerifiedAuthorUrl": str,
         "Version": VersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCloudFormationChangeSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCloudFormationChangeSetRequestRequestTypeDef",
     {
         "ApplicationId": str,
```

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo/type_defs.pyi` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -22,46 +22,46 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "ApplicationDependencySummaryTypeDef",
     "ApplicationPolicyStatementTypeDef",
     "ApplicationSummaryTypeDef",
     "CreateApplicationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateApplicationVersionRequestRequestTypeDef",
     "ParameterDefinitionTypeDef",
     "ParameterValueTypeDef",
     "TagTypeDef",
+    "CreateCloudFormationChangeSetResponseTypeDef",
     "CreateCloudFormationTemplateRequestRequestTypeDef",
+    "CreateCloudFormationTemplateResponseTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetApplicationPolicyRequestRequestTypeDef",
     "GetApplicationRequestRequestTypeDef",
     "GetCloudFormationTemplateRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetCloudFormationTemplateResponseTypeDef",
+    "ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
     "ListApplicationDependenciesRequestRequestTypeDef",
+    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
     "ListApplicationVersionsRequestRequestTypeDef",
     "VersionSummaryTypeDef",
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationsRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RollbackTriggerTypeDef",
     "UnshareApplicationRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
-    "PutApplicationPolicyRequestRequestTypeDef",
-    "CreateCloudFormationChangeSetResponseTypeDef",
-    "CreateCloudFormationTemplateResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetApplicationPolicyResponseTypeDef",
-    "GetCloudFormationTemplateResponseTypeDef",
     "ListApplicationDependenciesResponseTypeDef",
-    "ListApplicationsResponseTypeDef",
+    "GetApplicationPolicyResponseTypeDef",
+    "PutApplicationPolicyRequestRequestTypeDef",
     "PutApplicationPolicyResponseTypeDef",
+    "ListApplicationsResponseTypeDef",
     "CreateApplicationVersionResponseTypeDef",
     "VersionTypeDef",
-    "ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
-    "ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
     "ListApplicationVersionsResponseTypeDef",
     "RollbackConfigurationTypeDef",
     "CreateApplicationResponseTypeDef",
     "GetApplicationResponseTypeDef",
     "UpdateApplicationResponseTypeDef",
     "CreateCloudFormationChangeSetRequestRequestTypeDef",
 )
@@ -148,25 +148,14 @@
 )
 
 class CreateApplicationRequestRequestTypeDef(
     _RequiredCreateApplicationRequestRequestTypeDef, _OptionalCreateApplicationRequestRequestTypeDef
 ):
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
 _RequiredCreateApplicationVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationVersionRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "SemanticVersion": str,
     },
 )
@@ -229,14 +218,25 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateCloudFormationChangeSetResponseTypeDef = TypedDict(
+    "CreateCloudFormationChangeSetResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "ChangeSetId": str,
+        "SemanticVersion": str,
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateCloudFormationTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCloudFormationTemplateRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalCreateCloudFormationTemplateRequestRequestTypeDef = TypedDict(
@@ -249,21 +249,42 @@
 
 class CreateCloudFormationTemplateRequestRequestTypeDef(
     _RequiredCreateCloudFormationTemplateRequestRequestTypeDef,
     _OptionalCreateCloudFormationTemplateRequestRequestTypeDef,
 ):
     pass
 
+CreateCloudFormationTemplateResponseTypeDef = TypedDict(
+    "CreateCloudFormationTemplateResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "CreationTime": str,
+        "ExpirationTime": str,
+        "SemanticVersion": str,
+        "Status": StatusType,
+        "TemplateId": str,
+        "TemplateUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationRequestRequestTypeDef = TypedDict(
     "DeleteApplicationRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetApplicationPolicyRequestRequestTypeDef = TypedDict(
     "GetApplicationPolicyRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -290,24 +311,49 @@
     "GetCloudFormationTemplateRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "TemplateId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetCloudFormationTemplateResponseTypeDef = TypedDict(
+    "GetCloudFormationTemplateResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationId": str,
+        "CreationTime": str,
+        "ExpirationTime": str,
+        "SemanticVersion": str,
+        "Status": StatusType,
+        "TemplateId": str,
+        "TemplateUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
+    {
+        "ApplicationId": str,
+    },
+)
+_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
+    {
+        "SemanticVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef(
+    _RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
+    _OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListApplicationDependenciesRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationDependenciesRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalListApplicationDependenciesRequestRequestTypeDef = TypedDict(
@@ -322,14 +368,34 @@
 
 class ListApplicationDependenciesRequestRequestTypeDef(
     _RequiredListApplicationDependenciesRequestRequestTypeDef,
     _OptionalListApplicationDependenciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
+    {
+        "ApplicationId": str,
+    },
+)
+_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
+    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListApplicationVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListApplicationVersionsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalListApplicationVersionsRequestRequestTypeDef = TypedDict(
@@ -362,23 +428,52 @@
     },
     total=False,
 )
 
 class VersionSummaryTypeDef(_RequiredVersionSummaryTypeDef, _OptionalVersionSummaryTypeDef):
     pass
 
+ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsRequestListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsRequestRequestTypeDef = TypedDict(
     "ListApplicationsRequestRequestTypeDef",
     {
         "MaxItems": int,
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
 RollbackTriggerTypeDef = TypedDict(
     "RollbackTriggerTypeDef",
     {
         "Arn": str,
         "Type": str,
     },
 )
@@ -411,99 +506,53 @@
 )
 
 class UpdateApplicationRequestRequestTypeDef(
     _RequiredUpdateApplicationRequestRequestTypeDef, _OptionalUpdateApplicationRequestRequestTypeDef
 ):
     pass
 
-PutApplicationPolicyRequestRequestTypeDef = TypedDict(
-    "PutApplicationPolicyRequestRequestTypeDef",
-    {
-        "ApplicationId": str,
-        "Statements": Sequence[ApplicationPolicyStatementTypeDef],
-    },
-)
-
-CreateCloudFormationChangeSetResponseTypeDef = TypedDict(
-    "CreateCloudFormationChangeSetResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "ChangeSetId": str,
-        "SemanticVersion": str,
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCloudFormationTemplateResponseTypeDef = TypedDict(
-    "CreateCloudFormationTemplateResponseTypeDef",
-    {
-        "ApplicationId": str,
-        "CreationTime": str,
-        "ExpirationTime": str,
-        "SemanticVersion": str,
-        "Status": StatusType,
-        "TemplateId": str,
-        "TemplateUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+ListApplicationDependenciesResponseTypeDef = TypedDict(
+    "ListApplicationDependenciesResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Dependencies": List[ApplicationDependencySummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationPolicyResponseTypeDef = TypedDict(
     "GetApplicationPolicyResponseTypeDef",
     {
         "Statements": List[ApplicationPolicyStatementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetCloudFormationTemplateResponseTypeDef = TypedDict(
-    "GetCloudFormationTemplateResponseTypeDef",
+PutApplicationPolicyRequestRequestTypeDef = TypedDict(
+    "PutApplicationPolicyRequestRequestTypeDef",
     {
         "ApplicationId": str,
-        "CreationTime": str,
-        "ExpirationTime": str,
-        "SemanticVersion": str,
-        "Status": StatusType,
-        "TemplateId": str,
-        "TemplateUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Statements": Sequence[ApplicationPolicyStatementTypeDef],
     },
 )
 
-ListApplicationDependenciesResponseTypeDef = TypedDict(
-    "ListApplicationDependenciesResponseTypeDef",
+PutApplicationPolicyResponseTypeDef = TypedDict(
+    "PutApplicationPolicyResponseTypeDef",
     {
-        "Dependencies": List[ApplicationDependencySummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Statements": List[ApplicationPolicyStatementTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "Applications": List[ApplicationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutApplicationPolicyResponseTypeDef = TypedDict(
-    "PutApplicationPolicyResponseTypeDef",
-    {
-        "Statements": List[ApplicationPolicyStatementTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateApplicationVersionResponseTypeDef = TypedDict(
     "CreateApplicationVersionResponseTypeDef",
     {
         "ApplicationId": str,
@@ -511,15 +560,15 @@
         "ParameterDefinitions": List[ParameterDefinitionTypeDef],
         "RequiredCapabilities": List[CapabilityType],
         "ResourcesSupported": bool,
         "SemanticVersion": str,
         "SourceCodeArchiveUrl": str,
         "SourceCodeUrl": str,
         "TemplateUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVersionTypeDef = TypedDict(
     "_RequiredVersionTypeDef",
     {
         "ApplicationId": str,
@@ -539,69 +588,20 @@
     },
     total=False,
 )
 
 class VersionTypeDef(_RequiredVersionTypeDef, _OptionalVersionTypeDef):
     pass
 
-_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
-    {
-        "ApplicationId": str,
-    },
-)
-_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef",
-    {
-        "SemanticVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef(
-    _RequiredListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
-    _OptionalListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "ApplicationId": str,
-    },
-)
-_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef(
-    _RequiredListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    _OptionalListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-):
-    pass
-
-ListApplicationsRequestListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsRequestListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListApplicationVersionsResponseTypeDef = TypedDict(
     "ListApplicationVersionsResponseTypeDef",
     {
         "NextToken": str,
         "Versions": List[VersionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RollbackConfigurationTypeDef = TypedDict(
     "RollbackConfigurationTypeDef",
     {
         "MonitoringTimeInMinutes": int,
@@ -622,15 +622,15 @@
         "Labels": List[str],
         "LicenseUrl": str,
         "Name": str,
         "ReadmeUrl": str,
         "SpdxLicenseId": str,
         "VerifiedAuthorUrl": str,
         "Version": VersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationResponseTypeDef = TypedDict(
     "GetApplicationResponseTypeDef",
     {
         "ApplicationId": str,
@@ -642,15 +642,15 @@
         "Labels": List[str],
         "LicenseUrl": str,
         "Name": str,
         "ReadmeUrl": str,
         "SpdxLicenseId": str,
         "VerifiedAuthorUrl": str,
         "Version": VersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationResponseTypeDef = TypedDict(
     "UpdateApplicationResponseTypeDef",
     {
         "ApplicationId": str,
@@ -662,15 +662,15 @@
         "Labels": List[str],
         "LicenseUrl": str,
         "Name": str,
         "ReadmeUrl": str,
         "SpdxLicenseId": str,
         "VerifiedAuthorUrl": str,
         "Version": VersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCloudFormationChangeSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCloudFormationChangeSetRequestRequestTypeDef",
     {
         "ApplicationId": str,
```

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/PKG-INFO` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-serverlessrepo
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ServerlessApplicationRepository 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-serverlessrepo"></a>
 
 # types-aiobotocore-serverlessrepo
 
 [![PyPI - types-aiobotocore-serverlessrepo](https://img.shields.io/pypi/v/types-aiobotocore-serverlessrepo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-serverlessrepo)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-serverlessrepo.svg?color=blue)](https://pypi.org/project/types-aiobotocore-serverlessrepo)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-serverlessrepo?color=blue)](https://pypistats.org/packages/types-aiobotocore-serverlessrepo)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ServerlessApplicationRepository 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository)
+[aiobotocore.ServerlessApplicationRepository 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/serverlessrepo.html#ServerlessApplicationRepository)
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
 [types-aiobotocore-serverlessrepo docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_serverlessrepo/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,46 +334,46 @@
 
 ```python
 from types_aiobotocore_serverlessrepo.type_defs import (
     ApplicationDependencySummaryTypeDef,
     ApplicationPolicyStatementTypeDef,
     ApplicationSummaryTypeDef,
     CreateApplicationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     CreateApplicationVersionRequestRequestTypeDef,
     ParameterDefinitionTypeDef,
     ParameterValueTypeDef,
     TagTypeDef,
+    CreateCloudFormationChangeSetResponseTypeDef,
     CreateCloudFormationTemplateRequestRequestTypeDef,
+    CreateCloudFormationTemplateResponseTypeDef,
     DeleteApplicationRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetApplicationPolicyRequestRequestTypeDef,
     GetApplicationRequestRequestTypeDef,
     GetCloudFormationTemplateRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetCloudFormationTemplateResponseTypeDef,
+    ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
     ListApplicationDependenciesRequestRequestTypeDef,
+    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
     ListApplicationVersionsRequestRequestTypeDef,
     VersionSummaryTypeDef,
+    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationsRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RollbackTriggerTypeDef,
     UnshareApplicationRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
-    PutApplicationPolicyRequestRequestTypeDef,
-    CreateCloudFormationChangeSetResponseTypeDef,
-    CreateCloudFormationTemplateResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetApplicationPolicyResponseTypeDef,
-    GetCloudFormationTemplateResponseTypeDef,
     ListApplicationDependenciesResponseTypeDef,
-    ListApplicationsResponseTypeDef,
+    GetApplicationPolicyResponseTypeDef,
+    PutApplicationPolicyRequestRequestTypeDef,
     PutApplicationPolicyResponseTypeDef,
+    ListApplicationsResponseTypeDef,
     CreateApplicationVersionResponseTypeDef,
     VersionTypeDef,
-    ListApplicationDependenciesRequestListApplicationDependenciesPaginateTypeDef,
-    ListApplicationVersionsRequestListApplicationVersionsPaginateTypeDef,
-    ListApplicationsRequestListApplicationsPaginateTypeDef,
     ListApplicationVersionsResponseTypeDef,
     RollbackConfigurationTypeDef,
     CreateApplicationResponseTypeDef,
     GetApplicationResponseTypeDef,
     UpdateApplicationResponseTypeDef,
     CreateCloudFormationChangeSetRequestRequestTypeDef,
 )
@@ -386,43 +386,43 @@
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

### Comparing `types-aiobotocore-serverlessrepo-2.5.0.post1/types_aiobotocore_serverlessrepo.egg-info/SOURCES.txt` & `types-aiobotocore-serverlessrepo-2.5.1/types_aiobotocore_serverlessrepo.egg-info/SOURCES.txt`

 * *Files identical despite different names*

