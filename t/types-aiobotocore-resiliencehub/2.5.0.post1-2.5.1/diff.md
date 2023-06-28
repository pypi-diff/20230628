# Comparing `tmp/types-aiobotocore-resiliencehub-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-resiliencehub-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-resiliencehub-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:11 2023, max compression
+gzip compressed data, was "types-aiobotocore-resiliencehub-2.5.1.tar", last modified: Wed Jun 28 01:44:03 2023, max compression
```

## Comparing `types-aiobotocore-resiliencehub-2.5.0.post1.tar` & `types-aiobotocore-resiliencehub-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.471541 types-aiobotocore-resiliencehub-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18850 2023-03-11 12:27:11.467541 types-aiobotocore-resiliencehub-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17255 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:11.471541 types-aiobotocore-resiliencehub-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.467541 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/
--rw-r--r--   0 runner    (1001) docker     (123)      490 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      489 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    41772 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    41712 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10600 2023-03-11 12:22:25.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10598 2023-03-11 12:22:25.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    59682 2023-03-11 12:22:26.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    59579 2023-03-11 12:22:26.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:22.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:11.467541 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18850 2023-03-11 12:27:11.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      836 2023-03-11 12:27:11.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:11.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:11.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:11.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:27:11.000000 types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.190200 types-aiobotocore-resiliencehub-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18938 2023-06-28 01:44:03.182200 types-aiobotocore-resiliencehub-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17349 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:03.190200 types-aiobotocore-resiliencehub-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2160 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.182200 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/
+-rw-r--r--   0 runner    (1001) docker     (123)      490 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41861 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41801 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10908 2023-06-28 01:39:11.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10906 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    60903 2023-06-28 01:39:12.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60798 2023-06-28 01:39:11.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:10.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:03.182200 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18938 2023-06-28 01:44:03.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-28 01:44:03.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:03.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:03.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:44:03.000000 types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/LICENSE` & `types-aiobotocore-resiliencehub-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/PKG-INFO` & `types-aiobotocore-resiliencehub-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resiliencehub
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResilienceHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResilienceHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resiliencehub"></a>
 
 # types-aiobotocore-resiliencehub
 
 [![PyPI - types-aiobotocore-resiliencehub](https://img.shields.io/pypi/v/types-aiobotocore-resiliencehub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resiliencehub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resiliencehub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resiliencehub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resiliencehub?color=blue)](https://pypistats.org/packages/types-aiobotocore-resiliencehub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResilienceHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub)
+[aiobotocore.ResilienceHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub)
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
 [types-aiobotocore-resiliencehub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,14 +291,15 @@
     RecommendationTemplateStatusType,
     RenderRecommendationTypeType,
     ResiliencyPolicyTierType,
     ResourceImportStatusTypeType,
     ResourceImportStrategyTypeType,
     ResourceMappingTypeType,
     ResourceResolutionStatusTypeType,
+    ResourceSourceTypeType,
     SopServiceTypeType,
     TemplateFormatType,
     TestRiskType,
     TestTypeType,
     ResilienceHubServiceName,
     ServiceName,
     ResourceServiceName,
@@ -315,43 +316,52 @@
 ### Typed dictionaries
 
 `types_aiobotocore_resiliencehub.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resiliencehub.type_defs import (
-    ResponseMetadataTypeDef,
     RecommendationItemTypeDef,
     CostTypeDef,
     DisruptionComplianceTypeDef,
     ResiliencyScoreTypeDef,
     AppComponentTypeDef,
+    EksSourceClusterNamespaceTypeDef,
     TerraformSourceTypeDef,
     AppSummaryTypeDef,
     AppTypeDef,
     AppVersionSummaryTypeDef,
     RecommendationDisruptionComplianceTypeDef,
     CreateAppRequestRequestTypeDef,
     CreateAppVersionAppComponentRequestRequestTypeDef,
     LogicalResourceIdTypeDef,
     CreateRecommendationTemplateRequestRequestTypeDef,
     FailurePolicyTypeDef,
     DeleteAppAssessmentRequestRequestTypeDef,
+    DeleteAppAssessmentResponseTypeDef,
     DeleteAppRequestRequestTypeDef,
+    DeleteAppResponseTypeDef,
     DeleteAppVersionAppComponentRequestRequestTypeDef,
     DeleteRecommendationTemplateRequestRequestTypeDef,
+    DeleteRecommendationTemplateResponseTypeDef,
     DeleteResiliencyPolicyRequestRequestTypeDef,
+    DeleteResiliencyPolicyResponseTypeDef,
     DescribeAppAssessmentRequestRequestTypeDef,
     DescribeAppRequestRequestTypeDef,
     DescribeAppVersionAppComponentRequestRequestTypeDef,
     DescribeAppVersionRequestRequestTypeDef,
     DescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef,
+    DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
+    DescribeAppVersionResponseTypeDef,
     DescribeAppVersionTemplateRequestRequestTypeDef,
+    DescribeAppVersionTemplateResponseTypeDef,
     DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef,
+    DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
     DescribeResiliencyPolicyRequestRequestTypeDef,
+    EksSourceTypeDef,
     ListAlarmRecommendationsRequestRequestTypeDef,
     ListAppAssessmentsRequestRequestTypeDef,
     ListAppComponentCompliancesRequestRequestTypeDef,
     ListAppComponentRecommendationsRequestRequestTypeDef,
     ListAppInputSourcesRequestRequestTypeDef,
     ListAppVersionAppComponentsRequestRequestTypeDef,
     ListAppVersionResourceMappingsRequestRequestTypeDef,
@@ -359,70 +369,63 @@
     ListAppVersionsRequestRequestTypeDef,
     ListAppsRequestRequestTypeDef,
     ListRecommendationTemplatesRequestRequestTypeDef,
     ListResiliencyPoliciesRequestRequestTypeDef,
     ListSopRecommendationsRequestRequestTypeDef,
     ListSuggestedResiliencyPoliciesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTestRecommendationsRequestRequestTypeDef,
     ListUnsupportedAppVersionResourcesRequestRequestTypeDef,
     PhysicalResourceIdTypeDef,
     PublishAppVersionRequestRequestTypeDef,
+    PublishAppVersionResponseTypeDef,
     PutDraftAppVersionTemplateRequestRequestTypeDef,
+    PutDraftAppVersionTemplateResponseTypeDef,
     S3LocationTypeDef,
     RemoveDraftAppVersionResourceMappingsRequestRequestTypeDef,
+    RemoveDraftAppVersionResourceMappingsResponseTypeDef,
     ResolveAppVersionResourcesRequestRequestTypeDef,
+    ResolveAppVersionResourcesResponseTypeDef,
     ResourceErrorTypeDef,
+    ResponseMetadataTypeDef,
     StartAppAssessmentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAppRequestRequestTypeDef,
     UpdateAppVersionAppComponentRequestRequestTypeDef,
     UpdateAppVersionRequestRequestTypeDef,
-    DeleteAppAssessmentResponseTypeDef,
-    DeleteAppResponseTypeDef,
-    DeleteRecommendationTemplateResponseTypeDef,
-    DeleteResiliencyPolicyResponseTypeDef,
-    DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
-    DescribeAppVersionResponseTypeDef,
-    DescribeAppVersionTemplateResponseTypeDef,
-    DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PublishAppVersionResponseTypeDef,
-    PutDraftAppVersionTemplateResponseTypeDef,
-    RemoveDraftAppVersionResourceMappingsResponseTypeDef,
-    ResolveAppVersionResourcesResponseTypeDef,
     UpdateAppVersionResponseTypeDef,
     AlarmRecommendationTypeDef,
     SopRecommendationTypeDef,
     TestRecommendationTypeDef,
     AppAssessmentSummaryTypeDef,
     AppComponentComplianceTypeDef,
     CreateAppVersionAppComponentResponseTypeDef,
     DeleteAppVersionAppComponentResponseTypeDef,
     DescribeAppVersionAppComponentResponseTypeDef,
     ListAppVersionAppComponentsResponseTypeDef,
     UpdateAppVersionAppComponentResponseTypeDef,
     AppInputSourceTypeDef,
     DeleteAppInputSourceRequestRequestTypeDef,
-    ImportResourcesToDraftAppVersionRequestRequestTypeDef,
-    ImportResourcesToDraftAppVersionResponseTypeDef,
     ListAppsResponseTypeDef,
     CreateAppResponseTypeDef,
     DescribeAppResponseTypeDef,
     UpdateAppResponseTypeDef,
     ListAppVersionsResponseTypeDef,
     ConfigRecommendationTypeDef,
     CreateAppVersionResourceRequestRequestTypeDef,
     DeleteAppVersionResourceRequestRequestTypeDef,
     DescribeAppVersionResourceRequestRequestTypeDef,
     UpdateAppVersionResourceRequestRequestTypeDef,
     CreateResiliencyPolicyRequestRequestTypeDef,
     ResiliencyPolicyTypeDef,
     UpdateResiliencyPolicyRequestRequestTypeDef,
+    ImportResourcesToDraftAppVersionRequestRequestTypeDef,
+    ImportResourcesToDraftAppVersionResponseTypeDef,
     PhysicalResourceTypeDef,
     ResourceMappingTypeDef,
     UnsupportedResourceTypeDef,
     RecommendationTemplateTypeDef,
     ResourceErrorsDetailsTypeDef,
     ListAlarmRecommendationsResponseTypeDef,
     ListSopRecommendationsResponseTypeDef,
@@ -451,54 +454,54 @@
     AppAssessmentTypeDef,
     ListAppComponentRecommendationsResponseTypeDef,
     DescribeAppAssessmentResponseTypeDef,
     StartAppAssessmentResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> RecommendationItemTypeDef:
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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/README.md` & `types-aiobotocore-resiliencehub-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-resiliencehub"></a>
 
 # types-aiobotocore-resiliencehub
 
 [![PyPI - types-aiobotocore-resiliencehub](https://img.shields.io/pypi/v/types-aiobotocore-resiliencehub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resiliencehub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resiliencehub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resiliencehub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resiliencehub?color=blue)](https://pypistats.org/packages/types-aiobotocore-resiliencehub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResilienceHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub)
+[aiobotocore.ResilienceHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub)
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
 [types-aiobotocore-resiliencehub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -258,14 +258,15 @@
     RecommendationTemplateStatusType,
     RenderRecommendationTypeType,
     ResiliencyPolicyTierType,
     ResourceImportStatusTypeType,
     ResourceImportStrategyTypeType,
     ResourceMappingTypeType,
     ResourceResolutionStatusTypeType,
+    ResourceSourceTypeType,
     SopServiceTypeType,
     TemplateFormatType,
     TestRiskType,
     TestTypeType,
     ResilienceHubServiceName,
     ServiceName,
     ResourceServiceName,
@@ -282,43 +283,52 @@
 ### Typed dictionaries
 
 `types_aiobotocore_resiliencehub.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resiliencehub.type_defs import (
-    ResponseMetadataTypeDef,
     RecommendationItemTypeDef,
     CostTypeDef,
     DisruptionComplianceTypeDef,
     ResiliencyScoreTypeDef,
     AppComponentTypeDef,
+    EksSourceClusterNamespaceTypeDef,
     TerraformSourceTypeDef,
     AppSummaryTypeDef,
     AppTypeDef,
     AppVersionSummaryTypeDef,
     RecommendationDisruptionComplianceTypeDef,
     CreateAppRequestRequestTypeDef,
     CreateAppVersionAppComponentRequestRequestTypeDef,
     LogicalResourceIdTypeDef,
     CreateRecommendationTemplateRequestRequestTypeDef,
     FailurePolicyTypeDef,
     DeleteAppAssessmentRequestRequestTypeDef,
+    DeleteAppAssessmentResponseTypeDef,
     DeleteAppRequestRequestTypeDef,
+    DeleteAppResponseTypeDef,
     DeleteAppVersionAppComponentRequestRequestTypeDef,
     DeleteRecommendationTemplateRequestRequestTypeDef,
+    DeleteRecommendationTemplateResponseTypeDef,
     DeleteResiliencyPolicyRequestRequestTypeDef,
+    DeleteResiliencyPolicyResponseTypeDef,
     DescribeAppAssessmentRequestRequestTypeDef,
     DescribeAppRequestRequestTypeDef,
     DescribeAppVersionAppComponentRequestRequestTypeDef,
     DescribeAppVersionRequestRequestTypeDef,
     DescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef,
+    DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
+    DescribeAppVersionResponseTypeDef,
     DescribeAppVersionTemplateRequestRequestTypeDef,
+    DescribeAppVersionTemplateResponseTypeDef,
     DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef,
+    DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
     DescribeResiliencyPolicyRequestRequestTypeDef,
+    EksSourceTypeDef,
     ListAlarmRecommendationsRequestRequestTypeDef,
     ListAppAssessmentsRequestRequestTypeDef,
     ListAppComponentCompliancesRequestRequestTypeDef,
     ListAppComponentRecommendationsRequestRequestTypeDef,
     ListAppInputSourcesRequestRequestTypeDef,
     ListAppVersionAppComponentsRequestRequestTypeDef,
     ListAppVersionResourceMappingsRequestRequestTypeDef,
@@ -326,70 +336,63 @@
     ListAppVersionsRequestRequestTypeDef,
     ListAppsRequestRequestTypeDef,
     ListRecommendationTemplatesRequestRequestTypeDef,
     ListResiliencyPoliciesRequestRequestTypeDef,
     ListSopRecommendationsRequestRequestTypeDef,
     ListSuggestedResiliencyPoliciesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTestRecommendationsRequestRequestTypeDef,
     ListUnsupportedAppVersionResourcesRequestRequestTypeDef,
     PhysicalResourceIdTypeDef,
     PublishAppVersionRequestRequestTypeDef,
+    PublishAppVersionResponseTypeDef,
     PutDraftAppVersionTemplateRequestRequestTypeDef,
+    PutDraftAppVersionTemplateResponseTypeDef,
     S3LocationTypeDef,
     RemoveDraftAppVersionResourceMappingsRequestRequestTypeDef,
+    RemoveDraftAppVersionResourceMappingsResponseTypeDef,
     ResolveAppVersionResourcesRequestRequestTypeDef,
+    ResolveAppVersionResourcesResponseTypeDef,
     ResourceErrorTypeDef,
+    ResponseMetadataTypeDef,
     StartAppAssessmentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAppRequestRequestTypeDef,
     UpdateAppVersionAppComponentRequestRequestTypeDef,
     UpdateAppVersionRequestRequestTypeDef,
-    DeleteAppAssessmentResponseTypeDef,
-    DeleteAppResponseTypeDef,
-    DeleteRecommendationTemplateResponseTypeDef,
-    DeleteResiliencyPolicyResponseTypeDef,
-    DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
-    DescribeAppVersionResponseTypeDef,
-    DescribeAppVersionTemplateResponseTypeDef,
-    DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PublishAppVersionResponseTypeDef,
-    PutDraftAppVersionTemplateResponseTypeDef,
-    RemoveDraftAppVersionResourceMappingsResponseTypeDef,
-    ResolveAppVersionResourcesResponseTypeDef,
     UpdateAppVersionResponseTypeDef,
     AlarmRecommendationTypeDef,
     SopRecommendationTypeDef,
     TestRecommendationTypeDef,
     AppAssessmentSummaryTypeDef,
     AppComponentComplianceTypeDef,
     CreateAppVersionAppComponentResponseTypeDef,
     DeleteAppVersionAppComponentResponseTypeDef,
     DescribeAppVersionAppComponentResponseTypeDef,
     ListAppVersionAppComponentsResponseTypeDef,
     UpdateAppVersionAppComponentResponseTypeDef,
     AppInputSourceTypeDef,
     DeleteAppInputSourceRequestRequestTypeDef,
-    ImportResourcesToDraftAppVersionRequestRequestTypeDef,
-    ImportResourcesToDraftAppVersionResponseTypeDef,
     ListAppsResponseTypeDef,
     CreateAppResponseTypeDef,
     DescribeAppResponseTypeDef,
     UpdateAppResponseTypeDef,
     ListAppVersionsResponseTypeDef,
     ConfigRecommendationTypeDef,
     CreateAppVersionResourceRequestRequestTypeDef,
     DeleteAppVersionResourceRequestRequestTypeDef,
     DescribeAppVersionResourceRequestRequestTypeDef,
     UpdateAppVersionResourceRequestRequestTypeDef,
     CreateResiliencyPolicyRequestRequestTypeDef,
     ResiliencyPolicyTypeDef,
     UpdateResiliencyPolicyRequestRequestTypeDef,
+    ImportResourcesToDraftAppVersionRequestRequestTypeDef,
+    ImportResourcesToDraftAppVersionResponseTypeDef,
     PhysicalResourceTypeDef,
     ResourceMappingTypeDef,
     UnsupportedResourceTypeDef,
     RecommendationTemplateTypeDef,
     ResourceErrorsDetailsTypeDef,
     ListAlarmRecommendationsResponseTypeDef,
     ListSopRecommendationsResponseTypeDef,
@@ -418,54 +421,54 @@
     AppAssessmentTypeDef,
     ListAppComponentRecommendationsResponseTypeDef,
     DescribeAppAssessmentResponseTypeDef,
     StartAppAssessmentResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> RecommendationItemTypeDef:
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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/setup.py` & `types-aiobotocore-resiliencehub-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-resiliencehub.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-resiliencehub",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_resiliencehub"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ResilienceHub 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ResilienceHub 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/"
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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/__main__.py` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/__main__.py`

 * *Files 11% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ResilienceHub 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ResilienceHub 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub\nOther"
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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/client.py` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -51,14 +51,16 @@
     DescribeAppVersionAppComponentResponseTypeDef,
     DescribeAppVersionResourceResponseTypeDef,
     DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
     DescribeAppVersionResponseTypeDef,
     DescribeAppVersionTemplateResponseTypeDef,
     DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
     DescribeResiliencyPolicyResponseTypeDef,
+    EksSourceClusterNamespaceTypeDef,
+    EksSourceTypeDef,
     FailurePolicyTypeDef,
     ImportResourcesToDraftAppVersionResponseTypeDef,
     ListAlarmRecommendationsResponseTypeDef,
     ListAppAssessmentsResponseTypeDef,
     ListAppComponentCompliancesResponseTypeDef,
     ListAppComponentRecommendationsResponseTypeDef,
     ListAppInputSourcesResponseTypeDef,
@@ -161,15 +163,15 @@
         assessmentSchedule: AppAssessmentScheduleTypeType = ...,
         clientToken: str = ...,
         description: str = ...,
         policyArn: str = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateAppResponseTypeDef:
         """
-        Creates an AWS Resilience Hub application.
+        Creates an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_app)
         """
 
     async def create_app_version_app_component(
         self,
@@ -178,36 +180,36 @@
         name: str,
         type: str,
         additionalInfo: Mapping[str, Sequence[str]] = ...,
         clientToken: str = ...,
         id: str = ...
     ) -> CreateAppVersionAppComponentResponseTypeDef:
         """
-        Creates a new Application Component in the AWS Resilience Hub application.
+        Creates a new Application Component in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_app_version_app_component)
         """
 
     async def create_app_version_resource(
         self,
         *,
         appArn: str,
         appComponents: Sequence[str],
         logicalResourceId: LogicalResourceIdTypeDef,
         physicalResourceId: str,
-        resourceName: str,
         resourceType: str,
         additionalInfo: Mapping[str, Sequence[str]] = ...,
         awsAccountId: str = ...,
         awsRegion: str = ...,
-        clientToken: str = ...
+        clientToken: str = ...,
+        resourceName: str = ...
     ) -> CreateAppVersionResourceResponseTypeDef:
         """
-        Adds a resource to the AWS Resilience Hub applicationand assigns it to the
+        Adds a resource to the Resilience Hub application and assigns it to the
         specified Application Components.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_app_version_resource)
         """
 
     async def create_recommendation_template(
@@ -219,15 +221,15 @@
         clientToken: str = ...,
         format: TemplateFormatType = ...,
         recommendationIds: Sequence[str] = ...,
         recommendationTypes: Sequence[RenderRecommendationTypeType] = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateRecommendationTemplateResponseTypeDef:
         """
-        Creates a new recommendation template for the AWS Resilience Hub application.
+        Creates a new recommendation template for the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_recommendation_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_recommendation_template)
         """
 
     async def create_resiliency_policy(
         self,
@@ -247,51 +249,52 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_resiliency_policy)
         """
 
     async def delete_app(
         self, *, appArn: str, clientToken: str = ..., forceDelete: bool = ...
     ) -> DeleteAppResponseTypeDef:
         """
-        Deletes an AWS Resilience Hub application.
+        Deletes an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app)
         """
 
     async def delete_app_assessment(
         self, *, assessmentArn: str, clientToken: str = ...
     ) -> DeleteAppAssessmentResponseTypeDef:
         """
-        Deletes an AWS Resilience Hub application assessment.
+        Deletes an Resilience Hub application assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_assessment)
         """
 
     async def delete_app_input_source(
         self,
         *,
         appArn: str,
         clientToken: str = ...,
+        eksSourceClusterNamespace: EksSourceClusterNamespaceTypeDef = ...,
         sourceArn: str = ...,
         terraformSource: TerraformSourceTypeDef = ...
     ) -> DeleteAppInputSourceResponseTypeDef:
         """
-        Deletes the input source and all of its imported resources from the AWS
-        Resilience Hub application.
+        Deletes the input source and all of its imported resources from the Resilience
+        Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_input_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_input_source)
         """
 
     async def delete_app_version_app_component(
         self, *, appArn: str, id: str, clientToken: str = ...
     ) -> DeleteAppVersionAppComponentResponseTypeDef:
         """
-        Deletes an Application Component from the AWS Resilience Hub application.
+        Deletes an Application Component from the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_version_app_component)
         """
 
     async def delete_app_version_resource(
         self,
@@ -301,15 +304,15 @@
         awsRegion: str = ...,
         clientToken: str = ...,
         logicalResourceId: LogicalResourceIdTypeDef = ...,
         physicalResourceId: str = ...,
         resourceName: str = ...
     ) -> DeleteAppVersionResourceResponseTypeDef:
         """
-        Deletes a resource from the AWS Resilience Hub application.
+        Deletes a resource from the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_version_resource)
         """
 
     async def delete_recommendation_template(
         self, *, recommendationTemplateArn: str, clientToken: str = ...
@@ -329,45 +332,45 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_resiliency_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_resiliency_policy)
         """
 
     async def describe_app(self, *, appArn: str) -> DescribeAppResponseTypeDef:
         """
-        Describes an AWS Resilience Hub application.
+        Describes an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app)
         """
 
     async def describe_app_assessment(
         self, *, assessmentArn: str
     ) -> DescribeAppAssessmentResponseTypeDef:
         """
-        Describes an assessment for an AWS Resilience Hub application.
+        Describes an assessment for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_assessment)
         """
 
     async def describe_app_version(
         self, *, appArn: str, appVersion: str
     ) -> DescribeAppVersionResponseTypeDef:
         """
-        Describes the AWS Resilience Hub application version.
+        Describes the Resilience Hub application version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version)
         """
 
     async def describe_app_version_app_component(
         self, *, appArn: str, appVersion: str, id: str
     ) -> DescribeAppVersionAppComponentResponseTypeDef:
         """
-        Describes an Application Component in the AWS Resilience Hub application.
+        Describes an Application Component in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_app_component)
         """
 
     async def describe_app_version_resource(
         self,
@@ -377,15 +380,15 @@
         awsAccountId: str = ...,
         awsRegion: str = ...,
         logicalResourceId: LogicalResourceIdTypeDef = ...,
         physicalResourceId: str = ...,
         resourceName: str = ...
     ) -> DescribeAppVersionResourceResponseTypeDef:
         """
-        Describes a resource of the AWS Resilience Hub application.
+        Describes a resource of the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_resource)
         """
 
     async def describe_app_version_resources_resolution_status(
         self, *, appArn: str, appVersion: str, resolutionId: str = ...
@@ -398,15 +401,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_resources_resolution_status)
         """
 
     async def describe_app_version_template(
         self, *, appArn: str, appVersion: str
     ) -> DescribeAppVersionTemplateResponseTypeDef:
         """
-        Describes details about an AWS Resilience Hub application.
+        Describes details about an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_template)
         """
 
     async def describe_draft_app_version_resources_import_status(
         self, *, appArn: str
@@ -418,15 +421,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_draft_app_version_resources_import_status)
         """
 
     async def describe_resiliency_policy(
         self, *, policyArn: str
     ) -> DescribeResiliencyPolicyResponseTypeDef:
         """
-        Describes a specified resiliency policy for an AWS Resilience Hub application.
+        Describes a specified resiliency policy for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_resiliency_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_resiliency_policy)
         """
 
     async def generate_presigned_url(
         self,
@@ -442,31 +445,32 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#generate_presigned_url)
         """
 
     async def import_resources_to_draft_app_version(
         self,
         *,
         appArn: str,
+        eksSources: Sequence[EksSourceTypeDef] = ...,
         importStrategy: ResourceImportStrategyTypeType = ...,
         sourceArns: Sequence[str] = ...,
         terraformSources: Sequence[TerraformSourceTypeDef] = ...
     ) -> ImportResourcesToDraftAppVersionResponseTypeDef:
         """
-        Imports resources to AWS Resilience Hub application draft version from different
+        Imports resources to Resilience Hub application draft version from different
         input sources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.import_resources_to_draft_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#import_resources_to_draft_app_version)
         """
 
     async def list_alarm_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAlarmRecommendationsResponseTypeDef:
         """
-        Lists the alarm recommendations for an AWS Resilience Hub application.
+        Lists the alarm recommendations for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_alarm_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_alarm_recommendations)
         """
 
     async def list_app_assessments(
         self,
@@ -477,55 +481,55 @@
         complianceStatus: ComplianceStatusType = ...,
         invoker: AssessmentInvokerType = ...,
         maxResults: int = ...,
         nextToken: str = ...,
         reverseOrder: bool = ...
     ) -> ListAppAssessmentsResponseTypeDef:
         """
-        Lists the assessments for an AWS Resilience Hub application.
+        Lists the assessments for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_assessments)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_assessments)
         """
 
     async def list_app_component_compliances(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppComponentCompliancesResponseTypeDef:
         """
-        Lists the compliances for an AWS Resilience Hub Application Component.
+        Lists the compliances for an Resilience Hub Application Component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_component_compliances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_component_compliances)
         """
 
     async def list_app_component_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppComponentRecommendationsResponseTypeDef:
         """
-        Lists the recommendations for an AWS Resilience Hub Application Component.
+        Lists the recommendations for an Resilience Hub Application Component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_component_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_component_recommendations)
         """
 
     async def list_app_input_sources(
         self, *, appArn: str, appVersion: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppInputSourcesResponseTypeDef:
         """
-        Lists all the input sources of the AWS Resilience Hub application.
+        Lists all the input sources of the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_input_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_input_sources)
         """
 
     async def list_app_version_app_components(
         self, *, appArn: str, appVersion: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppVersionAppComponentsResponseTypeDef:
         """
-        Lists all the Application Components in the AWS Resilience Hub application.
+        Lists all the Application Components in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_version_app_components)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_version_app_components)
         """
 
     async def list_app_version_resource_mappings(
         self, *, appArn: str, appVersion: str, maxResults: int = ..., nextToken: str = ...
@@ -543,35 +547,35 @@
         appArn: str,
         appVersion: str,
         maxResults: int = ...,
         nextToken: str = ...,
         resolutionId: str = ...
     ) -> ListAppVersionResourcesResponseTypeDef:
         """
-        Lists all the resources in an AWS Resilience Hub application.
+        Lists all the resources in an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_version_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_version_resources)
         """
 
     async def list_app_versions(
         self, *, appArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppVersionsResponseTypeDef:
         """
-        Lists the different versions for the AWS Resilience Hub applications.
+        Lists the different versions for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_versions)
         """
 
     async def list_apps(
         self, *, appArn: str = ..., maxResults: int = ..., name: str = ..., nextToken: str = ...
     ) -> ListAppsResponseTypeDef:
         """
-        Lists your AWS Resilience Hub applications.
+        Lists your Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_apps)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_apps)
         """
 
     async def list_recommendation_templates(
         self,
@@ -581,66 +585,66 @@
         name: str = ...,
         nextToken: str = ...,
         recommendationTemplateArn: str = ...,
         reverseOrder: bool = ...,
         status: Sequence[RecommendationTemplateStatusType] = ...
     ) -> ListRecommendationTemplatesResponseTypeDef:
         """
-        Lists the recommendation templates for the AWS Resilience Hub applications.
+        Lists the recommendation templates for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_recommendation_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_recommendation_templates)
         """
 
     async def list_resiliency_policies(
         self, *, maxResults: int = ..., nextToken: str = ..., policyName: str = ...
     ) -> ListResiliencyPoliciesResponseTypeDef:
         """
-        Lists the resiliency policies for the AWS Resilience Hub applications.
+        Lists the resiliency policies for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_resiliency_policies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_resiliency_policies)
         """
 
     async def list_sop_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListSopRecommendationsResponseTypeDef:
         """
-        Lists the standard operating procedure (SOP) recommendations for the AWS
-        Resilience Hub applications.
+        Lists the standard operating procedure (SOP) recommendations for the Resilience
+        Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_sop_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_sop_recommendations)
         """
 
     async def list_suggested_resiliency_policies(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSuggestedResiliencyPoliciesResponseTypeDef:
         """
-        Lists the suggested resiliency policies for the AWS Resilience Hub applications.
+        Lists the suggested resiliency policies for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_suggested_resiliency_policies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_suggested_resiliency_policies)
         """
 
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        Lists the tags for your resources in your AWS Resilience Hub applications.
+        Lists the tags for your resources in your Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_tags_for_resource)
         """
 
     async def list_test_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListTestRecommendationsResponseTypeDef:
         """
-        Lists the test recommendations for the AWS Resilience Hub application.
+        Lists the test recommendations for the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_test_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_test_recommendations)
         """
 
     async def list_unsupported_app_version_resources(
         self,
@@ -648,44 +652,45 @@
         appArn: str,
         appVersion: str,
         maxResults: int = ...,
         nextToken: str = ...,
         resolutionId: str = ...
     ) -> ListUnsupportedAppVersionResourcesResponseTypeDef:
         """
-        Lists the resources that are not currently supported in AWS Resilience Hub.
+        Lists the resources that are not currently supported in Resilience Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_unsupported_app_version_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_unsupported_app_version_resources)
         """
 
     async def publish_app_version(self, *, appArn: str) -> PublishAppVersionResponseTypeDef:
         """
-        Publishes a new version of a specific AWS Resilience Hub application.
+        Publishes a new version of a specific Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.publish_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#publish_app_version)
         """
 
     async def put_draft_app_version_template(
         self, *, appArn: str, appTemplateBody: str
     ) -> PutDraftAppVersionTemplateResponseTypeDef:
         """
-        Adds or updates the app template for an AWS Resilience Hub application draft
+        Adds or updates the app template for an Resilience Hub application draft
         version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.put_draft_app_version_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#put_draft_app_version_template)
         """
 
     async def remove_draft_app_version_resource_mappings(
         self,
         *,
         appArn: str,
         appRegistryAppNames: Sequence[str] = ...,
+        eksSourceNames: Sequence[str] = ...,
         logicalStackNames: Sequence[str] = ...,
         resourceGroupNames: Sequence[str] = ...,
         resourceNames: Sequence[str] = ...,
         terraformSourceNames: Sequence[str] = ...
     ) -> RemoveDraftAppVersionResourceMappingsResponseTypeDef:
         """
         Removes resource mappings from a draft application version.
@@ -752,15 +757,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app)
         """
 
     async def update_app_version(
         self, *, appArn: str, additionalInfo: Mapping[str, Sequence[str]] = ...
     ) -> UpdateAppVersionResponseTypeDef:
         """
-        Updates the AWS Resilience Hub application version.
+        Updates the Resilience Hub application version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.update_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app_version)
         """
 
     async def update_app_version_app_component(
         self,
@@ -768,15 +773,15 @@
         appArn: str,
         id: str,
         additionalInfo: Mapping[str, Sequence[str]] = ...,
         name: str = ...,
         type: str = ...
     ) -> UpdateAppVersionAppComponentResponseTypeDef:
         """
-        Updates an existing Application Component in the AWS Resilience Hub application.
+        Updates an existing Application Component in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.update_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app_version_app_component)
         """
 
     async def update_app_version_resource(
         self,
@@ -789,15 +794,15 @@
         excluded: bool = ...,
         logicalResourceId: LogicalResourceIdTypeDef = ...,
         physicalResourceId: str = ...,
         resourceName: str = ...,
         resourceType: str = ...
     ) -> UpdateAppVersionResourceResponseTypeDef:
         """
-        Updates the resource details in the AWS Resilience Hub application.
+        Updates the resource details in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.update_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app_version_resource)
         """
 
     async def update_resiliency_policy(
         self,
```

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/client.pyi` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -51,14 +51,16 @@
     DescribeAppVersionAppComponentResponseTypeDef,
     DescribeAppVersionResourceResponseTypeDef,
     DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
     DescribeAppVersionResponseTypeDef,
     DescribeAppVersionTemplateResponseTypeDef,
     DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
     DescribeResiliencyPolicyResponseTypeDef,
+    EksSourceClusterNamespaceTypeDef,
+    EksSourceTypeDef,
     FailurePolicyTypeDef,
     ImportResourcesToDraftAppVersionResponseTypeDef,
     ListAlarmRecommendationsResponseTypeDef,
     ListAppAssessmentsResponseTypeDef,
     ListAppComponentCompliancesResponseTypeDef,
     ListAppComponentRecommendationsResponseTypeDef,
     ListAppInputSourcesResponseTypeDef,
@@ -154,15 +156,15 @@
         assessmentSchedule: AppAssessmentScheduleTypeType = ...,
         clientToken: str = ...,
         description: str = ...,
         policyArn: str = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateAppResponseTypeDef:
         """
-        Creates an AWS Resilience Hub application.
+        Creates an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_app)
         """
     async def create_app_version_app_component(
         self,
         *,
@@ -170,35 +172,35 @@
         name: str,
         type: str,
         additionalInfo: Mapping[str, Sequence[str]] = ...,
         clientToken: str = ...,
         id: str = ...
     ) -> CreateAppVersionAppComponentResponseTypeDef:
         """
-        Creates a new Application Component in the AWS Resilience Hub application.
+        Creates a new Application Component in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_app_version_app_component)
         """
     async def create_app_version_resource(
         self,
         *,
         appArn: str,
         appComponents: Sequence[str],
         logicalResourceId: LogicalResourceIdTypeDef,
         physicalResourceId: str,
-        resourceName: str,
         resourceType: str,
         additionalInfo: Mapping[str, Sequence[str]] = ...,
         awsAccountId: str = ...,
         awsRegion: str = ...,
-        clientToken: str = ...
+        clientToken: str = ...,
+        resourceName: str = ...
     ) -> CreateAppVersionResourceResponseTypeDef:
         """
-        Adds a resource to the AWS Resilience Hub applicationand assigns it to the
+        Adds a resource to the Resilience Hub application and assigns it to the
         specified Application Components.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_app_version_resource)
         """
     async def create_recommendation_template(
         self,
@@ -209,15 +211,15 @@
         clientToken: str = ...,
         format: TemplateFormatType = ...,
         recommendationIds: Sequence[str] = ...,
         recommendationTypes: Sequence[RenderRecommendationTypeType] = ...,
         tags: Mapping[str, str] = ...
     ) -> CreateRecommendationTemplateResponseTypeDef:
         """
-        Creates a new recommendation template for the AWS Resilience Hub application.
+        Creates a new recommendation template for the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_recommendation_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_recommendation_template)
         """
     async def create_resiliency_policy(
         self,
         *,
@@ -235,48 +237,49 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.create_resiliency_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#create_resiliency_policy)
         """
     async def delete_app(
         self, *, appArn: str, clientToken: str = ..., forceDelete: bool = ...
     ) -> DeleteAppResponseTypeDef:
         """
-        Deletes an AWS Resilience Hub application.
+        Deletes an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app)
         """
     async def delete_app_assessment(
         self, *, assessmentArn: str, clientToken: str = ...
     ) -> DeleteAppAssessmentResponseTypeDef:
         """
-        Deletes an AWS Resilience Hub application assessment.
+        Deletes an Resilience Hub application assessment.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_assessment)
         """
     async def delete_app_input_source(
         self,
         *,
         appArn: str,
         clientToken: str = ...,
+        eksSourceClusterNamespace: EksSourceClusterNamespaceTypeDef = ...,
         sourceArn: str = ...,
         terraformSource: TerraformSourceTypeDef = ...
     ) -> DeleteAppInputSourceResponseTypeDef:
         """
-        Deletes the input source and all of its imported resources from the AWS
-        Resilience Hub application.
+        Deletes the input source and all of its imported resources from the Resilience
+        Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_input_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_input_source)
         """
     async def delete_app_version_app_component(
         self, *, appArn: str, id: str, clientToken: str = ...
     ) -> DeleteAppVersionAppComponentResponseTypeDef:
         """
-        Deletes an Application Component from the AWS Resilience Hub application.
+        Deletes an Application Component from the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_version_app_component)
         """
     async def delete_app_version_resource(
         self,
         *,
@@ -285,15 +288,15 @@
         awsRegion: str = ...,
         clientToken: str = ...,
         logicalResourceId: LogicalResourceIdTypeDef = ...,
         physicalResourceId: str = ...,
         resourceName: str = ...
     ) -> DeleteAppVersionResourceResponseTypeDef:
         """
-        Deletes a resource from the AWS Resilience Hub application.
+        Deletes a resource from the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_app_version_resource)
         """
     async def delete_recommendation_template(
         self, *, recommendationTemplateArn: str, clientToken: str = ...
     ) -> DeleteRecommendationTemplateResponseTypeDef:
@@ -310,42 +313,42 @@
         Deletes a resiliency policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.delete_resiliency_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#delete_resiliency_policy)
         """
     async def describe_app(self, *, appArn: str) -> DescribeAppResponseTypeDef:
         """
-        Describes an AWS Resilience Hub application.
+        Describes an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app)
         """
     async def describe_app_assessment(
         self, *, assessmentArn: str
     ) -> DescribeAppAssessmentResponseTypeDef:
         """
-        Describes an assessment for an AWS Resilience Hub application.
+        Describes an assessment for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_assessment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_assessment)
         """
     async def describe_app_version(
         self, *, appArn: str, appVersion: str
     ) -> DescribeAppVersionResponseTypeDef:
         """
-        Describes the AWS Resilience Hub application version.
+        Describes the Resilience Hub application version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version)
         """
     async def describe_app_version_app_component(
         self, *, appArn: str, appVersion: str, id: str
     ) -> DescribeAppVersionAppComponentResponseTypeDef:
         """
-        Describes an Application Component in the AWS Resilience Hub application.
+        Describes an Application Component in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_app_component)
         """
     async def describe_app_version_resource(
         self,
         *,
@@ -354,15 +357,15 @@
         awsAccountId: str = ...,
         awsRegion: str = ...,
         logicalResourceId: LogicalResourceIdTypeDef = ...,
         physicalResourceId: str = ...,
         resourceName: str = ...
     ) -> DescribeAppVersionResourceResponseTypeDef:
         """
-        Describes a resource of the AWS Resilience Hub application.
+        Describes a resource of the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_resource)
         """
     async def describe_app_version_resources_resolution_status(
         self, *, appArn: str, appVersion: str, resolutionId: str = ...
     ) -> DescribeAppVersionResourcesResolutionStatusResponseTypeDef:
@@ -373,15 +376,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version_resources_resolution_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_resources_resolution_status)
         """
     async def describe_app_version_template(
         self, *, appArn: str, appVersion: str
     ) -> DescribeAppVersionTemplateResponseTypeDef:
         """
-        Describes details about an AWS Resilience Hub application.
+        Describes details about an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_app_version_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_app_version_template)
         """
     async def describe_draft_app_version_resources_import_status(
         self, *, appArn: str
     ) -> DescribeDraftAppVersionResourcesImportStatusResponseTypeDef:
@@ -391,15 +394,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_draft_app_version_resources_import_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_draft_app_version_resources_import_status)
         """
     async def describe_resiliency_policy(
         self, *, policyArn: str
     ) -> DescribeResiliencyPolicyResponseTypeDef:
         """
-        Describes a specified resiliency policy for an AWS Resilience Hub application.
+        Describes a specified resiliency policy for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.describe_resiliency_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#describe_resiliency_policy)
         """
     async def generate_presigned_url(
         self,
         ClientMethod: str,
@@ -413,30 +416,31 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#generate_presigned_url)
         """
     async def import_resources_to_draft_app_version(
         self,
         *,
         appArn: str,
+        eksSources: Sequence[EksSourceTypeDef] = ...,
         importStrategy: ResourceImportStrategyTypeType = ...,
         sourceArns: Sequence[str] = ...,
         terraformSources: Sequence[TerraformSourceTypeDef] = ...
     ) -> ImportResourcesToDraftAppVersionResponseTypeDef:
         """
-        Imports resources to AWS Resilience Hub application draft version from different
+        Imports resources to Resilience Hub application draft version from different
         input sources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.import_resources_to_draft_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#import_resources_to_draft_app_version)
         """
     async def list_alarm_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAlarmRecommendationsResponseTypeDef:
         """
-        Lists the alarm recommendations for an AWS Resilience Hub application.
+        Lists the alarm recommendations for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_alarm_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_alarm_recommendations)
         """
     async def list_app_assessments(
         self,
         *,
@@ -446,51 +450,51 @@
         complianceStatus: ComplianceStatusType = ...,
         invoker: AssessmentInvokerType = ...,
         maxResults: int = ...,
         nextToken: str = ...,
         reverseOrder: bool = ...
     ) -> ListAppAssessmentsResponseTypeDef:
         """
-        Lists the assessments for an AWS Resilience Hub application.
+        Lists the assessments for an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_assessments)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_assessments)
         """
     async def list_app_component_compliances(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppComponentCompliancesResponseTypeDef:
         """
-        Lists the compliances for an AWS Resilience Hub Application Component.
+        Lists the compliances for an Resilience Hub Application Component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_component_compliances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_component_compliances)
         """
     async def list_app_component_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppComponentRecommendationsResponseTypeDef:
         """
-        Lists the recommendations for an AWS Resilience Hub Application Component.
+        Lists the recommendations for an Resilience Hub Application Component.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_component_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_component_recommendations)
         """
     async def list_app_input_sources(
         self, *, appArn: str, appVersion: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppInputSourcesResponseTypeDef:
         """
-        Lists all the input sources of the AWS Resilience Hub application.
+        Lists all the input sources of the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_input_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_input_sources)
         """
     async def list_app_version_app_components(
         self, *, appArn: str, appVersion: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppVersionAppComponentsResponseTypeDef:
         """
-        Lists all the Application Components in the AWS Resilience Hub application.
+        Lists all the Application Components in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_version_app_components)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_version_app_components)
         """
     async def list_app_version_resource_mappings(
         self, *, appArn: str, appVersion: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppVersionResourceMappingsResponseTypeDef:
@@ -506,33 +510,33 @@
         appArn: str,
         appVersion: str,
         maxResults: int = ...,
         nextToken: str = ...,
         resolutionId: str = ...
     ) -> ListAppVersionResourcesResponseTypeDef:
         """
-        Lists all the resources in an AWS Resilience Hub application.
+        Lists all the resources in an Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_version_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_version_resources)
         """
     async def list_app_versions(
         self, *, appArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListAppVersionsResponseTypeDef:
         """
-        Lists the different versions for the AWS Resilience Hub applications.
+        Lists the different versions for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_app_versions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_app_versions)
         """
     async def list_apps(
         self, *, appArn: str = ..., maxResults: int = ..., name: str = ..., nextToken: str = ...
     ) -> ListAppsResponseTypeDef:
         """
-        Lists your AWS Resilience Hub applications.
+        Lists your Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_apps)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_apps)
         """
     async def list_recommendation_templates(
         self,
         *,
@@ -541,102 +545,103 @@
         name: str = ...,
         nextToken: str = ...,
         recommendationTemplateArn: str = ...,
         reverseOrder: bool = ...,
         status: Sequence[RecommendationTemplateStatusType] = ...
     ) -> ListRecommendationTemplatesResponseTypeDef:
         """
-        Lists the recommendation templates for the AWS Resilience Hub applications.
+        Lists the recommendation templates for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_recommendation_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_recommendation_templates)
         """
     async def list_resiliency_policies(
         self, *, maxResults: int = ..., nextToken: str = ..., policyName: str = ...
     ) -> ListResiliencyPoliciesResponseTypeDef:
         """
-        Lists the resiliency policies for the AWS Resilience Hub applications.
+        Lists the resiliency policies for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_resiliency_policies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_resiliency_policies)
         """
     async def list_sop_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListSopRecommendationsResponseTypeDef:
         """
-        Lists the standard operating procedure (SOP) recommendations for the AWS
-        Resilience Hub applications.
+        Lists the standard operating procedure (SOP) recommendations for the Resilience
+        Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_sop_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_sop_recommendations)
         """
     async def list_suggested_resiliency_policies(
         self, *, maxResults: int = ..., nextToken: str = ...
     ) -> ListSuggestedResiliencyPoliciesResponseTypeDef:
         """
-        Lists the suggested resiliency policies for the AWS Resilience Hub applications.
+        Lists the suggested resiliency policies for the Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_suggested_resiliency_policies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_suggested_resiliency_policies)
         """
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        Lists the tags for your resources in your AWS Resilience Hub applications.
+        Lists the tags for your resources in your Resilience Hub applications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_tags_for_resource)
         """
     async def list_test_recommendations(
         self, *, assessmentArn: str, maxResults: int = ..., nextToken: str = ...
     ) -> ListTestRecommendationsResponseTypeDef:
         """
-        Lists the test recommendations for the AWS Resilience Hub application.
+        Lists the test recommendations for the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_test_recommendations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_test_recommendations)
         """
     async def list_unsupported_app_version_resources(
         self,
         *,
         appArn: str,
         appVersion: str,
         maxResults: int = ...,
         nextToken: str = ...,
         resolutionId: str = ...
     ) -> ListUnsupportedAppVersionResourcesResponseTypeDef:
         """
-        Lists the resources that are not currently supported in AWS Resilience Hub.
+        Lists the resources that are not currently supported in Resilience Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.list_unsupported_app_version_resources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#list_unsupported_app_version_resources)
         """
     async def publish_app_version(self, *, appArn: str) -> PublishAppVersionResponseTypeDef:
         """
-        Publishes a new version of a specific AWS Resilience Hub application.
+        Publishes a new version of a specific Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.publish_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#publish_app_version)
         """
     async def put_draft_app_version_template(
         self, *, appArn: str, appTemplateBody: str
     ) -> PutDraftAppVersionTemplateResponseTypeDef:
         """
-        Adds or updates the app template for an AWS Resilience Hub application draft
+        Adds or updates the app template for an Resilience Hub application draft
         version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.put_draft_app_version_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#put_draft_app_version_template)
         """
     async def remove_draft_app_version_resource_mappings(
         self,
         *,
         appArn: str,
         appRegistryAppNames: Sequence[str] = ...,
+        eksSourceNames: Sequence[str] = ...,
         logicalStackNames: Sequence[str] = ...,
         resourceGroupNames: Sequence[str] = ...,
         resourceNames: Sequence[str] = ...,
         terraformSourceNames: Sequence[str] = ...
     ) -> RemoveDraftAppVersionResourceMappingsResponseTypeDef:
         """
         Removes resource mappings from a draft application version.
@@ -697,30 +702,30 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.update_app)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app)
         """
     async def update_app_version(
         self, *, appArn: str, additionalInfo: Mapping[str, Sequence[str]] = ...
     ) -> UpdateAppVersionResponseTypeDef:
         """
-        Updates the AWS Resilience Hub application version.
+        Updates the Resilience Hub application version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.update_app_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app_version)
         """
     async def update_app_version_app_component(
         self,
         *,
         appArn: str,
         id: str,
         additionalInfo: Mapping[str, Sequence[str]] = ...,
         name: str = ...,
         type: str = ...
     ) -> UpdateAppVersionAppComponentResponseTypeDef:
         """
-        Updates an existing Application Component in the AWS Resilience Hub application.
+        Updates an existing Application Component in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.update_app_version_app_component)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app_version_app_component)
         """
     async def update_app_version_resource(
         self,
         *,
@@ -732,15 +737,15 @@
         excluded: bool = ...,
         logicalResourceId: LogicalResourceIdTypeDef = ...,
         physicalResourceId: str = ...,
         resourceName: str = ...,
         resourceType: str = ...
     ) -> UpdateAppVersionResourceResponseTypeDef:
         """
-        Updates the resource details in the AWS Resilience Hub application.
+        Updates the resource details in the Resilience Hub application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub.Client.update_app_version_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/client/#update_app_version_resource)
         """
     async def update_resiliency_policy(
         self,
         *,
```

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/literals.py` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AlarmTypeType",
     "AppAssessmentScheduleTypeType",
     "AppComplianceStatusTypeType",
     "AppStatusTypeType",
     "AssessmentInvokerType",
     "AssessmentStatusType",
@@ -38,25 +37,25 @@
     "RecommendationTemplateStatusType",
     "RenderRecommendationTypeType",
     "ResiliencyPolicyTierType",
     "ResourceImportStatusTypeType",
     "ResourceImportStrategyTypeType",
     "ResourceMappingTypeType",
     "ResourceResolutionStatusTypeType",
+    "ResourceSourceTypeType",
     "SopServiceTypeType",
     "TemplateFormatType",
     "TestRiskType",
     "TestTypeType",
     "ResilienceHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 AlarmTypeType = Literal["Canary", "Composite", "Event", "Logs", "Metric"]
 AppAssessmentScheduleTypeType = Literal["Daily", "Disabled"]
 AppComplianceStatusTypeType = Literal[
     "ChangesDetected", "NotAssessed", "PolicyBreached", "PolicyMet"
 ]
 AppStatusTypeType = Literal["Active", "Deleting"]
 AssessmentInvokerType = Literal["System", "User"]
@@ -85,17 +84,18 @@
 RenderRecommendationTypeType = Literal["Alarm", "Sop", "Test"]
 ResiliencyPolicyTierType = Literal[
     "CoreServices", "Critical", "Important", "MissionCritical", "NonCritical"
 ]
 ResourceImportStatusTypeType = Literal["Failed", "InProgress", "Pending", "Success"]
 ResourceImportStrategyTypeType = Literal["AddOnly", "ReplaceAll"]
 ResourceMappingTypeType = Literal[
-    "AppRegistryApp", "CfnStack", "Resource", "ResourceGroup", "Terraform"
+    "AppRegistryApp", "CfnStack", "EKS", "Resource", "ResourceGroup", "Terraform"
 ]
 ResourceResolutionStatusTypeType = Literal["Failed", "InProgress", "Pending", "Success"]
+ResourceSourceTypeType = Literal["AppTemplate", "Discovered"]
 SopServiceTypeType = Literal["SSM"]
 TemplateFormatType = Literal["CfnJson", "CfnYaml"]
 TestRiskType = Literal["High", "Medium", "Small"]
 TestTypeType = Literal["AZ", "Hardware", "Region", "Software"]
 ResilienceHubServiceName = Literal["resiliencehub"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -155,14 +155,15 @@
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
@@ -241,14 +242,15 @@
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
@@ -259,14 +261,15 @@
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
@@ -302,14 +305,15 @@
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
@@ -328,16 +332,19 @@
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
@@ -421,15 +428,17 @@
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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/literals.pyi` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AlarmTypeType",
     "AppAssessmentScheduleTypeType",
     "AppComplianceStatusTypeType",
     "AppStatusTypeType",
     "AssessmentInvokerType",
     "AssessmentStatusType",
@@ -37,24 +38,26 @@
     "RecommendationTemplateStatusType",
     "RenderRecommendationTypeType",
     "ResiliencyPolicyTierType",
     "ResourceImportStatusTypeType",
     "ResourceImportStrategyTypeType",
     "ResourceMappingTypeType",
     "ResourceResolutionStatusTypeType",
+    "ResourceSourceTypeType",
     "SopServiceTypeType",
     "TemplateFormatType",
     "TestRiskType",
     "TestTypeType",
     "ResilienceHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 AlarmTypeType = Literal["Canary", "Composite", "Event", "Logs", "Metric"]
 AppAssessmentScheduleTypeType = Literal["Daily", "Disabled"]
 AppComplianceStatusTypeType = Literal[
     "ChangesDetected", "NotAssessed", "PolicyBreached", "PolicyMet"
 ]
 AppStatusTypeType = Literal["Active", "Deleting"]
 AssessmentInvokerType = Literal["System", "User"]
@@ -83,17 +86,18 @@
 RenderRecommendationTypeType = Literal["Alarm", "Sop", "Test"]
 ResiliencyPolicyTierType = Literal[
     "CoreServices", "Critical", "Important", "MissionCritical", "NonCritical"
 ]
 ResourceImportStatusTypeType = Literal["Failed", "InProgress", "Pending", "Success"]
 ResourceImportStrategyTypeType = Literal["AddOnly", "ReplaceAll"]
 ResourceMappingTypeType = Literal[
-    "AppRegistryApp", "CfnStack", "Resource", "ResourceGroup", "Terraform"
+    "AppRegistryApp", "CfnStack", "EKS", "Resource", "ResourceGroup", "Terraform"
 ]
 ResourceResolutionStatusTypeType = Literal["Failed", "InProgress", "Pending", "Success"]
+ResourceSourceTypeType = Literal["AppTemplate", "Discovered"]
 SopServiceTypeType = Literal["SSM"]
 TemplateFormatType = Literal["CfnJson", "CfnYaml"]
 TestRiskType = Literal["High", "Medium", "Small"]
 TestTypeType = Literal["AZ", "Hardware", "Region", "Software"]
 ResilienceHubServiceName = Literal["resiliencehub"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -153,14 +157,15 @@
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
@@ -239,14 +244,15 @@
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
@@ -257,14 +263,15 @@
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
@@ -300,14 +307,15 @@
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
@@ -326,16 +334,19 @@
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
@@ -419,15 +430,17 @@
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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/type_defs.py` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for resiliencehub service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_resiliencehub.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_resiliencehub.type_defs import RecommendationItemTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: RecommendationItemTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
@@ -34,14 +34,15 @@
     RecommendationTemplateStatusType,
     RenderRecommendationTypeType,
     ResiliencyPolicyTierType,
     ResourceImportStatusTypeType,
     ResourceImportStrategyTypeType,
     ResourceMappingTypeType,
     ResourceResolutionStatusTypeType,
+    ResourceSourceTypeType,
     TemplateFormatType,
     TestRiskType,
     TestTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -50,43 +51,52 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
-    "ResponseMetadataTypeDef",
     "RecommendationItemTypeDef",
     "CostTypeDef",
     "DisruptionComplianceTypeDef",
     "ResiliencyScoreTypeDef",
     "AppComponentTypeDef",
+    "EksSourceClusterNamespaceTypeDef",
     "TerraformSourceTypeDef",
     "AppSummaryTypeDef",
     "AppTypeDef",
     "AppVersionSummaryTypeDef",
     "RecommendationDisruptionComplianceTypeDef",
     "CreateAppRequestRequestTypeDef",
     "CreateAppVersionAppComponentRequestRequestTypeDef",
     "LogicalResourceIdTypeDef",
     "CreateRecommendationTemplateRequestRequestTypeDef",
     "FailurePolicyTypeDef",
     "DeleteAppAssessmentRequestRequestTypeDef",
+    "DeleteAppAssessmentResponseTypeDef",
     "DeleteAppRequestRequestTypeDef",
+    "DeleteAppResponseTypeDef",
     "DeleteAppVersionAppComponentRequestRequestTypeDef",
     "DeleteRecommendationTemplateRequestRequestTypeDef",
+    "DeleteRecommendationTemplateResponseTypeDef",
     "DeleteResiliencyPolicyRequestRequestTypeDef",
+    "DeleteResiliencyPolicyResponseTypeDef",
     "DescribeAppAssessmentRequestRequestTypeDef",
     "DescribeAppRequestRequestTypeDef",
     "DescribeAppVersionAppComponentRequestRequestTypeDef",
     "DescribeAppVersionRequestRequestTypeDef",
     "DescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef",
+    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
+    "DescribeAppVersionResponseTypeDef",
     "DescribeAppVersionTemplateRequestRequestTypeDef",
+    "DescribeAppVersionTemplateResponseTypeDef",
     "DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef",
+    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
     "DescribeResiliencyPolicyRequestRequestTypeDef",
+    "EksSourceTypeDef",
     "ListAlarmRecommendationsRequestRequestTypeDef",
     "ListAppAssessmentsRequestRequestTypeDef",
     "ListAppComponentCompliancesRequestRequestTypeDef",
     "ListAppComponentRecommendationsRequestRequestTypeDef",
     "ListAppInputSourcesRequestRequestTypeDef",
     "ListAppVersionAppComponentsRequestRequestTypeDef",
     "ListAppVersionResourceMappingsRequestRequestTypeDef",
@@ -94,70 +104,63 @@
     "ListAppVersionsRequestRequestTypeDef",
     "ListAppsRequestRequestTypeDef",
     "ListRecommendationTemplatesRequestRequestTypeDef",
     "ListResiliencyPoliciesRequestRequestTypeDef",
     "ListSopRecommendationsRequestRequestTypeDef",
     "ListSuggestedResiliencyPoliciesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListTestRecommendationsRequestRequestTypeDef",
     "ListUnsupportedAppVersionResourcesRequestRequestTypeDef",
     "PhysicalResourceIdTypeDef",
     "PublishAppVersionRequestRequestTypeDef",
+    "PublishAppVersionResponseTypeDef",
     "PutDraftAppVersionTemplateRequestRequestTypeDef",
+    "PutDraftAppVersionTemplateResponseTypeDef",
     "S3LocationTypeDef",
     "RemoveDraftAppVersionResourceMappingsRequestRequestTypeDef",
+    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
     "ResolveAppVersionResourcesRequestRequestTypeDef",
+    "ResolveAppVersionResourcesResponseTypeDef",
     "ResourceErrorTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAppAssessmentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAppRequestRequestTypeDef",
     "UpdateAppVersionAppComponentRequestRequestTypeDef",
     "UpdateAppVersionRequestRequestTypeDef",
-    "DeleteAppAssessmentResponseTypeDef",
-    "DeleteAppResponseTypeDef",
-    "DeleteRecommendationTemplateResponseTypeDef",
-    "DeleteResiliencyPolicyResponseTypeDef",
-    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
-    "DescribeAppVersionResponseTypeDef",
-    "DescribeAppVersionTemplateResponseTypeDef",
-    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PublishAppVersionResponseTypeDef",
-    "PutDraftAppVersionTemplateResponseTypeDef",
-    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
-    "ResolveAppVersionResourcesResponseTypeDef",
     "UpdateAppVersionResponseTypeDef",
     "AlarmRecommendationTypeDef",
     "SopRecommendationTypeDef",
     "TestRecommendationTypeDef",
     "AppAssessmentSummaryTypeDef",
     "AppComponentComplianceTypeDef",
     "CreateAppVersionAppComponentResponseTypeDef",
     "DeleteAppVersionAppComponentResponseTypeDef",
     "DescribeAppVersionAppComponentResponseTypeDef",
     "ListAppVersionAppComponentsResponseTypeDef",
     "UpdateAppVersionAppComponentResponseTypeDef",
     "AppInputSourceTypeDef",
     "DeleteAppInputSourceRequestRequestTypeDef",
-    "ImportResourcesToDraftAppVersionRequestRequestTypeDef",
-    "ImportResourcesToDraftAppVersionResponseTypeDef",
     "ListAppsResponseTypeDef",
     "CreateAppResponseTypeDef",
     "DescribeAppResponseTypeDef",
     "UpdateAppResponseTypeDef",
     "ListAppVersionsResponseTypeDef",
     "ConfigRecommendationTypeDef",
     "CreateAppVersionResourceRequestRequestTypeDef",
     "DeleteAppVersionResourceRequestRequestTypeDef",
     "DescribeAppVersionResourceRequestRequestTypeDef",
     "UpdateAppVersionResourceRequestRequestTypeDef",
     "CreateResiliencyPolicyRequestRequestTypeDef",
     "ResiliencyPolicyTypeDef",
     "UpdateResiliencyPolicyRequestRequestTypeDef",
+    "ImportResourcesToDraftAppVersionRequestRequestTypeDef",
+    "ImportResourcesToDraftAppVersionResponseTypeDef",
     "PhysicalResourceTypeDef",
     "ResourceMappingTypeDef",
     "UnsupportedResourceTypeDef",
     "RecommendationTemplateTypeDef",
     "ResourceErrorsDetailsTypeDef",
     "ListAlarmRecommendationsResponseTypeDef",
     "ListSopRecommendationsResponseTypeDef",
@@ -185,25 +188,14 @@
     "ListRecommendationTemplatesResponseTypeDef",
     "AppAssessmentTypeDef",
     "ListAppComponentRecommendationsResponseTypeDef",
     "DescribeAppAssessmentResponseTypeDef",
     "StartAppAssessmentResponseTypeDef",
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
 RecommendationItemTypeDef = TypedDict(
     "RecommendationItemTypeDef",
     {
         "alreadyImplemented": bool,
         "resourceId": str,
         "targetAccountId": str,
         "targetRegion": str,
@@ -274,14 +266,22 @@
 )
 
 
 class AppComponentTypeDef(_RequiredAppComponentTypeDef, _OptionalAppComponentTypeDef):
     pass
 
 
+EksSourceClusterNamespaceTypeDef = TypedDict(
+    "EksSourceClusterNamespaceTypeDef",
+    {
+        "eksClusterArn": str,
+        "namespace": str,
+    },
+)
+
 TerraformSourceTypeDef = TypedDict(
     "TerraformSourceTypeDef",
     {
         "s3StateFileUrl": str,
     },
 )
 
@@ -427,14 +427,15 @@
     {
         "identifier": str,
     },
 )
 _OptionalLogicalResourceIdTypeDef = TypedDict(
     "_OptionalLogicalResourceIdTypeDef",
     {
+        "eksSourceName": str,
         "logicalStackName": str,
         "resourceGroupName": str,
         "terraformSourceName": str,
     },
     total=False,
 )
 
@@ -499,14 +500,23 @@
 class DeleteAppAssessmentRequestRequestTypeDef(
     _RequiredDeleteAppAssessmentRequestRequestTypeDef,
     _OptionalDeleteAppAssessmentRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteAppAssessmentResponseTypeDef = TypedDict(
+    "DeleteAppAssessmentResponseTypeDef",
+    {
+        "assessmentArn": str,
+        "assessmentStatus": AssessmentStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteAppRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAppRequestRequestTypeDef",
     {
         "appArn": str,
     },
 )
 _OptionalDeleteAppRequestRequestTypeDef = TypedDict(
@@ -521,14 +531,22 @@
 
 class DeleteAppRequestRequestTypeDef(
     _RequiredDeleteAppRequestRequestTypeDef, _OptionalDeleteAppRequestRequestTypeDef
 ):
     pass
 
 
+DeleteAppResponseTypeDef = TypedDict(
+    "DeleteAppResponseTypeDef",
+    {
+        "appArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteAppVersionAppComponentRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAppVersionAppComponentRequestRequestTypeDef",
     {
         "appArn": str,
         "id": str,
     },
 )
@@ -566,14 +584,23 @@
 class DeleteRecommendationTemplateRequestRequestTypeDef(
     _RequiredDeleteRecommendationTemplateRequestRequestTypeDef,
     _OptionalDeleteRecommendationTemplateRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteRecommendationTemplateResponseTypeDef = TypedDict(
+    "DeleteRecommendationTemplateResponseTypeDef",
+    {
+        "recommendationTemplateArn": str,
+        "status": RecommendationTemplateStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteResiliencyPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResiliencyPolicyRequestRequestTypeDef",
     {
         "policyArn": str,
     },
 )
 _OptionalDeleteResiliencyPolicyRequestRequestTypeDef = TypedDict(
@@ -588,14 +615,22 @@
 class DeleteResiliencyPolicyRequestRequestTypeDef(
     _RequiredDeleteResiliencyPolicyRequestRequestTypeDef,
     _OptionalDeleteResiliencyPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteResiliencyPolicyResponseTypeDef = TypedDict(
+    "DeleteResiliencyPolicyResponseTypeDef",
+    {
+        "policyArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeAppAssessmentRequestRequestTypeDef = TypedDict(
     "DescribeAppAssessmentRequestRequestTypeDef",
     {
         "assessmentArn": str,
     },
 )
 
@@ -642,36 +677,88 @@
 class DescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef(
     _RequiredDescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef,
     _OptionalDescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeAppVersionResourcesResolutionStatusResponseTypeDef = TypedDict(
+    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "errorMessage": str,
+        "resolutionId": str,
+        "status": ResourceResolutionStatusTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAppVersionResponseTypeDef = TypedDict(
+    "DescribeAppVersionResponseTypeDef",
+    {
+        "additionalInfo": Dict[str, List[str]],
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeAppVersionTemplateRequestRequestTypeDef = TypedDict(
     "DescribeAppVersionTemplateRequestRequestTypeDef",
     {
         "appArn": str,
         "appVersion": str,
     },
 )
 
+DescribeAppVersionTemplateResponseTypeDef = TypedDict(
+    "DescribeAppVersionTemplateResponseTypeDef",
+    {
+        "appArn": str,
+        "appTemplateBody": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef = TypedDict(
     "DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef",
     {
         "appArn": str,
     },
 )
 
+DescribeDraftAppVersionResourcesImportStatusResponseTypeDef = TypedDict(
+    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "errorMessage": str,
+        "status": ResourceImportStatusTypeType,
+        "statusChangeTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeResiliencyPolicyRequestRequestTypeDef = TypedDict(
     "DescribeResiliencyPolicyRequestRequestTypeDef",
     {
         "policyArn": str,
     },
 )
 
+EksSourceTypeDef = TypedDict(
+    "EksSourceTypeDef",
+    {
+        "eksClusterArn": str,
+        "namespaces": Sequence[str],
+    },
+)
+
 _RequiredListAlarmRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredListAlarmRecommendationsRequestRequestTypeDef",
     {
         "assessmentArn": str,
     },
 )
 _OptionalListAlarmRecommendationsRequestRequestTypeDef = TypedDict(
@@ -954,14 +1041,22 @@
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
 _RequiredListTestRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredListTestRecommendationsRequestRequestTypeDef",
     {
         "assessmentArn": str,
     },
 )
 _OptionalListTestRecommendationsRequestRequestTypeDef = TypedDict(
@@ -1032,22 +1127,40 @@
 PublishAppVersionRequestRequestTypeDef = TypedDict(
     "PublishAppVersionRequestRequestTypeDef",
     {
         "appArn": str,
     },
 )
 
+PublishAppVersionResponseTypeDef = TypedDict(
+    "PublishAppVersionResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutDraftAppVersionTemplateRequestRequestTypeDef = TypedDict(
     "PutDraftAppVersionTemplateRequestRequestTypeDef",
     {
         "appArn": str,
         "appTemplateBody": str,
     },
 )
 
+PutDraftAppVersionTemplateResponseTypeDef = TypedDict(
+    "PutDraftAppVersionTemplateResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3LocationTypeDef = TypedDict(
     "S3LocationTypeDef",
     {
         "bucket": str,
         "prefix": str,
     },
     total=False,
@@ -1059,14 +1172,15 @@
         "appArn": str,
     },
 )
 _OptionalRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef = TypedDict(
     "_OptionalRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef",
     {
         "appRegistryAppNames": Sequence[str],
+        "eksSourceNames": Sequence[str],
         "logicalStackNames": Sequence[str],
         "resourceGroupNames": Sequence[str],
         "resourceNames": Sequence[str],
         "terraformSourceNames": Sequence[str],
     },
     total=False,
 )
@@ -1075,32 +1189,63 @@
 class RemoveDraftAppVersionResourceMappingsRequestRequestTypeDef(
     _RequiredRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef,
     _OptionalRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef,
 ):
     pass
 
 
+RemoveDraftAppVersionResourceMappingsResponseTypeDef = TypedDict(
+    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResolveAppVersionResourcesRequestRequestTypeDef = TypedDict(
     "ResolveAppVersionResourcesRequestRequestTypeDef",
     {
         "appArn": str,
         "appVersion": str,
     },
 )
 
+ResolveAppVersionResourcesResponseTypeDef = TypedDict(
+    "ResolveAppVersionResourcesResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "resolutionId": str,
+        "status": ResourceResolutionStatusTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceErrorTypeDef = TypedDict(
     "ResourceErrorTypeDef",
     {
         "logicalResourceId": str,
         "physicalResourceId": str,
         "reason": str,
     },
     total=False,
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
 _RequiredStartAppAssessmentRequestRequestTypeDef = TypedDict(
     "_RequiredStartAppAssessmentRequestRequestTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "assessmentName": str,
     },
@@ -1204,145 +1349,21 @@
 
 class UpdateAppVersionRequestRequestTypeDef(
     _RequiredUpdateAppVersionRequestRequestTypeDef, _OptionalUpdateAppVersionRequestRequestTypeDef
 ):
     pass
 
 
-DeleteAppAssessmentResponseTypeDef = TypedDict(
-    "DeleteAppAssessmentResponseTypeDef",
-    {
-        "assessmentArn": str,
-        "assessmentStatus": AssessmentStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteAppResponseTypeDef = TypedDict(
-    "DeleteAppResponseTypeDef",
-    {
-        "appArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRecommendationTemplateResponseTypeDef = TypedDict(
-    "DeleteRecommendationTemplateResponseTypeDef",
-    {
-        "recommendationTemplateArn": str,
-        "status": RecommendationTemplateStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteResiliencyPolicyResponseTypeDef = TypedDict(
-    "DeleteResiliencyPolicyResponseTypeDef",
-    {
-        "policyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppVersionResourcesResolutionStatusResponseTypeDef = TypedDict(
-    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "errorMessage": str,
-        "resolutionId": str,
-        "status": ResourceResolutionStatusTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppVersionResponseTypeDef = TypedDict(
-    "DescribeAppVersionResponseTypeDef",
-    {
-        "additionalInfo": Dict[str, List[str]],
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppVersionTemplateResponseTypeDef = TypedDict(
-    "DescribeAppVersionTemplateResponseTypeDef",
-    {
-        "appArn": str,
-        "appTemplateBody": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDraftAppVersionResourcesImportStatusResponseTypeDef = TypedDict(
-    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "errorMessage": str,
-        "status": ResourceImportStatusTypeType,
-        "statusChangeTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PublishAppVersionResponseTypeDef = TypedDict(
-    "PublishAppVersionResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutDraftAppVersionTemplateResponseTypeDef = TypedDict(
-    "PutDraftAppVersionTemplateResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveDraftAppVersionResourceMappingsResponseTypeDef = TypedDict(
-    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResolveAppVersionResourcesResponseTypeDef = TypedDict(
-    "ResolveAppVersionResourcesResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "resolutionId": str,
-        "status": ResourceResolutionStatusTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateAppVersionResponseTypeDef = TypedDict(
     "UpdateAppVersionResponseTypeDef",
     {
         "additionalInfo": Dict[str, List[str]],
         "appArn": str,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAlarmRecommendationTypeDef = TypedDict(
     "_RequiredAlarmRecommendationTypeDef",
     {
         "name": str,
@@ -1472,68 +1493,69 @@
 
 CreateAppVersionAppComponentResponseTypeDef = TypedDict(
     "CreateAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAppVersionAppComponentResponseTypeDef = TypedDict(
     "DeleteAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppVersionAppComponentResponseTypeDef = TypedDict(
     "DescribeAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionAppComponentsResponseTypeDef = TypedDict(
     "ListAppVersionAppComponentsResponseTypeDef",
     {
         "appArn": str,
         "appComponents": List[AppComponentTypeDef],
         "appVersion": str,
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppVersionAppComponentResponseTypeDef = TypedDict(
     "UpdateAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAppInputSourceTypeDef = TypedDict(
     "_RequiredAppInputSourceTypeDef",
     {
         "importType": ResourceMappingTypeType,
     },
 )
 _OptionalAppInputSourceTypeDef = TypedDict(
     "_OptionalAppInputSourceTypeDef",
     {
+        "eksSourceClusterNamespace": EksSourceClusterNamespaceTypeDef,
         "resourceCount": int,
         "sourceArn": str,
         "sourceName": str,
         "terraformSource": TerraformSourceTypeDef,
     },
     total=False,
 )
@@ -1549,103 +1571,68 @@
         "appArn": str,
     },
 )
 _OptionalDeleteAppInputSourceRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteAppInputSourceRequestRequestTypeDef",
     {
         "clientToken": str,
+        "eksSourceClusterNamespace": EksSourceClusterNamespaceTypeDef,
         "sourceArn": str,
         "terraformSource": TerraformSourceTypeDef,
     },
     total=False,
 )
 
 
 class DeleteAppInputSourceRequestRequestTypeDef(
     _RequiredDeleteAppInputSourceRequestRequestTypeDef,
     _OptionalDeleteAppInputSourceRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef",
-    {
-        "appArn": str,
-    },
-)
-_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef",
-    {
-        "importStrategy": ResourceImportStrategyTypeType,
-        "sourceArns": Sequence[str],
-        "terraformSources": Sequence[TerraformSourceTypeDef],
-    },
-    total=False,
-)
-
-
-class ImportResourcesToDraftAppVersionRequestRequestTypeDef(
-    _RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef,
-    _OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef,
-):
-    pass
-
-
-ImportResourcesToDraftAppVersionResponseTypeDef = TypedDict(
-    "ImportResourcesToDraftAppVersionResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "sourceArns": List[str],
-        "status": ResourceImportStatusTypeType,
-        "terraformSources": List[TerraformSourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListAppsResponseTypeDef = TypedDict(
     "ListAppsResponseTypeDef",
     {
         "appSummaries": List[AppSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppResponseTypeDef = TypedDict(
     "CreateAppResponseTypeDef",
     {
         "app": AppTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppResponseTypeDef = TypedDict(
     "DescribeAppResponseTypeDef",
     {
         "app": AppTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppResponseTypeDef = TypedDict(
     "UpdateAppResponseTypeDef",
     {
         "app": AppTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionsResponseTypeDef = TypedDict(
     "ListAppVersionsResponseTypeDef",
     {
         "appVersions": List[AppVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConfigRecommendationTypeDef = TypedDict(
     "_RequiredConfigRecommendationTypeDef",
     {
         "name": str,
@@ -1679,25 +1666,25 @@
 _RequiredCreateAppVersionResourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppVersionResourceRequestRequestTypeDef",
     {
         "appArn": str,
         "appComponents": Sequence[str],
         "logicalResourceId": LogicalResourceIdTypeDef,
         "physicalResourceId": str,
-        "resourceName": str,
         "resourceType": str,
     },
 )
 _OptionalCreateAppVersionResourceRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAppVersionResourceRequestRequestTypeDef",
     {
         "additionalInfo": Mapping[str, Sequence[str]],
         "awsAccountId": str,
         "awsRegion": str,
         "clientToken": str,
+        "resourceName": str,
     },
     total=False,
 )
 
 
 class CreateAppVersionResourceRequestRequestTypeDef(
     _RequiredCreateAppVersionResourceRequestRequestTypeDef,
@@ -1855,29 +1842,69 @@
 class UpdateResiliencyPolicyRequestRequestTypeDef(
     _RequiredUpdateResiliencyPolicyRequestRequestTypeDef,
     _OptionalUpdateResiliencyPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef",
+    {
+        "appArn": str,
+    },
+)
+_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef",
+    {
+        "eksSources": Sequence[EksSourceTypeDef],
+        "importStrategy": ResourceImportStrategyTypeType,
+        "sourceArns": Sequence[str],
+        "terraformSources": Sequence[TerraformSourceTypeDef],
+    },
+    total=False,
+)
+
+
+class ImportResourcesToDraftAppVersionRequestRequestTypeDef(
+    _RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef,
+    _OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef,
+):
+    pass
+
+
+ImportResourcesToDraftAppVersionResponseTypeDef = TypedDict(
+    "ImportResourcesToDraftAppVersionResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "eksSources": List[EksSourceTypeDef],
+        "sourceArns": List[str],
+        "status": ResourceImportStatusTypeType,
+        "terraformSources": List[TerraformSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPhysicalResourceTypeDef = TypedDict(
     "_RequiredPhysicalResourceTypeDef",
     {
         "logicalResourceId": LogicalResourceIdTypeDef,
         "physicalResourceId": PhysicalResourceIdTypeDef,
         "resourceType": str,
     },
 )
 _OptionalPhysicalResourceTypeDef = TypedDict(
     "_OptionalPhysicalResourceTypeDef",
     {
         "additionalInfo": Dict[str, List[str]],
         "appComponents": List[AppComponentTypeDef],
         "excluded": bool,
+        "parentResourceName": str,
         "resourceName": str,
+        "sourceType": ResourceSourceTypeType,
     },
     total=False,
 )
 
 
 class PhysicalResourceTypeDef(_RequiredPhysicalResourceTypeDef, _OptionalPhysicalResourceTypeDef):
     pass
@@ -1890,35 +1917,50 @@
         "physicalResourceId": PhysicalResourceIdTypeDef,
     },
 )
 _OptionalResourceMappingTypeDef = TypedDict(
     "_OptionalResourceMappingTypeDef",
     {
         "appRegistryAppName": str,
+        "eksSourceName": str,
         "logicalStackName": str,
         "resourceGroupName": str,
         "resourceName": str,
         "terraformSourceName": str,
     },
     total=False,
 )
 
 
 class ResourceMappingTypeDef(_RequiredResourceMappingTypeDef, _OptionalResourceMappingTypeDef):
     pass
 
 
-UnsupportedResourceTypeDef = TypedDict(
-    "UnsupportedResourceTypeDef",
+_RequiredUnsupportedResourceTypeDef = TypedDict(
+    "_RequiredUnsupportedResourceTypeDef",
     {
         "logicalResourceId": LogicalResourceIdTypeDef,
         "physicalResourceId": PhysicalResourceIdTypeDef,
         "resourceType": str,
     },
 )
+_OptionalUnsupportedResourceTypeDef = TypedDict(
+    "_OptionalUnsupportedResourceTypeDef",
+    {
+        "unsupportedResourceStatus": str,
+    },
+    total=False,
+)
+
+
+class UnsupportedResourceTypeDef(
+    _RequiredUnsupportedResourceTypeDef, _OptionalUnsupportedResourceTypeDef
+):
+    pass
+
 
 _RequiredRecommendationTemplateTypeDef = TypedDict(
     "_RequiredRecommendationTemplateTypeDef",
     {
         "assessmentArn": str,
         "format": TemplateFormatType,
         "name": str,
@@ -1959,69 +2001,69 @@
 )
 
 ListAlarmRecommendationsResponseTypeDef = TypedDict(
     "ListAlarmRecommendationsResponseTypeDef",
     {
         "alarmRecommendations": List[AlarmRecommendationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSopRecommendationsResponseTypeDef = TypedDict(
     "ListSopRecommendationsResponseTypeDef",
     {
         "nextToken": str,
         "sopRecommendations": List[SopRecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestRecommendationsResponseTypeDef = TypedDict(
     "ListTestRecommendationsResponseTypeDef",
     {
         "nextToken": str,
         "testRecommendations": List[TestRecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppAssessmentsResponseTypeDef = TypedDict(
     "ListAppAssessmentsResponseTypeDef",
     {
         "assessmentSummaries": List[AppAssessmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppComponentCompliancesResponseTypeDef = TypedDict(
     "ListAppComponentCompliancesResponseTypeDef",
     {
         "componentCompliances": List[AppComponentComplianceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAppInputSourceResponseTypeDef = TypedDict(
     "DeleteAppInputSourceResponseTypeDef",
     {
         "appArn": str,
         "appInputSource": AppInputSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInputSourcesResponseTypeDef = TypedDict(
     "ListAppInputSourcesResponseTypeDef",
     {
         "appInputSources": List[AppInputSourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentRecommendationTypeDef = TypedDict(
     "ComponentRecommendationTypeDef",
     {
         "appComponentName": str,
@@ -2030,99 +2072,99 @@
     },
 )
 
 CreateResiliencyPolicyResponseTypeDef = TypedDict(
     "CreateResiliencyPolicyResponseTypeDef",
     {
         "policy": ResiliencyPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeResiliencyPolicyResponseTypeDef = TypedDict(
     "DescribeResiliencyPolicyResponseTypeDef",
     {
         "policy": ResiliencyPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResiliencyPoliciesResponseTypeDef = TypedDict(
     "ListResiliencyPoliciesResponseTypeDef",
     {
         "nextToken": str,
         "resiliencyPolicies": List[ResiliencyPolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSuggestedResiliencyPoliciesResponseTypeDef = TypedDict(
     "ListSuggestedResiliencyPoliciesResponseTypeDef",
     {
         "nextToken": str,
         "resiliencyPolicies": List[ResiliencyPolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResiliencyPolicyResponseTypeDef = TypedDict(
     "UpdateResiliencyPolicyResponseTypeDef",
     {
         "policy": ResiliencyPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppVersionResourceResponseTypeDef = TypedDict(
     "CreateAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAppVersionResourceResponseTypeDef = TypedDict(
     "DeleteAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppVersionResourceResponseTypeDef = TypedDict(
     "DescribeAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionResourcesResponseTypeDef = TypedDict(
     "ListAppVersionResourcesResponseTypeDef",
     {
         "nextToken": str,
         "physicalResources": List[PhysicalResourceTypeDef],
         "resolutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppVersionResourceResponseTypeDef = TypedDict(
     "UpdateAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddDraftAppVersionResourceMappingsRequestRequestTypeDef = TypedDict(
     "AddDraftAppVersionResourceMappingsRequestRequestTypeDef",
     {
         "appArn": str,
@@ -2132,51 +2174,51 @@
 
 AddDraftAppVersionResourceMappingsResponseTypeDef = TypedDict(
     "AddDraftAppVersionResourceMappingsResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "resourceMappings": List[ResourceMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionResourceMappingsResponseTypeDef = TypedDict(
     "ListAppVersionResourceMappingsResponseTypeDef",
     {
         "nextToken": str,
         "resourceMappings": List[ResourceMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUnsupportedAppVersionResourcesResponseTypeDef = TypedDict(
     "ListUnsupportedAppVersionResourcesResponseTypeDef",
     {
         "nextToken": str,
         "resolutionId": str,
         "unsupportedResources": List[UnsupportedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRecommendationTemplateResponseTypeDef = TypedDict(
     "CreateRecommendationTemplateResponseTypeDef",
     {
         "recommendationTemplate": RecommendationTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecommendationTemplatesResponseTypeDef = TypedDict(
     "ListRecommendationTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "recommendationTemplates": List[RecommendationTemplateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAppAssessmentTypeDef = TypedDict(
     "_RequiredAppAssessmentTypeDef",
     {
         "assessmentArn": str,
@@ -2210,26 +2252,26 @@
 
 
 ListAppComponentRecommendationsResponseTypeDef = TypedDict(
     "ListAppComponentRecommendationsResponseTypeDef",
     {
         "componentRecommendations": List[ComponentRecommendationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppAssessmentResponseTypeDef = TypedDict(
     "DescribeAppAssessmentResponseTypeDef",
     {
         "assessment": AppAssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartAppAssessmentResponseTypeDef = TypedDict(
     "StartAppAssessmentResponseTypeDef",
     {
         "assessment": AppAssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub/type_defs.pyi` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for resiliencehub service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_resiliencehub.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_resiliencehub.type_defs import RecommendationItemTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: RecommendationItemTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
@@ -34,14 +34,15 @@
     RecommendationTemplateStatusType,
     RenderRecommendationTypeType,
     ResiliencyPolicyTierType,
     ResourceImportStatusTypeType,
     ResourceImportStrategyTypeType,
     ResourceMappingTypeType,
     ResourceResolutionStatusTypeType,
+    ResourceSourceTypeType,
     TemplateFormatType,
     TestRiskType,
     TestTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -49,43 +50,52 @@
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
-    "ResponseMetadataTypeDef",
     "RecommendationItemTypeDef",
     "CostTypeDef",
     "DisruptionComplianceTypeDef",
     "ResiliencyScoreTypeDef",
     "AppComponentTypeDef",
+    "EksSourceClusterNamespaceTypeDef",
     "TerraformSourceTypeDef",
     "AppSummaryTypeDef",
     "AppTypeDef",
     "AppVersionSummaryTypeDef",
     "RecommendationDisruptionComplianceTypeDef",
     "CreateAppRequestRequestTypeDef",
     "CreateAppVersionAppComponentRequestRequestTypeDef",
     "LogicalResourceIdTypeDef",
     "CreateRecommendationTemplateRequestRequestTypeDef",
     "FailurePolicyTypeDef",
     "DeleteAppAssessmentRequestRequestTypeDef",
+    "DeleteAppAssessmentResponseTypeDef",
     "DeleteAppRequestRequestTypeDef",
+    "DeleteAppResponseTypeDef",
     "DeleteAppVersionAppComponentRequestRequestTypeDef",
     "DeleteRecommendationTemplateRequestRequestTypeDef",
+    "DeleteRecommendationTemplateResponseTypeDef",
     "DeleteResiliencyPolicyRequestRequestTypeDef",
+    "DeleteResiliencyPolicyResponseTypeDef",
     "DescribeAppAssessmentRequestRequestTypeDef",
     "DescribeAppRequestRequestTypeDef",
     "DescribeAppVersionAppComponentRequestRequestTypeDef",
     "DescribeAppVersionRequestRequestTypeDef",
     "DescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef",
+    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
+    "DescribeAppVersionResponseTypeDef",
     "DescribeAppVersionTemplateRequestRequestTypeDef",
+    "DescribeAppVersionTemplateResponseTypeDef",
     "DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef",
+    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
     "DescribeResiliencyPolicyRequestRequestTypeDef",
+    "EksSourceTypeDef",
     "ListAlarmRecommendationsRequestRequestTypeDef",
     "ListAppAssessmentsRequestRequestTypeDef",
     "ListAppComponentCompliancesRequestRequestTypeDef",
     "ListAppComponentRecommendationsRequestRequestTypeDef",
     "ListAppInputSourcesRequestRequestTypeDef",
     "ListAppVersionAppComponentsRequestRequestTypeDef",
     "ListAppVersionResourceMappingsRequestRequestTypeDef",
@@ -93,70 +103,63 @@
     "ListAppVersionsRequestRequestTypeDef",
     "ListAppsRequestRequestTypeDef",
     "ListRecommendationTemplatesRequestRequestTypeDef",
     "ListResiliencyPoliciesRequestRequestTypeDef",
     "ListSopRecommendationsRequestRequestTypeDef",
     "ListSuggestedResiliencyPoliciesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListTestRecommendationsRequestRequestTypeDef",
     "ListUnsupportedAppVersionResourcesRequestRequestTypeDef",
     "PhysicalResourceIdTypeDef",
     "PublishAppVersionRequestRequestTypeDef",
+    "PublishAppVersionResponseTypeDef",
     "PutDraftAppVersionTemplateRequestRequestTypeDef",
+    "PutDraftAppVersionTemplateResponseTypeDef",
     "S3LocationTypeDef",
     "RemoveDraftAppVersionResourceMappingsRequestRequestTypeDef",
+    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
     "ResolveAppVersionResourcesRequestRequestTypeDef",
+    "ResolveAppVersionResourcesResponseTypeDef",
     "ResourceErrorTypeDef",
+    "ResponseMetadataTypeDef",
     "StartAppAssessmentRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAppRequestRequestTypeDef",
     "UpdateAppVersionAppComponentRequestRequestTypeDef",
     "UpdateAppVersionRequestRequestTypeDef",
-    "DeleteAppAssessmentResponseTypeDef",
-    "DeleteAppResponseTypeDef",
-    "DeleteRecommendationTemplateResponseTypeDef",
-    "DeleteResiliencyPolicyResponseTypeDef",
-    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
-    "DescribeAppVersionResponseTypeDef",
-    "DescribeAppVersionTemplateResponseTypeDef",
-    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PublishAppVersionResponseTypeDef",
-    "PutDraftAppVersionTemplateResponseTypeDef",
-    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
-    "ResolveAppVersionResourcesResponseTypeDef",
     "UpdateAppVersionResponseTypeDef",
     "AlarmRecommendationTypeDef",
     "SopRecommendationTypeDef",
     "TestRecommendationTypeDef",
     "AppAssessmentSummaryTypeDef",
     "AppComponentComplianceTypeDef",
     "CreateAppVersionAppComponentResponseTypeDef",
     "DeleteAppVersionAppComponentResponseTypeDef",
     "DescribeAppVersionAppComponentResponseTypeDef",
     "ListAppVersionAppComponentsResponseTypeDef",
     "UpdateAppVersionAppComponentResponseTypeDef",
     "AppInputSourceTypeDef",
     "DeleteAppInputSourceRequestRequestTypeDef",
-    "ImportResourcesToDraftAppVersionRequestRequestTypeDef",
-    "ImportResourcesToDraftAppVersionResponseTypeDef",
     "ListAppsResponseTypeDef",
     "CreateAppResponseTypeDef",
     "DescribeAppResponseTypeDef",
     "UpdateAppResponseTypeDef",
     "ListAppVersionsResponseTypeDef",
     "ConfigRecommendationTypeDef",
     "CreateAppVersionResourceRequestRequestTypeDef",
     "DeleteAppVersionResourceRequestRequestTypeDef",
     "DescribeAppVersionResourceRequestRequestTypeDef",
     "UpdateAppVersionResourceRequestRequestTypeDef",
     "CreateResiliencyPolicyRequestRequestTypeDef",
     "ResiliencyPolicyTypeDef",
     "UpdateResiliencyPolicyRequestRequestTypeDef",
+    "ImportResourcesToDraftAppVersionRequestRequestTypeDef",
+    "ImportResourcesToDraftAppVersionResponseTypeDef",
     "PhysicalResourceTypeDef",
     "ResourceMappingTypeDef",
     "UnsupportedResourceTypeDef",
     "RecommendationTemplateTypeDef",
     "ResourceErrorsDetailsTypeDef",
     "ListAlarmRecommendationsResponseTypeDef",
     "ListSopRecommendationsResponseTypeDef",
@@ -184,25 +187,14 @@
     "ListRecommendationTemplatesResponseTypeDef",
     "AppAssessmentTypeDef",
     "ListAppComponentRecommendationsResponseTypeDef",
     "DescribeAppAssessmentResponseTypeDef",
     "StartAppAssessmentResponseTypeDef",
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
 RecommendationItemTypeDef = TypedDict(
     "RecommendationItemTypeDef",
     {
         "alreadyImplemented": bool,
         "resourceId": str,
         "targetAccountId": str,
         "targetRegion": str,
@@ -269,14 +261,22 @@
     },
     total=False,
 )
 
 class AppComponentTypeDef(_RequiredAppComponentTypeDef, _OptionalAppComponentTypeDef):
     pass
 
+EksSourceClusterNamespaceTypeDef = TypedDict(
+    "EksSourceClusterNamespaceTypeDef",
+    {
+        "eksClusterArn": str,
+        "namespace": str,
+    },
+)
+
 TerraformSourceTypeDef = TypedDict(
     "TerraformSourceTypeDef",
     {
         "s3StateFileUrl": str,
     },
 )
 
@@ -412,14 +412,15 @@
     {
         "identifier": str,
     },
 )
 _OptionalLogicalResourceIdTypeDef = TypedDict(
     "_OptionalLogicalResourceIdTypeDef",
     {
+        "eksSourceName": str,
         "logicalStackName": str,
         "resourceGroupName": str,
         "terraformSourceName": str,
     },
     total=False,
 )
 
@@ -478,14 +479,23 @@
 
 class DeleteAppAssessmentRequestRequestTypeDef(
     _RequiredDeleteAppAssessmentRequestRequestTypeDef,
     _OptionalDeleteAppAssessmentRequestRequestTypeDef,
 ):
     pass
 
+DeleteAppAssessmentResponseTypeDef = TypedDict(
+    "DeleteAppAssessmentResponseTypeDef",
+    {
+        "assessmentArn": str,
+        "assessmentStatus": AssessmentStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteAppRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAppRequestRequestTypeDef",
     {
         "appArn": str,
     },
 )
 _OptionalDeleteAppRequestRequestTypeDef = TypedDict(
@@ -498,14 +508,22 @@
 )
 
 class DeleteAppRequestRequestTypeDef(
     _RequiredDeleteAppRequestRequestTypeDef, _OptionalDeleteAppRequestRequestTypeDef
 ):
     pass
 
+DeleteAppResponseTypeDef = TypedDict(
+    "DeleteAppResponseTypeDef",
+    {
+        "appArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteAppVersionAppComponentRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteAppVersionAppComponentRequestRequestTypeDef",
     {
         "appArn": str,
         "id": str,
     },
 )
@@ -539,14 +557,23 @@
 
 class DeleteRecommendationTemplateRequestRequestTypeDef(
     _RequiredDeleteRecommendationTemplateRequestRequestTypeDef,
     _OptionalDeleteRecommendationTemplateRequestRequestTypeDef,
 ):
     pass
 
+DeleteRecommendationTemplateResponseTypeDef = TypedDict(
+    "DeleteRecommendationTemplateResponseTypeDef",
+    {
+        "recommendationTemplateArn": str,
+        "status": RecommendationTemplateStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteResiliencyPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResiliencyPolicyRequestRequestTypeDef",
     {
         "policyArn": str,
     },
 )
 _OptionalDeleteResiliencyPolicyRequestRequestTypeDef = TypedDict(
@@ -559,14 +586,22 @@
 
 class DeleteResiliencyPolicyRequestRequestTypeDef(
     _RequiredDeleteResiliencyPolicyRequestRequestTypeDef,
     _OptionalDeleteResiliencyPolicyRequestRequestTypeDef,
 ):
     pass
 
+DeleteResiliencyPolicyResponseTypeDef = TypedDict(
+    "DeleteResiliencyPolicyResponseTypeDef",
+    {
+        "policyArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeAppAssessmentRequestRequestTypeDef = TypedDict(
     "DescribeAppAssessmentRequestRequestTypeDef",
     {
         "assessmentArn": str,
     },
 )
 
@@ -611,36 +646,88 @@
 
 class DescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef(
     _RequiredDescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef,
     _OptionalDescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef,
 ):
     pass
 
+DescribeAppVersionResourcesResolutionStatusResponseTypeDef = TypedDict(
+    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "errorMessage": str,
+        "resolutionId": str,
+        "status": ResourceResolutionStatusTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAppVersionResponseTypeDef = TypedDict(
+    "DescribeAppVersionResponseTypeDef",
+    {
+        "additionalInfo": Dict[str, List[str]],
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeAppVersionTemplateRequestRequestTypeDef = TypedDict(
     "DescribeAppVersionTemplateRequestRequestTypeDef",
     {
         "appArn": str,
         "appVersion": str,
     },
 )
 
+DescribeAppVersionTemplateResponseTypeDef = TypedDict(
+    "DescribeAppVersionTemplateResponseTypeDef",
+    {
+        "appArn": str,
+        "appTemplateBody": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef = TypedDict(
     "DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef",
     {
         "appArn": str,
     },
 )
 
+DescribeDraftAppVersionResourcesImportStatusResponseTypeDef = TypedDict(
+    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "errorMessage": str,
+        "status": ResourceImportStatusTypeType,
+        "statusChangeTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeResiliencyPolicyRequestRequestTypeDef = TypedDict(
     "DescribeResiliencyPolicyRequestRequestTypeDef",
     {
         "policyArn": str,
     },
 )
 
+EksSourceTypeDef = TypedDict(
+    "EksSourceTypeDef",
+    {
+        "eksClusterArn": str,
+        "namespaces": Sequence[str],
+    },
+)
+
 _RequiredListAlarmRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredListAlarmRecommendationsRequestRequestTypeDef",
     {
         "assessmentArn": str,
     },
 )
 _OptionalListAlarmRecommendationsRequestRequestTypeDef = TypedDict(
@@ -903,14 +990,22 @@
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
 _RequiredListTestRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredListTestRecommendationsRequestRequestTypeDef",
     {
         "assessmentArn": str,
     },
 )
 _OptionalListTestRecommendationsRequestRequestTypeDef = TypedDict(
@@ -975,22 +1070,40 @@
 PublishAppVersionRequestRequestTypeDef = TypedDict(
     "PublishAppVersionRequestRequestTypeDef",
     {
         "appArn": str,
     },
 )
 
+PublishAppVersionResponseTypeDef = TypedDict(
+    "PublishAppVersionResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutDraftAppVersionTemplateRequestRequestTypeDef = TypedDict(
     "PutDraftAppVersionTemplateRequestRequestTypeDef",
     {
         "appArn": str,
         "appTemplateBody": str,
     },
 )
 
+PutDraftAppVersionTemplateResponseTypeDef = TypedDict(
+    "PutDraftAppVersionTemplateResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3LocationTypeDef = TypedDict(
     "S3LocationTypeDef",
     {
         "bucket": str,
         "prefix": str,
     },
     total=False,
@@ -1002,46 +1115,78 @@
         "appArn": str,
     },
 )
 _OptionalRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef = TypedDict(
     "_OptionalRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef",
     {
         "appRegistryAppNames": Sequence[str],
+        "eksSourceNames": Sequence[str],
         "logicalStackNames": Sequence[str],
         "resourceGroupNames": Sequence[str],
         "resourceNames": Sequence[str],
         "terraformSourceNames": Sequence[str],
     },
     total=False,
 )
 
 class RemoveDraftAppVersionResourceMappingsRequestRequestTypeDef(
     _RequiredRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef,
     _OptionalRemoveDraftAppVersionResourceMappingsRequestRequestTypeDef,
 ):
     pass
 
+RemoveDraftAppVersionResourceMappingsResponseTypeDef = TypedDict(
+    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResolveAppVersionResourcesRequestRequestTypeDef = TypedDict(
     "ResolveAppVersionResourcesRequestRequestTypeDef",
     {
         "appArn": str,
         "appVersion": str,
     },
 )
 
+ResolveAppVersionResourcesResponseTypeDef = TypedDict(
+    "ResolveAppVersionResourcesResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "resolutionId": str,
+        "status": ResourceResolutionStatusTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceErrorTypeDef = TypedDict(
     "ResourceErrorTypeDef",
     {
         "logicalResourceId": str,
         "physicalResourceId": str,
         "reason": str,
     },
     total=False,
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
 _RequiredStartAppAssessmentRequestRequestTypeDef = TypedDict(
     "_RequiredStartAppAssessmentRequestRequestTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "assessmentName": str,
     },
@@ -1137,145 +1282,21 @@
 )
 
 class UpdateAppVersionRequestRequestTypeDef(
     _RequiredUpdateAppVersionRequestRequestTypeDef, _OptionalUpdateAppVersionRequestRequestTypeDef
 ):
     pass
 
-DeleteAppAssessmentResponseTypeDef = TypedDict(
-    "DeleteAppAssessmentResponseTypeDef",
-    {
-        "assessmentArn": str,
-        "assessmentStatus": AssessmentStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteAppResponseTypeDef = TypedDict(
-    "DeleteAppResponseTypeDef",
-    {
-        "appArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRecommendationTemplateResponseTypeDef = TypedDict(
-    "DeleteRecommendationTemplateResponseTypeDef",
-    {
-        "recommendationTemplateArn": str,
-        "status": RecommendationTemplateStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteResiliencyPolicyResponseTypeDef = TypedDict(
-    "DeleteResiliencyPolicyResponseTypeDef",
-    {
-        "policyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppVersionResourcesResolutionStatusResponseTypeDef = TypedDict(
-    "DescribeAppVersionResourcesResolutionStatusResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "errorMessage": str,
-        "resolutionId": str,
-        "status": ResourceResolutionStatusTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppVersionResponseTypeDef = TypedDict(
-    "DescribeAppVersionResponseTypeDef",
-    {
-        "additionalInfo": Dict[str, List[str]],
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppVersionTemplateResponseTypeDef = TypedDict(
-    "DescribeAppVersionTemplateResponseTypeDef",
-    {
-        "appArn": str,
-        "appTemplateBody": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDraftAppVersionResourcesImportStatusResponseTypeDef = TypedDict(
-    "DescribeDraftAppVersionResourcesImportStatusResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "errorMessage": str,
-        "status": ResourceImportStatusTypeType,
-        "statusChangeTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PublishAppVersionResponseTypeDef = TypedDict(
-    "PublishAppVersionResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutDraftAppVersionTemplateResponseTypeDef = TypedDict(
-    "PutDraftAppVersionTemplateResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveDraftAppVersionResourceMappingsResponseTypeDef = TypedDict(
-    "RemoveDraftAppVersionResourceMappingsResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResolveAppVersionResourcesResponseTypeDef = TypedDict(
-    "ResolveAppVersionResourcesResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "resolutionId": str,
-        "status": ResourceResolutionStatusTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateAppVersionResponseTypeDef = TypedDict(
     "UpdateAppVersionResponseTypeDef",
     {
         "additionalInfo": Dict[str, List[str]],
         "appArn": str,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAlarmRecommendationTypeDef = TypedDict(
     "_RequiredAlarmRecommendationTypeDef",
     {
         "name": str,
@@ -1397,68 +1418,69 @@
 
 CreateAppVersionAppComponentResponseTypeDef = TypedDict(
     "CreateAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAppVersionAppComponentResponseTypeDef = TypedDict(
     "DeleteAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppVersionAppComponentResponseTypeDef = TypedDict(
     "DescribeAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionAppComponentsResponseTypeDef = TypedDict(
     "ListAppVersionAppComponentsResponseTypeDef",
     {
         "appArn": str,
         "appComponents": List[AppComponentTypeDef],
         "appVersion": str,
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppVersionAppComponentResponseTypeDef = TypedDict(
     "UpdateAppVersionAppComponentResponseTypeDef",
     {
         "appArn": str,
         "appComponent": AppComponentTypeDef,
         "appVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAppInputSourceTypeDef = TypedDict(
     "_RequiredAppInputSourceTypeDef",
     {
         "importType": ResourceMappingTypeType,
     },
 )
 _OptionalAppInputSourceTypeDef = TypedDict(
     "_OptionalAppInputSourceTypeDef",
     {
+        "eksSourceClusterNamespace": EksSourceClusterNamespaceTypeDef,
         "resourceCount": int,
         "sourceArn": str,
         "sourceName": str,
         "terraformSource": TerraformSourceTypeDef,
     },
     total=False,
 )
@@ -1472,99 +1494,66 @@
         "appArn": str,
     },
 )
 _OptionalDeleteAppInputSourceRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteAppInputSourceRequestRequestTypeDef",
     {
         "clientToken": str,
+        "eksSourceClusterNamespace": EksSourceClusterNamespaceTypeDef,
         "sourceArn": str,
         "terraformSource": TerraformSourceTypeDef,
     },
     total=False,
 )
 
 class DeleteAppInputSourceRequestRequestTypeDef(
     _RequiredDeleteAppInputSourceRequestRequestTypeDef,
     _OptionalDeleteAppInputSourceRequestRequestTypeDef,
 ):
     pass
 
-_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
-    "_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef",
-    {
-        "appArn": str,
-    },
-)
-_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
-    "_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef",
-    {
-        "importStrategy": ResourceImportStrategyTypeType,
-        "sourceArns": Sequence[str],
-        "terraformSources": Sequence[TerraformSourceTypeDef],
-    },
-    total=False,
-)
-
-class ImportResourcesToDraftAppVersionRequestRequestTypeDef(
-    _RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef,
-    _OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef,
-):
-    pass
-
-ImportResourcesToDraftAppVersionResponseTypeDef = TypedDict(
-    "ImportResourcesToDraftAppVersionResponseTypeDef",
-    {
-        "appArn": str,
-        "appVersion": str,
-        "sourceArns": List[str],
-        "status": ResourceImportStatusTypeType,
-        "terraformSources": List[TerraformSourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListAppsResponseTypeDef = TypedDict(
     "ListAppsResponseTypeDef",
     {
         "appSummaries": List[AppSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppResponseTypeDef = TypedDict(
     "CreateAppResponseTypeDef",
     {
         "app": AppTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppResponseTypeDef = TypedDict(
     "DescribeAppResponseTypeDef",
     {
         "app": AppTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppResponseTypeDef = TypedDict(
     "UpdateAppResponseTypeDef",
     {
         "app": AppTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionsResponseTypeDef = TypedDict(
     "ListAppVersionsResponseTypeDef",
     {
         "appVersions": List[AppVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredConfigRecommendationTypeDef = TypedDict(
     "_RequiredConfigRecommendationTypeDef",
     {
         "name": str,
@@ -1596,25 +1585,25 @@
 _RequiredCreateAppVersionResourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppVersionResourceRequestRequestTypeDef",
     {
         "appArn": str,
         "appComponents": Sequence[str],
         "logicalResourceId": LogicalResourceIdTypeDef,
         "physicalResourceId": str,
-        "resourceName": str,
         "resourceType": str,
     },
 )
 _OptionalCreateAppVersionResourceRequestRequestTypeDef = TypedDict(
     "_OptionalCreateAppVersionResourceRequestRequestTypeDef",
     {
         "additionalInfo": Mapping[str, Sequence[str]],
         "awsAccountId": str,
         "awsRegion": str,
         "clientToken": str,
+        "resourceName": str,
     },
     total=False,
 )
 
 class CreateAppVersionResourceRequestRequestTypeDef(
     _RequiredCreateAppVersionResourceRequestRequestTypeDef,
     _OptionalCreateAppVersionResourceRequestRequestTypeDef,
@@ -1760,29 +1749,67 @@
 
 class UpdateResiliencyPolicyRequestRequestTypeDef(
     _RequiredUpdateResiliencyPolicyRequestRequestTypeDef,
     _OptionalUpdateResiliencyPolicyRequestRequestTypeDef,
 ):
     pass
 
+_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
+    "_RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef",
+    {
+        "appArn": str,
+    },
+)
+_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef = TypedDict(
+    "_OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef",
+    {
+        "eksSources": Sequence[EksSourceTypeDef],
+        "importStrategy": ResourceImportStrategyTypeType,
+        "sourceArns": Sequence[str],
+        "terraformSources": Sequence[TerraformSourceTypeDef],
+    },
+    total=False,
+)
+
+class ImportResourcesToDraftAppVersionRequestRequestTypeDef(
+    _RequiredImportResourcesToDraftAppVersionRequestRequestTypeDef,
+    _OptionalImportResourcesToDraftAppVersionRequestRequestTypeDef,
+):
+    pass
+
+ImportResourcesToDraftAppVersionResponseTypeDef = TypedDict(
+    "ImportResourcesToDraftAppVersionResponseTypeDef",
+    {
+        "appArn": str,
+        "appVersion": str,
+        "eksSources": List[EksSourceTypeDef],
+        "sourceArns": List[str],
+        "status": ResourceImportStatusTypeType,
+        "terraformSources": List[TerraformSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPhysicalResourceTypeDef = TypedDict(
     "_RequiredPhysicalResourceTypeDef",
     {
         "logicalResourceId": LogicalResourceIdTypeDef,
         "physicalResourceId": PhysicalResourceIdTypeDef,
         "resourceType": str,
     },
 )
 _OptionalPhysicalResourceTypeDef = TypedDict(
     "_OptionalPhysicalResourceTypeDef",
     {
         "additionalInfo": Dict[str, List[str]],
         "appComponents": List[AppComponentTypeDef],
         "excluded": bool,
+        "parentResourceName": str,
         "resourceName": str,
+        "sourceType": ResourceSourceTypeType,
     },
     total=False,
 )
 
 class PhysicalResourceTypeDef(_RequiredPhysicalResourceTypeDef, _OptionalPhysicalResourceTypeDef):
     pass
 
@@ -1793,33 +1820,46 @@
         "physicalResourceId": PhysicalResourceIdTypeDef,
     },
 )
 _OptionalResourceMappingTypeDef = TypedDict(
     "_OptionalResourceMappingTypeDef",
     {
         "appRegistryAppName": str,
+        "eksSourceName": str,
         "logicalStackName": str,
         "resourceGroupName": str,
         "resourceName": str,
         "terraformSourceName": str,
     },
     total=False,
 )
 
 class ResourceMappingTypeDef(_RequiredResourceMappingTypeDef, _OptionalResourceMappingTypeDef):
     pass
 
-UnsupportedResourceTypeDef = TypedDict(
-    "UnsupportedResourceTypeDef",
+_RequiredUnsupportedResourceTypeDef = TypedDict(
+    "_RequiredUnsupportedResourceTypeDef",
     {
         "logicalResourceId": LogicalResourceIdTypeDef,
         "physicalResourceId": PhysicalResourceIdTypeDef,
         "resourceType": str,
     },
 )
+_OptionalUnsupportedResourceTypeDef = TypedDict(
+    "_OptionalUnsupportedResourceTypeDef",
+    {
+        "unsupportedResourceStatus": str,
+    },
+    total=False,
+)
+
+class UnsupportedResourceTypeDef(
+    _RequiredUnsupportedResourceTypeDef, _OptionalUnsupportedResourceTypeDef
+):
+    pass
 
 _RequiredRecommendationTemplateTypeDef = TypedDict(
     "_RequiredRecommendationTemplateTypeDef",
     {
         "assessmentArn": str,
         "format": TemplateFormatType,
         "name": str,
@@ -1858,69 +1898,69 @@
 )
 
 ListAlarmRecommendationsResponseTypeDef = TypedDict(
     "ListAlarmRecommendationsResponseTypeDef",
     {
         "alarmRecommendations": List[AlarmRecommendationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSopRecommendationsResponseTypeDef = TypedDict(
     "ListSopRecommendationsResponseTypeDef",
     {
         "nextToken": str,
         "sopRecommendations": List[SopRecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestRecommendationsResponseTypeDef = TypedDict(
     "ListTestRecommendationsResponseTypeDef",
     {
         "nextToken": str,
         "testRecommendations": List[TestRecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppAssessmentsResponseTypeDef = TypedDict(
     "ListAppAssessmentsResponseTypeDef",
     {
         "assessmentSummaries": List[AppAssessmentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppComponentCompliancesResponseTypeDef = TypedDict(
     "ListAppComponentCompliancesResponseTypeDef",
     {
         "componentCompliances": List[AppComponentComplianceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAppInputSourceResponseTypeDef = TypedDict(
     "DeleteAppInputSourceResponseTypeDef",
     {
         "appArn": str,
         "appInputSource": AppInputSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInputSourcesResponseTypeDef = TypedDict(
     "ListAppInputSourcesResponseTypeDef",
     {
         "appInputSources": List[AppInputSourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComponentRecommendationTypeDef = TypedDict(
     "ComponentRecommendationTypeDef",
     {
         "appComponentName": str,
@@ -1929,99 +1969,99 @@
     },
 )
 
 CreateResiliencyPolicyResponseTypeDef = TypedDict(
     "CreateResiliencyPolicyResponseTypeDef",
     {
         "policy": ResiliencyPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeResiliencyPolicyResponseTypeDef = TypedDict(
     "DescribeResiliencyPolicyResponseTypeDef",
     {
         "policy": ResiliencyPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResiliencyPoliciesResponseTypeDef = TypedDict(
     "ListResiliencyPoliciesResponseTypeDef",
     {
         "nextToken": str,
         "resiliencyPolicies": List[ResiliencyPolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSuggestedResiliencyPoliciesResponseTypeDef = TypedDict(
     "ListSuggestedResiliencyPoliciesResponseTypeDef",
     {
         "nextToken": str,
         "resiliencyPolicies": List[ResiliencyPolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResiliencyPolicyResponseTypeDef = TypedDict(
     "UpdateResiliencyPolicyResponseTypeDef",
     {
         "policy": ResiliencyPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAppVersionResourceResponseTypeDef = TypedDict(
     "CreateAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAppVersionResourceResponseTypeDef = TypedDict(
     "DeleteAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppVersionResourceResponseTypeDef = TypedDict(
     "DescribeAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionResourcesResponseTypeDef = TypedDict(
     "ListAppVersionResourcesResponseTypeDef",
     {
         "nextToken": str,
         "physicalResources": List[PhysicalResourceTypeDef],
         "resolutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAppVersionResourceResponseTypeDef = TypedDict(
     "UpdateAppVersionResourceResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "physicalResource": PhysicalResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AddDraftAppVersionResourceMappingsRequestRequestTypeDef = TypedDict(
     "AddDraftAppVersionResourceMappingsRequestRequestTypeDef",
     {
         "appArn": str,
@@ -2031,51 +2071,51 @@
 
 AddDraftAppVersionResourceMappingsResponseTypeDef = TypedDict(
     "AddDraftAppVersionResourceMappingsResponseTypeDef",
     {
         "appArn": str,
         "appVersion": str,
         "resourceMappings": List[ResourceMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppVersionResourceMappingsResponseTypeDef = TypedDict(
     "ListAppVersionResourceMappingsResponseTypeDef",
     {
         "nextToken": str,
         "resourceMappings": List[ResourceMappingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUnsupportedAppVersionResourcesResponseTypeDef = TypedDict(
     "ListUnsupportedAppVersionResourcesResponseTypeDef",
     {
         "nextToken": str,
         "resolutionId": str,
         "unsupportedResources": List[UnsupportedResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRecommendationTemplateResponseTypeDef = TypedDict(
     "CreateRecommendationTemplateResponseTypeDef",
     {
         "recommendationTemplate": RecommendationTemplateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecommendationTemplatesResponseTypeDef = TypedDict(
     "ListRecommendationTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "recommendationTemplates": List[RecommendationTemplateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAppAssessmentTypeDef = TypedDict(
     "_RequiredAppAssessmentTypeDef",
     {
         "assessmentArn": str,
@@ -2107,26 +2147,26 @@
     pass
 
 ListAppComponentRecommendationsResponseTypeDef = TypedDict(
     "ListAppComponentRecommendationsResponseTypeDef",
     {
         "componentRecommendations": List[ComponentRecommendationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppAssessmentResponseTypeDef = TypedDict(
     "DescribeAppAssessmentResponseTypeDef",
     {
         "assessment": AppAssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartAppAssessmentResponseTypeDef = TypedDict(
     "StartAppAssessmentResponseTypeDef",
     {
         "assessment": AppAssessmentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/PKG-INFO` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-resiliencehub
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ResilienceHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ResilienceHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-resiliencehub"></a>
 
 # types-aiobotocore-resiliencehub
 
 [![PyPI - types-aiobotocore-resiliencehub](https://img.shields.io/pypi/v/types-aiobotocore-resiliencehub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resiliencehub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-resiliencehub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-resiliencehub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-resiliencehub?color=blue)](https://pypistats.org/packages/types-aiobotocore-resiliencehub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ResilienceHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub)
+[aiobotocore.ResilienceHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resiliencehub.html#ResilienceHub)
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
 [types-aiobotocore-resiliencehub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_resiliencehub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -291,14 +291,15 @@
     RecommendationTemplateStatusType,
     RenderRecommendationTypeType,
     ResiliencyPolicyTierType,
     ResourceImportStatusTypeType,
     ResourceImportStrategyTypeType,
     ResourceMappingTypeType,
     ResourceResolutionStatusTypeType,
+    ResourceSourceTypeType,
     SopServiceTypeType,
     TemplateFormatType,
     TestRiskType,
     TestTypeType,
     ResilienceHubServiceName,
     ServiceName,
     ResourceServiceName,
@@ -315,43 +316,52 @@
 ### Typed dictionaries
 
 `types_aiobotocore_resiliencehub.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_resiliencehub.type_defs import (
-    ResponseMetadataTypeDef,
     RecommendationItemTypeDef,
     CostTypeDef,
     DisruptionComplianceTypeDef,
     ResiliencyScoreTypeDef,
     AppComponentTypeDef,
+    EksSourceClusterNamespaceTypeDef,
     TerraformSourceTypeDef,
     AppSummaryTypeDef,
     AppTypeDef,
     AppVersionSummaryTypeDef,
     RecommendationDisruptionComplianceTypeDef,
     CreateAppRequestRequestTypeDef,
     CreateAppVersionAppComponentRequestRequestTypeDef,
     LogicalResourceIdTypeDef,
     CreateRecommendationTemplateRequestRequestTypeDef,
     FailurePolicyTypeDef,
     DeleteAppAssessmentRequestRequestTypeDef,
+    DeleteAppAssessmentResponseTypeDef,
     DeleteAppRequestRequestTypeDef,
+    DeleteAppResponseTypeDef,
     DeleteAppVersionAppComponentRequestRequestTypeDef,
     DeleteRecommendationTemplateRequestRequestTypeDef,
+    DeleteRecommendationTemplateResponseTypeDef,
     DeleteResiliencyPolicyRequestRequestTypeDef,
+    DeleteResiliencyPolicyResponseTypeDef,
     DescribeAppAssessmentRequestRequestTypeDef,
     DescribeAppRequestRequestTypeDef,
     DescribeAppVersionAppComponentRequestRequestTypeDef,
     DescribeAppVersionRequestRequestTypeDef,
     DescribeAppVersionResourcesResolutionStatusRequestRequestTypeDef,
+    DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
+    DescribeAppVersionResponseTypeDef,
     DescribeAppVersionTemplateRequestRequestTypeDef,
+    DescribeAppVersionTemplateResponseTypeDef,
     DescribeDraftAppVersionResourcesImportStatusRequestRequestTypeDef,
+    DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
     DescribeResiliencyPolicyRequestRequestTypeDef,
+    EksSourceTypeDef,
     ListAlarmRecommendationsRequestRequestTypeDef,
     ListAppAssessmentsRequestRequestTypeDef,
     ListAppComponentCompliancesRequestRequestTypeDef,
     ListAppComponentRecommendationsRequestRequestTypeDef,
     ListAppInputSourcesRequestRequestTypeDef,
     ListAppVersionAppComponentsRequestRequestTypeDef,
     ListAppVersionResourceMappingsRequestRequestTypeDef,
@@ -359,70 +369,63 @@
     ListAppVersionsRequestRequestTypeDef,
     ListAppsRequestRequestTypeDef,
     ListRecommendationTemplatesRequestRequestTypeDef,
     ListResiliencyPoliciesRequestRequestTypeDef,
     ListSopRecommendationsRequestRequestTypeDef,
     ListSuggestedResiliencyPoliciesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListTestRecommendationsRequestRequestTypeDef,
     ListUnsupportedAppVersionResourcesRequestRequestTypeDef,
     PhysicalResourceIdTypeDef,
     PublishAppVersionRequestRequestTypeDef,
+    PublishAppVersionResponseTypeDef,
     PutDraftAppVersionTemplateRequestRequestTypeDef,
+    PutDraftAppVersionTemplateResponseTypeDef,
     S3LocationTypeDef,
     RemoveDraftAppVersionResourceMappingsRequestRequestTypeDef,
+    RemoveDraftAppVersionResourceMappingsResponseTypeDef,
     ResolveAppVersionResourcesRequestRequestTypeDef,
+    ResolveAppVersionResourcesResponseTypeDef,
     ResourceErrorTypeDef,
+    ResponseMetadataTypeDef,
     StartAppAssessmentRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAppRequestRequestTypeDef,
     UpdateAppVersionAppComponentRequestRequestTypeDef,
     UpdateAppVersionRequestRequestTypeDef,
-    DeleteAppAssessmentResponseTypeDef,
-    DeleteAppResponseTypeDef,
-    DeleteRecommendationTemplateResponseTypeDef,
-    DeleteResiliencyPolicyResponseTypeDef,
-    DescribeAppVersionResourcesResolutionStatusResponseTypeDef,
-    DescribeAppVersionResponseTypeDef,
-    DescribeAppVersionTemplateResponseTypeDef,
-    DescribeDraftAppVersionResourcesImportStatusResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PublishAppVersionResponseTypeDef,
-    PutDraftAppVersionTemplateResponseTypeDef,
-    RemoveDraftAppVersionResourceMappingsResponseTypeDef,
-    ResolveAppVersionResourcesResponseTypeDef,
     UpdateAppVersionResponseTypeDef,
     AlarmRecommendationTypeDef,
     SopRecommendationTypeDef,
     TestRecommendationTypeDef,
     AppAssessmentSummaryTypeDef,
     AppComponentComplianceTypeDef,
     CreateAppVersionAppComponentResponseTypeDef,
     DeleteAppVersionAppComponentResponseTypeDef,
     DescribeAppVersionAppComponentResponseTypeDef,
     ListAppVersionAppComponentsResponseTypeDef,
     UpdateAppVersionAppComponentResponseTypeDef,
     AppInputSourceTypeDef,
     DeleteAppInputSourceRequestRequestTypeDef,
-    ImportResourcesToDraftAppVersionRequestRequestTypeDef,
-    ImportResourcesToDraftAppVersionResponseTypeDef,
     ListAppsResponseTypeDef,
     CreateAppResponseTypeDef,
     DescribeAppResponseTypeDef,
     UpdateAppResponseTypeDef,
     ListAppVersionsResponseTypeDef,
     ConfigRecommendationTypeDef,
     CreateAppVersionResourceRequestRequestTypeDef,
     DeleteAppVersionResourceRequestRequestTypeDef,
     DescribeAppVersionResourceRequestRequestTypeDef,
     UpdateAppVersionResourceRequestRequestTypeDef,
     CreateResiliencyPolicyRequestRequestTypeDef,
     ResiliencyPolicyTypeDef,
     UpdateResiliencyPolicyRequestRequestTypeDef,
+    ImportResourcesToDraftAppVersionRequestRequestTypeDef,
+    ImportResourcesToDraftAppVersionResponseTypeDef,
     PhysicalResourceTypeDef,
     ResourceMappingTypeDef,
     UnsupportedResourceTypeDef,
     RecommendationTemplateTypeDef,
     ResourceErrorsDetailsTypeDef,
     ListAlarmRecommendationsResponseTypeDef,
     ListSopRecommendationsResponseTypeDef,
@@ -451,54 +454,54 @@
     AppAssessmentTypeDef,
     ListAppComponentRecommendationsResponseTypeDef,
     DescribeAppAssessmentResponseTypeDef,
     StartAppAssessmentResponseTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> RecommendationItemTypeDef:
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

### Comparing `types-aiobotocore-resiliencehub-2.5.0.post1/types_aiobotocore_resiliencehub.egg-info/SOURCES.txt` & `types-aiobotocore-resiliencehub-2.5.1/types_aiobotocore_resiliencehub.egg-info/SOURCES.txt`

 * *Files identical despite different names*

