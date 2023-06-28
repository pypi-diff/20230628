# Comparing `tmp/types-aiobotocore-resource-groups-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-resource-groups-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-resource-groups-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-resource-groups-2.5.1.tar", last modified: Wed Jun 28 01:44:03 2023, max compression
```

## Comparing `types-aiobotocore-resource-groups-2.5.0.post1.tar` & `types-aiobotocore-resource-groups-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.191558 types-aiobotocore-resource-groups-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15671 2023-03-11 12:27:13.191558 types-aiobotocore-resource-groups-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14069 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.191558 types-aiobotocore-resource-groups-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2179 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.183557 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/
--rw-r--r--   0 runner    (1001) docker     (123)     1101 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1100 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      973 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16991 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16961 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9212 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9210 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4734 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4728 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    15880 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    15865 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:28.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.191558 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15671 2023-03-11 12:27:13.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:27:13.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:27:13.000000 types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.494200 types-aiobotocore-resource-groups-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15671 2023-06-28 01:44:03.490200 types-aiobotocore-resource-groups-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14075 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:03.494200 types-aiobotocore-resource-groups-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.490200 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/
+-rw-r--r--   0 runner    (1001) docker     (123)     1101 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1100 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16991 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16961 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9421 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9419 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4644 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4639 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    15920 2023-06-28 01:39:16.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15905 2023-06-28 01:39:14.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:13.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.490200 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15671 2023-06-28 01:44:03.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:44:03.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:03.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:44:03.000000 types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/LICENSE` & `types-aiobotocore-resource-groups-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/PKG-INFO` & `types-aiobotocore-resource-groups-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resource-groups
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResourceGroups 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResourceGroups 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resource-groups"></a>
 
 # types-aiobotocore-resource-groups
 
 [![PyPI - types-aiobotocore-resource-groups](https://img.shields.io/pypi/v/types-aiobotocore-resource-groups.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-groups)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resource-groups.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-groups)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resource-groups?color=blue)](https://pypistats.org/packages/types-aiobotocore-resource-groups)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceGroups 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups)
+[aiobotocore.ResourceGroups 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups)
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
 [types-aiobotocore-resource-groups docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/).
 
 See how it helps to find and fix potential bugs:
 
@@ -335,54 +335,54 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resource_groups.type_defs import (
     AccountSettingsTypeDef,
     ResourceQueryTypeDef,
     GroupTypeDef,
-    ResponseMetadataTypeDef,
     DeleteGroupInputRequestTypeDef,
     FailedResourceTypeDef,
     GetGroupConfigurationInputRequestTypeDef,
     GetGroupInputRequestTypeDef,
     GetGroupQueryInputRequestTypeDef,
     GetTagsInputRequestTypeDef,
+    GetTagsOutputTypeDef,
     GroupConfigurationParameterTypeDef,
     GroupFilterTypeDef,
     GroupIdentifierTypeDef,
     GroupResourcesInputRequestTypeDef,
     PendingResourceTypeDef,
-    PaginatorConfigTypeDef,
     ResourceFilterTypeDef,
     ResourceIdentifierTypeDef,
     ResourceStatusTypeDef,
     QueryErrorTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagInputRequestTypeDef,
+    TagOutputTypeDef,
     UngroupResourcesInputRequestTypeDef,
     UntagInputRequestTypeDef,
+    UntagOutputTypeDef,
     UpdateAccountSettingsInputRequestTypeDef,
     UpdateGroupInputRequestTypeDef,
+    GetAccountSettingsOutputTypeDef,
+    UpdateAccountSettingsOutputTypeDef,
     GroupQueryTypeDef,
     SearchResourcesInputRequestTypeDef,
+    SearchResourcesInputSearchResourcesPaginateTypeDef,
     UpdateGroupQueryInputRequestTypeDef,
     DeleteGroupOutputTypeDef,
-    GetAccountSettingsOutputTypeDef,
     GetGroupOutputTypeDef,
-    GetTagsOutputTypeDef,
-    TagOutputTypeDef,
-    UntagOutputTypeDef,
-    UpdateAccountSettingsOutputTypeDef,
     UpdateGroupOutputTypeDef,
     GroupConfigurationItemTypeDef,
+    ListGroupsInputListGroupsPaginateTypeDef,
     ListGroupsInputRequestTypeDef,
     ListGroupsOutputTypeDef,
     GroupResourcesOutputTypeDef,
     UngroupResourcesOutputTypeDef,
-    ListGroupsInputListGroupsPaginateTypeDef,
-    SearchResourcesInputSearchResourcesPaginateTypeDef,
     ListGroupResourcesInputListGroupResourcesPaginateTypeDef,
     ListGroupResourcesInputRequestTypeDef,
     ListGroupResourcesItemTypeDef,
     SearchResourcesOutputTypeDef,
     GetGroupQueryOutputTypeDef,
     UpdateGroupQueryOutputTypeDef,
     CreateGroupInputRequestTypeDef,
@@ -401,43 +401,43 @@
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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/README.md` & `types-aiobotocore-resource-groups-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-resource-groups"></a>
 
 # types-aiobotocore-resource-groups
 
 [![PyPI - types-aiobotocore-resource-groups](https://img.shields.io/pypi/v/types-aiobotocore-resource-groups.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-groups)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resource-groups.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-groups)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resource-groups?color=blue)](https://pypistats.org/packages/types-aiobotocore-resource-groups)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceGroups 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups)
+[aiobotocore.ResourceGroups 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups)
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
 [types-aiobotocore-resource-groups docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/).
 
 See how it helps to find and fix potential bugs:
 
@@ -302,54 +302,54 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resource_groups.type_defs import (
     AccountSettingsTypeDef,
     ResourceQueryTypeDef,
     GroupTypeDef,
-    ResponseMetadataTypeDef,
     DeleteGroupInputRequestTypeDef,
     FailedResourceTypeDef,
     GetGroupConfigurationInputRequestTypeDef,
     GetGroupInputRequestTypeDef,
     GetGroupQueryInputRequestTypeDef,
     GetTagsInputRequestTypeDef,
+    GetTagsOutputTypeDef,
     GroupConfigurationParameterTypeDef,
     GroupFilterTypeDef,
     GroupIdentifierTypeDef,
     GroupResourcesInputRequestTypeDef,
     PendingResourceTypeDef,
-    PaginatorConfigTypeDef,
     ResourceFilterTypeDef,
     ResourceIdentifierTypeDef,
     ResourceStatusTypeDef,
     QueryErrorTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagInputRequestTypeDef,
+    TagOutputTypeDef,
     UngroupResourcesInputRequestTypeDef,
     UntagInputRequestTypeDef,
+    UntagOutputTypeDef,
     UpdateAccountSettingsInputRequestTypeDef,
     UpdateGroupInputRequestTypeDef,
+    GetAccountSettingsOutputTypeDef,
+    UpdateAccountSettingsOutputTypeDef,
     GroupQueryTypeDef,
     SearchResourcesInputRequestTypeDef,
+    SearchResourcesInputSearchResourcesPaginateTypeDef,
     UpdateGroupQueryInputRequestTypeDef,
     DeleteGroupOutputTypeDef,
-    GetAccountSettingsOutputTypeDef,
     GetGroupOutputTypeDef,
-    GetTagsOutputTypeDef,
-    TagOutputTypeDef,
-    UntagOutputTypeDef,
-    UpdateAccountSettingsOutputTypeDef,
     UpdateGroupOutputTypeDef,
     GroupConfigurationItemTypeDef,
+    ListGroupsInputListGroupsPaginateTypeDef,
     ListGroupsInputRequestTypeDef,
     ListGroupsOutputTypeDef,
     GroupResourcesOutputTypeDef,
     UngroupResourcesOutputTypeDef,
-    ListGroupsInputListGroupsPaginateTypeDef,
-    SearchResourcesInputSearchResourcesPaginateTypeDef,
     ListGroupResourcesInputListGroupResourcesPaginateTypeDef,
     ListGroupResourcesInputRequestTypeDef,
     ListGroupResourcesItemTypeDef,
     SearchResourcesOutputTypeDef,
     GetGroupQueryOutputTypeDef,
     UpdateGroupQueryOutputTypeDef,
     CreateGroupInputRequestTypeDef,
@@ -368,43 +368,43 @@
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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/setup.py` & `types-aiobotocore-resource-groups-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-resource-groups.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-resource-groups",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_resource_groups"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ResourceGroups 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ResourceGroups 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/"
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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/__init__.py` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/__init__.pyi` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/__main__.py` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/__main__.py`

 * *Files 22% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ResourceGroups 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ResourceGroups 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups\nOther"
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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/client.py` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/client.pyi` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/literals.py` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "GroupConfigurationStatusType",
     "GroupFilterNameType",
     "GroupLifecycleEventsDesiredStatusType",
     "GroupLifecycleEventsStatusType",
     "ListGroupResourcesPaginatorName",
     "ListGroupsPaginatorName",
@@ -34,15 +33,14 @@
     "ResourceGroupsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 GroupConfigurationStatusType = Literal["UPDATE_COMPLETE", "UPDATE_FAILED", "UPDATING"]
 GroupFilterNameType = Literal["configuration-type", "resource-type"]
 GroupLifecycleEventsDesiredStatusType = Literal["ACTIVE", "INACTIVE"]
 GroupLifecycleEventsStatusType = Literal["ACTIVE", "ERROR", "INACTIVE", "IN_PROGRESS"]
 ListGroupResourcesPaginatorName = Literal["list_group_resources"]
 ListGroupsPaginatorName = Literal["list_groups"]
 QueryErrorCodeType = Literal[
@@ -113,14 +111,15 @@
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
@@ -199,14 +198,15 @@
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
@@ -217,14 +217,15 @@
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
@@ -260,14 +261,15 @@
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
@@ -286,16 +288,19 @@
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
@@ -379,15 +384,17 @@
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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/literals.pyi` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "GroupConfigurationStatusType",
     "GroupFilterNameType",
     "GroupLifecycleEventsDesiredStatusType",
     "GroupLifecycleEventsStatusType",
     "ListGroupResourcesPaginatorName",
     "ListGroupsPaginatorName",
@@ -33,14 +34,15 @@
     "ResourceGroupsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 GroupConfigurationStatusType = Literal["UPDATE_COMPLETE", "UPDATE_FAILED", "UPDATING"]
 GroupFilterNameType = Literal["configuration-type", "resource-type"]
 GroupLifecycleEventsDesiredStatusType = Literal["ACTIVE", "INACTIVE"]
 GroupLifecycleEventsStatusType = Literal["ACTIVE", "ERROR", "INACTIVE", "IN_PROGRESS"]
 ListGroupResourcesPaginatorName = Literal["list_group_resources"]
 ListGroupsPaginatorName = Literal["list_groups"]
 QueryErrorCodeType = Literal[
@@ -111,14 +113,15 @@
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
@@ -197,14 +200,15 @@
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
@@ -215,14 +219,15 @@
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
@@ -258,14 +263,15 @@
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
@@ -284,16 +290,19 @@
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
@@ -377,15 +386,17 @@
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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/paginator.py` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/paginator.py`

 * *Files 10% similar despite different names*

```diff
@@ -20,36 +20,29 @@
         client: ResourceGroupsClient
 
         list_group_resources_paginator: ListGroupResourcesPaginator = client.get_paginator("list_group_resources")
         list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
         search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GroupFilterTypeDef,
     ListGroupResourcesOutputTypeDef,
     ListGroupsOutputTypeDef,
     PaginatorConfigTypeDef,
     ResourceFilterTypeDef,
     ResourceQueryTypeDef,
     SearchResourcesOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListGroupResourcesPaginator", "ListGroupsPaginator", "SearchResourcesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -67,15 +60,15 @@
 
     def paginate(
         self,
         *,
         GroupName: str = ...,
         Group: str = ...,
         Filters: Sequence[ResourceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.ListGroupResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#listgroupresourcespaginator)
         """
 
 
@@ -85,28 +78,31 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#listgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[GroupFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#listgroupspaginator)
         """
 
 
 class SearchResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.SearchResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#searchresourcespaginator)
     """
 
     def paginate(
-        self, *, ResourceQuery: ResourceQueryTypeDef, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ResourceQuery: ResourceQueryTypeDef,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.SearchResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#searchresourcespaginator)
         """
```

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/paginator.pyi` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -20,35 +20,29 @@
         client: ResourceGroupsClient
 
         list_group_resources_paginator: ListGroupResourcesPaginator = client.get_paginator("list_group_resources")
         list_groups_paginator: ListGroupsPaginator = client.get_paginator("list_groups")
         search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GroupFilterTypeDef,
     ListGroupResourcesOutputTypeDef,
     ListGroupsOutputTypeDef,
     PaginatorConfigTypeDef,
     ResourceFilterTypeDef,
     ResourceQueryTypeDef,
     SearchResourcesOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListGroupResourcesPaginator", "ListGroupsPaginator", "SearchResourcesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -63,15 +57,15 @@
 
     def paginate(
         self,
         *,
         GroupName: str = ...,
         Group: str = ...,
         Filters: Sequence[ResourceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.ListGroupResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#listgroupresourcespaginator)
         """
 
 class ListGroupsPaginator(AioPaginator):
@@ -80,27 +74,30 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#listgroupspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[GroupFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.ListGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#listgroupspaginator)
         """
 
 class SearchResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.SearchResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#searchresourcespaginator)
     """
 
     def paginate(
-        self, *, ResourceQuery: ResourceQueryTypeDef, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ResourceQuery: ResourceQueryTypeDef,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups.Paginator.SearchResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/paginators/#searchresourcespaginator)
         """
```

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/type_defs.py` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -28,59 +28,58 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AccountSettingsTypeDef",
     "ResourceQueryTypeDef",
     "GroupTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteGroupInputRequestTypeDef",
     "FailedResourceTypeDef",
     "GetGroupConfigurationInputRequestTypeDef",
     "GetGroupInputRequestTypeDef",
     "GetGroupQueryInputRequestTypeDef",
     "GetTagsInputRequestTypeDef",
+    "GetTagsOutputTypeDef",
     "GroupConfigurationParameterTypeDef",
     "GroupFilterTypeDef",
     "GroupIdentifierTypeDef",
     "GroupResourcesInputRequestTypeDef",
     "PendingResourceTypeDef",
-    "PaginatorConfigTypeDef",
     "ResourceFilterTypeDef",
     "ResourceIdentifierTypeDef",
     "ResourceStatusTypeDef",
     "QueryErrorTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagInputRequestTypeDef",
+    "TagOutputTypeDef",
     "UngroupResourcesInputRequestTypeDef",
     "UntagInputRequestTypeDef",
+    "UntagOutputTypeDef",
     "UpdateAccountSettingsInputRequestTypeDef",
     "UpdateGroupInputRequestTypeDef",
+    "GetAccountSettingsOutputTypeDef",
+    "UpdateAccountSettingsOutputTypeDef",
     "GroupQueryTypeDef",
     "SearchResourcesInputRequestTypeDef",
+    "SearchResourcesInputSearchResourcesPaginateTypeDef",
     "UpdateGroupQueryInputRequestTypeDef",
     "DeleteGroupOutputTypeDef",
-    "GetAccountSettingsOutputTypeDef",
     "GetGroupOutputTypeDef",
-    "GetTagsOutputTypeDef",
-    "TagOutputTypeDef",
-    "UntagOutputTypeDef",
-    "UpdateAccountSettingsOutputTypeDef",
     "UpdateGroupOutputTypeDef",
     "GroupConfigurationItemTypeDef",
+    "ListGroupsInputListGroupsPaginateTypeDef",
     "ListGroupsInputRequestTypeDef",
     "ListGroupsOutputTypeDef",
     "GroupResourcesOutputTypeDef",
     "UngroupResourcesOutputTypeDef",
-    "ListGroupsInputListGroupsPaginateTypeDef",
-    "SearchResourcesInputSearchResourcesPaginateTypeDef",
     "ListGroupResourcesInputListGroupResourcesPaginateTypeDef",
     "ListGroupResourcesInputRequestTypeDef",
     "ListGroupResourcesItemTypeDef",
     "SearchResourcesOutputTypeDef",
     "GetGroupQueryOutputTypeDef",
     "UpdateGroupQueryOutputTypeDef",
     "CreateGroupInputRequestTypeDef",
@@ -120,30 +119,17 @@
     "_OptionalGroupTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class GroupTypeDef(_RequiredGroupTypeDef, _OptionalGroupTypeDef):
     pass
 
-
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
 DeleteGroupInputRequestTypeDef = TypedDict(
     "DeleteGroupInputRequestTypeDef",
     {
         "GroupName": str,
         "Group": str,
     },
     total=False,
@@ -188,35 +174,42 @@
 GetTagsInputRequestTypeDef = TypedDict(
     "GetTagsInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetTagsOutputTypeDef = TypedDict(
+    "GetTagsOutputTypeDef",
+    {
+        "Arn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGroupConfigurationParameterTypeDef = TypedDict(
     "_RequiredGroupConfigurationParameterTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGroupConfigurationParameterTypeDef = TypedDict(
     "_OptionalGroupConfigurationParameterTypeDef",
     {
         "Values": Sequence[str],
     },
     total=False,
 )
 
-
 class GroupConfigurationParameterTypeDef(
     _RequiredGroupConfigurationParameterTypeDef, _OptionalGroupConfigurationParameterTypeDef
 ):
     pass
 
-
 GroupFilterTypeDef = TypedDict(
     "GroupFilterTypeDef",
     {
         "Name": GroupFilterNameType,
         "Values": Sequence[str],
     },
 )
@@ -242,24 +235,14 @@
     "PendingResourceTypeDef",
     {
         "ResourceArn": str,
     },
     total=False,
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
 ResourceFilterTypeDef = TypedDict(
     "ResourceFilterTypeDef",
     {
         "Name": Literal["resource-type"],
         "Values": Sequence[str],
     },
 )
@@ -286,22 +269,52 @@
     {
         "ErrorCode": QueryErrorCodeType,
         "Message": str,
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
 TagInputRequestTypeDef = TypedDict(
     "TagInputRequestTypeDef",
     {
         "Arn": str,
         "Tags": Mapping[str, str],
     },
 )
 
+TagOutputTypeDef = TypedDict(
+    "TagOutputTypeDef",
+    {
+        "Arn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UngroupResourcesInputRequestTypeDef = TypedDict(
     "UngroupResourcesInputRequestTypeDef",
     {
         "Group": str,
         "ResourceArns": Sequence[str],
     },
 )
@@ -310,14 +323,23 @@
     "UntagInputRequestTypeDef",
     {
         "Arn": str,
         "Keys": Sequence[str],
     },
 )
 
+UntagOutputTypeDef = TypedDict(
+    "UntagOutputTypeDef",
+    {
+        "Arn": str,
+        "Keys": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAccountSettingsInputRequestTypeDef = TypedDict(
     "UpdateAccountSettingsInputRequestTypeDef",
     {
         "GroupLifecycleEventsDesiredStatus": GroupLifecycleEventsDesiredStatusType,
     },
     total=False,
 )
@@ -328,14 +350,30 @@
         "GroupName": str,
         "Group": str,
         "Description": str,
     },
     total=False,
 )
 
+GetAccountSettingsOutputTypeDef = TypedDict(
+    "GetAccountSettingsOutputTypeDef",
+    {
+        "AccountSettings": AccountSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateAccountSettingsOutputTypeDef = TypedDict(
+    "UpdateAccountSettingsOutputTypeDef",
+    {
+        "AccountSettings": AccountSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GroupQueryTypeDef = TypedDict(
     "GroupQueryTypeDef",
     {
         "GroupName": str,
         "ResourceQuery": ResourceQueryTypeDef,
     },
 )
@@ -351,20 +389,38 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class SearchResourcesInputRequestTypeDef(
     _RequiredSearchResourcesInputRequestTypeDef, _OptionalSearchResourcesInputRequestTypeDef
 ):
     pass
 
+_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
+    "_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef",
+    {
+        "ResourceQuery": ResourceQueryTypeDef,
+    },
+)
+_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
+    "_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SearchResourcesInputSearchResourcesPaginateTypeDef(
+    _RequiredSearchResourcesInputSearchResourcesPaginateTypeDef,
+    _OptionalSearchResourcesInputSearchResourcesPaginateTypeDef,
+):
+    pass
 
 _RequiredUpdateGroupQueryInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGroupQueryInputRequestTypeDef",
     {
         "ResourceQuery": ResourceQueryTypeDef,
     },
 )
@@ -373,85 +429,40 @@
     {
         "GroupName": str,
         "Group": str,
     },
     total=False,
 )
 
-
 class UpdateGroupQueryInputRequestTypeDef(
     _RequiredUpdateGroupQueryInputRequestTypeDef, _OptionalUpdateGroupQueryInputRequestTypeDef
 ):
     pass
 
-
 DeleteGroupOutputTypeDef = TypedDict(
     "DeleteGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountSettingsOutputTypeDef = TypedDict(
-    "GetAccountSettingsOutputTypeDef",
-    {
-        "AccountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupOutputTypeDef = TypedDict(
     "GetGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagsOutputTypeDef = TypedDict(
-    "GetTagsOutputTypeDef",
-    {
-        "Arn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagOutputTypeDef = TypedDict(
-    "TagOutputTypeDef",
-    {
-        "Arn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UntagOutputTypeDef = TypedDict(
-    "UntagOutputTypeDef",
-    {
-        "Arn": str,
-        "Keys": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAccountSettingsOutputTypeDef = TypedDict(
-    "UpdateAccountSettingsOutputTypeDef",
-    {
-        "AccountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGroupOutputTypeDef = TypedDict(
     "UpdateGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGroupConfigurationItemTypeDef = TypedDict(
     "_RequiredGroupConfigurationItemTypeDef",
     {
         "Type": str,
@@ -461,20 +472,27 @@
     "_OptionalGroupConfigurationItemTypeDef",
     {
         "Parameters": Sequence[GroupConfigurationParameterTypeDef],
     },
     total=False,
 )
 
-
 class GroupConfigurationItemTypeDef(
     _RequiredGroupConfigurationItemTypeDef, _OptionalGroupConfigurationItemTypeDef
 ):
     pass
 
+ListGroupsInputListGroupsPaginateTypeDef = TypedDict(
+    "ListGroupsInputListGroupsPaginateTypeDef",
+    {
+        "Filters": Sequence[GroupFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListGroupsInputRequestTypeDef = TypedDict(
     "ListGroupsInputRequestTypeDef",
     {
         "Filters": Sequence[GroupFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
@@ -484,76 +502,45 @@
 
 ListGroupsOutputTypeDef = TypedDict(
     "ListGroupsOutputTypeDef",
     {
         "GroupIdentifiers": List[GroupIdentifierTypeDef],
         "Groups": List[GroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GroupResourcesOutputTypeDef = TypedDict(
     "GroupResourcesOutputTypeDef",
     {
         "Succeeded": List[str],
         "Failed": List[FailedResourceTypeDef],
         "Pending": List[PendingResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UngroupResourcesOutputTypeDef = TypedDict(
     "UngroupResourcesOutputTypeDef",
     {
         "Succeeded": List[str],
         "Failed": List[FailedResourceTypeDef],
         "Pending": List[PendingResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGroupsInputListGroupsPaginateTypeDef = TypedDict(
-    "ListGroupsInputListGroupsPaginateTypeDef",
-    {
-        "Filters": Sequence[GroupFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
-    "_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef",
-    {
-        "ResourceQuery": ResourceQueryTypeDef,
-    },
-)
-_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
-    "_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class SearchResourcesInputSearchResourcesPaginateTypeDef(
-    _RequiredSearchResourcesInputSearchResourcesPaginateTypeDef,
-    _OptionalSearchResourcesInputSearchResourcesPaginateTypeDef,
-):
-    pass
-
-
 ListGroupResourcesInputListGroupResourcesPaginateTypeDef = TypedDict(
     "ListGroupResourcesInputListGroupResourcesPaginateTypeDef",
     {
         "GroupName": str,
         "Group": str,
         "Filters": Sequence[ResourceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListGroupResourcesInputRequestTypeDef = TypedDict(
     "ListGroupResourcesInputRequestTypeDef",
     {
@@ -577,31 +564,31 @@
 
 SearchResourcesOutputTypeDef = TypedDict(
     "SearchResourcesOutputTypeDef",
     {
         "ResourceIdentifiers": List[ResourceIdentifierTypeDef],
         "NextToken": str,
         "QueryErrors": List[QueryErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupQueryOutputTypeDef = TypedDict(
     "GetGroupQueryOutputTypeDef",
     {
         "GroupQuery": GroupQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGroupQueryOutputTypeDef = TypedDict(
     "UpdateGroupQueryOutputTypeDef",
     {
         "GroupQuery": GroupQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateGroupInputRequestTypeDef",
     {
         "Name": str,
@@ -614,21 +601,19 @@
         "ResourceQuery": ResourceQueryTypeDef,
         "Tags": Mapping[str, str],
         "Configuration": Sequence[GroupConfigurationItemTypeDef],
     },
     total=False,
 )
 
-
 class CreateGroupInputRequestTypeDef(
     _RequiredCreateGroupInputRequestTypeDef, _OptionalCreateGroupInputRequestTypeDef
 ):
     pass
 
-
 GroupConfigurationTypeDef = TypedDict(
     "GroupConfigurationTypeDef",
     {
         "Configuration": List[GroupConfigurationItemTypeDef],
         "ProposedConfiguration": List[GroupConfigurationItemTypeDef],
         "Status": GroupConfigurationStatusType,
         "FailureReason": str,
@@ -648,29 +633,29 @@
 ListGroupResourcesOutputTypeDef = TypedDict(
     "ListGroupResourcesOutputTypeDef",
     {
         "Resources": List[ListGroupResourcesItemTypeDef],
         "ResourceIdentifiers": List[ResourceIdentifierTypeDef],
         "NextToken": str,
         "QueryErrors": List[QueryErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGroupOutputTypeDef = TypedDict(
     "CreateGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
         "ResourceQuery": ResourceQueryTypeDef,
         "Tags": Dict[str, str],
         "GroupConfiguration": GroupConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupConfigurationOutputTypeDef = TypedDict(
     "GetGroupConfigurationOutputTypeDef",
     {
         "GroupConfiguration": GroupConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups/type_defs.pyi` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups/type_defs.py`

 * *Files 14% similar despite different names*

```diff
@@ -28,58 +28,59 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AccountSettingsTypeDef",
     "ResourceQueryTypeDef",
     "GroupTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteGroupInputRequestTypeDef",
     "FailedResourceTypeDef",
     "GetGroupConfigurationInputRequestTypeDef",
     "GetGroupInputRequestTypeDef",
     "GetGroupQueryInputRequestTypeDef",
     "GetTagsInputRequestTypeDef",
+    "GetTagsOutputTypeDef",
     "GroupConfigurationParameterTypeDef",
     "GroupFilterTypeDef",
     "GroupIdentifierTypeDef",
     "GroupResourcesInputRequestTypeDef",
     "PendingResourceTypeDef",
-    "PaginatorConfigTypeDef",
     "ResourceFilterTypeDef",
     "ResourceIdentifierTypeDef",
     "ResourceStatusTypeDef",
     "QueryErrorTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagInputRequestTypeDef",
+    "TagOutputTypeDef",
     "UngroupResourcesInputRequestTypeDef",
     "UntagInputRequestTypeDef",
+    "UntagOutputTypeDef",
     "UpdateAccountSettingsInputRequestTypeDef",
     "UpdateGroupInputRequestTypeDef",
+    "GetAccountSettingsOutputTypeDef",
+    "UpdateAccountSettingsOutputTypeDef",
     "GroupQueryTypeDef",
     "SearchResourcesInputRequestTypeDef",
+    "SearchResourcesInputSearchResourcesPaginateTypeDef",
     "UpdateGroupQueryInputRequestTypeDef",
     "DeleteGroupOutputTypeDef",
-    "GetAccountSettingsOutputTypeDef",
     "GetGroupOutputTypeDef",
-    "GetTagsOutputTypeDef",
-    "TagOutputTypeDef",
-    "UntagOutputTypeDef",
-    "UpdateAccountSettingsOutputTypeDef",
     "UpdateGroupOutputTypeDef",
     "GroupConfigurationItemTypeDef",
+    "ListGroupsInputListGroupsPaginateTypeDef",
     "ListGroupsInputRequestTypeDef",
     "ListGroupsOutputTypeDef",
     "GroupResourcesOutputTypeDef",
     "UngroupResourcesOutputTypeDef",
-    "ListGroupsInputListGroupsPaginateTypeDef",
-    "SearchResourcesInputSearchResourcesPaginateTypeDef",
     "ListGroupResourcesInputListGroupResourcesPaginateTypeDef",
     "ListGroupResourcesInputRequestTypeDef",
     "ListGroupResourcesItemTypeDef",
     "SearchResourcesOutputTypeDef",
     "GetGroupQueryOutputTypeDef",
     "UpdateGroupQueryOutputTypeDef",
     "CreateGroupInputRequestTypeDef",
@@ -119,27 +120,18 @@
     "_OptionalGroupTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class GroupTypeDef(_RequiredGroupTypeDef, _OptionalGroupTypeDef):
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
 
 DeleteGroupInputRequestTypeDef = TypedDict(
     "DeleteGroupInputRequestTypeDef",
     {
         "GroupName": str,
         "Group": str,
     },
@@ -185,33 +177,44 @@
 GetTagsInputRequestTypeDef = TypedDict(
     "GetTagsInputRequestTypeDef",
     {
         "Arn": str,
     },
 )
 
+GetTagsOutputTypeDef = TypedDict(
+    "GetTagsOutputTypeDef",
+    {
+        "Arn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGroupConfigurationParameterTypeDef = TypedDict(
     "_RequiredGroupConfigurationParameterTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalGroupConfigurationParameterTypeDef = TypedDict(
     "_OptionalGroupConfigurationParameterTypeDef",
     {
         "Values": Sequence[str],
     },
     total=False,
 )
 
+
 class GroupConfigurationParameterTypeDef(
     _RequiredGroupConfigurationParameterTypeDef, _OptionalGroupConfigurationParameterTypeDef
 ):
     pass
 
+
 GroupFilterTypeDef = TypedDict(
     "GroupFilterTypeDef",
     {
         "Name": GroupFilterNameType,
         "Values": Sequence[str],
     },
 )
@@ -237,24 +240,14 @@
     "PendingResourceTypeDef",
     {
         "ResourceArn": str,
     },
     total=False,
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
 ResourceFilterTypeDef = TypedDict(
     "ResourceFilterTypeDef",
     {
         "Name": Literal["resource-type"],
         "Values": Sequence[str],
     },
 )
@@ -281,22 +274,52 @@
     {
         "ErrorCode": QueryErrorCodeType,
         "Message": str,
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
 TagInputRequestTypeDef = TypedDict(
     "TagInputRequestTypeDef",
     {
         "Arn": str,
         "Tags": Mapping[str, str],
     },
 )
 
+TagOutputTypeDef = TypedDict(
+    "TagOutputTypeDef",
+    {
+        "Arn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UngroupResourcesInputRequestTypeDef = TypedDict(
     "UngroupResourcesInputRequestTypeDef",
     {
         "Group": str,
         "ResourceArns": Sequence[str],
     },
 )
@@ -305,14 +328,23 @@
     "UntagInputRequestTypeDef",
     {
         "Arn": str,
         "Keys": Sequence[str],
     },
 )
 
+UntagOutputTypeDef = TypedDict(
+    "UntagOutputTypeDef",
+    {
+        "Arn": str,
+        "Keys": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAccountSettingsInputRequestTypeDef = TypedDict(
     "UpdateAccountSettingsInputRequestTypeDef",
     {
         "GroupLifecycleEventsDesiredStatus": GroupLifecycleEventsDesiredStatusType,
     },
     total=False,
 )
@@ -323,14 +355,30 @@
         "GroupName": str,
         "Group": str,
         "Description": str,
     },
     total=False,
 )
 
+GetAccountSettingsOutputTypeDef = TypedDict(
+    "GetAccountSettingsOutputTypeDef",
+    {
+        "AccountSettings": AccountSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateAccountSettingsOutputTypeDef = TypedDict(
+    "UpdateAccountSettingsOutputTypeDef",
+    {
+        "AccountSettings": AccountSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GroupQueryTypeDef = TypedDict(
     "GroupQueryTypeDef",
     {
         "GroupName": str,
         "ResourceQuery": ResourceQueryTypeDef,
     },
 )
@@ -346,19 +394,43 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class SearchResourcesInputRequestTypeDef(
     _RequiredSearchResourcesInputRequestTypeDef, _OptionalSearchResourcesInputRequestTypeDef
 ):
     pass
 
+
+_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
+    "_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef",
+    {
+        "ResourceQuery": ResourceQueryTypeDef,
+    },
+)
+_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
+    "_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SearchResourcesInputSearchResourcesPaginateTypeDef(
+    _RequiredSearchResourcesInputSearchResourcesPaginateTypeDef,
+    _OptionalSearchResourcesInputSearchResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredUpdateGroupQueryInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGroupQueryInputRequestTypeDef",
     {
         "ResourceQuery": ResourceQueryTypeDef,
     },
 )
 _OptionalUpdateGroupQueryInputRequestTypeDef = TypedDict(
@@ -366,83 +438,42 @@
     {
         "GroupName": str,
         "Group": str,
     },
     total=False,
 )
 
+
 class UpdateGroupQueryInputRequestTypeDef(
     _RequiredUpdateGroupQueryInputRequestTypeDef, _OptionalUpdateGroupQueryInputRequestTypeDef
 ):
     pass
 
+
 DeleteGroupOutputTypeDef = TypedDict(
     "DeleteGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountSettingsOutputTypeDef = TypedDict(
-    "GetAccountSettingsOutputTypeDef",
-    {
-        "AccountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupOutputTypeDef = TypedDict(
     "GetGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagsOutputTypeDef = TypedDict(
-    "GetTagsOutputTypeDef",
-    {
-        "Arn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TagOutputTypeDef = TypedDict(
-    "TagOutputTypeDef",
-    {
-        "Arn": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UntagOutputTypeDef = TypedDict(
-    "UntagOutputTypeDef",
-    {
-        "Arn": str,
-        "Keys": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAccountSettingsOutputTypeDef = TypedDict(
-    "UpdateAccountSettingsOutputTypeDef",
-    {
-        "AccountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGroupOutputTypeDef = TypedDict(
     "UpdateGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGroupConfigurationItemTypeDef = TypedDict(
     "_RequiredGroupConfigurationItemTypeDef",
     {
         "Type": str,
@@ -452,19 +483,30 @@
     "_OptionalGroupConfigurationItemTypeDef",
     {
         "Parameters": Sequence[GroupConfigurationParameterTypeDef],
     },
     total=False,
 )
 
+
 class GroupConfigurationItemTypeDef(
     _RequiredGroupConfigurationItemTypeDef, _OptionalGroupConfigurationItemTypeDef
 ):
     pass
 
+
+ListGroupsInputListGroupsPaginateTypeDef = TypedDict(
+    "ListGroupsInputListGroupsPaginateTypeDef",
+    {
+        "Filters": Sequence[GroupFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGroupsInputRequestTypeDef = TypedDict(
     "ListGroupsInputRequestTypeDef",
     {
         "Filters": Sequence[GroupFilterTypeDef],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -473,74 +515,45 @@
 
 ListGroupsOutputTypeDef = TypedDict(
     "ListGroupsOutputTypeDef",
     {
         "GroupIdentifiers": List[GroupIdentifierTypeDef],
         "Groups": List[GroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GroupResourcesOutputTypeDef = TypedDict(
     "GroupResourcesOutputTypeDef",
     {
         "Succeeded": List[str],
         "Failed": List[FailedResourceTypeDef],
         "Pending": List[PendingResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UngroupResourcesOutputTypeDef = TypedDict(
     "UngroupResourcesOutputTypeDef",
     {
         "Succeeded": List[str],
         "Failed": List[FailedResourceTypeDef],
         "Pending": List[PendingResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGroupsInputListGroupsPaginateTypeDef = TypedDict(
-    "ListGroupsInputListGroupsPaginateTypeDef",
-    {
-        "Filters": Sequence[GroupFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
-    "_RequiredSearchResourcesInputSearchResourcesPaginateTypeDef",
-    {
-        "ResourceQuery": ResourceQueryTypeDef,
-    },
-)
-_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef = TypedDict(
-    "_OptionalSearchResourcesInputSearchResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class SearchResourcesInputSearchResourcesPaginateTypeDef(
-    _RequiredSearchResourcesInputSearchResourcesPaginateTypeDef,
-    _OptionalSearchResourcesInputSearchResourcesPaginateTypeDef,
-):
-    pass
-
 ListGroupResourcesInputListGroupResourcesPaginateTypeDef = TypedDict(
     "ListGroupResourcesInputListGroupResourcesPaginateTypeDef",
     {
         "GroupName": str,
         "Group": str,
         "Filters": Sequence[ResourceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListGroupResourcesInputRequestTypeDef = TypedDict(
     "ListGroupResourcesInputRequestTypeDef",
     {
@@ -564,31 +577,31 @@
 
 SearchResourcesOutputTypeDef = TypedDict(
     "SearchResourcesOutputTypeDef",
     {
         "ResourceIdentifiers": List[ResourceIdentifierTypeDef],
         "NextToken": str,
         "QueryErrors": List[QueryErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupQueryOutputTypeDef = TypedDict(
     "GetGroupQueryOutputTypeDef",
     {
         "GroupQuery": GroupQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGroupQueryOutputTypeDef = TypedDict(
     "UpdateGroupQueryOutputTypeDef",
     {
         "GroupQuery": GroupQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateGroupInputRequestTypeDef",
     {
         "Name": str,
@@ -601,19 +614,21 @@
         "ResourceQuery": ResourceQueryTypeDef,
         "Tags": Mapping[str, str],
         "Configuration": Sequence[GroupConfigurationItemTypeDef],
     },
     total=False,
 )
 
+
 class CreateGroupInputRequestTypeDef(
     _RequiredCreateGroupInputRequestTypeDef, _OptionalCreateGroupInputRequestTypeDef
 ):
     pass
 
+
 GroupConfigurationTypeDef = TypedDict(
     "GroupConfigurationTypeDef",
     {
         "Configuration": List[GroupConfigurationItemTypeDef],
         "ProposedConfiguration": List[GroupConfigurationItemTypeDef],
         "Status": GroupConfigurationStatusType,
         "FailureReason": str,
@@ -633,29 +648,29 @@
 ListGroupResourcesOutputTypeDef = TypedDict(
     "ListGroupResourcesOutputTypeDef",
     {
         "Resources": List[ListGroupResourcesItemTypeDef],
         "ResourceIdentifiers": List[ResourceIdentifierTypeDef],
         "NextToken": str,
         "QueryErrors": List[QueryErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGroupOutputTypeDef = TypedDict(
     "CreateGroupOutputTypeDef",
     {
         "Group": GroupTypeDef,
         "ResourceQuery": ResourceQueryTypeDef,
         "Tags": Dict[str, str],
         "GroupConfiguration": GroupConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupConfigurationOutputTypeDef = TypedDict(
     "GetGroupConfigurationOutputTypeDef",
     {
         "GroupConfiguration": GroupConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/PKG-INFO` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resource-groups
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResourceGroups 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResourceGroups 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resource-groups"></a>
 
 # types-aiobotocore-resource-groups
 
 [![PyPI - types-aiobotocore-resource-groups](https://img.shields.io/pypi/v/types-aiobotocore-resource-groups.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-groups)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resource-groups.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resource-groups)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resource-groups?color=blue)](https://pypistats.org/packages/types-aiobotocore-resource-groups)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResourceGroups 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups)
+[aiobotocore.ResourceGroups 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html#ResourceGroups)
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
 [types-aiobotocore-resource-groups docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resource_groups/).
 
 See how it helps to find and fix potential bugs:
 
@@ -335,54 +335,54 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resource_groups.type_defs import (
     AccountSettingsTypeDef,
     ResourceQueryTypeDef,
     GroupTypeDef,
-    ResponseMetadataTypeDef,
     DeleteGroupInputRequestTypeDef,
     FailedResourceTypeDef,
     GetGroupConfigurationInputRequestTypeDef,
     GetGroupInputRequestTypeDef,
     GetGroupQueryInputRequestTypeDef,
     GetTagsInputRequestTypeDef,
+    GetTagsOutputTypeDef,
     GroupConfigurationParameterTypeDef,
     GroupFilterTypeDef,
     GroupIdentifierTypeDef,
     GroupResourcesInputRequestTypeDef,
     PendingResourceTypeDef,
-    PaginatorConfigTypeDef,
     ResourceFilterTypeDef,
     ResourceIdentifierTypeDef,
     ResourceStatusTypeDef,
     QueryErrorTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagInputRequestTypeDef,
+    TagOutputTypeDef,
     UngroupResourcesInputRequestTypeDef,
     UntagInputRequestTypeDef,
+    UntagOutputTypeDef,
     UpdateAccountSettingsInputRequestTypeDef,
     UpdateGroupInputRequestTypeDef,
+    GetAccountSettingsOutputTypeDef,
+    UpdateAccountSettingsOutputTypeDef,
     GroupQueryTypeDef,
     SearchResourcesInputRequestTypeDef,
+    SearchResourcesInputSearchResourcesPaginateTypeDef,
     UpdateGroupQueryInputRequestTypeDef,
     DeleteGroupOutputTypeDef,
-    GetAccountSettingsOutputTypeDef,
     GetGroupOutputTypeDef,
-    GetTagsOutputTypeDef,
-    TagOutputTypeDef,
-    UntagOutputTypeDef,
-    UpdateAccountSettingsOutputTypeDef,
     UpdateGroupOutputTypeDef,
     GroupConfigurationItemTypeDef,
+    ListGroupsInputListGroupsPaginateTypeDef,
     ListGroupsInputRequestTypeDef,
     ListGroupsOutputTypeDef,
     GroupResourcesOutputTypeDef,
     UngroupResourcesOutputTypeDef,
-    ListGroupsInputListGroupsPaginateTypeDef,
-    SearchResourcesInputSearchResourcesPaginateTypeDef,
     ListGroupResourcesInputListGroupResourcesPaginateTypeDef,
     ListGroupResourcesInputRequestTypeDef,
     ListGroupResourcesItemTypeDef,
     SearchResourcesOutputTypeDef,
     GetGroupQueryOutputTypeDef,
     UpdateGroupQueryOutputTypeDef,
     CreateGroupInputRequestTypeDef,
@@ -401,43 +401,43 @@
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

### Comparing `types-aiobotocore-resource-groups-2.5.0.post1/types_aiobotocore_resource_groups.egg-info/SOURCES.txt` & `types-aiobotocore-resource-groups-2.5.1/types_aiobotocore_resource_groups.egg-info/SOURCES.txt`

 * *Files identical despite different names*

