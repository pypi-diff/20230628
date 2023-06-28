# Comparing `tmp/types-aiobotocore-fms-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-fms-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-fms-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:39 2023, max compression
+gzip compressed data, was "types-aiobotocore-fms-2.5.1.tar", last modified: Wed Jun 28 01:43:31 2023, max compression
```

## Comparing `types-aiobotocore-fms-2.5.0.post1.tar` & `types-aiobotocore-fms-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.199222 types-aiobotocore-fms-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19996 2023-03-11 12:26:39.199222 types-aiobotocore-fms-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18441 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:39.199222 types-aiobotocore-fms-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.199222 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/
--rw-r--r--   0 runner    (1001) docker     (123)     1815 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1814 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    29483 2023-03-11 12:14:40.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    29430 2023-03-11 12:14:39.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12019 2023-03-11 12:14:40.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12017 2023-03-11 12:14:40.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7852 2023-03-11 12:14:40.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7843 2023-03-11 12:14:40.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    54770 2023-03-11 12:14:41.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    54705 2023-03-11 12:14:40.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:38.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.199222 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19996 2023-03-11 12:26:39.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:39.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:39.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:39.000000 types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.282140 types-aiobotocore-fms-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21238 2023-06-28 01:43:31.274140 types-aiobotocore-fms-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19689 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:31.282140 types-aiobotocore-fms-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.270140 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/
+-rw-r--r--   0 runner    (1001) docker     (123)     2379 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2378 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32969 2023-06-28 01:31:16.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32910 2023-06-28 01:31:16.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12999 2023-06-28 01:31:16.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12997 2023-06-28 01:31:16.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10174 2023-06-28 01:31:16.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10164 2023-06-28 01:31:16.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    59453 2023-06-28 01:31:17.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59386 2023-06-28 01:31:16.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:15.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.274140 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21238 2023-06-28 01:43:31.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:31.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:31.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:31.000000 types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/LICENSE` & `types-aiobotocore-fms-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-fms-2.5.0.post1/PKG-INFO` & `types-aiobotocore-fms-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-fms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FMS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FMS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-fms"></a>
 
 # types-aiobotocore-fms
 
 [![PyPI - types-aiobotocore-fms](https://img.shields.io/pypi/v/types-aiobotocore-fms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fms?color=blue)](https://pypistats.org/packages/types-aiobotocore-fms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
+[aiobotocore.FMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
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
 [types-aiobotocore-fms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -271,28 +271,36 @@
 paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_fms import FMSClient
 from types_aiobotocore_fms.paginator import (
+    ListAdminAccountsForOrganizationPaginator,
+    ListAdminsManagingAccountPaginator,
     ListAppsListsPaginator,
     ListComplianceStatusPaginator,
     ListMemberAccountsPaginator,
     ListPoliciesPaginator,
     ListProtocolsListsPaginator,
     ListThirdPartyFirewallFirewallPoliciesPaginator,
 )
 
 session = get_session()
 async with session.create_client("fms") as client:
     client: FMSClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
+    list_admin_accounts_for_organization_paginator: ListAdminAccountsForOrganizationPaginator = (
+        client.get_paginator("list_admin_accounts_for_organization")
+    )
+    list_admins_managing_account_paginator: ListAdminsManagingAccountPaginator = (
+        client.get_paginator("list_admins_managing_account")
+    )
     list_apps_lists_paginator: ListAppsListsPaginator = client.get_paginator("list_apps_lists")
     list_compliance_status_paginator: ListComplianceStatusPaginator = client.get_paginator(
         "list_compliance_status"
     )
     list_member_accounts_paginator: ListMemberAccountsPaginator = client.get_paginator(
         "list_member_accounts"
     )
@@ -312,28 +320,33 @@
 `types_aiobotocore_fms.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_fms.literals import (
     AccountRoleStatusType,
     CustomerPolicyScopeIdTypeType,
+    CustomerPolicyStatusType,
     DependentServiceNameType,
     DestinationTypeType,
     FailedItemReasonType,
     FirewallDeploymentModelType,
+    ListAdminAccountsForOrganizationPaginatorName,
+    ListAdminsManagingAccountPaginatorName,
     ListAppsListsPaginatorName,
     ListComplianceStatusPaginatorName,
     ListMemberAccountsPaginatorName,
     ListPoliciesPaginatorName,
     ListProtocolsListsPaginatorName,
     ListThirdPartyFirewallFirewallPoliciesPaginatorName,
     MarketplaceSubscriptionOnboardingStatusType,
     NetworkFirewallOverrideActionType,
+    OrganizationStatusType,
     PolicyComplianceStatusTypeType,
     RemediationActionTypeType,
+    ResourceSetStatusType,
     RuleOrderType,
     SecurityServiceTypeType,
     TargetTypeType,
     ThirdPartyFirewallAssociationStatusType,
     ThirdPartyFirewallType,
     ViolationReasonType,
     FMSServiceName,
@@ -353,116 +366,129 @@
 ### Typed dictionaries
 
 `types_aiobotocore_fms.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_fms.type_defs import (
+    AccountScopeTypeDef,
     ActionTargetTypeDef,
+    AdminAccountSummaryTypeDef,
+    OrganizationalUnitScopeTypeDef,
+    PolicyTypeScopeTypeDef,
+    RegionScopeTypeDef,
     AppTypeDef,
     AssociateAdminAccountRequestRequestTypeDef,
     AssociateThirdPartyFirewallRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateThirdPartyFirewallResponseTypeDef,
     AwsEc2NetworkInterfaceViolationTypeDef,
     PartialMatchTypeDef,
     BatchAssociateResourceRequestRequestTypeDef,
     FailedItemTypeDef,
     BatchDisassociateResourceRequestRequestTypeDef,
     ComplianceViolatorTypeDef,
     DeleteAppsListRequestRequestTypeDef,
     DeletePolicyRequestRequestTypeDef,
     DeleteProtocolsListRequestRequestTypeDef,
     DeleteResourceSetRequestRequestTypeDef,
     DisassociateThirdPartyFirewallRequestRequestTypeDef,
+    DisassociateThirdPartyFirewallResponseTypeDef,
     DiscoveredResourceTypeDef,
     DnsDuplicateRuleGroupViolationTypeDef,
     DnsRuleGroupLimitExceededViolationTypeDef,
     DnsRuleGroupPriorityConflictViolationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluationResultTypeDef,
     ExpectedRouteTypeDef,
     FMSPolicyUpdateFirewallCreationConfigActionTypeDef,
     FirewallSubnetIsOutOfScopeViolationTypeDef,
     FirewallSubnetMissingVPCEndpointViolationTypeDef,
+    GetAdminAccountResponseTypeDef,
+    GetAdminScopeRequestRequestTypeDef,
     GetAppsListRequestRequestTypeDef,
     GetComplianceDetailRequestRequestTypeDef,
+    GetNotificationChannelResponseTypeDef,
     GetPolicyRequestRequestTypeDef,
     GetProtectionStatusRequestRequestTypeDef,
+    GetProtectionStatusResponseTypeDef,
     GetProtocolsListRequestRequestTypeDef,
     ProtocolsListDataTypeDef,
     GetResourceSetRequestRequestTypeDef,
     ResourceSetTypeDef,
     GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef,
+    GetThirdPartyFirewallAssociationStatusResponseTypeDef,
     GetViolationDetailsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef,
+    ListAdminAccountsForOrganizationRequestRequestTypeDef,
+    ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef,
+    ListAdminsManagingAccountRequestRequestTypeDef,
+    ListAdminsManagingAccountResponseTypeDef,
+    ListAppsListsRequestListAppsListsPaginateTypeDef,
     ListAppsListsRequestRequestTypeDef,
+    ListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
     ListComplianceStatusRequestRequestTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
+    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
     ListMemberAccountsRequestRequestTypeDef,
+    ListMemberAccountsResponseTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
     PolicySummaryTypeDef,
+    ListProtocolsListsRequestListProtocolsListsPaginateTypeDef,
     ListProtocolsListsRequestRequestTypeDef,
     ProtocolsListDataSummaryTypeDef,
     ListResourceSetResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListResourceSetsRequestRequestTypeDef,
     ResourceSetSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
     ListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef,
     ThirdPartyFirewallFirewallPolicyTypeDef,
     RouteTypeDef,
     NetworkFirewallMissingExpectedRTViolationTypeDef,
     NetworkFirewallMissingFirewallViolationTypeDef,
     NetworkFirewallMissingSubnetViolationTypeDef,
     StatefulEngineOptionsTypeDef,
     StatelessRuleGroupTypeDef,
     NetworkFirewallPolicyTypeDef,
     NetworkFirewallStatefulRuleGroupOverrideTypeDef,
+    PaginatorConfigTypeDef,
     ThirdPartyFirewallPolicyTypeDef,
     ResourceTagTypeDef,
     PutNotificationChannelRequestRequestTypeDef,
     ThirdPartyFirewallMissingExpectedRouteTableViolationTypeDef,
     ThirdPartyFirewallMissingFirewallViolationTypeDef,
     ThirdPartyFirewallMissingSubnetViolationTypeDef,
+    ResponseMetadataTypeDef,
     SecurityGroupRuleDescriptionTypeDef,
     UntagResourceRequestRequestTypeDef,
     EC2AssociateRouteTableActionTypeDef,
     EC2CopyRouteTableActionTypeDef,
     EC2CreateRouteActionTypeDef,
     EC2CreateRouteTableActionTypeDef,
     EC2DeleteRouteActionTypeDef,
     EC2ReplaceRouteActionTypeDef,
     EC2ReplaceRouteTableAssociationActionTypeDef,
+    ListAdminAccountsForOrganizationResponseTypeDef,
+    AdminScopeTypeDef,
     AppsListDataSummaryTypeDef,
     AppsListDataTypeDef,
-    AssociateThirdPartyFirewallResponseTypeDef,
-    DisassociateThirdPartyFirewallResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAdminAccountResponseTypeDef,
-    GetNotificationChannelResponseTypeDef,
-    GetProtectionStatusResponseTypeDef,
-    GetThirdPartyFirewallAssociationStatusResponseTypeDef,
-    ListMemberAccountsResponseTypeDef,
     AwsEc2InstanceViolationTypeDef,
     BatchAssociateResourceResponseTypeDef,
     BatchDisassociateResourceResponseTypeDef,
     PolicyComplianceDetailTypeDef,
     ListDiscoveredResourcesResponseTypeDef,
     PolicyComplianceStatusTypeDef,
     NetworkFirewallMissingExpectedRoutesViolationTypeDef,
     GetProtocolsListResponseTypeDef,
     PutProtocolsListResponseTypeDef,
     GetResourceSetResponseTypeDef,
     PutResourceSetResponseTypeDef,
-    ListAppsListsRequestListAppsListsPaginateTypeDef,
-    ListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
-    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListProtocolsListsRequestListProtocolsListsPaginateTypeDef,
-    ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
     ListPoliciesResponseTypeDef,
     ListProtocolsListsResponseTypeDef,
     ListResourceSetResourcesResponseTypeDef,
     ListResourceSetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutProtocolsListRequestRequestTypeDef,
     PutResourceSetRequestRequestTypeDef,
@@ -474,14 +500,16 @@
     NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef,
     NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef,
     RouteHasOutOfScopeEndpointViolationTypeDef,
     StatefulRuleGroupTypeDef,
     PolicyOptionTypeDef,
     SecurityGroupRemediationActionTypeDef,
     RemediationActionTypeDef,
+    GetAdminScopeResponseTypeDef,
+    PutAdminAccountRequestRequestTypeDef,
     ListAppsListsResponseTypeDef,
     GetAppsListResponseTypeDef,
     PutAppsListRequestRequestTypeDef,
     PutAppsListResponseTypeDef,
     GetComplianceDetailResponseTypeDef,
     ListComplianceStatusResponseTypeDef,
     NetworkFirewallPolicyDescriptionTypeDef,
@@ -497,54 +525,54 @@
     PossibleRemediationActionsTypeDef,
     ResourceViolationTypeDef,
     ViolationDetailTypeDef,
     GetViolationDetailsResponseTypeDef,
 )
 
 
-def get_structure() -> ActionTargetTypeDef:
+def get_structure() -> AccountScopeTypeDef:
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

### Comparing `types-aiobotocore-fms-2.5.0.post1/README.md` & `types-aiobotocore-fms-2.5.1/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-fms"></a>
 
 # types-aiobotocore-fms
 
 [![PyPI - types-aiobotocore-fms](https://img.shields.io/pypi/v/types-aiobotocore-fms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fms?color=blue)](https://pypistats.org/packages/types-aiobotocore-fms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
+[aiobotocore.FMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
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
 [types-aiobotocore-fms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -238,28 +238,36 @@
 paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_fms import FMSClient
 from types_aiobotocore_fms.paginator import (
+    ListAdminAccountsForOrganizationPaginator,
+    ListAdminsManagingAccountPaginator,
     ListAppsListsPaginator,
     ListComplianceStatusPaginator,
     ListMemberAccountsPaginator,
     ListPoliciesPaginator,
     ListProtocolsListsPaginator,
     ListThirdPartyFirewallFirewallPoliciesPaginator,
 )
 
 session = get_session()
 async with session.create_client("fms") as client:
     client: FMSClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
+    list_admin_accounts_for_organization_paginator: ListAdminAccountsForOrganizationPaginator = (
+        client.get_paginator("list_admin_accounts_for_organization")
+    )
+    list_admins_managing_account_paginator: ListAdminsManagingAccountPaginator = (
+        client.get_paginator("list_admins_managing_account")
+    )
     list_apps_lists_paginator: ListAppsListsPaginator = client.get_paginator("list_apps_lists")
     list_compliance_status_paginator: ListComplianceStatusPaginator = client.get_paginator(
         "list_compliance_status"
     )
     list_member_accounts_paginator: ListMemberAccountsPaginator = client.get_paginator(
         "list_member_accounts"
     )
@@ -279,28 +287,33 @@
 `types_aiobotocore_fms.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_fms.literals import (
     AccountRoleStatusType,
     CustomerPolicyScopeIdTypeType,
+    CustomerPolicyStatusType,
     DependentServiceNameType,
     DestinationTypeType,
     FailedItemReasonType,
     FirewallDeploymentModelType,
+    ListAdminAccountsForOrganizationPaginatorName,
+    ListAdminsManagingAccountPaginatorName,
     ListAppsListsPaginatorName,
     ListComplianceStatusPaginatorName,
     ListMemberAccountsPaginatorName,
     ListPoliciesPaginatorName,
     ListProtocolsListsPaginatorName,
     ListThirdPartyFirewallFirewallPoliciesPaginatorName,
     MarketplaceSubscriptionOnboardingStatusType,
     NetworkFirewallOverrideActionType,
+    OrganizationStatusType,
     PolicyComplianceStatusTypeType,
     RemediationActionTypeType,
+    ResourceSetStatusType,
     RuleOrderType,
     SecurityServiceTypeType,
     TargetTypeType,
     ThirdPartyFirewallAssociationStatusType,
     ThirdPartyFirewallType,
     ViolationReasonType,
     FMSServiceName,
@@ -320,116 +333,129 @@
 ### Typed dictionaries
 
 `types_aiobotocore_fms.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_fms.type_defs import (
+    AccountScopeTypeDef,
     ActionTargetTypeDef,
+    AdminAccountSummaryTypeDef,
+    OrganizationalUnitScopeTypeDef,
+    PolicyTypeScopeTypeDef,
+    RegionScopeTypeDef,
     AppTypeDef,
     AssociateAdminAccountRequestRequestTypeDef,
     AssociateThirdPartyFirewallRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateThirdPartyFirewallResponseTypeDef,
     AwsEc2NetworkInterfaceViolationTypeDef,
     PartialMatchTypeDef,
     BatchAssociateResourceRequestRequestTypeDef,
     FailedItemTypeDef,
     BatchDisassociateResourceRequestRequestTypeDef,
     ComplianceViolatorTypeDef,
     DeleteAppsListRequestRequestTypeDef,
     DeletePolicyRequestRequestTypeDef,
     DeleteProtocolsListRequestRequestTypeDef,
     DeleteResourceSetRequestRequestTypeDef,
     DisassociateThirdPartyFirewallRequestRequestTypeDef,
+    DisassociateThirdPartyFirewallResponseTypeDef,
     DiscoveredResourceTypeDef,
     DnsDuplicateRuleGroupViolationTypeDef,
     DnsRuleGroupLimitExceededViolationTypeDef,
     DnsRuleGroupPriorityConflictViolationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluationResultTypeDef,
     ExpectedRouteTypeDef,
     FMSPolicyUpdateFirewallCreationConfigActionTypeDef,
     FirewallSubnetIsOutOfScopeViolationTypeDef,
     FirewallSubnetMissingVPCEndpointViolationTypeDef,
+    GetAdminAccountResponseTypeDef,
+    GetAdminScopeRequestRequestTypeDef,
     GetAppsListRequestRequestTypeDef,
     GetComplianceDetailRequestRequestTypeDef,
+    GetNotificationChannelResponseTypeDef,
     GetPolicyRequestRequestTypeDef,
     GetProtectionStatusRequestRequestTypeDef,
+    GetProtectionStatusResponseTypeDef,
     GetProtocolsListRequestRequestTypeDef,
     ProtocolsListDataTypeDef,
     GetResourceSetRequestRequestTypeDef,
     ResourceSetTypeDef,
     GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef,
+    GetThirdPartyFirewallAssociationStatusResponseTypeDef,
     GetViolationDetailsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef,
+    ListAdminAccountsForOrganizationRequestRequestTypeDef,
+    ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef,
+    ListAdminsManagingAccountRequestRequestTypeDef,
+    ListAdminsManagingAccountResponseTypeDef,
+    ListAppsListsRequestListAppsListsPaginateTypeDef,
     ListAppsListsRequestRequestTypeDef,
+    ListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
     ListComplianceStatusRequestRequestTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
+    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
     ListMemberAccountsRequestRequestTypeDef,
+    ListMemberAccountsResponseTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
     PolicySummaryTypeDef,
+    ListProtocolsListsRequestListProtocolsListsPaginateTypeDef,
     ListProtocolsListsRequestRequestTypeDef,
     ProtocolsListDataSummaryTypeDef,
     ListResourceSetResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListResourceSetsRequestRequestTypeDef,
     ResourceSetSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
     ListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef,
     ThirdPartyFirewallFirewallPolicyTypeDef,
     RouteTypeDef,
     NetworkFirewallMissingExpectedRTViolationTypeDef,
     NetworkFirewallMissingFirewallViolationTypeDef,
     NetworkFirewallMissingSubnetViolationTypeDef,
     StatefulEngineOptionsTypeDef,
     StatelessRuleGroupTypeDef,
     NetworkFirewallPolicyTypeDef,
     NetworkFirewallStatefulRuleGroupOverrideTypeDef,
+    PaginatorConfigTypeDef,
     ThirdPartyFirewallPolicyTypeDef,
     ResourceTagTypeDef,
     PutNotificationChannelRequestRequestTypeDef,
     ThirdPartyFirewallMissingExpectedRouteTableViolationTypeDef,
     ThirdPartyFirewallMissingFirewallViolationTypeDef,
     ThirdPartyFirewallMissingSubnetViolationTypeDef,
+    ResponseMetadataTypeDef,
     SecurityGroupRuleDescriptionTypeDef,
     UntagResourceRequestRequestTypeDef,
     EC2AssociateRouteTableActionTypeDef,
     EC2CopyRouteTableActionTypeDef,
     EC2CreateRouteActionTypeDef,
     EC2CreateRouteTableActionTypeDef,
     EC2DeleteRouteActionTypeDef,
     EC2ReplaceRouteActionTypeDef,
     EC2ReplaceRouteTableAssociationActionTypeDef,
+    ListAdminAccountsForOrganizationResponseTypeDef,
+    AdminScopeTypeDef,
     AppsListDataSummaryTypeDef,
     AppsListDataTypeDef,
-    AssociateThirdPartyFirewallResponseTypeDef,
-    DisassociateThirdPartyFirewallResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAdminAccountResponseTypeDef,
-    GetNotificationChannelResponseTypeDef,
-    GetProtectionStatusResponseTypeDef,
-    GetThirdPartyFirewallAssociationStatusResponseTypeDef,
-    ListMemberAccountsResponseTypeDef,
     AwsEc2InstanceViolationTypeDef,
     BatchAssociateResourceResponseTypeDef,
     BatchDisassociateResourceResponseTypeDef,
     PolicyComplianceDetailTypeDef,
     ListDiscoveredResourcesResponseTypeDef,
     PolicyComplianceStatusTypeDef,
     NetworkFirewallMissingExpectedRoutesViolationTypeDef,
     GetProtocolsListResponseTypeDef,
     PutProtocolsListResponseTypeDef,
     GetResourceSetResponseTypeDef,
     PutResourceSetResponseTypeDef,
-    ListAppsListsRequestListAppsListsPaginateTypeDef,
-    ListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
-    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListProtocolsListsRequestListProtocolsListsPaginateTypeDef,
-    ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
     ListPoliciesResponseTypeDef,
     ListProtocolsListsResponseTypeDef,
     ListResourceSetResourcesResponseTypeDef,
     ListResourceSetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutProtocolsListRequestRequestTypeDef,
     PutResourceSetRequestRequestTypeDef,
@@ -441,14 +467,16 @@
     NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef,
     NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef,
     RouteHasOutOfScopeEndpointViolationTypeDef,
     StatefulRuleGroupTypeDef,
     PolicyOptionTypeDef,
     SecurityGroupRemediationActionTypeDef,
     RemediationActionTypeDef,
+    GetAdminScopeResponseTypeDef,
+    PutAdminAccountRequestRequestTypeDef,
     ListAppsListsResponseTypeDef,
     GetAppsListResponseTypeDef,
     PutAppsListRequestRequestTypeDef,
     PutAppsListResponseTypeDef,
     GetComplianceDetailResponseTypeDef,
     ListComplianceStatusResponseTypeDef,
     NetworkFirewallPolicyDescriptionTypeDef,
@@ -464,54 +492,54 @@
     PossibleRemediationActionsTypeDef,
     ResourceViolationTypeDef,
     ViolationDetailTypeDef,
     GetViolationDetailsResponseTypeDef,
 )
 
 
-def get_structure() -> ActionTargetTypeDef:
+def get_structure() -> AccountScopeTypeDef:
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

### Comparing `types-aiobotocore-fms-2.5.0.post1/setup.py` & `types-aiobotocore-fms-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-fms.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-fms",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_fms"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.FMS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.FMS 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/",
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

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/__main__.py` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.FMS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.FMS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS\nOther"
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

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/client.py` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/client.py`

 * *Files 3% similar despite different names*

```diff
@@ -19,38 +19,44 @@
 from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import ThirdPartyFirewallType
 from .paginator import (
+    ListAdminAccountsForOrganizationPaginator,
+    ListAdminsManagingAccountPaginator,
     ListAppsListsPaginator,
     ListComplianceStatusPaginator,
     ListMemberAccountsPaginator,
     ListPoliciesPaginator,
     ListProtocolsListsPaginator,
     ListThirdPartyFirewallFirewallPoliciesPaginator,
 )
 from .type_defs import (
+    AdminScopeTypeDef,
     AppsListDataTypeDef,
     AssociateThirdPartyFirewallResponseTypeDef,
     BatchAssociateResourceResponseTypeDef,
     BatchDisassociateResourceResponseTypeDef,
     DisassociateThirdPartyFirewallResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     GetAdminAccountResponseTypeDef,
+    GetAdminScopeResponseTypeDef,
     GetAppsListResponseTypeDef,
     GetComplianceDetailResponseTypeDef,
     GetNotificationChannelResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetProtectionStatusResponseTypeDef,
     GetProtocolsListResponseTypeDef,
     GetResourceSetResponseTypeDef,
     GetThirdPartyFirewallAssociationStatusResponseTypeDef,
     GetViolationDetailsResponseTypeDef,
+    ListAdminAccountsForOrganizationResponseTypeDef,
+    ListAdminsManagingAccountResponseTypeDef,
     ListAppsListsResponseTypeDef,
     ListComplianceStatusResponseTypeDef,
     ListDiscoveredResourcesResponseTypeDef,
     ListMemberAccountsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListProtocolsListsResponseTypeDef,
     ListResourceSetResourcesResponseTypeDef,
@@ -109,15 +115,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#exceptions)
         """
 
     async def associate_admin_account(self, *, AdminAccount: str) -> EmptyResponseMetadataTypeDef:
         """
-        Sets the Firewall Manager administrator account.
+        Sets a Firewall Manager default administrator account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.associate_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#associate_admin_account)
         """
 
     async def associate_third_party_firewall(
         self, *, ThirdPartyFirewall: ThirdPartyFirewallType
@@ -208,16 +214,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.delete_resource_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#delete_resource_set)
         """
 
     async def disassociate_admin_account(self) -> EmptyResponseMetadataTypeDef:
         """
-        Disassociates the account that has been set as the Firewall Manager
-        administrator account.
+        Disassociates an Firewall Manager administrator account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.disassociate_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#disassociate_admin_account)
         """
 
     async def disassociate_third_party_firewall(
         self, *, ThirdPartyFirewall: ThirdPartyFirewallType
@@ -243,20 +248,28 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#generate_presigned_url)
         """
 
     async def get_admin_account(self) -> GetAdminAccountResponseTypeDef:
         """
         Returns the Organizations account that is associated with Firewall Manager as
-        the Firewall Manager administrator.
+        the Firewall Manager default administrator.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_admin_account)
         """
 
+    async def get_admin_scope(self, *, AdminAccount: str) -> GetAdminScopeResponseTypeDef:
+        """
+        Returns information about the specified account's administrative scope.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_admin_scope)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_admin_scope)
+        """
+
     async def get_apps_list(
         self, *, ListId: str, DefaultList: bool = ...
     ) -> GetAppsListResponseTypeDef:
         """
         Returns information about the specified Firewall Manager applications list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_apps_list)
@@ -344,14 +357,36 @@
         Retrieves violations for a resource based on the specified Firewall Manager
         policy and Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_violation_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_violation_details)
         """
 
+    async def list_admin_accounts_for_organization(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListAdminAccountsForOrganizationResponseTypeDef:
+        """
+        Returns a `AdminAccounts` object that lists the Firewall Manager administrators
+        within the organization that are onboarded to Firewall Manager by
+        AssociateAdminAccount.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_admin_accounts_for_organization)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#list_admin_accounts_for_organization)
+        """
+
+    async def list_admins_managing_account(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListAdminsManagingAccountResponseTypeDef:
+        """
+        Lists the accounts that are managing the specified Organizations member account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_admins_managing_account)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#list_admins_managing_account)
+        """
+
     async def list_apps_lists(
         self, *, MaxResults: int, DefaultLists: bool = ..., NextToken: str = ...
     ) -> ListAppsListsResponseTypeDef:
         """
         Returns an array of `AppsListDataSummary` objects.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_apps_lists)
@@ -452,14 +487,24 @@
         Retrieves a list of all of the third-party firewall policies that are associated
         with the third-party firewall administrator's account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_third_party_firewall_firewall_policies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#list_third_party_firewall_firewall_policies)
         """
 
+    async def put_admin_account(
+        self, *, AdminAccount: str, AdminScope: AdminScopeTypeDef = ...
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Creates or updates an Firewall Manager administrator account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_admin_account)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#put_admin_account)
+        """
+
     async def put_apps_list(
         self, *, AppsList: AppsListDataTypeDef, TagList: Sequence[TagTypeDef] = ...
     ) -> PutAppsListResponseTypeDef:
         """
         Creates an Firewall Manager applications list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_apps_list)
@@ -522,14 +567,32 @@
         Removes one or more tags from an Amazon Web Services resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#untag_resource)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_admin_accounts_for_organization"]
+    ) -> ListAdminAccountsForOrganizationPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_admins_managing_account"]
+    ) -> ListAdminsManagingAccountPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["list_apps_lists"]) -> ListAppsListsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_paginator)
         """
 
     @overload
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/client.pyi` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/client.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -19,38 +19,44 @@
 from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import ThirdPartyFirewallType
 from .paginator import (
+    ListAdminAccountsForOrganizationPaginator,
+    ListAdminsManagingAccountPaginator,
     ListAppsListsPaginator,
     ListComplianceStatusPaginator,
     ListMemberAccountsPaginator,
     ListPoliciesPaginator,
     ListProtocolsListsPaginator,
     ListThirdPartyFirewallFirewallPoliciesPaginator,
 )
 from .type_defs import (
+    AdminScopeTypeDef,
     AppsListDataTypeDef,
     AssociateThirdPartyFirewallResponseTypeDef,
     BatchAssociateResourceResponseTypeDef,
     BatchDisassociateResourceResponseTypeDef,
     DisassociateThirdPartyFirewallResponseTypeDef,
     EmptyResponseMetadataTypeDef,
     GetAdminAccountResponseTypeDef,
+    GetAdminScopeResponseTypeDef,
     GetAppsListResponseTypeDef,
     GetComplianceDetailResponseTypeDef,
     GetNotificationChannelResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetProtectionStatusResponseTypeDef,
     GetProtocolsListResponseTypeDef,
     GetResourceSetResponseTypeDef,
     GetThirdPartyFirewallAssociationStatusResponseTypeDef,
     GetViolationDetailsResponseTypeDef,
+    ListAdminAccountsForOrganizationResponseTypeDef,
+    ListAdminsManagingAccountResponseTypeDef,
     ListAppsListsResponseTypeDef,
     ListComplianceStatusResponseTypeDef,
     ListDiscoveredResourcesResponseTypeDef,
     ListMemberAccountsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListProtocolsListsResponseTypeDef,
     ListResourceSetResourcesResponseTypeDef,
@@ -104,15 +110,15 @@
         FMSClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#exceptions)
         """
     async def associate_admin_account(self, *, AdminAccount: str) -> EmptyResponseMetadataTypeDef:
         """
-        Sets the Firewall Manager administrator account.
+        Sets a Firewall Manager default administrator account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.associate_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#associate_admin_account)
         """
     async def associate_third_party_firewall(
         self, *, ThirdPartyFirewall: ThirdPartyFirewallType
     ) -> AssociateThirdPartyFirewallResponseTypeDef:
@@ -192,16 +198,15 @@
         Deletes the specified  ResourceSet.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.delete_resource_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#delete_resource_set)
         """
     async def disassociate_admin_account(self) -> EmptyResponseMetadataTypeDef:
         """
-        Disassociates the account that has been set as the Firewall Manager
-        administrator account.
+        Disassociates an Firewall Manager administrator account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.disassociate_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#disassociate_admin_account)
         """
     async def disassociate_third_party_firewall(
         self, *, ThirdPartyFirewall: ThirdPartyFirewallType
     ) -> DisassociateThirdPartyFirewallResponseTypeDef:
@@ -224,19 +229,26 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#generate_presigned_url)
         """
     async def get_admin_account(self) -> GetAdminAccountResponseTypeDef:
         """
         Returns the Organizations account that is associated with Firewall Manager as
-        the Firewall Manager administrator.
+        the Firewall Manager default administrator.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_admin_account)
         """
+    async def get_admin_scope(self, *, AdminAccount: str) -> GetAdminScopeResponseTypeDef:
+        """
+        Returns information about the specified account's administrative scope.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_admin_scope)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_admin_scope)
+        """
     async def get_apps_list(
         self, *, ListId: str, DefaultList: bool = ...
     ) -> GetAppsListResponseTypeDef:
         """
         Returns information about the specified Firewall Manager applications list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_apps_list)
@@ -315,14 +327,34 @@
         """
         Retrieves violations for a resource based on the specified Firewall Manager
         policy and Amazon Web Services account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_violation_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_violation_details)
         """
+    async def list_admin_accounts_for_organization(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListAdminAccountsForOrganizationResponseTypeDef:
+        """
+        Returns a `AdminAccounts` object that lists the Firewall Manager administrators
+        within the organization that are onboarded to Firewall Manager by
+        AssociateAdminAccount.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_admin_accounts_for_organization)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#list_admin_accounts_for_organization)
+        """
+    async def list_admins_managing_account(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListAdminsManagingAccountResponseTypeDef:
+        """
+        Lists the accounts that are managing the specified Organizations member account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_admins_managing_account)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#list_admins_managing_account)
+        """
     async def list_apps_lists(
         self, *, MaxResults: int, DefaultLists: bool = ..., NextToken: str = ...
     ) -> ListAppsListsResponseTypeDef:
         """
         Returns an array of `AppsListDataSummary` objects.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_apps_lists)
@@ -413,14 +445,23 @@
         """
         Retrieves a list of all of the third-party firewall policies that are associated
         with the third-party firewall administrator's account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.list_third_party_firewall_firewall_policies)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#list_third_party_firewall_firewall_policies)
         """
+    async def put_admin_account(
+        self, *, AdminAccount: str, AdminScope: AdminScopeTypeDef = ...
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Creates or updates an Firewall Manager administrator account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_admin_account)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#put_admin_account)
+        """
     async def put_apps_list(
         self, *, AppsList: AppsListDataTypeDef, TagList: Sequence[TagTypeDef] = ...
     ) -> PutAppsListResponseTypeDef:
         """
         Creates an Firewall Manager applications list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.put_apps_list)
@@ -476,14 +517,30 @@
         """
         Removes one or more tags from an Amazon Web Services resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#untag_resource)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["list_admin_accounts_for_organization"]
+    ) -> ListAdminAccountsForOrganizationPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_admins_managing_account"]
+    ) -> ListAdminsManagingAccountPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["list_apps_lists"]) -> ListAppsListsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/client/#get_paginator)
         """
     @overload
     def get_paginator(
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/literals.py` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,28 +18,33 @@
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AccountRoleStatusType",
     "CustomerPolicyScopeIdTypeType",
+    "CustomerPolicyStatusType",
     "DependentServiceNameType",
     "DestinationTypeType",
     "FailedItemReasonType",
     "FirewallDeploymentModelType",
+    "ListAdminAccountsForOrganizationPaginatorName",
+    "ListAdminsManagingAccountPaginatorName",
     "ListAppsListsPaginatorName",
     "ListComplianceStatusPaginatorName",
     "ListMemberAccountsPaginatorName",
     "ListPoliciesPaginatorName",
     "ListProtocolsListsPaginatorName",
     "ListThirdPartyFirewallFirewallPoliciesPaginatorName",
     "MarketplaceSubscriptionOnboardingStatusType",
     "NetworkFirewallOverrideActionType",
+    "OrganizationStatusType",
     "PolicyComplianceStatusTypeType",
     "RemediationActionTypeType",
+    "ResourceSetStatusType",
     "RuleOrderType",
     "SecurityServiceTypeType",
     "TargetTypeType",
     "ThirdPartyFirewallAssociationStatusType",
     "ThirdPartyFirewallType",
     "ViolationReasonType",
     "FMSServiceName",
@@ -48,37 +53,44 @@
     "PaginatorName",
     "RegionName",
 )
 
 
 AccountRoleStatusType = Literal["CREATING", "DELETED", "DELETING", "PENDING_DELETION", "READY"]
 CustomerPolicyScopeIdTypeType = Literal["ACCOUNT", "ORG_UNIT"]
+CustomerPolicyStatusType = Literal["ACTIVE", "OUT_OF_ADMIN_SCOPE"]
 DependentServiceNameType = Literal["AWSCONFIG", "AWSSHIELD_ADVANCED", "AWSVPC", "AWSWAF"]
 DestinationTypeType = Literal["IPV4", "IPV6", "PREFIX_LIST"]
 FailedItemReasonType = Literal[
     "NOT_VALID_ACCOUNT_ID",
     "NOT_VALID_ARN",
     "NOT_VALID_PARTITION",
     "NOT_VALID_REGION",
     "NOT_VALID_RESOURCE_TYPE",
     "NOT_VALID_SERVICE",
 ]
 FirewallDeploymentModelType = Literal["CENTRALIZED", "DISTRIBUTED"]
+ListAdminAccountsForOrganizationPaginatorName = Literal["list_admin_accounts_for_organization"]
+ListAdminsManagingAccountPaginatorName = Literal["list_admins_managing_account"]
 ListAppsListsPaginatorName = Literal["list_apps_lists"]
 ListComplianceStatusPaginatorName = Literal["list_compliance_status"]
 ListMemberAccountsPaginatorName = Literal["list_member_accounts"]
 ListPoliciesPaginatorName = Literal["list_policies"]
 ListProtocolsListsPaginatorName = Literal["list_protocols_lists"]
 ListThirdPartyFirewallFirewallPoliciesPaginatorName = Literal[
     "list_third_party_firewall_firewall_policies"
 ]
 MarketplaceSubscriptionOnboardingStatusType = Literal["COMPLETE", "NOT_COMPLETE", "NO_SUBSCRIPTION"]
 NetworkFirewallOverrideActionType = Literal["DROP_TO_ALERT"]
+OrganizationStatusType = Literal[
+    "OFFBOARDING", "OFFBOARDING_COMPLETE", "ONBOARDING", "ONBOARDING_COMPLETE"
+]
 PolicyComplianceStatusTypeType = Literal["COMPLIANT", "NON_COMPLIANT"]
 RemediationActionTypeType = Literal["MODIFY", "REMOVE"]
+ResourceSetStatusType = Literal["ACTIVE", "OUT_OF_ADMIN_SCOPE"]
 RuleOrderType = Literal["DEFAULT_ACTION_ORDER", "STRICT_ORDER"]
 SecurityServiceTypeType = Literal[
     "DNS_FIREWALL",
     "IMPORT_NETWORK_FIREWALL",
     "NETWORK_FIREWALL",
     "SECURITY_GROUPS_COMMON",
     "SECURITY_GROUPS_CONTENT_AUDIT",
@@ -193,14 +205,15 @@
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
@@ -279,14 +292,15 @@
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
@@ -297,14 +311,15 @@
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
@@ -340,14 +355,15 @@
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
@@ -366,16 +382,19 @@
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
@@ -459,15 +478,17 @@
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
@@ -486,35 +507,41 @@
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
+    "list_admin_accounts_for_organization",
+    "list_admins_managing_account",
     "list_apps_lists",
     "list_compliance_status",
     "list_member_accounts",
     "list_policies",
     "list_protocols_lists",
     "list_third_party_firewall_firewall_policies",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/literals.pyi` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -17,28 +17,33 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AccountRoleStatusType",
     "CustomerPolicyScopeIdTypeType",
+    "CustomerPolicyStatusType",
     "DependentServiceNameType",
     "DestinationTypeType",
     "FailedItemReasonType",
     "FirewallDeploymentModelType",
+    "ListAdminAccountsForOrganizationPaginatorName",
+    "ListAdminsManagingAccountPaginatorName",
     "ListAppsListsPaginatorName",
     "ListComplianceStatusPaginatorName",
     "ListMemberAccountsPaginatorName",
     "ListPoliciesPaginatorName",
     "ListProtocolsListsPaginatorName",
     "ListThirdPartyFirewallFirewallPoliciesPaginatorName",
     "MarketplaceSubscriptionOnboardingStatusType",
     "NetworkFirewallOverrideActionType",
+    "OrganizationStatusType",
     "PolicyComplianceStatusTypeType",
     "RemediationActionTypeType",
+    "ResourceSetStatusType",
     "RuleOrderType",
     "SecurityServiceTypeType",
     "TargetTypeType",
     "ThirdPartyFirewallAssociationStatusType",
     "ThirdPartyFirewallType",
     "ViolationReasonType",
     "FMSServiceName",
@@ -46,37 +51,44 @@
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 AccountRoleStatusType = Literal["CREATING", "DELETED", "DELETING", "PENDING_DELETION", "READY"]
 CustomerPolicyScopeIdTypeType = Literal["ACCOUNT", "ORG_UNIT"]
+CustomerPolicyStatusType = Literal["ACTIVE", "OUT_OF_ADMIN_SCOPE"]
 DependentServiceNameType = Literal["AWSCONFIG", "AWSSHIELD_ADVANCED", "AWSVPC", "AWSWAF"]
 DestinationTypeType = Literal["IPV4", "IPV6", "PREFIX_LIST"]
 FailedItemReasonType = Literal[
     "NOT_VALID_ACCOUNT_ID",
     "NOT_VALID_ARN",
     "NOT_VALID_PARTITION",
     "NOT_VALID_REGION",
     "NOT_VALID_RESOURCE_TYPE",
     "NOT_VALID_SERVICE",
 ]
 FirewallDeploymentModelType = Literal["CENTRALIZED", "DISTRIBUTED"]
+ListAdminAccountsForOrganizationPaginatorName = Literal["list_admin_accounts_for_organization"]
+ListAdminsManagingAccountPaginatorName = Literal["list_admins_managing_account"]
 ListAppsListsPaginatorName = Literal["list_apps_lists"]
 ListComplianceStatusPaginatorName = Literal["list_compliance_status"]
 ListMemberAccountsPaginatorName = Literal["list_member_accounts"]
 ListPoliciesPaginatorName = Literal["list_policies"]
 ListProtocolsListsPaginatorName = Literal["list_protocols_lists"]
 ListThirdPartyFirewallFirewallPoliciesPaginatorName = Literal[
     "list_third_party_firewall_firewall_policies"
 ]
 MarketplaceSubscriptionOnboardingStatusType = Literal["COMPLETE", "NOT_COMPLETE", "NO_SUBSCRIPTION"]
 NetworkFirewallOverrideActionType = Literal["DROP_TO_ALERT"]
+OrganizationStatusType = Literal[
+    "OFFBOARDING", "OFFBOARDING_COMPLETE", "ONBOARDING", "ONBOARDING_COMPLETE"
+]
 PolicyComplianceStatusTypeType = Literal["COMPLIANT", "NON_COMPLIANT"]
 RemediationActionTypeType = Literal["MODIFY", "REMOVE"]
+ResourceSetStatusType = Literal["ACTIVE", "OUT_OF_ADMIN_SCOPE"]
 RuleOrderType = Literal["DEFAULT_ACTION_ORDER", "STRICT_ORDER"]
 SecurityServiceTypeType = Literal[
     "DNS_FIREWALL",
     "IMPORT_NETWORK_FIREWALL",
     "NETWORK_FIREWALL",
     "SECURITY_GROUPS_COMMON",
     "SECURITY_GROUPS_CONTENT_AUDIT",
@@ -191,14 +203,15 @@
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
@@ -277,14 +290,15 @@
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
@@ -295,14 +309,15 @@
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
@@ -338,14 +353,15 @@
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
@@ -364,16 +380,19 @@
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
@@ -457,15 +476,17 @@
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
@@ -484,35 +505,41 @@
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal[
+    "list_admin_accounts_for_organization",
+    "list_admins_managing_account",
     "list_apps_lists",
     "list_compliance_status",
     "list_member_accounts",
     "list_policies",
     "list_protocols_lists",
     "list_third_party_firewall_firewall_policies",
 ]
 RegionName = Literal[
     "af-south-1",
     "ap-east-1",
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-northeast-3",
     "ap-south-1",
+    "ap-south-2",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
+    "ap-southeast-4",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/paginator.py` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/paginator.py`

 * *Files 15% similar despite different names*

```diff
@@ -6,58 +6,59 @@
 Usage::
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_fms.client import FMSClient
     from types_aiobotocore_fms.paginator import (
+        ListAdminAccountsForOrganizationPaginator,
+        ListAdminsManagingAccountPaginator,
         ListAppsListsPaginator,
         ListComplianceStatusPaginator,
         ListMemberAccountsPaginator,
         ListPoliciesPaginator,
         ListProtocolsListsPaginator,
         ListThirdPartyFirewallFirewallPoliciesPaginator,
     )
 
     session = get_session()
     with session.create_client("fms") as client:
         client: FMSClient
 
+        list_admin_accounts_for_organization_paginator: ListAdminAccountsForOrganizationPaginator = client.get_paginator("list_admin_accounts_for_organization")
+        list_admins_managing_account_paginator: ListAdminsManagingAccountPaginator = client.get_paginator("list_admins_managing_account")
         list_apps_lists_paginator: ListAppsListsPaginator = client.get_paginator("list_apps_lists")
         list_compliance_status_paginator: ListComplianceStatusPaginator = client.get_paginator("list_compliance_status")
         list_member_accounts_paginator: ListMemberAccountsPaginator = client.get_paginator("list_member_accounts")
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
         list_protocols_lists_paginator: ListProtocolsListsPaginator = client.get_paginator("list_protocols_lists")
         list_third_party_firewall_firewall_policies_paginator: ListThirdPartyFirewallFirewallPoliciesPaginator = client.get_paginator("list_third_party_firewall_firewall_policies")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ThirdPartyFirewallType
 from .type_defs import (
+    ListAdminAccountsForOrganizationResponseTypeDef,
+    ListAdminsManagingAccountResponseTypeDef,
     ListAppsListsResponseTypeDef,
     ListComplianceStatusResponseTypeDef,
     ListMemberAccountsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListProtocolsListsResponseTypeDef,
     ListThirdPartyFirewallFirewallPoliciesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
+    "ListAdminAccountsForOrganizationPaginator",
+    "ListAdminsManagingAccountPaginator",
     "ListAppsListsPaginator",
     "ListComplianceStatusPaginator",
     "ListMemberAccountsPaginator",
     "ListPoliciesPaginator",
     "ListProtocolsListsPaginator",
     "ListThirdPartyFirewallFirewallPoliciesPaginator",
 )
@@ -69,82 +70,112 @@
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
 
+class ListAdminAccountsForOrganizationPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminAccountsForOrganization)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminaccountsfororganizationpaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListAdminAccountsForOrganizationResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminAccountsForOrganization.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminaccountsfororganizationpaginator)
+        """
+
+
+class ListAdminsManagingAccountPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminsManagingAccount)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminsmanagingaccountpaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListAdminsManagingAccountResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminsManagingAccount.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminsmanagingaccountpaginator)
+        """
+
+
 class ListAppsListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAppsLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listappslistspaginator)
     """
 
     def paginate(
-        self, *, DefaultLists: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DefaultLists: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppsListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAppsLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listappslistspaginator)
         """
 
 
 class ListComplianceStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListComplianceStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listcompliancestatuspaginator)
     """
 
     def paginate(
-        self, *, PolicyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PolicyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComplianceStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListComplianceStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listcompliancestatuspaginator)
         """
 
 
 class ListMemberAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListMemberAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listmemberaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMemberAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListMemberAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listmemberaccountspaginator)
         """
 
 
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listpoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listpoliciespaginator)
         """
 
 
 class ListProtocolsListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListProtocolsLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listprotocolslistspaginator)
     """
 
     def paginate(
-        self, *, DefaultLists: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DefaultLists: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtocolsListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListProtocolsLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listprotocolslistspaginator)
         """
 
 
@@ -154,13 +185,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listthirdpartyfirewallfirewallpoliciespaginator)
     """
 
     def paginate(
         self,
         *,
         ThirdPartyFirewall: ThirdPartyFirewallType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThirdPartyFirewallFirewallPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListThirdPartyFirewallFirewallPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listthirdpartyfirewallfirewallpoliciespaginator)
         """
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/paginator.pyi` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/paginator.pyi`

 * *Files 21% similar despite different names*

```diff
@@ -6,57 +6,59 @@
 Usage::
 
     ```python
     from aiobotocore.session import get_session
 
     from types_aiobotocore_fms.client import FMSClient
     from types_aiobotocore_fms.paginator import (
+        ListAdminAccountsForOrganizationPaginator,
+        ListAdminsManagingAccountPaginator,
         ListAppsListsPaginator,
         ListComplianceStatusPaginator,
         ListMemberAccountsPaginator,
         ListPoliciesPaginator,
         ListProtocolsListsPaginator,
         ListThirdPartyFirewallFirewallPoliciesPaginator,
     )
 
     session = get_session()
     with session.create_client("fms") as client:
         client: FMSClient
 
+        list_admin_accounts_for_organization_paginator: ListAdminAccountsForOrganizationPaginator = client.get_paginator("list_admin_accounts_for_organization")
+        list_admins_managing_account_paginator: ListAdminsManagingAccountPaginator = client.get_paginator("list_admins_managing_account")
         list_apps_lists_paginator: ListAppsListsPaginator = client.get_paginator("list_apps_lists")
         list_compliance_status_paginator: ListComplianceStatusPaginator = client.get_paginator("list_compliance_status")
         list_member_accounts_paginator: ListMemberAccountsPaginator = client.get_paginator("list_member_accounts")
         list_policies_paginator: ListPoliciesPaginator = client.get_paginator("list_policies")
         list_protocols_lists_paginator: ListProtocolsListsPaginator = client.get_paginator("list_protocols_lists")
         list_third_party_firewall_firewall_policies_paginator: ListThirdPartyFirewallFirewallPoliciesPaginator = client.get_paginator("list_third_party_firewall_firewall_policies")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ThirdPartyFirewallType
 from .type_defs import (
+    ListAdminAccountsForOrganizationResponseTypeDef,
+    ListAdminsManagingAccountResponseTypeDef,
     ListAppsListsResponseTypeDef,
     ListComplianceStatusResponseTypeDef,
     ListMemberAccountsResponseTypeDef,
     ListPoliciesResponseTypeDef,
     ListProtocolsListsResponseTypeDef,
     ListThirdPartyFirewallFirewallPoliciesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
+    "ListAdminAccountsForOrganizationPaginator",
+    "ListAdminsManagingAccountPaginator",
     "ListAppsListsPaginator",
     "ListComplianceStatusPaginator",
     "ListMemberAccountsPaginator",
     "ListPoliciesPaginator",
     "ListProtocolsListsPaginator",
     "ListThirdPartyFirewallFirewallPoliciesPaginator",
 )
@@ -65,78 +67,106 @@
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+class ListAdminAccountsForOrganizationPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminAccountsForOrganization)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminaccountsfororganizationpaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListAdminAccountsForOrganizationResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminAccountsForOrganization.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminaccountsfororganizationpaginator)
+        """
+
+class ListAdminsManagingAccountPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminsManagingAccount)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminsmanagingaccountpaginator)
+    """
+
+    def paginate(
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListAdminsManagingAccountResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAdminsManagingAccount.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listadminsmanagingaccountpaginator)
+        """
+
 class ListAppsListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAppsLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listappslistspaginator)
     """
 
     def paginate(
-        self, *, DefaultLists: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DefaultLists: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAppsListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListAppsLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listappslistspaginator)
         """
 
 class ListComplianceStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListComplianceStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listcompliancestatuspaginator)
     """
 
     def paginate(
-        self, *, PolicyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PolicyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComplianceStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListComplianceStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listcompliancestatuspaginator)
         """
 
 class ListMemberAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListMemberAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listmemberaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMemberAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListMemberAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listmemberaccountspaginator)
         """
 
 class ListPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listpoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listpoliciespaginator)
         """
 
 class ListProtocolsListsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListProtocolsLists)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listprotocolslistspaginator)
     """
 
     def paginate(
-        self, *, DefaultLists: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DefaultLists: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProtocolsListsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListProtocolsLists.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listprotocolslistspaginator)
         """
 
 class ListThirdPartyFirewallFirewallPoliciesPaginator(AioPaginator):
@@ -145,13 +175,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listthirdpartyfirewallfirewallpoliciespaginator)
     """
 
     def paginate(
         self,
         *,
         ThirdPartyFirewall: ThirdPartyFirewallType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListThirdPartyFirewallFirewallPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS.Paginator.ListThirdPartyFirewallFirewallPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/paginators/#listthirdpartyfirewallfirewallpoliciespaginator)
         """
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/type_defs.py` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -2,33 +2,36 @@
 Type annotations for fms service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_fms.type_defs import ActionTargetTypeDef
+    from types_aiobotocore_fms.type_defs import AccountScopeTypeDef
 
-    data: ActionTargetTypeDef = {...}
+    data: AccountScopeTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
 from .literals import (
     AccountRoleStatusType,
     CustomerPolicyScopeIdTypeType,
+    CustomerPolicyStatusType,
     DependentServiceNameType,
     DestinationTypeType,
     FailedItemReasonType,
     FirewallDeploymentModelType,
     MarketplaceSubscriptionOnboardingStatusType,
+    OrganizationStatusType,
     PolicyComplianceStatusTypeType,
     RemediationActionTypeType,
+    ResourceSetStatusType,
     RuleOrderType,
     SecurityServiceTypeType,
     TargetTypeType,
     ThirdPartyFirewallAssociationStatusType,
     ThirdPartyFirewallType,
     ViolationReasonType,
 )
@@ -40,116 +43,129 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
+    "AccountScopeTypeDef",
     "ActionTargetTypeDef",
+    "AdminAccountSummaryTypeDef",
+    "OrganizationalUnitScopeTypeDef",
+    "PolicyTypeScopeTypeDef",
+    "RegionScopeTypeDef",
     "AppTypeDef",
     "AssociateAdminAccountRequestRequestTypeDef",
     "AssociateThirdPartyFirewallRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateThirdPartyFirewallResponseTypeDef",
     "AwsEc2NetworkInterfaceViolationTypeDef",
     "PartialMatchTypeDef",
     "BatchAssociateResourceRequestRequestTypeDef",
     "FailedItemTypeDef",
     "BatchDisassociateResourceRequestRequestTypeDef",
     "ComplianceViolatorTypeDef",
     "DeleteAppsListRequestRequestTypeDef",
     "DeletePolicyRequestRequestTypeDef",
     "DeleteProtocolsListRequestRequestTypeDef",
     "DeleteResourceSetRequestRequestTypeDef",
     "DisassociateThirdPartyFirewallRequestRequestTypeDef",
+    "DisassociateThirdPartyFirewallResponseTypeDef",
     "DiscoveredResourceTypeDef",
     "DnsDuplicateRuleGroupViolationTypeDef",
     "DnsRuleGroupLimitExceededViolationTypeDef",
     "DnsRuleGroupPriorityConflictViolationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EvaluationResultTypeDef",
     "ExpectedRouteTypeDef",
     "FMSPolicyUpdateFirewallCreationConfigActionTypeDef",
     "FirewallSubnetIsOutOfScopeViolationTypeDef",
     "FirewallSubnetMissingVPCEndpointViolationTypeDef",
+    "GetAdminAccountResponseTypeDef",
+    "GetAdminScopeRequestRequestTypeDef",
     "GetAppsListRequestRequestTypeDef",
     "GetComplianceDetailRequestRequestTypeDef",
+    "GetNotificationChannelResponseTypeDef",
     "GetPolicyRequestRequestTypeDef",
     "GetProtectionStatusRequestRequestTypeDef",
+    "GetProtectionStatusResponseTypeDef",
     "GetProtocolsListRequestRequestTypeDef",
     "ProtocolsListDataTypeDef",
     "GetResourceSetRequestRequestTypeDef",
     "ResourceSetTypeDef",
     "GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef",
+    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
     "GetViolationDetailsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef",
+    "ListAdminAccountsForOrganizationRequestRequestTypeDef",
+    "ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef",
+    "ListAdminsManagingAccountRequestRequestTypeDef",
+    "ListAdminsManagingAccountResponseTypeDef",
+    "ListAppsListsRequestListAppsListsPaginateTypeDef",
     "ListAppsListsRequestRequestTypeDef",
+    "ListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
     "ListComplianceStatusRequestRequestTypeDef",
     "ListDiscoveredResourcesRequestRequestTypeDef",
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
     "ListMemberAccountsRequestRequestTypeDef",
+    "ListMemberAccountsResponseTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
     "PolicySummaryTypeDef",
+    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
     "ListProtocolsListsRequestRequestTypeDef",
     "ProtocolsListDataSummaryTypeDef",
     "ListResourceSetResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
     "ListResourceSetsRequestRequestTypeDef",
     "ResourceSetSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
+    "ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
     "ListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef",
     "ThirdPartyFirewallFirewallPolicyTypeDef",
     "RouteTypeDef",
     "NetworkFirewallMissingExpectedRTViolationTypeDef",
     "NetworkFirewallMissingFirewallViolationTypeDef",
     "NetworkFirewallMissingSubnetViolationTypeDef",
     "StatefulEngineOptionsTypeDef",
     "StatelessRuleGroupTypeDef",
     "NetworkFirewallPolicyTypeDef",
     "NetworkFirewallStatefulRuleGroupOverrideTypeDef",
+    "PaginatorConfigTypeDef",
     "ThirdPartyFirewallPolicyTypeDef",
     "ResourceTagTypeDef",
     "PutNotificationChannelRequestRequestTypeDef",
     "ThirdPartyFirewallMissingExpectedRouteTableViolationTypeDef",
     "ThirdPartyFirewallMissingFirewallViolationTypeDef",
     "ThirdPartyFirewallMissingSubnetViolationTypeDef",
+    "ResponseMetadataTypeDef",
     "SecurityGroupRuleDescriptionTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "EC2AssociateRouteTableActionTypeDef",
     "EC2CopyRouteTableActionTypeDef",
     "EC2CreateRouteActionTypeDef",
     "EC2CreateRouteTableActionTypeDef",
     "EC2DeleteRouteActionTypeDef",
     "EC2ReplaceRouteActionTypeDef",
     "EC2ReplaceRouteTableAssociationActionTypeDef",
+    "ListAdminAccountsForOrganizationResponseTypeDef",
+    "AdminScopeTypeDef",
     "AppsListDataSummaryTypeDef",
     "AppsListDataTypeDef",
-    "AssociateThirdPartyFirewallResponseTypeDef",
-    "DisassociateThirdPartyFirewallResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAdminAccountResponseTypeDef",
-    "GetNotificationChannelResponseTypeDef",
-    "GetProtectionStatusResponseTypeDef",
-    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
-    "ListMemberAccountsResponseTypeDef",
     "AwsEc2InstanceViolationTypeDef",
     "BatchAssociateResourceResponseTypeDef",
     "BatchDisassociateResourceResponseTypeDef",
     "PolicyComplianceDetailTypeDef",
     "ListDiscoveredResourcesResponseTypeDef",
     "PolicyComplianceStatusTypeDef",
     "NetworkFirewallMissingExpectedRoutesViolationTypeDef",
     "GetProtocolsListResponseTypeDef",
     "PutProtocolsListResponseTypeDef",
     "GetResourceSetResponseTypeDef",
     "PutResourceSetResponseTypeDef",
-    "ListAppsListsRequestListAppsListsPaginateTypeDef",
-    "ListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
-    "ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
     "ListPoliciesResponseTypeDef",
     "ListProtocolsListsResponseTypeDef",
     "ListResourceSetResourcesResponseTypeDef",
     "ListResourceSetsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "PutProtocolsListRequestRequestTypeDef",
     "PutResourceSetRequestRequestTypeDef",
@@ -161,14 +177,16 @@
     "NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef",
     "NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef",
     "RouteHasOutOfScopeEndpointViolationTypeDef",
     "StatefulRuleGroupTypeDef",
     "PolicyOptionTypeDef",
     "SecurityGroupRemediationActionTypeDef",
     "RemediationActionTypeDef",
+    "GetAdminScopeResponseTypeDef",
+    "PutAdminAccountRequestRequestTypeDef",
     "ListAppsListsResponseTypeDef",
     "GetAppsListResponseTypeDef",
     "PutAppsListRequestRequestTypeDef",
     "PutAppsListResponseTypeDef",
     "GetComplianceDetailResponseTypeDef",
     "ListComplianceStatusResponseTypeDef",
     "NetworkFirewallPolicyDescriptionTypeDef",
@@ -183,23 +201,71 @@
     "PutPolicyResponseTypeDef",
     "PossibleRemediationActionsTypeDef",
     "ResourceViolationTypeDef",
     "ViolationDetailTypeDef",
     "GetViolationDetailsResponseTypeDef",
 )
 
+AccountScopeTypeDef = TypedDict(
+    "AccountScopeTypeDef",
+    {
+        "Accounts": List[str],
+        "AllAccountsEnabled": bool,
+        "ExcludeSpecifiedAccounts": bool,
+    },
+    total=False,
+)
+
 ActionTargetTypeDef = TypedDict(
     "ActionTargetTypeDef",
     {
         "ResourceId": str,
         "Description": str,
     },
     total=False,
 )
 
+AdminAccountSummaryTypeDef = TypedDict(
+    "AdminAccountSummaryTypeDef",
+    {
+        "AdminAccount": str,
+        "DefaultAdmin": bool,
+        "Status": OrganizationStatusType,
+    },
+    total=False,
+)
+
+OrganizationalUnitScopeTypeDef = TypedDict(
+    "OrganizationalUnitScopeTypeDef",
+    {
+        "OrganizationalUnits": List[str],
+        "AllOrganizationalUnitsEnabled": bool,
+        "ExcludeSpecifiedOrganizationalUnits": bool,
+    },
+    total=False,
+)
+
+PolicyTypeScopeTypeDef = TypedDict(
+    "PolicyTypeScopeTypeDef",
+    {
+        "PolicyTypes": List[SecurityServiceTypeType],
+        "AllPolicyTypesEnabled": bool,
+    },
+    total=False,
+)
+
+RegionScopeTypeDef = TypedDict(
+    "RegionScopeTypeDef",
+    {
+        "Regions": List[str],
+        "AllRegionsEnabled": bool,
+    },
+    total=False,
+)
+
 AppTypeDef = TypedDict(
     "AppTypeDef",
     {
         "AppName": str,
         "Protocol": str,
         "Port": int,
     },
@@ -215,22 +281,19 @@
 AssociateThirdPartyFirewallRequestRequestTypeDef = TypedDict(
     "AssociateThirdPartyFirewallRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateThirdPartyFirewallResponseTypeDef = TypedDict(
+    "AssociateThirdPartyFirewallResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsEc2NetworkInterfaceViolationTypeDef = TypedDict(
     "AwsEc2NetworkInterfaceViolationTypeDef",
     {
         "ViolationTarget": str,
@@ -329,14 +392,22 @@
 DisassociateThirdPartyFirewallRequestRequestTypeDef = TypedDict(
     "DisassociateThirdPartyFirewallRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
     },
 )
 
+DisassociateThirdPartyFirewallResponseTypeDef = TypedDict(
+    "DisassociateThirdPartyFirewallResponseTypeDef",
+    {
+        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DiscoveredResourceTypeDef = TypedDict(
     "DiscoveredResourceTypeDef",
     {
         "URI": str,
         "AccountId": str,
         "Type": str,
         "Name": str,
@@ -371,14 +442,21 @@
         "ConflictingPriority": int,
         "ConflictingPolicyId": str,
         "UnavailablePriorities": List[int],
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
 EvaluationResultTypeDef = TypedDict(
     "EvaluationResultTypeDef",
     {
         "ComplianceStatus": PolicyComplianceStatusTypeType,
         "ViolatorCount": int,
         "EvaluationLimitExceeded": bool,
     },
@@ -426,14 +504,30 @@
         "VpcId": str,
         "SubnetAvailabilityZone": str,
         "SubnetAvailabilityZoneId": str,
     },
     total=False,
 )
 
+GetAdminAccountResponseTypeDef = TypedDict(
+    "GetAdminAccountResponseTypeDef",
+    {
+        "AdminAccount": str,
+        "RoleStatus": AccountRoleStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetAdminScopeRequestRequestTypeDef = TypedDict(
+    "GetAdminScopeRequestRequestTypeDef",
+    {
+        "AdminAccount": str,
+    },
+)
+
 _RequiredGetAppsListRequestRequestTypeDef = TypedDict(
     "_RequiredGetAppsListRequestRequestTypeDef",
     {
         "ListId": str,
     },
 )
 _OptionalGetAppsListRequestRequestTypeDef = TypedDict(
@@ -455,14 +549,23 @@
     "GetComplianceDetailRequestRequestTypeDef",
     {
         "PolicyId": str,
         "MemberAccount": str,
     },
 )
 
+GetNotificationChannelResponseTypeDef = TypedDict(
+    "GetNotificationChannelResponseTypeDef",
+    {
+        "SnsTopicArn": str,
+        "SnsRoleName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPolicyRequestRequestTypeDef = TypedDict(
     "GetPolicyRequestRequestTypeDef",
     {
         "PolicyId": str,
     },
 )
 
@@ -488,14 +591,25 @@
 class GetProtectionStatusRequestRequestTypeDef(
     _RequiredGetProtectionStatusRequestRequestTypeDef,
     _OptionalGetProtectionStatusRequestRequestTypeDef,
 ):
     pass
 
 
+GetProtectionStatusResponseTypeDef = TypedDict(
+    "GetProtectionStatusResponseTypeDef",
+    {
+        "AdminAccountId": str,
+        "ServiceType": SecurityServiceTypeType,
+        "Data": str,
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetProtocolsListRequestRequestTypeDef = TypedDict(
     "_RequiredGetProtocolsListRequestRequestTypeDef",
     {
         "ListId": str,
     },
 )
 _OptionalGetProtocolsListRequestRequestTypeDef = TypedDict(
@@ -556,14 +670,15 @@
 _OptionalResourceSetTypeDef = TypedDict(
     "_OptionalResourceSetTypeDef",
     {
         "Id": str,
         "Description": str,
         "UpdateToken": str,
         "LastUpdateTime": datetime,
+        "ResourceSetStatus": ResourceSetStatusType,
     },
     total=False,
 )
 
 
 class ResourceSetTypeDef(_RequiredResourceSetTypeDef, _OptionalResourceSetTypeDef):
     pass
@@ -572,30 +687,81 @@
 GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef = TypedDict(
     "GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
     },
 )
 
+GetThirdPartyFirewallAssociationStatusResponseTypeDef = TypedDict(
+    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
+    {
+        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
+        "MarketplaceOnboardingStatus": MarketplaceSubscriptionOnboardingStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetViolationDetailsRequestRequestTypeDef = TypedDict(
     "GetViolationDetailsRequestRequestTypeDef",
     {
         "PolicyId": str,
         "MemberAccount": str,
         "ResourceId": str,
         "ResourceType": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef = TypedDict(
+    "ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListAdminAccountsForOrganizationRequestRequestTypeDef = TypedDict(
+    "ListAdminAccountsForOrganizationRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef = TypedDict(
+    "ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListAdminsManagingAccountRequestRequestTypeDef = TypedDict(
+    "ListAdminsManagingAccountRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListAdminsManagingAccountResponseTypeDef = TypedDict(
+    "ListAdminsManagingAccountResponseTypeDef",
+    {
+        "AdminAccounts": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAppsListsRequestListAppsListsPaginateTypeDef = TypedDict(
+    "ListAppsListsRequestListAppsListsPaginateTypeDef",
+    {
+        "DefaultLists": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 _RequiredListAppsListsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppsListsRequestRequestTypeDef",
     {
@@ -614,14 +780,36 @@
 
 class ListAppsListsRequestRequestTypeDef(
     _RequiredListAppsListsRequestRequestTypeDef, _OptionalListAppsListsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
+    "_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
+    {
+        "PolicyId": str,
+    },
+)
+_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
+    "_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListComplianceStatusRequestListComplianceStatusPaginateTypeDef(
+    _RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
+    _OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListComplianceStatusRequestRequestTypeDef = TypedDict(
     "_RequiredListComplianceStatusRequestRequestTypeDef",
     {
         "PolicyId": str,
     },
 )
 _OptionalListComplianceStatusRequestRequestTypeDef = TypedDict(
@@ -661,23 +849,48 @@
 class ListDiscoveredResourcesRequestRequestTypeDef(
     _RequiredListDiscoveredResourcesRequestRequestTypeDef,
     _OptionalListDiscoveredResourcesRequestRequestTypeDef,
 ):
     pass
 
 
+ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMemberAccountsRequestRequestTypeDef = TypedDict(
     "ListMemberAccountsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListMemberAccountsResponseTypeDef = TypedDict(
+    "ListMemberAccountsResponseTypeDef",
+    {
+        "MemberAccounts": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPoliciesRequestRequestTypeDef = TypedDict(
     "ListPoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -689,14 +902,24 @@
         "PolicyArn": str,
         "PolicyId": str,
         "PolicyName": str,
         "ResourceType": str,
         "SecurityServiceType": SecurityServiceTypeType,
         "RemediationEnabled": bool,
         "DeleteUnusedFMManagedResources": bool,
+        "PolicyStatus": CustomerPolicyStatusType,
+    },
+    total=False,
+)
+
+ListProtocolsListsRequestListProtocolsListsPaginateTypeDef = TypedDict(
+    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
+    {
+        "DefaultLists": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 _RequiredListProtocolsListsRequestRequestTypeDef = TypedDict(
     "_RequiredListProtocolsListsRequestRequestTypeDef",
     {
@@ -785,14 +1008,15 @@
 ResourceSetSummaryTypeDef = TypedDict(
     "ResourceSetSummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "LastUpdateTime": datetime,
+        "ResourceSetStatus": ResourceSetStatusType,
     },
     total=False,
 )
 
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
@@ -804,14 +1028,36 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
+    {
+        "ThirdPartyFirewall": ThirdPartyFirewallType,
+    },
+)
+_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef(
+    _RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
+    _OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
         "MaxResults": int,
     },
 )
@@ -915,14 +1161,24 @@
     "NetworkFirewallStatefulRuleGroupOverrideTypeDef",
     {
         "Action": Literal["DROP_TO_ALERT"],
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
 ThirdPartyFirewallPolicyTypeDef = TypedDict(
     "ThirdPartyFirewallPolicyTypeDef",
     {
         "FirewallDeploymentModel": FirewallDeploymentModelType,
     },
     total=False,
 )
@@ -984,14 +1240,25 @@
         "VPC": str,
         "AvailabilityZone": str,
         "TargetViolationReason": str,
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
 SecurityGroupRuleDescriptionTypeDef = TypedDict(
     "SecurityGroupRuleDescriptionTypeDef",
     {
         "IPV4Range": str,
         "IPV6Range": str,
         "PrefixListId": str,
         "Protocol": str,
@@ -1169,14 +1436,34 @@
 class EC2ReplaceRouteTableAssociationActionTypeDef(
     _RequiredEC2ReplaceRouteTableAssociationActionTypeDef,
     _OptionalEC2ReplaceRouteTableAssociationActionTypeDef,
 ):
     pass
 
 
+ListAdminAccountsForOrganizationResponseTypeDef = TypedDict(
+    "ListAdminAccountsForOrganizationResponseTypeDef",
+    {
+        "AdminAccounts": List[AdminAccountSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AdminScopeTypeDef = TypedDict(
+    "AdminScopeTypeDef",
+    {
+        "AccountScope": AccountScopeTypeDef,
+        "OrganizationalUnitScope": OrganizationalUnitScopeTypeDef,
+        "RegionScope": RegionScopeTypeDef,
+        "PolicyTypeScope": PolicyTypeScopeTypeDef,
+    },
+    total=False,
+)
+
 AppsListDataSummaryTypeDef = TypedDict(
     "AppsListDataSummaryTypeDef",
     {
         "ListArn": str,
         "ListId": str,
         "ListName": str,
         "AppsList": List[AppTypeDef],
@@ -1204,108 +1491,38 @@
 )
 
 
 class AppsListDataTypeDef(_RequiredAppsListDataTypeDef, _OptionalAppsListDataTypeDef):
     pass
 
 
-AssociateThirdPartyFirewallResponseTypeDef = TypedDict(
-    "AssociateThirdPartyFirewallResponseTypeDef",
-    {
-        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateThirdPartyFirewallResponseTypeDef = TypedDict(
-    "DisassociateThirdPartyFirewallResponseTypeDef",
-    {
-        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
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
-GetAdminAccountResponseTypeDef = TypedDict(
-    "GetAdminAccountResponseTypeDef",
-    {
-        "AdminAccount": str,
-        "RoleStatus": AccountRoleStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetNotificationChannelResponseTypeDef = TypedDict(
-    "GetNotificationChannelResponseTypeDef",
-    {
-        "SnsTopicArn": str,
-        "SnsRoleName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetProtectionStatusResponseTypeDef = TypedDict(
-    "GetProtectionStatusResponseTypeDef",
-    {
-        "AdminAccountId": str,
-        "ServiceType": SecurityServiceTypeType,
-        "Data": str,
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetThirdPartyFirewallAssociationStatusResponseTypeDef = TypedDict(
-    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
-    {
-        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
-        "MarketplaceOnboardingStatus": MarketplaceSubscriptionOnboardingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListMemberAccountsResponseTypeDef = TypedDict(
-    "ListMemberAccountsResponseTypeDef",
-    {
-        "MemberAccounts": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AwsEc2InstanceViolationTypeDef = TypedDict(
     "AwsEc2InstanceViolationTypeDef",
     {
         "ViolationTarget": str,
         "AwsEc2NetworkInterfaceViolations": List[AwsEc2NetworkInterfaceViolationTypeDef],
     },
     total=False,
 )
 
 BatchAssociateResourceResponseTypeDef = TypedDict(
     "BatchAssociateResourceResponseTypeDef",
     {
         "ResourceSetIdentifier": str,
         "FailedItems": List[FailedItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateResourceResponseTypeDef = TypedDict(
     "BatchDisassociateResourceResponseTypeDef",
     {
         "ResourceSetIdentifier": str,
         "FailedItems": List[FailedItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyComplianceDetailTypeDef = TypedDict(
     "PolicyComplianceDetailTypeDef",
     {
         "PolicyOwner": str,
@@ -1320,15 +1537,15 @@
 )
 
 ListDiscoveredResourcesResponseTypeDef = TypedDict(
     "ListDiscoveredResourcesResponseTypeDef",
     {
         "Items": List[DiscoveredResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyComplianceStatusTypeDef = TypedDict(
     "PolicyComplianceStatusTypeDef",
     {
         "PolicyOwner": str,
@@ -1353,164 +1570,86 @@
 )
 
 GetProtocolsListResponseTypeDef = TypedDict(
     "GetProtocolsListResponseTypeDef",
     {
         "ProtocolsList": ProtocolsListDataTypeDef,
         "ProtocolsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutProtocolsListResponseTypeDef = TypedDict(
     "PutProtocolsListResponseTypeDef",
     {
         "ProtocolsList": ProtocolsListDataTypeDef,
         "ProtocolsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceSetResponseTypeDef = TypedDict(
     "GetResourceSetResponseTypeDef",
     {
         "ResourceSet": ResourceSetTypeDef,
         "ResourceSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourceSetResponseTypeDef = TypedDict(
     "PutResourceSetResponseTypeDef",
     {
         "ResourceSet": ResourceSetTypeDef,
         "ResourceSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAppsListsRequestListAppsListsPaginateTypeDef = TypedDict(
-    "ListAppsListsRequestListAppsListsPaginateTypeDef",
-    {
-        "DefaultLists": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
-    "_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
-    {
-        "PolicyId": str,
-    },
-)
-_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
-    "_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListComplianceStatusRequestListComplianceStatusPaginateTypeDef(
-    _RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
-    _OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
-):
-    pass
-
-
-ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProtocolsListsRequestListProtocolsListsPaginateTypeDef = TypedDict(
-    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
-    {
-        "DefaultLists": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
-    {
-        "ThirdPartyFirewall": ThirdPartyFirewallType,
-    },
-)
-_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef(
-    _RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
-    _OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
-):
-    pass
-
-
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "PolicyList": List[PolicySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtocolsListsResponseTypeDef = TypedDict(
     "ListProtocolsListsResponseTypeDef",
     {
         "ProtocolsLists": List[ProtocolsListDataSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceSetResourcesResponseTypeDef = TypedDict(
     "ListResourceSetResourcesResponseTypeDef",
     {
         "Items": List[ResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceSetsResponseTypeDef = TypedDict(
     "ListResourceSetsResponseTypeDef",
     {
         "ResourceSets": List[ResourceSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutProtocolsListRequestRequestTypeDef = TypedDict(
     "_RequiredPutProtocolsListRequestRequestTypeDef",
     {
         "ProtocolsList": ProtocolsListDataTypeDef,
@@ -1561,15 +1700,15 @@
 )
 
 ListThirdPartyFirewallFirewallPoliciesResponseTypeDef = TypedDict(
     "ListThirdPartyFirewallFirewallPoliciesResponseTypeDef",
     {
         "ThirdPartyFirewallFirewallPolicies": List[ThirdPartyFirewallFirewallPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkFirewallBlackHoleRouteDetectedViolationTypeDef = TypedDict(
     "NetworkFirewallBlackHoleRouteDetectedViolationTypeDef",
     {
         "ViolationTarget": str,
@@ -1712,29 +1851,59 @@
         "FMSPolicyUpdateFirewallCreationConfigAction": (
             FMSPolicyUpdateFirewallCreationConfigActionTypeDef
         ),
     },
     total=False,
 )
 
+GetAdminScopeResponseTypeDef = TypedDict(
+    "GetAdminScopeResponseTypeDef",
+    {
+        "AdminScope": AdminScopeTypeDef,
+        "Status": OrganizationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredPutAdminAccountRequestRequestTypeDef = TypedDict(
+    "_RequiredPutAdminAccountRequestRequestTypeDef",
+    {
+        "AdminAccount": str,
+    },
+)
+_OptionalPutAdminAccountRequestRequestTypeDef = TypedDict(
+    "_OptionalPutAdminAccountRequestRequestTypeDef",
+    {
+        "AdminScope": AdminScopeTypeDef,
+    },
+    total=False,
+)
+
+
+class PutAdminAccountRequestRequestTypeDef(
+    _RequiredPutAdminAccountRequestRequestTypeDef, _OptionalPutAdminAccountRequestRequestTypeDef
+):
+    pass
+
+
 ListAppsListsResponseTypeDef = TypedDict(
     "ListAppsListsResponseTypeDef",
     {
         "AppsLists": List[AppsListDataSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppsListResponseTypeDef = TypedDict(
     "GetAppsListResponseTypeDef",
     {
         "AppsList": AppsListDataTypeDef,
         "AppsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAppsListRequestRequestTypeDef = TypedDict(
     "_RequiredPutAppsListRequestRequestTypeDef",
     {
         "AppsList": AppsListDataTypeDef,
@@ -1756,32 +1925,32 @@
 
 
 PutAppsListResponseTypeDef = TypedDict(
     "PutAppsListResponseTypeDef",
     {
         "AppsList": AppsListDataTypeDef,
         "AppsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceDetailResponseTypeDef = TypedDict(
     "GetComplianceDetailResponseTypeDef",
     {
         "PolicyComplianceDetail": PolicyComplianceDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComplianceStatusResponseTypeDef = TypedDict(
     "ListComplianceStatusResponseTypeDef",
     {
         "PolicyComplianceStatusList": List[PolicyComplianceStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkFirewallPolicyDescriptionTypeDef = TypedDict(
     "NetworkFirewallPolicyDescriptionTypeDef",
     {
         "StatelessRuleGroups": List[StatelessRuleGroupTypeDef],
@@ -1865,14 +2034,15 @@
         "ResourceTypeList": List[str],
         "ResourceTags": List[ResourceTagTypeDef],
         "DeleteUnusedFMManagedResources": bool,
         "IncludeMap": Dict[CustomerPolicyScopeIdTypeType, List[str]],
         "ExcludeMap": Dict[CustomerPolicyScopeIdTypeType, List[str]],
         "ResourceSetIds": List[str],
         "PolicyDescription": str,
+        "PolicyStatus": CustomerPolicyStatusType,
     },
     total=False,
 )
 
 
 class PolicyTypeDef(_RequiredPolicyTypeDef, _OptionalPolicyTypeDef):
     pass
@@ -1901,15 +2071,15 @@
 
 
 GetPolicyResponseTypeDef = TypedDict(
     "GetPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
         "PolicyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutPolicyRequestRequestTypeDef",
     {
         "Policy": PolicyTypeDef,
@@ -1931,15 +2101,15 @@
 
 
 PutPolicyResponseTypeDef = TypedDict(
     "PutPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
         "PolicyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PossibleRemediationActionsTypeDef = TypedDict(
     "PossibleRemediationActionsTypeDef",
     {
         "Description": str,
@@ -2022,10 +2192,10 @@
     pass
 
 
 GetViolationDetailsResponseTypeDef = TypedDict(
     "GetViolationDetailsResponseTypeDef",
     {
         "ViolationDetail": ViolationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms/type_defs.pyi` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms/type_defs.pyi`

 * *Files 12% similar despite different names*

```diff
@@ -2,33 +2,36 @@
 Type annotations for fms service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_fms.type_defs import ActionTargetTypeDef
+    from types_aiobotocore_fms.type_defs import AccountScopeTypeDef
 
-    data: ActionTargetTypeDef = {...}
+    data: AccountScopeTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence, Union
 
 from .literals import (
     AccountRoleStatusType,
     CustomerPolicyScopeIdTypeType,
+    CustomerPolicyStatusType,
     DependentServiceNameType,
     DestinationTypeType,
     FailedItemReasonType,
     FirewallDeploymentModelType,
     MarketplaceSubscriptionOnboardingStatusType,
+    OrganizationStatusType,
     PolicyComplianceStatusTypeType,
     RemediationActionTypeType,
+    ResourceSetStatusType,
     RuleOrderType,
     SecurityServiceTypeType,
     TargetTypeType,
     ThirdPartyFirewallAssociationStatusType,
     ThirdPartyFirewallType,
     ViolationReasonType,
 )
@@ -39,116 +42,129 @@
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
+    "AccountScopeTypeDef",
     "ActionTargetTypeDef",
+    "AdminAccountSummaryTypeDef",
+    "OrganizationalUnitScopeTypeDef",
+    "PolicyTypeScopeTypeDef",
+    "RegionScopeTypeDef",
     "AppTypeDef",
     "AssociateAdminAccountRequestRequestTypeDef",
     "AssociateThirdPartyFirewallRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateThirdPartyFirewallResponseTypeDef",
     "AwsEc2NetworkInterfaceViolationTypeDef",
     "PartialMatchTypeDef",
     "BatchAssociateResourceRequestRequestTypeDef",
     "FailedItemTypeDef",
     "BatchDisassociateResourceRequestRequestTypeDef",
     "ComplianceViolatorTypeDef",
     "DeleteAppsListRequestRequestTypeDef",
     "DeletePolicyRequestRequestTypeDef",
     "DeleteProtocolsListRequestRequestTypeDef",
     "DeleteResourceSetRequestRequestTypeDef",
     "DisassociateThirdPartyFirewallRequestRequestTypeDef",
+    "DisassociateThirdPartyFirewallResponseTypeDef",
     "DiscoveredResourceTypeDef",
     "DnsDuplicateRuleGroupViolationTypeDef",
     "DnsRuleGroupLimitExceededViolationTypeDef",
     "DnsRuleGroupPriorityConflictViolationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EvaluationResultTypeDef",
     "ExpectedRouteTypeDef",
     "FMSPolicyUpdateFirewallCreationConfigActionTypeDef",
     "FirewallSubnetIsOutOfScopeViolationTypeDef",
     "FirewallSubnetMissingVPCEndpointViolationTypeDef",
+    "GetAdminAccountResponseTypeDef",
+    "GetAdminScopeRequestRequestTypeDef",
     "GetAppsListRequestRequestTypeDef",
     "GetComplianceDetailRequestRequestTypeDef",
+    "GetNotificationChannelResponseTypeDef",
     "GetPolicyRequestRequestTypeDef",
     "GetProtectionStatusRequestRequestTypeDef",
+    "GetProtectionStatusResponseTypeDef",
     "GetProtocolsListRequestRequestTypeDef",
     "ProtocolsListDataTypeDef",
     "GetResourceSetRequestRequestTypeDef",
     "ResourceSetTypeDef",
     "GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef",
+    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
     "GetViolationDetailsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef",
+    "ListAdminAccountsForOrganizationRequestRequestTypeDef",
+    "ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef",
+    "ListAdminsManagingAccountRequestRequestTypeDef",
+    "ListAdminsManagingAccountResponseTypeDef",
+    "ListAppsListsRequestListAppsListsPaginateTypeDef",
     "ListAppsListsRequestRequestTypeDef",
+    "ListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
     "ListComplianceStatusRequestRequestTypeDef",
     "ListDiscoveredResourcesRequestRequestTypeDef",
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
     "ListMemberAccountsRequestRequestTypeDef",
+    "ListMemberAccountsResponseTypeDef",
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
     "ListPoliciesRequestRequestTypeDef",
     "PolicySummaryTypeDef",
+    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
     "ListProtocolsListsRequestRequestTypeDef",
     "ProtocolsListDataSummaryTypeDef",
     "ListResourceSetResourcesRequestRequestTypeDef",
     "ResourceTypeDef",
     "ListResourceSetsRequestRequestTypeDef",
     "ResourceSetSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
+    "ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
     "ListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef",
     "ThirdPartyFirewallFirewallPolicyTypeDef",
     "RouteTypeDef",
     "NetworkFirewallMissingExpectedRTViolationTypeDef",
     "NetworkFirewallMissingFirewallViolationTypeDef",
     "NetworkFirewallMissingSubnetViolationTypeDef",
     "StatefulEngineOptionsTypeDef",
     "StatelessRuleGroupTypeDef",
     "NetworkFirewallPolicyTypeDef",
     "NetworkFirewallStatefulRuleGroupOverrideTypeDef",
+    "PaginatorConfigTypeDef",
     "ThirdPartyFirewallPolicyTypeDef",
     "ResourceTagTypeDef",
     "PutNotificationChannelRequestRequestTypeDef",
     "ThirdPartyFirewallMissingExpectedRouteTableViolationTypeDef",
     "ThirdPartyFirewallMissingFirewallViolationTypeDef",
     "ThirdPartyFirewallMissingSubnetViolationTypeDef",
+    "ResponseMetadataTypeDef",
     "SecurityGroupRuleDescriptionTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "EC2AssociateRouteTableActionTypeDef",
     "EC2CopyRouteTableActionTypeDef",
     "EC2CreateRouteActionTypeDef",
     "EC2CreateRouteTableActionTypeDef",
     "EC2DeleteRouteActionTypeDef",
     "EC2ReplaceRouteActionTypeDef",
     "EC2ReplaceRouteTableAssociationActionTypeDef",
+    "ListAdminAccountsForOrganizationResponseTypeDef",
+    "AdminScopeTypeDef",
     "AppsListDataSummaryTypeDef",
     "AppsListDataTypeDef",
-    "AssociateThirdPartyFirewallResponseTypeDef",
-    "DisassociateThirdPartyFirewallResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAdminAccountResponseTypeDef",
-    "GetNotificationChannelResponseTypeDef",
-    "GetProtectionStatusResponseTypeDef",
-    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
-    "ListMemberAccountsResponseTypeDef",
     "AwsEc2InstanceViolationTypeDef",
     "BatchAssociateResourceResponseTypeDef",
     "BatchDisassociateResourceResponseTypeDef",
     "PolicyComplianceDetailTypeDef",
     "ListDiscoveredResourcesResponseTypeDef",
     "PolicyComplianceStatusTypeDef",
     "NetworkFirewallMissingExpectedRoutesViolationTypeDef",
     "GetProtocolsListResponseTypeDef",
     "PutProtocolsListResponseTypeDef",
     "GetResourceSetResponseTypeDef",
     "PutResourceSetResponseTypeDef",
-    "ListAppsListsRequestListAppsListsPaginateTypeDef",
-    "ListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
-    "ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
     "ListPoliciesResponseTypeDef",
     "ListProtocolsListsResponseTypeDef",
     "ListResourceSetResourcesResponseTypeDef",
     "ListResourceSetsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "PutProtocolsListRequestRequestTypeDef",
     "PutResourceSetRequestRequestTypeDef",
@@ -160,14 +176,16 @@
     "NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef",
     "NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef",
     "RouteHasOutOfScopeEndpointViolationTypeDef",
     "StatefulRuleGroupTypeDef",
     "PolicyOptionTypeDef",
     "SecurityGroupRemediationActionTypeDef",
     "RemediationActionTypeDef",
+    "GetAdminScopeResponseTypeDef",
+    "PutAdminAccountRequestRequestTypeDef",
     "ListAppsListsResponseTypeDef",
     "GetAppsListResponseTypeDef",
     "PutAppsListRequestRequestTypeDef",
     "PutAppsListResponseTypeDef",
     "GetComplianceDetailResponseTypeDef",
     "ListComplianceStatusResponseTypeDef",
     "NetworkFirewallPolicyDescriptionTypeDef",
@@ -182,23 +200,71 @@
     "PutPolicyResponseTypeDef",
     "PossibleRemediationActionsTypeDef",
     "ResourceViolationTypeDef",
     "ViolationDetailTypeDef",
     "GetViolationDetailsResponseTypeDef",
 )
 
+AccountScopeTypeDef = TypedDict(
+    "AccountScopeTypeDef",
+    {
+        "Accounts": List[str],
+        "AllAccountsEnabled": bool,
+        "ExcludeSpecifiedAccounts": bool,
+    },
+    total=False,
+)
+
 ActionTargetTypeDef = TypedDict(
     "ActionTargetTypeDef",
     {
         "ResourceId": str,
         "Description": str,
     },
     total=False,
 )
 
+AdminAccountSummaryTypeDef = TypedDict(
+    "AdminAccountSummaryTypeDef",
+    {
+        "AdminAccount": str,
+        "DefaultAdmin": bool,
+        "Status": OrganizationStatusType,
+    },
+    total=False,
+)
+
+OrganizationalUnitScopeTypeDef = TypedDict(
+    "OrganizationalUnitScopeTypeDef",
+    {
+        "OrganizationalUnits": List[str],
+        "AllOrganizationalUnitsEnabled": bool,
+        "ExcludeSpecifiedOrganizationalUnits": bool,
+    },
+    total=False,
+)
+
+PolicyTypeScopeTypeDef = TypedDict(
+    "PolicyTypeScopeTypeDef",
+    {
+        "PolicyTypes": List[SecurityServiceTypeType],
+        "AllPolicyTypesEnabled": bool,
+    },
+    total=False,
+)
+
+RegionScopeTypeDef = TypedDict(
+    "RegionScopeTypeDef",
+    {
+        "Regions": List[str],
+        "AllRegionsEnabled": bool,
+    },
+    total=False,
+)
+
 AppTypeDef = TypedDict(
     "AppTypeDef",
     {
         "AppName": str,
         "Protocol": str,
         "Port": int,
     },
@@ -214,22 +280,19 @@
 AssociateThirdPartyFirewallRequestRequestTypeDef = TypedDict(
     "AssociateThirdPartyFirewallRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateThirdPartyFirewallResponseTypeDef = TypedDict(
+    "AssociateThirdPartyFirewallResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsEc2NetworkInterfaceViolationTypeDef = TypedDict(
     "AwsEc2NetworkInterfaceViolationTypeDef",
     {
         "ViolationTarget": str,
@@ -326,14 +389,22 @@
 DisassociateThirdPartyFirewallRequestRequestTypeDef = TypedDict(
     "DisassociateThirdPartyFirewallRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
     },
 )
 
+DisassociateThirdPartyFirewallResponseTypeDef = TypedDict(
+    "DisassociateThirdPartyFirewallResponseTypeDef",
+    {
+        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DiscoveredResourceTypeDef = TypedDict(
     "DiscoveredResourceTypeDef",
     {
         "URI": str,
         "AccountId": str,
         "Type": str,
         "Name": str,
@@ -368,14 +439,21 @@
         "ConflictingPriority": int,
         "ConflictingPolicyId": str,
         "UnavailablePriorities": List[int],
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
 EvaluationResultTypeDef = TypedDict(
     "EvaluationResultTypeDef",
     {
         "ComplianceStatus": PolicyComplianceStatusTypeType,
         "ViolatorCount": int,
         "EvaluationLimitExceeded": bool,
     },
@@ -423,14 +501,30 @@
         "VpcId": str,
         "SubnetAvailabilityZone": str,
         "SubnetAvailabilityZoneId": str,
     },
     total=False,
 )
 
+GetAdminAccountResponseTypeDef = TypedDict(
+    "GetAdminAccountResponseTypeDef",
+    {
+        "AdminAccount": str,
+        "RoleStatus": AccountRoleStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetAdminScopeRequestRequestTypeDef = TypedDict(
+    "GetAdminScopeRequestRequestTypeDef",
+    {
+        "AdminAccount": str,
+    },
+)
+
 _RequiredGetAppsListRequestRequestTypeDef = TypedDict(
     "_RequiredGetAppsListRequestRequestTypeDef",
     {
         "ListId": str,
     },
 )
 _OptionalGetAppsListRequestRequestTypeDef = TypedDict(
@@ -450,14 +544,23 @@
     "GetComplianceDetailRequestRequestTypeDef",
     {
         "PolicyId": str,
         "MemberAccount": str,
     },
 )
 
+GetNotificationChannelResponseTypeDef = TypedDict(
+    "GetNotificationChannelResponseTypeDef",
+    {
+        "SnsTopicArn": str,
+        "SnsRoleName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPolicyRequestRequestTypeDef = TypedDict(
     "GetPolicyRequestRequestTypeDef",
     {
         "PolicyId": str,
     },
 )
 
@@ -481,14 +584,25 @@
 
 class GetProtectionStatusRequestRequestTypeDef(
     _RequiredGetProtectionStatusRequestRequestTypeDef,
     _OptionalGetProtectionStatusRequestRequestTypeDef,
 ):
     pass
 
+GetProtectionStatusResponseTypeDef = TypedDict(
+    "GetProtectionStatusResponseTypeDef",
+    {
+        "AdminAccountId": str,
+        "ServiceType": SecurityServiceTypeType,
+        "Data": str,
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetProtocolsListRequestRequestTypeDef = TypedDict(
     "_RequiredGetProtocolsListRequestRequestTypeDef",
     {
         "ListId": str,
     },
 )
 _OptionalGetProtocolsListRequestRequestTypeDef = TypedDict(
@@ -545,44 +659,96 @@
 _OptionalResourceSetTypeDef = TypedDict(
     "_OptionalResourceSetTypeDef",
     {
         "Id": str,
         "Description": str,
         "UpdateToken": str,
         "LastUpdateTime": datetime,
+        "ResourceSetStatus": ResourceSetStatusType,
     },
     total=False,
 )
 
 class ResourceSetTypeDef(_RequiredResourceSetTypeDef, _OptionalResourceSetTypeDef):
     pass
 
 GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef = TypedDict(
     "GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
     },
 )
 
+GetThirdPartyFirewallAssociationStatusResponseTypeDef = TypedDict(
+    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
+    {
+        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
+        "MarketplaceOnboardingStatus": MarketplaceSubscriptionOnboardingStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetViolationDetailsRequestRequestTypeDef = TypedDict(
     "GetViolationDetailsRequestRequestTypeDef",
     {
         "PolicyId": str,
         "MemberAccount": str,
         "ResourceId": str,
         "ResourceType": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef = TypedDict(
+    "ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListAdminAccountsForOrganizationRequestRequestTypeDef = TypedDict(
+    "ListAdminAccountsForOrganizationRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef = TypedDict(
+    "ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListAdminsManagingAccountRequestRequestTypeDef = TypedDict(
+    "ListAdminsManagingAccountRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListAdminsManagingAccountResponseTypeDef = TypedDict(
+    "ListAdminsManagingAccountResponseTypeDef",
+    {
+        "AdminAccounts": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAppsListsRequestListAppsListsPaginateTypeDef = TypedDict(
+    "ListAppsListsRequestListAppsListsPaginateTypeDef",
+    {
+        "DefaultLists": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 _RequiredListAppsListsRequestRequestTypeDef = TypedDict(
     "_RequiredListAppsListsRequestRequestTypeDef",
     {
@@ -599,14 +765,34 @@
 )
 
 class ListAppsListsRequestRequestTypeDef(
     _RequiredListAppsListsRequestRequestTypeDef, _OptionalListAppsListsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
+    "_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
+    {
+        "PolicyId": str,
+    },
+)
+_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
+    "_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListComplianceStatusRequestListComplianceStatusPaginateTypeDef(
+    _RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
+    _OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
+):
+    pass
+
 _RequiredListComplianceStatusRequestRequestTypeDef = TypedDict(
     "_RequiredListComplianceStatusRequestRequestTypeDef",
     {
         "PolicyId": str,
     },
 )
 _OptionalListComplianceStatusRequestRequestTypeDef = TypedDict(
@@ -642,23 +828,48 @@
 
 class ListDiscoveredResourcesRequestRequestTypeDef(
     _RequiredListDiscoveredResourcesRequestRequestTypeDef,
     _OptionalListDiscoveredResourcesRequestRequestTypeDef,
 ):
     pass
 
+ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
+    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMemberAccountsRequestRequestTypeDef = TypedDict(
     "ListMemberAccountsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListMemberAccountsResponseTypeDef = TypedDict(
+    "ListMemberAccountsResponseTypeDef",
+    {
+        "MemberAccounts": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
+    "ListPoliciesRequestListPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPoliciesRequestRequestTypeDef = TypedDict(
     "ListPoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -670,14 +881,24 @@
         "PolicyArn": str,
         "PolicyId": str,
         "PolicyName": str,
         "ResourceType": str,
         "SecurityServiceType": SecurityServiceTypeType,
         "RemediationEnabled": bool,
         "DeleteUnusedFMManagedResources": bool,
+        "PolicyStatus": CustomerPolicyStatusType,
+    },
+    total=False,
+)
+
+ListProtocolsListsRequestListProtocolsListsPaginateTypeDef = TypedDict(
+    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
+    {
+        "DefaultLists": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 _RequiredListProtocolsListsRequestRequestTypeDef = TypedDict(
     "_RequiredListProtocolsListsRequestRequestTypeDef",
     {
@@ -760,14 +981,15 @@
 ResourceSetSummaryTypeDef = TypedDict(
     "ResourceSetSummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "LastUpdateTime": datetime,
+        "ResourceSetStatus": ResourceSetStatusType,
     },
     total=False,
 )
 
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
@@ -779,14 +1001,34 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
+    {
+        "ThirdPartyFirewall": ThirdPartyFirewallType,
+    },
+)
+_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef(
+    _RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
+    _OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef",
     {
         "ThirdPartyFirewall": ThirdPartyFirewallType,
         "MaxResults": int,
     },
 )
@@ -888,14 +1130,24 @@
     "NetworkFirewallStatefulRuleGroupOverrideTypeDef",
     {
         "Action": Literal["DROP_TO_ALERT"],
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
 ThirdPartyFirewallPolicyTypeDef = TypedDict(
     "ThirdPartyFirewallPolicyTypeDef",
     {
         "FirewallDeploymentModel": FirewallDeploymentModelType,
     },
     total=False,
 )
@@ -955,14 +1207,25 @@
         "VPC": str,
         "AvailabilityZone": str,
         "TargetViolationReason": str,
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
 SecurityGroupRuleDescriptionTypeDef = TypedDict(
     "SecurityGroupRuleDescriptionTypeDef",
     {
         "IPV4Range": str,
         "IPV6Range": str,
         "PrefixListId": str,
         "Protocol": str,
@@ -1126,14 +1389,34 @@
 
 class EC2ReplaceRouteTableAssociationActionTypeDef(
     _RequiredEC2ReplaceRouteTableAssociationActionTypeDef,
     _OptionalEC2ReplaceRouteTableAssociationActionTypeDef,
 ):
     pass
 
+ListAdminAccountsForOrganizationResponseTypeDef = TypedDict(
+    "ListAdminAccountsForOrganizationResponseTypeDef",
+    {
+        "AdminAccounts": List[AdminAccountSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AdminScopeTypeDef = TypedDict(
+    "AdminScopeTypeDef",
+    {
+        "AccountScope": AccountScopeTypeDef,
+        "OrganizationalUnitScope": OrganizationalUnitScopeTypeDef,
+        "RegionScope": RegionScopeTypeDef,
+        "PolicyTypeScope": PolicyTypeScopeTypeDef,
+    },
+    total=False,
+)
+
 AppsListDataSummaryTypeDef = TypedDict(
     "AppsListDataSummaryTypeDef",
     {
         "ListArn": str,
         "ListId": str,
         "ListName": str,
         "AppsList": List[AppTypeDef],
@@ -1159,108 +1442,38 @@
     },
     total=False,
 )
 
 class AppsListDataTypeDef(_RequiredAppsListDataTypeDef, _OptionalAppsListDataTypeDef):
     pass
 
-AssociateThirdPartyFirewallResponseTypeDef = TypedDict(
-    "AssociateThirdPartyFirewallResponseTypeDef",
-    {
-        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateThirdPartyFirewallResponseTypeDef = TypedDict(
-    "DisassociateThirdPartyFirewallResponseTypeDef",
-    {
-        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
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
-GetAdminAccountResponseTypeDef = TypedDict(
-    "GetAdminAccountResponseTypeDef",
-    {
-        "AdminAccount": str,
-        "RoleStatus": AccountRoleStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetNotificationChannelResponseTypeDef = TypedDict(
-    "GetNotificationChannelResponseTypeDef",
-    {
-        "SnsTopicArn": str,
-        "SnsRoleName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetProtectionStatusResponseTypeDef = TypedDict(
-    "GetProtectionStatusResponseTypeDef",
-    {
-        "AdminAccountId": str,
-        "ServiceType": SecurityServiceTypeType,
-        "Data": str,
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetThirdPartyFirewallAssociationStatusResponseTypeDef = TypedDict(
-    "GetThirdPartyFirewallAssociationStatusResponseTypeDef",
-    {
-        "ThirdPartyFirewallStatus": ThirdPartyFirewallAssociationStatusType,
-        "MarketplaceOnboardingStatus": MarketplaceSubscriptionOnboardingStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListMemberAccountsResponseTypeDef = TypedDict(
-    "ListMemberAccountsResponseTypeDef",
-    {
-        "MemberAccounts": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AwsEc2InstanceViolationTypeDef = TypedDict(
     "AwsEc2InstanceViolationTypeDef",
     {
         "ViolationTarget": str,
         "AwsEc2NetworkInterfaceViolations": List[AwsEc2NetworkInterfaceViolationTypeDef],
     },
     total=False,
 )
 
 BatchAssociateResourceResponseTypeDef = TypedDict(
     "BatchAssociateResourceResponseTypeDef",
     {
         "ResourceSetIdentifier": str,
         "FailedItems": List[FailedItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisassociateResourceResponseTypeDef = TypedDict(
     "BatchDisassociateResourceResponseTypeDef",
     {
         "ResourceSetIdentifier": str,
         "FailedItems": List[FailedItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyComplianceDetailTypeDef = TypedDict(
     "PolicyComplianceDetailTypeDef",
     {
         "PolicyOwner": str,
@@ -1275,15 +1488,15 @@
 )
 
 ListDiscoveredResourcesResponseTypeDef = TypedDict(
     "ListDiscoveredResourcesResponseTypeDef",
     {
         "Items": List[DiscoveredResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyComplianceStatusTypeDef = TypedDict(
     "PolicyComplianceStatusTypeDef",
     {
         "PolicyOwner": str,
@@ -1308,160 +1521,86 @@
 )
 
 GetProtocolsListResponseTypeDef = TypedDict(
     "GetProtocolsListResponseTypeDef",
     {
         "ProtocolsList": ProtocolsListDataTypeDef,
         "ProtocolsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutProtocolsListResponseTypeDef = TypedDict(
     "PutProtocolsListResponseTypeDef",
     {
         "ProtocolsList": ProtocolsListDataTypeDef,
         "ProtocolsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceSetResponseTypeDef = TypedDict(
     "GetResourceSetResponseTypeDef",
     {
         "ResourceSet": ResourceSetTypeDef,
         "ResourceSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutResourceSetResponseTypeDef = TypedDict(
     "PutResourceSetResponseTypeDef",
     {
         "ResourceSet": ResourceSetTypeDef,
         "ResourceSetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAppsListsRequestListAppsListsPaginateTypeDef = TypedDict(
-    "ListAppsListsRequestListAppsListsPaginateTypeDef",
-    {
-        "DefaultLists": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
-    "_RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
-    {
-        "PolicyId": str,
-    },
-)
-_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef = TypedDict(
-    "_OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListComplianceStatusRequestListComplianceStatusPaginateTypeDef(
-    _RequiredListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
-    _OptionalListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
-):
-    pass
-
-ListMemberAccountsRequestListMemberAccountsPaginateTypeDef = TypedDict(
-    "ListMemberAccountsRequestListMemberAccountsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPoliciesRequestListPoliciesPaginateTypeDef = TypedDict(
-    "ListPoliciesRequestListPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProtocolsListsRequestListProtocolsListsPaginateTypeDef = TypedDict(
-    "ListProtocolsListsRequestListProtocolsListsPaginateTypeDef",
-    {
-        "DefaultLists": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
-    {
-        "ThirdPartyFirewall": ThirdPartyFirewallType,
-    },
-)
-_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef(
-    _RequiredListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
-    _OptionalListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
-):
-    pass
-
 ListPoliciesResponseTypeDef = TypedDict(
     "ListPoliciesResponseTypeDef",
     {
         "PolicyList": List[PolicySummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProtocolsListsResponseTypeDef = TypedDict(
     "ListProtocolsListsResponseTypeDef",
     {
         "ProtocolsLists": List[ProtocolsListDataSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceSetResourcesResponseTypeDef = TypedDict(
     "ListResourceSetResourcesResponseTypeDef",
     {
         "Items": List[ResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceSetsResponseTypeDef = TypedDict(
     "ListResourceSetsResponseTypeDef",
     {
         "ResourceSets": List[ResourceSetSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutProtocolsListRequestRequestTypeDef = TypedDict(
     "_RequiredPutProtocolsListRequestRequestTypeDef",
     {
         "ProtocolsList": ProtocolsListDataTypeDef,
@@ -1508,15 +1647,15 @@
 )
 
 ListThirdPartyFirewallFirewallPoliciesResponseTypeDef = TypedDict(
     "ListThirdPartyFirewallFirewallPoliciesResponseTypeDef",
     {
         "ThirdPartyFirewallFirewallPolicies": List[ThirdPartyFirewallFirewallPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkFirewallBlackHoleRouteDetectedViolationTypeDef = TypedDict(
     "NetworkFirewallBlackHoleRouteDetectedViolationTypeDef",
     {
         "ViolationTarget": str,
@@ -1659,29 +1798,57 @@
         "FMSPolicyUpdateFirewallCreationConfigAction": (
             FMSPolicyUpdateFirewallCreationConfigActionTypeDef
         ),
     },
     total=False,
 )
 
+GetAdminScopeResponseTypeDef = TypedDict(
+    "GetAdminScopeResponseTypeDef",
+    {
+        "AdminScope": AdminScopeTypeDef,
+        "Status": OrganizationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredPutAdminAccountRequestRequestTypeDef = TypedDict(
+    "_RequiredPutAdminAccountRequestRequestTypeDef",
+    {
+        "AdminAccount": str,
+    },
+)
+_OptionalPutAdminAccountRequestRequestTypeDef = TypedDict(
+    "_OptionalPutAdminAccountRequestRequestTypeDef",
+    {
+        "AdminScope": AdminScopeTypeDef,
+    },
+    total=False,
+)
+
+class PutAdminAccountRequestRequestTypeDef(
+    _RequiredPutAdminAccountRequestRequestTypeDef, _OptionalPutAdminAccountRequestRequestTypeDef
+):
+    pass
+
 ListAppsListsResponseTypeDef = TypedDict(
     "ListAppsListsResponseTypeDef",
     {
         "AppsLists": List[AppsListDataSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppsListResponseTypeDef = TypedDict(
     "GetAppsListResponseTypeDef",
     {
         "AppsList": AppsListDataTypeDef,
         "AppsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAppsListRequestRequestTypeDef = TypedDict(
     "_RequiredPutAppsListRequestRequestTypeDef",
     {
         "AppsList": AppsListDataTypeDef,
@@ -1701,32 +1868,32 @@
     pass
 
 PutAppsListResponseTypeDef = TypedDict(
     "PutAppsListResponseTypeDef",
     {
         "AppsList": AppsListDataTypeDef,
         "AppsListArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceDetailResponseTypeDef = TypedDict(
     "GetComplianceDetailResponseTypeDef",
     {
         "PolicyComplianceDetail": PolicyComplianceDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComplianceStatusResponseTypeDef = TypedDict(
     "ListComplianceStatusResponseTypeDef",
     {
         "PolicyComplianceStatusList": List[PolicyComplianceStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkFirewallPolicyDescriptionTypeDef = TypedDict(
     "NetworkFirewallPolicyDescriptionTypeDef",
     {
         "StatelessRuleGroups": List[StatelessRuleGroupTypeDef],
@@ -1808,14 +1975,15 @@
         "ResourceTypeList": List[str],
         "ResourceTags": List[ResourceTagTypeDef],
         "DeleteUnusedFMManagedResources": bool,
         "IncludeMap": Dict[CustomerPolicyScopeIdTypeType, List[str]],
         "ExcludeMap": Dict[CustomerPolicyScopeIdTypeType, List[str]],
         "ResourceSetIds": List[str],
         "PolicyDescription": str,
+        "PolicyStatus": CustomerPolicyStatusType,
     },
     total=False,
 )
 
 class PolicyTypeDef(_RequiredPolicyTypeDef, _OptionalPolicyTypeDef):
     pass
 
@@ -1840,15 +2008,15 @@
     pass
 
 GetPolicyResponseTypeDef = TypedDict(
     "GetPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
         "PolicyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutPolicyRequestRequestTypeDef",
     {
         "Policy": PolicyTypeDef,
@@ -1868,15 +2036,15 @@
     pass
 
 PutPolicyResponseTypeDef = TypedDict(
     "PutPolicyResponseTypeDef",
     {
         "Policy": PolicyTypeDef,
         "PolicyArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PossibleRemediationActionsTypeDef = TypedDict(
     "PossibleRemediationActionsTypeDef",
     {
         "Description": str,
@@ -1957,10 +2125,10 @@
 class ViolationDetailTypeDef(_RequiredViolationDetailTypeDef, _OptionalViolationDetailTypeDef):
     pass
 
 GetViolationDetailsResponseTypeDef = TypedDict(
     "GetViolationDetailsResponseTypeDef",
     {
         "ViolationDetail": ViolationDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/PKG-INFO` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-fms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FMS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FMS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-fms"></a>
 
 # types-aiobotocore-fms
 
 [![PyPI - types-aiobotocore-fms](https://img.shields.io/pypi/v/types-aiobotocore-fms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-fms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-fms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-fms?color=blue)](https://pypistats.org/packages/types-aiobotocore-fms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
+[aiobotocore.FMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/fms.html#FMS)
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
 [types-aiobotocore-fms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_fms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -271,28 +271,36 @@
 paginators.
 
 ```python
 from aiobotocore.session import get_session
 
 from types_aiobotocore_fms import FMSClient
 from types_aiobotocore_fms.paginator import (
+    ListAdminAccountsForOrganizationPaginator,
+    ListAdminsManagingAccountPaginator,
     ListAppsListsPaginator,
     ListComplianceStatusPaginator,
     ListMemberAccountsPaginator,
     ListPoliciesPaginator,
     ListProtocolsListsPaginator,
     ListThirdPartyFirewallFirewallPoliciesPaginator,
 )
 
 session = get_session()
 async with session.create_client("fms") as client:
     client: FMSClient
 
     # Explicit type annotations are optional here
     # Types should be correctly discovered by mypy and IDEs
+    list_admin_accounts_for_organization_paginator: ListAdminAccountsForOrganizationPaginator = (
+        client.get_paginator("list_admin_accounts_for_organization")
+    )
+    list_admins_managing_account_paginator: ListAdminsManagingAccountPaginator = (
+        client.get_paginator("list_admins_managing_account")
+    )
     list_apps_lists_paginator: ListAppsListsPaginator = client.get_paginator("list_apps_lists")
     list_compliance_status_paginator: ListComplianceStatusPaginator = client.get_paginator(
         "list_compliance_status"
     )
     list_member_accounts_paginator: ListMemberAccountsPaginator = client.get_paginator(
         "list_member_accounts"
     )
@@ -312,28 +320,33 @@
 `types_aiobotocore_fms.literals` module contains literals extracted from shapes
 that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_fms.literals import (
     AccountRoleStatusType,
     CustomerPolicyScopeIdTypeType,
+    CustomerPolicyStatusType,
     DependentServiceNameType,
     DestinationTypeType,
     FailedItemReasonType,
     FirewallDeploymentModelType,
+    ListAdminAccountsForOrganizationPaginatorName,
+    ListAdminsManagingAccountPaginatorName,
     ListAppsListsPaginatorName,
     ListComplianceStatusPaginatorName,
     ListMemberAccountsPaginatorName,
     ListPoliciesPaginatorName,
     ListProtocolsListsPaginatorName,
     ListThirdPartyFirewallFirewallPoliciesPaginatorName,
     MarketplaceSubscriptionOnboardingStatusType,
     NetworkFirewallOverrideActionType,
+    OrganizationStatusType,
     PolicyComplianceStatusTypeType,
     RemediationActionTypeType,
+    ResourceSetStatusType,
     RuleOrderType,
     SecurityServiceTypeType,
     TargetTypeType,
     ThirdPartyFirewallAssociationStatusType,
     ThirdPartyFirewallType,
     ViolationReasonType,
     FMSServiceName,
@@ -353,116 +366,129 @@
 ### Typed dictionaries
 
 `types_aiobotocore_fms.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_fms.type_defs import (
+    AccountScopeTypeDef,
     ActionTargetTypeDef,
+    AdminAccountSummaryTypeDef,
+    OrganizationalUnitScopeTypeDef,
+    PolicyTypeScopeTypeDef,
+    RegionScopeTypeDef,
     AppTypeDef,
     AssociateAdminAccountRequestRequestTypeDef,
     AssociateThirdPartyFirewallRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateThirdPartyFirewallResponseTypeDef,
     AwsEc2NetworkInterfaceViolationTypeDef,
     PartialMatchTypeDef,
     BatchAssociateResourceRequestRequestTypeDef,
     FailedItemTypeDef,
     BatchDisassociateResourceRequestRequestTypeDef,
     ComplianceViolatorTypeDef,
     DeleteAppsListRequestRequestTypeDef,
     DeletePolicyRequestRequestTypeDef,
     DeleteProtocolsListRequestRequestTypeDef,
     DeleteResourceSetRequestRequestTypeDef,
     DisassociateThirdPartyFirewallRequestRequestTypeDef,
+    DisassociateThirdPartyFirewallResponseTypeDef,
     DiscoveredResourceTypeDef,
     DnsDuplicateRuleGroupViolationTypeDef,
     DnsRuleGroupLimitExceededViolationTypeDef,
     DnsRuleGroupPriorityConflictViolationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluationResultTypeDef,
     ExpectedRouteTypeDef,
     FMSPolicyUpdateFirewallCreationConfigActionTypeDef,
     FirewallSubnetIsOutOfScopeViolationTypeDef,
     FirewallSubnetMissingVPCEndpointViolationTypeDef,
+    GetAdminAccountResponseTypeDef,
+    GetAdminScopeRequestRequestTypeDef,
     GetAppsListRequestRequestTypeDef,
     GetComplianceDetailRequestRequestTypeDef,
+    GetNotificationChannelResponseTypeDef,
     GetPolicyRequestRequestTypeDef,
     GetProtectionStatusRequestRequestTypeDef,
+    GetProtectionStatusResponseTypeDef,
     GetProtocolsListRequestRequestTypeDef,
     ProtocolsListDataTypeDef,
     GetResourceSetRequestRequestTypeDef,
     ResourceSetTypeDef,
     GetThirdPartyFirewallAssociationStatusRequestRequestTypeDef,
+    GetThirdPartyFirewallAssociationStatusResponseTypeDef,
     GetViolationDetailsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAdminAccountsForOrganizationRequestListAdminAccountsForOrganizationPaginateTypeDef,
+    ListAdminAccountsForOrganizationRequestRequestTypeDef,
+    ListAdminsManagingAccountRequestListAdminsManagingAccountPaginateTypeDef,
+    ListAdminsManagingAccountRequestRequestTypeDef,
+    ListAdminsManagingAccountResponseTypeDef,
+    ListAppsListsRequestListAppsListsPaginateTypeDef,
     ListAppsListsRequestRequestTypeDef,
+    ListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
     ListComplianceStatusRequestRequestTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
+    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
     ListMemberAccountsRequestRequestTypeDef,
+    ListMemberAccountsResponseTypeDef,
+    ListPoliciesRequestListPoliciesPaginateTypeDef,
     ListPoliciesRequestRequestTypeDef,
     PolicySummaryTypeDef,
+    ListProtocolsListsRequestListProtocolsListsPaginateTypeDef,
     ListProtocolsListsRequestRequestTypeDef,
     ProtocolsListDataSummaryTypeDef,
     ListResourceSetResourcesRequestRequestTypeDef,
     ResourceTypeDef,
     ListResourceSetsRequestRequestTypeDef,
     ResourceSetSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
+    ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
     ListThirdPartyFirewallFirewallPoliciesRequestRequestTypeDef,
     ThirdPartyFirewallFirewallPolicyTypeDef,
     RouteTypeDef,
     NetworkFirewallMissingExpectedRTViolationTypeDef,
     NetworkFirewallMissingFirewallViolationTypeDef,
     NetworkFirewallMissingSubnetViolationTypeDef,
     StatefulEngineOptionsTypeDef,
     StatelessRuleGroupTypeDef,
     NetworkFirewallPolicyTypeDef,
     NetworkFirewallStatefulRuleGroupOverrideTypeDef,
+    PaginatorConfigTypeDef,
     ThirdPartyFirewallPolicyTypeDef,
     ResourceTagTypeDef,
     PutNotificationChannelRequestRequestTypeDef,
     ThirdPartyFirewallMissingExpectedRouteTableViolationTypeDef,
     ThirdPartyFirewallMissingFirewallViolationTypeDef,
     ThirdPartyFirewallMissingSubnetViolationTypeDef,
+    ResponseMetadataTypeDef,
     SecurityGroupRuleDescriptionTypeDef,
     UntagResourceRequestRequestTypeDef,
     EC2AssociateRouteTableActionTypeDef,
     EC2CopyRouteTableActionTypeDef,
     EC2CreateRouteActionTypeDef,
     EC2CreateRouteTableActionTypeDef,
     EC2DeleteRouteActionTypeDef,
     EC2ReplaceRouteActionTypeDef,
     EC2ReplaceRouteTableAssociationActionTypeDef,
+    ListAdminAccountsForOrganizationResponseTypeDef,
+    AdminScopeTypeDef,
     AppsListDataSummaryTypeDef,
     AppsListDataTypeDef,
-    AssociateThirdPartyFirewallResponseTypeDef,
-    DisassociateThirdPartyFirewallResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAdminAccountResponseTypeDef,
-    GetNotificationChannelResponseTypeDef,
-    GetProtectionStatusResponseTypeDef,
-    GetThirdPartyFirewallAssociationStatusResponseTypeDef,
-    ListMemberAccountsResponseTypeDef,
     AwsEc2InstanceViolationTypeDef,
     BatchAssociateResourceResponseTypeDef,
     BatchDisassociateResourceResponseTypeDef,
     PolicyComplianceDetailTypeDef,
     ListDiscoveredResourcesResponseTypeDef,
     PolicyComplianceStatusTypeDef,
     NetworkFirewallMissingExpectedRoutesViolationTypeDef,
     GetProtocolsListResponseTypeDef,
     PutProtocolsListResponseTypeDef,
     GetResourceSetResponseTypeDef,
     PutResourceSetResponseTypeDef,
-    ListAppsListsRequestListAppsListsPaginateTypeDef,
-    ListComplianceStatusRequestListComplianceStatusPaginateTypeDef,
-    ListMemberAccountsRequestListMemberAccountsPaginateTypeDef,
-    ListPoliciesRequestListPoliciesPaginateTypeDef,
-    ListProtocolsListsRequestListProtocolsListsPaginateTypeDef,
-    ListThirdPartyFirewallFirewallPoliciesRequestListThirdPartyFirewallFirewallPoliciesPaginateTypeDef,
     ListPoliciesResponseTypeDef,
     ListProtocolsListsResponseTypeDef,
     ListResourceSetResourcesResponseTypeDef,
     ListResourceSetsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutProtocolsListRequestRequestTypeDef,
     PutResourceSetRequestRequestTypeDef,
@@ -474,14 +500,16 @@
     NetworkFirewallUnexpectedFirewallRoutesViolationTypeDef,
     NetworkFirewallUnexpectedGatewayRoutesViolationTypeDef,
     RouteHasOutOfScopeEndpointViolationTypeDef,
     StatefulRuleGroupTypeDef,
     PolicyOptionTypeDef,
     SecurityGroupRemediationActionTypeDef,
     RemediationActionTypeDef,
+    GetAdminScopeResponseTypeDef,
+    PutAdminAccountRequestRequestTypeDef,
     ListAppsListsResponseTypeDef,
     GetAppsListResponseTypeDef,
     PutAppsListRequestRequestTypeDef,
     PutAppsListResponseTypeDef,
     GetComplianceDetailResponseTypeDef,
     ListComplianceStatusResponseTypeDef,
     NetworkFirewallPolicyDescriptionTypeDef,
@@ -497,54 +525,54 @@
     PossibleRemediationActionsTypeDef,
     ResourceViolationTypeDef,
     ViolationDetailTypeDef,
     GetViolationDetailsResponseTypeDef,
 )
 
 
-def get_structure() -> ActionTargetTypeDef:
+def get_structure() -> AccountScopeTypeDef:
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

### Comparing `types-aiobotocore-fms-2.5.0.post1/types_aiobotocore_fms.egg-info/SOURCES.txt` & `types-aiobotocore-fms-2.5.1/types_aiobotocore_fms.egg-info/SOURCES.txt`

 * *Files identical despite different names*

