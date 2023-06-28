# Comparing `tmp/types-aiobotocore-translate-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-translate-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-translate-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:28 2023, max compression
+gzip compressed data, was "types-aiobotocore-translate-2.5.1.tar", last modified: Wed Jun 28 01:44:18 2023, max compression
```

## Comparing `types-aiobotocore-translate-2.5.0.post1.tar` & `types-aiobotocore-translate-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:28.019700 types-aiobotocore-translate-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15202 2023-03-11 12:27:27.987699 types-aiobotocore-translate-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13623 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:28.019700 types-aiobotocore-translate-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.987699 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/
--rw-r--r--   0 runner    (1001) docker     (123)      681 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      680 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17375 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17347 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8757 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8755 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2161 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2157 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    18687 2023-03-11 12:25:13.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    18670 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:12.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:27.987699 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15202 2023-03-11 12:27:27.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:27:27.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:27.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:27.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:27:27.000000 types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:18.318228 types-aiobotocore-translate-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15330 2023-06-28 01:44:18.318228 types-aiobotocore-translate-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13757 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:18.318228 types-aiobotocore-translate-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:18.314228 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/
+-rw-r--r--   0 runner    (1001) docker     (123)      681 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      680 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18162 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18133 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8966 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8964 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2043 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2040 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    20179 2023-06-28 01:42:04.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20160 2023-06-28 01:42:04.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:03.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:18.318228 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15330 2023-06-28 01:44:18.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:44:18.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:18.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:18.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:18.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:44:18.000000 types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-translate-2.5.0.post1/LICENSE` & `types-aiobotocore-translate-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-translate-2.5.0.post1/PKG-INFO` & `types-aiobotocore-translate-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-translate
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Translate 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Translate 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-translate"></a>
 
 # types-aiobotocore-translate
 
 [![PyPI - types-aiobotocore-translate](https://img.shields.io/pypi/v/types-aiobotocore-translate.svg?color=blue)](https://pypi.org/project/types-aiobotocore-translate)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-translate.svg?color=blue)](https://pypi.org/project/types-aiobotocore-translate)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-translate?color=blue)](https://pypistats.org/packages/types-aiobotocore-translate)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Translate 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate)
+[aiobotocore.Translate 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate)
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
 [types-aiobotocore-translate docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/).
 
 See how it helps to find and fix potential bugs:
 
@@ -330,54 +330,58 @@
 
 ```python
 from types_aiobotocore_translate.type_defs import (
     TermTypeDef,
     EncryptionKeyTypeDef,
     ParallelDataConfigTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateParallelDataResponseTypeDef,
     DeleteParallelDataRequestRequestTypeDef,
+    DeleteParallelDataResponseTypeDef,
     DeleteTerminologyRequestRequestTypeDef,
     DescribeTextTranslationJobRequestRequestTypeDef,
+    DocumentTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetParallelDataRequestRequestTypeDef,
     ParallelDataDataLocationTypeDef,
     GetTerminologyRequestRequestTypeDef,
     TerminologyDataLocationTypeDef,
     TerminologyDataTypeDef,
     InputDataConfigTypeDef,
     JobDetailsTypeDef,
     LanguageTypeDef,
     ListLanguagesRequestRequestTypeDef,
     ListParallelDataRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListTerminologiesRequestListTerminologiesPaginateTypeDef,
     ListTerminologiesRequestRequestTypeDef,
     TextTranslationJobFilterTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TranslationSettingsTypeDef,
+    StartTextTranslationJobResponseTypeDef,
     StopTextTranslationJobRequestRequestTypeDef,
+    StopTextTranslationJobResponseTypeDef,
+    TranslatedDocumentTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateParallelDataResponseTypeDef,
     AppliedTerminologyTypeDef,
     OutputDataConfigTypeDef,
     TerminologyPropertiesTypeDef,
     ParallelDataPropertiesTypeDef,
     UpdateParallelDataRequestRequestTypeDef,
     CreateParallelDataRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateParallelDataResponseTypeDef,
-    DeleteParallelDataResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartTextTranslationJobResponseTypeDef,
-    StopTextTranslationJobResponseTypeDef,
-    UpdateParallelDataResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ImportTerminologyRequestRequestTypeDef,
     ListLanguagesResponseTypeDef,
-    ListTerminologiesRequestListTerminologiesPaginateTypeDef,
     ListTextTranslationJobsRequestRequestTypeDef,
+    TranslateDocumentRequestRequestTypeDef,
     TranslateTextRequestRequestTypeDef,
+    TranslateDocumentResponseTypeDef,
     TranslateTextResponseTypeDef,
     StartTextTranslationJobRequestRequestTypeDef,
     TextTranslationJobPropertiesTypeDef,
     GetTerminologyResponseTypeDef,
     ImportTerminologyResponseTypeDef,
     ListTerminologiesResponseTypeDef,
     GetParallelDataResponseTypeDef,
@@ -394,43 +398,43 @@
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

### Comparing `types-aiobotocore-translate-2.5.0.post1/README.md` & `types-aiobotocore-translate-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-translate"></a>
 
 # types-aiobotocore-translate
 
 [![PyPI - types-aiobotocore-translate](https://img.shields.io/pypi/v/types-aiobotocore-translate.svg?color=blue)](https://pypi.org/project/types-aiobotocore-translate)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-translate.svg?color=blue)](https://pypi.org/project/types-aiobotocore-translate)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-translate?color=blue)](https://pypistats.org/packages/types-aiobotocore-translate)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Translate 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate)
+[aiobotocore.Translate 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate)
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
 [types-aiobotocore-translate docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,54 +297,58 @@
 
 ```python
 from types_aiobotocore_translate.type_defs import (
     TermTypeDef,
     EncryptionKeyTypeDef,
     ParallelDataConfigTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateParallelDataResponseTypeDef,
     DeleteParallelDataRequestRequestTypeDef,
+    DeleteParallelDataResponseTypeDef,
     DeleteTerminologyRequestRequestTypeDef,
     DescribeTextTranslationJobRequestRequestTypeDef,
+    DocumentTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetParallelDataRequestRequestTypeDef,
     ParallelDataDataLocationTypeDef,
     GetTerminologyRequestRequestTypeDef,
     TerminologyDataLocationTypeDef,
     TerminologyDataTypeDef,
     InputDataConfigTypeDef,
     JobDetailsTypeDef,
     LanguageTypeDef,
     ListLanguagesRequestRequestTypeDef,
     ListParallelDataRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListTerminologiesRequestListTerminologiesPaginateTypeDef,
     ListTerminologiesRequestRequestTypeDef,
     TextTranslationJobFilterTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TranslationSettingsTypeDef,
+    StartTextTranslationJobResponseTypeDef,
     StopTextTranslationJobRequestRequestTypeDef,
+    StopTextTranslationJobResponseTypeDef,
+    TranslatedDocumentTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateParallelDataResponseTypeDef,
     AppliedTerminologyTypeDef,
     OutputDataConfigTypeDef,
     TerminologyPropertiesTypeDef,
     ParallelDataPropertiesTypeDef,
     UpdateParallelDataRequestRequestTypeDef,
     CreateParallelDataRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateParallelDataResponseTypeDef,
-    DeleteParallelDataResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartTextTranslationJobResponseTypeDef,
-    StopTextTranslationJobResponseTypeDef,
-    UpdateParallelDataResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ImportTerminologyRequestRequestTypeDef,
     ListLanguagesResponseTypeDef,
-    ListTerminologiesRequestListTerminologiesPaginateTypeDef,
     ListTextTranslationJobsRequestRequestTypeDef,
+    TranslateDocumentRequestRequestTypeDef,
     TranslateTextRequestRequestTypeDef,
+    TranslateDocumentResponseTypeDef,
     TranslateTextResponseTypeDef,
     StartTextTranslationJobRequestRequestTypeDef,
     TextTranslationJobPropertiesTypeDef,
     GetTerminologyResponseTypeDef,
     ImportTerminologyResponseTypeDef,
     ListTerminologiesResponseTypeDef,
     GetParallelDataResponseTypeDef,
@@ -361,43 +365,43 @@
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

### Comparing `types-aiobotocore-translate-2.5.0.post1/setup.py` & `types-aiobotocore-translate-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-translate.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-translate",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_translate"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Translate 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Translate 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/"
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

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/__init__.py` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/__init__.pyi` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/__main__.py` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Translate 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Translate 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate\nOther"
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

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/client.py` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 
 from .literals import DisplayLanguageCodeType, TerminologyDataFormatType
 from .paginator import ListTerminologiesPaginator
 from .type_defs import (
     CreateParallelDataResponseTypeDef,
     DeleteParallelDataResponseTypeDef,
     DescribeTextTranslationJobResponseTypeDef,
+    DocumentTypeDef,
     EmptyResponseMetadataTypeDef,
     EncryptionKeyTypeDef,
     GetParallelDataResponseTypeDef,
     GetTerminologyResponseTypeDef,
     ImportTerminologyResponseTypeDef,
     InputDataConfigTypeDef,
     ListLanguagesResponseTypeDef,
@@ -40,36 +41,34 @@
     OutputDataConfigTypeDef,
     ParallelDataConfigTypeDef,
     StartTextTranslationJobResponseTypeDef,
     StopTextTranslationJobResponseTypeDef,
     TagTypeDef,
     TerminologyDataTypeDef,
     TextTranslationJobFilterTypeDef,
+    TranslateDocumentResponseTypeDef,
     TranslateTextResponseTypeDef,
     TranslationSettingsTypeDef,
     UpdateParallelDataResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("TranslateClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     ConcurrentModificationException: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     DetectedLanguageLowConfidenceException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidFilterException: Type[BotocoreClientError]
@@ -80,15 +79,14 @@
     ServiceUnavailableException: Type[BotocoreClientError]
     TextSizeLimitExceededException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
     TooManyTagsException: Type[BotocoreClientError]
     UnsupportedDisplayLanguageCodeException: Type[BotocoreClientError]
     UnsupportedLanguagePairException: Type[BotocoreClientError]
 
-
 class TranslateClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/)
     """
 
     meta: ClientMeta
@@ -97,31 +95,28 @@
     def exceptions(self) -> Exceptions:
         """
         TranslateClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#exceptions)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#close)
         """
-
     async def create_parallel_data(
         self,
         *,
         Name: str,
         ParallelDataConfig: ParallelDataConfigTypeDef,
         ClientToken: str,
         Description: str = ...,
@@ -131,75 +126,68 @@
         """
         Creates a parallel data resource in Amazon Translate by importing an input file
         from Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.create_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#create_parallel_data)
         """
-
     async def delete_parallel_data(self, *, Name: str) -> DeleteParallelDataResponseTypeDef:
         """
         Deletes a parallel data resource in Amazon Translate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.delete_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#delete_parallel_data)
         """
-
     async def delete_terminology(self, *, Name: str) -> EmptyResponseMetadataTypeDef:
         """
         A synchronous action that deletes a custom terminology.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.delete_terminology)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#delete_terminology)
         """
-
     async def describe_text_translation_job(
         self, *, JobId: str
     ) -> DescribeTextTranslationJobResponseTypeDef:
         """
         Gets the properties associated with an asynchronous batch translation job
         including name, ID, status, source and target languages, input/output S3
         buckets, and so on.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.describe_text_translation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#describe_text_translation_job)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#generate_presigned_url)
         """
-
     async def get_parallel_data(self, *, Name: str) -> GetParallelDataResponseTypeDef:
         """
         Provides information about a parallel data resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.get_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#get_parallel_data)
         """
-
     async def get_terminology(
         self, *, Name: str, TerminologyDataFormat: TerminologyDataFormatType = ...
     ) -> GetTerminologyResponseTypeDef:
         """
         Retrieves a custom terminology.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.get_terminology)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#get_terminology)
         """
-
     async def import_terminology(
         self,
         *,
         Name: str,
         MergeStrategy: Literal["OVERWRITE"],
         TerminologyData: TerminologyDataTypeDef,
         Description: str = ...,
@@ -209,74 +197,68 @@
         """
         Creates or updates a custom terminology, depending on whether one already exists
         for the given terminology name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.import_terminology)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#import_terminology)
         """
-
     async def list_languages(
         self,
         *,
         DisplayLanguageCode: DisplayLanguageCodeType = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListLanguagesResponseTypeDef:
         """
         Provides a list of languages (RFC-5646 codes and names) that Amazon Translate
         supports.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_languages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_languages)
         """
-
     async def list_parallel_data(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListParallelDataResponseTypeDef:
         """
         Provides a list of your parallel data resources in Amazon Translate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_parallel_data)
         """
-
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all tags associated with a given Amazon Translate resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_tags_for_resource)
         """
-
     async def list_terminologies(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListTerminologiesResponseTypeDef:
         """
         Provides a list of custom terminologies associated with your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_terminologies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_terminologies)
         """
-
     async def list_text_translation_jobs(
         self,
         *,
         Filter: TextTranslationJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListTextTranslationJobsResponseTypeDef:
         """
         Gets a list of the batch translation jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_text_translation_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_text_translation_jobs)
         """
-
     async def start_text_translation_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         SourceLanguageCode: str,
@@ -289,33 +271,45 @@
     ) -> StartTextTranslationJobResponseTypeDef:
         """
         Starts an asynchronous batch translation job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.start_text_translation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#start_text_translation_job)
         """
-
     async def stop_text_translation_job(
         self, *, JobId: str
     ) -> StopTextTranslationJobResponseTypeDef:
         """
         Stops an asynchronous batch translation job that is in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.stop_text_translation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#stop_text_translation_job)
         """
-
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Associates a specific tag with a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#tag_resource)
         """
+    async def translate_document(
+        self,
+        *,
+        Document: DocumentTypeDef,
+        SourceLanguageCode: str,
+        TargetLanguageCode: str,
+        TerminologyNames: Sequence[str] = ...,
+        Settings: TranslationSettingsTypeDef = ...
+    ) -> TranslateDocumentResponseTypeDef:
+        """
+        Translates the input document from the source language to the target language.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.translate_document)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#translate_document)
+        """
     async def translate_text(
         self,
         *,
         Text: str,
         SourceLanguageCode: str,
         TargetLanguageCode: str,
         TerminologyNames: Sequence[str] = ...,
@@ -323,23 +317,21 @@
     ) -> TranslateTextResponseTypeDef:
         """
         Translates input text from the source language to the target language.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.translate_text)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#translate_text)
         """
-
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a specific tag associated with an Amazon Translate resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#untag_resource)
         """
-
     async def update_parallel_data(
         self,
         *,
         Name: str,
         ParallelDataConfig: ParallelDataConfigTypeDef,
         ClientToken: str,
         Description: str = ...
@@ -347,27 +339,24 @@
         """
         Updates a previously created parallel data resource by importing a new input
         file from Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.update_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#update_parallel_data)
         """
-
     def get_paginator(
         self, operation_name: Literal["list_terminologies"]
     ) -> ListTerminologiesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "TranslateClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/)
         """
```

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/client.pyi` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 
 from .literals import DisplayLanguageCodeType, TerminologyDataFormatType
 from .paginator import ListTerminologiesPaginator
 from .type_defs import (
     CreateParallelDataResponseTypeDef,
     DeleteParallelDataResponseTypeDef,
     DescribeTextTranslationJobResponseTypeDef,
+    DocumentTypeDef,
     EmptyResponseMetadataTypeDef,
     EncryptionKeyTypeDef,
     GetParallelDataResponseTypeDef,
     GetTerminologyResponseTypeDef,
     ImportTerminologyResponseTypeDef,
     InputDataConfigTypeDef,
     ListLanguagesResponseTypeDef,
@@ -40,33 +41,37 @@
     OutputDataConfigTypeDef,
     ParallelDataConfigTypeDef,
     StartTextTranslationJobResponseTypeDef,
     StopTextTranslationJobResponseTypeDef,
     TagTypeDef,
     TerminologyDataTypeDef,
     TextTranslationJobFilterTypeDef,
+    TranslateDocumentResponseTypeDef,
     TranslateTextResponseTypeDef,
     TranslationSettingsTypeDef,
     UpdateParallelDataResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("TranslateClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     ClientError: Type[BotocoreClientError]
     ConcurrentModificationException: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     DetectedLanguageLowConfidenceException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidFilterException: Type[BotocoreClientError]
@@ -77,14 +82,15 @@
     ServiceUnavailableException: Type[BotocoreClientError]
     TextSizeLimitExceededException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
     TooManyTagsException: Type[BotocoreClientError]
     UnsupportedDisplayLanguageCodeException: Type[BotocoreClientError]
     UnsupportedLanguagePairException: Type[BotocoreClientError]
 
+
 class TranslateClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/)
     """
 
     meta: ClientMeta
@@ -93,28 +99,31 @@
     def exceptions(self) -> Exceptions:
         """
         TranslateClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#exceptions)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#close)
         """
+
     async def create_parallel_data(
         self,
         *,
         Name: str,
         ParallelDataConfig: ParallelDataConfigTypeDef,
         ClientToken: str,
         Description: str = ...,
@@ -124,68 +133,75 @@
         """
         Creates a parallel data resource in Amazon Translate by importing an input file
         from Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.create_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#create_parallel_data)
         """
+
     async def delete_parallel_data(self, *, Name: str) -> DeleteParallelDataResponseTypeDef:
         """
         Deletes a parallel data resource in Amazon Translate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.delete_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#delete_parallel_data)
         """
+
     async def delete_terminology(self, *, Name: str) -> EmptyResponseMetadataTypeDef:
         """
         A synchronous action that deletes a custom terminology.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.delete_terminology)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#delete_terminology)
         """
+
     async def describe_text_translation_job(
         self, *, JobId: str
     ) -> DescribeTextTranslationJobResponseTypeDef:
         """
         Gets the properties associated with an asynchronous batch translation job
         including name, ID, status, source and target languages, input/output S3
         buckets, and so on.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.describe_text_translation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#describe_text_translation_job)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#generate_presigned_url)
         """
+
     async def get_parallel_data(self, *, Name: str) -> GetParallelDataResponseTypeDef:
         """
         Provides information about a parallel data resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.get_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#get_parallel_data)
         """
+
     async def get_terminology(
         self, *, Name: str, TerminologyDataFormat: TerminologyDataFormatType = ...
     ) -> GetTerminologyResponseTypeDef:
         """
         Retrieves a custom terminology.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.get_terminology)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#get_terminology)
         """
+
     async def import_terminology(
         self,
         *,
         Name: str,
         MergeStrategy: Literal["OVERWRITE"],
         TerminologyData: TerminologyDataTypeDef,
         Description: str = ...,
@@ -195,68 +211,74 @@
         """
         Creates or updates a custom terminology, depending on whether one already exists
         for the given terminology name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.import_terminology)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#import_terminology)
         """
+
     async def list_languages(
         self,
         *,
         DisplayLanguageCode: DisplayLanguageCodeType = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListLanguagesResponseTypeDef:
         """
         Provides a list of languages (RFC-5646 codes and names) that Amazon Translate
         supports.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_languages)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_languages)
         """
+
     async def list_parallel_data(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListParallelDataResponseTypeDef:
         """
         Provides a list of your parallel data resources in Amazon Translate.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_parallel_data)
         """
+
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all tags associated with a given Amazon Translate resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_tags_for_resource)
         """
+
     async def list_terminologies(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListTerminologiesResponseTypeDef:
         """
         Provides a list of custom terminologies associated with your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_terminologies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_terminologies)
         """
+
     async def list_text_translation_jobs(
         self,
         *,
         Filter: TextTranslationJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListTextTranslationJobsResponseTypeDef:
         """
         Gets a list of the batch translation jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.list_text_translation_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#list_text_translation_jobs)
         """
+
     async def start_text_translation_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         SourceLanguageCode: str,
@@ -269,30 +291,49 @@
     ) -> StartTextTranslationJobResponseTypeDef:
         """
         Starts an asynchronous batch translation job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.start_text_translation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#start_text_translation_job)
         """
+
     async def stop_text_translation_job(
         self, *, JobId: str
     ) -> StopTextTranslationJobResponseTypeDef:
         """
         Stops an asynchronous batch translation job that is in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.stop_text_translation_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#stop_text_translation_job)
         """
+
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Associates a specific tag with a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#tag_resource)
         """
+
+    async def translate_document(
+        self,
+        *,
+        Document: DocumentTypeDef,
+        SourceLanguageCode: str,
+        TargetLanguageCode: str,
+        TerminologyNames: Sequence[str] = ...,
+        Settings: TranslationSettingsTypeDef = ...
+    ) -> TranslateDocumentResponseTypeDef:
+        """
+        Translates the input document from the source language to the target language.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.translate_document)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#translate_document)
+        """
+
     async def translate_text(
         self,
         *,
         Text: str,
         SourceLanguageCode: str,
         TargetLanguageCode: str,
         TerminologyNames: Sequence[str] = ...,
@@ -300,21 +341,23 @@
     ) -> TranslateTextResponseTypeDef:
         """
         Translates input text from the source language to the target language.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.translate_text)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#translate_text)
         """
+
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a specific tag associated with an Amazon Translate resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#untag_resource)
         """
+
     async def update_parallel_data(
         self,
         *,
         Name: str,
         ParallelDataConfig: ParallelDataConfigTypeDef,
         ClientToken: str,
         Description: str = ...
@@ -322,24 +365,27 @@
         """
         Updates a previously created parallel data resource by importing a new input
         file from Amazon S3.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.update_parallel_data)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#update_parallel_data)
         """
+
     def get_paginator(
         self, operation_name: Literal["list_terminologies"]
     ) -> ListTerminologiesPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "TranslateClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/client/)
         """
```

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/literals.py` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -117,14 +117,15 @@
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
@@ -203,14 +204,15 @@
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
@@ -221,14 +223,15 @@
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
@@ -264,14 +267,15 @@
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
@@ -290,16 +294,19 @@
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
@@ -383,15 +390,17 @@
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

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/literals.pyi` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -115,14 +115,15 @@
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
@@ -201,14 +202,15 @@
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
@@ -219,14 +221,15 @@
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
@@ -262,14 +265,15 @@
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
@@ -288,16 +292,19 @@
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
@@ -381,15 +388,17 @@
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

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/paginator.py` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("translate") as client:
         client: TranslateClient
 
         list_terminologies_paginator: ListTerminologiesPaginator = client.get_paginator("list_terminologies")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListTerminologiesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListTerminologiesPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListTerminologiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Paginator.ListTerminologies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/paginators/#listterminologiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTerminologiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Paginator.ListTerminologies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/paginators/#listterminologiespaginator)
         """
```

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/paginator.pyi` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("translate") as client:
         client: TranslateClient
 
         list_terminologies_paginator: ListTerminologiesPaginator = client.get_paginator("list_terminologies")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListTerminologiesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListTerminologiesPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListTerminologiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Paginator.ListTerminologies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/paginators/#listterminologiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTerminologiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate.Paginator.ListTerminologies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/paginators/#listterminologiespaginator)
         """
```

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/type_defs.py` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -38,54 +38,58 @@
 
 
 __all__ = (
     "TermTypeDef",
     "EncryptionKeyTypeDef",
     "ParallelDataConfigTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateParallelDataResponseTypeDef",
     "DeleteParallelDataRequestRequestTypeDef",
+    "DeleteParallelDataResponseTypeDef",
     "DeleteTerminologyRequestRequestTypeDef",
     "DescribeTextTranslationJobRequestRequestTypeDef",
+    "DocumentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetParallelDataRequestRequestTypeDef",
     "ParallelDataDataLocationTypeDef",
     "GetTerminologyRequestRequestTypeDef",
     "TerminologyDataLocationTypeDef",
     "TerminologyDataTypeDef",
     "InputDataConfigTypeDef",
     "JobDetailsTypeDef",
     "LanguageTypeDef",
     "ListLanguagesRequestRequestTypeDef",
     "ListParallelDataRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
     "ListTerminologiesRequestRequestTypeDef",
     "TextTranslationJobFilterTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TranslationSettingsTypeDef",
+    "StartTextTranslationJobResponseTypeDef",
     "StopTextTranslationJobRequestRequestTypeDef",
+    "StopTextTranslationJobResponseTypeDef",
+    "TranslatedDocumentTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateParallelDataResponseTypeDef",
     "AppliedTerminologyTypeDef",
     "OutputDataConfigTypeDef",
     "TerminologyPropertiesTypeDef",
     "ParallelDataPropertiesTypeDef",
     "UpdateParallelDataRequestRequestTypeDef",
     "CreateParallelDataRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateParallelDataResponseTypeDef",
-    "DeleteParallelDataResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartTextTranslationJobResponseTypeDef",
-    "StopTextTranslationJobResponseTypeDef",
-    "UpdateParallelDataResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ImportTerminologyRequestRequestTypeDef",
     "ListLanguagesResponseTypeDef",
-    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
     "ListTextTranslationJobsRequestRequestTypeDef",
+    "TranslateDocumentRequestRequestTypeDef",
     "TranslateTextRequestRequestTypeDef",
+    "TranslateDocumentResponseTypeDef",
     "TranslateTextResponseTypeDef",
     "StartTextTranslationJobRequestRequestTypeDef",
     "TextTranslationJobPropertiesTypeDef",
     "GetTerminologyResponseTypeDef",
     "ImportTerminologyResponseTypeDef",
     "ListTerminologiesResponseTypeDef",
     "GetParallelDataResponseTypeDef",
@@ -123,46 +127,68 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateParallelDataResponseTypeDef = TypedDict(
+    "CreateParallelDataResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Name": str,
+        "Status": ParallelDataStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteParallelDataRequestRequestTypeDef = TypedDict(
     "DeleteParallelDataRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteParallelDataResponseTypeDef = TypedDict(
+    "DeleteParallelDataResponseTypeDef",
+    {
+        "Name": str,
+        "Status": ParallelDataStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTerminologyRequestRequestTypeDef = TypedDict(
     "DeleteTerminologyRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
 DescribeTextTranslationJobRequestRequestTypeDef = TypedDict(
     "DescribeTextTranslationJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DocumentTypeDef = TypedDict(
+    "DocumentTypeDef",
+    {
+        "Content": Union[str, bytes, IO[Any], StreamingBody],
+        "ContentType": str,
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetParallelDataRequestRequestTypeDef = TypedDict(
     "GetParallelDataRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -271,20 +297,18 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListTerminologiesRequestListTerminologiesPaginateTypeDef = TypedDict(
+    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTerminologiesRequestRequestTypeDef = TypedDict(
     "ListTerminologiesRequestRequestTypeDef",
     {
@@ -301,38 +325,95 @@
         "JobStatus": JobStatusType,
         "SubmittedBeforeTime": Union[datetime, str],
         "SubmittedAfterTime": Union[datetime, str],
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
 TranslationSettingsTypeDef = TypedDict(
     "TranslationSettingsTypeDef",
     {
         "Formality": FormalityType,
         "Profanity": Literal["MASK"],
     },
     total=False,
 )
 
+StartTextTranslationJobResponseTypeDef = TypedDict(
+    "StartTextTranslationJobResponseTypeDef",
+    {
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopTextTranslationJobRequestRequestTypeDef = TypedDict(
     "StopTextTranslationJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopTextTranslationJobResponseTypeDef = TypedDict(
+    "StopTextTranslationJobResponseTypeDef",
+    {
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TranslatedDocumentTypeDef = TypedDict(
+    "TranslatedDocumentTypeDef",
+    {
+        "Content": bytes,
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateParallelDataResponseTypeDef = TypedDict(
+    "UpdateParallelDataResponseTypeDef",
+    {
+        "Name": str,
+        "Status": ParallelDataStatusType,
+        "LatestUpdateAttemptStatus": ParallelDataStatusType,
+        "LatestUpdateAttemptAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppliedTerminologyTypeDef = TypedDict(
     "AppliedTerminologyTypeDef",
     {
         "Name": str,
         "Terms": List[TermTypeDef],
     },
     total=False,
@@ -448,81 +529,27 @@
 class CreateParallelDataRequestRequestTypeDef(
     _RequiredCreateParallelDataRequestRequestTypeDef,
     _OptionalCreateParallelDataRequestRequestTypeDef,
 ):
     pass
 
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateParallelDataResponseTypeDef = TypedDict(
-    "CreateParallelDataResponseTypeDef",
-    {
-        "Name": str,
-        "Status": ParallelDataStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteParallelDataResponseTypeDef = TypedDict(
-    "DeleteParallelDataResponseTypeDef",
-    {
-        "Name": str,
-        "Status": ParallelDataStatusType,
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTextTranslationJobResponseTypeDef = TypedDict(
-    "StartTextTranslationJobResponseTypeDef",
-    {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopTextTranslationJobResponseTypeDef = TypedDict(
-    "StopTextTranslationJobResponseTypeDef",
-    {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateParallelDataResponseTypeDef = TypedDict(
-    "UpdateParallelDataResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "Name": str,
-        "Status": ParallelDataStatusType,
-        "LatestUpdateAttemptStatus": ParallelDataStatusType,
-        "LatestUpdateAttemptAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredImportTerminologyRequestRequestTypeDef = TypedDict(
     "_RequiredImportTerminologyRequestRequestTypeDef",
     {
         "Name": str,
@@ -549,36 +576,52 @@
 
 ListLanguagesResponseTypeDef = TypedDict(
     "ListLanguagesResponseTypeDef",
     {
         "Languages": List[LanguageTypeDef],
         "DisplayLanguageCode": DisplayLanguageCodeType,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTerminologiesRequestListTerminologiesPaginateTypeDef = TypedDict(
-    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListTextTranslationJobsRequestRequestTypeDef = TypedDict(
     "ListTextTranslationJobsRequestRequestTypeDef",
     {
         "Filter": TextTranslationJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredTranslateDocumentRequestRequestTypeDef = TypedDict(
+    "_RequiredTranslateDocumentRequestRequestTypeDef",
+    {
+        "Document": DocumentTypeDef,
+        "SourceLanguageCode": str,
+        "TargetLanguageCode": str,
+    },
+)
+_OptionalTranslateDocumentRequestRequestTypeDef = TypedDict(
+    "_OptionalTranslateDocumentRequestRequestTypeDef",
+    {
+        "TerminologyNames": Sequence[str],
+        "Settings": TranslationSettingsTypeDef,
+    },
+    total=False,
+)
+
+
+class TranslateDocumentRequestRequestTypeDef(
+    _RequiredTranslateDocumentRequestRequestTypeDef, _OptionalTranslateDocumentRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredTranslateTextRequestRequestTypeDef = TypedDict(
     "_RequiredTranslateTextRequestRequestTypeDef",
     {
         "Text": str,
         "SourceLanguageCode": str,
         "TargetLanguageCode": str,
     },
@@ -595,23 +638,35 @@
 
 class TranslateTextRequestRequestTypeDef(
     _RequiredTranslateTextRequestRequestTypeDef, _OptionalTranslateTextRequestRequestTypeDef
 ):
     pass
 
 
+TranslateDocumentResponseTypeDef = TypedDict(
+    "TranslateDocumentResponseTypeDef",
+    {
+        "TranslatedDocument": TranslatedDocumentTypeDef,
+        "SourceLanguageCode": str,
+        "TargetLanguageCode": str,
+        "AppliedTerminologies": List[AppliedTerminologyTypeDef],
+        "AppliedSettings": TranslationSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TranslateTextResponseTypeDef = TypedDict(
     "TranslateTextResponseTypeDef",
     {
         "TranslatedText": str,
         "SourceLanguageCode": str,
         "TargetLanguageCode": str,
         "AppliedTerminologies": List[AppliedTerminologyTypeDef],
         "AppliedSettings": TranslationSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartTextTranslationJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartTextTranslationJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
@@ -665,65 +720,65 @@
 
 GetTerminologyResponseTypeDef = TypedDict(
     "GetTerminologyResponseTypeDef",
     {
         "TerminologyProperties": TerminologyPropertiesTypeDef,
         "TerminologyDataLocation": TerminologyDataLocationTypeDef,
         "AuxiliaryDataLocation": TerminologyDataLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportTerminologyResponseTypeDef = TypedDict(
     "ImportTerminologyResponseTypeDef",
     {
         "TerminologyProperties": TerminologyPropertiesTypeDef,
         "AuxiliaryDataLocation": TerminologyDataLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTerminologiesResponseTypeDef = TypedDict(
     "ListTerminologiesResponseTypeDef",
     {
         "TerminologyPropertiesList": List[TerminologyPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParallelDataResponseTypeDef = TypedDict(
     "GetParallelDataResponseTypeDef",
     {
         "ParallelDataProperties": ParallelDataPropertiesTypeDef,
         "DataLocation": ParallelDataDataLocationTypeDef,
         "AuxiliaryDataLocation": ParallelDataDataLocationTypeDef,
         "LatestUpdateAttemptAuxiliaryDataLocation": ParallelDataDataLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListParallelDataResponseTypeDef = TypedDict(
     "ListParallelDataResponseTypeDef",
     {
         "ParallelDataPropertiesList": List[ParallelDataPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTextTranslationJobResponseTypeDef = TypedDict(
     "DescribeTextTranslationJobResponseTypeDef",
     {
         "TextTranslationJobProperties": TextTranslationJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTextTranslationJobsResponseTypeDef = TypedDict(
     "ListTextTranslationJobsResponseTypeDef",
     {
         "TextTranslationJobPropertiesList": List[TextTranslationJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate/type_defs.pyi` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -37,54 +37,58 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "TermTypeDef",
     "EncryptionKeyTypeDef",
     "ParallelDataConfigTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateParallelDataResponseTypeDef",
     "DeleteParallelDataRequestRequestTypeDef",
+    "DeleteParallelDataResponseTypeDef",
     "DeleteTerminologyRequestRequestTypeDef",
     "DescribeTextTranslationJobRequestRequestTypeDef",
+    "DocumentTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetParallelDataRequestRequestTypeDef",
     "ParallelDataDataLocationTypeDef",
     "GetTerminologyRequestRequestTypeDef",
     "TerminologyDataLocationTypeDef",
     "TerminologyDataTypeDef",
     "InputDataConfigTypeDef",
     "JobDetailsTypeDef",
     "LanguageTypeDef",
     "ListLanguagesRequestRequestTypeDef",
     "ListParallelDataRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
     "ListTerminologiesRequestRequestTypeDef",
     "TextTranslationJobFilterTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TranslationSettingsTypeDef",
+    "StartTextTranslationJobResponseTypeDef",
     "StopTextTranslationJobRequestRequestTypeDef",
+    "StopTextTranslationJobResponseTypeDef",
+    "TranslatedDocumentTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateParallelDataResponseTypeDef",
     "AppliedTerminologyTypeDef",
     "OutputDataConfigTypeDef",
     "TerminologyPropertiesTypeDef",
     "ParallelDataPropertiesTypeDef",
     "UpdateParallelDataRequestRequestTypeDef",
     "CreateParallelDataRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateParallelDataResponseTypeDef",
-    "DeleteParallelDataResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartTextTranslationJobResponseTypeDef",
-    "StopTextTranslationJobResponseTypeDef",
-    "UpdateParallelDataResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "ImportTerminologyRequestRequestTypeDef",
     "ListLanguagesResponseTypeDef",
-    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
     "ListTextTranslationJobsRequestRequestTypeDef",
+    "TranslateDocumentRequestRequestTypeDef",
     "TranslateTextRequestRequestTypeDef",
+    "TranslateDocumentResponseTypeDef",
     "TranslateTextResponseTypeDef",
     "StartTextTranslationJobRequestRequestTypeDef",
     "TextTranslationJobPropertiesTypeDef",
     "GetTerminologyResponseTypeDef",
     "ImportTerminologyResponseTypeDef",
     "ListTerminologiesResponseTypeDef",
     "GetParallelDataResponseTypeDef",
@@ -122,46 +126,68 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateParallelDataResponseTypeDef = TypedDict(
+    "CreateParallelDataResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Name": str,
+        "Status": ParallelDataStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteParallelDataRequestRequestTypeDef = TypedDict(
     "DeleteParallelDataRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteParallelDataResponseTypeDef = TypedDict(
+    "DeleteParallelDataResponseTypeDef",
+    {
+        "Name": str,
+        "Status": ParallelDataStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteTerminologyRequestRequestTypeDef = TypedDict(
     "DeleteTerminologyRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
 DescribeTextTranslationJobRequestRequestTypeDef = TypedDict(
     "DescribeTextTranslationJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DocumentTypeDef = TypedDict(
+    "DocumentTypeDef",
+    {
+        "Content": Union[str, bytes, IO[Any], StreamingBody],
+        "ContentType": str,
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetParallelDataRequestRequestTypeDef = TypedDict(
     "GetParallelDataRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -266,20 +292,18 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListTerminologiesRequestListTerminologiesPaginateTypeDef = TypedDict(
+    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTerminologiesRequestRequestTypeDef = TypedDict(
     "ListTerminologiesRequestRequestTypeDef",
     {
@@ -296,38 +320,95 @@
         "JobStatus": JobStatusType,
         "SubmittedBeforeTime": Union[datetime, str],
         "SubmittedAfterTime": Union[datetime, str],
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
 TranslationSettingsTypeDef = TypedDict(
     "TranslationSettingsTypeDef",
     {
         "Formality": FormalityType,
         "Profanity": Literal["MASK"],
     },
     total=False,
 )
 
+StartTextTranslationJobResponseTypeDef = TypedDict(
+    "StartTextTranslationJobResponseTypeDef",
+    {
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopTextTranslationJobRequestRequestTypeDef = TypedDict(
     "StopTextTranslationJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+StopTextTranslationJobResponseTypeDef = TypedDict(
+    "StopTextTranslationJobResponseTypeDef",
+    {
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TranslatedDocumentTypeDef = TypedDict(
+    "TranslatedDocumentTypeDef",
+    {
+        "Content": bytes,
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateParallelDataResponseTypeDef = TypedDict(
+    "UpdateParallelDataResponseTypeDef",
+    {
+        "Name": str,
+        "Status": ParallelDataStatusType,
+        "LatestUpdateAttemptStatus": ParallelDataStatusType,
+        "LatestUpdateAttemptAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AppliedTerminologyTypeDef = TypedDict(
     "AppliedTerminologyTypeDef",
     {
         "Name": str,
         "Terms": List[TermTypeDef],
     },
     total=False,
@@ -437,81 +518,27 @@
 
 class CreateParallelDataRequestRequestTypeDef(
     _RequiredCreateParallelDataRequestRequestTypeDef,
     _OptionalCreateParallelDataRequestRequestTypeDef,
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateParallelDataResponseTypeDef = TypedDict(
-    "CreateParallelDataResponseTypeDef",
-    {
-        "Name": str,
-        "Status": ParallelDataStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteParallelDataResponseTypeDef = TypedDict(
-    "DeleteParallelDataResponseTypeDef",
-    {
-        "Name": str,
-        "Status": ParallelDataStatusType,
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
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTextTranslationJobResponseTypeDef = TypedDict(
-    "StartTextTranslationJobResponseTypeDef",
-    {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopTextTranslationJobResponseTypeDef = TypedDict(
-    "StopTextTranslationJobResponseTypeDef",
-    {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateParallelDataResponseTypeDef = TypedDict(
-    "UpdateParallelDataResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "Name": str,
-        "Status": ParallelDataStatusType,
-        "LatestUpdateAttemptStatus": ParallelDataStatusType,
-        "LatestUpdateAttemptAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredImportTerminologyRequestRequestTypeDef = TypedDict(
     "_RequiredImportTerminologyRequestRequestTypeDef",
     {
         "Name": str,
@@ -536,36 +563,50 @@
 
 ListLanguagesResponseTypeDef = TypedDict(
     "ListLanguagesResponseTypeDef",
     {
         "Languages": List[LanguageTypeDef],
         "DisplayLanguageCode": DisplayLanguageCodeType,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTerminologiesRequestListTerminologiesPaginateTypeDef = TypedDict(
-    "ListTerminologiesRequestListTerminologiesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 ListTextTranslationJobsRequestRequestTypeDef = TypedDict(
     "ListTextTranslationJobsRequestRequestTypeDef",
     {
         "Filter": TextTranslationJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredTranslateDocumentRequestRequestTypeDef = TypedDict(
+    "_RequiredTranslateDocumentRequestRequestTypeDef",
+    {
+        "Document": DocumentTypeDef,
+        "SourceLanguageCode": str,
+        "TargetLanguageCode": str,
+    },
+)
+_OptionalTranslateDocumentRequestRequestTypeDef = TypedDict(
+    "_OptionalTranslateDocumentRequestRequestTypeDef",
+    {
+        "TerminologyNames": Sequence[str],
+        "Settings": TranslationSettingsTypeDef,
+    },
+    total=False,
+)
+
+class TranslateDocumentRequestRequestTypeDef(
+    _RequiredTranslateDocumentRequestRequestTypeDef, _OptionalTranslateDocumentRequestRequestTypeDef
+):
+    pass
+
 _RequiredTranslateTextRequestRequestTypeDef = TypedDict(
     "_RequiredTranslateTextRequestRequestTypeDef",
     {
         "Text": str,
         "SourceLanguageCode": str,
         "TargetLanguageCode": str,
     },
@@ -580,23 +621,35 @@
 )
 
 class TranslateTextRequestRequestTypeDef(
     _RequiredTranslateTextRequestRequestTypeDef, _OptionalTranslateTextRequestRequestTypeDef
 ):
     pass
 
+TranslateDocumentResponseTypeDef = TypedDict(
+    "TranslateDocumentResponseTypeDef",
+    {
+        "TranslatedDocument": TranslatedDocumentTypeDef,
+        "SourceLanguageCode": str,
+        "TargetLanguageCode": str,
+        "AppliedTerminologies": List[AppliedTerminologyTypeDef],
+        "AppliedSettings": TranslationSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TranslateTextResponseTypeDef = TypedDict(
     "TranslateTextResponseTypeDef",
     {
         "TranslatedText": str,
         "SourceLanguageCode": str,
         "TargetLanguageCode": str,
         "AppliedTerminologies": List[AppliedTerminologyTypeDef],
         "AppliedSettings": TranslationSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartTextTranslationJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartTextTranslationJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
@@ -648,65 +701,65 @@
 
 GetTerminologyResponseTypeDef = TypedDict(
     "GetTerminologyResponseTypeDef",
     {
         "TerminologyProperties": TerminologyPropertiesTypeDef,
         "TerminologyDataLocation": TerminologyDataLocationTypeDef,
         "AuxiliaryDataLocation": TerminologyDataLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportTerminologyResponseTypeDef = TypedDict(
     "ImportTerminologyResponseTypeDef",
     {
         "TerminologyProperties": TerminologyPropertiesTypeDef,
         "AuxiliaryDataLocation": TerminologyDataLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTerminologiesResponseTypeDef = TypedDict(
     "ListTerminologiesResponseTypeDef",
     {
         "TerminologyPropertiesList": List[TerminologyPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetParallelDataResponseTypeDef = TypedDict(
     "GetParallelDataResponseTypeDef",
     {
         "ParallelDataProperties": ParallelDataPropertiesTypeDef,
         "DataLocation": ParallelDataDataLocationTypeDef,
         "AuxiliaryDataLocation": ParallelDataDataLocationTypeDef,
         "LatestUpdateAttemptAuxiliaryDataLocation": ParallelDataDataLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListParallelDataResponseTypeDef = TypedDict(
     "ListParallelDataResponseTypeDef",
     {
         "ParallelDataPropertiesList": List[ParallelDataPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTextTranslationJobResponseTypeDef = TypedDict(
     "DescribeTextTranslationJobResponseTypeDef",
     {
         "TextTranslationJobProperties": TextTranslationJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTextTranslationJobsResponseTypeDef = TypedDict(
     "ListTextTranslationJobsResponseTypeDef",
     {
         "TextTranslationJobPropertiesList": List[TextTranslationJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/PKG-INFO` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-translate
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Translate 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Translate 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-translate"></a>
 
 # types-aiobotocore-translate
 
 [![PyPI - types-aiobotocore-translate](https://img.shields.io/pypi/v/types-aiobotocore-translate.svg?color=blue)](https://pypi.org/project/types-aiobotocore-translate)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-translate.svg?color=blue)](https://pypi.org/project/types-aiobotocore-translate)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-translate?color=blue)](https://pypistats.org/packages/types-aiobotocore-translate)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Translate 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate)
+[aiobotocore.Translate 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/translate.html#Translate)
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
 [types-aiobotocore-translate docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/).
 
 See how it helps to find and fix potential bugs:
 
@@ -330,54 +330,58 @@
 
 ```python
 from types_aiobotocore_translate.type_defs import (
     TermTypeDef,
     EncryptionKeyTypeDef,
     ParallelDataConfigTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateParallelDataResponseTypeDef,
     DeleteParallelDataRequestRequestTypeDef,
+    DeleteParallelDataResponseTypeDef,
     DeleteTerminologyRequestRequestTypeDef,
     DescribeTextTranslationJobRequestRequestTypeDef,
+    DocumentTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetParallelDataRequestRequestTypeDef,
     ParallelDataDataLocationTypeDef,
     GetTerminologyRequestRequestTypeDef,
     TerminologyDataLocationTypeDef,
     TerminologyDataTypeDef,
     InputDataConfigTypeDef,
     JobDetailsTypeDef,
     LanguageTypeDef,
     ListLanguagesRequestRequestTypeDef,
     ListParallelDataRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListTerminologiesRequestListTerminologiesPaginateTypeDef,
     ListTerminologiesRequestRequestTypeDef,
     TextTranslationJobFilterTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TranslationSettingsTypeDef,
+    StartTextTranslationJobResponseTypeDef,
     StopTextTranslationJobRequestRequestTypeDef,
+    StopTextTranslationJobResponseTypeDef,
+    TranslatedDocumentTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateParallelDataResponseTypeDef,
     AppliedTerminologyTypeDef,
     OutputDataConfigTypeDef,
     TerminologyPropertiesTypeDef,
     ParallelDataPropertiesTypeDef,
     UpdateParallelDataRequestRequestTypeDef,
     CreateParallelDataRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateParallelDataResponseTypeDef,
-    DeleteParallelDataResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartTextTranslationJobResponseTypeDef,
-    StopTextTranslationJobResponseTypeDef,
-    UpdateParallelDataResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     ImportTerminologyRequestRequestTypeDef,
     ListLanguagesResponseTypeDef,
-    ListTerminologiesRequestListTerminologiesPaginateTypeDef,
     ListTextTranslationJobsRequestRequestTypeDef,
+    TranslateDocumentRequestRequestTypeDef,
     TranslateTextRequestRequestTypeDef,
+    TranslateDocumentResponseTypeDef,
     TranslateTextResponseTypeDef,
     StartTextTranslationJobRequestRequestTypeDef,
     TextTranslationJobPropertiesTypeDef,
     GetTerminologyResponseTypeDef,
     ImportTerminologyResponseTypeDef,
     ListTerminologiesResponseTypeDef,
     GetParallelDataResponseTypeDef,
@@ -394,43 +398,43 @@
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

### Comparing `types-aiobotocore-translate-2.5.0.post1/types_aiobotocore_translate.egg-info/SOURCES.txt` & `types-aiobotocore-translate-2.5.1/types_aiobotocore_translate.egg-info/SOURCES.txt`

 * *Files identical despite different names*

