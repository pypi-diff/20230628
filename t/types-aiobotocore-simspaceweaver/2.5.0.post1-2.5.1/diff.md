# Comparing `tmp/types-aiobotocore-simspaceweaver-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-simspaceweaver-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-simspaceweaver-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:21 2023, max compression
+gzip compressed data, was "types-aiobotocore-simspaceweaver-2.5.1.tar", last modified: Wed Jun 28 01:44:12 2023, max compression
```

## Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1.tar` & `types-aiobotocore-simspaceweaver-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.083634 types-aiobotocore-simspaceweaver-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13756 2023-03-11 12:27:21.083634 types-aiobotocore-simspaceweaver-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12157 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:21.083634 types-aiobotocore-simspaceweaver-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.083634 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/
--rw-r--r--   0 runner    (1001) docker     (123)      498 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      497 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12676 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    12653 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8398 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8396 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    10054 2023-03-11 12:24:17.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    10047 2023-03-11 12:24:17.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:16.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.083634 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13756 2023-03-11 12:27:20.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      853 2023-03-11 12:27:20.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:20.000000 types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.194217 types-aiobotocore-simspaceweaver-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13820 2023-06-28 01:44:12.194217 types-aiobotocore-simspaceweaver-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12227 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:12.194217 types-aiobotocore-simspaceweaver-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.190217 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/
+-rw-r--r--   0 runner    (1001) docker     (123)      498 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13279 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13255 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8664 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8662 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    10592 2023-06-28 01:41:05.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10585 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:04.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.190217 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13820 2023-06-28 01:44:12.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      853 2023-06-28 01:44:12.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:12.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:12.000000 types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/LICENSE` & `types-aiobotocore-simspaceweaver-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/PKG-INFO` & `types-aiobotocore-simspaceweaver-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-simspaceweaver
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SimSpaceWeaver 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SimSpaceWeaver 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-simspaceweaver"></a>
 
 # types-aiobotocore-simspaceweaver
 
 [![PyPI - types-aiobotocore-simspaceweaver](https://img.shields.io/pypi/v/types-aiobotocore-simspaceweaver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-simspaceweaver)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-simspaceweaver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-simspaceweaver)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-simspaceweaver?color=blue)](https://pypistats.org/packages/types-aiobotocore-simspaceweaver)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SimSpaceWeaver 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver)
+[aiobotocore.SimSpaceWeaver 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver)
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
 [types-aiobotocore-simspaceweaver docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,40 +297,42 @@
 
 `types_aiobotocore_simspaceweaver.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_simspaceweaver.type_defs import (
     CloudWatchLogsLogGroupTypeDef,
+    S3DestinationTypeDef,
     DeleteAppInputRequestTypeDef,
     DeleteSimulationInputRequestTypeDef,
     DescribeAppInputRequestTypeDef,
     LaunchOverridesTypeDef,
-    ResponseMetadataTypeDef,
     DescribeSimulationInputRequestTypeDef,
     S3LocationTypeDef,
     DomainTypeDef,
     ListAppsInputRequestTypeDef,
     SimulationAppMetadataTypeDef,
     ListSimulationsInputRequestTypeDef,
     SimulationMetadataTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     SimulationClockTypeDef,
+    ResponseMetadataTypeDef,
     SimulationAppPortMappingTypeDef,
+    StartAppOutputTypeDef,
     StartClockInputRequestTypeDef,
+    StartSimulationOutputTypeDef,
     StopAppInputRequestTypeDef,
     StopClockInputRequestTypeDef,
     StopSimulationInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     LogDestinationTypeDef,
+    CreateSnapshotInputRequestTypeDef,
     StartAppInputRequestTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    StartAppOutputTypeDef,
-    StartSimulationOutputTypeDef,
     StartSimulationInputRequestTypeDef,
     ListAppsOutputTypeDef,
     ListSimulationsOutputTypeDef,
     LiveSimulationStateTypeDef,
     SimulationAppEndpointInfoTypeDef,
     LoggingConfigurationTypeDef,
     DescribeAppOutputTypeDef,
@@ -345,43 +347,43 @@
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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/README.md` & `types-aiobotocore-simspaceweaver-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-simspaceweaver"></a>
 
 # types-aiobotocore-simspaceweaver
 
 [![PyPI - types-aiobotocore-simspaceweaver](https://img.shields.io/pypi/v/types-aiobotocore-simspaceweaver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-simspaceweaver)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-simspaceweaver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-simspaceweaver)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-simspaceweaver?color=blue)](https://pypistats.org/packages/types-aiobotocore-simspaceweaver)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SimSpaceWeaver 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver)
+[aiobotocore.SimSpaceWeaver 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver)
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
 [types-aiobotocore-simspaceweaver docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/).
 
 See how it helps to find and fix potential bugs:
 
@@ -264,40 +264,42 @@
 
 `types_aiobotocore_simspaceweaver.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_simspaceweaver.type_defs import (
     CloudWatchLogsLogGroupTypeDef,
+    S3DestinationTypeDef,
     DeleteAppInputRequestTypeDef,
     DeleteSimulationInputRequestTypeDef,
     DescribeAppInputRequestTypeDef,
     LaunchOverridesTypeDef,
-    ResponseMetadataTypeDef,
     DescribeSimulationInputRequestTypeDef,
     S3LocationTypeDef,
     DomainTypeDef,
     ListAppsInputRequestTypeDef,
     SimulationAppMetadataTypeDef,
     ListSimulationsInputRequestTypeDef,
     SimulationMetadataTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     SimulationClockTypeDef,
+    ResponseMetadataTypeDef,
     SimulationAppPortMappingTypeDef,
+    StartAppOutputTypeDef,
     StartClockInputRequestTypeDef,
+    StartSimulationOutputTypeDef,
     StopAppInputRequestTypeDef,
     StopClockInputRequestTypeDef,
     StopSimulationInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     LogDestinationTypeDef,
+    CreateSnapshotInputRequestTypeDef,
     StartAppInputRequestTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    StartAppOutputTypeDef,
-    StartSimulationOutputTypeDef,
     StartSimulationInputRequestTypeDef,
     ListAppsOutputTypeDef,
     ListSimulationsOutputTypeDef,
     LiveSimulationStateTypeDef,
     SimulationAppEndpointInfoTypeDef,
     LoggingConfigurationTypeDef,
     DescribeAppOutputTypeDef,
@@ -312,43 +314,43 @@
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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/setup.py` & `types-aiobotocore-simspaceweaver-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-simspaceweaver.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-simspaceweaver",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_simspaceweaver"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SimSpaceWeaver 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SimSpaceWeaver 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/"
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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/__main__.py` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SimSpaceWeaver 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SimSpaceWeaver 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver\nOther"
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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/client.py` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 from .type_defs import (
     DescribeAppOutputTypeDef,
     DescribeSimulationOutputTypeDef,
     LaunchOverridesTypeDef,
     ListAppsOutputTypeDef,
     ListSimulationsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
+    S3DestinationTypeDef,
     S3LocationTypeDef,
     StartAppOutputTypeDef,
     StartSimulationOutputTypeDef,
 )
 
 __all__ = ("SimSpaceWeaverClient",)
 
@@ -82,14 +83,24 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#close)
         """
 
+    async def create_snapshot(
+        self, *, Destination: S3DestinationTypeDef, Simulation: str
+    ) -> Dict[str, Any]:
+        """
+        Creates a snapshot of the specified simulation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.create_snapshot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#create_snapshot)
+        """
+
     async def delete_app(self, *, App: str, Domain: str, Simulation: str) -> Dict[str, Any]:
         """
         Deletes the instance of the given custom app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.delete_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#delete_app)
         """
@@ -189,22 +200,23 @@
         """
 
     async def start_simulation(
         self,
         *,
         Name: str,
         RoleArn: str,
-        SchemaS3Location: S3LocationTypeDef,
         ClientToken: str = ...,
         Description: str = ...,
         MaximumDuration: str = ...,
+        SchemaS3Location: S3LocationTypeDef = ...,
+        SnapshotS3Location: S3LocationTypeDef = ...,
         Tags: Mapping[str, str] = ...
     ) -> StartSimulationOutputTypeDef:
         """
-        Starts a simulation with the given name and schema.
+        Starts a simulation with the given name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.start_simulation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#start_simulation)
         """
 
     async def stop_app(self, *, App: str, Domain: str, Simulation: str) -> Dict[str, Any]:
         """
```

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/client.pyi` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 from .type_defs import (
     DescribeAppOutputTypeDef,
     DescribeSimulationOutputTypeDef,
     LaunchOverridesTypeDef,
     ListAppsOutputTypeDef,
     ListSimulationsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
+    S3DestinationTypeDef,
     S3LocationTypeDef,
     StartAppOutputTypeDef,
     StartSimulationOutputTypeDef,
 )
 
 __all__ = ("SimSpaceWeaverClient",)
 
@@ -76,14 +77,23 @@
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#close)
         """
+    async def create_snapshot(
+        self, *, Destination: S3DestinationTypeDef, Simulation: str
+    ) -> Dict[str, Any]:
+        """
+        Creates a snapshot of the specified simulation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.create_snapshot)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#create_snapshot)
+        """
     async def delete_app(self, *, App: str, Domain: str, Simulation: str) -> Dict[str, Any]:
         """
         Deletes the instance of the given custom app.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.delete_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#delete_app)
         """
@@ -173,22 +183,23 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#start_clock)
         """
     async def start_simulation(
         self,
         *,
         Name: str,
         RoleArn: str,
-        SchemaS3Location: S3LocationTypeDef,
         ClientToken: str = ...,
         Description: str = ...,
         MaximumDuration: str = ...,
+        SchemaS3Location: S3LocationTypeDef = ...,
+        SnapshotS3Location: S3LocationTypeDef = ...,
         Tags: Mapping[str, str] = ...
     ) -> StartSimulationOutputTypeDef:
         """
-        Starts a simulation with the given name and schema.
+        Starts a simulation with the given name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver.Client.start_simulation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/client/#start_simulation)
         """
     async def stop_app(self, *, App: str, Domain: str, Simulation: str) -> Dict[str, Any]:
         """
         Stops the given custom app and shuts down all of its allocated compute
```

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/literals.py` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,15 +38,23 @@
 ClockTargetStatusType = Literal["STARTED", "STOPPED", "UNKNOWN"]
 LifecycleManagementStrategyType = Literal[
     "ByRequest", "BySpatialSubdivision", "PerWorker", "Unknown"
 ]
 SimulationAppStatusType = Literal["ERROR", "STARTED", "STARTING", "STOPPED", "STOPPING", "UNKNOWN"]
 SimulationAppTargetStatusType = Literal["STARTED", "STOPPED", "UNKNOWN"]
 SimulationStatusType = Literal[
-    "DELETED", "DELETING", "FAILED", "STARTED", "STARTING", "STOPPED", "STOPPING", "UNKNOWN"
+    "DELETED",
+    "DELETING",
+    "FAILED",
+    "SNAPSHOT_IN_PROGRESS",
+    "STARTED",
+    "STARTING",
+    "STOPPED",
+    "STOPPING",
+    "UNKNOWN",
 ]
 SimulationTargetStatusType = Literal["DELETED", "STARTED", "STOPPED", "UNKNOWN"]
 SimSpaceWeaverServiceName = Literal["simspaceweaver"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -104,14 +112,15 @@
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
@@ -190,14 +199,15 @@
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
@@ -208,14 +218,15 @@
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
@@ -251,14 +262,15 @@
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
@@ -277,16 +289,19 @@
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
@@ -370,15 +385,17 @@
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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/literals.pyi` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -36,15 +36,23 @@
 ClockTargetStatusType = Literal["STARTED", "STOPPED", "UNKNOWN"]
 LifecycleManagementStrategyType = Literal[
     "ByRequest", "BySpatialSubdivision", "PerWorker", "Unknown"
 ]
 SimulationAppStatusType = Literal["ERROR", "STARTED", "STARTING", "STOPPED", "STOPPING", "UNKNOWN"]
 SimulationAppTargetStatusType = Literal["STARTED", "STOPPED", "UNKNOWN"]
 SimulationStatusType = Literal[
-    "DELETED", "DELETING", "FAILED", "STARTED", "STARTING", "STOPPED", "STOPPING", "UNKNOWN"
+    "DELETED",
+    "DELETING",
+    "FAILED",
+    "SNAPSHOT_IN_PROGRESS",
+    "STARTED",
+    "STARTING",
+    "STOPPED",
+    "STOPPING",
+    "UNKNOWN",
 ]
 SimulationTargetStatusType = Literal["DELETED", "STARTED", "STOPPED", "UNKNOWN"]
 SimSpaceWeaverServiceName = Literal["simspaceweaver"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -102,14 +110,15 @@
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
@@ -188,14 +197,15 @@
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
@@ -206,14 +216,15 @@
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
@@ -249,14 +260,15 @@
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
@@ -275,16 +287,19 @@
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
@@ -368,15 +383,17 @@
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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/type_defs.py` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -29,40 +29,42 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CloudWatchLogsLogGroupTypeDef",
+    "S3DestinationTypeDef",
     "DeleteAppInputRequestTypeDef",
     "DeleteSimulationInputRequestTypeDef",
     "DescribeAppInputRequestTypeDef",
     "LaunchOverridesTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeSimulationInputRequestTypeDef",
     "S3LocationTypeDef",
     "DomainTypeDef",
     "ListAppsInputRequestTypeDef",
     "SimulationAppMetadataTypeDef",
     "ListSimulationsInputRequestTypeDef",
     "SimulationMetadataTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "SimulationClockTypeDef",
+    "ResponseMetadataTypeDef",
     "SimulationAppPortMappingTypeDef",
+    "StartAppOutputTypeDef",
     "StartClockInputRequestTypeDef",
+    "StartSimulationOutputTypeDef",
     "StopAppInputRequestTypeDef",
     "StopClockInputRequestTypeDef",
     "StopSimulationInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "LogDestinationTypeDef",
+    "CreateSnapshotInputRequestTypeDef",
     "StartAppInputRequestTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "StartAppOutputTypeDef",
-    "StartSimulationOutputTypeDef",
     "StartSimulationInputRequestTypeDef",
     "ListAppsOutputTypeDef",
     "ListSimulationsOutputTypeDef",
     "LiveSimulationStateTypeDef",
     "SimulationAppEndpointInfoTypeDef",
     "LoggingConfigurationTypeDef",
     "DescribeAppOutputTypeDef",
@@ -73,14 +75,23 @@
     "CloudWatchLogsLogGroupTypeDef",
     {
         "LogGroupArn": str,
     },
     total=False,
 )
 
+S3DestinationTypeDef = TypedDict(
+    "S3DestinationTypeDef",
+    {
+        "BucketName": str,
+        "ObjectKeyPrefix": str,
+    },
+    total=False,
+)
+
 DeleteAppInputRequestTypeDef = TypedDict(
     "DeleteAppInputRequestTypeDef",
     {
         "App": str,
         "Domain": str,
         "Simulation": str,
     },
@@ -106,25 +117,14 @@
     "LaunchOverridesTypeDef",
     {
         "LaunchCommands": List[str],
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
 DescribeSimulationInputRequestTypeDef = TypedDict(
     "DescribeSimulationInputRequestTypeDef",
     {
         "Simulation": str,
     },
 )
 
@@ -205,39 +205,78 @@
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
 SimulationClockTypeDef = TypedDict(
     "SimulationClockTypeDef",
     {
         "Status": ClockStatusType,
         "TargetStatus": ClockTargetStatusType,
     },
     total=False,
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
 SimulationAppPortMappingTypeDef = TypedDict(
     "SimulationAppPortMappingTypeDef",
     {
         "Actual": int,
         "Declared": int,
     },
     total=False,
 )
 
+StartAppOutputTypeDef = TypedDict(
+    "StartAppOutputTypeDef",
+    {
+        "Domain": str,
+        "Name": str,
+        "Simulation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartClockInputRequestTypeDef = TypedDict(
     "StartClockInputRequestTypeDef",
     {
         "Simulation": str,
     },
 )
 
+StartSimulationOutputTypeDef = TypedDict(
+    "StartSimulationOutputTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "ExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopAppInputRequestTypeDef = TypedDict(
     "StopAppInputRequestTypeDef",
     {
         "App": str,
         "Domain": str,
         "Simulation": str,
     },
@@ -277,14 +316,22 @@
     "LogDestinationTypeDef",
     {
         "CloudWatchLogsLogGroup": CloudWatchLogsLogGroupTypeDef,
     },
     total=False,
 )
 
+CreateSnapshotInputRequestTypeDef = TypedDict(
+    "CreateSnapshotInputRequestTypeDef",
+    {
+        "Destination": S3DestinationTypeDef,
+        "Simulation": str,
+    },
+)
+
 _RequiredStartAppInputRequestTypeDef = TypedDict(
     "_RequiredStartAppInputRequestTypeDef",
     {
         "Domain": str,
         "Name": str,
         "Simulation": str,
     },
@@ -302,56 +349,29 @@
 
 class StartAppInputRequestTypeDef(
     _RequiredStartAppInputRequestTypeDef, _OptionalStartAppInputRequestTypeDef
 ):
     pass
 
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAppOutputTypeDef = TypedDict(
-    "StartAppOutputTypeDef",
-    {
-        "Domain": str,
-        "Name": str,
-        "Simulation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSimulationOutputTypeDef = TypedDict(
-    "StartSimulationOutputTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "ExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredStartSimulationInputRequestTypeDef = TypedDict(
     "_RequiredStartSimulationInputRequestTypeDef",
     {
         "Name": str,
         "RoleArn": str,
-        "SchemaS3Location": S3LocationTypeDef,
     },
 )
 _OptionalStartSimulationInputRequestTypeDef = TypedDict(
     "_OptionalStartSimulationInputRequestTypeDef",
     {
         "ClientToken": str,
         "Description": str,
         "MaximumDuration": str,
+        "SchemaS3Location": S3LocationTypeDef,
+        "SnapshotS3Location": S3LocationTypeDef,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class StartSimulationInputRequestTypeDef(
@@ -361,24 +381,24 @@
 
 
 ListAppsOutputTypeDef = TypedDict(
     "ListAppsOutputTypeDef",
     {
         "Apps": List[SimulationAppMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSimulationsOutputTypeDef = TypedDict(
     "ListSimulationsOutputTypeDef",
     {
         "NextToken": str,
         "Simulations": List[SimulationMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LiveSimulationStateTypeDef = TypedDict(
     "LiveSimulationStateTypeDef",
     {
         "Clocks": List[SimulationClockTypeDef],
@@ -411,15 +431,15 @@
         "Domain": str,
         "EndpointInfo": SimulationAppEndpointInfoTypeDef,
         "LaunchOverrides": LaunchOverridesTypeDef,
         "Name": str,
         "Simulation": str,
         "Status": SimulationAppStatusType,
         "TargetStatus": SimulationAppTargetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationOutputTypeDef = TypedDict(
     "DescribeSimulationOutputTypeDef",
     {
         "Arn": str,
@@ -429,12 +449,14 @@
         "LiveSimulationState": LiveSimulationStateTypeDef,
         "LoggingConfiguration": LoggingConfigurationTypeDef,
         "MaximumDuration": str,
         "Name": str,
         "RoleArn": str,
         "SchemaError": str,
         "SchemaS3Location": S3LocationTypeDef,
+        "SnapshotS3Location": S3LocationTypeDef,
+        "StartError": str,
         "Status": SimulationStatusType,
         "TargetStatus": SimulationTargetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver/type_defs.pyi` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -28,40 +28,42 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CloudWatchLogsLogGroupTypeDef",
+    "S3DestinationTypeDef",
     "DeleteAppInputRequestTypeDef",
     "DeleteSimulationInputRequestTypeDef",
     "DescribeAppInputRequestTypeDef",
     "LaunchOverridesTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeSimulationInputRequestTypeDef",
     "S3LocationTypeDef",
     "DomainTypeDef",
     "ListAppsInputRequestTypeDef",
     "SimulationAppMetadataTypeDef",
     "ListSimulationsInputRequestTypeDef",
     "SimulationMetadataTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "SimulationClockTypeDef",
+    "ResponseMetadataTypeDef",
     "SimulationAppPortMappingTypeDef",
+    "StartAppOutputTypeDef",
     "StartClockInputRequestTypeDef",
+    "StartSimulationOutputTypeDef",
     "StopAppInputRequestTypeDef",
     "StopClockInputRequestTypeDef",
     "StopSimulationInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "LogDestinationTypeDef",
+    "CreateSnapshotInputRequestTypeDef",
     "StartAppInputRequestTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "StartAppOutputTypeDef",
-    "StartSimulationOutputTypeDef",
     "StartSimulationInputRequestTypeDef",
     "ListAppsOutputTypeDef",
     "ListSimulationsOutputTypeDef",
     "LiveSimulationStateTypeDef",
     "SimulationAppEndpointInfoTypeDef",
     "LoggingConfigurationTypeDef",
     "DescribeAppOutputTypeDef",
@@ -72,14 +74,23 @@
     "CloudWatchLogsLogGroupTypeDef",
     {
         "LogGroupArn": str,
     },
     total=False,
 )
 
+S3DestinationTypeDef = TypedDict(
+    "S3DestinationTypeDef",
+    {
+        "BucketName": str,
+        "ObjectKeyPrefix": str,
+    },
+    total=False,
+)
+
 DeleteAppInputRequestTypeDef = TypedDict(
     "DeleteAppInputRequestTypeDef",
     {
         "App": str,
         "Domain": str,
         "Simulation": str,
     },
@@ -105,25 +116,14 @@
     "LaunchOverridesTypeDef",
     {
         "LaunchCommands": List[str],
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
 DescribeSimulationInputRequestTypeDef = TypedDict(
     "DescribeSimulationInputRequestTypeDef",
     {
         "Simulation": str,
     },
 )
 
@@ -202,39 +202,78 @@
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
 SimulationClockTypeDef = TypedDict(
     "SimulationClockTypeDef",
     {
         "Status": ClockStatusType,
         "TargetStatus": ClockTargetStatusType,
     },
     total=False,
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
 SimulationAppPortMappingTypeDef = TypedDict(
     "SimulationAppPortMappingTypeDef",
     {
         "Actual": int,
         "Declared": int,
     },
     total=False,
 )
 
+StartAppOutputTypeDef = TypedDict(
+    "StartAppOutputTypeDef",
+    {
+        "Domain": str,
+        "Name": str,
+        "Simulation": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartClockInputRequestTypeDef = TypedDict(
     "StartClockInputRequestTypeDef",
     {
         "Simulation": str,
     },
 )
 
+StartSimulationOutputTypeDef = TypedDict(
+    "StartSimulationOutputTypeDef",
+    {
+        "Arn": str,
+        "CreationTime": datetime,
+        "ExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopAppInputRequestTypeDef = TypedDict(
     "StopAppInputRequestTypeDef",
     {
         "App": str,
         "Domain": str,
         "Simulation": str,
     },
@@ -274,14 +313,22 @@
     "LogDestinationTypeDef",
     {
         "CloudWatchLogsLogGroup": CloudWatchLogsLogGroupTypeDef,
     },
     total=False,
 )
 
+CreateSnapshotInputRequestTypeDef = TypedDict(
+    "CreateSnapshotInputRequestTypeDef",
+    {
+        "Destination": S3DestinationTypeDef,
+        "Simulation": str,
+    },
+)
+
 _RequiredStartAppInputRequestTypeDef = TypedDict(
     "_RequiredStartAppInputRequestTypeDef",
     {
         "Domain": str,
         "Name": str,
         "Simulation": str,
     },
@@ -297,56 +344,29 @@
 )
 
 class StartAppInputRequestTypeDef(
     _RequiredStartAppInputRequestTypeDef, _OptionalStartAppInputRequestTypeDef
 ):
     pass
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAppOutputTypeDef = TypedDict(
-    "StartAppOutputTypeDef",
-    {
-        "Domain": str,
-        "Name": str,
-        "Simulation": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartSimulationOutputTypeDef = TypedDict(
-    "StartSimulationOutputTypeDef",
-    {
-        "Arn": str,
-        "CreationTime": datetime,
-        "ExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredStartSimulationInputRequestTypeDef = TypedDict(
     "_RequiredStartSimulationInputRequestTypeDef",
     {
         "Name": str,
         "RoleArn": str,
-        "SchemaS3Location": S3LocationTypeDef,
     },
 )
 _OptionalStartSimulationInputRequestTypeDef = TypedDict(
     "_OptionalStartSimulationInputRequestTypeDef",
     {
         "ClientToken": str,
         "Description": str,
         "MaximumDuration": str,
+        "SchemaS3Location": S3LocationTypeDef,
+        "SnapshotS3Location": S3LocationTypeDef,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
 class StartSimulationInputRequestTypeDef(
     _RequiredStartSimulationInputRequestTypeDef, _OptionalStartSimulationInputRequestTypeDef
@@ -354,24 +374,24 @@
     pass
 
 ListAppsOutputTypeDef = TypedDict(
     "ListAppsOutputTypeDef",
     {
         "Apps": List[SimulationAppMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSimulationsOutputTypeDef = TypedDict(
     "ListSimulationsOutputTypeDef",
     {
         "NextToken": str,
         "Simulations": List[SimulationMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LiveSimulationStateTypeDef = TypedDict(
     "LiveSimulationStateTypeDef",
     {
         "Clocks": List[SimulationClockTypeDef],
@@ -404,15 +424,15 @@
         "Domain": str,
         "EndpointInfo": SimulationAppEndpointInfoTypeDef,
         "LaunchOverrides": LaunchOverridesTypeDef,
         "Name": str,
         "Simulation": str,
         "Status": SimulationAppStatusType,
         "TargetStatus": SimulationAppTargetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSimulationOutputTypeDef = TypedDict(
     "DescribeSimulationOutputTypeDef",
     {
         "Arn": str,
@@ -422,12 +442,14 @@
         "LiveSimulationState": LiveSimulationStateTypeDef,
         "LoggingConfiguration": LoggingConfigurationTypeDef,
         "MaximumDuration": str,
         "Name": str,
         "RoleArn": str,
         "SchemaError": str,
         "SchemaS3Location": S3LocationTypeDef,
+        "SnapshotS3Location": S3LocationTypeDef,
+        "StartError": str,
         "Status": SimulationStatusType,
         "TargetStatus": SimulationTargetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/PKG-INFO` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-simspaceweaver
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SimSpaceWeaver 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SimSpaceWeaver 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-simspaceweaver"></a>
 
 # types-aiobotocore-simspaceweaver
 
 [![PyPI - types-aiobotocore-simspaceweaver](https://img.shields.io/pypi/v/types-aiobotocore-simspaceweaver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-simspaceweaver)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-simspaceweaver.svg?color=blue)](https://pypi.org/project/types-aiobotocore-simspaceweaver)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-simspaceweaver?color=blue)](https://pypistats.org/packages/types-aiobotocore-simspaceweaver)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SimSpaceWeaver 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver)
+[aiobotocore.SimSpaceWeaver 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/simspaceweaver.html#SimSpaceWeaver)
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
 [types-aiobotocore-simspaceweaver docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_simspaceweaver/).
 
 See how it helps to find and fix potential bugs:
 
@@ -297,40 +297,42 @@
 
 `types_aiobotocore_simspaceweaver.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_simspaceweaver.type_defs import (
     CloudWatchLogsLogGroupTypeDef,
+    S3DestinationTypeDef,
     DeleteAppInputRequestTypeDef,
     DeleteSimulationInputRequestTypeDef,
     DescribeAppInputRequestTypeDef,
     LaunchOverridesTypeDef,
-    ResponseMetadataTypeDef,
     DescribeSimulationInputRequestTypeDef,
     S3LocationTypeDef,
     DomainTypeDef,
     ListAppsInputRequestTypeDef,
     SimulationAppMetadataTypeDef,
     ListSimulationsInputRequestTypeDef,
     SimulationMetadataTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     SimulationClockTypeDef,
+    ResponseMetadataTypeDef,
     SimulationAppPortMappingTypeDef,
+    StartAppOutputTypeDef,
     StartClockInputRequestTypeDef,
+    StartSimulationOutputTypeDef,
     StopAppInputRequestTypeDef,
     StopClockInputRequestTypeDef,
     StopSimulationInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     LogDestinationTypeDef,
+    CreateSnapshotInputRequestTypeDef,
     StartAppInputRequestTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    StartAppOutputTypeDef,
-    StartSimulationOutputTypeDef,
     StartSimulationInputRequestTypeDef,
     ListAppsOutputTypeDef,
     ListSimulationsOutputTypeDef,
     LiveSimulationStateTypeDef,
     SimulationAppEndpointInfoTypeDef,
     LoggingConfigurationTypeDef,
     DescribeAppOutputTypeDef,
@@ -345,43 +347,43 @@
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

### Comparing `types-aiobotocore-simspaceweaver-2.5.0.post1/types_aiobotocore_simspaceweaver.egg-info/SOURCES.txt` & `types-aiobotocore-simspaceweaver-2.5.1/types_aiobotocore_simspaceweaver.egg-info/SOURCES.txt`

 * *Files identical despite different names*

