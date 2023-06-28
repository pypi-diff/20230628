# Comparing `tmp/types-aiobotocore-kendra-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kendra-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kendra-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:49 2023, max compression
+gzip compressed data, was "types-aiobotocore-kendra-2.5.1.tar", last modified: Wed Jun 28 01:43:40 2023, max compression
```

## Comparing `types-aiobotocore-kendra-2.5.0.post1.tar` & `types-aiobotocore-kendra-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.315323 types-aiobotocore-kendra-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22796 2023-03-11 12:26:49.315323 types-aiobotocore-kendra-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    21229 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:49.315323 types-aiobotocore-kendra-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.315323 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/
--rw-r--r--   0 runner    (1001) docker     (123)      434 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      433 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    45501 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    45433 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14839 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14837 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   100742 2023-03-11 12:16:52.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   100597 2023-03-11 12:16:49.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:48.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.315323 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22796 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      717 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:49.000000 types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.778158 types-aiobotocore-kendra-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    23909 2023-06-28 01:43:40.774158 types-aiobotocore-kendra-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    22348 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:40.778158 types-aiobotocore-kendra-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.770158 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/
+-rw-r--r--   0 runner    (1001) docker     (123)      434 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      433 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    50591 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    50517 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15346 2023-06-28 01:33:29.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15344 2023-06-28 01:33:29.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   110885 2023-06-28 01:33:31.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   110732 2023-06-28 01:33:30.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:28.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.774158 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23909 2023-06-28 01:43:40.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      717 2023-06-28 01:43:40.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:40.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:40.000000 types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kendra-2.5.0.post1/LICENSE` & `types-aiobotocore-kendra-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kendra-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kendra-2.5.1/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-kendra
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.kendra 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore kendra type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-kendra"></a>
 
 # types-aiobotocore-kendra
 
 [![PyPI - types-aiobotocore-kendra](https://img.shields.io/pypi/v/types-aiobotocore-kendra.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kendra.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kendra?color=blue)](https://pypistats.org/packages/types-aiobotocore-kendra)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.kendra 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra)
+[aiobotocore.kendra 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra)
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
 [types-aiobotocore-kendra docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/).
 
 See how it helps to find and fix potential bugs:
 
@@ -270,14 +237,15 @@
 `types_aiobotocore_kendra.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_kendra.literals import (
     AdditionalResultAttributeValueTypeType,
     AlfrescoEntityType,
+    AttributeSuggestionsModeType,
     ConditionOperatorType,
     ConfluenceAttachmentFieldNameType,
     ConfluenceAuthenticationTypeType,
     ConfluenceBlogFieldNameType,
     ConfluencePageFieldNameType,
     ConfluenceSpaceFieldNameType,
     ConfluenceVersionType,
@@ -290,14 +258,15 @@
     DocumentStatusType,
     EndpointTypeType,
     EntityTypeType,
     ErrorCodeType,
     ExperienceStatusType,
     FaqFileFormatType,
     FaqStatusType,
+    FeaturedResultsSetStatusType,
     FsxFileSystemTypeType,
     HighlightTypeType,
     IndexEditionType,
     IndexStatusType,
     IntervalType,
     IssueSubEntityType,
     KeyLocationType,
@@ -320,14 +289,15 @@
     ScoreConfidenceType,
     ServiceNowAuthenticationTypeType,
     ServiceNowBuildVersionTypeType,
     SharePointOnlineAuthenticationTypeType,
     SharePointVersionType,
     SlackEntityType,
     SortOrderType,
+    SuggestionTypeType,
     ThesaurusStatusType,
     TypeType,
     UserContextPolicyType,
     UserGroupResolutionModeType,
     WarningCodeType,
     WebCrawlerModeType,
     kendraServiceName,
@@ -354,19 +324,21 @@
     AccessControlListConfigurationTypeDef,
     AclConfigurationTypeDef,
     DataSourceToIndexFieldMappingTypeDef,
     DataSourceVpcConfigurationTypeDef,
     S3PathTypeDef,
     EntityConfigurationTypeDef,
     FailedEntityTypeDef,
-    ResponseMetadataTypeDef,
     EntityPersonaConfigurationTypeDef,
+    SuggestableConfigTypeDef,
     BasicAuthenticationConfigurationTypeDef,
     DataSourceSyncJobMetricTargetTypeDef,
     BatchDeleteDocumentResponseFailedDocumentTypeDef,
+    BatchDeleteFeaturedResultsSetErrorTypeDef,
+    BatchDeleteFeaturedResultsSetRequestRequestTypeDef,
     BatchGetDocumentStatusResponseErrorTypeDef,
     StatusTypeDef,
     BatchPutDocumentResponseFailedDocumentTypeDef,
     CapacityUnitsConfigurationTypeDef,
     ClearQuerySuggestionsRequestRequestTypeDef,
     ClickFeedbackTypeDef,
     ConfluenceAttachmentToIndexFieldMappingTypeDef,
@@ -374,17 +346,25 @@
     ProxyConfigurationTypeDef,
     ConfluencePageToIndexFieldMappingTypeDef,
     ConfluenceSpaceToIndexFieldMappingTypeDef,
     ConnectionConfigurationTypeDef,
     ContentSourceConfigurationTypeDef,
     CorrectionTypeDef,
     PrincipalTypeDef,
+    CreateAccessControlConfigurationResponseTypeDef,
     TagTypeDef,
+    CreateDataSourceResponseTypeDef,
+    CreateExperienceResponseTypeDef,
+    CreateFaqResponseTypeDef,
+    FeaturedDocumentTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     UserGroupResolutionConfigurationTypeDef,
+    CreateIndexResponseTypeDef,
+    CreateQuerySuggestionsBlockListResponseTypeDef,
+    CreateThesaurusResponseTypeDef,
     TemplateConfigurationTypeDef,
     DataSourceGroupTypeDef,
     DataSourceSummaryTypeDef,
     DataSourceSyncJobMetricsTypeDef,
     SqlConfigurationTypeDef,
     DeleteAccessControlConfigurationRequestRequestTypeDef,
     DeleteDataSourceRequestRequestTypeDef,
@@ -395,32 +375,36 @@
     DeleteQuerySuggestionsBlockListRequestRequestTypeDef,
     DeleteThesaurusRequestRequestTypeDef,
     DescribeAccessControlConfigurationRequestRequestTypeDef,
     DescribeDataSourceRequestRequestTypeDef,
     DescribeExperienceRequestRequestTypeDef,
     ExperienceEndpointTypeDef,
     DescribeFaqRequestRequestTypeDef,
+    DescribeFeaturedResultsSetRequestRequestTypeDef,
+    FeaturedDocumentMissingTypeDef,
+    FeaturedDocumentWithMetadataTypeDef,
     DescribeIndexRequestRequestTypeDef,
     DescribePrincipalMappingRequestRequestTypeDef,
     GroupOrderingIdSummaryTypeDef,
     DescribeQuerySuggestionsBlockListRequestRequestTypeDef,
     DescribeQuerySuggestionsConfigRequestRequestTypeDef,
     DescribeThesaurusRequestRequestTypeDef,
     DisassociatePersonasFromEntitiesRequestRequestTypeDef,
     DocumentAttributeValueTypeDef,
     RelevanceTypeDef,
     SearchTypeDef,
     DocumentsMetadataConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EntityDisplayDataTypeDef,
     UserIdentityConfigurationTypeDef,
     FacetResultTypeDef,
     FacetTypeDef,
     FaqStatisticsTypeDef,
     FaqSummaryTypeDef,
-    GetQuerySuggestionsRequestRequestTypeDef,
+    FeaturedResultsSetSummaryTypeDef,
     GetSnapshotsRequestRequestTypeDef,
     TimeRangeTypeDef,
     GitHubDocumentCrawlPropertiesTypeDef,
     SaaSConfigurationTypeDef,
     MemberGroupTypeDef,
     MemberUserTypeDef,
     GroupSummaryTypeDef,
@@ -432,34 +416,37 @@
     ListAccessControlConfigurationsRequestRequestTypeDef,
     ListDataSourcesRequestRequestTypeDef,
     ListEntityPersonasRequestRequestTypeDef,
     PersonasSummaryTypeDef,
     ListExperienceEntitiesRequestRequestTypeDef,
     ListExperiencesRequestRequestTypeDef,
     ListFaqsRequestRequestTypeDef,
+    ListFeaturedResultsSetsRequestRequestTypeDef,
     ListGroupsOlderThanOrderingIdRequestRequestTypeDef,
     ListIndicesRequestRequestTypeDef,
     ListQuerySuggestionsBlockListsRequestRequestTypeDef,
     QuerySuggestionsBlockListSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListThesauriRequestRequestTypeDef,
     ThesaurusSummaryTypeDef,
     SortingConfigurationTypeDef,
     SpellCorrectionConfigurationTypeDef,
     ScoreAttributesTypeDef,
     WarningTypeDef,
     RelevanceFeedbackTypeDef,
+    ResponseMetadataTypeDef,
     SeedUrlConfigurationTypeDef,
     SiteMapsConfigurationTypeDef,
     StartDataSourceSyncJobRequestRequestTypeDef,
+    StartDataSourceSyncJobResponseTypeDef,
     StopDataSourceSyncJobRequestRequestTypeDef,
     SuggestionHighlightTypeDef,
     TableCellTypeDef,
     UntagResourceRequestRequestTypeDef,
-    UpdateQuerySuggestionsConfigRequestRequestTypeDef,
+    ListAccessControlConfigurationsResponseTypeDef,
     ColumnConfigurationTypeDef,
     GoogleDriveConfigurationTypeDef,
     SalesforceChatterFeedConfigurationTypeDef,
     SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef,
     SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef,
     SalesforceStandardObjectAttachmentConfigurationTypeDef,
     SalesforceStandardObjectConfigurationTypeDef,
@@ -468,71 +455,68 @@
     WorkDocsConfigurationTypeDef,
     BoxConfigurationTypeDef,
     FsxConfigurationTypeDef,
     JiraConfigurationTypeDef,
     QuipConfigurationTypeDef,
     SlackConfigurationTypeDef,
     AlfrescoConfigurationTypeDef,
+    DescribeFaqResponseTypeDef,
+    DescribeQuerySuggestionsBlockListResponseTypeDef,
+    DescribeThesaurusResponseTypeDef,
     OnPremiseConfigurationTypeDef,
     OneDriveUsersTypeDef,
     UpdateQuerySuggestionsBlockListRequestRequestTypeDef,
     UpdateThesaurusRequestRequestTypeDef,
     AssociateEntitiesToExperienceRequestRequestTypeDef,
     DisassociateEntitiesFromExperienceRequestRequestTypeDef,
     AssociateEntitiesToExperienceResponseTypeDef,
     AssociatePersonasToEntitiesResponseTypeDef,
-    CreateAccessControlConfigurationResponseTypeDef,
-    CreateDataSourceResponseTypeDef,
-    CreateExperienceResponseTypeDef,
-    CreateFaqResponseTypeDef,
-    CreateIndexResponseTypeDef,
-    CreateQuerySuggestionsBlockListResponseTypeDef,
-    CreateThesaurusResponseTypeDef,
-    DescribeFaqResponseTypeDef,
-    DescribeQuerySuggestionsBlockListResponseTypeDef,
-    DescribeQuerySuggestionsConfigResponseTypeDef,
-    DescribeThesaurusResponseTypeDef,
     DisassociateEntitiesFromExperienceResponseTypeDef,
     DisassociatePersonasFromEntitiesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAccessControlConfigurationsResponseTypeDef,
-    StartDataSourceSyncJobResponseTypeDef,
     AssociatePersonasToEntitiesRequestRequestTypeDef,
+    AttributeSuggestionsDescribeConfigTypeDef,
+    AttributeSuggestionsUpdateConfigTypeDef,
     AuthenticationConfigurationTypeDef,
     BatchDeleteDocumentRequestRequestTypeDef,
     BatchDeleteDocumentResponseTypeDef,
+    BatchDeleteFeaturedResultsSetResponseTypeDef,
     BatchGetDocumentStatusResponseTypeDef,
     BatchPutDocumentResponseTypeDef,
     ConfluenceAttachmentConfigurationTypeDef,
     ConfluenceBlogConfigurationTypeDef,
     SharePointConfigurationTypeDef,
     ConfluencePageConfigurationTypeDef,
     ConfluenceSpaceConfigurationTypeDef,
     SpellCorrectedQueryTypeDef,
     HierarchicalPrincipalTypeDef,
     CreateFaqRequestRequestTypeDef,
     CreateQuerySuggestionsBlockListRequestRequestTypeDef,
     CreateThesaurusRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateFeaturedResultsSetRequestRequestTypeDef,
+    FeaturedResultsSetTypeDef,
+    UpdateFeaturedResultsSetRequestRequestTypeDef,
     UserContextTypeDef,
     ListDataSourcesResponseTypeDef,
     DataSourceSyncJobTypeDef,
     ExperiencesSummaryTypeDef,
+    DescribeFeaturedResultsSetResponseTypeDef,
     DescribePrincipalMappingResponseTypeDef,
     DocumentAttributeConditionTypeDef,
     DocumentAttributeTargetTypeDef,
     DocumentAttributeTypeDef,
     DocumentAttributeValueCountPairTypeDef,
     DocumentRelevanceConfigurationTypeDef,
     DocumentMetadataConfigurationTypeDef,
     S3DataSourceConfigurationTypeDef,
     ExperienceEntitiesSummaryTypeDef,
     ExperienceConfigurationTypeDef,
     ListFaqsResponseTypeDef,
+    ListFeaturedResultsSetsResponseTypeDef,
     GetSnapshotsResponseTypeDef,
     ListDataSourceSyncJobsRequestRequestTypeDef,
     GroupMembersTypeDef,
     ListGroupsOlderThanOrderingIdResponseTypeDef,
     TextWithHighlightsTypeDef,
     ListIndicesResponseTypeDef,
     IndexStatisticsTypeDef,
@@ -545,45 +529,56 @@
     SuggestionTextWithHighlightsTypeDef,
     TableRowTypeDef,
     DatabaseConfigurationTypeDef,
     SalesforceKnowledgeArticleConfigurationTypeDef,
     ServiceNowConfigurationTypeDef,
     GitHubConfigurationTypeDef,
     OneDriveConfigurationTypeDef,
+    DescribeQuerySuggestionsConfigResponseTypeDef,
+    UpdateQuerySuggestionsConfigRequestRequestTypeDef,
     ConfluenceConfigurationTypeDef,
     CreateAccessControlConfigurationRequestRequestTypeDef,
     DescribeAccessControlConfigurationResponseTypeDef,
     UpdateAccessControlConfigurationRequestRequestTypeDef,
+    CreateFeaturedResultsSetResponseTypeDef,
+    UpdateFeaturedResultsSetResponseTypeDef,
+    AttributeSuggestionsGetConfigTypeDef,
     ListDataSourceSyncJobsResponseTypeDef,
     ListExperiencesResponseTypeDef,
     HookConfigurationTypeDef,
     InlineCustomDocumentEnrichmentConfigurationTypeDef,
     AttributeFilterTypeDef,
     DocumentInfoTypeDef,
     DocumentTypeDef,
+    RetrieveResultItemTypeDef,
+    SourceDocumentTypeDef,
     QueryRequestRequestTypeDef,
+    RetrieveRequestRequestTypeDef,
     ListExperienceEntitiesResponseTypeDef,
     CreateExperienceRequestRequestTypeDef,
     DescribeExperienceResponseTypeDef,
     UpdateExperienceRequestRequestTypeDef,
     PutPrincipalMappingRequestRequestTypeDef,
     AdditionalResultAttributeValueTypeDef,
     CreateIndexRequestRequestTypeDef,
     DescribeIndexResponseTypeDef,
     UpdateIndexRequestRequestTypeDef,
     WebCrawlerConfigurationTypeDef,
     SuggestionValueTypeDef,
     TableExcerptTypeDef,
     SalesforceConfigurationTypeDef,
+    GetQuerySuggestionsRequestRequestTypeDef,
     CustomDocumentEnrichmentConfigurationTypeDef,
     BatchGetDocumentStatusRequestRequestTypeDef,
+    RetrieveResultTypeDef,
     AdditionalResultAttributeTypeDef,
     SuggestionTypeDef,
     DataSourceConfigurationTypeDef,
     BatchPutDocumentRequestRequestTypeDef,
+    FeaturedResultsItemTypeDef,
     QueryResultItemTypeDef,
     GetQuerySuggestionsResponseTypeDef,
     CreateDataSourceRequestRequestTypeDef,
     DescribeDataSourceResponseTypeDef,
     UpdateDataSourceRequestRequestTypeDef,
     QueryResultTypeDef,
 )
@@ -596,43 +591,43 @@
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

### Comparing `types-aiobotocore-kendra-2.5.0.post1/README.md` & `types-aiobotocore-kendra-2.5.1/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-kendra
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.kendra 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore kendra type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-kendra"></a>
 
 # types-aiobotocore-kendra
 
 [![PyPI - types-aiobotocore-kendra](https://img.shields.io/pypi/v/types-aiobotocore-kendra.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kendra.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kendra?color=blue)](https://pypistats.org/packages/types-aiobotocore-kendra)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.kendra 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra)
+[aiobotocore.kendra 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra)
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
 [types-aiobotocore-kendra docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/).
 
 See how it helps to find and fix potential bugs:
 
@@ -237,14 +270,15 @@
 `types_aiobotocore_kendra.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_kendra.literals import (
     AdditionalResultAttributeValueTypeType,
     AlfrescoEntityType,
+    AttributeSuggestionsModeType,
     ConditionOperatorType,
     ConfluenceAttachmentFieldNameType,
     ConfluenceAuthenticationTypeType,
     ConfluenceBlogFieldNameType,
     ConfluencePageFieldNameType,
     ConfluenceSpaceFieldNameType,
     ConfluenceVersionType,
@@ -257,14 +291,15 @@
     DocumentStatusType,
     EndpointTypeType,
     EntityTypeType,
     ErrorCodeType,
     ExperienceStatusType,
     FaqFileFormatType,
     FaqStatusType,
+    FeaturedResultsSetStatusType,
     FsxFileSystemTypeType,
     HighlightTypeType,
     IndexEditionType,
     IndexStatusType,
     IntervalType,
     IssueSubEntityType,
     KeyLocationType,
@@ -287,14 +322,15 @@
     ScoreConfidenceType,
     ServiceNowAuthenticationTypeType,
     ServiceNowBuildVersionTypeType,
     SharePointOnlineAuthenticationTypeType,
     SharePointVersionType,
     SlackEntityType,
     SortOrderType,
+    SuggestionTypeType,
     ThesaurusStatusType,
     TypeType,
     UserContextPolicyType,
     UserGroupResolutionModeType,
     WarningCodeType,
     WebCrawlerModeType,
     kendraServiceName,
@@ -321,19 +357,21 @@
     AccessControlListConfigurationTypeDef,
     AclConfigurationTypeDef,
     DataSourceToIndexFieldMappingTypeDef,
     DataSourceVpcConfigurationTypeDef,
     S3PathTypeDef,
     EntityConfigurationTypeDef,
     FailedEntityTypeDef,
-    ResponseMetadataTypeDef,
     EntityPersonaConfigurationTypeDef,
+    SuggestableConfigTypeDef,
     BasicAuthenticationConfigurationTypeDef,
     DataSourceSyncJobMetricTargetTypeDef,
     BatchDeleteDocumentResponseFailedDocumentTypeDef,
+    BatchDeleteFeaturedResultsSetErrorTypeDef,
+    BatchDeleteFeaturedResultsSetRequestRequestTypeDef,
     BatchGetDocumentStatusResponseErrorTypeDef,
     StatusTypeDef,
     BatchPutDocumentResponseFailedDocumentTypeDef,
     CapacityUnitsConfigurationTypeDef,
     ClearQuerySuggestionsRequestRequestTypeDef,
     ClickFeedbackTypeDef,
     ConfluenceAttachmentToIndexFieldMappingTypeDef,
@@ -341,17 +379,25 @@
     ProxyConfigurationTypeDef,
     ConfluencePageToIndexFieldMappingTypeDef,
     ConfluenceSpaceToIndexFieldMappingTypeDef,
     ConnectionConfigurationTypeDef,
     ContentSourceConfigurationTypeDef,
     CorrectionTypeDef,
     PrincipalTypeDef,
+    CreateAccessControlConfigurationResponseTypeDef,
     TagTypeDef,
+    CreateDataSourceResponseTypeDef,
+    CreateExperienceResponseTypeDef,
+    CreateFaqResponseTypeDef,
+    FeaturedDocumentTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     UserGroupResolutionConfigurationTypeDef,
+    CreateIndexResponseTypeDef,
+    CreateQuerySuggestionsBlockListResponseTypeDef,
+    CreateThesaurusResponseTypeDef,
     TemplateConfigurationTypeDef,
     DataSourceGroupTypeDef,
     DataSourceSummaryTypeDef,
     DataSourceSyncJobMetricsTypeDef,
     SqlConfigurationTypeDef,
     DeleteAccessControlConfigurationRequestRequestTypeDef,
     DeleteDataSourceRequestRequestTypeDef,
@@ -362,32 +408,36 @@
     DeleteQuerySuggestionsBlockListRequestRequestTypeDef,
     DeleteThesaurusRequestRequestTypeDef,
     DescribeAccessControlConfigurationRequestRequestTypeDef,
     DescribeDataSourceRequestRequestTypeDef,
     DescribeExperienceRequestRequestTypeDef,
     ExperienceEndpointTypeDef,
     DescribeFaqRequestRequestTypeDef,
+    DescribeFeaturedResultsSetRequestRequestTypeDef,
+    FeaturedDocumentMissingTypeDef,
+    FeaturedDocumentWithMetadataTypeDef,
     DescribeIndexRequestRequestTypeDef,
     DescribePrincipalMappingRequestRequestTypeDef,
     GroupOrderingIdSummaryTypeDef,
     DescribeQuerySuggestionsBlockListRequestRequestTypeDef,
     DescribeQuerySuggestionsConfigRequestRequestTypeDef,
     DescribeThesaurusRequestRequestTypeDef,
     DisassociatePersonasFromEntitiesRequestRequestTypeDef,
     DocumentAttributeValueTypeDef,
     RelevanceTypeDef,
     SearchTypeDef,
     DocumentsMetadataConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EntityDisplayDataTypeDef,
     UserIdentityConfigurationTypeDef,
     FacetResultTypeDef,
     FacetTypeDef,
     FaqStatisticsTypeDef,
     FaqSummaryTypeDef,
-    GetQuerySuggestionsRequestRequestTypeDef,
+    FeaturedResultsSetSummaryTypeDef,
     GetSnapshotsRequestRequestTypeDef,
     TimeRangeTypeDef,
     GitHubDocumentCrawlPropertiesTypeDef,
     SaaSConfigurationTypeDef,
     MemberGroupTypeDef,
     MemberUserTypeDef,
     GroupSummaryTypeDef,
@@ -399,34 +449,37 @@
     ListAccessControlConfigurationsRequestRequestTypeDef,
     ListDataSourcesRequestRequestTypeDef,
     ListEntityPersonasRequestRequestTypeDef,
     PersonasSummaryTypeDef,
     ListExperienceEntitiesRequestRequestTypeDef,
     ListExperiencesRequestRequestTypeDef,
     ListFaqsRequestRequestTypeDef,
+    ListFeaturedResultsSetsRequestRequestTypeDef,
     ListGroupsOlderThanOrderingIdRequestRequestTypeDef,
     ListIndicesRequestRequestTypeDef,
     ListQuerySuggestionsBlockListsRequestRequestTypeDef,
     QuerySuggestionsBlockListSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListThesauriRequestRequestTypeDef,
     ThesaurusSummaryTypeDef,
     SortingConfigurationTypeDef,
     SpellCorrectionConfigurationTypeDef,
     ScoreAttributesTypeDef,
     WarningTypeDef,
     RelevanceFeedbackTypeDef,
+    ResponseMetadataTypeDef,
     SeedUrlConfigurationTypeDef,
     SiteMapsConfigurationTypeDef,
     StartDataSourceSyncJobRequestRequestTypeDef,
+    StartDataSourceSyncJobResponseTypeDef,
     StopDataSourceSyncJobRequestRequestTypeDef,
     SuggestionHighlightTypeDef,
     TableCellTypeDef,
     UntagResourceRequestRequestTypeDef,
-    UpdateQuerySuggestionsConfigRequestRequestTypeDef,
+    ListAccessControlConfigurationsResponseTypeDef,
     ColumnConfigurationTypeDef,
     GoogleDriveConfigurationTypeDef,
     SalesforceChatterFeedConfigurationTypeDef,
     SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef,
     SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef,
     SalesforceStandardObjectAttachmentConfigurationTypeDef,
     SalesforceStandardObjectConfigurationTypeDef,
@@ -435,71 +488,68 @@
     WorkDocsConfigurationTypeDef,
     BoxConfigurationTypeDef,
     FsxConfigurationTypeDef,
     JiraConfigurationTypeDef,
     QuipConfigurationTypeDef,
     SlackConfigurationTypeDef,
     AlfrescoConfigurationTypeDef,
+    DescribeFaqResponseTypeDef,
+    DescribeQuerySuggestionsBlockListResponseTypeDef,
+    DescribeThesaurusResponseTypeDef,
     OnPremiseConfigurationTypeDef,
     OneDriveUsersTypeDef,
     UpdateQuerySuggestionsBlockListRequestRequestTypeDef,
     UpdateThesaurusRequestRequestTypeDef,
     AssociateEntitiesToExperienceRequestRequestTypeDef,
     DisassociateEntitiesFromExperienceRequestRequestTypeDef,
     AssociateEntitiesToExperienceResponseTypeDef,
     AssociatePersonasToEntitiesResponseTypeDef,
-    CreateAccessControlConfigurationResponseTypeDef,
-    CreateDataSourceResponseTypeDef,
-    CreateExperienceResponseTypeDef,
-    CreateFaqResponseTypeDef,
-    CreateIndexResponseTypeDef,
-    CreateQuerySuggestionsBlockListResponseTypeDef,
-    CreateThesaurusResponseTypeDef,
-    DescribeFaqResponseTypeDef,
-    DescribeQuerySuggestionsBlockListResponseTypeDef,
-    DescribeQuerySuggestionsConfigResponseTypeDef,
-    DescribeThesaurusResponseTypeDef,
     DisassociateEntitiesFromExperienceResponseTypeDef,
     DisassociatePersonasFromEntitiesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAccessControlConfigurationsResponseTypeDef,
-    StartDataSourceSyncJobResponseTypeDef,
     AssociatePersonasToEntitiesRequestRequestTypeDef,
+    AttributeSuggestionsDescribeConfigTypeDef,
+    AttributeSuggestionsUpdateConfigTypeDef,
     AuthenticationConfigurationTypeDef,
     BatchDeleteDocumentRequestRequestTypeDef,
     BatchDeleteDocumentResponseTypeDef,
+    BatchDeleteFeaturedResultsSetResponseTypeDef,
     BatchGetDocumentStatusResponseTypeDef,
     BatchPutDocumentResponseTypeDef,
     ConfluenceAttachmentConfigurationTypeDef,
     ConfluenceBlogConfigurationTypeDef,
     SharePointConfigurationTypeDef,
     ConfluencePageConfigurationTypeDef,
     ConfluenceSpaceConfigurationTypeDef,
     SpellCorrectedQueryTypeDef,
     HierarchicalPrincipalTypeDef,
     CreateFaqRequestRequestTypeDef,
     CreateQuerySuggestionsBlockListRequestRequestTypeDef,
     CreateThesaurusRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateFeaturedResultsSetRequestRequestTypeDef,
+    FeaturedResultsSetTypeDef,
+    UpdateFeaturedResultsSetRequestRequestTypeDef,
     UserContextTypeDef,
     ListDataSourcesResponseTypeDef,
     DataSourceSyncJobTypeDef,
     ExperiencesSummaryTypeDef,
+    DescribeFeaturedResultsSetResponseTypeDef,
     DescribePrincipalMappingResponseTypeDef,
     DocumentAttributeConditionTypeDef,
     DocumentAttributeTargetTypeDef,
     DocumentAttributeTypeDef,
     DocumentAttributeValueCountPairTypeDef,
     DocumentRelevanceConfigurationTypeDef,
     DocumentMetadataConfigurationTypeDef,
     S3DataSourceConfigurationTypeDef,
     ExperienceEntitiesSummaryTypeDef,
     ExperienceConfigurationTypeDef,
     ListFaqsResponseTypeDef,
+    ListFeaturedResultsSetsResponseTypeDef,
     GetSnapshotsResponseTypeDef,
     ListDataSourceSyncJobsRequestRequestTypeDef,
     GroupMembersTypeDef,
     ListGroupsOlderThanOrderingIdResponseTypeDef,
     TextWithHighlightsTypeDef,
     ListIndicesResponseTypeDef,
     IndexStatisticsTypeDef,
@@ -512,45 +562,56 @@
     SuggestionTextWithHighlightsTypeDef,
     TableRowTypeDef,
     DatabaseConfigurationTypeDef,
     SalesforceKnowledgeArticleConfigurationTypeDef,
     ServiceNowConfigurationTypeDef,
     GitHubConfigurationTypeDef,
     OneDriveConfigurationTypeDef,
+    DescribeQuerySuggestionsConfigResponseTypeDef,
+    UpdateQuerySuggestionsConfigRequestRequestTypeDef,
     ConfluenceConfigurationTypeDef,
     CreateAccessControlConfigurationRequestRequestTypeDef,
     DescribeAccessControlConfigurationResponseTypeDef,
     UpdateAccessControlConfigurationRequestRequestTypeDef,
+    CreateFeaturedResultsSetResponseTypeDef,
+    UpdateFeaturedResultsSetResponseTypeDef,
+    AttributeSuggestionsGetConfigTypeDef,
     ListDataSourceSyncJobsResponseTypeDef,
     ListExperiencesResponseTypeDef,
     HookConfigurationTypeDef,
     InlineCustomDocumentEnrichmentConfigurationTypeDef,
     AttributeFilterTypeDef,
     DocumentInfoTypeDef,
     DocumentTypeDef,
+    RetrieveResultItemTypeDef,
+    SourceDocumentTypeDef,
     QueryRequestRequestTypeDef,
+    RetrieveRequestRequestTypeDef,
     ListExperienceEntitiesResponseTypeDef,
     CreateExperienceRequestRequestTypeDef,
     DescribeExperienceResponseTypeDef,
     UpdateExperienceRequestRequestTypeDef,
     PutPrincipalMappingRequestRequestTypeDef,
     AdditionalResultAttributeValueTypeDef,
     CreateIndexRequestRequestTypeDef,
     DescribeIndexResponseTypeDef,
     UpdateIndexRequestRequestTypeDef,
     WebCrawlerConfigurationTypeDef,
     SuggestionValueTypeDef,
     TableExcerptTypeDef,
     SalesforceConfigurationTypeDef,
+    GetQuerySuggestionsRequestRequestTypeDef,
     CustomDocumentEnrichmentConfigurationTypeDef,
     BatchGetDocumentStatusRequestRequestTypeDef,
+    RetrieveResultTypeDef,
     AdditionalResultAttributeTypeDef,
     SuggestionTypeDef,
     DataSourceConfigurationTypeDef,
     BatchPutDocumentRequestRequestTypeDef,
+    FeaturedResultsItemTypeDef,
     QueryResultItemTypeDef,
     GetQuerySuggestionsResponseTypeDef,
     CreateDataSourceRequestRequestTypeDef,
     DescribeDataSourceResponseTypeDef,
     UpdateDataSourceRequestRequestTypeDef,
     QueryResultTypeDef,
 )
@@ -563,43 +624,43 @@
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

### Comparing `types-aiobotocore-kendra-2.5.0.post1/setup.py` & `types-aiobotocore-kendra-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kendra.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kendra",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kendra"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.kendra 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.kendra 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/"
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

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/__main__.py` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.kendra 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.kendra 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra\nOther"
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

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/client.py` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/client.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -19,45 +19,52 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     DataSourceSyncJobStatusType,
     DataSourceTypeType,
     FaqFileFormatType,
+    FeaturedResultsSetStatusType,
     IndexEditionType,
     IntervalType,
     MetricTypeType,
     ModeType,
     QueryResultTypeType,
+    SuggestionTypeType,
     UserContextPolicyType,
 )
 from .type_defs import (
     AssociateEntitiesToExperienceResponseTypeDef,
     AssociatePersonasToEntitiesResponseTypeDef,
     AttributeFilterTypeDef,
+    AttributeSuggestionsGetConfigTypeDef,
+    AttributeSuggestionsUpdateConfigTypeDef,
     BatchDeleteDocumentResponseTypeDef,
+    BatchDeleteFeaturedResultsSetResponseTypeDef,
     BatchGetDocumentStatusResponseTypeDef,
     BatchPutDocumentResponseTypeDef,
     CapacityUnitsConfigurationTypeDef,
     ClickFeedbackTypeDef,
     CreateAccessControlConfigurationResponseTypeDef,
     CreateDataSourceResponseTypeDef,
     CreateExperienceResponseTypeDef,
     CreateFaqResponseTypeDef,
+    CreateFeaturedResultsSetResponseTypeDef,
     CreateIndexResponseTypeDef,
     CreateQuerySuggestionsBlockListResponseTypeDef,
     CreateThesaurusResponseTypeDef,
     CustomDocumentEnrichmentConfigurationTypeDef,
     DataSourceConfigurationTypeDef,
     DataSourceSyncJobMetricTargetTypeDef,
     DataSourceVpcConfigurationTypeDef,
     DescribeAccessControlConfigurationResponseTypeDef,
     DescribeDataSourceResponseTypeDef,
     DescribeExperienceResponseTypeDef,
     DescribeFaqResponseTypeDef,
+    DescribeFeaturedResultsSetResponseTypeDef,
     DescribeIndexResponseTypeDef,
     DescribePrincipalMappingResponseTypeDef,
     DescribeQuerySuggestionsBlockListResponseTypeDef,
     DescribeQuerySuggestionsConfigResponseTypeDef,
     DescribeThesaurusResponseTypeDef,
     DisassociateEntitiesFromExperienceResponseTypeDef,
     DisassociatePersonasFromEntitiesResponseTypeDef,
@@ -66,71 +73,73 @@
     DocumentRelevanceConfigurationTypeDef,
     DocumentTypeDef,
     EmptyResponseMetadataTypeDef,
     EntityConfigurationTypeDef,
     EntityPersonaConfigurationTypeDef,
     ExperienceConfigurationTypeDef,
     FacetTypeDef,
+    FeaturedDocumentTypeDef,
     GetQuerySuggestionsResponseTypeDef,
     GetSnapshotsResponseTypeDef,
     GroupMembersTypeDef,
     HierarchicalPrincipalTypeDef,
     ListAccessControlConfigurationsResponseTypeDef,
     ListDataSourcesResponseTypeDef,
     ListDataSourceSyncJobsResponseTypeDef,
     ListEntityPersonasResponseTypeDef,
     ListExperienceEntitiesResponseTypeDef,
     ListExperiencesResponseTypeDef,
     ListFaqsResponseTypeDef,
+    ListFeaturedResultsSetsResponseTypeDef,
     ListGroupsOlderThanOrderingIdResponseTypeDef,
     ListIndicesResponseTypeDef,
     ListQuerySuggestionsBlockListsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListThesauriResponseTypeDef,
     PrincipalTypeDef,
     QueryResultTypeDef,
     RelevanceFeedbackTypeDef,
+    RetrieveResultTypeDef,
     S3PathTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     SortingConfigurationTypeDef,
     SpellCorrectionConfigurationTypeDef,
     StartDataSourceSyncJobResponseTypeDef,
     TagTypeDef,
     TimeRangeTypeDef,
+    UpdateFeaturedResultsSetResponseTypeDef,
     UserContextTypeDef,
     UserGroupResolutionConfigurationTypeDef,
     UserTokenConfigurationTypeDef,
 )
 
 __all__ = ("kendraClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
+    FeaturedResultsConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidRequestException: Type[BotocoreClientError]
     ResourceAlreadyExistException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceUnavailableException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class kendraClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/)
     """
 
     meta: ClientMeta
@@ -139,102 +148,102 @@
     def exceptions(self) -> Exceptions:
         """
         kendraClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#exceptions)
         """
-
     async def associate_entities_to_experience(
         self, *, Id: str, IndexId: str, EntityList: Sequence[EntityConfigurationTypeDef]
     ) -> AssociateEntitiesToExperienceResponseTypeDef:
         """
         Grants users or groups in your IAM Identity Center identity source access to
         your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.associate_entities_to_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#associate_entities_to_experience)
         """
-
     async def associate_personas_to_entities(
         self, *, Id: str, IndexId: str, Personas: Sequence[EntityPersonaConfigurationTypeDef]
     ) -> AssociatePersonasToEntitiesResponseTypeDef:
         """
         Defines the specific permissions of users or groups in your IAM Identity Center
         identity source with access to your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.associate_personas_to_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#associate_personas_to_entities)
         """
-
     async def batch_delete_document(
         self,
         *,
         IndexId: str,
         DocumentIdList: Sequence[str],
         DataSourceSyncJobMetricTarget: DataSourceSyncJobMetricTargetTypeDef = ...
     ) -> BatchDeleteDocumentResponseTypeDef:
         """
         Removes one or more documents from an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_delete_document)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_delete_document)
         """
+    async def batch_delete_featured_results_set(
+        self, *, IndexId: str, FeaturedResultsSetIds: Sequence[str]
+    ) -> BatchDeleteFeaturedResultsSetResponseTypeDef:
+        """
+        Removes one or more sets of featured results.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_delete_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_delete_featured_results_set)
+        """
     async def batch_get_document_status(
         self, *, IndexId: str, DocumentInfoList: Sequence[DocumentInfoTypeDef]
     ) -> BatchGetDocumentStatusResponseTypeDef:
         """
         Returns the indexing status for one or more documents submitted with the
         [BatchPutDocument](https://docs.aws.amazon.com/kendra/latest/dg/API_BatchPutDocument.html)_
         API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_get_document_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_get_document_status)
         """
-
     async def batch_put_document(
         self,
         *,
         IndexId: str,
         Documents: Sequence[DocumentTypeDef],
         RoleArn: str = ...,
         CustomDocumentEnrichmentConfiguration: CustomDocumentEnrichmentConfigurationTypeDef = ...
     ) -> BatchPutDocumentResponseTypeDef:
         """
         Adds one or more documents to an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_put_document)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_put_document)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#can_paginate)
         """
-
     async def clear_query_suggestions(self, *, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Clears existing query suggestions from an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.clear_query_suggestions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#clear_query_suggestions)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#close)
         """
-
     async def create_access_control_configuration(
         self,
         *,
         IndexId: str,
         Name: str,
         Description: str = ...,
         AccessControlList: Sequence[PrincipalTypeDef] = ...,
@@ -243,15 +252,14 @@
     ) -> CreateAccessControlConfigurationResponseTypeDef:
         """
         Creates an access configuration for your documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_access_control_configuration)
         """
-
     async def create_data_source(
         self,
         *,
         Name: str,
         IndexId: str,
         Type: DataSourceTypeType,
         Configuration: DataSourceConfigurationTypeDef = ...,
@@ -267,15 +275,14 @@
         """
         Creates a data source connector that you want to use with an Amazon Kendra
         index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_data_source)
         """
-
     async def create_experience(
         self,
         *,
         Name: str,
         IndexId: str,
         RoleArn: str = ...,
         Configuration: ExperienceConfigurationTypeDef = ...,
@@ -284,35 +291,53 @@
     ) -> CreateExperienceResponseTypeDef:
         """
         Creates an Amazon Kendra experience such as a search application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_experience)
         """
-
     async def create_faq(
         self,
         *,
         IndexId: str,
         Name: str,
         S3Path: S3PathTypeDef,
         RoleArn: str,
         Description: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
         FileFormat: FaqFileFormatType = ...,
         ClientToken: str = ...,
         LanguageCode: str = ...
     ) -> CreateFaqResponseTypeDef:
         """
-        Creates an new set of frequently asked question (FAQ) questions and answers.
+        Creates a set of frequently ask questions (FAQs) using a specified FAQ file
+        stored in an Amazon S3 bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_faq)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_faq)
         """
+    async def create_featured_results_set(
+        self,
+        *,
+        IndexId: str,
+        FeaturedResultsSetName: str,
+        Description: str = ...,
+        ClientToken: str = ...,
+        Status: FeaturedResultsSetStatusType = ...,
+        QueryTexts: Sequence[str] = ...,
+        FeaturedDocuments: Sequence[FeaturedDocumentTypeDef] = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateFeaturedResultsSetResponseTypeDef:
+        """
+        Creates a set of featured results to display at the top of the search results
+        page.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_featured_results_set)
+        """
     async def create_index(
         self,
         *,
         Name: str,
         RoleArn: str,
         Edition: IndexEditionType = ...,
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef = ...,
@@ -325,15 +350,14 @@
     ) -> CreateIndexResponseTypeDef:
         """
         Creates an Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_index)
         """
-
     async def create_query_suggestions_block_list(
         self,
         *,
         IndexId: str,
         Name: str,
         SourceS3Path: S3PathTypeDef,
         RoleArn: str,
@@ -343,15 +367,14 @@
     ) -> CreateQuerySuggestionsBlockListResponseTypeDef:
         """
         Creates a block list to exlcude certain queries from suggestions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_query_suggestions_block_list)
         """
-
     async def create_thesaurus(
         self,
         *,
         IndexId: str,
         Name: str,
         RoleArn: str,
         SourceS3Path: S3PathTypeDef,
@@ -361,220 +384,213 @@
     ) -> CreateThesaurusResponseTypeDef:
         """
         Creates a thesaurus for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_thesaurus)
         """
-
     async def delete_access_control_configuration(self, *, IndexId: str, Id: str) -> Dict[str, Any]:
         """
         Deletes an access control configuration that you created for your documents in
         an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_access_control_configuration)
         """
-
     async def delete_data_source(self, *, Id: str, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an Amazon Kendra data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_data_source)
         """
-
     async def delete_experience(self, *, Id: str, IndexId: str) -> Dict[str, Any]:
         """
         Deletes your Amazon Kendra experience such as a search application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_experience)
         """
-
     async def delete_faq(self, *, Id: str, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Removes an FAQ from an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_faq)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_faq)
         """
-
     async def delete_index(self, *, Id: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an existing Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_index)
         """
-
     async def delete_principal_mapping(
         self, *, IndexId: str, GroupId: str, DataSourceId: str = ..., OrderingId: int = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a group so that all users and sub groups that belong to the group can no
         longer access documents only available to that group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_principal_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_principal_mapping)
         """
-
     async def delete_query_suggestions_block_list(
         self, *, IndexId: str, Id: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a block list used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_query_suggestions_block_list)
         """
-
     async def delete_thesaurus(self, *, Id: str, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an existing Amazon Kendra thesaurus.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_thesaurus)
         """
-
     async def describe_access_control_configuration(
         self, *, IndexId: str, Id: str
     ) -> DescribeAccessControlConfigurationResponseTypeDef:
         """
         Gets information about an access control configuration that you created for your
         documents in an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_access_control_configuration)
         """
-
     async def describe_data_source(
         self, *, Id: str, IndexId: str
     ) -> DescribeDataSourceResponseTypeDef:
         """
         Gets information about an Amazon Kendra data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_data_source)
         """
-
     async def describe_experience(
         self, *, Id: str, IndexId: str
     ) -> DescribeExperienceResponseTypeDef:
         """
         Gets information about your Amazon Kendra experience such as a search
         application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_experience)
         """
-
     async def describe_faq(self, *, Id: str, IndexId: str) -> DescribeFaqResponseTypeDef:
         """
         Gets information about an FAQ list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_faq)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_faq)
         """
+    async def describe_featured_results_set(
+        self, *, IndexId: str, FeaturedResultsSetId: str
+    ) -> DescribeFeaturedResultsSetResponseTypeDef:
+        """
+        Gets information about a set of featured results.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_featured_results_set)
+        """
     async def describe_index(self, *, Id: str) -> DescribeIndexResponseTypeDef:
         """
         Gets information about an existing Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_index)
         """
-
     async def describe_principal_mapping(
         self, *, IndexId: str, GroupId: str, DataSourceId: str = ...
     ) -> DescribePrincipalMappingResponseTypeDef:
         """
         Describes the processing of `PUT` and `DELETE` actions for mapping users to
         their groups.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_principal_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_principal_mapping)
         """
-
     async def describe_query_suggestions_block_list(
         self, *, IndexId: str, Id: str
     ) -> DescribeQuerySuggestionsBlockListResponseTypeDef:
         """
         Gets information about a block list used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_query_suggestions_block_list)
         """
-
     async def describe_query_suggestions_config(
         self, *, IndexId: str
     ) -> DescribeQuerySuggestionsConfigResponseTypeDef:
         """
         Gets information on the settings of query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_query_suggestions_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_query_suggestions_config)
         """
-
     async def describe_thesaurus(
         self, *, Id: str, IndexId: str
     ) -> DescribeThesaurusResponseTypeDef:
         """
         Gets information about an existing Amazon Kendra thesaurus.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_thesaurus)
         """
-
     async def disassociate_entities_from_experience(
         self, *, Id: str, IndexId: str, EntityList: Sequence[EntityConfigurationTypeDef]
     ) -> DisassociateEntitiesFromExperienceResponseTypeDef:
         """
         Prevents users or groups in your IAM Identity Center identity source from
         accessing your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.disassociate_entities_from_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#disassociate_entities_from_experience)
         """
-
     async def disassociate_personas_from_entities(
         self, *, Id: str, IndexId: str, EntityIds: Sequence[str]
     ) -> DisassociatePersonasFromEntitiesResponseTypeDef:
         """
         Removes the specific permissions of users or groups in your IAM Identity Center
         identity source with access to your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.disassociate_personas_from_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#disassociate_personas_from_entities)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#generate_presigned_url)
         """
-
     async def get_query_suggestions(
-        self, *, IndexId: str, QueryText: str, MaxSuggestionsCount: int = ...
+        self,
+        *,
+        IndexId: str,
+        QueryText: str,
+        MaxSuggestionsCount: int = ...,
+        SuggestionTypes: Sequence[SuggestionTypeType] = ...,
+        AttributeSuggestionsConfig: AttributeSuggestionsGetConfigTypeDef = ...
     ) -> GetQuerySuggestionsResponseTypeDef:
         """
         Fetches the queries that are suggested to your users.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.get_query_suggestions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#get_query_suggestions)
         """
-
     async def get_snapshots(
         self,
         *,
         IndexId: str,
         Interval: IntervalType,
         MetricType: MetricTypeType,
         NextToken: str = ...,
@@ -582,25 +598,23 @@
     ) -> GetSnapshotsResponseTypeDef:
         """
         Retrieves search metrics data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.get_snapshots)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#get_snapshots)
         """
-
     async def list_access_control_configurations(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListAccessControlConfigurationsResponseTypeDef:
         """
         Lists one or more access control configurations for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_access_control_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_access_control_configurations)
         """
-
     async def list_data_source_sync_jobs(
         self,
         *,
         Id: str,
         IndexId: str,
         NextToken: str = ...,
         MaxResults: int = ...,
@@ -609,67 +623,70 @@
     ) -> ListDataSourceSyncJobsResponseTypeDef:
         """
         Gets statistics about synchronizing a data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_data_source_sync_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_data_source_sync_jobs)
         """
-
     async def list_data_sources(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDataSourcesResponseTypeDef:
         """
         Lists the data source connectors that you have created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_data_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_data_sources)
         """
-
     async def list_entity_personas(
         self, *, Id: str, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEntityPersonasResponseTypeDef:
         """
         Lists specific permissions of users and groups with access to your Amazon Kendra
         experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_entity_personas)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_entity_personas)
         """
-
     async def list_experience_entities(
         self, *, Id: str, IndexId: str, NextToken: str = ...
     ) -> ListExperienceEntitiesResponseTypeDef:
         """
         Lists users or groups in your IAM Identity Center identity source that are
         granted access to your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_experience_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_experience_entities)
         """
-
     async def list_experiences(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListExperiencesResponseTypeDef:
         """
         Lists one or more Amazon Kendra experiences.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_experiences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_experiences)
         """
-
     async def list_faqs(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListFaqsResponseTypeDef:
         """
         Gets a list of FAQ lists associated with an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_faqs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_faqs)
         """
+    async def list_featured_results_sets(
+        self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListFeaturedResultsSetsResponseTypeDef:
+        """
+        Lists all your sets of featured results for a given index.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_featured_results_sets)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_featured_results_sets)
+        """
     async def list_groups_older_than_ordering_id(
         self,
         *,
         IndexId: str,
         OrderingId: int,
         DataSourceId: str = ...,
         NextToken: str = ...,
@@ -678,55 +695,50 @@
         """
         Provides a list of groups that are mapped to users before a given ordering or
         timestamp identifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_groups_older_than_ordering_id)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_groups_older_than_ordering_id)
         """
-
     async def list_indices(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListIndicesResponseTypeDef:
         """
         Lists the Amazon Kendra indexes that you created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_indices)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_indices)
         """
-
     async def list_query_suggestions_block_lists(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListQuerySuggestionsBlockListsResponseTypeDef:
         """
         Lists the block lists used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_query_suggestions_block_lists)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_query_suggestions_block_lists)
         """
-
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Gets a list of tags associated with a specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_tags_for_resource)
         """
-
     async def list_thesauri(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListThesauriResponseTypeDef:
         """
         Lists the thesauri for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_thesauri)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_thesauri)
         """
-
     async def put_principal_mapping(
         self,
         *,
         IndexId: str,
         GroupId: str,
         GroupMembers: GroupMembersTypeDef,
         DataSourceId: str = ...,
@@ -736,15 +748,14 @@
         """
         Maps users to their groups so that you only need to provide the user ID when you
         issue the query.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.put_principal_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#put_principal_mapping)
         """
-
     async def query(
         self,
         *,
         IndexId: str,
         QueryText: str = ...,
         AttributeFilter: "AttributeFilterTypeDef" = ...,
         Facets: Sequence["FacetTypeDef"] = ...,
@@ -757,40 +768,57 @@
         PageSize: int = ...,
         SortingConfiguration: SortingConfigurationTypeDef = ...,
         UserContext: UserContextTypeDef = ...,
         VisitorId: str = ...,
         SpellCorrectionConfiguration: SpellCorrectionConfigurationTypeDef = ...
     ) -> QueryResultTypeDef:
         """
-        Searches an active index.
+        Searches an index given an input query.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#query)
         """
+    async def retrieve(
+        self,
+        *,
+        IndexId: str,
+        QueryText: str,
+        AttributeFilter: "AttributeFilterTypeDef" = ...,
+        RequestedDocumentAttributes: Sequence[str] = ...,
+        DocumentRelevanceOverrideConfigurations: Sequence[
+            DocumentRelevanceConfigurationTypeDef
+        ] = ...,
+        PageNumber: int = ...,
+        PageSize: int = ...,
+        UserContext: UserContextTypeDef = ...
+    ) -> RetrieveResultTypeDef:
+        """
+        Retrieves relevant passages or text excerpts given an input query.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.retrieve)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#retrieve)
+        """
     async def start_data_source_sync_job(
         self, *, Id: str, IndexId: str
     ) -> StartDataSourceSyncJobResponseTypeDef:
         """
         Starts a synchronization job for a data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.start_data_source_sync_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#start_data_source_sync_job)
         """
-
     async def stop_data_source_sync_job(
         self, *, Id: str, IndexId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Stops a synchronization job that is currently running.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.stop_data_source_sync_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#stop_data_source_sync_job)
         """
-
     async def submit_feedback(
         self,
         *,
         IndexId: str,
         QueryId: str,
         ClickFeedbackItems: Sequence[ClickFeedbackTypeDef] = ...,
         RelevanceFeedbackItems: Sequence[RelevanceFeedbackTypeDef] = ...
@@ -798,31 +826,28 @@
         """
         Enables you to provide feedback to Amazon Kendra to improve the performance of
         your index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.submit_feedback)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#submit_feedback)
         """
-
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Adds the specified tag to the specified index, FAQ, or data source resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#tag_resource)
         """
-
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a tag from an index, FAQ, or a data source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#untag_resource)
         """
-
     async def update_access_control_configuration(
         self,
         *,
         IndexId: str,
         Id: str,
         Name: str = ...,
         Description: str = ...,
@@ -831,15 +856,14 @@
     ) -> Dict[str, Any]:
         """
         Updates an access control configuration for your documents in an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_access_control_configuration)
         """
-
     async def update_data_source(
         self,
         *,
         Id: str,
         IndexId: str,
         Name: str = ...,
         Configuration: DataSourceConfigurationTypeDef = ...,
@@ -852,15 +876,14 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates an existing Amazon Kendra data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_data_source)
         """
-
     async def update_experience(
         self,
         *,
         Id: str,
         IndexId: str,
         Name: str = ...,
         RoleArn: str = ...,
@@ -869,15 +892,31 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates your Amazon Kendra experience such as a search application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_experience)
         """
+    async def update_featured_results_set(
+        self,
+        *,
+        IndexId: str,
+        FeaturedResultsSetId: str,
+        FeaturedResultsSetName: str = ...,
+        Description: str = ...,
+        Status: FeaturedResultsSetStatusType = ...,
+        QueryTexts: Sequence[str] = ...,
+        FeaturedDocuments: Sequence[FeaturedDocumentTypeDef] = ...
+    ) -> UpdateFeaturedResultsSetResponseTypeDef:
+        """
+        Updates a set of featured results.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_featured_results_set)
+        """
     async def update_index(
         self,
         *,
         Id: str,
         Name: str = ...,
         RoleArn: str = ...,
         Description: str = ...,
@@ -889,15 +928,14 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates an existing Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_index)
         """
-
     async def update_query_suggestions_block_list(
         self,
         *,
         IndexId: str,
         Id: str,
         Name: str = ...,
         Description: str = ...,
@@ -906,32 +944,31 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a block list used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_query_suggestions_block_list)
         """
-
     async def update_query_suggestions_config(
         self,
         *,
         IndexId: str,
         Mode: ModeType = ...,
         QueryLogLookBackWindowInDays: int = ...,
         IncludeQueriesWithoutUserInformation: bool = ...,
         MinimumNumberOfQueryingUsers: int = ...,
-        MinimumQueryCount: int = ...
+        MinimumQueryCount: int = ...,
+        AttributeSuggestionsConfig: AttributeSuggestionsUpdateConfigTypeDef = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates the settings of query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_query_suggestions_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_query_suggestions_config)
         """
-
     async def update_thesaurus(
         self,
         *,
         Id: str,
         IndexId: str,
         Name: str = ...,
         Description: str = ...,
@@ -940,19 +977,17 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a thesaurus for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_thesaurus)
         """
-
     async def __aenter__(self) -> "kendraClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/)
         """
```

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/client.pyi` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/client.py`

 * *Files 19% similar despite different names*

```diff
@@ -19,45 +19,52 @@
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     DataSourceSyncJobStatusType,
     DataSourceTypeType,
     FaqFileFormatType,
+    FeaturedResultsSetStatusType,
     IndexEditionType,
     IntervalType,
     MetricTypeType,
     ModeType,
     QueryResultTypeType,
+    SuggestionTypeType,
     UserContextPolicyType,
 )
 from .type_defs import (
     AssociateEntitiesToExperienceResponseTypeDef,
     AssociatePersonasToEntitiesResponseTypeDef,
     AttributeFilterTypeDef,
+    AttributeSuggestionsGetConfigTypeDef,
+    AttributeSuggestionsUpdateConfigTypeDef,
     BatchDeleteDocumentResponseTypeDef,
+    BatchDeleteFeaturedResultsSetResponseTypeDef,
     BatchGetDocumentStatusResponseTypeDef,
     BatchPutDocumentResponseTypeDef,
     CapacityUnitsConfigurationTypeDef,
     ClickFeedbackTypeDef,
     CreateAccessControlConfigurationResponseTypeDef,
     CreateDataSourceResponseTypeDef,
     CreateExperienceResponseTypeDef,
     CreateFaqResponseTypeDef,
+    CreateFeaturedResultsSetResponseTypeDef,
     CreateIndexResponseTypeDef,
     CreateQuerySuggestionsBlockListResponseTypeDef,
     CreateThesaurusResponseTypeDef,
     CustomDocumentEnrichmentConfigurationTypeDef,
     DataSourceConfigurationTypeDef,
     DataSourceSyncJobMetricTargetTypeDef,
     DataSourceVpcConfigurationTypeDef,
     DescribeAccessControlConfigurationResponseTypeDef,
     DescribeDataSourceResponseTypeDef,
     DescribeExperienceResponseTypeDef,
     DescribeFaqResponseTypeDef,
+    DescribeFeaturedResultsSetResponseTypeDef,
     DescribeIndexResponseTypeDef,
     DescribePrincipalMappingResponseTypeDef,
     DescribeQuerySuggestionsBlockListResponseTypeDef,
     DescribeQuerySuggestionsConfigResponseTypeDef,
     DescribeThesaurusResponseTypeDef,
     DisassociateEntitiesFromExperienceResponseTypeDef,
     DisassociatePersonasFromEntitiesResponseTypeDef,
@@ -66,68 +73,76 @@
     DocumentRelevanceConfigurationTypeDef,
     DocumentTypeDef,
     EmptyResponseMetadataTypeDef,
     EntityConfigurationTypeDef,
     EntityPersonaConfigurationTypeDef,
     ExperienceConfigurationTypeDef,
     FacetTypeDef,
+    FeaturedDocumentTypeDef,
     GetQuerySuggestionsResponseTypeDef,
     GetSnapshotsResponseTypeDef,
     GroupMembersTypeDef,
     HierarchicalPrincipalTypeDef,
     ListAccessControlConfigurationsResponseTypeDef,
     ListDataSourcesResponseTypeDef,
     ListDataSourceSyncJobsResponseTypeDef,
     ListEntityPersonasResponseTypeDef,
     ListExperienceEntitiesResponseTypeDef,
     ListExperiencesResponseTypeDef,
     ListFaqsResponseTypeDef,
+    ListFeaturedResultsSetsResponseTypeDef,
     ListGroupsOlderThanOrderingIdResponseTypeDef,
     ListIndicesResponseTypeDef,
     ListQuerySuggestionsBlockListsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListThesauriResponseTypeDef,
     PrincipalTypeDef,
     QueryResultTypeDef,
     RelevanceFeedbackTypeDef,
+    RetrieveResultTypeDef,
     S3PathTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     SortingConfigurationTypeDef,
     SpellCorrectionConfigurationTypeDef,
     StartDataSourceSyncJobResponseTypeDef,
     TagTypeDef,
     TimeRangeTypeDef,
+    UpdateFeaturedResultsSetResponseTypeDef,
     UserContextTypeDef,
     UserGroupResolutionConfigurationTypeDef,
     UserTokenConfigurationTypeDef,
 )
 
 __all__ = ("kendraClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
+    FeaturedResultsConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidRequestException: Type[BotocoreClientError]
     ResourceAlreadyExistException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceUnavailableException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class kendraClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/)
     """
 
     meta: ClientMeta
@@ -136,93 +151,112 @@
     def exceptions(self) -> Exceptions:
         """
         kendraClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#exceptions)
         """
+
     async def associate_entities_to_experience(
         self, *, Id: str, IndexId: str, EntityList: Sequence[EntityConfigurationTypeDef]
     ) -> AssociateEntitiesToExperienceResponseTypeDef:
         """
         Grants users or groups in your IAM Identity Center identity source access to
         your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.associate_entities_to_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#associate_entities_to_experience)
         """
+
     async def associate_personas_to_entities(
         self, *, Id: str, IndexId: str, Personas: Sequence[EntityPersonaConfigurationTypeDef]
     ) -> AssociatePersonasToEntitiesResponseTypeDef:
         """
         Defines the specific permissions of users or groups in your IAM Identity Center
         identity source with access to your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.associate_personas_to_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#associate_personas_to_entities)
         """
+
     async def batch_delete_document(
         self,
         *,
         IndexId: str,
         DocumentIdList: Sequence[str],
         DataSourceSyncJobMetricTarget: DataSourceSyncJobMetricTargetTypeDef = ...
     ) -> BatchDeleteDocumentResponseTypeDef:
         """
         Removes one or more documents from an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_delete_document)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_delete_document)
         """
+
+    async def batch_delete_featured_results_set(
+        self, *, IndexId: str, FeaturedResultsSetIds: Sequence[str]
+    ) -> BatchDeleteFeaturedResultsSetResponseTypeDef:
+        """
+        Removes one or more sets of featured results.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_delete_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_delete_featured_results_set)
+        """
+
     async def batch_get_document_status(
         self, *, IndexId: str, DocumentInfoList: Sequence[DocumentInfoTypeDef]
     ) -> BatchGetDocumentStatusResponseTypeDef:
         """
         Returns the indexing status for one or more documents submitted with the
         [BatchPutDocument](https://docs.aws.amazon.com/kendra/latest/dg/API_BatchPutDocument.html)_
         API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_get_document_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_get_document_status)
         """
+
     async def batch_put_document(
         self,
         *,
         IndexId: str,
         Documents: Sequence[DocumentTypeDef],
         RoleArn: str = ...,
         CustomDocumentEnrichmentConfiguration: CustomDocumentEnrichmentConfigurationTypeDef = ...
     ) -> BatchPutDocumentResponseTypeDef:
         """
         Adds one or more documents to an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.batch_put_document)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#batch_put_document)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#can_paginate)
         """
+
     async def clear_query_suggestions(self, *, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Clears existing query suggestions from an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.clear_query_suggestions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#clear_query_suggestions)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#close)
         """
+
     async def create_access_control_configuration(
         self,
         *,
         IndexId: str,
         Name: str,
         Description: str = ...,
         AccessControlList: Sequence[PrincipalTypeDef] = ...,
@@ -231,14 +265,15 @@
     ) -> CreateAccessControlConfigurationResponseTypeDef:
         """
         Creates an access configuration for your documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_access_control_configuration)
         """
+
     async def create_data_source(
         self,
         *,
         Name: str,
         IndexId: str,
         Type: DataSourceTypeType,
         Configuration: DataSourceConfigurationTypeDef = ...,
@@ -254,14 +289,15 @@
         """
         Creates a data source connector that you want to use with an Amazon Kendra
         index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_data_source)
         """
+
     async def create_experience(
         self,
         *,
         Name: str,
         IndexId: str,
         RoleArn: str = ...,
         Configuration: ExperienceConfigurationTypeDef = ...,
@@ -270,33 +306,56 @@
     ) -> CreateExperienceResponseTypeDef:
         """
         Creates an Amazon Kendra experience such as a search application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_experience)
         """
+
     async def create_faq(
         self,
         *,
         IndexId: str,
         Name: str,
         S3Path: S3PathTypeDef,
         RoleArn: str,
         Description: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
         FileFormat: FaqFileFormatType = ...,
         ClientToken: str = ...,
         LanguageCode: str = ...
     ) -> CreateFaqResponseTypeDef:
         """
-        Creates an new set of frequently asked question (FAQ) questions and answers.
+        Creates a set of frequently ask questions (FAQs) using a specified FAQ file
+        stored in an Amazon S3 bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_faq)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_faq)
         """
+
+    async def create_featured_results_set(
+        self,
+        *,
+        IndexId: str,
+        FeaturedResultsSetName: str,
+        Description: str = ...,
+        ClientToken: str = ...,
+        Status: FeaturedResultsSetStatusType = ...,
+        QueryTexts: Sequence[str] = ...,
+        FeaturedDocuments: Sequence[FeaturedDocumentTypeDef] = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateFeaturedResultsSetResponseTypeDef:
+        """
+        Creates a set of featured results to display at the top of the search results
+        page.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_featured_results_set)
+        """
+
     async def create_index(
         self,
         *,
         Name: str,
         RoleArn: str,
         Edition: IndexEditionType = ...,
         ServerSideEncryptionConfiguration: ServerSideEncryptionConfigurationTypeDef = ...,
@@ -309,14 +368,15 @@
     ) -> CreateIndexResponseTypeDef:
         """
         Creates an Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_index)
         """
+
     async def create_query_suggestions_block_list(
         self,
         *,
         IndexId: str,
         Name: str,
         SourceS3Path: S3PathTypeDef,
         RoleArn: str,
@@ -326,14 +386,15 @@
     ) -> CreateQuerySuggestionsBlockListResponseTypeDef:
         """
         Creates a block list to exlcude certain queries from suggestions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_query_suggestions_block_list)
         """
+
     async def create_thesaurus(
         self,
         *,
         IndexId: str,
         Name: str,
         RoleArn: str,
         SourceS3Path: S3PathTypeDef,
@@ -343,198 +404,236 @@
     ) -> CreateThesaurusResponseTypeDef:
         """
         Creates a thesaurus for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.create_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#create_thesaurus)
         """
+
     async def delete_access_control_configuration(self, *, IndexId: str, Id: str) -> Dict[str, Any]:
         """
         Deletes an access control configuration that you created for your documents in
         an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_access_control_configuration)
         """
+
     async def delete_data_source(self, *, Id: str, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an Amazon Kendra data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_data_source)
         """
+
     async def delete_experience(self, *, Id: str, IndexId: str) -> Dict[str, Any]:
         """
         Deletes your Amazon Kendra experience such as a search application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_experience)
         """
+
     async def delete_faq(self, *, Id: str, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Removes an FAQ from an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_faq)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_faq)
         """
+
     async def delete_index(self, *, Id: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an existing Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_index)
         """
+
     async def delete_principal_mapping(
         self, *, IndexId: str, GroupId: str, DataSourceId: str = ..., OrderingId: int = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a group so that all users and sub groups that belong to the group can no
         longer access documents only available to that group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_principal_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_principal_mapping)
         """
+
     async def delete_query_suggestions_block_list(
         self, *, IndexId: str, Id: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a block list used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_query_suggestions_block_list)
         """
+
     async def delete_thesaurus(self, *, Id: str, IndexId: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes an existing Amazon Kendra thesaurus.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.delete_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#delete_thesaurus)
         """
+
     async def describe_access_control_configuration(
         self, *, IndexId: str, Id: str
     ) -> DescribeAccessControlConfigurationResponseTypeDef:
         """
         Gets information about an access control configuration that you created for your
         documents in an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_access_control_configuration)
         """
+
     async def describe_data_source(
         self, *, Id: str, IndexId: str
     ) -> DescribeDataSourceResponseTypeDef:
         """
         Gets information about an Amazon Kendra data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_data_source)
         """
+
     async def describe_experience(
         self, *, Id: str, IndexId: str
     ) -> DescribeExperienceResponseTypeDef:
         """
         Gets information about your Amazon Kendra experience such as a search
         application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_experience)
         """
+
     async def describe_faq(self, *, Id: str, IndexId: str) -> DescribeFaqResponseTypeDef:
         """
         Gets information about an FAQ list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_faq)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_faq)
         """
+
+    async def describe_featured_results_set(
+        self, *, IndexId: str, FeaturedResultsSetId: str
+    ) -> DescribeFeaturedResultsSetResponseTypeDef:
+        """
+        Gets information about a set of featured results.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_featured_results_set)
+        """
+
     async def describe_index(self, *, Id: str) -> DescribeIndexResponseTypeDef:
         """
         Gets information about an existing Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_index)
         """
+
     async def describe_principal_mapping(
         self, *, IndexId: str, GroupId: str, DataSourceId: str = ...
     ) -> DescribePrincipalMappingResponseTypeDef:
         """
         Describes the processing of `PUT` and `DELETE` actions for mapping users to
         their groups.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_principal_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_principal_mapping)
         """
+
     async def describe_query_suggestions_block_list(
         self, *, IndexId: str, Id: str
     ) -> DescribeQuerySuggestionsBlockListResponseTypeDef:
         """
         Gets information about a block list used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_query_suggestions_block_list)
         """
+
     async def describe_query_suggestions_config(
         self, *, IndexId: str
     ) -> DescribeQuerySuggestionsConfigResponseTypeDef:
         """
         Gets information on the settings of query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_query_suggestions_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_query_suggestions_config)
         """
+
     async def describe_thesaurus(
         self, *, Id: str, IndexId: str
     ) -> DescribeThesaurusResponseTypeDef:
         """
         Gets information about an existing Amazon Kendra thesaurus.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.describe_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#describe_thesaurus)
         """
+
     async def disassociate_entities_from_experience(
         self, *, Id: str, IndexId: str, EntityList: Sequence[EntityConfigurationTypeDef]
     ) -> DisassociateEntitiesFromExperienceResponseTypeDef:
         """
         Prevents users or groups in your IAM Identity Center identity source from
         accessing your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.disassociate_entities_from_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#disassociate_entities_from_experience)
         """
+
     async def disassociate_personas_from_entities(
         self, *, Id: str, IndexId: str, EntityIds: Sequence[str]
     ) -> DisassociatePersonasFromEntitiesResponseTypeDef:
         """
         Removes the specific permissions of users or groups in your IAM Identity Center
         identity source with access to your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.disassociate_personas_from_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#disassociate_personas_from_entities)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#generate_presigned_url)
         """
+
     async def get_query_suggestions(
-        self, *, IndexId: str, QueryText: str, MaxSuggestionsCount: int = ...
+        self,
+        *,
+        IndexId: str,
+        QueryText: str,
+        MaxSuggestionsCount: int = ...,
+        SuggestionTypes: Sequence[SuggestionTypeType] = ...,
+        AttributeSuggestionsConfig: AttributeSuggestionsGetConfigTypeDef = ...
     ) -> GetQuerySuggestionsResponseTypeDef:
         """
         Fetches the queries that are suggested to your users.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.get_query_suggestions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#get_query_suggestions)
         """
+
     async def get_snapshots(
         self,
         *,
         IndexId: str,
         Interval: IntervalType,
         MetricType: MetricTypeType,
         NextToken: str = ...,
@@ -542,23 +641,25 @@
     ) -> GetSnapshotsResponseTypeDef:
         """
         Retrieves search metrics data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.get_snapshots)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#get_snapshots)
         """
+
     async def list_access_control_configurations(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListAccessControlConfigurationsResponseTypeDef:
         """
         Lists one or more access control configurations for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_access_control_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_access_control_configurations)
         """
+
     async def list_data_source_sync_jobs(
         self,
         *,
         Id: str,
         IndexId: str,
         NextToken: str = ...,
         MaxResults: int = ...,
@@ -567,61 +668,77 @@
     ) -> ListDataSourceSyncJobsResponseTypeDef:
         """
         Gets statistics about synchronizing a data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_data_source_sync_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_data_source_sync_jobs)
         """
+
     async def list_data_sources(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDataSourcesResponseTypeDef:
         """
         Lists the data source connectors that you have created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_data_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_data_sources)
         """
+
     async def list_entity_personas(
         self, *, Id: str, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEntityPersonasResponseTypeDef:
         """
         Lists specific permissions of users and groups with access to your Amazon Kendra
         experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_entity_personas)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_entity_personas)
         """
+
     async def list_experience_entities(
         self, *, Id: str, IndexId: str, NextToken: str = ...
     ) -> ListExperienceEntitiesResponseTypeDef:
         """
         Lists users or groups in your IAM Identity Center identity source that are
         granted access to your Amazon Kendra experience.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_experience_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_experience_entities)
         """
+
     async def list_experiences(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListExperiencesResponseTypeDef:
         """
         Lists one or more Amazon Kendra experiences.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_experiences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_experiences)
         """
+
     async def list_faqs(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListFaqsResponseTypeDef:
         """
         Gets a list of FAQ lists associated with an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_faqs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_faqs)
         """
+
+    async def list_featured_results_sets(
+        self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
+    ) -> ListFeaturedResultsSetsResponseTypeDef:
+        """
+        Lists all your sets of featured results for a given index.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_featured_results_sets)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_featured_results_sets)
+        """
+
     async def list_groups_older_than_ordering_id(
         self,
         *,
         IndexId: str,
         OrderingId: int,
         DataSourceId: str = ...,
         NextToken: str = ...,
@@ -630,50 +747,55 @@
         """
         Provides a list of groups that are mapped to users before a given ordering or
         timestamp identifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_groups_older_than_ordering_id)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_groups_older_than_ordering_id)
         """
+
     async def list_indices(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListIndicesResponseTypeDef:
         """
         Lists the Amazon Kendra indexes that you created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_indices)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_indices)
         """
+
     async def list_query_suggestions_block_lists(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListQuerySuggestionsBlockListsResponseTypeDef:
         """
         Lists the block lists used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_query_suggestions_block_lists)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_query_suggestions_block_lists)
         """
+
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Gets a list of tags associated with a specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_tags_for_resource)
         """
+
     async def list_thesauri(
         self, *, IndexId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListThesauriResponseTypeDef:
         """
         Lists the thesauri for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.list_thesauri)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#list_thesauri)
         """
+
     async def put_principal_mapping(
         self,
         *,
         IndexId: str,
         GroupId: str,
         GroupMembers: GroupMembersTypeDef,
         DataSourceId: str = ...,
@@ -683,14 +805,15 @@
         """
         Maps users to their groups so that you only need to provide the user ID when you
         issue the query.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.put_principal_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#put_principal_mapping)
         """
+
     async def query(
         self,
         *,
         IndexId: str,
         QueryText: str = ...,
         AttributeFilter: "AttributeFilterTypeDef" = ...,
         Facets: Sequence["FacetTypeDef"] = ...,
@@ -703,37 +826,61 @@
         PageSize: int = ...,
         SortingConfiguration: SortingConfigurationTypeDef = ...,
         UserContext: UserContextTypeDef = ...,
         VisitorId: str = ...,
         SpellCorrectionConfiguration: SpellCorrectionConfigurationTypeDef = ...
     ) -> QueryResultTypeDef:
         """
-        Searches an active index.
+        Searches an index given an input query.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.query)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#query)
         """
+
+    async def retrieve(
+        self,
+        *,
+        IndexId: str,
+        QueryText: str,
+        AttributeFilter: "AttributeFilterTypeDef" = ...,
+        RequestedDocumentAttributes: Sequence[str] = ...,
+        DocumentRelevanceOverrideConfigurations: Sequence[
+            DocumentRelevanceConfigurationTypeDef
+        ] = ...,
+        PageNumber: int = ...,
+        PageSize: int = ...,
+        UserContext: UserContextTypeDef = ...
+    ) -> RetrieveResultTypeDef:
+        """
+        Retrieves relevant passages or text excerpts given an input query.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.retrieve)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#retrieve)
+        """
+
     async def start_data_source_sync_job(
         self, *, Id: str, IndexId: str
     ) -> StartDataSourceSyncJobResponseTypeDef:
         """
         Starts a synchronization job for a data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.start_data_source_sync_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#start_data_source_sync_job)
         """
+
     async def stop_data_source_sync_job(
         self, *, Id: str, IndexId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Stops a synchronization job that is currently running.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.stop_data_source_sync_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#stop_data_source_sync_job)
         """
+
     async def submit_feedback(
         self,
         *,
         IndexId: str,
         QueryId: str,
         ClickFeedbackItems: Sequence[ClickFeedbackTypeDef] = ...,
         RelevanceFeedbackItems: Sequence[RelevanceFeedbackTypeDef] = ...
@@ -741,28 +888,31 @@
         """
         Enables you to provide feedback to Amazon Kendra to improve the performance of
         your index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.submit_feedback)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#submit_feedback)
         """
+
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Adds the specified tag to the specified index, FAQ, or data source resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#tag_resource)
         """
+
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a tag from an index, FAQ, or a data source.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#untag_resource)
         """
+
     async def update_access_control_configuration(
         self,
         *,
         IndexId: str,
         Id: str,
         Name: str = ...,
         Description: str = ...,
@@ -771,14 +921,15 @@
     ) -> Dict[str, Any]:
         """
         Updates an access control configuration for your documents in an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_access_control_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_access_control_configuration)
         """
+
     async def update_data_source(
         self,
         *,
         Id: str,
         IndexId: str,
         Name: str = ...,
         Configuration: DataSourceConfigurationTypeDef = ...,
@@ -791,14 +942,15 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates an existing Amazon Kendra data source connector.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_data_source)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_data_source)
         """
+
     async def update_experience(
         self,
         *,
         Id: str,
         IndexId: str,
         Name: str = ...,
         RoleArn: str = ...,
@@ -807,14 +959,33 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates your Amazon Kendra experience such as a search application.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_experience)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_experience)
         """
+
+    async def update_featured_results_set(
+        self,
+        *,
+        IndexId: str,
+        FeaturedResultsSetId: str,
+        FeaturedResultsSetName: str = ...,
+        Description: str = ...,
+        Status: FeaturedResultsSetStatusType = ...,
+        QueryTexts: Sequence[str] = ...,
+        FeaturedDocuments: Sequence[FeaturedDocumentTypeDef] = ...
+    ) -> UpdateFeaturedResultsSetResponseTypeDef:
+        """
+        Updates a set of featured results.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_featured_results_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_featured_results_set)
+        """
+
     async def update_index(
         self,
         *,
         Id: str,
         Name: str = ...,
         RoleArn: str = ...,
         Description: str = ...,
@@ -826,14 +997,15 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates an existing Amazon Kendra index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_index)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_index)
         """
+
     async def update_query_suggestions_block_list(
         self,
         *,
         IndexId: str,
         Id: str,
         Name: str = ...,
         Description: str = ...,
@@ -842,30 +1014,33 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a block list used for query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_query_suggestions_block_list)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_query_suggestions_block_list)
         """
+
     async def update_query_suggestions_config(
         self,
         *,
         IndexId: str,
         Mode: ModeType = ...,
         QueryLogLookBackWindowInDays: int = ...,
         IncludeQueriesWithoutUserInformation: bool = ...,
         MinimumNumberOfQueryingUsers: int = ...,
-        MinimumQueryCount: int = ...
+        MinimumQueryCount: int = ...,
+        AttributeSuggestionsConfig: AttributeSuggestionsUpdateConfigTypeDef = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates the settings of query suggestions for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_query_suggestions_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_query_suggestions_config)
         """
+
     async def update_thesaurus(
         self,
         *,
         Id: str,
         IndexId: str,
         Name: str = ...,
         Description: str = ...,
@@ -874,17 +1049,19 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates a thesaurus for an index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client.update_thesaurus)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/#update_thesaurus)
         """
+
     async def __aenter__(self) -> "kendraClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/client/)
         """
```

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/literals.py` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AdditionalResultAttributeValueTypeType",
     "AlfrescoEntityType",
+    "AttributeSuggestionsModeType",
     "ConditionOperatorType",
     "ConfluenceAttachmentFieldNameType",
     "ConfluenceAuthenticationTypeType",
     "ConfluenceBlogFieldNameType",
     "ConfluencePageFieldNameType",
     "ConfluenceSpaceFieldNameType",
     "ConfluenceVersionType",
@@ -38,14 +39,15 @@
     "DocumentStatusType",
     "EndpointTypeType",
     "EntityTypeType",
     "ErrorCodeType",
     "ExperienceStatusType",
     "FaqFileFormatType",
     "FaqStatusType",
+    "FeaturedResultsSetStatusType",
     "FsxFileSystemTypeType",
     "HighlightTypeType",
     "IndexEditionType",
     "IndexStatusType",
     "IntervalType",
     "IssueSubEntityType",
     "KeyLocationType",
@@ -68,14 +70,15 @@
     "ScoreConfidenceType",
     "ServiceNowAuthenticationTypeType",
     "ServiceNowBuildVersionTypeType",
     "SharePointOnlineAuthenticationTypeType",
     "SharePointVersionType",
     "SlackEntityType",
     "SortOrderType",
+    "SuggestionTypeType",
     "ThesaurusStatusType",
     "TypeType",
     "UserContextPolicyType",
     "UserGroupResolutionModeType",
     "WarningCodeType",
     "WebCrawlerModeType",
     "kendraServiceName",
@@ -83,14 +86,15 @@
     "ResourceServiceName",
     "RegionName",
 )
 
 
 AdditionalResultAttributeValueTypeType = Literal["TEXT_WITH_HIGHLIGHTS_VALUE"]
 AlfrescoEntityType = Literal["blog", "documentLibrary", "wiki"]
+AttributeSuggestionsModeType = Literal["ACTIVE", "INACTIVE"]
 ConditionOperatorType = Literal[
     "BeginsWith",
     "Contains",
     "Equals",
     "Exists",
     "GreaterThan",
     "GreaterThanOrEquals",
@@ -191,14 +195,15 @@
 ]
 EndpointTypeType = Literal["HOME"]
 EntityTypeType = Literal["GROUP", "USER"]
 ErrorCodeType = Literal["InternalError", "InvalidRequest"]
 ExperienceStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED"]
 FaqFileFormatType = Literal["CSV", "CSV_WITH_HEADER", "JSON"]
 FaqStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "UPDATING"]
+FeaturedResultsSetStatusType = Literal["ACTIVE", "INACTIVE"]
 FsxFileSystemTypeType = Literal["WINDOWS"]
 HighlightTypeType = Literal["STANDARD", "THESAURUS_SYNONYM"]
 IndexEditionType = Literal["DEVELOPER_EDITION", "ENTERPRISE_EDITION"]
 IndexStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "SYSTEM_UPDATING", "UPDATING"]
 IntervalType = Literal[
     "ONE_MONTH_AGO", "ONE_WEEK_AGO", "THIS_MONTH", "THIS_WEEK", "TWO_MONTHS_AGO", "TWO_WEEKS_AGO"
 ]
@@ -252,14 +257,15 @@
 ServiceNowBuildVersionTypeType = Literal["LONDON", "OTHERS"]
 SharePointOnlineAuthenticationTypeType = Literal["HTTP_BASIC", "OAUTH2"]
 SharePointVersionType = Literal[
     "SHAREPOINT_2013", "SHAREPOINT_2016", "SHAREPOINT_2019", "SHAREPOINT_ONLINE"
 ]
 SlackEntityType = Literal["DIRECT_MESSAGE", "GROUP_MESSAGE", "PRIVATE_CHANNEL", "PUBLIC_CHANNEL"]
 SortOrderType = Literal["ASC", "DESC"]
+SuggestionTypeType = Literal["DOCUMENT_ATTRIBUTES", "QUERY"]
 ThesaurusStatusType = Literal[
     "ACTIVE", "ACTIVE_BUT_UPDATE_FAILED", "CREATING", "DELETING", "FAILED", "UPDATING"
 ]
 TypeType = Literal["ON_PREMISE", "SAAS"]
 UserContextPolicyType = Literal["ATTRIBUTE_FILTER", "USER_TOKEN"]
 UserGroupResolutionModeType = Literal["AWS_SSO", "NONE"]
 WarningCodeType = Literal["QUERY_LANGUAGE_INVALID_SYNTAX"]
@@ -323,14 +329,15 @@
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
@@ -409,14 +416,15 @@
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
@@ -427,14 +435,15 @@
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
@@ -470,14 +479,15 @@
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
@@ -496,16 +506,19 @@
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
@@ -589,15 +602,17 @@
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
@@ -622,11 +637,12 @@
 RegionName = Literal[
     "ap-northeast-1",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-west-1",
+    "eu-west-2",
     "us-east-1",
     "us-east-2",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/literals.pyi` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -17,14 +17,15 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AdditionalResultAttributeValueTypeType",
     "AlfrescoEntityType",
+    "AttributeSuggestionsModeType",
     "ConditionOperatorType",
     "ConfluenceAttachmentFieldNameType",
     "ConfluenceAuthenticationTypeType",
     "ConfluenceBlogFieldNameType",
     "ConfluencePageFieldNameType",
     "ConfluenceSpaceFieldNameType",
     "ConfluenceVersionType",
@@ -37,14 +38,15 @@
     "DocumentStatusType",
     "EndpointTypeType",
     "EntityTypeType",
     "ErrorCodeType",
     "ExperienceStatusType",
     "FaqFileFormatType",
     "FaqStatusType",
+    "FeaturedResultsSetStatusType",
     "FsxFileSystemTypeType",
     "HighlightTypeType",
     "IndexEditionType",
     "IndexStatusType",
     "IntervalType",
     "IssueSubEntityType",
     "KeyLocationType",
@@ -67,28 +69,30 @@
     "ScoreConfidenceType",
     "ServiceNowAuthenticationTypeType",
     "ServiceNowBuildVersionTypeType",
     "SharePointOnlineAuthenticationTypeType",
     "SharePointVersionType",
     "SlackEntityType",
     "SortOrderType",
+    "SuggestionTypeType",
     "ThesaurusStatusType",
     "TypeType",
     "UserContextPolicyType",
     "UserGroupResolutionModeType",
     "WarningCodeType",
     "WebCrawlerModeType",
     "kendraServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 AdditionalResultAttributeValueTypeType = Literal["TEXT_WITH_HIGHLIGHTS_VALUE"]
 AlfrescoEntityType = Literal["blog", "documentLibrary", "wiki"]
+AttributeSuggestionsModeType = Literal["ACTIVE", "INACTIVE"]
 ConditionOperatorType = Literal[
     "BeginsWith",
     "Contains",
     "Equals",
     "Exists",
     "GreaterThan",
     "GreaterThanOrEquals",
@@ -189,14 +193,15 @@
 ]
 EndpointTypeType = Literal["HOME"]
 EntityTypeType = Literal["GROUP", "USER"]
 ErrorCodeType = Literal["InternalError", "InvalidRequest"]
 ExperienceStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED"]
 FaqFileFormatType = Literal["CSV", "CSV_WITH_HEADER", "JSON"]
 FaqStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "UPDATING"]
+FeaturedResultsSetStatusType = Literal["ACTIVE", "INACTIVE"]
 FsxFileSystemTypeType = Literal["WINDOWS"]
 HighlightTypeType = Literal["STANDARD", "THESAURUS_SYNONYM"]
 IndexEditionType = Literal["DEVELOPER_EDITION", "ENTERPRISE_EDITION"]
 IndexStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "SYSTEM_UPDATING", "UPDATING"]
 IntervalType = Literal[
     "ONE_MONTH_AGO", "ONE_WEEK_AGO", "THIS_MONTH", "THIS_WEEK", "TWO_MONTHS_AGO", "TWO_WEEKS_AGO"
 ]
@@ -250,14 +255,15 @@
 ServiceNowBuildVersionTypeType = Literal["LONDON", "OTHERS"]
 SharePointOnlineAuthenticationTypeType = Literal["HTTP_BASIC", "OAUTH2"]
 SharePointVersionType = Literal[
     "SHAREPOINT_2013", "SHAREPOINT_2016", "SHAREPOINT_2019", "SHAREPOINT_ONLINE"
 ]
 SlackEntityType = Literal["DIRECT_MESSAGE", "GROUP_MESSAGE", "PRIVATE_CHANNEL", "PUBLIC_CHANNEL"]
 SortOrderType = Literal["ASC", "DESC"]
+SuggestionTypeType = Literal["DOCUMENT_ATTRIBUTES", "QUERY"]
 ThesaurusStatusType = Literal[
     "ACTIVE", "ACTIVE_BUT_UPDATE_FAILED", "CREATING", "DELETING", "FAILED", "UPDATING"
 ]
 TypeType = Literal["ON_PREMISE", "SAAS"]
 UserContextPolicyType = Literal["ATTRIBUTE_FILTER", "USER_TOKEN"]
 UserGroupResolutionModeType = Literal["AWS_SSO", "NONE"]
 WarningCodeType = Literal["QUERY_LANGUAGE_INVALID_SYNTAX"]
@@ -321,14 +327,15 @@
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
@@ -407,14 +414,15 @@
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
@@ -425,14 +433,15 @@
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
@@ -468,14 +477,15 @@
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
@@ -494,16 +504,19 @@
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
@@ -587,15 +600,17 @@
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
@@ -620,11 +635,12 @@
 RegionName = Literal[
     "ap-northeast-1",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ca-central-1",
     "eu-west-1",
+    "eu-west-2",
     "us-east-1",
     "us-east-2",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/type_defs.py` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AlfrescoEntityType,
+    AttributeSuggestionsModeType,
     ConditionOperatorType,
     ConfluenceAttachmentFieldNameType,
     ConfluenceAuthenticationTypeType,
     ConfluenceBlogFieldNameType,
     ConfluencePageFieldNameType,
     ConfluenceSpaceFieldNameType,
     ConfluenceVersionType,
@@ -34,14 +35,15 @@
     DocumentAttributeValueTypeType,
     DocumentStatusType,
     EntityTypeType,
     ErrorCodeType,
     ExperienceStatusType,
     FaqFileFormatType,
     FaqStatusType,
+    FeaturedResultsSetStatusType,
     HighlightTypeType,
     IndexEditionType,
     IndexStatusType,
     IntervalType,
     IssueSubEntityType,
     KeyLocationType,
     MetricTypeType,
@@ -63,14 +65,15 @@
     ScoreConfidenceType,
     ServiceNowAuthenticationTypeType,
     ServiceNowBuildVersionTypeType,
     SharePointOnlineAuthenticationTypeType,
     SharePointVersionType,
     SlackEntityType,
     SortOrderType,
+    SuggestionTypeType,
     ThesaurusStatusType,
     TypeType,
     UserContextPolicyType,
     UserGroupResolutionModeType,
     WebCrawlerModeType,
 )
 
@@ -89,19 +92,21 @@
     "AccessControlListConfigurationTypeDef",
     "AclConfigurationTypeDef",
     "DataSourceToIndexFieldMappingTypeDef",
     "DataSourceVpcConfigurationTypeDef",
     "S3PathTypeDef",
     "EntityConfigurationTypeDef",
     "FailedEntityTypeDef",
-    "ResponseMetadataTypeDef",
     "EntityPersonaConfigurationTypeDef",
+    "SuggestableConfigTypeDef",
     "BasicAuthenticationConfigurationTypeDef",
     "DataSourceSyncJobMetricTargetTypeDef",
     "BatchDeleteDocumentResponseFailedDocumentTypeDef",
+    "BatchDeleteFeaturedResultsSetErrorTypeDef",
+    "BatchDeleteFeaturedResultsSetRequestRequestTypeDef",
     "BatchGetDocumentStatusResponseErrorTypeDef",
     "StatusTypeDef",
     "BatchPutDocumentResponseFailedDocumentTypeDef",
     "CapacityUnitsConfigurationTypeDef",
     "ClearQuerySuggestionsRequestRequestTypeDef",
     "ClickFeedbackTypeDef",
     "ConfluenceAttachmentToIndexFieldMappingTypeDef",
@@ -109,17 +114,25 @@
     "ProxyConfigurationTypeDef",
     "ConfluencePageToIndexFieldMappingTypeDef",
     "ConfluenceSpaceToIndexFieldMappingTypeDef",
     "ConnectionConfigurationTypeDef",
     "ContentSourceConfigurationTypeDef",
     "CorrectionTypeDef",
     "PrincipalTypeDef",
+    "CreateAccessControlConfigurationResponseTypeDef",
     "TagTypeDef",
+    "CreateDataSourceResponseTypeDef",
+    "CreateExperienceResponseTypeDef",
+    "CreateFaqResponseTypeDef",
+    "FeaturedDocumentTypeDef",
     "ServerSideEncryptionConfigurationTypeDef",
     "UserGroupResolutionConfigurationTypeDef",
+    "CreateIndexResponseTypeDef",
+    "CreateQuerySuggestionsBlockListResponseTypeDef",
+    "CreateThesaurusResponseTypeDef",
     "TemplateConfigurationTypeDef",
     "DataSourceGroupTypeDef",
     "DataSourceSummaryTypeDef",
     "DataSourceSyncJobMetricsTypeDef",
     "SqlConfigurationTypeDef",
     "DeleteAccessControlConfigurationRequestRequestTypeDef",
     "DeleteDataSourceRequestRequestTypeDef",
@@ -130,32 +143,36 @@
     "DeleteQuerySuggestionsBlockListRequestRequestTypeDef",
     "DeleteThesaurusRequestRequestTypeDef",
     "DescribeAccessControlConfigurationRequestRequestTypeDef",
     "DescribeDataSourceRequestRequestTypeDef",
     "DescribeExperienceRequestRequestTypeDef",
     "ExperienceEndpointTypeDef",
     "DescribeFaqRequestRequestTypeDef",
+    "DescribeFeaturedResultsSetRequestRequestTypeDef",
+    "FeaturedDocumentMissingTypeDef",
+    "FeaturedDocumentWithMetadataTypeDef",
     "DescribeIndexRequestRequestTypeDef",
     "DescribePrincipalMappingRequestRequestTypeDef",
     "GroupOrderingIdSummaryTypeDef",
     "DescribeQuerySuggestionsBlockListRequestRequestTypeDef",
     "DescribeQuerySuggestionsConfigRequestRequestTypeDef",
     "DescribeThesaurusRequestRequestTypeDef",
     "DisassociatePersonasFromEntitiesRequestRequestTypeDef",
     "DocumentAttributeValueTypeDef",
     "RelevanceTypeDef",
     "SearchTypeDef",
     "DocumentsMetadataConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EntityDisplayDataTypeDef",
     "UserIdentityConfigurationTypeDef",
     "FacetResultTypeDef",
     "FacetTypeDef",
     "FaqStatisticsTypeDef",
     "FaqSummaryTypeDef",
-    "GetQuerySuggestionsRequestRequestTypeDef",
+    "FeaturedResultsSetSummaryTypeDef",
     "GetSnapshotsRequestRequestTypeDef",
     "TimeRangeTypeDef",
     "GitHubDocumentCrawlPropertiesTypeDef",
     "SaaSConfigurationTypeDef",
     "MemberGroupTypeDef",
     "MemberUserTypeDef",
     "GroupSummaryTypeDef",
@@ -167,34 +184,37 @@
     "ListAccessControlConfigurationsRequestRequestTypeDef",
     "ListDataSourcesRequestRequestTypeDef",
     "ListEntityPersonasRequestRequestTypeDef",
     "PersonasSummaryTypeDef",
     "ListExperienceEntitiesRequestRequestTypeDef",
     "ListExperiencesRequestRequestTypeDef",
     "ListFaqsRequestRequestTypeDef",
+    "ListFeaturedResultsSetsRequestRequestTypeDef",
     "ListGroupsOlderThanOrderingIdRequestRequestTypeDef",
     "ListIndicesRequestRequestTypeDef",
     "ListQuerySuggestionsBlockListsRequestRequestTypeDef",
     "QuerySuggestionsBlockListSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListThesauriRequestRequestTypeDef",
     "ThesaurusSummaryTypeDef",
     "SortingConfigurationTypeDef",
     "SpellCorrectionConfigurationTypeDef",
     "ScoreAttributesTypeDef",
     "WarningTypeDef",
     "RelevanceFeedbackTypeDef",
+    "ResponseMetadataTypeDef",
     "SeedUrlConfigurationTypeDef",
     "SiteMapsConfigurationTypeDef",
     "StartDataSourceSyncJobRequestRequestTypeDef",
+    "StartDataSourceSyncJobResponseTypeDef",
     "StopDataSourceSyncJobRequestRequestTypeDef",
     "SuggestionHighlightTypeDef",
     "TableCellTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "UpdateQuerySuggestionsConfigRequestRequestTypeDef",
+    "ListAccessControlConfigurationsResponseTypeDef",
     "ColumnConfigurationTypeDef",
     "GoogleDriveConfigurationTypeDef",
     "SalesforceChatterFeedConfigurationTypeDef",
     "SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef",
     "SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef",
     "SalesforceStandardObjectAttachmentConfigurationTypeDef",
     "SalesforceStandardObjectConfigurationTypeDef",
@@ -203,71 +223,68 @@
     "WorkDocsConfigurationTypeDef",
     "BoxConfigurationTypeDef",
     "FsxConfigurationTypeDef",
     "JiraConfigurationTypeDef",
     "QuipConfigurationTypeDef",
     "SlackConfigurationTypeDef",
     "AlfrescoConfigurationTypeDef",
+    "DescribeFaqResponseTypeDef",
+    "DescribeQuerySuggestionsBlockListResponseTypeDef",
+    "DescribeThesaurusResponseTypeDef",
     "OnPremiseConfigurationTypeDef",
     "OneDriveUsersTypeDef",
     "UpdateQuerySuggestionsBlockListRequestRequestTypeDef",
     "UpdateThesaurusRequestRequestTypeDef",
     "AssociateEntitiesToExperienceRequestRequestTypeDef",
     "DisassociateEntitiesFromExperienceRequestRequestTypeDef",
     "AssociateEntitiesToExperienceResponseTypeDef",
     "AssociatePersonasToEntitiesResponseTypeDef",
-    "CreateAccessControlConfigurationResponseTypeDef",
-    "CreateDataSourceResponseTypeDef",
-    "CreateExperienceResponseTypeDef",
-    "CreateFaqResponseTypeDef",
-    "CreateIndexResponseTypeDef",
-    "CreateQuerySuggestionsBlockListResponseTypeDef",
-    "CreateThesaurusResponseTypeDef",
-    "DescribeFaqResponseTypeDef",
-    "DescribeQuerySuggestionsBlockListResponseTypeDef",
-    "DescribeQuerySuggestionsConfigResponseTypeDef",
-    "DescribeThesaurusResponseTypeDef",
     "DisassociateEntitiesFromExperienceResponseTypeDef",
     "DisassociatePersonasFromEntitiesResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListAccessControlConfigurationsResponseTypeDef",
-    "StartDataSourceSyncJobResponseTypeDef",
     "AssociatePersonasToEntitiesRequestRequestTypeDef",
+    "AttributeSuggestionsDescribeConfigTypeDef",
+    "AttributeSuggestionsUpdateConfigTypeDef",
     "AuthenticationConfigurationTypeDef",
     "BatchDeleteDocumentRequestRequestTypeDef",
     "BatchDeleteDocumentResponseTypeDef",
+    "BatchDeleteFeaturedResultsSetResponseTypeDef",
     "BatchGetDocumentStatusResponseTypeDef",
     "BatchPutDocumentResponseTypeDef",
     "ConfluenceAttachmentConfigurationTypeDef",
     "ConfluenceBlogConfigurationTypeDef",
     "SharePointConfigurationTypeDef",
     "ConfluencePageConfigurationTypeDef",
     "ConfluenceSpaceConfigurationTypeDef",
     "SpellCorrectedQueryTypeDef",
     "HierarchicalPrincipalTypeDef",
     "CreateFaqRequestRequestTypeDef",
     "CreateQuerySuggestionsBlockListRequestRequestTypeDef",
     "CreateThesaurusRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "CreateFeaturedResultsSetRequestRequestTypeDef",
+    "FeaturedResultsSetTypeDef",
+    "UpdateFeaturedResultsSetRequestRequestTypeDef",
     "UserContextTypeDef",
     "ListDataSourcesResponseTypeDef",
     "DataSourceSyncJobTypeDef",
     "ExperiencesSummaryTypeDef",
+    "DescribeFeaturedResultsSetResponseTypeDef",
     "DescribePrincipalMappingResponseTypeDef",
     "DocumentAttributeConditionTypeDef",
     "DocumentAttributeTargetTypeDef",
     "DocumentAttributeTypeDef",
     "DocumentAttributeValueCountPairTypeDef",
     "DocumentRelevanceConfigurationTypeDef",
     "DocumentMetadataConfigurationTypeDef",
     "S3DataSourceConfigurationTypeDef",
     "ExperienceEntitiesSummaryTypeDef",
     "ExperienceConfigurationTypeDef",
     "ListFaqsResponseTypeDef",
+    "ListFeaturedResultsSetsResponseTypeDef",
     "GetSnapshotsResponseTypeDef",
     "ListDataSourceSyncJobsRequestRequestTypeDef",
     "GroupMembersTypeDef",
     "ListGroupsOlderThanOrderingIdResponseTypeDef",
     "TextWithHighlightsTypeDef",
     "ListIndicesResponseTypeDef",
     "IndexStatisticsTypeDef",
@@ -280,45 +297,56 @@
     "SuggestionTextWithHighlightsTypeDef",
     "TableRowTypeDef",
     "DatabaseConfigurationTypeDef",
     "SalesforceKnowledgeArticleConfigurationTypeDef",
     "ServiceNowConfigurationTypeDef",
     "GitHubConfigurationTypeDef",
     "OneDriveConfigurationTypeDef",
+    "DescribeQuerySuggestionsConfigResponseTypeDef",
+    "UpdateQuerySuggestionsConfigRequestRequestTypeDef",
     "ConfluenceConfigurationTypeDef",
     "CreateAccessControlConfigurationRequestRequestTypeDef",
     "DescribeAccessControlConfigurationResponseTypeDef",
     "UpdateAccessControlConfigurationRequestRequestTypeDef",
+    "CreateFeaturedResultsSetResponseTypeDef",
+    "UpdateFeaturedResultsSetResponseTypeDef",
+    "AttributeSuggestionsGetConfigTypeDef",
     "ListDataSourceSyncJobsResponseTypeDef",
     "ListExperiencesResponseTypeDef",
     "HookConfigurationTypeDef",
     "InlineCustomDocumentEnrichmentConfigurationTypeDef",
     "AttributeFilterTypeDef",
     "DocumentInfoTypeDef",
     "DocumentTypeDef",
+    "RetrieveResultItemTypeDef",
+    "SourceDocumentTypeDef",
     "QueryRequestRequestTypeDef",
+    "RetrieveRequestRequestTypeDef",
     "ListExperienceEntitiesResponseTypeDef",
     "CreateExperienceRequestRequestTypeDef",
     "DescribeExperienceResponseTypeDef",
     "UpdateExperienceRequestRequestTypeDef",
     "PutPrincipalMappingRequestRequestTypeDef",
     "AdditionalResultAttributeValueTypeDef",
     "CreateIndexRequestRequestTypeDef",
     "DescribeIndexResponseTypeDef",
     "UpdateIndexRequestRequestTypeDef",
     "WebCrawlerConfigurationTypeDef",
     "SuggestionValueTypeDef",
     "TableExcerptTypeDef",
     "SalesforceConfigurationTypeDef",
+    "GetQuerySuggestionsRequestRequestTypeDef",
     "CustomDocumentEnrichmentConfigurationTypeDef",
     "BatchGetDocumentStatusRequestRequestTypeDef",
+    "RetrieveResultTypeDef",
     "AdditionalResultAttributeTypeDef",
     "SuggestionTypeDef",
     "DataSourceConfigurationTypeDef",
     "BatchPutDocumentRequestRequestTypeDef",
+    "FeaturedResultsItemTypeDef",
     "QueryResultItemTypeDef",
     "GetQuerySuggestionsResponseTypeDef",
     "CreateDataSourceRequestRequestTypeDef",
     "DescribeDataSourceResponseTypeDef",
     "UpdateDataSourceRequestRequestTypeDef",
     "QueryResultTypeDef",
 )
@@ -396,33 +424,31 @@
     {
         "EntityId": str,
         "ErrorMessage": str,
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
 EntityPersonaConfigurationTypeDef = TypedDict(
     "EntityPersonaConfigurationTypeDef",
     {
         "EntityId": str,
         "Persona": PersonaType,
     },
 )
 
+SuggestableConfigTypeDef = TypedDict(
+    "SuggestableConfigTypeDef",
+    {
+        "AttributeName": str,
+        "Suggestable": bool,
+    },
+    total=False,
+)
+
 BasicAuthenticationConfigurationTypeDef = TypedDict(
     "BasicAuthenticationConfigurationTypeDef",
     {
         "Host": str,
         "Port": int,
         "Credentials": str,
     },
@@ -455,14 +481,31 @@
         "Id": str,
         "ErrorCode": ErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+BatchDeleteFeaturedResultsSetErrorTypeDef = TypedDict(
+    "BatchDeleteFeaturedResultsSetErrorTypeDef",
+    {
+        "Id": str,
+        "ErrorCode": ErrorCodeType,
+        "ErrorMessage": str,
+    },
+)
+
+BatchDeleteFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "BatchDeleteFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetIds": Sequence[str],
+    },
+)
+
 BatchGetDocumentStatusResponseErrorTypeDef = TypedDict(
     "BatchGetDocumentStatusResponseErrorTypeDef",
     {
         "DocumentId": str,
         "ErrorCode": ErrorCodeType,
         "ErrorMessage": str,
     },
@@ -624,22 +667,62 @@
 )
 
 
 class PrincipalTypeDef(_RequiredPrincipalTypeDef, _OptionalPrincipalTypeDef):
     pass
 
 
+CreateAccessControlConfigurationResponseTypeDef = TypedDict(
+    "CreateAccessControlConfigurationResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateDataSourceResponseTypeDef = TypedDict(
+    "CreateDataSourceResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateExperienceResponseTypeDef = TypedDict(
+    "CreateExperienceResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFaqResponseTypeDef = TypedDict(
+    "CreateFaqResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+FeaturedDocumentTypeDef = TypedDict(
+    "FeaturedDocumentTypeDef",
+    {
+        "Id": str,
+    },
+    total=False,
+)
+
 ServerSideEncryptionConfigurationTypeDef = TypedDict(
     "ServerSideEncryptionConfigurationTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
@@ -647,14 +730,38 @@
 UserGroupResolutionConfigurationTypeDef = TypedDict(
     "UserGroupResolutionConfigurationTypeDef",
     {
         "UserGroupResolutionMode": UserGroupResolutionModeType,
     },
 )
 
+CreateIndexResponseTypeDef = TypedDict(
+    "CreateIndexResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateQuerySuggestionsBlockListResponseTypeDef = TypedDict(
+    "CreateQuerySuggestionsBlockListResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateThesaurusResponseTypeDef = TypedDict(
+    "CreateThesaurusResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TemplateConfigurationTypeDef = TypedDict(
     "TemplateConfigurationTypeDef",
     {
         "Template": Mapping[str, Any],
     },
     total=False,
 )
@@ -817,14 +924,40 @@
     "DescribeFaqRequestRequestTypeDef",
     {
         "Id": str,
         "IndexId": str,
     },
 )
 
+DescribeFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "DescribeFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetId": str,
+    },
+)
+
+FeaturedDocumentMissingTypeDef = TypedDict(
+    "FeaturedDocumentMissingTypeDef",
+    {
+        "Id": str,
+    },
+    total=False,
+)
+
+FeaturedDocumentWithMetadataTypeDef = TypedDict(
+    "FeaturedDocumentWithMetadataTypeDef",
+    {
+        "Id": str,
+        "Title": str,
+        "URI": str,
+    },
+    total=False,
+)
+
 DescribeIndexRequestRequestTypeDef = TypedDict(
     "DescribeIndexRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -933,14 +1066,21 @@
     "DocumentsMetadataConfigurationTypeDef",
     {
         "S3Prefix": str,
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
 EntityDisplayDataTypeDef = TypedDict(
     "EntityDisplayDataTypeDef",
     {
         "UserName": str,
         "GroupName": str,
         "IdentifiedUserName": str,
         "FirstName": str,
@@ -994,37 +1134,26 @@
         "UpdatedAt": datetime,
         "FileFormat": FaqFileFormatType,
         "LanguageCode": str,
     },
     total=False,
 )
 
-_RequiredGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
-    "_RequiredGetQuerySuggestionsRequestRequestTypeDef",
+FeaturedResultsSetSummaryTypeDef = TypedDict(
+    "FeaturedResultsSetSummaryTypeDef",
     {
-        "IndexId": str,
-        "QueryText": str,
-    },
-)
-_OptionalGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
-    "_OptionalGetQuerySuggestionsRequestRequestTypeDef",
-    {
-        "MaxSuggestionsCount": int,
+        "FeaturedResultsSetId": str,
+        "FeaturedResultsSetName": str,
+        "Status": FeaturedResultsSetStatusType,
+        "LastUpdatedTimestamp": int,
+        "CreationTimestamp": int,
     },
     total=False,
 )
 
-
-class GetQuerySuggestionsRequestRequestTypeDef(
-    _RequiredGetQuerySuggestionsRequestRequestTypeDef,
-    _OptionalGetQuerySuggestionsRequestRequestTypeDef,
-):
-    pass
-
-
 _RequiredGetSnapshotsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSnapshotsRequestRequestTypeDef",
     {
         "IndexId": str,
         "Interval": IntervalType,
         "MetricType": MetricTypeType,
     },
@@ -1342,14 +1471,37 @@
 
 class ListFaqsRequestRequestTypeDef(
     _RequiredListFaqsRequestRequestTypeDef, _OptionalListFaqsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListFeaturedResultsSetsRequestRequestTypeDef = TypedDict(
+    "_RequiredListFeaturedResultsSetsRequestRequestTypeDef",
+    {
+        "IndexId": str,
+    },
+)
+_OptionalListFeaturedResultsSetsRequestRequestTypeDef = TypedDict(
+    "_OptionalListFeaturedResultsSetsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class ListFeaturedResultsSetsRequestRequestTypeDef(
+    _RequiredListFeaturedResultsSetsRequestRequestTypeDef,
+    _OptionalListFeaturedResultsSetsRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredListGroupsOlderThanOrderingIdRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupsOlderThanOrderingIdRequestRequestTypeDef",
     {
         "IndexId": str,
         "OrderingId": int,
     },
 )
@@ -1493,14 +1645,25 @@
     "RelevanceFeedbackTypeDef",
     {
         "ResultId": str,
         "RelevanceValue": RelevanceTypeType,
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
 _RequiredSeedUrlConfigurationTypeDef = TypedDict(
     "_RequiredSeedUrlConfigurationTypeDef",
     {
         "SeedUrls": Sequence[str],
     },
 )
 _OptionalSeedUrlConfigurationTypeDef = TypedDict(
@@ -1529,14 +1692,22 @@
     "StartDataSourceSyncJobRequestRequestTypeDef",
     {
         "Id": str,
         "IndexId": str,
     },
 )
 
+StartDataSourceSyncJobResponseTypeDef = TypedDict(
+    "StartDataSourceSyncJobResponseTypeDef",
+    {
+        "ExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopDataSourceSyncJobRequestRequestTypeDef = TypedDict(
     "StopDataSourceSyncJobRequestRequestTypeDef",
     {
         "Id": str,
         "IndexId": str,
     },
 )
@@ -1565,40 +1736,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
-_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef",
-    {
-        "IndexId": str,
-    },
-)
-_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef",
+ListAccessControlConfigurationsResponseTypeDef = TypedDict(
+    "ListAccessControlConfigurationsResponseTypeDef",
     {
-        "Mode": ModeType,
-        "QueryLogLookBackWindowInDays": int,
-        "IncludeQueriesWithoutUserInformation": bool,
-        "MinimumNumberOfQueryingUsers": int,
-        "MinimumQueryCount": int,
+        "NextToken": str,
+        "AccessControlConfigurations": List[AccessControlConfigurationSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class UpdateQuerySuggestionsConfigRequestRequestTypeDef(
-    _RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef,
-    _OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef,
-):
-    pass
-
-
 _RequiredColumnConfigurationTypeDef = TypedDict(
     "_RequiredColumnConfigurationTypeDef",
     {
         "DocumentIdColumnName": str,
         "DocumentDataColumnName": str,
         "ChangeDetectingColumns": Sequence[str],
     },
@@ -2007,14 +2161,72 @@
 
 class AlfrescoConfigurationTypeDef(
     _RequiredAlfrescoConfigurationTypeDef, _OptionalAlfrescoConfigurationTypeDef
 ):
     pass
 
 
+DescribeFaqResponseTypeDef = TypedDict(
+    "DescribeFaqResponseTypeDef",
+    {
+        "Id": str,
+        "IndexId": str,
+        "Name": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "S3Path": S3PathTypeDef,
+        "Status": FaqStatusType,
+        "RoleArn": str,
+        "ErrorMessage": str,
+        "FileFormat": FaqFileFormatType,
+        "LanguageCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeQuerySuggestionsBlockListResponseTypeDef = TypedDict(
+    "DescribeQuerySuggestionsBlockListResponseTypeDef",
+    {
+        "IndexId": str,
+        "Id": str,
+        "Name": str,
+        "Description": str,
+        "Status": QuerySuggestionsBlockListStatusType,
+        "ErrorMessage": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "SourceS3Path": S3PathTypeDef,
+        "ItemCount": int,
+        "FileSizeBytes": int,
+        "RoleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeThesaurusResponseTypeDef = TypedDict(
+    "DescribeThesaurusResponseTypeDef",
+    {
+        "Id": str,
+        "IndexId": str,
+        "Name": str,
+        "Description": str,
+        "Status": ThesaurusStatusType,
+        "ErrorMessage": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "RoleArn": str,
+        "SourceS3Path": S3PathTypeDef,
+        "FileSizeBytes": int,
+        "TermCount": int,
+        "SynonymRuleCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OnPremiseConfigurationTypeDef = TypedDict(
     "OnPremiseConfigurationTypeDef",
     {
         "HostUrl": str,
         "OrganizationName": str,
         "SslCertificateS3Path": S3PathTypeDef,
     },
@@ -2098,203 +2310,67 @@
     },
 )
 
 AssociateEntitiesToExperienceResponseTypeDef = TypedDict(
     "AssociateEntitiesToExperienceResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociatePersonasToEntitiesResponseTypeDef = TypedDict(
     "AssociatePersonasToEntitiesResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessControlConfigurationResponseTypeDef = TypedDict(
-    "CreateAccessControlConfigurationResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceResponseTypeDef = TypedDict(
-    "CreateDataSourceResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateExperienceResponseTypeDef = TypedDict(
-    "CreateExperienceResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFaqResponseTypeDef = TypedDict(
-    "CreateFaqResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIndexResponseTypeDef = TypedDict(
-    "CreateIndexResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateQuerySuggestionsBlockListResponseTypeDef = TypedDict(
-    "CreateQuerySuggestionsBlockListResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateThesaurusResponseTypeDef = TypedDict(
-    "CreateThesaurusResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFaqResponseTypeDef = TypedDict(
-    "DescribeFaqResponseTypeDef",
-    {
-        "Id": str,
-        "IndexId": str,
-        "Name": str,
-        "Description": str,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "S3Path": S3PathTypeDef,
-        "Status": FaqStatusType,
-        "RoleArn": str,
-        "ErrorMessage": str,
-        "FileFormat": FaqFileFormatType,
-        "LanguageCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeQuerySuggestionsBlockListResponseTypeDef = TypedDict(
-    "DescribeQuerySuggestionsBlockListResponseTypeDef",
-    {
-        "IndexId": str,
-        "Id": str,
-        "Name": str,
-        "Description": str,
-        "Status": QuerySuggestionsBlockListStatusType,
-        "ErrorMessage": str,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "SourceS3Path": S3PathTypeDef,
-        "ItemCount": int,
-        "FileSizeBytes": int,
-        "RoleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeQuerySuggestionsConfigResponseTypeDef = TypedDict(
-    "DescribeQuerySuggestionsConfigResponseTypeDef",
-    {
-        "Mode": ModeType,
-        "Status": QuerySuggestionsStatusType,
-        "QueryLogLookBackWindowInDays": int,
-        "IncludeQueriesWithoutUserInformation": bool,
-        "MinimumNumberOfQueryingUsers": int,
-        "MinimumQueryCount": int,
-        "LastSuggestionsBuildTime": datetime,
-        "LastClearTime": datetime,
-        "TotalSuggestionsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeThesaurusResponseTypeDef = TypedDict(
-    "DescribeThesaurusResponseTypeDef",
-    {
-        "Id": str,
-        "IndexId": str,
-        "Name": str,
-        "Description": str,
-        "Status": ThesaurusStatusType,
-        "ErrorMessage": str,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "RoleArn": str,
-        "SourceS3Path": S3PathTypeDef,
-        "FileSizeBytes": int,
-        "TermCount": int,
-        "SynonymRuleCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateEntitiesFromExperienceResponseTypeDef = TypedDict(
     "DisassociateEntitiesFromExperienceResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociatePersonasFromEntitiesResponseTypeDef = TypedDict(
     "DisassociatePersonasFromEntitiesResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+AssociatePersonasToEntitiesRequestRequestTypeDef = TypedDict(
+    "AssociatePersonasToEntitiesRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Id": str,
+        "IndexId": str,
+        "Personas": Sequence[EntityPersonaConfigurationTypeDef],
     },
 )
 
-ListAccessControlConfigurationsResponseTypeDef = TypedDict(
-    "ListAccessControlConfigurationsResponseTypeDef",
+AttributeSuggestionsDescribeConfigTypeDef = TypedDict(
+    "AttributeSuggestionsDescribeConfigTypeDef",
     {
-        "NextToken": str,
-        "AccessControlConfigurations": List[AccessControlConfigurationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SuggestableConfigList": List[SuggestableConfigTypeDef],
+        "AttributeSuggestionsMode": AttributeSuggestionsModeType,
     },
+    total=False,
 )
 
-StartDataSourceSyncJobResponseTypeDef = TypedDict(
-    "StartDataSourceSyncJobResponseTypeDef",
+AttributeSuggestionsUpdateConfigTypeDef = TypedDict(
+    "AttributeSuggestionsUpdateConfigTypeDef",
     {
-        "ExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociatePersonasToEntitiesRequestRequestTypeDef = TypedDict(
-    "AssociatePersonasToEntitiesRequestRequestTypeDef",
-    {
-        "Id": str,
-        "IndexId": str,
-        "Personas": Sequence[EntityPersonaConfigurationTypeDef],
+        "SuggestableConfigList": Sequence[SuggestableConfigTypeDef],
+        "AttributeSuggestionsMode": AttributeSuggestionsModeType,
     },
+    total=False,
 )
 
 AuthenticationConfigurationTypeDef = TypedDict(
     "AuthenticationConfigurationTypeDef",
     {
         "BasicAuthentication": Sequence[BasicAuthenticationConfigurationTypeDef],
     },
@@ -2324,32 +2400,40 @@
     pass
 
 
 BatchDeleteDocumentResponseTypeDef = TypedDict(
     "BatchDeleteDocumentResponseTypeDef",
     {
         "FailedDocuments": List[BatchDeleteDocumentResponseFailedDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchDeleteFeaturedResultsSetResponseTypeDef = TypedDict(
+    "BatchDeleteFeaturedResultsSetResponseTypeDef",
+    {
+        "Errors": List[BatchDeleteFeaturedResultsSetErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDocumentStatusResponseTypeDef = TypedDict(
     "BatchGetDocumentStatusResponseTypeDef",
     {
         "Errors": List[BatchGetDocumentStatusResponseErrorTypeDef],
         "DocumentStatusList": List[StatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutDocumentResponseTypeDef = TypedDict(
     "BatchPutDocumentResponseTypeDef",
     {
         "FailedDocuments": List[BatchPutDocumentResponseFailedDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfluenceAttachmentConfigurationTypeDef = TypedDict(
     "ConfluenceAttachmentConfigurationTypeDef",
     {
         "CrawlAttachments": bool,
@@ -2516,26 +2600,96 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+_RequiredCreateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetName": str,
+    },
+)
+_OptionalCreateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "Description": str,
+        "ClientToken": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": Sequence[str],
+        "FeaturedDocuments": Sequence[FeaturedDocumentTypeDef],
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreateFeaturedResultsSetRequestRequestTypeDef(
+    _RequiredCreateFeaturedResultsSetRequestRequestTypeDef,
+    _OptionalCreateFeaturedResultsSetRequestRequestTypeDef,
+):
+    pass
+
+
+FeaturedResultsSetTypeDef = TypedDict(
+    "FeaturedResultsSetTypeDef",
+    {
+        "FeaturedResultsSetId": str,
+        "FeaturedResultsSetName": str,
+        "Description": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": List[str],
+        "FeaturedDocuments": List[FeaturedDocumentTypeDef],
+        "LastUpdatedTimestamp": int,
+        "CreationTimestamp": int,
+    },
+    total=False,
+)
+
+_RequiredUpdateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetId": str,
+    },
+)
+_OptionalUpdateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "FeaturedResultsSetName": str,
+        "Description": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": Sequence[str],
+        "FeaturedDocuments": Sequence[FeaturedDocumentTypeDef],
+    },
+    total=False,
+)
+
+
+class UpdateFeaturedResultsSetRequestRequestTypeDef(
+    _RequiredUpdateFeaturedResultsSetRequestRequestTypeDef,
+    _OptionalUpdateFeaturedResultsSetRequestRequestTypeDef,
+):
+    pass
+
+
 UserContextTypeDef = TypedDict(
     "UserContextTypeDef",
     {
         "Token": str,
         "UserId": str,
         "Groups": Sequence[str],
         "DataSourceGroups": Sequence[DataSourceGroupTypeDef],
@@ -2544,15 +2698,15 @@
 )
 
 ListDataSourcesResponseTypeDef = TypedDict(
     "ListDataSourcesResponseTypeDef",
     {
         "SummaryItems": List[DataSourceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSourceSyncJobTypeDef = TypedDict(
     "DataSourceSyncJobTypeDef",
     {
         "ExecutionId": str,
@@ -2575,22 +2729,38 @@
         "CreatedAt": datetime,
         "Status": ExperienceStatusType,
         "Endpoints": List[ExperienceEndpointTypeDef],
     },
     total=False,
 )
 
+DescribeFeaturedResultsSetResponseTypeDef = TypedDict(
+    "DescribeFeaturedResultsSetResponseTypeDef",
+    {
+        "FeaturedResultsSetId": str,
+        "FeaturedResultsSetName": str,
+        "Description": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": List[str],
+        "FeaturedDocumentsWithMetadata": List[FeaturedDocumentWithMetadataTypeDef],
+        "FeaturedDocumentsMissing": List[FeaturedDocumentMissingTypeDef],
+        "LastUpdatedTimestamp": int,
+        "CreationTimestamp": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePrincipalMappingResponseTypeDef = TypedDict(
     "DescribePrincipalMappingResponseTypeDef",
     {
         "IndexId": str,
         "DataSourceId": str,
         "GroupId": str,
         "GroupOrderingIdSummaries": List[GroupOrderingIdSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDocumentAttributeConditionTypeDef = TypedDict(
     "_RequiredDocumentAttributeConditionTypeDef",
     {
         "ConditionDocumentAttributeKey": str,
@@ -2716,26 +2886,35 @@
 )
 
 ListFaqsResponseTypeDef = TypedDict(
     "ListFaqsResponseTypeDef",
     {
         "NextToken": str,
         "FaqSummaryItems": List[FaqSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFeaturedResultsSetsResponseTypeDef = TypedDict(
+    "ListFeaturedResultsSetsResponseTypeDef",
+    {
+        "FeaturedResultsSetSummaryItems": List[FeaturedResultsSetSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotsResponseTypeDef = TypedDict(
     "GetSnapshotsResponseTypeDef",
     {
         "SnapShotTimeFilter": TimeRangeTypeDef,
         "SnapshotsDataHeader": List[str],
         "SnapshotsData": List[List[str]],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListDataSourceSyncJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSourceSyncJobsRequestRequestTypeDef",
     {
         "Id": str,
@@ -2772,15 +2951,15 @@
 )
 
 ListGroupsOlderThanOrderingIdResponseTypeDef = TypedDict(
     "ListGroupsOlderThanOrderingIdResponseTypeDef",
     {
         "GroupsSummaries": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TextWithHighlightsTypeDef = TypedDict(
     "TextWithHighlightsTypeDef",
     {
         "Text": str,
@@ -2790,15 +2969,15 @@
 )
 
 ListIndicesResponseTypeDef = TypedDict(
     "ListIndicesResponseTypeDef",
     {
         "IndexConfigurationSummaryItems": List[IndexConfigurationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IndexStatisticsTypeDef = TypedDict(
     "IndexStatisticsTypeDef",
     {
         "FaqStatistics": FaqStatisticsTypeDef,
@@ -2816,33 +2995,33 @@
 )
 
 ListEntityPersonasResponseTypeDef = TypedDict(
     "ListEntityPersonasResponseTypeDef",
     {
         "SummaryItems": List[PersonasSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQuerySuggestionsBlockListsResponseTypeDef = TypedDict(
     "ListQuerySuggestionsBlockListsResponseTypeDef",
     {
         "BlockListSummaryItems": List[QuerySuggestionsBlockListSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThesauriResponseTypeDef = TypedDict(
     "ListThesauriResponseTypeDef",
     {
         "NextToken": str,
         "ThesaurusSummaryItems": List[ThesaurusSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSubmitFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredSubmitFeedbackRequestRequestTypeDef",
     {
         "IndexId": str,
@@ -3045,14 +3224,58 @@
 
 class OneDriveConfigurationTypeDef(
     _RequiredOneDriveConfigurationTypeDef, _OptionalOneDriveConfigurationTypeDef
 ):
     pass
 
 
+DescribeQuerySuggestionsConfigResponseTypeDef = TypedDict(
+    "DescribeQuerySuggestionsConfigResponseTypeDef",
+    {
+        "Mode": ModeType,
+        "Status": QuerySuggestionsStatusType,
+        "QueryLogLookBackWindowInDays": int,
+        "IncludeQueriesWithoutUserInformation": bool,
+        "MinimumNumberOfQueryingUsers": int,
+        "MinimumQueryCount": int,
+        "LastSuggestionsBuildTime": datetime,
+        "LastClearTime": datetime,
+        "TotalSuggestionsCount": int,
+        "AttributeSuggestionsConfig": AttributeSuggestionsDescribeConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef",
+    {
+        "IndexId": str,
+    },
+)
+_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef",
+    {
+        "Mode": ModeType,
+        "QueryLogLookBackWindowInDays": int,
+        "IncludeQueriesWithoutUserInformation": bool,
+        "MinimumNumberOfQueryingUsers": int,
+        "MinimumQueryCount": int,
+        "AttributeSuggestionsConfig": AttributeSuggestionsUpdateConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateQuerySuggestionsConfigRequestRequestTypeDef(
+    _RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef,
+    _OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredConfluenceConfigurationTypeDef = TypedDict(
     "_RequiredConfluenceConfigurationTypeDef",
     {
         "ServerUrl": str,
         "SecretArn": str,
         "Version": ConfluenceVersionType,
     },
@@ -3110,15 +3333,15 @@
     "DescribeAccessControlConfigurationResponseTypeDef",
     {
         "Name": str,
         "Description": str,
         "ErrorMessage": str,
         "AccessControlList": List[PrincipalTypeDef],
         "HierarchicalAccessControlList": List[HierarchicalPrincipalTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAccessControlConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAccessControlConfigurationRequestRequestTypeDef",
     {
         "IndexId": str,
@@ -3140,29 +3363,56 @@
 class UpdateAccessControlConfigurationRequestRequestTypeDef(
     _RequiredUpdateAccessControlConfigurationRequestRequestTypeDef,
     _OptionalUpdateAccessControlConfigurationRequestRequestTypeDef,
 ):
     pass
 
 
+CreateFeaturedResultsSetResponseTypeDef = TypedDict(
+    "CreateFeaturedResultsSetResponseTypeDef",
+    {
+        "FeaturedResultsSet": FeaturedResultsSetTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFeaturedResultsSetResponseTypeDef = TypedDict(
+    "UpdateFeaturedResultsSetResponseTypeDef",
+    {
+        "FeaturedResultsSet": FeaturedResultsSetTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AttributeSuggestionsGetConfigTypeDef = TypedDict(
+    "AttributeSuggestionsGetConfigTypeDef",
+    {
+        "SuggestionAttributes": Sequence[str],
+        "AdditionalResponseAttributes": Sequence[str],
+        "AttributeFilter": "AttributeFilterTypeDef",
+        "UserContext": UserContextTypeDef,
+    },
+    total=False,
+)
+
 ListDataSourceSyncJobsResponseTypeDef = TypedDict(
     "ListDataSourceSyncJobsResponseTypeDef",
     {
         "History": List[DataSourceSyncJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExperiencesResponseTypeDef = TypedDict(
     "ListExperiencesResponseTypeDef",
     {
         "SummaryItems": List[ExperiencesSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHookConfigurationTypeDef = TypedDict(
     "_RequiredHookConfigurationTypeDef",
     {
         "LambdaArn": str,
@@ -3252,14 +3502,37 @@
 )
 
 
 class DocumentTypeDef(_RequiredDocumentTypeDef, _OptionalDocumentTypeDef):
     pass
 
 
+RetrieveResultItemTypeDef = TypedDict(
+    "RetrieveResultItemTypeDef",
+    {
+        "Id": str,
+        "DocumentId": str,
+        "DocumentTitle": str,
+        "Content": str,
+        "DocumentURI": str,
+        "DocumentAttributes": List[DocumentAttributeTypeDef],
+    },
+    total=False,
+)
+
+SourceDocumentTypeDef = TypedDict(
+    "SourceDocumentTypeDef",
+    {
+        "DocumentId": str,
+        "SuggestionAttributes": List[str],
+        "AdditionalAttributes": List[DocumentAttributeTypeDef],
+    },
+    total=False,
+)
+
 _RequiredQueryRequestRequestTypeDef = TypedDict(
     "_RequiredQueryRequestRequestTypeDef",
     {
         "IndexId": str,
     },
 )
 _OptionalQueryRequestRequestTypeDef = TypedDict(
@@ -3284,20 +3557,47 @@
 
 class QueryRequestRequestTypeDef(
     _RequiredQueryRequestRequestTypeDef, _OptionalQueryRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredRetrieveRequestRequestTypeDef = TypedDict(
+    "_RequiredRetrieveRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "QueryText": str,
+    },
+)
+_OptionalRetrieveRequestRequestTypeDef = TypedDict(
+    "_OptionalRetrieveRequestRequestTypeDef",
+    {
+        "AttributeFilter": "AttributeFilterTypeDef",
+        "RequestedDocumentAttributes": Sequence[str],
+        "DocumentRelevanceOverrideConfigurations": Sequence[DocumentRelevanceConfigurationTypeDef],
+        "PageNumber": int,
+        "PageSize": int,
+        "UserContext": UserContextTypeDef,
+    },
+    total=False,
+)
+
+
+class RetrieveRequestRequestTypeDef(
+    _RequiredRetrieveRequestRequestTypeDef, _OptionalRetrieveRequestRequestTypeDef
+):
+    pass
+
+
 ListExperienceEntitiesResponseTypeDef = TypedDict(
     "ListExperienceEntitiesResponseTypeDef",
     {
         "SummaryItems": List[ExperienceEntitiesSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateExperienceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExperienceRequestRequestTypeDef",
     {
         "Name": str,
@@ -3332,15 +3632,15 @@
         "Configuration": ExperienceConfigurationTypeDef,
         "CreatedAt": datetime,
         "UpdatedAt": datetime,
         "Description": str,
         "Status": ExperienceStatusType,
         "RoleArn": str,
         "ErrorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateExperienceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateExperienceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3443,15 +3743,15 @@
         "DocumentMetadataConfigurations": List[DocumentMetadataConfigurationTypeDef],
         "IndexStatistics": IndexStatisticsTypeDef,
         "ErrorMessage": str,
         "CapacityUnits": CapacityUnitsConfigurationTypeDef,
         "UserTokenConfigurations": List[UserTokenConfigurationTypeDef],
         "UserContextPolicy": UserContextPolicyType,
         "UserGroupResolutionConfiguration": UserGroupResolutionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateIndexRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIndexRequestRequestTypeDef",
     {
         "Id": str,
@@ -3550,14 +3850,39 @@
 
 class SalesforceConfigurationTypeDef(
     _RequiredSalesforceConfigurationTypeDef, _OptionalSalesforceConfigurationTypeDef
 ):
     pass
 
 
+_RequiredGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetQuerySuggestionsRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "QueryText": str,
+    },
+)
+_OptionalGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetQuerySuggestionsRequestRequestTypeDef",
+    {
+        "MaxSuggestionsCount": int,
+        "SuggestionTypes": Sequence[SuggestionTypeType],
+        "AttributeSuggestionsConfig": AttributeSuggestionsGetConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class GetQuerySuggestionsRequestRequestTypeDef(
+    _RequiredGetQuerySuggestionsRequestRequestTypeDef,
+    _OptionalGetQuerySuggestionsRequestRequestTypeDef,
+):
+    pass
+
+
 CustomDocumentEnrichmentConfigurationTypeDef = TypedDict(
     "CustomDocumentEnrichmentConfigurationTypeDef",
     {
         "InlineConfigurations": Sequence[InlineCustomDocumentEnrichmentConfigurationTypeDef],
         "PreExtractionHookConfiguration": HookConfigurationTypeDef,
         "PostExtractionHookConfiguration": HookConfigurationTypeDef,
         "RoleArn": str,
@@ -3569,28 +3894,38 @@
     "BatchGetDocumentStatusRequestRequestTypeDef",
     {
         "IndexId": str,
         "DocumentInfoList": Sequence[DocumentInfoTypeDef],
     },
 )
 
+RetrieveResultTypeDef = TypedDict(
+    "RetrieveResultTypeDef",
+    {
+        "QueryId": str,
+        "ResultItems": List[RetrieveResultItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AdditionalResultAttributeTypeDef = TypedDict(
     "AdditionalResultAttributeTypeDef",
     {
         "Key": str,
         "ValueType": Literal["TEXT_WITH_HIGHLIGHTS_VALUE"],
         "Value": AdditionalResultAttributeValueTypeDef,
     },
 )
 
 SuggestionTypeDef = TypedDict(
     "SuggestionTypeDef",
     {
         "Id": str,
         "Value": SuggestionValueTypeDef,
+        "SourceDocuments": List[SourceDocumentTypeDef],
     },
     total=False,
 )
 
 DataSourceConfigurationTypeDef = TypedDict(
     "DataSourceConfigurationTypeDef",
     {
@@ -3635,14 +3970,30 @@
 
 class BatchPutDocumentRequestRequestTypeDef(
     _RequiredBatchPutDocumentRequestRequestTypeDef, _OptionalBatchPutDocumentRequestRequestTypeDef
 ):
     pass
 
 
+FeaturedResultsItemTypeDef = TypedDict(
+    "FeaturedResultsItemTypeDef",
+    {
+        "Id": str,
+        "Type": QueryResultTypeType,
+        "AdditionalAttributes": List[AdditionalResultAttributeTypeDef],
+        "DocumentId": str,
+        "DocumentTitle": TextWithHighlightsTypeDef,
+        "DocumentExcerpt": TextWithHighlightsTypeDef,
+        "DocumentURI": str,
+        "DocumentAttributes": List[DocumentAttributeTypeDef],
+        "FeedbackToken": str,
+    },
+    total=False,
+)
+
 QueryResultItemTypeDef = TypedDict(
     "QueryResultItemTypeDef",
     {
         "Id": str,
         "Type": QueryResultTypeType,
         "Format": QueryResultFormatType,
         "AdditionalAttributes": List[AdditionalResultAttributeTypeDef],
@@ -3659,15 +4010,15 @@
 )
 
 GetQuerySuggestionsResponseTypeDef = TypedDict(
     "GetQuerySuggestionsResponseTypeDef",
     {
         "QuerySuggestionsId": str,
         "Suggestions": List[SuggestionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceRequestRequestTypeDef",
     {
         "Name": str,
@@ -3712,15 +4063,15 @@
         "Description": str,
         "Status": DataSourceStatusType,
         "Schedule": str,
         "RoleArn": str,
         "ErrorMessage": str,
         "LanguageCode": str,
         "CustomDocumentEnrichmentConfiguration": CustomDocumentEnrichmentConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDataSourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDataSourceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3754,10 +4105,11 @@
     {
         "QueryId": str,
         "ResultItems": List[QueryResultItemTypeDef],
         "FacetResults": List["FacetResultTypeDef"],
         "TotalNumberOfResults": int,
         "Warnings": List[WarningTypeDef],
         "SpellCorrectedQueries": List[SpellCorrectedQueryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FeaturedResultsItems": List[FeaturedResultsItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra/type_defs.pyi` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AlfrescoEntityType,
+    AttributeSuggestionsModeType,
     ConditionOperatorType,
     ConfluenceAttachmentFieldNameType,
     ConfluenceAuthenticationTypeType,
     ConfluenceBlogFieldNameType,
     ConfluencePageFieldNameType,
     ConfluenceSpaceFieldNameType,
     ConfluenceVersionType,
@@ -34,14 +35,15 @@
     DocumentAttributeValueTypeType,
     DocumentStatusType,
     EntityTypeType,
     ErrorCodeType,
     ExperienceStatusType,
     FaqFileFormatType,
     FaqStatusType,
+    FeaturedResultsSetStatusType,
     HighlightTypeType,
     IndexEditionType,
     IndexStatusType,
     IntervalType,
     IssueSubEntityType,
     KeyLocationType,
     MetricTypeType,
@@ -63,14 +65,15 @@
     ScoreConfidenceType,
     ServiceNowAuthenticationTypeType,
     ServiceNowBuildVersionTypeType,
     SharePointOnlineAuthenticationTypeType,
     SharePointVersionType,
     SlackEntityType,
     SortOrderType,
+    SuggestionTypeType,
     ThesaurusStatusType,
     TypeType,
     UserContextPolicyType,
     UserGroupResolutionModeType,
     WebCrawlerModeType,
 )
 
@@ -88,19 +91,21 @@
     "AccessControlListConfigurationTypeDef",
     "AclConfigurationTypeDef",
     "DataSourceToIndexFieldMappingTypeDef",
     "DataSourceVpcConfigurationTypeDef",
     "S3PathTypeDef",
     "EntityConfigurationTypeDef",
     "FailedEntityTypeDef",
-    "ResponseMetadataTypeDef",
     "EntityPersonaConfigurationTypeDef",
+    "SuggestableConfigTypeDef",
     "BasicAuthenticationConfigurationTypeDef",
     "DataSourceSyncJobMetricTargetTypeDef",
     "BatchDeleteDocumentResponseFailedDocumentTypeDef",
+    "BatchDeleteFeaturedResultsSetErrorTypeDef",
+    "BatchDeleteFeaturedResultsSetRequestRequestTypeDef",
     "BatchGetDocumentStatusResponseErrorTypeDef",
     "StatusTypeDef",
     "BatchPutDocumentResponseFailedDocumentTypeDef",
     "CapacityUnitsConfigurationTypeDef",
     "ClearQuerySuggestionsRequestRequestTypeDef",
     "ClickFeedbackTypeDef",
     "ConfluenceAttachmentToIndexFieldMappingTypeDef",
@@ -108,17 +113,25 @@
     "ProxyConfigurationTypeDef",
     "ConfluencePageToIndexFieldMappingTypeDef",
     "ConfluenceSpaceToIndexFieldMappingTypeDef",
     "ConnectionConfigurationTypeDef",
     "ContentSourceConfigurationTypeDef",
     "CorrectionTypeDef",
     "PrincipalTypeDef",
+    "CreateAccessControlConfigurationResponseTypeDef",
     "TagTypeDef",
+    "CreateDataSourceResponseTypeDef",
+    "CreateExperienceResponseTypeDef",
+    "CreateFaqResponseTypeDef",
+    "FeaturedDocumentTypeDef",
     "ServerSideEncryptionConfigurationTypeDef",
     "UserGroupResolutionConfigurationTypeDef",
+    "CreateIndexResponseTypeDef",
+    "CreateQuerySuggestionsBlockListResponseTypeDef",
+    "CreateThesaurusResponseTypeDef",
     "TemplateConfigurationTypeDef",
     "DataSourceGroupTypeDef",
     "DataSourceSummaryTypeDef",
     "DataSourceSyncJobMetricsTypeDef",
     "SqlConfigurationTypeDef",
     "DeleteAccessControlConfigurationRequestRequestTypeDef",
     "DeleteDataSourceRequestRequestTypeDef",
@@ -129,32 +142,36 @@
     "DeleteQuerySuggestionsBlockListRequestRequestTypeDef",
     "DeleteThesaurusRequestRequestTypeDef",
     "DescribeAccessControlConfigurationRequestRequestTypeDef",
     "DescribeDataSourceRequestRequestTypeDef",
     "DescribeExperienceRequestRequestTypeDef",
     "ExperienceEndpointTypeDef",
     "DescribeFaqRequestRequestTypeDef",
+    "DescribeFeaturedResultsSetRequestRequestTypeDef",
+    "FeaturedDocumentMissingTypeDef",
+    "FeaturedDocumentWithMetadataTypeDef",
     "DescribeIndexRequestRequestTypeDef",
     "DescribePrincipalMappingRequestRequestTypeDef",
     "GroupOrderingIdSummaryTypeDef",
     "DescribeQuerySuggestionsBlockListRequestRequestTypeDef",
     "DescribeQuerySuggestionsConfigRequestRequestTypeDef",
     "DescribeThesaurusRequestRequestTypeDef",
     "DisassociatePersonasFromEntitiesRequestRequestTypeDef",
     "DocumentAttributeValueTypeDef",
     "RelevanceTypeDef",
     "SearchTypeDef",
     "DocumentsMetadataConfigurationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EntityDisplayDataTypeDef",
     "UserIdentityConfigurationTypeDef",
     "FacetResultTypeDef",
     "FacetTypeDef",
     "FaqStatisticsTypeDef",
     "FaqSummaryTypeDef",
-    "GetQuerySuggestionsRequestRequestTypeDef",
+    "FeaturedResultsSetSummaryTypeDef",
     "GetSnapshotsRequestRequestTypeDef",
     "TimeRangeTypeDef",
     "GitHubDocumentCrawlPropertiesTypeDef",
     "SaaSConfigurationTypeDef",
     "MemberGroupTypeDef",
     "MemberUserTypeDef",
     "GroupSummaryTypeDef",
@@ -166,34 +183,37 @@
     "ListAccessControlConfigurationsRequestRequestTypeDef",
     "ListDataSourcesRequestRequestTypeDef",
     "ListEntityPersonasRequestRequestTypeDef",
     "PersonasSummaryTypeDef",
     "ListExperienceEntitiesRequestRequestTypeDef",
     "ListExperiencesRequestRequestTypeDef",
     "ListFaqsRequestRequestTypeDef",
+    "ListFeaturedResultsSetsRequestRequestTypeDef",
     "ListGroupsOlderThanOrderingIdRequestRequestTypeDef",
     "ListIndicesRequestRequestTypeDef",
     "ListQuerySuggestionsBlockListsRequestRequestTypeDef",
     "QuerySuggestionsBlockListSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "ListThesauriRequestRequestTypeDef",
     "ThesaurusSummaryTypeDef",
     "SortingConfigurationTypeDef",
     "SpellCorrectionConfigurationTypeDef",
     "ScoreAttributesTypeDef",
     "WarningTypeDef",
     "RelevanceFeedbackTypeDef",
+    "ResponseMetadataTypeDef",
     "SeedUrlConfigurationTypeDef",
     "SiteMapsConfigurationTypeDef",
     "StartDataSourceSyncJobRequestRequestTypeDef",
+    "StartDataSourceSyncJobResponseTypeDef",
     "StopDataSourceSyncJobRequestRequestTypeDef",
     "SuggestionHighlightTypeDef",
     "TableCellTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "UpdateQuerySuggestionsConfigRequestRequestTypeDef",
+    "ListAccessControlConfigurationsResponseTypeDef",
     "ColumnConfigurationTypeDef",
     "GoogleDriveConfigurationTypeDef",
     "SalesforceChatterFeedConfigurationTypeDef",
     "SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef",
     "SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef",
     "SalesforceStandardObjectAttachmentConfigurationTypeDef",
     "SalesforceStandardObjectConfigurationTypeDef",
@@ -202,71 +222,68 @@
     "WorkDocsConfigurationTypeDef",
     "BoxConfigurationTypeDef",
     "FsxConfigurationTypeDef",
     "JiraConfigurationTypeDef",
     "QuipConfigurationTypeDef",
     "SlackConfigurationTypeDef",
     "AlfrescoConfigurationTypeDef",
+    "DescribeFaqResponseTypeDef",
+    "DescribeQuerySuggestionsBlockListResponseTypeDef",
+    "DescribeThesaurusResponseTypeDef",
     "OnPremiseConfigurationTypeDef",
     "OneDriveUsersTypeDef",
     "UpdateQuerySuggestionsBlockListRequestRequestTypeDef",
     "UpdateThesaurusRequestRequestTypeDef",
     "AssociateEntitiesToExperienceRequestRequestTypeDef",
     "DisassociateEntitiesFromExperienceRequestRequestTypeDef",
     "AssociateEntitiesToExperienceResponseTypeDef",
     "AssociatePersonasToEntitiesResponseTypeDef",
-    "CreateAccessControlConfigurationResponseTypeDef",
-    "CreateDataSourceResponseTypeDef",
-    "CreateExperienceResponseTypeDef",
-    "CreateFaqResponseTypeDef",
-    "CreateIndexResponseTypeDef",
-    "CreateQuerySuggestionsBlockListResponseTypeDef",
-    "CreateThesaurusResponseTypeDef",
-    "DescribeFaqResponseTypeDef",
-    "DescribeQuerySuggestionsBlockListResponseTypeDef",
-    "DescribeQuerySuggestionsConfigResponseTypeDef",
-    "DescribeThesaurusResponseTypeDef",
     "DisassociateEntitiesFromExperienceResponseTypeDef",
     "DisassociatePersonasFromEntitiesResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListAccessControlConfigurationsResponseTypeDef",
-    "StartDataSourceSyncJobResponseTypeDef",
     "AssociatePersonasToEntitiesRequestRequestTypeDef",
+    "AttributeSuggestionsDescribeConfigTypeDef",
+    "AttributeSuggestionsUpdateConfigTypeDef",
     "AuthenticationConfigurationTypeDef",
     "BatchDeleteDocumentRequestRequestTypeDef",
     "BatchDeleteDocumentResponseTypeDef",
+    "BatchDeleteFeaturedResultsSetResponseTypeDef",
     "BatchGetDocumentStatusResponseTypeDef",
     "BatchPutDocumentResponseTypeDef",
     "ConfluenceAttachmentConfigurationTypeDef",
     "ConfluenceBlogConfigurationTypeDef",
     "SharePointConfigurationTypeDef",
     "ConfluencePageConfigurationTypeDef",
     "ConfluenceSpaceConfigurationTypeDef",
     "SpellCorrectedQueryTypeDef",
     "HierarchicalPrincipalTypeDef",
     "CreateFaqRequestRequestTypeDef",
     "CreateQuerySuggestionsBlockListRequestRequestTypeDef",
     "CreateThesaurusRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "CreateFeaturedResultsSetRequestRequestTypeDef",
+    "FeaturedResultsSetTypeDef",
+    "UpdateFeaturedResultsSetRequestRequestTypeDef",
     "UserContextTypeDef",
     "ListDataSourcesResponseTypeDef",
     "DataSourceSyncJobTypeDef",
     "ExperiencesSummaryTypeDef",
+    "DescribeFeaturedResultsSetResponseTypeDef",
     "DescribePrincipalMappingResponseTypeDef",
     "DocumentAttributeConditionTypeDef",
     "DocumentAttributeTargetTypeDef",
     "DocumentAttributeTypeDef",
     "DocumentAttributeValueCountPairTypeDef",
     "DocumentRelevanceConfigurationTypeDef",
     "DocumentMetadataConfigurationTypeDef",
     "S3DataSourceConfigurationTypeDef",
     "ExperienceEntitiesSummaryTypeDef",
     "ExperienceConfigurationTypeDef",
     "ListFaqsResponseTypeDef",
+    "ListFeaturedResultsSetsResponseTypeDef",
     "GetSnapshotsResponseTypeDef",
     "ListDataSourceSyncJobsRequestRequestTypeDef",
     "GroupMembersTypeDef",
     "ListGroupsOlderThanOrderingIdResponseTypeDef",
     "TextWithHighlightsTypeDef",
     "ListIndicesResponseTypeDef",
     "IndexStatisticsTypeDef",
@@ -279,45 +296,56 @@
     "SuggestionTextWithHighlightsTypeDef",
     "TableRowTypeDef",
     "DatabaseConfigurationTypeDef",
     "SalesforceKnowledgeArticleConfigurationTypeDef",
     "ServiceNowConfigurationTypeDef",
     "GitHubConfigurationTypeDef",
     "OneDriveConfigurationTypeDef",
+    "DescribeQuerySuggestionsConfigResponseTypeDef",
+    "UpdateQuerySuggestionsConfigRequestRequestTypeDef",
     "ConfluenceConfigurationTypeDef",
     "CreateAccessControlConfigurationRequestRequestTypeDef",
     "DescribeAccessControlConfigurationResponseTypeDef",
     "UpdateAccessControlConfigurationRequestRequestTypeDef",
+    "CreateFeaturedResultsSetResponseTypeDef",
+    "UpdateFeaturedResultsSetResponseTypeDef",
+    "AttributeSuggestionsGetConfigTypeDef",
     "ListDataSourceSyncJobsResponseTypeDef",
     "ListExperiencesResponseTypeDef",
     "HookConfigurationTypeDef",
     "InlineCustomDocumentEnrichmentConfigurationTypeDef",
     "AttributeFilterTypeDef",
     "DocumentInfoTypeDef",
     "DocumentTypeDef",
+    "RetrieveResultItemTypeDef",
+    "SourceDocumentTypeDef",
     "QueryRequestRequestTypeDef",
+    "RetrieveRequestRequestTypeDef",
     "ListExperienceEntitiesResponseTypeDef",
     "CreateExperienceRequestRequestTypeDef",
     "DescribeExperienceResponseTypeDef",
     "UpdateExperienceRequestRequestTypeDef",
     "PutPrincipalMappingRequestRequestTypeDef",
     "AdditionalResultAttributeValueTypeDef",
     "CreateIndexRequestRequestTypeDef",
     "DescribeIndexResponseTypeDef",
     "UpdateIndexRequestRequestTypeDef",
     "WebCrawlerConfigurationTypeDef",
     "SuggestionValueTypeDef",
     "TableExcerptTypeDef",
     "SalesforceConfigurationTypeDef",
+    "GetQuerySuggestionsRequestRequestTypeDef",
     "CustomDocumentEnrichmentConfigurationTypeDef",
     "BatchGetDocumentStatusRequestRequestTypeDef",
+    "RetrieveResultTypeDef",
     "AdditionalResultAttributeTypeDef",
     "SuggestionTypeDef",
     "DataSourceConfigurationTypeDef",
     "BatchPutDocumentRequestRequestTypeDef",
+    "FeaturedResultsItemTypeDef",
     "QueryResultItemTypeDef",
     "GetQuerySuggestionsResponseTypeDef",
     "CreateDataSourceRequestRequestTypeDef",
     "DescribeDataSourceResponseTypeDef",
     "UpdateDataSourceRequestRequestTypeDef",
     "QueryResultTypeDef",
 )
@@ -393,33 +421,31 @@
     {
         "EntityId": str,
         "ErrorMessage": str,
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
 EntityPersonaConfigurationTypeDef = TypedDict(
     "EntityPersonaConfigurationTypeDef",
     {
         "EntityId": str,
         "Persona": PersonaType,
     },
 )
 
+SuggestableConfigTypeDef = TypedDict(
+    "SuggestableConfigTypeDef",
+    {
+        "AttributeName": str,
+        "Suggestable": bool,
+    },
+    total=False,
+)
+
 BasicAuthenticationConfigurationTypeDef = TypedDict(
     "BasicAuthenticationConfigurationTypeDef",
     {
         "Host": str,
         "Port": int,
         "Credentials": str,
     },
@@ -450,14 +476,31 @@
         "Id": str,
         "ErrorCode": ErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+BatchDeleteFeaturedResultsSetErrorTypeDef = TypedDict(
+    "BatchDeleteFeaturedResultsSetErrorTypeDef",
+    {
+        "Id": str,
+        "ErrorCode": ErrorCodeType,
+        "ErrorMessage": str,
+    },
+)
+
+BatchDeleteFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "BatchDeleteFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetIds": Sequence[str],
+    },
+)
+
 BatchGetDocumentStatusResponseErrorTypeDef = TypedDict(
     "BatchGetDocumentStatusResponseErrorTypeDef",
     {
         "DocumentId": str,
         "ErrorCode": ErrorCodeType,
         "ErrorMessage": str,
     },
@@ -615,22 +658,62 @@
     },
     total=False,
 )
 
 class PrincipalTypeDef(_RequiredPrincipalTypeDef, _OptionalPrincipalTypeDef):
     pass
 
+CreateAccessControlConfigurationResponseTypeDef = TypedDict(
+    "CreateAccessControlConfigurationResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateDataSourceResponseTypeDef = TypedDict(
+    "CreateDataSourceResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateExperienceResponseTypeDef = TypedDict(
+    "CreateExperienceResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFaqResponseTypeDef = TypedDict(
+    "CreateFaqResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+FeaturedDocumentTypeDef = TypedDict(
+    "FeaturedDocumentTypeDef",
+    {
+        "Id": str,
+    },
+    total=False,
+)
+
 ServerSideEncryptionConfigurationTypeDef = TypedDict(
     "ServerSideEncryptionConfigurationTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
@@ -638,14 +721,38 @@
 UserGroupResolutionConfigurationTypeDef = TypedDict(
     "UserGroupResolutionConfigurationTypeDef",
     {
         "UserGroupResolutionMode": UserGroupResolutionModeType,
     },
 )
 
+CreateIndexResponseTypeDef = TypedDict(
+    "CreateIndexResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateQuerySuggestionsBlockListResponseTypeDef = TypedDict(
+    "CreateQuerySuggestionsBlockListResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateThesaurusResponseTypeDef = TypedDict(
+    "CreateThesaurusResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TemplateConfigurationTypeDef = TypedDict(
     "TemplateConfigurationTypeDef",
     {
         "Template": Mapping[str, Any],
     },
     total=False,
 )
@@ -806,14 +913,40 @@
     "DescribeFaqRequestRequestTypeDef",
     {
         "Id": str,
         "IndexId": str,
     },
 )
 
+DescribeFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "DescribeFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetId": str,
+    },
+)
+
+FeaturedDocumentMissingTypeDef = TypedDict(
+    "FeaturedDocumentMissingTypeDef",
+    {
+        "Id": str,
+    },
+    total=False,
+)
+
+FeaturedDocumentWithMetadataTypeDef = TypedDict(
+    "FeaturedDocumentWithMetadataTypeDef",
+    {
+        "Id": str,
+        "Title": str,
+        "URI": str,
+    },
+    total=False,
+)
+
 DescribeIndexRequestRequestTypeDef = TypedDict(
     "DescribeIndexRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -920,14 +1053,21 @@
     "DocumentsMetadataConfigurationTypeDef",
     {
         "S3Prefix": str,
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
 EntityDisplayDataTypeDef = TypedDict(
     "EntityDisplayDataTypeDef",
     {
         "UserName": str,
         "GroupName": str,
         "IdentifiedUserName": str,
         "FirstName": str,
@@ -981,35 +1121,26 @@
         "UpdatedAt": datetime,
         "FileFormat": FaqFileFormatType,
         "LanguageCode": str,
     },
     total=False,
 )
 
-_RequiredGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
-    "_RequiredGetQuerySuggestionsRequestRequestTypeDef",
-    {
-        "IndexId": str,
-        "QueryText": str,
-    },
-)
-_OptionalGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
-    "_OptionalGetQuerySuggestionsRequestRequestTypeDef",
+FeaturedResultsSetSummaryTypeDef = TypedDict(
+    "FeaturedResultsSetSummaryTypeDef",
     {
-        "MaxSuggestionsCount": int,
+        "FeaturedResultsSetId": str,
+        "FeaturedResultsSetName": str,
+        "Status": FeaturedResultsSetStatusType,
+        "LastUpdatedTimestamp": int,
+        "CreationTimestamp": int,
     },
     total=False,
 )
 
-class GetQuerySuggestionsRequestRequestTypeDef(
-    _RequiredGetQuerySuggestionsRequestRequestTypeDef,
-    _OptionalGetQuerySuggestionsRequestRequestTypeDef,
-):
-    pass
-
 _RequiredGetSnapshotsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSnapshotsRequestRequestTypeDef",
     {
         "IndexId": str,
         "Interval": IntervalType,
         "MetricType": MetricTypeType,
     },
@@ -1305,14 +1436,35 @@
 )
 
 class ListFaqsRequestRequestTypeDef(
     _RequiredListFaqsRequestRequestTypeDef, _OptionalListFaqsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListFeaturedResultsSetsRequestRequestTypeDef = TypedDict(
+    "_RequiredListFeaturedResultsSetsRequestRequestTypeDef",
+    {
+        "IndexId": str,
+    },
+)
+_OptionalListFeaturedResultsSetsRequestRequestTypeDef = TypedDict(
+    "_OptionalListFeaturedResultsSetsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class ListFeaturedResultsSetsRequestRequestTypeDef(
+    _RequiredListFeaturedResultsSetsRequestRequestTypeDef,
+    _OptionalListFeaturedResultsSetsRequestRequestTypeDef,
+):
+    pass
+
 _RequiredListGroupsOlderThanOrderingIdRequestRequestTypeDef = TypedDict(
     "_RequiredListGroupsOlderThanOrderingIdRequestRequestTypeDef",
     {
         "IndexId": str,
         "OrderingId": int,
     },
 )
@@ -1450,14 +1602,25 @@
     "RelevanceFeedbackTypeDef",
     {
         "ResultId": str,
         "RelevanceValue": RelevanceTypeType,
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
 _RequiredSeedUrlConfigurationTypeDef = TypedDict(
     "_RequiredSeedUrlConfigurationTypeDef",
     {
         "SeedUrls": Sequence[str],
     },
 )
 _OptionalSeedUrlConfigurationTypeDef = TypedDict(
@@ -1484,14 +1647,22 @@
     "StartDataSourceSyncJobRequestRequestTypeDef",
     {
         "Id": str,
         "IndexId": str,
     },
 )
 
+StartDataSourceSyncJobResponseTypeDef = TypedDict(
+    "StartDataSourceSyncJobResponseTypeDef",
+    {
+        "ExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopDataSourceSyncJobRequestRequestTypeDef = TypedDict(
     "StopDataSourceSyncJobRequestRequestTypeDef",
     {
         "Id": str,
         "IndexId": str,
     },
 )
@@ -1520,38 +1691,23 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
-_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef",
-    {
-        "IndexId": str,
-    },
-)
-_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef",
+ListAccessControlConfigurationsResponseTypeDef = TypedDict(
+    "ListAccessControlConfigurationsResponseTypeDef",
     {
-        "Mode": ModeType,
-        "QueryLogLookBackWindowInDays": int,
-        "IncludeQueriesWithoutUserInformation": bool,
-        "MinimumNumberOfQueryingUsers": int,
-        "MinimumQueryCount": int,
+        "NextToken": str,
+        "AccessControlConfigurations": List[AccessControlConfigurationSummaryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class UpdateQuerySuggestionsConfigRequestRequestTypeDef(
-    _RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef,
-    _OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef,
-):
-    pass
-
 _RequiredColumnConfigurationTypeDef = TypedDict(
     "_RequiredColumnConfigurationTypeDef",
     {
         "DocumentIdColumnName": str,
         "DocumentDataColumnName": str,
         "ChangeDetectingColumns": Sequence[str],
     },
@@ -1930,14 +2086,72 @@
 )
 
 class AlfrescoConfigurationTypeDef(
     _RequiredAlfrescoConfigurationTypeDef, _OptionalAlfrescoConfigurationTypeDef
 ):
     pass
 
+DescribeFaqResponseTypeDef = TypedDict(
+    "DescribeFaqResponseTypeDef",
+    {
+        "Id": str,
+        "IndexId": str,
+        "Name": str,
+        "Description": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "S3Path": S3PathTypeDef,
+        "Status": FaqStatusType,
+        "RoleArn": str,
+        "ErrorMessage": str,
+        "FileFormat": FaqFileFormatType,
+        "LanguageCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeQuerySuggestionsBlockListResponseTypeDef = TypedDict(
+    "DescribeQuerySuggestionsBlockListResponseTypeDef",
+    {
+        "IndexId": str,
+        "Id": str,
+        "Name": str,
+        "Description": str,
+        "Status": QuerySuggestionsBlockListStatusType,
+        "ErrorMessage": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "SourceS3Path": S3PathTypeDef,
+        "ItemCount": int,
+        "FileSizeBytes": int,
+        "RoleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeThesaurusResponseTypeDef = TypedDict(
+    "DescribeThesaurusResponseTypeDef",
+    {
+        "Id": str,
+        "IndexId": str,
+        "Name": str,
+        "Description": str,
+        "Status": ThesaurusStatusType,
+        "ErrorMessage": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "RoleArn": str,
+        "SourceS3Path": S3PathTypeDef,
+        "FileSizeBytes": int,
+        "TermCount": int,
+        "SynonymRuleCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OnPremiseConfigurationTypeDef = TypedDict(
     "OnPremiseConfigurationTypeDef",
     {
         "HostUrl": str,
         "OrganizationName": str,
         "SslCertificateS3Path": S3PathTypeDef,
     },
@@ -2017,203 +2231,67 @@
     },
 )
 
 AssociateEntitiesToExperienceResponseTypeDef = TypedDict(
     "AssociateEntitiesToExperienceResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AssociatePersonasToEntitiesResponseTypeDef = TypedDict(
     "AssociatePersonasToEntitiesResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAccessControlConfigurationResponseTypeDef = TypedDict(
-    "CreateAccessControlConfigurationResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataSourceResponseTypeDef = TypedDict(
-    "CreateDataSourceResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateExperienceResponseTypeDef = TypedDict(
-    "CreateExperienceResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFaqResponseTypeDef = TypedDict(
-    "CreateFaqResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateIndexResponseTypeDef = TypedDict(
-    "CreateIndexResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateQuerySuggestionsBlockListResponseTypeDef = TypedDict(
-    "CreateQuerySuggestionsBlockListResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateThesaurusResponseTypeDef = TypedDict(
-    "CreateThesaurusResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFaqResponseTypeDef = TypedDict(
-    "DescribeFaqResponseTypeDef",
-    {
-        "Id": str,
-        "IndexId": str,
-        "Name": str,
-        "Description": str,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "S3Path": S3PathTypeDef,
-        "Status": FaqStatusType,
-        "RoleArn": str,
-        "ErrorMessage": str,
-        "FileFormat": FaqFileFormatType,
-        "LanguageCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeQuerySuggestionsBlockListResponseTypeDef = TypedDict(
-    "DescribeQuerySuggestionsBlockListResponseTypeDef",
-    {
-        "IndexId": str,
-        "Id": str,
-        "Name": str,
-        "Description": str,
-        "Status": QuerySuggestionsBlockListStatusType,
-        "ErrorMessage": str,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "SourceS3Path": S3PathTypeDef,
-        "ItemCount": int,
-        "FileSizeBytes": int,
-        "RoleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeQuerySuggestionsConfigResponseTypeDef = TypedDict(
-    "DescribeQuerySuggestionsConfigResponseTypeDef",
-    {
-        "Mode": ModeType,
-        "Status": QuerySuggestionsStatusType,
-        "QueryLogLookBackWindowInDays": int,
-        "IncludeQueriesWithoutUserInformation": bool,
-        "MinimumNumberOfQueryingUsers": int,
-        "MinimumQueryCount": int,
-        "LastSuggestionsBuildTime": datetime,
-        "LastClearTime": datetime,
-        "TotalSuggestionsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeThesaurusResponseTypeDef = TypedDict(
-    "DescribeThesaurusResponseTypeDef",
-    {
-        "Id": str,
-        "IndexId": str,
-        "Name": str,
-        "Description": str,
-        "Status": ThesaurusStatusType,
-        "ErrorMessage": str,
-        "CreatedAt": datetime,
-        "UpdatedAt": datetime,
-        "RoleArn": str,
-        "SourceS3Path": S3PathTypeDef,
-        "FileSizeBytes": int,
-        "TermCount": int,
-        "SynonymRuleCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociateEntitiesFromExperienceResponseTypeDef = TypedDict(
     "DisassociateEntitiesFromExperienceResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisassociatePersonasFromEntitiesResponseTypeDef = TypedDict(
     "DisassociatePersonasFromEntitiesResponseTypeDef",
     {
         "FailedEntityList": List[FailedEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccessControlConfigurationsResponseTypeDef = TypedDict(
-    "ListAccessControlConfigurationsResponseTypeDef",
+AssociatePersonasToEntitiesRequestRequestTypeDef = TypedDict(
+    "AssociatePersonasToEntitiesRequestRequestTypeDef",
     {
-        "NextToken": str,
-        "AccessControlConfigurations": List[AccessControlConfigurationSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Id": str,
+        "IndexId": str,
+        "Personas": Sequence[EntityPersonaConfigurationTypeDef],
     },
 )
 
-StartDataSourceSyncJobResponseTypeDef = TypedDict(
-    "StartDataSourceSyncJobResponseTypeDef",
+AttributeSuggestionsDescribeConfigTypeDef = TypedDict(
+    "AttributeSuggestionsDescribeConfigTypeDef",
     {
-        "ExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SuggestableConfigList": List[SuggestableConfigTypeDef],
+        "AttributeSuggestionsMode": AttributeSuggestionsModeType,
     },
+    total=False,
 )
 
-AssociatePersonasToEntitiesRequestRequestTypeDef = TypedDict(
-    "AssociatePersonasToEntitiesRequestRequestTypeDef",
+AttributeSuggestionsUpdateConfigTypeDef = TypedDict(
+    "AttributeSuggestionsUpdateConfigTypeDef",
     {
-        "Id": str,
-        "IndexId": str,
-        "Personas": Sequence[EntityPersonaConfigurationTypeDef],
+        "SuggestableConfigList": Sequence[SuggestableConfigTypeDef],
+        "AttributeSuggestionsMode": AttributeSuggestionsModeType,
     },
+    total=False,
 )
 
 AuthenticationConfigurationTypeDef = TypedDict(
     "AuthenticationConfigurationTypeDef",
     {
         "BasicAuthentication": Sequence[BasicAuthenticationConfigurationTypeDef],
     },
@@ -2241,32 +2319,40 @@
 ):
     pass
 
 BatchDeleteDocumentResponseTypeDef = TypedDict(
     "BatchDeleteDocumentResponseTypeDef",
     {
         "FailedDocuments": List[BatchDeleteDocumentResponseFailedDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchDeleteFeaturedResultsSetResponseTypeDef = TypedDict(
+    "BatchDeleteFeaturedResultsSetResponseTypeDef",
+    {
+        "Errors": List[BatchDeleteFeaturedResultsSetErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDocumentStatusResponseTypeDef = TypedDict(
     "BatchGetDocumentStatusResponseTypeDef",
     {
         "Errors": List[BatchGetDocumentStatusResponseErrorTypeDef],
         "DocumentStatusList": List[StatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutDocumentResponseTypeDef = TypedDict(
     "BatchPutDocumentResponseTypeDef",
     {
         "FailedDocuments": List[BatchPutDocumentResponseFailedDocumentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfluenceAttachmentConfigurationTypeDef = TypedDict(
     "ConfluenceAttachmentConfigurationTypeDef",
     {
         "CrawlAttachments": bool,
@@ -2425,26 +2511,92 @@
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
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+_RequiredCreateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetName": str,
+    },
+)
+_OptionalCreateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "Description": str,
+        "ClientToken": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": Sequence[str],
+        "FeaturedDocuments": Sequence[FeaturedDocumentTypeDef],
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreateFeaturedResultsSetRequestRequestTypeDef(
+    _RequiredCreateFeaturedResultsSetRequestRequestTypeDef,
+    _OptionalCreateFeaturedResultsSetRequestRequestTypeDef,
+):
+    pass
+
+FeaturedResultsSetTypeDef = TypedDict(
+    "FeaturedResultsSetTypeDef",
+    {
+        "FeaturedResultsSetId": str,
+        "FeaturedResultsSetName": str,
+        "Description": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": List[str],
+        "FeaturedDocuments": List[FeaturedDocumentTypeDef],
+        "LastUpdatedTimestamp": int,
+        "CreationTimestamp": int,
+    },
+    total=False,
+)
+
+_RequiredUpdateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "FeaturedResultsSetId": str,
+    },
+)
+_OptionalUpdateFeaturedResultsSetRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFeaturedResultsSetRequestRequestTypeDef",
+    {
+        "FeaturedResultsSetName": str,
+        "Description": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": Sequence[str],
+        "FeaturedDocuments": Sequence[FeaturedDocumentTypeDef],
+    },
+    total=False,
+)
+
+class UpdateFeaturedResultsSetRequestRequestTypeDef(
+    _RequiredUpdateFeaturedResultsSetRequestRequestTypeDef,
+    _OptionalUpdateFeaturedResultsSetRequestRequestTypeDef,
+):
+    pass
+
 UserContextTypeDef = TypedDict(
     "UserContextTypeDef",
     {
         "Token": str,
         "UserId": str,
         "Groups": Sequence[str],
         "DataSourceGroups": Sequence[DataSourceGroupTypeDef],
@@ -2453,15 +2605,15 @@
 )
 
 ListDataSourcesResponseTypeDef = TypedDict(
     "ListDataSourcesResponseTypeDef",
     {
         "SummaryItems": List[DataSourceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSourceSyncJobTypeDef = TypedDict(
     "DataSourceSyncJobTypeDef",
     {
         "ExecutionId": str,
@@ -2484,22 +2636,38 @@
         "CreatedAt": datetime,
         "Status": ExperienceStatusType,
         "Endpoints": List[ExperienceEndpointTypeDef],
     },
     total=False,
 )
 
+DescribeFeaturedResultsSetResponseTypeDef = TypedDict(
+    "DescribeFeaturedResultsSetResponseTypeDef",
+    {
+        "FeaturedResultsSetId": str,
+        "FeaturedResultsSetName": str,
+        "Description": str,
+        "Status": FeaturedResultsSetStatusType,
+        "QueryTexts": List[str],
+        "FeaturedDocumentsWithMetadata": List[FeaturedDocumentWithMetadataTypeDef],
+        "FeaturedDocumentsMissing": List[FeaturedDocumentMissingTypeDef],
+        "LastUpdatedTimestamp": int,
+        "CreationTimestamp": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribePrincipalMappingResponseTypeDef = TypedDict(
     "DescribePrincipalMappingResponseTypeDef",
     {
         "IndexId": str,
         "DataSourceId": str,
         "GroupId": str,
         "GroupOrderingIdSummaries": List[GroupOrderingIdSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDocumentAttributeConditionTypeDef = TypedDict(
     "_RequiredDocumentAttributeConditionTypeDef",
     {
         "ConditionDocumentAttributeKey": str,
@@ -2619,26 +2787,35 @@
 )
 
 ListFaqsResponseTypeDef = TypedDict(
     "ListFaqsResponseTypeDef",
     {
         "NextToken": str,
         "FaqSummaryItems": List[FaqSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFeaturedResultsSetsResponseTypeDef = TypedDict(
+    "ListFeaturedResultsSetsResponseTypeDef",
+    {
+        "FeaturedResultsSetSummaryItems": List[FeaturedResultsSetSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSnapshotsResponseTypeDef = TypedDict(
     "GetSnapshotsResponseTypeDef",
     {
         "SnapShotTimeFilter": TimeRangeTypeDef,
         "SnapshotsDataHeader": List[str],
         "SnapshotsData": List[List[str]],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListDataSourceSyncJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSourceSyncJobsRequestRequestTypeDef",
     {
         "Id": str,
@@ -2673,15 +2850,15 @@
 )
 
 ListGroupsOlderThanOrderingIdResponseTypeDef = TypedDict(
     "ListGroupsOlderThanOrderingIdResponseTypeDef",
     {
         "GroupsSummaries": List[GroupSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TextWithHighlightsTypeDef = TypedDict(
     "TextWithHighlightsTypeDef",
     {
         "Text": str,
@@ -2691,15 +2868,15 @@
 )
 
 ListIndicesResponseTypeDef = TypedDict(
     "ListIndicesResponseTypeDef",
     {
         "IndexConfigurationSummaryItems": List[IndexConfigurationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IndexStatisticsTypeDef = TypedDict(
     "IndexStatisticsTypeDef",
     {
         "FaqStatistics": FaqStatisticsTypeDef,
@@ -2717,33 +2894,33 @@
 )
 
 ListEntityPersonasResponseTypeDef = TypedDict(
     "ListEntityPersonasResponseTypeDef",
     {
         "SummaryItems": List[PersonasSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQuerySuggestionsBlockListsResponseTypeDef = TypedDict(
     "ListQuerySuggestionsBlockListsResponseTypeDef",
     {
         "BlockListSummaryItems": List[QuerySuggestionsBlockListSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListThesauriResponseTypeDef = TypedDict(
     "ListThesauriResponseTypeDef",
     {
         "NextToken": str,
         "ThesaurusSummaryItems": List[ThesaurusSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSubmitFeedbackRequestRequestTypeDef = TypedDict(
     "_RequiredSubmitFeedbackRequestRequestTypeDef",
     {
         "IndexId": str,
@@ -2934,14 +3111,56 @@
 )
 
 class OneDriveConfigurationTypeDef(
     _RequiredOneDriveConfigurationTypeDef, _OptionalOneDriveConfigurationTypeDef
 ):
     pass
 
+DescribeQuerySuggestionsConfigResponseTypeDef = TypedDict(
+    "DescribeQuerySuggestionsConfigResponseTypeDef",
+    {
+        "Mode": ModeType,
+        "Status": QuerySuggestionsStatusType,
+        "QueryLogLookBackWindowInDays": int,
+        "IncludeQueriesWithoutUserInformation": bool,
+        "MinimumNumberOfQueryingUsers": int,
+        "MinimumQueryCount": int,
+        "LastSuggestionsBuildTime": datetime,
+        "LastClearTime": datetime,
+        "TotalSuggestionsCount": int,
+        "AttributeSuggestionsConfig": AttributeSuggestionsDescribeConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef",
+    {
+        "IndexId": str,
+    },
+)
+_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef",
+    {
+        "Mode": ModeType,
+        "QueryLogLookBackWindowInDays": int,
+        "IncludeQueriesWithoutUserInformation": bool,
+        "MinimumNumberOfQueryingUsers": int,
+        "MinimumQueryCount": int,
+        "AttributeSuggestionsConfig": AttributeSuggestionsUpdateConfigTypeDef,
+    },
+    total=False,
+)
+
+class UpdateQuerySuggestionsConfigRequestRequestTypeDef(
+    _RequiredUpdateQuerySuggestionsConfigRequestRequestTypeDef,
+    _OptionalUpdateQuerySuggestionsConfigRequestRequestTypeDef,
+):
+    pass
+
 _RequiredConfluenceConfigurationTypeDef = TypedDict(
     "_RequiredConfluenceConfigurationTypeDef",
     {
         "ServerUrl": str,
         "SecretArn": str,
         "Version": ConfluenceVersionType,
     },
@@ -2995,15 +3214,15 @@
     "DescribeAccessControlConfigurationResponseTypeDef",
     {
         "Name": str,
         "Description": str,
         "ErrorMessage": str,
         "AccessControlList": List[PrincipalTypeDef],
         "HierarchicalAccessControlList": List[HierarchicalPrincipalTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateAccessControlConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAccessControlConfigurationRequestRequestTypeDef",
     {
         "IndexId": str,
@@ -3023,29 +3242,56 @@
 
 class UpdateAccessControlConfigurationRequestRequestTypeDef(
     _RequiredUpdateAccessControlConfigurationRequestRequestTypeDef,
     _OptionalUpdateAccessControlConfigurationRequestRequestTypeDef,
 ):
     pass
 
+CreateFeaturedResultsSetResponseTypeDef = TypedDict(
+    "CreateFeaturedResultsSetResponseTypeDef",
+    {
+        "FeaturedResultsSet": FeaturedResultsSetTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFeaturedResultsSetResponseTypeDef = TypedDict(
+    "UpdateFeaturedResultsSetResponseTypeDef",
+    {
+        "FeaturedResultsSet": FeaturedResultsSetTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AttributeSuggestionsGetConfigTypeDef = TypedDict(
+    "AttributeSuggestionsGetConfigTypeDef",
+    {
+        "SuggestionAttributes": Sequence[str],
+        "AdditionalResponseAttributes": Sequence[str],
+        "AttributeFilter": "AttributeFilterTypeDef",
+        "UserContext": UserContextTypeDef,
+    },
+    total=False,
+)
+
 ListDataSourceSyncJobsResponseTypeDef = TypedDict(
     "ListDataSourceSyncJobsResponseTypeDef",
     {
         "History": List[DataSourceSyncJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExperiencesResponseTypeDef = TypedDict(
     "ListExperiencesResponseTypeDef",
     {
         "SummaryItems": List[ExperiencesSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHookConfigurationTypeDef = TypedDict(
     "_RequiredHookConfigurationTypeDef",
     {
         "LambdaArn": str,
@@ -3129,14 +3375,37 @@
     },
     total=False,
 )
 
 class DocumentTypeDef(_RequiredDocumentTypeDef, _OptionalDocumentTypeDef):
     pass
 
+RetrieveResultItemTypeDef = TypedDict(
+    "RetrieveResultItemTypeDef",
+    {
+        "Id": str,
+        "DocumentId": str,
+        "DocumentTitle": str,
+        "Content": str,
+        "DocumentURI": str,
+        "DocumentAttributes": List[DocumentAttributeTypeDef],
+    },
+    total=False,
+)
+
+SourceDocumentTypeDef = TypedDict(
+    "SourceDocumentTypeDef",
+    {
+        "DocumentId": str,
+        "SuggestionAttributes": List[str],
+        "AdditionalAttributes": List[DocumentAttributeTypeDef],
+    },
+    total=False,
+)
+
 _RequiredQueryRequestRequestTypeDef = TypedDict(
     "_RequiredQueryRequestRequestTypeDef",
     {
         "IndexId": str,
     },
 )
 _OptionalQueryRequestRequestTypeDef = TypedDict(
@@ -3159,20 +3428,45 @@
 )
 
 class QueryRequestRequestTypeDef(
     _RequiredQueryRequestRequestTypeDef, _OptionalQueryRequestRequestTypeDef
 ):
     pass
 
+_RequiredRetrieveRequestRequestTypeDef = TypedDict(
+    "_RequiredRetrieveRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "QueryText": str,
+    },
+)
+_OptionalRetrieveRequestRequestTypeDef = TypedDict(
+    "_OptionalRetrieveRequestRequestTypeDef",
+    {
+        "AttributeFilter": "AttributeFilterTypeDef",
+        "RequestedDocumentAttributes": Sequence[str],
+        "DocumentRelevanceOverrideConfigurations": Sequence[DocumentRelevanceConfigurationTypeDef],
+        "PageNumber": int,
+        "PageSize": int,
+        "UserContext": UserContextTypeDef,
+    },
+    total=False,
+)
+
+class RetrieveRequestRequestTypeDef(
+    _RequiredRetrieveRequestRequestTypeDef, _OptionalRetrieveRequestRequestTypeDef
+):
+    pass
+
 ListExperienceEntitiesResponseTypeDef = TypedDict(
     "ListExperienceEntitiesResponseTypeDef",
     {
         "SummaryItems": List[ExperienceEntitiesSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateExperienceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExperienceRequestRequestTypeDef",
     {
         "Name": str,
@@ -3205,15 +3499,15 @@
         "Configuration": ExperienceConfigurationTypeDef,
         "CreatedAt": datetime,
         "UpdatedAt": datetime,
         "Description": str,
         "Status": ExperienceStatusType,
         "RoleArn": str,
         "ErrorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateExperienceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateExperienceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3310,15 +3604,15 @@
         "DocumentMetadataConfigurations": List[DocumentMetadataConfigurationTypeDef],
         "IndexStatistics": IndexStatisticsTypeDef,
         "ErrorMessage": str,
         "CapacityUnits": CapacityUnitsConfigurationTypeDef,
         "UserTokenConfigurations": List[UserTokenConfigurationTypeDef],
         "UserContextPolicy": UserContextPolicyType,
         "UserGroupResolutionConfiguration": UserGroupResolutionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateIndexRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIndexRequestRequestTypeDef",
     {
         "Id": str,
@@ -3411,14 +3705,37 @@
 )
 
 class SalesforceConfigurationTypeDef(
     _RequiredSalesforceConfigurationTypeDef, _OptionalSalesforceConfigurationTypeDef
 ):
     pass
 
+_RequiredGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetQuerySuggestionsRequestRequestTypeDef",
+    {
+        "IndexId": str,
+        "QueryText": str,
+    },
+)
+_OptionalGetQuerySuggestionsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetQuerySuggestionsRequestRequestTypeDef",
+    {
+        "MaxSuggestionsCount": int,
+        "SuggestionTypes": Sequence[SuggestionTypeType],
+        "AttributeSuggestionsConfig": AttributeSuggestionsGetConfigTypeDef,
+    },
+    total=False,
+)
+
+class GetQuerySuggestionsRequestRequestTypeDef(
+    _RequiredGetQuerySuggestionsRequestRequestTypeDef,
+    _OptionalGetQuerySuggestionsRequestRequestTypeDef,
+):
+    pass
+
 CustomDocumentEnrichmentConfigurationTypeDef = TypedDict(
     "CustomDocumentEnrichmentConfigurationTypeDef",
     {
         "InlineConfigurations": Sequence[InlineCustomDocumentEnrichmentConfigurationTypeDef],
         "PreExtractionHookConfiguration": HookConfigurationTypeDef,
         "PostExtractionHookConfiguration": HookConfigurationTypeDef,
         "RoleArn": str,
@@ -3430,28 +3747,38 @@
     "BatchGetDocumentStatusRequestRequestTypeDef",
     {
         "IndexId": str,
         "DocumentInfoList": Sequence[DocumentInfoTypeDef],
     },
 )
 
+RetrieveResultTypeDef = TypedDict(
+    "RetrieveResultTypeDef",
+    {
+        "QueryId": str,
+        "ResultItems": List[RetrieveResultItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AdditionalResultAttributeTypeDef = TypedDict(
     "AdditionalResultAttributeTypeDef",
     {
         "Key": str,
         "ValueType": Literal["TEXT_WITH_HIGHLIGHTS_VALUE"],
         "Value": AdditionalResultAttributeValueTypeDef,
     },
 )
 
 SuggestionTypeDef = TypedDict(
     "SuggestionTypeDef",
     {
         "Id": str,
         "Value": SuggestionValueTypeDef,
+        "SourceDocuments": List[SourceDocumentTypeDef],
     },
     total=False,
 )
 
 DataSourceConfigurationTypeDef = TypedDict(
     "DataSourceConfigurationTypeDef",
     {
@@ -3494,14 +3821,30 @@
 )
 
 class BatchPutDocumentRequestRequestTypeDef(
     _RequiredBatchPutDocumentRequestRequestTypeDef, _OptionalBatchPutDocumentRequestRequestTypeDef
 ):
     pass
 
+FeaturedResultsItemTypeDef = TypedDict(
+    "FeaturedResultsItemTypeDef",
+    {
+        "Id": str,
+        "Type": QueryResultTypeType,
+        "AdditionalAttributes": List[AdditionalResultAttributeTypeDef],
+        "DocumentId": str,
+        "DocumentTitle": TextWithHighlightsTypeDef,
+        "DocumentExcerpt": TextWithHighlightsTypeDef,
+        "DocumentURI": str,
+        "DocumentAttributes": List[DocumentAttributeTypeDef],
+        "FeedbackToken": str,
+    },
+    total=False,
+)
+
 QueryResultItemTypeDef = TypedDict(
     "QueryResultItemTypeDef",
     {
         "Id": str,
         "Type": QueryResultTypeType,
         "Format": QueryResultFormatType,
         "AdditionalAttributes": List[AdditionalResultAttributeTypeDef],
@@ -3518,15 +3861,15 @@
 )
 
 GetQuerySuggestionsResponseTypeDef = TypedDict(
     "GetQuerySuggestionsResponseTypeDef",
     {
         "QuerySuggestionsId": str,
         "Suggestions": List[SuggestionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceRequestRequestTypeDef",
     {
         "Name": str,
@@ -3569,15 +3912,15 @@
         "Description": str,
         "Status": DataSourceStatusType,
         "Schedule": str,
         "RoleArn": str,
         "ErrorMessage": str,
         "LanguageCode": str,
         "CustomDocumentEnrichmentConfiguration": CustomDocumentEnrichmentConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDataSourceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDataSourceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3609,10 +3952,11 @@
     {
         "QueryId": str,
         "ResultItems": List[QueryResultItemTypeDef],
         "FacetResults": List["FacetResultTypeDef"],
         "TotalNumberOfResults": int,
         "Warnings": List[WarningTypeDef],
         "SpellCorrectedQueries": List[SpellCorrectedQueryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "FeaturedResultsItems": List[FeaturedResultsItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/PKG-INFO` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kendra
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.kendra 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.kendra 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kendra"></a>
 
 # types-aiobotocore-kendra
 
 [![PyPI - types-aiobotocore-kendra](https://img.shields.io/pypi/v/types-aiobotocore-kendra.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kendra.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kendra)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kendra?color=blue)](https://pypistats.org/packages/types-aiobotocore-kendra)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.kendra 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra)
+[aiobotocore.kendra 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kendra.html#kendra)
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
 [types-aiobotocore-kendra docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kendra/).
 
 See how it helps to find and fix potential bugs:
 
@@ -270,14 +270,15 @@
 `types_aiobotocore_kendra.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_kendra.literals import (
     AdditionalResultAttributeValueTypeType,
     AlfrescoEntityType,
+    AttributeSuggestionsModeType,
     ConditionOperatorType,
     ConfluenceAttachmentFieldNameType,
     ConfluenceAuthenticationTypeType,
     ConfluenceBlogFieldNameType,
     ConfluencePageFieldNameType,
     ConfluenceSpaceFieldNameType,
     ConfluenceVersionType,
@@ -290,14 +291,15 @@
     DocumentStatusType,
     EndpointTypeType,
     EntityTypeType,
     ErrorCodeType,
     ExperienceStatusType,
     FaqFileFormatType,
     FaqStatusType,
+    FeaturedResultsSetStatusType,
     FsxFileSystemTypeType,
     HighlightTypeType,
     IndexEditionType,
     IndexStatusType,
     IntervalType,
     IssueSubEntityType,
     KeyLocationType,
@@ -320,14 +322,15 @@
     ScoreConfidenceType,
     ServiceNowAuthenticationTypeType,
     ServiceNowBuildVersionTypeType,
     SharePointOnlineAuthenticationTypeType,
     SharePointVersionType,
     SlackEntityType,
     SortOrderType,
+    SuggestionTypeType,
     ThesaurusStatusType,
     TypeType,
     UserContextPolicyType,
     UserGroupResolutionModeType,
     WarningCodeType,
     WebCrawlerModeType,
     kendraServiceName,
@@ -354,19 +357,21 @@
     AccessControlListConfigurationTypeDef,
     AclConfigurationTypeDef,
     DataSourceToIndexFieldMappingTypeDef,
     DataSourceVpcConfigurationTypeDef,
     S3PathTypeDef,
     EntityConfigurationTypeDef,
     FailedEntityTypeDef,
-    ResponseMetadataTypeDef,
     EntityPersonaConfigurationTypeDef,
+    SuggestableConfigTypeDef,
     BasicAuthenticationConfigurationTypeDef,
     DataSourceSyncJobMetricTargetTypeDef,
     BatchDeleteDocumentResponseFailedDocumentTypeDef,
+    BatchDeleteFeaturedResultsSetErrorTypeDef,
+    BatchDeleteFeaturedResultsSetRequestRequestTypeDef,
     BatchGetDocumentStatusResponseErrorTypeDef,
     StatusTypeDef,
     BatchPutDocumentResponseFailedDocumentTypeDef,
     CapacityUnitsConfigurationTypeDef,
     ClearQuerySuggestionsRequestRequestTypeDef,
     ClickFeedbackTypeDef,
     ConfluenceAttachmentToIndexFieldMappingTypeDef,
@@ -374,17 +379,25 @@
     ProxyConfigurationTypeDef,
     ConfluencePageToIndexFieldMappingTypeDef,
     ConfluenceSpaceToIndexFieldMappingTypeDef,
     ConnectionConfigurationTypeDef,
     ContentSourceConfigurationTypeDef,
     CorrectionTypeDef,
     PrincipalTypeDef,
+    CreateAccessControlConfigurationResponseTypeDef,
     TagTypeDef,
+    CreateDataSourceResponseTypeDef,
+    CreateExperienceResponseTypeDef,
+    CreateFaqResponseTypeDef,
+    FeaturedDocumentTypeDef,
     ServerSideEncryptionConfigurationTypeDef,
     UserGroupResolutionConfigurationTypeDef,
+    CreateIndexResponseTypeDef,
+    CreateQuerySuggestionsBlockListResponseTypeDef,
+    CreateThesaurusResponseTypeDef,
     TemplateConfigurationTypeDef,
     DataSourceGroupTypeDef,
     DataSourceSummaryTypeDef,
     DataSourceSyncJobMetricsTypeDef,
     SqlConfigurationTypeDef,
     DeleteAccessControlConfigurationRequestRequestTypeDef,
     DeleteDataSourceRequestRequestTypeDef,
@@ -395,32 +408,36 @@
     DeleteQuerySuggestionsBlockListRequestRequestTypeDef,
     DeleteThesaurusRequestRequestTypeDef,
     DescribeAccessControlConfigurationRequestRequestTypeDef,
     DescribeDataSourceRequestRequestTypeDef,
     DescribeExperienceRequestRequestTypeDef,
     ExperienceEndpointTypeDef,
     DescribeFaqRequestRequestTypeDef,
+    DescribeFeaturedResultsSetRequestRequestTypeDef,
+    FeaturedDocumentMissingTypeDef,
+    FeaturedDocumentWithMetadataTypeDef,
     DescribeIndexRequestRequestTypeDef,
     DescribePrincipalMappingRequestRequestTypeDef,
     GroupOrderingIdSummaryTypeDef,
     DescribeQuerySuggestionsBlockListRequestRequestTypeDef,
     DescribeQuerySuggestionsConfigRequestRequestTypeDef,
     DescribeThesaurusRequestRequestTypeDef,
     DisassociatePersonasFromEntitiesRequestRequestTypeDef,
     DocumentAttributeValueTypeDef,
     RelevanceTypeDef,
     SearchTypeDef,
     DocumentsMetadataConfigurationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EntityDisplayDataTypeDef,
     UserIdentityConfigurationTypeDef,
     FacetResultTypeDef,
     FacetTypeDef,
     FaqStatisticsTypeDef,
     FaqSummaryTypeDef,
-    GetQuerySuggestionsRequestRequestTypeDef,
+    FeaturedResultsSetSummaryTypeDef,
     GetSnapshotsRequestRequestTypeDef,
     TimeRangeTypeDef,
     GitHubDocumentCrawlPropertiesTypeDef,
     SaaSConfigurationTypeDef,
     MemberGroupTypeDef,
     MemberUserTypeDef,
     GroupSummaryTypeDef,
@@ -432,34 +449,37 @@
     ListAccessControlConfigurationsRequestRequestTypeDef,
     ListDataSourcesRequestRequestTypeDef,
     ListEntityPersonasRequestRequestTypeDef,
     PersonasSummaryTypeDef,
     ListExperienceEntitiesRequestRequestTypeDef,
     ListExperiencesRequestRequestTypeDef,
     ListFaqsRequestRequestTypeDef,
+    ListFeaturedResultsSetsRequestRequestTypeDef,
     ListGroupsOlderThanOrderingIdRequestRequestTypeDef,
     ListIndicesRequestRequestTypeDef,
     ListQuerySuggestionsBlockListsRequestRequestTypeDef,
     QuerySuggestionsBlockListSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     ListThesauriRequestRequestTypeDef,
     ThesaurusSummaryTypeDef,
     SortingConfigurationTypeDef,
     SpellCorrectionConfigurationTypeDef,
     ScoreAttributesTypeDef,
     WarningTypeDef,
     RelevanceFeedbackTypeDef,
+    ResponseMetadataTypeDef,
     SeedUrlConfigurationTypeDef,
     SiteMapsConfigurationTypeDef,
     StartDataSourceSyncJobRequestRequestTypeDef,
+    StartDataSourceSyncJobResponseTypeDef,
     StopDataSourceSyncJobRequestRequestTypeDef,
     SuggestionHighlightTypeDef,
     TableCellTypeDef,
     UntagResourceRequestRequestTypeDef,
-    UpdateQuerySuggestionsConfigRequestRequestTypeDef,
+    ListAccessControlConfigurationsResponseTypeDef,
     ColumnConfigurationTypeDef,
     GoogleDriveConfigurationTypeDef,
     SalesforceChatterFeedConfigurationTypeDef,
     SalesforceCustomKnowledgeArticleTypeConfigurationTypeDef,
     SalesforceStandardKnowledgeArticleTypeConfigurationTypeDef,
     SalesforceStandardObjectAttachmentConfigurationTypeDef,
     SalesforceStandardObjectConfigurationTypeDef,
@@ -468,71 +488,68 @@
     WorkDocsConfigurationTypeDef,
     BoxConfigurationTypeDef,
     FsxConfigurationTypeDef,
     JiraConfigurationTypeDef,
     QuipConfigurationTypeDef,
     SlackConfigurationTypeDef,
     AlfrescoConfigurationTypeDef,
+    DescribeFaqResponseTypeDef,
+    DescribeQuerySuggestionsBlockListResponseTypeDef,
+    DescribeThesaurusResponseTypeDef,
     OnPremiseConfigurationTypeDef,
     OneDriveUsersTypeDef,
     UpdateQuerySuggestionsBlockListRequestRequestTypeDef,
     UpdateThesaurusRequestRequestTypeDef,
     AssociateEntitiesToExperienceRequestRequestTypeDef,
     DisassociateEntitiesFromExperienceRequestRequestTypeDef,
     AssociateEntitiesToExperienceResponseTypeDef,
     AssociatePersonasToEntitiesResponseTypeDef,
-    CreateAccessControlConfigurationResponseTypeDef,
-    CreateDataSourceResponseTypeDef,
-    CreateExperienceResponseTypeDef,
-    CreateFaqResponseTypeDef,
-    CreateIndexResponseTypeDef,
-    CreateQuerySuggestionsBlockListResponseTypeDef,
-    CreateThesaurusResponseTypeDef,
-    DescribeFaqResponseTypeDef,
-    DescribeQuerySuggestionsBlockListResponseTypeDef,
-    DescribeQuerySuggestionsConfigResponseTypeDef,
-    DescribeThesaurusResponseTypeDef,
     DisassociateEntitiesFromExperienceResponseTypeDef,
     DisassociatePersonasFromEntitiesResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListAccessControlConfigurationsResponseTypeDef,
-    StartDataSourceSyncJobResponseTypeDef,
     AssociatePersonasToEntitiesRequestRequestTypeDef,
+    AttributeSuggestionsDescribeConfigTypeDef,
+    AttributeSuggestionsUpdateConfigTypeDef,
     AuthenticationConfigurationTypeDef,
     BatchDeleteDocumentRequestRequestTypeDef,
     BatchDeleteDocumentResponseTypeDef,
+    BatchDeleteFeaturedResultsSetResponseTypeDef,
     BatchGetDocumentStatusResponseTypeDef,
     BatchPutDocumentResponseTypeDef,
     ConfluenceAttachmentConfigurationTypeDef,
     ConfluenceBlogConfigurationTypeDef,
     SharePointConfigurationTypeDef,
     ConfluencePageConfigurationTypeDef,
     ConfluenceSpaceConfigurationTypeDef,
     SpellCorrectedQueryTypeDef,
     HierarchicalPrincipalTypeDef,
     CreateFaqRequestRequestTypeDef,
     CreateQuerySuggestionsBlockListRequestRequestTypeDef,
     CreateThesaurusRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    CreateFeaturedResultsSetRequestRequestTypeDef,
+    FeaturedResultsSetTypeDef,
+    UpdateFeaturedResultsSetRequestRequestTypeDef,
     UserContextTypeDef,
     ListDataSourcesResponseTypeDef,
     DataSourceSyncJobTypeDef,
     ExperiencesSummaryTypeDef,
+    DescribeFeaturedResultsSetResponseTypeDef,
     DescribePrincipalMappingResponseTypeDef,
     DocumentAttributeConditionTypeDef,
     DocumentAttributeTargetTypeDef,
     DocumentAttributeTypeDef,
     DocumentAttributeValueCountPairTypeDef,
     DocumentRelevanceConfigurationTypeDef,
     DocumentMetadataConfigurationTypeDef,
     S3DataSourceConfigurationTypeDef,
     ExperienceEntitiesSummaryTypeDef,
     ExperienceConfigurationTypeDef,
     ListFaqsResponseTypeDef,
+    ListFeaturedResultsSetsResponseTypeDef,
     GetSnapshotsResponseTypeDef,
     ListDataSourceSyncJobsRequestRequestTypeDef,
     GroupMembersTypeDef,
     ListGroupsOlderThanOrderingIdResponseTypeDef,
     TextWithHighlightsTypeDef,
     ListIndicesResponseTypeDef,
     IndexStatisticsTypeDef,
@@ -545,45 +562,56 @@
     SuggestionTextWithHighlightsTypeDef,
     TableRowTypeDef,
     DatabaseConfigurationTypeDef,
     SalesforceKnowledgeArticleConfigurationTypeDef,
     ServiceNowConfigurationTypeDef,
     GitHubConfigurationTypeDef,
     OneDriveConfigurationTypeDef,
+    DescribeQuerySuggestionsConfigResponseTypeDef,
+    UpdateQuerySuggestionsConfigRequestRequestTypeDef,
     ConfluenceConfigurationTypeDef,
     CreateAccessControlConfigurationRequestRequestTypeDef,
     DescribeAccessControlConfigurationResponseTypeDef,
     UpdateAccessControlConfigurationRequestRequestTypeDef,
+    CreateFeaturedResultsSetResponseTypeDef,
+    UpdateFeaturedResultsSetResponseTypeDef,
+    AttributeSuggestionsGetConfigTypeDef,
     ListDataSourceSyncJobsResponseTypeDef,
     ListExperiencesResponseTypeDef,
     HookConfigurationTypeDef,
     InlineCustomDocumentEnrichmentConfigurationTypeDef,
     AttributeFilterTypeDef,
     DocumentInfoTypeDef,
     DocumentTypeDef,
+    RetrieveResultItemTypeDef,
+    SourceDocumentTypeDef,
     QueryRequestRequestTypeDef,
+    RetrieveRequestRequestTypeDef,
     ListExperienceEntitiesResponseTypeDef,
     CreateExperienceRequestRequestTypeDef,
     DescribeExperienceResponseTypeDef,
     UpdateExperienceRequestRequestTypeDef,
     PutPrincipalMappingRequestRequestTypeDef,
     AdditionalResultAttributeValueTypeDef,
     CreateIndexRequestRequestTypeDef,
     DescribeIndexResponseTypeDef,
     UpdateIndexRequestRequestTypeDef,
     WebCrawlerConfigurationTypeDef,
     SuggestionValueTypeDef,
     TableExcerptTypeDef,
     SalesforceConfigurationTypeDef,
+    GetQuerySuggestionsRequestRequestTypeDef,
     CustomDocumentEnrichmentConfigurationTypeDef,
     BatchGetDocumentStatusRequestRequestTypeDef,
+    RetrieveResultTypeDef,
     AdditionalResultAttributeTypeDef,
     SuggestionTypeDef,
     DataSourceConfigurationTypeDef,
     BatchPutDocumentRequestRequestTypeDef,
+    FeaturedResultsItemTypeDef,
     QueryResultItemTypeDef,
     GetQuerySuggestionsResponseTypeDef,
     CreateDataSourceRequestRequestTypeDef,
     DescribeDataSourceResponseTypeDef,
     UpdateDataSourceRequestRequestTypeDef,
     QueryResultTypeDef,
 )
@@ -596,43 +624,43 @@
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

### Comparing `types-aiobotocore-kendra-2.5.0.post1/types_aiobotocore_kendra.egg-info/SOURCES.txt` & `types-aiobotocore-kendra-2.5.1/types_aiobotocore_kendra.egg-info/SOURCES.txt`

 * *Files identical despite different names*

