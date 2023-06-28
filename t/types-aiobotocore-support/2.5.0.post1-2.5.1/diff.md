# Comparing `tmp/types-aiobotocore-support-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-support-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-support-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:25 2023, max compression
+gzip compressed data, was "types-aiobotocore-support-2.5.1.tar", last modified: Wed Jun 28 01:44:16 2023, max compression
```

## Comparing `types-aiobotocore-support-2.5.0.post1.tar` & `types-aiobotocore-support-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.807679 types-aiobotocore-support-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15035 2023-03-11 12:27:25.807679 types-aiobotocore-support-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13464 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:25.807679 types-aiobotocore-support-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.807679 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/
--rw-r--r--   0 runner    (1001) docker     (123)      871 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14804 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14779 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7629 2023-03-11 12:24:55.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7627 2023-03-11 12:24:55.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3619 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3614 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    16582 2023-03-11 12:24:55.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    16565 2023-03-11 12:24:55.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:54.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:25.807679 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15035 2023-03-11 12:27:25.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-11 12:27:25.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:27:25.000000 types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.126224 types-aiobotocore-support-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15343 2023-06-28 01:44:16.126224 types-aiobotocore-support-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13778 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:16.126224 types-aiobotocore-support-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.126224 types-aiobotocore-support-2.5.1/types_aiobotocore_support/
+-rw-r--r--   0 runner    (1001) docker     (123)      871 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16246 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16219 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7838 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7836 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3503 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3499 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    18634 2023-06-28 01:41:44.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18617 2023-06-28 01:41:44.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:43.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.126224 types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15343 2023-06-28 01:44:15.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:44:15.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:15.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:15.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:15.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:44:15.000000 types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-support-2.5.0.post1/LICENSE` & `types-aiobotocore-support-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-support-2.5.0.post1/PKG-INFO` & `types-aiobotocore-support-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-support
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Support 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Support 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-support"></a>
 
 # types-aiobotocore-support
 
 [![PyPI - types-aiobotocore-support](https://img.shields.io/pypi/v/types-aiobotocore-support.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-support.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-support?color=blue)](https://pypistats.org/packages/types-aiobotocore-support)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Support 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support)
+[aiobotocore.Support 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support)
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
 [types-aiobotocore-support docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,55 +320,63 @@
 
 `types_aiobotocore_support.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_support.type_defs import (
     AttachmentTypeDef,
-    ResponseMetadataTypeDef,
+    AddAttachmentsToSetResponseTypeDef,
     AddCommunicationToCaseRequestRequestTypeDef,
+    AddCommunicationToCaseResponseTypeDef,
     AttachmentDetailsTypeDef,
     CategoryTypeDef,
+    DateIntervalTypeDef,
+    SupportedHourTypeDef,
     CreateCaseRequestRequestTypeDef,
+    CreateCaseResponseTypeDef,
     DescribeAttachmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCasesRequestDescribeCasesPaginateTypeDef,
     DescribeCasesRequestRequestTypeDef,
+    DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
     DescribeCommunicationsRequestRequestTypeDef,
+    DescribeCreateCaseOptionsRequestRequestTypeDef,
     DescribeServicesRequestRequestTypeDef,
     DescribeSeverityLevelsRequestRequestTypeDef,
     SeverityLevelTypeDef,
+    DescribeSupportedLanguagesRequestRequestTypeDef,
+    SupportedLanguageTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef,
     TrustedAdvisorCheckRefreshStatusTypeDef,
     DescribeTrustedAdvisorCheckResultRequestRequestTypeDef,
     DescribeTrustedAdvisorCheckSummariesRequestRequestTypeDef,
     DescribeTrustedAdvisorChecksRequestRequestTypeDef,
     TrustedAdvisorCheckDescriptionTypeDef,
+    PaginatorConfigTypeDef,
     RefreshTrustedAdvisorCheckRequestRequestTypeDef,
     ResolveCaseRequestRequestTypeDef,
+    ResolveCaseResponseTypeDef,
+    ResponseMetadataTypeDef,
     TrustedAdvisorCostOptimizingSummaryTypeDef,
     TrustedAdvisorResourceDetailTypeDef,
     TrustedAdvisorResourcesSummaryTypeDef,
     AddAttachmentsToSetRequestRequestTypeDef,
-    AddAttachmentsToSetResponseTypeDef,
-    AddCommunicationToCaseResponseTypeDef,
-    CreateCaseResponseTypeDef,
     DescribeAttachmentResponseTypeDef,
-    ResolveCaseResponseTypeDef,
     CommunicationTypeDef,
     ServiceTypeDef,
-    DescribeCasesRequestDescribeCasesPaginateTypeDef,
-    DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
+    CommunicationTypeOptionsTypeDef,
     DescribeSeverityLevelsResponseTypeDef,
+    DescribeSupportedLanguagesResponseTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef,
     RefreshTrustedAdvisorCheckResponseTypeDef,
     DescribeTrustedAdvisorChecksResponseTypeDef,
     TrustedAdvisorCategorySpecificSummaryTypeDef,
     DescribeCommunicationsResponseTypeDef,
     RecentCaseCommunicationsTypeDef,
     DescribeServicesResponseTypeDef,
+    DescribeCreateCaseOptionsResponseTypeDef,
     TrustedAdvisorCheckResultTypeDef,
     TrustedAdvisorCheckSummaryTypeDef,
     CaseDetailsTypeDef,
     DescribeTrustedAdvisorCheckResultResponseTypeDef,
     DescribeTrustedAdvisorCheckSummariesResponseTypeDef,
     DescribeCasesResponseTypeDef,
 )
@@ -381,43 +389,43 @@
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

### Comparing `types-aiobotocore-support-2.5.0.post1/README.md` & `types-aiobotocore-support-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-support"></a>
 
 # types-aiobotocore-support
 
 [![PyPI - types-aiobotocore-support](https://img.shields.io/pypi/v/types-aiobotocore-support.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-support.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-support?color=blue)](https://pypistats.org/packages/types-aiobotocore-support)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Support 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support)
+[aiobotocore.Support 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support)
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
 [types-aiobotocore-support docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,55 +287,63 @@
 
 `types_aiobotocore_support.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_support.type_defs import (
     AttachmentTypeDef,
-    ResponseMetadataTypeDef,
+    AddAttachmentsToSetResponseTypeDef,
     AddCommunicationToCaseRequestRequestTypeDef,
+    AddCommunicationToCaseResponseTypeDef,
     AttachmentDetailsTypeDef,
     CategoryTypeDef,
+    DateIntervalTypeDef,
+    SupportedHourTypeDef,
     CreateCaseRequestRequestTypeDef,
+    CreateCaseResponseTypeDef,
     DescribeAttachmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCasesRequestDescribeCasesPaginateTypeDef,
     DescribeCasesRequestRequestTypeDef,
+    DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
     DescribeCommunicationsRequestRequestTypeDef,
+    DescribeCreateCaseOptionsRequestRequestTypeDef,
     DescribeServicesRequestRequestTypeDef,
     DescribeSeverityLevelsRequestRequestTypeDef,
     SeverityLevelTypeDef,
+    DescribeSupportedLanguagesRequestRequestTypeDef,
+    SupportedLanguageTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef,
     TrustedAdvisorCheckRefreshStatusTypeDef,
     DescribeTrustedAdvisorCheckResultRequestRequestTypeDef,
     DescribeTrustedAdvisorCheckSummariesRequestRequestTypeDef,
     DescribeTrustedAdvisorChecksRequestRequestTypeDef,
     TrustedAdvisorCheckDescriptionTypeDef,
+    PaginatorConfigTypeDef,
     RefreshTrustedAdvisorCheckRequestRequestTypeDef,
     ResolveCaseRequestRequestTypeDef,
+    ResolveCaseResponseTypeDef,
+    ResponseMetadataTypeDef,
     TrustedAdvisorCostOptimizingSummaryTypeDef,
     TrustedAdvisorResourceDetailTypeDef,
     TrustedAdvisorResourcesSummaryTypeDef,
     AddAttachmentsToSetRequestRequestTypeDef,
-    AddAttachmentsToSetResponseTypeDef,
-    AddCommunicationToCaseResponseTypeDef,
-    CreateCaseResponseTypeDef,
     DescribeAttachmentResponseTypeDef,
-    ResolveCaseResponseTypeDef,
     CommunicationTypeDef,
     ServiceTypeDef,
-    DescribeCasesRequestDescribeCasesPaginateTypeDef,
-    DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
+    CommunicationTypeOptionsTypeDef,
     DescribeSeverityLevelsResponseTypeDef,
+    DescribeSupportedLanguagesResponseTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef,
     RefreshTrustedAdvisorCheckResponseTypeDef,
     DescribeTrustedAdvisorChecksResponseTypeDef,
     TrustedAdvisorCategorySpecificSummaryTypeDef,
     DescribeCommunicationsResponseTypeDef,
     RecentCaseCommunicationsTypeDef,
     DescribeServicesResponseTypeDef,
+    DescribeCreateCaseOptionsResponseTypeDef,
     TrustedAdvisorCheckResultTypeDef,
     TrustedAdvisorCheckSummaryTypeDef,
     CaseDetailsTypeDef,
     DescribeTrustedAdvisorCheckResultResponseTypeDef,
     DescribeTrustedAdvisorCheckSummariesResponseTypeDef,
     DescribeCasesResponseTypeDef,
 )
@@ -348,43 +356,43 @@
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

### Comparing `types-aiobotocore-support-2.5.0.post1/setup.py` & `types-aiobotocore-support-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-support.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-support",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_support"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Support 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Support 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/"
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

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/__init__.py` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/__init__.pyi` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/__main__.py` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Support 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Support 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support\nOther"
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

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/client.py` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -25,53 +25,52 @@
     AddAttachmentsToSetResponseTypeDef,
     AddCommunicationToCaseResponseTypeDef,
     AttachmentTypeDef,
     CreateCaseResponseTypeDef,
     DescribeAttachmentResponseTypeDef,
     DescribeCasesResponseTypeDef,
     DescribeCommunicationsResponseTypeDef,
+    DescribeCreateCaseOptionsResponseTypeDef,
     DescribeServicesResponseTypeDef,
     DescribeSeverityLevelsResponseTypeDef,
+    DescribeSupportedLanguagesResponseTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef,
     DescribeTrustedAdvisorCheckResultResponseTypeDef,
     DescribeTrustedAdvisorChecksResponseTypeDef,
     DescribeTrustedAdvisorCheckSummariesResponseTypeDef,
     RefreshTrustedAdvisorCheckResponseTypeDef,
     ResolveCaseResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("SupportClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AttachmentIdNotFound: Type[BotocoreClientError]
     AttachmentLimitExceeded: Type[BotocoreClientError]
     AttachmentSetExpired: Type[BotocoreClientError]
     AttachmentSetIdNotFound: Type[BotocoreClientError]
     AttachmentSetSizeLimitExceeded: Type[BotocoreClientError]
     CaseCreationLimitExceeded: Type[BotocoreClientError]
     CaseIdNotFound: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     DescribeAttachmentLimitExceeded: Type[BotocoreClientError]
     InternalServerError: Type[BotocoreClientError]
-
+    ThrottlingException: Type[BotocoreClientError]
 
 class SupportClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/)
     """
 
@@ -81,56 +80,51 @@
     def exceptions(self) -> Exceptions:
         """
         SupportClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#exceptions)
         """
-
     async def add_attachments_to_set(
         self, *, attachments: Sequence[AttachmentTypeDef], attachmentSetId: str = ...
     ) -> AddAttachmentsToSetResponseTypeDef:
         """
         Adds one or more attachments to an attachment set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.add_attachments_to_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#add_attachments_to_set)
         """
-
     async def add_communication_to_case(
         self,
         *,
         communicationBody: str,
         caseId: str = ...,
         ccEmailAddresses: Sequence[str] = ...,
         attachmentSetId: str = ...
     ) -> AddCommunicationToCaseResponseTypeDef:
         """
         Adds additional customer communication to an Amazon Web Services Support case.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.add_communication_to_case)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#add_communication_to_case)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#close)
         """
-
     async def create_case(
         self,
         *,
         subject: str,
         communicationBody: str,
         serviceCode: str = ...,
         severityCode: str = ...,
@@ -142,23 +136,21 @@
     ) -> CreateCaseResponseTypeDef:
         """
         Creates a case in the Amazon Web Services Support Center.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.create_case)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#create_case)
         """
-
     async def describe_attachment(self, *, attachmentId: str) -> DescribeAttachmentResponseTypeDef:
         """
         Returns the attachment that has the specified ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_attachment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_attachment)
         """
-
     async def describe_cases(
         self,
         *,
         caseIdList: Sequence[str] = ...,
         displayId: str = ...,
         afterTime: str = ...,
         beforeTime: str = ...,
@@ -170,15 +162,14 @@
     ) -> DescribeCasesResponseTypeDef:
         """
         Returns a list of cases that you specify by passing one or more case IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_cases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_cases)
         """
-
     async def describe_communications(
         self,
         *,
         caseId: str,
         beforeTime: str = ...,
         afterTime: str = ...,
         nextToken: str = ...,
@@ -186,132 +177,139 @@
     ) -> DescribeCommunicationsResponseTypeDef:
         """
         Returns communications and attachments for one or more support cases.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_communications)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_communications)
         """
+    async def describe_create_case_options(
+        self, *, issueType: str, serviceCode: str, language: str, categoryCode: str
+    ) -> DescribeCreateCaseOptionsResponseTypeDef:
+        """
+        Returns a list of CreateCaseOption types along with the corresponding supported
+        hours and language availability.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_create_case_options)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_create_case_options)
+        """
     async def describe_services(
         self, *, serviceCodeList: Sequence[str] = ..., language: str = ...
     ) -> DescribeServicesResponseTypeDef:
         """
         Returns the current list of Amazon Web Services services and a list of service
         categories for each service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_services)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_services)
         """
-
     async def describe_severity_levels(
         self, *, language: str = ...
     ) -> DescribeSeverityLevelsResponseTypeDef:
         """
         Returns the list of severity levels that you can assign to a support case.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_severity_levels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_severity_levels)
         """
+    async def describe_supported_languages(
+        self, *, issueType: str, serviceCode: str, categoryCode: str
+    ) -> DescribeSupportedLanguagesResponseTypeDef:
+        """
+        Returns a list of supported languages for a specified `categoryCode`,
+        `issueType` and `serviceCode`.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_supported_languages)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_supported_languages)
+        """
     async def describe_trusted_advisor_check_refresh_statuses(
         self, *, checkIds: Sequence[str]
     ) -> DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef:
         """
         Returns the refresh status of the Trusted Advisor checks that have the specified
         check IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_check_refresh_statuses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_check_refresh_statuses)
         """
-
     async def describe_trusted_advisor_check_result(
         self, *, checkId: str, language: str = ...
     ) -> DescribeTrustedAdvisorCheckResultResponseTypeDef:
         """
         Returns the results of the Trusted Advisor check that has the specified check
         ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_check_result)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_check_result)
         """
-
     async def describe_trusted_advisor_check_summaries(
         self, *, checkIds: Sequence[str]
     ) -> DescribeTrustedAdvisorCheckSummariesResponseTypeDef:
         """
         Returns the results for the Trusted Advisor check summaries for the check IDs
         that you specified.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_check_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_check_summaries)
         """
-
     async def describe_trusted_advisor_checks(
         self, *, language: str
     ) -> DescribeTrustedAdvisorChecksResponseTypeDef:
         """
         Returns information about all available Trusted Advisor checks, including the
         name, ID, category, description, and metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_checks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_checks)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#generate_presigned_url)
         """
-
     async def refresh_trusted_advisor_check(
         self, *, checkId: str
     ) -> RefreshTrustedAdvisorCheckResponseTypeDef:
         """
         Refreshes the Trusted Advisor check that you specify using the check ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.refresh_trusted_advisor_check)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#refresh_trusted_advisor_check)
         """
-
     async def resolve_case(self, *, caseId: str = ...) -> ResolveCaseResponseTypeDef:
         """
         Resolves a support case.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.resolve_case)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#resolve_case)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["describe_cases"]) -> DescribeCasesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["describe_communications"]
     ) -> DescribeCommunicationsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "SupportClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/)
         """
```

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/client.pyi` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/client.py`

 * *Files 8% similar despite different names*

```diff
@@ -25,49 +25,56 @@
     AddAttachmentsToSetResponseTypeDef,
     AddCommunicationToCaseResponseTypeDef,
     AttachmentTypeDef,
     CreateCaseResponseTypeDef,
     DescribeAttachmentResponseTypeDef,
     DescribeCasesResponseTypeDef,
     DescribeCommunicationsResponseTypeDef,
+    DescribeCreateCaseOptionsResponseTypeDef,
     DescribeServicesResponseTypeDef,
     DescribeSeverityLevelsResponseTypeDef,
+    DescribeSupportedLanguagesResponseTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef,
     DescribeTrustedAdvisorCheckResultResponseTypeDef,
     DescribeTrustedAdvisorChecksResponseTypeDef,
     DescribeTrustedAdvisorCheckSummariesResponseTypeDef,
     RefreshTrustedAdvisorCheckResponseTypeDef,
     ResolveCaseResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("SupportClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AttachmentIdNotFound: Type[BotocoreClientError]
     AttachmentLimitExceeded: Type[BotocoreClientError]
     AttachmentSetExpired: Type[BotocoreClientError]
     AttachmentSetIdNotFound: Type[BotocoreClientError]
     AttachmentSetSizeLimitExceeded: Type[BotocoreClientError]
     CaseCreationLimitExceeded: Type[BotocoreClientError]
     CaseIdNotFound: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     DescribeAttachmentLimitExceeded: Type[BotocoreClientError]
     InternalServerError: Type[BotocoreClientError]
+    ThrottlingException: Type[BotocoreClientError]
+
 
 class SupportClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/)
     """
 
@@ -77,51 +84,56 @@
     def exceptions(self) -> Exceptions:
         """
         SupportClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#exceptions)
         """
+
     async def add_attachments_to_set(
         self, *, attachments: Sequence[AttachmentTypeDef], attachmentSetId: str = ...
     ) -> AddAttachmentsToSetResponseTypeDef:
         """
         Adds one or more attachments to an attachment set.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.add_attachments_to_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#add_attachments_to_set)
         """
+
     async def add_communication_to_case(
         self,
         *,
         communicationBody: str,
         caseId: str = ...,
         ccEmailAddresses: Sequence[str] = ...,
         attachmentSetId: str = ...
     ) -> AddCommunicationToCaseResponseTypeDef:
         """
         Adds additional customer communication to an Amazon Web Services Support case.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.add_communication_to_case)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#add_communication_to_case)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#close)
         """
+
     async def create_case(
         self,
         *,
         subject: str,
         communicationBody: str,
         serviceCode: str = ...,
         severityCode: str = ...,
@@ -133,21 +145,23 @@
     ) -> CreateCaseResponseTypeDef:
         """
         Creates a case in the Amazon Web Services Support Center.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.create_case)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#create_case)
         """
+
     async def describe_attachment(self, *, attachmentId: str) -> DescribeAttachmentResponseTypeDef:
         """
         Returns the attachment that has the specified ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_attachment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_attachment)
         """
+
     async def describe_cases(
         self,
         *,
         caseIdList: Sequence[str] = ...,
         displayId: str = ...,
         afterTime: str = ...,
         beforeTime: str = ...,
@@ -159,14 +173,15 @@
     ) -> DescribeCasesResponseTypeDef:
         """
         Returns a list of cases that you specify by passing one or more case IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_cases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_cases)
         """
+
     async def describe_communications(
         self,
         *,
         caseId: str,
         beforeTime: str = ...,
         afterTime: str = ...,
         nextToken: str = ...,
@@ -174,119 +189,154 @@
     ) -> DescribeCommunicationsResponseTypeDef:
         """
         Returns communications and attachments for one or more support cases.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_communications)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_communications)
         """
+
+    async def describe_create_case_options(
+        self, *, issueType: str, serviceCode: str, language: str, categoryCode: str
+    ) -> DescribeCreateCaseOptionsResponseTypeDef:
+        """
+        Returns a list of CreateCaseOption types along with the corresponding supported
+        hours and language availability.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_create_case_options)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_create_case_options)
+        """
+
     async def describe_services(
         self, *, serviceCodeList: Sequence[str] = ..., language: str = ...
     ) -> DescribeServicesResponseTypeDef:
         """
         Returns the current list of Amazon Web Services services and a list of service
         categories for each service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_services)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_services)
         """
+
     async def describe_severity_levels(
         self, *, language: str = ...
     ) -> DescribeSeverityLevelsResponseTypeDef:
         """
         Returns the list of severity levels that you can assign to a support case.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_severity_levels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_severity_levels)
         """
+
+    async def describe_supported_languages(
+        self, *, issueType: str, serviceCode: str, categoryCode: str
+    ) -> DescribeSupportedLanguagesResponseTypeDef:
+        """
+        Returns a list of supported languages for a specified `categoryCode`,
+        `issueType` and `serviceCode`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_supported_languages)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_supported_languages)
+        """
+
     async def describe_trusted_advisor_check_refresh_statuses(
         self, *, checkIds: Sequence[str]
     ) -> DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef:
         """
         Returns the refresh status of the Trusted Advisor checks that have the specified
         check IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_check_refresh_statuses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_check_refresh_statuses)
         """
+
     async def describe_trusted_advisor_check_result(
         self, *, checkId: str, language: str = ...
     ) -> DescribeTrustedAdvisorCheckResultResponseTypeDef:
         """
         Returns the results of the Trusted Advisor check that has the specified check
         ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_check_result)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_check_result)
         """
+
     async def describe_trusted_advisor_check_summaries(
         self, *, checkIds: Sequence[str]
     ) -> DescribeTrustedAdvisorCheckSummariesResponseTypeDef:
         """
         Returns the results for the Trusted Advisor check summaries for the check IDs
         that you specified.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_check_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_check_summaries)
         """
+
     async def describe_trusted_advisor_checks(
         self, *, language: str
     ) -> DescribeTrustedAdvisorChecksResponseTypeDef:
         """
         Returns information about all available Trusted Advisor checks, including the
         name, ID, category, description, and metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.describe_trusted_advisor_checks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#describe_trusted_advisor_checks)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#generate_presigned_url)
         """
+
     async def refresh_trusted_advisor_check(
         self, *, checkId: str
     ) -> RefreshTrustedAdvisorCheckResponseTypeDef:
         """
         Refreshes the Trusted Advisor check that you specify using the check ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.refresh_trusted_advisor_check)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#refresh_trusted_advisor_check)
         """
+
     async def resolve_case(self, *, caseId: str = ...) -> ResolveCaseResponseTypeDef:
         """
         Resolves a support case.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.resolve_case)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#resolve_case)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["describe_cases"]) -> DescribeCasesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["describe_communications"]
     ) -> DescribeCommunicationsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "SupportClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/client/)
         """
```

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/literals.py` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -90,14 +90,15 @@
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
@@ -176,14 +177,15 @@
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
@@ -194,14 +196,15 @@
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
@@ -237,14 +240,15 @@
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
@@ -263,16 +267,19 @@
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
@@ -356,15 +363,17 @@
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

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/literals.pyi` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -88,14 +88,15 @@
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
@@ -174,14 +175,15 @@
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
@@ -192,14 +194,15 @@
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
@@ -235,14 +238,15 @@
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
@@ -261,16 +265,19 @@
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
@@ -354,15 +361,17 @@
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

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/paginator.py` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -18,45 +18,35 @@
     with session.create_client("support") as client:
         client: SupportClient
 
         describe_cases_paginator: DescribeCasesPaginator = client.get_paginator("describe_cases")
         describe_communications_paginator: DescribeCommunicationsPaginator = client.get_paginator("describe_communications")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeCasesResponseTypeDef,
     DescribeCommunicationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeCasesPaginator", "DescribeCommunicationsPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeCasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecasespaginator)
     """
 
     def paginate(
@@ -65,33 +55,32 @@
         caseIdList: Sequence[str] = ...,
         displayId: str = ...,
         afterTime: str = ...,
         beforeTime: str = ...,
         includeResolvedCases: bool = ...,
         language: str = ...,
         includeCommunications: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecasespaginator)
         """
 
-
 class DescribeCommunicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCommunications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecommunicationspaginator)
     """
 
     def paginate(
         self,
         *,
         caseId: str,
         beforeTime: str = ...,
         afterTime: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCommunicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCommunications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecommunicationspaginator)
         """
```

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/paginator.pyi` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -18,41 +18,38 @@
     with session.create_client("support") as client:
         client: SupportClient
 
         describe_cases_paginator: DescribeCasesPaginator = client.get_paginator("describe_cases")
         describe_communications_paginator: DescribeCommunicationsPaginator = client.get_paginator("describe_communications")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeCasesResponseTypeDef,
     DescribeCommunicationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeCasesPaginator", "DescribeCommunicationsPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeCasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecasespaginator)
     """
 
     def paginate(
@@ -61,32 +58,33 @@
         caseIdList: Sequence[str] = ...,
         displayId: str = ...,
         afterTime: str = ...,
         beforeTime: str = ...,
         includeResolvedCases: bool = ...,
         language: str = ...,
         includeCommunications: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecasespaginator)
         """
 
+
 class DescribeCommunicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCommunications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecommunicationspaginator)
     """
 
     def paginate(
         self,
         *,
         caseId: str,
         beforeTime: str = ...,
         afterTime: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCommunicationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support.Paginator.DescribeCommunications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/paginators/#describecommunicationspaginator)
         """
```

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/type_defs.py` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -20,55 +20,63 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AttachmentTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddAttachmentsToSetResponseTypeDef",
     "AddCommunicationToCaseRequestRequestTypeDef",
+    "AddCommunicationToCaseResponseTypeDef",
     "AttachmentDetailsTypeDef",
     "CategoryTypeDef",
+    "DateIntervalTypeDef",
+    "SupportedHourTypeDef",
     "CreateCaseRequestRequestTypeDef",
+    "CreateCaseResponseTypeDef",
     "DescribeAttachmentRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
     "DescribeCasesRequestRequestTypeDef",
+    "DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
     "DescribeCommunicationsRequestRequestTypeDef",
+    "DescribeCreateCaseOptionsRequestRequestTypeDef",
     "DescribeServicesRequestRequestTypeDef",
     "DescribeSeverityLevelsRequestRequestTypeDef",
     "SeverityLevelTypeDef",
+    "DescribeSupportedLanguagesRequestRequestTypeDef",
+    "SupportedLanguageTypeDef",
     "DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef",
     "TrustedAdvisorCheckRefreshStatusTypeDef",
     "DescribeTrustedAdvisorCheckResultRequestRequestTypeDef",
     "DescribeTrustedAdvisorCheckSummariesRequestRequestTypeDef",
     "DescribeTrustedAdvisorChecksRequestRequestTypeDef",
     "TrustedAdvisorCheckDescriptionTypeDef",
+    "PaginatorConfigTypeDef",
     "RefreshTrustedAdvisorCheckRequestRequestTypeDef",
     "ResolveCaseRequestRequestTypeDef",
+    "ResolveCaseResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TrustedAdvisorCostOptimizingSummaryTypeDef",
     "TrustedAdvisorResourceDetailTypeDef",
     "TrustedAdvisorResourcesSummaryTypeDef",
     "AddAttachmentsToSetRequestRequestTypeDef",
-    "AddAttachmentsToSetResponseTypeDef",
-    "AddCommunicationToCaseResponseTypeDef",
-    "CreateCaseResponseTypeDef",
     "DescribeAttachmentResponseTypeDef",
-    "ResolveCaseResponseTypeDef",
     "CommunicationTypeDef",
     "ServiceTypeDef",
-    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
-    "DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+    "CommunicationTypeOptionsTypeDef",
     "DescribeSeverityLevelsResponseTypeDef",
+    "DescribeSupportedLanguagesResponseTypeDef",
     "DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef",
     "RefreshTrustedAdvisorCheckResponseTypeDef",
     "DescribeTrustedAdvisorChecksResponseTypeDef",
     "TrustedAdvisorCategorySpecificSummaryTypeDef",
     "DescribeCommunicationsResponseTypeDef",
     "RecentCaseCommunicationsTypeDef",
     "DescribeServicesResponseTypeDef",
+    "DescribeCreateCaseOptionsResponseTypeDef",
     "TrustedAdvisorCheckResultTypeDef",
     "TrustedAdvisorCheckSummaryTypeDef",
     "CaseDetailsTypeDef",
     "DescribeTrustedAdvisorCheckResultResponseTypeDef",
     "DescribeTrustedAdvisorCheckSummariesResponseTypeDef",
     "DescribeCasesResponseTypeDef",
 )
@@ -78,22 +86,20 @@
     {
         "fileName": str,
         "data": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddAttachmentsToSetResponseTypeDef = TypedDict(
+    "AddAttachmentsToSetResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "attachmentSetId": str,
+        "expiryTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddCommunicationToCaseRequestRequestTypeDef = TypedDict(
     "_RequiredAddCommunicationToCaseRequestRequestTypeDef",
     {
         "communicationBody": str,
@@ -113,14 +119,22 @@
 class AddCommunicationToCaseRequestRequestTypeDef(
     _RequiredAddCommunicationToCaseRequestRequestTypeDef,
     _OptionalAddCommunicationToCaseRequestRequestTypeDef,
 ):
     pass
 
 
+AddCommunicationToCaseResponseTypeDef = TypedDict(
+    "AddCommunicationToCaseResponseTypeDef",
+    {
+        "result": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttachmentDetailsTypeDef = TypedDict(
     "AttachmentDetailsTypeDef",
     {
         "attachmentId": str,
         "fileName": str,
     },
     total=False,
@@ -131,14 +145,32 @@
     {
         "code": str,
         "name": str,
     },
     total=False,
 )
 
+DateIntervalTypeDef = TypedDict(
+    "DateIntervalTypeDef",
+    {
+        "startDateTime": str,
+        "endDateTime": str,
+    },
+    total=False,
+)
+
+SupportedHourTypeDef = TypedDict(
+    "SupportedHourTypeDef",
+    {
+        "startTime": str,
+        "endTime": str,
+    },
+    total=False,
+)
+
 _RequiredCreateCaseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCaseRequestRequestTypeDef",
     {
         "subject": str,
         "communicationBody": str,
     },
 )
@@ -159,27 +191,40 @@
 
 class CreateCaseRequestRequestTypeDef(
     _RequiredCreateCaseRequestRequestTypeDef, _OptionalCreateCaseRequestRequestTypeDef
 ):
     pass
 
 
+CreateCaseResponseTypeDef = TypedDict(
+    "CreateCaseResponseTypeDef",
+    {
+        "caseId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeAttachmentRequestRequestTypeDef = TypedDict(
     "DescribeAttachmentRequestRequestTypeDef",
     {
         "attachmentId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeCasesRequestDescribeCasesPaginateTypeDef = TypedDict(
+    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "caseIdList": Sequence[str],
+        "displayId": str,
+        "afterTime": str,
+        "beforeTime": str,
+        "includeResolvedCases": bool,
+        "language": str,
+        "includeCommunications": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeCasesRequestRequestTypeDef = TypedDict(
     "DescribeCasesRequestRequestTypeDef",
     {
@@ -192,14 +237,38 @@
         "maxResults": int,
         "language": str,
         "includeCommunications": bool,
     },
     total=False,
 )
 
+_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+    {
+        "caseId": str,
+    },
+)
+_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+    {
+        "beforeTime": str,
+        "afterTime": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef(
+    _RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
+    _OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeCommunicationsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeCommunicationsRequestRequestTypeDef",
     {
         "caseId": str,
     },
 )
 _OptionalDescribeCommunicationsRequestRequestTypeDef = TypedDict(
@@ -217,14 +286,24 @@
 class DescribeCommunicationsRequestRequestTypeDef(
     _RequiredDescribeCommunicationsRequestRequestTypeDef,
     _OptionalDescribeCommunicationsRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeCreateCaseOptionsRequestRequestTypeDef = TypedDict(
+    "DescribeCreateCaseOptionsRequestRequestTypeDef",
+    {
+        "issueType": str,
+        "serviceCode": str,
+        "language": str,
+        "categoryCode": str,
+    },
+)
+
 DescribeServicesRequestRequestTypeDef = TypedDict(
     "DescribeServicesRequestRequestTypeDef",
     {
         "serviceCodeList": Sequence[str],
         "language": str,
     },
     total=False,
@@ -243,14 +322,33 @@
     {
         "code": str,
         "name": str,
     },
     total=False,
 )
 
+DescribeSupportedLanguagesRequestRequestTypeDef = TypedDict(
+    "DescribeSupportedLanguagesRequestRequestTypeDef",
+    {
+        "issueType": str,
+        "serviceCode": str,
+        "categoryCode": str,
+    },
+)
+
+SupportedLanguageTypeDef = TypedDict(
+    "SupportedLanguageTypeDef",
+    {
+        "code": str,
+        "language": str,
+        "display": str,
+    },
+    total=False,
+)
+
 DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef",
     {
         "checkIds": Sequence[str],
     },
 )
 
@@ -306,14 +404,24 @@
         "name": str,
         "description": str,
         "category": str,
         "metadata": List[str],
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
 RefreshTrustedAdvisorCheckRequestRequestTypeDef = TypedDict(
     "RefreshTrustedAdvisorCheckRequestRequestTypeDef",
     {
         "checkId": str,
     },
 )
 
@@ -321,14 +429,34 @@
     "ResolveCaseRequestRequestTypeDef",
     {
         "caseId": str,
     },
     total=False,
 )
 
+ResolveCaseResponseTypeDef = TypedDict(
+    "ResolveCaseResponseTypeDef",
+    {
+        "initialCaseStatus": str,
+        "finalCaseStatus": str,
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
 TrustedAdvisorCostOptimizingSummaryTypeDef = TypedDict(
     "TrustedAdvisorCostOptimizingSummaryTypeDef",
     {
         "estimatedMonthlySavings": float,
         "estimatedPercentMonthlySavings": float,
     },
 )
@@ -385,53 +513,19 @@
 class AddAttachmentsToSetRequestRequestTypeDef(
     _RequiredAddAttachmentsToSetRequestRequestTypeDef,
     _OptionalAddAttachmentsToSetRequestRequestTypeDef,
 ):
     pass
 
 
-AddAttachmentsToSetResponseTypeDef = TypedDict(
-    "AddAttachmentsToSetResponseTypeDef",
-    {
-        "attachmentSetId": str,
-        "expiryTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AddCommunicationToCaseResponseTypeDef = TypedDict(
-    "AddCommunicationToCaseResponseTypeDef",
-    {
-        "result": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCaseResponseTypeDef = TypedDict(
-    "CreateCaseResponseTypeDef",
-    {
-        "caseId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeAttachmentResponseTypeDef = TypedDict(
     "DescribeAttachmentResponseTypeDef",
     {
         "attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResolveCaseResponseTypeDef = TypedDict(
-    "ResolveCaseResponseTypeDef",
-    {
-        "initialCaseStatus": str,
-        "finalCaseStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CommunicationTypeDef = TypedDict(
     "CommunicationTypeDef",
     {
         "caseId": str,
@@ -449,82 +543,61 @@
         "code": str,
         "name": str,
         "categories": List[CategoryTypeDef],
     },
     total=False,
 )
 
-DescribeCasesRequestDescribeCasesPaginateTypeDef = TypedDict(
-    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
+CommunicationTypeOptionsTypeDef = TypedDict(
+    "CommunicationTypeOptionsTypeDef",
     {
-        "caseIdList": Sequence[str],
-        "displayId": str,
-        "afterTime": str,
-        "beforeTime": str,
-        "includeResolvedCases": bool,
-        "language": str,
-        "includeCommunications": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "type": str,
+        "supportedHours": List[SupportedHourTypeDef],
+        "datesWithoutSupport": List[DateIntervalTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
-    {
-        "caseId": str,
-    },
-)
-_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+DescribeSeverityLevelsResponseTypeDef = TypedDict(
+    "DescribeSeverityLevelsResponseTypeDef",
     {
-        "beforeTime": str,
-        "afterTime": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "severityLevels": List[SeverityLevelTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef(
-    _RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
-    _OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
-):
-    pass
-
-
-DescribeSeverityLevelsResponseTypeDef = TypedDict(
-    "DescribeSeverityLevelsResponseTypeDef",
+DescribeSupportedLanguagesResponseTypeDef = TypedDict(
+    "DescribeSupportedLanguagesResponseTypeDef",
     {
-        "severityLevels": List[SeverityLevelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "supportedLanguages": List[SupportedLanguageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef",
     {
         "statuses": List[TrustedAdvisorCheckRefreshStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RefreshTrustedAdvisorCheckResponseTypeDef = TypedDict(
     "RefreshTrustedAdvisorCheckResponseTypeDef",
     {
         "status": TrustedAdvisorCheckRefreshStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustedAdvisorChecksResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorChecksResponseTypeDef",
     {
         "checks": List[TrustedAdvisorCheckDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrustedAdvisorCategorySpecificSummaryTypeDef = TypedDict(
     "TrustedAdvisorCategorySpecificSummaryTypeDef",
     {
         "costOptimizing": TrustedAdvisorCostOptimizingSummaryTypeDef,
@@ -533,15 +606,15 @@
 )
 
 DescribeCommunicationsResponseTypeDef = TypedDict(
     "DescribeCommunicationsResponseTypeDef",
     {
         "communications": List[CommunicationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecentCaseCommunicationsTypeDef = TypedDict(
     "RecentCaseCommunicationsTypeDef",
     {
         "communications": List[CommunicationTypeDef],
@@ -550,15 +623,24 @@
     total=False,
 )
 
 DescribeServicesResponseTypeDef = TypedDict(
     "DescribeServicesResponseTypeDef",
     {
         "services": List[ServiceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeCreateCaseOptionsResponseTypeDef = TypedDict(
+    "DescribeCreateCaseOptionsResponseTypeDef",
+    {
+        "languageAvailability": str,
+        "communicationTypes": List[CommunicationTypeOptionsTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrustedAdvisorCheckResultTypeDef = TypedDict(
     "TrustedAdvisorCheckResultTypeDef",
     {
         "checkId": str,
@@ -614,27 +696,27 @@
     total=False,
 )
 
 DescribeTrustedAdvisorCheckResultResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckResultResponseTypeDef",
     {
         "result": TrustedAdvisorCheckResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustedAdvisorCheckSummariesResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckSummariesResponseTypeDef",
     {
         "summaries": List[TrustedAdvisorCheckSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCasesResponseTypeDef = TypedDict(
     "DescribeCasesResponseTypeDef",
     {
         "cases": List[CaseDetailsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support/type_defs.pyi` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -19,55 +19,63 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AttachmentTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddAttachmentsToSetResponseTypeDef",
     "AddCommunicationToCaseRequestRequestTypeDef",
+    "AddCommunicationToCaseResponseTypeDef",
     "AttachmentDetailsTypeDef",
     "CategoryTypeDef",
+    "DateIntervalTypeDef",
+    "SupportedHourTypeDef",
     "CreateCaseRequestRequestTypeDef",
+    "CreateCaseResponseTypeDef",
     "DescribeAttachmentRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
     "DescribeCasesRequestRequestTypeDef",
+    "DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
     "DescribeCommunicationsRequestRequestTypeDef",
+    "DescribeCreateCaseOptionsRequestRequestTypeDef",
     "DescribeServicesRequestRequestTypeDef",
     "DescribeSeverityLevelsRequestRequestTypeDef",
     "SeverityLevelTypeDef",
+    "DescribeSupportedLanguagesRequestRequestTypeDef",
+    "SupportedLanguageTypeDef",
     "DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef",
     "TrustedAdvisorCheckRefreshStatusTypeDef",
     "DescribeTrustedAdvisorCheckResultRequestRequestTypeDef",
     "DescribeTrustedAdvisorCheckSummariesRequestRequestTypeDef",
     "DescribeTrustedAdvisorChecksRequestRequestTypeDef",
     "TrustedAdvisorCheckDescriptionTypeDef",
+    "PaginatorConfigTypeDef",
     "RefreshTrustedAdvisorCheckRequestRequestTypeDef",
     "ResolveCaseRequestRequestTypeDef",
+    "ResolveCaseResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TrustedAdvisorCostOptimizingSummaryTypeDef",
     "TrustedAdvisorResourceDetailTypeDef",
     "TrustedAdvisorResourcesSummaryTypeDef",
     "AddAttachmentsToSetRequestRequestTypeDef",
-    "AddAttachmentsToSetResponseTypeDef",
-    "AddCommunicationToCaseResponseTypeDef",
-    "CreateCaseResponseTypeDef",
     "DescribeAttachmentResponseTypeDef",
-    "ResolveCaseResponseTypeDef",
     "CommunicationTypeDef",
     "ServiceTypeDef",
-    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
-    "DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+    "CommunicationTypeOptionsTypeDef",
     "DescribeSeverityLevelsResponseTypeDef",
+    "DescribeSupportedLanguagesResponseTypeDef",
     "DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef",
     "RefreshTrustedAdvisorCheckResponseTypeDef",
     "DescribeTrustedAdvisorChecksResponseTypeDef",
     "TrustedAdvisorCategorySpecificSummaryTypeDef",
     "DescribeCommunicationsResponseTypeDef",
     "RecentCaseCommunicationsTypeDef",
     "DescribeServicesResponseTypeDef",
+    "DescribeCreateCaseOptionsResponseTypeDef",
     "TrustedAdvisorCheckResultTypeDef",
     "TrustedAdvisorCheckSummaryTypeDef",
     "CaseDetailsTypeDef",
     "DescribeTrustedAdvisorCheckResultResponseTypeDef",
     "DescribeTrustedAdvisorCheckSummariesResponseTypeDef",
     "DescribeCasesResponseTypeDef",
 )
@@ -77,22 +85,20 @@
     {
         "fileName": str,
         "data": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddAttachmentsToSetResponseTypeDef = TypedDict(
+    "AddAttachmentsToSetResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "attachmentSetId": str,
+        "expiryTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddCommunicationToCaseRequestRequestTypeDef = TypedDict(
     "_RequiredAddCommunicationToCaseRequestRequestTypeDef",
     {
         "communicationBody": str,
@@ -110,14 +116,22 @@
 
 class AddCommunicationToCaseRequestRequestTypeDef(
     _RequiredAddCommunicationToCaseRequestRequestTypeDef,
     _OptionalAddCommunicationToCaseRequestRequestTypeDef,
 ):
     pass
 
+AddCommunicationToCaseResponseTypeDef = TypedDict(
+    "AddCommunicationToCaseResponseTypeDef",
+    {
+        "result": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AttachmentDetailsTypeDef = TypedDict(
     "AttachmentDetailsTypeDef",
     {
         "attachmentId": str,
         "fileName": str,
     },
     total=False,
@@ -128,14 +142,32 @@
     {
         "code": str,
         "name": str,
     },
     total=False,
 )
 
+DateIntervalTypeDef = TypedDict(
+    "DateIntervalTypeDef",
+    {
+        "startDateTime": str,
+        "endDateTime": str,
+    },
+    total=False,
+)
+
+SupportedHourTypeDef = TypedDict(
+    "SupportedHourTypeDef",
+    {
+        "startTime": str,
+        "endTime": str,
+    },
+    total=False,
+)
+
 _RequiredCreateCaseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCaseRequestRequestTypeDef",
     {
         "subject": str,
         "communicationBody": str,
     },
 )
@@ -154,27 +186,40 @@
 )
 
 class CreateCaseRequestRequestTypeDef(
     _RequiredCreateCaseRequestRequestTypeDef, _OptionalCreateCaseRequestRequestTypeDef
 ):
     pass
 
+CreateCaseResponseTypeDef = TypedDict(
+    "CreateCaseResponseTypeDef",
+    {
+        "caseId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeAttachmentRequestRequestTypeDef = TypedDict(
     "DescribeAttachmentRequestRequestTypeDef",
     {
         "attachmentId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeCasesRequestDescribeCasesPaginateTypeDef = TypedDict(
+    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "caseIdList": Sequence[str],
+        "displayId": str,
+        "afterTime": str,
+        "beforeTime": str,
+        "includeResolvedCases": bool,
+        "language": str,
+        "includeCommunications": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeCasesRequestRequestTypeDef = TypedDict(
     "DescribeCasesRequestRequestTypeDef",
     {
@@ -187,14 +232,36 @@
         "maxResults": int,
         "language": str,
         "includeCommunications": bool,
     },
     total=False,
 )
 
+_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+    {
+        "caseId": str,
+    },
+)
+_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+    {
+        "beforeTime": str,
+        "afterTime": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef(
+    _RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
+    _OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeCommunicationsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeCommunicationsRequestRequestTypeDef",
     {
         "caseId": str,
     },
 )
 _OptionalDescribeCommunicationsRequestRequestTypeDef = TypedDict(
@@ -210,14 +277,24 @@
 
 class DescribeCommunicationsRequestRequestTypeDef(
     _RequiredDescribeCommunicationsRequestRequestTypeDef,
     _OptionalDescribeCommunicationsRequestRequestTypeDef,
 ):
     pass
 
+DescribeCreateCaseOptionsRequestRequestTypeDef = TypedDict(
+    "DescribeCreateCaseOptionsRequestRequestTypeDef",
+    {
+        "issueType": str,
+        "serviceCode": str,
+        "language": str,
+        "categoryCode": str,
+    },
+)
+
 DescribeServicesRequestRequestTypeDef = TypedDict(
     "DescribeServicesRequestRequestTypeDef",
     {
         "serviceCodeList": Sequence[str],
         "language": str,
     },
     total=False,
@@ -236,14 +313,33 @@
     {
         "code": str,
         "name": str,
     },
     total=False,
 )
 
+DescribeSupportedLanguagesRequestRequestTypeDef = TypedDict(
+    "DescribeSupportedLanguagesRequestRequestTypeDef",
+    {
+        "issueType": str,
+        "serviceCode": str,
+        "categoryCode": str,
+    },
+)
+
+SupportedLanguageTypeDef = TypedDict(
+    "SupportedLanguageTypeDef",
+    {
+        "code": str,
+        "language": str,
+        "display": str,
+    },
+    total=False,
+)
+
 DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef",
     {
         "checkIds": Sequence[str],
     },
 )
 
@@ -297,14 +393,24 @@
         "name": str,
         "description": str,
         "category": str,
         "metadata": List[str],
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
 RefreshTrustedAdvisorCheckRequestRequestTypeDef = TypedDict(
     "RefreshTrustedAdvisorCheckRequestRequestTypeDef",
     {
         "checkId": str,
     },
 )
 
@@ -312,14 +418,34 @@
     "ResolveCaseRequestRequestTypeDef",
     {
         "caseId": str,
     },
     total=False,
 )
 
+ResolveCaseResponseTypeDef = TypedDict(
+    "ResolveCaseResponseTypeDef",
+    {
+        "initialCaseStatus": str,
+        "finalCaseStatus": str,
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
 TrustedAdvisorCostOptimizingSummaryTypeDef = TypedDict(
     "TrustedAdvisorCostOptimizingSummaryTypeDef",
     {
         "estimatedMonthlySavings": float,
         "estimatedPercentMonthlySavings": float,
     },
 )
@@ -372,53 +498,19 @@
 
 class AddAttachmentsToSetRequestRequestTypeDef(
     _RequiredAddAttachmentsToSetRequestRequestTypeDef,
     _OptionalAddAttachmentsToSetRequestRequestTypeDef,
 ):
     pass
 
-AddAttachmentsToSetResponseTypeDef = TypedDict(
-    "AddAttachmentsToSetResponseTypeDef",
-    {
-        "attachmentSetId": str,
-        "expiryTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AddCommunicationToCaseResponseTypeDef = TypedDict(
-    "AddCommunicationToCaseResponseTypeDef",
-    {
-        "result": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCaseResponseTypeDef = TypedDict(
-    "CreateCaseResponseTypeDef",
-    {
-        "caseId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeAttachmentResponseTypeDef = TypedDict(
     "DescribeAttachmentResponseTypeDef",
     {
         "attachment": AttachmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResolveCaseResponseTypeDef = TypedDict(
-    "ResolveCaseResponseTypeDef",
-    {
-        "initialCaseStatus": str,
-        "finalCaseStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CommunicationTypeDef = TypedDict(
     "CommunicationTypeDef",
     {
         "caseId": str,
@@ -436,80 +528,61 @@
         "code": str,
         "name": str,
         "categories": List[CategoryTypeDef],
     },
     total=False,
 )
 
-DescribeCasesRequestDescribeCasesPaginateTypeDef = TypedDict(
-    "DescribeCasesRequestDescribeCasesPaginateTypeDef",
+CommunicationTypeOptionsTypeDef = TypedDict(
+    "CommunicationTypeOptionsTypeDef",
     {
-        "caseIdList": Sequence[str],
-        "displayId": str,
-        "afterTime": str,
-        "beforeTime": str,
-        "includeResolvedCases": bool,
-        "language": str,
-        "includeCommunications": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "type": str,
+        "supportedHours": List[SupportedHourTypeDef],
+        "datesWithoutSupport": List[DateIntervalTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
-    {
-        "caseId": str,
-    },
-)
-_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef",
+DescribeSeverityLevelsResponseTypeDef = TypedDict(
+    "DescribeSeverityLevelsResponseTypeDef",
     {
-        "beforeTime": str,
-        "afterTime": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "severityLevels": List[SeverityLevelTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef(
-    _RequiredDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
-    _OptionalDescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
-):
-    pass
-
-DescribeSeverityLevelsResponseTypeDef = TypedDict(
-    "DescribeSeverityLevelsResponseTypeDef",
+DescribeSupportedLanguagesResponseTypeDef = TypedDict(
+    "DescribeSupportedLanguagesResponseTypeDef",
     {
-        "severityLevels": List[SeverityLevelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "supportedLanguages": List[SupportedLanguageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef",
     {
         "statuses": List[TrustedAdvisorCheckRefreshStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RefreshTrustedAdvisorCheckResponseTypeDef = TypedDict(
     "RefreshTrustedAdvisorCheckResponseTypeDef",
     {
         "status": TrustedAdvisorCheckRefreshStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustedAdvisorChecksResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorChecksResponseTypeDef",
     {
         "checks": List[TrustedAdvisorCheckDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrustedAdvisorCategorySpecificSummaryTypeDef = TypedDict(
     "TrustedAdvisorCategorySpecificSummaryTypeDef",
     {
         "costOptimizing": TrustedAdvisorCostOptimizingSummaryTypeDef,
@@ -518,15 +591,15 @@
 )
 
 DescribeCommunicationsResponseTypeDef = TypedDict(
     "DescribeCommunicationsResponseTypeDef",
     {
         "communications": List[CommunicationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecentCaseCommunicationsTypeDef = TypedDict(
     "RecentCaseCommunicationsTypeDef",
     {
         "communications": List[CommunicationTypeDef],
@@ -535,15 +608,24 @@
     total=False,
 )
 
 DescribeServicesResponseTypeDef = TypedDict(
     "DescribeServicesResponseTypeDef",
     {
         "services": List[ServiceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeCreateCaseOptionsResponseTypeDef = TypedDict(
+    "DescribeCreateCaseOptionsResponseTypeDef",
+    {
+        "languageAvailability": str,
+        "communicationTypes": List[CommunicationTypeOptionsTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrustedAdvisorCheckResultTypeDef = TypedDict(
     "TrustedAdvisorCheckResultTypeDef",
     {
         "checkId": str,
@@ -597,27 +679,27 @@
     total=False,
 )
 
 DescribeTrustedAdvisorCheckResultResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckResultResponseTypeDef",
     {
         "result": TrustedAdvisorCheckResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrustedAdvisorCheckSummariesResponseTypeDef = TypedDict(
     "DescribeTrustedAdvisorCheckSummariesResponseTypeDef",
     {
         "summaries": List[TrustedAdvisorCheckSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCasesResponseTypeDef = TypedDict(
     "DescribeCasesResponseTypeDef",
     {
         "cases": List[CaseDetailsTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/PKG-INFO` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-support
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Support 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Support 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-support"></a>
 
 # types-aiobotocore-support
 
 [![PyPI - types-aiobotocore-support](https://img.shields.io/pypi/v/types-aiobotocore-support.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-support.svg?color=blue)](https://pypi.org/project/types-aiobotocore-support)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-support?color=blue)](https://pypistats.org/packages/types-aiobotocore-support)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Support 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support)
+[aiobotocore.Support 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/support.html#Support)
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
 [types-aiobotocore-support docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_support/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,55 +320,63 @@
 
 `types_aiobotocore_support.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_support.type_defs import (
     AttachmentTypeDef,
-    ResponseMetadataTypeDef,
+    AddAttachmentsToSetResponseTypeDef,
     AddCommunicationToCaseRequestRequestTypeDef,
+    AddCommunicationToCaseResponseTypeDef,
     AttachmentDetailsTypeDef,
     CategoryTypeDef,
+    DateIntervalTypeDef,
+    SupportedHourTypeDef,
     CreateCaseRequestRequestTypeDef,
+    CreateCaseResponseTypeDef,
     DescribeAttachmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCasesRequestDescribeCasesPaginateTypeDef,
     DescribeCasesRequestRequestTypeDef,
+    DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
     DescribeCommunicationsRequestRequestTypeDef,
+    DescribeCreateCaseOptionsRequestRequestTypeDef,
     DescribeServicesRequestRequestTypeDef,
     DescribeSeverityLevelsRequestRequestTypeDef,
     SeverityLevelTypeDef,
+    DescribeSupportedLanguagesRequestRequestTypeDef,
+    SupportedLanguageTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesRequestRequestTypeDef,
     TrustedAdvisorCheckRefreshStatusTypeDef,
     DescribeTrustedAdvisorCheckResultRequestRequestTypeDef,
     DescribeTrustedAdvisorCheckSummariesRequestRequestTypeDef,
     DescribeTrustedAdvisorChecksRequestRequestTypeDef,
     TrustedAdvisorCheckDescriptionTypeDef,
+    PaginatorConfigTypeDef,
     RefreshTrustedAdvisorCheckRequestRequestTypeDef,
     ResolveCaseRequestRequestTypeDef,
+    ResolveCaseResponseTypeDef,
+    ResponseMetadataTypeDef,
     TrustedAdvisorCostOptimizingSummaryTypeDef,
     TrustedAdvisorResourceDetailTypeDef,
     TrustedAdvisorResourcesSummaryTypeDef,
     AddAttachmentsToSetRequestRequestTypeDef,
-    AddAttachmentsToSetResponseTypeDef,
-    AddCommunicationToCaseResponseTypeDef,
-    CreateCaseResponseTypeDef,
     DescribeAttachmentResponseTypeDef,
-    ResolveCaseResponseTypeDef,
     CommunicationTypeDef,
     ServiceTypeDef,
-    DescribeCasesRequestDescribeCasesPaginateTypeDef,
-    DescribeCommunicationsRequestDescribeCommunicationsPaginateTypeDef,
+    CommunicationTypeOptionsTypeDef,
     DescribeSeverityLevelsResponseTypeDef,
+    DescribeSupportedLanguagesResponseTypeDef,
     DescribeTrustedAdvisorCheckRefreshStatusesResponseTypeDef,
     RefreshTrustedAdvisorCheckResponseTypeDef,
     DescribeTrustedAdvisorChecksResponseTypeDef,
     TrustedAdvisorCategorySpecificSummaryTypeDef,
     DescribeCommunicationsResponseTypeDef,
     RecentCaseCommunicationsTypeDef,
     DescribeServicesResponseTypeDef,
+    DescribeCreateCaseOptionsResponseTypeDef,
     TrustedAdvisorCheckResultTypeDef,
     TrustedAdvisorCheckSummaryTypeDef,
     CaseDetailsTypeDef,
     DescribeTrustedAdvisorCheckResultResponseTypeDef,
     DescribeTrustedAdvisorCheckSummariesResponseTypeDef,
     DescribeCasesResponseTypeDef,
 )
@@ -381,43 +389,43 @@
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

### Comparing `types-aiobotocore-support-2.5.0.post1/types_aiobotocore_support.egg-info/SOURCES.txt` & `types-aiobotocore-support-2.5.1/types_aiobotocore_support.egg-info/SOURCES.txt`

 * *Files identical despite different names*

