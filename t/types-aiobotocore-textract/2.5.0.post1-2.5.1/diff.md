# Comparing `tmp/types-aiobotocore-textract-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-textract-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-textract-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:26 2023, max compression
+gzip compressed data, was "types-aiobotocore-textract-2.5.1.tar", last modified: Wed Jun 28 01:44:16 2023, max compression
```

## Comparing `types-aiobotocore-textract-2.5.0.post1.tar` & `types-aiobotocore-textract-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:26.135682 types-aiobotocore-textract-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14538 2023-03-11 12:27:26.131682 types-aiobotocore-textract-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12963 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:26.135682 types-aiobotocore-textract-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:26.127682 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/
--rw-r--r--   0 runner    (1001) docker     (123)      450 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14110 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14089 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8571 2023-03-11 12:25:03.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8569 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    22941 2023-03-11 12:25:04.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    22914 2023-03-11 12:25:04.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:00.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:26.131682 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14538 2023-03-11 12:27:25.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:27:25.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:25.000000 types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.758225 types-aiobotocore-textract-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14531 2023-06-28 01:44:16.758225 types-aiobotocore-textract-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12962 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:16.758225 types-aiobotocore-textract-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.758225 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/
+-rw-r--r--   0 runner    (1001) docker     (123)      450 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14110 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14089 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9047 2023-06-28 01:41:52.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9045 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    22967 2023-06-28 01:41:52.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22940 2023-06-28 01:41:52.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:51.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.758225 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14531 2023-06-28 01:44:16.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:44:16.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:16.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:16.000000 types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-textract-2.5.0.post1/LICENSE` & `types-aiobotocore-textract-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-textract-2.5.0.post1/PKG-INFO` & `types-aiobotocore-textract-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-textract
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Textract 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Textract 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-textract"></a>
 
 # types-aiobotocore-textract
 
 [![PyPI - types-aiobotocore-textract](https://img.shields.io/pypi/v/types-aiobotocore-textract.svg?color=blue)](https://pypi.org/project/types-aiobotocore-textract)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-textract.svg?color=blue)](https://pypi.org/project/types-aiobotocore-textract)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-textract?color=blue)](https://pypistats.org/packages/types-aiobotocore-textract)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Textract 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract)
+[aiobotocore.Textract 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract)
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
 [types-aiobotocore-textract docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,15 +299,14 @@
 `types_aiobotocore_textract.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_textract.type_defs import (
     DocumentMetadataTypeDef,
     HumanLoopActivationOutputTypeDef,
-    ResponseMetadataTypeDef,
     NormalizedValueTypeDef,
     QueryTypeDef,
     RelationshipTypeDef,
     BoundingBoxTypeDef,
     DetectedSignatureTypeDef,
     SplitDocumentTypeDef,
     UndetectedSignatureTypeDef,
@@ -322,14 +321,15 @@
     GetExpenseAnalysisRequestRequestTypeDef,
     GetLendingAnalysisRequestRequestTypeDef,
     GetLendingAnalysisSummaryRequestRequestTypeDef,
     HumanLoopDataAttributesTypeDef,
     NotificationChannelTypeDef,
     OutputConfigTypeDef,
     PredictionTypeDef,
+    ResponseMetadataTypeDef,
     StartDocumentAnalysisResponseTypeDef,
     StartDocumentTextDetectionResponseTypeDef,
     StartExpenseAnalysisResponseTypeDef,
     StartLendingAnalysisResponseTypeDef,
     AnalyzeIDDetectionsTypeDef,
     QueriesConfigTypeDef,
     DocumentGroupTypeDef,
@@ -380,43 +380,43 @@
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

### Comparing `types-aiobotocore-textract-2.5.0.post1/README.md` & `types-aiobotocore-textract-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-textract"></a>
 
 # types-aiobotocore-textract
 
 [![PyPI - types-aiobotocore-textract](https://img.shields.io/pypi/v/types-aiobotocore-textract.svg?color=blue)](https://pypi.org/project/types-aiobotocore-textract)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-textract.svg?color=blue)](https://pypi.org/project/types-aiobotocore-textract)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-textract?color=blue)](https://pypistats.org/packages/types-aiobotocore-textract)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Textract 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract)
+[aiobotocore.Textract 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract)
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
 [types-aiobotocore-textract docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/).
 
 See how it helps to find and fix potential bugs:
 
@@ -266,15 +266,14 @@
 `types_aiobotocore_textract.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_textract.type_defs import (
     DocumentMetadataTypeDef,
     HumanLoopActivationOutputTypeDef,
-    ResponseMetadataTypeDef,
     NormalizedValueTypeDef,
     QueryTypeDef,
     RelationshipTypeDef,
     BoundingBoxTypeDef,
     DetectedSignatureTypeDef,
     SplitDocumentTypeDef,
     UndetectedSignatureTypeDef,
@@ -289,14 +288,15 @@
     GetExpenseAnalysisRequestRequestTypeDef,
     GetLendingAnalysisRequestRequestTypeDef,
     GetLendingAnalysisSummaryRequestRequestTypeDef,
     HumanLoopDataAttributesTypeDef,
     NotificationChannelTypeDef,
     OutputConfigTypeDef,
     PredictionTypeDef,
+    ResponseMetadataTypeDef,
     StartDocumentAnalysisResponseTypeDef,
     StartDocumentTextDetectionResponseTypeDef,
     StartExpenseAnalysisResponseTypeDef,
     StartLendingAnalysisResponseTypeDef,
     AnalyzeIDDetectionsTypeDef,
     QueriesConfigTypeDef,
     DocumentGroupTypeDef,
@@ -347,43 +347,43 @@
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

### Comparing `types-aiobotocore-textract-2.5.0.post1/setup.py` & `types-aiobotocore-textract-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-textract.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-textract",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_textract"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Textract 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Textract 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/"
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

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/__main__.py` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Textract 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Textract 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract\nOther"
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

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/client.py` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/client.pyi` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/literals.py` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/literals.py`

 * *Files 6% similar despite different names*

```diff
@@ -43,23 +43,43 @@
     "MERGED_CELL",
     "PAGE",
     "QUERY",
     "QUERY_RESULT",
     "SELECTION_ELEMENT",
     "SIGNATURE",
     "TABLE",
+    "TABLE_FOOTER",
+    "TABLE_TITLE",
     "TITLE",
     "WORD",
 ]
 ContentClassifierType = Literal["FreeOfAdultContent", "FreeOfPersonallyIdentifiableInformation"]
-EntityTypeType = Literal["COLUMN_HEADER", "KEY", "VALUE"]
+EntityTypeType = Literal[
+    "COLUMN_HEADER",
+    "KEY",
+    "SEMI_STRUCTURED_TABLE",
+    "STRUCTURED_TABLE",
+    "TABLE_FOOTER",
+    "TABLE_SECTION_TITLE",
+    "TABLE_SUMMARY",
+    "TABLE_TITLE",
+    "VALUE",
+]
 FeatureTypeType = Literal["FORMS", "QUERIES", "SIGNATURES", "TABLES"]
 JobStatusType = Literal["FAILED", "IN_PROGRESS", "PARTIAL_SUCCESS", "SUCCEEDED"]
 RelationshipTypeType = Literal[
-    "ANSWER", "CHILD", "COMPLEX_FEATURES", "MERGED_CELL", "TITLE", "VALUE"
+    "ANSWER",
+    "CHILD",
+    "COMPLEX_FEATURES",
+    "MERGED_CELL",
+    "TABLE",
+    "TABLE_FOOTER",
+    "TABLE_TITLE",
+    "TITLE",
+    "VALUE",
 ]
 SelectionStatusType = Literal["NOT_SELECTED", "SELECTED"]
 TextTypeType = Literal["HANDWRITING", "PRINTED"]
 ValueTypeType = Literal["DATE"]
 TextractServiceName = Literal["textract"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -119,14 +139,15 @@
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
@@ -205,14 +226,15 @@
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
@@ -223,14 +245,15 @@
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
@@ -266,14 +289,15 @@
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
@@ -292,16 +316,19 @@
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
@@ -385,15 +412,17 @@
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

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/literals.pyi` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/literals.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -41,23 +41,43 @@
     "MERGED_CELL",
     "PAGE",
     "QUERY",
     "QUERY_RESULT",
     "SELECTION_ELEMENT",
     "SIGNATURE",
     "TABLE",
+    "TABLE_FOOTER",
+    "TABLE_TITLE",
     "TITLE",
     "WORD",
 ]
 ContentClassifierType = Literal["FreeOfAdultContent", "FreeOfPersonallyIdentifiableInformation"]
-EntityTypeType = Literal["COLUMN_HEADER", "KEY", "VALUE"]
+EntityTypeType = Literal[
+    "COLUMN_HEADER",
+    "KEY",
+    "SEMI_STRUCTURED_TABLE",
+    "STRUCTURED_TABLE",
+    "TABLE_FOOTER",
+    "TABLE_SECTION_TITLE",
+    "TABLE_SUMMARY",
+    "TABLE_TITLE",
+    "VALUE",
+]
 FeatureTypeType = Literal["FORMS", "QUERIES", "SIGNATURES", "TABLES"]
 JobStatusType = Literal["FAILED", "IN_PROGRESS", "PARTIAL_SUCCESS", "SUCCEEDED"]
 RelationshipTypeType = Literal[
-    "ANSWER", "CHILD", "COMPLEX_FEATURES", "MERGED_CELL", "TITLE", "VALUE"
+    "ANSWER",
+    "CHILD",
+    "COMPLEX_FEATURES",
+    "MERGED_CELL",
+    "TABLE",
+    "TABLE_FOOTER",
+    "TABLE_TITLE",
+    "TITLE",
+    "VALUE",
 ]
 SelectionStatusType = Literal["NOT_SELECTED", "SELECTED"]
 TextTypeType = Literal["HANDWRITING", "PRINTED"]
 ValueTypeType = Literal["DATE"]
 TextractServiceName = Literal["textract"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -117,14 +137,15 @@
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
@@ -203,14 +224,15 @@
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
@@ -221,14 +243,15 @@
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
@@ -264,14 +287,15 @@
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
@@ -290,16 +314,19 @@
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
@@ -383,15 +410,17 @@
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

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/type_defs.py` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -36,15 +36,14 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DocumentMetadataTypeDef",
     "HumanLoopActivationOutputTypeDef",
-    "ResponseMetadataTypeDef",
     "NormalizedValueTypeDef",
     "QueryTypeDef",
     "RelationshipTypeDef",
     "BoundingBoxTypeDef",
     "DetectedSignatureTypeDef",
     "SplitDocumentTypeDef",
     "UndetectedSignatureTypeDef",
@@ -59,14 +58,15 @@
     "GetExpenseAnalysisRequestRequestTypeDef",
     "GetLendingAnalysisRequestRequestTypeDef",
     "GetLendingAnalysisSummaryRequestRequestTypeDef",
     "HumanLoopDataAttributesTypeDef",
     "NotificationChannelTypeDef",
     "OutputConfigTypeDef",
     "PredictionTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDocumentAnalysisResponseTypeDef",
     "StartDocumentTextDetectionResponseTypeDef",
     "StartExpenseAnalysisResponseTypeDef",
     "StartLendingAnalysisResponseTypeDef",
     "AnalyzeIDDetectionsTypeDef",
     "QueriesConfigTypeDef",
     "DocumentGroupTypeDef",
@@ -123,25 +123,14 @@
         "HumanLoopArn": str,
         "HumanLoopActivationReasons": List[str],
         "HumanLoopActivationConditionsEvaluationResults": str,
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
 NormalizedValueTypeDef = TypedDict(
     "NormalizedValueTypeDef",
     {
         "Value": str,
         "ValueType": Literal["DATE"],
     },
     total=False,
@@ -406,43 +395,54 @@
     {
         "Value": str,
         "Confidence": float,
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
 StartDocumentAnalysisResponseTypeDef = TypedDict(
     "StartDocumentAnalysisResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDocumentTextDetectionResponseTypeDef = TypedDict(
     "StartDocumentTextDetectionResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartExpenseAnalysisResponseTypeDef = TypedDict(
     "StartExpenseAnalysisResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartLendingAnalysisResponseTypeDef = TypedDict(
     "StartLendingAnalysisResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAnalyzeIDDetectionsTypeDef = TypedDict(
     "_RequiredAnalyzeIDDetectionsTypeDef",
     {
         "Text": str,
@@ -761,64 +761,64 @@
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "Summary": LendingSummaryTypeDef,
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeLendingModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnalyzeDocumentResponseTypeDef = TypedDict(
     "AnalyzeDocumentResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "Blocks": List[BlockTypeDef],
         "HumanLoopActivationOutput": HumanLoopActivationOutputTypeDef,
         "AnalyzeDocumentModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectDocumentTextResponseTypeDef = TypedDict(
     "DetectDocumentTextResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "Blocks": List[BlockTypeDef],
         "DetectDocumentTextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentAnalysisResponseTypeDef = TypedDict(
     "GetDocumentAnalysisResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "Blocks": List[BlockTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeDocumentModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentTextDetectionResponseTypeDef = TypedDict(
     "GetDocumentTextDetectionResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "Blocks": List[BlockTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "DetectDocumentTextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IdentityDocumentTypeDef = TypedDict(
     "IdentityDocumentTypeDef",
     {
         "DocumentIndex": int,
@@ -853,15 +853,15 @@
 
 AnalyzeIDResponseTypeDef = TypedDict(
     "AnalyzeIDResponseTypeDef",
     {
         "IdentityDocuments": List[IdentityDocumentTypeDef],
         "DocumentMetadata": DocumentMetadataTypeDef,
         "AnalyzeIDModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LineItemFieldsTypeDef = TypedDict(
     "LineItemFieldsTypeDef",
     {
         "LineItemExpenseFields": List[ExpenseFieldTypeDef],
@@ -899,15 +899,15 @@
 )
 
 AnalyzeExpenseResponseTypeDef = TypedDict(
     "AnalyzeExpenseResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "ExpenseDocuments": List[ExpenseDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExtractionTypeDef = TypedDict(
     "ExtractionTypeDef",
     {
         "LendingDocument": LendingDocumentTypeDef,
@@ -923,15 +923,15 @@
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "ExpenseDocuments": List[ExpenseDocumentTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeExpenseModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LendingResultTypeDef = TypedDict(
     "LendingResultTypeDef",
     {
         "Page": int,
@@ -947,10 +947,10 @@
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "Results": List[LendingResultTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeLendingModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract/type_defs.pyi` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -35,15 +35,14 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DocumentMetadataTypeDef",
     "HumanLoopActivationOutputTypeDef",
-    "ResponseMetadataTypeDef",
     "NormalizedValueTypeDef",
     "QueryTypeDef",
     "RelationshipTypeDef",
     "BoundingBoxTypeDef",
     "DetectedSignatureTypeDef",
     "SplitDocumentTypeDef",
     "UndetectedSignatureTypeDef",
@@ -58,14 +57,15 @@
     "GetExpenseAnalysisRequestRequestTypeDef",
     "GetLendingAnalysisRequestRequestTypeDef",
     "GetLendingAnalysisSummaryRequestRequestTypeDef",
     "HumanLoopDataAttributesTypeDef",
     "NotificationChannelTypeDef",
     "OutputConfigTypeDef",
     "PredictionTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDocumentAnalysisResponseTypeDef",
     "StartDocumentTextDetectionResponseTypeDef",
     "StartExpenseAnalysisResponseTypeDef",
     "StartLendingAnalysisResponseTypeDef",
     "AnalyzeIDDetectionsTypeDef",
     "QueriesConfigTypeDef",
     "DocumentGroupTypeDef",
@@ -122,25 +122,14 @@
         "HumanLoopArn": str,
         "HumanLoopActivationReasons": List[str],
         "HumanLoopActivationConditionsEvaluationResults": str,
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
 NormalizedValueTypeDef = TypedDict(
     "NormalizedValueTypeDef",
     {
         "Value": str,
         "ValueType": Literal["DATE"],
     },
     total=False,
@@ -393,43 +382,54 @@
     {
         "Value": str,
         "Confidence": float,
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
 StartDocumentAnalysisResponseTypeDef = TypedDict(
     "StartDocumentAnalysisResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartDocumentTextDetectionResponseTypeDef = TypedDict(
     "StartDocumentTextDetectionResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartExpenseAnalysisResponseTypeDef = TypedDict(
     "StartExpenseAnalysisResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartLendingAnalysisResponseTypeDef = TypedDict(
     "StartLendingAnalysisResponseTypeDef",
     {
         "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAnalyzeIDDetectionsTypeDef = TypedDict(
     "_RequiredAnalyzeIDDetectionsTypeDef",
     {
         "Text": str,
@@ -734,64 +734,64 @@
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "Summary": LendingSummaryTypeDef,
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeLendingModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AnalyzeDocumentResponseTypeDef = TypedDict(
     "AnalyzeDocumentResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "Blocks": List[BlockTypeDef],
         "HumanLoopActivationOutput": HumanLoopActivationOutputTypeDef,
         "AnalyzeDocumentModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectDocumentTextResponseTypeDef = TypedDict(
     "DetectDocumentTextResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "Blocks": List[BlockTypeDef],
         "DetectDocumentTextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentAnalysisResponseTypeDef = TypedDict(
     "GetDocumentAnalysisResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "Blocks": List[BlockTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeDocumentModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDocumentTextDetectionResponseTypeDef = TypedDict(
     "GetDocumentTextDetectionResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "Blocks": List[BlockTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "DetectDocumentTextModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IdentityDocumentTypeDef = TypedDict(
     "IdentityDocumentTypeDef",
     {
         "DocumentIndex": int,
@@ -826,15 +826,15 @@
 
 AnalyzeIDResponseTypeDef = TypedDict(
     "AnalyzeIDResponseTypeDef",
     {
         "IdentityDocuments": List[IdentityDocumentTypeDef],
         "DocumentMetadata": DocumentMetadataTypeDef,
         "AnalyzeIDModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LineItemFieldsTypeDef = TypedDict(
     "LineItemFieldsTypeDef",
     {
         "LineItemExpenseFields": List[ExpenseFieldTypeDef],
@@ -872,15 +872,15 @@
 )
 
 AnalyzeExpenseResponseTypeDef = TypedDict(
     "AnalyzeExpenseResponseTypeDef",
     {
         "DocumentMetadata": DocumentMetadataTypeDef,
         "ExpenseDocuments": List[ExpenseDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExtractionTypeDef = TypedDict(
     "ExtractionTypeDef",
     {
         "LendingDocument": LendingDocumentTypeDef,
@@ -896,15 +896,15 @@
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "ExpenseDocuments": List[ExpenseDocumentTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeExpenseModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LendingResultTypeDef = TypedDict(
     "LendingResultTypeDef",
     {
         "Page": int,
@@ -920,10 +920,10 @@
         "DocumentMetadata": DocumentMetadataTypeDef,
         "JobStatus": JobStatusType,
         "NextToken": str,
         "Results": List[LendingResultTypeDef],
         "Warnings": List[WarningTypeDef],
         "StatusMessage": str,
         "AnalyzeLendingModelVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/PKG-INFO` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-textract
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Textract 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Textract 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-textract"></a>
 
 # types-aiobotocore-textract
 
 [![PyPI - types-aiobotocore-textract](https://img.shields.io/pypi/v/types-aiobotocore-textract.svg?color=blue)](https://pypi.org/project/types-aiobotocore-textract)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-textract.svg?color=blue)](https://pypi.org/project/types-aiobotocore-textract)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-textract?color=blue)](https://pypistats.org/packages/types-aiobotocore-textract)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Textract 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract)
+[aiobotocore.Textract 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/textract.html#Textract)
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
 [types-aiobotocore-textract docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_textract/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,15 +299,14 @@
 `types_aiobotocore_textract.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_textract.type_defs import (
     DocumentMetadataTypeDef,
     HumanLoopActivationOutputTypeDef,
-    ResponseMetadataTypeDef,
     NormalizedValueTypeDef,
     QueryTypeDef,
     RelationshipTypeDef,
     BoundingBoxTypeDef,
     DetectedSignatureTypeDef,
     SplitDocumentTypeDef,
     UndetectedSignatureTypeDef,
@@ -322,14 +321,15 @@
     GetExpenseAnalysisRequestRequestTypeDef,
     GetLendingAnalysisRequestRequestTypeDef,
     GetLendingAnalysisSummaryRequestRequestTypeDef,
     HumanLoopDataAttributesTypeDef,
     NotificationChannelTypeDef,
     OutputConfigTypeDef,
     PredictionTypeDef,
+    ResponseMetadataTypeDef,
     StartDocumentAnalysisResponseTypeDef,
     StartDocumentTextDetectionResponseTypeDef,
     StartExpenseAnalysisResponseTypeDef,
     StartLendingAnalysisResponseTypeDef,
     AnalyzeIDDetectionsTypeDef,
     QueriesConfigTypeDef,
     DocumentGroupTypeDef,
@@ -380,43 +380,43 @@
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

### Comparing `types-aiobotocore-textract-2.5.0.post1/types_aiobotocore_textract.egg-info/SOURCES.txt` & `types-aiobotocore-textract-2.5.1/types_aiobotocore_textract.egg-info/SOURCES.txt`

 * *Files identical despite different names*

