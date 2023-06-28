# Comparing `tmp/types-aiobotocore-pi-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-pi-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-pi-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:06 2023, max compression
+gzip compressed data, was "types-aiobotocore-pi-2.5.1.tar", last modified: Wed Jun 28 01:43:58 2023, max compression
```

## Comparing `types-aiobotocore-pi-2.5.0.post1.tar` & `types-aiobotocore-pi-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.351491 types-aiobotocore-pi-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12830 2023-03-11 12:27:06.351491 types-aiobotocore-pi-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11279 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:06.351491 types-aiobotocore-pi-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2054 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.351491 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/
--rw-r--r--   0 runner    (1001) docker     (123)      402 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      401 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      912 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8713 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8699 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8174 2023-03-11 12:19:46.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8172 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    10431 2023-03-11 12:19:46.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    10414 2023-03-11 12:19:46.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:45.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.351491 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12830 2023-03-11 12:27:06.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      649 2023-03-11 12:27:06.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:06.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-03-11 12:27:06.000000 types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.490191 types-aiobotocore-pi-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    12842 2023-06-28 01:43:58.490191 types-aiobotocore-pi-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11297 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.490191 types-aiobotocore-pi-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2048 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.490191 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/
+-rw-r--r--   0 runner    (1001) docker     (123)      402 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      401 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      900 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8786 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8772 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8466 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8464 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    10512 2023-06-28 01:36:33.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10495 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:32.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.490191 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12842 2023-06-28 01:43:58.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      649 2023-06-28 01:43:58.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:58.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 01:43:58.000000 types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-pi-2.5.0.post1/LICENSE` & `types-aiobotocore-pi-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-pi-2.5.0.post1/PKG-INFO` & `types-aiobotocore-pi-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pi
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PI 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PI 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pi"></a>
 
 # types-aiobotocore-pi
 
 [![PyPI - types-aiobotocore-pi](https://img.shields.io/pypi/v/types-aiobotocore-pi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pi)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pi)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pi?color=blue)](https://pypistats.org/packages/types-aiobotocore-pi)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PI 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI)
+[aiobotocore.PI 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI)
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
 [types-aiobotocore-pi docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,14 +269,15 @@
 `types_aiobotocore_pi.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_pi.literals import (
     DetailStatusType,
     FeatureStatusType,
+    PeriodAlignmentType,
     ServiceTypeType,
     PIServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -293,25 +294,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_pi.type_defs import (
     DataPointTypeDef,
     DimensionGroupTypeDef,
     DimensionKeyDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     ResponsePartitionKeyTypeDef,
     DimensionDetailTypeDef,
     DimensionKeyDetailTypeDef,
     FeatureMetadataTypeDef,
     GetDimensionKeyDetailsRequestRequestTypeDef,
     GetResourceMetadataRequestRequestTypeDef,
     ListAvailableResourceDimensionsRequestRequestTypeDef,
     ListAvailableResourceMetricsRequestRequestTypeDef,
     ResponseResourceMetricTypeDef,
     ResponseResourceMetricKeyTypeDef,
+    ResponseMetadataTypeDef,
     DescribeDimensionKeysRequestRequestTypeDef,
     MetricQueryTypeDef,
     DescribeDimensionKeysResponseTypeDef,
     DimensionGroupDetailTypeDef,
     GetDimensionKeyDetailsResponseTypeDef,
     GetResourceMetadataResponseTypeDef,
     ListAvailableResourceMetricsResponseTypeDef,
@@ -330,43 +331,43 @@
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

### Comparing `types-aiobotocore-pi-2.5.0.post1/README.md` & `types-aiobotocore-pi-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-pi"></a>
 
 # types-aiobotocore-pi
 
 [![PyPI - types-aiobotocore-pi](https://img.shields.io/pypi/v/types-aiobotocore-pi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pi)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pi)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pi?color=blue)](https://pypistats.org/packages/types-aiobotocore-pi)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PI 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI)
+[aiobotocore.PI 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI)
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
 [types-aiobotocore-pi docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/).
 
 See how it helps to find and fix potential bugs:
 
@@ -236,14 +236,15 @@
 `types_aiobotocore_pi.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_pi.literals import (
     DetailStatusType,
     FeatureStatusType,
+    PeriodAlignmentType,
     ServiceTypeType,
     PIServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -260,25 +261,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_pi.type_defs import (
     DataPointTypeDef,
     DimensionGroupTypeDef,
     DimensionKeyDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     ResponsePartitionKeyTypeDef,
     DimensionDetailTypeDef,
     DimensionKeyDetailTypeDef,
     FeatureMetadataTypeDef,
     GetDimensionKeyDetailsRequestRequestTypeDef,
     GetResourceMetadataRequestRequestTypeDef,
     ListAvailableResourceDimensionsRequestRequestTypeDef,
     ListAvailableResourceMetricsRequestRequestTypeDef,
     ResponseResourceMetricTypeDef,
     ResponseResourceMetricKeyTypeDef,
+    ResponseMetadataTypeDef,
     DescribeDimensionKeysRequestRequestTypeDef,
     MetricQueryTypeDef,
     DescribeDimensionKeysResponseTypeDef,
     DimensionGroupDetailTypeDef,
     GetDimensionKeyDetailsResponseTypeDef,
     GetResourceMetadataResponseTypeDef,
     ListAvailableResourceMetricsResponseTypeDef,
@@ -297,43 +298,43 @@
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

### Comparing `types-aiobotocore-pi-2.5.0.post1/setup.py` & `types-aiobotocore-pi-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,27 +1,27 @@
 """
 Setup script for types-aiobotocore-pi.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-pi",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_pi"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.PI 2.5.0 service generated with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.PI 2.5.1 service generated with mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -45,11 +45,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/",
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

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/__main__.py` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.PI 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.PI 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi//\nBoto3 docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI\nOther"
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

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/client.py` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 """
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import ServiceTypeType
+from .literals import PeriodAlignmentType, ServiceTypeType
 from .type_defs import (
     DescribeDimensionKeysResponseTypeDef,
     DimensionGroupTypeDef,
     GetDimensionKeyDetailsResponseTypeDef,
     GetResourceMetadataResponseTypeDef,
     GetResourceMetricsResponseTypeDef,
     ListAvailableResourceDimensionsResponseTypeDef,
@@ -153,15 +153,16 @@
         ServiceType: ServiceTypeType,
         Identifier: str,
         MetricQueries: Sequence[MetricQueryTypeDef],
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         PeriodInSeconds: int = ...,
         MaxResults: int = ...,
-        NextToken: str = ...
+        NextToken: str = ...,
+        PeriodAlignment: PeriodAlignmentType = ...
     ) -> GetResourceMetricsResponseTypeDef:
         """
         Retrieve Performance Insights metrics for a set of data sources over a time
         period.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI.Client.get_resource_metrics)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/client/#get_resource_metrics)
```

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/client.pyi` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 """
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import ServiceTypeType
+from .literals import PeriodAlignmentType, ServiceTypeType
 from .type_defs import (
     DescribeDimensionKeysResponseTypeDef,
     DimensionGroupTypeDef,
     GetDimensionKeyDetailsResponseTypeDef,
     GetResourceMetadataResponseTypeDef,
     GetResourceMetricsResponseTypeDef,
     ListAvailableResourceDimensionsResponseTypeDef,
@@ -143,15 +143,16 @@
         ServiceType: ServiceTypeType,
         Identifier: str,
         MetricQueries: Sequence[MetricQueryTypeDef],
         StartTime: Union[datetime, str],
         EndTime: Union[datetime, str],
         PeriodInSeconds: int = ...,
         MaxResults: int = ...,
-        NextToken: str = ...
+        NextToken: str = ...,
+        PeriodAlignment: PeriodAlignmentType = ...
     ) -> GetResourceMetricsResponseTypeDef:
         """
         Retrieve Performance Insights metrics for a set of data sources over a time
         period.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI.Client.get_resource_metrics)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/client/#get_resource_metrics)
```

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/literals.py` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -14,35 +14,35 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "DetailStatusType",
     "FeatureStatusType",
+    "PeriodAlignmentType",
     "ServiceTypeType",
     "PIServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 DetailStatusType = Literal["AVAILABLE", "PROCESSING", "UNAVAILABLE"]
 FeatureStatusType = Literal[
     "DISABLED",
     "DISABLED_PENDING_REBOOT",
     "ENABLED",
     "ENABLED_PENDING_REBOOT",
     "UNKNOWN",
     "UNSUPPORTED",
 ]
+PeriodAlignmentType = Literal["END_TIME", "START_TIME"]
 ServiceTypeType = Literal["DOCDB", "RDS"]
 PIServiceName = Literal["pi"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -99,14 +99,15 @@
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
@@ -185,14 +186,15 @@
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
@@ -203,14 +205,15 @@
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
@@ -246,14 +249,15 @@
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
@@ -272,16 +276,19 @@
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
@@ -365,15 +372,17 @@
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

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/literals.pyi` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -14,33 +14,37 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "DetailStatusType",
     "FeatureStatusType",
+    "PeriodAlignmentType",
     "ServiceTypeType",
     "PIServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 DetailStatusType = Literal["AVAILABLE", "PROCESSING", "UNAVAILABLE"]
 FeatureStatusType = Literal[
     "DISABLED",
     "DISABLED_PENDING_REBOOT",
     "ENABLED",
     "ENABLED_PENDING_REBOOT",
     "UNKNOWN",
     "UNSUPPORTED",
 ]
+PeriodAlignmentType = Literal["END_TIME", "START_TIME"]
 ServiceTypeType = Literal["DOCDB", "RDS"]
 PIServiceName = Literal["pi"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -97,14 +101,15 @@
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
@@ -183,14 +188,15 @@
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
@@ -201,14 +207,15 @@
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
@@ -244,14 +251,15 @@
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
@@ -270,16 +278,19 @@
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
@@ -363,15 +374,17 @@
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

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/type_defs.py` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -11,37 +11,36 @@
     data: DataPointTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
-from .literals import DetailStatusType, FeatureStatusType, ServiceTypeType
+from .literals import DetailStatusType, FeatureStatusType, PeriodAlignmentType, ServiceTypeType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "DataPointTypeDef",
     "DimensionGroupTypeDef",
     "DimensionKeyDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "ResponsePartitionKeyTypeDef",
     "DimensionDetailTypeDef",
     "DimensionKeyDetailTypeDef",
     "FeatureMetadataTypeDef",
     "GetDimensionKeyDetailsRequestRequestTypeDef",
     "GetResourceMetadataRequestRequestTypeDef",
     "ListAvailableResourceDimensionsRequestRequestTypeDef",
     "ListAvailableResourceMetricsRequestRequestTypeDef",
     "ResponseResourceMetricTypeDef",
     "ResponseResourceMetricKeyTypeDef",
+    "ResponseMetadataTypeDef",
     "DescribeDimensionKeysRequestRequestTypeDef",
     "MetricQueryTypeDef",
     "DescribeDimensionKeysResponseTypeDef",
     "DimensionGroupDetailTypeDef",
     "GetDimensionKeyDetailsResponseTypeDef",
     "GetResourceMetadataResponseTypeDef",
     "ListAvailableResourceMetricsResponseTypeDef",
@@ -71,41 +70,28 @@
     {
         "Dimensions": Sequence[str],
         "Limit": int,
     },
     total=False,
 )
 
-
 class DimensionGroupTypeDef(_RequiredDimensionGroupTypeDef, _OptionalDimensionGroupTypeDef):
     pass
 
-
 DimensionKeyDescriptionTypeDef = TypedDict(
     "DimensionKeyDescriptionTypeDef",
     {
         "Dimensions": Dict[str, str],
         "Total": float,
         "AdditionalMetrics": Dict[str, float],
         "Partitions": List[float],
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
 ResponsePartitionKeyTypeDef = TypedDict(
     "ResponsePartitionKeyTypeDef",
     {
         "Dimensions": Dict[str, str],
     },
 )
 
@@ -148,22 +134,20 @@
     "_OptionalGetDimensionKeyDetailsRequestRequestTypeDef",
     {
         "RequestedDimensions": Sequence[str],
     },
     total=False,
 )
 
-
 class GetDimensionKeyDetailsRequestRequestTypeDef(
     _RequiredGetDimensionKeyDetailsRequestRequestTypeDef,
     _OptionalGetDimensionKeyDetailsRequestRequestTypeDef,
 ):
     pass
 
-
 GetResourceMetadataRequestRequestTypeDef = TypedDict(
     "GetResourceMetadataRequestRequestTypeDef",
     {
         "ServiceType": ServiceTypeType,
         "Identifier": str,
     },
 )
@@ -181,22 +165,20 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListAvailableResourceDimensionsRequestRequestTypeDef(
     _RequiredListAvailableResourceDimensionsRequestRequestTypeDef,
     _OptionalListAvailableResourceDimensionsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListAvailableResourceMetricsRequestRequestTypeDef = TypedDict(
     "_RequiredListAvailableResourceMetricsRequestRequestTypeDef",
     {
         "ServiceType": ServiceTypeType,
         "Identifier": str,
         "MetricTypes": Sequence[str],
     },
@@ -206,22 +188,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListAvailableResourceMetricsRequestRequestTypeDef(
     _RequiredListAvailableResourceMetricsRequestRequestTypeDef,
     _OptionalListAvailableResourceMetricsRequestRequestTypeDef,
 ):
     pass
 
-
 ResponseResourceMetricTypeDef = TypedDict(
     "ResponseResourceMetricTypeDef",
     {
         "Metric": str,
         "Description": str,
         "Unit": str,
     },
@@ -238,20 +218,29 @@
     "_OptionalResponseResourceMetricKeyTypeDef",
     {
         "Dimensions": Dict[str, str],
     },
     total=False,
 )
 
-
 class ResponseResourceMetricKeyTypeDef(
     _RequiredResponseResourceMetricKeyTypeDef, _OptionalResponseResourceMetricKeyTypeDef
 ):
     pass
 
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
 
 _RequiredDescribeDimensionKeysRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDimensionKeysRequestRequestTypeDef",
     {
         "ServiceType": ServiceTypeType,
         "Identifier": str,
         "StartTime": Union[datetime, str],
@@ -269,22 +258,20 @@
         "Filter": Mapping[str, str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeDimensionKeysRequestRequestTypeDef(
     _RequiredDescribeDimensionKeysRequestRequestTypeDef,
     _OptionalDescribeDimensionKeysRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredMetricQueryTypeDef = TypedDict(
     "_RequiredMetricQueryTypeDef",
     {
         "Metric": str,
     },
 )
 _OptionalMetricQueryTypeDef = TypedDict(
@@ -292,28 +279,26 @@
     {
         "GroupBy": DimensionGroupTypeDef,
         "Filter": Mapping[str, str],
     },
     total=False,
 )
 
-
 class MetricQueryTypeDef(_RequiredMetricQueryTypeDef, _OptionalMetricQueryTypeDef):
     pass
 
-
 DescribeDimensionKeysResponseTypeDef = TypedDict(
     "DescribeDimensionKeysResponseTypeDef",
     {
         "AlignedStartTime": datetime,
         "AlignedEndTime": datetime,
         "PartitionKeys": List[ResponsePartitionKeyTypeDef],
         "Keys": List[DimensionKeyDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DimensionGroupDetailTypeDef = TypedDict(
     "DimensionGroupDetailTypeDef",
     {
         "Group": str,
@@ -322,33 +307,33 @@
     total=False,
 )
 
 GetDimensionKeyDetailsResponseTypeDef = TypedDict(
     "GetDimensionKeyDetailsResponseTypeDef",
     {
         "Dimensions": List[DimensionKeyDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceMetadataResponseTypeDef = TypedDict(
     "GetResourceMetadataResponseTypeDef",
     {
         "Identifier": str,
         "Features": Dict[str, FeatureMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableResourceMetricsResponseTypeDef = TypedDict(
     "ListAvailableResourceMetricsResponseTypeDef",
     {
         "Metrics": List[ResponseResourceMetricTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricKeyDataPointsTypeDef = TypedDict(
     "MetricKeyDataPointsTypeDef",
     {
         "Key": ResponseResourceMetricKeyTypeDef,
@@ -369,26 +354,25 @@
 )
 _OptionalGetResourceMetricsRequestRequestTypeDef = TypedDict(
     "_OptionalGetResourceMetricsRequestRequestTypeDef",
     {
         "PeriodInSeconds": int,
         "MaxResults": int,
         "NextToken": str,
+        "PeriodAlignment": PeriodAlignmentType,
     },
     total=False,
 )
 
-
 class GetResourceMetricsRequestRequestTypeDef(
     _RequiredGetResourceMetricsRequestRequestTypeDef,
     _OptionalGetResourceMetricsRequestRequestTypeDef,
 ):
     pass
 
-
 MetricDimensionGroupsTypeDef = TypedDict(
     "MetricDimensionGroupsTypeDef",
     {
         "Metric": str,
         "Groups": List[DimensionGroupDetailTypeDef],
     },
     total=False,
@@ -398,19 +382,19 @@
     "GetResourceMetricsResponseTypeDef",
     {
         "AlignedStartTime": datetime,
         "AlignedEndTime": datetime,
         "Identifier": str,
         "MetricList": List[MetricKeyDataPointsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableResourceDimensionsResponseTypeDef = TypedDict(
     "ListAvailableResourceDimensionsResponseTypeDef",
     {
         "MetricDimensions": List[MetricDimensionGroupsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi/type_defs.pyi` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -11,36 +11,37 @@
     data: DataPointTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
-from .literals import DetailStatusType, FeatureStatusType, ServiceTypeType
+from .literals import DetailStatusType, FeatureStatusType, PeriodAlignmentType, ServiceTypeType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "DataPointTypeDef",
     "DimensionGroupTypeDef",
     "DimensionKeyDescriptionTypeDef",
-    "ResponseMetadataTypeDef",
     "ResponsePartitionKeyTypeDef",
     "DimensionDetailTypeDef",
     "DimensionKeyDetailTypeDef",
     "FeatureMetadataTypeDef",
     "GetDimensionKeyDetailsRequestRequestTypeDef",
     "GetResourceMetadataRequestRequestTypeDef",
     "ListAvailableResourceDimensionsRequestRequestTypeDef",
     "ListAvailableResourceMetricsRequestRequestTypeDef",
     "ResponseResourceMetricTypeDef",
     "ResponseResourceMetricKeyTypeDef",
+    "ResponseMetadataTypeDef",
     "DescribeDimensionKeysRequestRequestTypeDef",
     "MetricQueryTypeDef",
     "DescribeDimensionKeysResponseTypeDef",
     "DimensionGroupDetailTypeDef",
     "GetDimensionKeyDetailsResponseTypeDef",
     "GetResourceMetadataResponseTypeDef",
     "ListAvailableResourceMetricsResponseTypeDef",
@@ -70,39 +71,30 @@
     {
         "Dimensions": Sequence[str],
         "Limit": int,
     },
     total=False,
 )
 
+
 class DimensionGroupTypeDef(_RequiredDimensionGroupTypeDef, _OptionalDimensionGroupTypeDef):
     pass
 
+
 DimensionKeyDescriptionTypeDef = TypedDict(
     "DimensionKeyDescriptionTypeDef",
     {
         "Dimensions": Dict[str, str],
         "Total": float,
         "AdditionalMetrics": Dict[str, float],
         "Partitions": List[float],
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
 ResponsePartitionKeyTypeDef = TypedDict(
     "ResponsePartitionKeyTypeDef",
     {
         "Dimensions": Dict[str, str],
     },
 )
 
@@ -145,20 +137,22 @@
     "_OptionalGetDimensionKeyDetailsRequestRequestTypeDef",
     {
         "RequestedDimensions": Sequence[str],
     },
     total=False,
 )
 
+
 class GetDimensionKeyDetailsRequestRequestTypeDef(
     _RequiredGetDimensionKeyDetailsRequestRequestTypeDef,
     _OptionalGetDimensionKeyDetailsRequestRequestTypeDef,
 ):
     pass
 
+
 GetResourceMetadataRequestRequestTypeDef = TypedDict(
     "GetResourceMetadataRequestRequestTypeDef",
     {
         "ServiceType": ServiceTypeType,
         "Identifier": str,
     },
 )
@@ -176,20 +170,22 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListAvailableResourceDimensionsRequestRequestTypeDef(
     _RequiredListAvailableResourceDimensionsRequestRequestTypeDef,
     _OptionalListAvailableResourceDimensionsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListAvailableResourceMetricsRequestRequestTypeDef = TypedDict(
     "_RequiredListAvailableResourceMetricsRequestRequestTypeDef",
     {
         "ServiceType": ServiceTypeType,
         "Identifier": str,
         "MetricTypes": Sequence[str],
     },
@@ -199,20 +195,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListAvailableResourceMetricsRequestRequestTypeDef(
     _RequiredListAvailableResourceMetricsRequestRequestTypeDef,
     _OptionalListAvailableResourceMetricsRequestRequestTypeDef,
 ):
     pass
 
+
 ResponseResourceMetricTypeDef = TypedDict(
     "ResponseResourceMetricTypeDef",
     {
         "Metric": str,
         "Description": str,
         "Unit": str,
     },
@@ -229,19 +227,32 @@
     "_OptionalResponseResourceMetricKeyTypeDef",
     {
         "Dimensions": Dict[str, str],
     },
     total=False,
 )
 
+
 class ResponseResourceMetricKeyTypeDef(
     _RequiredResponseResourceMetricKeyTypeDef, _OptionalResponseResourceMetricKeyTypeDef
 ):
     pass
 
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
 _RequiredDescribeDimensionKeysRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDimensionKeysRequestRequestTypeDef",
     {
         "ServiceType": ServiceTypeType,
         "Identifier": str,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
@@ -258,20 +269,22 @@
         "Filter": Mapping[str, str],
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeDimensionKeysRequestRequestTypeDef(
     _RequiredDescribeDimensionKeysRequestRequestTypeDef,
     _OptionalDescribeDimensionKeysRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredMetricQueryTypeDef = TypedDict(
     "_RequiredMetricQueryTypeDef",
     {
         "Metric": str,
     },
 )
 _OptionalMetricQueryTypeDef = TypedDict(
@@ -279,26 +292,28 @@
     {
         "GroupBy": DimensionGroupTypeDef,
         "Filter": Mapping[str, str],
     },
     total=False,
 )
 
+
 class MetricQueryTypeDef(_RequiredMetricQueryTypeDef, _OptionalMetricQueryTypeDef):
     pass
 
+
 DescribeDimensionKeysResponseTypeDef = TypedDict(
     "DescribeDimensionKeysResponseTypeDef",
     {
         "AlignedStartTime": datetime,
         "AlignedEndTime": datetime,
         "PartitionKeys": List[ResponsePartitionKeyTypeDef],
         "Keys": List[DimensionKeyDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DimensionGroupDetailTypeDef = TypedDict(
     "DimensionGroupDetailTypeDef",
     {
         "Group": str,
@@ -307,33 +322,33 @@
     total=False,
 )
 
 GetDimensionKeyDetailsResponseTypeDef = TypedDict(
     "GetDimensionKeyDetailsResponseTypeDef",
     {
         "Dimensions": List[DimensionKeyDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceMetadataResponseTypeDef = TypedDict(
     "GetResourceMetadataResponseTypeDef",
     {
         "Identifier": str,
         "Features": Dict[str, FeatureMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableResourceMetricsResponseTypeDef = TypedDict(
     "ListAvailableResourceMetricsResponseTypeDef",
     {
         "Metrics": List[ResponseResourceMetricTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricKeyDataPointsTypeDef = TypedDict(
     "MetricKeyDataPointsTypeDef",
     {
         "Key": ResponseResourceMetricKeyTypeDef,
@@ -354,24 +369,27 @@
 )
 _OptionalGetResourceMetricsRequestRequestTypeDef = TypedDict(
     "_OptionalGetResourceMetricsRequestRequestTypeDef",
     {
         "PeriodInSeconds": int,
         "MaxResults": int,
         "NextToken": str,
+        "PeriodAlignment": PeriodAlignmentType,
     },
     total=False,
 )
 
+
 class GetResourceMetricsRequestRequestTypeDef(
     _RequiredGetResourceMetricsRequestRequestTypeDef,
     _OptionalGetResourceMetricsRequestRequestTypeDef,
 ):
     pass
 
+
 MetricDimensionGroupsTypeDef = TypedDict(
     "MetricDimensionGroupsTypeDef",
     {
         "Metric": str,
         "Groups": List[DimensionGroupDetailTypeDef],
     },
     total=False,
@@ -381,19 +399,19 @@
     "GetResourceMetricsResponseTypeDef",
     {
         "AlignedStartTime": datetime,
         "AlignedEndTime": datetime,
         "Identifier": str,
         "MetricList": List[MetricKeyDataPointsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableResourceDimensionsResponseTypeDef = TypedDict(
     "ListAvailableResourceDimensionsResponseTypeDef",
     {
         "MetricDimensions": List[MetricDimensionGroupsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/PKG-INFO` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pi
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PI 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PI 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pi"></a>
 
 # types-aiobotocore-pi
 
 [![PyPI - types-aiobotocore-pi](https://img.shields.io/pypi/v/types-aiobotocore-pi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pi)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pi.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pi)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pi?color=blue)](https://pypistats.org/packages/types-aiobotocore-pi)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PI 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI)
+[aiobotocore.PI 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pi.html#PI)
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
 [types-aiobotocore-pi docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pi/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,14 +269,15 @@
 `types_aiobotocore_pi.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_pi.literals import (
     DetailStatusType,
     FeatureStatusType,
+    PeriodAlignmentType,
     ServiceTypeType,
     PIServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -293,25 +294,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_pi.type_defs import (
     DataPointTypeDef,
     DimensionGroupTypeDef,
     DimensionKeyDescriptionTypeDef,
-    ResponseMetadataTypeDef,
     ResponsePartitionKeyTypeDef,
     DimensionDetailTypeDef,
     DimensionKeyDetailTypeDef,
     FeatureMetadataTypeDef,
     GetDimensionKeyDetailsRequestRequestTypeDef,
     GetResourceMetadataRequestRequestTypeDef,
     ListAvailableResourceDimensionsRequestRequestTypeDef,
     ListAvailableResourceMetricsRequestRequestTypeDef,
     ResponseResourceMetricTypeDef,
     ResponseResourceMetricKeyTypeDef,
+    ResponseMetadataTypeDef,
     DescribeDimensionKeysRequestRequestTypeDef,
     MetricQueryTypeDef,
     DescribeDimensionKeysResponseTypeDef,
     DimensionGroupDetailTypeDef,
     GetDimensionKeyDetailsResponseTypeDef,
     GetResourceMetadataResponseTypeDef,
     ListAvailableResourceMetricsResponseTypeDef,
@@ -330,43 +331,43 @@
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

### Comparing `types-aiobotocore-pi-2.5.0.post1/types_aiobotocore_pi.egg-info/SOURCES.txt` & `types-aiobotocore-pi-2.5.1/types_aiobotocore_pi.egg-info/SOURCES.txt`

 * *Files identical despite different names*

