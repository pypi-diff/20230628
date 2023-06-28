# Comparing `tmp/types-aiobotocore-iotsecuretunneling-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotsecuretunneling-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotsecuretunneling-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotsecuretunneling-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1.tar` & `types-aiobotocore-iotsecuretunneling-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.963299 types-aiobotocore-iotsecuretunneling-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13320 2023-03-11 12:26:46.963299 types-aiobotocore-iotsecuretunneling-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11705 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.963299 types-aiobotocore-iotsecuretunneling-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2217 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.963299 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/
--rw-r--r--   0 runner    (1001) docker     (123)      530 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      529 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      987 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9213 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9197 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7978 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7976 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     6510 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6503 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:25.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.963299 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13320 2023-03-11 12:26:46.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      921 2023-03-11 12:26:46.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-03-11 12:26:46.000000 types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.590154 types-aiobotocore-iotsecuretunneling-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13323 2023-06-28 01:43:38.590154 types-aiobotocore-iotsecuretunneling-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11714 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.590154 types-aiobotocore-iotsecuretunneling-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2211 2023-06-28 01:33:02.000000 types-aiobotocore-iotsecuretunneling-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.582154 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/
+-rw-r--r--   0 runner    (1001) docker     (123)      530 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      529 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9213 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9197 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8207 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8205 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     6520 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6513 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:04.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.590154 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13323 2023-06-28 01:43:38.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      921 2023-06-28 01:43:38.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:38.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 01:43:38.000000 types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/LICENSE` & `types-aiobotocore-iotsecuretunneling-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotsecuretunneling-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotsecuretunneling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTSecureTunneling 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTSecureTunneling 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotsecuretunneling"></a>
 
 # types-aiobotocore-iotsecuretunneling
 
 [![PyPI - types-aiobotocore-iotsecuretunneling](https://img.shields.io/pypi/v/types-aiobotocore-iotsecuretunneling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsecuretunneling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotsecuretunneling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsecuretunneling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotsecuretunneling?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotsecuretunneling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTSecureTunneling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsecuretunneling.html#IoTSecureTunneling)
+[aiobotocore.IoTSecureTunneling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsecuretunneling.html#IoTSecureTunneling)
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
 [types-aiobotocore-iotsecuretunneling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,24 +295,24 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotsecuretunneling.type_defs import (
     CloseTunnelRequestRequestTypeDef,
     ConnectionStateTypeDef,
     DescribeTunnelRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DestinationConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     ListTunnelsRequestRequestTypeDef,
     TunnelSummaryTypeDef,
     TimeoutConfigTypeDef,
-    UntagResourceRequestRequestTypeDef,
     OpenTunnelResponseTypeDef,
+    ResponseMetadataTypeDef,
     RotateTunnelAccessTokenResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     RotateTunnelAccessTokenRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListTunnelsResponseTypeDef,
     OpenTunnelRequestRequestTypeDef,
     TunnelTypeDef,
     DescribeTunnelResponseTypeDef,
@@ -326,43 +326,43 @@
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

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/README.md` & `types-aiobotocore-iotsecuretunneling-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotsecuretunneling"></a>
 
 # types-aiobotocore-iotsecuretunneling
 
 [![PyPI - types-aiobotocore-iotsecuretunneling](https://img.shields.io/pypi/v/types-aiobotocore-iotsecuretunneling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsecuretunneling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotsecuretunneling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsecuretunneling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotsecuretunneling?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotsecuretunneling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTSecureTunneling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsecuretunneling.html#IoTSecureTunneling)
+[aiobotocore.IoTSecureTunneling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsecuretunneling.html#IoTSecureTunneling)
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
 [types-aiobotocore-iotsecuretunneling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -262,24 +262,24 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotsecuretunneling.type_defs import (
     CloseTunnelRequestRequestTypeDef,
     ConnectionStateTypeDef,
     DescribeTunnelRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DestinationConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     ListTunnelsRequestRequestTypeDef,
     TunnelSummaryTypeDef,
     TimeoutConfigTypeDef,
-    UntagResourceRequestRequestTypeDef,
     OpenTunnelResponseTypeDef,
+    ResponseMetadataTypeDef,
     RotateTunnelAccessTokenResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     RotateTunnelAccessTokenRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListTunnelsResponseTypeDef,
     OpenTunnelRequestRequestTypeDef,
     TunnelTypeDef,
     DescribeTunnelResponseTypeDef,
@@ -293,43 +293,43 @@
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

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/setup.py` & `types-aiobotocore-iotsecuretunneling-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotsecuretunneling.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotsecuretunneling",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotsecuretunneling"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTSecureTunneling 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTSecureTunneling 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/"
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

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/__init__.py` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/__init__.pyi` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/__main__.py` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTSecureTunneling 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTSecureTunneling 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsecuretunneling.html#IoTSecureTunneling\nOther"
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

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/client.py` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/client.pyi` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/literals.py` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/literals.pyi`

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
     "ClientModeType",
     "ConnectionStatusType",
     "TunnelStatusType",
     "IoTSecureTunnelingServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 ClientModeType = Literal["ALL", "DESTINATION", "SOURCE"]
 ConnectionStatusType = Literal["CONNECTED", "DISCONNECTED"]
 TunnelStatusType = Literal["CLOSED", "OPEN"]
 IoTSecureTunnelingServiceName = Literal["iotsecuretunneling"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -92,14 +90,15 @@
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
@@ -178,14 +177,15 @@
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
@@ -196,14 +196,15 @@
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
@@ -239,14 +240,15 @@
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
@@ -265,16 +267,19 @@
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
@@ -358,15 +363,17 @@
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
@@ -397,14 +404,15 @@
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/literals.pyi` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/literals.py`

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
     "ClientModeType",
     "ConnectionStatusType",
     "TunnelStatusType",
     "IoTSecureTunnelingServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 ClientModeType = Literal["ALL", "DESTINATION", "SOURCE"]
 ConnectionStatusType = Literal["CONNECTED", "DISCONNECTED"]
 TunnelStatusType = Literal["CLOSED", "OPEN"]
 IoTSecureTunnelingServiceName = Literal["iotsecuretunneling"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -90,14 +92,15 @@
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
@@ -176,14 +179,15 @@
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
@@ -194,14 +198,15 @@
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
@@ -237,14 +242,15 @@
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
@@ -263,16 +269,19 @@
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
@@ -356,15 +365,17 @@
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
@@ -395,14 +406,15 @@
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/type_defs.py` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -23,24 +23,24 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CloseTunnelRequestRequestTypeDef",
     "ConnectionStateTypeDef",
     "DescribeTunnelRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "DestinationConfigTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "ListTunnelsRequestRequestTypeDef",
     "TunnelSummaryTypeDef",
     "TimeoutConfigTypeDef",
-    "UntagResourceRequestRequestTypeDef",
     "OpenTunnelResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RotateTunnelAccessTokenResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "RotateTunnelAccessTokenRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ListTunnelsResponseTypeDef",
     "OpenTunnelRequestRequestTypeDef",
     "TunnelTypeDef",
     "DescribeTunnelResponseTypeDef",
@@ -79,25 +79,14 @@
 DescribeTunnelRequestRequestTypeDef = TypedDict(
     "DescribeTunnelRequestRequestTypeDef",
     {
         "tunnelId": str,
     },
 )
 
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
 _RequiredDestinationConfigTypeDef = TypedDict(
     "_RequiredDestinationConfigTypeDef",
     {
         "services": List[str],
     },
 )
 _OptionalDestinationConfigTypeDef = TypedDict(
@@ -157,40 +146,51 @@
     "TimeoutConfigTypeDef",
     {
         "maxLifetimeTimeoutMinutes": int,
     },
     total=False,
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
 OpenTunnelResponseTypeDef = TypedDict(
     "OpenTunnelResponseTypeDef",
     {
         "tunnelId": str,
         "tunnelArn": str,
         "sourceAccessToken": str,
         "destinationAccessToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
     },
 )
 
 RotateTunnelAccessTokenResponseTypeDef = TypedDict(
     "RotateTunnelAccessTokenResponseTypeDef",
     {
         "tunnelArn": str,
         "sourceAccessToken": str,
         "destinationAccessToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
 _RequiredRotateTunnelAccessTokenRequestRequestTypeDef = TypedDict(
     "_RequiredRotateTunnelAccessTokenRequestRequestTypeDef",
     {
         "tunnelId": str,
@@ -213,15 +213,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -230,15 +230,15 @@
 )
 
 ListTunnelsResponseTypeDef = TypedDict(
     "ListTunnelsResponseTypeDef",
     {
         "tunnelSummaries": List[TunnelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpenTunnelRequestRequestTypeDef = TypedDict(
     "OpenTunnelRequestRequestTypeDef",
     {
         "description": str,
@@ -267,10 +267,10 @@
     total=False,
 )
 
 DescribeTunnelResponseTypeDef = TypedDict(
     "DescribeTunnelResponseTypeDef",
     {
         "tunnel": TunnelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling/type_defs.pyi` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -22,24 +22,24 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CloseTunnelRequestRequestTypeDef",
     "ConnectionStateTypeDef",
     "DescribeTunnelRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "DestinationConfigTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "ListTunnelsRequestRequestTypeDef",
     "TunnelSummaryTypeDef",
     "TimeoutConfigTypeDef",
-    "UntagResourceRequestRequestTypeDef",
     "OpenTunnelResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RotateTunnelAccessTokenResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "RotateTunnelAccessTokenRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ListTunnelsResponseTypeDef",
     "OpenTunnelRequestRequestTypeDef",
     "TunnelTypeDef",
     "DescribeTunnelResponseTypeDef",
@@ -76,25 +76,14 @@
 DescribeTunnelRequestRequestTypeDef = TypedDict(
     "DescribeTunnelRequestRequestTypeDef",
     {
         "tunnelId": str,
     },
 )
 
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
 _RequiredDestinationConfigTypeDef = TypedDict(
     "_RequiredDestinationConfigTypeDef",
     {
         "services": List[str],
     },
 )
 _OptionalDestinationConfigTypeDef = TypedDict(
@@ -152,40 +141,51 @@
     "TimeoutConfigTypeDef",
     {
         "maxLifetimeTimeoutMinutes": int,
     },
     total=False,
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
 OpenTunnelResponseTypeDef = TypedDict(
     "OpenTunnelResponseTypeDef",
     {
         "tunnelId": str,
         "tunnelArn": str,
         "sourceAccessToken": str,
         "destinationAccessToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
     },
 )
 
 RotateTunnelAccessTokenResponseTypeDef = TypedDict(
     "RotateTunnelAccessTokenResponseTypeDef",
     {
         "tunnelArn": str,
         "sourceAccessToken": str,
         "destinationAccessToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
+    {
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
 _RequiredRotateTunnelAccessTokenRequestRequestTypeDef = TypedDict(
     "_RequiredRotateTunnelAccessTokenRequestRequestTypeDef",
     {
         "tunnelId": str,
@@ -206,15 +206,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -223,15 +223,15 @@
 )
 
 ListTunnelsResponseTypeDef = TypedDict(
     "ListTunnelsResponseTypeDef",
     {
         "tunnelSummaries": List[TunnelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpenTunnelRequestRequestTypeDef = TypedDict(
     "OpenTunnelRequestRequestTypeDef",
     {
         "description": str,
@@ -260,10 +260,10 @@
     total=False,
 )
 
 DescribeTunnelResponseTypeDef = TypedDict(
     "DescribeTunnelResponseTypeDef",
     {
         "tunnel": TunnelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/PKG-INFO` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotsecuretunneling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTSecureTunneling 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTSecureTunneling 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotsecuretunneling"></a>
 
 # types-aiobotocore-iotsecuretunneling
 
 [![PyPI - types-aiobotocore-iotsecuretunneling](https://img.shields.io/pypi/v/types-aiobotocore-iotsecuretunneling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsecuretunneling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotsecuretunneling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotsecuretunneling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotsecuretunneling?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotsecuretunneling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTSecureTunneling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsecuretunneling.html#IoTSecureTunneling)
+[aiobotocore.IoTSecureTunneling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotsecuretunneling.html#IoTSecureTunneling)
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
 [types-aiobotocore-iotsecuretunneling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotsecuretunneling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -295,24 +295,24 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotsecuretunneling.type_defs import (
     CloseTunnelRequestRequestTypeDef,
     ConnectionStateTypeDef,
     DescribeTunnelRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     DestinationConfigTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     ListTunnelsRequestRequestTypeDef,
     TunnelSummaryTypeDef,
     TimeoutConfigTypeDef,
-    UntagResourceRequestRequestTypeDef,
     OpenTunnelResponseTypeDef,
+    ResponseMetadataTypeDef,
     RotateTunnelAccessTokenResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
     RotateTunnelAccessTokenRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListTunnelsResponseTypeDef,
     OpenTunnelRequestRequestTypeDef,
     TunnelTypeDef,
     DescribeTunnelResponseTypeDef,
@@ -326,43 +326,43 @@
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

### Comparing `types-aiobotocore-iotsecuretunneling-2.5.0.post1/types_aiobotocore_iotsecuretunneling.egg-info/SOURCES.txt` & `types-aiobotocore-iotsecuretunneling-2.5.1/types_aiobotocore_iotsecuretunneling.egg-info/SOURCES.txt`

 * *Files identical despite different names*

