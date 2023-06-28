# Comparing `tmp/types-aiobotocore-accessanalyzer-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-accessanalyzer-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-accessanalyzer-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:07 2023, max compression
+gzip compressed data, was "types-aiobotocore-accessanalyzer-2.5.1.tar", last modified: Wed Jun 28 01:43:01 2023, max compression
```

## Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1.tar` & `types-aiobotocore-accessanalyzer-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.790904 types-aiobotocore-accessanalyzer-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19227 2023-03-11 12:26:07.786903 types-aiobotocore-accessanalyzer-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17628 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:07.790904 types-aiobotocore-accessanalyzer-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.782904 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/
--rw-r--r--   0 runner    (1001) docker     (123)     2237 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2236 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26597 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    26552 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11842 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11840 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11071 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11060 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    42687 2023-03-11 12:09:03.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    42608 2023-03-11 12:09:03.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:02.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.786903 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19227 2023-03-11 12:26:07.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:26:07.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:07.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:07.000000 types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.702085 types-aiobotocore-accessanalyzer-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19226 2023-06-28 01:43:01.694085 types-aiobotocore-accessanalyzer-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17633 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:01.702085 types-aiobotocore-accessanalyzer-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.690085 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/
+-rw-r--r--   0 runner    (1001) docker     (123)     2237 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2236 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26596 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26551 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12051 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12049 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10951 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10941 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    42687 2023-06-28 01:25:40.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42608 2023-06-28 01:25:40.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:39.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.694085 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19226 2023-06-28 01:43:01.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:01.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:01.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:01.000000 types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/LICENSE` & `types-aiobotocore-accessanalyzer-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/PKG-INFO` & `types-aiobotocore-accessanalyzer-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-accessanalyzer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AccessAnalyzer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AccessAnalyzer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-accessanalyzer"></a>
 
 # types-aiobotocore-accessanalyzer
 
 [![PyPI - types-aiobotocore-accessanalyzer](https://img.shields.io/pypi/v/types-aiobotocore-accessanalyzer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-accessanalyzer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-accessanalyzer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-accessanalyzer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-accessanalyzer?color=blue)](https://pypistats.org/packages/types-aiobotocore-accessanalyzer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AccessAnalyzer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer)
+[aiobotocore.AccessAnalyzer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer)
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
 [types-aiobotocore-accessanalyzer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -492,43 +492,43 @@
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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/README.md` & `types-aiobotocore-accessanalyzer-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-accessanalyzer"></a>
 
 # types-aiobotocore-accessanalyzer
 
 [![PyPI - types-aiobotocore-accessanalyzer](https://img.shields.io/pypi/v/types-aiobotocore-accessanalyzer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-accessanalyzer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-accessanalyzer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-accessanalyzer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-accessanalyzer?color=blue)](https://pypistats.org/packages/types-aiobotocore-accessanalyzer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AccessAnalyzer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer)
+[aiobotocore.AccessAnalyzer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer)
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
 [types-aiobotocore-accessanalyzer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -459,43 +459,43 @@
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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/setup.py` & `types-aiobotocore-accessanalyzer-2.5.1/setup.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-accessanalyzer.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-accessanalyzer",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_accessanalyzer"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AccessAnalyzer 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AccessAnalyzer 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/"
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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/__init__.py` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/__init__.pyi` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/__main__.py` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AccessAnalyzer 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AccessAnalyzer 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer\nOther"
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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/client.py` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -276,15 +276,15 @@
         self,
         *,
         jobId: str,
         includeResourcePlaceholders: bool = ...,
         includeServiceLevelTemplate: bool = ...
     ) -> GetGeneratedPolicyResponseTypeDef:
         """
-        Retrieves the policy that was generated using `StartPolicyGeneration` .
+        Retrieves the policy that was generated using `StartPolicyGeneration`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_generated_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/client/#get_generated_policy)
         """
 
     async def list_access_preview_findings(
         self,
```

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/client.pyi` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -256,15 +256,15 @@
         self,
         *,
         jobId: str,
         includeResourcePlaceholders: bool = ...,
         includeServiceLevelTemplate: bool = ...
     ) -> GetGeneratedPolicyResponseTypeDef:
         """
-        Retrieves the policy that was generated using `StartPolicyGeneration` .
+        Retrieves the policy that was generated using `StartPolicyGeneration`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer.Client.get_generated_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/client/#get_generated_policy)
         """
     async def list_access_preview_findings(
         self,
         *,
```

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/literals.py` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AccessPreviewStatusReasonCodeType",
     "AccessPreviewStatusType",
     "AclPermissionType",
     "AnalyzerStatusType",
     "FindingChangeTypeType",
     "FindingSourceTypeType",
@@ -50,15 +49,14 @@
     "AccessAnalyzerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 AccessPreviewStatusReasonCodeType = Literal["INTERNAL_ERROR", "INVALID_CONFIGURATION"]
 AccessPreviewStatusType = Literal["COMPLETED", "CREATING", "FAILED"]
 AclPermissionType = Literal["FULL_CONTROL", "READ", "READ_ACP", "WRITE", "WRITE_ACP"]
 AnalyzerStatusType = Literal["ACTIVE", "CREATING", "DISABLED", "FAILED"]
 FindingChangeTypeType = Literal["CHANGED", "NEW", "UNCHANGED"]
 FindingSourceTypeType = Literal[
     "BUCKET_ACL", "POLICY", "S3_ACCESS_POINT", "S3_ACCESS_POINT_ACCOUNT"
@@ -188,14 +186,15 @@
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
@@ -274,14 +273,15 @@
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
@@ -292,14 +292,15 @@
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
@@ -335,14 +336,15 @@
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
@@ -361,16 +363,19 @@
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
@@ -454,15 +459,17 @@
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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/literals.pyi` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AccessPreviewStatusReasonCodeType",
     "AccessPreviewStatusType",
     "AclPermissionType",
     "AnalyzerStatusType",
     "FindingChangeTypeType",
     "FindingSourceTypeType",
@@ -49,14 +50,15 @@
     "AccessAnalyzerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 AccessPreviewStatusReasonCodeType = Literal["INTERNAL_ERROR", "INVALID_CONFIGURATION"]
 AccessPreviewStatusType = Literal["COMPLETED", "CREATING", "FAILED"]
 AclPermissionType = Literal["FULL_CONTROL", "READ", "READ_ACP", "WRITE", "WRITE_ACP"]
 AnalyzerStatusType = Literal["ACTIVE", "CREATING", "DISABLED", "FAILED"]
 FindingChangeTypeType = Literal["CHANGED", "NEW", "UNCHANGED"]
 FindingSourceTypeType = Literal[
     "BUCKET_ACL", "POLICY", "S3_ACCESS_POINT", "S3_ACCESS_POINT_ACCOUNT"
@@ -186,14 +188,15 @@
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
@@ -272,14 +275,15 @@
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
@@ -290,14 +294,15 @@
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
@@ -333,14 +338,15 @@
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
@@ -359,16 +365,19 @@
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
@@ -452,15 +461,17 @@
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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/paginator.py` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_analyzers_paginator: ListAnalyzersPaginator = client.get_paginator("list_analyzers")
         list_archive_rules_paginator: ListArchiveRulesPaginator = client.get_paginator("list_archive_rules")
         list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
         list_policy_generations_paginator: ListPolicyGenerationsPaginator = client.get_paginator("list_policy_generations")
         validate_policy_paginator: ValidatePolicyPaginator = client.get_paginator("validate_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     LocaleType,
     PolicyTypeType,
@@ -57,20 +56,14 @@
     ListFindingsResponseTypeDef,
     ListPolicyGenerationsResponseTypeDef,
     PaginatorConfigTypeDef,
     SortCriteriaTypeDef,
     ValidatePolicyResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAccessPreviewFindingsPaginator",
     "ListAccessPreviewsPaginator",
     "ListAnalyzedResourcesPaginator",
     "ListAnalyzersPaginator",
     "ListArchiveRulesPaginator",
     "ListFindingsPaginator",
```

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/paginator.pyi` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -30,16 +30,15 @@
         list_analyzers_paginator: ListAnalyzersPaginator = client.get_paginator("list_analyzers")
         list_archive_rules_paginator: ListArchiveRulesPaginator = client.get_paginator("list_archive_rules")
         list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
         list_policy_generations_paginator: ListPolicyGenerationsPaginator = client.get_paginator("list_policy_generations")
         validate_policy_paginator: ValidatePolicyPaginator = client.get_paginator("validate_policy")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     LocaleType,
     PolicyTypeType,
@@ -57,19 +56,14 @@
     ListFindingsResponseTypeDef,
     ListPolicyGenerationsResponseTypeDef,
     PaginatorConfigTypeDef,
     SortCriteriaTypeDef,
     ValidatePolicyResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAccessPreviewFindingsPaginator",
     "ListAccessPreviewsPaginator",
     "ListAnalyzedResourcesPaginator",
     "ListAnalyzersPaginator",
     "ListArchiveRulesPaginator",
     "ListFindingsPaginator",
```

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/type_defs.py` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/type_defs.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer/type_defs.pyi` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer/type_defs.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/PKG-INFO` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-accessanalyzer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AccessAnalyzer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AccessAnalyzer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-accessanalyzer"></a>
 
 # types-aiobotocore-accessanalyzer
 
 [![PyPI - types-aiobotocore-accessanalyzer](https://img.shields.io/pypi/v/types-aiobotocore-accessanalyzer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-accessanalyzer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-accessanalyzer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-accessanalyzer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-accessanalyzer?color=blue)](https://pypistats.org/packages/types-aiobotocore-accessanalyzer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AccessAnalyzer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer)
+[aiobotocore.AccessAnalyzer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/accessanalyzer.html#AccessAnalyzer)
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
 [types-aiobotocore-accessanalyzer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_accessanalyzer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -492,43 +492,43 @@
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

### Comparing `types-aiobotocore-accessanalyzer-2.5.0.post1/types_aiobotocore_accessanalyzer.egg-info/SOURCES.txt` & `types-aiobotocore-accessanalyzer-2.5.1/types_aiobotocore_accessanalyzer.egg-info/SOURCES.txt`

 * *Files identical despite different names*

