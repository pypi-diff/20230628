# Comparing `tmp/types-aiobotocore-mturk-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mturk-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mturk-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-mturk-2.5.1.tar", last modified: Wed Jun 28 01:43:53 2023, max compression
```

## Comparing `types-aiobotocore-mturk-2.5.0.post1.tar` & `types-aiobotocore-mturk-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.199461 types-aiobotocore-mturk-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18634 2023-03-11 12:27:03.199461 types-aiobotocore-mturk-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17071 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.199461 types-aiobotocore-mturk-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.191460 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/
--rw-r--r--   0 runner    (1001) docker     (123)     2567 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2566 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35389 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35332 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10386 2023-03-11 12:18:59.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10384 2023-03-11 12:18:59.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11862 2023-03-11 12:18:59.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11850 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    37534 2023-03-11 12:18:59.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    37479 2023-03-11 12:18:59.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:58.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.199461 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18634 2023-03-11 12:27:03.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-03-11 12:27:03.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:27:03.000000 types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.970183 types-aiobotocore-mturk-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18624 2023-06-28 01:43:53.966183 types-aiobotocore-mturk-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17067 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:53.970183 types-aiobotocore-mturk-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.958182 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/
+-rw-r--r--   0 runner    (1001) docker     (123)     2567 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2566 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35388 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35331 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10595 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10593 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11760 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11749 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    37596 2023-06-28 01:35:43.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37541 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:42.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.966183 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18624 2023-06-28 01:43:53.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 01:43:53.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:53.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:43:53.000000 types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mturk-2.5.0.post1/LICENSE` & `types-aiobotocore-mturk-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mturk-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mturk
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MTurk 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MTurk 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mturk"></a>
 
 # types-aiobotocore-mturk
 
 [![PyPI - types-aiobotocore-mturk](https://img.shields.io/pypi/v/types-aiobotocore-mturk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mturk)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mturk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mturk)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mturk?color=blue)](https://pypistats.org/packages/types-aiobotocore-mturk)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MTurk 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk)
+[aiobotocore.MTurk 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk)
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
 [types-aiobotocore-mturk docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/).
 
 See how it helps to find and fix potential bugs:
 
@@ -374,72 +374,72 @@
     AcceptQualificationRequestRequestRequestTypeDef,
     ApproveAssignmentRequestRequestTypeDef,
     AssignmentTypeDef,
     AssociateQualificationWithWorkerRequestRequestTypeDef,
     BonusPaymentTypeDef,
     CreateAdditionalAssignmentsForHITRequestRequestTypeDef,
     HITLayoutParameterTypeDef,
-    ResponseMetadataTypeDef,
+    CreateHITTypeResponseTypeDef,
     CreateQualificationTypeRequestRequestTypeDef,
     QualificationTypeTypeDef,
     CreateWorkerBlockRequestRequestTypeDef,
     DeleteHITRequestRequestTypeDef,
     DeleteQualificationTypeRequestRequestTypeDef,
     DeleteWorkerBlockRequestRequestTypeDef,
     DisassociateQualificationFromWorkerRequestRequestTypeDef,
+    GetAccountBalanceResponseTypeDef,
     GetAssignmentRequestRequestTypeDef,
     GetFileUploadURLRequestRequestTypeDef,
+    GetFileUploadURLResponseTypeDef,
     GetHITRequestRequestTypeDef,
     GetQualificationScoreRequestRequestTypeDef,
     GetQualificationTypeRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
     ListAssignmentsForHITRequestRequestTypeDef,
+    ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef,
     ListBonusPaymentsRequestRequestTypeDef,
+    ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
     ListHITsForQualificationTypeRequestRequestTypeDef,
+    ListHITsRequestListHITsPaginateTypeDef,
     ListHITsRequestRequestTypeDef,
+    ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef,
     ListQualificationRequestsRequestRequestTypeDef,
     QualificationRequestTypeDef,
+    ListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
     ListQualificationTypesRequestRequestTypeDef,
     ListReviewPolicyResultsForHITRequestRequestTypeDef,
+    ListReviewableHITsRequestListReviewableHITsPaginateTypeDef,
     ListReviewableHITsRequestRequestTypeDef,
+    ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef,
     ListWorkerBlocksRequestRequestTypeDef,
     WorkerBlockTypeDef,
+    ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
     ListWorkersWithQualificationTypeRequestRequestTypeDef,
     LocaleTypeDef,
     NotificationSpecificationTypeDef,
     NotifyWorkersFailureStatusTypeDef,
     NotifyWorkersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterMapEntryTypeDef,
     RejectAssignmentRequestRequestTypeDef,
     RejectQualificationRequestRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ReviewActionDetailTypeDef,
     ReviewResultDetailTypeDef,
     SendBonusRequestRequestTypeDef,
     UpdateExpirationForHITRequestRequestTypeDef,
     UpdateHITReviewStatusRequestRequestTypeDef,
     UpdateHITTypeOfHITRequestRequestTypeDef,
     UpdateQualificationTypeRequestRequestTypeDef,
-    CreateHITTypeResponseTypeDef,
-    GetAccountBalanceResponseTypeDef,
-    GetFileUploadURLResponseTypeDef,
     ListAssignmentsForHITResponseTypeDef,
     ListBonusPaymentsResponseTypeDef,
     CreateQualificationTypeResponseTypeDef,
     GetQualificationTypeResponseTypeDef,
     ListQualificationTypesResponseTypeDef,
     UpdateQualificationTypeResponseTypeDef,
-    ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
-    ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef,
-    ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
-    ListHITsRequestListHITsPaginateTypeDef,
-    ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef,
-    ListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
-    ListReviewableHITsRequestListReviewableHITsPaginateTypeDef,
-    ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef,
-    ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
     ListQualificationRequestsResponseTypeDef,
     ListWorkerBlocksResponseTypeDef,
     QualificationRequirementTypeDef,
     QualificationTypeDef,
     SendTestEventNotificationRequestRequestTypeDef,
     UpdateNotificationSettingsRequestRequestTypeDef,
     NotifyWorkersResponseTypeDef,
@@ -470,43 +470,43 @@
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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/README.md` & `types-aiobotocore-mturk-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mturk"></a>
 
 # types-aiobotocore-mturk
 
 [![PyPI - types-aiobotocore-mturk](https://img.shields.io/pypi/v/types-aiobotocore-mturk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mturk)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mturk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mturk)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mturk?color=blue)](https://pypistats.org/packages/types-aiobotocore-mturk)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MTurk 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk)
+[aiobotocore.MTurk 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk)
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
 [types-aiobotocore-mturk docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/).
 
 See how it helps to find and fix potential bugs:
 
@@ -341,72 +341,72 @@
     AcceptQualificationRequestRequestRequestTypeDef,
     ApproveAssignmentRequestRequestTypeDef,
     AssignmentTypeDef,
     AssociateQualificationWithWorkerRequestRequestTypeDef,
     BonusPaymentTypeDef,
     CreateAdditionalAssignmentsForHITRequestRequestTypeDef,
     HITLayoutParameterTypeDef,
-    ResponseMetadataTypeDef,
+    CreateHITTypeResponseTypeDef,
     CreateQualificationTypeRequestRequestTypeDef,
     QualificationTypeTypeDef,
     CreateWorkerBlockRequestRequestTypeDef,
     DeleteHITRequestRequestTypeDef,
     DeleteQualificationTypeRequestRequestTypeDef,
     DeleteWorkerBlockRequestRequestTypeDef,
     DisassociateQualificationFromWorkerRequestRequestTypeDef,
+    GetAccountBalanceResponseTypeDef,
     GetAssignmentRequestRequestTypeDef,
     GetFileUploadURLRequestRequestTypeDef,
+    GetFileUploadURLResponseTypeDef,
     GetHITRequestRequestTypeDef,
     GetQualificationScoreRequestRequestTypeDef,
     GetQualificationTypeRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
     ListAssignmentsForHITRequestRequestTypeDef,
+    ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef,
     ListBonusPaymentsRequestRequestTypeDef,
+    ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
     ListHITsForQualificationTypeRequestRequestTypeDef,
+    ListHITsRequestListHITsPaginateTypeDef,
     ListHITsRequestRequestTypeDef,
+    ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef,
     ListQualificationRequestsRequestRequestTypeDef,
     QualificationRequestTypeDef,
+    ListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
     ListQualificationTypesRequestRequestTypeDef,
     ListReviewPolicyResultsForHITRequestRequestTypeDef,
+    ListReviewableHITsRequestListReviewableHITsPaginateTypeDef,
     ListReviewableHITsRequestRequestTypeDef,
+    ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef,
     ListWorkerBlocksRequestRequestTypeDef,
     WorkerBlockTypeDef,
+    ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
     ListWorkersWithQualificationTypeRequestRequestTypeDef,
     LocaleTypeDef,
     NotificationSpecificationTypeDef,
     NotifyWorkersFailureStatusTypeDef,
     NotifyWorkersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterMapEntryTypeDef,
     RejectAssignmentRequestRequestTypeDef,
     RejectQualificationRequestRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ReviewActionDetailTypeDef,
     ReviewResultDetailTypeDef,
     SendBonusRequestRequestTypeDef,
     UpdateExpirationForHITRequestRequestTypeDef,
     UpdateHITReviewStatusRequestRequestTypeDef,
     UpdateHITTypeOfHITRequestRequestTypeDef,
     UpdateQualificationTypeRequestRequestTypeDef,
-    CreateHITTypeResponseTypeDef,
-    GetAccountBalanceResponseTypeDef,
-    GetFileUploadURLResponseTypeDef,
     ListAssignmentsForHITResponseTypeDef,
     ListBonusPaymentsResponseTypeDef,
     CreateQualificationTypeResponseTypeDef,
     GetQualificationTypeResponseTypeDef,
     ListQualificationTypesResponseTypeDef,
     UpdateQualificationTypeResponseTypeDef,
-    ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
-    ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef,
-    ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
-    ListHITsRequestListHITsPaginateTypeDef,
-    ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef,
-    ListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
-    ListReviewableHITsRequestListReviewableHITsPaginateTypeDef,
-    ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef,
-    ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
     ListQualificationRequestsResponseTypeDef,
     ListWorkerBlocksResponseTypeDef,
     QualificationRequirementTypeDef,
     QualificationTypeDef,
     SendTestEventNotificationRequestRequestTypeDef,
     UpdateNotificationSettingsRequestRequestTypeDef,
     NotifyWorkersResponseTypeDef,
@@ -437,43 +437,43 @@
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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/setup.py` & `types-aiobotocore-mturk-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mturk.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mturk",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mturk"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MTurk 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.MTurk 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/"
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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/__init__.py` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/__init__.pyi` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/__main__.py` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MTurk 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MTurk 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk\nOther"
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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/client.py` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -368,15 +368,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/client/#get_qualification_score)
         """
 
     async def get_qualification_type(
         self, *, QualificationTypeId: str
     ) -> GetQualificationTypeResponseTypeDef:
         """
-        The `GetQualificationType` operation retrieves information about a Qualification
+        The `GetQualificationType`operation retrieves information about a Qualification
         type using its ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Client.get_qualification_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/client/#get_qualification_type)
         """
 
     async def list_assignments_for_hit(
```

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/client.pyi` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -342,15 +342,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Client.get_qualification_score)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/client/#get_qualification_score)
         """
     async def get_qualification_type(
         self, *, QualificationTypeId: str
     ) -> GetQualificationTypeResponseTypeDef:
         """
-        The `GetQualificationType` operation retrieves information about a Qualification
+        The `GetQualificationType`operation retrieves information about a Qualification
         type using its ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Client.get_qualification_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/client/#get_qualification_type)
         """
     async def list_assignments_for_hit(
         self,
```

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/literals.py` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -157,14 +157,15 @@
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
@@ -243,14 +244,15 @@
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
@@ -261,14 +263,15 @@
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
@@ -304,14 +307,15 @@
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
@@ -330,16 +334,19 @@
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
@@ -423,15 +430,17 @@
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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/literals.pyi` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -155,14 +155,15 @@
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
@@ -241,14 +242,15 @@
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
@@ -259,14 +261,15 @@
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
@@ -302,14 +305,15 @@
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
@@ -328,16 +332,19 @@
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
@@ -421,15 +428,17 @@
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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/paginator.py` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/paginator.py`

 * *Files 7% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_qualification_requests_paginator: ListQualificationRequestsPaginator = client.get_paginator("list_qualification_requests")
         list_qualification_types_paginator: ListQualificationTypesPaginator = client.get_paginator("list_qualification_types")
         list_reviewable_hits_paginator: ListReviewableHITsPaginator = client.get_paginator("list_reviewable_hits")
         list_worker_blocks_paginator: ListWorkerBlocksPaginator = client.get_paginator("list_worker_blocks")
         list_workers_with_qualification_type_paginator: ListWorkersWithQualificationTypePaginator = client.get_paginator("list_workers_with_qualification_type")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AssignmentStatusType, QualificationStatusType, ReviewableHITStatusType
 from .type_defs import (
     ListAssignmentsForHITResponseTypeDef,
@@ -52,20 +51,14 @@
     ListQualificationTypesResponseTypeDef,
     ListReviewableHITsResponseTypeDef,
     ListWorkerBlocksResponseTypeDef,
     ListWorkersWithQualificationTypeResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAssignmentsForHITPaginator",
     "ListBonusPaymentsPaginator",
     "ListHITsPaginator",
     "ListHITsForQualificationTypePaginator",
     "ListQualificationRequestsPaginator",
     "ListQualificationTypesPaginator",
@@ -92,15 +85,15 @@
     """
 
     def paginate(
         self,
         *,
         HITId: str,
         AssignmentStatuses: Sequence[AssignmentStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssignmentsForHITResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListAssignmentsForHIT.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listassignmentsforhitpaginator)
         """
 
 
@@ -111,60 +104,60 @@
     """
 
     def paginate(
         self,
         *,
         HITId: str = ...,
         AssignmentId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBonusPaymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListBonusPayments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listbonuspaymentspaginator)
         """
 
 
 class ListHITsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHITsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitspaginator)
         """
 
 
 class ListHITsForQualificationTypePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITsForQualificationType)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitsforqualificationtypepaginator)
     """
 
     def paginate(
-        self, *, QualificationTypeId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QualificationTypeId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHITsForQualificationTypeResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITsForQualificationType.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitsforqualificationtypepaginator)
         """
 
 
 class ListQualificationRequestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListQualificationRequests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listqualificationrequestspaginator)
     """
 
     def paginate(
-        self, *, QualificationTypeId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QualificationTypeId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQualificationRequestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListQualificationRequests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listqualificationrequestspaginator)
         """
 
 
@@ -176,15 +169,15 @@
 
     def paginate(
         self,
         *,
         MustBeRequestable: bool,
         Query: str = ...,
         MustBeOwnedByCaller: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQualificationTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListQualificationTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listqualificationtypespaginator)
         """
 
 
@@ -195,30 +188,30 @@
     """
 
     def paginate(
         self,
         *,
         HITTypeId: str = ...,
         Status: ReviewableHITStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReviewableHITsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListReviewableHITs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listreviewablehitspaginator)
         """
 
 
 class ListWorkerBlocksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListWorkerBlocks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listworkerblockspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkerBlocksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListWorkerBlocks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listworkerblockspaginator)
         """
 
 
@@ -229,13 +222,13 @@
     """
 
     def paginate(
         self,
         *,
         QualificationTypeId: str,
         Status: QualificationStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkersWithQualificationTypeResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListWorkersWithQualificationType.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listworkerswithqualificationtypepaginator)
         """
```

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/paginator.pyi` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/paginator.pyi`

 * *Files 14% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_qualification_requests_paginator: ListQualificationRequestsPaginator = client.get_paginator("list_qualification_requests")
         list_qualification_types_paginator: ListQualificationTypesPaginator = client.get_paginator("list_qualification_types")
         list_reviewable_hits_paginator: ListReviewableHITsPaginator = client.get_paginator("list_reviewable_hits")
         list_worker_blocks_paginator: ListWorkerBlocksPaginator = client.get_paginator("list_worker_blocks")
         list_workers_with_qualification_type_paginator: ListWorkersWithQualificationTypePaginator = client.get_paginator("list_workers_with_qualification_type")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import AssignmentStatusType, QualificationStatusType, ReviewableHITStatusType
 from .type_defs import (
     ListAssignmentsForHITResponseTypeDef,
@@ -52,19 +51,14 @@
     ListQualificationTypesResponseTypeDef,
     ListReviewableHITsResponseTypeDef,
     ListWorkerBlocksResponseTypeDef,
     ListWorkersWithQualificationTypeResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAssignmentsForHITPaginator",
     "ListBonusPaymentsPaginator",
     "ListHITsPaginator",
     "ListHITsForQualificationTypePaginator",
     "ListQualificationRequestsPaginator",
     "ListQualificationTypesPaginator",
@@ -88,15 +82,15 @@
     """
 
     def paginate(
         self,
         *,
         HITId: str,
         AssignmentStatuses: Sequence[AssignmentStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssignmentsForHITResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListAssignmentsForHIT.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listassignmentsforhitpaginator)
         """
 
 class ListBonusPaymentsPaginator(AioPaginator):
@@ -106,57 +100,57 @@
     """
 
     def paginate(
         self,
         *,
         HITId: str = ...,
         AssignmentId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBonusPaymentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListBonusPayments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listbonuspaymentspaginator)
         """
 
 class ListHITsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHITsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitspaginator)
         """
 
 class ListHITsForQualificationTypePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITsForQualificationType)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitsforqualificationtypepaginator)
     """
 
     def paginate(
-        self, *, QualificationTypeId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QualificationTypeId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListHITsForQualificationTypeResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListHITsForQualificationType.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listhitsforqualificationtypepaginator)
         """
 
 class ListQualificationRequestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListQualificationRequests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listqualificationrequestspaginator)
     """
 
     def paginate(
-        self, *, QualificationTypeId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, QualificationTypeId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQualificationRequestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListQualificationRequests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listqualificationrequestspaginator)
         """
 
 class ListQualificationTypesPaginator(AioPaginator):
@@ -167,15 +161,15 @@
 
     def paginate(
         self,
         *,
         MustBeRequestable: bool,
         Query: str = ...,
         MustBeOwnedByCaller: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListQualificationTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListQualificationTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listqualificationtypespaginator)
         """
 
 class ListReviewableHITsPaginator(AioPaginator):
@@ -185,29 +179,29 @@
     """
 
     def paginate(
         self,
         *,
         HITTypeId: str = ...,
         Status: ReviewableHITStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReviewableHITsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListReviewableHITs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listreviewablehitspaginator)
         """
 
 class ListWorkerBlocksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListWorkerBlocks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listworkerblockspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkerBlocksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListWorkerBlocks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listworkerblockspaginator)
         """
 
 class ListWorkersWithQualificationTypePaginator(AioPaginator):
@@ -217,13 +211,13 @@
     """
 
     def paginate(
         self,
         *,
         QualificationTypeId: str,
         Status: QualificationStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkersWithQualificationTypeResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk.Paginator.ListWorkersWithQualificationType.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/paginators/#listworkerswithqualificationtypepaginator)
         """
```

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/type_defs.py` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -41,72 +41,72 @@
     "AcceptQualificationRequestRequestRequestTypeDef",
     "ApproveAssignmentRequestRequestTypeDef",
     "AssignmentTypeDef",
     "AssociateQualificationWithWorkerRequestRequestTypeDef",
     "BonusPaymentTypeDef",
     "CreateAdditionalAssignmentsForHITRequestRequestTypeDef",
     "HITLayoutParameterTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateHITTypeResponseTypeDef",
     "CreateQualificationTypeRequestRequestTypeDef",
     "QualificationTypeTypeDef",
     "CreateWorkerBlockRequestRequestTypeDef",
     "DeleteHITRequestRequestTypeDef",
     "DeleteQualificationTypeRequestRequestTypeDef",
     "DeleteWorkerBlockRequestRequestTypeDef",
     "DisassociateQualificationFromWorkerRequestRequestTypeDef",
+    "GetAccountBalanceResponseTypeDef",
     "GetAssignmentRequestRequestTypeDef",
     "GetFileUploadURLRequestRequestTypeDef",
+    "GetFileUploadURLResponseTypeDef",
     "GetHITRequestRequestTypeDef",
     "GetQualificationScoreRequestRequestTypeDef",
     "GetQualificationTypeRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
     "ListAssignmentsForHITRequestRequestTypeDef",
+    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
     "ListBonusPaymentsRequestRequestTypeDef",
+    "ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
     "ListHITsForQualificationTypeRequestRequestTypeDef",
+    "ListHITsRequestListHITsPaginateTypeDef",
     "ListHITsRequestRequestTypeDef",
+    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
     "ListQualificationRequestsRequestRequestTypeDef",
     "QualificationRequestTypeDef",
+    "ListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
     "ListQualificationTypesRequestRequestTypeDef",
     "ListReviewPolicyResultsForHITRequestRequestTypeDef",
+    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
     "ListReviewableHITsRequestRequestTypeDef",
+    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
     "ListWorkerBlocksRequestRequestTypeDef",
     "WorkerBlockTypeDef",
+    "ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
     "ListWorkersWithQualificationTypeRequestRequestTypeDef",
     "LocaleTypeDef",
     "NotificationSpecificationTypeDef",
     "NotifyWorkersFailureStatusTypeDef",
     "NotifyWorkersRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterMapEntryTypeDef",
     "RejectAssignmentRequestRequestTypeDef",
     "RejectQualificationRequestRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ReviewActionDetailTypeDef",
     "ReviewResultDetailTypeDef",
     "SendBonusRequestRequestTypeDef",
     "UpdateExpirationForHITRequestRequestTypeDef",
     "UpdateHITReviewStatusRequestRequestTypeDef",
     "UpdateHITTypeOfHITRequestRequestTypeDef",
     "UpdateQualificationTypeRequestRequestTypeDef",
-    "CreateHITTypeResponseTypeDef",
-    "GetAccountBalanceResponseTypeDef",
-    "GetFileUploadURLResponseTypeDef",
     "ListAssignmentsForHITResponseTypeDef",
     "ListBonusPaymentsResponseTypeDef",
     "CreateQualificationTypeResponseTypeDef",
     "GetQualificationTypeResponseTypeDef",
     "ListQualificationTypesResponseTypeDef",
     "UpdateQualificationTypeResponseTypeDef",
-    "ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
-    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
-    "ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
-    "ListHITsRequestListHITsPaginateTypeDef",
-    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
-    "ListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
-    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
-    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
-    "ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
     "ListQualificationRequestsResponseTypeDef",
     "ListWorkerBlocksResponseTypeDef",
     "QualificationRequirementTypeDef",
     "QualificationTypeDef",
     "SendTestEventNotificationRequestRequestTypeDef",
     "UpdateNotificationSettingsRequestRequestTypeDef",
     "NotifyWorkersResponseTypeDef",
@@ -255,22 +255,19 @@
     "HITLayoutParameterTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateHITTypeResponseTypeDef = TypedDict(
+    "CreateHITTypeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "HITTypeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateQualificationTypeRequestRequestTypeDef = TypedDict(
     "_RequiredCreateQualificationTypeRequestRequestTypeDef",
     {
         "Name": str,
@@ -382,14 +379,23 @@
 class DisassociateQualificationFromWorkerRequestRequestTypeDef(
     _RequiredDisassociateQualificationFromWorkerRequestRequestTypeDef,
     _OptionalDisassociateQualificationFromWorkerRequestRequestTypeDef,
 ):
     pass
 
 
+GetAccountBalanceResponseTypeDef = TypedDict(
+    "GetAccountBalanceResponseTypeDef",
+    {
+        "AvailableBalance": str,
+        "OnHoldBalance": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAssignmentRequestRequestTypeDef = TypedDict(
     "GetAssignmentRequestRequestTypeDef",
     {
         "AssignmentId": str,
     },
 )
 
@@ -397,14 +403,22 @@
     "GetFileUploadURLRequestRequestTypeDef",
     {
         "AssignmentId": str,
         "QuestionIdentifier": str,
     },
 )
 
+GetFileUploadURLResponseTypeDef = TypedDict(
+    "GetFileUploadURLResponseTypeDef",
+    {
+        "FileUploadURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHITRequestRequestTypeDef = TypedDict(
     "GetHITRequestRequestTypeDef",
     {
         "HITId": str,
     },
 )
 
@@ -419,24 +433,37 @@
 GetQualificationTypeRequestRequestTypeDef = TypedDict(
     "GetQualificationTypeRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
+    "_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "HITId": str,
+    },
+)
+_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
+    "_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
+    {
+        "AssignmentStatuses": Sequence[AssignmentStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef(
+    _RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
+    _OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssignmentsForHITRequestRequestTypeDef = TypedDict(
     "_RequiredListAssignmentsForHITRequestRequestTypeDef",
     {
         "HITId": str,
     },
 )
 _OptionalListAssignmentsForHITRequestRequestTypeDef = TypedDict(
@@ -453,25 +480,57 @@
 class ListAssignmentsForHITRequestRequestTypeDef(
     _RequiredListAssignmentsForHITRequestRequestTypeDef,
     _OptionalListAssignmentsForHITRequestRequestTypeDef,
 ):
     pass
 
 
+ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef = TypedDict(
+    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
+    {
+        "HITId": str,
+        "AssignmentId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBonusPaymentsRequestRequestTypeDef = TypedDict(
     "ListBonusPaymentsRequestRequestTypeDef",
     {
         "HITId": str,
         "AssignmentId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
+    "_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
+    {
+        "QualificationTypeId": str,
+    },
+)
+_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
+    "_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef(
+    _RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
+    _OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListHITsForQualificationTypeRequestRequestTypeDef = TypedDict(
     "_RequiredListHITsForQualificationTypeRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
     },
 )
 _OptionalListHITsForQualificationTypeRequestRequestTypeDef = TypedDict(
@@ -487,23 +546,40 @@
 class ListHITsForQualificationTypeRequestRequestTypeDef(
     _RequiredListHITsForQualificationTypeRequestRequestTypeDef,
     _OptionalListHITsForQualificationTypeRequestRequestTypeDef,
 ):
     pass
 
 
+ListHITsRequestListHITsPaginateTypeDef = TypedDict(
+    "ListHITsRequestListHITsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHITsRequestRequestTypeDef = TypedDict(
     "ListHITsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef = TypedDict(
+    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
+    {
+        "QualificationTypeId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQualificationRequestsRequestRequestTypeDef = TypedDict(
     "ListQualificationRequestsRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -519,14 +595,38 @@
         "Test": str,
         "Answer": str,
         "SubmitTime": datetime,
     },
     total=False,
 )
 
+_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
+    "_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
+    {
+        "MustBeRequestable": bool,
+    },
+)
+_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
+    "_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
+    {
+        "Query": str,
+        "MustBeOwnedByCaller": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListQualificationTypesRequestListQualificationTypesPaginateTypeDef(
+    _RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
+    _OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListQualificationTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListQualificationTypesRequestRequestTypeDef",
     {
         "MustBeRequestable": bool,
     },
 )
 _OptionalListQualificationTypesRequestRequestTypeDef = TypedDict(
@@ -570,25 +670,43 @@
 class ListReviewPolicyResultsForHITRequestRequestTypeDef(
     _RequiredListReviewPolicyResultsForHITRequestRequestTypeDef,
     _OptionalListReviewPolicyResultsForHITRequestRequestTypeDef,
 ):
     pass
 
 
+ListReviewableHITsRequestListReviewableHITsPaginateTypeDef = TypedDict(
+    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
+    {
+        "HITTypeId": str,
+        "Status": ReviewableHITStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReviewableHITsRequestRequestTypeDef = TypedDict(
     "ListReviewableHITsRequestRequestTypeDef",
     {
         "HITTypeId": str,
         "Status": ReviewableHITStatusType,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef = TypedDict(
+    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkerBlocksRequestRequestTypeDef = TypedDict(
     "ListWorkerBlocksRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -599,14 +717,37 @@
     {
         "WorkerId": str,
         "Reason": str,
     },
     total=False,
 )
 
+_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
+    "_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
+    {
+        "QualificationTypeId": str,
+    },
+)
+_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
+    "_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
+    {
+        "Status": QualificationStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef(
+    _RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
+    _OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListWorkersWithQualificationTypeRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkersWithQualificationTypeRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
     },
 )
 _OptionalListWorkersWithQualificationTypeRequestRequestTypeDef = TypedDict(
@@ -671,14 +812,24 @@
     {
         "Subject": str,
         "MessageText": str,
         "WorkerIds": Sequence[str],
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
 ParameterMapEntryTypeDef = TypedDict(
     "ParameterMapEntryTypeDef",
     {
         "Key": str,
         "Values": Sequence[str],
     },
     total=False,
@@ -710,14 +861,25 @@
 class RejectQualificationRequestRequestRequestTypeDef(
     _RequiredRejectQualificationRequestRequestRequestTypeDef,
     _OptionalRejectQualificationRequestRequestRequestTypeDef,
 ):
     pass
 
 
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
 ReviewActionDetailTypeDef = TypedDict(
     "ReviewActionDetailTypeDef",
     {
         "ActionId": str,
         "ActionName": str,
         "TargetId": str,
         "TargetType": str,
@@ -829,247 +991,85 @@
 class UpdateQualificationTypeRequestRequestTypeDef(
     _RequiredUpdateQualificationTypeRequestRequestTypeDef,
     _OptionalUpdateQualificationTypeRequestRequestTypeDef,
 ):
     pass
 
 
-CreateHITTypeResponseTypeDef = TypedDict(
-    "CreateHITTypeResponseTypeDef",
-    {
-        "HITTypeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountBalanceResponseTypeDef = TypedDict(
-    "GetAccountBalanceResponseTypeDef",
-    {
-        "AvailableBalance": str,
-        "OnHoldBalance": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFileUploadURLResponseTypeDef = TypedDict(
-    "GetFileUploadURLResponseTypeDef",
-    {
-        "FileUploadURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListAssignmentsForHITResponseTypeDef = TypedDict(
     "ListAssignmentsForHITResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "Assignments": List[AssignmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBonusPaymentsResponseTypeDef = TypedDict(
     "ListBonusPaymentsResponseTypeDef",
     {
         "NumResults": int,
         "NextToken": str,
         "BonusPayments": List[BonusPaymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateQualificationTypeResponseTypeDef = TypedDict(
     "CreateQualificationTypeResponseTypeDef",
     {
         "QualificationType": QualificationTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQualificationTypeResponseTypeDef = TypedDict(
     "GetQualificationTypeResponseTypeDef",
     {
         "QualificationType": QualificationTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQualificationTypesResponseTypeDef = TypedDict(
     "ListQualificationTypesResponseTypeDef",
     {
         "NumResults": int,
         "NextToken": str,
         "QualificationTypes": List[QualificationTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateQualificationTypeResponseTypeDef = TypedDict(
     "UpdateQualificationTypeResponseTypeDef",
     {
         "QualificationType": QualificationTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
-    "_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
-    {
-        "HITId": str,
-    },
-)
-_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
-    "_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
-    {
-        "AssignmentStatuses": Sequence[AssignmentStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef(
-    _RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
-    _OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
-):
-    pass
-
-
-ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef = TypedDict(
-    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
-    {
-        "HITId": str,
-        "AssignmentId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
-    "_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
-    {
-        "QualificationTypeId": str,
-    },
-)
-_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
-    "_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef(
-    _RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
-    _OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
-):
-    pass
-
-
-ListHITsRequestListHITsPaginateTypeDef = TypedDict(
-    "ListHITsRequestListHITsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef = TypedDict(
-    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
-    {
-        "QualificationTypeId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
-    "_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
-    {
-        "MustBeRequestable": bool,
-    },
-)
-_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
-    "_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
-    {
-        "Query": str,
-        "MustBeOwnedByCaller": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListQualificationTypesRequestListQualificationTypesPaginateTypeDef(
-    _RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
-    _OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
-):
-    pass
-
-
-ListReviewableHITsRequestListReviewableHITsPaginateTypeDef = TypedDict(
-    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
-    {
-        "HITTypeId": str,
-        "Status": ReviewableHITStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef = TypedDict(
-    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
-    "_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
-    {
-        "QualificationTypeId": str,
-    },
-)
-_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
-    "_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
-    {
-        "Status": QualificationStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef(
-    _RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
-    _OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
-):
-    pass
-
-
 ListQualificationRequestsResponseTypeDef = TypedDict(
     "ListQualificationRequestsResponseTypeDef",
     {
         "NumResults": int,
         "NextToken": str,
         "QualificationRequests": List[QualificationRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkerBlocksResponseTypeDef = TypedDict(
     "ListWorkerBlocksResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "WorkerBlocks": List[WorkerBlockTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredQualificationRequirementTypeDef = TypedDict(
     "_RequiredQualificationRequirementTypeDef",
     {
         "QualificationTypeId": str,
@@ -1138,15 +1138,15 @@
     pass
 
 
 NotifyWorkersResponseTypeDef = TypedDict(
     "NotifyWorkersResponseTypeDef",
     {
         "NotifyWorkersFailureStatuses": List[NotifyWorkersFailureStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyParameterTypeDef = TypedDict(
     "PolicyParameterTypeDef",
     {
         "Key": str,
@@ -1219,25 +1219,25 @@
     total=False,
 )
 
 GetQualificationScoreResponseTypeDef = TypedDict(
     "GetQualificationScoreResponseTypeDef",
     {
         "Qualification": QualificationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkersWithQualificationTypeResponseTypeDef = TypedDict(
     "ListWorkersWithQualificationTypeResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "Qualifications": List[QualificationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredReviewPolicyTypeDef = TypedDict(
     "_RequiredReviewPolicyTypeDef",
     {
         "PolicyName": str,
@@ -1256,70 +1256,70 @@
     pass
 
 
 CreateHITResponseTypeDef = TypedDict(
     "CreateHITResponseTypeDef",
     {
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHITWithHITTypeResponseTypeDef = TypedDict(
     "CreateHITWithHITTypeResponseTypeDef",
     {
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssignmentResponseTypeDef = TypedDict(
     "GetAssignmentResponseTypeDef",
     {
         "Assignment": AssignmentTypeDef,
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHITResponseTypeDef = TypedDict(
     "GetHITResponseTypeDef",
     {
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHITsForQualificationTypeResponseTypeDef = TypedDict(
     "ListHITsForQualificationTypeResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "HITs": List[HITTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHITsResponseTypeDef = TypedDict(
     "ListHITsResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "HITs": List[HITTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReviewableHITsResponseTypeDef = TypedDict(
     "ListReviewableHITsResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "HITs": List[HITTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateHITRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHITRequestRequestTypeDef",
     {
         "LifetimeInSeconds": int,
@@ -1389,10 +1389,10 @@
     {
         "HITId": str,
         "AssignmentReviewPolicy": ReviewPolicyTypeDef,
         "HITReviewPolicy": ReviewPolicyTypeDef,
         "AssignmentReviewReport": ReviewReportTypeDef,
         "HITReviewReport": ReviewReportTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk/type_defs.pyi` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -40,72 +40,72 @@
     "AcceptQualificationRequestRequestRequestTypeDef",
     "ApproveAssignmentRequestRequestTypeDef",
     "AssignmentTypeDef",
     "AssociateQualificationWithWorkerRequestRequestTypeDef",
     "BonusPaymentTypeDef",
     "CreateAdditionalAssignmentsForHITRequestRequestTypeDef",
     "HITLayoutParameterTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateHITTypeResponseTypeDef",
     "CreateQualificationTypeRequestRequestTypeDef",
     "QualificationTypeTypeDef",
     "CreateWorkerBlockRequestRequestTypeDef",
     "DeleteHITRequestRequestTypeDef",
     "DeleteQualificationTypeRequestRequestTypeDef",
     "DeleteWorkerBlockRequestRequestTypeDef",
     "DisassociateQualificationFromWorkerRequestRequestTypeDef",
+    "GetAccountBalanceResponseTypeDef",
     "GetAssignmentRequestRequestTypeDef",
     "GetFileUploadURLRequestRequestTypeDef",
+    "GetFileUploadURLResponseTypeDef",
     "GetHITRequestRequestTypeDef",
     "GetQualificationScoreRequestRequestTypeDef",
     "GetQualificationTypeRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
     "ListAssignmentsForHITRequestRequestTypeDef",
+    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
     "ListBonusPaymentsRequestRequestTypeDef",
+    "ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
     "ListHITsForQualificationTypeRequestRequestTypeDef",
+    "ListHITsRequestListHITsPaginateTypeDef",
     "ListHITsRequestRequestTypeDef",
+    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
     "ListQualificationRequestsRequestRequestTypeDef",
     "QualificationRequestTypeDef",
+    "ListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
     "ListQualificationTypesRequestRequestTypeDef",
     "ListReviewPolicyResultsForHITRequestRequestTypeDef",
+    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
     "ListReviewableHITsRequestRequestTypeDef",
+    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
     "ListWorkerBlocksRequestRequestTypeDef",
     "WorkerBlockTypeDef",
+    "ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
     "ListWorkersWithQualificationTypeRequestRequestTypeDef",
     "LocaleTypeDef",
     "NotificationSpecificationTypeDef",
     "NotifyWorkersFailureStatusTypeDef",
     "NotifyWorkersRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ParameterMapEntryTypeDef",
     "RejectAssignmentRequestRequestTypeDef",
     "RejectQualificationRequestRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ReviewActionDetailTypeDef",
     "ReviewResultDetailTypeDef",
     "SendBonusRequestRequestTypeDef",
     "UpdateExpirationForHITRequestRequestTypeDef",
     "UpdateHITReviewStatusRequestRequestTypeDef",
     "UpdateHITTypeOfHITRequestRequestTypeDef",
     "UpdateQualificationTypeRequestRequestTypeDef",
-    "CreateHITTypeResponseTypeDef",
-    "GetAccountBalanceResponseTypeDef",
-    "GetFileUploadURLResponseTypeDef",
     "ListAssignmentsForHITResponseTypeDef",
     "ListBonusPaymentsResponseTypeDef",
     "CreateQualificationTypeResponseTypeDef",
     "GetQualificationTypeResponseTypeDef",
     "ListQualificationTypesResponseTypeDef",
     "UpdateQualificationTypeResponseTypeDef",
-    "ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
-    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
-    "ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
-    "ListHITsRequestListHITsPaginateTypeDef",
-    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
-    "ListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
-    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
-    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
-    "ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
     "ListQualificationRequestsResponseTypeDef",
     "ListWorkerBlocksResponseTypeDef",
     "QualificationRequirementTypeDef",
     "QualificationTypeDef",
     "SendTestEventNotificationRequestRequestTypeDef",
     "UpdateNotificationSettingsRequestRequestTypeDef",
     "NotifyWorkersResponseTypeDef",
@@ -246,22 +246,19 @@
     "HITLayoutParameterTypeDef",
     {
         "Name": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateHITTypeResponseTypeDef = TypedDict(
+    "CreateHITTypeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "HITTypeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateQualificationTypeRequestRequestTypeDef = TypedDict(
     "_RequiredCreateQualificationTypeRequestRequestTypeDef",
     {
         "Name": str,
@@ -367,14 +364,23 @@
 
 class DisassociateQualificationFromWorkerRequestRequestTypeDef(
     _RequiredDisassociateQualificationFromWorkerRequestRequestTypeDef,
     _OptionalDisassociateQualificationFromWorkerRequestRequestTypeDef,
 ):
     pass
 
+GetAccountBalanceResponseTypeDef = TypedDict(
+    "GetAccountBalanceResponseTypeDef",
+    {
+        "AvailableBalance": str,
+        "OnHoldBalance": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAssignmentRequestRequestTypeDef = TypedDict(
     "GetAssignmentRequestRequestTypeDef",
     {
         "AssignmentId": str,
     },
 )
 
@@ -382,14 +388,22 @@
     "GetFileUploadURLRequestRequestTypeDef",
     {
         "AssignmentId": str,
         "QuestionIdentifier": str,
     },
 )
 
+GetFileUploadURLResponseTypeDef = TypedDict(
+    "GetFileUploadURLResponseTypeDef",
+    {
+        "FileUploadURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHITRequestRequestTypeDef = TypedDict(
     "GetHITRequestRequestTypeDef",
     {
         "HITId": str,
     },
 )
 
@@ -404,24 +418,35 @@
 GetQualificationTypeRequestRequestTypeDef = TypedDict(
     "GetQualificationTypeRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
+    "_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "HITId": str,
+    },
+)
+_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
+    "_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
+    {
+        "AssignmentStatuses": Sequence[AssignmentStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef(
+    _RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
+    _OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssignmentsForHITRequestRequestTypeDef = TypedDict(
     "_RequiredListAssignmentsForHITRequestRequestTypeDef",
     {
         "HITId": str,
     },
 )
 _OptionalListAssignmentsForHITRequestRequestTypeDef = TypedDict(
@@ -436,25 +461,55 @@
 
 class ListAssignmentsForHITRequestRequestTypeDef(
     _RequiredListAssignmentsForHITRequestRequestTypeDef,
     _OptionalListAssignmentsForHITRequestRequestTypeDef,
 ):
     pass
 
+ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef = TypedDict(
+    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
+    {
+        "HITId": str,
+        "AssignmentId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBonusPaymentsRequestRequestTypeDef = TypedDict(
     "ListBonusPaymentsRequestRequestTypeDef",
     {
         "HITId": str,
         "AssignmentId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
+    "_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
+    {
+        "QualificationTypeId": str,
+    },
+)
+_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
+    "_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef(
+    _RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
+    _OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
+):
+    pass
+
 _RequiredListHITsForQualificationTypeRequestRequestTypeDef = TypedDict(
     "_RequiredListHITsForQualificationTypeRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
     },
 )
 _OptionalListHITsForQualificationTypeRequestRequestTypeDef = TypedDict(
@@ -468,23 +523,40 @@
 
 class ListHITsForQualificationTypeRequestRequestTypeDef(
     _RequiredListHITsForQualificationTypeRequestRequestTypeDef,
     _OptionalListHITsForQualificationTypeRequestRequestTypeDef,
 ):
     pass
 
+ListHITsRequestListHITsPaginateTypeDef = TypedDict(
+    "ListHITsRequestListHITsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListHITsRequestRequestTypeDef = TypedDict(
     "ListHITsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef = TypedDict(
+    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
+    {
+        "QualificationTypeId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListQualificationRequestsRequestRequestTypeDef = TypedDict(
     "ListQualificationRequestsRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -500,14 +572,36 @@
         "Test": str,
         "Answer": str,
         "SubmitTime": datetime,
     },
     total=False,
 )
 
+_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
+    "_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
+    {
+        "MustBeRequestable": bool,
+    },
+)
+_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
+    "_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
+    {
+        "Query": str,
+        "MustBeOwnedByCaller": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListQualificationTypesRequestListQualificationTypesPaginateTypeDef(
+    _RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
+    _OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
+):
+    pass
+
 _RequiredListQualificationTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListQualificationTypesRequestRequestTypeDef",
     {
         "MustBeRequestable": bool,
     },
 )
 _OptionalListQualificationTypesRequestRequestTypeDef = TypedDict(
@@ -547,25 +641,43 @@
 
 class ListReviewPolicyResultsForHITRequestRequestTypeDef(
     _RequiredListReviewPolicyResultsForHITRequestRequestTypeDef,
     _OptionalListReviewPolicyResultsForHITRequestRequestTypeDef,
 ):
     pass
 
+ListReviewableHITsRequestListReviewableHITsPaginateTypeDef = TypedDict(
+    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
+    {
+        "HITTypeId": str,
+        "Status": ReviewableHITStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReviewableHITsRequestRequestTypeDef = TypedDict(
     "ListReviewableHITsRequestRequestTypeDef",
     {
         "HITTypeId": str,
         "Status": ReviewableHITStatusType,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef = TypedDict(
+    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListWorkerBlocksRequestRequestTypeDef = TypedDict(
     "ListWorkerBlocksRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -576,14 +688,35 @@
     {
         "WorkerId": str,
         "Reason": str,
     },
     total=False,
 )
 
+_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
+    "_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
+    {
+        "QualificationTypeId": str,
+    },
+)
+_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
+    "_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
+    {
+        "Status": QualificationStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef(
+    _RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
+    _OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
+):
+    pass
+
 _RequiredListWorkersWithQualificationTypeRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkersWithQualificationTypeRequestRequestTypeDef",
     {
         "QualificationTypeId": str,
     },
 )
 _OptionalListWorkersWithQualificationTypeRequestRequestTypeDef = TypedDict(
@@ -644,14 +777,24 @@
     {
         "Subject": str,
         "MessageText": str,
         "WorkerIds": Sequence[str],
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
 ParameterMapEntryTypeDef = TypedDict(
     "ParameterMapEntryTypeDef",
     {
         "Key": str,
         "Values": Sequence[str],
     },
     total=False,
@@ -681,14 +824,25 @@
 
 class RejectQualificationRequestRequestRequestTypeDef(
     _RequiredRejectQualificationRequestRequestRequestTypeDef,
     _OptionalRejectQualificationRequestRequestRequestTypeDef,
 ):
     pass
 
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
 ReviewActionDetailTypeDef = TypedDict(
     "ReviewActionDetailTypeDef",
     {
         "ActionId": str,
         "ActionName": str,
         "TargetId": str,
         "TargetType": str,
@@ -794,239 +948,85 @@
 
 class UpdateQualificationTypeRequestRequestTypeDef(
     _RequiredUpdateQualificationTypeRequestRequestTypeDef,
     _OptionalUpdateQualificationTypeRequestRequestTypeDef,
 ):
     pass
 
-CreateHITTypeResponseTypeDef = TypedDict(
-    "CreateHITTypeResponseTypeDef",
-    {
-        "HITTypeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountBalanceResponseTypeDef = TypedDict(
-    "GetAccountBalanceResponseTypeDef",
-    {
-        "AvailableBalance": str,
-        "OnHoldBalance": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFileUploadURLResponseTypeDef = TypedDict(
-    "GetFileUploadURLResponseTypeDef",
-    {
-        "FileUploadURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListAssignmentsForHITResponseTypeDef = TypedDict(
     "ListAssignmentsForHITResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "Assignments": List[AssignmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBonusPaymentsResponseTypeDef = TypedDict(
     "ListBonusPaymentsResponseTypeDef",
     {
         "NumResults": int,
         "NextToken": str,
         "BonusPayments": List[BonusPaymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateQualificationTypeResponseTypeDef = TypedDict(
     "CreateQualificationTypeResponseTypeDef",
     {
         "QualificationType": QualificationTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetQualificationTypeResponseTypeDef = TypedDict(
     "GetQualificationTypeResponseTypeDef",
     {
         "QualificationType": QualificationTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQualificationTypesResponseTypeDef = TypedDict(
     "ListQualificationTypesResponseTypeDef",
     {
         "NumResults": int,
         "NextToken": str,
         "QualificationTypes": List[QualificationTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateQualificationTypeResponseTypeDef = TypedDict(
     "UpdateQualificationTypeResponseTypeDef",
     {
         "QualificationType": QualificationTypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
-    "_RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
-    {
-        "HITId": str,
-    },
-)
-_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef = TypedDict(
-    "_OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef",
-    {
-        "AssignmentStatuses": Sequence[AssignmentStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef(
-    _RequiredListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
-    _OptionalListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
-):
-    pass
-
-ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef = TypedDict(
-    "ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef",
-    {
-        "HITId": str,
-        "AssignmentId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
-    "_RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
-    {
-        "QualificationTypeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef = TypedDict(
-    "_OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef(
-    _RequiredListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
-    _OptionalListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
-):
-    pass
-
-ListHITsRequestListHITsPaginateTypeDef = TypedDict(
-    "ListHITsRequestListHITsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef = TypedDict(
-    "ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef",
-    {
-        "QualificationTypeId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
-    "_RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
-    {
-        "MustBeRequestable": bool,
-    },
-)
-_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef = TypedDict(
-    "_OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef",
-    {
-        "Query": str,
-        "MustBeOwnedByCaller": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListQualificationTypesRequestListQualificationTypesPaginateTypeDef(
-    _RequiredListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
-    _OptionalListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
-):
-    pass
-
-ListReviewableHITsRequestListReviewableHITsPaginateTypeDef = TypedDict(
-    "ListReviewableHITsRequestListReviewableHITsPaginateTypeDef",
-    {
-        "HITTypeId": str,
-        "Status": ReviewableHITStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef = TypedDict(
-    "ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
-    "_RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
-    {
-        "QualificationTypeId": str,
-    },
-)
-_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef = TypedDict(
-    "_OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef",
-    {
-        "Status": QualificationStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef(
-    _RequiredListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
-    _OptionalListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
-):
-    pass
 
 ListQualificationRequestsResponseTypeDef = TypedDict(
     "ListQualificationRequestsResponseTypeDef",
     {
         "NumResults": int,
         "NextToken": str,
         "QualificationRequests": List[QualificationRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkerBlocksResponseTypeDef = TypedDict(
     "ListWorkerBlocksResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "WorkerBlocks": List[WorkerBlockTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredQualificationRequirementTypeDef = TypedDict(
     "_RequiredQualificationRequirementTypeDef",
     {
         "QualificationTypeId": str,
@@ -1091,15 +1091,15 @@
 ):
     pass
 
 NotifyWorkersResponseTypeDef = TypedDict(
     "NotifyWorkersResponseTypeDef",
     {
         "NotifyWorkersFailureStatuses": List[NotifyWorkersFailureStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyParameterTypeDef = TypedDict(
     "PolicyParameterTypeDef",
     {
         "Key": str,
@@ -1170,25 +1170,25 @@
     total=False,
 )
 
 GetQualificationScoreResponseTypeDef = TypedDict(
     "GetQualificationScoreResponseTypeDef",
     {
         "Qualification": QualificationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkersWithQualificationTypeResponseTypeDef = TypedDict(
     "ListWorkersWithQualificationTypeResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "Qualifications": List[QualificationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredReviewPolicyTypeDef = TypedDict(
     "_RequiredReviewPolicyTypeDef",
     {
         "PolicyName": str,
@@ -1205,70 +1205,70 @@
 class ReviewPolicyTypeDef(_RequiredReviewPolicyTypeDef, _OptionalReviewPolicyTypeDef):
     pass
 
 CreateHITResponseTypeDef = TypedDict(
     "CreateHITResponseTypeDef",
     {
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHITWithHITTypeResponseTypeDef = TypedDict(
     "CreateHITWithHITTypeResponseTypeDef",
     {
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssignmentResponseTypeDef = TypedDict(
     "GetAssignmentResponseTypeDef",
     {
         "Assignment": AssignmentTypeDef,
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetHITResponseTypeDef = TypedDict(
     "GetHITResponseTypeDef",
     {
         "HIT": HITTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHITsForQualificationTypeResponseTypeDef = TypedDict(
     "ListHITsForQualificationTypeResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "HITs": List[HITTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListHITsResponseTypeDef = TypedDict(
     "ListHITsResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "HITs": List[HITTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReviewableHITsResponseTypeDef = TypedDict(
     "ListReviewableHITsResponseTypeDef",
     {
         "NextToken": str,
         "NumResults": int,
         "HITs": List[HITTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateHITRequestRequestTypeDef = TypedDict(
     "_RequiredCreateHITRequestRequestTypeDef",
     {
         "LifetimeInSeconds": int,
@@ -1334,10 +1334,10 @@
     {
         "HITId": str,
         "AssignmentReviewPolicy": ReviewPolicyTypeDef,
         "HITReviewPolicy": ReviewPolicyTypeDef,
         "AssignmentReviewReport": ReviewReportTypeDef,
         "HITReviewReport": ReviewReportTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/PKG-INFO` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mturk
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MTurk 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MTurk 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mturk"></a>
 
 # types-aiobotocore-mturk
 
 [![PyPI - types-aiobotocore-mturk](https://img.shields.io/pypi/v/types-aiobotocore-mturk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mturk)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mturk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mturk)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mturk?color=blue)](https://pypistats.org/packages/types-aiobotocore-mturk)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MTurk 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk)
+[aiobotocore.MTurk 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mturk.html#MTurk)
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
 [types-aiobotocore-mturk docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mturk/).
 
 See how it helps to find and fix potential bugs:
 
@@ -374,72 +374,72 @@
     AcceptQualificationRequestRequestRequestTypeDef,
     ApproveAssignmentRequestRequestTypeDef,
     AssignmentTypeDef,
     AssociateQualificationWithWorkerRequestRequestTypeDef,
     BonusPaymentTypeDef,
     CreateAdditionalAssignmentsForHITRequestRequestTypeDef,
     HITLayoutParameterTypeDef,
-    ResponseMetadataTypeDef,
+    CreateHITTypeResponseTypeDef,
     CreateQualificationTypeRequestRequestTypeDef,
     QualificationTypeTypeDef,
     CreateWorkerBlockRequestRequestTypeDef,
     DeleteHITRequestRequestTypeDef,
     DeleteQualificationTypeRequestRequestTypeDef,
     DeleteWorkerBlockRequestRequestTypeDef,
     DisassociateQualificationFromWorkerRequestRequestTypeDef,
+    GetAccountBalanceResponseTypeDef,
     GetAssignmentRequestRequestTypeDef,
     GetFileUploadURLRequestRequestTypeDef,
+    GetFileUploadURLResponseTypeDef,
     GetHITRequestRequestTypeDef,
     GetQualificationScoreRequestRequestTypeDef,
     GetQualificationTypeRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
     ListAssignmentsForHITRequestRequestTypeDef,
+    ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef,
     ListBonusPaymentsRequestRequestTypeDef,
+    ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
     ListHITsForQualificationTypeRequestRequestTypeDef,
+    ListHITsRequestListHITsPaginateTypeDef,
     ListHITsRequestRequestTypeDef,
+    ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef,
     ListQualificationRequestsRequestRequestTypeDef,
     QualificationRequestTypeDef,
+    ListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
     ListQualificationTypesRequestRequestTypeDef,
     ListReviewPolicyResultsForHITRequestRequestTypeDef,
+    ListReviewableHITsRequestListReviewableHITsPaginateTypeDef,
     ListReviewableHITsRequestRequestTypeDef,
+    ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef,
     ListWorkerBlocksRequestRequestTypeDef,
     WorkerBlockTypeDef,
+    ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
     ListWorkersWithQualificationTypeRequestRequestTypeDef,
     LocaleTypeDef,
     NotificationSpecificationTypeDef,
     NotifyWorkersFailureStatusTypeDef,
     NotifyWorkersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ParameterMapEntryTypeDef,
     RejectAssignmentRequestRequestTypeDef,
     RejectQualificationRequestRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ReviewActionDetailTypeDef,
     ReviewResultDetailTypeDef,
     SendBonusRequestRequestTypeDef,
     UpdateExpirationForHITRequestRequestTypeDef,
     UpdateHITReviewStatusRequestRequestTypeDef,
     UpdateHITTypeOfHITRequestRequestTypeDef,
     UpdateQualificationTypeRequestRequestTypeDef,
-    CreateHITTypeResponseTypeDef,
-    GetAccountBalanceResponseTypeDef,
-    GetFileUploadURLResponseTypeDef,
     ListAssignmentsForHITResponseTypeDef,
     ListBonusPaymentsResponseTypeDef,
     CreateQualificationTypeResponseTypeDef,
     GetQualificationTypeResponseTypeDef,
     ListQualificationTypesResponseTypeDef,
     UpdateQualificationTypeResponseTypeDef,
-    ListAssignmentsForHITRequestListAssignmentsForHITPaginateTypeDef,
-    ListBonusPaymentsRequestListBonusPaymentsPaginateTypeDef,
-    ListHITsForQualificationTypeRequestListHITsForQualificationTypePaginateTypeDef,
-    ListHITsRequestListHITsPaginateTypeDef,
-    ListQualificationRequestsRequestListQualificationRequestsPaginateTypeDef,
-    ListQualificationTypesRequestListQualificationTypesPaginateTypeDef,
-    ListReviewableHITsRequestListReviewableHITsPaginateTypeDef,
-    ListWorkerBlocksRequestListWorkerBlocksPaginateTypeDef,
-    ListWorkersWithQualificationTypeRequestListWorkersWithQualificationTypePaginateTypeDef,
     ListQualificationRequestsResponseTypeDef,
     ListWorkerBlocksResponseTypeDef,
     QualificationRequirementTypeDef,
     QualificationTypeDef,
     SendTestEventNotificationRequestRequestTypeDef,
     UpdateNotificationSettingsRequestRequestTypeDef,
     NotifyWorkersResponseTypeDef,
@@ -470,43 +470,43 @@
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

### Comparing `types-aiobotocore-mturk-2.5.0.post1/types_aiobotocore_mturk.egg-info/SOURCES.txt` & `types-aiobotocore-mturk-2.5.1/types_aiobotocore_mturk.egg-info/SOURCES.txt`

 * *Files identical despite different names*

