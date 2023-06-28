# Comparing `tmp/types-aiobotocore-transcribe-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-transcribe-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-transcribe-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:27 2023, max compression
+gzip compressed data, was "types-aiobotocore-transcribe-2.5.1.tar", last modified: Wed Jun 28 01:44:17 2023, max compression
```

## Comparing `types-aiobotocore-transcribe-2.5.0.post1.tar` & `types-aiobotocore-transcribe-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.931699 types-aiobotocore-transcribe-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16887 2023-03-11 12:27:27.923699 types-aiobotocore-transcribe-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15297 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:27.931699 types-aiobotocore-transcribe-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.923699 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/
--rw-r--r--   0 runner    (1001) docker     (123)      501 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      500 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    31569 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    31521 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10245 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10243 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    39017 2023-03-11 12:25:09.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    38986 2023-03-11 12:25:09.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:08.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.923699 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16887 2023-03-11 12:27:27.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      785 2023-03-11 12:27:27.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:27.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:27:27.000000 types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.858227 types-aiobotocore-transcribe-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16882 2023-06-28 01:44:17.858227 types-aiobotocore-transcribe-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15298 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:17.858227 types-aiobotocore-transcribe-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.858227 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      500 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31721 2023-06-28 01:41:57.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31673 2023-06-28 01:41:57.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10454 2023-06-28 01:41:57.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10452 2023-06-28 01:41:57.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    39213 2023-06-28 01:41:58.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39182 2023-06-28 01:41:57.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:56.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:17.858227 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16882 2023-06-28 01:44:17.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      785 2023-06-28 01:44:17.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:17.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:17.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:17.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:44:17.000000 types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/LICENSE` & `types-aiobotocore-transcribe-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/PKG-INFO` & `types-aiobotocore-transcribe-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-transcribe
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TranscribeService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TranscribeService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-transcribe"></a>
 
 # types-aiobotocore-transcribe
 
 [![PyPI - types-aiobotocore-transcribe](https://img.shields.io/pypi/v/types-aiobotocore-transcribe.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transcribe)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-transcribe.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transcribe)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-transcribe?color=blue)](https://pypistats.org/packages/types-aiobotocore-transcribe)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TranscribeService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService)
+[aiobotocore.TranscribeService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService)
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
 [types-aiobotocore-transcribe docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,33 +317,39 @@
     AbsoluteTimeRangeTypeDef,
     ContentRedactionTypeDef,
     LanguageIdSettingsTypeDef,
     CallAnalyticsJobSummaryTypeDef,
     ChannelDefinitionTypeDef,
     MediaTypeDef,
     TranscriptTypeDef,
-    ResponseMetadataTypeDef,
     InputDataConfigTypeDef,
     TagTypeDef,
+    CreateMedicalVocabularyResponseTypeDef,
+    CreateVocabularyFilterResponseTypeDef,
+    CreateVocabularyResponseTypeDef,
     DeleteCallAnalyticsCategoryRequestRequestTypeDef,
     DeleteCallAnalyticsJobRequestRequestTypeDef,
     DeleteLanguageModelRequestRequestTypeDef,
     DeleteMedicalTranscriptionJobRequestRequestTypeDef,
     DeleteMedicalVocabularyRequestRequestTypeDef,
     DeleteTranscriptionJobRequestRequestTypeDef,
     DeleteVocabularyFilterRequestRequestTypeDef,
     DeleteVocabularyRequestRequestTypeDef,
     DescribeLanguageModelRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCallAnalyticsCategoryRequestRequestTypeDef,
     GetCallAnalyticsJobRequestRequestTypeDef,
     GetMedicalTranscriptionJobRequestRequestTypeDef,
     GetMedicalVocabularyRequestRequestTypeDef,
+    GetMedicalVocabularyResponseTypeDef,
     GetTranscriptionJobRequestRequestTypeDef,
     GetVocabularyFilterRequestRequestTypeDef,
+    GetVocabularyFilterResponseTypeDef,
     GetVocabularyRequestRequestTypeDef,
+    GetVocabularyResponseTypeDef,
     RelativeTimeRangeTypeDef,
     JobExecutionSettingsTypeDef,
     LanguageCodeItemTypeDef,
     ListCallAnalyticsCategoriesRequestRequestTypeDef,
     ListCallAnalyticsJobsRequestRequestTypeDef,
     ListLanguageModelsRequestRequestTypeDef,
     ListMedicalTranscriptionJobsRequestRequestTypeDef,
@@ -354,33 +360,27 @@
     ListTranscriptionJobsRequestRequestTypeDef,
     ListVocabulariesRequestRequestTypeDef,
     ListVocabularyFiltersRequestRequestTypeDef,
     VocabularyFilterInfoTypeDef,
     MedicalTranscriptTypeDef,
     MedicalTranscriptionSettingTypeDef,
     ModelSettingsTypeDef,
+    ResponseMetadataTypeDef,
     SettingsTypeDef,
     SubtitlesTypeDef,
     SubtitlesOutputTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateMedicalVocabularyRequestRequestTypeDef,
+    UpdateMedicalVocabularyResponseTypeDef,
     UpdateVocabularyFilterRequestRequestTypeDef,
+    UpdateVocabularyFilterResponseTypeDef,
     UpdateVocabularyRequestRequestTypeDef,
+    UpdateVocabularyResponseTypeDef,
     CallAnalyticsJobSettingsTypeDef,
-    CreateMedicalVocabularyResponseTypeDef,
-    CreateVocabularyFilterResponseTypeDef,
-    CreateVocabularyResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetMedicalVocabularyResponseTypeDef,
-    GetVocabularyFilterResponseTypeDef,
-    GetVocabularyResponseTypeDef,
     ListCallAnalyticsJobsResponseTypeDef,
-    UpdateMedicalVocabularyResponseTypeDef,
-    UpdateVocabularyFilterResponseTypeDef,
-    UpdateVocabularyResponseTypeDef,
     CreateLanguageModelResponseTypeDef,
     LanguageModelTypeDef,
     CreateLanguageModelRequestRequestTypeDef,
     CreateMedicalVocabularyRequestRequestTypeDef,
     CreateVocabularyFilterRequestRequestTypeDef,
     CreateVocabularyRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -427,43 +427,43 @@
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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/README.md` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-transcribe
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.TranscribeService 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore transcribe type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-transcribe"></a>
 
 # types-aiobotocore-transcribe
 
 [![PyPI - types-aiobotocore-transcribe](https://img.shields.io/pypi/v/types-aiobotocore-transcribe.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transcribe)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-transcribe.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transcribe)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-transcribe?color=blue)](https://pypistats.org/packages/types-aiobotocore-transcribe)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TranscribeService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService)
+[aiobotocore.TranscribeService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService)
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
 [types-aiobotocore-transcribe docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/).
 
 See how it helps to find and fix potential bugs:
 
@@ -284,33 +317,39 @@
     AbsoluteTimeRangeTypeDef,
     ContentRedactionTypeDef,
     LanguageIdSettingsTypeDef,
     CallAnalyticsJobSummaryTypeDef,
     ChannelDefinitionTypeDef,
     MediaTypeDef,
     TranscriptTypeDef,
-    ResponseMetadataTypeDef,
     InputDataConfigTypeDef,
     TagTypeDef,
+    CreateMedicalVocabularyResponseTypeDef,
+    CreateVocabularyFilterResponseTypeDef,
+    CreateVocabularyResponseTypeDef,
     DeleteCallAnalyticsCategoryRequestRequestTypeDef,
     DeleteCallAnalyticsJobRequestRequestTypeDef,
     DeleteLanguageModelRequestRequestTypeDef,
     DeleteMedicalTranscriptionJobRequestRequestTypeDef,
     DeleteMedicalVocabularyRequestRequestTypeDef,
     DeleteTranscriptionJobRequestRequestTypeDef,
     DeleteVocabularyFilterRequestRequestTypeDef,
     DeleteVocabularyRequestRequestTypeDef,
     DescribeLanguageModelRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCallAnalyticsCategoryRequestRequestTypeDef,
     GetCallAnalyticsJobRequestRequestTypeDef,
     GetMedicalTranscriptionJobRequestRequestTypeDef,
     GetMedicalVocabularyRequestRequestTypeDef,
+    GetMedicalVocabularyResponseTypeDef,
     GetTranscriptionJobRequestRequestTypeDef,
     GetVocabularyFilterRequestRequestTypeDef,
+    GetVocabularyFilterResponseTypeDef,
     GetVocabularyRequestRequestTypeDef,
+    GetVocabularyResponseTypeDef,
     RelativeTimeRangeTypeDef,
     JobExecutionSettingsTypeDef,
     LanguageCodeItemTypeDef,
     ListCallAnalyticsCategoriesRequestRequestTypeDef,
     ListCallAnalyticsJobsRequestRequestTypeDef,
     ListLanguageModelsRequestRequestTypeDef,
     ListMedicalTranscriptionJobsRequestRequestTypeDef,
@@ -321,33 +360,27 @@
     ListTranscriptionJobsRequestRequestTypeDef,
     ListVocabulariesRequestRequestTypeDef,
     ListVocabularyFiltersRequestRequestTypeDef,
     VocabularyFilterInfoTypeDef,
     MedicalTranscriptTypeDef,
     MedicalTranscriptionSettingTypeDef,
     ModelSettingsTypeDef,
+    ResponseMetadataTypeDef,
     SettingsTypeDef,
     SubtitlesTypeDef,
     SubtitlesOutputTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateMedicalVocabularyRequestRequestTypeDef,
+    UpdateMedicalVocabularyResponseTypeDef,
     UpdateVocabularyFilterRequestRequestTypeDef,
+    UpdateVocabularyFilterResponseTypeDef,
     UpdateVocabularyRequestRequestTypeDef,
+    UpdateVocabularyResponseTypeDef,
     CallAnalyticsJobSettingsTypeDef,
-    CreateMedicalVocabularyResponseTypeDef,
-    CreateVocabularyFilterResponseTypeDef,
-    CreateVocabularyResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetMedicalVocabularyResponseTypeDef,
-    GetVocabularyFilterResponseTypeDef,
-    GetVocabularyResponseTypeDef,
     ListCallAnalyticsJobsResponseTypeDef,
-    UpdateMedicalVocabularyResponseTypeDef,
-    UpdateVocabularyFilterResponseTypeDef,
-    UpdateVocabularyResponseTypeDef,
     CreateLanguageModelResponseTypeDef,
     LanguageModelTypeDef,
     CreateLanguageModelRequestRequestTypeDef,
     CreateMedicalVocabularyRequestRequestTypeDef,
     CreateVocabularyFilterRequestRequestTypeDef,
     CreateVocabularyRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -394,43 +427,43 @@
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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/setup.py` & `types-aiobotocore-transcribe-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-transcribe.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-transcribe",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_transcribe"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.TranscribeService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.TranscribeService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/"
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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/__main__.py` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.TranscribeService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.TranscribeService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService\nOther"
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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/client.py` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -181,15 +181,16 @@
     async def create_vocabulary(
         self,
         *,
         VocabularyName: str,
         LanguageCode: LanguageCodeType,
         Phrases: Sequence[str] = ...,
         VocabularyFileUri: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        DataAccessRoleArn: str = ...
     ) -> CreateVocabularyResponseTypeDef:
         """
         Creates a new custom vocabulary.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_vocabulary)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#create_vocabulary)
         """
@@ -197,15 +198,16 @@
     async def create_vocabulary_filter(
         self,
         *,
         VocabularyFilterName: str,
         LanguageCode: LanguageCodeType,
         Words: Sequence[str] = ...,
         VocabularyFilterFileUri: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        DataAccessRoleArn: str = ...
     ) -> CreateVocabularyFilterResponseTypeDef:
         """
         Creates a new custom vocabulary filter.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_vocabulary_filter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#create_vocabulary_filter)
         """
@@ -612,29 +614,31 @@
 
     async def update_vocabulary(
         self,
         *,
         VocabularyName: str,
         LanguageCode: LanguageCodeType,
         Phrases: Sequence[str] = ...,
-        VocabularyFileUri: str = ...
+        VocabularyFileUri: str = ...,
+        DataAccessRoleArn: str = ...
     ) -> UpdateVocabularyResponseTypeDef:
         """
         Updates an existing custom vocabulary with new values.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_vocabulary)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#update_vocabulary)
         """
 
     async def update_vocabulary_filter(
         self,
         *,
         VocabularyFilterName: str,
         Words: Sequence[str] = ...,
-        VocabularyFilterFileUri: str = ...
+        VocabularyFilterFileUri: str = ...,
+        DataAccessRoleArn: str = ...
     ) -> UpdateVocabularyFilterResponseTypeDef:
         """
         Updates an existing custom vocabulary filter with a new list of words.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_vocabulary_filter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#update_vocabulary_filter)
         """
```

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/client.pyi` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -171,30 +171,32 @@
     async def create_vocabulary(
         self,
         *,
         VocabularyName: str,
         LanguageCode: LanguageCodeType,
         Phrases: Sequence[str] = ...,
         VocabularyFileUri: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        DataAccessRoleArn: str = ...
     ) -> CreateVocabularyResponseTypeDef:
         """
         Creates a new custom vocabulary.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_vocabulary)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#create_vocabulary)
         """
     async def create_vocabulary_filter(
         self,
         *,
         VocabularyFilterName: str,
         LanguageCode: LanguageCodeType,
         Words: Sequence[str] = ...,
         VocabularyFilterFileUri: str = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        DataAccessRoleArn: str = ...
     ) -> CreateVocabularyFilterResponseTypeDef:
         """
         Creates a new custom vocabulary filter.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.create_vocabulary_filter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#create_vocabulary_filter)
         """
@@ -567,28 +569,30 @@
         """
     async def update_vocabulary(
         self,
         *,
         VocabularyName: str,
         LanguageCode: LanguageCodeType,
         Phrases: Sequence[str] = ...,
-        VocabularyFileUri: str = ...
+        VocabularyFileUri: str = ...,
+        DataAccessRoleArn: str = ...
     ) -> UpdateVocabularyResponseTypeDef:
         """
         Updates an existing custom vocabulary with new values.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_vocabulary)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#update_vocabulary)
         """
     async def update_vocabulary_filter(
         self,
         *,
         VocabularyFilterName: str,
         Words: Sequence[str] = ...,
-        VocabularyFilterFileUri: str = ...
+        VocabularyFilterFileUri: str = ...,
+        DataAccessRoleArn: str = ...
     ) -> UpdateVocabularyFilterResponseTypeDef:
         """
         Updates an existing custom vocabulary filter with a new list of words.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService.Client.update_vocabulary_filter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/client/#update_vocabulary_filter)
         """
```

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/literals.py` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -181,14 +181,15 @@
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
@@ -267,14 +268,15 @@
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
@@ -285,14 +287,15 @@
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
@@ -328,14 +331,15 @@
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
@@ -354,16 +358,19 @@
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
@@ -447,15 +454,17 @@
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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/literals.pyi` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -179,14 +179,15 @@
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
@@ -265,14 +266,15 @@
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
@@ -283,14 +285,15 @@
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
@@ -326,14 +329,15 @@
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
@@ -352,16 +356,19 @@
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
@@ -445,15 +452,17 @@
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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/type_defs.py` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -49,33 +49,39 @@
     "AbsoluteTimeRangeTypeDef",
     "ContentRedactionTypeDef",
     "LanguageIdSettingsTypeDef",
     "CallAnalyticsJobSummaryTypeDef",
     "ChannelDefinitionTypeDef",
     "MediaTypeDef",
     "TranscriptTypeDef",
-    "ResponseMetadataTypeDef",
     "InputDataConfigTypeDef",
     "TagTypeDef",
+    "CreateMedicalVocabularyResponseTypeDef",
+    "CreateVocabularyFilterResponseTypeDef",
+    "CreateVocabularyResponseTypeDef",
     "DeleteCallAnalyticsCategoryRequestRequestTypeDef",
     "DeleteCallAnalyticsJobRequestRequestTypeDef",
     "DeleteLanguageModelRequestRequestTypeDef",
     "DeleteMedicalTranscriptionJobRequestRequestTypeDef",
     "DeleteMedicalVocabularyRequestRequestTypeDef",
     "DeleteTranscriptionJobRequestRequestTypeDef",
     "DeleteVocabularyFilterRequestRequestTypeDef",
     "DeleteVocabularyRequestRequestTypeDef",
     "DescribeLanguageModelRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCallAnalyticsCategoryRequestRequestTypeDef",
     "GetCallAnalyticsJobRequestRequestTypeDef",
     "GetMedicalTranscriptionJobRequestRequestTypeDef",
     "GetMedicalVocabularyRequestRequestTypeDef",
+    "GetMedicalVocabularyResponseTypeDef",
     "GetTranscriptionJobRequestRequestTypeDef",
     "GetVocabularyFilterRequestRequestTypeDef",
+    "GetVocabularyFilterResponseTypeDef",
     "GetVocabularyRequestRequestTypeDef",
+    "GetVocabularyResponseTypeDef",
     "RelativeTimeRangeTypeDef",
     "JobExecutionSettingsTypeDef",
     "LanguageCodeItemTypeDef",
     "ListCallAnalyticsCategoriesRequestRequestTypeDef",
     "ListCallAnalyticsJobsRequestRequestTypeDef",
     "ListLanguageModelsRequestRequestTypeDef",
     "ListMedicalTranscriptionJobsRequestRequestTypeDef",
@@ -86,33 +92,27 @@
     "ListTranscriptionJobsRequestRequestTypeDef",
     "ListVocabulariesRequestRequestTypeDef",
     "ListVocabularyFiltersRequestRequestTypeDef",
     "VocabularyFilterInfoTypeDef",
     "MedicalTranscriptTypeDef",
     "MedicalTranscriptionSettingTypeDef",
     "ModelSettingsTypeDef",
+    "ResponseMetadataTypeDef",
     "SettingsTypeDef",
     "SubtitlesTypeDef",
     "SubtitlesOutputTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateMedicalVocabularyRequestRequestTypeDef",
+    "UpdateMedicalVocabularyResponseTypeDef",
     "UpdateVocabularyFilterRequestRequestTypeDef",
+    "UpdateVocabularyFilterResponseTypeDef",
     "UpdateVocabularyRequestRequestTypeDef",
+    "UpdateVocabularyResponseTypeDef",
     "CallAnalyticsJobSettingsTypeDef",
-    "CreateMedicalVocabularyResponseTypeDef",
-    "CreateVocabularyFilterResponseTypeDef",
-    "CreateVocabularyResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetMedicalVocabularyResponseTypeDef",
-    "GetVocabularyFilterResponseTypeDef",
-    "GetVocabularyResponseTypeDef",
     "ListCallAnalyticsJobsResponseTypeDef",
-    "UpdateMedicalVocabularyResponseTypeDef",
-    "UpdateVocabularyFilterResponseTypeDef",
-    "UpdateVocabularyResponseTypeDef",
     "CreateLanguageModelResponseTypeDef",
     "LanguageModelTypeDef",
     "CreateLanguageModelRequestRequestTypeDef",
     "CreateMedicalVocabularyRequestRequestTypeDef",
     "CreateVocabularyFilterRequestRequestTypeDef",
     "CreateVocabularyRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -229,25 +229,14 @@
     {
         "TranscriptFileUri": str,
         "RedactedTranscriptFileUri": str,
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
 _RequiredInputDataConfigTypeDef = TypedDict(
     "_RequiredInputDataConfigTypeDef",
     {
         "S3Uri": str,
         "DataAccessRoleArn": str,
     },
 )
@@ -268,14 +257,48 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateMedicalVocabularyResponseTypeDef = TypedDict(
+    "CreateMedicalVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVocabularyFilterResponseTypeDef = TypedDict(
+    "CreateVocabularyFilterResponseTypeDef",
+    {
+        "VocabularyFilterName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVocabularyResponseTypeDef = TypedDict(
+    "CreateVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCallAnalyticsCategoryRequestRequestTypeDef = TypedDict(
     "DeleteCallAnalyticsCategoryRequestRequestTypeDef",
     {
         "CategoryName": str,
     },
 )
 
@@ -331,14 +354,21 @@
 DescribeLanguageModelRequestRequestTypeDef = TypedDict(
     "DescribeLanguageModelRequestRequestTypeDef",
     {
         "ModelName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCallAnalyticsCategoryRequestRequestTypeDef = TypedDict(
     "GetCallAnalyticsCategoryRequestRequestTypeDef",
     {
         "CategoryName": str,
     },
 )
 
@@ -359,35 +389,72 @@
 GetMedicalVocabularyRequestRequestTypeDef = TypedDict(
     "GetMedicalVocabularyRequestRequestTypeDef",
     {
         "VocabularyName": str,
     },
 )
 
+GetMedicalVocabularyResponseTypeDef = TypedDict(
+    "GetMedicalVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "DownloadUri": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTranscriptionJobRequestRequestTypeDef = TypedDict(
     "GetTranscriptionJobRequestRequestTypeDef",
     {
         "TranscriptionJobName": str,
     },
 )
 
 GetVocabularyFilterRequestRequestTypeDef = TypedDict(
     "GetVocabularyFilterRequestRequestTypeDef",
     {
         "VocabularyFilterName": str,
     },
 )
 
+GetVocabularyFilterResponseTypeDef = TypedDict(
+    "GetVocabularyFilterResponseTypeDef",
+    {
+        "VocabularyFilterName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "DownloadUri": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetVocabularyRequestRequestTypeDef = TypedDict(
     "GetVocabularyRequestRequestTypeDef",
     {
         "VocabularyName": str,
     },
 )
 
+GetVocabularyResponseTypeDef = TypedDict(
+    "GetVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "DownloadUri": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RelativeTimeRangeTypeDef = TypedDict(
     "RelativeTimeRangeTypeDef",
     {
         "StartPercentage": int,
         "EndPercentage": int,
         "First": int,
         "Last": int,
@@ -569,14 +636,25 @@
     "ModelSettingsTypeDef",
     {
         "LanguageModelName": str,
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
 SettingsTypeDef = TypedDict(
     "SettingsTypeDef",
     {
         "VocabularyName": str,
         "ShowSpeakerLabels": bool,
         "MaxSpeakerLabels": int,
         "ChannelIdentification": bool,
@@ -620,203 +698,127 @@
     {
         "VocabularyName": str,
         "LanguageCode": LanguageCodeType,
         "VocabularyFileUri": str,
     },
 )
 
+UpdateMedicalVocabularyResponseTypeDef = TypedDict(
+    "UpdateMedicalVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "VocabularyState": VocabularyStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateVocabularyFilterRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVocabularyFilterRequestRequestTypeDef",
     {
         "VocabularyFilterName": str,
     },
 )
 _OptionalUpdateVocabularyFilterRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateVocabularyFilterRequestRequestTypeDef",
     {
         "Words": Sequence[str],
         "VocabularyFilterFileUri": str,
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 
 class UpdateVocabularyFilterRequestRequestTypeDef(
     _RequiredUpdateVocabularyFilterRequestRequestTypeDef,
     _OptionalUpdateVocabularyFilterRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateVocabularyFilterResponseTypeDef = TypedDict(
+    "UpdateVocabularyFilterResponseTypeDef",
+    {
+        "VocabularyFilterName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateVocabularyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVocabularyRequestRequestTypeDef",
     {
         "VocabularyName": str,
         "LanguageCode": LanguageCodeType,
     },
 )
 _OptionalUpdateVocabularyRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateVocabularyRequestRequestTypeDef",
     {
         "Phrases": Sequence[str],
         "VocabularyFileUri": str,
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 
 class UpdateVocabularyRequestRequestTypeDef(
     _RequiredUpdateVocabularyRequestRequestTypeDef, _OptionalUpdateVocabularyRequestRequestTypeDef
 ):
     pass
 
 
-CallAnalyticsJobSettingsTypeDef = TypedDict(
-    "CallAnalyticsJobSettingsTypeDef",
-    {
-        "VocabularyName": str,
-        "VocabularyFilterName": str,
-        "VocabularyFilterMethod": VocabularyFilterMethodType,
-        "LanguageModelName": str,
-        "ContentRedaction": ContentRedactionTypeDef,
-        "LanguageOptions": List[LanguageCodeType],
-        "LanguageIdSettings": Dict[LanguageCodeType, LanguageIdSettingsTypeDef],
-    },
-    total=False,
-)
-
-CreateMedicalVocabularyResponseTypeDef = TypedDict(
-    "CreateMedicalVocabularyResponseTypeDef",
+UpdateVocabularyResponseTypeDef = TypedDict(
+    "UpdateVocabularyResponseTypeDef",
     {
         "VocabularyName": str,
         "LanguageCode": LanguageCodeType,
-        "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVocabularyFilterResponseTypeDef = TypedDict(
-    "CreateVocabularyFilterResponseTypeDef",
-    {
-        "VocabularyFilterName": str,
-        "LanguageCode": LanguageCodeType,
         "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVocabularyResponseTypeDef = TypedDict(
-    "CreateVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
         "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMedicalVocabularyResponseTypeDef = TypedDict(
-    "GetMedicalVocabularyResponseTypeDef",
+CallAnalyticsJobSettingsTypeDef = TypedDict(
+    "CallAnalyticsJobSettingsTypeDef",
     {
         "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "DownloadUri": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVocabularyFilterResponseTypeDef = TypedDict(
-    "GetVocabularyFilterResponseTypeDef",
-    {
         "VocabularyFilterName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "DownloadUri": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVocabularyResponseTypeDef = TypedDict(
-    "GetVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "DownloadUri": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "VocabularyFilterMethod": VocabularyFilterMethodType,
+        "LanguageModelName": str,
+        "ContentRedaction": ContentRedactionTypeDef,
+        "LanguageOptions": List[LanguageCodeType],
+        "LanguageIdSettings": Dict[LanguageCodeType, LanguageIdSettingsTypeDef],
     },
+    total=False,
 )
 
 ListCallAnalyticsJobsResponseTypeDef = TypedDict(
     "ListCallAnalyticsJobsResponseTypeDef",
     {
         "Status": CallAnalyticsJobStatusType,
         "NextToken": str,
         "CallAnalyticsJobSummaries": List[CallAnalyticsJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMedicalVocabularyResponseTypeDef = TypedDict(
-    "UpdateMedicalVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "VocabularyState": VocabularyStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateVocabularyFilterResponseTypeDef = TypedDict(
-    "UpdateVocabularyFilterResponseTypeDef",
-    {
-        "VocabularyFilterName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateVocabularyResponseTypeDef = TypedDict(
-    "UpdateVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "VocabularyState": VocabularyStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLanguageModelResponseTypeDef = TypedDict(
     "CreateLanguageModelResponseTypeDef",
     {
         "LanguageCode": CLMLanguageCodeType,
         "BaseModelName": BaseModelNameType,
         "ModelName": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "ModelStatus": ModelStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LanguageModelTypeDef = TypedDict(
     "LanguageModelTypeDef",
     {
         "ModelName": str,
@@ -890,14 +892,15 @@
 )
 _OptionalCreateVocabularyFilterRequestRequestTypeDef = TypedDict(
     "_OptionalCreateVocabularyFilterRequestRequestTypeDef",
     {
         "Words": Sequence[str],
         "VocabularyFilterFileUri": str,
         "Tags": Sequence[TagTypeDef],
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 
 class CreateVocabularyFilterRequestRequestTypeDef(
     _RequiredCreateVocabularyFilterRequestRequestTypeDef,
@@ -915,14 +918,15 @@
 )
 _OptionalCreateVocabularyRequestRequestTypeDef = TypedDict(
     "_OptionalCreateVocabularyRequestRequestTypeDef",
     {
         "Phrases": Sequence[str],
         "VocabularyFileUri": str,
         "Tags": Sequence[TagTypeDef],
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 
 class CreateVocabularyRequestRequestTypeDef(
     _RequiredCreateVocabularyRequestRequestTypeDef, _OptionalCreateVocabularyRequestRequestTypeDef
@@ -931,15 +935,15 @@
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1017,44 +1021,44 @@
 
 ListMedicalTranscriptionJobsResponseTypeDef = TypedDict(
     "ListMedicalTranscriptionJobsResponseTypeDef",
     {
         "Status": TranscriptionJobStatusType,
         "NextToken": str,
         "MedicalTranscriptionJobSummaries": List[MedicalTranscriptionJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMedicalVocabulariesResponseTypeDef = TypedDict(
     "ListMedicalVocabulariesResponseTypeDef",
     {
         "Status": VocabularyStateType,
         "NextToken": str,
         "Vocabularies": List[VocabularyInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVocabulariesResponseTypeDef = TypedDict(
     "ListVocabulariesResponseTypeDef",
     {
         "Status": VocabularyStateType,
         "NextToken": str,
         "Vocabularies": List[VocabularyInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVocabularyFiltersResponseTypeDef = TypedDict(
     "ListVocabularyFiltersResponseTypeDef",
     {
         "NextToken": str,
         "VocabularyFilters": List[VocabularyFilterInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MedicalTranscriptionJobTypeDef = TypedDict(
     "MedicalTranscriptionJobTypeDef",
     {
         "MedicalTranscriptionJobName": str,
@@ -1250,24 +1254,24 @@
     pass
 
 
 DescribeLanguageModelResponseTypeDef = TypedDict(
     "DescribeLanguageModelResponseTypeDef",
     {
         "LanguageModel": LanguageModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLanguageModelsResponseTypeDef = TypedDict(
     "ListLanguageModelsResponseTypeDef",
     {
         "NextToken": str,
         "Models": List[LanguageModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuleTypeDef = TypedDict(
     "RuleTypeDef",
     {
         "NonTalkTimeFilter": NonTalkTimeFilterTypeDef,
@@ -1278,65 +1282,65 @@
     total=False,
 )
 
 GetMedicalTranscriptionJobResponseTypeDef = TypedDict(
     "GetMedicalTranscriptionJobResponseTypeDef",
     {
         "MedicalTranscriptionJob": MedicalTranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMedicalTranscriptionJobResponseTypeDef = TypedDict(
     "StartMedicalTranscriptionJobResponseTypeDef",
     {
         "MedicalTranscriptionJob": MedicalTranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTranscriptionJobsResponseTypeDef = TypedDict(
     "ListTranscriptionJobsResponseTypeDef",
     {
         "Status": TranscriptionJobStatusType,
         "NextToken": str,
         "TranscriptionJobSummaries": List[TranscriptionJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTranscriptionJobResponseTypeDef = TypedDict(
     "GetTranscriptionJobResponseTypeDef",
     {
         "TranscriptionJob": TranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTranscriptionJobResponseTypeDef = TypedDict(
     "StartTranscriptionJobResponseTypeDef",
     {
         "TranscriptionJob": TranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCallAnalyticsJobResponseTypeDef = TypedDict(
     "GetCallAnalyticsJobResponseTypeDef",
     {
         "CallAnalyticsJob": CallAnalyticsJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartCallAnalyticsJobResponseTypeDef = TypedDict(
     "StartCallAnalyticsJobResponseTypeDef",
     {
         "CallAnalyticsJob": CallAnalyticsJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CategoryPropertiesTypeDef = TypedDict(
     "CategoryPropertiesTypeDef",
     {
         "CategoryName": str,
@@ -1394,35 +1398,35 @@
     pass
 
 
 CreateCallAnalyticsCategoryResponseTypeDef = TypedDict(
     "CreateCallAnalyticsCategoryResponseTypeDef",
     {
         "CategoryProperties": CategoryPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCallAnalyticsCategoryResponseTypeDef = TypedDict(
     "GetCallAnalyticsCategoryResponseTypeDef",
     {
         "CategoryProperties": CategoryPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCallAnalyticsCategoriesResponseTypeDef = TypedDict(
     "ListCallAnalyticsCategoriesResponseTypeDef",
     {
         "NextToken": str,
         "Categories": List[CategoryPropertiesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCallAnalyticsCategoryResponseTypeDef = TypedDict(
     "UpdateCallAnalyticsCategoryResponseTypeDef",
     {
         "CategoryProperties": CategoryPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe/type_defs.pyi` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -48,33 +48,39 @@
     "AbsoluteTimeRangeTypeDef",
     "ContentRedactionTypeDef",
     "LanguageIdSettingsTypeDef",
     "CallAnalyticsJobSummaryTypeDef",
     "ChannelDefinitionTypeDef",
     "MediaTypeDef",
     "TranscriptTypeDef",
-    "ResponseMetadataTypeDef",
     "InputDataConfigTypeDef",
     "TagTypeDef",
+    "CreateMedicalVocabularyResponseTypeDef",
+    "CreateVocabularyFilterResponseTypeDef",
+    "CreateVocabularyResponseTypeDef",
     "DeleteCallAnalyticsCategoryRequestRequestTypeDef",
     "DeleteCallAnalyticsJobRequestRequestTypeDef",
     "DeleteLanguageModelRequestRequestTypeDef",
     "DeleteMedicalTranscriptionJobRequestRequestTypeDef",
     "DeleteMedicalVocabularyRequestRequestTypeDef",
     "DeleteTranscriptionJobRequestRequestTypeDef",
     "DeleteVocabularyFilterRequestRequestTypeDef",
     "DeleteVocabularyRequestRequestTypeDef",
     "DescribeLanguageModelRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCallAnalyticsCategoryRequestRequestTypeDef",
     "GetCallAnalyticsJobRequestRequestTypeDef",
     "GetMedicalTranscriptionJobRequestRequestTypeDef",
     "GetMedicalVocabularyRequestRequestTypeDef",
+    "GetMedicalVocabularyResponseTypeDef",
     "GetTranscriptionJobRequestRequestTypeDef",
     "GetVocabularyFilterRequestRequestTypeDef",
+    "GetVocabularyFilterResponseTypeDef",
     "GetVocabularyRequestRequestTypeDef",
+    "GetVocabularyResponseTypeDef",
     "RelativeTimeRangeTypeDef",
     "JobExecutionSettingsTypeDef",
     "LanguageCodeItemTypeDef",
     "ListCallAnalyticsCategoriesRequestRequestTypeDef",
     "ListCallAnalyticsJobsRequestRequestTypeDef",
     "ListLanguageModelsRequestRequestTypeDef",
     "ListMedicalTranscriptionJobsRequestRequestTypeDef",
@@ -85,33 +91,27 @@
     "ListTranscriptionJobsRequestRequestTypeDef",
     "ListVocabulariesRequestRequestTypeDef",
     "ListVocabularyFiltersRequestRequestTypeDef",
     "VocabularyFilterInfoTypeDef",
     "MedicalTranscriptTypeDef",
     "MedicalTranscriptionSettingTypeDef",
     "ModelSettingsTypeDef",
+    "ResponseMetadataTypeDef",
     "SettingsTypeDef",
     "SubtitlesTypeDef",
     "SubtitlesOutputTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateMedicalVocabularyRequestRequestTypeDef",
+    "UpdateMedicalVocabularyResponseTypeDef",
     "UpdateVocabularyFilterRequestRequestTypeDef",
+    "UpdateVocabularyFilterResponseTypeDef",
     "UpdateVocabularyRequestRequestTypeDef",
+    "UpdateVocabularyResponseTypeDef",
     "CallAnalyticsJobSettingsTypeDef",
-    "CreateMedicalVocabularyResponseTypeDef",
-    "CreateVocabularyFilterResponseTypeDef",
-    "CreateVocabularyResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetMedicalVocabularyResponseTypeDef",
-    "GetVocabularyFilterResponseTypeDef",
-    "GetVocabularyResponseTypeDef",
     "ListCallAnalyticsJobsResponseTypeDef",
-    "UpdateMedicalVocabularyResponseTypeDef",
-    "UpdateVocabularyFilterResponseTypeDef",
-    "UpdateVocabularyResponseTypeDef",
     "CreateLanguageModelResponseTypeDef",
     "LanguageModelTypeDef",
     "CreateLanguageModelRequestRequestTypeDef",
     "CreateMedicalVocabularyRequestRequestTypeDef",
     "CreateVocabularyFilterRequestRequestTypeDef",
     "CreateVocabularyRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -226,25 +226,14 @@
     {
         "TranscriptFileUri": str,
         "RedactedTranscriptFileUri": str,
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
 _RequiredInputDataConfigTypeDef = TypedDict(
     "_RequiredInputDataConfigTypeDef",
     {
         "S3Uri": str,
         "DataAccessRoleArn": str,
     },
 )
@@ -263,14 +252,48 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateMedicalVocabularyResponseTypeDef = TypedDict(
+    "CreateMedicalVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVocabularyFilterResponseTypeDef = TypedDict(
+    "CreateVocabularyFilterResponseTypeDef",
+    {
+        "VocabularyFilterName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateVocabularyResponseTypeDef = TypedDict(
+    "CreateVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCallAnalyticsCategoryRequestRequestTypeDef = TypedDict(
     "DeleteCallAnalyticsCategoryRequestRequestTypeDef",
     {
         "CategoryName": str,
     },
 )
 
@@ -326,14 +349,21 @@
 DescribeLanguageModelRequestRequestTypeDef = TypedDict(
     "DescribeLanguageModelRequestRequestTypeDef",
     {
         "ModelName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCallAnalyticsCategoryRequestRequestTypeDef = TypedDict(
     "GetCallAnalyticsCategoryRequestRequestTypeDef",
     {
         "CategoryName": str,
     },
 )
 
@@ -354,35 +384,72 @@
 GetMedicalVocabularyRequestRequestTypeDef = TypedDict(
     "GetMedicalVocabularyRequestRequestTypeDef",
     {
         "VocabularyName": str,
     },
 )
 
+GetMedicalVocabularyResponseTypeDef = TypedDict(
+    "GetMedicalVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "DownloadUri": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTranscriptionJobRequestRequestTypeDef = TypedDict(
     "GetTranscriptionJobRequestRequestTypeDef",
     {
         "TranscriptionJobName": str,
     },
 )
 
 GetVocabularyFilterRequestRequestTypeDef = TypedDict(
     "GetVocabularyFilterRequestRequestTypeDef",
     {
         "VocabularyFilterName": str,
     },
 )
 
+GetVocabularyFilterResponseTypeDef = TypedDict(
+    "GetVocabularyFilterResponseTypeDef",
+    {
+        "VocabularyFilterName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "DownloadUri": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetVocabularyRequestRequestTypeDef = TypedDict(
     "GetVocabularyRequestRequestTypeDef",
     {
         "VocabularyName": str,
     },
 )
 
+GetVocabularyResponseTypeDef = TypedDict(
+    "GetVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "VocabularyState": VocabularyStateType,
+        "LastModifiedTime": datetime,
+        "FailureReason": str,
+        "DownloadUri": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RelativeTimeRangeTypeDef = TypedDict(
     "RelativeTimeRangeTypeDef",
     {
         "StartPercentage": int,
         "EndPercentage": int,
         "First": int,
         "Last": int,
@@ -564,14 +631,25 @@
     "ModelSettingsTypeDef",
     {
         "LanguageModelName": str,
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
 SettingsTypeDef = TypedDict(
     "SettingsTypeDef",
     {
         "VocabularyName": str,
         "ShowSpeakerLabels": bool,
         "MaxSpeakerLabels": int,
         "ChannelIdentification": bool,
@@ -615,199 +693,123 @@
     {
         "VocabularyName": str,
         "LanguageCode": LanguageCodeType,
         "VocabularyFileUri": str,
     },
 )
 
+UpdateMedicalVocabularyResponseTypeDef = TypedDict(
+    "UpdateMedicalVocabularyResponseTypeDef",
+    {
+        "VocabularyName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "VocabularyState": VocabularyStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateVocabularyFilterRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVocabularyFilterRequestRequestTypeDef",
     {
         "VocabularyFilterName": str,
     },
 )
 _OptionalUpdateVocabularyFilterRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateVocabularyFilterRequestRequestTypeDef",
     {
         "Words": Sequence[str],
         "VocabularyFilterFileUri": str,
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 class UpdateVocabularyFilterRequestRequestTypeDef(
     _RequiredUpdateVocabularyFilterRequestRequestTypeDef,
     _OptionalUpdateVocabularyFilterRequestRequestTypeDef,
 ):
     pass
 
+UpdateVocabularyFilterResponseTypeDef = TypedDict(
+    "UpdateVocabularyFilterResponseTypeDef",
+    {
+        "VocabularyFilterName": str,
+        "LanguageCode": LanguageCodeType,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateVocabularyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateVocabularyRequestRequestTypeDef",
     {
         "VocabularyName": str,
         "LanguageCode": LanguageCodeType,
     },
 )
 _OptionalUpdateVocabularyRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateVocabularyRequestRequestTypeDef",
     {
         "Phrases": Sequence[str],
         "VocabularyFileUri": str,
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 class UpdateVocabularyRequestRequestTypeDef(
     _RequiredUpdateVocabularyRequestRequestTypeDef, _OptionalUpdateVocabularyRequestRequestTypeDef
 ):
     pass
 
-CallAnalyticsJobSettingsTypeDef = TypedDict(
-    "CallAnalyticsJobSettingsTypeDef",
-    {
-        "VocabularyName": str,
-        "VocabularyFilterName": str,
-        "VocabularyFilterMethod": VocabularyFilterMethodType,
-        "LanguageModelName": str,
-        "ContentRedaction": ContentRedactionTypeDef,
-        "LanguageOptions": List[LanguageCodeType],
-        "LanguageIdSettings": Dict[LanguageCodeType, LanguageIdSettingsTypeDef],
-    },
-    total=False,
-)
-
-CreateMedicalVocabularyResponseTypeDef = TypedDict(
-    "CreateMedicalVocabularyResponseTypeDef",
+UpdateVocabularyResponseTypeDef = TypedDict(
+    "UpdateVocabularyResponseTypeDef",
     {
         "VocabularyName": str,
         "LanguageCode": LanguageCodeType,
-        "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVocabularyFilterResponseTypeDef = TypedDict(
-    "CreateVocabularyFilterResponseTypeDef",
-    {
-        "VocabularyFilterName": str,
-        "LanguageCode": LanguageCodeType,
         "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVocabularyResponseTypeDef = TypedDict(
-    "CreateVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
         "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMedicalVocabularyResponseTypeDef = TypedDict(
-    "GetMedicalVocabularyResponseTypeDef",
+CallAnalyticsJobSettingsTypeDef = TypedDict(
+    "CallAnalyticsJobSettingsTypeDef",
     {
         "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "DownloadUri": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVocabularyFilterResponseTypeDef = TypedDict(
-    "GetVocabularyFilterResponseTypeDef",
-    {
         "VocabularyFilterName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "DownloadUri": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVocabularyResponseTypeDef = TypedDict(
-    "GetVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "VocabularyState": VocabularyStateType,
-        "LastModifiedTime": datetime,
-        "FailureReason": str,
-        "DownloadUri": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "VocabularyFilterMethod": VocabularyFilterMethodType,
+        "LanguageModelName": str,
+        "ContentRedaction": ContentRedactionTypeDef,
+        "LanguageOptions": List[LanguageCodeType],
+        "LanguageIdSettings": Dict[LanguageCodeType, LanguageIdSettingsTypeDef],
     },
+    total=False,
 )
 
 ListCallAnalyticsJobsResponseTypeDef = TypedDict(
     "ListCallAnalyticsJobsResponseTypeDef",
     {
         "Status": CallAnalyticsJobStatusType,
         "NextToken": str,
         "CallAnalyticsJobSummaries": List[CallAnalyticsJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMedicalVocabularyResponseTypeDef = TypedDict(
-    "UpdateMedicalVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "VocabularyState": VocabularyStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateVocabularyFilterResponseTypeDef = TypedDict(
-    "UpdateVocabularyFilterResponseTypeDef",
-    {
-        "VocabularyFilterName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateVocabularyResponseTypeDef = TypedDict(
-    "UpdateVocabularyResponseTypeDef",
-    {
-        "VocabularyName": str,
-        "LanguageCode": LanguageCodeType,
-        "LastModifiedTime": datetime,
-        "VocabularyState": VocabularyStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLanguageModelResponseTypeDef = TypedDict(
     "CreateLanguageModelResponseTypeDef",
     {
         "LanguageCode": CLMLanguageCodeType,
         "BaseModelName": BaseModelNameType,
         "ModelName": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "ModelStatus": ModelStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LanguageModelTypeDef = TypedDict(
     "LanguageModelTypeDef",
     {
         "ModelName": str,
@@ -877,14 +879,15 @@
 )
 _OptionalCreateVocabularyFilterRequestRequestTypeDef = TypedDict(
     "_OptionalCreateVocabularyFilterRequestRequestTypeDef",
     {
         "Words": Sequence[str],
         "VocabularyFilterFileUri": str,
         "Tags": Sequence[TagTypeDef],
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 class CreateVocabularyFilterRequestRequestTypeDef(
     _RequiredCreateVocabularyFilterRequestRequestTypeDef,
     _OptionalCreateVocabularyFilterRequestRequestTypeDef,
@@ -900,29 +903,30 @@
 )
 _OptionalCreateVocabularyRequestRequestTypeDef = TypedDict(
     "_OptionalCreateVocabularyRequestRequestTypeDef",
     {
         "Phrases": Sequence[str],
         "VocabularyFileUri": str,
         "Tags": Sequence[TagTypeDef],
+        "DataAccessRoleArn": str,
     },
     total=False,
 )
 
 class CreateVocabularyRequestRequestTypeDef(
     _RequiredCreateVocabularyRequestRequestTypeDef, _OptionalCreateVocabularyRequestRequestTypeDef
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -996,44 +1000,44 @@
 
 ListMedicalTranscriptionJobsResponseTypeDef = TypedDict(
     "ListMedicalTranscriptionJobsResponseTypeDef",
     {
         "Status": TranscriptionJobStatusType,
         "NextToken": str,
         "MedicalTranscriptionJobSummaries": List[MedicalTranscriptionJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMedicalVocabulariesResponseTypeDef = TypedDict(
     "ListMedicalVocabulariesResponseTypeDef",
     {
         "Status": VocabularyStateType,
         "NextToken": str,
         "Vocabularies": List[VocabularyInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVocabulariesResponseTypeDef = TypedDict(
     "ListVocabulariesResponseTypeDef",
     {
         "Status": VocabularyStateType,
         "NextToken": str,
         "Vocabularies": List[VocabularyInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVocabularyFiltersResponseTypeDef = TypedDict(
     "ListVocabularyFiltersResponseTypeDef",
     {
         "NextToken": str,
         "VocabularyFilters": List[VocabularyFilterInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MedicalTranscriptionJobTypeDef = TypedDict(
     "MedicalTranscriptionJobTypeDef",
     {
         "MedicalTranscriptionJobName": str,
@@ -1223,24 +1227,24 @@
 ):
     pass
 
 DescribeLanguageModelResponseTypeDef = TypedDict(
     "DescribeLanguageModelResponseTypeDef",
     {
         "LanguageModel": LanguageModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLanguageModelsResponseTypeDef = TypedDict(
     "ListLanguageModelsResponseTypeDef",
     {
         "NextToken": str,
         "Models": List[LanguageModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuleTypeDef = TypedDict(
     "RuleTypeDef",
     {
         "NonTalkTimeFilter": NonTalkTimeFilterTypeDef,
@@ -1251,65 +1255,65 @@
     total=False,
 )
 
 GetMedicalTranscriptionJobResponseTypeDef = TypedDict(
     "GetMedicalTranscriptionJobResponseTypeDef",
     {
         "MedicalTranscriptionJob": MedicalTranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMedicalTranscriptionJobResponseTypeDef = TypedDict(
     "StartMedicalTranscriptionJobResponseTypeDef",
     {
         "MedicalTranscriptionJob": MedicalTranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTranscriptionJobsResponseTypeDef = TypedDict(
     "ListTranscriptionJobsResponseTypeDef",
     {
         "Status": TranscriptionJobStatusType,
         "NextToken": str,
         "TranscriptionJobSummaries": List[TranscriptionJobSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTranscriptionJobResponseTypeDef = TypedDict(
     "GetTranscriptionJobResponseTypeDef",
     {
         "TranscriptionJob": TranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTranscriptionJobResponseTypeDef = TypedDict(
     "StartTranscriptionJobResponseTypeDef",
     {
         "TranscriptionJob": TranscriptionJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCallAnalyticsJobResponseTypeDef = TypedDict(
     "GetCallAnalyticsJobResponseTypeDef",
     {
         "CallAnalyticsJob": CallAnalyticsJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartCallAnalyticsJobResponseTypeDef = TypedDict(
     "StartCallAnalyticsJobResponseTypeDef",
     {
         "CallAnalyticsJob": CallAnalyticsJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CategoryPropertiesTypeDef = TypedDict(
     "CategoryPropertiesTypeDef",
     {
         "CategoryName": str,
@@ -1363,35 +1367,35 @@
 ):
     pass
 
 CreateCallAnalyticsCategoryResponseTypeDef = TypedDict(
     "CreateCallAnalyticsCategoryResponseTypeDef",
     {
         "CategoryProperties": CategoryPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCallAnalyticsCategoryResponseTypeDef = TypedDict(
     "GetCallAnalyticsCategoryResponseTypeDef",
     {
         "CategoryProperties": CategoryPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCallAnalyticsCategoriesResponseTypeDef = TypedDict(
     "ListCallAnalyticsCategoriesResponseTypeDef",
     {
         "NextToken": str,
         "Categories": List[CategoryPropertiesTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCallAnalyticsCategoryResponseTypeDef = TypedDict(
     "UpdateCallAnalyticsCategoryResponseTypeDef",
     {
         "CategoryProperties": CategoryPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/PKG-INFO` & `types-aiobotocore-transcribe-2.5.1/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-transcribe
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.TranscribeService 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore transcribe type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-transcribe"></a>
 
 # types-aiobotocore-transcribe
 
 [![PyPI - types-aiobotocore-transcribe](https://img.shields.io/pypi/v/types-aiobotocore-transcribe.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transcribe)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-transcribe.svg?color=blue)](https://pypi.org/project/types-aiobotocore-transcribe)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-transcribe?color=blue)](https://pypistats.org/packages/types-aiobotocore-transcribe)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.TranscribeService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService)
+[aiobotocore.TranscribeService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/transcribe.html#TranscribeService)
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
 [types-aiobotocore-transcribe docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transcribe/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,33 +284,39 @@
     AbsoluteTimeRangeTypeDef,
     ContentRedactionTypeDef,
     LanguageIdSettingsTypeDef,
     CallAnalyticsJobSummaryTypeDef,
     ChannelDefinitionTypeDef,
     MediaTypeDef,
     TranscriptTypeDef,
-    ResponseMetadataTypeDef,
     InputDataConfigTypeDef,
     TagTypeDef,
+    CreateMedicalVocabularyResponseTypeDef,
+    CreateVocabularyFilterResponseTypeDef,
+    CreateVocabularyResponseTypeDef,
     DeleteCallAnalyticsCategoryRequestRequestTypeDef,
     DeleteCallAnalyticsJobRequestRequestTypeDef,
     DeleteLanguageModelRequestRequestTypeDef,
     DeleteMedicalTranscriptionJobRequestRequestTypeDef,
     DeleteMedicalVocabularyRequestRequestTypeDef,
     DeleteTranscriptionJobRequestRequestTypeDef,
     DeleteVocabularyFilterRequestRequestTypeDef,
     DeleteVocabularyRequestRequestTypeDef,
     DescribeLanguageModelRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCallAnalyticsCategoryRequestRequestTypeDef,
     GetCallAnalyticsJobRequestRequestTypeDef,
     GetMedicalTranscriptionJobRequestRequestTypeDef,
     GetMedicalVocabularyRequestRequestTypeDef,
+    GetMedicalVocabularyResponseTypeDef,
     GetTranscriptionJobRequestRequestTypeDef,
     GetVocabularyFilterRequestRequestTypeDef,
+    GetVocabularyFilterResponseTypeDef,
     GetVocabularyRequestRequestTypeDef,
+    GetVocabularyResponseTypeDef,
     RelativeTimeRangeTypeDef,
     JobExecutionSettingsTypeDef,
     LanguageCodeItemTypeDef,
     ListCallAnalyticsCategoriesRequestRequestTypeDef,
     ListCallAnalyticsJobsRequestRequestTypeDef,
     ListLanguageModelsRequestRequestTypeDef,
     ListMedicalTranscriptionJobsRequestRequestTypeDef,
@@ -354,33 +327,27 @@
     ListTranscriptionJobsRequestRequestTypeDef,
     ListVocabulariesRequestRequestTypeDef,
     ListVocabularyFiltersRequestRequestTypeDef,
     VocabularyFilterInfoTypeDef,
     MedicalTranscriptTypeDef,
     MedicalTranscriptionSettingTypeDef,
     ModelSettingsTypeDef,
+    ResponseMetadataTypeDef,
     SettingsTypeDef,
     SubtitlesTypeDef,
     SubtitlesOutputTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateMedicalVocabularyRequestRequestTypeDef,
+    UpdateMedicalVocabularyResponseTypeDef,
     UpdateVocabularyFilterRequestRequestTypeDef,
+    UpdateVocabularyFilterResponseTypeDef,
     UpdateVocabularyRequestRequestTypeDef,
+    UpdateVocabularyResponseTypeDef,
     CallAnalyticsJobSettingsTypeDef,
-    CreateMedicalVocabularyResponseTypeDef,
-    CreateVocabularyFilterResponseTypeDef,
-    CreateVocabularyResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetMedicalVocabularyResponseTypeDef,
-    GetVocabularyFilterResponseTypeDef,
-    GetVocabularyResponseTypeDef,
     ListCallAnalyticsJobsResponseTypeDef,
-    UpdateMedicalVocabularyResponseTypeDef,
-    UpdateVocabularyFilterResponseTypeDef,
-    UpdateVocabularyResponseTypeDef,
     CreateLanguageModelResponseTypeDef,
     LanguageModelTypeDef,
     CreateLanguageModelRequestRequestTypeDef,
     CreateMedicalVocabularyRequestRequestTypeDef,
     CreateVocabularyFilterRequestRequestTypeDef,
     CreateVocabularyRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -427,43 +394,43 @@
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

### Comparing `types-aiobotocore-transcribe-2.5.0.post1/types_aiobotocore_transcribe.egg-info/SOURCES.txt` & `types-aiobotocore-transcribe-2.5.1/types_aiobotocore_transcribe.egg-info/SOURCES.txt`

 * *Files identical despite different names*

