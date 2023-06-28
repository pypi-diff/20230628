# Comparing `tmp/types-aiobotocore-kendra-ranking-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kendra-ranking-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kendra-ranking-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:49 2023, max compression
+gzip compressed data, was "types-aiobotocore-kendra-ranking-2.5.1.tar", last modified: Wed Jun 28 01:43:42 2023, max compression
```

## Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1.tar` & `types-aiobotocore-kendra-ranking-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.391324 types-aiobotocore-kendra-ranking-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13258 2023-03-11 12:26:49.391324 types-aiobotocore-kendra-ranking-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11660 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:49.391324 types-aiobotocore-kendra-ranking-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.391324 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/
--rw-r--r--   0 runner    (1001) docker     (123)      493 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      492 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9954 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9937 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8027 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8025 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6903 2023-03-11 12:16:53.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6896 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.391324 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13258 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      853 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.074160 types-aiobotocore-kendra-ranking-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13257 2023-06-28 01:43:42.074160 types-aiobotocore-kendra-ranking-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11665 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:42.074160 types-aiobotocore-kendra-ranking-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.074160 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/
+-rw-r--r--   0 runner    (1001) docker     (123)      493 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      492 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9954 2023-06-28 01:33:32.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9937 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8236 2023-06-28 01:33:33.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8234 2023-06-28 01:33:32.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6915 2023-06-28 01:33:33.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6908 2023-06-28 01:33:33.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.074160 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13257 2023-06-28 01:43:41.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      853 2023-06-28 01:43:41.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:41.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:41.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:41.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:41.000000 types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/LICENSE` & `types-aiobotocore-kendra-ranking-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kendra-ranking-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kendra-ranking
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KendraRanking 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KendraRanking 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kendra-ranking"></a>
 
 # types-aiobotocore-kendra-ranking
 
 [![PyPI - types-aiobotocore-kendra-ranking](https://img.shields.io/pypi/v/types-aiobotocore-kendra-ranking.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra-ranking)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kendra-ranking.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra-ranking)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kendra-ranking?color=blue)](https://pypistats.org/packages/types-aiobotocore-kendra-ranking)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KendraRanking 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra-ranking.html#KendraRanking)
+[aiobotocore.KendraRanking 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra-ranking.html#KendraRanking)
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
 [types-aiobotocore-kendra-ranking docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,30 +292,30 @@
 `types_aiobotocore_kendra_ranking.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kendra_ranking.type_defs import (
     CapacityUnitsConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateRescoreExecutionPlanResponseTypeDef,
     DeleteRescoreExecutionPlanRequestRequestTypeDef,
     DescribeRescoreExecutionPlanRequestRequestTypeDef,
     DocumentTypeDef,
+    EmptyResponseMetadataTypeDef,
     ListRescoreExecutionPlansRequestRequestTypeDef,
     RescoreExecutionPlanSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RescoreResultItemTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    DescribeRescoreExecutionPlanResponseTypeDef,
     UpdateRescoreExecutionPlanRequestRequestTypeDef,
     CreateRescoreExecutionPlanRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateRescoreExecutionPlanResponseTypeDef,
-    DescribeRescoreExecutionPlanResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     RescoreRequestRequestTypeDef,
     ListRescoreExecutionPlansResponseTypeDef,
     RescoreResultTypeDef,
 )
 
 
 def get_structure() -> CapacityUnitsConfigurationTypeDef:
@@ -325,43 +325,43 @@
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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/README.md` & `types-aiobotocore-kendra-ranking-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kendra-ranking"></a>
 
 # types-aiobotocore-kendra-ranking
 
 [![PyPI - types-aiobotocore-kendra-ranking](https://img.shields.io/pypi/v/types-aiobotocore-kendra-ranking.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra-ranking)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kendra-ranking.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra-ranking)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kendra-ranking?color=blue)](https://pypistats.org/packages/types-aiobotocore-kendra-ranking)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KendraRanking 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra-ranking.html#KendraRanking)
+[aiobotocore.KendraRanking 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra-ranking.html#KendraRanking)
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
 [types-aiobotocore-kendra-ranking docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/).
 
 See how it helps to find and fix potential bugs:
 
@@ -259,30 +259,30 @@
 `types_aiobotocore_kendra_ranking.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kendra_ranking.type_defs import (
     CapacityUnitsConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateRescoreExecutionPlanResponseTypeDef,
     DeleteRescoreExecutionPlanRequestRequestTypeDef,
     DescribeRescoreExecutionPlanRequestRequestTypeDef,
     DocumentTypeDef,
+    EmptyResponseMetadataTypeDef,
     ListRescoreExecutionPlansRequestRequestTypeDef,
     RescoreExecutionPlanSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RescoreResultItemTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    DescribeRescoreExecutionPlanResponseTypeDef,
     UpdateRescoreExecutionPlanRequestRequestTypeDef,
     CreateRescoreExecutionPlanRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateRescoreExecutionPlanResponseTypeDef,
-    DescribeRescoreExecutionPlanResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     RescoreRequestRequestTypeDef,
     ListRescoreExecutionPlansResponseTypeDef,
     RescoreResultTypeDef,
 )
 
 
 def get_structure() -> CapacityUnitsConfigurationTypeDef:
@@ -292,43 +292,43 @@
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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/setup.py` & `types-aiobotocore-kendra-ranking-2.5.1/setup.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kendra-ranking.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kendra-ranking",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kendra_ranking"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KendraRanking 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.KendraRanking 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/"
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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/__main__.py` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KendraRanking 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KendraRanking 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra-ranking.html#KendraRanking\nOther"
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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/client.py` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/client.pyi` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/literals.py` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -88,14 +88,15 @@
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
@@ -174,14 +175,15 @@
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
@@ -192,14 +194,15 @@
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
@@ -235,14 +238,15 @@
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
@@ -261,16 +265,19 @@
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
@@ -354,15 +361,17 @@
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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/literals.pyi` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -86,14 +86,15 @@
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
@@ -172,14 +173,15 @@
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
@@ -190,14 +192,15 @@
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
@@ -233,14 +236,15 @@
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
@@ -259,16 +263,19 @@
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
@@ -352,15 +359,17 @@
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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/type_defs.py` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -18,34 +18,33 @@
 from .literals import RescoreExecutionPlanStatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "CapacityUnitsConfigurationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateRescoreExecutionPlanResponseTypeDef",
     "DeleteRescoreExecutionPlanRequestRequestTypeDef",
     "DescribeRescoreExecutionPlanRequestRequestTypeDef",
     "DocumentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ListRescoreExecutionPlansRequestRequestTypeDef",
     "RescoreExecutionPlanSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "RescoreResultItemTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "DescribeRescoreExecutionPlanResponseTypeDef",
     "UpdateRescoreExecutionPlanRequestRequestTypeDef",
     "CreateRescoreExecutionPlanRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateRescoreExecutionPlanResponseTypeDef",
-    "DescribeRescoreExecutionPlanResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "RescoreRequestRequestTypeDef",
     "ListRescoreExecutionPlansResponseTypeDef",
     "RescoreResultTypeDef",
 )
 
 CapacityUnitsConfigurationTypeDef = TypedDict(
     "CapacityUnitsConfigurationTypeDef",
@@ -58,22 +57,20 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateRescoreExecutionPlanResponseTypeDef = TypedDict(
+    "CreateRescoreExecutionPlanResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
     "DeleteRescoreExecutionPlanRequestRequestTypeDef",
     {
         "Id": str,
@@ -102,18 +99,23 @@
         "Body": str,
         "TokenizedTitle": Sequence[str],
         "TokenizedBody": Sequence[str],
     },
     total=False,
 )
 
-
 class DocumentTypeDef(_RequiredDocumentTypeDef, _OptionalDocumentTypeDef):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ListRescoreExecutionPlansRequestRequestTypeDef = TypedDict(
     "ListRescoreExecutionPlansRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
@@ -144,22 +146,49 @@
     {
         "DocumentId": str,
         "Score": float,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+DescribeRescoreExecutionPlanResponseTypeDef = TypedDict(
+    "DescribeRescoreExecutionPlanResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "Name": str,
+        "Description": str,
+        "CapacityUnits": CapacityUnitsConfigurationTypeDef,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "Status": RescoreExecutionPlanStatusType,
+        "ErrorMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRescoreExecutionPlanRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
@@ -168,22 +197,20 @@
         "Name": str,
         "Description": str,
         "CapacityUnits": CapacityUnitsConfigurationTypeDef,
     },
     total=False,
 )
 
-
 class UpdateRescoreExecutionPlanRequestRequestTypeDef(
     _RequiredUpdateRescoreExecutionPlanRequestRequestTypeDef,
     _OptionalUpdateRescoreExecutionPlanRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRescoreExecutionPlanRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
@@ -193,89 +220,55 @@
         "CapacityUnits": CapacityUnitsConfigurationTypeDef,
         "Tags": Sequence[TagTypeDef],
         "ClientToken": str,
     },
     total=False,
 )
 
-
 class CreateRescoreExecutionPlanRequestRequestTypeDef(
     _RequiredCreateRescoreExecutionPlanRequestRequestTypeDef,
     _OptionalCreateRescoreExecutionPlanRequestRequestTypeDef,
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-CreateRescoreExecutionPlanResponseTypeDef = TypedDict(
-    "CreateRescoreExecutionPlanResponseTypeDef",
-    {
-        "Id": str,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRescoreExecutionPlanResponseTypeDef = TypedDict(
-    "DescribeRescoreExecutionPlanResponseTypeDef",
-    {
-        "Id": str,
-        "Arn": str,
-        "Name": str,
-        "Description": str,
-        "CapacityUnits": CapacityUnitsConfigurationTypeDef,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "Status": RescoreExecutionPlanStatusType,
-        "ErrorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 RescoreRequestRequestTypeDef = TypedDict(
     "RescoreRequestRequestTypeDef",
     {
         "RescoreExecutionPlanId": str,
         "SearchQuery": str,
         "Documents": Sequence[DocumentTypeDef],
     },
 )
 
 ListRescoreExecutionPlansResponseTypeDef = TypedDict(
     "ListRescoreExecutionPlansResponseTypeDef",
     {
         "SummaryItems": List[RescoreExecutionPlanSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RescoreResultTypeDef = TypedDict(
     "RescoreResultTypeDef",
     {
         "RescoreId": str,
         "ResultItems": List[RescoreResultItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking/type_defs.pyi` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -18,33 +18,34 @@
 from .literals import RescoreExecutionPlanStatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "CapacityUnitsConfigurationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateRescoreExecutionPlanResponseTypeDef",
     "DeleteRescoreExecutionPlanRequestRequestTypeDef",
     "DescribeRescoreExecutionPlanRequestRequestTypeDef",
     "DocumentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ListRescoreExecutionPlansRequestRequestTypeDef",
     "RescoreExecutionPlanSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "RescoreResultItemTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "DescribeRescoreExecutionPlanResponseTypeDef",
     "UpdateRescoreExecutionPlanRequestRequestTypeDef",
     "CreateRescoreExecutionPlanRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateRescoreExecutionPlanResponseTypeDef",
-    "DescribeRescoreExecutionPlanResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "RescoreRequestRequestTypeDef",
     "ListRescoreExecutionPlansResponseTypeDef",
     "RescoreResultTypeDef",
 )
 
 CapacityUnitsConfigurationTypeDef = TypedDict(
     "CapacityUnitsConfigurationTypeDef",
@@ -57,22 +58,20 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateRescoreExecutionPlanResponseTypeDef = TypedDict(
+    "CreateRescoreExecutionPlanResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
     "DeleteRescoreExecutionPlanRequestRequestTypeDef",
     {
         "Id": str,
@@ -101,17 +100,26 @@
         "Body": str,
         "TokenizedTitle": Sequence[str],
         "TokenizedBody": Sequence[str],
     },
     total=False,
 )
 
+
 class DocumentTypeDef(_RequiredDocumentTypeDef, _OptionalDocumentTypeDef):
     pass
 
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListRescoreExecutionPlansRequestRequestTypeDef = TypedDict(
     "ListRescoreExecutionPlansRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -141,22 +149,49 @@
     {
         "DocumentId": str,
         "Score": float,
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+DescribeRescoreExecutionPlanResponseTypeDef = TypedDict(
+    "DescribeRescoreExecutionPlanResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "Name": str,
+        "Description": str,
+        "CapacityUnits": CapacityUnitsConfigurationTypeDef,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "Status": RescoreExecutionPlanStatusType,
+        "ErrorMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRescoreExecutionPlanRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
@@ -165,20 +200,22 @@
         "Name": str,
         "Description": str,
         "CapacityUnits": CapacityUnitsConfigurationTypeDef,
     },
     total=False,
 )
 
+
 class UpdateRescoreExecutionPlanRequestRequestTypeDef(
     _RequiredUpdateRescoreExecutionPlanRequestRequestTypeDef,
     _OptionalUpdateRescoreExecutionPlanRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRescoreExecutionPlanRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateRescoreExecutionPlanRequestRequestTypeDef = TypedDict(
@@ -188,65 +225,35 @@
         "CapacityUnits": CapacityUnitsConfigurationTypeDef,
         "Tags": Sequence[TagTypeDef],
         "ClientToken": str,
     },
     total=False,
 )
 
+
 class CreateRescoreExecutionPlanRequestRequestTypeDef(
     _RequiredCreateRescoreExecutionPlanRequestRequestTypeDef,
     _OptionalCreateRescoreExecutionPlanRequestRequestTypeDef,
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateRescoreExecutionPlanResponseTypeDef = TypedDict(
-    "CreateRescoreExecutionPlanResponseTypeDef",
-    {
-        "Id": str,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRescoreExecutionPlanResponseTypeDef = TypedDict(
-    "DescribeRescoreExecutionPlanResponseTypeDef",
-    {
-        "Id": str,
-        "Arn": str,
-        "Name": str,
-        "Description": str,
-        "CapacityUnits": CapacityUnitsConfigurationTypeDef,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "Status": RescoreExecutionPlanStatusType,
-        "ErrorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 RescoreRequestRequestTypeDef = TypedDict(
     "RescoreRequestRequestTypeDef",
     {
         "RescoreExecutionPlanId": str,
@@ -256,19 +263,19 @@
 )
 
 ListRescoreExecutionPlansResponseTypeDef = TypedDict(
     "ListRescoreExecutionPlansResponseTypeDef",
     {
         "SummaryItems": List[RescoreExecutionPlanSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RescoreResultTypeDef = TypedDict(
     "RescoreResultTypeDef",
     {
         "RescoreId": str,
         "ResultItems": List[RescoreResultItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/PKG-INFO` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kendra-ranking
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KendraRanking 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KendraRanking 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kendra-ranking"></a>
 
 # types-aiobotocore-kendra-ranking
 
 [![PyPI - types-aiobotocore-kendra-ranking](https://img.shields.io/pypi/v/types-aiobotocore-kendra-ranking.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra-ranking)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kendra-ranking.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra-ranking)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kendra-ranking?color=blue)](https://pypistats.org/packages/types-aiobotocore-kendra-ranking)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KendraRanking 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra-ranking.html#KendraRanking)
+[aiobotocore.KendraRanking 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra-ranking.html#KendraRanking)
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
 [types-aiobotocore-kendra-ranking docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra_ranking/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,30 +292,30 @@
 `types_aiobotocore_kendra_ranking.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kendra_ranking.type_defs import (
     CapacityUnitsConfigurationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateRescoreExecutionPlanResponseTypeDef,
     DeleteRescoreExecutionPlanRequestRequestTypeDef,
     DescribeRescoreExecutionPlanRequestRequestTypeDef,
     DocumentTypeDef,
+    EmptyResponseMetadataTypeDef,
     ListRescoreExecutionPlansRequestRequestTypeDef,
     RescoreExecutionPlanSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RescoreResultItemTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    DescribeRescoreExecutionPlanResponseTypeDef,
     UpdateRescoreExecutionPlanRequestRequestTypeDef,
     CreateRescoreExecutionPlanRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateRescoreExecutionPlanResponseTypeDef,
-    DescribeRescoreExecutionPlanResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     RescoreRequestRequestTypeDef,
     ListRescoreExecutionPlansResponseTypeDef,
     RescoreResultTypeDef,
 )
 
 
 def get_structure() -> CapacityUnitsConfigurationTypeDef:
@@ -325,43 +325,43 @@
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

### Comparing `types-aiobotocore-kendra-ranking-2.5.0.post1/types_aiobotocore_kendra_ranking.egg-info/SOURCES.txt` & `types-aiobotocore-kendra-ranking-2.5.1/types_aiobotocore_kendra_ranking.egg-info/SOURCES.txt`

 * *Files identical despite different names*

