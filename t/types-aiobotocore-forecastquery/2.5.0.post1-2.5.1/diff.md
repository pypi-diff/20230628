# Comparing `tmp/types-aiobotocore-forecastquery-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-forecastquery-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-forecastquery-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:39 2023, max compression
+gzip compressed data, was "types-aiobotocore-forecastquery-2.5.1.tar", last modified: Wed Jun 28 01:43:31 2023, max compression
```

## Comparing `types-aiobotocore-forecastquery-2.5.0.post1.tar` & `types-aiobotocore-forecastquery-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.431224 types-aiobotocore-forecastquery-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12612 2023-03-11 12:26:39.427224 types-aiobotocore-forecastquery-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11010 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:39.431224 types-aiobotocore-forecastquery-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.423224 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/
--rw-r--r--   0 runner    (1001) docker     (123)      525 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      524 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5751 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5741 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7610 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7608 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2812 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2807 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:45.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.427224 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12612 2023-03-11 12:26:39.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      836 2023-03-11 12:26:39.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:39.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:39.000000 types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.494140 types-aiobotocore-forecastquery-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12610 2023-06-28 01:43:31.494140 types-aiobotocore-forecastquery-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11014 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:31.494140 types-aiobotocore-forecastquery-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.486140 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/
+-rw-r--r--   0 runner    (1001) docker     (123)      525 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      524 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5751 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5741 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7819 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7817 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2816 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2811 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:21.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.494140 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12610 2023-06-28 01:43:31.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-28 01:43:31.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:31.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:31.000000 types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/LICENSE` & `types-aiobotocore-forecastquery-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/PKG-INFO` & `types-aiobotocore-forecastquery-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-forecastquery
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ForecastQueryService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ForecastQueryService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-forecastquery"></a>
 
 # types-aiobotocore-forecastquery
 
 [![PyPI - types-aiobotocore-forecastquery](https://img.shields.io/pypi/v/types-aiobotocore-forecastquery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-forecastquery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-forecastquery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-forecastquery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-forecastquery?color=blue)](https://pypistats.org/packages/types-aiobotocore-forecastquery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ForecastQueryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html#ForecastQueryService)
+[aiobotocore.ForecastQueryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html#ForecastQueryService)
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
 [types-aiobotocore-forecastquery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,16 +291,16 @@
 `types_aiobotocore_forecastquery.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_forecastquery.type_defs import (
     DataPointTypeDef,
     QueryForecastRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     QueryWhatIfForecastRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ForecastTypeDef,
     QueryForecastResponseTypeDef,
     QueryWhatIfForecastResponseTypeDef,
 )
 
 
 def get_structure() -> DataPointTypeDef:
@@ -310,43 +310,43 @@
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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/README.md` & `types-aiobotocore-forecastquery-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-forecastquery"></a>
 
 # types-aiobotocore-forecastquery
 
 [![PyPI - types-aiobotocore-forecastquery](https://img.shields.io/pypi/v/types-aiobotocore-forecastquery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-forecastquery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-forecastquery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-forecastquery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-forecastquery?color=blue)](https://pypistats.org/packages/types-aiobotocore-forecastquery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ForecastQueryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html#ForecastQueryService)
+[aiobotocore.ForecastQueryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html#ForecastQueryService)
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
 [types-aiobotocore-forecastquery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -258,16 +258,16 @@
 `types_aiobotocore_forecastquery.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_forecastquery.type_defs import (
     DataPointTypeDef,
     QueryForecastRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     QueryWhatIfForecastRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ForecastTypeDef,
     QueryForecastResponseTypeDef,
     QueryWhatIfForecastResponseTypeDef,
 )
 
 
 def get_structure() -> DataPointTypeDef:
@@ -277,43 +277,43 @@
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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/setup.py` & `types-aiobotocore-forecastquery-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-forecastquery.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-forecastquery",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_forecastquery"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ForecastQueryService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ForecastQueryService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/"
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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/__init__.py` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/__init__.pyi` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/__main__.py` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ForecastQueryService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ForecastQueryService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html#ForecastQueryService\nOther"
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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/client.py` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/client.pyi` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/literals.py` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -81,14 +81,15 @@
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
@@ -167,14 +168,15 @@
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
@@ -185,14 +187,15 @@
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
@@ -228,14 +231,15 @@
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
@@ -254,16 +258,19 @@
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
@@ -347,15 +354,17 @@
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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/literals.pyi` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -79,14 +79,15 @@
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
@@ -165,14 +166,15 @@
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
@@ -183,14 +185,15 @@
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
@@ -226,14 +229,15 @@
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
@@ -252,16 +256,19 @@
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
@@ -345,15 +352,17 @@
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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/type_defs.py` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "DataPointTypeDef",
     "QueryForecastRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "QueryWhatIfForecastRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ForecastTypeDef",
     "QueryForecastResponseTypeDef",
     "QueryWhatIfForecastResponseTypeDef",
 )
 
 DataPointTypeDef = TypedDict(
     "DataPointTypeDef",
@@ -59,25 +59,14 @@
 
 class QueryForecastRequestRequestTypeDef(
     _RequiredQueryForecastRequestRequestTypeDef, _OptionalQueryForecastRequestRequestTypeDef
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
 _RequiredQueryWhatIfForecastRequestRequestTypeDef = TypedDict(
     "_RequiredQueryWhatIfForecastRequestRequestTypeDef",
     {
         "WhatIfForecastArn": str,
         "Filters": Mapping[str, str],
     },
 )
@@ -95,30 +84,41 @@
 class QueryWhatIfForecastRequestRequestTypeDef(
     _RequiredQueryWhatIfForecastRequestRequestTypeDef,
     _OptionalQueryWhatIfForecastRequestRequestTypeDef,
 ):
     pass
 
 
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
 ForecastTypeDef = TypedDict(
     "ForecastTypeDef",
     {
         "Predictions": Dict[str, List[DataPointTypeDef]],
     },
     total=False,
 )
 
 QueryForecastResponseTypeDef = TypedDict(
     "QueryForecastResponseTypeDef",
     {
         "Forecast": ForecastTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryWhatIfForecastResponseTypeDef = TypedDict(
     "QueryWhatIfForecastResponseTypeDef",
     {
         "Forecast": ForecastTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery/type_defs.pyi` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -18,16 +18,16 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "DataPointTypeDef",
     "QueryForecastRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "QueryWhatIfForecastRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ForecastTypeDef",
     "QueryForecastResponseTypeDef",
     "QueryWhatIfForecastResponseTypeDef",
 )
 
 DataPointTypeDef = TypedDict(
     "DataPointTypeDef",
@@ -56,25 +56,14 @@
 )
 
 class QueryForecastRequestRequestTypeDef(
     _RequiredQueryForecastRequestRequestTypeDef, _OptionalQueryForecastRequestRequestTypeDef
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
 _RequiredQueryWhatIfForecastRequestRequestTypeDef = TypedDict(
     "_RequiredQueryWhatIfForecastRequestRequestTypeDef",
     {
         "WhatIfForecastArn": str,
         "Filters": Mapping[str, str],
     },
 )
@@ -90,30 +79,41 @@
 
 class QueryWhatIfForecastRequestRequestTypeDef(
     _RequiredQueryWhatIfForecastRequestRequestTypeDef,
     _OptionalQueryWhatIfForecastRequestRequestTypeDef,
 ):
     pass
 
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
 ForecastTypeDef = TypedDict(
     "ForecastTypeDef",
     {
         "Predictions": Dict[str, List[DataPointTypeDef]],
     },
     total=False,
 )
 
 QueryForecastResponseTypeDef = TypedDict(
     "QueryForecastResponseTypeDef",
     {
         "Forecast": ForecastTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryWhatIfForecastResponseTypeDef = TypedDict(
     "QueryWhatIfForecastResponseTypeDef",
     {
         "Forecast": ForecastTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/PKG-INFO` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-forecastquery
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ForecastQueryService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ForecastQueryService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-forecastquery"></a>
 
 # types-aiobotocore-forecastquery
 
 [![PyPI - types-aiobotocore-forecastquery](https://img.shields.io/pypi/v/types-aiobotocore-forecastquery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-forecastquery)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-forecastquery.svg?color=blue)](https://pypi.org/project/types-aiobotocore-forecastquery)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-forecastquery?color=blue)](https://pypistats.org/packages/types-aiobotocore-forecastquery)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ForecastQueryService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html#ForecastQueryService)
+[aiobotocore.ForecastQueryService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html#ForecastQueryService)
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
 [types-aiobotocore-forecastquery docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_forecastquery/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,16 +291,16 @@
 `types_aiobotocore_forecastquery.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_forecastquery.type_defs import (
     DataPointTypeDef,
     QueryForecastRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     QueryWhatIfForecastRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     ForecastTypeDef,
     QueryForecastResponseTypeDef,
     QueryWhatIfForecastResponseTypeDef,
 )
 
 
 def get_structure() -> DataPointTypeDef:
@@ -310,43 +310,43 @@
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

### Comparing `types-aiobotocore-forecastquery-2.5.0.post1/types_aiobotocore_forecastquery.egg-info/SOURCES.txt` & `types-aiobotocore-forecastquery-2.5.1/types_aiobotocore_forecastquery.egg-info/SOURCES.txt`

 * *Files identical despite different names*

