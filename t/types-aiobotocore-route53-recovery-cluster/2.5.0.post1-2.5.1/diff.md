# Comparing `tmp/types-aiobotocore-route53-recovery-cluster-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-route53-recovery-cluster-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-route53-recovery-cluster-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-route53-recovery-cluster-2.5.1.tar", last modified: Wed Jun 28 01:44:05 2023, max compression
```

## Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1.tar` & `types-aiobotocore-route53-recovery-cluster-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.579561 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14266 2023-03-11 12:27:13.575561 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12629 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.579561 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2244 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.563561 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/
--rw-r--r--   0 runner    (1001) docker     (123)      805 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      804 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1007 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8343 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8329 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7707 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7705 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2402 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2398 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     4501 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     4497 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:39.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.575561 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14266 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       43 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.150203 types-aiobotocore-route53-recovery-cluster-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14275 2023-06-28 01:44:05.150203 types-aiobotocore-route53-recovery-cluster-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12644 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:05.150203 types-aiobotocore-route53-recovery-cluster-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2238 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.150203 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/
+-rw-r--r--   0 runner    (1001) docker     (123)      805 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      804 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      995 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8343 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8329 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7916 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7914 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2284 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2281 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     4507 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4503 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:26.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.150203 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14275 2023-06-28 01:44:04.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1136 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:04.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:04.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:04.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       43 2023-06-28 01:44:04.000000 types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/LICENSE` & `types-aiobotocore-route53-recovery-cluster-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/PKG-INFO` & `types-aiobotocore-route53-recovery-cluster-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53-recovery-cluster
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53RecoveryCluster 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53RecoveryCluster 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53-recovery-cluster"></a>
 
 # types-aiobotocore-route53-recovery-cluster
 
 [![PyPI - types-aiobotocore-route53-recovery-cluster](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-cluster.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-cluster)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-cluster.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-cluster)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-cluster?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-cluster)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryCluster 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster)
+[aiobotocore.Route53RecoveryCluster 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster)
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
 [types-aiobotocore-route53-recovery-cluster docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,22 +318,22 @@
 `types_aiobotocore_route53_recovery_cluster.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_route53_recovery_cluster.type_defs import (
     GetRoutingControlStateRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    GetRoutingControlStateResponseTypeDef,
+    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsRequestRequestTypeDef,
     RoutingControlTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateRoutingControlStateEntryTypeDef,
     UpdateRoutingControlStateRequestRequestTypeDef,
-    GetRoutingControlStateResponseTypeDef,
-    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsResponseTypeDef,
     UpdateRoutingControlStatesRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetRoutingControlStateRequestRequestTypeDef:
     return {...}
@@ -342,43 +342,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/README.md` & `types-aiobotocore-route53-recovery-cluster-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-route53-recovery-cluster"></a>
 
 # types-aiobotocore-route53-recovery-cluster
 
 [![PyPI - types-aiobotocore-route53-recovery-cluster](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-cluster.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-cluster)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-cluster.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-cluster)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-cluster?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-cluster)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryCluster 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster)
+[aiobotocore.Route53RecoveryCluster 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster)
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
 [types-aiobotocore-route53-recovery-cluster docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/).
 
 See how it helps to find and fix potential bugs:
 
@@ -285,22 +285,22 @@
 `types_aiobotocore_route53_recovery_cluster.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_route53_recovery_cluster.type_defs import (
     GetRoutingControlStateRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    GetRoutingControlStateResponseTypeDef,
+    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsRequestRequestTypeDef,
     RoutingControlTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateRoutingControlStateEntryTypeDef,
     UpdateRoutingControlStateRequestRequestTypeDef,
-    GetRoutingControlStateResponseTypeDef,
-    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsResponseTypeDef,
     UpdateRoutingControlStatesRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetRoutingControlStateRequestRequestTypeDef:
     return {...}
@@ -309,43 +309,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/setup.py` & `types-aiobotocore-route53-recovery-cluster-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-route53-recovery-cluster.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-route53-recovery-cluster",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_route53_recovery_cluster"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Route53RecoveryCluster 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Route53RecoveryCluster 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/",
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

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/__init__.py` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/__init__.pyi` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/__main__.py` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/__main__.py`

 * *Files 19% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Route53RecoveryCluster 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Route53RecoveryCluster 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster\nOther"
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

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/client.py` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/client.pyi` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/literals.py` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/literals.py`

 * *Files 2% similar despite different names*

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
```

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/literals.pyi` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/literals.pyi`

 * *Files 2% similar despite different names*

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
```

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/paginator.py` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/paginator.py`

 * *Files 10% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("route53-recovery-cluster") as client:
         client: Route53RecoveryClusterClient
 
         list_routing_controls_paginator: ListRoutingControlsPaginator = client.get_paginator("list_routing_controls")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListRoutingControlsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListRoutingControlsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListRoutingControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster.Paginator.ListRoutingControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/paginators/#listroutingcontrolspaginator)
     """
 
     def paginate(
-        self, *, ControlPanelArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ControlPanelArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutingControlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster.Paginator.ListRoutingControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/paginators/#listroutingcontrolspaginator)
         """
```

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/paginator.pyi` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("route53-recovery-cluster") as client:
         client: Route53RecoveryClusterClient
 
         list_routing_controls_paginator: ListRoutingControlsPaginator = client.get_paginator("list_routing_controls")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListRoutingControlsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListRoutingControlsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListRoutingControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster.Paginator.ListRoutingControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/paginators/#listroutingcontrolspaginator)
     """
 
     def paginate(
-        self, *, ControlPanelArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ControlPanelArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRoutingControlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster.Paginator.ListRoutingControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/paginators/#listroutingcontrolspaginator)
         """
```

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/type_defs.py` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -20,50 +20,48 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "GetRoutingControlStateRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetRoutingControlStateResponseTypeDef",
+    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     "ListRoutingControlsRequestRequestTypeDef",
     "RoutingControlTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateRoutingControlStateEntryTypeDef",
     "UpdateRoutingControlStateRequestRequestTypeDef",
-    "GetRoutingControlStateResponseTypeDef",
-    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     "ListRoutingControlsResponseTypeDef",
     "UpdateRoutingControlStatesRequestRequestTypeDef",
 )
 
 GetRoutingControlStateRequestRequestTypeDef = TypedDict(
     "GetRoutingControlStateRequestRequestTypeDef",
     {
         "RoutingControlArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetRoutingControlStateResponseTypeDef = TypedDict(
+    "GetRoutingControlStateResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "RoutingControlArn": str,
+        "RoutingControlState": RoutingControlStateType,
+        "RoutingControlName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
+    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ControlPanelArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRoutingControlsRequestRequestTypeDef = TypedDict(
     "ListRoutingControlsRequestRequestTypeDef",
     {
@@ -82,14 +80,35 @@
         "RoutingControlArn": str,
         "RoutingControlName": str,
         "RoutingControlState": RoutingControlStateType,
     },
     total=False,
 )
 
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
 UpdateRoutingControlStateEntryTypeDef = TypedDict(
     "UpdateRoutingControlStateEntryTypeDef",
     {
         "RoutingControlArn": str,
         "RoutingControlState": RoutingControlStateType,
     },
 )
@@ -113,39 +132,20 @@
 class UpdateRoutingControlStateRequestRequestTypeDef(
     _RequiredUpdateRoutingControlStateRequestRequestTypeDef,
     _OptionalUpdateRoutingControlStateRequestRequestTypeDef,
 ):
     pass
 
 
-GetRoutingControlStateResponseTypeDef = TypedDict(
-    "GetRoutingControlStateResponseTypeDef",
-    {
-        "RoutingControlArn": str,
-        "RoutingControlState": RoutingControlStateType,
-        "RoutingControlName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
-    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    {
-        "ControlPanelArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListRoutingControlsResponseTypeDef = TypedDict(
     "ListRoutingControlsResponseTypeDef",
     {
         "RoutingControls": List[RoutingControlTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateRoutingControlStatesRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRoutingControlStatesRequestRequestTypeDef",
     {
         "UpdateRoutingControlStateEntries": Sequence[UpdateRoutingControlStateEntryTypeDef],
```

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster/type_defs.pyi` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -19,50 +19,48 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "GetRoutingControlStateRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetRoutingControlStateResponseTypeDef",
+    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     "ListRoutingControlsRequestRequestTypeDef",
     "RoutingControlTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateRoutingControlStateEntryTypeDef",
     "UpdateRoutingControlStateRequestRequestTypeDef",
-    "GetRoutingControlStateResponseTypeDef",
-    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     "ListRoutingControlsResponseTypeDef",
     "UpdateRoutingControlStatesRequestRequestTypeDef",
 )
 
 GetRoutingControlStateRequestRequestTypeDef = TypedDict(
     "GetRoutingControlStateRequestRequestTypeDef",
     {
         "RoutingControlArn": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+GetRoutingControlStateResponseTypeDef = TypedDict(
+    "GetRoutingControlStateResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "RoutingControlArn": str,
+        "RoutingControlState": RoutingControlStateType,
+        "RoutingControlName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
+    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ControlPanelArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListRoutingControlsRequestRequestTypeDef = TypedDict(
     "ListRoutingControlsRequestRequestTypeDef",
     {
@@ -81,14 +79,35 @@
         "RoutingControlArn": str,
         "RoutingControlName": str,
         "RoutingControlState": RoutingControlStateType,
     },
     total=False,
 )
 
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
 UpdateRoutingControlStateEntryTypeDef = TypedDict(
     "UpdateRoutingControlStateEntryTypeDef",
     {
         "RoutingControlArn": str,
         "RoutingControlState": RoutingControlStateType,
     },
 )
@@ -110,39 +129,20 @@
 
 class UpdateRoutingControlStateRequestRequestTypeDef(
     _RequiredUpdateRoutingControlStateRequestRequestTypeDef,
     _OptionalUpdateRoutingControlStateRequestRequestTypeDef,
 ):
     pass
 
-GetRoutingControlStateResponseTypeDef = TypedDict(
-    "GetRoutingControlStateResponseTypeDef",
-    {
-        "RoutingControlArn": str,
-        "RoutingControlState": RoutingControlStateType,
-        "RoutingControlName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRoutingControlsRequestListRoutingControlsPaginateTypeDef = TypedDict(
-    "ListRoutingControlsRequestListRoutingControlsPaginateTypeDef",
-    {
-        "ControlPanelArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListRoutingControlsResponseTypeDef = TypedDict(
     "ListRoutingControlsResponseTypeDef",
     {
         "RoutingControls": List[RoutingControlTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateRoutingControlStatesRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRoutingControlStatesRequestRequestTypeDef",
     {
         "UpdateRoutingControlStateEntries": Sequence[UpdateRoutingControlStateEntryTypeDef],
```

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/PKG-INFO` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53-recovery-cluster
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53RecoveryCluster 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53RecoveryCluster 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53-recovery-cluster"></a>
 
 # types-aiobotocore-route53-recovery-cluster
 
 [![PyPI - types-aiobotocore-route53-recovery-cluster](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-cluster.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-cluster)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-cluster.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-cluster)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-cluster?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-cluster)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryCluster 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster)
+[aiobotocore.Route53RecoveryCluster 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-cluster.html#Route53RecoveryCluster)
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
 [types-aiobotocore-route53-recovery-cluster docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_cluster/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,22 +318,22 @@
 `types_aiobotocore_route53_recovery_cluster.type_defs` module contains
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_route53_recovery_cluster.type_defs import (
     GetRoutingControlStateRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
-    PaginatorConfigTypeDef,
+    GetRoutingControlStateResponseTypeDef,
+    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsRequestRequestTypeDef,
     RoutingControlTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateRoutingControlStateEntryTypeDef,
     UpdateRoutingControlStateRequestRequestTypeDef,
-    GetRoutingControlStateResponseTypeDef,
-    ListRoutingControlsRequestListRoutingControlsPaginateTypeDef,
     ListRoutingControlsResponseTypeDef,
     UpdateRoutingControlStatesRequestRequestTypeDef,
 )
 
 
 def get_structure() -> GetRoutingControlStateRequestRequestTypeDef:
     return {...}
@@ -342,43 +342,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-cluster-2.5.0.post1/types_aiobotocore_route53_recovery_cluster.egg-info/SOURCES.txt` & `types-aiobotocore-route53-recovery-cluster-2.5.1/types_aiobotocore_route53_recovery_cluster.egg-info/SOURCES.txt`

 * *Files identical despite different names*

