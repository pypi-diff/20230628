# Comparing `tmp/types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-resourcegroupstaggingapi-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-resourcegroupstaggingapi-2.5.1.tar", last modified: Wed Jun 28 01:44:03 2023, max compression
```

## Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1.tar` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.207558 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15202 2023-03-11 12:27:13.203558 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13563 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.207558 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2246 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.203558 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/
--rw-r--r--   0 runner    (1001) docker     (123)     1371 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1370 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1011 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12694 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12673 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8739 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8737 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6416 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6409 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8263 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8258 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:29.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.203558 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15202 2023-03-11 12:27:13.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-03-11 12:27:13.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-03-11 12:27:13.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.506200 types-aiobotocore-resourcegroupstaggingapi-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15211 2023-06-28 01:44:03.506200 types-aiobotocore-resourcegroupstaggingapi-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13578 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:03.506200 types-aiobotocore-resourcegroupstaggingapi-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2240 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.506200 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/
+-rw-r--r--   0 runner    (1001) docker     (123)     1371 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1370 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      999 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12694 2023-06-28 01:39:17.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12673 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8948 2023-06-28 01:39:17.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8946 2023-06-28 01:39:17.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6304 2023-06-28 01:39:17.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6298 2023-06-28 01:39:17.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8285 2023-06-28 01:39:17.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8280 2023-06-28 01:39:17.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:16.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.506200 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15211 2023-06-28 01:44:03.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-06-28 01:44:03.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:03.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 01:44:03.000000 types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/LICENSE` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/PKG-INFO` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resourcegroupstaggingapi
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resourcegroupstaggingapi"></a>
 
 # types-aiobotocore-resourcegroupstaggingapi
 
 [![PyPI - types-aiobotocore-resourcegroupstaggingapi](https://img.shields.io/pypi/v/types-aiobotocore-resourcegroupstaggingapi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resourcegroupstaggingapi)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resourcegroupstaggingapi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resourcegroupstaggingapi)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resourcegroupstaggingapi?color=blue)](https://pypistats.org/packages/types-aiobotocore-resourcegroupstaggingapi)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceGroupsTaggingAPI 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI)
+[aiobotocore.ResourceGroupsTaggingAPI 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI)
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
 [types-aiobotocore-resourcegroupstaggingapi docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,34 +332,34 @@
 `types_aiobotocore_resourcegroupstaggingapi.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_resourcegroupstaggingapi.type_defs import (
     ComplianceDetailsTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeReportCreationOutputTypeDef,
     FailureInfoTypeDef,
-    PaginatorConfigTypeDef,
+    GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef,
     GetComplianceSummaryInputRequestTypeDef,
     SummaryTypeDef,
     TagFilterTypeDef,
+    GetTagKeysInputGetTagKeysPaginateTypeDef,
     GetTagKeysInputRequestTypeDef,
+    GetTagKeysOutputTypeDef,
+    GetTagValuesInputGetTagValuesPaginateTypeDef,
     GetTagValuesInputRequestTypeDef,
+    GetTagValuesOutputTypeDef,
+    PaginatorConfigTypeDef,
     TagTypeDef,
+    ResponseMetadataTypeDef,
     StartReportCreationInputRequestTypeDef,
     TagResourcesInputRequestTypeDef,
     UntagResourcesInputRequestTypeDef,
-    DescribeReportCreationOutputTypeDef,
-    GetTagKeysOutputTypeDef,
-    GetTagValuesOutputTypeDef,
     TagResourcesOutputTypeDef,
     UntagResourcesOutputTypeDef,
-    GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef,
-    GetTagKeysInputGetTagKeysPaginateTypeDef,
-    GetTagValuesInputGetTagValuesPaginateTypeDef,
     GetComplianceSummaryOutputTypeDef,
     GetResourcesInputGetResourcesPaginateTypeDef,
     GetResourcesInputRequestTypeDef,
     ResourceTagMappingTypeDef,
     GetResourcesOutputTypeDef,
 )
 
@@ -371,43 +371,43 @@
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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/README.md` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-resourcegroupstaggingapi"></a>
 
 # types-aiobotocore-resourcegroupstaggingapi
 
 [![PyPI - types-aiobotocore-resourcegroupstaggingapi](https://img.shields.io/pypi/v/types-aiobotocore-resourcegroupstaggingapi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resourcegroupstaggingapi)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resourcegroupstaggingapi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resourcegroupstaggingapi)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resourcegroupstaggingapi?color=blue)](https://pypistats.org/packages/types-aiobotocore-resourcegroupstaggingapi)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceGroupsTaggingAPI 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI)
+[aiobotocore.ResourceGroupsTaggingAPI 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI)
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
 [types-aiobotocore-resourcegroupstaggingapi docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,34 +299,34 @@
 `types_aiobotocore_resourcegroupstaggingapi.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_resourcegroupstaggingapi.type_defs import (
     ComplianceDetailsTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeReportCreationOutputTypeDef,
     FailureInfoTypeDef,
-    PaginatorConfigTypeDef,
+    GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef,
     GetComplianceSummaryInputRequestTypeDef,
     SummaryTypeDef,
     TagFilterTypeDef,
+    GetTagKeysInputGetTagKeysPaginateTypeDef,
     GetTagKeysInputRequestTypeDef,
+    GetTagKeysOutputTypeDef,
+    GetTagValuesInputGetTagValuesPaginateTypeDef,
     GetTagValuesInputRequestTypeDef,
+    GetTagValuesOutputTypeDef,
+    PaginatorConfigTypeDef,
     TagTypeDef,
+    ResponseMetadataTypeDef,
     StartReportCreationInputRequestTypeDef,
     TagResourcesInputRequestTypeDef,
     UntagResourcesInputRequestTypeDef,
-    DescribeReportCreationOutputTypeDef,
-    GetTagKeysOutputTypeDef,
-    GetTagValuesOutputTypeDef,
     TagResourcesOutputTypeDef,
     UntagResourcesOutputTypeDef,
-    GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef,
-    GetTagKeysInputGetTagKeysPaginateTypeDef,
-    GetTagValuesInputGetTagValuesPaginateTypeDef,
     GetComplianceSummaryOutputTypeDef,
     GetResourcesInputGetResourcesPaginateTypeDef,
     GetResourcesInputRequestTypeDef,
     ResourceTagMappingTypeDef,
     GetResourcesOutputTypeDef,
 )
 
@@ -338,43 +338,43 @@
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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/setup.py` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-resourcegroupstaggingapi.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-resourcegroupstaggingapi",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_resourcegroupstaggingapi"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/",
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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/__init__.py` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/__init__.pyi` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/__main__.py` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/__main__.py`

 * *Files 8% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI\nOther"
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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/client.py` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/client.pyi` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/literals.py` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -101,14 +101,15 @@
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
@@ -187,14 +188,15 @@
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
@@ -205,14 +207,15 @@
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
@@ -248,14 +251,15 @@
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
@@ -274,16 +278,19 @@
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
@@ -367,15 +374,17 @@
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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/literals.pyi` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/literals.pyi`

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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/paginator.py` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,36 +22,29 @@
 
         get_compliance_summary_paginator: GetComplianceSummaryPaginator = client.get_paginator("get_compliance_summary")
         get_resources_paginator: GetResourcesPaginator = client.get_paginator("get_resources")
         get_tag_keys_paginator: GetTagKeysPaginator = client.get_paginator("get_tag_keys")
         get_tag_values_paginator: GetTagValuesPaginator = client.get_paginator("get_tag_values")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import GroupByAttributeType
 from .type_defs import (
     GetComplianceSummaryOutputTypeDef,
     GetResourcesOutputTypeDef,
     GetTagKeysOutputTypeDef,
     GetTagValuesOutputTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetComplianceSummaryPaginator",
     "GetResourcesPaginator",
     "GetTagKeysPaginator",
     "GetTagValuesPaginator",
 )
 
@@ -76,15 +69,15 @@
         self,
         *,
         TargetIdFilters: Sequence[str] = ...,
         RegionFilters: Sequence[str] = ...,
         ResourceTypeFilters: Sequence[str] = ...,
         TagKeyFilters: Sequence[str] = ...,
         GroupBy: Sequence[GroupByAttributeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetComplianceSummaryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetComplianceSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#getcompliancesummarypaginator)
         """
 
 
@@ -99,43 +92,43 @@
         *,
         TagFilters: Sequence[TagFilterTypeDef] = ...,
         TagsPerPage: int = ...,
         ResourceTypeFilters: Sequence[str] = ...,
         IncludeComplianceDetails: bool = ...,
         ExcludeCompliantResources: bool = ...,
         ResourceARNList: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#getresourcespaginator)
         """
 
 
 class GetTagKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagkeyspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTagKeysOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagkeyspaginator)
         """
 
 
 class GetTagValuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagValues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagvaluespaginator)
     """
 
     def paginate(
-        self, *, Key: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Key: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTagValuesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagvaluespaginator)
         """
```

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/paginator.pyi` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,35 +22,29 @@
 
         get_compliance_summary_paginator: GetComplianceSummaryPaginator = client.get_paginator("get_compliance_summary")
         get_resources_paginator: GetResourcesPaginator = client.get_paginator("get_resources")
         get_tag_keys_paginator: GetTagKeysPaginator = client.get_paginator("get_tag_keys")
         get_tag_values_paginator: GetTagValuesPaginator = client.get_paginator("get_tag_values")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import GroupByAttributeType
 from .type_defs import (
     GetComplianceSummaryOutputTypeDef,
     GetResourcesOutputTypeDef,
     GetTagKeysOutputTypeDef,
     GetTagValuesOutputTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetComplianceSummaryPaginator",
     "GetResourcesPaginator",
     "GetTagKeysPaginator",
     "GetTagValuesPaginator",
 )
 
@@ -72,15 +66,15 @@
         self,
         *,
         TargetIdFilters: Sequence[str] = ...,
         RegionFilters: Sequence[str] = ...,
         ResourceTypeFilters: Sequence[str] = ...,
         TagKeyFilters: Sequence[str] = ...,
         GroupBy: Sequence[GroupByAttributeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetComplianceSummaryOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetComplianceSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#getcompliancesummarypaginator)
         """
 
 class GetResourcesPaginator(AioPaginator):
@@ -94,41 +88,41 @@
         *,
         TagFilters: Sequence[TagFilterTypeDef] = ...,
         TagsPerPage: int = ...,
         ResourceTypeFilters: Sequence[str] = ...,
         IncludeComplianceDetails: bool = ...,
         ExcludeCompliantResources: bool = ...,
         ResourceARNList: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#getresourcespaginator)
         """
 
 class GetTagKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagkeyspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTagKeysOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagkeyspaginator)
         """
 
 class GetTagValuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagValues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagvaluespaginator)
     """
 
     def paginate(
-        self, *, Key: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Key: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTagValuesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI.Paginator.GetTagValues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/paginators/#gettagvaluespaginator)
         """
```

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/type_defs.py` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/type_defs.py`

 * *Files 11% similar despite different names*

```diff
@@ -20,34 +20,34 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ComplianceDetailsTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeReportCreationOutputTypeDef",
     "FailureInfoTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
     "GetComplianceSummaryInputRequestTypeDef",
     "SummaryTypeDef",
     "TagFilterTypeDef",
+    "GetTagKeysInputGetTagKeysPaginateTypeDef",
     "GetTagKeysInputRequestTypeDef",
+    "GetTagKeysOutputTypeDef",
+    "GetTagValuesInputGetTagValuesPaginateTypeDef",
     "GetTagValuesInputRequestTypeDef",
+    "GetTagValuesOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "TagTypeDef",
+    "ResponseMetadataTypeDef",
     "StartReportCreationInputRequestTypeDef",
     "TagResourcesInputRequestTypeDef",
     "UntagResourcesInputRequestTypeDef",
-    "DescribeReportCreationOutputTypeDef",
-    "GetTagKeysOutputTypeDef",
-    "GetTagValuesOutputTypeDef",
     "TagResourcesOutputTypeDef",
     "UntagResourcesOutputTypeDef",
-    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
-    "GetTagKeysInputGetTagKeysPaginateTypeDef",
-    "GetTagValuesInputGetTagValuesPaginateTypeDef",
     "GetComplianceSummaryOutputTypeDef",
     "GetResourcesInputGetResourcesPaginateTypeDef",
     "GetResourcesInputRequestTypeDef",
     "ResourceTagMappingTypeDef",
     "GetResourcesOutputTypeDef",
 )
 
@@ -57,41 +57,43 @@
         "NoncompliantKeys": List[str],
         "KeysWithNoncompliantValues": List[str],
         "ComplianceStatus": bool,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DescribeReportCreationOutputTypeDef = TypedDict(
+    "DescribeReportCreationOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Status": str,
+        "S3Location": str,
+        "ErrorMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailureInfoTypeDef = TypedDict(
     "FailureInfoTypeDef",
     {
         "StatusCode": int,
         "ErrorCode": ErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef = TypedDict(
+    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TargetIdFilters": Sequence[str],
+        "RegionFilters": Sequence[str],
+        "ResourceTypeFilters": Sequence[str],
+        "TagKeyFilters": Sequence[str],
+        "GroupBy": Sequence[GroupByAttributeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetComplianceSummaryInputRequestTypeDef = TypedDict(
     "GetComplianceSummaryInputRequestTypeDef",
     {
@@ -124,22 +126,61 @@
     {
         "Key": str,
         "Values": Sequence[str],
     },
     total=False,
 )
 
+GetTagKeysInputGetTagKeysPaginateTypeDef = TypedDict(
+    "GetTagKeysInputGetTagKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetTagKeysInputRequestTypeDef = TypedDict(
     "GetTagKeysInputRequestTypeDef",
     {
         "PaginationToken": str,
     },
     total=False,
 )
 
+GetTagKeysOutputTypeDef = TypedDict(
+    "GetTagKeysOutputTypeDef",
+    {
+        "PaginationToken": str,
+        "TagKeys": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
+    "_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef",
+    {
+        "Key": str,
+    },
+)
+_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
+    "_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetTagValuesInputGetTagValuesPaginateTypeDef(
+    _RequiredGetTagValuesInputGetTagValuesPaginateTypeDef,
+    _OptionalGetTagValuesInputGetTagValuesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetTagValuesInputRequestTypeDef = TypedDict(
     "_RequiredGetTagValuesInputRequestTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalGetTagValuesInputRequestTypeDef = TypedDict(
@@ -153,22 +194,52 @@
 
 class GetTagValuesInputRequestTypeDef(
     _RequiredGetTagValuesInputRequestTypeDef, _OptionalGetTagValuesInputRequestTypeDef
 ):
     pass
 
 
+GetTagValuesOutputTypeDef = TypedDict(
+    "GetTagValuesOutputTypeDef",
+    {
+        "PaginationToken": str,
+        "TagValues": List[str],
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 StartReportCreationInputRequestTypeDef = TypedDict(
     "StartReportCreationInputRequestTypeDef",
     {
         "S3Bucket": str,
     },
 )
 
@@ -184,120 +255,49 @@
     "UntagResourcesInputRequestTypeDef",
     {
         "ResourceARNList": Sequence[str],
         "TagKeys": Sequence[str],
     },
 )
 
-DescribeReportCreationOutputTypeDef = TypedDict(
-    "DescribeReportCreationOutputTypeDef",
-    {
-        "Status": str,
-        "S3Location": str,
-        "ErrorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagKeysOutputTypeDef = TypedDict(
-    "GetTagKeysOutputTypeDef",
-    {
-        "PaginationToken": str,
-        "TagKeys": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagValuesOutputTypeDef = TypedDict(
-    "GetTagValuesOutputTypeDef",
-    {
-        "PaginationToken": str,
-        "TagValues": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 TagResourcesOutputTypeDef = TypedDict(
     "TagResourcesOutputTypeDef",
     {
         "FailedResourcesMap": Dict[str, FailureInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourcesOutputTypeDef = TypedDict(
     "UntagResourcesOutputTypeDef",
     {
         "FailedResourcesMap": Dict[str, FailureInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef = TypedDict(
-    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
-    {
-        "TargetIdFilters": Sequence[str],
-        "RegionFilters": Sequence[str],
-        "ResourceTypeFilters": Sequence[str],
-        "TagKeyFilters": Sequence[str],
-        "GroupBy": Sequence[GroupByAttributeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetTagKeysInputGetTagKeysPaginateTypeDef = TypedDict(
-    "GetTagKeysInputGetTagKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
-    "_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef",
-    {
-        "Key": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
-    "_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetTagValuesInputGetTagValuesPaginateTypeDef(
-    _RequiredGetTagValuesInputGetTagValuesPaginateTypeDef,
-    _OptionalGetTagValuesInputGetTagValuesPaginateTypeDef,
-):
-    pass
-
 
 GetComplianceSummaryOutputTypeDef = TypedDict(
     "GetComplianceSummaryOutputTypeDef",
     {
         "SummaryList": List[SummaryTypeDef],
         "PaginationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcesInputGetResourcesPaginateTypeDef = TypedDict(
     "GetResourcesInputGetResourcesPaginateTypeDef",
     {
         "TagFilters": Sequence[TagFilterTypeDef],
         "TagsPerPage": int,
         "ResourceTypeFilters": Sequence[str],
         "IncludeComplianceDetails": bool,
         "ExcludeCompliantResources": bool,
         "ResourceARNList": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetResourcesInputRequestTypeDef = TypedDict(
     "GetResourcesInputRequestTypeDef",
     {
@@ -324,10 +324,10 @@
 )
 
 GetResourcesOutputTypeDef = TypedDict(
     "GetResourcesOutputTypeDef",
     {
         "PaginationToken": str,
         "ResourceTagMappingList": List[ResourceTagMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi/type_defs.pyi` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi/type_defs.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -19,34 +19,34 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ComplianceDetailsTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeReportCreationOutputTypeDef",
     "FailureInfoTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
     "GetComplianceSummaryInputRequestTypeDef",
     "SummaryTypeDef",
     "TagFilterTypeDef",
+    "GetTagKeysInputGetTagKeysPaginateTypeDef",
     "GetTagKeysInputRequestTypeDef",
+    "GetTagKeysOutputTypeDef",
+    "GetTagValuesInputGetTagValuesPaginateTypeDef",
     "GetTagValuesInputRequestTypeDef",
+    "GetTagValuesOutputTypeDef",
+    "PaginatorConfigTypeDef",
     "TagTypeDef",
+    "ResponseMetadataTypeDef",
     "StartReportCreationInputRequestTypeDef",
     "TagResourcesInputRequestTypeDef",
     "UntagResourcesInputRequestTypeDef",
-    "DescribeReportCreationOutputTypeDef",
-    "GetTagKeysOutputTypeDef",
-    "GetTagValuesOutputTypeDef",
     "TagResourcesOutputTypeDef",
     "UntagResourcesOutputTypeDef",
-    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
-    "GetTagKeysInputGetTagKeysPaginateTypeDef",
-    "GetTagValuesInputGetTagValuesPaginateTypeDef",
     "GetComplianceSummaryOutputTypeDef",
     "GetResourcesInputGetResourcesPaginateTypeDef",
     "GetResourcesInputRequestTypeDef",
     "ResourceTagMappingTypeDef",
     "GetResourcesOutputTypeDef",
 )
 
@@ -56,41 +56,43 @@
         "NoncompliantKeys": List[str],
         "KeysWithNoncompliantValues": List[str],
         "ComplianceStatus": bool,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+DescribeReportCreationOutputTypeDef = TypedDict(
+    "DescribeReportCreationOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Status": str,
+        "S3Location": str,
+        "ErrorMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailureInfoTypeDef = TypedDict(
     "FailureInfoTypeDef",
     {
         "StatusCode": int,
         "ErrorCode": ErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef = TypedDict(
+    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TargetIdFilters": Sequence[str],
+        "RegionFilters": Sequence[str],
+        "ResourceTypeFilters": Sequence[str],
+        "TagKeyFilters": Sequence[str],
+        "GroupBy": Sequence[GroupByAttributeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetComplianceSummaryInputRequestTypeDef = TypedDict(
     "GetComplianceSummaryInputRequestTypeDef",
     {
@@ -123,22 +125,59 @@
     {
         "Key": str,
         "Values": Sequence[str],
     },
     total=False,
 )
 
+GetTagKeysInputGetTagKeysPaginateTypeDef = TypedDict(
+    "GetTagKeysInputGetTagKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetTagKeysInputRequestTypeDef = TypedDict(
     "GetTagKeysInputRequestTypeDef",
     {
         "PaginationToken": str,
     },
     total=False,
 )
 
+GetTagKeysOutputTypeDef = TypedDict(
+    "GetTagKeysOutputTypeDef",
+    {
+        "PaginationToken": str,
+        "TagKeys": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
+    "_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef",
+    {
+        "Key": str,
+    },
+)
+_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
+    "_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetTagValuesInputGetTagValuesPaginateTypeDef(
+    _RequiredGetTagValuesInputGetTagValuesPaginateTypeDef,
+    _OptionalGetTagValuesInputGetTagValuesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetTagValuesInputRequestTypeDef = TypedDict(
     "_RequiredGetTagValuesInputRequestTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalGetTagValuesInputRequestTypeDef = TypedDict(
@@ -150,22 +189,52 @@
 )
 
 class GetTagValuesInputRequestTypeDef(
     _RequiredGetTagValuesInputRequestTypeDef, _OptionalGetTagValuesInputRequestTypeDef
 ):
     pass
 
+GetTagValuesOutputTypeDef = TypedDict(
+    "GetTagValuesOutputTypeDef",
+    {
+        "PaginationToken": str,
+        "TagValues": List[str],
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 StartReportCreationInputRequestTypeDef = TypedDict(
     "StartReportCreationInputRequestTypeDef",
     {
         "S3Bucket": str,
     },
 )
 
@@ -181,118 +250,49 @@
     "UntagResourcesInputRequestTypeDef",
     {
         "ResourceARNList": Sequence[str],
         "TagKeys": Sequence[str],
     },
 )
 
-DescribeReportCreationOutputTypeDef = TypedDict(
-    "DescribeReportCreationOutputTypeDef",
-    {
-        "Status": str,
-        "S3Location": str,
-        "ErrorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagKeysOutputTypeDef = TypedDict(
-    "GetTagKeysOutputTypeDef",
-    {
-        "PaginationToken": str,
-        "TagKeys": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagValuesOutputTypeDef = TypedDict(
-    "GetTagValuesOutputTypeDef",
-    {
-        "PaginationToken": str,
-        "TagValues": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 TagResourcesOutputTypeDef = TypedDict(
     "TagResourcesOutputTypeDef",
     {
         "FailedResourcesMap": Dict[str, FailureInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourcesOutputTypeDef = TypedDict(
     "UntagResourcesOutputTypeDef",
     {
         "FailedResourcesMap": Dict[str, FailureInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef = TypedDict(
-    "GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef",
-    {
-        "TargetIdFilters": Sequence[str],
-        "RegionFilters": Sequence[str],
-        "ResourceTypeFilters": Sequence[str],
-        "TagKeyFilters": Sequence[str],
-        "GroupBy": Sequence[GroupByAttributeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetTagKeysInputGetTagKeysPaginateTypeDef = TypedDict(
-    "GetTagKeysInputGetTagKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
-    "_RequiredGetTagValuesInputGetTagValuesPaginateTypeDef",
-    {
-        "Key": str,
-    },
-)
-_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef = TypedDict(
-    "_OptionalGetTagValuesInputGetTagValuesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetTagValuesInputGetTagValuesPaginateTypeDef(
-    _RequiredGetTagValuesInputGetTagValuesPaginateTypeDef,
-    _OptionalGetTagValuesInputGetTagValuesPaginateTypeDef,
-):
-    pass
-
 GetComplianceSummaryOutputTypeDef = TypedDict(
     "GetComplianceSummaryOutputTypeDef",
     {
         "SummaryList": List[SummaryTypeDef],
         "PaginationToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourcesInputGetResourcesPaginateTypeDef = TypedDict(
     "GetResourcesInputGetResourcesPaginateTypeDef",
     {
         "TagFilters": Sequence[TagFilterTypeDef],
         "TagsPerPage": int,
         "ResourceTypeFilters": Sequence[str],
         "IncludeComplianceDetails": bool,
         "ExcludeCompliantResources": bool,
         "ResourceARNList": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetResourcesInputRequestTypeDef = TypedDict(
     "GetResourcesInputRequestTypeDef",
     {
@@ -319,10 +319,10 @@
 )
 
 GetResourcesOutputTypeDef = TypedDict(
     "GetResourcesOutputTypeDef",
     {
         "PaginationToken": str,
         "ResourceTagMappingList": List[ResourceTagMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/PKG-INFO` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resourcegroupstaggingapi
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResourceGroupsTaggingAPI 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resourcegroupstaggingapi"></a>
 
 # types-aiobotocore-resourcegroupstaggingapi
 
 [![PyPI - types-aiobotocore-resourcegroupstaggingapi](https://img.shields.io/pypi/v/types-aiobotocore-resourcegroupstaggingapi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resourcegroupstaggingapi)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resourcegroupstaggingapi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resourcegroupstaggingapi)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resourcegroupstaggingapi?color=blue)](https://pypistats.org/packages/types-aiobotocore-resourcegroupstaggingapi)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceGroupsTaggingAPI 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI)
+[aiobotocore.ResourceGroupsTaggingAPI 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html#ResourceGroupsTaggingAPI)
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
 [types-aiobotocore-resourcegroupstaggingapi docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resourcegroupstaggingapi/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,34 +332,34 @@
 `types_aiobotocore_resourcegroupstaggingapi.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_resourcegroupstaggingapi.type_defs import (
     ComplianceDetailsTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeReportCreationOutputTypeDef,
     FailureInfoTypeDef,
-    PaginatorConfigTypeDef,
+    GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef,
     GetComplianceSummaryInputRequestTypeDef,
     SummaryTypeDef,
     TagFilterTypeDef,
+    GetTagKeysInputGetTagKeysPaginateTypeDef,
     GetTagKeysInputRequestTypeDef,
+    GetTagKeysOutputTypeDef,
+    GetTagValuesInputGetTagValuesPaginateTypeDef,
     GetTagValuesInputRequestTypeDef,
+    GetTagValuesOutputTypeDef,
+    PaginatorConfigTypeDef,
     TagTypeDef,
+    ResponseMetadataTypeDef,
     StartReportCreationInputRequestTypeDef,
     TagResourcesInputRequestTypeDef,
     UntagResourcesInputRequestTypeDef,
-    DescribeReportCreationOutputTypeDef,
-    GetTagKeysOutputTypeDef,
-    GetTagValuesOutputTypeDef,
     TagResourcesOutputTypeDef,
     UntagResourcesOutputTypeDef,
-    GetComplianceSummaryInputGetComplianceSummaryPaginateTypeDef,
-    GetTagKeysInputGetTagKeysPaginateTypeDef,
-    GetTagValuesInputGetTagValuesPaginateTypeDef,
     GetComplianceSummaryOutputTypeDef,
     GetResourcesInputGetResourcesPaginateTypeDef,
     GetResourcesInputRequestTypeDef,
     ResourceTagMappingTypeDef,
     GetResourcesOutputTypeDef,
 )
 
@@ -371,43 +371,43 @@
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

### Comparing `types-aiobotocore-resourcegroupstaggingapi-2.5.0.post1/types_aiobotocore_resourcegroupstaggingapi.egg-info/SOURCES.txt` & `types-aiobotocore-resourcegroupstaggingapi-2.5.1/types_aiobotocore_resourcegroupstaggingapi.egg-info/SOURCES.txt`

 * *Files identical despite different names*

