# Comparing `tmp/types-aiobotocore-autoscaling-plans-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-autoscaling-plans-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-autoscaling-plans-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-autoscaling-plans-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1.tar` & `types-aiobotocore-autoscaling-plans-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.066972 types-aiobotocore-autoscaling-plans-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15126 2023-03-11 12:26:15.066972 types-aiobotocore-autoscaling-plans-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13516 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.066972 types-aiobotocore-autoscaling-plans-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.058972 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/
--rw-r--r--   0 runner    (1001) docker     (123)     1049 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1048 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10272 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    10255 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10640 2023-03-11 12:10:02.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10638 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3886 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3881 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    14032 2023-03-11 12:10:02.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    14007 2023-03-11 12:10:02.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.066972 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15126 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.802098 types-aiobotocore-autoscaling-plans-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15128 2023-06-28 01:43:08.794098 types-aiobotocore-autoscaling-plans-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13524 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.802098 types-aiobotocore-autoscaling-plans-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2203 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.790098 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/
+-rw-r--r--   0 runner    (1001) docker     (123)     1049 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1048 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10272 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10255 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10849 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10847 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3770 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3766 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    14044 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14019 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:38.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.794098 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15128 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/LICENSE` & `types-aiobotocore-autoscaling-plans-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/PKG-INFO` & `types-aiobotocore-autoscaling-plans-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-autoscaling-plans
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AutoScalingPlans 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AutoScalingPlans 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-autoscaling-plans"></a>
 
 # types-aiobotocore-autoscaling-plans
 
 [![PyPI - types-aiobotocore-autoscaling-plans](https://img.shields.io/pypi/v/types-aiobotocore-autoscaling-plans.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling-plans)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-autoscaling-plans.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling-plans)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-autoscaling-plans?color=blue)](https://pypistats.org/packages/types-aiobotocore-autoscaling-plans)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AutoScalingPlans 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
+[aiobotocore.AutoScalingPlans 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
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
 [types-aiobotocore-autoscaling-plans docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/).
 
 See how it helps to find and fix potential bugs:
 
@@ -336,29 +336,29 @@
 
 `types_aiobotocore_autoscaling_plans.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_autoscaling_plans.type_defs import (
     TagFilterTypeDef,
-    ResponseMetadataTypeDef,
+    CreateScalingPlanResponseTypeDef,
     MetricDimensionTypeDef,
     DatapointTypeDef,
     DeleteScalingPlanRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
     DescribeScalingPlanResourcesRequestRequestTypeDef,
     GetScalingPlanResourceForecastDataRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedLoadMetricSpecificationTypeDef,
     PredefinedScalingMetricSpecificationTypeDef,
+    ResponseMetadataTypeDef,
     ApplicationSourceTypeDef,
-    CreateScalingPlanResponseTypeDef,
     CustomizedLoadMetricSpecificationTypeDef,
     CustomizedScalingMetricSpecificationTypeDef,
     GetScalingPlanResourceForecastDataResponseTypeDef,
-    DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
     DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef,
     DescribeScalingPlansRequestRequestTypeDef,
     TargetTrackingConfigurationTypeDef,
     ScalingInstructionTypeDef,
     ScalingPolicyTypeDef,
     CreateScalingPlanRequestRequestTypeDef,
     ScalingPlanTypeDef,
@@ -376,43 +376,43 @@
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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/README.md` & `types-aiobotocore-autoscaling-plans-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-autoscaling-plans"></a>
 
 # types-aiobotocore-autoscaling-plans
 
 [![PyPI - types-aiobotocore-autoscaling-plans](https://img.shields.io/pypi/v/types-aiobotocore-autoscaling-plans.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling-plans)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-autoscaling-plans.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling-plans)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-autoscaling-plans?color=blue)](https://pypistats.org/packages/types-aiobotocore-autoscaling-plans)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AutoScalingPlans 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
+[aiobotocore.AutoScalingPlans 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
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
 [types-aiobotocore-autoscaling-plans docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/).
 
 See how it helps to find and fix potential bugs:
 
@@ -303,29 +303,29 @@
 
 `types_aiobotocore_autoscaling_plans.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_autoscaling_plans.type_defs import (
     TagFilterTypeDef,
-    ResponseMetadataTypeDef,
+    CreateScalingPlanResponseTypeDef,
     MetricDimensionTypeDef,
     DatapointTypeDef,
     DeleteScalingPlanRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
     DescribeScalingPlanResourcesRequestRequestTypeDef,
     GetScalingPlanResourceForecastDataRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedLoadMetricSpecificationTypeDef,
     PredefinedScalingMetricSpecificationTypeDef,
+    ResponseMetadataTypeDef,
     ApplicationSourceTypeDef,
-    CreateScalingPlanResponseTypeDef,
     CustomizedLoadMetricSpecificationTypeDef,
     CustomizedScalingMetricSpecificationTypeDef,
     GetScalingPlanResourceForecastDataResponseTypeDef,
-    DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
     DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef,
     DescribeScalingPlansRequestRequestTypeDef,
     TargetTrackingConfigurationTypeDef,
     ScalingInstructionTypeDef,
     ScalingPolicyTypeDef,
     CreateScalingPlanRequestRequestTypeDef,
     ScalingPlanTypeDef,
@@ -343,43 +343,43 @@
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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/setup.py` & `types-aiobotocore-autoscaling-plans-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-autoscaling-plans.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-autoscaling-plans",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_autoscaling_plans"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AutoScalingPlans 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AutoScalingPlans 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/"
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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/__init__.py` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/__init__.pyi` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/__main__.py` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AutoScalingPlans 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AutoScalingPlans 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans\nOther"
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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/client.py` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/client.pyi` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/literals.py` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -158,14 +158,15 @@
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
@@ -244,14 +245,15 @@
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
@@ -262,14 +264,15 @@
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
@@ -305,14 +308,15 @@
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
@@ -331,16 +335,19 @@
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
@@ -424,15 +431,17 @@
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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/literals.pyi` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -156,14 +156,15 @@
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
@@ -242,14 +243,15 @@
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
@@ -260,14 +262,15 @@
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
@@ -303,14 +306,15 @@
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
@@ -329,16 +333,19 @@
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
@@ -422,15 +429,17 @@
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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/paginator.py` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -18,33 +18,26 @@
     with session.create_client("autoscaling-plans") as client:
         client: AutoScalingPlansClient
 
         describe_scaling_plan_resources_paginator: DescribeScalingPlanResourcesPaginator = client.get_paginator("describe_scaling_plan_resources")
         describe_scaling_plans_paginator: DescribeScalingPlansPaginator = client.get_paginator("describe_scaling_plans")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ApplicationSourceTypeDef,
     DescribeScalingPlanResourcesResponseTypeDef,
     DescribeScalingPlansResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeScalingPlanResourcesPaginator", "DescribeScalingPlansPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -61,15 +54,15 @@
     """
 
     def paginate(
         self,
         *,
         ScalingPlanName: str,
         ScalingPlanVersion: int,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPlanResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans.Paginator.DescribeScalingPlanResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/paginators/#describescalingplanresourcespaginator)
         """
 
 
@@ -81,13 +74,13 @@
 
     def paginate(
         self,
         *,
         ScalingPlanNames: Sequence[str] = ...,
         ScalingPlanVersion: int = ...,
         ApplicationSources: Sequence[ApplicationSourceTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPlansResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans.Paginator.DescribeScalingPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/paginators/#describescalingplanspaginator)
         """
```

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/paginator.pyi` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -18,32 +18,26 @@
     with session.create_client("autoscaling-plans") as client:
         client: AutoScalingPlansClient
 
         describe_scaling_plan_resources_paginator: DescribeScalingPlanResourcesPaginator = client.get_paginator("describe_scaling_plan_resources")
         describe_scaling_plans_paginator: DescribeScalingPlansPaginator = client.get_paginator("describe_scaling_plans")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ApplicationSourceTypeDef,
     DescribeScalingPlanResourcesResponseTypeDef,
     DescribeScalingPlansResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeScalingPlanResourcesPaginator", "DescribeScalingPlansPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -57,15 +51,15 @@
     """
 
     def paginate(
         self,
         *,
         ScalingPlanName: str,
         ScalingPlanVersion: int,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPlanResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans.Paginator.DescribeScalingPlanResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/paginators/#describescalingplanresourcespaginator)
         """
 
 class DescribeScalingPlansPaginator(AioPaginator):
@@ -76,13 +70,13 @@
 
     def paginate(
         self,
         *,
         ScalingPlanNames: Sequence[str] = ...,
         ScalingPlanVersion: int = ...,
         ApplicationSources: Sequence[ApplicationSourceTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPlansResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans.Paginator.DescribeScalingPlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/paginators/#describescalingplanspaginator)
         """
```

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/type_defs.py` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -37,29 +37,29 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "TagFilterTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateScalingPlanResponseTypeDef",
     "MetricDimensionTypeDef",
     "DatapointTypeDef",
     "DeleteScalingPlanRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
     "DescribeScalingPlanResourcesRequestRequestTypeDef",
     "GetScalingPlanResourceForecastDataRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PredefinedLoadMetricSpecificationTypeDef",
     "PredefinedScalingMetricSpecificationTypeDef",
+    "ResponseMetadataTypeDef",
     "ApplicationSourceTypeDef",
-    "CreateScalingPlanResponseTypeDef",
     "CustomizedLoadMetricSpecificationTypeDef",
     "CustomizedScalingMetricSpecificationTypeDef",
     "GetScalingPlanResourceForecastDataResponseTypeDef",
-    "DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
     "DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef",
     "DescribeScalingPlansRequestRequestTypeDef",
     "TargetTrackingConfigurationTypeDef",
     "ScalingInstructionTypeDef",
     "ScalingPolicyTypeDef",
     "CreateScalingPlanRequestRequestTypeDef",
     "ScalingPlanTypeDef",
@@ -74,22 +74,19 @@
     {
         "Key": str,
         "Values": Sequence[str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateScalingPlanResponseTypeDef = TypedDict(
+    "CreateScalingPlanResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScalingPlanVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricDimensionTypeDef = TypedDict(
     "MetricDimensionTypeDef",
     {
         "Name": str,
@@ -110,24 +107,37 @@
     "DeleteScalingPlanRequestRequestTypeDef",
     {
         "ScalingPlanName": str,
         "ScalingPlanVersion": int,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ScalingPlanName": str,
+        "ScalingPlanVersion": int,
+    },
+)
+_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef(
+    _RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
+    _OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeScalingPlanResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingPlanResourcesRequestRequestTypeDef",
     {
         "ScalingPlanName": str,
         "ScalingPlanVersion": int,
     },
 )
@@ -158,14 +168,24 @@
         "ScalableDimension": ScalableDimensionType,
         "ForecastDataType": ForecastDataTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
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
 _RequiredPredefinedLoadMetricSpecificationTypeDef = TypedDict(
     "_RequiredPredefinedLoadMetricSpecificationTypeDef",
     {
         "PredefinedLoadMetricType": LoadMetricTypeType,
     },
 )
 _OptionalPredefinedLoadMetricSpecificationTypeDef = TypedDict(
@@ -202,31 +222,34 @@
 class PredefinedScalingMetricSpecificationTypeDef(
     _RequiredPredefinedScalingMetricSpecificationTypeDef,
     _OptionalPredefinedScalingMetricSpecificationTypeDef,
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
+
 ApplicationSourceTypeDef = TypedDict(
     "ApplicationSourceTypeDef",
     {
         "CloudFormationStackARN": str,
         "TagFilters": Sequence[TagFilterTypeDef],
     },
     total=False,
 )
 
-CreateScalingPlanResponseTypeDef = TypedDict(
-    "CreateScalingPlanResponseTypeDef",
-    {
-        "ScalingPlanVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCustomizedLoadMetricSpecificationTypeDef = TypedDict(
     "_RequiredCustomizedLoadMetricSpecificationTypeDef",
     {
         "MetricName": str,
         "Namespace": str,
         "Statistic": MetricStatisticType,
     },
@@ -273,48 +296,25 @@
     pass
 
 
 GetScalingPlanResourceForecastDataResponseTypeDef = TypedDict(
     "GetScalingPlanResourceForecastDataResponseTypeDef",
     {
         "Datapoints": List[DatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
-    {
-        "ScalingPlanName": str,
-        "ScalingPlanVersion": int,
-    },
-)
-_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef(
-    _RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
-    _OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
-):
-    pass
-
-
 DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef = TypedDict(
     "DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef",
     {
         "ScalingPlanNames": Sequence[str],
         "ScalingPlanVersion": int,
         "ApplicationSources": Sequence[ApplicationSourceTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeScalingPlansRequestRequestTypeDef = TypedDict(
     "DescribeScalingPlansRequestRequestTypeDef",
     {
@@ -491,19 +491,19 @@
 
 
 DescribeScalingPlansResponseTypeDef = TypedDict(
     "DescribeScalingPlansResponseTypeDef",
     {
         "ScalingPlans": List[ScalingPlanTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScalingPlanResourcesResponseTypeDef = TypedDict(
     "DescribeScalingPlanResourcesResponseTypeDef",
     {
         "ScalingPlanResources": List[ScalingPlanResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans/type_defs.pyi` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -36,29 +36,29 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "TagFilterTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateScalingPlanResponseTypeDef",
     "MetricDimensionTypeDef",
     "DatapointTypeDef",
     "DeleteScalingPlanRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
     "DescribeScalingPlanResourcesRequestRequestTypeDef",
     "GetScalingPlanResourceForecastDataRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PredefinedLoadMetricSpecificationTypeDef",
     "PredefinedScalingMetricSpecificationTypeDef",
+    "ResponseMetadataTypeDef",
     "ApplicationSourceTypeDef",
-    "CreateScalingPlanResponseTypeDef",
     "CustomizedLoadMetricSpecificationTypeDef",
     "CustomizedScalingMetricSpecificationTypeDef",
     "GetScalingPlanResourceForecastDataResponseTypeDef",
-    "DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
     "DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef",
     "DescribeScalingPlansRequestRequestTypeDef",
     "TargetTrackingConfigurationTypeDef",
     "ScalingInstructionTypeDef",
     "ScalingPolicyTypeDef",
     "CreateScalingPlanRequestRequestTypeDef",
     "ScalingPlanTypeDef",
@@ -73,22 +73,19 @@
     {
         "Key": str,
         "Values": Sequence[str],
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateScalingPlanResponseTypeDef = TypedDict(
+    "CreateScalingPlanResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ScalingPlanVersion": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MetricDimensionTypeDef = TypedDict(
     "MetricDimensionTypeDef",
     {
         "Name": str,
@@ -109,24 +106,35 @@
     "DeleteScalingPlanRequestRequestTypeDef",
     {
         "ScalingPlanName": str,
         "ScalingPlanVersion": int,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ScalingPlanName": str,
+        "ScalingPlanVersion": int,
+    },
+)
+_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef(
+    _RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
+    _OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeScalingPlanResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingPlanResourcesRequestRequestTypeDef",
     {
         "ScalingPlanName": str,
         "ScalingPlanVersion": int,
     },
 )
@@ -155,14 +163,24 @@
         "ScalableDimension": ScalableDimensionType,
         "ForecastDataType": ForecastDataTypeType,
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
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
 _RequiredPredefinedLoadMetricSpecificationTypeDef = TypedDict(
     "_RequiredPredefinedLoadMetricSpecificationTypeDef",
     {
         "PredefinedLoadMetricType": LoadMetricTypeType,
     },
 )
 _OptionalPredefinedLoadMetricSpecificationTypeDef = TypedDict(
@@ -195,31 +213,34 @@
 
 class PredefinedScalingMetricSpecificationTypeDef(
     _RequiredPredefinedScalingMetricSpecificationTypeDef,
     _OptionalPredefinedScalingMetricSpecificationTypeDef,
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
+
 ApplicationSourceTypeDef = TypedDict(
     "ApplicationSourceTypeDef",
     {
         "CloudFormationStackARN": str,
         "TagFilters": Sequence[TagFilterTypeDef],
     },
     total=False,
 )
 
-CreateScalingPlanResponseTypeDef = TypedDict(
-    "CreateScalingPlanResponseTypeDef",
-    {
-        "ScalingPlanVersion": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCustomizedLoadMetricSpecificationTypeDef = TypedDict(
     "_RequiredCustomizedLoadMetricSpecificationTypeDef",
     {
         "MetricName": str,
         "Namespace": str,
         "Statistic": MetricStatisticType,
     },
@@ -262,46 +283,25 @@
 ):
     pass
 
 GetScalingPlanResourceForecastDataResponseTypeDef = TypedDict(
     "GetScalingPlanResourceForecastDataResponseTypeDef",
     {
         "Datapoints": List[DatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
-    {
-        "ScalingPlanName": str,
-        "ScalingPlanVersion": int,
-    },
-)
-_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef(
-    _RequiredDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
-    _OptionalDescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
-):
-    pass
-
 DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef = TypedDict(
     "DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef",
     {
         "ScalingPlanNames": Sequence[str],
         "ScalingPlanVersion": int,
         "ApplicationSources": Sequence[ApplicationSourceTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeScalingPlansRequestRequestTypeDef = TypedDict(
     "DescribeScalingPlansRequestRequestTypeDef",
     {
@@ -466,19 +466,19 @@
     pass
 
 DescribeScalingPlansResponseTypeDef = TypedDict(
     "DescribeScalingPlansResponseTypeDef",
     {
         "ScalingPlans": List[ScalingPlanTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScalingPlanResourcesResponseTypeDef = TypedDict(
     "DescribeScalingPlanResourcesResponseTypeDef",
     {
         "ScalingPlanResources": List[ScalingPlanResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/PKG-INFO` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-autoscaling-plans
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AutoScalingPlans 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AutoScalingPlans 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-autoscaling-plans"></a>
 
 # types-aiobotocore-autoscaling-plans
 
 [![PyPI - types-aiobotocore-autoscaling-plans](https://img.shields.io/pypi/v/types-aiobotocore-autoscaling-plans.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling-plans)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-autoscaling-plans.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling-plans)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-autoscaling-plans?color=blue)](https://pypistats.org/packages/types-aiobotocore-autoscaling-plans)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AutoScalingPlans 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
+[aiobotocore.AutoScalingPlans 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling-plans.html#AutoScalingPlans)
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
 [types-aiobotocore-autoscaling-plans docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling_plans/).
 
 See how it helps to find and fix potential bugs:
 
@@ -336,29 +336,29 @@
 
 `types_aiobotocore_autoscaling_plans.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_autoscaling_plans.type_defs import (
     TagFilterTypeDef,
-    ResponseMetadataTypeDef,
+    CreateScalingPlanResponseTypeDef,
     MetricDimensionTypeDef,
     DatapointTypeDef,
     DeleteScalingPlanRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
     DescribeScalingPlanResourcesRequestRequestTypeDef,
     GetScalingPlanResourceForecastDataRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedLoadMetricSpecificationTypeDef,
     PredefinedScalingMetricSpecificationTypeDef,
+    ResponseMetadataTypeDef,
     ApplicationSourceTypeDef,
-    CreateScalingPlanResponseTypeDef,
     CustomizedLoadMetricSpecificationTypeDef,
     CustomizedScalingMetricSpecificationTypeDef,
     GetScalingPlanResourceForecastDataResponseTypeDef,
-    DescribeScalingPlanResourcesRequestDescribeScalingPlanResourcesPaginateTypeDef,
     DescribeScalingPlansRequestDescribeScalingPlansPaginateTypeDef,
     DescribeScalingPlansRequestRequestTypeDef,
     TargetTrackingConfigurationTypeDef,
     ScalingInstructionTypeDef,
     ScalingPolicyTypeDef,
     CreateScalingPlanRequestRequestTypeDef,
     ScalingPlanTypeDef,
@@ -376,43 +376,43 @@
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

### Comparing `types-aiobotocore-autoscaling-plans-2.5.0.post1/types_aiobotocore_autoscaling_plans.egg-info/SOURCES.txt` & `types-aiobotocore-autoscaling-plans-2.5.1/types_aiobotocore_autoscaling_plans.egg-info/SOURCES.txt`

 * *Files identical despite different names*

