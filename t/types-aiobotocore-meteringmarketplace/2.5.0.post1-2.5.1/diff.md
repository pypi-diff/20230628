# Comparing `tmp/types-aiobotocore-meteringmarketplace-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-meteringmarketplace-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-meteringmarketplace-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:00 2023, max compression
+gzip compressed data, was "types-aiobotocore-meteringmarketplace-2.5.1.tar", last modified: Wed Jun 28 01:43:51 2023, max compression
```

## Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1.tar` & `types-aiobotocore-meteringmarketplace-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.859438 types-aiobotocore-meteringmarketplace-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13071 2023-03-11 12:27:00.859438 types-aiobotocore-meteringmarketplace-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11452 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:00.859438 types-aiobotocore-meteringmarketplace-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2200 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.855438 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/
--rw-r--r--   0 runner    (1001) docker     (123)      538 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      537 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      991 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8035 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8023 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8098 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8096 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     4851 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     4842 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:43.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:00.859438 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13071 2023-03-11 12:27:00.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:27:00.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:00.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:00.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:00.000000 types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.806178 types-aiobotocore-meteringmarketplace-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13075 2023-06-28 01:43:51.806178 types-aiobotocore-meteringmarketplace-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11462 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:51.806178 types-aiobotocore-meteringmarketplace-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2194 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.806178 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/
+-rw-r--r--   0 runner    (1001) docker     (123)      538 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      537 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      979 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8035 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8023 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8307 2023-06-28 01:35:26.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8305 2023-06-28 01:35:26.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     4859 2023-06-28 01:35:26.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4850 2023-06-28 01:35:26.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:25.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:51.806178 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13075 2023-06-28 01:43:51.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 01:43:51.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:51.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:51.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:51.000000 types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/LICENSE` & `types-aiobotocore-meteringmarketplace-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/PKG-INFO` & `types-aiobotocore-meteringmarketplace-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-meteringmarketplace
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceMetering 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceMetering 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-meteringmarketplace"></a>
 
 # types-aiobotocore-meteringmarketplace
 
 [![PyPI - types-aiobotocore-meteringmarketplace](https://img.shields.io/pypi/v/types-aiobotocore-meteringmarketplace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-meteringmarketplace)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-meteringmarketplace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-meteringmarketplace)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-meteringmarketplace?color=blue)](https://pypistats.org/packages/types-aiobotocore-meteringmarketplace)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceMetering 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering)
+[aiobotocore.MarketplaceMetering 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering)
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
 [types-aiobotocore-meteringmarketplace docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,70 +290,70 @@
 ### Typed dictionaries
 
 `types_aiobotocore_meteringmarketplace.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_meteringmarketplace.type_defs import (
-    ResponseMetadataTypeDef,
-    RegisterUsageRequestRequestTypeDef,
-    ResolveCustomerRequestRequestTypeDef,
-    TagTypeDef,
     MeterUsageResultTypeDef,
+    RegisterUsageRequestRequestTypeDef,
     RegisterUsageResultTypeDef,
+    ResolveCustomerRequestRequestTypeDef,
     ResolveCustomerResultTypeDef,
+    ResponseMetadataTypeDef,
+    TagTypeDef,
     UsageAllocationTypeDef,
     MeterUsageRequestRequestTypeDef,
     UsageRecordTypeDef,
     BatchMeterUsageRequestRequestTypeDef,
     UsageRecordResultTypeDef,
     BatchMeterUsageResultTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> MeterUsageResultTypeDef:
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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/README.md` & `types-aiobotocore-meteringmarketplace-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-meteringmarketplace"></a>
 
 # types-aiobotocore-meteringmarketplace
 
 [![PyPI - types-aiobotocore-meteringmarketplace](https://img.shields.io/pypi/v/types-aiobotocore-meteringmarketplace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-meteringmarketplace)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-meteringmarketplace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-meteringmarketplace)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-meteringmarketplace?color=blue)](https://pypistats.org/packages/types-aiobotocore-meteringmarketplace)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceMetering 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering)
+[aiobotocore.MarketplaceMetering 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering)
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
 [types-aiobotocore-meteringmarketplace docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/).
 
 See how it helps to find and fix potential bugs:
 
@@ -257,70 +257,70 @@
 ### Typed dictionaries
 
 `types_aiobotocore_meteringmarketplace.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_meteringmarketplace.type_defs import (
-    ResponseMetadataTypeDef,
-    RegisterUsageRequestRequestTypeDef,
-    ResolveCustomerRequestRequestTypeDef,
-    TagTypeDef,
     MeterUsageResultTypeDef,
+    RegisterUsageRequestRequestTypeDef,
     RegisterUsageResultTypeDef,
+    ResolveCustomerRequestRequestTypeDef,
     ResolveCustomerResultTypeDef,
+    ResponseMetadataTypeDef,
+    TagTypeDef,
     UsageAllocationTypeDef,
     MeterUsageRequestRequestTypeDef,
     UsageRecordTypeDef,
     BatchMeterUsageRequestRequestTypeDef,
     UsageRecordResultTypeDef,
     BatchMeterUsageResultTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> MeterUsageResultTypeDef:
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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/setup.py` & `types-aiobotocore-meteringmarketplace-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-meteringmarketplace.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-meteringmarketplace",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_meteringmarketplace"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MarketplaceMetering 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MarketplaceMetering 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/",
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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/__init__.py` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/__init__.pyi` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/__main__.py` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/__main__.py`

 * *Files 3% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MarketplaceMetering 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MarketplaceMetering 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering\nOther"
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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/client.py` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/client.pyi` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/literals.py` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -14,24 +14,22 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "UsageRecordResultStatusType",
     "MarketplaceMeteringServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 UsageRecordResultStatusType = Literal["CustomerNotSubscribed", "DuplicateRecord", "Success"]
 MarketplaceMeteringServiceName = Literal["meteringmarketplace"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -88,14 +86,15 @@
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
@@ -174,14 +173,15 @@
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
@@ -192,14 +192,15 @@
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
@@ -235,14 +236,15 @@
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
@@ -261,16 +263,19 @@
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
@@ -354,15 +359,17 @@
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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/literals.pyi` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/literals.py`

 * *Files 6% similar despite different names*

```diff
@@ -14,22 +14,24 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "UsageRecordResultStatusType",
     "MarketplaceMeteringServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 UsageRecordResultStatusType = Literal["CustomerNotSubscribed", "DuplicateRecord", "Success"]
 MarketplaceMeteringServiceName = Literal["meteringmarketplace"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -86,14 +88,15 @@
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
@@ -172,14 +175,15 @@
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
@@ -190,14 +194,15 @@
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
@@ -233,14 +238,15 @@
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
@@ -259,16 +265,19 @@
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
@@ -352,15 +361,17 @@
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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/type_defs.py` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for meteringmarketplace service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_meteringmarketplace.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_meteringmarketplace.type_defs import MeterUsageResultTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: MeterUsageResultTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
 from .literals import UsageRecordResultStatusType
@@ -20,37 +20,34 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
-    "ResponseMetadataTypeDef",
-    "RegisterUsageRequestRequestTypeDef",
-    "ResolveCustomerRequestRequestTypeDef",
-    "TagTypeDef",
     "MeterUsageResultTypeDef",
+    "RegisterUsageRequestRequestTypeDef",
     "RegisterUsageResultTypeDef",
+    "ResolveCustomerRequestRequestTypeDef",
     "ResolveCustomerResultTypeDef",
+    "ResponseMetadataTypeDef",
+    "TagTypeDef",
     "UsageAllocationTypeDef",
     "MeterUsageRequestRequestTypeDef",
     "UsageRecordTypeDef",
     "BatchMeterUsageRequestRequestTypeDef",
     "UsageRecordResultTypeDef",
     "BatchMeterUsageResultTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+MeterUsageResultTypeDef = TypedDict(
+    "MeterUsageResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "MeteringRecordId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterUsageRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterUsageRequestRequestTypeDef",
     {
         "ProductCode": str,
@@ -68,53 +65,56 @@
 
 class RegisterUsageRequestRequestTypeDef(
     _RequiredRegisterUsageRequestRequestTypeDef, _OptionalRegisterUsageRequestRequestTypeDef
 ):
     pass
 
 
-ResolveCustomerRequestRequestTypeDef = TypedDict(
-    "ResolveCustomerRequestRequestTypeDef",
+RegisterUsageResultTypeDef = TypedDict(
+    "RegisterUsageResultTypeDef",
     {
-        "RegistrationToken": str,
+        "PublicKeyRotationTimestamp": datetime,
+        "Signature": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-TagTypeDef = TypedDict(
-    "TagTypeDef",
+ResolveCustomerRequestRequestTypeDef = TypedDict(
+    "ResolveCustomerRequestRequestTypeDef",
     {
-        "Key": str,
-        "Value": str,
+        "RegistrationToken": str,
     },
 )
 
-MeterUsageResultTypeDef = TypedDict(
-    "MeterUsageResultTypeDef",
+ResolveCustomerResultTypeDef = TypedDict(
+    "ResolveCustomerResultTypeDef",
     {
-        "MeteringRecordId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CustomerIdentifier": str,
+        "ProductCode": str,
+        "CustomerAWSAccountId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RegisterUsageResultTypeDef = TypedDict(
-    "RegisterUsageResultTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "PublicKeyRotationTimestamp": datetime,
-        "Signature": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-ResolveCustomerResultTypeDef = TypedDict(
-    "ResolveCustomerResultTypeDef",
+TagTypeDef = TypedDict(
+    "TagTypeDef",
     {
-        "CustomerIdentifier": str,
-        "ProductCode": str,
-        "CustomerAWSAccountId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Key": str,
+        "Value": str,
     },
 )
 
 _RequiredUsageAllocationTypeDef = TypedDict(
     "_RequiredUsageAllocationTypeDef",
     {
         "AllocatedUsageQuantity": int,
@@ -199,10 +199,10 @@
 )
 
 BatchMeterUsageResultTypeDef = TypedDict(
     "BatchMeterUsageResultTypeDef",
     {
         "Results": List[UsageRecordResultTypeDef],
         "UnprocessedRecords": List[UsageRecordTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace/type_defs.pyi` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -2,54 +2,51 @@
 Type annotations for meteringmarketplace service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_meteringmarketplace.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_meteringmarketplace.type_defs import MeterUsageResultTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: MeterUsageResultTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
 from .literals import UsageRecordResultStatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
-    "ResponseMetadataTypeDef",
-    "RegisterUsageRequestRequestTypeDef",
-    "ResolveCustomerRequestRequestTypeDef",
-    "TagTypeDef",
     "MeterUsageResultTypeDef",
+    "RegisterUsageRequestRequestTypeDef",
     "RegisterUsageResultTypeDef",
+    "ResolveCustomerRequestRequestTypeDef",
     "ResolveCustomerResultTypeDef",
+    "ResponseMetadataTypeDef",
+    "TagTypeDef",
     "UsageAllocationTypeDef",
     "MeterUsageRequestRequestTypeDef",
     "UsageRecordTypeDef",
     "BatchMeterUsageRequestRequestTypeDef",
     "UsageRecordResultTypeDef",
     "BatchMeterUsageResultTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+MeterUsageResultTypeDef = TypedDict(
+    "MeterUsageResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "MeteringRecordId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterUsageRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterUsageRequestRequestTypeDef",
     {
         "ProductCode": str,
@@ -65,53 +62,56 @@
 )
 
 class RegisterUsageRequestRequestTypeDef(
     _RequiredRegisterUsageRequestRequestTypeDef, _OptionalRegisterUsageRequestRequestTypeDef
 ):
     pass
 
-ResolveCustomerRequestRequestTypeDef = TypedDict(
-    "ResolveCustomerRequestRequestTypeDef",
+RegisterUsageResultTypeDef = TypedDict(
+    "RegisterUsageResultTypeDef",
     {
-        "RegistrationToken": str,
+        "PublicKeyRotationTimestamp": datetime,
+        "Signature": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-TagTypeDef = TypedDict(
-    "TagTypeDef",
+ResolveCustomerRequestRequestTypeDef = TypedDict(
+    "ResolveCustomerRequestRequestTypeDef",
     {
-        "Key": str,
-        "Value": str,
+        "RegistrationToken": str,
     },
 )
 
-MeterUsageResultTypeDef = TypedDict(
-    "MeterUsageResultTypeDef",
+ResolveCustomerResultTypeDef = TypedDict(
+    "ResolveCustomerResultTypeDef",
     {
-        "MeteringRecordId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CustomerIdentifier": str,
+        "ProductCode": str,
+        "CustomerAWSAccountId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RegisterUsageResultTypeDef = TypedDict(
-    "RegisterUsageResultTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "PublicKeyRotationTimestamp": datetime,
-        "Signature": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-ResolveCustomerResultTypeDef = TypedDict(
-    "ResolveCustomerResultTypeDef",
+TagTypeDef = TypedDict(
+    "TagTypeDef",
     {
-        "CustomerIdentifier": str,
-        "ProductCode": str,
-        "CustomerAWSAccountId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Key": str,
+        "Value": str,
     },
 )
 
 _RequiredUsageAllocationTypeDef = TypedDict(
     "_RequiredUsageAllocationTypeDef",
     {
         "AllocatedUsageQuantity": int,
@@ -190,10 +190,10 @@
 )
 
 BatchMeterUsageResultTypeDef = TypedDict(
     "BatchMeterUsageResultTypeDef",
     {
         "Results": List[UsageRecordResultTypeDef],
         "UnprocessedRecords": List[UsageRecordTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/PKG-INFO` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-meteringmarketplace
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MarketplaceMetering 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MarketplaceMetering 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-meteringmarketplace"></a>
 
 # types-aiobotocore-meteringmarketplace
 
 [![PyPI - types-aiobotocore-meteringmarketplace](https://img.shields.io/pypi/v/types-aiobotocore-meteringmarketplace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-meteringmarketplace)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-meteringmarketplace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-meteringmarketplace)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-meteringmarketplace?color=blue)](https://pypistats.org/packages/types-aiobotocore-meteringmarketplace)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MarketplaceMetering 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering)
+[aiobotocore.MarketplaceMetering 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/meteringmarketplace.html#MarketplaceMetering)
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
 [types-aiobotocore-meteringmarketplace docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_meteringmarketplace/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,70 +290,70 @@
 ### Typed dictionaries
 
 `types_aiobotocore_meteringmarketplace.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_meteringmarketplace.type_defs import (
-    ResponseMetadataTypeDef,
-    RegisterUsageRequestRequestTypeDef,
-    ResolveCustomerRequestRequestTypeDef,
-    TagTypeDef,
     MeterUsageResultTypeDef,
+    RegisterUsageRequestRequestTypeDef,
     RegisterUsageResultTypeDef,
+    ResolveCustomerRequestRequestTypeDef,
     ResolveCustomerResultTypeDef,
+    ResponseMetadataTypeDef,
+    TagTypeDef,
     UsageAllocationTypeDef,
     MeterUsageRequestRequestTypeDef,
     UsageRecordTypeDef,
     BatchMeterUsageRequestRequestTypeDef,
     UsageRecordResultTypeDef,
     BatchMeterUsageResultTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> MeterUsageResultTypeDef:
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

### Comparing `types-aiobotocore-meteringmarketplace-2.5.0.post1/types_aiobotocore_meteringmarketplace.egg-info/SOURCES.txt` & `types-aiobotocore-meteringmarketplace-2.5.1/types_aiobotocore_meteringmarketplace.egg-info/SOURCES.txt`

 * *Files identical despite different names*

