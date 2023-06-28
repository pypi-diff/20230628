# Comparing `tmp/types-aiobotocore-lex-models-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lex-models-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lex-models-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:53 2023, max compression
+gzip compressed data, was "types-aiobotocore-lex-models-2.5.1.tar", last modified: Wed Jun 28 01:43:44 2023, max compression
```

## Comparing `types-aiobotocore-lex-models-2.5.0.post1.tar` & `types-aiobotocore-lex-models-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.707367 types-aiobotocore-lex-models-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19641 2023-03-11 12:26:53.707367 types-aiobotocore-lex-models-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18045 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:53.707367 types-aiobotocore-lex-models-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2158 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.707367 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/
--rw-r--r--   0 runner    (1001) docker     (123)     2570 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2569 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    37373 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    37312 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10941 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10939 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12787 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12774 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    46009 2023-03-11 12:17:16.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    45956 2023-03-11 12:17:16.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:15.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.707367 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19641 2023-03-11 12:26:53.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:53.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:53.000000 types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.966166 types-aiobotocore-lex-models-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19636 2023-06-28 01:43:44.966166 types-aiobotocore-lex-models-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18046 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:44.966166 types-aiobotocore-lex-models-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.966166 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/
+-rw-r--r--   0 runner    (1001) docker     (123)     2570 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2569 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37384 2023-06-28 01:33:56.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37323 2023-06-28 01:33:56.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11150 2023-06-28 01:33:56.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11148 2023-06-28 01:33:56.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12687 2023-06-28 01:33:56.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12675 2023-06-28 01:33:56.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    46093 2023-06-28 01:33:57.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46040 2023-06-28 01:33:56.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:55.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.966166 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19636 2023-06-28 01:43:44.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:44.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:44.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:44.000000 types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/LICENSE` & `types-aiobotocore-lex-models-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lex-models-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lex-models
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LexModelBuildingService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LexModelBuildingService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lex-models"></a>
 
 # types-aiobotocore-lex-models
 
 [![PyPI - types-aiobotocore-lex-models](https://img.shields.io/pypi/v/types-aiobotocore-lex-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-models)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lex-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-models)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lex-models?color=blue)](https://pypistats.org/packages/types-aiobotocore-lex-models)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexModelBuildingService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService)
+[aiobotocore.LexModelBuildingService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService)
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
 [types-aiobotocore-lex-models docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/).
 
 See how it helps to find and fix potential bugs:
 
@@ -386,15 +386,14 @@
     BuiltinIntentSlotTypeDef,
     BuiltinSlotTypeMetadataTypeDef,
     CodeHookTypeDef,
     LogSettingsRequestTypeDef,
     LogSettingsResponseTypeDef,
     CreateBotVersionRequestRequestTypeDef,
     IntentTypeDef,
-    ResponseMetadataTypeDef,
     CreateIntentVersionRequestRequestTypeDef,
     InputContextTypeDef,
     KendraConfigurationTypeDef,
     OutputContextTypeDef,
     CreateSlotTypeVersionRequestRequestTypeDef,
     EnumerationValueTypeDef,
     DeleteBotAliasRequestRequestTypeDef,
@@ -402,72 +401,73 @@
     DeleteBotRequestRequestTypeDef,
     DeleteBotVersionRequestRequestTypeDef,
     DeleteIntentRequestRequestTypeDef,
     DeleteIntentVersionRequestRequestTypeDef,
     DeleteSlotTypeRequestRequestTypeDef,
     DeleteSlotTypeVersionRequestRequestTypeDef,
     DeleteUtterancesRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetBotAliasRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetBotAliasesRequestGetBotAliasesPaginateTypeDef,
     GetBotAliasesRequestRequestTypeDef,
     GetBotChannelAssociationRequestRequestTypeDef,
+    GetBotChannelAssociationResponseTypeDef,
+    GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
     GetBotChannelAssociationsRequestRequestTypeDef,
     GetBotRequestRequestTypeDef,
+    GetBotVersionsRequestGetBotVersionsPaginateTypeDef,
     GetBotVersionsRequestRequestTypeDef,
+    GetBotsRequestGetBotsPaginateTypeDef,
     GetBotsRequestRequestTypeDef,
     GetBuiltinIntentRequestRequestTypeDef,
+    GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef,
     GetBuiltinIntentsRequestRequestTypeDef,
+    GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef,
     GetBuiltinSlotTypesRequestRequestTypeDef,
     GetExportRequestRequestTypeDef,
+    GetExportResponseTypeDef,
     GetImportRequestRequestTypeDef,
+    GetImportResponseTypeDef,
     GetIntentRequestRequestTypeDef,
+    GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
     GetIntentVersionsRequestRequestTypeDef,
     IntentMetadataTypeDef,
+    GetIntentsRequestGetIntentsPaginateTypeDef,
     GetIntentsRequestRequestTypeDef,
     GetMigrationRequestRequestTypeDef,
     MigrationAlertTypeDef,
     GetMigrationsRequestRequestTypeDef,
     MigrationSummaryTypeDef,
     GetSlotTypeRequestRequestTypeDef,
+    GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
     GetSlotTypeVersionsRequestRequestTypeDef,
     SlotTypeMetadataTypeDef,
+    GetSlotTypesRequestGetSlotTypesPaginateTypeDef,
     GetSlotTypesRequestRequestTypeDef,
     GetUtterancesViewRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     MessageTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SlotDefaultValueTypeDef,
     SlotTypeRegexConfigurationTypeDef,
     StartMigrationRequestRequestTypeDef,
+    StartMigrationResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UtteranceDataTypeDef,
-    FulfillmentActivityTypeDef,
-    ConversationLogsRequestTypeDef,
-    ConversationLogsResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetBotChannelAssociationResponseTypeDef,
     GetBotChannelAssociationsResponseTypeDef,
     GetBotVersionsResponseTypeDef,
     GetBotsResponseTypeDef,
-    GetBuiltinIntentResponseTypeDef,
     GetBuiltinIntentsResponseTypeDef,
+    GetBuiltinIntentResponseTypeDef,
     GetBuiltinSlotTypesResponseTypeDef,
-    GetExportResponseTypeDef,
-    GetImportResponseTypeDef,
-    StartMigrationResponseTypeDef,
-    GetBotAliasesRequestGetBotAliasesPaginateTypeDef,
-    GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
-    GetBotVersionsRequestGetBotVersionsPaginateTypeDef,
-    GetBotsRequestGetBotsPaginateTypeDef,
-    GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef,
-    GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef,
-    GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
-    GetIntentsRequestGetIntentsPaginateTypeDef,
-    GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
-    GetSlotTypesRequestGetSlotTypesPaginateTypeDef,
+    FulfillmentActivityTypeDef,
+    ConversationLogsRequestTypeDef,
+    ConversationLogsResponseTypeDef,
     GetIntentVersionsResponseTypeDef,
     GetIntentsResponseTypeDef,
     GetMigrationResponseTypeDef,
     GetMigrationsResponseTypeDef,
     GetSlotTypeVersionsResponseTypeDef,
     GetSlotTypesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -509,43 +509,43 @@
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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/README.md` & `types-aiobotocore-lex-models-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lex-models"></a>
 
 # types-aiobotocore-lex-models
 
 [![PyPI - types-aiobotocore-lex-models](https://img.shields.io/pypi/v/types-aiobotocore-lex-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-models)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lex-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-models)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lex-models?color=blue)](https://pypistats.org/packages/types-aiobotocore-lex-models)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexModelBuildingService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService)
+[aiobotocore.LexModelBuildingService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService)
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
 [types-aiobotocore-lex-models docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/).
 
 See how it helps to find and fix potential bugs:
 
@@ -353,15 +353,14 @@
     BuiltinIntentSlotTypeDef,
     BuiltinSlotTypeMetadataTypeDef,
     CodeHookTypeDef,
     LogSettingsRequestTypeDef,
     LogSettingsResponseTypeDef,
     CreateBotVersionRequestRequestTypeDef,
     IntentTypeDef,
-    ResponseMetadataTypeDef,
     CreateIntentVersionRequestRequestTypeDef,
     InputContextTypeDef,
     KendraConfigurationTypeDef,
     OutputContextTypeDef,
     CreateSlotTypeVersionRequestRequestTypeDef,
     EnumerationValueTypeDef,
     DeleteBotAliasRequestRequestTypeDef,
@@ -369,72 +368,73 @@
     DeleteBotRequestRequestTypeDef,
     DeleteBotVersionRequestRequestTypeDef,
     DeleteIntentRequestRequestTypeDef,
     DeleteIntentVersionRequestRequestTypeDef,
     DeleteSlotTypeRequestRequestTypeDef,
     DeleteSlotTypeVersionRequestRequestTypeDef,
     DeleteUtterancesRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetBotAliasRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetBotAliasesRequestGetBotAliasesPaginateTypeDef,
     GetBotAliasesRequestRequestTypeDef,
     GetBotChannelAssociationRequestRequestTypeDef,
+    GetBotChannelAssociationResponseTypeDef,
+    GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
     GetBotChannelAssociationsRequestRequestTypeDef,
     GetBotRequestRequestTypeDef,
+    GetBotVersionsRequestGetBotVersionsPaginateTypeDef,
     GetBotVersionsRequestRequestTypeDef,
+    GetBotsRequestGetBotsPaginateTypeDef,
     GetBotsRequestRequestTypeDef,
     GetBuiltinIntentRequestRequestTypeDef,
+    GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef,
     GetBuiltinIntentsRequestRequestTypeDef,
+    GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef,
     GetBuiltinSlotTypesRequestRequestTypeDef,
     GetExportRequestRequestTypeDef,
+    GetExportResponseTypeDef,
     GetImportRequestRequestTypeDef,
+    GetImportResponseTypeDef,
     GetIntentRequestRequestTypeDef,
+    GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
     GetIntentVersionsRequestRequestTypeDef,
     IntentMetadataTypeDef,
+    GetIntentsRequestGetIntentsPaginateTypeDef,
     GetIntentsRequestRequestTypeDef,
     GetMigrationRequestRequestTypeDef,
     MigrationAlertTypeDef,
     GetMigrationsRequestRequestTypeDef,
     MigrationSummaryTypeDef,
     GetSlotTypeRequestRequestTypeDef,
+    GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
     GetSlotTypeVersionsRequestRequestTypeDef,
     SlotTypeMetadataTypeDef,
+    GetSlotTypesRequestGetSlotTypesPaginateTypeDef,
     GetSlotTypesRequestRequestTypeDef,
     GetUtterancesViewRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     MessageTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SlotDefaultValueTypeDef,
     SlotTypeRegexConfigurationTypeDef,
     StartMigrationRequestRequestTypeDef,
+    StartMigrationResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UtteranceDataTypeDef,
-    FulfillmentActivityTypeDef,
-    ConversationLogsRequestTypeDef,
-    ConversationLogsResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetBotChannelAssociationResponseTypeDef,
     GetBotChannelAssociationsResponseTypeDef,
     GetBotVersionsResponseTypeDef,
     GetBotsResponseTypeDef,
-    GetBuiltinIntentResponseTypeDef,
     GetBuiltinIntentsResponseTypeDef,
+    GetBuiltinIntentResponseTypeDef,
     GetBuiltinSlotTypesResponseTypeDef,
-    GetExportResponseTypeDef,
-    GetImportResponseTypeDef,
-    StartMigrationResponseTypeDef,
-    GetBotAliasesRequestGetBotAliasesPaginateTypeDef,
-    GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
-    GetBotVersionsRequestGetBotVersionsPaginateTypeDef,
-    GetBotsRequestGetBotsPaginateTypeDef,
-    GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef,
-    GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef,
-    GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
-    GetIntentsRequestGetIntentsPaginateTypeDef,
-    GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
-    GetSlotTypesRequestGetSlotTypesPaginateTypeDef,
+    FulfillmentActivityTypeDef,
+    ConversationLogsRequestTypeDef,
+    ConversationLogsResponseTypeDef,
     GetIntentVersionsResponseTypeDef,
     GetIntentsResponseTypeDef,
     GetMigrationResponseTypeDef,
     GetMigrationsResponseTypeDef,
     GetSlotTypeVersionsResponseTypeDef,
     GetSlotTypesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -476,43 +476,43 @@
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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/setup.py` & `types-aiobotocore-lex-models-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lex-models.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lex-models",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lex_models"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LexModelBuildingService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LexModelBuildingService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/"
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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/__init__.py` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/__init__.pyi` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/__main__.py` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LexModelBuildingService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LexModelBuildingService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService\nOther"
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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/client.py` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -343,15 +343,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_bot_versions)
         """
 
     async def get_bots(
         self, *, nextToken: str = ..., maxResults: int = ..., nameContains: str = ...
     ) -> GetBotsResponseTypeDef:
         """
-        Returns bot information as follows * If you provide the `nameContains` field,
+        Returns bot information as follows: * If you provide the `nameContains` field,
         the response includes information for the `$LATEST` version of all bots whose
         name contains the specified string.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bots)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_bots)
         """
 
@@ -429,16 +429,17 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_intent_versions)
         """
 
     async def get_intents(
         self, *, nextToken: str = ..., maxResults: int = ..., nameContains: str = ...
     ) -> GetIntentsResponseTypeDef:
         """
-        Returns intent information as follows * If you specify the `nameContains` field,
-        returns the `$LATEST` version of all intents that contain the specified string.
+        Returns intent information as follows: * If you specify the `nameContains`
+        field, returns the `$LATEST` version of all intents that contain the specified
+        string.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_intents)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_intents)
         """
 
     async def get_migration(self, *, migrationId: str) -> GetMigrationResponseTypeDef:
         """
@@ -484,15 +485,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_slot_type_versions)
         """
 
     async def get_slot_types(
         self, *, nextToken: str = ..., maxResults: int = ..., nameContains: str = ...
     ) -> GetSlotTypesResponseTypeDef:
         """
-        Returns slot type information as follows * If you specify the `nameContains`
+        Returns slot type information as follows: * If you specify the `nameContains`
         field, returns the `$LATEST` version of all slot types that contain the
         specified string.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_slot_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_slot_types)
         """
```

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/client.pyi` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -317,15 +317,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bot_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_bot_versions)
         """
     async def get_bots(
         self, *, nextToken: str = ..., maxResults: int = ..., nameContains: str = ...
     ) -> GetBotsResponseTypeDef:
         """
-        Returns bot information as follows * If you provide the `nameContains` field,
+        Returns bot information as follows: * If you provide the `nameContains` field,
         the response includes information for the `$LATEST` version of all bots whose
         name contains the specified string.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_bots)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_bots)
         """
     async def get_builtin_intent(self, *, signature: str) -> GetBuiltinIntentResponseTypeDef:
@@ -395,16 +395,17 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_intent_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_intent_versions)
         """
     async def get_intents(
         self, *, nextToken: str = ..., maxResults: int = ..., nameContains: str = ...
     ) -> GetIntentsResponseTypeDef:
         """
-        Returns intent information as follows * If you specify the `nameContains` field,
-        returns the `$LATEST` version of all intents that contain the specified string.
+        Returns intent information as follows: * If you specify the `nameContains`
+        field, returns the `$LATEST` version of all intents that contain the specified
+        string.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_intents)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_intents)
         """
     async def get_migration(self, *, migrationId: str) -> GetMigrationResponseTypeDef:
         """
         Provides details about an ongoing or complete migration from an Amazon Lex V1
@@ -445,15 +446,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_slot_type_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_slot_type_versions)
         """
     async def get_slot_types(
         self, *, nextToken: str = ..., maxResults: int = ..., nameContains: str = ...
     ) -> GetSlotTypesResponseTypeDef:
         """
-        Returns slot type information as follows * If you specify the `nameContains`
+        Returns slot type information as follows: * If you specify the `nameContains`
         field, returns the `$LATEST` version of all slot types that contain the
         specified string.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Client.get_slot_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/client/#get_slot_types)
         """
     async def get_utterances_view(
```

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/literals.py` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -167,14 +167,15 @@
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
@@ -253,14 +254,15 @@
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
@@ -271,14 +273,15 @@
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
@@ -314,14 +317,15 @@
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
@@ -340,16 +344,19 @@
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
@@ -433,15 +440,17 @@
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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/literals.pyi` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -165,14 +165,15 @@
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
@@ -251,14 +252,15 @@
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
@@ -269,14 +271,15 @@
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
@@ -312,14 +315,15 @@
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
@@ -338,16 +342,19 @@
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
@@ -431,15 +438,17 @@
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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/paginator.py` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         get_builtin_slot_types_paginator: GetBuiltinSlotTypesPaginator = client.get_paginator("get_builtin_slot_types")
         get_intent_versions_paginator: GetIntentVersionsPaginator = client.get_paginator("get_intent_versions")
         get_intents_paginator: GetIntentsPaginator = client.get_paginator("get_intents")
         get_slot_type_versions_paginator: GetSlotTypeVersionsPaginator = client.get_paginator("get_slot_type_versions")
         get_slot_types_paginator: GetSlotTypesPaginator = client.get_paginator("get_slot_types")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import LocaleType
 from .type_defs import (
     GetBotAliasesResponseTypeDef,
@@ -55,20 +54,14 @@
     GetIntentsResponseTypeDef,
     GetIntentVersionsResponseTypeDef,
     GetSlotTypesResponseTypeDef,
     GetSlotTypeVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetBotAliasesPaginator",
     "GetBotChannelAssociationsPaginator",
     "GetBotVersionsPaginator",
     "GetBotsPaginator",
     "GetBuiltinIntentsPaginator",
     "GetBuiltinSlotTypesPaginator",
@@ -96,15 +89,15 @@
     """
 
     def paginate(
         self,
         *,
         botName: str,
         nameContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotaliasespaginator)
         """
 
 
@@ -116,45 +109,45 @@
 
     def paginate(
         self,
         *,
         botName: str,
         botAlias: str,
         nameContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotChannelAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotChannelAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotchannelassociationspaginator)
         """
 
 
 class GetBotVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotversionspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotversionspaginator)
         """
 
 
 class GetBotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotspaginator)
     """
 
     def paginate(
-        self, *, nameContains: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, nameContains: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotspaginator)
         """
 
 
@@ -165,15 +158,15 @@
     """
 
     def paginate(
         self,
         *,
         locale: LocaleType = ...,
         signatureContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBuiltinIntentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBuiltinIntents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbuiltinintentspaginator)
         """
 
 
@@ -184,73 +177,73 @@
     """
 
     def paginate(
         self,
         *,
         locale: LocaleType = ...,
         signatureContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBuiltinSlotTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBuiltinSlotTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbuiltinslottypespaginator)
         """
 
 
 class GetIntentVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntentVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentversionspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntentVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentversionspaginator)
         """
 
 
 class GetIntentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentspaginator)
     """
 
     def paginate(
-        self, *, nameContains: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, nameContains: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentspaginator)
         """
 
 
 class GetSlotTypeVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypeVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypeversionspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSlotTypeVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypeVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypeversionspaginator)
         """
 
 
 class GetSlotTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypespaginator)
     """
 
     def paginate(
-        self, *, nameContains: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, nameContains: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSlotTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypespaginator)
         """
```

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/paginator.pyi` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         get_builtin_slot_types_paginator: GetBuiltinSlotTypesPaginator = client.get_paginator("get_builtin_slot_types")
         get_intent_versions_paginator: GetIntentVersionsPaginator = client.get_paginator("get_intent_versions")
         get_intents_paginator: GetIntentsPaginator = client.get_paginator("get_intents")
         get_slot_type_versions_paginator: GetSlotTypeVersionsPaginator = client.get_paginator("get_slot_type_versions")
         get_slot_types_paginator: GetSlotTypesPaginator = client.get_paginator("get_slot_types")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import LocaleType
 from .type_defs import (
     GetBotAliasesResponseTypeDef,
@@ -55,19 +54,14 @@
     GetIntentsResponseTypeDef,
     GetIntentVersionsResponseTypeDef,
     GetSlotTypesResponseTypeDef,
     GetSlotTypeVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetBotAliasesPaginator",
     "GetBotChannelAssociationsPaginator",
     "GetBotVersionsPaginator",
     "GetBotsPaginator",
     "GetBuiltinIntentsPaginator",
     "GetBuiltinSlotTypesPaginator",
@@ -92,15 +86,15 @@
     """
 
     def paginate(
         self,
         *,
         botName: str,
         nameContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotaliasespaginator)
         """
 
 class GetBotChannelAssociationsPaginator(AioPaginator):
@@ -111,43 +105,43 @@
 
     def paginate(
         self,
         *,
         botName: str,
         botAlias: str,
         nameContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotChannelAssociationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotChannelAssociations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotchannelassociationspaginator)
         """
 
 class GetBotVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotversionspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBotVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotversionspaginator)
         """
 
 class GetBotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotspaginator)
     """
 
     def paginate(
-        self, *, nameContains: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, nameContains: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBotsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbotspaginator)
         """
 
 class GetBuiltinIntentsPaginator(AioPaginator):
@@ -157,15 +151,15 @@
     """
 
     def paginate(
         self,
         *,
         locale: LocaleType = ...,
         signatureContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBuiltinIntentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBuiltinIntents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbuiltinintentspaginator)
         """
 
 class GetBuiltinSlotTypesPaginator(AioPaginator):
@@ -175,69 +169,69 @@
     """
 
     def paginate(
         self,
         *,
         locale: LocaleType = ...,
         signatureContains: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBuiltinSlotTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetBuiltinSlotTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getbuiltinslottypespaginator)
         """
 
 class GetIntentVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntentVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentversionspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntentVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntentVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentversionspaginator)
         """
 
 class GetIntentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentspaginator)
     """
 
     def paginate(
-        self, *, nameContains: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, nameContains: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetIntentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetIntents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getintentspaginator)
         """
 
 class GetSlotTypeVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypeVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypeversionspaginator)
     """
 
     def paginate(
-        self, *, name: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSlotTypeVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypeVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypeversionspaginator)
         """
 
 class GetSlotTypesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypespaginator)
     """
 
     def paginate(
-        self, *, nameContains: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, nameContains: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSlotTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService.Paginator.GetSlotTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/paginators/#getslottypespaginator)
         """
```

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/type_defs.py` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -44,27 +44,25 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "BotChannelAssociationTypeDef",
     "BotMetadataTypeDef",
     "BuiltinIntentMetadataTypeDef",
     "BuiltinIntentSlotTypeDef",
     "BuiltinSlotTypeMetadataTypeDef",
     "CodeHookTypeDef",
     "LogSettingsRequestTypeDef",
     "LogSettingsResponseTypeDef",
     "CreateBotVersionRequestRequestTypeDef",
     "IntentTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateIntentVersionRequestRequestTypeDef",
     "InputContextTypeDef",
     "KendraConfigurationTypeDef",
     "OutputContextTypeDef",
     "CreateSlotTypeVersionRequestRequestTypeDef",
     "EnumerationValueTypeDef",
     "DeleteBotAliasRequestRequestTypeDef",
@@ -72,72 +70,73 @@
     "DeleteBotRequestRequestTypeDef",
     "DeleteBotVersionRequestRequestTypeDef",
     "DeleteIntentRequestRequestTypeDef",
     "DeleteIntentVersionRequestRequestTypeDef",
     "DeleteSlotTypeRequestRequestTypeDef",
     "DeleteSlotTypeVersionRequestRequestTypeDef",
     "DeleteUtterancesRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetBotAliasRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetBotAliasesRequestGetBotAliasesPaginateTypeDef",
     "GetBotAliasesRequestRequestTypeDef",
     "GetBotChannelAssociationRequestRequestTypeDef",
+    "GetBotChannelAssociationResponseTypeDef",
+    "GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
     "GetBotChannelAssociationsRequestRequestTypeDef",
     "GetBotRequestRequestTypeDef",
+    "GetBotVersionsRequestGetBotVersionsPaginateTypeDef",
     "GetBotVersionsRequestRequestTypeDef",
+    "GetBotsRequestGetBotsPaginateTypeDef",
     "GetBotsRequestRequestTypeDef",
     "GetBuiltinIntentRequestRequestTypeDef",
+    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
     "GetBuiltinIntentsRequestRequestTypeDef",
+    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
     "GetBuiltinSlotTypesRequestRequestTypeDef",
     "GetExportRequestRequestTypeDef",
+    "GetExportResponseTypeDef",
     "GetImportRequestRequestTypeDef",
+    "GetImportResponseTypeDef",
     "GetIntentRequestRequestTypeDef",
+    "GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
     "GetIntentVersionsRequestRequestTypeDef",
     "IntentMetadataTypeDef",
+    "GetIntentsRequestGetIntentsPaginateTypeDef",
     "GetIntentsRequestRequestTypeDef",
     "GetMigrationRequestRequestTypeDef",
     "MigrationAlertTypeDef",
     "GetMigrationsRequestRequestTypeDef",
     "MigrationSummaryTypeDef",
     "GetSlotTypeRequestRequestTypeDef",
+    "GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
     "GetSlotTypeVersionsRequestRequestTypeDef",
     "SlotTypeMetadataTypeDef",
+    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
     "GetSlotTypesRequestRequestTypeDef",
     "GetUtterancesViewRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "MessageTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SlotDefaultValueTypeDef",
     "SlotTypeRegexConfigurationTypeDef",
     "StartMigrationRequestRequestTypeDef",
+    "StartMigrationResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UtteranceDataTypeDef",
-    "FulfillmentActivityTypeDef",
-    "ConversationLogsRequestTypeDef",
-    "ConversationLogsResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetBotChannelAssociationResponseTypeDef",
     "GetBotChannelAssociationsResponseTypeDef",
     "GetBotVersionsResponseTypeDef",
     "GetBotsResponseTypeDef",
-    "GetBuiltinIntentResponseTypeDef",
     "GetBuiltinIntentsResponseTypeDef",
+    "GetBuiltinIntentResponseTypeDef",
     "GetBuiltinSlotTypesResponseTypeDef",
-    "GetExportResponseTypeDef",
-    "GetImportResponseTypeDef",
-    "StartMigrationResponseTypeDef",
-    "GetBotAliasesRequestGetBotAliasesPaginateTypeDef",
-    "GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
-    "GetBotVersionsRequestGetBotVersionsPaginateTypeDef",
-    "GetBotsRequestGetBotsPaginateTypeDef",
-    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
-    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
-    "GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
-    "GetIntentsRequestGetIntentsPaginateTypeDef",
-    "GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
-    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
+    "FulfillmentActivityTypeDef",
+    "ConversationLogsRequestTypeDef",
+    "ConversationLogsResponseTypeDef",
     "GetIntentVersionsResponseTypeDef",
     "GetIntentsResponseTypeDef",
     "GetMigrationResponseTypeDef",
     "GetMigrationsResponseTypeDef",
     "GetSlotTypeVersionsResponseTypeDef",
     "GetSlotTypesResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -246,21 +245,19 @@
     "_OptionalLogSettingsRequestTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
-
 class LogSettingsRequestTypeDef(
     _RequiredLogSettingsRequestTypeDef, _OptionalLogSettingsRequestTypeDef
 ):
     pass
 
-
 LogSettingsResponseTypeDef = TypedDict(
     "LogSettingsResponseTypeDef",
     {
         "logType": LogTypeType,
         "destination": DestinationType,
         "kmsKeyArn": str,
         "resourceArn": str,
@@ -279,62 +276,47 @@
     "_OptionalCreateBotVersionRequestRequestTypeDef",
     {
         "checksum": str,
     },
     total=False,
 )
 
-
 class CreateBotVersionRequestRequestTypeDef(
     _RequiredCreateBotVersionRequestRequestTypeDef, _OptionalCreateBotVersionRequestRequestTypeDef
 ):
     pass
 
-
 IntentTypeDef = TypedDict(
     "IntentTypeDef",
     {
         "intentName": str,
         "intentVersion": str,
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
 _RequiredCreateIntentVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIntentVersionRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateIntentVersionRequestRequestTypeDef = TypedDict(
     "_OptionalCreateIntentVersionRequestRequestTypeDef",
     {
         "checksum": str,
     },
     total=False,
 )
 
-
 class CreateIntentVersionRequestRequestTypeDef(
     _RequiredCreateIntentVersionRequestRequestTypeDef,
     _OptionalCreateIntentVersionRequestRequestTypeDef,
 ):
     pass
 
-
 InputContextTypeDef = TypedDict(
     "InputContextTypeDef",
     {
         "name": str,
     },
 )
 
@@ -349,21 +331,19 @@
     "_OptionalKendraConfigurationTypeDef",
     {
         "queryFilterString": str,
     },
     total=False,
 )
 
-
 class KendraConfigurationTypeDef(
     _RequiredKendraConfigurationTypeDef, _OptionalKendraConfigurationTypeDef
 ):
     pass
 
-
 OutputContextTypeDef = TypedDict(
     "OutputContextTypeDef",
     {
         "name": str,
         "timeToLiveInSeconds": int,
         "turnsToLive": int,
     },
@@ -379,41 +359,37 @@
     "_OptionalCreateSlotTypeVersionRequestRequestTypeDef",
     {
         "checksum": str,
     },
     total=False,
 )
 
-
 class CreateSlotTypeVersionRequestRequestTypeDef(
     _RequiredCreateSlotTypeVersionRequestRequestTypeDef,
     _OptionalCreateSlotTypeVersionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredEnumerationValueTypeDef = TypedDict(
     "_RequiredEnumerationValueTypeDef",
     {
         "value": str,
     },
 )
 _OptionalEnumerationValueTypeDef = TypedDict(
     "_OptionalEnumerationValueTypeDef",
     {
         "synonyms": List[str],
     },
     total=False,
 )
 
-
 class EnumerationValueTypeDef(_RequiredEnumerationValueTypeDef, _OptionalEnumerationValueTypeDef):
     pass
 
-
 DeleteBotAliasRequestRequestTypeDef = TypedDict(
     "DeleteBotAliasRequestRequestTypeDef",
     {
         "name": str,
         "botName": str,
     },
 )
@@ -476,32 +452,50 @@
     "DeleteUtterancesRequestRequestTypeDef",
     {
         "botName": str,
         "userId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBotAliasRequestRequestTypeDef = TypedDict(
     "GetBotAliasRequestRequestTypeDef",
     {
         "name": str,
         "botName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
+    "_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "botName": str,
+    },
+)
+_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
+    "_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetBotAliasesRequestGetBotAliasesPaginateTypeDef(
+    _RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
+    _OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetBotAliasesRequestRequestTypeDef = TypedDict(
     "_RequiredGetBotAliasesRequestRequestTypeDef",
     {
         "botName": str,
     },
 )
 _OptionalGetBotAliasesRequestRequestTypeDef = TypedDict(
@@ -510,30 +504,66 @@
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
     total=False,
 )
 
-
 class GetBotAliasesRequestRequestTypeDef(
     _RequiredGetBotAliasesRequestRequestTypeDef, _OptionalGetBotAliasesRequestRequestTypeDef
 ):
     pass
 
-
 GetBotChannelAssociationRequestRequestTypeDef = TypedDict(
     "GetBotChannelAssociationRequestRequestTypeDef",
     {
         "name": str,
         "botName": str,
         "botAlias": str,
     },
 )
 
+GetBotChannelAssociationResponseTypeDef = TypedDict(
+    "GetBotChannelAssociationResponseTypeDef",
+    {
+        "name": str,
+        "description": str,
+        "botAlias": str,
+        "botName": str,
+        "createdDate": datetime,
+        "type": ChannelTypeType,
+        "botConfiguration": Dict[str, str],
+        "status": ChannelStatusType,
+        "failureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
+    {
+        "botName": str,
+        "botAlias": str,
+    },
+)
+_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef(
+    _RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
+    _OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetBotChannelAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetBotChannelAssociationsRequestRequestTypeDef",
     {
         "botName": str,
         "botAlias": str,
     },
 )
@@ -543,30 +573,48 @@
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
     total=False,
 )
 
-
 class GetBotChannelAssociationsRequestRequestTypeDef(
     _RequiredGetBotChannelAssociationsRequestRequestTypeDef,
     _OptionalGetBotChannelAssociationsRequestRequestTypeDef,
 ):
     pass
 
-
 GetBotRequestRequestTypeDef = TypedDict(
     "GetBotRequestRequestTypeDef",
     {
         "name": str,
         "versionOrAlias": str,
     },
 )
 
+_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetBotVersionsRequestGetBotVersionsPaginateTypeDef(
+    _RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
+    _OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetBotVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetBotVersionsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalGetBotVersionsRequestRequestTypeDef = TypedDict(
@@ -574,20 +622,27 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class GetBotVersionsRequestRequestTypeDef(
     _RequiredGetBotVersionsRequestRequestTypeDef, _OptionalGetBotVersionsRequestRequestTypeDef
 ):
     pass
 
+GetBotsRequestGetBotsPaginateTypeDef = TypedDict(
+    "GetBotsRequestGetBotsPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 GetBotsRequestRequestTypeDef = TypedDict(
     "GetBotsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
@@ -598,25 +653,45 @@
 GetBuiltinIntentRequestRequestTypeDef = TypedDict(
     "GetBuiltinIntentRequestRequestTypeDef",
     {
         "signature": str,
     },
 )
 
+GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef = TypedDict(
+    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
+    {
+        "locale": LocaleType,
+        "signatureContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBuiltinIntentsRequestRequestTypeDef = TypedDict(
     "GetBuiltinIntentsRequestRequestTypeDef",
     {
         "locale": LocaleType,
         "signatureContains": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef = TypedDict(
+    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
+    {
+        "locale": LocaleType,
+        "signatureContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBuiltinSlotTypesRequestRequestTypeDef = TypedDict(
     "GetBuiltinSlotTypesRequestRequestTypeDef",
     {
         "locale": LocaleType,
         "signatureContains": str,
         "nextToken": str,
         "maxResults": int,
@@ -630,29 +705,77 @@
         "name": str,
         "version": str,
         "resourceType": ResourceTypeType,
         "exportType": ExportTypeType,
     },
 )
 
+GetExportResponseTypeDef = TypedDict(
+    "GetExportResponseTypeDef",
+    {
+        "name": str,
+        "version": str,
+        "resourceType": ResourceTypeType,
+        "exportType": ExportTypeType,
+        "exportStatus": ExportStatusType,
+        "failureReason": str,
+        "url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetImportRequestRequestTypeDef = TypedDict(
     "GetImportRequestRequestTypeDef",
     {
         "importId": str,
     },
 )
 
+GetImportResponseTypeDef = TypedDict(
+    "GetImportResponseTypeDef",
+    {
+        "name": str,
+        "resourceType": ResourceTypeType,
+        "mergeStrategy": MergeStrategyType,
+        "importId": str,
+        "importStatus": ImportStatusType,
+        "failureReason": List[str],
+        "createdDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIntentRequestRequestTypeDef = TypedDict(
     "GetIntentRequestRequestTypeDef",
     {
         "name": str,
         "version": str,
     },
 )
 
+_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef(
+    _RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
+    _OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetIntentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetIntentVersionsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalGetIntentVersionsRequestRequestTypeDef = TypedDict(
@@ -660,33 +783,40 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class GetIntentVersionsRequestRequestTypeDef(
     _RequiredGetIntentVersionsRequestRequestTypeDef, _OptionalGetIntentVersionsRequestRequestTypeDef
 ):
     pass
 
-
 IntentMetadataTypeDef = TypedDict(
     "IntentMetadataTypeDef",
     {
         "name": str,
         "description": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
     },
     total=False,
 )
 
+GetIntentsRequestGetIntentsPaginateTypeDef = TypedDict(
+    "GetIntentsRequestGetIntentsPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetIntentsRequestRequestTypeDef = TypedDict(
     "GetIntentsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
@@ -744,14 +874,34 @@
     "GetSlotTypeRequestRequestTypeDef",
     {
         "name": str,
         "version": str,
     },
 )
 
+_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef(
+    _RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
+    _OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetSlotTypeVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSlotTypeVersionsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalGetSlotTypeVersionsRequestRequestTypeDef = TypedDict(
@@ -759,34 +909,41 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class GetSlotTypeVersionsRequestRequestTypeDef(
     _RequiredGetSlotTypeVersionsRequestRequestTypeDef,
     _OptionalGetSlotTypeVersionsRequestRequestTypeDef,
 ):
     pass
 
-
 SlotTypeMetadataTypeDef = TypedDict(
     "SlotTypeMetadataTypeDef",
     {
         "name": str,
         "description": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
     },
     total=False,
 )
 
+GetSlotTypesRequestGetSlotTypesPaginateTypeDef = TypedDict(
+    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetSlotTypesRequestRequestTypeDef = TypedDict(
     "GetSlotTypesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
@@ -828,18 +985,37 @@
     "_OptionalMessageTypeDef",
     {
         "groupNumber": int,
     },
     total=False,
 )
 
-
 class MessageTypeDef(_RequiredMessageTypeDef, _OptionalMessageTypeDef):
     pass
 
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
 
 SlotDefaultValueTypeDef = TypedDict(
     "SlotDefaultValueTypeDef",
     {
         "defaultValue": str,
     },
 )
@@ -858,14 +1034,29 @@
         "v1BotVersion": str,
         "v2BotName": str,
         "v2BotRole": str,
         "migrationStrategy": MigrationStrategyType,
     },
 )
 
+StartMigrationResponseTypeDef = TypedDict(
+    "StartMigrationResponseTypeDef",
+    {
+        "v1BotName": str,
+        "v1BotVersion": str,
+        "v1BotLocale": LocaleType,
+        "v2BotId": str,
+        "v2BotRole": str,
+        "migrationId": str,
+        "migrationStrategy": MigrationStrategyType,
+        "migrationTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -878,348 +1069,120 @@
         "distinctUsers": int,
         "firstUtteredDate": datetime,
         "lastUtteredDate": datetime,
     },
     total=False,
 )
 
-_RequiredFulfillmentActivityTypeDef = TypedDict(
-    "_RequiredFulfillmentActivityTypeDef",
-    {
-        "type": FulfillmentActivityTypeType,
-    },
-)
-_OptionalFulfillmentActivityTypeDef = TypedDict(
-    "_OptionalFulfillmentActivityTypeDef",
-    {
-        "codeHook": CodeHookTypeDef,
-    },
-    total=False,
-)
-
-
-class FulfillmentActivityTypeDef(
-    _RequiredFulfillmentActivityTypeDef, _OptionalFulfillmentActivityTypeDef
-):
-    pass
-
-
-ConversationLogsRequestTypeDef = TypedDict(
-    "ConversationLogsRequestTypeDef",
-    {
-        "logSettings": Sequence[LogSettingsRequestTypeDef],
-        "iamRoleArn": str,
-    },
-)
-
-ConversationLogsResponseTypeDef = TypedDict(
-    "ConversationLogsResponseTypeDef",
-    {
-        "logSettings": List[LogSettingsResponseTypeDef],
-        "iamRoleArn": str,
-    },
-    total=False,
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBotChannelAssociationResponseTypeDef = TypedDict(
-    "GetBotChannelAssociationResponseTypeDef",
-    {
-        "name": str,
-        "description": str,
-        "botAlias": str,
-        "botName": str,
-        "createdDate": datetime,
-        "type": ChannelTypeType,
-        "botConfiguration": Dict[str, str],
-        "status": ChannelStatusType,
-        "failureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetBotChannelAssociationsResponseTypeDef = TypedDict(
     "GetBotChannelAssociationsResponseTypeDef",
     {
         "botChannelAssociations": List[BotChannelAssociationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotVersionsResponseTypeDef = TypedDict(
     "GetBotVersionsResponseTypeDef",
     {
         "bots": List[BotMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotsResponseTypeDef = TypedDict(
     "GetBotsResponseTypeDef",
     {
         "bots": List[BotMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetBuiltinIntentsResponseTypeDef = TypedDict(
+    "GetBuiltinIntentsResponseTypeDef",
+    {
+        "intents": List[BuiltinIntentMetadataTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBuiltinIntentResponseTypeDef = TypedDict(
     "GetBuiltinIntentResponseTypeDef",
     {
         "signature": str,
         "supportedLocales": List[LocaleType],
         "slots": List[BuiltinIntentSlotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBuiltinIntentsResponseTypeDef = TypedDict(
-    "GetBuiltinIntentsResponseTypeDef",
-    {
-        "intents": List[BuiltinIntentMetadataTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBuiltinSlotTypesResponseTypeDef = TypedDict(
     "GetBuiltinSlotTypesResponseTypeDef",
     {
         "slotTypes": List[BuiltinSlotTypeMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetExportResponseTypeDef = TypedDict(
-    "GetExportResponseTypeDef",
-    {
-        "name": str,
-        "version": str,
-        "resourceType": ResourceTypeType,
-        "exportType": ExportTypeType,
-        "exportStatus": ExportStatusType,
-        "failureReason": str,
-        "url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetImportResponseTypeDef = TypedDict(
-    "GetImportResponseTypeDef",
-    {
-        "name": str,
-        "resourceType": ResourceTypeType,
-        "mergeStrategy": MergeStrategyType,
-        "importId": str,
-        "importStatus": ImportStatusType,
-        "failureReason": List[str],
-        "createdDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMigrationResponseTypeDef = TypedDict(
-    "StartMigrationResponseTypeDef",
-    {
-        "v1BotName": str,
-        "v1BotVersion": str,
-        "v1BotLocale": LocaleType,
-        "v2BotId": str,
-        "v2BotRole": str,
-        "migrationId": str,
-        "migrationStrategy": MigrationStrategyType,
-        "migrationTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
-    "_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
-    {
-        "botName": str,
-    },
-)
-_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
-    "_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetBotAliasesRequestGetBotAliasesPaginateTypeDef(
-    _RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
-    _OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
-    {
-        "botName": str,
-        "botAlias": str,
-    },
-)
-_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef(
-    _RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
-    _OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetBotVersionsRequestGetBotVersionsPaginateTypeDef(
-    _RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
-    _OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
-):
-    pass
-
-
-GetBotsRequestGetBotsPaginateTypeDef = TypedDict(
-    "GetBotsRequestGetBotsPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef = TypedDict(
-    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
-    {
-        "locale": LocaleType,
-        "signatureContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
-GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef = TypedDict(
-    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
-    {
-        "locale": LocaleType,
-        "signatureContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
+_RequiredFulfillmentActivityTypeDef = TypedDict(
+    "_RequiredFulfillmentActivityTypeDef",
     {
-        "name": str,
+        "type": FulfillmentActivityTypeType,
     },
 )
-_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
+_OptionalFulfillmentActivityTypeDef = TypedDict(
+    "_OptionalFulfillmentActivityTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "codeHook": CodeHookTypeDef,
     },
     total=False,
 )
 
-
-class GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef(
-    _RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
-    _OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
+class FulfillmentActivityTypeDef(
+    _RequiredFulfillmentActivityTypeDef, _OptionalFulfillmentActivityTypeDef
 ):
     pass
 
-
-GetIntentsRequestGetIntentsPaginateTypeDef = TypedDict(
-    "GetIntentsRequestGetIntentsPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
+ConversationLogsRequestTypeDef = TypedDict(
+    "ConversationLogsRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "logSettings": Sequence[LogSettingsRequestTypeDef],
+        "iamRoleArn": str,
     },
-    total=False,
 )
 
-
-class GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef(
-    _RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
-    _OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
-):
-    pass
-
-
-GetSlotTypesRequestGetSlotTypesPaginateTypeDef = TypedDict(
-    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
+ConversationLogsResponseTypeDef = TypedDict(
+    "ConversationLogsResponseTypeDef",
     {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "logSettings": List[LogSettingsResponseTypeDef],
+        "iamRoleArn": str,
     },
     total=False,
 )
 
 GetIntentVersionsResponseTypeDef = TypedDict(
     "GetIntentVersionsResponseTypeDef",
     {
         "intents": List[IntentMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntentsResponseTypeDef = TypedDict(
     "GetIntentsResponseTypeDef",
     {
         "intents": List[IntentMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationResponseTypeDef = TypedDict(
     "GetMigrationResponseTypeDef",
     {
         "migrationId": str,
@@ -1228,50 +1191,50 @@
         "v1BotLocale": LocaleType,
         "v2BotId": str,
         "v2BotRole": str,
         "migrationStatus": MigrationStatusType,
         "migrationStrategy": MigrationStrategyType,
         "migrationTimestamp": datetime,
         "alerts": List[MigrationAlertTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationsResponseTypeDef = TypedDict(
     "GetMigrationsResponseTypeDef",
     {
         "migrationSummaries": List[MigrationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSlotTypeVersionsResponseTypeDef = TypedDict(
     "GetSlotTypeVersionsResponseTypeDef",
     {
         "slotTypes": List[SlotTypeMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSlotTypesResponseTypeDef = TypedDict(
     "GetSlotTypesResponseTypeDef",
     {
         "slotTypes": List[SlotTypeMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartImportRequestRequestTypeDef = TypedDict(
     "_RequiredStartImportRequestRequestTypeDef",
     {
         "payload": Union[str, bytes, IO[Any], StreamingBody],
@@ -1283,32 +1246,30 @@
     "_OptionalStartImportRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartImportRequestRequestTypeDef(
     _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
 ):
     pass
 
-
 StartImportResponseTypeDef = TypedDict(
     "StartImportResponseTypeDef",
     {
         "name": str,
         "resourceType": ResourceTypeType,
         "mergeStrategy": MergeStrategyType,
         "importId": str,
         "importStatus": ImportStatusType,
         "tags": List[TagTypeDef],
         "createdDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1327,38 +1288,34 @@
     "_OptionalPromptTypeDef",
     {
         "responseCard": str,
     },
     total=False,
 )
 
-
 class PromptTypeDef(_RequiredPromptTypeDef, _OptionalPromptTypeDef):
     pass
 
-
 _RequiredStatementTypeDef = TypedDict(
     "_RequiredStatementTypeDef",
     {
         "messages": List[MessageTypeDef],
     },
 )
 _OptionalStatementTypeDef = TypedDict(
     "_OptionalStatementTypeDef",
     {
         "responseCard": str,
     },
     total=False,
 )
 
-
 class StatementTypeDef(_RequiredStatementTypeDef, _OptionalStatementTypeDef):
     pass
 
-
 SlotDefaultValueSpecTypeDef = TypedDict(
     "SlotDefaultValueSpecTypeDef",
     {
         "defaultValueList": List[SlotDefaultValueTypeDef],
     },
 )
 
@@ -1394,21 +1351,19 @@
         "checksum": str,
         "conversationLogs": ConversationLogsRequestTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class PutBotAliasRequestRequestTypeDef(
     _RequiredPutBotAliasRequestRequestTypeDef, _OptionalPutBotAliasRequestRequestTypeDef
 ):
     pass
 
-
 BotAliasMetadataTypeDef = TypedDict(
     "BotAliasMetadataTypeDef",
     {
         "name": str,
         "description": str,
         "botVersion": str,
         "botName": str,
@@ -1427,15 +1382,15 @@
         "description": str,
         "botVersion": str,
         "botName": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "checksum": str,
         "conversationLogs": ConversationLogsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBotAliasResponseTypeDef = TypedDict(
     "PutBotAliasResponseTypeDef",
     {
         "name": str,
@@ -1443,15 +1398,15 @@
         "botVersion": str,
         "botName": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "checksum": str,
         "conversationLogs": ConversationLogsResponseTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBotVersionResponseTypeDef = TypedDict(
     "CreateBotVersionResponseTypeDef",
     {
         "name": str,
@@ -1467,15 +1422,15 @@
         "voiceId": str,
         "checksum": str,
         "version": str,
         "locale": LocaleType,
         "childDirected": bool,
         "enableModelImprovements": bool,
         "detectSentiment": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FollowUpPromptTypeDef = TypedDict(
     "FollowUpPromptTypeDef",
     {
         "prompt": PromptTypeDef,
@@ -1500,15 +1455,15 @@
         "idleSessionTTLInSeconds": int,
         "voiceId": str,
         "checksum": str,
         "version": str,
         "locale": LocaleType,
         "childDirected": bool,
         "detectSentiment": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBotRequestRequestTypeDef = TypedDict(
     "_RequiredPutBotRequestRequestTypeDef",
     {
         "name": str,
@@ -1532,21 +1487,19 @@
         "detectSentiment": bool,
         "createVersion": bool,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class PutBotRequestRequestTypeDef(
     _RequiredPutBotRequestRequestTypeDef, _OptionalPutBotRequestRequestTypeDef
 ):
     pass
 
-
 PutBotResponseTypeDef = TypedDict(
     "PutBotResponseTypeDef",
     {
         "name": str,
         "description": str,
         "intents": List[IntentTypeDef],
         "enableModelImprovements": bool,
@@ -1562,15 +1515,15 @@
         "checksum": str,
         "version": str,
         "locale": LocaleType,
         "childDirected": bool,
         "createVersion": bool,
         "detectSentiment": bool,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSlotTypeDef = TypedDict(
     "_RequiredSlotTypeDef",
     {
         "name": str,
@@ -1589,33 +1542,31 @@
         "responseCard": str,
         "obfuscationSetting": ObfuscationSettingType,
         "defaultValueSpec": SlotDefaultValueSpecTypeDef,
     },
     total=False,
 )
 
-
 class SlotTypeDef(_RequiredSlotTypeDef, _OptionalSlotTypeDef):
     pass
 
-
 CreateSlotTypeVersionResponseTypeDef = TypedDict(
     "CreateSlotTypeVersionResponseTypeDef",
     {
         "name": str,
         "description": str,
         "enumerationValues": List[EnumerationValueTypeDef],
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "valueSelectionStrategy": SlotValueSelectionStrategyType,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": List[SlotTypeConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSlotTypeResponseTypeDef = TypedDict(
     "GetSlotTypeResponseTypeDef",
     {
         "name": str,
@@ -1624,15 +1575,15 @@
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "valueSelectionStrategy": SlotValueSelectionStrategyType,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": List[SlotTypeConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutSlotTypeRequestRequestTypeDef = TypedDict(
     "_RequiredPutSlotTypeRequestRequestTypeDef",
     {
         "name": str,
@@ -1648,54 +1599,52 @@
         "createVersion": bool,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": Sequence[SlotTypeConfigurationTypeDef],
     },
     total=False,
 )
 
-
 class PutSlotTypeRequestRequestTypeDef(
     _RequiredPutSlotTypeRequestRequestTypeDef, _OptionalPutSlotTypeRequestRequestTypeDef
 ):
     pass
 
-
 PutSlotTypeResponseTypeDef = TypedDict(
     "PutSlotTypeResponseTypeDef",
     {
         "name": str,
         "description": str,
         "enumerationValues": List[EnumerationValueTypeDef],
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "valueSelectionStrategy": SlotValueSelectionStrategyType,
         "createVersion": bool,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": List[SlotTypeConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUtterancesViewResponseTypeDef = TypedDict(
     "GetUtterancesViewResponseTypeDef",
     {
         "botName": str,
         "utterances": List[UtteranceListTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotAliasesResponseTypeDef = TypedDict(
     "GetBotAliasesResponseTypeDef",
     {
         "BotAliases": List[BotAliasMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateIntentVersionResponseTypeDef = TypedDict(
     "CreateIntentVersionResponseTypeDef",
     {
         "name": str,
@@ -1712,15 +1661,15 @@
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": List[InputContextTypeDef],
         "outputContexts": List[OutputContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntentResponseTypeDef = TypedDict(
     "GetIntentResponseTypeDef",
     {
         "name": str,
@@ -1737,15 +1686,15 @@
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": List[InputContextTypeDef],
         "outputContexts": List[OutputContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutIntentRequestRequestTypeDef = TypedDict(
     "_RequiredPutIntentRequestRequestTypeDef",
     {
         "name": str,
@@ -1769,21 +1718,19 @@
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": Sequence[InputContextTypeDef],
         "outputContexts": Sequence[OutputContextTypeDef],
     },
     total=False,
 )
 
-
 class PutIntentRequestRequestTypeDef(
     _RequiredPutIntentRequestRequestTypeDef, _OptionalPutIntentRequestRequestTypeDef
 ):
     pass
 
-
 PutIntentResponseTypeDef = TypedDict(
     "PutIntentResponseTypeDef",
     {
         "name": str,
         "description": str,
         "slots": List[SlotTypeDef],
         "sampleUtterances": List[str],
@@ -1798,10 +1745,10 @@
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "createVersion": bool,
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": List[InputContextTypeDef],
         "outputContexts": List[OutputContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models/type_defs.pyi` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -44,26 +44,26 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "BotChannelAssociationTypeDef",
     "BotMetadataTypeDef",
     "BuiltinIntentMetadataTypeDef",
     "BuiltinIntentSlotTypeDef",
     "BuiltinSlotTypeMetadataTypeDef",
     "CodeHookTypeDef",
     "LogSettingsRequestTypeDef",
     "LogSettingsResponseTypeDef",
     "CreateBotVersionRequestRequestTypeDef",
     "IntentTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateIntentVersionRequestRequestTypeDef",
     "InputContextTypeDef",
     "KendraConfigurationTypeDef",
     "OutputContextTypeDef",
     "CreateSlotTypeVersionRequestRequestTypeDef",
     "EnumerationValueTypeDef",
     "DeleteBotAliasRequestRequestTypeDef",
@@ -71,72 +71,73 @@
     "DeleteBotRequestRequestTypeDef",
     "DeleteBotVersionRequestRequestTypeDef",
     "DeleteIntentRequestRequestTypeDef",
     "DeleteIntentVersionRequestRequestTypeDef",
     "DeleteSlotTypeRequestRequestTypeDef",
     "DeleteSlotTypeVersionRequestRequestTypeDef",
     "DeleteUtterancesRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetBotAliasRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetBotAliasesRequestGetBotAliasesPaginateTypeDef",
     "GetBotAliasesRequestRequestTypeDef",
     "GetBotChannelAssociationRequestRequestTypeDef",
+    "GetBotChannelAssociationResponseTypeDef",
+    "GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
     "GetBotChannelAssociationsRequestRequestTypeDef",
     "GetBotRequestRequestTypeDef",
+    "GetBotVersionsRequestGetBotVersionsPaginateTypeDef",
     "GetBotVersionsRequestRequestTypeDef",
+    "GetBotsRequestGetBotsPaginateTypeDef",
     "GetBotsRequestRequestTypeDef",
     "GetBuiltinIntentRequestRequestTypeDef",
+    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
     "GetBuiltinIntentsRequestRequestTypeDef",
+    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
     "GetBuiltinSlotTypesRequestRequestTypeDef",
     "GetExportRequestRequestTypeDef",
+    "GetExportResponseTypeDef",
     "GetImportRequestRequestTypeDef",
+    "GetImportResponseTypeDef",
     "GetIntentRequestRequestTypeDef",
+    "GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
     "GetIntentVersionsRequestRequestTypeDef",
     "IntentMetadataTypeDef",
+    "GetIntentsRequestGetIntentsPaginateTypeDef",
     "GetIntentsRequestRequestTypeDef",
     "GetMigrationRequestRequestTypeDef",
     "MigrationAlertTypeDef",
     "GetMigrationsRequestRequestTypeDef",
     "MigrationSummaryTypeDef",
     "GetSlotTypeRequestRequestTypeDef",
+    "GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
     "GetSlotTypeVersionsRequestRequestTypeDef",
     "SlotTypeMetadataTypeDef",
+    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
     "GetSlotTypesRequestRequestTypeDef",
     "GetUtterancesViewRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "MessageTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "SlotDefaultValueTypeDef",
     "SlotTypeRegexConfigurationTypeDef",
     "StartMigrationRequestRequestTypeDef",
+    "StartMigrationResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UtteranceDataTypeDef",
-    "FulfillmentActivityTypeDef",
-    "ConversationLogsRequestTypeDef",
-    "ConversationLogsResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetBotChannelAssociationResponseTypeDef",
     "GetBotChannelAssociationsResponseTypeDef",
     "GetBotVersionsResponseTypeDef",
     "GetBotsResponseTypeDef",
-    "GetBuiltinIntentResponseTypeDef",
     "GetBuiltinIntentsResponseTypeDef",
+    "GetBuiltinIntentResponseTypeDef",
     "GetBuiltinSlotTypesResponseTypeDef",
-    "GetExportResponseTypeDef",
-    "GetImportResponseTypeDef",
-    "StartMigrationResponseTypeDef",
-    "GetBotAliasesRequestGetBotAliasesPaginateTypeDef",
-    "GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
-    "GetBotVersionsRequestGetBotVersionsPaginateTypeDef",
-    "GetBotsRequestGetBotsPaginateTypeDef",
-    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
-    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
-    "GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
-    "GetIntentsRequestGetIntentsPaginateTypeDef",
-    "GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
-    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
+    "FulfillmentActivityTypeDef",
+    "ConversationLogsRequestTypeDef",
+    "ConversationLogsResponseTypeDef",
     "GetIntentVersionsResponseTypeDef",
     "GetIntentsResponseTypeDef",
     "GetMigrationResponseTypeDef",
     "GetMigrationsResponseTypeDef",
     "GetSlotTypeVersionsResponseTypeDef",
     "GetSlotTypesResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -245,19 +246,21 @@
     "_OptionalLogSettingsRequestTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
+
 class LogSettingsRequestTypeDef(
     _RequiredLogSettingsRequestTypeDef, _OptionalLogSettingsRequestTypeDef
 ):
     pass
 
+
 LogSettingsResponseTypeDef = TypedDict(
     "LogSettingsResponseTypeDef",
     {
         "logType": LogTypeType,
         "destination": DestinationType,
         "kmsKeyArn": str,
         "resourceArn": str,
@@ -276,58 +279,51 @@
     "_OptionalCreateBotVersionRequestRequestTypeDef",
     {
         "checksum": str,
     },
     total=False,
 )
 
+
 class CreateBotVersionRequestRequestTypeDef(
     _RequiredCreateBotVersionRequestRequestTypeDef, _OptionalCreateBotVersionRequestRequestTypeDef
 ):
     pass
 
+
 IntentTypeDef = TypedDict(
     "IntentTypeDef",
     {
         "intentName": str,
         "intentVersion": str,
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
 _RequiredCreateIntentVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIntentVersionRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateIntentVersionRequestRequestTypeDef = TypedDict(
     "_OptionalCreateIntentVersionRequestRequestTypeDef",
     {
         "checksum": str,
     },
     total=False,
 )
 
+
 class CreateIntentVersionRequestRequestTypeDef(
     _RequiredCreateIntentVersionRequestRequestTypeDef,
     _OptionalCreateIntentVersionRequestRequestTypeDef,
 ):
     pass
 
+
 InputContextTypeDef = TypedDict(
     "InputContextTypeDef",
     {
         "name": str,
     },
 )
 
@@ -342,19 +338,21 @@
     "_OptionalKendraConfigurationTypeDef",
     {
         "queryFilterString": str,
     },
     total=False,
 )
 
+
 class KendraConfigurationTypeDef(
     _RequiredKendraConfigurationTypeDef, _OptionalKendraConfigurationTypeDef
 ):
     pass
 
+
 OutputContextTypeDef = TypedDict(
     "OutputContextTypeDef",
     {
         "name": str,
         "timeToLiveInSeconds": int,
         "turnsToLive": int,
     },
@@ -370,37 +368,41 @@
     "_OptionalCreateSlotTypeVersionRequestRequestTypeDef",
     {
         "checksum": str,
     },
     total=False,
 )
 
+
 class CreateSlotTypeVersionRequestRequestTypeDef(
     _RequiredCreateSlotTypeVersionRequestRequestTypeDef,
     _OptionalCreateSlotTypeVersionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredEnumerationValueTypeDef = TypedDict(
     "_RequiredEnumerationValueTypeDef",
     {
         "value": str,
     },
 )
 _OptionalEnumerationValueTypeDef = TypedDict(
     "_OptionalEnumerationValueTypeDef",
     {
         "synonyms": List[str],
     },
     total=False,
 )
 
+
 class EnumerationValueTypeDef(_RequiredEnumerationValueTypeDef, _OptionalEnumerationValueTypeDef):
     pass
 
+
 DeleteBotAliasRequestRequestTypeDef = TypedDict(
     "DeleteBotAliasRequestRequestTypeDef",
     {
         "name": str,
         "botName": str,
     },
 )
@@ -463,32 +465,52 @@
     "DeleteUtterancesRequestRequestTypeDef",
     {
         "botName": str,
         "userId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBotAliasRequestRequestTypeDef = TypedDict(
     "GetBotAliasRequestRequestTypeDef",
     {
         "name": str,
         "botName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
+    "_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "botName": str,
+    },
+)
+_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
+    "_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetBotAliasesRequestGetBotAliasesPaginateTypeDef(
+    _RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
+    _OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetBotAliasesRequestRequestTypeDef = TypedDict(
     "_RequiredGetBotAliasesRequestRequestTypeDef",
     {
         "botName": str,
     },
 )
 _OptionalGetBotAliasesRequestRequestTypeDef = TypedDict(
@@ -497,28 +519,70 @@
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
     total=False,
 )
 
+
 class GetBotAliasesRequestRequestTypeDef(
     _RequiredGetBotAliasesRequestRequestTypeDef, _OptionalGetBotAliasesRequestRequestTypeDef
 ):
     pass
 
+
 GetBotChannelAssociationRequestRequestTypeDef = TypedDict(
     "GetBotChannelAssociationRequestRequestTypeDef",
     {
         "name": str,
         "botName": str,
         "botAlias": str,
     },
 )
 
+GetBotChannelAssociationResponseTypeDef = TypedDict(
+    "GetBotChannelAssociationResponseTypeDef",
+    {
+        "name": str,
+        "description": str,
+        "botAlias": str,
+        "botName": str,
+        "createdDate": datetime,
+        "type": ChannelTypeType,
+        "botConfiguration": Dict[str, str],
+        "status": ChannelStatusType,
+        "failureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
+    {
+        "botName": str,
+        "botAlias": str,
+    },
+)
+_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef(
+    _RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
+    _OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetBotChannelAssociationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetBotChannelAssociationsRequestRequestTypeDef",
     {
         "botName": str,
         "botAlias": str,
     },
 )
@@ -528,28 +592,52 @@
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
     total=False,
 )
 
+
 class GetBotChannelAssociationsRequestRequestTypeDef(
     _RequiredGetBotChannelAssociationsRequestRequestTypeDef,
     _OptionalGetBotChannelAssociationsRequestRequestTypeDef,
 ):
     pass
 
+
 GetBotRequestRequestTypeDef = TypedDict(
     "GetBotRequestRequestTypeDef",
     {
         "name": str,
         "versionOrAlias": str,
     },
 )
 
+_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetBotVersionsRequestGetBotVersionsPaginateTypeDef(
+    _RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
+    _OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetBotVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetBotVersionsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalGetBotVersionsRequestRequestTypeDef = TypedDict(
@@ -557,19 +645,30 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class GetBotVersionsRequestRequestTypeDef(
     _RequiredGetBotVersionsRequestRequestTypeDef, _OptionalGetBotVersionsRequestRequestTypeDef
 ):
     pass
 
+
+GetBotsRequestGetBotsPaginateTypeDef = TypedDict(
+    "GetBotsRequestGetBotsPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBotsRequestRequestTypeDef = TypedDict(
     "GetBotsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
@@ -579,25 +678,45 @@
 GetBuiltinIntentRequestRequestTypeDef = TypedDict(
     "GetBuiltinIntentRequestRequestTypeDef",
     {
         "signature": str,
     },
 )
 
+GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef = TypedDict(
+    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
+    {
+        "locale": LocaleType,
+        "signatureContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBuiltinIntentsRequestRequestTypeDef = TypedDict(
     "GetBuiltinIntentsRequestRequestTypeDef",
     {
         "locale": LocaleType,
         "signatureContains": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef = TypedDict(
+    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
+    {
+        "locale": LocaleType,
+        "signatureContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBuiltinSlotTypesRequestRequestTypeDef = TypedDict(
     "GetBuiltinSlotTypesRequestRequestTypeDef",
     {
         "locale": LocaleType,
         "signatureContains": str,
         "nextToken": str,
         "maxResults": int,
@@ -611,29 +730,79 @@
         "name": str,
         "version": str,
         "resourceType": ResourceTypeType,
         "exportType": ExportTypeType,
     },
 )
 
+GetExportResponseTypeDef = TypedDict(
+    "GetExportResponseTypeDef",
+    {
+        "name": str,
+        "version": str,
+        "resourceType": ResourceTypeType,
+        "exportType": ExportTypeType,
+        "exportStatus": ExportStatusType,
+        "failureReason": str,
+        "url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetImportRequestRequestTypeDef = TypedDict(
     "GetImportRequestRequestTypeDef",
     {
         "importId": str,
     },
 )
 
+GetImportResponseTypeDef = TypedDict(
+    "GetImportResponseTypeDef",
+    {
+        "name": str,
+        "resourceType": ResourceTypeType,
+        "mergeStrategy": MergeStrategyType,
+        "importId": str,
+        "importStatus": ImportStatusType,
+        "failureReason": List[str],
+        "createdDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIntentRequestRequestTypeDef = TypedDict(
     "GetIntentRequestRequestTypeDef",
     {
         "name": str,
         "version": str,
     },
 )
 
+_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef(
+    _RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
+    _OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetIntentVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetIntentVersionsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalGetIntentVersionsRequestRequestTypeDef = TypedDict(
@@ -641,31 +810,42 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class GetIntentVersionsRequestRequestTypeDef(
     _RequiredGetIntentVersionsRequestRequestTypeDef, _OptionalGetIntentVersionsRequestRequestTypeDef
 ):
     pass
 
+
 IntentMetadataTypeDef = TypedDict(
     "IntentMetadataTypeDef",
     {
         "name": str,
         "description": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
     },
     total=False,
 )
 
+GetIntentsRequestGetIntentsPaginateTypeDef = TypedDict(
+    "GetIntentsRequestGetIntentsPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetIntentsRequestRequestTypeDef = TypedDict(
     "GetIntentsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
@@ -723,14 +903,36 @@
     "GetSlotTypeRequestRequestTypeDef",
     {
         "name": str,
         "version": str,
     },
 )
 
+_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
+    {
+        "name": str,
+    },
+)
+_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef(
+    _RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
+    _OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetSlotTypeVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSlotTypeVersionsRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalGetSlotTypeVersionsRequestRequestTypeDef = TypedDict(
@@ -738,32 +940,43 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class GetSlotTypeVersionsRequestRequestTypeDef(
     _RequiredGetSlotTypeVersionsRequestRequestTypeDef,
     _OptionalGetSlotTypeVersionsRequestRequestTypeDef,
 ):
     pass
 
+
 SlotTypeMetadataTypeDef = TypedDict(
     "SlotTypeMetadataTypeDef",
     {
         "name": str,
         "description": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
     },
     total=False,
 )
 
+GetSlotTypesRequestGetSlotTypesPaginateTypeDef = TypedDict(
+    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
+    {
+        "nameContains": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetSlotTypesRequestRequestTypeDef = TypedDict(
     "GetSlotTypesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
         "nameContains": str,
     },
@@ -805,17 +1018,40 @@
     "_OptionalMessageTypeDef",
     {
         "groupNumber": int,
     },
     total=False,
 )
 
+
 class MessageTypeDef(_RequiredMessageTypeDef, _OptionalMessageTypeDef):
     pass
 
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
 SlotDefaultValueTypeDef = TypedDict(
     "SlotDefaultValueTypeDef",
     {
         "defaultValue": str,
     },
 )
 
@@ -833,14 +1069,29 @@
         "v1BotVersion": str,
         "v2BotName": str,
         "v2BotRole": str,
         "migrationStrategy": MigrationStrategyType,
     },
 )
 
+StartMigrationResponseTypeDef = TypedDict(
+    "StartMigrationResponseTypeDef",
+    {
+        "v1BotName": str,
+        "v1BotVersion": str,
+        "v1BotLocale": LocaleType,
+        "v2BotId": str,
+        "v2BotRole": str,
+        "migrationId": str,
+        "migrationStrategy": MigrationStrategyType,
+        "migrationTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -853,336 +1104,122 @@
         "distinctUsers": int,
         "firstUtteredDate": datetime,
         "lastUtteredDate": datetime,
     },
     total=False,
 )
 
-_RequiredFulfillmentActivityTypeDef = TypedDict(
-    "_RequiredFulfillmentActivityTypeDef",
-    {
-        "type": FulfillmentActivityTypeType,
-    },
-)
-_OptionalFulfillmentActivityTypeDef = TypedDict(
-    "_OptionalFulfillmentActivityTypeDef",
-    {
-        "codeHook": CodeHookTypeDef,
-    },
-    total=False,
-)
-
-class FulfillmentActivityTypeDef(
-    _RequiredFulfillmentActivityTypeDef, _OptionalFulfillmentActivityTypeDef
-):
-    pass
-
-ConversationLogsRequestTypeDef = TypedDict(
-    "ConversationLogsRequestTypeDef",
-    {
-        "logSettings": Sequence[LogSettingsRequestTypeDef],
-        "iamRoleArn": str,
-    },
-)
-
-ConversationLogsResponseTypeDef = TypedDict(
-    "ConversationLogsResponseTypeDef",
-    {
-        "logSettings": List[LogSettingsResponseTypeDef],
-        "iamRoleArn": str,
-    },
-    total=False,
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBotChannelAssociationResponseTypeDef = TypedDict(
-    "GetBotChannelAssociationResponseTypeDef",
-    {
-        "name": str,
-        "description": str,
-        "botAlias": str,
-        "botName": str,
-        "createdDate": datetime,
-        "type": ChannelTypeType,
-        "botConfiguration": Dict[str, str],
-        "status": ChannelStatusType,
-        "failureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetBotChannelAssociationsResponseTypeDef = TypedDict(
     "GetBotChannelAssociationsResponseTypeDef",
     {
         "botChannelAssociations": List[BotChannelAssociationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotVersionsResponseTypeDef = TypedDict(
     "GetBotVersionsResponseTypeDef",
     {
         "bots": List[BotMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotsResponseTypeDef = TypedDict(
     "GetBotsResponseTypeDef",
     {
         "bots": List[BotMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetBuiltinIntentsResponseTypeDef = TypedDict(
+    "GetBuiltinIntentsResponseTypeDef",
+    {
+        "intents": List[BuiltinIntentMetadataTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBuiltinIntentResponseTypeDef = TypedDict(
     "GetBuiltinIntentResponseTypeDef",
     {
         "signature": str,
         "supportedLocales": List[LocaleType],
         "slots": List[BuiltinIntentSlotTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBuiltinIntentsResponseTypeDef = TypedDict(
-    "GetBuiltinIntentsResponseTypeDef",
-    {
-        "intents": List[BuiltinIntentMetadataTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBuiltinSlotTypesResponseTypeDef = TypedDict(
     "GetBuiltinSlotTypesResponseTypeDef",
     {
         "slotTypes": List[BuiltinSlotTypeMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetExportResponseTypeDef = TypedDict(
-    "GetExportResponseTypeDef",
-    {
-        "name": str,
-        "version": str,
-        "resourceType": ResourceTypeType,
-        "exportType": ExportTypeType,
-        "exportStatus": ExportStatusType,
-        "failureReason": str,
-        "url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetImportResponseTypeDef = TypedDict(
-    "GetImportResponseTypeDef",
-    {
-        "name": str,
-        "resourceType": ResourceTypeType,
-        "mergeStrategy": MergeStrategyType,
-        "importId": str,
-        "importStatus": ImportStatusType,
-        "failureReason": List[str],
-        "createdDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMigrationResponseTypeDef = TypedDict(
-    "StartMigrationResponseTypeDef",
-    {
-        "v1BotName": str,
-        "v1BotVersion": str,
-        "v1BotLocale": LocaleType,
-        "v2BotId": str,
-        "v2BotRole": str,
-        "migrationId": str,
-        "migrationStrategy": MigrationStrategyType,
-        "migrationTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
-    "_RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
-    {
-        "botName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef = TypedDict(
-    "_OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetBotAliasesRequestGetBotAliasesPaginateTypeDef(
-    _RequiredGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
-    _OptionalGetBotAliasesRequestGetBotAliasesPaginateTypeDef,
-):
-    pass
-
-_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
-    "_RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
-    {
-        "botName": str,
-        "botAlias": str,
-    },
-)
-_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef = TypedDict(
-    "_OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef(
-    _RequiredGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
-    _OptionalGetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetBotVersionsRequestGetBotVersionsPaginateTypeDef(
-    _RequiredGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
-    _OptionalGetBotVersionsRequestGetBotVersionsPaginateTypeDef,
-):
-    pass
-
-GetBotsRequestGetBotsPaginateTypeDef = TypedDict(
-    "GetBotsRequestGetBotsPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef = TypedDict(
-    "GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef",
+_RequiredFulfillmentActivityTypeDef = TypedDict(
+    "_RequiredFulfillmentActivityTypeDef",
     {
-        "locale": LocaleType,
-        "signatureContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "type": FulfillmentActivityTypeType,
     },
-    total=False,
 )
-
-GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef = TypedDict(
-    "GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef",
+_OptionalFulfillmentActivityTypeDef = TypedDict(
+    "_OptionalFulfillmentActivityTypeDef",
     {
-        "locale": LocaleType,
-        "signatureContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "codeHook": CodeHookTypeDef,
     },
     total=False,
 )
 
-_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-class GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef(
-    _RequiredGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
-    _OptionalGetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
+class FulfillmentActivityTypeDef(
+    _RequiredFulfillmentActivityTypeDef, _OptionalFulfillmentActivityTypeDef
 ):
     pass
 
-GetIntentsRequestGetIntentsPaginateTypeDef = TypedDict(
-    "GetIntentsRequestGetIntentsPaginateTypeDef",
-    {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
-    {
-        "name": str,
-    },
-)
-_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef",
+ConversationLogsRequestTypeDef = TypedDict(
+    "ConversationLogsRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "logSettings": Sequence[LogSettingsRequestTypeDef],
+        "iamRoleArn": str,
     },
-    total=False,
 )
 
-class GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef(
-    _RequiredGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
-    _OptionalGetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
-):
-    pass
-
-GetSlotTypesRequestGetSlotTypesPaginateTypeDef = TypedDict(
-    "GetSlotTypesRequestGetSlotTypesPaginateTypeDef",
+ConversationLogsResponseTypeDef = TypedDict(
+    "ConversationLogsResponseTypeDef",
     {
-        "nameContains": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "logSettings": List[LogSettingsResponseTypeDef],
+        "iamRoleArn": str,
     },
     total=False,
 )
 
 GetIntentVersionsResponseTypeDef = TypedDict(
     "GetIntentVersionsResponseTypeDef",
     {
         "intents": List[IntentMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntentsResponseTypeDef = TypedDict(
     "GetIntentsResponseTypeDef",
     {
         "intents": List[IntentMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationResponseTypeDef = TypedDict(
     "GetMigrationResponseTypeDef",
     {
         "migrationId": str,
@@ -1191,50 +1228,50 @@
         "v1BotLocale": LocaleType,
         "v2BotId": str,
         "v2BotRole": str,
         "migrationStatus": MigrationStatusType,
         "migrationStrategy": MigrationStrategyType,
         "migrationTimestamp": datetime,
         "alerts": List[MigrationAlertTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMigrationsResponseTypeDef = TypedDict(
     "GetMigrationsResponseTypeDef",
     {
         "migrationSummaries": List[MigrationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSlotTypeVersionsResponseTypeDef = TypedDict(
     "GetSlotTypeVersionsResponseTypeDef",
     {
         "slotTypes": List[SlotTypeMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSlotTypesResponseTypeDef = TypedDict(
     "GetSlotTypesResponseTypeDef",
     {
         "slotTypes": List[SlotTypeMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartImportRequestRequestTypeDef = TypedDict(
     "_RequiredStartImportRequestRequestTypeDef",
     {
         "payload": Union[str, bytes, IO[Any], StreamingBody],
@@ -1246,30 +1283,32 @@
     "_OptionalStartImportRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartImportRequestRequestTypeDef(
     _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
 ):
     pass
 
+
 StartImportResponseTypeDef = TypedDict(
     "StartImportResponseTypeDef",
     {
         "name": str,
         "resourceType": ResourceTypeType,
         "mergeStrategy": MergeStrategyType,
         "importId": str,
         "importStatus": ImportStatusType,
         "tags": List[TagTypeDef],
         "createdDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1288,34 +1327,38 @@
     "_OptionalPromptTypeDef",
     {
         "responseCard": str,
     },
     total=False,
 )
 
+
 class PromptTypeDef(_RequiredPromptTypeDef, _OptionalPromptTypeDef):
     pass
 
+
 _RequiredStatementTypeDef = TypedDict(
     "_RequiredStatementTypeDef",
     {
         "messages": List[MessageTypeDef],
     },
 )
 _OptionalStatementTypeDef = TypedDict(
     "_OptionalStatementTypeDef",
     {
         "responseCard": str,
     },
     total=False,
 )
 
+
 class StatementTypeDef(_RequiredStatementTypeDef, _OptionalStatementTypeDef):
     pass
 
+
 SlotDefaultValueSpecTypeDef = TypedDict(
     "SlotDefaultValueSpecTypeDef",
     {
         "defaultValueList": List[SlotDefaultValueTypeDef],
     },
 )
 
@@ -1351,19 +1394,21 @@
         "checksum": str,
         "conversationLogs": ConversationLogsRequestTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class PutBotAliasRequestRequestTypeDef(
     _RequiredPutBotAliasRequestRequestTypeDef, _OptionalPutBotAliasRequestRequestTypeDef
 ):
     pass
 
+
 BotAliasMetadataTypeDef = TypedDict(
     "BotAliasMetadataTypeDef",
     {
         "name": str,
         "description": str,
         "botVersion": str,
         "botName": str,
@@ -1382,15 +1427,15 @@
         "description": str,
         "botVersion": str,
         "botName": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "checksum": str,
         "conversationLogs": ConversationLogsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutBotAliasResponseTypeDef = TypedDict(
     "PutBotAliasResponseTypeDef",
     {
         "name": str,
@@ -1398,15 +1443,15 @@
         "botVersion": str,
         "botName": str,
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "checksum": str,
         "conversationLogs": ConversationLogsResponseTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBotVersionResponseTypeDef = TypedDict(
     "CreateBotVersionResponseTypeDef",
     {
         "name": str,
@@ -1422,15 +1467,15 @@
         "voiceId": str,
         "checksum": str,
         "version": str,
         "locale": LocaleType,
         "childDirected": bool,
         "enableModelImprovements": bool,
         "detectSentiment": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FollowUpPromptTypeDef = TypedDict(
     "FollowUpPromptTypeDef",
     {
         "prompt": PromptTypeDef,
@@ -1455,15 +1500,15 @@
         "idleSessionTTLInSeconds": int,
         "voiceId": str,
         "checksum": str,
         "version": str,
         "locale": LocaleType,
         "childDirected": bool,
         "detectSentiment": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutBotRequestRequestTypeDef = TypedDict(
     "_RequiredPutBotRequestRequestTypeDef",
     {
         "name": str,
@@ -1487,19 +1532,21 @@
         "detectSentiment": bool,
         "createVersion": bool,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class PutBotRequestRequestTypeDef(
     _RequiredPutBotRequestRequestTypeDef, _OptionalPutBotRequestRequestTypeDef
 ):
     pass
 
+
 PutBotResponseTypeDef = TypedDict(
     "PutBotResponseTypeDef",
     {
         "name": str,
         "description": str,
         "intents": List[IntentTypeDef],
         "enableModelImprovements": bool,
@@ -1515,15 +1562,15 @@
         "checksum": str,
         "version": str,
         "locale": LocaleType,
         "childDirected": bool,
         "createVersion": bool,
         "detectSentiment": bool,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSlotTypeDef = TypedDict(
     "_RequiredSlotTypeDef",
     {
         "name": str,
@@ -1542,31 +1589,33 @@
         "responseCard": str,
         "obfuscationSetting": ObfuscationSettingType,
         "defaultValueSpec": SlotDefaultValueSpecTypeDef,
     },
     total=False,
 )
 
+
 class SlotTypeDef(_RequiredSlotTypeDef, _OptionalSlotTypeDef):
     pass
 
+
 CreateSlotTypeVersionResponseTypeDef = TypedDict(
     "CreateSlotTypeVersionResponseTypeDef",
     {
         "name": str,
         "description": str,
         "enumerationValues": List[EnumerationValueTypeDef],
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "valueSelectionStrategy": SlotValueSelectionStrategyType,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": List[SlotTypeConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSlotTypeResponseTypeDef = TypedDict(
     "GetSlotTypeResponseTypeDef",
     {
         "name": str,
@@ -1575,15 +1624,15 @@
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "valueSelectionStrategy": SlotValueSelectionStrategyType,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": List[SlotTypeConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutSlotTypeRequestRequestTypeDef = TypedDict(
     "_RequiredPutSlotTypeRequestRequestTypeDef",
     {
         "name": str,
@@ -1599,52 +1648,54 @@
         "createVersion": bool,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": Sequence[SlotTypeConfigurationTypeDef],
     },
     total=False,
 )
 
+
 class PutSlotTypeRequestRequestTypeDef(
     _RequiredPutSlotTypeRequestRequestTypeDef, _OptionalPutSlotTypeRequestRequestTypeDef
 ):
     pass
 
+
 PutSlotTypeResponseTypeDef = TypedDict(
     "PutSlotTypeResponseTypeDef",
     {
         "name": str,
         "description": str,
         "enumerationValues": List[EnumerationValueTypeDef],
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "valueSelectionStrategy": SlotValueSelectionStrategyType,
         "createVersion": bool,
         "parentSlotTypeSignature": str,
         "slotTypeConfigurations": List[SlotTypeConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUtterancesViewResponseTypeDef = TypedDict(
     "GetUtterancesViewResponseTypeDef",
     {
         "botName": str,
         "utterances": List[UtteranceListTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotAliasesResponseTypeDef = TypedDict(
     "GetBotAliasesResponseTypeDef",
     {
         "BotAliases": List[BotAliasMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateIntentVersionResponseTypeDef = TypedDict(
     "CreateIntentVersionResponseTypeDef",
     {
         "name": str,
@@ -1661,15 +1712,15 @@
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": List[InputContextTypeDef],
         "outputContexts": List[OutputContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIntentResponseTypeDef = TypedDict(
     "GetIntentResponseTypeDef",
     {
         "name": str,
@@ -1686,15 +1737,15 @@
         "lastUpdatedDate": datetime,
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": List[InputContextTypeDef],
         "outputContexts": List[OutputContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutIntentRequestRequestTypeDef = TypedDict(
     "_RequiredPutIntentRequestRequestTypeDef",
     {
         "name": str,
@@ -1718,19 +1769,21 @@
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": Sequence[InputContextTypeDef],
         "outputContexts": Sequence[OutputContextTypeDef],
     },
     total=False,
 )
 
+
 class PutIntentRequestRequestTypeDef(
     _RequiredPutIntentRequestRequestTypeDef, _OptionalPutIntentRequestRequestTypeDef
 ):
     pass
 
+
 PutIntentResponseTypeDef = TypedDict(
     "PutIntentResponseTypeDef",
     {
         "name": str,
         "description": str,
         "slots": List[SlotTypeDef],
         "sampleUtterances": List[str],
@@ -1745,10 +1798,10 @@
         "createdDate": datetime,
         "version": str,
         "checksum": str,
         "createVersion": bool,
         "kendraConfiguration": KendraConfigurationTypeDef,
         "inputContexts": List[InputContextTypeDef],
         "outputContexts": List[OutputContextTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/PKG-INFO` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lex-models
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.LexModelBuildingService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LexModelBuildingService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lex-models"></a>
 
 # types-aiobotocore-lex-models
 
 [![PyPI - types-aiobotocore-lex-models](https://img.shields.io/pypi/v/types-aiobotocore-lex-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-models)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lex-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lex-models)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lex-models?color=blue)](https://pypistats.org/packages/types-aiobotocore-lex-models)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexModelBuildingService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService)
+[aiobotocore.LexModelBuildingService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lex-models.html#LexModelBuildingService)
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
 [types-aiobotocore-lex-models docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lex_models/).
 
 See how it helps to find and fix potential bugs:
 
@@ -386,15 +386,14 @@
     BuiltinIntentSlotTypeDef,
     BuiltinSlotTypeMetadataTypeDef,
     CodeHookTypeDef,
     LogSettingsRequestTypeDef,
     LogSettingsResponseTypeDef,
     CreateBotVersionRequestRequestTypeDef,
     IntentTypeDef,
-    ResponseMetadataTypeDef,
     CreateIntentVersionRequestRequestTypeDef,
     InputContextTypeDef,
     KendraConfigurationTypeDef,
     OutputContextTypeDef,
     CreateSlotTypeVersionRequestRequestTypeDef,
     EnumerationValueTypeDef,
     DeleteBotAliasRequestRequestTypeDef,
@@ -402,72 +401,73 @@
     DeleteBotRequestRequestTypeDef,
     DeleteBotVersionRequestRequestTypeDef,
     DeleteIntentRequestRequestTypeDef,
     DeleteIntentVersionRequestRequestTypeDef,
     DeleteSlotTypeRequestRequestTypeDef,
     DeleteSlotTypeVersionRequestRequestTypeDef,
     DeleteUtterancesRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetBotAliasRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetBotAliasesRequestGetBotAliasesPaginateTypeDef,
     GetBotAliasesRequestRequestTypeDef,
     GetBotChannelAssociationRequestRequestTypeDef,
+    GetBotChannelAssociationResponseTypeDef,
+    GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
     GetBotChannelAssociationsRequestRequestTypeDef,
     GetBotRequestRequestTypeDef,
+    GetBotVersionsRequestGetBotVersionsPaginateTypeDef,
     GetBotVersionsRequestRequestTypeDef,
+    GetBotsRequestGetBotsPaginateTypeDef,
     GetBotsRequestRequestTypeDef,
     GetBuiltinIntentRequestRequestTypeDef,
+    GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef,
     GetBuiltinIntentsRequestRequestTypeDef,
+    GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef,
     GetBuiltinSlotTypesRequestRequestTypeDef,
     GetExportRequestRequestTypeDef,
+    GetExportResponseTypeDef,
     GetImportRequestRequestTypeDef,
+    GetImportResponseTypeDef,
     GetIntentRequestRequestTypeDef,
+    GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
     GetIntentVersionsRequestRequestTypeDef,
     IntentMetadataTypeDef,
+    GetIntentsRequestGetIntentsPaginateTypeDef,
     GetIntentsRequestRequestTypeDef,
     GetMigrationRequestRequestTypeDef,
     MigrationAlertTypeDef,
     GetMigrationsRequestRequestTypeDef,
     MigrationSummaryTypeDef,
     GetSlotTypeRequestRequestTypeDef,
+    GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
     GetSlotTypeVersionsRequestRequestTypeDef,
     SlotTypeMetadataTypeDef,
+    GetSlotTypesRequestGetSlotTypesPaginateTypeDef,
     GetSlotTypesRequestRequestTypeDef,
     GetUtterancesViewRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     MessageTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     SlotDefaultValueTypeDef,
     SlotTypeRegexConfigurationTypeDef,
     StartMigrationRequestRequestTypeDef,
+    StartMigrationResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UtteranceDataTypeDef,
-    FulfillmentActivityTypeDef,
-    ConversationLogsRequestTypeDef,
-    ConversationLogsResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetBotChannelAssociationResponseTypeDef,
     GetBotChannelAssociationsResponseTypeDef,
     GetBotVersionsResponseTypeDef,
     GetBotsResponseTypeDef,
-    GetBuiltinIntentResponseTypeDef,
     GetBuiltinIntentsResponseTypeDef,
+    GetBuiltinIntentResponseTypeDef,
     GetBuiltinSlotTypesResponseTypeDef,
-    GetExportResponseTypeDef,
-    GetImportResponseTypeDef,
-    StartMigrationResponseTypeDef,
-    GetBotAliasesRequestGetBotAliasesPaginateTypeDef,
-    GetBotChannelAssociationsRequestGetBotChannelAssociationsPaginateTypeDef,
-    GetBotVersionsRequestGetBotVersionsPaginateTypeDef,
-    GetBotsRequestGetBotsPaginateTypeDef,
-    GetBuiltinIntentsRequestGetBuiltinIntentsPaginateTypeDef,
-    GetBuiltinSlotTypesRequestGetBuiltinSlotTypesPaginateTypeDef,
-    GetIntentVersionsRequestGetIntentVersionsPaginateTypeDef,
-    GetIntentsRequestGetIntentsPaginateTypeDef,
-    GetSlotTypeVersionsRequestGetSlotTypeVersionsPaginateTypeDef,
-    GetSlotTypesRequestGetSlotTypesPaginateTypeDef,
+    FulfillmentActivityTypeDef,
+    ConversationLogsRequestTypeDef,
+    ConversationLogsResponseTypeDef,
     GetIntentVersionsResponseTypeDef,
     GetIntentsResponseTypeDef,
     GetMigrationResponseTypeDef,
     GetMigrationsResponseTypeDef,
     GetSlotTypeVersionsResponseTypeDef,
     GetSlotTypesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -509,43 +509,43 @@
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

### Comparing `types-aiobotocore-lex-models-2.5.0.post1/types_aiobotocore_lex_models.egg-info/SOURCES.txt` & `types-aiobotocore-lex-models-2.5.1/types_aiobotocore_lex_models.egg-info/SOURCES.txt`

 * *Files identical despite different names*

