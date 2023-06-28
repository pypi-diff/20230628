# Comparing `tmp/types-aiobotocore-iot1click-projects-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iot1click-projects-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iot1click-projects-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:44 2023, max compression
+gzip compressed data, was "types-aiobotocore-iot1click-projects-2.5.1.tar", last modified: Wed Jun 28 01:43:36 2023, max compression
```

## Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1.tar` & `types-aiobotocore-iot1click-projects-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.623276 types-aiobotocore-iot1click-projects-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14838 2023-03-11 12:26:44.615276 types-aiobotocore-iot1click-projects-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13224 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:44.623276 types-aiobotocore-iot1click-projects-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2216 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.615276 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/
--rw-r--r--   0 runner    (1001) docker     (123)      900 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      899 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      985 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14748 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14721 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7829 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7827 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3362 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3357 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    10884 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    10867 2023-03-11 12:16:13.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.615276 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14838 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.342149 types-aiobotocore-iot1click-projects-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14841 2023-06-28 01:43:36.334149 types-aiobotocore-iot1click-projects-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13233 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:36.342149 types-aiobotocore-iot1click-projects-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.334149 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/
+-rw-r--r--   0 runner    (1001) docker     (123)      900 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      899 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      973 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14748 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14721 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8038 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8036 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3246 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3242 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    10900 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10883 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:51.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.334149 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14841 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1022 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/LICENSE` & `types-aiobotocore-iot1click-projects-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iot1click-projects-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-iot1click-projects
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoT1ClickProjects 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore iot1click-projects type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-iot1click-projects"></a>
 
 # types-aiobotocore-iot1click-projects
 
 [![PyPI - types-aiobotocore-iot1click-projects](https://img.shields.io/pypi/v/types-aiobotocore-iot1click-projects.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-projects)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot1click-projects.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-projects)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot1click-projects?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot1click-projects)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT1ClickProjects 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects)
+[aiobotocore.IoT1ClickProjects 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects)
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
 [types-aiobotocore-iot1click-projects docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,34 +292,34 @@
 from types_aiobotocore_iot1click_projects.type_defs import (
     AssociateDeviceWithPlacementRequestRequestTypeDef,
     CreatePlacementRequestRequestTypeDef,
     DeletePlacementRequestRequestTypeDef,
     DeleteProjectRequestRequestTypeDef,
     DescribePlacementRequestRequestTypeDef,
     PlacementDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     DescribeProjectRequestRequestTypeDef,
     DeviceTemplateTypeDef,
     DisassociateDeviceFromPlacementRequestRequestTypeDef,
     GetDevicesInPlacementRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDevicesInPlacementResponseTypeDef,
+    ListPlacementsRequestListPlacementsPaginateTypeDef,
     ListPlacementsRequestRequestTypeDef,
     PlacementSummaryTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePlacementRequestRequestTypeDef,
     DescribePlacementResponseTypeDef,
-    GetDevicesInPlacementResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     PlacementTemplateTypeDef,
-    ListPlacementsRequestListPlacementsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListPlacementsResponseTypeDef,
     ListProjectsResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
     ProjectDescriptionTypeDef,
     UpdateProjectRequestRequestTypeDef,
     DescribeProjectResponseTypeDef,
 )
@@ -365,43 +332,43 @@
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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/README.md` & `types-aiobotocore-iot1click-projects-2.5.1/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-iot1click-projects
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoT1ClickProjects 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore iot1click-projects type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-iot1click-projects"></a>
 
 # types-aiobotocore-iot1click-projects
 
 [![PyPI - types-aiobotocore-iot1click-projects](https://img.shields.io/pypi/v/types-aiobotocore-iot1click-projects.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-projects)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot1click-projects.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-projects)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot1click-projects?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot1click-projects)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT1ClickProjects 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects)
+[aiobotocore.IoT1ClickProjects 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects)
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
 [types-aiobotocore-iot1click-projects docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,34 +325,34 @@
 from types_aiobotocore_iot1click_projects.type_defs import (
     AssociateDeviceWithPlacementRequestRequestTypeDef,
     CreatePlacementRequestRequestTypeDef,
     DeletePlacementRequestRequestTypeDef,
     DeleteProjectRequestRequestTypeDef,
     DescribePlacementRequestRequestTypeDef,
     PlacementDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     DescribeProjectRequestRequestTypeDef,
     DeviceTemplateTypeDef,
     DisassociateDeviceFromPlacementRequestRequestTypeDef,
     GetDevicesInPlacementRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDevicesInPlacementResponseTypeDef,
+    ListPlacementsRequestListPlacementsPaginateTypeDef,
     ListPlacementsRequestRequestTypeDef,
     PlacementSummaryTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePlacementRequestRequestTypeDef,
     DescribePlacementResponseTypeDef,
-    GetDevicesInPlacementResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     PlacementTemplateTypeDef,
-    ListPlacementsRequestListPlacementsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListPlacementsResponseTypeDef,
     ListProjectsResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
     ProjectDescriptionTypeDef,
     UpdateProjectRequestRequestTypeDef,
     DescribeProjectResponseTypeDef,
 )
@@ -332,43 +365,43 @@
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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/setup.py` & `types-aiobotocore-iot1click-projects-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iot1click-projects.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iot1click-projects",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iot1click_projects"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoT1ClickProjects 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoT1ClickProjects 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/"
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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/__init__.py` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/__init__.pyi` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/__main__.py` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoT1ClickProjects 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoT1ClickProjects 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects\nOther"
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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/client.py` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/client.pyi` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/literals.py` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -91,14 +91,15 @@
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
@@ -177,14 +178,15 @@
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
@@ -195,14 +197,15 @@
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
@@ -238,14 +241,15 @@
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
@@ -264,16 +268,19 @@
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
@@ -357,15 +364,17 @@
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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/literals.pyi` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -89,14 +89,15 @@
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
@@ -175,14 +176,15 @@
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
@@ -193,14 +195,15 @@
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
@@ -236,14 +239,15 @@
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
@@ -262,16 +266,19 @@
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
@@ -355,15 +362,17 @@
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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/paginator.py` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -18,66 +18,55 @@
     with session.create_client("iot1click-projects") as client:
         client: IoT1ClickProjectsClient
 
         list_placements_paginator: ListPlacementsPaginator = client.get_paginator("list_placements")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListPlacementsResponseTypeDef,
     ListProjectsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListPlacementsPaginator", "ListProjectsPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListPlacementsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListPlacements)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listplacementspaginator)
     """
 
     def paginate(
-        self, *, projectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlacementsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListPlacements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listplacementspaginator)
         """
 
-
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listprojectspaginator)
         """
```

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/paginator.pyi` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,61 +18,59 @@
     with session.create_client("iot1click-projects") as client:
         client: IoT1ClickProjectsClient
 
         list_placements_paginator: ListPlacementsPaginator = client.get_paginator("list_placements")
         list_projects_paginator: ListProjectsPaginator = client.get_paginator("list_projects")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListPlacementsResponseTypeDef,
     ListProjectsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListPlacementsPaginator", "ListProjectsPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListPlacementsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListPlacements)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listplacementspaginator)
     """
 
     def paginate(
-        self, *, projectName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, projectName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlacementsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListPlacements.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listplacementspaginator)
         """
 
+
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/paginators/#listprojectspaginator)
         """
```

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/type_defs.py` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -16,42 +16,41 @@
 from typing import Dict, List, Mapping, Sequence
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AssociateDeviceWithPlacementRequestRequestTypeDef",
     "CreatePlacementRequestRequestTypeDef",
     "DeletePlacementRequestRequestTypeDef",
     "DeleteProjectRequestRequestTypeDef",
     "DescribePlacementRequestRequestTypeDef",
     "PlacementDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "DeviceTemplateTypeDef",
     "DisassociateDeviceFromPlacementRequestRequestTypeDef",
     "GetDevicesInPlacementRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetDevicesInPlacementResponseTypeDef",
+    "ListPlacementsRequestListPlacementsPaginateTypeDef",
     "ListPlacementsRequestRequestTypeDef",
     "PlacementSummaryTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdatePlacementRequestRequestTypeDef",
     "DescribePlacementResponseTypeDef",
-    "GetDevicesInPlacementResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "PlacementTemplateTypeDef",
-    "ListPlacementsRequestListPlacementsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListPlacementsResponseTypeDef",
     "ListProjectsResponseTypeDef",
     "CreateProjectRequestRequestTypeDef",
     "ProjectDescriptionTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "DescribeProjectResponseTypeDef",
 )
@@ -77,21 +76,19 @@
     "_OptionalCreatePlacementRequestRequestTypeDef",
     {
         "attributes": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreatePlacementRequestRequestTypeDef(
     _RequiredCreatePlacementRequestRequestTypeDef, _OptionalCreatePlacementRequestRequestTypeDef
 ):
     pass
 
-
 DeletePlacementRequestRequestTypeDef = TypedDict(
     "DeletePlacementRequestRequestTypeDef",
     {
         "placementName": str,
         "projectName": str,
     },
 )
@@ -118,25 +115,14 @@
         "placementName": str,
         "attributes": Dict[str, str],
         "createdDate": datetime,
         "updatedDate": datetime,
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
 DescribeProjectRequestRequestTypeDef = TypedDict(
     "DescribeProjectRequestRequestTypeDef",
     {
         "projectName": str,
     },
 )
 
@@ -162,24 +148,42 @@
     "GetDevicesInPlacementRequestRequestTypeDef",
     {
         "projectName": str,
         "placementName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetDevicesInPlacementResponseTypeDef = TypedDict(
+    "GetDevicesInPlacementResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "devices": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
+    "_RequiredListPlacementsRequestListPlacementsPaginateTypeDef",
+    {
+        "projectName": str,
+    },
+)
+_OptionalListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
+    "_OptionalListPlacementsRequestListPlacementsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListPlacementsRequestListPlacementsPaginateTypeDef(
+    _RequiredListPlacementsRequestListPlacementsPaginateTypeDef,
+    _OptionalListPlacementsRequestListPlacementsPaginateTypeDef,
+):
+    pass
+
 _RequiredListPlacementsRequestRequestTypeDef = TypedDict(
     "_RequiredListPlacementsRequestRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalListPlacementsRequestRequestTypeDef = TypedDict(
@@ -187,31 +191,37 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class ListPlacementsRequestRequestTypeDef(
     _RequiredListPlacementsRequestRequestTypeDef, _OptionalListPlacementsRequestRequestTypeDef
 ):
     pass
 
-
 PlacementSummaryTypeDef = TypedDict(
     "PlacementSummaryTypeDef",
     {
         "projectName": str,
         "placementName": str,
         "createdDate": datetime,
         "updatedDate": datetime,
     },
 )
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -230,26 +240,53 @@
     {
         "arn": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
-
 class ProjectSummaryTypeDef(_RequiredProjectSummaryTypeDef, _OptionalProjectSummaryTypeDef):
     pass
 
-
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -273,99 +310,51 @@
     "_OptionalUpdatePlacementRequestRequestTypeDef",
     {
         "attributes": Mapping[str, str],
     },
     total=False,
 )
 
-
 class UpdatePlacementRequestRequestTypeDef(
     _RequiredUpdatePlacementRequestRequestTypeDef, _OptionalUpdatePlacementRequestRequestTypeDef
 ):
     pass
 
-
 DescribePlacementResponseTypeDef = TypedDict(
     "DescribePlacementResponseTypeDef",
     {
         "placement": PlacementDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDevicesInPlacementResponseTypeDef = TypedDict(
-    "GetDevicesInPlacementResponseTypeDef",
-    {
-        "devices": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PlacementTemplateTypeDef = TypedDict(
     "PlacementTemplateTypeDef",
     {
         "defaultAttributes": Mapping[str, str],
         "deviceTemplates": Mapping[str, DeviceTemplateTypeDef],
     },
     total=False,
 )
 
-_RequiredListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
-    "_RequiredListPlacementsRequestListPlacementsPaginateTypeDef",
-    {
-        "projectName": str,
-    },
-)
-_OptionalListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
-    "_OptionalListPlacementsRequestListPlacementsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPlacementsRequestListPlacementsPaginateTypeDef(
-    _RequiredListPlacementsRequestListPlacementsPaginateTypeDef,
-    _OptionalListPlacementsRequestListPlacementsPaginateTypeDef,
-):
-    pass
-
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPlacementsResponseTypeDef = TypedDict(
     "ListPlacementsResponseTypeDef",
     {
         "placements": List[PlacementSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "projects": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProjectRequestRequestTypeDef",
     {
         "projectName": str,
@@ -377,21 +366,19 @@
         "description": str,
         "placementTemplate": PlacementTemplateTypeDef,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateProjectRequestRequestTypeDef(
     _RequiredCreateProjectRequestRequestTypeDef, _OptionalCreateProjectRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredProjectDescriptionTypeDef = TypedDict(
     "_RequiredProjectDescriptionTypeDef",
     {
         "projectName": str,
         "createdDate": datetime,
         "updatedDate": datetime,
     },
@@ -403,21 +390,19 @@
         "description": str,
         "placementTemplate": PlacementTemplateTypeDef,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
-
 class ProjectDescriptionTypeDef(
     _RequiredProjectDescriptionTypeDef, _OptionalProjectDescriptionTypeDef
 ):
     pass
 
-
 _RequiredUpdateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProjectRequestRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalUpdateProjectRequestRequestTypeDef = TypedDict(
@@ -425,21 +410,19 @@
     {
         "description": str,
         "placementTemplate": PlacementTemplateTypeDef,
     },
     total=False,
 )
 
-
 class UpdateProjectRequestRequestTypeDef(
     _RequiredUpdateProjectRequestRequestTypeDef, _OptionalUpdateProjectRequestRequestTypeDef
 ):
     pass
 
-
 DescribeProjectResponseTypeDef = TypedDict(
     "DescribeProjectResponseTypeDef",
     {
         "project": ProjectDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects/type_defs.pyi` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,41 +16,42 @@
 from typing import Dict, List, Mapping, Sequence
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AssociateDeviceWithPlacementRequestRequestTypeDef",
     "CreatePlacementRequestRequestTypeDef",
     "DeletePlacementRequestRequestTypeDef",
     "DeleteProjectRequestRequestTypeDef",
     "DescribePlacementRequestRequestTypeDef",
     "PlacementDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "DescribeProjectRequestRequestTypeDef",
     "DeviceTemplateTypeDef",
     "DisassociateDeviceFromPlacementRequestRequestTypeDef",
     "GetDevicesInPlacementRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetDevicesInPlacementResponseTypeDef",
+    "ListPlacementsRequestListPlacementsPaginateTypeDef",
     "ListPlacementsRequestRequestTypeDef",
     "PlacementSummaryTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
     "ProjectSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdatePlacementRequestRequestTypeDef",
     "DescribePlacementResponseTypeDef",
-    "GetDevicesInPlacementResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "PlacementTemplateTypeDef",
-    "ListPlacementsRequestListPlacementsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListPlacementsResponseTypeDef",
     "ListProjectsResponseTypeDef",
     "CreateProjectRequestRequestTypeDef",
     "ProjectDescriptionTypeDef",
     "UpdateProjectRequestRequestTypeDef",
     "DescribeProjectResponseTypeDef",
 )
@@ -76,19 +77,21 @@
     "_OptionalCreatePlacementRequestRequestTypeDef",
     {
         "attributes": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreatePlacementRequestRequestTypeDef(
     _RequiredCreatePlacementRequestRequestTypeDef, _OptionalCreatePlacementRequestRequestTypeDef
 ):
     pass
 
+
 DeletePlacementRequestRequestTypeDef = TypedDict(
     "DeletePlacementRequestRequestTypeDef",
     {
         "placementName": str,
         "projectName": str,
     },
 )
@@ -115,25 +118,14 @@
         "placementName": str,
         "attributes": Dict[str, str],
         "createdDate": datetime,
         "updatedDate": datetime,
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
 DescribeProjectRequestRequestTypeDef = TypedDict(
     "DescribeProjectRequestRequestTypeDef",
     {
         "projectName": str,
     },
 )
 
@@ -159,24 +151,44 @@
     "GetDevicesInPlacementRequestRequestTypeDef",
     {
         "projectName": str,
         "placementName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetDevicesInPlacementResponseTypeDef = TypedDict(
+    "GetDevicesInPlacementResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "devices": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
+    "_RequiredListPlacementsRequestListPlacementsPaginateTypeDef",
+    {
+        "projectName": str,
+    },
+)
+_OptionalListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
+    "_OptionalListPlacementsRequestListPlacementsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListPlacementsRequestListPlacementsPaginateTypeDef(
+    _RequiredListPlacementsRequestListPlacementsPaginateTypeDef,
+    _OptionalListPlacementsRequestListPlacementsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListPlacementsRequestRequestTypeDef = TypedDict(
     "_RequiredListPlacementsRequestRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalListPlacementsRequestRequestTypeDef = TypedDict(
@@ -184,29 +196,39 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class ListPlacementsRequestRequestTypeDef(
     _RequiredListPlacementsRequestRequestTypeDef, _OptionalListPlacementsRequestRequestTypeDef
 ):
     pass
 
+
 PlacementSummaryTypeDef = TypedDict(
     "PlacementSummaryTypeDef",
     {
         "projectName": str,
         "placementName": str,
         "createdDate": datetime,
         "updatedDate": datetime,
     },
 )
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -225,24 +247,55 @@
     {
         "arn": str,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+
 class ProjectSummaryTypeDef(_RequiredProjectSummaryTypeDef, _OptionalProjectSummaryTypeDef):
     pass
 
+
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -266,95 +319,53 @@
     "_OptionalUpdatePlacementRequestRequestTypeDef",
     {
         "attributes": Mapping[str, str],
     },
     total=False,
 )
 
+
 class UpdatePlacementRequestRequestTypeDef(
     _RequiredUpdatePlacementRequestRequestTypeDef, _OptionalUpdatePlacementRequestRequestTypeDef
 ):
     pass
 
+
 DescribePlacementResponseTypeDef = TypedDict(
     "DescribePlacementResponseTypeDef",
     {
         "placement": PlacementDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDevicesInPlacementResponseTypeDef = TypedDict(
-    "GetDevicesInPlacementResponseTypeDef",
-    {
-        "devices": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PlacementTemplateTypeDef = TypedDict(
     "PlacementTemplateTypeDef",
     {
         "defaultAttributes": Mapping[str, str],
         "deviceTemplates": Mapping[str, DeviceTemplateTypeDef],
     },
     total=False,
 )
 
-_RequiredListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
-    "_RequiredListPlacementsRequestListPlacementsPaginateTypeDef",
-    {
-        "projectName": str,
-    },
-)
-_OptionalListPlacementsRequestListPlacementsPaginateTypeDef = TypedDict(
-    "_OptionalListPlacementsRequestListPlacementsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPlacementsRequestListPlacementsPaginateTypeDef(
-    _RequiredListPlacementsRequestListPlacementsPaginateTypeDef,
-    _OptionalListPlacementsRequestListPlacementsPaginateTypeDef,
-):
-    pass
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPlacementsResponseTypeDef = TypedDict(
     "ListPlacementsResponseTypeDef",
     {
         "placements": List[PlacementSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResponseTypeDef = TypedDict(
     "ListProjectsResponseTypeDef",
     {
         "projects": List[ProjectSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProjectRequestRequestTypeDef",
     {
         "projectName": str,
@@ -366,19 +377,21 @@
         "description": str,
         "placementTemplate": PlacementTemplateTypeDef,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateProjectRequestRequestTypeDef(
     _RequiredCreateProjectRequestRequestTypeDef, _OptionalCreateProjectRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredProjectDescriptionTypeDef = TypedDict(
     "_RequiredProjectDescriptionTypeDef",
     {
         "projectName": str,
         "createdDate": datetime,
         "updatedDate": datetime,
     },
@@ -390,19 +403,21 @@
         "description": str,
         "placementTemplate": PlacementTemplateTypeDef,
         "tags": Dict[str, str],
     },
     total=False,
 )
 
+
 class ProjectDescriptionTypeDef(
     _RequiredProjectDescriptionTypeDef, _OptionalProjectDescriptionTypeDef
 ):
     pass
 
+
 _RequiredUpdateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateProjectRequestRequestTypeDef",
     {
         "projectName": str,
     },
 )
 _OptionalUpdateProjectRequestRequestTypeDef = TypedDict(
@@ -410,19 +425,21 @@
     {
         "description": str,
         "placementTemplate": PlacementTemplateTypeDef,
     },
     total=False,
 )
 
+
 class UpdateProjectRequestRequestTypeDef(
     _RequiredUpdateProjectRequestRequestTypeDef, _OptionalUpdateProjectRequestRequestTypeDef
 ):
     pass
 
+
 DescribeProjectResponseTypeDef = TypedDict(
     "DescribeProjectResponseTypeDef",
     {
         "project": ProjectDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/PKG-INFO` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot1click-projects
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoT1ClickProjects 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoT1ClickProjects 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot1click-projects"></a>
 
 # types-aiobotocore-iot1click-projects
 
 [![PyPI - types-aiobotocore-iot1click-projects](https://img.shields.io/pypi/v/types-aiobotocore-iot1click-projects.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-projects)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot1click-projects.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-projects)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot1click-projects?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot1click-projects)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT1ClickProjects 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects)
+[aiobotocore.IoT1ClickProjects 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-projects.html#IoT1ClickProjects)
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
 [types-aiobotocore-iot1click-projects docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_projects/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,34 +325,34 @@
 from types_aiobotocore_iot1click_projects.type_defs import (
     AssociateDeviceWithPlacementRequestRequestTypeDef,
     CreatePlacementRequestRequestTypeDef,
     DeletePlacementRequestRequestTypeDef,
     DeleteProjectRequestRequestTypeDef,
     DescribePlacementRequestRequestTypeDef,
     PlacementDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     DescribeProjectRequestRequestTypeDef,
     DeviceTemplateTypeDef,
     DisassociateDeviceFromPlacementRequestRequestTypeDef,
     GetDevicesInPlacementRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDevicesInPlacementResponseTypeDef,
+    ListPlacementsRequestListPlacementsPaginateTypeDef,
     ListPlacementsRequestRequestTypeDef,
     PlacementSummaryTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
     ProjectSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdatePlacementRequestRequestTypeDef,
     DescribePlacementResponseTypeDef,
-    GetDevicesInPlacementResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
     PlacementTemplateTypeDef,
-    ListPlacementsRequestListPlacementsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
     ListPlacementsResponseTypeDef,
     ListProjectsResponseTypeDef,
     CreateProjectRequestRequestTypeDef,
     ProjectDescriptionTypeDef,
     UpdateProjectRequestRequestTypeDef,
     DescribeProjectResponseTypeDef,
 )
@@ -365,43 +365,43 @@
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

### Comparing `types-aiobotocore-iot1click-projects-2.5.0.post1/types_aiobotocore_iot1click_projects.egg-info/SOURCES.txt` & `types-aiobotocore-iot1click-projects-2.5.1/types_aiobotocore_iot1click_projects.egg-info/SOURCES.txt`

 * *Files identical despite different names*

