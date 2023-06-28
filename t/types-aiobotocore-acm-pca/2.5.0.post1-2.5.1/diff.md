# Comparing `tmp/types-aiobotocore-acm-pca-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-acm-pca-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-acm-pca-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:07 2023, max compression
+gzip compressed data, was "types-aiobotocore-acm-pca-2.5.1.tar", last modified: Wed Jun 28 01:43:01 2023, max compression
```

## Comparing `types-aiobotocore-acm-pca-2.5.0.post1.tar` & `types-aiobotocore-acm-pca-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.786903 types-aiobotocore-acm-pca-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17641 2023-03-11 12:26:07.782904 types-aiobotocore-acm-pca-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16071 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:07.786903 types-aiobotocore-acm-pca-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2123 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.782904 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/
--rw-r--r--   0 runner    (1001) docker     (123)     1775 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1774 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      941 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24004 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23966 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10932 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10930 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4461 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4455 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    27365 2023-03-11 12:09:07.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    27322 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     3816 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     3813 2023-03-11 12:09:06.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.782904 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17641 2023-03-11 12:26:07.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      886 2023-03-11 12:26:07.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:07.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:07.000000 types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.682085 types-aiobotocore-acm-pca-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17633 2023-06-28 01:43:01.682085 types-aiobotocore-acm-pca-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16069 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:01.682085 types-aiobotocore-acm-pca-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.678085 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/
+-rw-r--r--   0 runner    (1001) docker     (123)     1775 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1774 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      929 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24003 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23965 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11219 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11217 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4341 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4336 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    27365 2023-06-28 01:25:44.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27322 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3816 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3813 2023-06-28 01:25:43.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.682085 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17633 2023-06-28 01:43:01.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      886 2023-06-28 01:43:01.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:01.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:01.000000 types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/LICENSE` & `types-aiobotocore-acm-pca-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/PKG-INFO` & `types-aiobotocore-acm-pca-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-acm-pca
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ACMPCA 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ACMPCA 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-acm-pca"></a>
 
 # types-aiobotocore-acm-pca
 
 [![PyPI - types-aiobotocore-acm-pca](https://img.shields.io/pypi/v/types-aiobotocore-acm-pca.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm-pca)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-acm-pca.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm-pca)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-acm-pca?color=blue)](https://pypistats.org/packages/types-aiobotocore-acm-pca)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ACMPCA 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA)
+[aiobotocore.ACMPCA 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA)
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
 [types-aiobotocore-acm-pca docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/).
 
 See how it helps to find and fix potential bugs:
 
@@ -460,43 +460,43 @@
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

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/README.md` & `types-aiobotocore-acm-pca-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-acm-pca"></a>
 
 # types-aiobotocore-acm-pca
 
 [![PyPI - types-aiobotocore-acm-pca](https://img.shields.io/pypi/v/types-aiobotocore-acm-pca.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm-pca)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-acm-pca.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm-pca)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-acm-pca?color=blue)](https://pypistats.org/packages/types-aiobotocore-acm-pca)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ACMPCA 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA)
+[aiobotocore.ACMPCA 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA)
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
 [types-aiobotocore-acm-pca docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/).
 
 See how it helps to find and fix potential bugs:
 
@@ -427,43 +427,43 @@
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

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/setup.py` & `types-aiobotocore-acm-pca-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-acm-pca.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-acm-pca",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_acm_pca"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ACMPCA 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.ACMPCA 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/"
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

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/__init__.py` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/__init__.pyi` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/__main__.py` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ACMPCA 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ACMPCA 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA\nOther"
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

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/client.py` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -174,15 +174,15 @@
         CertificateAuthorityArn: str,
         Principal: str,
         Actions: Sequence[ActionTypeType],
         SourceAccount: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Grants one or more permissions on a private CA to the Certificate Manager (ACM)
-        service principal ( `acm.amazonaws.com` ).
+        service principal ( `acm.amazonaws.com`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA.Client.create_permission)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/client/#create_permission)
         """
 
     async def delete_certificate_authority(
         self, *, CertificateAuthorityArn: str, PermanentDeletionTimeInDays: int = ...
```

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/client.pyi` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -165,15 +165,15 @@
         CertificateAuthorityArn: str,
         Principal: str,
         Actions: Sequence[ActionTypeType],
         SourceAccount: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Grants one or more permissions on a private CA to the Certificate Manager (ACM)
-        service principal ( `acm.amazonaws.com` ).
+        service principal ( `acm.amazonaws.com`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA.Client.create_permission)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/client/#create_permission)
         """
     async def delete_certificate_authority(
         self, *, CertificateAuthorityArn: str, PermanentDeletionTimeInDays: int = ...
     ) -> EmptyResponseMetadataTypeDef:
```

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/literals.py` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AccessMethodTypeType",
     "ActionTypeType",
     "AuditReportCreatedWaiterName",
     "AuditReportResponseFormatType",
     "AuditReportStatusType",
     "CertificateAuthorityCSRCreatedWaiterName",
@@ -47,15 +46,14 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
-
 AccessMethodTypeType = Literal["CA_REPOSITORY", "RESOURCE_PKI_MANIFEST", "RESOURCE_PKI_NOTIFY"]
 ActionTypeType = Literal["GetCertificate", "IssueCertificate", "ListPermissions"]
 AuditReportCreatedWaiterName = Literal["audit_report_created"]
 AuditReportResponseFormatType = Literal["CSV", "JSON"]
 AuditReportStatusType = Literal["CREATING", "FAILED", "SUCCESS"]
 CertificateAuthorityCSRCreatedWaiterName = Literal["certificate_authority_csr_created"]
 CertificateAuthorityStatusType = Literal[
@@ -164,14 +162,15 @@
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
@@ -250,14 +249,15 @@
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
@@ -268,14 +268,15 @@
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
@@ -311,14 +312,15 @@
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
@@ -337,16 +339,19 @@
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
@@ -430,15 +435,17 @@
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
@@ -467,21 +474,25 @@
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
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/literals.pyi` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/literals.py`

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
     "AccessMethodTypeType",
     "ActionTypeType",
     "AuditReportCreatedWaiterName",
     "AuditReportResponseFormatType",
     "AuditReportStatusType",
     "CertificateAuthorityCSRCreatedWaiterName",
@@ -46,14 +47,15 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
+
 AccessMethodTypeType = Literal["CA_REPOSITORY", "RESOURCE_PKI_MANIFEST", "RESOURCE_PKI_NOTIFY"]
 ActionTypeType = Literal["GetCertificate", "IssueCertificate", "ListPermissions"]
 AuditReportCreatedWaiterName = Literal["audit_report_created"]
 AuditReportResponseFormatType = Literal["CSV", "JSON"]
 AuditReportStatusType = Literal["CREATING", "FAILED", "SUCCESS"]
 CertificateAuthorityCSRCreatedWaiterName = Literal["certificate_authority_csr_created"]
 CertificateAuthorityStatusType = Literal[
@@ -162,14 +164,15 @@
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
@@ -248,14 +251,15 @@
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
@@ -266,14 +270,15 @@
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
@@ -309,14 +314,15 @@
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
@@ -335,16 +341,19 @@
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
@@ -428,15 +437,17 @@
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
@@ -465,21 +476,25 @@
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
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/paginator.py` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -20,34 +20,27 @@
         client: ACMPCAClient
 
         list_certificate_authorities_paginator: ListCertificateAuthoritiesPaginator = client.get_paginator("list_certificate_authorities")
         list_permissions_paginator: ListPermissionsPaginator = client.get_paginator("list_permissions")
         list_tags_paginator: ListTagsPaginator = client.get_paginator("list_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceOwnerType
 from .type_defs import (
     ListCertificateAuthoritiesResponseTypeDef,
     ListPermissionsResponseTypeDef,
     ListTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListCertificateAuthoritiesPaginator", "ListPermissionsPaginator", "ListTagsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
```

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/paginator.pyi` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,33 +20,27 @@
         client: ACMPCAClient
 
         list_certificate_authorities_paginator: ListCertificateAuthoritiesPaginator = client.get_paginator("list_certificate_authorities")
         list_permissions_paginator: ListPermissionsPaginator = client.get_paginator("list_permissions")
         list_tags_paginator: ListTagsPaginator = client.get_paginator("list_tags")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceOwnerType
 from .type_defs import (
     ListCertificateAuthoritiesResponseTypeDef,
     ListPermissionsResponseTypeDef,
     ListTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListCertificateAuthoritiesPaginator", "ListPermissionsPaginator", "ListTagsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
```

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/type_defs.py` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/type_defs.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/type_defs.pyi` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/type_defs.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/waiter.py` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca/waiter.pyi` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/PKG-INFO` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-acm-pca
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ACMPCA 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ACMPCA 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-acm-pca"></a>
 
 # types-aiobotocore-acm-pca
 
 [![PyPI - types-aiobotocore-acm-pca](https://img.shields.io/pypi/v/types-aiobotocore-acm-pca.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm-pca)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-acm-pca.svg?color=blue)](https://pypi.org/project/types-aiobotocore-acm-pca)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-acm-pca?color=blue)](https://pypistats.org/packages/types-aiobotocore-acm-pca)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ACMPCA 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA)
+[aiobotocore.ACMPCA 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/acm-pca.html#ACMPCA)
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
 [types-aiobotocore-acm-pca docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_acm_pca/).
 
 See how it helps to find and fix potential bugs:
 
@@ -460,43 +460,43 @@
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

### Comparing `types-aiobotocore-acm-pca-2.5.0.post1/types_aiobotocore_acm_pca.egg-info/SOURCES.txt` & `types-aiobotocore-acm-pca-2.5.1/types_aiobotocore_acm_pca.egg-info/SOURCES.txt`

 * *Files identical despite different names*

