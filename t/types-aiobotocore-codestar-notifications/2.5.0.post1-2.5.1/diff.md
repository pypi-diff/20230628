# Comparing `tmp/types-aiobotocore-codestar-notifications-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codestar-notifications-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codestar-notifications-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-codestar-notifications-2.5.1.tar", last modified: Wed Jun 28 01:43:17 2023, max compression
```

## Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1.tar` & `types-aiobotocore-codestar-notifications-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.695072 types-aiobotocore-codestar-notifications-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15495 2023-03-11 12:26:24.687072 types-aiobotocore-codestar-notifications-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13865 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:24.695072 types-aiobotocore-codestar-notifications-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2220 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.683072 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/
--rw-r--r--   0 runner    (1001) docker     (123)     1177 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1176 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1001 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15312 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15287 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8819 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8817 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4977 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4971 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    10927 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    10918 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.687072 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15495 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1098 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.890115 types-aiobotocore-codestar-notifications-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15502 2023-06-28 01:43:17.890115 types-aiobotocore-codestar-notifications-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13878 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:17.890115 types-aiobotocore-codestar-notifications-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2214 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.886115 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/
+-rw-r--r--   0 runner    (1001) docker     (123)     1177 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1176 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      989 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15312 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15287 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9028 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9026 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4863 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4858 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    10953 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10944 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:06.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.890115 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15502 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1098 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/LICENSE` & `types-aiobotocore-codestar-notifications-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codestar-notifications-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codestar-notifications
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeStarNotifications 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeStarNotifications 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codestar-notifications"></a>
 
 # types-aiobotocore-codestar-notifications
 
 [![PyPI - types-aiobotocore-codestar-notifications](https://img.shields.io/pypi/v/types-aiobotocore-codestar-notifications.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-notifications)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar-notifications.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-notifications)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar-notifications?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar-notifications)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStarNotifications 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications)
+[aiobotocore.CodeStarNotifications 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications)
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
 [types-aiobotocore-codestar-notifications docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,43 +331,43 @@
 
 `types_aiobotocore_codestar_notifications.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar_notifications.type_defs import (
     TargetTypeDef,
-    ResponseMetadataTypeDef,
+    CreateNotificationRuleResultTypeDef,
     DeleteNotificationRuleRequestRequestTypeDef,
+    DeleteNotificationRuleResultTypeDef,
     DeleteTargetRequestRequestTypeDef,
     DescribeNotificationRuleRequestRequestTypeDef,
     EventTypeSummaryTypeDef,
     TargetSummaryTypeDef,
     ListEventTypesFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListNotificationRulesFilterTypeDef,
     NotificationRuleSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     ListTargetsFilterTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    SubscribeResultTypeDef,
     TagResourceRequestRequestTypeDef,
+    TagResourceResultTypeDef,
     UnsubscribeRequestRequestTypeDef,
+    UnsubscribeResultTypeDef,
     UntagResourceRequestRequestTypeDef,
     CreateNotificationRuleRequestRequestTypeDef,
     SubscribeRequestRequestTypeDef,
     UpdateNotificationRuleRequestRequestTypeDef,
-    CreateNotificationRuleResultTypeDef,
-    DeleteNotificationRuleResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    SubscribeResultTypeDef,
-    TagResourceResultTypeDef,
-    UnsubscribeResultTypeDef,
     ListEventTypesResultTypeDef,
     DescribeNotificationRuleResultTypeDef,
     ListTargetsResultTypeDef,
-    ListEventTypesRequestRequestTypeDef,
     ListEventTypesRequestListEventTypesPaginateTypeDef,
+    ListEventTypesRequestRequestTypeDef,
     ListNotificationRulesRequestListNotificationRulesPaginateTypeDef,
     ListNotificationRulesRequestRequestTypeDef,
     ListNotificationRulesResultTypeDef,
     ListTargetsRequestListTargetsPaginateTypeDef,
     ListTargetsRequestRequestTypeDef,
 )
 
@@ -379,43 +379,43 @@
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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/README.md` & `types-aiobotocore-codestar-notifications-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codestar-notifications"></a>
 
 # types-aiobotocore-codestar-notifications
 
 [![PyPI - types-aiobotocore-codestar-notifications](https://img.shields.io/pypi/v/types-aiobotocore-codestar-notifications.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-notifications)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar-notifications.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-notifications)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar-notifications?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar-notifications)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStarNotifications 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications)
+[aiobotocore.CodeStarNotifications 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications)
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
 [types-aiobotocore-codestar-notifications docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,43 +298,43 @@
 
 `types_aiobotocore_codestar_notifications.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar_notifications.type_defs import (
     TargetTypeDef,
-    ResponseMetadataTypeDef,
+    CreateNotificationRuleResultTypeDef,
     DeleteNotificationRuleRequestRequestTypeDef,
+    DeleteNotificationRuleResultTypeDef,
     DeleteTargetRequestRequestTypeDef,
     DescribeNotificationRuleRequestRequestTypeDef,
     EventTypeSummaryTypeDef,
     TargetSummaryTypeDef,
     ListEventTypesFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListNotificationRulesFilterTypeDef,
     NotificationRuleSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     ListTargetsFilterTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    SubscribeResultTypeDef,
     TagResourceRequestRequestTypeDef,
+    TagResourceResultTypeDef,
     UnsubscribeRequestRequestTypeDef,
+    UnsubscribeResultTypeDef,
     UntagResourceRequestRequestTypeDef,
     CreateNotificationRuleRequestRequestTypeDef,
     SubscribeRequestRequestTypeDef,
     UpdateNotificationRuleRequestRequestTypeDef,
-    CreateNotificationRuleResultTypeDef,
-    DeleteNotificationRuleResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    SubscribeResultTypeDef,
-    TagResourceResultTypeDef,
-    UnsubscribeResultTypeDef,
     ListEventTypesResultTypeDef,
     DescribeNotificationRuleResultTypeDef,
     ListTargetsResultTypeDef,
-    ListEventTypesRequestRequestTypeDef,
     ListEventTypesRequestListEventTypesPaginateTypeDef,
+    ListEventTypesRequestRequestTypeDef,
     ListNotificationRulesRequestListNotificationRulesPaginateTypeDef,
     ListNotificationRulesRequestRequestTypeDef,
     ListNotificationRulesResultTypeDef,
     ListTargetsRequestListTargetsPaginateTypeDef,
     ListTargetsRequestRequestTypeDef,
 )
 
@@ -346,43 +346,43 @@
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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/setup.py` & `types-aiobotocore-codestar-notifications-2.5.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codestar-notifications.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codestar-notifications",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codestar_notifications"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeStarNotifications 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodeStarNotifications 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/",
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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/__init__.py` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/__init__.pyi` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/__main__.py` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeStarNotifications 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeStarNotifications 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications\nOther"
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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/client.py` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/client.pyi` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/literals.py` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -107,14 +107,15 @@
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
@@ -193,14 +194,15 @@
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
@@ -211,14 +213,15 @@
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
@@ -254,14 +257,15 @@
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
@@ -280,16 +284,19 @@
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
@@ -373,15 +380,17 @@
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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/literals.pyi` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -105,14 +105,15 @@
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
@@ -191,14 +192,15 @@
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
@@ -209,14 +211,15 @@
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
@@ -252,14 +255,15 @@
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
@@ -278,16 +282,19 @@
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
@@ -371,15 +378,17 @@
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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/paginator.py` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -20,94 +20,82 @@
         client: CodeStarNotificationsClient
 
         list_event_types_paginator: ListEventTypesPaginator = client.get_paginator("list_event_types")
         list_notification_rules_paginator: ListNotificationRulesPaginator = client.get_paginator("list_notification_rules")
         list_targets_paginator: ListTargetsPaginator = client.get_paginator("list_targets")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListEventTypesFilterTypeDef,
     ListEventTypesResultTypeDef,
     ListNotificationRulesFilterTypeDef,
     ListNotificationRulesResultTypeDef,
     ListTargetsFilterTypeDef,
     ListTargetsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListEventTypesPaginator", "ListNotificationRulesPaginator", "ListTargetsPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListEventTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListEventTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listeventtypespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ListEventTypesFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventTypesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListEventTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listeventtypespaginator)
         """
 
-
 class ListNotificationRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListNotificationRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listnotificationrulespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ListNotificationRulesFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNotificationRulesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListNotificationRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listnotificationrulespaginator)
         """
 
-
 class ListTargetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListTargets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listtargetspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ListTargetsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listtargetspaginator)
         """
```

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/paginator.pyi` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -20,88 +20,87 @@
         client: CodeStarNotificationsClient
 
         list_event_types_paginator: ListEventTypesPaginator = client.get_paginator("list_event_types")
         list_notification_rules_paginator: ListNotificationRulesPaginator = client.get_paginator("list_notification_rules")
         list_targets_paginator: ListTargetsPaginator = client.get_paginator("list_targets")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListEventTypesFilterTypeDef,
     ListEventTypesResultTypeDef,
     ListNotificationRulesFilterTypeDef,
     ListNotificationRulesResultTypeDef,
     ListTargetsFilterTypeDef,
     ListTargetsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListEventTypesPaginator", "ListNotificationRulesPaginator", "ListTargetsPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListEventTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListEventTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listeventtypespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ListEventTypesFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventTypesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListEventTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listeventtypespaginator)
         """
 
+
 class ListNotificationRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListNotificationRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listnotificationrulespaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ListNotificationRulesFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNotificationRulesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListNotificationRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listnotificationrulespaginator)
         """
 
+
 class ListTargetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListTargets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listtargetspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[ListTargetsFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications.Paginator.ListTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/paginators/#listtargetspaginator)
         """
```

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/type_defs.py` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -28,43 +28,43 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TargetTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateNotificationRuleResultTypeDef",
     "DeleteNotificationRuleRequestRequestTypeDef",
+    "DeleteNotificationRuleResultTypeDef",
     "DeleteTargetRequestRequestTypeDef",
     "DescribeNotificationRuleRequestRequestTypeDef",
     "EventTypeSummaryTypeDef",
     "TargetSummaryTypeDef",
     "ListEventTypesFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListNotificationRulesFilterTypeDef",
     "NotificationRuleSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
     "ListTargetsFilterTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "SubscribeResultTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "TagResourceResultTypeDef",
     "UnsubscribeRequestRequestTypeDef",
+    "UnsubscribeResultTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "CreateNotificationRuleRequestRequestTypeDef",
     "SubscribeRequestRequestTypeDef",
     "UpdateNotificationRuleRequestRequestTypeDef",
-    "CreateNotificationRuleResultTypeDef",
-    "DeleteNotificationRuleResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "SubscribeResultTypeDef",
-    "TagResourceResultTypeDef",
-    "UnsubscribeResultTypeDef",
     "ListEventTypesResultTypeDef",
     "DescribeNotificationRuleResultTypeDef",
     "ListTargetsResultTypeDef",
-    "ListEventTypesRequestRequestTypeDef",
     "ListEventTypesRequestListEventTypesPaginateTypeDef",
+    "ListEventTypesRequestRequestTypeDef",
     "ListNotificationRulesRequestListNotificationRulesPaginateTypeDef",
     "ListNotificationRulesRequestRequestTypeDef",
     "ListNotificationRulesResultTypeDef",
     "ListTargetsRequestListTargetsPaginateTypeDef",
     "ListTargetsRequestRequestTypeDef",
 )
 
@@ -73,32 +73,37 @@
     {
         "TargetType": str,
         "TargetAddress": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateNotificationRuleResultTypeDef = TypedDict(
+    "CreateNotificationRuleResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNotificationRuleRequestRequestTypeDef = TypedDict(
     "DeleteNotificationRuleRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeleteNotificationRuleResultTypeDef = TypedDict(
+    "DeleteNotificationRuleResultTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteTargetRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTargetRequestRequestTypeDef",
     {
         "TargetAddress": str,
     },
 )
 _OptionalDeleteTargetRequestRequestTypeDef = TypedDict(
@@ -148,24 +153,14 @@
     "ListEventTypesFilterTypeDef",
     {
         "Name": ListEventTypesFilterNameType,
         "Value": str,
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
 ListNotificationRulesFilterTypeDef = TypedDict(
     "ListNotificationRulesFilterTypeDef",
     {
         "Name": ListNotificationRulesFilterNameType,
         "Value": str,
     },
 )
@@ -182,38 +177,91 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTargetsFilterTypeDef = TypedDict(
     "ListTargetsFilterTypeDef",
     {
         "Name": ListTargetsFilterNameType,
         "Value": str,
     },
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
+SubscribeResultTypeDef = TypedDict(
+    "SubscribeResultTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "Arn": str,
         "Tags": Mapping[str, str],
     },
 )
 
+TagResourceResultTypeDef = TypedDict(
+    "TagResourceResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnsubscribeRequestRequestTypeDef = TypedDict(
     "UnsubscribeRequestRequestTypeDef",
     {
         "Arn": str,
         "TargetAddress": str,
     },
 )
 
+UnsubscribeResultTypeDef = TypedDict(
+    "UnsubscribeResultTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "Arn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -290,68 +338,20 @@
 class UpdateNotificationRuleRequestRequestTypeDef(
     _RequiredUpdateNotificationRuleRequestRequestTypeDef,
     _OptionalUpdateNotificationRuleRequestRequestTypeDef,
 ):
     pass
 
 
-CreateNotificationRuleResultTypeDef = TypedDict(
-    "CreateNotificationRuleResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteNotificationRuleResultTypeDef = TypedDict(
-    "DeleteNotificationRuleResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubscribeResultTypeDef = TypedDict(
-    "SubscribeResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagResourceResultTypeDef = TypedDict(
-    "TagResourceResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UnsubscribeResultTypeDef = TypedDict(
-    "UnsubscribeResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListEventTypesResultTypeDef = TypedDict(
     "ListEventTypesResultTypeDef",
     {
         "EventTypes": List[EventTypeSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNotificationRuleResultTypeDef = TypedDict(
     "DescribeNotificationRuleResultTypeDef",
     {
         "Arn": str,
@@ -361,51 +361,51 @@
         "Targets": List[TargetSummaryTypeDef],
         "DetailType": DetailTypeType,
         "CreatedBy": str,
         "Status": NotificationRuleStatusType,
         "CreatedTimestamp": datetime,
         "LastModifiedTimestamp": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsResultTypeDef = TypedDict(
     "ListTargetsResultTypeDef",
     {
         "Targets": List[TargetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListEventTypesRequestRequestTypeDef = TypedDict(
-    "ListEventTypesRequestRequestTypeDef",
+ListEventTypesRequestListEventTypesPaginateTypeDef = TypedDict(
+    "ListEventTypesRequestListEventTypesPaginateTypeDef",
     {
         "Filters": Sequence[ListEventTypesFilterTypeDef],
-        "NextToken": str,
-        "MaxResults": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListEventTypesRequestListEventTypesPaginateTypeDef = TypedDict(
-    "ListEventTypesRequestListEventTypesPaginateTypeDef",
+ListEventTypesRequestRequestTypeDef = TypedDict(
+    "ListEventTypesRequestRequestTypeDef",
     {
         "Filters": Sequence[ListEventTypesFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
     },
     total=False,
 )
 
 ListNotificationRulesRequestListNotificationRulesPaginateTypeDef = TypedDict(
     "ListNotificationRulesRequestListNotificationRulesPaginateTypeDef",
     {
         "Filters": Sequence[ListNotificationRulesFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListNotificationRulesRequestRequestTypeDef = TypedDict(
     "ListNotificationRulesRequestRequestTypeDef",
     {
@@ -417,23 +417,23 @@
 )
 
 ListNotificationRulesResultTypeDef = TypedDict(
     "ListNotificationRulesResultTypeDef",
     {
         "NextToken": str,
         "NotificationRules": List[NotificationRuleSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsRequestListTargetsPaginateTypeDef = TypedDict(
     "ListTargetsRequestListTargetsPaginateTypeDef",
     {
         "Filters": Sequence[ListTargetsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTargetsRequestRequestTypeDef = TypedDict(
     "ListTargetsRequestRequestTypeDef",
     {
```

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications/type_defs.pyi` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -27,43 +27,43 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TargetTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateNotificationRuleResultTypeDef",
     "DeleteNotificationRuleRequestRequestTypeDef",
+    "DeleteNotificationRuleResultTypeDef",
     "DeleteTargetRequestRequestTypeDef",
     "DescribeNotificationRuleRequestRequestTypeDef",
     "EventTypeSummaryTypeDef",
     "TargetSummaryTypeDef",
     "ListEventTypesFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListNotificationRulesFilterTypeDef",
     "NotificationRuleSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
     "ListTargetsFilterTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
+    "SubscribeResultTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "TagResourceResultTypeDef",
     "UnsubscribeRequestRequestTypeDef",
+    "UnsubscribeResultTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "CreateNotificationRuleRequestRequestTypeDef",
     "SubscribeRequestRequestTypeDef",
     "UpdateNotificationRuleRequestRequestTypeDef",
-    "CreateNotificationRuleResultTypeDef",
-    "DeleteNotificationRuleResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "SubscribeResultTypeDef",
-    "TagResourceResultTypeDef",
-    "UnsubscribeResultTypeDef",
     "ListEventTypesResultTypeDef",
     "DescribeNotificationRuleResultTypeDef",
     "ListTargetsResultTypeDef",
-    "ListEventTypesRequestRequestTypeDef",
     "ListEventTypesRequestListEventTypesPaginateTypeDef",
+    "ListEventTypesRequestRequestTypeDef",
     "ListNotificationRulesRequestListNotificationRulesPaginateTypeDef",
     "ListNotificationRulesRequestRequestTypeDef",
     "ListNotificationRulesResultTypeDef",
     "ListTargetsRequestListTargetsPaginateTypeDef",
     "ListTargetsRequestRequestTypeDef",
 )
 
@@ -72,32 +72,37 @@
     {
         "TargetType": str,
         "TargetAddress": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateNotificationRuleResultTypeDef = TypedDict(
+    "CreateNotificationRuleResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNotificationRuleRequestRequestTypeDef = TypedDict(
     "DeleteNotificationRuleRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+DeleteNotificationRuleResultTypeDef = TypedDict(
+    "DeleteNotificationRuleResultTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteTargetRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTargetRequestRequestTypeDef",
     {
         "TargetAddress": str,
     },
 )
 _OptionalDeleteTargetRequestRequestTypeDef = TypedDict(
@@ -145,24 +150,14 @@
     "ListEventTypesFilterTypeDef",
     {
         "Name": ListEventTypesFilterNameType,
         "Value": str,
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
 ListNotificationRulesFilterTypeDef = TypedDict(
     "ListNotificationRulesFilterTypeDef",
     {
         "Name": ListNotificationRulesFilterNameType,
         "Value": str,
     },
 )
@@ -179,38 +174,91 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTargetsFilterTypeDef = TypedDict(
     "ListTargetsFilterTypeDef",
     {
         "Name": ListTargetsFilterNameType,
         "Value": str,
     },
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
+SubscribeResultTypeDef = TypedDict(
+    "SubscribeResultTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "Arn": str,
         "Tags": Mapping[str, str],
     },
 )
 
+TagResourceResultTypeDef = TypedDict(
+    "TagResourceResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnsubscribeRequestRequestTypeDef = TypedDict(
     "UnsubscribeRequestRequestTypeDef",
     {
         "Arn": str,
         "TargetAddress": str,
     },
 )
 
+UnsubscribeResultTypeDef = TypedDict(
+    "UnsubscribeResultTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "Arn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -281,68 +329,20 @@
 
 class UpdateNotificationRuleRequestRequestTypeDef(
     _RequiredUpdateNotificationRuleRequestRequestTypeDef,
     _OptionalUpdateNotificationRuleRequestRequestTypeDef,
 ):
     pass
 
-CreateNotificationRuleResultTypeDef = TypedDict(
-    "CreateNotificationRuleResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteNotificationRuleResultTypeDef = TypedDict(
-    "DeleteNotificationRuleResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubscribeResultTypeDef = TypedDict(
-    "SubscribeResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagResourceResultTypeDef = TypedDict(
-    "TagResourceResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UnsubscribeResultTypeDef = TypedDict(
-    "UnsubscribeResultTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListEventTypesResultTypeDef = TypedDict(
     "ListEventTypesResultTypeDef",
     {
         "EventTypes": List[EventTypeSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNotificationRuleResultTypeDef = TypedDict(
     "DescribeNotificationRuleResultTypeDef",
     {
         "Arn": str,
@@ -352,51 +352,51 @@
         "Targets": List[TargetSummaryTypeDef],
         "DetailType": DetailTypeType,
         "CreatedBy": str,
         "Status": NotificationRuleStatusType,
         "CreatedTimestamp": datetime,
         "LastModifiedTimestamp": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsResultTypeDef = TypedDict(
     "ListTargetsResultTypeDef",
     {
         "Targets": List[TargetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListEventTypesRequestRequestTypeDef = TypedDict(
-    "ListEventTypesRequestRequestTypeDef",
+ListEventTypesRequestListEventTypesPaginateTypeDef = TypedDict(
+    "ListEventTypesRequestListEventTypesPaginateTypeDef",
     {
         "Filters": Sequence[ListEventTypesFilterTypeDef],
-        "NextToken": str,
-        "MaxResults": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-ListEventTypesRequestListEventTypesPaginateTypeDef = TypedDict(
-    "ListEventTypesRequestListEventTypesPaginateTypeDef",
+ListEventTypesRequestRequestTypeDef = TypedDict(
+    "ListEventTypesRequestRequestTypeDef",
     {
         "Filters": Sequence[ListEventTypesFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
     },
     total=False,
 )
 
 ListNotificationRulesRequestListNotificationRulesPaginateTypeDef = TypedDict(
     "ListNotificationRulesRequestListNotificationRulesPaginateTypeDef",
     {
         "Filters": Sequence[ListNotificationRulesFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListNotificationRulesRequestRequestTypeDef = TypedDict(
     "ListNotificationRulesRequestRequestTypeDef",
     {
@@ -408,23 +408,23 @@
 )
 
 ListNotificationRulesResultTypeDef = TypedDict(
     "ListNotificationRulesResultTypeDef",
     {
         "NextToken": str,
         "NotificationRules": List[NotificationRuleSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsRequestListTargetsPaginateTypeDef = TypedDict(
     "ListTargetsRequestListTargetsPaginateTypeDef",
     {
         "Filters": Sequence[ListTargetsFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTargetsRequestRequestTypeDef = TypedDict(
     "ListTargetsRequestRequestTypeDef",
     {
```

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/PKG-INFO` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codestar-notifications
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeStarNotifications 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeStarNotifications 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codestar-notifications"></a>
 
 # types-aiobotocore-codestar-notifications
 
 [![PyPI - types-aiobotocore-codestar-notifications](https://img.shields.io/pypi/v/types-aiobotocore-codestar-notifications.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-notifications)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar-notifications.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-notifications)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar-notifications?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar-notifications)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStarNotifications 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications)
+[aiobotocore.CodeStarNotifications 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-notifications.html#CodeStarNotifications)
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
 [types-aiobotocore-codestar-notifications docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_notifications/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,43 +331,43 @@
 
 `types_aiobotocore_codestar_notifications.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar_notifications.type_defs import (
     TargetTypeDef,
-    ResponseMetadataTypeDef,
+    CreateNotificationRuleResultTypeDef,
     DeleteNotificationRuleRequestRequestTypeDef,
+    DeleteNotificationRuleResultTypeDef,
     DeleteTargetRequestRequestTypeDef,
     DescribeNotificationRuleRequestRequestTypeDef,
     EventTypeSummaryTypeDef,
     TargetSummaryTypeDef,
     ListEventTypesFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListNotificationRulesFilterTypeDef,
     NotificationRuleSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     ListTargetsFilterTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
+    SubscribeResultTypeDef,
     TagResourceRequestRequestTypeDef,
+    TagResourceResultTypeDef,
     UnsubscribeRequestRequestTypeDef,
+    UnsubscribeResultTypeDef,
     UntagResourceRequestRequestTypeDef,
     CreateNotificationRuleRequestRequestTypeDef,
     SubscribeRequestRequestTypeDef,
     UpdateNotificationRuleRequestRequestTypeDef,
-    CreateNotificationRuleResultTypeDef,
-    DeleteNotificationRuleResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    SubscribeResultTypeDef,
-    TagResourceResultTypeDef,
-    UnsubscribeResultTypeDef,
     ListEventTypesResultTypeDef,
     DescribeNotificationRuleResultTypeDef,
     ListTargetsResultTypeDef,
-    ListEventTypesRequestRequestTypeDef,
     ListEventTypesRequestListEventTypesPaginateTypeDef,
+    ListEventTypesRequestRequestTypeDef,
     ListNotificationRulesRequestListNotificationRulesPaginateTypeDef,
     ListNotificationRulesRequestRequestTypeDef,
     ListNotificationRulesResultTypeDef,
     ListTargetsRequestListTargetsPaginateTypeDef,
     ListTargetsRequestRequestTypeDef,
 )
 
@@ -379,43 +379,43 @@
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

### Comparing `types-aiobotocore-codestar-notifications-2.5.0.post1/types_aiobotocore_codestar_notifications.egg-info/SOURCES.txt` & `types-aiobotocore-codestar-notifications-2.5.1/types_aiobotocore_codestar_notifications.egg-info/SOURCES.txt`

 * *Files identical despite different names*

