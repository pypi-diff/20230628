# Comparing `tmp/types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sagemaker-featurestore-runtime-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:16 2023, max compression
+gzip compressed data, was "types-aiobotocore-sagemaker-featurestore-runtime-2.5.1.tar", last modified: Wed Jun 28 01:44:07 2023, max compression
```

## Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1.tar` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.235587 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13559 2023-03-11 12:27:16.235587 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11898 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:16.235587 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2286 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.235587 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/
--rw-r--r--   0 runner    (1001) docker     (123)      616 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      615 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1031 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7532 2023-03-11 12:23:31.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     7520 2023-03-11 12:23:31.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7524 2023-03-11 12:23:31.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7522 2023-03-11 12:23:31.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     4822 2023-03-11 12:23:31.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     4813 2023-03-11 12:23:31.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:30.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.235587 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13559 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1125 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       49 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.498208 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13597 2023-06-28 01:44:07.498208 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11942 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:07.498208 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2280 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.498208 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/
+-rw-r--r--   0 runner    (1001) docker     (123)      616 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      615 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1019 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7616 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7604 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7812 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7810 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     4888 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4879 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:17.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.498208 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13597 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1125 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       49 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/LICENSE` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-featurestore-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-featurestore-runtime"></a>
 
 # types-aiobotocore-sagemaker-featurestore-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-featurestore-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-featurestore-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-featurestore-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-featurestore-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-featurestore-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-featurestore-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-featurestore-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerFeatureStoreRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime)
+[aiobotocore.SageMakerFeatureStoreRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime)
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
 [types-aiobotocore-sagemaker-featurestore-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,22 +273,23 @@
 ### Literals
 
 `types_aiobotocore_sagemaker_featurestore_runtime.literals` module contains
 literals extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_sagemaker_featurestore_runtime.literals import (
+    DeletionModeType,
     TargetStoreType,
     SageMakerFeatureStoreRuntimeServiceName,
     ServiceName,
     ResourceServiceName,
 )
 
 
-def check_value(value: TargetStoreType) -> bool:
+def check_value(value: DeletionModeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
@@ -296,20 +297,20 @@
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_sagemaker_featurestore_runtime.type_defs import (
     BatchGetRecordErrorTypeDef,
     BatchGetRecordIdentifierTypeDef,
-    ResponseMetadataTypeDef,
     FeatureValueTypeDef,
     DeleteRecordRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRecordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     BatchGetRecordRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     BatchGetRecordResultDetailTypeDef,
     GetRecordResponseTypeDef,
     PutRecordRequestRequestTypeDef,
     BatchGetRecordResponseTypeDef,
 )
 
 
@@ -320,43 +321,43 @@
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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/README.md` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sagemaker-featurestore-runtime"></a>
 
 # types-aiobotocore-sagemaker-featurestore-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-featurestore-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-featurestore-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-featurestore-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-featurestore-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-featurestore-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-featurestore-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-featurestore-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerFeatureStoreRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime)
+[aiobotocore.SageMakerFeatureStoreRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime)
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
 [types-aiobotocore-sagemaker-featurestore-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -240,22 +240,23 @@
 ### Literals
 
 `types_aiobotocore_sagemaker_featurestore_runtime.literals` module contains
 literals extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_sagemaker_featurestore_runtime.literals import (
+    DeletionModeType,
     TargetStoreType,
     SageMakerFeatureStoreRuntimeServiceName,
     ServiceName,
     ResourceServiceName,
 )
 
 
-def check_value(value: TargetStoreType) -> bool:
+def check_value(value: DeletionModeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
@@ -263,20 +264,20 @@
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_sagemaker_featurestore_runtime.type_defs import (
     BatchGetRecordErrorTypeDef,
     BatchGetRecordIdentifierTypeDef,
-    ResponseMetadataTypeDef,
     FeatureValueTypeDef,
     DeleteRecordRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRecordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     BatchGetRecordRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     BatchGetRecordResultDetailTypeDef,
     GetRecordResponseTypeDef,
     PutRecordRequestRequestTypeDef,
     BatchGetRecordResponseTypeDef,
 )
 
 
@@ -287,43 +288,43 @@
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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/setup.py` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sagemaker-featurestore-runtime.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sagemaker-featurestore-runtime",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sagemaker_featurestore_runtime"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/",
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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.py` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.pyi` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/__main__.py` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime\nOther"
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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/client.py` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,15 +15,15 @@
     ```
 """
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import TargetStoreType
+from .literals import DeletionModeType, TargetStoreType
 from .type_defs import (
     BatchGetRecordIdentifierTypeDef,
     BatchGetRecordResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     FeatureValueTypeDef,
     GetRecordResponseTypeDef,
 )
@@ -65,15 +65,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/client/#exceptions)
         """
 
     async def batch_get_record(
         self, *, Identifiers: Sequence[BatchGetRecordIdentifierTypeDef]
     ) -> BatchGetRecordResponseTypeDef:
         """
-        Retrieves a batch of `Records` from a `FeatureGroup` .
+        Retrieves a batch of `Records` from a `FeatureGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime.Client.batch_get_record)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/client/#batch_get_record)
         """
 
     def can_paginate(self, operation_name: str) -> bool:
         """
@@ -93,18 +93,19 @@
 
     async def delete_record(
         self,
         *,
         FeatureGroupName: str,
         RecordIdentifierValueAsString: str,
         EventTime: str,
-        TargetStores: Sequence[TargetStoreType] = ...
+        TargetStores: Sequence[TargetStoreType] = ...,
+        DeletionMode: DeletionModeType = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes a `Record` from a `FeatureGroup`.
+        Deletes a `Record` from a `FeatureGroup` in the `OnlineStore`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime.Client.delete_record)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/client/#delete_record)
         """
 
     async def generate_presigned_url(
         self,
```

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/client.pyi` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -15,15 +15,15 @@
     ```
 """
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import TargetStoreType
+from .literals import DeletionModeType, TargetStoreType
 from .type_defs import (
     BatchGetRecordIdentifierTypeDef,
     BatchGetRecordResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     FeatureValueTypeDef,
     GetRecordResponseTypeDef,
 )
@@ -61,15 +61,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/client/#exceptions)
         """
     async def batch_get_record(
         self, *, Identifiers: Sequence[BatchGetRecordIdentifierTypeDef]
     ) -> BatchGetRecordResponseTypeDef:
         """
-        Retrieves a batch of `Records` from a `FeatureGroup` .
+        Retrieves a batch of `Records` from a `FeatureGroup`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime.Client.batch_get_record)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/client/#batch_get_record)
         """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
@@ -86,18 +86,19 @@
         """
     async def delete_record(
         self,
         *,
         FeatureGroupName: str,
         RecordIdentifierValueAsString: str,
         EventTime: str,
-        TargetStores: Sequence[TargetStoreType] = ...
+        TargetStores: Sequence[TargetStoreType] = ...,
+        DeletionMode: DeletionModeType = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes a `Record` from a `FeatureGroup`.
+        Deletes a `Record` from a `FeatureGroup` in the `OnlineStore`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime.Client.delete_record)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/client/#delete_record)
         """
     async def generate_presigned_url(
         self,
         ClientMethod: str,
```

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/literals.py` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,35 +2,37 @@
 Type annotations for sagemaker-featurestore-runtime service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_sagemaker_featurestore_runtime.literals import TargetStoreType
+    from types_aiobotocore_sagemaker_featurestore_runtime.literals import DeletionModeType
 
-    data: TargetStoreType = "OfflineStore"
+    data: DeletionModeType = "HardDelete"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "DeletionModeType",
     "TargetStoreType",
     "SageMakerFeatureStoreRuntimeServiceName",
     "ServiceName",
     "ResourceServiceName",
 )
 
 
+DeletionModeType = Literal["HardDelete", "SoftDelete"]
 TargetStoreType = Literal["OfflineStore", "OnlineStore"]
 SageMakerFeatureStoreRuntimeServiceName = Literal["sagemaker-featurestore-runtime"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -87,14 +89,15 @@
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
@@ -173,14 +176,15 @@
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
@@ -191,14 +195,15 @@
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
@@ -234,14 +239,15 @@
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
@@ -260,16 +266,19 @@
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
@@ -353,15 +362,17 @@
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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/literals.pyi` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -2,33 +2,35 @@
 Type annotations for sagemaker-featurestore-runtime service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_sagemaker_featurestore_runtime.literals import TargetStoreType
+    from types_aiobotocore_sagemaker_featurestore_runtime.literals import DeletionModeType
 
-    data: TargetStoreType = "OfflineStore"
+    data: DeletionModeType = "HardDelete"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "DeletionModeType",
     "TargetStoreType",
     "SageMakerFeatureStoreRuntimeServiceName",
     "ServiceName",
     "ResourceServiceName",
 )
 
+DeletionModeType = Literal["HardDelete", "SoftDelete"]
 TargetStoreType = Literal["OfflineStore", "OnlineStore"]
 SageMakerFeatureStoreRuntimeServiceName = Literal["sagemaker-featurestore-runtime"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -85,14 +87,15 @@
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
@@ -171,14 +174,15 @@
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
@@ -189,14 +193,15 @@
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
@@ -232,14 +237,15 @@
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
@@ -258,16 +264,19 @@
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
@@ -351,15 +360,17 @@
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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.py` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -10,31 +10,31 @@
 
     data: BatchGetRecordErrorTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Sequence
 
-from .literals import TargetStoreType
+from .literals import DeletionModeType, TargetStoreType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "BatchGetRecordErrorTypeDef",
     "BatchGetRecordIdentifierTypeDef",
-    "ResponseMetadataTypeDef",
     "FeatureValueTypeDef",
     "DeleteRecordRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetRecordRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "BatchGetRecordRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "BatchGetRecordResultDetailTypeDef",
     "GetRecordResponseTypeDef",
     "PutRecordRequestRequestTypeDef",
     "BatchGetRecordResponseTypeDef",
 )
 
 BatchGetRecordErrorTypeDef = TypedDict(
@@ -65,25 +65,14 @@
 
 class BatchGetRecordIdentifierTypeDef(
     _RequiredBatchGetRecordIdentifierTypeDef, _OptionalBatchGetRecordIdentifierTypeDef
 ):
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
 FeatureValueTypeDef = TypedDict(
     "FeatureValueTypeDef",
     {
         "FeatureName": str,
         "ValueAsString": str,
     },
 )
@@ -96,25 +85,33 @@
         "EventTime": str,
     },
 )
 _OptionalDeleteRecordRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteRecordRequestRequestTypeDef",
     {
         "TargetStores": Sequence[TargetStoreType],
+        "DeletionMode": DeletionModeType,
     },
     total=False,
 )
 
 
 class DeleteRecordRequestRequestTypeDef(
     _RequiredDeleteRecordRequestRequestTypeDef, _OptionalDeleteRecordRequestRequestTypeDef
 ):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRecordRequestRequestTypeDef = TypedDict(
     "_RequiredGetRecordRequestRequestTypeDef",
     {
         "FeatureGroupName": str,
         "RecordIdentifierValueAsString": str,
     },
 )
@@ -129,25 +126,29 @@
 
 class GetRecordRequestRequestTypeDef(
     _RequiredGetRecordRequestRequestTypeDef, _OptionalGetRecordRequestRequestTypeDef
 ):
     pass
 
 
-BatchGetRecordRequestRequestTypeDef = TypedDict(
-    "BatchGetRecordRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Identifiers": Sequence[BatchGetRecordIdentifierTypeDef],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+BatchGetRecordRequestRequestTypeDef = TypedDict(
+    "BatchGetRecordRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Identifiers": Sequence[BatchGetRecordIdentifierTypeDef],
     },
 )
 
 BatchGetRecordResultDetailTypeDef = TypedDict(
     "BatchGetRecordResultDetailTypeDef",
     {
         "FeatureGroupName": str,
@@ -156,15 +157,15 @@
     },
 )
 
 GetRecordResponseTypeDef = TypedDict(
     "GetRecordResponseTypeDef",
     {
         "Record": List[FeatureValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutRecordRequestRequestTypeDef = TypedDict(
     "_RequiredPutRecordRequestRequestTypeDef",
     {
         "FeatureGroupName": str,
@@ -188,10 +189,10 @@
 
 BatchGetRecordResponseTypeDef = TypedDict(
     "BatchGetRecordResponseTypeDef",
     {
         "Records": List[BatchGetRecordResultDetailTypeDef],
         "Errors": List[BatchGetRecordErrorTypeDef],
         "UnprocessedIdentifiers": List[BatchGetRecordIdentifierTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.pyi` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -10,30 +10,30 @@
 
     data: BatchGetRecordErrorTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Sequence
 
-from .literals import TargetStoreType
+from .literals import DeletionModeType, TargetStoreType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "BatchGetRecordErrorTypeDef",
     "BatchGetRecordIdentifierTypeDef",
-    "ResponseMetadataTypeDef",
     "FeatureValueTypeDef",
     "DeleteRecordRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetRecordRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "BatchGetRecordRequestRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "BatchGetRecordResultDetailTypeDef",
     "GetRecordResponseTypeDef",
     "PutRecordRequestRequestTypeDef",
     "BatchGetRecordResponseTypeDef",
 )
 
 BatchGetRecordErrorTypeDef = TypedDict(
@@ -62,25 +62,14 @@
 )
 
 class BatchGetRecordIdentifierTypeDef(
     _RequiredBatchGetRecordIdentifierTypeDef, _OptionalBatchGetRecordIdentifierTypeDef
 ):
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
 FeatureValueTypeDef = TypedDict(
     "FeatureValueTypeDef",
     {
         "FeatureName": str,
         "ValueAsString": str,
     },
 )
@@ -93,23 +82,31 @@
         "EventTime": str,
     },
 )
 _OptionalDeleteRecordRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteRecordRequestRequestTypeDef",
     {
         "TargetStores": Sequence[TargetStoreType],
+        "DeletionMode": DeletionModeType,
     },
     total=False,
 )
 
 class DeleteRecordRequestRequestTypeDef(
     _RequiredDeleteRecordRequestRequestTypeDef, _OptionalDeleteRecordRequestRequestTypeDef
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRecordRequestRequestTypeDef = TypedDict(
     "_RequiredGetRecordRequestRequestTypeDef",
     {
         "FeatureGroupName": str,
         "RecordIdentifierValueAsString": str,
     },
 )
@@ -122,25 +119,29 @@
 )
 
 class GetRecordRequestRequestTypeDef(
     _RequiredGetRecordRequestRequestTypeDef, _OptionalGetRecordRequestRequestTypeDef
 ):
     pass
 
-BatchGetRecordRequestRequestTypeDef = TypedDict(
-    "BatchGetRecordRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Identifiers": Sequence[BatchGetRecordIdentifierTypeDef],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+BatchGetRecordRequestRequestTypeDef = TypedDict(
+    "BatchGetRecordRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Identifiers": Sequence[BatchGetRecordIdentifierTypeDef],
     },
 )
 
 BatchGetRecordResultDetailTypeDef = TypedDict(
     "BatchGetRecordResultDetailTypeDef",
     {
         "FeatureGroupName": str,
@@ -149,15 +150,15 @@
     },
 )
 
 GetRecordResponseTypeDef = TypedDict(
     "GetRecordResponseTypeDef",
     {
         "Record": List[FeatureValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutRecordRequestRequestTypeDef = TypedDict(
     "_RequiredPutRecordRequestRequestTypeDef",
     {
         "FeatureGroupName": str,
@@ -179,10 +180,10 @@
 
 BatchGetRecordResponseTypeDef = TypedDict(
     "BatchGetRecordResponseTypeDef",
     {
         "Records": List[BatchGetRecordResultDetailTypeDef],
         "Errors": List[BatchGetRecordErrorTypeDef],
         "UnprocessedIdentifiers": List[BatchGetRecordIdentifierTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/PKG-INFO` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-featurestore-runtime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SageMakerFeatureStoreRuntime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-featurestore-runtime"></a>
 
 # types-aiobotocore-sagemaker-featurestore-runtime
 
 [![PyPI - types-aiobotocore-sagemaker-featurestore-runtime](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-featurestore-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-featurestore-runtime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-featurestore-runtime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-featurestore-runtime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-featurestore-runtime?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-featurestore-runtime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerFeatureStoreRuntime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime)
+[aiobotocore.SageMakerFeatureStoreRuntime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-featurestore-runtime.html#SageMakerFeatureStoreRuntime)
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
 [types-aiobotocore-sagemaker-featurestore-runtime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_featurestore_runtime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -273,22 +273,23 @@
 ### Literals
 
 `types_aiobotocore_sagemaker_featurestore_runtime.literals` module contains
 literals extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_sagemaker_featurestore_runtime.literals import (
+    DeletionModeType,
     TargetStoreType,
     SageMakerFeatureStoreRuntimeServiceName,
     ServiceName,
     ResourceServiceName,
 )
 
 
-def check_value(value: TargetStoreType) -> bool:
+def check_value(value: DeletionModeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
@@ -296,20 +297,20 @@
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_sagemaker_featurestore_runtime.type_defs import (
     BatchGetRecordErrorTypeDef,
     BatchGetRecordIdentifierTypeDef,
-    ResponseMetadataTypeDef,
     FeatureValueTypeDef,
     DeleteRecordRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetRecordRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     BatchGetRecordRequestRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
     BatchGetRecordResultDetailTypeDef,
     GetRecordResponseTypeDef,
     PutRecordRequestRequestTypeDef,
     BatchGetRecordResponseTypeDef,
 )
 
 
@@ -320,43 +321,43 @@
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

### Comparing `types-aiobotocore-sagemaker-featurestore-runtime-2.5.0.post1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/SOURCES.txt` & `types-aiobotocore-sagemaker-featurestore-runtime-2.5.1/types_aiobotocore_sagemaker_featurestore_runtime.egg-info/SOURCES.txt`

 * *Files identical despite different names*

