# Comparing `tmp/types-aiobotocore-cloud9-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloud9-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloud9-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:19 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloud9-2.5.1.tar", last modified: Wed Jun 28 01:43:12 2023, max compression
```

## Comparing `types-aiobotocore-cloud9-2.5.0.post1.tar` & `types-aiobotocore-cloud9-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.799022 types-aiobotocore-cloud9-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14503 2023-03-11 12:26:19.791022 types-aiobotocore-cloud9-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12936 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:19.799022 types-aiobotocore-cloud9-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.791022 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/
--rw-r--r--   0 runner    (1001) docker     (123)      950 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      949 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13609 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13585 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9244 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9242 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3536 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3531 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     9719 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     9710 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:36.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.791022 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14503 2023-03-11 12:26:19.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:26:19.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:12.474105 types-aiobotocore-cloud9-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14494 2023-06-28 01:43:12.474105 types-aiobotocore-cloud9-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12933 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:12.474105 types-aiobotocore-cloud9-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:12.470105 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/
+-rw-r--r--   0 runner    (1001) docker     (123)      950 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13609 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13585 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9453 2023-06-28 01:27:14.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9451 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3420 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3416 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     9739 2023-06-28 01:27:14.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9730 2023-06-28 01:27:14.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:13.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:12.474105 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14494 2023-06-28 01:43:12.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:12.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:12.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:12.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:12.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:12.000000 types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/LICENSE` & `types-aiobotocore-cloud9-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloud9-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloud9
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Cloud9 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Cloud9 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloud9"></a>
 
 # types-aiobotocore-cloud9
 
 [![PyPI - types-aiobotocore-cloud9](https://img.shields.io/pypi/v/types-aiobotocore-cloud9.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloud9)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloud9.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloud9)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloud9?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloud9)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Cloud9 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
+[aiobotocore.Cloud9 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
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
 [types-aiobotocore-cloud9 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,40 +331,40 @@
 
 `types_aiobotocore_cloud9.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloud9.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateEnvironmentEC2ResultTypeDef,
     CreateEnvironmentMembershipRequestRequestTypeDef,
     EnvironmentMemberTypeDef,
     DeleteEnvironmentMembershipRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef,
     DescribeEnvironmentMembershipsRequestRequestTypeDef,
     DescribeEnvironmentStatusRequestRequestTypeDef,
+    DescribeEnvironmentStatusResultTypeDef,
     DescribeEnvironmentsRequestRequestTypeDef,
     EnvironmentLifecycleTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
+    ListEnvironmentsResultTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateEnvironmentMembershipRequestRequestTypeDef,
     UpdateEnvironmentRequestRequestTypeDef,
     CreateEnvironmentEC2RequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateEnvironmentEC2ResultTypeDef,
-    DescribeEnvironmentStatusResultTypeDef,
-    ListEnvironmentsResultTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateEnvironmentMembershipResultTypeDef,
     DescribeEnvironmentMembershipsResultTypeDef,
     UpdateEnvironmentMembershipResultTypeDef,
-    DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     EnvironmentTypeDef,
     DescribeEnvironmentsResultTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
     return {...}
@@ -373,43 +373,43 @@
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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/README.md` & `types-aiobotocore-cloud9-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloud9"></a>
 
 # types-aiobotocore-cloud9
 
 [![PyPI - types-aiobotocore-cloud9](https://img.shields.io/pypi/v/types-aiobotocore-cloud9.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloud9)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloud9.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloud9)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloud9?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloud9)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Cloud9 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
+[aiobotocore.Cloud9 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
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
 [types-aiobotocore-cloud9 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,40 +298,40 @@
 
 `types_aiobotocore_cloud9.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloud9.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateEnvironmentEC2ResultTypeDef,
     CreateEnvironmentMembershipRequestRequestTypeDef,
     EnvironmentMemberTypeDef,
     DeleteEnvironmentMembershipRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef,
     DescribeEnvironmentMembershipsRequestRequestTypeDef,
     DescribeEnvironmentStatusRequestRequestTypeDef,
+    DescribeEnvironmentStatusResultTypeDef,
     DescribeEnvironmentsRequestRequestTypeDef,
     EnvironmentLifecycleTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
+    ListEnvironmentsResultTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateEnvironmentMembershipRequestRequestTypeDef,
     UpdateEnvironmentRequestRequestTypeDef,
     CreateEnvironmentEC2RequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateEnvironmentEC2ResultTypeDef,
-    DescribeEnvironmentStatusResultTypeDef,
-    ListEnvironmentsResultTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateEnvironmentMembershipResultTypeDef,
     DescribeEnvironmentMembershipsResultTypeDef,
     UpdateEnvironmentMembershipResultTypeDef,
-    DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     EnvironmentTypeDef,
     DescribeEnvironmentsResultTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
     return {...}
@@ -340,43 +340,43 @@
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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/setup.py` & `types-aiobotocore-cloud9-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloud9.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloud9",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloud9"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Cloud9 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Cloud9 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/"
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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/__init__.py` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/__init__.pyi` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/__main__.py` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Cloud9 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Cloud9 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9\nOther"
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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/client.py` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/client.pyi` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/literals.py` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -123,14 +123,15 @@
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
@@ -209,14 +210,15 @@
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
@@ -227,14 +229,15 @@
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
@@ -270,14 +273,15 @@
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
@@ -296,16 +300,19 @@
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
@@ -389,15 +396,17 @@
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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/literals.pyi` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -121,14 +121,15 @@
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
@@ -207,14 +208,15 @@
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
@@ -225,14 +227,15 @@
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
@@ -268,14 +271,15 @@
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
@@ -294,16 +298,19 @@
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
@@ -387,15 +394,17 @@
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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/paginator.py` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -18,72 +18,61 @@
     with session.create_client("cloud9") as client:
         client: Cloud9Client
 
         describe_environment_memberships_paginator: DescribeEnvironmentMembershipsPaginator = client.get_paginator("describe_environment_memberships")
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import PermissionsType
 from .type_defs import (
     DescribeEnvironmentMembershipsResultTypeDef,
     ListEnvironmentsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeEnvironmentMembershipsPaginator", "ListEnvironmentsPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeEnvironmentMembershipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.DescribeEnvironmentMemberships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#describeenvironmentmembershipspaginator)
     """
 
     def paginate(
         self,
         *,
         userArn: str = ...,
         environmentId: str = ...,
         permissions: Sequence[PermissionsType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEnvironmentMembershipsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.DescribeEnvironmentMemberships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#describeenvironmentmembershipspaginator)
         """
 
-
 class ListEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.ListEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#listenvironmentspaginator)
         """
```

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/paginator.pyi` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -18,67 +18,65 @@
     with session.create_client("cloud9") as client:
         client: Cloud9Client
 
         describe_environment_memberships_paginator: DescribeEnvironmentMembershipsPaginator = client.get_paginator("describe_environment_memberships")
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import PermissionsType
 from .type_defs import (
     DescribeEnvironmentMembershipsResultTypeDef,
     ListEnvironmentsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeEnvironmentMembershipsPaginator", "ListEnvironmentsPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeEnvironmentMembershipsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.DescribeEnvironmentMemberships)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#describeenvironmentmembershipspaginator)
     """
 
     def paginate(
         self,
         *,
         userArn: str = ...,
         environmentId: str = ...,
         permissions: Sequence[PermissionsType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEnvironmentMembershipsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.DescribeEnvironmentMemberships.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#describeenvironmentmembershipspaginator)
         """
 
+
 class ListEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.ListEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/paginators/#listenvironmentspaginator)
         """
```

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/type_defs.py` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,60 +30,57 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateEnvironmentEC2ResultTypeDef",
     "CreateEnvironmentMembershipRequestRequestTypeDef",
     "EnvironmentMemberTypeDef",
     "DeleteEnvironmentMembershipRequestRequestTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
     "DescribeEnvironmentMembershipsRequestRequestTypeDef",
     "DescribeEnvironmentStatusRequestRequestTypeDef",
+    "DescribeEnvironmentStatusResultTypeDef",
     "DescribeEnvironmentsRequestRequestTypeDef",
     "EnvironmentLifecycleTypeDef",
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
+    "ListEnvironmentsResultTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateEnvironmentMembershipRequestRequestTypeDef",
     "UpdateEnvironmentRequestRequestTypeDef",
     "CreateEnvironmentEC2RequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateEnvironmentEC2ResultTypeDef",
-    "DescribeEnvironmentStatusResultTypeDef",
-    "ListEnvironmentsResultTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateEnvironmentMembershipResultTypeDef",
     "DescribeEnvironmentMembershipsResultTypeDef",
     "UpdateEnvironmentMembershipResultTypeDef",
-    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "EnvironmentTypeDef",
     "DescribeEnvironmentsResultTypeDef",
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateEnvironmentEC2ResultTypeDef = TypedDict(
+    "CreateEnvironmentEC2ResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "environmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentMembershipRequestRequestTypeDef = TypedDict(
     "CreateEnvironmentMembershipRequestRequestTypeDef",
     {
         "environmentId": str,
@@ -127,20 +124,21 @@
 DeleteEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteEnvironmentRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef = TypedDict(
+    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "userArn": str,
+        "environmentId": str,
+        "permissions": Sequence[PermissionsType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEnvironmentMembershipsRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentMembershipsRequestRequestTypeDef",
     {
@@ -156,14 +154,23 @@
 DescribeEnvironmentStatusRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentStatusRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 
+DescribeEnvironmentStatusResultTypeDef = TypedDict(
+    "DescribeEnvironmentStatusResultTypeDef",
+    {
+        "status": EnvironmentStatusType,
+        "message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeEnvironmentsRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentsRequestRequestTypeDef",
     {
         "environmentIds": Sequence[str],
     },
 )
 
@@ -173,30 +180,68 @@
         "status": EnvironmentLifecycleStatusType,
         "reason": str,
         "failureResource": str,
     },
     total=False,
 )
 
+ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentsRequestRequestTypeDef = TypedDict(
     "ListEnvironmentsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListEnvironmentsResultTypeDef = TypedDict(
+    "ListEnvironmentsResultTypeDef",
+    {
+        "nextToken": str,
+        "environmentIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -260,100 +305,55 @@
 class CreateEnvironmentEC2RequestRequestTypeDef(
     _RequiredCreateEnvironmentEC2RequestRequestTypeDef,
     _OptionalCreateEnvironmentEC2RequestRequestTypeDef,
 ):
     pass
 
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateEnvironmentEC2ResultTypeDef = TypedDict(
-    "CreateEnvironmentEC2ResultTypeDef",
-    {
-        "environmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEnvironmentStatusResultTypeDef = TypedDict(
-    "DescribeEnvironmentStatusResultTypeDef",
-    {
-        "status": EnvironmentStatusType,
-        "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListEnvironmentsResultTypeDef = TypedDict(
-    "ListEnvironmentsResultTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "nextToken": str,
-        "environmentIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 CreateEnvironmentMembershipResultTypeDef = TypedDict(
     "CreateEnvironmentMembershipResultTypeDef",
     {
         "membership": EnvironmentMemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEnvironmentMembershipsResultTypeDef = TypedDict(
     "DescribeEnvironmentMembershipsResultTypeDef",
     {
         "memberships": List[EnvironmentMemberTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentMembershipResultTypeDef = TypedDict(
     "UpdateEnvironmentMembershipResultTypeDef",
     {
         "membership": EnvironmentMemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef = TypedDict(
-    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
-    {
-        "userArn": str,
-        "environmentId": str,
-        "permissions": Sequence[PermissionsType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredEnvironmentTypeDef = TypedDict(
     "_RequiredEnvironmentTypeDef",
     {
         "type": EnvironmentTypeType,
         "arn": str,
         "ownerArn": str,
     },
@@ -376,10 +376,10 @@
     pass
 
 
 DescribeEnvironmentsResultTypeDef = TypedDict(
     "DescribeEnvironmentsResultTypeDef",
     {
         "environments": List[EnvironmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9/type_defs.pyi` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -29,60 +29,57 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateEnvironmentEC2ResultTypeDef",
     "CreateEnvironmentMembershipRequestRequestTypeDef",
     "EnvironmentMemberTypeDef",
     "DeleteEnvironmentMembershipRequestRequestTypeDef",
     "DeleteEnvironmentRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
     "DescribeEnvironmentMembershipsRequestRequestTypeDef",
     "DescribeEnvironmentStatusRequestRequestTypeDef",
+    "DescribeEnvironmentStatusResultTypeDef",
     "DescribeEnvironmentsRequestRequestTypeDef",
     "EnvironmentLifecycleTypeDef",
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsRequestRequestTypeDef",
+    "ListEnvironmentsResultTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateEnvironmentMembershipRequestRequestTypeDef",
     "UpdateEnvironmentRequestRequestTypeDef",
     "CreateEnvironmentEC2RequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateEnvironmentEC2ResultTypeDef",
-    "DescribeEnvironmentStatusResultTypeDef",
-    "ListEnvironmentsResultTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateEnvironmentMembershipResultTypeDef",
     "DescribeEnvironmentMembershipsResultTypeDef",
     "UpdateEnvironmentMembershipResultTypeDef",
-    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
     "EnvironmentTypeDef",
     "DescribeEnvironmentsResultTypeDef",
 )
 
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateEnvironmentEC2ResultTypeDef = TypedDict(
+    "CreateEnvironmentEC2ResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "environmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEnvironmentMembershipRequestRequestTypeDef = TypedDict(
     "CreateEnvironmentMembershipRequestRequestTypeDef",
     {
         "environmentId": str,
@@ -124,20 +121,21 @@
 DeleteEnvironmentRequestRequestTypeDef = TypedDict(
     "DeleteEnvironmentRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef = TypedDict(
+    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "userArn": str,
+        "environmentId": str,
+        "permissions": Sequence[PermissionsType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEnvironmentMembershipsRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentMembershipsRequestRequestTypeDef",
     {
@@ -153,14 +151,23 @@
 DescribeEnvironmentStatusRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentStatusRequestRequestTypeDef",
     {
         "environmentId": str,
     },
 )
 
+DescribeEnvironmentStatusResultTypeDef = TypedDict(
+    "DescribeEnvironmentStatusResultTypeDef",
+    {
+        "status": EnvironmentStatusType,
+        "message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeEnvironmentsRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentsRequestRequestTypeDef",
     {
         "environmentIds": Sequence[str],
     },
 )
 
@@ -170,30 +177,68 @@
         "status": EnvironmentLifecycleStatusType,
         "reason": str,
         "failureResource": str,
     },
     total=False,
 )
 
+ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnvironmentsRequestRequestTypeDef = TypedDict(
     "ListEnvironmentsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListEnvironmentsResultTypeDef = TypedDict(
+    "ListEnvironmentsResultTypeDef",
+    {
+        "nextToken": str,
+        "environmentIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -253,100 +298,55 @@
 
 class CreateEnvironmentEC2RequestRequestTypeDef(
     _RequiredCreateEnvironmentEC2RequestRequestTypeDef,
     _OptionalCreateEnvironmentEC2RequestRequestTypeDef,
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateEnvironmentEC2ResultTypeDef = TypedDict(
-    "CreateEnvironmentEC2ResultTypeDef",
-    {
-        "environmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEnvironmentStatusResultTypeDef = TypedDict(
-    "DescribeEnvironmentStatusResultTypeDef",
-    {
-        "status": EnvironmentStatusType,
-        "message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListEnvironmentsResultTypeDef = TypedDict(
-    "ListEnvironmentsResultTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "nextToken": str,
-        "environmentIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 CreateEnvironmentMembershipResultTypeDef = TypedDict(
     "CreateEnvironmentMembershipResultTypeDef",
     {
         "membership": EnvironmentMemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEnvironmentMembershipsResultTypeDef = TypedDict(
     "DescribeEnvironmentMembershipsResultTypeDef",
     {
         "memberships": List[EnvironmentMemberTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEnvironmentMembershipResultTypeDef = TypedDict(
     "UpdateEnvironmentMembershipResultTypeDef",
     {
         "membership": EnvironmentMemberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef = TypedDict(
-    "DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef",
-    {
-        "userArn": str,
-        "environmentId": str,
-        "permissions": Sequence[PermissionsType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnvironmentsRequestListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsRequestListEnvironmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredEnvironmentTypeDef = TypedDict(
     "_RequiredEnvironmentTypeDef",
     {
         "type": EnvironmentTypeType,
         "arn": str,
         "ownerArn": str,
     },
@@ -367,10 +367,10 @@
 class EnvironmentTypeDef(_RequiredEnvironmentTypeDef, _OptionalEnvironmentTypeDef):
     pass
 
 DescribeEnvironmentsResultTypeDef = TypedDict(
     "DescribeEnvironmentsResultTypeDef",
     {
         "environments": List[EnvironmentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/PKG-INFO` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloud9
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Cloud9 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Cloud9 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloud9"></a>
 
 # types-aiobotocore-cloud9
 
 [![PyPI - types-aiobotocore-cloud9](https://img.shields.io/pypi/v/types-aiobotocore-cloud9.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloud9)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloud9.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloud9)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloud9?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloud9)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Cloud9 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
+[aiobotocore.Cloud9 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloud9.html#Cloud9)
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
 [types-aiobotocore-cloud9 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloud9/).
 
 See how it helps to find and fix potential bugs:
 
@@ -331,40 +331,40 @@
 
 `types_aiobotocore_cloud9.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloud9.type_defs import (
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateEnvironmentEC2ResultTypeDef,
     CreateEnvironmentMembershipRequestRequestTypeDef,
     EnvironmentMemberTypeDef,
     DeleteEnvironmentMembershipRequestRequestTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef,
     DescribeEnvironmentMembershipsRequestRequestTypeDef,
     DescribeEnvironmentStatusRequestRequestTypeDef,
+    DescribeEnvironmentStatusResultTypeDef,
     DescribeEnvironmentsRequestRequestTypeDef,
     EnvironmentLifecycleTypeDef,
+    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
+    ListEnvironmentsResultTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateEnvironmentMembershipRequestRequestTypeDef,
     UpdateEnvironmentRequestRequestTypeDef,
     CreateEnvironmentEC2RequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateEnvironmentEC2ResultTypeDef,
-    DescribeEnvironmentStatusResultTypeDef,
-    ListEnvironmentsResultTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateEnvironmentMembershipResultTypeDef,
     DescribeEnvironmentMembershipsResultTypeDef,
     UpdateEnvironmentMembershipResultTypeDef,
-    DescribeEnvironmentMembershipsRequestDescribeEnvironmentMembershipsPaginateTypeDef,
-    ListEnvironmentsRequestListEnvironmentsPaginateTypeDef,
     EnvironmentTypeDef,
     DescribeEnvironmentsResultTypeDef,
 )
 
 
 def get_structure() -> TagTypeDef:
     return {...}
@@ -373,43 +373,43 @@
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

### Comparing `types-aiobotocore-cloud9-2.5.0.post1/types_aiobotocore_cloud9.egg-info/SOURCES.txt` & `types-aiobotocore-cloud9-2.5.1/types_aiobotocore_cloud9.egg-info/SOURCES.txt`

 * *Files identical despite different names*

