# Comparing `tmp/types-aiobotocore-dlm-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-dlm-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-dlm-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:30 2023, max compression
+gzip compressed data, was "types-aiobotocore-dlm-2.5.1.tar", last modified: Wed Jun 28 01:43:23 2023, max compression
```

## Comparing `types-aiobotocore-dlm-2.5.0.post1.tar` & `types-aiobotocore-dlm-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:30.967136 types-aiobotocore-dlm-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13291 2023-03-11 12:26:30.967136 types-aiobotocore-dlm-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11736 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:30.967136 types-aiobotocore-dlm-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:30.967136 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      409 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8835 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8819 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8729 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8727 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    12401 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    12384 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:31.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:30.967136 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13291 2023-03-11 12:26:30.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      666 2023-03-11 12:26:30.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:30.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:30.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:30.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:30.000000 types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:23.478125 types-aiobotocore-dlm-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13279 2023-06-28 01:43:23.478125 types-aiobotocore-dlm-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11730 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:23.478125 types-aiobotocore-dlm-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:23.474125 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      409 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8835 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8819 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8976 2023-06-28 01:29:11.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8974 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    12409 2023-06-28 01:29:11.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12392 2023-06-28 01:29:11.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:10.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:23.478125 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13279 2023-06-28 01:43:23.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      666 2023-06-28 01:43:23.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:23.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:23.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:23.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:23.000000 types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-dlm-2.5.0.post1/LICENSE` & `types-aiobotocore-dlm-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/PKG-INFO` & `types-aiobotocore-dlm-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dlm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DLM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DLM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dlm"></a>
 
 # types-aiobotocore-dlm
 
 [![PyPI - types-aiobotocore-dlm](https://img.shields.io/pypi/v/types-aiobotocore-dlm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dlm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dlm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dlm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dlm?color=blue)](https://pypistats.org/packages/types-aiobotocore-dlm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DLM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM)
+[aiobotocore.DLM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM)
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
 [types-aiobotocore-dlm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,35 +298,35 @@
 
 `types_aiobotocore_dlm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dlm.type_defs import (
     RetentionArchiveTierTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLifecyclePolicyResponseTypeDef,
     CreateRuleTypeDef,
     CrossRegionCopyRetainRuleTypeDef,
     EncryptionConfigurationTypeDef,
     CrossRegionCopyDeprecateRuleTypeDef,
     DeleteLifecyclePolicyRequestRequestTypeDef,
     DeprecateRuleTypeDef,
     EventParametersTypeDef,
     FastRestoreRuleTypeDef,
     GetLifecyclePoliciesRequestRequestTypeDef,
     LifecyclePolicySummaryTypeDef,
     GetLifecyclePolicyRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagTypeDef,
+    ResponseMetadataTypeDef,
     RetainRuleTypeDef,
     ShareRuleTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ArchiveRetainRuleTypeDef,
-    CreateLifecyclePolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CrossRegionCopyActionTypeDef,
     CrossRegionCopyRuleTypeDef,
     EventSourceTypeDef,
     GetLifecyclePoliciesResponseTypeDef,
     ParametersTypeDef,
     ArchiveRuleTypeDef,
     ActionTypeDef,
@@ -346,43 +346,43 @@
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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/README.md` & `types-aiobotocore-dlm-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-dlm"></a>
 
 # types-aiobotocore-dlm
 
 [![PyPI - types-aiobotocore-dlm](https://img.shields.io/pypi/v/types-aiobotocore-dlm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dlm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dlm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dlm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dlm?color=blue)](https://pypistats.org/packages/types-aiobotocore-dlm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DLM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM)
+[aiobotocore.DLM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM)
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
 [types-aiobotocore-dlm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -265,35 +265,35 @@
 
 `types_aiobotocore_dlm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dlm.type_defs import (
     RetentionArchiveTierTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLifecyclePolicyResponseTypeDef,
     CreateRuleTypeDef,
     CrossRegionCopyRetainRuleTypeDef,
     EncryptionConfigurationTypeDef,
     CrossRegionCopyDeprecateRuleTypeDef,
     DeleteLifecyclePolicyRequestRequestTypeDef,
     DeprecateRuleTypeDef,
     EventParametersTypeDef,
     FastRestoreRuleTypeDef,
     GetLifecyclePoliciesRequestRequestTypeDef,
     LifecyclePolicySummaryTypeDef,
     GetLifecyclePolicyRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagTypeDef,
+    ResponseMetadataTypeDef,
     RetainRuleTypeDef,
     ShareRuleTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ArchiveRetainRuleTypeDef,
-    CreateLifecyclePolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CrossRegionCopyActionTypeDef,
     CrossRegionCopyRuleTypeDef,
     EventSourceTypeDef,
     GetLifecyclePoliciesResponseTypeDef,
     ParametersTypeDef,
     ArchiveRuleTypeDef,
     ActionTypeDef,
@@ -313,43 +313,43 @@
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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/setup.py` & `types-aiobotocore-dlm-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-dlm.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-dlm",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_dlm"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DLM 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.DLM 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/",
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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/__main__.py` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/__main__.py`

 * *Files 23% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DLM 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DLM 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM\nOther"
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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/client.py` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/client.pyi` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/literals.py` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -106,14 +106,15 @@
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
@@ -192,14 +193,15 @@
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
@@ -210,14 +212,15 @@
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
@@ -253,14 +256,15 @@
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
@@ -279,16 +283,19 @@
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
@@ -372,15 +379,17 @@
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
@@ -411,16 +420,18 @@
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
     "ap-southeast-4",
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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/literals.pyi` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -104,14 +104,15 @@
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
@@ -190,14 +191,15 @@
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
@@ -208,14 +210,15 @@
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
@@ -251,14 +254,15 @@
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
@@ -277,16 +281,19 @@
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
@@ -370,15 +377,17 @@
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
@@ -409,16 +418,18 @@
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
     "ap-southeast-4",
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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/type_defs.py` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -33,35 +33,35 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "RetentionArchiveTierTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateLifecyclePolicyResponseTypeDef",
     "CreateRuleTypeDef",
     "CrossRegionCopyRetainRuleTypeDef",
     "EncryptionConfigurationTypeDef",
     "CrossRegionCopyDeprecateRuleTypeDef",
     "DeleteLifecyclePolicyRequestRequestTypeDef",
     "DeprecateRuleTypeDef",
     "EventParametersTypeDef",
     "FastRestoreRuleTypeDef",
     "GetLifecyclePoliciesRequestRequestTypeDef",
     "LifecyclePolicySummaryTypeDef",
     "GetLifecyclePolicyRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagTypeDef",
+    "ResponseMetadataTypeDef",
     "RetainRuleTypeDef",
     "ShareRuleTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ArchiveRetainRuleTypeDef",
-    "CreateLifecyclePolicyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CrossRegionCopyActionTypeDef",
     "CrossRegionCopyRuleTypeDef",
     "EventSourceTypeDef",
     "GetLifecyclePoliciesResponseTypeDef",
     "ParametersTypeDef",
     "ArchiveRuleTypeDef",
     "ActionTypeDef",
@@ -79,22 +79,19 @@
         "Count": int,
         "Interval": int,
         "IntervalUnit": RetentionIntervalUnitValuesType,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateLifecyclePolicyResponseTypeDef = TypedDict(
+    "CreateLifecyclePolicyResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "PolicyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRuleTypeDef = TypedDict(
     "CreateRuleTypeDef",
     {
         "Location": LocationValuesType,
@@ -226,22 +223,41 @@
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 RetainRuleTypeDef = TypedDict(
     "RetainRuleTypeDef",
     {
         "Count": int,
         "Interval": int,
         "IntervalUnit": RetentionIntervalUnitValuesType,
     },
@@ -287,30 +303,14 @@
 ArchiveRetainRuleTypeDef = TypedDict(
     "ArchiveRetainRuleTypeDef",
     {
         "RetentionArchiveTier": RetentionArchiveTierTypeDef,
     },
 )
 
-CreateLifecyclePolicyResponseTypeDef = TypedDict(
-    "CreateLifecyclePolicyResponseTypeDef",
-    {
-        "PolicyId": str,
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
 _RequiredCrossRegionCopyActionTypeDef = TypedDict(
     "_RequiredCrossRegionCopyActionTypeDef",
     {
         "Target": str,
         "EncryptionConfiguration": EncryptionConfigurationTypeDef,
     },
 )
@@ -374,15 +374,15 @@
     pass
 
 
 GetLifecyclePoliciesResponseTypeDef = TypedDict(
     "GetLifecyclePoliciesResponseTypeDef",
     {
         "Policies": List[LifecyclePolicySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParametersTypeDef = TypedDict(
     "ParametersTypeDef",
     {
         "ExcludeBootVolume": bool,
@@ -507,10 +507,10 @@
     pass
 
 
 GetLifecyclePolicyResponseTypeDef = TypedDict(
     "GetLifecyclePolicyResponseTypeDef",
     {
         "Policy": LifecyclePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm/type_defs.pyi` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -32,35 +32,35 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "RetentionArchiveTierTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateLifecyclePolicyResponseTypeDef",
     "CreateRuleTypeDef",
     "CrossRegionCopyRetainRuleTypeDef",
     "EncryptionConfigurationTypeDef",
     "CrossRegionCopyDeprecateRuleTypeDef",
     "DeleteLifecyclePolicyRequestRequestTypeDef",
     "DeprecateRuleTypeDef",
     "EventParametersTypeDef",
     "FastRestoreRuleTypeDef",
     "GetLifecyclePoliciesRequestRequestTypeDef",
     "LifecyclePolicySummaryTypeDef",
     "GetLifecyclePolicyRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagTypeDef",
+    "ResponseMetadataTypeDef",
     "RetainRuleTypeDef",
     "ShareRuleTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "ArchiveRetainRuleTypeDef",
-    "CreateLifecyclePolicyResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CrossRegionCopyActionTypeDef",
     "CrossRegionCopyRuleTypeDef",
     "EventSourceTypeDef",
     "GetLifecyclePoliciesResponseTypeDef",
     "ParametersTypeDef",
     "ArchiveRuleTypeDef",
     "ActionTypeDef",
@@ -78,22 +78,19 @@
         "Count": int,
         "Interval": int,
         "IntervalUnit": RetentionIntervalUnitValuesType,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateLifecyclePolicyResponseTypeDef = TypedDict(
+    "CreateLifecyclePolicyResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "PolicyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRuleTypeDef = TypedDict(
     "CreateRuleTypeDef",
     {
         "Location": LocationValuesType,
@@ -221,22 +218,41 @@
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
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 RetainRuleTypeDef = TypedDict(
     "RetainRuleTypeDef",
     {
         "Count": int,
         "Interval": int,
         "IntervalUnit": RetentionIntervalUnitValuesType,
     },
@@ -280,30 +296,14 @@
 ArchiveRetainRuleTypeDef = TypedDict(
     "ArchiveRetainRuleTypeDef",
     {
         "RetentionArchiveTier": RetentionArchiveTierTypeDef,
     },
 )
 
-CreateLifecyclePolicyResponseTypeDef = TypedDict(
-    "CreateLifecyclePolicyResponseTypeDef",
-    {
-        "PolicyId": str,
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
 _RequiredCrossRegionCopyActionTypeDef = TypedDict(
     "_RequiredCrossRegionCopyActionTypeDef",
     {
         "Target": str,
         "EncryptionConfiguration": EncryptionConfigurationTypeDef,
     },
 )
@@ -361,15 +361,15 @@
 class EventSourceTypeDef(_RequiredEventSourceTypeDef, _OptionalEventSourceTypeDef):
     pass
 
 GetLifecyclePoliciesResponseTypeDef = TypedDict(
     "GetLifecyclePoliciesResponseTypeDef",
     {
         "Policies": List[LifecyclePolicySummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParametersTypeDef = TypedDict(
     "ParametersTypeDef",
     {
         "ExcludeBootVolume": bool,
@@ -490,10 +490,10 @@
 ):
     pass
 
 GetLifecyclePolicyResponseTypeDef = TypedDict(
     "GetLifecyclePolicyResponseTypeDef",
     {
         "Policy": LifecyclePolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/PKG-INFO` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dlm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DLM 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DLM 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dlm"></a>
 
 # types-aiobotocore-dlm
 
 [![PyPI - types-aiobotocore-dlm](https://img.shields.io/pypi/v/types-aiobotocore-dlm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dlm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dlm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dlm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dlm?color=blue)](https://pypistats.org/packages/types-aiobotocore-dlm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DLM 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM)
+[aiobotocore.DLM 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dlm.html#DLM)
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
 [types-aiobotocore-dlm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dlm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -298,35 +298,35 @@
 
 `types_aiobotocore_dlm.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dlm.type_defs import (
     RetentionArchiveTierTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLifecyclePolicyResponseTypeDef,
     CreateRuleTypeDef,
     CrossRegionCopyRetainRuleTypeDef,
     EncryptionConfigurationTypeDef,
     CrossRegionCopyDeprecateRuleTypeDef,
     DeleteLifecyclePolicyRequestRequestTypeDef,
     DeprecateRuleTypeDef,
     EventParametersTypeDef,
     FastRestoreRuleTypeDef,
     GetLifecyclePoliciesRequestRequestTypeDef,
     LifecyclePolicySummaryTypeDef,
     GetLifecyclePolicyRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagTypeDef,
+    ResponseMetadataTypeDef,
     RetainRuleTypeDef,
     ShareRuleTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     ArchiveRetainRuleTypeDef,
-    CreateLifecyclePolicyResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CrossRegionCopyActionTypeDef,
     CrossRegionCopyRuleTypeDef,
     EventSourceTypeDef,
     GetLifecyclePoliciesResponseTypeDef,
     ParametersTypeDef,
     ArchiveRuleTypeDef,
     ActionTypeDef,
@@ -346,43 +346,43 @@
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

### Comparing `types-aiobotocore-dlm-2.5.0.post1/types_aiobotocore_dlm.egg-info/SOURCES.txt` & `types-aiobotocore-dlm-2.5.1/types_aiobotocore_dlm.egg-info/SOURCES.txt`

 * *Files identical despite different names*

