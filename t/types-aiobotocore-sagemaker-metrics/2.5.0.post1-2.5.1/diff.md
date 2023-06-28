# Comparing `tmp/types-aiobotocore-sagemaker-metrics-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sagemaker-metrics-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sagemaker-metrics-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:16 2023, max compression
+gzip compressed data, was "types-aiobotocore-sagemaker-metrics-2.5.1.tar", last modified: Wed Jun 28 01:44:07 2023, max compression
```

## Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1.tar` & `types-aiobotocore-sagemaker-metrics-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.363589 types-aiobotocore-sagemaker-metrics-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12710 2023-03-11 12:27:16.355589 types-aiobotocore-sagemaker-metrics-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11100 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:16.363589 types-aiobotocore-sagemaker-metrics-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-03-11 12:23:32.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.351589 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/
--rw-r--r--   0 runner    (1001) docker     (123)      517 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      516 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4725 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     4716 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7998 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7996 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2042 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2039 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:33.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:16.355589 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12710 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:27:16.000000 types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.726208 types-aiobotocore-sagemaker-metrics-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12712 2023-06-28 01:44:07.726208 types-aiobotocore-sagemaker-metrics-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11108 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:07.726208 types-aiobotocore-sagemaker-metrics-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2203 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.726208 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/
+-rw-r--r--   0 runner    (1001) docker     (123)      517 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      516 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4725 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4716 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8302 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8300 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2044 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2041 2023-06-28 01:40:20.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:19.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:07.726208 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12712 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:44:07.000000 types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/LICENSE` & `types-aiobotocore-sagemaker-metrics-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sagemaker-metrics-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-metrics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SageMakerMetrics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SageMakerMetrics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-metrics"></a>
 
 # types-aiobotocore-sagemaker-metrics
 
 [![PyPI - types-aiobotocore-sagemaker-metrics](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-metrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-metrics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-metrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-metrics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-metrics?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-metrics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerMetrics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-metrics.html#SageMakerMetrics)
+[aiobotocore.SageMakerMetrics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-metrics.html#SageMakerMetrics)
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
 [types-aiobotocore-sagemaker-metrics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -293,59 +293,59 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_metrics.type_defs import (
     BatchPutMetricsErrorTypeDef,
     RawMetricDataTypeDef,
     ResponseMetadataTypeDef,
-    BatchPutMetricsRequestRequestTypeDef,
     BatchPutMetricsResponseTypeDef,
+    BatchPutMetricsRequestRequestTypeDef,
 )
 
 
 def get_structure() -> BatchPutMetricsErrorTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/README.md` & `types-aiobotocore-sagemaker-metrics-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sagemaker-metrics"></a>
 
 # types-aiobotocore-sagemaker-metrics
 
 [![PyPI - types-aiobotocore-sagemaker-metrics](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-metrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-metrics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-metrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-metrics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-metrics?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-metrics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerMetrics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-metrics.html#SageMakerMetrics)
+[aiobotocore.SageMakerMetrics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-metrics.html#SageMakerMetrics)
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
 [types-aiobotocore-sagemaker-metrics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -260,59 +260,59 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_metrics.type_defs import (
     BatchPutMetricsErrorTypeDef,
     RawMetricDataTypeDef,
     ResponseMetadataTypeDef,
-    BatchPutMetricsRequestRequestTypeDef,
     BatchPutMetricsResponseTypeDef,
+    BatchPutMetricsRequestRequestTypeDef,
 )
 
 
 def get_structure() -> BatchPutMetricsErrorTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/setup.py` & `types-aiobotocore-sagemaker-metrics-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sagemaker-metrics.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sagemaker-metrics",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sagemaker_metrics"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SageMakerMetrics 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SageMakerMetrics 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/"
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

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/__init__.py` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/__init__.pyi` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/__main__.py` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/__main__.py`

 * *Files 23% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SageMakerMetrics 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SageMakerMetrics 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-metrics.html#SageMakerMetrics\nOther"
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

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/client.py` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/client.pyi` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/literals.py` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -14,24 +14,22 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "PutMetricsErrorCodeType",
     "SageMakerMetricsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 PutMetricsErrorCodeType = Literal[
     "CONFLICT_ERROR", "INTERNAL_ERROR", "METRIC_LIMIT_EXCEEDED", "VALIDATION_ERROR"
 ]
 SageMakerMetricsServiceName = Literal["sagemaker-metrics"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -90,14 +88,15 @@
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
@@ -176,14 +175,15 @@
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
@@ -194,14 +194,15 @@
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
@@ -237,14 +238,15 @@
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
@@ -263,16 +265,19 @@
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
@@ -356,15 +361,17 @@
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
@@ -389,23 +396,28 @@
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
+    "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
```

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/literals.pyi` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,22 +14,24 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "PutMetricsErrorCodeType",
     "SageMakerMetricsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 PutMetricsErrorCodeType = Literal[
     "CONFLICT_ERROR", "INTERNAL_ERROR", "METRIC_LIMIT_EXCEEDED", "VALIDATION_ERROR"
 ]
 SageMakerMetricsServiceName = Literal["sagemaker-metrics"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -88,14 +90,15 @@
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
@@ -174,14 +177,15 @@
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
@@ -192,14 +196,15 @@
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
@@ -235,14 +240,15 @@
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
@@ -261,16 +267,19 @@
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
@@ -354,15 +363,17 @@
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
@@ -387,23 +398,28 @@
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
+    "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
```

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/type_defs.py` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -23,16 +23,16 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "BatchPutMetricsErrorTypeDef",
     "RawMetricDataTypeDef",
     "ResponseMetadataTypeDef",
-    "BatchPutMetricsRequestRequestTypeDef",
     "BatchPutMetricsResponseTypeDef",
+    "BatchPutMetricsRequestRequestTypeDef",
 )
 
 BatchPutMetricsErrorTypeDef = TypedDict(
     "BatchPutMetricsErrorTypeDef",
     {
         "Code": PutMetricsErrorCodeType,
         "MetricIndex": int,
@@ -68,22 +68,22 @@
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
         "RetryAttempts": int,
     },
 )
 
-BatchPutMetricsRequestRequestTypeDef = TypedDict(
-    "BatchPutMetricsRequestRequestTypeDef",
+BatchPutMetricsResponseTypeDef = TypedDict(
+    "BatchPutMetricsResponseTypeDef",
     {
-        "TrialComponentName": str,
-        "MetricData": Sequence[RawMetricDataTypeDef],
+        "Errors": List[BatchPutMetricsErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-BatchPutMetricsResponseTypeDef = TypedDict(
-    "BatchPutMetricsResponseTypeDef",
+BatchPutMetricsRequestRequestTypeDef = TypedDict(
+    "BatchPutMetricsRequestRequestTypeDef",
     {
-        "Errors": List[BatchPutMetricsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TrialComponentName": str,
+        "MetricData": Sequence[RawMetricDataTypeDef],
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics/type_defs.pyi` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics/type_defs.pyi`

 * *Files 18% similar despite different names*

```diff
@@ -22,16 +22,16 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "BatchPutMetricsErrorTypeDef",
     "RawMetricDataTypeDef",
     "ResponseMetadataTypeDef",
-    "BatchPutMetricsRequestRequestTypeDef",
     "BatchPutMetricsResponseTypeDef",
+    "BatchPutMetricsRequestRequestTypeDef",
 )
 
 BatchPutMetricsErrorTypeDef = TypedDict(
     "BatchPutMetricsErrorTypeDef",
     {
         "Code": PutMetricsErrorCodeType,
         "MetricIndex": int,
@@ -65,22 +65,22 @@
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
         "RetryAttempts": int,
     },
 )
 
-BatchPutMetricsRequestRequestTypeDef = TypedDict(
-    "BatchPutMetricsRequestRequestTypeDef",
+BatchPutMetricsResponseTypeDef = TypedDict(
+    "BatchPutMetricsResponseTypeDef",
     {
-        "TrialComponentName": str,
-        "MetricData": Sequence[RawMetricDataTypeDef],
+        "Errors": List[BatchPutMetricsErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-BatchPutMetricsResponseTypeDef = TypedDict(
-    "BatchPutMetricsResponseTypeDef",
+BatchPutMetricsRequestRequestTypeDef = TypedDict(
+    "BatchPutMetricsRequestRequestTypeDef",
     {
-        "Errors": List[BatchPutMetricsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "TrialComponentName": str,
+        "MetricData": Sequence[RawMetricDataTypeDef],
     },
 )
```

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/PKG-INFO` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sagemaker-metrics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SageMakerMetrics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SageMakerMetrics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sagemaker-metrics"></a>
 
 # types-aiobotocore-sagemaker-metrics
 
 [![PyPI - types-aiobotocore-sagemaker-metrics](https://img.shields.io/pypi/v/types-aiobotocore-sagemaker-metrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-metrics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sagemaker-metrics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sagemaker-metrics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sagemaker-metrics?color=blue)](https://pypistats.org/packages/types-aiobotocore-sagemaker-metrics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SageMakerMetrics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-metrics.html#SageMakerMetrics)
+[aiobotocore.SageMakerMetrics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sagemaker-metrics.html#SageMakerMetrics)
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
 [types-aiobotocore-sagemaker-metrics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sagemaker_metrics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -293,59 +293,59 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_sagemaker_metrics.type_defs import (
     BatchPutMetricsErrorTypeDef,
     RawMetricDataTypeDef,
     ResponseMetadataTypeDef,
-    BatchPutMetricsRequestRequestTypeDef,
     BatchPutMetricsResponseTypeDef,
+    BatchPutMetricsRequestRequestTypeDef,
 )
 
 
 def get_structure() -> BatchPutMetricsErrorTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-sagemaker-metrics-2.5.0.post1/types_aiobotocore_sagemaker_metrics.egg-info/SOURCES.txt` & `types-aiobotocore-sagemaker-metrics-2.5.1/types_aiobotocore_sagemaker_metrics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

