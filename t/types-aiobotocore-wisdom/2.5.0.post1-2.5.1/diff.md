# Comparing `tmp/types-aiobotocore-wisdom-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-wisdom-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-wisdom-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-wisdom-2.5.1.tar", last modified: Wed Jun 28 01:44:20 2023, max compression
```

## Comparing `types-aiobotocore-wisdom-2.5.0.post1.tar` & `types-aiobotocore-wisdom-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:29.891717 types-aiobotocore-wisdom-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17961 2023-03-11 12:27:29.891717 types-aiobotocore-wisdom-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16380 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:29.891717 types-aiobotocore-wisdom-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:29.891717 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/
--rw-r--r--   0 runner    (1001) docker     (123)     1949 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1948 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      956 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26939 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    26892 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9663 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9661 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9082 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     9072 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    35217 2023-03-11 12:25:34.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    35158 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:33.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:29.891717 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17961 2023-03-11 12:27:29.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:27:29.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:29.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:29.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:29.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:29.000000 types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.018231 types-aiobotocore-wisdom-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17952 2023-06-28 01:44:20.018231 types-aiobotocore-wisdom-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16377 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:20.018231 types-aiobotocore-wisdom-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:42:29.000000 types-aiobotocore-wisdom-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.010231 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/
+-rw-r--r--   0 runner    (1001) docker     (123)     1949 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1948 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      944 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26939 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26892 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9872 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9870 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8976 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8967 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    35592 2023-06-28 01:42:31.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35531 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:30.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:20.018231 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17952 2023-06-28 01:44:19.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:44:19.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:19.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:19.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:19.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:44:19.000000 types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/LICENSE` & `types-aiobotocore-wisdom-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/PKG-INFO` & `types-aiobotocore-wisdom-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-wisdom
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectWisdomService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectWisdomService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-wisdom"></a>
 
 # types-aiobotocore-wisdom
 
 [![PyPI - types-aiobotocore-wisdom](https://img.shields.io/pypi/v/types-aiobotocore-wisdom.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wisdom)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wisdom.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wisdom)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wisdom?color=blue)](https://pypistats.org/packages/types-aiobotocore-wisdom)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectWisdomService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService)
+[aiobotocore.ConnectWisdomService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService)
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
 [types-aiobotocore-wisdom docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/).
 
 See how it helps to find and fix potential bugs:
 
@@ -357,15 +357,14 @@
     AppIntegrationsConfigurationTypeDef,
     AssistantAssociationInputDataTypeDef,
     KnowledgeBaseAssociationDataTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     ContentDataTypeDef,
     ContentReferenceTypeDef,
     ContentSummaryTypeDef,
-    ResponseMetadataTypeDef,
     CreateContentRequestRequestTypeDef,
     RenderingConfigurationTypeDef,
     CreateSessionRequestRequestTypeDef,
     SessionDataTypeDef,
     DeleteAssistantAssociationRequestRequestTypeDef,
     DeleteAssistantRequestRequestTypeDef,
     DeleteContentRequestRequestTypeDef,
@@ -375,54 +374,55 @@
     GetAssistantAssociationRequestRequestTypeDef,
     GetAssistantRequestRequestTypeDef,
     GetContentRequestRequestTypeDef,
     GetContentSummaryRequestRequestTypeDef,
     GetKnowledgeBaseRequestRequestTypeDef,
     GetRecommendationsRequestRequestTypeDef,
     GetSessionRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
     ListAssistantAssociationsRequestRequestTypeDef,
+    ListAssistantsRequestListAssistantsPaginateTypeDef,
     ListAssistantsRequestRequestTypeDef,
+    ListContentsRequestListContentsPaginateTypeDef,
     ListContentsRequestRequestTypeDef,
+    ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef,
     ListKnowledgeBasesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NotifyRecommendationsReceivedErrorTypeDef,
     NotifyRecommendationsReceivedRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    QueryAssistantRequestQueryAssistantPaginateTypeDef,
     QueryAssistantRequestRequestTypeDef,
     QueryRecommendationTriggerDataTypeDef,
     RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SessionSummaryTypeDef,
     StartContentUploadRequestRequestTypeDef,
+    StartContentUploadResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateContentRequestRequestTypeDef,
     UpdateKnowledgeBaseTemplateUriRequestRequestTypeDef,
     SourceConfigurationTypeDef,
     CreateAssistantAssociationRequestRequestTypeDef,
     AssistantAssociationOutputDataTypeDef,
     AssistantDataTypeDef,
     AssistantSummaryTypeDef,
     CreateAssistantRequestRequestTypeDef,
     CreateContentResponseTypeDef,
     GetContentResponseTypeDef,
+    UpdateContentResponseTypeDef,
     GetContentSummaryResponseTypeDef,
     ListContentsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     SearchContentResponseTypeDef,
-    StartContentUploadResponseTypeDef,
-    UpdateContentResponseTypeDef,
     CreateSessionResponseTypeDef,
     GetSessionResponseTypeDef,
     DocumentTextTypeDef,
     SearchExpressionTypeDef,
-    ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
-    ListAssistantsRequestListAssistantsPaginateTypeDef,
-    ListContentsRequestListContentsPaginateTypeDef,
-    ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef,
-    QueryAssistantRequestQueryAssistantPaginateTypeDef,
     NotifyRecommendationsReceivedResponseTypeDef,
     RecommendationTriggerDataTypeDef,
     SearchSessionsResponseTypeDef,
     CreateKnowledgeBaseRequestRequestTypeDef,
     KnowledgeBaseDataTypeDef,
     KnowledgeBaseSummaryTypeDef,
     AssistantAssociationDataTypeDef,
@@ -457,43 +457,43 @@
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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/README.md` & `types-aiobotocore-wisdom-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-wisdom"></a>
 
 # types-aiobotocore-wisdom
 
 [![PyPI - types-aiobotocore-wisdom](https://img.shields.io/pypi/v/types-aiobotocore-wisdom.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wisdom)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wisdom.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wisdom)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wisdom?color=blue)](https://pypistats.org/packages/types-aiobotocore-wisdom)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectWisdomService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService)
+[aiobotocore.ConnectWisdomService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService)
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
 [types-aiobotocore-wisdom docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/).
 
 See how it helps to find and fix potential bugs:
 
@@ -324,15 +324,14 @@
     AppIntegrationsConfigurationTypeDef,
     AssistantAssociationInputDataTypeDef,
     KnowledgeBaseAssociationDataTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     ContentDataTypeDef,
     ContentReferenceTypeDef,
     ContentSummaryTypeDef,
-    ResponseMetadataTypeDef,
     CreateContentRequestRequestTypeDef,
     RenderingConfigurationTypeDef,
     CreateSessionRequestRequestTypeDef,
     SessionDataTypeDef,
     DeleteAssistantAssociationRequestRequestTypeDef,
     DeleteAssistantRequestRequestTypeDef,
     DeleteContentRequestRequestTypeDef,
@@ -342,54 +341,55 @@
     GetAssistantAssociationRequestRequestTypeDef,
     GetAssistantRequestRequestTypeDef,
     GetContentRequestRequestTypeDef,
     GetContentSummaryRequestRequestTypeDef,
     GetKnowledgeBaseRequestRequestTypeDef,
     GetRecommendationsRequestRequestTypeDef,
     GetSessionRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
     ListAssistantAssociationsRequestRequestTypeDef,
+    ListAssistantsRequestListAssistantsPaginateTypeDef,
     ListAssistantsRequestRequestTypeDef,
+    ListContentsRequestListContentsPaginateTypeDef,
     ListContentsRequestRequestTypeDef,
+    ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef,
     ListKnowledgeBasesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NotifyRecommendationsReceivedErrorTypeDef,
     NotifyRecommendationsReceivedRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    QueryAssistantRequestQueryAssistantPaginateTypeDef,
     QueryAssistantRequestRequestTypeDef,
     QueryRecommendationTriggerDataTypeDef,
     RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SessionSummaryTypeDef,
     StartContentUploadRequestRequestTypeDef,
+    StartContentUploadResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateContentRequestRequestTypeDef,
     UpdateKnowledgeBaseTemplateUriRequestRequestTypeDef,
     SourceConfigurationTypeDef,
     CreateAssistantAssociationRequestRequestTypeDef,
     AssistantAssociationOutputDataTypeDef,
     AssistantDataTypeDef,
     AssistantSummaryTypeDef,
     CreateAssistantRequestRequestTypeDef,
     CreateContentResponseTypeDef,
     GetContentResponseTypeDef,
+    UpdateContentResponseTypeDef,
     GetContentSummaryResponseTypeDef,
     ListContentsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     SearchContentResponseTypeDef,
-    StartContentUploadResponseTypeDef,
-    UpdateContentResponseTypeDef,
     CreateSessionResponseTypeDef,
     GetSessionResponseTypeDef,
     DocumentTextTypeDef,
     SearchExpressionTypeDef,
-    ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
-    ListAssistantsRequestListAssistantsPaginateTypeDef,
-    ListContentsRequestListContentsPaginateTypeDef,
-    ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef,
-    QueryAssistantRequestQueryAssistantPaginateTypeDef,
     NotifyRecommendationsReceivedResponseTypeDef,
     RecommendationTriggerDataTypeDef,
     SearchSessionsResponseTypeDef,
     CreateKnowledgeBaseRequestRequestTypeDef,
     KnowledgeBaseDataTypeDef,
     KnowledgeBaseSummaryTypeDef,
     AssistantAssociationDataTypeDef,
@@ -424,43 +424,43 @@
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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/setup.py` & `types-aiobotocore-wisdom-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-wisdom.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-wisdom",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_wisdom"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ConnectWisdomService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ConnectWisdomService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/"
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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/__init__.py` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/__init__.pyi` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/__main__.py` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ConnectWisdomService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ConnectWisdomService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService\nOther"
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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/client.py` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/client.pyi` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/literals.py` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -147,14 +147,15 @@
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
@@ -233,14 +234,15 @@
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
@@ -251,14 +253,15 @@
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
@@ -294,14 +297,15 @@
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
@@ -320,16 +324,19 @@
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
@@ -413,15 +420,17 @@
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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/literals.pyi` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -145,14 +145,15 @@
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
@@ -231,14 +232,15 @@
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
@@ -249,14 +251,15 @@
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
@@ -292,14 +295,15 @@
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
@@ -318,16 +322,19 @@
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
@@ -411,15 +418,17 @@
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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/paginator.py` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_contents_paginator: ListContentsPaginator = client.get_paginator("list_contents")
         list_knowledge_bases_paginator: ListKnowledgeBasesPaginator = client.get_paginator("list_knowledge_bases")
         query_assistant_paginator: QueryAssistantPaginator = client.get_paginator("query_assistant")
         search_content_paginator: SearchContentPaginator = client.get_paginator("search_content")
         search_sessions_paginator: SearchSessionsPaginator = client.get_paginator("search_sessions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAssistantAssociationsResponseTypeDef,
     ListAssistantsResponseTypeDef,
@@ -46,145 +45,130 @@
     PaginatorConfigTypeDef,
     QueryAssistantResponseTypeDef,
     SearchContentResponseTypeDef,
     SearchExpressionTypeDef,
     SearchSessionsResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAssistantAssociationsPaginator",
     "ListAssistantsPaginator",
     "ListContentsPaginator",
     "ListKnowledgeBasesPaginator",
     "QueryAssistantPaginator",
     "SearchContentPaginator",
     "SearchSessionsPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListAssistantAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistantAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantassociationspaginator)
     """
 
     def paginate(
-        self, *, assistantId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, assistantId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssistantAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistantAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantassociationspaginator)
         """
 
-
 class ListAssistantsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistants)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssistantsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistants.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantspaginator)
         """
 
-
 class ListContentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListContents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listcontentspaginator)
     """
 
     def paginate(
-        self, *, knowledgeBaseId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, knowledgeBaseId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListContentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListContents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listcontentspaginator)
         """
 
-
 class ListKnowledgeBasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListKnowledgeBases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listknowledgebasespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKnowledgeBasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListKnowledgeBases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listknowledgebasespaginator)
         """
 
-
 class QueryAssistantPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.QueryAssistant)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#queryassistantpaginator)
     """
 
     def paginate(
-        self, *, assistantId: str, queryText: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, assistantId: str, queryText: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryAssistantResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.QueryAssistant.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#queryassistantpaginator)
         """
 
-
 class SearchContentPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchContent)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchcontentpaginator)
     """
 
     def paginate(
         self,
         *,
         knowledgeBaseId: str,
         searchExpression: SearchExpressionTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchContentResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchContent.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchcontentpaginator)
         """
 
-
 class SearchSessionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchSessions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchsessionspaginator)
     """
 
     def paginate(
         self,
         *,
         assistantId: str,
         searchExpression: SearchExpressionTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSessionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchsessionspaginator)
         """
```

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/paginator.pyi` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -28,16 +28,15 @@
         list_contents_paginator: ListContentsPaginator = client.get_paginator("list_contents")
         list_knowledge_bases_paginator: ListKnowledgeBasesPaginator = client.get_paginator("list_knowledge_bases")
         query_assistant_paginator: QueryAssistantPaginator = client.get_paginator("query_assistant")
         search_content_paginator: SearchContentPaginator = client.get_paginator("search_content")
         search_sessions_paginator: SearchSessionsPaginator = client.get_paginator("search_sessions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListAssistantAssociationsResponseTypeDef,
     ListAssistantsResponseTypeDef,
@@ -46,135 +45,139 @@
     PaginatorConfigTypeDef,
     QueryAssistantResponseTypeDef,
     SearchContentResponseTypeDef,
     SearchExpressionTypeDef,
     SearchSessionsResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAssistantAssociationsPaginator",
     "ListAssistantsPaginator",
     "ListContentsPaginator",
     "ListKnowledgeBasesPaginator",
     "QueryAssistantPaginator",
     "SearchContentPaginator",
     "SearchSessionsPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListAssistantAssociationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistantAssociations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantassociationspaginator)
     """
 
     def paginate(
-        self, *, assistantId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, assistantId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssistantAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistantAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantassociationspaginator)
         """
 
+
 class ListAssistantsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistants)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssistantsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListAssistants.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listassistantspaginator)
         """
 
+
 class ListContentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListContents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listcontentspaginator)
     """
 
     def paginate(
-        self, *, knowledgeBaseId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, knowledgeBaseId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListContentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListContents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listcontentspaginator)
         """
 
+
 class ListKnowledgeBasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListKnowledgeBases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listknowledgebasespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKnowledgeBasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.ListKnowledgeBases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#listknowledgebasespaginator)
         """
 
+
 class QueryAssistantPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.QueryAssistant)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#queryassistantpaginator)
     """
 
     def paginate(
-        self, *, assistantId: str, queryText: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, assistantId: str, queryText: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryAssistantResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.QueryAssistant.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#queryassistantpaginator)
         """
 
+
 class SearchContentPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchContent)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchcontentpaginator)
     """
 
     def paginate(
         self,
         *,
         knowledgeBaseId: str,
         searchExpression: SearchExpressionTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchContentResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchContent.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchcontentpaginator)
         """
 
+
 class SearchSessionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchSessions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchsessionspaginator)
     """
 
     def paginate(
         self,
         *,
         assistantId: str,
         searchExpression: SearchExpressionTypeDef,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchSessionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService.Paginator.SearchSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/paginators/#searchsessionspaginator)
         """
```

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/type_defs.py` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,15 +38,14 @@
     "AppIntegrationsConfigurationTypeDef",
     "AssistantAssociationInputDataTypeDef",
     "KnowledgeBaseAssociationDataTypeDef",
     "ServerSideEncryptionConfigurationTypeDef",
     "ContentDataTypeDef",
     "ContentReferenceTypeDef",
     "ContentSummaryTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateContentRequestRequestTypeDef",
     "RenderingConfigurationTypeDef",
     "CreateSessionRequestRequestTypeDef",
     "SessionDataTypeDef",
     "DeleteAssistantAssociationRequestRequestTypeDef",
     "DeleteAssistantRequestRequestTypeDef",
     "DeleteContentRequestRequestTypeDef",
@@ -56,54 +55,55 @@
     "GetAssistantAssociationRequestRequestTypeDef",
     "GetAssistantRequestRequestTypeDef",
     "GetContentRequestRequestTypeDef",
     "GetContentSummaryRequestRequestTypeDef",
     "GetKnowledgeBaseRequestRequestTypeDef",
     "GetRecommendationsRequestRequestTypeDef",
     "GetSessionRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
     "ListAssistantAssociationsRequestRequestTypeDef",
+    "ListAssistantsRequestListAssistantsPaginateTypeDef",
     "ListAssistantsRequestRequestTypeDef",
+    "ListContentsRequestListContentsPaginateTypeDef",
     "ListContentsRequestRequestTypeDef",
+    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
     "ListKnowledgeBasesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NotifyRecommendationsReceivedErrorTypeDef",
     "NotifyRecommendationsReceivedRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "QueryAssistantRequestQueryAssistantPaginateTypeDef",
     "QueryAssistantRequestRequestTypeDef",
     "QueryRecommendationTriggerDataTypeDef",
     "RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SessionSummaryTypeDef",
     "StartContentUploadRequestRequestTypeDef",
+    "StartContentUploadResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateContentRequestRequestTypeDef",
     "UpdateKnowledgeBaseTemplateUriRequestRequestTypeDef",
     "SourceConfigurationTypeDef",
     "CreateAssistantAssociationRequestRequestTypeDef",
     "AssistantAssociationOutputDataTypeDef",
     "AssistantDataTypeDef",
     "AssistantSummaryTypeDef",
     "CreateAssistantRequestRequestTypeDef",
     "CreateContentResponseTypeDef",
     "GetContentResponseTypeDef",
+    "UpdateContentResponseTypeDef",
     "GetContentSummaryResponseTypeDef",
     "ListContentsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "SearchContentResponseTypeDef",
-    "StartContentUploadResponseTypeDef",
-    "UpdateContentResponseTypeDef",
     "CreateSessionResponseTypeDef",
     "GetSessionResponseTypeDef",
     "DocumentTextTypeDef",
     "SearchExpressionTypeDef",
-    "ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
-    "ListAssistantsRequestListAssistantsPaginateTypeDef",
-    "ListContentsRequestListContentsPaginateTypeDef",
-    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
-    "QueryAssistantRequestQueryAssistantPaginateTypeDef",
     "NotifyRecommendationsReceivedResponseTypeDef",
     "RecommendationTriggerDataTypeDef",
     "SearchSessionsResponseTypeDef",
     "CreateKnowledgeBaseRequestRequestTypeDef",
     "KnowledgeBaseDataTypeDef",
     "KnowledgeBaseSummaryTypeDef",
     "AssistantAssociationDataTypeDef",
@@ -126,22 +126,35 @@
     "ListAssistantAssociationsResponseTypeDef",
     "RecommendationDataTypeDef",
     "ResultDataTypeDef",
     "GetRecommendationsResponseTypeDef",
     "QueryAssistantResponseTypeDef",
 )
 
-AppIntegrationsConfigurationTypeDef = TypedDict(
-    "AppIntegrationsConfigurationTypeDef",
+_RequiredAppIntegrationsConfigurationTypeDef = TypedDict(
+    "_RequiredAppIntegrationsConfigurationTypeDef",
     {
         "appIntegrationArn": str,
+    },
+)
+_OptionalAppIntegrationsConfigurationTypeDef = TypedDict(
+    "_OptionalAppIntegrationsConfigurationTypeDef",
+    {
         "objectFields": Sequence[str],
     },
+    total=False,
 )
 
+
+class AppIntegrationsConfigurationTypeDef(
+    _RequiredAppIntegrationsConfigurationTypeDef, _OptionalAppIntegrationsConfigurationTypeDef
+):
+    pass
+
+
 AssistantAssociationInputDataTypeDef = TypedDict(
     "AssistantAssociationInputDataTypeDef",
     {
         "knowledgeBaseId": str,
     },
     total=False,
 )
@@ -229,25 +242,14 @@
 )
 
 
 class ContentSummaryTypeDef(_RequiredContentSummaryTypeDef, _OptionalContentSummaryTypeDef):
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
-
 _RequiredCreateContentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateContentRequestRequestTypeDef",
     {
         "knowledgeBaseId": str,
         "name": str,
         "uploadId": str,
     },
@@ -439,24 +441,36 @@
     "GetSessionRequestRequestTypeDef",
     {
         "assistantId": str,
         "sessionId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "assistantId": str,
+    },
+)
+_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef(
+    _RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
+    _OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAssistantAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssistantAssociationsRequestRequestTypeDef",
     {
         "assistantId": str,
     },
 )
 _OptionalListAssistantAssociationsRequestRequestTypeDef = TypedDict(
@@ -472,23 +486,53 @@
 class ListAssistantAssociationsRequestRequestTypeDef(
     _RequiredListAssistantAssociationsRequestRequestTypeDef,
     _OptionalListAssistantAssociationsRequestRequestTypeDef,
 ):
     pass
 
 
+ListAssistantsRequestListAssistantsPaginateTypeDef = TypedDict(
+    "ListAssistantsRequestListAssistantsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssistantsRequestRequestTypeDef = TypedDict(
     "ListAssistantsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListContentsRequestListContentsPaginateTypeDef = TypedDict(
+    "_RequiredListContentsRequestListContentsPaginateTypeDef",
+    {
+        "knowledgeBaseId": str,
+    },
+)
+_OptionalListContentsRequestListContentsPaginateTypeDef = TypedDict(
+    "_OptionalListContentsRequestListContentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListContentsRequestListContentsPaginateTypeDef(
+    _RequiredListContentsRequestListContentsPaginateTypeDef,
+    _OptionalListContentsRequestListContentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListContentsRequestRequestTypeDef = TypedDict(
     "_RequiredListContentsRequestRequestTypeDef",
     {
         "knowledgeBaseId": str,
     },
 )
 _OptionalListContentsRequestRequestTypeDef = TypedDict(
@@ -503,14 +547,22 @@
 
 class ListContentsRequestRequestTypeDef(
     _RequiredListContentsRequestRequestTypeDef, _OptionalListContentsRequestRequestTypeDef
 ):
     pass
 
 
+ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef = TypedDict(
+    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListKnowledgeBasesRequestRequestTypeDef = TypedDict(
     "ListKnowledgeBasesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -519,14 +571,22 @@
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
 NotifyRecommendationsReceivedErrorTypeDef = TypedDict(
     "NotifyRecommendationsReceivedErrorTypeDef",
     {
         "message": str,
         "recommendationId": str,
     },
     total=False,
@@ -537,14 +597,47 @@
     {
         "assistantId": str,
         "recommendationIds": Sequence[str],
         "sessionId": str,
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
+_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
+    "_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef",
+    {
+        "assistantId": str,
+        "queryText": str,
+    },
+)
+_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
+    "_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class QueryAssistantRequestQueryAssistantPaginateTypeDef(
+    _RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef,
+    _OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef,
+):
+    pass
+
+
 _RequiredQueryAssistantRequestRequestTypeDef = TypedDict(
     "_RequiredQueryAssistantRequestRequestTypeDef",
     {
         "assistantId": str,
         "queryText": str,
     },
 )
@@ -575,14 +668,25 @@
 RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef = TypedDict(
     "RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef",
     {
         "knowledgeBaseId": str,
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
 SessionSummaryTypeDef = TypedDict(
     "SessionSummaryTypeDef",
     {
         "assistantArn": str,
         "assistantId": str,
         "sessionArn": str,
         "sessionId": str,
@@ -593,14 +697,25 @@
     "StartContentUploadRequestRequestTypeDef",
     {
         "contentType": str,
         "knowledgeBaseId": str,
     },
 )
 
+StartContentUploadResponseTypeDef = TypedDict(
+    "StartContentUploadResponseTypeDef",
+    {
+        "headersToInclude": Dict[str, str],
+        "uploadId": str,
+        "url": str,
+        "urlExpiry": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -764,92 +879,73 @@
     pass
 
 
 CreateContentResponseTypeDef = TypedDict(
     "CreateContentResponseTypeDef",
     {
         "content": ContentDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContentResponseTypeDef = TypedDict(
     "GetContentResponseTypeDef",
     {
         "content": ContentDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateContentResponseTypeDef = TypedDict(
+    "UpdateContentResponseTypeDef",
+    {
+        "content": ContentDataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContentSummaryResponseTypeDef = TypedDict(
     "GetContentSummaryResponseTypeDef",
     {
         "contentSummary": ContentSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListContentsResponseTypeDef = TypedDict(
     "ListContentsResponseTypeDef",
     {
         "contentSummaries": List[ContentSummaryTypeDef],
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
 
 SearchContentResponseTypeDef = TypedDict(
     "SearchContentResponseTypeDef",
     {
         "contentSummaries": List[ContentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartContentUploadResponseTypeDef = TypedDict(
-    "StartContentUploadResponseTypeDef",
-    {
-        "headersToInclude": Dict[str, str],
-        "uploadId": str,
-        "url": str,
-        "urlExpiry": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateContentResponseTypeDef = TypedDict(
-    "UpdateContentResponseTypeDef",
-    {
-        "content": ContentDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSessionResponseTypeDef = TypedDict(
     "CreateSessionResponseTypeDef",
     {
         "session": SessionDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
         "session": SessionDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentTextTypeDef = TypedDict(
     "DocumentTextTypeDef",
     {
         "highlights": List[HighlightTypeDef],
@@ -861,103 +957,20 @@
 SearchExpressionTypeDef = TypedDict(
     "SearchExpressionTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
     },
 )
 
-_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
-    {
-        "assistantId": str,
-    },
-)
-_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef(
-    _RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
-    _OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
-):
-    pass
-
-
-ListAssistantsRequestListAssistantsPaginateTypeDef = TypedDict(
-    "ListAssistantsRequestListAssistantsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListContentsRequestListContentsPaginateTypeDef = TypedDict(
-    "_RequiredListContentsRequestListContentsPaginateTypeDef",
-    {
-        "knowledgeBaseId": str,
-    },
-)
-_OptionalListContentsRequestListContentsPaginateTypeDef = TypedDict(
-    "_OptionalListContentsRequestListContentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListContentsRequestListContentsPaginateTypeDef(
-    _RequiredListContentsRequestListContentsPaginateTypeDef,
-    _OptionalListContentsRequestListContentsPaginateTypeDef,
-):
-    pass
-
-
-ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef = TypedDict(
-    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
-    "_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef",
-    {
-        "assistantId": str,
-        "queryText": str,
-    },
-)
-_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
-    "_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class QueryAssistantRequestQueryAssistantPaginateTypeDef(
-    _RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef,
-    _OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef,
-):
-    pass
-
-
 NotifyRecommendationsReceivedResponseTypeDef = TypedDict(
     "NotifyRecommendationsReceivedResponseTypeDef",
     {
         "errors": List[NotifyRecommendationsReceivedErrorTypeDef],
         "recommendationIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecommendationTriggerDataTypeDef = TypedDict(
     "RecommendationTriggerDataTypeDef",
     {
         "query": QueryRecommendationTriggerDataTypeDef,
@@ -966,15 +979,15 @@
 )
 
 SearchSessionsResponseTypeDef = TypedDict(
     "SearchSessionsResponseTypeDef",
     {
         "nextToken": str,
         "sessionSummaries": List[SessionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateKnowledgeBaseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateKnowledgeBaseRequestRequestTypeDef",
     {
         "knowledgeBaseType": KnowledgeBaseTypeType,
@@ -1113,32 +1126,32 @@
     pass
 
 
 CreateAssistantResponseTypeDef = TypedDict(
     "CreateAssistantResponseTypeDef",
     {
         "assistant": AssistantDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssistantResponseTypeDef = TypedDict(
     "GetAssistantResponseTypeDef",
     {
         "assistant": AssistantDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssistantsResponseTypeDef = TypedDict(
     "ListAssistantsResponseTypeDef",
     {
         "assistantSummaries": List[AssistantSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDocumentTypeDef = TypedDict(
     "_RequiredDocumentTypeDef",
     {
         "contentReference": ContentReferenceTypeDef,
@@ -1187,15 +1200,15 @@
         "knowledgeBaseId": str,
         "searchExpression": SearchExpressionTypeDef,
     },
 )
 _OptionalSearchContentRequestSearchContentPaginateTypeDef = TypedDict(
     "_OptionalSearchContentRequestSearchContentPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class SearchContentRequestSearchContentPaginateTypeDef(
     _RequiredSearchContentRequestSearchContentPaginateTypeDef,
@@ -1233,15 +1246,15 @@
         "assistantId": str,
         "searchExpression": SearchExpressionTypeDef,
     },
 )
 _OptionalSearchSessionsRequestSearchSessionsPaginateTypeDef = TypedDict(
     "_OptionalSearchSessionsRequestSearchSessionsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class SearchSessionsRequestSearchSessionsPaginateTypeDef(
     _RequiredSearchSessionsRequestSearchSessionsPaginateTypeDef,
@@ -1261,65 +1274,65 @@
     },
 )
 
 CreateKnowledgeBaseResponseTypeDef = TypedDict(
     "CreateKnowledgeBaseResponseTypeDef",
     {
         "knowledgeBase": KnowledgeBaseDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKnowledgeBaseResponseTypeDef = TypedDict(
     "GetKnowledgeBaseResponseTypeDef",
     {
         "knowledgeBase": KnowledgeBaseDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateKnowledgeBaseTemplateUriResponseTypeDef = TypedDict(
     "UpdateKnowledgeBaseTemplateUriResponseTypeDef",
     {
         "knowledgeBase": KnowledgeBaseDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListKnowledgeBasesResponseTypeDef = TypedDict(
     "ListKnowledgeBasesResponseTypeDef",
     {
         "knowledgeBaseSummaries": List[KnowledgeBaseSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssistantAssociationResponseTypeDef = TypedDict(
     "CreateAssistantAssociationResponseTypeDef",
     {
         "assistantAssociation": AssistantAssociationDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssistantAssociationResponseTypeDef = TypedDict(
     "GetAssistantAssociationResponseTypeDef",
     {
         "assistantAssociation": AssistantAssociationDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssistantAssociationsResponseTypeDef = TypedDict(
     "ListAssistantAssociationsResponseTypeDef",
     {
         "assistantAssociationSummaries": List[AssistantAssociationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRecommendationDataTypeDef = TypedDict(
     "_RequiredRecommendationDataTypeDef",
     {
         "document": DocumentTypeDef,
@@ -1364,19 +1377,19 @@
 
 
 GetRecommendationsResponseTypeDef = TypedDict(
     "GetRecommendationsResponseTypeDef",
     {
         "recommendations": List[RecommendationDataTypeDef],
         "triggers": List[RecommendationTriggerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryAssistantResponseTypeDef = TypedDict(
     "QueryAssistantResponseTypeDef",
     {
         "nextToken": str,
         "results": List[ResultDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom/type_defs.pyi` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -37,15 +37,14 @@
     "AppIntegrationsConfigurationTypeDef",
     "AssistantAssociationInputDataTypeDef",
     "KnowledgeBaseAssociationDataTypeDef",
     "ServerSideEncryptionConfigurationTypeDef",
     "ContentDataTypeDef",
     "ContentReferenceTypeDef",
     "ContentSummaryTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateContentRequestRequestTypeDef",
     "RenderingConfigurationTypeDef",
     "CreateSessionRequestRequestTypeDef",
     "SessionDataTypeDef",
     "DeleteAssistantAssociationRequestRequestTypeDef",
     "DeleteAssistantRequestRequestTypeDef",
     "DeleteContentRequestRequestTypeDef",
@@ -55,54 +54,55 @@
     "GetAssistantAssociationRequestRequestTypeDef",
     "GetAssistantRequestRequestTypeDef",
     "GetContentRequestRequestTypeDef",
     "GetContentSummaryRequestRequestTypeDef",
     "GetKnowledgeBaseRequestRequestTypeDef",
     "GetRecommendationsRequestRequestTypeDef",
     "GetSessionRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
     "ListAssistantAssociationsRequestRequestTypeDef",
+    "ListAssistantsRequestListAssistantsPaginateTypeDef",
     "ListAssistantsRequestRequestTypeDef",
+    "ListContentsRequestListContentsPaginateTypeDef",
     "ListContentsRequestRequestTypeDef",
+    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
     "ListKnowledgeBasesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NotifyRecommendationsReceivedErrorTypeDef",
     "NotifyRecommendationsReceivedRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "QueryAssistantRequestQueryAssistantPaginateTypeDef",
     "QueryAssistantRequestRequestTypeDef",
     "QueryRecommendationTriggerDataTypeDef",
     "RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SessionSummaryTypeDef",
     "StartContentUploadRequestRequestTypeDef",
+    "StartContentUploadResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateContentRequestRequestTypeDef",
     "UpdateKnowledgeBaseTemplateUriRequestRequestTypeDef",
     "SourceConfigurationTypeDef",
     "CreateAssistantAssociationRequestRequestTypeDef",
     "AssistantAssociationOutputDataTypeDef",
     "AssistantDataTypeDef",
     "AssistantSummaryTypeDef",
     "CreateAssistantRequestRequestTypeDef",
     "CreateContentResponseTypeDef",
     "GetContentResponseTypeDef",
+    "UpdateContentResponseTypeDef",
     "GetContentSummaryResponseTypeDef",
     "ListContentsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "SearchContentResponseTypeDef",
-    "StartContentUploadResponseTypeDef",
-    "UpdateContentResponseTypeDef",
     "CreateSessionResponseTypeDef",
     "GetSessionResponseTypeDef",
     "DocumentTextTypeDef",
     "SearchExpressionTypeDef",
-    "ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
-    "ListAssistantsRequestListAssistantsPaginateTypeDef",
-    "ListContentsRequestListContentsPaginateTypeDef",
-    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
-    "QueryAssistantRequestQueryAssistantPaginateTypeDef",
     "NotifyRecommendationsReceivedResponseTypeDef",
     "RecommendationTriggerDataTypeDef",
     "SearchSessionsResponseTypeDef",
     "CreateKnowledgeBaseRequestRequestTypeDef",
     "KnowledgeBaseDataTypeDef",
     "KnowledgeBaseSummaryTypeDef",
     "AssistantAssociationDataTypeDef",
@@ -125,22 +125,33 @@
     "ListAssistantAssociationsResponseTypeDef",
     "RecommendationDataTypeDef",
     "ResultDataTypeDef",
     "GetRecommendationsResponseTypeDef",
     "QueryAssistantResponseTypeDef",
 )
 
-AppIntegrationsConfigurationTypeDef = TypedDict(
-    "AppIntegrationsConfigurationTypeDef",
+_RequiredAppIntegrationsConfigurationTypeDef = TypedDict(
+    "_RequiredAppIntegrationsConfigurationTypeDef",
     {
         "appIntegrationArn": str,
+    },
+)
+_OptionalAppIntegrationsConfigurationTypeDef = TypedDict(
+    "_OptionalAppIntegrationsConfigurationTypeDef",
+    {
         "objectFields": Sequence[str],
     },
+    total=False,
 )
 
+class AppIntegrationsConfigurationTypeDef(
+    _RequiredAppIntegrationsConfigurationTypeDef, _OptionalAppIntegrationsConfigurationTypeDef
+):
+    pass
+
 AssistantAssociationInputDataTypeDef = TypedDict(
     "AssistantAssociationInputDataTypeDef",
     {
         "knowledgeBaseId": str,
     },
     total=False,
 )
@@ -224,25 +235,14 @@
     },
     total=False,
 )
 
 class ContentSummaryTypeDef(_RequiredContentSummaryTypeDef, _OptionalContentSummaryTypeDef):
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
-
 _RequiredCreateContentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateContentRequestRequestTypeDef",
     {
         "knowledgeBaseId": str,
         "name": str,
         "uploadId": str,
     },
@@ -426,24 +426,34 @@
     "GetSessionRequestRequestTypeDef",
     {
         "assistantId": str,
         "sessionId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "assistantId": str,
+    },
+)
+_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef(
+    _RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
+    _OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListAssistantAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssistantAssociationsRequestRequestTypeDef",
     {
         "assistantId": str,
     },
 )
 _OptionalListAssistantAssociationsRequestRequestTypeDef = TypedDict(
@@ -457,23 +467,51 @@
 
 class ListAssistantAssociationsRequestRequestTypeDef(
     _RequiredListAssistantAssociationsRequestRequestTypeDef,
     _OptionalListAssistantAssociationsRequestRequestTypeDef,
 ):
     pass
 
+ListAssistantsRequestListAssistantsPaginateTypeDef = TypedDict(
+    "ListAssistantsRequestListAssistantsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssistantsRequestRequestTypeDef = TypedDict(
     "ListAssistantsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListContentsRequestListContentsPaginateTypeDef = TypedDict(
+    "_RequiredListContentsRequestListContentsPaginateTypeDef",
+    {
+        "knowledgeBaseId": str,
+    },
+)
+_OptionalListContentsRequestListContentsPaginateTypeDef = TypedDict(
+    "_OptionalListContentsRequestListContentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListContentsRequestListContentsPaginateTypeDef(
+    _RequiredListContentsRequestListContentsPaginateTypeDef,
+    _OptionalListContentsRequestListContentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListContentsRequestRequestTypeDef = TypedDict(
     "_RequiredListContentsRequestRequestTypeDef",
     {
         "knowledgeBaseId": str,
     },
 )
 _OptionalListContentsRequestRequestTypeDef = TypedDict(
@@ -486,14 +524,22 @@
 )
 
 class ListContentsRequestRequestTypeDef(
     _RequiredListContentsRequestRequestTypeDef, _OptionalListContentsRequestRequestTypeDef
 ):
     pass
 
+ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef = TypedDict(
+    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListKnowledgeBasesRequestRequestTypeDef = TypedDict(
     "ListKnowledgeBasesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -502,14 +548,22 @@
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
 NotifyRecommendationsReceivedErrorTypeDef = TypedDict(
     "NotifyRecommendationsReceivedErrorTypeDef",
     {
         "message": str,
         "recommendationId": str,
     },
     total=False,
@@ -520,14 +574,45 @@
     {
         "assistantId": str,
         "recommendationIds": Sequence[str],
         "sessionId": str,
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
+_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
+    "_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef",
+    {
+        "assistantId": str,
+        "queryText": str,
+    },
+)
+_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
+    "_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class QueryAssistantRequestQueryAssistantPaginateTypeDef(
+    _RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef,
+    _OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef,
+):
+    pass
+
 _RequiredQueryAssistantRequestRequestTypeDef = TypedDict(
     "_RequiredQueryAssistantRequestRequestTypeDef",
     {
         "assistantId": str,
         "queryText": str,
     },
 )
@@ -556,14 +641,25 @@
 RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef = TypedDict(
     "RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef",
     {
         "knowledgeBaseId": str,
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
 SessionSummaryTypeDef = TypedDict(
     "SessionSummaryTypeDef",
     {
         "assistantArn": str,
         "assistantId": str,
         "sessionArn": str,
         "sessionId": str,
@@ -574,14 +670,25 @@
     "StartContentUploadRequestRequestTypeDef",
     {
         "contentType": str,
         "knowledgeBaseId": str,
     },
 )
 
+StartContentUploadResponseTypeDef = TypedDict(
+    "StartContentUploadResponseTypeDef",
+    {
+        "headersToInclude": Dict[str, str],
+        "uploadId": str,
+        "url": str,
+        "urlExpiry": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -735,92 +842,73 @@
 ):
     pass
 
 CreateContentResponseTypeDef = TypedDict(
     "CreateContentResponseTypeDef",
     {
         "content": ContentDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContentResponseTypeDef = TypedDict(
     "GetContentResponseTypeDef",
     {
         "content": ContentDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateContentResponseTypeDef = TypedDict(
+    "UpdateContentResponseTypeDef",
+    {
+        "content": ContentDataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContentSummaryResponseTypeDef = TypedDict(
     "GetContentSummaryResponseTypeDef",
     {
         "contentSummary": ContentSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListContentsResponseTypeDef = TypedDict(
     "ListContentsResponseTypeDef",
     {
         "contentSummaries": List[ContentSummaryTypeDef],
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
 
 SearchContentResponseTypeDef = TypedDict(
     "SearchContentResponseTypeDef",
     {
         "contentSummaries": List[ContentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartContentUploadResponseTypeDef = TypedDict(
-    "StartContentUploadResponseTypeDef",
-    {
-        "headersToInclude": Dict[str, str],
-        "uploadId": str,
-        "url": str,
-        "urlExpiry": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateContentResponseTypeDef = TypedDict(
-    "UpdateContentResponseTypeDef",
-    {
-        "content": ContentDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSessionResponseTypeDef = TypedDict(
     "CreateSessionResponseTypeDef",
     {
         "session": SessionDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
         "session": SessionDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentTextTypeDef = TypedDict(
     "DocumentTextTypeDef",
     {
         "highlights": List[HighlightTypeDef],
@@ -832,97 +920,20 @@
 SearchExpressionTypeDef = TypedDict(
     "SearchExpressionTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
     },
 )
 
-_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
-    {
-        "assistantId": str,
-    },
-)
-_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef(
-    _RequiredListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
-    _OptionalListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
-):
-    pass
-
-ListAssistantsRequestListAssistantsPaginateTypeDef = TypedDict(
-    "ListAssistantsRequestListAssistantsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListContentsRequestListContentsPaginateTypeDef = TypedDict(
-    "_RequiredListContentsRequestListContentsPaginateTypeDef",
-    {
-        "knowledgeBaseId": str,
-    },
-)
-_OptionalListContentsRequestListContentsPaginateTypeDef = TypedDict(
-    "_OptionalListContentsRequestListContentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListContentsRequestListContentsPaginateTypeDef(
-    _RequiredListContentsRequestListContentsPaginateTypeDef,
-    _OptionalListContentsRequestListContentsPaginateTypeDef,
-):
-    pass
-
-ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef = TypedDict(
-    "ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
-    "_RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef",
-    {
-        "assistantId": str,
-        "queryText": str,
-    },
-)
-_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef = TypedDict(
-    "_OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class QueryAssistantRequestQueryAssistantPaginateTypeDef(
-    _RequiredQueryAssistantRequestQueryAssistantPaginateTypeDef,
-    _OptionalQueryAssistantRequestQueryAssistantPaginateTypeDef,
-):
-    pass
-
 NotifyRecommendationsReceivedResponseTypeDef = TypedDict(
     "NotifyRecommendationsReceivedResponseTypeDef",
     {
         "errors": List[NotifyRecommendationsReceivedErrorTypeDef],
         "recommendationIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecommendationTriggerDataTypeDef = TypedDict(
     "RecommendationTriggerDataTypeDef",
     {
         "query": QueryRecommendationTriggerDataTypeDef,
@@ -931,15 +942,15 @@
 )
 
 SearchSessionsResponseTypeDef = TypedDict(
     "SearchSessionsResponseTypeDef",
     {
         "nextToken": str,
         "sessionSummaries": List[SessionSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateKnowledgeBaseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateKnowledgeBaseRequestRequestTypeDef",
     {
         "knowledgeBaseType": KnowledgeBaseTypeType,
@@ -1068,32 +1079,32 @@
 ):
     pass
 
 CreateAssistantResponseTypeDef = TypedDict(
     "CreateAssistantResponseTypeDef",
     {
         "assistant": AssistantDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssistantResponseTypeDef = TypedDict(
     "GetAssistantResponseTypeDef",
     {
         "assistant": AssistantDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssistantsResponseTypeDef = TypedDict(
     "ListAssistantsResponseTypeDef",
     {
         "assistantSummaries": List[AssistantSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDocumentTypeDef = TypedDict(
     "_RequiredDocumentTypeDef",
     {
         "contentReference": ContentReferenceTypeDef,
@@ -1138,15 +1149,15 @@
         "knowledgeBaseId": str,
         "searchExpression": SearchExpressionTypeDef,
     },
 )
 _OptionalSearchContentRequestSearchContentPaginateTypeDef = TypedDict(
     "_OptionalSearchContentRequestSearchContentPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class SearchContentRequestSearchContentPaginateTypeDef(
     _RequiredSearchContentRequestSearchContentPaginateTypeDef,
     _OptionalSearchContentRequestSearchContentPaginateTypeDef,
@@ -1180,15 +1191,15 @@
         "assistantId": str,
         "searchExpression": SearchExpressionTypeDef,
     },
 )
 _OptionalSearchSessionsRequestSearchSessionsPaginateTypeDef = TypedDict(
     "_OptionalSearchSessionsRequestSearchSessionsPaginateTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class SearchSessionsRequestSearchSessionsPaginateTypeDef(
     _RequiredSearchSessionsRequestSearchSessionsPaginateTypeDef,
     _OptionalSearchSessionsRequestSearchSessionsPaginateTypeDef,
@@ -1206,65 +1217,65 @@
     },
 )
 
 CreateKnowledgeBaseResponseTypeDef = TypedDict(
     "CreateKnowledgeBaseResponseTypeDef",
     {
         "knowledgeBase": KnowledgeBaseDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKnowledgeBaseResponseTypeDef = TypedDict(
     "GetKnowledgeBaseResponseTypeDef",
     {
         "knowledgeBase": KnowledgeBaseDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateKnowledgeBaseTemplateUriResponseTypeDef = TypedDict(
     "UpdateKnowledgeBaseTemplateUriResponseTypeDef",
     {
         "knowledgeBase": KnowledgeBaseDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListKnowledgeBasesResponseTypeDef = TypedDict(
     "ListKnowledgeBasesResponseTypeDef",
     {
         "knowledgeBaseSummaries": List[KnowledgeBaseSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAssistantAssociationResponseTypeDef = TypedDict(
     "CreateAssistantAssociationResponseTypeDef",
     {
         "assistantAssociation": AssistantAssociationDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAssistantAssociationResponseTypeDef = TypedDict(
     "GetAssistantAssociationResponseTypeDef",
     {
         "assistantAssociation": AssistantAssociationDataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssistantAssociationsResponseTypeDef = TypedDict(
     "ListAssistantAssociationsResponseTypeDef",
     {
         "assistantAssociationSummaries": List[AssistantAssociationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRecommendationDataTypeDef = TypedDict(
     "_RequiredRecommendationDataTypeDef",
     {
         "document": DocumentTypeDef,
@@ -1305,19 +1316,19 @@
     pass
 
 GetRecommendationsResponseTypeDef = TypedDict(
     "GetRecommendationsResponseTypeDef",
     {
         "recommendations": List[RecommendationDataTypeDef],
         "triggers": List[RecommendationTriggerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryAssistantResponseTypeDef = TypedDict(
     "QueryAssistantResponseTypeDef",
     {
         "nextToken": str,
         "results": List[ResultDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/PKG-INFO` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-wisdom
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConnectWisdomService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConnectWisdomService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-wisdom"></a>
 
 # types-aiobotocore-wisdom
 
 [![PyPI - types-aiobotocore-wisdom](https://img.shields.io/pypi/v/types-aiobotocore-wisdom.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wisdom)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wisdom.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wisdom)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wisdom?color=blue)](https://pypistats.org/packages/types-aiobotocore-wisdom)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConnectWisdomService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService)
+[aiobotocore.ConnectWisdomService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wisdom.html#ConnectWisdomService)
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
 [types-aiobotocore-wisdom docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wisdom/).
 
 See how it helps to find and fix potential bugs:
 
@@ -357,15 +357,14 @@
     AppIntegrationsConfigurationTypeDef,
     AssistantAssociationInputDataTypeDef,
     KnowledgeBaseAssociationDataTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     ContentDataTypeDef,
     ContentReferenceTypeDef,
     ContentSummaryTypeDef,
-    ResponseMetadataTypeDef,
     CreateContentRequestRequestTypeDef,
     RenderingConfigurationTypeDef,
     CreateSessionRequestRequestTypeDef,
     SessionDataTypeDef,
     DeleteAssistantAssociationRequestRequestTypeDef,
     DeleteAssistantRequestRequestTypeDef,
     DeleteContentRequestRequestTypeDef,
@@ -375,54 +374,55 @@
     GetAssistantAssociationRequestRequestTypeDef,
     GetAssistantRequestRequestTypeDef,
     GetContentRequestRequestTypeDef,
     GetContentSummaryRequestRequestTypeDef,
     GetKnowledgeBaseRequestRequestTypeDef,
     GetRecommendationsRequestRequestTypeDef,
     GetSessionRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
     ListAssistantAssociationsRequestRequestTypeDef,
+    ListAssistantsRequestListAssistantsPaginateTypeDef,
     ListAssistantsRequestRequestTypeDef,
+    ListContentsRequestListContentsPaginateTypeDef,
     ListContentsRequestRequestTypeDef,
+    ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef,
     ListKnowledgeBasesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NotifyRecommendationsReceivedErrorTypeDef,
     NotifyRecommendationsReceivedRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    QueryAssistantRequestQueryAssistantPaginateTypeDef,
     QueryAssistantRequestRequestTypeDef,
     QueryRecommendationTriggerDataTypeDef,
     RemoveKnowledgeBaseTemplateUriRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SessionSummaryTypeDef,
     StartContentUploadRequestRequestTypeDef,
+    StartContentUploadResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateContentRequestRequestTypeDef,
     UpdateKnowledgeBaseTemplateUriRequestRequestTypeDef,
     SourceConfigurationTypeDef,
     CreateAssistantAssociationRequestRequestTypeDef,
     AssistantAssociationOutputDataTypeDef,
     AssistantDataTypeDef,
     AssistantSummaryTypeDef,
     CreateAssistantRequestRequestTypeDef,
     CreateContentResponseTypeDef,
     GetContentResponseTypeDef,
+    UpdateContentResponseTypeDef,
     GetContentSummaryResponseTypeDef,
     ListContentsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     SearchContentResponseTypeDef,
-    StartContentUploadResponseTypeDef,
-    UpdateContentResponseTypeDef,
     CreateSessionResponseTypeDef,
     GetSessionResponseTypeDef,
     DocumentTextTypeDef,
     SearchExpressionTypeDef,
-    ListAssistantAssociationsRequestListAssistantAssociationsPaginateTypeDef,
-    ListAssistantsRequestListAssistantsPaginateTypeDef,
-    ListContentsRequestListContentsPaginateTypeDef,
-    ListKnowledgeBasesRequestListKnowledgeBasesPaginateTypeDef,
-    QueryAssistantRequestQueryAssistantPaginateTypeDef,
     NotifyRecommendationsReceivedResponseTypeDef,
     RecommendationTriggerDataTypeDef,
     SearchSessionsResponseTypeDef,
     CreateKnowledgeBaseRequestRequestTypeDef,
     KnowledgeBaseDataTypeDef,
     KnowledgeBaseSummaryTypeDef,
     AssistantAssociationDataTypeDef,
@@ -457,43 +457,43 @@
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

### Comparing `types-aiobotocore-wisdom-2.5.0.post1/types_aiobotocore_wisdom.egg-info/SOURCES.txt` & `types-aiobotocore-wisdom-2.5.1/types_aiobotocore_wisdom.egg-info/SOURCES.txt`

 * *Files identical despite different names*

