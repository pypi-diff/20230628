# Comparing `tmp/types-aiobotocore-mediastore-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mediastore-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mediastore-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:59 2023, max compression
+gzip compressed data, was "types-aiobotocore-mediastore-2.5.1.tar", last modified: Wed Jun 28 01:43:51 2023, max compression
```

## Comparing `types-aiobotocore-mediastore-2.5.0.post1.tar` & `types-aiobotocore-mediastore-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.223422 types-aiobotocore-mediastore-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14401 2023-03-11 12:26:59.223422 types-aiobotocore-mediastore-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12818 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:59.223422 types-aiobotocore-mediastore-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.223422 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/
--rw-r--r--   0 runner    (1001) docker     (123)      671 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      670 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16111 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    16080 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7976 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7974 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2134 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2130 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     9298 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     9289 2023-03-11 12:18:36.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:35.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:59.223422 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14401 2023-03-11 12:26:59.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:59.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:59.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:59.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:59.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:59.000000 types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.326177 types-aiobotocore-mediastore-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14396 2023-06-28 01:43:51.326177 types-aiobotocore-mediastore-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12819 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:51.326177 types-aiobotocore-mediastore-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.326177 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/
+-rw-r--r--   0 runner    (1001) docker     (123)      671 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      670 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16111 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16080 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8185 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8183 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2016 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2013 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     9316 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9307 2023-06-28 01:35:19.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:18.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.326177 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14396 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:51.000000 types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/LICENSE` & `types-aiobotocore-mediastore-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mediastore-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediastore
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaStore 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaStore 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediastore"></a>
 
 # types-aiobotocore-mediastore
 
 [![PyPI - types-aiobotocore-mediastore](https://img.shields.io/pypi/v/types-aiobotocore-mediastore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediastore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediastore?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediastore)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaStore 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore)
+[aiobotocore.MediaStore 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore)
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
 [types-aiobotocore-mediastore docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,45 +320,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediastore.type_defs import (
     ContainerTypeDef,
     CorsRuleTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteContainerInputRequestTypeDef,
     DeleteContainerPolicyInputRequestTypeDef,
     DeleteCorsPolicyInputRequestTypeDef,
     DeleteLifecyclePolicyInputRequestTypeDef,
     DeleteMetricPolicyInputRequestTypeDef,
     DescribeContainerInputRequestTypeDef,
     GetContainerPolicyInputRequestTypeDef,
+    GetContainerPolicyOutputTypeDef,
     GetCorsPolicyInputRequestTypeDef,
     GetLifecyclePolicyInputRequestTypeDef,
+    GetLifecyclePolicyOutputTypeDef,
     GetMetricPolicyInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListContainersInputListContainersPaginateTypeDef,
     ListContainersInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     MetricPolicyRuleTypeDef,
+    PaginatorConfigTypeDef,
     PutContainerPolicyInputRequestTypeDef,
     PutLifecyclePolicyInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartAccessLoggingInputRequestTypeDef,
     StopAccessLoggingInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
-    PutCorsPolicyInputRequestTypeDef,
-    CreateContainerInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
     CreateContainerOutputTypeDef,
     DescribeContainerOutputTypeDef,
-    GetContainerPolicyOutputTypeDef,
-    GetCorsPolicyOutputTypeDef,
-    GetLifecyclePolicyOutputTypeDef,
     ListContainersOutputTypeDef,
+    GetCorsPolicyOutputTypeDef,
+    PutCorsPolicyInputRequestTypeDef,
+    CreateContainerInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
-    ListContainersInputListContainersPaginateTypeDef,
+    TagResourceInputRequestTypeDef,
     MetricPolicyTypeDef,
     GetMetricPolicyOutputTypeDef,
     PutMetricPolicyInputRequestTypeDef,
 )
 
 
 def get_structure() -> ContainerTypeDef:
@@ -368,43 +368,43 @@
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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/README.md` & `types-aiobotocore-mediastore-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mediastore"></a>
 
 # types-aiobotocore-mediastore
 
 [![PyPI - types-aiobotocore-mediastore](https://img.shields.io/pypi/v/types-aiobotocore-mediastore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediastore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediastore?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediastore)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaStore 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore)
+[aiobotocore.MediaStore 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore)
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
 [types-aiobotocore-mediastore docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,45 +287,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediastore.type_defs import (
     ContainerTypeDef,
     CorsRuleTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteContainerInputRequestTypeDef,
     DeleteContainerPolicyInputRequestTypeDef,
     DeleteCorsPolicyInputRequestTypeDef,
     DeleteLifecyclePolicyInputRequestTypeDef,
     DeleteMetricPolicyInputRequestTypeDef,
     DescribeContainerInputRequestTypeDef,
     GetContainerPolicyInputRequestTypeDef,
+    GetContainerPolicyOutputTypeDef,
     GetCorsPolicyInputRequestTypeDef,
     GetLifecyclePolicyInputRequestTypeDef,
+    GetLifecyclePolicyOutputTypeDef,
     GetMetricPolicyInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListContainersInputListContainersPaginateTypeDef,
     ListContainersInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     MetricPolicyRuleTypeDef,
+    PaginatorConfigTypeDef,
     PutContainerPolicyInputRequestTypeDef,
     PutLifecyclePolicyInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartAccessLoggingInputRequestTypeDef,
     StopAccessLoggingInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
-    PutCorsPolicyInputRequestTypeDef,
-    CreateContainerInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
     CreateContainerOutputTypeDef,
     DescribeContainerOutputTypeDef,
-    GetContainerPolicyOutputTypeDef,
-    GetCorsPolicyOutputTypeDef,
-    GetLifecyclePolicyOutputTypeDef,
     ListContainersOutputTypeDef,
+    GetCorsPolicyOutputTypeDef,
+    PutCorsPolicyInputRequestTypeDef,
+    CreateContainerInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
-    ListContainersInputListContainersPaginateTypeDef,
+    TagResourceInputRequestTypeDef,
     MetricPolicyTypeDef,
     GetMetricPolicyOutputTypeDef,
     PutMetricPolicyInputRequestTypeDef,
 )
 
 
 def get_structure() -> ContainerTypeDef:
@@ -335,43 +335,43 @@
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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/setup.py` & `types-aiobotocore-mediastore-2.5.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mediastore.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mediastore",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mediastore"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaStore 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MediaStore 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/"
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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/__init__.py` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/__init__.pyi` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/__main__.py` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaStore 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaStore 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore\nOther"
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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/client.py` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/client.pyi` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/literals.py` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -95,14 +95,15 @@
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
@@ -181,14 +182,15 @@
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
@@ -199,14 +201,15 @@
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
@@ -242,14 +245,15 @@
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
@@ -268,16 +272,19 @@
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
@@ -361,15 +368,17 @@
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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/literals.pyi` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -93,14 +93,15 @@
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
@@ -179,14 +180,15 @@
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
@@ -197,14 +199,15 @@
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
@@ -240,14 +243,15 @@
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
@@ -266,16 +270,19 @@
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
@@ -359,15 +366,17 @@
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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/paginator.py` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("mediastore") as client:
         client: MediaStoreClient
 
         list_containers_paginator: ListContainersPaginator = client.get_paginator("list_containers")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListContainersOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListContainersPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListContainersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore.Paginator.ListContainers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/paginators/#listcontainerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListContainersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore.Paginator.ListContainers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/paginators/#listcontainerspaginator)
         """
```

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/paginator.pyi` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("mediastore") as client:
         client: MediaStoreClient
 
         list_containers_paginator: ListContainersPaginator = client.get_paginator("list_containers")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListContainersOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListContainersPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListContainersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore.Paginator.ListContainers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/paginators/#listcontainerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListContainersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore.Paginator.ListContainers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/paginators/#listcontainerspaginator)
         """
```

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/type_defs.py` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,50 +18,49 @@
 from .literals import ContainerLevelMetricsType, ContainerStatusType, MethodNameType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ContainerTypeDef",
     "CorsRuleTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteContainerInputRequestTypeDef",
     "DeleteContainerPolicyInputRequestTypeDef",
     "DeleteCorsPolicyInputRequestTypeDef",
     "DeleteLifecyclePolicyInputRequestTypeDef",
     "DeleteMetricPolicyInputRequestTypeDef",
     "DescribeContainerInputRequestTypeDef",
     "GetContainerPolicyInputRequestTypeDef",
+    "GetContainerPolicyOutputTypeDef",
     "GetCorsPolicyInputRequestTypeDef",
     "GetLifecyclePolicyInputRequestTypeDef",
+    "GetLifecyclePolicyOutputTypeDef",
     "GetMetricPolicyInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListContainersInputListContainersPaginateTypeDef",
     "ListContainersInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "MetricPolicyRuleTypeDef",
+    "PaginatorConfigTypeDef",
     "PutContainerPolicyInputRequestTypeDef",
     "PutLifecyclePolicyInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAccessLoggingInputRequestTypeDef",
     "StopAccessLoggingInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
-    "PutCorsPolicyInputRequestTypeDef",
-    "CreateContainerInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
     "CreateContainerOutputTypeDef",
     "DescribeContainerOutputTypeDef",
-    "GetContainerPolicyOutputTypeDef",
-    "GetCorsPolicyOutputTypeDef",
-    "GetLifecyclePolicyOutputTypeDef",
     "ListContainersOutputTypeDef",
+    "GetCorsPolicyOutputTypeDef",
+    "PutCorsPolicyInputRequestTypeDef",
+    "CreateContainerInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
-    "ListContainersInputListContainersPaginateTypeDef",
+    "TagResourceInputRequestTypeDef",
     "MetricPolicyTypeDef",
     "GetMetricPolicyOutputTypeDef",
     "PutMetricPolicyInputRequestTypeDef",
 )
 
 ContainerTypeDef = TypedDict(
     "ContainerTypeDef",
@@ -89,49 +88,34 @@
         "AllowedMethods": List[MethodNameType],
         "MaxAgeSeconds": int,
         "ExposeHeaders": List[str],
     },
     total=False,
 )
 
-
 class CorsRuleTypeDef(_RequiredCorsRuleTypeDef, _OptionalCorsRuleTypeDef):
     pass
 
-
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
     "_OptionalTagTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
-
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
-
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
 DeleteContainerInputRequestTypeDef = TypedDict(
     "DeleteContainerInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
@@ -174,41 +158,55 @@
 GetContainerPolicyInputRequestTypeDef = TypedDict(
     "GetContainerPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
+GetContainerPolicyOutputTypeDef = TypedDict(
+    "GetContainerPolicyOutputTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCorsPolicyInputRequestTypeDef = TypedDict(
     "GetCorsPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
 GetLifecyclePolicyInputRequestTypeDef = TypedDict(
     "GetLifecyclePolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
+GetLifecyclePolicyOutputTypeDef = TypedDict(
+    "GetLifecyclePolicyOutputTypeDef",
+    {
+        "LifecyclePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMetricPolicyInputRequestTypeDef = TypedDict(
     "GetMetricPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListContainersInputListContainersPaginateTypeDef = TypedDict(
+    "ListContainersInputListContainersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListContainersInputRequestTypeDef = TypedDict(
     "ListContainersInputRequestTypeDef",
     {
@@ -229,14 +227,24 @@
     "MetricPolicyRuleTypeDef",
     {
         "ObjectGroup": str,
         "ObjectGroupName": str,
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
 PutContainerPolicyInputRequestTypeDef = TypedDict(
     "PutContainerPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
         "Policy": str,
     },
 )
@@ -245,14 +253,25 @@
     "PutLifecyclePolicyInputRequestTypeDef",
     {
         "ContainerName": str,
         "LifecyclePolicy": str,
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
 StartAccessLoggingInputRequestTypeDef = TypedDict(
     "StartAccessLoggingInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
@@ -267,114 +286,88 @@
     "UntagResourceInputRequestTypeDef",
     {
         "Resource": str,
         "TagKeys": Sequence[str],
     },
 )
 
-PutCorsPolicyInputRequestTypeDef = TypedDict(
-    "PutCorsPolicyInputRequestTypeDef",
-    {
-        "ContainerName": str,
-        "CorsPolicy": Sequence[CorsRuleTypeDef],
-    },
-)
-
-_RequiredCreateContainerInputRequestTypeDef = TypedDict(
-    "_RequiredCreateContainerInputRequestTypeDef",
-    {
-        "ContainerName": str,
-    },
-)
-_OptionalCreateContainerInputRequestTypeDef = TypedDict(
-    "_OptionalCreateContainerInputRequestTypeDef",
-    {
-        "Tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-
-class CreateContainerInputRequestTypeDef(
-    _RequiredCreateContainerInputRequestTypeDef, _OptionalCreateContainerInputRequestTypeDef
-):
-    pass
-
-
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "Resource": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
 CreateContainerOutputTypeDef = TypedDict(
     "CreateContainerOutputTypeDef",
     {
         "Container": ContainerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContainerOutputTypeDef = TypedDict(
     "DescribeContainerOutputTypeDef",
     {
         "Container": ContainerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetContainerPolicyOutputTypeDef = TypedDict(
-    "GetContainerPolicyOutputTypeDef",
+ListContainersOutputTypeDef = TypedDict(
+    "ListContainersOutputTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Containers": List[ContainerTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCorsPolicyOutputTypeDef = TypedDict(
     "GetCorsPolicyOutputTypeDef",
     {
         "CorsPolicy": List[CorsRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetLifecyclePolicyOutputTypeDef = TypedDict(
-    "GetLifecyclePolicyOutputTypeDef",
+PutCorsPolicyInputRequestTypeDef = TypedDict(
+    "PutCorsPolicyInputRequestTypeDef",
     {
-        "LifecyclePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ContainerName": str,
+        "CorsPolicy": Sequence[CorsRuleTypeDef],
     },
 )
 
-ListContainersOutputTypeDef = TypedDict(
-    "ListContainersOutputTypeDef",
+_RequiredCreateContainerInputRequestTypeDef = TypedDict(
+    "_RequiredCreateContainerInputRequestTypeDef",
     {
-        "Containers": List[ContainerTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ContainerName": str,
+    },
+)
+_OptionalCreateContainerInputRequestTypeDef = TypedDict(
+    "_OptionalCreateContainerInputRequestTypeDef",
+    {
+        "Tags": Sequence[TagTypeDef],
     },
+    total=False,
 )
 
+class CreateContainerInputRequestTypeDef(
+    _RequiredCreateContainerInputRequestTypeDef, _OptionalCreateContainerInputRequestTypeDef
+):
+    pass
+
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListContainersInputListContainersPaginateTypeDef = TypedDict(
-    "ListContainersInputListContainersPaginateTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Resource": str,
+        "Tags": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
 _RequiredMetricPolicyTypeDef = TypedDict(
     "_RequiredMetricPolicyTypeDef",
     {
         "ContainerLevelMetrics": ContainerLevelMetricsType,
     },
@@ -383,24 +376,22 @@
     "_OptionalMetricPolicyTypeDef",
     {
         "MetricPolicyRules": List[MetricPolicyRuleTypeDef],
     },
     total=False,
 )
 
-
 class MetricPolicyTypeDef(_RequiredMetricPolicyTypeDef, _OptionalMetricPolicyTypeDef):
     pass
 
-
 GetMetricPolicyOutputTypeDef = TypedDict(
     "GetMetricPolicyOutputTypeDef",
     {
         "MetricPolicy": MetricPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutMetricPolicyInputRequestTypeDef = TypedDict(
     "PutMetricPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
```

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore/type_defs.pyi` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,49 +18,50 @@
 from .literals import ContainerLevelMetricsType, ContainerStatusType, MethodNameType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ContainerTypeDef",
     "CorsRuleTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "DeleteContainerInputRequestTypeDef",
     "DeleteContainerPolicyInputRequestTypeDef",
     "DeleteCorsPolicyInputRequestTypeDef",
     "DeleteLifecyclePolicyInputRequestTypeDef",
     "DeleteMetricPolicyInputRequestTypeDef",
     "DescribeContainerInputRequestTypeDef",
     "GetContainerPolicyInputRequestTypeDef",
+    "GetContainerPolicyOutputTypeDef",
     "GetCorsPolicyInputRequestTypeDef",
     "GetLifecyclePolicyInputRequestTypeDef",
+    "GetLifecyclePolicyOutputTypeDef",
     "GetMetricPolicyInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListContainersInputListContainersPaginateTypeDef",
     "ListContainersInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
     "MetricPolicyRuleTypeDef",
+    "PaginatorConfigTypeDef",
     "PutContainerPolicyInputRequestTypeDef",
     "PutLifecyclePolicyInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAccessLoggingInputRequestTypeDef",
     "StopAccessLoggingInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
-    "PutCorsPolicyInputRequestTypeDef",
-    "CreateContainerInputRequestTypeDef",
-    "TagResourceInputRequestTypeDef",
     "CreateContainerOutputTypeDef",
     "DescribeContainerOutputTypeDef",
-    "GetContainerPolicyOutputTypeDef",
-    "GetCorsPolicyOutputTypeDef",
-    "GetLifecyclePolicyOutputTypeDef",
     "ListContainersOutputTypeDef",
+    "GetCorsPolicyOutputTypeDef",
+    "PutCorsPolicyInputRequestTypeDef",
+    "CreateContainerInputRequestTypeDef",
     "ListTagsForResourceOutputTypeDef",
-    "ListContainersInputListContainersPaginateTypeDef",
+    "TagResourceInputRequestTypeDef",
     "MetricPolicyTypeDef",
     "GetMetricPolicyOutputTypeDef",
     "PutMetricPolicyInputRequestTypeDef",
 )
 
 ContainerTypeDef = TypedDict(
     "ContainerTypeDef",
@@ -88,44 +89,37 @@
         "AllowedMethods": List[MethodNameType],
         "MaxAgeSeconds": int,
         "ExposeHeaders": List[str],
     },
     total=False,
 )
 
+
 class CorsRuleTypeDef(_RequiredCorsRuleTypeDef, _OptionalCorsRuleTypeDef):
     pass
 
+
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
     "_OptionalTagTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
+
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
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
 
 DeleteContainerInputRequestTypeDef = TypedDict(
     "DeleteContainerInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
@@ -169,41 +163,55 @@
 GetContainerPolicyInputRequestTypeDef = TypedDict(
     "GetContainerPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
+GetContainerPolicyOutputTypeDef = TypedDict(
+    "GetContainerPolicyOutputTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCorsPolicyInputRequestTypeDef = TypedDict(
     "GetCorsPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
 GetLifecyclePolicyInputRequestTypeDef = TypedDict(
     "GetLifecyclePolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
+GetLifecyclePolicyOutputTypeDef = TypedDict(
+    "GetLifecyclePolicyOutputTypeDef",
+    {
+        "LifecyclePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMetricPolicyInputRequestTypeDef = TypedDict(
     "GetMetricPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListContainersInputListContainersPaginateTypeDef = TypedDict(
+    "ListContainersInputListContainersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListContainersInputRequestTypeDef = TypedDict(
     "ListContainersInputRequestTypeDef",
     {
@@ -224,14 +232,24 @@
     "MetricPolicyRuleTypeDef",
     {
         "ObjectGroup": str,
         "ObjectGroupName": str,
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
 PutContainerPolicyInputRequestTypeDef = TypedDict(
     "PutContainerPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
         "Policy": str,
     },
 )
@@ -240,14 +258,25 @@
     "PutLifecyclePolicyInputRequestTypeDef",
     {
         "ContainerName": str,
         "LifecyclePolicy": str,
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
 StartAccessLoggingInputRequestTypeDef = TypedDict(
     "StartAccessLoggingInputRequestTypeDef",
     {
         "ContainerName": str,
     },
 )
 
@@ -262,112 +291,90 @@
     "UntagResourceInputRequestTypeDef",
     {
         "Resource": str,
         "TagKeys": Sequence[str],
     },
 )
 
-PutCorsPolicyInputRequestTypeDef = TypedDict(
-    "PutCorsPolicyInputRequestTypeDef",
-    {
-        "ContainerName": str,
-        "CorsPolicy": Sequence[CorsRuleTypeDef],
-    },
-)
-
-_RequiredCreateContainerInputRequestTypeDef = TypedDict(
-    "_RequiredCreateContainerInputRequestTypeDef",
-    {
-        "ContainerName": str,
-    },
-)
-_OptionalCreateContainerInputRequestTypeDef = TypedDict(
-    "_OptionalCreateContainerInputRequestTypeDef",
-    {
-        "Tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-class CreateContainerInputRequestTypeDef(
-    _RequiredCreateContainerInputRequestTypeDef, _OptionalCreateContainerInputRequestTypeDef
-):
-    pass
-
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "Resource": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
 CreateContainerOutputTypeDef = TypedDict(
     "CreateContainerOutputTypeDef",
     {
         "Container": ContainerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContainerOutputTypeDef = TypedDict(
     "DescribeContainerOutputTypeDef",
     {
         "Container": ContainerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetContainerPolicyOutputTypeDef = TypedDict(
-    "GetContainerPolicyOutputTypeDef",
+ListContainersOutputTypeDef = TypedDict(
+    "ListContainersOutputTypeDef",
     {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Containers": List[ContainerTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCorsPolicyOutputTypeDef = TypedDict(
     "GetCorsPolicyOutputTypeDef",
     {
         "CorsPolicy": List[CorsRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetLifecyclePolicyOutputTypeDef = TypedDict(
-    "GetLifecyclePolicyOutputTypeDef",
+PutCorsPolicyInputRequestTypeDef = TypedDict(
+    "PutCorsPolicyInputRequestTypeDef",
     {
-        "LifecyclePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ContainerName": str,
+        "CorsPolicy": Sequence[CorsRuleTypeDef],
     },
 )
 
-ListContainersOutputTypeDef = TypedDict(
-    "ListContainersOutputTypeDef",
+_RequiredCreateContainerInputRequestTypeDef = TypedDict(
+    "_RequiredCreateContainerInputRequestTypeDef",
     {
-        "Containers": List[ContainerTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ContainerName": str,
+    },
+)
+_OptionalCreateContainerInputRequestTypeDef = TypedDict(
+    "_OptionalCreateContainerInputRequestTypeDef",
+    {
+        "Tags": Sequence[TagTypeDef],
     },
+    total=False,
 )
 
+
+class CreateContainerInputRequestTypeDef(
+    _RequiredCreateContainerInputRequestTypeDef, _OptionalCreateContainerInputRequestTypeDef
+):
+    pass
+
+
 ListTagsForResourceOutputTypeDef = TypedDict(
     "ListTagsForResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListContainersInputListContainersPaginateTypeDef = TypedDict(
-    "ListContainersInputListContainersPaginateTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Resource": str,
+        "Tags": Sequence[TagTypeDef],
     },
-    total=False,
 )
 
 _RequiredMetricPolicyTypeDef = TypedDict(
     "_RequiredMetricPolicyTypeDef",
     {
         "ContainerLevelMetrics": ContainerLevelMetricsType,
     },
@@ -376,22 +383,24 @@
     "_OptionalMetricPolicyTypeDef",
     {
         "MetricPolicyRules": List[MetricPolicyRuleTypeDef],
     },
     total=False,
 )
 
+
 class MetricPolicyTypeDef(_RequiredMetricPolicyTypeDef, _OptionalMetricPolicyTypeDef):
     pass
 
+
 GetMetricPolicyOutputTypeDef = TypedDict(
     "GetMetricPolicyOutputTypeDef",
     {
         "MetricPolicy": MetricPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutMetricPolicyInputRequestTypeDef = TypedDict(
     "PutMetricPolicyInputRequestTypeDef",
     {
         "ContainerName": str,
```

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/PKG-INFO` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mediastore
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaStore 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaStore 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mediastore"></a>
 
 # types-aiobotocore-mediastore
 
 [![PyPI - types-aiobotocore-mediastore](https://img.shields.io/pypi/v/types-aiobotocore-mediastore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mediastore.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mediastore)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mediastore?color=blue)](https://pypistats.org/packages/types-aiobotocore-mediastore)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaStore 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore)
+[aiobotocore.MediaStore 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mediastore.html#MediaStore)
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
 [types-aiobotocore-mediastore docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,45 +320,45 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mediastore.type_defs import (
     ContainerTypeDef,
     CorsRuleTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     DeleteContainerInputRequestTypeDef,
     DeleteContainerPolicyInputRequestTypeDef,
     DeleteCorsPolicyInputRequestTypeDef,
     DeleteLifecyclePolicyInputRequestTypeDef,
     DeleteMetricPolicyInputRequestTypeDef,
     DescribeContainerInputRequestTypeDef,
     GetContainerPolicyInputRequestTypeDef,
+    GetContainerPolicyOutputTypeDef,
     GetCorsPolicyInputRequestTypeDef,
     GetLifecyclePolicyInputRequestTypeDef,
+    GetLifecyclePolicyOutputTypeDef,
     GetMetricPolicyInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListContainersInputListContainersPaginateTypeDef,
     ListContainersInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
     MetricPolicyRuleTypeDef,
+    PaginatorConfigTypeDef,
     PutContainerPolicyInputRequestTypeDef,
     PutLifecyclePolicyInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartAccessLoggingInputRequestTypeDef,
     StopAccessLoggingInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
-    PutCorsPolicyInputRequestTypeDef,
-    CreateContainerInputRequestTypeDef,
-    TagResourceInputRequestTypeDef,
     CreateContainerOutputTypeDef,
     DescribeContainerOutputTypeDef,
-    GetContainerPolicyOutputTypeDef,
-    GetCorsPolicyOutputTypeDef,
-    GetLifecyclePolicyOutputTypeDef,
     ListContainersOutputTypeDef,
+    GetCorsPolicyOutputTypeDef,
+    PutCorsPolicyInputRequestTypeDef,
+    CreateContainerInputRequestTypeDef,
     ListTagsForResourceOutputTypeDef,
-    ListContainersInputListContainersPaginateTypeDef,
+    TagResourceInputRequestTypeDef,
     MetricPolicyTypeDef,
     GetMetricPolicyOutputTypeDef,
     PutMetricPolicyInputRequestTypeDef,
 )
 
 
 def get_structure() -> ContainerTypeDef:
@@ -368,43 +368,43 @@
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

### Comparing `types-aiobotocore-mediastore-2.5.0.post1/types_aiobotocore_mediastore.egg-info/SOURCES.txt` & `types-aiobotocore-mediastore-2.5.1/types_aiobotocore_mediastore.egg-info/SOURCES.txt`

 * *Files identical despite different names*

