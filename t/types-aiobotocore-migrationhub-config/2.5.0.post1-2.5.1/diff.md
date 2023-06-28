# Comparing `tmp/types-aiobotocore-migrationhub-config-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-migrationhub-config-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-migrationhub-config-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-migrationhub-config-2.5.1.tar", last modified: Wed Jun 28 01:43:52 2023, max compression
```

## Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1.tar` & `types-aiobotocore-migrationhub-config-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.319443 types-aiobotocore-migrationhub-config-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12894 2023-03-11 12:27:01.319443 types-aiobotocore-migrationhub-config-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11276 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.319443 types-aiobotocore-migrationhub-config-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2199 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.311442 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/
--rw-r--r--   0 runner    (1001) docker     (123)      533 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      532 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6471 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6460 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7412 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7410 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     3246 2023-03-11 12:18:51.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     3241 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:50.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.319443 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12894 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.186179 types-aiobotocore-migrationhub-config-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12898 2023-06-28 01:43:52.186179 types-aiobotocore-migrationhub-config-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11286 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:52.186179 types-aiobotocore-migrationhub-config-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2193 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.182179 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/
+-rw-r--r--   0 runner    (1001) docker     (123)      533 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      532 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6471 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6460 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7621 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7619 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     3252 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3247 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:34.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:52.186179 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12898 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:52.000000 types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/LICENSE` & `types-aiobotocore-migrationhub-config-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/PKG-INFO` & `types-aiobotocore-migrationhub-config-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migrationhub-config
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubConfig 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubConfig 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migrationhub-config"></a>
 
 # types-aiobotocore-migrationhub-config
 
 [![PyPI - types-aiobotocore-migrationhub-config](https://img.shields.io/pypi/v/types-aiobotocore-migrationhub-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhub-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhub-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhub-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhub-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhub-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhub-config.html#MigrationHubConfig)
+[aiobotocore.MigrationHubConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhub-config.html#MigrationHubConfig)
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
 [types-aiobotocore-migrationhub-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,19 +290,19 @@
 
 `types_aiobotocore_migrationhub_config.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_migrationhub_config.type_defs import (
     TargetTypeDef,
+    GetHomeRegionResultTypeDef,
     ResponseMetadataTypeDef,
     CreateHomeRegionControlRequestRequestTypeDef,
     DescribeHomeRegionControlsRequestRequestTypeDef,
     HomeRegionControlTypeDef,
-    GetHomeRegionResultTypeDef,
     CreateHomeRegionControlResultTypeDef,
     DescribeHomeRegionControlsResultTypeDef,
 )
 
 
 def get_structure() -> TargetTypeDef:
     return {...}
@@ -311,43 +311,43 @@
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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/README.md` & `types-aiobotocore-migrationhub-config-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-migrationhub-config"></a>
 
 # types-aiobotocore-migrationhub-config
 
 [![PyPI - types-aiobotocore-migrationhub-config](https://img.shields.io/pypi/v/types-aiobotocore-migrationhub-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhub-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhub-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhub-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhub-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhub-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhub-config.html#MigrationHubConfig)
+[aiobotocore.MigrationHubConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhub-config.html#MigrationHubConfig)
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
 [types-aiobotocore-migrationhub-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -257,19 +257,19 @@
 
 `types_aiobotocore_migrationhub_config.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_migrationhub_config.type_defs import (
     TargetTypeDef,
+    GetHomeRegionResultTypeDef,
     ResponseMetadataTypeDef,
     CreateHomeRegionControlRequestRequestTypeDef,
     DescribeHomeRegionControlsRequestRequestTypeDef,
     HomeRegionControlTypeDef,
-    GetHomeRegionResultTypeDef,
     CreateHomeRegionControlResultTypeDef,
     DescribeHomeRegionControlsResultTypeDef,
 )
 
 
 def get_structure() -> TargetTypeDef:
     return {...}
@@ -278,43 +278,43 @@
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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/setup.py` & `types-aiobotocore-migrationhub-config-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-migrationhub-config.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-migrationhub-config",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_migrationhub_config"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MigrationHubConfig 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MigrationHubConfig 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/",
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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/__init__.py` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/__init__.pyi` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/__main__.py` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MigrationHubConfig 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MigrationHubConfig 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhub-config.html#MigrationHubConfig\nOther"
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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/client.py` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/client.pyi` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/literals.py` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -82,14 +82,15 @@
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
@@ -168,14 +169,15 @@
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
@@ -186,14 +188,15 @@
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
@@ -229,14 +232,15 @@
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
@@ -255,16 +259,19 @@
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
@@ -348,15 +355,17 @@
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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/literals.pyi` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -80,14 +80,15 @@
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
@@ -166,14 +167,15 @@
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
@@ -184,14 +186,15 @@
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
@@ -227,14 +230,15 @@
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
@@ -253,16 +257,19 @@
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
@@ -346,15 +353,17 @@
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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/type_defs.py` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -23,19 +23,19 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TargetTypeDef",
+    "GetHomeRegionResultTypeDef",
     "ResponseMetadataTypeDef",
     "CreateHomeRegionControlRequestRequestTypeDef",
     "DescribeHomeRegionControlsRequestRequestTypeDef",
     "HomeRegionControlTypeDef",
-    "GetHomeRegionResultTypeDef",
     "CreateHomeRegionControlResultTypeDef",
     "DescribeHomeRegionControlsResultTypeDef",
 )
 
 _RequiredTargetTypeDef = TypedDict(
     "_RequiredTargetTypeDef",
     {
@@ -51,14 +51,22 @@
 )
 
 
 class TargetTypeDef(_RequiredTargetTypeDef, _OptionalTargetTypeDef):
     pass
 
 
+GetHomeRegionResultTypeDef = TypedDict(
+    "GetHomeRegionResultTypeDef",
+    {
+        "HomeRegion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -108,31 +116,23 @@
         "HomeRegion": str,
         "Target": TargetTypeDef,
         "RequestedTime": datetime,
     },
     total=False,
 )
 
-GetHomeRegionResultTypeDef = TypedDict(
-    "GetHomeRegionResultTypeDef",
-    {
-        "HomeRegion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateHomeRegionControlResultTypeDef = TypedDict(
     "CreateHomeRegionControlResultTypeDef",
     {
         "HomeRegionControl": HomeRegionControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHomeRegionControlsResultTypeDef = TypedDict(
     "DescribeHomeRegionControlsResultTypeDef",
     {
         "HomeRegionControls": List[HomeRegionControlTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config/type_defs.pyi` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,19 +22,19 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TargetTypeDef",
+    "GetHomeRegionResultTypeDef",
     "ResponseMetadataTypeDef",
     "CreateHomeRegionControlRequestRequestTypeDef",
     "DescribeHomeRegionControlsRequestRequestTypeDef",
     "HomeRegionControlTypeDef",
-    "GetHomeRegionResultTypeDef",
     "CreateHomeRegionControlResultTypeDef",
     "DescribeHomeRegionControlsResultTypeDef",
 )
 
 _RequiredTargetTypeDef = TypedDict(
     "_RequiredTargetTypeDef",
     {
@@ -48,14 +48,22 @@
     },
     total=False,
 )
 
 class TargetTypeDef(_RequiredTargetTypeDef, _OptionalTargetTypeDef):
     pass
 
+GetHomeRegionResultTypeDef = TypedDict(
+    "GetHomeRegionResultTypeDef",
+    {
+        "HomeRegion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResponseMetadataTypeDef = TypedDict(
     "ResponseMetadataTypeDef",
     {
         "RequestId": str,
         "HostId": str,
         "HTTPStatusCode": int,
         "HTTPHeaders": Dict[str, str],
@@ -103,31 +111,23 @@
         "HomeRegion": str,
         "Target": TargetTypeDef,
         "RequestedTime": datetime,
     },
     total=False,
 )
 
-GetHomeRegionResultTypeDef = TypedDict(
-    "GetHomeRegionResultTypeDef",
-    {
-        "HomeRegion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateHomeRegionControlResultTypeDef = TypedDict(
     "CreateHomeRegionControlResultTypeDef",
     {
         "HomeRegionControl": HomeRegionControlTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeHomeRegionControlsResultTypeDef = TypedDict(
     "DescribeHomeRegionControlsResultTypeDef",
     {
         "HomeRegionControls": List[HomeRegionControlTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/PKG-INFO` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migrationhub-config
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubConfig 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubConfig 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migrationhub-config"></a>
 
 # types-aiobotocore-migrationhub-config
 
 [![PyPI - types-aiobotocore-migrationhub-config](https://img.shields.io/pypi/v/types-aiobotocore-migrationhub-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhub-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhub-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhub-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhub-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhub-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubConfig 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhub-config.html#MigrationHubConfig)
+[aiobotocore.MigrationHubConfig 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhub-config.html#MigrationHubConfig)
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
 [types-aiobotocore-migrationhub-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhub_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,19 +290,19 @@
 
 `types_aiobotocore_migrationhub_config.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_migrationhub_config.type_defs import (
     TargetTypeDef,
+    GetHomeRegionResultTypeDef,
     ResponseMetadataTypeDef,
     CreateHomeRegionControlRequestRequestTypeDef,
     DescribeHomeRegionControlsRequestRequestTypeDef,
     HomeRegionControlTypeDef,
-    GetHomeRegionResultTypeDef,
     CreateHomeRegionControlResultTypeDef,
     DescribeHomeRegionControlsResultTypeDef,
 )
 
 
 def get_structure() -> TargetTypeDef:
     return {...}
@@ -311,43 +311,43 @@
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

### Comparing `types-aiobotocore-migrationhub-config-2.5.0.post1/types_aiobotocore_migrationhub_config.egg-info/SOURCES.txt` & `types-aiobotocore-migrationhub-config-2.5.1/types_aiobotocore_migrationhub_config.egg-info/SOURCES.txt`

 * *Files identical despite different names*

