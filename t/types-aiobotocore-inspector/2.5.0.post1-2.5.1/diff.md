# Comparing `tmp/types-aiobotocore-inspector-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-inspector-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-inspector-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:44 2023, max compression
+gzip compressed data, was "types-aiobotocore-inspector-2.5.1.tar", last modified: Wed Jun 28 01:43:36 2023, max compression
```

## Comparing `types-aiobotocore-inspector-2.5.0.post1.tar` & `types-aiobotocore-inspector-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.339273 types-aiobotocore-inspector-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19248 2023-03-11 12:26:44.339273 types-aiobotocore-inspector-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17669 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:44.339273 types-aiobotocore-inspector-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.335273 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/
--rw-r--r--   0 runner    (1001) docker     (123)     2443 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    34033 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    33978 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10699 2023-03-11 12:15:52.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10697 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11903 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11891 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    40454 2023-03-11 12:15:54.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    40389 2023-03-11 12:15:52.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:51.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.339273 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19248 2023-03-11 12:26:44.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:26:44.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:44.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:44.000000 types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.074149 types-aiobotocore-inspector-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19242 2023-06-28 01:43:36.070149 types-aiobotocore-inspector-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17669 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:36.074149 types-aiobotocore-inspector-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.070149 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/
+-rw-r--r--   0 runner    (1001) docker     (123)     2443 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34033 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33978 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10908 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10906 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11801 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11790 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    40530 2023-06-28 01:32:29.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40465 2023-06-28 01:32:29.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:28.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.070149 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19242 2023-06-28 01:43:35.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:43:35.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:35.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:35.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:35.000000 types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-inspector-2.5.0.post1/LICENSE` & `types-aiobotocore-inspector-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/PKG-INFO` & `types-aiobotocore-inspector-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-inspector
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Inspector 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Inspector 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-inspector"></a>
 
 # types-aiobotocore-inspector
 
 [![PyPI - types-aiobotocore-inspector](https://img.shields.io/pypi/v/types-aiobotocore-inspector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-inspector)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-inspector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-inspector)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-inspector?color=blue)](https://pypistats.org/packages/types-aiobotocore-inspector)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Inspector 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector)
+[aiobotocore.Inspector 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector)
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
 [types-aiobotocore-inspector docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/).
 
 See how it helps to find and fix potential bugs:
 
@@ -369,103 +369,103 @@
 `types_aiobotocore_inspector.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_inspector.type_defs import (
     AttributeTypeDef,
     FailedItemDetailsTypeDef,
-    ResponseMetadataTypeDef,
     AgentFilterTypeDef,
     AgentPreviewTypeDef,
     TelemetryMetadataTypeDef,
     DurationRangeTypeDef,
     TimestampRangeTypeDef,
     AssessmentRunNotificationTypeDef,
     AssessmentRunStateChangeTypeDef,
     AssessmentTargetFilterTypeDef,
     AssessmentTargetTypeDef,
     TagTypeDef,
     CreateAssessmentTargetRequestRequestTypeDef,
+    CreateAssessmentTargetResponseTypeDef,
+    CreateAssessmentTemplateResponseTypeDef,
     CreateExclusionsPreviewRequestRequestTypeDef,
+    CreateExclusionsPreviewResponseTypeDef,
     ResourceGroupTagTypeDef,
+    CreateResourceGroupResponseTypeDef,
     DeleteAssessmentRunRequestRequestTypeDef,
     DeleteAssessmentTargetRequestRequestTypeDef,
     DeleteAssessmentTemplateRequestRequestTypeDef,
     DescribeAssessmentRunsRequestRequestTypeDef,
     DescribeAssessmentTargetsRequestRequestTypeDef,
     DescribeAssessmentTemplatesRequestRequestTypeDef,
+    DescribeCrossAccountAccessRoleResponseTypeDef,
     DescribeExclusionsRequestRequestTypeDef,
     DescribeFindingsRequestRequestTypeDef,
     DescribeResourceGroupsRequestRequestTypeDef,
     DescribeRulesPackagesRequestRequestTypeDef,
     RulesPackageTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventSubscriptionTypeDef,
     ScopeTypeDef,
     InspectorServiceAttributesTypeDef,
     GetAssessmentReportRequestRequestTypeDef,
+    GetAssessmentReportResponseTypeDef,
     GetExclusionsPreviewRequestRequestTypeDef,
     GetTelemetryMetadataRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssessmentRunsResponseTypeDef,
+    ListAssessmentTargetsResponseTypeDef,
+    ListAssessmentTemplatesResponseTypeDef,
+    ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef,
     ListEventSubscriptionsRequestRequestTypeDef,
+    ListExclusionsRequestListExclusionsPaginateTypeDef,
     ListExclusionsRequestRequestTypeDef,
+    ListExclusionsResponseTypeDef,
+    ListFindingsResponseTypeDef,
+    ListRulesPackagesRequestListRulesPackagesPaginateTypeDef,
     ListRulesPackagesRequestRequestTypeDef,
+    ListRulesPackagesResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     PrivateIpTypeDef,
     SecurityGroupTypeDef,
+    PaginatorConfigTypeDef,
+    PreviewAgentsRequestPreviewAgentsPaginateTypeDef,
     PreviewAgentsRequestRequestTypeDef,
     RegisterCrossAccountAccessRoleRequestRequestTypeDef,
     RemoveAttributesFromFindingsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartAssessmentRunRequestRequestTypeDef,
+    StartAssessmentRunResponseTypeDef,
     StopAssessmentRunRequestRequestTypeDef,
     SubscribeToEventRequestRequestTypeDef,
     UnsubscribeFromEventRequestRequestTypeDef,
     UpdateAssessmentTargetRequestRequestTypeDef,
     AddAttributesToFindingsRequestRequestTypeDef,
     AssessmentTemplateTypeDef,
     CreateAssessmentTemplateRequestRequestTypeDef,
     AddAttributesToFindingsResponseTypeDef,
-    CreateAssessmentTargetResponseTypeDef,
-    CreateAssessmentTemplateResponseTypeDef,
-    CreateExclusionsPreviewResponseTypeDef,
-    CreateResourceGroupResponseTypeDef,
-    DescribeCrossAccountAccessRoleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAssessmentReportResponseTypeDef,
-    ListAssessmentRunsResponseTypeDef,
-    ListAssessmentTargetsResponseTypeDef,
-    ListAssessmentTemplatesResponseTypeDef,
-    ListExclusionsResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListRulesPackagesResponseTypeDef,
     RemoveAttributesFromFindingsResponseTypeDef,
-    StartAssessmentRunResponseTypeDef,
+    ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
     ListAssessmentRunAgentsRequestRequestTypeDef,
     PreviewAgentsResponseTypeDef,
     AssessmentRunAgentTypeDef,
     GetTelemetryMetadataResponseTypeDef,
     AssessmentTemplateFilterTypeDef,
     AssessmentRunFilterTypeDef,
     FindingFilterTypeDef,
     AssessmentRunTypeDef,
+    ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef,
     ListAssessmentTargetsRequestRequestTypeDef,
     DescribeAssessmentTargetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     SetTagsForResourceRequestRequestTypeDef,
     CreateResourceGroupRequestRequestTypeDef,
     ResourceGroupTypeDef,
     DescribeRulesPackagesResponseTypeDef,
     SubscriptionTypeDef,
     ExclusionPreviewTypeDef,
     ExclusionTypeDef,
-    ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
-    ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef,
-    ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef,
-    ListExclusionsRequestListExclusionsPaginateTypeDef,
-    ListRulesPackagesRequestListRulesPackagesPaginateTypeDef,
-    PreviewAgentsRequestPreviewAgentsPaginateTypeDef,
     NetworkInterfaceTypeDef,
     DescribeAssessmentTemplatesResponseTypeDef,
     ListAssessmentRunAgentsResponseTypeDef,
     ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef,
     ListAssessmentTemplatesRequestRequestTypeDef,
     ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef,
     ListAssessmentRunsRequestRequestTypeDef,
@@ -489,43 +489,43 @@
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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/README.md` & `types-aiobotocore-inspector-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-inspector"></a>
 
 # types-aiobotocore-inspector
 
 [![PyPI - types-aiobotocore-inspector](https://img.shields.io/pypi/v/types-aiobotocore-inspector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-inspector)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-inspector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-inspector)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-inspector?color=blue)](https://pypistats.org/packages/types-aiobotocore-inspector)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Inspector 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector)
+[aiobotocore.Inspector 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector)
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
 [types-aiobotocore-inspector docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/).
 
 See how it helps to find and fix potential bugs:
 
@@ -336,103 +336,103 @@
 `types_aiobotocore_inspector.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_inspector.type_defs import (
     AttributeTypeDef,
     FailedItemDetailsTypeDef,
-    ResponseMetadataTypeDef,
     AgentFilterTypeDef,
     AgentPreviewTypeDef,
     TelemetryMetadataTypeDef,
     DurationRangeTypeDef,
     TimestampRangeTypeDef,
     AssessmentRunNotificationTypeDef,
     AssessmentRunStateChangeTypeDef,
     AssessmentTargetFilterTypeDef,
     AssessmentTargetTypeDef,
     TagTypeDef,
     CreateAssessmentTargetRequestRequestTypeDef,
+    CreateAssessmentTargetResponseTypeDef,
+    CreateAssessmentTemplateResponseTypeDef,
     CreateExclusionsPreviewRequestRequestTypeDef,
+    CreateExclusionsPreviewResponseTypeDef,
     ResourceGroupTagTypeDef,
+    CreateResourceGroupResponseTypeDef,
     DeleteAssessmentRunRequestRequestTypeDef,
     DeleteAssessmentTargetRequestRequestTypeDef,
     DeleteAssessmentTemplateRequestRequestTypeDef,
     DescribeAssessmentRunsRequestRequestTypeDef,
     DescribeAssessmentTargetsRequestRequestTypeDef,
     DescribeAssessmentTemplatesRequestRequestTypeDef,
+    DescribeCrossAccountAccessRoleResponseTypeDef,
     DescribeExclusionsRequestRequestTypeDef,
     DescribeFindingsRequestRequestTypeDef,
     DescribeResourceGroupsRequestRequestTypeDef,
     DescribeRulesPackagesRequestRequestTypeDef,
     RulesPackageTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventSubscriptionTypeDef,
     ScopeTypeDef,
     InspectorServiceAttributesTypeDef,
     GetAssessmentReportRequestRequestTypeDef,
+    GetAssessmentReportResponseTypeDef,
     GetExclusionsPreviewRequestRequestTypeDef,
     GetTelemetryMetadataRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssessmentRunsResponseTypeDef,
+    ListAssessmentTargetsResponseTypeDef,
+    ListAssessmentTemplatesResponseTypeDef,
+    ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef,
     ListEventSubscriptionsRequestRequestTypeDef,
+    ListExclusionsRequestListExclusionsPaginateTypeDef,
     ListExclusionsRequestRequestTypeDef,
+    ListExclusionsResponseTypeDef,
+    ListFindingsResponseTypeDef,
+    ListRulesPackagesRequestListRulesPackagesPaginateTypeDef,
     ListRulesPackagesRequestRequestTypeDef,
+    ListRulesPackagesResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     PrivateIpTypeDef,
     SecurityGroupTypeDef,
+    PaginatorConfigTypeDef,
+    PreviewAgentsRequestPreviewAgentsPaginateTypeDef,
     PreviewAgentsRequestRequestTypeDef,
     RegisterCrossAccountAccessRoleRequestRequestTypeDef,
     RemoveAttributesFromFindingsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartAssessmentRunRequestRequestTypeDef,
+    StartAssessmentRunResponseTypeDef,
     StopAssessmentRunRequestRequestTypeDef,
     SubscribeToEventRequestRequestTypeDef,
     UnsubscribeFromEventRequestRequestTypeDef,
     UpdateAssessmentTargetRequestRequestTypeDef,
     AddAttributesToFindingsRequestRequestTypeDef,
     AssessmentTemplateTypeDef,
     CreateAssessmentTemplateRequestRequestTypeDef,
     AddAttributesToFindingsResponseTypeDef,
-    CreateAssessmentTargetResponseTypeDef,
-    CreateAssessmentTemplateResponseTypeDef,
-    CreateExclusionsPreviewResponseTypeDef,
-    CreateResourceGroupResponseTypeDef,
-    DescribeCrossAccountAccessRoleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAssessmentReportResponseTypeDef,
-    ListAssessmentRunsResponseTypeDef,
-    ListAssessmentTargetsResponseTypeDef,
-    ListAssessmentTemplatesResponseTypeDef,
-    ListExclusionsResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListRulesPackagesResponseTypeDef,
     RemoveAttributesFromFindingsResponseTypeDef,
-    StartAssessmentRunResponseTypeDef,
+    ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
     ListAssessmentRunAgentsRequestRequestTypeDef,
     PreviewAgentsResponseTypeDef,
     AssessmentRunAgentTypeDef,
     GetTelemetryMetadataResponseTypeDef,
     AssessmentTemplateFilterTypeDef,
     AssessmentRunFilterTypeDef,
     FindingFilterTypeDef,
     AssessmentRunTypeDef,
+    ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef,
     ListAssessmentTargetsRequestRequestTypeDef,
     DescribeAssessmentTargetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     SetTagsForResourceRequestRequestTypeDef,
     CreateResourceGroupRequestRequestTypeDef,
     ResourceGroupTypeDef,
     DescribeRulesPackagesResponseTypeDef,
     SubscriptionTypeDef,
     ExclusionPreviewTypeDef,
     ExclusionTypeDef,
-    ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
-    ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef,
-    ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef,
-    ListExclusionsRequestListExclusionsPaginateTypeDef,
-    ListRulesPackagesRequestListRulesPackagesPaginateTypeDef,
-    PreviewAgentsRequestPreviewAgentsPaginateTypeDef,
     NetworkInterfaceTypeDef,
     DescribeAssessmentTemplatesResponseTypeDef,
     ListAssessmentRunAgentsResponseTypeDef,
     ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef,
     ListAssessmentTemplatesRequestRequestTypeDef,
     ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef,
     ListAssessmentRunsRequestRequestTypeDef,
@@ -456,43 +456,43 @@
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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/setup.py` & `types-aiobotocore-inspector-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-inspector.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-inspector",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_inspector"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Inspector 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Inspector 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/"
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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/__init__.py` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/__init__.pyi` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/__main__.py` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Inspector 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Inspector 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector\nOther"
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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/client.py` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/client.pyi` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/literals.py` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -164,14 +164,15 @@
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
@@ -250,14 +251,15 @@
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
@@ -268,14 +270,15 @@
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
@@ -311,14 +314,15 @@
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
@@ -337,16 +341,19 @@
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
@@ -430,15 +437,17 @@
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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/literals.pyi` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -162,14 +162,15 @@
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
@@ -248,14 +249,15 @@
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
@@ -266,14 +268,15 @@
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
@@ -309,14 +312,15 @@
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
@@ -335,16 +339,19 @@
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
@@ -428,15 +435,17 @@
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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/paginator.py` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_event_subscriptions_paginator: ListEventSubscriptionsPaginator = client.get_paginator("list_event_subscriptions")
         list_exclusions_paginator: ListExclusionsPaginator = client.get_paginator("list_exclusions")
         list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
         list_rules_packages_paginator: ListRulesPackagesPaginator = client.get_paginator("list_rules_packages")
         preview_agents_paginator: PreviewAgentsPaginator = client.get_paginator("preview_agents")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     AgentFilterTypeDef,
     AssessmentRunFilterTypeDef,
@@ -56,20 +55,14 @@
     ListExclusionsResponseTypeDef,
     ListFindingsResponseTypeDef,
     ListRulesPackagesResponseTypeDef,
     PaginatorConfigTypeDef,
     PreviewAgentsResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListAssessmentRunAgentsPaginator",
     "ListAssessmentRunsPaginator",
     "ListAssessmentTargetsPaginator",
     "ListAssessmentTemplatesPaginator",
     "ListEventSubscriptionsPaginator",
     "ListExclusionsPaginator",
@@ -96,15 +89,15 @@
     """
 
     def paginate(
         self,
         *,
         assessmentRunArn: str,
         filter: AgentFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentRunAgentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentRunAgents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmentrunagentspaginator)
         """
 
 
@@ -115,15 +108,15 @@
     """
 
     def paginate(
         self,
         *,
         assessmentTemplateArns: Sequence[str] = ...,
         filter: AssessmentRunFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmentrunspaginator)
         """
 
 
@@ -133,15 +126,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmenttargetspaginator)
     """
 
     def paginate(
         self,
         *,
         filter: AssessmentTargetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmenttargetspaginator)
         """
 
 
@@ -152,45 +145,45 @@
     """
 
     def paginate(
         self,
         *,
         assessmentTargetArns: Sequence[str] = ...,
         filter: AssessmentTemplateFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmenttemplatespaginator)
         """
 
 
 class ListEventSubscriptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListEventSubscriptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listeventsubscriptionspaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listeventsubscriptionspaginator)
         """
 
 
 class ListExclusionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListExclusions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listexclusionspaginator)
     """
 
     def paginate(
-        self, *, assessmentRunArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, assessmentRunArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExclusionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListExclusions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listexclusionspaginator)
         """
 
 
@@ -201,43 +194,43 @@
     """
 
     def paginate(
         self,
         *,
         assessmentRunArns: Sequence[str] = ...,
         filter: FindingFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listfindingspaginator)
         """
 
 
 class ListRulesPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListRulesPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listrulespackagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesPackagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListRulesPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listrulespackagespaginator)
         """
 
 
 class PreviewAgentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.PreviewAgents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#previewagentspaginator)
     """
 
     def paginate(
-        self, *, previewAgentsArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, previewAgentsArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[PreviewAgentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.PreviewAgents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#previewagentspaginator)
         """
```

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/paginator.pyi` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_event_subscriptions_paginator: ListEventSubscriptionsPaginator = client.get_paginator("list_event_subscriptions")
         list_exclusions_paginator: ListExclusionsPaginator = client.get_paginator("list_exclusions")
         list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
         list_rules_packages_paginator: ListRulesPackagesPaginator = client.get_paginator("list_rules_packages")
         preview_agents_paginator: PreviewAgentsPaginator = client.get_paginator("preview_agents")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     AgentFilterTypeDef,
     AssessmentRunFilterTypeDef,
@@ -56,19 +55,14 @@
     ListExclusionsResponseTypeDef,
     ListFindingsResponseTypeDef,
     ListRulesPackagesResponseTypeDef,
     PaginatorConfigTypeDef,
     PreviewAgentsResponseTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListAssessmentRunAgentsPaginator",
     "ListAssessmentRunsPaginator",
     "ListAssessmentTargetsPaginator",
     "ListAssessmentTemplatesPaginator",
     "ListEventSubscriptionsPaginator",
     "ListExclusionsPaginator",
@@ -92,15 +86,15 @@
     """
 
     def paginate(
         self,
         *,
         assessmentRunArn: str,
         filter: AgentFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentRunAgentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentRunAgents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmentrunagentspaginator)
         """
 
 class ListAssessmentRunsPaginator(AioPaginator):
@@ -110,15 +104,15 @@
     """
 
     def paginate(
         self,
         *,
         assessmentTemplateArns: Sequence[str] = ...,
         filter: AssessmentRunFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmentrunspaginator)
         """
 
 class ListAssessmentTargetsPaginator(AioPaginator):
@@ -127,15 +121,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmenttargetspaginator)
     """
 
     def paginate(
         self,
         *,
         filter: AssessmentTargetFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmenttargetspaginator)
         """
 
 class ListAssessmentTemplatesPaginator(AioPaginator):
@@ -145,43 +139,43 @@
     """
 
     def paginate(
         self,
         *,
         assessmentTargetArns: Sequence[str] = ...,
         filter: AssessmentTemplateFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAssessmentTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListAssessmentTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listassessmenttemplatespaginator)
         """
 
 class ListEventSubscriptionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListEventSubscriptions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listeventsubscriptionspaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventSubscriptionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListEventSubscriptions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listeventsubscriptionspaginator)
         """
 
 class ListExclusionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListExclusions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listexclusionspaginator)
     """
 
     def paginate(
-        self, *, assessmentRunArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, assessmentRunArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExclusionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListExclusions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listexclusionspaginator)
         """
 
 class ListFindingsPaginator(AioPaginator):
@@ -191,41 +185,41 @@
     """
 
     def paginate(
         self,
         *,
         assessmentRunArns: Sequence[str] = ...,
         filter: FindingFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listfindingspaginator)
         """
 
 class ListRulesPackagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListRulesPackages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listrulespackagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesPackagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.ListRulesPackages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#listrulespackagespaginator)
         """
 
 class PreviewAgentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.PreviewAgents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#previewagentspaginator)
     """
 
     def paginate(
-        self, *, previewAgentsArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, previewAgentsArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[PreviewAgentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector.Paginator.PreviewAgents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/paginators/#previewagentspaginator)
         """
```

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/type_defs.py` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -36,107 +36,106 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AttributeTypeDef",
     "FailedItemDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "AgentFilterTypeDef",
     "AgentPreviewTypeDef",
     "TelemetryMetadataTypeDef",
     "DurationRangeTypeDef",
     "TimestampRangeTypeDef",
     "AssessmentRunNotificationTypeDef",
     "AssessmentRunStateChangeTypeDef",
     "AssessmentTargetFilterTypeDef",
     "AssessmentTargetTypeDef",
     "TagTypeDef",
     "CreateAssessmentTargetRequestRequestTypeDef",
+    "CreateAssessmentTargetResponseTypeDef",
+    "CreateAssessmentTemplateResponseTypeDef",
     "CreateExclusionsPreviewRequestRequestTypeDef",
+    "CreateExclusionsPreviewResponseTypeDef",
     "ResourceGroupTagTypeDef",
+    "CreateResourceGroupResponseTypeDef",
     "DeleteAssessmentRunRequestRequestTypeDef",
     "DeleteAssessmentTargetRequestRequestTypeDef",
     "DeleteAssessmentTemplateRequestRequestTypeDef",
     "DescribeAssessmentRunsRequestRequestTypeDef",
     "DescribeAssessmentTargetsRequestRequestTypeDef",
     "DescribeAssessmentTemplatesRequestRequestTypeDef",
+    "DescribeCrossAccountAccessRoleResponseTypeDef",
     "DescribeExclusionsRequestRequestTypeDef",
     "DescribeFindingsRequestRequestTypeDef",
     "DescribeResourceGroupsRequestRequestTypeDef",
     "DescribeRulesPackagesRequestRequestTypeDef",
     "RulesPackageTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventSubscriptionTypeDef",
     "ScopeTypeDef",
     "InspectorServiceAttributesTypeDef",
     "GetAssessmentReportRequestRequestTypeDef",
+    "GetAssessmentReportResponseTypeDef",
     "GetExclusionsPreviewRequestRequestTypeDef",
     "GetTelemetryMetadataRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssessmentRunsResponseTypeDef",
+    "ListAssessmentTargetsResponseTypeDef",
+    "ListAssessmentTemplatesResponseTypeDef",
+    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
     "ListEventSubscriptionsRequestRequestTypeDef",
+    "ListExclusionsRequestListExclusionsPaginateTypeDef",
     "ListExclusionsRequestRequestTypeDef",
+    "ListExclusionsResponseTypeDef",
+    "ListFindingsResponseTypeDef",
+    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
     "ListRulesPackagesRequestRequestTypeDef",
+    "ListRulesPackagesResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "PrivateIpTypeDef",
     "SecurityGroupTypeDef",
+    "PaginatorConfigTypeDef",
+    "PreviewAgentsRequestPreviewAgentsPaginateTypeDef",
     "PreviewAgentsRequestRequestTypeDef",
     "RegisterCrossAccountAccessRoleRequestRequestTypeDef",
     "RemoveAttributesFromFindingsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAssessmentRunRequestRequestTypeDef",
+    "StartAssessmentRunResponseTypeDef",
     "StopAssessmentRunRequestRequestTypeDef",
     "SubscribeToEventRequestRequestTypeDef",
     "UnsubscribeFromEventRequestRequestTypeDef",
     "UpdateAssessmentTargetRequestRequestTypeDef",
     "AddAttributesToFindingsRequestRequestTypeDef",
     "AssessmentTemplateTypeDef",
     "CreateAssessmentTemplateRequestRequestTypeDef",
     "AddAttributesToFindingsResponseTypeDef",
-    "CreateAssessmentTargetResponseTypeDef",
-    "CreateAssessmentTemplateResponseTypeDef",
-    "CreateExclusionsPreviewResponseTypeDef",
-    "CreateResourceGroupResponseTypeDef",
-    "DescribeCrossAccountAccessRoleResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAssessmentReportResponseTypeDef",
-    "ListAssessmentRunsResponseTypeDef",
-    "ListAssessmentTargetsResponseTypeDef",
-    "ListAssessmentTemplatesResponseTypeDef",
-    "ListExclusionsResponseTypeDef",
-    "ListFindingsResponseTypeDef",
-    "ListRulesPackagesResponseTypeDef",
     "RemoveAttributesFromFindingsResponseTypeDef",
-    "StartAssessmentRunResponseTypeDef",
+    "ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
     "ListAssessmentRunAgentsRequestRequestTypeDef",
     "PreviewAgentsResponseTypeDef",
     "AssessmentRunAgentTypeDef",
     "GetTelemetryMetadataResponseTypeDef",
     "AssessmentTemplateFilterTypeDef",
     "AssessmentRunFilterTypeDef",
     "FindingFilterTypeDef",
     "AssessmentRunTypeDef",
+    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
     "ListAssessmentTargetsRequestRequestTypeDef",
     "DescribeAssessmentTargetsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "SetTagsForResourceRequestRequestTypeDef",
     "CreateResourceGroupRequestRequestTypeDef",
     "ResourceGroupTypeDef",
     "DescribeRulesPackagesResponseTypeDef",
     "SubscriptionTypeDef",
     "ExclusionPreviewTypeDef",
     "ExclusionTypeDef",
-    "ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
-    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
-    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
-    "ListExclusionsRequestListExclusionsPaginateTypeDef",
-    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
-    "PreviewAgentsRequestPreviewAgentsPaginateTypeDef",
     "NetworkInterfaceTypeDef",
     "DescribeAssessmentTemplatesResponseTypeDef",
     "ListAssessmentRunAgentsResponseTypeDef",
     "ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef",
     "ListAssessmentTemplatesRequestRequestTypeDef",
     "ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef",
     "ListAssessmentRunsRequestRequestTypeDef",
@@ -162,38 +161,25 @@
     "_OptionalAttributeTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
-
 class AttributeTypeDef(_RequiredAttributeTypeDef, _OptionalAttributeTypeDef):
     pass
 
-
 FailedItemDetailsTypeDef = TypedDict(
     "FailedItemDetailsTypeDef",
     {
         "failureCode": FailedItemErrorCodeType,
         "retryable": bool,
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
 AgentFilterTypeDef = TypedDict(
     "AgentFilterTypeDef",
     {
         "agentHealths": Sequence[AgentHealthType],
         "agentHealthCodes": Sequence[AgentHealthCodeType],
     },
 )
@@ -214,19 +200,17 @@
         "operatingSystem": str,
         "kernelVersion": str,
         "ipv4Address": str,
     },
     total=False,
 )
 
-
 class AgentPreviewTypeDef(_RequiredAgentPreviewTypeDef, _OptionalAgentPreviewTypeDef):
     pass
 
-
 _RequiredTelemetryMetadataTypeDef = TypedDict(
     "_RequiredTelemetryMetadataTypeDef",
     {
         "messageType": str,
         "count": int,
     },
 )
@@ -234,21 +218,19 @@
     "_OptionalTelemetryMetadataTypeDef",
     {
         "dataSize": int,
     },
     total=False,
 )
 
-
 class TelemetryMetadataTypeDef(
     _RequiredTelemetryMetadataTypeDef, _OptionalTelemetryMetadataTypeDef
 ):
     pass
 
-
 DurationRangeTypeDef = TypedDict(
     "DurationRangeTypeDef",
     {
         "minSeconds": int,
         "maxSeconds": int,
     },
     total=False,
@@ -277,21 +259,19 @@
         "message": str,
         "snsTopicArn": str,
         "snsPublishStatusCode": AssessmentRunNotificationSnsStatusCodeType,
     },
     total=False,
 )
 
-
 class AssessmentRunNotificationTypeDef(
     _RequiredAssessmentRunNotificationTypeDef, _OptionalAssessmentRunNotificationTypeDef
 ):
     pass
 
-
 AssessmentRunStateChangeTypeDef = TypedDict(
     "AssessmentRunStateChangeTypeDef",
     {
         "stateChangedAt": datetime,
         "state": AssessmentRunStateType,
     },
 )
@@ -317,85 +297,109 @@
     "_OptionalAssessmentTargetTypeDef",
     {
         "resourceGroupArn": str,
     },
     total=False,
 )
 
-
 class AssessmentTargetTypeDef(_RequiredAssessmentTargetTypeDef, _OptionalAssessmentTargetTypeDef):
     pass
 
-
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
     "_OptionalTagTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
-
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
-
 _RequiredCreateAssessmentTargetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssessmentTargetRequestRequestTypeDef",
     {
         "assessmentTargetName": str,
     },
 )
 _OptionalCreateAssessmentTargetRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAssessmentTargetRequestRequestTypeDef",
     {
         "resourceGroupArn": str,
     },
     total=False,
 )
 
-
 class CreateAssessmentTargetRequestRequestTypeDef(
     _RequiredCreateAssessmentTargetRequestRequestTypeDef,
     _OptionalCreateAssessmentTargetRequestRequestTypeDef,
 ):
     pass
 
+CreateAssessmentTargetResponseTypeDef = TypedDict(
+    "CreateAssessmentTargetResponseTypeDef",
+    {
+        "assessmentTargetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAssessmentTemplateResponseTypeDef = TypedDict(
+    "CreateAssessmentTemplateResponseTypeDef",
+    {
+        "assessmentTemplateArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 CreateExclusionsPreviewRequestRequestTypeDef = TypedDict(
     "CreateExclusionsPreviewRequestRequestTypeDef",
     {
         "assessmentTemplateArn": str,
     },
 )
 
+CreateExclusionsPreviewResponseTypeDef = TypedDict(
+    "CreateExclusionsPreviewResponseTypeDef",
+    {
+        "previewToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredResourceGroupTagTypeDef = TypedDict(
     "_RequiredResourceGroupTagTypeDef",
     {
         "key": str,
     },
 )
 _OptionalResourceGroupTagTypeDef = TypedDict(
     "_OptionalResourceGroupTagTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
-
 class ResourceGroupTagTypeDef(_RequiredResourceGroupTagTypeDef, _OptionalResourceGroupTagTypeDef):
     pass
 
+CreateResourceGroupResponseTypeDef = TypedDict(
+    "CreateResourceGroupResponseTypeDef",
+    {
+        "resourceGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteAssessmentRunRequestRequestTypeDef = TypedDict(
     "DeleteAssessmentRunRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
@@ -431,57 +435,63 @@
 DescribeAssessmentTemplatesRequestRequestTypeDef = TypedDict(
     "DescribeAssessmentTemplatesRequestRequestTypeDef",
     {
         "assessmentTemplateArns": Sequence[str],
     },
 )
 
+DescribeCrossAccountAccessRoleResponseTypeDef = TypedDict(
+    "DescribeCrossAccountAccessRoleResponseTypeDef",
+    {
+        "roleArn": str,
+        "valid": bool,
+        "registeredAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeExclusionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeExclusionsRequestRequestTypeDef",
     {
         "exclusionArns": Sequence[str],
     },
 )
 _OptionalDescribeExclusionsRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeExclusionsRequestRequestTypeDef",
     {
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
-
 class DescribeExclusionsRequestRequestTypeDef(
     _RequiredDescribeExclusionsRequestRequestTypeDef,
     _OptionalDescribeExclusionsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDescribeFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeFindingsRequestRequestTypeDef",
     {
         "findingArns": Sequence[str],
     },
 )
 _OptionalDescribeFindingsRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeFindingsRequestRequestTypeDef",
     {
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
-
 class DescribeFindingsRequestRequestTypeDef(
     _RequiredDescribeFindingsRequestRequestTypeDef, _OptionalDescribeFindingsRequestRequestTypeDef
 ):
     pass
 
-
 DescribeResourceGroupsRequestRequestTypeDef = TypedDict(
     "DescribeResourceGroupsRequestRequestTypeDef",
     {
         "resourceGroupArns": Sequence[str],
     },
 )
 
@@ -495,22 +505,20 @@
     "_OptionalDescribeRulesPackagesRequestRequestTypeDef",
     {
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
-
 class DescribeRulesPackagesRequestRequestTypeDef(
     _RequiredDescribeRulesPackagesRequestRequestTypeDef,
     _OptionalDescribeRulesPackagesRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredRulesPackageTypeDef = TypedDict(
     "_RequiredRulesPackageTypeDef",
     {
         "arn": str,
         "name": str,
         "version": str,
         "provider": str,
@@ -520,18 +528,23 @@
     "_OptionalRulesPackageTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
-
 class RulesPackageTypeDef(_RequiredRulesPackageTypeDef, _OptionalRulesPackageTypeDef):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 EventSubscriptionTypeDef = TypedDict(
     "EventSubscriptionTypeDef",
     {
         "event": InspectorEventType,
         "subscribedAt": datetime,
     },
@@ -557,30 +570,37 @@
     {
         "assessmentRunArn": str,
         "rulesPackageArn": str,
     },
     total=False,
 )
 
-
 class InspectorServiceAttributesTypeDef(
     _RequiredInspectorServiceAttributesTypeDef, _OptionalInspectorServiceAttributesTypeDef
 ):
     pass
 
-
 GetAssessmentReportRequestRequestTypeDef = TypedDict(
     "GetAssessmentReportRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
         "reportFileFormat": ReportFileFormatType,
         "reportType": ReportTypeType,
     },
 )
 
+GetAssessmentReportResponseTypeDef = TypedDict(
+    "GetAssessmentReportResponseTypeDef",
+    {
+        "status": ReportStatusType,
+        "url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetExclusionsPreviewRequestRequestTypeDef = TypedDict(
     "_RequiredGetExclusionsPreviewRequestRequestTypeDef",
     {
         "assessmentTemplateArn": str,
         "previewToken": str,
     },
 )
@@ -590,49 +610,93 @@
         "nextToken": str,
         "maxResults": int,
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
-
 class GetExclusionsPreviewRequestRequestTypeDef(
     _RequiredGetExclusionsPreviewRequestRequestTypeDef,
     _OptionalGetExclusionsPreviewRequestRequestTypeDef,
 ):
     pass
 
-
 GetTelemetryMetadataRequestRequestTypeDef = TypedDict(
     "GetTelemetryMetadataRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAssessmentRunsResponseTypeDef = TypedDict(
+    "ListAssessmentRunsResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "assessmentRunArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAssessmentTargetsResponseTypeDef = TypedDict(
+    "ListAssessmentTargetsResponseTypeDef",
+    {
+        "assessmentTargetArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAssessmentTemplatesResponseTypeDef = TypedDict(
+    "ListAssessmentTemplatesResponseTypeDef",
+    {
+        "assessmentTemplateArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef = TypedDict(
+    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
+    {
+        "resourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEventSubscriptionsRequestRequestTypeDef = TypedDict(
     "ListEventSubscriptionsRequestRequestTypeDef",
     {
         "resourceArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
+    "_RequiredListExclusionsRequestListExclusionsPaginateTypeDef",
+    {
+        "assessmentRunArn": str,
+    },
+)
+_OptionalListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
+    "_OptionalListExclusionsRequestListExclusionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListExclusionsRequestListExclusionsPaginateTypeDef(
+    _RequiredListExclusionsRequestListExclusionsPaginateTypeDef,
+    _OptionalListExclusionsRequestListExclusionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListExclusionsRequestRequestTypeDef = TypedDict(
     "_RequiredListExclusionsRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
 _OptionalListExclusionsRequestRequestTypeDef = TypedDict(
@@ -640,30 +704,63 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class ListExclusionsRequestRequestTypeDef(
     _RequiredListExclusionsRequestRequestTypeDef, _OptionalListExclusionsRequestRequestTypeDef
 ):
     pass
 
+ListExclusionsResponseTypeDef = TypedDict(
+    "ListExclusionsResponseTypeDef",
+    {
+        "exclusionArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFindingsResponseTypeDef = TypedDict(
+    "ListFindingsResponseTypeDef",
+    {
+        "findingArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListRulesPackagesRequestListRulesPackagesPaginateTypeDef = TypedDict(
+    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListRulesPackagesRequestRequestTypeDef = TypedDict(
     "ListRulesPackagesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListRulesPackagesResponseTypeDef = TypedDict(
+    "ListRulesPackagesResponseTypeDef",
+    {
+        "rulesPackageArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
@@ -681,14 +778,44 @@
     {
         "groupName": str,
         "groupId": str,
     },
     total=False,
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
+_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
+    "_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
+    {
+        "previewAgentsArn": str,
+    },
+)
+_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
+    "_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class PreviewAgentsRequestPreviewAgentsPaginateTypeDef(
+    _RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
+    _OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
+):
+    pass
+
 _RequiredPreviewAgentsRequestRequestTypeDef = TypedDict(
     "_RequiredPreviewAgentsRequestRequestTypeDef",
     {
         "previewAgentsArn": str,
     },
 )
 _OptionalPreviewAgentsRequestRequestTypeDef = TypedDict(
@@ -696,21 +823,19 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class PreviewAgentsRequestRequestTypeDef(
     _RequiredPreviewAgentsRequestRequestTypeDef, _OptionalPreviewAgentsRequestRequestTypeDef
 ):
     pass
 
-
 RegisterCrossAccountAccessRoleRequestRequestTypeDef = TypedDict(
     "RegisterCrossAccountAccessRoleRequestRequestTypeDef",
     {
         "roleArn": str,
     },
 )
 
@@ -718,35 +843,52 @@
     "RemoveAttributesFromFindingsRequestRequestTypeDef",
     {
         "findingArns": Sequence[str],
         "attributeKeys": Sequence[str],
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
 _RequiredStartAssessmentRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartAssessmentRunRequestRequestTypeDef",
     {
         "assessmentTemplateArn": str,
     },
 )
 _OptionalStartAssessmentRunRequestRequestTypeDef = TypedDict(
     "_OptionalStartAssessmentRunRequestRequestTypeDef",
     {
         "assessmentRunName": str,
     },
     total=False,
 )
 
-
 class StartAssessmentRunRequestRequestTypeDef(
     _RequiredStartAssessmentRunRequestRequestTypeDef,
     _OptionalStartAssessmentRunRequestRequestTypeDef,
 ):
     pass
 
+StartAssessmentRunResponseTypeDef = TypedDict(
+    "StartAssessmentRunResponseTypeDef",
+    {
+        "assessmentRunArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredStopAssessmentRunRequestRequestTypeDef = TypedDict(
     "_RequiredStopAssessmentRunRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
@@ -754,21 +896,19 @@
     "_OptionalStopAssessmentRunRequestRequestTypeDef",
     {
         "stopAction": StopActionType,
     },
     total=False,
 )
 
-
 class StopAssessmentRunRequestRequestTypeDef(
     _RequiredStopAssessmentRunRequestRequestTypeDef, _OptionalStopAssessmentRunRequestRequestTypeDef
 ):
     pass
 
-
 SubscribeToEventRequestRequestTypeDef = TypedDict(
     "SubscribeToEventRequestRequestTypeDef",
     {
         "resourceArn": str,
         "event": InspectorEventType,
         "topicArn": str,
     },
@@ -794,22 +934,20 @@
     "_OptionalUpdateAssessmentTargetRequestRequestTypeDef",
     {
         "resourceGroupArn": str,
     },
     total=False,
 )
 
-
 class UpdateAssessmentTargetRequestRequestTypeDef(
     _RequiredUpdateAssessmentTargetRequestRequestTypeDef,
     _OptionalUpdateAssessmentTargetRequestRequestTypeDef,
 ):
     pass
 
-
 AddAttributesToFindingsRequestRequestTypeDef = TypedDict(
     "AddAttributesToFindingsRequestRequestTypeDef",
     {
         "findingArns": Sequence[str],
         "attributes": Sequence[AttributeTypeDef],
     },
 )
@@ -831,21 +969,19 @@
     "_OptionalAssessmentTemplateTypeDef",
     {
         "lastAssessmentRunArn": str,
     },
     total=False,
 )
 
-
 class AssessmentTemplateTypeDef(
     _RequiredAssessmentTemplateTypeDef, _OptionalAssessmentTemplateTypeDef
 ):
     pass
 
-
 _RequiredCreateAssessmentTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssessmentTemplateRequestRequestTypeDef",
     {
         "assessmentTargetArn": str,
         "assessmentTemplateName": str,
         "durationInSeconds": int,
         "rulesPackageArns": Sequence[str],
@@ -855,157 +991,56 @@
     "_OptionalCreateAssessmentTemplateRequestRequestTypeDef",
     {
         "userAttributesForFindings": Sequence[AttributeTypeDef],
     },
     total=False,
 )
 
-
 class CreateAssessmentTemplateRequestRequestTypeDef(
     _RequiredCreateAssessmentTemplateRequestRequestTypeDef,
     _OptionalCreateAssessmentTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 AddAttributesToFindingsResponseTypeDef = TypedDict(
     "AddAttributesToFindingsResponseTypeDef",
     {
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAssessmentTargetResponseTypeDef = TypedDict(
-    "CreateAssessmentTargetResponseTypeDef",
-    {
-        "assessmentTargetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAssessmentTemplateResponseTypeDef = TypedDict(
-    "CreateAssessmentTemplateResponseTypeDef",
-    {
-        "assessmentTemplateArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateExclusionsPreviewResponseTypeDef = TypedDict(
-    "CreateExclusionsPreviewResponseTypeDef",
-    {
-        "previewToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResourceGroupResponseTypeDef = TypedDict(
-    "CreateResourceGroupResponseTypeDef",
-    {
-        "resourceGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCrossAccountAccessRoleResponseTypeDef = TypedDict(
-    "DescribeCrossAccountAccessRoleResponseTypeDef",
-    {
-        "roleArn": str,
-        "valid": bool,
-        "registeredAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAssessmentReportResponseTypeDef = TypedDict(
-    "GetAssessmentReportResponseTypeDef",
-    {
-        "status": ReportStatusType,
-        "url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssessmentRunsResponseTypeDef = TypedDict(
-    "ListAssessmentRunsResponseTypeDef",
-    {
-        "assessmentRunArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssessmentTargetsResponseTypeDef = TypedDict(
-    "ListAssessmentTargetsResponseTypeDef",
-    {
-        "assessmentTargetArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssessmentTemplatesResponseTypeDef = TypedDict(
-    "ListAssessmentTemplatesResponseTypeDef",
-    {
-        "assessmentTemplateArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListExclusionsResponseTypeDef = TypedDict(
-    "ListExclusionsResponseTypeDef",
-    {
-        "exclusionArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFindingsResponseTypeDef = TypedDict(
-    "ListFindingsResponseTypeDef",
-    {
-        "findingArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRulesPackagesResponseTypeDef = TypedDict(
-    "ListRulesPackagesResponseTypeDef",
-    {
-        "rulesPackageArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveAttributesFromFindingsResponseTypeDef = TypedDict(
     "RemoveAttributesFromFindingsResponseTypeDef",
     {
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartAssessmentRunResponseTypeDef = TypedDict(
-    "StartAssessmentRunResponseTypeDef",
+_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
+    "_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
     {
         "assessmentRunArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
+_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
+    "_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
+    {
+        "filter": AgentFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef(
+    _RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
+    _OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
+):
+    pass
 
 _RequiredListAssessmentRunAgentsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssessmentRunAgentsRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
@@ -1015,28 +1050,26 @@
         "filter": AgentFilterTypeDef,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class ListAssessmentRunAgentsRequestRequestTypeDef(
     _RequiredListAssessmentRunAgentsRequestRequestTypeDef,
     _OptionalListAssessmentRunAgentsRequestRequestTypeDef,
 ):
     pass
 
-
 PreviewAgentsResponseTypeDef = TypedDict(
     "PreviewAgentsResponseTypeDef",
     {
         "agentPreviews": List[AgentPreviewTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssessmentRunAgentTypeDef = TypedDict(
     "_RequiredAssessmentRunAgentTypeDef",
     {
         "agentId": str,
@@ -1051,26 +1084,24 @@
     {
         "agentHealthDetails": str,
         "autoScalingGroup": str,
     },
     total=False,
 )
 
-
 class AssessmentRunAgentTypeDef(
     _RequiredAssessmentRunAgentTypeDef, _OptionalAssessmentRunAgentTypeDef
 ):
     pass
 
-
 GetTelemetryMetadataResponseTypeDef = TypedDict(
     "GetTelemetryMetadataResponseTypeDef",
     {
         "telemetryMetadata": List[TelemetryMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentTemplateFilterTypeDef = TypedDict(
     "AssessmentTemplateFilterTypeDef",
     {
         "namePattern": str,
@@ -1132,18 +1163,25 @@
     {
         "startedAt": datetime,
         "completedAt": datetime,
     },
     total=False,
 )
 
-
 class AssessmentRunTypeDef(_RequiredAssessmentRunTypeDef, _OptionalAssessmentRunTypeDef):
     pass
 
+ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef = TypedDict(
+    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
+    {
+        "filter": AssessmentTargetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListAssessmentTargetsRequestRequestTypeDef = TypedDict(
     "ListAssessmentTargetsRequestRequestTypeDef",
     {
         "filter": AssessmentTargetFilterTypeDef,
         "nextToken": str,
         "maxResults": int,
@@ -1152,23 +1190,23 @@
 )
 
 DescribeAssessmentTargetsResponseTypeDef = TypedDict(
     "DescribeAssessmentTargetsResponseTypeDef",
     {
         "assessmentTargets": List[AssessmentTargetTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredSetTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1178,22 +1216,20 @@
     "_OptionalSetTagsForResourceRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class SetTagsForResourceRequestRequestTypeDef(
     _RequiredSetTagsForResourceRequestRequestTypeDef,
     _OptionalSetTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
-
 CreateResourceGroupRequestRequestTypeDef = TypedDict(
     "CreateResourceGroupRequestRequestTypeDef",
     {
         "resourceGroupTags": Sequence[ResourceGroupTagTypeDef],
     },
 )
 
@@ -1207,15 +1243,15 @@
 )
 
 DescribeRulesPackagesResponseTypeDef = TypedDict(
     "DescribeRulesPackagesResponseTypeDef",
     {
         "rulesPackages": List[RulesPackageTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubscriptionTypeDef = TypedDict(
     "SubscriptionTypeDef",
     {
         "resourceArn": str,
@@ -1237,19 +1273,17 @@
     "_OptionalExclusionPreviewTypeDef",
     {
         "attributes": List[AttributeTypeDef],
     },
     total=False,
 )
 
-
 class ExclusionPreviewTypeDef(_RequiredExclusionPreviewTypeDef, _OptionalExclusionPreviewTypeDef):
     pass
 
-
 _RequiredExclusionTypeDef = TypedDict(
     "_RequiredExclusionTypeDef",
     {
         "arn": str,
         "title": str,
         "description": str,
         "recommendation": str,
@@ -1260,112 +1294,17 @@
     "_OptionalExclusionTypeDef",
     {
         "attributes": List[AttributeTypeDef],
     },
     total=False,
 )
 
-
 class ExclusionTypeDef(_RequiredExclusionTypeDef, _OptionalExclusionTypeDef):
     pass
 
-
-_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
-    "_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
-    {
-        "assessmentRunArn": str,
-    },
-)
-_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
-    "_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
-    {
-        "filter": AgentFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef(
-    _RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
-    _OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
-):
-    pass
-
-
-ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef = TypedDict(
-    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
-    {
-        "filter": AssessmentTargetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef = TypedDict(
-    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
-    {
-        "resourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
-    "_RequiredListExclusionsRequestListExclusionsPaginateTypeDef",
-    {
-        "assessmentRunArn": str,
-    },
-)
-_OptionalListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
-    "_OptionalListExclusionsRequestListExclusionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListExclusionsRequestListExclusionsPaginateTypeDef(
-    _RequiredListExclusionsRequestListExclusionsPaginateTypeDef,
-    _OptionalListExclusionsRequestListExclusionsPaginateTypeDef,
-):
-    pass
-
-
-ListRulesPackagesRequestListRulesPackagesPaginateTypeDef = TypedDict(
-    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
-    "_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
-    {
-        "previewAgentsArn": str,
-    },
-)
-_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
-    "_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class PreviewAgentsRequestPreviewAgentsPaginateTypeDef(
-    _RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
-    _OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
-):
-    pass
-
-
 NetworkInterfaceTypeDef = TypedDict(
     "NetworkInterfaceTypeDef",
     {
         "networkInterfaceId": str,
         "subnetId": str,
         "vpcId": str,
         "privateDnsName": str,
@@ -1380,33 +1319,33 @@
 )
 
 DescribeAssessmentTemplatesResponseTypeDef = TypedDict(
     "DescribeAssessmentTemplatesResponseTypeDef",
     {
         "assessmentTemplates": List[AssessmentTemplateTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentRunAgentsResponseTypeDef = TypedDict(
     "ListAssessmentRunAgentsResponseTypeDef",
     {
         "assessmentRunAgents": List[AssessmentRunAgentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef = TypedDict(
     "ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef",
     {
         "assessmentTargetArns": Sequence[str],
         "filter": AssessmentTemplateFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAssessmentTemplatesRequestRequestTypeDef = TypedDict(
     "ListAssessmentTemplatesRequestRequestTypeDef",
     {
@@ -1419,15 +1358,15 @@
 )
 
 ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef = TypedDict(
     "ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef",
     {
         "assessmentTemplateArns": Sequence[str],
         "filter": AssessmentRunFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAssessmentRunsRequestRequestTypeDef = TypedDict(
     "ListAssessmentRunsRequestRequestTypeDef",
     {
@@ -1440,15 +1379,15 @@
 )
 
 ListFindingsRequestListFindingsPaginateTypeDef = TypedDict(
     "ListFindingsRequestListFindingsPaginateTypeDef",
     {
         "assessmentRunArns": Sequence[str],
         "filter": FindingFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFindingsRequestRequestTypeDef = TypedDict(
     "ListFindingsRequestRequestTypeDef",
     {
@@ -1461,52 +1400,52 @@
 )
 
 DescribeAssessmentRunsResponseTypeDef = TypedDict(
     "DescribeAssessmentRunsResponseTypeDef",
     {
         "assessmentRuns": List[AssessmentRunTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeResourceGroupsResponseTypeDef = TypedDict(
     "DescribeResourceGroupsResponseTypeDef",
     {
         "resourceGroups": List[ResourceGroupTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventSubscriptionsResponseTypeDef = TypedDict(
     "ListEventSubscriptionsResponseTypeDef",
     {
         "subscriptions": List[SubscriptionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExclusionsPreviewResponseTypeDef = TypedDict(
     "GetExclusionsPreviewResponseTypeDef",
     {
         "previewStatus": PreviewStatusType,
         "exclusionPreviews": List[ExclusionPreviewTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExclusionsResponseTypeDef = TypedDict(
     "DescribeExclusionsResponseTypeDef",
     {
         "exclusions": Dict[str, ExclusionTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetAttributesTypeDef = TypedDict(
     "_RequiredAssetAttributesTypeDef",
     {
         "schemaVersion": int,
@@ -1522,19 +1461,17 @@
         "ipv4Addresses": List[str],
         "tags": List[TagTypeDef],
         "networkInterfaces": List[NetworkInterfaceTypeDef],
     },
     total=False,
 )
 
-
 class AssetAttributesTypeDef(_RequiredAssetAttributesTypeDef, _OptionalAssetAttributesTypeDef):
     pass
 
-
 _RequiredFindingTypeDef = TypedDict(
     "_RequiredFindingTypeDef",
     {
         "arn": str,
         "attributes": List[AttributeTypeDef],
         "userAttributes": List[AttributeTypeDef],
         "createdAt": datetime,
@@ -1557,20 +1494,18 @@
         "numericSeverity": float,
         "confidence": int,
         "indicatorOfCompromise": bool,
     },
     total=False,
 )
 
-
 class FindingTypeDef(_RequiredFindingTypeDef, _OptionalFindingTypeDef):
     pass
 
-
 DescribeFindingsResponseTypeDef = TypedDict(
     "DescribeFindingsResponseTypeDef",
     {
         "findings": List[FindingTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector/type_defs.pyi` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -36,106 +36,107 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AttributeTypeDef",
     "FailedItemDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "AgentFilterTypeDef",
     "AgentPreviewTypeDef",
     "TelemetryMetadataTypeDef",
     "DurationRangeTypeDef",
     "TimestampRangeTypeDef",
     "AssessmentRunNotificationTypeDef",
     "AssessmentRunStateChangeTypeDef",
     "AssessmentTargetFilterTypeDef",
     "AssessmentTargetTypeDef",
     "TagTypeDef",
     "CreateAssessmentTargetRequestRequestTypeDef",
+    "CreateAssessmentTargetResponseTypeDef",
+    "CreateAssessmentTemplateResponseTypeDef",
     "CreateExclusionsPreviewRequestRequestTypeDef",
+    "CreateExclusionsPreviewResponseTypeDef",
     "ResourceGroupTagTypeDef",
+    "CreateResourceGroupResponseTypeDef",
     "DeleteAssessmentRunRequestRequestTypeDef",
     "DeleteAssessmentTargetRequestRequestTypeDef",
     "DeleteAssessmentTemplateRequestRequestTypeDef",
     "DescribeAssessmentRunsRequestRequestTypeDef",
     "DescribeAssessmentTargetsRequestRequestTypeDef",
     "DescribeAssessmentTemplatesRequestRequestTypeDef",
+    "DescribeCrossAccountAccessRoleResponseTypeDef",
     "DescribeExclusionsRequestRequestTypeDef",
     "DescribeFindingsRequestRequestTypeDef",
     "DescribeResourceGroupsRequestRequestTypeDef",
     "DescribeRulesPackagesRequestRequestTypeDef",
     "RulesPackageTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventSubscriptionTypeDef",
     "ScopeTypeDef",
     "InspectorServiceAttributesTypeDef",
     "GetAssessmentReportRequestRequestTypeDef",
+    "GetAssessmentReportResponseTypeDef",
     "GetExclusionsPreviewRequestRequestTypeDef",
     "GetTelemetryMetadataRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAssessmentRunsResponseTypeDef",
+    "ListAssessmentTargetsResponseTypeDef",
+    "ListAssessmentTemplatesResponseTypeDef",
+    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
     "ListEventSubscriptionsRequestRequestTypeDef",
+    "ListExclusionsRequestListExclusionsPaginateTypeDef",
     "ListExclusionsRequestRequestTypeDef",
+    "ListExclusionsResponseTypeDef",
+    "ListFindingsResponseTypeDef",
+    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
     "ListRulesPackagesRequestRequestTypeDef",
+    "ListRulesPackagesResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "PrivateIpTypeDef",
     "SecurityGroupTypeDef",
+    "PaginatorConfigTypeDef",
+    "PreviewAgentsRequestPreviewAgentsPaginateTypeDef",
     "PreviewAgentsRequestRequestTypeDef",
     "RegisterCrossAccountAccessRoleRequestRequestTypeDef",
     "RemoveAttributesFromFindingsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAssessmentRunRequestRequestTypeDef",
+    "StartAssessmentRunResponseTypeDef",
     "StopAssessmentRunRequestRequestTypeDef",
     "SubscribeToEventRequestRequestTypeDef",
     "UnsubscribeFromEventRequestRequestTypeDef",
     "UpdateAssessmentTargetRequestRequestTypeDef",
     "AddAttributesToFindingsRequestRequestTypeDef",
     "AssessmentTemplateTypeDef",
     "CreateAssessmentTemplateRequestRequestTypeDef",
     "AddAttributesToFindingsResponseTypeDef",
-    "CreateAssessmentTargetResponseTypeDef",
-    "CreateAssessmentTemplateResponseTypeDef",
-    "CreateExclusionsPreviewResponseTypeDef",
-    "CreateResourceGroupResponseTypeDef",
-    "DescribeCrossAccountAccessRoleResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAssessmentReportResponseTypeDef",
-    "ListAssessmentRunsResponseTypeDef",
-    "ListAssessmentTargetsResponseTypeDef",
-    "ListAssessmentTemplatesResponseTypeDef",
-    "ListExclusionsResponseTypeDef",
-    "ListFindingsResponseTypeDef",
-    "ListRulesPackagesResponseTypeDef",
     "RemoveAttributesFromFindingsResponseTypeDef",
-    "StartAssessmentRunResponseTypeDef",
+    "ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
     "ListAssessmentRunAgentsRequestRequestTypeDef",
     "PreviewAgentsResponseTypeDef",
     "AssessmentRunAgentTypeDef",
     "GetTelemetryMetadataResponseTypeDef",
     "AssessmentTemplateFilterTypeDef",
     "AssessmentRunFilterTypeDef",
     "FindingFilterTypeDef",
     "AssessmentRunTypeDef",
+    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
     "ListAssessmentTargetsRequestRequestTypeDef",
     "DescribeAssessmentTargetsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "SetTagsForResourceRequestRequestTypeDef",
     "CreateResourceGroupRequestRequestTypeDef",
     "ResourceGroupTypeDef",
     "DescribeRulesPackagesResponseTypeDef",
     "SubscriptionTypeDef",
     "ExclusionPreviewTypeDef",
     "ExclusionTypeDef",
-    "ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
-    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
-    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
-    "ListExclusionsRequestListExclusionsPaginateTypeDef",
-    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
-    "PreviewAgentsRequestPreviewAgentsPaginateTypeDef",
     "NetworkInterfaceTypeDef",
     "DescribeAssessmentTemplatesResponseTypeDef",
     "ListAssessmentRunAgentsResponseTypeDef",
     "ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef",
     "ListAssessmentTemplatesRequestRequestTypeDef",
     "ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef",
     "ListAssessmentRunsRequestRequestTypeDef",
@@ -161,36 +162,27 @@
     "_OptionalAttributeTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
+
 class AttributeTypeDef(_RequiredAttributeTypeDef, _OptionalAttributeTypeDef):
     pass
 
+
 FailedItemDetailsTypeDef = TypedDict(
     "FailedItemDetailsTypeDef",
     {
         "failureCode": FailedItemErrorCodeType,
         "retryable": bool,
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
 AgentFilterTypeDef = TypedDict(
     "AgentFilterTypeDef",
     {
         "agentHealths": Sequence[AgentHealthType],
         "agentHealthCodes": Sequence[AgentHealthCodeType],
     },
 )
@@ -211,17 +203,19 @@
         "operatingSystem": str,
         "kernelVersion": str,
         "ipv4Address": str,
     },
     total=False,
 )
 
+
 class AgentPreviewTypeDef(_RequiredAgentPreviewTypeDef, _OptionalAgentPreviewTypeDef):
     pass
 
+
 _RequiredTelemetryMetadataTypeDef = TypedDict(
     "_RequiredTelemetryMetadataTypeDef",
     {
         "messageType": str,
         "count": int,
     },
 )
@@ -229,19 +223,21 @@
     "_OptionalTelemetryMetadataTypeDef",
     {
         "dataSize": int,
     },
     total=False,
 )
 
+
 class TelemetryMetadataTypeDef(
     _RequiredTelemetryMetadataTypeDef, _OptionalTelemetryMetadataTypeDef
 ):
     pass
 
+
 DurationRangeTypeDef = TypedDict(
     "DurationRangeTypeDef",
     {
         "minSeconds": int,
         "maxSeconds": int,
     },
     total=False,
@@ -270,19 +266,21 @@
         "message": str,
         "snsTopicArn": str,
         "snsPublishStatusCode": AssessmentRunNotificationSnsStatusCodeType,
     },
     total=False,
 )
 
+
 class AssessmentRunNotificationTypeDef(
     _RequiredAssessmentRunNotificationTypeDef, _OptionalAssessmentRunNotificationTypeDef
 ):
     pass
 
+
 AssessmentRunStateChangeTypeDef = TypedDict(
     "AssessmentRunStateChangeTypeDef",
     {
         "stateChangedAt": datetime,
         "state": AssessmentRunStateType,
     },
 )
@@ -308,78 +306,118 @@
     "_OptionalAssessmentTargetTypeDef",
     {
         "resourceGroupArn": str,
     },
     total=False,
 )
 
+
 class AssessmentTargetTypeDef(_RequiredAssessmentTargetTypeDef, _OptionalAssessmentTargetTypeDef):
     pass
 
+
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
     "_OptionalTagTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
+
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
+
 _RequiredCreateAssessmentTargetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssessmentTargetRequestRequestTypeDef",
     {
         "assessmentTargetName": str,
     },
 )
 _OptionalCreateAssessmentTargetRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAssessmentTargetRequestRequestTypeDef",
     {
         "resourceGroupArn": str,
     },
     total=False,
 )
 
+
 class CreateAssessmentTargetRequestRequestTypeDef(
     _RequiredCreateAssessmentTargetRequestRequestTypeDef,
     _OptionalCreateAssessmentTargetRequestRequestTypeDef,
 ):
     pass
 
+
+CreateAssessmentTargetResponseTypeDef = TypedDict(
+    "CreateAssessmentTargetResponseTypeDef",
+    {
+        "assessmentTargetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAssessmentTemplateResponseTypeDef = TypedDict(
+    "CreateAssessmentTemplateResponseTypeDef",
+    {
+        "assessmentTemplateArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateExclusionsPreviewRequestRequestTypeDef = TypedDict(
     "CreateExclusionsPreviewRequestRequestTypeDef",
     {
         "assessmentTemplateArn": str,
     },
 )
 
+CreateExclusionsPreviewResponseTypeDef = TypedDict(
+    "CreateExclusionsPreviewResponseTypeDef",
+    {
+        "previewToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredResourceGroupTagTypeDef = TypedDict(
     "_RequiredResourceGroupTagTypeDef",
     {
         "key": str,
     },
 )
 _OptionalResourceGroupTagTypeDef = TypedDict(
     "_OptionalResourceGroupTagTypeDef",
     {
         "value": str,
     },
     total=False,
 )
 
+
 class ResourceGroupTagTypeDef(_RequiredResourceGroupTagTypeDef, _OptionalResourceGroupTagTypeDef):
     pass
 
+
+CreateResourceGroupResponseTypeDef = TypedDict(
+    "CreateResourceGroupResponseTypeDef",
+    {
+        "resourceGroupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAssessmentRunRequestRequestTypeDef = TypedDict(
     "DeleteAssessmentRunRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
 
@@ -414,53 +452,67 @@
 DescribeAssessmentTemplatesRequestRequestTypeDef = TypedDict(
     "DescribeAssessmentTemplatesRequestRequestTypeDef",
     {
         "assessmentTemplateArns": Sequence[str],
     },
 )
 
+DescribeCrossAccountAccessRoleResponseTypeDef = TypedDict(
+    "DescribeCrossAccountAccessRoleResponseTypeDef",
+    {
+        "roleArn": str,
+        "valid": bool,
+        "registeredAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeExclusionsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeExclusionsRequestRequestTypeDef",
     {
         "exclusionArns": Sequence[str],
     },
 )
 _OptionalDescribeExclusionsRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeExclusionsRequestRequestTypeDef",
     {
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
+
 class DescribeExclusionsRequestRequestTypeDef(
     _RequiredDescribeExclusionsRequestRequestTypeDef,
     _OptionalDescribeExclusionsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDescribeFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeFindingsRequestRequestTypeDef",
     {
         "findingArns": Sequence[str],
     },
 )
 _OptionalDescribeFindingsRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeFindingsRequestRequestTypeDef",
     {
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
+
 class DescribeFindingsRequestRequestTypeDef(
     _RequiredDescribeFindingsRequestRequestTypeDef, _OptionalDescribeFindingsRequestRequestTypeDef
 ):
     pass
 
+
 DescribeResourceGroupsRequestRequestTypeDef = TypedDict(
     "DescribeResourceGroupsRequestRequestTypeDef",
     {
         "resourceGroupArns": Sequence[str],
     },
 )
 
@@ -474,20 +526,22 @@
     "_OptionalDescribeRulesPackagesRequestRequestTypeDef",
     {
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
+
 class DescribeRulesPackagesRequestRequestTypeDef(
     _RequiredDescribeRulesPackagesRequestRequestTypeDef,
     _OptionalDescribeRulesPackagesRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredRulesPackageTypeDef = TypedDict(
     "_RequiredRulesPackageTypeDef",
     {
         "arn": str,
         "name": str,
         "version": str,
         "provider": str,
@@ -497,17 +551,26 @@
     "_OptionalRulesPackageTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
+
 class RulesPackageTypeDef(_RequiredRulesPackageTypeDef, _OptionalRulesPackageTypeDef):
     pass
 
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventSubscriptionTypeDef = TypedDict(
     "EventSubscriptionTypeDef",
     {
         "event": InspectorEventType,
         "subscribedAt": datetime,
     },
 )
@@ -532,28 +595,39 @@
     {
         "assessmentRunArn": str,
         "rulesPackageArn": str,
     },
     total=False,
 )
 
+
 class InspectorServiceAttributesTypeDef(
     _RequiredInspectorServiceAttributesTypeDef, _OptionalInspectorServiceAttributesTypeDef
 ):
     pass
 
+
 GetAssessmentReportRequestRequestTypeDef = TypedDict(
     "GetAssessmentReportRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
         "reportFileFormat": ReportFileFormatType,
         "reportType": ReportTypeType,
     },
 )
 
+GetAssessmentReportResponseTypeDef = TypedDict(
+    "GetAssessmentReportResponseTypeDef",
+    {
+        "status": ReportStatusType,
+        "url": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetExclusionsPreviewRequestRequestTypeDef = TypedDict(
     "_RequiredGetExclusionsPreviewRequestRequestTypeDef",
     {
         "assessmentTemplateArn": str,
         "previewToken": str,
     },
 )
@@ -563,47 +637,97 @@
         "nextToken": str,
         "maxResults": int,
         "locale": Literal["EN_US"],
     },
     total=False,
 )
 
+
 class GetExclusionsPreviewRequestRequestTypeDef(
     _RequiredGetExclusionsPreviewRequestRequestTypeDef,
     _OptionalGetExclusionsPreviewRequestRequestTypeDef,
 ):
     pass
 
+
 GetTelemetryMetadataRequestRequestTypeDef = TypedDict(
     "GetTelemetryMetadataRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAssessmentRunsResponseTypeDef = TypedDict(
+    "ListAssessmentRunsResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "assessmentRunArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAssessmentTargetsResponseTypeDef = TypedDict(
+    "ListAssessmentTargetsResponseTypeDef",
+    {
+        "assessmentTargetArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAssessmentTemplatesResponseTypeDef = TypedDict(
+    "ListAssessmentTemplatesResponseTypeDef",
+    {
+        "assessmentTemplateArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef = TypedDict(
+    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
+    {
+        "resourceArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListEventSubscriptionsRequestRequestTypeDef = TypedDict(
     "ListEventSubscriptionsRequestRequestTypeDef",
     {
         "resourceArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
+    "_RequiredListExclusionsRequestListExclusionsPaginateTypeDef",
+    {
+        "assessmentRunArn": str,
+    },
+)
+_OptionalListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
+    "_OptionalListExclusionsRequestListExclusionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListExclusionsRequestListExclusionsPaginateTypeDef(
+    _RequiredListExclusionsRequestListExclusionsPaginateTypeDef,
+    _OptionalListExclusionsRequestListExclusionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListExclusionsRequestRequestTypeDef = TypedDict(
     "_RequiredListExclusionsRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
 _OptionalListExclusionsRequestRequestTypeDef = TypedDict(
@@ -611,28 +735,65 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class ListExclusionsRequestRequestTypeDef(
     _RequiredListExclusionsRequestRequestTypeDef, _OptionalListExclusionsRequestRequestTypeDef
 ):
     pass
 
+
+ListExclusionsResponseTypeDef = TypedDict(
+    "ListExclusionsResponseTypeDef",
+    {
+        "exclusionArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFindingsResponseTypeDef = TypedDict(
+    "ListFindingsResponseTypeDef",
+    {
+        "findingArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListRulesPackagesRequestListRulesPackagesPaginateTypeDef = TypedDict(
+    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRulesPackagesRequestRequestTypeDef = TypedDict(
     "ListRulesPackagesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListRulesPackagesResponseTypeDef = TypedDict(
+    "ListRulesPackagesResponseTypeDef",
+    {
+        "rulesPackageArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
@@ -650,14 +811,46 @@
     {
         "groupName": str,
         "groupId": str,
     },
     total=False,
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
+_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
+    "_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
+    {
+        "previewAgentsArn": str,
+    },
+)
+_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
+    "_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class PreviewAgentsRequestPreviewAgentsPaginateTypeDef(
+    _RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
+    _OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredPreviewAgentsRequestRequestTypeDef = TypedDict(
     "_RequiredPreviewAgentsRequestRequestTypeDef",
     {
         "previewAgentsArn": str,
     },
 )
 _OptionalPreviewAgentsRequestRequestTypeDef = TypedDict(
@@ -665,19 +858,21 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class PreviewAgentsRequestRequestTypeDef(
     _RequiredPreviewAgentsRequestRequestTypeDef, _OptionalPreviewAgentsRequestRequestTypeDef
 ):
     pass
 
+
 RegisterCrossAccountAccessRoleRequestRequestTypeDef = TypedDict(
     "RegisterCrossAccountAccessRoleRequestRequestTypeDef",
     {
         "roleArn": str,
     },
 )
 
@@ -685,53 +880,76 @@
     "RemoveAttributesFromFindingsRequestRequestTypeDef",
     {
         "findingArns": Sequence[str],
         "attributeKeys": Sequence[str],
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
 _RequiredStartAssessmentRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartAssessmentRunRequestRequestTypeDef",
     {
         "assessmentTemplateArn": str,
     },
 )
 _OptionalStartAssessmentRunRequestRequestTypeDef = TypedDict(
     "_OptionalStartAssessmentRunRequestRequestTypeDef",
     {
         "assessmentRunName": str,
     },
     total=False,
 )
 
+
 class StartAssessmentRunRequestRequestTypeDef(
     _RequiredStartAssessmentRunRequestRequestTypeDef,
     _OptionalStartAssessmentRunRequestRequestTypeDef,
 ):
     pass
 
+
+StartAssessmentRunResponseTypeDef = TypedDict(
+    "StartAssessmentRunResponseTypeDef",
+    {
+        "assessmentRunArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopAssessmentRunRequestRequestTypeDef = TypedDict(
     "_RequiredStopAssessmentRunRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
 _OptionalStopAssessmentRunRequestRequestTypeDef = TypedDict(
     "_OptionalStopAssessmentRunRequestRequestTypeDef",
     {
         "stopAction": StopActionType,
     },
     total=False,
 )
 
+
 class StopAssessmentRunRequestRequestTypeDef(
     _RequiredStopAssessmentRunRequestRequestTypeDef, _OptionalStopAssessmentRunRequestRequestTypeDef
 ):
     pass
 
+
 SubscribeToEventRequestRequestTypeDef = TypedDict(
     "SubscribeToEventRequestRequestTypeDef",
     {
         "resourceArn": str,
         "event": InspectorEventType,
         "topicArn": str,
     },
@@ -757,20 +975,22 @@
     "_OptionalUpdateAssessmentTargetRequestRequestTypeDef",
     {
         "resourceGroupArn": str,
     },
     total=False,
 )
 
+
 class UpdateAssessmentTargetRequestRequestTypeDef(
     _RequiredUpdateAssessmentTargetRequestRequestTypeDef,
     _OptionalUpdateAssessmentTargetRequestRequestTypeDef,
 ):
     pass
 
+
 AddAttributesToFindingsRequestRequestTypeDef = TypedDict(
     "AddAttributesToFindingsRequestRequestTypeDef",
     {
         "findingArns": Sequence[str],
         "attributes": Sequence[AttributeTypeDef],
     },
 )
@@ -792,19 +1012,21 @@
     "_OptionalAssessmentTemplateTypeDef",
     {
         "lastAssessmentRunArn": str,
     },
     total=False,
 )
 
+
 class AssessmentTemplateTypeDef(
     _RequiredAssessmentTemplateTypeDef, _OptionalAssessmentTemplateTypeDef
 ):
     pass
 
+
 _RequiredCreateAssessmentTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAssessmentTemplateRequestRequestTypeDef",
     {
         "assessmentTargetArn": str,
         "assessmentTemplateName": str,
         "durationInSeconds": int,
         "rulesPackageArns": Sequence[str],
@@ -814,155 +1036,60 @@
     "_OptionalCreateAssessmentTemplateRequestRequestTypeDef",
     {
         "userAttributesForFindings": Sequence[AttributeTypeDef],
     },
     total=False,
 )
 
+
 class CreateAssessmentTemplateRequestRequestTypeDef(
     _RequiredCreateAssessmentTemplateRequestRequestTypeDef,
     _OptionalCreateAssessmentTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 AddAttributesToFindingsResponseTypeDef = TypedDict(
     "AddAttributesToFindingsResponseTypeDef",
     {
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateAssessmentTargetResponseTypeDef = TypedDict(
-    "CreateAssessmentTargetResponseTypeDef",
-    {
-        "assessmentTargetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAssessmentTemplateResponseTypeDef = TypedDict(
-    "CreateAssessmentTemplateResponseTypeDef",
-    {
-        "assessmentTemplateArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateExclusionsPreviewResponseTypeDef = TypedDict(
-    "CreateExclusionsPreviewResponseTypeDef",
-    {
-        "previewToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResourceGroupResponseTypeDef = TypedDict(
-    "CreateResourceGroupResponseTypeDef",
-    {
-        "resourceGroupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeCrossAccountAccessRoleResponseTypeDef = TypedDict(
-    "DescribeCrossAccountAccessRoleResponseTypeDef",
-    {
-        "roleArn": str,
-        "valid": bool,
-        "registeredAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAssessmentReportResponseTypeDef = TypedDict(
-    "GetAssessmentReportResponseTypeDef",
-    {
-        "status": ReportStatusType,
-        "url": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssessmentRunsResponseTypeDef = TypedDict(
-    "ListAssessmentRunsResponseTypeDef",
-    {
-        "assessmentRunArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAssessmentTargetsResponseTypeDef = TypedDict(
-    "ListAssessmentTargetsResponseTypeDef",
+RemoveAttributesFromFindingsResponseTypeDef = TypedDict(
+    "RemoveAttributesFromFindingsResponseTypeDef",
     {
-        "assessmentTargetArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "failedItems": Dict[str, FailedItemDetailsTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAssessmentTemplatesResponseTypeDef = TypedDict(
-    "ListAssessmentTemplatesResponseTypeDef",
+_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
+    "_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
     {
-        "assessmentTemplateArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "assessmentRunArn": str,
     },
 )
-
-ListExclusionsResponseTypeDef = TypedDict(
-    "ListExclusionsResponseTypeDef",
+_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
+    "_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
     {
-        "exclusionArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "filter": AgentFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-ListFindingsResponseTypeDef = TypedDict(
-    "ListFindingsResponseTypeDef",
-    {
-        "findingArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ListRulesPackagesResponseTypeDef = TypedDict(
-    "ListRulesPackagesResponseTypeDef",
-    {
-        "rulesPackageArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef(
+    _RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
+    _OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
+):
+    pass
 
-RemoveAttributesFromFindingsResponseTypeDef = TypedDict(
-    "RemoveAttributesFromFindingsResponseTypeDef",
-    {
-        "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAssessmentRunResponseTypeDef = TypedDict(
-    "StartAssessmentRunResponseTypeDef",
-    {
-        "assessmentRunArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 _RequiredListAssessmentRunAgentsRequestRequestTypeDef = TypedDict(
     "_RequiredListAssessmentRunAgentsRequestRequestTypeDef",
     {
         "assessmentRunArn": str,
     },
 )
@@ -972,26 +1099,28 @@
         "filter": AgentFilterTypeDef,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class ListAssessmentRunAgentsRequestRequestTypeDef(
     _RequiredListAssessmentRunAgentsRequestRequestTypeDef,
     _OptionalListAssessmentRunAgentsRequestRequestTypeDef,
 ):
     pass
 
+
 PreviewAgentsResponseTypeDef = TypedDict(
     "PreviewAgentsResponseTypeDef",
     {
         "agentPreviews": List[AgentPreviewTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssessmentRunAgentTypeDef = TypedDict(
     "_RequiredAssessmentRunAgentTypeDef",
     {
         "agentId": str,
@@ -1006,24 +1135,26 @@
     {
         "agentHealthDetails": str,
         "autoScalingGroup": str,
     },
     total=False,
 )
 
+
 class AssessmentRunAgentTypeDef(
     _RequiredAssessmentRunAgentTypeDef, _OptionalAssessmentRunAgentTypeDef
 ):
     pass
 
+
 GetTelemetryMetadataResponseTypeDef = TypedDict(
     "GetTelemetryMetadataResponseTypeDef",
     {
         "telemetryMetadata": List[TelemetryMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssessmentTemplateFilterTypeDef = TypedDict(
     "AssessmentTemplateFilterTypeDef",
     {
         "namePattern": str,
@@ -1085,17 +1216,28 @@
     {
         "startedAt": datetime,
         "completedAt": datetime,
     },
     total=False,
 )
 
+
 class AssessmentRunTypeDef(_RequiredAssessmentRunTypeDef, _OptionalAssessmentRunTypeDef):
     pass
 
+
+ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef = TypedDict(
+    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
+    {
+        "filter": AssessmentTargetFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAssessmentTargetsRequestRequestTypeDef = TypedDict(
     "ListAssessmentTargetsRequestRequestTypeDef",
     {
         "filter": AssessmentTargetFilterTypeDef,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1103,23 +1245,23 @@
 )
 
 DescribeAssessmentTargetsResponseTypeDef = TypedDict(
     "DescribeAssessmentTargetsResponseTypeDef",
     {
         "assessmentTargets": List[AssessmentTargetTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredSetTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1129,20 +1271,22 @@
     "_OptionalSetTagsForResourceRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class SetTagsForResourceRequestRequestTypeDef(
     _RequiredSetTagsForResourceRequestRequestTypeDef,
     _OptionalSetTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
+
 CreateResourceGroupRequestRequestTypeDef = TypedDict(
     "CreateResourceGroupRequestRequestTypeDef",
     {
         "resourceGroupTags": Sequence[ResourceGroupTagTypeDef],
     },
 )
 
@@ -1156,15 +1300,15 @@
 )
 
 DescribeRulesPackagesResponseTypeDef = TypedDict(
     "DescribeRulesPackagesResponseTypeDef",
     {
         "rulesPackages": List[RulesPackageTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubscriptionTypeDef = TypedDict(
     "SubscriptionTypeDef",
     {
         "resourceArn": str,
@@ -1186,17 +1330,19 @@
     "_OptionalExclusionPreviewTypeDef",
     {
         "attributes": List[AttributeTypeDef],
     },
     total=False,
 )
 
+
 class ExclusionPreviewTypeDef(_RequiredExclusionPreviewTypeDef, _OptionalExclusionPreviewTypeDef):
     pass
 
+
 _RequiredExclusionTypeDef = TypedDict(
     "_RequiredExclusionTypeDef",
     {
         "arn": str,
         "title": str,
         "description": str,
         "recommendation": str,
@@ -1207,103 +1353,18 @@
     "_OptionalExclusionTypeDef",
     {
         "attributes": List[AttributeTypeDef],
     },
     total=False,
 )
 
-class ExclusionTypeDef(_RequiredExclusionTypeDef, _OptionalExclusionTypeDef):
-    pass
-
-_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
-    "_RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
-    {
-        "assessmentRunArn": str,
-    },
-)
-_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef = TypedDict(
-    "_OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef",
-    {
-        "filter": AgentFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef(
-    _RequiredListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
-    _OptionalListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
-):
-    pass
-
-ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef = TypedDict(
-    "ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef",
-    {
-        "filter": AssessmentTargetFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef = TypedDict(
-    "ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef",
-    {
-        "resourceArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
-_RequiredListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
-    "_RequiredListExclusionsRequestListExclusionsPaginateTypeDef",
-    {
-        "assessmentRunArn": str,
-    },
-)
-_OptionalListExclusionsRequestListExclusionsPaginateTypeDef = TypedDict(
-    "_OptionalListExclusionsRequestListExclusionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListExclusionsRequestListExclusionsPaginateTypeDef(
-    _RequiredListExclusionsRequestListExclusionsPaginateTypeDef,
-    _OptionalListExclusionsRequestListExclusionsPaginateTypeDef,
-):
+class ExclusionTypeDef(_RequiredExclusionTypeDef, _OptionalExclusionTypeDef):
     pass
 
-ListRulesPackagesRequestListRulesPackagesPaginateTypeDef = TypedDict(
-    "ListRulesPackagesRequestListRulesPackagesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
-    "_RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
-    {
-        "previewAgentsArn": str,
-    },
-)
-_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef = TypedDict(
-    "_OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class PreviewAgentsRequestPreviewAgentsPaginateTypeDef(
-    _RequiredPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
-    _OptionalPreviewAgentsRequestPreviewAgentsPaginateTypeDef,
-):
-    pass
 
 NetworkInterfaceTypeDef = TypedDict(
     "NetworkInterfaceTypeDef",
     {
         "networkInterfaceId": str,
         "subnetId": str,
         "vpcId": str,
@@ -1319,33 +1380,33 @@
 )
 
 DescribeAssessmentTemplatesResponseTypeDef = TypedDict(
     "DescribeAssessmentTemplatesResponseTypeDef",
     {
         "assessmentTemplates": List[AssessmentTemplateTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentRunAgentsResponseTypeDef = TypedDict(
     "ListAssessmentRunAgentsResponseTypeDef",
     {
         "assessmentRunAgents": List[AssessmentRunAgentTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef = TypedDict(
     "ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef",
     {
         "assessmentTargetArns": Sequence[str],
         "filter": AssessmentTemplateFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAssessmentTemplatesRequestRequestTypeDef = TypedDict(
     "ListAssessmentTemplatesRequestRequestTypeDef",
     {
@@ -1358,15 +1419,15 @@
 )
 
 ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef = TypedDict(
     "ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef",
     {
         "assessmentTemplateArns": Sequence[str],
         "filter": AssessmentRunFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAssessmentRunsRequestRequestTypeDef = TypedDict(
     "ListAssessmentRunsRequestRequestTypeDef",
     {
@@ -1379,15 +1440,15 @@
 )
 
 ListFindingsRequestListFindingsPaginateTypeDef = TypedDict(
     "ListFindingsRequestListFindingsPaginateTypeDef",
     {
         "assessmentRunArns": Sequence[str],
         "filter": FindingFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFindingsRequestRequestTypeDef = TypedDict(
     "ListFindingsRequestRequestTypeDef",
     {
@@ -1400,52 +1461,52 @@
 )
 
 DescribeAssessmentRunsResponseTypeDef = TypedDict(
     "DescribeAssessmentRunsResponseTypeDef",
     {
         "assessmentRuns": List[AssessmentRunTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeResourceGroupsResponseTypeDef = TypedDict(
     "DescribeResourceGroupsResponseTypeDef",
     {
         "resourceGroups": List[ResourceGroupTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventSubscriptionsResponseTypeDef = TypedDict(
     "ListEventSubscriptionsResponseTypeDef",
     {
         "subscriptions": List[SubscriptionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExclusionsPreviewResponseTypeDef = TypedDict(
     "GetExclusionsPreviewResponseTypeDef",
     {
         "previewStatus": PreviewStatusType,
         "exclusionPreviews": List[ExclusionPreviewTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExclusionsResponseTypeDef = TypedDict(
     "DescribeExclusionsResponseTypeDef",
     {
         "exclusions": Dict[str, ExclusionTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAssetAttributesTypeDef = TypedDict(
     "_RequiredAssetAttributesTypeDef",
     {
         "schemaVersion": int,
@@ -1461,17 +1522,19 @@
         "ipv4Addresses": List[str],
         "tags": List[TagTypeDef],
         "networkInterfaces": List[NetworkInterfaceTypeDef],
     },
     total=False,
 )
 
+
 class AssetAttributesTypeDef(_RequiredAssetAttributesTypeDef, _OptionalAssetAttributesTypeDef):
     pass
 
+
 _RequiredFindingTypeDef = TypedDict(
     "_RequiredFindingTypeDef",
     {
         "arn": str,
         "attributes": List[AttributeTypeDef],
         "userAttributes": List[AttributeTypeDef],
         "createdAt": datetime,
@@ -1494,18 +1557,20 @@
         "numericSeverity": float,
         "confidence": int,
         "indicatorOfCompromise": bool,
     },
     total=False,
 )
 
+
 class FindingTypeDef(_RequiredFindingTypeDef, _OptionalFindingTypeDef):
     pass
 
+
 DescribeFindingsResponseTypeDef = TypedDict(
     "DescribeFindingsResponseTypeDef",
     {
         "findings": List[FindingTypeDef],
         "failedItems": Dict[str, FailedItemDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/PKG-INFO` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-inspector
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Inspector 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Inspector 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-inspector"></a>
 
 # types-aiobotocore-inspector
 
 [![PyPI - types-aiobotocore-inspector](https://img.shields.io/pypi/v/types-aiobotocore-inspector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-inspector)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-inspector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-inspector)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-inspector?color=blue)](https://pypistats.org/packages/types-aiobotocore-inspector)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Inspector 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector)
+[aiobotocore.Inspector 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/inspector.html#Inspector)
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
 [types-aiobotocore-inspector docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/).
 
 See how it helps to find and fix potential bugs:
 
@@ -369,103 +369,103 @@
 `types_aiobotocore_inspector.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_inspector.type_defs import (
     AttributeTypeDef,
     FailedItemDetailsTypeDef,
-    ResponseMetadataTypeDef,
     AgentFilterTypeDef,
     AgentPreviewTypeDef,
     TelemetryMetadataTypeDef,
     DurationRangeTypeDef,
     TimestampRangeTypeDef,
     AssessmentRunNotificationTypeDef,
     AssessmentRunStateChangeTypeDef,
     AssessmentTargetFilterTypeDef,
     AssessmentTargetTypeDef,
     TagTypeDef,
     CreateAssessmentTargetRequestRequestTypeDef,
+    CreateAssessmentTargetResponseTypeDef,
+    CreateAssessmentTemplateResponseTypeDef,
     CreateExclusionsPreviewRequestRequestTypeDef,
+    CreateExclusionsPreviewResponseTypeDef,
     ResourceGroupTagTypeDef,
+    CreateResourceGroupResponseTypeDef,
     DeleteAssessmentRunRequestRequestTypeDef,
     DeleteAssessmentTargetRequestRequestTypeDef,
     DeleteAssessmentTemplateRequestRequestTypeDef,
     DescribeAssessmentRunsRequestRequestTypeDef,
     DescribeAssessmentTargetsRequestRequestTypeDef,
     DescribeAssessmentTemplatesRequestRequestTypeDef,
+    DescribeCrossAccountAccessRoleResponseTypeDef,
     DescribeExclusionsRequestRequestTypeDef,
     DescribeFindingsRequestRequestTypeDef,
     DescribeResourceGroupsRequestRequestTypeDef,
     DescribeRulesPackagesRequestRequestTypeDef,
     RulesPackageTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventSubscriptionTypeDef,
     ScopeTypeDef,
     InspectorServiceAttributesTypeDef,
     GetAssessmentReportRequestRequestTypeDef,
+    GetAssessmentReportResponseTypeDef,
     GetExclusionsPreviewRequestRequestTypeDef,
     GetTelemetryMetadataRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAssessmentRunsResponseTypeDef,
+    ListAssessmentTargetsResponseTypeDef,
+    ListAssessmentTemplatesResponseTypeDef,
+    ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef,
     ListEventSubscriptionsRequestRequestTypeDef,
+    ListExclusionsRequestListExclusionsPaginateTypeDef,
     ListExclusionsRequestRequestTypeDef,
+    ListExclusionsResponseTypeDef,
+    ListFindingsResponseTypeDef,
+    ListRulesPackagesRequestListRulesPackagesPaginateTypeDef,
     ListRulesPackagesRequestRequestTypeDef,
+    ListRulesPackagesResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     PrivateIpTypeDef,
     SecurityGroupTypeDef,
+    PaginatorConfigTypeDef,
+    PreviewAgentsRequestPreviewAgentsPaginateTypeDef,
     PreviewAgentsRequestRequestTypeDef,
     RegisterCrossAccountAccessRoleRequestRequestTypeDef,
     RemoveAttributesFromFindingsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StartAssessmentRunRequestRequestTypeDef,
+    StartAssessmentRunResponseTypeDef,
     StopAssessmentRunRequestRequestTypeDef,
     SubscribeToEventRequestRequestTypeDef,
     UnsubscribeFromEventRequestRequestTypeDef,
     UpdateAssessmentTargetRequestRequestTypeDef,
     AddAttributesToFindingsRequestRequestTypeDef,
     AssessmentTemplateTypeDef,
     CreateAssessmentTemplateRequestRequestTypeDef,
     AddAttributesToFindingsResponseTypeDef,
-    CreateAssessmentTargetResponseTypeDef,
-    CreateAssessmentTemplateResponseTypeDef,
-    CreateExclusionsPreviewResponseTypeDef,
-    CreateResourceGroupResponseTypeDef,
-    DescribeCrossAccountAccessRoleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAssessmentReportResponseTypeDef,
-    ListAssessmentRunsResponseTypeDef,
-    ListAssessmentTargetsResponseTypeDef,
-    ListAssessmentTemplatesResponseTypeDef,
-    ListExclusionsResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListRulesPackagesResponseTypeDef,
     RemoveAttributesFromFindingsResponseTypeDef,
-    StartAssessmentRunResponseTypeDef,
+    ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
     ListAssessmentRunAgentsRequestRequestTypeDef,
     PreviewAgentsResponseTypeDef,
     AssessmentRunAgentTypeDef,
     GetTelemetryMetadataResponseTypeDef,
     AssessmentTemplateFilterTypeDef,
     AssessmentRunFilterTypeDef,
     FindingFilterTypeDef,
     AssessmentRunTypeDef,
+    ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef,
     ListAssessmentTargetsRequestRequestTypeDef,
     DescribeAssessmentTargetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     SetTagsForResourceRequestRequestTypeDef,
     CreateResourceGroupRequestRequestTypeDef,
     ResourceGroupTypeDef,
     DescribeRulesPackagesResponseTypeDef,
     SubscriptionTypeDef,
     ExclusionPreviewTypeDef,
     ExclusionTypeDef,
-    ListAssessmentRunAgentsRequestListAssessmentRunAgentsPaginateTypeDef,
-    ListAssessmentTargetsRequestListAssessmentTargetsPaginateTypeDef,
-    ListEventSubscriptionsRequestListEventSubscriptionsPaginateTypeDef,
-    ListExclusionsRequestListExclusionsPaginateTypeDef,
-    ListRulesPackagesRequestListRulesPackagesPaginateTypeDef,
-    PreviewAgentsRequestPreviewAgentsPaginateTypeDef,
     NetworkInterfaceTypeDef,
     DescribeAssessmentTemplatesResponseTypeDef,
     ListAssessmentRunAgentsResponseTypeDef,
     ListAssessmentTemplatesRequestListAssessmentTemplatesPaginateTypeDef,
     ListAssessmentTemplatesRequestRequestTypeDef,
     ListAssessmentRunsRequestListAssessmentRunsPaginateTypeDef,
     ListAssessmentRunsRequestRequestTypeDef,
@@ -489,43 +489,43 @@
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

### Comparing `types-aiobotocore-inspector-2.5.0.post1/types_aiobotocore_inspector.egg-info/SOURCES.txt` & `types-aiobotocore-inspector-2.5.1/types_aiobotocore_inspector.egg-info/SOURCES.txt`

 * *Files identical despite different names*

