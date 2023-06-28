# Comparing `tmp/types-aiobotocore-ebs-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ebs-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ebs-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:32 2023, max compression
+gzip compressed data, was "types-aiobotocore-ebs-2.5.1.tar", last modified: Wed Jun 28 01:43:24 2023, max compression
```

## Comparing `types-aiobotocore-ebs-2.5.0.post1.tar` & `types-aiobotocore-ebs-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.227149 types-aiobotocore-ebs-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12472 2023-03-11 12:26:32.223149 types-aiobotocore-ebs-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    10917 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:32.227149 types-aiobotocore-ebs-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.219149 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      409 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8626 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8611 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8093 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8091 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     7038 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     7027 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:57.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.223149 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12472 2023-03-11 12:26:32.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      666 2023-03-11 12:26:32.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:32.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:32.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:32.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:32.000000 types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.898128 types-aiobotocore-ebs-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12460 2023-06-28 01:43:24.898128 types-aiobotocore-ebs-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    10911 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:24.898128 types-aiobotocore-ebs-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.898128 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      409 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8626 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8611 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8302 2023-06-28 01:29:36.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8300 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     7050 2023-06-28 01:29:36.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7039 2023-06-28 01:29:36.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:35.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.898128 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12460 2023-06-28 01:43:24.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 01:43:24.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:24.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:24.000000 types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ebs-2.5.0.post1/LICENSE` & `types-aiobotocore-ebs-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ebs-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ebs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EBS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EBS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ebs"></a>
 
 # types-aiobotocore-ebs
 
 [![PyPI - types-aiobotocore-ebs](https://img.shields.io/pypi/v/types-aiobotocore-ebs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ebs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ebs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ebs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ebs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ebs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EBS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS)
+[aiobotocore.EBS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS)
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
 [types-aiobotocore-ebs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -293,25 +293,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ebs.type_defs import (
     BlockTypeDef,
     ChangedBlockTypeDef,
     CompleteSnapshotRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CompleteSnapshotResponseTypeDef,
     GetSnapshotBlockRequestRequestTypeDef,
+    GetSnapshotBlockResponseTypeDef,
     ListChangedBlocksRequestRequestTypeDef,
     ListSnapshotBlocksRequestRequestTypeDef,
     PutSnapshotBlockRequestRequestTypeDef,
+    PutSnapshotBlockResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagTypeDef,
-    CompleteSnapshotResponseTypeDef,
-    GetSnapshotBlockResponseTypeDef,
-    ListChangedBlocksResponseTypeDef,
     ListSnapshotBlocksResponseTypeDef,
-    PutSnapshotBlockResponseTypeDef,
+    ListChangedBlocksResponseTypeDef,
     StartSnapshotRequestRequestTypeDef,
     StartSnapshotResponseTypeDef,
 )
 
 
 def get_structure() -> BlockTypeDef:
     return {...}
@@ -320,43 +320,43 @@
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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/README.md` & `types-aiobotocore-ebs-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ebs"></a>
 
 # types-aiobotocore-ebs
 
 [![PyPI - types-aiobotocore-ebs](https://img.shields.io/pypi/v/types-aiobotocore-ebs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ebs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ebs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ebs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ebs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ebs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EBS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS)
+[aiobotocore.EBS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS)
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
 [types-aiobotocore-ebs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -260,25 +260,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ebs.type_defs import (
     BlockTypeDef,
     ChangedBlockTypeDef,
     CompleteSnapshotRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CompleteSnapshotResponseTypeDef,
     GetSnapshotBlockRequestRequestTypeDef,
+    GetSnapshotBlockResponseTypeDef,
     ListChangedBlocksRequestRequestTypeDef,
     ListSnapshotBlocksRequestRequestTypeDef,
     PutSnapshotBlockRequestRequestTypeDef,
+    PutSnapshotBlockResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagTypeDef,
-    CompleteSnapshotResponseTypeDef,
-    GetSnapshotBlockResponseTypeDef,
-    ListChangedBlocksResponseTypeDef,
     ListSnapshotBlocksResponseTypeDef,
-    PutSnapshotBlockResponseTypeDef,
+    ListChangedBlocksResponseTypeDef,
     StartSnapshotRequestRequestTypeDef,
     StartSnapshotResponseTypeDef,
 )
 
 
 def get_structure() -> BlockTypeDef:
     return {...}
@@ -287,43 +287,43 @@
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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/setup.py` & `types-aiobotocore-ebs-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ebs.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ebs",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ebs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EBS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.EBS 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/",
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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/__main__.py` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EBS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EBS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS\nOther"
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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/client.py` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/client.pyi` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/literals.py` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -92,14 +92,15 @@
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
@@ -178,14 +179,15 @@
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
@@ -196,14 +198,15 @@
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
@@ -239,14 +242,15 @@
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
@@ -265,16 +269,19 @@
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
@@ -358,15 +365,17 @@
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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/literals.pyi` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/literals.pyi`

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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/type_defs.py` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -29,25 +29,25 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "BlockTypeDef",
     "ChangedBlockTypeDef",
     "CompleteSnapshotRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CompleteSnapshotResponseTypeDef",
     "GetSnapshotBlockRequestRequestTypeDef",
+    "GetSnapshotBlockResponseTypeDef",
     "ListChangedBlocksRequestRequestTypeDef",
     "ListSnapshotBlocksRequestRequestTypeDef",
     "PutSnapshotBlockRequestRequestTypeDef",
+    "PutSnapshotBlockResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TagTypeDef",
-    "CompleteSnapshotResponseTypeDef",
-    "GetSnapshotBlockResponseTypeDef",
-    "ListChangedBlocksResponseTypeDef",
     "ListSnapshotBlocksResponseTypeDef",
-    "PutSnapshotBlockResponseTypeDef",
+    "ListChangedBlocksResponseTypeDef",
     "StartSnapshotRequestRequestTypeDef",
     "StartSnapshotResponseTypeDef",
 )
 
 BlockTypeDef = TypedDict(
     "BlockTypeDef",
     {
@@ -87,34 +87,42 @@
 
 class CompleteSnapshotRequestRequestTypeDef(
     _RequiredCompleteSnapshotRequestRequestTypeDef, _OptionalCompleteSnapshotRequestRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CompleteSnapshotResponseTypeDef = TypedDict(
+    "CompleteSnapshotResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Status": StatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotBlockRequestRequestTypeDef = TypedDict(
     "GetSnapshotBlockRequestRequestTypeDef",
     {
         "SnapshotId": str,
         "BlockIndex": int,
         "BlockToken": str,
     },
 )
 
+GetSnapshotBlockResponseTypeDef = TypedDict(
+    "GetSnapshotBlockResponseTypeDef",
+    {
+        "DataLength": int,
+        "BlockData": StreamingBody,
+        "Checksum": str,
+        "ChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListChangedBlocksRequestRequestTypeDef = TypedDict(
     "_RequiredListChangedBlocksRequestRequestTypeDef",
     {
         "SecondSnapshotId": str,
     },
 )
 _OptionalListChangedBlocksRequestRequestTypeDef = TypedDict(
@@ -181,72 +189,64 @@
 
 class PutSnapshotBlockRequestRequestTypeDef(
     _RequiredPutSnapshotBlockRequestRequestTypeDef, _OptionalPutSnapshotBlockRequestRequestTypeDef
 ):
     pass
 
 
-TagTypeDef = TypedDict(
-    "TagTypeDef",
+PutSnapshotBlockResponseTypeDef = TypedDict(
+    "PutSnapshotBlockResponseTypeDef",
     {
-        "Key": str,
-        "Value": str,
+        "Checksum": str,
+        "ChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CompleteSnapshotResponseTypeDef = TypedDict(
-    "CompleteSnapshotResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-GetSnapshotBlockResponseTypeDef = TypedDict(
-    "GetSnapshotBlockResponseTypeDef",
+TagTypeDef = TypedDict(
+    "TagTypeDef",
     {
-        "DataLength": int,
-        "BlockData": StreamingBody,
-        "Checksum": str,
-        "ChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Key": str,
+        "Value": str,
     },
+    total=False,
 )
 
-ListChangedBlocksResponseTypeDef = TypedDict(
-    "ListChangedBlocksResponseTypeDef",
+ListSnapshotBlocksResponseTypeDef = TypedDict(
+    "ListSnapshotBlocksResponseTypeDef",
     {
-        "ChangedBlocks": List[ChangedBlockTypeDef],
+        "Blocks": List[BlockTypeDef],
         "ExpiryTime": datetime,
         "VolumeSize": int,
         "BlockSize": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListSnapshotBlocksResponseTypeDef = TypedDict(
-    "ListSnapshotBlocksResponseTypeDef",
+ListChangedBlocksResponseTypeDef = TypedDict(
+    "ListChangedBlocksResponseTypeDef",
     {
-        "Blocks": List[BlockTypeDef],
+        "ChangedBlocks": List[ChangedBlockTypeDef],
         "ExpiryTime": datetime,
         "VolumeSize": int,
         "BlockSize": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSnapshotBlockResponseTypeDef = TypedDict(
-    "PutSnapshotBlockResponseTypeDef",
-    {
-        "Checksum": str,
-        "ChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredStartSnapshotRequestRequestTypeDef",
     {
         "VolumeSize": int,
@@ -282,10 +282,10 @@
         "Status": StatusType,
         "StartTime": datetime,
         "VolumeSize": int,
         "BlockSize": int,
         "Tags": List[TagTypeDef],
         "ParentSnapshotId": str,
         "KmsKeyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs/type_defs.pyi` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -28,25 +28,25 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "BlockTypeDef",
     "ChangedBlockTypeDef",
     "CompleteSnapshotRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CompleteSnapshotResponseTypeDef",
     "GetSnapshotBlockRequestRequestTypeDef",
+    "GetSnapshotBlockResponseTypeDef",
     "ListChangedBlocksRequestRequestTypeDef",
     "ListSnapshotBlocksRequestRequestTypeDef",
     "PutSnapshotBlockRequestRequestTypeDef",
+    "PutSnapshotBlockResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TagTypeDef",
-    "CompleteSnapshotResponseTypeDef",
-    "GetSnapshotBlockResponseTypeDef",
-    "ListChangedBlocksResponseTypeDef",
     "ListSnapshotBlocksResponseTypeDef",
-    "PutSnapshotBlockResponseTypeDef",
+    "ListChangedBlocksResponseTypeDef",
     "StartSnapshotRequestRequestTypeDef",
     "StartSnapshotResponseTypeDef",
 )
 
 BlockTypeDef = TypedDict(
     "BlockTypeDef",
     {
@@ -84,34 +84,42 @@
 )
 
 class CompleteSnapshotRequestRequestTypeDef(
     _RequiredCompleteSnapshotRequestRequestTypeDef, _OptionalCompleteSnapshotRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CompleteSnapshotResponseTypeDef = TypedDict(
+    "CompleteSnapshotResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Status": StatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotBlockRequestRequestTypeDef = TypedDict(
     "GetSnapshotBlockRequestRequestTypeDef",
     {
         "SnapshotId": str,
         "BlockIndex": int,
         "BlockToken": str,
     },
 )
 
+GetSnapshotBlockResponseTypeDef = TypedDict(
+    "GetSnapshotBlockResponseTypeDef",
+    {
+        "DataLength": int,
+        "BlockData": StreamingBody,
+        "Checksum": str,
+        "ChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListChangedBlocksRequestRequestTypeDef = TypedDict(
     "_RequiredListChangedBlocksRequestRequestTypeDef",
     {
         "SecondSnapshotId": str,
     },
 )
 _OptionalListChangedBlocksRequestRequestTypeDef = TypedDict(
@@ -172,72 +180,64 @@
 )
 
 class PutSnapshotBlockRequestRequestTypeDef(
     _RequiredPutSnapshotBlockRequestRequestTypeDef, _OptionalPutSnapshotBlockRequestRequestTypeDef
 ):
     pass
 
-TagTypeDef = TypedDict(
-    "TagTypeDef",
+PutSnapshotBlockResponseTypeDef = TypedDict(
+    "PutSnapshotBlockResponseTypeDef",
     {
-        "Key": str,
-        "Value": str,
+        "Checksum": str,
+        "ChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CompleteSnapshotResponseTypeDef = TypedDict(
-    "CompleteSnapshotResponseTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Status": StatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-GetSnapshotBlockResponseTypeDef = TypedDict(
-    "GetSnapshotBlockResponseTypeDef",
+TagTypeDef = TypedDict(
+    "TagTypeDef",
     {
-        "DataLength": int,
-        "BlockData": StreamingBody,
-        "Checksum": str,
-        "ChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Key": str,
+        "Value": str,
     },
+    total=False,
 )
 
-ListChangedBlocksResponseTypeDef = TypedDict(
-    "ListChangedBlocksResponseTypeDef",
+ListSnapshotBlocksResponseTypeDef = TypedDict(
+    "ListSnapshotBlocksResponseTypeDef",
     {
-        "ChangedBlocks": List[ChangedBlockTypeDef],
+        "Blocks": List[BlockTypeDef],
         "ExpiryTime": datetime,
         "VolumeSize": int,
         "BlockSize": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListSnapshotBlocksResponseTypeDef = TypedDict(
-    "ListSnapshotBlocksResponseTypeDef",
+ListChangedBlocksResponseTypeDef = TypedDict(
+    "ListChangedBlocksResponseTypeDef",
     {
-        "Blocks": List[BlockTypeDef],
+        "ChangedBlocks": List[ChangedBlockTypeDef],
         "ExpiryTime": datetime,
         "VolumeSize": int,
         "BlockSize": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSnapshotBlockResponseTypeDef = TypedDict(
-    "PutSnapshotBlockResponseTypeDef",
-    {
-        "Checksum": str,
-        "ChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredStartSnapshotRequestRequestTypeDef",
     {
         "VolumeSize": int,
@@ -271,10 +271,10 @@
         "Status": StatusType,
         "StartTime": datetime,
         "VolumeSize": int,
         "BlockSize": int,
         "Tags": List[TagTypeDef],
         "ParentSnapshotId": str,
         "KmsKeyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/PKG-INFO` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ebs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EBS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EBS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ebs"></a>
 
 # types-aiobotocore-ebs
 
 [![PyPI - types-aiobotocore-ebs](https://img.shields.io/pypi/v/types-aiobotocore-ebs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ebs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ebs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ebs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ebs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ebs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EBS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS)
+[aiobotocore.EBS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ebs.html#EBS)
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
 [types-aiobotocore-ebs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ebs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -293,25 +293,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_ebs.type_defs import (
     BlockTypeDef,
     ChangedBlockTypeDef,
     CompleteSnapshotRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CompleteSnapshotResponseTypeDef,
     GetSnapshotBlockRequestRequestTypeDef,
+    GetSnapshotBlockResponseTypeDef,
     ListChangedBlocksRequestRequestTypeDef,
     ListSnapshotBlocksRequestRequestTypeDef,
     PutSnapshotBlockRequestRequestTypeDef,
+    PutSnapshotBlockResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagTypeDef,
-    CompleteSnapshotResponseTypeDef,
-    GetSnapshotBlockResponseTypeDef,
-    ListChangedBlocksResponseTypeDef,
     ListSnapshotBlocksResponseTypeDef,
-    PutSnapshotBlockResponseTypeDef,
+    ListChangedBlocksResponseTypeDef,
     StartSnapshotRequestRequestTypeDef,
     StartSnapshotResponseTypeDef,
 )
 
 
 def get_structure() -> BlockTypeDef:
     return {...}
@@ -320,43 +320,43 @@
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

### Comparing `types-aiobotocore-ebs-2.5.0.post1/types_aiobotocore_ebs.egg-info/SOURCES.txt` & `types-aiobotocore-ebs-2.5.1/types_aiobotocore_ebs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

