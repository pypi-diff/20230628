# Comparing `tmp/types-aiobotocore-synthetics-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-synthetics-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-synthetics-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:26 2023, max compression
+gzip compressed data, was "types-aiobotocore-synthetics-2.5.1.tar", last modified: Wed Jun 28 01:44:16 2023, max compression
```

## Comparing `types-aiobotocore-synthetics-2.5.0.post1.tar` & `types-aiobotocore-synthetics-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:26.015681 types-aiobotocore-synthetics-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14327 2023-03-11 12:27:26.015681 types-aiobotocore-synthetics-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12744 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:26.015681 types-aiobotocore-synthetics-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:24:58.000000 types-aiobotocore-synthetics-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:26.011681 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/
--rw-r--r--   0 runner    (1001) docker     (123)      466 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      465 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17058 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17029 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8740 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8738 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    18357 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    18334 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:59.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:26.015681 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14327 2023-03-11 12:27:25.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      785 2023-03-11 12:27:25.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:25.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:25.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:27:25.000000 types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.750225 types-aiobotocore-synthetics-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14322 2023-06-28 01:44:16.750225 types-aiobotocore-synthetics-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12745 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:16.750225 types-aiobotocore-synthetics-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:41:47.000000 types-aiobotocore-synthetics-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.746225 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/
+-rw-r--r--   0 runner    (1001) docker     (123)      466 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      465 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17058 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17029 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8949 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8947 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    18381 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18358 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:48.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:16.750225 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14322 2023-06-28 01:44:16.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      785 2023-06-28 01:44:16.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:16.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:16.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:44:16.000000 types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/LICENSE` & `types-aiobotocore-synthetics-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/PKG-INFO` & `types-aiobotocore-synthetics-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-synthetics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Synthetics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Synthetics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-synthetics"></a>
 
 # types-aiobotocore-synthetics
 
 [![PyPI - types-aiobotocore-synthetics](https://img.shields.io/pypi/v/types-aiobotocore-synthetics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-synthetics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-synthetics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-synthetics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-synthetics?color=blue)](https://pypistats.org/packages/types-aiobotocore-synthetics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Synthetics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/synthetics.html#Synthetics)
+[aiobotocore.Synthetics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/synthetics.html#Synthetics)
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
 [types-aiobotocore-synthetics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -309,15 +309,14 @@
     CanaryRunTimelineTypeDef,
     CanaryScheduleInputTypeDef,
     CanaryScheduleOutputTypeDef,
     CanaryStatusTypeDef,
     CanaryTimelineTypeDef,
     VpcConfigOutputTypeDef,
     VpcConfigInputTypeDef,
-    ResponseMetadataTypeDef,
     CreateGroupRequestRequestTypeDef,
     GroupTypeDef,
     DeleteCanaryRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DescribeCanariesLastRunRequestRequestTypeDef,
     DescribeCanariesRequestRequestTypeDef,
     DescribeRuntimeVersionsRequestRequestTypeDef,
@@ -325,27 +324,28 @@
     DisassociateResourceRequestRequestTypeDef,
     GetCanaryRequestRequestTypeDef,
     GetCanaryRunsRequestRequestTypeDef,
     GetGroupRequestRequestTypeDef,
     GroupSummaryTypeDef,
     ListAssociatedGroupsRequestRequestTypeDef,
     ListGroupResourcesRequestRequestTypeDef,
+    ListGroupResourcesResponseTypeDef,
     ListGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartCanaryRequestRequestTypeDef,
     StopCanaryRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ArtifactConfigInputTypeDef,
     ArtifactConfigOutputTypeDef,
     VisualReferenceInputTypeDef,
     VisualReferenceOutputTypeDef,
     CanaryRunTypeDef,
-    ListGroupResourcesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateGroupResponseTypeDef,
     GetGroupResponseTypeDef,
     DescribeRuntimeVersionsResponseTypeDef,
     ListAssociatedGroupsResponseTypeDef,
     ListGroupsResponseTypeDef,
     CreateCanaryRequestRequestTypeDef,
     UpdateCanaryRequestRequestTypeDef,
@@ -366,43 +366,43 @@
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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/README.md` & `types-aiobotocore-synthetics-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-synthetics"></a>
 
 # types-aiobotocore-synthetics
 
 [![PyPI - types-aiobotocore-synthetics](https://img.shields.io/pypi/v/types-aiobotocore-synthetics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-synthetics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-synthetics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-synthetics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-synthetics?color=blue)](https://pypistats.org/packages/types-aiobotocore-synthetics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Synthetics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/synthetics.html#Synthetics)
+[aiobotocore.Synthetics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/synthetics.html#Synthetics)
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
 [types-aiobotocore-synthetics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,15 +276,14 @@
     CanaryRunTimelineTypeDef,
     CanaryScheduleInputTypeDef,
     CanaryScheduleOutputTypeDef,
     CanaryStatusTypeDef,
     CanaryTimelineTypeDef,
     VpcConfigOutputTypeDef,
     VpcConfigInputTypeDef,
-    ResponseMetadataTypeDef,
     CreateGroupRequestRequestTypeDef,
     GroupTypeDef,
     DeleteCanaryRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DescribeCanariesLastRunRequestRequestTypeDef,
     DescribeCanariesRequestRequestTypeDef,
     DescribeRuntimeVersionsRequestRequestTypeDef,
@@ -292,27 +291,28 @@
     DisassociateResourceRequestRequestTypeDef,
     GetCanaryRequestRequestTypeDef,
     GetCanaryRunsRequestRequestTypeDef,
     GetGroupRequestRequestTypeDef,
     GroupSummaryTypeDef,
     ListAssociatedGroupsRequestRequestTypeDef,
     ListGroupResourcesRequestRequestTypeDef,
+    ListGroupResourcesResponseTypeDef,
     ListGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartCanaryRequestRequestTypeDef,
     StopCanaryRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ArtifactConfigInputTypeDef,
     ArtifactConfigOutputTypeDef,
     VisualReferenceInputTypeDef,
     VisualReferenceOutputTypeDef,
     CanaryRunTypeDef,
-    ListGroupResourcesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateGroupResponseTypeDef,
     GetGroupResponseTypeDef,
     DescribeRuntimeVersionsResponseTypeDef,
     ListAssociatedGroupsResponseTypeDef,
     ListGroupsResponseTypeDef,
     CreateCanaryRequestRequestTypeDef,
     UpdateCanaryRequestRequestTypeDef,
@@ -333,43 +333,43 @@
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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/setup.py` & `types-aiobotocore-synthetics-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-synthetics.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-synthetics",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_synthetics"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Synthetics 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Synthetics 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/"
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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/__main__.py` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/__main__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Synthetics 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Synthetics 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/synthetics.html#Synthetics\nOther"
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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/client.py` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/client.pyi` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/literals.py` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -119,14 +119,15 @@
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
@@ -205,14 +206,15 @@
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
@@ -223,14 +225,15 @@
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
@@ -266,14 +269,15 @@
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
@@ -292,16 +296,19 @@
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
@@ -385,15 +392,17 @@
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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/literals.pyi` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -117,14 +117,15 @@
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
@@ -203,14 +204,15 @@
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
@@ -221,14 +223,15 @@
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
@@ -264,14 +267,15 @@
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
@@ -290,16 +294,19 @@
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
@@ -383,15 +390,17 @@
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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/type_defs.py` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/type_defs.py`

 * *Files 0% similar despite different names*

```diff
@@ -43,15 +43,14 @@
     "CanaryRunTimelineTypeDef",
     "CanaryScheduleInputTypeDef",
     "CanaryScheduleOutputTypeDef",
     "CanaryStatusTypeDef",
     "CanaryTimelineTypeDef",
     "VpcConfigOutputTypeDef",
     "VpcConfigInputTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateGroupRequestRequestTypeDef",
     "GroupTypeDef",
     "DeleteCanaryRequestRequestTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DescribeCanariesLastRunRequestRequestTypeDef",
     "DescribeCanariesRequestRequestTypeDef",
     "DescribeRuntimeVersionsRequestRequestTypeDef",
@@ -59,27 +58,28 @@
     "DisassociateResourceRequestRequestTypeDef",
     "GetCanaryRequestRequestTypeDef",
     "GetCanaryRunsRequestRequestTypeDef",
     "GetGroupRequestRequestTypeDef",
     "GroupSummaryTypeDef",
     "ListAssociatedGroupsRequestRequestTypeDef",
     "ListGroupResourcesRequestRequestTypeDef",
+    "ListGroupResourcesResponseTypeDef",
     "ListGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartCanaryRequestRequestTypeDef",
     "StopCanaryRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ArtifactConfigInputTypeDef",
     "ArtifactConfigOutputTypeDef",
     "VisualReferenceInputTypeDef",
     "VisualReferenceOutputTypeDef",
     "CanaryRunTypeDef",
-    "ListGroupResourcesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateGroupResponseTypeDef",
     "GetGroupResponseTypeDef",
     "DescribeRuntimeVersionsResponseTypeDef",
     "ListAssociatedGroupsResponseTypeDef",
     "ListGroupsResponseTypeDef",
     "CreateCanaryRequestRequestTypeDef",
     "UpdateCanaryRequestRequestTypeDef",
@@ -265,25 +265,14 @@
     {
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
     total=False,
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
 _RequiredCreateGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateGroupRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateGroupRequestRequestTypeDef = TypedDict(
@@ -478,14 +467,23 @@
 class ListGroupResourcesRequestRequestTypeDef(
     _RequiredListGroupResourcesRequestRequestTypeDef,
     _OptionalListGroupResourcesRequestRequestTypeDef,
 ):
     pass
 
 
+ListGroupResourcesResponseTypeDef = TypedDict(
+    "ListGroupResourcesResponseTypeDef",
+    {
+        "Resources": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListGroupsRequestRequestTypeDef = TypedDict(
     "ListGroupsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -494,14 +492,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
+    },
+)
+
 StartCanaryRequestRequestTypeDef = TypedDict(
     "StartCanaryRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -582,71 +599,54 @@
         "Status": CanaryRunStatusTypeDef,
         "Timeline": CanaryRunTimelineTypeDef,
         "ArtifactS3Location": str,
     },
     total=False,
 )
 
-ListGroupResourcesResponseTypeDef = TypedDict(
-    "ListGroupResourcesResponseTypeDef",
-    {
-        "Resources": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateGroupResponseTypeDef = TypedDict(
     "CreateGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupResponseTypeDef = TypedDict(
     "GetGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRuntimeVersionsResponseTypeDef = TypedDict(
     "DescribeRuntimeVersionsResponseTypeDef",
     {
         "RuntimeVersions": List[RuntimeVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssociatedGroupsResponseTypeDef = TypedDict(
     "ListAssociatedGroupsResponseTypeDef",
     {
         "Groups": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCanaryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCanaryRequestRequestTypeDef",
     {
         "Name": str,
@@ -742,44 +742,44 @@
 )
 
 GetCanaryRunsResponseTypeDef = TypedDict(
     "GetCanaryRunsResponseTypeDef",
     {
         "CanaryRuns": List[CanaryRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCanaryResponseTypeDef = TypedDict(
     "CreateCanaryResponseTypeDef",
     {
         "Canary": CanaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCanariesResponseTypeDef = TypedDict(
     "DescribeCanariesResponseTypeDef",
     {
         "Canaries": List[CanaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCanaryResponseTypeDef = TypedDict(
     "GetCanaryResponseTypeDef",
     {
         "Canary": CanaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCanariesLastRunResponseTypeDef = TypedDict(
     "DescribeCanariesLastRunResponseTypeDef",
     {
         "CanariesLastRun": List[CanaryLastRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics/type_defs.pyi` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics/type_defs.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -42,15 +42,14 @@
     "CanaryRunTimelineTypeDef",
     "CanaryScheduleInputTypeDef",
     "CanaryScheduleOutputTypeDef",
     "CanaryStatusTypeDef",
     "CanaryTimelineTypeDef",
     "VpcConfigOutputTypeDef",
     "VpcConfigInputTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateGroupRequestRequestTypeDef",
     "GroupTypeDef",
     "DeleteCanaryRequestRequestTypeDef",
     "DeleteGroupRequestRequestTypeDef",
     "DescribeCanariesLastRunRequestRequestTypeDef",
     "DescribeCanariesRequestRequestTypeDef",
     "DescribeRuntimeVersionsRequestRequestTypeDef",
@@ -58,27 +57,28 @@
     "DisassociateResourceRequestRequestTypeDef",
     "GetCanaryRequestRequestTypeDef",
     "GetCanaryRunsRequestRequestTypeDef",
     "GetGroupRequestRequestTypeDef",
     "GroupSummaryTypeDef",
     "ListAssociatedGroupsRequestRequestTypeDef",
     "ListGroupResourcesRequestRequestTypeDef",
+    "ListGroupResourcesResponseTypeDef",
     "ListGroupsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartCanaryRequestRequestTypeDef",
     "StopCanaryRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ArtifactConfigInputTypeDef",
     "ArtifactConfigOutputTypeDef",
     "VisualReferenceInputTypeDef",
     "VisualReferenceOutputTypeDef",
     "CanaryRunTypeDef",
-    "ListGroupResourcesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateGroupResponseTypeDef",
     "GetGroupResponseTypeDef",
     "DescribeRuntimeVersionsResponseTypeDef",
     "ListAssociatedGroupsResponseTypeDef",
     "ListGroupsResponseTypeDef",
     "CreateCanaryRequestRequestTypeDef",
     "UpdateCanaryRequestRequestTypeDef",
@@ -258,25 +258,14 @@
     {
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
     total=False,
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
 _RequiredCreateGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateGroupRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateGroupRequestRequestTypeDef = TypedDict(
@@ -461,14 +450,23 @@
 
 class ListGroupResourcesRequestRequestTypeDef(
     _RequiredListGroupResourcesRequestRequestTypeDef,
     _OptionalListGroupResourcesRequestRequestTypeDef,
 ):
     pass
 
+ListGroupResourcesResponseTypeDef = TypedDict(
+    "ListGroupResourcesResponseTypeDef",
+    {
+        "Resources": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListGroupsRequestRequestTypeDef = TypedDict(
     "ListGroupsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -477,14 +475,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
+    },
+)
+
 StartCanaryRequestRequestTypeDef = TypedDict(
     "StartCanaryRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -563,71 +580,54 @@
         "Status": CanaryRunStatusTypeDef,
         "Timeline": CanaryRunTimelineTypeDef,
         "ArtifactS3Location": str,
     },
     total=False,
 )
 
-ListGroupResourcesResponseTypeDef = TypedDict(
-    "ListGroupResourcesResponseTypeDef",
-    {
-        "Resources": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateGroupResponseTypeDef = TypedDict(
     "CreateGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGroupResponseTypeDef = TypedDict(
     "GetGroupResponseTypeDef",
     {
         "Group": GroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRuntimeVersionsResponseTypeDef = TypedDict(
     "DescribeRuntimeVersionsResponseTypeDef",
     {
         "RuntimeVersions": List[RuntimeVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssociatedGroupsResponseTypeDef = TypedDict(
     "ListAssociatedGroupsResponseTypeDef",
     {
         "Groups": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGroupsResponseTypeDef = TypedDict(
     "ListGroupsResponseTypeDef",
     {
         "Groups": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCanaryRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCanaryRequestRequestTypeDef",
     {
         "Name": str,
@@ -719,44 +719,44 @@
 )
 
 GetCanaryRunsResponseTypeDef = TypedDict(
     "GetCanaryRunsResponseTypeDef",
     {
         "CanaryRuns": List[CanaryRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCanaryResponseTypeDef = TypedDict(
     "CreateCanaryResponseTypeDef",
     {
         "Canary": CanaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCanariesResponseTypeDef = TypedDict(
     "DescribeCanariesResponseTypeDef",
     {
         "Canaries": List[CanaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCanaryResponseTypeDef = TypedDict(
     "GetCanaryResponseTypeDef",
     {
         "Canary": CanaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCanariesLastRunResponseTypeDef = TypedDict(
     "DescribeCanariesLastRunResponseTypeDef",
     {
         "CanariesLastRun": List[CanaryLastRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/PKG-INFO` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-synthetics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Synthetics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Synthetics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-synthetics"></a>
 
 # types-aiobotocore-synthetics
 
 [![PyPI - types-aiobotocore-synthetics](https://img.shields.io/pypi/v/types-aiobotocore-synthetics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-synthetics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-synthetics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-synthetics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-synthetics?color=blue)](https://pypistats.org/packages/types-aiobotocore-synthetics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Synthetics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/synthetics.html#Synthetics)
+[aiobotocore.Synthetics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/synthetics.html#Synthetics)
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
 [types-aiobotocore-synthetics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_synthetics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -309,15 +309,14 @@
     CanaryRunTimelineTypeDef,
     CanaryScheduleInputTypeDef,
     CanaryScheduleOutputTypeDef,
     CanaryStatusTypeDef,
     CanaryTimelineTypeDef,
     VpcConfigOutputTypeDef,
     VpcConfigInputTypeDef,
-    ResponseMetadataTypeDef,
     CreateGroupRequestRequestTypeDef,
     GroupTypeDef,
     DeleteCanaryRequestRequestTypeDef,
     DeleteGroupRequestRequestTypeDef,
     DescribeCanariesLastRunRequestRequestTypeDef,
     DescribeCanariesRequestRequestTypeDef,
     DescribeRuntimeVersionsRequestRequestTypeDef,
@@ -325,27 +324,28 @@
     DisassociateResourceRequestRequestTypeDef,
     GetCanaryRequestRequestTypeDef,
     GetCanaryRunsRequestRequestTypeDef,
     GetGroupRequestRequestTypeDef,
     GroupSummaryTypeDef,
     ListAssociatedGroupsRequestRequestTypeDef,
     ListGroupResourcesRequestRequestTypeDef,
+    ListGroupResourcesResponseTypeDef,
     ListGroupsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartCanaryRequestRequestTypeDef,
     StopCanaryRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ArtifactConfigInputTypeDef,
     ArtifactConfigOutputTypeDef,
     VisualReferenceInputTypeDef,
     VisualReferenceOutputTypeDef,
     CanaryRunTypeDef,
-    ListGroupResourcesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateGroupResponseTypeDef,
     GetGroupResponseTypeDef,
     DescribeRuntimeVersionsResponseTypeDef,
     ListAssociatedGroupsResponseTypeDef,
     ListGroupsResponseTypeDef,
     CreateCanaryRequestRequestTypeDef,
     UpdateCanaryRequestRequestTypeDef,
@@ -366,43 +366,43 @@
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

### Comparing `types-aiobotocore-synthetics-2.5.0.post1/types_aiobotocore_synthetics.egg-info/SOURCES.txt` & `types-aiobotocore-synthetics-2.5.1/types_aiobotocore_synthetics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

