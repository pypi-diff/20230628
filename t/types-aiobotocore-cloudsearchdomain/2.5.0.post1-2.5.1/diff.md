# Comparing `tmp/types-aiobotocore-cloudsearchdomain-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudsearchdomain-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudsearchdomain-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:21 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudsearchdomain-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1.tar` & `types-aiobotocore-cloudsearchdomain-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:21.443039 types-aiobotocore-cloudsearchdomain-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12993 2023-03-11 12:26:21.443039 types-aiobotocore-cloudsearchdomain-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11382 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:21.443039 types-aiobotocore-cloudsearchdomain-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:21.443039 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/
--rw-r--r--   0 runner    (1001) docker     (123)      522 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      521 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      983 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6423 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6412 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7555 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7553 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5194 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5189 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:58.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:21.443039 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12993 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:21.000000 types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.530107 types-aiobotocore-cloudsearchdomain-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12995 2023-06-28 01:43:13.526107 types-aiobotocore-cloudsearchdomain-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11390 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.530107 types-aiobotocore-cloudsearchdomain-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2204 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.526107 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/
+-rw-r--r--   0 runner    (1001) docker     (123)      522 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      521 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      971 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6423 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6412 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7764 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7762 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5200 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5195 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:35.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.526107 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12995 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:13.000000 types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudsearchdomain-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudsearchdomain-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudsearchdomain
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudSearchDomain 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudSearchDomain 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudsearchdomain"></a>
 
 # types-aiobotocore-cloudsearchdomain
 
 [![PyPI - types-aiobotocore-cloudsearchdomain](https://img.shields.io/pypi/v/types-aiobotocore-cloudsearchdomain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearchdomain)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudsearchdomain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearchdomain)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudsearchdomain?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudsearchdomain)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudSearchDomain 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearchdomain.html#CloudSearchDomain)
+[aiobotocore.CloudSearchDomain 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearchdomain.html#CloudSearchDomain)
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
 [types-aiobotocore-cloudsearchdomain docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/).
 
 See how it helps to find and fix potential bugs:
 
@@ -302,16 +302,16 @@
     SearchRequestRequestTypeDef,
     SearchStatusTypeDef,
     SuggestionMatchTypeDef,
     SuggestRequestRequestTypeDef,
     SuggestStatusTypeDef,
     UploadDocumentsRequestRequestTypeDef,
     BucketInfoTypeDef,
-    HitsTypeDef,
     UploadDocumentsResponseTypeDef,
+    HitsTypeDef,
     SuggestModelTypeDef,
     SearchResponseTypeDef,
     SuggestResponseTypeDef,
 )
 
 
 def get_structure() -> BucketTypeDef:
@@ -321,43 +321,43 @@
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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/README.md` & `types-aiobotocore-cloudsearchdomain-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudsearchdomain"></a>
 
 # types-aiobotocore-cloudsearchdomain
 
 [![PyPI - types-aiobotocore-cloudsearchdomain](https://img.shields.io/pypi/v/types-aiobotocore-cloudsearchdomain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearchdomain)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudsearchdomain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearchdomain)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudsearchdomain?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudsearchdomain)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudSearchDomain 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearchdomain.html#CloudSearchDomain)
+[aiobotocore.CloudSearchDomain 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearchdomain.html#CloudSearchDomain)
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
 [types-aiobotocore-cloudsearchdomain docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,16 +269,16 @@
     SearchRequestRequestTypeDef,
     SearchStatusTypeDef,
     SuggestionMatchTypeDef,
     SuggestRequestRequestTypeDef,
     SuggestStatusTypeDef,
     UploadDocumentsRequestRequestTypeDef,
     BucketInfoTypeDef,
-    HitsTypeDef,
     UploadDocumentsResponseTypeDef,
+    HitsTypeDef,
     SuggestModelTypeDef,
     SearchResponseTypeDef,
     SuggestResponseTypeDef,
 )
 
 
 def get_structure() -> BucketTypeDef:
@@ -288,43 +288,43 @@
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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/setup.py` & `types-aiobotocore-cloudsearchdomain-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudsearchdomain.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudsearchdomain",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudsearchdomain"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudSearchDomain 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudSearchDomain 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/"
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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/__init__.py` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/__init__.pyi` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/__main__.py` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudSearchDomain 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudSearchDomain 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearchdomain.html#CloudSearchDomain\nOther"
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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/client.py` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/client.pyi` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/literals.py` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/literals.py`

 * *Files 7% similar despite different names*

```diff
@@ -89,14 +89,15 @@
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
@@ -175,14 +176,15 @@
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
@@ -193,14 +195,15 @@
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
@@ -236,14 +239,15 @@
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
@@ -262,16 +266,19 @@
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
@@ -355,15 +362,17 @@
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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/literals.pyi` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/literals.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -87,14 +87,15 @@
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
@@ -173,14 +174,15 @@
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
@@ -191,14 +193,15 @@
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
@@ -234,14 +237,15 @@
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
@@ -260,16 +264,19 @@
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
@@ -353,15 +360,17 @@
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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/type_defs.py` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -33,16 +33,16 @@
     "SearchRequestRequestTypeDef",
     "SearchStatusTypeDef",
     "SuggestionMatchTypeDef",
     "SuggestRequestRequestTypeDef",
     "SuggestStatusTypeDef",
     "UploadDocumentsRequestRequestTypeDef",
     "BucketInfoTypeDef",
-    "HitsTypeDef",
     "UploadDocumentsResponseTypeDef",
+    "HitsTypeDef",
     "SuggestModelTypeDef",
     "SearchResponseTypeDef",
     "SuggestResponseTypeDef",
 )
 
 BucketTypeDef = TypedDict(
     "BucketTypeDef",
@@ -193,36 +193,36 @@
     "BucketInfoTypeDef",
     {
         "buckets": List[BucketTypeDef],
     },
     total=False,
 )
 
+UploadDocumentsResponseTypeDef = TypedDict(
+    "UploadDocumentsResponseTypeDef",
+    {
+        "status": str,
+        "adds": int,
+        "deletes": int,
+        "warnings": List[DocumentServiceWarningTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HitsTypeDef = TypedDict(
     "HitsTypeDef",
     {
         "found": int,
         "start": int,
         "cursor": str,
         "hit": List[HitTypeDef],
     },
     total=False,
 )
 
-UploadDocumentsResponseTypeDef = TypedDict(
-    "UploadDocumentsResponseTypeDef",
-    {
-        "status": str,
-        "adds": int,
-        "deletes": int,
-        "warnings": List[DocumentServiceWarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 SuggestModelTypeDef = TypedDict(
     "SuggestModelTypeDef",
     {
         "query": str,
         "found": int,
         "suggestions": List[SuggestionMatchTypeDef],
     },
@@ -232,19 +232,19 @@
 SearchResponseTypeDef = TypedDict(
     "SearchResponseTypeDef",
     {
         "status": SearchStatusTypeDef,
         "hits": HitsTypeDef,
         "facets": Dict[str, BucketInfoTypeDef],
         "stats": Dict[str, FieldStatsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SuggestResponseTypeDef = TypedDict(
     "SuggestResponseTypeDef",
     {
         "status": SuggestStatusTypeDef,
         "suggest": SuggestModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain/type_defs.pyi` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -32,16 +32,16 @@
     "SearchRequestRequestTypeDef",
     "SearchStatusTypeDef",
     "SuggestionMatchTypeDef",
     "SuggestRequestRequestTypeDef",
     "SuggestStatusTypeDef",
     "UploadDocumentsRequestRequestTypeDef",
     "BucketInfoTypeDef",
-    "HitsTypeDef",
     "UploadDocumentsResponseTypeDef",
+    "HitsTypeDef",
     "SuggestModelTypeDef",
     "SearchResponseTypeDef",
     "SuggestResponseTypeDef",
 )
 
 BucketTypeDef = TypedDict(
     "BucketTypeDef",
@@ -188,36 +188,36 @@
     "BucketInfoTypeDef",
     {
         "buckets": List[BucketTypeDef],
     },
     total=False,
 )
 
+UploadDocumentsResponseTypeDef = TypedDict(
+    "UploadDocumentsResponseTypeDef",
+    {
+        "status": str,
+        "adds": int,
+        "deletes": int,
+        "warnings": List[DocumentServiceWarningTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HitsTypeDef = TypedDict(
     "HitsTypeDef",
     {
         "found": int,
         "start": int,
         "cursor": str,
         "hit": List[HitTypeDef],
     },
     total=False,
 )
 
-UploadDocumentsResponseTypeDef = TypedDict(
-    "UploadDocumentsResponseTypeDef",
-    {
-        "status": str,
-        "adds": int,
-        "deletes": int,
-        "warnings": List[DocumentServiceWarningTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 SuggestModelTypeDef = TypedDict(
     "SuggestModelTypeDef",
     {
         "query": str,
         "found": int,
         "suggestions": List[SuggestionMatchTypeDef],
     },
@@ -227,19 +227,19 @@
 SearchResponseTypeDef = TypedDict(
     "SearchResponseTypeDef",
     {
         "status": SearchStatusTypeDef,
         "hits": HitsTypeDef,
         "facets": Dict[str, BucketInfoTypeDef],
         "stats": Dict[str, FieldStatsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SuggestResponseTypeDef = TypedDict(
     "SuggestResponseTypeDef",
     {
         "status": SuggestStatusTypeDef,
         "suggest": SuggestModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/PKG-INFO` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudsearchdomain
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudSearchDomain 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudSearchDomain 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudsearchdomain"></a>
 
 # types-aiobotocore-cloudsearchdomain
 
 [![PyPI - types-aiobotocore-cloudsearchdomain](https://img.shields.io/pypi/v/types-aiobotocore-cloudsearchdomain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearchdomain)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudsearchdomain.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudsearchdomain)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudsearchdomain?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudsearchdomain)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudSearchDomain 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearchdomain.html#CloudSearchDomain)
+[aiobotocore.CloudSearchDomain 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudsearchdomain.html#CloudSearchDomain)
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
 [types-aiobotocore-cloudsearchdomain docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudsearchdomain/).
 
 See how it helps to find and fix potential bugs:
 
@@ -302,16 +302,16 @@
     SearchRequestRequestTypeDef,
     SearchStatusTypeDef,
     SuggestionMatchTypeDef,
     SuggestRequestRequestTypeDef,
     SuggestStatusTypeDef,
     UploadDocumentsRequestRequestTypeDef,
     BucketInfoTypeDef,
-    HitsTypeDef,
     UploadDocumentsResponseTypeDef,
+    HitsTypeDef,
     SuggestModelTypeDef,
     SearchResponseTypeDef,
     SuggestResponseTypeDef,
 )
 
 
 def get_structure() -> BucketTypeDef:
@@ -321,43 +321,43 @@
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

### Comparing `types-aiobotocore-cloudsearchdomain-2.5.0.post1/types_aiobotocore_cloudsearchdomain.egg-info/SOURCES.txt` & `types-aiobotocore-cloudsearchdomain-2.5.1/types_aiobotocore_cloudsearchdomain.egg-info/SOURCES.txt`

 * *Files identical despite different names*

