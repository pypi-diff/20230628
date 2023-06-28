# Comparing `tmp/types-aiobotocore-guardduty-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-guardduty-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-guardduty-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:42 2023, max compression
+gzip compressed data, was "types-aiobotocore-guardduty-2.5.1.tar", last modified: Wed Jun 28 01:43:34 2023, max compression
```

## Comparing `types-aiobotocore-guardduty-2.5.0.post1.tar` & `types-aiobotocore-guardduty-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.115251 types-aiobotocore-guardduty-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    24129 2023-03-11 12:26:42.115251 types-aiobotocore-guardduty-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    22550 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:42.115251 types-aiobotocore-guardduty-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:15:29.000000 types-aiobotocore-guardduty-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.115251 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/
--rw-r--r--   0 runner    (1001) docker     (123)     2303 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2302 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    49646 2023-03-11 12:15:31.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    49563 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11267 2023-03-11 12:15:32.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11265 2023-03-11 12:15:31.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11379 2023-03-11 12:15:31.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    11367 2023-03-11 12:15:31.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    77828 2023-03-11 12:15:33.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    77749 2023-03-11 12:15:32.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:30.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:42.115251 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    24129 2023-03-11 12:26:41.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:26:41.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:41.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:41.000000 types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.994145 types-aiobotocore-guardduty-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:06.000000 types-aiobotocore-guardduty-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    26224 2023-06-28 01:43:33.994145 types-aiobotocore-guardduty-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    24651 2023-06-28 01:32:06.000000 types-aiobotocore-guardduty-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:33.994145 types-aiobotocore-guardduty-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:32:05.000000 types-aiobotocore-guardduty-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.994145 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/
+-rw-r--r--   0 runner    (1001) docker     (123)     2481 2023-06-28 01:32:06.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2480 2023-06-28 01:32:06.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:32:06.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52639 2023-06-28 01:32:07.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52552 2023-06-28 01:32:07.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14015 2023-06-28 01:32:07.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14013 2023-06-28 01:32:07.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12552 2023-06-28 01:32:07.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12540 2023-06-28 01:32:07.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:06.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    93113 2023-06-28 01:32:09.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    93026 2023-06-28 01:32:08.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:06.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.994145 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    26224 2023-06-28 01:43:33.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:43:33.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:33.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:33.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:33.000000 types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/LICENSE` & `types-aiobotocore-guardduty-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/PKG-INFO` & `types-aiobotocore-guardduty-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-guardduty
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GuardDuty 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GuardDuty 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-guardduty"></a>
 
 # types-aiobotocore-guardduty
 
 [![PyPI - types-aiobotocore-guardduty](https://img.shields.io/pypi/v/types-aiobotocore-guardduty.svg?color=blue)](https://pypi.org/project/types-aiobotocore-guardduty)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-guardduty.svg?color=blue)](https://pypi.org/project/types-aiobotocore-guardduty)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-guardduty?color=blue)](https://pypistats.org/packages/types-aiobotocore-guardduty)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GuardDuty 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
+[aiobotocore.GuardDuty 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
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
 [types-aiobotocore-guardduty docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,14 +274,15 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_guardduty import GuardDutyClient
 from types_aiobotocore_guardduty.paginator import (
     DescribeMalwareScansPaginator,
+    ListCoveragePaginator,
     ListDetectorsPaginator,
     ListFiltersPaginator,
     ListFindingsPaginator,
     ListIPSetsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
@@ -293,14 +294,15 @@
     client: GuardDutyClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     describe_malware_scans_paginator: DescribeMalwareScansPaginator = client.get_paginator(
         "describe_malware_scans"
     )
+    list_coverage_paginator: ListCoveragePaginator = client.get_paginator("list_coverage")
     list_detectors_paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
     list_filters_paginator: ListFiltersPaginator = client.get_paginator("list_filters")
     list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
     list_ip_sets_paginator: ListIPSetsPaginator = client.get_paginator("list_ip_sets")
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = (
@@ -317,42 +319,59 @@
 
 `types_aiobotocore_guardduty.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_guardduty.literals import (
     AdminStatusType,
+    AutoEnableMembersType,
+    CoverageFilterCriterionKeyType,
+    CoverageSortKeyType,
+    CoverageStatisticsTypeType,
+    CoverageStatusType,
     CriterionKeyType,
     DataSourceStatusType,
     DataSourceType,
     DescribeMalwareScansPaginatorName,
     DestinationTypeType,
+    DetectorFeatureResultType,
+    DetectorFeatureType,
     DetectorStatusType,
     EbsSnapshotPreservationType,
+    FeatureAdditionalConfigurationType,
+    FeatureStatusType,
     FeedbackType,
     FilterActionType,
     FindingPublishingFrequencyType,
     FindingStatisticTypeType,
+    FreeTrialFeatureResultType,
     IpSetFormatType,
     IpSetStatusType,
+    ListCoveragePaginatorName,
     ListDetectorsPaginatorName,
     ListFiltersPaginatorName,
     ListFindingsPaginatorName,
     ListIPSetsPaginatorName,
     ListInvitationsPaginatorName,
     ListMembersPaginatorName,
     ListOrganizationAdminAccountsPaginatorName,
     ListThreatIntelSetsPaginatorName,
     OrderByType,
+    OrgFeatureAdditionalConfigurationType,
+    OrgFeatureStatusType,
+    OrgFeatureType,
     PublishingStatusType,
+    ResourceTypeType,
     ScanCriterionKeyType,
     ScanResultType,
     ScanStatusType,
+    ScanTypeType,
     ThreatIntelSetFormatType,
     ThreatIntelSetStatusType,
+    UsageFeatureType,
     UsageStatisticTypeType,
     GuardDutyServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -372,53 +391,62 @@
 ```python
 from types_aiobotocore_guardduty.type_defs import (
     AcceptAdministratorInvitationRequestRequestTypeDef,
     AcceptInvitationRequestRequestTypeDef,
     AccessControlListTypeDef,
     AccessKeyDetailsTypeDef,
     AccountDetailTypeDef,
+    FreeTrialFeatureConfigurationResultTypeDef,
     BlockPublicAccessTypeDef,
     DnsRequestActionTypeDef,
+    AddonDetailsTypeDef,
     AdminAccountTypeDef,
     AdministratorTypeDef,
     ArchiveFindingsRequestRequestTypeDef,
     DomainDetailsTypeDef,
     RemoteAccountDetailsTypeDef,
     BucketPolicyTypeDef,
     CityTypeDef,
     CloudTrailConfigurationResultTypeDef,
     ConditionTypeDef,
     SecurityContextTypeDef,
     VolumeMountTypeDef,
     CountryTypeDef,
-    ResponseMetadataTypeDef,
+    CoverageFilterConditionTypeDef,
+    CoverageSortCriteriaTypeDef,
+    CoverageStatisticsTypeDef,
+    CreateFilterResponseTypeDef,
     CreateIPSetRequestRequestTypeDef,
+    CreateIPSetResponseTypeDef,
     UnprocessedAccountTypeDef,
     DestinationPropertiesTypeDef,
+    CreatePublishingDestinationResponseTypeDef,
     CreateSampleFindingsRequestRequestTypeDef,
     CreateThreatIntelSetRequestRequestTypeDef,
+    CreateThreatIntelSetResponseTypeDef,
     DNSLogsConfigurationResultTypeDef,
     FlowLogsConfigurationResultTypeDef,
     S3LogsConfigurationResultTypeDef,
     S3LogsConfigurationTypeDef,
     DataSourceFreeTrialTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DefaultServerSideEncryptionTypeDef,
     DeleteDetectorRequestRequestTypeDef,
     DeleteFilterRequestRequestTypeDef,
     DeleteIPSetRequestRequestTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
     DeletePublishingDestinationRequestRequestTypeDef,
     DeleteThreatIntelSetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     SortCriteriaTypeDef,
     DescribeOrganizationConfigurationRequestRequestTypeDef,
     DescribePublishingDestinationRequestRequestTypeDef,
     DestinationTypeDef,
+    DetectorAdditionalConfigurationResultTypeDef,
+    DetectorAdditionalConfigurationTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateFromAdministratorAccountRequestRequestTypeDef,
     DisassociateFromMasterAccountRequestRequestTypeDef,
     DisassociateMembersRequestRequestTypeDef,
     VolumeDetailTypeDef,
     EbsVolumesResultTypeDef,
     TagTypeDef,
@@ -427,185 +455,216 @@
     FilterConditionTypeDef,
     FindingStatisticsTypeDef,
     GeoLocationTypeDef,
     GetAdministratorAccountRequestRequestTypeDef,
     GetDetectorRequestRequestTypeDef,
     GetFilterRequestRequestTypeDef,
     GetIPSetRequestRequestTypeDef,
+    GetIPSetResponseTypeDef,
+    GetInvitationsCountResponseTypeDef,
     GetMalwareScanSettingsRequestRequestTypeDef,
     GetMasterAccountRequestRequestTypeDef,
     MasterTypeDef,
     GetMemberDetectorsRequestRequestTypeDef,
     GetMembersRequestRequestTypeDef,
     MemberTypeDef,
     GetRemainingFreeTrialDaysRequestRequestTypeDef,
     GetThreatIntelSetRequestRequestTypeDef,
+    GetThreatIntelSetResponseTypeDef,
     UsageCriteriaTypeDef,
     HighestSeverityThreatDetailsTypeDef,
     HostPathTypeDef,
     IamInstanceProfileTypeDef,
     ProductCodeTypeDef,
     InvitationTypeDef,
     InviteMembersRequestRequestTypeDef,
     KubernetesAuditLogsConfigurationResultTypeDef,
     KubernetesAuditLogsConfigurationTypeDef,
     KubernetesUserDetailsTypeDef,
+    LineageObjectTypeDef,
+    ListDetectorsRequestListDetectorsPaginateTypeDef,
     ListDetectorsRequestRequestTypeDef,
+    ListDetectorsResponseTypeDef,
+    ListFiltersRequestListFiltersPaginateTypeDef,
     ListFiltersRequestRequestTypeDef,
+    ListFiltersResponseTypeDef,
+    ListFindingsResponseTypeDef,
+    ListIPSetsRequestListIPSetsPaginateTypeDef,
     ListIPSetsRequestRequestTypeDef,
+    ListIPSetsResponseTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
     ListPublishingDestinationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
     ListThreatIntelSetsRequestRequestTypeDef,
+    ListThreatIntelSetsResponseTypeDef,
     LocalIpDetailsTypeDef,
     LocalPortDetailsTypeDef,
+    LoginAttributeTypeDef,
     ScanEc2InstanceWithFindingsTypeDef,
+    MemberAdditionalConfigurationResultTypeDef,
+    MemberAdditionalConfigurationTypeDef,
     RemotePortDetailsTypeDef,
     PrivateIpAddressDetailsTypeDef,
     SecurityGroupTypeDef,
+    OrganizationAdditionalConfigurationResultTypeDef,
+    OrganizationAdditionalConfigurationTypeDef,
     OrganizationS3LogsConfigurationResultTypeDef,
     OrganizationS3LogsConfigurationTypeDef,
     OrganizationEbsVolumesResultTypeDef,
     OrganizationEbsVolumesTypeDef,
     OrganizationKubernetesAuditLogsConfigurationResultTypeDef,
     OrganizationKubernetesAuditLogsConfigurationTypeDef,
     OrganizationTypeDef,
     OwnerTypeDef,
+    PaginatorConfigTypeDef,
+    RdsDbUserDetailsTypeDef,
     ResourceDetailsTypeDef,
+    ResponseMetadataTypeDef,
     ScanConditionPairTypeDef,
     ScannedItemCountTypeDef,
     ThreatsDetectedItemCountTypeDef,
     ScanFilePathTypeDef,
     ScanResultDetailsTypeDef,
     TriggerDetailsTypeDef,
     ServiceAdditionalInfoTypeDef,
+    StartMalwareScanRequestRequestTypeDef,
+    StartMalwareScanResponseTypeDef,
     StartMonitoringMembersRequestRequestTypeDef,
     StopMonitoringMembersRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TotalTypeDef,
     UnarchiveFindingsRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateFilterResponseTypeDef,
     UpdateFindingsFeedbackRequestRequestTypeDef,
     UpdateIPSetRequestRequestTypeDef,
     UpdateThreatIntelSetRequestRequestTypeDef,
     CreateMembersRequestRequestTypeDef,
     AccountLevelPermissionsTypeDef,
+    CoverageEksClusterDetailsTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
+    GetAdministratorAccountResponseTypeDef,
     BucketLevelPermissionsTypeDef,
     FindingCriteriaTypeDef,
     ContainerTypeDef,
-    CreateFilterResponseTypeDef,
-    CreateIPSetResponseTypeDef,
-    CreatePublishingDestinationResponseTypeDef,
-    CreateThreatIntelSetResponseTypeDef,
-    GetAdministratorAccountResponseTypeDef,
-    GetIPSetResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    GetThreatIntelSetResponseTypeDef,
-    ListDetectorsResponseTypeDef,
-    ListFiltersResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListIPSetsResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListThreatIntelSetsResponseTypeDef,
-    UpdateFilterResponseTypeDef,
+    CoverageFilterCriterionTypeDef,
+    GetCoverageStatisticsResponseTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DisassociateMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
     StartMonitoringMembersResponseTypeDef,
     StopMonitoringMembersResponseTypeDef,
     UpdateMemberDetectorsResponseTypeDef,
     CreatePublishingDestinationRequestRequestTypeDef,
     DescribePublishingDestinationResponseTypeDef,
     UpdatePublishingDestinationRequestRequestTypeDef,
     KubernetesDataSourceFreeTrialTypeDef,
     MalwareProtectionDataSourceFreeTrialTypeDef,
-    ListDetectorsRequestListDetectorsPaginateTypeDef,
-    ListFiltersRequestListFiltersPaginateTypeDef,
-    ListIPSetsRequestListIPSetsPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
-    ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
     GetFindingsRequestRequestTypeDef,
     ListPublishingDestinationsResponseTypeDef,
+    DetectorFeatureConfigurationResultTypeDef,
+    DetectorFeatureConfigurationTypeDef,
     EbsVolumeDetailsTypeDef,
     ScanEc2InstanceWithFindingsResultTypeDef,
     EksClusterDetailsTypeDef,
+    RdsDbInstanceDetailsTypeDef,
     EvidenceTypeDef,
     FilterCriterionTypeDef,
     GetFindingsStatisticsResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     GetMembersResponseTypeDef,
     ListMembersResponseTypeDef,
     GetUsageStatisticsRequestRequestTypeDef,
     VolumeTypeDef,
     ListInvitationsResponseTypeDef,
     KubernetesConfigurationResultTypeDef,
     KubernetesConfigurationTypeDef,
+    ProcessDetailsTypeDef,
     MalwareProtectionConfigurationTypeDef,
+    MemberFeaturesConfigurationResultTypeDef,
+    MemberFeaturesConfigurationTypeDef,
     NetworkInterfaceTypeDef,
+    VpcConfigTypeDef,
+    OrganizationFeatureConfigurationResultTypeDef,
+    OrganizationFeatureConfigurationTypeDef,
     OrganizationScanEc2InstanceWithFindingsResultTypeDef,
     OrganizationScanEc2InstanceWithFindingsTypeDef,
     OrganizationKubernetesConfigurationResultTypeDef,
     OrganizationKubernetesConfigurationTypeDef,
     RemoteIpDetailsTypeDef,
     ScanConditionTypeDef,
     ScanThreatNameTypeDef,
     ScanTypeDef,
     UsageAccountResultTypeDef,
     UsageDataSourceResultTypeDef,
+    UsageFeatureResultTypeDef,
     UsageResourceResultTypeDef,
+    CoverageResourceDetailsTypeDef,
     PermissionConfigurationTypeDef,
     CreateFilterRequestRequestTypeDef,
     GetFilterResponseTypeDef,
     GetFindingsStatisticsRequestRequestTypeDef,
     ListFindingsRequestListFindingsPaginateTypeDef,
     ListFindingsRequestRequestTypeDef,
     UpdateFilterRequestRequestTypeDef,
+    CoverageFilterCriteriaTypeDef,
     DataSourcesFreeTrialTypeDef,
     MalwareProtectionConfigurationResultTypeDef,
     FilterCriteriaTypeDef,
     EcsTaskDetailsTypeDef,
     KubernetesWorkloadDetailsTypeDef,
+    RuntimeContextTypeDef,
     DataSourceConfigurationsTypeDef,
     InstanceDetailsTypeDef,
+    LambdaDetailsTypeDef,
     OrganizationMalwareProtectionConfigurationResultTypeDef,
     OrganizationMalwareProtectionConfigurationTypeDef,
     AwsApiCallActionTypeDef,
     KubernetesApiCallActionTypeDef,
     NetworkConnectionActionTypeDef,
     PortProbeDetailTypeDef,
+    RdsLoginAttemptActionTypeDef,
     ScanResourceCriteriaTypeDef,
     ThreatDetectedByNameTypeDef,
     DescribeMalwareScansResponseTypeDef,
     UsageStatisticsTypeDef,
+    CoverageResourceTypeDef,
     PublicAccessTypeDef,
+    GetCoverageStatisticsRequestRequestTypeDef,
+    ListCoverageRequestListCoveragePaginateTypeDef,
+    ListCoverageRequestRequestTypeDef,
     AccountFreeTrialInfoTypeDef,
     DataSourceConfigurationsResultTypeDef,
     UnprocessedDataSourcesResultTypeDef,
     DescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef,
     DescribeMalwareScansRequestRequestTypeDef,
     EcsClusterDetailsTypeDef,
     KubernetesDetailsTypeDef,
+    RuntimeDetailsTypeDef,
     CreateDetectorRequestRequestTypeDef,
     UpdateDetectorRequestRequestTypeDef,
     UpdateMemberDetectorsRequestRequestTypeDef,
     OrganizationDataSourceConfigurationsResultTypeDef,
     OrganizationDataSourceConfigurationsTypeDef,
     PortProbeActionTypeDef,
     GetMalwareScanSettingsResponseTypeDef,
     UpdateMalwareScanSettingsRequestRequestTypeDef,
     ScanDetectionsTypeDef,
     GetUsageStatisticsResponseTypeDef,
+    ListCoverageResponseTypeDef,
     S3BucketDetailTypeDef,
     GetRemainingFreeTrialDaysResponseTypeDef,
     GetDetectorResponseTypeDef,
     MemberDataSourceConfigurationTypeDef,
     CreateDetectorResponseTypeDef,
     DescribeOrganizationConfigurationResponseTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
@@ -626,43 +685,43 @@
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

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/README.md` & `types-aiobotocore-guardduty-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-guardduty"></a>
 
 # types-aiobotocore-guardduty
 
 [![PyPI - types-aiobotocore-guardduty](https://img.shields.io/pypi/v/types-aiobotocore-guardduty.svg?color=blue)](https://pypi.org/project/types-aiobotocore-guardduty)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-guardduty.svg?color=blue)](https://pypi.org/project/types-aiobotocore-guardduty)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-guardduty?color=blue)](https://pypistats.org/packages/types-aiobotocore-guardduty)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GuardDuty 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
+[aiobotocore.GuardDuty 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
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
 [types-aiobotocore-guardduty docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/).
 
 See how it helps to find and fix potential bugs:
 
@@ -241,14 +241,15 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_guardduty import GuardDutyClient
 from types_aiobotocore_guardduty.paginator import (
     DescribeMalwareScansPaginator,
+    ListCoveragePaginator,
     ListDetectorsPaginator,
     ListFiltersPaginator,
     ListFindingsPaginator,
     ListIPSetsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
@@ -260,14 +261,15 @@
     client: GuardDutyClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     describe_malware_scans_paginator: DescribeMalwareScansPaginator = client.get_paginator(
         "describe_malware_scans"
     )
+    list_coverage_paginator: ListCoveragePaginator = client.get_paginator("list_coverage")
     list_detectors_paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
     list_filters_paginator: ListFiltersPaginator = client.get_paginator("list_filters")
     list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
     list_ip_sets_paginator: ListIPSetsPaginator = client.get_paginator("list_ip_sets")
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = (
@@ -284,42 +286,59 @@
 
 `types_aiobotocore_guardduty.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_guardduty.literals import (
     AdminStatusType,
+    AutoEnableMembersType,
+    CoverageFilterCriterionKeyType,
+    CoverageSortKeyType,
+    CoverageStatisticsTypeType,
+    CoverageStatusType,
     CriterionKeyType,
     DataSourceStatusType,
     DataSourceType,
     DescribeMalwareScansPaginatorName,
     DestinationTypeType,
+    DetectorFeatureResultType,
+    DetectorFeatureType,
     DetectorStatusType,
     EbsSnapshotPreservationType,
+    FeatureAdditionalConfigurationType,
+    FeatureStatusType,
     FeedbackType,
     FilterActionType,
     FindingPublishingFrequencyType,
     FindingStatisticTypeType,
+    FreeTrialFeatureResultType,
     IpSetFormatType,
     IpSetStatusType,
+    ListCoveragePaginatorName,
     ListDetectorsPaginatorName,
     ListFiltersPaginatorName,
     ListFindingsPaginatorName,
     ListIPSetsPaginatorName,
     ListInvitationsPaginatorName,
     ListMembersPaginatorName,
     ListOrganizationAdminAccountsPaginatorName,
     ListThreatIntelSetsPaginatorName,
     OrderByType,
+    OrgFeatureAdditionalConfigurationType,
+    OrgFeatureStatusType,
+    OrgFeatureType,
     PublishingStatusType,
+    ResourceTypeType,
     ScanCriterionKeyType,
     ScanResultType,
     ScanStatusType,
+    ScanTypeType,
     ThreatIntelSetFormatType,
     ThreatIntelSetStatusType,
+    UsageFeatureType,
     UsageStatisticTypeType,
     GuardDutyServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -339,53 +358,62 @@
 ```python
 from types_aiobotocore_guardduty.type_defs import (
     AcceptAdministratorInvitationRequestRequestTypeDef,
     AcceptInvitationRequestRequestTypeDef,
     AccessControlListTypeDef,
     AccessKeyDetailsTypeDef,
     AccountDetailTypeDef,
+    FreeTrialFeatureConfigurationResultTypeDef,
     BlockPublicAccessTypeDef,
     DnsRequestActionTypeDef,
+    AddonDetailsTypeDef,
     AdminAccountTypeDef,
     AdministratorTypeDef,
     ArchiveFindingsRequestRequestTypeDef,
     DomainDetailsTypeDef,
     RemoteAccountDetailsTypeDef,
     BucketPolicyTypeDef,
     CityTypeDef,
     CloudTrailConfigurationResultTypeDef,
     ConditionTypeDef,
     SecurityContextTypeDef,
     VolumeMountTypeDef,
     CountryTypeDef,
-    ResponseMetadataTypeDef,
+    CoverageFilterConditionTypeDef,
+    CoverageSortCriteriaTypeDef,
+    CoverageStatisticsTypeDef,
+    CreateFilterResponseTypeDef,
     CreateIPSetRequestRequestTypeDef,
+    CreateIPSetResponseTypeDef,
     UnprocessedAccountTypeDef,
     DestinationPropertiesTypeDef,
+    CreatePublishingDestinationResponseTypeDef,
     CreateSampleFindingsRequestRequestTypeDef,
     CreateThreatIntelSetRequestRequestTypeDef,
+    CreateThreatIntelSetResponseTypeDef,
     DNSLogsConfigurationResultTypeDef,
     FlowLogsConfigurationResultTypeDef,
     S3LogsConfigurationResultTypeDef,
     S3LogsConfigurationTypeDef,
     DataSourceFreeTrialTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DefaultServerSideEncryptionTypeDef,
     DeleteDetectorRequestRequestTypeDef,
     DeleteFilterRequestRequestTypeDef,
     DeleteIPSetRequestRequestTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
     DeletePublishingDestinationRequestRequestTypeDef,
     DeleteThreatIntelSetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     SortCriteriaTypeDef,
     DescribeOrganizationConfigurationRequestRequestTypeDef,
     DescribePublishingDestinationRequestRequestTypeDef,
     DestinationTypeDef,
+    DetectorAdditionalConfigurationResultTypeDef,
+    DetectorAdditionalConfigurationTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateFromAdministratorAccountRequestRequestTypeDef,
     DisassociateFromMasterAccountRequestRequestTypeDef,
     DisassociateMembersRequestRequestTypeDef,
     VolumeDetailTypeDef,
     EbsVolumesResultTypeDef,
     TagTypeDef,
@@ -394,185 +422,216 @@
     FilterConditionTypeDef,
     FindingStatisticsTypeDef,
     GeoLocationTypeDef,
     GetAdministratorAccountRequestRequestTypeDef,
     GetDetectorRequestRequestTypeDef,
     GetFilterRequestRequestTypeDef,
     GetIPSetRequestRequestTypeDef,
+    GetIPSetResponseTypeDef,
+    GetInvitationsCountResponseTypeDef,
     GetMalwareScanSettingsRequestRequestTypeDef,
     GetMasterAccountRequestRequestTypeDef,
     MasterTypeDef,
     GetMemberDetectorsRequestRequestTypeDef,
     GetMembersRequestRequestTypeDef,
     MemberTypeDef,
     GetRemainingFreeTrialDaysRequestRequestTypeDef,
     GetThreatIntelSetRequestRequestTypeDef,
+    GetThreatIntelSetResponseTypeDef,
     UsageCriteriaTypeDef,
     HighestSeverityThreatDetailsTypeDef,
     HostPathTypeDef,
     IamInstanceProfileTypeDef,
     ProductCodeTypeDef,
     InvitationTypeDef,
     InviteMembersRequestRequestTypeDef,
     KubernetesAuditLogsConfigurationResultTypeDef,
     KubernetesAuditLogsConfigurationTypeDef,
     KubernetesUserDetailsTypeDef,
+    LineageObjectTypeDef,
+    ListDetectorsRequestListDetectorsPaginateTypeDef,
     ListDetectorsRequestRequestTypeDef,
+    ListDetectorsResponseTypeDef,
+    ListFiltersRequestListFiltersPaginateTypeDef,
     ListFiltersRequestRequestTypeDef,
+    ListFiltersResponseTypeDef,
+    ListFindingsResponseTypeDef,
+    ListIPSetsRequestListIPSetsPaginateTypeDef,
     ListIPSetsRequestRequestTypeDef,
+    ListIPSetsResponseTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
     ListPublishingDestinationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
     ListThreatIntelSetsRequestRequestTypeDef,
+    ListThreatIntelSetsResponseTypeDef,
     LocalIpDetailsTypeDef,
     LocalPortDetailsTypeDef,
+    LoginAttributeTypeDef,
     ScanEc2InstanceWithFindingsTypeDef,
+    MemberAdditionalConfigurationResultTypeDef,
+    MemberAdditionalConfigurationTypeDef,
     RemotePortDetailsTypeDef,
     PrivateIpAddressDetailsTypeDef,
     SecurityGroupTypeDef,
+    OrganizationAdditionalConfigurationResultTypeDef,
+    OrganizationAdditionalConfigurationTypeDef,
     OrganizationS3LogsConfigurationResultTypeDef,
     OrganizationS3LogsConfigurationTypeDef,
     OrganizationEbsVolumesResultTypeDef,
     OrganizationEbsVolumesTypeDef,
     OrganizationKubernetesAuditLogsConfigurationResultTypeDef,
     OrganizationKubernetesAuditLogsConfigurationTypeDef,
     OrganizationTypeDef,
     OwnerTypeDef,
+    PaginatorConfigTypeDef,
+    RdsDbUserDetailsTypeDef,
     ResourceDetailsTypeDef,
+    ResponseMetadataTypeDef,
     ScanConditionPairTypeDef,
     ScannedItemCountTypeDef,
     ThreatsDetectedItemCountTypeDef,
     ScanFilePathTypeDef,
     ScanResultDetailsTypeDef,
     TriggerDetailsTypeDef,
     ServiceAdditionalInfoTypeDef,
+    StartMalwareScanRequestRequestTypeDef,
+    StartMalwareScanResponseTypeDef,
     StartMonitoringMembersRequestRequestTypeDef,
     StopMonitoringMembersRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TotalTypeDef,
     UnarchiveFindingsRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateFilterResponseTypeDef,
     UpdateFindingsFeedbackRequestRequestTypeDef,
     UpdateIPSetRequestRequestTypeDef,
     UpdateThreatIntelSetRequestRequestTypeDef,
     CreateMembersRequestRequestTypeDef,
     AccountLevelPermissionsTypeDef,
+    CoverageEksClusterDetailsTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
+    GetAdministratorAccountResponseTypeDef,
     BucketLevelPermissionsTypeDef,
     FindingCriteriaTypeDef,
     ContainerTypeDef,
-    CreateFilterResponseTypeDef,
-    CreateIPSetResponseTypeDef,
-    CreatePublishingDestinationResponseTypeDef,
-    CreateThreatIntelSetResponseTypeDef,
-    GetAdministratorAccountResponseTypeDef,
-    GetIPSetResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    GetThreatIntelSetResponseTypeDef,
-    ListDetectorsResponseTypeDef,
-    ListFiltersResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListIPSetsResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListThreatIntelSetsResponseTypeDef,
-    UpdateFilterResponseTypeDef,
+    CoverageFilterCriterionTypeDef,
+    GetCoverageStatisticsResponseTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DisassociateMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
     StartMonitoringMembersResponseTypeDef,
     StopMonitoringMembersResponseTypeDef,
     UpdateMemberDetectorsResponseTypeDef,
     CreatePublishingDestinationRequestRequestTypeDef,
     DescribePublishingDestinationResponseTypeDef,
     UpdatePublishingDestinationRequestRequestTypeDef,
     KubernetesDataSourceFreeTrialTypeDef,
     MalwareProtectionDataSourceFreeTrialTypeDef,
-    ListDetectorsRequestListDetectorsPaginateTypeDef,
-    ListFiltersRequestListFiltersPaginateTypeDef,
-    ListIPSetsRequestListIPSetsPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
-    ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
     GetFindingsRequestRequestTypeDef,
     ListPublishingDestinationsResponseTypeDef,
+    DetectorFeatureConfigurationResultTypeDef,
+    DetectorFeatureConfigurationTypeDef,
     EbsVolumeDetailsTypeDef,
     ScanEc2InstanceWithFindingsResultTypeDef,
     EksClusterDetailsTypeDef,
+    RdsDbInstanceDetailsTypeDef,
     EvidenceTypeDef,
     FilterCriterionTypeDef,
     GetFindingsStatisticsResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     GetMembersResponseTypeDef,
     ListMembersResponseTypeDef,
     GetUsageStatisticsRequestRequestTypeDef,
     VolumeTypeDef,
     ListInvitationsResponseTypeDef,
     KubernetesConfigurationResultTypeDef,
     KubernetesConfigurationTypeDef,
+    ProcessDetailsTypeDef,
     MalwareProtectionConfigurationTypeDef,
+    MemberFeaturesConfigurationResultTypeDef,
+    MemberFeaturesConfigurationTypeDef,
     NetworkInterfaceTypeDef,
+    VpcConfigTypeDef,
+    OrganizationFeatureConfigurationResultTypeDef,
+    OrganizationFeatureConfigurationTypeDef,
     OrganizationScanEc2InstanceWithFindingsResultTypeDef,
     OrganizationScanEc2InstanceWithFindingsTypeDef,
     OrganizationKubernetesConfigurationResultTypeDef,
     OrganizationKubernetesConfigurationTypeDef,
     RemoteIpDetailsTypeDef,
     ScanConditionTypeDef,
     ScanThreatNameTypeDef,
     ScanTypeDef,
     UsageAccountResultTypeDef,
     UsageDataSourceResultTypeDef,
+    UsageFeatureResultTypeDef,
     UsageResourceResultTypeDef,
+    CoverageResourceDetailsTypeDef,
     PermissionConfigurationTypeDef,
     CreateFilterRequestRequestTypeDef,
     GetFilterResponseTypeDef,
     GetFindingsStatisticsRequestRequestTypeDef,
     ListFindingsRequestListFindingsPaginateTypeDef,
     ListFindingsRequestRequestTypeDef,
     UpdateFilterRequestRequestTypeDef,
+    CoverageFilterCriteriaTypeDef,
     DataSourcesFreeTrialTypeDef,
     MalwareProtectionConfigurationResultTypeDef,
     FilterCriteriaTypeDef,
     EcsTaskDetailsTypeDef,
     KubernetesWorkloadDetailsTypeDef,
+    RuntimeContextTypeDef,
     DataSourceConfigurationsTypeDef,
     InstanceDetailsTypeDef,
+    LambdaDetailsTypeDef,
     OrganizationMalwareProtectionConfigurationResultTypeDef,
     OrganizationMalwareProtectionConfigurationTypeDef,
     AwsApiCallActionTypeDef,
     KubernetesApiCallActionTypeDef,
     NetworkConnectionActionTypeDef,
     PortProbeDetailTypeDef,
+    RdsLoginAttemptActionTypeDef,
     ScanResourceCriteriaTypeDef,
     ThreatDetectedByNameTypeDef,
     DescribeMalwareScansResponseTypeDef,
     UsageStatisticsTypeDef,
+    CoverageResourceTypeDef,
     PublicAccessTypeDef,
+    GetCoverageStatisticsRequestRequestTypeDef,
+    ListCoverageRequestListCoveragePaginateTypeDef,
+    ListCoverageRequestRequestTypeDef,
     AccountFreeTrialInfoTypeDef,
     DataSourceConfigurationsResultTypeDef,
     UnprocessedDataSourcesResultTypeDef,
     DescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef,
     DescribeMalwareScansRequestRequestTypeDef,
     EcsClusterDetailsTypeDef,
     KubernetesDetailsTypeDef,
+    RuntimeDetailsTypeDef,
     CreateDetectorRequestRequestTypeDef,
     UpdateDetectorRequestRequestTypeDef,
     UpdateMemberDetectorsRequestRequestTypeDef,
     OrganizationDataSourceConfigurationsResultTypeDef,
     OrganizationDataSourceConfigurationsTypeDef,
     PortProbeActionTypeDef,
     GetMalwareScanSettingsResponseTypeDef,
     UpdateMalwareScanSettingsRequestRequestTypeDef,
     ScanDetectionsTypeDef,
     GetUsageStatisticsResponseTypeDef,
+    ListCoverageResponseTypeDef,
     S3BucketDetailTypeDef,
     GetRemainingFreeTrialDaysResponseTypeDef,
     GetDetectorResponseTypeDef,
     MemberDataSourceConfigurationTypeDef,
     CreateDetectorResponseTypeDef,
     DescribeOrganizationConfigurationResponseTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
@@ -593,43 +652,43 @@
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

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/setup.py` & `types-aiobotocore-guardduty-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-guardduty.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-guardduty",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_guardduty"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.GuardDuty 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.GuardDuty 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/"
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

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/__init__.py` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/__init__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_guardduty import (
         Client,
         DescribeMalwareScansPaginator,
         GuardDutyClient,
+        ListCoveragePaginator,
         ListDetectorsPaginator,
         ListFiltersPaginator,
         ListFindingsPaginator,
         ListIPSetsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
@@ -22,27 +23,29 @@
     session = get_session()
     async with session.create_client("guardduty") as client:
         client: GuardDutyClient
         ...
 
 
     describe_malware_scans_paginator: DescribeMalwareScansPaginator = client.get_paginator("describe_malware_scans")
+    list_coverage_paginator: ListCoveragePaginator = client.get_paginator("list_coverage")
     list_detectors_paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
     list_filters_paginator: ListFiltersPaginator = client.get_paginator("list_filters")
     list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
     list_ip_sets_paginator: ListIPSetsPaginator = client.get_paginator("list_ip_sets")
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
     list_threat_intel_sets_paginator: ListThreatIntelSetsPaginator = client.get_paginator("list_threat_intel_sets")
     ```
 """
 from .client import GuardDutyClient
 from .paginator import (
     DescribeMalwareScansPaginator,
+    ListCoveragePaginator,
     ListDetectorsPaginator,
     ListFiltersPaginator,
     ListFindingsPaginator,
     ListInvitationsPaginator,
     ListIPSetsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
@@ -52,14 +55,15 @@
 Client = GuardDutyClient
 
 
 __all__ = (
     "Client",
     "DescribeMalwareScansPaginator",
     "GuardDutyClient",
+    "ListCoveragePaginator",
     "ListDetectorsPaginator",
     "ListFiltersPaginator",
     "ListFindingsPaginator",
     "ListIPSetsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/__init__.pyi` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/__init__.pyi`

 * *Files 15% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 
     ```python
     from aiobotocore.session import get_session
     from types_aiobotocore_guardduty import (
         Client,
         DescribeMalwareScansPaginator,
         GuardDutyClient,
+        ListCoveragePaginator,
         ListDetectorsPaginator,
         ListFiltersPaginator,
         ListFindingsPaginator,
         ListIPSetsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
@@ -22,27 +23,29 @@
     session = get_session()
     async with session.create_client("guardduty") as client:
         client: GuardDutyClient
         ...
 
 
     describe_malware_scans_paginator: DescribeMalwareScansPaginator = client.get_paginator("describe_malware_scans")
+    list_coverage_paginator: ListCoveragePaginator = client.get_paginator("list_coverage")
     list_detectors_paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
     list_filters_paginator: ListFiltersPaginator = client.get_paginator("list_filters")
     list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
     list_ip_sets_paginator: ListIPSetsPaginator = client.get_paginator("list_ip_sets")
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
     list_threat_intel_sets_paginator: ListThreatIntelSetsPaginator = client.get_paginator("list_threat_intel_sets")
     ```
 """
 from .client import GuardDutyClient
 from .paginator import (
     DescribeMalwareScansPaginator,
+    ListCoveragePaginator,
     ListDetectorsPaginator,
     ListFiltersPaginator,
     ListFindingsPaginator,
     ListInvitationsPaginator,
     ListIPSetsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
@@ -51,14 +54,15 @@
 
 Client = GuardDutyClient
 
 __all__ = (
     "Client",
     "DescribeMalwareScansPaginator",
     "GuardDutyClient",
+    "ListCoveragePaginator",
     "ListDetectorsPaginator",
     "ListFiltersPaginator",
     "ListFindingsPaginator",
     "ListIPSetsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/__main__.py` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.GuardDuty 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.GuardDuty 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty\nOther"
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

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/client.py` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -17,80 +17,91 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    AutoEnableMembersType,
+    CoverageStatisticsTypeType,
     EbsSnapshotPreservationType,
     FeedbackType,
     FilterActionType,
     FindingPublishingFrequencyType,
     IpSetFormatType,
     ThreatIntelSetFormatType,
     UsageStatisticTypeType,
 )
 from .paginator import (
     DescribeMalwareScansPaginator,
+    ListCoveragePaginator,
     ListDetectorsPaginator,
     ListFiltersPaginator,
     ListFindingsPaginator,
     ListInvitationsPaginator,
     ListIPSetsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
     ListThreatIntelSetsPaginator,
 )
 from .type_defs import (
     AccountDetailTypeDef,
+    CoverageFilterCriteriaTypeDef,
+    CoverageSortCriteriaTypeDef,
     CreateDetectorResponseTypeDef,
     CreateFilterResponseTypeDef,
     CreateIPSetResponseTypeDef,
     CreateMembersResponseTypeDef,
     CreatePublishingDestinationResponseTypeDef,
     CreateThreatIntelSetResponseTypeDef,
     DataSourceConfigurationsTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DescribeMalwareScansResponseTypeDef,
     DescribeOrganizationConfigurationResponseTypeDef,
     DescribePublishingDestinationResponseTypeDef,
     DestinationPropertiesTypeDef,
+    DetectorFeatureConfigurationTypeDef,
     DisassociateMembersResponseTypeDef,
     FilterCriteriaTypeDef,
     FindingCriteriaTypeDef,
     GetAdministratorAccountResponseTypeDef,
+    GetCoverageStatisticsResponseTypeDef,
     GetDetectorResponseTypeDef,
     GetFilterResponseTypeDef,
     GetFindingsResponseTypeDef,
     GetFindingsStatisticsResponseTypeDef,
     GetInvitationsCountResponseTypeDef,
     GetIPSetResponseTypeDef,
     GetMalwareScanSettingsResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     GetMemberDetectorsResponseTypeDef,
     GetMembersResponseTypeDef,
     GetRemainingFreeTrialDaysResponseTypeDef,
     GetThreatIntelSetResponseTypeDef,
     GetUsageStatisticsResponseTypeDef,
     InviteMembersResponseTypeDef,
+    ListCoverageResponseTypeDef,
     ListDetectorsResponseTypeDef,
     ListFiltersResponseTypeDef,
     ListFindingsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListIPSetsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
     ListPublishingDestinationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListThreatIntelSetsResponseTypeDef,
+    MemberFeaturesConfigurationTypeDef,
     OrganizationDataSourceConfigurationsTypeDef,
+    OrganizationFeatureConfigurationTypeDef,
     ScanResourceCriteriaTypeDef,
     SortCriteriaTypeDef,
+    StartMalwareScanResponseTypeDef,
     StartMonitoringMembersResponseTypeDef,
     StopMonitoringMembersResponseTypeDef,
     UpdateFilterResponseTypeDef,
     UpdateMemberDetectorsResponseTypeDef,
     UsageCriteriaTypeDef,
 )
 
@@ -108,16 +119,18 @@
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 
 class Exceptions:
+    AccessDeniedException: Type[BotocoreClientError]
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     InternalServerErrorException: Type[BotocoreClientError]
 
 
 class GuardDutyClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/)
@@ -184,15 +197,16 @@
     async def create_detector(
         self,
         *,
         Enable: bool,
         ClientToken: str = ...,
         FindingPublishingFrequency: FindingPublishingFrequencyType = ...,
         DataSources: DataSourceConfigurationsTypeDef = ...,
-        Tags: Mapping[str, str] = ...
+        Tags: Mapping[str, str] = ...,
+        Features: Sequence[DetectorFeatureConfigurationTypeDef] = ...
     ) -> CreateDetectorResponseTypeDef:
         """
         Creates a single Amazon GuardDuty detector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.create_detector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#create_detector)
         """
@@ -261,15 +275,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#create_publishing_destination)
         """
 
     async def create_sample_findings(
         self, *, DetectorId: str, FindingTypes: Sequence[str] = ...
     ) -> Dict[str, Any]:
         """
-        Generates example findings of types specified by the list of finding types.
+        Generates sample findings of types specified by the list of finding types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.create_sample_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#create_sample_findings)
         """
 
     async def create_threat_intel_set(
         self,
@@ -346,15 +360,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#delete_members)
         """
 
     async def delete_publishing_destination(
         self, *, DetectorId: str, DestinationId: str
     ) -> Dict[str, Any]:
         """
-        Deletes the publishing definition with the specified `destinationId` .
+        Deletes the publishing definition with the specified `destinationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.delete_publishing_destination)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#delete_publishing_destination)
         """
 
     async def delete_threat_intel_set(
         self, *, DetectorId: str, ThreatIntelSetId: str
@@ -379,30 +393,30 @@
         Returns a list of malware scans.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.describe_malware_scans)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#describe_malware_scans)
         """
 
     async def describe_organization_configuration(
-        self, *, DetectorId: str
+        self, *, DetectorId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> DescribeOrganizationConfigurationResponseTypeDef:
         """
         Returns information about the account selected as the delegated administrator
         for GuardDuty.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.describe_organization_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#describe_organization_configuration)
         """
 
     async def describe_publishing_destination(
         self, *, DetectorId: str, DestinationId: str
     ) -> DescribePublishingDestinationResponseTypeDef:
         """
         Returns information about the publishing destination specified by the provided
-        `destinationId` .
+        `destinationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.describe_publishing_destination)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#describe_publishing_destination)
         """
 
     async def disable_organization_admin_account(self, *, AdminAccountId: str) -> Dict[str, Any]:
         """
@@ -431,15 +445,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#disassociate_from_master_account)
         """
 
     async def disassociate_members(
         self, *, DetectorId: str, AccountIds: Sequence[str]
     ) -> DisassociateMembersResponseTypeDef:
         """
-        Disassociates GuardDuty member accounts (to the current administrator account)
+        Disassociates GuardDuty member accounts (from the current administrator account)
         specified by the account IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.disassociate_members)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#disassociate_members)
         """
 
     async def enable_organization_admin_account(self, *, AdminAccountId: str) -> Dict[str, Any]:
@@ -472,14 +486,28 @@
         Provides the details for the GuardDuty administrator account associated with the
         current GuardDuty member account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_administrator_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_administrator_account)
         """
 
+    async def get_coverage_statistics(
+        self,
+        *,
+        DetectorId: str,
+        StatisticsType: Sequence[CoverageStatisticsTypeType],
+        FilterCriteria: CoverageFilterCriteriaTypeDef = ...
+    ) -> GetCoverageStatisticsResponseTypeDef:
+        """
+        Retrieves aggregated statistics for your account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_coverage_statistics)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_coverage_statistics)
+        """
+
     async def get_detector(self, *, DetectorId: str) -> GetDetectorResponseTypeDef:
         """
         Retrieves an Amazon GuardDuty detector specified by the detectorId.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_detector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_detector)
         """
@@ -523,15 +551,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_invitations_count)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_invitations_count)
         """
 
     async def get_ip_set(self, *, DetectorId: str, IpSetId: str) -> GetIPSetResponseTypeDef:
         """
-        Retrieves the IPSet specified by the `ipSetId` .
+        Retrieves the IPSet specified by the `ipSetId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_ip_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_ip_set)
         """
 
     async def get_malware_scan_settings(
         self, *, DetectorId: str
@@ -617,23 +645,37 @@
         *,
         DetectorId: str,
         AccountIds: Sequence[str],
         DisableEmailNotification: bool = ...,
         Message: str = ...
     ) -> InviteMembersResponseTypeDef:
         """
-        Invites other Amazon Web Services accounts (created as members of the current
-        Amazon Web Services account by CreateMembers) to enable GuardDuty, and allow the
-        current Amazon Web Services account to view and manage these accounts' findings
-        on their behalf as the GuardDuty administrator account.
+        Invites Amazon Web Services accounts to become members of an organization
+        administered by the Amazon Web Services account that invokes this API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.invite_members)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#invite_members)
         """
 
+    async def list_coverage(
+        self,
+        *,
+        DetectorId: str,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        FilterCriteria: CoverageFilterCriteriaTypeDef = ...,
+        SortCriteria: CoverageSortCriteriaTypeDef = ...
+    ) -> ListCoverageResponseTypeDef:
+        """
+        Lists coverage details for your GuardDuty account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_coverage)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#list_coverage)
+        """
+
     async def list_detectors(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListDetectorsResponseTypeDef:
         """
         Lists detectorIds of all the existing Amazon GuardDuty detector resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_detectors)
@@ -714,15 +756,15 @@
         """
 
     async def list_publishing_destinations(
         self, *, DetectorId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListPublishingDestinationsResponseTypeDef:
         """
         Returns a list of publishing destinations associated with the specified
-        `detectorId` .
+        `detectorId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_publishing_destinations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#list_publishing_destinations)
         """
 
     async def list_tags_for_resource(
         self, *, ResourceArn: str
@@ -740,14 +782,22 @@
         """
         Lists the ThreatIntelSets of the GuardDuty service specified by the detector ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_threat_intel_sets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#list_threat_intel_sets)
         """
 
+    async def start_malware_scan(self, *, ResourceArn: str) -> StartMalwareScanResponseTypeDef:
+        """
+        Initiates the malware scan.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.start_malware_scan)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#start_malware_scan)
+        """
+
     async def start_monitoring_members(
         self, *, DetectorId: str, AccountIds: Sequence[str]
     ) -> StartMonitoringMembersResponseTypeDef:
         """
         Turns on GuardDuty monitoring of the specified member accounts.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.start_monitoring_members)
@@ -772,15 +822,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#tag_resource)
         """
 
     async def unarchive_findings(
         self, *, DetectorId: str, FindingIds: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Unarchives GuardDuty findings specified by the `findingIds` .
+        Unarchives GuardDuty findings specified by the `findingIds`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.unarchive_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#unarchive_findings)
         """
 
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
@@ -792,15 +842,16 @@
 
     async def update_detector(
         self,
         *,
         DetectorId: str,
         Enable: bool = ...,
         FindingPublishingFrequency: FindingPublishingFrequencyType = ...,
-        DataSources: DataSourceConfigurationsTypeDef = ...
+        DataSources: DataSourceConfigurationsTypeDef = ...,
+        Features: Sequence[DetectorFeatureConfigurationTypeDef] = ...
     ) -> Dict[str, Any]:
         """
         Updates the Amazon GuardDuty detector specified by the detectorId.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_detector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_detector)
         """
@@ -868,47 +919,50 @@
         """
 
     async def update_member_detectors(
         self,
         *,
         DetectorId: str,
         AccountIds: Sequence[str],
-        DataSources: DataSourceConfigurationsTypeDef = ...
+        DataSources: DataSourceConfigurationsTypeDef = ...,
+        Features: Sequence[MemberFeaturesConfigurationTypeDef] = ...
     ) -> UpdateMemberDetectorsResponseTypeDef:
         """
         Contains information on member accounts to be updated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_member_detectors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_member_detectors)
         """
 
     async def update_organization_configuration(
         self,
         *,
         DetectorId: str,
-        AutoEnable: bool,
-        DataSources: OrganizationDataSourceConfigurationsTypeDef = ...
+        AutoEnable: bool = ...,
+        DataSources: OrganizationDataSourceConfigurationsTypeDef = ...,
+        Features: Sequence[OrganizationFeatureConfigurationTypeDef] = ...,
+        AutoEnableOrganizationMembers: AutoEnableMembersType = ...
     ) -> Dict[str, Any]:
         """
-        Updates the delegated administrator account with the values provided.
+        Configures the delegated administrator account with the provided values.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_organization_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_organization_configuration)
         """
 
     async def update_publishing_destination(
         self,
         *,
         DetectorId: str,
         DestinationId: str,
         DestinationProperties: DestinationPropertiesTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Updates information about the publishing destination specified by the
-        `destinationId` .
+        `destinationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_publishing_destination)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_publishing_destination)
         """
 
     async def update_threat_intel_set(
         self,
@@ -932,14 +986,21 @@
     ) -> DescribeMalwareScansPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(self, operation_name: Literal["list_coverage"]) -> ListCoveragePaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_detectors"]) -> ListDetectorsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_paginator)
         """
 
     @overload
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/client.pyi` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -17,80 +17,91 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    AutoEnableMembersType,
+    CoverageStatisticsTypeType,
     EbsSnapshotPreservationType,
     FeedbackType,
     FilterActionType,
     FindingPublishingFrequencyType,
     IpSetFormatType,
     ThreatIntelSetFormatType,
     UsageStatisticTypeType,
 )
 from .paginator import (
     DescribeMalwareScansPaginator,
+    ListCoveragePaginator,
     ListDetectorsPaginator,
     ListFiltersPaginator,
     ListFindingsPaginator,
     ListInvitationsPaginator,
     ListIPSetsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
     ListThreatIntelSetsPaginator,
 )
 from .type_defs import (
     AccountDetailTypeDef,
+    CoverageFilterCriteriaTypeDef,
+    CoverageSortCriteriaTypeDef,
     CreateDetectorResponseTypeDef,
     CreateFilterResponseTypeDef,
     CreateIPSetResponseTypeDef,
     CreateMembersResponseTypeDef,
     CreatePublishingDestinationResponseTypeDef,
     CreateThreatIntelSetResponseTypeDef,
     DataSourceConfigurationsTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DescribeMalwareScansResponseTypeDef,
     DescribeOrganizationConfigurationResponseTypeDef,
     DescribePublishingDestinationResponseTypeDef,
     DestinationPropertiesTypeDef,
+    DetectorFeatureConfigurationTypeDef,
     DisassociateMembersResponseTypeDef,
     FilterCriteriaTypeDef,
     FindingCriteriaTypeDef,
     GetAdministratorAccountResponseTypeDef,
+    GetCoverageStatisticsResponseTypeDef,
     GetDetectorResponseTypeDef,
     GetFilterResponseTypeDef,
     GetFindingsResponseTypeDef,
     GetFindingsStatisticsResponseTypeDef,
     GetInvitationsCountResponseTypeDef,
     GetIPSetResponseTypeDef,
     GetMalwareScanSettingsResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     GetMemberDetectorsResponseTypeDef,
     GetMembersResponseTypeDef,
     GetRemainingFreeTrialDaysResponseTypeDef,
     GetThreatIntelSetResponseTypeDef,
     GetUsageStatisticsResponseTypeDef,
     InviteMembersResponseTypeDef,
+    ListCoverageResponseTypeDef,
     ListDetectorsResponseTypeDef,
     ListFiltersResponseTypeDef,
     ListFindingsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListIPSetsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
     ListPublishingDestinationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListThreatIntelSetsResponseTypeDef,
+    MemberFeaturesConfigurationTypeDef,
     OrganizationDataSourceConfigurationsTypeDef,
+    OrganizationFeatureConfigurationTypeDef,
     ScanResourceCriteriaTypeDef,
     SortCriteriaTypeDef,
+    StartMalwareScanResponseTypeDef,
     StartMonitoringMembersResponseTypeDef,
     StopMonitoringMembersResponseTypeDef,
     UpdateFilterResponseTypeDef,
     UpdateMemberDetectorsResponseTypeDef,
     UsageCriteriaTypeDef,
 )
 
@@ -105,16 +116,18 @@
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
 class Exceptions:
+    AccessDeniedException: Type[BotocoreClientError]
     BadRequestException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
+    ConflictException: Type[BotocoreClientError]
     InternalServerErrorException: Type[BotocoreClientError]
 
 class GuardDutyClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/)
     """
@@ -174,15 +187,16 @@
     async def create_detector(
         self,
         *,
         Enable: bool,
         ClientToken: str = ...,
         FindingPublishingFrequency: FindingPublishingFrequencyType = ...,
         DataSources: DataSourceConfigurationsTypeDef = ...,
-        Tags: Mapping[str, str] = ...
+        Tags: Mapping[str, str] = ...,
+        Features: Sequence[DetectorFeatureConfigurationTypeDef] = ...
     ) -> CreateDetectorResponseTypeDef:
         """
         Creates a single Amazon GuardDuty detector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.create_detector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#create_detector)
         """
@@ -246,15 +260,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.create_publishing_destination)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#create_publishing_destination)
         """
     async def create_sample_findings(
         self, *, DetectorId: str, FindingTypes: Sequence[str] = ...
     ) -> Dict[str, Any]:
         """
-        Generates example findings of types specified by the list of finding types.
+        Generates sample findings of types specified by the list of finding types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.create_sample_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#create_sample_findings)
         """
     async def create_threat_intel_set(
         self,
         *,
@@ -323,15 +337,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.delete_members)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#delete_members)
         """
     async def delete_publishing_destination(
         self, *, DetectorId: str, DestinationId: str
     ) -> Dict[str, Any]:
         """
-        Deletes the publishing definition with the specified `destinationId` .
+        Deletes the publishing definition with the specified `destinationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.delete_publishing_destination)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#delete_publishing_destination)
         """
     async def delete_threat_intel_set(
         self, *, DetectorId: str, ThreatIntelSetId: str
     ) -> Dict[str, Any]:
@@ -353,29 +367,29 @@
         """
         Returns a list of malware scans.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.describe_malware_scans)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#describe_malware_scans)
         """
     async def describe_organization_configuration(
-        self, *, DetectorId: str
+        self, *, DetectorId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> DescribeOrganizationConfigurationResponseTypeDef:
         """
         Returns information about the account selected as the delegated administrator
         for GuardDuty.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.describe_organization_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#describe_organization_configuration)
         """
     async def describe_publishing_destination(
         self, *, DetectorId: str, DestinationId: str
     ) -> DescribePublishingDestinationResponseTypeDef:
         """
         Returns information about the publishing destination specified by the provided
-        `destinationId` .
+        `destinationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.describe_publishing_destination)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#describe_publishing_destination)
         """
     async def disable_organization_admin_account(self, *, AdminAccountId: str) -> Dict[str, Any]:
         """
         Disables an Amazon Web Services account within the Organization as the GuardDuty
@@ -400,15 +414,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.disassociate_from_master_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#disassociate_from_master_account)
         """
     async def disassociate_members(
         self, *, DetectorId: str, AccountIds: Sequence[str]
     ) -> DisassociateMembersResponseTypeDef:
         """
-        Disassociates GuardDuty member accounts (to the current administrator account)
+        Disassociates GuardDuty member accounts (from the current administrator account)
         specified by the account IDs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.disassociate_members)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#disassociate_members)
         """
     async def enable_organization_admin_account(self, *, AdminAccountId: str) -> Dict[str, Any]:
         """
@@ -437,14 +451,27 @@
         """
         Provides the details for the GuardDuty administrator account associated with the
         current GuardDuty member account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_administrator_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_administrator_account)
         """
+    async def get_coverage_statistics(
+        self,
+        *,
+        DetectorId: str,
+        StatisticsType: Sequence[CoverageStatisticsTypeType],
+        FilterCriteria: CoverageFilterCriteriaTypeDef = ...
+    ) -> GetCoverageStatisticsResponseTypeDef:
+        """
+        Retrieves aggregated statistics for your account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_coverage_statistics)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_coverage_statistics)
+        """
     async def get_detector(self, *, DetectorId: str) -> GetDetectorResponseTypeDef:
         """
         Retrieves an Amazon GuardDuty detector specified by the detectorId.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_detector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_detector)
         """
@@ -483,15 +510,15 @@
         current member account except the currently accepted invitation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_invitations_count)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_invitations_count)
         """
     async def get_ip_set(self, *, DetectorId: str, IpSetId: str) -> GetIPSetResponseTypeDef:
         """
-        Retrieves the IPSet specified by the `ipSetId` .
+        Retrieves the IPSet specified by the `ipSetId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_ip_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_ip_set)
         """
     async def get_malware_scan_settings(
         self, *, DetectorId: str
     ) -> GetMalwareScanSettingsResponseTypeDef:
@@ -569,22 +596,35 @@
         *,
         DetectorId: str,
         AccountIds: Sequence[str],
         DisableEmailNotification: bool = ...,
         Message: str = ...
     ) -> InviteMembersResponseTypeDef:
         """
-        Invites other Amazon Web Services accounts (created as members of the current
-        Amazon Web Services account by CreateMembers) to enable GuardDuty, and allow the
-        current Amazon Web Services account to view and manage these accounts' findings
-        on their behalf as the GuardDuty administrator account.
+        Invites Amazon Web Services accounts to become members of an organization
+        administered by the Amazon Web Services account that invokes this API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.invite_members)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#invite_members)
         """
+    async def list_coverage(
+        self,
+        *,
+        DetectorId: str,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        FilterCriteria: CoverageFilterCriteriaTypeDef = ...,
+        SortCriteria: CoverageSortCriteriaTypeDef = ...
+    ) -> ListCoverageResponseTypeDef:
+        """
+        Lists coverage details for your GuardDuty account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_coverage)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#list_coverage)
+        """
     async def list_detectors(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListDetectorsResponseTypeDef:
         """
         Lists detectorIds of all the existing Amazon GuardDuty detector resources.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_detectors)
@@ -658,15 +698,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#list_organization_admin_accounts)
         """
     async def list_publishing_destinations(
         self, *, DetectorId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListPublishingDestinationsResponseTypeDef:
         """
         Returns a list of publishing destinations associated with the specified
-        `detectorId` .
+        `detectorId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_publishing_destinations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#list_publishing_destinations)
         """
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
@@ -681,14 +721,21 @@
     ) -> ListThreatIntelSetsResponseTypeDef:
         """
         Lists the ThreatIntelSets of the GuardDuty service specified by the detector ID.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.list_threat_intel_sets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#list_threat_intel_sets)
         """
+    async def start_malware_scan(self, *, ResourceArn: str) -> StartMalwareScanResponseTypeDef:
+        """
+        Initiates the malware scan.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.start_malware_scan)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#start_malware_scan)
+        """
     async def start_monitoring_members(
         self, *, DetectorId: str, AccountIds: Sequence[str]
     ) -> StartMonitoringMembersResponseTypeDef:
         """
         Turns on GuardDuty monitoring of the specified member accounts.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.start_monitoring_members)
@@ -710,15 +757,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#tag_resource)
         """
     async def unarchive_findings(
         self, *, DetectorId: str, FindingIds: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Unarchives GuardDuty findings specified by the `findingIds` .
+        Unarchives GuardDuty findings specified by the `findingIds`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.unarchive_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#unarchive_findings)
         """
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes tags from a resource.
@@ -728,15 +775,16 @@
         """
     async def update_detector(
         self,
         *,
         DetectorId: str,
         Enable: bool = ...,
         FindingPublishingFrequency: FindingPublishingFrequencyType = ...,
-        DataSources: DataSourceConfigurationsTypeDef = ...
+        DataSources: DataSourceConfigurationsTypeDef = ...,
+        Features: Sequence[DetectorFeatureConfigurationTypeDef] = ...
     ) -> Dict[str, Any]:
         """
         Updates the Amazon GuardDuty detector specified by the detectorId.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_detector)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_detector)
         """
@@ -799,45 +847,48 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_malware_scan_settings)
         """
     async def update_member_detectors(
         self,
         *,
         DetectorId: str,
         AccountIds: Sequence[str],
-        DataSources: DataSourceConfigurationsTypeDef = ...
+        DataSources: DataSourceConfigurationsTypeDef = ...,
+        Features: Sequence[MemberFeaturesConfigurationTypeDef] = ...
     ) -> UpdateMemberDetectorsResponseTypeDef:
         """
         Contains information on member accounts to be updated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_member_detectors)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_member_detectors)
         """
     async def update_organization_configuration(
         self,
         *,
         DetectorId: str,
-        AutoEnable: bool,
-        DataSources: OrganizationDataSourceConfigurationsTypeDef = ...
+        AutoEnable: bool = ...,
+        DataSources: OrganizationDataSourceConfigurationsTypeDef = ...,
+        Features: Sequence[OrganizationFeatureConfigurationTypeDef] = ...,
+        AutoEnableOrganizationMembers: AutoEnableMembersType = ...
     ) -> Dict[str, Any]:
         """
-        Updates the delegated administrator account with the values provided.
+        Configures the delegated administrator account with the provided values.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_organization_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_organization_configuration)
         """
     async def update_publishing_destination(
         self,
         *,
         DetectorId: str,
         DestinationId: str,
         DestinationProperties: DestinationPropertiesTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Updates information about the publishing destination specified by the
-        `destinationId` .
+        `destinationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.update_publishing_destination)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#update_publishing_destination)
         """
     async def update_threat_intel_set(
         self,
         *,
@@ -858,14 +909,20 @@
         self, operation_name: Literal["describe_malware_scans"]
     ) -> DescribeMalwareScansPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_paginator)
         """
     @overload
+    def get_paginator(self, operation_name: Literal["list_coverage"]) -> ListCoveragePaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_detectors"]) -> ListDetectorsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/client/#get_paginator)
         """
     @overload
     def get_paginator(self, operation_name: Literal["list_filters"]) -> ListFiltersPaginator:
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/literals.py` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/literals.py`

 * *Files 15% similar despite different names*

```diff
@@ -17,99 +17,182 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AdminStatusType",
+    "AutoEnableMembersType",
+    "CoverageFilterCriterionKeyType",
+    "CoverageSortKeyType",
+    "CoverageStatisticsTypeType",
+    "CoverageStatusType",
     "CriterionKeyType",
     "DataSourceStatusType",
     "DataSourceType",
     "DescribeMalwareScansPaginatorName",
     "DestinationTypeType",
+    "DetectorFeatureResultType",
+    "DetectorFeatureType",
     "DetectorStatusType",
     "EbsSnapshotPreservationType",
+    "FeatureAdditionalConfigurationType",
+    "FeatureStatusType",
     "FeedbackType",
     "FilterActionType",
     "FindingPublishingFrequencyType",
     "FindingStatisticTypeType",
+    "FreeTrialFeatureResultType",
     "IpSetFormatType",
     "IpSetStatusType",
+    "ListCoveragePaginatorName",
     "ListDetectorsPaginatorName",
     "ListFiltersPaginatorName",
     "ListFindingsPaginatorName",
     "ListIPSetsPaginatorName",
     "ListInvitationsPaginatorName",
     "ListMembersPaginatorName",
     "ListOrganizationAdminAccountsPaginatorName",
     "ListThreatIntelSetsPaginatorName",
     "OrderByType",
+    "OrgFeatureAdditionalConfigurationType",
+    "OrgFeatureStatusType",
+    "OrgFeatureType",
     "PublishingStatusType",
+    "ResourceTypeType",
     "ScanCriterionKeyType",
     "ScanResultType",
     "ScanStatusType",
+    "ScanTypeType",
     "ThreatIntelSetFormatType",
     "ThreatIntelSetStatusType",
+    "UsageFeatureType",
     "UsageStatisticTypeType",
     "GuardDutyServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 AdminStatusType = Literal["DISABLE_IN_PROGRESS", "ENABLED"]
+AutoEnableMembersType = Literal["ALL", "NEW", "NONE"]
+CoverageFilterCriterionKeyType = Literal[
+    "ACCOUNT_ID", "ADDON_VERSION", "CLUSTER_NAME", "COVERAGE_STATUS", "RESOURCE_TYPE"
+]
+CoverageSortKeyType = Literal[
+    "ACCOUNT_ID", "ADDON_VERSION", "CLUSTER_NAME", "COVERAGE_STATUS", "ISSUE", "UPDATED_AT"
+]
+CoverageStatisticsTypeType = Literal["COUNT_BY_COVERAGE_STATUS", "COUNT_BY_RESOURCE_TYPE"]
+CoverageStatusType = Literal["HEALTHY", "UNHEALTHY"]
 CriterionKeyType = Literal[
     "ACCOUNT_ID",
     "EC2_INSTANCE_ARN",
     "GUARDDUTY_FINDING_ID",
     "SCAN_ID",
     "SCAN_START_TIME",
     "SCAN_STATUS",
+    "SCAN_TYPE",
 ]
 DataSourceStatusType = Literal["DISABLED", "ENABLED"]
 DataSourceType = Literal[
     "CLOUD_TRAIL", "DNS_LOGS", "EC2_MALWARE_SCAN", "FLOW_LOGS", "KUBERNETES_AUDIT_LOGS", "S3_LOGS"
 ]
 DescribeMalwareScansPaginatorName = Literal["describe_malware_scans"]
 DestinationTypeType = Literal["S3"]
+DetectorFeatureResultType = Literal[
+    "CLOUD_TRAIL",
+    "DNS_LOGS",
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "FLOW_LOGS",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
+DetectorFeatureType = Literal[
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 DetectorStatusType = Literal["DISABLED", "ENABLED"]
 EbsSnapshotPreservationType = Literal["NO_RETENTION", "RETENTION_WITH_FINDING"]
+FeatureAdditionalConfigurationType = Literal["EKS_ADDON_MANAGEMENT"]
+FeatureStatusType = Literal["DISABLED", "ENABLED"]
 FeedbackType = Literal["NOT_USEFUL", "USEFUL"]
 FilterActionType = Literal["ARCHIVE", "NOOP"]
 FindingPublishingFrequencyType = Literal["FIFTEEN_MINUTES", "ONE_HOUR", "SIX_HOURS"]
 FindingStatisticTypeType = Literal["COUNT_BY_SEVERITY"]
+FreeTrialFeatureResultType = Literal[
+    "CLOUD_TRAIL",
+    "DNS_LOGS",
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "FLOW_LOGS",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 IpSetFormatType = Literal["ALIEN_VAULT", "FIRE_EYE", "OTX_CSV", "PROOF_POINT", "STIX", "TXT"]
 IpSetStatusType = Literal[
     "ACTIVATING", "ACTIVE", "DEACTIVATING", "DELETED", "DELETE_PENDING", "ERROR", "INACTIVE"
 ]
+ListCoveragePaginatorName = Literal["list_coverage"]
 ListDetectorsPaginatorName = Literal["list_detectors"]
 ListFiltersPaginatorName = Literal["list_filters"]
 ListFindingsPaginatorName = Literal["list_findings"]
 ListIPSetsPaginatorName = Literal["list_ip_sets"]
 ListInvitationsPaginatorName = Literal["list_invitations"]
 ListMembersPaginatorName = Literal["list_members"]
 ListOrganizationAdminAccountsPaginatorName = Literal["list_organization_admin_accounts"]
 ListThreatIntelSetsPaginatorName = Literal["list_threat_intel_sets"]
 OrderByType = Literal["ASC", "DESC"]
+OrgFeatureAdditionalConfigurationType = Literal["EKS_ADDON_MANAGEMENT"]
+OrgFeatureStatusType = Literal["NEW", "NONE"]
+OrgFeatureType = Literal[
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 PublishingStatusType = Literal[
     "PENDING_VERIFICATION", "PUBLISHING", "STOPPED", "UNABLE_TO_PUBLISH_FIX_DESTINATION_PROPERTY"
 ]
+ResourceTypeType = Literal["EKS"]
 ScanCriterionKeyType = Literal["EC2_INSTANCE_TAG"]
 ScanResultType = Literal["CLEAN", "INFECTED"]
-ScanStatusType = Literal["COMPLETED", "FAILED", "RUNNING"]
+ScanStatusType = Literal["COMPLETED", "FAILED", "RUNNING", "SKIPPED"]
+ScanTypeType = Literal["GUARDDUTY_INITIATED", "ON_DEMAND"]
 ThreatIntelSetFormatType = Literal[
     "ALIEN_VAULT", "FIRE_EYE", "OTX_CSV", "PROOF_POINT", "STIX", "TXT"
 ]
 ThreatIntelSetStatusType = Literal[
     "ACTIVATING", "ACTIVE", "DEACTIVATING", "DELETED", "DELETE_PENDING", "ERROR", "INACTIVE"
 ]
+UsageFeatureType = Literal[
+    "CLOUD_TRAIL",
+    "DNS_LOGS",
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "FLOW_LOGS",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 UsageStatisticTypeType = Literal[
-    "SUM_BY_ACCOUNT", "SUM_BY_DATA_SOURCE", "SUM_BY_RESOURCE", "TOP_RESOURCES"
+    "SUM_BY_ACCOUNT", "SUM_BY_DATA_SOURCE", "SUM_BY_FEATURES", "SUM_BY_RESOURCE", "TOP_RESOURCES"
 ]
 GuardDutyServiceName = Literal["guardduty"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -166,14 +249,15 @@
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
@@ -252,14 +336,15 @@
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
@@ -270,14 +355,15 @@
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
@@ -313,14 +399,15 @@
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
@@ -339,16 +426,19 @@
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
@@ -432,15 +522,17 @@
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
@@ -460,14 +552,15 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "describe_malware_scans",
+    "list_coverage",
     "list_detectors",
     "list_filters",
     "list_findings",
     "list_invitations",
     "list_ip_sets",
     "list_members",
     "list_organization_admin_accounts",
@@ -480,14 +573,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/literals.pyi` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/literals.pyi`

 * *Files 15% similar despite different names*

```diff
@@ -16,98 +16,181 @@
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AdminStatusType",
+    "AutoEnableMembersType",
+    "CoverageFilterCriterionKeyType",
+    "CoverageSortKeyType",
+    "CoverageStatisticsTypeType",
+    "CoverageStatusType",
     "CriterionKeyType",
     "DataSourceStatusType",
     "DataSourceType",
     "DescribeMalwareScansPaginatorName",
     "DestinationTypeType",
+    "DetectorFeatureResultType",
+    "DetectorFeatureType",
     "DetectorStatusType",
     "EbsSnapshotPreservationType",
+    "FeatureAdditionalConfigurationType",
+    "FeatureStatusType",
     "FeedbackType",
     "FilterActionType",
     "FindingPublishingFrequencyType",
     "FindingStatisticTypeType",
+    "FreeTrialFeatureResultType",
     "IpSetFormatType",
     "IpSetStatusType",
+    "ListCoveragePaginatorName",
     "ListDetectorsPaginatorName",
     "ListFiltersPaginatorName",
     "ListFindingsPaginatorName",
     "ListIPSetsPaginatorName",
     "ListInvitationsPaginatorName",
     "ListMembersPaginatorName",
     "ListOrganizationAdminAccountsPaginatorName",
     "ListThreatIntelSetsPaginatorName",
     "OrderByType",
+    "OrgFeatureAdditionalConfigurationType",
+    "OrgFeatureStatusType",
+    "OrgFeatureType",
     "PublishingStatusType",
+    "ResourceTypeType",
     "ScanCriterionKeyType",
     "ScanResultType",
     "ScanStatusType",
+    "ScanTypeType",
     "ThreatIntelSetFormatType",
     "ThreatIntelSetStatusType",
+    "UsageFeatureType",
     "UsageStatisticTypeType",
     "GuardDutyServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 AdminStatusType = Literal["DISABLE_IN_PROGRESS", "ENABLED"]
+AutoEnableMembersType = Literal["ALL", "NEW", "NONE"]
+CoverageFilterCriterionKeyType = Literal[
+    "ACCOUNT_ID", "ADDON_VERSION", "CLUSTER_NAME", "COVERAGE_STATUS", "RESOURCE_TYPE"
+]
+CoverageSortKeyType = Literal[
+    "ACCOUNT_ID", "ADDON_VERSION", "CLUSTER_NAME", "COVERAGE_STATUS", "ISSUE", "UPDATED_AT"
+]
+CoverageStatisticsTypeType = Literal["COUNT_BY_COVERAGE_STATUS", "COUNT_BY_RESOURCE_TYPE"]
+CoverageStatusType = Literal["HEALTHY", "UNHEALTHY"]
 CriterionKeyType = Literal[
     "ACCOUNT_ID",
     "EC2_INSTANCE_ARN",
     "GUARDDUTY_FINDING_ID",
     "SCAN_ID",
     "SCAN_START_TIME",
     "SCAN_STATUS",
+    "SCAN_TYPE",
 ]
 DataSourceStatusType = Literal["DISABLED", "ENABLED"]
 DataSourceType = Literal[
     "CLOUD_TRAIL", "DNS_LOGS", "EC2_MALWARE_SCAN", "FLOW_LOGS", "KUBERNETES_AUDIT_LOGS", "S3_LOGS"
 ]
 DescribeMalwareScansPaginatorName = Literal["describe_malware_scans"]
 DestinationTypeType = Literal["S3"]
+DetectorFeatureResultType = Literal[
+    "CLOUD_TRAIL",
+    "DNS_LOGS",
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "FLOW_LOGS",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
+DetectorFeatureType = Literal[
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 DetectorStatusType = Literal["DISABLED", "ENABLED"]
 EbsSnapshotPreservationType = Literal["NO_RETENTION", "RETENTION_WITH_FINDING"]
+FeatureAdditionalConfigurationType = Literal["EKS_ADDON_MANAGEMENT"]
+FeatureStatusType = Literal["DISABLED", "ENABLED"]
 FeedbackType = Literal["NOT_USEFUL", "USEFUL"]
 FilterActionType = Literal["ARCHIVE", "NOOP"]
 FindingPublishingFrequencyType = Literal["FIFTEEN_MINUTES", "ONE_HOUR", "SIX_HOURS"]
 FindingStatisticTypeType = Literal["COUNT_BY_SEVERITY"]
+FreeTrialFeatureResultType = Literal[
+    "CLOUD_TRAIL",
+    "DNS_LOGS",
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "FLOW_LOGS",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 IpSetFormatType = Literal["ALIEN_VAULT", "FIRE_EYE", "OTX_CSV", "PROOF_POINT", "STIX", "TXT"]
 IpSetStatusType = Literal[
     "ACTIVATING", "ACTIVE", "DEACTIVATING", "DELETED", "DELETE_PENDING", "ERROR", "INACTIVE"
 ]
+ListCoveragePaginatorName = Literal["list_coverage"]
 ListDetectorsPaginatorName = Literal["list_detectors"]
 ListFiltersPaginatorName = Literal["list_filters"]
 ListFindingsPaginatorName = Literal["list_findings"]
 ListIPSetsPaginatorName = Literal["list_ip_sets"]
 ListInvitationsPaginatorName = Literal["list_invitations"]
 ListMembersPaginatorName = Literal["list_members"]
 ListOrganizationAdminAccountsPaginatorName = Literal["list_organization_admin_accounts"]
 ListThreatIntelSetsPaginatorName = Literal["list_threat_intel_sets"]
 OrderByType = Literal["ASC", "DESC"]
+OrgFeatureAdditionalConfigurationType = Literal["EKS_ADDON_MANAGEMENT"]
+OrgFeatureStatusType = Literal["NEW", "NONE"]
+OrgFeatureType = Literal[
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 PublishingStatusType = Literal[
     "PENDING_VERIFICATION", "PUBLISHING", "STOPPED", "UNABLE_TO_PUBLISH_FIX_DESTINATION_PROPERTY"
 ]
+ResourceTypeType = Literal["EKS"]
 ScanCriterionKeyType = Literal["EC2_INSTANCE_TAG"]
 ScanResultType = Literal["CLEAN", "INFECTED"]
-ScanStatusType = Literal["COMPLETED", "FAILED", "RUNNING"]
+ScanStatusType = Literal["COMPLETED", "FAILED", "RUNNING", "SKIPPED"]
+ScanTypeType = Literal["GUARDDUTY_INITIATED", "ON_DEMAND"]
 ThreatIntelSetFormatType = Literal[
     "ALIEN_VAULT", "FIRE_EYE", "OTX_CSV", "PROOF_POINT", "STIX", "TXT"
 ]
 ThreatIntelSetStatusType = Literal[
     "ACTIVATING", "ACTIVE", "DEACTIVATING", "DELETED", "DELETE_PENDING", "ERROR", "INACTIVE"
 ]
+UsageFeatureType = Literal[
+    "CLOUD_TRAIL",
+    "DNS_LOGS",
+    "EBS_MALWARE_PROTECTION",
+    "EKS_AUDIT_LOGS",
+    "EKS_RUNTIME_MONITORING",
+    "FLOW_LOGS",
+    "LAMBDA_NETWORK_LOGS",
+    "RDS_LOGIN_EVENTS",
+    "S3_DATA_EVENTS",
+]
 UsageStatisticTypeType = Literal[
-    "SUM_BY_ACCOUNT", "SUM_BY_DATA_SOURCE", "SUM_BY_RESOURCE", "TOP_RESOURCES"
+    "SUM_BY_ACCOUNT", "SUM_BY_DATA_SOURCE", "SUM_BY_FEATURES", "SUM_BY_RESOURCE", "TOP_RESOURCES"
 ]
 GuardDutyServiceName = Literal["guardduty"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -164,14 +247,15 @@
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
@@ -250,14 +334,15 @@
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
@@ -268,14 +353,15 @@
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
@@ -311,14 +397,15 @@
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
@@ -337,16 +424,19 @@
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
@@ -430,15 +520,17 @@
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
@@ -458,14 +550,15 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
     "describe_malware_scans",
+    "list_coverage",
     "list_detectors",
     "list_filters",
     "list_findings",
     "list_invitations",
     "list_ip_sets",
     "list_members",
     "list_organization_admin_accounts",
@@ -478,14 +571,15 @@
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
     "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
     "eu-central-2",
     "eu-north-1",
     "eu-south-1",
     "eu-south-2",
     "eu-west-1",
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/paginator.py` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_guardduty.client import GuardDutyClient
     from types_aiobotocore_guardduty.paginator import (
         DescribeMalwareScansPaginator,
+        ListCoveragePaginator,
         ListDetectorsPaginator,
         ListFiltersPaginator,
         ListFindingsPaginator,
         ListIPSetsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
@@ -22,54 +23,52 @@
     )
 
     session = get_session()
     with session.create_client("guardduty") as client:
         client: GuardDutyClient
 
         describe_malware_scans_paginator: DescribeMalwareScansPaginator = client.get_paginator("describe_malware_scans")
+        list_coverage_paginator: ListCoveragePaginator = client.get_paginator("list_coverage")
         list_detectors_paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
         list_filters_paginator: ListFiltersPaginator = client.get_paginator("list_filters")
         list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
         list_ip_sets_paginator: ListIPSetsPaginator = client.get_paginator("list_ip_sets")
         list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
         list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
         list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
         list_threat_intel_sets_paginator: ListThreatIntelSetsPaginator = client.get_paginator("list_threat_intel_sets")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
+    CoverageFilterCriteriaTypeDef,
+    CoverageSortCriteriaTypeDef,
     DescribeMalwareScansResponseTypeDef,
     FilterCriteriaTypeDef,
     FindingCriteriaTypeDef,
+    ListCoverageResponseTypeDef,
     ListDetectorsResponseTypeDef,
     ListFiltersResponseTypeDef,
     ListFindingsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListIPSetsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
     ListThreatIntelSetsResponseTypeDef,
     PaginatorConfigTypeDef,
     SortCriteriaTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeMalwareScansPaginator",
+    "ListCoveragePaginator",
     "ListDetectorsPaginator",
     "ListFiltersPaginator",
     "ListFindingsPaginator",
     "ListIPSetsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
@@ -95,45 +94,65 @@
 
     def paginate(
         self,
         *,
         DetectorId: str,
         FilterCriteria: FilterCriteriaTypeDef = ...,
         SortCriteria: SortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMalwareScansResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.DescribeMalwareScans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#describemalwarescanspaginator)
         """
 
 
+class ListCoveragePaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListCoverage)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listcoveragepaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        DetectorId: str,
+        FilterCriteria: CoverageFilterCriteriaTypeDef = ...,
+        SortCriteria: CoverageSortCriteriaTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListCoverageResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListCoverage.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listcoveragepaginator)
+        """
+
+
 class ListDetectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListDetectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listdetectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDetectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListDetectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listdetectorspaginator)
         """
 
 
 class ListFiltersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListFilters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listfilterspaginator)
     """
 
     def paginate(
-        self, *, DetectorId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DetectorId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFiltersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListFilters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listfilterspaginator)
         """
 
 
@@ -145,45 +164,45 @@
 
     def paginate(
         self,
         *,
         DetectorId: str,
         FindingCriteria: FindingCriteriaTypeDef = ...,
         SortCriteria: SortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listfindingspaginator)
         """
 
 
 class ListIPSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListIPSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listipsetspaginator)
     """
 
     def paginate(
-        self, *, DetectorId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DetectorId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIPSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListIPSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listipsetspaginator)
         """
 
 
 class ListInvitationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListInvitations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listinvitationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listinvitationspaginator)
         """
 
 
@@ -194,43 +213,43 @@
     """
 
     def paginate(
         self,
         *,
         DetectorId: str,
         OnlyAssociated: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listmemberspaginator)
         """
 
 
 class ListOrganizationAdminAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListOrganizationAdminAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listorganizationadminaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationAdminAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListOrganizationAdminAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listorganizationadminaccountspaginator)
         """
 
 
 class ListThreatIntelSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListThreatIntelSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listthreatintelsetspaginator)
     """
 
     def paginate(
-        self, *, DetectorId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DetectorId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThreatIntelSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListThreatIntelSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listthreatintelsetspaginator)
         """
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/paginator.pyi` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/paginator.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_guardduty.client import GuardDutyClient
     from types_aiobotocore_guardduty.paginator import (
         DescribeMalwareScansPaginator,
+        ListCoveragePaginator,
         ListDetectorsPaginator,
         ListFiltersPaginator,
         ListFindingsPaginator,
         ListIPSetsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
@@ -22,53 +23,52 @@
     )
 
     session = get_session()
     with session.create_client("guardduty") as client:
         client: GuardDutyClient
 
         describe_malware_scans_paginator: DescribeMalwareScansPaginator = client.get_paginator("describe_malware_scans")
+        list_coverage_paginator: ListCoveragePaginator = client.get_paginator("list_coverage")
         list_detectors_paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
         list_filters_paginator: ListFiltersPaginator = client.get_paginator("list_filters")
         list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
         list_ip_sets_paginator: ListIPSetsPaginator = client.get_paginator("list_ip_sets")
         list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
         list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
         list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
         list_threat_intel_sets_paginator: ListThreatIntelSetsPaginator = client.get_paginator("list_threat_intel_sets")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
+    CoverageFilterCriteriaTypeDef,
+    CoverageSortCriteriaTypeDef,
     DescribeMalwareScansResponseTypeDef,
     FilterCriteriaTypeDef,
     FindingCriteriaTypeDef,
+    ListCoverageResponseTypeDef,
     ListDetectorsResponseTypeDef,
     ListFiltersResponseTypeDef,
     ListFindingsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListIPSetsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
     ListThreatIntelSetsResponseTypeDef,
     PaginatorConfigTypeDef,
     SortCriteriaTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeMalwareScansPaginator",
+    "ListCoveragePaginator",
     "ListDetectorsPaginator",
     "ListFiltersPaginator",
     "ListFindingsPaginator",
     "ListIPSetsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
@@ -91,43 +91,62 @@
 
     def paginate(
         self,
         *,
         DetectorId: str,
         FilterCriteria: FilterCriteriaTypeDef = ...,
         SortCriteria: SortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMalwareScansResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.DescribeMalwareScans.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#describemalwarescanspaginator)
         """
 
+class ListCoveragePaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListCoverage)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listcoveragepaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        DetectorId: str,
+        FilterCriteria: CoverageFilterCriteriaTypeDef = ...,
+        SortCriteria: CoverageSortCriteriaTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListCoverageResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListCoverage.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listcoveragepaginator)
+        """
+
 class ListDetectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListDetectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listdetectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDetectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListDetectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listdetectorspaginator)
         """
 
 class ListFiltersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListFilters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listfilterspaginator)
     """
 
     def paginate(
-        self, *, DetectorId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DetectorId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFiltersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListFilters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listfilterspaginator)
         """
 
 class ListFindingsPaginator(AioPaginator):
@@ -138,43 +157,43 @@
 
     def paginate(
         self,
         *,
         DetectorId: str,
         FindingCriteria: FindingCriteriaTypeDef = ...,
         SortCriteria: SortCriteriaTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listfindingspaginator)
         """
 
 class ListIPSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListIPSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listipsetspaginator)
     """
 
     def paginate(
-        self, *, DetectorId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DetectorId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListIPSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListIPSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listipsetspaginator)
         """
 
 class ListInvitationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListInvitations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listinvitationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listinvitationspaginator)
         """
 
 class ListMembersPaginator(AioPaginator):
@@ -184,41 +203,41 @@
     """
 
     def paginate(
         self,
         *,
         DetectorId: str,
         OnlyAssociated: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listmemberspaginator)
         """
 
 class ListOrganizationAdminAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListOrganizationAdminAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listorganizationadminaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationAdminAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListOrganizationAdminAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listorganizationadminaccountspaginator)
         """
 
 class ListThreatIntelSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListThreatIntelSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listthreatintelsetspaginator)
     """
 
     def paginate(
-        self, *, DetectorId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DetectorId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThreatIntelSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty.Paginator.ListThreatIntelSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/paginators/#listthreatintelsetspaginator)
         """
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/type_defs.py` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -13,30 +13,43 @@
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AdminStatusType,
+    AutoEnableMembersType,
+    CoverageFilterCriterionKeyType,
+    CoverageSortKeyType,
+    CoverageStatisticsTypeType,
+    CoverageStatusType,
     CriterionKeyType,
     DataSourceStatusType,
     DataSourceType,
+    DetectorFeatureResultType,
+    DetectorFeatureType,
     DetectorStatusType,
     EbsSnapshotPreservationType,
+    FeatureStatusType,
     FeedbackType,
     FilterActionType,
     FindingPublishingFrequencyType,
+    FreeTrialFeatureResultType,
     IpSetFormatType,
     IpSetStatusType,
     OrderByType,
+    OrgFeatureStatusType,
+    OrgFeatureType,
     PublishingStatusType,
     ScanResultType,
     ScanStatusType,
+    ScanTypeType,
     ThreatIntelSetFormatType,
     ThreatIntelSetStatusType,
+    UsageFeatureType,
     UsageStatisticTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -48,53 +61,62 @@
 
 __all__ = (
     "AcceptAdministratorInvitationRequestRequestTypeDef",
     "AcceptInvitationRequestRequestTypeDef",
     "AccessControlListTypeDef",
     "AccessKeyDetailsTypeDef",
     "AccountDetailTypeDef",
+    "FreeTrialFeatureConfigurationResultTypeDef",
     "BlockPublicAccessTypeDef",
     "DnsRequestActionTypeDef",
+    "AddonDetailsTypeDef",
     "AdminAccountTypeDef",
     "AdministratorTypeDef",
     "ArchiveFindingsRequestRequestTypeDef",
     "DomainDetailsTypeDef",
     "RemoteAccountDetailsTypeDef",
     "BucketPolicyTypeDef",
     "CityTypeDef",
     "CloudTrailConfigurationResultTypeDef",
     "ConditionTypeDef",
     "SecurityContextTypeDef",
     "VolumeMountTypeDef",
     "CountryTypeDef",
-    "ResponseMetadataTypeDef",
+    "CoverageFilterConditionTypeDef",
+    "CoverageSortCriteriaTypeDef",
+    "CoverageStatisticsTypeDef",
+    "CreateFilterResponseTypeDef",
     "CreateIPSetRequestRequestTypeDef",
+    "CreateIPSetResponseTypeDef",
     "UnprocessedAccountTypeDef",
     "DestinationPropertiesTypeDef",
+    "CreatePublishingDestinationResponseTypeDef",
     "CreateSampleFindingsRequestRequestTypeDef",
     "CreateThreatIntelSetRequestRequestTypeDef",
+    "CreateThreatIntelSetResponseTypeDef",
     "DNSLogsConfigurationResultTypeDef",
     "FlowLogsConfigurationResultTypeDef",
     "S3LogsConfigurationResultTypeDef",
     "S3LogsConfigurationTypeDef",
     "DataSourceFreeTrialTypeDef",
     "DeclineInvitationsRequestRequestTypeDef",
     "DefaultServerSideEncryptionTypeDef",
     "DeleteDetectorRequestRequestTypeDef",
     "DeleteFilterRequestRequestTypeDef",
     "DeleteIPSetRequestRequestTypeDef",
     "DeleteInvitationsRequestRequestTypeDef",
     "DeleteMembersRequestRequestTypeDef",
     "DeletePublishingDestinationRequestRequestTypeDef",
     "DeleteThreatIntelSetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "SortCriteriaTypeDef",
     "DescribeOrganizationConfigurationRequestRequestTypeDef",
     "DescribePublishingDestinationRequestRequestTypeDef",
     "DestinationTypeDef",
+    "DetectorAdditionalConfigurationResultTypeDef",
+    "DetectorAdditionalConfigurationTypeDef",
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     "DisassociateFromAdministratorAccountRequestRequestTypeDef",
     "DisassociateFromMasterAccountRequestRequestTypeDef",
     "DisassociateMembersRequestRequestTypeDef",
     "VolumeDetailTypeDef",
     "EbsVolumesResultTypeDef",
     "TagTypeDef",
@@ -103,185 +125,216 @@
     "FilterConditionTypeDef",
     "FindingStatisticsTypeDef",
     "GeoLocationTypeDef",
     "GetAdministratorAccountRequestRequestTypeDef",
     "GetDetectorRequestRequestTypeDef",
     "GetFilterRequestRequestTypeDef",
     "GetIPSetRequestRequestTypeDef",
+    "GetIPSetResponseTypeDef",
+    "GetInvitationsCountResponseTypeDef",
     "GetMalwareScanSettingsRequestRequestTypeDef",
     "GetMasterAccountRequestRequestTypeDef",
     "MasterTypeDef",
     "GetMemberDetectorsRequestRequestTypeDef",
     "GetMembersRequestRequestTypeDef",
     "MemberTypeDef",
     "GetRemainingFreeTrialDaysRequestRequestTypeDef",
     "GetThreatIntelSetRequestRequestTypeDef",
+    "GetThreatIntelSetResponseTypeDef",
     "UsageCriteriaTypeDef",
     "HighestSeverityThreatDetailsTypeDef",
     "HostPathTypeDef",
     "IamInstanceProfileTypeDef",
     "ProductCodeTypeDef",
     "InvitationTypeDef",
     "InviteMembersRequestRequestTypeDef",
     "KubernetesAuditLogsConfigurationResultTypeDef",
     "KubernetesAuditLogsConfigurationTypeDef",
     "KubernetesUserDetailsTypeDef",
+    "LineageObjectTypeDef",
+    "ListDetectorsRequestListDetectorsPaginateTypeDef",
     "ListDetectorsRequestRequestTypeDef",
+    "ListDetectorsResponseTypeDef",
+    "ListFiltersRequestListFiltersPaginateTypeDef",
     "ListFiltersRequestRequestTypeDef",
+    "ListFiltersResponseTypeDef",
+    "ListFindingsResponseTypeDef",
+    "ListIPSetsRequestListIPSetsPaginateTypeDef",
     "ListIPSetsRequestRequestTypeDef",
+    "ListIPSetsResponseTypeDef",
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
     "ListInvitationsRequestRequestTypeDef",
+    "ListMembersRequestListMembersPaginateTypeDef",
     "ListMembersRequestRequestTypeDef",
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
     "ListPublishingDestinationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
     "ListThreatIntelSetsRequestRequestTypeDef",
+    "ListThreatIntelSetsResponseTypeDef",
     "LocalIpDetailsTypeDef",
     "LocalPortDetailsTypeDef",
+    "LoginAttributeTypeDef",
     "ScanEc2InstanceWithFindingsTypeDef",
+    "MemberAdditionalConfigurationResultTypeDef",
+    "MemberAdditionalConfigurationTypeDef",
     "RemotePortDetailsTypeDef",
     "PrivateIpAddressDetailsTypeDef",
     "SecurityGroupTypeDef",
+    "OrganizationAdditionalConfigurationResultTypeDef",
+    "OrganizationAdditionalConfigurationTypeDef",
     "OrganizationS3LogsConfigurationResultTypeDef",
     "OrganizationS3LogsConfigurationTypeDef",
     "OrganizationEbsVolumesResultTypeDef",
     "OrganizationEbsVolumesTypeDef",
     "OrganizationKubernetesAuditLogsConfigurationResultTypeDef",
     "OrganizationKubernetesAuditLogsConfigurationTypeDef",
     "OrganizationTypeDef",
     "OwnerTypeDef",
+    "PaginatorConfigTypeDef",
+    "RdsDbUserDetailsTypeDef",
     "ResourceDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "ScanConditionPairTypeDef",
     "ScannedItemCountTypeDef",
     "ThreatsDetectedItemCountTypeDef",
     "ScanFilePathTypeDef",
     "ScanResultDetailsTypeDef",
     "TriggerDetailsTypeDef",
     "ServiceAdditionalInfoTypeDef",
+    "StartMalwareScanRequestRequestTypeDef",
+    "StartMalwareScanResponseTypeDef",
     "StartMonitoringMembersRequestRequestTypeDef",
     "StopMonitoringMembersRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TotalTypeDef",
     "UnarchiveFindingsRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateFilterResponseTypeDef",
     "UpdateFindingsFeedbackRequestRequestTypeDef",
     "UpdateIPSetRequestRequestTypeDef",
     "UpdateThreatIntelSetRequestRequestTypeDef",
     "CreateMembersRequestRequestTypeDef",
     "AccountLevelPermissionsTypeDef",
+    "CoverageEksClusterDetailsTypeDef",
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    "GetAdministratorAccountResponseTypeDef",
     "BucketLevelPermissionsTypeDef",
     "FindingCriteriaTypeDef",
     "ContainerTypeDef",
-    "CreateFilterResponseTypeDef",
-    "CreateIPSetResponseTypeDef",
-    "CreatePublishingDestinationResponseTypeDef",
-    "CreateThreatIntelSetResponseTypeDef",
-    "GetAdministratorAccountResponseTypeDef",
-    "GetIPSetResponseTypeDef",
-    "GetInvitationsCountResponseTypeDef",
-    "GetThreatIntelSetResponseTypeDef",
-    "ListDetectorsResponseTypeDef",
-    "ListFiltersResponseTypeDef",
-    "ListFindingsResponseTypeDef",
-    "ListIPSetsResponseTypeDef",
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListThreatIntelSetsResponseTypeDef",
-    "UpdateFilterResponseTypeDef",
+    "CoverageFilterCriterionTypeDef",
+    "GetCoverageStatisticsResponseTypeDef",
     "CreateMembersResponseTypeDef",
     "DeclineInvitationsResponseTypeDef",
     "DeleteInvitationsResponseTypeDef",
     "DeleteMembersResponseTypeDef",
     "DisassociateMembersResponseTypeDef",
     "InviteMembersResponseTypeDef",
     "StartMonitoringMembersResponseTypeDef",
     "StopMonitoringMembersResponseTypeDef",
     "UpdateMemberDetectorsResponseTypeDef",
     "CreatePublishingDestinationRequestRequestTypeDef",
     "DescribePublishingDestinationResponseTypeDef",
     "UpdatePublishingDestinationRequestRequestTypeDef",
     "KubernetesDataSourceFreeTrialTypeDef",
     "MalwareProtectionDataSourceFreeTrialTypeDef",
-    "ListDetectorsRequestListDetectorsPaginateTypeDef",
-    "ListFiltersRequestListFiltersPaginateTypeDef",
-    "ListIPSetsRequestListIPSetsPaginateTypeDef",
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    "ListMembersRequestListMembersPaginateTypeDef",
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    "ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
     "GetFindingsRequestRequestTypeDef",
     "ListPublishingDestinationsResponseTypeDef",
+    "DetectorFeatureConfigurationResultTypeDef",
+    "DetectorFeatureConfigurationTypeDef",
     "EbsVolumeDetailsTypeDef",
     "ScanEc2InstanceWithFindingsResultTypeDef",
     "EksClusterDetailsTypeDef",
+    "RdsDbInstanceDetailsTypeDef",
     "EvidenceTypeDef",
     "FilterCriterionTypeDef",
     "GetFindingsStatisticsResponseTypeDef",
     "GetMasterAccountResponseTypeDef",
     "GetMembersResponseTypeDef",
     "ListMembersResponseTypeDef",
     "GetUsageStatisticsRequestRequestTypeDef",
     "VolumeTypeDef",
     "ListInvitationsResponseTypeDef",
     "KubernetesConfigurationResultTypeDef",
     "KubernetesConfigurationTypeDef",
+    "ProcessDetailsTypeDef",
     "MalwareProtectionConfigurationTypeDef",
+    "MemberFeaturesConfigurationResultTypeDef",
+    "MemberFeaturesConfigurationTypeDef",
     "NetworkInterfaceTypeDef",
+    "VpcConfigTypeDef",
+    "OrganizationFeatureConfigurationResultTypeDef",
+    "OrganizationFeatureConfigurationTypeDef",
     "OrganizationScanEc2InstanceWithFindingsResultTypeDef",
     "OrganizationScanEc2InstanceWithFindingsTypeDef",
     "OrganizationKubernetesConfigurationResultTypeDef",
     "OrganizationKubernetesConfigurationTypeDef",
     "RemoteIpDetailsTypeDef",
     "ScanConditionTypeDef",
     "ScanThreatNameTypeDef",
     "ScanTypeDef",
     "UsageAccountResultTypeDef",
     "UsageDataSourceResultTypeDef",
+    "UsageFeatureResultTypeDef",
     "UsageResourceResultTypeDef",
+    "CoverageResourceDetailsTypeDef",
     "PermissionConfigurationTypeDef",
     "CreateFilterRequestRequestTypeDef",
     "GetFilterResponseTypeDef",
     "GetFindingsStatisticsRequestRequestTypeDef",
     "ListFindingsRequestListFindingsPaginateTypeDef",
     "ListFindingsRequestRequestTypeDef",
     "UpdateFilterRequestRequestTypeDef",
+    "CoverageFilterCriteriaTypeDef",
     "DataSourcesFreeTrialTypeDef",
     "MalwareProtectionConfigurationResultTypeDef",
     "FilterCriteriaTypeDef",
     "EcsTaskDetailsTypeDef",
     "KubernetesWorkloadDetailsTypeDef",
+    "RuntimeContextTypeDef",
     "DataSourceConfigurationsTypeDef",
     "InstanceDetailsTypeDef",
+    "LambdaDetailsTypeDef",
     "OrganizationMalwareProtectionConfigurationResultTypeDef",
     "OrganizationMalwareProtectionConfigurationTypeDef",
     "AwsApiCallActionTypeDef",
     "KubernetesApiCallActionTypeDef",
     "NetworkConnectionActionTypeDef",
     "PortProbeDetailTypeDef",
+    "RdsLoginAttemptActionTypeDef",
     "ScanResourceCriteriaTypeDef",
     "ThreatDetectedByNameTypeDef",
     "DescribeMalwareScansResponseTypeDef",
     "UsageStatisticsTypeDef",
+    "CoverageResourceTypeDef",
     "PublicAccessTypeDef",
+    "GetCoverageStatisticsRequestRequestTypeDef",
+    "ListCoverageRequestListCoveragePaginateTypeDef",
+    "ListCoverageRequestRequestTypeDef",
     "AccountFreeTrialInfoTypeDef",
     "DataSourceConfigurationsResultTypeDef",
     "UnprocessedDataSourcesResultTypeDef",
     "DescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef",
     "DescribeMalwareScansRequestRequestTypeDef",
     "EcsClusterDetailsTypeDef",
     "KubernetesDetailsTypeDef",
+    "RuntimeDetailsTypeDef",
     "CreateDetectorRequestRequestTypeDef",
     "UpdateDetectorRequestRequestTypeDef",
     "UpdateMemberDetectorsRequestRequestTypeDef",
     "OrganizationDataSourceConfigurationsResultTypeDef",
     "OrganizationDataSourceConfigurationsTypeDef",
     "PortProbeActionTypeDef",
     "GetMalwareScanSettingsResponseTypeDef",
     "UpdateMalwareScanSettingsRequestRequestTypeDef",
     "ScanDetectionsTypeDef",
     "GetUsageStatisticsResponseTypeDef",
+    "ListCoverageResponseTypeDef",
     "S3BucketDetailTypeDef",
     "GetRemainingFreeTrialDaysResponseTypeDef",
     "GetDetectorResponseTypeDef",
     "MemberDataSourceConfigurationTypeDef",
     "CreateDetectorResponseTypeDef",
     "DescribeOrganizationConfigurationResponseTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
@@ -336,14 +389,23 @@
     "AccountDetailTypeDef",
     {
         "AccountId": str,
         "Email": str,
     },
 )
 
+FreeTrialFeatureConfigurationResultTypeDef = TypedDict(
+    "FreeTrialFeatureConfigurationResultTypeDef",
+    {
+        "Name": FreeTrialFeatureResultType,
+        "FreeTrialDaysRemaining": int,
+    },
+    total=False,
+)
+
 BlockPublicAccessTypeDef = TypedDict(
     "BlockPublicAccessTypeDef",
     {
         "IgnorePublicAcls": bool,
         "RestrictPublicBuckets": bool,
         "BlockPublicAcls": bool,
         "BlockPublicPolicy": bool,
@@ -357,14 +419,23 @@
         "Domain": str,
         "Protocol": str,
         "Blocked": bool,
     },
     total=False,
 )
 
+AddonDetailsTypeDef = TypedDict(
+    "AddonDetailsTypeDef",
+    {
+        "AddonVersion": str,
+        "AddonStatus": str,
+    },
+    total=False,
+)
+
 AdminAccountTypeDef = TypedDict(
     "AdminAccountTypeDef",
     {
         "AdminAccountId": str,
         "AdminStatus": AdminStatusType,
     },
     total=False,
@@ -471,22 +542,46 @@
     {
         "CountryCode": str,
         "CountryName": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CoverageFilterConditionTypeDef = TypedDict(
+    "CoverageFilterConditionTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Equals": Sequence[str],
+        "NotEquals": Sequence[str],
+    },
+    total=False,
+)
+
+CoverageSortCriteriaTypeDef = TypedDict(
+    "CoverageSortCriteriaTypeDef",
+    {
+        "AttributeName": CoverageSortKeyType,
+        "OrderBy": OrderByType,
+    },
+    total=False,
+)
+
+CoverageStatisticsTypeDef = TypedDict(
+    "CoverageStatisticsTypeDef",
+    {
+        "CountByResourceType": Dict[Literal["EKS"], int],
+        "CountByCoverageStatus": Dict[CoverageStatusType, int],
+    },
+    total=False,
+)
+
+CreateFilterResponseTypeDef = TypedDict(
+    "CreateFilterResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateIPSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIPSetRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -508,14 +603,22 @@
 
 class CreateIPSetRequestRequestTypeDef(
     _RequiredCreateIPSetRequestRequestTypeDef, _OptionalCreateIPSetRequestRequestTypeDef
 ):
     pass
 
 
+CreateIPSetResponseTypeDef = TypedDict(
+    "CreateIPSetResponseTypeDef",
+    {
+        "IpSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnprocessedAccountTypeDef = TypedDict(
     "UnprocessedAccountTypeDef",
     {
         "AccountId": str,
         "Result": str,
     },
 )
@@ -525,14 +628,22 @@
     {
         "DestinationArn": str,
         "KmsKeyArn": str,
     },
     total=False,
 )
 
+CreatePublishingDestinationResponseTypeDef = TypedDict(
+    "CreatePublishingDestinationResponseTypeDef",
+    {
+        "DestinationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSampleFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSampleFindingsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalCreateSampleFindingsRequestRequestTypeDef = TypedDict(
@@ -574,14 +685,22 @@
 class CreateThreatIntelSetRequestRequestTypeDef(
     _RequiredCreateThreatIntelSetRequestRequestTypeDef,
     _OptionalCreateThreatIntelSetRequestRequestTypeDef,
 ):
     pass
 
 
+CreateThreatIntelSetResponseTypeDef = TypedDict(
+    "CreateThreatIntelSetResponseTypeDef",
+    {
+        "ThreatIntelSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DNSLogsConfigurationResultTypeDef = TypedDict(
     "DNSLogsConfigurationResultTypeDef",
     {
         "Status": DataSourceStatusType,
     },
 )
 
@@ -680,39 +799,45 @@
     "DeleteThreatIntelSetRequestRequestTypeDef",
     {
         "DetectorId": str,
         "ThreatIntelSetId": str,
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
 SortCriteriaTypeDef = TypedDict(
     "SortCriteriaTypeDef",
     {
         "AttributeName": str,
         "OrderBy": OrderByType,
     },
     total=False,
 )
 
-DescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationRequestRequestTypeDef",
+_RequiredDescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeOrganizationConfigurationRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
+_OptionalDescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeOrganizationConfigurationRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+
+class DescribeOrganizationConfigurationRequestRequestTypeDef(
+    _RequiredDescribeOrganizationConfigurationRequestRequestTypeDef,
+    _OptionalDescribeOrganizationConfigurationRequestRequestTypeDef,
+):
+    pass
+
 
 DescribePublishingDestinationRequestRequestTypeDef = TypedDict(
     "DescribePublishingDestinationRequestRequestTypeDef",
     {
         "DetectorId": str,
         "DestinationId": str,
     },
@@ -723,14 +848,33 @@
     {
         "DestinationId": str,
         "DestinationType": Literal["S3"],
         "Status": PublishingStatusType,
     },
 )
 
+DetectorAdditionalConfigurationResultTypeDef = TypedDict(
+    "DetectorAdditionalConfigurationResultTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+    },
+    total=False,
+)
+
+DetectorAdditionalConfigurationTypeDef = TypedDict(
+    "DetectorAdditionalConfigurationTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+    },
+    total=False,
+)
+
 DisableOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     {
         "AdminAccountId": str,
     },
 )
 
@@ -857,14 +1001,34 @@
     "GetIPSetRequestRequestTypeDef",
     {
         "DetectorId": str,
         "IpSetId": str,
     },
 )
 
+GetIPSetResponseTypeDef = TypedDict(
+    "GetIPSetResponseTypeDef",
+    {
+        "Name": str,
+        "Format": IpSetFormatType,
+        "Location": str,
+        "Status": IpSetStatusType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetInvitationsCountResponseTypeDef = TypedDict(
+    "GetInvitationsCountResponseTypeDef",
+    {
+        "InvitationsCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMalwareScanSettingsRequestRequestTypeDef = TypedDict(
     "GetMalwareScanSettingsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 
@@ -953,34 +1117,37 @@
     "GetThreatIntelSetRequestRequestTypeDef",
     {
         "DetectorId": str,
         "ThreatIntelSetId": str,
     },
 )
 
-_RequiredUsageCriteriaTypeDef = TypedDict(
-    "_RequiredUsageCriteriaTypeDef",
+GetThreatIntelSetResponseTypeDef = TypedDict(
+    "GetThreatIntelSetResponseTypeDef",
     {
-        "DataSources": Sequence[DataSourceType],
+        "Name": str,
+        "Format": ThreatIntelSetFormatType,
+        "Location": str,
+        "Status": ThreatIntelSetStatusType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalUsageCriteriaTypeDef = TypedDict(
-    "_OptionalUsageCriteriaTypeDef",
+
+UsageCriteriaTypeDef = TypedDict(
+    "UsageCriteriaTypeDef",
     {
         "AccountIds": Sequence[str],
+        "DataSources": Sequence[DataSourceType],
         "Resources": Sequence[str],
+        "Features": Sequence[UsageFeatureType],
     },
     total=False,
 )
 
-
-class UsageCriteriaTypeDef(_RequiredUsageCriteriaTypeDef, _OptionalUsageCriteriaTypeDef):
-    pass
-
-
 HighestSeverityThreatDetailsTypeDef = TypedDict(
     "HighestSeverityThreatDetailsTypeDef",
     {
         "Severity": str,
         "ThreatName": str,
         "Count": int,
     },
@@ -1063,27 +1230,83 @@
 
 KubernetesUserDetailsTypeDef = TypedDict(
     "KubernetesUserDetailsTypeDef",
     {
         "Username": str,
         "Uid": str,
         "Groups": List[str],
+        "SessionName": List[str],
+    },
+    total=False,
+)
+
+LineageObjectTypeDef = TypedDict(
+    "LineageObjectTypeDef",
+    {
+        "StartTime": datetime,
+        "NamespacePid": int,
+        "UserId": int,
+        "Name": str,
+        "Pid": int,
+        "Uuid": str,
+        "ExecutablePath": str,
+        "Euid": int,
+        "ParentUuid": str,
+    },
+    total=False,
+)
+
+ListDetectorsRequestListDetectorsPaginateTypeDef = TypedDict(
+    "ListDetectorsRequestListDetectorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDetectorsRequestRequestTypeDef = TypedDict(
     "ListDetectorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListDetectorsResponseTypeDef = TypedDict(
+    "ListDetectorsResponseTypeDef",
+    {
+        "DetectorIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
+    "_RequiredListFiltersRequestListFiltersPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
+    "_OptionalListFiltersRequestListFiltersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFiltersRequestListFiltersPaginateTypeDef(
+    _RequiredListFiltersRequestListFiltersPaginateTypeDef,
+    _OptionalListFiltersRequestListFiltersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFiltersRequestRequestTypeDef = TypedDict(
     "_RequiredListFiltersRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListFiltersRequestRequestTypeDef = TypedDict(
@@ -1098,14 +1321,54 @@
 
 class ListFiltersRequestRequestTypeDef(
     _RequiredListFiltersRequestRequestTypeDef, _OptionalListFiltersRequestRequestTypeDef
 ):
     pass
 
 
+ListFiltersResponseTypeDef = TypedDict(
+    "ListFiltersResponseTypeDef",
+    {
+        "FilterNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFindingsResponseTypeDef = TypedDict(
+    "ListFindingsResponseTypeDef",
+    {
+        "FindingIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
+    "_RequiredListIPSetsRequestListIPSetsPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
+    "_OptionalListIPSetsRequestListIPSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListIPSetsRequestListIPSetsPaginateTypeDef(
+    _RequiredListIPSetsRequestListIPSetsPaginateTypeDef,
+    _OptionalListIPSetsRequestListIPSetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListIPSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListIPSetsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListIPSetsRequestRequestTypeDef = TypedDict(
@@ -1120,23 +1383,63 @@
 
 class ListIPSetsRequestRequestTypeDef(
     _RequiredListIPSetsRequestRequestTypeDef, _OptionalListIPSetsRequestRequestTypeDef
 ):
     pass
 
 
+ListIPSetsResponseTypeDef = TypedDict(
+    "ListIPSetsResponseTypeDef",
+    {
+        "IpSetIds": List[str],
+        "NextToken": str,
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "_RequiredListMembersRequestListMembersPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "_OptionalListMembersRequestListMembersPaginateTypeDef",
+    {
+        "OnlyAssociated": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMembersRequestListMembersPaginateTypeDef(
+    _RequiredListMembersRequestListMembersPaginateTypeDef,
+    _OptionalListMembersRequestListMembersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListMembersRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListMembersRequestRequestTypeDef = TypedDict(
@@ -1152,14 +1455,22 @@
 
 class ListMembersRequestRequestTypeDef(
     _RequiredListMembersRequestRequestTypeDef, _OptionalListMembersRequestRequestTypeDef
 ):
     pass
 
 
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -1191,14 +1502,44 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
+    "_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
+    "_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef(
+    _RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
+    _OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListThreatIntelSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListThreatIntelSetsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListThreatIntelSetsRequestRequestTypeDef = TypedDict(
@@ -1214,14 +1555,23 @@
 class ListThreatIntelSetsRequestRequestTypeDef(
     _RequiredListThreatIntelSetsRequestRequestTypeDef,
     _OptionalListThreatIntelSetsRequestRequestTypeDef,
 ):
     pass
 
 
+ListThreatIntelSetsResponseTypeDef = TypedDict(
+    "ListThreatIntelSetsResponseTypeDef",
+    {
+        "ThreatIntelSetIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LocalIpDetailsTypeDef = TypedDict(
     "LocalIpDetailsTypeDef",
     {
         "IpAddressV4": str,
     },
     total=False,
 )
@@ -1231,22 +1581,52 @@
     {
         "Port": int,
         "PortName": str,
     },
     total=False,
 )
 
+LoginAttributeTypeDef = TypedDict(
+    "LoginAttributeTypeDef",
+    {
+        "User": str,
+        "Application": str,
+        "FailedLoginAttempts": int,
+        "SuccessfulLoginAttempts": int,
+    },
+    total=False,
+)
+
 ScanEc2InstanceWithFindingsTypeDef = TypedDict(
     "ScanEc2InstanceWithFindingsTypeDef",
     {
         "EbsVolumes": bool,
     },
     total=False,
 )
 
+MemberAdditionalConfigurationResultTypeDef = TypedDict(
+    "MemberAdditionalConfigurationResultTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+    },
+    total=False,
+)
+
+MemberAdditionalConfigurationTypeDef = TypedDict(
+    "MemberAdditionalConfigurationTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+    },
+    total=False,
+)
+
 RemotePortDetailsTypeDef = TypedDict(
     "RemotePortDetailsTypeDef",
     {
         "Port": int,
         "PortName": str,
     },
     total=False,
@@ -1266,14 +1646,32 @@
     {
         "GroupId": str,
         "GroupName": str,
     },
     total=False,
 )
 
+OrganizationAdditionalConfigurationResultTypeDef = TypedDict(
+    "OrganizationAdditionalConfigurationResultTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "AutoEnable": OrgFeatureStatusType,
+    },
+    total=False,
+)
+
+OrganizationAdditionalConfigurationTypeDef = TypedDict(
+    "OrganizationAdditionalConfigurationTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "AutoEnable": OrgFeatureStatusType,
+    },
+    total=False,
+)
+
 OrganizationS3LogsConfigurationResultTypeDef = TypedDict(
     "OrganizationS3LogsConfigurationResultTypeDef",
     {
         "AutoEnable": bool,
     },
 )
 
@@ -1329,22 +1727,55 @@
     "OwnerTypeDef",
     {
         "Id": str,
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
+RdsDbUserDetailsTypeDef = TypedDict(
+    "RdsDbUserDetailsTypeDef",
+    {
+        "User": str,
+        "Application": str,
+        "Database": str,
+        "Ssl": str,
+        "AuthMethod": str,
+    },
+    total=False,
+)
+
 ResourceDetailsTypeDef = TypedDict(
     "ResourceDetailsTypeDef",
     {
         "InstanceArn": str,
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
 _RequiredScanConditionPairTypeDef = TypedDict(
     "_RequiredScanConditionPairTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalScanConditionPairTypeDef = TypedDict(
@@ -1413,14 +1844,29 @@
     {
         "Value": str,
         "Type": str,
     },
     total=False,
 )
 
+StartMalwareScanRequestRequestTypeDef = TypedDict(
+    "StartMalwareScanRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+
+StartMalwareScanResponseTypeDef = TypedDict(
+    "StartMalwareScanResponseTypeDef",
+    {
+        "ScanId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMonitoringMembersRequestRequestTypeDef = TypedDict(
     "StartMonitoringMembersRequestRequestTypeDef",
     {
         "DetectorId": str,
         "AccountIds": Sequence[str],
     },
 )
@@ -1462,14 +1908,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateFilterResponseTypeDef = TypedDict(
+    "UpdateFilterResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFindingsFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFindingsFeedbackRequestRequestTypeDef",
     {
         "DetectorId": str,
         "FindingIds": Sequence[str],
         "Feedback": FeedbackType,
     },
@@ -1551,14 +2005,42 @@
     "AccountLevelPermissionsTypeDef",
     {
         "BlockPublicAccess": BlockPublicAccessTypeDef,
     },
     total=False,
 )
 
+CoverageEksClusterDetailsTypeDef = TypedDict(
+    "CoverageEksClusterDetailsTypeDef",
+    {
+        "ClusterName": str,
+        "CoveredNodes": int,
+        "CompatibleNodes": int,
+        "AddonDetails": AddonDetailsTypeDef,
+    },
+    total=False,
+)
+
+ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    {
+        "AdminAccounts": List[AdminAccountTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetAdministratorAccountResponseTypeDef = TypedDict(
+    "GetAdministratorAccountResponseTypeDef",
+    {
+        "Administrator": AdministratorTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BucketLevelPermissionsTypeDef = TypedDict(
     "BucketLevelPermissionsTypeDef",
     {
         "AccessControlList": AccessControlListTypeDef,
         "BucketPolicy": BucketPolicyTypeDef,
         "BlockPublicAccess": BlockPublicAccessTypeDef,
     },
@@ -1583,225 +2065,100 @@
         "ImagePrefix": str,
         "VolumeMounts": List[VolumeMountTypeDef],
         "SecurityContext": SecurityContextTypeDef,
     },
     total=False,
 )
 
-CreateFilterResponseTypeDef = TypedDict(
-    "CreateFilterResponseTypeDef",
+CoverageFilterCriterionTypeDef = TypedDict(
+    "CoverageFilterCriterionTypeDef",
     {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIPSetResponseTypeDef = TypedDict(
-    "CreateIPSetResponseTypeDef",
-    {
-        "IpSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePublishingDestinationResponseTypeDef = TypedDict(
-    "CreatePublishingDestinationResponseTypeDef",
-    {
-        "DestinationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateThreatIntelSetResponseTypeDef = TypedDict(
-    "CreateThreatIntelSetResponseTypeDef",
-    {
-        "ThreatIntelSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAdministratorAccountResponseTypeDef = TypedDict(
-    "GetAdministratorAccountResponseTypeDef",
-    {
-        "Administrator": AdministratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIPSetResponseTypeDef = TypedDict(
-    "GetIPSetResponseTypeDef",
-    {
-        "Name": str,
-        "Format": IpSetFormatType,
-        "Location": str,
-        "Status": IpSetStatusType,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetInvitationsCountResponseTypeDef = TypedDict(
-    "GetInvitationsCountResponseTypeDef",
-    {
-        "InvitationsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetThreatIntelSetResponseTypeDef = TypedDict(
-    "GetThreatIntelSetResponseTypeDef",
-    {
-        "Name": str,
-        "Format": ThreatIntelSetFormatType,
-        "Location": str,
-        "Status": ThreatIntelSetStatusType,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDetectorsResponseTypeDef = TypedDict(
-    "ListDetectorsResponseTypeDef",
-    {
-        "DetectorIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFiltersResponseTypeDef = TypedDict(
-    "ListFiltersResponseTypeDef",
-    {
-        "FilterNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFindingsResponseTypeDef = TypedDict(
-    "ListFindingsResponseTypeDef",
-    {
-        "FindingIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIPSetsResponseTypeDef = TypedDict(
-    "ListIPSetsResponseTypeDef",
-    {
-        "IpSetIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    {
-        "AdminAccounts": List[AdminAccountTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThreatIntelSetsResponseTypeDef = TypedDict(
-    "ListThreatIntelSetsResponseTypeDef",
-    {
-        "ThreatIntelSetIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CriterionKey": CoverageFilterCriterionKeyType,
+        "FilterCondition": CoverageFilterConditionTypeDef,
     },
+    total=False,
 )
 
-UpdateFilterResponseTypeDef = TypedDict(
-    "UpdateFilterResponseTypeDef",
+GetCoverageStatisticsResponseTypeDef = TypedDict(
+    "GetCoverageStatisticsResponseTypeDef",
     {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CoverageStatistics": CoverageStatisticsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMembersResponseTypeDef = TypedDict(
     "CreateMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineInvitationsResponseTypeDef = TypedDict(
     "DeclineInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInvitationsResponseTypeDef = TypedDict(
     "DeleteInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMembersResponseTypeDef = TypedDict(
     "DeleteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateMembersResponseTypeDef = TypedDict(
     "DisassociateMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteMembersResponseTypeDef = TypedDict(
     "InviteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMonitoringMembersResponseTypeDef = TypedDict(
     "StartMonitoringMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopMonitoringMembersResponseTypeDef = TypedDict(
     "StopMonitoringMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMemberDetectorsResponseTypeDef = TypedDict(
     "UpdateMemberDetectorsResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePublishingDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePublishingDestinationRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -1829,15 +2186,15 @@
     "DescribePublishingDestinationResponseTypeDef",
     {
         "DestinationId": str,
         "DestinationType": Literal["S3"],
         "Status": PublishingStatusType,
         "PublishingFailureStartTimestamp": int,
         "DestinationProperties": DestinationPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePublishingDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePublishingDestinationRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -1872,127 +2229,14 @@
     "MalwareProtectionDataSourceFreeTrialTypeDef",
     {
         "ScanEc2InstanceWithFindings": DataSourceFreeTrialTypeDef,
     },
     total=False,
 )
 
-ListDetectorsRequestListDetectorsPaginateTypeDef = TypedDict(
-    "ListDetectorsRequestListDetectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
-    "_RequiredListFiltersRequestListFiltersPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
-    "_OptionalListFiltersRequestListFiltersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFiltersRequestListFiltersPaginateTypeDef(
-    _RequiredListFiltersRequestListFiltersPaginateTypeDef,
-    _OptionalListFiltersRequestListFiltersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
-    "_RequiredListIPSetsRequestListIPSetsPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
-    "_OptionalListIPSetsRequestListIPSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListIPSetsRequestListIPSetsPaginateTypeDef(
-    _RequiredListIPSetsRequestListIPSetsPaginateTypeDef,
-    _OptionalListIPSetsRequestListIPSetsPaginateTypeDef,
-):
-    pass
-
-
-ListInvitationsRequestListInvitationsPaginateTypeDef = TypedDict(
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "_RequiredListMembersRequestListMembersPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "_OptionalListMembersRequestListMembersPaginateTypeDef",
-    {
-        "OnlyAssociated": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListMembersRequestListMembersPaginateTypeDef(
-    _RequiredListMembersRequestListMembersPaginateTypeDef,
-    _OptionalListMembersRequestListMembersPaginateTypeDef,
-):
-    pass
-
-
-ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
-    "_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
-    "_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef(
-    _RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
-    _OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
-):
-    pass
-
-
 _RequiredGetFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredGetFindingsRequestRequestTypeDef",
     {
         "DetectorId": str,
         "FindingIds": Sequence[str],
     },
 )
@@ -2012,16 +2256,37 @@
 
 
 ListPublishingDestinationsResponseTypeDef = TypedDict(
     "ListPublishingDestinationsResponseTypeDef",
     {
         "Destinations": List[DestinationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DetectorFeatureConfigurationResultTypeDef = TypedDict(
+    "DetectorFeatureConfigurationResultTypeDef",
+    {
+        "Name": DetectorFeatureResultType,
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+        "AdditionalConfiguration": List[DetectorAdditionalConfigurationResultTypeDef],
     },
+    total=False,
+)
+
+DetectorFeatureConfigurationTypeDef = TypedDict(
+    "DetectorFeatureConfigurationTypeDef",
+    {
+        "Name": DetectorFeatureType,
+        "Status": FeatureStatusType,
+        "AdditionalConfiguration": Sequence[DetectorAdditionalConfigurationTypeDef],
+    },
+    total=False,
 )
 
 EbsVolumeDetailsTypeDef = TypedDict(
     "EbsVolumeDetailsTypeDef",
     {
         "ScannedVolumeDetails": List[VolumeDetailTypeDef],
         "SkippedVolumeDetails": List[VolumeDetailTypeDef],
@@ -2046,14 +2311,27 @@
         "Status": str,
         "Tags": List[TagTypeDef],
         "CreatedAt": datetime,
     },
     total=False,
 )
 
+RdsDbInstanceDetailsTypeDef = TypedDict(
+    "RdsDbInstanceDetailsTypeDef",
+    {
+        "DbInstanceIdentifier": str,
+        "Engine": str,
+        "EngineVersion": str,
+        "DbClusterIdentifier": str,
+        "DbInstanceArn": str,
+        "Tags": List[TagTypeDef],
+    },
+    total=False,
+)
+
 EvidenceTypeDef = TypedDict(
     "EvidenceTypeDef",
     {
         "ThreatIntelligenceDetails": List[ThreatIntelligenceDetailTypeDef],
     },
     total=False,
 )
@@ -2067,41 +2345,41 @@
     total=False,
 )
 
 GetFindingsStatisticsResponseTypeDef = TypedDict(
     "GetFindingsStatisticsResponseTypeDef",
     {
         "FindingStatistics": FindingStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMasterAccountResponseTypeDef = TypedDict(
     "GetMasterAccountResponseTypeDef",
     {
         "Master": MasterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMembersResponseTypeDef = TypedDict(
     "GetMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembersResponseTypeDef = TypedDict(
     "ListMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetUsageStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetUsageStatisticsRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -2137,15 +2415,15 @@
 )
 
 ListInvitationsResponseTypeDef = TypedDict(
     "ListInvitationsResponseTypeDef",
     {
         "Invitations": List[InvitationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 KubernetesConfigurationResultTypeDef = TypedDict(
     "KubernetesConfigurationResultTypeDef",
     {
         "AuditLogs": KubernetesAuditLogsConfigurationResultTypeDef,
@@ -2155,22 +2433,63 @@
 KubernetesConfigurationTypeDef = TypedDict(
     "KubernetesConfigurationTypeDef",
     {
         "AuditLogs": KubernetesAuditLogsConfigurationTypeDef,
     },
 )
 
+ProcessDetailsTypeDef = TypedDict(
+    "ProcessDetailsTypeDef",
+    {
+        "Name": str,
+        "ExecutablePath": str,
+        "ExecutableSha256": str,
+        "NamespacePid": int,
+        "Pwd": str,
+        "Pid": int,
+        "StartTime": datetime,
+        "Uuid": str,
+        "ParentUuid": str,
+        "User": str,
+        "UserId": int,
+        "Euid": int,
+        "Lineage": List[LineageObjectTypeDef],
+    },
+    total=False,
+)
+
 MalwareProtectionConfigurationTypeDef = TypedDict(
     "MalwareProtectionConfigurationTypeDef",
     {
         "ScanEc2InstanceWithFindings": ScanEc2InstanceWithFindingsTypeDef,
     },
     total=False,
 )
 
+MemberFeaturesConfigurationResultTypeDef = TypedDict(
+    "MemberFeaturesConfigurationResultTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+        "AdditionalConfiguration": List[MemberAdditionalConfigurationResultTypeDef],
+    },
+    total=False,
+)
+
+MemberFeaturesConfigurationTypeDef = TypedDict(
+    "MemberFeaturesConfigurationTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "Status": FeatureStatusType,
+        "AdditionalConfiguration": Sequence[MemberAdditionalConfigurationTypeDef],
+    },
+    total=False,
+)
+
 NetworkInterfaceTypeDef = TypedDict(
     "NetworkInterfaceTypeDef",
     {
         "Ipv6Addresses": List[str],
         "NetworkInterfaceId": str,
         "PrivateDnsName": str,
         "PrivateIpAddress": str,
@@ -2180,14 +2499,44 @@
         "SecurityGroups": List[SecurityGroupTypeDef],
         "SubnetId": str,
         "VpcId": str,
     },
     total=False,
 )
 
+VpcConfigTypeDef = TypedDict(
+    "VpcConfigTypeDef",
+    {
+        "SubnetIds": List[str],
+        "VpcId": str,
+        "SecurityGroups": List[SecurityGroupTypeDef],
+    },
+    total=False,
+)
+
+OrganizationFeatureConfigurationResultTypeDef = TypedDict(
+    "OrganizationFeatureConfigurationResultTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "AutoEnable": OrgFeatureStatusType,
+        "AdditionalConfiguration": List[OrganizationAdditionalConfigurationResultTypeDef],
+    },
+    total=False,
+)
+
+OrganizationFeatureConfigurationTypeDef = TypedDict(
+    "OrganizationFeatureConfigurationTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "AutoEnable": OrgFeatureStatusType,
+        "AdditionalConfiguration": Sequence[OrganizationAdditionalConfigurationTypeDef],
+    },
+    total=False,
+)
+
 OrganizationScanEc2InstanceWithFindingsResultTypeDef = TypedDict(
     "OrganizationScanEc2InstanceWithFindingsResultTypeDef",
     {
         "EbsVolumes": OrganizationEbsVolumesResultTypeDef,
     },
     total=False,
 )
@@ -2257,14 +2606,15 @@
         "TriggerDetails": TriggerDetailsTypeDef,
         "ResourceDetails": ResourceDetailsTypeDef,
         "ScanResultDetails": ScanResultDetailsTypeDef,
         "AccountId": str,
         "TotalBytes": int,
         "FileCount": int,
         "AttachedVolumes": List[VolumeDetailTypeDef],
+        "ScanType": ScanTypeType,
     },
     total=False,
 )
 
 UsageAccountResultTypeDef = TypedDict(
     "UsageAccountResultTypeDef",
     {
@@ -2279,23 +2629,41 @@
     {
         "DataSource": DataSourceType,
         "Total": TotalTypeDef,
     },
     total=False,
 )
 
+UsageFeatureResultTypeDef = TypedDict(
+    "UsageFeatureResultTypeDef",
+    {
+        "Feature": UsageFeatureType,
+        "Total": TotalTypeDef,
+    },
+    total=False,
+)
+
 UsageResourceResultTypeDef = TypedDict(
     "UsageResourceResultTypeDef",
     {
         "Resource": str,
         "Total": TotalTypeDef,
     },
     total=False,
 )
 
+CoverageResourceDetailsTypeDef = TypedDict(
+    "CoverageResourceDetailsTypeDef",
+    {
+        "EksClusterDetails": CoverageEksClusterDetailsTypeDef,
+        "ResourceType": Literal["EKS"],
+    },
+    total=False,
+)
+
 PermissionConfigurationTypeDef = TypedDict(
     "PermissionConfigurationTypeDef",
     {
         "BucketLevelPermissions": BucketLevelPermissionsTypeDef,
         "AccountLevelPermissions": AccountLevelPermissionsTypeDef,
     },
     total=False,
@@ -2333,15 +2701,15 @@
     {
         "Name": str,
         "Description": str,
         "Action": FilterActionType,
         "Rank": int,
         "FindingCriteria": FindingCriteriaTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetFindingsStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetFindingsStatisticsRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -2371,15 +2739,15 @@
     },
 )
 _OptionalListFindingsRequestListFindingsPaginateTypeDef = TypedDict(
     "_OptionalListFindingsRequestListFindingsPaginateTypeDef",
     {
         "FindingCriteria": FindingCriteriaTypeDef,
         "SortCriteria": SortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListFindingsRequestListFindingsPaginateTypeDef(
     _RequiredListFindingsRequestListFindingsPaginateTypeDef,
@@ -2433,14 +2801,22 @@
 
 class UpdateFilterRequestRequestTypeDef(
     _RequiredUpdateFilterRequestRequestTypeDef, _OptionalUpdateFilterRequestRequestTypeDef
 ):
     pass
 
 
+CoverageFilterCriteriaTypeDef = TypedDict(
+    "CoverageFilterCriteriaTypeDef",
+    {
+        "FilterCriterion": Sequence[CoverageFilterCriterionTypeDef],
+    },
+    total=False,
+)
+
 DataSourcesFreeTrialTypeDef = TypedDict(
     "DataSourcesFreeTrialTypeDef",
     {
         "CloudTrail": DataSourceFreeTrialTypeDef,
         "DnsLogs": DataSourceFreeTrialTypeDef,
         "FlowLogs": DataSourceFreeTrialTypeDef,
         "S3Logs": DataSourceFreeTrialTypeDef,
@@ -2494,14 +2870,41 @@
         "HostNetwork": bool,
         "Containers": List[ContainerTypeDef],
         "Volumes": List[VolumeTypeDef],
     },
     total=False,
 )
 
+RuntimeContextTypeDef = TypedDict(
+    "RuntimeContextTypeDef",
+    {
+        "ModifyingProcess": ProcessDetailsTypeDef,
+        "ModifiedAt": datetime,
+        "ScriptPath": str,
+        "LibraryPath": str,
+        "LdPreloadValue": str,
+        "SocketPath": str,
+        "RuncBinaryPath": str,
+        "ReleaseAgentPath": str,
+        "MountSource": str,
+        "MountTarget": str,
+        "FileSystemType": str,
+        "Flags": List[str],
+        "ModuleName": str,
+        "ModuleFilePath": str,
+        "ModuleSha256": str,
+        "ShellHistoryFilePath": str,
+        "TargetProcess": ProcessDetailsTypeDef,
+        "AddressFamily": str,
+        "IanaProtocolNumber": int,
+        "MemoryRegions": List[str],
+    },
+    total=False,
+)
+
 DataSourceConfigurationsTypeDef = TypedDict(
     "DataSourceConfigurationsTypeDef",
     {
         "S3Logs": S3LogsConfigurationTypeDef,
         "Kubernetes": KubernetesConfigurationTypeDef,
         "MalwareProtection": MalwareProtectionConfigurationTypeDef,
     },
@@ -2524,14 +2927,30 @@
         "Platform": str,
         "ProductCodes": List[ProductCodeTypeDef],
         "Tags": List[TagTypeDef],
     },
     total=False,
 )
 
+LambdaDetailsTypeDef = TypedDict(
+    "LambdaDetailsTypeDef",
+    {
+        "FunctionArn": str,
+        "FunctionName": str,
+        "Description": str,
+        "LastModifiedAt": datetime,
+        "RevisionId": str,
+        "FunctionVersion": str,
+        "Role": str,
+        "VpcConfig": VpcConfigTypeDef,
+        "Tags": List[TagTypeDef],
+    },
+    total=False,
+)
+
 OrganizationMalwareProtectionConfigurationResultTypeDef = TypedDict(
     "OrganizationMalwareProtectionConfigurationResultTypeDef",
     {
         "ScanEc2InstanceWithFindings": OrganizationScanEc2InstanceWithFindingsResultTypeDef,
     },
     total=False,
 )
@@ -2594,14 +3013,23 @@
         "LocalPortDetails": LocalPortDetailsTypeDef,
         "LocalIpDetails": LocalIpDetailsTypeDef,
         "RemoteIpDetails": RemoteIpDetailsTypeDef,
     },
     total=False,
 )
 
+RdsLoginAttemptActionTypeDef = TypedDict(
+    "RdsLoginAttemptActionTypeDef",
+    {
+        "RemoteIpDetails": RemoteIpDetailsTypeDef,
+        "LoginAttributes": List[LoginAttributeTypeDef],
+    },
+    total=False,
+)
+
 ScanResourceCriteriaTypeDef = TypedDict(
     "ScanResourceCriteriaTypeDef",
     {
         "Include": Dict[Literal["EC2_INSTANCE_TAG"], ScanConditionTypeDef],
         "Exclude": Dict[Literal["EC2_INSTANCE_TAG"], ScanConditionTypeDef],
     },
     total=False,
@@ -2619,43 +3047,130 @@
 )
 
 DescribeMalwareScansResponseTypeDef = TypedDict(
     "DescribeMalwareScansResponseTypeDef",
     {
         "Scans": List[ScanTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UsageStatisticsTypeDef = TypedDict(
     "UsageStatisticsTypeDef",
     {
         "SumByAccount": List[UsageAccountResultTypeDef],
         "SumByDataSource": List[UsageDataSourceResultTypeDef],
         "SumByResource": List[UsageResourceResultTypeDef],
         "TopResources": List[UsageResourceResultTypeDef],
+        "SumByFeature": List[UsageFeatureResultTypeDef],
+    },
+    total=False,
+)
+
+CoverageResourceTypeDef = TypedDict(
+    "CoverageResourceTypeDef",
+    {
+        "ResourceId": str,
+        "DetectorId": str,
+        "AccountId": str,
+        "ResourceDetails": CoverageResourceDetailsTypeDef,
+        "CoverageStatus": CoverageStatusType,
+        "Issue": str,
+        "UpdatedAt": datetime,
     },
     total=False,
 )
 
 PublicAccessTypeDef = TypedDict(
     "PublicAccessTypeDef",
     {
         "PermissionConfiguration": PermissionConfigurationTypeDef,
         "EffectivePermission": str,
     },
     total=False,
 )
 
+_RequiredGetCoverageStatisticsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetCoverageStatisticsRequestRequestTypeDef",
+    {
+        "DetectorId": str,
+        "StatisticsType": Sequence[CoverageStatisticsTypeType],
+    },
+)
+_OptionalGetCoverageStatisticsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetCoverageStatisticsRequestRequestTypeDef",
+    {
+        "FilterCriteria": CoverageFilterCriteriaTypeDef,
+    },
+    total=False,
+)
+
+
+class GetCoverageStatisticsRequestRequestTypeDef(
+    _RequiredGetCoverageStatisticsRequestRequestTypeDef,
+    _OptionalGetCoverageStatisticsRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredListCoverageRequestListCoveragePaginateTypeDef = TypedDict(
+    "_RequiredListCoverageRequestListCoveragePaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListCoverageRequestListCoveragePaginateTypeDef = TypedDict(
+    "_OptionalListCoverageRequestListCoveragePaginateTypeDef",
+    {
+        "FilterCriteria": CoverageFilterCriteriaTypeDef,
+        "SortCriteria": CoverageSortCriteriaTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListCoverageRequestListCoveragePaginateTypeDef(
+    _RequiredListCoverageRequestListCoveragePaginateTypeDef,
+    _OptionalListCoverageRequestListCoveragePaginateTypeDef,
+):
+    pass
+
+
+_RequiredListCoverageRequestRequestTypeDef = TypedDict(
+    "_RequiredListCoverageRequestRequestTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListCoverageRequestRequestTypeDef = TypedDict(
+    "_OptionalListCoverageRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+        "FilterCriteria": CoverageFilterCriteriaTypeDef,
+        "SortCriteria": CoverageSortCriteriaTypeDef,
+    },
+    total=False,
+)
+
+
+class ListCoverageRequestRequestTypeDef(
+    _RequiredListCoverageRequestRequestTypeDef, _OptionalListCoverageRequestRequestTypeDef
+):
+    pass
+
+
 AccountFreeTrialInfoTypeDef = TypedDict(
     "AccountFreeTrialInfoTypeDef",
     {
         "AccountId": str,
         "DataSources": DataSourcesFreeTrialTypeDef,
+        "Features": List[FreeTrialFeatureConfigurationResultTypeDef],
     },
     total=False,
 )
 
 _RequiredDataSourceConfigurationsResultTypeDef = TypedDict(
     "_RequiredDataSourceConfigurationsResultTypeDef",
     {
@@ -2696,15 +3211,15 @@
     },
 )
 _OptionalDescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef = TypedDict(
     "_OptionalDescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef",
     {
         "FilterCriteria": FilterCriteriaTypeDef,
         "SortCriteria": SortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef(
     _RequiredDescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef,
@@ -2758,27 +3273,37 @@
     {
         "KubernetesUserDetails": KubernetesUserDetailsTypeDef,
         "KubernetesWorkloadDetails": KubernetesWorkloadDetailsTypeDef,
     },
     total=False,
 )
 
+RuntimeDetailsTypeDef = TypedDict(
+    "RuntimeDetailsTypeDef",
+    {
+        "Process": ProcessDetailsTypeDef,
+        "Context": RuntimeContextTypeDef,
+    },
+    total=False,
+)
+
 _RequiredCreateDetectorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDetectorRequestRequestTypeDef",
     {
         "Enable": bool,
     },
 )
 _OptionalCreateDetectorRequestRequestTypeDef = TypedDict(
     "_OptionalCreateDetectorRequestRequestTypeDef",
     {
         "ClientToken": str,
         "FindingPublishingFrequency": FindingPublishingFrequencyType,
         "DataSources": DataSourceConfigurationsTypeDef,
         "Tags": Mapping[str, str],
+        "Features": Sequence[DetectorFeatureConfigurationTypeDef],
     },
     total=False,
 )
 
 
 class CreateDetectorRequestRequestTypeDef(
     _RequiredCreateDetectorRequestRequestTypeDef, _OptionalCreateDetectorRequestRequestTypeDef
@@ -2794,14 +3319,15 @@
 )
 _OptionalUpdateDetectorRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateDetectorRequestRequestTypeDef",
     {
         "Enable": bool,
         "FindingPublishingFrequency": FindingPublishingFrequencyType,
         "DataSources": DataSourceConfigurationsTypeDef,
+        "Features": Sequence[DetectorFeatureConfigurationTypeDef],
     },
     total=False,
 )
 
 
 class UpdateDetectorRequestRequestTypeDef(
     _RequiredUpdateDetectorRequestRequestTypeDef, _OptionalUpdateDetectorRequestRequestTypeDef
@@ -2816,14 +3342,15 @@
         "AccountIds": Sequence[str],
     },
 )
 _OptionalUpdateMemberDetectorsRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateMemberDetectorsRequestRequestTypeDef",
     {
         "DataSources": DataSourceConfigurationsTypeDef,
+        "Features": Sequence[MemberFeaturesConfigurationTypeDef],
     },
     total=False,
 )
 
 
 class UpdateMemberDetectorsRequestRequestTypeDef(
     _RequiredUpdateMemberDetectorsRequestRequestTypeDef,
@@ -2875,15 +3402,15 @@
 )
 
 GetMalwareScanSettingsResponseTypeDef = TypedDict(
     "GetMalwareScanSettingsResponseTypeDef",
     {
         "ScanResourceCriteria": ScanResourceCriteriaTypeDef,
         "EbsSnapshotPreservation": EbsSnapshotPreservationType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateMalwareScanSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateMalwareScanSettingsRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -2918,15 +3445,24 @@
 )
 
 GetUsageStatisticsResponseTypeDef = TypedDict(
     "GetUsageStatisticsResponseTypeDef",
     {
         "UsageStatistics": UsageStatisticsTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCoverageResponseTypeDef = TypedDict(
+    "ListCoverageResponseTypeDef",
+    {
+        "Resources": List[CoverageResourceTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 S3BucketDetailTypeDef = TypedDict(
     "S3BucketDetailTypeDef",
     {
         "Arn": str,
@@ -2942,70 +3478,90 @@
 )
 
 GetRemainingFreeTrialDaysResponseTypeDef = TypedDict(
     "GetRemainingFreeTrialDaysResponseTypeDef",
     {
         "Accounts": List[AccountFreeTrialInfoTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDetectorResponseTypeDef = TypedDict(
     "GetDetectorResponseTypeDef",
     {
         "CreatedAt": str,
         "FindingPublishingFrequency": FindingPublishingFrequencyType,
         "ServiceRole": str,
         "Status": DetectorStatusType,
         "UpdatedAt": str,
         "DataSources": DataSourceConfigurationsResultTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Features": List[DetectorFeatureConfigurationResultTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-MemberDataSourceConfigurationTypeDef = TypedDict(
-    "MemberDataSourceConfigurationTypeDef",
+_RequiredMemberDataSourceConfigurationTypeDef = TypedDict(
+    "_RequiredMemberDataSourceConfigurationTypeDef",
     {
         "AccountId": str,
+    },
+)
+_OptionalMemberDataSourceConfigurationTypeDef = TypedDict(
+    "_OptionalMemberDataSourceConfigurationTypeDef",
+    {
         "DataSources": DataSourceConfigurationsResultTypeDef,
+        "Features": List[MemberFeaturesConfigurationResultTypeDef],
     },
+    total=False,
 )
 
+
+class MemberDataSourceConfigurationTypeDef(
+    _RequiredMemberDataSourceConfigurationTypeDef, _OptionalMemberDataSourceConfigurationTypeDef
+):
+    pass
+
+
 CreateDetectorResponseTypeDef = TypedDict(
     "CreateDetectorResponseTypeDef",
     {
         "DetectorId": str,
         "UnprocessedDataSources": UnprocessedDataSourcesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
     "DescribeOrganizationConfigurationResponseTypeDef",
     {
         "AutoEnable": bool,
         "MemberAccountLimitReached": bool,
         "DataSources": OrganizationDataSourceConfigurationsResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Features": List[OrganizationFeatureConfigurationResultTypeDef],
+        "NextToken": str,
+        "AutoEnableOrganizationMembers": AutoEnableMembersType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
         "DetectorId": str,
-        "AutoEnable": bool,
     },
 )
 _OptionalUpdateOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
+        "AutoEnable": bool,
         "DataSources": OrganizationDataSourceConfigurationsTypeDef,
+        "Features": Sequence[OrganizationFeatureConfigurationTypeDef],
+        "AutoEnableOrganizationMembers": AutoEnableMembersType,
     },
     total=False,
 )
 
 
 class UpdateOrganizationConfigurationRequestRequestTypeDef(
     _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef,
@@ -3019,27 +3575,29 @@
     {
         "ActionType": str,
         "AwsApiCallAction": AwsApiCallActionTypeDef,
         "DnsRequestAction": DnsRequestActionTypeDef,
         "NetworkConnectionAction": NetworkConnectionActionTypeDef,
         "PortProbeAction": PortProbeActionTypeDef,
         "KubernetesApiCallAction": KubernetesApiCallActionTypeDef,
+        "RdsLoginAttemptAction": RdsLoginAttemptActionTypeDef,
     },
     total=False,
 )
 
 EbsVolumeScanDetailsTypeDef = TypedDict(
     "EbsVolumeScanDetailsTypeDef",
     {
         "ScanId": str,
         "ScanStartedAt": datetime,
         "ScanCompletedAt": datetime,
         "TriggerFindingId": str,
         "Sources": List[str],
         "ScanDetections": ScanDetectionsTypeDef,
+        "ScanType": ScanTypeType,
     },
     total=False,
 )
 
 ResourceTypeDef = TypedDict(
     "ResourceTypeDef",
     {
@@ -3048,24 +3606,27 @@
         "InstanceDetails": InstanceDetailsTypeDef,
         "EksClusterDetails": EksClusterDetailsTypeDef,
         "KubernetesDetails": KubernetesDetailsTypeDef,
         "ResourceType": str,
         "EbsVolumeDetails": EbsVolumeDetailsTypeDef,
         "EcsClusterDetails": EcsClusterDetailsTypeDef,
         "ContainerDetails": ContainerTypeDef,
+        "RdsDbInstanceDetails": RdsDbInstanceDetailsTypeDef,
+        "RdsDbUserDetails": RdsDbUserDetailsTypeDef,
+        "LambdaDetails": LambdaDetailsTypeDef,
     },
     total=False,
 )
 
 GetMemberDetectorsResponseTypeDef = TypedDict(
     "GetMemberDetectorsResponseTypeDef",
     {
         "MemberDataSourceConfigurations": List[MemberDataSourceConfigurationTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceTypeDef = TypedDict(
     "ServiceTypeDef",
     {
         "Action": ActionTypeDef,
@@ -3077,14 +3638,15 @@
         "EventLastSeen": str,
         "ResourceRole": str,
         "ServiceName": str,
         "UserFeedback": str,
         "AdditionalInfo": ServiceAdditionalInfoTypeDef,
         "FeatureName": str,
         "EbsVolumeScanDetails": EbsVolumeScanDetailsTypeDef,
+        "RuntimeDetails": RuntimeDetailsTypeDef,
     },
     total=False,
 )
 
 _RequiredFindingTypeDef = TypedDict(
     "_RequiredFindingTypeDef",
     {
@@ -3117,10 +3679,10 @@
     pass
 
 
 GetFindingsResponseTypeDef = TypedDict(
     "GetFindingsResponseTypeDef",
     {
         "Findings": List[FindingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty/type_defs.pyi` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty/type_defs.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -13,30 +13,43 @@
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence
 
 from .literals import (
     AdminStatusType,
+    AutoEnableMembersType,
+    CoverageFilterCriterionKeyType,
+    CoverageSortKeyType,
+    CoverageStatisticsTypeType,
+    CoverageStatusType,
     CriterionKeyType,
     DataSourceStatusType,
     DataSourceType,
+    DetectorFeatureResultType,
+    DetectorFeatureType,
     DetectorStatusType,
     EbsSnapshotPreservationType,
+    FeatureStatusType,
     FeedbackType,
     FilterActionType,
     FindingPublishingFrequencyType,
+    FreeTrialFeatureResultType,
     IpSetFormatType,
     IpSetStatusType,
     OrderByType,
+    OrgFeatureStatusType,
+    OrgFeatureType,
     PublishingStatusType,
     ScanResultType,
     ScanStatusType,
+    ScanTypeType,
     ThreatIntelSetFormatType,
     ThreatIntelSetStatusType,
+    UsageFeatureType,
     UsageStatisticTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -47,53 +60,62 @@
 
 __all__ = (
     "AcceptAdministratorInvitationRequestRequestTypeDef",
     "AcceptInvitationRequestRequestTypeDef",
     "AccessControlListTypeDef",
     "AccessKeyDetailsTypeDef",
     "AccountDetailTypeDef",
+    "FreeTrialFeatureConfigurationResultTypeDef",
     "BlockPublicAccessTypeDef",
     "DnsRequestActionTypeDef",
+    "AddonDetailsTypeDef",
     "AdminAccountTypeDef",
     "AdministratorTypeDef",
     "ArchiveFindingsRequestRequestTypeDef",
     "DomainDetailsTypeDef",
     "RemoteAccountDetailsTypeDef",
     "BucketPolicyTypeDef",
     "CityTypeDef",
     "CloudTrailConfigurationResultTypeDef",
     "ConditionTypeDef",
     "SecurityContextTypeDef",
     "VolumeMountTypeDef",
     "CountryTypeDef",
-    "ResponseMetadataTypeDef",
+    "CoverageFilterConditionTypeDef",
+    "CoverageSortCriteriaTypeDef",
+    "CoverageStatisticsTypeDef",
+    "CreateFilterResponseTypeDef",
     "CreateIPSetRequestRequestTypeDef",
+    "CreateIPSetResponseTypeDef",
     "UnprocessedAccountTypeDef",
     "DestinationPropertiesTypeDef",
+    "CreatePublishingDestinationResponseTypeDef",
     "CreateSampleFindingsRequestRequestTypeDef",
     "CreateThreatIntelSetRequestRequestTypeDef",
+    "CreateThreatIntelSetResponseTypeDef",
     "DNSLogsConfigurationResultTypeDef",
     "FlowLogsConfigurationResultTypeDef",
     "S3LogsConfigurationResultTypeDef",
     "S3LogsConfigurationTypeDef",
     "DataSourceFreeTrialTypeDef",
     "DeclineInvitationsRequestRequestTypeDef",
     "DefaultServerSideEncryptionTypeDef",
     "DeleteDetectorRequestRequestTypeDef",
     "DeleteFilterRequestRequestTypeDef",
     "DeleteIPSetRequestRequestTypeDef",
     "DeleteInvitationsRequestRequestTypeDef",
     "DeleteMembersRequestRequestTypeDef",
     "DeletePublishingDestinationRequestRequestTypeDef",
     "DeleteThreatIntelSetRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
     "SortCriteriaTypeDef",
     "DescribeOrganizationConfigurationRequestRequestTypeDef",
     "DescribePublishingDestinationRequestRequestTypeDef",
     "DestinationTypeDef",
+    "DetectorAdditionalConfigurationResultTypeDef",
+    "DetectorAdditionalConfigurationTypeDef",
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     "DisassociateFromAdministratorAccountRequestRequestTypeDef",
     "DisassociateFromMasterAccountRequestRequestTypeDef",
     "DisassociateMembersRequestRequestTypeDef",
     "VolumeDetailTypeDef",
     "EbsVolumesResultTypeDef",
     "TagTypeDef",
@@ -102,185 +124,216 @@
     "FilterConditionTypeDef",
     "FindingStatisticsTypeDef",
     "GeoLocationTypeDef",
     "GetAdministratorAccountRequestRequestTypeDef",
     "GetDetectorRequestRequestTypeDef",
     "GetFilterRequestRequestTypeDef",
     "GetIPSetRequestRequestTypeDef",
+    "GetIPSetResponseTypeDef",
+    "GetInvitationsCountResponseTypeDef",
     "GetMalwareScanSettingsRequestRequestTypeDef",
     "GetMasterAccountRequestRequestTypeDef",
     "MasterTypeDef",
     "GetMemberDetectorsRequestRequestTypeDef",
     "GetMembersRequestRequestTypeDef",
     "MemberTypeDef",
     "GetRemainingFreeTrialDaysRequestRequestTypeDef",
     "GetThreatIntelSetRequestRequestTypeDef",
+    "GetThreatIntelSetResponseTypeDef",
     "UsageCriteriaTypeDef",
     "HighestSeverityThreatDetailsTypeDef",
     "HostPathTypeDef",
     "IamInstanceProfileTypeDef",
     "ProductCodeTypeDef",
     "InvitationTypeDef",
     "InviteMembersRequestRequestTypeDef",
     "KubernetesAuditLogsConfigurationResultTypeDef",
     "KubernetesAuditLogsConfigurationTypeDef",
     "KubernetesUserDetailsTypeDef",
+    "LineageObjectTypeDef",
+    "ListDetectorsRequestListDetectorsPaginateTypeDef",
     "ListDetectorsRequestRequestTypeDef",
+    "ListDetectorsResponseTypeDef",
+    "ListFiltersRequestListFiltersPaginateTypeDef",
     "ListFiltersRequestRequestTypeDef",
+    "ListFiltersResponseTypeDef",
+    "ListFindingsResponseTypeDef",
+    "ListIPSetsRequestListIPSetsPaginateTypeDef",
     "ListIPSetsRequestRequestTypeDef",
+    "ListIPSetsResponseTypeDef",
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
     "ListInvitationsRequestRequestTypeDef",
+    "ListMembersRequestListMembersPaginateTypeDef",
     "ListMembersRequestRequestTypeDef",
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
     "ListPublishingDestinationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
     "ListThreatIntelSetsRequestRequestTypeDef",
+    "ListThreatIntelSetsResponseTypeDef",
     "LocalIpDetailsTypeDef",
     "LocalPortDetailsTypeDef",
+    "LoginAttributeTypeDef",
     "ScanEc2InstanceWithFindingsTypeDef",
+    "MemberAdditionalConfigurationResultTypeDef",
+    "MemberAdditionalConfigurationTypeDef",
     "RemotePortDetailsTypeDef",
     "PrivateIpAddressDetailsTypeDef",
     "SecurityGroupTypeDef",
+    "OrganizationAdditionalConfigurationResultTypeDef",
+    "OrganizationAdditionalConfigurationTypeDef",
     "OrganizationS3LogsConfigurationResultTypeDef",
     "OrganizationS3LogsConfigurationTypeDef",
     "OrganizationEbsVolumesResultTypeDef",
     "OrganizationEbsVolumesTypeDef",
     "OrganizationKubernetesAuditLogsConfigurationResultTypeDef",
     "OrganizationKubernetesAuditLogsConfigurationTypeDef",
     "OrganizationTypeDef",
     "OwnerTypeDef",
+    "PaginatorConfigTypeDef",
+    "RdsDbUserDetailsTypeDef",
     "ResourceDetailsTypeDef",
+    "ResponseMetadataTypeDef",
     "ScanConditionPairTypeDef",
     "ScannedItemCountTypeDef",
     "ThreatsDetectedItemCountTypeDef",
     "ScanFilePathTypeDef",
     "ScanResultDetailsTypeDef",
     "TriggerDetailsTypeDef",
     "ServiceAdditionalInfoTypeDef",
+    "StartMalwareScanRequestRequestTypeDef",
+    "StartMalwareScanResponseTypeDef",
     "StartMonitoringMembersRequestRequestTypeDef",
     "StopMonitoringMembersRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "TotalTypeDef",
     "UnarchiveFindingsRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateFilterResponseTypeDef",
     "UpdateFindingsFeedbackRequestRequestTypeDef",
     "UpdateIPSetRequestRequestTypeDef",
     "UpdateThreatIntelSetRequestRequestTypeDef",
     "CreateMembersRequestRequestTypeDef",
     "AccountLevelPermissionsTypeDef",
+    "CoverageEksClusterDetailsTypeDef",
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    "GetAdministratorAccountResponseTypeDef",
     "BucketLevelPermissionsTypeDef",
     "FindingCriteriaTypeDef",
     "ContainerTypeDef",
-    "CreateFilterResponseTypeDef",
-    "CreateIPSetResponseTypeDef",
-    "CreatePublishingDestinationResponseTypeDef",
-    "CreateThreatIntelSetResponseTypeDef",
-    "GetAdministratorAccountResponseTypeDef",
-    "GetIPSetResponseTypeDef",
-    "GetInvitationsCountResponseTypeDef",
-    "GetThreatIntelSetResponseTypeDef",
-    "ListDetectorsResponseTypeDef",
-    "ListFiltersResponseTypeDef",
-    "ListFindingsResponseTypeDef",
-    "ListIPSetsResponseTypeDef",
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListThreatIntelSetsResponseTypeDef",
-    "UpdateFilterResponseTypeDef",
+    "CoverageFilterCriterionTypeDef",
+    "GetCoverageStatisticsResponseTypeDef",
     "CreateMembersResponseTypeDef",
     "DeclineInvitationsResponseTypeDef",
     "DeleteInvitationsResponseTypeDef",
     "DeleteMembersResponseTypeDef",
     "DisassociateMembersResponseTypeDef",
     "InviteMembersResponseTypeDef",
     "StartMonitoringMembersResponseTypeDef",
     "StopMonitoringMembersResponseTypeDef",
     "UpdateMemberDetectorsResponseTypeDef",
     "CreatePublishingDestinationRequestRequestTypeDef",
     "DescribePublishingDestinationResponseTypeDef",
     "UpdatePublishingDestinationRequestRequestTypeDef",
     "KubernetesDataSourceFreeTrialTypeDef",
     "MalwareProtectionDataSourceFreeTrialTypeDef",
-    "ListDetectorsRequestListDetectorsPaginateTypeDef",
-    "ListFiltersRequestListFiltersPaginateTypeDef",
-    "ListIPSetsRequestListIPSetsPaginateTypeDef",
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    "ListMembersRequestListMembersPaginateTypeDef",
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    "ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
     "GetFindingsRequestRequestTypeDef",
     "ListPublishingDestinationsResponseTypeDef",
+    "DetectorFeatureConfigurationResultTypeDef",
+    "DetectorFeatureConfigurationTypeDef",
     "EbsVolumeDetailsTypeDef",
     "ScanEc2InstanceWithFindingsResultTypeDef",
     "EksClusterDetailsTypeDef",
+    "RdsDbInstanceDetailsTypeDef",
     "EvidenceTypeDef",
     "FilterCriterionTypeDef",
     "GetFindingsStatisticsResponseTypeDef",
     "GetMasterAccountResponseTypeDef",
     "GetMembersResponseTypeDef",
     "ListMembersResponseTypeDef",
     "GetUsageStatisticsRequestRequestTypeDef",
     "VolumeTypeDef",
     "ListInvitationsResponseTypeDef",
     "KubernetesConfigurationResultTypeDef",
     "KubernetesConfigurationTypeDef",
+    "ProcessDetailsTypeDef",
     "MalwareProtectionConfigurationTypeDef",
+    "MemberFeaturesConfigurationResultTypeDef",
+    "MemberFeaturesConfigurationTypeDef",
     "NetworkInterfaceTypeDef",
+    "VpcConfigTypeDef",
+    "OrganizationFeatureConfigurationResultTypeDef",
+    "OrganizationFeatureConfigurationTypeDef",
     "OrganizationScanEc2InstanceWithFindingsResultTypeDef",
     "OrganizationScanEc2InstanceWithFindingsTypeDef",
     "OrganizationKubernetesConfigurationResultTypeDef",
     "OrganizationKubernetesConfigurationTypeDef",
     "RemoteIpDetailsTypeDef",
     "ScanConditionTypeDef",
     "ScanThreatNameTypeDef",
     "ScanTypeDef",
     "UsageAccountResultTypeDef",
     "UsageDataSourceResultTypeDef",
+    "UsageFeatureResultTypeDef",
     "UsageResourceResultTypeDef",
+    "CoverageResourceDetailsTypeDef",
     "PermissionConfigurationTypeDef",
     "CreateFilterRequestRequestTypeDef",
     "GetFilterResponseTypeDef",
     "GetFindingsStatisticsRequestRequestTypeDef",
     "ListFindingsRequestListFindingsPaginateTypeDef",
     "ListFindingsRequestRequestTypeDef",
     "UpdateFilterRequestRequestTypeDef",
+    "CoverageFilterCriteriaTypeDef",
     "DataSourcesFreeTrialTypeDef",
     "MalwareProtectionConfigurationResultTypeDef",
     "FilterCriteriaTypeDef",
     "EcsTaskDetailsTypeDef",
     "KubernetesWorkloadDetailsTypeDef",
+    "RuntimeContextTypeDef",
     "DataSourceConfigurationsTypeDef",
     "InstanceDetailsTypeDef",
+    "LambdaDetailsTypeDef",
     "OrganizationMalwareProtectionConfigurationResultTypeDef",
     "OrganizationMalwareProtectionConfigurationTypeDef",
     "AwsApiCallActionTypeDef",
     "KubernetesApiCallActionTypeDef",
     "NetworkConnectionActionTypeDef",
     "PortProbeDetailTypeDef",
+    "RdsLoginAttemptActionTypeDef",
     "ScanResourceCriteriaTypeDef",
     "ThreatDetectedByNameTypeDef",
     "DescribeMalwareScansResponseTypeDef",
     "UsageStatisticsTypeDef",
+    "CoverageResourceTypeDef",
     "PublicAccessTypeDef",
+    "GetCoverageStatisticsRequestRequestTypeDef",
+    "ListCoverageRequestListCoveragePaginateTypeDef",
+    "ListCoverageRequestRequestTypeDef",
     "AccountFreeTrialInfoTypeDef",
     "DataSourceConfigurationsResultTypeDef",
     "UnprocessedDataSourcesResultTypeDef",
     "DescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef",
     "DescribeMalwareScansRequestRequestTypeDef",
     "EcsClusterDetailsTypeDef",
     "KubernetesDetailsTypeDef",
+    "RuntimeDetailsTypeDef",
     "CreateDetectorRequestRequestTypeDef",
     "UpdateDetectorRequestRequestTypeDef",
     "UpdateMemberDetectorsRequestRequestTypeDef",
     "OrganizationDataSourceConfigurationsResultTypeDef",
     "OrganizationDataSourceConfigurationsTypeDef",
     "PortProbeActionTypeDef",
     "GetMalwareScanSettingsResponseTypeDef",
     "UpdateMalwareScanSettingsRequestRequestTypeDef",
     "ScanDetectionsTypeDef",
     "GetUsageStatisticsResponseTypeDef",
+    "ListCoverageResponseTypeDef",
     "S3BucketDetailTypeDef",
     "GetRemainingFreeTrialDaysResponseTypeDef",
     "GetDetectorResponseTypeDef",
     "MemberDataSourceConfigurationTypeDef",
     "CreateDetectorResponseTypeDef",
     "DescribeOrganizationConfigurationResponseTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
@@ -335,14 +388,23 @@
     "AccountDetailTypeDef",
     {
         "AccountId": str,
         "Email": str,
     },
 )
 
+FreeTrialFeatureConfigurationResultTypeDef = TypedDict(
+    "FreeTrialFeatureConfigurationResultTypeDef",
+    {
+        "Name": FreeTrialFeatureResultType,
+        "FreeTrialDaysRemaining": int,
+    },
+    total=False,
+)
+
 BlockPublicAccessTypeDef = TypedDict(
     "BlockPublicAccessTypeDef",
     {
         "IgnorePublicAcls": bool,
         "RestrictPublicBuckets": bool,
         "BlockPublicAcls": bool,
         "BlockPublicPolicy": bool,
@@ -356,14 +418,23 @@
         "Domain": str,
         "Protocol": str,
         "Blocked": bool,
     },
     total=False,
 )
 
+AddonDetailsTypeDef = TypedDict(
+    "AddonDetailsTypeDef",
+    {
+        "AddonVersion": str,
+        "AddonStatus": str,
+    },
+    total=False,
+)
+
 AdminAccountTypeDef = TypedDict(
     "AdminAccountTypeDef",
     {
         "AdminAccountId": str,
         "AdminStatus": AdminStatusType,
     },
     total=False,
@@ -470,22 +541,46 @@
     {
         "CountryCode": str,
         "CountryName": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CoverageFilterConditionTypeDef = TypedDict(
+    "CoverageFilterConditionTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Equals": Sequence[str],
+        "NotEquals": Sequence[str],
+    },
+    total=False,
+)
+
+CoverageSortCriteriaTypeDef = TypedDict(
+    "CoverageSortCriteriaTypeDef",
+    {
+        "AttributeName": CoverageSortKeyType,
+        "OrderBy": OrderByType,
+    },
+    total=False,
+)
+
+CoverageStatisticsTypeDef = TypedDict(
+    "CoverageStatisticsTypeDef",
+    {
+        "CountByResourceType": Dict[Literal["EKS"], int],
+        "CountByCoverageStatus": Dict[CoverageStatusType, int],
+    },
+    total=False,
+)
+
+CreateFilterResponseTypeDef = TypedDict(
+    "CreateFilterResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateIPSetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateIPSetRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -505,14 +600,22 @@
 )
 
 class CreateIPSetRequestRequestTypeDef(
     _RequiredCreateIPSetRequestRequestTypeDef, _OptionalCreateIPSetRequestRequestTypeDef
 ):
     pass
 
+CreateIPSetResponseTypeDef = TypedDict(
+    "CreateIPSetResponseTypeDef",
+    {
+        "IpSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UnprocessedAccountTypeDef = TypedDict(
     "UnprocessedAccountTypeDef",
     {
         "AccountId": str,
         "Result": str,
     },
 )
@@ -522,14 +625,22 @@
     {
         "DestinationArn": str,
         "KmsKeyArn": str,
     },
     total=False,
 )
 
+CreatePublishingDestinationResponseTypeDef = TypedDict(
+    "CreatePublishingDestinationResponseTypeDef",
+    {
+        "DestinationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSampleFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSampleFindingsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalCreateSampleFindingsRequestRequestTypeDef = TypedDict(
@@ -567,14 +678,22 @@
 
 class CreateThreatIntelSetRequestRequestTypeDef(
     _RequiredCreateThreatIntelSetRequestRequestTypeDef,
     _OptionalCreateThreatIntelSetRequestRequestTypeDef,
 ):
     pass
 
+CreateThreatIntelSetResponseTypeDef = TypedDict(
+    "CreateThreatIntelSetResponseTypeDef",
+    {
+        "ThreatIntelSetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DNSLogsConfigurationResultTypeDef = TypedDict(
     "DNSLogsConfigurationResultTypeDef",
     {
         "Status": DataSourceStatusType,
     },
 )
 
@@ -673,39 +792,43 @@
     "DeleteThreatIntelSetRequestRequestTypeDef",
     {
         "DetectorId": str,
         "ThreatIntelSetId": str,
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
 SortCriteriaTypeDef = TypedDict(
     "SortCriteriaTypeDef",
     {
         "AttributeName": str,
         "OrderBy": OrderByType,
     },
     total=False,
 )
 
-DescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationRequestRequestTypeDef",
+_RequiredDescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "_RequiredDescribeOrganizationConfigurationRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
+_OptionalDescribeOrganizationConfigurationRequestRequestTypeDef = TypedDict(
+    "_OptionalDescribeOrganizationConfigurationRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+class DescribeOrganizationConfigurationRequestRequestTypeDef(
+    _RequiredDescribeOrganizationConfigurationRequestRequestTypeDef,
+    _OptionalDescribeOrganizationConfigurationRequestRequestTypeDef,
+):
+    pass
 
 DescribePublishingDestinationRequestRequestTypeDef = TypedDict(
     "DescribePublishingDestinationRequestRequestTypeDef",
     {
         "DetectorId": str,
         "DestinationId": str,
     },
@@ -716,14 +839,33 @@
     {
         "DestinationId": str,
         "DestinationType": Literal["S3"],
         "Status": PublishingStatusType,
     },
 )
 
+DetectorAdditionalConfigurationResultTypeDef = TypedDict(
+    "DetectorAdditionalConfigurationResultTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+    },
+    total=False,
+)
+
+DetectorAdditionalConfigurationTypeDef = TypedDict(
+    "DetectorAdditionalConfigurationTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+    },
+    total=False,
+)
+
 DisableOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     {
         "AdminAccountId": str,
     },
 )
 
@@ -850,14 +992,34 @@
     "GetIPSetRequestRequestTypeDef",
     {
         "DetectorId": str,
         "IpSetId": str,
     },
 )
 
+GetIPSetResponseTypeDef = TypedDict(
+    "GetIPSetResponseTypeDef",
+    {
+        "Name": str,
+        "Format": IpSetFormatType,
+        "Location": str,
+        "Status": IpSetStatusType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetInvitationsCountResponseTypeDef = TypedDict(
+    "GetInvitationsCountResponseTypeDef",
+    {
+        "InvitationsCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMalwareScanSettingsRequestRequestTypeDef = TypedDict(
     "GetMalwareScanSettingsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 
@@ -942,32 +1104,37 @@
     "GetThreatIntelSetRequestRequestTypeDef",
     {
         "DetectorId": str,
         "ThreatIntelSetId": str,
     },
 )
 
-_RequiredUsageCriteriaTypeDef = TypedDict(
-    "_RequiredUsageCriteriaTypeDef",
+GetThreatIntelSetResponseTypeDef = TypedDict(
+    "GetThreatIntelSetResponseTypeDef",
     {
-        "DataSources": Sequence[DataSourceType],
+        "Name": str,
+        "Format": ThreatIntelSetFormatType,
+        "Location": str,
+        "Status": ThreatIntelSetStatusType,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalUsageCriteriaTypeDef = TypedDict(
-    "_OptionalUsageCriteriaTypeDef",
+
+UsageCriteriaTypeDef = TypedDict(
+    "UsageCriteriaTypeDef",
     {
         "AccountIds": Sequence[str],
+        "DataSources": Sequence[DataSourceType],
         "Resources": Sequence[str],
+        "Features": Sequence[UsageFeatureType],
     },
     total=False,
 )
 
-class UsageCriteriaTypeDef(_RequiredUsageCriteriaTypeDef, _OptionalUsageCriteriaTypeDef):
-    pass
-
 HighestSeverityThreatDetailsTypeDef = TypedDict(
     "HighestSeverityThreatDetailsTypeDef",
     {
         "Severity": str,
         "ThreatName": str,
         "Count": int,
     },
@@ -1048,27 +1215,81 @@
 
 KubernetesUserDetailsTypeDef = TypedDict(
     "KubernetesUserDetailsTypeDef",
     {
         "Username": str,
         "Uid": str,
         "Groups": List[str],
+        "SessionName": List[str],
+    },
+    total=False,
+)
+
+LineageObjectTypeDef = TypedDict(
+    "LineageObjectTypeDef",
+    {
+        "StartTime": datetime,
+        "NamespacePid": int,
+        "UserId": int,
+        "Name": str,
+        "Pid": int,
+        "Uuid": str,
+        "ExecutablePath": str,
+        "Euid": int,
+        "ParentUuid": str,
+    },
+    total=False,
+)
+
+ListDetectorsRequestListDetectorsPaginateTypeDef = TypedDict(
+    "ListDetectorsRequestListDetectorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDetectorsRequestRequestTypeDef = TypedDict(
     "ListDetectorsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListDetectorsResponseTypeDef = TypedDict(
+    "ListDetectorsResponseTypeDef",
+    {
+        "DetectorIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
+    "_RequiredListFiltersRequestListFiltersPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
+    "_OptionalListFiltersRequestListFiltersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFiltersRequestListFiltersPaginateTypeDef(
+    _RequiredListFiltersRequestListFiltersPaginateTypeDef,
+    _OptionalListFiltersRequestListFiltersPaginateTypeDef,
+):
+    pass
+
 _RequiredListFiltersRequestRequestTypeDef = TypedDict(
     "_RequiredListFiltersRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListFiltersRequestRequestTypeDef = TypedDict(
@@ -1081,14 +1302,52 @@
 )
 
 class ListFiltersRequestRequestTypeDef(
     _RequiredListFiltersRequestRequestTypeDef, _OptionalListFiltersRequestRequestTypeDef
 ):
     pass
 
+ListFiltersResponseTypeDef = TypedDict(
+    "ListFiltersResponseTypeDef",
+    {
+        "FilterNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFindingsResponseTypeDef = TypedDict(
+    "ListFindingsResponseTypeDef",
+    {
+        "FindingIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
+    "_RequiredListIPSetsRequestListIPSetsPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
+    "_OptionalListIPSetsRequestListIPSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListIPSetsRequestListIPSetsPaginateTypeDef(
+    _RequiredListIPSetsRequestListIPSetsPaginateTypeDef,
+    _OptionalListIPSetsRequestListIPSetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListIPSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListIPSetsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListIPSetsRequestRequestTypeDef = TypedDict(
@@ -1101,23 +1360,61 @@
 )
 
 class ListIPSetsRequestRequestTypeDef(
     _RequiredListIPSetsRequestRequestTypeDef, _OptionalListIPSetsRequestRequestTypeDef
 ):
     pass
 
+ListIPSetsResponseTypeDef = TypedDict(
+    "ListIPSetsResponseTypeDef",
+    {
+        "IpSetIds": List[str],
+        "NextToken": str,
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "_RequiredListMembersRequestListMembersPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "_OptionalListMembersRequestListMembersPaginateTypeDef",
+    {
+        "OnlyAssociated": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMembersRequestListMembersPaginateTypeDef(
+    _RequiredListMembersRequestListMembersPaginateTypeDef,
+    _OptionalListMembersRequestListMembersPaginateTypeDef,
+):
+    pass
+
 _RequiredListMembersRequestRequestTypeDef = TypedDict(
     "_RequiredListMembersRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListMembersRequestRequestTypeDef = TypedDict(
@@ -1131,14 +1428,22 @@
 )
 
 class ListMembersRequestRequestTypeDef(
     _RequiredListMembersRequestRequestTypeDef, _OptionalListMembersRequestRequestTypeDef
 ):
     pass
 
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -1168,14 +1473,42 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
+    "_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
+    "_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef(
+    _RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
+    _OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListThreatIntelSetsRequestRequestTypeDef = TypedDict(
     "_RequiredListThreatIntelSetsRequestRequestTypeDef",
     {
         "DetectorId": str,
     },
 )
 _OptionalListThreatIntelSetsRequestRequestTypeDef = TypedDict(
@@ -1189,14 +1522,23 @@
 
 class ListThreatIntelSetsRequestRequestTypeDef(
     _RequiredListThreatIntelSetsRequestRequestTypeDef,
     _OptionalListThreatIntelSetsRequestRequestTypeDef,
 ):
     pass
 
+ListThreatIntelSetsResponseTypeDef = TypedDict(
+    "ListThreatIntelSetsResponseTypeDef",
+    {
+        "ThreatIntelSetIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LocalIpDetailsTypeDef = TypedDict(
     "LocalIpDetailsTypeDef",
     {
         "IpAddressV4": str,
     },
     total=False,
 )
@@ -1206,22 +1548,52 @@
     {
         "Port": int,
         "PortName": str,
     },
     total=False,
 )
 
+LoginAttributeTypeDef = TypedDict(
+    "LoginAttributeTypeDef",
+    {
+        "User": str,
+        "Application": str,
+        "FailedLoginAttempts": int,
+        "SuccessfulLoginAttempts": int,
+    },
+    total=False,
+)
+
 ScanEc2InstanceWithFindingsTypeDef = TypedDict(
     "ScanEc2InstanceWithFindingsTypeDef",
     {
         "EbsVolumes": bool,
     },
     total=False,
 )
 
+MemberAdditionalConfigurationResultTypeDef = TypedDict(
+    "MemberAdditionalConfigurationResultTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+    },
+    total=False,
+)
+
+MemberAdditionalConfigurationTypeDef = TypedDict(
+    "MemberAdditionalConfigurationTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "Status": FeatureStatusType,
+    },
+    total=False,
+)
+
 RemotePortDetailsTypeDef = TypedDict(
     "RemotePortDetailsTypeDef",
     {
         "Port": int,
         "PortName": str,
     },
     total=False,
@@ -1241,14 +1613,32 @@
     {
         "GroupId": str,
         "GroupName": str,
     },
     total=False,
 )
 
+OrganizationAdditionalConfigurationResultTypeDef = TypedDict(
+    "OrganizationAdditionalConfigurationResultTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "AutoEnable": OrgFeatureStatusType,
+    },
+    total=False,
+)
+
+OrganizationAdditionalConfigurationTypeDef = TypedDict(
+    "OrganizationAdditionalConfigurationTypeDef",
+    {
+        "Name": Literal["EKS_ADDON_MANAGEMENT"],
+        "AutoEnable": OrgFeatureStatusType,
+    },
+    total=False,
+)
+
 OrganizationS3LogsConfigurationResultTypeDef = TypedDict(
     "OrganizationS3LogsConfigurationResultTypeDef",
     {
         "AutoEnable": bool,
     },
 )
 
@@ -1304,22 +1694,55 @@
     "OwnerTypeDef",
     {
         "Id": str,
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
+RdsDbUserDetailsTypeDef = TypedDict(
+    "RdsDbUserDetailsTypeDef",
+    {
+        "User": str,
+        "Application": str,
+        "Database": str,
+        "Ssl": str,
+        "AuthMethod": str,
+    },
+    total=False,
+)
+
 ResourceDetailsTypeDef = TypedDict(
     "ResourceDetailsTypeDef",
     {
         "InstanceArn": str,
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
 _RequiredScanConditionPairTypeDef = TypedDict(
     "_RequiredScanConditionPairTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalScanConditionPairTypeDef = TypedDict(
@@ -1386,14 +1809,29 @@
     {
         "Value": str,
         "Type": str,
     },
     total=False,
 )
 
+StartMalwareScanRequestRequestTypeDef = TypedDict(
+    "StartMalwareScanRequestRequestTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+
+StartMalwareScanResponseTypeDef = TypedDict(
+    "StartMalwareScanResponseTypeDef",
+    {
+        "ScanId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMonitoringMembersRequestRequestTypeDef = TypedDict(
     "StartMonitoringMembersRequestRequestTypeDef",
     {
         "DetectorId": str,
         "AccountIds": Sequence[str],
     },
 )
@@ -1435,14 +1873,22 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateFilterResponseTypeDef = TypedDict(
+    "UpdateFilterResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFindingsFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFindingsFeedbackRequestRequestTypeDef",
     {
         "DetectorId": str,
         "FindingIds": Sequence[str],
         "Feedback": FeedbackType,
     },
@@ -1518,14 +1964,42 @@
     "AccountLevelPermissionsTypeDef",
     {
         "BlockPublicAccess": BlockPublicAccessTypeDef,
     },
     total=False,
 )
 
+CoverageEksClusterDetailsTypeDef = TypedDict(
+    "CoverageEksClusterDetailsTypeDef",
+    {
+        "ClusterName": str,
+        "CoveredNodes": int,
+        "CompatibleNodes": int,
+        "AddonDetails": AddonDetailsTypeDef,
+    },
+    total=False,
+)
+
+ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    {
+        "AdminAccounts": List[AdminAccountTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetAdministratorAccountResponseTypeDef = TypedDict(
+    "GetAdministratorAccountResponseTypeDef",
+    {
+        "Administrator": AdministratorTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BucketLevelPermissionsTypeDef = TypedDict(
     "BucketLevelPermissionsTypeDef",
     {
         "AccessControlList": AccessControlListTypeDef,
         "BucketPolicy": BucketPolicyTypeDef,
         "BlockPublicAccess": BlockPublicAccessTypeDef,
     },
@@ -1550,225 +2024,100 @@
         "ImagePrefix": str,
         "VolumeMounts": List[VolumeMountTypeDef],
         "SecurityContext": SecurityContextTypeDef,
     },
     total=False,
 )
 
-CreateFilterResponseTypeDef = TypedDict(
-    "CreateFilterResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIPSetResponseTypeDef = TypedDict(
-    "CreateIPSetResponseTypeDef",
-    {
-        "IpSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePublishingDestinationResponseTypeDef = TypedDict(
-    "CreatePublishingDestinationResponseTypeDef",
-    {
-        "DestinationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateThreatIntelSetResponseTypeDef = TypedDict(
-    "CreateThreatIntelSetResponseTypeDef",
-    {
-        "ThreatIntelSetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAdministratorAccountResponseTypeDef = TypedDict(
-    "GetAdministratorAccountResponseTypeDef",
-    {
-        "Administrator": AdministratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetIPSetResponseTypeDef = TypedDict(
-    "GetIPSetResponseTypeDef",
-    {
-        "Name": str,
-        "Format": IpSetFormatType,
-        "Location": str,
-        "Status": IpSetStatusType,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetInvitationsCountResponseTypeDef = TypedDict(
-    "GetInvitationsCountResponseTypeDef",
-    {
-        "InvitationsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetThreatIntelSetResponseTypeDef = TypedDict(
-    "GetThreatIntelSetResponseTypeDef",
-    {
-        "Name": str,
-        "Format": ThreatIntelSetFormatType,
-        "Location": str,
-        "Status": ThreatIntelSetStatusType,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDetectorsResponseTypeDef = TypedDict(
-    "ListDetectorsResponseTypeDef",
-    {
-        "DetectorIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFiltersResponseTypeDef = TypedDict(
-    "ListFiltersResponseTypeDef",
-    {
-        "FilterNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFindingsResponseTypeDef = TypedDict(
-    "ListFindingsResponseTypeDef",
+CoverageFilterCriterionTypeDef = TypedDict(
+    "CoverageFilterCriterionTypeDef",
     {
-        "FindingIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListIPSetsResponseTypeDef = TypedDict(
-    "ListIPSetsResponseTypeDef",
-    {
-        "IpSetIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    {
-        "AdminAccounts": List[AdminAccountTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListThreatIntelSetsResponseTypeDef = TypedDict(
-    "ListThreatIntelSetsResponseTypeDef",
-    {
-        "ThreatIntelSetIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CriterionKey": CoverageFilterCriterionKeyType,
+        "FilterCondition": CoverageFilterConditionTypeDef,
     },
+    total=False,
 )
 
-UpdateFilterResponseTypeDef = TypedDict(
-    "UpdateFilterResponseTypeDef",
+GetCoverageStatisticsResponseTypeDef = TypedDict(
+    "GetCoverageStatisticsResponseTypeDef",
     {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CoverageStatistics": CoverageStatisticsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMembersResponseTypeDef = TypedDict(
     "CreateMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineInvitationsResponseTypeDef = TypedDict(
     "DeclineInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInvitationsResponseTypeDef = TypedDict(
     "DeleteInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMembersResponseTypeDef = TypedDict(
     "DeleteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateMembersResponseTypeDef = TypedDict(
     "DisassociateMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteMembersResponseTypeDef = TypedDict(
     "InviteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMonitoringMembersResponseTypeDef = TypedDict(
     "StartMonitoringMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopMonitoringMembersResponseTypeDef = TypedDict(
     "StopMonitoringMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMemberDetectorsResponseTypeDef = TypedDict(
     "UpdateMemberDetectorsResponseTypeDef",
     {
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreatePublishingDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePublishingDestinationRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -1794,15 +2143,15 @@
     "DescribePublishingDestinationResponseTypeDef",
     {
         "DestinationId": str,
         "DestinationType": Literal["S3"],
         "Status": PublishingStatusType,
         "PublishingFailureStartTimestamp": int,
         "DestinationProperties": DestinationPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdatePublishingDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePublishingDestinationRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -1835,119 +2184,14 @@
     "MalwareProtectionDataSourceFreeTrialTypeDef",
     {
         "ScanEc2InstanceWithFindings": DataSourceFreeTrialTypeDef,
     },
     total=False,
 )
 
-ListDetectorsRequestListDetectorsPaginateTypeDef = TypedDict(
-    "ListDetectorsRequestListDetectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
-    "_RequiredListFiltersRequestListFiltersPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
-    "_OptionalListFiltersRequestListFiltersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFiltersRequestListFiltersPaginateTypeDef(
-    _RequiredListFiltersRequestListFiltersPaginateTypeDef,
-    _OptionalListFiltersRequestListFiltersPaginateTypeDef,
-):
-    pass
-
-_RequiredListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
-    "_RequiredListIPSetsRequestListIPSetsPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListIPSetsRequestListIPSetsPaginateTypeDef = TypedDict(
-    "_OptionalListIPSetsRequestListIPSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListIPSetsRequestListIPSetsPaginateTypeDef(
-    _RequiredListIPSetsRequestListIPSetsPaginateTypeDef,
-    _OptionalListIPSetsRequestListIPSetsPaginateTypeDef,
-):
-    pass
-
-ListInvitationsRequestListInvitationsPaginateTypeDef = TypedDict(
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "_RequiredListMembersRequestListMembersPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "_OptionalListMembersRequestListMembersPaginateTypeDef",
-    {
-        "OnlyAssociated": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListMembersRequestListMembersPaginateTypeDef(
-    _RequiredListMembersRequestListMembersPaginateTypeDef,
-    _OptionalListMembersRequestListMembersPaginateTypeDef,
-):
-    pass
-
-ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
-    "_RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
-    {
-        "DetectorId": str,
-    },
-)
-_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef = TypedDict(
-    "_OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef(
-    _RequiredListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
-    _OptionalListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
-):
-    pass
-
 _RequiredGetFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredGetFindingsRequestRequestTypeDef",
     {
         "DetectorId": str,
         "FindingIds": Sequence[str],
     },
 )
@@ -1965,18 +2209,39 @@
     pass
 
 ListPublishingDestinationsResponseTypeDef = TypedDict(
     "ListPublishingDestinationsResponseTypeDef",
     {
         "Destinations": List[DestinationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+DetectorFeatureConfigurationResultTypeDef = TypedDict(
+    "DetectorFeatureConfigurationResultTypeDef",
+    {
+        "Name": DetectorFeatureResultType,
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+        "AdditionalConfiguration": List[DetectorAdditionalConfigurationResultTypeDef],
+    },
+    total=False,
+)
+
+DetectorFeatureConfigurationTypeDef = TypedDict(
+    "DetectorFeatureConfigurationTypeDef",
+    {
+        "Name": DetectorFeatureType,
+        "Status": FeatureStatusType,
+        "AdditionalConfiguration": Sequence[DetectorAdditionalConfigurationTypeDef],
+    },
+    total=False,
+)
+
 EbsVolumeDetailsTypeDef = TypedDict(
     "EbsVolumeDetailsTypeDef",
     {
         "ScannedVolumeDetails": List[VolumeDetailTypeDef],
         "SkippedVolumeDetails": List[VolumeDetailTypeDef],
     },
     total=False,
@@ -1999,14 +2264,27 @@
         "Status": str,
         "Tags": List[TagTypeDef],
         "CreatedAt": datetime,
     },
     total=False,
 )
 
+RdsDbInstanceDetailsTypeDef = TypedDict(
+    "RdsDbInstanceDetailsTypeDef",
+    {
+        "DbInstanceIdentifier": str,
+        "Engine": str,
+        "EngineVersion": str,
+        "DbClusterIdentifier": str,
+        "DbInstanceArn": str,
+        "Tags": List[TagTypeDef],
+    },
+    total=False,
+)
+
 EvidenceTypeDef = TypedDict(
     "EvidenceTypeDef",
     {
         "ThreatIntelligenceDetails": List[ThreatIntelligenceDetailTypeDef],
     },
     total=False,
 )
@@ -2020,41 +2298,41 @@
     total=False,
 )
 
 GetFindingsStatisticsResponseTypeDef = TypedDict(
     "GetFindingsStatisticsResponseTypeDef",
     {
         "FindingStatistics": FindingStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMasterAccountResponseTypeDef = TypedDict(
     "GetMasterAccountResponseTypeDef",
     {
         "Master": MasterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMembersResponseTypeDef = TypedDict(
     "GetMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMembersResponseTypeDef = TypedDict(
     "ListMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetUsageStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetUsageStatisticsRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -2088,15 +2366,15 @@
 )
 
 ListInvitationsResponseTypeDef = TypedDict(
     "ListInvitationsResponseTypeDef",
     {
         "Invitations": List[InvitationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 KubernetesConfigurationResultTypeDef = TypedDict(
     "KubernetesConfigurationResultTypeDef",
     {
         "AuditLogs": KubernetesAuditLogsConfigurationResultTypeDef,
@@ -2106,22 +2384,63 @@
 KubernetesConfigurationTypeDef = TypedDict(
     "KubernetesConfigurationTypeDef",
     {
         "AuditLogs": KubernetesAuditLogsConfigurationTypeDef,
     },
 )
 
+ProcessDetailsTypeDef = TypedDict(
+    "ProcessDetailsTypeDef",
+    {
+        "Name": str,
+        "ExecutablePath": str,
+        "ExecutableSha256": str,
+        "NamespacePid": int,
+        "Pwd": str,
+        "Pid": int,
+        "StartTime": datetime,
+        "Uuid": str,
+        "ParentUuid": str,
+        "User": str,
+        "UserId": int,
+        "Euid": int,
+        "Lineage": List[LineageObjectTypeDef],
+    },
+    total=False,
+)
+
 MalwareProtectionConfigurationTypeDef = TypedDict(
     "MalwareProtectionConfigurationTypeDef",
     {
         "ScanEc2InstanceWithFindings": ScanEc2InstanceWithFindingsTypeDef,
     },
     total=False,
 )
 
+MemberFeaturesConfigurationResultTypeDef = TypedDict(
+    "MemberFeaturesConfigurationResultTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "Status": FeatureStatusType,
+        "UpdatedAt": datetime,
+        "AdditionalConfiguration": List[MemberAdditionalConfigurationResultTypeDef],
+    },
+    total=False,
+)
+
+MemberFeaturesConfigurationTypeDef = TypedDict(
+    "MemberFeaturesConfigurationTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "Status": FeatureStatusType,
+        "AdditionalConfiguration": Sequence[MemberAdditionalConfigurationTypeDef],
+    },
+    total=False,
+)
+
 NetworkInterfaceTypeDef = TypedDict(
     "NetworkInterfaceTypeDef",
     {
         "Ipv6Addresses": List[str],
         "NetworkInterfaceId": str,
         "PrivateDnsName": str,
         "PrivateIpAddress": str,
@@ -2131,14 +2450,44 @@
         "SecurityGroups": List[SecurityGroupTypeDef],
         "SubnetId": str,
         "VpcId": str,
     },
     total=False,
 )
 
+VpcConfigTypeDef = TypedDict(
+    "VpcConfigTypeDef",
+    {
+        "SubnetIds": List[str],
+        "VpcId": str,
+        "SecurityGroups": List[SecurityGroupTypeDef],
+    },
+    total=False,
+)
+
+OrganizationFeatureConfigurationResultTypeDef = TypedDict(
+    "OrganizationFeatureConfigurationResultTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "AutoEnable": OrgFeatureStatusType,
+        "AdditionalConfiguration": List[OrganizationAdditionalConfigurationResultTypeDef],
+    },
+    total=False,
+)
+
+OrganizationFeatureConfigurationTypeDef = TypedDict(
+    "OrganizationFeatureConfigurationTypeDef",
+    {
+        "Name": OrgFeatureType,
+        "AutoEnable": OrgFeatureStatusType,
+        "AdditionalConfiguration": Sequence[OrganizationAdditionalConfigurationTypeDef],
+    },
+    total=False,
+)
+
 OrganizationScanEc2InstanceWithFindingsResultTypeDef = TypedDict(
     "OrganizationScanEc2InstanceWithFindingsResultTypeDef",
     {
         "EbsVolumes": OrganizationEbsVolumesResultTypeDef,
     },
     total=False,
 )
@@ -2208,14 +2557,15 @@
         "TriggerDetails": TriggerDetailsTypeDef,
         "ResourceDetails": ResourceDetailsTypeDef,
         "ScanResultDetails": ScanResultDetailsTypeDef,
         "AccountId": str,
         "TotalBytes": int,
         "FileCount": int,
         "AttachedVolumes": List[VolumeDetailTypeDef],
+        "ScanType": ScanTypeType,
     },
     total=False,
 )
 
 UsageAccountResultTypeDef = TypedDict(
     "UsageAccountResultTypeDef",
     {
@@ -2230,23 +2580,41 @@
     {
         "DataSource": DataSourceType,
         "Total": TotalTypeDef,
     },
     total=False,
 )
 
+UsageFeatureResultTypeDef = TypedDict(
+    "UsageFeatureResultTypeDef",
+    {
+        "Feature": UsageFeatureType,
+        "Total": TotalTypeDef,
+    },
+    total=False,
+)
+
 UsageResourceResultTypeDef = TypedDict(
     "UsageResourceResultTypeDef",
     {
         "Resource": str,
         "Total": TotalTypeDef,
     },
     total=False,
 )
 
+CoverageResourceDetailsTypeDef = TypedDict(
+    "CoverageResourceDetailsTypeDef",
+    {
+        "EksClusterDetails": CoverageEksClusterDetailsTypeDef,
+        "ResourceType": Literal["EKS"],
+    },
+    total=False,
+)
+
 PermissionConfigurationTypeDef = TypedDict(
     "PermissionConfigurationTypeDef",
     {
         "BucketLevelPermissions": BucketLevelPermissionsTypeDef,
         "AccountLevelPermissions": AccountLevelPermissionsTypeDef,
     },
     total=False,
@@ -2282,15 +2650,15 @@
     {
         "Name": str,
         "Description": str,
         "Action": FilterActionType,
         "Rank": int,
         "FindingCriteria": FindingCriteriaTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetFindingsStatisticsRequestRequestTypeDef = TypedDict(
     "_RequiredGetFindingsStatisticsRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -2318,15 +2686,15 @@
     },
 )
 _OptionalListFindingsRequestListFindingsPaginateTypeDef = TypedDict(
     "_OptionalListFindingsRequestListFindingsPaginateTypeDef",
     {
         "FindingCriteria": FindingCriteriaTypeDef,
         "SortCriteria": SortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListFindingsRequestListFindingsPaginateTypeDef(
     _RequiredListFindingsRequestListFindingsPaginateTypeDef,
     _OptionalListFindingsRequestListFindingsPaginateTypeDef,
@@ -2374,14 +2742,22 @@
 )
 
 class UpdateFilterRequestRequestTypeDef(
     _RequiredUpdateFilterRequestRequestTypeDef, _OptionalUpdateFilterRequestRequestTypeDef
 ):
     pass
 
+CoverageFilterCriteriaTypeDef = TypedDict(
+    "CoverageFilterCriteriaTypeDef",
+    {
+        "FilterCriterion": Sequence[CoverageFilterCriterionTypeDef],
+    },
+    total=False,
+)
+
 DataSourcesFreeTrialTypeDef = TypedDict(
     "DataSourcesFreeTrialTypeDef",
     {
         "CloudTrail": DataSourceFreeTrialTypeDef,
         "DnsLogs": DataSourceFreeTrialTypeDef,
         "FlowLogs": DataSourceFreeTrialTypeDef,
         "S3Logs": DataSourceFreeTrialTypeDef,
@@ -2435,14 +2811,41 @@
         "HostNetwork": bool,
         "Containers": List[ContainerTypeDef],
         "Volumes": List[VolumeTypeDef],
     },
     total=False,
 )
 
+RuntimeContextTypeDef = TypedDict(
+    "RuntimeContextTypeDef",
+    {
+        "ModifyingProcess": ProcessDetailsTypeDef,
+        "ModifiedAt": datetime,
+        "ScriptPath": str,
+        "LibraryPath": str,
+        "LdPreloadValue": str,
+        "SocketPath": str,
+        "RuncBinaryPath": str,
+        "ReleaseAgentPath": str,
+        "MountSource": str,
+        "MountTarget": str,
+        "FileSystemType": str,
+        "Flags": List[str],
+        "ModuleName": str,
+        "ModuleFilePath": str,
+        "ModuleSha256": str,
+        "ShellHistoryFilePath": str,
+        "TargetProcess": ProcessDetailsTypeDef,
+        "AddressFamily": str,
+        "IanaProtocolNumber": int,
+        "MemoryRegions": List[str],
+    },
+    total=False,
+)
+
 DataSourceConfigurationsTypeDef = TypedDict(
     "DataSourceConfigurationsTypeDef",
     {
         "S3Logs": S3LogsConfigurationTypeDef,
         "Kubernetes": KubernetesConfigurationTypeDef,
         "MalwareProtection": MalwareProtectionConfigurationTypeDef,
     },
@@ -2465,14 +2868,30 @@
         "Platform": str,
         "ProductCodes": List[ProductCodeTypeDef],
         "Tags": List[TagTypeDef],
     },
     total=False,
 )
 
+LambdaDetailsTypeDef = TypedDict(
+    "LambdaDetailsTypeDef",
+    {
+        "FunctionArn": str,
+        "FunctionName": str,
+        "Description": str,
+        "LastModifiedAt": datetime,
+        "RevisionId": str,
+        "FunctionVersion": str,
+        "Role": str,
+        "VpcConfig": VpcConfigTypeDef,
+        "Tags": List[TagTypeDef],
+    },
+    total=False,
+)
+
 OrganizationMalwareProtectionConfigurationResultTypeDef = TypedDict(
     "OrganizationMalwareProtectionConfigurationResultTypeDef",
     {
         "ScanEc2InstanceWithFindings": OrganizationScanEc2InstanceWithFindingsResultTypeDef,
     },
     total=False,
 )
@@ -2535,14 +2954,23 @@
         "LocalPortDetails": LocalPortDetailsTypeDef,
         "LocalIpDetails": LocalIpDetailsTypeDef,
         "RemoteIpDetails": RemoteIpDetailsTypeDef,
     },
     total=False,
 )
 
+RdsLoginAttemptActionTypeDef = TypedDict(
+    "RdsLoginAttemptActionTypeDef",
+    {
+        "RemoteIpDetails": RemoteIpDetailsTypeDef,
+        "LoginAttributes": List[LoginAttributeTypeDef],
+    },
+    total=False,
+)
+
 ScanResourceCriteriaTypeDef = TypedDict(
     "ScanResourceCriteriaTypeDef",
     {
         "Include": Dict[Literal["EC2_INSTANCE_TAG"], ScanConditionTypeDef],
         "Exclude": Dict[Literal["EC2_INSTANCE_TAG"], ScanConditionTypeDef],
     },
     total=False,
@@ -2560,43 +2988,124 @@
 )
 
 DescribeMalwareScansResponseTypeDef = TypedDict(
     "DescribeMalwareScansResponseTypeDef",
     {
         "Scans": List[ScanTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UsageStatisticsTypeDef = TypedDict(
     "UsageStatisticsTypeDef",
     {
         "SumByAccount": List[UsageAccountResultTypeDef],
         "SumByDataSource": List[UsageDataSourceResultTypeDef],
         "SumByResource": List[UsageResourceResultTypeDef],
         "TopResources": List[UsageResourceResultTypeDef],
+        "SumByFeature": List[UsageFeatureResultTypeDef],
+    },
+    total=False,
+)
+
+CoverageResourceTypeDef = TypedDict(
+    "CoverageResourceTypeDef",
+    {
+        "ResourceId": str,
+        "DetectorId": str,
+        "AccountId": str,
+        "ResourceDetails": CoverageResourceDetailsTypeDef,
+        "CoverageStatus": CoverageStatusType,
+        "Issue": str,
+        "UpdatedAt": datetime,
     },
     total=False,
 )
 
 PublicAccessTypeDef = TypedDict(
     "PublicAccessTypeDef",
     {
         "PermissionConfiguration": PermissionConfigurationTypeDef,
         "EffectivePermission": str,
     },
     total=False,
 )
 
+_RequiredGetCoverageStatisticsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetCoverageStatisticsRequestRequestTypeDef",
+    {
+        "DetectorId": str,
+        "StatisticsType": Sequence[CoverageStatisticsTypeType],
+    },
+)
+_OptionalGetCoverageStatisticsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetCoverageStatisticsRequestRequestTypeDef",
+    {
+        "FilterCriteria": CoverageFilterCriteriaTypeDef,
+    },
+    total=False,
+)
+
+class GetCoverageStatisticsRequestRequestTypeDef(
+    _RequiredGetCoverageStatisticsRequestRequestTypeDef,
+    _OptionalGetCoverageStatisticsRequestRequestTypeDef,
+):
+    pass
+
+_RequiredListCoverageRequestListCoveragePaginateTypeDef = TypedDict(
+    "_RequiredListCoverageRequestListCoveragePaginateTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListCoverageRequestListCoveragePaginateTypeDef = TypedDict(
+    "_OptionalListCoverageRequestListCoveragePaginateTypeDef",
+    {
+        "FilterCriteria": CoverageFilterCriteriaTypeDef,
+        "SortCriteria": CoverageSortCriteriaTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListCoverageRequestListCoveragePaginateTypeDef(
+    _RequiredListCoverageRequestListCoveragePaginateTypeDef,
+    _OptionalListCoverageRequestListCoveragePaginateTypeDef,
+):
+    pass
+
+_RequiredListCoverageRequestRequestTypeDef = TypedDict(
+    "_RequiredListCoverageRequestRequestTypeDef",
+    {
+        "DetectorId": str,
+    },
+)
+_OptionalListCoverageRequestRequestTypeDef = TypedDict(
+    "_OptionalListCoverageRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+        "FilterCriteria": CoverageFilterCriteriaTypeDef,
+        "SortCriteria": CoverageSortCriteriaTypeDef,
+    },
+    total=False,
+)
+
+class ListCoverageRequestRequestTypeDef(
+    _RequiredListCoverageRequestRequestTypeDef, _OptionalListCoverageRequestRequestTypeDef
+):
+    pass
+
 AccountFreeTrialInfoTypeDef = TypedDict(
     "AccountFreeTrialInfoTypeDef",
     {
         "AccountId": str,
         "DataSources": DataSourcesFreeTrialTypeDef,
+        "Features": List[FreeTrialFeatureConfigurationResultTypeDef],
     },
     total=False,
 )
 
 _RequiredDataSourceConfigurationsResultTypeDef = TypedDict(
     "_RequiredDataSourceConfigurationsResultTypeDef",
     {
@@ -2635,15 +3144,15 @@
     },
 )
 _OptionalDescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef = TypedDict(
     "_OptionalDescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef",
     {
         "FilterCriteria": FilterCriteriaTypeDef,
         "SortCriteria": SortCriteriaTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef(
     _RequiredDescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef,
     _OptionalDescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef,
@@ -2693,27 +3202,37 @@
     {
         "KubernetesUserDetails": KubernetesUserDetailsTypeDef,
         "KubernetesWorkloadDetails": KubernetesWorkloadDetailsTypeDef,
     },
     total=False,
 )
 
+RuntimeDetailsTypeDef = TypedDict(
+    "RuntimeDetailsTypeDef",
+    {
+        "Process": ProcessDetailsTypeDef,
+        "Context": RuntimeContextTypeDef,
+    },
+    total=False,
+)
+
 _RequiredCreateDetectorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDetectorRequestRequestTypeDef",
     {
         "Enable": bool,
     },
 )
 _OptionalCreateDetectorRequestRequestTypeDef = TypedDict(
     "_OptionalCreateDetectorRequestRequestTypeDef",
     {
         "ClientToken": str,
         "FindingPublishingFrequency": FindingPublishingFrequencyType,
         "DataSources": DataSourceConfigurationsTypeDef,
         "Tags": Mapping[str, str],
+        "Features": Sequence[DetectorFeatureConfigurationTypeDef],
     },
     total=False,
 )
 
 class CreateDetectorRequestRequestTypeDef(
     _RequiredCreateDetectorRequestRequestTypeDef, _OptionalCreateDetectorRequestRequestTypeDef
 ):
@@ -2727,14 +3246,15 @@
 )
 _OptionalUpdateDetectorRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateDetectorRequestRequestTypeDef",
     {
         "Enable": bool,
         "FindingPublishingFrequency": FindingPublishingFrequencyType,
         "DataSources": DataSourceConfigurationsTypeDef,
+        "Features": Sequence[DetectorFeatureConfigurationTypeDef],
     },
     total=False,
 )
 
 class UpdateDetectorRequestRequestTypeDef(
     _RequiredUpdateDetectorRequestRequestTypeDef, _OptionalUpdateDetectorRequestRequestTypeDef
 ):
@@ -2747,14 +3267,15 @@
         "AccountIds": Sequence[str],
     },
 )
 _OptionalUpdateMemberDetectorsRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateMemberDetectorsRequestRequestTypeDef",
     {
         "DataSources": DataSourceConfigurationsTypeDef,
+        "Features": Sequence[MemberFeaturesConfigurationTypeDef],
     },
     total=False,
 )
 
 class UpdateMemberDetectorsRequestRequestTypeDef(
     _RequiredUpdateMemberDetectorsRequestRequestTypeDef,
     _OptionalUpdateMemberDetectorsRequestRequestTypeDef,
@@ -2802,15 +3323,15 @@
 )
 
 GetMalwareScanSettingsResponseTypeDef = TypedDict(
     "GetMalwareScanSettingsResponseTypeDef",
     {
         "ScanResourceCriteria": ScanResourceCriteriaTypeDef,
         "EbsSnapshotPreservation": EbsSnapshotPreservationType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateMalwareScanSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateMalwareScanSettingsRequestRequestTypeDef",
     {
         "DetectorId": str,
@@ -2843,15 +3364,24 @@
 )
 
 GetUsageStatisticsResponseTypeDef = TypedDict(
     "GetUsageStatisticsResponseTypeDef",
     {
         "UsageStatistics": UsageStatisticsTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCoverageResponseTypeDef = TypedDict(
+    "ListCoverageResponseTypeDef",
+    {
+        "Resources": List[CoverageResourceTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 S3BucketDetailTypeDef = TypedDict(
     "S3BucketDetailTypeDef",
     {
         "Arn": str,
@@ -2867,70 +3397,88 @@
 )
 
 GetRemainingFreeTrialDaysResponseTypeDef = TypedDict(
     "GetRemainingFreeTrialDaysResponseTypeDef",
     {
         "Accounts": List[AccountFreeTrialInfoTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDetectorResponseTypeDef = TypedDict(
     "GetDetectorResponseTypeDef",
     {
         "CreatedAt": str,
         "FindingPublishingFrequency": FindingPublishingFrequencyType,
         "ServiceRole": str,
         "Status": DetectorStatusType,
         "UpdatedAt": str,
         "DataSources": DataSourceConfigurationsResultTypeDef,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Features": List[DetectorFeatureConfigurationResultTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-MemberDataSourceConfigurationTypeDef = TypedDict(
-    "MemberDataSourceConfigurationTypeDef",
+_RequiredMemberDataSourceConfigurationTypeDef = TypedDict(
+    "_RequiredMemberDataSourceConfigurationTypeDef",
     {
         "AccountId": str,
+    },
+)
+_OptionalMemberDataSourceConfigurationTypeDef = TypedDict(
+    "_OptionalMemberDataSourceConfigurationTypeDef",
+    {
         "DataSources": DataSourceConfigurationsResultTypeDef,
+        "Features": List[MemberFeaturesConfigurationResultTypeDef],
     },
+    total=False,
 )
 
+class MemberDataSourceConfigurationTypeDef(
+    _RequiredMemberDataSourceConfigurationTypeDef, _OptionalMemberDataSourceConfigurationTypeDef
+):
+    pass
+
 CreateDetectorResponseTypeDef = TypedDict(
     "CreateDetectorResponseTypeDef",
     {
         "DetectorId": str,
         "UnprocessedDataSources": UnprocessedDataSourcesResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
     "DescribeOrganizationConfigurationResponseTypeDef",
     {
         "AutoEnable": bool,
         "MemberAccountLimitReached": bool,
         "DataSources": OrganizationDataSourceConfigurationsResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Features": List[OrganizationFeatureConfigurationResultTypeDef],
+        "NextToken": str,
+        "AutoEnableOrganizationMembers": AutoEnableMembersType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
         "DetectorId": str,
-        "AutoEnable": bool,
     },
 )
 _OptionalUpdateOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
+        "AutoEnable": bool,
         "DataSources": OrganizationDataSourceConfigurationsTypeDef,
+        "Features": Sequence[OrganizationFeatureConfigurationTypeDef],
+        "AutoEnableOrganizationMembers": AutoEnableMembersType,
     },
     total=False,
 )
 
 class UpdateOrganizationConfigurationRequestRequestTypeDef(
     _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef,
     _OptionalUpdateOrganizationConfigurationRequestRequestTypeDef,
@@ -2942,27 +3490,29 @@
     {
         "ActionType": str,
         "AwsApiCallAction": AwsApiCallActionTypeDef,
         "DnsRequestAction": DnsRequestActionTypeDef,
         "NetworkConnectionAction": NetworkConnectionActionTypeDef,
         "PortProbeAction": PortProbeActionTypeDef,
         "KubernetesApiCallAction": KubernetesApiCallActionTypeDef,
+        "RdsLoginAttemptAction": RdsLoginAttemptActionTypeDef,
     },
     total=False,
 )
 
 EbsVolumeScanDetailsTypeDef = TypedDict(
     "EbsVolumeScanDetailsTypeDef",
     {
         "ScanId": str,
         "ScanStartedAt": datetime,
         "ScanCompletedAt": datetime,
         "TriggerFindingId": str,
         "Sources": List[str],
         "ScanDetections": ScanDetectionsTypeDef,
+        "ScanType": ScanTypeType,
     },
     total=False,
 )
 
 ResourceTypeDef = TypedDict(
     "ResourceTypeDef",
     {
@@ -2971,24 +3521,27 @@
         "InstanceDetails": InstanceDetailsTypeDef,
         "EksClusterDetails": EksClusterDetailsTypeDef,
         "KubernetesDetails": KubernetesDetailsTypeDef,
         "ResourceType": str,
         "EbsVolumeDetails": EbsVolumeDetailsTypeDef,
         "EcsClusterDetails": EcsClusterDetailsTypeDef,
         "ContainerDetails": ContainerTypeDef,
+        "RdsDbInstanceDetails": RdsDbInstanceDetailsTypeDef,
+        "RdsDbUserDetails": RdsDbUserDetailsTypeDef,
+        "LambdaDetails": LambdaDetailsTypeDef,
     },
     total=False,
 )
 
 GetMemberDetectorsResponseTypeDef = TypedDict(
     "GetMemberDetectorsResponseTypeDef",
     {
         "MemberDataSourceConfigurations": List[MemberDataSourceConfigurationTypeDef],
         "UnprocessedAccounts": List[UnprocessedAccountTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceTypeDef = TypedDict(
     "ServiceTypeDef",
     {
         "Action": ActionTypeDef,
@@ -3000,14 +3553,15 @@
         "EventLastSeen": str,
         "ResourceRole": str,
         "ServiceName": str,
         "UserFeedback": str,
         "AdditionalInfo": ServiceAdditionalInfoTypeDef,
         "FeatureName": str,
         "EbsVolumeScanDetails": EbsVolumeScanDetailsTypeDef,
+        "RuntimeDetails": RuntimeDetailsTypeDef,
     },
     total=False,
 )
 
 _RequiredFindingTypeDef = TypedDict(
     "_RequiredFindingTypeDef",
     {
@@ -3038,10 +3592,10 @@
 class FindingTypeDef(_RequiredFindingTypeDef, _OptionalFindingTypeDef):
     pass
 
 GetFindingsResponseTypeDef = TypedDict(
     "GetFindingsResponseTypeDef",
     {
         "Findings": List[FindingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/PKG-INFO` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-guardduty
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GuardDuty 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GuardDuty 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-guardduty"></a>
 
 # types-aiobotocore-guardduty
 
 [![PyPI - types-aiobotocore-guardduty](https://img.shields.io/pypi/v/types-aiobotocore-guardduty.svg?color=blue)](https://pypi.org/project/types-aiobotocore-guardduty)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-guardduty.svg?color=blue)](https://pypi.org/project/types-aiobotocore-guardduty)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-guardduty?color=blue)](https://pypistats.org/packages/types-aiobotocore-guardduty)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GuardDuty 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
+[aiobotocore.GuardDuty 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/guardduty.html#GuardDuty)
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
 [types-aiobotocore-guardduty docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_guardduty/).
 
 See how it helps to find and fix potential bugs:
 
@@ -274,14 +274,15 @@
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_guardduty import GuardDutyClient
 from types_aiobotocore_guardduty.paginator import (
     DescribeMalwareScansPaginator,
+    ListCoveragePaginator,
     ListDetectorsPaginator,
     ListFiltersPaginator,
     ListFindingsPaginator,
     ListIPSetsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
@@ -293,14 +294,15 @@
     client: GuardDutyClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
     describe_malware_scans_paginator: DescribeMalwareScansPaginator = client.get_paginator(
         "describe_malware_scans"
     )
+    list_coverage_paginator: ListCoveragePaginator = client.get_paginator("list_coverage")
     list_detectors_paginator: ListDetectorsPaginator = client.get_paginator("list_detectors")
     list_filters_paginator: ListFiltersPaginator = client.get_paginator("list_filters")
     list_findings_paginator: ListFindingsPaginator = client.get_paginator("list_findings")
     list_ip_sets_paginator: ListIPSetsPaginator = client.get_paginator("list_ip_sets")
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = (
@@ -317,42 +319,59 @@
 
 `types_aiobotocore_guardduty.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_guardduty.literals import (
     AdminStatusType,
+    AutoEnableMembersType,
+    CoverageFilterCriterionKeyType,
+    CoverageSortKeyType,
+    CoverageStatisticsTypeType,
+    CoverageStatusType,
     CriterionKeyType,
     DataSourceStatusType,
     DataSourceType,
     DescribeMalwareScansPaginatorName,
     DestinationTypeType,
+    DetectorFeatureResultType,
+    DetectorFeatureType,
     DetectorStatusType,
     EbsSnapshotPreservationType,
+    FeatureAdditionalConfigurationType,
+    FeatureStatusType,
     FeedbackType,
     FilterActionType,
     FindingPublishingFrequencyType,
     FindingStatisticTypeType,
+    FreeTrialFeatureResultType,
     IpSetFormatType,
     IpSetStatusType,
+    ListCoveragePaginatorName,
     ListDetectorsPaginatorName,
     ListFiltersPaginatorName,
     ListFindingsPaginatorName,
     ListIPSetsPaginatorName,
     ListInvitationsPaginatorName,
     ListMembersPaginatorName,
     ListOrganizationAdminAccountsPaginatorName,
     ListThreatIntelSetsPaginatorName,
     OrderByType,
+    OrgFeatureAdditionalConfigurationType,
+    OrgFeatureStatusType,
+    OrgFeatureType,
     PublishingStatusType,
+    ResourceTypeType,
     ScanCriterionKeyType,
     ScanResultType,
     ScanStatusType,
+    ScanTypeType,
     ThreatIntelSetFormatType,
     ThreatIntelSetStatusType,
+    UsageFeatureType,
     UsageStatisticTypeType,
     GuardDutyServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -372,53 +391,62 @@
 ```python
 from types_aiobotocore_guardduty.type_defs import (
     AcceptAdministratorInvitationRequestRequestTypeDef,
     AcceptInvitationRequestRequestTypeDef,
     AccessControlListTypeDef,
     AccessKeyDetailsTypeDef,
     AccountDetailTypeDef,
+    FreeTrialFeatureConfigurationResultTypeDef,
     BlockPublicAccessTypeDef,
     DnsRequestActionTypeDef,
+    AddonDetailsTypeDef,
     AdminAccountTypeDef,
     AdministratorTypeDef,
     ArchiveFindingsRequestRequestTypeDef,
     DomainDetailsTypeDef,
     RemoteAccountDetailsTypeDef,
     BucketPolicyTypeDef,
     CityTypeDef,
     CloudTrailConfigurationResultTypeDef,
     ConditionTypeDef,
     SecurityContextTypeDef,
     VolumeMountTypeDef,
     CountryTypeDef,
-    ResponseMetadataTypeDef,
+    CoverageFilterConditionTypeDef,
+    CoverageSortCriteriaTypeDef,
+    CoverageStatisticsTypeDef,
+    CreateFilterResponseTypeDef,
     CreateIPSetRequestRequestTypeDef,
+    CreateIPSetResponseTypeDef,
     UnprocessedAccountTypeDef,
     DestinationPropertiesTypeDef,
+    CreatePublishingDestinationResponseTypeDef,
     CreateSampleFindingsRequestRequestTypeDef,
     CreateThreatIntelSetRequestRequestTypeDef,
+    CreateThreatIntelSetResponseTypeDef,
     DNSLogsConfigurationResultTypeDef,
     FlowLogsConfigurationResultTypeDef,
     S3LogsConfigurationResultTypeDef,
     S3LogsConfigurationTypeDef,
     DataSourceFreeTrialTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DefaultServerSideEncryptionTypeDef,
     DeleteDetectorRequestRequestTypeDef,
     DeleteFilterRequestRequestTypeDef,
     DeleteIPSetRequestRequestTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
     DeletePublishingDestinationRequestRequestTypeDef,
     DeleteThreatIntelSetRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
     SortCriteriaTypeDef,
     DescribeOrganizationConfigurationRequestRequestTypeDef,
     DescribePublishingDestinationRequestRequestTypeDef,
     DestinationTypeDef,
+    DetectorAdditionalConfigurationResultTypeDef,
+    DetectorAdditionalConfigurationTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateFromAdministratorAccountRequestRequestTypeDef,
     DisassociateFromMasterAccountRequestRequestTypeDef,
     DisassociateMembersRequestRequestTypeDef,
     VolumeDetailTypeDef,
     EbsVolumesResultTypeDef,
     TagTypeDef,
@@ -427,185 +455,216 @@
     FilterConditionTypeDef,
     FindingStatisticsTypeDef,
     GeoLocationTypeDef,
     GetAdministratorAccountRequestRequestTypeDef,
     GetDetectorRequestRequestTypeDef,
     GetFilterRequestRequestTypeDef,
     GetIPSetRequestRequestTypeDef,
+    GetIPSetResponseTypeDef,
+    GetInvitationsCountResponseTypeDef,
     GetMalwareScanSettingsRequestRequestTypeDef,
     GetMasterAccountRequestRequestTypeDef,
     MasterTypeDef,
     GetMemberDetectorsRequestRequestTypeDef,
     GetMembersRequestRequestTypeDef,
     MemberTypeDef,
     GetRemainingFreeTrialDaysRequestRequestTypeDef,
     GetThreatIntelSetRequestRequestTypeDef,
+    GetThreatIntelSetResponseTypeDef,
     UsageCriteriaTypeDef,
     HighestSeverityThreatDetailsTypeDef,
     HostPathTypeDef,
     IamInstanceProfileTypeDef,
     ProductCodeTypeDef,
     InvitationTypeDef,
     InviteMembersRequestRequestTypeDef,
     KubernetesAuditLogsConfigurationResultTypeDef,
     KubernetesAuditLogsConfigurationTypeDef,
     KubernetesUserDetailsTypeDef,
+    LineageObjectTypeDef,
+    ListDetectorsRequestListDetectorsPaginateTypeDef,
     ListDetectorsRequestRequestTypeDef,
+    ListDetectorsResponseTypeDef,
+    ListFiltersRequestListFiltersPaginateTypeDef,
     ListFiltersRequestRequestTypeDef,
+    ListFiltersResponseTypeDef,
+    ListFindingsResponseTypeDef,
+    ListIPSetsRequestListIPSetsPaginateTypeDef,
     ListIPSetsRequestRequestTypeDef,
+    ListIPSetsResponseTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
     ListPublishingDestinationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
     ListThreatIntelSetsRequestRequestTypeDef,
+    ListThreatIntelSetsResponseTypeDef,
     LocalIpDetailsTypeDef,
     LocalPortDetailsTypeDef,
+    LoginAttributeTypeDef,
     ScanEc2InstanceWithFindingsTypeDef,
+    MemberAdditionalConfigurationResultTypeDef,
+    MemberAdditionalConfigurationTypeDef,
     RemotePortDetailsTypeDef,
     PrivateIpAddressDetailsTypeDef,
     SecurityGroupTypeDef,
+    OrganizationAdditionalConfigurationResultTypeDef,
+    OrganizationAdditionalConfigurationTypeDef,
     OrganizationS3LogsConfigurationResultTypeDef,
     OrganizationS3LogsConfigurationTypeDef,
     OrganizationEbsVolumesResultTypeDef,
     OrganizationEbsVolumesTypeDef,
     OrganizationKubernetesAuditLogsConfigurationResultTypeDef,
     OrganizationKubernetesAuditLogsConfigurationTypeDef,
     OrganizationTypeDef,
     OwnerTypeDef,
+    PaginatorConfigTypeDef,
+    RdsDbUserDetailsTypeDef,
     ResourceDetailsTypeDef,
+    ResponseMetadataTypeDef,
     ScanConditionPairTypeDef,
     ScannedItemCountTypeDef,
     ThreatsDetectedItemCountTypeDef,
     ScanFilePathTypeDef,
     ScanResultDetailsTypeDef,
     TriggerDetailsTypeDef,
     ServiceAdditionalInfoTypeDef,
+    StartMalwareScanRequestRequestTypeDef,
+    StartMalwareScanResponseTypeDef,
     StartMonitoringMembersRequestRequestTypeDef,
     StopMonitoringMembersRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     TotalTypeDef,
     UnarchiveFindingsRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateFilterResponseTypeDef,
     UpdateFindingsFeedbackRequestRequestTypeDef,
     UpdateIPSetRequestRequestTypeDef,
     UpdateThreatIntelSetRequestRequestTypeDef,
     CreateMembersRequestRequestTypeDef,
     AccountLevelPermissionsTypeDef,
+    CoverageEksClusterDetailsTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
+    GetAdministratorAccountResponseTypeDef,
     BucketLevelPermissionsTypeDef,
     FindingCriteriaTypeDef,
     ContainerTypeDef,
-    CreateFilterResponseTypeDef,
-    CreateIPSetResponseTypeDef,
-    CreatePublishingDestinationResponseTypeDef,
-    CreateThreatIntelSetResponseTypeDef,
-    GetAdministratorAccountResponseTypeDef,
-    GetIPSetResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    GetThreatIntelSetResponseTypeDef,
-    ListDetectorsResponseTypeDef,
-    ListFiltersResponseTypeDef,
-    ListFindingsResponseTypeDef,
-    ListIPSetsResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListThreatIntelSetsResponseTypeDef,
-    UpdateFilterResponseTypeDef,
+    CoverageFilterCriterionTypeDef,
+    GetCoverageStatisticsResponseTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     DisassociateMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
     StartMonitoringMembersResponseTypeDef,
     StopMonitoringMembersResponseTypeDef,
     UpdateMemberDetectorsResponseTypeDef,
     CreatePublishingDestinationRequestRequestTypeDef,
     DescribePublishingDestinationResponseTypeDef,
     UpdatePublishingDestinationRequestRequestTypeDef,
     KubernetesDataSourceFreeTrialTypeDef,
     MalwareProtectionDataSourceFreeTrialTypeDef,
-    ListDetectorsRequestListDetectorsPaginateTypeDef,
-    ListFiltersRequestListFiltersPaginateTypeDef,
-    ListIPSetsRequestListIPSetsPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
-    ListThreatIntelSetsRequestListThreatIntelSetsPaginateTypeDef,
     GetFindingsRequestRequestTypeDef,
     ListPublishingDestinationsResponseTypeDef,
+    DetectorFeatureConfigurationResultTypeDef,
+    DetectorFeatureConfigurationTypeDef,
     EbsVolumeDetailsTypeDef,
     ScanEc2InstanceWithFindingsResultTypeDef,
     EksClusterDetailsTypeDef,
+    RdsDbInstanceDetailsTypeDef,
     EvidenceTypeDef,
     FilterCriterionTypeDef,
     GetFindingsStatisticsResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     GetMembersResponseTypeDef,
     ListMembersResponseTypeDef,
     GetUsageStatisticsRequestRequestTypeDef,
     VolumeTypeDef,
     ListInvitationsResponseTypeDef,
     KubernetesConfigurationResultTypeDef,
     KubernetesConfigurationTypeDef,
+    ProcessDetailsTypeDef,
     MalwareProtectionConfigurationTypeDef,
+    MemberFeaturesConfigurationResultTypeDef,
+    MemberFeaturesConfigurationTypeDef,
     NetworkInterfaceTypeDef,
+    VpcConfigTypeDef,
+    OrganizationFeatureConfigurationResultTypeDef,
+    OrganizationFeatureConfigurationTypeDef,
     OrganizationScanEc2InstanceWithFindingsResultTypeDef,
     OrganizationScanEc2InstanceWithFindingsTypeDef,
     OrganizationKubernetesConfigurationResultTypeDef,
     OrganizationKubernetesConfigurationTypeDef,
     RemoteIpDetailsTypeDef,
     ScanConditionTypeDef,
     ScanThreatNameTypeDef,
     ScanTypeDef,
     UsageAccountResultTypeDef,
     UsageDataSourceResultTypeDef,
+    UsageFeatureResultTypeDef,
     UsageResourceResultTypeDef,
+    CoverageResourceDetailsTypeDef,
     PermissionConfigurationTypeDef,
     CreateFilterRequestRequestTypeDef,
     GetFilterResponseTypeDef,
     GetFindingsStatisticsRequestRequestTypeDef,
     ListFindingsRequestListFindingsPaginateTypeDef,
     ListFindingsRequestRequestTypeDef,
     UpdateFilterRequestRequestTypeDef,
+    CoverageFilterCriteriaTypeDef,
     DataSourcesFreeTrialTypeDef,
     MalwareProtectionConfigurationResultTypeDef,
     FilterCriteriaTypeDef,
     EcsTaskDetailsTypeDef,
     KubernetesWorkloadDetailsTypeDef,
+    RuntimeContextTypeDef,
     DataSourceConfigurationsTypeDef,
     InstanceDetailsTypeDef,
+    LambdaDetailsTypeDef,
     OrganizationMalwareProtectionConfigurationResultTypeDef,
     OrganizationMalwareProtectionConfigurationTypeDef,
     AwsApiCallActionTypeDef,
     KubernetesApiCallActionTypeDef,
     NetworkConnectionActionTypeDef,
     PortProbeDetailTypeDef,
+    RdsLoginAttemptActionTypeDef,
     ScanResourceCriteriaTypeDef,
     ThreatDetectedByNameTypeDef,
     DescribeMalwareScansResponseTypeDef,
     UsageStatisticsTypeDef,
+    CoverageResourceTypeDef,
     PublicAccessTypeDef,
+    GetCoverageStatisticsRequestRequestTypeDef,
+    ListCoverageRequestListCoveragePaginateTypeDef,
+    ListCoverageRequestRequestTypeDef,
     AccountFreeTrialInfoTypeDef,
     DataSourceConfigurationsResultTypeDef,
     UnprocessedDataSourcesResultTypeDef,
     DescribeMalwareScansRequestDescribeMalwareScansPaginateTypeDef,
     DescribeMalwareScansRequestRequestTypeDef,
     EcsClusterDetailsTypeDef,
     KubernetesDetailsTypeDef,
+    RuntimeDetailsTypeDef,
     CreateDetectorRequestRequestTypeDef,
     UpdateDetectorRequestRequestTypeDef,
     UpdateMemberDetectorsRequestRequestTypeDef,
     OrganizationDataSourceConfigurationsResultTypeDef,
     OrganizationDataSourceConfigurationsTypeDef,
     PortProbeActionTypeDef,
     GetMalwareScanSettingsResponseTypeDef,
     UpdateMalwareScanSettingsRequestRequestTypeDef,
     ScanDetectionsTypeDef,
     GetUsageStatisticsResponseTypeDef,
+    ListCoverageResponseTypeDef,
     S3BucketDetailTypeDef,
     GetRemainingFreeTrialDaysResponseTypeDef,
     GetDetectorResponseTypeDef,
     MemberDataSourceConfigurationTypeDef,
     CreateDetectorResponseTypeDef,
     DescribeOrganizationConfigurationResponseTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
@@ -626,43 +685,43 @@
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

### Comparing `types-aiobotocore-guardduty-2.5.0.post1/types_aiobotocore_guardduty.egg-info/SOURCES.txt` & `types-aiobotocore-guardduty-2.5.1/types_aiobotocore_guardduty.egg-info/SOURCES.txt`

 * *Files identical despite different names*

