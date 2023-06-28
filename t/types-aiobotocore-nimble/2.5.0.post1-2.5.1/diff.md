# Comparing `tmp/types-aiobotocore-nimble-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-nimble-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-nimble-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-nimble-2.5.1.tar", last modified: Wed Jun 28 01:43:54 2023, max compression
```

## Comparing `types-aiobotocore-nimble-2.5.0.post1.tar` & `types-aiobotocore-nimble-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.683465 types-aiobotocore-nimble-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    25153 2023-03-11 12:27:03.679465 types-aiobotocore-nimble-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    23580 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.683465 types-aiobotocore-nimble-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2123 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.679465 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/
--rw-r--r--   0 runner    (1001) docker     (123)     5224 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5223 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      940 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    47143 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    47063 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17755 2023-03-11 12:19:15.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    17753 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13006 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12993 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    70020 2023-03-11 12:19:16.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    69903 2023-03-11 12:19:15.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    13016 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)    13004 2023-03-11 12:19:14.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.679465 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    25153 2023-03-11 12:27:03.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      865 2023-03-11 12:27:03.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.422183 types-aiobotocore-nimble-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    25144 2023-06-28 01:43:54.422183 types-aiobotocore-nimble-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    23577 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:54.422183 types-aiobotocore-nimble-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.418183 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/
+-rw-r--r--   0 runner    (1001) docker     (123)     5224 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5223 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      928 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47143 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47063 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    18079 2023-06-28 01:35:59.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18077 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12938 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12926 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    70126 2023-06-28 01:36:00.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70009 2023-06-28 01:35:59.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13016 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13004 2023-06-28 01:35:58.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.422183 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    25144 2023-06-28 01:43:54.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      865 2023-06-28 01:43:54.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:54.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:54.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:54.000000 types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-nimble-2.5.0.post1/LICENSE` & `types-aiobotocore-nimble-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-nimble-2.5.0.post1/PKG-INFO` & `types-aiobotocore-nimble-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-nimble
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.NimbleStudio 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.NimbleStudio 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-nimble"></a>
 
 # types-aiobotocore-nimble
 
 [![PyPI - types-aiobotocore-nimble](https://img.shields.io/pypi/v/types-aiobotocore-nimble.svg?color=blue)](https://pypi.org/project/types-aiobotocore-nimble)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-nimble.svg?color=blue)](https://pypi.org/project/types-aiobotocore-nimble)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-nimble?color=blue)](https://pypistats.org/packages/types-aiobotocore-nimble)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NimbleStudio 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio)
+[aiobotocore.NimbleStudio 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio)
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
 [types-aiobotocore-nimble docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/).
 
 See how it helps to find and fix potential bugs:
 
@@ -471,15 +471,14 @@
 `types_aiobotocore_nimble.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_nimble.type_defs import (
     AcceptEulasRequestRequestTypeDef,
     EulaAcceptanceTypeDef,
-    ResponseMetadataTypeDef,
     ActiveDirectoryComputerAttributeTypeDef,
     ComputeFarmConfigurationTypeDef,
     CreateStreamingImageRequestRequestTypeDef,
     CreateStreamingSessionRequestRequestTypeDef,
     CreateStreamingSessionStreamRequestRequestTypeDef,
     StreamingSessionStreamTypeDef,
     ScriptParameterKeyValueTypeDef,
@@ -509,28 +508,40 @@
     GetStudioComponentRequestRequestTypeDef,
     GetStudioMemberRequestRequestTypeDef,
     StudioMembershipTypeDef,
     GetStudioRequestRequestTypeDef,
     LaunchProfileInitializationScriptTypeDef,
     ValidationResultTypeDef,
     LicenseServiceConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
     ListEulaAcceptancesRequestRequestTypeDef,
+    ListEulasRequestListEulasPaginateTypeDef,
     ListEulasRequestRequestTypeDef,
+    ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
     ListLaunchProfileMembersRequestRequestTypeDef,
+    ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
     ListLaunchProfilesRequestRequestTypeDef,
+    ListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
     ListStreamingImagesRequestRequestTypeDef,
+    ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
     ListStreamingSessionBackupsRequestRequestTypeDef,
+    ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
     ListStreamingSessionsRequestRequestTypeDef,
+    ListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
     ListStudioComponentsRequestRequestTypeDef,
+    ListStudioMembersRequestListStudioMembersPaginateTypeDef,
     ListStudioMembersRequestRequestTypeDef,
+    ListStudiosRequestListStudiosPaginateTypeDef,
     ListStudiosRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NewLaunchProfileMemberTypeDef,
     NewStudioMemberTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SharedFileSystemConfigurationTypeDef,
     StartStreamingSessionRequestRequestTypeDef,
     StartStudioSSOConfigurationRepairRequestRequestTypeDef,
     StopStreamingSessionRequestRequestTypeDef,
     StreamConfigurationSessionBackupTypeDef,
     VolumeConfigurationTypeDef,
     StreamingSessionStorageRootTypeDef,
@@ -538,15 +549,14 @@
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLaunchProfileMemberRequestRequestTypeDef,
     UpdateStreamingImageRequestRequestTypeDef,
     UpdateStudioRequestRequestTypeDef,
     AcceptEulasResponseTypeDef,
     ListEulaAcceptancesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     ActiveDirectoryConfigurationTypeDef,
     LaunchProfileInitializationActiveDirectoryTypeDef,
     CreateStreamingSessionStreamResponseTypeDef,
     GetStreamingSessionStreamResponseTypeDef,
     CreateStudioRequestRequestTypeDef,
     StudioTypeDef,
     GetEulaResponseTypeDef,
@@ -566,24 +576,14 @@
     GetStudioComponentRequestStudioComponentReadyWaitTypeDef,
     GetStudioRequestStudioDeletedWaitTypeDef,
     GetStudioRequestStudioReadyWaitTypeDef,
     GetStreamingSessionBackupResponseTypeDef,
     ListStreamingSessionBackupsResponseTypeDef,
     GetStudioMemberResponseTypeDef,
     ListStudioMembersResponseTypeDef,
-    ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
-    ListEulasRequestListEulasPaginateTypeDef,
-    ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
-    ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
-    ListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
-    ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
-    ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
-    ListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
-    ListStudioMembersRequestListStudioMembersPaginateTypeDef,
-    ListStudiosRequestListStudiosPaginateTypeDef,
     PutLaunchProfileMembersRequestRequestTypeDef,
     PutStudioMembersRequestRequestTypeDef,
     StreamingSessionTypeDef,
     StreamConfigurationSessionStorageTypeDef,
     StreamingImageTypeDef,
     StudioComponentConfigurationTypeDef,
     LaunchProfileInitializationTypeDef,
@@ -634,43 +634,43 @@
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

### Comparing `types-aiobotocore-nimble-2.5.0.post1/README.md` & `types-aiobotocore-nimble-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-nimble"></a>
 
 # types-aiobotocore-nimble
 
 [![PyPI - types-aiobotocore-nimble](https://img.shields.io/pypi/v/types-aiobotocore-nimble.svg?color=blue)](https://pypi.org/project/types-aiobotocore-nimble)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-nimble.svg?color=blue)](https://pypi.org/project/types-aiobotocore-nimble)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-nimble?color=blue)](https://pypistats.org/packages/types-aiobotocore-nimble)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NimbleStudio 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio)
+[aiobotocore.NimbleStudio 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio)
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
 [types-aiobotocore-nimble docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/).
 
 See how it helps to find and fix potential bugs:
 
@@ -438,15 +438,14 @@
 `types_aiobotocore_nimble.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_nimble.type_defs import (
     AcceptEulasRequestRequestTypeDef,
     EulaAcceptanceTypeDef,
-    ResponseMetadataTypeDef,
     ActiveDirectoryComputerAttributeTypeDef,
     ComputeFarmConfigurationTypeDef,
     CreateStreamingImageRequestRequestTypeDef,
     CreateStreamingSessionRequestRequestTypeDef,
     CreateStreamingSessionStreamRequestRequestTypeDef,
     StreamingSessionStreamTypeDef,
     ScriptParameterKeyValueTypeDef,
@@ -476,28 +475,40 @@
     GetStudioComponentRequestRequestTypeDef,
     GetStudioMemberRequestRequestTypeDef,
     StudioMembershipTypeDef,
     GetStudioRequestRequestTypeDef,
     LaunchProfileInitializationScriptTypeDef,
     ValidationResultTypeDef,
     LicenseServiceConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
     ListEulaAcceptancesRequestRequestTypeDef,
+    ListEulasRequestListEulasPaginateTypeDef,
     ListEulasRequestRequestTypeDef,
+    ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
     ListLaunchProfileMembersRequestRequestTypeDef,
+    ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
     ListLaunchProfilesRequestRequestTypeDef,
+    ListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
     ListStreamingImagesRequestRequestTypeDef,
+    ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
     ListStreamingSessionBackupsRequestRequestTypeDef,
+    ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
     ListStreamingSessionsRequestRequestTypeDef,
+    ListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
     ListStudioComponentsRequestRequestTypeDef,
+    ListStudioMembersRequestListStudioMembersPaginateTypeDef,
     ListStudioMembersRequestRequestTypeDef,
+    ListStudiosRequestListStudiosPaginateTypeDef,
     ListStudiosRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NewLaunchProfileMemberTypeDef,
     NewStudioMemberTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SharedFileSystemConfigurationTypeDef,
     StartStreamingSessionRequestRequestTypeDef,
     StartStudioSSOConfigurationRepairRequestRequestTypeDef,
     StopStreamingSessionRequestRequestTypeDef,
     StreamConfigurationSessionBackupTypeDef,
     VolumeConfigurationTypeDef,
     StreamingSessionStorageRootTypeDef,
@@ -505,15 +516,14 @@
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLaunchProfileMemberRequestRequestTypeDef,
     UpdateStreamingImageRequestRequestTypeDef,
     UpdateStudioRequestRequestTypeDef,
     AcceptEulasResponseTypeDef,
     ListEulaAcceptancesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     ActiveDirectoryConfigurationTypeDef,
     LaunchProfileInitializationActiveDirectoryTypeDef,
     CreateStreamingSessionStreamResponseTypeDef,
     GetStreamingSessionStreamResponseTypeDef,
     CreateStudioRequestRequestTypeDef,
     StudioTypeDef,
     GetEulaResponseTypeDef,
@@ -533,24 +543,14 @@
     GetStudioComponentRequestStudioComponentReadyWaitTypeDef,
     GetStudioRequestStudioDeletedWaitTypeDef,
     GetStudioRequestStudioReadyWaitTypeDef,
     GetStreamingSessionBackupResponseTypeDef,
     ListStreamingSessionBackupsResponseTypeDef,
     GetStudioMemberResponseTypeDef,
     ListStudioMembersResponseTypeDef,
-    ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
-    ListEulasRequestListEulasPaginateTypeDef,
-    ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
-    ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
-    ListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
-    ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
-    ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
-    ListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
-    ListStudioMembersRequestListStudioMembersPaginateTypeDef,
-    ListStudiosRequestListStudiosPaginateTypeDef,
     PutLaunchProfileMembersRequestRequestTypeDef,
     PutStudioMembersRequestRequestTypeDef,
     StreamingSessionTypeDef,
     StreamConfigurationSessionStorageTypeDef,
     StreamingImageTypeDef,
     StudioComponentConfigurationTypeDef,
     LaunchProfileInitializationTypeDef,
@@ -601,43 +601,43 @@
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

### Comparing `types-aiobotocore-nimble-2.5.0.post1/setup.py` & `types-aiobotocore-nimble-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-nimble.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-nimble",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_nimble"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.NimbleStudio 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.NimbleStudio 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/"
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

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/__init__.py` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/__init__.pyi` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/__main__.py` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.NimbleStudio 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.NimbleStudio 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio\nOther"
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

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/client.py` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/client.pyi` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/literals.py` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -362,14 +362,15 @@
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
@@ -448,14 +449,15 @@
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
@@ -466,14 +468,15 @@
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
@@ -509,14 +512,15 @@
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
@@ -535,16 +539,19 @@
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
@@ -628,15 +635,17 @@
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
@@ -681,9 +690,19 @@
     "streaming_session_stream_ready",
     "studio_component_deleted",
     "studio_component_ready",
     "studio_deleted",
     "studio_ready",
 ]
 RegionName = Literal[
-    "ap-northeast-1", "ap-southeast-2", "ca-central-1", "eu-west-2", "us-east-1", "us-west-2"
+    "ap-northeast-1",
+    "ap-southeast-1",
+    "ap-southeast-2",
+    "ca-central-1",
+    "eu-central-1",
+    "eu-north-1",
+    "eu-west-1",
+    "eu-west-2",
+    "us-east-1",
+    "us-east-2",
+    "us-west-2",
 ]
```

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/literals.pyi` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -360,14 +360,15 @@
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
@@ -446,14 +447,15 @@
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
@@ -464,14 +466,15 @@
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
@@ -507,14 +510,15 @@
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
@@ -533,16 +537,19 @@
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
@@ -626,15 +633,17 @@
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
@@ -679,9 +688,19 @@
     "streaming_session_stream_ready",
     "studio_component_deleted",
     "studio_component_ready",
     "studio_deleted",
     "studio_ready",
 ]
 RegionName = Literal[
-    "ap-northeast-1", "ap-southeast-2", "ca-central-1", "eu-west-2", "us-east-1", "us-west-2"
+    "ap-northeast-1",
+    "ap-southeast-1",
+    "ap-southeast-2",
+    "ca-central-1",
+    "eu-central-1",
+    "eu-north-1",
+    "eu-west-1",
+    "eu-west-2",
+    "us-east-1",
+    "us-east-2",
+    "us-west-2",
 ]
```

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/paginator.py` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_streaming_session_backups_paginator: ListStreamingSessionBackupsPaginator = client.get_paginator("list_streaming_session_backups")
         list_streaming_sessions_paginator: ListStreamingSessionsPaginator = client.get_paginator("list_streaming_sessions")
         list_studio_components_paginator: ListStudioComponentsPaginator = client.get_paginator("list_studio_components")
         list_studio_members_paginator: ListStudioMembersPaginator = client.get_paginator("list_studio_members")
         list_studios_paginator: ListStudiosPaginator = client.get_paginator("list_studios")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import LaunchProfileStateType, StudioComponentStateType, StudioComponentTypeType
 from .type_defs import (
     ListEulaAcceptancesResponseTypeDef,
@@ -55,20 +54,14 @@
     ListStreamingSessionsResponseTypeDef,
     ListStudioComponentsResponseTypeDef,
     ListStudioMembersResponseTypeDef,
     ListStudiosResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListEulaAcceptancesPaginator",
     "ListEulasPaginator",
     "ListLaunchProfileMembersPaginator",
     "ListLaunchProfilesPaginator",
     "ListStreamingImagesPaginator",
     "ListStreamingSessionBackupsPaginator",
@@ -96,45 +89,49 @@
     """
 
     def paginate(
         self,
         *,
         studioId: str,
         eulaIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEulaAcceptancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListEulaAcceptances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listeulaacceptancespaginator)
         """
 
 
 class ListEulasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListEulas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listeulaspaginator)
     """
 
     def paginate(
-        self, *, eulaIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, eulaIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEulasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListEulas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listeulaspaginator)
         """
 
 
 class ListLaunchProfileMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListLaunchProfileMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listlaunchprofilememberspaginator)
     """
 
     def paginate(
-        self, *, launchProfileId: str, studioId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        launchProfileId: str,
+        studioId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLaunchProfileMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListLaunchProfileMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listlaunchprofilememberspaginator)
         """
 
 
@@ -146,45 +143,45 @@
 
     def paginate(
         self,
         *,
         studioId: str,
         principalId: str = ...,
         states: Sequence[LaunchProfileStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLaunchProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListLaunchProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listlaunchprofilespaginator)
         """
 
 
 class ListStreamingImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingimagespaginator)
     """
 
     def paginate(
-        self, *, studioId: str, owner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, studioId: str, owner: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingimagespaginator)
         """
 
 
 class ListStreamingSessionBackupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingSessionBackups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingsessionbackupspaginator)
     """
 
     def paginate(
-        self, *, studioId: str, ownedBy: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, studioId: str, ownedBy: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingSessionBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingSessionBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingsessionbackupspaginator)
         """
 
 
@@ -197,15 +194,15 @@
     def paginate(
         self,
         *,
         studioId: str,
         createdBy: str = ...,
         ownedBy: str = ...,
         sessionIds: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingSessionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingsessionspaginator)
         """
 
 
@@ -217,43 +214,43 @@
 
     def paginate(
         self,
         *,
         studioId: str,
         states: Sequence[StudioComponentStateType] = ...,
         types: Sequence[StudioComponentTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStudioComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudioComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiocomponentspaginator)
         """
 
 
 class ListStudioMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudioMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiomemberspaginator)
     """
 
     def paginate(
-        self, *, studioId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, studioId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStudioMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudioMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiomemberspaginator)
         """
 
 
 class ListStudiosPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudios)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiospaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStudiosResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudios.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiospaginator)
         """
```

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/paginator.pyi` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_streaming_session_backups_paginator: ListStreamingSessionBackupsPaginator = client.get_paginator("list_streaming_session_backups")
         list_streaming_sessions_paginator: ListStreamingSessionsPaginator = client.get_paginator("list_streaming_sessions")
         list_studio_components_paginator: ListStudioComponentsPaginator = client.get_paginator("list_studio_components")
         list_studio_members_paginator: ListStudioMembersPaginator = client.get_paginator("list_studio_members")
         list_studios_paginator: ListStudiosPaginator = client.get_paginator("list_studios")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import LaunchProfileStateType, StudioComponentStateType, StudioComponentTypeType
 from .type_defs import (
     ListEulaAcceptancesResponseTypeDef,
@@ -55,19 +54,14 @@
     ListStreamingSessionsResponseTypeDef,
     ListStudioComponentsResponseTypeDef,
     ListStudioMembersResponseTypeDef,
     ListStudiosResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListEulaAcceptancesPaginator",
     "ListEulasPaginator",
     "ListLaunchProfileMembersPaginator",
     "ListLaunchProfilesPaginator",
     "ListStreamingImagesPaginator",
     "ListStreamingSessionBackupsPaginator",
@@ -92,43 +86,47 @@
     """
 
     def paginate(
         self,
         *,
         studioId: str,
         eulaIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEulaAcceptancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListEulaAcceptances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listeulaacceptancespaginator)
         """
 
 class ListEulasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListEulas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listeulaspaginator)
     """
 
     def paginate(
-        self, *, eulaIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, eulaIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEulasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListEulas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listeulaspaginator)
         """
 
 class ListLaunchProfileMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListLaunchProfileMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listlaunchprofilememberspaginator)
     """
 
     def paginate(
-        self, *, launchProfileId: str, studioId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        launchProfileId: str,
+        studioId: str,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLaunchProfileMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListLaunchProfileMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listlaunchprofilememberspaginator)
         """
 
 class ListLaunchProfilesPaginator(AioPaginator):
@@ -139,43 +137,43 @@
 
     def paginate(
         self,
         *,
         studioId: str,
         principalId: str = ...,
         states: Sequence[LaunchProfileStateType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLaunchProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListLaunchProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#listlaunchprofilespaginator)
         """
 
 class ListStreamingImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingimagespaginator)
     """
 
     def paginate(
-        self, *, studioId: str, owner: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, studioId: str, owner: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingimagespaginator)
         """
 
 class ListStreamingSessionBackupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingSessionBackups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingsessionbackupspaginator)
     """
 
     def paginate(
-        self, *, studioId: str, ownedBy: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, studioId: str, ownedBy: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingSessionBackupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingSessionBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingsessionbackupspaginator)
         """
 
 class ListStreamingSessionsPaginator(AioPaginator):
@@ -187,15 +185,15 @@
     def paginate(
         self,
         *,
         studioId: str,
         createdBy: str = ...,
         ownedBy: str = ...,
         sessionIds: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingSessionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStreamingSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststreamingsessionspaginator)
         """
 
 class ListStudioComponentsPaginator(AioPaginator):
@@ -206,41 +204,41 @@
 
     def paginate(
         self,
         *,
         studioId: str,
         states: Sequence[StudioComponentStateType] = ...,
         types: Sequence[StudioComponentTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStudioComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudioComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiocomponentspaginator)
         """
 
 class ListStudioMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudioMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiomemberspaginator)
     """
 
     def paginate(
-        self, *, studioId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, studioId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStudioMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudioMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiomemberspaginator)
         """
 
 class ListStudiosPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudios)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiospaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStudiosResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio.Paginator.ListStudios.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/paginators/#liststudiospaginator)
         """
```

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/type_defs.py` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -53,15 +53,14 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceptEulasRequestRequestTypeDef",
     "EulaAcceptanceTypeDef",
-    "ResponseMetadataTypeDef",
     "ActiveDirectoryComputerAttributeTypeDef",
     "ComputeFarmConfigurationTypeDef",
     "CreateStreamingImageRequestRequestTypeDef",
     "CreateStreamingSessionRequestRequestTypeDef",
     "CreateStreamingSessionStreamRequestRequestTypeDef",
     "StreamingSessionStreamTypeDef",
     "ScriptParameterKeyValueTypeDef",
@@ -91,28 +90,40 @@
     "GetStudioComponentRequestRequestTypeDef",
     "GetStudioMemberRequestRequestTypeDef",
     "StudioMembershipTypeDef",
     "GetStudioRequestRequestTypeDef",
     "LaunchProfileInitializationScriptTypeDef",
     "ValidationResultTypeDef",
     "LicenseServiceConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
     "ListEulaAcceptancesRequestRequestTypeDef",
+    "ListEulasRequestListEulasPaginateTypeDef",
     "ListEulasRequestRequestTypeDef",
+    "ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
     "ListLaunchProfileMembersRequestRequestTypeDef",
+    "ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
     "ListLaunchProfilesRequestRequestTypeDef",
+    "ListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
     "ListStreamingImagesRequestRequestTypeDef",
+    "ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
     "ListStreamingSessionBackupsRequestRequestTypeDef",
+    "ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
     "ListStreamingSessionsRequestRequestTypeDef",
+    "ListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
     "ListStudioComponentsRequestRequestTypeDef",
+    "ListStudioMembersRequestListStudioMembersPaginateTypeDef",
     "ListStudioMembersRequestRequestTypeDef",
+    "ListStudiosRequestListStudiosPaginateTypeDef",
     "ListStudiosRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NewLaunchProfileMemberTypeDef",
     "NewStudioMemberTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SharedFileSystemConfigurationTypeDef",
     "StartStreamingSessionRequestRequestTypeDef",
     "StartStudioSSOConfigurationRepairRequestRequestTypeDef",
     "StopStreamingSessionRequestRequestTypeDef",
     "StreamConfigurationSessionBackupTypeDef",
     "VolumeConfigurationTypeDef",
     "StreamingSessionStorageRootTypeDef",
@@ -120,15 +131,14 @@
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateLaunchProfileMemberRequestRequestTypeDef",
     "UpdateStreamingImageRequestRequestTypeDef",
     "UpdateStudioRequestRequestTypeDef",
     "AcceptEulasResponseTypeDef",
     "ListEulaAcceptancesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "ActiveDirectoryConfigurationTypeDef",
     "LaunchProfileInitializationActiveDirectoryTypeDef",
     "CreateStreamingSessionStreamResponseTypeDef",
     "GetStreamingSessionStreamResponseTypeDef",
     "CreateStudioRequestRequestTypeDef",
     "StudioTypeDef",
     "GetEulaResponseTypeDef",
@@ -148,24 +158,14 @@
     "GetStudioComponentRequestStudioComponentReadyWaitTypeDef",
     "GetStudioRequestStudioDeletedWaitTypeDef",
     "GetStudioRequestStudioReadyWaitTypeDef",
     "GetStreamingSessionBackupResponseTypeDef",
     "ListStreamingSessionBackupsResponseTypeDef",
     "GetStudioMemberResponseTypeDef",
     "ListStudioMembersResponseTypeDef",
-    "ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
-    "ListEulasRequestListEulasPaginateTypeDef",
-    "ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
-    "ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
-    "ListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
-    "ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
-    "ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
-    "ListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
-    "ListStudioMembersRequestListStudioMembersPaginateTypeDef",
-    "ListStudiosRequestListStudiosPaginateTypeDef",
     "PutLaunchProfileMembersRequestRequestTypeDef",
     "PutStudioMembersRequestRequestTypeDef",
     "StreamingSessionTypeDef",
     "StreamConfigurationSessionStorageTypeDef",
     "StreamingImageTypeDef",
     "StudioComponentConfigurationTypeDef",
     "LaunchProfileInitializationTypeDef",
@@ -238,25 +238,14 @@
         "accepteeId": str,
         "eulaAcceptanceId": str,
         "eulaId": str,
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
 ActiveDirectoryComputerAttributeTypeDef = TypedDict(
     "ActiveDirectoryComputerAttributeTypeDef",
     {
         "name": str,
         "value": str,
     },
     total=False,
@@ -765,24 +754,37 @@
     "LicenseServiceConfigurationTypeDef",
     {
         "endpoint": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
+    "_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "studioId": str,
+    },
+)
+_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
+    "_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
+    {
+        "eulaIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef(
+    _RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
+    _OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListEulaAcceptancesRequestRequestTypeDef = TypedDict(
     "_RequiredListEulaAcceptancesRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListEulaAcceptancesRequestRequestTypeDef = TypedDict(
@@ -798,23 +800,55 @@
 class ListEulaAcceptancesRequestRequestTypeDef(
     _RequiredListEulaAcceptancesRequestRequestTypeDef,
     _OptionalListEulaAcceptancesRequestRequestTypeDef,
 ):
     pass
 
 
+ListEulasRequestListEulasPaginateTypeDef = TypedDict(
+    "ListEulasRequestListEulasPaginateTypeDef",
+    {
+        "eulaIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEulasRequestRequestTypeDef = TypedDict(
     "ListEulasRequestRequestTypeDef",
     {
         "eulaIds": Sequence[str],
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
+    "_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
+    {
+        "launchProfileId": str,
+        "studioId": str,
+    },
+)
+_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
+    "_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef(
+    _RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
+    _OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListLaunchProfileMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListLaunchProfileMembersRequestRequestTypeDef",
     {
         "launchProfileId": str,
         "studioId": str,
     },
 )
@@ -831,14 +865,38 @@
 class ListLaunchProfileMembersRequestRequestTypeDef(
     _RequiredListLaunchProfileMembersRequestRequestTypeDef,
     _OptionalListLaunchProfileMembersRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
+    "_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
+    "_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
+    {
+        "principalId": str,
+        "states": Sequence[LaunchProfileStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef(
+    _RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
+    _OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListLaunchProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredListLaunchProfilesRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListLaunchProfilesRequestRequestTypeDef = TypedDict(
@@ -856,14 +914,37 @@
 class ListLaunchProfilesRequestRequestTypeDef(
     _RequiredListLaunchProfilesRequestRequestTypeDef,
     _OptionalListLaunchProfilesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
+    "_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
+    "_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
+    {
+        "owner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStreamingImagesRequestListStreamingImagesPaginateTypeDef(
+    _RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
+    _OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStreamingImagesRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamingImagesRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStreamingImagesRequestRequestTypeDef = TypedDict(
@@ -879,14 +960,37 @@
 class ListStreamingImagesRequestRequestTypeDef(
     _RequiredListStreamingImagesRequestRequestTypeDef,
     _OptionalListStreamingImagesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
+    "_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
+    "_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
+    {
+        "ownedBy": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef(
+    _RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
+    _OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStreamingSessionBackupsRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamingSessionBackupsRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStreamingSessionBackupsRequestRequestTypeDef = TypedDict(
@@ -902,14 +1006,39 @@
 class ListStreamingSessionBackupsRequestRequestTypeDef(
     _RequiredListStreamingSessionBackupsRequestRequestTypeDef,
     _OptionalListStreamingSessionBackupsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
+    "_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
+    "_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
+    {
+        "createdBy": str,
+        "ownedBy": str,
+        "sessionIds": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef(
+    _RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
+    _OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStreamingSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamingSessionsRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStreamingSessionsRequestRequestTypeDef = TypedDict(
@@ -927,14 +1056,38 @@
 class ListStreamingSessionsRequestRequestTypeDef(
     _RequiredListStreamingSessionsRequestRequestTypeDef,
     _OptionalListStreamingSessionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
+    "_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
+    "_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
+    {
+        "states": Sequence[StudioComponentStateType],
+        "types": Sequence[StudioComponentTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStudioComponentsRequestListStudioComponentsPaginateTypeDef(
+    _RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
+    _OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStudioComponentsRequestRequestTypeDef = TypedDict(
     "_RequiredListStudioComponentsRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStudioComponentsRequestRequestTypeDef = TypedDict(
@@ -952,14 +1105,36 @@
 class ListStudioComponentsRequestRequestTypeDef(
     _RequiredListStudioComponentsRequestRequestTypeDef,
     _OptionalListStudioComponentsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
+    "_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
+    "_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStudioMembersRequestListStudioMembersPaginateTypeDef(
+    _RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef,
+    _OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListStudioMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListStudioMembersRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStudioMembersRequestRequestTypeDef = TypedDict(
@@ -974,14 +1149,22 @@
 
 class ListStudioMembersRequestRequestTypeDef(
     _RequiredListStudioMembersRequestRequestTypeDef, _OptionalListStudioMembersRequestRequestTypeDef
 ):
     pass
 
 
+ListStudiosRequestListStudiosPaginateTypeDef = TypedDict(
+    "ListStudiosRequestListStudiosPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStudiosRequestRequestTypeDef = TypedDict(
     "ListStudiosRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
@@ -989,14 +1172,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NewLaunchProfileMemberTypeDef = TypedDict(
     "NewLaunchProfileMemberTypeDef",
     {
         "persona": Literal["USER"],
         "principalId": str,
     },
 )
@@ -1005,14 +1196,35 @@
     "NewStudioMemberTypeDef",
     {
         "persona": Literal["ADMINISTRATOR"],
         "principalId": str,
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
 SharedFileSystemConfigurationTypeDef = TypedDict(
     "SharedFileSystemConfigurationTypeDef",
     {
         "endpoint": str,
         "fileSystemId": str,
         "linuxMountPoint": str,
         "shareName": str,
@@ -1244,32 +1456,24 @@
     pass
 
 
 AcceptEulasResponseTypeDef = TypedDict(
     "AcceptEulasResponseTypeDef",
     {
         "eulaAcceptances": List[EulaAcceptanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEulaAcceptancesResponseTypeDef = TypedDict(
     "ListEulaAcceptancesResponseTypeDef",
     {
         "eulaAcceptances": List[EulaAcceptanceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActiveDirectoryConfigurationTypeDef = TypedDict(
     "ActiveDirectoryConfigurationTypeDef",
     {
         "computerAttributes": Sequence[ActiveDirectoryComputerAttributeTypeDef],
@@ -1293,23 +1497,23 @@
     total=False,
 )
 
 CreateStreamingSessionStreamResponseTypeDef = TypedDict(
     "CreateStreamingSessionStreamResponseTypeDef",
     {
         "stream": StreamingSessionStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingSessionStreamResponseTypeDef = TypedDict(
     "GetStreamingSessionStreamResponseTypeDef",
     {
         "stream": StreamingSessionStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStudioRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStudioRequestRequestTypeDef",
     {
         "adminRoleArn": str,
@@ -1358,49 +1562,49 @@
     total=False,
 )
 
 GetEulaResponseTypeDef = TypedDict(
     "GetEulaResponseTypeDef",
     {
         "eula": EulaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEulasResponseTypeDef = TypedDict(
     "ListEulasResponseTypeDef",
     {
         "eulas": List[EulaTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLaunchProfileMemberResponseTypeDef = TypedDict(
     "GetLaunchProfileMemberResponseTypeDef",
     {
         "member": LaunchProfileMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLaunchProfileMembersResponseTypeDef = TypedDict(
     "ListLaunchProfileMembersResponseTypeDef",
     {
         "members": List[LaunchProfileMembershipTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLaunchProfileMemberResponseTypeDef = TypedDict(
     "UpdateLaunchProfileMemberResponseTypeDef",
     {
         "member": LaunchProfileMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetLaunchProfileRequestLaunchProfileDeletedWaitTypeDef = TypedDict(
     "_RequiredGetLaunchProfileRequestLaunchProfileDeletedWaitTypeDef",
     {
         "launchProfileId": str,
@@ -1674,246 +1878,42 @@
     pass
 
 
 GetStreamingSessionBackupResponseTypeDef = TypedDict(
     "GetStreamingSessionBackupResponseTypeDef",
     {
         "streamingSessionBackup": StreamingSessionBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamingSessionBackupsResponseTypeDef = TypedDict(
     "ListStreamingSessionBackupsResponseTypeDef",
     {
         "nextToken": str,
         "streamingSessionBackups": List[StreamingSessionBackupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStudioMemberResponseTypeDef = TypedDict(
     "GetStudioMemberResponseTypeDef",
     {
         "member": StudioMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStudioMembersResponseTypeDef = TypedDict(
     "ListStudioMembersResponseTypeDef",
     {
         "members": List[StudioMembershipTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
-    "_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
-    "_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
-    {
-        "eulaIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef(
-    _RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
-    _OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
-):
-    pass
-
-
-ListEulasRequestListEulasPaginateTypeDef = TypedDict(
-    "ListEulasRequestListEulasPaginateTypeDef",
-    {
-        "eulaIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
-    "_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
-    {
-        "launchProfileId": str,
-        "studioId": str,
-    },
-)
-_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
-    "_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef(
-    _RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
-    _OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
-    "_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
-    "_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
-    {
-        "principalId": str,
-        "states": Sequence[LaunchProfileStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef(
-    _RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
-    _OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
-    "_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
-    "_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
-    {
-        "owner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStreamingImagesRequestListStreamingImagesPaginateTypeDef(
-    _RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
-    _OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
-    "_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
-    "_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
-    {
-        "ownedBy": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-
-class ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef(
-    _RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
-    _OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
-    "_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
-    "_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
-    {
-        "createdBy": str,
-        "ownedBy": str,
-        "sessionIds": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef(
-    _RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
-    _OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
-    "_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
-    "_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
-    {
-        "states": Sequence[StudioComponentStateType],
-        "types": Sequence[StudioComponentTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStudioComponentsRequestListStudioComponentsPaginateTypeDef(
-    _RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
-    _OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
-    "_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
-    "_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListStudioMembersRequestListStudioMembersPaginateTypeDef(
-    _RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef,
-    _OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef,
-):
-    pass
-
-
-ListStudiosRequestListStudiosPaginateTypeDef = TypedDict(
-    "ListStudiosRequestListStudiosPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 _RequiredPutLaunchProfileMembersRequestRequestTypeDef = TypedDict(
     "_RequiredPutLaunchProfileMembersRequestRequestTypeDef",
     {
         "identityStoreId": str,
         "launchProfileId": str,
@@ -2063,105 +2063,105 @@
     total=False,
 )
 
 CreateStudioResponseTypeDef = TypedDict(
     "CreateStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStudioResponseTypeDef = TypedDict(
     "DeleteStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStudioResponseTypeDef = TypedDict(
     "GetStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStudiosResponseTypeDef = TypedDict(
     "ListStudiosResponseTypeDef",
     {
         "nextToken": str,
         "studios": List[StudioTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartStudioSSOConfigurationRepairResponseTypeDef = TypedDict(
     "StartStudioSSOConfigurationRepairResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStudioResponseTypeDef = TypedDict(
     "UpdateStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingSessionResponseTypeDef = TypedDict(
     "CreateStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStreamingSessionResponseTypeDef = TypedDict(
     "DeleteStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingSessionResponseTypeDef = TypedDict(
     "GetStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamingSessionsResponseTypeDef = TypedDict(
     "ListStreamingSessionsResponseTypeDef",
     {
         "nextToken": str,
         "sessions": List[StreamingSessionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartStreamingSessionResponseTypeDef = TypedDict(
     "StartStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopStreamingSessionResponseTypeDef = TypedDict(
     "StopStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStreamConfigurationCreateTypeDef = TypedDict(
     "_RequiredStreamConfigurationCreateTypeDef",
     {
         "clipboardMode": StreamingClipboardModeType,
@@ -2219,48 +2219,48 @@
     pass
 
 
 CreateStreamingImageResponseTypeDef = TypedDict(
     "CreateStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStreamingImageResponseTypeDef = TypedDict(
     "DeleteStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingImageResponseTypeDef = TypedDict(
     "GetStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamingImagesResponseTypeDef = TypedDict(
     "ListStreamingImagesResponseTypeDef",
     {
         "nextToken": str,
         "streamingImages": List[StreamingImageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStreamingImageResponseTypeDef = TypedDict(
     "UpdateStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStudioComponentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStudioComponentRequestRequestTypeDef",
     {
         "name": str,
@@ -2353,15 +2353,15 @@
     pass
 
 
 GetLaunchProfileInitializationResponseTypeDef = TypedDict(
     "GetLaunchProfileInitializationResponseTypeDef",
     {
         "launchProfileInitialization": LaunchProfileInitializationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLaunchProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLaunchProfileRequestRequestTypeDef",
     {
         "ec2SubnetIds": Sequence[str],
@@ -2442,94 +2442,94 @@
     total=False,
 )
 
 CreateStudioComponentResponseTypeDef = TypedDict(
     "CreateStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStudioComponentResponseTypeDef = TypedDict(
     "DeleteStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStudioComponentResponseTypeDef = TypedDict(
     "GetStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStudioComponentsResponseTypeDef = TypedDict(
     "ListStudioComponentsResponseTypeDef",
     {
         "nextToken": str,
         "studioComponents": List[StudioComponentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStudioComponentResponseTypeDef = TypedDict(
     "UpdateStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLaunchProfileResponseTypeDef = TypedDict(
     "CreateLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLaunchProfileResponseTypeDef = TypedDict(
     "DeleteLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLaunchProfileDetailsResponseTypeDef = TypedDict(
     "GetLaunchProfileDetailsResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
         "streamingImages": List[StreamingImageTypeDef],
         "studioComponentSummaries": List[StudioComponentSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLaunchProfileResponseTypeDef = TypedDict(
     "GetLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLaunchProfilesResponseTypeDef = TypedDict(
     "ListLaunchProfilesResponseTypeDef",
     {
         "launchProfiles": List[LaunchProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLaunchProfileResponseTypeDef = TypedDict(
     "UpdateLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/type_defs.pyi` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -52,15 +52,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceptEulasRequestRequestTypeDef",
     "EulaAcceptanceTypeDef",
-    "ResponseMetadataTypeDef",
     "ActiveDirectoryComputerAttributeTypeDef",
     "ComputeFarmConfigurationTypeDef",
     "CreateStreamingImageRequestRequestTypeDef",
     "CreateStreamingSessionRequestRequestTypeDef",
     "CreateStreamingSessionStreamRequestRequestTypeDef",
     "StreamingSessionStreamTypeDef",
     "ScriptParameterKeyValueTypeDef",
@@ -90,28 +89,40 @@
     "GetStudioComponentRequestRequestTypeDef",
     "GetStudioMemberRequestRequestTypeDef",
     "StudioMembershipTypeDef",
     "GetStudioRequestRequestTypeDef",
     "LaunchProfileInitializationScriptTypeDef",
     "ValidationResultTypeDef",
     "LicenseServiceConfigurationTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
     "ListEulaAcceptancesRequestRequestTypeDef",
+    "ListEulasRequestListEulasPaginateTypeDef",
     "ListEulasRequestRequestTypeDef",
+    "ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
     "ListLaunchProfileMembersRequestRequestTypeDef",
+    "ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
     "ListLaunchProfilesRequestRequestTypeDef",
+    "ListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
     "ListStreamingImagesRequestRequestTypeDef",
+    "ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
     "ListStreamingSessionBackupsRequestRequestTypeDef",
+    "ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
     "ListStreamingSessionsRequestRequestTypeDef",
+    "ListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
     "ListStudioComponentsRequestRequestTypeDef",
+    "ListStudioMembersRequestListStudioMembersPaginateTypeDef",
     "ListStudioMembersRequestRequestTypeDef",
+    "ListStudiosRequestListStudiosPaginateTypeDef",
     "ListStudiosRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NewLaunchProfileMemberTypeDef",
     "NewStudioMemberTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SharedFileSystemConfigurationTypeDef",
     "StartStreamingSessionRequestRequestTypeDef",
     "StartStudioSSOConfigurationRepairRequestRequestTypeDef",
     "StopStreamingSessionRequestRequestTypeDef",
     "StreamConfigurationSessionBackupTypeDef",
     "VolumeConfigurationTypeDef",
     "StreamingSessionStorageRootTypeDef",
@@ -119,15 +130,14 @@
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateLaunchProfileMemberRequestRequestTypeDef",
     "UpdateStreamingImageRequestRequestTypeDef",
     "UpdateStudioRequestRequestTypeDef",
     "AcceptEulasResponseTypeDef",
     "ListEulaAcceptancesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "ActiveDirectoryConfigurationTypeDef",
     "LaunchProfileInitializationActiveDirectoryTypeDef",
     "CreateStreamingSessionStreamResponseTypeDef",
     "GetStreamingSessionStreamResponseTypeDef",
     "CreateStudioRequestRequestTypeDef",
     "StudioTypeDef",
     "GetEulaResponseTypeDef",
@@ -147,24 +157,14 @@
     "GetStudioComponentRequestStudioComponentReadyWaitTypeDef",
     "GetStudioRequestStudioDeletedWaitTypeDef",
     "GetStudioRequestStudioReadyWaitTypeDef",
     "GetStreamingSessionBackupResponseTypeDef",
     "ListStreamingSessionBackupsResponseTypeDef",
     "GetStudioMemberResponseTypeDef",
     "ListStudioMembersResponseTypeDef",
-    "ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
-    "ListEulasRequestListEulasPaginateTypeDef",
-    "ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
-    "ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
-    "ListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
-    "ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
-    "ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
-    "ListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
-    "ListStudioMembersRequestListStudioMembersPaginateTypeDef",
-    "ListStudiosRequestListStudiosPaginateTypeDef",
     "PutLaunchProfileMembersRequestRequestTypeDef",
     "PutStudioMembersRequestRequestTypeDef",
     "StreamingSessionTypeDef",
     "StreamConfigurationSessionStorageTypeDef",
     "StreamingImageTypeDef",
     "StudioComponentConfigurationTypeDef",
     "LaunchProfileInitializationTypeDef",
@@ -235,25 +235,14 @@
         "accepteeId": str,
         "eulaAcceptanceId": str,
         "eulaId": str,
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
 ActiveDirectoryComputerAttributeTypeDef = TypedDict(
     "ActiveDirectoryComputerAttributeTypeDef",
     {
         "name": str,
         "value": str,
     },
     total=False,
@@ -740,24 +729,35 @@
     "LicenseServiceConfigurationTypeDef",
     {
         "endpoint": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
+    "_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "studioId": str,
+    },
+)
+_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
+    "_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
+    {
+        "eulaIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef(
+    _RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
+    _OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
+):
+    pass
+
 _RequiredListEulaAcceptancesRequestRequestTypeDef = TypedDict(
     "_RequiredListEulaAcceptancesRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListEulaAcceptancesRequestRequestTypeDef = TypedDict(
@@ -771,23 +771,53 @@
 
 class ListEulaAcceptancesRequestRequestTypeDef(
     _RequiredListEulaAcceptancesRequestRequestTypeDef,
     _OptionalListEulaAcceptancesRequestRequestTypeDef,
 ):
     pass
 
+ListEulasRequestListEulasPaginateTypeDef = TypedDict(
+    "ListEulasRequestListEulasPaginateTypeDef",
+    {
+        "eulaIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEulasRequestRequestTypeDef = TypedDict(
     "ListEulasRequestRequestTypeDef",
     {
         "eulaIds": Sequence[str],
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
+    "_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
+    {
+        "launchProfileId": str,
+        "studioId": str,
+    },
+)
+_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
+    "_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef(
+    _RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
+    _OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
+):
+    pass
+
 _RequiredListLaunchProfileMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListLaunchProfileMembersRequestRequestTypeDef",
     {
         "launchProfileId": str,
         "studioId": str,
     },
 )
@@ -802,14 +832,36 @@
 
 class ListLaunchProfileMembersRequestRequestTypeDef(
     _RequiredListLaunchProfileMembersRequestRequestTypeDef,
     _OptionalListLaunchProfileMembersRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
+    "_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
+    "_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
+    {
+        "principalId": str,
+        "states": Sequence[LaunchProfileStateType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef(
+    _RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
+    _OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
+):
+    pass
+
 _RequiredListLaunchProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredListLaunchProfilesRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListLaunchProfilesRequestRequestTypeDef = TypedDict(
@@ -825,14 +877,35 @@
 
 class ListLaunchProfilesRequestRequestTypeDef(
     _RequiredListLaunchProfilesRequestRequestTypeDef,
     _OptionalListLaunchProfilesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
+    "_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
+    "_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
+    {
+        "owner": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStreamingImagesRequestListStreamingImagesPaginateTypeDef(
+    _RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
+    _OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
+):
+    pass
+
 _RequiredListStreamingImagesRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamingImagesRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStreamingImagesRequestRequestTypeDef = TypedDict(
@@ -846,14 +919,35 @@
 
 class ListStreamingImagesRequestRequestTypeDef(
     _RequiredListStreamingImagesRequestRequestTypeDef,
     _OptionalListStreamingImagesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
+    "_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
+    "_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
+    {
+        "ownedBy": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef(
+    _RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
+    _OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListStreamingSessionBackupsRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamingSessionBackupsRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStreamingSessionBackupsRequestRequestTypeDef = TypedDict(
@@ -867,14 +961,37 @@
 
 class ListStreamingSessionBackupsRequestRequestTypeDef(
     _RequiredListStreamingSessionBackupsRequestRequestTypeDef,
     _OptionalListStreamingSessionBackupsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
+    "_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
+    "_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
+    {
+        "createdBy": str,
+        "ownedBy": str,
+        "sessionIds": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef(
+    _RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
+    _OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListStreamingSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListStreamingSessionsRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStreamingSessionsRequestRequestTypeDef = TypedDict(
@@ -890,14 +1007,36 @@
 
 class ListStreamingSessionsRequestRequestTypeDef(
     _RequiredListStreamingSessionsRequestRequestTypeDef,
     _OptionalListStreamingSessionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
+    "_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
+    "_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
+    {
+        "states": Sequence[StudioComponentStateType],
+        "types": Sequence[StudioComponentTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStudioComponentsRequestListStudioComponentsPaginateTypeDef(
+    _RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
+    _OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListStudioComponentsRequestRequestTypeDef = TypedDict(
     "_RequiredListStudioComponentsRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStudioComponentsRequestRequestTypeDef = TypedDict(
@@ -913,14 +1052,34 @@
 
 class ListStudioComponentsRequestRequestTypeDef(
     _RequiredListStudioComponentsRequestRequestTypeDef,
     _OptionalListStudioComponentsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
+    "_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef",
+    {
+        "studioId": str,
+    },
+)
+_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
+    "_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStudioMembersRequestListStudioMembersPaginateTypeDef(
+    _RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef,
+    _OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef,
+):
+    pass
+
 _RequiredListStudioMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListStudioMembersRequestRequestTypeDef",
     {
         "studioId": str,
     },
 )
 _OptionalListStudioMembersRequestRequestTypeDef = TypedDict(
@@ -933,14 +1092,22 @@
 )
 
 class ListStudioMembersRequestRequestTypeDef(
     _RequiredListStudioMembersRequestRequestTypeDef, _OptionalListStudioMembersRequestRequestTypeDef
 ):
     pass
 
+ListStudiosRequestListStudiosPaginateTypeDef = TypedDict(
+    "ListStudiosRequestListStudiosPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStudiosRequestRequestTypeDef = TypedDict(
     "ListStudiosRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
@@ -948,14 +1115,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NewLaunchProfileMemberTypeDef = TypedDict(
     "NewLaunchProfileMemberTypeDef",
     {
         "persona": Literal["USER"],
         "principalId": str,
     },
 )
@@ -964,14 +1139,35 @@
     "NewStudioMemberTypeDef",
     {
         "persona": Literal["ADMINISTRATOR"],
         "principalId": str,
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
 SharedFileSystemConfigurationTypeDef = TypedDict(
     "SharedFileSystemConfigurationTypeDef",
     {
         "endpoint": str,
         "fileSystemId": str,
         "linuxMountPoint": str,
         "shareName": str,
@@ -1187,32 +1383,24 @@
 ):
     pass
 
 AcceptEulasResponseTypeDef = TypedDict(
     "AcceptEulasResponseTypeDef",
     {
         "eulaAcceptances": List[EulaAcceptanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEulaAcceptancesResponseTypeDef = TypedDict(
     "ListEulaAcceptancesResponseTypeDef",
     {
         "eulaAcceptances": List[EulaAcceptanceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActiveDirectoryConfigurationTypeDef = TypedDict(
     "ActiveDirectoryConfigurationTypeDef",
     {
         "computerAttributes": Sequence[ActiveDirectoryComputerAttributeTypeDef],
@@ -1236,23 +1424,23 @@
     total=False,
 )
 
 CreateStreamingSessionStreamResponseTypeDef = TypedDict(
     "CreateStreamingSessionStreamResponseTypeDef",
     {
         "stream": StreamingSessionStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingSessionStreamResponseTypeDef = TypedDict(
     "GetStreamingSessionStreamResponseTypeDef",
     {
         "stream": StreamingSessionStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStudioRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStudioRequestRequestTypeDef",
     {
         "adminRoleArn": str,
@@ -1299,49 +1487,49 @@
     total=False,
 )
 
 GetEulaResponseTypeDef = TypedDict(
     "GetEulaResponseTypeDef",
     {
         "eula": EulaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEulasResponseTypeDef = TypedDict(
     "ListEulasResponseTypeDef",
     {
         "eulas": List[EulaTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLaunchProfileMemberResponseTypeDef = TypedDict(
     "GetLaunchProfileMemberResponseTypeDef",
     {
         "member": LaunchProfileMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLaunchProfileMembersResponseTypeDef = TypedDict(
     "ListLaunchProfileMembersResponseTypeDef",
     {
         "members": List[LaunchProfileMembershipTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLaunchProfileMemberResponseTypeDef = TypedDict(
     "UpdateLaunchProfileMemberResponseTypeDef",
     {
         "member": LaunchProfileMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetLaunchProfileRequestLaunchProfileDeletedWaitTypeDef = TypedDict(
     "_RequiredGetLaunchProfileRequestLaunchProfileDeletedWaitTypeDef",
     {
         "launchProfileId": str,
@@ -1591,230 +1779,42 @@
 ):
     pass
 
 GetStreamingSessionBackupResponseTypeDef = TypedDict(
     "GetStreamingSessionBackupResponseTypeDef",
     {
         "streamingSessionBackup": StreamingSessionBackupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamingSessionBackupsResponseTypeDef = TypedDict(
     "ListStreamingSessionBackupsResponseTypeDef",
     {
         "nextToken": str,
         "streamingSessionBackups": List[StreamingSessionBackupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStudioMemberResponseTypeDef = TypedDict(
     "GetStudioMemberResponseTypeDef",
     {
         "member": StudioMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStudioMembersResponseTypeDef = TypedDict(
     "ListStudioMembersResponseTypeDef",
     {
         "members": List[StudioMembershipTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
-    "_RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef = TypedDict(
-    "_OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef",
-    {
-        "eulaIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef(
-    _RequiredListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
-    _OptionalListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
-):
-    pass
-
-ListEulasRequestListEulasPaginateTypeDef = TypedDict(
-    "ListEulasRequestListEulasPaginateTypeDef",
-    {
-        "eulaIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
-    "_RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
-    {
-        "launchProfileId": str,
-        "studioId": str,
-    },
-)
-_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef = TypedDict(
-    "_OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef(
-    _RequiredListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
-    _OptionalListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
-):
-    pass
-
-_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
-    "_RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef = TypedDict(
-    "_OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef",
-    {
-        "principalId": str,
-        "states": Sequence[LaunchProfileStateType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef(
-    _RequiredListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
-    _OptionalListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
-):
-    pass
-
-_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
-    "_RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef = TypedDict(
-    "_OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef",
-    {
-        "owner": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStreamingImagesRequestListStreamingImagesPaginateTypeDef(
-    _RequiredListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
-    _OptionalListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
-):
-    pass
-
-_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
-    "_RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef = TypedDict(
-    "_OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef",
-    {
-        "ownedBy": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-class ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef(
-    _RequiredListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
-    _OptionalListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
-    "_RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef = TypedDict(
-    "_OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef",
-    {
-        "createdBy": str,
-        "ownedBy": str,
-        "sessionIds": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef(
-    _RequiredListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
-    _OptionalListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
-    "_RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef = TypedDict(
-    "_OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef",
-    {
-        "states": Sequence[StudioComponentStateType],
-        "types": Sequence[StudioComponentTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStudioComponentsRequestListStudioComponentsPaginateTypeDef(
-    _RequiredListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
-    _OptionalListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
-):
-    pass
-
-_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
-    "_RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef",
-    {
-        "studioId": str,
-    },
-)
-_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef = TypedDict(
-    "_OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListStudioMembersRequestListStudioMembersPaginateTypeDef(
-    _RequiredListStudioMembersRequestListStudioMembersPaginateTypeDef,
-    _OptionalListStudioMembersRequestListStudioMembersPaginateTypeDef,
-):
-    pass
-
-ListStudiosRequestListStudiosPaginateTypeDef = TypedDict(
-    "ListStudiosRequestListStudiosPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 _RequiredPutLaunchProfileMembersRequestRequestTypeDef = TypedDict(
     "_RequiredPutLaunchProfileMembersRequestRequestTypeDef",
     {
         "identityStoreId": str,
         "launchProfileId": str,
@@ -1958,105 +1958,105 @@
     total=False,
 )
 
 CreateStudioResponseTypeDef = TypedDict(
     "CreateStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStudioResponseTypeDef = TypedDict(
     "DeleteStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStudioResponseTypeDef = TypedDict(
     "GetStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStudiosResponseTypeDef = TypedDict(
     "ListStudiosResponseTypeDef",
     {
         "nextToken": str,
         "studios": List[StudioTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartStudioSSOConfigurationRepairResponseTypeDef = TypedDict(
     "StartStudioSSOConfigurationRepairResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStudioResponseTypeDef = TypedDict(
     "UpdateStudioResponseTypeDef",
     {
         "studio": StudioTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingSessionResponseTypeDef = TypedDict(
     "CreateStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStreamingSessionResponseTypeDef = TypedDict(
     "DeleteStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingSessionResponseTypeDef = TypedDict(
     "GetStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamingSessionsResponseTypeDef = TypedDict(
     "ListStreamingSessionsResponseTypeDef",
     {
         "nextToken": str,
         "sessions": List[StreamingSessionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartStreamingSessionResponseTypeDef = TypedDict(
     "StartStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopStreamingSessionResponseTypeDef = TypedDict(
     "StopStreamingSessionResponseTypeDef",
     {
         "session": StreamingSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStreamConfigurationCreateTypeDef = TypedDict(
     "_RequiredStreamConfigurationCreateTypeDef",
     {
         "clipboardMode": StreamingClipboardModeType,
@@ -2110,48 +2110,48 @@
 ):
     pass
 
 CreateStreamingImageResponseTypeDef = TypedDict(
     "CreateStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStreamingImageResponseTypeDef = TypedDict(
     "DeleteStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingImageResponseTypeDef = TypedDict(
     "GetStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStreamingImagesResponseTypeDef = TypedDict(
     "ListStreamingImagesResponseTypeDef",
     {
         "nextToken": str,
         "streamingImages": List[StreamingImageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStreamingImageResponseTypeDef = TypedDict(
     "UpdateStreamingImageResponseTypeDef",
     {
         "streamingImage": StreamingImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateStudioComponentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateStudioComponentRequestRequestTypeDef",
     {
         "name": str,
@@ -2240,15 +2240,15 @@
 ):
     pass
 
 GetLaunchProfileInitializationResponseTypeDef = TypedDict(
     "GetLaunchProfileInitializationResponseTypeDef",
     {
         "launchProfileInitialization": LaunchProfileInitializationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLaunchProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLaunchProfileRequestRequestTypeDef",
     {
         "ec2SubnetIds": Sequence[str],
@@ -2325,94 +2325,94 @@
     total=False,
 )
 
 CreateStudioComponentResponseTypeDef = TypedDict(
     "CreateStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteStudioComponentResponseTypeDef = TypedDict(
     "DeleteStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStudioComponentResponseTypeDef = TypedDict(
     "GetStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStudioComponentsResponseTypeDef = TypedDict(
     "ListStudioComponentsResponseTypeDef",
     {
         "nextToken": str,
         "studioComponents": List[StudioComponentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStudioComponentResponseTypeDef = TypedDict(
     "UpdateStudioComponentResponseTypeDef",
     {
         "studioComponent": StudioComponentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLaunchProfileResponseTypeDef = TypedDict(
     "CreateLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLaunchProfileResponseTypeDef = TypedDict(
     "DeleteLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLaunchProfileDetailsResponseTypeDef = TypedDict(
     "GetLaunchProfileDetailsResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
         "streamingImages": List[StreamingImageTypeDef],
         "studioComponentSummaries": List[StudioComponentSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLaunchProfileResponseTypeDef = TypedDict(
     "GetLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLaunchProfilesResponseTypeDef = TypedDict(
     "ListLaunchProfilesResponseTypeDef",
     {
         "launchProfiles": List[LaunchProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLaunchProfileResponseTypeDef = TypedDict(
     "UpdateLaunchProfileResponseTypeDef",
     {
         "launchProfile": LaunchProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/waiter.py` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble/waiter.pyi` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/PKG-INFO` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-nimble
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.NimbleStudio 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.NimbleStudio 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-nimble"></a>
 
 # types-aiobotocore-nimble
 
 [![PyPI - types-aiobotocore-nimble](https://img.shields.io/pypi/v/types-aiobotocore-nimble.svg?color=blue)](https://pypi.org/project/types-aiobotocore-nimble)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-nimble.svg?color=blue)](https://pypi.org/project/types-aiobotocore-nimble)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-nimble?color=blue)](https://pypistats.org/packages/types-aiobotocore-nimble)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.NimbleStudio 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio)
+[aiobotocore.NimbleStudio 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/nimble.html#NimbleStudio)
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
 [types-aiobotocore-nimble docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_nimble/).
 
 See how it helps to find and fix potential bugs:
 
@@ -471,15 +471,14 @@
 `types_aiobotocore_nimble.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_nimble.type_defs import (
     AcceptEulasRequestRequestTypeDef,
     EulaAcceptanceTypeDef,
-    ResponseMetadataTypeDef,
     ActiveDirectoryComputerAttributeTypeDef,
     ComputeFarmConfigurationTypeDef,
     CreateStreamingImageRequestRequestTypeDef,
     CreateStreamingSessionRequestRequestTypeDef,
     CreateStreamingSessionStreamRequestRequestTypeDef,
     StreamingSessionStreamTypeDef,
     ScriptParameterKeyValueTypeDef,
@@ -509,28 +508,40 @@
     GetStudioComponentRequestRequestTypeDef,
     GetStudioMemberRequestRequestTypeDef,
     StudioMembershipTypeDef,
     GetStudioRequestRequestTypeDef,
     LaunchProfileInitializationScriptTypeDef,
     ValidationResultTypeDef,
     LicenseServiceConfigurationTypeDef,
-    PaginatorConfigTypeDef,
+    ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
     ListEulaAcceptancesRequestRequestTypeDef,
+    ListEulasRequestListEulasPaginateTypeDef,
     ListEulasRequestRequestTypeDef,
+    ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
     ListLaunchProfileMembersRequestRequestTypeDef,
+    ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
     ListLaunchProfilesRequestRequestTypeDef,
+    ListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
     ListStreamingImagesRequestRequestTypeDef,
+    ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
     ListStreamingSessionBackupsRequestRequestTypeDef,
+    ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
     ListStreamingSessionsRequestRequestTypeDef,
+    ListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
     ListStudioComponentsRequestRequestTypeDef,
+    ListStudioMembersRequestListStudioMembersPaginateTypeDef,
     ListStudioMembersRequestRequestTypeDef,
+    ListStudiosRequestListStudiosPaginateTypeDef,
     ListStudiosRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NewLaunchProfileMemberTypeDef,
     NewStudioMemberTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SharedFileSystemConfigurationTypeDef,
     StartStreamingSessionRequestRequestTypeDef,
     StartStudioSSOConfigurationRepairRequestRequestTypeDef,
     StopStreamingSessionRequestRequestTypeDef,
     StreamConfigurationSessionBackupTypeDef,
     VolumeConfigurationTypeDef,
     StreamingSessionStorageRootTypeDef,
@@ -538,15 +549,14 @@
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateLaunchProfileMemberRequestRequestTypeDef,
     UpdateStreamingImageRequestRequestTypeDef,
     UpdateStudioRequestRequestTypeDef,
     AcceptEulasResponseTypeDef,
     ListEulaAcceptancesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     ActiveDirectoryConfigurationTypeDef,
     LaunchProfileInitializationActiveDirectoryTypeDef,
     CreateStreamingSessionStreamResponseTypeDef,
     GetStreamingSessionStreamResponseTypeDef,
     CreateStudioRequestRequestTypeDef,
     StudioTypeDef,
     GetEulaResponseTypeDef,
@@ -566,24 +576,14 @@
     GetStudioComponentRequestStudioComponentReadyWaitTypeDef,
     GetStudioRequestStudioDeletedWaitTypeDef,
     GetStudioRequestStudioReadyWaitTypeDef,
     GetStreamingSessionBackupResponseTypeDef,
     ListStreamingSessionBackupsResponseTypeDef,
     GetStudioMemberResponseTypeDef,
     ListStudioMembersResponseTypeDef,
-    ListEulaAcceptancesRequestListEulaAcceptancesPaginateTypeDef,
-    ListEulasRequestListEulasPaginateTypeDef,
-    ListLaunchProfileMembersRequestListLaunchProfileMembersPaginateTypeDef,
-    ListLaunchProfilesRequestListLaunchProfilesPaginateTypeDef,
-    ListStreamingImagesRequestListStreamingImagesPaginateTypeDef,
-    ListStreamingSessionBackupsRequestListStreamingSessionBackupsPaginateTypeDef,
-    ListStreamingSessionsRequestListStreamingSessionsPaginateTypeDef,
-    ListStudioComponentsRequestListStudioComponentsPaginateTypeDef,
-    ListStudioMembersRequestListStudioMembersPaginateTypeDef,
-    ListStudiosRequestListStudiosPaginateTypeDef,
     PutLaunchProfileMembersRequestRequestTypeDef,
     PutStudioMembersRequestRequestTypeDef,
     StreamingSessionTypeDef,
     StreamConfigurationSessionStorageTypeDef,
     StreamingImageTypeDef,
     StudioComponentConfigurationTypeDef,
     LaunchProfileInitializationTypeDef,
@@ -634,43 +634,43 @@
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

### Comparing `types-aiobotocore-nimble-2.5.0.post1/types_aiobotocore_nimble.egg-info/SOURCES.txt` & `types-aiobotocore-nimble-2.5.1/types_aiobotocore_nimble.egg-info/SOURCES.txt`

 * *Files identical despite different names*

