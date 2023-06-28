# Comparing `tmp/types-aiobotocore-budgets-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-budgets-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-budgets-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:17 2023, max compression
+gzip compressed data, was "types-aiobotocore-budgets-2.5.1.tar", last modified: Wed Jun 28 01:43:10 2023, max compression
```

## Comparing `types-aiobotocore-budgets-2.5.0.post1.tar` & `types-aiobotocore-budgets-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.454998 types-aiobotocore-budgets-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18082 2023-03-11 12:26:17.454998 types-aiobotocore-budgets-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16511 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:17.454998 types-aiobotocore-budgets-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.454998 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/
--rw-r--r--   0 runner    (1001) docker     (123)     2791 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2790 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23641 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23601 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10448 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10446 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11583 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11572 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    31348 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    31299 2023-03-11 12:10:15.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:14.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.454998 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18082 2023-03-11 12:26:17.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-11 12:26:17.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:17.000000 types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.978103 types-aiobotocore-budgets-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18074 2023-06-28 01:43:10.974102 types-aiobotocore-budgets-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16509 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:10.978103 types-aiobotocore-budgets-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.974102 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/
+-rw-r--r--   0 runner    (1001) docker     (123)     2791 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2790 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23639 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23599 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10657 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10655 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11479 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11469 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    31392 2023-06-28 01:26:52.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31343 2023-06-28 01:26:52.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:51.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:10.974102 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18074 2023-06-28 01:43:10.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:43:10.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:10.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:10.000000 types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-budgets-2.5.0.post1/LICENSE` & `types-aiobotocore-budgets-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/PKG-INFO` & `types-aiobotocore-budgets-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-budgets
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Budgets 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Budgets 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-budgets"></a>
 
 # types-aiobotocore-budgets
 
 [![PyPI - types-aiobotocore-budgets](https://img.shields.io/pypi/v/types-aiobotocore-budgets.svg?color=blue)](https://pypi.org/project/types-aiobotocore-budgets)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-budgets.svg?color=blue)](https://pypi.org/project/types-aiobotocore-budgets)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-budgets?color=blue)](https://pypistats.org/packages/types-aiobotocore-budgets)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Budgets 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets)
+[aiobotocore.Budgets 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets)
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
 [types-aiobotocore-budgets docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/).
 
 See how it helps to find and fix potential bugs:
 
@@ -370,56 +370,56 @@
     ActionThresholdTypeDef,
     SubscriberTypeDef,
     HistoricalOptionsTypeDef,
     NotificationTypeDef,
     CostTypesTypeDef,
     SpendTypeDef,
     TimePeriodTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBudgetActionResponseTypeDef,
     IamActionDefinitionTypeDef,
     ScpActionDefinitionTypeDef,
     SsmActionDefinitionTypeDef,
     DeleteBudgetActionRequestRequestTypeDef,
     DeleteBudgetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     DescribeBudgetActionRequestRequestTypeDef,
+    DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
     DescribeBudgetActionsForAccountRequestRequestTypeDef,
+    DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
     DescribeBudgetActionsForBudgetRequestRequestTypeDef,
+    DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
     DescribeBudgetNotificationsForAccountRequestRequestTypeDef,
     DescribeBudgetRequestRequestTypeDef,
+    DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
     DescribeBudgetsRequestRequestTypeDef,
+    DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
     DescribeNotificationsForBudgetRequestRequestTypeDef,
     ExecuteBudgetActionRequestRequestTypeDef,
+    ExecuteBudgetActionResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeSubscribersForNotificationResponseTypeDef,
     AutoAdjustDataTypeDef,
     BudgetNotificationsForAccountTypeDef,
     CreateNotificationRequestRequestTypeDef,
     CreateSubscriberRequestRequestTypeDef,
     DeleteNotificationRequestRequestTypeDef,
     DeleteSubscriberRequestRequestTypeDef,
+    DescribeNotificationsForBudgetResponseTypeDef,
+    DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
     DescribeSubscribersForNotificationRequestRequestTypeDef,
     NotificationWithSubscribersTypeDef,
     UpdateNotificationRequestRequestTypeDef,
     UpdateSubscriberRequestRequestTypeDef,
     CalculatedSpendTypeDef,
     BudgetedAndActualAmountsTypeDef,
+    DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
     DescribeBudgetActionHistoriesRequestRequestTypeDef,
+    DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
     DescribeBudgetPerformanceHistoryRequestRequestTypeDef,
-    CreateBudgetActionResponseTypeDef,
-    DescribeNotificationsForBudgetResponseTypeDef,
-    DescribeSubscribersForNotificationResponseTypeDef,
-    ExecuteBudgetActionResponseTypeDef,
     DefinitionTypeDef,
-    DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
-    DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
-    DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
-    DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
-    DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
-    DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
-    DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
-    DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
     DescribeBudgetNotificationsForAccountResponseTypeDef,
     BudgetTypeDef,
     BudgetPerformanceHistoryTypeDef,
     ActionTypeDef,
     CreateBudgetActionRequestRequestTypeDef,
     UpdateBudgetActionRequestRequestTypeDef,
     CreateBudgetRequestRequestTypeDef,
@@ -445,43 +445,43 @@
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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/README.md` & `types-aiobotocore-budgets-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-budgets"></a>
 
 # types-aiobotocore-budgets
 
 [![PyPI - types-aiobotocore-budgets](https://img.shields.io/pypi/v/types-aiobotocore-budgets.svg?color=blue)](https://pypi.org/project/types-aiobotocore-budgets)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-budgets.svg?color=blue)](https://pypi.org/project/types-aiobotocore-budgets)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-budgets?color=blue)](https://pypistats.org/packages/types-aiobotocore-budgets)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Budgets 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets)
+[aiobotocore.Budgets 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets)
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
 [types-aiobotocore-budgets docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/).
 
 See how it helps to find and fix potential bugs:
 
@@ -337,56 +337,56 @@
     ActionThresholdTypeDef,
     SubscriberTypeDef,
     HistoricalOptionsTypeDef,
     NotificationTypeDef,
     CostTypesTypeDef,
     SpendTypeDef,
     TimePeriodTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBudgetActionResponseTypeDef,
     IamActionDefinitionTypeDef,
     ScpActionDefinitionTypeDef,
     SsmActionDefinitionTypeDef,
     DeleteBudgetActionRequestRequestTypeDef,
     DeleteBudgetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     DescribeBudgetActionRequestRequestTypeDef,
+    DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
     DescribeBudgetActionsForAccountRequestRequestTypeDef,
+    DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
     DescribeBudgetActionsForBudgetRequestRequestTypeDef,
+    DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
     DescribeBudgetNotificationsForAccountRequestRequestTypeDef,
     DescribeBudgetRequestRequestTypeDef,
+    DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
     DescribeBudgetsRequestRequestTypeDef,
+    DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
     DescribeNotificationsForBudgetRequestRequestTypeDef,
     ExecuteBudgetActionRequestRequestTypeDef,
+    ExecuteBudgetActionResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeSubscribersForNotificationResponseTypeDef,
     AutoAdjustDataTypeDef,
     BudgetNotificationsForAccountTypeDef,
     CreateNotificationRequestRequestTypeDef,
     CreateSubscriberRequestRequestTypeDef,
     DeleteNotificationRequestRequestTypeDef,
     DeleteSubscriberRequestRequestTypeDef,
+    DescribeNotificationsForBudgetResponseTypeDef,
+    DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
     DescribeSubscribersForNotificationRequestRequestTypeDef,
     NotificationWithSubscribersTypeDef,
     UpdateNotificationRequestRequestTypeDef,
     UpdateSubscriberRequestRequestTypeDef,
     CalculatedSpendTypeDef,
     BudgetedAndActualAmountsTypeDef,
+    DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
     DescribeBudgetActionHistoriesRequestRequestTypeDef,
+    DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
     DescribeBudgetPerformanceHistoryRequestRequestTypeDef,
-    CreateBudgetActionResponseTypeDef,
-    DescribeNotificationsForBudgetResponseTypeDef,
-    DescribeSubscribersForNotificationResponseTypeDef,
-    ExecuteBudgetActionResponseTypeDef,
     DefinitionTypeDef,
-    DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
-    DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
-    DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
-    DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
-    DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
-    DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
-    DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
-    DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
     DescribeBudgetNotificationsForAccountResponseTypeDef,
     BudgetTypeDef,
     BudgetPerformanceHistoryTypeDef,
     ActionTypeDef,
     CreateBudgetActionRequestRequestTypeDef,
     UpdateBudgetActionRequestRequestTypeDef,
     CreateBudgetRequestRequestTypeDef,
@@ -412,43 +412,43 @@
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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/setup.py` & `types-aiobotocore-budgets-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-budgets.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-budgets",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_budgets"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Budgets 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Budgets 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/"
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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/__init__.py` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/__init__.pyi` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/__main__.py` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Budgets 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Budgets 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets\nOther"
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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/client.py` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -299,15 +299,15 @@
         AccountId: str,
         BudgetName: str,
         TimePeriod: TimePeriodTypeDef = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> DescribeBudgetPerformanceHistoryResponseTypeDef:
         """
-        Describes the history for `DAILY` , `MONTHLY` , and `QUARTERLY` budgets.
+        Describes the history for `DAILY`, `MONTHLY`, and `QUARTERLY` budgets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Client.describe_budget_performance_history)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/client/#describe_budget_performance_history)
         """
 
     async def describe_budgets(
         self, *, AccountId: str, MaxResults: int = ..., NextToken: str = ...
```

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/client.pyi` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -278,15 +278,15 @@
         AccountId: str,
         BudgetName: str,
         TimePeriod: TimePeriodTypeDef = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> DescribeBudgetPerformanceHistoryResponseTypeDef:
         """
-        Describes the history for `DAILY` , `MONTHLY` , and `QUARTERLY` budgets.
+        Describes the history for `DAILY`, `MONTHLY`, and `QUARTERLY` budgets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Client.describe_budget_performance_history)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/client/#describe_budget_performance_history)
         """
     async def describe_budgets(
         self, *, AccountId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> DescribeBudgetsResponseTypeDef:
```

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/literals.py` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ActionStatusType",
     "ActionSubTypeType",
     "ActionTypeType",
     "ApprovalModelType",
     "AutoAdjustTypeType",
     "BudgetTypeType",
@@ -44,15 +43,14 @@
     "TimeUnitType",
     "BudgetsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
-
 ActionStatusType = Literal[
     "EXECUTION_FAILURE",
     "EXECUTION_IN_PROGRESS",
     "EXECUTION_SUCCESS",
     "PENDING",
     "RESET_FAILURE",
     "RESET_IN_PROGRESS",
@@ -154,14 +152,15 @@
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
@@ -240,14 +239,15 @@
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
@@ -258,14 +258,15 @@
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
@@ -301,14 +302,15 @@
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
@@ -327,16 +329,19 @@
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
@@ -420,15 +425,17 @@
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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/literals.pyi` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ActionStatusType",
     "ActionSubTypeType",
     "ActionTypeType",
     "ApprovalModelType",
     "AutoAdjustTypeType",
     "BudgetTypeType",
@@ -43,14 +44,15 @@
     "TimeUnitType",
     "BudgetsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
+
 ActionStatusType = Literal[
     "EXECUTION_FAILURE",
     "EXECUTION_IN_PROGRESS",
     "EXECUTION_SUCCESS",
     "PENDING",
     "RESET_FAILURE",
     "RESET_IN_PROGRESS",
@@ -152,14 +154,15 @@
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
@@ -238,14 +241,15 @@
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
@@ -256,14 +260,15 @@
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
@@ -299,14 +304,15 @@
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
@@ -325,16 +331,19 @@
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
@@ -418,15 +427,17 @@
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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/paginator.py` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         describe_budget_notifications_for_account_paginator: DescribeBudgetNotificationsForAccountPaginator = client.get_paginator("describe_budget_notifications_for_account")
         describe_budget_performance_history_paginator: DescribeBudgetPerformanceHistoryPaginator = client.get_paginator("describe_budget_performance_history")
         describe_budgets_paginator: DescribeBudgetsPaginator = client.get_paginator("describe_budgets")
         describe_notifications_for_budget_paginator: DescribeNotificationsForBudgetPaginator = client.get_paginator("describe_notifications_for_budget")
         describe_subscribers_for_notification_paginator: DescribeSubscribersForNotificationPaginator = client.get_paginator("describe_subscribers_for_notification")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBudgetActionHistoriesResponseTypeDef,
     DescribeBudgetActionsForAccountResponseTypeDef,
@@ -50,20 +49,14 @@
     DescribeNotificationsForBudgetResponseTypeDef,
     DescribeSubscribersForNotificationResponseTypeDef,
     NotificationTypeDef,
     PaginatorConfigTypeDef,
     TimePeriodTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeBudgetActionHistoriesPaginator",
     "DescribeBudgetActionsForAccountPaginator",
     "DescribeBudgetActionsForBudgetPaginator",
     "DescribeBudgetNotificationsForAccountPaginator",
     "DescribeBudgetPerformanceHistoryPaginator",
     "DescribeBudgetsPaginator",
@@ -91,60 +84,60 @@
     def paginate(
         self,
         *,
         AccountId: str,
         BudgetName: str,
         ActionId: str,
         TimePeriod: TimePeriodTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetActionHistoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionHistories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionhistoriespaginator)
         """
 
 
 class DescribeBudgetActionsForAccountPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForAccount)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforaccountpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetActionsForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforaccountpaginator)
         """
 
 
 class DescribeBudgetActionsForBudgetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForBudget)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforbudgetpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, BudgetName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, BudgetName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetActionsForBudgetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForBudget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforbudgetpaginator)
         """
 
 
 class DescribeBudgetNotificationsForAccountPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetNotificationsForAccount)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetnotificationsforaccountpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetNotificationsForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetNotificationsForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetnotificationsforaccountpaginator)
         """
 
 
@@ -156,45 +149,45 @@
 
     def paginate(
         self,
         *,
         AccountId: str,
         BudgetName: str,
         TimePeriod: TimePeriodTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetPerformanceHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetPerformanceHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetperformancehistorypaginator)
         """
 
 
 class DescribeBudgetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetspaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetspaginator)
         """
 
 
 class DescribeNotificationsForBudgetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeNotificationsForBudget)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describenotificationsforbudgetpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, BudgetName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, BudgetName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeNotificationsForBudgetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeNotificationsForBudget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describenotificationsforbudgetpaginator)
         """
 
 
@@ -206,13 +199,13 @@
 
     def paginate(
         self,
         *,
         AccountId: str,
         BudgetName: str,
         Notification: NotificationTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSubscribersForNotificationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeSubscribersForNotification.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describesubscribersfornotificationpaginator)
         """
```

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/paginator.pyi` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         describe_budget_notifications_for_account_paginator: DescribeBudgetNotificationsForAccountPaginator = client.get_paginator("describe_budget_notifications_for_account")
         describe_budget_performance_history_paginator: DescribeBudgetPerformanceHistoryPaginator = client.get_paginator("describe_budget_performance_history")
         describe_budgets_paginator: DescribeBudgetsPaginator = client.get_paginator("describe_budgets")
         describe_notifications_for_budget_paginator: DescribeNotificationsForBudgetPaginator = client.get_paginator("describe_notifications_for_budget")
         describe_subscribers_for_notification_paginator: DescribeSubscribersForNotificationPaginator = client.get_paginator("describe_subscribers_for_notification")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeBudgetActionHistoriesResponseTypeDef,
     DescribeBudgetActionsForAccountResponseTypeDef,
@@ -50,19 +49,14 @@
     DescribeNotificationsForBudgetResponseTypeDef,
     DescribeSubscribersForNotificationResponseTypeDef,
     NotificationTypeDef,
     PaginatorConfigTypeDef,
     TimePeriodTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeBudgetActionHistoriesPaginator",
     "DescribeBudgetActionsForAccountPaginator",
     "DescribeBudgetActionsForBudgetPaginator",
     "DescribeBudgetNotificationsForAccountPaginator",
     "DescribeBudgetPerformanceHistoryPaginator",
     "DescribeBudgetsPaginator",
@@ -87,57 +81,57 @@
     def paginate(
         self,
         *,
         AccountId: str,
         BudgetName: str,
         ActionId: str,
         TimePeriod: TimePeriodTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetActionHistoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionHistories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionhistoriespaginator)
         """
 
 class DescribeBudgetActionsForAccountPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForAccount)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforaccountpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetActionsForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforaccountpaginator)
         """
 
 class DescribeBudgetActionsForBudgetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForBudget)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforbudgetpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, BudgetName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, BudgetName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetActionsForBudgetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetActionsForBudget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetactionsforbudgetpaginator)
         """
 
 class DescribeBudgetNotificationsForAccountPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetNotificationsForAccount)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetnotificationsforaccountpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetNotificationsForAccountResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetNotificationsForAccount.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetnotificationsforaccountpaginator)
         """
 
 class DescribeBudgetPerformanceHistoryPaginator(AioPaginator):
@@ -148,43 +142,43 @@
 
     def paginate(
         self,
         *,
         AccountId: str,
         BudgetName: str,
         TimePeriod: TimePeriodTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetPerformanceHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgetPerformanceHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetperformancehistorypaginator)
         """
 
 class DescribeBudgetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetspaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBudgetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeBudgets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describebudgetspaginator)
         """
 
 class DescribeNotificationsForBudgetPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeNotificationsForBudget)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describenotificationsforbudgetpaginator)
     """
 
     def paginate(
-        self, *, AccountId: str, BudgetName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AccountId: str, BudgetName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeNotificationsForBudgetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeNotificationsForBudget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describenotificationsforbudgetpaginator)
         """
 
 class DescribeSubscribersForNotificationPaginator(AioPaginator):
@@ -195,13 +189,13 @@
 
     def paginate(
         self,
         *,
         AccountId: str,
         BudgetName: str,
         Notification: NotificationTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeSubscribersForNotificationResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets.Paginator.DescribeSubscribersForNotification.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/paginators/#describesubscribersfornotificationpaginator)
         """
```

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/type_defs.py` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -42,56 +42,56 @@
     "ActionThresholdTypeDef",
     "SubscriberTypeDef",
     "HistoricalOptionsTypeDef",
     "NotificationTypeDef",
     "CostTypesTypeDef",
     "SpendTypeDef",
     "TimePeriodTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBudgetActionResponseTypeDef",
     "IamActionDefinitionTypeDef",
     "ScpActionDefinitionTypeDef",
     "SsmActionDefinitionTypeDef",
     "DeleteBudgetActionRequestRequestTypeDef",
     "DeleteBudgetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeBudgetActionRequestRequestTypeDef",
+    "DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
     "DescribeBudgetActionsForAccountRequestRequestTypeDef",
+    "DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
     "DescribeBudgetActionsForBudgetRequestRequestTypeDef",
+    "DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
     "DescribeBudgetNotificationsForAccountRequestRequestTypeDef",
     "DescribeBudgetRequestRequestTypeDef",
+    "DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
     "DescribeBudgetsRequestRequestTypeDef",
+    "DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
     "DescribeNotificationsForBudgetRequestRequestTypeDef",
     "ExecuteBudgetActionRequestRequestTypeDef",
+    "ExecuteBudgetActionResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "DescribeSubscribersForNotificationResponseTypeDef",
     "AutoAdjustDataTypeDef",
     "BudgetNotificationsForAccountTypeDef",
     "CreateNotificationRequestRequestTypeDef",
     "CreateSubscriberRequestRequestTypeDef",
     "DeleteNotificationRequestRequestTypeDef",
     "DeleteSubscriberRequestRequestTypeDef",
+    "DescribeNotificationsForBudgetResponseTypeDef",
+    "DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
     "DescribeSubscribersForNotificationRequestRequestTypeDef",
     "NotificationWithSubscribersTypeDef",
     "UpdateNotificationRequestRequestTypeDef",
     "UpdateSubscriberRequestRequestTypeDef",
     "CalculatedSpendTypeDef",
     "BudgetedAndActualAmountsTypeDef",
+    "DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
     "DescribeBudgetActionHistoriesRequestRequestTypeDef",
+    "DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
     "DescribeBudgetPerformanceHistoryRequestRequestTypeDef",
-    "CreateBudgetActionResponseTypeDef",
-    "DescribeNotificationsForBudgetResponseTypeDef",
-    "DescribeSubscribersForNotificationResponseTypeDef",
-    "ExecuteBudgetActionResponseTypeDef",
     "DefinitionTypeDef",
-    "DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
-    "DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
-    "DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
-    "DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
-    "DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
-    "DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
-    "DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
-    "DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
     "DescribeBudgetNotificationsForAccountResponseTypeDef",
     "BudgetTypeDef",
     "BudgetPerformanceHistoryTypeDef",
     "ActionTypeDef",
     "CreateBudgetActionRequestRequestTypeDef",
     "UpdateBudgetActionRequestRequestTypeDef",
     "CreateBudgetRequestRequestTypeDef",
@@ -199,22 +199,21 @@
     {
         "Start": Union[datetime, str],
         "End": Union[datetime, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBudgetActionResponseTypeDef = TypedDict(
+    "CreateBudgetActionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AccountId": str,
+        "BudgetName": str,
+        "ActionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIamActionDefinitionTypeDef = TypedDict(
     "_RequiredIamActionDefinitionTypeDef",
     {
         "PolicyArn": str,
@@ -267,33 +266,45 @@
     "DeleteBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 DescribeBudgetActionRequestRequestTypeDef = TypedDict(
     "DescribeBudgetActionRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "ActionId": str,
     },
 )
 
+_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef(
+    _RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
+    _OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeBudgetActionsForAccountRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetActionsForAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalDescribeBudgetActionsForAccountRequestRequestTypeDef = TypedDict(
@@ -309,14 +320,37 @@
 class DescribeBudgetActionsForAccountRequestRequestTypeDef(
     _RequiredDescribeBudgetActionsForAccountRequestRequestTypeDef,
     _OptionalDescribeBudgetActionsForAccountRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+    },
+)
+_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef(
+    _RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
+    _OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeBudgetActionsForBudgetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetActionsForBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
@@ -333,14 +367,36 @@
 class DescribeBudgetActionsForBudgetRequestRequestTypeDef(
     _RequiredDescribeBudgetActionsForBudgetRequestRequestTypeDef,
     _OptionalDescribeBudgetActionsForBudgetRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef(
+    _RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
+    _OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeBudgetNotificationsForAccountRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetNotificationsForAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalDescribeBudgetNotificationsForAccountRequestRequestTypeDef = TypedDict(
@@ -364,14 +420,36 @@
     "DescribeBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
 
+_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef(
+    _RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
+    _OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeBudgetsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetsRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalDescribeBudgetsRequestRequestTypeDef = TypedDict(
@@ -386,14 +464,37 @@
 
 class DescribeBudgetsRequestRequestTypeDef(
     _RequiredDescribeBudgetsRequestRequestTypeDef, _OptionalDescribeBudgetsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+    },
+)
+_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef(
+    _RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
+    _OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeNotificationsForBudgetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeNotificationsForBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
@@ -420,14 +521,55 @@
         "AccountId": str,
         "BudgetName": str,
         "ActionId": str,
         "ExecutionType": ExecutionTypeType,
     },
 )
 
+ExecuteBudgetActionResponseTypeDef = TypedDict(
+    "ExecuteBudgetActionResponseTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+        "ActionId": str,
+        "ExecutionType": ExecutionTypeType,
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
+DescribeSubscribersForNotificationResponseTypeDef = TypedDict(
+    "DescribeSubscribersForNotificationResponseTypeDef",
+    {
+        "Subscribers": List[SubscriberTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAutoAdjustDataTypeDef = TypedDict(
     "_RequiredAutoAdjustDataTypeDef",
     {
         "AutoAdjustType": AutoAdjustTypeType,
     },
 )
 _OptionalAutoAdjustDataTypeDef = TypedDict(
@@ -488,14 +630,47 @@
         "AccountId": str,
         "BudgetName": str,
         "Notification": NotificationTypeDef,
         "Subscriber": SubscriberTypeDef,
     },
 )
 
+DescribeNotificationsForBudgetResponseTypeDef = TypedDict(
+    "DescribeNotificationsForBudgetResponseTypeDef",
+    {
+        "Notifications": List[NotificationTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+        "Notification": NotificationTypeDef,
+    },
+)
+_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef(
+    _RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
+    _OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeSubscribersForNotificationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSubscribersForNotificationRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "Notification": NotificationTypeDef,
     },
@@ -571,114 +746,14 @@
         "BudgetedAmount": SpendTypeDef,
         "ActualAmount": SpendTypeDef,
         "TimePeriod": TimePeriodTypeDef,
     },
     total=False,
 )
 
-_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
-    "_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "ActionId": str,
-    },
-)
-_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
-    "_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef",
-    {
-        "TimePeriod": TimePeriodTypeDef,
-        "MaxResults": int,
-        "NextToken": str,
-    },
-    total=False,
-)
-
-
-class DescribeBudgetActionHistoriesRequestRequestTypeDef(
-    _RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef,
-    _OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef,
-):
-    pass
-
-
-_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
-    "_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-    },
-)
-_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
-    "_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
-    {
-        "TimePeriod": TimePeriodTypeDef,
-        "MaxResults": int,
-        "NextToken": str,
-    },
-    total=False,
-)
-
-
-class DescribeBudgetPerformanceHistoryRequestRequestTypeDef(
-    _RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
-    _OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
-):
-    pass
-
-
-CreateBudgetActionResponseTypeDef = TypedDict(
-    "CreateBudgetActionResponseTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "ActionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeNotificationsForBudgetResponseTypeDef = TypedDict(
-    "DescribeNotificationsForBudgetResponseTypeDef",
-    {
-        "Notifications": List[NotificationTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeSubscribersForNotificationResponseTypeDef = TypedDict(
-    "DescribeSubscribersForNotificationResponseTypeDef",
-    {
-        "Subscribers": List[SubscriberTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExecuteBudgetActionResponseTypeDef = TypedDict(
-    "ExecuteBudgetActionResponseTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "ActionId": str,
-        "ExecutionType": ExecutionTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DefinitionTypeDef = TypedDict(
-    "DefinitionTypeDef",
-    {
-        "IamActionDefinition": IamActionDefinitionTypeDef,
-        "ScpActionDefinition": ScpActionDefinitionTypeDef,
-        "SsmActionDefinition": SsmActionDefinitionTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef = (
     TypedDict(
         "_RequiredDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
         {
             "AccountId": str,
             "BudgetName": str,
             "ActionId": str,
@@ -686,91 +761,50 @@
     )
 )
 _OptionalDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef = (
     TypedDict(
         "_OptionalDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
         {
             "TimePeriod": TimePeriodTypeDef,
-            "PaginationConfig": PaginatorConfigTypeDef,
+            "PaginationConfig": "PaginatorConfigTypeDef",
         },
         total=False,
     )
 )
 
 
 class DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef(
     _RequiredDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
     _OptionalDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
 ):
     pass
 
 
-_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef(
-    _RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
-    _OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
+_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
+        "ActionId": str,
     },
 )
-_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef(
-    _RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
-    _OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
+_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "TimePeriod": TimePeriodTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
     },
     total=False,
 )
 
 
-class DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef(
-    _RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
-    _OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
+class DescribeBudgetActionHistoriesRequestRequestTypeDef(
+    _RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef,
+    _OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef,
 ):
     pass
 
 
 _RequiredDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef = TypedDict(
     "_RequiredDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
     {
@@ -778,102 +812,68 @@
         "BudgetName": str,
     },
 )
 _OptionalDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef = TypedDict(
     "_OptionalDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
     {
         "TimePeriod": TimePeriodTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef(
     _RequiredDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
     _OptionalDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
 ):
     pass
 
 
-_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef(
-    _RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
-    _OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
-_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "TimePeriod": TimePeriodTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
     },
     total=False,
 )
 
 
-class DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef(
-    _RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
-    _OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
+class DescribeBudgetPerformanceHistoryRequestRequestTypeDef(
+    _RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
+    _OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "Notification": NotificationTypeDef,
-    },
-)
-_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
+DefinitionTypeDef = TypedDict(
+    "DefinitionTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "IamActionDefinition": IamActionDefinitionTypeDef,
+        "ScpActionDefinition": ScpActionDefinitionTypeDef,
+        "SsmActionDefinition": SsmActionDefinitionTypeDef,
     },
     total=False,
 )
 
-
-class DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef(
-    _RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
-    _OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
-):
-    pass
-
-
 DescribeBudgetNotificationsForAccountResponseTypeDef = TypedDict(
     "DescribeBudgetNotificationsForAccountResponseTypeDef",
     {
         "BudgetNotificationsForAccount": List[BudgetNotificationsForAccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBudgetTypeDef = TypedDict(
     "_RequiredBudgetTypeDef",
     {
         "BudgetName": str,
@@ -996,24 +996,24 @@
     pass
 
 
 DescribeBudgetResponseTypeDef = TypedDict(
     "DescribeBudgetResponseTypeDef",
     {
         "Budget": BudgetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetsResponseTypeDef = TypedDict(
     "DescribeBudgetsResponseTypeDef",
     {
         "Budgets": List[BudgetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBudgetRequestRequestTypeDef = TypedDict(
     "UpdateBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -1022,15 +1022,15 @@
 )
 
 DescribeBudgetPerformanceHistoryResponseTypeDef = TypedDict(
     "DescribeBudgetPerformanceHistoryResponseTypeDef",
     {
         "BudgetPerformanceHistory": BudgetPerformanceHistoryTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionHistoryDetailsTypeDef = TypedDict(
     "ActionHistoryDetailsTypeDef",
     {
         "Message": str,
@@ -1040,54 +1040,54 @@
 
 DeleteBudgetActionResponseTypeDef = TypedDict(
     "DeleteBudgetActionResponseTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "Action": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetActionResponseTypeDef = TypedDict(
     "DescribeBudgetActionResponseTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "Action": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetActionsForAccountResponseTypeDef = TypedDict(
     "DescribeBudgetActionsForAccountResponseTypeDef",
     {
         "Actions": List[ActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetActionsForBudgetResponseTypeDef = TypedDict(
     "DescribeBudgetActionsForBudgetResponseTypeDef",
     {
         "Actions": List[ActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBudgetActionResponseTypeDef = TypedDict(
     "UpdateBudgetActionResponseTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "OldAction": ActionTypeDef,
         "NewAction": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionHistoryTypeDef = TypedDict(
     "ActionHistoryTypeDef",
     {
         "Timestamp": datetime,
@@ -1098,10 +1098,10 @@
 )
 
 DescribeBudgetActionHistoriesResponseTypeDef = TypedDict(
     "DescribeBudgetActionHistoriesResponseTypeDef",
     {
         "ActionHistories": List[ActionHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets/type_defs.pyi` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets/type_defs.pyi`

 * *Files 14% similar despite different names*

```diff
@@ -41,56 +41,56 @@
     "ActionThresholdTypeDef",
     "SubscriberTypeDef",
     "HistoricalOptionsTypeDef",
     "NotificationTypeDef",
     "CostTypesTypeDef",
     "SpendTypeDef",
     "TimePeriodTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBudgetActionResponseTypeDef",
     "IamActionDefinitionTypeDef",
     "ScpActionDefinitionTypeDef",
     "SsmActionDefinitionTypeDef",
     "DeleteBudgetActionRequestRequestTypeDef",
     "DeleteBudgetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeBudgetActionRequestRequestTypeDef",
+    "DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
     "DescribeBudgetActionsForAccountRequestRequestTypeDef",
+    "DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
     "DescribeBudgetActionsForBudgetRequestRequestTypeDef",
+    "DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
     "DescribeBudgetNotificationsForAccountRequestRequestTypeDef",
     "DescribeBudgetRequestRequestTypeDef",
+    "DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
     "DescribeBudgetsRequestRequestTypeDef",
+    "DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
     "DescribeNotificationsForBudgetRequestRequestTypeDef",
     "ExecuteBudgetActionRequestRequestTypeDef",
+    "ExecuteBudgetActionResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "DescribeSubscribersForNotificationResponseTypeDef",
     "AutoAdjustDataTypeDef",
     "BudgetNotificationsForAccountTypeDef",
     "CreateNotificationRequestRequestTypeDef",
     "CreateSubscriberRequestRequestTypeDef",
     "DeleteNotificationRequestRequestTypeDef",
     "DeleteSubscriberRequestRequestTypeDef",
+    "DescribeNotificationsForBudgetResponseTypeDef",
+    "DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
     "DescribeSubscribersForNotificationRequestRequestTypeDef",
     "NotificationWithSubscribersTypeDef",
     "UpdateNotificationRequestRequestTypeDef",
     "UpdateSubscriberRequestRequestTypeDef",
     "CalculatedSpendTypeDef",
     "BudgetedAndActualAmountsTypeDef",
+    "DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
     "DescribeBudgetActionHistoriesRequestRequestTypeDef",
+    "DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
     "DescribeBudgetPerformanceHistoryRequestRequestTypeDef",
-    "CreateBudgetActionResponseTypeDef",
-    "DescribeNotificationsForBudgetResponseTypeDef",
-    "DescribeSubscribersForNotificationResponseTypeDef",
-    "ExecuteBudgetActionResponseTypeDef",
     "DefinitionTypeDef",
-    "DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
-    "DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
-    "DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
-    "DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
-    "DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
-    "DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
-    "DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
-    "DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
     "DescribeBudgetNotificationsForAccountResponseTypeDef",
     "BudgetTypeDef",
     "BudgetPerformanceHistoryTypeDef",
     "ActionTypeDef",
     "CreateBudgetActionRequestRequestTypeDef",
     "UpdateBudgetActionRequestRequestTypeDef",
     "CreateBudgetRequestRequestTypeDef",
@@ -194,22 +194,21 @@
     {
         "Start": Union[datetime, str],
         "End": Union[datetime, str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBudgetActionResponseTypeDef = TypedDict(
+    "CreateBudgetActionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AccountId": str,
+        "BudgetName": str,
+        "ActionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIamActionDefinitionTypeDef = TypedDict(
     "_RequiredIamActionDefinitionTypeDef",
     {
         "PolicyArn": str,
@@ -260,33 +259,43 @@
     "DeleteBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 DescribeBudgetActionRequestRequestTypeDef = TypedDict(
     "DescribeBudgetActionRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "ActionId": str,
     },
 )
 
+_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef(
+    _RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
+    _OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeBudgetActionsForAccountRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetActionsForAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalDescribeBudgetActionsForAccountRequestRequestTypeDef = TypedDict(
@@ -300,14 +309,35 @@
 
 class DescribeBudgetActionsForAccountRequestRequestTypeDef(
     _RequiredDescribeBudgetActionsForAccountRequestRequestTypeDef,
     _OptionalDescribeBudgetActionsForAccountRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+    },
+)
+_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef(
+    _RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
+    _OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeBudgetActionsForBudgetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetActionsForBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
@@ -322,14 +352,34 @@
 
 class DescribeBudgetActionsForBudgetRequestRequestTypeDef(
     _RequiredDescribeBudgetActionsForBudgetRequestRequestTypeDef,
     _OptionalDescribeBudgetActionsForBudgetRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef(
+    _RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
+    _OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeBudgetNotificationsForAccountRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetNotificationsForAccountRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalDescribeBudgetNotificationsForAccountRequestRequestTypeDef = TypedDict(
@@ -351,14 +401,34 @@
     "DescribeBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
 
+_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef(
+    _RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
+    _OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeBudgetsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeBudgetsRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalDescribeBudgetsRequestRequestTypeDef = TypedDict(
@@ -371,14 +441,35 @@
 )
 
 class DescribeBudgetsRequestRequestTypeDef(
     _RequiredDescribeBudgetsRequestRequestTypeDef, _OptionalDescribeBudgetsRequestRequestTypeDef
 ):
     pass
 
+_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
+    "_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+    },
+)
+_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
+    "_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef(
+    _RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
+    _OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeNotificationsForBudgetRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeNotificationsForBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
@@ -403,14 +494,55 @@
         "AccountId": str,
         "BudgetName": str,
         "ActionId": str,
         "ExecutionType": ExecutionTypeType,
     },
 )
 
+ExecuteBudgetActionResponseTypeDef = TypedDict(
+    "ExecuteBudgetActionResponseTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+        "ActionId": str,
+        "ExecutionType": ExecutionTypeType,
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
+DescribeSubscribersForNotificationResponseTypeDef = TypedDict(
+    "DescribeSubscribersForNotificationResponseTypeDef",
+    {
+        "Subscribers": List[SubscriberTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAutoAdjustDataTypeDef = TypedDict(
     "_RequiredAutoAdjustDataTypeDef",
     {
         "AutoAdjustType": AutoAdjustTypeType,
     },
 )
 _OptionalAutoAdjustDataTypeDef = TypedDict(
@@ -469,14 +601,45 @@
         "AccountId": str,
         "BudgetName": str,
         "Notification": NotificationTypeDef,
         "Subscriber": SubscriberTypeDef,
     },
 )
 
+DescribeNotificationsForBudgetResponseTypeDef = TypedDict(
+    "DescribeNotificationsForBudgetResponseTypeDef",
+    {
+        "Notifications": List[NotificationTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
+    "_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
+    {
+        "AccountId": str,
+        "BudgetName": str,
+        "Notification": NotificationTypeDef,
+    },
+)
+_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
+    "_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef(
+    _RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
+    _OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeSubscribersForNotificationRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeSubscribersForNotificationRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "Notification": NotificationTypeDef,
     },
@@ -548,110 +711,14 @@
         "BudgetedAmount": SpendTypeDef,
         "ActualAmount": SpendTypeDef,
         "TimePeriod": TimePeriodTypeDef,
     },
     total=False,
 )
 
-_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
-    "_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "ActionId": str,
-    },
-)
-_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
-    "_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef",
-    {
-        "TimePeriod": TimePeriodTypeDef,
-        "MaxResults": int,
-        "NextToken": str,
-    },
-    total=False,
-)
-
-class DescribeBudgetActionHistoriesRequestRequestTypeDef(
-    _RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef,
-    _OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef,
-):
-    pass
-
-_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
-    "_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-    },
-)
-_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
-    "_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
-    {
-        "TimePeriod": TimePeriodTypeDef,
-        "MaxResults": int,
-        "NextToken": str,
-    },
-    total=False,
-)
-
-class DescribeBudgetPerformanceHistoryRequestRequestTypeDef(
-    _RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
-    _OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
-):
-    pass
-
-CreateBudgetActionResponseTypeDef = TypedDict(
-    "CreateBudgetActionResponseTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "ActionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeNotificationsForBudgetResponseTypeDef = TypedDict(
-    "DescribeNotificationsForBudgetResponseTypeDef",
-    {
-        "Notifications": List[NotificationTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeSubscribersForNotificationResponseTypeDef = TypedDict(
-    "DescribeSubscribersForNotificationResponseTypeDef",
-    {
-        "Subscribers": List[SubscriberTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ExecuteBudgetActionResponseTypeDef = TypedDict(
-    "ExecuteBudgetActionResponseTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "ActionId": str,
-        "ExecutionType": ExecutionTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DefinitionTypeDef = TypedDict(
-    "DefinitionTypeDef",
-    {
-        "IamActionDefinition": IamActionDefinitionTypeDef,
-        "ScpActionDefinition": ScpActionDefinitionTypeDef,
-        "SsmActionDefinition": SsmActionDefinitionTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef = (
     TypedDict(
         "_RequiredDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
         {
             "AccountId": str,
             "BudgetName": str,
             "ActionId": str,
@@ -659,178 +726,111 @@
     )
 )
 _OptionalDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef = (
     TypedDict(
         "_OptionalDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef",
         {
             "TimePeriod": TimePeriodTypeDef,
-            "PaginationConfig": PaginatorConfigTypeDef,
+            "PaginationConfig": "PaginatorConfigTypeDef",
         },
         total=False,
     )
 )
 
 class DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef(
     _RequiredDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
     _OptionalDescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
 ):
     pass
 
-_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef(
-    _RequiredDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
-    _OptionalDescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
+_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
+        "ActionId": str,
     },
 )
-_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef(
-    _RequiredDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
-    _OptionalDescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef",
+_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "TimePeriod": TimePeriodTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
     },
     total=False,
 )
 
-class DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef(
-    _RequiredDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
-    _OptionalDescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
+class DescribeBudgetActionHistoriesRequestRequestTypeDef(
+    _RequiredDescribeBudgetActionHistoriesRequestRequestTypeDef,
+    _OptionalDescribeBudgetActionHistoriesRequestRequestTypeDef,
 ):
     pass
 
 _RequiredDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef = TypedDict(
     "_RequiredDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
 _OptionalDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef = TypedDict(
     "_OptionalDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef",
     {
         "TimePeriod": TimePeriodTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef(
     _RequiredDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
     _OptionalDescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
 ):
     pass
 
-_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef(
-    _RequiredDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
-    _OptionalDescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
-    "_RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
     },
 )
-_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef = TypedDict(
-    "_OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef",
+_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "TimePeriod": TimePeriodTypeDef,
+        "MaxResults": int,
+        "NextToken": str,
     },
     total=False,
 )
 
-class DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef(
-    _RequiredDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
-    _OptionalDescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
+class DescribeBudgetPerformanceHistoryRequestRequestTypeDef(
+    _RequiredDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
+    _OptionalDescribeBudgetPerformanceHistoryRequestRequestTypeDef,
 ):
     pass
 
-_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
-    "_RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
-    {
-        "AccountId": str,
-        "BudgetName": str,
-        "Notification": NotificationTypeDef,
-    },
-)
-_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef = TypedDict(
-    "_OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef",
+DefinitionTypeDef = TypedDict(
+    "DefinitionTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "IamActionDefinition": IamActionDefinitionTypeDef,
+        "ScpActionDefinition": ScpActionDefinitionTypeDef,
+        "SsmActionDefinition": SsmActionDefinitionTypeDef,
     },
     total=False,
 )
 
-class DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef(
-    _RequiredDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
-    _OptionalDescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
-):
-    pass
-
 DescribeBudgetNotificationsForAccountResponseTypeDef = TypedDict(
     "DescribeBudgetNotificationsForAccountResponseTypeDef",
     {
         "BudgetNotificationsForAccount": List[BudgetNotificationsForAccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBudgetTypeDef = TypedDict(
     "_RequiredBudgetTypeDef",
     {
         "BudgetName": str,
@@ -947,24 +947,24 @@
 ):
     pass
 
 DescribeBudgetResponseTypeDef = TypedDict(
     "DescribeBudgetResponseTypeDef",
     {
         "Budget": BudgetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetsResponseTypeDef = TypedDict(
     "DescribeBudgetsResponseTypeDef",
     {
         "Budgets": List[BudgetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBudgetRequestRequestTypeDef = TypedDict(
     "UpdateBudgetRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -973,15 +973,15 @@
 )
 
 DescribeBudgetPerformanceHistoryResponseTypeDef = TypedDict(
     "DescribeBudgetPerformanceHistoryResponseTypeDef",
     {
         "BudgetPerformanceHistory": BudgetPerformanceHistoryTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionHistoryDetailsTypeDef = TypedDict(
     "ActionHistoryDetailsTypeDef",
     {
         "Message": str,
@@ -991,54 +991,54 @@
 
 DeleteBudgetActionResponseTypeDef = TypedDict(
     "DeleteBudgetActionResponseTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "Action": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetActionResponseTypeDef = TypedDict(
     "DescribeBudgetActionResponseTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "Action": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetActionsForAccountResponseTypeDef = TypedDict(
     "DescribeBudgetActionsForAccountResponseTypeDef",
     {
         "Actions": List[ActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBudgetActionsForBudgetResponseTypeDef = TypedDict(
     "DescribeBudgetActionsForBudgetResponseTypeDef",
     {
         "Actions": List[ActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBudgetActionResponseTypeDef = TypedDict(
     "UpdateBudgetActionResponseTypeDef",
     {
         "AccountId": str,
         "BudgetName": str,
         "OldAction": ActionTypeDef,
         "NewAction": ActionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionHistoryTypeDef = TypedDict(
     "ActionHistoryTypeDef",
     {
         "Timestamp": datetime,
@@ -1049,10 +1049,10 @@
 )
 
 DescribeBudgetActionHistoriesResponseTypeDef = TypedDict(
     "DescribeBudgetActionHistoriesResponseTypeDef",
     {
         "ActionHistories": List[ActionHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/PKG-INFO` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-budgets
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Budgets 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Budgets 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-budgets"></a>
 
 # types-aiobotocore-budgets
 
 [![PyPI - types-aiobotocore-budgets](https://img.shields.io/pypi/v/types-aiobotocore-budgets.svg?color=blue)](https://pypi.org/project/types-aiobotocore-budgets)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-budgets.svg?color=blue)](https://pypi.org/project/types-aiobotocore-budgets)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-budgets?color=blue)](https://pypistats.org/packages/types-aiobotocore-budgets)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Budgets 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets)
+[aiobotocore.Budgets 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/budgets.html#Budgets)
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
 [types-aiobotocore-budgets docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_budgets/).
 
 See how it helps to find and fix potential bugs:
 
@@ -370,56 +370,56 @@
     ActionThresholdTypeDef,
     SubscriberTypeDef,
     HistoricalOptionsTypeDef,
     NotificationTypeDef,
     CostTypesTypeDef,
     SpendTypeDef,
     TimePeriodTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBudgetActionResponseTypeDef,
     IamActionDefinitionTypeDef,
     ScpActionDefinitionTypeDef,
     SsmActionDefinitionTypeDef,
     DeleteBudgetActionRequestRequestTypeDef,
     DeleteBudgetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     DescribeBudgetActionRequestRequestTypeDef,
+    DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
     DescribeBudgetActionsForAccountRequestRequestTypeDef,
+    DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
     DescribeBudgetActionsForBudgetRequestRequestTypeDef,
+    DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
     DescribeBudgetNotificationsForAccountRequestRequestTypeDef,
     DescribeBudgetRequestRequestTypeDef,
+    DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
     DescribeBudgetsRequestRequestTypeDef,
+    DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
     DescribeNotificationsForBudgetRequestRequestTypeDef,
     ExecuteBudgetActionRequestRequestTypeDef,
+    ExecuteBudgetActionResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    DescribeSubscribersForNotificationResponseTypeDef,
     AutoAdjustDataTypeDef,
     BudgetNotificationsForAccountTypeDef,
     CreateNotificationRequestRequestTypeDef,
     CreateSubscriberRequestRequestTypeDef,
     DeleteNotificationRequestRequestTypeDef,
     DeleteSubscriberRequestRequestTypeDef,
+    DescribeNotificationsForBudgetResponseTypeDef,
+    DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
     DescribeSubscribersForNotificationRequestRequestTypeDef,
     NotificationWithSubscribersTypeDef,
     UpdateNotificationRequestRequestTypeDef,
     UpdateSubscriberRequestRequestTypeDef,
     CalculatedSpendTypeDef,
     BudgetedAndActualAmountsTypeDef,
+    DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
     DescribeBudgetActionHistoriesRequestRequestTypeDef,
+    DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
     DescribeBudgetPerformanceHistoryRequestRequestTypeDef,
-    CreateBudgetActionResponseTypeDef,
-    DescribeNotificationsForBudgetResponseTypeDef,
-    DescribeSubscribersForNotificationResponseTypeDef,
-    ExecuteBudgetActionResponseTypeDef,
     DefinitionTypeDef,
-    DescribeBudgetActionHistoriesRequestDescribeBudgetActionHistoriesPaginateTypeDef,
-    DescribeBudgetActionsForAccountRequestDescribeBudgetActionsForAccountPaginateTypeDef,
-    DescribeBudgetActionsForBudgetRequestDescribeBudgetActionsForBudgetPaginateTypeDef,
-    DescribeBudgetNotificationsForAccountRequestDescribeBudgetNotificationsForAccountPaginateTypeDef,
-    DescribeBudgetPerformanceHistoryRequestDescribeBudgetPerformanceHistoryPaginateTypeDef,
-    DescribeBudgetsRequestDescribeBudgetsPaginateTypeDef,
-    DescribeNotificationsForBudgetRequestDescribeNotificationsForBudgetPaginateTypeDef,
-    DescribeSubscribersForNotificationRequestDescribeSubscribersForNotificationPaginateTypeDef,
     DescribeBudgetNotificationsForAccountResponseTypeDef,
     BudgetTypeDef,
     BudgetPerformanceHistoryTypeDef,
     ActionTypeDef,
     CreateBudgetActionRequestRequestTypeDef,
     UpdateBudgetActionRequestRequestTypeDef,
     CreateBudgetRequestRequestTypeDef,
@@ -445,43 +445,43 @@
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

### Comparing `types-aiobotocore-budgets-2.5.0.post1/types_aiobotocore_budgets.egg-info/SOURCES.txt` & `types-aiobotocore-budgets-2.5.1/types_aiobotocore_budgets.egg-info/SOURCES.txt`

 * *Files identical despite different names*

