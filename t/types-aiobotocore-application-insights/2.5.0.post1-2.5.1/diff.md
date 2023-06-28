# Comparing `tmp/types-aiobotocore-application-insights-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-application-insights-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-application-insights-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-application-insights-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-application-insights-2.5.0.post1.tar` & `types-aiobotocore-application-insights-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.726948 types-aiobotocore-application-insights-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15186 2023-03-11 12:26:12.722948 types-aiobotocore-application-insights-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13564 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.726948 types-aiobotocore-application-insights-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2206 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.718948 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/
--rw-r--r--   0 runner    (1001) docker     (123)      541 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      540 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      993 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22691 2023-03-11 12:09:37.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22655 2023-03-11 12:09:37.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9323 2023-03-11 12:09:37.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9321 2023-03-11 12:09:37.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19778 2023-03-11 12:09:37.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19763 2023-03-11 12:09:37.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:36.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.722948 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15186 2023-03-11 12:26:12.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:26:12.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-03-11 12:26:12.000000 types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.474094 types-aiobotocore-application-insights-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15191 2023-06-28 01:43:06.474094 types-aiobotocore-application-insights-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13575 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.474094 types-aiobotocore-application-insights-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2200 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.470094 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/
+-rw-r--r--   0 runner    (1001) docker     (123)      541 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      540 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      981 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22686 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22650 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9532 2023-06-28 01:26:14.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9530 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19816 2023-06-28 01:26:14.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19801 2023-06-28 01:26:14.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:13.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.474094 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15191 2023-06-28 01:43:06.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:43:06.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 01:43:06.000000 types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/LICENSE` & `types-aiobotocore-application-insights-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/PKG-INFO` & `types-aiobotocore-application-insights-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-application-insights
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationInsights 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationInsights 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-application-insights"></a>
 
 # types-aiobotocore-application-insights
 
 [![PyPI - types-aiobotocore-application-insights](https://img.shields.io/pypi/v/types-aiobotocore-application-insights.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-insights)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-application-insights.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-insights)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-application-insights?color=blue)](https://pypistats.org/packages/types-aiobotocore-application-insights)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationInsights 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
+[aiobotocore.ApplicationInsights 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
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
 [types-aiobotocore-application-insights docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/).
 
 See how it helps to find and fix potential bugs:
 
@@ -305,56 +305,56 @@
 
 ```python
 from types_aiobotocore_application_insights.type_defs import (
     ApplicationComponentTypeDef,
     ApplicationInfoTypeDef,
     ConfigurationEventTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateComponentRequestRequestTypeDef,
     CreateLogPatternRequestRequestTypeDef,
     LogPatternTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteLogPatternRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DescribeComponentConfigurationRecommendationRequestRequestTypeDef,
+    DescribeComponentConfigurationRecommendationResponseTypeDef,
     DescribeComponentConfigurationRequestRequestTypeDef,
+    DescribeComponentConfigurationResponseTypeDef,
     DescribeComponentRequestRequestTypeDef,
     DescribeLogPatternRequestRequestTypeDef,
     DescribeObservationRequestRequestTypeDef,
     ObservationTypeDef,
     DescribeProblemObservationsRequestRequestTypeDef,
     DescribeProblemRequestRequestTypeDef,
     ProblemTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListComponentsRequestRequestTypeDef,
     ListConfigurationHistoryRequestRequestTypeDef,
     ListLogPatternSetsRequestRequestTypeDef,
+    ListLogPatternSetsResponseTypeDef,
     ListLogPatternsRequestRequestTypeDef,
     ListProblemsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateComponentConfigurationRequestRequestTypeDef,
     UpdateComponentRequestRequestTypeDef,
     UpdateLogPatternRequestRequestTypeDef,
-    CreateApplicationRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
+    DescribeComponentResponseTypeDef,
+    ListComponentsResponseTypeDef,
     CreateApplicationResponseTypeDef,
     DescribeApplicationResponseTypeDef,
-    DescribeComponentConfigurationRecommendationResponseTypeDef,
-    DescribeComponentConfigurationResponseTypeDef,
-    DescribeComponentResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListComponentsResponseTypeDef,
+    UpdateApplicationResponseTypeDef,
     ListConfigurationHistoryResponseTypeDef,
-    ListLogPatternSetsResponseTypeDef,
+    CreateApplicationRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
-    UpdateApplicationResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateLogPatternResponseTypeDef,
     DescribeLogPatternResponseTypeDef,
     ListLogPatternsResponseTypeDef,
     UpdateLogPatternResponseTypeDef,
     DescribeObservationResponseTypeDef,
     RelatedObservationsTypeDef,
     DescribeProblemResponseTypeDef,
@@ -370,43 +370,43 @@
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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/README.md` & `types-aiobotocore-application-insights-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-application-insights"></a>
 
 # types-aiobotocore-application-insights
 
 [![PyPI - types-aiobotocore-application-insights](https://img.shields.io/pypi/v/types-aiobotocore-application-insights.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-insights)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-application-insights.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-insights)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-application-insights?color=blue)](https://pypistats.org/packages/types-aiobotocore-application-insights)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationInsights 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
+[aiobotocore.ApplicationInsights 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
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
 [types-aiobotocore-application-insights docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/).
 
 See how it helps to find and fix potential bugs:
 
@@ -272,56 +272,56 @@
 
 ```python
 from types_aiobotocore_application_insights.type_defs import (
     ApplicationComponentTypeDef,
     ApplicationInfoTypeDef,
     ConfigurationEventTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateComponentRequestRequestTypeDef,
     CreateLogPatternRequestRequestTypeDef,
     LogPatternTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteLogPatternRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DescribeComponentConfigurationRecommendationRequestRequestTypeDef,
+    DescribeComponentConfigurationRecommendationResponseTypeDef,
     DescribeComponentConfigurationRequestRequestTypeDef,
+    DescribeComponentConfigurationResponseTypeDef,
     DescribeComponentRequestRequestTypeDef,
     DescribeLogPatternRequestRequestTypeDef,
     DescribeObservationRequestRequestTypeDef,
     ObservationTypeDef,
     DescribeProblemObservationsRequestRequestTypeDef,
     DescribeProblemRequestRequestTypeDef,
     ProblemTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListComponentsRequestRequestTypeDef,
     ListConfigurationHistoryRequestRequestTypeDef,
     ListLogPatternSetsRequestRequestTypeDef,
+    ListLogPatternSetsResponseTypeDef,
     ListLogPatternsRequestRequestTypeDef,
     ListProblemsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateComponentConfigurationRequestRequestTypeDef,
     UpdateComponentRequestRequestTypeDef,
     UpdateLogPatternRequestRequestTypeDef,
-    CreateApplicationRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
+    DescribeComponentResponseTypeDef,
+    ListComponentsResponseTypeDef,
     CreateApplicationResponseTypeDef,
     DescribeApplicationResponseTypeDef,
-    DescribeComponentConfigurationRecommendationResponseTypeDef,
-    DescribeComponentConfigurationResponseTypeDef,
-    DescribeComponentResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListComponentsResponseTypeDef,
+    UpdateApplicationResponseTypeDef,
     ListConfigurationHistoryResponseTypeDef,
-    ListLogPatternSetsResponseTypeDef,
+    CreateApplicationRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
-    UpdateApplicationResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateLogPatternResponseTypeDef,
     DescribeLogPatternResponseTypeDef,
     ListLogPatternsResponseTypeDef,
     UpdateLogPatternResponseTypeDef,
     DescribeObservationResponseTypeDef,
     RelatedObservationsTypeDef,
     DescribeProblemResponseTypeDef,
@@ -337,43 +337,43 @@
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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/setup.py` & `types-aiobotocore-application-insights-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-application-insights.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-application-insights",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_application_insights"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ApplicationInsights 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ApplicationInsights 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/",
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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/__init__.py` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/__init__.pyi` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/__main__.py` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ApplicationInsights 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ApplicationInsights 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights\nOther"
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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/client.py` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -142,15 +142,15 @@
         ResourceGroupName: str,
         PatternSetName: str,
         PatternName: str,
         Pattern: str,
         Rank: int
     ) -> CreateLogPatternResponseTypeDef:
         """
-        Adds an log pattern to a `LogPatternSet` .
+        Adds an log pattern to a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.create_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#create_log_pattern)
         """
 
     async def delete_application(self, *, ResourceGroupName: str) -> Dict[str, Any]:
         """
@@ -170,15 +170,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#delete_component)
         """
 
     async def delete_log_pattern(
         self, *, ResourceGroupName: str, PatternSetName: str, PatternName: str
     ) -> Dict[str, Any]:
         """
-        Removes the specified log pattern from a `LogPatternSet` .
+        Removes the specified log pattern from a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.delete_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#delete_log_pattern)
         """
 
     async def describe_application(
         self, *, ResourceGroupName: str
@@ -221,15 +221,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#describe_component_configuration_recommendation)
         """
 
     async def describe_log_pattern(
         self, *, ResourceGroupName: str, PatternSetName: str, PatternName: str
     ) -> DescribeLogPatternResponseTypeDef:
         """
-        Describe a specific log pattern from a `LogPatternSet` .
+        Describe a specific log pattern from a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#describe_log_pattern)
         """
 
     async def describe_observation(
         self, *, ObservationId: str
@@ -326,15 +326,15 @@
         *,
         ResourceGroupName: str,
         PatternSetName: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListLogPatternsResponseTypeDef:
         """
-        Lists the log patterns in the specific log `LogPatternSet` .
+        Lists the log patterns in the specific log `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_log_patterns)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#list_log_patterns)
         """
 
     async def list_problems(
         self,
@@ -436,15 +436,15 @@
         ResourceGroupName: str,
         PatternSetName: str,
         PatternName: str,
         Pattern: str = ...,
         Rank: int = ...
     ) -> UpdateLogPatternResponseTypeDef:
         """
-        Adds a log pattern to a `LogPatternSet` .
+        Adds a log pattern to a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.update_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#update_log_pattern)
         """
 
     async def __aenter__(self) -> "ApplicationInsightsClient":
         """
```

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/client.pyi` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -133,15 +133,15 @@
         ResourceGroupName: str,
         PatternSetName: str,
         PatternName: str,
         Pattern: str,
         Rank: int
     ) -> CreateLogPatternResponseTypeDef:
         """
-        Adds an log pattern to a `LogPatternSet` .
+        Adds an log pattern to a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.create_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#create_log_pattern)
         """
     async def delete_application(self, *, ResourceGroupName: str) -> Dict[str, Any]:
         """
         Removes the specified application from monitoring.
@@ -158,15 +158,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.delete_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#delete_component)
         """
     async def delete_log_pattern(
         self, *, ResourceGroupName: str, PatternSetName: str, PatternName: str
     ) -> Dict[str, Any]:
         """
-        Removes the specified log pattern from a `LogPatternSet` .
+        Removes the specified log pattern from a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.delete_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#delete_log_pattern)
         """
     async def describe_application(
         self, *, ResourceGroupName: str
     ) -> DescribeApplicationResponseTypeDef:
@@ -204,15 +204,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_component_configuration_recommendation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#describe_component_configuration_recommendation)
         """
     async def describe_log_pattern(
         self, *, ResourceGroupName: str, PatternSetName: str, PatternName: str
     ) -> DescribeLogPatternResponseTypeDef:
         """
-        Describe a specific log pattern from a `LogPatternSet` .
+        Describe a specific log pattern from a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.describe_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#describe_log_pattern)
         """
     async def describe_observation(
         self, *, ObservationId: str
     ) -> DescribeObservationResponseTypeDef:
@@ -300,15 +300,15 @@
         *,
         ResourceGroupName: str,
         PatternSetName: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListLogPatternsResponseTypeDef:
         """
-        Lists the log patterns in the specific log `LogPatternSet` .
+        Lists the log patterns in the specific log `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.list_log_patterns)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#list_log_patterns)
         """
     async def list_problems(
         self,
         *,
@@ -402,15 +402,15 @@
         ResourceGroupName: str,
         PatternSetName: str,
         PatternName: str,
         Pattern: str = ...,
         Rank: int = ...
     ) -> UpdateLogPatternResponseTypeDef:
         """
-        Adds a log pattern to a `LogPatternSet` .
+        Adds a log pattern to a `LogPatternSet`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client.update_log_pattern)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/client/#update_log_pattern)
         """
     async def __aenter__(self) -> "ApplicationInsightsClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights.Client)
```

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/literals.py` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -131,14 +131,15 @@
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
@@ -217,14 +218,15 @@
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
@@ -235,14 +237,15 @@
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
@@ -278,14 +281,15 @@
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
@@ -304,16 +308,19 @@
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
@@ -397,15 +404,17 @@
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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/literals.pyi` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -129,14 +129,15 @@
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
@@ -215,14 +216,15 @@
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
@@ -233,14 +235,15 @@
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
@@ -276,14 +279,15 @@
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
@@ -302,16 +306,19 @@
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
@@ -395,15 +402,17 @@
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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/type_defs.py` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,56 +39,56 @@
 
 
 __all__ = (
     "ApplicationComponentTypeDef",
     "ApplicationInfoTypeDef",
     "ConfigurationEventTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateComponentRequestRequestTypeDef",
     "CreateLogPatternRequestRequestTypeDef",
     "LogPatternTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteComponentRequestRequestTypeDef",
     "DeleteLogPatternRequestRequestTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
     "DescribeComponentConfigurationRecommendationRequestRequestTypeDef",
+    "DescribeComponentConfigurationRecommendationResponseTypeDef",
     "DescribeComponentConfigurationRequestRequestTypeDef",
+    "DescribeComponentConfigurationResponseTypeDef",
     "DescribeComponentRequestRequestTypeDef",
     "DescribeLogPatternRequestRequestTypeDef",
     "DescribeObservationRequestRequestTypeDef",
     "ObservationTypeDef",
     "DescribeProblemObservationsRequestRequestTypeDef",
     "DescribeProblemRequestRequestTypeDef",
     "ProblemTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListComponentsRequestRequestTypeDef",
     "ListConfigurationHistoryRequestRequestTypeDef",
     "ListLogPatternSetsRequestRequestTypeDef",
+    "ListLogPatternSetsResponseTypeDef",
     "ListLogPatternsRequestRequestTypeDef",
     "ListProblemsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateComponentConfigurationRequestRequestTypeDef",
     "UpdateComponentRequestRequestTypeDef",
     "UpdateLogPatternRequestRequestTypeDef",
-    "CreateApplicationRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
+    "DescribeComponentResponseTypeDef",
+    "ListComponentsResponseTypeDef",
     "CreateApplicationResponseTypeDef",
     "DescribeApplicationResponseTypeDef",
-    "DescribeComponentConfigurationRecommendationResponseTypeDef",
-    "DescribeComponentConfigurationResponseTypeDef",
-    "DescribeComponentResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListComponentsResponseTypeDef",
+    "UpdateApplicationResponseTypeDef",
     "ListConfigurationHistoryResponseTypeDef",
-    "ListLogPatternSetsResponseTypeDef",
+    "CreateApplicationRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "UpdateApplicationResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateLogPatternResponseTypeDef",
     "DescribeLogPatternResponseTypeDef",
     "ListLogPatternsResponseTypeDef",
     "UpdateLogPatternResponseTypeDef",
     "DescribeObservationResponseTypeDef",
     "RelatedObservationsTypeDef",
     "DescribeProblemResponseTypeDef",
@@ -142,25 +142,14 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 CreateComponentRequestRequestTypeDef = TypedDict(
     "CreateComponentRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
         "ComponentName": str,
         "ResourceList": Sequence[str],
     },
@@ -224,22 +213,40 @@
     {
         "ResourceGroupName": str,
         "ComponentName": str,
         "Tier": TierType,
     },
 )
 
+DescribeComponentConfigurationRecommendationResponseTypeDef = TypedDict(
+    "DescribeComponentConfigurationRecommendationResponseTypeDef",
+    {
+        "ComponentConfiguration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeComponentConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeComponentConfigurationRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
         "ComponentName": str,
     },
 )
 
+DescribeComponentConfigurationResponseTypeDef = TypedDict(
+    "DescribeComponentConfigurationResponseTypeDef",
+    {
+        "Monitor": bool,
+        "Tier": TierType,
+        "ComponentConfiguration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeComponentRequestRequestTypeDef = TypedDict(
     "DescribeComponentRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
         "ComponentName": str,
     },
 )
@@ -408,14 +415,24 @@
 class ListLogPatternSetsRequestRequestTypeDef(
     _RequiredListLogPatternSetsRequestRequestTypeDef,
     _OptionalListLogPatternSetsRequestRequestTypeDef,
 ):
     pass
 
 
+ListLogPatternSetsResponseTypeDef = TypedDict(
+    "ListLogPatternSetsResponseTypeDef",
+    {
+        "ResourceGroupName": str,
+        "LogPatternSets": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListLogPatternsRequestRequestTypeDef = TypedDict(
     "_RequiredListLogPatternsRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
     },
 )
 _OptionalListLogPatternsRequestRequestTypeDef = TypedDict(
@@ -451,14 +468,25 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -557,175 +585,147 @@
 
 class UpdateLogPatternRequestRequestTypeDef(
     _RequiredUpdateLogPatternRequestRequestTypeDef, _OptionalUpdateLogPatternRequestRequestTypeDef
 ):
     pass
 
 
-CreateApplicationRequestRequestTypeDef = TypedDict(
-    "CreateApplicationRequestRequestTypeDef",
+DescribeComponentResponseTypeDef = TypedDict(
+    "DescribeComponentResponseTypeDef",
     {
-        "ResourceGroupName": str,
-        "OpsCenterEnabled": bool,
-        "CWEMonitorEnabled": bool,
-        "OpsItemSNSTopicArn": str,
-        "Tags": Sequence[TagTypeDef],
-        "AutoConfigEnabled": bool,
-        "AutoCreate": bool,
-        "GroupingType": Literal["ACCOUNT_BASED"],
+        "ApplicationComponent": ApplicationComponentTypeDef,
+        "ResourceList": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+ListComponentsResponseTypeDef = TypedDict(
+    "ListComponentsResponseTypeDef",
     {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
+        "ApplicationComponentList": List[ApplicationComponentTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateApplicationResponseTypeDef = TypedDict(
     "CreateApplicationResponseTypeDef",
     {
         "ApplicationInfo": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationResponseTypeDef = TypedDict(
     "DescribeApplicationResponseTypeDef",
     {
         "ApplicationInfo": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComponentConfigurationRecommendationResponseTypeDef = TypedDict(
-    "DescribeComponentConfigurationRecommendationResponseTypeDef",
-    {
-        "ComponentConfiguration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComponentConfigurationResponseTypeDef = TypedDict(
-    "DescribeComponentConfigurationResponseTypeDef",
-    {
-        "Monitor": bool,
-        "Tier": TierType,
-        "ComponentConfiguration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComponentResponseTypeDef = TypedDict(
-    "DescribeComponentResponseTypeDef",
-    {
-        "ApplicationComponent": ApplicationComponentTypeDef,
-        "ResourceList": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationInfoList": List[ApplicationInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListComponentsResponseTypeDef = TypedDict(
-    "ListComponentsResponseTypeDef",
+UpdateApplicationResponseTypeDef = TypedDict(
+    "UpdateApplicationResponseTypeDef",
     {
-        "ApplicationComponentList": List[ApplicationComponentTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationInfo": ApplicationInfoTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConfigurationHistoryResponseTypeDef = TypedDict(
     "ListConfigurationHistoryResponseTypeDef",
     {
         "EventList": List[ConfigurationEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListLogPatternSetsResponseTypeDef = TypedDict(
-    "ListLogPatternSetsResponseTypeDef",
+CreateApplicationRequestRequestTypeDef = TypedDict(
+    "CreateApplicationRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
-        "LogPatternSets": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "OpsCenterEnabled": bool,
+        "CWEMonitorEnabled": bool,
+        "OpsItemSNSTopicArn": str,
+        "Tags": Sequence[TagTypeDef],
+        "AutoConfigEnabled": bool,
+        "AutoCreate": bool,
+        "GroupingType": Literal["ACCOUNT_BASED"],
     },
+    total=False,
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApplicationResponseTypeDef = TypedDict(
-    "UpdateApplicationResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ApplicationInfo": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 CreateLogPatternResponseTypeDef = TypedDict(
     "CreateLogPatternResponseTypeDef",
     {
         "LogPattern": LogPatternTypeDef,
         "ResourceGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLogPatternResponseTypeDef = TypedDict(
     "DescribeLogPatternResponseTypeDef",
     {
         "ResourceGroupName": str,
         "LogPattern": LogPatternTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLogPatternsResponseTypeDef = TypedDict(
     "ListLogPatternsResponseTypeDef",
     {
         "ResourceGroupName": str,
         "LogPatterns": List[LogPatternTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLogPatternResponseTypeDef = TypedDict(
     "UpdateLogPatternResponseTypeDef",
     {
         "ResourceGroupName": str,
         "LogPattern": LogPatternTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeObservationResponseTypeDef = TypedDict(
     "DescribeObservationResponseTypeDef",
     {
         "Observation": ObservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RelatedObservationsTypeDef = TypedDict(
     "RelatedObservationsTypeDef",
     {
         "ObservationList": List[ObservationTypeDef],
@@ -733,28 +733,28 @@
     total=False,
 )
 
 DescribeProblemResponseTypeDef = TypedDict(
     "DescribeProblemResponseTypeDef",
     {
         "Problem": ProblemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProblemsResponseTypeDef = TypedDict(
     "ListProblemsResponseTypeDef",
     {
         "ProblemList": List[ProblemTypeDef],
         "NextToken": str,
         "ResourceGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProblemObservationsResponseTypeDef = TypedDict(
     "DescribeProblemObservationsResponseTypeDef",
     {
         "RelatedObservations": RelatedObservationsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights/type_defs.pyi` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -38,56 +38,56 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "ApplicationComponentTypeDef",
     "ApplicationInfoTypeDef",
     "ConfigurationEventTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateComponentRequestRequestTypeDef",
     "CreateLogPatternRequestRequestTypeDef",
     "LogPatternTypeDef",
     "DeleteApplicationRequestRequestTypeDef",
     "DeleteComponentRequestRequestTypeDef",
     "DeleteLogPatternRequestRequestTypeDef",
     "DescribeApplicationRequestRequestTypeDef",
     "DescribeComponentConfigurationRecommendationRequestRequestTypeDef",
+    "DescribeComponentConfigurationRecommendationResponseTypeDef",
     "DescribeComponentConfigurationRequestRequestTypeDef",
+    "DescribeComponentConfigurationResponseTypeDef",
     "DescribeComponentRequestRequestTypeDef",
     "DescribeLogPatternRequestRequestTypeDef",
     "DescribeObservationRequestRequestTypeDef",
     "ObservationTypeDef",
     "DescribeProblemObservationsRequestRequestTypeDef",
     "DescribeProblemRequestRequestTypeDef",
     "ProblemTypeDef",
     "ListApplicationsRequestRequestTypeDef",
     "ListComponentsRequestRequestTypeDef",
     "ListConfigurationHistoryRequestRequestTypeDef",
     "ListLogPatternSetsRequestRequestTypeDef",
+    "ListLogPatternSetsResponseTypeDef",
     "ListLogPatternsRequestRequestTypeDef",
     "ListProblemsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApplicationRequestRequestTypeDef",
     "UpdateComponentConfigurationRequestRequestTypeDef",
     "UpdateComponentRequestRequestTypeDef",
     "UpdateLogPatternRequestRequestTypeDef",
-    "CreateApplicationRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
+    "DescribeComponentResponseTypeDef",
+    "ListComponentsResponseTypeDef",
     "CreateApplicationResponseTypeDef",
     "DescribeApplicationResponseTypeDef",
-    "DescribeComponentConfigurationRecommendationResponseTypeDef",
-    "DescribeComponentConfigurationResponseTypeDef",
-    "DescribeComponentResponseTypeDef",
     "ListApplicationsResponseTypeDef",
-    "ListComponentsResponseTypeDef",
+    "UpdateApplicationResponseTypeDef",
     "ListConfigurationHistoryResponseTypeDef",
-    "ListLogPatternSetsResponseTypeDef",
+    "CreateApplicationRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "UpdateApplicationResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateLogPatternResponseTypeDef",
     "DescribeLogPatternResponseTypeDef",
     "ListLogPatternsResponseTypeDef",
     "UpdateLogPatternResponseTypeDef",
     "DescribeObservationResponseTypeDef",
     "RelatedObservationsTypeDef",
     "DescribeProblemResponseTypeDef",
@@ -141,25 +141,14 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
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
 CreateComponentRequestRequestTypeDef = TypedDict(
     "CreateComponentRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
         "ComponentName": str,
         "ResourceList": Sequence[str],
     },
@@ -223,22 +212,40 @@
     {
         "ResourceGroupName": str,
         "ComponentName": str,
         "Tier": TierType,
     },
 )
 
+DescribeComponentConfigurationRecommendationResponseTypeDef = TypedDict(
+    "DescribeComponentConfigurationRecommendationResponseTypeDef",
+    {
+        "ComponentConfiguration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeComponentConfigurationRequestRequestTypeDef = TypedDict(
     "DescribeComponentConfigurationRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
         "ComponentName": str,
     },
 )
 
+DescribeComponentConfigurationResponseTypeDef = TypedDict(
+    "DescribeComponentConfigurationResponseTypeDef",
+    {
+        "Monitor": bool,
+        "Tier": TierType,
+        "ComponentConfiguration": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeComponentRequestRequestTypeDef = TypedDict(
     "DescribeComponentRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
         "ComponentName": str,
     },
 )
@@ -403,14 +410,24 @@
 
 class ListLogPatternSetsRequestRequestTypeDef(
     _RequiredListLogPatternSetsRequestRequestTypeDef,
     _OptionalListLogPatternSetsRequestRequestTypeDef,
 ):
     pass
 
+ListLogPatternSetsResponseTypeDef = TypedDict(
+    "ListLogPatternSetsResponseTypeDef",
+    {
+        "ResourceGroupName": str,
+        "LogPatternSets": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListLogPatternsRequestRequestTypeDef = TypedDict(
     "_RequiredListLogPatternsRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
     },
 )
 _OptionalListLogPatternsRequestRequestTypeDef = TypedDict(
@@ -444,14 +461,25 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
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
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -542,175 +570,147 @@
 )
 
 class UpdateLogPatternRequestRequestTypeDef(
     _RequiredUpdateLogPatternRequestRequestTypeDef, _OptionalUpdateLogPatternRequestRequestTypeDef
 ):
     pass
 
-CreateApplicationRequestRequestTypeDef = TypedDict(
-    "CreateApplicationRequestRequestTypeDef",
+DescribeComponentResponseTypeDef = TypedDict(
+    "DescribeComponentResponseTypeDef",
     {
-        "ResourceGroupName": str,
-        "OpsCenterEnabled": bool,
-        "CWEMonitorEnabled": bool,
-        "OpsItemSNSTopicArn": str,
-        "Tags": Sequence[TagTypeDef],
-        "AutoConfigEnabled": bool,
-        "AutoCreate": bool,
-        "GroupingType": Literal["ACCOUNT_BASED"],
+        "ApplicationComponent": ApplicationComponentTypeDef,
+        "ResourceList": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+ListComponentsResponseTypeDef = TypedDict(
+    "ListComponentsResponseTypeDef",
     {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
+        "ApplicationComponentList": List[ApplicationComponentTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateApplicationResponseTypeDef = TypedDict(
     "CreateApplicationResponseTypeDef",
     {
         "ApplicationInfo": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeApplicationResponseTypeDef = TypedDict(
     "DescribeApplicationResponseTypeDef",
     {
         "ApplicationInfo": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComponentConfigurationRecommendationResponseTypeDef = TypedDict(
-    "DescribeComponentConfigurationRecommendationResponseTypeDef",
-    {
-        "ComponentConfiguration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComponentConfigurationResponseTypeDef = TypedDict(
-    "DescribeComponentConfigurationResponseTypeDef",
-    {
-        "Monitor": bool,
-        "Tier": TierType,
-        "ComponentConfiguration": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeComponentResponseTypeDef = TypedDict(
-    "DescribeComponentResponseTypeDef",
-    {
-        "ApplicationComponent": ApplicationComponentTypeDef,
-        "ResourceList": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationsResponseTypeDef = TypedDict(
     "ListApplicationsResponseTypeDef",
     {
         "ApplicationInfoList": List[ApplicationInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListComponentsResponseTypeDef = TypedDict(
-    "ListComponentsResponseTypeDef",
+UpdateApplicationResponseTypeDef = TypedDict(
+    "UpdateApplicationResponseTypeDef",
     {
-        "ApplicationComponentList": List[ApplicationComponentTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationInfo": ApplicationInfoTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConfigurationHistoryResponseTypeDef = TypedDict(
     "ListConfigurationHistoryResponseTypeDef",
     {
         "EventList": List[ConfigurationEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListLogPatternSetsResponseTypeDef = TypedDict(
-    "ListLogPatternSetsResponseTypeDef",
+CreateApplicationRequestRequestTypeDef = TypedDict(
+    "CreateApplicationRequestRequestTypeDef",
     {
         "ResourceGroupName": str,
-        "LogPatternSets": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "OpsCenterEnabled": bool,
+        "CWEMonitorEnabled": bool,
+        "OpsItemSNSTopicArn": str,
+        "Tags": Sequence[TagTypeDef],
+        "AutoConfigEnabled": bool,
+        "AutoCreate": bool,
+        "GroupingType": Literal["ACCOUNT_BASED"],
     },
+    total=False,
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApplicationResponseTypeDef = TypedDict(
-    "UpdateApplicationResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ApplicationInfo": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
 CreateLogPatternResponseTypeDef = TypedDict(
     "CreateLogPatternResponseTypeDef",
     {
         "LogPattern": LogPatternTypeDef,
         "ResourceGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLogPatternResponseTypeDef = TypedDict(
     "DescribeLogPatternResponseTypeDef",
     {
         "ResourceGroupName": str,
         "LogPattern": LogPatternTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLogPatternsResponseTypeDef = TypedDict(
     "ListLogPatternsResponseTypeDef",
     {
         "ResourceGroupName": str,
         "LogPatterns": List[LogPatternTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLogPatternResponseTypeDef = TypedDict(
     "UpdateLogPatternResponseTypeDef",
     {
         "ResourceGroupName": str,
         "LogPattern": LogPatternTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeObservationResponseTypeDef = TypedDict(
     "DescribeObservationResponseTypeDef",
     {
         "Observation": ObservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RelatedObservationsTypeDef = TypedDict(
     "RelatedObservationsTypeDef",
     {
         "ObservationList": List[ObservationTypeDef],
@@ -718,28 +718,28 @@
     total=False,
 )
 
 DescribeProblemResponseTypeDef = TypedDict(
     "DescribeProblemResponseTypeDef",
     {
         "Problem": ProblemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProblemsResponseTypeDef = TypedDict(
     "ListProblemsResponseTypeDef",
     {
         "ProblemList": List[ProblemTypeDef],
         "NextToken": str,
         "ResourceGroupName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeProblemObservationsResponseTypeDef = TypedDict(
     "DescribeProblemObservationsResponseTypeDef",
     {
         "RelatedObservations": RelatedObservationsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/PKG-INFO` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-application-insights
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ApplicationInsights 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ApplicationInsights 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-application-insights"></a>
 
 # types-aiobotocore-application-insights
 
 [![PyPI - types-aiobotocore-application-insights](https://img.shields.io/pypi/v/types-aiobotocore-application-insights.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-insights)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-application-insights.svg?color=blue)](https://pypi.org/project/types-aiobotocore-application-insights)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-application-insights?color=blue)](https://pypistats.org/packages/types-aiobotocore-application-insights)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ApplicationInsights 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
+[aiobotocore.ApplicationInsights 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/application-insights.html#ApplicationInsights)
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
 [types-aiobotocore-application-insights docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_application_insights/).
 
 See how it helps to find and fix potential bugs:
 
@@ -305,56 +305,56 @@
 
 ```python
 from types_aiobotocore_application_insights.type_defs import (
     ApplicationComponentTypeDef,
     ApplicationInfoTypeDef,
     ConfigurationEventTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     CreateComponentRequestRequestTypeDef,
     CreateLogPatternRequestRequestTypeDef,
     LogPatternTypeDef,
     DeleteApplicationRequestRequestTypeDef,
     DeleteComponentRequestRequestTypeDef,
     DeleteLogPatternRequestRequestTypeDef,
     DescribeApplicationRequestRequestTypeDef,
     DescribeComponentConfigurationRecommendationRequestRequestTypeDef,
+    DescribeComponentConfigurationRecommendationResponseTypeDef,
     DescribeComponentConfigurationRequestRequestTypeDef,
+    DescribeComponentConfigurationResponseTypeDef,
     DescribeComponentRequestRequestTypeDef,
     DescribeLogPatternRequestRequestTypeDef,
     DescribeObservationRequestRequestTypeDef,
     ObservationTypeDef,
     DescribeProblemObservationsRequestRequestTypeDef,
     DescribeProblemRequestRequestTypeDef,
     ProblemTypeDef,
     ListApplicationsRequestRequestTypeDef,
     ListComponentsRequestRequestTypeDef,
     ListConfigurationHistoryRequestRequestTypeDef,
     ListLogPatternSetsRequestRequestTypeDef,
+    ListLogPatternSetsResponseTypeDef,
     ListLogPatternsRequestRequestTypeDef,
     ListProblemsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApplicationRequestRequestTypeDef,
     UpdateComponentConfigurationRequestRequestTypeDef,
     UpdateComponentRequestRequestTypeDef,
     UpdateLogPatternRequestRequestTypeDef,
-    CreateApplicationRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
+    DescribeComponentResponseTypeDef,
+    ListComponentsResponseTypeDef,
     CreateApplicationResponseTypeDef,
     DescribeApplicationResponseTypeDef,
-    DescribeComponentConfigurationRecommendationResponseTypeDef,
-    DescribeComponentConfigurationResponseTypeDef,
-    DescribeComponentResponseTypeDef,
     ListApplicationsResponseTypeDef,
-    ListComponentsResponseTypeDef,
+    UpdateApplicationResponseTypeDef,
     ListConfigurationHistoryResponseTypeDef,
-    ListLogPatternSetsResponseTypeDef,
+    CreateApplicationRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
-    UpdateApplicationResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateLogPatternResponseTypeDef,
     DescribeLogPatternResponseTypeDef,
     ListLogPatternsResponseTypeDef,
     UpdateLogPatternResponseTypeDef,
     DescribeObservationResponseTypeDef,
     RelatedObservationsTypeDef,
     DescribeProblemResponseTypeDef,
@@ -370,43 +370,43 @@
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

### Comparing `types-aiobotocore-application-insights-2.5.0.post1/types_aiobotocore_application_insights.egg-info/SOURCES.txt` & `types-aiobotocore-application-insights-2.5.1/types_aiobotocore_application_insights.egg-info/SOURCES.txt`

 * *Files identical despite different names*

