# Comparing `tmp/types-aiobotocore-shield-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-shield-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-shield-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:21 2023, max compression
+gzip compressed data, was "types-aiobotocore-shield-2.5.1.tar", last modified: Wed Jun 28 01:44:11 2023, max compression
```

## Comparing `types-aiobotocore-shield-2.5.0.post1.tar` & `types-aiobotocore-shield-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.015633 types-aiobotocore-shield-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16094 2023-03-11 12:27:21.015633 types-aiobotocore-shield-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14527 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:21.015633 types-aiobotocore-shield-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.003633 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/
--rw-r--r--   0 runner    (1001) docker     (123)      809 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      808 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27483 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27436 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8961 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8959 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3419 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3414 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    22175 2023-03-11 12:24:15.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    22156 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:14.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.015633 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16094 2023-03-11 12:27:20.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:27:20.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.674216 types-aiobotocore-shield-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16085 2023-06-28 01:44:11.674216 types-aiobotocore-shield-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14524 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:11.674216 types-aiobotocore-shield-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.674216 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/
+-rw-r--r--   0 runner    (1001) docker     (123)      809 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      808 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27481 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27434 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9170 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9168 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3303 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3299 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    22207 2023-06-28 01:41:03.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22188 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:02.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.674216 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16085 2023-06-28 01:44:11.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:44:11.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:11.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:11.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:11.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:44:11.000000 types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-shield-2.5.0.post1/LICENSE` & `types-aiobotocore-shield-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-shield-2.5.0.post1/PKG-INFO` & `types-aiobotocore-shield-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-shield
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Shield 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Shield 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-shield"></a>
 
 # types-aiobotocore-shield
 
 [![PyPI - types-aiobotocore-shield](https://img.shields.io/pypi/v/types-aiobotocore-shield.svg?color=blue)](https://pypi.org/project/types-aiobotocore-shield)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-shield.svg?color=blue)](https://pypi.org/project/types-aiobotocore-shield)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-shield?color=blue)](https://pypistats.org/packages/types-aiobotocore-shield)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Shield 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield)
+[aiobotocore.Shield 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield)
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
 [types-aiobotocore-shield docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/).
 
 See how it helps to find and fix potential bugs:
 
@@ -336,61 +336,61 @@
     EmergencyContactTypeDef,
     MitigationTypeDef,
     SummarizedCounterTypeDef,
     ContributorTypeDef,
     AttackVectorDescriptionTypeDef,
     AttackVolumeStatisticsTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateProtectionResponseTypeDef,
     DeleteProtectionGroupRequestRequestTypeDef,
     DeleteProtectionRequestRequestTypeDef,
     DescribeAttackRequestRequestTypeDef,
     TimeRangeTypeDef,
+    DescribeDRTAccessResponseTypeDef,
     DescribeProtectionGroupRequestRequestTypeDef,
     ProtectionGroupTypeDef,
     DescribeProtectionRequestRequestTypeDef,
     DisableApplicationLayerAutomaticResponseRequestRequestTypeDef,
     DisassociateDRTLogBucketRequestRequestTypeDef,
     DisassociateHealthCheckRequestRequestTypeDef,
+    GetSubscriptionStateResponseTypeDef,
     InclusionProtectionFiltersTypeDef,
     InclusionProtectionGroupFiltersTypeDef,
     LimitTypeDef,
-    PaginatorConfigTypeDef,
     ListResourcesInProtectionGroupRequestRequestTypeDef,
+    ListResourcesInProtectionGroupResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ProtectionGroupArbitraryPatternLimitsTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateProtectionGroupRequestRequestTypeDef,
     UpdateSubscriptionRequestRequestTypeDef,
     ApplicationLayerAutomaticResponseConfigurationTypeDef,
     EnableApplicationLayerAutomaticResponseRequestRequestTypeDef,
     UpdateApplicationLayerAutomaticResponseRequestRequestTypeDef,
     AssociateProactiveEngagementDetailsRequestRequestTypeDef,
+    DescribeEmergencyContactSettingsResponseTypeDef,
     UpdateEmergencyContactSettingsRequestRequestTypeDef,
     SummarizedAttackVectorTypeDef,
     AttackPropertyTypeDef,
     AttackSummaryTypeDef,
     AttackVolumeTypeDef,
     CreateProtectionGroupRequestRequestTypeDef,
     CreateProtectionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateProtectionResponseTypeDef,
-    DescribeDRTAccessResponseTypeDef,
-    DescribeEmergencyContactSettingsResponseTypeDef,
-    GetSubscriptionStateResponseTypeDef,
-    ListResourcesInProtectionGroupResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
+    ListAttacksRequestListAttacksPaginateTypeDef,
     ListAttacksRequestRequestTypeDef,
     DescribeProtectionGroupResponseTypeDef,
     ListProtectionGroupsResponseTypeDef,
+    ListProtectionsRequestListProtectionsPaginateTypeDef,
     ListProtectionsRequestRequestTypeDef,
     ListProtectionGroupsRequestRequestTypeDef,
     ProtectionLimitsTypeDef,
-    ListAttacksRequestListAttacksPaginateTypeDef,
-    ListProtectionsRequestListProtectionsPaginateTypeDef,
     ProtectionGroupPatternTypeLimitsTypeDef,
     ProtectionTypeDef,
     SubResourceSummaryTypeDef,
     ListAttacksResponseTypeDef,
     AttackStatisticsDataItemTypeDef,
     ProtectionGroupLimitsTypeDef,
     DescribeProtectionResponseTypeDef,
@@ -411,43 +411,43 @@
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

### Comparing `types-aiobotocore-shield-2.5.0.post1/README.md` & `types-aiobotocore-shield-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-shield"></a>
 
 # types-aiobotocore-shield
 
 [![PyPI - types-aiobotocore-shield](https://img.shields.io/pypi/v/types-aiobotocore-shield.svg?color=blue)](https://pypi.org/project/types-aiobotocore-shield)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-shield.svg?color=blue)](https://pypi.org/project/types-aiobotocore-shield)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-shield?color=blue)](https://pypistats.org/packages/types-aiobotocore-shield)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Shield 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield)
+[aiobotocore.Shield 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield)
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
 [types-aiobotocore-shield docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/).
 
 See how it helps to find and fix potential bugs:
 
@@ -303,61 +303,61 @@
     EmergencyContactTypeDef,
     MitigationTypeDef,
     SummarizedCounterTypeDef,
     ContributorTypeDef,
     AttackVectorDescriptionTypeDef,
     AttackVolumeStatisticsTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateProtectionResponseTypeDef,
     DeleteProtectionGroupRequestRequestTypeDef,
     DeleteProtectionRequestRequestTypeDef,
     DescribeAttackRequestRequestTypeDef,
     TimeRangeTypeDef,
+    DescribeDRTAccessResponseTypeDef,
     DescribeProtectionGroupRequestRequestTypeDef,
     ProtectionGroupTypeDef,
     DescribeProtectionRequestRequestTypeDef,
     DisableApplicationLayerAutomaticResponseRequestRequestTypeDef,
     DisassociateDRTLogBucketRequestRequestTypeDef,
     DisassociateHealthCheckRequestRequestTypeDef,
+    GetSubscriptionStateResponseTypeDef,
     InclusionProtectionFiltersTypeDef,
     InclusionProtectionGroupFiltersTypeDef,
     LimitTypeDef,
-    PaginatorConfigTypeDef,
     ListResourcesInProtectionGroupRequestRequestTypeDef,
+    ListResourcesInProtectionGroupResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ProtectionGroupArbitraryPatternLimitsTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateProtectionGroupRequestRequestTypeDef,
     UpdateSubscriptionRequestRequestTypeDef,
     ApplicationLayerAutomaticResponseConfigurationTypeDef,
     EnableApplicationLayerAutomaticResponseRequestRequestTypeDef,
     UpdateApplicationLayerAutomaticResponseRequestRequestTypeDef,
     AssociateProactiveEngagementDetailsRequestRequestTypeDef,
+    DescribeEmergencyContactSettingsResponseTypeDef,
     UpdateEmergencyContactSettingsRequestRequestTypeDef,
     SummarizedAttackVectorTypeDef,
     AttackPropertyTypeDef,
     AttackSummaryTypeDef,
     AttackVolumeTypeDef,
     CreateProtectionGroupRequestRequestTypeDef,
     CreateProtectionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateProtectionResponseTypeDef,
-    DescribeDRTAccessResponseTypeDef,
-    DescribeEmergencyContactSettingsResponseTypeDef,
-    GetSubscriptionStateResponseTypeDef,
-    ListResourcesInProtectionGroupResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
+    ListAttacksRequestListAttacksPaginateTypeDef,
     ListAttacksRequestRequestTypeDef,
     DescribeProtectionGroupResponseTypeDef,
     ListProtectionGroupsResponseTypeDef,
+    ListProtectionsRequestListProtectionsPaginateTypeDef,
     ListProtectionsRequestRequestTypeDef,
     ListProtectionGroupsRequestRequestTypeDef,
     ProtectionLimitsTypeDef,
-    ListAttacksRequestListAttacksPaginateTypeDef,
-    ListProtectionsRequestListProtectionsPaginateTypeDef,
     ProtectionGroupPatternTypeLimitsTypeDef,
     ProtectionTypeDef,
     SubResourceSummaryTypeDef,
     ListAttacksResponseTypeDef,
     AttackStatisticsDataItemTypeDef,
     ProtectionGroupLimitsTypeDef,
     DescribeProtectionResponseTypeDef,
@@ -378,43 +378,43 @@
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

### Comparing `types-aiobotocore-shield-2.5.0.post1/setup.py` & `types-aiobotocore-shield-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-shield.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-shield",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_shield"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Shield 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Shield 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/"
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

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/__init__.py` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/__init__.pyi` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/__main__.py` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Shield 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Shield 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield\nOther"
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

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/client.py` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -368,15 +368,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/client/#generate_presigned_url)
         """
 
     async def get_subscription_state(self) -> GetSubscriptionStateResponseTypeDef:
         """
-        Returns the `SubscriptionState` , either `Active` or `Inactive` .
+        Returns the `SubscriptionState`, either `Active` or `Inactive`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Client.get_subscription_state)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/client/#get_subscription_state)
         """
 
     async def list_attacks(
         self,
```

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/client.pyi` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -336,15 +336,15 @@
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/client/#generate_presigned_url)
         """
     async def get_subscription_state(self) -> GetSubscriptionStateResponseTypeDef:
         """
-        Returns the `SubscriptionState` , either `Active` or `Inactive` .
+        Returns the `SubscriptionState`, either `Active` or `Inactive`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Client.get_subscription_state)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/client/#get_subscription_state)
         """
     async def list_attacks(
         self,
         *,
```

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/literals.py` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ApplicationLayerAutomaticResponseStatusType",
     "AttackLayerType",
     "AttackPropertyIdentifierType",
     "AutoRenewType",
     "ListAttacksPaginatorName",
     "ListProtectionsPaginatorName",
@@ -35,15 +34,14 @@
     "UnitType",
     "ShieldServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
-
 ApplicationLayerAutomaticResponseStatusType = Literal["DISABLED", "ENABLED"]
 AttackLayerType = Literal["APPLICATION", "NETWORK"]
 AttackPropertyIdentifierType = Literal[
     "DESTINATION_URL",
     "REFERRER",
     "SOURCE_ASN",
     "SOURCE_COUNTRY",
@@ -128,14 +126,15 @@
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
@@ -214,14 +213,15 @@
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
@@ -232,14 +232,15 @@
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
@@ -275,14 +276,15 @@
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
@@ -301,16 +303,19 @@
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
@@ -394,15 +399,17 @@
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

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/literals.pyi` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/literals.py`

 * *Files 5% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ApplicationLayerAutomaticResponseStatusType",
     "AttackLayerType",
     "AttackPropertyIdentifierType",
     "AutoRenewType",
     "ListAttacksPaginatorName",
     "ListProtectionsPaginatorName",
@@ -34,14 +35,15 @@
     "UnitType",
     "ShieldServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
+
 ApplicationLayerAutomaticResponseStatusType = Literal["DISABLED", "ENABLED"]
 AttackLayerType = Literal["APPLICATION", "NETWORK"]
 AttackPropertyIdentifierType = Literal[
     "DESTINATION_URL",
     "REFERRER",
     "SOURCE_ASN",
     "SOURCE_COUNTRY",
@@ -126,14 +128,15 @@
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
@@ -212,14 +215,15 @@
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
@@ -230,14 +234,15 @@
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
@@ -273,14 +278,15 @@
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
@@ -299,16 +305,19 @@
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
@@ -392,15 +401,17 @@
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

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/paginator.py` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,34 +18,27 @@
     with session.create_client("shield") as client:
         client: ShieldClient
 
         list_attacks_paginator: ListAttacksPaginator = client.get_paginator("list_attacks")
         list_protections_paginator: ListProtectionsPaginator = client.get_paginator("list_protections")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     InclusionProtectionFiltersTypeDef,
     ListAttacksResponseTypeDef,
     ListProtectionsResponseTypeDef,
     PaginatorConfigTypeDef,
     TimeRangeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListAttacksPaginator", "ListProtectionsPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -63,15 +56,15 @@
 
     def paginate(
         self,
         *,
         ResourceArns: Sequence[str] = ...,
         StartTime: TimeRangeTypeDef = ...,
         EndTime: TimeRangeTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Paginator.ListAttacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/paginators/#listattackspaginator)
         """
 
 
@@ -81,13 +74,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/paginators/#listprotectionspaginator)
     """
 
     def paginate(
         self,
         *,
         InclusionFilters: InclusionProtectionFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Paginator.ListProtections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/paginators/#listprotectionspaginator)
         """
```

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/paginator.pyi` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -18,33 +18,27 @@
     with session.create_client("shield") as client:
         client: ShieldClient
 
         list_attacks_paginator: ListAttacksPaginator = client.get_paginator("list_attacks")
         list_protections_paginator: ListProtectionsPaginator = client.get_paginator("list_protections")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     InclusionProtectionFiltersTypeDef,
     ListAttacksResponseTypeDef,
     ListProtectionsResponseTypeDef,
     PaginatorConfigTypeDef,
     TimeRangeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListAttacksPaginator", "ListProtectionsPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -59,15 +53,15 @@
 
     def paginate(
         self,
         *,
         ResourceArns: Sequence[str] = ...,
         StartTime: TimeRangeTypeDef = ...,
         EndTime: TimeRangeTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Paginator.ListAttacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/paginators/#listattackspaginator)
         """
 
 class ListProtectionsPaginator(AioPaginator):
@@ -76,13 +70,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/paginators/#listprotectionspaginator)
     """
 
     def paginate(
         self,
         *,
         InclusionFilters: InclusionProtectionFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield.Paginator.ListProtections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/paginators/#listprotectionspaginator)
         """
```

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/type_defs.py` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -43,61 +43,61 @@
     "EmergencyContactTypeDef",
     "MitigationTypeDef",
     "SummarizedCounterTypeDef",
     "ContributorTypeDef",
     "AttackVectorDescriptionTypeDef",
     "AttackVolumeStatisticsTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateProtectionResponseTypeDef",
     "DeleteProtectionGroupRequestRequestTypeDef",
     "DeleteProtectionRequestRequestTypeDef",
     "DescribeAttackRequestRequestTypeDef",
     "TimeRangeTypeDef",
+    "DescribeDRTAccessResponseTypeDef",
     "DescribeProtectionGroupRequestRequestTypeDef",
     "ProtectionGroupTypeDef",
     "DescribeProtectionRequestRequestTypeDef",
     "DisableApplicationLayerAutomaticResponseRequestRequestTypeDef",
     "DisassociateDRTLogBucketRequestRequestTypeDef",
     "DisassociateHealthCheckRequestRequestTypeDef",
+    "GetSubscriptionStateResponseTypeDef",
     "InclusionProtectionFiltersTypeDef",
     "InclusionProtectionGroupFiltersTypeDef",
     "LimitTypeDef",
-    "PaginatorConfigTypeDef",
     "ListResourcesInProtectionGroupRequestRequestTypeDef",
+    "ListResourcesInProtectionGroupResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ProtectionGroupArbitraryPatternLimitsTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateProtectionGroupRequestRequestTypeDef",
     "UpdateSubscriptionRequestRequestTypeDef",
     "ApplicationLayerAutomaticResponseConfigurationTypeDef",
     "EnableApplicationLayerAutomaticResponseRequestRequestTypeDef",
     "UpdateApplicationLayerAutomaticResponseRequestRequestTypeDef",
     "AssociateProactiveEngagementDetailsRequestRequestTypeDef",
+    "DescribeEmergencyContactSettingsResponseTypeDef",
     "UpdateEmergencyContactSettingsRequestRequestTypeDef",
     "SummarizedAttackVectorTypeDef",
     "AttackPropertyTypeDef",
     "AttackSummaryTypeDef",
     "AttackVolumeTypeDef",
     "CreateProtectionGroupRequestRequestTypeDef",
     "CreateProtectionRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateProtectionResponseTypeDef",
-    "DescribeDRTAccessResponseTypeDef",
-    "DescribeEmergencyContactSettingsResponseTypeDef",
-    "GetSubscriptionStateResponseTypeDef",
-    "ListResourcesInProtectionGroupResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "ListAttacksRequestListAttacksPaginateTypeDef",
     "ListAttacksRequestRequestTypeDef",
     "DescribeProtectionGroupResponseTypeDef",
     "ListProtectionGroupsResponseTypeDef",
+    "ListProtectionsRequestListProtectionsPaginateTypeDef",
     "ListProtectionsRequestRequestTypeDef",
     "ListProtectionGroupsRequestRequestTypeDef",
     "ProtectionLimitsTypeDef",
-    "ListAttacksRequestListAttacksPaginateTypeDef",
-    "ListProtectionsRequestListProtectionsPaginateTypeDef",
     "ProtectionGroupPatternTypeLimitsTypeDef",
     "ProtectionTypeDef",
     "SubResourceSummaryTypeDef",
     "ListAttacksResponseTypeDef",
     "AttackStatisticsDataItemTypeDef",
     "ProtectionGroupLimitsTypeDef",
     "DescribeProtectionResponseTypeDef",
@@ -210,22 +210,19 @@
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateProtectionResponseTypeDef = TypedDict(
+    "CreateProtectionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ProtectionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteProtectionGroupRequestRequestTypeDef = TypedDict(
     "DeleteProtectionGroupRequestRequestTypeDef",
     {
         "ProtectionGroupId": str,
@@ -251,14 +248,23 @@
     {
         "FromInclusive": datetime,
         "ToExclusive": datetime,
     },
     total=False,
 )
 
+DescribeDRTAccessResponseTypeDef = TypedDict(
+    "DescribeDRTAccessResponseTypeDef",
+    {
+        "RoleArn": str,
+        "LogBucketList": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeProtectionGroupRequestRequestTypeDef = TypedDict(
     "DescribeProtectionGroupRequestRequestTypeDef",
     {
         "ProtectionGroupId": str,
     },
 )
 
@@ -312,14 +318,22 @@
     "DisassociateHealthCheckRequestRequestTypeDef",
     {
         "ProtectionId": str,
         "HealthCheckArn": str,
     },
 )
 
+GetSubscriptionStateResponseTypeDef = TypedDict(
+    "GetSubscriptionStateResponseTypeDef",
+    {
+        "SubscriptionState": SubscriptionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InclusionProtectionFiltersTypeDef = TypedDict(
     "InclusionProtectionFiltersTypeDef",
     {
         "ResourceArns": Sequence[str],
         "ProtectionNames": Sequence[str],
         "ResourceTypes": Sequence[ProtectedResourceTypeType],
     },
@@ -342,24 +356,14 @@
     {
         "Type": str,
         "Max": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 _RequiredListResourcesInProtectionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesInProtectionGroupRequestRequestTypeDef",
     {
         "ProtectionGroupId": str,
     },
 )
 _OptionalListResourcesInProtectionGroupRequestRequestTypeDef = TypedDict(
@@ -375,28 +379,58 @@
 class ListResourcesInProtectionGroupRequestRequestTypeDef(
     _RequiredListResourcesInProtectionGroupRequestRequestTypeDef,
     _OptionalListResourcesInProtectionGroupRequestRequestTypeDef,
 ):
     pass
 
 
+ListResourcesInProtectionGroupResponseTypeDef = TypedDict(
+    "ListResourcesInProtectionGroupResponseTypeDef",
+    {
+        "ResourceArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 ProtectionGroupArbitraryPatternLimitsTypeDef = TypedDict(
     "ProtectionGroupArbitraryPatternLimitsTypeDef",
     {
         "MaxMembers": int,
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
@@ -461,14 +495,22 @@
 AssociateProactiveEngagementDetailsRequestRequestTypeDef = TypedDict(
     "AssociateProactiveEngagementDetailsRequestRequestTypeDef",
     {
         "EmergencyContactList": Sequence[EmergencyContactTypeDef],
     },
 )
 
+DescribeEmergencyContactSettingsResponseTypeDef = TypedDict(
+    "DescribeEmergencyContactSettingsResponseTypeDef",
+    {
+        "EmergencyContactList": List[EmergencyContactTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateEmergencyContactSettingsRequestRequestTypeDef = TypedDict(
     "UpdateEmergencyContactSettingsRequestRequestTypeDef",
     {
         "EmergencyContactList": Sequence[EmergencyContactTypeDef],
     },
     total=False,
 )
@@ -572,70 +614,39 @@
 
 class CreateProtectionRequestRequestTypeDef(
     _RequiredCreateProtectionRequestRequestTypeDef, _OptionalCreateProtectionRequestRequestTypeDef
 ):
     pass
 
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateProtectionResponseTypeDef = TypedDict(
-    "CreateProtectionResponseTypeDef",
-    {
-        "ProtectionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDRTAccessResponseTypeDef = TypedDict(
-    "DescribeDRTAccessResponseTypeDef",
-    {
-        "RoleArn": str,
-        "LogBucketList": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEmergencyContactSettingsResponseTypeDef = TypedDict(
-    "DescribeEmergencyContactSettingsResponseTypeDef",
-    {
-        "EmergencyContactList": List[EmergencyContactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSubscriptionStateResponseTypeDef = TypedDict(
-    "GetSubscriptionStateResponseTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "SubscriptionState": SubscriptionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListResourcesInProtectionGroupResponseTypeDef = TypedDict(
-    "ListResourcesInProtectionGroupResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ResourceArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+ListAttacksRequestListAttacksPaginateTypeDef = TypedDict(
+    "ListAttacksRequestListAttacksPaginateTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArns": Sequence[str],
+        "StartTime": TimeRangeTypeDef,
+        "EndTime": TimeRangeTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListAttacksRequestRequestTypeDef = TypedDict(
     "ListAttacksRequestRequestTypeDef",
     {
         "ResourceArns": Sequence[str],
         "StartTime": TimeRangeTypeDef,
@@ -646,25 +657,34 @@
     total=False,
 )
 
 DescribeProtectionGroupResponseTypeDef = TypedDict(
     "DescribeProtectionGroupResponseTypeDef",
     {
         "ProtectionGroup": ProtectionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtectionGroupsResponseTypeDef = TypedDict(
     "ListProtectionGroupsResponseTypeDef",
     {
         "ProtectionGroups": List[ProtectionGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProtectionsRequestListProtectionsPaginateTypeDef = TypedDict(
+    "ListProtectionsRequestListProtectionsPaginateTypeDef",
+    {
+        "InclusionFilters": InclusionProtectionFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListProtectionsRequestRequestTypeDef = TypedDict(
     "ListProtectionsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
@@ -686,34 +706,14 @@
 ProtectionLimitsTypeDef = TypedDict(
     "ProtectionLimitsTypeDef",
     {
         "ProtectedResourceTypeLimits": List[LimitTypeDef],
     },
 )
 
-ListAttacksRequestListAttacksPaginateTypeDef = TypedDict(
-    "ListAttacksRequestListAttacksPaginateTypeDef",
-    {
-        "ResourceArns": Sequence[str],
-        "StartTime": TimeRangeTypeDef,
-        "EndTime": TimeRangeTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProtectionsRequestListProtectionsPaginateTypeDef = TypedDict(
-    "ListProtectionsRequestListProtectionsPaginateTypeDef",
-    {
-        "InclusionFilters": InclusionProtectionFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ProtectionGroupPatternTypeLimitsTypeDef = TypedDict(
     "ProtectionGroupPatternTypeLimitsTypeDef",
     {
         "ArbitraryPatternLimits": ProtectionGroupArbitraryPatternLimitsTypeDef,
     },
 )
 
@@ -744,15 +744,15 @@
 )
 
 ListAttacksResponseTypeDef = TypedDict(
     "ListAttacksResponseTypeDef",
     {
         "AttackSummaries": List[AttackSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAttackStatisticsDataItemTypeDef = TypedDict(
     "_RequiredAttackStatisticsDataItemTypeDef",
     {
         "AttackCount": int,
@@ -781,24 +781,24 @@
     },
 )
 
 DescribeProtectionResponseTypeDef = TypedDict(
     "DescribeProtectionResponseTypeDef",
     {
         "Protection": ProtectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtectionsResponseTypeDef = TypedDict(
     "ListProtectionsResponseTypeDef",
     {
         "Protections": List[ProtectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttackDetailTypeDef = TypedDict(
     "AttackDetailTypeDef",
     {
         "AttackId": str,
@@ -814,15 +814,15 @@
 )
 
 DescribeAttackStatisticsResponseTypeDef = TypedDict(
     "DescribeAttackStatisticsResponseTypeDef",
     {
         "TimeRange": TimeRangeTypeDef,
         "DataItems": List[AttackStatisticsDataItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubscriptionLimitsTypeDef = TypedDict(
     "SubscriptionLimitsTypeDef",
     {
         "ProtectionLimits": ProtectionLimitsTypeDef,
@@ -830,15 +830,15 @@
     },
 )
 
 DescribeAttackResponseTypeDef = TypedDict(
     "DescribeAttackResponseTypeDef",
     {
         "Attack": AttackDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSubscriptionTypeDef = TypedDict(
     "_RequiredSubscriptionTypeDef",
     {
         "SubscriptionLimits": SubscriptionLimitsTypeDef,
@@ -863,10 +863,10 @@
     pass
 
 
 DescribeSubscriptionResponseTypeDef = TypedDict(
     "DescribeSubscriptionResponseTypeDef",
     {
         "Subscription": SubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield/type_defs.pyi` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -42,61 +42,61 @@
     "EmergencyContactTypeDef",
     "MitigationTypeDef",
     "SummarizedCounterTypeDef",
     "ContributorTypeDef",
     "AttackVectorDescriptionTypeDef",
     "AttackVolumeStatisticsTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateProtectionResponseTypeDef",
     "DeleteProtectionGroupRequestRequestTypeDef",
     "DeleteProtectionRequestRequestTypeDef",
     "DescribeAttackRequestRequestTypeDef",
     "TimeRangeTypeDef",
+    "DescribeDRTAccessResponseTypeDef",
     "DescribeProtectionGroupRequestRequestTypeDef",
     "ProtectionGroupTypeDef",
     "DescribeProtectionRequestRequestTypeDef",
     "DisableApplicationLayerAutomaticResponseRequestRequestTypeDef",
     "DisassociateDRTLogBucketRequestRequestTypeDef",
     "DisassociateHealthCheckRequestRequestTypeDef",
+    "GetSubscriptionStateResponseTypeDef",
     "InclusionProtectionFiltersTypeDef",
     "InclusionProtectionGroupFiltersTypeDef",
     "LimitTypeDef",
-    "PaginatorConfigTypeDef",
     "ListResourcesInProtectionGroupRequestRequestTypeDef",
+    "ListResourcesInProtectionGroupResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "ProtectionGroupArbitraryPatternLimitsTypeDef",
+    "ResponseMetadataTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateProtectionGroupRequestRequestTypeDef",
     "UpdateSubscriptionRequestRequestTypeDef",
     "ApplicationLayerAutomaticResponseConfigurationTypeDef",
     "EnableApplicationLayerAutomaticResponseRequestRequestTypeDef",
     "UpdateApplicationLayerAutomaticResponseRequestRequestTypeDef",
     "AssociateProactiveEngagementDetailsRequestRequestTypeDef",
+    "DescribeEmergencyContactSettingsResponseTypeDef",
     "UpdateEmergencyContactSettingsRequestRequestTypeDef",
     "SummarizedAttackVectorTypeDef",
     "AttackPropertyTypeDef",
     "AttackSummaryTypeDef",
     "AttackVolumeTypeDef",
     "CreateProtectionGroupRequestRequestTypeDef",
     "CreateProtectionRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateProtectionResponseTypeDef",
-    "DescribeDRTAccessResponseTypeDef",
-    "DescribeEmergencyContactSettingsResponseTypeDef",
-    "GetSubscriptionStateResponseTypeDef",
-    "ListResourcesInProtectionGroupResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
+    "ListAttacksRequestListAttacksPaginateTypeDef",
     "ListAttacksRequestRequestTypeDef",
     "DescribeProtectionGroupResponseTypeDef",
     "ListProtectionGroupsResponseTypeDef",
+    "ListProtectionsRequestListProtectionsPaginateTypeDef",
     "ListProtectionsRequestRequestTypeDef",
     "ListProtectionGroupsRequestRequestTypeDef",
     "ProtectionLimitsTypeDef",
-    "ListAttacksRequestListAttacksPaginateTypeDef",
-    "ListProtectionsRequestListProtectionsPaginateTypeDef",
     "ProtectionGroupPatternTypeLimitsTypeDef",
     "ProtectionTypeDef",
     "SubResourceSummaryTypeDef",
     "ListAttacksResponseTypeDef",
     "AttackStatisticsDataItemTypeDef",
     "ProtectionGroupLimitsTypeDef",
     "DescribeProtectionResponseTypeDef",
@@ -207,22 +207,19 @@
     {
         "Key": str,
         "Value": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateProtectionResponseTypeDef = TypedDict(
+    "CreateProtectionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ProtectionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteProtectionGroupRequestRequestTypeDef = TypedDict(
     "DeleteProtectionGroupRequestRequestTypeDef",
     {
         "ProtectionGroupId": str,
@@ -248,14 +245,23 @@
     {
         "FromInclusive": datetime,
         "ToExclusive": datetime,
     },
     total=False,
 )
 
+DescribeDRTAccessResponseTypeDef = TypedDict(
+    "DescribeDRTAccessResponseTypeDef",
+    {
+        "RoleArn": str,
+        "LogBucketList": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeProtectionGroupRequestRequestTypeDef = TypedDict(
     "DescribeProtectionGroupRequestRequestTypeDef",
     {
         "ProtectionGroupId": str,
     },
 )
 
@@ -307,14 +313,22 @@
     "DisassociateHealthCheckRequestRequestTypeDef",
     {
         "ProtectionId": str,
         "HealthCheckArn": str,
     },
 )
 
+GetSubscriptionStateResponseTypeDef = TypedDict(
+    "GetSubscriptionStateResponseTypeDef",
+    {
+        "SubscriptionState": SubscriptionStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InclusionProtectionFiltersTypeDef = TypedDict(
     "InclusionProtectionFiltersTypeDef",
     {
         "ResourceArns": Sequence[str],
         "ProtectionNames": Sequence[str],
         "ResourceTypes": Sequence[ProtectedResourceTypeType],
     },
@@ -337,24 +351,14 @@
     {
         "Type": str,
         "Max": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 _RequiredListResourcesInProtectionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredListResourcesInProtectionGroupRequestRequestTypeDef",
     {
         "ProtectionGroupId": str,
     },
 )
 _OptionalListResourcesInProtectionGroupRequestRequestTypeDef = TypedDict(
@@ -368,28 +372,58 @@
 
 class ListResourcesInProtectionGroupRequestRequestTypeDef(
     _RequiredListResourcesInProtectionGroupRequestRequestTypeDef,
     _OptionalListResourcesInProtectionGroupRequestRequestTypeDef,
 ):
     pass
 
+ListResourcesInProtectionGroupResponseTypeDef = TypedDict(
+    "ListResourcesInProtectionGroupResponseTypeDef",
+    {
+        "ResourceArns": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 ProtectionGroupArbitraryPatternLimitsTypeDef = TypedDict(
     "ProtectionGroupArbitraryPatternLimitsTypeDef",
     {
         "MaxMembers": int,
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
@@ -452,14 +486,22 @@
 AssociateProactiveEngagementDetailsRequestRequestTypeDef = TypedDict(
     "AssociateProactiveEngagementDetailsRequestRequestTypeDef",
     {
         "EmergencyContactList": Sequence[EmergencyContactTypeDef],
     },
 )
 
+DescribeEmergencyContactSettingsResponseTypeDef = TypedDict(
+    "DescribeEmergencyContactSettingsResponseTypeDef",
+    {
+        "EmergencyContactList": List[EmergencyContactTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateEmergencyContactSettingsRequestRequestTypeDef = TypedDict(
     "UpdateEmergencyContactSettingsRequestRequestTypeDef",
     {
         "EmergencyContactList": Sequence[EmergencyContactTypeDef],
     },
     total=False,
 )
@@ -557,70 +599,39 @@
 )
 
 class CreateProtectionRequestRequestTypeDef(
     _RequiredCreateProtectionRequestRequestTypeDef, _OptionalCreateProtectionRequestRequestTypeDef
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "ResourceARN": str,
-        "Tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateProtectionResponseTypeDef = TypedDict(
-    "CreateProtectionResponseTypeDef",
-    {
-        "ProtectionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDRTAccessResponseTypeDef = TypedDict(
-    "DescribeDRTAccessResponseTypeDef",
-    {
-        "RoleArn": str,
-        "LogBucketList": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEmergencyContactSettingsResponseTypeDef = TypedDict(
-    "DescribeEmergencyContactSettingsResponseTypeDef",
-    {
-        "EmergencyContactList": List[EmergencyContactTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSubscriptionStateResponseTypeDef = TypedDict(
-    "GetSubscriptionStateResponseTypeDef",
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
     {
-        "SubscriptionState": SubscriptionStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListResourcesInProtectionGroupResponseTypeDef = TypedDict(
-    "ListResourcesInProtectionGroupResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "ResourceArns": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceARN": str,
+        "Tags": Sequence[TagTypeDef],
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+ListAttacksRequestListAttacksPaginateTypeDef = TypedDict(
+    "ListAttacksRequestListAttacksPaginateTypeDef",
     {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArns": Sequence[str],
+        "StartTime": TimeRangeTypeDef,
+        "EndTime": TimeRangeTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListAttacksRequestRequestTypeDef = TypedDict(
     "ListAttacksRequestRequestTypeDef",
     {
         "ResourceArns": Sequence[str],
         "StartTime": TimeRangeTypeDef,
@@ -631,25 +642,34 @@
     total=False,
 )
 
 DescribeProtectionGroupResponseTypeDef = TypedDict(
     "DescribeProtectionGroupResponseTypeDef",
     {
         "ProtectionGroup": ProtectionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtectionGroupsResponseTypeDef = TypedDict(
     "ListProtectionGroupsResponseTypeDef",
     {
         "ProtectionGroups": List[ProtectionGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProtectionsRequestListProtectionsPaginateTypeDef = TypedDict(
+    "ListProtectionsRequestListProtectionsPaginateTypeDef",
+    {
+        "InclusionFilters": InclusionProtectionFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
 ListProtectionsRequestRequestTypeDef = TypedDict(
     "ListProtectionsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
@@ -671,34 +691,14 @@
 ProtectionLimitsTypeDef = TypedDict(
     "ProtectionLimitsTypeDef",
     {
         "ProtectedResourceTypeLimits": List[LimitTypeDef],
     },
 )
 
-ListAttacksRequestListAttacksPaginateTypeDef = TypedDict(
-    "ListAttacksRequestListAttacksPaginateTypeDef",
-    {
-        "ResourceArns": Sequence[str],
-        "StartTime": TimeRangeTypeDef,
-        "EndTime": TimeRangeTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProtectionsRequestListProtectionsPaginateTypeDef = TypedDict(
-    "ListProtectionsRequestListProtectionsPaginateTypeDef",
-    {
-        "InclusionFilters": InclusionProtectionFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ProtectionGroupPatternTypeLimitsTypeDef = TypedDict(
     "ProtectionGroupPatternTypeLimitsTypeDef",
     {
         "ArbitraryPatternLimits": ProtectionGroupArbitraryPatternLimitsTypeDef,
     },
 )
 
@@ -729,15 +729,15 @@
 )
 
 ListAttacksResponseTypeDef = TypedDict(
     "ListAttacksResponseTypeDef",
     {
         "AttackSummaries": List[AttackSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAttackStatisticsDataItemTypeDef = TypedDict(
     "_RequiredAttackStatisticsDataItemTypeDef",
     {
         "AttackCount": int,
@@ -764,24 +764,24 @@
     },
 )
 
 DescribeProtectionResponseTypeDef = TypedDict(
     "DescribeProtectionResponseTypeDef",
     {
         "Protection": ProtectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtectionsResponseTypeDef = TypedDict(
     "ListProtectionsResponseTypeDef",
     {
         "Protections": List[ProtectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttackDetailTypeDef = TypedDict(
     "AttackDetailTypeDef",
     {
         "AttackId": str,
@@ -797,15 +797,15 @@
 )
 
 DescribeAttackStatisticsResponseTypeDef = TypedDict(
     "DescribeAttackStatisticsResponseTypeDef",
     {
         "TimeRange": TimeRangeTypeDef,
         "DataItems": List[AttackStatisticsDataItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SubscriptionLimitsTypeDef = TypedDict(
     "SubscriptionLimitsTypeDef",
     {
         "ProtectionLimits": ProtectionLimitsTypeDef,
@@ -813,15 +813,15 @@
     },
 )
 
 DescribeAttackResponseTypeDef = TypedDict(
     "DescribeAttackResponseTypeDef",
     {
         "Attack": AttackDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSubscriptionTypeDef = TypedDict(
     "_RequiredSubscriptionTypeDef",
     {
         "SubscriptionLimits": SubscriptionLimitsTypeDef,
@@ -844,10 +844,10 @@
 class SubscriptionTypeDef(_RequiredSubscriptionTypeDef, _OptionalSubscriptionTypeDef):
     pass
 
 DescribeSubscriptionResponseTypeDef = TypedDict(
     "DescribeSubscriptionResponseTypeDef",
     {
         "Subscription": SubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/PKG-INFO` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-shield
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Shield 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Shield 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-shield"></a>
 
 # types-aiobotocore-shield
 
 [![PyPI - types-aiobotocore-shield](https://img.shields.io/pypi/v/types-aiobotocore-shield.svg?color=blue)](https://pypi.org/project/types-aiobotocore-shield)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-shield.svg?color=blue)](https://pypi.org/project/types-aiobotocore-shield)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-shield?color=blue)](https://pypistats.org/packages/types-aiobotocore-shield)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Shield 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield)
+[aiobotocore.Shield 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/shield.html#Shield)
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
 [types-aiobotocore-shield docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_shield/).
 
 See how it helps to find and fix potential bugs:
 
@@ -336,61 +336,61 @@
     EmergencyContactTypeDef,
     MitigationTypeDef,
     SummarizedCounterTypeDef,
     ContributorTypeDef,
     AttackVectorDescriptionTypeDef,
     AttackVolumeStatisticsTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateProtectionResponseTypeDef,
     DeleteProtectionGroupRequestRequestTypeDef,
     DeleteProtectionRequestRequestTypeDef,
     DescribeAttackRequestRequestTypeDef,
     TimeRangeTypeDef,
+    DescribeDRTAccessResponseTypeDef,
     DescribeProtectionGroupRequestRequestTypeDef,
     ProtectionGroupTypeDef,
     DescribeProtectionRequestRequestTypeDef,
     DisableApplicationLayerAutomaticResponseRequestRequestTypeDef,
     DisassociateDRTLogBucketRequestRequestTypeDef,
     DisassociateHealthCheckRequestRequestTypeDef,
+    GetSubscriptionStateResponseTypeDef,
     InclusionProtectionFiltersTypeDef,
     InclusionProtectionGroupFiltersTypeDef,
     LimitTypeDef,
-    PaginatorConfigTypeDef,
     ListResourcesInProtectionGroupRequestRequestTypeDef,
+    ListResourcesInProtectionGroupResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     ProtectionGroupArbitraryPatternLimitsTypeDef,
+    ResponseMetadataTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateProtectionGroupRequestRequestTypeDef,
     UpdateSubscriptionRequestRequestTypeDef,
     ApplicationLayerAutomaticResponseConfigurationTypeDef,
     EnableApplicationLayerAutomaticResponseRequestRequestTypeDef,
     UpdateApplicationLayerAutomaticResponseRequestRequestTypeDef,
     AssociateProactiveEngagementDetailsRequestRequestTypeDef,
+    DescribeEmergencyContactSettingsResponseTypeDef,
     UpdateEmergencyContactSettingsRequestRequestTypeDef,
     SummarizedAttackVectorTypeDef,
     AttackPropertyTypeDef,
     AttackSummaryTypeDef,
     AttackVolumeTypeDef,
     CreateProtectionGroupRequestRequestTypeDef,
     CreateProtectionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateProtectionResponseTypeDef,
-    DescribeDRTAccessResponseTypeDef,
-    DescribeEmergencyContactSettingsResponseTypeDef,
-    GetSubscriptionStateResponseTypeDef,
-    ListResourcesInProtectionGroupResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
+    ListAttacksRequestListAttacksPaginateTypeDef,
     ListAttacksRequestRequestTypeDef,
     DescribeProtectionGroupResponseTypeDef,
     ListProtectionGroupsResponseTypeDef,
+    ListProtectionsRequestListProtectionsPaginateTypeDef,
     ListProtectionsRequestRequestTypeDef,
     ListProtectionGroupsRequestRequestTypeDef,
     ProtectionLimitsTypeDef,
-    ListAttacksRequestListAttacksPaginateTypeDef,
-    ListProtectionsRequestListProtectionsPaginateTypeDef,
     ProtectionGroupPatternTypeLimitsTypeDef,
     ProtectionTypeDef,
     SubResourceSummaryTypeDef,
     ListAttacksResponseTypeDef,
     AttackStatisticsDataItemTypeDef,
     ProtectionGroupLimitsTypeDef,
     DescribeProtectionResponseTypeDef,
@@ -411,43 +411,43 @@
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

### Comparing `types-aiobotocore-shield-2.5.0.post1/types_aiobotocore_shield.egg-info/SOURCES.txt` & `types-aiobotocore-shield-2.5.1/types_aiobotocore_shield.egg-info/SOURCES.txt`

 * *Files identical despite different names*

