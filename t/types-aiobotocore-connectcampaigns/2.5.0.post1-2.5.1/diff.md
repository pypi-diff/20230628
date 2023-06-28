# Comparing `tmp/types-aiobotocore-connectcampaigns-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-connectcampaigns-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-connectcampaigns-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-connectcampaigns-2.5.1.tar", last modified: Wed Jun 28 01:43:20 2023, max compression
```

## Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1.tar` & `types-aiobotocore-connectcampaigns-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.119096 types-aiobotocore-connectcampaigns-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:58.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15674 2023-03-11 12:26:27.119096 types-aiobotocore-connectcampaigns-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14061 2023-03-11 12:11:58.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:27.119096 types-aiobotocore-connectcampaigns-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2193 2023-03-11 12:11:58.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.119096 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/
--rw-r--r--   0 runner    (1001) docker     (123)      743 2023-03-11 12:11:58.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      742 2023-03-11 12:11:58.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      991 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18370 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18338 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8521 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8519 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2315 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2311 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    15066 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    15053 2023-03-11 12:11:59.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:58.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:27.119096 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15674 2023-03-11 12:26:26.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:26:26.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:26.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:26.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:26.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:26.000000 types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.206119 types-aiobotocore-connectcampaigns-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15675 2023-06-28 01:43:20.206119 types-aiobotocore-connectcampaigns-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14068 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:20.206119 types-aiobotocore-connectcampaigns-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.206119 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/
+-rw-r--r--   0 runner    (1001) docker     (123)      743 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      742 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      979 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18370 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18338 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8730 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8728 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2197 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2194 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    15090 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15077 2023-06-28 01:28:38.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:37.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.206119 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15675 2023-06-28 01:43:20.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:20.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:20.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:20.000000 types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/LICENSE` & `types-aiobotocore-connectcampaigns-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/PKG-INFO` & `types-aiobotocore-connectcampaigns-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-connectcampaigns
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectCampaignService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectCampaignService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-connectcampaigns"></a>
 
 # types-aiobotocore-connectcampaigns
 
 [![PyPI - types-aiobotocore-connectcampaigns](https://img.shields.io/pypi/v/types-aiobotocore-connectcampaigns.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcampaigns)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectcampaigns.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcampaigns)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectcampaigns?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectcampaigns)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectCampaignService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService)
+[aiobotocore.ConnectCampaignService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService)
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
 [types-aiobotocore-connectcampaigns docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/).
 
 See how it helps to find and fix potential bugs:
 
@@ -324,49 +324,49 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_connectcampaigns.type_defs import (
     AnswerMachineDetectionConfigTypeDef,
     InstanceIdFilterTypeDef,
     CampaignSummaryTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCampaignResponseTypeDef,
     DeleteCampaignRequestRequestTypeDef,
     DeleteConnectInstanceConfigRequestRequestTypeDef,
     DeleteInstanceOnboardingJobRequestRequestTypeDef,
     DescribeCampaignRequestRequestTypeDef,
     DialRequestTypeDef,
     PredictiveDialerConfigTypeDef,
     ProgressiveDialerConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionConfigTypeDef,
     FailedCampaignStateResponseTypeDef,
     FailedRequestTypeDef,
     GetCampaignStateBatchRequestRequestTypeDef,
     SuccessfulCampaignStateResponseTypeDef,
     GetCampaignStateRequestRequestTypeDef,
+    GetCampaignStateResponseTypeDef,
     GetConnectInstanceConfigRequestRequestTypeDef,
     GetInstanceOnboardingJobStatusRequestRequestTypeDef,
     InstanceOnboardingJobStatusTypeDef,
-    PaginatorConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PauseCampaignRequestRequestTypeDef,
     SuccessfulRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResumeCampaignRequestRequestTypeDef,
     StartCampaignRequestRequestTypeDef,
     StopCampaignRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCampaignNameRequestRequestTypeDef,
     OutboundCallConfigTypeDef,
     UpdateCampaignOutboundCallConfigRequestRequestTypeDef,
     CampaignFiltersTypeDef,
-    CreateCampaignResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCampaignStateResponseTypeDef,
     ListCampaignsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     PutDialRequestBatchRequestRequestTypeDef,
     DialerConfigTypeDef,
     InstanceConfigTypeDef,
     StartInstanceOnboardingJobRequestRequestTypeDef,
     GetCampaignStateBatchResponseTypeDef,
     GetInstanceOnboardingJobStatusResponseTypeDef,
     StartInstanceOnboardingJobResponseTypeDef,
@@ -388,43 +388,43 @@
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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/README.md` & `types-aiobotocore-connectcampaigns-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-connectcampaigns"></a>
 
 # types-aiobotocore-connectcampaigns
 
 [![PyPI - types-aiobotocore-connectcampaigns](https://img.shields.io/pypi/v/types-aiobotocore-connectcampaigns.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcampaigns)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectcampaigns.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcampaigns)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectcampaigns?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectcampaigns)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectCampaignService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService)
+[aiobotocore.ConnectCampaignService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService)
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
 [types-aiobotocore-connectcampaigns docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,49 +291,49 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_connectcampaigns.type_defs import (
     AnswerMachineDetectionConfigTypeDef,
     InstanceIdFilterTypeDef,
     CampaignSummaryTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCampaignResponseTypeDef,
     DeleteCampaignRequestRequestTypeDef,
     DeleteConnectInstanceConfigRequestRequestTypeDef,
     DeleteInstanceOnboardingJobRequestRequestTypeDef,
     DescribeCampaignRequestRequestTypeDef,
     DialRequestTypeDef,
     PredictiveDialerConfigTypeDef,
     ProgressiveDialerConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionConfigTypeDef,
     FailedCampaignStateResponseTypeDef,
     FailedRequestTypeDef,
     GetCampaignStateBatchRequestRequestTypeDef,
     SuccessfulCampaignStateResponseTypeDef,
     GetCampaignStateRequestRequestTypeDef,
+    GetCampaignStateResponseTypeDef,
     GetConnectInstanceConfigRequestRequestTypeDef,
     GetInstanceOnboardingJobStatusRequestRequestTypeDef,
     InstanceOnboardingJobStatusTypeDef,
-    PaginatorConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PauseCampaignRequestRequestTypeDef,
     SuccessfulRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResumeCampaignRequestRequestTypeDef,
     StartCampaignRequestRequestTypeDef,
     StopCampaignRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCampaignNameRequestRequestTypeDef,
     OutboundCallConfigTypeDef,
     UpdateCampaignOutboundCallConfigRequestRequestTypeDef,
     CampaignFiltersTypeDef,
-    CreateCampaignResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCampaignStateResponseTypeDef,
     ListCampaignsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     PutDialRequestBatchRequestRequestTypeDef,
     DialerConfigTypeDef,
     InstanceConfigTypeDef,
     StartInstanceOnboardingJobRequestRequestTypeDef,
     GetCampaignStateBatchResponseTypeDef,
     GetInstanceOnboardingJobStatusResponseTypeDef,
     StartInstanceOnboardingJobResponseTypeDef,
@@ -355,43 +355,43 @@
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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/setup.py` & `types-aiobotocore-connectcampaigns-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-connectcampaigns.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-connectcampaigns",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_connectcampaigns"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ConnectCampaignService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ConnectCampaignService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/"
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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/__init__.py` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/__init__.pyi` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/__main__.py` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ConnectCampaignService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ConnectCampaignService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService\nOther"
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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/client.py` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/client.pyi` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/literals.py` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/literals.py`

 * *Files 0% similar despite different names*

```diff
@@ -110,14 +110,15 @@
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
@@ -196,14 +197,15 @@
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
@@ -214,14 +216,15 @@
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
@@ -257,14 +260,15 @@
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
@@ -283,16 +287,19 @@
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
@@ -376,15 +383,17 @@
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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/literals.pyi` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -108,14 +108,15 @@
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
@@ -194,14 +195,15 @@
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
@@ -212,14 +214,15 @@
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
@@ -255,14 +258,15 @@
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
@@ -281,16 +285,19 @@
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
@@ -374,15 +381,17 @@
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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/paginator.py` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -16,50 +16,40 @@
     session = get_session()
     with session.create_client("connectcampaigns") as client:
         client: ConnectCampaignServiceClient
 
         list_campaigns_paginator: ListCampaignsPaginator = client.get_paginator("list_campaigns")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import CampaignFiltersTypeDef, ListCampaignsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListCampaignsPaginator",)
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListCampaignsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService.Paginator.ListCampaigns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/paginators/#listcampaignspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: CampaignFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCampaignsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService.Paginator.ListCampaigns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/paginators/#listcampaignspaginator)
         """
```

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/paginator.pyi` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,46 +16,43 @@
     session = get_session()
     with session.create_client("connectcampaigns") as client:
         client: ConnectCampaignServiceClient
 
         list_campaigns_paginator: ListCampaignsPaginator = client.get_paginator("list_campaigns")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import CampaignFiltersTypeDef, ListCampaignsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListCampaignsPaginator",)
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListCampaignsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService.Paginator.ListCampaigns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/paginators/#listcampaignspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: CampaignFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCampaignsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService.Paginator.ListCampaigns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/paginators/#listcampaignspaginator)
         """
```

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/type_defs.py` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -28,54 +28,53 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AnswerMachineDetectionConfigTypeDef",
     "InstanceIdFilterTypeDef",
     "CampaignSummaryTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateCampaignResponseTypeDef",
     "DeleteCampaignRequestRequestTypeDef",
     "DeleteConnectInstanceConfigRequestRequestTypeDef",
     "DeleteInstanceOnboardingJobRequestRequestTypeDef",
     "DescribeCampaignRequestRequestTypeDef",
     "DialRequestTypeDef",
     "PredictiveDialerConfigTypeDef",
     "ProgressiveDialerConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionConfigTypeDef",
     "FailedCampaignStateResponseTypeDef",
     "FailedRequestTypeDef",
     "GetCampaignStateBatchRequestRequestTypeDef",
     "SuccessfulCampaignStateResponseTypeDef",
     "GetCampaignStateRequestRequestTypeDef",
+    "GetCampaignStateResponseTypeDef",
     "GetConnectInstanceConfigRequestRequestTypeDef",
     "GetInstanceOnboardingJobStatusRequestRequestTypeDef",
     "InstanceOnboardingJobStatusTypeDef",
-    "PaginatorConfigTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PauseCampaignRequestRequestTypeDef",
     "SuccessfulRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeCampaignRequestRequestTypeDef",
     "StartCampaignRequestRequestTypeDef",
     "StopCampaignRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCampaignNameRequestRequestTypeDef",
     "OutboundCallConfigTypeDef",
     "UpdateCampaignOutboundCallConfigRequestRequestTypeDef",
     "CampaignFiltersTypeDef",
-    "CreateCampaignResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCampaignStateResponseTypeDef",
     "ListCampaignsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "PutDialRequestBatchRequestRequestTypeDef",
     "DialerConfigTypeDef",
     "InstanceConfigTypeDef",
     "StartInstanceOnboardingJobRequestRequestTypeDef",
     "GetCampaignStateBatchResponseTypeDef",
     "GetInstanceOnboardingJobStatusResponseTypeDef",
     "StartInstanceOnboardingJobResponseTypeDef",
@@ -110,22 +109,21 @@
         "arn": str,
         "connectInstanceId": str,
         "id": str,
         "name": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateCampaignResponseTypeDef = TypedDict(
+    "CreateCampaignResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "id": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCampaignRequestRequestTypeDef = TypedDict(
     "DeleteCampaignRequestRequestTypeDef",
     {
         "id": str,
@@ -173,14 +171,21 @@
 ProgressiveDialerConfigTypeDef = TypedDict(
     "ProgressiveDialerConfigTypeDef",
     {
         "bandwidthAllocation": float,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEncryptionConfigTypeDef = TypedDict(
     "_RequiredEncryptionConfigTypeDef",
     {
         "enabled": bool,
     },
 )
 _OptionalEncryptionConfigTypeDef = TypedDict(
@@ -188,19 +193,17 @@
     {
         "encryptionType": Literal["KMS"],
         "keyArn": str,
     },
     total=False,
 )
 
-
 class EncryptionConfigTypeDef(_RequiredEncryptionConfigTypeDef, _OptionalEncryptionConfigTypeDef):
     pass
 
-
 FailedCampaignStateResponseTypeDef = TypedDict(
     "FailedCampaignStateResponseTypeDef",
     {
         "campaignId": str,
         "failureCode": GetCampaignStateBatchFailureCodeType,
     },
     total=False,
@@ -235,14 +238,22 @@
 GetCampaignStateRequestRequestTypeDef = TypedDict(
     "GetCampaignStateRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetCampaignStateResponseTypeDef = TypedDict(
+    "GetCampaignStateResponseTypeDef",
+    {
+        "state": CampaignStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetConnectInstanceConfigRequestRequestTypeDef = TypedDict(
     "GetConnectInstanceConfigRequestRequestTypeDef",
     {
         "connectInstanceId": str,
     },
 )
 
@@ -264,38 +275,44 @@
     "_OptionalInstanceOnboardingJobStatusTypeDef",
     {
         "failureCode": InstanceOnboardingJobFailureCodeType,
     },
     total=False,
 )
 
-
 class InstanceOnboardingJobStatusTypeDef(
     _RequiredInstanceOnboardingJobStatusTypeDef, _OptionalInstanceOnboardingJobStatusTypeDef
 ):
     pass
 
+ListTagsForResourceRequestRequestTypeDef = TypedDict(
+    "ListTagsForResourceRequestRequestTypeDef",
+    {
+        "arn": str,
+    },
+)
+
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 PaginatorConfigTypeDef = TypedDict(
     "PaginatorConfigTypeDef",
     {
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
     total=False,
 )
 
-ListTagsForResourceRequestRequestTypeDef = TypedDict(
-    "ListTagsForResourceRequestRequestTypeDef",
-    {
-        "arn": str,
-    },
-)
-
 PauseCampaignRequestRequestTypeDef = TypedDict(
     "PauseCampaignRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -304,14 +321,25 @@
     {
         "clientToken": str,
         "id": str,
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
 ResumeCampaignRequestRequestTypeDef = TypedDict(
     "ResumeCampaignRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -365,21 +393,19 @@
     {
         "answerMachineDetectionConfig": AnswerMachineDetectionConfigTypeDef,
         "connectSourcePhoneNumber": str,
     },
     total=False,
 )
 
-
 class OutboundCallConfigTypeDef(
     _RequiredOutboundCallConfigTypeDef, _OptionalOutboundCallConfigTypeDef
 ):
     pass
 
-
 _RequiredUpdateCampaignOutboundCallConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCampaignOutboundCallConfigRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalUpdateCampaignOutboundCallConfigRequestRequestTypeDef = TypedDict(
@@ -388,69 +414,34 @@
         "answerMachineDetectionConfig": AnswerMachineDetectionConfigTypeDef,
         "connectContactFlowId": str,
         "connectSourcePhoneNumber": str,
     },
     total=False,
 )
 
-
 class UpdateCampaignOutboundCallConfigRequestRequestTypeDef(
     _RequiredUpdateCampaignOutboundCallConfigRequestRequestTypeDef,
     _OptionalUpdateCampaignOutboundCallConfigRequestRequestTypeDef,
 ):
     pass
 
-
 CampaignFiltersTypeDef = TypedDict(
     "CampaignFiltersTypeDef",
     {
         "instanceIdFilter": InstanceIdFilterTypeDef,
     },
     total=False,
 )
 
-CreateCampaignResponseTypeDef = TypedDict(
-    "CreateCampaignResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "tags": Dict[str, str],
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
-GetCampaignStateResponseTypeDef = TypedDict(
-    "GetCampaignStateResponseTypeDef",
-    {
-        "state": CampaignStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListCampaignsResponseTypeDef = TypedDict(
     "ListCampaignsResponseTypeDef",
     {
         "campaignSummaryList": List[CampaignSummaryTypeDef],
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
 
 PutDialRequestBatchRequestRequestTypeDef = TypedDict(
     "PutDialRequestBatchRequestRequestTypeDef",
     {
         "dialRequests": Sequence[DialRequestTypeDef],
@@ -485,48 +476,48 @@
 )
 
 GetCampaignStateBatchResponseTypeDef = TypedDict(
     "GetCampaignStateBatchResponseTypeDef",
     {
         "failedRequests": List[FailedCampaignStateResponseTypeDef],
         "successfulRequests": List[SuccessfulCampaignStateResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceOnboardingJobStatusResponseTypeDef = TypedDict(
     "GetInstanceOnboardingJobStatusResponseTypeDef",
     {
         "connectInstanceOnboardingJobStatus": InstanceOnboardingJobStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartInstanceOnboardingJobResponseTypeDef = TypedDict(
     "StartInstanceOnboardingJobResponseTypeDef",
     {
         "connectInstanceOnboardingJobStatus": InstanceOnboardingJobStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDialRequestBatchResponseTypeDef = TypedDict(
     "PutDialRequestBatchResponseTypeDef",
     {
         "failedRequests": List[FailedRequestTypeDef],
         "successfulRequests": List[SuccessfulRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
     "ListCampaignsRequestListCampaignsPaginateTypeDef",
     {
         "filters": CampaignFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCampaignsRequestRequestTypeDef = TypedDict(
     "ListCampaignsRequestRequestTypeDef",
     {
@@ -552,19 +543,17 @@
     "_OptionalCampaignTypeDef",
     {
         "tags": Dict[str, str],
     },
     total=False,
 )
 
-
 class CampaignTypeDef(_RequiredCampaignTypeDef, _OptionalCampaignTypeDef):
     pass
 
-
 _RequiredCreateCampaignRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCampaignRequestRequestTypeDef",
     {
         "connectInstanceId": str,
         "dialerConfig": DialerConfigTypeDef,
         "name": str,
         "outboundCallConfig": OutboundCallConfigTypeDef,
@@ -574,37 +563,35 @@
     "_OptionalCreateCampaignRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateCampaignRequestRequestTypeDef(
     _RequiredCreateCampaignRequestRequestTypeDef, _OptionalCreateCampaignRequestRequestTypeDef
 ):
     pass
 
-
 UpdateCampaignDialerConfigRequestRequestTypeDef = TypedDict(
     "UpdateCampaignDialerConfigRequestRequestTypeDef",
     {
         "dialerConfig": DialerConfigTypeDef,
         "id": str,
     },
 )
 
 GetConnectInstanceConfigResponseTypeDef = TypedDict(
     "GetConnectInstanceConfigResponseTypeDef",
     {
         "connectInstanceConfig": InstanceConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCampaignResponseTypeDef = TypedDict(
     "DescribeCampaignResponseTypeDef",
     {
         "campaign": CampaignTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns/type_defs.pyi` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -28,53 +28,54 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AnswerMachineDetectionConfigTypeDef",
     "InstanceIdFilterTypeDef",
     "CampaignSummaryTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateCampaignResponseTypeDef",
     "DeleteCampaignRequestRequestTypeDef",
     "DeleteConnectInstanceConfigRequestRequestTypeDef",
     "DeleteInstanceOnboardingJobRequestRequestTypeDef",
     "DescribeCampaignRequestRequestTypeDef",
     "DialRequestTypeDef",
     "PredictiveDialerConfigTypeDef",
     "ProgressiveDialerConfigTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionConfigTypeDef",
     "FailedCampaignStateResponseTypeDef",
     "FailedRequestTypeDef",
     "GetCampaignStateBatchRequestRequestTypeDef",
     "SuccessfulCampaignStateResponseTypeDef",
     "GetCampaignStateRequestRequestTypeDef",
+    "GetCampaignStateResponseTypeDef",
     "GetConnectInstanceConfigRequestRequestTypeDef",
     "GetInstanceOnboardingJobStatusRequestRequestTypeDef",
     "InstanceOnboardingJobStatusTypeDef",
-    "PaginatorConfigTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
     "PauseCampaignRequestRequestTypeDef",
     "SuccessfulRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeCampaignRequestRequestTypeDef",
     "StartCampaignRequestRequestTypeDef",
     "StopCampaignRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCampaignNameRequestRequestTypeDef",
     "OutboundCallConfigTypeDef",
     "UpdateCampaignOutboundCallConfigRequestRequestTypeDef",
     "CampaignFiltersTypeDef",
-    "CreateCampaignResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCampaignStateResponseTypeDef",
     "ListCampaignsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "PutDialRequestBatchRequestRequestTypeDef",
     "DialerConfigTypeDef",
     "InstanceConfigTypeDef",
     "StartInstanceOnboardingJobRequestRequestTypeDef",
     "GetCampaignStateBatchResponseTypeDef",
     "GetInstanceOnboardingJobStatusResponseTypeDef",
     "StartInstanceOnboardingJobResponseTypeDef",
@@ -109,22 +110,21 @@
         "arn": str,
         "connectInstanceId": str,
         "id": str,
         "name": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateCampaignResponseTypeDef = TypedDict(
+    "CreateCampaignResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "id": str,
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCampaignRequestRequestTypeDef = TypedDict(
     "DeleteCampaignRequestRequestTypeDef",
     {
         "id": str,
@@ -172,14 +172,21 @@
 ProgressiveDialerConfigTypeDef = TypedDict(
     "ProgressiveDialerConfigTypeDef",
     {
         "bandwidthAllocation": float,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEncryptionConfigTypeDef = TypedDict(
     "_RequiredEncryptionConfigTypeDef",
     {
         "enabled": bool,
     },
 )
 _OptionalEncryptionConfigTypeDef = TypedDict(
@@ -187,17 +194,19 @@
     {
         "encryptionType": Literal["KMS"],
         "keyArn": str,
     },
     total=False,
 )
 
+
 class EncryptionConfigTypeDef(_RequiredEncryptionConfigTypeDef, _OptionalEncryptionConfigTypeDef):
     pass
 
+
 FailedCampaignStateResponseTypeDef = TypedDict(
     "FailedCampaignStateResponseTypeDef",
     {
         "campaignId": str,
         "failureCode": GetCampaignStateBatchFailureCodeType,
     },
     total=False,
@@ -232,14 +241,22 @@
 GetCampaignStateRequestRequestTypeDef = TypedDict(
     "GetCampaignStateRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetCampaignStateResponseTypeDef = TypedDict(
+    "GetCampaignStateResponseTypeDef",
+    {
+        "state": CampaignStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetConnectInstanceConfigRequestRequestTypeDef = TypedDict(
     "GetConnectInstanceConfigRequestRequestTypeDef",
     {
         "connectInstanceId": str,
     },
 )
 
@@ -261,36 +278,46 @@
     "_OptionalInstanceOnboardingJobStatusTypeDef",
     {
         "failureCode": InstanceOnboardingJobFailureCodeType,
     },
     total=False,
 )
 
+
 class InstanceOnboardingJobStatusTypeDef(
     _RequiredInstanceOnboardingJobStatusTypeDef, _OptionalInstanceOnboardingJobStatusTypeDef
 ):
     pass
 
+
+ListTagsForResourceRequestRequestTypeDef = TypedDict(
+    "ListTagsForResourceRequestRequestTypeDef",
+    {
+        "arn": str,
+    },
+)
+
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PaginatorConfigTypeDef = TypedDict(
     "PaginatorConfigTypeDef",
     {
         "MaxItems": int,
         "PageSize": int,
         "StartingToken": str,
     },
     total=False,
 )
 
-ListTagsForResourceRequestRequestTypeDef = TypedDict(
-    "ListTagsForResourceRequestRequestTypeDef",
-    {
-        "arn": str,
-    },
-)
-
 PauseCampaignRequestRequestTypeDef = TypedDict(
     "PauseCampaignRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -299,14 +326,25 @@
     {
         "clientToken": str,
         "id": str,
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
 ResumeCampaignRequestRequestTypeDef = TypedDict(
     "ResumeCampaignRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -360,19 +398,21 @@
     {
         "answerMachineDetectionConfig": AnswerMachineDetectionConfigTypeDef,
         "connectSourcePhoneNumber": str,
     },
     total=False,
 )
 
+
 class OutboundCallConfigTypeDef(
     _RequiredOutboundCallConfigTypeDef, _OptionalOutboundCallConfigTypeDef
 ):
     pass
 
+
 _RequiredUpdateCampaignOutboundCallConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCampaignOutboundCallConfigRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalUpdateCampaignOutboundCallConfigRequestRequestTypeDef = TypedDict(
@@ -381,67 +421,36 @@
         "answerMachineDetectionConfig": AnswerMachineDetectionConfigTypeDef,
         "connectContactFlowId": str,
         "connectSourcePhoneNumber": str,
     },
     total=False,
 )
 
+
 class UpdateCampaignOutboundCallConfigRequestRequestTypeDef(
     _RequiredUpdateCampaignOutboundCallConfigRequestRequestTypeDef,
     _OptionalUpdateCampaignOutboundCallConfigRequestRequestTypeDef,
 ):
     pass
 
+
 CampaignFiltersTypeDef = TypedDict(
     "CampaignFiltersTypeDef",
     {
         "instanceIdFilter": InstanceIdFilterTypeDef,
     },
     total=False,
 )
 
-CreateCampaignResponseTypeDef = TypedDict(
-    "CreateCampaignResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "tags": Dict[str, str],
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
-GetCampaignStateResponseTypeDef = TypedDict(
-    "GetCampaignStateResponseTypeDef",
-    {
-        "state": CampaignStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListCampaignsResponseTypeDef = TypedDict(
     "ListCampaignsResponseTypeDef",
     {
         "campaignSummaryList": List[CampaignSummaryTypeDef],
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
 
 PutDialRequestBatchRequestRequestTypeDef = TypedDict(
     "PutDialRequestBatchRequestRequestTypeDef",
     {
         "dialRequests": Sequence[DialRequestTypeDef],
@@ -476,48 +485,48 @@
 )
 
 GetCampaignStateBatchResponseTypeDef = TypedDict(
     "GetCampaignStateBatchResponseTypeDef",
     {
         "failedRequests": List[FailedCampaignStateResponseTypeDef],
         "successfulRequests": List[SuccessfulCampaignStateResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceOnboardingJobStatusResponseTypeDef = TypedDict(
     "GetInstanceOnboardingJobStatusResponseTypeDef",
     {
         "connectInstanceOnboardingJobStatus": InstanceOnboardingJobStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartInstanceOnboardingJobResponseTypeDef = TypedDict(
     "StartInstanceOnboardingJobResponseTypeDef",
     {
         "connectInstanceOnboardingJobStatus": InstanceOnboardingJobStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDialRequestBatchResponseTypeDef = TypedDict(
     "PutDialRequestBatchResponseTypeDef",
     {
         "failedRequests": List[FailedRequestTypeDef],
         "successfulRequests": List[SuccessfulRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
     "ListCampaignsRequestListCampaignsPaginateTypeDef",
     {
         "filters": CampaignFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCampaignsRequestRequestTypeDef = TypedDict(
     "ListCampaignsRequestRequestTypeDef",
     {
@@ -543,17 +552,19 @@
     "_OptionalCampaignTypeDef",
     {
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+
 class CampaignTypeDef(_RequiredCampaignTypeDef, _OptionalCampaignTypeDef):
     pass
 
+
 _RequiredCreateCampaignRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCampaignRequestRequestTypeDef",
     {
         "connectInstanceId": str,
         "dialerConfig": DialerConfigTypeDef,
         "name": str,
         "outboundCallConfig": OutboundCallConfigTypeDef,
@@ -563,35 +574,37 @@
     "_OptionalCreateCampaignRequestRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateCampaignRequestRequestTypeDef(
     _RequiredCreateCampaignRequestRequestTypeDef, _OptionalCreateCampaignRequestRequestTypeDef
 ):
     pass
 
+
 UpdateCampaignDialerConfigRequestRequestTypeDef = TypedDict(
     "UpdateCampaignDialerConfigRequestRequestTypeDef",
     {
         "dialerConfig": DialerConfigTypeDef,
         "id": str,
     },
 )
 
 GetConnectInstanceConfigResponseTypeDef = TypedDict(
     "GetConnectInstanceConfigResponseTypeDef",
     {
         "connectInstanceConfig": InstanceConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCampaignResponseTypeDef = TypedDict(
     "DescribeCampaignResponseTypeDef",
     {
         "campaign": CampaignTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/PKG-INFO` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-connectcampaigns
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectCampaignService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectCampaignService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-connectcampaigns"></a>
 
 # types-aiobotocore-connectcampaigns
 
 [![PyPI - types-aiobotocore-connectcampaigns](https://img.shields.io/pypi/v/types-aiobotocore-connectcampaigns.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcampaigns)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-connectcampaigns.svg?color=blue)](https://pypi.org/project/types-aiobotocore-connectcampaigns)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-connectcampaigns?color=blue)](https://pypistats.org/packages/types-aiobotocore-connectcampaigns)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectCampaignService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService)
+[aiobotocore.ConnectCampaignService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/connectcampaigns.html#ConnectCampaignService)
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
 [types-aiobotocore-connectcampaigns docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_connectcampaigns/).
 
 See how it helps to find and fix potential bugs:
 
@@ -324,49 +324,49 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_connectcampaigns.type_defs import (
     AnswerMachineDetectionConfigTypeDef,
     InstanceIdFilterTypeDef,
     CampaignSummaryTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCampaignResponseTypeDef,
     DeleteCampaignRequestRequestTypeDef,
     DeleteConnectInstanceConfigRequestRequestTypeDef,
     DeleteInstanceOnboardingJobRequestRequestTypeDef,
     DescribeCampaignRequestRequestTypeDef,
     DialRequestTypeDef,
     PredictiveDialerConfigTypeDef,
     ProgressiveDialerConfigTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionConfigTypeDef,
     FailedCampaignStateResponseTypeDef,
     FailedRequestTypeDef,
     GetCampaignStateBatchRequestRequestTypeDef,
     SuccessfulCampaignStateResponseTypeDef,
     GetCampaignStateRequestRequestTypeDef,
+    GetCampaignStateResponseTypeDef,
     GetConnectInstanceConfigRequestRequestTypeDef,
     GetInstanceOnboardingJobStatusRequestRequestTypeDef,
     InstanceOnboardingJobStatusTypeDef,
-    PaginatorConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
     PauseCampaignRequestRequestTypeDef,
     SuccessfulRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResumeCampaignRequestRequestTypeDef,
     StartCampaignRequestRequestTypeDef,
     StopCampaignRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCampaignNameRequestRequestTypeDef,
     OutboundCallConfigTypeDef,
     UpdateCampaignOutboundCallConfigRequestRequestTypeDef,
     CampaignFiltersTypeDef,
-    CreateCampaignResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCampaignStateResponseTypeDef,
     ListCampaignsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     PutDialRequestBatchRequestRequestTypeDef,
     DialerConfigTypeDef,
     InstanceConfigTypeDef,
     StartInstanceOnboardingJobRequestRequestTypeDef,
     GetCampaignStateBatchResponseTypeDef,
     GetInstanceOnboardingJobStatusResponseTypeDef,
     StartInstanceOnboardingJobResponseTypeDef,
@@ -388,43 +388,43 @@
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

### Comparing `types-aiobotocore-connectcampaigns-2.5.0.post1/types_aiobotocore_connectcampaigns.egg-info/SOURCES.txt` & `types-aiobotocore-connectcampaigns-2.5.1/types_aiobotocore_connectcampaigns.egg-info/SOURCES.txt`

 * *Files identical despite different names*

