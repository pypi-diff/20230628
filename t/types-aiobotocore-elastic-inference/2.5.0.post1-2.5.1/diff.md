# Comparing `tmp/types-aiobotocore-elastic-inference-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-elastic-inference-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-elastic-inference-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-elastic-inference-2.5.1.tar", last modified: Wed Jun 28 01:43:27 2023, max compression
```

## Comparing `types-aiobotocore-elastic-inference-2.5.0.post1.tar` & `types-aiobotocore-elastic-inference-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.579174 types-aiobotocore-elastic-inference-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14156 2023-03-11 12:26:34.571174 types-aiobotocore-elastic-inference-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12546 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.579174 types-aiobotocore-elastic-inference-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-03-11 12:13:59.000000 types-aiobotocore-elastic-inference-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.567174 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/
--rw-r--r--   0 runner    (1001) docker     (123)      758 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      757 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8763 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8747 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7832 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7830 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2431 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2427 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5696 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5693 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:00.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.571174 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14156 2023-03-11 12:26:34.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-03-11 12:26:34.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:34.000000 types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.046132 types-aiobotocore-elastic-inference-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14158 2023-06-28 01:43:27.046132 types-aiobotocore-elastic-inference-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12554 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:27.046132 types-aiobotocore-elastic-inference-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2203 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.046132 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/
+-rw-r--r--   0 runner    (1001) docker     (123)      758 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      757 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8763 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8747 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8041 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8039 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2313 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2310 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5706 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5703 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:36.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.046132 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14158 2023-06-28 01:43:26.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 01:43:26.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:26.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:26.000000 types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/LICENSE` & `types-aiobotocore-elastic-inference-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/PKG-INFO` & `types-aiobotocore-elastic-inference-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-elastic-inference
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticInference 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore elastic-inference type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-elastic-inference"></a>
 
 # types-aiobotocore-elastic-inference
 
 [![PyPI - types-aiobotocore-elastic-inference](https://img.shields.io/pypi/v/types-aiobotocore-elastic-inference.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastic-inference)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elastic-inference.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastic-inference)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elastic-inference?color=blue)](https://pypistats.org/packages/types-aiobotocore-elastic-inference)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticInference 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference)
+[aiobotocore.ElasticInference 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference)
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
 [types-aiobotocore-elastic-inference docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/).
 
 See how it helps to find and fix potential bugs:
 
@@ -321,26 +288,26 @@
 
 ```python
 from types_aiobotocore_elastic_inference.type_defs import (
     AcceleratorTypeOfferingTypeDef,
     KeyValuePairTypeDef,
     MemoryInfoTypeDef,
     DescribeAcceleratorOfferingsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     ElasticInferenceAcceleratorHealthTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AcceleratorTypeTypeDef,
     DescribeAcceleratorOfferingsResponseTypeDef,
-    ListTagsForResourceResultTypeDef,
-    DescribeAcceleratorsRequestRequestTypeDef,
+    AcceleratorTypeTypeDef,
     DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef,
+    DescribeAcceleratorsRequestRequestTypeDef,
     ElasticInferenceAcceleratorTypeDef,
     DescribeAcceleratorTypesResponseTypeDef,
     DescribeAcceleratorsResponseTypeDef,
 )
 
 
 def get_structure() -> AcceleratorTypeOfferingTypeDef:
@@ -350,43 +317,43 @@
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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/README.md` & `types-aiobotocore-elastic-inference-2.5.1/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-elastic-inference
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticInference 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore elastic-inference type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-elastic-inference"></a>
 
 # types-aiobotocore-elastic-inference
 
 [![PyPI - types-aiobotocore-elastic-inference](https://img.shields.io/pypi/v/types-aiobotocore-elastic-inference.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastic-inference)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elastic-inference.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastic-inference)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elastic-inference?color=blue)](https://pypistats.org/packages/types-aiobotocore-elastic-inference)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticInference 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference)
+[aiobotocore.ElasticInference 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference)
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
 [types-aiobotocore-elastic-inference docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/).
 
 See how it helps to find and fix potential bugs:
 
@@ -288,26 +321,26 @@
 
 ```python
 from types_aiobotocore_elastic_inference.type_defs import (
     AcceleratorTypeOfferingTypeDef,
     KeyValuePairTypeDef,
     MemoryInfoTypeDef,
     DescribeAcceleratorOfferingsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     ElasticInferenceAcceleratorHealthTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AcceleratorTypeTypeDef,
     DescribeAcceleratorOfferingsResponseTypeDef,
-    ListTagsForResourceResultTypeDef,
-    DescribeAcceleratorsRequestRequestTypeDef,
+    AcceleratorTypeTypeDef,
     DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef,
+    DescribeAcceleratorsRequestRequestTypeDef,
     ElasticInferenceAcceleratorTypeDef,
     DescribeAcceleratorTypesResponseTypeDef,
     DescribeAcceleratorsResponseTypeDef,
 )
 
 
 def get_structure() -> AcceleratorTypeOfferingTypeDef:
@@ -317,43 +350,43 @@
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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/setup.py` & `types-aiobotocore-elastic-inference-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-elastic-inference.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-elastic-inference",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_elastic_inference"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ElasticInference 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ElasticInference 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/"
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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/__init__.py` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/__init__.pyi` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/__main__.py` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/__main__.py`

 * *Files 18% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ElasticInference 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ElasticInference 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference\nOther"
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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/client.py` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/client.pyi` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/literals.py` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -14,26 +14,24 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "DescribeAcceleratorsPaginatorName",
     "LocationTypeType",
     "ElasticInferenceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 DescribeAcceleratorsPaginatorName = Literal["describe_accelerators"]
 LocationTypeType = Literal["availability-zone", "availability-zone-id", "region"]
 ElasticInferenceServiceName = Literal["elastic-inference"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -91,14 +89,15 @@
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
@@ -177,14 +176,15 @@
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
@@ -195,14 +195,15 @@
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
@@ -238,14 +239,15 @@
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
@@ -264,16 +266,19 @@
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
@@ -357,15 +362,17 @@
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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/literals.pyi` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -14,24 +14,26 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "DescribeAcceleratorsPaginatorName",
     "LocationTypeType",
     "ElasticInferenceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 DescribeAcceleratorsPaginatorName = Literal["describe_accelerators"]
 LocationTypeType = Literal["availability-zone", "availability-zone-id", "region"]
 ElasticInferenceServiceName = Literal["elastic-inference"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -89,14 +91,15 @@
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
@@ -175,14 +178,15 @@
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
@@ -193,14 +197,15 @@
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
@@ -236,14 +241,15 @@
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
@@ -262,16 +268,19 @@
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
@@ -355,15 +364,17 @@
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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/paginator.py` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("elastic-inference") as client:
         client: ElasticInferenceClient
 
         describe_accelerators_paginator: DescribeAcceleratorsPaginator = client.get_paginator("describe_accelerators")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import DescribeAcceleratorsResponseTypeDef, FilterTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeAcceleratorsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -54,13 +47,13 @@
     """
 
     def paginate(
         self,
         *,
         acceleratorIds: Sequence[str] = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAcceleratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference.Paginator.DescribeAccelerators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/paginators/#describeacceleratorspaginator)
         """
```

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/paginator.pyi` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("elastic-inference") as client:
         client: ElasticInferenceClient
 
         describe_accelerators_paginator: DescribeAcceleratorsPaginator = client.get_paginator("describe_accelerators")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import DescribeAcceleratorsResponseTypeDef, FilterTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeAcceleratorsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -50,13 +44,13 @@
     """
 
     def paginate(
         self,
         *,
         acceleratorIds: Sequence[str] = ...,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAcceleratorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference.Paginator.DescribeAccelerators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/paginators/#describeacceleratorspaginator)
         """
```

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/type_defs.py` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -23,26 +23,26 @@
 
 
 __all__ = (
     "AcceleratorTypeOfferingTypeDef",
     "KeyValuePairTypeDef",
     "MemoryInfoTypeDef",
     "DescribeAcceleratorOfferingsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ElasticInferenceAcceleratorHealthTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AcceleratorTypeTypeDef",
     "DescribeAcceleratorOfferingsResponseTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "DescribeAcceleratorsRequestRequestTypeDef",
+    "AcceleratorTypeTypeDef",
     "DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef",
+    "DescribeAcceleratorsRequestRequestTypeDef",
     "ElasticInferenceAcceleratorTypeDef",
     "DescribeAcceleratorTypesResponseTypeDef",
     "DescribeAcceleratorsResponseTypeDef",
 )
 
 AcceleratorTypeOfferingTypeDef = TypedDict(
     "AcceleratorTypeOfferingTypeDef",
@@ -89,44 +89,23 @@
 class DescribeAcceleratorOfferingsRequestRequestTypeDef(
     _RequiredDescribeAcceleratorOfferingsRequestRequestTypeDef,
     _OptionalDescribeAcceleratorOfferingsRequestRequestTypeDef,
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
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "name": str,
         "values": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 ElasticInferenceAcceleratorHealthTypeDef = TypedDict(
     "ElasticInferenceAcceleratorHealthTypeDef",
     {
         "status": str,
     },
     total=False,
 )
@@ -134,14 +113,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -150,57 +158,49 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-AcceleratorTypeTypeDef = TypedDict(
-    "AcceleratorTypeTypeDef",
-    {
-        "acceleratorTypeName": str,
-        "memoryInfo": MemoryInfoTypeDef,
-        "throughputInfo": List[KeyValuePairTypeDef],
-    },
-    total=False,
-)
-
 DescribeAcceleratorOfferingsResponseTypeDef = TypedDict(
     "DescribeAcceleratorOfferingsResponseTypeDef",
     {
         "acceleratorTypeOfferings": List[AcceleratorTypeOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
+AcceleratorTypeTypeDef = TypedDict(
+    "AcceleratorTypeTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "acceleratorTypeName": str,
+        "memoryInfo": MemoryInfoTypeDef,
+        "throughputInfo": List[KeyValuePairTypeDef],
     },
+    total=False,
 )
 
-DescribeAcceleratorsRequestRequestTypeDef = TypedDict(
-    "DescribeAcceleratorsRequestRequestTypeDef",
+DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef = TypedDict(
+    "DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef",
     {
         "acceleratorIds": Sequence[str],
         "filters": Sequence[FilterTypeDef],
-        "maxResults": int,
-        "nextToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef = TypedDict(
-    "DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef",
+DescribeAcceleratorsRequestRequestTypeDef = TypedDict(
+    "DescribeAcceleratorsRequestRequestTypeDef",
     {
         "acceleratorIds": Sequence[str],
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "maxResults": int,
+        "nextToken": str,
     },
     total=False,
 )
 
 ElasticInferenceAcceleratorTypeDef = TypedDict(
     "ElasticInferenceAcceleratorTypeDef",
     {
@@ -213,19 +213,19 @@
     total=False,
 )
 
 DescribeAcceleratorTypesResponseTypeDef = TypedDict(
     "DescribeAcceleratorTypesResponseTypeDef",
     {
         "acceleratorTypes": List[AcceleratorTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAcceleratorsResponseTypeDef = TypedDict(
     "DescribeAcceleratorsResponseTypeDef",
     {
         "acceleratorSet": List[ElasticInferenceAcceleratorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference/type_defs.pyi` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -22,26 +22,26 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceleratorTypeOfferingTypeDef",
     "KeyValuePairTypeDef",
     "MemoryInfoTypeDef",
     "DescribeAcceleratorOfferingsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ElasticInferenceAcceleratorHealthTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AcceleratorTypeTypeDef",
     "DescribeAcceleratorOfferingsResponseTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "DescribeAcceleratorsRequestRequestTypeDef",
+    "AcceleratorTypeTypeDef",
     "DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef",
+    "DescribeAcceleratorsRequestRequestTypeDef",
     "ElasticInferenceAcceleratorTypeDef",
     "DescribeAcceleratorTypesResponseTypeDef",
     "DescribeAcceleratorsResponseTypeDef",
 )
 
 AcceleratorTypeOfferingTypeDef = TypedDict(
     "AcceleratorTypeOfferingTypeDef",
@@ -86,44 +86,23 @@
 
 class DescribeAcceleratorOfferingsRequestRequestTypeDef(
     _RequiredDescribeAcceleratorOfferingsRequestRequestTypeDef,
     _OptionalDescribeAcceleratorOfferingsRequestRequestTypeDef,
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
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "name": str,
         "values": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 ElasticInferenceAcceleratorHealthTypeDef = TypedDict(
     "ElasticInferenceAcceleratorHealthTypeDef",
     {
         "status": str,
     },
     total=False,
 )
@@ -131,14 +110,43 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -147,57 +155,49 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
-AcceleratorTypeTypeDef = TypedDict(
-    "AcceleratorTypeTypeDef",
-    {
-        "acceleratorTypeName": str,
-        "memoryInfo": MemoryInfoTypeDef,
-        "throughputInfo": List[KeyValuePairTypeDef],
-    },
-    total=False,
-)
-
 DescribeAcceleratorOfferingsResponseTypeDef = TypedDict(
     "DescribeAcceleratorOfferingsResponseTypeDef",
     {
         "acceleratorTypeOfferings": List[AcceleratorTypeOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
+AcceleratorTypeTypeDef = TypedDict(
+    "AcceleratorTypeTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "acceleratorTypeName": str,
+        "memoryInfo": MemoryInfoTypeDef,
+        "throughputInfo": List[KeyValuePairTypeDef],
     },
+    total=False,
 )
 
-DescribeAcceleratorsRequestRequestTypeDef = TypedDict(
-    "DescribeAcceleratorsRequestRequestTypeDef",
+DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef = TypedDict(
+    "DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef",
     {
         "acceleratorIds": Sequence[str],
         "filters": Sequence[FilterTypeDef],
-        "maxResults": int,
-        "nextToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef = TypedDict(
-    "DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef",
+DescribeAcceleratorsRequestRequestTypeDef = TypedDict(
+    "DescribeAcceleratorsRequestRequestTypeDef",
     {
         "acceleratorIds": Sequence[str],
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "maxResults": int,
+        "nextToken": str,
     },
     total=False,
 )
 
 ElasticInferenceAcceleratorTypeDef = TypedDict(
     "ElasticInferenceAcceleratorTypeDef",
     {
@@ -210,19 +210,19 @@
     total=False,
 )
 
 DescribeAcceleratorTypesResponseTypeDef = TypedDict(
     "DescribeAcceleratorTypesResponseTypeDef",
     {
         "acceleratorTypes": List[AcceleratorTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAcceleratorsResponseTypeDef = TypedDict(
     "DescribeAcceleratorsResponseTypeDef",
     {
         "acceleratorSet": List[ElasticInferenceAcceleratorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/PKG-INFO` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elastic-inference
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticInference 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticInference 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elastic-inference"></a>
 
 # types-aiobotocore-elastic-inference
 
 [![PyPI - types-aiobotocore-elastic-inference](https://img.shields.io/pypi/v/types-aiobotocore-elastic-inference.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastic-inference)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elastic-inference.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elastic-inference)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elastic-inference?color=blue)](https://pypistats.org/packages/types-aiobotocore-elastic-inference)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticInference 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference)
+[aiobotocore.ElasticInference 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elastic-inference.html#ElasticInference)
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
 [types-aiobotocore-elastic-inference docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elastic_inference/).
 
 See how it helps to find and fix potential bugs:
 
@@ -321,26 +321,26 @@
 
 ```python
 from types_aiobotocore_elastic_inference.type_defs import (
     AcceleratorTypeOfferingTypeDef,
     KeyValuePairTypeDef,
     MemoryInfoTypeDef,
     DescribeAcceleratorOfferingsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     ElasticInferenceAcceleratorHealthTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AcceleratorTypeTypeDef,
     DescribeAcceleratorOfferingsResponseTypeDef,
-    ListTagsForResourceResultTypeDef,
-    DescribeAcceleratorsRequestRequestTypeDef,
+    AcceleratorTypeTypeDef,
     DescribeAcceleratorsRequestDescribeAcceleratorsPaginateTypeDef,
+    DescribeAcceleratorsRequestRequestTypeDef,
     ElasticInferenceAcceleratorTypeDef,
     DescribeAcceleratorTypesResponseTypeDef,
     DescribeAcceleratorsResponseTypeDef,
 )
 
 
 def get_structure() -> AcceleratorTypeOfferingTypeDef:
@@ -350,43 +350,43 @@
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

### Comparing `types-aiobotocore-elastic-inference-2.5.0.post1/types_aiobotocore_elastic_inference.egg-info/SOURCES.txt` & `types-aiobotocore-elastic-inference-2.5.1/types_aiobotocore_elastic_inference.egg-info/SOURCES.txt`

 * *Files identical despite different names*

