# Comparing `tmp/types-aiobotocore-route53-recovery-readiness-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-route53-recovery-readiness-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-route53-recovery-readiness-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:13 2023, max compression
+gzip compressed data, was "types-aiobotocore-route53-recovery-readiness-2.5.1.tar", last modified: Wed Jun 28 01:44:05 2023, max compression
```

## Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1.tar` & `types-aiobotocore-route53-recovery-readiness-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.823564 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19429 2023-03-11 12:27:13.823564 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17784 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:13.823564 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2258 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.823564 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/
--rw-r--r--   0 runner    (1001) docker     (123)     2973 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2972 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1015 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    30666 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    30615 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9080 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9078 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13910 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    13897 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    29775 2023-03-11 12:22:42.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    29738 2023-03-11 12:22:42.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:22:41.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:13.823564 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19429 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-03-11 12:27:13.000000 types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.426204 types-aiobotocore-route53-recovery-readiness-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19440 2023-06-28 01:44:05.422204 types-aiobotocore-route53-recovery-readiness-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17801 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:05.426204 types-aiobotocore-route53-recovery-readiness-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2252 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.422204 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/
+-rw-r--r--   0 runner    (1001) docker     (123)     2973 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2972 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30666 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30615 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9289 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9287 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13810 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13798 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    29847 2023-06-28 01:39:29.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29810 2023-06-28 01:39:29.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:39:28.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:05.422204 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19440 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 01:44:05.000000 types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/LICENSE` & `types-aiobotocore-route53-recovery-readiness-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/PKG-INFO` & `types-aiobotocore-route53-recovery-readiness-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53-recovery-readiness
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53-recovery-readiness"></a>
 
 # types-aiobotocore-route53-recovery-readiness
 
 [![PyPI - types-aiobotocore-route53-recovery-readiness](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-readiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-readiness)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-readiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-readiness)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-readiness?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-readiness)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryReadiness 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness)
+[aiobotocore.Route53RecoveryReadiness 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness)
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
 [types-aiobotocore-route53-recovery-readiness docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/).
 
 See how it helps to find and fix potential bugs:
 
@@ -363,79 +363,79 @@
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_route53_recovery_readiness.type_defs import (
     CellOutputTypeDef,
     CreateCellRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCellResponseTypeDef,
     CreateCrossAccountAuthorizationRequestRequestTypeDef,
+    CreateCrossAccountAuthorizationResponseTypeDef,
     CreateReadinessCheckRequestRequestTypeDef,
+    CreateReadinessCheckResponseTypeDef,
     CreateRecoveryGroupRequestRequestTypeDef,
+    CreateRecoveryGroupResponseTypeDef,
     DeleteCellRequestRequestTypeDef,
     DeleteCrossAccountAuthorizationRequestRequestTypeDef,
     DeleteReadinessCheckRequestRequestTypeDef,
     DeleteRecoveryGroupRequestRequestTypeDef,
     DeleteResourceSetRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetArchitectureRecommendationsRequestRequestTypeDef,
     RecommendationTypeDef,
-    PaginatorConfigTypeDef,
+    GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
     GetCellReadinessSummaryRequestRequestTypeDef,
     ReadinessCheckSummaryTypeDef,
     GetCellRequestRequestTypeDef,
+    GetCellResponseTypeDef,
     GetReadinessCheckRequestRequestTypeDef,
+    GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
     GetReadinessCheckResourceStatusRequestRequestTypeDef,
+    GetReadinessCheckResponseTypeDef,
+    GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
     GetReadinessCheckStatusRequestRequestTypeDef,
     MessageTypeDef,
     ResourceResultTypeDef,
+    GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
     GetRecoveryGroupReadinessSummaryRequestRequestTypeDef,
     GetRecoveryGroupRequestRequestTypeDef,
+    GetRecoveryGroupResponseTypeDef,
     GetResourceSetRequestRequestTypeDef,
+    ListCellsRequestListCellsPaginateTypeDef,
     ListCellsRequestRequestTypeDef,
+    ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef,
     ListCrossAccountAuthorizationsRequestRequestTypeDef,
+    ListCrossAccountAuthorizationsResponseTypeDef,
+    ListReadinessChecksRequestListReadinessChecksPaginateTypeDef,
     ListReadinessChecksRequestRequestTypeDef,
     ReadinessCheckOutputTypeDef,
+    ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef,
     ListRecoveryGroupsRequestRequestTypeDef,
     RecoveryGroupOutputTypeDef,
+    ListResourceSetsRequestListResourceSetsPaginateTypeDef,
     ListResourceSetsRequestRequestTypeDef,
     ListRulesOutputTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     ListTagsForResourcesRequestRequestTypeDef,
+    ListTagsForResourcesResponseTypeDef,
     NLBResourceTypeDef,
+    PaginatorConfigTypeDef,
     R53ResourceRecordTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCellRequestRequestTypeDef,
-    UpdateReadinessCheckRequestRequestTypeDef,
-    UpdateRecoveryGroupRequestRequestTypeDef,
-    CreateCellResponseTypeDef,
-    CreateCrossAccountAuthorizationResponseTypeDef,
-    CreateReadinessCheckResponseTypeDef,
-    CreateRecoveryGroupResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCellResponseTypeDef,
-    GetReadinessCheckResponseTypeDef,
-    GetRecoveryGroupResponseTypeDef,
-    ListCellsResponseTypeDef,
-    ListCrossAccountAuthorizationsResponseTypeDef,
-    ListTagsForResourcesResponseTypeDef,
     UpdateCellResponseTypeDef,
+    UpdateReadinessCheckRequestRequestTypeDef,
     UpdateReadinessCheckResponseTypeDef,
+    UpdateRecoveryGroupRequestRequestTypeDef,
     UpdateRecoveryGroupResponseTypeDef,
+    ListCellsResponseTypeDef,
     GetArchitectureRecommendationsResponseTypeDef,
-    GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
-    GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
-    GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
-    GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
-    ListCellsRequestListCellsPaginateTypeDef,
-    ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef,
-    ListReadinessChecksRequestListReadinessChecksPaginateTypeDef,
-    ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef,
-    ListResourceSetsRequestListResourceSetsPaginateTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
     GetCellReadinessSummaryResponseTypeDef,
     GetRecoveryGroupReadinessSummaryResponseTypeDef,
     RuleResultTypeDef,
     GetReadinessCheckStatusResponseTypeDef,
     ListReadinessChecksResponseTypeDef,
     ListRecoveryGroupsResponseTypeDef,
     ListRulesResponseTypeDef,
@@ -460,43 +460,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/README.md` & `types-aiobotocore-route53-recovery-readiness-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-route53-recovery-readiness"></a>
 
 # types-aiobotocore-route53-recovery-readiness
 
 [![PyPI - types-aiobotocore-route53-recovery-readiness](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-readiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-readiness)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-readiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-readiness)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-readiness?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-readiness)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryReadiness 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness)
+[aiobotocore.Route53RecoveryReadiness 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness)
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
 [types-aiobotocore-route53-recovery-readiness docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/).
 
 See how it helps to find and fix potential bugs:
 
@@ -330,79 +330,79 @@
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_route53_recovery_readiness.type_defs import (
     CellOutputTypeDef,
     CreateCellRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCellResponseTypeDef,
     CreateCrossAccountAuthorizationRequestRequestTypeDef,
+    CreateCrossAccountAuthorizationResponseTypeDef,
     CreateReadinessCheckRequestRequestTypeDef,
+    CreateReadinessCheckResponseTypeDef,
     CreateRecoveryGroupRequestRequestTypeDef,
+    CreateRecoveryGroupResponseTypeDef,
     DeleteCellRequestRequestTypeDef,
     DeleteCrossAccountAuthorizationRequestRequestTypeDef,
     DeleteReadinessCheckRequestRequestTypeDef,
     DeleteRecoveryGroupRequestRequestTypeDef,
     DeleteResourceSetRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetArchitectureRecommendationsRequestRequestTypeDef,
     RecommendationTypeDef,
-    PaginatorConfigTypeDef,
+    GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
     GetCellReadinessSummaryRequestRequestTypeDef,
     ReadinessCheckSummaryTypeDef,
     GetCellRequestRequestTypeDef,
+    GetCellResponseTypeDef,
     GetReadinessCheckRequestRequestTypeDef,
+    GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
     GetReadinessCheckResourceStatusRequestRequestTypeDef,
+    GetReadinessCheckResponseTypeDef,
+    GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
     GetReadinessCheckStatusRequestRequestTypeDef,
     MessageTypeDef,
     ResourceResultTypeDef,
+    GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
     GetRecoveryGroupReadinessSummaryRequestRequestTypeDef,
     GetRecoveryGroupRequestRequestTypeDef,
+    GetRecoveryGroupResponseTypeDef,
     GetResourceSetRequestRequestTypeDef,
+    ListCellsRequestListCellsPaginateTypeDef,
     ListCellsRequestRequestTypeDef,
+    ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef,
     ListCrossAccountAuthorizationsRequestRequestTypeDef,
+    ListCrossAccountAuthorizationsResponseTypeDef,
+    ListReadinessChecksRequestListReadinessChecksPaginateTypeDef,
     ListReadinessChecksRequestRequestTypeDef,
     ReadinessCheckOutputTypeDef,
+    ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef,
     ListRecoveryGroupsRequestRequestTypeDef,
     RecoveryGroupOutputTypeDef,
+    ListResourceSetsRequestListResourceSetsPaginateTypeDef,
     ListResourceSetsRequestRequestTypeDef,
     ListRulesOutputTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     ListTagsForResourcesRequestRequestTypeDef,
+    ListTagsForResourcesResponseTypeDef,
     NLBResourceTypeDef,
+    PaginatorConfigTypeDef,
     R53ResourceRecordTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCellRequestRequestTypeDef,
-    UpdateReadinessCheckRequestRequestTypeDef,
-    UpdateRecoveryGroupRequestRequestTypeDef,
-    CreateCellResponseTypeDef,
-    CreateCrossAccountAuthorizationResponseTypeDef,
-    CreateReadinessCheckResponseTypeDef,
-    CreateRecoveryGroupResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCellResponseTypeDef,
-    GetReadinessCheckResponseTypeDef,
-    GetRecoveryGroupResponseTypeDef,
-    ListCellsResponseTypeDef,
-    ListCrossAccountAuthorizationsResponseTypeDef,
-    ListTagsForResourcesResponseTypeDef,
     UpdateCellResponseTypeDef,
+    UpdateReadinessCheckRequestRequestTypeDef,
     UpdateReadinessCheckResponseTypeDef,
+    UpdateRecoveryGroupRequestRequestTypeDef,
     UpdateRecoveryGroupResponseTypeDef,
+    ListCellsResponseTypeDef,
     GetArchitectureRecommendationsResponseTypeDef,
-    GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
-    GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
-    GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
-    GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
-    ListCellsRequestListCellsPaginateTypeDef,
-    ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef,
-    ListReadinessChecksRequestListReadinessChecksPaginateTypeDef,
-    ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef,
-    ListResourceSetsRequestListResourceSetsPaginateTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
     GetCellReadinessSummaryResponseTypeDef,
     GetRecoveryGroupReadinessSummaryResponseTypeDef,
     RuleResultTypeDef,
     GetReadinessCheckStatusResponseTypeDef,
     ListReadinessChecksResponseTypeDef,
     ListRecoveryGroupsResponseTypeDef,
     ListRulesResponseTypeDef,
@@ -427,43 +427,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/setup.py` & `types-aiobotocore-route53-recovery-readiness-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-route53-recovery-readiness.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-route53-recovery-readiness",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_route53_recovery_readiness"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.1 service generated with"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/",
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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/__init__.py` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/__init__.pyi` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/__main__.py` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/__main__.py`

 * *Files 25% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness\nOther"
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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/client.py` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/client.pyi` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/literals.py` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -108,14 +108,15 @@
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
@@ -194,14 +195,15 @@
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
@@ -212,14 +214,15 @@
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
@@ -255,14 +258,15 @@
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
@@ -281,16 +285,19 @@
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
@@ -374,15 +381,17 @@
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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/literals.pyi` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -106,14 +106,15 @@
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
@@ -192,14 +193,15 @@
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
@@ -210,14 +212,15 @@
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
@@ -253,14 +256,15 @@
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
@@ -279,16 +283,19 @@
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
@@ -372,15 +379,17 @@
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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/paginator.py` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_cross_account_authorizations_paginator: ListCrossAccountAuthorizationsPaginator = client.get_paginator("list_cross_account_authorizations")
         list_readiness_checks_paginator: ListReadinessChecksPaginator = client.get_paginator("list_readiness_checks")
         list_recovery_groups_paginator: ListRecoveryGroupsPaginator = client.get_paginator("list_recovery_groups")
         list_resource_sets_paginator: ListResourceSetsPaginator = client.get_paginator("list_resource_sets")
         list_rules_paginator: ListRulesPaginator = client.get_paginator("list_rules")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetCellReadinessSummaryResponseTypeDef,
     GetReadinessCheckResourceStatusResponseTypeDef,
@@ -54,20 +53,14 @@
     ListReadinessChecksResponseTypeDef,
     ListRecoveryGroupsResponseTypeDef,
     ListResourceSetsResponseTypeDef,
     ListRulesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetCellReadinessSummaryPaginator",
     "GetReadinessCheckResourceStatusPaginator",
     "GetReadinessCheckStatusPaginator",
     "GetRecoveryGroupReadinessSummaryPaginator",
     "ListCellsPaginator",
     "ListCrossAccountAuthorizationsPaginator",
@@ -91,15 +84,15 @@
 class GetCellReadinessSummaryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetCellReadinessSummary)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getcellreadinesssummarypaginator)
     """
 
     def paginate(
-        self, *, CellName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CellName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCellReadinessSummaryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetCellReadinessSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getcellreadinesssummarypaginator)
         """
 
 
@@ -110,133 +103,133 @@
     """
 
     def paginate(
         self,
         *,
         ReadinessCheckName: str,
         ResourceIdentifier: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReadinessCheckResourceStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetReadinessCheckResourceStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getreadinesscheckresourcestatuspaginator)
         """
 
 
 class GetReadinessCheckStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetReadinessCheckStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getreadinesscheckstatuspaginator)
     """
 
     def paginate(
-        self, *, ReadinessCheckName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ReadinessCheckName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReadinessCheckStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetReadinessCheckStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getreadinesscheckstatuspaginator)
         """
 
 
 class GetRecoveryGroupReadinessSummaryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetRecoveryGroupReadinessSummary)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getrecoverygroupreadinesssummarypaginator)
     """
 
     def paginate(
-        self, *, RecoveryGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RecoveryGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRecoveryGroupReadinessSummaryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetRecoveryGroupReadinessSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getrecoverygroupreadinesssummarypaginator)
         """
 
 
 class ListCellsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCells)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcellspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCellsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCells.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcellspaginator)
         """
 
 
 class ListCrossAccountAuthorizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCrossAccountAuthorizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcrossaccountauthorizationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCrossAccountAuthorizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCrossAccountAuthorizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcrossaccountauthorizationspaginator)
         """
 
 
 class ListReadinessChecksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListReadinessChecks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listreadinesscheckspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadinessChecksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListReadinessChecks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listreadinesscheckspaginator)
         """
 
 
 class ListRecoveryGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRecoveryGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrecoverygroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRecoveryGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrecoverygroupspaginator)
         """
 
 
 class ListResourceSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListResourceSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listresourcesetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListResourceSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listresourcesetspaginator)
         """
 
 
 class ListRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrulespaginator)
     """
 
     def paginate(
-        self, *, ResourceType: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceType: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrulespaginator)
         """
```

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/paginator.pyi` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_cross_account_authorizations_paginator: ListCrossAccountAuthorizationsPaginator = client.get_paginator("list_cross_account_authorizations")
         list_readiness_checks_paginator: ListReadinessChecksPaginator = client.get_paginator("list_readiness_checks")
         list_recovery_groups_paginator: ListRecoveryGroupsPaginator = client.get_paginator("list_recovery_groups")
         list_resource_sets_paginator: ListResourceSetsPaginator = client.get_paginator("list_resource_sets")
         list_rules_paginator: ListRulesPaginator = client.get_paginator("list_rules")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetCellReadinessSummaryResponseTypeDef,
     GetReadinessCheckResourceStatusResponseTypeDef,
@@ -54,19 +53,14 @@
     ListReadinessChecksResponseTypeDef,
     ListRecoveryGroupsResponseTypeDef,
     ListResourceSetsResponseTypeDef,
     ListRulesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetCellReadinessSummaryPaginator",
     "GetReadinessCheckResourceStatusPaginator",
     "GetReadinessCheckStatusPaginator",
     "GetRecoveryGroupReadinessSummaryPaginator",
     "ListCellsPaginator",
     "ListCrossAccountAuthorizationsPaginator",
@@ -87,15 +81,15 @@
 class GetCellReadinessSummaryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetCellReadinessSummary)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getcellreadinesssummarypaginator)
     """
 
     def paginate(
-        self, *, CellName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CellName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCellReadinessSummaryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetCellReadinessSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getcellreadinesssummarypaginator)
         """
 
 class GetReadinessCheckResourceStatusPaginator(AioPaginator):
@@ -105,125 +99,125 @@
     """
 
     def paginate(
         self,
         *,
         ReadinessCheckName: str,
         ResourceIdentifier: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReadinessCheckResourceStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetReadinessCheckResourceStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getreadinesscheckresourcestatuspaginator)
         """
 
 class GetReadinessCheckStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetReadinessCheckStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getreadinesscheckstatuspaginator)
     """
 
     def paginate(
-        self, *, ReadinessCheckName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ReadinessCheckName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetReadinessCheckStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetReadinessCheckStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getreadinesscheckstatuspaginator)
         """
 
 class GetRecoveryGroupReadinessSummaryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetRecoveryGroupReadinessSummary)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getrecoverygroupreadinesssummarypaginator)
     """
 
     def paginate(
-        self, *, RecoveryGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RecoveryGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRecoveryGroupReadinessSummaryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.GetRecoveryGroupReadinessSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#getrecoverygroupreadinesssummarypaginator)
         """
 
 class ListCellsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCells)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcellspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCellsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCells.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcellspaginator)
         """
 
 class ListCrossAccountAuthorizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCrossAccountAuthorizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcrossaccountauthorizationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCrossAccountAuthorizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListCrossAccountAuthorizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listcrossaccountauthorizationspaginator)
         """
 
 class ListReadinessChecksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListReadinessChecks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listreadinesscheckspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReadinessChecksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListReadinessChecks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listreadinesscheckspaginator)
         """
 
 class ListRecoveryGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRecoveryGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrecoverygroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecoveryGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRecoveryGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrecoverygroupspaginator)
         """
 
 class ListResourceSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListResourceSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listresourcesetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListResourceSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listresourcesetspaginator)
         """
 
 class ListRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrulespaginator)
     """
 
     def paginate(
-        self, *, ResourceType: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceType: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness.Paginator.ListRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/paginators/#listrulespaginator)
         """
```

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/type_defs.py` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -22,79 +22,79 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CellOutputTypeDef",
     "CreateCellRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateCellResponseTypeDef",
     "CreateCrossAccountAuthorizationRequestRequestTypeDef",
+    "CreateCrossAccountAuthorizationResponseTypeDef",
     "CreateReadinessCheckRequestRequestTypeDef",
+    "CreateReadinessCheckResponseTypeDef",
     "CreateRecoveryGroupRequestRequestTypeDef",
+    "CreateRecoveryGroupResponseTypeDef",
     "DeleteCellRequestRequestTypeDef",
     "DeleteCrossAccountAuthorizationRequestRequestTypeDef",
     "DeleteReadinessCheckRequestRequestTypeDef",
     "DeleteRecoveryGroupRequestRequestTypeDef",
     "DeleteResourceSetRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetArchitectureRecommendationsRequestRequestTypeDef",
     "RecommendationTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
     "GetCellReadinessSummaryRequestRequestTypeDef",
     "ReadinessCheckSummaryTypeDef",
     "GetCellRequestRequestTypeDef",
+    "GetCellResponseTypeDef",
     "GetReadinessCheckRequestRequestTypeDef",
+    "GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
     "GetReadinessCheckResourceStatusRequestRequestTypeDef",
+    "GetReadinessCheckResponseTypeDef",
+    "GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
     "GetReadinessCheckStatusRequestRequestTypeDef",
     "MessageTypeDef",
     "ResourceResultTypeDef",
+    "GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
     "GetRecoveryGroupReadinessSummaryRequestRequestTypeDef",
     "GetRecoveryGroupRequestRequestTypeDef",
+    "GetRecoveryGroupResponseTypeDef",
     "GetResourceSetRequestRequestTypeDef",
+    "ListCellsRequestListCellsPaginateTypeDef",
     "ListCellsRequestRequestTypeDef",
+    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
     "ListCrossAccountAuthorizationsRequestRequestTypeDef",
+    "ListCrossAccountAuthorizationsResponseTypeDef",
+    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
     "ListReadinessChecksRequestRequestTypeDef",
     "ReadinessCheckOutputTypeDef",
+    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
     "ListRecoveryGroupsRequestRequestTypeDef",
     "RecoveryGroupOutputTypeDef",
+    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
     "ListResourceSetsRequestRequestTypeDef",
     "ListRulesOutputTypeDef",
+    "ListRulesRequestListRulesPaginateTypeDef",
     "ListRulesRequestRequestTypeDef",
     "ListTagsForResourcesRequestRequestTypeDef",
+    "ListTagsForResourcesResponseTypeDef",
     "NLBResourceTypeDef",
+    "PaginatorConfigTypeDef",
     "R53ResourceRecordTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCellRequestRequestTypeDef",
-    "UpdateReadinessCheckRequestRequestTypeDef",
-    "UpdateRecoveryGroupRequestRequestTypeDef",
-    "CreateCellResponseTypeDef",
-    "CreateCrossAccountAuthorizationResponseTypeDef",
-    "CreateReadinessCheckResponseTypeDef",
-    "CreateRecoveryGroupResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCellResponseTypeDef",
-    "GetReadinessCheckResponseTypeDef",
-    "GetRecoveryGroupResponseTypeDef",
-    "ListCellsResponseTypeDef",
-    "ListCrossAccountAuthorizationsResponseTypeDef",
-    "ListTagsForResourcesResponseTypeDef",
     "UpdateCellResponseTypeDef",
+    "UpdateReadinessCheckRequestRequestTypeDef",
     "UpdateReadinessCheckResponseTypeDef",
+    "UpdateRecoveryGroupRequestRequestTypeDef",
     "UpdateRecoveryGroupResponseTypeDef",
+    "ListCellsResponseTypeDef",
     "GetArchitectureRecommendationsResponseTypeDef",
-    "GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
-    "GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
-    "GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
-    "GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
-    "ListCellsRequestListCellsPaginateTypeDef",
-    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
-    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
-    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
-    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
-    "ListRulesRequestListRulesPaginateTypeDef",
     "GetCellReadinessSummaryResponseTypeDef",
     "GetRecoveryGroupReadinessSummaryResponseTypeDef",
     "RuleResultTypeDef",
     "GetReadinessCheckStatusResponseTypeDef",
     "ListReadinessChecksResponseTypeDef",
     "ListRecoveryGroupsResponseTypeDef",
     "ListRulesResponseTypeDef",
@@ -151,32 +151,41 @@
 
 class CreateCellRequestRequestTypeDef(
     _RequiredCreateCellRequestRequestTypeDef, _OptionalCreateCellRequestRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateCellResponseTypeDef = TypedDict(
+    "CreateCellResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "CellArn": str,
+        "CellName": str,
+        "Cells": List[str],
+        "ParentReadinessScopes": List[str],
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCrossAccountAuthorizationRequestRequestTypeDef = TypedDict(
     "CreateCrossAccountAuthorizationRequestRequestTypeDef",
     {
         "CrossAccountAuthorization": str,
     },
 )
 
+CreateCrossAccountAuthorizationResponseTypeDef = TypedDict(
+    "CreateCrossAccountAuthorizationResponseTypeDef",
+    {
+        "CrossAccountAuthorization": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateReadinessCheckRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReadinessCheckRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
         "ResourceSetName": str,
     },
 )
@@ -192,14 +201,25 @@
 class CreateReadinessCheckRequestRequestTypeDef(
     _RequiredCreateReadinessCheckRequestRequestTypeDef,
     _OptionalCreateReadinessCheckRequestRequestTypeDef,
 ):
     pass
 
 
+CreateReadinessCheckResponseTypeDef = TypedDict(
+    "CreateReadinessCheckResponseTypeDef",
+    {
+        "ReadinessCheckArn": str,
+        "ReadinessCheckName": str,
+        "ResourceSet": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateRecoveryGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRecoveryGroupRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 _OptionalCreateRecoveryGroupRequestRequestTypeDef = TypedDict(
@@ -215,14 +235,25 @@
 class CreateRecoveryGroupRequestRequestTypeDef(
     _RequiredCreateRecoveryGroupRequestRequestTypeDef,
     _OptionalCreateRecoveryGroupRequestRequestTypeDef,
 ):
     pass
 
 
+CreateRecoveryGroupResponseTypeDef = TypedDict(
+    "CreateRecoveryGroupResponseTypeDef",
+    {
+        "Cells": List[str],
+        "RecoveryGroupArn": str,
+        "RecoveryGroupName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCellRequestRequestTypeDef = TypedDict(
     "DeleteCellRequestRequestTypeDef",
     {
         "CellName": str,
     },
 )
 
@@ -250,14 +281,21 @@
 DeleteResourceSetRequestRequestTypeDef = TypedDict(
     "DeleteResourceSetRequestRequestTypeDef",
     {
         "ResourceSetName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetArchitectureRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetArchitectureRecommendationsRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 _OptionalGetArchitectureRecommendationsRequestRequestTypeDef = TypedDict(
@@ -280,24 +318,36 @@
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "RecommendationText": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
+    "_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CellName": str,
+    },
+)
+_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
+    "_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef(
+    _RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
+    _OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetCellReadinessSummaryRequestRequestTypeDef = TypedDict(
     "_RequiredGetCellReadinessSummaryRequestRequestTypeDef",
     {
         "CellName": str,
     },
 )
 _OptionalGetCellReadinessSummaryRequestRequestTypeDef = TypedDict(
@@ -329,21 +379,56 @@
 GetCellRequestRequestTypeDef = TypedDict(
     "GetCellRequestRequestTypeDef",
     {
         "CellName": str,
     },
 )
 
+GetCellResponseTypeDef = TypedDict(
+    "GetCellResponseTypeDef",
+    {
+        "CellArn": str,
+        "CellName": str,
+        "Cells": List[str],
+        "ParentReadinessScopes": List[str],
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetReadinessCheckRequestRequestTypeDef = TypedDict(
     "GetReadinessCheckRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
     },
 )
 
+_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
+    "_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
+    {
+        "ReadinessCheckName": str,
+        "ResourceIdentifier": str,
+    },
+)
+_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
+    "_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef(
+    _RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
+    _OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetReadinessCheckResourceStatusRequestRequestTypeDef = TypedDict(
     "_RequiredGetReadinessCheckResourceStatusRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
         "ResourceIdentifier": str,
     },
 )
@@ -360,14 +445,47 @@
 class GetReadinessCheckResourceStatusRequestRequestTypeDef(
     _RequiredGetReadinessCheckResourceStatusRequestRequestTypeDef,
     _OptionalGetReadinessCheckResourceStatusRequestRequestTypeDef,
 ):
     pass
 
 
+GetReadinessCheckResponseTypeDef = TypedDict(
+    "GetReadinessCheckResponseTypeDef",
+    {
+        "ReadinessCheckArn": str,
+        "ReadinessCheckName": str,
+        "ResourceSet": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
+    "_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
+    {
+        "ReadinessCheckName": str,
+    },
+)
+_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
+    "_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef(
+    _RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
+    _OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetReadinessCheckStatusRequestRequestTypeDef = TypedDict(
     "_RequiredGetReadinessCheckStatusRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
     },
 )
 _OptionalGetReadinessCheckStatusRequestRequestTypeDef = TypedDict(
@@ -412,14 +530,36 @@
 )
 
 
 class ResourceResultTypeDef(_RequiredResourceResultTypeDef, _OptionalResourceResultTypeDef):
     pass
 
 
+_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
+    "_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
+    {
+        "RecoveryGroupName": str,
+    },
+)
+_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
+    "_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef(
+    _RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
+    _OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetRecoveryGroupReadinessSummaryRequestRequestTypeDef = TypedDict(
     "_RequiredGetRecoveryGroupReadinessSummaryRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 _OptionalGetRecoveryGroupReadinessSummaryRequestRequestTypeDef = TypedDict(
@@ -442,39 +582,83 @@
 GetRecoveryGroupRequestRequestTypeDef = TypedDict(
     "GetRecoveryGroupRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 
+GetRecoveryGroupResponseTypeDef = TypedDict(
+    "GetRecoveryGroupResponseTypeDef",
+    {
+        "Cells": List[str],
+        "RecoveryGroupArn": str,
+        "RecoveryGroupName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourceSetRequestRequestTypeDef = TypedDict(
     "GetResourceSetRequestRequestTypeDef",
     {
         "ResourceSetName": str,
     },
 )
 
+ListCellsRequestListCellsPaginateTypeDef = TypedDict(
+    "ListCellsRequestListCellsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCellsRequestRequestTypeDef = TypedDict(
     "ListCellsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef = TypedDict(
+    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCrossAccountAuthorizationsRequestRequestTypeDef = TypedDict(
     "ListCrossAccountAuthorizationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCrossAccountAuthorizationsResponseTypeDef = TypedDict(
+    "ListCrossAccountAuthorizationsResponseTypeDef",
+    {
+        "CrossAccountAuthorizations": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReadinessChecksRequestListReadinessChecksPaginateTypeDef = TypedDict(
+    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReadinessChecksRequestRequestTypeDef = TypedDict(
     "ListReadinessChecksRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -499,14 +683,22 @@
 
 class ReadinessCheckOutputTypeDef(
     _RequiredReadinessCheckOutputTypeDef, _OptionalReadinessCheckOutputTypeDef
 ):
     pass
 
 
+ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef = TypedDict(
+    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecoveryGroupsRequestRequestTypeDef = TypedDict(
     "ListRecoveryGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -531,14 +723,22 @@
 
 class RecoveryGroupOutputTypeDef(
     _RequiredRecoveryGroupOutputTypeDef, _OptionalRecoveryGroupOutputTypeDef
 ):
     pass
 
 
+ListResourceSetsRequestListResourceSetsPaginateTypeDef = TypedDict(
+    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceSetsRequestRequestTypeDef = TypedDict(
     "ListResourceSetsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -549,14 +749,23 @@
     {
         "ResourceType": str,
         "RuleDescription": str,
         "RuleId": str,
     },
 )
 
+ListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "ListRulesRequestListRulesPaginateTypeDef",
+    {
+        "ResourceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRulesRequestRequestTypeDef = TypedDict(
     "ListRulesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "ResourceType": str,
     },
@@ -566,31 +775,60 @@
 ListTagsForResourcesRequestRequestTypeDef = TypedDict(
     "ListTagsForResourcesRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourcesResponseTypeDef = TypedDict(
+    "ListTagsForResourcesResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NLBResourceTypeDef = TypedDict(
     "NLBResourceTypeDef",
     {
         "Arn": str,
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
 R53ResourceRecordTypeDef = TypedDict(
     "R53ResourceRecordTypeDef",
     {
         "DomainName": str,
         "RecordSetId": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -607,338 +845,100 @@
     "UpdateCellRequestRequestTypeDef",
     {
         "CellName": str,
         "Cells": Sequence[str],
     },
 )
 
-UpdateReadinessCheckRequestRequestTypeDef = TypedDict(
-    "UpdateReadinessCheckRequestRequestTypeDef",
-    {
-        "ReadinessCheckName": str,
-        "ResourceSetName": str,
-    },
-)
-
-UpdateRecoveryGroupRequestRequestTypeDef = TypedDict(
-    "UpdateRecoveryGroupRequestRequestTypeDef",
-    {
-        "Cells": Sequence[str],
-        "RecoveryGroupName": str,
-    },
-)
-
-CreateCellResponseTypeDef = TypedDict(
-    "CreateCellResponseTypeDef",
+UpdateCellResponseTypeDef = TypedDict(
+    "UpdateCellResponseTypeDef",
     {
         "CellArn": str,
         "CellName": str,
         "Cells": List[str],
         "ParentReadinessScopes": List[str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateCrossAccountAuthorizationResponseTypeDef = TypedDict(
-    "CreateCrossAccountAuthorizationResponseTypeDef",
+UpdateReadinessCheckRequestRequestTypeDef = TypedDict(
+    "UpdateReadinessCheckRequestRequestTypeDef",
     {
-        "CrossAccountAuthorization": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ReadinessCheckName": str,
+        "ResourceSetName": str,
     },
 )
 
-CreateReadinessCheckResponseTypeDef = TypedDict(
-    "CreateReadinessCheckResponseTypeDef",
+UpdateReadinessCheckResponseTypeDef = TypedDict(
+    "UpdateReadinessCheckResponseTypeDef",
     {
         "ReadinessCheckArn": str,
         "ReadinessCheckName": str,
         "ResourceSet": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateRecoveryGroupResponseTypeDef = TypedDict(
-    "CreateRecoveryGroupResponseTypeDef",
+UpdateRecoveryGroupRequestRequestTypeDef = TypedDict(
+    "UpdateRecoveryGroupRequestRequestTypeDef",
     {
-        "Cells": List[str],
-        "RecoveryGroupArn": str,
+        "Cells": Sequence[str],
         "RecoveryGroupName": str,
-        "Tags": Dict[str, str],
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
-GetCellResponseTypeDef = TypedDict(
-    "GetCellResponseTypeDef",
-    {
-        "CellArn": str,
-        "CellName": str,
-        "Cells": List[str],
-        "ParentReadinessScopes": List[str],
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetReadinessCheckResponseTypeDef = TypedDict(
-    "GetReadinessCheckResponseTypeDef",
-    {
-        "ReadinessCheckArn": str,
-        "ReadinessCheckName": str,
-        "ResourceSet": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-GetRecoveryGroupResponseTypeDef = TypedDict(
-    "GetRecoveryGroupResponseTypeDef",
+UpdateRecoveryGroupResponseTypeDef = TypedDict(
+    "UpdateRecoveryGroupResponseTypeDef",
     {
         "Cells": List[str],
         "RecoveryGroupArn": str,
         "RecoveryGroupName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCellsResponseTypeDef = TypedDict(
     "ListCellsResponseTypeDef",
     {
         "Cells": List[CellOutputTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCrossAccountAuthorizationsResponseTypeDef = TypedDict(
-    "ListCrossAccountAuthorizationsResponseTypeDef",
-    {
-        "CrossAccountAuthorizations": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourcesResponseTypeDef = TypedDict(
-    "ListTagsForResourcesResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCellResponseTypeDef = TypedDict(
-    "UpdateCellResponseTypeDef",
-    {
-        "CellArn": str,
-        "CellName": str,
-        "Cells": List[str],
-        "ParentReadinessScopes": List[str],
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateReadinessCheckResponseTypeDef = TypedDict(
-    "UpdateReadinessCheckResponseTypeDef",
-    {
-        "ReadinessCheckArn": str,
-        "ReadinessCheckName": str,
-        "ResourceSet": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRecoveryGroupResponseTypeDef = TypedDict(
-    "UpdateRecoveryGroupResponseTypeDef",
-    {
-        "Cells": List[str],
-        "RecoveryGroupArn": str,
-        "RecoveryGroupName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetArchitectureRecommendationsResponseTypeDef = TypedDict(
     "GetArchitectureRecommendationsResponseTypeDef",
     {
         "LastAuditTimestamp": datetime,
         "NextToken": str,
         "Recommendations": List[RecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
-    "_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
-    {
-        "CellName": str,
-    },
-)
-_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
-    "_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef(
-    _RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
-    _OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
-    "_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
-    {
-        "ReadinessCheckName": str,
-        "ResourceIdentifier": str,
-    },
-)
-_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
-    "_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef(
-    _RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
-    _OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
-    "_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
-    {
-        "ReadinessCheckName": str,
-    },
-)
-_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
-    "_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef(
-    _RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
-    _OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
-    "_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
-    {
-        "RecoveryGroupName": str,
-    },
-)
-_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
-    "_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef(
-    _RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
-    _OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
-):
-    pass
-
-
-ListCellsRequestListCellsPaginateTypeDef = TypedDict(
-    "ListCellsRequestListCellsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef = TypedDict(
-    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReadinessChecksRequestListReadinessChecksPaginateTypeDef = TypedDict(
-    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef = TypedDict(
-    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResourceSetsRequestListResourceSetsPaginateTypeDef = TypedDict(
-    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "ListRulesRequestListRulesPaginateTypeDef",
-    {
-        "ResourceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 GetCellReadinessSummaryResponseTypeDef = TypedDict(
     "GetCellReadinessSummaryResponseTypeDef",
     {
         "NextToken": str,
         "Readiness": ReadinessType,
         "ReadinessChecks": List[ReadinessCheckSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecoveryGroupReadinessSummaryResponseTypeDef = TypedDict(
     "GetRecoveryGroupReadinessSummaryResponseTypeDef",
     {
         "NextToken": str,
         "Readiness": ReadinessType,
         "ReadinessChecks": List[ReadinessCheckSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuleResultTypeDef = TypedDict(
     "RuleResultTypeDef",
     {
         "LastCheckedTimestamp": datetime,
@@ -951,42 +951,42 @@
 GetReadinessCheckStatusResponseTypeDef = TypedDict(
     "GetReadinessCheckStatusResponseTypeDef",
     {
         "Messages": List[MessageTypeDef],
         "NextToken": str,
         "Readiness": ReadinessType,
         "Resources": List[ResourceResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReadinessChecksResponseTypeDef = TypedDict(
     "ListReadinessChecksResponseTypeDef",
     {
         "NextToken": str,
         "ReadinessChecks": List[ReadinessCheckOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryGroupsResponseTypeDef = TypedDict(
     "ListRecoveryGroupsResponseTypeDef",
     {
         "NextToken": str,
         "RecoveryGroups": List[RecoveryGroupOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRulesResponseTypeDef = TypedDict(
     "ListRulesResponseTypeDef",
     {
         "NextToken": str,
         "Rules": List[ListRulesOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetResourceTypeDef = TypedDict(
     "TargetResourceTypeDef",
     {
         "NLBResource": NLBResourceTypeDef,
@@ -997,15 +997,15 @@
 
 GetReadinessCheckResourceStatusResponseTypeDef = TypedDict(
     "GetReadinessCheckResourceStatusResponseTypeDef",
     {
         "NextToken": str,
         "Readiness": ReadinessType,
         "Rules": List[RuleResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DNSTargetResourceTypeDef = TypedDict(
     "DNSTargetResourceTypeDef",
     {
         "DomainName": str,
@@ -1055,27 +1055,27 @@
     "CreateResourceSetResponseTypeDef",
     {
         "ResourceSetArn": str,
         "ResourceSetName": str,
         "ResourceSetType": str,
         "Resources": List[ResourceTypeDef],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceSetResponseTypeDef = TypedDict(
     "GetResourceSetResponseTypeDef",
     {
         "ResourceSetArn": str,
         "ResourceSetName": str,
         "ResourceSetType": str,
         "Resources": List[ResourceTypeDef],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResourceSetOutputTypeDef = TypedDict(
     "_RequiredResourceSetOutputTypeDef",
     {
         "ResourceSetArn": str,
@@ -1112,19 +1112,19 @@
     "UpdateResourceSetResponseTypeDef",
     {
         "ResourceSetArn": str,
         "ResourceSetName": str,
         "ResourceSetType": str,
         "Resources": List[ResourceTypeDef],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceSetsResponseTypeDef = TypedDict(
     "ListResourceSetsResponseTypeDef",
     {
         "NextToken": str,
         "ResourceSets": List[ResourceSetOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness/type_defs.pyi` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -21,79 +21,79 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CellOutputTypeDef",
     "CreateCellRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateCellResponseTypeDef",
     "CreateCrossAccountAuthorizationRequestRequestTypeDef",
+    "CreateCrossAccountAuthorizationResponseTypeDef",
     "CreateReadinessCheckRequestRequestTypeDef",
+    "CreateReadinessCheckResponseTypeDef",
     "CreateRecoveryGroupRequestRequestTypeDef",
+    "CreateRecoveryGroupResponseTypeDef",
     "DeleteCellRequestRequestTypeDef",
     "DeleteCrossAccountAuthorizationRequestRequestTypeDef",
     "DeleteReadinessCheckRequestRequestTypeDef",
     "DeleteRecoveryGroupRequestRequestTypeDef",
     "DeleteResourceSetRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetArchitectureRecommendationsRequestRequestTypeDef",
     "RecommendationTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
     "GetCellReadinessSummaryRequestRequestTypeDef",
     "ReadinessCheckSummaryTypeDef",
     "GetCellRequestRequestTypeDef",
+    "GetCellResponseTypeDef",
     "GetReadinessCheckRequestRequestTypeDef",
+    "GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
     "GetReadinessCheckResourceStatusRequestRequestTypeDef",
+    "GetReadinessCheckResponseTypeDef",
+    "GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
     "GetReadinessCheckStatusRequestRequestTypeDef",
     "MessageTypeDef",
     "ResourceResultTypeDef",
+    "GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
     "GetRecoveryGroupReadinessSummaryRequestRequestTypeDef",
     "GetRecoveryGroupRequestRequestTypeDef",
+    "GetRecoveryGroupResponseTypeDef",
     "GetResourceSetRequestRequestTypeDef",
+    "ListCellsRequestListCellsPaginateTypeDef",
     "ListCellsRequestRequestTypeDef",
+    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
     "ListCrossAccountAuthorizationsRequestRequestTypeDef",
+    "ListCrossAccountAuthorizationsResponseTypeDef",
+    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
     "ListReadinessChecksRequestRequestTypeDef",
     "ReadinessCheckOutputTypeDef",
+    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
     "ListRecoveryGroupsRequestRequestTypeDef",
     "RecoveryGroupOutputTypeDef",
+    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
     "ListResourceSetsRequestRequestTypeDef",
     "ListRulesOutputTypeDef",
+    "ListRulesRequestListRulesPaginateTypeDef",
     "ListRulesRequestRequestTypeDef",
     "ListTagsForResourcesRequestRequestTypeDef",
+    "ListTagsForResourcesResponseTypeDef",
     "NLBResourceTypeDef",
+    "PaginatorConfigTypeDef",
     "R53ResourceRecordTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCellRequestRequestTypeDef",
-    "UpdateReadinessCheckRequestRequestTypeDef",
-    "UpdateRecoveryGroupRequestRequestTypeDef",
-    "CreateCellResponseTypeDef",
-    "CreateCrossAccountAuthorizationResponseTypeDef",
-    "CreateReadinessCheckResponseTypeDef",
-    "CreateRecoveryGroupResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCellResponseTypeDef",
-    "GetReadinessCheckResponseTypeDef",
-    "GetRecoveryGroupResponseTypeDef",
-    "ListCellsResponseTypeDef",
-    "ListCrossAccountAuthorizationsResponseTypeDef",
-    "ListTagsForResourcesResponseTypeDef",
     "UpdateCellResponseTypeDef",
+    "UpdateReadinessCheckRequestRequestTypeDef",
     "UpdateReadinessCheckResponseTypeDef",
+    "UpdateRecoveryGroupRequestRequestTypeDef",
     "UpdateRecoveryGroupResponseTypeDef",
+    "ListCellsResponseTypeDef",
     "GetArchitectureRecommendationsResponseTypeDef",
-    "GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
-    "GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
-    "GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
-    "GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
-    "ListCellsRequestListCellsPaginateTypeDef",
-    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
-    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
-    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
-    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
-    "ListRulesRequestListRulesPaginateTypeDef",
     "GetCellReadinessSummaryResponseTypeDef",
     "GetRecoveryGroupReadinessSummaryResponseTypeDef",
     "RuleResultTypeDef",
     "GetReadinessCheckStatusResponseTypeDef",
     "ListReadinessChecksResponseTypeDef",
     "ListRecoveryGroupsResponseTypeDef",
     "ListRulesResponseTypeDef",
@@ -146,32 +146,41 @@
 )
 
 class CreateCellRequestRequestTypeDef(
     _RequiredCreateCellRequestRequestTypeDef, _OptionalCreateCellRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateCellResponseTypeDef = TypedDict(
+    "CreateCellResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "CellArn": str,
+        "CellName": str,
+        "Cells": List[str],
+        "ParentReadinessScopes": List[str],
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCrossAccountAuthorizationRequestRequestTypeDef = TypedDict(
     "CreateCrossAccountAuthorizationRequestRequestTypeDef",
     {
         "CrossAccountAuthorization": str,
     },
 )
 
+CreateCrossAccountAuthorizationResponseTypeDef = TypedDict(
+    "CreateCrossAccountAuthorizationResponseTypeDef",
+    {
+        "CrossAccountAuthorization": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateReadinessCheckRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReadinessCheckRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
         "ResourceSetName": str,
     },
 )
@@ -185,14 +194,25 @@
 
 class CreateReadinessCheckRequestRequestTypeDef(
     _RequiredCreateReadinessCheckRequestRequestTypeDef,
     _OptionalCreateReadinessCheckRequestRequestTypeDef,
 ):
     pass
 
+CreateReadinessCheckResponseTypeDef = TypedDict(
+    "CreateReadinessCheckResponseTypeDef",
+    {
+        "ReadinessCheckArn": str,
+        "ReadinessCheckName": str,
+        "ResourceSet": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateRecoveryGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRecoveryGroupRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 _OptionalCreateRecoveryGroupRequestRequestTypeDef = TypedDict(
@@ -206,14 +226,25 @@
 
 class CreateRecoveryGroupRequestRequestTypeDef(
     _RequiredCreateRecoveryGroupRequestRequestTypeDef,
     _OptionalCreateRecoveryGroupRequestRequestTypeDef,
 ):
     pass
 
+CreateRecoveryGroupResponseTypeDef = TypedDict(
+    "CreateRecoveryGroupResponseTypeDef",
+    {
+        "Cells": List[str],
+        "RecoveryGroupArn": str,
+        "RecoveryGroupName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCellRequestRequestTypeDef = TypedDict(
     "DeleteCellRequestRequestTypeDef",
     {
         "CellName": str,
     },
 )
 
@@ -241,14 +272,21 @@
 DeleteResourceSetRequestRequestTypeDef = TypedDict(
     "DeleteResourceSetRequestRequestTypeDef",
     {
         "ResourceSetName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetArchitectureRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredGetArchitectureRecommendationsRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 _OptionalGetArchitectureRecommendationsRequestRequestTypeDef = TypedDict(
@@ -269,24 +307,34 @@
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "RecommendationText": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
+    "_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CellName": str,
+    },
+)
+_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
+    "_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef(
+    _RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
+    _OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetCellReadinessSummaryRequestRequestTypeDef = TypedDict(
     "_RequiredGetCellReadinessSummaryRequestRequestTypeDef",
     {
         "CellName": str,
     },
 )
 _OptionalGetCellReadinessSummaryRequestRequestTypeDef = TypedDict(
@@ -316,21 +364,54 @@
 GetCellRequestRequestTypeDef = TypedDict(
     "GetCellRequestRequestTypeDef",
     {
         "CellName": str,
     },
 )
 
+GetCellResponseTypeDef = TypedDict(
+    "GetCellResponseTypeDef",
+    {
+        "CellArn": str,
+        "CellName": str,
+        "Cells": List[str],
+        "ParentReadinessScopes": List[str],
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetReadinessCheckRequestRequestTypeDef = TypedDict(
     "GetReadinessCheckRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
     },
 )
 
+_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
+    "_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
+    {
+        "ReadinessCheckName": str,
+        "ResourceIdentifier": str,
+    },
+)
+_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
+    "_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef(
+    _RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
+    _OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
+):
+    pass
+
 _RequiredGetReadinessCheckResourceStatusRequestRequestTypeDef = TypedDict(
     "_RequiredGetReadinessCheckResourceStatusRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
         "ResourceIdentifier": str,
     },
 )
@@ -345,14 +426,45 @@
 
 class GetReadinessCheckResourceStatusRequestRequestTypeDef(
     _RequiredGetReadinessCheckResourceStatusRequestRequestTypeDef,
     _OptionalGetReadinessCheckResourceStatusRequestRequestTypeDef,
 ):
     pass
 
+GetReadinessCheckResponseTypeDef = TypedDict(
+    "GetReadinessCheckResponseTypeDef",
+    {
+        "ReadinessCheckArn": str,
+        "ReadinessCheckName": str,
+        "ResourceSet": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
+    "_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
+    {
+        "ReadinessCheckName": str,
+    },
+)
+_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
+    "_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef(
+    _RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
+    _OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
+):
+    pass
+
 _RequiredGetReadinessCheckStatusRequestRequestTypeDef = TypedDict(
     "_RequiredGetReadinessCheckStatusRequestRequestTypeDef",
     {
         "ReadinessCheckName": str,
     },
 )
 _OptionalGetReadinessCheckStatusRequestRequestTypeDef = TypedDict(
@@ -393,14 +505,34 @@
     },
     total=False,
 )
 
 class ResourceResultTypeDef(_RequiredResourceResultTypeDef, _OptionalResourceResultTypeDef):
     pass
 
+_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
+    "_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
+    {
+        "RecoveryGroupName": str,
+    },
+)
+_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
+    "_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef(
+    _RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
+    _OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetRecoveryGroupReadinessSummaryRequestRequestTypeDef = TypedDict(
     "_RequiredGetRecoveryGroupReadinessSummaryRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 _OptionalGetRecoveryGroupReadinessSummaryRequestRequestTypeDef = TypedDict(
@@ -421,39 +553,83 @@
 GetRecoveryGroupRequestRequestTypeDef = TypedDict(
     "GetRecoveryGroupRequestRequestTypeDef",
     {
         "RecoveryGroupName": str,
     },
 )
 
+GetRecoveryGroupResponseTypeDef = TypedDict(
+    "GetRecoveryGroupResponseTypeDef",
+    {
+        "Cells": List[str],
+        "RecoveryGroupArn": str,
+        "RecoveryGroupName": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourceSetRequestRequestTypeDef = TypedDict(
     "GetResourceSetRequestRequestTypeDef",
     {
         "ResourceSetName": str,
     },
 )
 
+ListCellsRequestListCellsPaginateTypeDef = TypedDict(
+    "ListCellsRequestListCellsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCellsRequestRequestTypeDef = TypedDict(
     "ListCellsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef = TypedDict(
+    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCrossAccountAuthorizationsRequestRequestTypeDef = TypedDict(
     "ListCrossAccountAuthorizationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCrossAccountAuthorizationsResponseTypeDef = TypedDict(
+    "ListCrossAccountAuthorizationsResponseTypeDef",
+    {
+        "CrossAccountAuthorizations": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListReadinessChecksRequestListReadinessChecksPaginateTypeDef = TypedDict(
+    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReadinessChecksRequestRequestTypeDef = TypedDict(
     "ListReadinessChecksRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -476,14 +652,22 @@
 )
 
 class ReadinessCheckOutputTypeDef(
     _RequiredReadinessCheckOutputTypeDef, _OptionalReadinessCheckOutputTypeDef
 ):
     pass
 
+ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef = TypedDict(
+    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecoveryGroupsRequestRequestTypeDef = TypedDict(
     "ListRecoveryGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -506,14 +690,22 @@
 )
 
 class RecoveryGroupOutputTypeDef(
     _RequiredRecoveryGroupOutputTypeDef, _OptionalRecoveryGroupOutputTypeDef
 ):
     pass
 
+ListResourceSetsRequestListResourceSetsPaginateTypeDef = TypedDict(
+    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResourceSetsRequestRequestTypeDef = TypedDict(
     "ListResourceSetsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -524,14 +716,23 @@
     {
         "ResourceType": str,
         "RuleDescription": str,
         "RuleId": str,
     },
 )
 
+ListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "ListRulesRequestListRulesPaginateTypeDef",
+    {
+        "ResourceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRulesRequestRequestTypeDef = TypedDict(
     "ListRulesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "ResourceType": str,
     },
@@ -541,31 +742,60 @@
 ListTagsForResourcesRequestRequestTypeDef = TypedDict(
     "ListTagsForResourcesRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourcesResponseTypeDef = TypedDict(
+    "ListTagsForResourcesResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NLBResourceTypeDef = TypedDict(
     "NLBResourceTypeDef",
     {
         "Arn": str,
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
 R53ResourceRecordTypeDef = TypedDict(
     "R53ResourceRecordTypeDef",
     {
         "DomainName": str,
         "RecordSetId": str,
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -582,330 +812,100 @@
     "UpdateCellRequestRequestTypeDef",
     {
         "CellName": str,
         "Cells": Sequence[str],
     },
 )
 
-UpdateReadinessCheckRequestRequestTypeDef = TypedDict(
-    "UpdateReadinessCheckRequestRequestTypeDef",
-    {
-        "ReadinessCheckName": str,
-        "ResourceSetName": str,
-    },
-)
-
-UpdateRecoveryGroupRequestRequestTypeDef = TypedDict(
-    "UpdateRecoveryGroupRequestRequestTypeDef",
-    {
-        "Cells": Sequence[str],
-        "RecoveryGroupName": str,
-    },
-)
-
-CreateCellResponseTypeDef = TypedDict(
-    "CreateCellResponseTypeDef",
+UpdateCellResponseTypeDef = TypedDict(
+    "UpdateCellResponseTypeDef",
     {
         "CellArn": str,
         "CellName": str,
         "Cells": List[str],
         "ParentReadinessScopes": List[str],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateCrossAccountAuthorizationResponseTypeDef = TypedDict(
-    "CreateCrossAccountAuthorizationResponseTypeDef",
+UpdateReadinessCheckRequestRequestTypeDef = TypedDict(
+    "UpdateReadinessCheckRequestRequestTypeDef",
     {
-        "CrossAccountAuthorization": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ReadinessCheckName": str,
+        "ResourceSetName": str,
     },
 )
 
-CreateReadinessCheckResponseTypeDef = TypedDict(
-    "CreateReadinessCheckResponseTypeDef",
+UpdateReadinessCheckResponseTypeDef = TypedDict(
+    "UpdateReadinessCheckResponseTypeDef",
     {
         "ReadinessCheckArn": str,
         "ReadinessCheckName": str,
         "ResourceSet": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateRecoveryGroupResponseTypeDef = TypedDict(
-    "CreateRecoveryGroupResponseTypeDef",
+UpdateRecoveryGroupRequestRequestTypeDef = TypedDict(
+    "UpdateRecoveryGroupRequestRequestTypeDef",
     {
-        "Cells": List[str],
-        "RecoveryGroupArn": str,
+        "Cells": Sequence[str],
         "RecoveryGroupName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-GetCellResponseTypeDef = TypedDict(
-    "GetCellResponseTypeDef",
-    {
-        "CellArn": str,
-        "CellName": str,
-        "Cells": List[str],
-        "ParentReadinessScopes": List[str],
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetReadinessCheckResponseTypeDef = TypedDict(
-    "GetReadinessCheckResponseTypeDef",
-    {
-        "ReadinessCheckArn": str,
-        "ReadinessCheckName": str,
-        "ResourceSet": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRecoveryGroupResponseTypeDef = TypedDict(
-    "GetRecoveryGroupResponseTypeDef",
+UpdateRecoveryGroupResponseTypeDef = TypedDict(
+    "UpdateRecoveryGroupResponseTypeDef",
     {
         "Cells": List[str],
         "RecoveryGroupArn": str,
         "RecoveryGroupName": str,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCellsResponseTypeDef = TypedDict(
     "ListCellsResponseTypeDef",
     {
         "Cells": List[CellOutputTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCrossAccountAuthorizationsResponseTypeDef = TypedDict(
-    "ListCrossAccountAuthorizationsResponseTypeDef",
-    {
-        "CrossAccountAuthorizations": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourcesResponseTypeDef = TypedDict(
-    "ListTagsForResourcesResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCellResponseTypeDef = TypedDict(
-    "UpdateCellResponseTypeDef",
-    {
-        "CellArn": str,
-        "CellName": str,
-        "Cells": List[str],
-        "ParentReadinessScopes": List[str],
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateReadinessCheckResponseTypeDef = TypedDict(
-    "UpdateReadinessCheckResponseTypeDef",
-    {
-        "ReadinessCheckArn": str,
-        "ReadinessCheckName": str,
-        "ResourceSet": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRecoveryGroupResponseTypeDef = TypedDict(
-    "UpdateRecoveryGroupResponseTypeDef",
-    {
-        "Cells": List[str],
-        "RecoveryGroupArn": str,
-        "RecoveryGroupName": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetArchitectureRecommendationsResponseTypeDef = TypedDict(
     "GetArchitectureRecommendationsResponseTypeDef",
     {
         "LastAuditTimestamp": datetime,
         "NextToken": str,
         "Recommendations": List[RecommendationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
-    "_RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
-    {
-        "CellName": str,
-    },
-)
-_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef = TypedDict(
-    "_OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef(
-    _RequiredGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
-    _OptionalGetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
-):
-    pass
-
-_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
-    "_RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
-    {
-        "ReadinessCheckName": str,
-        "ResourceIdentifier": str,
-    },
-)
-_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef = TypedDict(
-    "_OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef(
-    _RequiredGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
-    _OptionalGetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
-):
-    pass
-
-_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
-    "_RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
-    {
-        "ReadinessCheckName": str,
-    },
-)
-_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef = TypedDict(
-    "_OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef(
-    _RequiredGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
-    _OptionalGetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
-):
-    pass
-
-_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
-    "_RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
-    {
-        "RecoveryGroupName": str,
-    },
-)
-_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef = TypedDict(
-    "_OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-class GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef(
-    _RequiredGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
-    _OptionalGetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
-):
-    pass
-
-ListCellsRequestListCellsPaginateTypeDef = TypedDict(
-    "ListCellsRequestListCellsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef = TypedDict(
-    "ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReadinessChecksRequestListReadinessChecksPaginateTypeDef = TypedDict(
-    "ListReadinessChecksRequestListReadinessChecksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef = TypedDict(
-    "ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResourceSetsRequestListResourceSetsPaginateTypeDef = TypedDict(
-    "ListResourceSetsRequestListResourceSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "ListRulesRequestListRulesPaginateTypeDef",
-    {
-        "ResourceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 GetCellReadinessSummaryResponseTypeDef = TypedDict(
     "GetCellReadinessSummaryResponseTypeDef",
     {
         "NextToken": str,
         "Readiness": ReadinessType,
         "ReadinessChecks": List[ReadinessCheckSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecoveryGroupReadinessSummaryResponseTypeDef = TypedDict(
     "GetRecoveryGroupReadinessSummaryResponseTypeDef",
     {
         "NextToken": str,
         "Readiness": ReadinessType,
         "ReadinessChecks": List[ReadinessCheckSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuleResultTypeDef = TypedDict(
     "RuleResultTypeDef",
     {
         "LastCheckedTimestamp": datetime,
@@ -918,42 +918,42 @@
 GetReadinessCheckStatusResponseTypeDef = TypedDict(
     "GetReadinessCheckStatusResponseTypeDef",
     {
         "Messages": List[MessageTypeDef],
         "NextToken": str,
         "Readiness": ReadinessType,
         "Resources": List[ResourceResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReadinessChecksResponseTypeDef = TypedDict(
     "ListReadinessChecksResponseTypeDef",
     {
         "NextToken": str,
         "ReadinessChecks": List[ReadinessCheckOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecoveryGroupsResponseTypeDef = TypedDict(
     "ListRecoveryGroupsResponseTypeDef",
     {
         "NextToken": str,
         "RecoveryGroups": List[RecoveryGroupOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRulesResponseTypeDef = TypedDict(
     "ListRulesResponseTypeDef",
     {
         "NextToken": str,
         "Rules": List[ListRulesOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetResourceTypeDef = TypedDict(
     "TargetResourceTypeDef",
     {
         "NLBResource": NLBResourceTypeDef,
@@ -964,15 +964,15 @@
 
 GetReadinessCheckResourceStatusResponseTypeDef = TypedDict(
     "GetReadinessCheckResourceStatusResponseTypeDef",
     {
         "NextToken": str,
         "Readiness": ReadinessType,
         "Rules": List[RuleResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DNSTargetResourceTypeDef = TypedDict(
     "DNSTargetResourceTypeDef",
     {
         "DomainName": str,
@@ -1020,27 +1020,27 @@
     "CreateResourceSetResponseTypeDef",
     {
         "ResourceSetArn": str,
         "ResourceSetName": str,
         "ResourceSetType": str,
         "Resources": List[ResourceTypeDef],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceSetResponseTypeDef = TypedDict(
     "GetResourceSetResponseTypeDef",
     {
         "ResourceSetArn": str,
         "ResourceSetName": str,
         "ResourceSetType": str,
         "Resources": List[ResourceTypeDef],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResourceSetOutputTypeDef = TypedDict(
     "_RequiredResourceSetOutputTypeDef",
     {
         "ResourceSetArn": str,
@@ -1075,19 +1075,19 @@
     "UpdateResourceSetResponseTypeDef",
     {
         "ResourceSetArn": str,
         "ResourceSetName": str,
         "ResourceSetType": str,
         "Resources": List[ResourceTypeDef],
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceSetsResponseTypeDef = TypedDict(
     "ListResourceSetsResponseTypeDef",
     {
         "NextToken": str,
         "ResourceSets": List[ResourceSetOutputTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/PKG-INFO` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-route53-recovery-readiness
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Route53RecoveryReadiness 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-route53-recovery-readiness"></a>
 
 # types-aiobotocore-route53-recovery-readiness
 
 [![PyPI - types-aiobotocore-route53-recovery-readiness](https://img.shields.io/pypi/v/types-aiobotocore-route53-recovery-readiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-readiness)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-route53-recovery-readiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-route53-recovery-readiness)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-route53-recovery-readiness?color=blue)](https://pypistats.org/packages/types-aiobotocore-route53-recovery-readiness)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Route53RecoveryReadiness 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness)
+[aiobotocore.Route53RecoveryReadiness 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/route53-recovery-readiness.html#Route53RecoveryReadiness)
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
 [types-aiobotocore-route53-recovery-readiness docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_route53_recovery_readiness/).
 
 See how it helps to find and fix potential bugs:
 
@@ -363,79 +363,79 @@
 structures and shapes assembled to typed dictionaries for additional type
 checking.
 
 ```python
 from types_aiobotocore_route53_recovery_readiness.type_defs import (
     CellOutputTypeDef,
     CreateCellRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateCellResponseTypeDef,
     CreateCrossAccountAuthorizationRequestRequestTypeDef,
+    CreateCrossAccountAuthorizationResponseTypeDef,
     CreateReadinessCheckRequestRequestTypeDef,
+    CreateReadinessCheckResponseTypeDef,
     CreateRecoveryGroupRequestRequestTypeDef,
+    CreateRecoveryGroupResponseTypeDef,
     DeleteCellRequestRequestTypeDef,
     DeleteCrossAccountAuthorizationRequestRequestTypeDef,
     DeleteReadinessCheckRequestRequestTypeDef,
     DeleteRecoveryGroupRequestRequestTypeDef,
     DeleteResourceSetRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetArchitectureRecommendationsRequestRequestTypeDef,
     RecommendationTypeDef,
-    PaginatorConfigTypeDef,
+    GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
     GetCellReadinessSummaryRequestRequestTypeDef,
     ReadinessCheckSummaryTypeDef,
     GetCellRequestRequestTypeDef,
+    GetCellResponseTypeDef,
     GetReadinessCheckRequestRequestTypeDef,
+    GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
     GetReadinessCheckResourceStatusRequestRequestTypeDef,
+    GetReadinessCheckResponseTypeDef,
+    GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
     GetReadinessCheckStatusRequestRequestTypeDef,
     MessageTypeDef,
     ResourceResultTypeDef,
+    GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
     GetRecoveryGroupReadinessSummaryRequestRequestTypeDef,
     GetRecoveryGroupRequestRequestTypeDef,
+    GetRecoveryGroupResponseTypeDef,
     GetResourceSetRequestRequestTypeDef,
+    ListCellsRequestListCellsPaginateTypeDef,
     ListCellsRequestRequestTypeDef,
+    ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef,
     ListCrossAccountAuthorizationsRequestRequestTypeDef,
+    ListCrossAccountAuthorizationsResponseTypeDef,
+    ListReadinessChecksRequestListReadinessChecksPaginateTypeDef,
     ListReadinessChecksRequestRequestTypeDef,
     ReadinessCheckOutputTypeDef,
+    ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef,
     ListRecoveryGroupsRequestRequestTypeDef,
     RecoveryGroupOutputTypeDef,
+    ListResourceSetsRequestListResourceSetsPaginateTypeDef,
     ListResourceSetsRequestRequestTypeDef,
     ListRulesOutputTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     ListTagsForResourcesRequestRequestTypeDef,
+    ListTagsForResourcesResponseTypeDef,
     NLBResourceTypeDef,
+    PaginatorConfigTypeDef,
     R53ResourceRecordTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCellRequestRequestTypeDef,
-    UpdateReadinessCheckRequestRequestTypeDef,
-    UpdateRecoveryGroupRequestRequestTypeDef,
-    CreateCellResponseTypeDef,
-    CreateCrossAccountAuthorizationResponseTypeDef,
-    CreateReadinessCheckResponseTypeDef,
-    CreateRecoveryGroupResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCellResponseTypeDef,
-    GetReadinessCheckResponseTypeDef,
-    GetRecoveryGroupResponseTypeDef,
-    ListCellsResponseTypeDef,
-    ListCrossAccountAuthorizationsResponseTypeDef,
-    ListTagsForResourcesResponseTypeDef,
     UpdateCellResponseTypeDef,
+    UpdateReadinessCheckRequestRequestTypeDef,
     UpdateReadinessCheckResponseTypeDef,
+    UpdateRecoveryGroupRequestRequestTypeDef,
     UpdateRecoveryGroupResponseTypeDef,
+    ListCellsResponseTypeDef,
     GetArchitectureRecommendationsResponseTypeDef,
-    GetCellReadinessSummaryRequestGetCellReadinessSummaryPaginateTypeDef,
-    GetReadinessCheckResourceStatusRequestGetReadinessCheckResourceStatusPaginateTypeDef,
-    GetReadinessCheckStatusRequestGetReadinessCheckStatusPaginateTypeDef,
-    GetRecoveryGroupReadinessSummaryRequestGetRecoveryGroupReadinessSummaryPaginateTypeDef,
-    ListCellsRequestListCellsPaginateTypeDef,
-    ListCrossAccountAuthorizationsRequestListCrossAccountAuthorizationsPaginateTypeDef,
-    ListReadinessChecksRequestListReadinessChecksPaginateTypeDef,
-    ListRecoveryGroupsRequestListRecoveryGroupsPaginateTypeDef,
-    ListResourceSetsRequestListResourceSetsPaginateTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
     GetCellReadinessSummaryResponseTypeDef,
     GetRecoveryGroupReadinessSummaryResponseTypeDef,
     RuleResultTypeDef,
     GetReadinessCheckStatusResponseTypeDef,
     ListReadinessChecksResponseTypeDef,
     ListRecoveryGroupsResponseTypeDef,
     ListRulesResponseTypeDef,
@@ -460,43 +460,43 @@
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

### Comparing `types-aiobotocore-route53-recovery-readiness-2.5.0.post1/types_aiobotocore_route53_recovery_readiness.egg-info/SOURCES.txt` & `types-aiobotocore-route53-recovery-readiness-2.5.1/types_aiobotocore_route53_recovery_readiness.egg-info/SOURCES.txt`

 * *Files identical despite different names*

