# Comparing `tmp/types-aiobotocore-mwaa-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-mwaa-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-mwaa-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-mwaa-2.5.1.tar", last modified: Wed Jun 28 01:43:54 2023, max compression
```

## Comparing `types-aiobotocore-mwaa-2.5.0.post1.tar` & `types-aiobotocore-mwaa-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.231461 types-aiobotocore-mwaa-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13964 2023-03-11 12:27:03.223461 types-aiobotocore-mwaa-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12405 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.231461 types-aiobotocore-mwaa-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.223461 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/
--rw-r--r--   0 runner    (1001) docker     (123)      635 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      634 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      920 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12114 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12093 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8811 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8809 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2080 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    11399 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    11392 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:00.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.223461 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13964 2023-03-11 12:27:03.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      756 2023-03-11 12:27:03.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-03-11 12:27:03.000000 types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.010182 types-aiobotocore-mwaa-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13953 2023-06-28 01:43:54.010182 types-aiobotocore-mwaa-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12400 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:54.010182 types-aiobotocore-mwaa-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2073 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.002183 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/
+-rw-r--r--   0 runner    (1001) docker     (123)      635 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      634 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12292 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12271 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9065 2023-06-28 01:35:44.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9063 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1962 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1959 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    11658 2023-06-28 01:35:44.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11651 2023-06-28 01:35:44.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:43.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:54.010182 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13953 2023-06-28 01:43:53.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      756 2023-06-28 01:43:53.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:53.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 01:43:53.000000 types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/LICENSE` & `types-aiobotocore-mwaa-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/PKG-INFO` & `types-aiobotocore-mwaa-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mwaa
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MWAA 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MWAA 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mwaa"></a>
 
 # types-aiobotocore-mwaa
 
 [![PyPI - types-aiobotocore-mwaa](https://img.shields.io/pypi/v/types-aiobotocore-mwaa.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mwaa)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mwaa.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mwaa)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mwaa?color=blue)](https://pypistats.org/packages/types-aiobotocore-mwaa)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MWAA 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
+[aiobotocore.MWAA 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
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
 [types-aiobotocore-mwaa docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,38 +320,38 @@
 
 `types_aiobotocore_mwaa.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mwaa.type_defs import (
     CreateCliTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCliTokenResponseTypeDef,
     NetworkConfigurationTypeDef,
+    CreateEnvironmentOutputTypeDef,
     CreateWebLoginTokenRequestRequestTypeDef,
+    CreateWebLoginTokenResponseTypeDef,
     DeleteEnvironmentInputRequestTypeDef,
     DimensionTypeDef,
     GetEnvironmentInputRequestTypeDef,
     UpdateErrorTypeDef,
-    PaginatorConfigTypeDef,
+    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     ListEnvironmentsInputRequestTypeDef,
+    ListEnvironmentsOutputTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ModuleLoggingConfigurationInputTypeDef,
     ModuleLoggingConfigurationTypeDef,
     StatisticSetTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateNetworkConfigurationInputTypeDef,
-    CreateCliTokenResponseTypeDef,
-    CreateEnvironmentOutputTypeDef,
-    CreateWebLoginTokenResponseTypeDef,
-    ListEnvironmentsOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
     LastUpdateTypeDef,
-    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     LoggingConfigurationInputTypeDef,
     LoggingConfigurationTypeDef,
     MetricDatumTypeDef,
     CreateEnvironmentInputRequestTypeDef,
     UpdateEnvironmentInputRequestTypeDef,
     EnvironmentTypeDef,
     PublishMetricsInputRequestTypeDef,
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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/README.md` & `types-aiobotocore-mwaa-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-mwaa"></a>
 
 # types-aiobotocore-mwaa
 
 [![PyPI - types-aiobotocore-mwaa](https://img.shields.io/pypi/v/types-aiobotocore-mwaa.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mwaa)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mwaa.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mwaa)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mwaa?color=blue)](https://pypistats.org/packages/types-aiobotocore-mwaa)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MWAA 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
+[aiobotocore.MWAA 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
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
 [types-aiobotocore-mwaa docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/).
 
 See how it helps to find and fix potential bugs:
 
@@ -287,38 +287,38 @@
 
 `types_aiobotocore_mwaa.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mwaa.type_defs import (
     CreateCliTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCliTokenResponseTypeDef,
     NetworkConfigurationTypeDef,
+    CreateEnvironmentOutputTypeDef,
     CreateWebLoginTokenRequestRequestTypeDef,
+    CreateWebLoginTokenResponseTypeDef,
     DeleteEnvironmentInputRequestTypeDef,
     DimensionTypeDef,
     GetEnvironmentInputRequestTypeDef,
     UpdateErrorTypeDef,
-    PaginatorConfigTypeDef,
+    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     ListEnvironmentsInputRequestTypeDef,
+    ListEnvironmentsOutputTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ModuleLoggingConfigurationInputTypeDef,
     ModuleLoggingConfigurationTypeDef,
     StatisticSetTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateNetworkConfigurationInputTypeDef,
-    CreateCliTokenResponseTypeDef,
-    CreateEnvironmentOutputTypeDef,
-    CreateWebLoginTokenResponseTypeDef,
-    ListEnvironmentsOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
     LastUpdateTypeDef,
-    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     LoggingConfigurationInputTypeDef,
     LoggingConfigurationTypeDef,
     MetricDatumTypeDef,
     CreateEnvironmentInputRequestTypeDef,
     UpdateEnvironmentInputRequestTypeDef,
     EnvironmentTypeDef,
     PublishMetricsInputRequestTypeDef,
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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/setup.py` & `types-aiobotocore-mwaa-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-mwaa.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-mwaa",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_mwaa"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MWAA 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.MWAA 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/",
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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/__init__.py` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/__init__.pyi` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/__main__.py` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MWAA 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MWAA 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa//\nBoto3 docs:   "
         "   https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA\nOther"
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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/client.py` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -118,14 +118,16 @@
         MaxWorkers: int = ...,
         MinWorkers: int = ...,
         PluginsS3ObjectVersion: str = ...,
         PluginsS3Path: str = ...,
         RequirementsS3ObjectVersion: str = ...,
         RequirementsS3Path: str = ...,
         Schedulers: int = ...,
+        StartupScriptS3ObjectVersion: str = ...,
+        StartupScriptS3Path: str = ...,
         Tags: Mapping[str, str] = ...,
         WebserverAccessMode: WebserverAccessModeType = ...,
         WeeklyMaintenanceWindowStart: str = ...
     ) -> CreateEnvironmentOutputTypeDef:
         """
         Creates an Amazon Managed Workflows for Apache Airflow (MWAA) environment.
 
@@ -233,14 +235,16 @@
         NetworkConfiguration: UpdateNetworkConfigurationInputTypeDef = ...,
         PluginsS3ObjectVersion: str = ...,
         PluginsS3Path: str = ...,
         RequirementsS3ObjectVersion: str = ...,
         RequirementsS3Path: str = ...,
         Schedulers: int = ...,
         SourceBucketArn: str = ...,
+        StartupScriptS3ObjectVersion: str = ...,
+        StartupScriptS3Path: str = ...,
         WebserverAccessMode: WebserverAccessModeType = ...,
         WeeklyMaintenanceWindowStart: str = ...
     ) -> UpdateEnvironmentOutputTypeDef:
         """
         Updates an Amazon Managed Workflows for Apache Airflow (MWAA) environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.update_environment)
```

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/client.pyi` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -110,14 +110,16 @@
         MaxWorkers: int = ...,
         MinWorkers: int = ...,
         PluginsS3ObjectVersion: str = ...,
         PluginsS3Path: str = ...,
         RequirementsS3ObjectVersion: str = ...,
         RequirementsS3Path: str = ...,
         Schedulers: int = ...,
+        StartupScriptS3ObjectVersion: str = ...,
+        StartupScriptS3Path: str = ...,
         Tags: Mapping[str, str] = ...,
         WebserverAccessMode: WebserverAccessModeType = ...,
         WeeklyMaintenanceWindowStart: str = ...
     ) -> CreateEnvironmentOutputTypeDef:
         """
         Creates an Amazon Managed Workflows for Apache Airflow (MWAA) environment.
 
@@ -215,14 +217,16 @@
         NetworkConfiguration: UpdateNetworkConfigurationInputTypeDef = ...,
         PluginsS3ObjectVersion: str = ...,
         PluginsS3Path: str = ...,
         RequirementsS3ObjectVersion: str = ...,
         RequirementsS3Path: str = ...,
         Schedulers: int = ...,
         SourceBucketArn: str = ...,
+        StartupScriptS3ObjectVersion: str = ...,
+        StartupScriptS3Path: str = ...,
         WebserverAccessMode: WebserverAccessModeType = ...,
         WeeklyMaintenanceWindowStart: str = ...
     ) -> UpdateEnvironmentOutputTypeDef:
         """
         Updates an Amazon Managed Workflows for Apache Airflow (MWAA) environment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Client.update_environment)
```

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/literals.py` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/literals.py`

 * *Files 9% similar despite different names*

```diff
@@ -34,16 +34,18 @@
 )
 
 
 EnvironmentStatusType = Literal[
     "AVAILABLE",
     "CREATE_FAILED",
     "CREATING",
+    "CREATING_SNAPSHOT",
     "DELETED",
     "DELETING",
+    "ROLLING_BACK",
     "UNAVAILABLE",
     "UPDATE_FAILED",
     "UPDATING",
 ]
 ListEnvironmentsPaginatorName = Literal["list_environments"]
 LoggingLevelType = Literal["CRITICAL", "DEBUG", "ERROR", "INFO", "WARNING"]
 UnitType = Literal[
@@ -136,14 +138,15 @@
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
@@ -222,14 +225,15 @@
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
@@ -240,14 +244,15 @@
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
@@ -283,14 +288,15 @@
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
@@ -309,16 +315,19 @@
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
@@ -402,15 +411,17 @@
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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/literals.pyi` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/literals.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -32,16 +32,18 @@
     "RegionName",
 )
 
 EnvironmentStatusType = Literal[
     "AVAILABLE",
     "CREATE_FAILED",
     "CREATING",
+    "CREATING_SNAPSHOT",
     "DELETED",
     "DELETING",
+    "ROLLING_BACK",
     "UNAVAILABLE",
     "UPDATE_FAILED",
     "UPDATING",
 ]
 ListEnvironmentsPaginatorName = Literal["list_environments"]
 LoggingLevelType = Literal["CRITICAL", "DEBUG", "ERROR", "INFO", "WARNING"]
 UnitType = Literal[
@@ -134,14 +136,15 @@
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
@@ -220,14 +223,15 @@
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
@@ -238,14 +242,15 @@
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
@@ -281,14 +286,15 @@
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
@@ -307,16 +313,19 @@
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
@@ -400,15 +409,17 @@
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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/paginator.py` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,28 +16,21 @@
     session = get_session()
     with session.create_client("mwaa") as client:
         client: MWAAClient
 
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListEnvironmentsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListEnvironmentsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -50,13 +43,13 @@
 class ListEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Paginator.ListEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/paginators/#listenvironmentspaginator)
         """
```

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/paginator.pyi` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -16,27 +16,21 @@
     session = get_session()
     with session.create_client("mwaa") as client:
         client: MWAAClient
 
         list_environments_paginator: ListEnvironmentsPaginator = client.get_paginator("list_environments")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import ListEnvironmentsOutputTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListEnvironmentsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -46,13 +40,13 @@
 class ListEnvironmentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Paginator.ListEnvironments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/paginators/#listenvironmentspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnvironmentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA.Paginator.ListEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/paginators/#listenvironmentspaginator)
         """
```

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/type_defs.py` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -27,38 +27,38 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CreateCliTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateCliTokenResponseTypeDef",
     "NetworkConfigurationTypeDef",
+    "CreateEnvironmentOutputTypeDef",
     "CreateWebLoginTokenRequestRequestTypeDef",
+    "CreateWebLoginTokenResponseTypeDef",
     "DeleteEnvironmentInputRequestTypeDef",
     "DimensionTypeDef",
     "GetEnvironmentInputRequestTypeDef",
     "UpdateErrorTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsInputRequestTypeDef",
+    "ListEnvironmentsOutputTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "ModuleLoggingConfigurationInputTypeDef",
     "ModuleLoggingConfigurationTypeDef",
     "StatisticSetTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateNetworkConfigurationInputTypeDef",
-    "CreateCliTokenResponseTypeDef",
-    "CreateEnvironmentOutputTypeDef",
-    "CreateWebLoginTokenResponseTypeDef",
-    "ListEnvironmentsOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
     "UpdateEnvironmentOutputTypeDef",
     "LastUpdateTypeDef",
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     "LoggingConfigurationInputTypeDef",
     "LoggingConfigurationTypeDef",
     "MetricDatumTypeDef",
     "CreateEnvironmentInputRequestTypeDef",
     "UpdateEnvironmentInputRequestTypeDef",
     "EnvironmentTypeDef",
     "PublishMetricsInputRequestTypeDef",
@@ -68,41 +68,56 @@
 CreateCliTokenRequestRequestTypeDef = TypedDict(
     "CreateCliTokenRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateCliTokenResponseTypeDef = TypedDict(
+    "CreateCliTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "CliToken": str,
+        "WebServerHostname": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkConfigurationTypeDef = TypedDict(
     "NetworkConfigurationTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
         "SubnetIds": Sequence[str],
     },
     total=False,
 )
 
+CreateEnvironmentOutputTypeDef = TypedDict(
+    "CreateEnvironmentOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateWebLoginTokenRequestRequestTypeDef = TypedDict(
     "CreateWebLoginTokenRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+CreateWebLoginTokenResponseTypeDef = TypedDict(
+    "CreateWebLoginTokenResponseTypeDef",
+    {
+        "WebServerHostname": str,
+        "WebToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEnvironmentInputRequestTypeDef = TypedDict(
     "DeleteEnvironmentInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -126,40 +141,55 @@
     {
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEnvironmentsInputRequestTypeDef = TypedDict(
     "ListEnvironmentsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListEnvironmentsOutputTypeDef = TypedDict(
+    "ListEnvironmentsOutputTypeDef",
+    {
+        "Environments": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ModuleLoggingConfigurationInputTypeDef = TypedDict(
     "ModuleLoggingConfigurationInputTypeDef",
     {
         "Enabled": bool,
         "LogLevel": LoggingLevelType,
     },
 )
@@ -181,14 +211,35 @@
         "Minimum": float,
         "SampleCount": int,
         "Sum": float,
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
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -204,84 +255,33 @@
 UpdateNetworkConfigurationInputTypeDef = TypedDict(
     "UpdateNetworkConfigurationInputTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
     },
 )
 
-CreateCliTokenResponseTypeDef = TypedDict(
-    "CreateCliTokenResponseTypeDef",
-    {
-        "CliToken": str,
-        "WebServerHostname": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEnvironmentOutputTypeDef = TypedDict(
-    "CreateEnvironmentOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWebLoginTokenResponseTypeDef = TypedDict(
-    "CreateWebLoginTokenResponseTypeDef",
-    {
-        "WebServerHostname": str,
-        "WebToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListEnvironmentsOutputTypeDef = TypedDict(
-    "ListEnvironmentsOutputTypeDef",
-    {
-        "Environments": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateEnvironmentOutputTypeDef = TypedDict(
     "UpdateEnvironmentOutputTypeDef",
     {
         "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LastUpdateTypeDef = TypedDict(
     "LastUpdateTypeDef",
     {
         "CreatedAt": datetime,
         "Error": UpdateErrorTypeDef,
         "Source": str,
         "Status": UpdateStatusType,
     },
     total=False,
 )
 
-ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 LoggingConfigurationInputTypeDef = TypedDict(
     "LoggingConfigurationInputTypeDef",
     {
         "DagProcessingLogs": ModuleLoggingConfigurationInputTypeDef,
         "SchedulerLogs": ModuleLoggingConfigurationInputTypeDef,
         "TaskLogs": ModuleLoggingConfigurationInputTypeDef,
         "WebserverLogs": ModuleLoggingConfigurationInputTypeDef,
@@ -346,14 +346,16 @@
         "MaxWorkers": int,
         "MinWorkers": int,
         "PluginsS3ObjectVersion": str,
         "PluginsS3Path": str,
         "RequirementsS3ObjectVersion": str,
         "RequirementsS3Path": str,
         "Schedulers": int,
+        "StartupScriptS3ObjectVersion": str,
+        "StartupScriptS3Path": str,
         "Tags": Mapping[str, str],
         "WebserverAccessMode": WebserverAccessModeType,
         "WeeklyMaintenanceWindowStart": str,
     },
     total=False,
 )
 
@@ -384,14 +386,16 @@
         "NetworkConfiguration": UpdateNetworkConfigurationInputTypeDef,
         "PluginsS3ObjectVersion": str,
         "PluginsS3Path": str,
         "RequirementsS3ObjectVersion": str,
         "RequirementsS3Path": str,
         "Schedulers": int,
         "SourceBucketArn": str,
+        "StartupScriptS3ObjectVersion": str,
+        "StartupScriptS3Path": str,
         "WebserverAccessMode": WebserverAccessModeType,
         "WeeklyMaintenanceWindowStart": str,
     },
     total=False,
 )
 
 
@@ -421,14 +425,16 @@
         "PluginsS3ObjectVersion": str,
         "PluginsS3Path": str,
         "RequirementsS3ObjectVersion": str,
         "RequirementsS3Path": str,
         "Schedulers": int,
         "ServiceRoleArn": str,
         "SourceBucketArn": str,
+        "StartupScriptS3ObjectVersion": str,
+        "StartupScriptS3Path": str,
         "Status": EnvironmentStatusType,
         "Tags": Dict[str, str],
         "WebserverAccessMode": WebserverAccessModeType,
         "WebserverUrl": str,
         "WeeklyMaintenanceWindowStart": str,
     },
     total=False,
@@ -442,10 +448,10 @@
     },
 )
 
 GetEnvironmentOutputTypeDef = TypedDict(
     "GetEnvironmentOutputTypeDef",
     {
         "Environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa/type_defs.pyi` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -26,38 +26,38 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CreateCliTokenRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateCliTokenResponseTypeDef",
     "NetworkConfigurationTypeDef",
+    "CreateEnvironmentOutputTypeDef",
     "CreateWebLoginTokenRequestRequestTypeDef",
+    "CreateWebLoginTokenResponseTypeDef",
     "DeleteEnvironmentInputRequestTypeDef",
     "DimensionTypeDef",
     "GetEnvironmentInputRequestTypeDef",
     "UpdateErrorTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     "ListEnvironmentsInputRequestTypeDef",
+    "ListEnvironmentsOutputTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "ModuleLoggingConfigurationInputTypeDef",
     "ModuleLoggingConfigurationTypeDef",
     "StatisticSetTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateNetworkConfigurationInputTypeDef",
-    "CreateCliTokenResponseTypeDef",
-    "CreateEnvironmentOutputTypeDef",
-    "CreateWebLoginTokenResponseTypeDef",
-    "ListEnvironmentsOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
     "UpdateEnvironmentOutputTypeDef",
     "LastUpdateTypeDef",
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     "LoggingConfigurationInputTypeDef",
     "LoggingConfigurationTypeDef",
     "MetricDatumTypeDef",
     "CreateEnvironmentInputRequestTypeDef",
     "UpdateEnvironmentInputRequestTypeDef",
     "EnvironmentTypeDef",
     "PublishMetricsInputRequestTypeDef",
@@ -67,41 +67,56 @@
 CreateCliTokenRequestRequestTypeDef = TypedDict(
     "CreateCliTokenRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateCliTokenResponseTypeDef = TypedDict(
+    "CreateCliTokenResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "CliToken": str,
+        "WebServerHostname": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkConfigurationTypeDef = TypedDict(
     "NetworkConfigurationTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
         "SubnetIds": Sequence[str],
     },
     total=False,
 )
 
+CreateEnvironmentOutputTypeDef = TypedDict(
+    "CreateEnvironmentOutputTypeDef",
+    {
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateWebLoginTokenRequestRequestTypeDef = TypedDict(
     "CreateWebLoginTokenRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+CreateWebLoginTokenResponseTypeDef = TypedDict(
+    "CreateWebLoginTokenResponseTypeDef",
+    {
+        "WebServerHostname": str,
+        "WebToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEnvironmentInputRequestTypeDef = TypedDict(
     "DeleteEnvironmentInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -125,40 +140,55 @@
     {
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
+    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEnvironmentsInputRequestTypeDef = TypedDict(
     "ListEnvironmentsInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListEnvironmentsOutputTypeDef = TypedDict(
+    "ListEnvironmentsOutputTypeDef",
+    {
+        "Environments": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ModuleLoggingConfigurationInputTypeDef = TypedDict(
     "ModuleLoggingConfigurationInputTypeDef",
     {
         "Enabled": bool,
         "LogLevel": LoggingLevelType,
     },
 )
@@ -180,14 +210,35 @@
         "Minimum": float,
         "SampleCount": int,
         "Sum": float,
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
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -203,84 +254,33 @@
 UpdateNetworkConfigurationInputTypeDef = TypedDict(
     "UpdateNetworkConfigurationInputTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
     },
 )
 
-CreateCliTokenResponseTypeDef = TypedDict(
-    "CreateCliTokenResponseTypeDef",
-    {
-        "CliToken": str,
-        "WebServerHostname": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEnvironmentOutputTypeDef = TypedDict(
-    "CreateEnvironmentOutputTypeDef",
-    {
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWebLoginTokenResponseTypeDef = TypedDict(
-    "CreateWebLoginTokenResponseTypeDef",
-    {
-        "WebServerHostname": str,
-        "WebToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListEnvironmentsOutputTypeDef = TypedDict(
-    "ListEnvironmentsOutputTypeDef",
-    {
-        "Environments": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateEnvironmentOutputTypeDef = TypedDict(
     "UpdateEnvironmentOutputTypeDef",
     {
         "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LastUpdateTypeDef = TypedDict(
     "LastUpdateTypeDef",
     {
         "CreatedAt": datetime,
         "Error": UpdateErrorTypeDef,
         "Source": str,
         "Status": UpdateStatusType,
     },
     total=False,
 )
 
-ListEnvironmentsInputListEnvironmentsPaginateTypeDef = TypedDict(
-    "ListEnvironmentsInputListEnvironmentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 LoggingConfigurationInputTypeDef = TypedDict(
     "LoggingConfigurationInputTypeDef",
     {
         "DagProcessingLogs": ModuleLoggingConfigurationInputTypeDef,
         "SchedulerLogs": ModuleLoggingConfigurationInputTypeDef,
         "TaskLogs": ModuleLoggingConfigurationInputTypeDef,
         "WebserverLogs": ModuleLoggingConfigurationInputTypeDef,
@@ -343,14 +343,16 @@
         "MaxWorkers": int,
         "MinWorkers": int,
         "PluginsS3ObjectVersion": str,
         "PluginsS3Path": str,
         "RequirementsS3ObjectVersion": str,
         "RequirementsS3Path": str,
         "Schedulers": int,
+        "StartupScriptS3ObjectVersion": str,
+        "StartupScriptS3Path": str,
         "Tags": Mapping[str, str],
         "WebserverAccessMode": WebserverAccessModeType,
         "WeeklyMaintenanceWindowStart": str,
     },
     total=False,
 )
 
@@ -379,14 +381,16 @@
         "NetworkConfiguration": UpdateNetworkConfigurationInputTypeDef,
         "PluginsS3ObjectVersion": str,
         "PluginsS3Path": str,
         "RequirementsS3ObjectVersion": str,
         "RequirementsS3Path": str,
         "Schedulers": int,
         "SourceBucketArn": str,
+        "StartupScriptS3ObjectVersion": str,
+        "StartupScriptS3Path": str,
         "WebserverAccessMode": WebserverAccessModeType,
         "WeeklyMaintenanceWindowStart": str,
     },
     total=False,
 )
 
 class UpdateEnvironmentInputRequestTypeDef(
@@ -414,14 +418,16 @@
         "PluginsS3ObjectVersion": str,
         "PluginsS3Path": str,
         "RequirementsS3ObjectVersion": str,
         "RequirementsS3Path": str,
         "Schedulers": int,
         "ServiceRoleArn": str,
         "SourceBucketArn": str,
+        "StartupScriptS3ObjectVersion": str,
+        "StartupScriptS3Path": str,
         "Status": EnvironmentStatusType,
         "Tags": Dict[str, str],
         "WebserverAccessMode": WebserverAccessModeType,
         "WebserverUrl": str,
         "WeeklyMaintenanceWindowStart": str,
     },
     total=False,
@@ -435,10 +441,10 @@
     },
 )
 
 GetEnvironmentOutputTypeDef = TypedDict(
     "GetEnvironmentOutputTypeDef",
     {
         "Environment": EnvironmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/PKG-INFO` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-mwaa
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MWAA 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MWAA 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-mwaa"></a>
 
 # types-aiobotocore-mwaa
 
 [![PyPI - types-aiobotocore-mwaa](https://img.shields.io/pypi/v/types-aiobotocore-mwaa.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mwaa)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-mwaa.svg?color=blue)](https://pypi.org/project/types-aiobotocore-mwaa)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-mwaa?color=blue)](https://pypistats.org/packages/types-aiobotocore-mwaa)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MWAA 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
+[aiobotocore.MWAA 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/mwaa.html#MWAA)
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
 [types-aiobotocore-mwaa docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mwaa/).
 
 See how it helps to find and fix potential bugs:
 
@@ -320,38 +320,38 @@
 
 `types_aiobotocore_mwaa.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_mwaa.type_defs import (
     CreateCliTokenRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCliTokenResponseTypeDef,
     NetworkConfigurationTypeDef,
+    CreateEnvironmentOutputTypeDef,
     CreateWebLoginTokenRequestRequestTypeDef,
+    CreateWebLoginTokenResponseTypeDef,
     DeleteEnvironmentInputRequestTypeDef,
     DimensionTypeDef,
     GetEnvironmentInputRequestTypeDef,
     UpdateErrorTypeDef,
-    PaginatorConfigTypeDef,
+    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     ListEnvironmentsInputRequestTypeDef,
+    ListEnvironmentsOutputTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ModuleLoggingConfigurationInputTypeDef,
     ModuleLoggingConfigurationTypeDef,
     StatisticSetTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateNetworkConfigurationInputTypeDef,
-    CreateCliTokenResponseTypeDef,
-    CreateEnvironmentOutputTypeDef,
-    CreateWebLoginTokenResponseTypeDef,
-    ListEnvironmentsOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
     UpdateEnvironmentOutputTypeDef,
     LastUpdateTypeDef,
-    ListEnvironmentsInputListEnvironmentsPaginateTypeDef,
     LoggingConfigurationInputTypeDef,
     LoggingConfigurationTypeDef,
     MetricDatumTypeDef,
     CreateEnvironmentInputRequestTypeDef,
     UpdateEnvironmentInputRequestTypeDef,
     EnvironmentTypeDef,
     PublishMetricsInputRequestTypeDef,
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

### Comparing `types-aiobotocore-mwaa-2.5.0.post1/types_aiobotocore_mwaa.egg-info/SOURCES.txt` & `types-aiobotocore-mwaa-2.5.1/types_aiobotocore_mwaa.egg-info/SOURCES.txt`

 * *Files identical despite different names*

