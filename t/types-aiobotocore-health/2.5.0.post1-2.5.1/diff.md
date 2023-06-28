# Comparing `tmp/types-aiobotocore-health-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-health-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-health-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:42 2023, max compression
+gzip compressed data, was "types-aiobotocore-health-2.5.1.tar", last modified: Wed Jun 28 01:43:34 2023, max compression
```

## Comparing `types-aiobotocore-health-2.5.0.post1.tar` & `types-aiobotocore-health-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.243252 types-aiobotocore-health-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16681 2023-03-11 12:26:42.243252 types-aiobotocore-health-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15114 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:42.243252 types-aiobotocore-health-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:15:33.000000 types-aiobotocore-health-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.243252 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/
--rw-r--r--   0 runner    (1001) docker     (123)     2353 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2352 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17083 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17054 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9191 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9189 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10352 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    10342 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    21635 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    21610 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:34.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.243252 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16681 2023-03-11 12:26:42.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:26:42.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:42.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:42.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:42.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:42.000000 types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.030145 types-aiobotocore-health-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16672 2023-06-28 01:43:34.030145 types-aiobotocore-health-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15111 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:34.030145 types-aiobotocore-health-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:32:09.000000 types-aiobotocore-health-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.022145 types-aiobotocore-health-2.5.1/types_aiobotocore_health/
+-rw-r--r--   0 runner    (1001) docker     (123)     2353 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2352 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17083 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17054 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9400 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9398 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10259 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10249 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21673 2023-06-28 01:32:11.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21648 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:10.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:34.030145 types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16672 2023-06-28 01:43:33.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:33.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:33.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:33.000000 types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-health-2.5.0.post1/LICENSE` & `types-aiobotocore-health-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-health-2.5.0.post1/PKG-INFO` & `types-aiobotocore-health-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-health
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Health 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Health 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-health"></a>
 
 # types-aiobotocore-health
 
 [![PyPI - types-aiobotocore-health](https://img.shields.io/pypi/v/types-aiobotocore-health.svg?color=blue)](https://pypi.org/project/types-aiobotocore-health)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-health.svg?color=blue)](https://pypi.org/project/types-aiobotocore-health)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-health?color=blue)](https://pypistats.org/packages/types-aiobotocore-health)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Health 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health)
+[aiobotocore.Health 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health)
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
 [types-aiobotocore-health docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/).
 
 See how it helps to find and fix potential bugs:
 
@@ -352,38 +352,38 @@
 `types_aiobotocore_health.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_health.type_defs import (
     AffectedEntityTypeDef,
     DateTimeRangeTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
     DescribeAffectedAccountsForOrganizationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeAffectedAccountsForOrganizationResponseTypeDef,
     EventAccountFilterTypeDef,
     OrganizationAffectedEntitiesErrorItemTypeDef,
     DescribeEntityAggregatesRequestRequestTypeDef,
     EntityAggregateTypeDef,
     EventAggregateTypeDef,
     OrganizationEventDetailsErrorItemTypeDef,
     DescribeEventDetailsRequestRequestTypeDef,
     EventDetailsErrorItemTypeDef,
     EventTypeFilterTypeDef,
     EventTypeTypeDef,
     OrganizationEventTypeDef,
     EventTypeDef,
+    DescribeHealthServiceStatusForOrganizationResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventDescriptionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeAffectedEntitiesResponseTypeDef,
     EntityFilterTypeDef,
     EventFilterTypeDef,
     OrganizationEventFilterTypeDef,
-    DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
-    DescribeAffectedAccountsForOrganizationResponseTypeDef,
-    DescribeAffectedEntitiesResponseTypeDef,
-    DescribeHealthServiceStatusForOrganizationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     DescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef,
     DescribeAffectedEntitiesForOrganizationRequestRequestTypeDef,
     DescribeEventDetailsForOrganizationRequestRequestTypeDef,
     DescribeAffectedEntitiesForOrganizationResponseTypeDef,
     DescribeEntityAggregatesResponseTypeDef,
     DescribeEventAggregatesResponseTypeDef,
     DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef,
@@ -413,43 +413,43 @@
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

### Comparing `types-aiobotocore-health-2.5.0.post1/README.md` & `types-aiobotocore-health-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-health"></a>
 
 # types-aiobotocore-health
 
 [![PyPI - types-aiobotocore-health](https://img.shields.io/pypi/v/types-aiobotocore-health.svg?color=blue)](https://pypi.org/project/types-aiobotocore-health)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-health.svg?color=blue)](https://pypi.org/project/types-aiobotocore-health)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-health?color=blue)](https://pypistats.org/packages/types-aiobotocore-health)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Health 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health)
+[aiobotocore.Health 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health)
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
 [types-aiobotocore-health docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/).
 
 See how it helps to find and fix potential bugs:
 
@@ -319,38 +319,38 @@
 `types_aiobotocore_health.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_health.type_defs import (
     AffectedEntityTypeDef,
     DateTimeRangeTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
     DescribeAffectedAccountsForOrganizationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeAffectedAccountsForOrganizationResponseTypeDef,
     EventAccountFilterTypeDef,
     OrganizationAffectedEntitiesErrorItemTypeDef,
     DescribeEntityAggregatesRequestRequestTypeDef,
     EntityAggregateTypeDef,
     EventAggregateTypeDef,
     OrganizationEventDetailsErrorItemTypeDef,
     DescribeEventDetailsRequestRequestTypeDef,
     EventDetailsErrorItemTypeDef,
     EventTypeFilterTypeDef,
     EventTypeTypeDef,
     OrganizationEventTypeDef,
     EventTypeDef,
+    DescribeHealthServiceStatusForOrganizationResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventDescriptionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeAffectedEntitiesResponseTypeDef,
     EntityFilterTypeDef,
     EventFilterTypeDef,
     OrganizationEventFilterTypeDef,
-    DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
-    DescribeAffectedAccountsForOrganizationResponseTypeDef,
-    DescribeAffectedEntitiesResponseTypeDef,
-    DescribeHealthServiceStatusForOrganizationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     DescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef,
     DescribeAffectedEntitiesForOrganizationRequestRequestTypeDef,
     DescribeEventDetailsForOrganizationRequestRequestTypeDef,
     DescribeAffectedEntitiesForOrganizationResponseTypeDef,
     DescribeEntityAggregatesResponseTypeDef,
     DescribeEventAggregatesResponseTypeDef,
     DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef,
@@ -380,43 +380,43 @@
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

### Comparing `types-aiobotocore-health-2.5.0.post1/setup.py` & `types-aiobotocore-health-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-health.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-health",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_health"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Health 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Health 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/"
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

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/__init__.py` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/__init__.pyi` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/__main__.py` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Health 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Health 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health\nOther"
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

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/client.py` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/client.pyi` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/literals.py` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/literals.py`

 * *Files 6% similar despite different names*

```diff
@@ -115,14 +115,15 @@
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
@@ -201,14 +202,15 @@
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
@@ -219,14 +221,15 @@
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
@@ -262,14 +265,15 @@
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
@@ -288,16 +292,19 @@
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
@@ -381,15 +388,17 @@
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

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/literals.pyi` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -113,14 +113,15 @@
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
@@ -199,14 +200,15 @@
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
@@ -217,14 +219,15 @@
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
@@ -260,14 +263,15 @@
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
@@ -286,16 +290,19 @@
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
@@ -379,15 +386,17 @@
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

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/paginator.py` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -29,15 +29,15 @@
         describe_event_aggregates_paginator: DescribeEventAggregatesPaginator = client.get_paginator("describe_event_aggregates")
         describe_event_types_paginator: DescribeEventTypesPaginator = client.get_paginator("describe_event_types")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_events_for_organization_paginator: DescribeEventsForOrganizationPaginator = client.get_paginator("describe_events_for_organization")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAffectedAccountsForOrganizationResponseTypeDef,
     DescribeAffectedEntitiesForOrganizationResponseTypeDef,
@@ -50,165 +50,151 @@
     EventAccountFilterTypeDef,
     EventFilterTypeDef,
     EventTypeFilterTypeDef,
     OrganizationEventFilterTypeDef,
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
     "DescribeAffectedAccountsForOrganizationPaginator",
     "DescribeAffectedEntitiesPaginator",
     "DescribeAffectedEntitiesForOrganizationPaginator",
     "DescribeEventAggregatesPaginator",
     "DescribeEventTypesPaginator",
     "DescribeEventsPaginator",
     "DescribeEventsForOrganizationPaginator",
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
 class DescribeAffectedAccountsForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedAccountsForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedaccountsfororganizationpaginator)
     """
 
     def paginate(
-        self, *, eventArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, eventArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAffectedAccountsForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedAccountsForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedaccountsfororganizationpaginator)
         """
 
-
 class DescribeAffectedEntitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: EntityFilterTypeDef,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAffectedEntitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiespaginator)
         """
 
-
 class DescribeAffectedEntitiesForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntitiesForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiesfororganizationpaginator)
     """
 
     def paginate(
         self,
         *,
         organizationEntityFilters: Sequence[EventAccountFilterTypeDef],
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAffectedEntitiesForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntitiesForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiesfororganizationpaginator)
         """
 
-
 class DescribeEventAggregatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventAggregates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventaggregatespaginator)
     """
 
     def paginate(
         self,
         *,
         aggregateField: Literal["eventTypeCategory"],
         filter: EventFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventAggregatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventAggregates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventaggregatespaginator)
         """
 
-
 class DescribeEventTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventtypespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: EventTypeFilterTypeDef = ...,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventtypespaginator)
         """
 
-
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         filter: EventFilterTypeDef = ...,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventspaginator)
         """
 
-
 class DescribeEventsForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventsForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventsfororganizationpaginator)
     """
 
     def paginate(
         self,
         *,
         filter: OrganizationEventFilterTypeDef = ...,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventsForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventsfororganizationpaginator)
         """
```

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/paginator.pyi` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -29,15 +29,15 @@
         describe_event_aggregates_paginator: DescribeEventAggregatesPaginator = client.get_paginator("describe_event_aggregates")
         describe_event_types_paginator: DescribeEventTypesPaginator = client.get_paginator("describe_event_types")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         describe_events_for_organization_paginator: DescribeEventsForOrganizationPaginator = client.get_paginator("describe_events_for_organization")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAffectedAccountsForOrganizationResponseTypeDef,
     DescribeAffectedEntitiesForOrganizationResponseTypeDef,
@@ -50,155 +50,161 @@
     EventAccountFilterTypeDef,
     EventFilterTypeDef,
     EventTypeFilterTypeDef,
     OrganizationEventFilterTypeDef,
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
     "DescribeAffectedAccountsForOrganizationPaginator",
     "DescribeAffectedEntitiesPaginator",
     "DescribeAffectedEntitiesForOrganizationPaginator",
     "DescribeEventAggregatesPaginator",
     "DescribeEventTypesPaginator",
     "DescribeEventsPaginator",
     "DescribeEventsForOrganizationPaginator",
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
 class DescribeAffectedAccountsForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedAccountsForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedaccountsfororganizationpaginator)
     """
 
     def paginate(
-        self, *, eventArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, eventArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAffectedAccountsForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedAccountsForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedaccountsfororganizationpaginator)
         """
 
+
 class DescribeAffectedEntitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: EntityFilterTypeDef,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAffectedEntitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiespaginator)
         """
 
+
 class DescribeAffectedEntitiesForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntitiesForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiesfororganizationpaginator)
     """
 
     def paginate(
         self,
         *,
         organizationEntityFilters: Sequence[EventAccountFilterTypeDef],
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAffectedEntitiesForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeAffectedEntitiesForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeaffectedentitiesfororganizationpaginator)
         """
 
+
 class DescribeEventAggregatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventAggregates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventaggregatespaginator)
     """
 
     def paginate(
         self,
         *,
         aggregateField: Literal["eventTypeCategory"],
         filter: EventFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventAggregatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventAggregates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventaggregatespaginator)
         """
 
+
 class DescribeEventTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventtypespaginator)
     """
 
     def paginate(
         self,
         *,
         filter: EventTypeFilterTypeDef = ...,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventtypespaginator)
         """
 
+
 class DescribeEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventspaginator)
     """
 
     def paginate(
         self,
         *,
         filter: EventFilterTypeDef = ...,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventspaginator)
         """
 
+
 class DescribeEventsForOrganizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventsForOrganization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventsfororganizationpaginator)
     """
 
     def paginate(
         self,
         *,
         filter: OrganizationEventFilterTypeDef = ...,
         locale: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEventsForOrganizationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health.Paginator.DescribeEventsForOrganization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/paginators/#describeeventsfororganizationpaginator)
         """
```

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/type_defs.py` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -27,42 +27,41 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AffectedEntityTypeDef",
     "DateTimeRangeTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
     "DescribeAffectedAccountsForOrganizationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
     "EventAccountFilterTypeDef",
     "OrganizationAffectedEntitiesErrorItemTypeDef",
     "DescribeEntityAggregatesRequestRequestTypeDef",
     "EntityAggregateTypeDef",
     "EventAggregateTypeDef",
     "OrganizationEventDetailsErrorItemTypeDef",
     "DescribeEventDetailsRequestRequestTypeDef",
     "EventDetailsErrorItemTypeDef",
     "EventTypeFilterTypeDef",
     "EventTypeTypeDef",
     "OrganizationEventTypeDef",
     "EventTypeDef",
+    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventDescriptionTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "DescribeAffectedEntitiesResponseTypeDef",
     "EntityFilterTypeDef",
     "EventFilterTypeDef",
     "OrganizationEventFilterTypeDef",
-    "DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
-    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
-    "DescribeAffectedEntitiesResponseTypeDef",
-    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "DescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef",
     "DescribeAffectedEntitiesForOrganizationRequestRequestTypeDef",
     "DescribeEventDetailsForOrganizationRequestRequestTypeDef",
     "DescribeAffectedEntitiesForOrganizationResponseTypeDef",
     "DescribeEntityAggregatesResponseTypeDef",
     "DescribeEventAggregatesResponseTypeDef",
     "DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef",
@@ -104,24 +103,34 @@
     {
         "from": Union[datetime, str],
         "to": Union[datetime, str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "eventArn": str,
+    },
+)
+_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef(
+    _RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
+    _OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeAffectedAccountsForOrganizationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAffectedAccountsForOrganizationRequestRequestTypeDef",
     {
         "eventArn": str,
     },
 )
 _OptionalDescribeAffectedAccountsForOrganizationRequestRequestTypeDef = TypedDict(
@@ -129,30 +138,27 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class DescribeAffectedAccountsForOrganizationRequestRequestTypeDef(
     _RequiredDescribeAffectedAccountsForOrganizationRequestRequestTypeDef,
     _OptionalDescribeAffectedAccountsForOrganizationRequestRequestTypeDef,
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DescribeAffectedAccountsForOrganizationResponseTypeDef = TypedDict(
+    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "affectedAccounts": List[str],
+        "eventScopeCode": eventScopeCodeType,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEventAccountFilterTypeDef = TypedDict(
     "_RequiredEventAccountFilterTypeDef",
     {
         "eventArn": str,
@@ -162,21 +168,19 @@
     "_OptionalEventAccountFilterTypeDef",
     {
         "awsAccountId": str,
     },
     total=False,
 )
 
-
 class EventAccountFilterTypeDef(
     _RequiredEventAccountFilterTypeDef, _OptionalEventAccountFilterTypeDef
 ):
     pass
 
-
 OrganizationAffectedEntitiesErrorItemTypeDef = TypedDict(
     "OrganizationAffectedEntitiesErrorItemTypeDef",
     {
         "awsAccountId": str,
         "eventArn": str,
         "errorName": str,
         "errorMessage": str,
@@ -231,22 +235,20 @@
     "_OptionalDescribeEventDetailsRequestRequestTypeDef",
     {
         "locale": str,
     },
     total=False,
 )
 
-
 class DescribeEventDetailsRequestRequestTypeDef(
     _RequiredDescribeEventDetailsRequestRequestTypeDef,
     _OptionalDescribeEventDetailsRequestRequestTypeDef,
 ):
     pass
 
-
 EventDetailsErrorItemTypeDef = TypedDict(
     "EventDetailsErrorItemTypeDef",
     {
         "eventArn": str,
         "errorName": str,
         "errorMessage": str,
     },
@@ -304,22 +306,67 @@
         "lastUpdatedTime": datetime,
         "statusCode": eventStatusCodeType,
         "eventScopeCode": eventScopeCodeType,
     },
     total=False,
 )
 
+DescribeHealthServiceStatusForOrganizationResponseTypeDef = TypedDict(
+    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
+    {
+        "healthServiceAccessStatusForOrganization": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventDescriptionTypeDef = TypedDict(
     "EventDescriptionTypeDef",
     {
         "latestDescription": str,
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
+DescribeAffectedEntitiesResponseTypeDef = TypedDict(
+    "DescribeAffectedEntitiesResponseTypeDef",
+    {
+        "entities": List[AffectedEntityTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEntityFilterTypeDef = TypedDict(
     "_RequiredEntityFilterTypeDef",
     {
         "eventArns": Sequence[str],
     },
 )
 _OptionalEntityFilterTypeDef = TypedDict(
@@ -330,19 +377,17 @@
         "lastUpdatedTimes": Sequence[DateTimeRangeTypeDef],
         "tags": Sequence[Mapping[str, str]],
         "statusCodes": Sequence[entityStatusCodeType],
     },
     total=False,
 )
 
-
 class EntityFilterTypeDef(_RequiredEntityFilterTypeDef, _OptionalEntityFilterTypeDef):
     pass
 
-
 EventFilterTypeDef = TypedDict(
     "EventFilterTypeDef",
     {
         "eventArns": Sequence[str],
         "eventTypeCodes": Sequence[str],
         "services": Sequence[str],
         "regions": Sequence[str],
@@ -373,93 +418,35 @@
         "entityValues": Sequence[str],
         "eventTypeCategories": Sequence[eventTypeCategoryType],
         "eventStatusCodes": Sequence[eventStatusCodeType],
     },
     total=False,
 )
 
-_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
-    {
-        "eventArn": str,
-    },
-)
-_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef(
-    _RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
-    _OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
-):
-    pass
-
-
-DescribeAffectedAccountsForOrganizationResponseTypeDef = TypedDict(
-    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
-    {
-        "affectedAccounts": List[str],
-        "eventScopeCode": eventScopeCodeType,
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAffectedEntitiesResponseTypeDef = TypedDict(
-    "DescribeAffectedEntitiesResponseTypeDef",
-    {
-        "entities": List[AffectedEntityTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeHealthServiceStatusForOrganizationResponseTypeDef = TypedDict(
-    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
-    {
-        "healthServiceAccessStatusForOrganization": str,
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
 _RequiredDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef = TypedDict(
     "_RequiredDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef",
     {
         "organizationEntityFilters": Sequence[EventAccountFilterTypeDef],
     },
 )
 _OptionalDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef = TypedDict(
     "_OptionalDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef",
     {
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class DescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef(
     _RequiredDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef,
     _OptionalDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef,
 ):
     pass
 
-
 _RequiredDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef",
     {
         "organizationEntityFilters": Sequence[EventAccountFilterTypeDef],
     },
 )
 _OptionalDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef = TypedDict(
@@ -468,77 +455,73 @@
         "locale": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class DescribeAffectedEntitiesForOrganizationRequestRequestTypeDef(
     _RequiredDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef,
     _OptionalDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDescribeEventDetailsForOrganizationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEventDetailsForOrganizationRequestRequestTypeDef",
     {
         "organizationEventDetailFilters": Sequence[EventAccountFilterTypeDef],
     },
 )
 _OptionalDescribeEventDetailsForOrganizationRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeEventDetailsForOrganizationRequestRequestTypeDef",
     {
         "locale": str,
     },
     total=False,
 )
 
-
 class DescribeEventDetailsForOrganizationRequestRequestTypeDef(
     _RequiredDescribeEventDetailsForOrganizationRequestRequestTypeDef,
     _OptionalDescribeEventDetailsForOrganizationRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeAffectedEntitiesForOrganizationResponseTypeDef = TypedDict(
     "DescribeAffectedEntitiesForOrganizationResponseTypeDef",
     {
         "entities": List[AffectedEntityTypeDef],
         "failedSet": List[OrganizationAffectedEntitiesErrorItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntityAggregatesResponseTypeDef = TypedDict(
     "DescribeEntityAggregatesResponseTypeDef",
     {
         "entityAggregates": List[EntityAggregateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventAggregatesResponseTypeDef = TypedDict(
     "DescribeEventAggregatesResponseTypeDef",
     {
         "eventAggregates": List[EventAggregateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef = TypedDict(
     "DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef",
     {
         "filter": EventTypeFilterTypeDef,
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEventTypesRequestRequestTypeDef = TypedDict(
     "DescribeEventTypesRequestRequestTypeDef",
     {
@@ -551,33 +534,33 @@
 )
 
 DescribeEventTypesResponseTypeDef = TypedDict(
     "DescribeEventTypesResponseTypeDef",
     {
         "eventTypes": List[EventTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsForOrganizationResponseTypeDef = TypedDict(
     "DescribeEventsForOrganizationResponseTypeDef",
     {
         "events": List[OrganizationEventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "events": List[EventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventDetailsTypeDef = TypedDict(
     "EventDetailsTypeDef",
     {
         "event": EventTypeDef,
@@ -604,27 +587,25 @@
         "filter": EntityFilterTypeDef,
     },
 )
 _OptionalDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef = TypedDict(
     "_OptionalDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef",
     {
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class DescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef(
     _RequiredDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef,
     _OptionalDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef,
 ):
     pass
 
-
 _RequiredDescribeAffectedEntitiesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAffectedEntitiesRequestRequestTypeDef",
     {
         "filter": EntityFilterTypeDef,
     },
 )
 _OptionalDescribeAffectedEntitiesRequestRequestTypeDef = TypedDict(
@@ -633,45 +614,41 @@
         "locale": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class DescribeAffectedEntitiesRequestRequestTypeDef(
     _RequiredDescribeAffectedEntitiesRequestRequestTypeDef,
     _OptionalDescribeAffectedEntitiesRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef = TypedDict(
     "_RequiredDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef",
     {
         "aggregateField": Literal["eventTypeCategory"],
     },
 )
 _OptionalDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef = TypedDict(
     "_OptionalDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef",
     {
         "filter": EventFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-
 class DescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef(
     _RequiredDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef,
     _OptionalDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef,
 ):
     pass
 
-
 _RequiredDescribeEventAggregatesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEventAggregatesRequestRequestTypeDef",
     {
         "aggregateField": Literal["eventTypeCategory"],
     },
 )
 _OptionalDescribeEventAggregatesRequestRequestTypeDef = TypedDict(
@@ -680,28 +657,26 @@
         "filter": EventFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class DescribeEventAggregatesRequestRequestTypeDef(
     _RequiredDescribeEventAggregatesRequestRequestTypeDef,
     _OptionalDescribeEventAggregatesRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
     "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     {
         "filter": EventFilterTypeDef,
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEventsRequestRequestTypeDef = TypedDict(
     "DescribeEventsRequestRequestTypeDef",
     {
@@ -714,15 +689,15 @@
 )
 
 DescribeEventsForOrganizationRequestDescribeEventsForOrganizationPaginateTypeDef = TypedDict(
     "DescribeEventsForOrganizationRequestDescribeEventsForOrganizationPaginateTypeDef",
     {
         "filter": OrganizationEventFilterTypeDef,
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEventsForOrganizationRequestRequestTypeDef = TypedDict(
     "DescribeEventsForOrganizationRequestRequestTypeDef",
     {
@@ -735,19 +710,19 @@
 )
 
 DescribeEventDetailsResponseTypeDef = TypedDict(
     "DescribeEventDetailsResponseTypeDef",
     {
         "successfulSet": List[EventDetailsTypeDef],
         "failedSet": List[EventDetailsErrorItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventDetailsForOrganizationResponseTypeDef = TypedDict(
     "DescribeEventDetailsForOrganizationResponseTypeDef",
     {
         "successfulSet": List[OrganizationEventDetailsTypeDef],
         "failedSet": List[OrganizationEventDetailsErrorItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health/type_defs.pyi` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -27,41 +27,42 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AffectedEntityTypeDef",
     "DateTimeRangeTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
     "DescribeAffectedAccountsForOrganizationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
     "EventAccountFilterTypeDef",
     "OrganizationAffectedEntitiesErrorItemTypeDef",
     "DescribeEntityAggregatesRequestRequestTypeDef",
     "EntityAggregateTypeDef",
     "EventAggregateTypeDef",
     "OrganizationEventDetailsErrorItemTypeDef",
     "DescribeEventDetailsRequestRequestTypeDef",
     "EventDetailsErrorItemTypeDef",
     "EventTypeFilterTypeDef",
     "EventTypeTypeDef",
     "OrganizationEventTypeDef",
     "EventTypeDef",
+    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventDescriptionTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "DescribeAffectedEntitiesResponseTypeDef",
     "EntityFilterTypeDef",
     "EventFilterTypeDef",
     "OrganizationEventFilterTypeDef",
-    "DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
-    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
-    "DescribeAffectedEntitiesResponseTypeDef",
-    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "DescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef",
     "DescribeAffectedEntitiesForOrganizationRequestRequestTypeDef",
     "DescribeEventDetailsForOrganizationRequestRequestTypeDef",
     "DescribeAffectedEntitiesForOrganizationResponseTypeDef",
     "DescribeEntityAggregatesResponseTypeDef",
     "DescribeEventAggregatesResponseTypeDef",
     "DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef",
@@ -103,24 +104,36 @@
     {
         "from": Union[datetime, str],
         "to": Union[datetime, str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "eventArn": str,
+    },
+)
+_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef(
+    _RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
+    _OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeAffectedAccountsForOrganizationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAffectedAccountsForOrganizationRequestRequestTypeDef",
     {
         "eventArn": str,
     },
 )
 _OptionalDescribeAffectedAccountsForOrganizationRequestRequestTypeDef = TypedDict(
@@ -128,28 +141,29 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class DescribeAffectedAccountsForOrganizationRequestRequestTypeDef(
     _RequiredDescribeAffectedAccountsForOrganizationRequestRequestTypeDef,
     _OptionalDescribeAffectedAccountsForOrganizationRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+DescribeAffectedAccountsForOrganizationResponseTypeDef = TypedDict(
+    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "affectedAccounts": List[str],
+        "eventScopeCode": eventScopeCodeType,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEventAccountFilterTypeDef = TypedDict(
     "_RequiredEventAccountFilterTypeDef",
     {
         "eventArn": str,
@@ -159,19 +173,21 @@
     "_OptionalEventAccountFilterTypeDef",
     {
         "awsAccountId": str,
     },
     total=False,
 )
 
+
 class EventAccountFilterTypeDef(
     _RequiredEventAccountFilterTypeDef, _OptionalEventAccountFilterTypeDef
 ):
     pass
 
+
 OrganizationAffectedEntitiesErrorItemTypeDef = TypedDict(
     "OrganizationAffectedEntitiesErrorItemTypeDef",
     {
         "awsAccountId": str,
         "eventArn": str,
         "errorName": str,
         "errorMessage": str,
@@ -226,20 +242,22 @@
     "_OptionalDescribeEventDetailsRequestRequestTypeDef",
     {
         "locale": str,
     },
     total=False,
 )
 
+
 class DescribeEventDetailsRequestRequestTypeDef(
     _RequiredDescribeEventDetailsRequestRequestTypeDef,
     _OptionalDescribeEventDetailsRequestRequestTypeDef,
 ):
     pass
 
+
 EventDetailsErrorItemTypeDef = TypedDict(
     "EventDetailsErrorItemTypeDef",
     {
         "eventArn": str,
         "errorName": str,
         "errorMessage": str,
     },
@@ -297,22 +315,67 @@
         "lastUpdatedTime": datetime,
         "statusCode": eventStatusCodeType,
         "eventScopeCode": eventScopeCodeType,
     },
     total=False,
 )
 
+DescribeHealthServiceStatusForOrganizationResponseTypeDef = TypedDict(
+    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
+    {
+        "healthServiceAccessStatusForOrganization": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventDescriptionTypeDef = TypedDict(
     "EventDescriptionTypeDef",
     {
         "latestDescription": str,
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
+DescribeAffectedEntitiesResponseTypeDef = TypedDict(
+    "DescribeAffectedEntitiesResponseTypeDef",
+    {
+        "entities": List[AffectedEntityTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEntityFilterTypeDef = TypedDict(
     "_RequiredEntityFilterTypeDef",
     {
         "eventArns": Sequence[str],
     },
 )
 _OptionalEntityFilterTypeDef = TypedDict(
@@ -323,17 +386,19 @@
         "lastUpdatedTimes": Sequence[DateTimeRangeTypeDef],
         "tags": Sequence[Mapping[str, str]],
         "statusCodes": Sequence[entityStatusCodeType],
     },
     total=False,
 )
 
+
 class EntityFilterTypeDef(_RequiredEntityFilterTypeDef, _OptionalEntityFilterTypeDef):
     pass
 
+
 EventFilterTypeDef = TypedDict(
     "EventFilterTypeDef",
     {
         "eventArns": Sequence[str],
         "eventTypeCodes": Sequence[str],
         "services": Sequence[str],
         "regions": Sequence[str],
@@ -364,89 +429,37 @@
         "entityValues": Sequence[str],
         "eventTypeCategories": Sequence[eventTypeCategoryType],
         "eventStatusCodes": Sequence[eventStatusCodeType],
     },
     total=False,
 )
 
-_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
-    {
-        "eventArn": str,
-    },
-)
-_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef(
-    _RequiredDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
-    _OptionalDescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
-):
-    pass
-
-DescribeAffectedAccountsForOrganizationResponseTypeDef = TypedDict(
-    "DescribeAffectedAccountsForOrganizationResponseTypeDef",
-    {
-        "affectedAccounts": List[str],
-        "eventScopeCode": eventScopeCodeType,
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAffectedEntitiesResponseTypeDef = TypedDict(
-    "DescribeAffectedEntitiesResponseTypeDef",
-    {
-        "entities": List[AffectedEntityTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeHealthServiceStatusForOrganizationResponseTypeDef = TypedDict(
-    "DescribeHealthServiceStatusForOrganizationResponseTypeDef",
-    {
-        "healthServiceAccessStatusForOrganization": str,
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
 _RequiredDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef = TypedDict(
     "_RequiredDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef",
     {
         "organizationEntityFilters": Sequence[EventAccountFilterTypeDef],
     },
 )
 _OptionalDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef = TypedDict(
     "_OptionalDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef",
     {
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class DescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef(
     _RequiredDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef,
     _OptionalDescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef,
 ):
     pass
 
+
 _RequiredDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef",
     {
         "organizationEntityFilters": Sequence[EventAccountFilterTypeDef],
     },
 )
 _OptionalDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef = TypedDict(
@@ -455,73 +468,77 @@
         "locale": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class DescribeAffectedEntitiesForOrganizationRequestRequestTypeDef(
     _RequiredDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef,
     _OptionalDescribeAffectedEntitiesForOrganizationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDescribeEventDetailsForOrganizationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEventDetailsForOrganizationRequestRequestTypeDef",
     {
         "organizationEventDetailFilters": Sequence[EventAccountFilterTypeDef],
     },
 )
 _OptionalDescribeEventDetailsForOrganizationRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeEventDetailsForOrganizationRequestRequestTypeDef",
     {
         "locale": str,
     },
     total=False,
 )
 
+
 class DescribeEventDetailsForOrganizationRequestRequestTypeDef(
     _RequiredDescribeEventDetailsForOrganizationRequestRequestTypeDef,
     _OptionalDescribeEventDetailsForOrganizationRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeAffectedEntitiesForOrganizationResponseTypeDef = TypedDict(
     "DescribeAffectedEntitiesForOrganizationResponseTypeDef",
     {
         "entities": List[AffectedEntityTypeDef],
         "failedSet": List[OrganizationAffectedEntitiesErrorItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntityAggregatesResponseTypeDef = TypedDict(
     "DescribeEntityAggregatesResponseTypeDef",
     {
         "entityAggregates": List[EntityAggregateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventAggregatesResponseTypeDef = TypedDict(
     "DescribeEventAggregatesResponseTypeDef",
     {
         "eventAggregates": List[EventAggregateTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef = TypedDict(
     "DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef",
     {
         "filter": EventTypeFilterTypeDef,
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEventTypesRequestRequestTypeDef = TypedDict(
     "DescribeEventTypesRequestRequestTypeDef",
     {
@@ -534,33 +551,33 @@
 )
 
 DescribeEventTypesResponseTypeDef = TypedDict(
     "DescribeEventTypesResponseTypeDef",
     {
         "eventTypes": List[EventTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsForOrganizationResponseTypeDef = TypedDict(
     "DescribeEventsForOrganizationResponseTypeDef",
     {
         "events": List[OrganizationEventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsResponseTypeDef = TypedDict(
     "DescribeEventsResponseTypeDef",
     {
         "events": List[EventTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventDetailsTypeDef = TypedDict(
     "EventDetailsTypeDef",
     {
         "event": EventTypeDef,
@@ -587,25 +604,27 @@
         "filter": EntityFilterTypeDef,
     },
 )
 _OptionalDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef = TypedDict(
     "_OptionalDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef",
     {
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class DescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef(
     _RequiredDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef,
     _OptionalDescribeAffectedEntitiesRequestDescribeAffectedEntitiesPaginateTypeDef,
 ):
     pass
 
+
 _RequiredDescribeAffectedEntitiesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAffectedEntitiesRequestRequestTypeDef",
     {
         "filter": EntityFilterTypeDef,
     },
 )
 _OptionalDescribeAffectedEntitiesRequestRequestTypeDef = TypedDict(
@@ -614,41 +633,45 @@
         "locale": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class DescribeAffectedEntitiesRequestRequestTypeDef(
     _RequiredDescribeAffectedEntitiesRequestRequestTypeDef,
     _OptionalDescribeAffectedEntitiesRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef = TypedDict(
     "_RequiredDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef",
     {
         "aggregateField": Literal["eventTypeCategory"],
     },
 )
 _OptionalDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef = TypedDict(
     "_OptionalDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef",
     {
         "filter": EventFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
 class DescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef(
     _RequiredDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef,
     _OptionalDescribeEventAggregatesRequestDescribeEventAggregatesPaginateTypeDef,
 ):
     pass
 
+
 _RequiredDescribeEventAggregatesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeEventAggregatesRequestRequestTypeDef",
     {
         "aggregateField": Literal["eventTypeCategory"],
     },
 )
 _OptionalDescribeEventAggregatesRequestRequestTypeDef = TypedDict(
@@ -657,26 +680,28 @@
         "filter": EventFilterTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class DescribeEventAggregatesRequestRequestTypeDef(
     _RequiredDescribeEventAggregatesRequestRequestTypeDef,
     _OptionalDescribeEventAggregatesRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeEventsRequestDescribeEventsPaginateTypeDef = TypedDict(
     "DescribeEventsRequestDescribeEventsPaginateTypeDef",
     {
         "filter": EventFilterTypeDef,
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEventsRequestRequestTypeDef = TypedDict(
     "DescribeEventsRequestRequestTypeDef",
     {
@@ -689,15 +714,15 @@
 )
 
 DescribeEventsForOrganizationRequestDescribeEventsForOrganizationPaginateTypeDef = TypedDict(
     "DescribeEventsForOrganizationRequestDescribeEventsForOrganizationPaginateTypeDef",
     {
         "filter": OrganizationEventFilterTypeDef,
         "locale": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEventsForOrganizationRequestRequestTypeDef = TypedDict(
     "DescribeEventsForOrganizationRequestRequestTypeDef",
     {
@@ -710,19 +735,19 @@
 )
 
 DescribeEventDetailsResponseTypeDef = TypedDict(
     "DescribeEventDetailsResponseTypeDef",
     {
         "successfulSet": List[EventDetailsTypeDef],
         "failedSet": List[EventDetailsErrorItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventDetailsForOrganizationResponseTypeDef = TypedDict(
     "DescribeEventDetailsForOrganizationResponseTypeDef",
     {
         "successfulSet": List[OrganizationEventDetailsTypeDef],
         "failedSet": List[OrganizationEventDetailsErrorItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/PKG-INFO` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-health
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Health 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Health 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-health"></a>
 
 # types-aiobotocore-health
 
 [![PyPI - types-aiobotocore-health](https://img.shields.io/pypi/v/types-aiobotocore-health.svg?color=blue)](https://pypi.org/project/types-aiobotocore-health)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-health.svg?color=blue)](https://pypi.org/project/types-aiobotocore-health)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-health?color=blue)](https://pypistats.org/packages/types-aiobotocore-health)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Health 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health)
+[aiobotocore.Health 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/health.html#Health)
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
 [types-aiobotocore-health docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_health/).
 
 See how it helps to find and fix potential bugs:
 
@@ -352,38 +352,38 @@
 `types_aiobotocore_health.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_health.type_defs import (
     AffectedEntityTypeDef,
     DateTimeRangeTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
     DescribeAffectedAccountsForOrganizationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeAffectedAccountsForOrganizationResponseTypeDef,
     EventAccountFilterTypeDef,
     OrganizationAffectedEntitiesErrorItemTypeDef,
     DescribeEntityAggregatesRequestRequestTypeDef,
     EntityAggregateTypeDef,
     EventAggregateTypeDef,
     OrganizationEventDetailsErrorItemTypeDef,
     DescribeEventDetailsRequestRequestTypeDef,
     EventDetailsErrorItemTypeDef,
     EventTypeFilterTypeDef,
     EventTypeTypeDef,
     OrganizationEventTypeDef,
     EventTypeDef,
+    DescribeHealthServiceStatusForOrganizationResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventDescriptionTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeAffectedEntitiesResponseTypeDef,
     EntityFilterTypeDef,
     EventFilterTypeDef,
     OrganizationEventFilterTypeDef,
-    DescribeAffectedAccountsForOrganizationRequestDescribeAffectedAccountsForOrganizationPaginateTypeDef,
-    DescribeAffectedAccountsForOrganizationResponseTypeDef,
-    DescribeAffectedEntitiesResponseTypeDef,
-    DescribeHealthServiceStatusForOrganizationResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     DescribeAffectedEntitiesForOrganizationRequestDescribeAffectedEntitiesForOrganizationPaginateTypeDef,
     DescribeAffectedEntitiesForOrganizationRequestRequestTypeDef,
     DescribeEventDetailsForOrganizationRequestRequestTypeDef,
     DescribeAffectedEntitiesForOrganizationResponseTypeDef,
     DescribeEntityAggregatesResponseTypeDef,
     DescribeEventAggregatesResponseTypeDef,
     DescribeEventTypesRequestDescribeEventTypesPaginateTypeDef,
@@ -413,43 +413,43 @@
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

### Comparing `types-aiobotocore-health-2.5.0.post1/types_aiobotocore_health.egg-info/SOURCES.txt` & `types-aiobotocore-health-2.5.1/types_aiobotocore_health.egg-info/SOURCES.txt`

 * *Files identical despite different names*

