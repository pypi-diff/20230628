# Comparing `tmp/types-aiobotocore-chime-sdk-identity-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-chime-sdk-identity-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-chime-sdk-identity-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:17 2023, max compression
+gzip compressed data, was "types-aiobotocore-chime-sdk-identity-2.5.1.tar", last modified: Wed Jun 28 01:43:11 2023, max compression
```

## Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1.tar` & `types-aiobotocore-chime-sdk-identity-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.510998 types-aiobotocore-chime-sdk-identity-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15134 2023-03-11 12:26:17.510998 types-aiobotocore-chime-sdk-identity-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13521 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:17.510998 types-aiobotocore-chime-sdk-identity-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2215 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.510998 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/
--rw-r--r--   0 runner    (1001) docker     (123)      520 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      519 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20411 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20379 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7807 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7805 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    18920 2023-03-11 12:10:27.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    18901 2023-03-11 12:10:26.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:25.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.510998 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15134 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      921 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-03-11 12:26:17.000000 types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.074103 types-aiobotocore-chime-sdk-identity-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15928 2023-06-28 01:43:11.066103 types-aiobotocore-chime-sdk-identity-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14321 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:11.074103 types-aiobotocore-chime-sdk-identity-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-06-28 01:27:01.000000 types-aiobotocore-chime-sdk-identity-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.066103 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/
+-rw-r--r--   0 runner    (1001) docker     (123)      520 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24651 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24613 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8338 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8336 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    25396 2023-06-28 01:27:03.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25367 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:02.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.066103 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15928 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      921 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 01:43:10.000000 types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/LICENSE` & `types-aiobotocore-chime-sdk-identity-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/PKG-INFO` & `types-aiobotocore-chime-sdk-identity-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-chime-sdk-identity
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ChimeSDKIdentity 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ChimeSDKIdentity 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-chime-sdk-identity"></a>
 
 # types-aiobotocore-chime-sdk-identity
 
 [![PyPI - types-aiobotocore-chime-sdk-identity](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-identity)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-identity)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-identity?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-identity)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKIdentity 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity)
+[aiobotocore.ChimeSDKIdentity 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity)
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
 [types-aiobotocore-chime-sdk-identity docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,14 +273,18 @@
 
 ```python
 from types_aiobotocore_chime_sdk_identity.literals import (
     AllowMessagesType,
     AppInstanceUserEndpointTypeType,
     EndpointStatusReasonType,
     EndpointStatusType,
+    ExpirationCriterionType,
+    RespondsToType,
+    StandardMessagesType,
+    TargetedMessagesType,
     ChimeSDKIdentityServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
@@ -294,114 +298,131 @@
 
 `types_aiobotocore_chime_sdk_identity.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_chime_sdk_identity.type_defs import (
     IdentityTypeDef,
+    AppInstanceBotSummaryTypeDef,
     ChannelRetentionSettingsTypeDef,
     AppInstanceSummaryTypeDef,
     AppInstanceTypeDef,
     EndpointStateTypeDef,
     EndpointAttributesTypeDef,
     AppInstanceUserSummaryTypeDef,
-    AppInstanceUserTypeDef,
+    ExpirationSettingsTypeDef,
     CreateAppInstanceAdminRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
+    CreateAppInstanceBotResponseTypeDef,
+    CreateAppInstanceResponseTypeDef,
+    CreateAppInstanceUserResponseTypeDef,
     DeleteAppInstanceAdminRequestRequestTypeDef,
+    DeleteAppInstanceBotRequestRequestTypeDef,
     DeleteAppInstanceRequestRequestTypeDef,
     DeleteAppInstanceUserRequestRequestTypeDef,
     DeregisterAppInstanceUserEndpointRequestRequestTypeDef,
     DescribeAppInstanceAdminRequestRequestTypeDef,
+    DescribeAppInstanceBotRequestRequestTypeDef,
     DescribeAppInstanceRequestRequestTypeDef,
     DescribeAppInstanceUserEndpointRequestRequestTypeDef,
     DescribeAppInstanceUserRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetAppInstanceRetentionSettingsRequestRequestTypeDef,
+    InvokedByTypeDef,
     ListAppInstanceAdminsRequestRequestTypeDef,
+    ListAppInstanceBotsRequestRequestTypeDef,
     ListAppInstanceUserEndpointsRequestRequestTypeDef,
     ListAppInstanceUsersRequestRequestTypeDef,
     ListAppInstancesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    RegisterAppInstanceUserEndpointResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAppInstanceBotResponseTypeDef,
     UpdateAppInstanceRequestRequestTypeDef,
+    UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserEndpointRequestRequestTypeDef,
+    UpdateAppInstanceUserEndpointResponseTypeDef,
     UpdateAppInstanceUserRequestRequestTypeDef,
+    UpdateAppInstanceUserResponseTypeDef,
     AppInstanceAdminSummaryTypeDef,
     AppInstanceAdminTypeDef,
+    CreateAppInstanceAdminResponseTypeDef,
+    ListAppInstanceBotsResponseTypeDef,
     AppInstanceRetentionSettingsTypeDef,
+    ListAppInstancesResponseTypeDef,
+    DescribeAppInstanceResponseTypeDef,
     AppInstanceUserEndpointSummaryTypeDef,
     AppInstanceUserEndpointTypeDef,
     RegisterAppInstanceUserEndpointRequestRequestTypeDef,
-    CreateAppInstanceAdminResponseTypeDef,
-    CreateAppInstanceResponseTypeDef,
-    CreateAppInstanceUserResponseTypeDef,
-    DescribeAppInstanceResponseTypeDef,
-    DescribeAppInstanceUserResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListAppInstanceUsersResponseTypeDef,
-    ListAppInstancesResponseTypeDef,
-    RegisterAppInstanceUserEndpointResponseTypeDef,
-    UpdateAppInstanceResponseTypeDef,
-    UpdateAppInstanceUserEndpointResponseTypeDef,
-    UpdateAppInstanceUserResponseTypeDef,
+    AppInstanceUserTypeDef,
+    PutAppInstanceUserExpirationSettingsRequestRequestTypeDef,
+    PutAppInstanceUserExpirationSettingsResponseTypeDef,
     CreateAppInstanceRequestRequestTypeDef,
     CreateAppInstanceUserRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    LexConfigurationTypeDef,
     ListAppInstanceAdminsResponseTypeDef,
     DescribeAppInstanceAdminResponseTypeDef,
     GetAppInstanceRetentionSettingsResponseTypeDef,
     PutAppInstanceRetentionSettingsRequestRequestTypeDef,
     PutAppInstanceRetentionSettingsResponseTypeDef,
     ListAppInstanceUserEndpointsResponseTypeDef,
     DescribeAppInstanceUserEndpointResponseTypeDef,
+    DescribeAppInstanceUserResponseTypeDef,
+    ConfigurationTypeDef,
+    AppInstanceBotTypeDef,
+    CreateAppInstanceBotRequestRequestTypeDef,
+    UpdateAppInstanceBotRequestRequestTypeDef,
+    DescribeAppInstanceBotResponseTypeDef,
 )
 
 
 def get_structure() -> IdentityTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/README.md` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-chime-sdk-identity
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ChimeSDKIdentity 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore chime-sdk-identity type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-chime-sdk-identity"></a>
 
 # types-aiobotocore-chime-sdk-identity
 
 [![PyPI - types-aiobotocore-chime-sdk-identity](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-identity)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-identity)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-identity?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-identity)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKIdentity 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity)
+[aiobotocore.ChimeSDKIdentity 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity)
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
 [types-aiobotocore-chime-sdk-identity docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/).
 
 See how it helps to find and fix potential bugs:
 
@@ -240,14 +273,18 @@
 
 ```python
 from types_aiobotocore_chime_sdk_identity.literals import (
     AllowMessagesType,
     AppInstanceUserEndpointTypeType,
     EndpointStatusReasonType,
     EndpointStatusType,
+    ExpirationCriterionType,
+    RespondsToType,
+    StandardMessagesType,
+    TargetedMessagesType,
     ChimeSDKIdentityServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
@@ -261,114 +298,131 @@
 
 `types_aiobotocore_chime_sdk_identity.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_chime_sdk_identity.type_defs import (
     IdentityTypeDef,
+    AppInstanceBotSummaryTypeDef,
     ChannelRetentionSettingsTypeDef,
     AppInstanceSummaryTypeDef,
     AppInstanceTypeDef,
     EndpointStateTypeDef,
     EndpointAttributesTypeDef,
     AppInstanceUserSummaryTypeDef,
-    AppInstanceUserTypeDef,
+    ExpirationSettingsTypeDef,
     CreateAppInstanceAdminRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
+    CreateAppInstanceBotResponseTypeDef,
+    CreateAppInstanceResponseTypeDef,
+    CreateAppInstanceUserResponseTypeDef,
     DeleteAppInstanceAdminRequestRequestTypeDef,
+    DeleteAppInstanceBotRequestRequestTypeDef,
     DeleteAppInstanceRequestRequestTypeDef,
     DeleteAppInstanceUserRequestRequestTypeDef,
     DeregisterAppInstanceUserEndpointRequestRequestTypeDef,
     DescribeAppInstanceAdminRequestRequestTypeDef,
+    DescribeAppInstanceBotRequestRequestTypeDef,
     DescribeAppInstanceRequestRequestTypeDef,
     DescribeAppInstanceUserEndpointRequestRequestTypeDef,
     DescribeAppInstanceUserRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetAppInstanceRetentionSettingsRequestRequestTypeDef,
+    InvokedByTypeDef,
     ListAppInstanceAdminsRequestRequestTypeDef,
+    ListAppInstanceBotsRequestRequestTypeDef,
     ListAppInstanceUserEndpointsRequestRequestTypeDef,
     ListAppInstanceUsersRequestRequestTypeDef,
     ListAppInstancesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    RegisterAppInstanceUserEndpointResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAppInstanceBotResponseTypeDef,
     UpdateAppInstanceRequestRequestTypeDef,
+    UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserEndpointRequestRequestTypeDef,
+    UpdateAppInstanceUserEndpointResponseTypeDef,
     UpdateAppInstanceUserRequestRequestTypeDef,
+    UpdateAppInstanceUserResponseTypeDef,
     AppInstanceAdminSummaryTypeDef,
     AppInstanceAdminTypeDef,
+    CreateAppInstanceAdminResponseTypeDef,
+    ListAppInstanceBotsResponseTypeDef,
     AppInstanceRetentionSettingsTypeDef,
+    ListAppInstancesResponseTypeDef,
+    DescribeAppInstanceResponseTypeDef,
     AppInstanceUserEndpointSummaryTypeDef,
     AppInstanceUserEndpointTypeDef,
     RegisterAppInstanceUserEndpointRequestRequestTypeDef,
-    CreateAppInstanceAdminResponseTypeDef,
-    CreateAppInstanceResponseTypeDef,
-    CreateAppInstanceUserResponseTypeDef,
-    DescribeAppInstanceResponseTypeDef,
-    DescribeAppInstanceUserResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListAppInstanceUsersResponseTypeDef,
-    ListAppInstancesResponseTypeDef,
-    RegisterAppInstanceUserEndpointResponseTypeDef,
-    UpdateAppInstanceResponseTypeDef,
-    UpdateAppInstanceUserEndpointResponseTypeDef,
-    UpdateAppInstanceUserResponseTypeDef,
+    AppInstanceUserTypeDef,
+    PutAppInstanceUserExpirationSettingsRequestRequestTypeDef,
+    PutAppInstanceUserExpirationSettingsResponseTypeDef,
     CreateAppInstanceRequestRequestTypeDef,
     CreateAppInstanceUserRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    LexConfigurationTypeDef,
     ListAppInstanceAdminsResponseTypeDef,
     DescribeAppInstanceAdminResponseTypeDef,
     GetAppInstanceRetentionSettingsResponseTypeDef,
     PutAppInstanceRetentionSettingsRequestRequestTypeDef,
     PutAppInstanceRetentionSettingsResponseTypeDef,
     ListAppInstanceUserEndpointsResponseTypeDef,
     DescribeAppInstanceUserEndpointResponseTypeDef,
+    DescribeAppInstanceUserResponseTypeDef,
+    ConfigurationTypeDef,
+    AppInstanceBotTypeDef,
+    CreateAppInstanceBotRequestRequestTypeDef,
+    UpdateAppInstanceBotRequestRequestTypeDef,
+    DescribeAppInstanceBotResponseTypeDef,
 )
 
 
 def get_structure() -> IdentityTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/setup.py` & `types-aiobotocore-chime-sdk-identity-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-chime-sdk-identity.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-chime-sdk-identity",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_chime_sdk_identity"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ChimeSDKIdentity 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ChimeSDKIdentity 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/"
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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/__init__.py` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/__init__.pyi` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/__main__.py` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/__main__.py`

 * *Files 17% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ChimeSDKIdentity 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ChimeSDKIdentity 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity\nOther"
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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/client.py` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/client.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -18,60 +18,65 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import AllowMessagesType, AppInstanceUserEndpointTypeType
 from .type_defs import (
     AppInstanceRetentionSettingsTypeDef,
+    ConfigurationTypeDef,
     CreateAppInstanceAdminResponseTypeDef,
+    CreateAppInstanceBotResponseTypeDef,
     CreateAppInstanceResponseTypeDef,
     CreateAppInstanceUserResponseTypeDef,
     DescribeAppInstanceAdminResponseTypeDef,
+    DescribeAppInstanceBotResponseTypeDef,
     DescribeAppInstanceResponseTypeDef,
     DescribeAppInstanceUserEndpointResponseTypeDef,
     DescribeAppInstanceUserResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     EndpointAttributesTypeDef,
+    ExpirationSettingsTypeDef,
     GetAppInstanceRetentionSettingsResponseTypeDef,
     ListAppInstanceAdminsResponseTypeDef,
+    ListAppInstanceBotsResponseTypeDef,
     ListAppInstancesResponseTypeDef,
     ListAppInstanceUserEndpointsResponseTypeDef,
     ListAppInstanceUsersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutAppInstanceRetentionSettingsResponseTypeDef,
+    PutAppInstanceUserExpirationSettingsResponseTypeDef,
     RegisterAppInstanceUserEndpointResponseTypeDef,
     TagTypeDef,
+    UpdateAppInstanceBotResponseTypeDef,
     UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserEndpointResponseTypeDef,
     UpdateAppInstanceUserResponseTypeDef,
 )
 
 __all__ = ("ChimeSDKIdentityClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
+    NotFoundException: Type[BotocoreClientError]
     ResourceLimitExceededException: Type[BotocoreClientError]
     ServiceFailureException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     ThrottledClientException: Type[BotocoreClientError]
     UnauthorizedClientException: Type[BotocoreClientError]
 
-
 class ChimeSDKIdentityClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/)
     """
 
     meta: ClientMeta
@@ -80,239 +85,270 @@
     def exceptions(self) -> Exceptions:
         """
         ChimeSDKIdentityClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#exceptions)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#close)
         """
-
     async def create_app_instance(
         self,
         *,
         Name: str,
         ClientRequestToken: str,
         Metadata: str = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateAppInstanceResponseTypeDef:
         """
         Creates an Amazon Chime SDK messaging `AppInstance` under an AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance)
         """
-
     async def create_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> CreateAppInstanceAdminResponseTypeDef:
         """
-        Promotes an `AppInstanceUser` to an `AppInstanceAdmin`.
+        Promotes an `AppInstanceUser` or `AppInstanceBot` to an `AppInstanceAdmin`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance_admin)
         """
+    async def create_app_instance_bot(
+        self,
+        *,
+        AppInstanceArn: str,
+        ClientRequestToken: str,
+        Configuration: ConfigurationTypeDef,
+        Name: str = ...,
+        Metadata: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateAppInstanceBotResponseTypeDef:
+        """
+        Creates a bot under an Amazon Chime `AppInstance`.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance_bot)
+        """
     async def create_app_instance_user(
         self,
         *,
         AppInstanceArn: str,
         AppInstanceUserId: str,
         Name: str,
         ClientRequestToken: str,
         Metadata: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        ExpirationSettings: ExpirationSettingsTypeDef = ...
     ) -> CreateAppInstanceUserResponseTypeDef:
         """
         Creates a user under an Amazon Chime `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance_user)
         """
-
     async def delete_app_instance(self, *, AppInstanceArn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an `AppInstance` and all associated data asynchronously.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance)
         """
-
     async def delete_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Demotes an `AppInstanceAdmin` to an `AppInstanceUser`.
+        Demotes an `AppInstanceAdmin` to an `AppInstanceUser` or `AppInstanceBot`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance_admin)
         """
+    async def delete_app_instance_bot(
+        self, *, AppInstanceBotArn: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes an `AppInstanceBot`.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance_bot)
+        """
     async def delete_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes an `AppInstanceUser` .
+        Deletes an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance_user)
         """
-
     async def deregister_app_instance_user_endpoint(
         self, *, AppInstanceUserArn: str, EndpointId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deregisters an `AppInstanceUserEndpoint` .
+        Deregisters an `AppInstanceUserEndpoint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.deregister_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#deregister_app_instance_user_endpoint)
         """
-
     async def describe_app_instance(
         self, *, AppInstanceArn: str
     ) -> DescribeAppInstanceResponseTypeDef:
         """
-        Returns the full details of an `AppInstance` .
+        Returns the full details of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance)
         """
-
     async def describe_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> DescribeAppInstanceAdminResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceAdmin` .
+        Returns the full details of an `AppInstanceAdmin`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_admin)
         """
+    async def describe_app_instance_bot(
+        self, *, AppInstanceBotArn: str
+    ) -> DescribeAppInstanceBotResponseTypeDef:
+        """
+        The `AppInstanceBot's` information.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_bot)
+        """
     async def describe_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> DescribeAppInstanceUserResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceUser` .
+        Returns the full details of an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_user)
         """
-
     async def describe_app_instance_user_endpoint(
         self, *, AppInstanceUserArn: str, EndpointId: str
     ) -> DescribeAppInstanceUserEndpointResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceUserEndpoint` .
+        Returns the full details of an `AppInstanceUserEndpoint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_user_endpoint)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#generate_presigned_url)
         """
-
     async def get_app_instance_retention_settings(
         self, *, AppInstanceArn: str
     ) -> GetAppInstanceRetentionSettingsResponseTypeDef:
         """
-        Gets the retention settings for an `AppInstance` .
+        Gets the retention settings for an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.get_app_instance_retention_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#get_app_instance_retention_settings)
         """
-
     async def list_app_instance_admins(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceAdminsResponseTypeDef:
         """
-        Returns a list of the administrators in the `AppInstance` .
+        Returns a list of the administrators in the `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_admins)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_admins)
         """
+    async def list_app_instance_bots(
+        self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListAppInstanceBotsResponseTypeDef:
+        """
+        Lists all `AppInstanceBots` created under a single `AppInstance`.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_bots)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_bots)
+        """
     async def list_app_instance_user_endpoints(
         self, *, AppInstanceUserArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceUserEndpointsResponseTypeDef:
         """
         Lists all the `AppInstanceUserEndpoints` created under a single
-        `AppInstanceUser` .
+        `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_user_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_user_endpoints)
         """
-
     async def list_app_instance_users(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceUsersResponseTypeDef:
         """
-        List all `AppInstanceUsers` created under a single `AppInstance` .
+        List all `AppInstanceUsers` created under a single `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_users)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_users)
         """
-
     async def list_app_instances(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstancesResponseTypeDef:
         """
-        Lists all Amazon Chime `AppInstance` s created under a single AWS account.
+        Lists all Amazon Chime `AppInstance`s created under a single AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instances)
         """
-
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags applied to an Amazon Chime SDK identity resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_tags_for_resource)
         """
-
     async def put_app_instance_retention_settings(
         self,
         *,
         AppInstanceArn: str,
         AppInstanceRetentionSettings: AppInstanceRetentionSettingsTypeDef
     ) -> PutAppInstanceRetentionSettingsResponseTypeDef:
         """
         Sets the amount of time in days that a given `AppInstance` retains data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.put_app_instance_retention_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#put_app_instance_retention_settings)
         """
+    async def put_app_instance_user_expiration_settings(
+        self, *, AppInstanceUserArn: str, ExpirationSettings: ExpirationSettingsTypeDef = ...
+    ) -> PutAppInstanceUserExpirationSettingsResponseTypeDef:
+        """
+        Sets the number of days before the `AppInstanceUser` is automatically deleted.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.put_app_instance_user_expiration_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#put_app_instance_user_expiration_settings)
+        """
     async def register_app_instance_user_endpoint(
         self,
         *,
         AppInstanceUserArn: str,
         Type: AppInstanceUserEndpointTypeType,
         ResourceArn: str,
         EndpointAttributes: EndpointAttributesTypeDef,
@@ -322,75 +358,82 @@
     ) -> RegisterAppInstanceUserEndpointResponseTypeDef:
         """
         Registers an endpoint under an Amazon Chime `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.register_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#register_app_instance_user_endpoint)
         """
-
     async def tag_resource(
         self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Applies the specified tags to the specified Amazon Chime SDK identity resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#tag_resource)
         """
-
     async def untag_resource(
         self, *, ResourceARN: str, TagKeys: Sequence[str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Removes the specified tags from the specified Amazon Chime SDK identity
         resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#untag_resource)
         """
-
     async def update_app_instance(
         self, *, AppInstanceArn: str, Name: str, Metadata: str
     ) -> UpdateAppInstanceResponseTypeDef:
         """
         Updates `AppInstance` metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance)
         """
+    async def update_app_instance_bot(
+        self,
+        *,
+        AppInstanceBotArn: str,
+        Name: str,
+        Metadata: str,
+        Configuration: ConfigurationTypeDef = ...
+    ) -> UpdateAppInstanceBotResponseTypeDef:
+        """
+        Updates the name and metadata of an `AppInstanceBot`.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance_bot)
+        """
     async def update_app_instance_user(
         self, *, AppInstanceUserArn: str, Name: str, Metadata: str
     ) -> UpdateAppInstanceUserResponseTypeDef:
         """
         Updates the details of an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance_user)
         """
-
     async def update_app_instance_user_endpoint(
         self,
         *,
         AppInstanceUserArn: str,
         EndpointId: str,
         Name: str = ...,
         AllowMessages: AllowMessagesType = ...
     ) -> UpdateAppInstanceUserEndpointResponseTypeDef:
         """
         Updates the details of an `AppInstanceUserEndpoint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance_user_endpoint)
         """
-
     async def __aenter__(self) -> "ChimeSDKIdentityClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/)
         """
```

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/client.pyi` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/client.py`

 * *Files 8% similar despite different names*

```diff
@@ -18,57 +18,68 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import AllowMessagesType, AppInstanceUserEndpointTypeType
 from .type_defs import (
     AppInstanceRetentionSettingsTypeDef,
+    ConfigurationTypeDef,
     CreateAppInstanceAdminResponseTypeDef,
+    CreateAppInstanceBotResponseTypeDef,
     CreateAppInstanceResponseTypeDef,
     CreateAppInstanceUserResponseTypeDef,
     DescribeAppInstanceAdminResponseTypeDef,
+    DescribeAppInstanceBotResponseTypeDef,
     DescribeAppInstanceResponseTypeDef,
     DescribeAppInstanceUserEndpointResponseTypeDef,
     DescribeAppInstanceUserResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     EndpointAttributesTypeDef,
+    ExpirationSettingsTypeDef,
     GetAppInstanceRetentionSettingsResponseTypeDef,
     ListAppInstanceAdminsResponseTypeDef,
+    ListAppInstanceBotsResponseTypeDef,
     ListAppInstancesResponseTypeDef,
     ListAppInstanceUserEndpointsResponseTypeDef,
     ListAppInstanceUsersResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutAppInstanceRetentionSettingsResponseTypeDef,
+    PutAppInstanceUserExpirationSettingsResponseTypeDef,
     RegisterAppInstanceUserEndpointResponseTypeDef,
     TagTypeDef,
+    UpdateAppInstanceBotResponseTypeDef,
     UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserEndpointResponseTypeDef,
     UpdateAppInstanceUserResponseTypeDef,
 )
 
 __all__ = ("ChimeSDKIdentityClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     ForbiddenException: Type[BotocoreClientError]
+    NotFoundException: Type[BotocoreClientError]
     ResourceLimitExceededException: Type[BotocoreClientError]
     ServiceFailureException: Type[BotocoreClientError]
     ServiceUnavailableException: Type[BotocoreClientError]
     ThrottledClientException: Type[BotocoreClientError]
     UnauthorizedClientException: Type[BotocoreClientError]
 
+
 class ChimeSDKIdentityClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/)
     """
 
     meta: ClientMeta
@@ -77,217 +88,297 @@
     def exceptions(self) -> Exceptions:
         """
         ChimeSDKIdentityClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#exceptions)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#close)
         """
+
     async def create_app_instance(
         self,
         *,
         Name: str,
         ClientRequestToken: str,
         Metadata: str = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateAppInstanceResponseTypeDef:
         """
         Creates an Amazon Chime SDK messaging `AppInstance` under an AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance)
         """
+
     async def create_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> CreateAppInstanceAdminResponseTypeDef:
         """
-        Promotes an `AppInstanceUser` to an `AppInstanceAdmin`.
+        Promotes an `AppInstanceUser` or `AppInstanceBot` to an `AppInstanceAdmin`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance_admin)
         """
+
+    async def create_app_instance_bot(
+        self,
+        *,
+        AppInstanceArn: str,
+        ClientRequestToken: str,
+        Configuration: ConfigurationTypeDef,
+        Name: str = ...,
+        Metadata: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateAppInstanceBotResponseTypeDef:
+        """
+        Creates a bot under an Amazon Chime `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance_bot)
+        """
+
     async def create_app_instance_user(
         self,
         *,
         AppInstanceArn: str,
         AppInstanceUserId: str,
         Name: str,
         ClientRequestToken: str,
         Metadata: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        ExpirationSettings: ExpirationSettingsTypeDef = ...
     ) -> CreateAppInstanceUserResponseTypeDef:
         """
         Creates a user under an Amazon Chime `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.create_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#create_app_instance_user)
         """
+
     async def delete_app_instance(self, *, AppInstanceArn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an `AppInstance` and all associated data asynchronously.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance)
         """
+
     async def delete_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Demotes an `AppInstanceAdmin` to an `AppInstanceUser`.
+        Demotes an `AppInstanceAdmin` to an `AppInstanceUser` or `AppInstanceBot`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance_admin)
         """
+
+    async def delete_app_instance_bot(
+        self, *, AppInstanceBotArn: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes an `AppInstanceBot`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance_bot)
+        """
+
     async def delete_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes an `AppInstanceUser` .
+        Deletes an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.delete_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#delete_app_instance_user)
         """
+
     async def deregister_app_instance_user_endpoint(
         self, *, AppInstanceUserArn: str, EndpointId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deregisters an `AppInstanceUserEndpoint` .
+        Deregisters an `AppInstanceUserEndpoint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.deregister_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#deregister_app_instance_user_endpoint)
         """
+
     async def describe_app_instance(
         self, *, AppInstanceArn: str
     ) -> DescribeAppInstanceResponseTypeDef:
         """
-        Returns the full details of an `AppInstance` .
+        Returns the full details of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance)
         """
+
     async def describe_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> DescribeAppInstanceAdminResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceAdmin` .
+        Returns the full details of an `AppInstanceAdmin`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_admin)
         """
+
+    async def describe_app_instance_bot(
+        self, *, AppInstanceBotArn: str
+    ) -> DescribeAppInstanceBotResponseTypeDef:
+        """
+        The `AppInstanceBot's` information.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_bot)
+        """
+
     async def describe_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> DescribeAppInstanceUserResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceUser` .
+        Returns the full details of an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_user)
         """
+
     async def describe_app_instance_user_endpoint(
         self, *, AppInstanceUserArn: str, EndpointId: str
     ) -> DescribeAppInstanceUserEndpointResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceUserEndpoint` .
+        Returns the full details of an `AppInstanceUserEndpoint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.describe_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#describe_app_instance_user_endpoint)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#generate_presigned_url)
         """
+
     async def get_app_instance_retention_settings(
         self, *, AppInstanceArn: str
     ) -> GetAppInstanceRetentionSettingsResponseTypeDef:
         """
-        Gets the retention settings for an `AppInstance` .
+        Gets the retention settings for an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.get_app_instance_retention_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#get_app_instance_retention_settings)
         """
+
     async def list_app_instance_admins(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceAdminsResponseTypeDef:
         """
-        Returns a list of the administrators in the `AppInstance` .
+        Returns a list of the administrators in the `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_admins)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_admins)
         """
+
+    async def list_app_instance_bots(
+        self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListAppInstanceBotsResponseTypeDef:
+        """
+        Lists all `AppInstanceBots` created under a single `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_bots)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_bots)
+        """
+
     async def list_app_instance_user_endpoints(
         self, *, AppInstanceUserArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceUserEndpointsResponseTypeDef:
         """
         Lists all the `AppInstanceUserEndpoints` created under a single
-        `AppInstanceUser` .
+        `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_user_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_user_endpoints)
         """
+
     async def list_app_instance_users(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceUsersResponseTypeDef:
         """
-        List all `AppInstanceUsers` created under a single `AppInstance` .
+        List all `AppInstanceUsers` created under a single `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instance_users)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instance_users)
         """
+
     async def list_app_instances(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstancesResponseTypeDef:
         """
-        Lists all Amazon Chime `AppInstance` s created under a single AWS account.
+        Lists all Amazon Chime `AppInstance`s created under a single AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_app_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_app_instances)
         """
+
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags applied to an Amazon Chime SDK identity resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#list_tags_for_resource)
         """
+
     async def put_app_instance_retention_settings(
         self,
         *,
         AppInstanceArn: str,
         AppInstanceRetentionSettings: AppInstanceRetentionSettingsTypeDef
     ) -> PutAppInstanceRetentionSettingsResponseTypeDef:
         """
         Sets the amount of time in days that a given `AppInstance` retains data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.put_app_instance_retention_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#put_app_instance_retention_settings)
         """
+
+    async def put_app_instance_user_expiration_settings(
+        self, *, AppInstanceUserArn: str, ExpirationSettings: ExpirationSettingsTypeDef = ...
+    ) -> PutAppInstanceUserExpirationSettingsResponseTypeDef:
+        """
+        Sets the number of days before the `AppInstanceUser` is automatically deleted.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.put_app_instance_user_expiration_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#put_app_instance_user_expiration_settings)
+        """
+
     async def register_app_instance_user_endpoint(
         self,
         *,
         AppInstanceUserArn: str,
         Type: AppInstanceUserEndpointTypeType,
         ResourceArn: str,
         EndpointAttributes: EndpointAttributesTypeDef,
@@ -297,68 +388,90 @@
     ) -> RegisterAppInstanceUserEndpointResponseTypeDef:
         """
         Registers an endpoint under an Amazon Chime `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.register_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#register_app_instance_user_endpoint)
         """
+
     async def tag_resource(
         self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Applies the specified tags to the specified Amazon Chime SDK identity resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#tag_resource)
         """
+
     async def untag_resource(
         self, *, ResourceARN: str, TagKeys: Sequence[str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Removes the specified tags from the specified Amazon Chime SDK identity
         resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#untag_resource)
         """
+
     async def update_app_instance(
         self, *, AppInstanceArn: str, Name: str, Metadata: str
     ) -> UpdateAppInstanceResponseTypeDef:
         """
         Updates `AppInstance` metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance)
         """
+
+    async def update_app_instance_bot(
+        self,
+        *,
+        AppInstanceBotArn: str,
+        Name: str,
+        Metadata: str,
+        Configuration: ConfigurationTypeDef = ...
+    ) -> UpdateAppInstanceBotResponseTypeDef:
+        """
+        Updates the name and metadata of an `AppInstanceBot`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance_bot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance_bot)
+        """
+
     async def update_app_instance_user(
         self, *, AppInstanceUserArn: str, Name: str, Metadata: str
     ) -> UpdateAppInstanceUserResponseTypeDef:
         """
         Updates the details of an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance_user)
         """
+
     async def update_app_instance_user_endpoint(
         self,
         *,
         AppInstanceUserArn: str,
         EndpointId: str,
         Name: str = ...,
         AllowMessages: AllowMessagesType = ...
     ) -> UpdateAppInstanceUserEndpointResponseTypeDef:
         """
         Updates the details of an `AppInstanceUserEndpoint`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client.update_app_instance_user_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/#update_app_instance_user_endpoint)
         """
+
     async def __aenter__(self) -> "ChimeSDKIdentityClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/client/)
         """
```

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/literals.py` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/literals.py`

 * *Files 9% similar despite different names*

```diff
@@ -20,25 +20,33 @@
 
 
 __all__ = (
     "AllowMessagesType",
     "AppInstanceUserEndpointTypeType",
     "EndpointStatusReasonType",
     "EndpointStatusType",
+    "ExpirationCriterionType",
+    "RespondsToType",
+    "StandardMessagesType",
+    "TargetedMessagesType",
     "ChimeSDKIdentityServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 
 AllowMessagesType = Literal["ALL", "NONE"]
 AppInstanceUserEndpointTypeType = Literal["APNS", "APNS_SANDBOX", "GCM"]
 EndpointStatusReasonType = Literal["INVALID_DEVICE_TOKEN", "INVALID_PINPOINT_ARN"]
 EndpointStatusType = Literal["ACTIVE", "INACTIVE"]
+ExpirationCriterionType = Literal["CREATED_TIMESTAMP"]
+RespondsToType = Literal["STANDARD_MESSAGES"]
+StandardMessagesType = Literal["ALL", "AUTO", "MENTIONS", "NONE"]
+TargetedMessagesType = Literal["ALL", "NONE"]
 ChimeSDKIdentityServiceName = Literal["chime-sdk-identity"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -94,14 +102,15 @@
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
@@ -180,14 +189,15 @@
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
@@ -198,14 +208,15 @@
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
@@ -241,14 +252,15 @@
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
@@ -267,16 +279,19 @@
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
@@ -360,15 +375,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/literals.pyi` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/literals.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -19,24 +19,32 @@
     from typing_extensions import Literal
 
 __all__ = (
     "AllowMessagesType",
     "AppInstanceUserEndpointTypeType",
     "EndpointStatusReasonType",
     "EndpointStatusType",
+    "ExpirationCriterionType",
+    "RespondsToType",
+    "StandardMessagesType",
+    "TargetedMessagesType",
     "ChimeSDKIdentityServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 AllowMessagesType = Literal["ALL", "NONE"]
 AppInstanceUserEndpointTypeType = Literal["APNS", "APNS_SANDBOX", "GCM"]
 EndpointStatusReasonType = Literal["INVALID_DEVICE_TOKEN", "INVALID_PINPOINT_ARN"]
 EndpointStatusType = Literal["ACTIVE", "INACTIVE"]
+ExpirationCriterionType = Literal["CREATED_TIMESTAMP"]
+RespondsToType = Literal["STANDARD_MESSAGES"]
+StandardMessagesType = Literal["ALL", "AUTO", "MENTIONS", "NONE"]
+TargetedMessagesType = Literal["ALL", "NONE"]
 ChimeSDKIdentityServiceName = Literal["chime-sdk-identity"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -92,14 +100,15 @@
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
@@ -178,14 +187,15 @@
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
@@ -196,14 +206,15 @@
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
@@ -239,14 +250,15 @@
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
@@ -265,16 +277,19 @@
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
@@ -358,15 +373,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/type_defs.py` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/type_defs.py`

 * *Files 16% similar despite different names*

```diff
@@ -16,92 +16,125 @@
 from typing import Dict, List, Sequence
 
 from .literals import (
     AllowMessagesType,
     AppInstanceUserEndpointTypeType,
     EndpointStatusReasonType,
     EndpointStatusType,
+    StandardMessagesType,
+    TargetedMessagesType,
 )
 
 if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "IdentityTypeDef",
+    "AppInstanceBotSummaryTypeDef",
     "ChannelRetentionSettingsTypeDef",
     "AppInstanceSummaryTypeDef",
     "AppInstanceTypeDef",
     "EndpointStateTypeDef",
     "EndpointAttributesTypeDef",
     "AppInstanceUserSummaryTypeDef",
-    "AppInstanceUserTypeDef",
+    "ExpirationSettingsTypeDef",
     "CreateAppInstanceAdminRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
+    "CreateAppInstanceBotResponseTypeDef",
+    "CreateAppInstanceResponseTypeDef",
+    "CreateAppInstanceUserResponseTypeDef",
     "DeleteAppInstanceAdminRequestRequestTypeDef",
+    "DeleteAppInstanceBotRequestRequestTypeDef",
     "DeleteAppInstanceRequestRequestTypeDef",
     "DeleteAppInstanceUserRequestRequestTypeDef",
     "DeregisterAppInstanceUserEndpointRequestRequestTypeDef",
     "DescribeAppInstanceAdminRequestRequestTypeDef",
+    "DescribeAppInstanceBotRequestRequestTypeDef",
     "DescribeAppInstanceRequestRequestTypeDef",
     "DescribeAppInstanceUserEndpointRequestRequestTypeDef",
     "DescribeAppInstanceUserRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetAppInstanceRetentionSettingsRequestRequestTypeDef",
+    "InvokedByTypeDef",
     "ListAppInstanceAdminsRequestRequestTypeDef",
+    "ListAppInstanceBotsRequestRequestTypeDef",
     "ListAppInstanceUserEndpointsRequestRequestTypeDef",
     "ListAppInstanceUsersRequestRequestTypeDef",
     "ListAppInstancesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "RegisterAppInstanceUserEndpointResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAppInstanceBotResponseTypeDef",
     "UpdateAppInstanceRequestRequestTypeDef",
+    "UpdateAppInstanceResponseTypeDef",
     "UpdateAppInstanceUserEndpointRequestRequestTypeDef",
+    "UpdateAppInstanceUserEndpointResponseTypeDef",
     "UpdateAppInstanceUserRequestRequestTypeDef",
+    "UpdateAppInstanceUserResponseTypeDef",
     "AppInstanceAdminSummaryTypeDef",
     "AppInstanceAdminTypeDef",
+    "CreateAppInstanceAdminResponseTypeDef",
+    "ListAppInstanceBotsResponseTypeDef",
     "AppInstanceRetentionSettingsTypeDef",
+    "ListAppInstancesResponseTypeDef",
+    "DescribeAppInstanceResponseTypeDef",
     "AppInstanceUserEndpointSummaryTypeDef",
     "AppInstanceUserEndpointTypeDef",
     "RegisterAppInstanceUserEndpointRequestRequestTypeDef",
-    "CreateAppInstanceAdminResponseTypeDef",
-    "CreateAppInstanceResponseTypeDef",
-    "CreateAppInstanceUserResponseTypeDef",
-    "DescribeAppInstanceResponseTypeDef",
-    "DescribeAppInstanceUserResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListAppInstanceUsersResponseTypeDef",
-    "ListAppInstancesResponseTypeDef",
-    "RegisterAppInstanceUserEndpointResponseTypeDef",
-    "UpdateAppInstanceResponseTypeDef",
-    "UpdateAppInstanceUserEndpointResponseTypeDef",
-    "UpdateAppInstanceUserResponseTypeDef",
+    "AppInstanceUserTypeDef",
+    "PutAppInstanceUserExpirationSettingsRequestRequestTypeDef",
+    "PutAppInstanceUserExpirationSettingsResponseTypeDef",
     "CreateAppInstanceRequestRequestTypeDef",
     "CreateAppInstanceUserRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "LexConfigurationTypeDef",
     "ListAppInstanceAdminsResponseTypeDef",
     "DescribeAppInstanceAdminResponseTypeDef",
     "GetAppInstanceRetentionSettingsResponseTypeDef",
     "PutAppInstanceRetentionSettingsRequestRequestTypeDef",
     "PutAppInstanceRetentionSettingsResponseTypeDef",
     "ListAppInstanceUserEndpointsResponseTypeDef",
     "DescribeAppInstanceUserEndpointResponseTypeDef",
+    "DescribeAppInstanceUserResponseTypeDef",
+    "ConfigurationTypeDef",
+    "AppInstanceBotTypeDef",
+    "CreateAppInstanceBotRequestRequestTypeDef",
+    "UpdateAppInstanceBotRequestRequestTypeDef",
+    "DescribeAppInstanceBotResponseTypeDef",
 )
 
 IdentityTypeDef = TypedDict(
     "IdentityTypeDef",
     {
         "Arn": str,
         "Name": str,
     },
     total=False,
 )
 
+AppInstanceBotSummaryTypeDef = TypedDict(
+    "AppInstanceBotSummaryTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "Name": str,
+        "Metadata": str,
+    },
+    total=False,
+)
+
 ChannelRetentionSettingsTypeDef = TypedDict(
     "ChannelRetentionSettingsTypeDef",
     {
         "RetentionDays": int,
     },
     total=False,
 )
@@ -174,61 +207,77 @@
         "AppInstanceUserArn": str,
         "Name": str,
         "Metadata": str,
     },
     total=False,
 )
 
-AppInstanceUserTypeDef = TypedDict(
-    "AppInstanceUserTypeDef",
+ExpirationSettingsTypeDef = TypedDict(
+    "ExpirationSettingsTypeDef",
     {
-        "AppInstanceUserArn": str,
-        "Name": str,
-        "Metadata": str,
-        "CreatedTimestamp": datetime,
-        "LastUpdatedTimestamp": datetime,
+        "ExpirationDays": int,
+        "ExpirationCriterion": Literal["CREATED_TIMESTAMP"],
     },
-    total=False,
 )
 
 CreateAppInstanceAdminRequestRequestTypeDef = TypedDict(
     "CreateAppInstanceAdminRequestRequestTypeDef",
     {
         "AppInstanceAdminArn": str,
         "AppInstanceArn": str,
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateAppInstanceBotResponseTypeDef = TypedDict(
+    "CreateAppInstanceBotResponseTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAppInstanceResponseTypeDef = TypedDict(
+    "CreateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAppInstanceUserResponseTypeDef = TypedDict(
+    "CreateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAppInstanceAdminRequestRequestTypeDef = TypedDict(
     "DeleteAppInstanceAdminRequestRequestTypeDef",
     {
         "AppInstanceAdminArn": str,
         "AppInstanceArn": str,
     },
 )
 
+DeleteAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "DeleteAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceBotArn": str,
+    },
+)
+
 DeleteAppInstanceRequestRequestTypeDef = TypedDict(
     "DeleteAppInstanceRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 
@@ -251,14 +300,21 @@
     "DescribeAppInstanceAdminRequestRequestTypeDef",
     {
         "AppInstanceAdminArn": str,
         "AppInstanceArn": str,
     },
 )
 
+DescribeAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "DescribeAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceBotArn": str,
+    },
+)
+
 DescribeAppInstanceRequestRequestTypeDef = TypedDict(
     "DescribeAppInstanceRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 
@@ -273,21 +329,36 @@
 DescribeAppInstanceUserRequestRequestTypeDef = TypedDict(
     "DescribeAppInstanceUserRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAppInstanceRetentionSettingsRequestRequestTypeDef = TypedDict(
     "GetAppInstanceRetentionSettingsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 
+InvokedByTypeDef = TypedDict(
+    "InvokedByTypeDef",
+    {
+        "StandardMessages": StandardMessagesType,
+        "TargetedMessages": TargetedMessagesType,
+    },
+)
+
 _RequiredListAppInstanceAdminsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppInstanceAdminsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 _OptionalListAppInstanceAdminsRequestRequestTypeDef = TypedDict(
@@ -303,14 +374,37 @@
 class ListAppInstanceAdminsRequestRequestTypeDef(
     _RequiredListAppInstanceAdminsRequestRequestTypeDef,
     _OptionalListAppInstanceAdminsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListAppInstanceBotsRequestRequestTypeDef = TypedDict(
+    "_RequiredListAppInstanceBotsRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+    },
+)
+_OptionalListAppInstanceBotsRequestRequestTypeDef = TypedDict(
+    "_OptionalListAppInstanceBotsRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+
+class ListAppInstanceBotsRequestRequestTypeDef(
+    _RequiredListAppInstanceBotsRequestRequestTypeDef,
+    _OptionalListAppInstanceBotsRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredListAppInstanceUserEndpointsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppInstanceUserEndpointsRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
     },
 )
 _OptionalListAppInstanceUserEndpointsRequestRequestTypeDef = TypedDict(
@@ -365,31 +459,67 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+RegisterAppInstanceUserEndpointResponseTypeDef = TypedDict(
+    "RegisterAppInstanceUserEndpointResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "EndpointId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateAppInstanceBotResponseTypeDef = TypedDict(
+    "UpdateAppInstanceBotResponseTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAppInstanceRequestRequestTypeDef = TypedDict(
     "UpdateAppInstanceRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
         "Name": str,
         "Metadata": str,
     },
 )
 
+UpdateAppInstanceResponseTypeDef = TypedDict(
+    "UpdateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateAppInstanceUserEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAppInstanceUserEndpointRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
         "EndpointId": str,
     },
 )
@@ -406,23 +536,40 @@
 class UpdateAppInstanceUserEndpointRequestRequestTypeDef(
     _RequiredUpdateAppInstanceUserEndpointRequestRequestTypeDef,
     _OptionalUpdateAppInstanceUserEndpointRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateAppInstanceUserEndpointResponseTypeDef = TypedDict(
+    "UpdateAppInstanceUserEndpointResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "EndpointId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAppInstanceUserRequestRequestTypeDef = TypedDict(
     "UpdateAppInstanceUserRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
         "Name": str,
         "Metadata": str,
     },
 )
 
+UpdateAppInstanceUserResponseTypeDef = TypedDict(
+    "UpdateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppInstanceAdminSummaryTypeDef = TypedDict(
     "AppInstanceAdminSummaryTypeDef",
     {
         "Admin": IdentityTypeDef,
     },
     total=False,
 )
@@ -433,22 +580,58 @@
         "Admin": IdentityTypeDef,
         "AppInstanceArn": str,
         "CreatedTimestamp": datetime,
     },
     total=False,
 )
 
+CreateAppInstanceAdminResponseTypeDef = TypedDict(
+    "CreateAppInstanceAdminResponseTypeDef",
+    {
+        "AppInstanceAdmin": IdentityTypeDef,
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAppInstanceBotsResponseTypeDef = TypedDict(
+    "ListAppInstanceBotsResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "AppInstanceBots": List[AppInstanceBotSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppInstanceRetentionSettingsTypeDef = TypedDict(
     "AppInstanceRetentionSettingsTypeDef",
     {
         "ChannelRetentionSettings": ChannelRetentionSettingsTypeDef,
     },
     total=False,
 )
 
+ListAppInstancesResponseTypeDef = TypedDict(
+    "ListAppInstancesResponseTypeDef",
+    {
+        "AppInstances": List[AppInstanceSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAppInstanceResponseTypeDef = TypedDict(
+    "DescribeAppInstanceResponseTypeDef",
+    {
+        "AppInstance": AppInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppInstanceUserEndpointSummaryTypeDef = TypedDict(
     "AppInstanceUserEndpointSummaryTypeDef",
     {
         "AppInstanceUserArn": str,
         "EndpointId": str,
         "Name": str,
         "Type": AppInstanceUserEndpointTypeType,
@@ -498,112 +681,65 @@
 class RegisterAppInstanceUserEndpointRequestRequestTypeDef(
     _RequiredRegisterAppInstanceUserEndpointRequestRequestTypeDef,
     _OptionalRegisterAppInstanceUserEndpointRequestRequestTypeDef,
 ):
     pass
 
 
-CreateAppInstanceAdminResponseTypeDef = TypedDict(
-    "CreateAppInstanceAdminResponseTypeDef",
-    {
-        "AppInstanceAdmin": IdentityTypeDef,
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceResponseTypeDef = TypedDict(
-    "CreateAppInstanceResponseTypeDef",
-    {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceUserResponseTypeDef = TypedDict(
-    "CreateAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceResponseTypeDef = TypedDict(
-    "DescribeAppInstanceResponseTypeDef",
-    {
-        "AppInstance": AppInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceUserResponseTypeDef = TypedDict(
-    "DescribeAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUser": AppInstanceUserTypeDef,
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
 ListAppInstanceUsersResponseTypeDef = TypedDict(
     "ListAppInstanceUsersResponseTypeDef",
     {
         "AppInstanceArn": str,
         "AppInstanceUsers": List[AppInstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAppInstancesResponseTypeDef = TypedDict(
-    "ListAppInstancesResponseTypeDef",
+AppInstanceUserTypeDef = TypedDict(
+    "AppInstanceUserTypeDef",
     {
-        "AppInstances": List[AppInstanceSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceUserArn": str,
+        "Name": str,
+        "Metadata": str,
+        "CreatedTimestamp": datetime,
+        "LastUpdatedTimestamp": datetime,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
+    total=False,
 )
 
-RegisterAppInstanceUserEndpointResponseTypeDef = TypedDict(
-    "RegisterAppInstanceUserEndpointResponseTypeDef",
+_RequiredPutAppInstanceUserExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredPutAppInstanceUserExpirationSettingsRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
-        "EndpointId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-UpdateAppInstanceResponseTypeDef = TypedDict(
-    "UpdateAppInstanceResponseTypeDef",
+_OptionalPutAppInstanceUserExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalPutAppInstanceUserExpirationSettingsRequestRequestTypeDef",
     {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
+    total=False,
 )
 
-UpdateAppInstanceUserEndpointResponseTypeDef = TypedDict(
-    "UpdateAppInstanceUserEndpointResponseTypeDef",
-    {
-        "AppInstanceUserArn": str,
-        "EndpointId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateAppInstanceUserResponseTypeDef = TypedDict(
-    "UpdateAppInstanceUserResponseTypeDef",
+class PutAppInstanceUserExpirationSettingsRequestRequestTypeDef(
+    _RequiredPutAppInstanceUserExpirationSettingsRequestRequestTypeDef,
+    _OptionalPutAppInstanceUserExpirationSettingsRequestRequestTypeDef,
+):
+    pass
+
+
+PutAppInstanceUserExpirationSettingsResponseTypeDef = TypedDict(
+    "PutAppInstanceUserExpirationSettingsResponseTypeDef",
     {
         "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAppInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppInstanceRequestRequestTypeDef",
     {
         "Name": str,
@@ -636,14 +772,15 @@
     },
 )
 _OptionalCreateAppInstanceUserRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAppInstanceUserRequestRequestTypeDef",
     {
         "Metadata": str,
         "Tags": Sequence[TagTypeDef],
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
     total=False,
 )
 
 
 class CreateAppInstanceUserRequestRequestTypeDef(
     _RequiredCreateAppInstanceUserRequestRequestTypeDef,
@@ -652,50 +789,72 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+_RequiredLexConfigurationTypeDef = TypedDict(
+    "_RequiredLexConfigurationTypeDef",
+    {
+        "LexBotAliasArn": str,
+        "LocaleId": str,
+    },
+)
+_OptionalLexConfigurationTypeDef = TypedDict(
+    "_OptionalLexConfigurationTypeDef",
+    {
+        "RespondsTo": Literal["STANDARD_MESSAGES"],
+        "InvokedBy": InvokedByTypeDef,
+        "WelcomeIntent": str,
+    },
+    total=False,
+)
+
+
+class LexConfigurationTypeDef(_RequiredLexConfigurationTypeDef, _OptionalLexConfigurationTypeDef):
+    pass
+
+
 ListAppInstanceAdminsResponseTypeDef = TypedDict(
     "ListAppInstanceAdminsResponseTypeDef",
     {
         "AppInstanceArn": str,
         "AppInstanceAdmins": List[AppInstanceAdminSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppInstanceAdminResponseTypeDef = TypedDict(
     "DescribeAppInstanceAdminResponseTypeDef",
     {
         "AppInstanceAdmin": AppInstanceAdminTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "GetAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppInstanceRetentionSettingsRequestRequestTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
@@ -704,27 +863,113 @@
 )
 
 PutAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInstanceUserEndpointsResponseTypeDef = TypedDict(
     "ListAppInstanceUserEndpointsResponseTypeDef",
     {
         "AppInstanceUserEndpoints": List[AppInstanceUserEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppInstanceUserEndpointResponseTypeDef = TypedDict(
     "DescribeAppInstanceUserEndpointResponseTypeDef",
     {
         "AppInstanceUserEndpoint": AppInstanceUserEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAppInstanceUserResponseTypeDef = TypedDict(
+    "DescribeAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUser": AppInstanceUserTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ConfigurationTypeDef = TypedDict(
+    "ConfigurationTypeDef",
+    {
+        "Lex": LexConfigurationTypeDef,
+    },
+)
+
+AppInstanceBotTypeDef = TypedDict(
+    "AppInstanceBotTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "Name": str,
+        "Configuration": ConfigurationTypeDef,
+        "CreatedTimestamp": datetime,
+        "LastUpdatedTimestamp": datetime,
+        "Metadata": str,
+    },
+    total=False,
+)
+
+_RequiredCreateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ClientRequestToken": str,
+        "Configuration": ConfigurationTypeDef,
+    },
+)
+_OptionalCreateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateAppInstanceBotRequestRequestTypeDef",
+    {
+        "Name": str,
+        "Metadata": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreateAppInstanceBotRequestRequestTypeDef(
+    _RequiredCreateAppInstanceBotRequestRequestTypeDef,
+    _OptionalCreateAppInstanceBotRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredUpdateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "Name": str,
+        "Metadata": str,
+    },
+)
+_OptionalUpdateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateAppInstanceBotRequestRequestTypeDef",
+    {
+        "Configuration": ConfigurationTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateAppInstanceBotRequestRequestTypeDef(
+    _RequiredUpdateAppInstanceBotRequestRequestTypeDef,
+    _OptionalUpdateAppInstanceBotRequestRequestTypeDef,
+):
+    pass
+
+
+DescribeAppInstanceBotResponseTypeDef = TypedDict(
+    "DescribeAppInstanceBotResponseTypeDef",
+    {
+        "AppInstanceBot": AppInstanceBotTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity/type_defs.pyi` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity/type_defs.pyi`

 * *Files 16% similar despite different names*

```diff
@@ -16,91 +16,124 @@
 from typing import Dict, List, Sequence
 
 from .literals import (
     AllowMessagesType,
     AppInstanceUserEndpointTypeType,
     EndpointStatusReasonType,
     EndpointStatusType,
+    StandardMessagesType,
+    TargetedMessagesType,
 )
 
 if sys.version_info >= (3, 9):
+    from typing import Literal
+else:
+    from typing_extensions import Literal
+if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "IdentityTypeDef",
+    "AppInstanceBotSummaryTypeDef",
     "ChannelRetentionSettingsTypeDef",
     "AppInstanceSummaryTypeDef",
     "AppInstanceTypeDef",
     "EndpointStateTypeDef",
     "EndpointAttributesTypeDef",
     "AppInstanceUserSummaryTypeDef",
-    "AppInstanceUserTypeDef",
+    "ExpirationSettingsTypeDef",
     "CreateAppInstanceAdminRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "TagTypeDef",
+    "CreateAppInstanceBotResponseTypeDef",
+    "CreateAppInstanceResponseTypeDef",
+    "CreateAppInstanceUserResponseTypeDef",
     "DeleteAppInstanceAdminRequestRequestTypeDef",
+    "DeleteAppInstanceBotRequestRequestTypeDef",
     "DeleteAppInstanceRequestRequestTypeDef",
     "DeleteAppInstanceUserRequestRequestTypeDef",
     "DeregisterAppInstanceUserEndpointRequestRequestTypeDef",
     "DescribeAppInstanceAdminRequestRequestTypeDef",
+    "DescribeAppInstanceBotRequestRequestTypeDef",
     "DescribeAppInstanceRequestRequestTypeDef",
     "DescribeAppInstanceUserEndpointRequestRequestTypeDef",
     "DescribeAppInstanceUserRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetAppInstanceRetentionSettingsRequestRequestTypeDef",
+    "InvokedByTypeDef",
     "ListAppInstanceAdminsRequestRequestTypeDef",
+    "ListAppInstanceBotsRequestRequestTypeDef",
     "ListAppInstanceUserEndpointsRequestRequestTypeDef",
     "ListAppInstanceUsersRequestRequestTypeDef",
     "ListAppInstancesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "RegisterAppInstanceUserEndpointResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAppInstanceBotResponseTypeDef",
     "UpdateAppInstanceRequestRequestTypeDef",
+    "UpdateAppInstanceResponseTypeDef",
     "UpdateAppInstanceUserEndpointRequestRequestTypeDef",
+    "UpdateAppInstanceUserEndpointResponseTypeDef",
     "UpdateAppInstanceUserRequestRequestTypeDef",
+    "UpdateAppInstanceUserResponseTypeDef",
     "AppInstanceAdminSummaryTypeDef",
     "AppInstanceAdminTypeDef",
+    "CreateAppInstanceAdminResponseTypeDef",
+    "ListAppInstanceBotsResponseTypeDef",
     "AppInstanceRetentionSettingsTypeDef",
+    "ListAppInstancesResponseTypeDef",
+    "DescribeAppInstanceResponseTypeDef",
     "AppInstanceUserEndpointSummaryTypeDef",
     "AppInstanceUserEndpointTypeDef",
     "RegisterAppInstanceUserEndpointRequestRequestTypeDef",
-    "CreateAppInstanceAdminResponseTypeDef",
-    "CreateAppInstanceResponseTypeDef",
-    "CreateAppInstanceUserResponseTypeDef",
-    "DescribeAppInstanceResponseTypeDef",
-    "DescribeAppInstanceUserResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListAppInstanceUsersResponseTypeDef",
-    "ListAppInstancesResponseTypeDef",
-    "RegisterAppInstanceUserEndpointResponseTypeDef",
-    "UpdateAppInstanceResponseTypeDef",
-    "UpdateAppInstanceUserEndpointResponseTypeDef",
-    "UpdateAppInstanceUserResponseTypeDef",
+    "AppInstanceUserTypeDef",
+    "PutAppInstanceUserExpirationSettingsRequestRequestTypeDef",
+    "PutAppInstanceUserExpirationSettingsResponseTypeDef",
     "CreateAppInstanceRequestRequestTypeDef",
     "CreateAppInstanceUserRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "LexConfigurationTypeDef",
     "ListAppInstanceAdminsResponseTypeDef",
     "DescribeAppInstanceAdminResponseTypeDef",
     "GetAppInstanceRetentionSettingsResponseTypeDef",
     "PutAppInstanceRetentionSettingsRequestRequestTypeDef",
     "PutAppInstanceRetentionSettingsResponseTypeDef",
     "ListAppInstanceUserEndpointsResponseTypeDef",
     "DescribeAppInstanceUserEndpointResponseTypeDef",
+    "DescribeAppInstanceUserResponseTypeDef",
+    "ConfigurationTypeDef",
+    "AppInstanceBotTypeDef",
+    "CreateAppInstanceBotRequestRequestTypeDef",
+    "UpdateAppInstanceBotRequestRequestTypeDef",
+    "DescribeAppInstanceBotResponseTypeDef",
 )
 
 IdentityTypeDef = TypedDict(
     "IdentityTypeDef",
     {
         "Arn": str,
         "Name": str,
     },
     total=False,
 )
 
+AppInstanceBotSummaryTypeDef = TypedDict(
+    "AppInstanceBotSummaryTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "Name": str,
+        "Metadata": str,
+    },
+    total=False,
+)
+
 ChannelRetentionSettingsTypeDef = TypedDict(
     "ChannelRetentionSettingsTypeDef",
     {
         "RetentionDays": int,
     },
     total=False,
 )
@@ -169,61 +202,77 @@
         "AppInstanceUserArn": str,
         "Name": str,
         "Metadata": str,
     },
     total=False,
 )
 
-AppInstanceUserTypeDef = TypedDict(
-    "AppInstanceUserTypeDef",
+ExpirationSettingsTypeDef = TypedDict(
+    "ExpirationSettingsTypeDef",
     {
-        "AppInstanceUserArn": str,
-        "Name": str,
-        "Metadata": str,
-        "CreatedTimestamp": datetime,
-        "LastUpdatedTimestamp": datetime,
+        "ExpirationDays": int,
+        "ExpirationCriterion": Literal["CREATED_TIMESTAMP"],
     },
-    total=False,
 )
 
 CreateAppInstanceAdminRequestRequestTypeDef = TypedDict(
     "CreateAppInstanceAdminRequestRequestTypeDef",
     {
         "AppInstanceAdminArn": str,
         "AppInstanceArn": str,
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateAppInstanceBotResponseTypeDef = TypedDict(
+    "CreateAppInstanceBotResponseTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAppInstanceResponseTypeDef = TypedDict(
+    "CreateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAppInstanceUserResponseTypeDef = TypedDict(
+    "CreateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAppInstanceAdminRequestRequestTypeDef = TypedDict(
     "DeleteAppInstanceAdminRequestRequestTypeDef",
     {
         "AppInstanceAdminArn": str,
         "AppInstanceArn": str,
     },
 )
 
+DeleteAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "DeleteAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceBotArn": str,
+    },
+)
+
 DeleteAppInstanceRequestRequestTypeDef = TypedDict(
     "DeleteAppInstanceRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 
@@ -246,14 +295,21 @@
     "DescribeAppInstanceAdminRequestRequestTypeDef",
     {
         "AppInstanceAdminArn": str,
         "AppInstanceArn": str,
     },
 )
 
+DescribeAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "DescribeAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceBotArn": str,
+    },
+)
+
 DescribeAppInstanceRequestRequestTypeDef = TypedDict(
     "DescribeAppInstanceRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 
@@ -268,21 +324,36 @@
 DescribeAppInstanceUserRequestRequestTypeDef = TypedDict(
     "DescribeAppInstanceUserRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAppInstanceRetentionSettingsRequestRequestTypeDef = TypedDict(
     "GetAppInstanceRetentionSettingsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 
+InvokedByTypeDef = TypedDict(
+    "InvokedByTypeDef",
+    {
+        "StandardMessages": StandardMessagesType,
+        "TargetedMessages": TargetedMessagesType,
+    },
+)
+
 _RequiredListAppInstanceAdminsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppInstanceAdminsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
     },
 )
 _OptionalListAppInstanceAdminsRequestRequestTypeDef = TypedDict(
@@ -296,14 +367,35 @@
 
 class ListAppInstanceAdminsRequestRequestTypeDef(
     _RequiredListAppInstanceAdminsRequestRequestTypeDef,
     _OptionalListAppInstanceAdminsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListAppInstanceBotsRequestRequestTypeDef = TypedDict(
+    "_RequiredListAppInstanceBotsRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+    },
+)
+_OptionalListAppInstanceBotsRequestRequestTypeDef = TypedDict(
+    "_OptionalListAppInstanceBotsRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+class ListAppInstanceBotsRequestRequestTypeDef(
+    _RequiredListAppInstanceBotsRequestRequestTypeDef,
+    _OptionalListAppInstanceBotsRequestRequestTypeDef,
+):
+    pass
+
 _RequiredListAppInstanceUserEndpointsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppInstanceUserEndpointsRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
     },
 )
 _OptionalListAppInstanceUserEndpointsRequestRequestTypeDef = TypedDict(
@@ -354,31 +446,67 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+RegisterAppInstanceUserEndpointResponseTypeDef = TypedDict(
+    "RegisterAppInstanceUserEndpointResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "EndpointId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateAppInstanceBotResponseTypeDef = TypedDict(
+    "UpdateAppInstanceBotResponseTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAppInstanceRequestRequestTypeDef = TypedDict(
     "UpdateAppInstanceRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
         "Name": str,
         "Metadata": str,
     },
 )
 
+UpdateAppInstanceResponseTypeDef = TypedDict(
+    "UpdateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateAppInstanceUserEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAppInstanceUserEndpointRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
         "EndpointId": str,
     },
 )
@@ -393,23 +521,40 @@
 
 class UpdateAppInstanceUserEndpointRequestRequestTypeDef(
     _RequiredUpdateAppInstanceUserEndpointRequestRequestTypeDef,
     _OptionalUpdateAppInstanceUserEndpointRequestRequestTypeDef,
 ):
     pass
 
+UpdateAppInstanceUserEndpointResponseTypeDef = TypedDict(
+    "UpdateAppInstanceUserEndpointResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "EndpointId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAppInstanceUserRequestRequestTypeDef = TypedDict(
     "UpdateAppInstanceUserRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
         "Name": str,
         "Metadata": str,
     },
 )
 
+UpdateAppInstanceUserResponseTypeDef = TypedDict(
+    "UpdateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppInstanceAdminSummaryTypeDef = TypedDict(
     "AppInstanceAdminSummaryTypeDef",
     {
         "Admin": IdentityTypeDef,
     },
     total=False,
 )
@@ -420,22 +565,58 @@
         "Admin": IdentityTypeDef,
         "AppInstanceArn": str,
         "CreatedTimestamp": datetime,
     },
     total=False,
 )
 
+CreateAppInstanceAdminResponseTypeDef = TypedDict(
+    "CreateAppInstanceAdminResponseTypeDef",
+    {
+        "AppInstanceAdmin": IdentityTypeDef,
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAppInstanceBotsResponseTypeDef = TypedDict(
+    "ListAppInstanceBotsResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "AppInstanceBots": List[AppInstanceBotSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppInstanceRetentionSettingsTypeDef = TypedDict(
     "AppInstanceRetentionSettingsTypeDef",
     {
         "ChannelRetentionSettings": ChannelRetentionSettingsTypeDef,
     },
     total=False,
 )
 
+ListAppInstancesResponseTypeDef = TypedDict(
+    "ListAppInstancesResponseTypeDef",
+    {
+        "AppInstances": List[AppInstanceSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAppInstanceResponseTypeDef = TypedDict(
+    "DescribeAppInstanceResponseTypeDef",
+    {
+        "AppInstance": AppInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppInstanceUserEndpointSummaryTypeDef = TypedDict(
     "AppInstanceUserEndpointSummaryTypeDef",
     {
         "AppInstanceUserArn": str,
         "EndpointId": str,
         "Name": str,
         "Type": AppInstanceUserEndpointTypeType,
@@ -483,112 +664,63 @@
 
 class RegisterAppInstanceUserEndpointRequestRequestTypeDef(
     _RequiredRegisterAppInstanceUserEndpointRequestRequestTypeDef,
     _OptionalRegisterAppInstanceUserEndpointRequestRequestTypeDef,
 ):
     pass
 
-CreateAppInstanceAdminResponseTypeDef = TypedDict(
-    "CreateAppInstanceAdminResponseTypeDef",
-    {
-        "AppInstanceAdmin": IdentityTypeDef,
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceResponseTypeDef = TypedDict(
-    "CreateAppInstanceResponseTypeDef",
-    {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceUserResponseTypeDef = TypedDict(
-    "CreateAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceResponseTypeDef = TypedDict(
-    "DescribeAppInstanceResponseTypeDef",
-    {
-        "AppInstance": AppInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceUserResponseTypeDef = TypedDict(
-    "DescribeAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUser": AppInstanceUserTypeDef,
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
 ListAppInstanceUsersResponseTypeDef = TypedDict(
     "ListAppInstanceUsersResponseTypeDef",
     {
         "AppInstanceArn": str,
         "AppInstanceUsers": List[AppInstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAppInstancesResponseTypeDef = TypedDict(
-    "ListAppInstancesResponseTypeDef",
+AppInstanceUserTypeDef = TypedDict(
+    "AppInstanceUserTypeDef",
     {
-        "AppInstances": List[AppInstanceSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceUserArn": str,
+        "Name": str,
+        "Metadata": str,
+        "CreatedTimestamp": datetime,
+        "LastUpdatedTimestamp": datetime,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
+    total=False,
 )
 
-RegisterAppInstanceUserEndpointResponseTypeDef = TypedDict(
-    "RegisterAppInstanceUserEndpointResponseTypeDef",
+_RequiredPutAppInstanceUserExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredPutAppInstanceUserExpirationSettingsRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
-        "EndpointId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-UpdateAppInstanceResponseTypeDef = TypedDict(
-    "UpdateAppInstanceResponseTypeDef",
+_OptionalPutAppInstanceUserExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalPutAppInstanceUserExpirationSettingsRequestRequestTypeDef",
     {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
+    total=False,
 )
 
-UpdateAppInstanceUserEndpointResponseTypeDef = TypedDict(
-    "UpdateAppInstanceUserEndpointResponseTypeDef",
-    {
-        "AppInstanceUserArn": str,
-        "EndpointId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class PutAppInstanceUserExpirationSettingsRequestRequestTypeDef(
+    _RequiredPutAppInstanceUserExpirationSettingsRequestRequestTypeDef,
+    _OptionalPutAppInstanceUserExpirationSettingsRequestRequestTypeDef,
+):
+    pass
 
-UpdateAppInstanceUserResponseTypeDef = TypedDict(
-    "UpdateAppInstanceUserResponseTypeDef",
+PutAppInstanceUserExpirationSettingsResponseTypeDef = TypedDict(
+    "PutAppInstanceUserExpirationSettingsResponseTypeDef",
     {
         "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAppInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppInstanceRequestRequestTypeDef",
     {
         "Name": str,
@@ -619,64 +751,85 @@
     },
 )
 _OptionalCreateAppInstanceUserRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAppInstanceUserRequestRequestTypeDef",
     {
         "Metadata": str,
         "Tags": Sequence[TagTypeDef],
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
     total=False,
 )
 
 class CreateAppInstanceUserRequestRequestTypeDef(
     _RequiredCreateAppInstanceUserRequestRequestTypeDef,
     _OptionalCreateAppInstanceUserRequestRequestTypeDef,
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+_RequiredLexConfigurationTypeDef = TypedDict(
+    "_RequiredLexConfigurationTypeDef",
+    {
+        "LexBotAliasArn": str,
+        "LocaleId": str,
+    },
+)
+_OptionalLexConfigurationTypeDef = TypedDict(
+    "_OptionalLexConfigurationTypeDef",
+    {
+        "RespondsTo": Literal["STANDARD_MESSAGES"],
+        "InvokedBy": InvokedByTypeDef,
+        "WelcomeIntent": str,
+    },
+    total=False,
+)
+
+class LexConfigurationTypeDef(_RequiredLexConfigurationTypeDef, _OptionalLexConfigurationTypeDef):
+    pass
+
 ListAppInstanceAdminsResponseTypeDef = TypedDict(
     "ListAppInstanceAdminsResponseTypeDef",
     {
         "AppInstanceArn": str,
         "AppInstanceAdmins": List[AppInstanceAdminSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppInstanceAdminResponseTypeDef = TypedDict(
     "DescribeAppInstanceAdminResponseTypeDef",
     {
         "AppInstanceAdmin": AppInstanceAdminTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "GetAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppInstanceRetentionSettingsRequestRequestTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
@@ -685,27 +838,109 @@
 )
 
 PutAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInstanceUserEndpointsResponseTypeDef = TypedDict(
     "ListAppInstanceUserEndpointsResponseTypeDef",
     {
         "AppInstanceUserEndpoints": List[AppInstanceUserEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppInstanceUserEndpointResponseTypeDef = TypedDict(
     "DescribeAppInstanceUserEndpointResponseTypeDef",
     {
         "AppInstanceUserEndpoint": AppInstanceUserEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAppInstanceUserResponseTypeDef = TypedDict(
+    "DescribeAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUser": AppInstanceUserTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ConfigurationTypeDef = TypedDict(
+    "ConfigurationTypeDef",
+    {
+        "Lex": LexConfigurationTypeDef,
+    },
+)
+
+AppInstanceBotTypeDef = TypedDict(
+    "AppInstanceBotTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "Name": str,
+        "Configuration": ConfigurationTypeDef,
+        "CreatedTimestamp": datetime,
+        "LastUpdatedTimestamp": datetime,
+        "Metadata": str,
+    },
+    total=False,
+)
+
+_RequiredCreateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ClientRequestToken": str,
+        "Configuration": ConfigurationTypeDef,
+    },
+)
+_OptionalCreateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateAppInstanceBotRequestRequestTypeDef",
+    {
+        "Name": str,
+        "Metadata": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreateAppInstanceBotRequestRequestTypeDef(
+    _RequiredCreateAppInstanceBotRequestRequestTypeDef,
+    _OptionalCreateAppInstanceBotRequestRequestTypeDef,
+):
+    pass
+
+_RequiredUpdateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateAppInstanceBotRequestRequestTypeDef",
+    {
+        "AppInstanceBotArn": str,
+        "Name": str,
+        "Metadata": str,
+    },
+)
+_OptionalUpdateAppInstanceBotRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateAppInstanceBotRequestRequestTypeDef",
+    {
+        "Configuration": ConfigurationTypeDef,
+    },
+    total=False,
+)
+
+class UpdateAppInstanceBotRequestRequestTypeDef(
+    _RequiredUpdateAppInstanceBotRequestRequestTypeDef,
+    _OptionalUpdateAppInstanceBotRequestRequestTypeDef,
+):
+    pass
+
+DescribeAppInstanceBotResponseTypeDef = TypedDict(
+    "DescribeAppInstanceBotResponseTypeDef",
+    {
+        "AppInstanceBot": AppInstanceBotTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/PKG-INFO` & `types-aiobotocore-chime-sdk-identity-2.5.1/README.md`

 * *Files 19% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-chime-sdk-identity
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ChimeSDKIdentity 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore chime-sdk-identity type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-chime-sdk-identity"></a>
 
 # types-aiobotocore-chime-sdk-identity
 
 [![PyPI - types-aiobotocore-chime-sdk-identity](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-identity)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-identity.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-identity)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-identity?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-identity)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKIdentity 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity)
+[aiobotocore.ChimeSDKIdentity 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-identity.html#ChimeSDKIdentity)
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
 [types-aiobotocore-chime-sdk-identity docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_identity/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,14 +240,18 @@
 
 ```python
 from types_aiobotocore_chime_sdk_identity.literals import (
     AllowMessagesType,
     AppInstanceUserEndpointTypeType,
     EndpointStatusReasonType,
     EndpointStatusType,
+    ExpirationCriterionType,
+    RespondsToType,
+    StandardMessagesType,
+    TargetedMessagesType,
     ChimeSDKIdentityServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
@@ -294,114 +265,131 @@
 
 `types_aiobotocore_chime_sdk_identity.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_chime_sdk_identity.type_defs import (
     IdentityTypeDef,
+    AppInstanceBotSummaryTypeDef,
     ChannelRetentionSettingsTypeDef,
     AppInstanceSummaryTypeDef,
     AppInstanceTypeDef,
     EndpointStateTypeDef,
     EndpointAttributesTypeDef,
     AppInstanceUserSummaryTypeDef,
-    AppInstanceUserTypeDef,
+    ExpirationSettingsTypeDef,
     CreateAppInstanceAdminRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     TagTypeDef,
+    CreateAppInstanceBotResponseTypeDef,
+    CreateAppInstanceResponseTypeDef,
+    CreateAppInstanceUserResponseTypeDef,
     DeleteAppInstanceAdminRequestRequestTypeDef,
+    DeleteAppInstanceBotRequestRequestTypeDef,
     DeleteAppInstanceRequestRequestTypeDef,
     DeleteAppInstanceUserRequestRequestTypeDef,
     DeregisterAppInstanceUserEndpointRequestRequestTypeDef,
     DescribeAppInstanceAdminRequestRequestTypeDef,
+    DescribeAppInstanceBotRequestRequestTypeDef,
     DescribeAppInstanceRequestRequestTypeDef,
     DescribeAppInstanceUserEndpointRequestRequestTypeDef,
     DescribeAppInstanceUserRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetAppInstanceRetentionSettingsRequestRequestTypeDef,
+    InvokedByTypeDef,
     ListAppInstanceAdminsRequestRequestTypeDef,
+    ListAppInstanceBotsRequestRequestTypeDef,
     ListAppInstanceUserEndpointsRequestRequestTypeDef,
     ListAppInstanceUsersRequestRequestTypeDef,
     ListAppInstancesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    RegisterAppInstanceUserEndpointResponseTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAppInstanceBotResponseTypeDef,
     UpdateAppInstanceRequestRequestTypeDef,
+    UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserEndpointRequestRequestTypeDef,
+    UpdateAppInstanceUserEndpointResponseTypeDef,
     UpdateAppInstanceUserRequestRequestTypeDef,
+    UpdateAppInstanceUserResponseTypeDef,
     AppInstanceAdminSummaryTypeDef,
     AppInstanceAdminTypeDef,
+    CreateAppInstanceAdminResponseTypeDef,
+    ListAppInstanceBotsResponseTypeDef,
     AppInstanceRetentionSettingsTypeDef,
+    ListAppInstancesResponseTypeDef,
+    DescribeAppInstanceResponseTypeDef,
     AppInstanceUserEndpointSummaryTypeDef,
     AppInstanceUserEndpointTypeDef,
     RegisterAppInstanceUserEndpointRequestRequestTypeDef,
-    CreateAppInstanceAdminResponseTypeDef,
-    CreateAppInstanceResponseTypeDef,
-    CreateAppInstanceUserResponseTypeDef,
-    DescribeAppInstanceResponseTypeDef,
-    DescribeAppInstanceUserResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListAppInstanceUsersResponseTypeDef,
-    ListAppInstancesResponseTypeDef,
-    RegisterAppInstanceUserEndpointResponseTypeDef,
-    UpdateAppInstanceResponseTypeDef,
-    UpdateAppInstanceUserEndpointResponseTypeDef,
-    UpdateAppInstanceUserResponseTypeDef,
+    AppInstanceUserTypeDef,
+    PutAppInstanceUserExpirationSettingsRequestRequestTypeDef,
+    PutAppInstanceUserExpirationSettingsResponseTypeDef,
     CreateAppInstanceRequestRequestTypeDef,
     CreateAppInstanceUserRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    LexConfigurationTypeDef,
     ListAppInstanceAdminsResponseTypeDef,
     DescribeAppInstanceAdminResponseTypeDef,
     GetAppInstanceRetentionSettingsResponseTypeDef,
     PutAppInstanceRetentionSettingsRequestRequestTypeDef,
     PutAppInstanceRetentionSettingsResponseTypeDef,
     ListAppInstanceUserEndpointsResponseTypeDef,
     DescribeAppInstanceUserEndpointResponseTypeDef,
+    DescribeAppInstanceUserResponseTypeDef,
+    ConfigurationTypeDef,
+    AppInstanceBotTypeDef,
+    CreateAppInstanceBotRequestRequestTypeDef,
+    UpdateAppInstanceBotRequestRequestTypeDef,
+    DescribeAppInstanceBotResponseTypeDef,
 )
 
 
 def get_structure() -> IdentityTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-chime-sdk-identity-2.5.0.post1/types_aiobotocore_chime_sdk_identity.egg-info/SOURCES.txt` & `types-aiobotocore-chime-sdk-identity-2.5.1/types_aiobotocore_chime_sdk_identity.egg-info/SOURCES.txt`

 * *Files identical despite different names*

