# Comparing `tmp/types-aiobotocore-arc-zonal-shift-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-arc-zonal-shift-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-arc-zonal-shift-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-arc-zonal-shift-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1.tar` & `types-aiobotocore-arc-zonal-shift-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.926950 types-aiobotocore-arc-zonal-shift-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14186 2023-03-11 12:26:12.922950 types-aiobotocore-arc-zonal-shift-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12585 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.926950 types-aiobotocore-arc-zonal-shift-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2178 2023-03-11 12:09:50.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.918950 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/
--rw-r--r--   0 runner    (1001) docker     (123)      948 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9732 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     9715 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8059 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8057 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3472 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3467 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5868 2023-03-11 12:09:52.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5863 2023-03-11 12:09:52.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:51.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.918950 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14186 2023-03-11 12:26:12.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:26:12.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:26:12.000000 types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.670094 types-aiobotocore-arc-zonal-shift-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14186 2023-06-28 01:43:06.670094 types-aiobotocore-arc-zonal-shift-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12591 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.670094 types-aiobotocore-arc-zonal-shift-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.670094 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/
+-rw-r--r--   0 runner    (1001) docker     (123)      948 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9732 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9715 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8587 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8585 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3380 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3376 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     5880 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5875 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:28.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.670094 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14186 2023-06-28 01:43:06.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:43:06.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:43:06.000000 types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/LICENSE` & `types-aiobotocore-arc-zonal-shift-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/PKG-INFO` & `types-aiobotocore-arc-zonal-shift-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-arc-zonal-shift
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ARCZonalShift 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ARCZonalShift 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-arc-zonal-shift"></a>
 
 # types-aiobotocore-arc-zonal-shift
 
 [![PyPI - types-aiobotocore-arc-zonal-shift](https://img.shields.io/pypi/v/types-aiobotocore-arc-zonal-shift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-arc-zonal-shift)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-arc-zonal-shift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-arc-zonal-shift)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-arc-zonal-shift?color=blue)](https://pypistats.org/packages/types-aiobotocore-arc-zonal-shift)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ARCZonalShift 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift)
+[aiobotocore.ARCZonalShift 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift)
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
 [types-aiobotocore-arc-zonal-shift docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/).
 
 See how it helps to find and fix potential bugs:
 
@@ -327,27 +327,27 @@
 `types_aiobotocore_arc_zonal_shift.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_arc_zonal_shift.type_defs import (
     CancelZonalShiftRequestRequestTypeDef,
     GetManagedResourceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ZonalShiftInResourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListManagedResourcesRequestListManagedResourcesPaginateTypeDef,
     ListManagedResourcesRequestRequestTypeDef,
     ManagedResourceSummaryTypeDef,
+    ListZonalShiftsRequestListZonalShiftsPaginateTypeDef,
     ListZonalShiftsRequestRequestTypeDef,
     ZonalShiftSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartZonalShiftRequestRequestTypeDef,
     UpdateZonalShiftRequestRequestTypeDef,
     ZonalShiftTypeDef,
     GetManagedResourceResponseTypeDef,
-    ListManagedResourcesRequestListManagedResourcesPaginateTypeDef,
-    ListZonalShiftsRequestListZonalShiftsPaginateTypeDef,
     ListManagedResourcesResponseTypeDef,
     ListZonalShiftsResponseTypeDef,
 )
 
 
 def get_structure() -> CancelZonalShiftRequestRequestTypeDef:
     return {...}
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/README.md` & `types-aiobotocore-arc-zonal-shift-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-arc-zonal-shift"></a>
 
 # types-aiobotocore-arc-zonal-shift
 
 [![PyPI - types-aiobotocore-arc-zonal-shift](https://img.shields.io/pypi/v/types-aiobotocore-arc-zonal-shift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-arc-zonal-shift)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-arc-zonal-shift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-arc-zonal-shift)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-arc-zonal-shift?color=blue)](https://pypistats.org/packages/types-aiobotocore-arc-zonal-shift)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ARCZonalShift 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift)
+[aiobotocore.ARCZonalShift 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift)
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
 [types-aiobotocore-arc-zonal-shift docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,27 +294,27 @@
 `types_aiobotocore_arc_zonal_shift.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_arc_zonal_shift.type_defs import (
     CancelZonalShiftRequestRequestTypeDef,
     GetManagedResourceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ZonalShiftInResourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListManagedResourcesRequestListManagedResourcesPaginateTypeDef,
     ListManagedResourcesRequestRequestTypeDef,
     ManagedResourceSummaryTypeDef,
+    ListZonalShiftsRequestListZonalShiftsPaginateTypeDef,
     ListZonalShiftsRequestRequestTypeDef,
     ZonalShiftSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartZonalShiftRequestRequestTypeDef,
     UpdateZonalShiftRequestRequestTypeDef,
     ZonalShiftTypeDef,
     GetManagedResourceResponseTypeDef,
-    ListManagedResourcesRequestListManagedResourcesPaginateTypeDef,
-    ListZonalShiftsRequestListZonalShiftsPaginateTypeDef,
     ListManagedResourcesResponseTypeDef,
     ListZonalShiftsResponseTypeDef,
 )
 
 
 def get_structure() -> CancelZonalShiftRequestRequestTypeDef:
     return {...}
@@ -323,43 +323,43 @@
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

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/setup.py` & `types-aiobotocore-arc-zonal-shift-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-arc-zonal-shift.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-arc-zonal-shift",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_arc_zonal_shift"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ARCZonalShift 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ARCZonalShift 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/"
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

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/__init__.py` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/__init__.pyi` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/__main__.py` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ARCZonalShift 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ARCZonalShift 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift\nOther"
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

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/client.py` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/client.pyi` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/literals.py` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/literals.py`

 * *Files 4% similar despite different names*

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
@@ -389,18 +398,35 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_managed_resources", "list_zonal_shifts"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-northeast-3",
+    "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
+    "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
+    "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
+    "eu-west-2",
+    "eu-west-3",
+    "me-central-1",
+    "me-south-1",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/literals.pyi` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/literals.pyi`

 * *Files 4% similar despite different names*

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
@@ -387,18 +396,35 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_managed_resources", "list_zonal_shifts"]
 RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
     "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-northeast-3",
+    "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
+    "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
+    "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
+    "eu-west-2",
+    "eu-west-3",
+    "me-central-1",
+    "me-south-1",
+    "sa-east-1",
     "us-east-1",
     "us-east-2",
+    "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/paginator.py` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/paginator.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -18,67 +18,59 @@
     with session.create_client("arc-zonal-shift") as client:
         client: ARCZonalShiftClient
 
         list_managed_resources_paginator: ListManagedResourcesPaginator = client.get_paginator("list_managed_resources")
         list_zonal_shifts_paginator: ListZonalShiftsPaginator = client.get_paginator("list_zonal_shifts")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ZonalShiftStatusType
 from .type_defs import (
     ListManagedResourcesResponseTypeDef,
     ListZonalShiftsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListManagedResourcesPaginator", "ListZonalShiftsPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListManagedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListManagedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listmanagedresourcespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListManagedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listmanagedresourcespaginator)
         """
 
-
 class ListZonalShiftsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListZonalShifts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listzonalshiftspaginator)
     """
 
     def paginate(
-        self, *, status: ZonalShiftStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        status: ZonalShiftStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListZonalShiftsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListZonalShifts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listzonalshiftspaginator)
         """
```

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/paginator.pyi` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -18,62 +18,63 @@
     with session.create_client("arc-zonal-shift") as client:
         client: ARCZonalShiftClient
 
         list_managed_resources_paginator: ListManagedResourcesPaginator = client.get_paginator("list_managed_resources")
         list_zonal_shifts_paginator: ListZonalShiftsPaginator = client.get_paginator("list_zonal_shifts")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ZonalShiftStatusType
 from .type_defs import (
     ListManagedResourcesResponseTypeDef,
     ListZonalShiftsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListManagedResourcesPaginator", "ListZonalShiftsPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListManagedResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListManagedResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listmanagedresourcespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListManagedResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listmanagedresourcespaginator)
         """
 
+
 class ListZonalShiftsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListZonalShifts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listzonalshiftspaginator)
     """
 
     def paginate(
-        self, *, status: ZonalShiftStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        status: ZonalShiftStatusType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListZonalShiftsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift.Paginator.ListZonalShifts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/paginators/#listzonalshiftspaginator)
         """
```

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/type_defs.py` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -22,27 +22,27 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelZonalShiftRequestRequestTypeDef",
     "GetManagedResourceRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ZonalShiftInResourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
     "ListManagedResourcesRequestRequestTypeDef",
     "ManagedResourceSummaryTypeDef",
+    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
     "ListZonalShiftsRequestRequestTypeDef",
     "ZonalShiftSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartZonalShiftRequestRequestTypeDef",
     "UpdateZonalShiftRequestRequestTypeDef",
     "ZonalShiftTypeDef",
     "GetManagedResourceResponseTypeDef",
-    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
-    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
     "ListManagedResourcesResponseTypeDef",
     "ListZonalShiftsResponseTypeDef",
 )
 
 CancelZonalShiftRequestRequestTypeDef = TypedDict(
     "CancelZonalShiftRequestRequestTypeDef",
     {
@@ -53,44 +53,31 @@
 GetManagedResourceRequestRequestTypeDef = TypedDict(
     "GetManagedResourceRequestRequestTypeDef",
     {
         "resourceIdentifier": str,
     },
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
 ZonalShiftInResourceTypeDef = TypedDict(
     "ZonalShiftInResourceTypeDef",
     {
         "appliedStatus": AppliedStatusType,
         "awayFrom": str,
         "comment": str,
         "expiryTime": datetime,
         "resourceIdentifier": str,
         "startTime": datetime,
         "zonalShiftId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListManagedResourcesRequestListManagedResourcesPaginateTypeDef = TypedDict(
+    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListManagedResourcesRequestRequestTypeDef = TypedDict(
     "ListManagedResourcesRequestRequestTypeDef",
     {
@@ -118,14 +105,23 @@
 
 class ManagedResourceSummaryTypeDef(
     _RequiredManagedResourceSummaryTypeDef, _OptionalManagedResourceSummaryTypeDef
 ):
     pass
 
 
+ListZonalShiftsRequestListZonalShiftsPaginateTypeDef = TypedDict(
+    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
+    {
+        "status": ZonalShiftStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListZonalShiftsRequestRequestTypeDef = TypedDict(
     "ListZonalShiftsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "status": ZonalShiftStatusType,
     },
@@ -141,14 +137,35 @@
         "resourceIdentifier": str,
         "startTime": datetime,
         "status": ZonalShiftStatusType,
         "zonalShiftId": str,
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
 StartZonalShiftRequestRequestTypeDef = TypedDict(
     "StartZonalShiftRequestRequestTypeDef",
     {
         "awayFrom": str,
         "comment": str,
         "expiresIn": str,
         "resourceIdentifier": str,
@@ -183,56 +200,39 @@
         "awayFrom": str,
         "comment": str,
         "expiryTime": datetime,
         "resourceIdentifier": str,
         "startTime": datetime,
         "status": ZonalShiftStatusType,
         "zonalShiftId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetManagedResourceResponseTypeDef = TypedDict(
     "GetManagedResourceResponseTypeDef",
     {
         "appliedWeights": Dict[str, float],
         "arn": str,
         "name": str,
         "zonalShifts": List[ZonalShiftInResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListManagedResourcesRequestListManagedResourcesPaginateTypeDef = TypedDict(
-    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListZonalShiftsRequestListZonalShiftsPaginateTypeDef = TypedDict(
-    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
-    {
-        "status": ZonalShiftStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListManagedResourcesResponseTypeDef = TypedDict(
     "ListManagedResourcesResponseTypeDef",
     {
         "items": List[ManagedResourceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListZonalShiftsResponseTypeDef = TypedDict(
     "ListZonalShiftsResponseTypeDef",
     {
         "items": List[ZonalShiftSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift/type_defs.pyi` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift/type_defs.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -21,27 +21,27 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelZonalShiftRequestRequestTypeDef",
     "GetManagedResourceRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ZonalShiftInResourceTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
     "ListManagedResourcesRequestRequestTypeDef",
     "ManagedResourceSummaryTypeDef",
+    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
     "ListZonalShiftsRequestRequestTypeDef",
     "ZonalShiftSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartZonalShiftRequestRequestTypeDef",
     "UpdateZonalShiftRequestRequestTypeDef",
     "ZonalShiftTypeDef",
     "GetManagedResourceResponseTypeDef",
-    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
-    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
     "ListManagedResourcesResponseTypeDef",
     "ListZonalShiftsResponseTypeDef",
 )
 
 CancelZonalShiftRequestRequestTypeDef = TypedDict(
     "CancelZonalShiftRequestRequestTypeDef",
     {
@@ -52,44 +52,31 @@
 GetManagedResourceRequestRequestTypeDef = TypedDict(
     "GetManagedResourceRequestRequestTypeDef",
     {
         "resourceIdentifier": str,
     },
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
 ZonalShiftInResourceTypeDef = TypedDict(
     "ZonalShiftInResourceTypeDef",
     {
         "appliedStatus": AppliedStatusType,
         "awayFrom": str,
         "comment": str,
         "expiryTime": datetime,
         "resourceIdentifier": str,
         "startTime": datetime,
         "zonalShiftId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListManagedResourcesRequestListManagedResourcesPaginateTypeDef = TypedDict(
+    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListManagedResourcesRequestRequestTypeDef = TypedDict(
     "ListManagedResourcesRequestRequestTypeDef",
     {
@@ -115,14 +102,23 @@
 )
 
 class ManagedResourceSummaryTypeDef(
     _RequiredManagedResourceSummaryTypeDef, _OptionalManagedResourceSummaryTypeDef
 ):
     pass
 
+ListZonalShiftsRequestListZonalShiftsPaginateTypeDef = TypedDict(
+    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
+    {
+        "status": ZonalShiftStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListZonalShiftsRequestRequestTypeDef = TypedDict(
     "ListZonalShiftsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "status": ZonalShiftStatusType,
     },
@@ -138,14 +134,35 @@
         "resourceIdentifier": str,
         "startTime": datetime,
         "status": ZonalShiftStatusType,
         "zonalShiftId": str,
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
 StartZonalShiftRequestRequestTypeDef = TypedDict(
     "StartZonalShiftRequestRequestTypeDef",
     {
         "awayFrom": str,
         "comment": str,
         "expiresIn": str,
         "resourceIdentifier": str,
@@ -178,56 +195,39 @@
         "awayFrom": str,
         "comment": str,
         "expiryTime": datetime,
         "resourceIdentifier": str,
         "startTime": datetime,
         "status": ZonalShiftStatusType,
         "zonalShiftId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetManagedResourceResponseTypeDef = TypedDict(
     "GetManagedResourceResponseTypeDef",
     {
         "appliedWeights": Dict[str, float],
         "arn": str,
         "name": str,
         "zonalShifts": List[ZonalShiftInResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListManagedResourcesRequestListManagedResourcesPaginateTypeDef = TypedDict(
-    "ListManagedResourcesRequestListManagedResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListZonalShiftsRequestListZonalShiftsPaginateTypeDef = TypedDict(
-    "ListZonalShiftsRequestListZonalShiftsPaginateTypeDef",
-    {
-        "status": ZonalShiftStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListManagedResourcesResponseTypeDef = TypedDict(
     "ListManagedResourcesResponseTypeDef",
     {
         "items": List[ManagedResourceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListZonalShiftsResponseTypeDef = TypedDict(
     "ListZonalShiftsResponseTypeDef",
     {
         "items": List[ZonalShiftSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/PKG-INFO` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-arc-zonal-shift
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ARCZonalShift 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ARCZonalShift 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-arc-zonal-shift"></a>
 
 # types-aiobotocore-arc-zonal-shift
 
 [![PyPI - types-aiobotocore-arc-zonal-shift](https://img.shields.io/pypi/v/types-aiobotocore-arc-zonal-shift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-arc-zonal-shift)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-arc-zonal-shift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-arc-zonal-shift)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-arc-zonal-shift?color=blue)](https://pypistats.org/packages/types-aiobotocore-arc-zonal-shift)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ARCZonalShift 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift)
+[aiobotocore.ARCZonalShift 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/arc-zonal-shift.html#ARCZonalShift)
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
 [types-aiobotocore-arc-zonal-shift docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_arc_zonal_shift/).
 
 See how it helps to find and fix potential bugs:
 
@@ -327,27 +327,27 @@
 `types_aiobotocore_arc_zonal_shift.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_arc_zonal_shift.type_defs import (
     CancelZonalShiftRequestRequestTypeDef,
     GetManagedResourceRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ZonalShiftInResourceTypeDef,
-    PaginatorConfigTypeDef,
+    ListManagedResourcesRequestListManagedResourcesPaginateTypeDef,
     ListManagedResourcesRequestRequestTypeDef,
     ManagedResourceSummaryTypeDef,
+    ListZonalShiftsRequestListZonalShiftsPaginateTypeDef,
     ListZonalShiftsRequestRequestTypeDef,
     ZonalShiftSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartZonalShiftRequestRequestTypeDef,
     UpdateZonalShiftRequestRequestTypeDef,
     ZonalShiftTypeDef,
     GetManagedResourceResponseTypeDef,
-    ListManagedResourcesRequestListManagedResourcesPaginateTypeDef,
-    ListZonalShiftsRequestListZonalShiftsPaginateTypeDef,
     ListManagedResourcesResponseTypeDef,
     ListZonalShiftsResponseTypeDef,
 )
 
 
 def get_structure() -> CancelZonalShiftRequestRequestTypeDef:
     return {...}
@@ -356,43 +356,43 @@
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

### Comparing `types-aiobotocore-arc-zonal-shift-2.5.0.post1/types_aiobotocore_arc_zonal_shift.egg-info/SOURCES.txt` & `types-aiobotocore-arc-zonal-shift-2.5.1/types_aiobotocore_arc_zonal_shift.egg-info/SOURCES.txt`

 * *Files identical despite different names*

