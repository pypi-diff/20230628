# Comparing `tmp/types-aiobotocore-cloudtrail-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudtrail-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudtrail-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:22 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudtrail-data-2.5.1.tar", last modified: Wed Jun 28 01:43:14 2023, max compression
```

## Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1.tar` & `types-aiobotocore-cloudtrail-data-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.167047 types-aiobotocore-cloudtrail-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12674 2023-03-11 12:26:22.167047 types-aiobotocore-cloudtrail-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11065 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:22.167047 types-aiobotocore-cloudtrail-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.167047 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/
--rw-r--r--   0 runner    (1001) docker     (123)      536 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      535 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      987 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5094 2023-03-11 12:11:02.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     5085 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7845 2023-03-11 12:11:02.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7843 2023-03-11 12:11:02.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     2421 2023-03-11 12:11:02.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     2416 2023-03-11 12:11:02.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:01.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.167047 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12674 2023-03-11 12:26:21.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:22.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:21.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:21.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:21.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:26:21.000000 types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:14.646109 types-aiobotocore-cloudtrail-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12674 2023-06-28 01:43:14.646109 types-aiobotocore-cloudtrail-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11071 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:14.646109 types-aiobotocore-cloudtrail-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:14.646109 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/
+-rw-r--r--   0 runner    (1001) docker     (123)      536 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      535 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5094 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5085 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8054 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8052 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     2423 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2418 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:38.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:14.646109 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12674 2023-06-28 01:43:14.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:14.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:14.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:14.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:14.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:43:14.000000 types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudtrail-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudtrail-data-2.5.1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudtrail-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudTrailDataService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudTrailDataService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudtrail-data"></a>
 
 # types-aiobotocore-cloudtrail-data
 
 [![PyPI - types-aiobotocore-cloudtrail-data](https://img.shields.io/pypi/v/types-aiobotocore-cloudtrail-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudtrail-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudtrail-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudtrail-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudtrail-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudtrail-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudTrailDataService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail-data.html#CloudTrailDataService)
+[aiobotocore.CloudTrailDataService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail-data.html#CloudTrailDataService)
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
 [types-aiobotocore-cloudtrail-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,16 +291,16 @@
 `types_aiobotocore_cloudtrail_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudtrail_data.type_defs import (
     AuditEventResultEntryTypeDef,
     AuditEventTypeDef,
-    ResponseMetadataTypeDef,
     ResultErrorEntryTypeDef,
+    ResponseMetadataTypeDef,
     PutAuditEventsRequestRequestTypeDef,
     PutAuditEventsResponseTypeDef,
 )
 
 
 def get_structure() -> AuditEventResultEntryTypeDef:
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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/README.md` & `types-aiobotocore-cloudtrail-data-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudtrail-data"></a>
 
 # types-aiobotocore-cloudtrail-data
 
 [![PyPI - types-aiobotocore-cloudtrail-data](https://img.shields.io/pypi/v/types-aiobotocore-cloudtrail-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudtrail-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudtrail-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudtrail-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudtrail-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudtrail-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudTrailDataService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail-data.html#CloudTrailDataService)
+[aiobotocore.CloudTrailDataService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail-data.html#CloudTrailDataService)
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
 [types-aiobotocore-cloudtrail-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -258,16 +258,16 @@
 `types_aiobotocore_cloudtrail_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudtrail_data.type_defs import (
     AuditEventResultEntryTypeDef,
     AuditEventTypeDef,
-    ResponseMetadataTypeDef,
     ResultErrorEntryTypeDef,
+    ResponseMetadataTypeDef,
     PutAuditEventsRequestRequestTypeDef,
     PutAuditEventsResponseTypeDef,
 )
 
 
 def get_structure() -> AuditEventResultEntryTypeDef:
     return {...}
@@ -276,43 +276,43 @@
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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/setup.py` & `types-aiobotocore-cloudtrail-data-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudtrail-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudtrail-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudtrail_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudTrailDataService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudTrailDataService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/"
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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/__init__.py` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/__init__.pyi` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/__main__.py` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CloudTrailDataService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CloudTrailDataService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail-data.html#CloudTrailDataService\nOther"
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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/client.py` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/client.pyi` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/literals.py` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/literals.py`

 * *Files 3% similar despite different names*

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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/literals.pyi` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/literals.pyi`

 * *Files 3% similar despite different names*

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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/type_defs.py` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AuditEventResultEntryTypeDef",
     "AuditEventTypeDef",
-    "ResponseMetadataTypeDef",
     "ResultErrorEntryTypeDef",
+    "ResponseMetadataTypeDef",
     "PutAuditEventsRequestRequestTypeDef",
     "PutAuditEventsResponseTypeDef",
 )
 
 AuditEventResultEntryTypeDef = TypedDict(
     "AuditEventResultEntryTypeDef",
     {
@@ -53,34 +53,34 @@
 )
 
 
 class AuditEventTypeDef(_RequiredAuditEventTypeDef, _OptionalAuditEventTypeDef):
     pass
 
 
+ResultErrorEntryTypeDef = TypedDict(
+    "ResultErrorEntryTypeDef",
+    {
+        "errorCode": str,
+        "errorMessage": str,
+        "id": str,
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
         "RetryAttempts": int,
     },
 )
 
-ResultErrorEntryTypeDef = TypedDict(
-    "ResultErrorEntryTypeDef",
-    {
-        "errorCode": str,
-        "errorMessage": str,
-        "id": str,
-    },
-)
-
 _RequiredPutAuditEventsRequestRequestTypeDef = TypedDict(
     "_RequiredPutAuditEventsRequestRequestTypeDef",
     {
         "auditEvents": Sequence[AuditEventTypeDef],
         "channelArn": str,
     },
 )
@@ -100,10 +100,10 @@
 
 
 PutAuditEventsResponseTypeDef = TypedDict(
     "PutAuditEventsResponseTypeDef",
     {
         "failed": List[ResultErrorEntryTypeDef],
         "successful": List[AuditEventResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data/type_defs.pyi` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -18,16 +18,16 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AuditEventResultEntryTypeDef",
     "AuditEventTypeDef",
-    "ResponseMetadataTypeDef",
     "ResultErrorEntryTypeDef",
+    "ResponseMetadataTypeDef",
     "PutAuditEventsRequestRequestTypeDef",
     "PutAuditEventsResponseTypeDef",
 )
 
 AuditEventResultEntryTypeDef = TypedDict(
     "AuditEventResultEntryTypeDef",
     {
@@ -50,34 +50,34 @@
     },
     total=False,
 )
 
 class AuditEventTypeDef(_RequiredAuditEventTypeDef, _OptionalAuditEventTypeDef):
     pass
 
+ResultErrorEntryTypeDef = TypedDict(
+    "ResultErrorEntryTypeDef",
+    {
+        "errorCode": str,
+        "errorMessage": str,
+        "id": str,
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
         "RetryAttempts": int,
     },
 )
 
-ResultErrorEntryTypeDef = TypedDict(
-    "ResultErrorEntryTypeDef",
-    {
-        "errorCode": str,
-        "errorMessage": str,
-        "id": str,
-    },
-)
-
 _RequiredPutAuditEventsRequestRequestTypeDef = TypedDict(
     "_RequiredPutAuditEventsRequestRequestTypeDef",
     {
         "auditEvents": Sequence[AuditEventTypeDef],
         "channelArn": str,
     },
 )
@@ -95,10 +95,10 @@
     pass
 
 PutAuditEventsResponseTypeDef = TypedDict(
     "PutAuditEventsResponseTypeDef",
     {
         "failed": List[ResultErrorEntryTypeDef],
         "successful": List[AuditEventResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/PKG-INFO` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudtrail-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudTrailDataService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudTrailDataService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudtrail-data"></a>
 
 # types-aiobotocore-cloudtrail-data
 
 [![PyPI - types-aiobotocore-cloudtrail-data](https://img.shields.io/pypi/v/types-aiobotocore-cloudtrail-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudtrail-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudtrail-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudtrail-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudtrail-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudtrail-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudTrailDataService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail-data.html#CloudTrailDataService)
+[aiobotocore.CloudTrailDataService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudtrail-data.html#CloudTrailDataService)
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
 [types-aiobotocore-cloudtrail-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudtrail_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,16 +291,16 @@
 `types_aiobotocore_cloudtrail_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cloudtrail_data.type_defs import (
     AuditEventResultEntryTypeDef,
     AuditEventTypeDef,
-    ResponseMetadataTypeDef,
     ResultErrorEntryTypeDef,
+    ResponseMetadataTypeDef,
     PutAuditEventsRequestRequestTypeDef,
     PutAuditEventsResponseTypeDef,
 )
 
 
 def get_structure() -> AuditEventResultEntryTypeDef:
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

### Comparing `types-aiobotocore-cloudtrail-data-2.5.0.post1/types_aiobotocore_cloudtrail_data.egg-info/SOURCES.txt` & `types-aiobotocore-cloudtrail-data-2.5.1/types_aiobotocore_cloudtrail_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

