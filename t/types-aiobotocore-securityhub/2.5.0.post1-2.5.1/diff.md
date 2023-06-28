# Comparing `tmp/types-aiobotocore-securityhub-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-securityhub-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-securityhub-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-securityhub-2.5.1.tar", last modified: Wed Jun 28 01:44:09 2023, max compression
```

## Comparing `types-aiobotocore-securityhub-2.5.0.post1.tar` & `types-aiobotocore-securityhub-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.591610 types-aiobotocore-securityhub-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    46113 2023-03-11 12:27:18.591610 types-aiobotocore-securityhub-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    44526 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:18.591610 types-aiobotocore-securityhub-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:23:44.000000 types-aiobotocore-securityhub-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.587610 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/
--rw-r--r--   0 runner    (1001) docker     (123)     3153 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3152 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    44724 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    44647 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12537 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12535 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15232 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    15217 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   242751 2023-03-11 12:23:53.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   242708 2023-03-11 12:23:51.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:45.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.591610 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    46113 2023-03-11 12:27:18.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      889 2023-03-11 12:27:18.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:18.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:27:18.000000 types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.778212 types-aiobotocore-securityhub-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    51423 2023-06-28 01:44:09.770212 types-aiobotocore-securityhub-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    49842 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:09.778212 types-aiobotocore-securityhub-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.770212 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/
+-rw-r--r--   0 runner    (1001) docker     (123)     3955 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3954 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54849 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54758 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14068 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14066 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    19141 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19124 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   279900 2023-06-28 01:40:42.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   279833 2023-06-28 01:40:37.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:34.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.770212 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    51423 2023-06-28 01:44:09.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      889 2023-06-28 01:44:09.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:09.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:44:09.000000 types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/LICENSE` & `types-aiobotocore-securityhub-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/PKG-INFO` & `types-aiobotocore-securityhub-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-securityhub
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SecurityHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore securityhub type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-securityhub"></a>
 
 # types-aiobotocore-securityhub
 
 [![PyPI - types-aiobotocore-securityhub](https://img.shields.io/pypi/v/types-aiobotocore-securityhub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securityhub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-securityhub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securityhub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-securityhub?color=blue)](https://pypistats.org/packages/types-aiobotocore-securityhub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecurityHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub)
+[aiobotocore.SecurityHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub)
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
 [types-aiobotocore-securityhub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -278,21 +245,24 @@
 from types_aiobotocore_securityhub import SecurityHubClient
 from types_aiobotocore_securityhub.paginator import (
     DescribeActionTargetsPaginator,
     DescribeProductsPaginator,
     DescribeStandardsPaginator,
     DescribeStandardsControlsPaginator,
     GetEnabledStandardsPaginator,
+    GetFindingHistoryPaginator,
     GetFindingsPaginator,
     GetInsightsPaginator,
     ListEnabledProductsForImportPaginator,
     ListFindingAggregatorsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
+    ListSecurityControlDefinitionsPaginator,
+    ListStandardsControlAssociationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("securityhub") as client:
     client: SecurityHubClient
 
     # Explicit type annotations are optional here
@@ -308,72 +278,91 @@
     )
     describe_standards_controls_paginator: DescribeStandardsControlsPaginator = (
         client.get_paginator("describe_standards_controls")
     )
     get_enabled_standards_paginator: GetEnabledStandardsPaginator = client.get_paginator(
         "get_enabled_standards"
     )
+    get_finding_history_paginator: GetFindingHistoryPaginator = client.get_paginator(
+        "get_finding_history"
+    )
     get_findings_paginator: GetFindingsPaginator = client.get_paginator("get_findings")
     get_insights_paginator: GetInsightsPaginator = client.get_paginator("get_insights")
     list_enabled_products_for_import_paginator: ListEnabledProductsForImportPaginator = (
         client.get_paginator("list_enabled_products_for_import")
     )
     list_finding_aggregators_paginator: ListFindingAggregatorsPaginator = client.get_paginator(
         "list_finding_aggregators"
     )
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = (
         client.get_paginator("list_organization_admin_accounts")
     )
+    list_security_control_definitions_paginator: ListSecurityControlDefinitionsPaginator = (
+        client.get_paginator("list_security_control_definitions")
+    )
+    list_standards_control_associations_paginator: ListStandardsControlAssociationsPaginator = (
+        client.get_paginator("list_standards_control_associations")
+    )
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_securityhub.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_securityhub.literals import (
     AdminStatusType,
+    AssociationStatusType,
     AutoEnableStandardsType,
+    AutomationRulesActionTypeType,
     AwsIamAccessKeyStatusType,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType,
     ComplianceStatusType,
+    ControlFindingGeneratorType,
     ControlStatusType,
     DateRangeUnitType,
     DescribeActionTargetsPaginatorName,
     DescribeProductsPaginatorName,
     DescribeStandardsControlsPaginatorName,
     DescribeStandardsPaginatorName,
+    FindingHistoryUpdateSourceTypeType,
     GetEnabledStandardsPaginatorName,
+    GetFindingHistoryPaginatorName,
     GetFindingsPaginatorName,
     GetInsightsPaginatorName,
     IntegrationTypeType,
     ListEnabledProductsForImportPaginatorName,
     ListFindingAggregatorsPaginatorName,
     ListInvitationsPaginatorName,
     ListMembersPaginatorName,
     ListOrganizationAdminAccountsPaginatorName,
+    ListSecurityControlDefinitionsPaginatorName,
+    ListStandardsControlAssociationsPaginatorName,
     MalwareStateType,
     MalwareTypeType,
     MapFilterComparisonType,
     NetworkDirectionType,
     PartitionType,
     RecordStateType,
+    RegionAvailabilityStatusType,
+    RuleStatusType,
     SeverityLabelType,
     SeverityRatingType,
     SortOrderType,
     StandardsStatusType,
     StatusReasonCodeType,
     StringFilterComparisonType,
     ThreatIntelIndicatorCategoryType,
     ThreatIntelIndicatorTypeType,
+    UnprocessedErrorCodeType,
     VerificationStateType,
     VulnerabilityFixAvailableType,
     WorkflowStateType,
     WorkflowStatusType,
     SecurityHubServiceName,
     ServiceName,
     ResourceServiceName,
@@ -406,22 +395,40 @@
     IpOrganizationDetailsTypeDef,
     ActionRemotePortDetailsTypeDef,
     ActionTargetTypeDef,
     DnsRequestActionTypeDef,
     AdjustmentTypeDef,
     AdminAccountTypeDef,
     AssociatedStandardTypeDef,
+    AssociationStateDetailsTypeDef,
+    NoteUpdateTypeDef,
+    RelatedFindingTypeDef,
+    SeverityUpdateTypeDef,
+    WorkflowUpdateTypeDef,
+    MapFilterTypeDef,
+    NumberFilterTypeDef,
+    StringFilterTypeDef,
+    AutomationRulesMetadataTypeDef,
     AvailabilityZoneTypeDef,
+    AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef,
+    AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef,
+    AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef,
+    AwsAmazonMqBrokerUsersDetailsTypeDef,
+    AwsAmazonMqBrokerLogsPendingDetailsTypeDef,
     AwsApiCallActionDomainDetailsTypeDef,
     AwsApiGatewayAccessLogSettingsTypeDef,
     AwsApiGatewayCanarySettingsTypeDef,
     AwsApiGatewayEndpointConfigurationTypeDef,
     AwsApiGatewayMethodSettingsTypeDef,
     AwsCorsConfigurationTypeDef,
     AwsApiGatewayV2RouteSettingsTypeDef,
+    AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiLogConfigDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupLaunchTemplateLaunchTemplateSpecificationTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyInstancesDistributionDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateLaunchTemplateSpecificationTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateOverridesListDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationBlockDeviceMappingsEbsDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationInstanceMonitoringDetailsTypeDef,
@@ -461,14 +468,15 @@
     AwsDynamoDbTableRestoreSummaryTypeDef,
     AwsDynamoDbTableSseDescriptionTypeDef,
     AwsDynamoDbTableStreamSpecificationTypeDef,
     AwsDynamoDbTableProjectionTypeDef,
     AwsDynamoDbTableProvisionedThroughputOverrideTypeDef,
     AwsEc2EipDetailsTypeDef,
     AwsEc2InstanceMetadataOptionsTypeDef,
+    AwsEc2InstanceMonitoringDetailsTypeDef,
     AwsEc2InstanceNetworkInterfacesDetailsTypeDef,
     AwsEc2LaunchTemplateDataBlockDeviceMappingSetEbsDetailsTypeDef,
     AwsEc2LaunchTemplateDataCapacityReservationSpecificationCapacityReservationTargetDetailsTypeDef,
     AwsEc2LaunchTemplateDataCpuOptionsDetailsTypeDef,
     AwsEc2LaunchTemplateDataCreditSpecificationDetailsTypeDef,
     AwsEc2LaunchTemplateDataElasticGpuSpecificationSetDetailsTypeDef,
     AwsEc2LaunchTemplateDataElasticInferenceAcceleratorSetDetailsTypeDef,
@@ -497,14 +505,16 @@
     AwsEc2NetworkAclAssociationTypeDef,
     IcmpTypeCodeTypeDef,
     PortRangeFromToTypeDef,
     AwsEc2NetworkInterfaceAttachmentTypeDef,
     AwsEc2NetworkInterfaceIpV6AddressDetailTypeDef,
     AwsEc2NetworkInterfacePrivateIpAddressDetailTypeDef,
     AwsEc2NetworkInterfaceSecurityGroupTypeDef,
+    PropagatingVgwSetDetailsTypeDef,
+    RouteSetDetailsTypeDef,
     AwsEc2SecurityGroupIpRangeTypeDef,
     AwsEc2SecurityGroupIpv6RangeTypeDef,
     AwsEc2SecurityGroupPrefixListIdTypeDef,
     AwsEc2SecurityGroupUserIdGroupPairTypeDef,
     Ipv6CidrBlockAssociationTypeDef,
     AwsEc2TransitGatewayDetailsTypeDef,
     AwsEc2VolumeAttachmentTypeDef,
@@ -581,14 +591,22 @@
     AwsElbLoadBalancerBackendServerDescriptionTypeDef,
     AwsElbLoadBalancerHealthCheckTypeDef,
     AwsElbLoadBalancerInstanceTypeDef,
     AwsElbLoadBalancerSourceSecurityGroupTypeDef,
     AwsElbLoadBalancerListenerTypeDef,
     AwsElbv2LoadBalancerAttributeTypeDef,
     LoadBalancerStateTypeDef,
+    AwsEventSchemasRegistryDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef,
+    AwsGuardDutyDetectorFeaturesDetailsTypeDef,
     AwsIamAccessKeySessionContextAttributesTypeDef,
     AwsIamAccessKeySessionContextSessionIssuerTypeDef,
     AwsIamAttachedManagedPolicyTypeDef,
     AwsIamGroupPolicyTypeDef,
     AwsIamInstanceProfileRoleTypeDef,
     AwsIamPermissionsBoundaryTypeDef,
     AwsIamPolicyVersionTypeDef,
@@ -648,39 +666,38 @@
     AwsS3BucketBucketLifecycleConfigurationRulesNoncurrentVersionTransitionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesTransitionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateTagDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsTagDetailsTypeDef,
     AwsS3BucketBucketVersioningConfigurationTypeDef,
     AwsS3BucketLoggingConfigurationTypeDef,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleTypeDef,
+    AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef,
     AwsS3BucketServerSideEncryptionByDefaultTypeDef,
     AwsS3BucketWebsiteConfigurationRedirectToTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleConditionTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleRedirectTypeDef,
     AwsS3ObjectDetailsTypeDef,
     AwsSageMakerNotebookInstanceMetadataServiceConfigurationDetailsTypeDef,
     AwsSecretsManagerSecretRotationRulesTypeDef,
     BooleanFilterTypeDef,
     IpFilterTypeDef,
     KeywordFilterTypeDef,
-    MapFilterTypeDef,
-    NumberFilterTypeDef,
-    StringFilterTypeDef,
     AwsSecurityFindingIdentifierTypeDef,
     MalwareTypeDef,
     NoteTypeDef,
     PatchSummaryTypeDef,
     ProcessDetailsTypeDef,
-    RelatedFindingTypeDef,
     SeverityTypeDef,
     ThreatIntelIndicatorTypeDef,
     WorkflowTypeDef,
     AwsSnsTopicSubscriptionTypeDef,
     AwsSqsQueueDetailsTypeDef,
     AwsSsmComplianceSummaryTypeDef,
+    AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef,
     AwsWafRateBasedRuleMatchPredicateTypeDef,
     AwsWafRegionalRateBasedRuleMatchPredicateTypeDef,
     AwsWafRegionalRulePredicateListDetailsTypeDef,
     AwsWafRegionalRuleGroupRulesActionDetailsTypeDef,
     AwsWafRegionalWebAclRulesListActionDetailsTypeDef,
     AwsWafRegionalWebAclRulesListOverrideActionDetailsTypeDef,
     AwsWafRulePredicateListDetailsTypeDef,
@@ -688,74 +705,113 @@
     WafActionTypeDef,
     WafExcludedRuleTypeDef,
     WafOverrideActionTypeDef,
     AwsWafv2CustomHttpHeaderTypeDef,
     AwsWafv2VisibilityConfigDetailsTypeDef,
     AwsWafv2WebAclCaptchaConfigImmunityTimePropertyDetailsTypeDef,
     AwsXrayEncryptionConfigDetailsTypeDef,
+    BatchDeleteAutomationRulesRequestRequestTypeDef,
+    UnprocessedAutomationRuleTypeDef,
     BatchDisableStandardsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     StandardsSubscriptionRequestTypeDef,
+    BatchGetAutomationRulesRequestRequestTypeDef,
+    BatchGetSecurityControlsRequestRequestTypeDef,
+    SecurityControlTypeDef,
+    UnprocessedSecurityControlTypeDef,
+    StandardsControlAssociationIdTypeDef,
+    StandardsControlAssociationDetailTypeDef,
     ImportFindingsErrorTypeDef,
-    NoteUpdateTypeDef,
-    SeverityUpdateTypeDef,
-    WorkflowUpdateTypeDef,
+    StandardsControlAssociationUpdateTypeDef,
     CellTypeDef,
     ClassificationStatusTypeDef,
     StatusReasonTypeDef,
     VolumeMountTypeDef,
     CreateActionTargetRequestRequestTypeDef,
+    CreateActionTargetResponseTypeDef,
+    CreateAutomationRuleResponseTypeDef,
     CreateFindingAggregatorRequestRequestTypeDef,
+    CreateFindingAggregatorResponseTypeDef,
+    CreateInsightResponseTypeDef,
     ResultTypeDef,
     DateRangeTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DeleteActionTargetRequestRequestTypeDef,
+    DeleteActionTargetResponseTypeDef,
     DeleteFindingAggregatorRequestRequestTypeDef,
     DeleteInsightRequestRequestTypeDef,
+    DeleteInsightResponseTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef,
     DescribeActionTargetsRequestRequestTypeDef,
     DescribeHubRequestRequestTypeDef,
+    DescribeHubResponseTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
+    DescribeProductsRequestDescribeProductsPaginateTypeDef,
     DescribeProductsRequestRequestTypeDef,
     ProductTypeDef,
+    DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
     DescribeStandardsControlsRequestRequestTypeDef,
     StandardsControlTypeDef,
+    DescribeStandardsRequestDescribeStandardsPaginateTypeDef,
     DescribeStandardsRequestRequestTypeDef,
     DisableImportFindingsForProductRequestRequestTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateMembersRequestRequestTypeDef,
     EnableImportFindingsForProductRequestRequestTypeDef,
+    EnableImportFindingsForProductResponseTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     EnableSecurityHubRequestRequestTypeDef,
     FilePathsTypeDef,
     FindingAggregatorTypeDef,
+    FindingHistoryUpdateSourceTypeDef,
+    FindingHistoryUpdateTypeDef,
     FindingProviderSeverityTypeDef,
     FirewallPolicyStatefulRuleGroupReferencesDetailsTypeDef,
     FirewallPolicyStatelessRuleGroupReferencesDetailsTypeDef,
     InvitationTypeDef,
+    GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef,
     GetEnabledStandardsRequestRequestTypeDef,
     GetFindingAggregatorRequestRequestTypeDef,
+    GetFindingAggregatorResponseTypeDef,
     SortCriterionTypeDef,
     GetInsightResultsRequestRequestTypeDef,
+    GetInsightsRequestGetInsightsPaginateTypeDef,
     GetInsightsRequestRequestTypeDef,
+    GetInvitationsCountResponseTypeDef,
     GetMembersRequestRequestTypeDef,
     MemberTypeDef,
     InsightResultValueTypeDef,
     InviteMembersRequestRequestTypeDef,
+    ListAutomationRulesRequestRequestTypeDef,
+    ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef,
     ListEnabledProductsForImportRequestRequestTypeDef,
+    ListEnabledProductsForImportResponseTypeDef,
+    ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef,
     ListFindingAggregatorsRequestRequestTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
+    ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef,
+    ListSecurityControlDefinitionsRequestRequestTypeDef,
+    SecurityControlDefinitionTypeDef,
+    ListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef,
+    ListStandardsControlAssociationsRequestRequestTypeDef,
+    StandardsControlAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PortRangeTypeDef,
     RangeTypeDef,
     RecordTypeDef,
+    PaginatorConfigTypeDef,
     RecommendationTypeDef,
+    ResponseMetadataTypeDef,
     RuleGroupSourceListDetailsTypeDef,
     RuleGroupSourceStatefulRulesHeaderDetailsTypeDef,
     RuleGroupSourceStatefulRulesOptionsDetailsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesDestinationPortsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesDestinationsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesSourcePortsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesSourcesTypeDef,
@@ -766,25 +822,33 @@
     StandardsManagedByTypeDef,
     StandardsStatusReasonTypeDef,
     StatelessCustomPublishMetricActionDimensionTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateActionTargetRequestRequestTypeDef,
     UpdateFindingAggregatorRequestRequestTypeDef,
+    UpdateFindingAggregatorResponseTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     UpdateSecurityHubConfigurationRequestRequestTypeDef,
     UpdateStandardsControlRequestRequestTypeDef,
     VulnerabilityVendorTypeDef,
     CreateMembersRequestRequestTypeDef,
     ActionRemoteIpDetailsTypeDef,
+    DescribeActionTargetsResponseTypeDef,
     CvssTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
+    AssociationSetDetailsTypeDef,
+    AutomationRulesFindingFieldsUpdateTypeDef,
+    ListAutomationRulesResponseTypeDef,
+    AwsAmazonMqBrokerLogsDetailsTypeDef,
     AwsApiGatewayRestApiDetailsTypeDef,
     AwsApiGatewayStageDetailsTypeDef,
     AwsApiGatewayV2ApiDetailsTypeDef,
     AwsApiGatewayV2StageDetailsTypeDef,
+    AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationBlockDeviceMappingsDetailsTypeDef,
     AwsBackupBackupPlanRuleCopyActionsDetailsTypeDef,
     AwsBackupBackupVaultDetailsTypeDef,
     AwsBackupRecoveryPointDetailsTypeDef,
     AwsCertificateManagerCertificateDomainValidationOptionTypeDef,
     AwsCloudFormationStackDetailsTypeDef,
@@ -827,14 +891,16 @@
     AwsElasticBeanstalkEnvironmentDetailsTypeDef,
     AwsElasticsearchDomainElasticsearchClusterConfigDetailsTypeDef,
     AwsElasticsearchDomainLogPublishingOptionsTypeDef,
     AwsElbLoadBalancerPoliciesTypeDef,
     AwsElbLoadBalancerAttributesTypeDef,
     AwsElbLoadBalancerListenerDescriptionTypeDef,
     AwsElbv2LoadBalancerDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef,
     AwsIamAccessKeySessionContextTypeDef,
     AwsIamGroupDetailsTypeDef,
     AwsIamInstanceProfileTypeDef,
     AwsIamPolicyDetailsTypeDef,
     AwsIamUserDetailsTypeDef,
     AwsKinesisStreamDetailsTypeDef,
     AwsLambdaFunctionEnvironmentTypeDef,
@@ -846,94 +912,86 @@
     AwsRdsDbSnapshotDetailsTypeDef,
     AwsRdsDbPendingModifiedValuesTypeDef,
     AwsRdsDbSecurityGroupDetailsTypeDef,
     AwsRdsDbSubnetGroupSubnetTypeDef,
     AwsRedshiftClusterClusterParameterGroupTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsDetailsTypeDef,
     AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef,
+    AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef,
     AwsS3BucketServerSideEncryptionRuleTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleTypeDef,
     AwsSageMakerNotebookInstanceDetailsTypeDef,
     AwsSecretsManagerSecretDetailsTypeDef,
+    BatchUpdateFindingsRequestRequestTypeDef,
     BatchUpdateFindingsUnprocessedFindingTypeDef,
+    GetFindingHistoryRequestGetFindingHistoryPaginateTypeDef,
+    GetFindingHistoryRequestRequestTypeDef,
     AwsSnsTopicDetailsTypeDef,
     AwsSsmPatchTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef,
     AwsWafRateBasedRuleDetailsTypeDef,
     AwsWafRegionalRateBasedRuleDetailsTypeDef,
     AwsWafRegionalRuleDetailsTypeDef,
     AwsWafRegionalRuleGroupRulesDetailsTypeDef,
     AwsWafRegionalWebAclRulesListDetailsTypeDef,
     AwsWafRuleDetailsTypeDef,
     AwsWafRuleGroupRulesDetailsTypeDef,
     AwsWafWebAclRuleTypeDef,
     AwsWafv2CustomRequestHandlingDetailsTypeDef,
     AwsWafv2CustomResponseDetailsTypeDef,
     AwsWafv2WebAclCaptchaConfigDetailsTypeDef,
-    CreateActionTargetResponseTypeDef,
-    CreateFindingAggregatorResponseTypeDef,
-    CreateInsightResponseTypeDef,
-    DeleteActionTargetResponseTypeDef,
-    DeleteInsightResponseTypeDef,
-    DescribeActionTargetsResponseTypeDef,
-    DescribeHubResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    EnableImportFindingsForProductResponseTypeDef,
-    GetFindingAggregatorResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    ListEnabledProductsForImportResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateFindingAggregatorResponseTypeDef,
+    BatchDeleteAutomationRulesResponseTypeDef,
+    BatchUpdateAutomationRulesResponseTypeDef,
     BatchEnableStandardsRequestRequestTypeDef,
+    BatchGetSecurityControlsResponseTypeDef,
+    BatchGetStandardsControlAssociationsRequestRequestTypeDef,
+    UnprocessedStandardsControlAssociationTypeDef,
     BatchImportFindingsResponseTypeDef,
-    BatchUpdateFindingsRequestRequestTypeDef,
+    BatchUpdateStandardsControlAssociationsRequestRequestTypeDef,
+    UnprocessedStandardsControlAssociationUpdateTypeDef,
     ComplianceTypeDef,
     ContainerDetailsTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
     DateFilterTypeDef,
-    DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef,
-    DescribeProductsRequestDescribeProductsPaginateTypeDef,
-    DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
-    DescribeStandardsRequestDescribeStandardsPaginateTypeDef,
-    GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef,
-    GetInsightsRequestGetInsightsPaginateTypeDef,
-    ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef,
-    ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     DescribeProductsResponseTypeDef,
     DescribeStandardsControlsResponseTypeDef,
     ThreatTypeDef,
     ListFindingAggregatorsResponseTypeDef,
+    FindingHistoryRecordTypeDef,
     FindingProviderFieldsTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     ListInvitationsResponseTypeDef,
     GetMembersResponseTypeDef,
     ListMembersResponseTypeDef,
     InsightResultsTypeDef,
+    ListSecurityControlDefinitionsResponseTypeDef,
+    ListStandardsControlAssociationsResponseTypeDef,
     NetworkPathComponentDetailsTypeDef,
     NetworkTypeDef,
     PageTypeDef,
     RemediationTypeDef,
     RuleGroupSourceStatefulRulesDetailsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesTypeDef,
     RuleGroupVariablesTypeDef,
     StandardTypeDef,
     StandardsSubscriptionTypeDef,
     StatelessCustomPublishMetricActionTypeDef,
     AwsApiCallActionTypeDef,
     NetworkConnectionActionTypeDef,
     PortProbeDetailTypeDef,
     VulnerabilityTypeDef,
+    AwsEc2RouteTableDetailsTypeDef,
+    AutomationRulesActionTypeDef,
+    AwsAmazonMqBrokerDetailsTypeDef,
+    AwsAppSyncGraphQlApiDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationDetailsTypeDef,
     AwsBackupBackupPlanRuleDetailsTypeDef,
     AwsCertificateManagerCertificateRenewalSummaryTypeDef,
     AwsCloudFrontDistributionOriginItemTypeDef,
     AwsCloudFrontDistributionOriginGroupTypeDef,
     AwsCodeBuildProjectDetailsTypeDef,
@@ -948,35 +1006,42 @@
     AwsEcsTaskDefinitionContainerDefinitionsDetailsTypeDef,
     AwsEcsTaskDefinitionVolumesDetailsTypeDef,
     AwsEcsTaskDetailsTypeDef,
     AwsEfsAccessPointDetailsTypeDef,
     AwsEksClusterDetailsTypeDef,
     AwsElasticsearchDomainDetailsTypeDef,
     AwsElbLoadBalancerDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef,
     AwsIamAccessKeyDetailsTypeDef,
     AwsIamRoleDetailsTypeDef,
     AwsLambdaFunctionDetailsTypeDef,
     AwsOpenSearchServiceDomainDetailsTypeDef,
     AwsRdsDbSubnetGroupTypeDef,
     AwsRedshiftClusterDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateDetailsTypeDef,
     AwsS3BucketNotificationConfigurationFilterTypeDef,
+    AwsS3BucketObjectLockConfigurationTypeDef,
     AwsS3BucketServerSideEncryptionConfigurationTypeDef,
     AwsS3BucketWebsiteConfigurationTypeDef,
     BatchUpdateFindingsResponseTypeDef,
     AwsSsmPatchComplianceDetailsTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef,
     AwsWafRegionalRuleGroupDetailsTypeDef,
     AwsWafRegionalWebAclDetailsTypeDef,
     AwsWafRuleGroupDetailsTypeDef,
     AwsWafWebAclDetailsTypeDef,
     AwsWafv2ActionAllowDetailsTypeDef,
     AwsWafv2RulesActionCaptchaDetailsTypeDef,
     AwsWafv2RulesActionCountDetailsTypeDef,
     AwsWafv2ActionBlockDetailsTypeDef,
+    BatchGetStandardsControlAssociationsResponseTypeDef,
+    BatchUpdateStandardsControlAssociationsResponseTypeDef,
+    AutomationRulesFindingFiltersTypeDef,
     AwsSecurityFindingFiltersTypeDef,
+    GetFindingHistoryResponseTypeDef,
     GetInsightResultsResponseTypeDef,
     NetworkHeaderTypeDef,
     OccurrencesTypeDef,
     RuleGroupSourceStatelessRuleDefinitionTypeDef,
     DescribeStandardsResponseTypeDef,
     BatchDisableStandardsResponseTypeDef,
     BatchEnableStandardsResponseTypeDef,
@@ -988,19 +1053,24 @@
     AwsCertificateManagerCertificateDetailsTypeDef,
     AwsCloudFrontDistributionOriginsTypeDef,
     AwsCloudFrontDistributionOriginGroupsTypeDef,
     AwsDynamoDbTableDetailsTypeDef,
     AwsEc2LaunchTemplateDetailsTypeDef,
     AwsEcsClusterDetailsTypeDef,
     AwsEcsTaskDefinitionDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesDetailsTypeDef,
     AwsRdsDbInstanceDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterDetailsTypeDef,
     AwsS3BucketNotificationConfigurationDetailTypeDef,
+    AwsStepFunctionStateMachineDetailsTypeDef,
     AwsWafv2RulesActionDetailsTypeDef,
     AwsWafv2WebAclActionDetailsTypeDef,
+    AutomationRulesConfigTypeDef,
+    CreateAutomationRuleRequestRequestTypeDef,
+    UpdateAutomationRulesRequestItemTypeDef,
     CreateInsightRequestRequestTypeDef,
     GetFindingsRequestGetFindingsPaginateTypeDef,
     GetFindingsRequestRequestTypeDef,
     InsightTypeDef,
     UpdateFindingsRequestRequestTypeDef,
     UpdateInsightRequestRequestTypeDef,
     NetworkPathComponentTypeDef,
@@ -1008,17 +1078,20 @@
     SensitiveDataDetectionsTypeDef,
     RuleGroupSourceStatelessRulesDetailsTypeDef,
     FirewallPolicyStatelessCustomActionsDetailsTypeDef,
     RuleGroupSourceCustomActionsDetailsTypeDef,
     ActionTypeDef,
     AwsBackupBackupPlanDetailsTypeDef,
     AwsCloudFrontDistributionDetailsTypeDef,
+    AwsGuardDutyDetectorDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef,
     AwsS3BucketNotificationConfigurationTypeDef,
     AwsWafv2RulesDetailsTypeDef,
+    BatchGetAutomationRulesResponseTypeDef,
+    BatchUpdateAutomationRulesRequestRequestTypeDef,
     GetInsightsResponseTypeDef,
     CustomDataIdentifiersResultTypeDef,
     SensitiveDataResultTypeDef,
     FirewallPolicyDetailsTypeDef,
     RuleGroupSourceStatelessRulesAndCustomActionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationDetailsTypeDef,
     AwsWafv2RuleGroupDetailsTypeDef,
@@ -1045,43 +1118,43 @@
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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/README.md` & `types-aiobotocore-securityhub-2.5.1/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-securityhub
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SecurityHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore securityhub type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-securityhub"></a>
 
 # types-aiobotocore-securityhub
 
 [![PyPI - types-aiobotocore-securityhub](https://img.shields.io/pypi/v/types-aiobotocore-securityhub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securityhub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-securityhub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securityhub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-securityhub?color=blue)](https://pypistats.org/packages/types-aiobotocore-securityhub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecurityHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub)
+[aiobotocore.SecurityHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub)
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
 [types-aiobotocore-securityhub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -245,21 +278,24 @@
 from types_aiobotocore_securityhub import SecurityHubClient
 from types_aiobotocore_securityhub.paginator import (
     DescribeActionTargetsPaginator,
     DescribeProductsPaginator,
     DescribeStandardsPaginator,
     DescribeStandardsControlsPaginator,
     GetEnabledStandardsPaginator,
+    GetFindingHistoryPaginator,
     GetFindingsPaginator,
     GetInsightsPaginator,
     ListEnabledProductsForImportPaginator,
     ListFindingAggregatorsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
+    ListSecurityControlDefinitionsPaginator,
+    ListStandardsControlAssociationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("securityhub") as client:
     client: SecurityHubClient
 
     # Explicit type annotations are optional here
@@ -275,72 +311,91 @@
     )
     describe_standards_controls_paginator: DescribeStandardsControlsPaginator = (
         client.get_paginator("describe_standards_controls")
     )
     get_enabled_standards_paginator: GetEnabledStandardsPaginator = client.get_paginator(
         "get_enabled_standards"
     )
+    get_finding_history_paginator: GetFindingHistoryPaginator = client.get_paginator(
+        "get_finding_history"
+    )
     get_findings_paginator: GetFindingsPaginator = client.get_paginator("get_findings")
     get_insights_paginator: GetInsightsPaginator = client.get_paginator("get_insights")
     list_enabled_products_for_import_paginator: ListEnabledProductsForImportPaginator = (
         client.get_paginator("list_enabled_products_for_import")
     )
     list_finding_aggregators_paginator: ListFindingAggregatorsPaginator = client.get_paginator(
         "list_finding_aggregators"
     )
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = (
         client.get_paginator("list_organization_admin_accounts")
     )
+    list_security_control_definitions_paginator: ListSecurityControlDefinitionsPaginator = (
+        client.get_paginator("list_security_control_definitions")
+    )
+    list_standards_control_associations_paginator: ListStandardsControlAssociationsPaginator = (
+        client.get_paginator("list_standards_control_associations")
+    )
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_securityhub.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_securityhub.literals import (
     AdminStatusType,
+    AssociationStatusType,
     AutoEnableStandardsType,
+    AutomationRulesActionTypeType,
     AwsIamAccessKeyStatusType,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType,
     ComplianceStatusType,
+    ControlFindingGeneratorType,
     ControlStatusType,
     DateRangeUnitType,
     DescribeActionTargetsPaginatorName,
     DescribeProductsPaginatorName,
     DescribeStandardsControlsPaginatorName,
     DescribeStandardsPaginatorName,
+    FindingHistoryUpdateSourceTypeType,
     GetEnabledStandardsPaginatorName,
+    GetFindingHistoryPaginatorName,
     GetFindingsPaginatorName,
     GetInsightsPaginatorName,
     IntegrationTypeType,
     ListEnabledProductsForImportPaginatorName,
     ListFindingAggregatorsPaginatorName,
     ListInvitationsPaginatorName,
     ListMembersPaginatorName,
     ListOrganizationAdminAccountsPaginatorName,
+    ListSecurityControlDefinitionsPaginatorName,
+    ListStandardsControlAssociationsPaginatorName,
     MalwareStateType,
     MalwareTypeType,
     MapFilterComparisonType,
     NetworkDirectionType,
     PartitionType,
     RecordStateType,
+    RegionAvailabilityStatusType,
+    RuleStatusType,
     SeverityLabelType,
     SeverityRatingType,
     SortOrderType,
     StandardsStatusType,
     StatusReasonCodeType,
     StringFilterComparisonType,
     ThreatIntelIndicatorCategoryType,
     ThreatIntelIndicatorTypeType,
+    UnprocessedErrorCodeType,
     VerificationStateType,
     VulnerabilityFixAvailableType,
     WorkflowStateType,
     WorkflowStatusType,
     SecurityHubServiceName,
     ServiceName,
     ResourceServiceName,
@@ -373,22 +428,40 @@
     IpOrganizationDetailsTypeDef,
     ActionRemotePortDetailsTypeDef,
     ActionTargetTypeDef,
     DnsRequestActionTypeDef,
     AdjustmentTypeDef,
     AdminAccountTypeDef,
     AssociatedStandardTypeDef,
+    AssociationStateDetailsTypeDef,
+    NoteUpdateTypeDef,
+    RelatedFindingTypeDef,
+    SeverityUpdateTypeDef,
+    WorkflowUpdateTypeDef,
+    MapFilterTypeDef,
+    NumberFilterTypeDef,
+    StringFilterTypeDef,
+    AutomationRulesMetadataTypeDef,
     AvailabilityZoneTypeDef,
+    AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef,
+    AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef,
+    AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef,
+    AwsAmazonMqBrokerUsersDetailsTypeDef,
+    AwsAmazonMqBrokerLogsPendingDetailsTypeDef,
     AwsApiCallActionDomainDetailsTypeDef,
     AwsApiGatewayAccessLogSettingsTypeDef,
     AwsApiGatewayCanarySettingsTypeDef,
     AwsApiGatewayEndpointConfigurationTypeDef,
     AwsApiGatewayMethodSettingsTypeDef,
     AwsCorsConfigurationTypeDef,
     AwsApiGatewayV2RouteSettingsTypeDef,
+    AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiLogConfigDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupLaunchTemplateLaunchTemplateSpecificationTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyInstancesDistributionDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateLaunchTemplateSpecificationTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateOverridesListDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationBlockDeviceMappingsEbsDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationInstanceMonitoringDetailsTypeDef,
@@ -428,14 +501,15 @@
     AwsDynamoDbTableRestoreSummaryTypeDef,
     AwsDynamoDbTableSseDescriptionTypeDef,
     AwsDynamoDbTableStreamSpecificationTypeDef,
     AwsDynamoDbTableProjectionTypeDef,
     AwsDynamoDbTableProvisionedThroughputOverrideTypeDef,
     AwsEc2EipDetailsTypeDef,
     AwsEc2InstanceMetadataOptionsTypeDef,
+    AwsEc2InstanceMonitoringDetailsTypeDef,
     AwsEc2InstanceNetworkInterfacesDetailsTypeDef,
     AwsEc2LaunchTemplateDataBlockDeviceMappingSetEbsDetailsTypeDef,
     AwsEc2LaunchTemplateDataCapacityReservationSpecificationCapacityReservationTargetDetailsTypeDef,
     AwsEc2LaunchTemplateDataCpuOptionsDetailsTypeDef,
     AwsEc2LaunchTemplateDataCreditSpecificationDetailsTypeDef,
     AwsEc2LaunchTemplateDataElasticGpuSpecificationSetDetailsTypeDef,
     AwsEc2LaunchTemplateDataElasticInferenceAcceleratorSetDetailsTypeDef,
@@ -464,14 +538,16 @@
     AwsEc2NetworkAclAssociationTypeDef,
     IcmpTypeCodeTypeDef,
     PortRangeFromToTypeDef,
     AwsEc2NetworkInterfaceAttachmentTypeDef,
     AwsEc2NetworkInterfaceIpV6AddressDetailTypeDef,
     AwsEc2NetworkInterfacePrivateIpAddressDetailTypeDef,
     AwsEc2NetworkInterfaceSecurityGroupTypeDef,
+    PropagatingVgwSetDetailsTypeDef,
+    RouteSetDetailsTypeDef,
     AwsEc2SecurityGroupIpRangeTypeDef,
     AwsEc2SecurityGroupIpv6RangeTypeDef,
     AwsEc2SecurityGroupPrefixListIdTypeDef,
     AwsEc2SecurityGroupUserIdGroupPairTypeDef,
     Ipv6CidrBlockAssociationTypeDef,
     AwsEc2TransitGatewayDetailsTypeDef,
     AwsEc2VolumeAttachmentTypeDef,
@@ -548,14 +624,22 @@
     AwsElbLoadBalancerBackendServerDescriptionTypeDef,
     AwsElbLoadBalancerHealthCheckTypeDef,
     AwsElbLoadBalancerInstanceTypeDef,
     AwsElbLoadBalancerSourceSecurityGroupTypeDef,
     AwsElbLoadBalancerListenerTypeDef,
     AwsElbv2LoadBalancerAttributeTypeDef,
     LoadBalancerStateTypeDef,
+    AwsEventSchemasRegistryDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef,
+    AwsGuardDutyDetectorFeaturesDetailsTypeDef,
     AwsIamAccessKeySessionContextAttributesTypeDef,
     AwsIamAccessKeySessionContextSessionIssuerTypeDef,
     AwsIamAttachedManagedPolicyTypeDef,
     AwsIamGroupPolicyTypeDef,
     AwsIamInstanceProfileRoleTypeDef,
     AwsIamPermissionsBoundaryTypeDef,
     AwsIamPolicyVersionTypeDef,
@@ -615,39 +699,38 @@
     AwsS3BucketBucketLifecycleConfigurationRulesNoncurrentVersionTransitionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesTransitionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateTagDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsTagDetailsTypeDef,
     AwsS3BucketBucketVersioningConfigurationTypeDef,
     AwsS3BucketLoggingConfigurationTypeDef,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleTypeDef,
+    AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef,
     AwsS3BucketServerSideEncryptionByDefaultTypeDef,
     AwsS3BucketWebsiteConfigurationRedirectToTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleConditionTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleRedirectTypeDef,
     AwsS3ObjectDetailsTypeDef,
     AwsSageMakerNotebookInstanceMetadataServiceConfigurationDetailsTypeDef,
     AwsSecretsManagerSecretRotationRulesTypeDef,
     BooleanFilterTypeDef,
     IpFilterTypeDef,
     KeywordFilterTypeDef,
-    MapFilterTypeDef,
-    NumberFilterTypeDef,
-    StringFilterTypeDef,
     AwsSecurityFindingIdentifierTypeDef,
     MalwareTypeDef,
     NoteTypeDef,
     PatchSummaryTypeDef,
     ProcessDetailsTypeDef,
-    RelatedFindingTypeDef,
     SeverityTypeDef,
     ThreatIntelIndicatorTypeDef,
     WorkflowTypeDef,
     AwsSnsTopicSubscriptionTypeDef,
     AwsSqsQueueDetailsTypeDef,
     AwsSsmComplianceSummaryTypeDef,
+    AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef,
     AwsWafRateBasedRuleMatchPredicateTypeDef,
     AwsWafRegionalRateBasedRuleMatchPredicateTypeDef,
     AwsWafRegionalRulePredicateListDetailsTypeDef,
     AwsWafRegionalRuleGroupRulesActionDetailsTypeDef,
     AwsWafRegionalWebAclRulesListActionDetailsTypeDef,
     AwsWafRegionalWebAclRulesListOverrideActionDetailsTypeDef,
     AwsWafRulePredicateListDetailsTypeDef,
@@ -655,74 +738,113 @@
     WafActionTypeDef,
     WafExcludedRuleTypeDef,
     WafOverrideActionTypeDef,
     AwsWafv2CustomHttpHeaderTypeDef,
     AwsWafv2VisibilityConfigDetailsTypeDef,
     AwsWafv2WebAclCaptchaConfigImmunityTimePropertyDetailsTypeDef,
     AwsXrayEncryptionConfigDetailsTypeDef,
+    BatchDeleteAutomationRulesRequestRequestTypeDef,
+    UnprocessedAutomationRuleTypeDef,
     BatchDisableStandardsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     StandardsSubscriptionRequestTypeDef,
+    BatchGetAutomationRulesRequestRequestTypeDef,
+    BatchGetSecurityControlsRequestRequestTypeDef,
+    SecurityControlTypeDef,
+    UnprocessedSecurityControlTypeDef,
+    StandardsControlAssociationIdTypeDef,
+    StandardsControlAssociationDetailTypeDef,
     ImportFindingsErrorTypeDef,
-    NoteUpdateTypeDef,
-    SeverityUpdateTypeDef,
-    WorkflowUpdateTypeDef,
+    StandardsControlAssociationUpdateTypeDef,
     CellTypeDef,
     ClassificationStatusTypeDef,
     StatusReasonTypeDef,
     VolumeMountTypeDef,
     CreateActionTargetRequestRequestTypeDef,
+    CreateActionTargetResponseTypeDef,
+    CreateAutomationRuleResponseTypeDef,
     CreateFindingAggregatorRequestRequestTypeDef,
+    CreateFindingAggregatorResponseTypeDef,
+    CreateInsightResponseTypeDef,
     ResultTypeDef,
     DateRangeTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DeleteActionTargetRequestRequestTypeDef,
+    DeleteActionTargetResponseTypeDef,
     DeleteFindingAggregatorRequestRequestTypeDef,
     DeleteInsightRequestRequestTypeDef,
+    DeleteInsightResponseTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef,
     DescribeActionTargetsRequestRequestTypeDef,
     DescribeHubRequestRequestTypeDef,
+    DescribeHubResponseTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
+    DescribeProductsRequestDescribeProductsPaginateTypeDef,
     DescribeProductsRequestRequestTypeDef,
     ProductTypeDef,
+    DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
     DescribeStandardsControlsRequestRequestTypeDef,
     StandardsControlTypeDef,
+    DescribeStandardsRequestDescribeStandardsPaginateTypeDef,
     DescribeStandardsRequestRequestTypeDef,
     DisableImportFindingsForProductRequestRequestTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateMembersRequestRequestTypeDef,
     EnableImportFindingsForProductRequestRequestTypeDef,
+    EnableImportFindingsForProductResponseTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     EnableSecurityHubRequestRequestTypeDef,
     FilePathsTypeDef,
     FindingAggregatorTypeDef,
+    FindingHistoryUpdateSourceTypeDef,
+    FindingHistoryUpdateTypeDef,
     FindingProviderSeverityTypeDef,
     FirewallPolicyStatefulRuleGroupReferencesDetailsTypeDef,
     FirewallPolicyStatelessRuleGroupReferencesDetailsTypeDef,
     InvitationTypeDef,
+    GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef,
     GetEnabledStandardsRequestRequestTypeDef,
     GetFindingAggregatorRequestRequestTypeDef,
+    GetFindingAggregatorResponseTypeDef,
     SortCriterionTypeDef,
     GetInsightResultsRequestRequestTypeDef,
+    GetInsightsRequestGetInsightsPaginateTypeDef,
     GetInsightsRequestRequestTypeDef,
+    GetInvitationsCountResponseTypeDef,
     GetMembersRequestRequestTypeDef,
     MemberTypeDef,
     InsightResultValueTypeDef,
     InviteMembersRequestRequestTypeDef,
+    ListAutomationRulesRequestRequestTypeDef,
+    ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef,
     ListEnabledProductsForImportRequestRequestTypeDef,
+    ListEnabledProductsForImportResponseTypeDef,
+    ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef,
     ListFindingAggregatorsRequestRequestTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
+    ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef,
+    ListSecurityControlDefinitionsRequestRequestTypeDef,
+    SecurityControlDefinitionTypeDef,
+    ListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef,
+    ListStandardsControlAssociationsRequestRequestTypeDef,
+    StandardsControlAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PortRangeTypeDef,
     RangeTypeDef,
     RecordTypeDef,
+    PaginatorConfigTypeDef,
     RecommendationTypeDef,
+    ResponseMetadataTypeDef,
     RuleGroupSourceListDetailsTypeDef,
     RuleGroupSourceStatefulRulesHeaderDetailsTypeDef,
     RuleGroupSourceStatefulRulesOptionsDetailsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesDestinationPortsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesDestinationsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesSourcePortsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesSourcesTypeDef,
@@ -733,25 +855,33 @@
     StandardsManagedByTypeDef,
     StandardsStatusReasonTypeDef,
     StatelessCustomPublishMetricActionDimensionTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateActionTargetRequestRequestTypeDef,
     UpdateFindingAggregatorRequestRequestTypeDef,
+    UpdateFindingAggregatorResponseTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     UpdateSecurityHubConfigurationRequestRequestTypeDef,
     UpdateStandardsControlRequestRequestTypeDef,
     VulnerabilityVendorTypeDef,
     CreateMembersRequestRequestTypeDef,
     ActionRemoteIpDetailsTypeDef,
+    DescribeActionTargetsResponseTypeDef,
     CvssTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
+    AssociationSetDetailsTypeDef,
+    AutomationRulesFindingFieldsUpdateTypeDef,
+    ListAutomationRulesResponseTypeDef,
+    AwsAmazonMqBrokerLogsDetailsTypeDef,
     AwsApiGatewayRestApiDetailsTypeDef,
     AwsApiGatewayStageDetailsTypeDef,
     AwsApiGatewayV2ApiDetailsTypeDef,
     AwsApiGatewayV2StageDetailsTypeDef,
+    AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationBlockDeviceMappingsDetailsTypeDef,
     AwsBackupBackupPlanRuleCopyActionsDetailsTypeDef,
     AwsBackupBackupVaultDetailsTypeDef,
     AwsBackupRecoveryPointDetailsTypeDef,
     AwsCertificateManagerCertificateDomainValidationOptionTypeDef,
     AwsCloudFormationStackDetailsTypeDef,
@@ -794,14 +924,16 @@
     AwsElasticBeanstalkEnvironmentDetailsTypeDef,
     AwsElasticsearchDomainElasticsearchClusterConfigDetailsTypeDef,
     AwsElasticsearchDomainLogPublishingOptionsTypeDef,
     AwsElbLoadBalancerPoliciesTypeDef,
     AwsElbLoadBalancerAttributesTypeDef,
     AwsElbLoadBalancerListenerDescriptionTypeDef,
     AwsElbv2LoadBalancerDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef,
     AwsIamAccessKeySessionContextTypeDef,
     AwsIamGroupDetailsTypeDef,
     AwsIamInstanceProfileTypeDef,
     AwsIamPolicyDetailsTypeDef,
     AwsIamUserDetailsTypeDef,
     AwsKinesisStreamDetailsTypeDef,
     AwsLambdaFunctionEnvironmentTypeDef,
@@ -813,94 +945,86 @@
     AwsRdsDbSnapshotDetailsTypeDef,
     AwsRdsDbPendingModifiedValuesTypeDef,
     AwsRdsDbSecurityGroupDetailsTypeDef,
     AwsRdsDbSubnetGroupSubnetTypeDef,
     AwsRedshiftClusterClusterParameterGroupTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsDetailsTypeDef,
     AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef,
+    AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef,
     AwsS3BucketServerSideEncryptionRuleTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleTypeDef,
     AwsSageMakerNotebookInstanceDetailsTypeDef,
     AwsSecretsManagerSecretDetailsTypeDef,
+    BatchUpdateFindingsRequestRequestTypeDef,
     BatchUpdateFindingsUnprocessedFindingTypeDef,
+    GetFindingHistoryRequestGetFindingHistoryPaginateTypeDef,
+    GetFindingHistoryRequestRequestTypeDef,
     AwsSnsTopicDetailsTypeDef,
     AwsSsmPatchTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef,
     AwsWafRateBasedRuleDetailsTypeDef,
     AwsWafRegionalRateBasedRuleDetailsTypeDef,
     AwsWafRegionalRuleDetailsTypeDef,
     AwsWafRegionalRuleGroupRulesDetailsTypeDef,
     AwsWafRegionalWebAclRulesListDetailsTypeDef,
     AwsWafRuleDetailsTypeDef,
     AwsWafRuleGroupRulesDetailsTypeDef,
     AwsWafWebAclRuleTypeDef,
     AwsWafv2CustomRequestHandlingDetailsTypeDef,
     AwsWafv2CustomResponseDetailsTypeDef,
     AwsWafv2WebAclCaptchaConfigDetailsTypeDef,
-    CreateActionTargetResponseTypeDef,
-    CreateFindingAggregatorResponseTypeDef,
-    CreateInsightResponseTypeDef,
-    DeleteActionTargetResponseTypeDef,
-    DeleteInsightResponseTypeDef,
-    DescribeActionTargetsResponseTypeDef,
-    DescribeHubResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    EnableImportFindingsForProductResponseTypeDef,
-    GetFindingAggregatorResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    ListEnabledProductsForImportResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateFindingAggregatorResponseTypeDef,
+    BatchDeleteAutomationRulesResponseTypeDef,
+    BatchUpdateAutomationRulesResponseTypeDef,
     BatchEnableStandardsRequestRequestTypeDef,
+    BatchGetSecurityControlsResponseTypeDef,
+    BatchGetStandardsControlAssociationsRequestRequestTypeDef,
+    UnprocessedStandardsControlAssociationTypeDef,
     BatchImportFindingsResponseTypeDef,
-    BatchUpdateFindingsRequestRequestTypeDef,
+    BatchUpdateStandardsControlAssociationsRequestRequestTypeDef,
+    UnprocessedStandardsControlAssociationUpdateTypeDef,
     ComplianceTypeDef,
     ContainerDetailsTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
     DateFilterTypeDef,
-    DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef,
-    DescribeProductsRequestDescribeProductsPaginateTypeDef,
-    DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
-    DescribeStandardsRequestDescribeStandardsPaginateTypeDef,
-    GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef,
-    GetInsightsRequestGetInsightsPaginateTypeDef,
-    ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef,
-    ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     DescribeProductsResponseTypeDef,
     DescribeStandardsControlsResponseTypeDef,
     ThreatTypeDef,
     ListFindingAggregatorsResponseTypeDef,
+    FindingHistoryRecordTypeDef,
     FindingProviderFieldsTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     ListInvitationsResponseTypeDef,
     GetMembersResponseTypeDef,
     ListMembersResponseTypeDef,
     InsightResultsTypeDef,
+    ListSecurityControlDefinitionsResponseTypeDef,
+    ListStandardsControlAssociationsResponseTypeDef,
     NetworkPathComponentDetailsTypeDef,
     NetworkTypeDef,
     PageTypeDef,
     RemediationTypeDef,
     RuleGroupSourceStatefulRulesDetailsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesTypeDef,
     RuleGroupVariablesTypeDef,
     StandardTypeDef,
     StandardsSubscriptionTypeDef,
     StatelessCustomPublishMetricActionTypeDef,
     AwsApiCallActionTypeDef,
     NetworkConnectionActionTypeDef,
     PortProbeDetailTypeDef,
     VulnerabilityTypeDef,
+    AwsEc2RouteTableDetailsTypeDef,
+    AutomationRulesActionTypeDef,
+    AwsAmazonMqBrokerDetailsTypeDef,
+    AwsAppSyncGraphQlApiDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationDetailsTypeDef,
     AwsBackupBackupPlanRuleDetailsTypeDef,
     AwsCertificateManagerCertificateRenewalSummaryTypeDef,
     AwsCloudFrontDistributionOriginItemTypeDef,
     AwsCloudFrontDistributionOriginGroupTypeDef,
     AwsCodeBuildProjectDetailsTypeDef,
@@ -915,35 +1039,42 @@
     AwsEcsTaskDefinitionContainerDefinitionsDetailsTypeDef,
     AwsEcsTaskDefinitionVolumesDetailsTypeDef,
     AwsEcsTaskDetailsTypeDef,
     AwsEfsAccessPointDetailsTypeDef,
     AwsEksClusterDetailsTypeDef,
     AwsElasticsearchDomainDetailsTypeDef,
     AwsElbLoadBalancerDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef,
     AwsIamAccessKeyDetailsTypeDef,
     AwsIamRoleDetailsTypeDef,
     AwsLambdaFunctionDetailsTypeDef,
     AwsOpenSearchServiceDomainDetailsTypeDef,
     AwsRdsDbSubnetGroupTypeDef,
     AwsRedshiftClusterDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateDetailsTypeDef,
     AwsS3BucketNotificationConfigurationFilterTypeDef,
+    AwsS3BucketObjectLockConfigurationTypeDef,
     AwsS3BucketServerSideEncryptionConfigurationTypeDef,
     AwsS3BucketWebsiteConfigurationTypeDef,
     BatchUpdateFindingsResponseTypeDef,
     AwsSsmPatchComplianceDetailsTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef,
     AwsWafRegionalRuleGroupDetailsTypeDef,
     AwsWafRegionalWebAclDetailsTypeDef,
     AwsWafRuleGroupDetailsTypeDef,
     AwsWafWebAclDetailsTypeDef,
     AwsWafv2ActionAllowDetailsTypeDef,
     AwsWafv2RulesActionCaptchaDetailsTypeDef,
     AwsWafv2RulesActionCountDetailsTypeDef,
     AwsWafv2ActionBlockDetailsTypeDef,
+    BatchGetStandardsControlAssociationsResponseTypeDef,
+    BatchUpdateStandardsControlAssociationsResponseTypeDef,
+    AutomationRulesFindingFiltersTypeDef,
     AwsSecurityFindingFiltersTypeDef,
+    GetFindingHistoryResponseTypeDef,
     GetInsightResultsResponseTypeDef,
     NetworkHeaderTypeDef,
     OccurrencesTypeDef,
     RuleGroupSourceStatelessRuleDefinitionTypeDef,
     DescribeStandardsResponseTypeDef,
     BatchDisableStandardsResponseTypeDef,
     BatchEnableStandardsResponseTypeDef,
@@ -955,19 +1086,24 @@
     AwsCertificateManagerCertificateDetailsTypeDef,
     AwsCloudFrontDistributionOriginsTypeDef,
     AwsCloudFrontDistributionOriginGroupsTypeDef,
     AwsDynamoDbTableDetailsTypeDef,
     AwsEc2LaunchTemplateDetailsTypeDef,
     AwsEcsClusterDetailsTypeDef,
     AwsEcsTaskDefinitionDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesDetailsTypeDef,
     AwsRdsDbInstanceDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterDetailsTypeDef,
     AwsS3BucketNotificationConfigurationDetailTypeDef,
+    AwsStepFunctionStateMachineDetailsTypeDef,
     AwsWafv2RulesActionDetailsTypeDef,
     AwsWafv2WebAclActionDetailsTypeDef,
+    AutomationRulesConfigTypeDef,
+    CreateAutomationRuleRequestRequestTypeDef,
+    UpdateAutomationRulesRequestItemTypeDef,
     CreateInsightRequestRequestTypeDef,
     GetFindingsRequestGetFindingsPaginateTypeDef,
     GetFindingsRequestRequestTypeDef,
     InsightTypeDef,
     UpdateFindingsRequestRequestTypeDef,
     UpdateInsightRequestRequestTypeDef,
     NetworkPathComponentTypeDef,
@@ -975,17 +1111,20 @@
     SensitiveDataDetectionsTypeDef,
     RuleGroupSourceStatelessRulesDetailsTypeDef,
     FirewallPolicyStatelessCustomActionsDetailsTypeDef,
     RuleGroupSourceCustomActionsDetailsTypeDef,
     ActionTypeDef,
     AwsBackupBackupPlanDetailsTypeDef,
     AwsCloudFrontDistributionDetailsTypeDef,
+    AwsGuardDutyDetectorDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef,
     AwsS3BucketNotificationConfigurationTypeDef,
     AwsWafv2RulesDetailsTypeDef,
+    BatchGetAutomationRulesResponseTypeDef,
+    BatchUpdateAutomationRulesRequestRequestTypeDef,
     GetInsightsResponseTypeDef,
     CustomDataIdentifiersResultTypeDef,
     SensitiveDataResultTypeDef,
     FirewallPolicyDetailsTypeDef,
     RuleGroupSourceStatelessRulesAndCustomActionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationDetailsTypeDef,
     AwsWafv2RuleGroupDetailsTypeDef,
@@ -1012,43 +1151,43 @@
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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/setup.py` & `types-aiobotocore-securityhub-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-securityhub.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-securityhub",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_securityhub"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SecurityHub 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SecurityHub 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/"
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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/__init__.py` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/__init__.py`

 * *Files 23% similar despite different names*

```diff
@@ -8,72 +8,84 @@
     from types_aiobotocore_securityhub import (
         Client,
         DescribeActionTargetsPaginator,
         DescribeProductsPaginator,
         DescribeStandardsControlsPaginator,
         DescribeStandardsPaginator,
         GetEnabledStandardsPaginator,
+        GetFindingHistoryPaginator,
         GetFindingsPaginator,
         GetInsightsPaginator,
         ListEnabledProductsForImportPaginator,
         ListFindingAggregatorsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
+        ListSecurityControlDefinitionsPaginator,
+        ListStandardsControlAssociationsPaginator,
         SecurityHubClient,
     )
 
     session = get_session()
     async with session.create_client("securityhub") as client:
         client: SecurityHubClient
         ...
 
 
     describe_action_targets_paginator: DescribeActionTargetsPaginator = client.get_paginator("describe_action_targets")
     describe_products_paginator: DescribeProductsPaginator = client.get_paginator("describe_products")
     describe_standards_paginator: DescribeStandardsPaginator = client.get_paginator("describe_standards")
     describe_standards_controls_paginator: DescribeStandardsControlsPaginator = client.get_paginator("describe_standards_controls")
     get_enabled_standards_paginator: GetEnabledStandardsPaginator = client.get_paginator("get_enabled_standards")
+    get_finding_history_paginator: GetFindingHistoryPaginator = client.get_paginator("get_finding_history")
     get_findings_paginator: GetFindingsPaginator = client.get_paginator("get_findings")
     get_insights_paginator: GetInsightsPaginator = client.get_paginator("get_insights")
     list_enabled_products_for_import_paginator: ListEnabledProductsForImportPaginator = client.get_paginator("list_enabled_products_for_import")
     list_finding_aggregators_paginator: ListFindingAggregatorsPaginator = client.get_paginator("list_finding_aggregators")
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
+    list_security_control_definitions_paginator: ListSecurityControlDefinitionsPaginator = client.get_paginator("list_security_control_definitions")
+    list_standards_control_associations_paginator: ListStandardsControlAssociationsPaginator = client.get_paginator("list_standards_control_associations")
     ```
 """
 from .client import SecurityHubClient
 from .paginator import (
     DescribeActionTargetsPaginator,
     DescribeProductsPaginator,
     DescribeStandardsControlsPaginator,
     DescribeStandardsPaginator,
     GetEnabledStandardsPaginator,
+    GetFindingHistoryPaginator,
     GetFindingsPaginator,
     GetInsightsPaginator,
     ListEnabledProductsForImportPaginator,
     ListFindingAggregatorsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
+    ListSecurityControlDefinitionsPaginator,
+    ListStandardsControlAssociationsPaginator,
 )
 
 Client = SecurityHubClient
 
 
 __all__ = (
     "Client",
     "DescribeActionTargetsPaginator",
     "DescribeProductsPaginator",
     "DescribeStandardsControlsPaginator",
     "DescribeStandardsPaginator",
     "GetEnabledStandardsPaginator",
+    "GetFindingHistoryPaginator",
     "GetFindingsPaginator",
     "GetInsightsPaginator",
     "ListEnabledProductsForImportPaginator",
     "ListFindingAggregatorsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
+    "ListSecurityControlDefinitionsPaginator",
+    "ListStandardsControlAssociationsPaginator",
     "SecurityHubClient",
 )
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/__init__.pyi` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/__init__.pyi`

 * *Files 23% similar despite different names*

```diff
@@ -8,71 +8,83 @@
     from types_aiobotocore_securityhub import (
         Client,
         DescribeActionTargetsPaginator,
         DescribeProductsPaginator,
         DescribeStandardsControlsPaginator,
         DescribeStandardsPaginator,
         GetEnabledStandardsPaginator,
+        GetFindingHistoryPaginator,
         GetFindingsPaginator,
         GetInsightsPaginator,
         ListEnabledProductsForImportPaginator,
         ListFindingAggregatorsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
+        ListSecurityControlDefinitionsPaginator,
+        ListStandardsControlAssociationsPaginator,
         SecurityHubClient,
     )
 
     session = get_session()
     async with session.create_client("securityhub") as client:
         client: SecurityHubClient
         ...
 
 
     describe_action_targets_paginator: DescribeActionTargetsPaginator = client.get_paginator("describe_action_targets")
     describe_products_paginator: DescribeProductsPaginator = client.get_paginator("describe_products")
     describe_standards_paginator: DescribeStandardsPaginator = client.get_paginator("describe_standards")
     describe_standards_controls_paginator: DescribeStandardsControlsPaginator = client.get_paginator("describe_standards_controls")
     get_enabled_standards_paginator: GetEnabledStandardsPaginator = client.get_paginator("get_enabled_standards")
+    get_finding_history_paginator: GetFindingHistoryPaginator = client.get_paginator("get_finding_history")
     get_findings_paginator: GetFindingsPaginator = client.get_paginator("get_findings")
     get_insights_paginator: GetInsightsPaginator = client.get_paginator("get_insights")
     list_enabled_products_for_import_paginator: ListEnabledProductsForImportPaginator = client.get_paginator("list_enabled_products_for_import")
     list_finding_aggregators_paginator: ListFindingAggregatorsPaginator = client.get_paginator("list_finding_aggregators")
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
+    list_security_control_definitions_paginator: ListSecurityControlDefinitionsPaginator = client.get_paginator("list_security_control_definitions")
+    list_standards_control_associations_paginator: ListStandardsControlAssociationsPaginator = client.get_paginator("list_standards_control_associations")
     ```
 """
 from .client import SecurityHubClient
 from .paginator import (
     DescribeActionTargetsPaginator,
     DescribeProductsPaginator,
     DescribeStandardsControlsPaginator,
     DescribeStandardsPaginator,
     GetEnabledStandardsPaginator,
+    GetFindingHistoryPaginator,
     GetFindingsPaginator,
     GetInsightsPaginator,
     ListEnabledProductsForImportPaginator,
     ListFindingAggregatorsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
+    ListSecurityControlDefinitionsPaginator,
+    ListStandardsControlAssociationsPaginator,
 )
 
 Client = SecurityHubClient
 
 __all__ = (
     "Client",
     "DescribeActionTargetsPaginator",
     "DescribeProductsPaginator",
     "DescribeStandardsControlsPaginator",
     "DescribeStandardsPaginator",
     "GetEnabledStandardsPaginator",
+    "GetFindingHistoryPaginator",
     "GetFindingsPaginator",
     "GetInsightsPaginator",
     "ListEnabledProductsForImportPaginator",
     "ListFindingAggregatorsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
+    "ListSecurityControlDefinitionsPaginator",
+    "ListStandardsControlAssociationsPaginator",
     "SecurityHubClient",
 )
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/__main__.py` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SecurityHub 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SecurityHub 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub\nOther"
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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/client.py` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/client.py`

 * *Files 9% similar despite different names*

```diff
@@ -11,49 +11,64 @@
 
     session = get_session()
     async with session.create_client("securityhub") as client:
         client: SecurityHubClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from datetime import datetime
+from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AutoEnableStandardsType,
+    ControlFindingGeneratorType,
     ControlStatusType,
     RecordStateType,
+    RuleStatusType,
     VerificationStateType,
 )
 from .paginator import (
     DescribeActionTargetsPaginator,
     DescribeProductsPaginator,
     DescribeStandardsControlsPaginator,
     DescribeStandardsPaginator,
     GetEnabledStandardsPaginator,
+    GetFindingHistoryPaginator,
     GetFindingsPaginator,
     GetInsightsPaginator,
     ListEnabledProductsForImportPaginator,
     ListFindingAggregatorsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
+    ListSecurityControlDefinitionsPaginator,
+    ListStandardsControlAssociationsPaginator,
 )
 from .type_defs import (
     AccountDetailsTypeDef,
+    AutomationRulesActionTypeDef,
+    AutomationRulesFindingFiltersTypeDef,
     AwsSecurityFindingFiltersTypeDef,
     AwsSecurityFindingIdentifierTypeDef,
     AwsSecurityFindingTypeDef,
+    BatchDeleteAutomationRulesResponseTypeDef,
     BatchDisableStandardsResponseTypeDef,
     BatchEnableStandardsResponseTypeDef,
+    BatchGetAutomationRulesResponseTypeDef,
+    BatchGetSecurityControlsResponseTypeDef,
+    BatchGetStandardsControlAssociationsResponseTypeDef,
     BatchImportFindingsResponseTypeDef,
+    BatchUpdateAutomationRulesResponseTypeDef,
     BatchUpdateFindingsResponseTypeDef,
+    BatchUpdateStandardsControlAssociationsResponseTypeDef,
     CreateActionTargetResponseTypeDef,
+    CreateAutomationRuleResponseTypeDef,
     CreateFindingAggregatorResponseTypeDef,
     CreateInsightResponseTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteActionTargetResponseTypeDef,
     DeleteInsightResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
@@ -64,32 +79,39 @@
     DescribeProductsResponseTypeDef,
     DescribeStandardsControlsResponseTypeDef,
     DescribeStandardsResponseTypeDef,
     EnableImportFindingsForProductResponseTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetEnabledStandardsResponseTypeDef,
     GetFindingAggregatorResponseTypeDef,
+    GetFindingHistoryResponseTypeDef,
     GetFindingsResponseTypeDef,
     GetInsightResultsResponseTypeDef,
     GetInsightsResponseTypeDef,
     GetInvitationsCountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     GetMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
+    ListAutomationRulesResponseTypeDef,
     ListEnabledProductsForImportResponseTypeDef,
     ListFindingAggregatorsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
+    ListSecurityControlDefinitionsResponseTypeDef,
+    ListStandardsControlAssociationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     NoteUpdateTypeDef,
     RelatedFindingTypeDef,
     SeverityUpdateTypeDef,
     SortCriterionTypeDef,
+    StandardsControlAssociationIdTypeDef,
+    StandardsControlAssociationUpdateTypeDef,
     StandardsSubscriptionRequestTypeDef,
+    UpdateAutomationRulesRequestItemTypeDef,
     UpdateFindingAggregatorResponseTypeDef,
     WorkflowUpdateTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -150,19 +172,29 @@
         """
         This method is deprecated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.accept_invitation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#accept_invitation)
         """
 
+    async def batch_delete_automation_rules(
+        self, *, AutomationRulesArns: Sequence[str]
+    ) -> BatchDeleteAutomationRulesResponseTypeDef:
+        """
+        Deletes one or more automation rules.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_delete_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_delete_automation_rules)
+        """
+
     async def batch_disable_standards(
         self, *, StandardsSubscriptionArns: Sequence[str]
     ) -> BatchDisableStandardsResponseTypeDef:
         """
-        Disables the standards specified by the provided `StandardsSubscriptionArns` .
+        Disables the standards specified by the provided `StandardsSubscriptionArns`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_disable_standards)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_disable_standards)
         """
 
     async def batch_enable_standards(
         self, *, StandardsSubscriptionRequests: Sequence[StandardsSubscriptionRequestTypeDef]
@@ -170,24 +202,70 @@
         """
         Enables the standards specified by the provided `StandardsArn`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_enable_standards)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_enable_standards)
         """
 
+    async def batch_get_automation_rules(
+        self, *, AutomationRulesArns: Sequence[str]
+    ) -> BatchGetAutomationRulesResponseTypeDef:
+        """
+        Retrieves a list of details for automation rules based on rule Amazon Resource
+        Names (ARNs).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_get_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_get_automation_rules)
+        """
+
+    async def batch_get_security_controls(
+        self, *, SecurityControlIds: Sequence[str]
+    ) -> BatchGetSecurityControlsResponseTypeDef:
+        """
+        Provides details about a batch of security controls for the current Amazon Web
+        Services account and Amazon Web Services Region.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_get_security_controls)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_get_security_controls)
+        """
+
+    async def batch_get_standards_control_associations(
+        self, *, StandardsControlAssociationIds: Sequence[StandardsControlAssociationIdTypeDef]
+    ) -> BatchGetStandardsControlAssociationsResponseTypeDef:
+        """
+        For a batch of security controls and standards, identifies whether each control
+        is currently enabled or disabled in a standard.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_get_standards_control_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_get_standards_control_associations)
+        """
+
     async def batch_import_findings(
         self, *, Findings: Sequence[AwsSecurityFindingTypeDef]
     ) -> BatchImportFindingsResponseTypeDef:
         """
         Imports security findings generated by a finding provider into Security Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_import_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_import_findings)
         """
 
+    async def batch_update_automation_rules(
+        self,
+        *,
+        UpdateAutomationRulesRequestItems: Sequence[UpdateAutomationRulesRequestItemTypeDef]
+    ) -> BatchUpdateAutomationRulesResponseTypeDef:
+        """
+        Updates one or more automation rules based on rule Amazon Resource Names (ARNs)
+        and input parameters.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_update_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_update_automation_rules)
+        """
+
     async def batch_update_findings(
         self,
         *,
         FindingIdentifiers: Sequence[AwsSecurityFindingIdentifierTypeDef],
         Note: NoteUpdateTypeDef = ...,
         Severity: SeverityUpdateTypeDef = ...,
         VerificationState: VerificationStateType = ...,
@@ -202,14 +280,27 @@
         Used by Security Hub customers to update information about their investigation
         into a finding.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_update_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_update_findings)
         """
 
+    async def batch_update_standards_control_associations(
+        self,
+        *,
+        StandardsControlAssociationUpdates: Sequence[StandardsControlAssociationUpdateTypeDef]
+    ) -> BatchUpdateStandardsControlAssociationsResponseTypeDef:
+        """
+        For a batch of security controls and standards, this operation updates the
+        enablement status of a control in a standard.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_update_standards_control_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_update_standards_control_associations)
+        """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#can_paginate)
         """
@@ -228,14 +319,33 @@
         """
         Creates a custom action target in Security Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.create_action_target)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#create_action_target)
         """
 
+    async def create_automation_rule(
+        self,
+        *,
+        RuleOrder: int,
+        RuleName: str,
+        Description: str,
+        Criteria: AutomationRulesFindingFiltersTypeDef,
+        Actions: Sequence[AutomationRulesActionTypeDef],
+        Tags: Mapping[str, str] = ...,
+        RuleStatus: RuleStatusType = ...,
+        IsTerminal: bool = ...
+    ) -> CreateAutomationRuleResponseTypeDef:
+        """
+        Creates an automation rule based on input parameters.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.create_automation_rule)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#create_automation_rule)
+        """
+
     async def create_finding_aggregator(
         self, *, RegionLinkingMode: str, Regions: Sequence[str] = ...
     ) -> CreateFindingAggregatorResponseTypeDef:
         """
         Used to enable finding aggregation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.create_finding_aggregator)
@@ -289,15 +399,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.delete_finding_aggregator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#delete_finding_aggregator)
         """
 
     async def delete_insight(self, *, InsightArn: str) -> DeleteInsightResponseTypeDef:
         """
-        Deletes the insight specified by the `InsightArn` .
+        Deletes the insight specified by the `InsightArn`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.delete_insight)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#delete_insight)
         """
 
     async def delete_invitations(
         self, *, AccountIds: Sequence[str]
@@ -444,15 +554,19 @@
         Designates the Security Hub administrator account for an organization.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.enable_organization_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#enable_organization_admin_account)
         """
 
     async def enable_security_hub(
-        self, *, Tags: Mapping[str, str] = ..., EnableDefaultStandards: bool = ...
+        self,
+        *,
+        Tags: Mapping[str, str] = ...,
+        EnableDefaultStandards: bool = ...,
+        ControlFindingGenerator: ControlFindingGeneratorType = ...
     ) -> Dict[str, Any]:
         """
         Enables Security Hub for your account in the current Region or the Region you
         specify in the request.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.enable_security_hub)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#enable_security_hub)
@@ -501,14 +615,30 @@
         """
         Returns the current finding aggregation configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_finding_aggregator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_finding_aggregator)
         """
 
+    async def get_finding_history(
+        self,
+        *,
+        FindingIdentifier: AwsSecurityFindingIdentifierTypeDef,
+        StartTime: Union[datetime, str] = ...,
+        EndTime: Union[datetime, str] = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> GetFindingHistoryResponseTypeDef:
+        """
+        Returns history for a Security Hub finding in the last 90 days.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_finding_history)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_finding_history)
+        """
+
     async def get_findings(
         self,
         *,
         Filters: AwsSecurityFindingFiltersTypeDef = ...,
         SortCriteria: Sequence[SortCriterionTypeDef] = ...,
         NextToken: str = ...,
         MaxResults: int = ...
@@ -569,14 +699,24 @@
         Invites other Amazon Web Services accounts to become member accounts for the
         Security Hub administrator account that the invitation is sent from.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.invite_members)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#invite_members)
         """
 
+    async def list_automation_rules(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListAutomationRulesResponseTypeDef:
+        """
+        A list of automation rules and their metadata for the calling account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_automation_rules)
+        """
+
     async def list_enabled_products_for_import(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEnabledProductsForImportResponseTypeDef:
         """
         Lists all findings-generating solutions (products) that you are subscribed to
         receive findings from in Security Hub.
 
@@ -623,14 +763,35 @@
         """
         Lists the Security Hub administrator accounts.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_organization_admin_accounts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_organization_admin_accounts)
         """
 
+    async def list_security_control_definitions(
+        self, *, StandardsArn: str = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListSecurityControlDefinitionsResponseTypeDef:
+        """
+        Lists all of the security controls that apply to a specified standard.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_security_control_definitions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_security_control_definitions)
+        """
+
+    async def list_standards_control_associations(
+        self, *, SecurityControlId: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListStandardsControlAssociationsResponseTypeDef:
+        """
+        Specifies whether a control is currently enabled or disabled in each enabled
+        standard in the calling account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_standards_control_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_standards_control_associations)
+        """
+
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Returns a list of tags associated with a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_tags_for_resource)
@@ -709,15 +870,18 @@
         Used to update the configuration related to Organizations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.update_organization_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#update_organization_configuration)
         """
 
     async def update_security_hub_configuration(
-        self, *, AutoEnableControls: bool = ...
+        self,
+        *,
+        AutoEnableControls: bool = ...,
+        ControlFindingGenerator: ControlFindingGeneratorType = ...
     ) -> Dict[str, Any]:
         """
         Updates configuration options for Security Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.update_security_hub_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#update_security_hub_configuration)
         """
@@ -779,14 +943,23 @@
     ) -> GetEnabledStandardsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
         """
 
     @overload
+    def get_paginator(
+        self, operation_name: Literal["get_finding_history"]
+    ) -> GetFindingHistoryPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
+        """
+
+    @overload
     def get_paginator(self, operation_name: Literal["get_findings"]) -> GetFindingsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
         """
 
     @overload
@@ -835,14 +1008,32 @@
         self, operation_name: Literal["list_organization_admin_accounts"]
     ) -> ListOrganizationAdminAccountsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
         """
 
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_security_control_definitions"]
+    ) -> ListSecurityControlDefinitionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
+        """
+
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_standards_control_associations"]
+    ) -> ListStandardsControlAssociationsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
+        """
+
     async def __aenter__(self) -> "SecurityHubClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/)
         """
 
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/client.pyi` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/client.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -11,49 +11,64 @@
 
     session = get_session()
     async with session.create_client("securityhub") as client:
         client: SecurityHubClient
     ```
 """
 import sys
-from typing import Any, Dict, Mapping, Sequence, Type, overload
+from datetime import datetime
+from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AutoEnableStandardsType,
+    ControlFindingGeneratorType,
     ControlStatusType,
     RecordStateType,
+    RuleStatusType,
     VerificationStateType,
 )
 from .paginator import (
     DescribeActionTargetsPaginator,
     DescribeProductsPaginator,
     DescribeStandardsControlsPaginator,
     DescribeStandardsPaginator,
     GetEnabledStandardsPaginator,
+    GetFindingHistoryPaginator,
     GetFindingsPaginator,
     GetInsightsPaginator,
     ListEnabledProductsForImportPaginator,
     ListFindingAggregatorsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
+    ListSecurityControlDefinitionsPaginator,
+    ListStandardsControlAssociationsPaginator,
 )
 from .type_defs import (
     AccountDetailsTypeDef,
+    AutomationRulesActionTypeDef,
+    AutomationRulesFindingFiltersTypeDef,
     AwsSecurityFindingFiltersTypeDef,
     AwsSecurityFindingIdentifierTypeDef,
     AwsSecurityFindingTypeDef,
+    BatchDeleteAutomationRulesResponseTypeDef,
     BatchDisableStandardsResponseTypeDef,
     BatchEnableStandardsResponseTypeDef,
+    BatchGetAutomationRulesResponseTypeDef,
+    BatchGetSecurityControlsResponseTypeDef,
+    BatchGetStandardsControlAssociationsResponseTypeDef,
     BatchImportFindingsResponseTypeDef,
+    BatchUpdateAutomationRulesResponseTypeDef,
     BatchUpdateFindingsResponseTypeDef,
+    BatchUpdateStandardsControlAssociationsResponseTypeDef,
     CreateActionTargetResponseTypeDef,
+    CreateAutomationRuleResponseTypeDef,
     CreateFindingAggregatorResponseTypeDef,
     CreateInsightResponseTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteActionTargetResponseTypeDef,
     DeleteInsightResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
@@ -64,32 +79,39 @@
     DescribeProductsResponseTypeDef,
     DescribeStandardsControlsResponseTypeDef,
     DescribeStandardsResponseTypeDef,
     EnableImportFindingsForProductResponseTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetEnabledStandardsResponseTypeDef,
     GetFindingAggregatorResponseTypeDef,
+    GetFindingHistoryResponseTypeDef,
     GetFindingsResponseTypeDef,
     GetInsightResultsResponseTypeDef,
     GetInsightsResponseTypeDef,
     GetInvitationsCountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     GetMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
+    ListAutomationRulesResponseTypeDef,
     ListEnabledProductsForImportResponseTypeDef,
     ListFindingAggregatorsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
+    ListSecurityControlDefinitionsResponseTypeDef,
+    ListStandardsControlAssociationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     NoteUpdateTypeDef,
     RelatedFindingTypeDef,
     SeverityUpdateTypeDef,
     SortCriterionTypeDef,
+    StandardsControlAssociationIdTypeDef,
+    StandardsControlAssociationUpdateTypeDef,
     StandardsSubscriptionRequestTypeDef,
+    UpdateAutomationRulesRequestItemTypeDef,
     UpdateFindingAggregatorResponseTypeDef,
     WorkflowUpdateTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -143,41 +165,92 @@
     async def accept_invitation(self, *, MasterId: str, InvitationId: str) -> Dict[str, Any]:
         """
         This method is deprecated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.accept_invitation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#accept_invitation)
         """
+    async def batch_delete_automation_rules(
+        self, *, AutomationRulesArns: Sequence[str]
+    ) -> BatchDeleteAutomationRulesResponseTypeDef:
+        """
+        Deletes one or more automation rules.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_delete_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_delete_automation_rules)
+        """
     async def batch_disable_standards(
         self, *, StandardsSubscriptionArns: Sequence[str]
     ) -> BatchDisableStandardsResponseTypeDef:
         """
-        Disables the standards specified by the provided `StandardsSubscriptionArns` .
+        Disables the standards specified by the provided `StandardsSubscriptionArns`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_disable_standards)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_disable_standards)
         """
     async def batch_enable_standards(
         self, *, StandardsSubscriptionRequests: Sequence[StandardsSubscriptionRequestTypeDef]
     ) -> BatchEnableStandardsResponseTypeDef:
         """
         Enables the standards specified by the provided `StandardsArn`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_enable_standards)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_enable_standards)
         """
+    async def batch_get_automation_rules(
+        self, *, AutomationRulesArns: Sequence[str]
+    ) -> BatchGetAutomationRulesResponseTypeDef:
+        """
+        Retrieves a list of details for automation rules based on rule Amazon Resource
+        Names (ARNs).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_get_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_get_automation_rules)
+        """
+    async def batch_get_security_controls(
+        self, *, SecurityControlIds: Sequence[str]
+    ) -> BatchGetSecurityControlsResponseTypeDef:
+        """
+        Provides details about a batch of security controls for the current Amazon Web
+        Services account and Amazon Web Services Region.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_get_security_controls)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_get_security_controls)
+        """
+    async def batch_get_standards_control_associations(
+        self, *, StandardsControlAssociationIds: Sequence[StandardsControlAssociationIdTypeDef]
+    ) -> BatchGetStandardsControlAssociationsResponseTypeDef:
+        """
+        For a batch of security controls and standards, identifies whether each control
+        is currently enabled or disabled in a standard.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_get_standards_control_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_get_standards_control_associations)
+        """
     async def batch_import_findings(
         self, *, Findings: Sequence[AwsSecurityFindingTypeDef]
     ) -> BatchImportFindingsResponseTypeDef:
         """
         Imports security findings generated by a finding provider into Security Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_import_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_import_findings)
         """
+    async def batch_update_automation_rules(
+        self,
+        *,
+        UpdateAutomationRulesRequestItems: Sequence[UpdateAutomationRulesRequestItemTypeDef]
+    ) -> BatchUpdateAutomationRulesResponseTypeDef:
+        """
+        Updates one or more automation rules based on rule Amazon Resource Names (ARNs)
+        and input parameters.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_update_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_update_automation_rules)
+        """
     async def batch_update_findings(
         self,
         *,
         FindingIdentifiers: Sequence[AwsSecurityFindingIdentifierTypeDef],
         Note: NoteUpdateTypeDef = ...,
         Severity: SeverityUpdateTypeDef = ...,
         VerificationState: VerificationStateType = ...,
@@ -191,14 +264,26 @@
         """
         Used by Security Hub customers to update information about their investigation
         into a finding.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_update_findings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_update_findings)
         """
+    async def batch_update_standards_control_associations(
+        self,
+        *,
+        StandardsControlAssociationUpdates: Sequence[StandardsControlAssociationUpdateTypeDef]
+    ) -> BatchUpdateStandardsControlAssociationsResponseTypeDef:
+        """
+        For a batch of security controls and standards, this operation updates the
+        enablement status of a control in a standard.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.batch_update_standards_control_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#batch_update_standards_control_associations)
+        """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#can_paginate)
         """
@@ -214,14 +299,32 @@
     ) -> CreateActionTargetResponseTypeDef:
         """
         Creates a custom action target in Security Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.create_action_target)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#create_action_target)
         """
+    async def create_automation_rule(
+        self,
+        *,
+        RuleOrder: int,
+        RuleName: str,
+        Description: str,
+        Criteria: AutomationRulesFindingFiltersTypeDef,
+        Actions: Sequence[AutomationRulesActionTypeDef],
+        Tags: Mapping[str, str] = ...,
+        RuleStatus: RuleStatusType = ...,
+        IsTerminal: bool = ...
+    ) -> CreateAutomationRuleResponseTypeDef:
+        """
+        Creates an automation rule based on input parameters.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.create_automation_rule)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#create_automation_rule)
+        """
     async def create_finding_aggregator(
         self, *, RegionLinkingMode: str, Regions: Sequence[str] = ...
     ) -> CreateFindingAggregatorResponseTypeDef:
         """
         Used to enable finding aggregation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.create_finding_aggregator)
@@ -269,15 +372,15 @@
         Deletes a finding aggregator.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.delete_finding_aggregator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#delete_finding_aggregator)
         """
     async def delete_insight(self, *, InsightArn: str) -> DeleteInsightResponseTypeDef:
         """
-        Deletes the insight specified by the `InsightArn` .
+        Deletes the insight specified by the `InsightArn`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.delete_insight)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#delete_insight)
         """
     async def delete_invitations(
         self, *, AccountIds: Sequence[str]
     ) -> DeleteInvitationsResponseTypeDef:
@@ -407,15 +510,19 @@
         """
         Designates the Security Hub administrator account for an organization.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.enable_organization_admin_account)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#enable_organization_admin_account)
         """
     async def enable_security_hub(
-        self, *, Tags: Mapping[str, str] = ..., EnableDefaultStandards: bool = ...
+        self,
+        *,
+        Tags: Mapping[str, str] = ...,
+        EnableDefaultStandards: bool = ...,
+        ControlFindingGenerator: ControlFindingGeneratorType = ...
     ) -> Dict[str, Any]:
         """
         Enables Security Hub for your account in the current Region or the Region you
         specify in the request.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.enable_security_hub)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#enable_security_hub)
@@ -459,14 +566,29 @@
     ) -> GetFindingAggregatorResponseTypeDef:
         """
         Returns the current finding aggregation configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_finding_aggregator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_finding_aggregator)
         """
+    async def get_finding_history(
+        self,
+        *,
+        FindingIdentifier: AwsSecurityFindingIdentifierTypeDef,
+        StartTime: Union[datetime, str] = ...,
+        EndTime: Union[datetime, str] = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> GetFindingHistoryResponseTypeDef:
+        """
+        Returns history for a Security Hub finding in the last 90 days.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_finding_history)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_finding_history)
+        """
     async def get_findings(
         self,
         *,
         Filters: AwsSecurityFindingFiltersTypeDef = ...,
         SortCriteria: Sequence[SortCriterionTypeDef] = ...,
         NextToken: str = ...,
         MaxResults: int = ...
@@ -520,14 +642,23 @@
         """
         Invites other Amazon Web Services accounts to become member accounts for the
         Security Hub administrator account that the invitation is sent from.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.invite_members)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#invite_members)
         """
+    async def list_automation_rules(
+        self, *, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListAutomationRulesResponseTypeDef:
+        """
+        A list of automation rules and their metadata for the calling account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_automation_rules)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_automation_rules)
+        """
     async def list_enabled_products_for_import(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEnabledProductsForImportResponseTypeDef:
         """
         Lists all findings-generating solutions (products) that you are subscribed to
         receive findings from in Security Hub.
 
@@ -569,14 +700,33 @@
     ) -> ListOrganizationAdminAccountsResponseTypeDef:
         """
         Lists the Security Hub administrator accounts.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_organization_admin_accounts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_organization_admin_accounts)
         """
+    async def list_security_control_definitions(
+        self, *, StandardsArn: str = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListSecurityControlDefinitionsResponseTypeDef:
+        """
+        Lists all of the security controls that apply to a specified standard.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_security_control_definitions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_security_control_definitions)
+        """
+    async def list_standards_control_associations(
+        self, *, SecurityControlId: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListStandardsControlAssociationsResponseTypeDef:
+        """
+        Specifies whether a control is currently enabled or disabled in each enabled
+        standard in the calling account.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_standards_control_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#list_standards_control_associations)
+        """
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Returns a list of tags associated with a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.list_tags_for_resource)
@@ -647,15 +797,18 @@
         """
         Used to update the configuration related to Organizations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.update_organization_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#update_organization_configuration)
         """
     async def update_security_hub_configuration(
-        self, *, AutoEnableControls: bool = ...
+        self,
+        *,
+        AutoEnableControls: bool = ...,
+        ControlFindingGenerator: ControlFindingGeneratorType = ...
     ) -> Dict[str, Any]:
         """
         Updates configuration options for Security Hub.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.update_security_hub_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#update_security_hub_configuration)
         """
@@ -710,14 +863,22 @@
         self, operation_name: Literal["get_enabled_standards"]
     ) -> GetEnabledStandardsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
         """
     @overload
+    def get_paginator(
+        self, operation_name: Literal["get_finding_history"]
+    ) -> GetFindingHistoryPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
+        """
+    @overload
     def get_paginator(self, operation_name: Literal["get_findings"]) -> GetFindingsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
         """
     @overload
     def get_paginator(self, operation_name: Literal["get_insights"]) -> GetInsightsPaginator:
@@ -759,14 +920,30 @@
     def get_paginator(
         self, operation_name: Literal["list_organization_admin_accounts"]
     ) -> ListOrganizationAdminAccountsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
         """
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_security_control_definitions"]
+    ) -> ListSecurityControlDefinitionsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
+        """
+    @overload
+    def get_paginator(
+        self, operation_name: Literal["list_standards_control_associations"]
+    ) -> ListStandardsControlAssociationsPaginator:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client.get_paginator)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/#get_paginator)
+        """
     async def __aenter__(self) -> "SecurityHubClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/client/)
         """
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/literals.py` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -17,83 +17,100 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AdminStatusType",
+    "AssociationStatusType",
     "AutoEnableStandardsType",
+    "AutomationRulesActionTypeType",
     "AwsIamAccessKeyStatusType",
     "AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType",
     "ComplianceStatusType",
+    "ControlFindingGeneratorType",
     "ControlStatusType",
     "DateRangeUnitType",
     "DescribeActionTargetsPaginatorName",
     "DescribeProductsPaginatorName",
     "DescribeStandardsControlsPaginatorName",
     "DescribeStandardsPaginatorName",
+    "FindingHistoryUpdateSourceTypeType",
     "GetEnabledStandardsPaginatorName",
+    "GetFindingHistoryPaginatorName",
     "GetFindingsPaginatorName",
     "GetInsightsPaginatorName",
     "IntegrationTypeType",
     "ListEnabledProductsForImportPaginatorName",
     "ListFindingAggregatorsPaginatorName",
     "ListInvitationsPaginatorName",
     "ListMembersPaginatorName",
     "ListOrganizationAdminAccountsPaginatorName",
+    "ListSecurityControlDefinitionsPaginatorName",
+    "ListStandardsControlAssociationsPaginatorName",
     "MalwareStateType",
     "MalwareTypeType",
     "MapFilterComparisonType",
     "NetworkDirectionType",
     "PartitionType",
     "RecordStateType",
+    "RegionAvailabilityStatusType",
+    "RuleStatusType",
     "SeverityLabelType",
     "SeverityRatingType",
     "SortOrderType",
     "StandardsStatusType",
     "StatusReasonCodeType",
     "StringFilterComparisonType",
     "ThreatIntelIndicatorCategoryType",
     "ThreatIntelIndicatorTypeType",
+    "UnprocessedErrorCodeType",
     "VerificationStateType",
     "VulnerabilityFixAvailableType",
     "WorkflowStateType",
     "WorkflowStatusType",
     "SecurityHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 AdminStatusType = Literal["DISABLE_IN_PROGRESS", "ENABLED"]
+AssociationStatusType = Literal["DISABLED", "ENABLED"]
 AutoEnableStandardsType = Literal["DEFAULT", "NONE"]
+AutomationRulesActionTypeType = Literal["FINDING_FIELDS_UPDATE"]
 AwsIamAccessKeyStatusType = Literal["Active", "Inactive"]
 AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType = Literal["Prefix", "Suffix"]
 ComplianceStatusType = Literal["FAILED", "NOT_AVAILABLE", "PASSED", "WARNING"]
+ControlFindingGeneratorType = Literal["SECURITY_CONTROL", "STANDARD_CONTROL"]
 ControlStatusType = Literal["DISABLED", "ENABLED"]
 DateRangeUnitType = Literal["DAYS"]
 DescribeActionTargetsPaginatorName = Literal["describe_action_targets"]
 DescribeProductsPaginatorName = Literal["describe_products"]
 DescribeStandardsControlsPaginatorName = Literal["describe_standards_controls"]
 DescribeStandardsPaginatorName = Literal["describe_standards"]
+FindingHistoryUpdateSourceTypeType = Literal["BATCH_IMPORT_FINDINGS", "BATCH_UPDATE_FINDINGS"]
 GetEnabledStandardsPaginatorName = Literal["get_enabled_standards"]
+GetFindingHistoryPaginatorName = Literal["get_finding_history"]
 GetFindingsPaginatorName = Literal["get_findings"]
 GetInsightsPaginatorName = Literal["get_insights"]
 IntegrationTypeType = Literal[
     "RECEIVE_FINDINGS_FROM_SECURITY_HUB",
     "SEND_FINDINGS_TO_SECURITY_HUB",
     "UPDATE_FINDINGS_IN_SECURITY_HUB",
 ]
 ListEnabledProductsForImportPaginatorName = Literal["list_enabled_products_for_import"]
 ListFindingAggregatorsPaginatorName = Literal["list_finding_aggregators"]
 ListInvitationsPaginatorName = Literal["list_invitations"]
 ListMembersPaginatorName = Literal["list_members"]
 ListOrganizationAdminAccountsPaginatorName = Literal["list_organization_admin_accounts"]
+ListSecurityControlDefinitionsPaginatorName = Literal["list_security_control_definitions"]
+ListStandardsControlAssociationsPaginatorName = Literal["list_standards_control_associations"]
 MalwareStateType = Literal["OBSERVED", "REMOVAL_FAILED", "REMOVED"]
 MalwareTypeType = Literal[
     "ADWARE",
     "BLENDED_THREAT",
     "BOTNET_AGENT",
     "COIN_MINER",
     "EXPLOIT_KIT",
@@ -108,14 +125,16 @@
     "VIRUS",
     "WORM",
 ]
 MapFilterComparisonType = Literal["EQUALS", "NOT_EQUALS"]
 NetworkDirectionType = Literal["IN", "OUT"]
 PartitionType = Literal["aws", "aws-cn", "aws-us-gov"]
 RecordStateType = Literal["ACTIVE", "ARCHIVED"]
+RegionAvailabilityStatusType = Literal["AVAILABLE", "UNAVAILABLE"]
+RuleStatusType = Literal["DISABLED", "ENABLED"]
 SeverityLabelType = Literal["CRITICAL", "HIGH", "INFORMATIONAL", "LOW", "MEDIUM"]
 SeverityRatingType = Literal["CRITICAL", "HIGH", "LOW", "MEDIUM"]
 SortOrderType = Literal["asc", "desc"]
 StandardsStatusType = Literal["DELETING", "FAILED", "INCOMPLETE", "PENDING", "READY"]
 StatusReasonCodeType = Literal["INTERNAL_ERROR", "NO_AVAILABLE_CONFIGURATION_RECORDER"]
 StringFilterComparisonType = Literal["EQUALS", "NOT_EQUALS", "PREFIX", "PREFIX_NOT_EQUALS"]
 ThreatIntelIndicatorCategoryType = Literal[
@@ -130,14 +149,15 @@
     "HASH_SHA512",
     "IPV4_ADDRESS",
     "IPV6_ADDRESS",
     "MUTEX",
     "PROCESS",
     "URL",
 ]
+UnprocessedErrorCodeType = Literal["ACCESS_DENIED", "INVALID_INPUT", "LIMIT_EXCEEDED", "NOT_FOUND"]
 VerificationStateType = Literal["BENIGN_POSITIVE", "FALSE_POSITIVE", "TRUE_POSITIVE", "UNKNOWN"]
 VulnerabilityFixAvailableType = Literal["NO", "PARTIAL", "YES"]
 WorkflowStateType = Literal["ASSIGNED", "DEFERRED", "IN_PROGRESS", "NEW", "RESOLVED"]
 WorkflowStatusType = Literal["NEW", "NOTIFIED", "RESOLVED", "SUPPRESSED"]
 SecurityHubServiceName = Literal["securityhub"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -197,14 +217,15 @@
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
@@ -283,14 +304,15 @@
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
@@ -301,14 +323,15 @@
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
@@ -344,14 +367,15 @@
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
@@ -370,16 +394,19 @@
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
@@ -463,15 +490,17 @@
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
@@ -495,36 +524,43 @@
 ]
 PaginatorName = Literal[
     "describe_action_targets",
     "describe_products",
     "describe_standards",
     "describe_standards_controls",
     "get_enabled_standards",
+    "get_finding_history",
     "get_findings",
     "get_insights",
     "list_enabled_products_for_import",
     "list_finding_aggregators",
     "list_invitations",
     "list_members",
     "list_organization_admin_accounts",
+    "list_security_control_definitions",
+    "list_standards_control_associations",
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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/literals.pyi` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -16,82 +16,99 @@
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AdminStatusType",
+    "AssociationStatusType",
     "AutoEnableStandardsType",
+    "AutomationRulesActionTypeType",
     "AwsIamAccessKeyStatusType",
     "AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType",
     "ComplianceStatusType",
+    "ControlFindingGeneratorType",
     "ControlStatusType",
     "DateRangeUnitType",
     "DescribeActionTargetsPaginatorName",
     "DescribeProductsPaginatorName",
     "DescribeStandardsControlsPaginatorName",
     "DescribeStandardsPaginatorName",
+    "FindingHistoryUpdateSourceTypeType",
     "GetEnabledStandardsPaginatorName",
+    "GetFindingHistoryPaginatorName",
     "GetFindingsPaginatorName",
     "GetInsightsPaginatorName",
     "IntegrationTypeType",
     "ListEnabledProductsForImportPaginatorName",
     "ListFindingAggregatorsPaginatorName",
     "ListInvitationsPaginatorName",
     "ListMembersPaginatorName",
     "ListOrganizationAdminAccountsPaginatorName",
+    "ListSecurityControlDefinitionsPaginatorName",
+    "ListStandardsControlAssociationsPaginatorName",
     "MalwareStateType",
     "MalwareTypeType",
     "MapFilterComparisonType",
     "NetworkDirectionType",
     "PartitionType",
     "RecordStateType",
+    "RegionAvailabilityStatusType",
+    "RuleStatusType",
     "SeverityLabelType",
     "SeverityRatingType",
     "SortOrderType",
     "StandardsStatusType",
     "StatusReasonCodeType",
     "StringFilterComparisonType",
     "ThreatIntelIndicatorCategoryType",
     "ThreatIntelIndicatorTypeType",
+    "UnprocessedErrorCodeType",
     "VerificationStateType",
     "VulnerabilityFixAvailableType",
     "WorkflowStateType",
     "WorkflowStatusType",
     "SecurityHubServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 AdminStatusType = Literal["DISABLE_IN_PROGRESS", "ENABLED"]
+AssociationStatusType = Literal["DISABLED", "ENABLED"]
 AutoEnableStandardsType = Literal["DEFAULT", "NONE"]
+AutomationRulesActionTypeType = Literal["FINDING_FIELDS_UPDATE"]
 AwsIamAccessKeyStatusType = Literal["Active", "Inactive"]
 AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType = Literal["Prefix", "Suffix"]
 ComplianceStatusType = Literal["FAILED", "NOT_AVAILABLE", "PASSED", "WARNING"]
+ControlFindingGeneratorType = Literal["SECURITY_CONTROL", "STANDARD_CONTROL"]
 ControlStatusType = Literal["DISABLED", "ENABLED"]
 DateRangeUnitType = Literal["DAYS"]
 DescribeActionTargetsPaginatorName = Literal["describe_action_targets"]
 DescribeProductsPaginatorName = Literal["describe_products"]
 DescribeStandardsControlsPaginatorName = Literal["describe_standards_controls"]
 DescribeStandardsPaginatorName = Literal["describe_standards"]
+FindingHistoryUpdateSourceTypeType = Literal["BATCH_IMPORT_FINDINGS", "BATCH_UPDATE_FINDINGS"]
 GetEnabledStandardsPaginatorName = Literal["get_enabled_standards"]
+GetFindingHistoryPaginatorName = Literal["get_finding_history"]
 GetFindingsPaginatorName = Literal["get_findings"]
 GetInsightsPaginatorName = Literal["get_insights"]
 IntegrationTypeType = Literal[
     "RECEIVE_FINDINGS_FROM_SECURITY_HUB",
     "SEND_FINDINGS_TO_SECURITY_HUB",
     "UPDATE_FINDINGS_IN_SECURITY_HUB",
 ]
 ListEnabledProductsForImportPaginatorName = Literal["list_enabled_products_for_import"]
 ListFindingAggregatorsPaginatorName = Literal["list_finding_aggregators"]
 ListInvitationsPaginatorName = Literal["list_invitations"]
 ListMembersPaginatorName = Literal["list_members"]
 ListOrganizationAdminAccountsPaginatorName = Literal["list_organization_admin_accounts"]
+ListSecurityControlDefinitionsPaginatorName = Literal["list_security_control_definitions"]
+ListStandardsControlAssociationsPaginatorName = Literal["list_standards_control_associations"]
 MalwareStateType = Literal["OBSERVED", "REMOVAL_FAILED", "REMOVED"]
 MalwareTypeType = Literal[
     "ADWARE",
     "BLENDED_THREAT",
     "BOTNET_AGENT",
     "COIN_MINER",
     "EXPLOIT_KIT",
@@ -106,14 +123,16 @@
     "VIRUS",
     "WORM",
 ]
 MapFilterComparisonType = Literal["EQUALS", "NOT_EQUALS"]
 NetworkDirectionType = Literal["IN", "OUT"]
 PartitionType = Literal["aws", "aws-cn", "aws-us-gov"]
 RecordStateType = Literal["ACTIVE", "ARCHIVED"]
+RegionAvailabilityStatusType = Literal["AVAILABLE", "UNAVAILABLE"]
+RuleStatusType = Literal["DISABLED", "ENABLED"]
 SeverityLabelType = Literal["CRITICAL", "HIGH", "INFORMATIONAL", "LOW", "MEDIUM"]
 SeverityRatingType = Literal["CRITICAL", "HIGH", "LOW", "MEDIUM"]
 SortOrderType = Literal["asc", "desc"]
 StandardsStatusType = Literal["DELETING", "FAILED", "INCOMPLETE", "PENDING", "READY"]
 StatusReasonCodeType = Literal["INTERNAL_ERROR", "NO_AVAILABLE_CONFIGURATION_RECORDER"]
 StringFilterComparisonType = Literal["EQUALS", "NOT_EQUALS", "PREFIX", "PREFIX_NOT_EQUALS"]
 ThreatIntelIndicatorCategoryType = Literal[
@@ -128,14 +147,15 @@
     "HASH_SHA512",
     "IPV4_ADDRESS",
     "IPV6_ADDRESS",
     "MUTEX",
     "PROCESS",
     "URL",
 ]
+UnprocessedErrorCodeType = Literal["ACCESS_DENIED", "INVALID_INPUT", "LIMIT_EXCEEDED", "NOT_FOUND"]
 VerificationStateType = Literal["BENIGN_POSITIVE", "FALSE_POSITIVE", "TRUE_POSITIVE", "UNKNOWN"]
 VulnerabilityFixAvailableType = Literal["NO", "PARTIAL", "YES"]
 WorkflowStateType = Literal["ASSIGNED", "DEFERRED", "IN_PROGRESS", "NEW", "RESOLVED"]
 WorkflowStatusType = Literal["NEW", "NOTIFIED", "RESOLVED", "SUPPRESSED"]
 SecurityHubServiceName = Literal["securityhub"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -195,14 +215,15 @@
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
@@ -281,14 +302,15 @@
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
@@ -299,14 +321,15 @@
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
@@ -342,14 +365,15 @@
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
@@ -368,16 +392,19 @@
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
@@ -461,15 +488,17 @@
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
@@ -493,36 +522,43 @@
 ]
 PaginatorName = Literal[
     "describe_action_targets",
     "describe_products",
     "describe_standards",
     "describe_standards_controls",
     "get_enabled_standards",
+    "get_finding_history",
     "get_findings",
     "get_insights",
     "list_enabled_products_for_import",
     "list_finding_aggregators",
     "list_invitations",
     "list_members",
     "list_organization_admin_accounts",
+    "list_security_control_definitions",
+    "list_standards_control_associations",
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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/paginator.py` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/paginator.py`

 * *Files 11% similar despite different names*

```diff
@@ -11,84 +11,91 @@
     from types_aiobotocore_securityhub.client import SecurityHubClient
     from types_aiobotocore_securityhub.paginator import (
         DescribeActionTargetsPaginator,
         DescribeProductsPaginator,
         DescribeStandardsPaginator,
         DescribeStandardsControlsPaginator,
         GetEnabledStandardsPaginator,
+        GetFindingHistoryPaginator,
         GetFindingsPaginator,
         GetInsightsPaginator,
         ListEnabledProductsForImportPaginator,
         ListFindingAggregatorsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
+        ListSecurityControlDefinitionsPaginator,
+        ListStandardsControlAssociationsPaginator,
     )
 
     session = get_session()
     with session.create_client("securityhub") as client:
         client: SecurityHubClient
 
         describe_action_targets_paginator: DescribeActionTargetsPaginator = client.get_paginator("describe_action_targets")
         describe_products_paginator: DescribeProductsPaginator = client.get_paginator("describe_products")
         describe_standards_paginator: DescribeStandardsPaginator = client.get_paginator("describe_standards")
         describe_standards_controls_paginator: DescribeStandardsControlsPaginator = client.get_paginator("describe_standards_controls")
         get_enabled_standards_paginator: GetEnabledStandardsPaginator = client.get_paginator("get_enabled_standards")
+        get_finding_history_paginator: GetFindingHistoryPaginator = client.get_paginator("get_finding_history")
         get_findings_paginator: GetFindingsPaginator = client.get_paginator("get_findings")
         get_insights_paginator: GetInsightsPaginator = client.get_paginator("get_insights")
         list_enabled_products_for_import_paginator: ListEnabledProductsForImportPaginator = client.get_paginator("list_enabled_products_for_import")
         list_finding_aggregators_paginator: ListFindingAggregatorsPaginator = client.get_paginator("list_finding_aggregators")
         list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
         list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
         list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
+        list_security_control_definitions_paginator: ListSecurityControlDefinitionsPaginator = client.get_paginator("list_security_control_definitions")
+        list_standards_control_associations_paginator: ListStandardsControlAssociationsPaginator = client.get_paginator("list_standards_control_associations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from datetime import datetime
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     AwsSecurityFindingFiltersTypeDef,
+    AwsSecurityFindingIdentifierTypeDef,
     DescribeActionTargetsResponseTypeDef,
     DescribeProductsResponseTypeDef,
     DescribeStandardsControlsResponseTypeDef,
     DescribeStandardsResponseTypeDef,
     GetEnabledStandardsResponseTypeDef,
+    GetFindingHistoryResponseTypeDef,
     GetFindingsResponseTypeDef,
     GetInsightsResponseTypeDef,
     ListEnabledProductsForImportResponseTypeDef,
     ListFindingAggregatorsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
+    ListSecurityControlDefinitionsResponseTypeDef,
+    ListStandardsControlAssociationsResponseTypeDef,
     PaginatorConfigTypeDef,
     SortCriterionTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeActionTargetsPaginator",
     "DescribeProductsPaginator",
     "DescribeStandardsPaginator",
     "DescribeStandardsControlsPaginator",
     "GetEnabledStandardsPaginator",
+    "GetFindingHistoryPaginator",
     "GetFindingsPaginator",
     "GetInsightsPaginator",
     "ListEnabledProductsForImportPaginator",
     "ListFindingAggregatorsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
+    "ListSecurityControlDefinitionsPaginator",
+    "ListStandardsControlAssociationsPaginator",
 )
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -104,60 +111,60 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeactiontargetspaginator)
     """
 
     def paginate(
         self,
         *,
         ActionTargetArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeActionTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeActionTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeactiontargetspaginator)
         """
 
 
 class DescribeProductsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeProducts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeproductspaginator)
     """
 
     def paginate(
-        self, *, ProductArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProductArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeProductsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeProducts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeproductspaginator)
         """
 
 
 class DescribeStandardsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandards)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStandardsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardspaginator)
         """
 
 
 class DescribeStandardsControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandardsControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardscontrolspaginator)
     """
 
     def paginate(
-        self, *, StandardsSubscriptionArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StandardsSubscriptionArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStandardsControlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandardsControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardscontrolspaginator)
         """
 
 
@@ -167,122 +174,172 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getenabledstandardspaginator)
     """
 
     def paginate(
         self,
         *,
         StandardsSubscriptionArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetEnabledStandardsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetEnabledStandards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getenabledstandardspaginator)
         """
 
 
+class GetFindingHistoryPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindingHistory)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindinghistorypaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        FindingIdentifier: AwsSecurityFindingIdentifierTypeDef,
+        StartTime: Union[datetime, str] = ...,
+        EndTime: Union[datetime, str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[GetFindingHistoryResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindingHistory.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindinghistorypaginator)
+        """
+
+
 class GetFindingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindingspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: AwsSecurityFindingFiltersTypeDef = ...,
         SortCriteria: Sequence[SortCriterionTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindingspaginator)
         """
 
 
 class GetInsightsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetInsights)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getinsightspaginator)
     """
 
     def paginate(
-        self, *, InsightArns: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InsightArns: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInsightsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetInsights.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getinsightspaginator)
         """
 
 
 class ListEnabledProductsForImportPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListEnabledProductsForImport)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listenabledproductsforimportpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnabledProductsForImportResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListEnabledProductsForImport.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listenabledproductsforimportpaginator)
         """
 
 
 class ListFindingAggregatorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListFindingAggregators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listfindingaggregatorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingAggregatorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListFindingAggregators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listfindingaggregatorspaginator)
         """
 
 
 class ListInvitationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListInvitations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listinvitationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listinvitationspaginator)
         """
 
 
 class ListMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listmemberspaginator)
     """
 
     def paginate(
-        self, *, OnlyAssociated: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OnlyAssociated: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listmemberspaginator)
         """
 
 
 class ListOrganizationAdminAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListOrganizationAdminAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listorganizationadminaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationAdminAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListOrganizationAdminAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listorganizationadminaccountspaginator)
         """
+
+
+class ListSecurityControlDefinitionsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListSecurityControlDefinitions)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listsecuritycontroldefinitionspaginator)
+    """
+
+    def paginate(
+        self, *, StandardsArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListSecurityControlDefinitionsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListSecurityControlDefinitions.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listsecuritycontroldefinitionspaginator)
+        """
+
+
+class ListStandardsControlAssociationsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListStandardsControlAssociations)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#liststandardscontrolassociationspaginator)
+    """
+
+    def paginate(
+        self, *, SecurityControlId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListStandardsControlAssociationsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListStandardsControlAssociations.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#liststandardscontrolassociationspaginator)
+        """
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/paginator.pyi` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/paginator.pyi`

 * *Files 11% similar despite different names*

```diff
@@ -11,83 +11,91 @@
     from types_aiobotocore_securityhub.client import SecurityHubClient
     from types_aiobotocore_securityhub.paginator import (
         DescribeActionTargetsPaginator,
         DescribeProductsPaginator,
         DescribeStandardsPaginator,
         DescribeStandardsControlsPaginator,
         GetEnabledStandardsPaginator,
+        GetFindingHistoryPaginator,
         GetFindingsPaginator,
         GetInsightsPaginator,
         ListEnabledProductsForImportPaginator,
         ListFindingAggregatorsPaginator,
         ListInvitationsPaginator,
         ListMembersPaginator,
         ListOrganizationAdminAccountsPaginator,
+        ListSecurityControlDefinitionsPaginator,
+        ListStandardsControlAssociationsPaginator,
     )
 
     session = get_session()
     with session.create_client("securityhub") as client:
         client: SecurityHubClient
 
         describe_action_targets_paginator: DescribeActionTargetsPaginator = client.get_paginator("describe_action_targets")
         describe_products_paginator: DescribeProductsPaginator = client.get_paginator("describe_products")
         describe_standards_paginator: DescribeStandardsPaginator = client.get_paginator("describe_standards")
         describe_standards_controls_paginator: DescribeStandardsControlsPaginator = client.get_paginator("describe_standards_controls")
         get_enabled_standards_paginator: GetEnabledStandardsPaginator = client.get_paginator("get_enabled_standards")
+        get_finding_history_paginator: GetFindingHistoryPaginator = client.get_paginator("get_finding_history")
         get_findings_paginator: GetFindingsPaginator = client.get_paginator("get_findings")
         get_insights_paginator: GetInsightsPaginator = client.get_paginator("get_insights")
         list_enabled_products_for_import_paginator: ListEnabledProductsForImportPaginator = client.get_paginator("list_enabled_products_for_import")
         list_finding_aggregators_paginator: ListFindingAggregatorsPaginator = client.get_paginator("list_finding_aggregators")
         list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
         list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
         list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = client.get_paginator("list_organization_admin_accounts")
+        list_security_control_definitions_paginator: ListSecurityControlDefinitionsPaginator = client.get_paginator("list_security_control_definitions")
+        list_standards_control_associations_paginator: ListStandardsControlAssociationsPaginator = client.get_paginator("list_standards_control_associations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from datetime import datetime
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     AwsSecurityFindingFiltersTypeDef,
+    AwsSecurityFindingIdentifierTypeDef,
     DescribeActionTargetsResponseTypeDef,
     DescribeProductsResponseTypeDef,
     DescribeStandardsControlsResponseTypeDef,
     DescribeStandardsResponseTypeDef,
     GetEnabledStandardsResponseTypeDef,
+    GetFindingHistoryResponseTypeDef,
     GetFindingsResponseTypeDef,
     GetInsightsResponseTypeDef,
     ListEnabledProductsForImportResponseTypeDef,
     ListFindingAggregatorsResponseTypeDef,
     ListInvitationsResponseTypeDef,
     ListMembersResponseTypeDef,
     ListOrganizationAdminAccountsResponseTypeDef,
+    ListSecurityControlDefinitionsResponseTypeDef,
+    ListStandardsControlAssociationsResponseTypeDef,
     PaginatorConfigTypeDef,
     SortCriterionTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeActionTargetsPaginator",
     "DescribeProductsPaginator",
     "DescribeStandardsPaginator",
     "DescribeStandardsControlsPaginator",
     "GetEnabledStandardsPaginator",
+    "GetFindingHistoryPaginator",
     "GetFindingsPaginator",
     "GetInsightsPaginator",
     "ListEnabledProductsForImportPaginator",
     "ListFindingAggregatorsPaginator",
     "ListInvitationsPaginator",
     "ListMembersPaginator",
     "ListOrganizationAdminAccountsPaginator",
+    "ListSecurityControlDefinitionsPaginator",
+    "ListStandardsControlAssociationsPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -100,57 +108,57 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeactiontargetspaginator)
     """
 
     def paginate(
         self,
         *,
         ActionTargetArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeActionTargetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeActionTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeactiontargetspaginator)
         """
 
 class DescribeProductsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeProducts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeproductspaginator)
     """
 
     def paginate(
-        self, *, ProductArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ProductArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeProductsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeProducts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describeproductspaginator)
         """
 
 class DescribeStandardsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandards)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStandardsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardspaginator)
         """
 
 class DescribeStandardsControlsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandardsControls)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardscontrolspaginator)
     """
 
     def paginate(
-        self, *, StandardsSubscriptionArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, StandardsSubscriptionArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeStandardsControlsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.DescribeStandardsControls.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#describestandardscontrolspaginator)
         """
 
 class GetEnabledStandardsPaginator(AioPaginator):
@@ -159,115 +167,162 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getenabledstandardspaginator)
     """
 
     def paginate(
         self,
         *,
         StandardsSubscriptionArns: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetEnabledStandardsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetEnabledStandards.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getenabledstandardspaginator)
         """
 
+class GetFindingHistoryPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindingHistory)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindinghistorypaginator)
+    """
+
+    def paginate(
+        self,
+        *,
+        FindingIdentifier: AwsSecurityFindingIdentifierTypeDef,
+        StartTime: Union[datetime, str] = ...,
+        EndTime: Union[datetime, str] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[GetFindingHistoryResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindingHistory.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindinghistorypaginator)
+        """
+
 class GetFindingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindingspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: AwsSecurityFindingFiltersTypeDef = ...,
         SortCriteria: Sequence[SortCriterionTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getfindingspaginator)
         """
 
 class GetInsightsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetInsights)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getinsightspaginator)
     """
 
     def paginate(
-        self, *, InsightArns: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InsightArns: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInsightsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.GetInsights.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#getinsightspaginator)
         """
 
 class ListEnabledProductsForImportPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListEnabledProductsForImport)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listenabledproductsforimportpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEnabledProductsForImportResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListEnabledProductsForImport.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listenabledproductsforimportpaginator)
         """
 
 class ListFindingAggregatorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListFindingAggregators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listfindingaggregatorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFindingAggregatorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListFindingAggregators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listfindingaggregatorspaginator)
         """
 
 class ListInvitationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListInvitations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listinvitationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvitationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListInvitations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listinvitationspaginator)
         """
 
 class ListMembersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListMembers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listmemberspaginator)
     """
 
     def paginate(
-        self, *, OnlyAssociated: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, OnlyAssociated: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMembersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListMembers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listmemberspaginator)
         """
 
 class ListOrganizationAdminAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListOrganizationAdminAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listorganizationadminaccountspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrganizationAdminAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListOrganizationAdminAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listorganizationadminaccountspaginator)
         """
+
+class ListSecurityControlDefinitionsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListSecurityControlDefinitions)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listsecuritycontroldefinitionspaginator)
+    """
+
+    def paginate(
+        self, *, StandardsArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListSecurityControlDefinitionsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListSecurityControlDefinitions.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#listsecuritycontroldefinitionspaginator)
+        """
+
+class ListStandardsControlAssociationsPaginator(AioPaginator):
+    """
+    [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListStandardsControlAssociations)
+    [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#liststandardscontrolassociationspaginator)
+    """
+
+    def paginate(
+        self, *, SecurityControlId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
+    ) -> AsyncIterator[ListStandardsControlAssociationsResponseTypeDef]:
+        """
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub.Paginator.ListStandardsControlAssociations.paginate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/paginators/#liststandardscontrolassociationspaginator)
+        """
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/type_defs.py` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -9,38 +9,44 @@
     from types_aiobotocore_securityhub.type_defs import AcceptAdministratorInvitationRequestRequestTypeDef
 
     data: AcceptAdministratorInvitationRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence
+from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AdminStatusType,
+    AssociationStatusType,
     AutoEnableStandardsType,
     AwsIamAccessKeyStatusType,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType,
     ComplianceStatusType,
+    ControlFindingGeneratorType,
     ControlStatusType,
+    FindingHistoryUpdateSourceTypeType,
     IntegrationTypeType,
     MalwareStateType,
     MalwareTypeType,
     MapFilterComparisonType,
     NetworkDirectionType,
     PartitionType,
     RecordStateType,
+    RegionAvailabilityStatusType,
+    RuleStatusType,
     SeverityLabelType,
     SeverityRatingType,
     SortOrderType,
     StandardsStatusType,
     StatusReasonCodeType,
     StringFilterComparisonType,
     ThreatIntelIndicatorCategoryType,
     ThreatIntelIndicatorTypeType,
+    UnprocessedErrorCodeType,
     VerificationStateType,
     VulnerabilityFixAvailableType,
     WorkflowStateType,
     WorkflowStatusType,
 )
 
 if sys.version_info >= (3, 9):
@@ -48,15 +54,14 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AcceptAdministratorInvitationRequestRequestTypeDef",
     "AcceptInvitationRequestRequestTypeDef",
     "AccountDetailsTypeDef",
     "ActionLocalIpDetailsTypeDef",
     "ActionLocalPortDetailsTypeDef",
     "CityTypeDef",
@@ -65,22 +70,40 @@
     "IpOrganizationDetailsTypeDef",
     "ActionRemotePortDetailsTypeDef",
     "ActionTargetTypeDef",
     "DnsRequestActionTypeDef",
     "AdjustmentTypeDef",
     "AdminAccountTypeDef",
     "AssociatedStandardTypeDef",
+    "AssociationStateDetailsTypeDef",
+    "NoteUpdateTypeDef",
+    "RelatedFindingTypeDef",
+    "SeverityUpdateTypeDef",
+    "WorkflowUpdateTypeDef",
+    "MapFilterTypeDef",
+    "NumberFilterTypeDef",
+    "StringFilterTypeDef",
+    "AutomationRulesMetadataTypeDef",
     "AvailabilityZoneTypeDef",
+    "AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef",
+    "AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef",
+    "AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef",
+    "AwsAmazonMqBrokerUsersDetailsTypeDef",
+    "AwsAmazonMqBrokerLogsPendingDetailsTypeDef",
     "AwsApiCallActionDomainDetailsTypeDef",
     "AwsApiGatewayAccessLogSettingsTypeDef",
     "AwsApiGatewayCanarySettingsTypeDef",
     "AwsApiGatewayEndpointConfigurationTypeDef",
     "AwsApiGatewayMethodSettingsTypeDef",
     "AwsCorsConfigurationTypeDef",
     "AwsApiGatewayV2RouteSettingsTypeDef",
+    "AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef",
+    "AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef",
+    "AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef",
+    "AwsAppSyncGraphQlApiLogConfigDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupLaunchTemplateLaunchTemplateSpecificationTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyInstancesDistributionDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateLaunchTemplateSpecificationTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateOverridesListDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationBlockDeviceMappingsEbsDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationInstanceMonitoringDetailsTypeDef",
@@ -120,14 +143,15 @@
     "AwsDynamoDbTableRestoreSummaryTypeDef",
     "AwsDynamoDbTableSseDescriptionTypeDef",
     "AwsDynamoDbTableStreamSpecificationTypeDef",
     "AwsDynamoDbTableProjectionTypeDef",
     "AwsDynamoDbTableProvisionedThroughputOverrideTypeDef",
     "AwsEc2EipDetailsTypeDef",
     "AwsEc2InstanceMetadataOptionsTypeDef",
+    "AwsEc2InstanceMonitoringDetailsTypeDef",
     "AwsEc2InstanceNetworkInterfacesDetailsTypeDef",
     "AwsEc2LaunchTemplateDataBlockDeviceMappingSetEbsDetailsTypeDef",
     "AwsEc2LaunchTemplateDataCapacityReservationSpecificationCapacityReservationTargetDetailsTypeDef",
     "AwsEc2LaunchTemplateDataCpuOptionsDetailsTypeDef",
     "AwsEc2LaunchTemplateDataCreditSpecificationDetailsTypeDef",
     "AwsEc2LaunchTemplateDataElasticGpuSpecificationSetDetailsTypeDef",
     "AwsEc2LaunchTemplateDataElasticInferenceAcceleratorSetDetailsTypeDef",
@@ -156,14 +180,16 @@
     "AwsEc2NetworkAclAssociationTypeDef",
     "IcmpTypeCodeTypeDef",
     "PortRangeFromToTypeDef",
     "AwsEc2NetworkInterfaceAttachmentTypeDef",
     "AwsEc2NetworkInterfaceIpV6AddressDetailTypeDef",
     "AwsEc2NetworkInterfacePrivateIpAddressDetailTypeDef",
     "AwsEc2NetworkInterfaceSecurityGroupTypeDef",
+    "PropagatingVgwSetDetailsTypeDef",
+    "RouteSetDetailsTypeDef",
     "AwsEc2SecurityGroupIpRangeTypeDef",
     "AwsEc2SecurityGroupIpv6RangeTypeDef",
     "AwsEc2SecurityGroupPrefixListIdTypeDef",
     "AwsEc2SecurityGroupUserIdGroupPairTypeDef",
     "Ipv6CidrBlockAssociationTypeDef",
     "AwsEc2TransitGatewayDetailsTypeDef",
     "AwsEc2VolumeAttachmentTypeDef",
@@ -240,14 +266,22 @@
     "AwsElbLoadBalancerBackendServerDescriptionTypeDef",
     "AwsElbLoadBalancerHealthCheckTypeDef",
     "AwsElbLoadBalancerInstanceTypeDef",
     "AwsElbLoadBalancerSourceSecurityGroupTypeDef",
     "AwsElbLoadBalancerListenerTypeDef",
     "AwsElbv2LoadBalancerAttributeTypeDef",
     "LoadBalancerStateTypeDef",
+    "AwsEventSchemasRegistryDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef",
+    "AwsGuardDutyDetectorFeaturesDetailsTypeDef",
     "AwsIamAccessKeySessionContextAttributesTypeDef",
     "AwsIamAccessKeySessionContextSessionIssuerTypeDef",
     "AwsIamAttachedManagedPolicyTypeDef",
     "AwsIamGroupPolicyTypeDef",
     "AwsIamInstanceProfileRoleTypeDef",
     "AwsIamPermissionsBoundaryTypeDef",
     "AwsIamPolicyVersionTypeDef",
@@ -307,39 +341,38 @@
     "AwsS3BucketBucketLifecycleConfigurationRulesNoncurrentVersionTransitionsDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesTransitionsDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateTagDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsTagDetailsTypeDef",
     "AwsS3BucketBucketVersioningConfigurationTypeDef",
     "AwsS3BucketLoggingConfigurationTypeDef",
     "AwsS3BucketNotificationConfigurationS3KeyFilterRuleTypeDef",
+    "AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef",
     "AwsS3BucketServerSideEncryptionByDefaultTypeDef",
     "AwsS3BucketWebsiteConfigurationRedirectToTypeDef",
     "AwsS3BucketWebsiteConfigurationRoutingRuleConditionTypeDef",
     "AwsS3BucketWebsiteConfigurationRoutingRuleRedirectTypeDef",
     "AwsS3ObjectDetailsTypeDef",
     "AwsSageMakerNotebookInstanceMetadataServiceConfigurationDetailsTypeDef",
     "AwsSecretsManagerSecretRotationRulesTypeDef",
     "BooleanFilterTypeDef",
     "IpFilterTypeDef",
     "KeywordFilterTypeDef",
-    "MapFilterTypeDef",
-    "NumberFilterTypeDef",
-    "StringFilterTypeDef",
     "AwsSecurityFindingIdentifierTypeDef",
     "MalwareTypeDef",
     "NoteTypeDef",
     "PatchSummaryTypeDef",
     "ProcessDetailsTypeDef",
-    "RelatedFindingTypeDef",
     "SeverityTypeDef",
     "ThreatIntelIndicatorTypeDef",
     "WorkflowTypeDef",
     "AwsSnsTopicSubscriptionTypeDef",
     "AwsSqsQueueDetailsTypeDef",
     "AwsSsmComplianceSummaryTypeDef",
+    "AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef",
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef",
     "AwsWafRateBasedRuleMatchPredicateTypeDef",
     "AwsWafRegionalRateBasedRuleMatchPredicateTypeDef",
     "AwsWafRegionalRulePredicateListDetailsTypeDef",
     "AwsWafRegionalRuleGroupRulesActionDetailsTypeDef",
     "AwsWafRegionalWebAclRulesListActionDetailsTypeDef",
     "AwsWafRegionalWebAclRulesListOverrideActionDetailsTypeDef",
     "AwsWafRulePredicateListDetailsTypeDef",
@@ -347,74 +380,113 @@
     "WafActionTypeDef",
     "WafExcludedRuleTypeDef",
     "WafOverrideActionTypeDef",
     "AwsWafv2CustomHttpHeaderTypeDef",
     "AwsWafv2VisibilityConfigDetailsTypeDef",
     "AwsWafv2WebAclCaptchaConfigImmunityTimePropertyDetailsTypeDef",
     "AwsXrayEncryptionConfigDetailsTypeDef",
+    "BatchDeleteAutomationRulesRequestRequestTypeDef",
+    "UnprocessedAutomationRuleTypeDef",
     "BatchDisableStandardsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "StandardsSubscriptionRequestTypeDef",
+    "BatchGetAutomationRulesRequestRequestTypeDef",
+    "BatchGetSecurityControlsRequestRequestTypeDef",
+    "SecurityControlTypeDef",
+    "UnprocessedSecurityControlTypeDef",
+    "StandardsControlAssociationIdTypeDef",
+    "StandardsControlAssociationDetailTypeDef",
     "ImportFindingsErrorTypeDef",
-    "NoteUpdateTypeDef",
-    "SeverityUpdateTypeDef",
-    "WorkflowUpdateTypeDef",
+    "StandardsControlAssociationUpdateTypeDef",
     "CellTypeDef",
     "ClassificationStatusTypeDef",
     "StatusReasonTypeDef",
     "VolumeMountTypeDef",
     "CreateActionTargetRequestRequestTypeDef",
+    "CreateActionTargetResponseTypeDef",
+    "CreateAutomationRuleResponseTypeDef",
     "CreateFindingAggregatorRequestRequestTypeDef",
+    "CreateFindingAggregatorResponseTypeDef",
+    "CreateInsightResponseTypeDef",
     "ResultTypeDef",
     "DateRangeTypeDef",
     "DeclineInvitationsRequestRequestTypeDef",
     "DeleteActionTargetRequestRequestTypeDef",
+    "DeleteActionTargetResponseTypeDef",
     "DeleteFindingAggregatorRequestRequestTypeDef",
     "DeleteInsightRequestRequestTypeDef",
+    "DeleteInsightResponseTypeDef",
     "DeleteInvitationsRequestRequestTypeDef",
     "DeleteMembersRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
     "DescribeActionTargetsRequestRequestTypeDef",
     "DescribeHubRequestRequestTypeDef",
+    "DescribeHubResponseTypeDef",
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
     "DescribeProductsRequestRequestTypeDef",
     "ProductTypeDef",
+    "DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
     "DescribeStandardsControlsRequestRequestTypeDef",
     "StandardsControlTypeDef",
+    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
     "DescribeStandardsRequestRequestTypeDef",
     "DisableImportFindingsForProductRequestRequestTypeDef",
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     "DisassociateMembersRequestRequestTypeDef",
     "EnableImportFindingsForProductRequestRequestTypeDef",
+    "EnableImportFindingsForProductResponseTypeDef",
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     "EnableSecurityHubRequestRequestTypeDef",
     "FilePathsTypeDef",
     "FindingAggregatorTypeDef",
+    "FindingHistoryUpdateSourceTypeDef",
+    "FindingHistoryUpdateTypeDef",
     "FindingProviderSeverityTypeDef",
     "FirewallPolicyStatefulRuleGroupReferencesDetailsTypeDef",
     "FirewallPolicyStatelessRuleGroupReferencesDetailsTypeDef",
     "InvitationTypeDef",
+    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
     "GetEnabledStandardsRequestRequestTypeDef",
     "GetFindingAggregatorRequestRequestTypeDef",
+    "GetFindingAggregatorResponseTypeDef",
     "SortCriterionTypeDef",
     "GetInsightResultsRequestRequestTypeDef",
+    "GetInsightsRequestGetInsightsPaginateTypeDef",
     "GetInsightsRequestRequestTypeDef",
+    "GetInvitationsCountResponseTypeDef",
     "GetMembersRequestRequestTypeDef",
     "MemberTypeDef",
     "InsightResultValueTypeDef",
     "InviteMembersRequestRequestTypeDef",
+    "ListAutomationRulesRequestRequestTypeDef",
+    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
     "ListEnabledProductsForImportRequestRequestTypeDef",
+    "ListEnabledProductsForImportResponseTypeDef",
+    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
     "ListFindingAggregatorsRequestRequestTypeDef",
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
     "ListInvitationsRequestRequestTypeDef",
+    "ListMembersRequestListMembersPaginateTypeDef",
     "ListMembersRequestRequestTypeDef",
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
+    "ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef",
+    "ListSecurityControlDefinitionsRequestRequestTypeDef",
+    "SecurityControlDefinitionTypeDef",
+    "ListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef",
+    "ListStandardsControlAssociationsRequestRequestTypeDef",
+    "StandardsControlAssociationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "PortRangeTypeDef",
     "RangeTypeDef",
     "RecordTypeDef",
+    "PaginatorConfigTypeDef",
     "RecommendationTypeDef",
+    "ResponseMetadataTypeDef",
     "RuleGroupSourceListDetailsTypeDef",
     "RuleGroupSourceStatefulRulesHeaderDetailsTypeDef",
     "RuleGroupSourceStatefulRulesOptionsDetailsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesDestinationPortsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesDestinationsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesSourcePortsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesSourcesTypeDef",
@@ -425,25 +497,33 @@
     "StandardsManagedByTypeDef",
     "StandardsStatusReasonTypeDef",
     "StatelessCustomPublishMetricActionDimensionTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateActionTargetRequestRequestTypeDef",
     "UpdateFindingAggregatorRequestRequestTypeDef",
+    "UpdateFindingAggregatorResponseTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
     "UpdateSecurityHubConfigurationRequestRequestTypeDef",
     "UpdateStandardsControlRequestRequestTypeDef",
     "VulnerabilityVendorTypeDef",
     "CreateMembersRequestRequestTypeDef",
     "ActionRemoteIpDetailsTypeDef",
+    "DescribeActionTargetsResponseTypeDef",
     "CvssTypeDef",
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    "AssociationSetDetailsTypeDef",
+    "AutomationRulesFindingFieldsUpdateTypeDef",
+    "ListAutomationRulesResponseTypeDef",
+    "AwsAmazonMqBrokerLogsDetailsTypeDef",
     "AwsApiGatewayRestApiDetailsTypeDef",
     "AwsApiGatewayStageDetailsTypeDef",
     "AwsApiGatewayV2ApiDetailsTypeDef",
     "AwsApiGatewayV2StageDetailsTypeDef",
+    "AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationBlockDeviceMappingsDetailsTypeDef",
     "AwsBackupBackupPlanRuleCopyActionsDetailsTypeDef",
     "AwsBackupBackupVaultDetailsTypeDef",
     "AwsBackupRecoveryPointDetailsTypeDef",
     "AwsCertificateManagerCertificateDomainValidationOptionTypeDef",
     "AwsCloudFormationStackDetailsTypeDef",
@@ -486,14 +566,16 @@
     "AwsElasticBeanstalkEnvironmentDetailsTypeDef",
     "AwsElasticsearchDomainElasticsearchClusterConfigDetailsTypeDef",
     "AwsElasticsearchDomainLogPublishingOptionsTypeDef",
     "AwsElbLoadBalancerPoliciesTypeDef",
     "AwsElbLoadBalancerAttributesTypeDef",
     "AwsElbLoadBalancerListenerDescriptionTypeDef",
     "AwsElbv2LoadBalancerDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef",
     "AwsIamAccessKeySessionContextTypeDef",
     "AwsIamGroupDetailsTypeDef",
     "AwsIamInstanceProfileTypeDef",
     "AwsIamPolicyDetailsTypeDef",
     "AwsIamUserDetailsTypeDef",
     "AwsKinesisStreamDetailsTypeDef",
     "AwsLambdaFunctionEnvironmentTypeDef",
@@ -505,94 +587,86 @@
     "AwsRdsDbSnapshotDetailsTypeDef",
     "AwsRdsDbPendingModifiedValuesTypeDef",
     "AwsRdsDbSecurityGroupDetailsTypeDef",
     "AwsRdsDbSubnetGroupSubnetTypeDef",
     "AwsRedshiftClusterClusterParameterGroupTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef",
+    "AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef",
     "AwsS3BucketServerSideEncryptionRuleTypeDef",
     "AwsS3BucketWebsiteConfigurationRoutingRuleTypeDef",
     "AwsSageMakerNotebookInstanceDetailsTypeDef",
     "AwsSecretsManagerSecretDetailsTypeDef",
+    "BatchUpdateFindingsRequestRequestTypeDef",
     "BatchUpdateFindingsUnprocessedFindingTypeDef",
+    "GetFindingHistoryRequestGetFindingHistoryPaginateTypeDef",
+    "GetFindingHistoryRequestRequestTypeDef",
     "AwsSnsTopicDetailsTypeDef",
     "AwsSsmPatchTypeDef",
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef",
     "AwsWafRateBasedRuleDetailsTypeDef",
     "AwsWafRegionalRateBasedRuleDetailsTypeDef",
     "AwsWafRegionalRuleDetailsTypeDef",
     "AwsWafRegionalRuleGroupRulesDetailsTypeDef",
     "AwsWafRegionalWebAclRulesListDetailsTypeDef",
     "AwsWafRuleDetailsTypeDef",
     "AwsWafRuleGroupRulesDetailsTypeDef",
     "AwsWafWebAclRuleTypeDef",
     "AwsWafv2CustomRequestHandlingDetailsTypeDef",
     "AwsWafv2CustomResponseDetailsTypeDef",
     "AwsWafv2WebAclCaptchaConfigDetailsTypeDef",
-    "CreateActionTargetResponseTypeDef",
-    "CreateFindingAggregatorResponseTypeDef",
-    "CreateInsightResponseTypeDef",
-    "DeleteActionTargetResponseTypeDef",
-    "DeleteInsightResponseTypeDef",
-    "DescribeActionTargetsResponseTypeDef",
-    "DescribeHubResponseTypeDef",
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    "EnableImportFindingsForProductResponseTypeDef",
-    "GetFindingAggregatorResponseTypeDef",
-    "GetInvitationsCountResponseTypeDef",
-    "ListEnabledProductsForImportResponseTypeDef",
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateFindingAggregatorResponseTypeDef",
+    "BatchDeleteAutomationRulesResponseTypeDef",
+    "BatchUpdateAutomationRulesResponseTypeDef",
     "BatchEnableStandardsRequestRequestTypeDef",
+    "BatchGetSecurityControlsResponseTypeDef",
+    "BatchGetStandardsControlAssociationsRequestRequestTypeDef",
+    "UnprocessedStandardsControlAssociationTypeDef",
     "BatchImportFindingsResponseTypeDef",
-    "BatchUpdateFindingsRequestRequestTypeDef",
+    "BatchUpdateStandardsControlAssociationsRequestRequestTypeDef",
+    "UnprocessedStandardsControlAssociationUpdateTypeDef",
     "ComplianceTypeDef",
     "ContainerDetailsTypeDef",
     "CreateMembersResponseTypeDef",
     "DeclineInvitationsResponseTypeDef",
     "DeleteInvitationsResponseTypeDef",
     "DeleteMembersResponseTypeDef",
     "InviteMembersResponseTypeDef",
     "DateFilterTypeDef",
-    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
-    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
-    "DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
-    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
-    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
-    "GetInsightsRequestGetInsightsPaginateTypeDef",
-    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
-    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    "ListMembersRequestListMembersPaginateTypeDef",
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "DescribeProductsResponseTypeDef",
     "DescribeStandardsControlsResponseTypeDef",
     "ThreatTypeDef",
     "ListFindingAggregatorsResponseTypeDef",
+    "FindingHistoryRecordTypeDef",
     "FindingProviderFieldsTypeDef",
     "GetAdministratorAccountResponseTypeDef",
     "GetMasterAccountResponseTypeDef",
     "ListInvitationsResponseTypeDef",
     "GetMembersResponseTypeDef",
     "ListMembersResponseTypeDef",
     "InsightResultsTypeDef",
+    "ListSecurityControlDefinitionsResponseTypeDef",
+    "ListStandardsControlAssociationsResponseTypeDef",
     "NetworkPathComponentDetailsTypeDef",
     "NetworkTypeDef",
     "PageTypeDef",
     "RemediationTypeDef",
     "RuleGroupSourceStatefulRulesDetailsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesTypeDef",
     "RuleGroupVariablesTypeDef",
     "StandardTypeDef",
     "StandardsSubscriptionTypeDef",
     "StatelessCustomPublishMetricActionTypeDef",
     "AwsApiCallActionTypeDef",
     "NetworkConnectionActionTypeDef",
     "PortProbeDetailTypeDef",
     "VulnerabilityTypeDef",
+    "AwsEc2RouteTableDetailsTypeDef",
+    "AutomationRulesActionTypeDef",
+    "AwsAmazonMqBrokerDetailsTypeDef",
+    "AwsAppSyncGraphQlApiDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationDetailsTypeDef",
     "AwsBackupBackupPlanRuleDetailsTypeDef",
     "AwsCertificateManagerCertificateRenewalSummaryTypeDef",
     "AwsCloudFrontDistributionOriginItemTypeDef",
     "AwsCloudFrontDistributionOriginGroupTypeDef",
     "AwsCodeBuildProjectDetailsTypeDef",
@@ -607,35 +681,42 @@
     "AwsEcsTaskDefinitionContainerDefinitionsDetailsTypeDef",
     "AwsEcsTaskDefinitionVolumesDetailsTypeDef",
     "AwsEcsTaskDetailsTypeDef",
     "AwsEfsAccessPointDetailsTypeDef",
     "AwsEksClusterDetailsTypeDef",
     "AwsElasticsearchDomainDetailsTypeDef",
     "AwsElbLoadBalancerDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef",
     "AwsIamAccessKeyDetailsTypeDef",
     "AwsIamRoleDetailsTypeDef",
     "AwsLambdaFunctionDetailsTypeDef",
     "AwsOpenSearchServiceDomainDetailsTypeDef",
     "AwsRdsDbSubnetGroupTypeDef",
     "AwsRedshiftClusterDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationFilterTypeDef",
+    "AwsS3BucketObjectLockConfigurationTypeDef",
     "AwsS3BucketServerSideEncryptionConfigurationTypeDef",
     "AwsS3BucketWebsiteConfigurationTypeDef",
     "BatchUpdateFindingsResponseTypeDef",
     "AwsSsmPatchComplianceDetailsTypeDef",
+    "AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef",
     "AwsWafRegionalRuleGroupDetailsTypeDef",
     "AwsWafRegionalWebAclDetailsTypeDef",
     "AwsWafRuleGroupDetailsTypeDef",
     "AwsWafWebAclDetailsTypeDef",
     "AwsWafv2ActionAllowDetailsTypeDef",
     "AwsWafv2RulesActionCaptchaDetailsTypeDef",
     "AwsWafv2RulesActionCountDetailsTypeDef",
     "AwsWafv2ActionBlockDetailsTypeDef",
+    "BatchGetStandardsControlAssociationsResponseTypeDef",
+    "BatchUpdateStandardsControlAssociationsResponseTypeDef",
+    "AutomationRulesFindingFiltersTypeDef",
     "AwsSecurityFindingFiltersTypeDef",
+    "GetFindingHistoryResponseTypeDef",
     "GetInsightResultsResponseTypeDef",
     "NetworkHeaderTypeDef",
     "OccurrencesTypeDef",
     "RuleGroupSourceStatelessRuleDefinitionTypeDef",
     "DescribeStandardsResponseTypeDef",
     "BatchDisableStandardsResponseTypeDef",
     "BatchEnableStandardsResponseTypeDef",
@@ -647,19 +728,24 @@
     "AwsCertificateManagerCertificateDetailsTypeDef",
     "AwsCloudFrontDistributionOriginsTypeDef",
     "AwsCloudFrontDistributionOriginGroupsTypeDef",
     "AwsDynamoDbTableDetailsTypeDef",
     "AwsEc2LaunchTemplateDetailsTypeDef",
     "AwsEcsClusterDetailsTypeDef",
     "AwsEcsTaskDefinitionDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesDetailsTypeDef",
     "AwsRdsDbInstanceDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationDetailTypeDef",
+    "AwsStepFunctionStateMachineDetailsTypeDef",
     "AwsWafv2RulesActionDetailsTypeDef",
     "AwsWafv2WebAclActionDetailsTypeDef",
+    "AutomationRulesConfigTypeDef",
+    "CreateAutomationRuleRequestRequestTypeDef",
+    "UpdateAutomationRulesRequestItemTypeDef",
     "CreateInsightRequestRequestTypeDef",
     "GetFindingsRequestGetFindingsPaginateTypeDef",
     "GetFindingsRequestRequestTypeDef",
     "InsightTypeDef",
     "UpdateFindingsRequestRequestTypeDef",
     "UpdateInsightRequestRequestTypeDef",
     "NetworkPathComponentTypeDef",
@@ -667,17 +753,20 @@
     "SensitiveDataDetectionsTypeDef",
     "RuleGroupSourceStatelessRulesDetailsTypeDef",
     "FirewallPolicyStatelessCustomActionsDetailsTypeDef",
     "RuleGroupSourceCustomActionsDetailsTypeDef",
     "ActionTypeDef",
     "AwsBackupBackupPlanDetailsTypeDef",
     "AwsCloudFrontDistributionDetailsTypeDef",
+    "AwsGuardDutyDetectorDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationTypeDef",
     "AwsWafv2RulesDetailsTypeDef",
+    "BatchGetAutomationRulesResponseTypeDef",
+    "BatchUpdateAutomationRulesRequestRequestTypeDef",
     "GetInsightsResponseTypeDef",
     "CustomDataIdentifiersResultTypeDef",
     "SensitiveDataResultTypeDef",
     "FirewallPolicyDetailsTypeDef",
     "RuleGroupSourceStatelessRulesAndCustomActionsDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationDetailsTypeDef",
     "AwsWafv2RuleGroupDetailsTypeDef",
@@ -722,19 +811,17 @@
     "_OptionalAccountDetailsTypeDef",
     {
         "Email": str,
     },
     total=False,
 )
 
-
 class AccountDetailsTypeDef(_RequiredAccountDetailsTypeDef, _OptionalAccountDetailsTypeDef):
     pass
 
-
 ActionLocalIpDetailsTypeDef = TypedDict(
     "ActionLocalIpDetailsTypeDef",
     {
         "IpAddressV4": str,
     },
     total=False,
 )
@@ -835,23 +922,165 @@
     "AssociatedStandardTypeDef",
     {
         "StandardsId": str,
     },
     total=False,
 )
 
+AssociationStateDetailsTypeDef = TypedDict(
+    "AssociationStateDetailsTypeDef",
+    {
+        "State": str,
+        "StatusMessage": str,
+    },
+    total=False,
+)
+
+NoteUpdateTypeDef = TypedDict(
+    "NoteUpdateTypeDef",
+    {
+        "Text": str,
+        "UpdatedBy": str,
+    },
+)
+
+RelatedFindingTypeDef = TypedDict(
+    "RelatedFindingTypeDef",
+    {
+        "ProductArn": str,
+        "Id": str,
+    },
+)
+
+SeverityUpdateTypeDef = TypedDict(
+    "SeverityUpdateTypeDef",
+    {
+        "Normalized": int,
+        "Product": float,
+        "Label": SeverityLabelType,
+    },
+    total=False,
+)
+
+WorkflowUpdateTypeDef = TypedDict(
+    "WorkflowUpdateTypeDef",
+    {
+        "Status": WorkflowStatusType,
+    },
+    total=False,
+)
+
+MapFilterTypeDef = TypedDict(
+    "MapFilterTypeDef",
+    {
+        "Key": str,
+        "Value": str,
+        "Comparison": MapFilterComparisonType,
+    },
+    total=False,
+)
+
+NumberFilterTypeDef = TypedDict(
+    "NumberFilterTypeDef",
+    {
+        "Gte": float,
+        "Lte": float,
+        "Eq": float,
+    },
+    total=False,
+)
+
+StringFilterTypeDef = TypedDict(
+    "StringFilterTypeDef",
+    {
+        "Value": str,
+        "Comparison": StringFilterComparisonType,
+    },
+    total=False,
+)
+
+AutomationRulesMetadataTypeDef = TypedDict(
+    "AutomationRulesMetadataTypeDef",
+    {
+        "RuleArn": str,
+        "RuleStatus": RuleStatusType,
+        "RuleOrder": int,
+        "RuleName": str,
+        "Description": str,
+        "IsTerminal": bool,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "CreatedBy": str,
+    },
+    total=False,
+)
+
 AvailabilityZoneTypeDef = TypedDict(
     "AvailabilityZoneTypeDef",
     {
         "ZoneName": str,
         "SubnetId": str,
     },
     total=False,
 )
 
+AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef",
+    {
+        "KmsKeyId": str,
+        "UseAwsOwnedKey": bool,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef",
+    {
+        "Hosts": Sequence[str],
+        "RoleBase": str,
+        "RoleName": str,
+        "RoleSearchMatching": str,
+        "RoleSearchSubtree": bool,
+        "ServiceAccountUsername": str,
+        "UserBase": str,
+        "UserRoleName": str,
+        "UserSearchMatching": str,
+        "UserSearchSubtree": bool,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef",
+    {
+        "DayOfWeek": str,
+        "TimeOfDay": str,
+        "TimeZone": str,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerUsersDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerUsersDetailsTypeDef",
+    {
+        "PendingChange": str,
+        "Username": str,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerLogsPendingDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerLogsPendingDetailsTypeDef",
+    {
+        "Audit": bool,
+        "General": bool,
+    },
+    total=False,
+)
+
 AwsApiCallActionDomainDetailsTypeDef = TypedDict(
     "AwsApiCallActionDomainDetailsTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
@@ -924,14 +1153,56 @@
         "DataTraceEnabled": bool,
         "ThrottlingBurstLimit": int,
         "ThrottlingRateLimit": float,
     },
     total=False,
 )
 
+AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef",
+    {
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerUri": str,
+        "IdentityValidationExpression": str,
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef",
+    {
+        "AuthTtL": int,
+        "ClientId": str,
+        "IatTtL": int,
+        "Issuer": str,
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef",
+    {
+        "AppIdClientRegex": str,
+        "AwsRegion": str,
+        "DefaultAction": str,
+        "UserPoolId": str,
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiLogConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiLogConfigDetailsTypeDef",
+    {
+        "CloudWatchLogsRoleArn": str,
+        "ExcludeVerboseContent": bool,
+        "FieldLogLevel": str,
+    },
+    total=False,
+)
+
 AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef = TypedDict(
     "AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
@@ -1404,14 +1675,22 @@
         "HttpPutResponseHopLimit": int,
         "HttpTokens": str,
         "InstanceMetadataTags": str,
     },
     total=False,
 )
 
+AwsEc2InstanceMonitoringDetailsTypeDef = TypedDict(
+    "AwsEc2InstanceMonitoringDetailsTypeDef",
+    {
+        "State": str,
+    },
+    total=False,
+)
+
 AwsEc2InstanceNetworkInterfacesDetailsTypeDef = TypedDict(
     "AwsEc2InstanceNetworkInterfacesDetailsTypeDef",
     {
         "NetworkInterfaceId": str,
     },
     total=False,
 )
@@ -1741,14 +2020,45 @@
     {
         "GroupName": str,
         "GroupId": str,
     },
     total=False,
 )
 
+PropagatingVgwSetDetailsTypeDef = TypedDict(
+    "PropagatingVgwSetDetailsTypeDef",
+    {
+        "GatewayId": str,
+    },
+    total=False,
+)
+
+RouteSetDetailsTypeDef = TypedDict(
+    "RouteSetDetailsTypeDef",
+    {
+        "CarrierGatewayId": str,
+        "CoreNetworkArn": str,
+        "DestinationCidrBlock": str,
+        "DestinationIpv6CidrBlock": str,
+        "DestinationPrefixListId": str,
+        "EgressOnlyInternetGatewayId": str,
+        "GatewayId": str,
+        "InstanceId": str,
+        "InstanceOwnerId": str,
+        "LocalGatewayId": str,
+        "NatGatewayId": str,
+        "NetworkInterfaceId": str,
+        "Origin": str,
+        "State": str,
+        "TransitGatewayId": str,
+        "VpcPeeringConnectionId": str,
+    },
+    total=False,
+)
+
 AwsEc2SecurityGroupIpRangeTypeDef = TypedDict(
     "AwsEc2SecurityGroupIpRangeTypeDef",
     {
         "CidrIp": str,
     },
     total=False,
 )
@@ -2321,14 +2631,15 @@
 )
 
 AwsEksClusterResourcesVpcConfigDetailsTypeDef = TypedDict(
     "AwsEksClusterResourcesVpcConfigDetailsTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
         "SubnetIds": Sequence[str],
+        "EndpointPublicAccess": bool,
     },
     total=False,
 )
 
 AwsEksClusterLoggingClusterLoggingDetailsTypeDef = TypedDict(
     "AwsEksClusterLoggingClusterLoggingDetailsTypeDef",
     {
@@ -2563,14 +2874,82 @@
     {
         "Code": str,
         "Reason": str,
     },
     total=False,
 )
 
+AwsEventSchemasRegistryDetailsTypeDef = TypedDict(
+    "AwsEventSchemasRegistryDetailsTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef",
+    {
+        "Reason": str,
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorFeaturesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorFeaturesDetailsTypeDef",
+    {
+        "Name": str,
+        "Status": str,
+    },
+    total=False,
+)
+
 AwsIamAccessKeySessionContextAttributesTypeDef = TypedDict(
     "AwsIamAccessKeySessionContextAttributesTypeDef",
     {
         "MfaAuthenticated": bool,
         "CreationDate": str,
     },
     total=False,
@@ -3246,14 +3625,24 @@
     {
         "Name": AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType,
         "Value": str,
     },
     total=False,
 )
 
+AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef = TypedDict(
+    "AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef",
+    {
+        "Days": int,
+        "Mode": str,
+        "Years": int,
+    },
+    total=False,
+)
+
 AwsS3BucketServerSideEncryptionByDefaultTypeDef = TypedDict(
     "AwsS3BucketServerSideEncryptionByDefaultTypeDef",
     {
         "SSEAlgorithm": str,
         "KMSMasterKeyID": str,
     },
     total=False,
@@ -3338,43 +3727,14 @@
     "KeywordFilterTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
-MapFilterTypeDef = TypedDict(
-    "MapFilterTypeDef",
-    {
-        "Key": str,
-        "Value": str,
-        "Comparison": MapFilterComparisonType,
-    },
-    total=False,
-)
-
-NumberFilterTypeDef = TypedDict(
-    "NumberFilterTypeDef",
-    {
-        "Gte": float,
-        "Lte": float,
-        "Eq": float,
-    },
-    total=False,
-)
-
-StringFilterTypeDef = TypedDict(
-    "StringFilterTypeDef",
-    {
-        "Value": str,
-        "Comparison": StringFilterComparisonType,
-    },
-    total=False,
-)
-
 AwsSecurityFindingIdentifierTypeDef = TypedDict(
     "AwsSecurityFindingIdentifierTypeDef",
     {
         "Id": str,
         "ProductArn": str,
     },
 )
@@ -3391,19 +3751,17 @@
         "Type": MalwareTypeType,
         "Path": str,
         "State": MalwareStateType,
     },
     total=False,
 )
 
-
 class MalwareTypeDef(_RequiredMalwareTypeDef, _OptionalMalwareTypeDef):
     pass
 
-
 NoteTypeDef = TypedDict(
     "NoteTypeDef",
     {
         "Text": str,
         "UpdatedBy": str,
         "UpdatedAt": str,
     },
@@ -3428,40 +3786,30 @@
         "OperationEndTime": str,
         "RebootOption": str,
         "Operation": str,
     },
     total=False,
 )
 
-
 class PatchSummaryTypeDef(_RequiredPatchSummaryTypeDef, _OptionalPatchSummaryTypeDef):
     pass
 
-
 ProcessDetailsTypeDef = TypedDict(
     "ProcessDetailsTypeDef",
     {
         "Name": str,
         "Path": str,
         "Pid": int,
         "ParentPid": int,
         "LaunchedAt": str,
         "TerminatedAt": str,
     },
     total=False,
 )
 
-RelatedFindingTypeDef = TypedDict(
-    "RelatedFindingTypeDef",
-    {
-        "ProductArn": str,
-        "Id": str,
-    },
-)
-
 SeverityTypeDef = TypedDict(
     "SeverityTypeDef",
     {
         "Product": float,
         "Label": SeverityLabelType,
         "Normalized": int,
         "Original": str,
@@ -3531,14 +3879,30 @@
         "NonCompliantMediumCount": int,
         "NonCompliantUnspecifiedCount": int,
         "PatchGroup": str,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef",
+    {
+        "Enabled": bool,
+    },
+    total=False,
+)
+
+AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef",
+    {
+        "LogGroupArn": str,
+    },
+    total=False,
+)
+
 AwsWafRateBasedRuleMatchPredicateTypeDef = TypedDict(
     "AwsWafRateBasedRuleMatchPredicateTypeDef",
     {
         "DataId": str,
         "Negated": bool,
         "Type": str,
     },
@@ -3664,29 +4028,35 @@
         "KeyId": str,
         "Status": str,
         "Type": str,
     },
     total=False,
 )
 
-BatchDisableStandardsRequestRequestTypeDef = TypedDict(
-    "BatchDisableStandardsRequestRequestTypeDef",
+BatchDeleteAutomationRulesRequestRequestTypeDef = TypedDict(
+    "BatchDeleteAutomationRulesRequestRequestTypeDef",
     {
-        "StandardsSubscriptionArns": Sequence[str],
+        "AutomationRulesArns": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+UnprocessedAutomationRuleTypeDef = TypedDict(
+    "UnprocessedAutomationRuleTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "RuleArn": str,
+        "ErrorCode": int,
+        "ErrorMessage": str,
+    },
+    total=False,
+)
+
+BatchDisableStandardsRequestRequestTypeDef = TypedDict(
+    "BatchDisableStandardsRequestRequestTypeDef",
+    {
+        "StandardsSubscriptionArns": Sequence[str],
     },
 )
 
 _RequiredStandardsSubscriptionRequestTypeDef = TypedDict(
     "_RequiredStandardsSubscriptionRequestTypeDef",
     {
         "StandardsArn": str,
@@ -3696,56 +4066,133 @@
     "_OptionalStandardsSubscriptionRequestTypeDef",
     {
         "StandardsInput": Mapping[str, str],
     },
     total=False,
 )
 
-
 class StandardsSubscriptionRequestTypeDef(
     _RequiredStandardsSubscriptionRequestTypeDef, _OptionalStandardsSubscriptionRequestTypeDef
 ):
     pass
 
+BatchGetAutomationRulesRequestRequestTypeDef = TypedDict(
+    "BatchGetAutomationRulesRequestRequestTypeDef",
+    {
+        "AutomationRulesArns": Sequence[str],
+    },
+)
 
-ImportFindingsErrorTypeDef = TypedDict(
-    "ImportFindingsErrorTypeDef",
+BatchGetSecurityControlsRequestRequestTypeDef = TypedDict(
+    "BatchGetSecurityControlsRequestRequestTypeDef",
     {
-        "Id": str,
-        "ErrorCode": str,
-        "ErrorMessage": str,
+        "SecurityControlIds": Sequence[str],
     },
 )
 
-NoteUpdateTypeDef = TypedDict(
-    "NoteUpdateTypeDef",
+SecurityControlTypeDef = TypedDict(
+    "SecurityControlTypeDef",
     {
-        "Text": str,
-        "UpdatedBy": str,
+        "SecurityControlId": str,
+        "SecurityControlArn": str,
+        "Title": str,
+        "Description": str,
+        "RemediationUrl": str,
+        "SeverityRating": SeverityRatingType,
+        "SecurityControlStatus": ControlStatusType,
     },
 )
 
-SeverityUpdateTypeDef = TypedDict(
-    "SeverityUpdateTypeDef",
+_RequiredUnprocessedSecurityControlTypeDef = TypedDict(
+    "_RequiredUnprocessedSecurityControlTypeDef",
     {
-        "Normalized": int,
-        "Product": float,
-        "Label": SeverityLabelType,
+        "SecurityControlId": str,
+        "ErrorCode": UnprocessedErrorCodeType,
+    },
+)
+_OptionalUnprocessedSecurityControlTypeDef = TypedDict(
+    "_OptionalUnprocessedSecurityControlTypeDef",
+    {
+        "ErrorReason": str,
     },
     total=False,
 )
 
-WorkflowUpdateTypeDef = TypedDict(
-    "WorkflowUpdateTypeDef",
+class UnprocessedSecurityControlTypeDef(
+    _RequiredUnprocessedSecurityControlTypeDef, _OptionalUnprocessedSecurityControlTypeDef
+):
+    pass
+
+StandardsControlAssociationIdTypeDef = TypedDict(
+    "StandardsControlAssociationIdTypeDef",
     {
-        "Status": WorkflowStatusType,
+        "SecurityControlId": str,
+        "StandardsArn": str,
+    },
+)
+
+_RequiredStandardsControlAssociationDetailTypeDef = TypedDict(
+    "_RequiredStandardsControlAssociationDetailTypeDef",
+    {
+        "StandardsArn": str,
+        "SecurityControlId": str,
+        "SecurityControlArn": str,
+        "AssociationStatus": AssociationStatusType,
+    },
+)
+_OptionalStandardsControlAssociationDetailTypeDef = TypedDict(
+    "_OptionalStandardsControlAssociationDetailTypeDef",
+    {
+        "RelatedRequirements": List[str],
+        "UpdatedAt": datetime,
+        "UpdatedReason": str,
+        "StandardsControlTitle": str,
+        "StandardsControlDescription": str,
+        "StandardsControlArns": List[str],
     },
     total=False,
 )
 
+class StandardsControlAssociationDetailTypeDef(
+    _RequiredStandardsControlAssociationDetailTypeDef,
+    _OptionalStandardsControlAssociationDetailTypeDef,
+):
+    pass
+
+ImportFindingsErrorTypeDef = TypedDict(
+    "ImportFindingsErrorTypeDef",
+    {
+        "Id": str,
+        "ErrorCode": str,
+        "ErrorMessage": str,
+    },
+)
+
+_RequiredStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_RequiredStandardsControlAssociationUpdateTypeDef",
+    {
+        "StandardsArn": str,
+        "SecurityControlId": str,
+        "AssociationStatus": AssociationStatusType,
+    },
+)
+_OptionalStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_OptionalStandardsControlAssociationUpdateTypeDef",
+    {
+        "UpdatedReason": str,
+    },
+    total=False,
+)
+
+class StandardsControlAssociationUpdateTypeDef(
+    _RequiredStandardsControlAssociationUpdateTypeDef,
+    _OptionalStandardsControlAssociationUpdateTypeDef,
+):
+    pass
+
 CellTypeDef = TypedDict(
     "CellTypeDef",
     {
         "Column": int,
         "Row": int,
         "ColumnName": str,
         "CellReference": str,
@@ -3772,19 +4219,17 @@
     "_OptionalStatusReasonTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
-
 class StatusReasonTypeDef(_RequiredStatusReasonTypeDef, _OptionalStatusReasonTypeDef):
     pass
 
-
 VolumeMountTypeDef = TypedDict(
     "VolumeMountTypeDef",
     {
         "Name": str,
         "MountPath": str,
     },
     total=False,
@@ -3795,35 +4240,68 @@
     {
         "Name": str,
         "Description": str,
         "Id": str,
     },
 )
 
+CreateActionTargetResponseTypeDef = TypedDict(
+    "CreateActionTargetResponseTypeDef",
+    {
+        "ActionTargetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAutomationRuleResponseTypeDef = TypedDict(
+    "CreateAutomationRuleResponseTypeDef",
+    {
+        "RuleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateFindingAggregatorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFindingAggregatorRequestRequestTypeDef",
     {
         "RegionLinkingMode": str,
     },
 )
 _OptionalCreateFindingAggregatorRequestRequestTypeDef = TypedDict(
     "_OptionalCreateFindingAggregatorRequestRequestTypeDef",
     {
         "Regions": Sequence[str],
     },
     total=False,
 )
 
-
 class CreateFindingAggregatorRequestRequestTypeDef(
     _RequiredCreateFindingAggregatorRequestRequestTypeDef,
     _OptionalCreateFindingAggregatorRequestRequestTypeDef,
 ):
     pass
 
+CreateFindingAggregatorResponseTypeDef = TypedDict(
+    "CreateFindingAggregatorResponseTypeDef",
+    {
+        "FindingAggregatorArn": str,
+        "FindingAggregationRegion": str,
+        "RegionLinkingMode": str,
+        "Regions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateInsightResponseTypeDef = TypedDict(
+    "CreateInsightResponseTypeDef",
+    {
+        "InsightArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ResultTypeDef = TypedDict(
     "ResultTypeDef",
     {
         "AccountId": str,
         "ProcessingResult": str,
     },
@@ -3849,48 +4327,63 @@
 DeleteActionTargetRequestRequestTypeDef = TypedDict(
     "DeleteActionTargetRequestRequestTypeDef",
     {
         "ActionTargetArn": str,
     },
 )
 
+DeleteActionTargetResponseTypeDef = TypedDict(
+    "DeleteActionTargetResponseTypeDef",
+    {
+        "ActionTargetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFindingAggregatorRequestRequestTypeDef = TypedDict(
     "DeleteFindingAggregatorRequestRequestTypeDef",
     {
         "FindingAggregatorArn": str,
     },
 )
 
 DeleteInsightRequestRequestTypeDef = TypedDict(
     "DeleteInsightRequestRequestTypeDef",
     {
         "InsightArn": str,
     },
 )
 
+DeleteInsightResponseTypeDef = TypedDict(
+    "DeleteInsightResponseTypeDef",
+    {
+        "InsightArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteInvitationsRequestRequestTypeDef = TypedDict(
     "DeleteInvitationsRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
 DeleteMembersRequestRequestTypeDef = TypedDict(
     "DeleteMembersRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef = TypedDict(
+    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ActionTargetArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeActionTargetsRequestRequestTypeDef = TypedDict(
     "DescribeActionTargetsRequestRequestTypeDef",
     {
@@ -3905,14 +4398,44 @@
     "DescribeHubRequestRequestTypeDef",
     {
         "HubArn": str,
     },
     total=False,
 )
 
+DescribeHubResponseTypeDef = TypedDict(
+    "DescribeHubResponseTypeDef",
+    {
+        "HubArn": str,
+        "SubscribedAt": str,
+        "AutoEnableControls": bool,
+        "ControlFindingGenerator": ControlFindingGeneratorType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    {
+        "AutoEnable": bool,
+        "MemberAccountLimitReached": bool,
+        "AutoEnableStandards": AutoEnableStandardsType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeProductsRequestDescribeProductsPaginateTypeDef = TypedDict(
+    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
+    {
+        "ProductArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeProductsRequestRequestTypeDef = TypedDict(
     "DescribeProductsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ProductArn": str,
     },
@@ -3936,18 +4459,36 @@
         "MarketplaceUrl": str,
         "ActivationUrl": str,
         "ProductSubscriptionResourcePolicy": str,
     },
     total=False,
 )
 
-
 class ProductTypeDef(_RequiredProductTypeDef, _OptionalProductTypeDef):
     pass
 
+_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
+    {
+        "StandardsSubscriptionArn": str,
+    },
+)
+_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef(
+    _RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
+    _OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
+):
+    pass
 
 _RequiredDescribeStandardsControlsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeStandardsControlsRequestRequestTypeDef",
     {
         "StandardsSubscriptionArn": str,
     },
 )
@@ -3956,22 +4497,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class DescribeStandardsControlsRequestRequestTypeDef(
     _RequiredDescribeStandardsControlsRequestRequestTypeDef,
     _OptionalDescribeStandardsControlsRequestRequestTypeDef,
 ):
     pass
 
-
 StandardsControlTypeDef = TypedDict(
     "StandardsControlTypeDef",
     {
         "StandardsControlArn": str,
         "ControlStatus": ControlStatusType,
         "DisabledReason": str,
         "ControlStatusUpdatedAt": datetime,
@@ -3981,14 +4520,22 @@
         "RemediationUrl": str,
         "SeverityRating": SeverityRatingType,
         "RelatedRequirements": List[str],
     },
     total=False,
 )
 
+DescribeStandardsRequestDescribeStandardsPaginateTypeDef = TypedDict(
+    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStandardsRequestRequestTypeDef = TypedDict(
     "DescribeStandardsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -4018,26 +4565,35 @@
 EnableImportFindingsForProductRequestRequestTypeDef = TypedDict(
     "EnableImportFindingsForProductRequestRequestTypeDef",
     {
         "ProductArn": str,
     },
 )
 
+EnableImportFindingsForProductResponseTypeDef = TypedDict(
+    "EnableImportFindingsForProductResponseTypeDef",
+    {
+        "ProductSubscriptionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     {
         "AdminAccountId": str,
     },
 )
 
 EnableSecurityHubRequestRequestTypeDef = TypedDict(
     "EnableSecurityHubRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
         "EnableDefaultStandards": bool,
+        "ControlFindingGenerator": ControlFindingGeneratorType,
     },
     total=False,
 )
 
 FilePathsTypeDef = TypedDict(
     "FilePathsTypeDef",
     {
@@ -4053,14 +4609,33 @@
     "FindingAggregatorTypeDef",
     {
         "FindingAggregatorArn": str,
     },
     total=False,
 )
 
+FindingHistoryUpdateSourceTypeDef = TypedDict(
+    "FindingHistoryUpdateSourceTypeDef",
+    {
+        "Type": FindingHistoryUpdateSourceTypeType,
+        "Identity": str,
+    },
+    total=False,
+)
+
+FindingHistoryUpdateTypeDef = TypedDict(
+    "FindingHistoryUpdateTypeDef",
+    {
+        "UpdatedField": str,
+        "OldValue": str,
+        "NewValue": str,
+    },
+    total=False,
+)
+
 FindingProviderSeverityTypeDef = TypedDict(
     "FindingProviderSeverityTypeDef",
     {
         "Label": SeverityLabelType,
         "Original": str,
     },
     total=False,
@@ -4090,14 +4665,23 @@
         "InvitationId": str,
         "InvitedAt": datetime,
         "MemberStatus": str,
     },
     total=False,
 )
 
+GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef = TypedDict(
+    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
+    {
+        "StandardsSubscriptionArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetEnabledStandardsRequestRequestTypeDef = TypedDict(
     "GetEnabledStandardsRequestRequestTypeDef",
     {
         "StandardsSubscriptionArns": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
@@ -4107,14 +4691,25 @@
 GetFindingAggregatorRequestRequestTypeDef = TypedDict(
     "GetFindingAggregatorRequestRequestTypeDef",
     {
         "FindingAggregatorArn": str,
     },
 )
 
+GetFindingAggregatorResponseTypeDef = TypedDict(
+    "GetFindingAggregatorResponseTypeDef",
+    {
+        "FindingAggregatorArn": str,
+        "FindingAggregationRegion": str,
+        "RegionLinkingMode": str,
+        "Regions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SortCriterionTypeDef = TypedDict(
     "SortCriterionTypeDef",
     {
         "Field": str,
         "SortOrder": SortOrderType,
     },
     total=False,
@@ -4123,24 +4718,41 @@
 GetInsightResultsRequestRequestTypeDef = TypedDict(
     "GetInsightResultsRequestRequestTypeDef",
     {
         "InsightArn": str,
     },
 )
 
+GetInsightsRequestGetInsightsPaginateTypeDef = TypedDict(
+    "GetInsightsRequestGetInsightsPaginateTypeDef",
+    {
+        "InsightArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInsightsRequestRequestTypeDef = TypedDict(
     "GetInsightsRequestRequestTypeDef",
     {
         "InsightArns": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+GetInvitationsCountResponseTypeDef = TypedDict(
+    "GetInvitationsCountResponseTypeDef",
+    {
+        "InvitationsCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMembersRequestRequestTypeDef = TypedDict(
     "GetMembersRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
@@ -4169,67 +4781,233 @@
 InviteMembersRequestRequestTypeDef = TypedDict(
     "InviteMembersRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
+ListAutomationRulesRequestRequestTypeDef = TypedDict(
+    "ListAutomationRulesRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef = TypedDict(
+    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnabledProductsForImportRequestRequestTypeDef = TypedDict(
     "ListEnabledProductsForImportRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListEnabledProductsForImportResponseTypeDef = TypedDict(
+    "ListEnabledProductsForImportResponseTypeDef",
+    {
+        "ProductSubscriptions": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef = TypedDict(
+    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFindingAggregatorsRequestRequestTypeDef = TypedDict(
     "ListFindingAggregatorsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
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
 
+ListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "ListMembersRequestListMembersPaginateTypeDef",
+    {
+        "OnlyAssociated": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMembersRequestRequestTypeDef = TypedDict(
     "ListMembersRequestRequestTypeDef",
     {
         "OnlyAssociated": bool,
         "MaxResults": int,
         "NextToken": str,
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef = TypedDict(
+    "ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef",
+    {
+        "StandardsArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListSecurityControlDefinitionsRequestRequestTypeDef = TypedDict(
+    "ListSecurityControlDefinitionsRequestRequestTypeDef",
+    {
+        "StandardsArn": str,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+SecurityControlDefinitionTypeDef = TypedDict(
+    "SecurityControlDefinitionTypeDef",
+    {
+        "SecurityControlId": str,
+        "Title": str,
+        "Description": str,
+        "RemediationUrl": str,
+        "SeverityRating": SeverityRatingType,
+        "CurrentRegionAvailability": RegionAvailabilityStatusType,
+    },
+)
+
+_RequiredListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef",
+    {
+        "SecurityControlId": str,
+    },
+)
+_OptionalListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef(
+    _RequiredListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef,
+    _OptionalListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef,
+):
+    pass
+
+_RequiredListStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "_RequiredListStandardsControlAssociationsRequestRequestTypeDef",
+    {
+        "SecurityControlId": str,
+    },
+)
+_OptionalListStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "_OptionalListStandardsControlAssociationsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class ListStandardsControlAssociationsRequestRequestTypeDef(
+    _RequiredListStandardsControlAssociationsRequestRequestTypeDef,
+    _OptionalListStandardsControlAssociationsRequestRequestTypeDef,
+):
+    pass
+
+_RequiredStandardsControlAssociationSummaryTypeDef = TypedDict(
+    "_RequiredStandardsControlAssociationSummaryTypeDef",
+    {
+        "StandardsArn": str,
+        "SecurityControlId": str,
+        "SecurityControlArn": str,
+        "AssociationStatus": AssociationStatusType,
+    },
+)
+_OptionalStandardsControlAssociationSummaryTypeDef = TypedDict(
+    "_OptionalStandardsControlAssociationSummaryTypeDef",
+    {
+        "RelatedRequirements": List[str],
+        "UpdatedAt": datetime,
+        "UpdatedReason": str,
+        "StandardsControlTitle": str,
+        "StandardsControlDescription": str,
+    },
+    total=False,
+)
+
+class StandardsControlAssociationSummaryTypeDef(
+    _RequiredStandardsControlAssociationSummaryTypeDef,
+    _OptionalStandardsControlAssociationSummaryTypeDef,
+):
+    pass
+
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
 PortRangeTypeDef = TypedDict(
     "PortRangeTypeDef",
     {
         "Begin": int,
         "End": int,
     },
     total=False,
@@ -4250,23 +5028,44 @@
     {
         "JsonPath": str,
         "RecordIndex": int,
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
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "Text": str,
         "Url": str,
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
 RuleGroupSourceListDetailsTypeDef = TypedDict(
     "RuleGroupSourceListDetailsTypeDef",
     {
         "GeneratedRulesType": str,
         "TargetTypes": Sequence[str],
         "Targets": Sequence[str],
     },
@@ -4423,22 +5222,20 @@
     {
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
-
 class UpdateActionTargetRequestRequestTypeDef(
     _RequiredUpdateActionTargetRequestRequestTypeDef,
     _OptionalUpdateActionTargetRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateFindingAggregatorRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFindingAggregatorRequestRequestTypeDef",
     {
         "FindingAggregatorArn": str,
         "RegionLinkingMode": str,
     },
 )
@@ -4446,21 +5243,30 @@
     "_OptionalUpdateFindingAggregatorRequestRequestTypeDef",
     {
         "Regions": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdateFindingAggregatorRequestRequestTypeDef(
     _RequiredUpdateFindingAggregatorRequestRequestTypeDef,
     _OptionalUpdateFindingAggregatorRequestRequestTypeDef,
 ):
     pass
 
+UpdateFindingAggregatorResponseTypeDef = TypedDict(
+    "UpdateFindingAggregatorResponseTypeDef",
+    {
+        "FindingAggregatorArn": str,
+        "FindingAggregationRegion": str,
+        "RegionLinkingMode": str,
+        "Regions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
         "AutoEnable": bool,
     },
 )
@@ -4468,26 +5274,25 @@
     "_OptionalUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
         "AutoEnableStandards": AutoEnableStandardsType,
     },
     total=False,
 )
 
-
 class UpdateOrganizationConfigurationRequestRequestTypeDef(
     _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef,
     _OptionalUpdateOrganizationConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateSecurityHubConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateSecurityHubConfigurationRequestRequestTypeDef",
     {
         "AutoEnableControls": bool,
+        "ControlFindingGenerator": ControlFindingGeneratorType,
     },
     total=False,
 )
 
 _RequiredUpdateStandardsControlRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStandardsControlRequestRequestTypeDef",
     {
@@ -4499,22 +5304,20 @@
     {
         "ControlStatus": ControlStatusType,
         "DisabledReason": str,
     },
     total=False,
 )
 
-
 class UpdateStandardsControlRequestRequestTypeDef(
     _RequiredUpdateStandardsControlRequestRequestTypeDef,
     _OptionalUpdateStandardsControlRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredVulnerabilityVendorTypeDef = TypedDict(
     "_RequiredVulnerabilityVendorTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalVulnerabilityVendorTypeDef = TypedDict(
@@ -4524,21 +5327,19 @@
         "VendorSeverity": str,
         "VendorCreatedAt": str,
         "VendorUpdatedAt": str,
     },
     total=False,
 )
 
-
 class VulnerabilityVendorTypeDef(
     _RequiredVulnerabilityVendorTypeDef, _OptionalVulnerabilityVendorTypeDef
 ):
     pass
 
-
 CreateMembersRequestRequestTypeDef = TypedDict(
     "CreateMembersRequestRequestTypeDef",
     {
         "AccountDetails": Sequence[AccountDetailsTypeDef],
     },
 )
 
@@ -4550,26 +5351,94 @@
         "Country": CountryTypeDef,
         "City": CityTypeDef,
         "GeoLocation": GeoLocationTypeDef,
     },
     total=False,
 )
 
+DescribeActionTargetsResponseTypeDef = TypedDict(
+    "DescribeActionTargetsResponseTypeDef",
+    {
+        "ActionTargets": List[ActionTargetTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CvssTypeDef = TypedDict(
     "CvssTypeDef",
     {
         "Version": str,
         "BaseScore": float,
         "BaseVector": str,
         "Source": str,
         "Adjustments": Sequence[AdjustmentTypeDef],
     },
     total=False,
 )
 
+ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    {
+        "AdminAccounts": List[AdminAccountTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociationSetDetailsTypeDef = TypedDict(
+    "AssociationSetDetailsTypeDef",
+    {
+        "AssociationState": AssociationStateDetailsTypeDef,
+        "GatewayId": str,
+        "Main": bool,
+        "RouteTableAssociationId": str,
+        "RouteTableId": str,
+        "SubnetId": str,
+    },
+    total=False,
+)
+
+AutomationRulesFindingFieldsUpdateTypeDef = TypedDict(
+    "AutomationRulesFindingFieldsUpdateTypeDef",
+    {
+        "Note": NoteUpdateTypeDef,
+        "Severity": SeverityUpdateTypeDef,
+        "VerificationState": VerificationStateType,
+        "Confidence": int,
+        "Criticality": int,
+        "Types": List[str],
+        "UserDefinedFields": Dict[str, str],
+        "Workflow": WorkflowUpdateTypeDef,
+        "RelatedFindings": List[RelatedFindingTypeDef],
+    },
+    total=False,
+)
+
+ListAutomationRulesResponseTypeDef = TypedDict(
+    "ListAutomationRulesResponseTypeDef",
+    {
+        "AutomationRulesMetadata": List[AutomationRulesMetadataTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AwsAmazonMqBrokerLogsDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerLogsDetailsTypeDef",
+    {
+        "Audit": bool,
+        "General": bool,
+        "AuditLogGroup": str,
+        "GeneralLogGroup": str,
+        "Pending": AwsAmazonMqBrokerLogsPendingDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsApiGatewayRestApiDetailsTypeDef = TypedDict(
     "AwsApiGatewayRestApiDetailsTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "CreatedDate": str,
@@ -4638,14 +5507,25 @@
         "AutoDeploy": bool,
         "LastDeploymentStatusMessage": str,
         "ApiGatewayManaged": bool,
     },
     total=False,
 )
 
+AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef",
+    {
+        "AuthenticationType": str,
+        "LambdaAuthorizerConfig": AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef,
+        "OpenIdConnectConfig": AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef,
+        "UserPoolConfig": AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef = TypedDict(
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef",
     {
         "LaunchTemplateSpecification": AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateLaunchTemplateSpecificationTypeDef,
         "Overrides": Sequence[
             AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateOverridesListDetailsTypeDef
         ],
@@ -4875,14 +5755,15 @@
         "IamInstanceProfileArn": str,
         "VpcId": str,
         "SubnetId": str,
         "LaunchedAt": str,
         "NetworkInterfaces": Sequence[AwsEc2InstanceNetworkInterfacesDetailsTypeDef],
         "VirtualizationType": str,
         "MetadataOptions": AwsEc2InstanceMetadataOptionsTypeDef,
+        "Monitoring": AwsEc2InstanceMonitoringDetailsTypeDef,
     },
     total=False,
 )
 
 AwsEc2LaunchTemplateDataBlockDeviceMappingSetDetailsTypeDef = TypedDict(
     "AwsEc2LaunchTemplateDataBlockDeviceMappingSetDetailsTypeDef",
     {
@@ -5354,14 +6235,30 @@
         "Type": str,
         "VpcId": str,
         "LoadBalancerAttributes": Sequence[AwsElbv2LoadBalancerAttributeTypeDef],
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef",
+    {
+        "AuditLogs": AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef",
+    {
+        "EbsVolumes": AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsIamAccessKeySessionContextTypeDef = TypedDict(
     "AwsIamAccessKeySessionContextTypeDef",
     {
         "Attributes": AwsIamAccessKeySessionContextAttributesTypeDef,
         "SessionIssuer": AwsIamAccessKeySessionContextSessionIssuerTypeDef,
     },
     total=False,
@@ -5651,14 +6548,22 @@
     "AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef",
     {
         "FilterRules": Sequence[AwsS3BucketNotificationConfigurationS3KeyFilterRuleTypeDef],
     },
     total=False,
 )
 
+AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef = TypedDict(
+    "AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef",
+    {
+        "DefaultRetention": AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsS3BucketServerSideEncryptionRuleTypeDef = TypedDict(
     "AwsS3BucketServerSideEncryptionRuleTypeDef",
     {
         "ApplyServerSideEncryptionByDefault": AwsS3BucketServerSideEncryptionByDefaultTypeDef,
     },
     total=False,
 )
@@ -5712,23 +6617,95 @@
         "Deleted": bool,
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
+_RequiredBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
+    "_RequiredBatchUpdateFindingsRequestRequestTypeDef",
+    {
+        "FindingIdentifiers": Sequence[AwsSecurityFindingIdentifierTypeDef],
+    },
+)
+_OptionalBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
+    "_OptionalBatchUpdateFindingsRequestRequestTypeDef",
+    {
+        "Note": NoteUpdateTypeDef,
+        "Severity": SeverityUpdateTypeDef,
+        "VerificationState": VerificationStateType,
+        "Confidence": int,
+        "Criticality": int,
+        "Types": Sequence[str],
+        "UserDefinedFields": Mapping[str, str],
+        "Workflow": WorkflowUpdateTypeDef,
+        "RelatedFindings": Sequence[RelatedFindingTypeDef],
+    },
+    total=False,
+)
+
+class BatchUpdateFindingsRequestRequestTypeDef(
+    _RequiredBatchUpdateFindingsRequestRequestTypeDef,
+    _OptionalBatchUpdateFindingsRequestRequestTypeDef,
+):
+    pass
+
 BatchUpdateFindingsUnprocessedFindingTypeDef = TypedDict(
     "BatchUpdateFindingsUnprocessedFindingTypeDef",
     {
         "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
 )
 
+_RequiredGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef",
+    {
+        "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
+    },
+)
+_OptionalGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetFindingHistoryRequestGetFindingHistoryPaginateTypeDef(
+    _RequiredGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef,
+    _OptionalGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef,
+):
+    pass
+
+_RequiredGetFindingHistoryRequestRequestTypeDef = TypedDict(
+    "_RequiredGetFindingHistoryRequestRequestTypeDef",
+    {
+        "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
+    },
+)
+_OptionalGetFindingHistoryRequestRequestTypeDef = TypedDict(
+    "_OptionalGetFindingHistoryRequestRequestTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class GetFindingHistoryRequestRequestTypeDef(
+    _RequiredGetFindingHistoryRequestRequestTypeDef, _OptionalGetFindingHistoryRequestRequestTypeDef
+):
+    pass
+
 AwsSnsTopicDetailsTypeDef = TypedDict(
     "AwsSnsTopicDetailsTypeDef",
     {
         "KmsMasterKeyId": str,
         "Subscription": Sequence[AwsSnsTopicSubscriptionTypeDef],
         "TopicName": str,
         "Owner": str,
@@ -5747,14 +6724,22 @@
     "AwsSsmPatchTypeDef",
     {
         "ComplianceSummary": AwsSsmComplianceSummaryTypeDef,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef",
+    {
+        "CloudWatchLogsLogGroup": AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsWafRateBasedRuleDetailsTypeDef = TypedDict(
     "AwsWafRateBasedRuleDetailsTypeDef",
     {
         "MetricName": str,
         "Name": str,
         "RateKey": str,
         "RateLimit": int,
@@ -5868,197 +6853,114 @@
     "AwsWafv2WebAclCaptchaConfigDetailsTypeDef",
     {
         "ImmunityTimeProperty": AwsWafv2WebAclCaptchaConfigImmunityTimePropertyDetailsTypeDef,
     },
     total=False,
 )
 
-CreateActionTargetResponseTypeDef = TypedDict(
-    "CreateActionTargetResponseTypeDef",
-    {
-        "ActionTargetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFindingAggregatorResponseTypeDef = TypedDict(
-    "CreateFindingAggregatorResponseTypeDef",
-    {
-        "FindingAggregatorArn": str,
-        "FindingAggregationRegion": str,
-        "RegionLinkingMode": str,
-        "Regions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateInsightResponseTypeDef = TypedDict(
-    "CreateInsightResponseTypeDef",
-    {
-        "InsightArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteActionTargetResponseTypeDef = TypedDict(
-    "DeleteActionTargetResponseTypeDef",
-    {
-        "ActionTargetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteInsightResponseTypeDef = TypedDict(
-    "DeleteInsightResponseTypeDef",
-    {
-        "InsightArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeActionTargetsResponseTypeDef = TypedDict(
-    "DescribeActionTargetsResponseTypeDef",
+BatchDeleteAutomationRulesResponseTypeDef = TypedDict(
+    "BatchDeleteAutomationRulesResponseTypeDef",
     {
-        "ActionTargets": List[ActionTargetTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProcessedAutomationRules": List[str],
+        "UnprocessedAutomationRules": List[UnprocessedAutomationRuleTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeHubResponseTypeDef = TypedDict(
-    "DescribeHubResponseTypeDef",
+BatchUpdateAutomationRulesResponseTypeDef = TypedDict(
+    "BatchUpdateAutomationRulesResponseTypeDef",
     {
-        "HubArn": str,
-        "SubscribedAt": str,
-        "AutoEnableControls": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    {
-        "AutoEnable": bool,
-        "MemberAccountLimitReached": bool,
-        "AutoEnableStandards": AutoEnableStandardsType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EnableImportFindingsForProductResponseTypeDef = TypedDict(
-    "EnableImportFindingsForProductResponseTypeDef",
-    {
-        "ProductSubscriptionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFindingAggregatorResponseTypeDef = TypedDict(
-    "GetFindingAggregatorResponseTypeDef",
-    {
-        "FindingAggregatorArn": str,
-        "FindingAggregationRegion": str,
-        "RegionLinkingMode": str,
-        "Regions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProcessedAutomationRules": List[str],
+        "UnprocessedAutomationRules": List[UnprocessedAutomationRuleTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetInvitationsCountResponseTypeDef = TypedDict(
-    "GetInvitationsCountResponseTypeDef",
+BatchEnableStandardsRequestRequestTypeDef = TypedDict(
+    "BatchEnableStandardsRequestRequestTypeDef",
     {
-        "InvitationsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StandardsSubscriptionRequests": Sequence[StandardsSubscriptionRequestTypeDef],
     },
 )
 
-ListEnabledProductsForImportResponseTypeDef = TypedDict(
-    "ListEnabledProductsForImportResponseTypeDef",
+BatchGetSecurityControlsResponseTypeDef = TypedDict(
+    "BatchGetSecurityControlsResponseTypeDef",
     {
-        "ProductSubscriptions": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SecurityControls": List[SecurityControlTypeDef],
+        "UnprocessedIds": List[UnprocessedSecurityControlTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
-    "ListOrganizationAdminAccountsResponseTypeDef",
+BatchGetStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "BatchGetStandardsControlAssociationsRequestRequestTypeDef",
     {
-        "AdminAccounts": List[AdminAccountTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StandardsControlAssociationIds": Sequence[StandardsControlAssociationIdTypeDef],
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_RequiredUnprocessedStandardsControlAssociationTypeDef = TypedDict(
+    "_RequiredUnprocessedStandardsControlAssociationTypeDef",
     {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StandardsControlAssociationId": StandardsControlAssociationIdTypeDef,
+        "ErrorCode": UnprocessedErrorCodeType,
     },
 )
-
-UpdateFindingAggregatorResponseTypeDef = TypedDict(
-    "UpdateFindingAggregatorResponseTypeDef",
+_OptionalUnprocessedStandardsControlAssociationTypeDef = TypedDict(
+    "_OptionalUnprocessedStandardsControlAssociationTypeDef",
     {
-        "FindingAggregatorArn": str,
-        "FindingAggregationRegion": str,
-        "RegionLinkingMode": str,
-        "Regions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ErrorReason": str,
     },
+    total=False,
 )
 
-BatchEnableStandardsRequestRequestTypeDef = TypedDict(
-    "BatchEnableStandardsRequestRequestTypeDef",
-    {
-        "StandardsSubscriptionRequests": Sequence[StandardsSubscriptionRequestTypeDef],
-    },
-)
+class UnprocessedStandardsControlAssociationTypeDef(
+    _RequiredUnprocessedStandardsControlAssociationTypeDef,
+    _OptionalUnprocessedStandardsControlAssociationTypeDef,
+):
+    pass
 
 BatchImportFindingsResponseTypeDef = TypedDict(
     "BatchImportFindingsResponseTypeDef",
     {
         "FailedCount": int,
         "SuccessCount": int,
         "FailedFindings": List[ImportFindingsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
-    "_RequiredBatchUpdateFindingsRequestRequestTypeDef",
+BatchUpdateStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "BatchUpdateStandardsControlAssociationsRequestRequestTypeDef",
     {
-        "FindingIdentifiers": Sequence[AwsSecurityFindingIdentifierTypeDef],
+        "StandardsControlAssociationUpdates": Sequence[StandardsControlAssociationUpdateTypeDef],
     },
 )
-_OptionalBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
-    "_OptionalBatchUpdateFindingsRequestRequestTypeDef",
+
+_RequiredUnprocessedStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_RequiredUnprocessedStandardsControlAssociationUpdateTypeDef",
     {
-        "Note": NoteUpdateTypeDef,
-        "Severity": SeverityUpdateTypeDef,
-        "VerificationState": VerificationStateType,
-        "Confidence": int,
-        "Criticality": int,
-        "Types": Sequence[str],
-        "UserDefinedFields": Mapping[str, str],
-        "Workflow": WorkflowUpdateTypeDef,
-        "RelatedFindings": Sequence[RelatedFindingTypeDef],
+        "StandardsControlAssociationUpdate": StandardsControlAssociationUpdateTypeDef,
+        "ErrorCode": UnprocessedErrorCodeType,
+    },
+)
+_OptionalUnprocessedStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_OptionalUnprocessedStandardsControlAssociationUpdateTypeDef",
+    {
+        "ErrorReason": str,
     },
     total=False,
 )
 
-
-class BatchUpdateFindingsRequestRequestTypeDef(
-    _RequiredBatchUpdateFindingsRequestRequestTypeDef,
-    _OptionalBatchUpdateFindingsRequestRequestTypeDef,
+class UnprocessedStandardsControlAssociationUpdateTypeDef(
+    _RequiredUnprocessedStandardsControlAssociationUpdateTypeDef,
+    _OptionalUnprocessedStandardsControlAssociationUpdateTypeDef,
 ):
     pass
 
-
 ComplianceTypeDef = TypedDict(
     "ComplianceTypeDef",
     {
         "Status": ComplianceStatusType,
         "RelatedRequirements": Sequence[str],
         "StatusReasons": Sequence[StatusReasonTypeDef],
         "SecurityControlId": str,
@@ -6081,182 +6983,75 @@
     total=False,
 )
 
 CreateMembersResponseTypeDef = TypedDict(
     "CreateMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineInvitationsResponseTypeDef = TypedDict(
     "DeclineInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInvitationsResponseTypeDef = TypedDict(
     "DeleteInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMembersResponseTypeDef = TypedDict(
     "DeleteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteMembersResponseTypeDef = TypedDict(
     "InviteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DateFilterTypeDef = TypedDict(
     "DateFilterTypeDef",
     {
         "Start": str,
         "End": str,
         "DateRange": DateRangeTypeDef,
     },
     total=False,
 )
 
-DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef = TypedDict(
-    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
-    {
-        "ActionTargetArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeProductsRequestDescribeProductsPaginateTypeDef = TypedDict(
-    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
-    {
-        "ProductArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
-    {
-        "StandardsSubscriptionArn": str,
-    },
-)
-_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef(
-    _RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
-    _OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
-):
-    pass
-
-
-DescribeStandardsRequestDescribeStandardsPaginateTypeDef = TypedDict(
-    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef = TypedDict(
-    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
-    {
-        "StandardsSubscriptionArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetInsightsRequestGetInsightsPaginateTypeDef = TypedDict(
-    "GetInsightsRequestGetInsightsPaginateTypeDef",
-    {
-        "InsightArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef = TypedDict(
-    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef = TypedDict(
-    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
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
-ListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "ListMembersRequestListMembersPaginateTypeDef",
-    {
-        "OnlyAssociated": bool,
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
 DescribeProductsResponseTypeDef = TypedDict(
     "DescribeProductsResponseTypeDef",
     {
         "Products": List[ProductTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStandardsControlsResponseTypeDef = TypedDict(
     "DescribeStandardsControlsResponseTypeDef",
     {
         "Controls": List[StandardsControlTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ThreatTypeDef = TypedDict(
     "ThreatTypeDef",
     {
         "Name": str,
@@ -6268,16 +7063,29 @@
 )
 
 ListFindingAggregatorsResponseTypeDef = TypedDict(
     "ListFindingAggregatorsResponseTypeDef",
     {
         "FindingAggregators": List[FindingAggregatorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+FindingHistoryRecordTypeDef = TypedDict(
+    "FindingHistoryRecordTypeDef",
+    {
+        "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
+        "UpdateTime": datetime,
+        "FindingCreated": bool,
+        "UpdateSource": FindingHistoryUpdateSourceTypeDef,
+        "Updates": List[FindingHistoryUpdateTypeDef],
+        "NextToken": str,
     },
+    total=False,
 )
 
 FindingProviderFieldsTypeDef = TypedDict(
     "FindingProviderFieldsTypeDef",
     {
         "Confidence": int,
         "Criticality": int,
@@ -6288,62 +7096,80 @@
     total=False,
 )
 
 GetAdministratorAccountResponseTypeDef = TypedDict(
     "GetAdministratorAccountResponseTypeDef",
     {
         "Administrator": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMasterAccountResponseTypeDef = TypedDict(
     "GetMasterAccountResponseTypeDef",
     {
         "Master": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
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
 
 GetMembersResponseTypeDef = TypedDict(
     "GetMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "UnprocessedAccounts": List[ResultTypeDef],
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
 
 InsightResultsTypeDef = TypedDict(
     "InsightResultsTypeDef",
     {
         "InsightArn": str,
         "GroupByAttribute": str,
         "ResultValues": List[InsightResultValueTypeDef],
     },
 )
 
+ListSecurityControlDefinitionsResponseTypeDef = TypedDict(
+    "ListSecurityControlDefinitionsResponseTypeDef",
+    {
+        "SecurityControlDefinitions": List[SecurityControlDefinitionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStandardsControlAssociationsResponseTypeDef = TypedDict(
+    "ListStandardsControlAssociationsResponseTypeDef",
+    {
+        "StandardsControlAssociationSummaries": List[StandardsControlAssociationSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NetworkPathComponentDetailsTypeDef = TypedDict(
     "NetworkPathComponentDetailsTypeDef",
     {
         "Address": Sequence[str],
         "PortRanges": Sequence[PortRangeTypeDef],
     },
     total=False,
@@ -6445,21 +7271,19 @@
     "_OptionalStandardsSubscriptionTypeDef",
     {
         "StandardsStatusReason": StandardsStatusReasonTypeDef,
     },
     total=False,
 )
 
-
 class StandardsSubscriptionTypeDef(
     _RequiredStandardsSubscriptionTypeDef, _OptionalStandardsSubscriptionTypeDef
 ):
     pass
 
-
 StatelessCustomPublishMetricActionTypeDef = TypedDict(
     "StatelessCustomPublishMetricActionTypeDef",
     {
         "Dimensions": Sequence[StatelessCustomPublishMetricActionDimensionTypeDef],
     },
     total=False,
 )
@@ -6517,18 +7341,84 @@
         "Vendor": VulnerabilityVendorTypeDef,
         "ReferenceUrls": Sequence[str],
         "FixAvailable": VulnerabilityFixAvailableType,
     },
     total=False,
 )
 
-
 class VulnerabilityTypeDef(_RequiredVulnerabilityTypeDef, _OptionalVulnerabilityTypeDef):
     pass
 
+AwsEc2RouteTableDetailsTypeDef = TypedDict(
+    "AwsEc2RouteTableDetailsTypeDef",
+    {
+        "AssociationSet": Sequence[AssociationSetDetailsTypeDef],
+        "OwnerId": str,
+        "PropagatingVgwSet": Sequence[PropagatingVgwSetDetailsTypeDef],
+        "RouteTableId": str,
+        "RouteSet": Sequence[RouteSetDetailsTypeDef],
+        "VpcId": str,
+    },
+    total=False,
+)
+
+AutomationRulesActionTypeDef = TypedDict(
+    "AutomationRulesActionTypeDef",
+    {
+        "Type": Literal["FINDING_FIELDS_UPDATE"],
+        "FindingFieldsUpdate": AutomationRulesFindingFieldsUpdateTypeDef,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerDetailsTypeDef",
+    {
+        "AuthenticationStrategy": str,
+        "AutoMinorVersionUpgrade": bool,
+        "BrokerArn": str,
+        "BrokerName": str,
+        "DeploymentMode": str,
+        "EncryptionOptions": AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef,
+        "EngineType": str,
+        "EngineVersion": str,
+        "HostInstanceType": str,
+        "BrokerId": str,
+        "LdapServerMetadata": AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef,
+        "Logs": AwsAmazonMqBrokerLogsDetailsTypeDef,
+        "MaintenanceWindowStartTime": AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef,
+        "PubliclyAccessible": bool,
+        "SecurityGroups": Sequence[str],
+        "StorageType": str,
+        "SubnetIds": Sequence[str],
+        "Users": Sequence[AwsAmazonMqBrokerUsersDetailsTypeDef],
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiDetailsTypeDef",
+    {
+        "ApiId": str,
+        "Id": str,
+        "OpenIdConnectConfig": AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef,
+        "Name": str,
+        "LambdaAuthorizerConfig": AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef,
+        "XrayEnabled": bool,
+        "Arn": str,
+        "UserPoolConfig": AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef,
+        "AuthenticationType": str,
+        "LogConfig": AwsAppSyncGraphQlApiLogConfigDetailsTypeDef,
+        "AdditionalAuthenticationProviders": Sequence[
+            AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef
+        ],
+        "WafWebAclArn": str,
+    },
+    total=False,
+)
 
 AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef = TypedDict(
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef",
     {
         "InstancesDistribution": (
             AwsAutoScalingAutoScalingGroupMixedInstancesPolicyInstancesDistributionDetailsTypeDef
         ),
@@ -6943,14 +7833,23 @@
         "SourceSecurityGroup": AwsElbLoadBalancerSourceSecurityGroupTypeDef,
         "Subnets": Sequence[str],
         "VpcId": str,
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef",
+    {
+        "ScanEc2InstanceWithFindings": AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef,
+        "ServiceRole": str,
+    },
+    total=False,
+)
+
 AwsIamAccessKeyDetailsTypeDef = TypedDict(
     "AwsIamAccessKeyDetailsTypeDef",
     {
         "UserName": str,
         "Status": AwsIamAccessKeyStatusType,
         "CreatedAt": str,
         "PrincipalId": str,
@@ -7112,14 +8011,23 @@
     "AwsS3BucketNotificationConfigurationFilterTypeDef",
     {
         "S3KeyFilter": AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef,
     },
     total=False,
 )
 
+AwsS3BucketObjectLockConfigurationTypeDef = TypedDict(
+    "AwsS3BucketObjectLockConfigurationTypeDef",
+    {
+        "ObjectLockEnabled": str,
+        "Rule": AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsS3BucketServerSideEncryptionConfigurationTypeDef = TypedDict(
     "AwsS3BucketServerSideEncryptionConfigurationTypeDef",
     {
         "Rules": Sequence[AwsS3BucketServerSideEncryptionRuleTypeDef],
     },
     total=False,
 )
@@ -7136,26 +8044,38 @@
 )
 
 BatchUpdateFindingsResponseTypeDef = TypedDict(
     "BatchUpdateFindingsResponseTypeDef",
     {
         "ProcessedFindings": List[AwsSecurityFindingIdentifierTypeDef],
         "UnprocessedFindings": List[BatchUpdateFindingsUnprocessedFindingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsSsmPatchComplianceDetailsTypeDef = TypedDict(
     "AwsSsmPatchComplianceDetailsTypeDef",
     {
         "Patch": AwsSsmPatchTypeDef,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef",
+    {
+        "Destinations": Sequence[
+            AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef
+        ],
+        "IncludeExecutionData": bool,
+        "Level": str,
+    },
+    total=False,
+)
+
 AwsWafRegionalRuleGroupDetailsTypeDef = TypedDict(
     "AwsWafRegionalRuleGroupDetailsTypeDef",
     {
         "MetricName": str,
         "Name": str,
         "RuleGroupId": str,
         "Rules": Sequence[AwsWafRegionalRuleGroupRulesDetailsTypeDef],
@@ -7225,14 +8145,73 @@
     "AwsWafv2ActionBlockDetailsTypeDef",
     {
         "CustomResponse": AwsWafv2CustomResponseDetailsTypeDef,
     },
     total=False,
 )
 
+BatchGetStandardsControlAssociationsResponseTypeDef = TypedDict(
+    "BatchGetStandardsControlAssociationsResponseTypeDef",
+    {
+        "StandardsControlAssociationDetails": List[StandardsControlAssociationDetailTypeDef],
+        "UnprocessedAssociations": List[UnprocessedStandardsControlAssociationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchUpdateStandardsControlAssociationsResponseTypeDef = TypedDict(
+    "BatchUpdateStandardsControlAssociationsResponseTypeDef",
+    {
+        "UnprocessedAssociationUpdates": List[UnprocessedStandardsControlAssociationUpdateTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AutomationRulesFindingFiltersTypeDef = TypedDict(
+    "AutomationRulesFindingFiltersTypeDef",
+    {
+        "ProductArn": List[StringFilterTypeDef],
+        "AwsAccountId": List[StringFilterTypeDef],
+        "Id": List[StringFilterTypeDef],
+        "GeneratorId": List[StringFilterTypeDef],
+        "Type": List[StringFilterTypeDef],
+        "FirstObservedAt": List[DateFilterTypeDef],
+        "LastObservedAt": List[DateFilterTypeDef],
+        "CreatedAt": List[DateFilterTypeDef],
+        "UpdatedAt": List[DateFilterTypeDef],
+        "Confidence": List[NumberFilterTypeDef],
+        "Criticality": List[NumberFilterTypeDef],
+        "Title": List[StringFilterTypeDef],
+        "Description": List[StringFilterTypeDef],
+        "SourceUrl": List[StringFilterTypeDef],
+        "ProductName": List[StringFilterTypeDef],
+        "CompanyName": List[StringFilterTypeDef],
+        "SeverityLabel": List[StringFilterTypeDef],
+        "ResourceType": List[StringFilterTypeDef],
+        "ResourceId": List[StringFilterTypeDef],
+        "ResourcePartition": List[StringFilterTypeDef],
+        "ResourceRegion": List[StringFilterTypeDef],
+        "ResourceTags": List[MapFilterTypeDef],
+        "ResourceDetailsOther": List[MapFilterTypeDef],
+        "ComplianceStatus": List[StringFilterTypeDef],
+        "ComplianceSecurityControlId": List[StringFilterTypeDef],
+        "ComplianceAssociatedStandardsId": List[StringFilterTypeDef],
+        "VerificationState": List[StringFilterTypeDef],
+        "WorkflowStatus": List[StringFilterTypeDef],
+        "RecordState": List[StringFilterTypeDef],
+        "RelatedFindingsProductArn": List[StringFilterTypeDef],
+        "RelatedFindingsId": List[StringFilterTypeDef],
+        "NoteText": List[StringFilterTypeDef],
+        "NoteUpdatedAt": List[DateFilterTypeDef],
+        "NoteUpdatedBy": List[StringFilterTypeDef],
+        "UserDefinedFields": List[MapFilterTypeDef],
+    },
+    total=False,
+)
+
 AwsSecurityFindingFiltersTypeDef = TypedDict(
     "AwsSecurityFindingFiltersTypeDef",
     {
         "ProductArn": Sequence[StringFilterTypeDef],
         "AwsAccountId": Sequence[StringFilterTypeDef],
         "Id": Sequence[StringFilterTypeDef],
         "GeneratorId": Sequence[StringFilterTypeDef],
@@ -7329,19 +8308,28 @@
         "Sample": Sequence[BooleanFilterTypeDef],
         "ComplianceSecurityControlId": Sequence[StringFilterTypeDef],
         "ComplianceAssociatedStandardsId": Sequence[StringFilterTypeDef],
     },
     total=False,
 )
 
+GetFindingHistoryResponseTypeDef = TypedDict(
+    "GetFindingHistoryResponseTypeDef",
+    {
+        "Records": List[FindingHistoryRecordTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInsightResultsResponseTypeDef = TypedDict(
     "GetInsightResultsResponseTypeDef",
     {
         "InsightResults": InsightResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkHeaderTypeDef = TypedDict(
     "NetworkHeaderTypeDef",
     {
         "Protocol": str,
@@ -7373,40 +8361,40 @@
 )
 
 DescribeStandardsResponseTypeDef = TypedDict(
     "DescribeStandardsResponseTypeDef",
     {
         "Standards": List[StandardTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisableStandardsResponseTypeDef = TypedDict(
     "BatchDisableStandardsResponseTypeDef",
     {
         "StandardsSubscriptions": List[StandardsSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEnableStandardsResponseTypeDef = TypedDict(
     "BatchEnableStandardsResponseTypeDef",
     {
         "StandardsSubscriptions": List[StandardsSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnabledStandardsResponseTypeDef = TypedDict(
     "GetEnabledStandardsResponseTypeDef",
     {
         "StandardsSubscriptions": List[StandardsSubscriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StatelessCustomActionDefinitionTypeDef = TypedDict(
     "StatelessCustomActionDefinitionTypeDef",
     {
         "PublishMetricAction": StatelessCustomPublishMetricActionTypeDef,
@@ -7575,14 +8563,27 @@
         "RequiresCompatibilities": Sequence[str],
         "TaskRoleArn": str,
         "Volumes": Sequence[AwsEcsTaskDefinitionVolumesDetailsTypeDef],
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDataSourcesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesDetailsTypeDef",
+    {
+        "CloudTrail": AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef,
+        "DnsLogs": AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef,
+        "FlowLogs": AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef,
+        "Kubernetes": AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef,
+        "MalwareProtection": AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef,
+        "S3Logs": AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsRdsDbInstanceDetailsTypeDef = TypedDict(
     "AwsRdsDbInstanceDetailsTypeDef",
     {
         "AssociatedRoles": Sequence[AwsRdsDbInstanceAssociatedRoleTypeDef],
         "CACertificateIdentifier": str,
         "DBClusterIdentifier": str,
         "DBInstanceIdentifier": str,
@@ -7658,14 +8659,29 @@
         "Filter": AwsS3BucketNotificationConfigurationFilterTypeDef,
         "Destination": str,
         "Type": str,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineDetailsTypeDef",
+    {
+        "Label": str,
+        "LoggingConfiguration": AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef,
+        "Name": str,
+        "RoleArn": str,
+        "StateMachineArn": str,
+        "Status": str,
+        "TracingConfiguration": AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef,
+        "Type": str,
+    },
+    total=False,
+)
+
 AwsWafv2RulesActionDetailsTypeDef = TypedDict(
     "AwsWafv2RulesActionDetailsTypeDef",
     {
         "Allow": AwsWafv2ActionAllowDetailsTypeDef,
         "Block": AwsWafv2ActionBlockDetailsTypeDef,
         "Captcha": AwsWafv2RulesActionCaptchaDetailsTypeDef,
         "Count": AwsWafv2RulesActionCountDetailsTypeDef,
@@ -7678,29 +8694,99 @@
     {
         "Allow": AwsWafv2ActionAllowDetailsTypeDef,
         "Block": AwsWafv2ActionBlockDetailsTypeDef,
     },
     total=False,
 )
 
+AutomationRulesConfigTypeDef = TypedDict(
+    "AutomationRulesConfigTypeDef",
+    {
+        "RuleArn": str,
+        "RuleStatus": RuleStatusType,
+        "RuleOrder": int,
+        "RuleName": str,
+        "Description": str,
+        "IsTerminal": bool,
+        "Criteria": AutomationRulesFindingFiltersTypeDef,
+        "Actions": List[AutomationRulesActionTypeDef],
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "CreatedBy": str,
+    },
+    total=False,
+)
+
+_RequiredCreateAutomationRuleRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateAutomationRuleRequestRequestTypeDef",
+    {
+        "RuleOrder": int,
+        "RuleName": str,
+        "Description": str,
+        "Criteria": AutomationRulesFindingFiltersTypeDef,
+        "Actions": Sequence[AutomationRulesActionTypeDef],
+    },
+)
+_OptionalCreateAutomationRuleRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateAutomationRuleRequestRequestTypeDef",
+    {
+        "Tags": Mapping[str, str],
+        "RuleStatus": RuleStatusType,
+        "IsTerminal": bool,
+    },
+    total=False,
+)
+
+class CreateAutomationRuleRequestRequestTypeDef(
+    _RequiredCreateAutomationRuleRequestRequestTypeDef,
+    _OptionalCreateAutomationRuleRequestRequestTypeDef,
+):
+    pass
+
+_RequiredUpdateAutomationRulesRequestItemTypeDef = TypedDict(
+    "_RequiredUpdateAutomationRulesRequestItemTypeDef",
+    {
+        "RuleArn": str,
+    },
+)
+_OptionalUpdateAutomationRulesRequestItemTypeDef = TypedDict(
+    "_OptionalUpdateAutomationRulesRequestItemTypeDef",
+    {
+        "RuleStatus": RuleStatusType,
+        "RuleOrder": int,
+        "Description": str,
+        "RuleName": str,
+        "IsTerminal": bool,
+        "Criteria": AutomationRulesFindingFiltersTypeDef,
+        "Actions": Sequence[AutomationRulesActionTypeDef],
+    },
+    total=False,
+)
+
+class UpdateAutomationRulesRequestItemTypeDef(
+    _RequiredUpdateAutomationRulesRequestItemTypeDef,
+    _OptionalUpdateAutomationRulesRequestItemTypeDef,
+):
+    pass
+
 CreateInsightRequestRequestTypeDef = TypedDict(
     "CreateInsightRequestRequestTypeDef",
     {
         "Name": str,
         "Filters": AwsSecurityFindingFiltersTypeDef,
         "GroupByAttribute": str,
     },
 )
 
 GetFindingsRequestGetFindingsPaginateTypeDef = TypedDict(
     "GetFindingsRequestGetFindingsPaginateTypeDef",
     {
         "Filters": AwsSecurityFindingFiltersTypeDef,
         "SortCriteria": Sequence[SortCriterionTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetFindingsRequestRequestTypeDef = TypedDict(
     "GetFindingsRequestRequestTypeDef",
     {
@@ -7733,21 +8819,19 @@
     {
         "Note": NoteUpdateTypeDef,
         "RecordState": RecordStateType,
     },
     total=False,
 )
 
-
 class UpdateFindingsRequestRequestTypeDef(
     _RequiredUpdateFindingsRequestRequestTypeDef, _OptionalUpdateFindingsRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateInsightRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateInsightRequestRequestTypeDef",
     {
         "InsightArn": str,
     },
 )
 _OptionalUpdateInsightRequestRequestTypeDef = TypedDict(
@@ -7756,21 +8840,19 @@
         "Name": str,
         "Filters": AwsSecurityFindingFiltersTypeDef,
         "GroupByAttribute": str,
     },
     total=False,
 )
 
-
 class UpdateInsightRequestRequestTypeDef(
     _RequiredUpdateInsightRequestRequestTypeDef, _OptionalUpdateInsightRequestRequestTypeDef
 ):
     pass
 
-
 NetworkPathComponentTypeDef = TypedDict(
     "NetworkPathComponentTypeDef",
     {
         "ComponentId": str,
         "ComponentType": str,
         "Egress": NetworkHeaderTypeDef,
         "Ingress": NetworkHeaderTypeDef,
@@ -7864,14 +8946,26 @@
         "ViewerCertificate": AwsCloudFrontDistributionViewerCertificateTypeDef,
         "Status": str,
         "WebAclId": str,
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDetailsTypeDef",
+    {
+        "DataSources": AwsGuardDutyDetectorDataSourcesDetailsTypeDef,
+        "Features": Sequence[AwsGuardDutyDetectorFeaturesDetailsTypeDef],
+        "FindingPublishingFrequency": str,
+        "ServiceRole": str,
+        "Status": str,
+    },
+    total=False,
+)
+
 AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef = TypedDict(
     "AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef",
     {
         "AbortIncompleteMultipartUpload": (
             AwsS3BucketBucketLifecycleConfigurationRulesAbortIncompleteMultipartUploadDetailsTypeDef
         ),
         "ExpirationDate": str,
@@ -7908,20 +9002,36 @@
         "OverrideAction": str,
         "Priority": int,
         "VisibilityConfig": AwsWafv2VisibilityConfigDetailsTypeDef,
     },
     total=False,
 )
 
+BatchGetAutomationRulesResponseTypeDef = TypedDict(
+    "BatchGetAutomationRulesResponseTypeDef",
+    {
+        "Rules": List[AutomationRulesConfigTypeDef],
+        "UnprocessedAutomationRules": List[UnprocessedAutomationRuleTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchUpdateAutomationRulesRequestRequestTypeDef = TypedDict(
+    "BatchUpdateAutomationRulesRequestRequestTypeDef",
+    {
+        "UpdateAutomationRulesRequestItems": Sequence[UpdateAutomationRulesRequestItemTypeDef],
+    },
+)
+
 GetInsightsResponseTypeDef = TypedDict(
     "GetInsightsResponseTypeDef",
     {
         "Insights": List[InsightTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomDataIdentifiersResultTypeDef = TypedDict(
     "CustomDataIdentifiersResultTypeDef",
     {
         "Detections": Sequence[CustomDataIdentifiersDetectionsTypeDef],
@@ -8054,14 +9164,15 @@
         "BucketLifecycleConfiguration": AwsS3BucketBucketLifecycleConfigurationDetailsTypeDef,
         "PublicAccessBlockConfiguration": AwsS3AccountPublicAccessBlockDetailsTypeDef,
         "AccessControlList": str,
         "BucketLoggingConfiguration": AwsS3BucketLoggingConfigurationTypeDef,
         "BucketWebsiteConfiguration": AwsS3BucketWebsiteConfigurationTypeDef,
         "BucketNotificationConfiguration": AwsS3BucketNotificationConfigurationTypeDef,
         "BucketVersioningConfiguration": AwsS3BucketBucketVersioningConfigurationTypeDef,
+        "ObjectLockConfiguration": AwsS3BucketObjectLockConfigurationTypeDef,
     },
     total=False,
 )
 
 DataClassificationDetailsTypeDef = TypedDict(
     "DataClassificationDetailsTypeDef",
     {
@@ -8176,14 +9287,20 @@
         "AwsBackupBackupVault": AwsBackupBackupVaultDetailsTypeDef,
         "AwsBackupBackupPlan": AwsBackupBackupPlanDetailsTypeDef,
         "AwsBackupRecoveryPoint": AwsBackupRecoveryPointDetailsTypeDef,
         "AwsEc2LaunchTemplate": AwsEc2LaunchTemplateDetailsTypeDef,
         "AwsSageMakerNotebookInstance": AwsSageMakerNotebookInstanceDetailsTypeDef,
         "AwsWafv2WebAcl": AwsWafv2WebAclDetailsTypeDef,
         "AwsWafv2RuleGroup": AwsWafv2RuleGroupDetailsTypeDef,
+        "AwsEc2RouteTable": AwsEc2RouteTableDetailsTypeDef,
+        "AwsAmazonMqBroker": AwsAmazonMqBrokerDetailsTypeDef,
+        "AwsAppSyncGraphQlApi": AwsAppSyncGraphQlApiDetailsTypeDef,
+        "AwsEventSchemasRegistry": AwsEventSchemasRegistryDetailsTypeDef,
+        "AwsGuardDutyDetector": AwsGuardDutyDetectorDetailsTypeDef,
+        "AwsStepFunctionStateMachine": AwsStepFunctionStateMachineDetailsTypeDef,
     },
     total=False,
 )
 
 _RequiredResourceTypeDef = TypedDict(
     "_RequiredResourceTypeDef",
     {
@@ -8200,19 +9317,17 @@
         "Tags": Mapping[str, str],
         "DataClassification": DataClassificationDetailsTypeDef,
         "Details": ResourceDetailsTypeDef,
     },
     total=False,
 )
 
-
 class ResourceTypeDef(_RequiredResourceTypeDef, _OptionalResourceTypeDef):
     pass
 
-
 _RequiredAwsSecurityFindingTypeDef = TypedDict(
     "_RequiredAwsSecurityFindingTypeDef",
     {
         "SchemaVersion": str,
         "Id": str,
         "ProductArn": str,
         "GeneratorId": str,
@@ -8258,29 +9373,27 @@
         "Action": ActionTypeDef,
         "FindingProviderFields": FindingProviderFieldsTypeDef,
         "Sample": bool,
     },
     total=False,
 )
 
-
 class AwsSecurityFindingTypeDef(
     _RequiredAwsSecurityFindingTypeDef, _OptionalAwsSecurityFindingTypeDef
 ):
     pass
 
-
 BatchImportFindingsRequestRequestTypeDef = TypedDict(
     "BatchImportFindingsRequestRequestTypeDef",
     {
         "Findings": Sequence[AwsSecurityFindingTypeDef],
     },
 )
 
 GetFindingsResponseTypeDef = TypedDict(
     "GetFindingsResponseTypeDef",
     {
         "Findings": List[AwsSecurityFindingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub/type_defs.pyi` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub/type_defs.py`

 * *Files 8% similar despite different names*

```diff
@@ -9,38 +9,44 @@
     from types_aiobotocore_securityhub.type_defs import AcceptAdministratorInvitationRequestRequestTypeDef
 
     data: AcceptAdministratorInvitationRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence
+from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AdminStatusType,
+    AssociationStatusType,
     AutoEnableStandardsType,
     AwsIamAccessKeyStatusType,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType,
     ComplianceStatusType,
+    ControlFindingGeneratorType,
     ControlStatusType,
+    FindingHistoryUpdateSourceTypeType,
     IntegrationTypeType,
     MalwareStateType,
     MalwareTypeType,
     MapFilterComparisonType,
     NetworkDirectionType,
     PartitionType,
     RecordStateType,
+    RegionAvailabilityStatusType,
+    RuleStatusType,
     SeverityLabelType,
     SeverityRatingType,
     SortOrderType,
     StandardsStatusType,
     StatusReasonCodeType,
     StringFilterComparisonType,
     ThreatIntelIndicatorCategoryType,
     ThreatIntelIndicatorTypeType,
+    UnprocessedErrorCodeType,
     VerificationStateType,
     VulnerabilityFixAvailableType,
     WorkflowStateType,
     WorkflowStatusType,
 )
 
 if sys.version_info >= (3, 9):
@@ -48,14 +54,15 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AcceptAdministratorInvitationRequestRequestTypeDef",
     "AcceptInvitationRequestRequestTypeDef",
     "AccountDetailsTypeDef",
     "ActionLocalIpDetailsTypeDef",
     "ActionLocalPortDetailsTypeDef",
     "CityTypeDef",
@@ -64,22 +71,40 @@
     "IpOrganizationDetailsTypeDef",
     "ActionRemotePortDetailsTypeDef",
     "ActionTargetTypeDef",
     "DnsRequestActionTypeDef",
     "AdjustmentTypeDef",
     "AdminAccountTypeDef",
     "AssociatedStandardTypeDef",
+    "AssociationStateDetailsTypeDef",
+    "NoteUpdateTypeDef",
+    "RelatedFindingTypeDef",
+    "SeverityUpdateTypeDef",
+    "WorkflowUpdateTypeDef",
+    "MapFilterTypeDef",
+    "NumberFilterTypeDef",
+    "StringFilterTypeDef",
+    "AutomationRulesMetadataTypeDef",
     "AvailabilityZoneTypeDef",
+    "AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef",
+    "AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef",
+    "AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef",
+    "AwsAmazonMqBrokerUsersDetailsTypeDef",
+    "AwsAmazonMqBrokerLogsPendingDetailsTypeDef",
     "AwsApiCallActionDomainDetailsTypeDef",
     "AwsApiGatewayAccessLogSettingsTypeDef",
     "AwsApiGatewayCanarySettingsTypeDef",
     "AwsApiGatewayEndpointConfigurationTypeDef",
     "AwsApiGatewayMethodSettingsTypeDef",
     "AwsCorsConfigurationTypeDef",
     "AwsApiGatewayV2RouteSettingsTypeDef",
+    "AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef",
+    "AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef",
+    "AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef",
+    "AwsAppSyncGraphQlApiLogConfigDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupLaunchTemplateLaunchTemplateSpecificationTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyInstancesDistributionDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateLaunchTemplateSpecificationTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateOverridesListDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationBlockDeviceMappingsEbsDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationInstanceMonitoringDetailsTypeDef",
@@ -119,14 +144,15 @@
     "AwsDynamoDbTableRestoreSummaryTypeDef",
     "AwsDynamoDbTableSseDescriptionTypeDef",
     "AwsDynamoDbTableStreamSpecificationTypeDef",
     "AwsDynamoDbTableProjectionTypeDef",
     "AwsDynamoDbTableProvisionedThroughputOverrideTypeDef",
     "AwsEc2EipDetailsTypeDef",
     "AwsEc2InstanceMetadataOptionsTypeDef",
+    "AwsEc2InstanceMonitoringDetailsTypeDef",
     "AwsEc2InstanceNetworkInterfacesDetailsTypeDef",
     "AwsEc2LaunchTemplateDataBlockDeviceMappingSetEbsDetailsTypeDef",
     "AwsEc2LaunchTemplateDataCapacityReservationSpecificationCapacityReservationTargetDetailsTypeDef",
     "AwsEc2LaunchTemplateDataCpuOptionsDetailsTypeDef",
     "AwsEc2LaunchTemplateDataCreditSpecificationDetailsTypeDef",
     "AwsEc2LaunchTemplateDataElasticGpuSpecificationSetDetailsTypeDef",
     "AwsEc2LaunchTemplateDataElasticInferenceAcceleratorSetDetailsTypeDef",
@@ -155,14 +181,16 @@
     "AwsEc2NetworkAclAssociationTypeDef",
     "IcmpTypeCodeTypeDef",
     "PortRangeFromToTypeDef",
     "AwsEc2NetworkInterfaceAttachmentTypeDef",
     "AwsEc2NetworkInterfaceIpV6AddressDetailTypeDef",
     "AwsEc2NetworkInterfacePrivateIpAddressDetailTypeDef",
     "AwsEc2NetworkInterfaceSecurityGroupTypeDef",
+    "PropagatingVgwSetDetailsTypeDef",
+    "RouteSetDetailsTypeDef",
     "AwsEc2SecurityGroupIpRangeTypeDef",
     "AwsEc2SecurityGroupIpv6RangeTypeDef",
     "AwsEc2SecurityGroupPrefixListIdTypeDef",
     "AwsEc2SecurityGroupUserIdGroupPairTypeDef",
     "Ipv6CidrBlockAssociationTypeDef",
     "AwsEc2TransitGatewayDetailsTypeDef",
     "AwsEc2VolumeAttachmentTypeDef",
@@ -239,14 +267,22 @@
     "AwsElbLoadBalancerBackendServerDescriptionTypeDef",
     "AwsElbLoadBalancerHealthCheckTypeDef",
     "AwsElbLoadBalancerInstanceTypeDef",
     "AwsElbLoadBalancerSourceSecurityGroupTypeDef",
     "AwsElbLoadBalancerListenerTypeDef",
     "AwsElbv2LoadBalancerAttributeTypeDef",
     "LoadBalancerStateTypeDef",
+    "AwsEventSchemasRegistryDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef",
+    "AwsGuardDutyDetectorFeaturesDetailsTypeDef",
     "AwsIamAccessKeySessionContextAttributesTypeDef",
     "AwsIamAccessKeySessionContextSessionIssuerTypeDef",
     "AwsIamAttachedManagedPolicyTypeDef",
     "AwsIamGroupPolicyTypeDef",
     "AwsIamInstanceProfileRoleTypeDef",
     "AwsIamPermissionsBoundaryTypeDef",
     "AwsIamPolicyVersionTypeDef",
@@ -306,39 +342,38 @@
     "AwsS3BucketBucketLifecycleConfigurationRulesNoncurrentVersionTransitionsDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesTransitionsDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateTagDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsTagDetailsTypeDef",
     "AwsS3BucketBucketVersioningConfigurationTypeDef",
     "AwsS3BucketLoggingConfigurationTypeDef",
     "AwsS3BucketNotificationConfigurationS3KeyFilterRuleTypeDef",
+    "AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef",
     "AwsS3BucketServerSideEncryptionByDefaultTypeDef",
     "AwsS3BucketWebsiteConfigurationRedirectToTypeDef",
     "AwsS3BucketWebsiteConfigurationRoutingRuleConditionTypeDef",
     "AwsS3BucketWebsiteConfigurationRoutingRuleRedirectTypeDef",
     "AwsS3ObjectDetailsTypeDef",
     "AwsSageMakerNotebookInstanceMetadataServiceConfigurationDetailsTypeDef",
     "AwsSecretsManagerSecretRotationRulesTypeDef",
     "BooleanFilterTypeDef",
     "IpFilterTypeDef",
     "KeywordFilterTypeDef",
-    "MapFilterTypeDef",
-    "NumberFilterTypeDef",
-    "StringFilterTypeDef",
     "AwsSecurityFindingIdentifierTypeDef",
     "MalwareTypeDef",
     "NoteTypeDef",
     "PatchSummaryTypeDef",
     "ProcessDetailsTypeDef",
-    "RelatedFindingTypeDef",
     "SeverityTypeDef",
     "ThreatIntelIndicatorTypeDef",
     "WorkflowTypeDef",
     "AwsSnsTopicSubscriptionTypeDef",
     "AwsSqsQueueDetailsTypeDef",
     "AwsSsmComplianceSummaryTypeDef",
+    "AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef",
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef",
     "AwsWafRateBasedRuleMatchPredicateTypeDef",
     "AwsWafRegionalRateBasedRuleMatchPredicateTypeDef",
     "AwsWafRegionalRulePredicateListDetailsTypeDef",
     "AwsWafRegionalRuleGroupRulesActionDetailsTypeDef",
     "AwsWafRegionalWebAclRulesListActionDetailsTypeDef",
     "AwsWafRegionalWebAclRulesListOverrideActionDetailsTypeDef",
     "AwsWafRulePredicateListDetailsTypeDef",
@@ -346,74 +381,113 @@
     "WafActionTypeDef",
     "WafExcludedRuleTypeDef",
     "WafOverrideActionTypeDef",
     "AwsWafv2CustomHttpHeaderTypeDef",
     "AwsWafv2VisibilityConfigDetailsTypeDef",
     "AwsWafv2WebAclCaptchaConfigImmunityTimePropertyDetailsTypeDef",
     "AwsXrayEncryptionConfigDetailsTypeDef",
+    "BatchDeleteAutomationRulesRequestRequestTypeDef",
+    "UnprocessedAutomationRuleTypeDef",
     "BatchDisableStandardsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "StandardsSubscriptionRequestTypeDef",
+    "BatchGetAutomationRulesRequestRequestTypeDef",
+    "BatchGetSecurityControlsRequestRequestTypeDef",
+    "SecurityControlTypeDef",
+    "UnprocessedSecurityControlTypeDef",
+    "StandardsControlAssociationIdTypeDef",
+    "StandardsControlAssociationDetailTypeDef",
     "ImportFindingsErrorTypeDef",
-    "NoteUpdateTypeDef",
-    "SeverityUpdateTypeDef",
-    "WorkflowUpdateTypeDef",
+    "StandardsControlAssociationUpdateTypeDef",
     "CellTypeDef",
     "ClassificationStatusTypeDef",
     "StatusReasonTypeDef",
     "VolumeMountTypeDef",
     "CreateActionTargetRequestRequestTypeDef",
+    "CreateActionTargetResponseTypeDef",
+    "CreateAutomationRuleResponseTypeDef",
     "CreateFindingAggregatorRequestRequestTypeDef",
+    "CreateFindingAggregatorResponseTypeDef",
+    "CreateInsightResponseTypeDef",
     "ResultTypeDef",
     "DateRangeTypeDef",
     "DeclineInvitationsRequestRequestTypeDef",
     "DeleteActionTargetRequestRequestTypeDef",
+    "DeleteActionTargetResponseTypeDef",
     "DeleteFindingAggregatorRequestRequestTypeDef",
     "DeleteInsightRequestRequestTypeDef",
+    "DeleteInsightResponseTypeDef",
     "DeleteInvitationsRequestRequestTypeDef",
     "DeleteMembersRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
     "DescribeActionTargetsRequestRequestTypeDef",
     "DescribeHubRequestRequestTypeDef",
+    "DescribeHubResponseTypeDef",
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
     "DescribeProductsRequestRequestTypeDef",
     "ProductTypeDef",
+    "DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
     "DescribeStandardsControlsRequestRequestTypeDef",
     "StandardsControlTypeDef",
+    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
     "DescribeStandardsRequestRequestTypeDef",
     "DisableImportFindingsForProductRequestRequestTypeDef",
     "DisableOrganizationAdminAccountRequestRequestTypeDef",
     "DisassociateMembersRequestRequestTypeDef",
     "EnableImportFindingsForProductRequestRequestTypeDef",
+    "EnableImportFindingsForProductResponseTypeDef",
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     "EnableSecurityHubRequestRequestTypeDef",
     "FilePathsTypeDef",
     "FindingAggregatorTypeDef",
+    "FindingHistoryUpdateSourceTypeDef",
+    "FindingHistoryUpdateTypeDef",
     "FindingProviderSeverityTypeDef",
     "FirewallPolicyStatefulRuleGroupReferencesDetailsTypeDef",
     "FirewallPolicyStatelessRuleGroupReferencesDetailsTypeDef",
     "InvitationTypeDef",
+    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
     "GetEnabledStandardsRequestRequestTypeDef",
     "GetFindingAggregatorRequestRequestTypeDef",
+    "GetFindingAggregatorResponseTypeDef",
     "SortCriterionTypeDef",
     "GetInsightResultsRequestRequestTypeDef",
+    "GetInsightsRequestGetInsightsPaginateTypeDef",
     "GetInsightsRequestRequestTypeDef",
+    "GetInvitationsCountResponseTypeDef",
     "GetMembersRequestRequestTypeDef",
     "MemberTypeDef",
     "InsightResultValueTypeDef",
     "InviteMembersRequestRequestTypeDef",
+    "ListAutomationRulesRequestRequestTypeDef",
+    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
     "ListEnabledProductsForImportRequestRequestTypeDef",
+    "ListEnabledProductsForImportResponseTypeDef",
+    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
     "ListFindingAggregatorsRequestRequestTypeDef",
+    "ListInvitationsRequestListInvitationsPaginateTypeDef",
     "ListInvitationsRequestRequestTypeDef",
+    "ListMembersRequestListMembersPaginateTypeDef",
     "ListMembersRequestRequestTypeDef",
+    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "ListOrganizationAdminAccountsRequestRequestTypeDef",
+    "ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef",
+    "ListSecurityControlDefinitionsRequestRequestTypeDef",
+    "SecurityControlDefinitionTypeDef",
+    "ListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef",
+    "ListStandardsControlAssociationsRequestRequestTypeDef",
+    "StandardsControlAssociationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "PortRangeTypeDef",
     "RangeTypeDef",
     "RecordTypeDef",
+    "PaginatorConfigTypeDef",
     "RecommendationTypeDef",
+    "ResponseMetadataTypeDef",
     "RuleGroupSourceListDetailsTypeDef",
     "RuleGroupSourceStatefulRulesHeaderDetailsTypeDef",
     "RuleGroupSourceStatefulRulesOptionsDetailsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesDestinationPortsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesDestinationsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesSourcePortsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesSourcesTypeDef",
@@ -424,25 +498,33 @@
     "StandardsManagedByTypeDef",
     "StandardsStatusReasonTypeDef",
     "StatelessCustomPublishMetricActionDimensionTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateActionTargetRequestRequestTypeDef",
     "UpdateFindingAggregatorRequestRequestTypeDef",
+    "UpdateFindingAggregatorResponseTypeDef",
     "UpdateOrganizationConfigurationRequestRequestTypeDef",
     "UpdateSecurityHubConfigurationRequestRequestTypeDef",
     "UpdateStandardsControlRequestRequestTypeDef",
     "VulnerabilityVendorTypeDef",
     "CreateMembersRequestRequestTypeDef",
     "ActionRemoteIpDetailsTypeDef",
+    "DescribeActionTargetsResponseTypeDef",
     "CvssTypeDef",
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    "AssociationSetDetailsTypeDef",
+    "AutomationRulesFindingFieldsUpdateTypeDef",
+    "ListAutomationRulesResponseTypeDef",
+    "AwsAmazonMqBrokerLogsDetailsTypeDef",
     "AwsApiGatewayRestApiDetailsTypeDef",
     "AwsApiGatewayStageDetailsTypeDef",
     "AwsApiGatewayV2ApiDetailsTypeDef",
     "AwsApiGatewayV2StageDetailsTypeDef",
+    "AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationBlockDeviceMappingsDetailsTypeDef",
     "AwsBackupBackupPlanRuleCopyActionsDetailsTypeDef",
     "AwsBackupBackupVaultDetailsTypeDef",
     "AwsBackupRecoveryPointDetailsTypeDef",
     "AwsCertificateManagerCertificateDomainValidationOptionTypeDef",
     "AwsCloudFormationStackDetailsTypeDef",
@@ -485,14 +567,16 @@
     "AwsElasticBeanstalkEnvironmentDetailsTypeDef",
     "AwsElasticsearchDomainElasticsearchClusterConfigDetailsTypeDef",
     "AwsElasticsearchDomainLogPublishingOptionsTypeDef",
     "AwsElbLoadBalancerPoliciesTypeDef",
     "AwsElbLoadBalancerAttributesTypeDef",
     "AwsElbLoadBalancerListenerDescriptionTypeDef",
     "AwsElbv2LoadBalancerDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef",
     "AwsIamAccessKeySessionContextTypeDef",
     "AwsIamGroupDetailsTypeDef",
     "AwsIamInstanceProfileTypeDef",
     "AwsIamPolicyDetailsTypeDef",
     "AwsIamUserDetailsTypeDef",
     "AwsKinesisStreamDetailsTypeDef",
     "AwsLambdaFunctionEnvironmentTypeDef",
@@ -504,94 +588,86 @@
     "AwsRdsDbSnapshotDetailsTypeDef",
     "AwsRdsDbPendingModifiedValuesTypeDef",
     "AwsRdsDbSecurityGroupDetailsTypeDef",
     "AwsRdsDbSubnetGroupSubnetTypeDef",
     "AwsRedshiftClusterClusterParameterGroupTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef",
+    "AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef",
     "AwsS3BucketServerSideEncryptionRuleTypeDef",
     "AwsS3BucketWebsiteConfigurationRoutingRuleTypeDef",
     "AwsSageMakerNotebookInstanceDetailsTypeDef",
     "AwsSecretsManagerSecretDetailsTypeDef",
+    "BatchUpdateFindingsRequestRequestTypeDef",
     "BatchUpdateFindingsUnprocessedFindingTypeDef",
+    "GetFindingHistoryRequestGetFindingHistoryPaginateTypeDef",
+    "GetFindingHistoryRequestRequestTypeDef",
     "AwsSnsTopicDetailsTypeDef",
     "AwsSsmPatchTypeDef",
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef",
     "AwsWafRateBasedRuleDetailsTypeDef",
     "AwsWafRegionalRateBasedRuleDetailsTypeDef",
     "AwsWafRegionalRuleDetailsTypeDef",
     "AwsWafRegionalRuleGroupRulesDetailsTypeDef",
     "AwsWafRegionalWebAclRulesListDetailsTypeDef",
     "AwsWafRuleDetailsTypeDef",
     "AwsWafRuleGroupRulesDetailsTypeDef",
     "AwsWafWebAclRuleTypeDef",
     "AwsWafv2CustomRequestHandlingDetailsTypeDef",
     "AwsWafv2CustomResponseDetailsTypeDef",
     "AwsWafv2WebAclCaptchaConfigDetailsTypeDef",
-    "CreateActionTargetResponseTypeDef",
-    "CreateFindingAggregatorResponseTypeDef",
-    "CreateInsightResponseTypeDef",
-    "DeleteActionTargetResponseTypeDef",
-    "DeleteInsightResponseTypeDef",
-    "DescribeActionTargetsResponseTypeDef",
-    "DescribeHubResponseTypeDef",
-    "DescribeOrganizationConfigurationResponseTypeDef",
-    "EnableImportFindingsForProductResponseTypeDef",
-    "GetFindingAggregatorResponseTypeDef",
-    "GetInvitationsCountResponseTypeDef",
-    "ListEnabledProductsForImportResponseTypeDef",
-    "ListOrganizationAdminAccountsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UpdateFindingAggregatorResponseTypeDef",
+    "BatchDeleteAutomationRulesResponseTypeDef",
+    "BatchUpdateAutomationRulesResponseTypeDef",
     "BatchEnableStandardsRequestRequestTypeDef",
+    "BatchGetSecurityControlsResponseTypeDef",
+    "BatchGetStandardsControlAssociationsRequestRequestTypeDef",
+    "UnprocessedStandardsControlAssociationTypeDef",
     "BatchImportFindingsResponseTypeDef",
-    "BatchUpdateFindingsRequestRequestTypeDef",
+    "BatchUpdateStandardsControlAssociationsRequestRequestTypeDef",
+    "UnprocessedStandardsControlAssociationUpdateTypeDef",
     "ComplianceTypeDef",
     "ContainerDetailsTypeDef",
     "CreateMembersResponseTypeDef",
     "DeclineInvitationsResponseTypeDef",
     "DeleteInvitationsResponseTypeDef",
     "DeleteMembersResponseTypeDef",
     "InviteMembersResponseTypeDef",
     "DateFilterTypeDef",
-    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
-    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
-    "DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
-    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
-    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
-    "GetInsightsRequestGetInsightsPaginateTypeDef",
-    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
-    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
-    "ListInvitationsRequestListInvitationsPaginateTypeDef",
-    "ListMembersRequestListMembersPaginateTypeDef",
-    "ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef",
     "DescribeProductsResponseTypeDef",
     "DescribeStandardsControlsResponseTypeDef",
     "ThreatTypeDef",
     "ListFindingAggregatorsResponseTypeDef",
+    "FindingHistoryRecordTypeDef",
     "FindingProviderFieldsTypeDef",
     "GetAdministratorAccountResponseTypeDef",
     "GetMasterAccountResponseTypeDef",
     "ListInvitationsResponseTypeDef",
     "GetMembersResponseTypeDef",
     "ListMembersResponseTypeDef",
     "InsightResultsTypeDef",
+    "ListSecurityControlDefinitionsResponseTypeDef",
+    "ListStandardsControlAssociationsResponseTypeDef",
     "NetworkPathComponentDetailsTypeDef",
     "NetworkTypeDef",
     "PageTypeDef",
     "RemediationTypeDef",
     "RuleGroupSourceStatefulRulesDetailsTypeDef",
     "RuleGroupSourceStatelessRuleMatchAttributesTypeDef",
     "RuleGroupVariablesTypeDef",
     "StandardTypeDef",
     "StandardsSubscriptionTypeDef",
     "StatelessCustomPublishMetricActionTypeDef",
     "AwsApiCallActionTypeDef",
     "NetworkConnectionActionTypeDef",
     "PortProbeDetailTypeDef",
     "VulnerabilityTypeDef",
+    "AwsEc2RouteTableDetailsTypeDef",
+    "AutomationRulesActionTypeDef",
+    "AwsAmazonMqBrokerDetailsTypeDef",
+    "AwsAppSyncGraphQlApiDetailsTypeDef",
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef",
     "AwsAutoScalingLaunchConfigurationDetailsTypeDef",
     "AwsBackupBackupPlanRuleDetailsTypeDef",
     "AwsCertificateManagerCertificateRenewalSummaryTypeDef",
     "AwsCloudFrontDistributionOriginItemTypeDef",
     "AwsCloudFrontDistributionOriginGroupTypeDef",
     "AwsCodeBuildProjectDetailsTypeDef",
@@ -606,35 +682,42 @@
     "AwsEcsTaskDefinitionContainerDefinitionsDetailsTypeDef",
     "AwsEcsTaskDefinitionVolumesDetailsTypeDef",
     "AwsEcsTaskDetailsTypeDef",
     "AwsEfsAccessPointDetailsTypeDef",
     "AwsEksClusterDetailsTypeDef",
     "AwsElasticsearchDomainDetailsTypeDef",
     "AwsElbLoadBalancerDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef",
     "AwsIamAccessKeyDetailsTypeDef",
     "AwsIamRoleDetailsTypeDef",
     "AwsLambdaFunctionDetailsTypeDef",
     "AwsOpenSearchServiceDomainDetailsTypeDef",
     "AwsRdsDbSubnetGroupTypeDef",
     "AwsRedshiftClusterDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationFilterTypeDef",
+    "AwsS3BucketObjectLockConfigurationTypeDef",
     "AwsS3BucketServerSideEncryptionConfigurationTypeDef",
     "AwsS3BucketWebsiteConfigurationTypeDef",
     "BatchUpdateFindingsResponseTypeDef",
     "AwsSsmPatchComplianceDetailsTypeDef",
+    "AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef",
     "AwsWafRegionalRuleGroupDetailsTypeDef",
     "AwsWafRegionalWebAclDetailsTypeDef",
     "AwsWafRuleGroupDetailsTypeDef",
     "AwsWafWebAclDetailsTypeDef",
     "AwsWafv2ActionAllowDetailsTypeDef",
     "AwsWafv2RulesActionCaptchaDetailsTypeDef",
     "AwsWafv2RulesActionCountDetailsTypeDef",
     "AwsWafv2ActionBlockDetailsTypeDef",
+    "BatchGetStandardsControlAssociationsResponseTypeDef",
+    "BatchUpdateStandardsControlAssociationsResponseTypeDef",
+    "AutomationRulesFindingFiltersTypeDef",
     "AwsSecurityFindingFiltersTypeDef",
+    "GetFindingHistoryResponseTypeDef",
     "GetInsightResultsResponseTypeDef",
     "NetworkHeaderTypeDef",
     "OccurrencesTypeDef",
     "RuleGroupSourceStatelessRuleDefinitionTypeDef",
     "DescribeStandardsResponseTypeDef",
     "BatchDisableStandardsResponseTypeDef",
     "BatchEnableStandardsResponseTypeDef",
@@ -646,19 +729,24 @@
     "AwsCertificateManagerCertificateDetailsTypeDef",
     "AwsCloudFrontDistributionOriginsTypeDef",
     "AwsCloudFrontDistributionOriginGroupsTypeDef",
     "AwsDynamoDbTableDetailsTypeDef",
     "AwsEc2LaunchTemplateDetailsTypeDef",
     "AwsEcsClusterDetailsTypeDef",
     "AwsEcsTaskDefinitionDetailsTypeDef",
+    "AwsGuardDutyDetectorDataSourcesDetailsTypeDef",
     "AwsRdsDbInstanceDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesFilterDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationDetailTypeDef",
+    "AwsStepFunctionStateMachineDetailsTypeDef",
     "AwsWafv2RulesActionDetailsTypeDef",
     "AwsWafv2WebAclActionDetailsTypeDef",
+    "AutomationRulesConfigTypeDef",
+    "CreateAutomationRuleRequestRequestTypeDef",
+    "UpdateAutomationRulesRequestItemTypeDef",
     "CreateInsightRequestRequestTypeDef",
     "GetFindingsRequestGetFindingsPaginateTypeDef",
     "GetFindingsRequestRequestTypeDef",
     "InsightTypeDef",
     "UpdateFindingsRequestRequestTypeDef",
     "UpdateInsightRequestRequestTypeDef",
     "NetworkPathComponentTypeDef",
@@ -666,17 +754,20 @@
     "SensitiveDataDetectionsTypeDef",
     "RuleGroupSourceStatelessRulesDetailsTypeDef",
     "FirewallPolicyStatelessCustomActionsDetailsTypeDef",
     "RuleGroupSourceCustomActionsDetailsTypeDef",
     "ActionTypeDef",
     "AwsBackupBackupPlanDetailsTypeDef",
     "AwsCloudFrontDistributionDetailsTypeDef",
+    "AwsGuardDutyDetectorDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef",
     "AwsS3BucketNotificationConfigurationTypeDef",
     "AwsWafv2RulesDetailsTypeDef",
+    "BatchGetAutomationRulesResponseTypeDef",
+    "BatchUpdateAutomationRulesRequestRequestTypeDef",
     "GetInsightsResponseTypeDef",
     "CustomDataIdentifiersResultTypeDef",
     "SensitiveDataResultTypeDef",
     "FirewallPolicyDetailsTypeDef",
     "RuleGroupSourceStatelessRulesAndCustomActionsDetailsTypeDef",
     "AwsS3BucketBucketLifecycleConfigurationDetailsTypeDef",
     "AwsWafv2RuleGroupDetailsTypeDef",
@@ -721,17 +812,19 @@
     "_OptionalAccountDetailsTypeDef",
     {
         "Email": str,
     },
     total=False,
 )
 
+
 class AccountDetailsTypeDef(_RequiredAccountDetailsTypeDef, _OptionalAccountDetailsTypeDef):
     pass
 
+
 ActionLocalIpDetailsTypeDef = TypedDict(
     "ActionLocalIpDetailsTypeDef",
     {
         "IpAddressV4": str,
     },
     total=False,
 )
@@ -832,23 +925,165 @@
     "AssociatedStandardTypeDef",
     {
         "StandardsId": str,
     },
     total=False,
 )
 
+AssociationStateDetailsTypeDef = TypedDict(
+    "AssociationStateDetailsTypeDef",
+    {
+        "State": str,
+        "StatusMessage": str,
+    },
+    total=False,
+)
+
+NoteUpdateTypeDef = TypedDict(
+    "NoteUpdateTypeDef",
+    {
+        "Text": str,
+        "UpdatedBy": str,
+    },
+)
+
+RelatedFindingTypeDef = TypedDict(
+    "RelatedFindingTypeDef",
+    {
+        "ProductArn": str,
+        "Id": str,
+    },
+)
+
+SeverityUpdateTypeDef = TypedDict(
+    "SeverityUpdateTypeDef",
+    {
+        "Normalized": int,
+        "Product": float,
+        "Label": SeverityLabelType,
+    },
+    total=False,
+)
+
+WorkflowUpdateTypeDef = TypedDict(
+    "WorkflowUpdateTypeDef",
+    {
+        "Status": WorkflowStatusType,
+    },
+    total=False,
+)
+
+MapFilterTypeDef = TypedDict(
+    "MapFilterTypeDef",
+    {
+        "Key": str,
+        "Value": str,
+        "Comparison": MapFilterComparisonType,
+    },
+    total=False,
+)
+
+NumberFilterTypeDef = TypedDict(
+    "NumberFilterTypeDef",
+    {
+        "Gte": float,
+        "Lte": float,
+        "Eq": float,
+    },
+    total=False,
+)
+
+StringFilterTypeDef = TypedDict(
+    "StringFilterTypeDef",
+    {
+        "Value": str,
+        "Comparison": StringFilterComparisonType,
+    },
+    total=False,
+)
+
+AutomationRulesMetadataTypeDef = TypedDict(
+    "AutomationRulesMetadataTypeDef",
+    {
+        "RuleArn": str,
+        "RuleStatus": RuleStatusType,
+        "RuleOrder": int,
+        "RuleName": str,
+        "Description": str,
+        "IsTerminal": bool,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "CreatedBy": str,
+    },
+    total=False,
+)
+
 AvailabilityZoneTypeDef = TypedDict(
     "AvailabilityZoneTypeDef",
     {
         "ZoneName": str,
         "SubnetId": str,
     },
     total=False,
 )
 
+AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef",
+    {
+        "KmsKeyId": str,
+        "UseAwsOwnedKey": bool,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef",
+    {
+        "Hosts": Sequence[str],
+        "RoleBase": str,
+        "RoleName": str,
+        "RoleSearchMatching": str,
+        "RoleSearchSubtree": bool,
+        "ServiceAccountUsername": str,
+        "UserBase": str,
+        "UserRoleName": str,
+        "UserSearchMatching": str,
+        "UserSearchSubtree": bool,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef",
+    {
+        "DayOfWeek": str,
+        "TimeOfDay": str,
+        "TimeZone": str,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerUsersDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerUsersDetailsTypeDef",
+    {
+        "PendingChange": str,
+        "Username": str,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerLogsPendingDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerLogsPendingDetailsTypeDef",
+    {
+        "Audit": bool,
+        "General": bool,
+    },
+    total=False,
+)
+
 AwsApiCallActionDomainDetailsTypeDef = TypedDict(
     "AwsApiCallActionDomainDetailsTypeDef",
     {
         "Domain": str,
     },
     total=False,
 )
@@ -921,14 +1156,56 @@
         "DataTraceEnabled": bool,
         "ThrottlingBurstLimit": int,
         "ThrottlingRateLimit": float,
     },
     total=False,
 )
 
+AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef",
+    {
+        "AuthorizerResultTtlInSeconds": int,
+        "AuthorizerUri": str,
+        "IdentityValidationExpression": str,
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef",
+    {
+        "AuthTtL": int,
+        "ClientId": str,
+        "IatTtL": int,
+        "Issuer": str,
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef",
+    {
+        "AppIdClientRegex": str,
+        "AwsRegion": str,
+        "DefaultAction": str,
+        "UserPoolId": str,
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiLogConfigDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiLogConfigDetailsTypeDef",
+    {
+        "CloudWatchLogsRoleArn": str,
+        "ExcludeVerboseContent": bool,
+        "FieldLogLevel": str,
+    },
+    total=False,
+)
+
 AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef = TypedDict(
     "AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
@@ -1401,14 +1678,22 @@
         "HttpPutResponseHopLimit": int,
         "HttpTokens": str,
         "InstanceMetadataTags": str,
     },
     total=False,
 )
 
+AwsEc2InstanceMonitoringDetailsTypeDef = TypedDict(
+    "AwsEc2InstanceMonitoringDetailsTypeDef",
+    {
+        "State": str,
+    },
+    total=False,
+)
+
 AwsEc2InstanceNetworkInterfacesDetailsTypeDef = TypedDict(
     "AwsEc2InstanceNetworkInterfacesDetailsTypeDef",
     {
         "NetworkInterfaceId": str,
     },
     total=False,
 )
@@ -1738,14 +2023,45 @@
     {
         "GroupName": str,
         "GroupId": str,
     },
     total=False,
 )
 
+PropagatingVgwSetDetailsTypeDef = TypedDict(
+    "PropagatingVgwSetDetailsTypeDef",
+    {
+        "GatewayId": str,
+    },
+    total=False,
+)
+
+RouteSetDetailsTypeDef = TypedDict(
+    "RouteSetDetailsTypeDef",
+    {
+        "CarrierGatewayId": str,
+        "CoreNetworkArn": str,
+        "DestinationCidrBlock": str,
+        "DestinationIpv6CidrBlock": str,
+        "DestinationPrefixListId": str,
+        "EgressOnlyInternetGatewayId": str,
+        "GatewayId": str,
+        "InstanceId": str,
+        "InstanceOwnerId": str,
+        "LocalGatewayId": str,
+        "NatGatewayId": str,
+        "NetworkInterfaceId": str,
+        "Origin": str,
+        "State": str,
+        "TransitGatewayId": str,
+        "VpcPeeringConnectionId": str,
+    },
+    total=False,
+)
+
 AwsEc2SecurityGroupIpRangeTypeDef = TypedDict(
     "AwsEc2SecurityGroupIpRangeTypeDef",
     {
         "CidrIp": str,
     },
     total=False,
 )
@@ -2318,14 +2634,15 @@
 )
 
 AwsEksClusterResourcesVpcConfigDetailsTypeDef = TypedDict(
     "AwsEksClusterResourcesVpcConfigDetailsTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
         "SubnetIds": Sequence[str],
+        "EndpointPublicAccess": bool,
     },
     total=False,
 )
 
 AwsEksClusterLoggingClusterLoggingDetailsTypeDef = TypedDict(
     "AwsEksClusterLoggingClusterLoggingDetailsTypeDef",
     {
@@ -2560,14 +2877,82 @@
     {
         "Code": str,
         "Reason": str,
     },
     total=False,
 )
 
+AwsEventSchemasRegistryDetailsTypeDef = TypedDict(
+    "AwsEventSchemasRegistryDetailsTypeDef",
+    {
+        "Description": str,
+        "RegistryArn": str,
+        "RegistryName": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef",
+    {
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef",
+    {
+        "Reason": str,
+        "Status": str,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorFeaturesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorFeaturesDetailsTypeDef",
+    {
+        "Name": str,
+        "Status": str,
+    },
+    total=False,
+)
+
 AwsIamAccessKeySessionContextAttributesTypeDef = TypedDict(
     "AwsIamAccessKeySessionContextAttributesTypeDef",
     {
         "MfaAuthenticated": bool,
         "CreationDate": str,
     },
     total=False,
@@ -3243,14 +3628,24 @@
     {
         "Name": AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType,
         "Value": str,
     },
     total=False,
 )
 
+AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef = TypedDict(
+    "AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef",
+    {
+        "Days": int,
+        "Mode": str,
+        "Years": int,
+    },
+    total=False,
+)
+
 AwsS3BucketServerSideEncryptionByDefaultTypeDef = TypedDict(
     "AwsS3BucketServerSideEncryptionByDefaultTypeDef",
     {
         "SSEAlgorithm": str,
         "KMSMasterKeyID": str,
     },
     total=False,
@@ -3335,43 +3730,14 @@
     "KeywordFilterTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
-MapFilterTypeDef = TypedDict(
-    "MapFilterTypeDef",
-    {
-        "Key": str,
-        "Value": str,
-        "Comparison": MapFilterComparisonType,
-    },
-    total=False,
-)
-
-NumberFilterTypeDef = TypedDict(
-    "NumberFilterTypeDef",
-    {
-        "Gte": float,
-        "Lte": float,
-        "Eq": float,
-    },
-    total=False,
-)
-
-StringFilterTypeDef = TypedDict(
-    "StringFilterTypeDef",
-    {
-        "Value": str,
-        "Comparison": StringFilterComparisonType,
-    },
-    total=False,
-)
-
 AwsSecurityFindingIdentifierTypeDef = TypedDict(
     "AwsSecurityFindingIdentifierTypeDef",
     {
         "Id": str,
         "ProductArn": str,
     },
 )
@@ -3388,17 +3754,19 @@
         "Type": MalwareTypeType,
         "Path": str,
         "State": MalwareStateType,
     },
     total=False,
 )
 
+
 class MalwareTypeDef(_RequiredMalwareTypeDef, _OptionalMalwareTypeDef):
     pass
 
+
 NoteTypeDef = TypedDict(
     "NoteTypeDef",
     {
         "Text": str,
         "UpdatedBy": str,
         "UpdatedAt": str,
     },
@@ -3423,38 +3791,32 @@
         "OperationEndTime": str,
         "RebootOption": str,
         "Operation": str,
     },
     total=False,
 )
 
+
 class PatchSummaryTypeDef(_RequiredPatchSummaryTypeDef, _OptionalPatchSummaryTypeDef):
     pass
 
+
 ProcessDetailsTypeDef = TypedDict(
     "ProcessDetailsTypeDef",
     {
         "Name": str,
         "Path": str,
         "Pid": int,
         "ParentPid": int,
         "LaunchedAt": str,
         "TerminatedAt": str,
     },
     total=False,
 )
 
-RelatedFindingTypeDef = TypedDict(
-    "RelatedFindingTypeDef",
-    {
-        "ProductArn": str,
-        "Id": str,
-    },
-)
-
 SeverityTypeDef = TypedDict(
     "SeverityTypeDef",
     {
         "Product": float,
         "Label": SeverityLabelType,
         "Normalized": int,
         "Original": str,
@@ -3524,14 +3886,30 @@
         "NonCompliantMediumCount": int,
         "NonCompliantUnspecifiedCount": int,
         "PatchGroup": str,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef",
+    {
+        "Enabled": bool,
+    },
+    total=False,
+)
+
+AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef",
+    {
+        "LogGroupArn": str,
+    },
+    total=False,
+)
+
 AwsWafRateBasedRuleMatchPredicateTypeDef = TypedDict(
     "AwsWafRateBasedRuleMatchPredicateTypeDef",
     {
         "DataId": str,
         "Negated": bool,
         "Type": str,
     },
@@ -3657,29 +4035,35 @@
         "KeyId": str,
         "Status": str,
         "Type": str,
     },
     total=False,
 )
 
-BatchDisableStandardsRequestRequestTypeDef = TypedDict(
-    "BatchDisableStandardsRequestRequestTypeDef",
+BatchDeleteAutomationRulesRequestRequestTypeDef = TypedDict(
+    "BatchDeleteAutomationRulesRequestRequestTypeDef",
     {
-        "StandardsSubscriptionArns": Sequence[str],
+        "AutomationRulesArns": Sequence[str],
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+UnprocessedAutomationRuleTypeDef = TypedDict(
+    "UnprocessedAutomationRuleTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "RuleArn": str,
+        "ErrorCode": int,
+        "ErrorMessage": str,
+    },
+    total=False,
+)
+
+BatchDisableStandardsRequestRequestTypeDef = TypedDict(
+    "BatchDisableStandardsRequestRequestTypeDef",
+    {
+        "StandardsSubscriptionArns": Sequence[str],
     },
 )
 
 _RequiredStandardsSubscriptionRequestTypeDef = TypedDict(
     "_RequiredStandardsSubscriptionRequestTypeDef",
     {
         "StandardsArn": str,
@@ -3689,54 +4073,141 @@
     "_OptionalStandardsSubscriptionRequestTypeDef",
     {
         "StandardsInput": Mapping[str, str],
     },
     total=False,
 )
 
+
 class StandardsSubscriptionRequestTypeDef(
     _RequiredStandardsSubscriptionRequestTypeDef, _OptionalStandardsSubscriptionRequestTypeDef
 ):
     pass
 
-ImportFindingsErrorTypeDef = TypedDict(
-    "ImportFindingsErrorTypeDef",
+
+BatchGetAutomationRulesRequestRequestTypeDef = TypedDict(
+    "BatchGetAutomationRulesRequestRequestTypeDef",
     {
-        "Id": str,
-        "ErrorCode": str,
-        "ErrorMessage": str,
+        "AutomationRulesArns": Sequence[str],
     },
 )
 
-NoteUpdateTypeDef = TypedDict(
-    "NoteUpdateTypeDef",
+BatchGetSecurityControlsRequestRequestTypeDef = TypedDict(
+    "BatchGetSecurityControlsRequestRequestTypeDef",
     {
-        "Text": str,
-        "UpdatedBy": str,
+        "SecurityControlIds": Sequence[str],
     },
 )
 
-SeverityUpdateTypeDef = TypedDict(
-    "SeverityUpdateTypeDef",
+SecurityControlTypeDef = TypedDict(
+    "SecurityControlTypeDef",
     {
-        "Normalized": int,
-        "Product": float,
-        "Label": SeverityLabelType,
+        "SecurityControlId": str,
+        "SecurityControlArn": str,
+        "Title": str,
+        "Description": str,
+        "RemediationUrl": str,
+        "SeverityRating": SeverityRatingType,
+        "SecurityControlStatus": ControlStatusType,
+    },
+)
+
+_RequiredUnprocessedSecurityControlTypeDef = TypedDict(
+    "_RequiredUnprocessedSecurityControlTypeDef",
+    {
+        "SecurityControlId": str,
+        "ErrorCode": UnprocessedErrorCodeType,
+    },
+)
+_OptionalUnprocessedSecurityControlTypeDef = TypedDict(
+    "_OptionalUnprocessedSecurityControlTypeDef",
+    {
+        "ErrorReason": str,
     },
     total=False,
 )
 
-WorkflowUpdateTypeDef = TypedDict(
-    "WorkflowUpdateTypeDef",
+
+class UnprocessedSecurityControlTypeDef(
+    _RequiredUnprocessedSecurityControlTypeDef, _OptionalUnprocessedSecurityControlTypeDef
+):
+    pass
+
+
+StandardsControlAssociationIdTypeDef = TypedDict(
+    "StandardsControlAssociationIdTypeDef",
     {
-        "Status": WorkflowStatusType,
+        "SecurityControlId": str,
+        "StandardsArn": str,
+    },
+)
+
+_RequiredStandardsControlAssociationDetailTypeDef = TypedDict(
+    "_RequiredStandardsControlAssociationDetailTypeDef",
+    {
+        "StandardsArn": str,
+        "SecurityControlId": str,
+        "SecurityControlArn": str,
+        "AssociationStatus": AssociationStatusType,
+    },
+)
+_OptionalStandardsControlAssociationDetailTypeDef = TypedDict(
+    "_OptionalStandardsControlAssociationDetailTypeDef",
+    {
+        "RelatedRequirements": List[str],
+        "UpdatedAt": datetime,
+        "UpdatedReason": str,
+        "StandardsControlTitle": str,
+        "StandardsControlDescription": str,
+        "StandardsControlArns": List[str],
+    },
+    total=False,
+)
+
+
+class StandardsControlAssociationDetailTypeDef(
+    _RequiredStandardsControlAssociationDetailTypeDef,
+    _OptionalStandardsControlAssociationDetailTypeDef,
+):
+    pass
+
+
+ImportFindingsErrorTypeDef = TypedDict(
+    "ImportFindingsErrorTypeDef",
+    {
+        "Id": str,
+        "ErrorCode": str,
+        "ErrorMessage": str,
+    },
+)
+
+_RequiredStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_RequiredStandardsControlAssociationUpdateTypeDef",
+    {
+        "StandardsArn": str,
+        "SecurityControlId": str,
+        "AssociationStatus": AssociationStatusType,
+    },
+)
+_OptionalStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_OptionalStandardsControlAssociationUpdateTypeDef",
+    {
+        "UpdatedReason": str,
     },
     total=False,
 )
 
+
+class StandardsControlAssociationUpdateTypeDef(
+    _RequiredStandardsControlAssociationUpdateTypeDef,
+    _OptionalStandardsControlAssociationUpdateTypeDef,
+):
+    pass
+
+
 CellTypeDef = TypedDict(
     "CellTypeDef",
     {
         "Column": int,
         "Row": int,
         "ColumnName": str,
         "CellReference": str,
@@ -3763,17 +4234,19 @@
     "_OptionalStatusReasonTypeDef",
     {
         "Description": str,
     },
     total=False,
 )
 
+
 class StatusReasonTypeDef(_RequiredStatusReasonTypeDef, _OptionalStatusReasonTypeDef):
     pass
 
+
 VolumeMountTypeDef = TypedDict(
     "VolumeMountTypeDef",
     {
         "Name": str,
         "MountPath": str,
     },
     total=False,
@@ -3784,34 +4257,71 @@
     {
         "Name": str,
         "Description": str,
         "Id": str,
     },
 )
 
+CreateActionTargetResponseTypeDef = TypedDict(
+    "CreateActionTargetResponseTypeDef",
+    {
+        "ActionTargetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAutomationRuleResponseTypeDef = TypedDict(
+    "CreateAutomationRuleResponseTypeDef",
+    {
+        "RuleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateFindingAggregatorRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFindingAggregatorRequestRequestTypeDef",
     {
         "RegionLinkingMode": str,
     },
 )
 _OptionalCreateFindingAggregatorRequestRequestTypeDef = TypedDict(
     "_OptionalCreateFindingAggregatorRequestRequestTypeDef",
     {
         "Regions": Sequence[str],
     },
     total=False,
 )
 
+
 class CreateFindingAggregatorRequestRequestTypeDef(
     _RequiredCreateFindingAggregatorRequestRequestTypeDef,
     _OptionalCreateFindingAggregatorRequestRequestTypeDef,
 ):
     pass
 
+
+CreateFindingAggregatorResponseTypeDef = TypedDict(
+    "CreateFindingAggregatorResponseTypeDef",
+    {
+        "FindingAggregatorArn": str,
+        "FindingAggregationRegion": str,
+        "RegionLinkingMode": str,
+        "Regions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateInsightResponseTypeDef = TypedDict(
+    "CreateInsightResponseTypeDef",
+    {
+        "InsightArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResultTypeDef = TypedDict(
     "ResultTypeDef",
     {
         "AccountId": str,
         "ProcessingResult": str,
     },
     total=False,
@@ -3836,48 +4346,63 @@
 DeleteActionTargetRequestRequestTypeDef = TypedDict(
     "DeleteActionTargetRequestRequestTypeDef",
     {
         "ActionTargetArn": str,
     },
 )
 
+DeleteActionTargetResponseTypeDef = TypedDict(
+    "DeleteActionTargetResponseTypeDef",
+    {
+        "ActionTargetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteFindingAggregatorRequestRequestTypeDef = TypedDict(
     "DeleteFindingAggregatorRequestRequestTypeDef",
     {
         "FindingAggregatorArn": str,
     },
 )
 
 DeleteInsightRequestRequestTypeDef = TypedDict(
     "DeleteInsightRequestRequestTypeDef",
     {
         "InsightArn": str,
     },
 )
 
+DeleteInsightResponseTypeDef = TypedDict(
+    "DeleteInsightResponseTypeDef",
+    {
+        "InsightArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteInvitationsRequestRequestTypeDef = TypedDict(
     "DeleteInvitationsRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
 DeleteMembersRequestRequestTypeDef = TypedDict(
     "DeleteMembersRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef = TypedDict(
+    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ActionTargetArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeActionTargetsRequestRequestTypeDef = TypedDict(
     "DescribeActionTargetsRequestRequestTypeDef",
     {
@@ -3892,14 +4417,44 @@
     "DescribeHubRequestRequestTypeDef",
     {
         "HubArn": str,
     },
     total=False,
 )
 
+DescribeHubResponseTypeDef = TypedDict(
+    "DescribeHubResponseTypeDef",
+    {
+        "HubArn": str,
+        "SubscribedAt": str,
+        "AutoEnableControls": bool,
+        "ControlFindingGenerator": ControlFindingGeneratorType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
+    "DescribeOrganizationConfigurationResponseTypeDef",
+    {
+        "AutoEnable": bool,
+        "MemberAccountLimitReached": bool,
+        "AutoEnableStandards": AutoEnableStandardsType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeProductsRequestDescribeProductsPaginateTypeDef = TypedDict(
+    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
+    {
+        "ProductArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeProductsRequestRequestTypeDef = TypedDict(
     "DescribeProductsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "ProductArn": str,
     },
@@ -3923,17 +4478,41 @@
         "MarketplaceUrl": str,
         "ActivationUrl": str,
         "ProductSubscriptionResourcePolicy": str,
     },
     total=False,
 )
 
+
 class ProductTypeDef(_RequiredProductTypeDef, _OptionalProductTypeDef):
     pass
 
+
+_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
+    {
+        "StandardsSubscriptionArn": str,
+    },
+)
+_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef(
+    _RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
+    _OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeStandardsControlsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeStandardsControlsRequestRequestTypeDef",
     {
         "StandardsSubscriptionArn": str,
     },
 )
 _OptionalDescribeStandardsControlsRequestRequestTypeDef = TypedDict(
@@ -3941,20 +4520,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class DescribeStandardsControlsRequestRequestTypeDef(
     _RequiredDescribeStandardsControlsRequestRequestTypeDef,
     _OptionalDescribeStandardsControlsRequestRequestTypeDef,
 ):
     pass
 
+
 StandardsControlTypeDef = TypedDict(
     "StandardsControlTypeDef",
     {
         "StandardsControlArn": str,
         "ControlStatus": ControlStatusType,
         "DisabledReason": str,
         "ControlStatusUpdatedAt": datetime,
@@ -3964,14 +4545,22 @@
         "RemediationUrl": str,
         "SeverityRating": SeverityRatingType,
         "RelatedRequirements": List[str],
     },
     total=False,
 )
 
+DescribeStandardsRequestDescribeStandardsPaginateTypeDef = TypedDict(
+    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeStandardsRequestRequestTypeDef = TypedDict(
     "DescribeStandardsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -4001,26 +4590,35 @@
 EnableImportFindingsForProductRequestRequestTypeDef = TypedDict(
     "EnableImportFindingsForProductRequestRequestTypeDef",
     {
         "ProductArn": str,
     },
 )
 
+EnableImportFindingsForProductResponseTypeDef = TypedDict(
+    "EnableImportFindingsForProductResponseTypeDef",
+    {
+        "ProductSubscriptionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableOrganizationAdminAccountRequestRequestTypeDef = TypedDict(
     "EnableOrganizationAdminAccountRequestRequestTypeDef",
     {
         "AdminAccountId": str,
     },
 )
 
 EnableSecurityHubRequestRequestTypeDef = TypedDict(
     "EnableSecurityHubRequestRequestTypeDef",
     {
         "Tags": Mapping[str, str],
         "EnableDefaultStandards": bool,
+        "ControlFindingGenerator": ControlFindingGeneratorType,
     },
     total=False,
 )
 
 FilePathsTypeDef = TypedDict(
     "FilePathsTypeDef",
     {
@@ -4036,14 +4634,33 @@
     "FindingAggregatorTypeDef",
     {
         "FindingAggregatorArn": str,
     },
     total=False,
 )
 
+FindingHistoryUpdateSourceTypeDef = TypedDict(
+    "FindingHistoryUpdateSourceTypeDef",
+    {
+        "Type": FindingHistoryUpdateSourceTypeType,
+        "Identity": str,
+    },
+    total=False,
+)
+
+FindingHistoryUpdateTypeDef = TypedDict(
+    "FindingHistoryUpdateTypeDef",
+    {
+        "UpdatedField": str,
+        "OldValue": str,
+        "NewValue": str,
+    },
+    total=False,
+)
+
 FindingProviderSeverityTypeDef = TypedDict(
     "FindingProviderSeverityTypeDef",
     {
         "Label": SeverityLabelType,
         "Original": str,
     },
     total=False,
@@ -4073,14 +4690,23 @@
         "InvitationId": str,
         "InvitedAt": datetime,
         "MemberStatus": str,
     },
     total=False,
 )
 
+GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef = TypedDict(
+    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
+    {
+        "StandardsSubscriptionArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetEnabledStandardsRequestRequestTypeDef = TypedDict(
     "GetEnabledStandardsRequestRequestTypeDef",
     {
         "StandardsSubscriptionArns": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
@@ -4090,14 +4716,25 @@
 GetFindingAggregatorRequestRequestTypeDef = TypedDict(
     "GetFindingAggregatorRequestRequestTypeDef",
     {
         "FindingAggregatorArn": str,
     },
 )
 
+GetFindingAggregatorResponseTypeDef = TypedDict(
+    "GetFindingAggregatorResponseTypeDef",
+    {
+        "FindingAggregatorArn": str,
+        "FindingAggregationRegion": str,
+        "RegionLinkingMode": str,
+        "Regions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SortCriterionTypeDef = TypedDict(
     "SortCriterionTypeDef",
     {
         "Field": str,
         "SortOrder": SortOrderType,
     },
     total=False,
@@ -4106,24 +4743,41 @@
 GetInsightResultsRequestRequestTypeDef = TypedDict(
     "GetInsightResultsRequestRequestTypeDef",
     {
         "InsightArn": str,
     },
 )
 
+GetInsightsRequestGetInsightsPaginateTypeDef = TypedDict(
+    "GetInsightsRequestGetInsightsPaginateTypeDef",
+    {
+        "InsightArns": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInsightsRequestRequestTypeDef = TypedDict(
     "GetInsightsRequestRequestTypeDef",
     {
         "InsightArns": Sequence[str],
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+GetInvitationsCountResponseTypeDef = TypedDict(
+    "GetInvitationsCountResponseTypeDef",
+    {
+        "InvitationsCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMembersRequestRequestTypeDef = TypedDict(
     "GetMembersRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
@@ -4152,67 +4806,239 @@
 InviteMembersRequestRequestTypeDef = TypedDict(
     "InviteMembersRequestRequestTypeDef",
     {
         "AccountIds": Sequence[str],
     },
 )
 
+ListAutomationRulesRequestRequestTypeDef = TypedDict(
+    "ListAutomationRulesRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef = TypedDict(
+    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEnabledProductsForImportRequestRequestTypeDef = TypedDict(
     "ListEnabledProductsForImportRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListEnabledProductsForImportResponseTypeDef = TypedDict(
+    "ListEnabledProductsForImportResponseTypeDef",
+    {
+        "ProductSubscriptions": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef = TypedDict(
+    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFindingAggregatorsRequestRequestTypeDef = TypedDict(
     "ListFindingAggregatorsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
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
 
+ListMembersRequestListMembersPaginateTypeDef = TypedDict(
+    "ListMembersRequestListMembersPaginateTypeDef",
+    {
+        "OnlyAssociated": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMembersRequestRequestTypeDef = TypedDict(
     "ListMembersRequestRequestTypeDef",
     {
         "OnlyAssociated": bool,
         "MaxResults": int,
         "NextToken": str,
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef = TypedDict(
+    "ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef",
+    {
+        "StandardsArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListSecurityControlDefinitionsRequestRequestTypeDef = TypedDict(
+    "ListSecurityControlDefinitionsRequestRequestTypeDef",
+    {
+        "StandardsArn": str,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+SecurityControlDefinitionTypeDef = TypedDict(
+    "SecurityControlDefinitionTypeDef",
+    {
+        "SecurityControlId": str,
+        "Title": str,
+        "Description": str,
+        "RemediationUrl": str,
+        "SeverityRating": SeverityRatingType,
+        "CurrentRegionAvailability": RegionAvailabilityStatusType,
+    },
+)
+
+_RequiredListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef = TypedDict(
+    "_RequiredListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef",
+    {
+        "SecurityControlId": str,
+    },
+)
+_OptionalListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef = TypedDict(
+    "_OptionalListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef(
+    _RequiredListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef,
+    _OptionalListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef,
+):
+    pass
+
+
+_RequiredListStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "_RequiredListStandardsControlAssociationsRequestRequestTypeDef",
+    {
+        "SecurityControlId": str,
+    },
+)
+_OptionalListStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "_OptionalListStandardsControlAssociationsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class ListStandardsControlAssociationsRequestRequestTypeDef(
+    _RequiredListStandardsControlAssociationsRequestRequestTypeDef,
+    _OptionalListStandardsControlAssociationsRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredStandardsControlAssociationSummaryTypeDef = TypedDict(
+    "_RequiredStandardsControlAssociationSummaryTypeDef",
+    {
+        "StandardsArn": str,
+        "SecurityControlId": str,
+        "SecurityControlArn": str,
+        "AssociationStatus": AssociationStatusType,
+    },
+)
+_OptionalStandardsControlAssociationSummaryTypeDef = TypedDict(
+    "_OptionalStandardsControlAssociationSummaryTypeDef",
+    {
+        "RelatedRequirements": List[str],
+        "UpdatedAt": datetime,
+        "UpdatedReason": str,
+        "StandardsControlTitle": str,
+        "StandardsControlDescription": str,
+    },
+    total=False,
+)
+
+
+class StandardsControlAssociationSummaryTypeDef(
+    _RequiredStandardsControlAssociationSummaryTypeDef,
+    _OptionalStandardsControlAssociationSummaryTypeDef,
+):
+    pass
+
+
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
 PortRangeTypeDef = TypedDict(
     "PortRangeTypeDef",
     {
         "Begin": int,
         "End": int,
     },
     total=False,
@@ -4233,23 +5059,44 @@
     {
         "JsonPath": str,
         "RecordIndex": int,
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
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "Text": str,
         "Url": str,
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
 RuleGroupSourceListDetailsTypeDef = TypedDict(
     "RuleGroupSourceListDetailsTypeDef",
     {
         "GeneratedRulesType": str,
         "TargetTypes": Sequence[str],
         "Targets": Sequence[str],
     },
@@ -4406,20 +5253,22 @@
     {
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
+
 class UpdateActionTargetRequestRequestTypeDef(
     _RequiredUpdateActionTargetRequestRequestTypeDef,
     _OptionalUpdateActionTargetRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateFindingAggregatorRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFindingAggregatorRequestRequestTypeDef",
     {
         "FindingAggregatorArn": str,
         "RegionLinkingMode": str,
     },
 )
@@ -4427,44 +5276,60 @@
     "_OptionalUpdateFindingAggregatorRequestRequestTypeDef",
     {
         "Regions": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdateFindingAggregatorRequestRequestTypeDef(
     _RequiredUpdateFindingAggregatorRequestRequestTypeDef,
     _OptionalUpdateFindingAggregatorRequestRequestTypeDef,
 ):
     pass
 
+
+UpdateFindingAggregatorResponseTypeDef = TypedDict(
+    "UpdateFindingAggregatorResponseTypeDef",
+    {
+        "FindingAggregatorArn": str,
+        "FindingAggregationRegion": str,
+        "RegionLinkingMode": str,
+        "Regions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
         "AutoEnable": bool,
     },
 )
 _OptionalUpdateOrganizationConfigurationRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateOrganizationConfigurationRequestRequestTypeDef",
     {
         "AutoEnableStandards": AutoEnableStandardsType,
     },
     total=False,
 )
 
+
 class UpdateOrganizationConfigurationRequestRequestTypeDef(
     _RequiredUpdateOrganizationConfigurationRequestRequestTypeDef,
     _OptionalUpdateOrganizationConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateSecurityHubConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateSecurityHubConfigurationRequestRequestTypeDef",
     {
         "AutoEnableControls": bool,
+        "ControlFindingGenerator": ControlFindingGeneratorType,
     },
     total=False,
 )
 
 _RequiredUpdateStandardsControlRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStandardsControlRequestRequestTypeDef",
     {
@@ -4476,20 +5341,22 @@
     {
         "ControlStatus": ControlStatusType,
         "DisabledReason": str,
     },
     total=False,
 )
 
+
 class UpdateStandardsControlRequestRequestTypeDef(
     _RequiredUpdateStandardsControlRequestRequestTypeDef,
     _OptionalUpdateStandardsControlRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredVulnerabilityVendorTypeDef = TypedDict(
     "_RequiredVulnerabilityVendorTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalVulnerabilityVendorTypeDef = TypedDict(
@@ -4499,19 +5366,21 @@
         "VendorSeverity": str,
         "VendorCreatedAt": str,
         "VendorUpdatedAt": str,
     },
     total=False,
 )
 
+
 class VulnerabilityVendorTypeDef(
     _RequiredVulnerabilityVendorTypeDef, _OptionalVulnerabilityVendorTypeDef
 ):
     pass
 
+
 CreateMembersRequestRequestTypeDef = TypedDict(
     "CreateMembersRequestRequestTypeDef",
     {
         "AccountDetails": Sequence[AccountDetailsTypeDef],
     },
 )
 
@@ -4523,26 +5392,94 @@
         "Country": CountryTypeDef,
         "City": CityTypeDef,
         "GeoLocation": GeoLocationTypeDef,
     },
     total=False,
 )
 
+DescribeActionTargetsResponseTypeDef = TypedDict(
+    "DescribeActionTargetsResponseTypeDef",
+    {
+        "ActionTargets": List[ActionTargetTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CvssTypeDef = TypedDict(
     "CvssTypeDef",
     {
         "Version": str,
         "BaseScore": float,
         "BaseVector": str,
         "Source": str,
         "Adjustments": Sequence[AdjustmentTypeDef],
     },
     total=False,
 )
 
+ListOrganizationAdminAccountsResponseTypeDef = TypedDict(
+    "ListOrganizationAdminAccountsResponseTypeDef",
+    {
+        "AdminAccounts": List[AdminAccountTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociationSetDetailsTypeDef = TypedDict(
+    "AssociationSetDetailsTypeDef",
+    {
+        "AssociationState": AssociationStateDetailsTypeDef,
+        "GatewayId": str,
+        "Main": bool,
+        "RouteTableAssociationId": str,
+        "RouteTableId": str,
+        "SubnetId": str,
+    },
+    total=False,
+)
+
+AutomationRulesFindingFieldsUpdateTypeDef = TypedDict(
+    "AutomationRulesFindingFieldsUpdateTypeDef",
+    {
+        "Note": NoteUpdateTypeDef,
+        "Severity": SeverityUpdateTypeDef,
+        "VerificationState": VerificationStateType,
+        "Confidence": int,
+        "Criticality": int,
+        "Types": List[str],
+        "UserDefinedFields": Dict[str, str],
+        "Workflow": WorkflowUpdateTypeDef,
+        "RelatedFindings": List[RelatedFindingTypeDef],
+    },
+    total=False,
+)
+
+ListAutomationRulesResponseTypeDef = TypedDict(
+    "ListAutomationRulesResponseTypeDef",
+    {
+        "AutomationRulesMetadata": List[AutomationRulesMetadataTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AwsAmazonMqBrokerLogsDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerLogsDetailsTypeDef",
+    {
+        "Audit": bool,
+        "General": bool,
+        "AuditLogGroup": str,
+        "GeneralLogGroup": str,
+        "Pending": AwsAmazonMqBrokerLogsPendingDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsApiGatewayRestApiDetailsTypeDef = TypedDict(
     "AwsApiGatewayRestApiDetailsTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "CreatedDate": str,
@@ -4611,14 +5548,25 @@
         "AutoDeploy": bool,
         "LastDeploymentStatusMessage": str,
         "ApiGatewayManaged": bool,
     },
     total=False,
 )
 
+AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef",
+    {
+        "AuthenticationType": str,
+        "LambdaAuthorizerConfig": AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef,
+        "OpenIdConnectConfig": AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef,
+        "UserPoolConfig": AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef = TypedDict(
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef",
     {
         "LaunchTemplateSpecification": AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateLaunchTemplateSpecificationTypeDef,
         "Overrides": Sequence[
             AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateOverridesListDetailsTypeDef
         ],
@@ -4848,14 +5796,15 @@
         "IamInstanceProfileArn": str,
         "VpcId": str,
         "SubnetId": str,
         "LaunchedAt": str,
         "NetworkInterfaces": Sequence[AwsEc2InstanceNetworkInterfacesDetailsTypeDef],
         "VirtualizationType": str,
         "MetadataOptions": AwsEc2InstanceMetadataOptionsTypeDef,
+        "Monitoring": AwsEc2InstanceMonitoringDetailsTypeDef,
     },
     total=False,
 )
 
 AwsEc2LaunchTemplateDataBlockDeviceMappingSetDetailsTypeDef = TypedDict(
     "AwsEc2LaunchTemplateDataBlockDeviceMappingSetDetailsTypeDef",
     {
@@ -5327,14 +6276,30 @@
         "Type": str,
         "VpcId": str,
         "LoadBalancerAttributes": Sequence[AwsElbv2LoadBalancerAttributeTypeDef],
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef",
+    {
+        "AuditLogs": AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef,
+    },
+    total=False,
+)
+
+AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef",
+    {
+        "EbsVolumes": AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsIamAccessKeySessionContextTypeDef = TypedDict(
     "AwsIamAccessKeySessionContextTypeDef",
     {
         "Attributes": AwsIamAccessKeySessionContextAttributesTypeDef,
         "SessionIssuer": AwsIamAccessKeySessionContextSessionIssuerTypeDef,
     },
     total=False,
@@ -5624,14 +6589,22 @@
     "AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef",
     {
         "FilterRules": Sequence[AwsS3BucketNotificationConfigurationS3KeyFilterRuleTypeDef],
     },
     total=False,
 )
 
+AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef = TypedDict(
+    "AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef",
+    {
+        "DefaultRetention": AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsS3BucketServerSideEncryptionRuleTypeDef = TypedDict(
     "AwsS3BucketServerSideEncryptionRuleTypeDef",
     {
         "ApplyServerSideEncryptionByDefault": AwsS3BucketServerSideEncryptionByDefaultTypeDef,
     },
     total=False,
 )
@@ -5685,23 +6658,101 @@
         "Deleted": bool,
         "Name": str,
         "Description": str,
     },
     total=False,
 )
 
+_RequiredBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
+    "_RequiredBatchUpdateFindingsRequestRequestTypeDef",
+    {
+        "FindingIdentifiers": Sequence[AwsSecurityFindingIdentifierTypeDef],
+    },
+)
+_OptionalBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
+    "_OptionalBatchUpdateFindingsRequestRequestTypeDef",
+    {
+        "Note": NoteUpdateTypeDef,
+        "Severity": SeverityUpdateTypeDef,
+        "VerificationState": VerificationStateType,
+        "Confidence": int,
+        "Criticality": int,
+        "Types": Sequence[str],
+        "UserDefinedFields": Mapping[str, str],
+        "Workflow": WorkflowUpdateTypeDef,
+        "RelatedFindings": Sequence[RelatedFindingTypeDef],
+    },
+    total=False,
+)
+
+
+class BatchUpdateFindingsRequestRequestTypeDef(
+    _RequiredBatchUpdateFindingsRequestRequestTypeDef,
+    _OptionalBatchUpdateFindingsRequestRequestTypeDef,
+):
+    pass
+
+
 BatchUpdateFindingsUnprocessedFindingTypeDef = TypedDict(
     "BatchUpdateFindingsUnprocessedFindingTypeDef",
     {
         "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
         "ErrorCode": str,
         "ErrorMessage": str,
     },
 )
 
+_RequiredGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef",
+    {
+        "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
+    },
+)
+_OptionalGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetFindingHistoryRequestGetFindingHistoryPaginateTypeDef(
+    _RequiredGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef,
+    _OptionalGetFindingHistoryRequestGetFindingHistoryPaginateTypeDef,
+):
+    pass
+
+
+_RequiredGetFindingHistoryRequestRequestTypeDef = TypedDict(
+    "_RequiredGetFindingHistoryRequestRequestTypeDef",
+    {
+        "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
+    },
+)
+_OptionalGetFindingHistoryRequestRequestTypeDef = TypedDict(
+    "_OptionalGetFindingHistoryRequestRequestTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class GetFindingHistoryRequestRequestTypeDef(
+    _RequiredGetFindingHistoryRequestRequestTypeDef, _OptionalGetFindingHistoryRequestRequestTypeDef
+):
+    pass
+
+
 AwsSnsTopicDetailsTypeDef = TypedDict(
     "AwsSnsTopicDetailsTypeDef",
     {
         "KmsMasterKeyId": str,
         "Subscription": Sequence[AwsSnsTopicSubscriptionTypeDef],
         "TopicName": str,
         "Owner": str,
@@ -5720,14 +6771,22 @@
     "AwsSsmPatchTypeDef",
     {
         "ComplianceSummary": AwsSsmComplianceSummaryTypeDef,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef",
+    {
+        "CloudWatchLogsLogGroup": AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsWafRateBasedRuleDetailsTypeDef = TypedDict(
     "AwsWafRateBasedRuleDetailsTypeDef",
     {
         "MetricName": str,
         "Name": str,
         "RateKey": str,
         "RateLimit": int,
@@ -5841,195 +6900,118 @@
     "AwsWafv2WebAclCaptchaConfigDetailsTypeDef",
     {
         "ImmunityTimeProperty": AwsWafv2WebAclCaptchaConfigImmunityTimePropertyDetailsTypeDef,
     },
     total=False,
 )
 
-CreateActionTargetResponseTypeDef = TypedDict(
-    "CreateActionTargetResponseTypeDef",
-    {
-        "ActionTargetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFindingAggregatorResponseTypeDef = TypedDict(
-    "CreateFindingAggregatorResponseTypeDef",
-    {
-        "FindingAggregatorArn": str,
-        "FindingAggregationRegion": str,
-        "RegionLinkingMode": str,
-        "Regions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateInsightResponseTypeDef = TypedDict(
-    "CreateInsightResponseTypeDef",
-    {
-        "InsightArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteActionTargetResponseTypeDef = TypedDict(
-    "DeleteActionTargetResponseTypeDef",
-    {
-        "ActionTargetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteInsightResponseTypeDef = TypedDict(
-    "DeleteInsightResponseTypeDef",
+BatchDeleteAutomationRulesResponseTypeDef = TypedDict(
+    "BatchDeleteAutomationRulesResponseTypeDef",
     {
-        "InsightArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProcessedAutomationRules": List[str],
+        "UnprocessedAutomationRules": List[UnprocessedAutomationRuleTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeActionTargetsResponseTypeDef = TypedDict(
-    "DescribeActionTargetsResponseTypeDef",
+BatchUpdateAutomationRulesResponseTypeDef = TypedDict(
+    "BatchUpdateAutomationRulesResponseTypeDef",
     {
-        "ActionTargets": List[ActionTargetTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProcessedAutomationRules": List[str],
+        "UnprocessedAutomationRules": List[UnprocessedAutomationRuleTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeHubResponseTypeDef = TypedDict(
-    "DescribeHubResponseTypeDef",
+BatchEnableStandardsRequestRequestTypeDef = TypedDict(
+    "BatchEnableStandardsRequestRequestTypeDef",
     {
-        "HubArn": str,
-        "SubscribedAt": str,
-        "AutoEnableControls": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StandardsSubscriptionRequests": Sequence[StandardsSubscriptionRequestTypeDef],
     },
 )
 
-DescribeOrganizationConfigurationResponseTypeDef = TypedDict(
-    "DescribeOrganizationConfigurationResponseTypeDef",
+BatchGetSecurityControlsResponseTypeDef = TypedDict(
+    "BatchGetSecurityControlsResponseTypeDef",
     {
-        "AutoEnable": bool,
-        "MemberAccountLimitReached": bool,
-        "AutoEnableStandards": AutoEnableStandardsType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SecurityControls": List[SecurityControlTypeDef],
+        "UnprocessedIds": List[UnprocessedSecurityControlTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EnableImportFindingsForProductResponseTypeDef = TypedDict(
-    "EnableImportFindingsForProductResponseTypeDef",
+BatchGetStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "BatchGetStandardsControlAssociationsRequestRequestTypeDef",
     {
-        "ProductSubscriptionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StandardsControlAssociationIds": Sequence[StandardsControlAssociationIdTypeDef],
     },
 )
 
-GetFindingAggregatorResponseTypeDef = TypedDict(
-    "GetFindingAggregatorResponseTypeDef",
+_RequiredUnprocessedStandardsControlAssociationTypeDef = TypedDict(
+    "_RequiredUnprocessedStandardsControlAssociationTypeDef",
     {
-        "FindingAggregatorArn": str,
-        "FindingAggregationRegion": str,
-        "RegionLinkingMode": str,
-        "Regions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "StandardsControlAssociationId": StandardsControlAssociationIdTypeDef,
+        "ErrorCode": UnprocessedErrorCodeType,
     },
 )
-
-GetInvitationsCountResponseTypeDef = TypedDict(
-    "GetInvitationsCountResponseTypeDef",
+_OptionalUnprocessedStandardsControlAssociationTypeDef = TypedDict(
+    "_OptionalUnprocessedStandardsControlAssociationTypeDef",
     {
-        "InvitationsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListEnabledProductsForImportResponseTypeDef = TypedDict(
-    "ListEnabledProductsForImportResponseTypeDef",
-    {
-        "ProductSubscriptions": List[str],
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
+        "ErrorReason": str,
     },
+    total=False,
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateFindingAggregatorResponseTypeDef = TypedDict(
-    "UpdateFindingAggregatorResponseTypeDef",
-    {
-        "FindingAggregatorArn": str,
-        "FindingAggregationRegion": str,
-        "RegionLinkingMode": str,
-        "Regions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UnprocessedStandardsControlAssociationTypeDef(
+    _RequiredUnprocessedStandardsControlAssociationTypeDef,
+    _OptionalUnprocessedStandardsControlAssociationTypeDef,
+):
+    pass
 
-BatchEnableStandardsRequestRequestTypeDef = TypedDict(
-    "BatchEnableStandardsRequestRequestTypeDef",
-    {
-        "StandardsSubscriptionRequests": Sequence[StandardsSubscriptionRequestTypeDef],
-    },
-)
 
 BatchImportFindingsResponseTypeDef = TypedDict(
     "BatchImportFindingsResponseTypeDef",
     {
         "FailedCount": int,
         "SuccessCount": int,
         "FailedFindings": List[ImportFindingsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
-    "_RequiredBatchUpdateFindingsRequestRequestTypeDef",
+BatchUpdateStandardsControlAssociationsRequestRequestTypeDef = TypedDict(
+    "BatchUpdateStandardsControlAssociationsRequestRequestTypeDef",
     {
-        "FindingIdentifiers": Sequence[AwsSecurityFindingIdentifierTypeDef],
+        "StandardsControlAssociationUpdates": Sequence[StandardsControlAssociationUpdateTypeDef],
     },
 )
-_OptionalBatchUpdateFindingsRequestRequestTypeDef = TypedDict(
-    "_OptionalBatchUpdateFindingsRequestRequestTypeDef",
+
+_RequiredUnprocessedStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_RequiredUnprocessedStandardsControlAssociationUpdateTypeDef",
     {
-        "Note": NoteUpdateTypeDef,
-        "Severity": SeverityUpdateTypeDef,
-        "VerificationState": VerificationStateType,
-        "Confidence": int,
-        "Criticality": int,
-        "Types": Sequence[str],
-        "UserDefinedFields": Mapping[str, str],
-        "Workflow": WorkflowUpdateTypeDef,
-        "RelatedFindings": Sequence[RelatedFindingTypeDef],
+        "StandardsControlAssociationUpdate": StandardsControlAssociationUpdateTypeDef,
+        "ErrorCode": UnprocessedErrorCodeType,
+    },
+)
+_OptionalUnprocessedStandardsControlAssociationUpdateTypeDef = TypedDict(
+    "_OptionalUnprocessedStandardsControlAssociationUpdateTypeDef",
+    {
+        "ErrorReason": str,
     },
     total=False,
 )
 
-class BatchUpdateFindingsRequestRequestTypeDef(
-    _RequiredBatchUpdateFindingsRequestRequestTypeDef,
-    _OptionalBatchUpdateFindingsRequestRequestTypeDef,
+
+class UnprocessedStandardsControlAssociationUpdateTypeDef(
+    _RequiredUnprocessedStandardsControlAssociationUpdateTypeDef,
+    _OptionalUnprocessedStandardsControlAssociationUpdateTypeDef,
 ):
     pass
 
+
 ComplianceTypeDef = TypedDict(
     "ComplianceTypeDef",
     {
         "Status": ComplianceStatusType,
         "RelatedRequirements": Sequence[str],
         "StatusReasons": Sequence[StatusReasonTypeDef],
         "SecurityControlId": str,
@@ -6052,180 +7034,75 @@
     total=False,
 )
 
 CreateMembersResponseTypeDef = TypedDict(
     "CreateMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeclineInvitationsResponseTypeDef = TypedDict(
     "DeclineInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInvitationsResponseTypeDef = TypedDict(
     "DeleteInvitationsResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteMembersResponseTypeDef = TypedDict(
     "DeleteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteMembersResponseTypeDef = TypedDict(
     "InviteMembersResponseTypeDef",
     {
         "UnprocessedAccounts": List[ResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DateFilterTypeDef = TypedDict(
     "DateFilterTypeDef",
     {
         "Start": str,
         "End": str,
         "DateRange": DateRangeTypeDef,
     },
     total=False,
 )
 
-DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef = TypedDict(
-    "DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef",
-    {
-        "ActionTargetArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeProductsRequestDescribeProductsPaginateTypeDef = TypedDict(
-    "DescribeProductsRequestDescribeProductsPaginateTypeDef",
-    {
-        "ProductArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
-    {
-        "StandardsSubscriptionArn": str,
-    },
-)
-_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef(
-    _RequiredDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
-    _OptionalDescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
-):
-    pass
-
-DescribeStandardsRequestDescribeStandardsPaginateTypeDef = TypedDict(
-    "DescribeStandardsRequestDescribeStandardsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef = TypedDict(
-    "GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef",
-    {
-        "StandardsSubscriptionArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetInsightsRequestGetInsightsPaginateTypeDef = TypedDict(
-    "GetInsightsRequestGetInsightsPaginateTypeDef",
-    {
-        "InsightArns": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef = TypedDict(
-    "ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef = TypedDict(
-    "ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef",
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
-ListMembersRequestListMembersPaginateTypeDef = TypedDict(
-    "ListMembersRequestListMembersPaginateTypeDef",
-    {
-        "OnlyAssociated": bool,
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
 DescribeProductsResponseTypeDef = TypedDict(
     "DescribeProductsResponseTypeDef",
     {
         "Products": List[ProductTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStandardsControlsResponseTypeDef = TypedDict(
     "DescribeStandardsControlsResponseTypeDef",
     {
         "Controls": List[StandardsControlTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ThreatTypeDef = TypedDict(
     "ThreatTypeDef",
     {
         "Name": str,
@@ -6237,18 +7114,31 @@
 )
 
 ListFindingAggregatorsResponseTypeDef = TypedDict(
     "ListFindingAggregatorsResponseTypeDef",
     {
         "FindingAggregators": List[FindingAggregatorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+FindingHistoryRecordTypeDef = TypedDict(
+    "FindingHistoryRecordTypeDef",
+    {
+        "FindingIdentifier": AwsSecurityFindingIdentifierTypeDef,
+        "UpdateTime": datetime,
+        "FindingCreated": bool,
+        "UpdateSource": FindingHistoryUpdateSourceTypeDef,
+        "Updates": List[FindingHistoryUpdateTypeDef],
+        "NextToken": str,
+    },
+    total=False,
+)
+
 FindingProviderFieldsTypeDef = TypedDict(
     "FindingProviderFieldsTypeDef",
     {
         "Confidence": int,
         "Criticality": int,
         "RelatedFindings": Sequence[RelatedFindingTypeDef],
         "Severity": FindingProviderSeverityTypeDef,
@@ -6257,62 +7147,80 @@
     total=False,
 )
 
 GetAdministratorAccountResponseTypeDef = TypedDict(
     "GetAdministratorAccountResponseTypeDef",
     {
         "Administrator": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMasterAccountResponseTypeDef = TypedDict(
     "GetMasterAccountResponseTypeDef",
     {
         "Master": InvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
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
 
 GetMembersResponseTypeDef = TypedDict(
     "GetMembersResponseTypeDef",
     {
         "Members": List[MemberTypeDef],
         "UnprocessedAccounts": List[ResultTypeDef],
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
 
 InsightResultsTypeDef = TypedDict(
     "InsightResultsTypeDef",
     {
         "InsightArn": str,
         "GroupByAttribute": str,
         "ResultValues": List[InsightResultValueTypeDef],
     },
 )
 
+ListSecurityControlDefinitionsResponseTypeDef = TypedDict(
+    "ListSecurityControlDefinitionsResponseTypeDef",
+    {
+        "SecurityControlDefinitions": List[SecurityControlDefinitionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListStandardsControlAssociationsResponseTypeDef = TypedDict(
+    "ListStandardsControlAssociationsResponseTypeDef",
+    {
+        "StandardsControlAssociationSummaries": List[StandardsControlAssociationSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NetworkPathComponentDetailsTypeDef = TypedDict(
     "NetworkPathComponentDetailsTypeDef",
     {
         "Address": Sequence[str],
         "PortRanges": Sequence[PortRangeTypeDef],
     },
     total=False,
@@ -6414,19 +7322,21 @@
     "_OptionalStandardsSubscriptionTypeDef",
     {
         "StandardsStatusReason": StandardsStatusReasonTypeDef,
     },
     total=False,
 )
 
+
 class StandardsSubscriptionTypeDef(
     _RequiredStandardsSubscriptionTypeDef, _OptionalStandardsSubscriptionTypeDef
 ):
     pass
 
+
 StatelessCustomPublishMetricActionTypeDef = TypedDict(
     "StatelessCustomPublishMetricActionTypeDef",
     {
         "Dimensions": Sequence[StatelessCustomPublishMetricActionDimensionTypeDef],
     },
     total=False,
 )
@@ -6484,17 +7394,87 @@
         "Vendor": VulnerabilityVendorTypeDef,
         "ReferenceUrls": Sequence[str],
         "FixAvailable": VulnerabilityFixAvailableType,
     },
     total=False,
 )
 
+
 class VulnerabilityTypeDef(_RequiredVulnerabilityTypeDef, _OptionalVulnerabilityTypeDef):
     pass
 
+
+AwsEc2RouteTableDetailsTypeDef = TypedDict(
+    "AwsEc2RouteTableDetailsTypeDef",
+    {
+        "AssociationSet": Sequence[AssociationSetDetailsTypeDef],
+        "OwnerId": str,
+        "PropagatingVgwSet": Sequence[PropagatingVgwSetDetailsTypeDef],
+        "RouteTableId": str,
+        "RouteSet": Sequence[RouteSetDetailsTypeDef],
+        "VpcId": str,
+    },
+    total=False,
+)
+
+AutomationRulesActionTypeDef = TypedDict(
+    "AutomationRulesActionTypeDef",
+    {
+        "Type": Literal["FINDING_FIELDS_UPDATE"],
+        "FindingFieldsUpdate": AutomationRulesFindingFieldsUpdateTypeDef,
+    },
+    total=False,
+)
+
+AwsAmazonMqBrokerDetailsTypeDef = TypedDict(
+    "AwsAmazonMqBrokerDetailsTypeDef",
+    {
+        "AuthenticationStrategy": str,
+        "AutoMinorVersionUpgrade": bool,
+        "BrokerArn": str,
+        "BrokerName": str,
+        "DeploymentMode": str,
+        "EncryptionOptions": AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef,
+        "EngineType": str,
+        "EngineVersion": str,
+        "HostInstanceType": str,
+        "BrokerId": str,
+        "LdapServerMetadata": AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef,
+        "Logs": AwsAmazonMqBrokerLogsDetailsTypeDef,
+        "MaintenanceWindowStartTime": AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef,
+        "PubliclyAccessible": bool,
+        "SecurityGroups": Sequence[str],
+        "StorageType": str,
+        "SubnetIds": Sequence[str],
+        "Users": Sequence[AwsAmazonMqBrokerUsersDetailsTypeDef],
+    },
+    total=False,
+)
+
+AwsAppSyncGraphQlApiDetailsTypeDef = TypedDict(
+    "AwsAppSyncGraphQlApiDetailsTypeDef",
+    {
+        "ApiId": str,
+        "Id": str,
+        "OpenIdConnectConfig": AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef,
+        "Name": str,
+        "LambdaAuthorizerConfig": AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef,
+        "XrayEnabled": bool,
+        "Arn": str,
+        "UserPoolConfig": AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef,
+        "AuthenticationType": str,
+        "LogConfig": AwsAppSyncGraphQlApiLogConfigDetailsTypeDef,
+        "AdditionalAuthenticationProviders": Sequence[
+            AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef
+        ],
+        "WafWebAclArn": str,
+    },
+    total=False,
+)
+
 AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef = TypedDict(
     "AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef",
     {
         "InstancesDistribution": (
             AwsAutoScalingAutoScalingGroupMixedInstancesPolicyInstancesDistributionDetailsTypeDef
         ),
         "LaunchTemplate": (
@@ -6908,14 +7888,23 @@
         "SourceSecurityGroup": AwsElbLoadBalancerSourceSecurityGroupTypeDef,
         "Subnets": Sequence[str],
         "VpcId": str,
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef",
+    {
+        "ScanEc2InstanceWithFindings": AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef,
+        "ServiceRole": str,
+    },
+    total=False,
+)
+
 AwsIamAccessKeyDetailsTypeDef = TypedDict(
     "AwsIamAccessKeyDetailsTypeDef",
     {
         "UserName": str,
         "Status": AwsIamAccessKeyStatusType,
         "CreatedAt": str,
         "PrincipalId": str,
@@ -7077,14 +8066,23 @@
     "AwsS3BucketNotificationConfigurationFilterTypeDef",
     {
         "S3KeyFilter": AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef,
     },
     total=False,
 )
 
+AwsS3BucketObjectLockConfigurationTypeDef = TypedDict(
+    "AwsS3BucketObjectLockConfigurationTypeDef",
+    {
+        "ObjectLockEnabled": str,
+        "Rule": AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsS3BucketServerSideEncryptionConfigurationTypeDef = TypedDict(
     "AwsS3BucketServerSideEncryptionConfigurationTypeDef",
     {
         "Rules": Sequence[AwsS3BucketServerSideEncryptionRuleTypeDef],
     },
     total=False,
 )
@@ -7101,26 +8099,38 @@
 )
 
 BatchUpdateFindingsResponseTypeDef = TypedDict(
     "BatchUpdateFindingsResponseTypeDef",
     {
         "ProcessedFindings": List[AwsSecurityFindingIdentifierTypeDef],
         "UnprocessedFindings": List[BatchUpdateFindingsUnprocessedFindingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsSsmPatchComplianceDetailsTypeDef = TypedDict(
     "AwsSsmPatchComplianceDetailsTypeDef",
     {
         "Patch": AwsSsmPatchTypeDef,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef",
+    {
+        "Destinations": Sequence[
+            AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef
+        ],
+        "IncludeExecutionData": bool,
+        "Level": str,
+    },
+    total=False,
+)
+
 AwsWafRegionalRuleGroupDetailsTypeDef = TypedDict(
     "AwsWafRegionalRuleGroupDetailsTypeDef",
     {
         "MetricName": str,
         "Name": str,
         "RuleGroupId": str,
         "Rules": Sequence[AwsWafRegionalRuleGroupRulesDetailsTypeDef],
@@ -7190,14 +8200,73 @@
     "AwsWafv2ActionBlockDetailsTypeDef",
     {
         "CustomResponse": AwsWafv2CustomResponseDetailsTypeDef,
     },
     total=False,
 )
 
+BatchGetStandardsControlAssociationsResponseTypeDef = TypedDict(
+    "BatchGetStandardsControlAssociationsResponseTypeDef",
+    {
+        "StandardsControlAssociationDetails": List[StandardsControlAssociationDetailTypeDef],
+        "UnprocessedAssociations": List[UnprocessedStandardsControlAssociationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchUpdateStandardsControlAssociationsResponseTypeDef = TypedDict(
+    "BatchUpdateStandardsControlAssociationsResponseTypeDef",
+    {
+        "UnprocessedAssociationUpdates": List[UnprocessedStandardsControlAssociationUpdateTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AutomationRulesFindingFiltersTypeDef = TypedDict(
+    "AutomationRulesFindingFiltersTypeDef",
+    {
+        "ProductArn": List[StringFilterTypeDef],
+        "AwsAccountId": List[StringFilterTypeDef],
+        "Id": List[StringFilterTypeDef],
+        "GeneratorId": List[StringFilterTypeDef],
+        "Type": List[StringFilterTypeDef],
+        "FirstObservedAt": List[DateFilterTypeDef],
+        "LastObservedAt": List[DateFilterTypeDef],
+        "CreatedAt": List[DateFilterTypeDef],
+        "UpdatedAt": List[DateFilterTypeDef],
+        "Confidence": List[NumberFilterTypeDef],
+        "Criticality": List[NumberFilterTypeDef],
+        "Title": List[StringFilterTypeDef],
+        "Description": List[StringFilterTypeDef],
+        "SourceUrl": List[StringFilterTypeDef],
+        "ProductName": List[StringFilterTypeDef],
+        "CompanyName": List[StringFilterTypeDef],
+        "SeverityLabel": List[StringFilterTypeDef],
+        "ResourceType": List[StringFilterTypeDef],
+        "ResourceId": List[StringFilterTypeDef],
+        "ResourcePartition": List[StringFilterTypeDef],
+        "ResourceRegion": List[StringFilterTypeDef],
+        "ResourceTags": List[MapFilterTypeDef],
+        "ResourceDetailsOther": List[MapFilterTypeDef],
+        "ComplianceStatus": List[StringFilterTypeDef],
+        "ComplianceSecurityControlId": List[StringFilterTypeDef],
+        "ComplianceAssociatedStandardsId": List[StringFilterTypeDef],
+        "VerificationState": List[StringFilterTypeDef],
+        "WorkflowStatus": List[StringFilterTypeDef],
+        "RecordState": List[StringFilterTypeDef],
+        "RelatedFindingsProductArn": List[StringFilterTypeDef],
+        "RelatedFindingsId": List[StringFilterTypeDef],
+        "NoteText": List[StringFilterTypeDef],
+        "NoteUpdatedAt": List[DateFilterTypeDef],
+        "NoteUpdatedBy": List[StringFilterTypeDef],
+        "UserDefinedFields": List[MapFilterTypeDef],
+    },
+    total=False,
+)
+
 AwsSecurityFindingFiltersTypeDef = TypedDict(
     "AwsSecurityFindingFiltersTypeDef",
     {
         "ProductArn": Sequence[StringFilterTypeDef],
         "AwsAccountId": Sequence[StringFilterTypeDef],
         "Id": Sequence[StringFilterTypeDef],
         "GeneratorId": Sequence[StringFilterTypeDef],
@@ -7294,19 +8363,28 @@
         "Sample": Sequence[BooleanFilterTypeDef],
         "ComplianceSecurityControlId": Sequence[StringFilterTypeDef],
         "ComplianceAssociatedStandardsId": Sequence[StringFilterTypeDef],
     },
     total=False,
 )
 
+GetFindingHistoryResponseTypeDef = TypedDict(
+    "GetFindingHistoryResponseTypeDef",
+    {
+        "Records": List[FindingHistoryRecordTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInsightResultsResponseTypeDef = TypedDict(
     "GetInsightResultsResponseTypeDef",
     {
         "InsightResults": InsightResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkHeaderTypeDef = TypedDict(
     "NetworkHeaderTypeDef",
     {
         "Protocol": str,
@@ -7338,40 +8416,40 @@
 )
 
 DescribeStandardsResponseTypeDef = TypedDict(
     "DescribeStandardsResponseTypeDef",
     {
         "Standards": List[StandardTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDisableStandardsResponseTypeDef = TypedDict(
     "BatchDisableStandardsResponseTypeDef",
     {
         "StandardsSubscriptions": List[StandardsSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchEnableStandardsResponseTypeDef = TypedDict(
     "BatchEnableStandardsResponseTypeDef",
     {
         "StandardsSubscriptions": List[StandardsSubscriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEnabledStandardsResponseTypeDef = TypedDict(
     "GetEnabledStandardsResponseTypeDef",
     {
         "StandardsSubscriptions": List[StandardsSubscriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StatelessCustomActionDefinitionTypeDef = TypedDict(
     "StatelessCustomActionDefinitionTypeDef",
     {
         "PublishMetricAction": StatelessCustomPublishMetricActionTypeDef,
@@ -7540,14 +8618,27 @@
         "RequiresCompatibilities": Sequence[str],
         "TaskRoleArn": str,
         "Volumes": Sequence[AwsEcsTaskDefinitionVolumesDetailsTypeDef],
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDataSourcesDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDataSourcesDetailsTypeDef",
+    {
+        "CloudTrail": AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef,
+        "DnsLogs": AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef,
+        "FlowLogs": AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef,
+        "Kubernetes": AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef,
+        "MalwareProtection": AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef,
+        "S3Logs": AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef,
+    },
+    total=False,
+)
+
 AwsRdsDbInstanceDetailsTypeDef = TypedDict(
     "AwsRdsDbInstanceDetailsTypeDef",
     {
         "AssociatedRoles": Sequence[AwsRdsDbInstanceAssociatedRoleTypeDef],
         "CACertificateIdentifier": str,
         "DBClusterIdentifier": str,
         "DBInstanceIdentifier": str,
@@ -7623,14 +8714,29 @@
         "Filter": AwsS3BucketNotificationConfigurationFilterTypeDef,
         "Destination": str,
         "Type": str,
     },
     total=False,
 )
 
+AwsStepFunctionStateMachineDetailsTypeDef = TypedDict(
+    "AwsStepFunctionStateMachineDetailsTypeDef",
+    {
+        "Label": str,
+        "LoggingConfiguration": AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef,
+        "Name": str,
+        "RoleArn": str,
+        "StateMachineArn": str,
+        "Status": str,
+        "TracingConfiguration": AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef,
+        "Type": str,
+    },
+    total=False,
+)
+
 AwsWafv2RulesActionDetailsTypeDef = TypedDict(
     "AwsWafv2RulesActionDetailsTypeDef",
     {
         "Allow": AwsWafv2ActionAllowDetailsTypeDef,
         "Block": AwsWafv2ActionBlockDetailsTypeDef,
         "Captcha": AwsWafv2RulesActionCaptchaDetailsTypeDef,
         "Count": AwsWafv2RulesActionCountDetailsTypeDef,
@@ -7643,29 +8749,103 @@
     {
         "Allow": AwsWafv2ActionAllowDetailsTypeDef,
         "Block": AwsWafv2ActionBlockDetailsTypeDef,
     },
     total=False,
 )
 
+AutomationRulesConfigTypeDef = TypedDict(
+    "AutomationRulesConfigTypeDef",
+    {
+        "RuleArn": str,
+        "RuleStatus": RuleStatusType,
+        "RuleOrder": int,
+        "RuleName": str,
+        "Description": str,
+        "IsTerminal": bool,
+        "Criteria": AutomationRulesFindingFiltersTypeDef,
+        "Actions": List[AutomationRulesActionTypeDef],
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "CreatedBy": str,
+    },
+    total=False,
+)
+
+_RequiredCreateAutomationRuleRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateAutomationRuleRequestRequestTypeDef",
+    {
+        "RuleOrder": int,
+        "RuleName": str,
+        "Description": str,
+        "Criteria": AutomationRulesFindingFiltersTypeDef,
+        "Actions": Sequence[AutomationRulesActionTypeDef],
+    },
+)
+_OptionalCreateAutomationRuleRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateAutomationRuleRequestRequestTypeDef",
+    {
+        "Tags": Mapping[str, str],
+        "RuleStatus": RuleStatusType,
+        "IsTerminal": bool,
+    },
+    total=False,
+)
+
+
+class CreateAutomationRuleRequestRequestTypeDef(
+    _RequiredCreateAutomationRuleRequestRequestTypeDef,
+    _OptionalCreateAutomationRuleRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredUpdateAutomationRulesRequestItemTypeDef = TypedDict(
+    "_RequiredUpdateAutomationRulesRequestItemTypeDef",
+    {
+        "RuleArn": str,
+    },
+)
+_OptionalUpdateAutomationRulesRequestItemTypeDef = TypedDict(
+    "_OptionalUpdateAutomationRulesRequestItemTypeDef",
+    {
+        "RuleStatus": RuleStatusType,
+        "RuleOrder": int,
+        "Description": str,
+        "RuleName": str,
+        "IsTerminal": bool,
+        "Criteria": AutomationRulesFindingFiltersTypeDef,
+        "Actions": Sequence[AutomationRulesActionTypeDef],
+    },
+    total=False,
+)
+
+
+class UpdateAutomationRulesRequestItemTypeDef(
+    _RequiredUpdateAutomationRulesRequestItemTypeDef,
+    _OptionalUpdateAutomationRulesRequestItemTypeDef,
+):
+    pass
+
+
 CreateInsightRequestRequestTypeDef = TypedDict(
     "CreateInsightRequestRequestTypeDef",
     {
         "Name": str,
         "Filters": AwsSecurityFindingFiltersTypeDef,
         "GroupByAttribute": str,
     },
 )
 
 GetFindingsRequestGetFindingsPaginateTypeDef = TypedDict(
     "GetFindingsRequestGetFindingsPaginateTypeDef",
     {
         "Filters": AwsSecurityFindingFiltersTypeDef,
         "SortCriteria": Sequence[SortCriterionTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetFindingsRequestRequestTypeDef = TypedDict(
     "GetFindingsRequestRequestTypeDef",
     {
@@ -7698,19 +8878,21 @@
     {
         "Note": NoteUpdateTypeDef,
         "RecordState": RecordStateType,
     },
     total=False,
 )
 
+
 class UpdateFindingsRequestRequestTypeDef(
     _RequiredUpdateFindingsRequestRequestTypeDef, _OptionalUpdateFindingsRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateInsightRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateInsightRequestRequestTypeDef",
     {
         "InsightArn": str,
     },
 )
 _OptionalUpdateInsightRequestRequestTypeDef = TypedDict(
@@ -7719,19 +8901,21 @@
         "Name": str,
         "Filters": AwsSecurityFindingFiltersTypeDef,
         "GroupByAttribute": str,
     },
     total=False,
 )
 
+
 class UpdateInsightRequestRequestTypeDef(
     _RequiredUpdateInsightRequestRequestTypeDef, _OptionalUpdateInsightRequestRequestTypeDef
 ):
     pass
 
+
 NetworkPathComponentTypeDef = TypedDict(
     "NetworkPathComponentTypeDef",
     {
         "ComponentId": str,
         "ComponentType": str,
         "Egress": NetworkHeaderTypeDef,
         "Ingress": NetworkHeaderTypeDef,
@@ -7825,14 +9009,26 @@
         "ViewerCertificate": AwsCloudFrontDistributionViewerCertificateTypeDef,
         "Status": str,
         "WebAclId": str,
     },
     total=False,
 )
 
+AwsGuardDutyDetectorDetailsTypeDef = TypedDict(
+    "AwsGuardDutyDetectorDetailsTypeDef",
+    {
+        "DataSources": AwsGuardDutyDetectorDataSourcesDetailsTypeDef,
+        "Features": Sequence[AwsGuardDutyDetectorFeaturesDetailsTypeDef],
+        "FindingPublishingFrequency": str,
+        "ServiceRole": str,
+        "Status": str,
+    },
+    total=False,
+)
+
 AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef = TypedDict(
     "AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef",
     {
         "AbortIncompleteMultipartUpload": (
             AwsS3BucketBucketLifecycleConfigurationRulesAbortIncompleteMultipartUploadDetailsTypeDef
         ),
         "ExpirationDate": str,
@@ -7869,20 +9065,36 @@
         "OverrideAction": str,
         "Priority": int,
         "VisibilityConfig": AwsWafv2VisibilityConfigDetailsTypeDef,
     },
     total=False,
 )
 
+BatchGetAutomationRulesResponseTypeDef = TypedDict(
+    "BatchGetAutomationRulesResponseTypeDef",
+    {
+        "Rules": List[AutomationRulesConfigTypeDef],
+        "UnprocessedAutomationRules": List[UnprocessedAutomationRuleTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchUpdateAutomationRulesRequestRequestTypeDef = TypedDict(
+    "BatchUpdateAutomationRulesRequestRequestTypeDef",
+    {
+        "UpdateAutomationRulesRequestItems": Sequence[UpdateAutomationRulesRequestItemTypeDef],
+    },
+)
+
 GetInsightsResponseTypeDef = TypedDict(
     "GetInsightsResponseTypeDef",
     {
         "Insights": List[InsightTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CustomDataIdentifiersResultTypeDef = TypedDict(
     "CustomDataIdentifiersResultTypeDef",
     {
         "Detections": Sequence[CustomDataIdentifiersDetectionsTypeDef],
@@ -8015,14 +9227,15 @@
         "BucketLifecycleConfiguration": AwsS3BucketBucketLifecycleConfigurationDetailsTypeDef,
         "PublicAccessBlockConfiguration": AwsS3AccountPublicAccessBlockDetailsTypeDef,
         "AccessControlList": str,
         "BucketLoggingConfiguration": AwsS3BucketLoggingConfigurationTypeDef,
         "BucketWebsiteConfiguration": AwsS3BucketWebsiteConfigurationTypeDef,
         "BucketNotificationConfiguration": AwsS3BucketNotificationConfigurationTypeDef,
         "BucketVersioningConfiguration": AwsS3BucketBucketVersioningConfigurationTypeDef,
+        "ObjectLockConfiguration": AwsS3BucketObjectLockConfigurationTypeDef,
     },
     total=False,
 )
 
 DataClassificationDetailsTypeDef = TypedDict(
     "DataClassificationDetailsTypeDef",
     {
@@ -8137,14 +9350,20 @@
         "AwsBackupBackupVault": AwsBackupBackupVaultDetailsTypeDef,
         "AwsBackupBackupPlan": AwsBackupBackupPlanDetailsTypeDef,
         "AwsBackupRecoveryPoint": AwsBackupRecoveryPointDetailsTypeDef,
         "AwsEc2LaunchTemplate": AwsEc2LaunchTemplateDetailsTypeDef,
         "AwsSageMakerNotebookInstance": AwsSageMakerNotebookInstanceDetailsTypeDef,
         "AwsWafv2WebAcl": AwsWafv2WebAclDetailsTypeDef,
         "AwsWafv2RuleGroup": AwsWafv2RuleGroupDetailsTypeDef,
+        "AwsEc2RouteTable": AwsEc2RouteTableDetailsTypeDef,
+        "AwsAmazonMqBroker": AwsAmazonMqBrokerDetailsTypeDef,
+        "AwsAppSyncGraphQlApi": AwsAppSyncGraphQlApiDetailsTypeDef,
+        "AwsEventSchemasRegistry": AwsEventSchemasRegistryDetailsTypeDef,
+        "AwsGuardDutyDetector": AwsGuardDutyDetectorDetailsTypeDef,
+        "AwsStepFunctionStateMachine": AwsStepFunctionStateMachineDetailsTypeDef,
     },
     total=False,
 )
 
 _RequiredResourceTypeDef = TypedDict(
     "_RequiredResourceTypeDef",
     {
@@ -8161,17 +9380,19 @@
         "Tags": Mapping[str, str],
         "DataClassification": DataClassificationDetailsTypeDef,
         "Details": ResourceDetailsTypeDef,
     },
     total=False,
 )
 
+
 class ResourceTypeDef(_RequiredResourceTypeDef, _OptionalResourceTypeDef):
     pass
 
+
 _RequiredAwsSecurityFindingTypeDef = TypedDict(
     "_RequiredAwsSecurityFindingTypeDef",
     {
         "SchemaVersion": str,
         "Id": str,
         "ProductArn": str,
         "GeneratorId": str,
@@ -8217,27 +9438,29 @@
         "Action": ActionTypeDef,
         "FindingProviderFields": FindingProviderFieldsTypeDef,
         "Sample": bool,
     },
     total=False,
 )
 
+
 class AwsSecurityFindingTypeDef(
     _RequiredAwsSecurityFindingTypeDef, _OptionalAwsSecurityFindingTypeDef
 ):
     pass
 
+
 BatchImportFindingsRequestRequestTypeDef = TypedDict(
     "BatchImportFindingsRequestRequestTypeDef",
     {
         "Findings": Sequence[AwsSecurityFindingTypeDef],
     },
 )
 
 GetFindingsResponseTypeDef = TypedDict(
     "GetFindingsResponseTypeDef",
     {
         "Findings": List[AwsSecurityFindingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/PKG-INFO` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-securityhub
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SecurityHub 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SecurityHub 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-securityhub"></a>
 
 # types-aiobotocore-securityhub
 
 [![PyPI - types-aiobotocore-securityhub](https://img.shields.io/pypi/v/types-aiobotocore-securityhub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securityhub)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-securityhub.svg?color=blue)](https://pypi.org/project/types-aiobotocore-securityhub)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-securityhub?color=blue)](https://pypistats.org/packages/types-aiobotocore-securityhub)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecurityHub 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub)
+[aiobotocore.SecurityHub 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/securityhub.html#SecurityHub)
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
 [types-aiobotocore-securityhub docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_securityhub/).
 
 See how it helps to find and fix potential bugs:
 
@@ -278,21 +278,24 @@
 from types_aiobotocore_securityhub import SecurityHubClient
 from types_aiobotocore_securityhub.paginator import (
     DescribeActionTargetsPaginator,
     DescribeProductsPaginator,
     DescribeStandardsPaginator,
     DescribeStandardsControlsPaginator,
     GetEnabledStandardsPaginator,
+    GetFindingHistoryPaginator,
     GetFindingsPaginator,
     GetInsightsPaginator,
     ListEnabledProductsForImportPaginator,
     ListFindingAggregatorsPaginator,
     ListInvitationsPaginator,
     ListMembersPaginator,
     ListOrganizationAdminAccountsPaginator,
+    ListSecurityControlDefinitionsPaginator,
+    ListStandardsControlAssociationsPaginator,
 )
 
 session = get_session()
 async with session.create_client("securityhub") as client:
     client: SecurityHubClient
 
     # Explicit type annotations are optional here
@@ -308,72 +311,91 @@
     )
     describe_standards_controls_paginator: DescribeStandardsControlsPaginator = (
         client.get_paginator("describe_standards_controls")
     )
     get_enabled_standards_paginator: GetEnabledStandardsPaginator = client.get_paginator(
         "get_enabled_standards"
     )
+    get_finding_history_paginator: GetFindingHistoryPaginator = client.get_paginator(
+        "get_finding_history"
+    )
     get_findings_paginator: GetFindingsPaginator = client.get_paginator("get_findings")
     get_insights_paginator: GetInsightsPaginator = client.get_paginator("get_insights")
     list_enabled_products_for_import_paginator: ListEnabledProductsForImportPaginator = (
         client.get_paginator("list_enabled_products_for_import")
     )
     list_finding_aggregators_paginator: ListFindingAggregatorsPaginator = client.get_paginator(
         "list_finding_aggregators"
     )
     list_invitations_paginator: ListInvitationsPaginator = client.get_paginator("list_invitations")
     list_members_paginator: ListMembersPaginator = client.get_paginator("list_members")
     list_organization_admin_accounts_paginator: ListOrganizationAdminAccountsPaginator = (
         client.get_paginator("list_organization_admin_accounts")
     )
+    list_security_control_definitions_paginator: ListSecurityControlDefinitionsPaginator = (
+        client.get_paginator("list_security_control_definitions")
+    )
+    list_standards_control_associations_paginator: ListStandardsControlAssociationsPaginator = (
+        client.get_paginator("list_standards_control_associations")
+    )
 ```
 
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_securityhub.literals` module contains literals extracted
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_securityhub.literals import (
     AdminStatusType,
+    AssociationStatusType,
     AutoEnableStandardsType,
+    AutomationRulesActionTypeType,
     AwsIamAccessKeyStatusType,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleNameType,
     ComplianceStatusType,
+    ControlFindingGeneratorType,
     ControlStatusType,
     DateRangeUnitType,
     DescribeActionTargetsPaginatorName,
     DescribeProductsPaginatorName,
     DescribeStandardsControlsPaginatorName,
     DescribeStandardsPaginatorName,
+    FindingHistoryUpdateSourceTypeType,
     GetEnabledStandardsPaginatorName,
+    GetFindingHistoryPaginatorName,
     GetFindingsPaginatorName,
     GetInsightsPaginatorName,
     IntegrationTypeType,
     ListEnabledProductsForImportPaginatorName,
     ListFindingAggregatorsPaginatorName,
     ListInvitationsPaginatorName,
     ListMembersPaginatorName,
     ListOrganizationAdminAccountsPaginatorName,
+    ListSecurityControlDefinitionsPaginatorName,
+    ListStandardsControlAssociationsPaginatorName,
     MalwareStateType,
     MalwareTypeType,
     MapFilterComparisonType,
     NetworkDirectionType,
     PartitionType,
     RecordStateType,
+    RegionAvailabilityStatusType,
+    RuleStatusType,
     SeverityLabelType,
     SeverityRatingType,
     SortOrderType,
     StandardsStatusType,
     StatusReasonCodeType,
     StringFilterComparisonType,
     ThreatIntelIndicatorCategoryType,
     ThreatIntelIndicatorTypeType,
+    UnprocessedErrorCodeType,
     VerificationStateType,
     VulnerabilityFixAvailableType,
     WorkflowStateType,
     WorkflowStatusType,
     SecurityHubServiceName,
     ServiceName,
     ResourceServiceName,
@@ -406,22 +428,40 @@
     IpOrganizationDetailsTypeDef,
     ActionRemotePortDetailsTypeDef,
     ActionTargetTypeDef,
     DnsRequestActionTypeDef,
     AdjustmentTypeDef,
     AdminAccountTypeDef,
     AssociatedStandardTypeDef,
+    AssociationStateDetailsTypeDef,
+    NoteUpdateTypeDef,
+    RelatedFindingTypeDef,
+    SeverityUpdateTypeDef,
+    WorkflowUpdateTypeDef,
+    MapFilterTypeDef,
+    NumberFilterTypeDef,
+    StringFilterTypeDef,
+    AutomationRulesMetadataTypeDef,
     AvailabilityZoneTypeDef,
+    AwsAmazonMqBrokerEncryptionOptionsDetailsTypeDef,
+    AwsAmazonMqBrokerLdapServerMetadataDetailsTypeDef,
+    AwsAmazonMqBrokerMaintenanceWindowStartTimeDetailsTypeDef,
+    AwsAmazonMqBrokerUsersDetailsTypeDef,
+    AwsAmazonMqBrokerLogsPendingDetailsTypeDef,
     AwsApiCallActionDomainDetailsTypeDef,
     AwsApiGatewayAccessLogSettingsTypeDef,
     AwsApiGatewayCanarySettingsTypeDef,
     AwsApiGatewayEndpointConfigurationTypeDef,
     AwsApiGatewayMethodSettingsTypeDef,
     AwsCorsConfigurationTypeDef,
     AwsApiGatewayV2RouteSettingsTypeDef,
+    AwsAppSyncGraphQlApiLambdaAuthorizerConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiOpenIdConnectConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiUserPoolConfigDetailsTypeDef,
+    AwsAppSyncGraphQlApiLogConfigDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupAvailabilityZonesListDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupLaunchTemplateLaunchTemplateSpecificationTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyInstancesDistributionDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateLaunchTemplateSpecificationTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateOverridesListDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationBlockDeviceMappingsEbsDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationInstanceMonitoringDetailsTypeDef,
@@ -461,14 +501,15 @@
     AwsDynamoDbTableRestoreSummaryTypeDef,
     AwsDynamoDbTableSseDescriptionTypeDef,
     AwsDynamoDbTableStreamSpecificationTypeDef,
     AwsDynamoDbTableProjectionTypeDef,
     AwsDynamoDbTableProvisionedThroughputOverrideTypeDef,
     AwsEc2EipDetailsTypeDef,
     AwsEc2InstanceMetadataOptionsTypeDef,
+    AwsEc2InstanceMonitoringDetailsTypeDef,
     AwsEc2InstanceNetworkInterfacesDetailsTypeDef,
     AwsEc2LaunchTemplateDataBlockDeviceMappingSetEbsDetailsTypeDef,
     AwsEc2LaunchTemplateDataCapacityReservationSpecificationCapacityReservationTargetDetailsTypeDef,
     AwsEc2LaunchTemplateDataCpuOptionsDetailsTypeDef,
     AwsEc2LaunchTemplateDataCreditSpecificationDetailsTypeDef,
     AwsEc2LaunchTemplateDataElasticGpuSpecificationSetDetailsTypeDef,
     AwsEc2LaunchTemplateDataElasticInferenceAcceleratorSetDetailsTypeDef,
@@ -497,14 +538,16 @@
     AwsEc2NetworkAclAssociationTypeDef,
     IcmpTypeCodeTypeDef,
     PortRangeFromToTypeDef,
     AwsEc2NetworkInterfaceAttachmentTypeDef,
     AwsEc2NetworkInterfaceIpV6AddressDetailTypeDef,
     AwsEc2NetworkInterfacePrivateIpAddressDetailTypeDef,
     AwsEc2NetworkInterfaceSecurityGroupTypeDef,
+    PropagatingVgwSetDetailsTypeDef,
+    RouteSetDetailsTypeDef,
     AwsEc2SecurityGroupIpRangeTypeDef,
     AwsEc2SecurityGroupIpv6RangeTypeDef,
     AwsEc2SecurityGroupPrefixListIdTypeDef,
     AwsEc2SecurityGroupUserIdGroupPairTypeDef,
     Ipv6CidrBlockAssociationTypeDef,
     AwsEc2TransitGatewayDetailsTypeDef,
     AwsEc2VolumeAttachmentTypeDef,
@@ -581,14 +624,22 @@
     AwsElbLoadBalancerBackendServerDescriptionTypeDef,
     AwsElbLoadBalancerHealthCheckTypeDef,
     AwsElbLoadBalancerInstanceTypeDef,
     AwsElbLoadBalancerSourceSecurityGroupTypeDef,
     AwsElbLoadBalancerListenerTypeDef,
     AwsElbv2LoadBalancerAttributeTypeDef,
     LoadBalancerStateTypeDef,
+    AwsEventSchemasRegistryDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesCloudTrailDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesDnsLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesFlowLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesS3LogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesKubernetesAuditLogsDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsEbsVolumesDetailsTypeDef,
+    AwsGuardDutyDetectorFeaturesDetailsTypeDef,
     AwsIamAccessKeySessionContextAttributesTypeDef,
     AwsIamAccessKeySessionContextSessionIssuerTypeDef,
     AwsIamAttachedManagedPolicyTypeDef,
     AwsIamGroupPolicyTypeDef,
     AwsIamInstanceProfileRoleTypeDef,
     AwsIamPermissionsBoundaryTypeDef,
     AwsIamPolicyVersionTypeDef,
@@ -648,39 +699,38 @@
     AwsS3BucketBucketLifecycleConfigurationRulesNoncurrentVersionTransitionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesTransitionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateTagDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsTagDetailsTypeDef,
     AwsS3BucketBucketVersioningConfigurationTypeDef,
     AwsS3BucketLoggingConfigurationTypeDef,
     AwsS3BucketNotificationConfigurationS3KeyFilterRuleTypeDef,
+    AwsS3BucketObjectLockConfigurationRuleDefaultRetentionDetailsTypeDef,
     AwsS3BucketServerSideEncryptionByDefaultTypeDef,
     AwsS3BucketWebsiteConfigurationRedirectToTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleConditionTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleRedirectTypeDef,
     AwsS3ObjectDetailsTypeDef,
     AwsSageMakerNotebookInstanceMetadataServiceConfigurationDetailsTypeDef,
     AwsSecretsManagerSecretRotationRulesTypeDef,
     BooleanFilterTypeDef,
     IpFilterTypeDef,
     KeywordFilterTypeDef,
-    MapFilterTypeDef,
-    NumberFilterTypeDef,
-    StringFilterTypeDef,
     AwsSecurityFindingIdentifierTypeDef,
     MalwareTypeDef,
     NoteTypeDef,
     PatchSummaryTypeDef,
     ProcessDetailsTypeDef,
-    RelatedFindingTypeDef,
     SeverityTypeDef,
     ThreatIntelIndicatorTypeDef,
     WorkflowTypeDef,
     AwsSnsTopicSubscriptionTypeDef,
     AwsSqsQueueDetailsTypeDef,
     AwsSsmComplianceSummaryTypeDef,
+    AwsStepFunctionStateMachineTracingConfigurationDetailsTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDestinationsCloudWatchLogsLogGroupDetailsTypeDef,
     AwsWafRateBasedRuleMatchPredicateTypeDef,
     AwsWafRegionalRateBasedRuleMatchPredicateTypeDef,
     AwsWafRegionalRulePredicateListDetailsTypeDef,
     AwsWafRegionalRuleGroupRulesActionDetailsTypeDef,
     AwsWafRegionalWebAclRulesListActionDetailsTypeDef,
     AwsWafRegionalWebAclRulesListOverrideActionDetailsTypeDef,
     AwsWafRulePredicateListDetailsTypeDef,
@@ -688,74 +738,113 @@
     WafActionTypeDef,
     WafExcludedRuleTypeDef,
     WafOverrideActionTypeDef,
     AwsWafv2CustomHttpHeaderTypeDef,
     AwsWafv2VisibilityConfigDetailsTypeDef,
     AwsWafv2WebAclCaptchaConfigImmunityTimePropertyDetailsTypeDef,
     AwsXrayEncryptionConfigDetailsTypeDef,
+    BatchDeleteAutomationRulesRequestRequestTypeDef,
+    UnprocessedAutomationRuleTypeDef,
     BatchDisableStandardsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     StandardsSubscriptionRequestTypeDef,
+    BatchGetAutomationRulesRequestRequestTypeDef,
+    BatchGetSecurityControlsRequestRequestTypeDef,
+    SecurityControlTypeDef,
+    UnprocessedSecurityControlTypeDef,
+    StandardsControlAssociationIdTypeDef,
+    StandardsControlAssociationDetailTypeDef,
     ImportFindingsErrorTypeDef,
-    NoteUpdateTypeDef,
-    SeverityUpdateTypeDef,
-    WorkflowUpdateTypeDef,
+    StandardsControlAssociationUpdateTypeDef,
     CellTypeDef,
     ClassificationStatusTypeDef,
     StatusReasonTypeDef,
     VolumeMountTypeDef,
     CreateActionTargetRequestRequestTypeDef,
+    CreateActionTargetResponseTypeDef,
+    CreateAutomationRuleResponseTypeDef,
     CreateFindingAggregatorRequestRequestTypeDef,
+    CreateFindingAggregatorResponseTypeDef,
+    CreateInsightResponseTypeDef,
     ResultTypeDef,
     DateRangeTypeDef,
     DeclineInvitationsRequestRequestTypeDef,
     DeleteActionTargetRequestRequestTypeDef,
+    DeleteActionTargetResponseTypeDef,
     DeleteFindingAggregatorRequestRequestTypeDef,
     DeleteInsightRequestRequestTypeDef,
+    DeleteInsightResponseTypeDef,
     DeleteInvitationsRequestRequestTypeDef,
     DeleteMembersRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef,
     DescribeActionTargetsRequestRequestTypeDef,
     DescribeHubRequestRequestTypeDef,
+    DescribeHubResponseTypeDef,
+    DescribeOrganizationConfigurationResponseTypeDef,
+    DescribeProductsRequestDescribeProductsPaginateTypeDef,
     DescribeProductsRequestRequestTypeDef,
     ProductTypeDef,
+    DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
     DescribeStandardsControlsRequestRequestTypeDef,
     StandardsControlTypeDef,
+    DescribeStandardsRequestDescribeStandardsPaginateTypeDef,
     DescribeStandardsRequestRequestTypeDef,
     DisableImportFindingsForProductRequestRequestTypeDef,
     DisableOrganizationAdminAccountRequestRequestTypeDef,
     DisassociateMembersRequestRequestTypeDef,
     EnableImportFindingsForProductRequestRequestTypeDef,
+    EnableImportFindingsForProductResponseTypeDef,
     EnableOrganizationAdminAccountRequestRequestTypeDef,
     EnableSecurityHubRequestRequestTypeDef,
     FilePathsTypeDef,
     FindingAggregatorTypeDef,
+    FindingHistoryUpdateSourceTypeDef,
+    FindingHistoryUpdateTypeDef,
     FindingProviderSeverityTypeDef,
     FirewallPolicyStatefulRuleGroupReferencesDetailsTypeDef,
     FirewallPolicyStatelessRuleGroupReferencesDetailsTypeDef,
     InvitationTypeDef,
+    GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef,
     GetEnabledStandardsRequestRequestTypeDef,
     GetFindingAggregatorRequestRequestTypeDef,
+    GetFindingAggregatorResponseTypeDef,
     SortCriterionTypeDef,
     GetInsightResultsRequestRequestTypeDef,
+    GetInsightsRequestGetInsightsPaginateTypeDef,
     GetInsightsRequestRequestTypeDef,
+    GetInvitationsCountResponseTypeDef,
     GetMembersRequestRequestTypeDef,
     MemberTypeDef,
     InsightResultValueTypeDef,
     InviteMembersRequestRequestTypeDef,
+    ListAutomationRulesRequestRequestTypeDef,
+    ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef,
     ListEnabledProductsForImportRequestRequestTypeDef,
+    ListEnabledProductsForImportResponseTypeDef,
+    ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef,
     ListFindingAggregatorsRequestRequestTypeDef,
+    ListInvitationsRequestListInvitationsPaginateTypeDef,
     ListInvitationsRequestRequestTypeDef,
+    ListMembersRequestListMembersPaginateTypeDef,
     ListMembersRequestRequestTypeDef,
+    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     ListOrganizationAdminAccountsRequestRequestTypeDef,
+    ListSecurityControlDefinitionsRequestListSecurityControlDefinitionsPaginateTypeDef,
+    ListSecurityControlDefinitionsRequestRequestTypeDef,
+    SecurityControlDefinitionTypeDef,
+    ListStandardsControlAssociationsRequestListStandardsControlAssociationsPaginateTypeDef,
+    ListStandardsControlAssociationsRequestRequestTypeDef,
+    StandardsControlAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     PortRangeTypeDef,
     RangeTypeDef,
     RecordTypeDef,
+    PaginatorConfigTypeDef,
     RecommendationTypeDef,
+    ResponseMetadataTypeDef,
     RuleGroupSourceListDetailsTypeDef,
     RuleGroupSourceStatefulRulesHeaderDetailsTypeDef,
     RuleGroupSourceStatefulRulesOptionsDetailsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesDestinationPortsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesDestinationsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesSourcePortsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesSourcesTypeDef,
@@ -766,25 +855,33 @@
     StandardsManagedByTypeDef,
     StandardsStatusReasonTypeDef,
     StatelessCustomPublishMetricActionDimensionTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateActionTargetRequestRequestTypeDef,
     UpdateFindingAggregatorRequestRequestTypeDef,
+    UpdateFindingAggregatorResponseTypeDef,
     UpdateOrganizationConfigurationRequestRequestTypeDef,
     UpdateSecurityHubConfigurationRequestRequestTypeDef,
     UpdateStandardsControlRequestRequestTypeDef,
     VulnerabilityVendorTypeDef,
     CreateMembersRequestRequestTypeDef,
     ActionRemoteIpDetailsTypeDef,
+    DescribeActionTargetsResponseTypeDef,
     CvssTypeDef,
+    ListOrganizationAdminAccountsResponseTypeDef,
+    AssociationSetDetailsTypeDef,
+    AutomationRulesFindingFieldsUpdateTypeDef,
+    ListAutomationRulesResponseTypeDef,
+    AwsAmazonMqBrokerLogsDetailsTypeDef,
     AwsApiGatewayRestApiDetailsTypeDef,
     AwsApiGatewayStageDetailsTypeDef,
     AwsApiGatewayV2ApiDetailsTypeDef,
     AwsApiGatewayV2StageDetailsTypeDef,
+    AwsAppSyncGraphQlApiAdditionalAuthenticationProvidersDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyLaunchTemplateDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationBlockDeviceMappingsDetailsTypeDef,
     AwsBackupBackupPlanRuleCopyActionsDetailsTypeDef,
     AwsBackupBackupVaultDetailsTypeDef,
     AwsBackupRecoveryPointDetailsTypeDef,
     AwsCertificateManagerCertificateDomainValidationOptionTypeDef,
     AwsCloudFormationStackDetailsTypeDef,
@@ -827,14 +924,16 @@
     AwsElasticBeanstalkEnvironmentDetailsTypeDef,
     AwsElasticsearchDomainElasticsearchClusterConfigDetailsTypeDef,
     AwsElasticsearchDomainLogPublishingOptionsTypeDef,
     AwsElbLoadBalancerPoliciesTypeDef,
     AwsElbLoadBalancerAttributesTypeDef,
     AwsElbLoadBalancerListenerDescriptionTypeDef,
     AwsElbv2LoadBalancerDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesKubernetesDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionScanEc2InstanceWithFindingsDetailsTypeDef,
     AwsIamAccessKeySessionContextTypeDef,
     AwsIamGroupDetailsTypeDef,
     AwsIamInstanceProfileTypeDef,
     AwsIamPolicyDetailsTypeDef,
     AwsIamUserDetailsTypeDef,
     AwsKinesisStreamDetailsTypeDef,
     AwsLambdaFunctionEnvironmentTypeDef,
@@ -846,94 +945,86 @@
     AwsRdsDbSnapshotDetailsTypeDef,
     AwsRdsDbPendingModifiedValuesTypeDef,
     AwsRdsDbSecurityGroupDetailsTypeDef,
     AwsRdsDbSubnetGroupSubnetTypeDef,
     AwsRedshiftClusterClusterParameterGroupTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateOperandsDetailsTypeDef,
     AwsS3BucketNotificationConfigurationS3KeyFilterTypeDef,
+    AwsS3BucketObjectLockConfigurationRuleDetailsTypeDef,
     AwsS3BucketServerSideEncryptionRuleTypeDef,
     AwsS3BucketWebsiteConfigurationRoutingRuleTypeDef,
     AwsSageMakerNotebookInstanceDetailsTypeDef,
     AwsSecretsManagerSecretDetailsTypeDef,
+    BatchUpdateFindingsRequestRequestTypeDef,
     BatchUpdateFindingsUnprocessedFindingTypeDef,
+    GetFindingHistoryRequestGetFindingHistoryPaginateTypeDef,
+    GetFindingHistoryRequestRequestTypeDef,
     AwsSnsTopicDetailsTypeDef,
     AwsSsmPatchTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDestinationsDetailsTypeDef,
     AwsWafRateBasedRuleDetailsTypeDef,
     AwsWafRegionalRateBasedRuleDetailsTypeDef,
     AwsWafRegionalRuleDetailsTypeDef,
     AwsWafRegionalRuleGroupRulesDetailsTypeDef,
     AwsWafRegionalWebAclRulesListDetailsTypeDef,
     AwsWafRuleDetailsTypeDef,
     AwsWafRuleGroupRulesDetailsTypeDef,
     AwsWafWebAclRuleTypeDef,
     AwsWafv2CustomRequestHandlingDetailsTypeDef,
     AwsWafv2CustomResponseDetailsTypeDef,
     AwsWafv2WebAclCaptchaConfigDetailsTypeDef,
-    CreateActionTargetResponseTypeDef,
-    CreateFindingAggregatorResponseTypeDef,
-    CreateInsightResponseTypeDef,
-    DeleteActionTargetResponseTypeDef,
-    DeleteInsightResponseTypeDef,
-    DescribeActionTargetsResponseTypeDef,
-    DescribeHubResponseTypeDef,
-    DescribeOrganizationConfigurationResponseTypeDef,
-    EnableImportFindingsForProductResponseTypeDef,
-    GetFindingAggregatorResponseTypeDef,
-    GetInvitationsCountResponseTypeDef,
-    ListEnabledProductsForImportResponseTypeDef,
-    ListOrganizationAdminAccountsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UpdateFindingAggregatorResponseTypeDef,
+    BatchDeleteAutomationRulesResponseTypeDef,
+    BatchUpdateAutomationRulesResponseTypeDef,
     BatchEnableStandardsRequestRequestTypeDef,
+    BatchGetSecurityControlsResponseTypeDef,
+    BatchGetStandardsControlAssociationsRequestRequestTypeDef,
+    UnprocessedStandardsControlAssociationTypeDef,
     BatchImportFindingsResponseTypeDef,
-    BatchUpdateFindingsRequestRequestTypeDef,
+    BatchUpdateStandardsControlAssociationsRequestRequestTypeDef,
+    UnprocessedStandardsControlAssociationUpdateTypeDef,
     ComplianceTypeDef,
     ContainerDetailsTypeDef,
     CreateMembersResponseTypeDef,
     DeclineInvitationsResponseTypeDef,
     DeleteInvitationsResponseTypeDef,
     DeleteMembersResponseTypeDef,
     InviteMembersResponseTypeDef,
     DateFilterTypeDef,
-    DescribeActionTargetsRequestDescribeActionTargetsPaginateTypeDef,
-    DescribeProductsRequestDescribeProductsPaginateTypeDef,
-    DescribeStandardsControlsRequestDescribeStandardsControlsPaginateTypeDef,
-    DescribeStandardsRequestDescribeStandardsPaginateTypeDef,
-    GetEnabledStandardsRequestGetEnabledStandardsPaginateTypeDef,
-    GetInsightsRequestGetInsightsPaginateTypeDef,
-    ListEnabledProductsForImportRequestListEnabledProductsForImportPaginateTypeDef,
-    ListFindingAggregatorsRequestListFindingAggregatorsPaginateTypeDef,
-    ListInvitationsRequestListInvitationsPaginateTypeDef,
-    ListMembersRequestListMembersPaginateTypeDef,
-    ListOrganizationAdminAccountsRequestListOrganizationAdminAccountsPaginateTypeDef,
     DescribeProductsResponseTypeDef,
     DescribeStandardsControlsResponseTypeDef,
     ThreatTypeDef,
     ListFindingAggregatorsResponseTypeDef,
+    FindingHistoryRecordTypeDef,
     FindingProviderFieldsTypeDef,
     GetAdministratorAccountResponseTypeDef,
     GetMasterAccountResponseTypeDef,
     ListInvitationsResponseTypeDef,
     GetMembersResponseTypeDef,
     ListMembersResponseTypeDef,
     InsightResultsTypeDef,
+    ListSecurityControlDefinitionsResponseTypeDef,
+    ListStandardsControlAssociationsResponseTypeDef,
     NetworkPathComponentDetailsTypeDef,
     NetworkTypeDef,
     PageTypeDef,
     RemediationTypeDef,
     RuleGroupSourceStatefulRulesDetailsTypeDef,
     RuleGroupSourceStatelessRuleMatchAttributesTypeDef,
     RuleGroupVariablesTypeDef,
     StandardTypeDef,
     StandardsSubscriptionTypeDef,
     StatelessCustomPublishMetricActionTypeDef,
     AwsApiCallActionTypeDef,
     NetworkConnectionActionTypeDef,
     PortProbeDetailTypeDef,
     VulnerabilityTypeDef,
+    AwsEc2RouteTableDetailsTypeDef,
+    AutomationRulesActionTypeDef,
+    AwsAmazonMqBrokerDetailsTypeDef,
+    AwsAppSyncGraphQlApiDetailsTypeDef,
     AwsAutoScalingAutoScalingGroupMixedInstancesPolicyDetailsTypeDef,
     AwsAutoScalingLaunchConfigurationDetailsTypeDef,
     AwsBackupBackupPlanRuleDetailsTypeDef,
     AwsCertificateManagerCertificateRenewalSummaryTypeDef,
     AwsCloudFrontDistributionOriginItemTypeDef,
     AwsCloudFrontDistributionOriginGroupTypeDef,
     AwsCodeBuildProjectDetailsTypeDef,
@@ -948,35 +1039,42 @@
     AwsEcsTaskDefinitionContainerDefinitionsDetailsTypeDef,
     AwsEcsTaskDefinitionVolumesDetailsTypeDef,
     AwsEcsTaskDetailsTypeDef,
     AwsEfsAccessPointDetailsTypeDef,
     AwsEksClusterDetailsTypeDef,
     AwsElasticsearchDomainDetailsTypeDef,
     AwsElbLoadBalancerDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesMalwareProtectionDetailsTypeDef,
     AwsIamAccessKeyDetailsTypeDef,
     AwsIamRoleDetailsTypeDef,
     AwsLambdaFunctionDetailsTypeDef,
     AwsOpenSearchServiceDomainDetailsTypeDef,
     AwsRdsDbSubnetGroupTypeDef,
     AwsRedshiftClusterDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterPredicateDetailsTypeDef,
     AwsS3BucketNotificationConfigurationFilterTypeDef,
+    AwsS3BucketObjectLockConfigurationTypeDef,
     AwsS3BucketServerSideEncryptionConfigurationTypeDef,
     AwsS3BucketWebsiteConfigurationTypeDef,
     BatchUpdateFindingsResponseTypeDef,
     AwsSsmPatchComplianceDetailsTypeDef,
+    AwsStepFunctionStateMachineLoggingConfigurationDetailsTypeDef,
     AwsWafRegionalRuleGroupDetailsTypeDef,
     AwsWafRegionalWebAclDetailsTypeDef,
     AwsWafRuleGroupDetailsTypeDef,
     AwsWafWebAclDetailsTypeDef,
     AwsWafv2ActionAllowDetailsTypeDef,
     AwsWafv2RulesActionCaptchaDetailsTypeDef,
     AwsWafv2RulesActionCountDetailsTypeDef,
     AwsWafv2ActionBlockDetailsTypeDef,
+    BatchGetStandardsControlAssociationsResponseTypeDef,
+    BatchUpdateStandardsControlAssociationsResponseTypeDef,
+    AutomationRulesFindingFiltersTypeDef,
     AwsSecurityFindingFiltersTypeDef,
+    GetFindingHistoryResponseTypeDef,
     GetInsightResultsResponseTypeDef,
     NetworkHeaderTypeDef,
     OccurrencesTypeDef,
     RuleGroupSourceStatelessRuleDefinitionTypeDef,
     DescribeStandardsResponseTypeDef,
     BatchDisableStandardsResponseTypeDef,
     BatchEnableStandardsResponseTypeDef,
@@ -988,19 +1086,24 @@
     AwsCertificateManagerCertificateDetailsTypeDef,
     AwsCloudFrontDistributionOriginsTypeDef,
     AwsCloudFrontDistributionOriginGroupsTypeDef,
     AwsDynamoDbTableDetailsTypeDef,
     AwsEc2LaunchTemplateDetailsTypeDef,
     AwsEcsClusterDetailsTypeDef,
     AwsEcsTaskDefinitionDetailsTypeDef,
+    AwsGuardDutyDetectorDataSourcesDetailsTypeDef,
     AwsRdsDbInstanceDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesFilterDetailsTypeDef,
     AwsS3BucketNotificationConfigurationDetailTypeDef,
+    AwsStepFunctionStateMachineDetailsTypeDef,
     AwsWafv2RulesActionDetailsTypeDef,
     AwsWafv2WebAclActionDetailsTypeDef,
+    AutomationRulesConfigTypeDef,
+    CreateAutomationRuleRequestRequestTypeDef,
+    UpdateAutomationRulesRequestItemTypeDef,
     CreateInsightRequestRequestTypeDef,
     GetFindingsRequestGetFindingsPaginateTypeDef,
     GetFindingsRequestRequestTypeDef,
     InsightTypeDef,
     UpdateFindingsRequestRequestTypeDef,
     UpdateInsightRequestRequestTypeDef,
     NetworkPathComponentTypeDef,
@@ -1008,17 +1111,20 @@
     SensitiveDataDetectionsTypeDef,
     RuleGroupSourceStatelessRulesDetailsTypeDef,
     FirewallPolicyStatelessCustomActionsDetailsTypeDef,
     RuleGroupSourceCustomActionsDetailsTypeDef,
     ActionTypeDef,
     AwsBackupBackupPlanDetailsTypeDef,
     AwsCloudFrontDistributionDetailsTypeDef,
+    AwsGuardDutyDetectorDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationRulesDetailsTypeDef,
     AwsS3BucketNotificationConfigurationTypeDef,
     AwsWafv2RulesDetailsTypeDef,
+    BatchGetAutomationRulesResponseTypeDef,
+    BatchUpdateAutomationRulesRequestRequestTypeDef,
     GetInsightsResponseTypeDef,
     CustomDataIdentifiersResultTypeDef,
     SensitiveDataResultTypeDef,
     FirewallPolicyDetailsTypeDef,
     RuleGroupSourceStatelessRulesAndCustomActionsDetailsTypeDef,
     AwsS3BucketBucketLifecycleConfigurationDetailsTypeDef,
     AwsWafv2RuleGroupDetailsTypeDef,
@@ -1045,43 +1151,43 @@
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

### Comparing `types-aiobotocore-securityhub-2.5.0.post1/types_aiobotocore_securityhub.egg-info/SOURCES.txt` & `types-aiobotocore-securityhub-2.5.1/types_aiobotocore_securityhub.egg-info/SOURCES.txt`

 * *Files identical despite different names*

