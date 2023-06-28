# Comparing `tmp/types-aiobotocore-config-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-config-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-config-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:26 2023, max compression
+gzip compressed data, was "types-aiobotocore-config-2.5.1.tar", last modified: Wed Jun 28 01:43:19 2023, max compression
```

## Comparing `types-aiobotocore-config-2.5.0.post1.tar` & `types-aiobotocore-config-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:26.911094 types-aiobotocore-config-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    37171 2023-03-11 12:26:26.907094 types-aiobotocore-config-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    35597 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:26.911094 types-aiobotocore-config-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:26.891094 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/
--rw-r--r--   0 runner    (1001) docker     (123)     9918 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9917 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      942 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    92629 2023-03-11 12:11:46.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    92497 2023-03-11 12:11:46.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    24221 2023-03-11 12:11:47.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    24219 2023-03-11 12:11:46.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    44542 2023-03-11 12:11:46.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    44508 2023-03-11 12:11:46.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   127451 2023-03-11 12:11:50.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   127300 2023-03-11 12:11:48.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:45.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:26.907094 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    37171 2023-03-11 12:26:26.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-03-11 12:26:26.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:26.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:26.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:26.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:26.000000 types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:19.166117 types-aiobotocore-config-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    37260 2023-06-28 01:43:19.166117 types-aiobotocore-config-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    35692 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:19.166117 types-aiobotocore-config-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:19.162117 types-aiobotocore-config-2.5.1/types_aiobotocore_config/
+-rw-r--r--   0 runner    (1001) docker     (123)     9918 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9917 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      930 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    92719 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    92587 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    30075 2023-06-28 01:28:24.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30073 2023-06-28 01:28:24.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    44508 2023-06-28 01:28:24.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    44475 2023-06-28 01:28:24.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   128192 2023-06-28 01:28:27.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   128041 2023-06-28 01:28:26.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:23.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:19.166117 types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    37260 2023-06-28 01:43:18.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-28 01:43:19.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:18.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:18.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:18.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:18.000000 types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-config-2.5.0.post1/LICENSE` & `types-aiobotocore-config-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-config-2.5.0.post1/PKG-INFO` & `types-aiobotocore-config-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-config
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConfigService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConfigService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-config"></a>
 
 # types-aiobotocore-config
 
 [![PyPI - types-aiobotocore-config](https://img.shields.io/pypi/v/types-aiobotocore-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConfigService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService)
+[aiobotocore.ConfigService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService)
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
 [types-aiobotocore-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -468,14 +468,15 @@
     OrganizationConfigRuleTriggerTypeNoSNType,
     OrganizationConfigRuleTriggerTypeType,
     OrganizationResourceDetailedStatusType,
     OrganizationResourceStatusType,
     OrganizationRuleStatusType,
     OwnerType,
     RecorderStatusType,
+    RecordingStrategyTypeType,
     RemediationExecutionStateType,
     RemediationExecutionStepStateType,
     RemediationTargetTypeType,
     ResourceConfigurationSchemaTypeType,
     ResourceCountGroupKeyType,
     ResourceEvaluationStatusType,
     ResourceTypeType,
@@ -510,29 +511,27 @@
     AggregateConformancePackComplianceCountTypeDef,
     AggregateConformancePackComplianceFiltersTypeDef,
     AggregateConformancePackComplianceSummaryFiltersTypeDef,
     AggregateResourceIdentifierTypeDef,
     AggregatedSourceStatusTypeDef,
     AggregationAuthorizationTypeDef,
     BaseConfigurationItemTypeDef,
-    ResponseMetadataTypeDef,
     ResourceKeyTypeDef,
     ComplianceContributorCountTypeDef,
     ConfigExportDeliveryInfoTypeDef,
     ConfigRuleComplianceFiltersTypeDef,
     ConfigRuleComplianceSummaryFiltersTypeDef,
     ConfigRuleEvaluationStatusTypeDef,
     EvaluationModeConfigurationTypeDef,
     ScopeTypeDef,
     ConfigSnapshotDeliveryPropertiesTypeDef,
     ConfigStreamDeliveryInfoTypeDef,
     OrganizationAggregationSourceTypeDef,
     RelationshipTypeDef,
     ConfigurationRecorderStatusTypeDef,
-    RecordingGroupTypeDef,
     ConformancePackComplianceFiltersTypeDef,
     ConformancePackComplianceScoreTypeDef,
     ConformancePackComplianceScoresFiltersTypeDef,
     ConformancePackComplianceSummaryTypeDef,
     ConformancePackInputParameterTypeDef,
     TemplateSSMDocumentDetailsTypeDef,
     ConformancePackEvaluationFiltersTypeDef,
@@ -551,128 +550,156 @@
     DeletePendingAggregationRequestRequestRequestTypeDef,
     DeleteRemediationConfigurationRequestRequestTypeDef,
     RemediationExceptionResourceKeyTypeDef,
     DeleteResourceConfigRequestRequestTypeDef,
     DeleteRetentionConfigurationRequestRequestTypeDef,
     DeleteStoredQueryRequestRequestTypeDef,
     DeliverConfigSnapshotRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeliverConfigSnapshotResponseTypeDef,
+    DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef,
     DescribeAggregationAuthorizationsRequestRequestTypeDef,
+    DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef,
     DescribeComplianceByConfigRuleRequestRequestTypeDef,
+    DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef,
     DescribeComplianceByResourceRequestRequestTypeDef,
+    DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef,
     DescribeConfigRuleEvaluationStatusRequestRequestTypeDef,
     DescribeConfigRulesFiltersTypeDef,
+    DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
     DescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef,
+    DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef,
     DescribeConfigurationAggregatorsRequestRequestTypeDef,
     DescribeConfigurationRecorderStatusRequestRequestTypeDef,
     DescribeConfigurationRecordersRequestRequestTypeDef,
+    DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef,
     DescribeConformancePackStatusRequestRequestTypeDef,
+    DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef,
     DescribeConformancePacksRequestRequestTypeDef,
     DescribeDeliveryChannelStatusRequestRequestTypeDef,
     DescribeDeliveryChannelsRequestRequestTypeDef,
+    DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef,
     DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef,
     OrganizationConfigRuleStatusTypeDef,
+    DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef,
     DescribeOrganizationConfigRulesRequestRequestTypeDef,
+    DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef,
     DescribeOrganizationConformancePackStatusesRequestRequestTypeDef,
     OrganizationConformancePackStatusTypeDef,
+    DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef,
     DescribeOrganizationConformancePacksRequestRequestTypeDef,
+    DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef,
     DescribePendingAggregationRequestsRequestRequestTypeDef,
     PendingAggregationRequestTypeDef,
     DescribeRemediationConfigurationsRequestRequestTypeDef,
     RemediationExceptionTypeDef,
+    DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef,
     DescribeRetentionConfigurationsRequestRequestTypeDef,
     RetentionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluationContextTypeDef,
     EvaluationResultQualifierTypeDef,
     EvaluationStatusTypeDef,
     EvaluationTypeDef,
+    ExclusionByResourceTypesTypeDef,
     SsmControlsTypeDef,
     ExternalEvaluationTypeDef,
     FieldInfoTypeDef,
+    GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
     GetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef,
     ResourceCountFiltersTypeDef,
     GroupedResourceCountTypeDef,
+    GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
     GetComplianceDetailsByConfigRuleRequestRequestTypeDef,
+    GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef,
     GetComplianceDetailsByResourceRequestRequestTypeDef,
     GetComplianceSummaryByResourceTypeRequestRequestTypeDef,
+    GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
     GetConformancePackComplianceSummaryRequestRequestTypeDef,
     GetCustomRulePolicyRequestRequestTypeDef,
+    GetCustomRulePolicyResponseTypeDef,
     GetDiscoveredResourceCountsRequestRequestTypeDef,
     ResourceCountTypeDef,
     StatusDetailFiltersTypeDef,
     MemberAccountStatusTypeDef,
     OrganizationResourceDetailedStatusFiltersTypeDef,
     OrganizationConformancePackDetailedStatusTypeDef,
     GetOrganizationCustomRulePolicyRequestRequestTypeDef,
+    GetOrganizationCustomRulePolicyResponseTypeDef,
+    GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
     GetResourceConfigHistoryRequestRequestTypeDef,
     GetResourceEvaluationSummaryRequestRequestTypeDef,
     ResourceDetailsTypeDef,
     GetStoredQueryRequestRequestTypeDef,
     StoredQueryTypeDef,
     ResourceFiltersTypeDef,
+    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
     ResourceIdentifierTypeDef,
     ResourceEvaluationTypeDef,
     ListStoredQueriesRequestRequestTypeDef,
     StoredQueryMetadataTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     OrganizationCustomPolicyRuleMetadataNoPolicyTypeDef,
     OrganizationCustomRuleMetadataTypeDef,
     OrganizationManagedRuleMetadataTypeDef,
     OrganizationCustomPolicyRuleMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    PutConformancePackResponseTypeDef,
+    PutOrganizationConfigRuleResponseTypeDef,
+    PutOrganizationConformancePackResponseTypeDef,
     PutResourceConfigRequestRequestTypeDef,
     PutRetentionConfigurationRequestRequestTypeDef,
+    PutStoredQueryResponseTypeDef,
+    RecordingStrategyTypeDef,
     RemediationExecutionStepTypeDef,
     ResourceValueTypeDef,
     StaticValueTypeDef,
     TimeWindowTypeDef,
+    ResponseMetadataTypeDef,
     SelectAggregateResourceConfigRequestRequestTypeDef,
+    SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
     SelectResourceConfigRequestRequestTypeDef,
+    SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
     SourceDetailTypeDef,
     StartConfigRulesEvaluationRequestRequestTypeDef,
     StartConfigurationRecorderRequestRequestTypeDef,
+    StartResourceEvaluationResponseTypeDef,
     StopConfigurationRecorderRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AggregateComplianceByConformancePackTypeDef,
     AggregateConformancePackComplianceSummaryTypeDef,
+    DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
     DescribeAggregateComplianceByConformancePacksRequestRequestTypeDef,
     GetAggregateConformancePackComplianceSummaryRequestRequestTypeDef,
     BatchGetAggregateResourceConfigRequestRequestTypeDef,
     GetAggregateResourceConfigRequestRequestTypeDef,
-    BatchGetAggregateResourceConfigResponseTypeDef,
-    DeliverConfigSnapshotResponseTypeDef,
-    DescribeAggregationAuthorizationsResponseTypeDef,
-    DescribeConfigurationAggregatorSourcesStatusResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCustomRulePolicyResponseTypeDef,
-    GetOrganizationCustomRulePolicyResponseTypeDef,
     ListAggregateDiscoveredResourcesResponseTypeDef,
+    DescribeConfigurationAggregatorSourcesStatusResponseTypeDef,
+    DescribeAggregationAuthorizationsResponseTypeDef,
     PutAggregationAuthorizationResponseTypeDef,
-    PutConformancePackResponseTypeDef,
-    PutOrganizationConfigRuleResponseTypeDef,
-    PutOrganizationConformancePackResponseTypeDef,
-    PutStoredQueryResponseTypeDef,
-    StartResourceEvaluationResponseTypeDef,
+    BatchGetAggregateResourceConfigResponseTypeDef,
     BatchGetResourceConfigRequestRequestTypeDef,
     BatchGetResourceConfigResponseTypeDef,
+    DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
     DescribeRemediationExecutionStatusRequestRequestTypeDef,
     StartRemediationExecutionRequestRequestTypeDef,
     StartRemediationExecutionResponseTypeDef,
     ComplianceSummaryTypeDef,
     ComplianceTypeDef,
+    DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
     DescribeAggregateComplianceByConfigRulesRequestRequestTypeDef,
     GetAggregateConfigRuleComplianceSummaryRequestRequestTypeDef,
     DescribeConfigRuleEvaluationStatusResponseTypeDef,
     DeliveryChannelTypeDef,
     DeliveryChannelStatusTypeDef,
     ConfigurationAggregatorTypeDef,
     ConfigurationItemTypeDef,
     DescribeConfigurationRecorderStatusResponseTypeDef,
-    ConfigurationRecorderTypeDef,
     DescribeConformancePackComplianceRequestRequestTypeDef,
     ListConformancePackComplianceScoresResponseTypeDef,
     ListConformancePackComplianceScoresRequestRequestTypeDef,
     GetConformancePackComplianceSummaryResponseTypeDef,
     OrganizationConformancePackTypeDef,
     PutOrganizationConformancePackRequestRequestTypeDef,
     ConformancePackDetailTypeDef,
@@ -680,40 +707,14 @@
     GetConformancePackComplianceDetailsRequestRequestTypeDef,
     DescribeConformancePackComplianceResponseTypeDef,
     DescribeConformancePackStatusResponseTypeDef,
     DeleteRemediationExceptionsRequestRequestTypeDef,
     DescribeRemediationExceptionsRequestRequestTypeDef,
     FailedDeleteRemediationExceptionsBatchTypeDef,
     PutRemediationExceptionsRequestRequestTypeDef,
-    DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
-    DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
-    DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef,
-    DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef,
-    DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef,
-    DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef,
-    DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
-    DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef,
-    DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef,
-    DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef,
-    DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef,
-    DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef,
-    DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef,
-    DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef,
-    DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef,
-    DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
-    DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef,
-    GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
-    GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
-    GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef,
-    GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
-    GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
-    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
-    SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
     DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef,
     DescribeConfigRulesRequestRequestTypeDef,
     DescribeOrganizationConfigRuleStatusesResponseTypeDef,
     DescribeOrganizationConformancePackStatusesResponseTypeDef,
     DescribePendingAggregationRequestsResponseTypeDef,
     DescribeRemediationExceptionsResponseTypeDef,
     FailedRemediationExceptionBatchTypeDef,
@@ -745,14 +746,15 @@
     ListTagsForResourceResponseTypeDef,
     PutAggregationAuthorizationRequestRequestTypeDef,
     PutConfigurationAggregatorRequestRequestTypeDef,
     PutStoredQueryRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     OrganizationConfigRuleTypeDef,
     PutOrganizationConfigRuleRequestRequestTypeDef,
+    RecordingGroupTypeDef,
     RemediationExecutionStatusTypeDef,
     RemediationParameterValueTypeDef,
     ResourceEvaluationFiltersTypeDef,
     SourceTypeDef,
     DescribeAggregateComplianceByConformancePacksResponseTypeDef,
     GetAggregateConformancePackComplianceSummaryResponseTypeDef,
     AggregateComplianceCountTypeDef,
@@ -764,40 +766,41 @@
     DescribeDeliveryChannelsResponseTypeDef,
     PutDeliveryChannelRequestRequestTypeDef,
     DescribeDeliveryChannelStatusResponseTypeDef,
     DescribeConfigurationAggregatorsResponseTypeDef,
     PutConfigurationAggregatorResponseTypeDef,
     GetAggregateResourceConfigResponseTypeDef,
     GetResourceConfigHistoryResponseTypeDef,
-    DescribeConfigurationRecordersResponseTypeDef,
-    PutConfigurationRecorderRequestRequestTypeDef,
     DescribeOrganizationConformancePacksResponseTypeDef,
     DescribeConformancePacksResponseTypeDef,
     DeleteRemediationExceptionsResponseTypeDef,
     PutRemediationExceptionsResponseTypeDef,
     AggregateEvaluationResultTypeDef,
     ConformancePackEvaluationResultTypeDef,
     EvaluationResultTypeDef,
     SelectAggregateResourceConfigResponseTypeDef,
     SelectResourceConfigResponseTypeDef,
     DescribeOrganizationConfigRulesResponseTypeDef,
+    ConfigurationRecorderTypeDef,
     DescribeRemediationExecutionStatusResponseTypeDef,
     RemediationConfigurationTypeDef,
     ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef,
     ListResourceEvaluationsRequestRequestTypeDef,
     ConfigRuleTypeDef,
     GetAggregateConfigRuleComplianceSummaryResponseTypeDef,
     GetComplianceSummaryByResourceTypeResponseTypeDef,
     DescribeAggregateComplianceByConfigRulesResponseTypeDef,
     DescribeComplianceByConfigRuleResponseTypeDef,
     DescribeComplianceByResourceResponseTypeDef,
     GetAggregateComplianceDetailsByConfigRuleResponseTypeDef,
     GetConformancePackComplianceDetailsResponseTypeDef,
     GetComplianceDetailsByConfigRuleResponseTypeDef,
     GetComplianceDetailsByResourceResponseTypeDef,
+    DescribeConfigurationRecordersResponseTypeDef,
+    PutConfigurationRecorderRequestRequestTypeDef,
     DescribeRemediationConfigurationsResponseTypeDef,
     FailedRemediationBatchTypeDef,
     PutRemediationConfigurationsRequestRequestTypeDef,
     DescribeConfigRulesResponseTypeDef,
     PutConfigRuleRequestRequestTypeDef,
     PutRemediationConfigurationsResponseTypeDef,
 )
@@ -810,43 +813,43 @@
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

### Comparing `types-aiobotocore-config-2.5.0.post1/README.md` & `types-aiobotocore-config-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-config"></a>
 
 # types-aiobotocore-config
 
 [![PyPI - types-aiobotocore-config](https://img.shields.io/pypi/v/types-aiobotocore-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConfigService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService)
+[aiobotocore.ConfigService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService)
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
 [types-aiobotocore-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -435,14 +435,15 @@
     OrganizationConfigRuleTriggerTypeNoSNType,
     OrganizationConfigRuleTriggerTypeType,
     OrganizationResourceDetailedStatusType,
     OrganizationResourceStatusType,
     OrganizationRuleStatusType,
     OwnerType,
     RecorderStatusType,
+    RecordingStrategyTypeType,
     RemediationExecutionStateType,
     RemediationExecutionStepStateType,
     RemediationTargetTypeType,
     ResourceConfigurationSchemaTypeType,
     ResourceCountGroupKeyType,
     ResourceEvaluationStatusType,
     ResourceTypeType,
@@ -477,29 +478,27 @@
     AggregateConformancePackComplianceCountTypeDef,
     AggregateConformancePackComplianceFiltersTypeDef,
     AggregateConformancePackComplianceSummaryFiltersTypeDef,
     AggregateResourceIdentifierTypeDef,
     AggregatedSourceStatusTypeDef,
     AggregationAuthorizationTypeDef,
     BaseConfigurationItemTypeDef,
-    ResponseMetadataTypeDef,
     ResourceKeyTypeDef,
     ComplianceContributorCountTypeDef,
     ConfigExportDeliveryInfoTypeDef,
     ConfigRuleComplianceFiltersTypeDef,
     ConfigRuleComplianceSummaryFiltersTypeDef,
     ConfigRuleEvaluationStatusTypeDef,
     EvaluationModeConfigurationTypeDef,
     ScopeTypeDef,
     ConfigSnapshotDeliveryPropertiesTypeDef,
     ConfigStreamDeliveryInfoTypeDef,
     OrganizationAggregationSourceTypeDef,
     RelationshipTypeDef,
     ConfigurationRecorderStatusTypeDef,
-    RecordingGroupTypeDef,
     ConformancePackComplianceFiltersTypeDef,
     ConformancePackComplianceScoreTypeDef,
     ConformancePackComplianceScoresFiltersTypeDef,
     ConformancePackComplianceSummaryTypeDef,
     ConformancePackInputParameterTypeDef,
     TemplateSSMDocumentDetailsTypeDef,
     ConformancePackEvaluationFiltersTypeDef,
@@ -518,128 +517,156 @@
     DeletePendingAggregationRequestRequestRequestTypeDef,
     DeleteRemediationConfigurationRequestRequestTypeDef,
     RemediationExceptionResourceKeyTypeDef,
     DeleteResourceConfigRequestRequestTypeDef,
     DeleteRetentionConfigurationRequestRequestTypeDef,
     DeleteStoredQueryRequestRequestTypeDef,
     DeliverConfigSnapshotRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeliverConfigSnapshotResponseTypeDef,
+    DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef,
     DescribeAggregationAuthorizationsRequestRequestTypeDef,
+    DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef,
     DescribeComplianceByConfigRuleRequestRequestTypeDef,
+    DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef,
     DescribeComplianceByResourceRequestRequestTypeDef,
+    DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef,
     DescribeConfigRuleEvaluationStatusRequestRequestTypeDef,
     DescribeConfigRulesFiltersTypeDef,
+    DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
     DescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef,
+    DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef,
     DescribeConfigurationAggregatorsRequestRequestTypeDef,
     DescribeConfigurationRecorderStatusRequestRequestTypeDef,
     DescribeConfigurationRecordersRequestRequestTypeDef,
+    DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef,
     DescribeConformancePackStatusRequestRequestTypeDef,
+    DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef,
     DescribeConformancePacksRequestRequestTypeDef,
     DescribeDeliveryChannelStatusRequestRequestTypeDef,
     DescribeDeliveryChannelsRequestRequestTypeDef,
+    DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef,
     DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef,
     OrganizationConfigRuleStatusTypeDef,
+    DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef,
     DescribeOrganizationConfigRulesRequestRequestTypeDef,
+    DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef,
     DescribeOrganizationConformancePackStatusesRequestRequestTypeDef,
     OrganizationConformancePackStatusTypeDef,
+    DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef,
     DescribeOrganizationConformancePacksRequestRequestTypeDef,
+    DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef,
     DescribePendingAggregationRequestsRequestRequestTypeDef,
     PendingAggregationRequestTypeDef,
     DescribeRemediationConfigurationsRequestRequestTypeDef,
     RemediationExceptionTypeDef,
+    DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef,
     DescribeRetentionConfigurationsRequestRequestTypeDef,
     RetentionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluationContextTypeDef,
     EvaluationResultQualifierTypeDef,
     EvaluationStatusTypeDef,
     EvaluationTypeDef,
+    ExclusionByResourceTypesTypeDef,
     SsmControlsTypeDef,
     ExternalEvaluationTypeDef,
     FieldInfoTypeDef,
+    GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
     GetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef,
     ResourceCountFiltersTypeDef,
     GroupedResourceCountTypeDef,
+    GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
     GetComplianceDetailsByConfigRuleRequestRequestTypeDef,
+    GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef,
     GetComplianceDetailsByResourceRequestRequestTypeDef,
     GetComplianceSummaryByResourceTypeRequestRequestTypeDef,
+    GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
     GetConformancePackComplianceSummaryRequestRequestTypeDef,
     GetCustomRulePolicyRequestRequestTypeDef,
+    GetCustomRulePolicyResponseTypeDef,
     GetDiscoveredResourceCountsRequestRequestTypeDef,
     ResourceCountTypeDef,
     StatusDetailFiltersTypeDef,
     MemberAccountStatusTypeDef,
     OrganizationResourceDetailedStatusFiltersTypeDef,
     OrganizationConformancePackDetailedStatusTypeDef,
     GetOrganizationCustomRulePolicyRequestRequestTypeDef,
+    GetOrganizationCustomRulePolicyResponseTypeDef,
+    GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
     GetResourceConfigHistoryRequestRequestTypeDef,
     GetResourceEvaluationSummaryRequestRequestTypeDef,
     ResourceDetailsTypeDef,
     GetStoredQueryRequestRequestTypeDef,
     StoredQueryTypeDef,
     ResourceFiltersTypeDef,
+    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
     ResourceIdentifierTypeDef,
     ResourceEvaluationTypeDef,
     ListStoredQueriesRequestRequestTypeDef,
     StoredQueryMetadataTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     OrganizationCustomPolicyRuleMetadataNoPolicyTypeDef,
     OrganizationCustomRuleMetadataTypeDef,
     OrganizationManagedRuleMetadataTypeDef,
     OrganizationCustomPolicyRuleMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    PutConformancePackResponseTypeDef,
+    PutOrganizationConfigRuleResponseTypeDef,
+    PutOrganizationConformancePackResponseTypeDef,
     PutResourceConfigRequestRequestTypeDef,
     PutRetentionConfigurationRequestRequestTypeDef,
+    PutStoredQueryResponseTypeDef,
+    RecordingStrategyTypeDef,
     RemediationExecutionStepTypeDef,
     ResourceValueTypeDef,
     StaticValueTypeDef,
     TimeWindowTypeDef,
+    ResponseMetadataTypeDef,
     SelectAggregateResourceConfigRequestRequestTypeDef,
+    SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
     SelectResourceConfigRequestRequestTypeDef,
+    SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
     SourceDetailTypeDef,
     StartConfigRulesEvaluationRequestRequestTypeDef,
     StartConfigurationRecorderRequestRequestTypeDef,
+    StartResourceEvaluationResponseTypeDef,
     StopConfigurationRecorderRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AggregateComplianceByConformancePackTypeDef,
     AggregateConformancePackComplianceSummaryTypeDef,
+    DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
     DescribeAggregateComplianceByConformancePacksRequestRequestTypeDef,
     GetAggregateConformancePackComplianceSummaryRequestRequestTypeDef,
     BatchGetAggregateResourceConfigRequestRequestTypeDef,
     GetAggregateResourceConfigRequestRequestTypeDef,
-    BatchGetAggregateResourceConfigResponseTypeDef,
-    DeliverConfigSnapshotResponseTypeDef,
-    DescribeAggregationAuthorizationsResponseTypeDef,
-    DescribeConfigurationAggregatorSourcesStatusResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCustomRulePolicyResponseTypeDef,
-    GetOrganizationCustomRulePolicyResponseTypeDef,
     ListAggregateDiscoveredResourcesResponseTypeDef,
+    DescribeConfigurationAggregatorSourcesStatusResponseTypeDef,
+    DescribeAggregationAuthorizationsResponseTypeDef,
     PutAggregationAuthorizationResponseTypeDef,
-    PutConformancePackResponseTypeDef,
-    PutOrganizationConfigRuleResponseTypeDef,
-    PutOrganizationConformancePackResponseTypeDef,
-    PutStoredQueryResponseTypeDef,
-    StartResourceEvaluationResponseTypeDef,
+    BatchGetAggregateResourceConfigResponseTypeDef,
     BatchGetResourceConfigRequestRequestTypeDef,
     BatchGetResourceConfigResponseTypeDef,
+    DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
     DescribeRemediationExecutionStatusRequestRequestTypeDef,
     StartRemediationExecutionRequestRequestTypeDef,
     StartRemediationExecutionResponseTypeDef,
     ComplianceSummaryTypeDef,
     ComplianceTypeDef,
+    DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
     DescribeAggregateComplianceByConfigRulesRequestRequestTypeDef,
     GetAggregateConfigRuleComplianceSummaryRequestRequestTypeDef,
     DescribeConfigRuleEvaluationStatusResponseTypeDef,
     DeliveryChannelTypeDef,
     DeliveryChannelStatusTypeDef,
     ConfigurationAggregatorTypeDef,
     ConfigurationItemTypeDef,
     DescribeConfigurationRecorderStatusResponseTypeDef,
-    ConfigurationRecorderTypeDef,
     DescribeConformancePackComplianceRequestRequestTypeDef,
     ListConformancePackComplianceScoresResponseTypeDef,
     ListConformancePackComplianceScoresRequestRequestTypeDef,
     GetConformancePackComplianceSummaryResponseTypeDef,
     OrganizationConformancePackTypeDef,
     PutOrganizationConformancePackRequestRequestTypeDef,
     ConformancePackDetailTypeDef,
@@ -647,40 +674,14 @@
     GetConformancePackComplianceDetailsRequestRequestTypeDef,
     DescribeConformancePackComplianceResponseTypeDef,
     DescribeConformancePackStatusResponseTypeDef,
     DeleteRemediationExceptionsRequestRequestTypeDef,
     DescribeRemediationExceptionsRequestRequestTypeDef,
     FailedDeleteRemediationExceptionsBatchTypeDef,
     PutRemediationExceptionsRequestRequestTypeDef,
-    DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
-    DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
-    DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef,
-    DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef,
-    DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef,
-    DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef,
-    DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
-    DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef,
-    DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef,
-    DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef,
-    DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef,
-    DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef,
-    DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef,
-    DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef,
-    DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef,
-    DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
-    DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef,
-    GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
-    GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
-    GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef,
-    GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
-    GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
-    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
-    SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
     DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef,
     DescribeConfigRulesRequestRequestTypeDef,
     DescribeOrganizationConfigRuleStatusesResponseTypeDef,
     DescribeOrganizationConformancePackStatusesResponseTypeDef,
     DescribePendingAggregationRequestsResponseTypeDef,
     DescribeRemediationExceptionsResponseTypeDef,
     FailedRemediationExceptionBatchTypeDef,
@@ -712,14 +713,15 @@
     ListTagsForResourceResponseTypeDef,
     PutAggregationAuthorizationRequestRequestTypeDef,
     PutConfigurationAggregatorRequestRequestTypeDef,
     PutStoredQueryRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     OrganizationConfigRuleTypeDef,
     PutOrganizationConfigRuleRequestRequestTypeDef,
+    RecordingGroupTypeDef,
     RemediationExecutionStatusTypeDef,
     RemediationParameterValueTypeDef,
     ResourceEvaluationFiltersTypeDef,
     SourceTypeDef,
     DescribeAggregateComplianceByConformancePacksResponseTypeDef,
     GetAggregateConformancePackComplianceSummaryResponseTypeDef,
     AggregateComplianceCountTypeDef,
@@ -731,40 +733,41 @@
     DescribeDeliveryChannelsResponseTypeDef,
     PutDeliveryChannelRequestRequestTypeDef,
     DescribeDeliveryChannelStatusResponseTypeDef,
     DescribeConfigurationAggregatorsResponseTypeDef,
     PutConfigurationAggregatorResponseTypeDef,
     GetAggregateResourceConfigResponseTypeDef,
     GetResourceConfigHistoryResponseTypeDef,
-    DescribeConfigurationRecordersResponseTypeDef,
-    PutConfigurationRecorderRequestRequestTypeDef,
     DescribeOrganizationConformancePacksResponseTypeDef,
     DescribeConformancePacksResponseTypeDef,
     DeleteRemediationExceptionsResponseTypeDef,
     PutRemediationExceptionsResponseTypeDef,
     AggregateEvaluationResultTypeDef,
     ConformancePackEvaluationResultTypeDef,
     EvaluationResultTypeDef,
     SelectAggregateResourceConfigResponseTypeDef,
     SelectResourceConfigResponseTypeDef,
     DescribeOrganizationConfigRulesResponseTypeDef,
+    ConfigurationRecorderTypeDef,
     DescribeRemediationExecutionStatusResponseTypeDef,
     RemediationConfigurationTypeDef,
     ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef,
     ListResourceEvaluationsRequestRequestTypeDef,
     ConfigRuleTypeDef,
     GetAggregateConfigRuleComplianceSummaryResponseTypeDef,
     GetComplianceSummaryByResourceTypeResponseTypeDef,
     DescribeAggregateComplianceByConfigRulesResponseTypeDef,
     DescribeComplianceByConfigRuleResponseTypeDef,
     DescribeComplianceByResourceResponseTypeDef,
     GetAggregateComplianceDetailsByConfigRuleResponseTypeDef,
     GetConformancePackComplianceDetailsResponseTypeDef,
     GetComplianceDetailsByConfigRuleResponseTypeDef,
     GetComplianceDetailsByResourceResponseTypeDef,
+    DescribeConfigurationRecordersResponseTypeDef,
+    PutConfigurationRecorderRequestRequestTypeDef,
     DescribeRemediationConfigurationsResponseTypeDef,
     FailedRemediationBatchTypeDef,
     PutRemediationConfigurationsRequestRequestTypeDef,
     DescribeConfigRulesResponseTypeDef,
     PutConfigRuleRequestRequestTypeDef,
     PutRemediationConfigurationsResponseTypeDef,
 )
@@ -777,43 +780,43 @@
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

### Comparing `types-aiobotocore-config-2.5.0.post1/setup.py` & `types-aiobotocore-config-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-config.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-config",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_config"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ConfigService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ConfigService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/"
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

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/__init__.py` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/__init__.pyi` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/__main__.py` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ConfigService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ConfigService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService\nOther"
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

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/client.py` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -591,15 +591,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#describe_configuration_aggregators)
         """
 
     async def describe_configuration_recorder_status(
         self, *, ConfigurationRecorderNames: Sequence[str] = ...
     ) -> DescribeConfigurationRecorderStatusResponseTypeDef:
         """
-        Returns the current status of the specified configuration recorder.
+        Returns the current status of the specified configuration recorder as well as
+        the status of the last recording event for the recorder.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.describe_configuration_recorder_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#describe_configuration_recorder_status)
         """
 
     async def describe_configuration_recorders(
         self, *, ConfigurationRecorderNames: Sequence[str] = ...
@@ -1193,16 +1194,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#put_configuration_aggregator)
         """
 
     async def put_configuration_recorder(
         self, *, ConfigurationRecorder: ConfigurationRecorderTypeDef
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Creates a new configuration recorder to record the selected resource
-        configurations.
+        Creates a new configuration recorder to record configuration changes for
+        specified resource types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.put_configuration_recorder)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#put_configuration_recorder)
         """
 
     async def put_conformance_pack(
         self,
@@ -1309,15 +1310,15 @@
         *,
         ConfigRuleName: str,
         ResourceKeys: Sequence[RemediationExceptionResourceKeyTypeDef],
         Message: str = ...,
         ExpirationTime: Union[datetime, str] = ...
     ) -> PutRemediationExceptionsResponseTypeDef:
         """
-        A remediation exception is when a specific resource is no longer considered for
+        A remediation exception is when a specified resource is no longer considered for
         auto-remediation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.put_remediation_exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#put_remediation_exceptions)
         """
 
     async def put_resource_config(
```

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/client.pyi` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -557,15 +557,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.describe_configuration_aggregators)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#describe_configuration_aggregators)
         """
     async def describe_configuration_recorder_status(
         self, *, ConfigurationRecorderNames: Sequence[str] = ...
     ) -> DescribeConfigurationRecorderStatusResponseTypeDef:
         """
-        Returns the current status of the specified configuration recorder.
+        Returns the current status of the specified configuration recorder as well as
+        the status of the last recording event for the recorder.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.describe_configuration_recorder_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#describe_configuration_recorder_status)
         """
     async def describe_configuration_recorders(
         self, *, ConfigurationRecorderNames: Sequence[str] = ...
     ) -> DescribeConfigurationRecordersResponseTypeDef:
@@ -1114,16 +1115,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.put_configuration_aggregator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#put_configuration_aggregator)
         """
     async def put_configuration_recorder(
         self, *, ConfigurationRecorder: ConfigurationRecorderTypeDef
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Creates a new configuration recorder to record the selected resource
-        configurations.
+        Creates a new configuration recorder to record configuration changes for
+        specified resource types.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.put_configuration_recorder)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#put_configuration_recorder)
         """
     async def put_conformance_pack(
         self,
         *,
@@ -1222,15 +1223,15 @@
         *,
         ConfigRuleName: str,
         ResourceKeys: Sequence[RemediationExceptionResourceKeyTypeDef],
         Message: str = ...,
         ExpirationTime: Union[datetime, str] = ...
     ) -> PutRemediationExceptionsResponseTypeDef:
         """
-        A remediation exception is when a specific resource is no longer considered for
+        A remediation exception is when a specified resource is no longer considered for
         auto-remediation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Client.put_remediation_exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/client/#put_remediation_exceptions)
         """
     async def put_resource_config(
         self,
```

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/literals.py` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/literals.py`

 * *Files 15% similar despite different names*

```diff
@@ -68,14 +68,15 @@
     "OrganizationConfigRuleTriggerTypeNoSNType",
     "OrganizationConfigRuleTriggerTypeType",
     "OrganizationResourceDetailedStatusType",
     "OrganizationResourceStatusType",
     "OrganizationRuleStatusType",
     "OwnerType",
     "RecorderStatusType",
+    "RecordingStrategyTypeType",
     "RemediationExecutionStateType",
     "RemediationExecutionStepStateType",
     "RemediationTargetTypeType",
     "ResourceConfigurationSchemaTypeType",
     "ResourceCountGroupKeyType",
     "ResourceEvaluationStatusType",
     "ResourceTypeType",
@@ -221,169 +222,326 @@
     "DELETE_SUCCESSFUL",
     "UPDATE_FAILED",
     "UPDATE_IN_PROGRESS",
     "UPDATE_SUCCESSFUL",
 ]
 OwnerType = Literal["AWS", "CUSTOM_LAMBDA", "CUSTOM_POLICY"]
 RecorderStatusType = Literal["Failure", "Pending", "Success"]
+RecordingStrategyTypeType = Literal[
+    "ALL_SUPPORTED_RESOURCE_TYPES", "EXCLUSION_BY_RESOURCE_TYPES", "INCLUSION_BY_RESOURCE_TYPES"
+]
 RemediationExecutionStateType = Literal["FAILED", "IN_PROGRESS", "QUEUED", "SUCCEEDED"]
 RemediationExecutionStepStateType = Literal["FAILED", "PENDING", "SUCCEEDED"]
 RemediationTargetTypeType = Literal["SSM_DOCUMENT"]
 ResourceConfigurationSchemaTypeType = Literal["CFN_RESOURCE_SCHEMA"]
 ResourceCountGroupKeyType = Literal["ACCOUNT_ID", "AWS_REGION", "RESOURCE_TYPE"]
 ResourceEvaluationStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 ResourceTypeType = Literal[
     "AWS::ACM::Certificate",
     "AWS::AccessAnalyzer::Analyzer",
+    "AWS::AmazonMQ::Broker",
+    "AWS::Amplify::App",
     "AWS::ApiGateway::RestApi",
     "AWS::ApiGateway::Stage",
     "AWS::ApiGatewayV2::Api",
     "AWS::ApiGatewayV2::Stage",
     "AWS::AppConfig::Application",
+    "AWS::AppConfig::ConfigurationProfile",
+    "AWS::AppConfig::DeploymentStrategy",
+    "AWS::AppConfig::Environment",
+    "AWS::AppFlow::Flow",
+    "AWS::AppMesh::VirtualNode",
+    "AWS::AppMesh::VirtualService",
+    "AWS::AppRunner::VpcConnector",
+    "AWS::AppStream::Application",
+    "AWS::AppStream::DirectoryConfig",
     "AWS::AppSync::GraphQLApi",
     "AWS::Athena::DataCatalog",
     "AWS::Athena::WorkGroup",
+    "AWS::AuditManager::Assessment",
     "AWS::AutoScaling::AutoScalingGroup",
     "AWS::AutoScaling::LaunchConfiguration",
     "AWS::AutoScaling::ScalingPolicy",
     "AWS::AutoScaling::ScheduledAction",
+    "AWS::AutoScaling::WarmPool",
     "AWS::Backup::BackupPlan",
     "AWS::Backup::BackupSelection",
     "AWS::Backup::BackupVault",
     "AWS::Backup::RecoveryPoint",
+    "AWS::Backup::ReportPlan",
     "AWS::Batch::ComputeEnvironment",
     "AWS::Batch::JobQueue",
+    "AWS::Budgets::BudgetsAction",
+    "AWS::Cassandra::Keyspace",
+    "AWS::Cloud9::EnvironmentEC2",
     "AWS::CloudFormation::Stack",
     "AWS::CloudFront::Distribution",
     "AWS::CloudFront::StreamingDistribution",
     "AWS::CloudTrail::Trail",
     "AWS::CloudWatch::Alarm",
+    "AWS::CloudWatch::MetricStream",
+    "AWS::CodeArtifact::Repository",
     "AWS::CodeBuild::Project",
     "AWS::CodeDeploy::Application",
     "AWS::CodeDeploy::DeploymentConfig",
     "AWS::CodeDeploy::DeploymentGroup",
+    "AWS::CodeGuruReviewer::RepositoryAssociation",
     "AWS::CodePipeline::Pipeline",
     "AWS::Config::ConformancePackCompliance",
     "AWS::Config::ResourceCompliance",
+    "AWS::Connect::PhoneNumber",
+    "AWS::CustomerProfiles::Domain",
     "AWS::DMS::Certificate",
     "AWS::DMS::EventSubscription",
     "AWS::DMS::ReplicationSubnetGroup",
     "AWS::DataSync::LocationEFS",
     "AWS::DataSync::LocationFSxLustre",
+    "AWS::DataSync::LocationFSxWindows",
+    "AWS::DataSync::LocationHDFS",
     "AWS::DataSync::LocationNFS",
+    "AWS::DataSync::LocationObjectStorage",
     "AWS::DataSync::LocationS3",
     "AWS::DataSync::LocationSMB",
     "AWS::DataSync::Task",
     "AWS::Detective::Graph",
+    "AWS::DeviceFarm::InstanceProfile",
+    "AWS::DeviceFarm::Project",
+    "AWS::DeviceFarm::TestGridProject",
     "AWS::DynamoDB::Table",
     "AWS::EC2::CustomerGateway",
+    "AWS::EC2::DHCPOptions",
+    "AWS::EC2::EC2Fleet",
     "AWS::EC2::EIP",
     "AWS::EC2::EgressOnlyInternetGateway",
     "AWS::EC2::FlowLog",
     "AWS::EC2::Host",
+    "AWS::EC2::IPAM",
     "AWS::EC2::Instance",
     "AWS::EC2::InternetGateway",
     "AWS::EC2::LaunchTemplate",
     "AWS::EC2::NatGateway",
     "AWS::EC2::NetworkAcl",
     "AWS::EC2::NetworkInsightsAccessScopeAnalysis",
+    "AWS::EC2::NetworkInsightsPath",
     "AWS::EC2::NetworkInterface",
+    "AWS::EC2::PrefixList",
     "AWS::EC2::RegisteredHAInstance",
     "AWS::EC2::RouteTable",
     "AWS::EC2::SecurityGroup",
+    "AWS::EC2::SpotFleet",
     "AWS::EC2::Subnet",
+    "AWS::EC2::SubnetRouteTableAssociation",
+    "AWS::EC2::TrafficMirrorFilter",
+    "AWS::EC2::TrafficMirrorSession",
+    "AWS::EC2::TrafficMirrorTarget",
     "AWS::EC2::TransitGateway",
     "AWS::EC2::TransitGatewayAttachment",
     "AWS::EC2::TransitGatewayRouteTable",
     "AWS::EC2::VPC",
     "AWS::EC2::VPCEndpoint",
     "AWS::EC2::VPCEndpointService",
     "AWS::EC2::VPCPeeringConnection",
     "AWS::EC2::VPNConnection",
     "AWS::EC2::VPNGateway",
     "AWS::EC2::Volume",
     "AWS::ECR::PublicRepository",
+    "AWS::ECR::PullThroughCacheRule",
+    "AWS::ECR::RegistryPolicy",
     "AWS::ECR::Repository",
     "AWS::ECS::Cluster",
     "AWS::ECS::Service",
     "AWS::ECS::TaskDefinition",
+    "AWS::ECS::TaskSet",
     "AWS::EFS::AccessPoint",
     "AWS::EFS::FileSystem",
+    "AWS::EKS::Addon",
     "AWS::EKS::Cluster",
     "AWS::EKS::FargateProfile",
+    "AWS::EKS::IdentityProviderConfig",
     "AWS::EMR::SecurityConfiguration",
     "AWS::ElasticBeanstalk::Application",
     "AWS::ElasticBeanstalk::ApplicationVersion",
     "AWS::ElasticBeanstalk::Environment",
     "AWS::ElasticLoadBalancing::LoadBalancer",
     "AWS::ElasticLoadBalancingV2::Listener",
     "AWS::ElasticLoadBalancingV2::LoadBalancer",
     "AWS::Elasticsearch::Domain",
+    "AWS::EventSchemas::Discoverer",
+    "AWS::EventSchemas::Registry",
+    "AWS::EventSchemas::RegistryPolicy",
+    "AWS::EventSchemas::Schema",
+    "AWS::Events::ApiDestination",
+    "AWS::Events::Archive",
+    "AWS::Events::Connection",
+    "AWS::Events::Endpoint",
+    "AWS::Events::EventBus",
+    "AWS::Events::Rule",
+    "AWS::Evidently::Project",
+    "AWS::FIS::ExperimentTemplate",
+    "AWS::Forecast::Dataset",
+    "AWS::FraudDetector::EntityType",
+    "AWS::FraudDetector::Label",
+    "AWS::FraudDetector::Outcome",
+    "AWS::FraudDetector::Variable",
     "AWS::GlobalAccelerator::Accelerator",
     "AWS::GlobalAccelerator::EndpointGroup",
     "AWS::GlobalAccelerator::Listener",
+    "AWS::Glue::Classifier",
     "AWS::Glue::Job",
+    "AWS::Glue::MLTransform",
+    "AWS::GroundStation::Config",
     "AWS::GuardDuty::Detector",
+    "AWS::GuardDuty::Filter",
     "AWS::GuardDuty::IPSet",
     "AWS::GuardDuty::ThreatIntelSet",
+    "AWS::HealthLake::FHIRDatastore",
     "AWS::IAM::Group",
     "AWS::IAM::Policy",
     "AWS::IAM::Role",
+    "AWS::IAM::SAMLProvider",
+    "AWS::IAM::ServerCertificate",
     "AWS::IAM::User",
+    "AWS::IVS::Channel",
+    "AWS::IVS::PlaybackKeyPair",
+    "AWS::IVS::RecordingConfiguration",
+    "AWS::ImageBuilder::ContainerRecipe",
+    "AWS::ImageBuilder::DistributionConfiguration",
+    "AWS::ImageBuilder::ImagePipeline",
+    "AWS::ImageBuilder::InfrastructureConfiguration",
+    "AWS::IoT::AccountAuditConfiguration",
+    "AWS::IoT::Authorizer",
+    "AWS::IoT::CustomMetric",
+    "AWS::IoT::Dimension",
+    "AWS::IoT::FleetMetric",
+    "AWS::IoT::MitigationAction",
+    "AWS::IoT::Policy",
+    "AWS::IoT::RoleAlias",
+    "AWS::IoT::ScheduledAudit",
+    "AWS::IoT::SecurityProfile",
+    "AWS::IoTAnalytics::Channel",
+    "AWS::IoTAnalytics::Dataset",
+    "AWS::IoTAnalytics::Datastore",
+    "AWS::IoTAnalytics::Pipeline",
+    "AWS::IoTEvents::AlarmModel",
+    "AWS::IoTEvents::DetectorModel",
+    "AWS::IoTEvents::Input",
+    "AWS::IoTSiteWise::AssetModel",
+    "AWS::IoTSiteWise::Dashboard",
+    "AWS::IoTSiteWise::Gateway",
+    "AWS::IoTSiteWise::Portal",
+    "AWS::IoTSiteWise::Project",
+    "AWS::IoTTwinMaker::Entity",
+    "AWS::IoTTwinMaker::Scene",
+    "AWS::IoTTwinMaker::Workspace",
+    "AWS::IoTWireless::ServiceProfile",
     "AWS::KMS::Key",
     "AWS::Kinesis::Stream",
     "AWS::Kinesis::StreamConsumer",
+    "AWS::KinesisAnalyticsV2::Application",
+    "AWS::KinesisFirehose::DeliveryStream",
+    "AWS::KinesisVideo::SignalingChannel",
     "AWS::Lambda::Function",
+    "AWS::Lex::Bot",
+    "AWS::Lex::BotAlias",
+    "AWS::Lightsail::Bucket",
+    "AWS::Lightsail::Certificate",
+    "AWS::Lightsail::Disk",
+    "AWS::Lightsail::StaticIp",
+    "AWS::LookoutMetrics::Alert",
+    "AWS::LookoutVision::Project",
     "AWS::MSK::Cluster",
+    "AWS::MediaPackage::PackagingConfiguration",
+    "AWS::MediaPackage::PackagingGroup",
     "AWS::NetworkFirewall::Firewall",
     "AWS::NetworkFirewall::FirewallPolicy",
     "AWS::NetworkFirewall::RuleGroup",
+    "AWS::NetworkManager::Device",
+    "AWS::NetworkManager::GlobalNetwork",
+    "AWS::NetworkManager::Link",
+    "AWS::NetworkManager::Site",
+    "AWS::NetworkManager::TransitGatewayRegistration",
     "AWS::OpenSearch::Domain",
+    "AWS::Panorama::Package",
+    "AWS::Pinpoint::App",
+    "AWS::Pinpoint::ApplicationSettings",
+    "AWS::Pinpoint::Campaign",
+    "AWS::Pinpoint::InAppTemplate",
+    "AWS::Pinpoint::Segment",
     "AWS::QLDB::Ledger",
     "AWS::RDS::DBCluster",
     "AWS::RDS::DBClusterSnapshot",
     "AWS::RDS::DBInstance",
     "AWS::RDS::DBSecurityGroup",
     "AWS::RDS::DBSnapshot",
     "AWS::RDS::DBSubnetGroup",
     "AWS::RDS::EventSubscription",
+    "AWS::RDS::GlobalCluster",
+    "AWS::RUM::AppMonitor",
     "AWS::Redshift::Cluster",
     "AWS::Redshift::ClusterParameterGroup",
     "AWS::Redshift::ClusterSecurityGroup",
     "AWS::Redshift::ClusterSnapshot",
     "AWS::Redshift::ClusterSubnetGroup",
     "AWS::Redshift::EventSubscription",
+    "AWS::Redshift::ScheduledAction",
+    "AWS::ResilienceHub::ResiliencyPolicy",
+    "AWS::RoboMaker::RobotApplication",
+    "AWS::RoboMaker::RobotApplicationVersion",
+    "AWS::RoboMaker::SimulationApplication",
     "AWS::Route53::HostedZone",
+    "AWS::Route53RecoveryControl::Cluster",
+    "AWS::Route53RecoveryControl::ControlPanel",
+    "AWS::Route53RecoveryControl::RoutingControl",
+    "AWS::Route53RecoveryControl::SafetyRule",
+    "AWS::Route53RecoveryReadiness::Cell",
+    "AWS::Route53RecoveryReadiness::ReadinessCheck",
+    "AWS::Route53RecoveryReadiness::RecoveryGroup",
+    "AWS::Route53RecoveryReadiness::ResourceSet",
+    "AWS::Route53Resolver::FirewallDomainList",
+    "AWS::Route53Resolver::FirewallRuleGroupAssociation",
     "AWS::Route53Resolver::ResolverEndpoint",
     "AWS::Route53Resolver::ResolverRule",
     "AWS::Route53Resolver::ResolverRuleAssociation",
     "AWS::S3::AccountPublicAccessBlock",
     "AWS::S3::Bucket",
+    "AWS::S3::MultiRegionAccessPoint",
+    "AWS::S3::StorageLens",
     "AWS::SES::ConfigurationSet",
     "AWS::SES::ContactList",
+    "AWS::SES::ReceiptFilter",
+    "AWS::SES::ReceiptRuleSet",
+    "AWS::SES::Template",
     "AWS::SNS::Topic",
     "AWS::SQS::Queue",
     "AWS::SSM::AssociationCompliance",
     "AWS::SSM::FileData",
     "AWS::SSM::ManagedInstanceInventory",
     "AWS::SSM::PatchCompliance",
+    "AWS::SageMaker::AppImageConfig",
     "AWS::SageMaker::CodeRepository",
+    "AWS::SageMaker::Domain",
+    "AWS::SageMaker::Image",
     "AWS::SageMaker::Model",
     "AWS::SageMaker::NotebookInstanceLifecycleConfig",
     "AWS::SageMaker::Workteam",
     "AWS::SecretsManager::Secret",
     "AWS::ServiceCatalog::CloudFormationProduct",
     "AWS::ServiceCatalog::CloudFormationProvisionedProduct",
     "AWS::ServiceCatalog::Portfolio",
+    "AWS::ServiceDiscovery::HttpNamespace",
     "AWS::ServiceDiscovery::PublicDnsNamespace",
     "AWS::ServiceDiscovery::Service",
     "AWS::Shield::Protection",
     "AWS::ShieldRegional::Protection",
+    "AWS::Signer::SigningProfile",
     "AWS::StepFunctions::Activity",
     "AWS::StepFunctions::StateMachine",
+    "AWS::Transfer::Agreement",
+    "AWS::Transfer::Connector",
+    "AWS::Transfer::Workflow",
     "AWS::WAF::RateBasedRule",
     "AWS::WAF::Rule",
     "AWS::WAF::RuleGroup",
     "AWS::WAF::WebACL",
     "AWS::WAFRegional::RateBasedRule",
     "AWS::WAFRegional::Rule",
     "AWS::WAFRegional::RuleGroup",
@@ -461,14 +619,15 @@
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
@@ -547,14 +706,15 @@
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
@@ -565,14 +725,15 @@
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
@@ -608,14 +769,15 @@
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
@@ -634,16 +796,19 @@
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
@@ -727,15 +892,17 @@
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

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/literals.pyi` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/literals.pyi`

 * *Files 15% similar despite different names*

```diff
@@ -67,14 +67,15 @@
     "OrganizationConfigRuleTriggerTypeNoSNType",
     "OrganizationConfigRuleTriggerTypeType",
     "OrganizationResourceDetailedStatusType",
     "OrganizationResourceStatusType",
     "OrganizationRuleStatusType",
     "OwnerType",
     "RecorderStatusType",
+    "RecordingStrategyTypeType",
     "RemediationExecutionStateType",
     "RemediationExecutionStepStateType",
     "RemediationTargetTypeType",
     "ResourceConfigurationSchemaTypeType",
     "ResourceCountGroupKeyType",
     "ResourceEvaluationStatusType",
     "ResourceTypeType",
@@ -219,169 +220,326 @@
     "DELETE_SUCCESSFUL",
     "UPDATE_FAILED",
     "UPDATE_IN_PROGRESS",
     "UPDATE_SUCCESSFUL",
 ]
 OwnerType = Literal["AWS", "CUSTOM_LAMBDA", "CUSTOM_POLICY"]
 RecorderStatusType = Literal["Failure", "Pending", "Success"]
+RecordingStrategyTypeType = Literal[
+    "ALL_SUPPORTED_RESOURCE_TYPES", "EXCLUSION_BY_RESOURCE_TYPES", "INCLUSION_BY_RESOURCE_TYPES"
+]
 RemediationExecutionStateType = Literal["FAILED", "IN_PROGRESS", "QUEUED", "SUCCEEDED"]
 RemediationExecutionStepStateType = Literal["FAILED", "PENDING", "SUCCEEDED"]
 RemediationTargetTypeType = Literal["SSM_DOCUMENT"]
 ResourceConfigurationSchemaTypeType = Literal["CFN_RESOURCE_SCHEMA"]
 ResourceCountGroupKeyType = Literal["ACCOUNT_ID", "AWS_REGION", "RESOURCE_TYPE"]
 ResourceEvaluationStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED"]
 ResourceTypeType = Literal[
     "AWS::ACM::Certificate",
     "AWS::AccessAnalyzer::Analyzer",
+    "AWS::AmazonMQ::Broker",
+    "AWS::Amplify::App",
     "AWS::ApiGateway::RestApi",
     "AWS::ApiGateway::Stage",
     "AWS::ApiGatewayV2::Api",
     "AWS::ApiGatewayV2::Stage",
     "AWS::AppConfig::Application",
+    "AWS::AppConfig::ConfigurationProfile",
+    "AWS::AppConfig::DeploymentStrategy",
+    "AWS::AppConfig::Environment",
+    "AWS::AppFlow::Flow",
+    "AWS::AppMesh::VirtualNode",
+    "AWS::AppMesh::VirtualService",
+    "AWS::AppRunner::VpcConnector",
+    "AWS::AppStream::Application",
+    "AWS::AppStream::DirectoryConfig",
     "AWS::AppSync::GraphQLApi",
     "AWS::Athena::DataCatalog",
     "AWS::Athena::WorkGroup",
+    "AWS::AuditManager::Assessment",
     "AWS::AutoScaling::AutoScalingGroup",
     "AWS::AutoScaling::LaunchConfiguration",
     "AWS::AutoScaling::ScalingPolicy",
     "AWS::AutoScaling::ScheduledAction",
+    "AWS::AutoScaling::WarmPool",
     "AWS::Backup::BackupPlan",
     "AWS::Backup::BackupSelection",
     "AWS::Backup::BackupVault",
     "AWS::Backup::RecoveryPoint",
+    "AWS::Backup::ReportPlan",
     "AWS::Batch::ComputeEnvironment",
     "AWS::Batch::JobQueue",
+    "AWS::Budgets::BudgetsAction",
+    "AWS::Cassandra::Keyspace",
+    "AWS::Cloud9::EnvironmentEC2",
     "AWS::CloudFormation::Stack",
     "AWS::CloudFront::Distribution",
     "AWS::CloudFront::StreamingDistribution",
     "AWS::CloudTrail::Trail",
     "AWS::CloudWatch::Alarm",
+    "AWS::CloudWatch::MetricStream",
+    "AWS::CodeArtifact::Repository",
     "AWS::CodeBuild::Project",
     "AWS::CodeDeploy::Application",
     "AWS::CodeDeploy::DeploymentConfig",
     "AWS::CodeDeploy::DeploymentGroup",
+    "AWS::CodeGuruReviewer::RepositoryAssociation",
     "AWS::CodePipeline::Pipeline",
     "AWS::Config::ConformancePackCompliance",
     "AWS::Config::ResourceCompliance",
+    "AWS::Connect::PhoneNumber",
+    "AWS::CustomerProfiles::Domain",
     "AWS::DMS::Certificate",
     "AWS::DMS::EventSubscription",
     "AWS::DMS::ReplicationSubnetGroup",
     "AWS::DataSync::LocationEFS",
     "AWS::DataSync::LocationFSxLustre",
+    "AWS::DataSync::LocationFSxWindows",
+    "AWS::DataSync::LocationHDFS",
     "AWS::DataSync::LocationNFS",
+    "AWS::DataSync::LocationObjectStorage",
     "AWS::DataSync::LocationS3",
     "AWS::DataSync::LocationSMB",
     "AWS::DataSync::Task",
     "AWS::Detective::Graph",
+    "AWS::DeviceFarm::InstanceProfile",
+    "AWS::DeviceFarm::Project",
+    "AWS::DeviceFarm::TestGridProject",
     "AWS::DynamoDB::Table",
     "AWS::EC2::CustomerGateway",
+    "AWS::EC2::DHCPOptions",
+    "AWS::EC2::EC2Fleet",
     "AWS::EC2::EIP",
     "AWS::EC2::EgressOnlyInternetGateway",
     "AWS::EC2::FlowLog",
     "AWS::EC2::Host",
+    "AWS::EC2::IPAM",
     "AWS::EC2::Instance",
     "AWS::EC2::InternetGateway",
     "AWS::EC2::LaunchTemplate",
     "AWS::EC2::NatGateway",
     "AWS::EC2::NetworkAcl",
     "AWS::EC2::NetworkInsightsAccessScopeAnalysis",
+    "AWS::EC2::NetworkInsightsPath",
     "AWS::EC2::NetworkInterface",
+    "AWS::EC2::PrefixList",
     "AWS::EC2::RegisteredHAInstance",
     "AWS::EC2::RouteTable",
     "AWS::EC2::SecurityGroup",
+    "AWS::EC2::SpotFleet",
     "AWS::EC2::Subnet",
+    "AWS::EC2::SubnetRouteTableAssociation",
+    "AWS::EC2::TrafficMirrorFilter",
+    "AWS::EC2::TrafficMirrorSession",
+    "AWS::EC2::TrafficMirrorTarget",
     "AWS::EC2::TransitGateway",
     "AWS::EC2::TransitGatewayAttachment",
     "AWS::EC2::TransitGatewayRouteTable",
     "AWS::EC2::VPC",
     "AWS::EC2::VPCEndpoint",
     "AWS::EC2::VPCEndpointService",
     "AWS::EC2::VPCPeeringConnection",
     "AWS::EC2::VPNConnection",
     "AWS::EC2::VPNGateway",
     "AWS::EC2::Volume",
     "AWS::ECR::PublicRepository",
+    "AWS::ECR::PullThroughCacheRule",
+    "AWS::ECR::RegistryPolicy",
     "AWS::ECR::Repository",
     "AWS::ECS::Cluster",
     "AWS::ECS::Service",
     "AWS::ECS::TaskDefinition",
+    "AWS::ECS::TaskSet",
     "AWS::EFS::AccessPoint",
     "AWS::EFS::FileSystem",
+    "AWS::EKS::Addon",
     "AWS::EKS::Cluster",
     "AWS::EKS::FargateProfile",
+    "AWS::EKS::IdentityProviderConfig",
     "AWS::EMR::SecurityConfiguration",
     "AWS::ElasticBeanstalk::Application",
     "AWS::ElasticBeanstalk::ApplicationVersion",
     "AWS::ElasticBeanstalk::Environment",
     "AWS::ElasticLoadBalancing::LoadBalancer",
     "AWS::ElasticLoadBalancingV2::Listener",
     "AWS::ElasticLoadBalancingV2::LoadBalancer",
     "AWS::Elasticsearch::Domain",
+    "AWS::EventSchemas::Discoverer",
+    "AWS::EventSchemas::Registry",
+    "AWS::EventSchemas::RegistryPolicy",
+    "AWS::EventSchemas::Schema",
+    "AWS::Events::ApiDestination",
+    "AWS::Events::Archive",
+    "AWS::Events::Connection",
+    "AWS::Events::Endpoint",
+    "AWS::Events::EventBus",
+    "AWS::Events::Rule",
+    "AWS::Evidently::Project",
+    "AWS::FIS::ExperimentTemplate",
+    "AWS::Forecast::Dataset",
+    "AWS::FraudDetector::EntityType",
+    "AWS::FraudDetector::Label",
+    "AWS::FraudDetector::Outcome",
+    "AWS::FraudDetector::Variable",
     "AWS::GlobalAccelerator::Accelerator",
     "AWS::GlobalAccelerator::EndpointGroup",
     "AWS::GlobalAccelerator::Listener",
+    "AWS::Glue::Classifier",
     "AWS::Glue::Job",
+    "AWS::Glue::MLTransform",
+    "AWS::GroundStation::Config",
     "AWS::GuardDuty::Detector",
+    "AWS::GuardDuty::Filter",
     "AWS::GuardDuty::IPSet",
     "AWS::GuardDuty::ThreatIntelSet",
+    "AWS::HealthLake::FHIRDatastore",
     "AWS::IAM::Group",
     "AWS::IAM::Policy",
     "AWS::IAM::Role",
+    "AWS::IAM::SAMLProvider",
+    "AWS::IAM::ServerCertificate",
     "AWS::IAM::User",
+    "AWS::IVS::Channel",
+    "AWS::IVS::PlaybackKeyPair",
+    "AWS::IVS::RecordingConfiguration",
+    "AWS::ImageBuilder::ContainerRecipe",
+    "AWS::ImageBuilder::DistributionConfiguration",
+    "AWS::ImageBuilder::ImagePipeline",
+    "AWS::ImageBuilder::InfrastructureConfiguration",
+    "AWS::IoT::AccountAuditConfiguration",
+    "AWS::IoT::Authorizer",
+    "AWS::IoT::CustomMetric",
+    "AWS::IoT::Dimension",
+    "AWS::IoT::FleetMetric",
+    "AWS::IoT::MitigationAction",
+    "AWS::IoT::Policy",
+    "AWS::IoT::RoleAlias",
+    "AWS::IoT::ScheduledAudit",
+    "AWS::IoT::SecurityProfile",
+    "AWS::IoTAnalytics::Channel",
+    "AWS::IoTAnalytics::Dataset",
+    "AWS::IoTAnalytics::Datastore",
+    "AWS::IoTAnalytics::Pipeline",
+    "AWS::IoTEvents::AlarmModel",
+    "AWS::IoTEvents::DetectorModel",
+    "AWS::IoTEvents::Input",
+    "AWS::IoTSiteWise::AssetModel",
+    "AWS::IoTSiteWise::Dashboard",
+    "AWS::IoTSiteWise::Gateway",
+    "AWS::IoTSiteWise::Portal",
+    "AWS::IoTSiteWise::Project",
+    "AWS::IoTTwinMaker::Entity",
+    "AWS::IoTTwinMaker::Scene",
+    "AWS::IoTTwinMaker::Workspace",
+    "AWS::IoTWireless::ServiceProfile",
     "AWS::KMS::Key",
     "AWS::Kinesis::Stream",
     "AWS::Kinesis::StreamConsumer",
+    "AWS::KinesisAnalyticsV2::Application",
+    "AWS::KinesisFirehose::DeliveryStream",
+    "AWS::KinesisVideo::SignalingChannel",
     "AWS::Lambda::Function",
+    "AWS::Lex::Bot",
+    "AWS::Lex::BotAlias",
+    "AWS::Lightsail::Bucket",
+    "AWS::Lightsail::Certificate",
+    "AWS::Lightsail::Disk",
+    "AWS::Lightsail::StaticIp",
+    "AWS::LookoutMetrics::Alert",
+    "AWS::LookoutVision::Project",
     "AWS::MSK::Cluster",
+    "AWS::MediaPackage::PackagingConfiguration",
+    "AWS::MediaPackage::PackagingGroup",
     "AWS::NetworkFirewall::Firewall",
     "AWS::NetworkFirewall::FirewallPolicy",
     "AWS::NetworkFirewall::RuleGroup",
+    "AWS::NetworkManager::Device",
+    "AWS::NetworkManager::GlobalNetwork",
+    "AWS::NetworkManager::Link",
+    "AWS::NetworkManager::Site",
+    "AWS::NetworkManager::TransitGatewayRegistration",
     "AWS::OpenSearch::Domain",
+    "AWS::Panorama::Package",
+    "AWS::Pinpoint::App",
+    "AWS::Pinpoint::ApplicationSettings",
+    "AWS::Pinpoint::Campaign",
+    "AWS::Pinpoint::InAppTemplate",
+    "AWS::Pinpoint::Segment",
     "AWS::QLDB::Ledger",
     "AWS::RDS::DBCluster",
     "AWS::RDS::DBClusterSnapshot",
     "AWS::RDS::DBInstance",
     "AWS::RDS::DBSecurityGroup",
     "AWS::RDS::DBSnapshot",
     "AWS::RDS::DBSubnetGroup",
     "AWS::RDS::EventSubscription",
+    "AWS::RDS::GlobalCluster",
+    "AWS::RUM::AppMonitor",
     "AWS::Redshift::Cluster",
     "AWS::Redshift::ClusterParameterGroup",
     "AWS::Redshift::ClusterSecurityGroup",
     "AWS::Redshift::ClusterSnapshot",
     "AWS::Redshift::ClusterSubnetGroup",
     "AWS::Redshift::EventSubscription",
+    "AWS::Redshift::ScheduledAction",
+    "AWS::ResilienceHub::ResiliencyPolicy",
+    "AWS::RoboMaker::RobotApplication",
+    "AWS::RoboMaker::RobotApplicationVersion",
+    "AWS::RoboMaker::SimulationApplication",
     "AWS::Route53::HostedZone",
+    "AWS::Route53RecoveryControl::Cluster",
+    "AWS::Route53RecoveryControl::ControlPanel",
+    "AWS::Route53RecoveryControl::RoutingControl",
+    "AWS::Route53RecoveryControl::SafetyRule",
+    "AWS::Route53RecoveryReadiness::Cell",
+    "AWS::Route53RecoveryReadiness::ReadinessCheck",
+    "AWS::Route53RecoveryReadiness::RecoveryGroup",
+    "AWS::Route53RecoveryReadiness::ResourceSet",
+    "AWS::Route53Resolver::FirewallDomainList",
+    "AWS::Route53Resolver::FirewallRuleGroupAssociation",
     "AWS::Route53Resolver::ResolverEndpoint",
     "AWS::Route53Resolver::ResolverRule",
     "AWS::Route53Resolver::ResolverRuleAssociation",
     "AWS::S3::AccountPublicAccessBlock",
     "AWS::S3::Bucket",
+    "AWS::S3::MultiRegionAccessPoint",
+    "AWS::S3::StorageLens",
     "AWS::SES::ConfigurationSet",
     "AWS::SES::ContactList",
+    "AWS::SES::ReceiptFilter",
+    "AWS::SES::ReceiptRuleSet",
+    "AWS::SES::Template",
     "AWS::SNS::Topic",
     "AWS::SQS::Queue",
     "AWS::SSM::AssociationCompliance",
     "AWS::SSM::FileData",
     "AWS::SSM::ManagedInstanceInventory",
     "AWS::SSM::PatchCompliance",
+    "AWS::SageMaker::AppImageConfig",
     "AWS::SageMaker::CodeRepository",
+    "AWS::SageMaker::Domain",
+    "AWS::SageMaker::Image",
     "AWS::SageMaker::Model",
     "AWS::SageMaker::NotebookInstanceLifecycleConfig",
     "AWS::SageMaker::Workteam",
     "AWS::SecretsManager::Secret",
     "AWS::ServiceCatalog::CloudFormationProduct",
     "AWS::ServiceCatalog::CloudFormationProvisionedProduct",
     "AWS::ServiceCatalog::Portfolio",
+    "AWS::ServiceDiscovery::HttpNamespace",
     "AWS::ServiceDiscovery::PublicDnsNamespace",
     "AWS::ServiceDiscovery::Service",
     "AWS::Shield::Protection",
     "AWS::ShieldRegional::Protection",
+    "AWS::Signer::SigningProfile",
     "AWS::StepFunctions::Activity",
     "AWS::StepFunctions::StateMachine",
+    "AWS::Transfer::Agreement",
+    "AWS::Transfer::Connector",
+    "AWS::Transfer::Workflow",
     "AWS::WAF::RateBasedRule",
     "AWS::WAF::Rule",
     "AWS::WAF::RuleGroup",
     "AWS::WAF::WebACL",
     "AWS::WAFRegional::RateBasedRule",
     "AWS::WAFRegional::Rule",
     "AWS::WAFRegional::RuleGroup",
@@ -459,14 +617,15 @@
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
@@ -545,14 +704,15 @@
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
@@ -563,14 +723,15 @@
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
@@ -606,14 +767,15 @@
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
@@ -632,16 +794,19 @@
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
@@ -725,15 +890,17 @@
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

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/paginator.py` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/paginator.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -76,17 +76,16 @@
         list_discovered_resources_paginator: ListDiscoveredResourcesPaginator = client.get_paginator("list_discovered_resources")
         list_resource_evaluations_paginator: ListResourceEvaluationsPaginator = client.get_paginator("list_resource_evaluations")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         select_aggregate_resource_config_paginator: SelectAggregateResourceConfigPaginator = client.get_paginator("select_aggregate_resource_config")
         select_resource_config_paginator: SelectResourceConfigPaginator = client.get_paginator("select_resource_config")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AggregatedSourceStatusTypeType,
     ChronologicalOrderType,
@@ -132,20 +131,14 @@
     ResourceFiltersTypeDef,
     ResourceKeyTypeDef,
     SelectAggregateResourceConfigResponseTypeDef,
     SelectResourceConfigResponseTypeDef,
     StatusDetailFiltersTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeAggregateComplianceByConfigRulesPaginator",
     "DescribeAggregateComplianceByConformancePacksPaginator",
     "DescribeAggregationAuthorizationsPaginator",
     "DescribeComplianceByConfigRulePaginator",
     "DescribeComplianceByResourcePaginator",
     "DescribeConfigRuleEvaluationStatusPaginator",
@@ -172,588 +165,558 @@
     "ListDiscoveredResourcesPaginator",
     "ListResourceEvaluationsPaginator",
     "ListTagsForResourcePaginator",
     "SelectAggregateResourceConfigPaginator",
     "SelectResourceConfigPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeAggregateComplianceByConfigRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConfigRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconfigrulespaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         Filters: ConfigRuleComplianceFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAggregateComplianceByConfigRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConfigRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconfigrulespaginator)
         """
 
-
 class DescribeAggregateComplianceByConformancePacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConformancePacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconformancepackspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         Filters: AggregateConformancePackComplianceFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAggregateComplianceByConformancePacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConformancePacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconformancepackspaginator)
         """
 
-
 class DescribeAggregationAuthorizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregationAuthorizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregationauthorizationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAggregationAuthorizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregationAuthorizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregationauthorizationspaginator)
         """
 
-
 class DescribeComplianceByConfigRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByConfigRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyconfigrulepaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleNames: Sequence[str] = ...,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeComplianceByConfigRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByConfigRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyconfigrulepaginator)
         """
 
-
 class DescribeComplianceByResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyresourcepaginator)
     """
 
     def paginate(
         self,
         *,
         ResourceType: str = ...,
         ResourceId: str = ...,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeComplianceByResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyresourcepaginator)
         """
 
-
 class DescribeConfigRuleEvaluationStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRuleEvaluationStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigruleevaluationstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigRuleEvaluationStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRuleEvaluationStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigruleevaluationstatuspaginator)
         """
 
-
 class DescribeConfigRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigrulespaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleNames: Sequence[str] = ...,
         Filters: DescribeConfigRulesFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigrulespaginator)
         """
 
-
 class DescribeConfigurationAggregatorSourcesStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregatorSourcesStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorsourcesstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         UpdateStatus: Sequence[AggregatedSourceStatusTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigurationAggregatorSourcesStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregatorSourcesStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorsourcesstatuspaginator)
         """
 
-
 class DescribeConfigurationAggregatorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigurationAggregatorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorspaginator)
         """
 
-
 class DescribeConformancePackStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePackStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConformancePackStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePackStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackstatuspaginator)
         """
 
-
 class DescribeConformancePacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackspaginator)
     """
 
     def paginate(
         self,
         *,
         ConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConformancePacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackspaginator)
         """
 
-
 class DescribeOrganizationConfigRuleStatusesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRuleStatuses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulestatusespaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConfigRuleNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConfigRuleStatusesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRuleStatuses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulestatusespaginator)
         """
 
-
 class DescribeOrganizationConfigRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulespaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConfigRuleNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConfigRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulespaginator)
         """
 
-
 class DescribeOrganizationConformancePackStatusesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePackStatuses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackstatusespaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConformancePackStatusesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePackStatuses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackstatusespaginator)
         """
 
-
 class DescribeOrganizationConformancePacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackspaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConformancePacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackspaginator)
         """
 
-
 class DescribePendingAggregationRequestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribePendingAggregationRequests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describependingaggregationrequestspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePendingAggregationRequestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribePendingAggregationRequests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describependingaggregationrequestspaginator)
         """
 
-
 class DescribeRemediationExecutionStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRemediationExecutionStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeremediationexecutionstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleName: str,
         ResourceKeys: Sequence[ResourceKeyTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRemediationExecutionStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRemediationExecutionStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeremediationexecutionstatuspaginator)
         """
 
-
 class DescribeRetentionConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRetentionConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeretentionconfigurationspaginator)
     """
 
     def paginate(
         self,
         *,
         RetentionConfigurationNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRetentionConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRetentionConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeretentionconfigurationspaginator)
         """
 
-
 class GetAggregateComplianceDetailsByConfigRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetAggregateComplianceDetailsByConfigRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getaggregatecompliancedetailsbyconfigrulepaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         ConfigRuleName: str,
         AccountId: str,
         AwsRegion: str,
         ComplianceType: ComplianceTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAggregateComplianceDetailsByConfigRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetAggregateComplianceDetailsByConfigRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getaggregatecompliancedetailsbyconfigrulepaginator)
         """
 
-
 class GetComplianceDetailsByConfigRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByConfigRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyconfigrulepaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleName: str,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetComplianceDetailsByConfigRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByConfigRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyconfigrulepaginator)
         """
 
-
 class GetComplianceDetailsByResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyresourcepaginator)
     """
 
     def paginate(
         self,
         *,
         ResourceType: str = ...,
         ResourceId: str = ...,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
         ResourceEvaluationId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetComplianceDetailsByResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyresourcepaginator)
         """
 
-
 class GetConformancePackComplianceSummaryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetConformancePackComplianceSummary)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getconformancepackcompliancesummarypaginator)
     """
 
     def paginate(
-        self, *, ConformancePackNames: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ConformancePackNames: Sequence[str],
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConformancePackComplianceSummaryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetConformancePackComplianceSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getconformancepackcompliancesummarypaginator)
         """
 
-
 class GetOrganizationConfigRuleDetailedStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConfigRuleDetailedStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconfigruledetailedstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConfigRuleName: str,
         Filters: StatusDetailFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOrganizationConfigRuleDetailedStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConfigRuleDetailedStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconfigruledetailedstatuspaginator)
         """
 
-
 class GetOrganizationConformancePackDetailedStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConformancePackDetailedStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconformancepackdetailedstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConformancePackName: str,
         Filters: OrganizationResourceDetailedStatusFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOrganizationConformancePackDetailedStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConformancePackDetailedStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconformancepackdetailedstatuspaginator)
         """
 
-
 class GetResourceConfigHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetResourceConfigHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getresourceconfighistorypaginator)
     """
 
     def paginate(
         self,
         *,
         resourceType: ResourceTypeType,
         resourceId: str,
         laterTime: Union[datetime, str] = ...,
         earlierTime: Union[datetime, str] = ...,
         chronologicalOrder: ChronologicalOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceConfigHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetResourceConfigHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getresourceconfighistorypaginator)
         """
 
-
 class ListAggregateDiscoveredResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListAggregateDiscoveredResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listaggregatediscoveredresourcespaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         ResourceType: ResourceTypeType,
         Filters: ResourceFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAggregateDiscoveredResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListAggregateDiscoveredResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listaggregatediscoveredresourcespaginator)
         """
 
-
 class ListDiscoveredResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListDiscoveredResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listdiscoveredresourcespaginator)
     """
 
     def paginate(
         self,
         *,
         resourceType: ResourceTypeType,
         resourceIds: Sequence[str] = ...,
         resourceName: str = ...,
         includeDeletedResources: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDiscoveredResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListDiscoveredResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listdiscoveredresourcespaginator)
         """
 
-
 class ListResourceEvaluationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListResourceEvaluations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listresourceevaluationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: ResourceEvaluationFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceEvaluationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListResourceEvaluations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listresourceevaluationspaginator)
         """
 
-
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listtagsforresourcepaginator)
         """
 
-
 class SelectAggregateResourceConfigPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectAggregateResourceConfig)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectaggregateresourceconfigpaginator)
     """
 
     def paginate(
         self,
         *,
         Expression: str,
         ConfigurationAggregatorName: str,
         MaxResults: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SelectAggregateResourceConfigResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectAggregateResourceConfig.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectaggregateresourceconfigpaginator)
         """
 
-
 class SelectResourceConfigPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectResourceConfig)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectresourceconfigpaginator)
     """
 
     def paginate(
-        self, *, Expression: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Expression: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SelectResourceConfigResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectResourceConfig.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectresourceconfigpaginator)
         """
```

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/paginator.pyi` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -76,17 +76,16 @@
         list_discovered_resources_paginator: ListDiscoveredResourcesPaginator = client.get_paginator("list_discovered_resources")
         list_resource_evaluations_paginator: ListResourceEvaluationsPaginator = client.get_paginator("list_resource_evaluations")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
         select_aggregate_resource_config_paginator: SelectAggregateResourceConfigPaginator = client.get_paginator("select_aggregate_resource_config")
         select_resource_config_paginator: SelectResourceConfigPaginator = client.get_paginator("select_resource_config")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     AggregatedSourceStatusTypeType,
     ChronologicalOrderType,
@@ -132,19 +131,14 @@
     ResourceFiltersTypeDef,
     ResourceKeyTypeDef,
     SelectAggregateResourceConfigResponseTypeDef,
     SelectResourceConfigResponseTypeDef,
     StatusDetailFiltersTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeAggregateComplianceByConfigRulesPaginator",
     "DescribeAggregateComplianceByConformancePacksPaginator",
     "DescribeAggregationAuthorizationsPaginator",
     "DescribeComplianceByConfigRulePaginator",
     "DescribeComplianceByResourcePaginator",
     "DescribeConfigRuleEvaluationStatusPaginator",
@@ -171,555 +165,591 @@
     "ListDiscoveredResourcesPaginator",
     "ListResourceEvaluationsPaginator",
     "ListTagsForResourcePaginator",
     "SelectAggregateResourceConfigPaginator",
     "SelectResourceConfigPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeAggregateComplianceByConfigRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConfigRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconfigrulespaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         Filters: ConfigRuleComplianceFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAggregateComplianceByConfigRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConfigRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconfigrulespaginator)
         """
 
+
 class DescribeAggregateComplianceByConformancePacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConformancePacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconformancepackspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         Filters: AggregateConformancePackComplianceFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAggregateComplianceByConformancePacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregateComplianceByConformancePacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregatecompliancebyconformancepackspaginator)
         """
 
+
 class DescribeAggregationAuthorizationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregationAuthorizations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregationauthorizationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAggregationAuthorizationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeAggregationAuthorizations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeaggregationauthorizationspaginator)
         """
 
+
 class DescribeComplianceByConfigRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByConfigRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyconfigrulepaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleNames: Sequence[str] = ...,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeComplianceByConfigRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByConfigRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyconfigrulepaginator)
         """
 
+
 class DescribeComplianceByResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyresourcepaginator)
     """
 
     def paginate(
         self,
         *,
         ResourceType: str = ...,
         ResourceId: str = ...,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeComplianceByResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeComplianceByResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describecompliancebyresourcepaginator)
         """
 
+
 class DescribeConfigRuleEvaluationStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRuleEvaluationStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigruleevaluationstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigRuleEvaluationStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRuleEvaluationStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigruleevaluationstatuspaginator)
         """
 
+
 class DescribeConfigRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigrulespaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleNames: Sequence[str] = ...,
         Filters: DescribeConfigRulesFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigrulespaginator)
         """
 
+
 class DescribeConfigurationAggregatorSourcesStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregatorSourcesStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorsourcesstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         UpdateStatus: Sequence[AggregatedSourceStatusTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigurationAggregatorSourcesStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregatorSourcesStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorsourcesstatuspaginator)
         """
 
+
 class DescribeConfigurationAggregatorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregators)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConfigurationAggregatorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConfigurationAggregators.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconfigurationaggregatorspaginator)
         """
 
+
 class DescribeConformancePackStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePackStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConformancePackStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePackStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackstatuspaginator)
         """
 
+
 class DescribeConformancePacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackspaginator)
     """
 
     def paginate(
         self,
         *,
         ConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeConformancePacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeConformancePacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeconformancepackspaginator)
         """
 
+
 class DescribeOrganizationConfigRuleStatusesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRuleStatuses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulestatusespaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConfigRuleNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConfigRuleStatusesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRuleStatuses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulestatusespaginator)
         """
 
+
 class DescribeOrganizationConfigRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulespaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConfigRuleNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConfigRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConfigRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconfigrulespaginator)
         """
 
+
 class DescribeOrganizationConformancePackStatusesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePackStatuses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackstatusespaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConformancePackStatusesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePackStatuses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackstatusespaginator)
         """
 
+
 class DescribeOrganizationConformancePacksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePacks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackspaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConformancePackNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeOrganizationConformancePacksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeOrganizationConformancePacks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeorganizationconformancepackspaginator)
         """
 
+
 class DescribePendingAggregationRequestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribePendingAggregationRequests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describependingaggregationrequestspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePendingAggregationRequestsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribePendingAggregationRequests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describependingaggregationrequestspaginator)
         """
 
+
 class DescribeRemediationExecutionStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRemediationExecutionStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeremediationexecutionstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleName: str,
         ResourceKeys: Sequence[ResourceKeyTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRemediationExecutionStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRemediationExecutionStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeremediationexecutionstatuspaginator)
         """
 
+
 class DescribeRetentionConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRetentionConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeretentionconfigurationspaginator)
     """
 
     def paginate(
         self,
         *,
         RetentionConfigurationNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRetentionConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.DescribeRetentionConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#describeretentionconfigurationspaginator)
         """
 
+
 class GetAggregateComplianceDetailsByConfigRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetAggregateComplianceDetailsByConfigRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getaggregatecompliancedetailsbyconfigrulepaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         ConfigRuleName: str,
         AccountId: str,
         AwsRegion: str,
         ComplianceType: ComplianceTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetAggregateComplianceDetailsByConfigRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetAggregateComplianceDetailsByConfigRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getaggregatecompliancedetailsbyconfigrulepaginator)
         """
 
+
 class GetComplianceDetailsByConfigRulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByConfigRule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyconfigrulepaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigRuleName: str,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetComplianceDetailsByConfigRuleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByConfigRule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyconfigrulepaginator)
         """
 
+
 class GetComplianceDetailsByResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyresourcepaginator)
     """
 
     def paginate(
         self,
         *,
         ResourceType: str = ...,
         ResourceId: str = ...,
         ComplianceTypes: Sequence[ComplianceTypeType] = ...,
         ResourceEvaluationId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetComplianceDetailsByResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetComplianceDetailsByResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getcompliancedetailsbyresourcepaginator)
         """
 
+
 class GetConformancePackComplianceSummaryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetConformancePackComplianceSummary)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getconformancepackcompliancesummarypaginator)
     """
 
     def paginate(
-        self, *, ConformancePackNames: Sequence[str], PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        ConformancePackNames: Sequence[str],
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConformancePackComplianceSummaryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetConformancePackComplianceSummary.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getconformancepackcompliancesummarypaginator)
         """
 
+
 class GetOrganizationConfigRuleDetailedStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConfigRuleDetailedStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconfigruledetailedstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConfigRuleName: str,
         Filters: StatusDetailFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOrganizationConfigRuleDetailedStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConfigRuleDetailedStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconfigruledetailedstatuspaginator)
         """
 
+
 class GetOrganizationConformancePackDetailedStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConformancePackDetailedStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconformancepackdetailedstatuspaginator)
     """
 
     def paginate(
         self,
         *,
         OrganizationConformancePackName: str,
         Filters: OrganizationResourceDetailedStatusFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOrganizationConformancePackDetailedStatusResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetOrganizationConformancePackDetailedStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getorganizationconformancepackdetailedstatuspaginator)
         """
 
+
 class GetResourceConfigHistoryPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetResourceConfigHistory)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getresourceconfighistorypaginator)
     """
 
     def paginate(
         self,
         *,
         resourceType: ResourceTypeType,
         resourceId: str,
         laterTime: Union[datetime, str] = ...,
         earlierTime: Union[datetime, str] = ...,
         chronologicalOrder: ChronologicalOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourceConfigHistoryResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.GetResourceConfigHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#getresourceconfighistorypaginator)
         """
 
+
 class ListAggregateDiscoveredResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListAggregateDiscoveredResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listaggregatediscoveredresourcespaginator)
     """
 
     def paginate(
         self,
         *,
         ConfigurationAggregatorName: str,
         ResourceType: ResourceTypeType,
         Filters: ResourceFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAggregateDiscoveredResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListAggregateDiscoveredResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listaggregatediscoveredresourcespaginator)
         """
 
+
 class ListDiscoveredResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListDiscoveredResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listdiscoveredresourcespaginator)
     """
 
     def paginate(
         self,
         *,
         resourceType: ResourceTypeType,
         resourceIds: Sequence[str] = ...,
         resourceName: str = ...,
         includeDeletedResources: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDiscoveredResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListDiscoveredResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listdiscoveredresourcespaginator)
         """
 
+
 class ListResourceEvaluationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListResourceEvaluations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listresourceevaluationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: ResourceEvaluationFiltersTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceEvaluationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListResourceEvaluations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listresourceevaluationspaginator)
         """
 
+
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#listtagsforresourcepaginator)
         """
 
+
 class SelectAggregateResourceConfigPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectAggregateResourceConfig)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectaggregateresourceconfigpaginator)
     """
 
     def paginate(
         self,
         *,
         Expression: str,
         ConfigurationAggregatorName: str,
         MaxResults: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SelectAggregateResourceConfigResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectAggregateResourceConfig.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectaggregateresourceconfigpaginator)
         """
 
+
 class SelectResourceConfigPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectResourceConfig)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectresourceconfigpaginator)
     """
 
     def paginate(
-        self, *, Expression: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Expression: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SelectResourceConfigResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService.Paginator.SelectResourceConfig.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/paginators/#selectresourceconfigpaginator)
         """
```

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/type_defs.py` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -34,14 +34,15 @@
     OrganizationConfigRuleTriggerTypeNoSNType,
     OrganizationConfigRuleTriggerTypeType,
     OrganizationResourceDetailedStatusType,
     OrganizationResourceStatusType,
     OrganizationRuleStatusType,
     OwnerType,
     RecorderStatusType,
+    RecordingStrategyTypeType,
     RemediationExecutionStateType,
     RemediationExecutionStepStateType,
     ResourceCountGroupKeyType,
     ResourceEvaluationStatusType,
     ResourceTypeType,
     SortOrderType,
 )
@@ -62,29 +63,27 @@
     "AggregateConformancePackComplianceCountTypeDef",
     "AggregateConformancePackComplianceFiltersTypeDef",
     "AggregateConformancePackComplianceSummaryFiltersTypeDef",
     "AggregateResourceIdentifierTypeDef",
     "AggregatedSourceStatusTypeDef",
     "AggregationAuthorizationTypeDef",
     "BaseConfigurationItemTypeDef",
-    "ResponseMetadataTypeDef",
     "ResourceKeyTypeDef",
     "ComplianceContributorCountTypeDef",
     "ConfigExportDeliveryInfoTypeDef",
     "ConfigRuleComplianceFiltersTypeDef",
     "ConfigRuleComplianceSummaryFiltersTypeDef",
     "ConfigRuleEvaluationStatusTypeDef",
     "EvaluationModeConfigurationTypeDef",
     "ScopeTypeDef",
     "ConfigSnapshotDeliveryPropertiesTypeDef",
     "ConfigStreamDeliveryInfoTypeDef",
     "OrganizationAggregationSourceTypeDef",
     "RelationshipTypeDef",
     "ConfigurationRecorderStatusTypeDef",
-    "RecordingGroupTypeDef",
     "ConformancePackComplianceFiltersTypeDef",
     "ConformancePackComplianceScoreTypeDef",
     "ConformancePackComplianceScoresFiltersTypeDef",
     "ConformancePackComplianceSummaryTypeDef",
     "ConformancePackInputParameterTypeDef",
     "TemplateSSMDocumentDetailsTypeDef",
     "ConformancePackEvaluationFiltersTypeDef",
@@ -103,128 +102,156 @@
     "DeletePendingAggregationRequestRequestRequestTypeDef",
     "DeleteRemediationConfigurationRequestRequestTypeDef",
     "RemediationExceptionResourceKeyTypeDef",
     "DeleteResourceConfigRequestRequestTypeDef",
     "DeleteRetentionConfigurationRequestRequestTypeDef",
     "DeleteStoredQueryRequestRequestTypeDef",
     "DeliverConfigSnapshotRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DeliverConfigSnapshotResponseTypeDef",
+    "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
     "DescribeAggregationAuthorizationsRequestRequestTypeDef",
+    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
     "DescribeComplianceByConfigRuleRequestRequestTypeDef",
+    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
     "DescribeComplianceByResourceRequestRequestTypeDef",
+    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
     "DescribeConfigRuleEvaluationStatusRequestRequestTypeDef",
     "DescribeConfigRulesFiltersTypeDef",
+    "DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
     "DescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef",
+    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
     "DescribeConfigurationAggregatorsRequestRequestTypeDef",
     "DescribeConfigurationRecorderStatusRequestRequestTypeDef",
     "DescribeConfigurationRecordersRequestRequestTypeDef",
+    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
     "DescribeConformancePackStatusRequestRequestTypeDef",
+    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
     "DescribeConformancePacksRequestRequestTypeDef",
     "DescribeDeliveryChannelStatusRequestRequestTypeDef",
     "DescribeDeliveryChannelsRequestRequestTypeDef",
+    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
     "DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef",
     "OrganizationConfigRuleStatusTypeDef",
+    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
     "DescribeOrganizationConfigRulesRequestRequestTypeDef",
+    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
     "DescribeOrganizationConformancePackStatusesRequestRequestTypeDef",
     "OrganizationConformancePackStatusTypeDef",
+    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
     "DescribeOrganizationConformancePacksRequestRequestTypeDef",
+    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
     "DescribePendingAggregationRequestsRequestRequestTypeDef",
     "PendingAggregationRequestTypeDef",
     "DescribeRemediationConfigurationsRequestRequestTypeDef",
     "RemediationExceptionTypeDef",
+    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
     "DescribeRetentionConfigurationsRequestRequestTypeDef",
     "RetentionConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EvaluationContextTypeDef",
     "EvaluationResultQualifierTypeDef",
     "EvaluationStatusTypeDef",
     "EvaluationTypeDef",
+    "ExclusionByResourceTypesTypeDef",
     "SsmControlsTypeDef",
     "ExternalEvaluationTypeDef",
     "FieldInfoTypeDef",
+    "GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
     "GetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef",
     "ResourceCountFiltersTypeDef",
     "GroupedResourceCountTypeDef",
+    "GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
     "GetComplianceDetailsByConfigRuleRequestRequestTypeDef",
+    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
     "GetComplianceDetailsByResourceRequestRequestTypeDef",
     "GetComplianceSummaryByResourceTypeRequestRequestTypeDef",
+    "GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
     "GetConformancePackComplianceSummaryRequestRequestTypeDef",
     "GetCustomRulePolicyRequestRequestTypeDef",
+    "GetCustomRulePolicyResponseTypeDef",
     "GetDiscoveredResourceCountsRequestRequestTypeDef",
     "ResourceCountTypeDef",
     "StatusDetailFiltersTypeDef",
     "MemberAccountStatusTypeDef",
     "OrganizationResourceDetailedStatusFiltersTypeDef",
     "OrganizationConformancePackDetailedStatusTypeDef",
     "GetOrganizationCustomRulePolicyRequestRequestTypeDef",
+    "GetOrganizationCustomRulePolicyResponseTypeDef",
+    "GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
     "GetResourceConfigHistoryRequestRequestTypeDef",
     "GetResourceEvaluationSummaryRequestRequestTypeDef",
     "ResourceDetailsTypeDef",
     "GetStoredQueryRequestRequestTypeDef",
     "StoredQueryTypeDef",
     "ResourceFiltersTypeDef",
+    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
     "ListDiscoveredResourcesRequestRequestTypeDef",
     "ResourceIdentifierTypeDef",
     "ResourceEvaluationTypeDef",
     "ListStoredQueriesRequestRequestTypeDef",
     "StoredQueryMetadataTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "OrganizationCustomPolicyRuleMetadataNoPolicyTypeDef",
     "OrganizationCustomRuleMetadataTypeDef",
     "OrganizationManagedRuleMetadataTypeDef",
     "OrganizationCustomPolicyRuleMetadataTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutConformancePackResponseTypeDef",
+    "PutOrganizationConfigRuleResponseTypeDef",
+    "PutOrganizationConformancePackResponseTypeDef",
     "PutResourceConfigRequestRequestTypeDef",
     "PutRetentionConfigurationRequestRequestTypeDef",
+    "PutStoredQueryResponseTypeDef",
+    "RecordingStrategyTypeDef",
     "RemediationExecutionStepTypeDef",
     "ResourceValueTypeDef",
     "StaticValueTypeDef",
     "TimeWindowTypeDef",
+    "ResponseMetadataTypeDef",
     "SelectAggregateResourceConfigRequestRequestTypeDef",
+    "SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
     "SelectResourceConfigRequestRequestTypeDef",
+    "SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
     "SourceDetailTypeDef",
     "StartConfigRulesEvaluationRequestRequestTypeDef",
     "StartConfigurationRecorderRequestRequestTypeDef",
+    "StartResourceEvaluationResponseTypeDef",
     "StopConfigurationRecorderRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AggregateComplianceByConformancePackTypeDef",
     "AggregateConformancePackComplianceSummaryTypeDef",
+    "DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
     "DescribeAggregateComplianceByConformancePacksRequestRequestTypeDef",
     "GetAggregateConformancePackComplianceSummaryRequestRequestTypeDef",
     "BatchGetAggregateResourceConfigRequestRequestTypeDef",
     "GetAggregateResourceConfigRequestRequestTypeDef",
-    "BatchGetAggregateResourceConfigResponseTypeDef",
-    "DeliverConfigSnapshotResponseTypeDef",
-    "DescribeAggregationAuthorizationsResponseTypeDef",
-    "DescribeConfigurationAggregatorSourcesStatusResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCustomRulePolicyResponseTypeDef",
-    "GetOrganizationCustomRulePolicyResponseTypeDef",
     "ListAggregateDiscoveredResourcesResponseTypeDef",
+    "DescribeConfigurationAggregatorSourcesStatusResponseTypeDef",
+    "DescribeAggregationAuthorizationsResponseTypeDef",
     "PutAggregationAuthorizationResponseTypeDef",
-    "PutConformancePackResponseTypeDef",
-    "PutOrganizationConfigRuleResponseTypeDef",
-    "PutOrganizationConformancePackResponseTypeDef",
-    "PutStoredQueryResponseTypeDef",
-    "StartResourceEvaluationResponseTypeDef",
+    "BatchGetAggregateResourceConfigResponseTypeDef",
     "BatchGetResourceConfigRequestRequestTypeDef",
     "BatchGetResourceConfigResponseTypeDef",
+    "DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
     "DescribeRemediationExecutionStatusRequestRequestTypeDef",
     "StartRemediationExecutionRequestRequestTypeDef",
     "StartRemediationExecutionResponseTypeDef",
     "ComplianceSummaryTypeDef",
     "ComplianceTypeDef",
+    "DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
     "DescribeAggregateComplianceByConfigRulesRequestRequestTypeDef",
     "GetAggregateConfigRuleComplianceSummaryRequestRequestTypeDef",
     "DescribeConfigRuleEvaluationStatusResponseTypeDef",
     "DeliveryChannelTypeDef",
     "DeliveryChannelStatusTypeDef",
     "ConfigurationAggregatorTypeDef",
     "ConfigurationItemTypeDef",
     "DescribeConfigurationRecorderStatusResponseTypeDef",
-    "ConfigurationRecorderTypeDef",
     "DescribeConformancePackComplianceRequestRequestTypeDef",
     "ListConformancePackComplianceScoresResponseTypeDef",
     "ListConformancePackComplianceScoresRequestRequestTypeDef",
     "GetConformancePackComplianceSummaryResponseTypeDef",
     "OrganizationConformancePackTypeDef",
     "PutOrganizationConformancePackRequestRequestTypeDef",
     "ConformancePackDetailTypeDef",
@@ -232,40 +259,14 @@
     "GetConformancePackComplianceDetailsRequestRequestTypeDef",
     "DescribeConformancePackComplianceResponseTypeDef",
     "DescribeConformancePackStatusResponseTypeDef",
     "DeleteRemediationExceptionsRequestRequestTypeDef",
     "DescribeRemediationExceptionsRequestRequestTypeDef",
     "FailedDeleteRemediationExceptionsBatchTypeDef",
     "PutRemediationExceptionsRequestRequestTypeDef",
-    "DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
-    "DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
-    "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
-    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
-    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
-    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
-    "DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
-    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
-    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
-    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
-    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
-    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
-    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
-    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
-    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
-    "DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
-    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
-    "GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
-    "GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
-    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
-    "GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
-    "GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
-    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
-    "SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
     "DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef",
     "DescribeConfigRulesRequestRequestTypeDef",
     "DescribeOrganizationConfigRuleStatusesResponseTypeDef",
     "DescribeOrganizationConformancePackStatusesResponseTypeDef",
     "DescribePendingAggregationRequestsResponseTypeDef",
     "DescribeRemediationExceptionsResponseTypeDef",
     "FailedRemediationExceptionBatchTypeDef",
@@ -297,14 +298,15 @@
     "ListTagsForResourceResponseTypeDef",
     "PutAggregationAuthorizationRequestRequestTypeDef",
     "PutConfigurationAggregatorRequestRequestTypeDef",
     "PutStoredQueryRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "OrganizationConfigRuleTypeDef",
     "PutOrganizationConfigRuleRequestRequestTypeDef",
+    "RecordingGroupTypeDef",
     "RemediationExecutionStatusTypeDef",
     "RemediationParameterValueTypeDef",
     "ResourceEvaluationFiltersTypeDef",
     "SourceTypeDef",
     "DescribeAggregateComplianceByConformancePacksResponseTypeDef",
     "GetAggregateConformancePackComplianceSummaryResponseTypeDef",
     "AggregateComplianceCountTypeDef",
@@ -316,40 +318,41 @@
     "DescribeDeliveryChannelsResponseTypeDef",
     "PutDeliveryChannelRequestRequestTypeDef",
     "DescribeDeliveryChannelStatusResponseTypeDef",
     "DescribeConfigurationAggregatorsResponseTypeDef",
     "PutConfigurationAggregatorResponseTypeDef",
     "GetAggregateResourceConfigResponseTypeDef",
     "GetResourceConfigHistoryResponseTypeDef",
-    "DescribeConfigurationRecordersResponseTypeDef",
-    "PutConfigurationRecorderRequestRequestTypeDef",
     "DescribeOrganizationConformancePacksResponseTypeDef",
     "DescribeConformancePacksResponseTypeDef",
     "DeleteRemediationExceptionsResponseTypeDef",
     "PutRemediationExceptionsResponseTypeDef",
     "AggregateEvaluationResultTypeDef",
     "ConformancePackEvaluationResultTypeDef",
     "EvaluationResultTypeDef",
     "SelectAggregateResourceConfigResponseTypeDef",
     "SelectResourceConfigResponseTypeDef",
     "DescribeOrganizationConfigRulesResponseTypeDef",
+    "ConfigurationRecorderTypeDef",
     "DescribeRemediationExecutionStatusResponseTypeDef",
     "RemediationConfigurationTypeDef",
     "ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef",
     "ListResourceEvaluationsRequestRequestTypeDef",
     "ConfigRuleTypeDef",
     "GetAggregateConfigRuleComplianceSummaryResponseTypeDef",
     "GetComplianceSummaryByResourceTypeResponseTypeDef",
     "DescribeAggregateComplianceByConfigRulesResponseTypeDef",
     "DescribeComplianceByConfigRuleResponseTypeDef",
     "DescribeComplianceByResourceResponseTypeDef",
     "GetAggregateComplianceDetailsByConfigRuleResponseTypeDef",
     "GetConformancePackComplianceDetailsResponseTypeDef",
     "GetComplianceDetailsByConfigRuleResponseTypeDef",
     "GetComplianceDetailsByResourceResponseTypeDef",
+    "DescribeConfigurationRecordersResponseTypeDef",
+    "PutConfigurationRecorderRequestRequestTypeDef",
     "DescribeRemediationConfigurationsResponseTypeDef",
     "FailedRemediationBatchTypeDef",
     "PutRemediationConfigurationsRequestRequestTypeDef",
     "DescribeConfigRulesResponseTypeDef",
     "PutConfigRuleRequestRequestTypeDef",
     "PutRemediationConfigurationsResponseTypeDef",
 )
@@ -482,25 +485,14 @@
         "resourceCreationTime": datetime,
         "configuration": str,
         "supplementaryConfiguration": Dict[str, str],
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
 ResourceKeyTypeDef = TypedDict(
     "ResourceKeyTypeDef",
     {
         "resourceType": ResourceTypeType,
         "resourceId": str,
     },
 )
@@ -651,24 +643,14 @@
         "lastErrorCode": str,
         "lastErrorMessage": str,
         "lastStatusChangeTime": datetime,
     },
     total=False,
 )
 
-RecordingGroupTypeDef = TypedDict(
-    "RecordingGroupTypeDef",
-    {
-        "allSupported": bool,
-        "includeGlobalResourceTypes": bool,
-        "resourceTypes": List[ResourceTypeType],
-    },
-    total=False,
-)
-
 ConformancePackComplianceFiltersTypeDef = TypedDict(
     "ConformancePackComplianceFiltersTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "ComplianceType": ConformancePackComplianceTypeType,
     },
     total=False,
@@ -926,55 +908,93 @@
 DeliverConfigSnapshotRequestRequestTypeDef = TypedDict(
     "DeliverConfigSnapshotRequestRequestTypeDef",
     {
         "deliveryChannelName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DeliverConfigSnapshotResponseTypeDef = TypedDict(
+    "DeliverConfigSnapshotResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "configSnapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
+)
+
+DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef = (
+    TypedDict(
+        "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
 )
 
 DescribeAggregationAuthorizationsRequestRequestTypeDef = TypedDict(
     "DescribeAggregationAuthorizationsRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef = TypedDict(
+    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
+    {
+        "ConfigRuleNames": Sequence[str],
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeComplianceByConfigRuleRequestRequestTypeDef = TypedDict(
     "DescribeComplianceByConfigRuleRequestRequestTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "ComplianceTypes": Sequence[ComplianceTypeType],
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef = TypedDict(
+    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
+    {
+        "ResourceType": str,
+        "ResourceId": str,
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeComplianceByResourceRequestRequestTypeDef = TypedDict(
     "DescribeComplianceByResourceRequestRequestTypeDef",
     {
         "ResourceType": str,
         "ResourceId": str,
         "ComplianceTypes": Sequence[ComplianceTypeType],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef = TypedDict(
+    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
+    {
+        "ConfigRuleNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConfigRuleEvaluationStatusRequestRequestTypeDef = TypedDict(
     "DescribeConfigRuleEvaluationStatusRequestRequestTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "NextToken": str,
         "Limit": int,
     },
@@ -985,14 +1005,37 @@
     "DescribeConfigRulesFiltersTypeDef",
     {
         "EvaluationMode": EvaluationModeType,
     },
     total=False,
 )
 
+_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
+    "_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+    },
+)
+_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
+    "_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
+    {
+        "UpdateStatus": Sequence[AggregatedSourceStatusTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef(
+    _RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
+    _OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
     },
 )
 _OptionalDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef = TypedDict(
@@ -1009,14 +1052,23 @@
 class DescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef(
     _RequiredDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef,
     _OptionalDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef,
 ):
     pass
 
 
+DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef = TypedDict(
+    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
+    {
+        "ConfigurationAggregatorNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConfigurationAggregatorsRequestRequestTypeDef = TypedDict(
     "DescribeConfigurationAggregatorsRequestRequestTypeDef",
     {
         "ConfigurationAggregatorNames": Sequence[str],
         "NextToken": str,
         "Limit": int,
     },
@@ -1035,24 +1087,42 @@
     "DescribeConfigurationRecordersRequestRequestTypeDef",
     {
         "ConfigurationRecorderNames": Sequence[str],
     },
     total=False,
 )
 
+DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef = TypedDict(
+    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
+    {
+        "ConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConformancePackStatusRequestRequestTypeDef = TypedDict(
     "DescribeConformancePackStatusRequestRequestTypeDef",
     {
         "ConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef = TypedDict(
+    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
+    {
+        "ConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConformancePacksRequestRequestTypeDef = TypedDict(
     "DescribeConformancePacksRequestRequestTypeDef",
     {
         "ConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
@@ -1071,14 +1141,23 @@
     "DescribeDeliveryChannelsRequestRequestTypeDef",
     {
         "DeliveryChannelNames": Sequence[str],
     },
     total=False,
 )
 
+DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
+    {
+        "OrganizationConfigRuleNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef",
     {
         "OrganizationConfigRuleNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
@@ -1105,24 +1184,42 @@
 
 class OrganizationConfigRuleStatusTypeDef(
     _RequiredOrganizationConfigRuleStatusTypeDef, _OptionalOrganizationConfigRuleStatusTypeDef
 ):
     pass
 
 
+DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
+    {
+        "OrganizationConfigRuleNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConfigRulesRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConfigRulesRequestRequestTypeDef",
     {
         "OrganizationConfigRuleNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
+    {
+        "OrganizationConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConformancePackStatusesRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConformancePackStatusesRequestRequestTypeDef",
     {
         "OrganizationConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
@@ -1150,24 +1247,41 @@
 class OrganizationConformancePackStatusTypeDef(
     _RequiredOrganizationConformancePackStatusTypeDef,
     _OptionalOrganizationConformancePackStatusTypeDef,
 ):
     pass
 
 
+DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
+    {
+        "OrganizationConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConformancePacksRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConformancePacksRequestRequestTypeDef",
     {
         "OrganizationConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef = TypedDict(
+    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePendingAggregationRequestsRequestRequestTypeDef = TypedDict(
     "DescribePendingAggregationRequestsRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
@@ -1209,14 +1323,23 @@
 
 class RemediationExceptionTypeDef(
     _RequiredRemediationExceptionTypeDef, _OptionalRemediationExceptionTypeDef
 ):
     pass
 
 
+DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
+    {
+        "RetentionConfigurationNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRetentionConfigurationsRequestRequestTypeDef = TypedDict(
     "DescribeRetentionConfigurationsRequestRequestTypeDef",
     {
         "RetentionConfigurationNames": Sequence[str],
         "NextToken": str,
     },
     total=False,
@@ -1226,14 +1349,21 @@
     "RetentionConfigurationTypeDef",
     {
         "Name": str,
         "RetentionPeriodInDays": int,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EvaluationContextTypeDef = TypedDict(
     "EvaluationContextTypeDef",
     {
         "EvaluationContextIdentifier": str,
     },
     total=False,
 )
@@ -1286,14 +1416,22 @@
 )
 
 
 class EvaluationTypeDef(_RequiredEvaluationTypeDef, _OptionalEvaluationTypeDef):
     pass
 
 
+ExclusionByResourceTypesTypeDef = TypedDict(
+    "ExclusionByResourceTypesTypeDef",
+    {
+        "resourceTypes": List[ResourceTypeType],
+    },
+    total=False,
+)
+
 SsmControlsTypeDef = TypedDict(
     "SsmControlsTypeDef",
     {
         "ConcurrentExecutionRatePercentage": int,
         "ErrorPercentage": int,
     },
     total=False,
@@ -1327,14 +1465,40 @@
     "FieldInfoTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+        "ConfigRuleName": str,
+        "AccountId": str,
+        "AwsRegion": str,
+    },
+)
+_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ComplianceType": ComplianceTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef(
+    _RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
+    _OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef = TypedDict(
     "_RequiredGetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
         "ConfigRuleName": str,
         "AccountId": str,
         "AwsRegion": str,
@@ -1372,14 +1536,37 @@
     "GroupedResourceCountTypeDef",
     {
         "GroupName": str,
         "ResourceCount": int,
     },
 )
 
+_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ConfigRuleName": str,
+    },
+)
+_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef(
+    _RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
+    _OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetComplianceDetailsByConfigRuleRequestRequestTypeDef = TypedDict(
     "_RequiredGetComplianceDetailsByConfigRuleRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
     },
 )
 _OptionalGetComplianceDetailsByConfigRuleRequestRequestTypeDef = TypedDict(
@@ -1396,14 +1583,26 @@
 class GetComplianceDetailsByConfigRuleRequestRequestTypeDef(
     _RequiredGetComplianceDetailsByConfigRuleRequestRequestTypeDef,
     _OptionalGetComplianceDetailsByConfigRuleRequestRequestTypeDef,
 ):
     pass
 
 
+GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef = TypedDict(
+    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
+    {
+        "ResourceType": str,
+        "ResourceId": str,
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "ResourceEvaluationId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetComplianceDetailsByResourceRequestRequestTypeDef = TypedDict(
     "GetComplianceDetailsByResourceRequestRequestTypeDef",
     {
         "ResourceType": str,
         "ResourceId": str,
         "ComplianceTypes": Sequence[ComplianceTypeType],
         "NextToken": str,
@@ -1416,14 +1615,36 @@
     "GetComplianceSummaryByResourceTypeRequestRequestTypeDef",
     {
         "ResourceTypes": Sequence[str],
     },
     total=False,
 )
 
+_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
+    "_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
+    {
+        "ConformancePackNames": Sequence[str],
+    },
+)
+_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
+    "_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef(
+    _RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
+    _OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetConformancePackComplianceSummaryRequestRequestTypeDef = TypedDict(
     "_RequiredGetConformancePackComplianceSummaryRequestRequestTypeDef",
     {
         "ConformancePackNames": Sequence[str],
     },
 )
 _OptionalGetConformancePackComplianceSummaryRequestRequestTypeDef = TypedDict(
@@ -1447,14 +1668,22 @@
     "GetCustomRulePolicyRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
     },
     total=False,
 )
 
+GetCustomRulePolicyResponseTypeDef = TypedDict(
+    "GetCustomRulePolicyResponseTypeDef",
+    {
+        "PolicyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDiscoveredResourceCountsRequestRequestTypeDef = TypedDict(
     "GetDiscoveredResourceCountsRequestRequestTypeDef",
     {
         "resourceTypes": Sequence[str],
         "limit": int,
         "nextToken": str,
     },
@@ -1542,14 +1771,48 @@
 GetOrganizationCustomRulePolicyRequestRequestTypeDef = TypedDict(
     "GetOrganizationCustomRulePolicyRequestRequestTypeDef",
     {
         "OrganizationConfigRuleName": str,
     },
 )
 
+GetOrganizationCustomRulePolicyResponseTypeDef = TypedDict(
+    "GetOrganizationCustomRulePolicyResponseTypeDef",
+    {
+        "PolicyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
+    {
+        "resourceType": ResourceTypeType,
+        "resourceId": str,
+    },
+)
+_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
+    {
+        "laterTime": Union[datetime, str],
+        "earlierTime": Union[datetime, str],
+        "chronologicalOrder": ChronologicalOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef(
+    _RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
+    _OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetResourceConfigHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourceConfigHistoryRequestRequestTypeDef",
     {
         "resourceType": ResourceTypeType,
         "resourceId": str,
     },
 )
@@ -1637,14 +1900,39 @@
         "ResourceId": str,
         "ResourceName": str,
         "Region": str,
     },
     total=False,
 )
 
+_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "resourceType": ResourceTypeType,
+    },
+)
+_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "resourceIds": Sequence[str],
+        "resourceName": str,
+        "includeDeletedResources": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
+    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDiscoveredResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListDiscoveredResourcesRequestRequestTypeDef",
     {
         "resourceType": ResourceTypeType,
     },
 )
 _OptionalListDiscoveredResourcesRequestRequestTypeDef = TypedDict(
@@ -1716,14 +2004,36 @@
 
 class StoredQueryMetadataTypeDef(
     _RequiredStoredQueryMetadataTypeDef, _OptionalStoredQueryMetadataTypeDef
 ):
     pass
 
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -1851,14 +2161,48 @@
 class OrganizationCustomPolicyRuleMetadataTypeDef(
     _RequiredOrganizationCustomPolicyRuleMetadataTypeDef,
     _OptionalOrganizationCustomPolicyRuleMetadataTypeDef,
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
+PutConformancePackResponseTypeDef = TypedDict(
+    "PutConformancePackResponseTypeDef",
+    {
+        "ConformancePackArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutOrganizationConfigRuleResponseTypeDef = TypedDict(
+    "PutOrganizationConfigRuleResponseTypeDef",
+    {
+        "OrganizationConfigRuleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutOrganizationConformancePackResponseTypeDef = TypedDict(
+    "PutOrganizationConformancePackResponseTypeDef",
+    {
+        "OrganizationConformancePackArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutResourceConfigRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourceConfigRequestRequestTypeDef",
     {
         "ResourceType": str,
         "SchemaVersionId": str,
         "ResourceId": str,
         "Configuration": str,
@@ -1883,14 +2227,30 @@
 PutRetentionConfigurationRequestRequestTypeDef = TypedDict(
     "PutRetentionConfigurationRequestRequestTypeDef",
     {
         "RetentionPeriodInDays": int,
     },
 )
 
+PutStoredQueryResponseTypeDef = TypedDict(
+    "PutStoredQueryResponseTypeDef",
+    {
+        "QueryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RecordingStrategyTypeDef = TypedDict(
+    "RecordingStrategyTypeDef",
+    {
+        "useOnly": RecordingStrategyTypeType,
+    },
+    total=False,
+)
+
 RemediationExecutionStepTypeDef = TypedDict(
     "RemediationExecutionStepTypeDef",
     {
         "Name": str,
         "State": RemediationExecutionStepStateType,
         "ErrorMessage": str,
         "StartTime": datetime,
@@ -1918,14 +2278,25 @@
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
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
 _RequiredSelectAggregateResourceConfigRequestRequestTypeDef = TypedDict(
     "_RequiredSelectAggregateResourceConfigRequestRequestTypeDef",
     {
         "Expression": str,
         "ConfigurationAggregatorName": str,
     },
 )
@@ -1943,14 +2314,42 @@
 class SelectAggregateResourceConfigRequestRequestTypeDef(
     _RequiredSelectAggregateResourceConfigRequestRequestTypeDef,
     _OptionalSelectAggregateResourceConfigRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
+    TypedDict(
+        "_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
+        {
+            "Expression": str,
+            "ConfigurationAggregatorName": str,
+        },
+    )
+)
+_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
+    TypedDict(
+        "_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
+        {
+            "MaxResults": int,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+
+class SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef(
+    _RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
+    _OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
+):
+    pass
+
+
 _RequiredSelectResourceConfigRequestRequestTypeDef = TypedDict(
     "_RequiredSelectResourceConfigRequestRequestTypeDef",
     {
         "Expression": str,
     },
 )
 _OptionalSelectResourceConfigRequestRequestTypeDef = TypedDict(
@@ -1966,14 +2365,36 @@
 class SelectResourceConfigRequestRequestTypeDef(
     _RequiredSelectResourceConfigRequestRequestTypeDef,
     _OptionalSelectResourceConfigRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
+    "_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
+    {
+        "Expression": str,
+    },
+)
+_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
+    "_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef(
+    _RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
+    _OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
+):
+    pass
+
+
 SourceDetailTypeDef = TypedDict(
     "SourceDetailTypeDef",
     {
         "EventSource": Literal["aws.config"],
         "MessageType": MessageTypeType,
         "MaximumExecutionFrequency": MaximumExecutionFrequencyType,
     },
@@ -1991,14 +2412,22 @@
 StartConfigurationRecorderRequestRequestTypeDef = TypedDict(
     "StartConfigurationRecorderRequestRequestTypeDef",
     {
         "ConfigurationRecorderName": str,
     },
 )
 
+StartResourceEvaluationResponseTypeDef = TypedDict(
+    "StartResourceEvaluationResponseTypeDef",
+    {
+        "ResourceEvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopConfigurationRecorderRequestRequestTypeDef = TypedDict(
     "StopConfigurationRecorderRequestRequestTypeDef",
     {
         "ConfigurationRecorderName": str,
     },
 )
 
@@ -2026,14 +2455,37 @@
     {
         "ComplianceSummary": AggregateConformancePackComplianceCountTypeDef,
         "GroupName": str,
     },
     total=False,
 )
 
+_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+    },
+)
+_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
+    {
+        "Filters": AggregateConformancePackComplianceFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef(
+    _RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
+    _OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeAggregateComplianceByConformancePacksRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAggregateComplianceByConformancePacksRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
     },
 )
 _OptionalDescribeAggregateComplianceByConformancePacksRequestRequestTypeDef = TypedDict(
@@ -2091,144 +2543,96 @@
     "GetAggregateResourceConfigRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
         "ResourceIdentifier": AggregateResourceIdentifierTypeDef,
     },
 )
 
-BatchGetAggregateResourceConfigResponseTypeDef = TypedDict(
-    "BatchGetAggregateResourceConfigResponseTypeDef",
-    {
-        "BaseConfigurationItems": List[BaseConfigurationItemTypeDef],
-        "UnprocessedResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeliverConfigSnapshotResponseTypeDef = TypedDict(
-    "DeliverConfigSnapshotResponseTypeDef",
-    {
-        "configSnapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAggregationAuthorizationsResponseTypeDef = TypedDict(
-    "DescribeAggregationAuthorizationsResponseTypeDef",
+ListAggregateDiscoveredResourcesResponseTypeDef = TypedDict(
+    "ListAggregateDiscoveredResourcesResponseTypeDef",
     {
-        "AggregationAuthorizations": List[AggregationAuthorizationTypeDef],
+        "ResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConfigurationAggregatorSourcesStatusResponseTypeDef = TypedDict(
     "DescribeConfigurationAggregatorSourcesStatusResponseTypeDef",
     {
         "AggregatedSourceStatusList": List[AggregatedSourceStatusTypeDef],
         "NextToken": str,
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
-GetCustomRulePolicyResponseTypeDef = TypedDict(
-    "GetCustomRulePolicyResponseTypeDef",
-    {
-        "PolicyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOrganizationCustomRulePolicyResponseTypeDef = TypedDict(
-    "GetOrganizationCustomRulePolicyResponseTypeDef",
-    {
-        "PolicyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAggregateDiscoveredResourcesResponseTypeDef = TypedDict(
-    "ListAggregateDiscoveredResourcesResponseTypeDef",
+DescribeAggregationAuthorizationsResponseTypeDef = TypedDict(
+    "DescribeAggregationAuthorizationsResponseTypeDef",
     {
-        "ResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
+        "AggregationAuthorizations": List[AggregationAuthorizationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAggregationAuthorizationResponseTypeDef = TypedDict(
     "PutAggregationAuthorizationResponseTypeDef",
     {
         "AggregationAuthorization": AggregationAuthorizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutConformancePackResponseTypeDef = TypedDict(
-    "PutConformancePackResponseTypeDef",
+BatchGetAggregateResourceConfigResponseTypeDef = TypedDict(
+    "BatchGetAggregateResourceConfigResponseTypeDef",
     {
-        "ConformancePackArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BaseConfigurationItems": List[BaseConfigurationItemTypeDef],
+        "UnprocessedResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutOrganizationConfigRuleResponseTypeDef = TypedDict(
-    "PutOrganizationConfigRuleResponseTypeDef",
+BatchGetResourceConfigRequestRequestTypeDef = TypedDict(
+    "BatchGetResourceConfigRequestRequestTypeDef",
     {
-        "OrganizationConfigRuleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceKeys": Sequence[ResourceKeyTypeDef],
     },
 )
 
-PutOrganizationConformancePackResponseTypeDef = TypedDict(
-    "PutOrganizationConformancePackResponseTypeDef",
+BatchGetResourceConfigResponseTypeDef = TypedDict(
+    "BatchGetResourceConfigResponseTypeDef",
     {
-        "OrganizationConformancePackArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "baseConfigurationItems": List[BaseConfigurationItemTypeDef],
+        "unprocessedResourceKeys": List[ResourceKeyTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutStoredQueryResponseTypeDef = TypedDict(
-    "PutStoredQueryResponseTypeDef",
+_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
+    "_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
     {
-        "QueryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ConfigRuleName": str,
     },
 )
-
-StartResourceEvaluationResponseTypeDef = TypedDict(
-    "StartResourceEvaluationResponseTypeDef",
+_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
+    "_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
     {
-        "ResourceEvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceKeys": Sequence[ResourceKeyTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-BatchGetResourceConfigRequestRequestTypeDef = TypedDict(
-    "BatchGetResourceConfigRequestRequestTypeDef",
-    {
-        "resourceKeys": Sequence[ResourceKeyTypeDef],
-    },
-)
 
-BatchGetResourceConfigResponseTypeDef = TypedDict(
-    "BatchGetResourceConfigResponseTypeDef",
-    {
-        "baseConfigurationItems": List[BaseConfigurationItemTypeDef],
-        "unprocessedResourceKeys": List[ResourceKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef(
+    _RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
+    _OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
+):
+    pass
+
 
 _RequiredDescribeRemediationExecutionStatusRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRemediationExecutionStatusRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
     },
 )
@@ -2259,15 +2663,15 @@
 )
 
 StartRemediationExecutionResponseTypeDef = TypedDict(
     "StartRemediationExecutionResponseTypeDef",
     {
         "FailureMessage": str,
         "FailedItems": List[ResourceKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComplianceSummaryTypeDef = TypedDict(
     "ComplianceSummaryTypeDef",
     {
         "CompliantResourceCount": ComplianceContributorCountTypeDef,
@@ -2282,14 +2686,37 @@
     {
         "ComplianceType": ComplianceTypeType,
         "ComplianceContributorCount": ComplianceContributorCountTypeDef,
     },
     total=False,
 )
 
+_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+    },
+)
+_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
+    {
+        "Filters": ConfigRuleComplianceFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef(
+    _RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
+    _OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeAggregateComplianceByConfigRulesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAggregateComplianceByConfigRulesRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
     },
 )
 _OptionalDescribeAggregateComplianceByConfigRulesRequestRequestTypeDef = TypedDict(
@@ -2336,15 +2763,15 @@
 
 
 DescribeConfigRuleEvaluationStatusResponseTypeDef = TypedDict(
     "DescribeConfigRuleEvaluationStatusResponseTypeDef",
     {
         "ConfigRulesEvaluationStatus": List[ConfigRuleEvaluationStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeliveryChannelTypeDef = TypedDict(
     "DeliveryChannelTypeDef",
     {
         "name": str,
@@ -2407,26 +2834,16 @@
     total=False,
 )
 
 DescribeConfigurationRecorderStatusResponseTypeDef = TypedDict(
     "DescribeConfigurationRecorderStatusResponseTypeDef",
     {
         "ConfigurationRecordersStatus": List[ConfigurationRecorderStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConfigurationRecorderTypeDef = TypedDict(
-    "ConfigurationRecorderTypeDef",
-    {
-        "name": str,
-        "roleARN": str,
-        "recordingGroup": RecordingGroupTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredDescribeConformancePackComplianceRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConformancePackComplianceRequestRequestTypeDef",
     {
         "ConformancePackName": str,
     },
@@ -2450,15 +2867,15 @@
 
 
 ListConformancePackComplianceScoresResponseTypeDef = TypedDict(
     "ListConformancePackComplianceScoresResponseTypeDef",
     {
         "NextToken": str,
         "ConformancePackComplianceScores": List[ConformancePackComplianceScoreTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConformancePackComplianceScoresRequestRequestTypeDef = TypedDict(
     "ListConformancePackComplianceScoresRequestRequestTypeDef",
     {
         "Filters": ConformancePackComplianceScoresFiltersTypeDef,
@@ -2471,15 +2888,15 @@
 )
 
 GetConformancePackComplianceSummaryResponseTypeDef = TypedDict(
     "GetConformancePackComplianceSummaryResponseTypeDef",
     {
         "ConformancePackComplianceSummaryList": List[ConformancePackComplianceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOrganizationConformancePackTypeDef = TypedDict(
     "_RequiredOrganizationConformancePackTypeDef",
     {
         "OrganizationConformancePackName": str,
@@ -2613,24 +3030,24 @@
 
 DescribeConformancePackComplianceResponseTypeDef = TypedDict(
     "DescribeConformancePackComplianceResponseTypeDef",
     {
         "ConformancePackName": str,
         "ConformancePackRuleComplianceList": List[ConformancePackRuleComplianceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConformancePackStatusResponseTypeDef = TypedDict(
     "DescribeConformancePackStatusResponseTypeDef",
     {
         "ConformancePackStatusDetails": List[ConformancePackStatusDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRemediationExceptionsRequestRequestTypeDef = TypedDict(
     "DeleteRemediationExceptionsRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
@@ -2691,438 +3108,20 @@
 class PutRemediationExceptionsRequestRequestTypeDef(
     _RequiredPutRemediationExceptionsRequestRequestTypeDef,
     _OptionalPutRemediationExceptionsRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-    },
-)
-_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
-    {
-        "Filters": ConfigRuleComplianceFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef(
-    _RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
-    _OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-    },
-)
-_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
-    {
-        "Filters": AggregateConformancePackComplianceFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef(
-    _RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
-    _OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
-):
-    pass
-
-
-DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef = (
-    TypedDict(
-        "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef = TypedDict(
-    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
-    {
-        "ConfigRuleNames": Sequence[str],
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef = TypedDict(
-    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
-    {
-        "ResourceType": str,
-        "ResourceId": str,
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef = TypedDict(
-    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
-    {
-        "ConfigRuleNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
-    "_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-    },
-)
-_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
-    "_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
-    {
-        "UpdateStatus": Sequence[AggregatedSourceStatusTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef(
-    _RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
-    _OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
-):
-    pass
-
-
-DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef = TypedDict(
-    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
-    {
-        "ConfigurationAggregatorNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef = TypedDict(
-    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
-    {
-        "ConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef = TypedDict(
-    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
-    {
-        "ConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
-    {
-        "OrganizationConfigRuleNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
-    {
-        "OrganizationConfigRuleNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
-    {
-        "OrganizationConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
-    {
-        "OrganizationConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef = TypedDict(
-    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
-    "_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
-    {
-        "ConfigRuleName": str,
-    },
-)
-_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
-    "_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
-    {
-        "ResourceKeys": Sequence[ResourceKeyTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef(
-    _RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
-    _OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
-):
-    pass
-
-
-DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
-    {
-        "RetentionConfigurationNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-        "ConfigRuleName": str,
-        "AccountId": str,
-        "AwsRegion": str,
-    },
-)
-_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ComplianceType": ComplianceTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef(
-    _RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
-    _OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ConfigRuleName": str,
-    },
-)
-_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef(
-    _RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
-    _OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
-):
-    pass
-
-
-GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef = TypedDict(
-    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
-    {
-        "ResourceType": str,
-        "ResourceId": str,
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "ResourceEvaluationId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
-    "_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
-    {
-        "ConformancePackNames": Sequence[str],
-    },
-)
-_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
-    "_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef(
-    _RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
-    _OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
-    {
-        "resourceType": ResourceTypeType,
-        "resourceId": str,
-    },
-)
-_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
-    {
-        "laterTime": Union[datetime, str],
-        "earlierTime": Union[datetime, str],
-        "chronologicalOrder": ChronologicalOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef(
-    _RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
-    _OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "resourceType": ResourceTypeType,
-    },
-)
-_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "resourceIds": Sequence[str],
-        "resourceName": str,
-        "includeDeletedResources": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
-    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
-_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
-    TypedDict(
-        "_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
-        {
-            "Expression": str,
-            "ConfigurationAggregatorName": str,
-        },
-    )
-)
-_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
-    TypedDict(
-        "_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
-        {
-            "MaxResults": int,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-
-class SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef(
-    _RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
-    _OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
-):
-    pass
-
-
-_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
-    "_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
-    {
-        "Expression": str,
-    },
-)
-_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
-    "_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef(
-    _RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
-    _OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
-):
-    pass
-
-
 DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef = TypedDict(
     "DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "Filters": DescribeConfigRulesFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeConfigRulesRequestRequestTypeDef = TypedDict(
     "DescribeConfigRulesRequestRequestTypeDef",
     {
@@ -3134,42 +3133,42 @@
 )
 
 DescribeOrganizationConfigRuleStatusesResponseTypeDef = TypedDict(
     "DescribeOrganizationConfigRuleStatusesResponseTypeDef",
     {
         "OrganizationConfigRuleStatuses": List[OrganizationConfigRuleStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConformancePackStatusesResponseTypeDef = TypedDict(
     "DescribeOrganizationConformancePackStatusesResponseTypeDef",
     {
         "OrganizationConformancePackStatuses": List[OrganizationConformancePackStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePendingAggregationRequestsResponseTypeDef = TypedDict(
     "DescribePendingAggregationRequestsResponseTypeDef",
     {
         "PendingAggregationRequests": List[PendingAggregationRequestTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRemediationExceptionsResponseTypeDef = TypedDict(
     "DescribeRemediationExceptionsResponseTypeDef",
     {
         "RemediationExceptions": List[RemediationExceptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailedRemediationExceptionBatchTypeDef = TypedDict(
     "FailedRemediationExceptionBatchTypeDef",
     {
         "FailureMessage": str,
@@ -3179,23 +3178,23 @@
 )
 
 DescribeRetentionConfigurationsResponseTypeDef = TypedDict(
     "DescribeRetentionConfigurationsResponseTypeDef",
     {
         "RetentionConfigurations": List[RetentionConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRetentionConfigurationResponseTypeDef = TypedDict(
     "PutRetentionConfigurationResponseTypeDef",
     {
         "RetentionConfiguration": RetentionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EvaluationResultIdentifierTypeDef = TypedDict(
     "EvaluationResultIdentifierTypeDef",
     {
         "EvaluationResultQualifier": EvaluationResultQualifierTypeDef,
@@ -3227,15 +3226,15 @@
     pass
 
 
 PutEvaluationsResponseTypeDef = TypedDict(
     "PutEvaluationsResponseTypeDef",
     {
         "FailedEvaluations": List[EvaluationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecutionControlsTypeDef = TypedDict(
     "ExecutionControlsTypeDef",
     {
         "SsmControls": SsmControlsTypeDef,
@@ -3287,39 +3286,39 @@
 GetAggregateDiscoveredResourceCountsResponseTypeDef = TypedDict(
     "GetAggregateDiscoveredResourceCountsResponseTypeDef",
     {
         "TotalDiscoveredResources": int,
         "GroupByKey": str,
         "GroupedResourceCounts": List[GroupedResourceCountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiscoveredResourceCountsResponseTypeDef = TypedDict(
     "GetDiscoveredResourceCountsResponseTypeDef",
     {
         "totalDiscoveredResources": int,
         "resourceCounts": List[ResourceCountTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef = TypedDict(
     "_RequiredGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef",
     {
         "OrganizationConfigRuleName": str,
     },
 )
 _OptionalGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef = TypedDict(
     "_OptionalGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef",
     {
         "Filters": StatusDetailFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef(
     _RequiredGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef,
@@ -3353,29 +3352,29 @@
 
 
 GetOrganizationConfigRuleDetailedStatusResponseTypeDef = TypedDict(
     "GetOrganizationConfigRuleDetailedStatusResponseTypeDef",
     {
         "OrganizationConfigRuleDetailedStatus": List[MemberAccountStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef = TypedDict(
     "_RequiredGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef",
     {
         "OrganizationConformancePackName": str,
     },
 )
 _OptionalGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef = TypedDict(
     "_OptionalGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef",
     {
         "Filters": OrganizationResourceDetailedStatusFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef(
     _RequiredGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef,
@@ -3411,29 +3410,29 @@
 GetOrganizationConformancePackDetailedStatusResponseTypeDef = TypedDict(
     "GetOrganizationConformancePackDetailedStatusResponseTypeDef",
     {
         "OrganizationConformancePackDetailedStatuses": List[
             OrganizationConformancePackDetailedStatusTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceEvaluationSummaryResponseTypeDef = TypedDict(
     "GetResourceEvaluationSummaryResponseTypeDef",
     {
         "ResourceEvaluationId": str,
         "EvaluationMode": EvaluationModeType,
         "EvaluationStatus": EvaluationStatusTypeDef,
         "EvaluationStartTimestamp": datetime,
         "Compliance": ComplianceTypeType,
         "EvaluationContext": EvaluationContextTypeDef,
         "ResourceDetails": ResourceDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartResourceEvaluationRequestRequestTypeDef = TypedDict(
     "_RequiredStartResourceEvaluationRequestRequestTypeDef",
     {
         "ResourceDetails": ResourceDetailsTypeDef,
@@ -3458,30 +3457,30 @@
     pass
 
 
 GetStoredQueryResponseTypeDef = TypedDict(
     "GetStoredQueryResponseTypeDef",
     {
         "StoredQuery": StoredQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef = TypedDict(
     "_RequiredListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef",
     {
         "ConfigurationAggregatorName": str,
         "ResourceType": ResourceTypeType,
     },
 )
 _OptionalListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef = TypedDict(
     "_OptionalListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef",
     {
         "Filters": ResourceFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef(
     _RequiredListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef,
@@ -3516,42 +3515,42 @@
 
 
 ListDiscoveredResourcesResponseTypeDef = TypedDict(
     "ListDiscoveredResourcesResponseTypeDef",
     {
         "resourceIdentifiers": List[ResourceIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceEvaluationsResponseTypeDef = TypedDict(
     "ListResourceEvaluationsResponseTypeDef",
     {
         "ResourceEvaluations": List[ResourceEvaluationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStoredQueriesResponseTypeDef = TypedDict(
     "ListStoredQueriesResponseTypeDef",
     {
         "StoredQueryMetadata": List[StoredQueryMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAggregationAuthorizationRequestRequestTypeDef = TypedDict(
     "_RequiredPutAggregationAuthorizationRequestRequestTypeDef",
     {
         "AuthorizedAccountId": str,
@@ -3674,14 +3673,26 @@
 class PutOrganizationConfigRuleRequestRequestTypeDef(
     _RequiredPutOrganizationConfigRuleRequestRequestTypeDef,
     _OptionalPutOrganizationConfigRuleRequestRequestTypeDef,
 ):
     pass
 
 
+RecordingGroupTypeDef = TypedDict(
+    "RecordingGroupTypeDef",
+    {
+        "allSupported": bool,
+        "includeGlobalResourceTypes": bool,
+        "resourceTypes": List[ResourceTypeType],
+        "exclusionByResourceTypes": ExclusionByResourceTypesTypeDef,
+        "recordingStrategy": RecordingStrategyTypeDef,
+    },
+    total=False,
+)
+
 RemediationExecutionStatusTypeDef = TypedDict(
     "RemediationExecutionStatusTypeDef",
     {
         "ResourceKey": ResourceKeyTypeDef,
         "State": RemediationExecutionStateType,
         "StepDetails": List[RemediationExecutionStepTypeDef],
         "InvocationTime": datetime,
@@ -3731,27 +3742,27 @@
 
 
 DescribeAggregateComplianceByConformancePacksResponseTypeDef = TypedDict(
     "DescribeAggregateComplianceByConformancePacksResponseTypeDef",
     {
         "AggregateComplianceByConformancePacks": List[AggregateComplianceByConformancePackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAggregateConformancePackComplianceSummaryResponseTypeDef = TypedDict(
     "GetAggregateConformancePackComplianceSummaryResponseTypeDef",
     {
         "AggregateConformancePackComplianceSummaries": List[
             AggregateConformancePackComplianceSummaryTypeDef
         ],
         "GroupByKey": str,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AggregateComplianceCountTypeDef = TypedDict(
     "AggregateComplianceCountTypeDef",
     {
         "GroupName": str,
@@ -3769,15 +3780,15 @@
     total=False,
 )
 
 GetComplianceSummaryByConfigRuleResponseTypeDef = TypedDict(
     "GetComplianceSummaryByConfigRuleResponseTypeDef",
     {
         "ComplianceSummary": ComplianceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AggregateComplianceByConfigRuleTypeDef = TypedDict(
     "AggregateComplianceByConfigRuleTypeDef",
     {
         "ConfigRuleName": str,
@@ -3807,113 +3818,98 @@
     total=False,
 )
 
 DescribeDeliveryChannelsResponseTypeDef = TypedDict(
     "DescribeDeliveryChannelsResponseTypeDef",
     {
         "DeliveryChannels": List[DeliveryChannelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDeliveryChannelRequestRequestTypeDef = TypedDict(
     "PutDeliveryChannelRequestRequestTypeDef",
     {
         "DeliveryChannel": DeliveryChannelTypeDef,
     },
 )
 
 DescribeDeliveryChannelStatusResponseTypeDef = TypedDict(
     "DescribeDeliveryChannelStatusResponseTypeDef",
     {
         "DeliveryChannelsStatus": List[DeliveryChannelStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConfigurationAggregatorsResponseTypeDef = TypedDict(
     "DescribeConfigurationAggregatorsResponseTypeDef",
     {
         "ConfigurationAggregators": List[ConfigurationAggregatorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutConfigurationAggregatorResponseTypeDef = TypedDict(
     "PutConfigurationAggregatorResponseTypeDef",
     {
         "ConfigurationAggregator": ConfigurationAggregatorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAggregateResourceConfigResponseTypeDef = TypedDict(
     "GetAggregateResourceConfigResponseTypeDef",
     {
         "ConfigurationItem": ConfigurationItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceConfigHistoryResponseTypeDef = TypedDict(
     "GetResourceConfigHistoryResponseTypeDef",
     {
         "configurationItems": List[ConfigurationItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeConfigurationRecordersResponseTypeDef = TypedDict(
-    "DescribeConfigurationRecordersResponseTypeDef",
-    {
-        "ConfigurationRecorders": List[ConfigurationRecorderTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutConfigurationRecorderRequestRequestTypeDef = TypedDict(
-    "PutConfigurationRecorderRequestRequestTypeDef",
-    {
-        "ConfigurationRecorder": ConfigurationRecorderTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConformancePacksResponseTypeDef = TypedDict(
     "DescribeOrganizationConformancePacksResponseTypeDef",
     {
         "OrganizationConformancePacks": List[OrganizationConformancePackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConformancePacksResponseTypeDef = TypedDict(
     "DescribeConformancePacksResponseTypeDef",
     {
         "ConformancePackDetails": List[ConformancePackDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRemediationExceptionsResponseTypeDef = TypedDict(
     "DeleteRemediationExceptionsResponseTypeDef",
     {
         "FailedBatches": List[FailedDeleteRemediationExceptionsBatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRemediationExceptionsResponseTypeDef = TypedDict(
     "PutRemediationExceptionsResponseTypeDef",
     {
         "FailedBatches": List[FailedRemediationExceptionBatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AggregateEvaluationResultTypeDef = TypedDict(
     "AggregateEvaluationResultTypeDef",
     {
         "EvaluationResultIdentifier": EvaluationResultIdentifierTypeDef,
@@ -3966,43 +3962,53 @@
 
 SelectAggregateResourceConfigResponseTypeDef = TypedDict(
     "SelectAggregateResourceConfigResponseTypeDef",
     {
         "Results": List[str],
         "QueryInfo": QueryInfoTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectResourceConfigResponseTypeDef = TypedDict(
     "SelectResourceConfigResponseTypeDef",
     {
         "Results": List[str],
         "QueryInfo": QueryInfoTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConfigRulesResponseTypeDef = TypedDict(
     "DescribeOrganizationConfigRulesResponseTypeDef",
     {
         "OrganizationConfigRules": List[OrganizationConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ConfigurationRecorderTypeDef = TypedDict(
+    "ConfigurationRecorderTypeDef",
+    {
+        "name": str,
+        "roleARN": str,
+        "recordingGroup": RecordingGroupTypeDef,
+    },
+    total=False,
+)
+
 DescribeRemediationExecutionStatusResponseTypeDef = TypedDict(
     "DescribeRemediationExecutionStatusResponseTypeDef",
     {
         "RemediationExecutionStatuses": List[RemediationExecutionStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRemediationConfigurationTypeDef = TypedDict(
     "_RequiredRemediationConfigurationTypeDef",
     {
         "ConfigRuleName": str,
@@ -4033,15 +4039,15 @@
     pass
 
 
 ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef = TypedDict(
     "ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef",
     {
         "Filters": ResourceEvaluationFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListResourceEvaluationsRequestRequestTypeDef = TypedDict(
     "ListResourceEvaluationsRequestRequestTypeDef",
     {
@@ -4082,95 +4088,110 @@
 
 GetAggregateConfigRuleComplianceSummaryResponseTypeDef = TypedDict(
     "GetAggregateConfigRuleComplianceSummaryResponseTypeDef",
     {
         "GroupByKey": str,
         "AggregateComplianceCounts": List[AggregateComplianceCountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceSummaryByResourceTypeResponseTypeDef = TypedDict(
     "GetComplianceSummaryByResourceTypeResponseTypeDef",
     {
         "ComplianceSummariesByResourceType": List[ComplianceSummaryByResourceTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAggregateComplianceByConfigRulesResponseTypeDef = TypedDict(
     "DescribeAggregateComplianceByConfigRulesResponseTypeDef",
     {
         "AggregateComplianceByConfigRules": List[AggregateComplianceByConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComplianceByConfigRuleResponseTypeDef = TypedDict(
     "DescribeComplianceByConfigRuleResponseTypeDef",
     {
         "ComplianceByConfigRules": List[ComplianceByConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComplianceByResourceResponseTypeDef = TypedDict(
     "DescribeComplianceByResourceResponseTypeDef",
     {
         "ComplianceByResources": List[ComplianceByResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAggregateComplianceDetailsByConfigRuleResponseTypeDef = TypedDict(
     "GetAggregateComplianceDetailsByConfigRuleResponseTypeDef",
     {
         "AggregateEvaluationResults": List[AggregateEvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConformancePackComplianceDetailsResponseTypeDef = TypedDict(
     "GetConformancePackComplianceDetailsResponseTypeDef",
     {
         "ConformancePackName": str,
         "ConformancePackRuleEvaluationResults": List[ConformancePackEvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceDetailsByConfigRuleResponseTypeDef = TypedDict(
     "GetComplianceDetailsByConfigRuleResponseTypeDef",
     {
         "EvaluationResults": List[EvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceDetailsByResourceResponseTypeDef = TypedDict(
     "GetComplianceDetailsByResourceResponseTypeDef",
     {
         "EvaluationResults": List[EvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeConfigurationRecordersResponseTypeDef = TypedDict(
+    "DescribeConfigurationRecordersResponseTypeDef",
+    {
+        "ConfigurationRecorders": List[ConfigurationRecorderTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutConfigurationRecorderRequestRequestTypeDef = TypedDict(
+    "PutConfigurationRecorderRequestRequestTypeDef",
+    {
+        "ConfigurationRecorder": ConfigurationRecorderTypeDef,
     },
 )
 
 DescribeRemediationConfigurationsResponseTypeDef = TypedDict(
     "DescribeRemediationConfigurationsResponseTypeDef",
     {
         "RemediationConfigurations": List[RemediationConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailedRemediationBatchTypeDef = TypedDict(
     "FailedRemediationBatchTypeDef",
     {
         "FailureMessage": str,
@@ -4187,15 +4208,15 @@
 )
 
 DescribeConfigRulesResponseTypeDef = TypedDict(
     "DescribeConfigRulesResponseTypeDef",
     {
         "ConfigRules": List[ConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutConfigRuleRequestRequestTypeDef = TypedDict(
     "_RequiredPutConfigRuleRequestRequestTypeDef",
     {
         "ConfigRule": ConfigRuleTypeDef,
@@ -4216,10 +4237,10 @@
     pass
 
 
 PutRemediationConfigurationsResponseTypeDef = TypedDict(
     "PutRemediationConfigurationsResponseTypeDef",
     {
         "FailedBatches": List[FailedRemediationBatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config/type_defs.pyi` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -34,14 +34,15 @@
     OrganizationConfigRuleTriggerTypeNoSNType,
     OrganizationConfigRuleTriggerTypeType,
     OrganizationResourceDetailedStatusType,
     OrganizationResourceStatusType,
     OrganizationRuleStatusType,
     OwnerType,
     RecorderStatusType,
+    RecordingStrategyTypeType,
     RemediationExecutionStateType,
     RemediationExecutionStepStateType,
     ResourceCountGroupKeyType,
     ResourceEvaluationStatusType,
     ResourceTypeType,
     SortOrderType,
 )
@@ -61,29 +62,27 @@
     "AggregateConformancePackComplianceCountTypeDef",
     "AggregateConformancePackComplianceFiltersTypeDef",
     "AggregateConformancePackComplianceSummaryFiltersTypeDef",
     "AggregateResourceIdentifierTypeDef",
     "AggregatedSourceStatusTypeDef",
     "AggregationAuthorizationTypeDef",
     "BaseConfigurationItemTypeDef",
-    "ResponseMetadataTypeDef",
     "ResourceKeyTypeDef",
     "ComplianceContributorCountTypeDef",
     "ConfigExportDeliveryInfoTypeDef",
     "ConfigRuleComplianceFiltersTypeDef",
     "ConfigRuleComplianceSummaryFiltersTypeDef",
     "ConfigRuleEvaluationStatusTypeDef",
     "EvaluationModeConfigurationTypeDef",
     "ScopeTypeDef",
     "ConfigSnapshotDeliveryPropertiesTypeDef",
     "ConfigStreamDeliveryInfoTypeDef",
     "OrganizationAggregationSourceTypeDef",
     "RelationshipTypeDef",
     "ConfigurationRecorderStatusTypeDef",
-    "RecordingGroupTypeDef",
     "ConformancePackComplianceFiltersTypeDef",
     "ConformancePackComplianceScoreTypeDef",
     "ConformancePackComplianceScoresFiltersTypeDef",
     "ConformancePackComplianceSummaryTypeDef",
     "ConformancePackInputParameterTypeDef",
     "TemplateSSMDocumentDetailsTypeDef",
     "ConformancePackEvaluationFiltersTypeDef",
@@ -102,128 +101,156 @@
     "DeletePendingAggregationRequestRequestRequestTypeDef",
     "DeleteRemediationConfigurationRequestRequestTypeDef",
     "RemediationExceptionResourceKeyTypeDef",
     "DeleteResourceConfigRequestRequestTypeDef",
     "DeleteRetentionConfigurationRequestRequestTypeDef",
     "DeleteStoredQueryRequestRequestTypeDef",
     "DeliverConfigSnapshotRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DeliverConfigSnapshotResponseTypeDef",
+    "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
     "DescribeAggregationAuthorizationsRequestRequestTypeDef",
+    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
     "DescribeComplianceByConfigRuleRequestRequestTypeDef",
+    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
     "DescribeComplianceByResourceRequestRequestTypeDef",
+    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
     "DescribeConfigRuleEvaluationStatusRequestRequestTypeDef",
     "DescribeConfigRulesFiltersTypeDef",
+    "DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
     "DescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef",
+    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
     "DescribeConfigurationAggregatorsRequestRequestTypeDef",
     "DescribeConfigurationRecorderStatusRequestRequestTypeDef",
     "DescribeConfigurationRecordersRequestRequestTypeDef",
+    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
     "DescribeConformancePackStatusRequestRequestTypeDef",
+    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
     "DescribeConformancePacksRequestRequestTypeDef",
     "DescribeDeliveryChannelStatusRequestRequestTypeDef",
     "DescribeDeliveryChannelsRequestRequestTypeDef",
+    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
     "DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef",
     "OrganizationConfigRuleStatusTypeDef",
+    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
     "DescribeOrganizationConfigRulesRequestRequestTypeDef",
+    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
     "DescribeOrganizationConformancePackStatusesRequestRequestTypeDef",
     "OrganizationConformancePackStatusTypeDef",
+    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
     "DescribeOrganizationConformancePacksRequestRequestTypeDef",
+    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
     "DescribePendingAggregationRequestsRequestRequestTypeDef",
     "PendingAggregationRequestTypeDef",
     "DescribeRemediationConfigurationsRequestRequestTypeDef",
     "RemediationExceptionTypeDef",
+    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
     "DescribeRetentionConfigurationsRequestRequestTypeDef",
     "RetentionConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EvaluationContextTypeDef",
     "EvaluationResultQualifierTypeDef",
     "EvaluationStatusTypeDef",
     "EvaluationTypeDef",
+    "ExclusionByResourceTypesTypeDef",
     "SsmControlsTypeDef",
     "ExternalEvaluationTypeDef",
     "FieldInfoTypeDef",
+    "GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
     "GetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef",
     "ResourceCountFiltersTypeDef",
     "GroupedResourceCountTypeDef",
+    "GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
     "GetComplianceDetailsByConfigRuleRequestRequestTypeDef",
+    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
     "GetComplianceDetailsByResourceRequestRequestTypeDef",
     "GetComplianceSummaryByResourceTypeRequestRequestTypeDef",
+    "GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
     "GetConformancePackComplianceSummaryRequestRequestTypeDef",
     "GetCustomRulePolicyRequestRequestTypeDef",
+    "GetCustomRulePolicyResponseTypeDef",
     "GetDiscoveredResourceCountsRequestRequestTypeDef",
     "ResourceCountTypeDef",
     "StatusDetailFiltersTypeDef",
     "MemberAccountStatusTypeDef",
     "OrganizationResourceDetailedStatusFiltersTypeDef",
     "OrganizationConformancePackDetailedStatusTypeDef",
     "GetOrganizationCustomRulePolicyRequestRequestTypeDef",
+    "GetOrganizationCustomRulePolicyResponseTypeDef",
+    "GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
     "GetResourceConfigHistoryRequestRequestTypeDef",
     "GetResourceEvaluationSummaryRequestRequestTypeDef",
     "ResourceDetailsTypeDef",
     "GetStoredQueryRequestRequestTypeDef",
     "StoredQueryTypeDef",
     "ResourceFiltersTypeDef",
+    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
     "ListDiscoveredResourcesRequestRequestTypeDef",
     "ResourceIdentifierTypeDef",
     "ResourceEvaluationTypeDef",
     "ListStoredQueriesRequestRequestTypeDef",
     "StoredQueryMetadataTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "OrganizationCustomPolicyRuleMetadataNoPolicyTypeDef",
     "OrganizationCustomRuleMetadataTypeDef",
     "OrganizationManagedRuleMetadataTypeDef",
     "OrganizationCustomPolicyRuleMetadataTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutConformancePackResponseTypeDef",
+    "PutOrganizationConfigRuleResponseTypeDef",
+    "PutOrganizationConformancePackResponseTypeDef",
     "PutResourceConfigRequestRequestTypeDef",
     "PutRetentionConfigurationRequestRequestTypeDef",
+    "PutStoredQueryResponseTypeDef",
+    "RecordingStrategyTypeDef",
     "RemediationExecutionStepTypeDef",
     "ResourceValueTypeDef",
     "StaticValueTypeDef",
     "TimeWindowTypeDef",
+    "ResponseMetadataTypeDef",
     "SelectAggregateResourceConfigRequestRequestTypeDef",
+    "SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
     "SelectResourceConfigRequestRequestTypeDef",
+    "SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
     "SourceDetailTypeDef",
     "StartConfigRulesEvaluationRequestRequestTypeDef",
     "StartConfigurationRecorderRequestRequestTypeDef",
+    "StartResourceEvaluationResponseTypeDef",
     "StopConfigurationRecorderRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "AggregateComplianceByConformancePackTypeDef",
     "AggregateConformancePackComplianceSummaryTypeDef",
+    "DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
     "DescribeAggregateComplianceByConformancePacksRequestRequestTypeDef",
     "GetAggregateConformancePackComplianceSummaryRequestRequestTypeDef",
     "BatchGetAggregateResourceConfigRequestRequestTypeDef",
     "GetAggregateResourceConfigRequestRequestTypeDef",
-    "BatchGetAggregateResourceConfigResponseTypeDef",
-    "DeliverConfigSnapshotResponseTypeDef",
-    "DescribeAggregationAuthorizationsResponseTypeDef",
-    "DescribeConfigurationAggregatorSourcesStatusResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCustomRulePolicyResponseTypeDef",
-    "GetOrganizationCustomRulePolicyResponseTypeDef",
     "ListAggregateDiscoveredResourcesResponseTypeDef",
+    "DescribeConfigurationAggregatorSourcesStatusResponseTypeDef",
+    "DescribeAggregationAuthorizationsResponseTypeDef",
     "PutAggregationAuthorizationResponseTypeDef",
-    "PutConformancePackResponseTypeDef",
-    "PutOrganizationConfigRuleResponseTypeDef",
-    "PutOrganizationConformancePackResponseTypeDef",
-    "PutStoredQueryResponseTypeDef",
-    "StartResourceEvaluationResponseTypeDef",
+    "BatchGetAggregateResourceConfigResponseTypeDef",
     "BatchGetResourceConfigRequestRequestTypeDef",
     "BatchGetResourceConfigResponseTypeDef",
+    "DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
     "DescribeRemediationExecutionStatusRequestRequestTypeDef",
     "StartRemediationExecutionRequestRequestTypeDef",
     "StartRemediationExecutionResponseTypeDef",
     "ComplianceSummaryTypeDef",
     "ComplianceTypeDef",
+    "DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
     "DescribeAggregateComplianceByConfigRulesRequestRequestTypeDef",
     "GetAggregateConfigRuleComplianceSummaryRequestRequestTypeDef",
     "DescribeConfigRuleEvaluationStatusResponseTypeDef",
     "DeliveryChannelTypeDef",
     "DeliveryChannelStatusTypeDef",
     "ConfigurationAggregatorTypeDef",
     "ConfigurationItemTypeDef",
     "DescribeConfigurationRecorderStatusResponseTypeDef",
-    "ConfigurationRecorderTypeDef",
     "DescribeConformancePackComplianceRequestRequestTypeDef",
     "ListConformancePackComplianceScoresResponseTypeDef",
     "ListConformancePackComplianceScoresRequestRequestTypeDef",
     "GetConformancePackComplianceSummaryResponseTypeDef",
     "OrganizationConformancePackTypeDef",
     "PutOrganizationConformancePackRequestRequestTypeDef",
     "ConformancePackDetailTypeDef",
@@ -231,40 +258,14 @@
     "GetConformancePackComplianceDetailsRequestRequestTypeDef",
     "DescribeConformancePackComplianceResponseTypeDef",
     "DescribeConformancePackStatusResponseTypeDef",
     "DeleteRemediationExceptionsRequestRequestTypeDef",
     "DescribeRemediationExceptionsRequestRequestTypeDef",
     "FailedDeleteRemediationExceptionsBatchTypeDef",
     "PutRemediationExceptionsRequestRequestTypeDef",
-    "DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
-    "DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
-    "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
-    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
-    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
-    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
-    "DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
-    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
-    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
-    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
-    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
-    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
-    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
-    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
-    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
-    "DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
-    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
-    "GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
-    "GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
-    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
-    "GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
-    "GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
-    "ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    "SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
-    "SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
     "DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef",
     "DescribeConfigRulesRequestRequestTypeDef",
     "DescribeOrganizationConfigRuleStatusesResponseTypeDef",
     "DescribeOrganizationConformancePackStatusesResponseTypeDef",
     "DescribePendingAggregationRequestsResponseTypeDef",
     "DescribeRemediationExceptionsResponseTypeDef",
     "FailedRemediationExceptionBatchTypeDef",
@@ -296,14 +297,15 @@
     "ListTagsForResourceResponseTypeDef",
     "PutAggregationAuthorizationRequestRequestTypeDef",
     "PutConfigurationAggregatorRequestRequestTypeDef",
     "PutStoredQueryRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "OrganizationConfigRuleTypeDef",
     "PutOrganizationConfigRuleRequestRequestTypeDef",
+    "RecordingGroupTypeDef",
     "RemediationExecutionStatusTypeDef",
     "RemediationParameterValueTypeDef",
     "ResourceEvaluationFiltersTypeDef",
     "SourceTypeDef",
     "DescribeAggregateComplianceByConformancePacksResponseTypeDef",
     "GetAggregateConformancePackComplianceSummaryResponseTypeDef",
     "AggregateComplianceCountTypeDef",
@@ -315,40 +317,41 @@
     "DescribeDeliveryChannelsResponseTypeDef",
     "PutDeliveryChannelRequestRequestTypeDef",
     "DescribeDeliveryChannelStatusResponseTypeDef",
     "DescribeConfigurationAggregatorsResponseTypeDef",
     "PutConfigurationAggregatorResponseTypeDef",
     "GetAggregateResourceConfigResponseTypeDef",
     "GetResourceConfigHistoryResponseTypeDef",
-    "DescribeConfigurationRecordersResponseTypeDef",
-    "PutConfigurationRecorderRequestRequestTypeDef",
     "DescribeOrganizationConformancePacksResponseTypeDef",
     "DescribeConformancePacksResponseTypeDef",
     "DeleteRemediationExceptionsResponseTypeDef",
     "PutRemediationExceptionsResponseTypeDef",
     "AggregateEvaluationResultTypeDef",
     "ConformancePackEvaluationResultTypeDef",
     "EvaluationResultTypeDef",
     "SelectAggregateResourceConfigResponseTypeDef",
     "SelectResourceConfigResponseTypeDef",
     "DescribeOrganizationConfigRulesResponseTypeDef",
+    "ConfigurationRecorderTypeDef",
     "DescribeRemediationExecutionStatusResponseTypeDef",
     "RemediationConfigurationTypeDef",
     "ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef",
     "ListResourceEvaluationsRequestRequestTypeDef",
     "ConfigRuleTypeDef",
     "GetAggregateConfigRuleComplianceSummaryResponseTypeDef",
     "GetComplianceSummaryByResourceTypeResponseTypeDef",
     "DescribeAggregateComplianceByConfigRulesResponseTypeDef",
     "DescribeComplianceByConfigRuleResponseTypeDef",
     "DescribeComplianceByResourceResponseTypeDef",
     "GetAggregateComplianceDetailsByConfigRuleResponseTypeDef",
     "GetConformancePackComplianceDetailsResponseTypeDef",
     "GetComplianceDetailsByConfigRuleResponseTypeDef",
     "GetComplianceDetailsByResourceResponseTypeDef",
+    "DescribeConfigurationRecordersResponseTypeDef",
+    "PutConfigurationRecorderRequestRequestTypeDef",
     "DescribeRemediationConfigurationsResponseTypeDef",
     "FailedRemediationBatchTypeDef",
     "PutRemediationConfigurationsRequestRequestTypeDef",
     "DescribeConfigRulesResponseTypeDef",
     "PutConfigRuleRequestRequestTypeDef",
     "PutRemediationConfigurationsResponseTypeDef",
 )
@@ -477,25 +480,14 @@
         "resourceCreationTime": datetime,
         "configuration": str,
         "supplementaryConfiguration": Dict[str, str],
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
 ResourceKeyTypeDef = TypedDict(
     "ResourceKeyTypeDef",
     {
         "resourceType": ResourceTypeType,
         "resourceId": str,
     },
 )
@@ -644,24 +636,14 @@
         "lastErrorCode": str,
         "lastErrorMessage": str,
         "lastStatusChangeTime": datetime,
     },
     total=False,
 )
 
-RecordingGroupTypeDef = TypedDict(
-    "RecordingGroupTypeDef",
-    {
-        "allSupported": bool,
-        "includeGlobalResourceTypes": bool,
-        "resourceTypes": List[ResourceTypeType],
-    },
-    total=False,
-)
-
 ConformancePackComplianceFiltersTypeDef = TypedDict(
     "ConformancePackComplianceFiltersTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "ComplianceType": ConformancePackComplianceTypeType,
     },
     total=False,
@@ -911,55 +893,93 @@
 DeliverConfigSnapshotRequestRequestTypeDef = TypedDict(
     "DeliverConfigSnapshotRequestRequestTypeDef",
     {
         "deliveryChannelName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DeliverConfigSnapshotResponseTypeDef = TypedDict(
+    "DeliverConfigSnapshotResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "configSnapshotId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
+)
+
+DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef = (
+    TypedDict(
+        "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
+        {
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
 )
 
 DescribeAggregationAuthorizationsRequestRequestTypeDef = TypedDict(
     "DescribeAggregationAuthorizationsRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef = TypedDict(
+    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
+    {
+        "ConfigRuleNames": Sequence[str],
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeComplianceByConfigRuleRequestRequestTypeDef = TypedDict(
     "DescribeComplianceByConfigRuleRequestRequestTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "ComplianceTypes": Sequence[ComplianceTypeType],
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef = TypedDict(
+    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
+    {
+        "ResourceType": str,
+        "ResourceId": str,
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeComplianceByResourceRequestRequestTypeDef = TypedDict(
     "DescribeComplianceByResourceRequestRequestTypeDef",
     {
         "ResourceType": str,
         "ResourceId": str,
         "ComplianceTypes": Sequence[ComplianceTypeType],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef = TypedDict(
+    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
+    {
+        "ConfigRuleNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConfigRuleEvaluationStatusRequestRequestTypeDef = TypedDict(
     "DescribeConfigRuleEvaluationStatusRequestRequestTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "NextToken": str,
         "Limit": int,
     },
@@ -970,14 +990,35 @@
     "DescribeConfigRulesFiltersTypeDef",
     {
         "EvaluationMode": EvaluationModeType,
     },
     total=False,
 )
 
+_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
+    "_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+    },
+)
+_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
+    "_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
+    {
+        "UpdateStatus": Sequence[AggregatedSourceStatusTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef(
+    _RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
+    _OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
     },
 )
 _OptionalDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef = TypedDict(
@@ -992,14 +1033,23 @@
 
 class DescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef(
     _RequiredDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef,
     _OptionalDescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef,
 ):
     pass
 
+DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef = TypedDict(
+    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
+    {
+        "ConfigurationAggregatorNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConfigurationAggregatorsRequestRequestTypeDef = TypedDict(
     "DescribeConfigurationAggregatorsRequestRequestTypeDef",
     {
         "ConfigurationAggregatorNames": Sequence[str],
         "NextToken": str,
         "Limit": int,
     },
@@ -1018,24 +1068,42 @@
     "DescribeConfigurationRecordersRequestRequestTypeDef",
     {
         "ConfigurationRecorderNames": Sequence[str],
     },
     total=False,
 )
 
+DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef = TypedDict(
+    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
+    {
+        "ConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConformancePackStatusRequestRequestTypeDef = TypedDict(
     "DescribeConformancePackStatusRequestRequestTypeDef",
     {
         "ConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef = TypedDict(
+    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
+    {
+        "ConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeConformancePacksRequestRequestTypeDef = TypedDict(
     "DescribeConformancePacksRequestRequestTypeDef",
     {
         "ConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
@@ -1054,14 +1122,23 @@
     "DescribeDeliveryChannelsRequestRequestTypeDef",
     {
         "DeliveryChannelNames": Sequence[str],
     },
     total=False,
 )
 
+DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
+    {
+        "OrganizationConfigRuleNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef",
     {
         "OrganizationConfigRuleNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
@@ -1086,24 +1163,42 @@
 )
 
 class OrganizationConfigRuleStatusTypeDef(
     _RequiredOrganizationConfigRuleStatusTypeDef, _OptionalOrganizationConfigRuleStatusTypeDef
 ):
     pass
 
+DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
+    {
+        "OrganizationConfigRuleNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConfigRulesRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConfigRulesRequestRequestTypeDef",
     {
         "OrganizationConfigRuleNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
+    {
+        "OrganizationConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConformancePackStatusesRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConformancePackStatusesRequestRequestTypeDef",
     {
         "OrganizationConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
@@ -1129,24 +1224,41 @@
 
 class OrganizationConformancePackStatusTypeDef(
     _RequiredOrganizationConformancePackStatusTypeDef,
     _OptionalOrganizationConformancePackStatusTypeDef,
 ):
     pass
 
+DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef = TypedDict(
+    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
+    {
+        "OrganizationConformancePackNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeOrganizationConformancePacksRequestRequestTypeDef = TypedDict(
     "DescribeOrganizationConformancePacksRequestRequestTypeDef",
     {
         "OrganizationConformancePackNames": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef = TypedDict(
+    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePendingAggregationRequestsRequestRequestTypeDef = TypedDict(
     "DescribePendingAggregationRequestsRequestRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
@@ -1186,14 +1298,23 @@
 )
 
 class RemediationExceptionTypeDef(
     _RequiredRemediationExceptionTypeDef, _OptionalRemediationExceptionTypeDef
 ):
     pass
 
+DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
+    {
+        "RetentionConfigurationNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRetentionConfigurationsRequestRequestTypeDef = TypedDict(
     "DescribeRetentionConfigurationsRequestRequestTypeDef",
     {
         "RetentionConfigurationNames": Sequence[str],
         "NextToken": str,
     },
     total=False,
@@ -1203,14 +1324,21 @@
     "RetentionConfigurationTypeDef",
     {
         "Name": str,
         "RetentionPeriodInDays": int,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EvaluationContextTypeDef = TypedDict(
     "EvaluationContextTypeDef",
     {
         "EvaluationContextIdentifier": str,
     },
     total=False,
 )
@@ -1259,14 +1387,22 @@
     },
     total=False,
 )
 
 class EvaluationTypeDef(_RequiredEvaluationTypeDef, _OptionalEvaluationTypeDef):
     pass
 
+ExclusionByResourceTypesTypeDef = TypedDict(
+    "ExclusionByResourceTypesTypeDef",
+    {
+        "resourceTypes": List[ResourceTypeType],
+    },
+    total=False,
+)
+
 SsmControlsTypeDef = TypedDict(
     "SsmControlsTypeDef",
     {
         "ConcurrentExecutionRatePercentage": int,
         "ErrorPercentage": int,
     },
     total=False,
@@ -1298,14 +1434,38 @@
     "FieldInfoTypeDef",
     {
         "Name": str,
     },
     total=False,
 )
 
+_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+        "ConfigRuleName": str,
+        "AccountId": str,
+        "AwsRegion": str,
+    },
+)
+_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ComplianceType": ComplianceTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef(
+    _RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
+    _OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
+):
+    pass
+
 _RequiredGetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef = TypedDict(
     "_RequiredGetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
         "ConfigRuleName": str,
         "AccountId": str,
         "AwsRegion": str,
@@ -1341,14 +1501,35 @@
     "GroupedResourceCountTypeDef",
     {
         "GroupName": str,
         "ResourceCount": int,
     },
 )
 
+_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ConfigRuleName": str,
+    },
+)
+_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
+    "_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
+    {
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef(
+    _RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
+    _OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
+):
+    pass
+
 _RequiredGetComplianceDetailsByConfigRuleRequestRequestTypeDef = TypedDict(
     "_RequiredGetComplianceDetailsByConfigRuleRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
     },
 )
 _OptionalGetComplianceDetailsByConfigRuleRequestRequestTypeDef = TypedDict(
@@ -1363,14 +1544,26 @@
 
 class GetComplianceDetailsByConfigRuleRequestRequestTypeDef(
     _RequiredGetComplianceDetailsByConfigRuleRequestRequestTypeDef,
     _OptionalGetComplianceDetailsByConfigRuleRequestRequestTypeDef,
 ):
     pass
 
+GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef = TypedDict(
+    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
+    {
+        "ResourceType": str,
+        "ResourceId": str,
+        "ComplianceTypes": Sequence[ComplianceTypeType],
+        "ResourceEvaluationId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetComplianceDetailsByResourceRequestRequestTypeDef = TypedDict(
     "GetComplianceDetailsByResourceRequestRequestTypeDef",
     {
         "ResourceType": str,
         "ResourceId": str,
         "ComplianceTypes": Sequence[ComplianceTypeType],
         "NextToken": str,
@@ -1383,14 +1576,34 @@
     "GetComplianceSummaryByResourceTypeRequestRequestTypeDef",
     {
         "ResourceTypes": Sequence[str],
     },
     total=False,
 )
 
+_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
+    "_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
+    {
+        "ConformancePackNames": Sequence[str],
+    },
+)
+_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
+    "_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef(
+    _RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
+    _OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetConformancePackComplianceSummaryRequestRequestTypeDef = TypedDict(
     "_RequiredGetConformancePackComplianceSummaryRequestRequestTypeDef",
     {
         "ConformancePackNames": Sequence[str],
     },
 )
 _OptionalGetConformancePackComplianceSummaryRequestRequestTypeDef = TypedDict(
@@ -1412,14 +1625,22 @@
     "GetCustomRulePolicyRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
     },
     total=False,
 )
 
+GetCustomRulePolicyResponseTypeDef = TypedDict(
+    "GetCustomRulePolicyResponseTypeDef",
+    {
+        "PolicyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDiscoveredResourceCountsRequestRequestTypeDef = TypedDict(
     "GetDiscoveredResourceCountsRequestRequestTypeDef",
     {
         "resourceTypes": Sequence[str],
         "limit": int,
         "nextToken": str,
     },
@@ -1503,14 +1724,46 @@
 GetOrganizationCustomRulePolicyRequestRequestTypeDef = TypedDict(
     "GetOrganizationCustomRulePolicyRequestRequestTypeDef",
     {
         "OrganizationConfigRuleName": str,
     },
 )
 
+GetOrganizationCustomRulePolicyResponseTypeDef = TypedDict(
+    "GetOrganizationCustomRulePolicyResponseTypeDef",
+    {
+        "PolicyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
+    "_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
+    {
+        "resourceType": ResourceTypeType,
+        "resourceId": str,
+    },
+)
+_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
+    "_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
+    {
+        "laterTime": Union[datetime, str],
+        "earlierTime": Union[datetime, str],
+        "chronologicalOrder": ChronologicalOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef(
+    _RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
+    _OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
+):
+    pass
+
 _RequiredGetResourceConfigHistoryRequestRequestTypeDef = TypedDict(
     "_RequiredGetResourceConfigHistoryRequestRequestTypeDef",
     {
         "resourceType": ResourceTypeType,
         "resourceId": str,
     },
 )
@@ -1592,14 +1845,37 @@
         "ResourceId": str,
         "ResourceName": str,
         "Region": str,
     },
     total=False,
 )
 
+_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "resourceType": ResourceTypeType,
+    },
+)
+_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
+    {
+        "resourceIds": Sequence[str],
+        "resourceName": str,
+        "includeDeletedResources": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
+    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDiscoveredResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListDiscoveredResourcesRequestRequestTypeDef",
     {
         "resourceType": ResourceTypeType,
     },
 )
 _OptionalListDiscoveredResourcesRequestRequestTypeDef = TypedDict(
@@ -1667,14 +1943,34 @@
 )
 
 class StoredQueryMetadataTypeDef(
     _RequiredStoredQueryMetadataTypeDef, _OptionalStoredQueryMetadataTypeDef
 ):
     pass
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -1794,14 +2090,48 @@
 
 class OrganizationCustomPolicyRuleMetadataTypeDef(
     _RequiredOrganizationCustomPolicyRuleMetadataTypeDef,
     _OptionalOrganizationCustomPolicyRuleMetadataTypeDef,
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
+PutConformancePackResponseTypeDef = TypedDict(
+    "PutConformancePackResponseTypeDef",
+    {
+        "ConformancePackArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutOrganizationConfigRuleResponseTypeDef = TypedDict(
+    "PutOrganizationConfigRuleResponseTypeDef",
+    {
+        "OrganizationConfigRuleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutOrganizationConformancePackResponseTypeDef = TypedDict(
+    "PutOrganizationConformancePackResponseTypeDef",
+    {
+        "OrganizationConformancePackArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutResourceConfigRequestRequestTypeDef = TypedDict(
     "_RequiredPutResourceConfigRequestRequestTypeDef",
     {
         "ResourceType": str,
         "SchemaVersionId": str,
         "ResourceId": str,
         "Configuration": str,
@@ -1824,14 +2154,30 @@
 PutRetentionConfigurationRequestRequestTypeDef = TypedDict(
     "PutRetentionConfigurationRequestRequestTypeDef",
     {
         "RetentionPeriodInDays": int,
     },
 )
 
+PutStoredQueryResponseTypeDef = TypedDict(
+    "PutStoredQueryResponseTypeDef",
+    {
+        "QueryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RecordingStrategyTypeDef = TypedDict(
+    "RecordingStrategyTypeDef",
+    {
+        "useOnly": RecordingStrategyTypeType,
+    },
+    total=False,
+)
+
 RemediationExecutionStepTypeDef = TypedDict(
     "RemediationExecutionStepTypeDef",
     {
         "Name": str,
         "State": RemediationExecutionStepStateType,
         "ErrorMessage": str,
         "StartTime": datetime,
@@ -1859,14 +2205,25 @@
     {
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
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
 _RequiredSelectAggregateResourceConfigRequestRequestTypeDef = TypedDict(
     "_RequiredSelectAggregateResourceConfigRequestRequestTypeDef",
     {
         "Expression": str,
         "ConfigurationAggregatorName": str,
     },
 )
@@ -1882,14 +2239,40 @@
 
 class SelectAggregateResourceConfigRequestRequestTypeDef(
     _RequiredSelectAggregateResourceConfigRequestRequestTypeDef,
     _OptionalSelectAggregateResourceConfigRequestRequestTypeDef,
 ):
     pass
 
+_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
+    TypedDict(
+        "_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
+        {
+            "Expression": str,
+            "ConfigurationAggregatorName": str,
+        },
+    )
+)
+_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
+    TypedDict(
+        "_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
+        {
+            "MaxResults": int,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
+class SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef(
+    _RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
+    _OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
+):
+    pass
+
 _RequiredSelectResourceConfigRequestRequestTypeDef = TypedDict(
     "_RequiredSelectResourceConfigRequestRequestTypeDef",
     {
         "Expression": str,
     },
 )
 _OptionalSelectResourceConfigRequestRequestTypeDef = TypedDict(
@@ -1903,14 +2286,34 @@
 
 class SelectResourceConfigRequestRequestTypeDef(
     _RequiredSelectResourceConfigRequestRequestTypeDef,
     _OptionalSelectResourceConfigRequestRequestTypeDef,
 ):
     pass
 
+_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
+    "_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
+    {
+        "Expression": str,
+    },
+)
+_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
+    "_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef(
+    _RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
+    _OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
+):
+    pass
+
 SourceDetailTypeDef = TypedDict(
     "SourceDetailTypeDef",
     {
         "EventSource": Literal["aws.config"],
         "MessageType": MessageTypeType,
         "MaximumExecutionFrequency": MaximumExecutionFrequencyType,
     },
@@ -1928,14 +2331,22 @@
 StartConfigurationRecorderRequestRequestTypeDef = TypedDict(
     "StartConfigurationRecorderRequestRequestTypeDef",
     {
         "ConfigurationRecorderName": str,
     },
 )
 
+StartResourceEvaluationResponseTypeDef = TypedDict(
+    "StartResourceEvaluationResponseTypeDef",
+    {
+        "ResourceEvaluationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopConfigurationRecorderRequestRequestTypeDef = TypedDict(
     "StopConfigurationRecorderRequestRequestTypeDef",
     {
         "ConfigurationRecorderName": str,
     },
 )
 
@@ -1963,14 +2374,35 @@
     {
         "ComplianceSummary": AggregateConformancePackComplianceCountTypeDef,
         "GroupName": str,
     },
     total=False,
 )
 
+_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+    },
+)
+_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
+    {
+        "Filters": AggregateConformancePackComplianceFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef(
+    _RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
+    _OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeAggregateComplianceByConformancePacksRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAggregateComplianceByConformancePacksRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
     },
 )
 _OptionalDescribeAggregateComplianceByConformancePacksRequestRequestTypeDef = TypedDict(
@@ -2024,144 +2456,94 @@
     "GetAggregateResourceConfigRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
         "ResourceIdentifier": AggregateResourceIdentifierTypeDef,
     },
 )
 
-BatchGetAggregateResourceConfigResponseTypeDef = TypedDict(
-    "BatchGetAggregateResourceConfigResponseTypeDef",
-    {
-        "BaseConfigurationItems": List[BaseConfigurationItemTypeDef],
-        "UnprocessedResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeliverConfigSnapshotResponseTypeDef = TypedDict(
-    "DeliverConfigSnapshotResponseTypeDef",
-    {
-        "configSnapshotId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAggregationAuthorizationsResponseTypeDef = TypedDict(
-    "DescribeAggregationAuthorizationsResponseTypeDef",
+ListAggregateDiscoveredResourcesResponseTypeDef = TypedDict(
+    "ListAggregateDiscoveredResourcesResponseTypeDef",
     {
-        "AggregationAuthorizations": List[AggregationAuthorizationTypeDef],
+        "ResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConfigurationAggregatorSourcesStatusResponseTypeDef = TypedDict(
     "DescribeConfigurationAggregatorSourcesStatusResponseTypeDef",
     {
         "AggregatedSourceStatusList": List[AggregatedSourceStatusTypeDef],
         "NextToken": str,
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
-GetCustomRulePolicyResponseTypeDef = TypedDict(
-    "GetCustomRulePolicyResponseTypeDef",
-    {
-        "PolicyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetOrganizationCustomRulePolicyResponseTypeDef = TypedDict(
-    "GetOrganizationCustomRulePolicyResponseTypeDef",
-    {
-        "PolicyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAggregateDiscoveredResourcesResponseTypeDef = TypedDict(
-    "ListAggregateDiscoveredResourcesResponseTypeDef",
+DescribeAggregationAuthorizationsResponseTypeDef = TypedDict(
+    "DescribeAggregationAuthorizationsResponseTypeDef",
     {
-        "ResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
+        "AggregationAuthorizations": List[AggregationAuthorizationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAggregationAuthorizationResponseTypeDef = TypedDict(
     "PutAggregationAuthorizationResponseTypeDef",
     {
         "AggregationAuthorization": AggregationAuthorizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutConformancePackResponseTypeDef = TypedDict(
-    "PutConformancePackResponseTypeDef",
-    {
-        "ConformancePackArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutOrganizationConfigRuleResponseTypeDef = TypedDict(
-    "PutOrganizationConfigRuleResponseTypeDef",
+BatchGetAggregateResourceConfigResponseTypeDef = TypedDict(
+    "BatchGetAggregateResourceConfigResponseTypeDef",
     {
-        "OrganizationConfigRuleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BaseConfigurationItems": List[BaseConfigurationItemTypeDef],
+        "UnprocessedResourceIdentifiers": List[AggregateResourceIdentifierTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutOrganizationConformancePackResponseTypeDef = TypedDict(
-    "PutOrganizationConformancePackResponseTypeDef",
+BatchGetResourceConfigRequestRequestTypeDef = TypedDict(
+    "BatchGetResourceConfigRequestRequestTypeDef",
     {
-        "OrganizationConformancePackArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceKeys": Sequence[ResourceKeyTypeDef],
     },
 )
 
-PutStoredQueryResponseTypeDef = TypedDict(
-    "PutStoredQueryResponseTypeDef",
+BatchGetResourceConfigResponseTypeDef = TypedDict(
+    "BatchGetResourceConfigResponseTypeDef",
     {
-        "QueryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "baseConfigurationItems": List[BaseConfigurationItemTypeDef],
+        "unprocessedResourceKeys": List[ResourceKeyTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartResourceEvaluationResponseTypeDef = TypedDict(
-    "StartResourceEvaluationResponseTypeDef",
+_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
+    "_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
     {
-        "ResourceEvaluationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ConfigRuleName": str,
     },
 )
-
-BatchGetResourceConfigRequestRequestTypeDef = TypedDict(
-    "BatchGetResourceConfigRequestRequestTypeDef",
+_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
+    "_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
     {
-        "resourceKeys": Sequence[ResourceKeyTypeDef],
+        "ResourceKeys": Sequence[ResourceKeyTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
+    total=False,
 )
 
-BatchGetResourceConfigResponseTypeDef = TypedDict(
-    "BatchGetResourceConfigResponseTypeDef",
-    {
-        "baseConfigurationItems": List[BaseConfigurationItemTypeDef],
-        "unprocessedResourceKeys": List[ResourceKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef(
+    _RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
+    _OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
+):
+    pass
 
 _RequiredDescribeRemediationExecutionStatusRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeRemediationExecutionStatusRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
     },
 )
@@ -2190,15 +2572,15 @@
 )
 
 StartRemediationExecutionResponseTypeDef = TypedDict(
     "StartRemediationExecutionResponseTypeDef",
     {
         "FailureMessage": str,
         "FailedItems": List[ResourceKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ComplianceSummaryTypeDef = TypedDict(
     "ComplianceSummaryTypeDef",
     {
         "CompliantResourceCount": ComplianceContributorCountTypeDef,
@@ -2213,14 +2595,35 @@
     {
         "ComplianceType": ComplianceTypeType,
         "ComplianceContributorCount": ComplianceContributorCountTypeDef,
     },
     total=False,
 )
 
+_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
+    {
+        "ConfigurationAggregatorName": str,
+    },
+)
+_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
+    {
+        "Filters": ConfigRuleComplianceFiltersTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef(
+    _RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
+    _OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeAggregateComplianceByConfigRulesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeAggregateComplianceByConfigRulesRequestRequestTypeDef",
     {
         "ConfigurationAggregatorName": str,
     },
 )
 _OptionalDescribeAggregateComplianceByConfigRulesRequestRequestTypeDef = TypedDict(
@@ -2263,15 +2666,15 @@
     pass
 
 DescribeConfigRuleEvaluationStatusResponseTypeDef = TypedDict(
     "DescribeConfigRuleEvaluationStatusResponseTypeDef",
     {
         "ConfigRulesEvaluationStatus": List[ConfigRuleEvaluationStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeliveryChannelTypeDef = TypedDict(
     "DeliveryChannelTypeDef",
     {
         "name": str,
@@ -2334,28 +2737,18 @@
     total=False,
 )
 
 DescribeConfigurationRecorderStatusResponseTypeDef = TypedDict(
     "DescribeConfigurationRecorderStatusResponseTypeDef",
     {
         "ConfigurationRecordersStatus": List[ConfigurationRecorderStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ConfigurationRecorderTypeDef = TypedDict(
-    "ConfigurationRecorderTypeDef",
-    {
-        "name": str,
-        "roleARN": str,
-        "recordingGroup": RecordingGroupTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeConformancePackComplianceRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeConformancePackComplianceRequestRequestTypeDef",
     {
         "ConformancePackName": str,
     },
 )
 _OptionalDescribeConformancePackComplianceRequestRequestTypeDef = TypedDict(
@@ -2375,15 +2768,15 @@
     pass
 
 ListConformancePackComplianceScoresResponseTypeDef = TypedDict(
     "ListConformancePackComplianceScoresResponseTypeDef",
     {
         "NextToken": str,
         "ConformancePackComplianceScores": List[ConformancePackComplianceScoreTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConformancePackComplianceScoresRequestRequestTypeDef = TypedDict(
     "ListConformancePackComplianceScoresRequestRequestTypeDef",
     {
         "Filters": ConformancePackComplianceScoresFiltersTypeDef,
@@ -2396,15 +2789,15 @@
 )
 
 GetConformancePackComplianceSummaryResponseTypeDef = TypedDict(
     "GetConformancePackComplianceSummaryResponseTypeDef",
     {
         "ConformancePackComplianceSummaryList": List[ConformancePackComplianceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOrganizationConformancePackTypeDef = TypedDict(
     "_RequiredOrganizationConformancePackTypeDef",
     {
         "OrganizationConformancePackName": str,
@@ -2528,24 +2921,24 @@
 
 DescribeConformancePackComplianceResponseTypeDef = TypedDict(
     "DescribeConformancePackComplianceResponseTypeDef",
     {
         "ConformancePackName": str,
         "ConformancePackRuleComplianceList": List[ConformancePackRuleComplianceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConformancePackStatusResponseTypeDef = TypedDict(
     "DescribeConformancePackStatusResponseTypeDef",
     {
         "ConformancePackStatusDetails": List[ConformancePackStatusDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRemediationExceptionsRequestRequestTypeDef = TypedDict(
     "DeleteRemediationExceptionsRequestRequestTypeDef",
     {
         "ConfigRuleName": str,
@@ -2602,414 +2995,20 @@
 
 class PutRemediationExceptionsRequestRequestTypeDef(
     _RequiredPutRemediationExceptionsRequestRequestTypeDef,
     _OptionalPutRemediationExceptionsRequestRequestTypeDef,
 ):
     pass
 
-_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-    },
-)
-_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef",
-    {
-        "Filters": ConfigRuleComplianceFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef(
-    _RequiredDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
-    _OptionalDescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
-    "_RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-    },
-)
-_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef = TypedDict(
-    "_OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef",
-    {
-        "Filters": AggregateConformancePackComplianceFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef(
-    _RequiredDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
-    _OptionalDescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
-):
-    pass
-
-DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef = (
-    TypedDict(
-        "DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef",
-        {
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef = TypedDict(
-    "DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef",
-    {
-        "ConfigRuleNames": Sequence[str],
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef = TypedDict(
-    "DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef",
-    {
-        "ResourceType": str,
-        "ResourceId": str,
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef = TypedDict(
-    "DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef",
-    {
-        "ConfigRuleNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
-    "_RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-    },
-)
-_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef = TypedDict(
-    "_OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef",
-    {
-        "UpdateStatus": Sequence[AggregatedSourceStatusTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef(
-    _RequiredDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
-    _OptionalDescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
-):
-    pass
-
-DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef = TypedDict(
-    "DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef",
-    {
-        "ConfigurationAggregatorNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef = TypedDict(
-    "DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef",
-    {
-        "ConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef = TypedDict(
-    "DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef",
-    {
-        "ConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef",
-    {
-        "OrganizationConfigRuleNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef",
-    {
-        "OrganizationConfigRuleNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef",
-    {
-        "OrganizationConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef = TypedDict(
-    "DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef",
-    {
-        "OrganizationConformancePackNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef = TypedDict(
-    "DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
-    "_RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
-    {
-        "ConfigRuleName": str,
-    },
-)
-_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef = TypedDict(
-    "_OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef",
-    {
-        "ResourceKeys": Sequence[ResourceKeyTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef(
-    _RequiredDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
-    _OptionalDescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
-):
-    pass
-
-DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef",
-    {
-        "RetentionConfigurationNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ConfigurationAggregatorName": str,
-        "ConfigRuleName": str,
-        "AccountId": str,
-        "AwsRegion": str,
-    },
-)
-_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ComplianceType": ComplianceTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef(
-    _RequiredGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
-    _OptionalGetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
-):
-    pass
-
-_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ConfigRuleName": str,
-    },
-)
-_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef = TypedDict(
-    "_OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef",
-    {
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef(
-    _RequiredGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
-    _OptionalGetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
-):
-    pass
-
-GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef = TypedDict(
-    "GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef",
-    {
-        "ResourceType": str,
-        "ResourceId": str,
-        "ComplianceTypes": Sequence[ComplianceTypeType],
-        "ResourceEvaluationId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
-    "_RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
-    {
-        "ConformancePackNames": Sequence[str],
-    },
-)
-_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef = TypedDict(
-    "_OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef(
-    _RequiredGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
-    _OptionalGetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
-):
-    pass
-
-_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
-    "_RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
-    {
-        "resourceType": ResourceTypeType,
-        "resourceId": str,
-    },
-)
-_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef = TypedDict(
-    "_OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef",
-    {
-        "laterTime": Union[datetime, str],
-        "earlierTime": Union[datetime, str],
-        "chronologicalOrder": ChronologicalOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef(
-    _RequiredGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
-    _OptionalGetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
-):
-    pass
-
-_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "resourceType": ResourceTypeType,
-    },
-)
-_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef",
-    {
-        "resourceIds": Sequence[str],
-        "resourceName": str,
-        "includeDeletedResources": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef(
-    _RequiredListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    _OptionalListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
-    TypedDict(
-        "_RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
-        {
-            "Expression": str,
-            "ConfigurationAggregatorName": str,
-        },
-    )
-)
-_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef = (
-    TypedDict(
-        "_OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef",
-        {
-            "MaxResults": int,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
-
-class SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef(
-    _RequiredSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
-    _OptionalSelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
-):
-    pass
-
-_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
-    "_RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
-    {
-        "Expression": str,
-    },
-)
-_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef = TypedDict(
-    "_OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef(
-    _RequiredSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
-    _OptionalSelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
-):
-    pass
-
 DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef = TypedDict(
     "DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef",
     {
         "ConfigRuleNames": Sequence[str],
         "Filters": DescribeConfigRulesFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeConfigRulesRequestRequestTypeDef = TypedDict(
     "DescribeConfigRulesRequestRequestTypeDef",
     {
@@ -3021,42 +3020,42 @@
 )
 
 DescribeOrganizationConfigRuleStatusesResponseTypeDef = TypedDict(
     "DescribeOrganizationConfigRuleStatusesResponseTypeDef",
     {
         "OrganizationConfigRuleStatuses": List[OrganizationConfigRuleStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConformancePackStatusesResponseTypeDef = TypedDict(
     "DescribeOrganizationConformancePackStatusesResponseTypeDef",
     {
         "OrganizationConformancePackStatuses": List[OrganizationConformancePackStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePendingAggregationRequestsResponseTypeDef = TypedDict(
     "DescribePendingAggregationRequestsResponseTypeDef",
     {
         "PendingAggregationRequests": List[PendingAggregationRequestTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRemediationExceptionsResponseTypeDef = TypedDict(
     "DescribeRemediationExceptionsResponseTypeDef",
     {
         "RemediationExceptions": List[RemediationExceptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailedRemediationExceptionBatchTypeDef = TypedDict(
     "FailedRemediationExceptionBatchTypeDef",
     {
         "FailureMessage": str,
@@ -3066,23 +3065,23 @@
 )
 
 DescribeRetentionConfigurationsResponseTypeDef = TypedDict(
     "DescribeRetentionConfigurationsResponseTypeDef",
     {
         "RetentionConfigurations": List[RetentionConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRetentionConfigurationResponseTypeDef = TypedDict(
     "PutRetentionConfigurationResponseTypeDef",
     {
         "RetentionConfiguration": RetentionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EvaluationResultIdentifierTypeDef = TypedDict(
     "EvaluationResultIdentifierTypeDef",
     {
         "EvaluationResultQualifier": EvaluationResultQualifierTypeDef,
@@ -3112,15 +3111,15 @@
 ):
     pass
 
 PutEvaluationsResponseTypeDef = TypedDict(
     "PutEvaluationsResponseTypeDef",
     {
         "FailedEvaluations": List[EvaluationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecutionControlsTypeDef = TypedDict(
     "ExecutionControlsTypeDef",
     {
         "SsmControls": SsmControlsTypeDef,
@@ -3170,39 +3169,39 @@
 GetAggregateDiscoveredResourceCountsResponseTypeDef = TypedDict(
     "GetAggregateDiscoveredResourceCountsResponseTypeDef",
     {
         "TotalDiscoveredResources": int,
         "GroupByKey": str,
         "GroupedResourceCounts": List[GroupedResourceCountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiscoveredResourceCountsResponseTypeDef = TypedDict(
     "GetDiscoveredResourceCountsResponseTypeDef",
     {
         "totalDiscoveredResources": int,
         "resourceCounts": List[ResourceCountTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef = TypedDict(
     "_RequiredGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef",
     {
         "OrganizationConfigRuleName": str,
     },
 )
 _OptionalGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef = TypedDict(
     "_OptionalGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef",
     {
         "Filters": StatusDetailFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef(
     _RequiredGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef,
     _OptionalGetOrganizationConfigRuleDetailedStatusRequestGetOrganizationConfigRuleDetailedStatusPaginateTypeDef,
@@ -3232,29 +3231,29 @@
     pass
 
 GetOrganizationConfigRuleDetailedStatusResponseTypeDef = TypedDict(
     "GetOrganizationConfigRuleDetailedStatusResponseTypeDef",
     {
         "OrganizationConfigRuleDetailedStatus": List[MemberAccountStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef = TypedDict(
     "_RequiredGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef",
     {
         "OrganizationConformancePackName": str,
     },
 )
 _OptionalGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef = TypedDict(
     "_OptionalGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef",
     {
         "Filters": OrganizationResourceDetailedStatusFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef(
     _RequiredGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef,
     _OptionalGetOrganizationConformancePackDetailedStatusRequestGetOrganizationConformancePackDetailedStatusPaginateTypeDef,
@@ -3286,29 +3285,29 @@
 GetOrganizationConformancePackDetailedStatusResponseTypeDef = TypedDict(
     "GetOrganizationConformancePackDetailedStatusResponseTypeDef",
     {
         "OrganizationConformancePackDetailedStatuses": List[
             OrganizationConformancePackDetailedStatusTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceEvaluationSummaryResponseTypeDef = TypedDict(
     "GetResourceEvaluationSummaryResponseTypeDef",
     {
         "ResourceEvaluationId": str,
         "EvaluationMode": EvaluationModeType,
         "EvaluationStatus": EvaluationStatusTypeDef,
         "EvaluationStartTimestamp": datetime,
         "Compliance": ComplianceTypeType,
         "EvaluationContext": EvaluationContextTypeDef,
         "ResourceDetails": ResourceDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartResourceEvaluationRequestRequestTypeDef = TypedDict(
     "_RequiredStartResourceEvaluationRequestRequestTypeDef",
     {
         "ResourceDetails": ResourceDetailsTypeDef,
@@ -3331,30 +3330,30 @@
 ):
     pass
 
 GetStoredQueryResponseTypeDef = TypedDict(
     "GetStoredQueryResponseTypeDef",
     {
         "StoredQuery": StoredQueryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef = TypedDict(
     "_RequiredListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef",
     {
         "ConfigurationAggregatorName": str,
         "ResourceType": ResourceTypeType,
     },
 )
 _OptionalListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef = TypedDict(
     "_OptionalListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef",
     {
         "Filters": ResourceFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef(
     _RequiredListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef,
     _OptionalListAggregateDiscoveredResourcesRequestListAggregateDiscoveredResourcesPaginateTypeDef,
@@ -3385,42 +3384,42 @@
     pass
 
 ListDiscoveredResourcesResponseTypeDef = TypedDict(
     "ListDiscoveredResourcesResponseTypeDef",
     {
         "resourceIdentifiers": List[ResourceIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResourceEvaluationsResponseTypeDef = TypedDict(
     "ListResourceEvaluationsResponseTypeDef",
     {
         "ResourceEvaluations": List[ResourceEvaluationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStoredQueriesResponseTypeDef = TypedDict(
     "ListStoredQueriesResponseTypeDef",
     {
         "StoredQueryMetadata": List[StoredQueryMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutAggregationAuthorizationRequestRequestTypeDef = TypedDict(
     "_RequiredPutAggregationAuthorizationRequestRequestTypeDef",
     {
         "AuthorizedAccountId": str,
@@ -3533,14 +3532,26 @@
 
 class PutOrganizationConfigRuleRequestRequestTypeDef(
     _RequiredPutOrganizationConfigRuleRequestRequestTypeDef,
     _OptionalPutOrganizationConfigRuleRequestRequestTypeDef,
 ):
     pass
 
+RecordingGroupTypeDef = TypedDict(
+    "RecordingGroupTypeDef",
+    {
+        "allSupported": bool,
+        "includeGlobalResourceTypes": bool,
+        "resourceTypes": List[ResourceTypeType],
+        "exclusionByResourceTypes": ExclusionByResourceTypesTypeDef,
+        "recordingStrategy": RecordingStrategyTypeDef,
+    },
+    total=False,
+)
+
 RemediationExecutionStatusTypeDef = TypedDict(
     "RemediationExecutionStatusTypeDef",
     {
         "ResourceKey": ResourceKeyTypeDef,
         "State": RemediationExecutionStateType,
         "StepDetails": List[RemediationExecutionStepTypeDef],
         "InvocationTime": datetime,
@@ -3588,27 +3599,27 @@
     pass
 
 DescribeAggregateComplianceByConformancePacksResponseTypeDef = TypedDict(
     "DescribeAggregateComplianceByConformancePacksResponseTypeDef",
     {
         "AggregateComplianceByConformancePacks": List[AggregateComplianceByConformancePackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAggregateConformancePackComplianceSummaryResponseTypeDef = TypedDict(
     "GetAggregateConformancePackComplianceSummaryResponseTypeDef",
     {
         "AggregateConformancePackComplianceSummaries": List[
             AggregateConformancePackComplianceSummaryTypeDef
         ],
         "GroupByKey": str,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AggregateComplianceCountTypeDef = TypedDict(
     "AggregateComplianceCountTypeDef",
     {
         "GroupName": str,
@@ -3626,15 +3637,15 @@
     total=False,
 )
 
 GetComplianceSummaryByConfigRuleResponseTypeDef = TypedDict(
     "GetComplianceSummaryByConfigRuleResponseTypeDef",
     {
         "ComplianceSummary": ComplianceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AggregateComplianceByConfigRuleTypeDef = TypedDict(
     "AggregateComplianceByConfigRuleTypeDef",
     {
         "ConfigRuleName": str,
@@ -3664,113 +3675,98 @@
     total=False,
 )
 
 DescribeDeliveryChannelsResponseTypeDef = TypedDict(
     "DescribeDeliveryChannelsResponseTypeDef",
     {
         "DeliveryChannels": List[DeliveryChannelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutDeliveryChannelRequestRequestTypeDef = TypedDict(
     "PutDeliveryChannelRequestRequestTypeDef",
     {
         "DeliveryChannel": DeliveryChannelTypeDef,
     },
 )
 
 DescribeDeliveryChannelStatusResponseTypeDef = TypedDict(
     "DescribeDeliveryChannelStatusResponseTypeDef",
     {
         "DeliveryChannelsStatus": List[DeliveryChannelStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConfigurationAggregatorsResponseTypeDef = TypedDict(
     "DescribeConfigurationAggregatorsResponseTypeDef",
     {
         "ConfigurationAggregators": List[ConfigurationAggregatorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutConfigurationAggregatorResponseTypeDef = TypedDict(
     "PutConfigurationAggregatorResponseTypeDef",
     {
         "ConfigurationAggregator": ConfigurationAggregatorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAggregateResourceConfigResponseTypeDef = TypedDict(
     "GetAggregateResourceConfigResponseTypeDef",
     {
         "ConfigurationItem": ConfigurationItemTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResourceConfigHistoryResponseTypeDef = TypedDict(
     "GetResourceConfigHistoryResponseTypeDef",
     {
         "configurationItems": List[ConfigurationItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeConfigurationRecordersResponseTypeDef = TypedDict(
-    "DescribeConfigurationRecordersResponseTypeDef",
-    {
-        "ConfigurationRecorders": List[ConfigurationRecorderTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutConfigurationRecorderRequestRequestTypeDef = TypedDict(
-    "PutConfigurationRecorderRequestRequestTypeDef",
-    {
-        "ConfigurationRecorder": ConfigurationRecorderTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConformancePacksResponseTypeDef = TypedDict(
     "DescribeOrganizationConformancePacksResponseTypeDef",
     {
         "OrganizationConformancePacks": List[OrganizationConformancePackTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeConformancePacksResponseTypeDef = TypedDict(
     "DescribeConformancePacksResponseTypeDef",
     {
         "ConformancePackDetails": List[ConformancePackDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRemediationExceptionsResponseTypeDef = TypedDict(
     "DeleteRemediationExceptionsResponseTypeDef",
     {
         "FailedBatches": List[FailedDeleteRemediationExceptionsBatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRemediationExceptionsResponseTypeDef = TypedDict(
     "PutRemediationExceptionsResponseTypeDef",
     {
         "FailedBatches": List[FailedRemediationExceptionBatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AggregateEvaluationResultTypeDef = TypedDict(
     "AggregateEvaluationResultTypeDef",
     {
         "EvaluationResultIdentifier": EvaluationResultIdentifierTypeDef,
@@ -3821,43 +3817,53 @@
 
 SelectAggregateResourceConfigResponseTypeDef = TypedDict(
     "SelectAggregateResourceConfigResponseTypeDef",
     {
         "Results": List[str],
         "QueryInfo": QueryInfoTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectResourceConfigResponseTypeDef = TypedDict(
     "SelectResourceConfigResponseTypeDef",
     {
         "Results": List[str],
         "QueryInfo": QueryInfoTypeDef,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOrganizationConfigRulesResponseTypeDef = TypedDict(
     "DescribeOrganizationConfigRulesResponseTypeDef",
     {
         "OrganizationConfigRules": List[OrganizationConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ConfigurationRecorderTypeDef = TypedDict(
+    "ConfigurationRecorderTypeDef",
+    {
+        "name": str,
+        "roleARN": str,
+        "recordingGroup": RecordingGroupTypeDef,
+    },
+    total=False,
+)
+
 DescribeRemediationExecutionStatusResponseTypeDef = TypedDict(
     "DescribeRemediationExecutionStatusResponseTypeDef",
     {
         "RemediationExecutionStatuses": List[RemediationExecutionStatusTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRemediationConfigurationTypeDef = TypedDict(
     "_RequiredRemediationConfigurationTypeDef",
     {
         "ConfigRuleName": str,
@@ -3886,15 +3892,15 @@
 ):
     pass
 
 ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef = TypedDict(
     "ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef",
     {
         "Filters": ResourceEvaluationFiltersTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListResourceEvaluationsRequestRequestTypeDef = TypedDict(
     "ListResourceEvaluationsRequestRequestTypeDef",
     {
@@ -3933,95 +3939,110 @@
 
 GetAggregateConfigRuleComplianceSummaryResponseTypeDef = TypedDict(
     "GetAggregateConfigRuleComplianceSummaryResponseTypeDef",
     {
         "GroupByKey": str,
         "AggregateComplianceCounts": List[AggregateComplianceCountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceSummaryByResourceTypeResponseTypeDef = TypedDict(
     "GetComplianceSummaryByResourceTypeResponseTypeDef",
     {
         "ComplianceSummariesByResourceType": List[ComplianceSummaryByResourceTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAggregateComplianceByConfigRulesResponseTypeDef = TypedDict(
     "DescribeAggregateComplianceByConfigRulesResponseTypeDef",
     {
         "AggregateComplianceByConfigRules": List[AggregateComplianceByConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComplianceByConfigRuleResponseTypeDef = TypedDict(
     "DescribeComplianceByConfigRuleResponseTypeDef",
     {
         "ComplianceByConfigRules": List[ComplianceByConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComplianceByResourceResponseTypeDef = TypedDict(
     "DescribeComplianceByResourceResponseTypeDef",
     {
         "ComplianceByResources": List[ComplianceByResourceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAggregateComplianceDetailsByConfigRuleResponseTypeDef = TypedDict(
     "GetAggregateComplianceDetailsByConfigRuleResponseTypeDef",
     {
         "AggregateEvaluationResults": List[AggregateEvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConformancePackComplianceDetailsResponseTypeDef = TypedDict(
     "GetConformancePackComplianceDetailsResponseTypeDef",
     {
         "ConformancePackName": str,
         "ConformancePackRuleEvaluationResults": List[ConformancePackEvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceDetailsByConfigRuleResponseTypeDef = TypedDict(
     "GetComplianceDetailsByConfigRuleResponseTypeDef",
     {
         "EvaluationResults": List[EvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetComplianceDetailsByResourceResponseTypeDef = TypedDict(
     "GetComplianceDetailsByResourceResponseTypeDef",
     {
         "EvaluationResults": List[EvaluationResultTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeConfigurationRecordersResponseTypeDef = TypedDict(
+    "DescribeConfigurationRecordersResponseTypeDef",
+    {
+        "ConfigurationRecorders": List[ConfigurationRecorderTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutConfigurationRecorderRequestRequestTypeDef = TypedDict(
+    "PutConfigurationRecorderRequestRequestTypeDef",
+    {
+        "ConfigurationRecorder": ConfigurationRecorderTypeDef,
     },
 )
 
 DescribeRemediationConfigurationsResponseTypeDef = TypedDict(
     "DescribeRemediationConfigurationsResponseTypeDef",
     {
         "RemediationConfigurations": List[RemediationConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FailedRemediationBatchTypeDef = TypedDict(
     "FailedRemediationBatchTypeDef",
     {
         "FailureMessage": str,
@@ -4038,15 +4059,15 @@
 )
 
 DescribeConfigRulesResponseTypeDef = TypedDict(
     "DescribeConfigRulesResponseTypeDef",
     {
         "ConfigRules": List[ConfigRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutConfigRuleRequestRequestTypeDef = TypedDict(
     "_RequiredPutConfigRuleRequestRequestTypeDef",
     {
         "ConfigRule": ConfigRuleTypeDef,
@@ -4065,10 +4086,10 @@
 ):
     pass
 
 PutRemediationConfigurationsResponseTypeDef = TypedDict(
     "PutRemediationConfigurationsResponseTypeDef",
     {
         "FailedBatches": List[FailedRemediationBatchTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/PKG-INFO` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-config
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ConfigService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ConfigService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-config"></a>
 
 # types-aiobotocore-config
 
 [![PyPI - types-aiobotocore-config](https://img.shields.io/pypi/v/types-aiobotocore-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-config)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-config.svg?color=blue)](https://pypi.org/project/types-aiobotocore-config)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-config?color=blue)](https://pypistats.org/packages/types-aiobotocore-config)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ConfigService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService)
+[aiobotocore.ConfigService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/config.html#ConfigService)
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
 [types-aiobotocore-config docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_config/).
 
 See how it helps to find and fix potential bugs:
 
@@ -468,14 +468,15 @@
     OrganizationConfigRuleTriggerTypeNoSNType,
     OrganizationConfigRuleTriggerTypeType,
     OrganizationResourceDetailedStatusType,
     OrganizationResourceStatusType,
     OrganizationRuleStatusType,
     OwnerType,
     RecorderStatusType,
+    RecordingStrategyTypeType,
     RemediationExecutionStateType,
     RemediationExecutionStepStateType,
     RemediationTargetTypeType,
     ResourceConfigurationSchemaTypeType,
     ResourceCountGroupKeyType,
     ResourceEvaluationStatusType,
     ResourceTypeType,
@@ -510,29 +511,27 @@
     AggregateConformancePackComplianceCountTypeDef,
     AggregateConformancePackComplianceFiltersTypeDef,
     AggregateConformancePackComplianceSummaryFiltersTypeDef,
     AggregateResourceIdentifierTypeDef,
     AggregatedSourceStatusTypeDef,
     AggregationAuthorizationTypeDef,
     BaseConfigurationItemTypeDef,
-    ResponseMetadataTypeDef,
     ResourceKeyTypeDef,
     ComplianceContributorCountTypeDef,
     ConfigExportDeliveryInfoTypeDef,
     ConfigRuleComplianceFiltersTypeDef,
     ConfigRuleComplianceSummaryFiltersTypeDef,
     ConfigRuleEvaluationStatusTypeDef,
     EvaluationModeConfigurationTypeDef,
     ScopeTypeDef,
     ConfigSnapshotDeliveryPropertiesTypeDef,
     ConfigStreamDeliveryInfoTypeDef,
     OrganizationAggregationSourceTypeDef,
     RelationshipTypeDef,
     ConfigurationRecorderStatusTypeDef,
-    RecordingGroupTypeDef,
     ConformancePackComplianceFiltersTypeDef,
     ConformancePackComplianceScoreTypeDef,
     ConformancePackComplianceScoresFiltersTypeDef,
     ConformancePackComplianceSummaryTypeDef,
     ConformancePackInputParameterTypeDef,
     TemplateSSMDocumentDetailsTypeDef,
     ConformancePackEvaluationFiltersTypeDef,
@@ -551,128 +550,156 @@
     DeletePendingAggregationRequestRequestRequestTypeDef,
     DeleteRemediationConfigurationRequestRequestTypeDef,
     RemediationExceptionResourceKeyTypeDef,
     DeleteResourceConfigRequestRequestTypeDef,
     DeleteRetentionConfigurationRequestRequestTypeDef,
     DeleteStoredQueryRequestRequestTypeDef,
     DeliverConfigSnapshotRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DeliverConfigSnapshotResponseTypeDef,
+    DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef,
     DescribeAggregationAuthorizationsRequestRequestTypeDef,
+    DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef,
     DescribeComplianceByConfigRuleRequestRequestTypeDef,
+    DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef,
     DescribeComplianceByResourceRequestRequestTypeDef,
+    DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef,
     DescribeConfigRuleEvaluationStatusRequestRequestTypeDef,
     DescribeConfigRulesFiltersTypeDef,
+    DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
     DescribeConfigurationAggregatorSourcesStatusRequestRequestTypeDef,
+    DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef,
     DescribeConfigurationAggregatorsRequestRequestTypeDef,
     DescribeConfigurationRecorderStatusRequestRequestTypeDef,
     DescribeConfigurationRecordersRequestRequestTypeDef,
+    DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef,
     DescribeConformancePackStatusRequestRequestTypeDef,
+    DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef,
     DescribeConformancePacksRequestRequestTypeDef,
     DescribeDeliveryChannelStatusRequestRequestTypeDef,
     DescribeDeliveryChannelsRequestRequestTypeDef,
+    DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef,
     DescribeOrganizationConfigRuleStatusesRequestRequestTypeDef,
     OrganizationConfigRuleStatusTypeDef,
+    DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef,
     DescribeOrganizationConfigRulesRequestRequestTypeDef,
+    DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef,
     DescribeOrganizationConformancePackStatusesRequestRequestTypeDef,
     OrganizationConformancePackStatusTypeDef,
+    DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef,
     DescribeOrganizationConformancePacksRequestRequestTypeDef,
+    DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef,
     DescribePendingAggregationRequestsRequestRequestTypeDef,
     PendingAggregationRequestTypeDef,
     DescribeRemediationConfigurationsRequestRequestTypeDef,
     RemediationExceptionTypeDef,
+    DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef,
     DescribeRetentionConfigurationsRequestRequestTypeDef,
     RetentionConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EvaluationContextTypeDef,
     EvaluationResultQualifierTypeDef,
     EvaluationStatusTypeDef,
     EvaluationTypeDef,
+    ExclusionByResourceTypesTypeDef,
     SsmControlsTypeDef,
     ExternalEvaluationTypeDef,
     FieldInfoTypeDef,
+    GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
     GetAggregateComplianceDetailsByConfigRuleRequestRequestTypeDef,
     ResourceCountFiltersTypeDef,
     GroupedResourceCountTypeDef,
+    GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
     GetComplianceDetailsByConfigRuleRequestRequestTypeDef,
+    GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef,
     GetComplianceDetailsByResourceRequestRequestTypeDef,
     GetComplianceSummaryByResourceTypeRequestRequestTypeDef,
+    GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
     GetConformancePackComplianceSummaryRequestRequestTypeDef,
     GetCustomRulePolicyRequestRequestTypeDef,
+    GetCustomRulePolicyResponseTypeDef,
     GetDiscoveredResourceCountsRequestRequestTypeDef,
     ResourceCountTypeDef,
     StatusDetailFiltersTypeDef,
     MemberAccountStatusTypeDef,
     OrganizationResourceDetailedStatusFiltersTypeDef,
     OrganizationConformancePackDetailedStatusTypeDef,
     GetOrganizationCustomRulePolicyRequestRequestTypeDef,
+    GetOrganizationCustomRulePolicyResponseTypeDef,
+    GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
     GetResourceConfigHistoryRequestRequestTypeDef,
     GetResourceEvaluationSummaryRequestRequestTypeDef,
     ResourceDetailsTypeDef,
     GetStoredQueryRequestRequestTypeDef,
     StoredQueryTypeDef,
     ResourceFiltersTypeDef,
+    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
     ListDiscoveredResourcesRequestRequestTypeDef,
     ResourceIdentifierTypeDef,
     ResourceEvaluationTypeDef,
     ListStoredQueriesRequestRequestTypeDef,
     StoredQueryMetadataTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     OrganizationCustomPolicyRuleMetadataNoPolicyTypeDef,
     OrganizationCustomRuleMetadataTypeDef,
     OrganizationManagedRuleMetadataTypeDef,
     OrganizationCustomPolicyRuleMetadataTypeDef,
+    PaginatorConfigTypeDef,
+    PutConformancePackResponseTypeDef,
+    PutOrganizationConfigRuleResponseTypeDef,
+    PutOrganizationConformancePackResponseTypeDef,
     PutResourceConfigRequestRequestTypeDef,
     PutRetentionConfigurationRequestRequestTypeDef,
+    PutStoredQueryResponseTypeDef,
+    RecordingStrategyTypeDef,
     RemediationExecutionStepTypeDef,
     ResourceValueTypeDef,
     StaticValueTypeDef,
     TimeWindowTypeDef,
+    ResponseMetadataTypeDef,
     SelectAggregateResourceConfigRequestRequestTypeDef,
+    SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
     SelectResourceConfigRequestRequestTypeDef,
+    SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
     SourceDetailTypeDef,
     StartConfigRulesEvaluationRequestRequestTypeDef,
     StartConfigurationRecorderRequestRequestTypeDef,
+    StartResourceEvaluationResponseTypeDef,
     StopConfigurationRecorderRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     AggregateComplianceByConformancePackTypeDef,
     AggregateConformancePackComplianceSummaryTypeDef,
+    DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
     DescribeAggregateComplianceByConformancePacksRequestRequestTypeDef,
     GetAggregateConformancePackComplianceSummaryRequestRequestTypeDef,
     BatchGetAggregateResourceConfigRequestRequestTypeDef,
     GetAggregateResourceConfigRequestRequestTypeDef,
-    BatchGetAggregateResourceConfigResponseTypeDef,
-    DeliverConfigSnapshotResponseTypeDef,
-    DescribeAggregationAuthorizationsResponseTypeDef,
-    DescribeConfigurationAggregatorSourcesStatusResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCustomRulePolicyResponseTypeDef,
-    GetOrganizationCustomRulePolicyResponseTypeDef,
     ListAggregateDiscoveredResourcesResponseTypeDef,
+    DescribeConfigurationAggregatorSourcesStatusResponseTypeDef,
+    DescribeAggregationAuthorizationsResponseTypeDef,
     PutAggregationAuthorizationResponseTypeDef,
-    PutConformancePackResponseTypeDef,
-    PutOrganizationConfigRuleResponseTypeDef,
-    PutOrganizationConformancePackResponseTypeDef,
-    PutStoredQueryResponseTypeDef,
-    StartResourceEvaluationResponseTypeDef,
+    BatchGetAggregateResourceConfigResponseTypeDef,
     BatchGetResourceConfigRequestRequestTypeDef,
     BatchGetResourceConfigResponseTypeDef,
+    DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
     DescribeRemediationExecutionStatusRequestRequestTypeDef,
     StartRemediationExecutionRequestRequestTypeDef,
     StartRemediationExecutionResponseTypeDef,
     ComplianceSummaryTypeDef,
     ComplianceTypeDef,
+    DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
     DescribeAggregateComplianceByConfigRulesRequestRequestTypeDef,
     GetAggregateConfigRuleComplianceSummaryRequestRequestTypeDef,
     DescribeConfigRuleEvaluationStatusResponseTypeDef,
     DeliveryChannelTypeDef,
     DeliveryChannelStatusTypeDef,
     ConfigurationAggregatorTypeDef,
     ConfigurationItemTypeDef,
     DescribeConfigurationRecorderStatusResponseTypeDef,
-    ConfigurationRecorderTypeDef,
     DescribeConformancePackComplianceRequestRequestTypeDef,
     ListConformancePackComplianceScoresResponseTypeDef,
     ListConformancePackComplianceScoresRequestRequestTypeDef,
     GetConformancePackComplianceSummaryResponseTypeDef,
     OrganizationConformancePackTypeDef,
     PutOrganizationConformancePackRequestRequestTypeDef,
     ConformancePackDetailTypeDef,
@@ -680,40 +707,14 @@
     GetConformancePackComplianceDetailsRequestRequestTypeDef,
     DescribeConformancePackComplianceResponseTypeDef,
     DescribeConformancePackStatusResponseTypeDef,
     DeleteRemediationExceptionsRequestRequestTypeDef,
     DescribeRemediationExceptionsRequestRequestTypeDef,
     FailedDeleteRemediationExceptionsBatchTypeDef,
     PutRemediationExceptionsRequestRequestTypeDef,
-    DescribeAggregateComplianceByConfigRulesRequestDescribeAggregateComplianceByConfigRulesPaginateTypeDef,
-    DescribeAggregateComplianceByConformancePacksRequestDescribeAggregateComplianceByConformancePacksPaginateTypeDef,
-    DescribeAggregationAuthorizationsRequestDescribeAggregationAuthorizationsPaginateTypeDef,
-    DescribeComplianceByConfigRuleRequestDescribeComplianceByConfigRulePaginateTypeDef,
-    DescribeComplianceByResourceRequestDescribeComplianceByResourcePaginateTypeDef,
-    DescribeConfigRuleEvaluationStatusRequestDescribeConfigRuleEvaluationStatusPaginateTypeDef,
-    DescribeConfigurationAggregatorSourcesStatusRequestDescribeConfigurationAggregatorSourcesStatusPaginateTypeDef,
-    DescribeConfigurationAggregatorsRequestDescribeConfigurationAggregatorsPaginateTypeDef,
-    DescribeConformancePackStatusRequestDescribeConformancePackStatusPaginateTypeDef,
-    DescribeConformancePacksRequestDescribeConformancePacksPaginateTypeDef,
-    DescribeOrganizationConfigRuleStatusesRequestDescribeOrganizationConfigRuleStatusesPaginateTypeDef,
-    DescribeOrganizationConfigRulesRequestDescribeOrganizationConfigRulesPaginateTypeDef,
-    DescribeOrganizationConformancePackStatusesRequestDescribeOrganizationConformancePackStatusesPaginateTypeDef,
-    DescribeOrganizationConformancePacksRequestDescribeOrganizationConformancePacksPaginateTypeDef,
-    DescribePendingAggregationRequestsRequestDescribePendingAggregationRequestsPaginateTypeDef,
-    DescribeRemediationExecutionStatusRequestDescribeRemediationExecutionStatusPaginateTypeDef,
-    DescribeRetentionConfigurationsRequestDescribeRetentionConfigurationsPaginateTypeDef,
-    GetAggregateComplianceDetailsByConfigRuleRequestGetAggregateComplianceDetailsByConfigRulePaginateTypeDef,
-    GetComplianceDetailsByConfigRuleRequestGetComplianceDetailsByConfigRulePaginateTypeDef,
-    GetComplianceDetailsByResourceRequestGetComplianceDetailsByResourcePaginateTypeDef,
-    GetConformancePackComplianceSummaryRequestGetConformancePackComplianceSummaryPaginateTypeDef,
-    GetResourceConfigHistoryRequestGetResourceConfigHistoryPaginateTypeDef,
-    ListDiscoveredResourcesRequestListDiscoveredResourcesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    SelectAggregateResourceConfigRequestSelectAggregateResourceConfigPaginateTypeDef,
-    SelectResourceConfigRequestSelectResourceConfigPaginateTypeDef,
     DescribeConfigRulesRequestDescribeConfigRulesPaginateTypeDef,
     DescribeConfigRulesRequestRequestTypeDef,
     DescribeOrganizationConfigRuleStatusesResponseTypeDef,
     DescribeOrganizationConformancePackStatusesResponseTypeDef,
     DescribePendingAggregationRequestsResponseTypeDef,
     DescribeRemediationExceptionsResponseTypeDef,
     FailedRemediationExceptionBatchTypeDef,
@@ -745,14 +746,15 @@
     ListTagsForResourceResponseTypeDef,
     PutAggregationAuthorizationRequestRequestTypeDef,
     PutConfigurationAggregatorRequestRequestTypeDef,
     PutStoredQueryRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     OrganizationConfigRuleTypeDef,
     PutOrganizationConfigRuleRequestRequestTypeDef,
+    RecordingGroupTypeDef,
     RemediationExecutionStatusTypeDef,
     RemediationParameterValueTypeDef,
     ResourceEvaluationFiltersTypeDef,
     SourceTypeDef,
     DescribeAggregateComplianceByConformancePacksResponseTypeDef,
     GetAggregateConformancePackComplianceSummaryResponseTypeDef,
     AggregateComplianceCountTypeDef,
@@ -764,40 +766,41 @@
     DescribeDeliveryChannelsResponseTypeDef,
     PutDeliveryChannelRequestRequestTypeDef,
     DescribeDeliveryChannelStatusResponseTypeDef,
     DescribeConfigurationAggregatorsResponseTypeDef,
     PutConfigurationAggregatorResponseTypeDef,
     GetAggregateResourceConfigResponseTypeDef,
     GetResourceConfigHistoryResponseTypeDef,
-    DescribeConfigurationRecordersResponseTypeDef,
-    PutConfigurationRecorderRequestRequestTypeDef,
     DescribeOrganizationConformancePacksResponseTypeDef,
     DescribeConformancePacksResponseTypeDef,
     DeleteRemediationExceptionsResponseTypeDef,
     PutRemediationExceptionsResponseTypeDef,
     AggregateEvaluationResultTypeDef,
     ConformancePackEvaluationResultTypeDef,
     EvaluationResultTypeDef,
     SelectAggregateResourceConfigResponseTypeDef,
     SelectResourceConfigResponseTypeDef,
     DescribeOrganizationConfigRulesResponseTypeDef,
+    ConfigurationRecorderTypeDef,
     DescribeRemediationExecutionStatusResponseTypeDef,
     RemediationConfigurationTypeDef,
     ListResourceEvaluationsRequestListResourceEvaluationsPaginateTypeDef,
     ListResourceEvaluationsRequestRequestTypeDef,
     ConfigRuleTypeDef,
     GetAggregateConfigRuleComplianceSummaryResponseTypeDef,
     GetComplianceSummaryByResourceTypeResponseTypeDef,
     DescribeAggregateComplianceByConfigRulesResponseTypeDef,
     DescribeComplianceByConfigRuleResponseTypeDef,
     DescribeComplianceByResourceResponseTypeDef,
     GetAggregateComplianceDetailsByConfigRuleResponseTypeDef,
     GetConformancePackComplianceDetailsResponseTypeDef,
     GetComplianceDetailsByConfigRuleResponseTypeDef,
     GetComplianceDetailsByResourceResponseTypeDef,
+    DescribeConfigurationRecordersResponseTypeDef,
+    PutConfigurationRecorderRequestRequestTypeDef,
     DescribeRemediationConfigurationsResponseTypeDef,
     FailedRemediationBatchTypeDef,
     PutRemediationConfigurationsRequestRequestTypeDef,
     DescribeConfigRulesResponseTypeDef,
     PutConfigRuleRequestRequestTypeDef,
     PutRemediationConfigurationsResponseTypeDef,
 )
@@ -810,43 +813,43 @@
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

### Comparing `types-aiobotocore-config-2.5.0.post1/types_aiobotocore_config.egg-info/SOURCES.txt` & `types-aiobotocore-config-2.5.1/types_aiobotocore_config.egg-info/SOURCES.txt`

 * *Files identical despite different names*

