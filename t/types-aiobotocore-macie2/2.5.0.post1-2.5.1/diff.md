# Comparing `tmp/types-aiobotocore-macie2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-macie2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-macie2-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:56 2023, max compression
+gzip compressed data, was "types-aiobotocore-macie2-2.5.1.tar", last modified: Wed Jun 28 01:43:47 2023, max compression
```

## Comparing `types-aiobotocore-macie2-2.5.0.post1.tar` & `types-aiobotocore-macie2-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.519395 types-aiobotocore-macie2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    29187 2023-03-11 12:26:56.519395 types-aiobotocore-macie2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    27620 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:56.519395 types-aiobotocore-macie2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.519395 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/
--rw-r--r--   0 runner    (1001) docker     (123)     4413 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4412 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    63125 2023-03-11 12:18:01.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    63020 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17074 2023-03-11 12:18:03.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    17072 2023-03-11 12:18:03.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    20473 2023-03-11 12:18:03.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    20454 2023-03-11 12:18:03.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    88779 2023-03-11 12:18:05.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    88724 2023-03-11 12:18:04.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:00.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1516 2023-03-11 12:18:03.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1515 2023-03-11 12:18:03.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:56.519395 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    29187 2023-03-11 12:26:56.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      865 2023-03-11 12:26:56.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:56.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:56.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:56.000000 types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.574170 types-aiobotocore-macie2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    29178 2023-06-28 01:43:47.570170 types-aiobotocore-macie2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    27617 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:47.574170 types-aiobotocore-macie2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.562171 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/
+-rw-r--r--   0 runner    (1001) docker     (123)     4413 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4412 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    63125 2023-06-28 01:34:44.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    63020 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17334 2023-06-28 01:34:44.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17332 2023-06-28 01:34:44.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    20385 2023-06-28 01:34:44.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20367 2023-06-28 01:34:44.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    88919 2023-06-28 01:34:46.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    88864 2023-06-28 01:34:45.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:42.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1516 2023-06-28 01:34:44.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1515 2023-06-28 01:34:44.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:47.570170 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    29178 2023-06-28 01:43:47.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      865 2023-06-28 01:43:47.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:47.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:47.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:47.000000 types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-macie2-2.5.0.post1/LICENSE` & `types-aiobotocore-macie2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-macie2-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-macie2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Macie2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Macie2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-macie2"></a>
 
 # types-aiobotocore-macie2
 
 [![PyPI - types-aiobotocore-macie2](https://img.shields.io/pypi/v/types-aiobotocore-macie2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-macie2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-macie2?color=blue)](https://pypistats.org/packages/types-aiobotocore-macie2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Macie2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
+[aiobotocore.Macie2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
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
 [types-aiobotocore-macie2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -473,15 +473,14 @@
     AllowListStatusTypeDef,
     AllowListSummaryTypeDef,
     ApiCallDetailsTypeDef,
     AwsAccountTypeDef,
     AwsServiceTypeDef,
     BatchGetCustomDataIdentifierSummaryTypeDef,
     BatchGetCustomDataIdentifiersRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BucketCountByEffectivePermissionTypeDef,
     BucketCountByEncryptionTypeTypeDef,
     BucketCountBySharedAccessTypeTypeDef,
     BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef,
     BucketCriteriaAdditionalPropertiesTypeDef,
     BucketPolicyTypeDef,
     BucketServerSideEncryptionTypeDef,
@@ -492,56 +491,66 @@
     ReplicationDetailsTypeDef,
     BucketSortCriteriaTypeDef,
     SensitivityAggregationsTypeDef,
     CellTypeDef,
     S3DestinationTypeDef,
     ClassificationResultStatusTypeDef,
     ClassificationScopeSummaryTypeDef,
+    CreateAllowListResponseTypeDef,
+    CreateClassificationJobResponseTypeDef,
     SeverityLevelTypeDef,
+    CreateCustomDataIdentifierResponseTypeDef,
+    CreateFindingsFilterResponseTypeDef,
     CreateInvitationsRequestRequestTypeDef,
     UnprocessedAccountTypeDef,
+    CreateMemberResponseTypeDef,
     CreateSampleFindingsRequestRequestTypeDef,
     SimpleCriterionForJobTypeDef,
     CriterionAdditionalPropertiesTypeDef,
     CustomDataIdentifierSummaryTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DeleteAllowListRequestRequestTypeDef,
     DeleteCustomDataIdentifierRequestRequestTypeDef,
     DeleteFindingsFilterRequestRequestTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMemberRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     DescribeClassificationJobRequestRequestTypeDef,
     LastRunErrorStatusTypeDef,
     StatisticsTypeDef,
     UserPausedDetailsTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
     DetectedDataDetailsTypeDef,
     DetectionTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateMemberRequestRequestTypeDef,
     DomainDetailsTypeDef,
     EnableMacieRequestRequestTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     FindingStatisticsSortCriteriaTypeDef,
     SeverityTypeDef,
     FindingsFilterListItemTypeDef,
     InvitationTypeDef,
     GetAllowListRequestRequestTypeDef,
+    GetAutomatedDiscoveryConfigurationResponseTypeDef,
     GetBucketStatisticsRequestRequestTypeDef,
     GetClassificationScopeRequestRequestTypeDef,
     GetCustomDataIdentifierRequestRequestTypeDef,
     GroupCountTypeDef,
     GetFindingsFilterRequestRequestTypeDef,
     SecurityHubConfigurationTypeDef,
     SortCriteriaTypeDef,
+    GetInvitationsCountResponseTypeDef,
+    GetMacieSessionResponseTypeDef,
     GetMemberRequestRequestTypeDef,
+    GetMemberResponseTypeDef,
     GetResourceProfileRequestRequestTypeDef,
     ResourceStatisticsTypeDef,
     RevealConfigurationTypeDef,
     GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef,
+    GetSensitiveDataOccurrencesAvailabilityResponseTypeDef,
     WaiterConfigTypeDef,
     GetSensitiveDataOccurrencesRequestRequestTypeDef,
     GetSensitivityInspectionTemplateRequestRequestTypeDef,
     SensitivityInspectionTemplateExcludesTypeDef,
     SensitivityInspectionTemplateIncludesTypeDef,
     UsageStatisticsFilterTypeDef,
     UsageStatisticsSortByTypeDef,
@@ -552,34 +561,49 @@
     IpCountryTypeDef,
     IpGeoLocationTypeDef,
     IpOwnerTypeDef,
     MonthlyScheduleTypeDef,
     WeeklyScheduleTypeDef,
     SimpleScopeTermTypeDef,
     S3BucketDefinitionForJobTypeDef,
+    ListAllowListsRequestListAllowListsPaginateTypeDef,
     ListAllowListsRequestRequestTypeDef,
     ListJobsSortCriteriaTypeDef,
+    ListClassificationScopesRequestListClassificationScopesPaginateTypeDef,
     ListClassificationScopesRequestRequestTypeDef,
+    ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef,
     ListCustomDataIdentifiersRequestRequestTypeDef,
+    ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef,
     ListFindingsFiltersRequestRequestTypeDef,
+    ListFindingsResponseTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
     ListJobsFilterTermTypeDef,
+    ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef,
     ListManagedDataIdentifiersRequestRequestTypeDef,
     ManagedDataIdentifierSummaryTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
     MemberTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
+    ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
     ListResourceProfileArtifactsRequestRequestTypeDef,
     ResourceProfileArtifactTypeDef,
+    ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
     ListResourceProfileDetectionsRequestRequestTypeDef,
+    ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef,
     ListSensitivityInspectionTemplatesRequestRequestTypeDef,
     SensitivityInspectionTemplatesEntryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RangeTypeDef,
     RecordTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3BucketOwnerTypeDef,
     ServerSideEncryptionTypeDef,
     S3ClassificationScopeExclusionTypeDef,
     S3ClassificationScopeExclusionUpdateTypeDef,
     SearchResourcesSimpleCriterionTypeDef,
     SearchResourcesSortCriteriaTypeDef,
     SearchResourcesTagCriterionPairTypeDef,
@@ -587,70 +611,46 @@
     SessionContextAttributesTypeDef,
     SessionIssuerTypeDef,
     SuppressDataIdentifierTypeDef,
     TagCriterionPairForJobTypeDef,
     TagResourceRequestRequestTypeDef,
     TagValuePairTypeDef,
     TestCustomDataIdentifierRequestRequestTypeDef,
+    TestCustomDataIdentifierResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAllowListResponseTypeDef,
     UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef,
     UpdateClassificationJobRequestRequestTypeDef,
+    UpdateFindingsFilterResponseTypeDef,
     UpdateMacieSessionRequestRequestTypeDef,
     UpdateMemberSessionRequestRequestTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     UpdateResourceProfileRequestRequestTypeDef,
     UserIdentityRootTypeDef,
     CreateMemberRequestRequestTypeDef,
     AccountLevelPermissionsTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
     AllowListCriteriaTypeDef,
+    ListAllowListsResponseTypeDef,
     FindingActionTypeDef,
     BatchGetCustomDataIdentifiersResponseTypeDef,
-    CreateAllowListResponseTypeDef,
-    CreateClassificationJobResponseTypeDef,
-    CreateCustomDataIdentifierResponseTypeDef,
-    CreateFindingsFilterResponseTypeDef,
-    CreateMemberResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    GetAutomatedDiscoveryConfigurationResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    GetMacieSessionResponseTypeDef,
-    GetMemberResponseTypeDef,
-    GetSensitiveDataOccurrencesAvailabilityResponseTypeDef,
-    ListAllowListsResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    TestCustomDataIdentifierResponseTypeDef,
-    UpdateAllowListResponseTypeDef,
-    UpdateFindingsFilterResponseTypeDef,
     BucketLevelPermissionsTypeDef,
     MatchingBucketTypeDef,
+    DescribeBucketsRequestDescribeBucketsPaginateTypeDef,
     DescribeBucketsRequestRequestTypeDef,
     BucketStatisticsBySensitivityTypeDef,
     ClassificationExportConfigurationTypeDef,
     ListClassificationScopesResponseTypeDef,
     CreateCustomDataIdentifierRequestRequestTypeDef,
     GetCustomDataIdentifierResponseTypeDef,
     CreateInvitationsResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     FindingCriteriaTypeDef,
     ListCustomDataIdentifiersResponseTypeDef,
-    DescribeBucketsRequestDescribeBucketsPaginateTypeDef,
-    ListAllowListsRequestListAllowListsPaginateTypeDef,
-    ListClassificationScopesRequestListClassificationScopesPaginateTypeDef,
-    ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef,
-    ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
-    ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
-    ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
-    ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef,
     GetSensitiveDataOccurrencesResponseTypeDef,
     ListResourceProfileDetectionsResponseTypeDef,
     ListFindingsFiltersResponseTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     ListInvitationsResponseTypeDef,
     GetFindingStatisticsResponseTypeDef,
@@ -751,43 +751,43 @@
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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/README.md` & `types-aiobotocore-macie2-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-macie2"></a>
 
 # types-aiobotocore-macie2
 
 [![PyPI - types-aiobotocore-macie2](https://img.shields.io/pypi/v/types-aiobotocore-macie2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-macie2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-macie2?color=blue)](https://pypistats.org/packages/types-aiobotocore-macie2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Macie2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
+[aiobotocore.Macie2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
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
 [types-aiobotocore-macie2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -440,15 +440,14 @@
     AllowListStatusTypeDef,
     AllowListSummaryTypeDef,
     ApiCallDetailsTypeDef,
     AwsAccountTypeDef,
     AwsServiceTypeDef,
     BatchGetCustomDataIdentifierSummaryTypeDef,
     BatchGetCustomDataIdentifiersRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BucketCountByEffectivePermissionTypeDef,
     BucketCountByEncryptionTypeTypeDef,
     BucketCountBySharedAccessTypeTypeDef,
     BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef,
     BucketCriteriaAdditionalPropertiesTypeDef,
     BucketPolicyTypeDef,
     BucketServerSideEncryptionTypeDef,
@@ -459,56 +458,66 @@
     ReplicationDetailsTypeDef,
     BucketSortCriteriaTypeDef,
     SensitivityAggregationsTypeDef,
     CellTypeDef,
     S3DestinationTypeDef,
     ClassificationResultStatusTypeDef,
     ClassificationScopeSummaryTypeDef,
+    CreateAllowListResponseTypeDef,
+    CreateClassificationJobResponseTypeDef,
     SeverityLevelTypeDef,
+    CreateCustomDataIdentifierResponseTypeDef,
+    CreateFindingsFilterResponseTypeDef,
     CreateInvitationsRequestRequestTypeDef,
     UnprocessedAccountTypeDef,
+    CreateMemberResponseTypeDef,
     CreateSampleFindingsRequestRequestTypeDef,
     SimpleCriterionForJobTypeDef,
     CriterionAdditionalPropertiesTypeDef,
     CustomDataIdentifierSummaryTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DeleteAllowListRequestRequestTypeDef,
     DeleteCustomDataIdentifierRequestRequestTypeDef,
     DeleteFindingsFilterRequestRequestTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMemberRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     DescribeClassificationJobRequestRequestTypeDef,
     LastRunErrorStatusTypeDef,
     StatisticsTypeDef,
     UserPausedDetailsTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
     DetectedDataDetailsTypeDef,
     DetectionTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateMemberRequestRequestTypeDef,
     DomainDetailsTypeDef,
     EnableMacieRequestRequestTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     FindingStatisticsSortCriteriaTypeDef,
     SeverityTypeDef,
     FindingsFilterListItemTypeDef,
     InvitationTypeDef,
     GetAllowListRequestRequestTypeDef,
+    GetAutomatedDiscoveryConfigurationResponseTypeDef,
     GetBucketStatisticsRequestRequestTypeDef,
     GetClassificationScopeRequestRequestTypeDef,
     GetCustomDataIdentifierRequestRequestTypeDef,
     GroupCountTypeDef,
     GetFindingsFilterRequestRequestTypeDef,
     SecurityHubConfigurationTypeDef,
     SortCriteriaTypeDef,
+    GetInvitationsCountResponseTypeDef,
+    GetMacieSessionResponseTypeDef,
     GetMemberRequestRequestTypeDef,
+    GetMemberResponseTypeDef,
     GetResourceProfileRequestRequestTypeDef,
     ResourceStatisticsTypeDef,
     RevealConfigurationTypeDef,
     GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef,
+    GetSensitiveDataOccurrencesAvailabilityResponseTypeDef,
     WaiterConfigTypeDef,
     GetSensitiveDataOccurrencesRequestRequestTypeDef,
     GetSensitivityInspectionTemplateRequestRequestTypeDef,
     SensitivityInspectionTemplateExcludesTypeDef,
     SensitivityInspectionTemplateIncludesTypeDef,
     UsageStatisticsFilterTypeDef,
     UsageStatisticsSortByTypeDef,
@@ -519,34 +528,49 @@
     IpCountryTypeDef,
     IpGeoLocationTypeDef,
     IpOwnerTypeDef,
     MonthlyScheduleTypeDef,
     WeeklyScheduleTypeDef,
     SimpleScopeTermTypeDef,
     S3BucketDefinitionForJobTypeDef,
+    ListAllowListsRequestListAllowListsPaginateTypeDef,
     ListAllowListsRequestRequestTypeDef,
     ListJobsSortCriteriaTypeDef,
+    ListClassificationScopesRequestListClassificationScopesPaginateTypeDef,
     ListClassificationScopesRequestRequestTypeDef,
+    ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef,
     ListCustomDataIdentifiersRequestRequestTypeDef,
+    ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef,
     ListFindingsFiltersRequestRequestTypeDef,
+    ListFindingsResponseTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
     ListJobsFilterTermTypeDef,
+    ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef,
     ListManagedDataIdentifiersRequestRequestTypeDef,
     ManagedDataIdentifierSummaryTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
     MemberTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
+    ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
     ListResourceProfileArtifactsRequestRequestTypeDef,
     ResourceProfileArtifactTypeDef,
+    ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
     ListResourceProfileDetectionsRequestRequestTypeDef,
+    ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef,
     ListSensitivityInspectionTemplatesRequestRequestTypeDef,
     SensitivityInspectionTemplatesEntryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RangeTypeDef,
     RecordTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3BucketOwnerTypeDef,
     ServerSideEncryptionTypeDef,
     S3ClassificationScopeExclusionTypeDef,
     S3ClassificationScopeExclusionUpdateTypeDef,
     SearchResourcesSimpleCriterionTypeDef,
     SearchResourcesSortCriteriaTypeDef,
     SearchResourcesTagCriterionPairTypeDef,
@@ -554,70 +578,46 @@
     SessionContextAttributesTypeDef,
     SessionIssuerTypeDef,
     SuppressDataIdentifierTypeDef,
     TagCriterionPairForJobTypeDef,
     TagResourceRequestRequestTypeDef,
     TagValuePairTypeDef,
     TestCustomDataIdentifierRequestRequestTypeDef,
+    TestCustomDataIdentifierResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAllowListResponseTypeDef,
     UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef,
     UpdateClassificationJobRequestRequestTypeDef,
+    UpdateFindingsFilterResponseTypeDef,
     UpdateMacieSessionRequestRequestTypeDef,
     UpdateMemberSessionRequestRequestTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     UpdateResourceProfileRequestRequestTypeDef,
     UserIdentityRootTypeDef,
     CreateMemberRequestRequestTypeDef,
     AccountLevelPermissionsTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
     AllowListCriteriaTypeDef,
+    ListAllowListsResponseTypeDef,
     FindingActionTypeDef,
     BatchGetCustomDataIdentifiersResponseTypeDef,
-    CreateAllowListResponseTypeDef,
-    CreateClassificationJobResponseTypeDef,
-    CreateCustomDataIdentifierResponseTypeDef,
-    CreateFindingsFilterResponseTypeDef,
-    CreateMemberResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    GetAutomatedDiscoveryConfigurationResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    GetMacieSessionResponseTypeDef,
-    GetMemberResponseTypeDef,
-    GetSensitiveDataOccurrencesAvailabilityResponseTypeDef,
-    ListAllowListsResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    TestCustomDataIdentifierResponseTypeDef,
-    UpdateAllowListResponseTypeDef,
-    UpdateFindingsFilterResponseTypeDef,
     BucketLevelPermissionsTypeDef,
     MatchingBucketTypeDef,
+    DescribeBucketsRequestDescribeBucketsPaginateTypeDef,
     DescribeBucketsRequestRequestTypeDef,
     BucketStatisticsBySensitivityTypeDef,
     ClassificationExportConfigurationTypeDef,
     ListClassificationScopesResponseTypeDef,
     CreateCustomDataIdentifierRequestRequestTypeDef,
     GetCustomDataIdentifierResponseTypeDef,
     CreateInvitationsResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     FindingCriteriaTypeDef,
     ListCustomDataIdentifiersResponseTypeDef,
-    DescribeBucketsRequestDescribeBucketsPaginateTypeDef,
-    ListAllowListsRequestListAllowListsPaginateTypeDef,
-    ListClassificationScopesRequestListClassificationScopesPaginateTypeDef,
-    ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef,
-    ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
-    ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
-    ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
-    ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef,
     GetSensitiveDataOccurrencesResponseTypeDef,
     ListResourceProfileDetectionsResponseTypeDef,
     ListFindingsFiltersResponseTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     ListInvitationsResponseTypeDef,
     GetFindingStatisticsResponseTypeDef,
@@ -718,43 +718,43 @@
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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/setup.py` & `types-aiobotocore-macie2-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-macie2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-macie2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_macie2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Macie2 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Macie2 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/"
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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/__init__.py` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/__init__.pyi` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/__main__.py` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/__main__.py`

 * *Files 17% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Macie2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Macie2 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2\nOther"
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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/client.py` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/client.pyi` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/literals.py` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -134,14 +134,15 @@
 FindingStatisticsSortAttributeNameType = Literal["count", "groupKey"]
 FindingTypeType = Literal[
     "Policy:IAMUser/S3BlockPublicAccessDisabled",
     "Policy:IAMUser/S3BucketEncryptionDisabled",
     "Policy:IAMUser/S3BucketPublic",
     "Policy:IAMUser/S3BucketReplicatedExternally",
     "Policy:IAMUser/S3BucketSharedExternally",
+    "Policy:IAMUser/S3BucketSharedWithCloudFront",
     "SensitiveData:S3Object/Credentials",
     "SensitiveData:S3Object/CustomIdentifier",
     "SensitiveData:S3Object/Financial",
     "SensitiveData:S3Object/Multiple",
     "SensitiveData:S3Object/Personal",
 ]
 FindingsFilterActionType = Literal["ARCHIVE", "NOOP"]
@@ -302,14 +303,15 @@
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
@@ -388,14 +390,15 @@
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
@@ -406,14 +409,15 @@
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
@@ -449,14 +453,15 @@
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
@@ -475,16 +480,19 @@
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
@@ -568,15 +576,17 @@
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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/literals.pyi` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -132,14 +132,15 @@
 FindingStatisticsSortAttributeNameType = Literal["count", "groupKey"]
 FindingTypeType = Literal[
     "Policy:IAMUser/S3BlockPublicAccessDisabled",
     "Policy:IAMUser/S3BucketEncryptionDisabled",
     "Policy:IAMUser/S3BucketPublic",
     "Policy:IAMUser/S3BucketReplicatedExternally",
     "Policy:IAMUser/S3BucketSharedExternally",
+    "Policy:IAMUser/S3BucketSharedWithCloudFront",
     "SensitiveData:S3Object/Credentials",
     "SensitiveData:S3Object/CustomIdentifier",
     "SensitiveData:S3Object/Financial",
     "SensitiveData:S3Object/Multiple",
     "SensitiveData:S3Object/Personal",
 ]
 FindingsFilterActionType = Literal["ARCHIVE", "NOOP"]
@@ -300,14 +301,15 @@
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
@@ -386,14 +388,15 @@
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
@@ -404,14 +407,15 @@
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
@@ -447,14 +451,15 @@
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
@@ -473,16 +478,19 @@
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
@@ -566,15 +574,17 @@
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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/paginator.py` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -46,16 +46,15 @@
         list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
         list_resource_profile_artifacts_paginator: ListResourceProfileArtifactsPaginator = client.get_paginator("list_resource_profile_artifacts")
         list_resource_profile_detections_paginator: ListResourceProfileDetectionsPaginator = client.get_paginator("list_resource_profile_detections")
         list_sensitivity_inspection_templates_paginator: ListSensitivityInspectionTemplatesPaginator = client.get_paginator("list_sensitivity_inspection_templates")
         search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import TimeRangeType
 from .type_defs import (
     BucketCriteriaAdditionalPropertiesTypeDef,
@@ -83,20 +82,14 @@
     SearchResourcesResponseTypeDef,
     SearchResourcesSortCriteriaTypeDef,
     SortCriteriaTypeDef,
     UsageStatisticsFilterTypeDef,
     UsageStatisticsSortByTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeBucketsPaginator",
     "GetUsageStatisticsPaginator",
     "ListAllowListsPaginator",
     "ListClassificationJobsPaginator",
     "ListClassificationScopesPaginator",
     "ListCustomDataIdentifiersPaginator",
@@ -130,15 +123,15 @@
     """
 
     def paginate(
         self,
         *,
         criteria: Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef] = ...,
         sortCriteria: BucketSortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBucketsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.DescribeBuckets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#describebucketspaginator)
         """
 
 
@@ -150,30 +143,30 @@
 
     def paginate(
         self,
         *,
         filterBy: Sequence[UsageStatisticsFilterTypeDef] = ...,
         sortBy: UsageStatisticsSortByTypeDef = ...,
         timeRange: TimeRangeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetUsageStatisticsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.GetUsageStatistics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#getusagestatisticspaginator)
         """
 
 
 class ListAllowListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListAllowLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listallowlistspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAllowListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListAllowLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listallowlistspaginator)
         """
 
 
@@ -184,45 +177,45 @@
     """
 
     def paginate(
         self,
         *,
         filterCriteria: ListJobsFilterCriteriaTypeDef = ...,
         sortCriteria: ListJobsSortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClassificationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListClassificationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listclassificationjobspaginator)
         """
 
 
 class ListClassificationScopesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListClassificationScopes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listclassificationscopespaginator)
     """
 
     def paginate(
-        self, *, name: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClassificationScopesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListClassificationScopes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listclassificationscopespaginator)
         """
 
 
 class ListCustomDataIdentifiersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListCustomDataIdentifiers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listcustomdataidentifierspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomDataIdentifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListCustomDataIdentifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listcustomdataidentifierspaginator)
         """
 
 
@@ -233,135 +226,135 @@
     """
 
     def paginate(
         self,
         *,
         findingCriteria: FindingCriteriaTypeDef = ...,
         sortCriteria: SortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listfindingspaginator)
         """
 
 
 class ListFindingsFiltersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListFindingsFilters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listfindingsfilterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsFiltersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListFindingsFilters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listfindingsfilterspaginator)
         """
 
 
 class ListInvitationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListInvitations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listinvitationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listinvitationspaginator)
         """
 
 
 class ListManagedDataIdentifiersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListManagedDataIdentifiers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmanageddataidentifierspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedDataIdentifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListManagedDataIdentifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmanageddataidentifierspaginator)
         """
 
 
 class ListMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmemberspaginator)
     """
 
     def paginate(
-        self, *, onlyAssociated: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, onlyAssociated: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmemberspaginator)
         """
 
 
 class ListOrganizationAdminAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListOrganizationAdminAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listorganizationadminaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationAdminAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListOrganizationAdminAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listorganizationadminaccountspaginator)
         """
 
 
 class ListResourceProfileArtifactsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileArtifacts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofileartifactspaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceProfileArtifactsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileArtifacts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofileartifactspaginator)
         """
 
 
 class ListResourceProfileDetectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileDetections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofiledetectionspaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceProfileDetectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileDetections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofiledetectionspaginator)
         """
 
 
 class ListSensitivityInspectionTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListSensitivityInspectionTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listsensitivityinspectiontemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSensitivityInspectionTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListSensitivityInspectionTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listsensitivityinspectiontemplatespaginator)
         """
 
 
@@ -372,13 +365,13 @@
     """
 
     def paginate(
         self,
         *,
         bucketCriteria: SearchResourcesBucketCriteriaTypeDef = ...,
         sortCriteria: SearchResourcesSortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.SearchResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#searchresourcespaginator)
         """
```

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/paginator.pyi` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -46,16 +46,15 @@
         list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
         list_resource_profile_artifacts_paginator: ListResourceProfileArtifactsPaginator = client.get_paginator("list_resource_profile_artifacts")
         list_resource_profile_detections_paginator: ListResourceProfileDetectionsPaginator = client.get_paginator("list_resource_profile_detections")
         list_sensitivity_inspection_templates_paginator: ListSensitivityInspectionTemplatesPaginator = client.get_paginator("list_sensitivity_inspection_templates")
         search_resources_paginator: SearchResourcesPaginator = client.get_paginator("search_resources")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import TimeRangeType
 from .type_defs import (
     BucketCriteriaAdditionalPropertiesTypeDef,
@@ -83,19 +82,14 @@
     SearchResourcesResponseTypeDef,
     SearchResourcesSortCriteriaTypeDef,
     SortCriteriaTypeDef,
     UsageStatisticsFilterTypeDef,
     UsageStatisticsSortByTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeBucketsPaginator",
     "GetUsageStatisticsPaginator",
     "ListAllowListsPaginator",
     "ListClassificationJobsPaginator",
     "ListClassificationScopesPaginator",
     "ListCustomDataIdentifiersPaginator",
@@ -126,15 +120,15 @@
     """
 
     def paginate(
         self,
         *,
         criteria: Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef] = ...,
         sortCriteria: BucketSortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeBucketsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.DescribeBuckets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#describebucketspaginator)
         """
 
 class GetUsageStatisticsPaginator(AioPaginator):
@@ -145,29 +139,29 @@
 
     def paginate(
         self,
         *,
         filterBy: Sequence[UsageStatisticsFilterTypeDef] = ...,
         sortBy: UsageStatisticsSortByTypeDef = ...,
         timeRange: TimeRangeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetUsageStatisticsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.GetUsageStatistics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#getusagestatisticspaginator)
         """
 
 class ListAllowListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListAllowLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listallowlistspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAllowListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListAllowLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listallowlistspaginator)
         """
 
 class ListClassificationJobsPaginator(AioPaginator):
@@ -177,43 +171,43 @@
     """
 
     def paginate(
         self,
         *,
         filterCriteria: ListJobsFilterCriteriaTypeDef = ...,
         sortCriteria: ListJobsSortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClassificationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListClassificationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listclassificationjobspaginator)
         """
 
 class ListClassificationScopesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListClassificationScopes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listclassificationscopespaginator)
     """
 
     def paginate(
-        self, *, name: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, name: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClassificationScopesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListClassificationScopes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listclassificationscopespaginator)
         """
 
 class ListCustomDataIdentifiersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListCustomDataIdentifiers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listcustomdataidentifierspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCustomDataIdentifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListCustomDataIdentifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listcustomdataidentifierspaginator)
         """
 
 class ListFindingsPaginator(AioPaginator):
@@ -223,127 +217,127 @@
     """
 
     def paginate(
         self,
         *,
         findingCriteria: FindingCriteriaTypeDef = ...,
         sortCriteria: SortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listfindingspaginator)
         """
 
 class ListFindingsFiltersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListFindingsFilters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listfindingsfilterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsFiltersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListFindingsFilters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listfindingsfilterspaginator)
         """
 
 class ListInvitationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListInvitations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listinvitationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listinvitationspaginator)
         """
 
 class ListManagedDataIdentifiersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListManagedDataIdentifiers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmanageddataidentifierspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListManagedDataIdentifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListManagedDataIdentifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmanageddataidentifierspaginator)
         """
 
 class ListMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmemberspaginator)
     """
 
     def paginate(
-        self, *, onlyAssociated: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, onlyAssociated: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listmemberspaginator)
         """
 
 class ListOrganizationAdminAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListOrganizationAdminAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listorganizationadminaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationAdminAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListOrganizationAdminAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listorganizationadminaccountspaginator)
         """
 
 class ListResourceProfileArtifactsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileArtifacts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofileartifactspaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceProfileArtifactsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileArtifacts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofileartifactspaginator)
         """
 
 class ListResourceProfileDetectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileDetections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofiledetectionspaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceProfileDetectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListResourceProfileDetections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listresourceprofiledetectionspaginator)
         """
 
 class ListSensitivityInspectionTemplatesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListSensitivityInspectionTemplates)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listsensitivityinspectiontemplatespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSensitivityInspectionTemplatesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.ListSensitivityInspectionTemplates.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#listsensitivityinspectiontemplatespaginator)
         """
 
 class SearchResourcesPaginator(AioPaginator):
@@ -353,13 +347,13 @@
     """
 
     def paginate(
         self,
         *,
         bucketCriteria: SearchResourcesBucketCriteriaTypeDef = ...,
         sortCriteria: SearchResourcesSortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2.Paginator.SearchResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/paginators/#searchresourcespaginator)
         """
```

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/type_defs.py` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -88,15 +88,14 @@
     "AllowListStatusTypeDef",
     "AllowListSummaryTypeDef",
     "ApiCallDetailsTypeDef",
     "AwsAccountTypeDef",
     "AwsServiceTypeDef",
     "BatchGetCustomDataIdentifierSummaryTypeDef",
     "BatchGetCustomDataIdentifiersRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "BucketCountByEffectivePermissionTypeDef",
     "BucketCountByEncryptionTypeTypeDef",
     "BucketCountBySharedAccessTypeTypeDef",
     "BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef",
     "BucketCriteriaAdditionalPropertiesTypeDef",
     "BucketPolicyTypeDef",
     "BucketServerSideEncryptionTypeDef",
@@ -107,56 +106,66 @@
     "ReplicationDetailsTypeDef",
     "BucketSortCriteriaTypeDef",
     "SensitivityAggregationsTypeDef",
     "CellTypeDef",
     "S3DestinationTypeDef",
     "ClassificationResultStatusTypeDef",
     "ClassificationScopeSummaryTypeDef",
+    "CreateAllowListResponseTypeDef",
+    "CreateClassificationJobResponseTypeDef",
     "SeverityLevelTypeDef",
+    "CreateCustomDataIdentifierResponseTypeDef",
+    "CreateFindingsFilterResponseTypeDef",
     "CreateInvitationsRequestRequestTypeDef",
     "UnprocessedAccountTypeDef",
+    "CreateMemberResponseTypeDef",
     "CreateSampleFindingsRequestRequestTypeDef",
     "SimpleCriterionForJobTypeDef",
     "CriterionAdditionalPropertiesTypeDef",
     "CustomDataIdentifierSummaryTypeDef",
     "DeclineInvitationsRequestRequestTypeDef",
     "DeleteAllowListRequestRequestTypeDef",
     "DeleteCustomDataIdentifierRequestRequestTypeDef",
     "DeleteFindingsFilterRequestRequestTypeDef",
     "DeleteInvitationsRequestRequestTypeDef",
     "DeleteMemberRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeClassificationJobRequestRequestTypeDef",
     "LastRunErrorStatusTypeDef",
     "StatisticsTypeDef",
     "UserPausedDetailsTypeDef",
+    "DescribeOrganizationConfigurationResponseTypeDef",
     "DetectedDataDetailsTypeDef",
     "DetectionTypeDef",
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     "DisassociateMemberRequestRequestTypeDef",
     "DomainDetailsTypeDef",
     "EnableMacieRequestRequestTypeDef",
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     "FindingStatisticsSortCriteriaTypeDef",
     "SeverityTypeDef",
     "FindingsFilterListItemTypeDef",
     "InvitationTypeDef",
     "GetAllowListRequestRequestTypeDef",
+    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
     "GetBucketStatisticsRequestRequestTypeDef",
     "GetClassificationScopeRequestRequestTypeDef",
     "GetCustomDataIdentifierRequestRequestTypeDef",
     "GroupCountTypeDef",
     "GetFindingsFilterRequestRequestTypeDef",
     "SecurityHubConfigurationTypeDef",
     "SortCriteriaTypeDef",
+    "GetInvitationsCountResponseTypeDef",
+    "GetMacieSessionResponseTypeDef",
     "GetMemberRequestRequestTypeDef",
+    "GetMemberResponseTypeDef",
     "GetResourceProfileRequestRequestTypeDef",
     "ResourceStatisticsTypeDef",
     "RevealConfigurationTypeDef",
     "GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef",
+    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetSensitiveDataOccurrencesRequestRequestTypeDef",
     "GetSensitivityInspectionTemplateRequestRequestTypeDef",
     "SensitivityInspectionTemplateExcludesTypeDef",
     "SensitivityInspectionTemplateIncludesTypeDef",
     "UsageStatisticsFilterTypeDef",
     "UsageStatisticsSortByTypeDef",
@@ -167,34 +176,49 @@
     "IpCountryTypeDef",
     "IpGeoLocationTypeDef",
     "IpOwnerTypeDef",
     "MonthlyScheduleTypeDef",
     "WeeklyScheduleTypeDef",
     "SimpleScopeTermTypeDef",
     "S3BucketDefinitionForJobTypeDef",
+    "ListAllowListsRequestListAllowListsPaginateTypeDef",
     "ListAllowListsRequestRequestTypeDef",
     "ListJobsSortCriteriaTypeDef",
+    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
     "ListClassificationScopesRequestRequestTypeDef",
+    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
     "ListCustomDataIdentifiersRequestRequestTypeDef",
+    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
     "ListFindingsFiltersRequestRequestTypeDef",
+    "ListFindingsResponseTypeDef",
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
     "ListInvitationsRequestRequestTypeDef",
     "ListJobsFilterTermTypeDef",
+    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
     "ListManagedDataIdentifiersRequestRequestTypeDef",
     "ManagedDataIdentifierSummaryTypeDef",
+    "ListMembersRequestListMembersPaginateTypeDef",
     "ListMembersRequestRequestTypeDef",
     "MemberTypeDef",
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
+    "ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
     "ListResourceProfileArtifactsRequestRequestTypeDef",
     "ResourceProfileArtifactTypeDef",
+    "ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
     "ListResourceProfileDetectionsRequestRequestTypeDef",
+    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
     "ListSensitivityInspectionTemplatesRequestRequestTypeDef",
     "SensitivityInspectionTemplatesEntryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "RangeTypeDef",
     "RecordTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3BucketOwnerTypeDef",
     "ServerSideEncryptionTypeDef",
     "S3ClassificationScopeExclusionTypeDef",
     "S3ClassificationScopeExclusionUpdateTypeDef",
     "SearchResourcesSimpleCriterionTypeDef",
     "SearchResourcesSortCriteriaTypeDef",
     "SearchResourcesTagCriterionPairTypeDef",
@@ -202,70 +226,46 @@
     "SessionContextAttributesTypeDef",
     "SessionIssuerTypeDef",
     "SuppressDataIdentifierTypeDef",
     "TagCriterionPairForJobTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TagValuePairTypeDef",
     "TestCustomDataIdentifierRequestRequestTypeDef",
+    "TestCustomDataIdentifierResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAllowListResponseTypeDef",
     "UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef",
     "UpdateClassificationJobRequestRequestTypeDef",
+    "UpdateFindingsFilterResponseTypeDef",
     "UpdateMacieSessionRequestRequestTypeDef",
     "UpdateMemberSessionRequestRequestTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
     "UpdateResourceProfileRequestRequestTypeDef",
     "UserIdentityRootTypeDef",
     "CreateMemberRequestRequestTypeDef",
     "AccountLevelPermissionsTypeDef",
+    "ListOrganizationAdminAccountsResponseTypeDef",
     "AllowListCriteriaTypeDef",
+    "ListAllowListsResponseTypeDef",
     "FindingActionTypeDef",
     "BatchGetCustomDataIdentifiersResponseTypeDef",
-    "CreateAllowListResponseTypeDef",
-    "CreateClassificationJobResponseTypeDef",
-    "CreateCustomDataIdentifierResponseTypeDef",
-    "CreateFindingsFilterResponseTypeDef",
-    "CreateMemberResponseTypeDef",
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
-    "GetInvitationsCountResponseTypeDef",
-    "GetMacieSessionResponseTypeDef",
-    "GetMemberResponseTypeDef",
-    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
-    "ListAllowListsResponseTypeDef",
-    "ListFindingsResponseTypeDef",
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "TestCustomDataIdentifierResponseTypeDef",
-    "UpdateAllowListResponseTypeDef",
-    "UpdateFindingsFilterResponseTypeDef",
     "BucketLevelPermissionsTypeDef",
     "MatchingBucketTypeDef",
+    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
     "DescribeBucketsRequestRequestTypeDef",
     "BucketStatisticsBySensitivityTypeDef",
     "ClassificationExportConfigurationTypeDef",
     "ListClassificationScopesResponseTypeDef",
     "CreateCustomDataIdentifierRequestRequestTypeDef",
     "GetCustomDataIdentifierResponseTypeDef",
     "CreateInvitationsResponseTypeDef",
     "DeclineInvitationsResponseTypeDef",
     "DeleteInvitationsResponseTypeDef",
     "FindingCriteriaTypeDef",
     "ListCustomDataIdentifiersResponseTypeDef",
-    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
-    "ListAllowListsRequestListAllowListsPaginateTypeDef",
-    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
-    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
-    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
-    "ListMembersRequestListMembersPaginateTypeDef",
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    "ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
-    "ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
-    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
     "GetSensitiveDataOccurrencesResponseTypeDef",
     "ListResourceProfileDetectionsResponseTypeDef",
     "ListFindingsFiltersResponseTypeDef",
     "GetAdministratorAccountResponseTypeDef",
     "GetMasterAccountResponseTypeDef",
     "ListInvitationsResponseTypeDef",
     "GetFindingStatisticsResponseTypeDef",
@@ -502,25 +502,14 @@
     "BatchGetCustomDataIdentifiersRequestRequestTypeDef",
     {
         "ids": Sequence[str],
     },
     total=False,
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
 BucketCountByEffectivePermissionTypeDef = TypedDict(
     "BucketCountByEffectivePermissionTypeDef",
     {
         "publiclyAccessible": int,
         "publiclyReadable": int,
         "publiclyWritable": int,
         "unknown": int,
@@ -709,22 +698,57 @@
     {
         "id": str,
         "name": str,
     },
     total=False,
 )
 
+CreateAllowListResponseTypeDef = TypedDict(
+    "CreateAllowListResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateClassificationJobResponseTypeDef = TypedDict(
+    "CreateClassificationJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SeverityLevelTypeDef = TypedDict(
     "SeverityLevelTypeDef",
     {
         "occurrencesThreshold": int,
         "severity": DataIdentifierSeverityType,
     },
 )
 
+CreateCustomDataIdentifierResponseTypeDef = TypedDict(
+    "CreateCustomDataIdentifierResponseTypeDef",
+    {
+        "customDataIdentifierId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFindingsFilterResponseTypeDef = TypedDict(
+    "CreateFindingsFilterResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateInvitationsRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInvitationsRequestRequestTypeDef",
     {
         "accountIds": Sequence[str],
     },
 )
 _OptionalCreateInvitationsRequestRequestTypeDef = TypedDict(
@@ -749,14 +773,22 @@
         "accountId": str,
         "errorCode": ErrorCodeType,
         "errorMessage": str,
     },
     total=False,
 )
 
+CreateMemberResponseTypeDef = TypedDict(
+    "CreateMemberResponseTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateSampleFindingsRequestRequestTypeDef = TypedDict(
     "CreateSampleFindingsRequestRequestTypeDef",
     {
         "findingTypes": Sequence[FindingTypeType],
     },
     total=False,
 )
@@ -849,24 +881,14 @@
 DeleteMemberRequestRequestTypeDef = TypedDict(
     "DeleteMemberRequestRequestTypeDef",
     {
         "id": str,
     },
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
 DescribeClassificationJobRequestRequestTypeDef = TypedDict(
     "DescribeClassificationJobRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
@@ -893,14 +915,23 @@
         "jobExpiresAt": datetime,
         "jobImminentExpirationHealthEventArn": str,
         "jobPausedAt": datetime,
     },
     total=False,
 )
 
+DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    {
+        "autoEnable": bool,
+        "maxAccountLimitReached": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DetectedDataDetailsTypeDef = TypedDict(
     "DetectedDataDetailsTypeDef",
     {
         "value": str,
     },
 )
 
@@ -1015,14 +1046,27 @@
 GetAllowListRequestRequestTypeDef = TypedDict(
     "GetAllowListRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetAutomatedDiscoveryConfigurationResponseTypeDef = TypedDict(
+    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
+    {
+        "classificationScopeId": str,
+        "disabledAt": datetime,
+        "firstEnabledAt": datetime,
+        "lastUpdatedAt": datetime,
+        "sensitivityInspectionTemplateId": str,
+        "status": AutomatedDiscoveryStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBucketStatisticsRequestRequestTypeDef = TypedDict(
     "GetBucketStatisticsRequestRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
@@ -1070,21 +1114,57 @@
     {
         "attributeName": str,
         "orderBy": OrderByType,
     },
     total=False,
 )
 
+GetInvitationsCountResponseTypeDef = TypedDict(
+    "GetInvitationsCountResponseTypeDef",
+    {
+        "invitationsCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetMacieSessionResponseTypeDef = TypedDict(
+    "GetMacieSessionResponseTypeDef",
+    {
+        "createdAt": datetime,
+        "findingPublishingFrequency": FindingPublishingFrequencyType,
+        "serviceRole": str,
+        "status": MacieStatusType,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMemberRequestRequestTypeDef = TypedDict(
     "GetMemberRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetMemberResponseTypeDef = TypedDict(
+    "GetMemberResponseTypeDef",
+    {
+        "accountId": str,
+        "administratorAccountId": str,
+        "arn": str,
+        "email": str,
+        "invitedAt": datetime,
+        "masterAccountId": str,
+        "relationshipStatus": RelationshipStatusType,
+        "tags": Dict[str, str],
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourceProfileRequestRequestTypeDef = TypedDict(
     "GetResourceProfileRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
@@ -1128,14 +1208,23 @@
 GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef = TypedDict(
     "GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef",
     {
         "findingId": str,
     },
 )
 
+GetSensitiveDataOccurrencesAvailabilityResponseTypeDef = TypedDict(
+    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
+    {
+        "code": AvailabilityCodeType,
+        "reasons": List[UnavailabilityReasonCodeType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -1288,14 +1377,22 @@
     "S3BucketDefinitionForJobTypeDef",
     {
         "accountId": str,
         "buckets": Sequence[str],
     },
 )
 
+ListAllowListsRequestListAllowListsPaginateTypeDef = TypedDict(
+    "ListAllowListsRequestListAllowListsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAllowListsRequestRequestTypeDef = TypedDict(
     "ListAllowListsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1306,41 +1403,83 @@
     {
         "attributeName": ListJobsSortAttributeNameType,
         "orderBy": OrderByType,
     },
     total=False,
 )
 
+ListClassificationScopesRequestListClassificationScopesPaginateTypeDef = TypedDict(
+    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
+    {
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClassificationScopesRequestRequestTypeDef = TypedDict(
     "ListClassificationScopesRequestRequestTypeDef",
     {
         "name": str,
         "nextToken": str,
     },
     total=False,
 )
 
+ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef = TypedDict(
+    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomDataIdentifiersRequestRequestTypeDef = TypedDict(
     "ListCustomDataIdentifiersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef = TypedDict(
+    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFindingsFiltersRequestRequestTypeDef = TypedDict(
     "ListFindingsFiltersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListFindingsResponseTypeDef = TypedDict(
+    "ListFindingsResponseTypeDef",
+    {
+        "findingIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListInvitationsRequestListInvitationsPaginateTypeDef = TypedDict(
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInvitationsRequestRequestTypeDef = TypedDict(
     "ListInvitationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1352,14 +1491,22 @@
         "comparator": JobComparatorType,
         "key": ListJobsFilterKeyType,
         "values": Sequence[str],
     },
     total=False,
 )
 
+ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef = TypedDict(
+    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListManagedDataIdentifiersRequestRequestTypeDef = TypedDict(
     "ListManagedDataIdentifiersRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
@@ -1369,14 +1516,23 @@
     {
         "category": SensitiveDataItemCategoryType,
         "id": str,
     },
     total=False,
 )
 
+ListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "ListMembersRequestListMembersPaginateTypeDef",
+    {
+        "onlyAssociated": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMembersRequestRequestTypeDef = TypedDict(
     "ListMembersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "onlyAssociated": str,
     },
@@ -1395,23 +1551,53 @@
         "relationshipStatus": RelationshipStatusType,
         "tags": Dict[str, str],
         "updatedAt": datetime,
     },
     total=False,
 )
 
+ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOrganizationAdminAccountsRequestRequestTypeDef = TypedDict(
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
+    "_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
+    "_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef(
+    _RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
+    _OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourceProfileArtifactsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceProfileArtifactsRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListResourceProfileArtifactsRequestRequestTypeDef = TypedDict(
@@ -1448,14 +1634,40 @@
 
 class ResourceProfileArtifactTypeDef(
     _RequiredResourceProfileArtifactTypeDef, _OptionalResourceProfileArtifactTypeDef
 ):
     pass
 
 
+_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
+        {
+            "resourceArn": str,
+        },
+    )
+)
+_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef(
+    _RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
+    _OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourceProfileDetectionsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceProfileDetectionsRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListResourceProfileDetectionsRequestRequestTypeDef = TypedDict(
@@ -1471,14 +1683,22 @@
 class ListResourceProfileDetectionsRequestRequestTypeDef(
     _RequiredListResourceProfileDetectionsRequestRequestTypeDef,
     _OptionalListResourceProfileDetectionsRequestRequestTypeDef,
 ):
     pass
 
 
+ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef = TypedDict(
+    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSensitivityInspectionTemplatesRequestRequestTypeDef = TypedDict(
     "ListSensitivityInspectionTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1496,14 +1716,22 @@
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
 RangeTypeDef = TypedDict(
     "RangeTypeDef",
     {
         "end": int,
         "start": int,
         "startColumn": int,
     },
@@ -1515,14 +1743,35 @@
     {
         "jsonPath": str,
         "recordIndex": int,
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
 S3BucketOwnerTypeDef = TypedDict(
     "S3BucketOwnerTypeDef",
     {
         "displayName": str,
         "id": str,
     },
     total=False,
@@ -1667,22 +1916,39 @@
 class TestCustomDataIdentifierRequestRequestTypeDef(
     _RequiredTestCustomDataIdentifierRequestRequestTypeDef,
     _OptionalTestCustomDataIdentifierRequestRequestTypeDef,
 ):
     pass
 
 
+TestCustomDataIdentifierResponseTypeDef = TypedDict(
+    "TestCustomDataIdentifierResponseTypeDef",
+    {
+        "matchCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateAllowListResponseTypeDef = TypedDict(
+    "UpdateAllowListResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef",
     {
         "status": AutomatedDiscoveryStatusType,
     },
 )
 
@@ -1690,14 +1956,23 @@
     "UpdateClassificationJobRequestRequestTypeDef",
     {
         "jobId": str,
         "jobStatus": JobStatusType,
     },
 )
 
+UpdateFindingsFilterResponseTypeDef = TypedDict(
+    "UpdateFindingsFilterResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateMacieSessionRequestRequestTypeDef = TypedDict(
     "UpdateMacieSessionRequestRequestTypeDef",
     {
         "findingPublishingFrequency": FindingPublishingFrequencyType,
         "status": MacieStatusType,
     },
     total=False,
@@ -1775,209 +2050,56 @@
     "AccountLevelPermissionsTypeDef",
     {
         "blockPublicAccess": BlockPublicAccessTypeDef,
     },
     total=False,
 )
 
+ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    {
+        "adminAccounts": List[AdminAccountTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AllowListCriteriaTypeDef = TypedDict(
     "AllowListCriteriaTypeDef",
     {
         "regex": str,
         "s3WordsList": S3WordsListTypeDef,
     },
     total=False,
 )
 
+ListAllowListsResponseTypeDef = TypedDict(
+    "ListAllowListsResponseTypeDef",
+    {
+        "allowLists": List[AllowListSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FindingActionTypeDef = TypedDict(
     "FindingActionTypeDef",
     {
         "actionType": Literal["AWS_API_CALL"],
         "apiCallDetails": ApiCallDetailsTypeDef,
     },
     total=False,
 )
 
 BatchGetCustomDataIdentifiersResponseTypeDef = TypedDict(
     "BatchGetCustomDataIdentifiersResponseTypeDef",
     {
         "customDataIdentifiers": List[BatchGetCustomDataIdentifierSummaryTypeDef],
         "notFoundIdentifierIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAllowListResponseTypeDef = TypedDict(
-    "CreateAllowListResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateClassificationJobResponseTypeDef = TypedDict(
-    "CreateClassificationJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomDataIdentifierResponseTypeDef = TypedDict(
-    "CreateCustomDataIdentifierResponseTypeDef",
-    {
-        "customDataIdentifierId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFindingsFilterResponseTypeDef = TypedDict(
-    "CreateFindingsFilterResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMemberResponseTypeDef = TypedDict(
-    "CreateMemberResponseTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    {
-        "autoEnable": bool,
-        "maxAccountLimitReached": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAutomatedDiscoveryConfigurationResponseTypeDef = TypedDict(
-    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
-    {
-        "classificationScopeId": str,
-        "disabledAt": datetime,
-        "firstEnabledAt": datetime,
-        "lastUpdatedAt": datetime,
-        "sensitivityInspectionTemplateId": str,
-        "status": AutomatedDiscoveryStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetInvitationsCountResponseTypeDef = TypedDict(
-    "GetInvitationsCountResponseTypeDef",
-    {
-        "invitationsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMacieSessionResponseTypeDef = TypedDict(
-    "GetMacieSessionResponseTypeDef",
-    {
-        "createdAt": datetime,
-        "findingPublishingFrequency": FindingPublishingFrequencyType,
-        "serviceRole": str,
-        "status": MacieStatusType,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMemberResponseTypeDef = TypedDict(
-    "GetMemberResponseTypeDef",
-    {
-        "accountId": str,
-        "administratorAccountId": str,
-        "arn": str,
-        "email": str,
-        "invitedAt": datetime,
-        "masterAccountId": str,
-        "relationshipStatus": RelationshipStatusType,
-        "tags": Dict[str, str],
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSensitiveDataOccurrencesAvailabilityResponseTypeDef = TypedDict(
-    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
-    {
-        "code": AvailabilityCodeType,
-        "reasons": List[UnavailabilityReasonCodeType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAllowListsResponseTypeDef = TypedDict(
-    "ListAllowListsResponseTypeDef",
-    {
-        "allowLists": List[AllowListSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFindingsResponseTypeDef = TypedDict(
-    "ListFindingsResponseTypeDef",
-    {
-        "findingIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    {
-        "adminAccounts": List[AdminAccountTypeDef],
-        "nextToken": str,
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
-TestCustomDataIdentifierResponseTypeDef = TypedDict(
-    "TestCustomDataIdentifierResponseTypeDef",
-    {
-        "matchCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAllowListResponseTypeDef = TypedDict(
-    "UpdateAllowListResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFindingsFilterResponseTypeDef = TypedDict(
-    "UpdateFindingsFilterResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BucketLevelPermissionsTypeDef = TypedDict(
     "BucketLevelPermissionsTypeDef",
     {
         "accessControlList": AccessControlListTypeDef,
@@ -2005,14 +2127,24 @@
         "sizeInBytesCompressed": int,
         "unclassifiableObjectCount": ObjectLevelStatisticsTypeDef,
         "unclassifiableObjectSizeInBytes": ObjectLevelStatisticsTypeDef,
     },
     total=False,
 )
 
+DescribeBucketsRequestDescribeBucketsPaginateTypeDef = TypedDict(
+    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
+    {
+        "criteria": Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef],
+        "sortCriteria": BucketSortCriteriaTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeBucketsRequestRequestTypeDef = TypedDict(
     "DescribeBucketsRequestRequestTypeDef",
     {
         "criteria": Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef],
         "maxResults": int,
         "nextToken": str,
         "sortCriteria": BucketSortCriteriaTypeDef,
@@ -2040,15 +2172,15 @@
 )
 
 ListClassificationScopesResponseTypeDef = TypedDict(
     "ListClassificationScopesResponseTypeDef",
     {
         "classificationScopes": List[ClassificationScopeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCustomDataIdentifierRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCustomDataIdentifierRequestRequestTypeDef",
     {
         "name": str,
@@ -2088,39 +2220,39 @@
         "ignoreWords": List[str],
         "keywords": List[str],
         "maximumMatchDistance": int,
         "name": str,
         "regex": str,
         "severityLevels": List[SeverityLevelTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInvitationsResponseTypeDef = TypedDict(
     "CreateInvitationsResponseTypeDef",
     {
         "unprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineInvitationsResponseTypeDef = TypedDict(
     "DeclineInvitationsResponseTypeDef",
     {
         "unprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInvitationsResponseTypeDef = TypedDict(
     "DeleteInvitationsResponseTypeDef",
     {
         "unprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FindingCriteriaTypeDef = TypedDict(
     "FindingCriteriaTypeDef",
     {
         "criterion": Mapping[str, CriterionAdditionalPropertiesTypeDef],
@@ -2129,216 +2261,84 @@
 )
 
 ListCustomDataIdentifiersResponseTypeDef = TypedDict(
     "ListCustomDataIdentifiersResponseTypeDef",
     {
         "items": List[CustomDataIdentifierSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeBucketsRequestDescribeBucketsPaginateTypeDef = TypedDict(
-    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
-    {
-        "criteria": Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef],
-        "sortCriteria": BucketSortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAllowListsRequestListAllowListsPaginateTypeDef = TypedDict(
-    "ListAllowListsRequestListAllowListsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListClassificationScopesRequestListClassificationScopesPaginateTypeDef = TypedDict(
-    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
-    {
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef = TypedDict(
-    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef = TypedDict(
-    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInvitationsRequestListInvitationsPaginateTypeDef = TypedDict(
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef = TypedDict(
-    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "ListMembersRequestListMembersPaginateTypeDef",
-    {
-        "onlyAssociated": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
-    "_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
-    "_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef(
-    _RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
-    _OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
-        {
-            "resourceArn": str,
-        },
-    )
-)
-_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef(
-    _RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
-    _OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
-):
-    pass
-
-
-ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef = TypedDict(
-    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetSensitiveDataOccurrencesResponseTypeDef = TypedDict(
     "GetSensitiveDataOccurrencesResponseTypeDef",
     {
         "error": str,
         "sensitiveDataOccurrences": Dict[str, List[DetectedDataDetailsTypeDef]],
         "status": RevealRequestStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceProfileDetectionsResponseTypeDef = TypedDict(
     "ListResourceProfileDetectionsResponseTypeDef",
     {
         "detections": List[DetectionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFindingsFiltersResponseTypeDef = TypedDict(
     "ListFindingsFiltersResponseTypeDef",
     {
         "findingsFilterListItems": List[FindingsFilterListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAdministratorAccountResponseTypeDef = TypedDict(
     "GetAdministratorAccountResponseTypeDef",
     {
         "administrator": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMasterAccountResponseTypeDef = TypedDict(
     "GetMasterAccountResponseTypeDef",
     {
         "master": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInvitationsResponseTypeDef = TypedDict(
     "ListInvitationsResponseTypeDef",
     {
         "invitations": List[InvitationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFindingStatisticsResponseTypeDef = TypedDict(
     "GetFindingStatisticsResponseTypeDef",
     {
         "countsByGroup": List[GroupCountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFindingsPublicationConfigurationResponseTypeDef = TypedDict(
     "GetFindingsPublicationConfigurationResponseTypeDef",
     {
         "securityHubConfiguration": SecurityHubConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutFindingsPublicationConfigurationRequestRequestTypeDef = TypedDict(
     "PutFindingsPublicationConfigurationRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -2371,38 +2371,38 @@
 GetResourceProfileResponseTypeDef = TypedDict(
     "GetResourceProfileResponseTypeDef",
     {
         "profileUpdatedAt": datetime,
         "sensitivityScore": int,
         "sensitivityScoreOverridden": bool,
         "statistics": ResourceStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRevealConfigurationResponseTypeDef = TypedDict(
     "GetRevealConfigurationResponseTypeDef",
     {
         "configuration": RevealConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRevealConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateRevealConfigurationRequestRequestTypeDef",
     {
         "configuration": RevealConfigurationTypeDef,
     },
 )
 
 UpdateRevealConfigurationResponseTypeDef = TypedDict(
     "UpdateRevealConfigurationResponseTypeDef",
     {
         "configuration": RevealConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetSensitiveDataOccurrencesRequestFindingRevealedWaitTypeDef = TypedDict(
     "_RequiredGetSensitiveDataOccurrencesRequestFindingRevealedWaitTypeDef",
     {
         "findingId": str,
@@ -2428,15 +2428,15 @@
     "GetSensitivityInspectionTemplateResponseTypeDef",
     {
         "description": str,
         "excludes": SensitivityInspectionTemplateExcludesTypeDef,
         "includes": SensitivityInspectionTemplateIncludesTypeDef,
         "name": str,
         "sensitivityInspectionTemplateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSensitivityInspectionTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSensitivityInspectionTemplateRequestRequestTypeDef",
     {
         "id": str,
@@ -2462,15 +2462,15 @@
 
 GetUsageStatisticsRequestGetUsageStatisticsPaginateTypeDef = TypedDict(
     "GetUsageStatisticsRequestGetUsageStatisticsPaginateTypeDef",
     {
         "filterBy": Sequence[UsageStatisticsFilterTypeDef],
         "sortBy": UsageStatisticsSortByTypeDef,
         "timeRange": TimeRangeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetUsageStatisticsRequestRequestTypeDef = TypedDict(
     "GetUsageStatisticsRequestRequestTypeDef",
     {
@@ -2484,15 +2484,15 @@
 )
 
 GetUsageTotalsResponseTypeDef = TypedDict(
     "GetUsageTotalsResponseTypeDef",
     {
         "timeRange": TimeRangeType,
         "usageTotals": List[UsageTotalTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IpAddressDetailsTypeDef = TypedDict(
     "IpAddressDetailsTypeDef",
     {
         "ipAddressV4": str,
@@ -2524,42 +2524,42 @@
 )
 
 ListManagedDataIdentifiersResponseTypeDef = TypedDict(
     "ListManagedDataIdentifiersResponseTypeDef",
     {
         "items": List[ManagedDataIdentifierSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembersResponseTypeDef = TypedDict(
     "ListMembersResponseTypeDef",
     {
         "members": List[MemberTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceProfileArtifactsResponseTypeDef = TypedDict(
     "ListResourceProfileArtifactsResponseTypeDef",
     {
         "artifacts": List[ResourceProfileArtifactTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSensitivityInspectionTemplatesResponseTypeDef = TypedDict(
     "ListSensitivityInspectionTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "sensitivityInspectionTemplates": List[SensitivityInspectionTemplatesEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PageTypeDef = TypedDict(
     "PageTypeDef",
     {
         "lineRange": RangeTypeDef,
@@ -2705,15 +2705,15 @@
         "criteria": AllowListCriteriaTypeDef,
         "description": str,
         "id": str,
         "name": str,
         "status": AllowListStatusTypeDef,
         "tags": Dict[str, str],
         "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAllowListRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAllowListRequestRequestTypeDef",
     {
         "criteria": AllowListCriteriaTypeDef,
@@ -2768,38 +2768,38 @@
         "classifiableSizeInBytes": int,
         "lastUpdated": datetime,
         "objectCount": int,
         "sizeInBytes": int,
         "sizeInBytesCompressed": int,
         "unclassifiableObjectCount": ObjectLevelStatisticsTypeDef,
         "unclassifiableObjectSizeInBytes": ObjectLevelStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClassificationExportConfigurationResponseTypeDef = TypedDict(
     "GetClassificationExportConfigurationResponseTypeDef",
     {
         "configuration": ClassificationExportConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutClassificationExportConfigurationRequestRequestTypeDef = TypedDict(
     "PutClassificationExportConfigurationRequestRequestTypeDef",
     {
         "configuration": ClassificationExportConfigurationTypeDef,
     },
 )
 
 PutClassificationExportConfigurationResponseTypeDef = TypedDict(
     "PutClassificationExportConfigurationResponseTypeDef",
     {
         "configuration": ClassificationExportConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFindingsFilterRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFindingsFilterRequestRequestTypeDef",
     {
         "action": FindingsFilterActionType,
@@ -2857,24 +2857,24 @@
         "arn": str,
         "description": str,
         "findingCriteria": FindingCriteriaTypeDef,
         "id": str,
         "name": str,
         "position": int,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFindingsRequestListFindingsPaginateTypeDef = TypedDict(
     "ListFindingsRequestListFindingsPaginateTypeDef",
     {
         "findingCriteria": FindingCriteriaTypeDef,
         "sortCriteria": SortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFindingsRequestRequestTypeDef = TypedDict(
     "ListFindingsRequestRequestTypeDef",
     {
@@ -2914,15 +2914,15 @@
 
 
 ListClassificationJobsRequestListClassificationJobsPaginateTypeDef = TypedDict(
     "ListClassificationJobsRequestListClassificationJobsPaginateTypeDef",
     {
         "filterCriteria": ListJobsFilterCriteriaTypeDef,
         "sortCriteria": ListJobsSortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListClassificationJobsRequestRequestTypeDef = TypedDict(
     "ListClassificationJobsRequestRequestTypeDef",
     {
@@ -2948,15 +2948,15 @@
 
 GetClassificationScopeResponseTypeDef = TypedDict(
     "GetClassificationScopeResponseTypeDef",
     {
         "id": str,
         "name": str,
         "s3": S3ClassificationScopeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateClassificationScopeRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateClassificationScopeRequestRequestTypeDef",
     {
         "id": str,
@@ -3050,15 +3050,15 @@
 )
 
 SearchResourcesResponseTypeDef = TypedDict(
     "SearchResourcesResponseTypeDef",
     {
         "matchingResources": List[MatchingResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomDetectionTypeDef = TypedDict(
     "CustomDetectionTypeDef",
     {
         "arn": str,
@@ -3089,15 +3089,15 @@
 
 GetUsageStatisticsResponseTypeDef = TypedDict(
     "GetUsageStatisticsResponseTypeDef",
     {
         "nextToken": str,
         "records": List[UsageRecordTypeDef],
         "timeRange": TimeRangeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserIdentityTypeDef = TypedDict(
     "UserIdentityTypeDef",
     {
         "assumedRole": AssumedRoleTypeDef,
@@ -3232,15 +3232,15 @@
 )
 
 DescribeBucketsResponseTypeDef = TypedDict(
     "DescribeBucketsResponseTypeDef",
     {
         "buckets": List[BucketMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourcesAffectedTypeDef = TypedDict(
     "ResourcesAffectedTypeDef",
     {
         "s3Bucket": S3BucketTypeDef,
@@ -3274,15 +3274,15 @@
 )
 
 SearchResourcesRequestSearchResourcesPaginateTypeDef = TypedDict(
     "SearchResourcesRequestSearchResourcesPaginateTypeDef",
     {
         "bucketCriteria": SearchResourcesBucketCriteriaTypeDef,
         "sortCriteria": SearchResourcesSortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 PolicyDetailsTypeDef = TypedDict(
     "PolicyDetailsTypeDef",
     {
@@ -3331,15 +3331,15 @@
 )
 
 ListClassificationJobsResponseTypeDef = TypedDict(
     "ListClassificationJobsResponseTypeDef",
     {
         "items": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateClassificationJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateClassificationJobRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -3392,15 +3392,15 @@
         "name": str,
         "s3JobDefinition": S3JobDefinitionTypeDef,
         "samplingPercentage": int,
         "scheduleFrequency": JobScheduleFrequencyTypeDef,
         "statistics": StatisticsTypeDef,
         "tags": Dict[str, str],
         "userPausedDetails": UserPausedDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FindingTypeDef = TypedDict(
     "FindingTypeDef",
     {
         "accountId": str,
@@ -3425,10 +3425,10 @@
     total=False,
 )
 
 GetFindingsResponseTypeDef = TypedDict(
     "GetFindingsResponseTypeDef",
     {
         "findings": List[FindingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/type_defs.pyi` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -87,15 +87,14 @@
     "AllowListStatusTypeDef",
     "AllowListSummaryTypeDef",
     "ApiCallDetailsTypeDef",
     "AwsAccountTypeDef",
     "AwsServiceTypeDef",
     "BatchGetCustomDataIdentifierSummaryTypeDef",
     "BatchGetCustomDataIdentifiersRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "BucketCountByEffectivePermissionTypeDef",
     "BucketCountByEncryptionTypeTypeDef",
     "BucketCountBySharedAccessTypeTypeDef",
     "BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef",
     "BucketCriteriaAdditionalPropertiesTypeDef",
     "BucketPolicyTypeDef",
     "BucketServerSideEncryptionTypeDef",
@@ -106,56 +105,66 @@
     "ReplicationDetailsTypeDef",
     "BucketSortCriteriaTypeDef",
     "SensitivityAggregationsTypeDef",
     "CellTypeDef",
     "S3DestinationTypeDef",
     "ClassificationResultStatusTypeDef",
     "ClassificationScopeSummaryTypeDef",
+    "CreateAllowListResponseTypeDef",
+    "CreateClassificationJobResponseTypeDef",
     "SeverityLevelTypeDef",
+    "CreateCustomDataIdentifierResponseTypeDef",
+    "CreateFindingsFilterResponseTypeDef",
     "CreateInvitationsRequestRequestTypeDef",
     "UnprocessedAccountTypeDef",
+    "CreateMemberResponseTypeDef",
     "CreateSampleFindingsRequestRequestTypeDef",
     "SimpleCriterionForJobTypeDef",
     "CriterionAdditionalPropertiesTypeDef",
     "CustomDataIdentifierSummaryTypeDef",
     "DeclineInvitationsRequestRequestTypeDef",
     "DeleteAllowListRequestRequestTypeDef",
     "DeleteCustomDataIdentifierRequestRequestTypeDef",
     "DeleteFindingsFilterRequestRequestTypeDef",
     "DeleteInvitationsRequestRequestTypeDef",
     "DeleteMemberRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "DescribeClassificationJobRequestRequestTypeDef",
     "LastRunErrorStatusTypeDef",
     "StatisticsTypeDef",
     "UserPausedDetailsTypeDef",
+    "DescribeOrganizationConfigurationResponseTypeDef",
     "DetectedDataDetailsTypeDef",
     "DetectionTypeDef",
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     "DisassociateMemberRequestRequestTypeDef",
     "DomainDetailsTypeDef",
     "EnableMacieRequestRequestTypeDef",
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     "FindingStatisticsSortCriteriaTypeDef",
     "SeverityTypeDef",
     "FindingsFilterListItemTypeDef",
     "InvitationTypeDef",
     "GetAllowListRequestRequestTypeDef",
+    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
     "GetBucketStatisticsRequestRequestTypeDef",
     "GetClassificationScopeRequestRequestTypeDef",
     "GetCustomDataIdentifierRequestRequestTypeDef",
     "GroupCountTypeDef",
     "GetFindingsFilterRequestRequestTypeDef",
     "SecurityHubConfigurationTypeDef",
     "SortCriteriaTypeDef",
+    "GetInvitationsCountResponseTypeDef",
+    "GetMacieSessionResponseTypeDef",
     "GetMemberRequestRequestTypeDef",
+    "GetMemberResponseTypeDef",
     "GetResourceProfileRequestRequestTypeDef",
     "ResourceStatisticsTypeDef",
     "RevealConfigurationTypeDef",
     "GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef",
+    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetSensitiveDataOccurrencesRequestRequestTypeDef",
     "GetSensitivityInspectionTemplateRequestRequestTypeDef",
     "SensitivityInspectionTemplateExcludesTypeDef",
     "SensitivityInspectionTemplateIncludesTypeDef",
     "UsageStatisticsFilterTypeDef",
     "UsageStatisticsSortByTypeDef",
@@ -166,34 +175,49 @@
     "IpCountryTypeDef",
     "IpGeoLocationTypeDef",
     "IpOwnerTypeDef",
     "MonthlyScheduleTypeDef",
     "WeeklyScheduleTypeDef",
     "SimpleScopeTermTypeDef",
     "S3BucketDefinitionForJobTypeDef",
+    "ListAllowListsRequestListAllowListsPaginateTypeDef",
     "ListAllowListsRequestRequestTypeDef",
     "ListJobsSortCriteriaTypeDef",
+    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
     "ListClassificationScopesRequestRequestTypeDef",
+    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
     "ListCustomDataIdentifiersRequestRequestTypeDef",
+    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
     "ListFindingsFiltersRequestRequestTypeDef",
+    "ListFindingsResponseTypeDef",
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
     "ListInvitationsRequestRequestTypeDef",
     "ListJobsFilterTermTypeDef",
+    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
     "ListManagedDataIdentifiersRequestRequestTypeDef",
     "ManagedDataIdentifierSummaryTypeDef",
+    "ListMembersRequestListMembersPaginateTypeDef",
     "ListMembersRequestRequestTypeDef",
     "MemberTypeDef",
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
+    "ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
     "ListResourceProfileArtifactsRequestRequestTypeDef",
     "ResourceProfileArtifactTypeDef",
+    "ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
     "ListResourceProfileDetectionsRequestRequestTypeDef",
+    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
     "ListSensitivityInspectionTemplatesRequestRequestTypeDef",
     "SensitivityInspectionTemplatesEntryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "RangeTypeDef",
     "RecordTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "S3BucketOwnerTypeDef",
     "ServerSideEncryptionTypeDef",
     "S3ClassificationScopeExclusionTypeDef",
     "S3ClassificationScopeExclusionUpdateTypeDef",
     "SearchResourcesSimpleCriterionTypeDef",
     "SearchResourcesSortCriteriaTypeDef",
     "SearchResourcesTagCriterionPairTypeDef",
@@ -201,70 +225,46 @@
     "SessionContextAttributesTypeDef",
     "SessionIssuerTypeDef",
     "SuppressDataIdentifierTypeDef",
     "TagCriterionPairForJobTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TagValuePairTypeDef",
     "TestCustomDataIdentifierRequestRequestTypeDef",
+    "TestCustomDataIdentifierResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateAllowListResponseTypeDef",
     "UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef",
     "UpdateClassificationJobRequestRequestTypeDef",
+    "UpdateFindingsFilterResponseTypeDef",
     "UpdateMacieSessionRequestRequestTypeDef",
     "UpdateMemberSessionRequestRequestTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
     "UpdateResourceProfileRequestRequestTypeDef",
     "UserIdentityRootTypeDef",
     "CreateMemberRequestRequestTypeDef",
     "AccountLevelPermissionsTypeDef",
+    "ListOrganizationAdminAccountsResponseTypeDef",
     "AllowListCriteriaTypeDef",
+    "ListAllowListsResponseTypeDef",
     "FindingActionTypeDef",
     "BatchGetCustomDataIdentifiersResponseTypeDef",
-    "CreateAllowListResponseTypeDef",
-    "CreateClassificationJobResponseTypeDef",
-    "CreateCustomDataIdentifierResponseTypeDef",
-    "CreateFindingsFilterResponseTypeDef",
-    "CreateMemberResponseTypeDef",
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
-    "GetInvitationsCountResponseTypeDef",
-    "GetMacieSessionResponseTypeDef",
-    "GetMemberResponseTypeDef",
-    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
-    "ListAllowListsResponseTypeDef",
-    "ListFindingsResponseTypeDef",
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "TestCustomDataIdentifierResponseTypeDef",
-    "UpdateAllowListResponseTypeDef",
-    "UpdateFindingsFilterResponseTypeDef",
     "BucketLevelPermissionsTypeDef",
     "MatchingBucketTypeDef",
+    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
     "DescribeBucketsRequestRequestTypeDef",
     "BucketStatisticsBySensitivityTypeDef",
     "ClassificationExportConfigurationTypeDef",
     "ListClassificationScopesResponseTypeDef",
     "CreateCustomDataIdentifierRequestRequestTypeDef",
     "GetCustomDataIdentifierResponseTypeDef",
     "CreateInvitationsResponseTypeDef",
     "DeclineInvitationsResponseTypeDef",
     "DeleteInvitationsResponseTypeDef",
     "FindingCriteriaTypeDef",
     "ListCustomDataIdentifiersResponseTypeDef",
-    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
-    "ListAllowListsRequestListAllowListsPaginateTypeDef",
-    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
-    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
-    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
-    "ListMembersRequestListMembersPaginateTypeDef",
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    "ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
-    "ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
-    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
     "GetSensitiveDataOccurrencesResponseTypeDef",
     "ListResourceProfileDetectionsResponseTypeDef",
     "ListFindingsFiltersResponseTypeDef",
     "GetAdministratorAccountResponseTypeDef",
     "GetMasterAccountResponseTypeDef",
     "ListInvitationsResponseTypeDef",
     "GetFindingStatisticsResponseTypeDef",
@@ -497,25 +497,14 @@
     "BatchGetCustomDataIdentifiersRequestRequestTypeDef",
     {
         "ids": Sequence[str],
     },
     total=False,
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
 BucketCountByEffectivePermissionTypeDef = TypedDict(
     "BucketCountByEffectivePermissionTypeDef",
     {
         "publiclyAccessible": int,
         "publiclyReadable": int,
         "publiclyWritable": int,
         "unknown": int,
@@ -702,22 +691,57 @@
     {
         "id": str,
         "name": str,
     },
     total=False,
 )
 
+CreateAllowListResponseTypeDef = TypedDict(
+    "CreateAllowListResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateClassificationJobResponseTypeDef = TypedDict(
+    "CreateClassificationJobResponseTypeDef",
+    {
+        "jobArn": str,
+        "jobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SeverityLevelTypeDef = TypedDict(
     "SeverityLevelTypeDef",
     {
         "occurrencesThreshold": int,
         "severity": DataIdentifierSeverityType,
     },
 )
 
+CreateCustomDataIdentifierResponseTypeDef = TypedDict(
+    "CreateCustomDataIdentifierResponseTypeDef",
+    {
+        "customDataIdentifierId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFindingsFilterResponseTypeDef = TypedDict(
+    "CreateFindingsFilterResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateInvitationsRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInvitationsRequestRequestTypeDef",
     {
         "accountIds": Sequence[str],
     },
 )
 _OptionalCreateInvitationsRequestRequestTypeDef = TypedDict(
@@ -740,14 +764,22 @@
         "accountId": str,
         "errorCode": ErrorCodeType,
         "errorMessage": str,
     },
     total=False,
 )
 
+CreateMemberResponseTypeDef = TypedDict(
+    "CreateMemberResponseTypeDef",
+    {
+        "arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateSampleFindingsRequestRequestTypeDef = TypedDict(
     "CreateSampleFindingsRequestRequestTypeDef",
     {
         "findingTypes": Sequence[FindingTypeType],
     },
     total=False,
 )
@@ -838,24 +870,14 @@
 DeleteMemberRequestRequestTypeDef = TypedDict(
     "DeleteMemberRequestRequestTypeDef",
     {
         "id": str,
     },
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
 DescribeClassificationJobRequestRequestTypeDef = TypedDict(
     "DescribeClassificationJobRequestRequestTypeDef",
     {
         "jobId": str,
     },
 )
 
@@ -882,14 +904,23 @@
         "jobExpiresAt": datetime,
         "jobImminentExpirationHealthEventArn": str,
         "jobPausedAt": datetime,
     },
     total=False,
 )
 
+DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    {
+        "autoEnable": bool,
+        "maxAccountLimitReached": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DetectedDataDetailsTypeDef = TypedDict(
     "DetectedDataDetailsTypeDef",
     {
         "value": str,
     },
 )
 
@@ -1002,14 +1033,27 @@
 GetAllowListRequestRequestTypeDef = TypedDict(
     "GetAllowListRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetAutomatedDiscoveryConfigurationResponseTypeDef = TypedDict(
+    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
+    {
+        "classificationScopeId": str,
+        "disabledAt": datetime,
+        "firstEnabledAt": datetime,
+        "lastUpdatedAt": datetime,
+        "sensitivityInspectionTemplateId": str,
+        "status": AutomatedDiscoveryStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBucketStatisticsRequestRequestTypeDef = TypedDict(
     "GetBucketStatisticsRequestRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
@@ -1057,21 +1101,57 @@
     {
         "attributeName": str,
         "orderBy": OrderByType,
     },
     total=False,
 )
 
+GetInvitationsCountResponseTypeDef = TypedDict(
+    "GetInvitationsCountResponseTypeDef",
+    {
+        "invitationsCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetMacieSessionResponseTypeDef = TypedDict(
+    "GetMacieSessionResponseTypeDef",
+    {
+        "createdAt": datetime,
+        "findingPublishingFrequency": FindingPublishingFrequencyType,
+        "serviceRole": str,
+        "status": MacieStatusType,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMemberRequestRequestTypeDef = TypedDict(
     "GetMemberRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetMemberResponseTypeDef = TypedDict(
+    "GetMemberResponseTypeDef",
+    {
+        "accountId": str,
+        "administratorAccountId": str,
+        "arn": str,
+        "email": str,
+        "invitedAt": datetime,
+        "masterAccountId": str,
+        "relationshipStatus": RelationshipStatusType,
+        "tags": Dict[str, str],
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourceProfileRequestRequestTypeDef = TypedDict(
     "GetResourceProfileRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
@@ -1113,14 +1193,23 @@
 GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef = TypedDict(
     "GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef",
     {
         "findingId": str,
     },
 )
 
+GetSensitiveDataOccurrencesAvailabilityResponseTypeDef = TypedDict(
+    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
+    {
+        "code": AvailabilityCodeType,
+        "reasons": List[UnavailabilityReasonCodeType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -1273,14 +1362,22 @@
     "S3BucketDefinitionForJobTypeDef",
     {
         "accountId": str,
         "buckets": Sequence[str],
     },
 )
 
+ListAllowListsRequestListAllowListsPaginateTypeDef = TypedDict(
+    "ListAllowListsRequestListAllowListsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAllowListsRequestRequestTypeDef = TypedDict(
     "ListAllowListsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1291,41 +1388,83 @@
     {
         "attributeName": ListJobsSortAttributeNameType,
         "orderBy": OrderByType,
     },
     total=False,
 )
 
+ListClassificationScopesRequestListClassificationScopesPaginateTypeDef = TypedDict(
+    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
+    {
+        "name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClassificationScopesRequestRequestTypeDef = TypedDict(
     "ListClassificationScopesRequestRequestTypeDef",
     {
         "name": str,
         "nextToken": str,
     },
     total=False,
 )
 
+ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef = TypedDict(
+    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCustomDataIdentifiersRequestRequestTypeDef = TypedDict(
     "ListCustomDataIdentifiersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef = TypedDict(
+    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFindingsFiltersRequestRequestTypeDef = TypedDict(
     "ListFindingsFiltersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListFindingsResponseTypeDef = TypedDict(
+    "ListFindingsResponseTypeDef",
+    {
+        "findingIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListInvitationsRequestListInvitationsPaginateTypeDef = TypedDict(
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInvitationsRequestRequestTypeDef = TypedDict(
     "ListInvitationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1337,14 +1476,22 @@
         "comparator": JobComparatorType,
         "key": ListJobsFilterKeyType,
         "values": Sequence[str],
     },
     total=False,
 )
 
+ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef = TypedDict(
+    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListManagedDataIdentifiersRequestRequestTypeDef = TypedDict(
     "ListManagedDataIdentifiersRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
@@ -1354,14 +1501,23 @@
     {
         "category": SensitiveDataItemCategoryType,
         "id": str,
     },
     total=False,
 )
 
+ListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "ListMembersRequestListMembersPaginateTypeDef",
+    {
+        "onlyAssociated": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMembersRequestRequestTypeDef = TypedDict(
     "ListMembersRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "onlyAssociated": str,
     },
@@ -1380,23 +1536,51 @@
         "relationshipStatus": RelationshipStatusType,
         "tags": Dict[str, str],
         "updatedAt": datetime,
     },
     total=False,
 )
 
+ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOrganizationAdminAccountsRequestRequestTypeDef = TypedDict(
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
+    "_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
+    "_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef(
+    _RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
+    _OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourceProfileArtifactsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceProfileArtifactsRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListResourceProfileArtifactsRequestRequestTypeDef = TypedDict(
@@ -1429,14 +1613,38 @@
 )
 
 class ResourceProfileArtifactTypeDef(
     _RequiredResourceProfileArtifactTypeDef, _OptionalResourceProfileArtifactTypeDef
 ):
     pass
 
+_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
+    TypedDict(
+        "_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
+        {
+            "resourceArn": str,
+        },
+    )
+)
+_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
+    TypedDict(
+        "_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef(
+    _RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
+    _OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourceProfileDetectionsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceProfileDetectionsRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListResourceProfileDetectionsRequestRequestTypeDef = TypedDict(
@@ -1450,14 +1658,22 @@
 
 class ListResourceProfileDetectionsRequestRequestTypeDef(
     _RequiredListResourceProfileDetectionsRequestRequestTypeDef,
     _OptionalListResourceProfileDetectionsRequestRequestTypeDef,
 ):
     pass
 
+ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef = TypedDict(
+    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSensitivityInspectionTemplatesRequestRequestTypeDef = TypedDict(
     "ListSensitivityInspectionTemplatesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1475,14 +1691,22 @@
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
 RangeTypeDef = TypedDict(
     "RangeTypeDef",
     {
         "end": int,
         "start": int,
         "startColumn": int,
     },
@@ -1494,14 +1718,35 @@
     {
         "jsonPath": str,
         "recordIndex": int,
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
 S3BucketOwnerTypeDef = TypedDict(
     "S3BucketOwnerTypeDef",
     {
         "displayName": str,
         "id": str,
     },
     total=False,
@@ -1644,22 +1889,39 @@
 
 class TestCustomDataIdentifierRequestRequestTypeDef(
     _RequiredTestCustomDataIdentifierRequestRequestTypeDef,
     _OptionalTestCustomDataIdentifierRequestRequestTypeDef,
 ):
     pass
 
+TestCustomDataIdentifierResponseTypeDef = TypedDict(
+    "TestCustomDataIdentifierResponseTypeDef",
+    {
+        "matchCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateAllowListResponseTypeDef = TypedDict(
+    "UpdateAllowListResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef",
     {
         "status": AutomatedDiscoveryStatusType,
     },
 )
 
@@ -1667,14 +1929,23 @@
     "UpdateClassificationJobRequestRequestTypeDef",
     {
         "jobId": str,
         "jobStatus": JobStatusType,
     },
 )
 
+UpdateFindingsFilterResponseTypeDef = TypedDict(
+    "UpdateFindingsFilterResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateMacieSessionRequestRequestTypeDef = TypedDict(
     "UpdateMacieSessionRequestRequestTypeDef",
     {
         "findingPublishingFrequency": FindingPublishingFrequencyType,
         "status": MacieStatusType,
     },
     total=False,
@@ -1748,209 +2019,56 @@
     "AccountLevelPermissionsTypeDef",
     {
         "blockPublicAccess": BlockPublicAccessTypeDef,
     },
     total=False,
 )
 
+ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    {
+        "adminAccounts": List[AdminAccountTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AllowListCriteriaTypeDef = TypedDict(
     "AllowListCriteriaTypeDef",
     {
         "regex": str,
         "s3WordsList": S3WordsListTypeDef,
     },
     total=False,
 )
 
+ListAllowListsResponseTypeDef = TypedDict(
+    "ListAllowListsResponseTypeDef",
+    {
+        "allowLists": List[AllowListSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FindingActionTypeDef = TypedDict(
     "FindingActionTypeDef",
     {
         "actionType": Literal["AWS_API_CALL"],
         "apiCallDetails": ApiCallDetailsTypeDef,
     },
     total=False,
 )
 
 BatchGetCustomDataIdentifiersResponseTypeDef = TypedDict(
     "BatchGetCustomDataIdentifiersResponseTypeDef",
     {
         "customDataIdentifiers": List[BatchGetCustomDataIdentifierSummaryTypeDef],
         "notFoundIdentifierIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAllowListResponseTypeDef = TypedDict(
-    "CreateAllowListResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateClassificationJobResponseTypeDef = TypedDict(
-    "CreateClassificationJobResponseTypeDef",
-    {
-        "jobArn": str,
-        "jobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomDataIdentifierResponseTypeDef = TypedDict(
-    "CreateCustomDataIdentifierResponseTypeDef",
-    {
-        "customDataIdentifierId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFindingsFilterResponseTypeDef = TypedDict(
-    "CreateFindingsFilterResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMemberResponseTypeDef = TypedDict(
-    "CreateMemberResponseTypeDef",
-    {
-        "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    {
-        "autoEnable": bool,
-        "maxAccountLimitReached": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAutomatedDiscoveryConfigurationResponseTypeDef = TypedDict(
-    "GetAutomatedDiscoveryConfigurationResponseTypeDef",
-    {
-        "classificationScopeId": str,
-        "disabledAt": datetime,
-        "firstEnabledAt": datetime,
-        "lastUpdatedAt": datetime,
-        "sensitivityInspectionTemplateId": str,
-        "status": AutomatedDiscoveryStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetInvitationsCountResponseTypeDef = TypedDict(
-    "GetInvitationsCountResponseTypeDef",
-    {
-        "invitationsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMacieSessionResponseTypeDef = TypedDict(
-    "GetMacieSessionResponseTypeDef",
-    {
-        "createdAt": datetime,
-        "findingPublishingFrequency": FindingPublishingFrequencyType,
-        "serviceRole": str,
-        "status": MacieStatusType,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetMemberResponseTypeDef = TypedDict(
-    "GetMemberResponseTypeDef",
-    {
-        "accountId": str,
-        "administratorAccountId": str,
-        "arn": str,
-        "email": str,
-        "invitedAt": datetime,
-        "masterAccountId": str,
-        "relationshipStatus": RelationshipStatusType,
-        "tags": Dict[str, str],
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSensitiveDataOccurrencesAvailabilityResponseTypeDef = TypedDict(
-    "GetSensitiveDataOccurrencesAvailabilityResponseTypeDef",
-    {
-        "code": AvailabilityCodeType,
-        "reasons": List[UnavailabilityReasonCodeType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAllowListsResponseTypeDef = TypedDict(
-    "ListAllowListsResponseTypeDef",
-    {
-        "allowLists": List[AllowListSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFindingsResponseTypeDef = TypedDict(
-    "ListFindingsResponseTypeDef",
-    {
-        "findingIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    {
-        "adminAccounts": List[AdminAccountTypeDef],
-        "nextToken": str,
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
-TestCustomDataIdentifierResponseTypeDef = TypedDict(
-    "TestCustomDataIdentifierResponseTypeDef",
-    {
-        "matchCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateAllowListResponseTypeDef = TypedDict(
-    "UpdateAllowListResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateFindingsFilterResponseTypeDef = TypedDict(
-    "UpdateFindingsFilterResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BucketLevelPermissionsTypeDef = TypedDict(
     "BucketLevelPermissionsTypeDef",
     {
         "accessControlList": AccessControlListTypeDef,
@@ -1978,14 +2096,24 @@
         "sizeInBytesCompressed": int,
         "unclassifiableObjectCount": ObjectLevelStatisticsTypeDef,
         "unclassifiableObjectSizeInBytes": ObjectLevelStatisticsTypeDef,
     },
     total=False,
 )
 
+DescribeBucketsRequestDescribeBucketsPaginateTypeDef = TypedDict(
+    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
+    {
+        "criteria": Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef],
+        "sortCriteria": BucketSortCriteriaTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeBucketsRequestRequestTypeDef = TypedDict(
     "DescribeBucketsRequestRequestTypeDef",
     {
         "criteria": Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef],
         "maxResults": int,
         "nextToken": str,
         "sortCriteria": BucketSortCriteriaTypeDef,
@@ -2013,15 +2141,15 @@
 )
 
 ListClassificationScopesResponseTypeDef = TypedDict(
     "ListClassificationScopesResponseTypeDef",
     {
         "classificationScopes": List[ClassificationScopeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCustomDataIdentifierRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCustomDataIdentifierRequestRequestTypeDef",
     {
         "name": str,
@@ -2059,39 +2187,39 @@
         "ignoreWords": List[str],
         "keywords": List[str],
         "maximumMatchDistance": int,
         "name": str,
         "regex": str,
         "severityLevels": List[SeverityLevelTypeDef],
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInvitationsResponseTypeDef = TypedDict(
     "CreateInvitationsResponseTypeDef",
     {
         "unprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineInvitationsResponseTypeDef = TypedDict(
     "DeclineInvitationsResponseTypeDef",
     {
         "unprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInvitationsResponseTypeDef = TypedDict(
     "DeleteInvitationsResponseTypeDef",
     {
         "unprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FindingCriteriaTypeDef = TypedDict(
     "FindingCriteriaTypeDef",
     {
         "criterion": Mapping[str, CriterionAdditionalPropertiesTypeDef],
@@ -2100,212 +2228,84 @@
 )
 
 ListCustomDataIdentifiersResponseTypeDef = TypedDict(
     "ListCustomDataIdentifiersResponseTypeDef",
     {
         "items": List[CustomDataIdentifierSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBucketsRequestDescribeBucketsPaginateTypeDef = TypedDict(
-    "DescribeBucketsRequestDescribeBucketsPaginateTypeDef",
-    {
-        "criteria": Mapping[str, BucketCriteriaAdditionalPropertiesTypeDef],
-        "sortCriteria": BucketSortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAllowListsRequestListAllowListsPaginateTypeDef = TypedDict(
-    "ListAllowListsRequestListAllowListsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListClassificationScopesRequestListClassificationScopesPaginateTypeDef = TypedDict(
-    "ListClassificationScopesRequestListClassificationScopesPaginateTypeDef",
-    {
-        "name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef = TypedDict(
-    "ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef = TypedDict(
-    "ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInvitationsRequestListInvitationsPaginateTypeDef = TypedDict(
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef = TypedDict(
-    "ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "ListMembersRequestListMembersPaginateTypeDef",
-    {
-        "onlyAssociated": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
-    "_RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef = TypedDict(
-    "_OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef(
-    _RequiredListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
-    _OptionalListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
-):
-    pass
-
-_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
-    TypedDict(
-        "_RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
-        {
-            "resourceArn": str,
-        },
-    )
-)
-_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef = (
-    TypedDict(
-        "_OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef(
-    _RequiredListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
-    _OptionalListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
-):
-    pass
-
-ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef = TypedDict(
-    "ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 GetSensitiveDataOccurrencesResponseTypeDef = TypedDict(
     "GetSensitiveDataOccurrencesResponseTypeDef",
     {
         "error": str,
         "sensitiveDataOccurrences": Dict[str, List[DetectedDataDetailsTypeDef]],
         "status": RevealRequestStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceProfileDetectionsResponseTypeDef = TypedDict(
     "ListResourceProfileDetectionsResponseTypeDef",
     {
         "detections": List[DetectionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFindingsFiltersResponseTypeDef = TypedDict(
     "ListFindingsFiltersResponseTypeDef",
     {
         "findingsFilterListItems": List[FindingsFilterListItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAdministratorAccountResponseTypeDef = TypedDict(
     "GetAdministratorAccountResponseTypeDef",
     {
         "administrator": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMasterAccountResponseTypeDef = TypedDict(
     "GetMasterAccountResponseTypeDef",
     {
         "master": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInvitationsResponseTypeDef = TypedDict(
     "ListInvitationsResponseTypeDef",
     {
         "invitations": List[InvitationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFindingStatisticsResponseTypeDef = TypedDict(
     "GetFindingStatisticsResponseTypeDef",
     {
         "countsByGroup": List[GroupCountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFindingsPublicationConfigurationResponseTypeDef = TypedDict(
     "GetFindingsPublicationConfigurationResponseTypeDef",
     {
         "securityHubConfiguration": SecurityHubConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutFindingsPublicationConfigurationRequestRequestTypeDef = TypedDict(
     "PutFindingsPublicationConfigurationRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -2336,38 +2336,38 @@
 GetResourceProfileResponseTypeDef = TypedDict(
     "GetResourceProfileResponseTypeDef",
     {
         "profileUpdatedAt": datetime,
         "sensitivityScore": int,
         "sensitivityScoreOverridden": bool,
         "statistics": ResourceStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRevealConfigurationResponseTypeDef = TypedDict(
     "GetRevealConfigurationResponseTypeDef",
     {
         "configuration": RevealConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRevealConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateRevealConfigurationRequestRequestTypeDef",
     {
         "configuration": RevealConfigurationTypeDef,
     },
 )
 
 UpdateRevealConfigurationResponseTypeDef = TypedDict(
     "UpdateRevealConfigurationResponseTypeDef",
     {
         "configuration": RevealConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetSensitiveDataOccurrencesRequestFindingRevealedWaitTypeDef = TypedDict(
     "_RequiredGetSensitiveDataOccurrencesRequestFindingRevealedWaitTypeDef",
     {
         "findingId": str,
@@ -2391,15 +2391,15 @@
     "GetSensitivityInspectionTemplateResponseTypeDef",
     {
         "description": str,
         "excludes": SensitivityInspectionTemplateExcludesTypeDef,
         "includes": SensitivityInspectionTemplateIncludesTypeDef,
         "name": str,
         "sensitivityInspectionTemplateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSensitivityInspectionTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSensitivityInspectionTemplateRequestRequestTypeDef",
     {
         "id": str,
@@ -2423,15 +2423,15 @@
 
 GetUsageStatisticsRequestGetUsageStatisticsPaginateTypeDef = TypedDict(
     "GetUsageStatisticsRequestGetUsageStatisticsPaginateTypeDef",
     {
         "filterBy": Sequence[UsageStatisticsFilterTypeDef],
         "sortBy": UsageStatisticsSortByTypeDef,
         "timeRange": TimeRangeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetUsageStatisticsRequestRequestTypeDef = TypedDict(
     "GetUsageStatisticsRequestRequestTypeDef",
     {
@@ -2445,15 +2445,15 @@
 )
 
 GetUsageTotalsResponseTypeDef = TypedDict(
     "GetUsageTotalsResponseTypeDef",
     {
         "timeRange": TimeRangeType,
         "usageTotals": List[UsageTotalTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IpAddressDetailsTypeDef = TypedDict(
     "IpAddressDetailsTypeDef",
     {
         "ipAddressV4": str,
@@ -2485,42 +2485,42 @@
 )
 
 ListManagedDataIdentifiersResponseTypeDef = TypedDict(
     "ListManagedDataIdentifiersResponseTypeDef",
     {
         "items": List[ManagedDataIdentifierSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembersResponseTypeDef = TypedDict(
     "ListMembersResponseTypeDef",
     {
         "members": List[MemberTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceProfileArtifactsResponseTypeDef = TypedDict(
     "ListResourceProfileArtifactsResponseTypeDef",
     {
         "artifacts": List[ResourceProfileArtifactTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSensitivityInspectionTemplatesResponseTypeDef = TypedDict(
     "ListSensitivityInspectionTemplatesResponseTypeDef",
     {
         "nextToken": str,
         "sensitivityInspectionTemplates": List[SensitivityInspectionTemplatesEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PageTypeDef = TypedDict(
     "PageTypeDef",
     {
         "lineRange": RangeTypeDef,
@@ -2662,15 +2662,15 @@
         "criteria": AllowListCriteriaTypeDef,
         "description": str,
         "id": str,
         "name": str,
         "status": AllowListStatusTypeDef,
         "tags": Dict[str, str],
         "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAllowListRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAllowListRequestRequestTypeDef",
     {
         "criteria": AllowListCriteriaTypeDef,
@@ -2723,38 +2723,38 @@
         "classifiableSizeInBytes": int,
         "lastUpdated": datetime,
         "objectCount": int,
         "sizeInBytes": int,
         "sizeInBytesCompressed": int,
         "unclassifiableObjectCount": ObjectLevelStatisticsTypeDef,
         "unclassifiableObjectSizeInBytes": ObjectLevelStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClassificationExportConfigurationResponseTypeDef = TypedDict(
     "GetClassificationExportConfigurationResponseTypeDef",
     {
         "configuration": ClassificationExportConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutClassificationExportConfigurationRequestRequestTypeDef = TypedDict(
     "PutClassificationExportConfigurationRequestRequestTypeDef",
     {
         "configuration": ClassificationExportConfigurationTypeDef,
     },
 )
 
 PutClassificationExportConfigurationResponseTypeDef = TypedDict(
     "PutClassificationExportConfigurationResponseTypeDef",
     {
         "configuration": ClassificationExportConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFindingsFilterRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFindingsFilterRequestRequestTypeDef",
     {
         "action": FindingsFilterActionType,
@@ -2808,24 +2808,24 @@
         "arn": str,
         "description": str,
         "findingCriteria": FindingCriteriaTypeDef,
         "id": str,
         "name": str,
         "position": int,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFindingsRequestListFindingsPaginateTypeDef = TypedDict(
     "ListFindingsRequestListFindingsPaginateTypeDef",
     {
         "findingCriteria": FindingCriteriaTypeDef,
         "sortCriteria": SortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListFindingsRequestRequestTypeDef = TypedDict(
     "ListFindingsRequestRequestTypeDef",
     {
@@ -2863,15 +2863,15 @@
     pass
 
 ListClassificationJobsRequestListClassificationJobsPaginateTypeDef = TypedDict(
     "ListClassificationJobsRequestListClassificationJobsPaginateTypeDef",
     {
         "filterCriteria": ListJobsFilterCriteriaTypeDef,
         "sortCriteria": ListJobsSortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListClassificationJobsRequestRequestTypeDef = TypedDict(
     "ListClassificationJobsRequestRequestTypeDef",
     {
@@ -2897,15 +2897,15 @@
 
 GetClassificationScopeResponseTypeDef = TypedDict(
     "GetClassificationScopeResponseTypeDef",
     {
         "id": str,
         "name": str,
         "s3": S3ClassificationScopeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateClassificationScopeRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateClassificationScopeRequestRequestTypeDef",
     {
         "id": str,
@@ -2997,15 +2997,15 @@
 )
 
 SearchResourcesResponseTypeDef = TypedDict(
     "SearchResourcesResponseTypeDef",
     {
         "matchingResources": List[MatchingResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomDetectionTypeDef = TypedDict(
     "CustomDetectionTypeDef",
     {
         "arn": str,
@@ -3036,15 +3036,15 @@
 
 GetUsageStatisticsResponseTypeDef = TypedDict(
     "GetUsageStatisticsResponseTypeDef",
     {
         "nextToken": str,
         "records": List[UsageRecordTypeDef],
         "timeRange": TimeRangeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UserIdentityTypeDef = TypedDict(
     "UserIdentityTypeDef",
     {
         "assumedRole": AssumedRoleTypeDef,
@@ -3179,15 +3179,15 @@
 )
 
 DescribeBucketsResponseTypeDef = TypedDict(
     "DescribeBucketsResponseTypeDef",
     {
         "buckets": List[BucketMetadataTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResourcesAffectedTypeDef = TypedDict(
     "ResourcesAffectedTypeDef",
     {
         "s3Bucket": S3BucketTypeDef,
@@ -3221,15 +3221,15 @@
 )
 
 SearchResourcesRequestSearchResourcesPaginateTypeDef = TypedDict(
     "SearchResourcesRequestSearchResourcesPaginateTypeDef",
     {
         "bucketCriteria": SearchResourcesBucketCriteriaTypeDef,
         "sortCriteria": SearchResourcesSortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 PolicyDetailsTypeDef = TypedDict(
     "PolicyDetailsTypeDef",
     {
@@ -3278,15 +3278,15 @@
 )
 
 ListClassificationJobsResponseTypeDef = TypedDict(
     "ListClassificationJobsResponseTypeDef",
     {
         "items": List[JobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateClassificationJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateClassificationJobRequestRequestTypeDef",
     {
         "clientToken": str,
@@ -3337,15 +3337,15 @@
         "name": str,
         "s3JobDefinition": S3JobDefinitionTypeDef,
         "samplingPercentage": int,
         "scheduleFrequency": JobScheduleFrequencyTypeDef,
         "statistics": StatisticsTypeDef,
         "tags": Dict[str, str],
         "userPausedDetails": UserPausedDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FindingTypeDef = TypedDict(
     "FindingTypeDef",
     {
         "accountId": str,
@@ -3370,10 +3370,10 @@
     total=False,
 )
 
 GetFindingsResponseTypeDef = TypedDict(
     "GetFindingsResponseTypeDef",
     {
         "findings": List[FindingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/waiter.py` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2/waiter.pyi` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/PKG-INFO` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-macie2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Macie2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Macie2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-macie2"></a>
 
 # types-aiobotocore-macie2
 
 [![PyPI - types-aiobotocore-macie2](https://img.shields.io/pypi/v/types-aiobotocore-macie2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-macie2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-macie2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-macie2?color=blue)](https://pypistats.org/packages/types-aiobotocore-macie2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Macie2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
+[aiobotocore.Macie2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/macie2.html#Macie2)
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
 [types-aiobotocore-macie2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_macie2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -473,15 +473,14 @@
     AllowListStatusTypeDef,
     AllowListSummaryTypeDef,
     ApiCallDetailsTypeDef,
     AwsAccountTypeDef,
     AwsServiceTypeDef,
     BatchGetCustomDataIdentifierSummaryTypeDef,
     BatchGetCustomDataIdentifiersRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     BucketCountByEffectivePermissionTypeDef,
     BucketCountByEncryptionTypeTypeDef,
     BucketCountBySharedAccessTypeTypeDef,
     BucketCountPolicyAllowsUnencryptedObjectUploadsTypeDef,
     BucketCriteriaAdditionalPropertiesTypeDef,
     BucketPolicyTypeDef,
     BucketServerSideEncryptionTypeDef,
@@ -492,56 +491,66 @@
     ReplicationDetailsTypeDef,
     BucketSortCriteriaTypeDef,
     SensitivityAggregationsTypeDef,
     CellTypeDef,
     S3DestinationTypeDef,
     ClassificationResultStatusTypeDef,
     ClassificationScopeSummaryTypeDef,
+    CreateAllowListResponseTypeDef,
+    CreateClassificationJobResponseTypeDef,
     SeverityLevelTypeDef,
+    CreateCustomDataIdentifierResponseTypeDef,
+    CreateFindingsFilterResponseTypeDef,
     CreateInvitationsRequestRequestTypeDef,
     UnprocessedAccountTypeDef,
+    CreateMemberResponseTypeDef,
     CreateSampleFindingsRequestRequestTypeDef,
     SimpleCriterionForJobTypeDef,
     CriterionAdditionalPropertiesTypeDef,
     CustomDataIdentifierSummaryTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DeleteAllowListRequestRequestTypeDef,
     DeleteCustomDataIdentifierRequestRequestTypeDef,
     DeleteFindingsFilterRequestRequestTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMemberRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     DescribeClassificationJobRequestRequestTypeDef,
     LastRunErrorStatusTypeDef,
     StatisticsTypeDef,
     UserPausedDetailsTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
     DetectedDataDetailsTypeDef,
     DetectionTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateMemberRequestRequestTypeDef,
     DomainDetailsTypeDef,
     EnableMacieRequestRequestTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     FindingStatisticsSortCriteriaTypeDef,
     SeverityTypeDef,
     FindingsFilterListItemTypeDef,
     InvitationTypeDef,
     GetAllowListRequestRequestTypeDef,
+    GetAutomatedDiscoveryConfigurationResponseTypeDef,
     GetBucketStatisticsRequestRequestTypeDef,
     GetClassificationScopeRequestRequestTypeDef,
     GetCustomDataIdentifierRequestRequestTypeDef,
     GroupCountTypeDef,
     GetFindingsFilterRequestRequestTypeDef,
     SecurityHubConfigurationTypeDef,
     SortCriteriaTypeDef,
+    GetInvitationsCountResponseTypeDef,
+    GetMacieSessionResponseTypeDef,
     GetMemberRequestRequestTypeDef,
+    GetMemberResponseTypeDef,
     GetResourceProfileRequestRequestTypeDef,
     ResourceStatisticsTypeDef,
     RevealConfigurationTypeDef,
     GetSensitiveDataOccurrencesAvailabilityRequestRequestTypeDef,
+    GetSensitiveDataOccurrencesAvailabilityResponseTypeDef,
     WaiterConfigTypeDef,
     GetSensitiveDataOccurrencesRequestRequestTypeDef,
     GetSensitivityInspectionTemplateRequestRequestTypeDef,
     SensitivityInspectionTemplateExcludesTypeDef,
     SensitivityInspectionTemplateIncludesTypeDef,
     UsageStatisticsFilterTypeDef,
     UsageStatisticsSortByTypeDef,
@@ -552,34 +561,49 @@
     IpCountryTypeDef,
     IpGeoLocationTypeDef,
     IpOwnerTypeDef,
     MonthlyScheduleTypeDef,
     WeeklyScheduleTypeDef,
     SimpleScopeTermTypeDef,
     S3BucketDefinitionForJobTypeDef,
+    ListAllowListsRequestListAllowListsPaginateTypeDef,
     ListAllowListsRequestRequestTypeDef,
     ListJobsSortCriteriaTypeDef,
+    ListClassificationScopesRequestListClassificationScopesPaginateTypeDef,
     ListClassificationScopesRequestRequestTypeDef,
+    ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef,
     ListCustomDataIdentifiersRequestRequestTypeDef,
+    ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef,
     ListFindingsFiltersRequestRequestTypeDef,
+    ListFindingsResponseTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
     ListJobsFilterTermTypeDef,
+    ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef,
     ListManagedDataIdentifiersRequestRequestTypeDef,
     ManagedDataIdentifierSummaryTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
     MemberTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
+    ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
     ListResourceProfileArtifactsRequestRequestTypeDef,
     ResourceProfileArtifactTypeDef,
+    ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
     ListResourceProfileDetectionsRequestRequestTypeDef,
+    ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef,
     ListSensitivityInspectionTemplatesRequestRequestTypeDef,
     SensitivityInspectionTemplatesEntryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     RangeTypeDef,
     RecordTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     S3BucketOwnerTypeDef,
     ServerSideEncryptionTypeDef,
     S3ClassificationScopeExclusionTypeDef,
     S3ClassificationScopeExclusionUpdateTypeDef,
     SearchResourcesSimpleCriterionTypeDef,
     SearchResourcesSortCriteriaTypeDef,
     SearchResourcesTagCriterionPairTypeDef,
@@ -587,70 +611,46 @@
     SessionContextAttributesTypeDef,
     SessionIssuerTypeDef,
     SuppressDataIdentifierTypeDef,
     TagCriterionPairForJobTypeDef,
     TagResourceRequestRequestTypeDef,
     TagValuePairTypeDef,
     TestCustomDataIdentifierRequestRequestTypeDef,
+    TestCustomDataIdentifierResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateAllowListResponseTypeDef,
     UpdateAutomatedDiscoveryConfigurationRequestRequestTypeDef,
     UpdateClassificationJobRequestRequestTypeDef,
+    UpdateFindingsFilterResponseTypeDef,
     UpdateMacieSessionRequestRequestTypeDef,
     UpdateMemberSessionRequestRequestTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     UpdateResourceProfileRequestRequestTypeDef,
     UserIdentityRootTypeDef,
     CreateMemberRequestRequestTypeDef,
     AccountLevelPermissionsTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
     AllowListCriteriaTypeDef,
+    ListAllowListsResponseTypeDef,
     FindingActionTypeDef,
     BatchGetCustomDataIdentifiersResponseTypeDef,
-    CreateAllowListResponseTypeDef,
-    CreateClassificationJobResponseTypeDef,
-    CreateCustomDataIdentifierResponseTypeDef,
-    CreateFindingsFilterResponseTypeDef,
-    CreateMemberResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    GetAutomatedDiscoveryConfigurationResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    GetMacieSessionResponseTypeDef,
-    GetMemberResponseTypeDef,
-    GetSensitiveDataOccurrencesAvailabilityResponseTypeDef,
-    ListAllowListsResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    TestCustomDataIdentifierResponseTypeDef,
-    UpdateAllowListResponseTypeDef,
-    UpdateFindingsFilterResponseTypeDef,
     BucketLevelPermissionsTypeDef,
     MatchingBucketTypeDef,
+    DescribeBucketsRequestDescribeBucketsPaginateTypeDef,
     DescribeBucketsRequestRequestTypeDef,
     BucketStatisticsBySensitivityTypeDef,
     ClassificationExportConfigurationTypeDef,
     ListClassificationScopesResponseTypeDef,
     CreateCustomDataIdentifierRequestRequestTypeDef,
     GetCustomDataIdentifierResponseTypeDef,
     CreateInvitationsResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     FindingCriteriaTypeDef,
     ListCustomDataIdentifiersResponseTypeDef,
-    DescribeBucketsRequestDescribeBucketsPaginateTypeDef,
-    ListAllowListsRequestListAllowListsPaginateTypeDef,
-    ListClassificationScopesRequestListClassificationScopesPaginateTypeDef,
-    ListCustomDataIdentifiersRequestListCustomDataIdentifiersPaginateTypeDef,
-    ListFindingsFiltersRequestListFindingsFiltersPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListManagedDataIdentifiersRequestListManagedDataIdentifiersPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
-    ListResourceProfileArtifactsRequestListResourceProfileArtifactsPaginateTypeDef,
-    ListResourceProfileDetectionsRequestListResourceProfileDetectionsPaginateTypeDef,
-    ListSensitivityInspectionTemplatesRequestListSensitivityInspectionTemplatesPaginateTypeDef,
     GetSensitiveDataOccurrencesResponseTypeDef,
     ListResourceProfileDetectionsResponseTypeDef,
     ListFindingsFiltersResponseTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     ListInvitationsResponseTypeDef,
     GetFindingStatisticsResponseTypeDef,
@@ -751,43 +751,43 @@
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

### Comparing `types-aiobotocore-macie2-2.5.0.post1/types_aiobotocore_macie2.egg-info/SOURCES.txt` & `types-aiobotocore-macie2-2.5.1/types_aiobotocore_macie2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

