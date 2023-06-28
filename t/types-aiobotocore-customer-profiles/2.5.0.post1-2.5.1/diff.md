# Comparing `tmp/types-aiobotocore-customer-profiles-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-customer-profiles-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-customer-profiles-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:28 2023, max compression
+gzip compressed data, was "types-aiobotocore-customer-profiles-2.5.1.tar", last modified: Wed Jun 28 01:43:20 2023, max compression
```

## Comparing `types-aiobotocore-customer-profiles-2.5.0.post1.tar` & `types-aiobotocore-customer-profiles-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:28.491109 types-aiobotocore-customer-profiles-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17678 2023-03-11 12:26:28.491109 types-aiobotocore-customer-profiles-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16068 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:28.491109 types-aiobotocore-customer-profiles-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:28.487110 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/
--rw-r--r--   0 runner    (1001) docker     (123)      517 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      516 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      981 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    32523 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    32476 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11787 2023-03-11 12:12:05.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11785 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    49343 2023-03-11 12:12:07.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    49275 2023-03-11 12:12:06.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:04.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:28.491109 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17678 2023-03-11 12:26:28.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      904 2023-03-11 12:26:28.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:28.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:28.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:28.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:28.000000 types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.414120 types-aiobotocore-customer-profiles-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20088 2023-06-28 01:43:20.414120 types-aiobotocore-customer-profiles-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18484 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:20.414120 types-aiobotocore-customer-profiles-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2203 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.410120 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/
+-rw-r--r--   0 runner    (1001) docker     (123)      736 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      735 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      969 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41040 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40981 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12679 2023-06-28 01:28:44.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12677 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2150 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2147 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    63039 2023-06-28 01:28:46.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    62951 2023-06-28 01:28:45.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:43.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:20.414120 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20088 2023-06-28 01:43:20.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 01:43:20.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:20.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:20.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:20.000000 types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/LICENSE` & `types-aiobotocore-customer-profiles-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/PKG-INFO` & `types-aiobotocore-customer-profiles-2.5.1/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-customer-profiles
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CustomerProfiles 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CustomerProfiles 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-customer-profiles"></a>
 
 # types-aiobotocore-customer-profiles
 
 [![PyPI - types-aiobotocore-customer-profiles](https://img.shields.io/pypi/v/types-aiobotocore-customer-profiles.svg?color=blue)](https://pypi.org/project/types-aiobotocore-customer-profiles)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-customer-profiles.svg?color=blue)](https://pypi.org/project/types-aiobotocore-customer-profiles)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-customer-profiles?color=blue)](https://pypistats.org/packages/types-aiobotocore-customer-profiles)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CustomerProfiles 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles)
+[aiobotocore.CustomerProfiles 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles)
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
 [types-aiobotocore-customer-profiles docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/).
 
 See how it helps to find and fix potential bugs:
 
@@ -72,14 +72,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -260,46 +261,77 @@
 
 session = get_session()
 async with session.create_client("customer-profiles") as client:
     client: CustomerProfilesClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_customer_profiles.paginator` module contains type
+annotations for all paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_customer_profiles import CustomerProfilesClient
+from types_aiobotocore_customer_profiles.paginator import ListEventStreamsPaginator
+
+session = get_session()
+async with session.create_client("customer-profiles") as client:
+    client: CustomerProfilesClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_event_streams_paginator: ListEventStreamsPaginator = client.get_paginator(
+        "list_event_streams"
+    )
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_customer_profiles.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_customer_profiles.literals import (
     ConflictResolvingModelType,
     DataPullModeType,
+    EventStreamDestinationStatusType,
+    EventStreamStateType,
     FieldContentTypeType,
     GenderType,
     IdentityResolutionJobStatusType,
     JobScheduleDayOfTheWeekType,
+    ListEventStreamsPaginatorName,
     MarketoConnectorOperatorType,
     OperatorPropertiesKeysType,
+    OperatorType,
     PartyTypeType,
     S3ConnectorOperatorType,
     SalesforceConnectorOperatorType,
     ServiceNowConnectorOperatorType,
     SourceConnectorTypeType,
     StandardIdentifierType,
+    StatisticType,
     StatusType,
     TaskTypeType,
     TriggerTypeType,
+    UnitType,
     WorkflowTypeType,
     ZendeskConnectorOperatorType,
     logicalOperatorType,
     CustomerProfilesServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
     RegionName,
 )
 
 
 def check_value(value: ConflictResolvingModelType) -> bool:
     ...
 ```
@@ -310,121 +342,153 @@
 
 `types_aiobotocore_customer_profiles.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_customer_profiles.type_defs import (
     AddProfileKeyRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddProfileKeyResponseTypeDef,
     AdditionalSearchKeyTypeDef,
     AddressTypeDef,
     BatchTypeDef,
     AppflowIntegrationWorkflowAttributesTypeDef,
     AppflowIntegrationWorkflowMetricsTypeDef,
     AppflowIntegrationWorkflowStepTypeDef,
+    AttributeItemTypeDef,
     ConflictResolutionTypeDef,
     ConsolidationTypeDef,
+    RangeTypeDef,
+    ThresholdTypeDef,
     ConnectorOperatorTypeDef,
+    CreateEventStreamRequestRequestTypeDef,
+    CreateEventStreamResponseTypeDef,
+    CreateIntegrationWorkflowResponseTypeDef,
+    CreateProfileResponseTypeDef,
+    DeleteCalculatedAttributeDefinitionRequestRequestTypeDef,
     DeleteDomainRequestRequestTypeDef,
+    DeleteDomainResponseTypeDef,
+    DeleteEventStreamRequestRequestTypeDef,
     DeleteIntegrationRequestRequestTypeDef,
+    DeleteIntegrationResponseTypeDef,
     DeleteProfileKeyRequestRequestTypeDef,
+    DeleteProfileKeyResponseTypeDef,
     DeleteProfileObjectRequestRequestTypeDef,
+    DeleteProfileObjectResponseTypeDef,
     DeleteProfileObjectTypeRequestRequestTypeDef,
+    DeleteProfileObjectTypeResponseTypeDef,
     DeleteProfileRequestRequestTypeDef,
+    DeleteProfileResponseTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    DestinationSummaryTypeDef,
     DomainStatsTypeDef,
+    EventStreamDestinationDetailsTypeDef,
     S3ExportingConfigTypeDef,
     S3ExportingLocationTypeDef,
     FieldSourceProfileIdsTypeDef,
     FoundByKeyValueTypeDef,
+    GetAutoMergingPreviewResponseTypeDef,
+    GetCalculatedAttributeDefinitionRequestRequestTypeDef,
+    GetCalculatedAttributeForProfileRequestRequestTypeDef,
+    GetCalculatedAttributeForProfileResponseTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetEventStreamRequestRequestTypeDef,
     GetIdentityResolutionJobRequestRequestTypeDef,
     JobStatsTypeDef,
     GetIntegrationRequestRequestTypeDef,
+    GetIntegrationResponseTypeDef,
     GetMatchesRequestRequestTypeDef,
     MatchItemTypeDef,
     GetProfileObjectTypeRequestRequestTypeDef,
     ObjectTypeFieldTypeDef,
     ObjectTypeKeyTypeDef,
     GetProfileObjectTypeTemplateRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     GetWorkflowStepsRequestRequestTypeDef,
     IncrementalPullConfigTypeDef,
     JobScheduleTypeDef,
     ListAccountIntegrationsRequestRequestTypeDef,
     ListIntegrationItemTypeDef,
+    ListCalculatedAttributeDefinitionItemTypeDef,
+    ListCalculatedAttributeDefinitionsRequestRequestTypeDef,
+    ListCalculatedAttributeForProfileItemTypeDef,
+    ListCalculatedAttributesForProfileRequestRequestTypeDef,
     ListDomainItemTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListEventStreamsRequestListEventStreamsPaginateTypeDef,
+    ListEventStreamsRequestRequestTypeDef,
     ListIdentityResolutionJobsRequestRequestTypeDef,
     ListIntegrationsRequestRequestTypeDef,
     ListProfileObjectTypeItemTypeDef,
     ListProfileObjectTypeTemplateItemTypeDef,
     ListProfileObjectTypeTemplatesRequestRequestTypeDef,
     ListProfileObjectTypesRequestRequestTypeDef,
     ListProfileObjectsItemTypeDef,
     ObjectFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWorkflowsItemTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     MarketoSourcePropertiesTypeDef,
+    MergeProfilesResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutIntegrationResponseTypeDef,
     PutProfileObjectRequestRequestTypeDef,
+    PutProfileObjectResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3SourcePropertiesTypeDef,
     SalesforceSourcePropertiesTypeDef,
     ScheduledTriggerPropertiesTypeDef,
     ServiceNowSourcePropertiesTypeDef,
     ZendeskSourcePropertiesTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAddressTypeDef,
-    AddProfileKeyResponseTypeDef,
-    CreateIntegrationWorkflowResponseTypeDef,
-    CreateProfileResponseTypeDef,
-    DeleteDomainResponseTypeDef,
-    DeleteIntegrationResponseTypeDef,
-    DeleteProfileKeyResponseTypeDef,
-    DeleteProfileObjectResponseTypeDef,
-    DeleteProfileObjectTypeResponseTypeDef,
-    DeleteProfileResponseTypeDef,
-    GetAutoMergingPreviewResponseTypeDef,
-    GetIntegrationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    MergeProfilesResponseTypeDef,
-    PutIntegrationResponseTypeDef,
-    PutProfileObjectResponseTypeDef,
     UpdateProfileResponseTypeDef,
     SearchProfilesRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     WorkflowAttributesTypeDef,
     WorkflowMetricsTypeDef,
     WorkflowStepItemTypeDef,
+    AttributeDetailsTypeDef,
     AutoMergingTypeDef,
     GetAutoMergingPreviewRequestRequestTypeDef,
+    ConditionsTypeDef,
     TaskTypeDef,
+    EventStreamSummaryTypeDef,
+    GetEventStreamResponseTypeDef,
     ExportingConfigTypeDef,
     ExportingLocationTypeDef,
     MergeProfilesRequestRequestTypeDef,
     ProfileTypeDef,
     GetMatchesResponseTypeDef,
     GetProfileObjectTypeResponseTypeDef,
     GetProfileObjectTypeTemplateResponseTypeDef,
     PutProfileObjectTypeRequestRequestTypeDef,
     PutProfileObjectTypeResponseTypeDef,
     ListAccountIntegrationsResponseTypeDef,
     ListIntegrationsResponseTypeDef,
+    ListCalculatedAttributeDefinitionsResponseTypeDef,
+    ListCalculatedAttributesForProfileResponseTypeDef,
     ListDomainsResponseTypeDef,
     ListProfileObjectTypesResponseTypeDef,
     ListProfileObjectTypeTemplatesResponseTypeDef,
     ListProfileObjectsResponseTypeDef,
     ListProfileObjectsRequestRequestTypeDef,
     ListWorkflowsResponseTypeDef,
     TriggerPropertiesTypeDef,
     SourceConnectorPropertiesTypeDef,
     UpdateProfileRequestRequestTypeDef,
     GetWorkflowResponseTypeDef,
     GetWorkflowStepsResponseTypeDef,
+    CreateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    CreateCalculatedAttributeDefinitionResponseTypeDef,
+    GetCalculatedAttributeDefinitionResponseTypeDef,
+    UpdateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    UpdateCalculatedAttributeDefinitionResponseTypeDef,
+    ListEventStreamsResponseTypeDef,
     MatchingRequestTypeDef,
     MatchingResponseTypeDef,
     GetIdentityResolutionJobResponseTypeDef,
     IdentityResolutionJobTypeDef,
     SearchProfilesResponseTypeDef,
     TriggerConfigTypeDef,
     SourceFlowConfigTypeDef,
@@ -449,43 +513,43 @@
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

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/README.md` & `types-aiobotocore-customer-profiles-2.5.1/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-customer-profiles"></a>
 
 # types-aiobotocore-customer-profiles
 
 [![PyPI - types-aiobotocore-customer-profiles](https://img.shields.io/pypi/v/types-aiobotocore-customer-profiles.svg?color=blue)](https://pypi.org/project/types-aiobotocore-customer-profiles)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-customer-profiles.svg?color=blue)](https://pypi.org/project/types-aiobotocore-customer-profiles)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-customer-profiles?color=blue)](https://pypistats.org/packages/types-aiobotocore-customer-profiles)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CustomerProfiles 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles)
+[aiobotocore.CustomerProfiles 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles)
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
 [types-aiobotocore-customer-profiles docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/).
 
 See how it helps to find and fix potential bugs:
 
@@ -39,14 +39,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -227,46 +228,77 @@
 
 session = get_session()
 async with session.create_client("customer-profiles") as client:
     client: CustomerProfilesClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_customer_profiles.paginator` module contains type
+annotations for all paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_customer_profiles import CustomerProfilesClient
+from types_aiobotocore_customer_profiles.paginator import ListEventStreamsPaginator
+
+session = get_session()
+async with session.create_client("customer-profiles") as client:
+    client: CustomerProfilesClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_event_streams_paginator: ListEventStreamsPaginator = client.get_paginator(
+        "list_event_streams"
+    )
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_customer_profiles.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_customer_profiles.literals import (
     ConflictResolvingModelType,
     DataPullModeType,
+    EventStreamDestinationStatusType,
+    EventStreamStateType,
     FieldContentTypeType,
     GenderType,
     IdentityResolutionJobStatusType,
     JobScheduleDayOfTheWeekType,
+    ListEventStreamsPaginatorName,
     MarketoConnectorOperatorType,
     OperatorPropertiesKeysType,
+    OperatorType,
     PartyTypeType,
     S3ConnectorOperatorType,
     SalesforceConnectorOperatorType,
     ServiceNowConnectorOperatorType,
     SourceConnectorTypeType,
     StandardIdentifierType,
+    StatisticType,
     StatusType,
     TaskTypeType,
     TriggerTypeType,
+    UnitType,
     WorkflowTypeType,
     ZendeskConnectorOperatorType,
     logicalOperatorType,
     CustomerProfilesServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
     RegionName,
 )
 
 
 def check_value(value: ConflictResolvingModelType) -> bool:
     ...
 ```
@@ -277,121 +309,153 @@
 
 `types_aiobotocore_customer_profiles.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_customer_profiles.type_defs import (
     AddProfileKeyRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddProfileKeyResponseTypeDef,
     AdditionalSearchKeyTypeDef,
     AddressTypeDef,
     BatchTypeDef,
     AppflowIntegrationWorkflowAttributesTypeDef,
     AppflowIntegrationWorkflowMetricsTypeDef,
     AppflowIntegrationWorkflowStepTypeDef,
+    AttributeItemTypeDef,
     ConflictResolutionTypeDef,
     ConsolidationTypeDef,
+    RangeTypeDef,
+    ThresholdTypeDef,
     ConnectorOperatorTypeDef,
+    CreateEventStreamRequestRequestTypeDef,
+    CreateEventStreamResponseTypeDef,
+    CreateIntegrationWorkflowResponseTypeDef,
+    CreateProfileResponseTypeDef,
+    DeleteCalculatedAttributeDefinitionRequestRequestTypeDef,
     DeleteDomainRequestRequestTypeDef,
+    DeleteDomainResponseTypeDef,
+    DeleteEventStreamRequestRequestTypeDef,
     DeleteIntegrationRequestRequestTypeDef,
+    DeleteIntegrationResponseTypeDef,
     DeleteProfileKeyRequestRequestTypeDef,
+    DeleteProfileKeyResponseTypeDef,
     DeleteProfileObjectRequestRequestTypeDef,
+    DeleteProfileObjectResponseTypeDef,
     DeleteProfileObjectTypeRequestRequestTypeDef,
+    DeleteProfileObjectTypeResponseTypeDef,
     DeleteProfileRequestRequestTypeDef,
+    DeleteProfileResponseTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    DestinationSummaryTypeDef,
     DomainStatsTypeDef,
+    EventStreamDestinationDetailsTypeDef,
     S3ExportingConfigTypeDef,
     S3ExportingLocationTypeDef,
     FieldSourceProfileIdsTypeDef,
     FoundByKeyValueTypeDef,
+    GetAutoMergingPreviewResponseTypeDef,
+    GetCalculatedAttributeDefinitionRequestRequestTypeDef,
+    GetCalculatedAttributeForProfileRequestRequestTypeDef,
+    GetCalculatedAttributeForProfileResponseTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetEventStreamRequestRequestTypeDef,
     GetIdentityResolutionJobRequestRequestTypeDef,
     JobStatsTypeDef,
     GetIntegrationRequestRequestTypeDef,
+    GetIntegrationResponseTypeDef,
     GetMatchesRequestRequestTypeDef,
     MatchItemTypeDef,
     GetProfileObjectTypeRequestRequestTypeDef,
     ObjectTypeFieldTypeDef,
     ObjectTypeKeyTypeDef,
     GetProfileObjectTypeTemplateRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     GetWorkflowStepsRequestRequestTypeDef,
     IncrementalPullConfigTypeDef,
     JobScheduleTypeDef,
     ListAccountIntegrationsRequestRequestTypeDef,
     ListIntegrationItemTypeDef,
+    ListCalculatedAttributeDefinitionItemTypeDef,
+    ListCalculatedAttributeDefinitionsRequestRequestTypeDef,
+    ListCalculatedAttributeForProfileItemTypeDef,
+    ListCalculatedAttributesForProfileRequestRequestTypeDef,
     ListDomainItemTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListEventStreamsRequestListEventStreamsPaginateTypeDef,
+    ListEventStreamsRequestRequestTypeDef,
     ListIdentityResolutionJobsRequestRequestTypeDef,
     ListIntegrationsRequestRequestTypeDef,
     ListProfileObjectTypeItemTypeDef,
     ListProfileObjectTypeTemplateItemTypeDef,
     ListProfileObjectTypeTemplatesRequestRequestTypeDef,
     ListProfileObjectTypesRequestRequestTypeDef,
     ListProfileObjectsItemTypeDef,
     ObjectFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWorkflowsItemTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     MarketoSourcePropertiesTypeDef,
+    MergeProfilesResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutIntegrationResponseTypeDef,
     PutProfileObjectRequestRequestTypeDef,
+    PutProfileObjectResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3SourcePropertiesTypeDef,
     SalesforceSourcePropertiesTypeDef,
     ScheduledTriggerPropertiesTypeDef,
     ServiceNowSourcePropertiesTypeDef,
     ZendeskSourcePropertiesTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAddressTypeDef,
-    AddProfileKeyResponseTypeDef,
-    CreateIntegrationWorkflowResponseTypeDef,
-    CreateProfileResponseTypeDef,
-    DeleteDomainResponseTypeDef,
-    DeleteIntegrationResponseTypeDef,
-    DeleteProfileKeyResponseTypeDef,
-    DeleteProfileObjectResponseTypeDef,
-    DeleteProfileObjectTypeResponseTypeDef,
-    DeleteProfileResponseTypeDef,
-    GetAutoMergingPreviewResponseTypeDef,
-    GetIntegrationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    MergeProfilesResponseTypeDef,
-    PutIntegrationResponseTypeDef,
-    PutProfileObjectResponseTypeDef,
     UpdateProfileResponseTypeDef,
     SearchProfilesRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     WorkflowAttributesTypeDef,
     WorkflowMetricsTypeDef,
     WorkflowStepItemTypeDef,
+    AttributeDetailsTypeDef,
     AutoMergingTypeDef,
     GetAutoMergingPreviewRequestRequestTypeDef,
+    ConditionsTypeDef,
     TaskTypeDef,
+    EventStreamSummaryTypeDef,
+    GetEventStreamResponseTypeDef,
     ExportingConfigTypeDef,
     ExportingLocationTypeDef,
     MergeProfilesRequestRequestTypeDef,
     ProfileTypeDef,
     GetMatchesResponseTypeDef,
     GetProfileObjectTypeResponseTypeDef,
     GetProfileObjectTypeTemplateResponseTypeDef,
     PutProfileObjectTypeRequestRequestTypeDef,
     PutProfileObjectTypeResponseTypeDef,
     ListAccountIntegrationsResponseTypeDef,
     ListIntegrationsResponseTypeDef,
+    ListCalculatedAttributeDefinitionsResponseTypeDef,
+    ListCalculatedAttributesForProfileResponseTypeDef,
     ListDomainsResponseTypeDef,
     ListProfileObjectTypesResponseTypeDef,
     ListProfileObjectTypeTemplatesResponseTypeDef,
     ListProfileObjectsResponseTypeDef,
     ListProfileObjectsRequestRequestTypeDef,
     ListWorkflowsResponseTypeDef,
     TriggerPropertiesTypeDef,
     SourceConnectorPropertiesTypeDef,
     UpdateProfileRequestRequestTypeDef,
     GetWorkflowResponseTypeDef,
     GetWorkflowStepsResponseTypeDef,
+    CreateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    CreateCalculatedAttributeDefinitionResponseTypeDef,
+    GetCalculatedAttributeDefinitionResponseTypeDef,
+    UpdateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    UpdateCalculatedAttributeDefinitionResponseTypeDef,
+    ListEventStreamsResponseTypeDef,
     MatchingRequestTypeDef,
     MatchingResponseTypeDef,
     GetIdentityResolutionJobResponseTypeDef,
     IdentityResolutionJobTypeDef,
     SearchProfilesResponseTypeDef,
     TriggerConfigTypeDef,
     SourceFlowConfigTypeDef,
@@ -416,43 +480,43 @@
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

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/setup.py` & `types-aiobotocore-customer-profiles-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-customer-profiles.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-customer-profiles",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_customer_profiles"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CustomerProfiles 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CustomerProfiles 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/"
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

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/__init__.py` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/__init__.py`

 * *Files 26% similar despite different names*

```diff
@@ -4,22 +4,26 @@
 Usage::
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_customer_profiles import (
         Client,
         CustomerProfilesClient,
+        ListEventStreamsPaginator,
     )
 
     session = get_session()
     async with session.create_client("customer-profiles") as client:
         client: CustomerProfilesClient
         ...
 
+
+    list_event_streams_paginator: ListEventStreamsPaginator = client.get_paginator("list_event_streams")
     ```
 """
 from .client import CustomerProfilesClient
+from .paginator import ListEventStreamsPaginator
 
 Client = CustomerProfilesClient
 
 
-__all__ = ("Client", "CustomerProfilesClient")
+__all__ = ("Client", "CustomerProfilesClient", "ListEventStreamsPaginator")
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/__init__.pyi` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/__init__.pyi`

 * *Files 26% similar despite different names*

```diff
@@ -4,21 +4,25 @@
 Usage::
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_customer_profiles import (
         Client,
         CustomerProfilesClient,
+        ListEventStreamsPaginator,
     )
 
     session = get_session()
     async with session.create_client("customer-profiles") as client:
         client: CustomerProfilesClient
         ...
 
+
+    list_event_streams_paginator: ListEventStreamsPaginator = client.get_paginator("list_event_streams")
     ```
 """
 from .client import CustomerProfilesClient
+from .paginator import ListEventStreamsPaginator
 
 Client = CustomerProfilesClient
 
-__all__ = ("Client", "CustomerProfilesClient")
+__all__ = ("Client", "CustomerProfilesClient", "ListEventStreamsPaginator")
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/__main__.py` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CustomerProfiles 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CustomerProfiles 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles\nOther"
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

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/client.py` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/client.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -17,44 +17,55 @@
 import sys
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import GenderType, PartyTypeType, StatusType, logicalOperatorType
+from .literals import GenderType, PartyTypeType, StatisticType, StatusType, logicalOperatorType
+from .paginator import ListEventStreamsPaginator
 from .type_defs import (
     AdditionalSearchKeyTypeDef,
     AddProfileKeyResponseTypeDef,
     AddressTypeDef,
+    AttributeDetailsTypeDef,
+    ConditionsTypeDef,
     ConflictResolutionTypeDef,
     ConsolidationTypeDef,
+    CreateCalculatedAttributeDefinitionResponseTypeDef,
     CreateDomainResponseTypeDef,
+    CreateEventStreamResponseTypeDef,
     CreateIntegrationWorkflowResponseTypeDef,
     CreateProfileResponseTypeDef,
     DeleteDomainResponseTypeDef,
     DeleteIntegrationResponseTypeDef,
     DeleteProfileKeyResponseTypeDef,
     DeleteProfileObjectResponseTypeDef,
     DeleteProfileObjectTypeResponseTypeDef,
     DeleteProfileResponseTypeDef,
     FieldSourceProfileIdsTypeDef,
     FlowDefinitionTypeDef,
     GetAutoMergingPreviewResponseTypeDef,
+    GetCalculatedAttributeDefinitionResponseTypeDef,
+    GetCalculatedAttributeForProfileResponseTypeDef,
     GetDomainResponseTypeDef,
+    GetEventStreamResponseTypeDef,
     GetIdentityResolutionJobResponseTypeDef,
     GetIntegrationResponseTypeDef,
     GetMatchesResponseTypeDef,
     GetProfileObjectTypeResponseTypeDef,
     GetProfileObjectTypeTemplateResponseTypeDef,
     GetWorkflowResponseTypeDef,
     GetWorkflowStepsResponseTypeDef,
     IntegrationConfigTypeDef,
     ListAccountIntegrationsResponseTypeDef,
+    ListCalculatedAttributeDefinitionsResponseTypeDef,
+    ListCalculatedAttributesForProfileResponseTypeDef,
     ListDomainsResponseTypeDef,
+    ListEventStreamsResponseTypeDef,
     ListIdentityResolutionJobsResponseTypeDef,
     ListIntegrationsResponseTypeDef,
     ListProfileObjectsResponseTypeDef,
     ListProfileObjectTypesResponseTypeDef,
     ListProfileObjectTypeTemplatesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListWorkflowsResponseTypeDef,
@@ -64,44 +75,41 @@
     ObjectTypeFieldTypeDef,
     ObjectTypeKeyTypeDef,
     PutIntegrationResponseTypeDef,
     PutProfileObjectResponseTypeDef,
     PutProfileObjectTypeResponseTypeDef,
     SearchProfilesResponseTypeDef,
     UpdateAddressTypeDef,
+    UpdateCalculatedAttributeDefinitionResponseTypeDef,
     UpdateDomainResponseTypeDef,
     UpdateProfileResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("CustomerProfilesClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
 
-
 class CustomerProfilesClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/)
     """
 
     meta: ClientMeta
@@ -110,42 +118,56 @@
     def exceptions(self) -> Exceptions:
         """
         CustomerProfilesClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#exceptions)
         """
-
     async def add_profile_key(
         self, *, ProfileId: str, KeyName: str, Values: Sequence[str], DomainName: str
     ) -> AddProfileKeyResponseTypeDef:
         """
         Associates a new key value with a specific profile, such as a Contact Record
         ContactId.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.add_profile_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#add_profile_key)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#close)
         """
+    async def create_calculated_attribute_definition(
+        self,
+        *,
+        DomainName: str,
+        CalculatedAttributeName: str,
+        AttributeDetails: AttributeDetailsTypeDef,
+        Statistic: StatisticType,
+        DisplayName: str = ...,
+        Description: str = ...,
+        Conditions: ConditionsTypeDef = ...,
+        Tags: Mapping[str, str] = ...
+    ) -> CreateCalculatedAttributeDefinitionResponseTypeDef:
+        """
+        Creates a new calculated attribute definition.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_calculated_attribute_definition)
+        """
     async def create_domain(
         self,
         *,
         DomainName: str,
         DefaultExpirationDays: int,
         DefaultEncryptionKey: str = ...,
         DeadLetterQueueUrl: str = ...,
@@ -155,15 +177,24 @@
         """
         Creates a domain, which is a container for all customer data, such as customer
         profile attributes, object types, profile keys, and encryption keys.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_domain)
         """
+    async def create_event_stream(
+        self, *, DomainName: str, Uri: str, EventStreamName: str, Tags: Mapping[str, str] = ...
+    ) -> CreateEventStreamResponseTypeDef:
+        """
+        Creates an event stream, which is a subscription to real-time events, such as
+        when profiles are created and updated through Amazon Connect Customer Profiles.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_event_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_event_stream)
+        """
     async def create_integration_workflow(
         self,
         *,
         DomainName: str,
         WorkflowType: Literal["APPFLOW_INTEGRATION"],
         IntegrationConfig: IntegrationConfigTypeDef,
         ObjectTypeName: str,
@@ -172,15 +203,14 @@
     ) -> CreateIntegrationWorkflowResponseTypeDef:
         """
         Creates an integration workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_integration_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_integration_workflow)
         """
-
     async def create_profile(
         self,
         *,
         DomainName: str,
         AccountNumber: str = ...,
         AdditionalInformation: str = ...,
         PartyType: PartyTypeType = ...,
@@ -207,97 +237,104 @@
     ) -> CreateProfileResponseTypeDef:
         """
         Creates a standard profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_profile)
         """
+    async def delete_calculated_attribute_definition(
+        self, *, DomainName: str, CalculatedAttributeName: str
+    ) -> Dict[str, Any]:
+        """
+        Deletes an existing calculated attribute definition.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_calculated_attribute_definition)
+        """
     async def delete_domain(self, *, DomainName: str) -> DeleteDomainResponseTypeDef:
         """
         Deletes a specific domain and all of its customer data, such as customer profile
         attributes and their related objects.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_domain)
         """
+    async def delete_event_stream(self, *, DomainName: str, EventStreamName: str) -> Dict[str, Any]:
+        """
+        Disables and deletes the specified event stream.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_event_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_event_stream)
+        """
     async def delete_integration(
         self, *, DomainName: str, Uri: str
     ) -> DeleteIntegrationResponseTypeDef:
         """
         Removes an integration from a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_integration)
         """
-
     async def delete_profile(
         self, *, ProfileId: str, DomainName: str
     ) -> DeleteProfileResponseTypeDef:
         """
         Deletes the standard customer profile and all data pertaining to the profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile)
         """
-
     async def delete_profile_key(
         self, *, ProfileId: str, KeyName: str, Values: Sequence[str], DomainName: str
     ) -> DeleteProfileKeyResponseTypeDef:
         """
         Removes a searchable key from a customer profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile_key)
         """
-
     async def delete_profile_object(
         self, *, ProfileId: str, ProfileObjectUniqueKey: str, ObjectTypeName: str, DomainName: str
     ) -> DeleteProfileObjectResponseTypeDef:
         """
         Removes an object associated with a profile of a given ProfileObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile_object)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile_object)
         """
-
     async def delete_profile_object_type(
         self, *, DomainName: str, ObjectTypeName: str
     ) -> DeleteProfileObjectTypeResponseTypeDef:
         """
         Removes a ProfileObjectType from a specific domain as well as removes all the
         ProfileObjects of that type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile_object_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile_object_type)
         """
-
     async def delete_workflow(self, *, DomainName: str, WorkflowId: str) -> Dict[str, Any]:
         """
         Deletes the specified workflow and all its corresponding resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_workflow)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#generate_presigned_url)
         """
-
     async def get_auto_merging_preview(
         self,
         *,
         DomainName: str,
         Consolidation: ConsolidationTypeDef,
         ConflictResolution: ConflictResolutionTypeDef,
         MinAllowedConfidenceScoreForMerging: float = ...
@@ -305,158 +342,200 @@
         """
         Tests the auto-merging settings of your Identity Resolution Job without merging
         your data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_auto_merging_preview)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_auto_merging_preview)
         """
+    async def get_calculated_attribute_definition(
+        self, *, DomainName: str, CalculatedAttributeName: str
+    ) -> GetCalculatedAttributeDefinitionResponseTypeDef:
+        """
+        Provides more information on a calculated attribute definition for Customer
+        Profiles.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_calculated_attribute_definition)
+        """
+    async def get_calculated_attribute_for_profile(
+        self, *, DomainName: str, ProfileId: str, CalculatedAttributeName: str
+    ) -> GetCalculatedAttributeForProfileResponseTypeDef:
+        """
+        Retrieve a calculated attribute for a customer profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_calculated_attribute_for_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_calculated_attribute_for_profile)
+        """
     async def get_domain(self, *, DomainName: str) -> GetDomainResponseTypeDef:
         """
         Returns information about a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_domain)
         """
+    async def get_event_stream(
+        self, *, DomainName: str, EventStreamName: str
+    ) -> GetEventStreamResponseTypeDef:
+        """
+        Returns information about the specified event stream in a specific domain.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_event_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_event_stream)
+        """
     async def get_identity_resolution_job(
         self, *, DomainName: str, JobId: str
     ) -> GetIdentityResolutionJobResponseTypeDef:
         """
         Returns information about an Identity Resolution Job in a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_identity_resolution_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_identity_resolution_job)
         """
-
     async def get_integration(self, *, DomainName: str, Uri: str) -> GetIntegrationResponseTypeDef:
         """
         Returns an integration for a domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_integration)
         """
-
     async def get_matches(
         self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> GetMatchesResponseTypeDef:
         """
         Before calling this API, use
         [CreateDomain](https://docs.aws.amazon.com/customerprofiles/latest/APIReference/API_CreateDomain.html)_
         or
         [UpdateDomain](https://docs.aws.amazon.com/customerprofiles/latest/APIReference/API_UpdateDomain.html)_
         to enable identity resolution: set `Matching` to tr...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_matches)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_matches)
         """
-
     async def get_profile_object_type(
         self, *, DomainName: str, ObjectTypeName: str
     ) -> GetProfileObjectTypeResponseTypeDef:
         """
         Returns the object types for a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_profile_object_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_profile_object_type)
         """
-
     async def get_profile_object_type_template(
         self, *, TemplateId: str
     ) -> GetProfileObjectTypeTemplateResponseTypeDef:
         """
         Returns the template information for a specific object type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_profile_object_type_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_profile_object_type_template)
         """
-
     async def get_workflow(self, *, DomainName: str, WorkflowId: str) -> GetWorkflowResponseTypeDef:
         """
         Get details of specified workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_workflow)
         """
-
     async def get_workflow_steps(
         self, *, DomainName: str, WorkflowId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> GetWorkflowStepsResponseTypeDef:
         """
         Get granular list of steps in workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_workflow_steps)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_workflow_steps)
         """
-
     async def list_account_integrations(
         self, *, Uri: str, NextToken: str = ..., MaxResults: int = ..., IncludeHidden: bool = ...
     ) -> ListAccountIntegrationsResponseTypeDef:
         """
         Lists all of the integrations associated to a specific URI in the AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_account_integrations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_account_integrations)
         """
+    async def list_calculated_attribute_definitions(
+        self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListCalculatedAttributeDefinitionsResponseTypeDef:
+        """
+        Lists calculated attribute definitions for Customer Profiles See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/customer-
+        profiles-2020-08-15/ListCalculatedAttributeDefinitions).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_calculated_attribute_definitions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_calculated_attribute_definitions)
+        """
+    async def list_calculated_attributes_for_profile(
+        self, *, DomainName: str, ProfileId: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListCalculatedAttributesForProfileResponseTypeDef:
+        """
+        Retrieve a list of calculated attributes for a customer profile.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_calculated_attributes_for_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_calculated_attributes_for_profile)
+        """
     async def list_domains(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDomainsResponseTypeDef:
         """
         Returns a list of all the domains for an AWS account that have been created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_domains)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_domains)
         """
+    async def list_event_streams(
+        self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListEventStreamsResponseTypeDef:
+        """
+        Returns a list of all the event streams in a specific domain.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_event_streams)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_event_streams)
+        """
     async def list_identity_resolution_jobs(
         self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListIdentityResolutionJobsResponseTypeDef:
         """
         Lists all of the Identity Resolution Jobs in your domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_identity_resolution_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_identity_resolution_jobs)
         """
-
     async def list_integrations(
         self,
         *,
         DomainName: str,
         NextToken: str = ...,
         MaxResults: int = ...,
         IncludeHidden: bool = ...
     ) -> ListIntegrationsResponseTypeDef:
         """
         Lists all of the integrations in your domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_integrations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_integrations)
         """
-
     async def list_profile_object_type_templates(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListProfileObjectTypeTemplatesResponseTypeDef:
         """
         Lists all of the template information for object types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_profile_object_type_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_profile_object_type_templates)
         """
-
     async def list_profile_object_types(
         self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListProfileObjectTypesResponseTypeDef:
         """
         Lists all of the templates available within the service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_profile_object_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_profile_object_types)
         """
-
     async def list_profile_objects(
         self,
         *,
         DomainName: str,
         ObjectTypeName: str,
         ProfileId: str,
         NextToken: str = ...,
@@ -466,25 +545,23 @@
         """
         Returns a list of objects associated with a profile of a given
         ProfileObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_profile_objects)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_profile_objects)
         """
-
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Displays the tags associated with an Amazon Connect Customer Profiles resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_tags_for_resource)
         """
-
     async def list_workflows(
         self,
         *,
         DomainName: str,
         WorkflowType: Literal["APPFLOW_INTEGRATION"] = ...,
         Status: StatusType = ...,
         QueryStartDate: Union[datetime, str] = ...,
@@ -494,31 +571,29 @@
     ) -> ListWorkflowsResponseTypeDef:
         """
         Query to list all workflows.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_workflows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_workflows)
         """
-
     async def merge_profiles(
         self,
         *,
         DomainName: str,
         MainProfileId: str,
         ProfileIdsToBeMerged: Sequence[str],
         FieldSourceProfileIds: FieldSourceProfileIdsTypeDef = ...
     ) -> MergeProfilesResponseTypeDef:
         """
-        Runs an AWS Lambda job that does the following * All the profileKeys in the
+        Runs an AWS Lambda job that does the following: * All the profileKeys in the
         `ProfileToBeMerged` will be moved to the main profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.merge_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#merge_profiles)
         """
-
     async def put_integration(
         self,
         *,
         DomainName: str,
         Uri: str = ...,
         ObjectTypeName: str = ...,
         Tags: Mapping[str, str] = ...,
@@ -528,25 +603,23 @@
         """
         Adds an integration between the service and a third-party service, which
         includes Amazon AppFlow and Amazon Connect.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.put_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#put_integration)
         """
-
     async def put_profile_object(
         self, *, ObjectTypeName: str, Object: str, DomainName: str
     ) -> PutProfileObjectResponseTypeDef:
         """
         Adds additional objects to customer profiles of a given ObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.put_profile_object)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#put_profile_object)
         """
-
     async def put_profile_object_type(
         self,
         *,
         DomainName: str,
         ObjectTypeName: str,
         Description: str,
         TemplateId: str = ...,
@@ -560,15 +633,14 @@
     ) -> PutProfileObjectTypeResponseTypeDef:
         """
         Defines a ProfileObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.put_profile_object_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#put_profile_object_type)
         """
-
     async def search_profiles(
         self,
         *,
         DomainName: str,
         KeyName: str,
         Values: Sequence[str],
         NextToken: str = ...,
@@ -580,33 +652,45 @@
         Searches for profiles within a specific domain using one or more predefined
         search keys (e.g., _fullName, _phone, _email, _account, etc.) and/or custom-
         defined search keys.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.search_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#search_profiles)
         """
-
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Assigns one or more tags (key-value pairs) to the specified Amazon Connect
         Customer Profiles resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#tag_resource)
         """
-
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes one or more tags from the specified Amazon Connect Customer Profiles
         resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#untag_resource)
         """
+    async def update_calculated_attribute_definition(
+        self,
+        *,
+        DomainName: str,
+        CalculatedAttributeName: str,
+        DisplayName: str = ...,
+        Description: str = ...,
+        Conditions: ConditionsTypeDef = ...
+    ) -> UpdateCalculatedAttributeDefinitionResponseTypeDef:
+        """
+        Updates an existing calculated attribute definition.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.update_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#update_calculated_attribute_definition)
+        """
     async def update_domain(
         self,
         *,
         DomainName: str,
         DefaultExpirationDays: int = ...,
         DefaultEncryptionKey: str = ...,
         DeadLetterQueueUrl: str = ...,
@@ -616,15 +700,14 @@
         """
         Updates the properties of a domain, including creating or selecting a dead
         letter queue or an encryption key.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.update_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#update_domain)
         """
-
     async def update_profile(
         self,
         *,
         DomainName: str,
         ProfileId: str,
         AdditionalInformation: str = ...,
         AccountNumber: str = ...,
@@ -652,19 +735,24 @@
     ) -> UpdateProfileResponseTypeDef:
         """
         Updates the properties of a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.update_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#update_profile)
         """
-
+    def get_paginator(
+        self, operation_name: Literal["list_event_streams"]
+    ) -> ListEventStreamsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_paginator)
+        """
     async def __aenter__(self) -> "CustomerProfilesClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/)
         """
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/client.pyi` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/client.py`

 * *Files 11% similar despite different names*

```diff
@@ -17,44 +17,55 @@
 import sys
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
-from .literals import GenderType, PartyTypeType, StatusType, logicalOperatorType
+from .literals import GenderType, PartyTypeType, StatisticType, StatusType, logicalOperatorType
+from .paginator import ListEventStreamsPaginator
 from .type_defs import (
     AdditionalSearchKeyTypeDef,
     AddProfileKeyResponseTypeDef,
     AddressTypeDef,
+    AttributeDetailsTypeDef,
+    ConditionsTypeDef,
     ConflictResolutionTypeDef,
     ConsolidationTypeDef,
+    CreateCalculatedAttributeDefinitionResponseTypeDef,
     CreateDomainResponseTypeDef,
+    CreateEventStreamResponseTypeDef,
     CreateIntegrationWorkflowResponseTypeDef,
     CreateProfileResponseTypeDef,
     DeleteDomainResponseTypeDef,
     DeleteIntegrationResponseTypeDef,
     DeleteProfileKeyResponseTypeDef,
     DeleteProfileObjectResponseTypeDef,
     DeleteProfileObjectTypeResponseTypeDef,
     DeleteProfileResponseTypeDef,
     FieldSourceProfileIdsTypeDef,
     FlowDefinitionTypeDef,
     GetAutoMergingPreviewResponseTypeDef,
+    GetCalculatedAttributeDefinitionResponseTypeDef,
+    GetCalculatedAttributeForProfileResponseTypeDef,
     GetDomainResponseTypeDef,
+    GetEventStreamResponseTypeDef,
     GetIdentityResolutionJobResponseTypeDef,
     GetIntegrationResponseTypeDef,
     GetMatchesResponseTypeDef,
     GetProfileObjectTypeResponseTypeDef,
     GetProfileObjectTypeTemplateResponseTypeDef,
     GetWorkflowResponseTypeDef,
     GetWorkflowStepsResponseTypeDef,
     IntegrationConfigTypeDef,
     ListAccountIntegrationsResponseTypeDef,
+    ListCalculatedAttributeDefinitionsResponseTypeDef,
+    ListCalculatedAttributesForProfileResponseTypeDef,
     ListDomainsResponseTypeDef,
+    ListEventStreamsResponseTypeDef,
     ListIdentityResolutionJobsResponseTypeDef,
     ListIntegrationsResponseTypeDef,
     ListProfileObjectsResponseTypeDef,
     ListProfileObjectTypesResponseTypeDef,
     ListProfileObjectTypeTemplatesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListWorkflowsResponseTypeDef,
@@ -64,40 +75,45 @@
     ObjectTypeFieldTypeDef,
     ObjectTypeKeyTypeDef,
     PutIntegrationResponseTypeDef,
     PutProfileObjectResponseTypeDef,
     PutProfileObjectTypeResponseTypeDef,
     SearchProfilesResponseTypeDef,
     UpdateAddressTypeDef,
+    UpdateCalculatedAttributeDefinitionResponseTypeDef,
     UpdateDomainResponseTypeDef,
     UpdateProfileResponseTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("CustomerProfilesClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
 
+
 class CustomerProfilesClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/)
     """
 
     meta: ClientMeta
@@ -106,38 +122,61 @@
     def exceptions(self) -> Exceptions:
         """
         CustomerProfilesClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#exceptions)
         """
+
     async def add_profile_key(
         self, *, ProfileId: str, KeyName: str, Values: Sequence[str], DomainName: str
     ) -> AddProfileKeyResponseTypeDef:
         """
         Associates a new key value with a specific profile, such as a Contact Record
         ContactId.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.add_profile_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#add_profile_key)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#close)
         """
+
+    async def create_calculated_attribute_definition(
+        self,
+        *,
+        DomainName: str,
+        CalculatedAttributeName: str,
+        AttributeDetails: AttributeDetailsTypeDef,
+        Statistic: StatisticType,
+        DisplayName: str = ...,
+        Description: str = ...,
+        Conditions: ConditionsTypeDef = ...,
+        Tags: Mapping[str, str] = ...
+    ) -> CreateCalculatedAttributeDefinitionResponseTypeDef:
+        """
+        Creates a new calculated attribute definition.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_calculated_attribute_definition)
+        """
+
     async def create_domain(
         self,
         *,
         DomainName: str,
         DefaultExpirationDays: int,
         DefaultEncryptionKey: str = ...,
         DeadLetterQueueUrl: str = ...,
@@ -147,14 +186,26 @@
         """
         Creates a domain, which is a container for all customer data, such as customer
         profile attributes, object types, profile keys, and encryption keys.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_domain)
         """
+
+    async def create_event_stream(
+        self, *, DomainName: str, Uri: str, EventStreamName: str, Tags: Mapping[str, str] = ...
+    ) -> CreateEventStreamResponseTypeDef:
+        """
+        Creates an event stream, which is a subscription to real-time events, such as
+        when profiles are created and updated through Amazon Connect Customer Profiles.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_event_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_event_stream)
+        """
+
     async def create_integration_workflow(
         self,
         *,
         DomainName: str,
         WorkflowType: Literal["APPFLOW_INTEGRATION"],
         IntegrationConfig: IntegrationConfigTypeDef,
         ObjectTypeName: str,
@@ -163,14 +214,15 @@
     ) -> CreateIntegrationWorkflowResponseTypeDef:
         """
         Creates an integration workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_integration_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_integration_workflow)
         """
+
     async def create_profile(
         self,
         *,
         DomainName: str,
         AccountNumber: str = ...,
         AdditionalInformation: str = ...,
         PartyType: PartyTypeType = ...,
@@ -197,88 +249,115 @@
     ) -> CreateProfileResponseTypeDef:
         """
         Creates a standard profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.create_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#create_profile)
         """
+
+    async def delete_calculated_attribute_definition(
+        self, *, DomainName: str, CalculatedAttributeName: str
+    ) -> Dict[str, Any]:
+        """
+        Deletes an existing calculated attribute definition.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_calculated_attribute_definition)
+        """
+
     async def delete_domain(self, *, DomainName: str) -> DeleteDomainResponseTypeDef:
         """
         Deletes a specific domain and all of its customer data, such as customer profile
         attributes and their related objects.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_domain)
         """
+
+    async def delete_event_stream(self, *, DomainName: str, EventStreamName: str) -> Dict[str, Any]:
+        """
+        Disables and deletes the specified event stream.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_event_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_event_stream)
+        """
+
     async def delete_integration(
         self, *, DomainName: str, Uri: str
     ) -> DeleteIntegrationResponseTypeDef:
         """
         Removes an integration from a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_integration)
         """
+
     async def delete_profile(
         self, *, ProfileId: str, DomainName: str
     ) -> DeleteProfileResponseTypeDef:
         """
         Deletes the standard customer profile and all data pertaining to the profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile)
         """
+
     async def delete_profile_key(
         self, *, ProfileId: str, KeyName: str, Values: Sequence[str], DomainName: str
     ) -> DeleteProfileKeyResponseTypeDef:
         """
         Removes a searchable key from a customer profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile_key)
         """
+
     async def delete_profile_object(
         self, *, ProfileId: str, ProfileObjectUniqueKey: str, ObjectTypeName: str, DomainName: str
     ) -> DeleteProfileObjectResponseTypeDef:
         """
         Removes an object associated with a profile of a given ProfileObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile_object)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile_object)
         """
+
     async def delete_profile_object_type(
         self, *, DomainName: str, ObjectTypeName: str
     ) -> DeleteProfileObjectTypeResponseTypeDef:
         """
         Removes a ProfileObjectType from a specific domain as well as removes all the
         ProfileObjects of that type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_profile_object_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_profile_object_type)
         """
+
     async def delete_workflow(self, *, DomainName: str, WorkflowId: str) -> Dict[str, Any]:
         """
         Deletes the specified workflow and all its corresponding resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.delete_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#delete_workflow)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#generate_presigned_url)
         """
+
     async def get_auto_merging_preview(
         self,
         *,
         DomainName: str,
         Consolidation: ConsolidationTypeDef,
         ConflictResolution: ConflictResolutionTypeDef,
         MinAllowedConfidenceScoreForMerging: float = ...
@@ -286,143 +365,221 @@
         """
         Tests the auto-merging settings of your Identity Resolution Job without merging
         your data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_auto_merging_preview)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_auto_merging_preview)
         """
+
+    async def get_calculated_attribute_definition(
+        self, *, DomainName: str, CalculatedAttributeName: str
+    ) -> GetCalculatedAttributeDefinitionResponseTypeDef:
+        """
+        Provides more information on a calculated attribute definition for Customer
+        Profiles.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_calculated_attribute_definition)
+        """
+
+    async def get_calculated_attribute_for_profile(
+        self, *, DomainName: str, ProfileId: str, CalculatedAttributeName: str
+    ) -> GetCalculatedAttributeForProfileResponseTypeDef:
+        """
+        Retrieve a calculated attribute for a customer profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_calculated_attribute_for_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_calculated_attribute_for_profile)
+        """
+
     async def get_domain(self, *, DomainName: str) -> GetDomainResponseTypeDef:
         """
         Returns information about a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_domain)
         """
+
+    async def get_event_stream(
+        self, *, DomainName: str, EventStreamName: str
+    ) -> GetEventStreamResponseTypeDef:
+        """
+        Returns information about the specified event stream in a specific domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_event_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_event_stream)
+        """
+
     async def get_identity_resolution_job(
         self, *, DomainName: str, JobId: str
     ) -> GetIdentityResolutionJobResponseTypeDef:
         """
         Returns information about an Identity Resolution Job in a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_identity_resolution_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_identity_resolution_job)
         """
+
     async def get_integration(self, *, DomainName: str, Uri: str) -> GetIntegrationResponseTypeDef:
         """
         Returns an integration for a domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_integration)
         """
+
     async def get_matches(
         self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> GetMatchesResponseTypeDef:
         """
         Before calling this API, use
         [CreateDomain](https://docs.aws.amazon.com/customerprofiles/latest/APIReference/API_CreateDomain.html)_
         or
         [UpdateDomain](https://docs.aws.amazon.com/customerprofiles/latest/APIReference/API_UpdateDomain.html)_
         to enable identity resolution: set `Matching` to tr...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_matches)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_matches)
         """
+
     async def get_profile_object_type(
         self, *, DomainName: str, ObjectTypeName: str
     ) -> GetProfileObjectTypeResponseTypeDef:
         """
         Returns the object types for a specific domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_profile_object_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_profile_object_type)
         """
+
     async def get_profile_object_type_template(
         self, *, TemplateId: str
     ) -> GetProfileObjectTypeTemplateResponseTypeDef:
         """
         Returns the template information for a specific object type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_profile_object_type_template)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_profile_object_type_template)
         """
+
     async def get_workflow(self, *, DomainName: str, WorkflowId: str) -> GetWorkflowResponseTypeDef:
         """
         Get details of specified workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_workflow)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_workflow)
         """
+
     async def get_workflow_steps(
         self, *, DomainName: str, WorkflowId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> GetWorkflowStepsResponseTypeDef:
         """
         Get granular list of steps in workflow.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_workflow_steps)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_workflow_steps)
         """
+
     async def list_account_integrations(
         self, *, Uri: str, NextToken: str = ..., MaxResults: int = ..., IncludeHidden: bool = ...
     ) -> ListAccountIntegrationsResponseTypeDef:
         """
         Lists all of the integrations associated to a specific URI in the AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_account_integrations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_account_integrations)
         """
+
+    async def list_calculated_attribute_definitions(
+        self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListCalculatedAttributeDefinitionsResponseTypeDef:
+        """
+        Lists calculated attribute definitions for Customer Profiles See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/customer-
+        profiles-2020-08-15/ListCalculatedAttributeDefinitions).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_calculated_attribute_definitions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_calculated_attribute_definitions)
+        """
+
+    async def list_calculated_attributes_for_profile(
+        self, *, DomainName: str, ProfileId: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListCalculatedAttributesForProfileResponseTypeDef:
+        """
+        Retrieve a list of calculated attributes for a customer profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_calculated_attributes_for_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_calculated_attributes_for_profile)
+        """
+
     async def list_domains(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDomainsResponseTypeDef:
         """
         Returns a list of all the domains for an AWS account that have been created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_domains)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_domains)
         """
+
+    async def list_event_streams(
+        self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListEventStreamsResponseTypeDef:
+        """
+        Returns a list of all the event streams in a specific domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_event_streams)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_event_streams)
+        """
+
     async def list_identity_resolution_jobs(
         self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListIdentityResolutionJobsResponseTypeDef:
         """
         Lists all of the Identity Resolution Jobs in your domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_identity_resolution_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_identity_resolution_jobs)
         """
+
     async def list_integrations(
         self,
         *,
         DomainName: str,
         NextToken: str = ...,
         MaxResults: int = ...,
         IncludeHidden: bool = ...
     ) -> ListIntegrationsResponseTypeDef:
         """
         Lists all of the integrations in your domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_integrations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_integrations)
         """
+
     async def list_profile_object_type_templates(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListProfileObjectTypeTemplatesResponseTypeDef:
         """
         Lists all of the template information for object types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_profile_object_type_templates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_profile_object_type_templates)
         """
+
     async def list_profile_object_types(
         self, *, DomainName: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListProfileObjectTypesResponseTypeDef:
         """
         Lists all of the templates available within the service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_profile_object_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_profile_object_types)
         """
+
     async def list_profile_objects(
         self,
         *,
         DomainName: str,
         ObjectTypeName: str,
         ProfileId: str,
         NextToken: str = ...,
@@ -432,23 +589,25 @@
         """
         Returns a list of objects associated with a profile of a given
         ProfileObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_profile_objects)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_profile_objects)
         """
+
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Displays the tags associated with an Amazon Connect Customer Profiles resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_tags_for_resource)
         """
+
     async def list_workflows(
         self,
         *,
         DomainName: str,
         WorkflowType: Literal["APPFLOW_INTEGRATION"] = ...,
         Status: StatusType = ...,
         QueryStartDate: Union[datetime, str] = ...,
@@ -458,29 +617,31 @@
     ) -> ListWorkflowsResponseTypeDef:
         """
         Query to list all workflows.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.list_workflows)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#list_workflows)
         """
+
     async def merge_profiles(
         self,
         *,
         DomainName: str,
         MainProfileId: str,
         ProfileIdsToBeMerged: Sequence[str],
         FieldSourceProfileIds: FieldSourceProfileIdsTypeDef = ...
     ) -> MergeProfilesResponseTypeDef:
         """
-        Runs an AWS Lambda job that does the following * All the profileKeys in the
+        Runs an AWS Lambda job that does the following: * All the profileKeys in the
         `ProfileToBeMerged` will be moved to the main profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.merge_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#merge_profiles)
         """
+
     async def put_integration(
         self,
         *,
         DomainName: str,
         Uri: str = ...,
         ObjectTypeName: str = ...,
         Tags: Mapping[str, str] = ...,
@@ -490,23 +651,25 @@
         """
         Adds an integration between the service and a third-party service, which
         includes Amazon AppFlow and Amazon Connect.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.put_integration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#put_integration)
         """
+
     async def put_profile_object(
         self, *, ObjectTypeName: str, Object: str, DomainName: str
     ) -> PutProfileObjectResponseTypeDef:
         """
         Adds additional objects to customer profiles of a given ObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.put_profile_object)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#put_profile_object)
         """
+
     async def put_profile_object_type(
         self,
         *,
         DomainName: str,
         ObjectTypeName: str,
         Description: str,
         TemplateId: str = ...,
@@ -520,14 +683,15 @@
     ) -> PutProfileObjectTypeResponseTypeDef:
         """
         Defines a ProfileObjectType.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.put_profile_object_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#put_profile_object_type)
         """
+
     async def search_profiles(
         self,
         *,
         DomainName: str,
         KeyName: str,
         Values: Sequence[str],
         NextToken: str = ...,
@@ -539,30 +703,49 @@
         Searches for profiles within a specific domain using one or more predefined
         search keys (e.g., _fullName, _phone, _email, _account, etc.) and/or custom-
         defined search keys.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.search_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#search_profiles)
         """
+
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Assigns one or more tags (key-value pairs) to the specified Amazon Connect
         Customer Profiles resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#tag_resource)
         """
+
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes one or more tags from the specified Amazon Connect Customer Profiles
         resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#untag_resource)
         """
+
+    async def update_calculated_attribute_definition(
+        self,
+        *,
+        DomainName: str,
+        CalculatedAttributeName: str,
+        DisplayName: str = ...,
+        Description: str = ...,
+        Conditions: ConditionsTypeDef = ...
+    ) -> UpdateCalculatedAttributeDefinitionResponseTypeDef:
+        """
+        Updates an existing calculated attribute definition.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.update_calculated_attribute_definition)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#update_calculated_attribute_definition)
+        """
+
     async def update_domain(
         self,
         *,
         DomainName: str,
         DefaultExpirationDays: int = ...,
         DefaultEncryptionKey: str = ...,
         DeadLetterQueueUrl: str = ...,
@@ -572,14 +755,15 @@
         """
         Updates the properties of a domain, including creating or selecting a dead
         letter queue or an encryption key.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.update_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#update_domain)
         """
+
     async def update_profile(
         self,
         *,
         DomainName: str,
         ProfileId: str,
         AdditionalInformation: str = ...,
         AccountNumber: str = ...,
@@ -607,17 +791,27 @@
     ) -> UpdateProfileResponseTypeDef:
         """
         Updates the properties of a profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.update_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#update_profile)
         """
+
+    def get_paginator(
+        self, operation_name: Literal["list_event_streams"]
+    ) -> ListEventStreamsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "CustomerProfilesClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/client/)
         """
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/literals.py` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/literals.py`

 * *Files 10% similar despite different names*

```diff
@@ -18,49 +18,59 @@
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "ConflictResolvingModelType",
     "DataPullModeType",
+    "EventStreamDestinationStatusType",
+    "EventStreamStateType",
     "FieldContentTypeType",
     "GenderType",
     "IdentityResolutionJobStatusType",
     "JobScheduleDayOfTheWeekType",
+    "ListEventStreamsPaginatorName",
     "MarketoConnectorOperatorType",
     "OperatorPropertiesKeysType",
+    "OperatorType",
     "PartyTypeType",
     "S3ConnectorOperatorType",
     "SalesforceConnectorOperatorType",
     "ServiceNowConnectorOperatorType",
     "SourceConnectorTypeType",
     "StandardIdentifierType",
+    "StatisticType",
     "StatusType",
     "TaskTypeType",
     "TriggerTypeType",
+    "UnitType",
     "WorkflowTypeType",
     "ZendeskConnectorOperatorType",
     "logicalOperatorType",
     "CustomerProfilesServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
     "RegionName",
 )
 
 
 ConflictResolvingModelType = Literal["RECENCY", "SOURCE"]
 DataPullModeType = Literal["Complete", "Incremental"]
+EventStreamDestinationStatusType = Literal["HEALTHY", "UNHEALTHY"]
+EventStreamStateType = Literal["RUNNING", "STOPPED"]
 FieldContentTypeType = Literal["EMAIL_ADDRESS", "NAME", "NUMBER", "PHONE_NUMBER", "STRING"]
 GenderType = Literal["FEMALE", "MALE", "UNSPECIFIED"]
 IdentityResolutionJobStatusType = Literal[
     "COMPLETED", "FAILED", "FIND_MATCHING", "MERGING", "PARTIAL_SUCCESS", "PENDING", "PREPROCESSING"
 ]
 JobScheduleDayOfTheWeekType = Literal[
     "FRIDAY", "MONDAY", "SATURDAY", "SUNDAY", "THURSDAY", "TUESDAY", "WEDNESDAY"
 ]
+ListEventStreamsPaginatorName = Literal["list_event_streams"]
 MarketoConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
     "GREATER_THAN",
     "LESS_THAN",
     "MASK_ALL",
@@ -87,14 +97,15 @@
     "SUBFIELD_CATEGORY_MAP",
     "TRUNCATE_LENGTH",
     "UPPER_BOUND",
     "VALIDATION_ACTION",
     "VALUE",
     "VALUES",
 ]
+OperatorType = Literal["EQUAL_TO", "GREATER_THAN", "LESS_THAN", "NOT_EQUAL_TO"]
 PartyTypeType = Literal["BUSINESS", "INDIVIDUAL", "OTHER"]
 S3ConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
     "EQUAL_TO",
     "GREATER_THAN",
@@ -160,19 +171,30 @@
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
 SourceConnectorTypeType = Literal["Marketo", "S3", "Salesforce", "Servicenow", "Zendesk"]
 StandardIdentifierType = Literal[
     "ASSET", "CASE", "LOOKUP_ONLY", "NEW_ONLY", "ORDER", "PROFILE", "SECONDARY", "UNIQUE"
 ]
+StatisticType = Literal[
+    "AVERAGE",
+    "COUNT",
+    "FIRST_OCCURRENCE",
+    "LAST_OCCURRENCE",
+    "MAXIMUM",
+    "MAX_OCCURRENCE",
+    "MINIMUM",
+    "SUM",
+]
 StatusType = Literal[
     "CANCELLED", "COMPLETE", "FAILED", "IN_PROGRESS", "NOT_STARTED", "RETRY", "SPLIT"
 ]
 TaskTypeType = Literal["Arithmetic", "Filter", "Map", "Mask", "Merge", "Truncate", "Validate"]
 TriggerTypeType = Literal["Event", "OnDemand", "Scheduled"]
+UnitType = Literal["DAYS"]
 WorkflowTypeType = Literal["APPFLOW_INTEGRATION"]
 ZendeskConnectorOperatorType = Literal[
     "ADDITION",
     "DIVISION",
     "GREATER_THAN",
     "MASK_ALL",
     "MASK_FIRST_N",
@@ -246,14 +268,15 @@
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
@@ -332,14 +355,15 @@
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
@@ -350,14 +374,15 @@
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
@@ -393,14 +418,15 @@
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
@@ -419,16 +445,19 @@
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
@@ -512,15 +541,17 @@
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
@@ -538,14 +569,15 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_event_streams"]
 RegionName = Literal[
     "af-south-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/literals.pyi` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/literals.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -17,48 +17,58 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ConflictResolvingModelType",
     "DataPullModeType",
+    "EventStreamDestinationStatusType",
+    "EventStreamStateType",
     "FieldContentTypeType",
     "GenderType",
     "IdentityResolutionJobStatusType",
     "JobScheduleDayOfTheWeekType",
+    "ListEventStreamsPaginatorName",
     "MarketoConnectorOperatorType",
     "OperatorPropertiesKeysType",
+    "OperatorType",
     "PartyTypeType",
     "S3ConnectorOperatorType",
     "SalesforceConnectorOperatorType",
     "ServiceNowConnectorOperatorType",
     "SourceConnectorTypeType",
     "StandardIdentifierType",
+    "StatisticType",
     "StatusType",
     "TaskTypeType",
     "TriggerTypeType",
+    "UnitType",
     "WorkflowTypeType",
     "ZendeskConnectorOperatorType",
     "logicalOperatorType",
     "CustomerProfilesServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
     "RegionName",
 )
 
 ConflictResolvingModelType = Literal["RECENCY", "SOURCE"]
 DataPullModeType = Literal["Complete", "Incremental"]
+EventStreamDestinationStatusType = Literal["HEALTHY", "UNHEALTHY"]
+EventStreamStateType = Literal["RUNNING", "STOPPED"]
 FieldContentTypeType = Literal["EMAIL_ADDRESS", "NAME", "NUMBER", "PHONE_NUMBER", "STRING"]
 GenderType = Literal["FEMALE", "MALE", "UNSPECIFIED"]
 IdentityResolutionJobStatusType = Literal[
     "COMPLETED", "FAILED", "FIND_MATCHING", "MERGING", "PARTIAL_SUCCESS", "PENDING", "PREPROCESSING"
 ]
 JobScheduleDayOfTheWeekType = Literal[
     "FRIDAY", "MONDAY", "SATURDAY", "SUNDAY", "THURSDAY", "TUESDAY", "WEDNESDAY"
 ]
+ListEventStreamsPaginatorName = Literal["list_event_streams"]
 MarketoConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
     "GREATER_THAN",
     "LESS_THAN",
     "MASK_ALL",
@@ -85,14 +95,15 @@
     "SUBFIELD_CATEGORY_MAP",
     "TRUNCATE_LENGTH",
     "UPPER_BOUND",
     "VALIDATION_ACTION",
     "VALUE",
     "VALUES",
 ]
+OperatorType = Literal["EQUAL_TO", "GREATER_THAN", "LESS_THAN", "NOT_EQUAL_TO"]
 PartyTypeType = Literal["BUSINESS", "INDIVIDUAL", "OTHER"]
 S3ConnectorOperatorType = Literal[
     "ADDITION",
     "BETWEEN",
     "DIVISION",
     "EQUAL_TO",
     "GREATER_THAN",
@@ -158,19 +169,30 @@
     "VALIDATE_NON_ZERO",
     "VALIDATE_NUMERIC",
 ]
 SourceConnectorTypeType = Literal["Marketo", "S3", "Salesforce", "Servicenow", "Zendesk"]
 StandardIdentifierType = Literal[
     "ASSET", "CASE", "LOOKUP_ONLY", "NEW_ONLY", "ORDER", "PROFILE", "SECONDARY", "UNIQUE"
 ]
+StatisticType = Literal[
+    "AVERAGE",
+    "COUNT",
+    "FIRST_OCCURRENCE",
+    "LAST_OCCURRENCE",
+    "MAXIMUM",
+    "MAX_OCCURRENCE",
+    "MINIMUM",
+    "SUM",
+]
 StatusType = Literal[
     "CANCELLED", "COMPLETE", "FAILED", "IN_PROGRESS", "NOT_STARTED", "RETRY", "SPLIT"
 ]
 TaskTypeType = Literal["Arithmetic", "Filter", "Map", "Mask", "Merge", "Truncate", "Validate"]
 TriggerTypeType = Literal["Event", "OnDemand", "Scheduled"]
+UnitType = Literal["DAYS"]
 WorkflowTypeType = Literal["APPFLOW_INTEGRATION"]
 ZendeskConnectorOperatorType = Literal[
     "ADDITION",
     "DIVISION",
     "GREATER_THAN",
     "MASK_ALL",
     "MASK_FIRST_N",
@@ -244,14 +266,15 @@
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
@@ -330,14 +353,15 @@
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
@@ -348,14 +372,15 @@
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
@@ -391,14 +416,15 @@
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
@@ -417,16 +443,19 @@
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
@@ -510,15 +539,17 @@
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
@@ -536,14 +567,15 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_event_streams"]
 RegionName = Literal[
     "af-south-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/type_defs.py` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/type_defs.py`

 * *Files 20% similar despite different names*

```diff
@@ -14,26 +14,30 @@
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     ConflictResolvingModelType,
     DataPullModeType,
+    EventStreamDestinationStatusType,
+    EventStreamStateType,
     FieldContentTypeType,
     GenderType,
     IdentityResolutionJobStatusType,
     JobScheduleDayOfTheWeekType,
     MarketoConnectorOperatorType,
     OperatorPropertiesKeysType,
+    OperatorType,
     PartyTypeType,
     S3ConnectorOperatorType,
     SalesforceConnectorOperatorType,
     ServiceNowConnectorOperatorType,
     SourceConnectorTypeType,
     StandardIdentifierType,
+    StatisticType,
     StatusType,
     TaskTypeType,
     TriggerTypeType,
     ZendeskConnectorOperatorType,
     logicalOperatorType,
 )
 
@@ -45,121 +49,153 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AddProfileKeyRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddProfileKeyResponseTypeDef",
     "AdditionalSearchKeyTypeDef",
     "AddressTypeDef",
     "BatchTypeDef",
     "AppflowIntegrationWorkflowAttributesTypeDef",
     "AppflowIntegrationWorkflowMetricsTypeDef",
     "AppflowIntegrationWorkflowStepTypeDef",
+    "AttributeItemTypeDef",
     "ConflictResolutionTypeDef",
     "ConsolidationTypeDef",
+    "RangeTypeDef",
+    "ThresholdTypeDef",
     "ConnectorOperatorTypeDef",
+    "CreateEventStreamRequestRequestTypeDef",
+    "CreateEventStreamResponseTypeDef",
+    "CreateIntegrationWorkflowResponseTypeDef",
+    "CreateProfileResponseTypeDef",
+    "DeleteCalculatedAttributeDefinitionRequestRequestTypeDef",
     "DeleteDomainRequestRequestTypeDef",
+    "DeleteDomainResponseTypeDef",
+    "DeleteEventStreamRequestRequestTypeDef",
     "DeleteIntegrationRequestRequestTypeDef",
+    "DeleteIntegrationResponseTypeDef",
     "DeleteProfileKeyRequestRequestTypeDef",
+    "DeleteProfileKeyResponseTypeDef",
     "DeleteProfileObjectRequestRequestTypeDef",
+    "DeleteProfileObjectResponseTypeDef",
     "DeleteProfileObjectTypeRequestRequestTypeDef",
+    "DeleteProfileObjectTypeResponseTypeDef",
     "DeleteProfileRequestRequestTypeDef",
+    "DeleteProfileResponseTypeDef",
     "DeleteWorkflowRequestRequestTypeDef",
+    "DestinationSummaryTypeDef",
     "DomainStatsTypeDef",
+    "EventStreamDestinationDetailsTypeDef",
     "S3ExportingConfigTypeDef",
     "S3ExportingLocationTypeDef",
     "FieldSourceProfileIdsTypeDef",
     "FoundByKeyValueTypeDef",
+    "GetAutoMergingPreviewResponseTypeDef",
+    "GetCalculatedAttributeDefinitionRequestRequestTypeDef",
+    "GetCalculatedAttributeForProfileRequestRequestTypeDef",
+    "GetCalculatedAttributeForProfileResponseTypeDef",
     "GetDomainRequestRequestTypeDef",
+    "GetEventStreamRequestRequestTypeDef",
     "GetIdentityResolutionJobRequestRequestTypeDef",
     "JobStatsTypeDef",
     "GetIntegrationRequestRequestTypeDef",
+    "GetIntegrationResponseTypeDef",
     "GetMatchesRequestRequestTypeDef",
     "MatchItemTypeDef",
     "GetProfileObjectTypeRequestRequestTypeDef",
     "ObjectTypeFieldTypeDef",
     "ObjectTypeKeyTypeDef",
     "GetProfileObjectTypeTemplateRequestRequestTypeDef",
     "GetWorkflowRequestRequestTypeDef",
     "GetWorkflowStepsRequestRequestTypeDef",
     "IncrementalPullConfigTypeDef",
     "JobScheduleTypeDef",
     "ListAccountIntegrationsRequestRequestTypeDef",
     "ListIntegrationItemTypeDef",
+    "ListCalculatedAttributeDefinitionItemTypeDef",
+    "ListCalculatedAttributeDefinitionsRequestRequestTypeDef",
+    "ListCalculatedAttributeForProfileItemTypeDef",
+    "ListCalculatedAttributesForProfileRequestRequestTypeDef",
     "ListDomainItemTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListEventStreamsRequestListEventStreamsPaginateTypeDef",
+    "ListEventStreamsRequestRequestTypeDef",
     "ListIdentityResolutionJobsRequestRequestTypeDef",
     "ListIntegrationsRequestRequestTypeDef",
     "ListProfileObjectTypeItemTypeDef",
     "ListProfileObjectTypeTemplateItemTypeDef",
     "ListProfileObjectTypeTemplatesRequestRequestTypeDef",
     "ListProfileObjectTypesRequestRequestTypeDef",
     "ListProfileObjectsItemTypeDef",
     "ObjectFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListWorkflowsItemTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
     "MarketoSourcePropertiesTypeDef",
+    "MergeProfilesResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutIntegrationResponseTypeDef",
     "PutProfileObjectRequestRequestTypeDef",
+    "PutProfileObjectResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "S3SourcePropertiesTypeDef",
     "SalesforceSourcePropertiesTypeDef",
     "ScheduledTriggerPropertiesTypeDef",
     "ServiceNowSourcePropertiesTypeDef",
     "ZendeskSourcePropertiesTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAddressTypeDef",
-    "AddProfileKeyResponseTypeDef",
-    "CreateIntegrationWorkflowResponseTypeDef",
-    "CreateProfileResponseTypeDef",
-    "DeleteDomainResponseTypeDef",
-    "DeleteIntegrationResponseTypeDef",
-    "DeleteProfileKeyResponseTypeDef",
-    "DeleteProfileObjectResponseTypeDef",
-    "DeleteProfileObjectTypeResponseTypeDef",
-    "DeleteProfileResponseTypeDef",
-    "GetAutoMergingPreviewResponseTypeDef",
-    "GetIntegrationResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "MergeProfilesResponseTypeDef",
-    "PutIntegrationResponseTypeDef",
-    "PutProfileObjectResponseTypeDef",
     "UpdateProfileResponseTypeDef",
     "SearchProfilesRequestRequestTypeDef",
     "CreateProfileRequestRequestTypeDef",
     "WorkflowAttributesTypeDef",
     "WorkflowMetricsTypeDef",
     "WorkflowStepItemTypeDef",
+    "AttributeDetailsTypeDef",
     "AutoMergingTypeDef",
     "GetAutoMergingPreviewRequestRequestTypeDef",
+    "ConditionsTypeDef",
     "TaskTypeDef",
+    "EventStreamSummaryTypeDef",
+    "GetEventStreamResponseTypeDef",
     "ExportingConfigTypeDef",
     "ExportingLocationTypeDef",
     "MergeProfilesRequestRequestTypeDef",
     "ProfileTypeDef",
     "GetMatchesResponseTypeDef",
     "GetProfileObjectTypeResponseTypeDef",
     "GetProfileObjectTypeTemplateResponseTypeDef",
     "PutProfileObjectTypeRequestRequestTypeDef",
     "PutProfileObjectTypeResponseTypeDef",
     "ListAccountIntegrationsResponseTypeDef",
     "ListIntegrationsResponseTypeDef",
+    "ListCalculatedAttributeDefinitionsResponseTypeDef",
+    "ListCalculatedAttributesForProfileResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "ListProfileObjectTypesResponseTypeDef",
     "ListProfileObjectTypeTemplatesResponseTypeDef",
     "ListProfileObjectsResponseTypeDef",
     "ListProfileObjectsRequestRequestTypeDef",
     "ListWorkflowsResponseTypeDef",
     "TriggerPropertiesTypeDef",
     "SourceConnectorPropertiesTypeDef",
     "UpdateProfileRequestRequestTypeDef",
     "GetWorkflowResponseTypeDef",
     "GetWorkflowStepsResponseTypeDef",
+    "CreateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    "CreateCalculatedAttributeDefinitionResponseTypeDef",
+    "GetCalculatedAttributeDefinitionResponseTypeDef",
+    "UpdateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    "UpdateCalculatedAttributeDefinitionResponseTypeDef",
+    "ListEventStreamsResponseTypeDef",
     "MatchingRequestTypeDef",
     "MatchingResponseTypeDef",
     "GetIdentityResolutionJobResponseTypeDef",
     "IdentityResolutionJobTypeDef",
     "SearchProfilesResponseTypeDef",
     "TriggerConfigTypeDef",
     "SourceFlowConfigTypeDef",
@@ -182,22 +218,20 @@
         "ProfileId": str,
         "KeyName": str,
         "Values": Sequence[str],
         "DomainName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddProfileKeyResponseTypeDef = TypedDict(
+    "AddProfileKeyResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "KeyName": str,
+        "Values": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdditionalSearchKeyTypeDef = TypedDict(
     "AdditionalSearchKeyTypeDef",
     {
         "KeyName": str,
@@ -272,14 +306,21 @@
         "BatchRecordsStartTime": str,
         "BatchRecordsEndTime": str,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
     },
 )
 
+AttributeItemTypeDef = TypedDict(
+    "AttributeItemTypeDef",
+    {
+        "Name": str,
+    },
+)
+
 _RequiredConflictResolutionTypeDef = TypedDict(
     "_RequiredConflictResolutionTypeDef",
     {
         "ConflictResolvingModel": ConflictResolvingModelType,
     },
 )
 _OptionalConflictResolutionTypeDef = TypedDict(
@@ -300,96 +341,270 @@
 ConsolidationTypeDef = TypedDict(
     "ConsolidationTypeDef",
     {
         "MatchingAttributesList": Sequence[Sequence[str]],
     },
 )
 
+RangeTypeDef = TypedDict(
+    "RangeTypeDef",
+    {
+        "Value": int,
+        "Unit": Literal["DAYS"],
+    },
+)
+
+ThresholdTypeDef = TypedDict(
+    "ThresholdTypeDef",
+    {
+        "Value": str,
+        "Operator": OperatorType,
+    },
+)
+
 ConnectorOperatorTypeDef = TypedDict(
     "ConnectorOperatorTypeDef",
     {
         "Marketo": MarketoConnectorOperatorType,
         "S3": S3ConnectorOperatorType,
         "Salesforce": SalesforceConnectorOperatorType,
         "ServiceNow": ServiceNowConnectorOperatorType,
         "Zendesk": ZendeskConnectorOperatorType,
     },
     total=False,
 )
 
+_RequiredCreateEventStreamRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateEventStreamRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "Uri": str,
+        "EventStreamName": str,
+    },
+)
+_OptionalCreateEventStreamRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateEventStreamRequestRequestTypeDef",
+    {
+        "Tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class CreateEventStreamRequestRequestTypeDef(
+    _RequiredCreateEventStreamRequestRequestTypeDef, _OptionalCreateEventStreamRequestRequestTypeDef
+):
+    pass
+
+
+CreateEventStreamResponseTypeDef = TypedDict(
+    "CreateEventStreamResponseTypeDef",
+    {
+        "EventStreamArn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateIntegrationWorkflowResponseTypeDef = TypedDict(
+    "CreateIntegrationWorkflowResponseTypeDef",
+    {
+        "WorkflowId": str,
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProfileResponseTypeDef = TypedDict(
+    "CreateProfileResponseTypeDef",
+    {
+        "ProfileId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "DeleteCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+    },
+)
+
 DeleteDomainRequestRequestTypeDef = TypedDict(
     "DeleteDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DeleteDomainResponseTypeDef = TypedDict(
+    "DeleteDomainResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteEventStreamRequestRequestTypeDef = TypedDict(
+    "DeleteEventStreamRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamName": str,
+    },
+)
+
 DeleteIntegrationRequestRequestTypeDef = TypedDict(
     "DeleteIntegrationRequestRequestTypeDef",
     {
         "DomainName": str,
         "Uri": str,
     },
 )
 
+DeleteIntegrationResponseTypeDef = TypedDict(
+    "DeleteIntegrationResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileKeyRequestRequestTypeDef = TypedDict(
     "DeleteProfileKeyRequestRequestTypeDef",
     {
         "ProfileId": str,
         "KeyName": str,
         "Values": Sequence[str],
         "DomainName": str,
     },
 )
 
+DeleteProfileKeyResponseTypeDef = TypedDict(
+    "DeleteProfileKeyResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileObjectRequestRequestTypeDef = TypedDict(
     "DeleteProfileObjectRequestRequestTypeDef",
     {
         "ProfileId": str,
         "ProfileObjectUniqueKey": str,
         "ObjectTypeName": str,
         "DomainName": str,
     },
 )
 
+DeleteProfileObjectResponseTypeDef = TypedDict(
+    "DeleteProfileObjectResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileObjectTypeRequestRequestTypeDef = TypedDict(
     "DeleteProfileObjectTypeRequestRequestTypeDef",
     {
         "DomainName": str,
         "ObjectTypeName": str,
     },
 )
 
+DeleteProfileObjectTypeResponseTypeDef = TypedDict(
+    "DeleteProfileObjectTypeResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileRequestRequestTypeDef = TypedDict(
     "DeleteProfileRequestRequestTypeDef",
     {
         "ProfileId": str,
         "DomainName": str,
     },
 )
 
+DeleteProfileResponseTypeDef = TypedDict(
+    "DeleteProfileResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowRequestRequestTypeDef",
     {
         "DomainName": str,
         "WorkflowId": str,
     },
 )
 
+_RequiredDestinationSummaryTypeDef = TypedDict(
+    "_RequiredDestinationSummaryTypeDef",
+    {
+        "Uri": str,
+        "Status": EventStreamDestinationStatusType,
+    },
+)
+_OptionalDestinationSummaryTypeDef = TypedDict(
+    "_OptionalDestinationSummaryTypeDef",
+    {
+        "UnhealthySince": datetime,
+    },
+    total=False,
+)
+
+
+class DestinationSummaryTypeDef(
+    _RequiredDestinationSummaryTypeDef, _OptionalDestinationSummaryTypeDef
+):
+    pass
+
+
 DomainStatsTypeDef = TypedDict(
     "DomainStatsTypeDef",
     {
         "ProfileCount": int,
         "MeteringProfileCount": int,
         "ObjectCount": int,
         "TotalSize": int,
     },
     total=False,
 )
 
+_RequiredEventStreamDestinationDetailsTypeDef = TypedDict(
+    "_RequiredEventStreamDestinationDetailsTypeDef",
+    {
+        "Uri": str,
+        "Status": EventStreamDestinationStatusType,
+    },
+)
+_OptionalEventStreamDestinationDetailsTypeDef = TypedDict(
+    "_OptionalEventStreamDestinationDetailsTypeDef",
+    {
+        "UnhealthySince": datetime,
+        "Message": str,
+    },
+    total=False,
+)
+
+
+class EventStreamDestinationDetailsTypeDef(
+    _RequiredEventStreamDestinationDetailsTypeDef, _OptionalEventStreamDestinationDetailsTypeDef
+):
+    pass
+
+
 _RequiredS3ExportingConfigTypeDef = TypedDict(
     "_RequiredS3ExportingConfigTypeDef",
     {
         "S3BucketName": str,
     },
 )
 _OptionalS3ExportingConfigTypeDef = TypedDict(
@@ -449,21 +664,68 @@
     {
         "KeyName": str,
         "Values": List[str],
     },
     total=False,
 )
 
+GetAutoMergingPreviewResponseTypeDef = TypedDict(
+    "GetAutoMergingPreviewResponseTypeDef",
+    {
+        "DomainName": str,
+        "NumberOfMatchesInSample": int,
+        "NumberOfProfilesInSample": int,
+        "NumberOfProfilesWillBeMerged": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "GetCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+    },
+)
+
+GetCalculatedAttributeForProfileRequestRequestTypeDef = TypedDict(
+    "GetCalculatedAttributeForProfileRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "ProfileId": str,
+        "CalculatedAttributeName": str,
+    },
+)
+
+GetCalculatedAttributeForProfileResponseTypeDef = TypedDict(
+    "GetCalculatedAttributeForProfileResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "IsDataPartial": str,
+        "Value": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDomainRequestRequestTypeDef = TypedDict(
     "GetDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetEventStreamRequestRequestTypeDef = TypedDict(
+    "GetEventStreamRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamName": str,
+    },
+)
+
 GetIdentityResolutionJobRequestRequestTypeDef = TypedDict(
     "GetIdentityResolutionJobRequestRequestTypeDef",
     {
         "DomainName": str,
         "JobId": str,
     },
 )
@@ -482,14 +744,30 @@
     "GetIntegrationRequestRequestTypeDef",
     {
         "DomainName": str,
         "Uri": str,
     },
 )
 
+GetIntegrationResponseTypeDef = TypedDict(
+    "GetIntegrationResponseTypeDef",
+    {
+        "DomainName": str,
+        "Uri": str,
+        "ObjectTypeName": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+        "ObjectTypeNames": Dict[str, str],
+        "WorkflowId": str,
+        "IsUnstructured": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetMatchesRequestRequestTypeDef = TypedDict(
     "_RequiredGetMatchesRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalGetMatchesRequestRequestTypeDef = TypedDict(
@@ -647,14 +925,85 @@
 
 class ListIntegrationItemTypeDef(
     _RequiredListIntegrationItemTypeDef, _OptionalListIntegrationItemTypeDef
 ):
     pass
 
 
+ListCalculatedAttributeDefinitionItemTypeDef = TypedDict(
+    "ListCalculatedAttributeDefinitionItemTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+    },
+    total=False,
+)
+
+_RequiredListCalculatedAttributeDefinitionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListCalculatedAttributeDefinitionsRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListCalculatedAttributeDefinitionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListCalculatedAttributeDefinitionsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class ListCalculatedAttributeDefinitionsRequestRequestTypeDef(
+    _RequiredListCalculatedAttributeDefinitionsRequestRequestTypeDef,
+    _OptionalListCalculatedAttributeDefinitionsRequestRequestTypeDef,
+):
+    pass
+
+
+ListCalculatedAttributeForProfileItemTypeDef = TypedDict(
+    "ListCalculatedAttributeForProfileItemTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "IsDataPartial": str,
+        "Value": str,
+    },
+    total=False,
+)
+
+_RequiredListCalculatedAttributesForProfileRequestRequestTypeDef = TypedDict(
+    "_RequiredListCalculatedAttributesForProfileRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "ProfileId": str,
+    },
+)
+_OptionalListCalculatedAttributesForProfileRequestRequestTypeDef = TypedDict(
+    "_OptionalListCalculatedAttributesForProfileRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class ListCalculatedAttributesForProfileRequestRequestTypeDef(
+    _RequiredListCalculatedAttributesForProfileRequestRequestTypeDef,
+    _OptionalListCalculatedAttributesForProfileRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredListDomainItemTypeDef = TypedDict(
     "_RequiredListDomainItemTypeDef",
     {
         "DomainName": str,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
     },
@@ -677,14 +1026,58 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListEventStreamsRequestListEventStreamsPaginateTypeDef = TypedDict(
+    "_RequiredListEventStreamsRequestListEventStreamsPaginateTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListEventStreamsRequestListEventStreamsPaginateTypeDef = TypedDict(
+    "_OptionalListEventStreamsRequestListEventStreamsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListEventStreamsRequestListEventStreamsPaginateTypeDef(
+    _RequiredListEventStreamsRequestListEventStreamsPaginateTypeDef,
+    _OptionalListEventStreamsRequestListEventStreamsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListEventStreamsRequestRequestTypeDef = TypedDict(
+    "_RequiredListEventStreamsRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListEventStreamsRequestRequestTypeDef = TypedDict(
+    "_OptionalListEventStreamsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class ListEventStreamsRequestRequestTypeDef(
+    _RequiredListEventStreamsRequestRequestTypeDef, _OptionalListEventStreamsRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredListIdentityResolutionJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListIdentityResolutionJobsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListIdentityResolutionJobsRequestRequestTypeDef = TypedDict(
@@ -814,14 +1207,22 @@
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
 ListWorkflowsItemTypeDef = TypedDict(
     "ListWorkflowsItemTypeDef",
     {
         "WorkflowType": Literal["APPFLOW_INTEGRATION"],
         "WorkflowId": str,
         "Status": StatusType,
         "StatusDescription": str,
@@ -859,23 +1260,76 @@
 MarketoSourcePropertiesTypeDef = TypedDict(
     "MarketoSourcePropertiesTypeDef",
     {
         "Object": str,
     },
 )
 
+MergeProfilesResponseTypeDef = TypedDict(
+    "MergeProfilesResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
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
+PutIntegrationResponseTypeDef = TypedDict(
+    "PutIntegrationResponseTypeDef",
+    {
+        "DomainName": str,
+        "Uri": str,
+        "ObjectTypeName": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+        "ObjectTypeNames": Dict[str, str],
+        "WorkflowId": str,
+        "IsUnstructured": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutProfileObjectRequestRequestTypeDef = TypedDict(
     "PutProfileObjectRequestRequestTypeDef",
     {
         "ObjectTypeName": str,
         "Object": str,
         "DomainName": str,
     },
 )
 
+PutProfileObjectResponseTypeDef = TypedDict(
+    "PutProfileObjectResponseTypeDef",
+    {
+        "ProfileObjectUniqueKey": str,
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
 _RequiredS3SourcePropertiesTypeDef = TypedDict(
     "_RequiredS3SourcePropertiesTypeDef",
     {
         "BucketName": str,
     },
 )
 _OptionalS3SourcePropertiesTypeDef = TypedDict(
@@ -984,160 +1438,19 @@
         "Province": str,
         "Country": str,
         "PostalCode": str,
     },
     total=False,
 )
 
-AddProfileKeyResponseTypeDef = TypedDict(
-    "AddProfileKeyResponseTypeDef",
-    {
-        "KeyName": str,
-        "Values": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIntegrationWorkflowResponseTypeDef = TypedDict(
-    "CreateIntegrationWorkflowResponseTypeDef",
-    {
-        "WorkflowId": str,
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProfileResponseTypeDef = TypedDict(
-    "CreateProfileResponseTypeDef",
-    {
-        "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDomainResponseTypeDef = TypedDict(
-    "DeleteDomainResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteIntegrationResponseTypeDef = TypedDict(
-    "DeleteIntegrationResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileKeyResponseTypeDef = TypedDict(
-    "DeleteProfileKeyResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileObjectResponseTypeDef = TypedDict(
-    "DeleteProfileObjectResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileObjectTypeResponseTypeDef = TypedDict(
-    "DeleteProfileObjectTypeResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileResponseTypeDef = TypedDict(
-    "DeleteProfileResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAutoMergingPreviewResponseTypeDef = TypedDict(
-    "GetAutoMergingPreviewResponseTypeDef",
-    {
-        "DomainName": str,
-        "NumberOfMatchesInSample": int,
-        "NumberOfProfilesInSample": int,
-        "NumberOfProfilesWillBeMerged": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIntegrationResponseTypeDef = TypedDict(
-    "GetIntegrationResponseTypeDef",
-    {
-        "DomainName": str,
-        "Uri": str,
-        "ObjectTypeName": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "Tags": Dict[str, str],
-        "ObjectTypeNames": Dict[str, str],
-        "WorkflowId": str,
-        "IsUnstructured": bool,
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
-MergeProfilesResponseTypeDef = TypedDict(
-    "MergeProfilesResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutIntegrationResponseTypeDef = TypedDict(
-    "PutIntegrationResponseTypeDef",
-    {
-        "DomainName": str,
-        "Uri": str,
-        "ObjectTypeName": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "Tags": Dict[str, str],
-        "ObjectTypeNames": Dict[str, str],
-        "WorkflowId": str,
-        "IsUnstructured": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutProfileObjectResponseTypeDef = TypedDict(
-    "PutProfileObjectResponseTypeDef",
-    {
-        "ProfileObjectUniqueKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateProfileResponseTypeDef = TypedDict(
     "UpdateProfileResponseTypeDef",
     {
         "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredSearchProfilesRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1226,14 +1539,22 @@
     "WorkflowStepItemTypeDef",
     {
         "AppflowIntegration": AppflowIntegrationWorkflowStepTypeDef,
     },
     total=False,
 )
 
+AttributeDetailsTypeDef = TypedDict(
+    "AttributeDetailsTypeDef",
+    {
+        "Attributes": Sequence[AttributeItemTypeDef],
+        "Expression": str,
+    },
+)
+
 _RequiredAutoMergingTypeDef = TypedDict(
     "_RequiredAutoMergingTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalAutoMergingTypeDef = TypedDict(
@@ -1271,14 +1592,24 @@
 class GetAutoMergingPreviewRequestRequestTypeDef(
     _RequiredGetAutoMergingPreviewRequestRequestTypeDef,
     _OptionalGetAutoMergingPreviewRequestRequestTypeDef,
 ):
     pass
 
 
+ConditionsTypeDef = TypedDict(
+    "ConditionsTypeDef",
+    {
+        "Range": RangeTypeDef,
+        "ObjectCount": int,
+        "Threshold": ThresholdTypeDef,
+    },
+    total=False,
+)
+
 _RequiredTaskTypeDef = TypedDict(
     "_RequiredTaskTypeDef",
     {
         "SourceFields": Sequence[str],
         "TaskType": TaskTypeType,
     },
 )
@@ -1293,14 +1624,54 @@
 )
 
 
 class TaskTypeDef(_RequiredTaskTypeDef, _OptionalTaskTypeDef):
     pass
 
 
+_RequiredEventStreamSummaryTypeDef = TypedDict(
+    "_RequiredEventStreamSummaryTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamName": str,
+        "EventStreamArn": str,
+        "State": EventStreamStateType,
+    },
+)
+_OptionalEventStreamSummaryTypeDef = TypedDict(
+    "_OptionalEventStreamSummaryTypeDef",
+    {
+        "StoppedSince": datetime,
+        "DestinationSummary": DestinationSummaryTypeDef,
+        "Tags": Dict[str, str],
+    },
+    total=False,
+)
+
+
+class EventStreamSummaryTypeDef(
+    _RequiredEventStreamSummaryTypeDef, _OptionalEventStreamSummaryTypeDef
+):
+    pass
+
+
+GetEventStreamResponseTypeDef = TypedDict(
+    "GetEventStreamResponseTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamArn": str,
+        "CreatedAt": datetime,
+        "State": EventStreamStateType,
+        "StoppedSince": datetime,
+        "DestinationDetails": EventStreamDestinationDetailsTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportingConfigTypeDef = TypedDict(
     "ExportingConfigTypeDef",
     {
         "S3Exporting": S3ExportingConfigTypeDef,
     },
     total=False,
 )
@@ -1371,15 +1742,15 @@
 GetMatchesResponseTypeDef = TypedDict(
     "GetMatchesResponseTypeDef",
     {
         "NextToken": str,
         "MatchGenerationDate": datetime,
         "PotentialMatches": int,
         "Matches": List[MatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProfileObjectTypeResponseTypeDef = TypedDict(
     "GetProfileObjectTypeResponseTypeDef",
     {
         "ObjectTypeName": str,
@@ -1390,29 +1761,29 @@
         "AllowProfileCreation": bool,
         "SourceLastUpdatedTimestampFormat": str,
         "Fields": Dict[str, ObjectTypeFieldTypeDef],
         "Keys": Dict[str, List[ObjectTypeKeyTypeDef]],
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProfileObjectTypeTemplateResponseTypeDef = TypedDict(
     "GetProfileObjectTypeTemplateResponseTypeDef",
     {
         "TemplateId": str,
         "SourceName": str,
         "SourceObject": str,
         "AllowProfileCreation": bool,
         "SourceLastUpdatedTimestampFormat": str,
         "Fields": Dict[str, ObjectTypeFieldTypeDef],
         "Keys": Dict[str, List[ObjectTypeKeyTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutProfileObjectTypeRequestRequestTypeDef = TypedDict(
     "_RequiredPutProfileObjectTypeRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1454,69 +1825,87 @@
         "AllowProfileCreation": bool,
         "SourceLastUpdatedTimestampFormat": str,
         "Fields": Dict[str, ObjectTypeFieldTypeDef],
         "Keys": Dict[str, List[ObjectTypeKeyTypeDef]],
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountIntegrationsResponseTypeDef = TypedDict(
     "ListAccountIntegrationsResponseTypeDef",
     {
         "Items": List[ListIntegrationItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIntegrationsResponseTypeDef = TypedDict(
     "ListIntegrationsResponseTypeDef",
     {
         "Items": List[ListIntegrationItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCalculatedAttributeDefinitionsResponseTypeDef = TypedDict(
+    "ListCalculatedAttributeDefinitionsResponseTypeDef",
+    {
+        "Items": List[ListCalculatedAttributeDefinitionItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCalculatedAttributesForProfileResponseTypeDef = TypedDict(
+    "ListCalculatedAttributesForProfileResponseTypeDef",
+    {
+        "Items": List[ListCalculatedAttributeForProfileItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "Items": List[ListDomainItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfileObjectTypesResponseTypeDef = TypedDict(
     "ListProfileObjectTypesResponseTypeDef",
     {
         "Items": List[ListProfileObjectTypeItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfileObjectTypeTemplatesResponseTypeDef = TypedDict(
     "ListProfileObjectTypeTemplatesResponseTypeDef",
     {
         "Items": List[ListProfileObjectTypeTemplateItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfileObjectsResponseTypeDef = TypedDict(
     "ListProfileObjectsResponseTypeDef",
     {
         "Items": List[ListProfileObjectsItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListProfileObjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListProfileObjectsRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1543,15 +1932,15 @@
 
 
 ListWorkflowsResponseTypeDef = TypedDict(
     "ListWorkflowsResponseTypeDef",
     {
         "Items": List[ListWorkflowsItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TriggerPropertiesTypeDef = TypedDict(
     "TriggerPropertiesTypeDef",
     {
         "Scheduled": ScheduledTriggerPropertiesTypeDef,
@@ -1622,26 +2011,136 @@
         "WorkflowType": Literal["APPFLOW_INTEGRATION"],
         "Status": StatusType,
         "ErrorDescription": str,
         "StartDate": datetime,
         "LastUpdatedAt": datetime,
         "Attributes": WorkflowAttributesTypeDef,
         "Metrics": WorkflowMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowStepsResponseTypeDef = TypedDict(
     "GetWorkflowStepsResponseTypeDef",
     {
         "WorkflowId": str,
         "WorkflowType": Literal["APPFLOW_INTEGRATION"],
         "Items": List[WorkflowStepItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Statistic": StatisticType,
+    },
+)
+_OptionalCreateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DisplayName": str,
+        "Description": str,
+        "Conditions": ConditionsTypeDef,
+        "Tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class CreateCalculatedAttributeDefinitionRequestRequestTypeDef(
+    _RequiredCreateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    _OptionalCreateCalculatedAttributeDefinitionRequestRequestTypeDef,
+):
+    pass
+
+
+CreateCalculatedAttributeDefinitionResponseTypeDef = TypedDict(
+    "CreateCalculatedAttributeDefinitionResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Conditions": ConditionsTypeDef,
+        "Statistic": StatisticType,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCalculatedAttributeDefinitionResponseTypeDef = TypedDict(
+    "GetCalculatedAttributeDefinitionResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Statistic": StatisticType,
+        "Conditions": ConditionsTypeDef,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUpdateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+    },
+)
+_OptionalUpdateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DisplayName": str,
+        "Description": str,
+        "Conditions": ConditionsTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateCalculatedAttributeDefinitionRequestRequestTypeDef(
+    _RequiredUpdateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    _OptionalUpdateCalculatedAttributeDefinitionRequestRequestTypeDef,
+):
+    pass
+
+
+UpdateCalculatedAttributeDefinitionResponseTypeDef = TypedDict(
+    "UpdateCalculatedAttributeDefinitionResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Statistic": StatisticType,
+        "Conditions": ConditionsTypeDef,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListEventStreamsResponseTypeDef = TypedDict(
+    "ListEventStreamsResponseTypeDef",
+    {
+        "Items": List[EventStreamSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMatchingRequestTypeDef = TypedDict(
     "_RequiredMatchingRequestTypeDef",
     {
         "Enabled": bool,
@@ -1683,15 +2182,15 @@
         "JobStartTime": datetime,
         "JobEndTime": datetime,
         "LastUpdatedAt": datetime,
         "JobExpirationTime": datetime,
         "AutoMerging": AutoMergingTypeDef,
         "ExportingLocation": ExportingLocationTypeDef,
         "JobStats": JobStatsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IdentityResolutionJobTypeDef = TypedDict(
     "IdentityResolutionJobTypeDef",
     {
         "DomainName": str,
@@ -1707,15 +2206,15 @@
 )
 
 SearchProfilesResponseTypeDef = TypedDict(
     "SearchProfilesResponseTypeDef",
     {
         "Items": List[ProfileTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTriggerConfigTypeDef = TypedDict(
     "_RequiredTriggerConfigTypeDef",
     {
         "TriggerType": TriggerTypeType,
@@ -1812,15 +2311,15 @@
         "DefaultExpirationDays": int,
         "DefaultEncryptionKey": str,
         "DeadLetterQueueUrl": str,
         "Matching": MatchingResponseTypeDef,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainResponseTypeDef = TypedDict(
     "GetDomainResponseTypeDef",
     {
         "DomainName": str,
@@ -1828,39 +2327,39 @@
         "DefaultEncryptionKey": str,
         "DeadLetterQueueUrl": str,
         "Stats": DomainStatsTypeDef,
         "Matching": MatchingResponseTypeDef,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainResponseTypeDef = TypedDict(
     "UpdateDomainResponseTypeDef",
     {
         "DomainName": str,
         "DefaultExpirationDays": int,
         "DefaultEncryptionKey": str,
         "DeadLetterQueueUrl": str,
         "Matching": MatchingResponseTypeDef,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityResolutionJobsResponseTypeDef = TypedDict(
     "ListIdentityResolutionJobsResponseTypeDef",
     {
         "IdentityResolutionJobsList": List[IdentityResolutionJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFlowDefinitionTypeDef = TypedDict(
     "_RequiredFlowDefinitionTypeDef",
     {
         "FlowName": str,
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles/type_defs.pyi` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles/type_defs.pyi`

 * *Files 24% similar despite different names*

```diff
@@ -14,26 +14,30 @@
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     ConflictResolvingModelType,
     DataPullModeType,
+    EventStreamDestinationStatusType,
+    EventStreamStateType,
     FieldContentTypeType,
     GenderType,
     IdentityResolutionJobStatusType,
     JobScheduleDayOfTheWeekType,
     MarketoConnectorOperatorType,
     OperatorPropertiesKeysType,
+    OperatorType,
     PartyTypeType,
     S3ConnectorOperatorType,
     SalesforceConnectorOperatorType,
     ServiceNowConnectorOperatorType,
     SourceConnectorTypeType,
     StandardIdentifierType,
+    StatisticType,
     StatusType,
     TaskTypeType,
     TriggerTypeType,
     ZendeskConnectorOperatorType,
     logicalOperatorType,
 )
 
@@ -44,121 +48,153 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AddProfileKeyRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddProfileKeyResponseTypeDef",
     "AdditionalSearchKeyTypeDef",
     "AddressTypeDef",
     "BatchTypeDef",
     "AppflowIntegrationWorkflowAttributesTypeDef",
     "AppflowIntegrationWorkflowMetricsTypeDef",
     "AppflowIntegrationWorkflowStepTypeDef",
+    "AttributeItemTypeDef",
     "ConflictResolutionTypeDef",
     "ConsolidationTypeDef",
+    "RangeTypeDef",
+    "ThresholdTypeDef",
     "ConnectorOperatorTypeDef",
+    "CreateEventStreamRequestRequestTypeDef",
+    "CreateEventStreamResponseTypeDef",
+    "CreateIntegrationWorkflowResponseTypeDef",
+    "CreateProfileResponseTypeDef",
+    "DeleteCalculatedAttributeDefinitionRequestRequestTypeDef",
     "DeleteDomainRequestRequestTypeDef",
+    "DeleteDomainResponseTypeDef",
+    "DeleteEventStreamRequestRequestTypeDef",
     "DeleteIntegrationRequestRequestTypeDef",
+    "DeleteIntegrationResponseTypeDef",
     "DeleteProfileKeyRequestRequestTypeDef",
+    "DeleteProfileKeyResponseTypeDef",
     "DeleteProfileObjectRequestRequestTypeDef",
+    "DeleteProfileObjectResponseTypeDef",
     "DeleteProfileObjectTypeRequestRequestTypeDef",
+    "DeleteProfileObjectTypeResponseTypeDef",
     "DeleteProfileRequestRequestTypeDef",
+    "DeleteProfileResponseTypeDef",
     "DeleteWorkflowRequestRequestTypeDef",
+    "DestinationSummaryTypeDef",
     "DomainStatsTypeDef",
+    "EventStreamDestinationDetailsTypeDef",
     "S3ExportingConfigTypeDef",
     "S3ExportingLocationTypeDef",
     "FieldSourceProfileIdsTypeDef",
     "FoundByKeyValueTypeDef",
+    "GetAutoMergingPreviewResponseTypeDef",
+    "GetCalculatedAttributeDefinitionRequestRequestTypeDef",
+    "GetCalculatedAttributeForProfileRequestRequestTypeDef",
+    "GetCalculatedAttributeForProfileResponseTypeDef",
     "GetDomainRequestRequestTypeDef",
+    "GetEventStreamRequestRequestTypeDef",
     "GetIdentityResolutionJobRequestRequestTypeDef",
     "JobStatsTypeDef",
     "GetIntegrationRequestRequestTypeDef",
+    "GetIntegrationResponseTypeDef",
     "GetMatchesRequestRequestTypeDef",
     "MatchItemTypeDef",
     "GetProfileObjectTypeRequestRequestTypeDef",
     "ObjectTypeFieldTypeDef",
     "ObjectTypeKeyTypeDef",
     "GetProfileObjectTypeTemplateRequestRequestTypeDef",
     "GetWorkflowRequestRequestTypeDef",
     "GetWorkflowStepsRequestRequestTypeDef",
     "IncrementalPullConfigTypeDef",
     "JobScheduleTypeDef",
     "ListAccountIntegrationsRequestRequestTypeDef",
     "ListIntegrationItemTypeDef",
+    "ListCalculatedAttributeDefinitionItemTypeDef",
+    "ListCalculatedAttributeDefinitionsRequestRequestTypeDef",
+    "ListCalculatedAttributeForProfileItemTypeDef",
+    "ListCalculatedAttributesForProfileRequestRequestTypeDef",
     "ListDomainItemTypeDef",
     "ListDomainsRequestRequestTypeDef",
+    "ListEventStreamsRequestListEventStreamsPaginateTypeDef",
+    "ListEventStreamsRequestRequestTypeDef",
     "ListIdentityResolutionJobsRequestRequestTypeDef",
     "ListIntegrationsRequestRequestTypeDef",
     "ListProfileObjectTypeItemTypeDef",
     "ListProfileObjectTypeTemplateItemTypeDef",
     "ListProfileObjectTypeTemplatesRequestRequestTypeDef",
     "ListProfileObjectTypesRequestRequestTypeDef",
     "ListProfileObjectsItemTypeDef",
     "ObjectFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "ListWorkflowsItemTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
     "MarketoSourcePropertiesTypeDef",
+    "MergeProfilesResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutIntegrationResponseTypeDef",
     "PutProfileObjectRequestRequestTypeDef",
+    "PutProfileObjectResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "S3SourcePropertiesTypeDef",
     "SalesforceSourcePropertiesTypeDef",
     "ScheduledTriggerPropertiesTypeDef",
     "ServiceNowSourcePropertiesTypeDef",
     "ZendeskSourcePropertiesTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAddressTypeDef",
-    "AddProfileKeyResponseTypeDef",
-    "CreateIntegrationWorkflowResponseTypeDef",
-    "CreateProfileResponseTypeDef",
-    "DeleteDomainResponseTypeDef",
-    "DeleteIntegrationResponseTypeDef",
-    "DeleteProfileKeyResponseTypeDef",
-    "DeleteProfileObjectResponseTypeDef",
-    "DeleteProfileObjectTypeResponseTypeDef",
-    "DeleteProfileResponseTypeDef",
-    "GetAutoMergingPreviewResponseTypeDef",
-    "GetIntegrationResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "MergeProfilesResponseTypeDef",
-    "PutIntegrationResponseTypeDef",
-    "PutProfileObjectResponseTypeDef",
     "UpdateProfileResponseTypeDef",
     "SearchProfilesRequestRequestTypeDef",
     "CreateProfileRequestRequestTypeDef",
     "WorkflowAttributesTypeDef",
     "WorkflowMetricsTypeDef",
     "WorkflowStepItemTypeDef",
+    "AttributeDetailsTypeDef",
     "AutoMergingTypeDef",
     "GetAutoMergingPreviewRequestRequestTypeDef",
+    "ConditionsTypeDef",
     "TaskTypeDef",
+    "EventStreamSummaryTypeDef",
+    "GetEventStreamResponseTypeDef",
     "ExportingConfigTypeDef",
     "ExportingLocationTypeDef",
     "MergeProfilesRequestRequestTypeDef",
     "ProfileTypeDef",
     "GetMatchesResponseTypeDef",
     "GetProfileObjectTypeResponseTypeDef",
     "GetProfileObjectTypeTemplateResponseTypeDef",
     "PutProfileObjectTypeRequestRequestTypeDef",
     "PutProfileObjectTypeResponseTypeDef",
     "ListAccountIntegrationsResponseTypeDef",
     "ListIntegrationsResponseTypeDef",
+    "ListCalculatedAttributeDefinitionsResponseTypeDef",
+    "ListCalculatedAttributesForProfileResponseTypeDef",
     "ListDomainsResponseTypeDef",
     "ListProfileObjectTypesResponseTypeDef",
     "ListProfileObjectTypeTemplatesResponseTypeDef",
     "ListProfileObjectsResponseTypeDef",
     "ListProfileObjectsRequestRequestTypeDef",
     "ListWorkflowsResponseTypeDef",
     "TriggerPropertiesTypeDef",
     "SourceConnectorPropertiesTypeDef",
     "UpdateProfileRequestRequestTypeDef",
     "GetWorkflowResponseTypeDef",
     "GetWorkflowStepsResponseTypeDef",
+    "CreateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    "CreateCalculatedAttributeDefinitionResponseTypeDef",
+    "GetCalculatedAttributeDefinitionResponseTypeDef",
+    "UpdateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    "UpdateCalculatedAttributeDefinitionResponseTypeDef",
+    "ListEventStreamsResponseTypeDef",
     "MatchingRequestTypeDef",
     "MatchingResponseTypeDef",
     "GetIdentityResolutionJobResponseTypeDef",
     "IdentityResolutionJobTypeDef",
     "SearchProfilesResponseTypeDef",
     "TriggerConfigTypeDef",
     "SourceFlowConfigTypeDef",
@@ -181,22 +217,20 @@
         "ProfileId": str,
         "KeyName": str,
         "Values": Sequence[str],
         "DomainName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddProfileKeyResponseTypeDef = TypedDict(
+    "AddProfileKeyResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "KeyName": str,
+        "Values": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdditionalSearchKeyTypeDef = TypedDict(
     "AdditionalSearchKeyTypeDef",
     {
         "KeyName": str,
@@ -269,14 +303,21 @@
         "BatchRecordsStartTime": str,
         "BatchRecordsEndTime": str,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
     },
 )
 
+AttributeItemTypeDef = TypedDict(
+    "AttributeItemTypeDef",
+    {
+        "Name": str,
+    },
+)
+
 _RequiredConflictResolutionTypeDef = TypedDict(
     "_RequiredConflictResolutionTypeDef",
     {
         "ConflictResolvingModel": ConflictResolvingModelType,
     },
 )
 _OptionalConflictResolutionTypeDef = TypedDict(
@@ -295,96 +336,264 @@
 ConsolidationTypeDef = TypedDict(
     "ConsolidationTypeDef",
     {
         "MatchingAttributesList": Sequence[Sequence[str]],
     },
 )
 
+RangeTypeDef = TypedDict(
+    "RangeTypeDef",
+    {
+        "Value": int,
+        "Unit": Literal["DAYS"],
+    },
+)
+
+ThresholdTypeDef = TypedDict(
+    "ThresholdTypeDef",
+    {
+        "Value": str,
+        "Operator": OperatorType,
+    },
+)
+
 ConnectorOperatorTypeDef = TypedDict(
     "ConnectorOperatorTypeDef",
     {
         "Marketo": MarketoConnectorOperatorType,
         "S3": S3ConnectorOperatorType,
         "Salesforce": SalesforceConnectorOperatorType,
         "ServiceNow": ServiceNowConnectorOperatorType,
         "Zendesk": ZendeskConnectorOperatorType,
     },
     total=False,
 )
 
+_RequiredCreateEventStreamRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateEventStreamRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "Uri": str,
+        "EventStreamName": str,
+    },
+)
+_OptionalCreateEventStreamRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateEventStreamRequestRequestTypeDef",
+    {
+        "Tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+class CreateEventStreamRequestRequestTypeDef(
+    _RequiredCreateEventStreamRequestRequestTypeDef, _OptionalCreateEventStreamRequestRequestTypeDef
+):
+    pass
+
+CreateEventStreamResponseTypeDef = TypedDict(
+    "CreateEventStreamResponseTypeDef",
+    {
+        "EventStreamArn": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateIntegrationWorkflowResponseTypeDef = TypedDict(
+    "CreateIntegrationWorkflowResponseTypeDef",
+    {
+        "WorkflowId": str,
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProfileResponseTypeDef = TypedDict(
+    "CreateProfileResponseTypeDef",
+    {
+        "ProfileId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "DeleteCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+    },
+)
+
 DeleteDomainRequestRequestTypeDef = TypedDict(
     "DeleteDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DeleteDomainResponseTypeDef = TypedDict(
+    "DeleteDomainResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteEventStreamRequestRequestTypeDef = TypedDict(
+    "DeleteEventStreamRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamName": str,
+    },
+)
+
 DeleteIntegrationRequestRequestTypeDef = TypedDict(
     "DeleteIntegrationRequestRequestTypeDef",
     {
         "DomainName": str,
         "Uri": str,
     },
 )
 
+DeleteIntegrationResponseTypeDef = TypedDict(
+    "DeleteIntegrationResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileKeyRequestRequestTypeDef = TypedDict(
     "DeleteProfileKeyRequestRequestTypeDef",
     {
         "ProfileId": str,
         "KeyName": str,
         "Values": Sequence[str],
         "DomainName": str,
     },
 )
 
+DeleteProfileKeyResponseTypeDef = TypedDict(
+    "DeleteProfileKeyResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileObjectRequestRequestTypeDef = TypedDict(
     "DeleteProfileObjectRequestRequestTypeDef",
     {
         "ProfileId": str,
         "ProfileObjectUniqueKey": str,
         "ObjectTypeName": str,
         "DomainName": str,
     },
 )
 
+DeleteProfileObjectResponseTypeDef = TypedDict(
+    "DeleteProfileObjectResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileObjectTypeRequestRequestTypeDef = TypedDict(
     "DeleteProfileObjectTypeRequestRequestTypeDef",
     {
         "DomainName": str,
         "ObjectTypeName": str,
     },
 )
 
+DeleteProfileObjectTypeResponseTypeDef = TypedDict(
+    "DeleteProfileObjectTypeResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteProfileRequestRequestTypeDef = TypedDict(
     "DeleteProfileRequestRequestTypeDef",
     {
         "ProfileId": str,
         "DomainName": str,
     },
 )
 
+DeleteProfileResponseTypeDef = TypedDict(
+    "DeleteProfileResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowRequestRequestTypeDef",
     {
         "DomainName": str,
         "WorkflowId": str,
     },
 )
 
+_RequiredDestinationSummaryTypeDef = TypedDict(
+    "_RequiredDestinationSummaryTypeDef",
+    {
+        "Uri": str,
+        "Status": EventStreamDestinationStatusType,
+    },
+)
+_OptionalDestinationSummaryTypeDef = TypedDict(
+    "_OptionalDestinationSummaryTypeDef",
+    {
+        "UnhealthySince": datetime,
+    },
+    total=False,
+)
+
+class DestinationSummaryTypeDef(
+    _RequiredDestinationSummaryTypeDef, _OptionalDestinationSummaryTypeDef
+):
+    pass
+
 DomainStatsTypeDef = TypedDict(
     "DomainStatsTypeDef",
     {
         "ProfileCount": int,
         "MeteringProfileCount": int,
         "ObjectCount": int,
         "TotalSize": int,
     },
     total=False,
 )
 
+_RequiredEventStreamDestinationDetailsTypeDef = TypedDict(
+    "_RequiredEventStreamDestinationDetailsTypeDef",
+    {
+        "Uri": str,
+        "Status": EventStreamDestinationStatusType,
+    },
+)
+_OptionalEventStreamDestinationDetailsTypeDef = TypedDict(
+    "_OptionalEventStreamDestinationDetailsTypeDef",
+    {
+        "UnhealthySince": datetime,
+        "Message": str,
+    },
+    total=False,
+)
+
+class EventStreamDestinationDetailsTypeDef(
+    _RequiredEventStreamDestinationDetailsTypeDef, _OptionalEventStreamDestinationDetailsTypeDef
+):
+    pass
+
 _RequiredS3ExportingConfigTypeDef = TypedDict(
     "_RequiredS3ExportingConfigTypeDef",
     {
         "S3BucketName": str,
     },
 )
 _OptionalS3ExportingConfigTypeDef = TypedDict(
@@ -442,21 +651,68 @@
     {
         "KeyName": str,
         "Values": List[str],
     },
     total=False,
 )
 
+GetAutoMergingPreviewResponseTypeDef = TypedDict(
+    "GetAutoMergingPreviewResponseTypeDef",
+    {
+        "DomainName": str,
+        "NumberOfMatchesInSample": int,
+        "NumberOfProfilesInSample": int,
+        "NumberOfProfilesWillBeMerged": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "GetCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+    },
+)
+
+GetCalculatedAttributeForProfileRequestRequestTypeDef = TypedDict(
+    "GetCalculatedAttributeForProfileRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "ProfileId": str,
+        "CalculatedAttributeName": str,
+    },
+)
+
+GetCalculatedAttributeForProfileResponseTypeDef = TypedDict(
+    "GetCalculatedAttributeForProfileResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "IsDataPartial": str,
+        "Value": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDomainRequestRequestTypeDef = TypedDict(
     "GetDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetEventStreamRequestRequestTypeDef = TypedDict(
+    "GetEventStreamRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamName": str,
+    },
+)
+
 GetIdentityResolutionJobRequestRequestTypeDef = TypedDict(
     "GetIdentityResolutionJobRequestRequestTypeDef",
     {
         "DomainName": str,
         "JobId": str,
     },
 )
@@ -475,14 +731,30 @@
     "GetIntegrationRequestRequestTypeDef",
     {
         "DomainName": str,
         "Uri": str,
     },
 )
 
+GetIntegrationResponseTypeDef = TypedDict(
+    "GetIntegrationResponseTypeDef",
+    {
+        "DomainName": str,
+        "Uri": str,
+        "ObjectTypeName": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+        "ObjectTypeNames": Dict[str, str],
+        "WorkflowId": str,
+        "IsUnstructured": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetMatchesRequestRequestTypeDef = TypedDict(
     "_RequiredGetMatchesRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalGetMatchesRequestRequestTypeDef = TypedDict(
@@ -632,14 +904,81 @@
 )
 
 class ListIntegrationItemTypeDef(
     _RequiredListIntegrationItemTypeDef, _OptionalListIntegrationItemTypeDef
 ):
     pass
 
+ListCalculatedAttributeDefinitionItemTypeDef = TypedDict(
+    "ListCalculatedAttributeDefinitionItemTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+    },
+    total=False,
+)
+
+_RequiredListCalculatedAttributeDefinitionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListCalculatedAttributeDefinitionsRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListCalculatedAttributeDefinitionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListCalculatedAttributeDefinitionsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class ListCalculatedAttributeDefinitionsRequestRequestTypeDef(
+    _RequiredListCalculatedAttributeDefinitionsRequestRequestTypeDef,
+    _OptionalListCalculatedAttributeDefinitionsRequestRequestTypeDef,
+):
+    pass
+
+ListCalculatedAttributeForProfileItemTypeDef = TypedDict(
+    "ListCalculatedAttributeForProfileItemTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "IsDataPartial": str,
+        "Value": str,
+    },
+    total=False,
+)
+
+_RequiredListCalculatedAttributesForProfileRequestRequestTypeDef = TypedDict(
+    "_RequiredListCalculatedAttributesForProfileRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "ProfileId": str,
+    },
+)
+_OptionalListCalculatedAttributesForProfileRequestRequestTypeDef = TypedDict(
+    "_OptionalListCalculatedAttributesForProfileRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class ListCalculatedAttributesForProfileRequestRequestTypeDef(
+    _RequiredListCalculatedAttributesForProfileRequestRequestTypeDef,
+    _OptionalListCalculatedAttributesForProfileRequestRequestTypeDef,
+):
+    pass
+
 _RequiredListDomainItemTypeDef = TypedDict(
     "_RequiredListDomainItemTypeDef",
     {
         "DomainName": str,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
     },
@@ -660,14 +999,54 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+_RequiredListEventStreamsRequestListEventStreamsPaginateTypeDef = TypedDict(
+    "_RequiredListEventStreamsRequestListEventStreamsPaginateTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListEventStreamsRequestListEventStreamsPaginateTypeDef = TypedDict(
+    "_OptionalListEventStreamsRequestListEventStreamsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListEventStreamsRequestListEventStreamsPaginateTypeDef(
+    _RequiredListEventStreamsRequestListEventStreamsPaginateTypeDef,
+    _OptionalListEventStreamsRequestListEventStreamsPaginateTypeDef,
+):
+    pass
+
+_RequiredListEventStreamsRequestRequestTypeDef = TypedDict(
+    "_RequiredListEventStreamsRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListEventStreamsRequestRequestTypeDef = TypedDict(
+    "_OptionalListEventStreamsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class ListEventStreamsRequestRequestTypeDef(
+    _RequiredListEventStreamsRequestRequestTypeDef, _OptionalListEventStreamsRequestRequestTypeDef
+):
+    pass
+
 _RequiredListIdentityResolutionJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListIdentityResolutionJobsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListIdentityResolutionJobsRequestRequestTypeDef = TypedDict(
@@ -789,14 +1168,22 @@
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
 ListWorkflowsItemTypeDef = TypedDict(
     "ListWorkflowsItemTypeDef",
     {
         "WorkflowType": Literal["APPFLOW_INTEGRATION"],
         "WorkflowId": str,
         "Status": StatusType,
         "StatusDescription": str,
@@ -832,23 +1219,76 @@
 MarketoSourcePropertiesTypeDef = TypedDict(
     "MarketoSourcePropertiesTypeDef",
     {
         "Object": str,
     },
 )
 
+MergeProfilesResponseTypeDef = TypedDict(
+    "MergeProfilesResponseTypeDef",
+    {
+        "Message": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
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
+PutIntegrationResponseTypeDef = TypedDict(
+    "PutIntegrationResponseTypeDef",
+    {
+        "DomainName": str,
+        "Uri": str,
+        "ObjectTypeName": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+        "ObjectTypeNames": Dict[str, str],
+        "WorkflowId": str,
+        "IsUnstructured": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutProfileObjectRequestRequestTypeDef = TypedDict(
     "PutProfileObjectRequestRequestTypeDef",
     {
         "ObjectTypeName": str,
         "Object": str,
         "DomainName": str,
     },
 )
 
+PutProfileObjectResponseTypeDef = TypedDict(
+    "PutProfileObjectResponseTypeDef",
+    {
+        "ProfileObjectUniqueKey": str,
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
 _RequiredS3SourcePropertiesTypeDef = TypedDict(
     "_RequiredS3SourcePropertiesTypeDef",
     {
         "BucketName": str,
     },
 )
 _OptionalS3SourcePropertiesTypeDef = TypedDict(
@@ -951,160 +1391,19 @@
         "Province": str,
         "Country": str,
         "PostalCode": str,
     },
     total=False,
 )
 
-AddProfileKeyResponseTypeDef = TypedDict(
-    "AddProfileKeyResponseTypeDef",
-    {
-        "KeyName": str,
-        "Values": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIntegrationWorkflowResponseTypeDef = TypedDict(
-    "CreateIntegrationWorkflowResponseTypeDef",
-    {
-        "WorkflowId": str,
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateProfileResponseTypeDef = TypedDict(
-    "CreateProfileResponseTypeDef",
-    {
-        "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDomainResponseTypeDef = TypedDict(
-    "DeleteDomainResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteIntegrationResponseTypeDef = TypedDict(
-    "DeleteIntegrationResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileKeyResponseTypeDef = TypedDict(
-    "DeleteProfileKeyResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileObjectResponseTypeDef = TypedDict(
-    "DeleteProfileObjectResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileObjectTypeResponseTypeDef = TypedDict(
-    "DeleteProfileObjectTypeResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteProfileResponseTypeDef = TypedDict(
-    "DeleteProfileResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAutoMergingPreviewResponseTypeDef = TypedDict(
-    "GetAutoMergingPreviewResponseTypeDef",
-    {
-        "DomainName": str,
-        "NumberOfMatchesInSample": int,
-        "NumberOfProfilesInSample": int,
-        "NumberOfProfilesWillBeMerged": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIntegrationResponseTypeDef = TypedDict(
-    "GetIntegrationResponseTypeDef",
-    {
-        "DomainName": str,
-        "Uri": str,
-        "ObjectTypeName": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "Tags": Dict[str, str],
-        "ObjectTypeNames": Dict[str, str],
-        "WorkflowId": str,
-        "IsUnstructured": bool,
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
-MergeProfilesResponseTypeDef = TypedDict(
-    "MergeProfilesResponseTypeDef",
-    {
-        "Message": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutIntegrationResponseTypeDef = TypedDict(
-    "PutIntegrationResponseTypeDef",
-    {
-        "DomainName": str,
-        "Uri": str,
-        "ObjectTypeName": str,
-        "CreatedAt": datetime,
-        "LastUpdatedAt": datetime,
-        "Tags": Dict[str, str],
-        "ObjectTypeNames": Dict[str, str],
-        "WorkflowId": str,
-        "IsUnstructured": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutProfileObjectResponseTypeDef = TypedDict(
-    "PutProfileObjectResponseTypeDef",
-    {
-        "ProfileObjectUniqueKey": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateProfileResponseTypeDef = TypedDict(
     "UpdateProfileResponseTypeDef",
     {
         "ProfileId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredSearchProfilesRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1189,14 +1488,22 @@
     "WorkflowStepItemTypeDef",
     {
         "AppflowIntegration": AppflowIntegrationWorkflowStepTypeDef,
     },
     total=False,
 )
 
+AttributeDetailsTypeDef = TypedDict(
+    "AttributeDetailsTypeDef",
+    {
+        "Attributes": Sequence[AttributeItemTypeDef],
+        "Expression": str,
+    },
+)
+
 _RequiredAutoMergingTypeDef = TypedDict(
     "_RequiredAutoMergingTypeDef",
     {
         "Enabled": bool,
     },
 )
 _OptionalAutoMergingTypeDef = TypedDict(
@@ -1230,14 +1537,24 @@
 
 class GetAutoMergingPreviewRequestRequestTypeDef(
     _RequiredGetAutoMergingPreviewRequestRequestTypeDef,
     _OptionalGetAutoMergingPreviewRequestRequestTypeDef,
 ):
     pass
 
+ConditionsTypeDef = TypedDict(
+    "ConditionsTypeDef",
+    {
+        "Range": RangeTypeDef,
+        "ObjectCount": int,
+        "Threshold": ThresholdTypeDef,
+    },
+    total=False,
+)
+
 _RequiredTaskTypeDef = TypedDict(
     "_RequiredTaskTypeDef",
     {
         "SourceFields": Sequence[str],
         "TaskType": TaskTypeType,
     },
 )
@@ -1250,14 +1567,52 @@
     },
     total=False,
 )
 
 class TaskTypeDef(_RequiredTaskTypeDef, _OptionalTaskTypeDef):
     pass
 
+_RequiredEventStreamSummaryTypeDef = TypedDict(
+    "_RequiredEventStreamSummaryTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamName": str,
+        "EventStreamArn": str,
+        "State": EventStreamStateType,
+    },
+)
+_OptionalEventStreamSummaryTypeDef = TypedDict(
+    "_OptionalEventStreamSummaryTypeDef",
+    {
+        "StoppedSince": datetime,
+        "DestinationSummary": DestinationSummaryTypeDef,
+        "Tags": Dict[str, str],
+    },
+    total=False,
+)
+
+class EventStreamSummaryTypeDef(
+    _RequiredEventStreamSummaryTypeDef, _OptionalEventStreamSummaryTypeDef
+):
+    pass
+
+GetEventStreamResponseTypeDef = TypedDict(
+    "GetEventStreamResponseTypeDef",
+    {
+        "DomainName": str,
+        "EventStreamArn": str,
+        "CreatedAt": datetime,
+        "State": EventStreamStateType,
+        "StoppedSince": datetime,
+        "DestinationDetails": EventStreamDestinationDetailsTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportingConfigTypeDef = TypedDict(
     "ExportingConfigTypeDef",
     {
         "S3Exporting": S3ExportingConfigTypeDef,
     },
     total=False,
 )
@@ -1326,15 +1681,15 @@
 GetMatchesResponseTypeDef = TypedDict(
     "GetMatchesResponseTypeDef",
     {
         "NextToken": str,
         "MatchGenerationDate": datetime,
         "PotentialMatches": int,
         "Matches": List[MatchItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProfileObjectTypeResponseTypeDef = TypedDict(
     "GetProfileObjectTypeResponseTypeDef",
     {
         "ObjectTypeName": str,
@@ -1345,29 +1700,29 @@
         "AllowProfileCreation": bool,
         "SourceLastUpdatedTimestampFormat": str,
         "Fields": Dict[str, ObjectTypeFieldTypeDef],
         "Keys": Dict[str, List[ObjectTypeKeyTypeDef]],
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProfileObjectTypeTemplateResponseTypeDef = TypedDict(
     "GetProfileObjectTypeTemplateResponseTypeDef",
     {
         "TemplateId": str,
         "SourceName": str,
         "SourceObject": str,
         "AllowProfileCreation": bool,
         "SourceLastUpdatedTimestampFormat": str,
         "Fields": Dict[str, ObjectTypeFieldTypeDef],
         "Keys": Dict[str, List[ObjectTypeKeyTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutProfileObjectTypeRequestRequestTypeDef = TypedDict(
     "_RequiredPutProfileObjectTypeRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1407,69 +1762,87 @@
         "AllowProfileCreation": bool,
         "SourceLastUpdatedTimestampFormat": str,
         "Fields": Dict[str, ObjectTypeFieldTypeDef],
         "Keys": Dict[str, List[ObjectTypeKeyTypeDef]],
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountIntegrationsResponseTypeDef = TypedDict(
     "ListAccountIntegrationsResponseTypeDef",
     {
         "Items": List[ListIntegrationItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIntegrationsResponseTypeDef = TypedDict(
     "ListIntegrationsResponseTypeDef",
     {
         "Items": List[ListIntegrationItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCalculatedAttributeDefinitionsResponseTypeDef = TypedDict(
+    "ListCalculatedAttributeDefinitionsResponseTypeDef",
+    {
+        "Items": List[ListCalculatedAttributeDefinitionItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCalculatedAttributesForProfileResponseTypeDef = TypedDict(
+    "ListCalculatedAttributesForProfileResponseTypeDef",
+    {
+        "Items": List[ListCalculatedAttributeForProfileItemTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsResponseTypeDef = TypedDict(
     "ListDomainsResponseTypeDef",
     {
         "Items": List[ListDomainItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfileObjectTypesResponseTypeDef = TypedDict(
     "ListProfileObjectTypesResponseTypeDef",
     {
         "Items": List[ListProfileObjectTypeItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfileObjectTypeTemplatesResponseTypeDef = TypedDict(
     "ListProfileObjectTypeTemplatesResponseTypeDef",
     {
         "Items": List[ListProfileObjectTypeTemplateItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProfileObjectsResponseTypeDef = TypedDict(
     "ListProfileObjectsResponseTypeDef",
     {
         "Items": List[ListProfileObjectsItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListProfileObjectsRequestRequestTypeDef = TypedDict(
     "_RequiredListProfileObjectsRequestRequestTypeDef",
     {
         "DomainName": str,
@@ -1494,15 +1867,15 @@
     pass
 
 ListWorkflowsResponseTypeDef = TypedDict(
     "ListWorkflowsResponseTypeDef",
     {
         "Items": List[ListWorkflowsItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TriggerPropertiesTypeDef = TypedDict(
     "TriggerPropertiesTypeDef",
     {
         "Scheduled": ScheduledTriggerPropertiesTypeDef,
@@ -1571,26 +1944,132 @@
         "WorkflowType": Literal["APPFLOW_INTEGRATION"],
         "Status": StatusType,
         "ErrorDescription": str,
         "StartDate": datetime,
         "LastUpdatedAt": datetime,
         "Attributes": WorkflowAttributesTypeDef,
         "Metrics": WorkflowMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowStepsResponseTypeDef = TypedDict(
     "GetWorkflowStepsResponseTypeDef",
     {
         "WorkflowId": str,
         "WorkflowType": Literal["APPFLOW_INTEGRATION"],
         "Items": List[WorkflowStepItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Statistic": StatisticType,
+    },
+)
+_OptionalCreateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DisplayName": str,
+        "Description": str,
+        "Conditions": ConditionsTypeDef,
+        "Tags": Mapping[str, str],
+    },
+    total=False,
+)
+
+class CreateCalculatedAttributeDefinitionRequestRequestTypeDef(
+    _RequiredCreateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    _OptionalCreateCalculatedAttributeDefinitionRequestRequestTypeDef,
+):
+    pass
+
+CreateCalculatedAttributeDefinitionResponseTypeDef = TypedDict(
+    "CreateCalculatedAttributeDefinitionResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Conditions": ConditionsTypeDef,
+        "Statistic": StatisticType,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetCalculatedAttributeDefinitionResponseTypeDef = TypedDict(
+    "GetCalculatedAttributeDefinitionResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Statistic": StatisticType,
+        "Conditions": ConditionsTypeDef,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUpdateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "CalculatedAttributeName": str,
+    },
+)
+_OptionalUpdateCalculatedAttributeDefinitionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateCalculatedAttributeDefinitionRequestRequestTypeDef",
+    {
+        "DisplayName": str,
+        "Description": str,
+        "Conditions": ConditionsTypeDef,
+    },
+    total=False,
+)
+
+class UpdateCalculatedAttributeDefinitionRequestRequestTypeDef(
+    _RequiredUpdateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    _OptionalUpdateCalculatedAttributeDefinitionRequestRequestTypeDef,
+):
+    pass
+
+UpdateCalculatedAttributeDefinitionResponseTypeDef = TypedDict(
+    "UpdateCalculatedAttributeDefinitionResponseTypeDef",
+    {
+        "CalculatedAttributeName": str,
+        "DisplayName": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "LastUpdatedAt": datetime,
+        "Statistic": StatisticType,
+        "Conditions": ConditionsTypeDef,
+        "AttributeDetails": AttributeDetailsTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListEventStreamsResponseTypeDef = TypedDict(
+    "ListEventStreamsResponseTypeDef",
+    {
+        "Items": List[EventStreamSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMatchingRequestTypeDef = TypedDict(
     "_RequiredMatchingRequestTypeDef",
     {
         "Enabled": bool,
@@ -1630,15 +2109,15 @@
         "JobStartTime": datetime,
         "JobEndTime": datetime,
         "LastUpdatedAt": datetime,
         "JobExpirationTime": datetime,
         "AutoMerging": AutoMergingTypeDef,
         "ExportingLocation": ExportingLocationTypeDef,
         "JobStats": JobStatsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IdentityResolutionJobTypeDef = TypedDict(
     "IdentityResolutionJobTypeDef",
     {
         "DomainName": str,
@@ -1654,15 +2133,15 @@
 )
 
 SearchProfilesResponseTypeDef = TypedDict(
     "SearchProfilesResponseTypeDef",
     {
         "Items": List[ProfileTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTriggerConfigTypeDef = TypedDict(
     "_RequiredTriggerConfigTypeDef",
     {
         "TriggerType": TriggerTypeType,
@@ -1751,15 +2230,15 @@
         "DefaultExpirationDays": int,
         "DefaultEncryptionKey": str,
         "DeadLetterQueueUrl": str,
         "Matching": MatchingResponseTypeDef,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainResponseTypeDef = TypedDict(
     "GetDomainResponseTypeDef",
     {
         "DomainName": str,
@@ -1767,39 +2246,39 @@
         "DefaultEncryptionKey": str,
         "DeadLetterQueueUrl": str,
         "Stats": DomainStatsTypeDef,
         "Matching": MatchingResponseTypeDef,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainResponseTypeDef = TypedDict(
     "UpdateDomainResponseTypeDef",
     {
         "DomainName": str,
         "DefaultExpirationDays": int,
         "DefaultEncryptionKey": str,
         "DeadLetterQueueUrl": str,
         "Matching": MatchingResponseTypeDef,
         "CreatedAt": datetime,
         "LastUpdatedAt": datetime,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityResolutionJobsResponseTypeDef = TypedDict(
     "ListIdentityResolutionJobsResponseTypeDef",
     {
         "IdentityResolutionJobsList": List[IdentityResolutionJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFlowDefinitionTypeDef = TypedDict(
     "_RequiredFlowDefinitionTypeDef",
     {
         "FlowName": str,
```

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/PKG-INFO` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-customer-profiles
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CustomerProfiles 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CustomerProfiles 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-customer-profiles"></a>
 
 # types-aiobotocore-customer-profiles
 
 [![PyPI - types-aiobotocore-customer-profiles](https://img.shields.io/pypi/v/types-aiobotocore-customer-profiles.svg?color=blue)](https://pypi.org/project/types-aiobotocore-customer-profiles)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-customer-profiles.svg?color=blue)](https://pypi.org/project/types-aiobotocore-customer-profiles)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-customer-profiles?color=blue)](https://pypistats.org/packages/types-aiobotocore-customer-profiles)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CustomerProfiles 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles)
+[aiobotocore.CustomerProfiles 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/customer-profiles.html#CustomerProfiles)
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
 [types-aiobotocore-customer-profiles docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_customer_profiles/).
 
 See how it helps to find and fix potential bugs:
 
@@ -72,14 +72,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -260,46 +261,77 @@
 
 session = get_session()
 async with session.create_client("customer-profiles") as client:
     client: CustomerProfilesClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_customer_profiles.paginator` module contains type
+annotations for all paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_customer_profiles import CustomerProfilesClient
+from types_aiobotocore_customer_profiles.paginator import ListEventStreamsPaginator
+
+session = get_session()
+async with session.create_client("customer-profiles") as client:
+    client: CustomerProfilesClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_event_streams_paginator: ListEventStreamsPaginator = client.get_paginator(
+        "list_event_streams"
+    )
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_customer_profiles.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_customer_profiles.literals import (
     ConflictResolvingModelType,
     DataPullModeType,
+    EventStreamDestinationStatusType,
+    EventStreamStateType,
     FieldContentTypeType,
     GenderType,
     IdentityResolutionJobStatusType,
     JobScheduleDayOfTheWeekType,
+    ListEventStreamsPaginatorName,
     MarketoConnectorOperatorType,
     OperatorPropertiesKeysType,
+    OperatorType,
     PartyTypeType,
     S3ConnectorOperatorType,
     SalesforceConnectorOperatorType,
     ServiceNowConnectorOperatorType,
     SourceConnectorTypeType,
     StandardIdentifierType,
+    StatisticType,
     StatusType,
     TaskTypeType,
     TriggerTypeType,
+    UnitType,
     WorkflowTypeType,
     ZendeskConnectorOperatorType,
     logicalOperatorType,
     CustomerProfilesServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
     RegionName,
 )
 
 
 def check_value(value: ConflictResolvingModelType) -> bool:
     ...
 ```
@@ -310,121 +342,153 @@
 
 `types_aiobotocore_customer_profiles.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_customer_profiles.type_defs import (
     AddProfileKeyRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddProfileKeyResponseTypeDef,
     AdditionalSearchKeyTypeDef,
     AddressTypeDef,
     BatchTypeDef,
     AppflowIntegrationWorkflowAttributesTypeDef,
     AppflowIntegrationWorkflowMetricsTypeDef,
     AppflowIntegrationWorkflowStepTypeDef,
+    AttributeItemTypeDef,
     ConflictResolutionTypeDef,
     ConsolidationTypeDef,
+    RangeTypeDef,
+    ThresholdTypeDef,
     ConnectorOperatorTypeDef,
+    CreateEventStreamRequestRequestTypeDef,
+    CreateEventStreamResponseTypeDef,
+    CreateIntegrationWorkflowResponseTypeDef,
+    CreateProfileResponseTypeDef,
+    DeleteCalculatedAttributeDefinitionRequestRequestTypeDef,
     DeleteDomainRequestRequestTypeDef,
+    DeleteDomainResponseTypeDef,
+    DeleteEventStreamRequestRequestTypeDef,
     DeleteIntegrationRequestRequestTypeDef,
+    DeleteIntegrationResponseTypeDef,
     DeleteProfileKeyRequestRequestTypeDef,
+    DeleteProfileKeyResponseTypeDef,
     DeleteProfileObjectRequestRequestTypeDef,
+    DeleteProfileObjectResponseTypeDef,
     DeleteProfileObjectTypeRequestRequestTypeDef,
+    DeleteProfileObjectTypeResponseTypeDef,
     DeleteProfileRequestRequestTypeDef,
+    DeleteProfileResponseTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    DestinationSummaryTypeDef,
     DomainStatsTypeDef,
+    EventStreamDestinationDetailsTypeDef,
     S3ExportingConfigTypeDef,
     S3ExportingLocationTypeDef,
     FieldSourceProfileIdsTypeDef,
     FoundByKeyValueTypeDef,
+    GetAutoMergingPreviewResponseTypeDef,
+    GetCalculatedAttributeDefinitionRequestRequestTypeDef,
+    GetCalculatedAttributeForProfileRequestRequestTypeDef,
+    GetCalculatedAttributeForProfileResponseTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetEventStreamRequestRequestTypeDef,
     GetIdentityResolutionJobRequestRequestTypeDef,
     JobStatsTypeDef,
     GetIntegrationRequestRequestTypeDef,
+    GetIntegrationResponseTypeDef,
     GetMatchesRequestRequestTypeDef,
     MatchItemTypeDef,
     GetProfileObjectTypeRequestRequestTypeDef,
     ObjectTypeFieldTypeDef,
     ObjectTypeKeyTypeDef,
     GetProfileObjectTypeTemplateRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     GetWorkflowStepsRequestRequestTypeDef,
     IncrementalPullConfigTypeDef,
     JobScheduleTypeDef,
     ListAccountIntegrationsRequestRequestTypeDef,
     ListIntegrationItemTypeDef,
+    ListCalculatedAttributeDefinitionItemTypeDef,
+    ListCalculatedAttributeDefinitionsRequestRequestTypeDef,
+    ListCalculatedAttributeForProfileItemTypeDef,
+    ListCalculatedAttributesForProfileRequestRequestTypeDef,
     ListDomainItemTypeDef,
     ListDomainsRequestRequestTypeDef,
+    ListEventStreamsRequestListEventStreamsPaginateTypeDef,
+    ListEventStreamsRequestRequestTypeDef,
     ListIdentityResolutionJobsRequestRequestTypeDef,
     ListIntegrationsRequestRequestTypeDef,
     ListProfileObjectTypeItemTypeDef,
     ListProfileObjectTypeTemplateItemTypeDef,
     ListProfileObjectTypeTemplatesRequestRequestTypeDef,
     ListProfileObjectTypesRequestRequestTypeDef,
     ListProfileObjectsItemTypeDef,
     ObjectFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     ListWorkflowsItemTypeDef,
     ListWorkflowsRequestRequestTypeDef,
     MarketoSourcePropertiesTypeDef,
+    MergeProfilesResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutIntegrationResponseTypeDef,
     PutProfileObjectRequestRequestTypeDef,
+    PutProfileObjectResponseTypeDef,
+    ResponseMetadataTypeDef,
     S3SourcePropertiesTypeDef,
     SalesforceSourcePropertiesTypeDef,
     ScheduledTriggerPropertiesTypeDef,
     ServiceNowSourcePropertiesTypeDef,
     ZendeskSourcePropertiesTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAddressTypeDef,
-    AddProfileKeyResponseTypeDef,
-    CreateIntegrationWorkflowResponseTypeDef,
-    CreateProfileResponseTypeDef,
-    DeleteDomainResponseTypeDef,
-    DeleteIntegrationResponseTypeDef,
-    DeleteProfileKeyResponseTypeDef,
-    DeleteProfileObjectResponseTypeDef,
-    DeleteProfileObjectTypeResponseTypeDef,
-    DeleteProfileResponseTypeDef,
-    GetAutoMergingPreviewResponseTypeDef,
-    GetIntegrationResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    MergeProfilesResponseTypeDef,
-    PutIntegrationResponseTypeDef,
-    PutProfileObjectResponseTypeDef,
     UpdateProfileResponseTypeDef,
     SearchProfilesRequestRequestTypeDef,
     CreateProfileRequestRequestTypeDef,
     WorkflowAttributesTypeDef,
     WorkflowMetricsTypeDef,
     WorkflowStepItemTypeDef,
+    AttributeDetailsTypeDef,
     AutoMergingTypeDef,
     GetAutoMergingPreviewRequestRequestTypeDef,
+    ConditionsTypeDef,
     TaskTypeDef,
+    EventStreamSummaryTypeDef,
+    GetEventStreamResponseTypeDef,
     ExportingConfigTypeDef,
     ExportingLocationTypeDef,
     MergeProfilesRequestRequestTypeDef,
     ProfileTypeDef,
     GetMatchesResponseTypeDef,
     GetProfileObjectTypeResponseTypeDef,
     GetProfileObjectTypeTemplateResponseTypeDef,
     PutProfileObjectTypeRequestRequestTypeDef,
     PutProfileObjectTypeResponseTypeDef,
     ListAccountIntegrationsResponseTypeDef,
     ListIntegrationsResponseTypeDef,
+    ListCalculatedAttributeDefinitionsResponseTypeDef,
+    ListCalculatedAttributesForProfileResponseTypeDef,
     ListDomainsResponseTypeDef,
     ListProfileObjectTypesResponseTypeDef,
     ListProfileObjectTypeTemplatesResponseTypeDef,
     ListProfileObjectsResponseTypeDef,
     ListProfileObjectsRequestRequestTypeDef,
     ListWorkflowsResponseTypeDef,
     TriggerPropertiesTypeDef,
     SourceConnectorPropertiesTypeDef,
     UpdateProfileRequestRequestTypeDef,
     GetWorkflowResponseTypeDef,
     GetWorkflowStepsResponseTypeDef,
+    CreateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    CreateCalculatedAttributeDefinitionResponseTypeDef,
+    GetCalculatedAttributeDefinitionResponseTypeDef,
+    UpdateCalculatedAttributeDefinitionRequestRequestTypeDef,
+    UpdateCalculatedAttributeDefinitionResponseTypeDef,
+    ListEventStreamsResponseTypeDef,
     MatchingRequestTypeDef,
     MatchingResponseTypeDef,
     GetIdentityResolutionJobResponseTypeDef,
     IdentityResolutionJobTypeDef,
     SearchProfilesResponseTypeDef,
     TriggerConfigTypeDef,
     SourceFlowConfigTypeDef,
@@ -449,43 +513,43 @@
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

### Comparing `types-aiobotocore-customer-profiles-2.5.0.post1/types_aiobotocore_customer_profiles.egg-info/SOURCES.txt` & `types-aiobotocore-customer-profiles-2.5.1/types_aiobotocore_customer_profiles.egg-info/SOURCES.txt`

 * *Files 14% similar despite different names*

```diff
@@ -4,14 +4,16 @@
 types_aiobotocore_customer_profiles/__init__.py
 types_aiobotocore_customer_profiles/__init__.pyi
 types_aiobotocore_customer_profiles/__main__.py
 types_aiobotocore_customer_profiles/client.py
 types_aiobotocore_customer_profiles/client.pyi
 types_aiobotocore_customer_profiles/literals.py
 types_aiobotocore_customer_profiles/literals.pyi
+types_aiobotocore_customer_profiles/paginator.py
+types_aiobotocore_customer_profiles/paginator.pyi
 types_aiobotocore_customer_profiles/py.typed
 types_aiobotocore_customer_profiles/type_defs.py
 types_aiobotocore_customer_profiles/type_defs.pyi
 types_aiobotocore_customer_profiles/version.py
 types_aiobotocore_customer_profiles.egg-info/PKG-INFO
 types_aiobotocore_customer_profiles.egg-info/SOURCES.txt
 types_aiobotocore_customer_profiles.egg-info/dependency_links.txt
```

