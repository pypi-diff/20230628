# Comparing `tmp/types-aiobotocore-ssm-incidents-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ssm-incidents-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ssm-incidents-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-ssm-incidents-2.5.1.tar", last modified: Wed Jun 28 01:44:13 2023, max compression
```

## Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1.tar` & `types-aiobotocore-ssm-incidents-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.415657 types-aiobotocore-ssm-incidents-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18803 2023-03-11 12:27:23.411656 types-aiobotocore-ssm-incidents-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17209 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:23.415657 types-aiobotocore-ssm-incidents-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2165 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.407657 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/
--rw-r--r--   0 runner    (1001) docker     (123)     2350 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2349 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27564 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27518 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9794 2023-03-11 12:24:41.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9792 2023-03-11 12:24:41.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8390 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8381 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    33911 2023-03-11 12:24:41.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    33847 2023-03-11 12:24:41.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2829 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2827 2023-03-11 12:24:40.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.411656 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18803 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:27:23.000000 types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.926220 types-aiobotocore-ssm-incidents-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18801 2023-06-28 01:44:13.922220 types-aiobotocore-ssm-incidents-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17213 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:13.926220 types-aiobotocore-ssm-incidents-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.918220 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/
+-rw-r--r--   0 runner    (1001) docker     (123)     2350 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2349 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      953 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27564 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27518 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10003 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10001 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8295 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8286 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    33955 2023-06-28 01:41:31.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33891 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:27.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2829 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2827 2023-06-28 01:41:30.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:13.922220 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18801 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:44:13.000000 types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/LICENSE` & `types-aiobotocore-ssm-incidents-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ssm-incidents-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm-incidents
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSMIncidents 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSMIncidents 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm-incidents"></a>
 
 # types-aiobotocore-ssm-incidents
 
 [![PyPI - types-aiobotocore-ssm-incidents](https://img.shields.io/pypi/v/types-aiobotocore-ssm-incidents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-incidents)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-incidents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-incidents)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-incidents?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-incidents)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSMIncidents 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
+[aiobotocore.SSMIncidents 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
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
 [types-aiobotocore-ssm-incidents docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/).
 
 See how it helps to find and fix potential bugs:
 
@@ -390,67 +390,67 @@
 ```python
 from types_aiobotocore_ssm_incidents.type_defs import (
     AddRegionActionTypeDef,
     AttributeValueListTypeDef,
     AutomationExecutionTypeDef,
     ChatChannelTypeDef,
     RegionMapInputValueTypeDef,
-    ResponseMetadataTypeDef,
+    CreateReplicationSetOutputTypeDef,
+    CreateResponsePlanOutputTypeDef,
     EventReferenceTypeDef,
+    CreateTimelineEventOutputTypeDef,
     DeleteIncidentRecordInputRequestTypeDef,
     DeleteRegionActionTypeDef,
     DeleteReplicationSetInputRequestTypeDef,
     DeleteResourcePolicyInputRequestTypeDef,
     DeleteResponsePlanInputRequestTypeDef,
     DeleteTimelineEventInputRequestTypeDef,
     DynamicSsmParameterValueTypeDef,
     GetIncidentRecordInputRequestTypeDef,
     GetReplicationSetInputRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesInputRequestTypeDef,
     ResourcePolicyTypeDef,
     GetResponsePlanInputRequestTypeDef,
     GetTimelineEventInputRequestTypeDef,
     IncidentRecordSourceTypeDef,
     NotificationTargetItemTypeDef,
     PagerDutyIncidentDetailTypeDef,
+    ListRelatedItemsInputListRelatedItemsPaginateTypeDef,
     ListRelatedItemsInputRequestTypeDef,
+    ListReplicationSetsInputListReplicationSetsPaginateTypeDef,
     ListReplicationSetsInputRequestTypeDef,
+    ListReplicationSetsOutputTypeDef,
+    ListResponsePlansInputListResponsePlansPaginateTypeDef,
     ListResponsePlansInputRequestTypeDef,
     ResponsePlanSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PagerDutyIncidentConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyInputRequestTypeDef,
+    PutResourcePolicyOutputTypeDef,
     RegionInfoTypeDef,
+    ResponseMetadataTypeDef,
     TriggerDetailsTypeDef,
+    StartIncidentOutputTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeletionProtectionInputRequestTypeDef,
     ConditionTypeDef,
     CreateReplicationSetInputRequestTypeDef,
-    CreateReplicationSetOutputTypeDef,
-    CreateResponsePlanOutputTypeDef,
-    CreateTimelineEventOutputTypeDef,
-    ListReplicationSetsOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutResourcePolicyOutputTypeDef,
-    StartIncidentOutputTypeDef,
     CreateTimelineEventInputRequestTypeDef,
     EventSummaryTypeDef,
     TimelineEventTypeDef,
     UpdateTimelineEventInputRequestTypeDef,
     UpdateReplicationSetActionTypeDef,
     SsmAutomationTypeDef,
     GetReplicationSetInputWaitForReplicationSetActiveWaitTypeDef,
     GetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef,
-    GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
-    ListRelatedItemsInputListRelatedItemsPaginateTypeDef,
-    ListReplicationSetsInputListReplicationSetsPaginateTypeDef,
-    ListResponsePlansInputListResponsePlansPaginateTypeDef,
     GetResourcePoliciesOutputTypeDef,
     IncidentRecordSummaryTypeDef,
     IncidentRecordTypeDef,
     IncidentTemplateTypeDef,
     UpdateIncidentRecordInputRequestTypeDef,
     ItemValueTypeDef,
     ListResponsePlansOutputTypeDef,
@@ -488,43 +488,43 @@
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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/README.md` & `types-aiobotocore-ssm-incidents-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ssm-incidents"></a>
 
 # types-aiobotocore-ssm-incidents
 
 [![PyPI - types-aiobotocore-ssm-incidents](https://img.shields.io/pypi/v/types-aiobotocore-ssm-incidents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-incidents)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-incidents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-incidents)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-incidents?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-incidents)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSMIncidents 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
+[aiobotocore.SSMIncidents 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
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
 [types-aiobotocore-ssm-incidents docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/).
 
 See how it helps to find and fix potential bugs:
 
@@ -357,67 +357,67 @@
 ```python
 from types_aiobotocore_ssm_incidents.type_defs import (
     AddRegionActionTypeDef,
     AttributeValueListTypeDef,
     AutomationExecutionTypeDef,
     ChatChannelTypeDef,
     RegionMapInputValueTypeDef,
-    ResponseMetadataTypeDef,
+    CreateReplicationSetOutputTypeDef,
+    CreateResponsePlanOutputTypeDef,
     EventReferenceTypeDef,
+    CreateTimelineEventOutputTypeDef,
     DeleteIncidentRecordInputRequestTypeDef,
     DeleteRegionActionTypeDef,
     DeleteReplicationSetInputRequestTypeDef,
     DeleteResourcePolicyInputRequestTypeDef,
     DeleteResponsePlanInputRequestTypeDef,
     DeleteTimelineEventInputRequestTypeDef,
     DynamicSsmParameterValueTypeDef,
     GetIncidentRecordInputRequestTypeDef,
     GetReplicationSetInputRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesInputRequestTypeDef,
     ResourcePolicyTypeDef,
     GetResponsePlanInputRequestTypeDef,
     GetTimelineEventInputRequestTypeDef,
     IncidentRecordSourceTypeDef,
     NotificationTargetItemTypeDef,
     PagerDutyIncidentDetailTypeDef,
+    ListRelatedItemsInputListRelatedItemsPaginateTypeDef,
     ListRelatedItemsInputRequestTypeDef,
+    ListReplicationSetsInputListReplicationSetsPaginateTypeDef,
     ListReplicationSetsInputRequestTypeDef,
+    ListReplicationSetsOutputTypeDef,
+    ListResponsePlansInputListResponsePlansPaginateTypeDef,
     ListResponsePlansInputRequestTypeDef,
     ResponsePlanSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PagerDutyIncidentConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyInputRequestTypeDef,
+    PutResourcePolicyOutputTypeDef,
     RegionInfoTypeDef,
+    ResponseMetadataTypeDef,
     TriggerDetailsTypeDef,
+    StartIncidentOutputTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeletionProtectionInputRequestTypeDef,
     ConditionTypeDef,
     CreateReplicationSetInputRequestTypeDef,
-    CreateReplicationSetOutputTypeDef,
-    CreateResponsePlanOutputTypeDef,
-    CreateTimelineEventOutputTypeDef,
-    ListReplicationSetsOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutResourcePolicyOutputTypeDef,
-    StartIncidentOutputTypeDef,
     CreateTimelineEventInputRequestTypeDef,
     EventSummaryTypeDef,
     TimelineEventTypeDef,
     UpdateTimelineEventInputRequestTypeDef,
     UpdateReplicationSetActionTypeDef,
     SsmAutomationTypeDef,
     GetReplicationSetInputWaitForReplicationSetActiveWaitTypeDef,
     GetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef,
-    GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
-    ListRelatedItemsInputListRelatedItemsPaginateTypeDef,
-    ListReplicationSetsInputListReplicationSetsPaginateTypeDef,
-    ListResponsePlansInputListResponsePlansPaginateTypeDef,
     GetResourcePoliciesOutputTypeDef,
     IncidentRecordSummaryTypeDef,
     IncidentRecordTypeDef,
     IncidentTemplateTypeDef,
     UpdateIncidentRecordInputRequestTypeDef,
     ItemValueTypeDef,
     ListResponsePlansOutputTypeDef,
@@ -455,43 +455,43 @@
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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/setup.py` & `types-aiobotocore-ssm-incidents-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ssm-incidents.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ssm-incidents",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ssm_incidents"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SSMIncidents 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SSMIncidents 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/"
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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/__init__.py` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/__init__.pyi` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/__main__.py` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SSMIncidents 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SSMIncidents 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents\nOther"
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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/client.py` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/client.pyi` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/literals.py` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -130,14 +130,15 @@
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
@@ -216,14 +217,15 @@
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
@@ -234,14 +236,15 @@
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
@@ -277,14 +280,15 @@
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
@@ -303,16 +307,19 @@
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
@@ -396,15 +403,17 @@
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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/literals.pyi` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -128,14 +128,15 @@
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
@@ -214,14 +215,15 @@
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
@@ -232,14 +234,15 @@
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
@@ -275,14 +278,15 @@
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
@@ -301,16 +305,19 @@
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
@@ -394,15 +401,17 @@
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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/paginator.py` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -27,15 +27,15 @@
         list_related_items_paginator: ListRelatedItemsPaginator = client.get_paginator("list_related_items")
         list_replication_sets_paginator: ListReplicationSetsPaginator = client.get_paginator("list_replication_sets")
         list_response_plans_paginator: ListResponsePlansPaginator = client.get_paginator("list_response_plans")
         list_timeline_events_paginator: ListTimelineEventsPaginator = client.get_paginator("list_timeline_events")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SortOrderType
 from .type_defs import (
     FilterTypeDef,
@@ -44,18 +44,14 @@
     ListRelatedItemsOutputTypeDef,
     ListReplicationSetsOutputTypeDef,
     ListResponsePlansOutputTypeDef,
     ListTimelineEventsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
@@ -81,15 +77,15 @@
 class GetResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.GetResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#getresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#getresourcepoliciespaginator)
         """
 
 
@@ -99,60 +95,60 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listincidentrecordspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIncidentRecordsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListIncidentRecords.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listincidentrecordspaginator)
         """
 
 
 class ListRelatedItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListRelatedItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listrelateditemspaginator)
     """
 
     def paginate(
-        self, *, incidentRecordArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, incidentRecordArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRelatedItemsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListRelatedItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listrelateditemspaginator)
         """
 
 
 class ListReplicationSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListReplicationSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listreplicationsetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReplicationSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListReplicationSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listreplicationsetspaginator)
         """
 
 
 class ListResponsePlansPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListResponsePlans)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listresponseplanspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResponsePlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListResponsePlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listresponseplanspaginator)
         """
 
 
@@ -165,13 +161,13 @@
     def paginate(
         self,
         *,
         incidentRecordArn: str,
         filters: Sequence[FilterTypeDef] = ...,
         sortBy: Literal["EVENT_TIME"] = ...,
         sortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTimelineEventsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListTimelineEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listtimelineeventspaginator)
         """
```

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/paginator.pyi` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -27,15 +27,15 @@
         list_related_items_paginator: ListRelatedItemsPaginator = client.get_paginator("list_related_items")
         list_replication_sets_paginator: ListReplicationSetsPaginator = client.get_paginator("list_replication_sets")
         list_response_plans_paginator: ListResponsePlansPaginator = client.get_paginator("list_response_plans")
         list_timeline_events_paginator: ListTimelineEventsPaginator = client.get_paginator("list_timeline_events")
     ```
 """
 import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SortOrderType
 from .type_defs import (
     FilterTypeDef,
@@ -44,18 +44,14 @@
     ListRelatedItemsOutputTypeDef,
     ListReplicationSetsOutputTypeDef,
     ListResponsePlansOutputTypeDef,
     ListTimelineEventsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "GetResourcePoliciesPaginator",
@@ -77,15 +73,15 @@
 class GetResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.GetResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#getresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#getresourcepoliciespaginator)
         """
 
 class ListIncidentRecordsPaginator(AioPaginator):
@@ -94,57 +90,57 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listincidentrecordspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIncidentRecordsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListIncidentRecords.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listincidentrecordspaginator)
         """
 
 class ListRelatedItemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListRelatedItems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listrelateditemspaginator)
     """
 
     def paginate(
-        self, *, incidentRecordArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, incidentRecordArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRelatedItemsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListRelatedItems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listrelateditemspaginator)
         """
 
 class ListReplicationSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListReplicationSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listreplicationsetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReplicationSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListReplicationSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listreplicationsetspaginator)
         """
 
 class ListResponsePlansPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListResponsePlans)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listresponseplanspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResponsePlansOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListResponsePlans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listresponseplanspaginator)
         """
 
 class ListTimelineEventsPaginator(AioPaginator):
@@ -156,13 +152,13 @@
     def paginate(
         self,
         *,
         incidentRecordArn: str,
         filters: Sequence[FilterTypeDef] = ...,
         sortBy: Literal["EVENT_TIME"] = ...,
         sortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTimelineEventsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents.Paginator.ListTimelineEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/paginators/#listtimelineeventspaginator)
         """
```

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/type_defs.py` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -37,67 +37,67 @@
 
 __all__ = (
     "AddRegionActionTypeDef",
     "AttributeValueListTypeDef",
     "AutomationExecutionTypeDef",
     "ChatChannelTypeDef",
     "RegionMapInputValueTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateReplicationSetOutputTypeDef",
+    "CreateResponsePlanOutputTypeDef",
     "EventReferenceTypeDef",
+    "CreateTimelineEventOutputTypeDef",
     "DeleteIncidentRecordInputRequestTypeDef",
     "DeleteRegionActionTypeDef",
     "DeleteReplicationSetInputRequestTypeDef",
     "DeleteResourcePolicyInputRequestTypeDef",
     "DeleteResponsePlanInputRequestTypeDef",
     "DeleteTimelineEventInputRequestTypeDef",
     "DynamicSsmParameterValueTypeDef",
     "GetIncidentRecordInputRequestTypeDef",
     "GetReplicationSetInputRequestTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesInputRequestTypeDef",
     "ResourcePolicyTypeDef",
     "GetResponsePlanInputRequestTypeDef",
     "GetTimelineEventInputRequestTypeDef",
     "IncidentRecordSourceTypeDef",
     "NotificationTargetItemTypeDef",
     "PagerDutyIncidentDetailTypeDef",
+    "ListRelatedItemsInputListRelatedItemsPaginateTypeDef",
     "ListRelatedItemsInputRequestTypeDef",
+    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
     "ListReplicationSetsInputRequestTypeDef",
+    "ListReplicationSetsOutputTypeDef",
+    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
     "ListResponsePlansInputRequestTypeDef",
     "ResponsePlanSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "PagerDutyIncidentConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePolicyInputRequestTypeDef",
+    "PutResourcePolicyOutputTypeDef",
     "RegionInfoTypeDef",
+    "ResponseMetadataTypeDef",
     "TriggerDetailsTypeDef",
+    "StartIncidentOutputTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeletionProtectionInputRequestTypeDef",
     "ConditionTypeDef",
     "CreateReplicationSetInputRequestTypeDef",
-    "CreateReplicationSetOutputTypeDef",
-    "CreateResponsePlanOutputTypeDef",
-    "CreateTimelineEventOutputTypeDef",
-    "ListReplicationSetsOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutResourcePolicyOutputTypeDef",
-    "StartIncidentOutputTypeDef",
     "CreateTimelineEventInputRequestTypeDef",
     "EventSummaryTypeDef",
     "TimelineEventTypeDef",
     "UpdateTimelineEventInputRequestTypeDef",
     "UpdateReplicationSetActionTypeDef",
     "SsmAutomationTypeDef",
     "GetReplicationSetInputWaitForReplicationSetActiveWaitTypeDef",
     "GetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef",
-    "GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
-    "ListRelatedItemsInputListRelatedItemsPaginateTypeDef",
-    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
-    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
     "GetResourcePoliciesOutputTypeDef",
     "IncidentRecordSummaryTypeDef",
     "IncidentRecordTypeDef",
     "IncidentTemplateTypeDef",
     "UpdateIncidentRecordInputRequestTypeDef",
     "ItemValueTypeDef",
     "ListResponsePlansOutputTypeDef",
@@ -176,34 +176,48 @@
     "RegionMapInputValueTypeDef",
     {
         "sseKmsKeyId": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateReplicationSetOutputTypeDef = TypedDict(
+    "CreateReplicationSetOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateResponsePlanOutputTypeDef = TypedDict(
+    "CreateResponsePlanOutputTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventReferenceTypeDef = TypedDict(
     "EventReferenceTypeDef",
     {
         "relatedItemId": str,
         "resource": str,
     },
     total=False,
 )
 
+CreateTimelineEventOutputTypeDef = TypedDict(
+    "CreateTimelineEventOutputTypeDef",
+    {
+        "eventId": str,
+        "incidentRecordArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteIncidentRecordInputRequestTypeDef = TypedDict(
     "DeleteIncidentRecordInputRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -271,24 +285,36 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "resourceArn": str,
+    },
+)
+_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef(
+    _RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
+    _OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetResourcePoliciesInputRequestTypeDef = TypedDict(
     "_RequiredGetResourcePoliciesInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalGetResourcePoliciesInputRequestTypeDef = TypedDict(
@@ -380,14 +406,36 @@
 
 class PagerDutyIncidentDetailTypeDef(
     _RequiredPagerDutyIncidentDetailTypeDef, _OptionalPagerDutyIncidentDetailTypeDef
 ):
     pass
 
 
+_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
+    "_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef",
+    {
+        "incidentRecordArn": str,
+    },
+)
+_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
+    "_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRelatedItemsInputListRelatedItemsPaginateTypeDef(
+    _RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef,
+    _OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRelatedItemsInputRequestTypeDef = TypedDict(
     "_RequiredListRelatedItemsInputRequestTypeDef",
     {
         "incidentRecordArn": str,
     },
 )
 _OptionalListRelatedItemsInputRequestTypeDef = TypedDict(
@@ -402,23 +450,48 @@
 
 class ListRelatedItemsInputRequestTypeDef(
     _RequiredListRelatedItemsInputRequestTypeDef, _OptionalListRelatedItemsInputRequestTypeDef
 ):
     pass
 
 
+ListReplicationSetsInputListReplicationSetsPaginateTypeDef = TypedDict(
+    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReplicationSetsInputRequestTypeDef = TypedDict(
     "ListReplicationSetsInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListReplicationSetsOutputTypeDef = TypedDict(
+    "ListReplicationSetsOutputTypeDef",
+    {
+        "nextToken": str,
+        "replicationSetArns": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListResponsePlansInputListResponsePlansPaginateTypeDef = TypedDict(
+    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResponsePlansInputRequestTypeDef = TypedDict(
     "ListResponsePlansInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -449,29 +522,55 @@
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
 PagerDutyIncidentConfigurationTypeDef = TypedDict(
     "PagerDutyIncidentConfigurationTypeDef",
     {
         "serviceId": str,
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
 PutResourcePolicyInputRequestTypeDef = TypedDict(
     "PutResourcePolicyInputRequestTypeDef",
     {
         "policy": str,
         "resourceArn": str,
     },
 )
 
+PutResourcePolicyOutputTypeDef = TypedDict(
+    "PutResourcePolicyOutputTypeDef",
+    {
+        "policyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegionInfoTypeDef = TypedDict(
     "_RequiredRegionInfoTypeDef",
     {
         "status": RegionStatusType,
         "statusUpdateDateTime": datetime,
     },
 )
@@ -485,14 +584,25 @@
 )
 
 
 class RegionInfoTypeDef(_RequiredRegionInfoTypeDef, _OptionalRegionInfoTypeDef):
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
 _RequiredTriggerDetailsTypeDef = TypedDict(
     "_RequiredTriggerDetailsTypeDef",
     {
         "source": str,
         "timestamp": Union[datetime, str],
     },
 )
@@ -506,14 +616,22 @@
 )
 
 
 class TriggerDetailsTypeDef(_RequiredTriggerDetailsTypeDef, _OptionalTriggerDetailsTypeDef):
     pass
 
 
+StartIncidentOutputTypeDef = TypedDict(
+    "StartIncidentOutputTypeDef",
+    {
+        "incidentRecordArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -578,72 +696,14 @@
 class CreateReplicationSetInputRequestTypeDef(
     _RequiredCreateReplicationSetInputRequestTypeDef,
     _OptionalCreateReplicationSetInputRequestTypeDef,
 ):
     pass
 
 
-CreateReplicationSetOutputTypeDef = TypedDict(
-    "CreateReplicationSetOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResponsePlanOutputTypeDef = TypedDict(
-    "CreateResponsePlanOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTimelineEventOutputTypeDef = TypedDict(
-    "CreateTimelineEventOutputTypeDef",
-    {
-        "eventId": str,
-        "incidentRecordArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReplicationSetsOutputTypeDef = TypedDict(
-    "ListReplicationSetsOutputTypeDef",
-    {
-        "nextToken": str,
-        "replicationSetArns": List[str],
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
-PutResourcePolicyOutputTypeDef = TypedDict(
-    "PutResourcePolicyOutputTypeDef",
-    {
-        "policyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartIncidentOutputTypeDef = TypedDict(
-    "StartIncidentOutputTypeDef",
-    {
-        "incidentRecordArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateTimelineEventInputRequestTypeDef = TypedDict(
     "_RequiredCreateTimelineEventInputRequestTypeDef",
     {
         "eventData": str,
         "eventTime": Union[datetime, str],
         "eventType": str,
         "incidentRecordArn": str,
@@ -810,80 +870,20 @@
 class GetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef(
     _RequiredGetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef,
     _OptionalGetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef,
 ):
     pass
 
 
-_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef(
-    _RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
-    _OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
-    "_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef",
-    {
-        "incidentRecordArn": str,
-    },
-)
-_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
-    "_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRelatedItemsInputListRelatedItemsPaginateTypeDef(
-    _RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef,
-    _OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef,
-):
-    pass
-
-
-ListReplicationSetsInputListReplicationSetsPaginateTypeDef = TypedDict(
-    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResponsePlansInputListResponsePlansPaginateTypeDef = TypedDict(
-    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetResourcePoliciesOutputTypeDef = TypedDict(
     "GetResourcePoliciesOutputTypeDef",
     {
         "nextToken": str,
         "resourcePolicies": List[ResourcePolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIncidentRecordSummaryTypeDef = TypedDict(
     "_RequiredIncidentRecordSummaryTypeDef",
     {
         "arn": str,
@@ -1003,15 +1003,15 @@
 )
 
 ListResponsePlansOutputTypeDef = TypedDict(
     "ListResponsePlansOutputTypeDef",
     {
         "nextToken": str,
         "responsePlanSummaries": List[ResponsePlanSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PagerDutyConfigurationTypeDef = TypedDict(
     "PagerDutyConfigurationTypeDef",
     {
         "name": str,
@@ -1054,23 +1054,23 @@
 )
 
 ListTimelineEventsOutputTypeDef = TypedDict(
     "ListTimelineEventsOutputTypeDef",
     {
         "eventSummaries": List[EventSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTimelineEventOutputTypeDef = TypedDict(
     "GetTimelineEventOutputTypeDef",
     {
         "event": TimelineEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateReplicationSetInputRequestTypeDef = TypedDict(
     "_RequiredUpdateReplicationSetInputRequestTypeDef",
     {
         "actions": Sequence[UpdateReplicationSetActionTypeDef],
@@ -1102,23 +1102,23 @@
 )
 
 ListIncidentRecordsOutputTypeDef = TypedDict(
     "ListIncidentRecordsOutputTypeDef",
     {
         "incidentRecordSummaries": List[IncidentRecordSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIncidentRecordOutputTypeDef = TypedDict(
     "GetIncidentRecordOutputTypeDef",
     {
         "incidentRecord": IncidentRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ItemIdentifierTypeDef = TypedDict(
     "ItemIdentifierTypeDef",
     {
         "type": ItemTypeType,
@@ -1134,23 +1134,23 @@
     total=False,
 )
 
 GetReplicationSetOutputTypeDef = TypedDict(
     "GetReplicationSetOutputTypeDef",
     {
         "replicationSet": ReplicationSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIncidentRecordsInputListIncidentRecordsPaginateTypeDef = TypedDict(
     "ListIncidentRecordsInputListIncidentRecordsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListIncidentRecordsInputRequestTypeDef = TypedDict(
     "ListIncidentRecordsInputRequestTypeDef",
     {
@@ -1169,15 +1169,15 @@
 )
 _OptionalListTimelineEventsInputListTimelineEventsPaginateTypeDef = TypedDict(
     "_OptionalListTimelineEventsInputListTimelineEventsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
         "sortBy": Literal["EVENT_TIME"],
         "sortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListTimelineEventsInputListTimelineEventsPaginateTypeDef(
     _RequiredListTimelineEventsInputListTimelineEventsPaginateTypeDef,
@@ -1266,15 +1266,15 @@
         "arn": str,
         "chatChannel": ChatChannelTypeDef,
         "displayName": str,
         "engagements": List[str],
         "incidentTemplate": IncidentTemplateTypeDef,
         "integrations": List[IntegrationTypeDef],
         "name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateResponsePlanInputRequestTypeDef = TypedDict(
     "_RequiredUpdateResponsePlanInputRequestTypeDef",
     {
         "arn": str,
@@ -1307,15 +1307,15 @@
 
 
 ListRelatedItemsOutputTypeDef = TypedDict(
     "ListRelatedItemsOutputTypeDef",
     {
         "nextToken": str,
         "relatedItems": List[RelatedItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RelatedItemsUpdateTypeDef = TypedDict(
     "RelatedItemsUpdateTypeDef",
     {
         "itemToAdd": RelatedItemTypeDef,
```

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/type_defs.pyi` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -36,67 +36,67 @@
 
 __all__ = (
     "AddRegionActionTypeDef",
     "AttributeValueListTypeDef",
     "AutomationExecutionTypeDef",
     "ChatChannelTypeDef",
     "RegionMapInputValueTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateReplicationSetOutputTypeDef",
+    "CreateResponsePlanOutputTypeDef",
     "EventReferenceTypeDef",
+    "CreateTimelineEventOutputTypeDef",
     "DeleteIncidentRecordInputRequestTypeDef",
     "DeleteRegionActionTypeDef",
     "DeleteReplicationSetInputRequestTypeDef",
     "DeleteResourcePolicyInputRequestTypeDef",
     "DeleteResponsePlanInputRequestTypeDef",
     "DeleteTimelineEventInputRequestTypeDef",
     "DynamicSsmParameterValueTypeDef",
     "GetIncidentRecordInputRequestTypeDef",
     "GetReplicationSetInputRequestTypeDef",
     "WaiterConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesInputRequestTypeDef",
     "ResourcePolicyTypeDef",
     "GetResponsePlanInputRequestTypeDef",
     "GetTimelineEventInputRequestTypeDef",
     "IncidentRecordSourceTypeDef",
     "NotificationTargetItemTypeDef",
     "PagerDutyIncidentDetailTypeDef",
+    "ListRelatedItemsInputListRelatedItemsPaginateTypeDef",
     "ListRelatedItemsInputRequestTypeDef",
+    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
     "ListReplicationSetsInputRequestTypeDef",
+    "ListReplicationSetsOutputTypeDef",
+    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
     "ListResponsePlansInputRequestTypeDef",
     "ResponsePlanSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "PagerDutyIncidentConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
     "PutResourcePolicyInputRequestTypeDef",
+    "PutResourcePolicyOutputTypeDef",
     "RegionInfoTypeDef",
+    "ResponseMetadataTypeDef",
     "TriggerDetailsTypeDef",
+    "StartIncidentOutputTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeletionProtectionInputRequestTypeDef",
     "ConditionTypeDef",
     "CreateReplicationSetInputRequestTypeDef",
-    "CreateReplicationSetOutputTypeDef",
-    "CreateResponsePlanOutputTypeDef",
-    "CreateTimelineEventOutputTypeDef",
-    "ListReplicationSetsOutputTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutResourcePolicyOutputTypeDef",
-    "StartIncidentOutputTypeDef",
     "CreateTimelineEventInputRequestTypeDef",
     "EventSummaryTypeDef",
     "TimelineEventTypeDef",
     "UpdateTimelineEventInputRequestTypeDef",
     "UpdateReplicationSetActionTypeDef",
     "SsmAutomationTypeDef",
     "GetReplicationSetInputWaitForReplicationSetActiveWaitTypeDef",
     "GetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef",
-    "GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
-    "ListRelatedItemsInputListRelatedItemsPaginateTypeDef",
-    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
-    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
     "GetResourcePoliciesOutputTypeDef",
     "IncidentRecordSummaryTypeDef",
     "IncidentRecordTypeDef",
     "IncidentTemplateTypeDef",
     "UpdateIncidentRecordInputRequestTypeDef",
     "ItemValueTypeDef",
     "ListResponsePlansOutputTypeDef",
@@ -173,34 +173,48 @@
     "RegionMapInputValueTypeDef",
     {
         "sseKmsKeyId": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateReplicationSetOutputTypeDef = TypedDict(
+    "CreateReplicationSetOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateResponsePlanOutputTypeDef = TypedDict(
+    "CreateResponsePlanOutputTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventReferenceTypeDef = TypedDict(
     "EventReferenceTypeDef",
     {
         "relatedItemId": str,
         "resource": str,
     },
     total=False,
 )
 
+CreateTimelineEventOutputTypeDef = TypedDict(
+    "CreateTimelineEventOutputTypeDef",
+    {
+        "eventId": str,
+        "incidentRecordArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteIncidentRecordInputRequestTypeDef = TypedDict(
     "DeleteIncidentRecordInputRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -268,24 +282,34 @@
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "resourceArn": str,
+    },
+)
+_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef(
+    _RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
+    _OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetResourcePoliciesInputRequestTypeDef = TypedDict(
     "_RequiredGetResourcePoliciesInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalGetResourcePoliciesInputRequestTypeDef = TypedDict(
@@ -371,14 +395,34 @@
 )
 
 class PagerDutyIncidentDetailTypeDef(
     _RequiredPagerDutyIncidentDetailTypeDef, _OptionalPagerDutyIncidentDetailTypeDef
 ):
     pass
 
+_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
+    "_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef",
+    {
+        "incidentRecordArn": str,
+    },
+)
+_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
+    "_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRelatedItemsInputListRelatedItemsPaginateTypeDef(
+    _RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef,
+    _OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRelatedItemsInputRequestTypeDef = TypedDict(
     "_RequiredListRelatedItemsInputRequestTypeDef",
     {
         "incidentRecordArn": str,
     },
 )
 _OptionalListRelatedItemsInputRequestTypeDef = TypedDict(
@@ -391,23 +435,48 @@
 )
 
 class ListRelatedItemsInputRequestTypeDef(
     _RequiredListRelatedItemsInputRequestTypeDef, _OptionalListRelatedItemsInputRequestTypeDef
 ):
     pass
 
+ListReplicationSetsInputListReplicationSetsPaginateTypeDef = TypedDict(
+    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReplicationSetsInputRequestTypeDef = TypedDict(
     "ListReplicationSetsInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListReplicationSetsOutputTypeDef = TypedDict(
+    "ListReplicationSetsOutputTypeDef",
+    {
+        "nextToken": str,
+        "replicationSetArns": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListResponsePlansInputListResponsePlansPaginateTypeDef = TypedDict(
+    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListResponsePlansInputRequestTypeDef = TypedDict(
     "ListResponsePlansInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -436,29 +505,55 @@
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
 PagerDutyIncidentConfigurationTypeDef = TypedDict(
     "PagerDutyIncidentConfigurationTypeDef",
     {
         "serviceId": str,
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
 PutResourcePolicyInputRequestTypeDef = TypedDict(
     "PutResourcePolicyInputRequestTypeDef",
     {
         "policy": str,
         "resourceArn": str,
     },
 )
 
+PutResourcePolicyOutputTypeDef = TypedDict(
+    "PutResourcePolicyOutputTypeDef",
+    {
+        "policyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegionInfoTypeDef = TypedDict(
     "_RequiredRegionInfoTypeDef",
     {
         "status": RegionStatusType,
         "statusUpdateDateTime": datetime,
     },
 )
@@ -470,14 +565,25 @@
     },
     total=False,
 )
 
 class RegionInfoTypeDef(_RequiredRegionInfoTypeDef, _OptionalRegionInfoTypeDef):
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
 _RequiredTriggerDetailsTypeDef = TypedDict(
     "_RequiredTriggerDetailsTypeDef",
     {
         "source": str,
         "timestamp": Union[datetime, str],
     },
 )
@@ -489,14 +595,22 @@
     },
     total=False,
 )
 
 class TriggerDetailsTypeDef(_RequiredTriggerDetailsTypeDef, _OptionalTriggerDetailsTypeDef):
     pass
 
+StartIncidentOutputTypeDef = TypedDict(
+    "StartIncidentOutputTypeDef",
+    {
+        "incidentRecordArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -557,72 +671,14 @@
 
 class CreateReplicationSetInputRequestTypeDef(
     _RequiredCreateReplicationSetInputRequestTypeDef,
     _OptionalCreateReplicationSetInputRequestTypeDef,
 ):
     pass
 
-CreateReplicationSetOutputTypeDef = TypedDict(
-    "CreateReplicationSetOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResponsePlanOutputTypeDef = TypedDict(
-    "CreateResponsePlanOutputTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTimelineEventOutputTypeDef = TypedDict(
-    "CreateTimelineEventOutputTypeDef",
-    {
-        "eventId": str,
-        "incidentRecordArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListReplicationSetsOutputTypeDef = TypedDict(
-    "ListReplicationSetsOutputTypeDef",
-    {
-        "nextToken": str,
-        "replicationSetArns": List[str],
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
-PutResourcePolicyOutputTypeDef = TypedDict(
-    "PutResourcePolicyOutputTypeDef",
-    {
-        "policyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartIncidentOutputTypeDef = TypedDict(
-    "StartIncidentOutputTypeDef",
-    {
-        "incidentRecordArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateTimelineEventInputRequestTypeDef = TypedDict(
     "_RequiredCreateTimelineEventInputRequestTypeDef",
     {
         "eventData": str,
         "eventTime": Union[datetime, str],
         "eventType": str,
         "incidentRecordArn": str,
@@ -775,76 +831,20 @@
 
 class GetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef(
     _RequiredGetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef,
     _OptionalGetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef,
 ):
     pass
 
-_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "_OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef(
-    _RequiredGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
-    _OptionalGetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
-):
-    pass
-
-_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
-    "_RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef",
-    {
-        "incidentRecordArn": str,
-    },
-)
-_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef = TypedDict(
-    "_OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRelatedItemsInputListRelatedItemsPaginateTypeDef(
-    _RequiredListRelatedItemsInputListRelatedItemsPaginateTypeDef,
-    _OptionalListRelatedItemsInputListRelatedItemsPaginateTypeDef,
-):
-    pass
-
-ListReplicationSetsInputListReplicationSetsPaginateTypeDef = TypedDict(
-    "ListReplicationSetsInputListReplicationSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListResponsePlansInputListResponsePlansPaginateTypeDef = TypedDict(
-    "ListResponsePlansInputListResponsePlansPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetResourcePoliciesOutputTypeDef = TypedDict(
     "GetResourcePoliciesOutputTypeDef",
     {
         "nextToken": str,
         "resourcePolicies": List[ResourcePolicyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredIncidentRecordSummaryTypeDef = TypedDict(
     "_RequiredIncidentRecordSummaryTypeDef",
     {
         "arn": str,
@@ -956,15 +956,15 @@
 )
 
 ListResponsePlansOutputTypeDef = TypedDict(
     "ListResponsePlansOutputTypeDef",
     {
         "nextToken": str,
         "responsePlanSummaries": List[ResponsePlanSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PagerDutyConfigurationTypeDef = TypedDict(
     "PagerDutyConfigurationTypeDef",
     {
         "name": str,
@@ -1005,23 +1005,23 @@
 )
 
 ListTimelineEventsOutputTypeDef = TypedDict(
     "ListTimelineEventsOutputTypeDef",
     {
         "eventSummaries": List[EventSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTimelineEventOutputTypeDef = TypedDict(
     "GetTimelineEventOutputTypeDef",
     {
         "event": TimelineEventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateReplicationSetInputRequestTypeDef = TypedDict(
     "_RequiredUpdateReplicationSetInputRequestTypeDef",
     {
         "actions": Sequence[UpdateReplicationSetActionTypeDef],
@@ -1051,23 +1051,23 @@
 )
 
 ListIncidentRecordsOutputTypeDef = TypedDict(
     "ListIncidentRecordsOutputTypeDef",
     {
         "incidentRecordSummaries": List[IncidentRecordSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIncidentRecordOutputTypeDef = TypedDict(
     "GetIncidentRecordOutputTypeDef",
     {
         "incidentRecord": IncidentRecordTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ItemIdentifierTypeDef = TypedDict(
     "ItemIdentifierTypeDef",
     {
         "type": ItemTypeType,
@@ -1083,23 +1083,23 @@
     total=False,
 )
 
 GetReplicationSetOutputTypeDef = TypedDict(
     "GetReplicationSetOutputTypeDef",
     {
         "replicationSet": ReplicationSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIncidentRecordsInputListIncidentRecordsPaginateTypeDef = TypedDict(
     "ListIncidentRecordsInputListIncidentRecordsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListIncidentRecordsInputRequestTypeDef = TypedDict(
     "ListIncidentRecordsInputRequestTypeDef",
     {
@@ -1118,15 +1118,15 @@
 )
 _OptionalListTimelineEventsInputListTimelineEventsPaginateTypeDef = TypedDict(
     "_OptionalListTimelineEventsInputListTimelineEventsPaginateTypeDef",
     {
         "filters": Sequence[FilterTypeDef],
         "sortBy": Literal["EVENT_TIME"],
         "sortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListTimelineEventsInputListTimelineEventsPaginateTypeDef(
     _RequiredListTimelineEventsInputListTimelineEventsPaginateTypeDef,
     _OptionalListTimelineEventsInputListTimelineEventsPaginateTypeDef,
@@ -1207,15 +1207,15 @@
         "arn": str,
         "chatChannel": ChatChannelTypeDef,
         "displayName": str,
         "engagements": List[str],
         "incidentTemplate": IncidentTemplateTypeDef,
         "integrations": List[IntegrationTypeDef],
         "name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateResponsePlanInputRequestTypeDef = TypedDict(
     "_RequiredUpdateResponsePlanInputRequestTypeDef",
     {
         "arn": str,
@@ -1246,15 +1246,15 @@
     pass
 
 ListRelatedItemsOutputTypeDef = TypedDict(
     "ListRelatedItemsOutputTypeDef",
     {
         "nextToken": str,
         "relatedItems": List[RelatedItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RelatedItemsUpdateTypeDef = TypedDict(
     "RelatedItemsUpdateTypeDef",
     {
         "itemToAdd": RelatedItemTypeDef,
```

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/waiter.py` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents/waiter.pyi` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/PKG-INFO` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ssm-incidents
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SSMIncidents 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SSMIncidents 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ssm-incidents"></a>
 
 # types-aiobotocore-ssm-incidents
 
 [![PyPI - types-aiobotocore-ssm-incidents](https://img.shields.io/pypi/v/types-aiobotocore-ssm-incidents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-incidents)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ssm-incidents.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ssm-incidents)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ssm-incidents?color=blue)](https://pypistats.org/packages/types-aiobotocore-ssm-incidents)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SSMIncidents 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
+[aiobotocore.SSMIncidents 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ssm-incidents.html#SSMIncidents)
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
 [types-aiobotocore-ssm-incidents docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ssm_incidents/).
 
 See how it helps to find and fix potential bugs:
 
@@ -390,67 +390,67 @@
 ```python
 from types_aiobotocore_ssm_incidents.type_defs import (
     AddRegionActionTypeDef,
     AttributeValueListTypeDef,
     AutomationExecutionTypeDef,
     ChatChannelTypeDef,
     RegionMapInputValueTypeDef,
-    ResponseMetadataTypeDef,
+    CreateReplicationSetOutputTypeDef,
+    CreateResponsePlanOutputTypeDef,
     EventReferenceTypeDef,
+    CreateTimelineEventOutputTypeDef,
     DeleteIncidentRecordInputRequestTypeDef,
     DeleteRegionActionTypeDef,
     DeleteReplicationSetInputRequestTypeDef,
     DeleteResourcePolicyInputRequestTypeDef,
     DeleteResponsePlanInputRequestTypeDef,
     DeleteTimelineEventInputRequestTypeDef,
     DynamicSsmParameterValueTypeDef,
     GetIncidentRecordInputRequestTypeDef,
     GetReplicationSetInputRequestTypeDef,
     WaiterConfigTypeDef,
-    PaginatorConfigTypeDef,
+    GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesInputRequestTypeDef,
     ResourcePolicyTypeDef,
     GetResponsePlanInputRequestTypeDef,
     GetTimelineEventInputRequestTypeDef,
     IncidentRecordSourceTypeDef,
     NotificationTargetItemTypeDef,
     PagerDutyIncidentDetailTypeDef,
+    ListRelatedItemsInputListRelatedItemsPaginateTypeDef,
     ListRelatedItemsInputRequestTypeDef,
+    ListReplicationSetsInputListReplicationSetsPaginateTypeDef,
     ListReplicationSetsInputRequestTypeDef,
+    ListReplicationSetsOutputTypeDef,
+    ListResponsePlansInputListResponsePlansPaginateTypeDef,
     ListResponsePlansInputRequestTypeDef,
     ResponsePlanSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PagerDutyIncidentConfigurationTypeDef,
+    PaginatorConfigTypeDef,
     PutResourcePolicyInputRequestTypeDef,
+    PutResourcePolicyOutputTypeDef,
     RegionInfoTypeDef,
+    ResponseMetadataTypeDef,
     TriggerDetailsTypeDef,
+    StartIncidentOutputTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeletionProtectionInputRequestTypeDef,
     ConditionTypeDef,
     CreateReplicationSetInputRequestTypeDef,
-    CreateReplicationSetOutputTypeDef,
-    CreateResponsePlanOutputTypeDef,
-    CreateTimelineEventOutputTypeDef,
-    ListReplicationSetsOutputTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutResourcePolicyOutputTypeDef,
-    StartIncidentOutputTypeDef,
     CreateTimelineEventInputRequestTypeDef,
     EventSummaryTypeDef,
     TimelineEventTypeDef,
     UpdateTimelineEventInputRequestTypeDef,
     UpdateReplicationSetActionTypeDef,
     SsmAutomationTypeDef,
     GetReplicationSetInputWaitForReplicationSetActiveWaitTypeDef,
     GetReplicationSetInputWaitForReplicationSetDeletedWaitTypeDef,
-    GetResourcePoliciesInputGetResourcePoliciesPaginateTypeDef,
-    ListRelatedItemsInputListRelatedItemsPaginateTypeDef,
-    ListReplicationSetsInputListReplicationSetsPaginateTypeDef,
-    ListResponsePlansInputListResponsePlansPaginateTypeDef,
     GetResourcePoliciesOutputTypeDef,
     IncidentRecordSummaryTypeDef,
     IncidentRecordTypeDef,
     IncidentTemplateTypeDef,
     UpdateIncidentRecordInputRequestTypeDef,
     ItemValueTypeDef,
     ListResponsePlansOutputTypeDef,
@@ -488,43 +488,43 @@
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

### Comparing `types-aiobotocore-ssm-incidents-2.5.0.post1/types_aiobotocore_ssm_incidents.egg-info/SOURCES.txt` & `types-aiobotocore-ssm-incidents-2.5.1/types_aiobotocore_ssm_incidents.egg-info/SOURCES.txt`

 * *Files identical despite different names*

