# Comparing `tmp/types-aiobotocore-codestar-connections-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codestar-connections-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codestar-connections-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-codestar-connections-2.5.1.tar", last modified: Wed Jun 28 01:43:17 2023, max compression
```

## Comparing `types-aiobotocore-codestar-connections-2.5.0.post1.tar` & `types-aiobotocore-codestar-connections-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.591071 types-aiobotocore-codestar-connections-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13482 2023-03-11 12:26:24.587071 types-aiobotocore-codestar-connections-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11860 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:24.591071 types-aiobotocore-codestar-connections-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2206 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.579071 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/
--rw-r--r--   0 runner    (1001) docker     (123)      541 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      540 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      993 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11748 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    11728 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7927 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7925 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     7328 2023-03-11 12:11:28.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     7319 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:27.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.587071 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13482 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-03-11 12:26:24.000000 types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.746115 types-aiobotocore-codestar-connections-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13487 2023-06-28 01:43:17.742115 types-aiobotocore-codestar-connections-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11871 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:17.746115 types-aiobotocore-codestar-connections-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2200 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.742115 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/
+-rw-r--r--   0 runner    (1001) docker     (123)      541 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      540 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      981 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11748 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11728 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8154 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8152 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     7342 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7333 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:05.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:17.742115 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13487 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 01:43:17.000000 types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/LICENSE` & `types-aiobotocore-codestar-connections-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codestar-connections-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codestar-connections
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeStarconnections 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeStarconnections 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codestar-connections"></a>
 
 # types-aiobotocore-codestar-connections
 
 [![PyPI - types-aiobotocore-codestar-connections](https://img.shields.io/pypi/v/types-aiobotocore-codestar-connections.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-connections)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar-connections.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-connections)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar-connections?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar-connections)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStarconnections 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections)
+[aiobotocore.CodeStarconnections 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections)
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
 [types-aiobotocore-codestar-connections docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/).
 
 See how it helps to find and fix potential bugs:
 
@@ -293,31 +293,31 @@
 `types_aiobotocore_codestar_connections.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar_connections.type_defs import (
     ConnectionTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     VpcConfigurationTypeDef,
     DeleteConnectionInputRequestTypeDef,
     DeleteHostInputRequestTypeDef,
     GetConnectionInputRequestTypeDef,
     GetHostInputRequestTypeDef,
     ListConnectionsInputRequestTypeDef,
     ListHostsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceInputRequestTypeDef,
+    GetConnectionOutputTypeDef,
+    ListConnectionsOutputTypeDef,
     CreateConnectionInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
     CreateConnectionOutputTypeDef,
     CreateHostOutputTypeDef,
-    GetConnectionOutputTypeDef,
-    ListConnectionsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
+    TagResourceInputRequestTypeDef,
     CreateHostInputRequestTypeDef,
     GetHostOutputTypeDef,
     HostTypeDef,
     UpdateHostInputRequestTypeDef,
     ListHostsOutputTypeDef,
 )
 
@@ -329,43 +329,43 @@
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

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/README.md` & `types-aiobotocore-codestar-connections-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codestar-connections"></a>
 
 # types-aiobotocore-codestar-connections
 
 [![PyPI - types-aiobotocore-codestar-connections](https://img.shields.io/pypi/v/types-aiobotocore-codestar-connections.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-connections)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar-connections.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-connections)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar-connections?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar-connections)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStarconnections 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections)
+[aiobotocore.CodeStarconnections 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections)
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
 [types-aiobotocore-codestar-connections docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/).
 
 See how it helps to find and fix potential bugs:
 
@@ -260,31 +260,31 @@
 `types_aiobotocore_codestar_connections.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar_connections.type_defs import (
     ConnectionTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     VpcConfigurationTypeDef,
     DeleteConnectionInputRequestTypeDef,
     DeleteHostInputRequestTypeDef,
     GetConnectionInputRequestTypeDef,
     GetHostInputRequestTypeDef,
     ListConnectionsInputRequestTypeDef,
     ListHostsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceInputRequestTypeDef,
+    GetConnectionOutputTypeDef,
+    ListConnectionsOutputTypeDef,
     CreateConnectionInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
     CreateConnectionOutputTypeDef,
     CreateHostOutputTypeDef,
-    GetConnectionOutputTypeDef,
-    ListConnectionsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
+    TagResourceInputRequestTypeDef,
     CreateHostInputRequestTypeDef,
     GetHostOutputTypeDef,
     HostTypeDef,
     UpdateHostInputRequestTypeDef,
     ListHostsOutputTypeDef,
 )
 
@@ -296,43 +296,43 @@
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

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/setup.py` & `types-aiobotocore-codestar-connections-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codestar-connections.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codestar-connections",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codestar_connections"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeStarconnections 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodeStarconnections 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/",
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

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/__init__.py` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/__init__.pyi` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/__main__.py` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeStarconnections 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeStarconnections 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections\nOther"
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

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/client.py` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/client.pyi` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/literals.py` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/literals.py`

 * *Files 1% similar despite different names*

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
@@ -391,14 +400,15 @@
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
+    "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
```

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/literals.pyi` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -88,14 +88,15 @@
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
@@ -174,14 +175,15 @@
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
@@ -192,14 +194,15 @@
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
@@ -235,14 +238,15 @@
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
@@ -261,16 +265,19 @@
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
@@ -354,15 +361,17 @@
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
@@ -389,14 +398,15 @@
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
+    "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
```

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/type_defs.py` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -21,31 +21,31 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ConnectionTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "VpcConfigurationTypeDef",
     "DeleteConnectionInputRequestTypeDef",
     "DeleteHostInputRequestTypeDef",
     "GetConnectionInputRequestTypeDef",
     "GetHostInputRequestTypeDef",
     "ListConnectionsInputRequestTypeDef",
     "ListHostsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "GetConnectionOutputTypeDef",
+    "ListConnectionsOutputTypeDef",
     "CreateConnectionInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
     "CreateConnectionOutputTypeDef",
     "CreateHostOutputTypeDef",
-    "GetConnectionOutputTypeDef",
-    "ListConnectionsOutputTypeDef",
     "ListTagsForResourceOutputTypeDef",
+    "TagResourceInputRequestTypeDef",
     "CreateHostInputRequestTypeDef",
     "GetHostOutputTypeDef",
     "HostTypeDef",
     "UpdateHostInputRequestTypeDef",
     "ListHostsOutputTypeDef",
 )
 
@@ -66,25 +66,14 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 _RequiredVpcConfigurationTypeDef = TypedDict(
     "_RequiredVpcConfigurationTypeDef",
     {
         "VpcId": str,
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
@@ -153,22 +142,50 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
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
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+GetConnectionOutputTypeDef = TypedDict(
+    "GetConnectionOutputTypeDef",
+    {
+        "Connection": ConnectionTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListConnectionsOutputTypeDef = TypedDict(
+    "ListConnectionsOutputTypeDef",
+    {
+        "Connections": List[ConnectionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateConnectionInputRequestTypeDef = TypedDict(
     "_RequiredCreateConnectionInputRequestTypeDef",
     {
         "ConnectionName": str,
     },
 )
 _OptionalCreateConnectionInputRequestTypeDef = TypedDict(
@@ -184,62 +201,45 @@
 
 class CreateConnectionInputRequestTypeDef(
     _RequiredCreateConnectionInputRequestTypeDef, _OptionalCreateConnectionInputRequestTypeDef
 ):
     pass
 
 
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
 CreateConnectionOutputTypeDef = TypedDict(
     "CreateConnectionOutputTypeDef",
     {
         "ConnectionArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHostOutputTypeDef = TypedDict(
     "CreateHostOutputTypeDef",
     {
         "HostArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetConnectionOutputTypeDef = TypedDict(
-    "GetConnectionOutputTypeDef",
-    {
-        "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConnectionsOutputTypeDef = TypedDict(
-    "ListConnectionsOutputTypeDef",
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
     {
-        "Connections": List[ConnectionTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredCreateHostInputRequestTypeDef = TypedDict(
     "_RequiredCreateHostInputRequestTypeDef",
     {
         "Name": str,
@@ -267,15 +267,15 @@
     "GetHostOutputTypeDef",
     {
         "Name": str,
         "Status": str,
         "ProviderType": ProviderTypeType,
         "ProviderEndpoint": str,
         "VpcConfiguration": VpcConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HostTypeDef = TypedDict(
     "HostTypeDef",
     {
         "Name": str,
@@ -312,10 +312,10 @@
 
 
 ListHostsOutputTypeDef = TypedDict(
     "ListHostsOutputTypeDef",
     {
         "Hosts": List[HostTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections/type_defs.pyi` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -20,31 +20,31 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ConnectionTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "VpcConfigurationTypeDef",
     "DeleteConnectionInputRequestTypeDef",
     "DeleteHostInputRequestTypeDef",
     "GetConnectionInputRequestTypeDef",
     "GetHostInputRequestTypeDef",
     "ListConnectionsInputRequestTypeDef",
     "ListHostsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceInputRequestTypeDef",
+    "GetConnectionOutputTypeDef",
+    "ListConnectionsOutputTypeDef",
     "CreateConnectionInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
     "CreateConnectionOutputTypeDef",
     "CreateHostOutputTypeDef",
-    "GetConnectionOutputTypeDef",
-    "ListConnectionsOutputTypeDef",
     "ListTagsForResourceOutputTypeDef",
+    "TagResourceInputRequestTypeDef",
     "CreateHostInputRequestTypeDef",
     "GetHostOutputTypeDef",
     "HostTypeDef",
     "UpdateHostInputRequestTypeDef",
     "ListHostsOutputTypeDef",
 )
 
@@ -65,25 +65,14 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 _RequiredVpcConfigurationTypeDef = TypedDict(
     "_RequiredVpcConfigurationTypeDef",
     {
         "VpcId": str,
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
@@ -150,22 +139,50 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
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
 UntagResourceInputRequestTypeDef = TypedDict(
     "UntagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+GetConnectionOutputTypeDef = TypedDict(
+    "GetConnectionOutputTypeDef",
+    {
+        "Connection": ConnectionTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListConnectionsOutputTypeDef = TypedDict(
+    "ListConnectionsOutputTypeDef",
+    {
+        "Connections": List[ConnectionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateConnectionInputRequestTypeDef = TypedDict(
     "_RequiredCreateConnectionInputRequestTypeDef",
     {
         "ConnectionName": str,
     },
 )
 _OptionalCreateConnectionInputRequestTypeDef = TypedDict(
@@ -179,62 +196,45 @@
 )
 
 class CreateConnectionInputRequestTypeDef(
     _RequiredCreateConnectionInputRequestTypeDef, _OptionalCreateConnectionInputRequestTypeDef
 ):
     pass
 
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
 CreateConnectionOutputTypeDef = TypedDict(
     "CreateConnectionOutputTypeDef",
     {
         "ConnectionArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateHostOutputTypeDef = TypedDict(
     "CreateHostOutputTypeDef",
     {
         "HostArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetConnectionOutputTypeDef = TypedDict(
-    "GetConnectionOutputTypeDef",
-    {
-        "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConnectionsOutputTypeDef = TypedDict(
-    "ListConnectionsOutputTypeDef",
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
     {
-        "Connections": List[ConnectionTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredCreateHostInputRequestTypeDef = TypedDict(
     "_RequiredCreateHostInputRequestTypeDef",
     {
         "Name": str,
@@ -260,15 +260,15 @@
     "GetHostOutputTypeDef",
     {
         "Name": str,
         "Status": str,
         "ProviderType": ProviderTypeType,
         "ProviderEndpoint": str,
         "VpcConfiguration": VpcConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HostTypeDef = TypedDict(
     "HostTypeDef",
     {
         "Name": str,
@@ -303,10 +303,10 @@
     pass
 
 ListHostsOutputTypeDef = TypedDict(
     "ListHostsOutputTypeDef",
     {
         "Hosts": List[HostTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/PKG-INFO` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codestar-connections
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeStarconnections 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeStarconnections 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codestar-connections"></a>
 
 # types-aiobotocore-codestar-connections
 
 [![PyPI - types-aiobotocore-codestar-connections](https://img.shields.io/pypi/v/types-aiobotocore-codestar-connections.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-connections)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codestar-connections.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codestar-connections)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codestar-connections?color=blue)](https://pypistats.org/packages/types-aiobotocore-codestar-connections)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeStarconnections 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections)
+[aiobotocore.CodeStarconnections 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codestar-connections.html#CodeStarconnections)
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
 [types-aiobotocore-codestar-connections docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codestar_connections/).
 
 See how it helps to find and fix potential bugs:
 
@@ -293,31 +293,31 @@
 `types_aiobotocore_codestar_connections.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_codestar_connections.type_defs import (
     ConnectionTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     VpcConfigurationTypeDef,
     DeleteConnectionInputRequestTypeDef,
     DeleteHostInputRequestTypeDef,
     GetConnectionInputRequestTypeDef,
     GetHostInputRequestTypeDef,
     ListConnectionsInputRequestTypeDef,
     ListHostsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceInputRequestTypeDef,
+    GetConnectionOutputTypeDef,
+    ListConnectionsOutputTypeDef,
     CreateConnectionInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
     CreateConnectionOutputTypeDef,
     CreateHostOutputTypeDef,
-    GetConnectionOutputTypeDef,
-    ListConnectionsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
+    TagResourceInputRequestTypeDef,
     CreateHostInputRequestTypeDef,
     GetHostOutputTypeDef,
     HostTypeDef,
     UpdateHostInputRequestTypeDef,
     ListHostsOutputTypeDef,
 )
 
@@ -329,43 +329,43 @@
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

### Comparing `types-aiobotocore-codestar-connections-2.5.0.post1/types_aiobotocore_codestar_connections.egg-info/SOURCES.txt` & `types-aiobotocore-codestar-connections-2.5.1/types_aiobotocore_codestar_connections.egg-info/SOURCES.txt`

 * *Files identical despite different names*

