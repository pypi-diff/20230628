# Comparing `tmp/types-aiobotocore-application-autoscaling-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-application-autoscaling-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-application-autoscaling-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-application-autoscaling-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1.tar` & `types-aiobotocore-application-autoscaling-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.690947 types-aiobotocore-application-autoscaling-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16111 2023-03-11 12:26:12.686947 types-aiobotocore-application-autoscaling-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14477 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.690947 types-aiobotocore-application-autoscaling-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2238 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.682947 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/
--rw-r--r--   0 runner    (1001) docker     (123)     1606 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1605 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1005 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15895 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15872 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11416 2023-03-11 12:09:36.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11414 2023-03-11 12:09:36.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7086 2023-03-11 12:09:36.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7079 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    20209 2023-03-11 12:09:36.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20168 2023-03-11 12:09:36.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:35.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.686947 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16111 2023-03-11 12:26:12.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-03-11 12:26:12.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       42 2023-03-11 12:26:12.000000 types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.442094 types-aiobotocore-application-autoscaling-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16480 2023-06-28 01:43:06.438094 types-aiobotocore-application-autoscaling-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14852 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.442094 types-aiobotocore-application-autoscaling-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2232 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.430094 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/
+-rw-r--r--   0 runner    (1001) docker     (123)     1606 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1605 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      993 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17845 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17819 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11802 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11800 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6974 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6968 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    22761 2023-06-28 01:26:13.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22718 2023-06-28 01:26:13.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:12.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.438094 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16480 2023-06-28 01:43:06.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1117 2023-06-28 01:43:06.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       42 2023-06-28 01:43:06.000000 types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/LICENSE` & `types-aiobotocore-application-autoscaling-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/PKG-INFO` & `types-aiobotocore-application-autoscaling-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-application-autoscaling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationAutoScaling 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationAutoScaling 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-application-autoscaling"></a>
 
 # types-aiobotocore-application-autoscaling
 
 [![PyPI - types-aiobotocore-application-autoscaling](https://img.shields.io/pypi/v/types-aiobotocore-application-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-autoscaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-application-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-autoscaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-application-autoscaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-application-autoscaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationAutoScaling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
+[aiobotocore.ApplicationAutoScaling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
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
 [types-aiobotocore-application-autoscaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -347,41 +347,50 @@
 ```python
 from types_aiobotocore_application_autoscaling.type_defs import (
     AlarmTypeDef,
     MetricDimensionTypeDef,
     DeleteScalingPolicyRequestRequestTypeDef,
     DeleteScheduledActionRequestRequestTypeDef,
     DeregisterScalableTargetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
     DescribeScalableTargetsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
     DescribeScalingActivitiesRequestRequestTypeDef,
+    DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
     DescribeScalingPoliciesRequestRequestTypeDef,
+    DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
     DescribeScheduledActionsRequestRequestTypeDef,
+    ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NotScaledReasonTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedMetricSpecificationTypeDef,
     ScalableTargetActionTypeDef,
     SuspendedStateTypeDef,
+    RegisterScalableTargetResponseTypeDef,
+    ResponseMetadataTypeDef,
     StepAdjustmentTypeDef,
-    CustomizedMetricSpecificationTypeDef,
-    DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
-    DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
-    DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
-    DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
+    TagResourceRequestRequestTypeDef,
+    TargetTrackingMetricDimensionTypeDef,
+    UntagResourceRequestRequestTypeDef,
     PutScalingPolicyResponseTypeDef,
     ScalingActivityTypeDef,
     PutScheduledActionRequestRequestTypeDef,
     ScheduledActionTypeDef,
     RegisterScalableTargetRequestRequestTypeDef,
     ScalableTargetTypeDef,
     StepScalingPolicyConfigurationTypeDef,
-    TargetTrackingScalingPolicyConfigurationTypeDef,
+    TargetTrackingMetricTypeDef,
     DescribeScalingActivitiesResponseTypeDef,
     DescribeScheduledActionsResponseTypeDef,
     DescribeScalableTargetsResponseTypeDef,
+    TargetTrackingMetricStatTypeDef,
+    TargetTrackingMetricDataQueryTypeDef,
+    CustomizedMetricSpecificationTypeDef,
+    TargetTrackingScalingPolicyConfigurationTypeDef,
     PutScalingPolicyRequestRequestTypeDef,
     ScalingPolicyTypeDef,
     DescribeScalingPoliciesResponseTypeDef,
 )
 
 
 def get_structure() -> AlarmTypeDef:
@@ -391,43 +400,43 @@
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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/README.md` & `types-aiobotocore-application-autoscaling-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-application-autoscaling"></a>
 
 # types-aiobotocore-application-autoscaling
 
 [![PyPI - types-aiobotocore-application-autoscaling](https://img.shields.io/pypi/v/types-aiobotocore-application-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-autoscaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-application-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-autoscaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-application-autoscaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-application-autoscaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationAutoScaling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
+[aiobotocore.ApplicationAutoScaling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
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
 [types-aiobotocore-application-autoscaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -314,41 +314,50 @@
 ```python
 from types_aiobotocore_application_autoscaling.type_defs import (
     AlarmTypeDef,
     MetricDimensionTypeDef,
     DeleteScalingPolicyRequestRequestTypeDef,
     DeleteScheduledActionRequestRequestTypeDef,
     DeregisterScalableTargetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
     DescribeScalableTargetsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
     DescribeScalingActivitiesRequestRequestTypeDef,
+    DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
     DescribeScalingPoliciesRequestRequestTypeDef,
+    DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
     DescribeScheduledActionsRequestRequestTypeDef,
+    ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NotScaledReasonTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedMetricSpecificationTypeDef,
     ScalableTargetActionTypeDef,
     SuspendedStateTypeDef,
+    RegisterScalableTargetResponseTypeDef,
+    ResponseMetadataTypeDef,
     StepAdjustmentTypeDef,
-    CustomizedMetricSpecificationTypeDef,
-    DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
-    DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
-    DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
-    DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
+    TagResourceRequestRequestTypeDef,
+    TargetTrackingMetricDimensionTypeDef,
+    UntagResourceRequestRequestTypeDef,
     PutScalingPolicyResponseTypeDef,
     ScalingActivityTypeDef,
     PutScheduledActionRequestRequestTypeDef,
     ScheduledActionTypeDef,
     RegisterScalableTargetRequestRequestTypeDef,
     ScalableTargetTypeDef,
     StepScalingPolicyConfigurationTypeDef,
-    TargetTrackingScalingPolicyConfigurationTypeDef,
+    TargetTrackingMetricTypeDef,
     DescribeScalingActivitiesResponseTypeDef,
     DescribeScheduledActionsResponseTypeDef,
     DescribeScalableTargetsResponseTypeDef,
+    TargetTrackingMetricStatTypeDef,
+    TargetTrackingMetricDataQueryTypeDef,
+    CustomizedMetricSpecificationTypeDef,
+    TargetTrackingScalingPolicyConfigurationTypeDef,
     PutScalingPolicyRequestRequestTypeDef,
     ScalingPolicyTypeDef,
     DescribeScalingPoliciesResponseTypeDef,
 )
 
 
 def get_structure() -> AlarmTypeDef:
@@ -358,43 +367,43 @@
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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/setup.py` & `types-aiobotocore-application-autoscaling-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-application-autoscaling.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-application-autoscaling",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_application_autoscaling"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ApplicationAutoScaling 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ApplicationAutoScaling 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -49,11 +49,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/",
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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/__init__.py` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/__init__.pyi` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/__main__.py` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/__main__.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ApplicationAutoScaling 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ApplicationAutoScaling 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling\nOther"
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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/client.py` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/client.py`

 * *Files 8% similar despite different names*

```diff
@@ -29,15 +29,17 @@
     DescribeScheduledActionsPaginator,
 )
 from .type_defs import (
     DescribeScalableTargetsResponseTypeDef,
     DescribeScalingActivitiesResponseTypeDef,
     DescribeScalingPoliciesResponseTypeDef,
     DescribeScheduledActionsResponseTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PutScalingPolicyResponseTypeDef,
+    RegisterScalableTargetResponseTypeDef,
     ScalableTargetActionTypeDef,
     StepScalingPolicyConfigurationTypeDef,
     SuspendedStateTypeDef,
     TargetTrackingScalingPolicyConfigurationTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -61,14 +63,16 @@
     ClientError: Type[BotocoreClientError]
     ConcurrentUpdateException: Type[BotocoreClientError]
     FailedResourceAccessException: Type[BotocoreClientError]
     InternalServiceException: Type[BotocoreClientError]
     InvalidNextTokenException: Type[BotocoreClientError]
     LimitExceededException: Type[BotocoreClientError]
     ObjectNotFoundException: Type[BotocoreClientError]
+    ResourceNotFoundException: Type[BotocoreClientError]
+    TooManyTagsException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 
 class ApplicationAutoScalingClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/)
@@ -228,14 +232,24 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#generate_presigned_url)
         """
 
+    async def list_tags_for_resource(
+        self, *, ResourceARN: str
+    ) -> ListTagsForResourceResponseTypeDef:
+        """
+        Returns all the tags on the specified Application Auto Scaling scalable target.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.list_tags_for_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#list_tags_for_resource)
+        """
+
     async def put_scaling_policy(
         self,
         *,
         PolicyName: str,
         ServiceNamespace: ServiceNamespaceType,
         ResourceId: str,
         ScalableDimension: ScalableDimensionType,
@@ -277,23 +291,41 @@
         *,
         ServiceNamespace: ServiceNamespaceType,
         ResourceId: str,
         ScalableDimension: ScalableDimensionType,
         MinCapacity: int = ...,
         MaxCapacity: int = ...,
         RoleARN: str = ...,
-        SuspendedState: SuspendedStateTypeDef = ...
-    ) -> Dict[str, Any]:
+        SuspendedState: SuspendedStateTypeDef = ...,
+        Tags: Mapping[str, str] = ...
+    ) -> RegisterScalableTargetResponseTypeDef:
         """
-        Registers or updates a scalable target, the resource that you want to scale.
+        Registers or updates a scalable target, which is the resource that you want to
+        scale.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.register_scalable_target)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#register_scalable_target)
         """
 
+    async def tag_resource(self, *, ResourceARN: str, Tags: Mapping[str, str]) -> Dict[str, Any]:
+        """
+        Adds or edits tags on an Application Auto Scaling scalable target.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.tag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#tag_resource)
+        """
+
+    async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
+        """
+        Deletes tags from an Application Auto Scaling scalable target.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.untag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#untag_resource)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["describe_scalable_targets"]
     ) -> DescribeScalableTargetsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#get_paginator)
```

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/client.pyi` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/client.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -29,15 +29,17 @@
     DescribeScheduledActionsPaginator,
 )
 from .type_defs import (
     DescribeScalableTargetsResponseTypeDef,
     DescribeScalingActivitiesResponseTypeDef,
     DescribeScalingPoliciesResponseTypeDef,
     DescribeScheduledActionsResponseTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PutScalingPolicyResponseTypeDef,
+    RegisterScalableTargetResponseTypeDef,
     ScalableTargetActionTypeDef,
     StepScalingPolicyConfigurationTypeDef,
     SuspendedStateTypeDef,
     TargetTrackingScalingPolicyConfigurationTypeDef,
 )
 
 if sys.version_info >= (3, 9):
@@ -58,14 +60,16 @@
     ClientError: Type[BotocoreClientError]
     ConcurrentUpdateException: Type[BotocoreClientError]
     FailedResourceAccessException: Type[BotocoreClientError]
     InternalServiceException: Type[BotocoreClientError]
     InvalidNextTokenException: Type[BotocoreClientError]
     LimitExceededException: Type[BotocoreClientError]
     ObjectNotFoundException: Type[BotocoreClientError]
+    ResourceNotFoundException: Type[BotocoreClientError]
+    TooManyTagsException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 class ApplicationAutoScalingClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/)
     """
@@ -213,14 +217,23 @@
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#generate_presigned_url)
         """
+    async def list_tags_for_resource(
+        self, *, ResourceARN: str
+    ) -> ListTagsForResourceResponseTypeDef:
+        """
+        Returns all the tags on the specified Application Auto Scaling scalable target.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.list_tags_for_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#list_tags_for_resource)
+        """
     async def put_scaling_policy(
         self,
         *,
         PolicyName: str,
         ServiceNamespace: ServiceNamespaceType,
         ResourceId: str,
         ScalableDimension: ScalableDimensionType,
@@ -260,22 +273,38 @@
         *,
         ServiceNamespace: ServiceNamespaceType,
         ResourceId: str,
         ScalableDimension: ScalableDimensionType,
         MinCapacity: int = ...,
         MaxCapacity: int = ...,
         RoleARN: str = ...,
-        SuspendedState: SuspendedStateTypeDef = ...
-    ) -> Dict[str, Any]:
+        SuspendedState: SuspendedStateTypeDef = ...,
+        Tags: Mapping[str, str] = ...
+    ) -> RegisterScalableTargetResponseTypeDef:
         """
-        Registers or updates a scalable target, the resource that you want to scale.
+        Registers or updates a scalable target, which is the resource that you want to
+        scale.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.register_scalable_target)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#register_scalable_target)
         """
+    async def tag_resource(self, *, ResourceARN: str, Tags: Mapping[str, str]) -> Dict[str, Any]:
+        """
+        Adds or edits tags on an Application Auto Scaling scalable target.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.tag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#tag_resource)
+        """
+    async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
+        """
+        Deletes tags from an Application Auto Scaling scalable target.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.untag_resource)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#untag_resource)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["describe_scalable_targets"]
     ) -> DescribeScalableTargetsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/client/#get_paginator)
```

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/literals.py` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/literals.py`

 * *Files 8% similar despite different names*

```diff
@@ -56,23 +56,25 @@
     "DynamoDBReadCapacityUtilization",
     "DynamoDBWriteCapacityUtilization",
     "EC2SpotFleetRequestAverageCPUUtilization",
     "EC2SpotFleetRequestAverageNetworkIn",
     "EC2SpotFleetRequestAverageNetworkOut",
     "ECSServiceAverageCPUUtilization",
     "ECSServiceAverageMemoryUtilization",
+    "ElastiCacheDatabaseCapacityUsageCountedForEvictPercentage",
     "ElastiCacheDatabaseMemoryUsageCountedForEvictPercentage",
     "ElastiCachePrimaryEngineCPUUtilization",
     "ElastiCacheReplicaEngineCPUUtilization",
     "KafkaBrokerStorageUtilization",
     "LambdaProvisionedConcurrencyUtilization",
     "NeptuneReaderAverageCPUUtilization",
     "RDSReaderAverageCPUUtilization",
     "RDSReaderAverageDatabaseConnections",
     "SageMakerVariantInvocationsPerInstance",
+    "SageMakerVariantProvisionedConcurrencyUtilization",
 ]
 PolicyTypeType = Literal["StepScaling", "TargetTrackingScaling"]
 ScalableDimensionType = Literal[
     "appstream:fleet:DesiredCapacity",
     "cassandra:table:ReadCapacityUnits",
     "cassandra:table:WriteCapacityUnits",
     "comprehend:document-classifier-endpoint:DesiredInferenceUnits",
@@ -88,14 +90,15 @@
     "elasticache:replication-group:Replicas",
     "elasticmapreduce:instancegroup:InstanceCount",
     "kafka:broker-storage:VolumeSize",
     "lambda:function:ProvisionedConcurrency",
     "neptune:cluster:ReadReplicaCount",
     "rds:cluster:ReadReplicaCount",
     "sagemaker:variant:DesiredInstanceCount",
+    "sagemaker:variant:DesiredProvisionedConcurrency",
 ]
 ScalingActivityStatusCodeType = Literal[
     "Failed", "InProgress", "Overridden", "Pending", "Successful", "Unfulfilled"
 ]
 ServiceNamespaceType = Literal[
     "appstream",
     "cassandra",
@@ -171,14 +174,15 @@
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
@@ -257,14 +261,15 @@
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
@@ -275,14 +280,15 @@
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
@@ -318,14 +324,15 @@
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
@@ -344,16 +351,19 @@
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
@@ -437,15 +447,17 @@
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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/literals.pyi` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/literals.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -54,23 +54,25 @@
     "DynamoDBReadCapacityUtilization",
     "DynamoDBWriteCapacityUtilization",
     "EC2SpotFleetRequestAverageCPUUtilization",
     "EC2SpotFleetRequestAverageNetworkIn",
     "EC2SpotFleetRequestAverageNetworkOut",
     "ECSServiceAverageCPUUtilization",
     "ECSServiceAverageMemoryUtilization",
+    "ElastiCacheDatabaseCapacityUsageCountedForEvictPercentage",
     "ElastiCacheDatabaseMemoryUsageCountedForEvictPercentage",
     "ElastiCachePrimaryEngineCPUUtilization",
     "ElastiCacheReplicaEngineCPUUtilization",
     "KafkaBrokerStorageUtilization",
     "LambdaProvisionedConcurrencyUtilization",
     "NeptuneReaderAverageCPUUtilization",
     "RDSReaderAverageCPUUtilization",
     "RDSReaderAverageDatabaseConnections",
     "SageMakerVariantInvocationsPerInstance",
+    "SageMakerVariantProvisionedConcurrencyUtilization",
 ]
 PolicyTypeType = Literal["StepScaling", "TargetTrackingScaling"]
 ScalableDimensionType = Literal[
     "appstream:fleet:DesiredCapacity",
     "cassandra:table:ReadCapacityUnits",
     "cassandra:table:WriteCapacityUnits",
     "comprehend:document-classifier-endpoint:DesiredInferenceUnits",
@@ -86,14 +88,15 @@
     "elasticache:replication-group:Replicas",
     "elasticmapreduce:instancegroup:InstanceCount",
     "kafka:broker-storage:VolumeSize",
     "lambda:function:ProvisionedConcurrency",
     "neptune:cluster:ReadReplicaCount",
     "rds:cluster:ReadReplicaCount",
     "sagemaker:variant:DesiredInstanceCount",
+    "sagemaker:variant:DesiredProvisionedConcurrency",
 ]
 ScalingActivityStatusCodeType = Literal[
     "Failed", "InProgress", "Overridden", "Pending", "Successful", "Unfulfilled"
 ]
 ServiceNamespaceType = Literal[
     "appstream",
     "cassandra",
@@ -169,14 +172,15 @@
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
@@ -255,14 +259,15 @@
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
@@ -273,14 +278,15 @@
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
@@ -316,14 +322,15 @@
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
@@ -342,16 +349,19 @@
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
@@ -435,15 +445,17 @@
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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/paginator.py` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,35 +22,28 @@
 
         describe_scalable_targets_paginator: DescribeScalableTargetsPaginator = client.get_paginator("describe_scalable_targets")
         describe_scaling_activities_paginator: DescribeScalingActivitiesPaginator = client.get_paginator("describe_scaling_activities")
         describe_scaling_policies_paginator: DescribeScalingPoliciesPaginator = client.get_paginator("describe_scaling_policies")
         describe_scheduled_actions_paginator: DescribeScheduledActionsPaginator = client.get_paginator("describe_scheduled_actions")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ScalableDimensionType, ServiceNamespaceType
 from .type_defs import (
     DescribeScalableTargetsResponseTypeDef,
     DescribeScalingActivitiesResponseTypeDef,
     DescribeScalingPoliciesResponseTypeDef,
     DescribeScheduledActionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeScalableTargetsPaginator",
     "DescribeScalingActivitiesPaginator",
     "DescribeScalingPoliciesPaginator",
     "DescribeScheduledActionsPaginator",
 )
 
@@ -73,15 +66,15 @@
 
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         ResourceIds: Sequence[str] = ...,
         ScalableDimension: ScalableDimensionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalableTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalableTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescalabletargetspaginator)
         """
 
 
@@ -94,15 +87,15 @@
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         ResourceId: str = ...,
         ScalableDimension: ScalableDimensionType = ...,
         IncludeNotScaledActivities: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingActivitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalingActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescalingactivitiespaginator)
         """
 
 
@@ -115,15 +108,15 @@
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         PolicyNames: Sequence[str] = ...,
         ResourceId: str = ...,
         ScalableDimension: ScalableDimensionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalingPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescalingpoliciespaginator)
         """
 
 
@@ -136,13 +129,13 @@
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         ScheduledActionNames: Sequence[str] = ...,
         ResourceId: str = ...,
         ScalableDimension: ScalableDimensionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScheduledActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScheduledActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescheduledactionspaginator)
         """
```

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/paginator.pyi` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -22,34 +22,28 @@
 
         describe_scalable_targets_paginator: DescribeScalableTargetsPaginator = client.get_paginator("describe_scalable_targets")
         describe_scaling_activities_paginator: DescribeScalingActivitiesPaginator = client.get_paginator("describe_scaling_activities")
         describe_scaling_policies_paginator: DescribeScalingPoliciesPaginator = client.get_paginator("describe_scaling_policies")
         describe_scheduled_actions_paginator: DescribeScheduledActionsPaginator = client.get_paginator("describe_scheduled_actions")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ScalableDimensionType, ServiceNamespaceType
 from .type_defs import (
     DescribeScalableTargetsResponseTypeDef,
     DescribeScalingActivitiesResponseTypeDef,
     DescribeScalingPoliciesResponseTypeDef,
     DescribeScheduledActionsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeScalableTargetsPaginator",
     "DescribeScalingActivitiesPaginator",
     "DescribeScalingPoliciesPaginator",
     "DescribeScheduledActionsPaginator",
 )
 
@@ -69,15 +63,15 @@
 
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         ResourceIds: Sequence[str] = ...,
         ScalableDimension: ScalableDimensionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalableTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalableTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescalabletargetspaginator)
         """
 
 class DescribeScalingActivitiesPaginator(AioPaginator):
@@ -89,15 +83,15 @@
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         ResourceId: str = ...,
         ScalableDimension: ScalableDimensionType = ...,
         IncludeNotScaledActivities: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingActivitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalingActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescalingactivitiespaginator)
         """
 
 class DescribeScalingPoliciesPaginator(AioPaginator):
@@ -109,15 +103,15 @@
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         PolicyNames: Sequence[str] = ...,
         ResourceId: str = ...,
         ScalableDimension: ScalableDimensionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScalingPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescalingpoliciespaginator)
         """
 
 class DescribeScheduledActionsPaginator(AioPaginator):
@@ -129,13 +123,13 @@
     def paginate(
         self,
         *,
         ServiceNamespace: ServiceNamespaceType,
         ScheduledActionNames: Sequence[str] = ...,
         ResourceId: str = ...,
         ScalableDimension: ScalableDimensionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScheduledActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling.Paginator.DescribeScheduledActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/paginators/#describescheduledactionspaginator)
         """
```

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/type_defs.py` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_application_autoscaling.type_defs import AlarmTypeDef
 
     data: AlarmTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Sequence, Union
+from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AdjustmentTypeType,
     MetricAggregationTypeType,
     MetricStatisticType,
     MetricTypeType,
     PolicyTypeType,
@@ -27,48 +27,56 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AlarmTypeDef",
     "MetricDimensionTypeDef",
     "DeleteScalingPolicyRequestRequestTypeDef",
     "DeleteScheduledActionRequestRequestTypeDef",
     "DeregisterScalableTargetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
     "DescribeScalableTargetsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
     "DescribeScalingActivitiesRequestRequestTypeDef",
+    "DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
     "DescribeScalingPoliciesRequestRequestTypeDef",
+    "DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
     "DescribeScheduledActionsRequestRequestTypeDef",
+    "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NotScaledReasonTypeDef",
+    "PaginatorConfigTypeDef",
     "PredefinedMetricSpecificationTypeDef",
     "ScalableTargetActionTypeDef",
     "SuspendedStateTypeDef",
+    "RegisterScalableTargetResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StepAdjustmentTypeDef",
-    "CustomizedMetricSpecificationTypeDef",
-    "DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
-    "DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
-    "DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
-    "DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "TargetTrackingMetricDimensionTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "PutScalingPolicyResponseTypeDef",
     "ScalingActivityTypeDef",
     "PutScheduledActionRequestRequestTypeDef",
     "ScheduledActionTypeDef",
     "RegisterScalableTargetRequestRequestTypeDef",
     "ScalableTargetTypeDef",
     "StepScalingPolicyConfigurationTypeDef",
-    "TargetTrackingScalingPolicyConfigurationTypeDef",
+    "TargetTrackingMetricTypeDef",
     "DescribeScalingActivitiesResponseTypeDef",
     "DescribeScheduledActionsResponseTypeDef",
     "DescribeScalableTargetsResponseTypeDef",
+    "TargetTrackingMetricStatTypeDef",
+    "TargetTrackingMetricDataQueryTypeDef",
+    "CustomizedMetricSpecificationTypeDef",
+    "TargetTrackingScalingPolicyConfigurationTypeDef",
     "PutScalingPolicyRequestRequestTypeDef",
     "ScalingPolicyTypeDef",
     "DescribeScalingPoliciesResponseTypeDef",
 )
 
 AlarmTypeDef = TypedDict(
     "AlarmTypeDef",
@@ -111,24 +119,36 @@
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
+    {
+        "ResourceIds": Sequence[str],
+        "ScalableDimension": ScalableDimensionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef(
+    _RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
+    _OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeScalableTargetsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalableTargetsRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
 _OptionalDescribeScalableTargetsRequestRequestTypeDef = TypedDict(
@@ -138,33 +158,43 @@
         "ScalableDimension": ScalableDimensionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeScalableTargetsRequestRequestTypeDef(
     _RequiredDescribeScalableTargetsRequestRequestTypeDef,
     _OptionalDescribeScalableTargetsRequestRequestTypeDef,
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
+    {
+        "ResourceId": str,
+        "ScalableDimension": ScalableDimensionType,
+        "IncludeNotScaledActivities": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
+class DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef(
+    _RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
+    _OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeScalingActivitiesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingActivitiesRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
 _OptionalDescribeScalingActivitiesRequestRequestTypeDef = TypedDict(
@@ -175,21 +205,42 @@
         "MaxResults": int,
         "NextToken": str,
         "IncludeNotScaledActivities": bool,
     },
     total=False,
 )
 
-
 class DescribeScalingActivitiesRequestRequestTypeDef(
     _RequiredDescribeScalingActivitiesRequestRequestTypeDef,
     _OptionalDescribeScalingActivitiesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "PolicyNames": Sequence[str],
+        "ResourceId": str,
+        "ScalableDimension": ScalableDimensionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef(
+    _RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
+    _OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
+):
+    pass
 
 _RequiredDescribeScalingPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingPoliciesRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
@@ -201,21 +252,42 @@
         "ScalableDimension": ScalableDimensionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeScalingPoliciesRequestRequestTypeDef(
     _RequiredDescribeScalingPoliciesRequestRequestTypeDef,
     _OptionalDescribeScalingPoliciesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+    {
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+    {
+        "ScheduledActionNames": Sequence[str],
+        "ResourceId": str,
+        "ScalableDimension": ScalableDimensionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef(
+    _RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
+    _OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
+):
+    pass
 
 _RequiredDescribeScheduledActionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScheduledActionsRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
@@ -227,21 +299,34 @@
         "ScalableDimension": ScalableDimensionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeScheduledActionsRequestRequestTypeDef(
     _RequiredDescribeScheduledActionsRequestRequestTypeDef,
     _OptionalDescribeScheduledActionsRequestRequestTypeDef,
 ):
     pass
 
+ListTagsForResourceRequestRequestTypeDef = TypedDict(
+    "ListTagsForResourceRequestRequestTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredNotScaledReasonTypeDef = TypedDict(
     "_RequiredNotScaledReasonTypeDef",
     {
         "Code": str,
     },
 )
@@ -251,18 +336,26 @@
         "MaxCapacity": int,
         "MinCapacity": int,
         "CurrentCapacity": int,
     },
     total=False,
 )
 
-
 class NotScaledReasonTypeDef(_RequiredNotScaledReasonTypeDef, _OptionalNotScaledReasonTypeDef):
     pass
 
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
+    },
+    total=False,
+)
 
 _RequiredPredefinedMetricSpecificationTypeDef = TypedDict(
     "_RequiredPredefinedMetricSpecificationTypeDef",
     {
         "PredefinedMetricType": MetricTypeType,
     },
 )
@@ -270,21 +363,19 @@
     "_OptionalPredefinedMetricSpecificationTypeDef",
     {
         "ResourceLabel": str,
     },
     total=False,
 )
 
-
 class PredefinedMetricSpecificationTypeDef(
     _RequiredPredefinedMetricSpecificationTypeDef, _OptionalPredefinedMetricSpecificationTypeDef
 ):
     pass
 
-
 ScalableTargetActionTypeDef = TypedDict(
     "ScalableTargetActionTypeDef",
     {
         "MinCapacity": int,
         "MaxCapacity": int,
     },
     total=False,
@@ -296,163 +387,81 @@
         "DynamicScalingInSuspended": bool,
         "DynamicScalingOutSuspended": bool,
         "ScheduledScalingSuspended": bool,
     },
     total=False,
 )
 
-_RequiredStepAdjustmentTypeDef = TypedDict(
-    "_RequiredStepAdjustmentTypeDef",
+RegisterScalableTargetResponseTypeDef = TypedDict(
+    "RegisterScalableTargetResponseTypeDef",
     {
-        "ScalingAdjustment": int,
+        "ScalableTargetARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalStepAdjustmentTypeDef = TypedDict(
-    "_OptionalStepAdjustmentTypeDef",
-    {
-        "MetricIntervalLowerBound": float,
-        "MetricIntervalUpperBound": float,
-    },
-    total=False,
-)
 
-
-class StepAdjustmentTypeDef(_RequiredStepAdjustmentTypeDef, _OptionalStepAdjustmentTypeDef):
-    pass
-
-
-_RequiredCustomizedMetricSpecificationTypeDef = TypedDict(
-    "_RequiredCustomizedMetricSpecificationTypeDef",
-    {
-        "MetricName": str,
-        "Namespace": str,
-        "Statistic": MetricStatisticType,
-    },
-)
-_OptionalCustomizedMetricSpecificationTypeDef = TypedDict(
-    "_OptionalCustomizedMetricSpecificationTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "Dimensions": List[MetricDimensionTypeDef],
-        "Unit": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
-
-class CustomizedMetricSpecificationTypeDef(
-    _RequiredCustomizedMetricSpecificationTypeDef, _OptionalCustomizedMetricSpecificationTypeDef
-):
-    pass
-
-
-_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
+_RequiredStepAdjustmentTypeDef = TypedDict(
+    "_RequiredStepAdjustmentTypeDef",
     {
-        "ServiceNamespace": ServiceNamespaceType,
+        "ScalingAdjustment": int,
     },
 )
-_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
+_OptionalStepAdjustmentTypeDef = TypedDict(
+    "_OptionalStepAdjustmentTypeDef",
     {
-        "ResourceIds": Sequence[str],
-        "ScalableDimension": ScalableDimensionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "MetricIntervalLowerBound": float,
+        "MetricIntervalUpperBound": float,
     },
     total=False,
 )
 
-
-class DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef(
-    _RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
-    _OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
-):
+class StepAdjustmentTypeDef(_RequiredStepAdjustmentTypeDef, _OptionalStepAdjustmentTypeDef):
     pass
 
-
-_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ServiceNamespace": ServiceNamespaceType,
+        "ResourceARN": str,
+        "Tags": Mapping[str, str],
     },
 )
-_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
-    {
-        "ResourceId": str,
-        "ScalableDimension": ScalableDimensionType,
-        "IncludeNotScaledActivities": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 
-class DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef(
-    _RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
-    _OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
-    {
-        "ServiceNamespace": ServiceNamespaceType,
-    },
-)
-_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
+TargetTrackingMetricDimensionTypeDef = TypedDict(
+    "TargetTrackingMetricDimensionTypeDef",
     {
-        "PolicyNames": Sequence[str],
-        "ResourceId": str,
-        "ScalableDimension": ScalableDimensionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Name": str,
+        "Value": str,
     },
-    total=False,
 )
 
-
-class DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef(
-    _RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
-    _OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "ServiceNamespace": ServiceNamespaceType,
+        "ResourceARN": str,
+        "TagKeys": Sequence[str],
     },
 )
-_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
-    {
-        "ScheduledActionNames": Sequence[str],
-        "ResourceId": str,
-        "ScalableDimension": ScalableDimensionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef(
-    _RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
-    _OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
-):
-    pass
-
 
 PutScalingPolicyResponseTypeDef = TypedDict(
     "PutScalingPolicyResponseTypeDef",
     {
         "PolicyARN": str,
         "Alarms": List[AlarmTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredScalingActivityTypeDef = TypedDict(
     "_RequiredScalingActivityTypeDef",
     {
         "ActivityId": str,
@@ -472,19 +481,17 @@
         "StatusMessage": str,
         "Details": str,
         "NotScaledReasons": List[NotScaledReasonTypeDef],
     },
     total=False,
 )
 
-
 class ScalingActivityTypeDef(_RequiredScalingActivityTypeDef, _OptionalScalingActivityTypeDef):
     pass
 
-
 _RequiredPutScheduledActionRequestRequestTypeDef = TypedDict(
     "_RequiredPutScheduledActionRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ScheduledActionName": str,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
@@ -498,22 +505,20 @@
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
         "ScalableTargetAction": ScalableTargetActionTypeDef,
     },
     total=False,
 )
 
-
 class PutScheduledActionRequestRequestTypeDef(
     _RequiredPutScheduledActionRequestRequestTypeDef,
     _OptionalPutScheduledActionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredScheduledActionTypeDef = TypedDict(
     "_RequiredScheduledActionTypeDef",
     {
         "ScheduledActionName": str,
         "ScheduledActionARN": str,
         "ServiceNamespace": ServiceNamespaceType,
         "Schedule": str,
@@ -529,19 +534,17 @@
         "StartTime": datetime,
         "EndTime": datetime,
         "ScalableTargetAction": ScalableTargetActionTypeDef,
     },
     total=False,
 )
 
-
 class ScheduledActionTypeDef(_RequiredScheduledActionTypeDef, _OptionalScheduledActionTypeDef):
     pass
 
-
 _RequiredRegisterScalableTargetRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterScalableTargetRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
     },
@@ -549,26 +552,25 @@
 _OptionalRegisterScalableTargetRequestRequestTypeDef = TypedDict(
     "_OptionalRegisterScalableTargetRequestRequestTypeDef",
     {
         "MinCapacity": int,
         "MaxCapacity": int,
         "RoleARN": str,
         "SuspendedState": SuspendedStateTypeDef,
+        "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class RegisterScalableTargetRequestRequestTypeDef(
     _RequiredRegisterScalableTargetRequestRequestTypeDef,
     _OptionalRegisterScalableTargetRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredScalableTargetTypeDef = TypedDict(
     "_RequiredScalableTargetTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
         "MinCapacity": int,
@@ -577,88 +579,150 @@
         "CreationTime": datetime,
     },
 )
 _OptionalScalableTargetTypeDef = TypedDict(
     "_OptionalScalableTargetTypeDef",
     {
         "SuspendedState": SuspendedStateTypeDef,
+        "ScalableTargetARN": str,
     },
     total=False,
 )
 
-
 class ScalableTargetTypeDef(_RequiredScalableTargetTypeDef, _OptionalScalableTargetTypeDef):
     pass
 
-
 StepScalingPolicyConfigurationTypeDef = TypedDict(
     "StepScalingPolicyConfigurationTypeDef",
     {
         "AdjustmentType": AdjustmentTypeType,
         "StepAdjustments": List[StepAdjustmentTypeDef],
         "MinAdjustmentMagnitude": int,
         "Cooldown": int,
         "MetricAggregationType": MetricAggregationTypeType,
     },
     total=False,
 )
 
-_RequiredTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
-    "_RequiredTargetTrackingScalingPolicyConfigurationTypeDef",
+TargetTrackingMetricTypeDef = TypedDict(
+    "TargetTrackingMetricTypeDef",
     {
-        "TargetValue": float,
-    },
-)
-_OptionalTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
-    "_OptionalTargetTrackingScalingPolicyConfigurationTypeDef",
-    {
-        "PredefinedMetricSpecification": PredefinedMetricSpecificationTypeDef,
-        "CustomizedMetricSpecification": CustomizedMetricSpecificationTypeDef,
-        "ScaleOutCooldown": int,
-        "ScaleInCooldown": int,
-        "DisableScaleIn": bool,
+        "Dimensions": List[TargetTrackingMetricDimensionTypeDef],
+        "MetricName": str,
+        "Namespace": str,
     },
     total=False,
 )
 
-
-class TargetTrackingScalingPolicyConfigurationTypeDef(
-    _RequiredTargetTrackingScalingPolicyConfigurationTypeDef,
-    _OptionalTargetTrackingScalingPolicyConfigurationTypeDef,
-):
-    pass
-
-
 DescribeScalingActivitiesResponseTypeDef = TypedDict(
     "DescribeScalingActivitiesResponseTypeDef",
     {
         "ScalingActivities": List[ScalingActivityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScheduledActionsResponseTypeDef = TypedDict(
     "DescribeScheduledActionsResponseTypeDef",
     {
         "ScheduledActions": List[ScheduledActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScalableTargetsResponseTypeDef = TypedDict(
     "DescribeScalableTargetsResponseTypeDef",
     {
         "ScalableTargets": List[ScalableTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredTargetTrackingMetricStatTypeDef = TypedDict(
+    "_RequiredTargetTrackingMetricStatTypeDef",
+    {
+        "Metric": TargetTrackingMetricTypeDef,
+        "Stat": str,
+    },
+)
+_OptionalTargetTrackingMetricStatTypeDef = TypedDict(
+    "_OptionalTargetTrackingMetricStatTypeDef",
+    {
+        "Unit": str,
+    },
+    total=False,
+)
+
+class TargetTrackingMetricStatTypeDef(
+    _RequiredTargetTrackingMetricStatTypeDef, _OptionalTargetTrackingMetricStatTypeDef
+):
+    pass
+
+_RequiredTargetTrackingMetricDataQueryTypeDef = TypedDict(
+    "_RequiredTargetTrackingMetricDataQueryTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalTargetTrackingMetricDataQueryTypeDef = TypedDict(
+    "_OptionalTargetTrackingMetricDataQueryTypeDef",
+    {
+        "Expression": str,
+        "Label": str,
+        "MetricStat": TargetTrackingMetricStatTypeDef,
+        "ReturnData": bool,
     },
+    total=False,
+)
+
+class TargetTrackingMetricDataQueryTypeDef(
+    _RequiredTargetTrackingMetricDataQueryTypeDef, _OptionalTargetTrackingMetricDataQueryTypeDef
+):
+    pass
+
+CustomizedMetricSpecificationTypeDef = TypedDict(
+    "CustomizedMetricSpecificationTypeDef",
+    {
+        "MetricName": str,
+        "Namespace": str,
+        "Dimensions": List[MetricDimensionTypeDef],
+        "Statistic": MetricStatisticType,
+        "Unit": str,
+        "Metrics": List[TargetTrackingMetricDataQueryTypeDef],
+    },
+    total=False,
 )
 
+_RequiredTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
+    "_RequiredTargetTrackingScalingPolicyConfigurationTypeDef",
+    {
+        "TargetValue": float,
+    },
+)
+_OptionalTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
+    "_OptionalTargetTrackingScalingPolicyConfigurationTypeDef",
+    {
+        "PredefinedMetricSpecification": PredefinedMetricSpecificationTypeDef,
+        "CustomizedMetricSpecification": CustomizedMetricSpecificationTypeDef,
+        "ScaleOutCooldown": int,
+        "ScaleInCooldown": int,
+        "DisableScaleIn": bool,
+    },
+    total=False,
+)
+
+class TargetTrackingScalingPolicyConfigurationTypeDef(
+    _RequiredTargetTrackingScalingPolicyConfigurationTypeDef,
+    _OptionalTargetTrackingScalingPolicyConfigurationTypeDef,
+):
+    pass
+
 _RequiredPutScalingPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutScalingPolicyRequestRequestTypeDef",
     {
         "PolicyName": str,
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
@@ -670,21 +734,19 @@
         "PolicyType": PolicyTypeType,
         "StepScalingPolicyConfiguration": StepScalingPolicyConfigurationTypeDef,
         "TargetTrackingScalingPolicyConfiguration": TargetTrackingScalingPolicyConfigurationTypeDef,
     },
     total=False,
 )
 
-
 class PutScalingPolicyRequestRequestTypeDef(
     _RequiredPutScalingPolicyRequestRequestTypeDef, _OptionalPutScalingPolicyRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredScalingPolicyTypeDef = TypedDict(
     "_RequiredScalingPolicyTypeDef",
     {
         "PolicyARN": str,
         "PolicyName": str,
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
@@ -699,20 +761,18 @@
         "StepScalingPolicyConfiguration": StepScalingPolicyConfigurationTypeDef,
         "TargetTrackingScalingPolicyConfiguration": TargetTrackingScalingPolicyConfigurationTypeDef,
         "Alarms": List[AlarmTypeDef],
     },
     total=False,
 )
 
-
 class ScalingPolicyTypeDef(_RequiredScalingPolicyTypeDef, _OptionalScalingPolicyTypeDef):
     pass
 
-
 DescribeScalingPoliciesResponseTypeDef = TypedDict(
     "DescribeScalingPoliciesResponseTypeDef",
     {
         "ScalingPolicies": List[ScalingPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling/type_defs.pyi` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -9,15 +9,15 @@
     from types_aiobotocore_application_autoscaling.type_defs import AlarmTypeDef
 
     data: AlarmTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Sequence, Union
+from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AdjustmentTypeType,
     MetricAggregationTypeType,
     MetricStatisticType,
     MetricTypeType,
     PolicyTypeType,
@@ -27,47 +27,57 @@
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AlarmTypeDef",
     "MetricDimensionTypeDef",
     "DeleteScalingPolicyRequestRequestTypeDef",
     "DeleteScheduledActionRequestRequestTypeDef",
     "DeregisterScalableTargetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
     "DescribeScalableTargetsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
     "DescribeScalingActivitiesRequestRequestTypeDef",
+    "DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
     "DescribeScalingPoliciesRequestRequestTypeDef",
+    "DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
     "DescribeScheduledActionsRequestRequestTypeDef",
+    "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NotScaledReasonTypeDef",
+    "PaginatorConfigTypeDef",
     "PredefinedMetricSpecificationTypeDef",
     "ScalableTargetActionTypeDef",
     "SuspendedStateTypeDef",
+    "RegisterScalableTargetResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StepAdjustmentTypeDef",
-    "CustomizedMetricSpecificationTypeDef",
-    "DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
-    "DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
-    "DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
-    "DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "TargetTrackingMetricDimensionTypeDef",
+    "UntagResourceRequestRequestTypeDef",
     "PutScalingPolicyResponseTypeDef",
     "ScalingActivityTypeDef",
     "PutScheduledActionRequestRequestTypeDef",
     "ScheduledActionTypeDef",
     "RegisterScalableTargetRequestRequestTypeDef",
     "ScalableTargetTypeDef",
     "StepScalingPolicyConfigurationTypeDef",
-    "TargetTrackingScalingPolicyConfigurationTypeDef",
+    "TargetTrackingMetricTypeDef",
     "DescribeScalingActivitiesResponseTypeDef",
     "DescribeScheduledActionsResponseTypeDef",
     "DescribeScalableTargetsResponseTypeDef",
+    "TargetTrackingMetricStatTypeDef",
+    "TargetTrackingMetricDataQueryTypeDef",
+    "CustomizedMetricSpecificationTypeDef",
+    "TargetTrackingScalingPolicyConfigurationTypeDef",
     "PutScalingPolicyRequestRequestTypeDef",
     "ScalingPolicyTypeDef",
     "DescribeScalingPoliciesResponseTypeDef",
 )
 
 AlarmTypeDef = TypedDict(
     "AlarmTypeDef",
@@ -110,24 +120,38 @@
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
+    {
+        "ResourceIds": Sequence[str],
+        "ScalableDimension": ScalableDimensionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef(
+    _RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
+    _OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeScalableTargetsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalableTargetsRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
 _OptionalDescribeScalableTargetsRequestRequestTypeDef = TypedDict(
@@ -137,31 +161,47 @@
         "ScalableDimension": ScalableDimensionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeScalableTargetsRequestRequestTypeDef(
     _RequiredDescribeScalableTargetsRequestRequestTypeDef,
     _OptionalDescribeScalableTargetsRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
+    {
+        "ResourceId": str,
+        "ScalableDimension": ScalableDimensionType,
+        "IncludeNotScaledActivities": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
+
+class DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef(
+    _RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
+    _OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeScalingActivitiesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingActivitiesRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
 _OptionalDescribeScalingActivitiesRequestRequestTypeDef = TypedDict(
@@ -172,20 +212,47 @@
         "MaxResults": int,
         "NextToken": str,
         "IncludeNotScaledActivities": bool,
     },
     total=False,
 )
 
+
 class DescribeScalingActivitiesRequestRequestTypeDef(
     _RequiredDescribeScalingActivitiesRequestRequestTypeDef,
     _OptionalDescribeScalingActivitiesRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "PolicyNames": Sequence[str],
+        "ResourceId": str,
+        "ScalableDimension": ScalableDimensionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef(
+    _RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
+    _OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeScalingPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingPoliciesRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
 _OptionalDescribeScalingPoliciesRequestRequestTypeDef = TypedDict(
@@ -196,20 +263,47 @@
         "ScalableDimension": ScalableDimensionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeScalingPoliciesRequestRequestTypeDef(
     _RequiredDescribeScalingPoliciesRequestRequestTypeDef,
     _OptionalDescribeScalingPoliciesRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+    {
+        "ServiceNamespace": ServiceNamespaceType,
+    },
+)
+_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+    {
+        "ScheduledActionNames": Sequence[str],
+        "ResourceId": str,
+        "ScalableDimension": ScalableDimensionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef(
+    _RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
+    _OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeScheduledActionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScheduledActionsRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
     },
 )
 _OptionalDescribeScheduledActionsRequestRequestTypeDef = TypedDict(
@@ -220,20 +314,37 @@
         "ScalableDimension": ScalableDimensionType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeScheduledActionsRequestRequestTypeDef(
     _RequiredDescribeScheduledActionsRequestRequestTypeDef,
     _OptionalDescribeScheduledActionsRequestRequestTypeDef,
 ):
     pass
 
+
+ListTagsForResourceRequestRequestTypeDef = TypedDict(
+    "ListTagsForResourceRequestRequestTypeDef",
+    {
+        "ResourceARN": str,
+    },
+)
+
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredNotScaledReasonTypeDef = TypedDict(
     "_RequiredNotScaledReasonTypeDef",
     {
         "Code": str,
     },
 )
 _OptionalNotScaledReasonTypeDef = TypedDict(
@@ -242,36 +353,50 @@
         "MaxCapacity": int,
         "MinCapacity": int,
         "CurrentCapacity": int,
     },
     total=False,
 )
 
+
 class NotScaledReasonTypeDef(_RequiredNotScaledReasonTypeDef, _OptionalNotScaledReasonTypeDef):
     pass
 
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
 _RequiredPredefinedMetricSpecificationTypeDef = TypedDict(
     "_RequiredPredefinedMetricSpecificationTypeDef",
     {
         "PredefinedMetricType": MetricTypeType,
     },
 )
 _OptionalPredefinedMetricSpecificationTypeDef = TypedDict(
     "_OptionalPredefinedMetricSpecificationTypeDef",
     {
         "ResourceLabel": str,
     },
     total=False,
 )
 
+
 class PredefinedMetricSpecificationTypeDef(
     _RequiredPredefinedMetricSpecificationTypeDef, _OptionalPredefinedMetricSpecificationTypeDef
 ):
     pass
 
+
 ScalableTargetActionTypeDef = TypedDict(
     "ScalableTargetActionTypeDef",
     {
         "MinCapacity": int,
         "MaxCapacity": int,
     },
     total=False,
@@ -283,14 +408,33 @@
         "DynamicScalingInSuspended": bool,
         "DynamicScalingOutSuspended": bool,
         "ScheduledScalingSuspended": bool,
     },
     total=False,
 )
 
+RegisterScalableTargetResponseTypeDef = TypedDict(
+    "RegisterScalableTargetResponseTypeDef",
+    {
+        "ScalableTargetARN": str,
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
 _RequiredStepAdjustmentTypeDef = TypedDict(
     "_RequiredStepAdjustmentTypeDef",
     {
         "ScalingAdjustment": int,
     },
 )
 _OptionalStepAdjustmentTypeDef = TypedDict(
@@ -298,136 +442,49 @@
     {
         "MetricIntervalLowerBound": float,
         "MetricIntervalUpperBound": float,
     },
     total=False,
 )
 
-class StepAdjustmentTypeDef(_RequiredStepAdjustmentTypeDef, _OptionalStepAdjustmentTypeDef):
-    pass
-
-_RequiredCustomizedMetricSpecificationTypeDef = TypedDict(
-    "_RequiredCustomizedMetricSpecificationTypeDef",
-    {
-        "MetricName": str,
-        "Namespace": str,
-        "Statistic": MetricStatisticType,
-    },
-)
-_OptionalCustomizedMetricSpecificationTypeDef = TypedDict(
-    "_OptionalCustomizedMetricSpecificationTypeDef",
-    {
-        "Dimensions": List[MetricDimensionTypeDef],
-        "Unit": str,
-    },
-    total=False,
-)
 
-class CustomizedMetricSpecificationTypeDef(
-    _RequiredCustomizedMetricSpecificationTypeDef, _OptionalCustomizedMetricSpecificationTypeDef
-):
+class StepAdjustmentTypeDef(_RequiredStepAdjustmentTypeDef, _OptionalStepAdjustmentTypeDef):
     pass
 
-_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
-    {
-        "ServiceNamespace": ServiceNamespaceType,
-    },
-)
-_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef",
-    {
-        "ResourceIds": Sequence[str],
-        "ScalableDimension": ScalableDimensionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef(
-    _RequiredDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
-    _OptionalDescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
-):
-    pass
 
-_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ServiceNamespace": ServiceNamespaceType,
+        "ResourceARN": str,
+        "Tags": Mapping[str, str],
     },
 )
-_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef",
-    {
-        "ResourceId": str,
-        "ScalableDimension": ScalableDimensionType,
-        "IncludeNotScaledActivities": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-class DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef(
-    _RequiredDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
-    _OptionalDescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
-    {
-        "ServiceNamespace": ServiceNamespaceType,
-    },
-)
-_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef",
+TargetTrackingMetricDimensionTypeDef = TypedDict(
+    "TargetTrackingMetricDimensionTypeDef",
     {
-        "PolicyNames": Sequence[str],
-        "ResourceId": str,
-        "ScalableDimension": ScalableDimensionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Name": str,
+        "Value": str,
     },
-    total=False,
 )
 
-class DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef(
-    _RequiredDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
-    _OptionalDescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
-    {
-        "ServiceNamespace": ServiceNamespaceType,
-    },
-)
-_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "ScheduledActionNames": Sequence[str],
-        "ResourceId": str,
-        "ScalableDimension": ScalableDimensionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResourceARN": str,
+        "TagKeys": Sequence[str],
     },
-    total=False,
 )
 
-class DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef(
-    _RequiredDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
-    _OptionalDescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
-):
-    pass
-
 PutScalingPolicyResponseTypeDef = TypedDict(
     "PutScalingPolicyResponseTypeDef",
     {
         "PolicyARN": str,
         "Alarms": List[AlarmTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredScalingActivityTypeDef = TypedDict(
     "_RequiredScalingActivityTypeDef",
     {
         "ActivityId": str,
@@ -447,17 +504,19 @@
         "StatusMessage": str,
         "Details": str,
         "NotScaledReasons": List[NotScaledReasonTypeDef],
     },
     total=False,
 )
 
+
 class ScalingActivityTypeDef(_RequiredScalingActivityTypeDef, _OptionalScalingActivityTypeDef):
     pass
 
+
 _RequiredPutScheduledActionRequestRequestTypeDef = TypedDict(
     "_RequiredPutScheduledActionRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ScheduledActionName": str,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
@@ -471,20 +530,22 @@
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
         "ScalableTargetAction": ScalableTargetActionTypeDef,
     },
     total=False,
 )
 
+
 class PutScheduledActionRequestRequestTypeDef(
     _RequiredPutScheduledActionRequestRequestTypeDef,
     _OptionalPutScheduledActionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredScheduledActionTypeDef = TypedDict(
     "_RequiredScheduledActionTypeDef",
     {
         "ScheduledActionName": str,
         "ScheduledActionARN": str,
         "ServiceNamespace": ServiceNamespaceType,
         "Schedule": str,
@@ -500,17 +561,19 @@
         "StartTime": datetime,
         "EndTime": datetime,
         "ScalableTargetAction": ScalableTargetActionTypeDef,
     },
     total=False,
 )
 
+
 class ScheduledActionTypeDef(_RequiredScheduledActionTypeDef, _OptionalScheduledActionTypeDef):
     pass
 
+
 _RequiredRegisterScalableTargetRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterScalableTargetRequestRequestTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
     },
@@ -518,24 +581,27 @@
 _OptionalRegisterScalableTargetRequestRequestTypeDef = TypedDict(
     "_OptionalRegisterScalableTargetRequestRequestTypeDef",
     {
         "MinCapacity": int,
         "MaxCapacity": int,
         "RoleARN": str,
         "SuspendedState": SuspendedStateTypeDef,
+        "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class RegisterScalableTargetRequestRequestTypeDef(
     _RequiredRegisterScalableTargetRequestRequestTypeDef,
     _OptionalRegisterScalableTargetRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredScalableTargetTypeDef = TypedDict(
     "_RequiredScalableTargetTypeDef",
     {
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
         "MinCapacity": int,
@@ -544,84 +610,158 @@
         "CreationTime": datetime,
     },
 )
 _OptionalScalableTargetTypeDef = TypedDict(
     "_OptionalScalableTargetTypeDef",
     {
         "SuspendedState": SuspendedStateTypeDef,
+        "ScalableTargetARN": str,
     },
     total=False,
 )
 
+
 class ScalableTargetTypeDef(_RequiredScalableTargetTypeDef, _OptionalScalableTargetTypeDef):
     pass
 
+
 StepScalingPolicyConfigurationTypeDef = TypedDict(
     "StepScalingPolicyConfigurationTypeDef",
     {
         "AdjustmentType": AdjustmentTypeType,
         "StepAdjustments": List[StepAdjustmentTypeDef],
         "MinAdjustmentMagnitude": int,
         "Cooldown": int,
         "MetricAggregationType": MetricAggregationTypeType,
     },
     total=False,
 )
 
-_RequiredTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
-    "_RequiredTargetTrackingScalingPolicyConfigurationTypeDef",
+TargetTrackingMetricTypeDef = TypedDict(
+    "TargetTrackingMetricTypeDef",
     {
-        "TargetValue": float,
-    },
-)
-_OptionalTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
-    "_OptionalTargetTrackingScalingPolicyConfigurationTypeDef",
-    {
-        "PredefinedMetricSpecification": PredefinedMetricSpecificationTypeDef,
-        "CustomizedMetricSpecification": CustomizedMetricSpecificationTypeDef,
-        "ScaleOutCooldown": int,
-        "ScaleInCooldown": int,
-        "DisableScaleIn": bool,
+        "Dimensions": List[TargetTrackingMetricDimensionTypeDef],
+        "MetricName": str,
+        "Namespace": str,
     },
     total=False,
 )
 
-class TargetTrackingScalingPolicyConfigurationTypeDef(
-    _RequiredTargetTrackingScalingPolicyConfigurationTypeDef,
-    _OptionalTargetTrackingScalingPolicyConfigurationTypeDef,
-):
-    pass
-
 DescribeScalingActivitiesResponseTypeDef = TypedDict(
     "DescribeScalingActivitiesResponseTypeDef",
     {
         "ScalingActivities": List[ScalingActivityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScheduledActionsResponseTypeDef = TypedDict(
     "DescribeScheduledActionsResponseTypeDef",
     {
         "ScheduledActions": List[ScheduledActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScalableTargetsResponseTypeDef = TypedDict(
     "DescribeScalableTargetsResponseTypeDef",
     {
         "ScalableTargets": List[ScalableTargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredTargetTrackingMetricStatTypeDef = TypedDict(
+    "_RequiredTargetTrackingMetricStatTypeDef",
+    {
+        "Metric": TargetTrackingMetricTypeDef,
+        "Stat": str,
+    },
+)
+_OptionalTargetTrackingMetricStatTypeDef = TypedDict(
+    "_OptionalTargetTrackingMetricStatTypeDef",
+    {
+        "Unit": str,
+    },
+    total=False,
+)
+
+
+class TargetTrackingMetricStatTypeDef(
+    _RequiredTargetTrackingMetricStatTypeDef, _OptionalTargetTrackingMetricStatTypeDef
+):
+    pass
+
+
+_RequiredTargetTrackingMetricDataQueryTypeDef = TypedDict(
+    "_RequiredTargetTrackingMetricDataQueryTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalTargetTrackingMetricDataQueryTypeDef = TypedDict(
+    "_OptionalTargetTrackingMetricDataQueryTypeDef",
+    {
+        "Expression": str,
+        "Label": str,
+        "MetricStat": TargetTrackingMetricStatTypeDef,
+        "ReturnData": bool,
+    },
+    total=False,
+)
+
+
+class TargetTrackingMetricDataQueryTypeDef(
+    _RequiredTargetTrackingMetricDataQueryTypeDef, _OptionalTargetTrackingMetricDataQueryTypeDef
+):
+    pass
+
+
+CustomizedMetricSpecificationTypeDef = TypedDict(
+    "CustomizedMetricSpecificationTypeDef",
+    {
+        "MetricName": str,
+        "Namespace": str,
+        "Dimensions": List[MetricDimensionTypeDef],
+        "Statistic": MetricStatisticType,
+        "Unit": str,
+        "Metrics": List[TargetTrackingMetricDataQueryTypeDef],
+    },
+    total=False,
+)
+
+_RequiredTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
+    "_RequiredTargetTrackingScalingPolicyConfigurationTypeDef",
+    {
+        "TargetValue": float,
+    },
+)
+_OptionalTargetTrackingScalingPolicyConfigurationTypeDef = TypedDict(
+    "_OptionalTargetTrackingScalingPolicyConfigurationTypeDef",
+    {
+        "PredefinedMetricSpecification": PredefinedMetricSpecificationTypeDef,
+        "CustomizedMetricSpecification": CustomizedMetricSpecificationTypeDef,
+        "ScaleOutCooldown": int,
+        "ScaleInCooldown": int,
+        "DisableScaleIn": bool,
     },
+    total=False,
 )
 
+
+class TargetTrackingScalingPolicyConfigurationTypeDef(
+    _RequiredTargetTrackingScalingPolicyConfigurationTypeDef,
+    _OptionalTargetTrackingScalingPolicyConfigurationTypeDef,
+):
+    pass
+
+
 _RequiredPutScalingPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutScalingPolicyRequestRequestTypeDef",
     {
         "PolicyName": str,
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
         "ScalableDimension": ScalableDimensionType,
@@ -633,19 +773,21 @@
         "PolicyType": PolicyTypeType,
         "StepScalingPolicyConfiguration": StepScalingPolicyConfigurationTypeDef,
         "TargetTrackingScalingPolicyConfiguration": TargetTrackingScalingPolicyConfigurationTypeDef,
     },
     total=False,
 )
 
+
 class PutScalingPolicyRequestRequestTypeDef(
     _RequiredPutScalingPolicyRequestRequestTypeDef, _OptionalPutScalingPolicyRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredScalingPolicyTypeDef = TypedDict(
     "_RequiredScalingPolicyTypeDef",
     {
         "PolicyARN": str,
         "PolicyName": str,
         "ServiceNamespace": ServiceNamespaceType,
         "ResourceId": str,
@@ -660,18 +802,20 @@
         "StepScalingPolicyConfiguration": StepScalingPolicyConfigurationTypeDef,
         "TargetTrackingScalingPolicyConfiguration": TargetTrackingScalingPolicyConfigurationTypeDef,
         "Alarms": List[AlarmTypeDef],
     },
     total=False,
 )
 
+
 class ScalingPolicyTypeDef(_RequiredScalingPolicyTypeDef, _OptionalScalingPolicyTypeDef):
     pass
 
+
 DescribeScalingPoliciesResponseTypeDef = TypedDict(
     "DescribeScalingPoliciesResponseTypeDef",
     {
         "ScalingPolicies": List[ScalingPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/PKG-INFO` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-application-autoscaling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationAutoScaling 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationAutoScaling 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-application-autoscaling"></a>
 
 # types-aiobotocore-application-autoscaling
 
 [![PyPI - types-aiobotocore-application-autoscaling](https://img.shields.io/pypi/v/types-aiobotocore-application-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-autoscaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-application-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-autoscaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-application-autoscaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-application-autoscaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationAutoScaling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
+[aiobotocore.ApplicationAutoScaling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-autoscaling.html#ApplicationAutoScaling)
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
 [types-aiobotocore-application-autoscaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_autoscaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -347,41 +347,50 @@
 ```python
 from types_aiobotocore_application_autoscaling.type_defs import (
     AlarmTypeDef,
     MetricDimensionTypeDef,
     DeleteScalingPolicyRequestRequestTypeDef,
     DeleteScheduledActionRequestRequestTypeDef,
     DeregisterScalableTargetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
     DescribeScalableTargetsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
     DescribeScalingActivitiesRequestRequestTypeDef,
+    DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
     DescribeScalingPoliciesRequestRequestTypeDef,
+    DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
     DescribeScheduledActionsRequestRequestTypeDef,
+    ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NotScaledReasonTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedMetricSpecificationTypeDef,
     ScalableTargetActionTypeDef,
     SuspendedStateTypeDef,
+    RegisterScalableTargetResponseTypeDef,
+    ResponseMetadataTypeDef,
     StepAdjustmentTypeDef,
-    CustomizedMetricSpecificationTypeDef,
-    DescribeScalableTargetsRequestDescribeScalableTargetsPaginateTypeDef,
-    DescribeScalingActivitiesRequestDescribeScalingActivitiesPaginateTypeDef,
-    DescribeScalingPoliciesRequestDescribeScalingPoliciesPaginateTypeDef,
-    DescribeScheduledActionsRequestDescribeScheduledActionsPaginateTypeDef,
+    TagResourceRequestRequestTypeDef,
+    TargetTrackingMetricDimensionTypeDef,
+    UntagResourceRequestRequestTypeDef,
     PutScalingPolicyResponseTypeDef,
     ScalingActivityTypeDef,
     PutScheduledActionRequestRequestTypeDef,
     ScheduledActionTypeDef,
     RegisterScalableTargetRequestRequestTypeDef,
     ScalableTargetTypeDef,
     StepScalingPolicyConfigurationTypeDef,
-    TargetTrackingScalingPolicyConfigurationTypeDef,
+    TargetTrackingMetricTypeDef,
     DescribeScalingActivitiesResponseTypeDef,
     DescribeScheduledActionsResponseTypeDef,
     DescribeScalableTargetsResponseTypeDef,
+    TargetTrackingMetricStatTypeDef,
+    TargetTrackingMetricDataQueryTypeDef,
+    CustomizedMetricSpecificationTypeDef,
+    TargetTrackingScalingPolicyConfigurationTypeDef,
     PutScalingPolicyRequestRequestTypeDef,
     ScalingPolicyTypeDef,
     DescribeScalingPoliciesResponseTypeDef,
 )
 
 
 def get_structure() -> AlarmTypeDef:
@@ -391,43 +400,43 @@
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

### Comparing `types-aiobotocore-application-autoscaling-2.5.0.post1/types_aiobotocore_application_autoscaling.egg-info/SOURCES.txt` & `types-aiobotocore-application-autoscaling-2.5.1/types_aiobotocore_application_autoscaling.egg-info/SOURCES.txt`

 * *Files identical despite different names*

