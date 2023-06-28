# Comparing `tmp/types-aiobotocore-appintegrations-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-appintegrations-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-appintegrations-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:10 2023, max compression
+gzip compressed data, was "types-aiobotocore-appintegrations-2.5.1.tar", last modified: Wed Jun 28 01:43:04 2023, max compression
```

## Comparing `types-aiobotocore-appintegrations-2.5.0.post1.tar` & `types-aiobotocore-appintegrations-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.394924 types-aiobotocore-appintegrations-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13839 2023-03-11 12:26:10.390924 types-aiobotocore-appintegrations-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12229 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:10.394924 types-aiobotocore-appintegrations-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.382924 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/
--rw-r--r--   0 runner    (1001) docker     (123)      541 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      540 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      989 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13946 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13923 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7631 2023-03-11 12:09:35.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7629 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    11391 2023-03-11 12:09:35.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    11378 2023-03-11 12:09:35.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:34.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:10.390924 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13839 2023-03-11 12:26:10.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:10.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:10.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:10.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:26:10.000000 types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.286090 types-aiobotocore-appintegrations-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13865 2023-06-28 01:43:04.286090 types-aiobotocore-appintegrations-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12261 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:04.286090 types-aiobotocore-appintegrations-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.286090 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/
+-rw-r--r--   0 runner    (1001) docker     (123)      541 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      540 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      977 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14095 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14072 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7840 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7838 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    12487 2023-06-28 01:26:12.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12470 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:11.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:04.286090 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13865 2023-06-28 01:43:04.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:04.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:04.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:04.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:43:04.000000 types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/LICENSE` & `types-aiobotocore-appintegrations-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/PKG-INFO` & `types-aiobotocore-appintegrations-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appintegrations
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppIntegrationsService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppIntegrationsService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appintegrations"></a>
 
 # types-aiobotocore-appintegrations
 
 [![PyPI - types-aiobotocore-appintegrations](https://img.shields.io/pypi/v/types-aiobotocore-appintegrations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appintegrations)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appintegrations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appintegrations)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appintegrations?color=blue)](https://pypistats.org/packages/types-aiobotocore-appintegrations)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppIntegrationsService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService)
+[aiobotocore.AppIntegrationsService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService)
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
 [types-aiobotocore-appintegrations docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,88 +289,89 @@
 ### Typed dictionaries
 
 `types_aiobotocore_appintegrations.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_appintegrations.type_defs import (
+    FileConfigurationTypeDef,
     ScheduleConfigurationTypeDef,
-    ResponseMetadataTypeDef,
     EventFilterTypeDef,
+    CreateEventIntegrationResponseTypeDef,
     DataIntegrationAssociationSummaryTypeDef,
     DataIntegrationSummaryTypeDef,
     DeleteDataIntegrationRequestRequestTypeDef,
     DeleteEventIntegrationRequestRequestTypeDef,
     EventIntegrationAssociationTypeDef,
     GetDataIntegrationRequestRequestTypeDef,
     GetEventIntegrationRequestRequestTypeDef,
     ListDataIntegrationAssociationsRequestRequestTypeDef,
     ListDataIntegrationsRequestRequestTypeDef,
     ListEventIntegrationAssociationsRequestRequestTypeDef,
     ListEventIntegrationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDataIntegrationRequestRequestTypeDef,
     UpdateEventIntegrationRequestRequestTypeDef,
     CreateDataIntegrationRequestRequestTypeDef,
     CreateDataIntegrationResponseTypeDef,
-    CreateEventIntegrationResponseTypeDef,
     GetDataIntegrationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateEventIntegrationRequestRequestTypeDef,
     EventIntegrationTypeDef,
     GetEventIntegrationResponseTypeDef,
     ListDataIntegrationAssociationsResponseTypeDef,
     ListDataIntegrationsResponseTypeDef,
     ListEventIntegrationAssociationsResponseTypeDef,
     ListEventIntegrationsResponseTypeDef,
 )
 
 
-def get_structure() -> ScheduleConfigurationTypeDef:
+def get_structure() -> FileConfigurationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/README.md` & `types-aiobotocore-appintegrations-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-appintegrations"></a>
 
 # types-aiobotocore-appintegrations
 
 [![PyPI - types-aiobotocore-appintegrations](https://img.shields.io/pypi/v/types-aiobotocore-appintegrations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appintegrations)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appintegrations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appintegrations)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appintegrations?color=blue)](https://pypistats.org/packages/types-aiobotocore-appintegrations)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppIntegrationsService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService)
+[aiobotocore.AppIntegrationsService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService)
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
 [types-aiobotocore-appintegrations docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/).
 
 See how it helps to find and fix potential bugs:
 
@@ -256,88 +256,89 @@
 ### Typed dictionaries
 
 `types_aiobotocore_appintegrations.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_appintegrations.type_defs import (
+    FileConfigurationTypeDef,
     ScheduleConfigurationTypeDef,
-    ResponseMetadataTypeDef,
     EventFilterTypeDef,
+    CreateEventIntegrationResponseTypeDef,
     DataIntegrationAssociationSummaryTypeDef,
     DataIntegrationSummaryTypeDef,
     DeleteDataIntegrationRequestRequestTypeDef,
     DeleteEventIntegrationRequestRequestTypeDef,
     EventIntegrationAssociationTypeDef,
     GetDataIntegrationRequestRequestTypeDef,
     GetEventIntegrationRequestRequestTypeDef,
     ListDataIntegrationAssociationsRequestRequestTypeDef,
     ListDataIntegrationsRequestRequestTypeDef,
     ListEventIntegrationAssociationsRequestRequestTypeDef,
     ListEventIntegrationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDataIntegrationRequestRequestTypeDef,
     UpdateEventIntegrationRequestRequestTypeDef,
     CreateDataIntegrationRequestRequestTypeDef,
     CreateDataIntegrationResponseTypeDef,
-    CreateEventIntegrationResponseTypeDef,
     GetDataIntegrationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateEventIntegrationRequestRequestTypeDef,
     EventIntegrationTypeDef,
     GetEventIntegrationResponseTypeDef,
     ListDataIntegrationAssociationsResponseTypeDef,
     ListDataIntegrationsResponseTypeDef,
     ListEventIntegrationAssociationsResponseTypeDef,
     ListEventIntegrationsResponseTypeDef,
 )
 
 
-def get_structure() -> ScheduleConfigurationTypeDef:
+def get_structure() -> FileConfigurationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/setup.py` & `types-aiobotocore-appintegrations-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-appintegrations.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-appintegrations",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_appintegrations"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AppIntegrationsService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AppIntegrationsService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/"
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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/__init__.py` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/__init__.pyi` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/__main__.py` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/__main__.py`

 * *Files 26% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AppIntegrationsService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AppIntegrationsService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService\nOther"
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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/client.py` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,14 +19,15 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .type_defs import (
     CreateDataIntegrationResponseTypeDef,
     CreateEventIntegrationResponseTypeDef,
     EventFilterTypeDef,
+    FileConfigurationTypeDef,
     GetDataIntegrationResponseTypeDef,
     GetEventIntegrationResponseTypeDef,
     ListDataIntegrationAssociationsResponseTypeDef,
     ListDataIntegrationsResponseTypeDef,
     ListEventIntegrationAssociationsResponseTypeDef,
     ListEventIntegrationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -88,20 +89,22 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/client/#close)
         """
 
     async def create_data_integration(
         self,
         *,
         Name: str,
+        KmsKey: str,
+        SourceURI: str,
+        ScheduleConfig: ScheduleConfigurationTypeDef,
         Description: str = ...,
-        KmsKey: str = ...,
-        SourceURI: str = ...,
-        ScheduleConfig: ScheduleConfigurationTypeDef = ...,
         Tags: Mapping[str, str] = ...,
-        ClientToken: str = ...
+        ClientToken: str = ...,
+        FileConfiguration: FileConfigurationTypeDef = ...,
+        ObjectConfiguration: Mapping[str, Mapping[str, Sequence[str]]] = ...
     ) -> CreateDataIntegrationResponseTypeDef:
         """
         Creates and persists a DataIntegration resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService.Client.create_data_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/client/#create_data_integration)
         """
```

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/client.pyi` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -19,14 +19,15 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .type_defs import (
     CreateDataIntegrationResponseTypeDef,
     CreateEventIntegrationResponseTypeDef,
     EventFilterTypeDef,
+    FileConfigurationTypeDef,
     GetDataIntegrationResponseTypeDef,
     GetEventIntegrationResponseTypeDef,
     ListDataIntegrationAssociationsResponseTypeDef,
     ListDataIntegrationsResponseTypeDef,
     ListEventIntegrationAssociationsResponseTypeDef,
     ListEventIntegrationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -82,20 +83,22 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/client/#close)
         """
     async def create_data_integration(
         self,
         *,
         Name: str,
+        KmsKey: str,
+        SourceURI: str,
+        ScheduleConfig: ScheduleConfigurationTypeDef,
         Description: str = ...,
-        KmsKey: str = ...,
-        SourceURI: str = ...,
-        ScheduleConfig: ScheduleConfigurationTypeDef = ...,
         Tags: Mapping[str, str] = ...,
-        ClientToken: str = ...
+        ClientToken: str = ...,
+        FileConfiguration: FileConfigurationTypeDef = ...,
+        ObjectConfiguration: Mapping[str, Mapping[str, Sequence[str]]] = ...
     ) -> CreateDataIntegrationResponseTypeDef:
         """
         Creates and persists a DataIntegration resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService.Client.create_data_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/client/#create_data_integration)
         """
```

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/literals.py` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -81,14 +81,15 @@
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
@@ -167,14 +168,15 @@
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
@@ -185,14 +187,15 @@
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
@@ -228,14 +231,15 @@
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
@@ -254,16 +258,19 @@
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
@@ -347,15 +354,17 @@
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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/literals.pyi` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -79,14 +79,15 @@
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
@@ -165,14 +166,15 @@
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
@@ -183,14 +185,15 @@
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
@@ -226,14 +229,15 @@
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
@@ -252,16 +256,19 @@
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
@@ -345,15 +352,17 @@
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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/type_defs.py` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/type_defs.pyi`

 * *Files 18% similar despite different names*

```diff
@@ -2,90 +2,116 @@
 Type annotations for appintegrations service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_appintegrations.type_defs import ScheduleConfigurationTypeDef
+    from types_aiobotocore_appintegrations.type_defs import FileConfigurationTypeDef
 
-    data: ScheduleConfigurationTypeDef = {...}
+    data: FileConfigurationTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Mapping, Sequence
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
+    "FileConfigurationTypeDef",
     "ScheduleConfigurationTypeDef",
-    "ResponseMetadataTypeDef",
     "EventFilterTypeDef",
+    "CreateEventIntegrationResponseTypeDef",
     "DataIntegrationAssociationSummaryTypeDef",
     "DataIntegrationSummaryTypeDef",
     "DeleteDataIntegrationRequestRequestTypeDef",
     "DeleteEventIntegrationRequestRequestTypeDef",
     "EventIntegrationAssociationTypeDef",
     "GetDataIntegrationRequestRequestTypeDef",
     "GetEventIntegrationRequestRequestTypeDef",
     "ListDataIntegrationAssociationsRequestRequestTypeDef",
     "ListDataIntegrationsRequestRequestTypeDef",
     "ListEventIntegrationAssociationsRequestRequestTypeDef",
     "ListEventIntegrationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDataIntegrationRequestRequestTypeDef",
     "UpdateEventIntegrationRequestRequestTypeDef",
     "CreateDataIntegrationRequestRequestTypeDef",
     "CreateDataIntegrationResponseTypeDef",
-    "CreateEventIntegrationResponseTypeDef",
     "GetDataIntegrationResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateEventIntegrationRequestRequestTypeDef",
     "EventIntegrationTypeDef",
     "GetEventIntegrationResponseTypeDef",
     "ListDataIntegrationAssociationsResponseTypeDef",
     "ListDataIntegrationsResponseTypeDef",
     "ListEventIntegrationAssociationsResponseTypeDef",
     "ListEventIntegrationsResponseTypeDef",
 )
 
-ScheduleConfigurationTypeDef = TypedDict(
-    "ScheduleConfigurationTypeDef",
+_RequiredFileConfigurationTypeDef = TypedDict(
+    "_RequiredFileConfigurationTypeDef",
     {
-        "FirstExecutionFrom": str,
-        "Object": str,
-        "ScheduleExpression": str,
+        "Folders": Sequence[str],
+    },
+)
+_OptionalFileConfigurationTypeDef = TypedDict(
+    "_OptionalFileConfigurationTypeDef",
+    {
+        "Filters": Mapping[str, Sequence[str]],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+class FileConfigurationTypeDef(
+    _RequiredFileConfigurationTypeDef, _OptionalFileConfigurationTypeDef
+):
+    pass
+
+_RequiredScheduleConfigurationTypeDef = TypedDict(
+    "_RequiredScheduleConfigurationTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScheduleExpression": str,
+    },
+)
+_OptionalScheduleConfigurationTypeDef = TypedDict(
+    "_OptionalScheduleConfigurationTypeDef",
+    {
+        "FirstExecutionFrom": str,
+        "Object": str,
     },
+    total=False,
 )
 
+class ScheduleConfigurationTypeDef(
+    _RequiredScheduleConfigurationTypeDef, _OptionalScheduleConfigurationTypeDef
+):
+    pass
+
 EventFilterTypeDef = TypedDict(
     "EventFilterTypeDef",
     {
         "Source": str,
     },
 )
 
+CreateEventIntegrationResponseTypeDef = TypedDict(
+    "CreateEventIntegrationResponseTypeDef",
+    {
+        "EventIntegrationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataIntegrationAssociationSummaryTypeDef = TypedDict(
     "DataIntegrationAssociationSummaryTypeDef",
     {
         "DataIntegrationAssociationArn": str,
         "DataIntegrationArn": str,
         "ClientId": str,
     },
@@ -154,22 +180,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListDataIntegrationAssociationsRequestRequestTypeDef(
     _RequiredListDataIntegrationAssociationsRequestRequestTypeDef,
     _OptionalListDataIntegrationAssociationsRequestRequestTypeDef,
 ):
     pass
 
-
 ListDataIntegrationsRequestRequestTypeDef = TypedDict(
     "ListDataIntegrationsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -186,22 +210,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListEventIntegrationAssociationsRequestRequestTypeDef(
     _RequiredListEventIntegrationAssociationsRequestRequestTypeDef,
     _OptionalListEventIntegrationAssociationsRequestRequestTypeDef,
 ):
     pass
 
-
 ListEventIntegrationsRequestRequestTypeDef = TypedDict(
     "ListEventIntegrationsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -210,14 +232,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -241,115 +282,99 @@
     {
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateDataIntegrationRequestRequestTypeDef(
     _RequiredUpdateDataIntegrationRequestRequestTypeDef,
     _OptionalUpdateDataIntegrationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateEventIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEventIntegrationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateEventIntegrationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateEventIntegrationRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateEventIntegrationRequestRequestTypeDef(
     _RequiredUpdateEventIntegrationRequestRequestTypeDef,
     _OptionalUpdateEventIntegrationRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDataIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDataIntegrationRequestRequestTypeDef",
     {
         "Name": str,
+        "KmsKey": str,
+        "SourceURI": str,
+        "ScheduleConfig": ScheduleConfigurationTypeDef,
     },
 )
 _OptionalCreateDataIntegrationRequestRequestTypeDef = TypedDict(
     "_OptionalCreateDataIntegrationRequestRequestTypeDef",
     {
         "Description": str,
-        "KmsKey": str,
-        "SourceURI": str,
-        "ScheduleConfig": ScheduleConfigurationTypeDef,
         "Tags": Mapping[str, str],
         "ClientToken": str,
+        "FileConfiguration": FileConfigurationTypeDef,
+        "ObjectConfiguration": Mapping[str, Mapping[str, Sequence[str]]],
     },
     total=False,
 )
 
-
 class CreateDataIntegrationRequestRequestTypeDef(
     _RequiredCreateDataIntegrationRequestRequestTypeDef,
     _OptionalCreateDataIntegrationRequestRequestTypeDef,
 ):
     pass
 
-
 CreateDataIntegrationResponseTypeDef = TypedDict(
     "CreateDataIntegrationResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "KmsKey": str,
         "SourceURI": str,
         "ScheduleConfiguration": ScheduleConfigurationTypeDef,
         "Tags": Dict[str, str],
         "ClientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEventIntegrationResponseTypeDef = TypedDict(
-    "CreateEventIntegrationResponseTypeDef",
-    {
-        "EventIntegrationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FileConfiguration": FileConfigurationTypeDef,
+        "ObjectConfiguration": Dict[str, Dict[str, List[str]]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataIntegrationResponseTypeDef = TypedDict(
     "GetDataIntegrationResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "KmsKey": str,
         "SourceURI": str,
         "ScheduleConfiguration": ScheduleConfigurationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FileConfiguration": FileConfigurationTypeDef,
+        "ObjectConfiguration": Dict[str, Dict[str, List[str]]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEventIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEventIntegrationRequestRequestTypeDef",
     {
         "Name": str,
@@ -363,22 +388,20 @@
         "Description": str,
         "ClientToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateEventIntegrationRequestRequestTypeDef(
     _RequiredCreateEventIntegrationRequestRequestTypeDef,
     _OptionalCreateEventIntegrationRequestRequestTypeDef,
 ):
     pass
 
-
 EventIntegrationTypeDef = TypedDict(
     "EventIntegrationTypeDef",
     {
         "EventIntegrationArn": str,
         "Name": str,
         "Description": str,
         "EventFilter": EventFilterTypeDef,
@@ -393,46 +416,46 @@
     {
         "Name": str,
         "Description": str,
         "EventIntegrationArn": str,
         "EventBridgeBus": str,
         "EventFilter": EventFilterTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataIntegrationAssociationsResponseTypeDef = TypedDict(
     "ListDataIntegrationAssociationsResponseTypeDef",
     {
         "DataIntegrationAssociations": List[DataIntegrationAssociationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataIntegrationsResponseTypeDef = TypedDict(
     "ListDataIntegrationsResponseTypeDef",
     {
         "DataIntegrations": List[DataIntegrationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventIntegrationAssociationsResponseTypeDef = TypedDict(
     "ListEventIntegrationAssociationsResponseTypeDef",
     {
         "EventIntegrationAssociations": List[EventIntegrationAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventIntegrationsResponseTypeDef = TypedDict(
     "ListEventIntegrationsResponseTypeDef",
     {
         "EventIntegrations": List[EventIntegrationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations/type_defs.pyi` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations/type_defs.py`

 * *Files 18% similar despite different names*

```diff
@@ -2,89 +2,121 @@
 Type annotations for appintegrations service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_appintegrations.type_defs import ScheduleConfigurationTypeDef
+    from types_aiobotocore_appintegrations.type_defs import FileConfigurationTypeDef
 
-    data: ScheduleConfigurationTypeDef = {...}
+    data: FileConfigurationTypeDef = {...}
     ```
 """
 import sys
 from typing import Dict, List, Mapping, Sequence
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
+    "FileConfigurationTypeDef",
     "ScheduleConfigurationTypeDef",
-    "ResponseMetadataTypeDef",
     "EventFilterTypeDef",
+    "CreateEventIntegrationResponseTypeDef",
     "DataIntegrationAssociationSummaryTypeDef",
     "DataIntegrationSummaryTypeDef",
     "DeleteDataIntegrationRequestRequestTypeDef",
     "DeleteEventIntegrationRequestRequestTypeDef",
     "EventIntegrationAssociationTypeDef",
     "GetDataIntegrationRequestRequestTypeDef",
     "GetEventIntegrationRequestRequestTypeDef",
     "ListDataIntegrationAssociationsRequestRequestTypeDef",
     "ListDataIntegrationsRequestRequestTypeDef",
     "ListEventIntegrationAssociationsRequestRequestTypeDef",
     "ListEventIntegrationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDataIntegrationRequestRequestTypeDef",
     "UpdateEventIntegrationRequestRequestTypeDef",
     "CreateDataIntegrationRequestRequestTypeDef",
     "CreateDataIntegrationResponseTypeDef",
-    "CreateEventIntegrationResponseTypeDef",
     "GetDataIntegrationResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "CreateEventIntegrationRequestRequestTypeDef",
     "EventIntegrationTypeDef",
     "GetEventIntegrationResponseTypeDef",
     "ListDataIntegrationAssociationsResponseTypeDef",
     "ListDataIntegrationsResponseTypeDef",
     "ListEventIntegrationAssociationsResponseTypeDef",
     "ListEventIntegrationsResponseTypeDef",
 )
 
-ScheduleConfigurationTypeDef = TypedDict(
-    "ScheduleConfigurationTypeDef",
+_RequiredFileConfigurationTypeDef = TypedDict(
+    "_RequiredFileConfigurationTypeDef",
     {
-        "FirstExecutionFrom": str,
-        "Object": str,
-        "ScheduleExpression": str,
+        "Folders": Sequence[str],
+    },
+)
+_OptionalFileConfigurationTypeDef = TypedDict(
+    "_OptionalFileConfigurationTypeDef",
+    {
+        "Filters": Mapping[str, Sequence[str]],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+class FileConfigurationTypeDef(
+    _RequiredFileConfigurationTypeDef, _OptionalFileConfigurationTypeDef
+):
+    pass
+
+
+_RequiredScheduleConfigurationTypeDef = TypedDict(
+    "_RequiredScheduleConfigurationTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScheduleExpression": str,
+    },
+)
+_OptionalScheduleConfigurationTypeDef = TypedDict(
+    "_OptionalScheduleConfigurationTypeDef",
+    {
+        "FirstExecutionFrom": str,
+        "Object": str,
     },
+    total=False,
 )
 
+
+class ScheduleConfigurationTypeDef(
+    _RequiredScheduleConfigurationTypeDef, _OptionalScheduleConfigurationTypeDef
+):
+    pass
+
+
 EventFilterTypeDef = TypedDict(
     "EventFilterTypeDef",
     {
         "Source": str,
     },
 )
 
+CreateEventIntegrationResponseTypeDef = TypedDict(
+    "CreateEventIntegrationResponseTypeDef",
+    {
+        "EventIntegrationArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataIntegrationAssociationSummaryTypeDef = TypedDict(
     "DataIntegrationAssociationSummaryTypeDef",
     {
         "DataIntegrationAssociationArn": str,
         "DataIntegrationArn": str,
         "ClientId": str,
     },
@@ -153,20 +185,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListDataIntegrationAssociationsRequestRequestTypeDef(
     _RequiredListDataIntegrationAssociationsRequestRequestTypeDef,
     _OptionalListDataIntegrationAssociationsRequestRequestTypeDef,
 ):
     pass
 
+
 ListDataIntegrationsRequestRequestTypeDef = TypedDict(
     "ListDataIntegrationsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -183,20 +217,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListEventIntegrationAssociationsRequestRequestTypeDef(
     _RequiredListEventIntegrationAssociationsRequestRequestTypeDef,
     _OptionalListEventIntegrationAssociationsRequestRequestTypeDef,
 ):
     pass
 
+
 ListEventIntegrationsRequestRequestTypeDef = TypedDict(
     "ListEventIntegrationsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -205,14 +241,33 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -236,109 +291,105 @@
     {
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateDataIntegrationRequestRequestTypeDef(
     _RequiredUpdateDataIntegrationRequestRequestTypeDef,
     _OptionalUpdateDataIntegrationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateEventIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEventIntegrationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateEventIntegrationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateEventIntegrationRequestRequestTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateEventIntegrationRequestRequestTypeDef(
     _RequiredUpdateEventIntegrationRequestRequestTypeDef,
     _OptionalUpdateEventIntegrationRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDataIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDataIntegrationRequestRequestTypeDef",
     {
         "Name": str,
+        "KmsKey": str,
+        "SourceURI": str,
+        "ScheduleConfig": ScheduleConfigurationTypeDef,
     },
 )
 _OptionalCreateDataIntegrationRequestRequestTypeDef = TypedDict(
     "_OptionalCreateDataIntegrationRequestRequestTypeDef",
     {
         "Description": str,
-        "KmsKey": str,
-        "SourceURI": str,
-        "ScheduleConfig": ScheduleConfigurationTypeDef,
         "Tags": Mapping[str, str],
         "ClientToken": str,
+        "FileConfiguration": FileConfigurationTypeDef,
+        "ObjectConfiguration": Mapping[str, Mapping[str, Sequence[str]]],
     },
     total=False,
 )
 
+
 class CreateDataIntegrationRequestRequestTypeDef(
     _RequiredCreateDataIntegrationRequestRequestTypeDef,
     _OptionalCreateDataIntegrationRequestRequestTypeDef,
 ):
     pass
 
+
 CreateDataIntegrationResponseTypeDef = TypedDict(
     "CreateDataIntegrationResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "KmsKey": str,
         "SourceURI": str,
         "ScheduleConfiguration": ScheduleConfigurationTypeDef,
         "Tags": Dict[str, str],
         "ClientToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEventIntegrationResponseTypeDef = TypedDict(
-    "CreateEventIntegrationResponseTypeDef",
-    {
-        "EventIntegrationArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FileConfiguration": FileConfigurationTypeDef,
+        "ObjectConfiguration": Dict[str, Dict[str, List[str]]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataIntegrationResponseTypeDef = TypedDict(
     "GetDataIntegrationResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "KmsKey": str,
         "SourceURI": str,
         "ScheduleConfiguration": ScheduleConfigurationTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FileConfiguration": FileConfigurationTypeDef,
+        "ObjectConfiguration": Dict[str, Dict[str, List[str]]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEventIntegrationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEventIntegrationRequestRequestTypeDef",
     {
         "Name": str,
@@ -352,20 +403,22 @@
         "Description": str,
         "ClientToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateEventIntegrationRequestRequestTypeDef(
     _RequiredCreateEventIntegrationRequestRequestTypeDef,
     _OptionalCreateEventIntegrationRequestRequestTypeDef,
 ):
     pass
 
+
 EventIntegrationTypeDef = TypedDict(
     "EventIntegrationTypeDef",
     {
         "EventIntegrationArn": str,
         "Name": str,
         "Description": str,
         "EventFilter": EventFilterTypeDef,
@@ -380,46 +433,46 @@
     {
         "Name": str,
         "Description": str,
         "EventIntegrationArn": str,
         "EventBridgeBus": str,
         "EventFilter": EventFilterTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataIntegrationAssociationsResponseTypeDef = TypedDict(
     "ListDataIntegrationAssociationsResponseTypeDef",
     {
         "DataIntegrationAssociations": List[DataIntegrationAssociationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataIntegrationsResponseTypeDef = TypedDict(
     "ListDataIntegrationsResponseTypeDef",
     {
         "DataIntegrations": List[DataIntegrationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventIntegrationAssociationsResponseTypeDef = TypedDict(
     "ListEventIntegrationAssociationsResponseTypeDef",
     {
         "EventIntegrationAssociations": List[EventIntegrationAssociationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventIntegrationsResponseTypeDef = TypedDict(
     "ListEventIntegrationsResponseTypeDef",
     {
         "EventIntegrations": List[EventIntegrationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/PKG-INFO` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appintegrations
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppIntegrationsService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppIntegrationsService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appintegrations"></a>
 
 # types-aiobotocore-appintegrations
 
 [![PyPI - types-aiobotocore-appintegrations](https://img.shields.io/pypi/v/types-aiobotocore-appintegrations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appintegrations)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appintegrations.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appintegrations)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appintegrations?color=blue)](https://pypistats.org/packages/types-aiobotocore-appintegrations)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppIntegrationsService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService)
+[aiobotocore.AppIntegrationsService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appintegrations.html#AppIntegrationsService)
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
 [types-aiobotocore-appintegrations docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appintegrations/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,88 +289,89 @@
 ### Typed dictionaries
 
 `types_aiobotocore_appintegrations.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_appintegrations.type_defs import (
+    FileConfigurationTypeDef,
     ScheduleConfigurationTypeDef,
-    ResponseMetadataTypeDef,
     EventFilterTypeDef,
+    CreateEventIntegrationResponseTypeDef,
     DataIntegrationAssociationSummaryTypeDef,
     DataIntegrationSummaryTypeDef,
     DeleteDataIntegrationRequestRequestTypeDef,
     DeleteEventIntegrationRequestRequestTypeDef,
     EventIntegrationAssociationTypeDef,
     GetDataIntegrationRequestRequestTypeDef,
     GetEventIntegrationRequestRequestTypeDef,
     ListDataIntegrationAssociationsRequestRequestTypeDef,
     ListDataIntegrationsRequestRequestTypeDef,
     ListEventIntegrationAssociationsRequestRequestTypeDef,
     ListEventIntegrationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDataIntegrationRequestRequestTypeDef,
     UpdateEventIntegrationRequestRequestTypeDef,
     CreateDataIntegrationRequestRequestTypeDef,
     CreateDataIntegrationResponseTypeDef,
-    CreateEventIntegrationResponseTypeDef,
     GetDataIntegrationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     CreateEventIntegrationRequestRequestTypeDef,
     EventIntegrationTypeDef,
     GetEventIntegrationResponseTypeDef,
     ListDataIntegrationAssociationsResponseTypeDef,
     ListDataIntegrationsResponseTypeDef,
     ListEventIntegrationAssociationsResponseTypeDef,
     ListEventIntegrationsResponseTypeDef,
 )
 
 
-def get_structure() -> ScheduleConfigurationTypeDef:
+def get_structure() -> FileConfigurationTypeDef:
     return {...}
 ```
 
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

### Comparing `types-aiobotocore-appintegrations-2.5.0.post1/types_aiobotocore_appintegrations.egg-info/SOURCES.txt` & `types-aiobotocore-appintegrations-2.5.1/types_aiobotocore_appintegrations.egg-info/SOURCES.txt`

 * *Files identical despite different names*

