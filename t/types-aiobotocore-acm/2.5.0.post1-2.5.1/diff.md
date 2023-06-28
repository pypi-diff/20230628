# Comparing `tmp/types-aiobotocore-acm-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-acm-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-acm-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:07 2023, max compression
+gzip compressed data, was "types-aiobotocore-acm-2.5.1.tar", last modified: Wed Jun 28 01:43:01 2023, max compression
```

## Comparing `types-aiobotocore-acm-2.5.0.post1.tar` & `types-aiobotocore-acm-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.786903 types-aiobotocore-acm-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15243 2023-03-11 12:26:07.786903 types-aiobotocore-acm-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13688 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:07.786903 types-aiobotocore-acm-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.782904 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/
--rw-r--r--   0 runner    (1001) docker     (123)      847 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      846 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15082 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15056 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10729 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10727 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2475 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2471 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    14802 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    14787 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1532 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-03-11 12:09:05.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.782904 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15243 2023-03-11 12:26:07.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:07.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:07.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:07.000000 types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.682085 types-aiobotocore-acm-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15231 2023-06-28 01:43:01.682085 types-aiobotocore-acm-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13682 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:01.682085 types-aiobotocore-acm-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.682085 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/
+-rw-r--r--   0 runner    (1001) docker     (123)      847 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      846 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15082 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15056 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10938 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10936 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2368 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2364 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    14802 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14787 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1532 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1531 2023-06-28 01:25:42.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.682085 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15231 2023-06-28 01:43:01.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:01.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:01.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:01.000000 types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-acm-2.5.0.post1/LICENSE` & `types-aiobotocore-acm-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-acm-2.5.0.post1/PKG-INFO` & `types-aiobotocore-acm-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-acm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ACM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ACM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-acm"></a>
 
 # types-aiobotocore-acm
 
 [![PyPI - types-aiobotocore-acm](https://img.shields.io/pypi/v/types-aiobotocore-acm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-acm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-acm?color=blue)](https://pypistats.org/packages/types-aiobotocore-acm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ACM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM)
+[aiobotocore.ACM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM)
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
 [types-aiobotocore-acm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -410,43 +410,43 @@
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

### Comparing `types-aiobotocore-acm-2.5.0.post1/README.md` & `types-aiobotocore-acm-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-acm"></a>
 
 # types-aiobotocore-acm
 
 [![PyPI - types-aiobotocore-acm](https://img.shields.io/pypi/v/types-aiobotocore-acm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-acm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-acm?color=blue)](https://pypistats.org/packages/types-aiobotocore-acm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ACM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM)
+[aiobotocore.ACM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM)
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
 [types-aiobotocore-acm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -377,43 +377,43 @@
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

### Comparing `types-aiobotocore-acm-2.5.0.post1/setup.py` & `types-aiobotocore-acm-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-acm.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-acm",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_acm"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ACM 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.ACM 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/",
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

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/__init__.py` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/__init__.pyi` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/__main__.py` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/__main__.py`

 * *Files 11% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ACM 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ACM 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM\nOther"
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

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/client.py` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/client.pyi` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/literals.py` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/literals.pyi`

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
     "CertificateStatusType",
     "CertificateTransparencyLoggingPreferenceType",
     "CertificateTypeType",
     "CertificateValidatedWaiterName",
     "DomainStatusType",
     "ExtendedKeyUsageNameType",
@@ -41,15 +40,14 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
-
 CertificateStatusType = Literal[
     "EXPIRED",
     "FAILED",
     "INACTIVE",
     "ISSUED",
     "PENDING_VALIDATION",
     "REVOKED",
@@ -186,14 +184,15 @@
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
@@ -272,14 +271,15 @@
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
@@ -290,14 +290,15 @@
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
@@ -333,14 +334,15 @@
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
@@ -359,16 +361,19 @@
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
@@ -452,15 +457,17 @@
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

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/literals.pyi` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/literals.py`

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
     "CertificateStatusType",
     "CertificateTransparencyLoggingPreferenceType",
     "CertificateTypeType",
     "CertificateValidatedWaiterName",
     "DomainStatusType",
     "ExtendedKeyUsageNameType",
@@ -40,14 +41,15 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
+
 CertificateStatusType = Literal[
     "EXPIRED",
     "FAILED",
     "INACTIVE",
     "ISSUED",
     "PENDING_VALIDATION",
     "REVOKED",
@@ -184,14 +186,15 @@
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
@@ -270,14 +273,15 @@
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
@@ -288,14 +292,15 @@
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
@@ -331,14 +336,15 @@
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
@@ -357,16 +363,19 @@
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
@@ -450,15 +459,17 @@
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

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/paginator.py` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -17,45 +17,37 @@
     with session.create_client("acm") as client:
         client: ACMClient
 
         list_certificates_paginator: ListCertificatesPaginator = client.get_paginator("list_certificates")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import CertificateStatusType, SortOrderType
 from .type_defs import FiltersTypeDef, ListCertificatesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("ListCertificatesPaginator",)
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/paginators/#listcertificatespaginator)
     """
 
     def paginate(
```

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/paginator.pyi` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -17,41 +17,41 @@
     with session.create_client("acm") as client:
         client: ACMClient
 
         list_certificates_paginator: ListCertificatesPaginator = client.get_paginator("list_certificates")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import CertificateStatusType, SortOrderType
 from .type_defs import FiltersTypeDef, ListCertificatesResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("ListCertificatesPaginator",)
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListCertificatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM.Paginator.ListCertificates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/paginators/#listcertificatespaginator)
     """
 
     def paginate(
```

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/type_defs.py` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/type_defs.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/type_defs.pyi` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/type_defs.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/waiter.py` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm/waiter.pyi` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/PKG-INFO` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-acm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ACM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ACM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-acm"></a>
 
 # types-aiobotocore-acm
 
 [![PyPI - types-aiobotocore-acm](https://img.shields.io/pypi/v/types-aiobotocore-acm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-acm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-acm?color=blue)](https://pypistats.org/packages/types-aiobotocore-acm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ACM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM)
+[aiobotocore.ACM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm.html#ACM)
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
 [types-aiobotocore-acm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -410,43 +410,43 @@
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

### Comparing `types-aiobotocore-acm-2.5.0.post1/types_aiobotocore_acm.egg-info/SOURCES.txt` & `types-aiobotocore-acm-2.5.1/types_aiobotocore_acm.egg-info/SOURCES.txt`

 * *Files identical despite different names*

