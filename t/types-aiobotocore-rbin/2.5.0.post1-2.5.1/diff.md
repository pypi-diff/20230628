# Comparing `tmp/types-aiobotocore-rbin-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-rbin-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-rbin-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-rbin-2.5.1.tar", last modified: Wed Jun 28 01:44:01 2023, max compression
```

## Comparing `types-aiobotocore-rbin-2.5.0.post1.tar` & `types-aiobotocore-rbin-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.795534 types-aiobotocore-rbin-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13615 2023-03-11 12:27:10.795534 types-aiobotocore-rbin-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12050 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:10.795534 types-aiobotocore-rbin-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2085 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.791534 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/
--rw-r--r--   0 runner    (1001) docker     (123)      623 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      622 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      932 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10323 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    10303 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8381 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8379 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2262 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2258 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     9443 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     9432 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:21:52.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:10.795534 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13615 2023-03-11 12:27:10.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      756 2023-03-11 12:27:10.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:10.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:10.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-03-11 12:27:10.000000 types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.246196 types-aiobotocore-rbin-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13604 2023-06-28 01:44:01.246196 types-aiobotocore-rbin-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12045 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:01.246196 types-aiobotocore-rbin-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.238196 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/
+-rw-r--r--   0 runner    (1001) docker     (123)      623 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      622 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      920 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10323 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10303 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8590 2023-06-28 01:38:40.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8588 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2144 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2141 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     9459 2023-06-28 01:38:40.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9448 2023-06-28 01:38:40.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:38:39.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:01.246196 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13604 2023-06-28 01:44:01.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      756 2023-06-28 01:44:01.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:01.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:01.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:01.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 01:44:01.000000 types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-rbin-2.5.0.post1/LICENSE` & `types-aiobotocore-rbin-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/PKG-INFO` & `types-aiobotocore-rbin-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rbin
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RecycleBin 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RecycleBin 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rbin"></a>
 
 # types-aiobotocore-rbin
 
 [![PyPI - types-aiobotocore-rbin](https://img.shields.io/pypi/v/types-aiobotocore-rbin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rbin)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rbin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rbin)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rbin?color=blue)](https://pypistats.org/packages/types-aiobotocore-rbin)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RecycleBin 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin)
+[aiobotocore.RecycleBin 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin)
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
 [types-aiobotocore-rbin docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,29 +320,29 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rbin.type_defs import (
     ResourceTagTypeDef,
     RetentionPeriodTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteRuleRequestRequestTypeDef,
     GetRuleRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     UnlockDelayTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UnlockRuleRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     RuleSummaryTypeDef,
     UpdateRuleRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateRuleResponseTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     LockConfigurationTypeDef,
     ListRulesResponseTypeDef,
     CreateRuleRequestRequestTypeDef,
     CreateRuleResponseTypeDef,
     GetRuleResponseTypeDef,
     LockRuleRequestRequestTypeDef,
     LockRuleResponseTypeDef,
@@ -357,43 +357,43 @@
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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/README.md` & `types-aiobotocore-rbin-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-rbin"></a>
 
 # types-aiobotocore-rbin
 
 [![PyPI - types-aiobotocore-rbin](https://img.shields.io/pypi/v/types-aiobotocore-rbin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rbin)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rbin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rbin)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rbin?color=blue)](https://pypistats.org/packages/types-aiobotocore-rbin)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RecycleBin 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin)
+[aiobotocore.RecycleBin 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin)
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
 [types-aiobotocore-rbin docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,29 +287,29 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rbin.type_defs import (
     ResourceTagTypeDef,
     RetentionPeriodTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteRuleRequestRequestTypeDef,
     GetRuleRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     UnlockDelayTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UnlockRuleRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     RuleSummaryTypeDef,
     UpdateRuleRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateRuleResponseTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     LockConfigurationTypeDef,
     ListRulesResponseTypeDef,
     CreateRuleRequestRequestTypeDef,
     CreateRuleResponseTypeDef,
     GetRuleResponseTypeDef,
     LockRuleRequestRequestTypeDef,
     LockRuleResponseTypeDef,
@@ -324,43 +324,43 @@
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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/setup.py` & `types-aiobotocore-rbin-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-rbin.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-rbin",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_rbin"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.RecycleBin 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.RecycleBin 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/",
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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/__init__.py` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/__init__.pyi` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/__main__.py` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.RecycleBin 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.RecycleBin 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin//\nBoto3 docs:   "
         "   https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin\nOther"
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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/client.py` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/client.pyi` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/literals.py` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/literals.py`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/literals.pyi` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/literals.pyi`

 * *Files 5% similar despite different names*

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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/paginator.py` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,29 +16,22 @@
     session = get_session()
     with session.create_client("rbin") as client:
         client: RecycleBinClient
 
         list_rules_paginator: ListRulesPaginator = client.get_paginator("list_rules")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import LockStateType, ResourceTypeType
 from .type_defs import ListRulesResponseTypeDef, PaginatorConfigTypeDef, ResourceTagTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListRulesPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -56,13 +49,13 @@
 
     def paginate(
         self,
         *,
         ResourceType: ResourceTypeType,
         ResourceTags: Sequence[ResourceTagTypeDef] = ...,
         LockState: LockStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin.Paginator.ListRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/paginators/#listrulespaginator)
         """
```

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/paginator.pyi` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,28 +16,22 @@
     session = get_session()
     with session.create_client("rbin") as client:
         client: RecycleBinClient
 
         list_rules_paginator: ListRulesPaginator = client.get_paginator("list_rules")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import LockStateType, ResourceTypeType
 from .type_defs import ListRulesResponseTypeDef, PaginatorConfigTypeDef, ResourceTagTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListRulesPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -52,13 +46,13 @@
 
     def paginate(
         self,
         *,
         ResourceType: ResourceTypeType,
         ResourceTags: Sequence[ResourceTagTypeDef] = ...,
         LockState: LockStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin.Paginator.ListRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/paginators/#listrulespaginator)
         """
```

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/type_defs.py` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -27,29 +27,29 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ResourceTagTypeDef",
     "RetentionPeriodTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteRuleRequestRequestTypeDef",
     "GetRuleRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "UnlockDelayTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UnlockRuleRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "ListRulesRequestListRulesPaginateTypeDef",
     "ListRulesRequestRequestTypeDef",
     "RuleSummaryTypeDef",
     "UpdateRuleRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateRuleResponseTypeDef",
-    "ListRulesRequestListRulesPaginateTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "LockConfigurationTypeDef",
     "ListRulesResponseTypeDef",
     "CreateRuleRequestRequestTypeDef",
     "CreateRuleResponseTypeDef",
     "GetRuleResponseTypeDef",
     "LockRuleRequestRequestTypeDef",
     "LockRuleResponseTypeDef",
@@ -87,49 +87,28 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 DeleteRuleRequestRequestTypeDef = TypedDict(
     "DeleteRuleRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
 GetRuleRequestRequestTypeDef = TypedDict(
     "GetRuleRequestRequestTypeDef",
     {
         "Identifier": str,
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
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
@@ -137,14 +116,35 @@
     "UnlockDelayTypeDef",
     {
         "UnlockDelayValue": int,
         "UnlockDelayUnit": Literal["DAYS"],
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
 UnlockRuleRequestRequestTypeDef = TypedDict(
     "UnlockRuleRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
@@ -152,14 +152,38 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+_RequiredListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "_RequiredListRulesRequestListRulesPaginateTypeDef",
+    {
+        "ResourceType": ResourceTypeType,
+    },
+)
+_OptionalListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "_OptionalListRulesRequestListRulesPaginateTypeDef",
+    {
+        "ResourceTags": Sequence[ResourceTagTypeDef],
+        "LockState": LockStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRulesRequestListRulesPaginateTypeDef(
+    _RequiredListRulesRequestListRulesPaginateTypeDef,
+    _OptionalListRulesRequestListRulesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRulesRequestRequestTypeDef = TypedDict(
     "_RequiredListRulesRequestRequestTypeDef",
     {
         "ResourceType": ResourceTypeType,
     },
 )
 _OptionalListRulesRequestRequestTypeDef = TypedDict(
@@ -211,82 +235,58 @@
 
 class UpdateRuleRequestRequestTypeDef(
     _RequiredUpdateRuleRequestRequestTypeDef, _OptionalUpdateRuleRequestRequestTypeDef
 ):
     pass
 
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
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
 UpdateRuleResponseTypeDef = TypedDict(
     "UpdateRuleResponseTypeDef",
     {
         "Identifier": str,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "Description": str,
         "ResourceType": ResourceTypeType,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockState": LockStateType,
         "LockEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "_RequiredListRulesRequestListRulesPaginateTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "ResourceType": ResourceTypeType,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "_OptionalListRulesRequestListRulesPaginateTypeDef",
+
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ResourceTags": Sequence[ResourceTagTypeDef],
-        "LockState": LockStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
-
-class ListRulesRequestListRulesPaginateTypeDef(
-    _RequiredListRulesRequestListRulesPaginateTypeDef,
-    _OptionalListRulesRequestListRulesPaginateTypeDef,
-):
-    pass
-
-
 LockConfigurationTypeDef = TypedDict(
     "LockConfigurationTypeDef",
     {
         "UnlockDelay": UnlockDelayTypeDef,
     },
 )
 
 ListRulesResponseTypeDef = TypedDict(
     "ListRulesResponseTypeDef",
     {
         "Rules": List[RuleSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRuleRequestRequestTypeDef",
     {
         "RetentionPeriod": RetentionPeriodTypeDef,
@@ -319,15 +319,15 @@
         "Description": str,
         "Tags": List[TagTypeDef],
         "ResourceType": ResourceTypeType,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRuleResponseTypeDef = TypedDict(
     "GetRuleResponseTypeDef",
     {
         "Identifier": str,
@@ -335,15 +335,15 @@
         "ResourceType": ResourceTypeType,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
         "LockEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LockRuleRequestRequestTypeDef = TypedDict(
     "LockRuleRequestRequestTypeDef",
     {
         "Identifier": str,
@@ -358,15 +358,15 @@
         "Description": str,
         "ResourceType": ResourceTypeType,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UnlockRuleResponseTypeDef = TypedDict(
     "UnlockRuleResponseTypeDef",
     {
         "Identifier": str,
@@ -374,10 +374,10 @@
         "ResourceType": ResourceTypeType,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
         "LockEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin/type_defs.pyi` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -26,29 +26,29 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ResourceTagTypeDef",
     "RetentionPeriodTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteRuleRequestRequestTypeDef",
     "GetRuleRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "UnlockDelayTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UnlockRuleRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "ListRulesRequestListRulesPaginateTypeDef",
     "ListRulesRequestRequestTypeDef",
     "RuleSummaryTypeDef",
     "UpdateRuleRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "UpdateRuleResponseTypeDef",
-    "ListRulesRequestListRulesPaginateTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "LockConfigurationTypeDef",
     "ListRulesResponseTypeDef",
     "CreateRuleRequestRequestTypeDef",
     "CreateRuleResponseTypeDef",
     "GetRuleResponseTypeDef",
     "LockRuleRequestRequestTypeDef",
     "LockRuleResponseTypeDef",
@@ -84,49 +84,28 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 DeleteRuleRequestRequestTypeDef = TypedDict(
     "DeleteRuleRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
 GetRuleRequestRequestTypeDef = TypedDict(
     "GetRuleRequestRequestTypeDef",
     {
         "Identifier": str,
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
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
@@ -134,14 +113,35 @@
     "UnlockDelayTypeDef",
     {
         "UnlockDelayValue": int,
         "UnlockDelayUnit": Literal["DAYS"],
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
 UnlockRuleRequestRequestTypeDef = TypedDict(
     "UnlockRuleRequestRequestTypeDef",
     {
         "Identifier": str,
     },
 )
 
@@ -149,14 +149,36 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+_RequiredListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "_RequiredListRulesRequestListRulesPaginateTypeDef",
+    {
+        "ResourceType": ResourceTypeType,
+    },
+)
+_OptionalListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "_OptionalListRulesRequestListRulesPaginateTypeDef",
+    {
+        "ResourceTags": Sequence[ResourceTagTypeDef],
+        "LockState": LockStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRulesRequestListRulesPaginateTypeDef(
+    _RequiredListRulesRequestListRulesPaginateTypeDef,
+    _OptionalListRulesRequestListRulesPaginateTypeDef,
+):
+    pass
+
 _RequiredListRulesRequestRequestTypeDef = TypedDict(
     "_RequiredListRulesRequestRequestTypeDef",
     {
         "ResourceType": ResourceTypeType,
     },
 )
 _OptionalListRulesRequestRequestTypeDef = TypedDict(
@@ -204,80 +226,58 @@
 )
 
 class UpdateRuleRequestRequestTypeDef(
     _RequiredUpdateRuleRequestRequestTypeDef, _OptionalUpdateRuleRequestRequestTypeDef
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
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
 UpdateRuleResponseTypeDef = TypedDict(
     "UpdateRuleResponseTypeDef",
     {
         "Identifier": str,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "Description": str,
         "ResourceType": ResourceTypeType,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockState": LockStateType,
         "LockEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "_RequiredListRulesRequestListRulesPaginateTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "ResourceType": ResourceTypeType,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "_OptionalListRulesRequestListRulesPaginateTypeDef",
+
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ResourceTags": Sequence[ResourceTagTypeDef],
-        "LockState": LockStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
-class ListRulesRequestListRulesPaginateTypeDef(
-    _RequiredListRulesRequestListRulesPaginateTypeDef,
-    _OptionalListRulesRequestListRulesPaginateTypeDef,
-):
-    pass
-
 LockConfigurationTypeDef = TypedDict(
     "LockConfigurationTypeDef",
     {
         "UnlockDelay": UnlockDelayTypeDef,
     },
 )
 
 ListRulesResponseTypeDef = TypedDict(
     "ListRulesResponseTypeDef",
     {
         "Rules": List[RuleSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRuleRequestRequestTypeDef",
     {
         "RetentionPeriod": RetentionPeriodTypeDef,
@@ -308,15 +308,15 @@
         "Description": str,
         "Tags": List[TagTypeDef],
         "ResourceType": ResourceTypeType,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRuleResponseTypeDef = TypedDict(
     "GetRuleResponseTypeDef",
     {
         "Identifier": str,
@@ -324,15 +324,15 @@
         "ResourceType": ResourceTypeType,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
         "LockEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LockRuleRequestRequestTypeDef = TypedDict(
     "LockRuleRequestRequestTypeDef",
     {
         "Identifier": str,
@@ -347,15 +347,15 @@
         "Description": str,
         "ResourceType": ResourceTypeType,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UnlockRuleResponseTypeDef = TypedDict(
     "UnlockRuleResponseTypeDef",
     {
         "Identifier": str,
@@ -363,10 +363,10 @@
         "ResourceType": ResourceTypeType,
         "RetentionPeriod": RetentionPeriodTypeDef,
         "ResourceTags": List[ResourceTagTypeDef],
         "Status": RuleStatusType,
         "LockConfiguration": LockConfigurationTypeDef,
         "LockState": LockStateType,
         "LockEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/PKG-INFO` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rbin
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.RecycleBin 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.RecycleBin 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rbin"></a>
 
 # types-aiobotocore-rbin
 
 [![PyPI - types-aiobotocore-rbin](https://img.shields.io/pypi/v/types-aiobotocore-rbin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rbin)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rbin.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rbin)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rbin?color=blue)](https://pypistats.org/packages/types-aiobotocore-rbin)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.RecycleBin 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin)
+[aiobotocore.RecycleBin 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rbin.html#RecycleBin)
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
 [types-aiobotocore-rbin docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rbin/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,29 +320,29 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rbin.type_defs import (
     ResourceTagTypeDef,
     RetentionPeriodTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteRuleRequestRequestTypeDef,
     GetRuleRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     UnlockDelayTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UnlockRuleRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     RuleSummaryTypeDef,
     UpdateRuleRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
     UpdateRuleResponseTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     LockConfigurationTypeDef,
     ListRulesResponseTypeDef,
     CreateRuleRequestRequestTypeDef,
     CreateRuleResponseTypeDef,
     GetRuleResponseTypeDef,
     LockRuleRequestRequestTypeDef,
     LockRuleResponseTypeDef,
@@ -357,43 +357,43 @@
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

### Comparing `types-aiobotocore-rbin-2.5.0.post1/types_aiobotocore_rbin.egg-info/SOURCES.txt` & `types-aiobotocore-rbin-2.5.1/types_aiobotocore_rbin.egg-info/SOURCES.txt`

 * *Files identical despite different names*

