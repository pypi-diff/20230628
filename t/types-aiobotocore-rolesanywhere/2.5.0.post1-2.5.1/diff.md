# Comparing `tmp/types-aiobotocore-rolesanywhere-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-rolesanywhere-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-rolesanywhere-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-rolesanywhere-2.5.1.tar", last modified: Wed Jun 28 01:44:04 2023, max compression
```

## Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1.tar` & `types-aiobotocore-rolesanywhere-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.299558 types-aiobotocore-rolesanywhere-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14968 2023-03-11 12:27:13.299558 types-aiobotocore-rolesanywhere-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13370 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.299558 types-aiobotocore-rolesanywhere-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2169 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.299558 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/
--rw-r--r--   0 runner    (1001) docker     (123)     1258 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1257 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      973 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20698 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20659 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8397 2023-03-11 12:22:33.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8395 2023-03-11 12:22:33.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5498 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5491 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    12354 2023-03-11 12:22:33.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    12341 2023-03-11 12:22:33.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:32.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.299558 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14968 2023-03-11 12:27:13.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:27:13.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:27:13.000000 types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:04.646202 types-aiobotocore-rolesanywhere-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15319 2023-06-28 01:44:04.638202 types-aiobotocore-rolesanywhere-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13727 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:04.646202 types-aiobotocore-rolesanywhere-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2163 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:04.638202 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/
+-rw-r--r--   0 runner    (1001) docker     (123)     1258 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1257 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      961 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22358 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22317 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8797 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8795 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5386 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5380 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    15361 2023-06-28 01:39:21.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15342 2023-06-28 01:39:21.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:20.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:04.638202 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15319 2023-06-28 01:44:04.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:44:04.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:04.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:04.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:04.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:44:04.000000 types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/LICENSE` & `types-aiobotocore-rolesanywhere-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/PKG-INFO` & `types-aiobotocore-rolesanywhere-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rolesanywhere
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IAMRolesAnywhere 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IAMRolesAnywhere 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rolesanywhere"></a>
 
 # types-aiobotocore-rolesanywhere
 
 [![PyPI - types-aiobotocore-rolesanywhere](https://img.shields.io/pypi/v/types-aiobotocore-rolesanywhere.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rolesanywhere)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rolesanywhere.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rolesanywhere)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rolesanywhere?color=blue)](https://pypistats.org/packages/types-aiobotocore-rolesanywhere)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IAMRolesAnywhere 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere)
+[aiobotocore.IAMRolesAnywhere 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere)
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
 [types-aiobotocore-rolesanywhere docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,14 +306,16 @@
 
 ```python
 from types_aiobotocore_rolesanywhere.literals import (
     ListCrlsPaginatorName,
     ListProfilesPaginatorName,
     ListSubjectsPaginatorName,
     ListTrustAnchorsPaginatorName,
+    NotificationChannelType,
+    NotificationEventType,
     TrustAnchorTypeType,
     IAMRolesAnywhereServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -329,51 +331,58 @@
 
 `types_aiobotocore_rolesanywhere.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rolesanywhere.type_defs import (
     TagTypeDef,
+    NotificationSettingTypeDef,
     CredentialSummaryTypeDef,
     CrlDetailTypeDef,
-    ResponseMetadataTypeDef,
     InstancePropertyTypeDef,
     ProfileDetailTypeDef,
-    PaginatorConfigTypeDef,
+    ListRequestListCrlsPaginateTypeDef,
+    ListRequestListProfilesPaginateTypeDef,
+    ListRequestListSubjectsPaginateTypeDef,
+    ListRequestListTrustAnchorsPaginateTypeDef,
     ListRequestRequestTypeDef,
     SubjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    NotificationSettingDetailTypeDef,
+    NotificationSettingKeyTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ScalarCrlRequestRequestTypeDef,
     ScalarProfileRequestRequestTypeDef,
     ScalarSubjectRequestRequestTypeDef,
     ScalarTrustAnchorRequestRequestTypeDef,
     SourceDataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCrlRequestRequestTypeDef,
     UpdateProfileRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     ImportCrlRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    PutNotificationSettingsRequestRequestTypeDef,
     CrlDetailResponseTypeDef,
     ListCrlsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     SubjectDetailTypeDef,
     ListProfilesResponseTypeDef,
     ProfileDetailResponseTypeDef,
-    ListRequestListCrlsPaginateTypeDef,
-    ListRequestListProfilesPaginateTypeDef,
-    ListRequestListSubjectsPaginateTypeDef,
-    ListRequestListTrustAnchorsPaginateTypeDef,
     ListSubjectsResponseTypeDef,
+    ResetNotificationSettingsRequestRequestTypeDef,
     SourceTypeDef,
     SubjectDetailResponseTypeDef,
     CreateTrustAnchorRequestRequestTypeDef,
     TrustAnchorDetailTypeDef,
     UpdateTrustAnchorRequestRequestTypeDef,
     ListTrustAnchorsResponseTypeDef,
+    PutNotificationSettingsResponseTypeDef,
+    ResetNotificationSettingsResponseTypeDef,
     TrustAnchorDetailResponseTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
     return {...}
 ```
@@ -381,43 +390,43 @@
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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/README.md` & `types-aiobotocore-rolesanywhere-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-rolesanywhere"></a>
 
 # types-aiobotocore-rolesanywhere
 
 [![PyPI - types-aiobotocore-rolesanywhere](https://img.shields.io/pypi/v/types-aiobotocore-rolesanywhere.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rolesanywhere)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rolesanywhere.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rolesanywhere)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rolesanywhere?color=blue)](https://pypistats.org/packages/types-aiobotocore-rolesanywhere)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IAMRolesAnywhere 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere)
+[aiobotocore.IAMRolesAnywhere 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere)
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
 [types-aiobotocore-rolesanywhere docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,14 +273,16 @@
 
 ```python
 from types_aiobotocore_rolesanywhere.literals import (
     ListCrlsPaginatorName,
     ListProfilesPaginatorName,
     ListSubjectsPaginatorName,
     ListTrustAnchorsPaginatorName,
+    NotificationChannelType,
+    NotificationEventType,
     TrustAnchorTypeType,
     IAMRolesAnywhereServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -296,51 +298,58 @@
 
 `types_aiobotocore_rolesanywhere.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rolesanywhere.type_defs import (
     TagTypeDef,
+    NotificationSettingTypeDef,
     CredentialSummaryTypeDef,
     CrlDetailTypeDef,
-    ResponseMetadataTypeDef,
     InstancePropertyTypeDef,
     ProfileDetailTypeDef,
-    PaginatorConfigTypeDef,
+    ListRequestListCrlsPaginateTypeDef,
+    ListRequestListProfilesPaginateTypeDef,
+    ListRequestListSubjectsPaginateTypeDef,
+    ListRequestListTrustAnchorsPaginateTypeDef,
     ListRequestRequestTypeDef,
     SubjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    NotificationSettingDetailTypeDef,
+    NotificationSettingKeyTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ScalarCrlRequestRequestTypeDef,
     ScalarProfileRequestRequestTypeDef,
     ScalarSubjectRequestRequestTypeDef,
     ScalarTrustAnchorRequestRequestTypeDef,
     SourceDataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCrlRequestRequestTypeDef,
     UpdateProfileRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     ImportCrlRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    PutNotificationSettingsRequestRequestTypeDef,
     CrlDetailResponseTypeDef,
     ListCrlsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     SubjectDetailTypeDef,
     ListProfilesResponseTypeDef,
     ProfileDetailResponseTypeDef,
-    ListRequestListCrlsPaginateTypeDef,
-    ListRequestListProfilesPaginateTypeDef,
-    ListRequestListSubjectsPaginateTypeDef,
-    ListRequestListTrustAnchorsPaginateTypeDef,
     ListSubjectsResponseTypeDef,
+    ResetNotificationSettingsRequestRequestTypeDef,
     SourceTypeDef,
     SubjectDetailResponseTypeDef,
     CreateTrustAnchorRequestRequestTypeDef,
     TrustAnchorDetailTypeDef,
     UpdateTrustAnchorRequestRequestTypeDef,
     ListTrustAnchorsResponseTypeDef,
+    PutNotificationSettingsResponseTypeDef,
+    ResetNotificationSettingsResponseTypeDef,
     TrustAnchorDetailResponseTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
     return {...}
 ```
@@ -348,43 +357,43 @@
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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/setup.py` & `types-aiobotocore-rolesanywhere-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-rolesanywhere.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-rolesanywhere",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_rolesanywhere"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IAMRolesAnywhere 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IAMRolesAnywhere 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/"
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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/__init__.py` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/__init__.pyi` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/__main__.py` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IAMRolesAnywhere 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IAMRolesAnywhere 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere\nOther"
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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/client.py` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/client.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -30,46 +30,46 @@
 from .type_defs import (
     CrlDetailResponseTypeDef,
     ListCrlsResponseTypeDef,
     ListProfilesResponseTypeDef,
     ListSubjectsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTrustAnchorsResponseTypeDef,
+    NotificationSettingKeyTypeDef,
+    NotificationSettingTypeDef,
     ProfileDetailResponseTypeDef,
+    PutNotificationSettingsResponseTypeDef,
+    ResetNotificationSettingsResponseTypeDef,
     SourceTypeDef,
     SubjectDetailResponseTypeDef,
     TagTypeDef,
     TrustAnchorDetailResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("IAMRolesAnywhereClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     TooManyTagsException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class IAMRolesAnywhereClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/)
     """
 
     meta: ClientMeta
@@ -78,184 +78,168 @@
     def exceptions(self) -> Exceptions:
         """
         IAMRolesAnywhereClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#exceptions)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#close)
         """
-
     async def create_profile(
         self,
         *,
         name: str,
         roleArns: Sequence[str],
         durationSeconds: int = ...,
         enabled: bool = ...,
         managedPolicyArns: Sequence[str] = ...,
         requireInstanceProperties: bool = ...,
         sessionPolicy: str = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> ProfileDetailResponseTypeDef:
         """
-        Creates a profile.
+        Creates a *profile*, a list of the roles that Roles Anywhere service is trusted
+        to assume.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.create_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#create_profile)
         """
-
     async def create_trust_anchor(
         self,
         *,
         name: str,
         source: SourceTypeDef,
         enabled: bool = ...,
+        notificationSettings: Sequence[NotificationSettingTypeDef] = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> TrustAnchorDetailResponseTypeDef:
         """
-        Creates a trust anchor.
+        Creates a trust anchor to establish trust between IAM Roles Anywhere and your
+        certificate authority (CA).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.create_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#create_trust_anchor)
         """
-
     async def delete_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Deletes a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.delete_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#delete_crl)
         """
-
     async def delete_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
         Deletes a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.delete_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#delete_profile)
         """
-
     async def delete_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Deletes a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.delete_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#delete_trust_anchor)
         """
-
     async def disable_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Disables a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.disable_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#disable_crl)
         """
-
     async def disable_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
         Disables a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.disable_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#disable_profile)
         """
-
     async def disable_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Disables a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.disable_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#disable_trust_anchor)
         """
-
     async def enable_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Enables a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.enable_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#enable_crl)
         """
-
     async def enable_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
-        Enables the roles in a profile to receive session credentials in
-        [CreateSession](https://docs.aws.amazon.com/rolesanywhere/latest/APIReference/API_CreateSession.html)_.
+        Enables temporary credential requests for a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.enable_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#enable_profile)
         """
-
     async def enable_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Enables a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.enable_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#enable_trust_anchor)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#generate_presigned_url)
         """
-
     async def get_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Gets a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_crl)
         """
-
     async def get_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
         Gets a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_profile)
         """
-
     async def get_subject(self, *, subjectId: str) -> SubjectDetailResponseTypeDef:
         """
-        Gets a Subject.
+        Gets a *subject*, which associates a certificate identity with authentication
+        attempts.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_subject)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_subject)
         """
-
     async def get_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Gets a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_trust_anchor)
         """
-
     async def import_crl(
         self,
         *,
         crlData: Union[str, bytes, IO[Any], StreamingBody],
         name: str,
         trustAnchorArn: str,
         enabled: bool = ...,
@@ -263,158 +247,164 @@
     ) -> CrlDetailResponseTypeDef:
         """
         Imports the certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.import_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#import_crl)
         """
-
     async def list_crls(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListCrlsResponseTypeDef:
         """
-        Lists all Crls in the authenticated account and Amazon Web Services Region.
+        Lists all certificate revocation lists (CRL) in the authenticated account and
+        Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_crls)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_crls)
         """
-
     async def list_profiles(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListProfilesResponseTypeDef:
         """
         Lists all profiles in the authenticated account and Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_profiles)
         """
-
     async def list_subjects(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListSubjectsResponseTypeDef:
         """
         Lists the subjects in the authenticated account and Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_subjects)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_subjects)
         """
-
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags attached to the resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_tags_for_resource)
         """
-
     async def list_trust_anchors(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListTrustAnchorsResponseTypeDef:
         """
         Lists the trust anchors in the authenticated account and Amazon Web Services
         Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_trust_anchors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_trust_anchors)
         """
+    async def put_notification_settings(
+        self, *, notificationSettings: Sequence[NotificationSettingTypeDef], trustAnchorId: str
+    ) -> PutNotificationSettingsResponseTypeDef:
+        """
+        Attaches a list of *notification settings* to a trust anchor.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.put_notification_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#put_notification_settings)
+        """
+    async def reset_notification_settings(
+        self,
+        *,
+        notificationSettingKeys: Sequence[NotificationSettingKeyTypeDef],
+        trustAnchorId: str
+    ) -> ResetNotificationSettingsResponseTypeDef:
+        """
+        Resets the *custom notification setting* to IAM Roles Anywhere default setting.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.reset_notification_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#reset_notification_settings)
+        """
     async def tag_resource(self, *, resourceArn: str, tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Attaches tags to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#tag_resource)
         """
-
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from the resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#untag_resource)
         """
-
     async def update_crl(
         self,
         *,
         crlId: str,
         crlData: Union[str, bytes, IO[Any], StreamingBody] = ...,
         name: str = ...
     ) -> CrlDetailResponseTypeDef:
         """
         Updates the certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.update_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#update_crl)
         """
-
     async def update_profile(
         self,
         *,
         profileId: str,
         durationSeconds: int = ...,
         managedPolicyArns: Sequence[str] = ...,
         name: str = ...,
         roleArns: Sequence[str] = ...,
         sessionPolicy: str = ...
     ) -> ProfileDetailResponseTypeDef:
         """
-        Updates the profile.
+        Updates a *profile*, a list of the roles that IAM Roles Anywhere service is
+        trusted to assume.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.update_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#update_profile)
         """
-
     async def update_trust_anchor(
         self, *, trustAnchorId: str, name: str = ..., source: SourceTypeDef = ...
     ) -> TrustAnchorDetailResponseTypeDef:
         """
-        Updates the trust anchor.You establish trust between IAM Roles Anywhere and your
-        certificate authority (CA) by configuring a trust anchor.
+        Updates a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.update_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#update_trust_anchor)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_crls"]) -> ListCrlsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_profiles"]) -> ListProfilesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_subjects"]) -> ListSubjectsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_trust_anchors"]
     ) -> ListTrustAnchorsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "IAMRolesAnywhereClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/)
         """
```

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/client.pyi` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/client.py`

 * *Files 4% similar despite different names*

```diff
@@ -30,42 +30,50 @@
 from .type_defs import (
     CrlDetailResponseTypeDef,
     ListCrlsResponseTypeDef,
     ListProfilesResponseTypeDef,
     ListSubjectsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTrustAnchorsResponseTypeDef,
+    NotificationSettingKeyTypeDef,
+    NotificationSettingTypeDef,
     ProfileDetailResponseTypeDef,
+    PutNotificationSettingsResponseTypeDef,
+    ResetNotificationSettingsResponseTypeDef,
     SourceTypeDef,
     SubjectDetailResponseTypeDef,
     TagTypeDef,
     TrustAnchorDetailResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("IAMRolesAnywhereClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     TooManyTagsException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class IAMRolesAnywhereClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/)
     """
 
     meta: ClientMeta
@@ -74,165 +82,187 @@
     def exceptions(self) -> Exceptions:
         """
         IAMRolesAnywhereClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#exceptions)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#close)
         """
+
     async def create_profile(
         self,
         *,
         name: str,
         roleArns: Sequence[str],
         durationSeconds: int = ...,
         enabled: bool = ...,
         managedPolicyArns: Sequence[str] = ...,
         requireInstanceProperties: bool = ...,
         sessionPolicy: str = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> ProfileDetailResponseTypeDef:
         """
-        Creates a profile.
+        Creates a *profile*, a list of the roles that Roles Anywhere service is trusted
+        to assume.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.create_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#create_profile)
         """
+
     async def create_trust_anchor(
         self,
         *,
         name: str,
         source: SourceTypeDef,
         enabled: bool = ...,
+        notificationSettings: Sequence[NotificationSettingTypeDef] = ...,
         tags: Sequence[TagTypeDef] = ...
     ) -> TrustAnchorDetailResponseTypeDef:
         """
-        Creates a trust anchor.
+        Creates a trust anchor to establish trust between IAM Roles Anywhere and your
+        certificate authority (CA).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.create_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#create_trust_anchor)
         """
+
     async def delete_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Deletes a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.delete_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#delete_crl)
         """
+
     async def delete_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
         Deletes a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.delete_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#delete_profile)
         """
+
     async def delete_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Deletes a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.delete_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#delete_trust_anchor)
         """
+
     async def disable_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Disables a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.disable_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#disable_crl)
         """
+
     async def disable_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
         Disables a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.disable_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#disable_profile)
         """
+
     async def disable_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Disables a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.disable_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#disable_trust_anchor)
         """
+
     async def enable_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Enables a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.enable_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#enable_crl)
         """
+
     async def enable_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
-        Enables the roles in a profile to receive session credentials in
-        [CreateSession](https://docs.aws.amazon.com/rolesanywhere/latest/APIReference/API_CreateSession.html)_.
+        Enables temporary credential requests for a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.enable_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#enable_profile)
         """
+
     async def enable_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Enables a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.enable_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#enable_trust_anchor)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#generate_presigned_url)
         """
+
     async def get_crl(self, *, crlId: str) -> CrlDetailResponseTypeDef:
         """
         Gets a certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_crl)
         """
+
     async def get_profile(self, *, profileId: str) -> ProfileDetailResponseTypeDef:
         """
         Gets a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_profile)
         """
+
     async def get_subject(self, *, subjectId: str) -> SubjectDetailResponseTypeDef:
         """
-        Gets a Subject.
+        Gets a *subject*, which associates a certificate identity with authentication
+        attempts.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_subject)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_subject)
         """
+
     async def get_trust_anchor(self, *, trustAnchorId: str) -> TrustAnchorDetailResponseTypeDef:
         """
         Gets a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_trust_anchor)
         """
+
     async def import_crl(
         self,
         *,
         crlData: Union[str, bytes, IO[Any], StreamingBody],
         name: str,
         trustAnchorArn: str,
         enabled: bool = ...,
@@ -240,142 +270,182 @@
     ) -> CrlDetailResponseTypeDef:
         """
         Imports the certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.import_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#import_crl)
         """
+
     async def list_crls(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListCrlsResponseTypeDef:
         """
-        Lists all Crls in the authenticated account and Amazon Web Services Region.
+        Lists all certificate revocation lists (CRL) in the authenticated account and
+        Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_crls)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_crls)
         """
+
     async def list_profiles(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListProfilesResponseTypeDef:
         """
         Lists all profiles in the authenticated account and Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_profiles)
         """
+
     async def list_subjects(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListSubjectsResponseTypeDef:
         """
         Lists the subjects in the authenticated account and Amazon Web Services Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_subjects)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_subjects)
         """
+
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags attached to the resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_tags_for_resource)
         """
+
     async def list_trust_anchors(
         self, *, nextToken: str = ..., pageSize: int = ...
     ) -> ListTrustAnchorsResponseTypeDef:
         """
         Lists the trust anchors in the authenticated account and Amazon Web Services
         Region.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.list_trust_anchors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#list_trust_anchors)
         """
+
+    async def put_notification_settings(
+        self, *, notificationSettings: Sequence[NotificationSettingTypeDef], trustAnchorId: str
+    ) -> PutNotificationSettingsResponseTypeDef:
+        """
+        Attaches a list of *notification settings* to a trust anchor.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.put_notification_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#put_notification_settings)
+        """
+
+    async def reset_notification_settings(
+        self,
+        *,
+        notificationSettingKeys: Sequence[NotificationSettingKeyTypeDef],
+        trustAnchorId: str
+    ) -> ResetNotificationSettingsResponseTypeDef:
+        """
+        Resets the *custom notification setting* to IAM Roles Anywhere default setting.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.reset_notification_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#reset_notification_settings)
+        """
+
     async def tag_resource(self, *, resourceArn: str, tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Attaches tags to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#tag_resource)
         """
+
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from the resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#untag_resource)
         """
+
     async def update_crl(
         self,
         *,
         crlId: str,
         crlData: Union[str, bytes, IO[Any], StreamingBody] = ...,
         name: str = ...
     ) -> CrlDetailResponseTypeDef:
         """
         Updates the certificate revocation list (CRL).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.update_crl)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#update_crl)
         """
+
     async def update_profile(
         self,
         *,
         profileId: str,
         durationSeconds: int = ...,
         managedPolicyArns: Sequence[str] = ...,
         name: str = ...,
         roleArns: Sequence[str] = ...,
         sessionPolicy: str = ...
     ) -> ProfileDetailResponseTypeDef:
         """
-        Updates the profile.
+        Updates a *profile*, a list of the roles that IAM Roles Anywhere service is
+        trusted to assume.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.update_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#update_profile)
         """
+
     async def update_trust_anchor(
         self, *, trustAnchorId: str, name: str = ..., source: SourceTypeDef = ...
     ) -> TrustAnchorDetailResponseTypeDef:
         """
-        Updates the trust anchor.You establish trust between IAM Roles Anywhere and your
-        certificate authority (CA) by configuring a trust anchor.
+        Updates a trust anchor.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.update_trust_anchor)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#update_trust_anchor)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_crls"]) -> ListCrlsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_profiles"]) -> ListProfilesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_subjects"]) -> ListSubjectsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_trust_anchors"]
     ) -> ListTrustAnchorsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "IAMRolesAnywhereClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/client/)
         """
```

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/literals.py` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/literals.py`

 * *Files 14% similar despite different names*

```diff
@@ -20,27 +20,31 @@
 
 
 __all__ = (
     "ListCrlsPaginatorName",
     "ListProfilesPaginatorName",
     "ListSubjectsPaginatorName",
     "ListTrustAnchorsPaginatorName",
+    "NotificationChannelType",
+    "NotificationEventType",
     "TrustAnchorTypeType",
     "IAMRolesAnywhereServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 ListCrlsPaginatorName = Literal["list_crls"]
 ListProfilesPaginatorName = Literal["list_profiles"]
 ListSubjectsPaginatorName = Literal["list_subjects"]
 ListTrustAnchorsPaginatorName = Literal["list_trust_anchors"]
+NotificationChannelType = Literal["ALL"]
+NotificationEventType = Literal["CA_CERTIFICATE_EXPIRY", "END_ENTITY_CERTIFICATE_EXPIRY"]
 TrustAnchorTypeType = Literal["AWS_ACM_PCA", "CERTIFICATE_BUNDLE", "SELF_SIGNED_REPOSITORY"]
 IAMRolesAnywhereServiceName = Literal["rolesanywhere"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -97,14 +101,15 @@
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
@@ -183,14 +188,15 @@
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
@@ -201,14 +207,15 @@
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
@@ -244,14 +251,15 @@
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
@@ -270,16 +278,19 @@
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
@@ -363,15 +374,17 @@
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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/literals.pyi` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/literals.pyi`

 * *Files 14% similar despite different names*

```diff
@@ -19,26 +19,30 @@
     from typing_extensions import Literal
 
 __all__ = (
     "ListCrlsPaginatorName",
     "ListProfilesPaginatorName",
     "ListSubjectsPaginatorName",
     "ListTrustAnchorsPaginatorName",
+    "NotificationChannelType",
+    "NotificationEventType",
     "TrustAnchorTypeType",
     "IAMRolesAnywhereServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 ListCrlsPaginatorName = Literal["list_crls"]
 ListProfilesPaginatorName = Literal["list_profiles"]
 ListSubjectsPaginatorName = Literal["list_subjects"]
 ListTrustAnchorsPaginatorName = Literal["list_trust_anchors"]
+NotificationChannelType = Literal["ALL"]
+NotificationEventType = Literal["CA_CERTIFICATE_EXPIRY", "END_ENTITY_CERTIFICATE_EXPIRY"]
 TrustAnchorTypeType = Literal["AWS_ACM_PCA", "CERTIFICATE_BUNDLE", "SELF_SIGNED_REPOSITORY"]
 IAMRolesAnywhereServiceName = Literal["rolesanywhere"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -95,14 +99,15 @@
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
@@ -181,14 +186,15 @@
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
@@ -199,14 +205,15 @@
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
@@ -242,14 +249,15 @@
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
@@ -268,16 +276,19 @@
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
@@ -361,15 +372,17 @@
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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/paginator.py` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,34 +22,27 @@
 
         list_crls_paginator: ListCrlsPaginator = client.get_paginator("list_crls")
         list_profiles_paginator: ListProfilesPaginator = client.get_paginator("list_profiles")
         list_subjects_paginator: ListSubjectsPaginator = client.get_paginator("list_subjects")
         list_trust_anchors_paginator: ListTrustAnchorsPaginator = client.get_paginator("list_trust_anchors")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListCrlsResponseTypeDef,
     ListProfilesResponseTypeDef,
     ListSubjectsResponseTypeDef,
     ListTrustAnchorsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListCrlsPaginator",
     "ListProfilesPaginator",
     "ListSubjectsPaginator",
     "ListTrustAnchorsPaginator",
 )
 
@@ -67,58 +60,58 @@
 class ListCrlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListCrls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listcrlspaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCrlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListCrls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listcrlspaginator)
         """
 
 
 class ListProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listprofilespaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listprofilespaginator)
         """
 
 
 class ListSubjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListSubjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listsubjectspaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSubjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListSubjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listsubjectspaginator)
         """
 
 
 class ListTrustAnchorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListTrustAnchors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listtrustanchorspaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTrustAnchorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListTrustAnchors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listtrustanchorspaginator)
         """
```

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/paginator.pyi` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -22,33 +22,27 @@
 
         list_crls_paginator: ListCrlsPaginator = client.get_paginator("list_crls")
         list_profiles_paginator: ListProfilesPaginator = client.get_paginator("list_profiles")
         list_subjects_paginator: ListSubjectsPaginator = client.get_paginator("list_subjects")
         list_trust_anchors_paginator: ListTrustAnchorsPaginator = client.get_paginator("list_trust_anchors")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListCrlsResponseTypeDef,
     ListProfilesResponseTypeDef,
     ListSubjectsResponseTypeDef,
     ListTrustAnchorsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListCrlsPaginator",
     "ListProfilesPaginator",
     "ListSubjectsPaginator",
     "ListTrustAnchorsPaginator",
 )
 
@@ -63,55 +57,55 @@
 class ListCrlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListCrls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listcrlspaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCrlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListCrls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listcrlspaginator)
         """
 
 class ListProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listprofilespaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listprofilespaginator)
         """
 
 class ListSubjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListSubjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listsubjectspaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSubjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListSubjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listsubjectspaginator)
         """
 
 class ListTrustAnchorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListTrustAnchors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listtrustanchorspaginator)
     """
 
     def paginate(
-        self, *, pageSize: int = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, pageSize: int = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTrustAnchorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere.Paginator.ListTrustAnchors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/paginators/#listtrustanchorspaginator)
         """
```

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/type_defs.py` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/type_defs.py`

 * *Files 17% similar despite different names*

```diff
@@ -13,72 +13,106 @@
 """
 import sys
 from datetime import datetime
 from typing import IO, Any, Dict, List, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
-from .literals import TrustAnchorTypeType
+from .literals import NotificationEventType, TrustAnchorTypeType
 
 if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TagTypeDef",
+    "NotificationSettingTypeDef",
     "CredentialSummaryTypeDef",
     "CrlDetailTypeDef",
-    "ResponseMetadataTypeDef",
     "InstancePropertyTypeDef",
     "ProfileDetailTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListRequestListCrlsPaginateTypeDef",
+    "ListRequestListProfilesPaginateTypeDef",
+    "ListRequestListSubjectsPaginateTypeDef",
+    "ListRequestListTrustAnchorsPaginateTypeDef",
     "ListRequestRequestTypeDef",
     "SubjectSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "NotificationSettingDetailTypeDef",
+    "NotificationSettingKeyTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ScalarCrlRequestRequestTypeDef",
     "ScalarProfileRequestRequestTypeDef",
     "ScalarSubjectRequestRequestTypeDef",
     "ScalarTrustAnchorRequestRequestTypeDef",
     "SourceDataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCrlRequestRequestTypeDef",
     "UpdateProfileRequestRequestTypeDef",
     "CreateProfileRequestRequestTypeDef",
     "ImportCrlRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "PutNotificationSettingsRequestRequestTypeDef",
     "CrlDetailResponseTypeDef",
     "ListCrlsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "SubjectDetailTypeDef",
     "ListProfilesResponseTypeDef",
     "ProfileDetailResponseTypeDef",
-    "ListRequestListCrlsPaginateTypeDef",
-    "ListRequestListProfilesPaginateTypeDef",
-    "ListRequestListSubjectsPaginateTypeDef",
-    "ListRequestListTrustAnchorsPaginateTypeDef",
     "ListSubjectsResponseTypeDef",
+    "ResetNotificationSettingsRequestRequestTypeDef",
     "SourceTypeDef",
     "SubjectDetailResponseTypeDef",
     "CreateTrustAnchorRequestRequestTypeDef",
     "TrustAnchorDetailTypeDef",
     "UpdateTrustAnchorRequestRequestTypeDef",
     "ListTrustAnchorsResponseTypeDef",
+    "PutNotificationSettingsResponseTypeDef",
+    "ResetNotificationSettingsResponseTypeDef",
     "TrustAnchorDetailResponseTypeDef",
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
+_RequiredNotificationSettingTypeDef = TypedDict(
+    "_RequiredNotificationSettingTypeDef",
+    {
+        "enabled": bool,
+        "event": NotificationEventType,
+    },
+)
+_OptionalNotificationSettingTypeDef = TypedDict(
+    "_OptionalNotificationSettingTypeDef",
+    {
+        "channel": Literal["ALL"],
+        "threshold": int,
+    },
+    total=False,
+)
+
+
+class NotificationSettingTypeDef(
+    _RequiredNotificationSettingTypeDef, _OptionalNotificationSettingTypeDef
+):
+    pass
+
+
 CredentialSummaryTypeDef = TypedDict(
     "CredentialSummaryTypeDef",
     {
         "enabled": bool,
         "failed": bool,
         "issuer": str,
         "seenAt": datetime,
@@ -99,25 +133,14 @@
         "name": str,
         "trustAnchorArn": str,
         "updatedAt": datetime,
     },
     total=False,
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
 InstancePropertyTypeDef = TypedDict(
     "InstancePropertyTypeDef",
     {
         "failed": bool,
         "properties": Dict[str, str],
         "seenAt": datetime,
     },
@@ -139,20 +162,46 @@
         "roleArns": List[str],
         "sessionPolicy": str,
         "updatedAt": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListRequestListCrlsPaginateTypeDef = TypedDict(
+    "ListRequestListCrlsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListRequestListProfilesPaginateTypeDef = TypedDict(
+    "ListRequestListProfilesPaginateTypeDef",
+    {
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListRequestListSubjectsPaginateTypeDef = TypedDict(
+    "ListRequestListSubjectsPaginateTypeDef",
+    {
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListRequestListTrustAnchorsPaginateTypeDef = TypedDict(
+    "ListRequestListTrustAnchorsPaginateTypeDef",
+    {
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRequestRequestTypeDef = TypedDict(
     "ListRequestRequestTypeDef",
     {
@@ -179,14 +228,80 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+_RequiredNotificationSettingDetailTypeDef = TypedDict(
+    "_RequiredNotificationSettingDetailTypeDef",
+    {
+        "enabled": bool,
+        "event": NotificationEventType,
+    },
+)
+_OptionalNotificationSettingDetailTypeDef = TypedDict(
+    "_OptionalNotificationSettingDetailTypeDef",
+    {
+        "channel": Literal["ALL"],
+        "configuredBy": str,
+        "threshold": int,
+    },
+    total=False,
+)
+
+
+class NotificationSettingDetailTypeDef(
+    _RequiredNotificationSettingDetailTypeDef, _OptionalNotificationSettingDetailTypeDef
+):
+    pass
+
+
+_RequiredNotificationSettingKeyTypeDef = TypedDict(
+    "_RequiredNotificationSettingKeyTypeDef",
+    {
+        "event": NotificationEventType,
+    },
+)
+_OptionalNotificationSettingKeyTypeDef = TypedDict(
+    "_OptionalNotificationSettingKeyTypeDef",
+    {
+        "channel": Literal["ALL"],
+    },
+    total=False,
+)
+
+
+class NotificationSettingKeyTypeDef(
+    _RequiredNotificationSettingKeyTypeDef, _OptionalNotificationSettingKeyTypeDef
+):
+    pass
+
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
 ScalarCrlRequestRequestTypeDef = TypedDict(
     "ScalarCrlRequestRequestTypeDef",
     {
         "crlId": str,
     },
 )
 
@@ -322,44 +437,52 @@
 
 class ImportCrlRequestRequestTypeDef(
     _RequiredImportCrlRequestRequestTypeDef, _OptionalImportCrlRequestRequestTypeDef
 ):
     pass
 
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Sequence[TagTypeDef],
     },
 )
 
+PutNotificationSettingsRequestRequestTypeDef = TypedDict(
+    "PutNotificationSettingsRequestRequestTypeDef",
+    {
+        "notificationSettings": Sequence[NotificationSettingTypeDef],
+        "trustAnchorId": str,
+    },
+)
+
 CrlDetailResponseTypeDef = TypedDict(
     "CrlDetailResponseTypeDef",
     {
         "crl": CrlDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCrlsResponseTypeDef = TypedDict(
     "ListCrlsResponseTypeDef",
     {
         "crls": List[CrlDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubjectDetailTypeDef = TypedDict(
     "SubjectDetailTypeDef",
     {
         "createdAt": datetime,
@@ -376,68 +499,40 @@
 )
 
 ListProfilesResponseTypeDef = TypedDict(
     "ListProfilesResponseTypeDef",
     {
         "nextToken": str,
         "profiles": List[ProfileDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProfileDetailResponseTypeDef = TypedDict(
     "ProfileDetailResponseTypeDef",
     {
         "profile": ProfileDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListRequestListCrlsPaginateTypeDef = TypedDict(
-    "ListRequestListCrlsPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRequestListProfilesPaginateTypeDef = TypedDict(
-    "ListRequestListProfilesPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRequestListSubjectsPaginateTypeDef = TypedDict(
-    "ListRequestListSubjectsPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRequestListTrustAnchorsPaginateTypeDef = TypedDict(
-    "ListRequestListTrustAnchorsPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListSubjectsResponseTypeDef = TypedDict(
     "ListSubjectsResponseTypeDef",
     {
         "nextToken": str,
         "subjects": List[SubjectSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResetNotificationSettingsRequestRequestTypeDef = TypedDict(
+    "ResetNotificationSettingsRequestRequestTypeDef",
+    {
+        "notificationSettingKeys": Sequence[NotificationSettingKeyTypeDef],
+        "trustAnchorId": str,
     },
 )
 
 SourceTypeDef = TypedDict(
     "SourceTypeDef",
     {
         "sourceData": SourceDataTypeDef,
@@ -446,29 +541,30 @@
     total=False,
 )
 
 SubjectDetailResponseTypeDef = TypedDict(
     "SubjectDetailResponseTypeDef",
     {
         "subject": SubjectDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateTrustAnchorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTrustAnchorRequestRequestTypeDef",
     {
         "name": str,
         "source": SourceTypeDef,
     },
 )
 _OptionalCreateTrustAnchorRequestRequestTypeDef = TypedDict(
     "_OptionalCreateTrustAnchorRequestRequestTypeDef",
     {
         "enabled": bool,
+        "notificationSettings": Sequence[NotificationSettingTypeDef],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
 
 class CreateTrustAnchorRequestRequestTypeDef(
@@ -479,14 +575,15 @@
 
 TrustAnchorDetailTypeDef = TypedDict(
     "TrustAnchorDetailTypeDef",
     {
         "createdAt": datetime,
         "enabled": bool,
         "name": str,
+        "notificationSettings": List[NotificationSettingDetailTypeDef],
         "source": SourceTypeDef,
         "trustAnchorArn": str,
         "trustAnchorId": str,
         "updatedAt": datetime,
     },
     total=False,
 )
@@ -514,18 +611,34 @@
 
 
 ListTrustAnchorsResponseTypeDef = TypedDict(
     "ListTrustAnchorsResponseTypeDef",
     {
         "nextToken": str,
         "trustAnchors": List[TrustAnchorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutNotificationSettingsResponseTypeDef = TypedDict(
+    "PutNotificationSettingsResponseTypeDef",
+    {
+        "trustAnchor": TrustAnchorDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResetNotificationSettingsResponseTypeDef = TypedDict(
+    "ResetNotificationSettingsResponseTypeDef",
+    {
+        "trustAnchor": TrustAnchorDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrustAnchorDetailResponseTypeDef = TypedDict(
     "TrustAnchorDetailResponseTypeDef",
     {
         "trustAnchor": TrustAnchorDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere/type_defs.pyi` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere/type_defs.pyi`

 * *Files 21% similar despite different names*

```diff
@@ -13,71 +13,103 @@
 """
 import sys
 from datetime import datetime
 from typing import IO, Any, Dict, List, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
-from .literals import TrustAnchorTypeType
+from .literals import NotificationEventType, TrustAnchorTypeType
 
 if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagTypeDef",
+    "NotificationSettingTypeDef",
     "CredentialSummaryTypeDef",
     "CrlDetailTypeDef",
-    "ResponseMetadataTypeDef",
     "InstancePropertyTypeDef",
     "ProfileDetailTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListRequestListCrlsPaginateTypeDef",
+    "ListRequestListProfilesPaginateTypeDef",
+    "ListRequestListSubjectsPaginateTypeDef",
+    "ListRequestListTrustAnchorsPaginateTypeDef",
     "ListRequestRequestTypeDef",
     "SubjectSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "NotificationSettingDetailTypeDef",
+    "NotificationSettingKeyTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "ScalarCrlRequestRequestTypeDef",
     "ScalarProfileRequestRequestTypeDef",
     "ScalarSubjectRequestRequestTypeDef",
     "ScalarTrustAnchorRequestRequestTypeDef",
     "SourceDataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCrlRequestRequestTypeDef",
     "UpdateProfileRequestRequestTypeDef",
     "CreateProfileRequestRequestTypeDef",
     "ImportCrlRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "PutNotificationSettingsRequestRequestTypeDef",
     "CrlDetailResponseTypeDef",
     "ListCrlsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "SubjectDetailTypeDef",
     "ListProfilesResponseTypeDef",
     "ProfileDetailResponseTypeDef",
-    "ListRequestListCrlsPaginateTypeDef",
-    "ListRequestListProfilesPaginateTypeDef",
-    "ListRequestListSubjectsPaginateTypeDef",
-    "ListRequestListTrustAnchorsPaginateTypeDef",
     "ListSubjectsResponseTypeDef",
+    "ResetNotificationSettingsRequestRequestTypeDef",
     "SourceTypeDef",
     "SubjectDetailResponseTypeDef",
     "CreateTrustAnchorRequestRequestTypeDef",
     "TrustAnchorDetailTypeDef",
     "UpdateTrustAnchorRequestRequestTypeDef",
     "ListTrustAnchorsResponseTypeDef",
+    "PutNotificationSettingsResponseTypeDef",
+    "ResetNotificationSettingsResponseTypeDef",
     "TrustAnchorDetailResponseTypeDef",
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
+_RequiredNotificationSettingTypeDef = TypedDict(
+    "_RequiredNotificationSettingTypeDef",
+    {
+        "enabled": bool,
+        "event": NotificationEventType,
+    },
+)
+_OptionalNotificationSettingTypeDef = TypedDict(
+    "_OptionalNotificationSettingTypeDef",
+    {
+        "channel": Literal["ALL"],
+        "threshold": int,
+    },
+    total=False,
+)
+
+class NotificationSettingTypeDef(
+    _RequiredNotificationSettingTypeDef, _OptionalNotificationSettingTypeDef
+):
+    pass
+
 CredentialSummaryTypeDef = TypedDict(
     "CredentialSummaryTypeDef",
     {
         "enabled": bool,
         "failed": bool,
         "issuer": str,
         "seenAt": datetime,
@@ -98,25 +130,14 @@
         "name": str,
         "trustAnchorArn": str,
         "updatedAt": datetime,
     },
     total=False,
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
 InstancePropertyTypeDef = TypedDict(
     "InstancePropertyTypeDef",
     {
         "failed": bool,
         "properties": Dict[str, str],
         "seenAt": datetime,
     },
@@ -138,20 +159,46 @@
         "roleArns": List[str],
         "sessionPolicy": str,
         "updatedAt": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListRequestListCrlsPaginateTypeDef = TypedDict(
+    "ListRequestListCrlsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListRequestListProfilesPaginateTypeDef = TypedDict(
+    "ListRequestListProfilesPaginateTypeDef",
+    {
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListRequestListSubjectsPaginateTypeDef = TypedDict(
+    "ListRequestListSubjectsPaginateTypeDef",
+    {
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListRequestListTrustAnchorsPaginateTypeDef = TypedDict(
+    "ListRequestListTrustAnchorsPaginateTypeDef",
+    {
+        "pageSize": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRequestRequestTypeDef = TypedDict(
     "ListRequestRequestTypeDef",
     {
@@ -178,14 +225,76 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+_RequiredNotificationSettingDetailTypeDef = TypedDict(
+    "_RequiredNotificationSettingDetailTypeDef",
+    {
+        "enabled": bool,
+        "event": NotificationEventType,
+    },
+)
+_OptionalNotificationSettingDetailTypeDef = TypedDict(
+    "_OptionalNotificationSettingDetailTypeDef",
+    {
+        "channel": Literal["ALL"],
+        "configuredBy": str,
+        "threshold": int,
+    },
+    total=False,
+)
+
+class NotificationSettingDetailTypeDef(
+    _RequiredNotificationSettingDetailTypeDef, _OptionalNotificationSettingDetailTypeDef
+):
+    pass
+
+_RequiredNotificationSettingKeyTypeDef = TypedDict(
+    "_RequiredNotificationSettingKeyTypeDef",
+    {
+        "event": NotificationEventType,
+    },
+)
+_OptionalNotificationSettingKeyTypeDef = TypedDict(
+    "_OptionalNotificationSettingKeyTypeDef",
+    {
+        "channel": Literal["ALL"],
+    },
+    total=False,
+)
+
+class NotificationSettingKeyTypeDef(
+    _RequiredNotificationSettingKeyTypeDef, _OptionalNotificationSettingKeyTypeDef
+):
+    pass
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
 ScalarCrlRequestRequestTypeDef = TypedDict(
     "ScalarCrlRequestRequestTypeDef",
     {
         "crlId": str,
     },
 )
 
@@ -313,44 +422,52 @@
 )
 
 class ImportCrlRequestRequestTypeDef(
     _RequiredImportCrlRequestRequestTypeDef, _OptionalImportCrlRequestRequestTypeDef
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Sequence[TagTypeDef],
     },
 )
 
+PutNotificationSettingsRequestRequestTypeDef = TypedDict(
+    "PutNotificationSettingsRequestRequestTypeDef",
+    {
+        "notificationSettings": Sequence[NotificationSettingTypeDef],
+        "trustAnchorId": str,
+    },
+)
+
 CrlDetailResponseTypeDef = TypedDict(
     "CrlDetailResponseTypeDef",
     {
         "crl": CrlDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCrlsResponseTypeDef = TypedDict(
     "ListCrlsResponseTypeDef",
     {
         "crls": List[CrlDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubjectDetailTypeDef = TypedDict(
     "SubjectDetailTypeDef",
     {
         "createdAt": datetime,
@@ -367,68 +484,40 @@
 )
 
 ListProfilesResponseTypeDef = TypedDict(
     "ListProfilesResponseTypeDef",
     {
         "nextToken": str,
         "profiles": List[ProfileDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProfileDetailResponseTypeDef = TypedDict(
     "ProfileDetailResponseTypeDef",
     {
         "profile": ProfileDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRequestListCrlsPaginateTypeDef = TypedDict(
-    "ListRequestListCrlsPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListRequestListProfilesPaginateTypeDef = TypedDict(
-    "ListRequestListProfilesPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRequestListSubjectsPaginateTypeDef = TypedDict(
-    "ListRequestListSubjectsPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRequestListTrustAnchorsPaginateTypeDef = TypedDict(
-    "ListRequestListTrustAnchorsPaginateTypeDef",
-    {
-        "pageSize": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListSubjectsResponseTypeDef = TypedDict(
     "ListSubjectsResponseTypeDef",
     {
         "nextToken": str,
         "subjects": List[SubjectSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResetNotificationSettingsRequestRequestTypeDef = TypedDict(
+    "ResetNotificationSettingsRequestRequestTypeDef",
+    {
+        "notificationSettingKeys": Sequence[NotificationSettingKeyTypeDef],
+        "trustAnchorId": str,
     },
 )
 
 SourceTypeDef = TypedDict(
     "SourceTypeDef",
     {
         "sourceData": SourceDataTypeDef,
@@ -437,29 +526,30 @@
     total=False,
 )
 
 SubjectDetailResponseTypeDef = TypedDict(
     "SubjectDetailResponseTypeDef",
     {
         "subject": SubjectDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateTrustAnchorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateTrustAnchorRequestRequestTypeDef",
     {
         "name": str,
         "source": SourceTypeDef,
     },
 )
 _OptionalCreateTrustAnchorRequestRequestTypeDef = TypedDict(
     "_OptionalCreateTrustAnchorRequestRequestTypeDef",
     {
         "enabled": bool,
+        "notificationSettings": Sequence[NotificationSettingTypeDef],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
 class CreateTrustAnchorRequestRequestTypeDef(
     _RequiredCreateTrustAnchorRequestRequestTypeDef, _OptionalCreateTrustAnchorRequestRequestTypeDef
@@ -468,14 +558,15 @@
 
 TrustAnchorDetailTypeDef = TypedDict(
     "TrustAnchorDetailTypeDef",
     {
         "createdAt": datetime,
         "enabled": bool,
         "name": str,
+        "notificationSettings": List[NotificationSettingDetailTypeDef],
         "source": SourceTypeDef,
         "trustAnchorArn": str,
         "trustAnchorId": str,
         "updatedAt": datetime,
     },
     total=False,
 )
@@ -501,18 +592,34 @@
     pass
 
 ListTrustAnchorsResponseTypeDef = TypedDict(
     "ListTrustAnchorsResponseTypeDef",
     {
         "nextToken": str,
         "trustAnchors": List[TrustAnchorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutNotificationSettingsResponseTypeDef = TypedDict(
+    "PutNotificationSettingsResponseTypeDef",
+    {
+        "trustAnchor": TrustAnchorDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResetNotificationSettingsResponseTypeDef = TypedDict(
+    "ResetNotificationSettingsResponseTypeDef",
+    {
+        "trustAnchor": TrustAnchorDetailTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrustAnchorDetailResponseTypeDef = TypedDict(
     "TrustAnchorDetailResponseTypeDef",
     {
         "trustAnchor": TrustAnchorDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/PKG-INFO` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-rolesanywhere
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IAMRolesAnywhere 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IAMRolesAnywhere 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-rolesanywhere"></a>
 
 # types-aiobotocore-rolesanywhere
 
 [![PyPI - types-aiobotocore-rolesanywhere](https://img.shields.io/pypi/v/types-aiobotocore-rolesanywhere.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rolesanywhere)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-rolesanywhere.svg?color=blue)](https://pypi.org/project/types-aiobotocore-rolesanywhere)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-rolesanywhere?color=blue)](https://pypistats.org/packages/types-aiobotocore-rolesanywhere)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IAMRolesAnywhere 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere)
+[aiobotocore.IAMRolesAnywhere 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/rolesanywhere.html#IAMRolesAnywhere)
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
 [types-aiobotocore-rolesanywhere docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rolesanywhere/).
 
 See how it helps to find and fix potential bugs:
 
@@ -306,14 +306,16 @@
 
 ```python
 from types_aiobotocore_rolesanywhere.literals import (
     ListCrlsPaginatorName,
     ListProfilesPaginatorName,
     ListSubjectsPaginatorName,
     ListTrustAnchorsPaginatorName,
+    NotificationChannelType,
+    NotificationEventType,
     TrustAnchorTypeType,
     IAMRolesAnywhereServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -329,51 +331,58 @@
 
 `types_aiobotocore_rolesanywhere.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_rolesanywhere.type_defs import (
     TagTypeDef,
+    NotificationSettingTypeDef,
     CredentialSummaryTypeDef,
     CrlDetailTypeDef,
-    ResponseMetadataTypeDef,
     InstancePropertyTypeDef,
     ProfileDetailTypeDef,
-    PaginatorConfigTypeDef,
+    ListRequestListCrlsPaginateTypeDef,
+    ListRequestListProfilesPaginateTypeDef,
+    ListRequestListSubjectsPaginateTypeDef,
+    ListRequestListTrustAnchorsPaginateTypeDef,
     ListRequestRequestTypeDef,
     SubjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    NotificationSettingDetailTypeDef,
+    NotificationSettingKeyTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     ScalarCrlRequestRequestTypeDef,
     ScalarProfileRequestRequestTypeDef,
     ScalarSubjectRequestRequestTypeDef,
     ScalarTrustAnchorRequestRequestTypeDef,
     SourceDataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCrlRequestRequestTypeDef,
     UpdateProfileRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     ImportCrlRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    PutNotificationSettingsRequestRequestTypeDef,
     CrlDetailResponseTypeDef,
     ListCrlsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     SubjectDetailTypeDef,
     ListProfilesResponseTypeDef,
     ProfileDetailResponseTypeDef,
-    ListRequestListCrlsPaginateTypeDef,
-    ListRequestListProfilesPaginateTypeDef,
-    ListRequestListSubjectsPaginateTypeDef,
-    ListRequestListTrustAnchorsPaginateTypeDef,
     ListSubjectsResponseTypeDef,
+    ResetNotificationSettingsRequestRequestTypeDef,
     SourceTypeDef,
     SubjectDetailResponseTypeDef,
     CreateTrustAnchorRequestRequestTypeDef,
     TrustAnchorDetailTypeDef,
     UpdateTrustAnchorRequestRequestTypeDef,
     ListTrustAnchorsResponseTypeDef,
+    PutNotificationSettingsResponseTypeDef,
+    ResetNotificationSettingsResponseTypeDef,
     TrustAnchorDetailResponseTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
     return {...}
 ```
@@ -381,43 +390,43 @@
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

### Comparing `types-aiobotocore-rolesanywhere-2.5.0.post1/types_aiobotocore_rolesanywhere.egg-info/SOURCES.txt` & `types-aiobotocore-rolesanywhere-2.5.1/types_aiobotocore_rolesanywhere.egg-info/SOURCES.txt`

 * *Files identical despite different names*

