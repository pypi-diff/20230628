# Comparing `tmp/types-aiobotocore-events-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-events-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-events-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:37 2023, max compression
+gzip compressed data, was "types-aiobotocore-events-2.5.1.tar", last modified: Wed Jun 28 01:43:29 2023, max compression
```

## Comparing `types-aiobotocore-events-2.5.0.post1.tar` & `types-aiobotocore-events-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.167201 types-aiobotocore-events-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20107 2023-03-11 12:26:37.163201 types-aiobotocore-events-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18535 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:37.167201 types-aiobotocore-events-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2122 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.163201 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/
--rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1107 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    40233 2023-03-11 12:14:27.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    40165 2023-03-11 12:14:27.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9997 2023-03-11 12:14:27.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9995 2023-03-11 12:14:27.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4493 2023-03-11 12:14:27.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4487 2023-03-11 12:14:27.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    58951 2023-03-11 12:14:28.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    58882 2023-03-11 12:14:28.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:26.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.163201 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20107 2023-03-11 12:26:36.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:26:37.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:36.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:36.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:36.000000 types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.354136 types-aiobotocore-events-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20098 2023-06-28 01:43:29.354136 types-aiobotocore-events-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18532 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:29.354136 types-aiobotocore-events-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2116 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.350136 types-aiobotocore-events-2.5.1/types_aiobotocore_events/
+-rw-r--r--   0 runner    (1001) docker     (123)     1108 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1107 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      926 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40233 2023-06-28 01:31:03.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40165 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10206 2023-06-28 01:31:03.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10204 2023-06-28 01:31:03.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4411 2023-06-28 01:31:03.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4406 2023-06-28 01:31:03.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    59070 2023-06-28 01:31:04.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59001 2023-06-28 01:31:03.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:02.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.354136 types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20098 2023-06-28 01:43:29.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:29.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:29.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:29.000000 types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-events-2.5.0.post1/LICENSE` & `types-aiobotocore-events-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-events-2.5.0.post1/PKG-INFO` & `types-aiobotocore-events-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-events
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EventBridge 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EventBridge 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-events"></a>
 
 # types-aiobotocore-events
 
 [![PyPI - types-aiobotocore-events](https://img.shields.io/pypi/v/types-aiobotocore-events.svg?color=blue)](https://pypi.org/project/types-aiobotocore-events)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-events.svg?color=blue)](https://pypi.org/project/types-aiobotocore-events)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-events?color=blue)](https://pypistats.org/packages/types-aiobotocore-events)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridge 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge)
+[aiobotocore.EventBridge 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge)
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
 [types-aiobotocore-events docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,56 +348,70 @@
     ActivateEventSourceRequestRequestTypeDef,
     ApiDestinationTypeDef,
     ArchiveTypeDef,
     AwsVpcConfigurationTypeDef,
     BatchArrayPropertiesTypeDef,
     BatchRetryStrategyTypeDef,
     CancelReplayRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelReplayResponseTypeDef,
     CapacityProviderStrategyItemTypeDef,
     ConditionTypeDef,
     ConnectionApiKeyAuthResponseParametersTypeDef,
     ConnectionBasicAuthResponseParametersTypeDef,
     ConnectionBodyParameterTypeDef,
     ConnectionHeaderParameterTypeDef,
     ConnectionQueryStringParameterTypeDef,
     ConnectionOAuthClientResponseParametersTypeDef,
     ConnectionTypeDef,
     CreateApiDestinationRequestRequestTypeDef,
+    CreateApiDestinationResponseTypeDef,
     CreateArchiveRequestRequestTypeDef,
+    CreateArchiveResponseTypeDef,
     CreateConnectionApiKeyAuthRequestParametersTypeDef,
     CreateConnectionBasicAuthRequestParametersTypeDef,
     CreateConnectionOAuthClientRequestParametersTypeDef,
+    CreateConnectionResponseTypeDef,
     EndpointEventBusTypeDef,
     ReplicationConfigTypeDef,
     TagTypeDef,
+    CreateEventBusResponseTypeDef,
     CreatePartnerEventSourceRequestRequestTypeDef,
+    CreatePartnerEventSourceResponseTypeDef,
     DeactivateEventSourceRequestRequestTypeDef,
     DeadLetterConfigTypeDef,
     DeauthorizeConnectionRequestRequestTypeDef,
+    DeauthorizeConnectionResponseTypeDef,
     DeleteApiDestinationRequestRequestTypeDef,
     DeleteArchiveRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
+    DeleteConnectionResponseTypeDef,
     DeleteEndpointRequestRequestTypeDef,
     DeleteEventBusRequestRequestTypeDef,
     DeletePartnerEventSourceRequestRequestTypeDef,
     DeleteRuleRequestRequestTypeDef,
     DescribeApiDestinationRequestRequestTypeDef,
+    DescribeApiDestinationResponseTypeDef,
     DescribeArchiveRequestRequestTypeDef,
+    DescribeArchiveResponseTypeDef,
     DescribeConnectionRequestRequestTypeDef,
     DescribeEndpointRequestRequestTypeDef,
     DescribeEventBusRequestRequestTypeDef,
+    DescribeEventBusResponseTypeDef,
     DescribeEventSourceRequestRequestTypeDef,
+    DescribeEventSourceResponseTypeDef,
     DescribePartnerEventSourceRequestRequestTypeDef,
+    DescribePartnerEventSourceResponseTypeDef,
     DescribeReplayRequestRequestTypeDef,
     ReplayDestinationTypeDef,
     DescribeRuleRequestRequestTypeDef,
+    DescribeRuleResponseTypeDef,
     DisableRuleRequestRequestTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableRuleRequestRequestTypeDef,
     EventBusTypeDef,
     EventSourceTypeDef,
     PrimaryTypeDef,
     SecondaryTypeDef,
     HttpParametersTypeDef,
     InputTransformerTypeDef,
@@ -410,66 +424,55 @@
     ListEventSourcesRequestRequestTypeDef,
     ListPartnerEventSourceAccountsRequestRequestTypeDef,
     PartnerEventSourceAccountTypeDef,
     ListPartnerEventSourcesRequestRequestTypeDef,
     PartnerEventSourceTypeDef,
     ListReplaysRequestRequestTypeDef,
     ReplayTypeDef,
-    PaginatorConfigTypeDef,
+    ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
     ListRuleNamesByTargetRequestRequestTypeDef,
+    ListRuleNamesByTargetResponseTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     RuleTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
     ListTargetsByRuleRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutEventsRequestEntryTypeDef,
     PutEventsResultEntryTypeDef,
     PutPartnerEventsRequestEntryTypeDef,
     PutPartnerEventsResultEntryTypeDef,
+    PutRuleResponseTypeDef,
     PutTargetsResultEntryTypeDef,
     RedshiftDataParametersTypeDef,
     RemovePermissionRequestRequestTypeDef,
     RemoveTargetsRequestRequestTypeDef,
     RemoveTargetsResultEntryTypeDef,
+    ResponseMetadataTypeDef,
     RetryPolicyTypeDef,
     RunCommandTargetTypeDef,
     SageMakerPipelineParameterTypeDef,
     SqsParametersTypeDef,
+    StartReplayResponseTypeDef,
     TestEventPatternRequestRequestTypeDef,
+    TestEventPatternResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiDestinationRequestRequestTypeDef,
+    UpdateApiDestinationResponseTypeDef,
     UpdateArchiveRequestRequestTypeDef,
+    UpdateArchiveResponseTypeDef,
     UpdateConnectionApiKeyAuthRequestParametersTypeDef,
     UpdateConnectionBasicAuthRequestParametersTypeDef,
     UpdateConnectionOAuthClientRequestParametersTypeDef,
-    NetworkConfigurationTypeDef,
-    BatchParametersTypeDef,
-    CancelReplayResponseTypeDef,
-    CreateApiDestinationResponseTypeDef,
-    CreateArchiveResponseTypeDef,
-    CreateConnectionResponseTypeDef,
-    CreateEventBusResponseTypeDef,
-    CreatePartnerEventSourceResponseTypeDef,
-    DeauthorizeConnectionResponseTypeDef,
-    DeleteConnectionResponseTypeDef,
-    DescribeApiDestinationResponseTypeDef,
-    DescribeArchiveResponseTypeDef,
-    DescribeEventBusResponseTypeDef,
-    DescribeEventSourceResponseTypeDef,
-    DescribePartnerEventSourceResponseTypeDef,
-    DescribeRuleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    UpdateConnectionResponseTypeDef,
     ListApiDestinationsResponseTypeDef,
     ListArchivesResponseTypeDef,
-    ListRuleNamesByTargetResponseTypeDef,
-    PutRuleResponseTypeDef,
-    StartReplayResponseTypeDef,
-    TestEventPatternResponseTypeDef,
-    UpdateApiDestinationResponseTypeDef,
-    UpdateArchiveResponseTypeDef,
-    UpdateConnectionResponseTypeDef,
+    NetworkConfigurationTypeDef,
+    BatchParametersTypeDef,
     PutPermissionRequestRequestTypeDef,
     ConnectionHttpParametersTypeDef,
     ListConnectionsResponseTypeDef,
     CreateEventBusRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutRuleRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
@@ -477,17 +480,14 @@
     StartReplayRequestRequestTypeDef,
     ListEventBusesResponseTypeDef,
     ListEventSourcesResponseTypeDef,
     FailoverConfigTypeDef,
     ListPartnerEventSourceAccountsResponseTypeDef,
     ListPartnerEventSourcesResponseTypeDef,
     ListReplaysResponseTypeDef,
-    ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
-    ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
     ListRulesResponseTypeDef,
     PutEventsRequestRequestTypeDef,
     PutEventsResponseTypeDef,
     PutPartnerEventsRequestRequestTypeDef,
     PutPartnerEventsResponseTypeDef,
     PutTargetsResponseTypeDef,
     RemoveTargetsResponseTypeDef,
@@ -524,43 +524,43 @@
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

### Comparing `types-aiobotocore-events-2.5.0.post1/README.md` & `types-aiobotocore-events-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-events"></a>
 
 # types-aiobotocore-events
 
 [![PyPI - types-aiobotocore-events](https://img.shields.io/pypi/v/types-aiobotocore-events.svg?color=blue)](https://pypi.org/project/types-aiobotocore-events)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-events.svg?color=blue)](https://pypi.org/project/types-aiobotocore-events)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-events?color=blue)](https://pypistats.org/packages/types-aiobotocore-events)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridge 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge)
+[aiobotocore.EventBridge 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge)
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
 [types-aiobotocore-events docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/).
 
 See how it helps to find and fix potential bugs:
 
@@ -315,56 +315,70 @@
     ActivateEventSourceRequestRequestTypeDef,
     ApiDestinationTypeDef,
     ArchiveTypeDef,
     AwsVpcConfigurationTypeDef,
     BatchArrayPropertiesTypeDef,
     BatchRetryStrategyTypeDef,
     CancelReplayRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelReplayResponseTypeDef,
     CapacityProviderStrategyItemTypeDef,
     ConditionTypeDef,
     ConnectionApiKeyAuthResponseParametersTypeDef,
     ConnectionBasicAuthResponseParametersTypeDef,
     ConnectionBodyParameterTypeDef,
     ConnectionHeaderParameterTypeDef,
     ConnectionQueryStringParameterTypeDef,
     ConnectionOAuthClientResponseParametersTypeDef,
     ConnectionTypeDef,
     CreateApiDestinationRequestRequestTypeDef,
+    CreateApiDestinationResponseTypeDef,
     CreateArchiveRequestRequestTypeDef,
+    CreateArchiveResponseTypeDef,
     CreateConnectionApiKeyAuthRequestParametersTypeDef,
     CreateConnectionBasicAuthRequestParametersTypeDef,
     CreateConnectionOAuthClientRequestParametersTypeDef,
+    CreateConnectionResponseTypeDef,
     EndpointEventBusTypeDef,
     ReplicationConfigTypeDef,
     TagTypeDef,
+    CreateEventBusResponseTypeDef,
     CreatePartnerEventSourceRequestRequestTypeDef,
+    CreatePartnerEventSourceResponseTypeDef,
     DeactivateEventSourceRequestRequestTypeDef,
     DeadLetterConfigTypeDef,
     DeauthorizeConnectionRequestRequestTypeDef,
+    DeauthorizeConnectionResponseTypeDef,
     DeleteApiDestinationRequestRequestTypeDef,
     DeleteArchiveRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
+    DeleteConnectionResponseTypeDef,
     DeleteEndpointRequestRequestTypeDef,
     DeleteEventBusRequestRequestTypeDef,
     DeletePartnerEventSourceRequestRequestTypeDef,
     DeleteRuleRequestRequestTypeDef,
     DescribeApiDestinationRequestRequestTypeDef,
+    DescribeApiDestinationResponseTypeDef,
     DescribeArchiveRequestRequestTypeDef,
+    DescribeArchiveResponseTypeDef,
     DescribeConnectionRequestRequestTypeDef,
     DescribeEndpointRequestRequestTypeDef,
     DescribeEventBusRequestRequestTypeDef,
+    DescribeEventBusResponseTypeDef,
     DescribeEventSourceRequestRequestTypeDef,
+    DescribeEventSourceResponseTypeDef,
     DescribePartnerEventSourceRequestRequestTypeDef,
+    DescribePartnerEventSourceResponseTypeDef,
     DescribeReplayRequestRequestTypeDef,
     ReplayDestinationTypeDef,
     DescribeRuleRequestRequestTypeDef,
+    DescribeRuleResponseTypeDef,
     DisableRuleRequestRequestTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableRuleRequestRequestTypeDef,
     EventBusTypeDef,
     EventSourceTypeDef,
     PrimaryTypeDef,
     SecondaryTypeDef,
     HttpParametersTypeDef,
     InputTransformerTypeDef,
@@ -377,66 +391,55 @@
     ListEventSourcesRequestRequestTypeDef,
     ListPartnerEventSourceAccountsRequestRequestTypeDef,
     PartnerEventSourceAccountTypeDef,
     ListPartnerEventSourcesRequestRequestTypeDef,
     PartnerEventSourceTypeDef,
     ListReplaysRequestRequestTypeDef,
     ReplayTypeDef,
-    PaginatorConfigTypeDef,
+    ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
     ListRuleNamesByTargetRequestRequestTypeDef,
+    ListRuleNamesByTargetResponseTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     RuleTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
     ListTargetsByRuleRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutEventsRequestEntryTypeDef,
     PutEventsResultEntryTypeDef,
     PutPartnerEventsRequestEntryTypeDef,
     PutPartnerEventsResultEntryTypeDef,
+    PutRuleResponseTypeDef,
     PutTargetsResultEntryTypeDef,
     RedshiftDataParametersTypeDef,
     RemovePermissionRequestRequestTypeDef,
     RemoveTargetsRequestRequestTypeDef,
     RemoveTargetsResultEntryTypeDef,
+    ResponseMetadataTypeDef,
     RetryPolicyTypeDef,
     RunCommandTargetTypeDef,
     SageMakerPipelineParameterTypeDef,
     SqsParametersTypeDef,
+    StartReplayResponseTypeDef,
     TestEventPatternRequestRequestTypeDef,
+    TestEventPatternResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiDestinationRequestRequestTypeDef,
+    UpdateApiDestinationResponseTypeDef,
     UpdateArchiveRequestRequestTypeDef,
+    UpdateArchiveResponseTypeDef,
     UpdateConnectionApiKeyAuthRequestParametersTypeDef,
     UpdateConnectionBasicAuthRequestParametersTypeDef,
     UpdateConnectionOAuthClientRequestParametersTypeDef,
-    NetworkConfigurationTypeDef,
-    BatchParametersTypeDef,
-    CancelReplayResponseTypeDef,
-    CreateApiDestinationResponseTypeDef,
-    CreateArchiveResponseTypeDef,
-    CreateConnectionResponseTypeDef,
-    CreateEventBusResponseTypeDef,
-    CreatePartnerEventSourceResponseTypeDef,
-    DeauthorizeConnectionResponseTypeDef,
-    DeleteConnectionResponseTypeDef,
-    DescribeApiDestinationResponseTypeDef,
-    DescribeArchiveResponseTypeDef,
-    DescribeEventBusResponseTypeDef,
-    DescribeEventSourceResponseTypeDef,
-    DescribePartnerEventSourceResponseTypeDef,
-    DescribeRuleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    UpdateConnectionResponseTypeDef,
     ListApiDestinationsResponseTypeDef,
     ListArchivesResponseTypeDef,
-    ListRuleNamesByTargetResponseTypeDef,
-    PutRuleResponseTypeDef,
-    StartReplayResponseTypeDef,
-    TestEventPatternResponseTypeDef,
-    UpdateApiDestinationResponseTypeDef,
-    UpdateArchiveResponseTypeDef,
-    UpdateConnectionResponseTypeDef,
+    NetworkConfigurationTypeDef,
+    BatchParametersTypeDef,
     PutPermissionRequestRequestTypeDef,
     ConnectionHttpParametersTypeDef,
     ListConnectionsResponseTypeDef,
     CreateEventBusRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutRuleRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
@@ -444,17 +447,14 @@
     StartReplayRequestRequestTypeDef,
     ListEventBusesResponseTypeDef,
     ListEventSourcesResponseTypeDef,
     FailoverConfigTypeDef,
     ListPartnerEventSourceAccountsResponseTypeDef,
     ListPartnerEventSourcesResponseTypeDef,
     ListReplaysResponseTypeDef,
-    ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
-    ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
     ListRulesResponseTypeDef,
     PutEventsRequestRequestTypeDef,
     PutEventsResponseTypeDef,
     PutPartnerEventsRequestRequestTypeDef,
     PutPartnerEventsResponseTypeDef,
     PutTargetsResponseTypeDef,
     RemoveTargetsResponseTypeDef,
@@ -491,43 +491,43 @@
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

### Comparing `types-aiobotocore-events-2.5.0.post1/setup.py` & `types-aiobotocore-events-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-events.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-events",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_events"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.EventBridge 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.EventBridge 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/"
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

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/__init__.py` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/__init__.pyi` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/__main__.py` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.EventBridge 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.EventBridge 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge\nOther"
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

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/client.py` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/client.pyi` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/literals.py` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/literals.pyi`

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
     "ApiDestinationHttpMethodType",
     "ApiDestinationStateType",
     "ArchiveStateType",
     "AssignPublicIpType",
     "ConnectionAuthorizationTypeType",
     "ConnectionOAuthHttpMethodType",
@@ -42,15 +41,14 @@
     "EventBridgeServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 ApiDestinationHttpMethodType = Literal["DELETE", "GET", "HEAD", "OPTIONS", "PATCH", "POST", "PUT"]
 ApiDestinationStateType = Literal["ACTIVE", "INACTIVE"]
 ArchiveStateType = Literal[
     "CREATE_FAILED", "CREATING", "DISABLED", "ENABLED", "UPDATE_FAILED", "UPDATING"
 ]
 AssignPublicIpType = Literal["DISABLED", "ENABLED"]
 ConnectionAuthorizationTypeType = Literal["API_KEY", "BASIC", "OAUTH_CLIENT_CREDENTIALS"]
@@ -131,14 +129,15 @@
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
@@ -217,14 +216,15 @@
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
@@ -235,14 +235,15 @@
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
@@ -278,14 +279,15 @@
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
@@ -304,16 +306,19 @@
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
@@ -397,15 +402,17 @@
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

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/literals.pyi` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ApiDestinationHttpMethodType",
     "ApiDestinationStateType",
     "ArchiveStateType",
     "AssignPublicIpType",
     "ConnectionAuthorizationTypeType",
     "ConnectionOAuthHttpMethodType",
@@ -41,14 +42,15 @@
     "EventBridgeServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 ApiDestinationHttpMethodType = Literal["DELETE", "GET", "HEAD", "OPTIONS", "PATCH", "POST", "PUT"]
 ApiDestinationStateType = Literal["ACTIVE", "INACTIVE"]
 ArchiveStateType = Literal[
     "CREATE_FAILED", "CREATING", "DISABLED", "ENABLED", "UPDATE_FAILED", "UPDATING"
 ]
 AssignPublicIpType = Literal["DISABLED", "ENABLED"]
 ConnectionAuthorizationTypeType = Literal["API_KEY", "BASIC", "OAUTH_CLIENT_CREDENTIALS"]
@@ -129,14 +131,15 @@
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
@@ -215,14 +218,15 @@
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
@@ -233,14 +237,15 @@
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
@@ -276,14 +281,15 @@
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
@@ -302,16 +308,19 @@
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
@@ -395,15 +404,17 @@
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

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/paginator.py` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,33 +20,26 @@
         client: EventBridgeClient
 
         list_rule_names_by_target_paginator: ListRuleNamesByTargetPaginator = client.get_paginator("list_rule_names_by_target")
         list_rules_paginator: ListRulesPaginator = client.get_paginator("list_rules")
         list_targets_by_rule_paginator: ListTargetsByRulePaginator = client.get_paginator("list_targets_by_rule")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListRuleNamesByTargetResponseTypeDef,
     ListRulesResponseTypeDef,
     ListTargetsByRuleResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListRuleNamesByTargetPaginator", "ListRulesPaginator", "ListTargetsByRulePaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -63,15 +56,15 @@
     """
 
     def paginate(
         self,
         *,
         TargetArn: str,
         EventBusName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRuleNamesByTargetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListRuleNamesByTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listrulenamesbytargetpaginator)
         """
 
 
@@ -82,28 +75,32 @@
     """
 
     def paginate(
         self,
         *,
         NamePrefix: str = ...,
         EventBusName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listrulespaginator)
         """
 
 
 class ListTargetsByRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListTargetsByRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listtargetsbyrulepaginator)
     """
 
     def paginate(
-        self, *, Rule: str, EventBusName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        Rule: str,
+        EventBusName: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsByRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListTargetsByRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listtargetsbyrulepaginator)
         """
```

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/paginator.pyi` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,32 +20,26 @@
         client: EventBridgeClient
 
         list_rule_names_by_target_paginator: ListRuleNamesByTargetPaginator = client.get_paginator("list_rule_names_by_target")
         list_rules_paginator: ListRulesPaginator = client.get_paginator("list_rules")
         list_targets_by_rule_paginator: ListTargetsByRulePaginator = client.get_paginator("list_targets_by_rule")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListRuleNamesByTargetResponseTypeDef,
     ListRulesResponseTypeDef,
     ListTargetsByRuleResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListRuleNamesByTargetPaginator", "ListRulesPaginator", "ListTargetsByRulePaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -59,15 +53,15 @@
     """
 
     def paginate(
         self,
         *,
         TargetArn: str,
         EventBusName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRuleNamesByTargetResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListRuleNamesByTarget.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listrulenamesbytargetpaginator)
         """
 
 class ListRulesPaginator(AioPaginator):
@@ -77,27 +71,31 @@
     """
 
     def paginate(
         self,
         *,
         NamePrefix: str = ...,
         EventBusName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listrulespaginator)
         """
 
 class ListTargetsByRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListTargetsByRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listtargetsbyrulepaginator)
     """
 
     def paginate(
-        self, *, Rule: str, EventBusName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        Rule: str,
+        EventBusName: str = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTargetsByRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge.Paginator.ListTargetsByRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/paginators/#listtargetsbyrulepaginator)
         """
```

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/type_defs.py` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/type_defs.py`

 * *Files 0% similar despite different names*

```diff
@@ -47,56 +47,70 @@
     "ActivateEventSourceRequestRequestTypeDef",
     "ApiDestinationTypeDef",
     "ArchiveTypeDef",
     "AwsVpcConfigurationTypeDef",
     "BatchArrayPropertiesTypeDef",
     "BatchRetryStrategyTypeDef",
     "CancelReplayRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelReplayResponseTypeDef",
     "CapacityProviderStrategyItemTypeDef",
     "ConditionTypeDef",
     "ConnectionApiKeyAuthResponseParametersTypeDef",
     "ConnectionBasicAuthResponseParametersTypeDef",
     "ConnectionBodyParameterTypeDef",
     "ConnectionHeaderParameterTypeDef",
     "ConnectionQueryStringParameterTypeDef",
     "ConnectionOAuthClientResponseParametersTypeDef",
     "ConnectionTypeDef",
     "CreateApiDestinationRequestRequestTypeDef",
+    "CreateApiDestinationResponseTypeDef",
     "CreateArchiveRequestRequestTypeDef",
+    "CreateArchiveResponseTypeDef",
     "CreateConnectionApiKeyAuthRequestParametersTypeDef",
     "CreateConnectionBasicAuthRequestParametersTypeDef",
     "CreateConnectionOAuthClientRequestParametersTypeDef",
+    "CreateConnectionResponseTypeDef",
     "EndpointEventBusTypeDef",
     "ReplicationConfigTypeDef",
     "TagTypeDef",
+    "CreateEventBusResponseTypeDef",
     "CreatePartnerEventSourceRequestRequestTypeDef",
+    "CreatePartnerEventSourceResponseTypeDef",
     "DeactivateEventSourceRequestRequestTypeDef",
     "DeadLetterConfigTypeDef",
     "DeauthorizeConnectionRequestRequestTypeDef",
+    "DeauthorizeConnectionResponseTypeDef",
     "DeleteApiDestinationRequestRequestTypeDef",
     "DeleteArchiveRequestRequestTypeDef",
     "DeleteConnectionRequestRequestTypeDef",
+    "DeleteConnectionResponseTypeDef",
     "DeleteEndpointRequestRequestTypeDef",
     "DeleteEventBusRequestRequestTypeDef",
     "DeletePartnerEventSourceRequestRequestTypeDef",
     "DeleteRuleRequestRequestTypeDef",
     "DescribeApiDestinationRequestRequestTypeDef",
+    "DescribeApiDestinationResponseTypeDef",
     "DescribeArchiveRequestRequestTypeDef",
+    "DescribeArchiveResponseTypeDef",
     "DescribeConnectionRequestRequestTypeDef",
     "DescribeEndpointRequestRequestTypeDef",
     "DescribeEventBusRequestRequestTypeDef",
+    "DescribeEventBusResponseTypeDef",
     "DescribeEventSourceRequestRequestTypeDef",
+    "DescribeEventSourceResponseTypeDef",
     "DescribePartnerEventSourceRequestRequestTypeDef",
+    "DescribePartnerEventSourceResponseTypeDef",
     "DescribeReplayRequestRequestTypeDef",
     "ReplayDestinationTypeDef",
     "DescribeRuleRequestRequestTypeDef",
+    "DescribeRuleResponseTypeDef",
     "DisableRuleRequestRequestTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableRuleRequestRequestTypeDef",
     "EventBusTypeDef",
     "EventSourceTypeDef",
     "PrimaryTypeDef",
     "SecondaryTypeDef",
     "HttpParametersTypeDef",
     "InputTransformerTypeDef",
@@ -109,66 +123,55 @@
     "ListEventSourcesRequestRequestTypeDef",
     "ListPartnerEventSourceAccountsRequestRequestTypeDef",
     "PartnerEventSourceAccountTypeDef",
     "ListPartnerEventSourcesRequestRequestTypeDef",
     "PartnerEventSourceTypeDef",
     "ListReplaysRequestRequestTypeDef",
     "ReplayTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
     "ListRuleNamesByTargetRequestRequestTypeDef",
+    "ListRuleNamesByTargetResponseTypeDef",
+    "ListRulesRequestListRulesPaginateTypeDef",
     "ListRulesRequestRequestTypeDef",
     "RuleTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
     "ListTargetsByRuleRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutEventsRequestEntryTypeDef",
     "PutEventsResultEntryTypeDef",
     "PutPartnerEventsRequestEntryTypeDef",
     "PutPartnerEventsResultEntryTypeDef",
+    "PutRuleResponseTypeDef",
     "PutTargetsResultEntryTypeDef",
     "RedshiftDataParametersTypeDef",
     "RemovePermissionRequestRequestTypeDef",
     "RemoveTargetsRequestRequestTypeDef",
     "RemoveTargetsResultEntryTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryPolicyTypeDef",
     "RunCommandTargetTypeDef",
     "SageMakerPipelineParameterTypeDef",
     "SqsParametersTypeDef",
+    "StartReplayResponseTypeDef",
     "TestEventPatternRequestRequestTypeDef",
+    "TestEventPatternResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApiDestinationRequestRequestTypeDef",
+    "UpdateApiDestinationResponseTypeDef",
     "UpdateArchiveRequestRequestTypeDef",
+    "UpdateArchiveResponseTypeDef",
     "UpdateConnectionApiKeyAuthRequestParametersTypeDef",
     "UpdateConnectionBasicAuthRequestParametersTypeDef",
     "UpdateConnectionOAuthClientRequestParametersTypeDef",
-    "NetworkConfigurationTypeDef",
-    "BatchParametersTypeDef",
-    "CancelReplayResponseTypeDef",
-    "CreateApiDestinationResponseTypeDef",
-    "CreateArchiveResponseTypeDef",
-    "CreateConnectionResponseTypeDef",
-    "CreateEventBusResponseTypeDef",
-    "CreatePartnerEventSourceResponseTypeDef",
-    "DeauthorizeConnectionResponseTypeDef",
-    "DeleteConnectionResponseTypeDef",
-    "DescribeApiDestinationResponseTypeDef",
-    "DescribeArchiveResponseTypeDef",
-    "DescribeEventBusResponseTypeDef",
-    "DescribeEventSourceResponseTypeDef",
-    "DescribePartnerEventSourceResponseTypeDef",
-    "DescribeRuleResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "UpdateConnectionResponseTypeDef",
     "ListApiDestinationsResponseTypeDef",
     "ListArchivesResponseTypeDef",
-    "ListRuleNamesByTargetResponseTypeDef",
-    "PutRuleResponseTypeDef",
-    "StartReplayResponseTypeDef",
-    "TestEventPatternResponseTypeDef",
-    "UpdateApiDestinationResponseTypeDef",
-    "UpdateArchiveResponseTypeDef",
-    "UpdateConnectionResponseTypeDef",
+    "NetworkConfigurationTypeDef",
+    "BatchParametersTypeDef",
     "PutPermissionRequestRequestTypeDef",
     "ConnectionHttpParametersTypeDef",
     "ListConnectionsResponseTypeDef",
     "CreateEventBusRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "PutRuleRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
@@ -176,17 +179,14 @@
     "StartReplayRequestRequestTypeDef",
     "ListEventBusesResponseTypeDef",
     "ListEventSourcesResponseTypeDef",
     "FailoverConfigTypeDef",
     "ListPartnerEventSourceAccountsResponseTypeDef",
     "ListPartnerEventSourcesResponseTypeDef",
     "ListReplaysResponseTypeDef",
-    "ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
-    "ListRulesRequestListRulesPaginateTypeDef",
-    "ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
     "ListRulesResponseTypeDef",
     "PutEventsRequestRequestTypeDef",
     "PutEventsResponseTypeDef",
     "PutPartnerEventsRequestRequestTypeDef",
     "PutPartnerEventsResponseTypeDef",
     "PutTargetsResponseTypeDef",
     "RemoveTargetsResponseTypeDef",
@@ -294,22 +294,21 @@
 CancelReplayRequestRequestTypeDef = TypedDict(
     "CancelReplayRequestRequestTypeDef",
     {
         "ReplayName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelReplayResponseTypeDef = TypedDict(
+    "CancelReplayResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ReplayArn": str,
+        "State": ReplayStateType,
+        "StateReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCapacityProviderStrategyItemTypeDef = TypedDict(
     "_RequiredCapacityProviderStrategyItemTypeDef",
     {
         "capacityProvider": str,
@@ -431,14 +430,25 @@
 class CreateApiDestinationRequestRequestTypeDef(
     _RequiredCreateApiDestinationRequestRequestTypeDef,
     _OptionalCreateApiDestinationRequestRequestTypeDef,
 ):
     pass
 
 
+CreateApiDestinationResponseTypeDef = TypedDict(
+    "CreateApiDestinationResponseTypeDef",
+    {
+        "ApiDestinationArn": str,
+        "ApiDestinationState": ApiDestinationStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateArchiveRequestRequestTypeDef = TypedDict(
     "_RequiredCreateArchiveRequestRequestTypeDef",
     {
         "ArchiveName": str,
         "EventSourceArn": str,
     },
 )
@@ -455,14 +465,25 @@
 
 class CreateArchiveRequestRequestTypeDef(
     _RequiredCreateArchiveRequestRequestTypeDef, _OptionalCreateArchiveRequestRequestTypeDef
 ):
     pass
 
 
+CreateArchiveResponseTypeDef = TypedDict(
+    "CreateArchiveResponseTypeDef",
+    {
+        "ArchiveArn": str,
+        "State": ArchiveStateType,
+        "StateReason": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateConnectionApiKeyAuthRequestParametersTypeDef = TypedDict(
     "CreateConnectionApiKeyAuthRequestParametersTypeDef",
     {
         "ApiKeyName": str,
         "ApiKeyValue": str,
     },
 )
@@ -479,14 +500,25 @@
     "CreateConnectionOAuthClientRequestParametersTypeDef",
     {
         "ClientID": str,
         "ClientSecret": str,
     },
 )
 
+CreateConnectionResponseTypeDef = TypedDict(
+    "CreateConnectionResponseTypeDef",
+    {
+        "ConnectionArn": str,
+        "ConnectionState": ConnectionStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EndpointEventBusTypeDef = TypedDict(
     "EndpointEventBusTypeDef",
     {
         "EventBusArn": str,
     },
 )
 
@@ -502,22 +534,38 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateEventBusResponseTypeDef = TypedDict(
+    "CreateEventBusResponseTypeDef",
+    {
+        "EventBusArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreatePartnerEventSourceRequestRequestTypeDef = TypedDict(
     "CreatePartnerEventSourceRequestRequestTypeDef",
     {
         "Name": str,
         "Account": str,
     },
 )
 
+CreatePartnerEventSourceResponseTypeDef = TypedDict(
+    "CreatePartnerEventSourceResponseTypeDef",
+    {
+        "EventSourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeactivateEventSourceRequestRequestTypeDef = TypedDict(
     "DeactivateEventSourceRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -532,14 +580,26 @@
 DeauthorizeConnectionRequestRequestTypeDef = TypedDict(
     "DeauthorizeConnectionRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeauthorizeConnectionResponseTypeDef = TypedDict(
+    "DeauthorizeConnectionResponseTypeDef",
+    {
+        "ConnectionArn": str,
+        "ConnectionState": ConnectionStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LastAuthorizedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApiDestinationRequestRequestTypeDef = TypedDict(
     "DeleteApiDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -553,14 +613,26 @@
 DeleteConnectionRequestRequestTypeDef = TypedDict(
     "DeleteConnectionRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteConnectionResponseTypeDef = TypedDict(
+    "DeleteConnectionResponseTypeDef",
+    {
+        "ConnectionArn": str,
+        "ConnectionState": ConnectionStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LastAuthorizedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEndpointRequestRequestTypeDef = TypedDict(
     "DeleteEndpointRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -604,21 +676,56 @@
 DescribeApiDestinationRequestRequestTypeDef = TypedDict(
     "DescribeApiDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DescribeApiDestinationResponseTypeDef = TypedDict(
+    "DescribeApiDestinationResponseTypeDef",
+    {
+        "ApiDestinationArn": str,
+        "Name": str,
+        "Description": str,
+        "ApiDestinationState": ApiDestinationStateType,
+        "ConnectionArn": str,
+        "InvocationEndpoint": str,
+        "HttpMethod": ApiDestinationHttpMethodType,
+        "InvocationRateLimitPerSecond": int,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeArchiveRequestRequestTypeDef = TypedDict(
     "DescribeArchiveRequestRequestTypeDef",
     {
         "ArchiveName": str,
     },
 )
 
+DescribeArchiveResponseTypeDef = TypedDict(
+    "DescribeArchiveResponseTypeDef",
+    {
+        "ArchiveArn": str,
+        "ArchiveName": str,
+        "EventSourceArn": str,
+        "Description": str,
+        "EventPattern": str,
+        "State": ArchiveStateType,
+        "StateReason": str,
+        "RetentionDays": int,
+        "SizeBytes": int,
+        "EventCount": int,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeConnectionRequestRequestTypeDef = TypedDict(
     "DescribeConnectionRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -647,28 +754,60 @@
     "DescribeEventBusRequestRequestTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+DescribeEventBusResponseTypeDef = TypedDict(
+    "DescribeEventBusResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeEventSourceRequestRequestTypeDef = TypedDict(
     "DescribeEventSourceRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DescribeEventSourceResponseTypeDef = TypedDict(
+    "DescribeEventSourceResponseTypeDef",
+    {
+        "Arn": str,
+        "CreatedBy": str,
+        "CreationTime": datetime,
+        "ExpirationTime": datetime,
+        "Name": str,
+        "State": EventSourceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePartnerEventSourceRequestRequestTypeDef = TypedDict(
     "DescribePartnerEventSourceRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DescribePartnerEventSourceResponseTypeDef = TypedDict(
+    "DescribePartnerEventSourceResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeReplayRequestRequestTypeDef = TypedDict(
     "DescribeReplayRequestRequestTypeDef",
     {
         "ReplayName": str,
     },
 )
 
@@ -710,14 +849,31 @@
 
 class DescribeRuleRequestRequestTypeDef(
     _RequiredDescribeRuleRequestRequestTypeDef, _OptionalDescribeRuleRequestRequestTypeDef
 ):
     pass
 
 
+DescribeRuleResponseTypeDef = TypedDict(
+    "DescribeRuleResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "EventPattern": str,
+        "ScheduleExpression": str,
+        "State": RuleStateType,
+        "Description": str,
+        "RoleArn": str,
+        "ManagedBy": str,
+        "EventBusName": str,
+        "CreatedBy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisableRuleRequestRequestTypeDef = TypedDict(
     "_RequiredDisableRuleRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDisableRuleRequestRequestTypeDef = TypedDict(
@@ -749,14 +905,21 @@
     {
         "type": PlacementStrategyTypeType,
         "field": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEnableRuleRequestRequestTypeDef = TypedDict(
     "_RequiredEnableRuleRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalEnableRuleRequestRequestTypeDef = TypedDict(
@@ -1002,24 +1165,37 @@
         "EventLastReplayedTime": datetime,
         "ReplayStartTime": datetime,
         "ReplayEndTime": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
+    "_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TargetArn": str,
+    },
+)
+_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
+    "_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
+    {
+        "EventBusName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef(
+    _RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
+    _OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRuleNamesByTargetRequestRequestTypeDef = TypedDict(
     "_RequiredListRuleNamesByTargetRequestRequestTypeDef",
     {
         "TargetArn": str,
     },
 )
 _OptionalListRuleNamesByTargetRequestRequestTypeDef = TypedDict(
@@ -1036,14 +1212,33 @@
 class ListRuleNamesByTargetRequestRequestTypeDef(
     _RequiredListRuleNamesByTargetRequestRequestTypeDef,
     _OptionalListRuleNamesByTargetRequestRequestTypeDef,
 ):
     pass
 
 
+ListRuleNamesByTargetResponseTypeDef = TypedDict(
+    "ListRuleNamesByTargetResponseTypeDef",
+    {
+        "RuleNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "ListRulesRequestListRulesPaginateTypeDef",
+    {
+        "NamePrefix": str,
+        "EventBusName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRulesRequestRequestTypeDef = TypedDict(
     "ListRulesRequestRequestTypeDef",
     {
         "NamePrefix": str,
         "EventBusName": str,
         "NextToken": str,
         "Limit": int,
@@ -1070,14 +1265,37 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
+    "_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
+    {
+        "Rule": str,
+    },
+)
+_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
+    "_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
+    {
+        "EventBusName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef(
+    _RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
+    _OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTargetsByRuleRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsByRuleRequestRequestTypeDef",
     {
         "Rule": str,
     },
 )
 _OptionalListTargetsByRuleRequestRequestTypeDef = TypedDict(
@@ -1093,14 +1311,24 @@
 
 class ListTargetsByRuleRequestRequestTypeDef(
     _RequiredListTargetsByRuleRequestRequestTypeDef, _OptionalListTargetsByRuleRequestRequestTypeDef
 ):
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
+
 PutEventsRequestEntryTypeDef = TypedDict(
     "PutEventsRequestEntryTypeDef",
     {
         "Time": Union[datetime, str],
         "Source": str,
         "Resources": Sequence[str],
         "DetailType": str,
@@ -1139,38 +1367,47 @@
         "EventId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+PutRuleResponseTypeDef = TypedDict(
+    "PutRuleResponseTypeDef",
+    {
+        "RuleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutTargetsResultEntryTypeDef = TypedDict(
     "PutTargetsResultEntryTypeDef",
     {
         "TargetId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
 _RequiredRedshiftDataParametersTypeDef = TypedDict(
     "_RequiredRedshiftDataParametersTypeDef",
     {
         "Database": str,
-        "Sql": str,
     },
 )
 _OptionalRedshiftDataParametersTypeDef = TypedDict(
     "_OptionalRedshiftDataParametersTypeDef",
     {
         "SecretManagerArn": str,
         "DbUser": str,
+        "Sql": str,
         "StatementName": str,
         "WithEvent": bool,
+        "Sqls": List[str],
     },
     total=False,
 )
 
 
 class RedshiftDataParametersTypeDef(
     _RequiredRedshiftDataParametersTypeDef, _OptionalRedshiftDataParametersTypeDef
@@ -1217,14 +1454,25 @@
         "TargetId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
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
 RetryPolicyTypeDef = TypedDict(
     "RetryPolicyTypeDef",
     {
         "MaximumRetryAttempts": int,
         "MaximumEventAgeInSeconds": int,
     },
     total=False,
@@ -1250,22 +1498,41 @@
     "SqsParametersTypeDef",
     {
         "MessageGroupId": str,
     },
     total=False,
 )
 
+StartReplayResponseTypeDef = TypedDict(
+    "StartReplayResponseTypeDef",
+    {
+        "ReplayArn": str,
+        "State": ReplayStateType,
+        "StateReason": str,
+        "ReplayStartTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TestEventPatternRequestRequestTypeDef = TypedDict(
     "TestEventPatternRequestRequestTypeDef",
     {
         "EventPattern": str,
         "Event": str,
     },
 )
 
+TestEventPatternResponseTypeDef = TypedDict(
+    "TestEventPatternResponseTypeDef",
+    {
+        "Result": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -1292,14 +1559,25 @@
 class UpdateApiDestinationRequestRequestTypeDef(
     _RequiredUpdateApiDestinationRequestRequestTypeDef,
     _OptionalUpdateApiDestinationRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateApiDestinationResponseTypeDef = TypedDict(
+    "UpdateApiDestinationResponseTypeDef",
+    {
+        "ApiDestinationArn": str,
+        "ApiDestinationState": ApiDestinationStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateArchiveRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateArchiveRequestRequestTypeDef",
     {
         "ArchiveName": str,
     },
 )
 _OptionalUpdateArchiveRequestRequestTypeDef = TypedDict(
@@ -1315,14 +1593,25 @@
 
 class UpdateArchiveRequestRequestTypeDef(
     _RequiredUpdateArchiveRequestRequestTypeDef, _OptionalUpdateArchiveRequestRequestTypeDef
 ):
     pass
 
 
+UpdateArchiveResponseTypeDef = TypedDict(
+    "UpdateArchiveResponseTypeDef",
+    {
+        "ArchiveArn": str,
+        "State": ArchiveStateType,
+        "StateReason": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateConnectionApiKeyAuthRequestParametersTypeDef = TypedDict(
     "UpdateConnectionApiKeyAuthRequestParametersTypeDef",
     {
         "ApiKeyName": str,
         "ApiKeyValue": str,
     },
     total=False,
@@ -1342,304 +1631,72 @@
     {
         "ClientID": str,
         "ClientSecret": str,
     },
     total=False,
 )
 
-NetworkConfigurationTypeDef = TypedDict(
-    "NetworkConfigurationTypeDef",
-    {
-        "awsvpcConfiguration": AwsVpcConfigurationTypeDef,
-    },
-    total=False,
-)
-
-_RequiredBatchParametersTypeDef = TypedDict(
-    "_RequiredBatchParametersTypeDef",
-    {
-        "JobDefinition": str,
-        "JobName": str,
-    },
-)
-_OptionalBatchParametersTypeDef = TypedDict(
-    "_OptionalBatchParametersTypeDef",
-    {
-        "ArrayProperties": BatchArrayPropertiesTypeDef,
-        "RetryStrategy": BatchRetryStrategyTypeDef,
-    },
-    total=False,
-)
-
-
-class BatchParametersTypeDef(_RequiredBatchParametersTypeDef, _OptionalBatchParametersTypeDef):
-    pass
-
-
-CancelReplayResponseTypeDef = TypedDict(
-    "CancelReplayResponseTypeDef",
-    {
-        "ReplayArn": str,
-        "State": ReplayStateType,
-        "StateReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApiDestinationResponseTypeDef = TypedDict(
-    "CreateApiDestinationResponseTypeDef",
-    {
-        "ApiDestinationArn": str,
-        "ApiDestinationState": ApiDestinationStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateArchiveResponseTypeDef = TypedDict(
-    "CreateArchiveResponseTypeDef",
-    {
-        "ArchiveArn": str,
-        "State": ArchiveStateType,
-        "StateReason": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateConnectionResponseTypeDef = TypedDict(
-    "CreateConnectionResponseTypeDef",
-    {
-        "ConnectionArn": str,
-        "ConnectionState": ConnectionStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEventBusResponseTypeDef = TypedDict(
-    "CreateEventBusResponseTypeDef",
-    {
-        "EventBusArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePartnerEventSourceResponseTypeDef = TypedDict(
-    "CreatePartnerEventSourceResponseTypeDef",
-    {
-        "EventSourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeauthorizeConnectionResponseTypeDef = TypedDict(
-    "DeauthorizeConnectionResponseTypeDef",
-    {
-        "ConnectionArn": str,
-        "ConnectionState": ConnectionStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteConnectionResponseTypeDef = TypedDict(
-    "DeleteConnectionResponseTypeDef",
+UpdateConnectionResponseTypeDef = TypedDict(
+    "UpdateConnectionResponseTypeDef",
     {
         "ConnectionArn": str,
         "ConnectionState": ConnectionStateType,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
         "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApiDestinationResponseTypeDef = TypedDict(
-    "DescribeApiDestinationResponseTypeDef",
-    {
-        "ApiDestinationArn": str,
-        "Name": str,
-        "Description": str,
-        "ApiDestinationState": ApiDestinationStateType,
-        "ConnectionArn": str,
-        "InvocationEndpoint": str,
-        "HttpMethod": ApiDestinationHttpMethodType,
-        "InvocationRateLimitPerSecond": int,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeArchiveResponseTypeDef = TypedDict(
-    "DescribeArchiveResponseTypeDef",
-    {
-        "ArchiveArn": str,
-        "ArchiveName": str,
-        "EventSourceArn": str,
-        "Description": str,
-        "EventPattern": str,
-        "State": ArchiveStateType,
-        "StateReason": str,
-        "RetentionDays": int,
-        "SizeBytes": int,
-        "EventCount": int,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEventBusResponseTypeDef = TypedDict(
-    "DescribeEventBusResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEventSourceResponseTypeDef = TypedDict(
-    "DescribeEventSourceResponseTypeDef",
-    {
-        "Arn": str,
-        "CreatedBy": str,
-        "CreationTime": datetime,
-        "ExpirationTime": datetime,
-        "Name": str,
-        "State": EventSourceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePartnerEventSourceResponseTypeDef = TypedDict(
-    "DescribePartnerEventSourceResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRuleResponseTypeDef = TypedDict(
-    "DescribeRuleResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "EventPattern": str,
-        "ScheduleExpression": str,
-        "State": RuleStateType,
-        "Description": str,
-        "RoleArn": str,
-        "ManagedBy": str,
-        "EventBusName": str,
-        "CreatedBy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApiDestinationsResponseTypeDef = TypedDict(
     "ListApiDestinationsResponseTypeDef",
     {
         "ApiDestinations": List[ApiDestinationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListArchivesResponseTypeDef = TypedDict(
     "ListArchivesResponseTypeDef",
     {
         "Archives": List[ArchiveTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListRuleNamesByTargetResponseTypeDef = TypedDict(
-    "ListRuleNamesByTargetResponseTypeDef",
+NetworkConfigurationTypeDef = TypedDict(
+    "NetworkConfigurationTypeDef",
     {
-        "RuleNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "awsvpcConfiguration": AwsVpcConfigurationTypeDef,
     },
+    total=False,
 )
 
-PutRuleResponseTypeDef = TypedDict(
-    "PutRuleResponseTypeDef",
+_RequiredBatchParametersTypeDef = TypedDict(
+    "_RequiredBatchParametersTypeDef",
     {
-        "RuleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobDefinition": str,
+        "JobName": str,
     },
 )
-
-StartReplayResponseTypeDef = TypedDict(
-    "StartReplayResponseTypeDef",
+_OptionalBatchParametersTypeDef = TypedDict(
+    "_OptionalBatchParametersTypeDef",
     {
-        "ReplayArn": str,
-        "State": ReplayStateType,
-        "StateReason": str,
-        "ReplayStartTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ArrayProperties": BatchArrayPropertiesTypeDef,
+        "RetryStrategy": BatchRetryStrategyTypeDef,
     },
+    total=False,
 )
 
-TestEventPatternResponseTypeDef = TypedDict(
-    "TestEventPatternResponseTypeDef",
-    {
-        "Result": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateApiDestinationResponseTypeDef = TypedDict(
-    "UpdateApiDestinationResponseTypeDef",
-    {
-        "ApiDestinationArn": str,
-        "ApiDestinationState": ApiDestinationStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateArchiveResponseTypeDef = TypedDict(
-    "UpdateArchiveResponseTypeDef",
-    {
-        "ArchiveArn": str,
-        "State": ArchiveStateType,
-        "StateReason": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class BatchParametersTypeDef(_RequiredBatchParametersTypeDef, _OptionalBatchParametersTypeDef):
+    pass
 
-UpdateConnectionResponseTypeDef = TypedDict(
-    "UpdateConnectionResponseTypeDef",
-    {
-        "ConnectionArn": str,
-        "ConnectionState": ConnectionStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 PutPermissionRequestRequestTypeDef = TypedDict(
     "PutPermissionRequestRequestTypeDef",
     {
         "EventBusName": str,
         "Action": str,
         "Principal": str,
@@ -1661,15 +1718,15 @@
 )
 
 ListConnectionsResponseTypeDef = TypedDict(
     "ListConnectionsResponseTypeDef",
     {
         "Connections": List[ConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEventBusRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEventBusRequestRequestTypeDef",
     {
         "Name": str,
@@ -1691,15 +1748,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutRuleRequestRequestTypeDef = TypedDict(
     "_RequiredPutRuleRequestRequestTypeDef",
     {
         "Name": str,
@@ -1745,15 +1802,15 @@
         "EventSourceArn": str,
         "Destination": ReplayDestinationTypeDef,
         "EventStartTime": datetime,
         "EventEndTime": datetime,
         "EventLastReplayedTime": datetime,
         "ReplayStartTime": datetime,
         "ReplayEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartReplayRequestRequestTypeDef = TypedDict(
     "_RequiredStartReplayRequestRequestTypeDef",
     {
         "ReplayName": str,
@@ -1779,24 +1836,24 @@
 
 
 ListEventBusesResponseTypeDef = TypedDict(
     "ListEventBusesResponseTypeDef",
     {
         "EventBuses": List[EventBusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventSourcesResponseTypeDef = TypedDict(
     "ListEventSourcesResponseTypeDef",
     {
         "EventSources": List[EventSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverConfigTypeDef = TypedDict(
     "FailoverConfigTypeDef",
     {
         "Primary": PrimaryTypeDef,
@@ -1805,98 +1862,42 @@
 )
 
 ListPartnerEventSourceAccountsResponseTypeDef = TypedDict(
     "ListPartnerEventSourceAccountsResponseTypeDef",
     {
         "PartnerEventSourceAccounts": List[PartnerEventSourceAccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPartnerEventSourcesResponseTypeDef = TypedDict(
     "ListPartnerEventSourcesResponseTypeDef",
     {
         "PartnerEventSources": List[PartnerEventSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReplaysResponseTypeDef = TypedDict(
     "ListReplaysResponseTypeDef",
     {
         "Replays": List[ReplayTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
-    "_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
-    {
-        "TargetArn": str,
-    },
-)
-_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
-    "_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
-    {
-        "EventBusName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-
-class ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef(
-    _RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
-    _OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
-):
-    pass
-
-
-ListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "ListRulesRequestListRulesPaginateTypeDef",
-    {
-        "NamePrefix": str,
-        "EventBusName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
-    "_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
-    {
-        "Rule": str,
-    },
-)
-_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
-    "_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
-    {
-        "EventBusName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
-
-class ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef(
-    _RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
-    _OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
-):
-    pass
-
-
 ListRulesResponseTypeDef = TypedDict(
     "ListRulesResponseTypeDef",
     {
         "Rules": List[RuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutEventsRequestRequestTypeDef = TypedDict(
     "_RequiredPutEventsRequestRequestTypeDef",
     {
         "Entries": Sequence[PutEventsRequestEntryTypeDef],
@@ -1918,15 +1919,15 @@
 
 
 PutEventsResponseTypeDef = TypedDict(
     "PutEventsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "Entries": List[PutEventsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPartnerEventsRequestRequestTypeDef = TypedDict(
     "PutPartnerEventsRequestRequestTypeDef",
     {
         "Entries": Sequence[PutPartnerEventsRequestEntryTypeDef],
@@ -1934,33 +1935,33 @@
 )
 
 PutPartnerEventsResponseTypeDef = TypedDict(
     "PutPartnerEventsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "Entries": List[PutPartnerEventsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutTargetsResponseTypeDef = TypedDict(
     "PutTargetsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "FailedEntries": List[PutTargetsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveTargetsResponseTypeDef = TypedDict(
     "RemoveTargetsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "FailedEntries": List[RemoveTargetsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RunCommandParametersTypeDef = TypedDict(
     "RunCommandParametersTypeDef",
     {
         "RunCommandTargets": List[RunCommandTargetTypeDef],
@@ -2156,15 +2157,15 @@
         "Name": str,
         "Arn": str,
         "RoutingConfig": RoutingConfigTypeDef,
         "ReplicationConfig": ReplicationConfigTypeDef,
         "EventBuses": List[EndpointEventBusTypeDef],
         "RoleArn": str,
         "State": EndpointStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointResponseTypeDef = TypedDict(
     "DescribeEndpointResponseTypeDef",
     {
         "Name": str,
@@ -2176,15 +2177,15 @@
         "RoleArn": str,
         "EndpointId": str,
         "EndpointUrl": str,
         "State": EndpointStateType,
         "StateReason": str,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointTypeDef = TypedDict(
     "EndpointTypeDef",
     {
         "Name": str,
@@ -2237,24 +2238,24 @@
         "RoutingConfig": RoutingConfigTypeDef,
         "ReplicationConfig": ReplicationConfigTypeDef,
         "EventBuses": List[EndpointEventBusTypeDef],
         "RoleArn": str,
         "EndpointId": str,
         "EndpointUrl": str,
         "State": EndpointStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsByRuleResponseTypeDef = TypedDict(
     "ListTargetsByRuleResponseTypeDef",
     {
         "Targets": List[TargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutTargetsRequestRequestTypeDef = TypedDict(
     "_RequiredPutTargetsRequestRequestTypeDef",
     {
         "Rule": str,
@@ -2286,15 +2287,15 @@
         "StateReason": str,
         "AuthorizationType": ConnectionAuthorizationTypeType,
         "SecretArn": str,
         "AuthParameters": ConnectionAuthResponseParametersTypeDef,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
         "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectionRequestRequestTypeDef",
     {
         "Name": str,
@@ -2341,10 +2342,10 @@
 
 
 ListEndpointsResponseTypeDef = TypedDict(
     "ListEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events/type_defs.pyi` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -46,56 +46,70 @@
     "ActivateEventSourceRequestRequestTypeDef",
     "ApiDestinationTypeDef",
     "ArchiveTypeDef",
     "AwsVpcConfigurationTypeDef",
     "BatchArrayPropertiesTypeDef",
     "BatchRetryStrategyTypeDef",
     "CancelReplayRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelReplayResponseTypeDef",
     "CapacityProviderStrategyItemTypeDef",
     "ConditionTypeDef",
     "ConnectionApiKeyAuthResponseParametersTypeDef",
     "ConnectionBasicAuthResponseParametersTypeDef",
     "ConnectionBodyParameterTypeDef",
     "ConnectionHeaderParameterTypeDef",
     "ConnectionQueryStringParameterTypeDef",
     "ConnectionOAuthClientResponseParametersTypeDef",
     "ConnectionTypeDef",
     "CreateApiDestinationRequestRequestTypeDef",
+    "CreateApiDestinationResponseTypeDef",
     "CreateArchiveRequestRequestTypeDef",
+    "CreateArchiveResponseTypeDef",
     "CreateConnectionApiKeyAuthRequestParametersTypeDef",
     "CreateConnectionBasicAuthRequestParametersTypeDef",
     "CreateConnectionOAuthClientRequestParametersTypeDef",
+    "CreateConnectionResponseTypeDef",
     "EndpointEventBusTypeDef",
     "ReplicationConfigTypeDef",
     "TagTypeDef",
+    "CreateEventBusResponseTypeDef",
     "CreatePartnerEventSourceRequestRequestTypeDef",
+    "CreatePartnerEventSourceResponseTypeDef",
     "DeactivateEventSourceRequestRequestTypeDef",
     "DeadLetterConfigTypeDef",
     "DeauthorizeConnectionRequestRequestTypeDef",
+    "DeauthorizeConnectionResponseTypeDef",
     "DeleteApiDestinationRequestRequestTypeDef",
     "DeleteArchiveRequestRequestTypeDef",
     "DeleteConnectionRequestRequestTypeDef",
+    "DeleteConnectionResponseTypeDef",
     "DeleteEndpointRequestRequestTypeDef",
     "DeleteEventBusRequestRequestTypeDef",
     "DeletePartnerEventSourceRequestRequestTypeDef",
     "DeleteRuleRequestRequestTypeDef",
     "DescribeApiDestinationRequestRequestTypeDef",
+    "DescribeApiDestinationResponseTypeDef",
     "DescribeArchiveRequestRequestTypeDef",
+    "DescribeArchiveResponseTypeDef",
     "DescribeConnectionRequestRequestTypeDef",
     "DescribeEndpointRequestRequestTypeDef",
     "DescribeEventBusRequestRequestTypeDef",
+    "DescribeEventBusResponseTypeDef",
     "DescribeEventSourceRequestRequestTypeDef",
+    "DescribeEventSourceResponseTypeDef",
     "DescribePartnerEventSourceRequestRequestTypeDef",
+    "DescribePartnerEventSourceResponseTypeDef",
     "DescribeReplayRequestRequestTypeDef",
     "ReplayDestinationTypeDef",
     "DescribeRuleRequestRequestTypeDef",
+    "DescribeRuleResponseTypeDef",
     "DisableRuleRequestRequestTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableRuleRequestRequestTypeDef",
     "EventBusTypeDef",
     "EventSourceTypeDef",
     "PrimaryTypeDef",
     "SecondaryTypeDef",
     "HttpParametersTypeDef",
     "InputTransformerTypeDef",
@@ -108,66 +122,55 @@
     "ListEventSourcesRequestRequestTypeDef",
     "ListPartnerEventSourceAccountsRequestRequestTypeDef",
     "PartnerEventSourceAccountTypeDef",
     "ListPartnerEventSourcesRequestRequestTypeDef",
     "PartnerEventSourceTypeDef",
     "ListReplaysRequestRequestTypeDef",
     "ReplayTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
     "ListRuleNamesByTargetRequestRequestTypeDef",
+    "ListRuleNamesByTargetResponseTypeDef",
+    "ListRulesRequestListRulesPaginateTypeDef",
     "ListRulesRequestRequestTypeDef",
     "RuleTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
     "ListTargetsByRuleRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutEventsRequestEntryTypeDef",
     "PutEventsResultEntryTypeDef",
     "PutPartnerEventsRequestEntryTypeDef",
     "PutPartnerEventsResultEntryTypeDef",
+    "PutRuleResponseTypeDef",
     "PutTargetsResultEntryTypeDef",
     "RedshiftDataParametersTypeDef",
     "RemovePermissionRequestRequestTypeDef",
     "RemoveTargetsRequestRequestTypeDef",
     "RemoveTargetsResultEntryTypeDef",
+    "ResponseMetadataTypeDef",
     "RetryPolicyTypeDef",
     "RunCommandTargetTypeDef",
     "SageMakerPipelineParameterTypeDef",
     "SqsParametersTypeDef",
+    "StartReplayResponseTypeDef",
     "TestEventPatternRequestRequestTypeDef",
+    "TestEventPatternResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApiDestinationRequestRequestTypeDef",
+    "UpdateApiDestinationResponseTypeDef",
     "UpdateArchiveRequestRequestTypeDef",
+    "UpdateArchiveResponseTypeDef",
     "UpdateConnectionApiKeyAuthRequestParametersTypeDef",
     "UpdateConnectionBasicAuthRequestParametersTypeDef",
     "UpdateConnectionOAuthClientRequestParametersTypeDef",
-    "NetworkConfigurationTypeDef",
-    "BatchParametersTypeDef",
-    "CancelReplayResponseTypeDef",
-    "CreateApiDestinationResponseTypeDef",
-    "CreateArchiveResponseTypeDef",
-    "CreateConnectionResponseTypeDef",
-    "CreateEventBusResponseTypeDef",
-    "CreatePartnerEventSourceResponseTypeDef",
-    "DeauthorizeConnectionResponseTypeDef",
-    "DeleteConnectionResponseTypeDef",
-    "DescribeApiDestinationResponseTypeDef",
-    "DescribeArchiveResponseTypeDef",
-    "DescribeEventBusResponseTypeDef",
-    "DescribeEventSourceResponseTypeDef",
-    "DescribePartnerEventSourceResponseTypeDef",
-    "DescribeRuleResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "UpdateConnectionResponseTypeDef",
     "ListApiDestinationsResponseTypeDef",
     "ListArchivesResponseTypeDef",
-    "ListRuleNamesByTargetResponseTypeDef",
-    "PutRuleResponseTypeDef",
-    "StartReplayResponseTypeDef",
-    "TestEventPatternResponseTypeDef",
-    "UpdateApiDestinationResponseTypeDef",
-    "UpdateArchiveResponseTypeDef",
-    "UpdateConnectionResponseTypeDef",
+    "NetworkConfigurationTypeDef",
+    "BatchParametersTypeDef",
     "PutPermissionRequestRequestTypeDef",
     "ConnectionHttpParametersTypeDef",
     "ListConnectionsResponseTypeDef",
     "CreateEventBusRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "PutRuleRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
@@ -175,17 +178,14 @@
     "StartReplayRequestRequestTypeDef",
     "ListEventBusesResponseTypeDef",
     "ListEventSourcesResponseTypeDef",
     "FailoverConfigTypeDef",
     "ListPartnerEventSourceAccountsResponseTypeDef",
     "ListPartnerEventSourcesResponseTypeDef",
     "ListReplaysResponseTypeDef",
-    "ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
-    "ListRulesRequestListRulesPaginateTypeDef",
-    "ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
     "ListRulesResponseTypeDef",
     "PutEventsRequestRequestTypeDef",
     "PutEventsResponseTypeDef",
     "PutPartnerEventsRequestRequestTypeDef",
     "PutPartnerEventsResponseTypeDef",
     "PutTargetsResponseTypeDef",
     "RemoveTargetsResponseTypeDef",
@@ -291,22 +291,21 @@
 CancelReplayRequestRequestTypeDef = TypedDict(
     "CancelReplayRequestRequestTypeDef",
     {
         "ReplayName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelReplayResponseTypeDef = TypedDict(
+    "CancelReplayResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ReplayArn": str,
+        "State": ReplayStateType,
+        "StateReason": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCapacityProviderStrategyItemTypeDef = TypedDict(
     "_RequiredCapacityProviderStrategyItemTypeDef",
     {
         "capacityProvider": str,
@@ -424,14 +423,25 @@
 
 class CreateApiDestinationRequestRequestTypeDef(
     _RequiredCreateApiDestinationRequestRequestTypeDef,
     _OptionalCreateApiDestinationRequestRequestTypeDef,
 ):
     pass
 
+CreateApiDestinationResponseTypeDef = TypedDict(
+    "CreateApiDestinationResponseTypeDef",
+    {
+        "ApiDestinationArn": str,
+        "ApiDestinationState": ApiDestinationStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateArchiveRequestRequestTypeDef = TypedDict(
     "_RequiredCreateArchiveRequestRequestTypeDef",
     {
         "ArchiveName": str,
         "EventSourceArn": str,
     },
 )
@@ -446,14 +456,25 @@
 )
 
 class CreateArchiveRequestRequestTypeDef(
     _RequiredCreateArchiveRequestRequestTypeDef, _OptionalCreateArchiveRequestRequestTypeDef
 ):
     pass
 
+CreateArchiveResponseTypeDef = TypedDict(
+    "CreateArchiveResponseTypeDef",
+    {
+        "ArchiveArn": str,
+        "State": ArchiveStateType,
+        "StateReason": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateConnectionApiKeyAuthRequestParametersTypeDef = TypedDict(
     "CreateConnectionApiKeyAuthRequestParametersTypeDef",
     {
         "ApiKeyName": str,
         "ApiKeyValue": str,
     },
 )
@@ -470,14 +491,25 @@
     "CreateConnectionOAuthClientRequestParametersTypeDef",
     {
         "ClientID": str,
         "ClientSecret": str,
     },
 )
 
+CreateConnectionResponseTypeDef = TypedDict(
+    "CreateConnectionResponseTypeDef",
+    {
+        "ConnectionArn": str,
+        "ConnectionState": ConnectionStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EndpointEventBusTypeDef = TypedDict(
     "EndpointEventBusTypeDef",
     {
         "EventBusArn": str,
     },
 )
 
@@ -493,22 +525,38 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateEventBusResponseTypeDef = TypedDict(
+    "CreateEventBusResponseTypeDef",
+    {
+        "EventBusArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreatePartnerEventSourceRequestRequestTypeDef = TypedDict(
     "CreatePartnerEventSourceRequestRequestTypeDef",
     {
         "Name": str,
         "Account": str,
     },
 )
 
+CreatePartnerEventSourceResponseTypeDef = TypedDict(
+    "CreatePartnerEventSourceResponseTypeDef",
+    {
+        "EventSourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeactivateEventSourceRequestRequestTypeDef = TypedDict(
     "DeactivateEventSourceRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -523,14 +571,26 @@
 DeauthorizeConnectionRequestRequestTypeDef = TypedDict(
     "DeauthorizeConnectionRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeauthorizeConnectionResponseTypeDef = TypedDict(
+    "DeauthorizeConnectionResponseTypeDef",
+    {
+        "ConnectionArn": str,
+        "ConnectionState": ConnectionStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LastAuthorizedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApiDestinationRequestRequestTypeDef = TypedDict(
     "DeleteApiDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -544,14 +604,26 @@
 DeleteConnectionRequestRequestTypeDef = TypedDict(
     "DeleteConnectionRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteConnectionResponseTypeDef = TypedDict(
+    "DeleteConnectionResponseTypeDef",
+    {
+        "ConnectionArn": str,
+        "ConnectionState": ConnectionStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LastAuthorizedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteEndpointRequestRequestTypeDef = TypedDict(
     "DeleteEndpointRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -593,21 +665,56 @@
 DescribeApiDestinationRequestRequestTypeDef = TypedDict(
     "DescribeApiDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DescribeApiDestinationResponseTypeDef = TypedDict(
+    "DescribeApiDestinationResponseTypeDef",
+    {
+        "ApiDestinationArn": str,
+        "Name": str,
+        "Description": str,
+        "ApiDestinationState": ApiDestinationStateType,
+        "ConnectionArn": str,
+        "InvocationEndpoint": str,
+        "HttpMethod": ApiDestinationHttpMethodType,
+        "InvocationRateLimitPerSecond": int,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeArchiveRequestRequestTypeDef = TypedDict(
     "DescribeArchiveRequestRequestTypeDef",
     {
         "ArchiveName": str,
     },
 )
 
+DescribeArchiveResponseTypeDef = TypedDict(
+    "DescribeArchiveResponseTypeDef",
+    {
+        "ArchiveArn": str,
+        "ArchiveName": str,
+        "EventSourceArn": str,
+        "Description": str,
+        "EventPattern": str,
+        "State": ArchiveStateType,
+        "StateReason": str,
+        "RetentionDays": int,
+        "SizeBytes": int,
+        "EventCount": int,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeConnectionRequestRequestTypeDef = TypedDict(
     "DescribeConnectionRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -634,28 +741,60 @@
     "DescribeEventBusRequestRequestTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+DescribeEventBusResponseTypeDef = TypedDict(
+    "DescribeEventBusResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeEventSourceRequestRequestTypeDef = TypedDict(
     "DescribeEventSourceRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DescribeEventSourceResponseTypeDef = TypedDict(
+    "DescribeEventSourceResponseTypeDef",
+    {
+        "Arn": str,
+        "CreatedBy": str,
+        "CreationTime": datetime,
+        "ExpirationTime": datetime,
+        "Name": str,
+        "State": EventSourceStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePartnerEventSourceRequestRequestTypeDef = TypedDict(
     "DescribePartnerEventSourceRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DescribePartnerEventSourceResponseTypeDef = TypedDict(
+    "DescribePartnerEventSourceResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeReplayRequestRequestTypeDef = TypedDict(
     "DescribeReplayRequestRequestTypeDef",
     {
         "ReplayName": str,
     },
 )
 
@@ -693,14 +832,31 @@
 )
 
 class DescribeRuleRequestRequestTypeDef(
     _RequiredDescribeRuleRequestRequestTypeDef, _OptionalDescribeRuleRequestRequestTypeDef
 ):
     pass
 
+DescribeRuleResponseTypeDef = TypedDict(
+    "DescribeRuleResponseTypeDef",
+    {
+        "Name": str,
+        "Arn": str,
+        "EventPattern": str,
+        "ScheduleExpression": str,
+        "State": RuleStateType,
+        "Description": str,
+        "RoleArn": str,
+        "ManagedBy": str,
+        "EventBusName": str,
+        "CreatedBy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisableRuleRequestRequestTypeDef = TypedDict(
     "_RequiredDisableRuleRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalDisableRuleRequestRequestTypeDef = TypedDict(
@@ -730,14 +886,21 @@
     {
         "type": PlacementStrategyTypeType,
         "field": str,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEnableRuleRequestRequestTypeDef = TypedDict(
     "_RequiredEnableRuleRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalEnableRuleRequestRequestTypeDef = TypedDict(
@@ -975,24 +1138,35 @@
         "EventLastReplayedTime": datetime,
         "ReplayStartTime": datetime,
         "ReplayEndTime": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
+    "_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TargetArn": str,
+    },
+)
+_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
+    "_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
+    {
+        "EventBusName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef(
+    _RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
+    _OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
+):
+    pass
+
 _RequiredListRuleNamesByTargetRequestRequestTypeDef = TypedDict(
     "_RequiredListRuleNamesByTargetRequestRequestTypeDef",
     {
         "TargetArn": str,
     },
 )
 _OptionalListRuleNamesByTargetRequestRequestTypeDef = TypedDict(
@@ -1007,14 +1181,33 @@
 
 class ListRuleNamesByTargetRequestRequestTypeDef(
     _RequiredListRuleNamesByTargetRequestRequestTypeDef,
     _OptionalListRuleNamesByTargetRequestRequestTypeDef,
 ):
     pass
 
+ListRuleNamesByTargetResponseTypeDef = TypedDict(
+    "ListRuleNamesByTargetResponseTypeDef",
+    {
+        "RuleNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListRulesRequestListRulesPaginateTypeDef = TypedDict(
+    "ListRulesRequestListRulesPaginateTypeDef",
+    {
+        "NamePrefix": str,
+        "EventBusName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRulesRequestRequestTypeDef = TypedDict(
     "ListRulesRequestRequestTypeDef",
     {
         "NamePrefix": str,
         "EventBusName": str,
         "NextToken": str,
         "Limit": int,
@@ -1041,14 +1234,35 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
+    "_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
+    {
+        "Rule": str,
+    },
+)
+_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
+    "_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
+    {
+        "EventBusName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef(
+    _RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
+    _OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
+):
+    pass
+
 _RequiredListTargetsByRuleRequestRequestTypeDef = TypedDict(
     "_RequiredListTargetsByRuleRequestRequestTypeDef",
     {
         "Rule": str,
     },
 )
 _OptionalListTargetsByRuleRequestRequestTypeDef = TypedDict(
@@ -1062,14 +1276,24 @@
 )
 
 class ListTargetsByRuleRequestRequestTypeDef(
     _RequiredListTargetsByRuleRequestRequestTypeDef, _OptionalListTargetsByRuleRequestRequestTypeDef
 ):
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
+
 PutEventsRequestEntryTypeDef = TypedDict(
     "PutEventsRequestEntryTypeDef",
     {
         "Time": Union[datetime, str],
         "Source": str,
         "Resources": Sequence[str],
         "DetailType": str,
@@ -1108,38 +1332,47 @@
         "EventId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+PutRuleResponseTypeDef = TypedDict(
+    "PutRuleResponseTypeDef",
+    {
+        "RuleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutTargetsResultEntryTypeDef = TypedDict(
     "PutTargetsResultEntryTypeDef",
     {
         "TargetId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
 _RequiredRedshiftDataParametersTypeDef = TypedDict(
     "_RequiredRedshiftDataParametersTypeDef",
     {
         "Database": str,
-        "Sql": str,
     },
 )
 _OptionalRedshiftDataParametersTypeDef = TypedDict(
     "_OptionalRedshiftDataParametersTypeDef",
     {
         "SecretManagerArn": str,
         "DbUser": str,
+        "Sql": str,
         "StatementName": str,
         "WithEvent": bool,
+        "Sqls": List[str],
     },
     total=False,
 )
 
 class RedshiftDataParametersTypeDef(
     _RequiredRedshiftDataParametersTypeDef, _OptionalRedshiftDataParametersTypeDef
 ):
@@ -1182,14 +1415,25 @@
         "TargetId": str,
         "ErrorCode": str,
         "ErrorMessage": str,
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
 RetryPolicyTypeDef = TypedDict(
     "RetryPolicyTypeDef",
     {
         "MaximumRetryAttempts": int,
         "MaximumEventAgeInSeconds": int,
     },
     total=False,
@@ -1215,22 +1459,41 @@
     "SqsParametersTypeDef",
     {
         "MessageGroupId": str,
     },
     total=False,
 )
 
+StartReplayResponseTypeDef = TypedDict(
+    "StartReplayResponseTypeDef",
+    {
+        "ReplayArn": str,
+        "State": ReplayStateType,
+        "StateReason": str,
+        "ReplayStartTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TestEventPatternRequestRequestTypeDef = TypedDict(
     "TestEventPatternRequestRequestTypeDef",
     {
         "EventPattern": str,
         "Event": str,
     },
 )
 
+TestEventPatternResponseTypeDef = TypedDict(
+    "TestEventPatternResponseTypeDef",
+    {
+        "Result": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
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
@@ -1255,14 +1518,25 @@
 
 class UpdateApiDestinationRequestRequestTypeDef(
     _RequiredUpdateApiDestinationRequestRequestTypeDef,
     _OptionalUpdateApiDestinationRequestRequestTypeDef,
 ):
     pass
 
+UpdateApiDestinationResponseTypeDef = TypedDict(
+    "UpdateApiDestinationResponseTypeDef",
+    {
+        "ApiDestinationArn": str,
+        "ApiDestinationState": ApiDestinationStateType,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateArchiveRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateArchiveRequestRequestTypeDef",
     {
         "ArchiveName": str,
     },
 )
 _OptionalUpdateArchiveRequestRequestTypeDef = TypedDict(
@@ -1276,14 +1550,25 @@
 )
 
 class UpdateArchiveRequestRequestTypeDef(
     _RequiredUpdateArchiveRequestRequestTypeDef, _OptionalUpdateArchiveRequestRequestTypeDef
 ):
     pass
 
+UpdateArchiveResponseTypeDef = TypedDict(
+    "UpdateArchiveResponseTypeDef",
+    {
+        "ArchiveArn": str,
+        "State": ArchiveStateType,
+        "StateReason": str,
+        "CreationTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateConnectionApiKeyAuthRequestParametersTypeDef = TypedDict(
     "UpdateConnectionApiKeyAuthRequestParametersTypeDef",
     {
         "ApiKeyName": str,
         "ApiKeyValue": str,
     },
     total=False,
@@ -1303,302 +1588,70 @@
     {
         "ClientID": str,
         "ClientSecret": str,
     },
     total=False,
 )
 
-NetworkConfigurationTypeDef = TypedDict(
-    "NetworkConfigurationTypeDef",
-    {
-        "awsvpcConfiguration": AwsVpcConfigurationTypeDef,
-    },
-    total=False,
-)
-
-_RequiredBatchParametersTypeDef = TypedDict(
-    "_RequiredBatchParametersTypeDef",
-    {
-        "JobDefinition": str,
-        "JobName": str,
-    },
-)
-_OptionalBatchParametersTypeDef = TypedDict(
-    "_OptionalBatchParametersTypeDef",
-    {
-        "ArrayProperties": BatchArrayPropertiesTypeDef,
-        "RetryStrategy": BatchRetryStrategyTypeDef,
-    },
-    total=False,
-)
-
-class BatchParametersTypeDef(_RequiredBatchParametersTypeDef, _OptionalBatchParametersTypeDef):
-    pass
-
-CancelReplayResponseTypeDef = TypedDict(
-    "CancelReplayResponseTypeDef",
-    {
-        "ReplayArn": str,
-        "State": ReplayStateType,
-        "StateReason": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApiDestinationResponseTypeDef = TypedDict(
-    "CreateApiDestinationResponseTypeDef",
-    {
-        "ApiDestinationArn": str,
-        "ApiDestinationState": ApiDestinationStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateArchiveResponseTypeDef = TypedDict(
-    "CreateArchiveResponseTypeDef",
-    {
-        "ArchiveArn": str,
-        "State": ArchiveStateType,
-        "StateReason": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateConnectionResponseTypeDef = TypedDict(
-    "CreateConnectionResponseTypeDef",
-    {
-        "ConnectionArn": str,
-        "ConnectionState": ConnectionStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEventBusResponseTypeDef = TypedDict(
-    "CreateEventBusResponseTypeDef",
-    {
-        "EventBusArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePartnerEventSourceResponseTypeDef = TypedDict(
-    "CreatePartnerEventSourceResponseTypeDef",
-    {
-        "EventSourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeauthorizeConnectionResponseTypeDef = TypedDict(
-    "DeauthorizeConnectionResponseTypeDef",
-    {
-        "ConnectionArn": str,
-        "ConnectionState": ConnectionStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteConnectionResponseTypeDef = TypedDict(
-    "DeleteConnectionResponseTypeDef",
+UpdateConnectionResponseTypeDef = TypedDict(
+    "UpdateConnectionResponseTypeDef",
     {
         "ConnectionArn": str,
         "ConnectionState": ConnectionStateType,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
         "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApiDestinationResponseTypeDef = TypedDict(
-    "DescribeApiDestinationResponseTypeDef",
-    {
-        "ApiDestinationArn": str,
-        "Name": str,
-        "Description": str,
-        "ApiDestinationState": ApiDestinationStateType,
-        "ConnectionArn": str,
-        "InvocationEndpoint": str,
-        "HttpMethod": ApiDestinationHttpMethodType,
-        "InvocationRateLimitPerSecond": int,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeArchiveResponseTypeDef = TypedDict(
-    "DescribeArchiveResponseTypeDef",
-    {
-        "ArchiveArn": str,
-        "ArchiveName": str,
-        "EventSourceArn": str,
-        "Description": str,
-        "EventPattern": str,
-        "State": ArchiveStateType,
-        "StateReason": str,
-        "RetentionDays": int,
-        "SizeBytes": int,
-        "EventCount": int,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEventBusResponseTypeDef = TypedDict(
-    "DescribeEventBusResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeEventSourceResponseTypeDef = TypedDict(
-    "DescribeEventSourceResponseTypeDef",
-    {
-        "Arn": str,
-        "CreatedBy": str,
-        "CreationTime": datetime,
-        "ExpirationTime": datetime,
-        "Name": str,
-        "State": EventSourceStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePartnerEventSourceResponseTypeDef = TypedDict(
-    "DescribePartnerEventSourceResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRuleResponseTypeDef = TypedDict(
-    "DescribeRuleResponseTypeDef",
-    {
-        "Name": str,
-        "Arn": str,
-        "EventPattern": str,
-        "ScheduleExpression": str,
-        "State": RuleStateType,
-        "Description": str,
-        "RoleArn": str,
-        "ManagedBy": str,
-        "EventBusName": str,
-        "CreatedBy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApiDestinationsResponseTypeDef = TypedDict(
     "ListApiDestinationsResponseTypeDef",
     {
         "ApiDestinations": List[ApiDestinationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListArchivesResponseTypeDef = TypedDict(
     "ListArchivesResponseTypeDef",
     {
         "Archives": List[ArchiveTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRuleNamesByTargetResponseTypeDef = TypedDict(
-    "ListRuleNamesByTargetResponseTypeDef",
-    {
-        "RuleNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutRuleResponseTypeDef = TypedDict(
-    "PutRuleResponseTypeDef",
-    {
-        "RuleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartReplayResponseTypeDef = TypedDict(
-    "StartReplayResponseTypeDef",
-    {
-        "ReplayArn": str,
-        "State": ReplayStateType,
-        "StateReason": str,
-        "ReplayStartTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-TestEventPatternResponseTypeDef = TypedDict(
-    "TestEventPatternResponseTypeDef",
+NetworkConfigurationTypeDef = TypedDict(
+    "NetworkConfigurationTypeDef",
     {
-        "Result": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "awsvpcConfiguration": AwsVpcConfigurationTypeDef,
     },
+    total=False,
 )
 
-UpdateApiDestinationResponseTypeDef = TypedDict(
-    "UpdateApiDestinationResponseTypeDef",
+_RequiredBatchParametersTypeDef = TypedDict(
+    "_RequiredBatchParametersTypeDef",
     {
-        "ApiDestinationArn": str,
-        "ApiDestinationState": ApiDestinationStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobDefinition": str,
+        "JobName": str,
     },
 )
-
-UpdateArchiveResponseTypeDef = TypedDict(
-    "UpdateArchiveResponseTypeDef",
+_OptionalBatchParametersTypeDef = TypedDict(
+    "_OptionalBatchParametersTypeDef",
     {
-        "ArchiveArn": str,
-        "State": ArchiveStateType,
-        "StateReason": str,
-        "CreationTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ArrayProperties": BatchArrayPropertiesTypeDef,
+        "RetryStrategy": BatchRetryStrategyTypeDef,
     },
+    total=False,
 )
 
-UpdateConnectionResponseTypeDef = TypedDict(
-    "UpdateConnectionResponseTypeDef",
-    {
-        "ConnectionArn": str,
-        "ConnectionState": ConnectionStateType,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class BatchParametersTypeDef(_RequiredBatchParametersTypeDef, _OptionalBatchParametersTypeDef):
+    pass
 
 PutPermissionRequestRequestTypeDef = TypedDict(
     "PutPermissionRequestRequestTypeDef",
     {
         "EventBusName": str,
         "Action": str,
         "Principal": str,
@@ -1620,15 +1673,15 @@
 )
 
 ListConnectionsResponseTypeDef = TypedDict(
     "ListConnectionsResponseTypeDef",
     {
         "Connections": List[ConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEventBusRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEventBusRequestRequestTypeDef",
     {
         "Name": str,
@@ -1648,15 +1701,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutRuleRequestRequestTypeDef = TypedDict(
     "_RequiredPutRuleRequestRequestTypeDef",
     {
         "Name": str,
@@ -1700,15 +1753,15 @@
         "EventSourceArn": str,
         "Destination": ReplayDestinationTypeDef,
         "EventStartTime": datetime,
         "EventEndTime": datetime,
         "EventLastReplayedTime": datetime,
         "ReplayStartTime": datetime,
         "ReplayEndTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartReplayRequestRequestTypeDef = TypedDict(
     "_RequiredStartReplayRequestRequestTypeDef",
     {
         "ReplayName": str,
@@ -1732,24 +1785,24 @@
     pass
 
 ListEventBusesResponseTypeDef = TypedDict(
     "ListEventBusesResponseTypeDef",
     {
         "EventBuses": List[EventBusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventSourcesResponseTypeDef = TypedDict(
     "ListEventSourcesResponseTypeDef",
     {
         "EventSources": List[EventSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailoverConfigTypeDef = TypedDict(
     "FailoverConfigTypeDef",
     {
         "Primary": PrimaryTypeDef,
@@ -1758,94 +1811,42 @@
 )
 
 ListPartnerEventSourceAccountsResponseTypeDef = TypedDict(
     "ListPartnerEventSourceAccountsResponseTypeDef",
     {
         "PartnerEventSourceAccounts": List[PartnerEventSourceAccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPartnerEventSourcesResponseTypeDef = TypedDict(
     "ListPartnerEventSourcesResponseTypeDef",
     {
         "PartnerEventSources": List[PartnerEventSourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReplaysResponseTypeDef = TypedDict(
     "ListReplaysResponseTypeDef",
     {
         "Replays": List[ReplayTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
-    "_RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
-    {
-        "TargetArn": str,
-    },
-)
-_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef = TypedDict(
-    "_OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef",
-    {
-        "EventBusName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef(
-    _RequiredListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
-    _OptionalListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
-):
-    pass
-
-ListRulesRequestListRulesPaginateTypeDef = TypedDict(
-    "ListRulesRequestListRulesPaginateTypeDef",
-    {
-        "NamePrefix": str,
-        "EventBusName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
-    "_RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
-    {
-        "Rule": str,
-    },
-)
-_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef = TypedDict(
-    "_OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef",
-    {
-        "EventBusName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef(
-    _RequiredListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
-    _OptionalListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
-):
-    pass
-
 ListRulesResponseTypeDef = TypedDict(
     "ListRulesResponseTypeDef",
     {
         "Rules": List[RuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutEventsRequestRequestTypeDef = TypedDict(
     "_RequiredPutEventsRequestRequestTypeDef",
     {
         "Entries": Sequence[PutEventsRequestEntryTypeDef],
@@ -1865,15 +1866,15 @@
     pass
 
 PutEventsResponseTypeDef = TypedDict(
     "PutEventsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "Entries": List[PutEventsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPartnerEventsRequestRequestTypeDef = TypedDict(
     "PutPartnerEventsRequestRequestTypeDef",
     {
         "Entries": Sequence[PutPartnerEventsRequestEntryTypeDef],
@@ -1881,33 +1882,33 @@
 )
 
 PutPartnerEventsResponseTypeDef = TypedDict(
     "PutPartnerEventsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "Entries": List[PutPartnerEventsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutTargetsResponseTypeDef = TypedDict(
     "PutTargetsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "FailedEntries": List[PutTargetsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveTargetsResponseTypeDef = TypedDict(
     "RemoveTargetsResponseTypeDef",
     {
         "FailedEntryCount": int,
         "FailedEntries": List[RemoveTargetsResultEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RunCommandParametersTypeDef = TypedDict(
     "RunCommandParametersTypeDef",
     {
         "RunCommandTargets": List[RunCommandTargetTypeDef],
@@ -2095,15 +2096,15 @@
         "Name": str,
         "Arn": str,
         "RoutingConfig": RoutingConfigTypeDef,
         "ReplicationConfig": ReplicationConfigTypeDef,
         "EventBuses": List[EndpointEventBusTypeDef],
         "RoleArn": str,
         "State": EndpointStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointResponseTypeDef = TypedDict(
     "DescribeEndpointResponseTypeDef",
     {
         "Name": str,
@@ -2115,15 +2116,15 @@
         "RoleArn": str,
         "EndpointId": str,
         "EndpointUrl": str,
         "State": EndpointStateType,
         "StateReason": str,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointTypeDef = TypedDict(
     "EndpointTypeDef",
     {
         "Name": str,
@@ -2174,24 +2175,24 @@
         "RoutingConfig": RoutingConfigTypeDef,
         "ReplicationConfig": ReplicationConfigTypeDef,
         "EventBuses": List[EndpointEventBusTypeDef],
         "RoleArn": str,
         "EndpointId": str,
         "EndpointUrl": str,
         "State": EndpointStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetsByRuleResponseTypeDef = TypedDict(
     "ListTargetsByRuleResponseTypeDef",
     {
         "Targets": List[TargetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutTargetsRequestRequestTypeDef = TypedDict(
     "_RequiredPutTargetsRequestRequestTypeDef",
     {
         "Rule": str,
@@ -2221,15 +2222,15 @@
         "StateReason": str,
         "AuthorizationType": ConnectionAuthorizationTypeType,
         "SecretArn": str,
         "AuthParameters": ConnectionAuthResponseParametersTypeDef,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
         "LastAuthorizedTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateConnectionRequestRequestTypeDef",
     {
         "Name": str,
@@ -2272,10 +2273,10 @@
     pass
 
 ListEndpointsResponseTypeDef = TypedDict(
     "ListEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/PKG-INFO` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-events
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.EventBridge 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.EventBridge 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-events"></a>
 
 # types-aiobotocore-events
 
 [![PyPI - types-aiobotocore-events](https://img.shields.io/pypi/v/types-aiobotocore-events.svg?color=blue)](https://pypi.org/project/types-aiobotocore-events)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-events.svg?color=blue)](https://pypi.org/project/types-aiobotocore-events)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-events?color=blue)](https://pypistats.org/packages/types-aiobotocore-events)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.EventBridge 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge)
+[aiobotocore.EventBridge 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/events.html#EventBridge)
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
 [types-aiobotocore-events docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_events/).
 
 See how it helps to find and fix potential bugs:
 
@@ -348,56 +348,70 @@
     ActivateEventSourceRequestRequestTypeDef,
     ApiDestinationTypeDef,
     ArchiveTypeDef,
     AwsVpcConfigurationTypeDef,
     BatchArrayPropertiesTypeDef,
     BatchRetryStrategyTypeDef,
     CancelReplayRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelReplayResponseTypeDef,
     CapacityProviderStrategyItemTypeDef,
     ConditionTypeDef,
     ConnectionApiKeyAuthResponseParametersTypeDef,
     ConnectionBasicAuthResponseParametersTypeDef,
     ConnectionBodyParameterTypeDef,
     ConnectionHeaderParameterTypeDef,
     ConnectionQueryStringParameterTypeDef,
     ConnectionOAuthClientResponseParametersTypeDef,
     ConnectionTypeDef,
     CreateApiDestinationRequestRequestTypeDef,
+    CreateApiDestinationResponseTypeDef,
     CreateArchiveRequestRequestTypeDef,
+    CreateArchiveResponseTypeDef,
     CreateConnectionApiKeyAuthRequestParametersTypeDef,
     CreateConnectionBasicAuthRequestParametersTypeDef,
     CreateConnectionOAuthClientRequestParametersTypeDef,
+    CreateConnectionResponseTypeDef,
     EndpointEventBusTypeDef,
     ReplicationConfigTypeDef,
     TagTypeDef,
+    CreateEventBusResponseTypeDef,
     CreatePartnerEventSourceRequestRequestTypeDef,
+    CreatePartnerEventSourceResponseTypeDef,
     DeactivateEventSourceRequestRequestTypeDef,
     DeadLetterConfigTypeDef,
     DeauthorizeConnectionRequestRequestTypeDef,
+    DeauthorizeConnectionResponseTypeDef,
     DeleteApiDestinationRequestRequestTypeDef,
     DeleteArchiveRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
+    DeleteConnectionResponseTypeDef,
     DeleteEndpointRequestRequestTypeDef,
     DeleteEventBusRequestRequestTypeDef,
     DeletePartnerEventSourceRequestRequestTypeDef,
     DeleteRuleRequestRequestTypeDef,
     DescribeApiDestinationRequestRequestTypeDef,
+    DescribeApiDestinationResponseTypeDef,
     DescribeArchiveRequestRequestTypeDef,
+    DescribeArchiveResponseTypeDef,
     DescribeConnectionRequestRequestTypeDef,
     DescribeEndpointRequestRequestTypeDef,
     DescribeEventBusRequestRequestTypeDef,
+    DescribeEventBusResponseTypeDef,
     DescribeEventSourceRequestRequestTypeDef,
+    DescribeEventSourceResponseTypeDef,
     DescribePartnerEventSourceRequestRequestTypeDef,
+    DescribePartnerEventSourceResponseTypeDef,
     DescribeReplayRequestRequestTypeDef,
     ReplayDestinationTypeDef,
     DescribeRuleRequestRequestTypeDef,
+    DescribeRuleResponseTypeDef,
     DisableRuleRequestRequestTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableRuleRequestRequestTypeDef,
     EventBusTypeDef,
     EventSourceTypeDef,
     PrimaryTypeDef,
     SecondaryTypeDef,
     HttpParametersTypeDef,
     InputTransformerTypeDef,
@@ -410,66 +424,55 @@
     ListEventSourcesRequestRequestTypeDef,
     ListPartnerEventSourceAccountsRequestRequestTypeDef,
     PartnerEventSourceAccountTypeDef,
     ListPartnerEventSourcesRequestRequestTypeDef,
     PartnerEventSourceTypeDef,
     ListReplaysRequestRequestTypeDef,
     ReplayTypeDef,
-    PaginatorConfigTypeDef,
+    ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
     ListRuleNamesByTargetRequestRequestTypeDef,
+    ListRuleNamesByTargetResponseTypeDef,
+    ListRulesRequestListRulesPaginateTypeDef,
     ListRulesRequestRequestTypeDef,
     RuleTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
     ListTargetsByRuleRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutEventsRequestEntryTypeDef,
     PutEventsResultEntryTypeDef,
     PutPartnerEventsRequestEntryTypeDef,
     PutPartnerEventsResultEntryTypeDef,
+    PutRuleResponseTypeDef,
     PutTargetsResultEntryTypeDef,
     RedshiftDataParametersTypeDef,
     RemovePermissionRequestRequestTypeDef,
     RemoveTargetsRequestRequestTypeDef,
     RemoveTargetsResultEntryTypeDef,
+    ResponseMetadataTypeDef,
     RetryPolicyTypeDef,
     RunCommandTargetTypeDef,
     SageMakerPipelineParameterTypeDef,
     SqsParametersTypeDef,
+    StartReplayResponseTypeDef,
     TestEventPatternRequestRequestTypeDef,
+    TestEventPatternResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiDestinationRequestRequestTypeDef,
+    UpdateApiDestinationResponseTypeDef,
     UpdateArchiveRequestRequestTypeDef,
+    UpdateArchiveResponseTypeDef,
     UpdateConnectionApiKeyAuthRequestParametersTypeDef,
     UpdateConnectionBasicAuthRequestParametersTypeDef,
     UpdateConnectionOAuthClientRequestParametersTypeDef,
-    NetworkConfigurationTypeDef,
-    BatchParametersTypeDef,
-    CancelReplayResponseTypeDef,
-    CreateApiDestinationResponseTypeDef,
-    CreateArchiveResponseTypeDef,
-    CreateConnectionResponseTypeDef,
-    CreateEventBusResponseTypeDef,
-    CreatePartnerEventSourceResponseTypeDef,
-    DeauthorizeConnectionResponseTypeDef,
-    DeleteConnectionResponseTypeDef,
-    DescribeApiDestinationResponseTypeDef,
-    DescribeArchiveResponseTypeDef,
-    DescribeEventBusResponseTypeDef,
-    DescribeEventSourceResponseTypeDef,
-    DescribePartnerEventSourceResponseTypeDef,
-    DescribeRuleResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    UpdateConnectionResponseTypeDef,
     ListApiDestinationsResponseTypeDef,
     ListArchivesResponseTypeDef,
-    ListRuleNamesByTargetResponseTypeDef,
-    PutRuleResponseTypeDef,
-    StartReplayResponseTypeDef,
-    TestEventPatternResponseTypeDef,
-    UpdateApiDestinationResponseTypeDef,
-    UpdateArchiveResponseTypeDef,
-    UpdateConnectionResponseTypeDef,
+    NetworkConfigurationTypeDef,
+    BatchParametersTypeDef,
     PutPermissionRequestRequestTypeDef,
     ConnectionHttpParametersTypeDef,
     ListConnectionsResponseTypeDef,
     CreateEventBusRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutRuleRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
@@ -477,17 +480,14 @@
     StartReplayRequestRequestTypeDef,
     ListEventBusesResponseTypeDef,
     ListEventSourcesResponseTypeDef,
     FailoverConfigTypeDef,
     ListPartnerEventSourceAccountsResponseTypeDef,
     ListPartnerEventSourcesResponseTypeDef,
     ListReplaysResponseTypeDef,
-    ListRuleNamesByTargetRequestListRuleNamesByTargetPaginateTypeDef,
-    ListRulesRequestListRulesPaginateTypeDef,
-    ListTargetsByRuleRequestListTargetsByRulePaginateTypeDef,
     ListRulesResponseTypeDef,
     PutEventsRequestRequestTypeDef,
     PutEventsResponseTypeDef,
     PutPartnerEventsRequestRequestTypeDef,
     PutPartnerEventsResponseTypeDef,
     PutTargetsResponseTypeDef,
     RemoveTargetsResponseTypeDef,
@@ -524,43 +524,43 @@
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

### Comparing `types-aiobotocore-events-2.5.0.post1/types_aiobotocore_events.egg-info/SOURCES.txt` & `types-aiobotocore-events-2.5.1/types_aiobotocore_events.egg-info/SOURCES.txt`

 * *Files identical despite different names*

