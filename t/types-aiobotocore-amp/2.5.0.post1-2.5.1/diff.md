# Comparing `tmp/types-aiobotocore-amp-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-amp-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-amp-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:07 2023, max compression
+gzip compressed data, was "types-aiobotocore-amp-2.5.1.tar", last modified: Wed Jun 28 01:43:01 2023, max compression
```

## Comparing `types-aiobotocore-amp-2.5.0.post1.tar` & `types-aiobotocore-amp-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.786903 types-aiobotocore-amp-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16400 2023-03-11 12:26:07.786903 types-aiobotocore-amp-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14831 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:07.786903 types-aiobotocore-amp-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2086 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.766903 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/
--rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1323 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      944 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18652 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18618 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8810 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8808 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3350 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3345 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    22736 2023-03-11 12:09:12.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    22691 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2493 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2491 2023-03-11 12:09:11.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.786903 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16400 2023-03-11 12:26:07.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:07.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:07.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:07.000000 types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.678085 types-aiobotocore-amp-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16388 2023-06-28 01:43:01.678085 types-aiobotocore-amp-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14825 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:01.678085 types-aiobotocore-amp-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2080 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.678085 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/
+-rw-r--r--   0 runner    (1001) docker     (123)     1324 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1323 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      932 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18652 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18618 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9093 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9091 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3230 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3226 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    22736 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22691 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2493 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2491 2023-06-28 01:25:48.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.678085 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16388 2023-06-28 01:43:01.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:01.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:01.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:01.000000 types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-amp-2.5.0.post1/LICENSE` & `types-aiobotocore-amp-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-amp-2.5.0.post1/PKG-INFO` & `types-aiobotocore-amp-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-amp
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PrometheusService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PrometheusService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-amp"></a>
 
 # types-aiobotocore-amp
 
 [![PyPI - types-aiobotocore-amp](https://img.shields.io/pypi/v/types-aiobotocore-amp.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amp)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-amp.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amp)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-amp?color=blue)](https://pypistats.org/packages/types-aiobotocore-amp)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PrometheusService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amp.html#PrometheusService)
+[aiobotocore.PrometheusService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amp.html#PrometheusService)
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
 [types-aiobotocore-amp docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/).
 
 See how it helps to find and fix potential bugs:
 
@@ -418,43 +418,43 @@
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

### Comparing `types-aiobotocore-amp-2.5.0.post1/README.md` & `types-aiobotocore-amp-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-amp"></a>
 
 # types-aiobotocore-amp
 
 [![PyPI - types-aiobotocore-amp](https://img.shields.io/pypi/v/types-aiobotocore-amp.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amp)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-amp.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amp)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-amp?color=blue)](https://pypistats.org/packages/types-aiobotocore-amp)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PrometheusService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amp.html#PrometheusService)
+[aiobotocore.PrometheusService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amp.html#PrometheusService)
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
 [types-aiobotocore-amp docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/).
 
 See how it helps to find and fix potential bugs:
 
@@ -385,43 +385,43 @@
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

### Comparing `types-aiobotocore-amp-2.5.0.post1/setup.py` & `types-aiobotocore-amp-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-amp.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-amp",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_amp"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.PrometheusService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.PrometheusService 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/",
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

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/__init__.py` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/__init__.pyi` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/__main__.py` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.PrometheusService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.PrometheusService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amp.html#PrometheusService\nOther"
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

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/client.py` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/client.pyi` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/literals.py` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -110,14 +110,15 @@
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
@@ -196,14 +197,15 @@
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
@@ -214,14 +216,15 @@
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
@@ -257,14 +260,15 @@
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
@@ -283,16 +287,19 @@
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
@@ -376,15 +383,17 @@
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
@@ -406,17 +415,21 @@
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_rule_groups_namespaces", "list_workspaces"]
 WaiterName = Literal["workspace_active", "workspace_deleted"]
 RegionName = Literal[
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
     "eu-west-2",
+    "eu-west-3",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/literals.pyi` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -108,14 +108,15 @@
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
@@ -194,14 +195,15 @@
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
@@ -212,14 +214,15 @@
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
@@ -255,14 +258,15 @@
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
@@ -281,16 +285,19 @@
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
@@ -374,15 +381,17 @@
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
@@ -404,17 +413,21 @@
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_rule_groups_namespaces", "list_workspaces"]
 WaiterName = Literal["workspace_active", "workspace_deleted"]
 RegionName = Literal[
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
     "eu-west-2",
+    "eu-west-3",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/paginator.py` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -18,32 +18,25 @@
     with session.create_client("amp") as client:
         client: PrometheusServiceClient
 
         list_rule_groups_namespaces_paginator: ListRuleGroupsNamespacesPaginator = client.get_paginator("list_rule_groups_namespaces")
         list_workspaces_paginator: ListWorkspacesPaginator = client.get_paginator("list_workspaces")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListRuleGroupsNamespacesResponseTypeDef,
     ListWorkspacesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListRuleGroupsNamespacesPaginator", "ListWorkspacesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
```

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/paginator.pyi` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -18,31 +18,25 @@
     with session.create_client("amp") as client:
         client: PrometheusServiceClient
 
         list_rule_groups_namespaces_paginator: ListRuleGroupsNamespacesPaginator = client.get_paginator("list_rule_groups_namespaces")
         list_workspaces_paginator: ListWorkspacesPaginator = client.get_paginator("list_workspaces")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListRuleGroupsNamespacesResponseTypeDef,
     ListWorkspacesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListRuleGroupsNamespacesPaginator", "ListWorkspacesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
```

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/type_defs.py` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/type_defs.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/type_defs.pyi` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/type_defs.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/waiter.py` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp/waiter.pyi` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/PKG-INFO` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-amp
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PrometheusService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PrometheusService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-amp"></a>
 
 # types-aiobotocore-amp
 
 [![PyPI - types-aiobotocore-amp](https://img.shields.io/pypi/v/types-aiobotocore-amp.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amp)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-amp.svg?color=blue)](https://pypi.org/project/types-aiobotocore-amp)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-amp?color=blue)](https://pypistats.org/packages/types-aiobotocore-amp)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PrometheusService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amp.html#PrometheusService)
+[aiobotocore.PrometheusService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/amp.html#PrometheusService)
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
 [types-aiobotocore-amp docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_amp/).
 
 See how it helps to find and fix potential bugs:
 
@@ -418,43 +418,43 @@
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

### Comparing `types-aiobotocore-amp-2.5.0.post1/types_aiobotocore_amp.egg-info/SOURCES.txt` & `types-aiobotocore-amp-2.5.1/types_aiobotocore_amp.egg-info/SOURCES.txt`

 * *Files identical despite different names*

