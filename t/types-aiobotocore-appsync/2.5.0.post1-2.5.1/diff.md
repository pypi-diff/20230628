# Comparing `tmp/types-aiobotocore-appsync-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-appsync-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-appsync-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:12 2023, max compression
+gzip compressed data, was "types-aiobotocore-appsync-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-appsync-2.5.0.post1.tar` & `types-aiobotocore-appsync-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.778948 types-aiobotocore-appsync-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19253 2023-03-11 12:26:12.770948 types-aiobotocore-appsync-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17682 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:12.778948 types-aiobotocore-appsync-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.770948 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/
--rw-r--r--   0 runner    (1001) docker     (123)     1827 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1826 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    39206 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    39139 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10584 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10582 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8705 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8695 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    48145 2023-03-11 12:09:50.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    48072 2023-03-11 12:09:50.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:49.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:12.770948 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19253 2023-03-11 12:26:12.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      813 2023-03-11 12:26:12.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:12.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:12.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:12.000000 types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.638094 types-aiobotocore-appsync-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20353 2023-06-28 01:43:06.638094 types-aiobotocore-appsync-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18788 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.638094 types-aiobotocore-appsync-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.638094 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/
+-rw-r--r--   0 runner    (1001) docker     (123)     1827 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1826 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45985 2023-06-28 01:26:26.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45909 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11472 2023-06-28 01:26:26.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11470 2023-06-28 01:26:26.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8729 2023-06-28 01:26:26.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8720 2023-06-28 01:26:26.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    57225 2023-06-28 01:26:27.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    57142 2023-06-28 01:26:26.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:25.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.638094 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20353 2023-06-28 01:43:06.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      813 2023-06-28 01:43:06.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:06.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:06.000000 types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/LICENSE` & `types-aiobotocore-appsync-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-appsync-2.5.0.post1/PKG-INFO` & `types-aiobotocore-appsync-2.5.1/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appsync
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppSync 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppSync 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appsync"></a>
 
 # types-aiobotocore-appsync
 
 [![PyPI - types-aiobotocore-appsync](https://img.shields.io/pypi/v/types-aiobotocore-appsync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appsync)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appsync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appsync)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appsync?color=blue)](https://pypistats.org/packages/types-aiobotocore-appsync)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppSync 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
+[aiobotocore.AppSync 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
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
 [types-aiobotocore-appsync docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/).
 
 See how it helps to find and fix potential bugs:
 
@@ -322,26 +322,31 @@
     AuthenticationTypeType,
     AuthorizationTypeType,
     ConflictDetectionTypeType,
     ConflictHandlerTypeType,
     DataSourceTypeType,
     DefaultActionType,
     FieldLogLevelType,
+    GraphQLApiTypeType,
+    GraphQLApiVisibilityType,
     ListApiKeysPaginatorName,
     ListDataSourcesPaginatorName,
     ListFunctionsPaginatorName,
     ListGraphqlApisPaginatorName,
     ListResolversByFunctionPaginatorName,
     ListResolversPaginatorName,
     ListTypesPaginatorName,
+    MergeTypeType,
     OutputTypeType,
+    OwnershipType,
     RelationalDatabaseSourceTypeType,
     ResolverKindType,
     RuntimeNameType,
     SchemaStatusType,
+    SourceApiAssociationStatusType,
     TypeDefinitionFormatType,
     AppSyncServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -364,15 +369,15 @@
     LambdaAuthorizerConfigTypeDef,
     OpenIDConnectConfigTypeDef,
     ApiAssociationTypeDef,
     ApiCacheTypeDef,
     ApiKeyTypeDef,
     AppSyncRuntimeTypeDef,
     AssociateApiRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    SourceApiAssociationConfigTypeDef,
     AwsIamConfigTypeDef,
     CachingConfigTypeDef,
     CodeErrorLocationTypeDef,
     CreateApiCacheRequestRequestTypeDef,
     CreateApiKeyRequestRequestTypeDef,
     ElasticsearchDataSourceConfigTypeDef,
     EventBridgeDataSourceConfigTypeDef,
@@ -391,84 +396,105 @@
     DeleteDomainNameRequestRequestTypeDef,
     DeleteFunctionRequestRequestTypeDef,
     DeleteGraphqlApiRequestRequestTypeDef,
     DeleteResolverRequestRequestTypeDef,
     DeleteTypeRequestRequestTypeDef,
     DeltaSyncConfigTypeDef,
     DisassociateApiRequestRequestTypeDef,
+    DisassociateMergedGraphqlApiRequestRequestTypeDef,
+    DisassociateMergedGraphqlApiResponseTypeDef,
+    DisassociateSourceGraphqlApiRequestRequestTypeDef,
+    DisassociateSourceGraphqlApiResponseTypeDef,
     ErrorDetailTypeDef,
     EvaluateMappingTemplateRequestRequestTypeDef,
     FlushApiCacheRequestRequestTypeDef,
     GetApiAssociationRequestRequestTypeDef,
     GetApiCacheRequestRequestTypeDef,
     GetDataSourceRequestRequestTypeDef,
     GetDomainNameRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
     GetGraphqlApiRequestRequestTypeDef,
     GetIntrospectionSchemaRequestRequestTypeDef,
+    GetIntrospectionSchemaResponseTypeDef,
     GetResolverRequestRequestTypeDef,
     GetSchemaCreationStatusRequestRequestTypeDef,
+    GetSchemaCreationStatusResponseTypeDef,
+    GetSourceApiAssociationRequestRequestTypeDef,
     GetTypeRequestRequestTypeDef,
     LambdaConflictHandlerConfigTypeDef,
-    PaginatorConfigTypeDef,
+    ListApiKeysRequestListApiKeysPaginateTypeDef,
     ListApiKeysRequestRequestTypeDef,
+    ListDataSourcesRequestListDataSourcesPaginateTypeDef,
     ListDataSourcesRequestRequestTypeDef,
     ListDomainNamesRequestRequestTypeDef,
+    ListFunctionsRequestListFunctionsPaginateTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListGraphqlApisRequestListGraphqlApisPaginateTypeDef,
     ListGraphqlApisRequestRequestTypeDef,
+    ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
     ListResolversByFunctionRequestRequestTypeDef,
+    ListResolversRequestListResolversPaginateTypeDef,
     ListResolversRequestRequestTypeDef,
+    ListSourceApiAssociationsRequestRequestTypeDef,
+    SourceApiAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTypesByAssociationRequestRequestTypeDef,
+    ListTypesRequestListTypesPaginateTypeDef,
     ListTypesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     RdsHttpEndpointConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartSchemaCreationRequestRequestTypeDef,
+    StartSchemaCreationResponseTypeDef,
+    StartSchemaMergeRequestRequestTypeDef,
+    StartSchemaMergeResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiCacheRequestRequestTypeDef,
     UpdateApiKeyRequestRequestTypeDef,
     UpdateDomainNameRequestRequestTypeDef,
     UpdateTypeRequestRequestTypeDef,
     AdditionalAuthenticationProviderTypeDef,
-    EvaluateCodeRequestRequestTypeDef,
     AssociateApiResponseTypeDef,
-    CreateApiCacheResponseTypeDef,
-    CreateApiKeyResponseTypeDef,
     GetApiAssociationResponseTypeDef,
+    CreateApiCacheResponseTypeDef,
     GetApiCacheResponseTypeDef,
-    GetIntrospectionSchemaResponseTypeDef,
-    GetSchemaCreationStatusResponseTypeDef,
-    ListApiKeysResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartSchemaCreationResponseTypeDef,
     UpdateApiCacheResponseTypeDef,
+    CreateApiKeyResponseTypeDef,
+    ListApiKeysResponseTypeDef,
     UpdateApiKeyResponseTypeDef,
+    EvaluateCodeRequestRequestTypeDef,
+    AssociateMergedGraphqlApiRequestRequestTypeDef,
+    AssociateSourceGraphqlApiRequestRequestTypeDef,
+    SourceApiAssociationTypeDef,
+    UpdateSourceApiAssociationRequestRequestTypeDef,
     AuthorizationConfigTypeDef,
     CodeErrorTypeDef,
     CreateDomainNameResponseTypeDef,
     GetDomainNameResponseTypeDef,
     ListDomainNamesResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     CreateTypeResponseTypeDef,
     GetTypeResponseTypeDef,
+    ListTypesByAssociationResponseTypeDef,
     ListTypesResponseTypeDef,
     UpdateTypeResponseTypeDef,
     DynamodbDataSourceConfigTypeDef,
     EvaluateMappingTemplateResponseTypeDef,
     SyncConfigTypeDef,
-    ListApiKeysRequestListApiKeysPaginateTypeDef,
-    ListDataSourcesRequestListDataSourcesPaginateTypeDef,
-    ListFunctionsRequestListFunctionsPaginateTypeDef,
-    ListGraphqlApisRequestListGraphqlApisPaginateTypeDef,
-    ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
-    ListResolversRequestListResolversPaginateTypeDef,
-    ListTypesRequestListTypesPaginateTypeDef,
+    ListSourceApiAssociationsResponseTypeDef,
     RelationalDatabaseDataSourceConfigTypeDef,
     CreateGraphqlApiRequestRequestTypeDef,
     GraphqlApiTypeDef,
     UpdateGraphqlApiRequestRequestTypeDef,
+    AssociateMergedGraphqlApiResponseTypeDef,
+    AssociateSourceGraphqlApiResponseTypeDef,
+    GetSourceApiAssociationResponseTypeDef,
+    UpdateSourceApiAssociationResponseTypeDef,
     HttpDataSourceConfigTypeDef,
     EvaluateCodeErrorDetailTypeDef,
     CreateFunctionRequestRequestTypeDef,
     CreateResolverRequestRequestTypeDef,
     FunctionConfigurationTypeDef,
     ResolverTypeDef,
     UpdateFunctionRequestRequestTypeDef,
@@ -504,43 +530,43 @@
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

### Comparing `types-aiobotocore-appsync-2.5.0.post1/README.md` & `types-aiobotocore-appsync-2.5.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-appsync"></a>
 
 # types-aiobotocore-appsync
 
 [![PyPI - types-aiobotocore-appsync](https://img.shields.io/pypi/v/types-aiobotocore-appsync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appsync)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appsync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appsync)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appsync?color=blue)](https://pypistats.org/packages/types-aiobotocore-appsync)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppSync 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
+[aiobotocore.AppSync 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
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
 [types-aiobotocore-appsync docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/).
 
 See how it helps to find and fix potential bugs:
 
@@ -289,26 +289,31 @@
     AuthenticationTypeType,
     AuthorizationTypeType,
     ConflictDetectionTypeType,
     ConflictHandlerTypeType,
     DataSourceTypeType,
     DefaultActionType,
     FieldLogLevelType,
+    GraphQLApiTypeType,
+    GraphQLApiVisibilityType,
     ListApiKeysPaginatorName,
     ListDataSourcesPaginatorName,
     ListFunctionsPaginatorName,
     ListGraphqlApisPaginatorName,
     ListResolversByFunctionPaginatorName,
     ListResolversPaginatorName,
     ListTypesPaginatorName,
+    MergeTypeType,
     OutputTypeType,
+    OwnershipType,
     RelationalDatabaseSourceTypeType,
     ResolverKindType,
     RuntimeNameType,
     SchemaStatusType,
+    SourceApiAssociationStatusType,
     TypeDefinitionFormatType,
     AppSyncServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -331,15 +336,15 @@
     LambdaAuthorizerConfigTypeDef,
     OpenIDConnectConfigTypeDef,
     ApiAssociationTypeDef,
     ApiCacheTypeDef,
     ApiKeyTypeDef,
     AppSyncRuntimeTypeDef,
     AssociateApiRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    SourceApiAssociationConfigTypeDef,
     AwsIamConfigTypeDef,
     CachingConfigTypeDef,
     CodeErrorLocationTypeDef,
     CreateApiCacheRequestRequestTypeDef,
     CreateApiKeyRequestRequestTypeDef,
     ElasticsearchDataSourceConfigTypeDef,
     EventBridgeDataSourceConfigTypeDef,
@@ -358,84 +363,105 @@
     DeleteDomainNameRequestRequestTypeDef,
     DeleteFunctionRequestRequestTypeDef,
     DeleteGraphqlApiRequestRequestTypeDef,
     DeleteResolverRequestRequestTypeDef,
     DeleteTypeRequestRequestTypeDef,
     DeltaSyncConfigTypeDef,
     DisassociateApiRequestRequestTypeDef,
+    DisassociateMergedGraphqlApiRequestRequestTypeDef,
+    DisassociateMergedGraphqlApiResponseTypeDef,
+    DisassociateSourceGraphqlApiRequestRequestTypeDef,
+    DisassociateSourceGraphqlApiResponseTypeDef,
     ErrorDetailTypeDef,
     EvaluateMappingTemplateRequestRequestTypeDef,
     FlushApiCacheRequestRequestTypeDef,
     GetApiAssociationRequestRequestTypeDef,
     GetApiCacheRequestRequestTypeDef,
     GetDataSourceRequestRequestTypeDef,
     GetDomainNameRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
     GetGraphqlApiRequestRequestTypeDef,
     GetIntrospectionSchemaRequestRequestTypeDef,
+    GetIntrospectionSchemaResponseTypeDef,
     GetResolverRequestRequestTypeDef,
     GetSchemaCreationStatusRequestRequestTypeDef,
+    GetSchemaCreationStatusResponseTypeDef,
+    GetSourceApiAssociationRequestRequestTypeDef,
     GetTypeRequestRequestTypeDef,
     LambdaConflictHandlerConfigTypeDef,
-    PaginatorConfigTypeDef,
+    ListApiKeysRequestListApiKeysPaginateTypeDef,
     ListApiKeysRequestRequestTypeDef,
+    ListDataSourcesRequestListDataSourcesPaginateTypeDef,
     ListDataSourcesRequestRequestTypeDef,
     ListDomainNamesRequestRequestTypeDef,
+    ListFunctionsRequestListFunctionsPaginateTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListGraphqlApisRequestListGraphqlApisPaginateTypeDef,
     ListGraphqlApisRequestRequestTypeDef,
+    ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
     ListResolversByFunctionRequestRequestTypeDef,
+    ListResolversRequestListResolversPaginateTypeDef,
     ListResolversRequestRequestTypeDef,
+    ListSourceApiAssociationsRequestRequestTypeDef,
+    SourceApiAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTypesByAssociationRequestRequestTypeDef,
+    ListTypesRequestListTypesPaginateTypeDef,
     ListTypesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     RdsHttpEndpointConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartSchemaCreationRequestRequestTypeDef,
+    StartSchemaCreationResponseTypeDef,
+    StartSchemaMergeRequestRequestTypeDef,
+    StartSchemaMergeResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiCacheRequestRequestTypeDef,
     UpdateApiKeyRequestRequestTypeDef,
     UpdateDomainNameRequestRequestTypeDef,
     UpdateTypeRequestRequestTypeDef,
     AdditionalAuthenticationProviderTypeDef,
-    EvaluateCodeRequestRequestTypeDef,
     AssociateApiResponseTypeDef,
-    CreateApiCacheResponseTypeDef,
-    CreateApiKeyResponseTypeDef,
     GetApiAssociationResponseTypeDef,
+    CreateApiCacheResponseTypeDef,
     GetApiCacheResponseTypeDef,
-    GetIntrospectionSchemaResponseTypeDef,
-    GetSchemaCreationStatusResponseTypeDef,
-    ListApiKeysResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartSchemaCreationResponseTypeDef,
     UpdateApiCacheResponseTypeDef,
+    CreateApiKeyResponseTypeDef,
+    ListApiKeysResponseTypeDef,
     UpdateApiKeyResponseTypeDef,
+    EvaluateCodeRequestRequestTypeDef,
+    AssociateMergedGraphqlApiRequestRequestTypeDef,
+    AssociateSourceGraphqlApiRequestRequestTypeDef,
+    SourceApiAssociationTypeDef,
+    UpdateSourceApiAssociationRequestRequestTypeDef,
     AuthorizationConfigTypeDef,
     CodeErrorTypeDef,
     CreateDomainNameResponseTypeDef,
     GetDomainNameResponseTypeDef,
     ListDomainNamesResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     CreateTypeResponseTypeDef,
     GetTypeResponseTypeDef,
+    ListTypesByAssociationResponseTypeDef,
     ListTypesResponseTypeDef,
     UpdateTypeResponseTypeDef,
     DynamodbDataSourceConfigTypeDef,
     EvaluateMappingTemplateResponseTypeDef,
     SyncConfigTypeDef,
-    ListApiKeysRequestListApiKeysPaginateTypeDef,
-    ListDataSourcesRequestListDataSourcesPaginateTypeDef,
-    ListFunctionsRequestListFunctionsPaginateTypeDef,
-    ListGraphqlApisRequestListGraphqlApisPaginateTypeDef,
-    ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
-    ListResolversRequestListResolversPaginateTypeDef,
-    ListTypesRequestListTypesPaginateTypeDef,
+    ListSourceApiAssociationsResponseTypeDef,
     RelationalDatabaseDataSourceConfigTypeDef,
     CreateGraphqlApiRequestRequestTypeDef,
     GraphqlApiTypeDef,
     UpdateGraphqlApiRequestRequestTypeDef,
+    AssociateMergedGraphqlApiResponseTypeDef,
+    AssociateSourceGraphqlApiResponseTypeDef,
+    GetSourceApiAssociationResponseTypeDef,
+    UpdateSourceApiAssociationResponseTypeDef,
     HttpDataSourceConfigTypeDef,
     EvaluateCodeErrorDetailTypeDef,
     CreateFunctionRequestRequestTypeDef,
     CreateResolverRequestRequestTypeDef,
     FunctionConfigurationTypeDef,
     ResolverTypeDef,
     UpdateFunctionRequestRequestTypeDef,
@@ -471,43 +497,43 @@
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

### Comparing `types-aiobotocore-appsync-2.5.0.post1/setup.py` & `types-aiobotocore-appsync-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-appsync.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-appsync",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_appsync"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AppSync 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.AppSync 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/"
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

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/__init__.py` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/__init__.pyi` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/__main__.py` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AppSync 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AppSync 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync\nOther"
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

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/client.py` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/client.py`

 * *Files 12% similar despite different names*

```diff
@@ -22,15 +22,18 @@
 from botocore.client import ClientMeta
 
 from .literals import (
     ApiCacheTypeType,
     ApiCachingBehaviorType,
     AuthenticationTypeType,
     DataSourceTypeType,
+    GraphQLApiTypeType,
+    GraphQLApiVisibilityType,
     OutputTypeType,
+    OwnershipType,
     ResolverKindType,
     TypeDefinitionFormatType,
 )
 from .paginator import (
     ListApiKeysPaginator,
     ListDataSourcesPaginator,
     ListFunctionsPaginator,
@@ -39,64 +42,74 @@
     ListResolversPaginator,
     ListTypesPaginator,
 )
 from .type_defs import (
     AdditionalAuthenticationProviderTypeDef,
     AppSyncRuntimeTypeDef,
     AssociateApiResponseTypeDef,
+    AssociateMergedGraphqlApiResponseTypeDef,
+    AssociateSourceGraphqlApiResponseTypeDef,
     CachingConfigTypeDef,
     CreateApiCacheResponseTypeDef,
     CreateApiKeyResponseTypeDef,
     CreateDataSourceResponseTypeDef,
     CreateDomainNameResponseTypeDef,
     CreateFunctionResponseTypeDef,
     CreateGraphqlApiResponseTypeDef,
     CreateResolverResponseTypeDef,
     CreateTypeResponseTypeDef,
+    DisassociateMergedGraphqlApiResponseTypeDef,
+    DisassociateSourceGraphqlApiResponseTypeDef,
     DynamodbDataSourceConfigTypeDef,
     ElasticsearchDataSourceConfigTypeDef,
     EvaluateCodeResponseTypeDef,
     EvaluateMappingTemplateResponseTypeDef,
     EventBridgeDataSourceConfigTypeDef,
     GetApiAssociationResponseTypeDef,
     GetApiCacheResponseTypeDef,
     GetDataSourceResponseTypeDef,
     GetDomainNameResponseTypeDef,
     GetFunctionResponseTypeDef,
     GetGraphqlApiResponseTypeDef,
     GetIntrospectionSchemaResponseTypeDef,
     GetResolverResponseTypeDef,
     GetSchemaCreationStatusResponseTypeDef,
+    GetSourceApiAssociationResponseTypeDef,
     GetTypeResponseTypeDef,
     HttpDataSourceConfigTypeDef,
     LambdaAuthorizerConfigTypeDef,
     LambdaDataSourceConfigTypeDef,
     ListApiKeysResponseTypeDef,
     ListDataSourcesResponseTypeDef,
     ListDomainNamesResponseTypeDef,
     ListFunctionsResponseTypeDef,
     ListGraphqlApisResponseTypeDef,
     ListResolversByFunctionResponseTypeDef,
     ListResolversResponseTypeDef,
+    ListSourceApiAssociationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTypesByAssociationResponseTypeDef,
     ListTypesResponseTypeDef,
     LogConfigTypeDef,
     OpenIDConnectConfigTypeDef,
     OpenSearchServiceDataSourceConfigTypeDef,
     PipelineConfigTypeDef,
     RelationalDatabaseDataSourceConfigTypeDef,
+    SourceApiAssociationConfigTypeDef,
     StartSchemaCreationResponseTypeDef,
+    StartSchemaMergeResponseTypeDef,
     SyncConfigTypeDef,
     UpdateApiCacheResponseTypeDef,
     UpdateApiKeyResponseTypeDef,
     UpdateDataSourceResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     UpdateFunctionResponseTypeDef,
     UpdateGraphqlApiResponseTypeDef,
     UpdateResolverResponseTypeDef,
+    UpdateSourceApiAssociationResponseTypeDef,
     UpdateTypeResponseTypeDef,
     UserPoolConfigTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -150,14 +163,46 @@
         """
         Maps an endpoint to your custom domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.associate_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#associate_api)
         """
 
+    async def associate_merged_graphql_api(
+        self,
+        *,
+        sourceApiIdentifier: str,
+        mergedApiIdentifier: str,
+        description: str = ...,
+        sourceApiAssociationConfig: SourceApiAssociationConfigTypeDef = ...
+    ) -> AssociateMergedGraphqlApiResponseTypeDef:
+        """
+        Creates an association between a Merged API and source API using the source
+        API's identifier.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.associate_merged_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#associate_merged_graphql_api)
+        """
+
+    async def associate_source_graphql_api(
+        self,
+        *,
+        mergedApiIdentifier: str,
+        sourceApiIdentifier: str,
+        description: str = ...,
+        sourceApiAssociationConfig: SourceApiAssociationConfigTypeDef = ...
+    ) -> AssociateSourceGraphqlApiResponseTypeDef:
+        """
+        Creates an association between a Merged API and source API using the Merged
+        API's identifier.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.associate_source_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#associate_source_graphql_api)
+        """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#can_paginate)
         """
@@ -259,15 +304,19 @@
         authenticationType: AuthenticationTypeType,
         logConfig: LogConfigTypeDef = ...,
         userPoolConfig: UserPoolConfigTypeDef = ...,
         openIDConnectConfig: OpenIDConnectConfigTypeDef = ...,
         tags: Mapping[str, str] = ...,
         additionalAuthenticationProviders: Sequence[AdditionalAuthenticationProviderTypeDef] = ...,
         xrayEnabled: bool = ...,
-        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...
+        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...,
+        visibility: GraphQLApiVisibilityType = ...,
+        apiType: GraphQLApiTypeType = ...,
+        mergedApiExecutionRoleArn: str = ...,
+        ownerContact: str = ...
     ) -> CreateGraphqlApiResponseTypeDef:
         """
         Creates a `GraphqlApi` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_graphql_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#create_graphql_api)
         """
@@ -336,15 +385,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_domain_name)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#delete_domain_name)
         """
 
     async def delete_function(self, *, apiId: str, functionId: str) -> Dict[str, Any]:
         """
-        Deletes a `Function` .
+        Deletes a `Function`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_function)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#delete_function)
         """
 
     async def delete_graphql_api(self, *, apiId: str) -> Dict[str, Any]:
         """
@@ -374,14 +423,36 @@
         """
         Removes an `ApiAssociation` object from a custom domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.disassociate_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#disassociate_api)
         """
 
+    async def disassociate_merged_graphql_api(
+        self, *, sourceApiIdentifier: str, associationId: str
+    ) -> DisassociateMergedGraphqlApiResponseTypeDef:
+        """
+        Deletes an association between a Merged API and source API using the source
+        API's identifier and the association ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.disassociate_merged_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#disassociate_merged_graphql_api)
+        """
+
+    async def disassociate_source_graphql_api(
+        self, *, mergedApiIdentifier: str, associationId: str
+    ) -> DisassociateSourceGraphqlApiResponseTypeDef:
+        """
+        Deletes an association between a Merged API and source API using the Merged
+        API's identifier and the association ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.disassociate_source_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#disassociate_source_graphql_api)
+        """
+
     async def evaluate_code(
         self, *, runtime: AppSyncRuntimeTypeDef, code: str, context: str, function: str = ...
     ) -> EvaluateCodeResponseTypeDef:
         """
         Evaluates the given code and returns the response.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.evaluate_code)
@@ -450,15 +521,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_domain_name)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_domain_name)
         """
 
     async def get_function(self, *, apiId: str, functionId: str) -> GetFunctionResponseTypeDef:
         """
-        Get a `Function` .
+        Get a `Function`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_function)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_function)
         """
 
     async def get_graphql_api(self, *, apiId: str) -> GetGraphqlApiResponseTypeDef:
         """
@@ -494,14 +565,24 @@
         """
         Retrieves the current status of a schema creation operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_schema_creation_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_schema_creation_status)
         """
 
+    async def get_source_api_association(
+        self, *, mergedApiIdentifier: str, associationId: str
+    ) -> GetSourceApiAssociationResponseTypeDef:
+        """
+        Retrieves a `SourceApiAssociation` object.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_source_api_association)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_source_api_association)
+        """
+
     async def get_type(
         self, *, apiId: str, typeName: str, format: TypeDefinitionFormatType
     ) -> GetTypeResponseTypeDef:
         """
         Retrieves a `Type` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_type)
@@ -545,15 +626,20 @@
         List multiple functions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_functions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_functions)
         """
 
     async def list_graphql_apis(
-        self, *, nextToken: str = ..., maxResults: int = ...
+        self,
+        *,
+        nextToken: str = ...,
+        maxResults: int = ...,
+        apiType: GraphQLApiTypeType = ...,
+        owner: OwnershipType = ...
     ) -> ListGraphqlApisResponseTypeDef:
         """
         Lists your GraphQL APIs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_graphql_apis)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_graphql_apis)
         """
@@ -574,14 +660,24 @@
         """
         List the resolvers that are associated with a specific function.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_resolvers_by_function)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_resolvers_by_function)
         """
 
+    async def list_source_api_associations(
+        self, *, apiId: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListSourceApiAssociationsResponseTypeDef:
+        """
+        Lists the `SourceApiAssociationSummary` data.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_source_api_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_source_api_associations)
+        """
+
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags for a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_tags_for_resource)
@@ -599,24 +695,50 @@
         """
         Lists the types for a given API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_types)
         """
 
+    async def list_types_by_association(
+        self,
+        *,
+        mergedApiIdentifier: str,
+        associationId: str,
+        format: TypeDefinitionFormatType,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListTypesByAssociationResponseTypeDef:
+        """
+        Lists `Type` objects by the source API association ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_types_by_association)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_types_by_association)
+        """
+
     async def start_schema_creation(
         self, *, apiId: str, definition: Union[str, bytes, IO[Any], StreamingBody]
     ) -> StartSchemaCreationResponseTypeDef:
         """
         Adds a new schema to your GraphQL API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.start_schema_creation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#start_schema_creation)
         """
 
+    async def start_schema_merge(
+        self, *, associationId: str, mergedApiIdentifier: str
+    ) -> StartSchemaMergeResponseTypeDef:
+        """
+        Initiates a merge operation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.start_schema_merge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#start_schema_merge)
+        """
+
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Tags a resource with user-supplied tags.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#tag_resource)
         """
@@ -717,15 +839,17 @@
         name: str,
         logConfig: LogConfigTypeDef = ...,
         authenticationType: AuthenticationTypeType = ...,
         userPoolConfig: UserPoolConfigTypeDef = ...,
         openIDConnectConfig: OpenIDConnectConfigTypeDef = ...,
         additionalAuthenticationProviders: Sequence[AdditionalAuthenticationProviderTypeDef] = ...,
         xrayEnabled: bool = ...,
-        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...
+        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...,
+        mergedApiExecutionRoleArn: str = ...,
+        ownerContact: str = ...
     ) -> UpdateGraphqlApiResponseTypeDef:
         """
         Updates a `GraphqlApi` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_graphql_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#update_graphql_api)
         """
@@ -750,14 +874,30 @@
         """
         Updates a `Resolver` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_resolver)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#update_resolver)
         """
 
+    async def update_source_api_association(
+        self,
+        *,
+        associationId: str,
+        mergedApiIdentifier: str,
+        description: str = ...,
+        sourceApiAssociationConfig: SourceApiAssociationConfigTypeDef = ...
+    ) -> UpdateSourceApiAssociationResponseTypeDef:
+        """
+        Updates some of the configuration choices of a particular source API
+        association.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_source_api_association)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#update_source_api_association)
+        """
+
     async def update_type(
         self, *, apiId: str, typeName: str, format: TypeDefinitionFormatType, definition: str = ...
     ) -> UpdateTypeResponseTypeDef:
         """
         Updates a `Type` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_type)
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/client.pyi` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/client.pyi`

 * *Files 15% similar despite different names*

```diff
@@ -22,15 +22,18 @@
 from botocore.client import ClientMeta
 
 from .literals import (
     ApiCacheTypeType,
     ApiCachingBehaviorType,
     AuthenticationTypeType,
     DataSourceTypeType,
+    GraphQLApiTypeType,
+    GraphQLApiVisibilityType,
     OutputTypeType,
+    OwnershipType,
     ResolverKindType,
     TypeDefinitionFormatType,
 )
 from .paginator import (
     ListApiKeysPaginator,
     ListDataSourcesPaginator,
     ListFunctionsPaginator,
@@ -39,64 +42,74 @@
     ListResolversPaginator,
     ListTypesPaginator,
 )
 from .type_defs import (
     AdditionalAuthenticationProviderTypeDef,
     AppSyncRuntimeTypeDef,
     AssociateApiResponseTypeDef,
+    AssociateMergedGraphqlApiResponseTypeDef,
+    AssociateSourceGraphqlApiResponseTypeDef,
     CachingConfigTypeDef,
     CreateApiCacheResponseTypeDef,
     CreateApiKeyResponseTypeDef,
     CreateDataSourceResponseTypeDef,
     CreateDomainNameResponseTypeDef,
     CreateFunctionResponseTypeDef,
     CreateGraphqlApiResponseTypeDef,
     CreateResolverResponseTypeDef,
     CreateTypeResponseTypeDef,
+    DisassociateMergedGraphqlApiResponseTypeDef,
+    DisassociateSourceGraphqlApiResponseTypeDef,
     DynamodbDataSourceConfigTypeDef,
     ElasticsearchDataSourceConfigTypeDef,
     EvaluateCodeResponseTypeDef,
     EvaluateMappingTemplateResponseTypeDef,
     EventBridgeDataSourceConfigTypeDef,
     GetApiAssociationResponseTypeDef,
     GetApiCacheResponseTypeDef,
     GetDataSourceResponseTypeDef,
     GetDomainNameResponseTypeDef,
     GetFunctionResponseTypeDef,
     GetGraphqlApiResponseTypeDef,
     GetIntrospectionSchemaResponseTypeDef,
     GetResolverResponseTypeDef,
     GetSchemaCreationStatusResponseTypeDef,
+    GetSourceApiAssociationResponseTypeDef,
     GetTypeResponseTypeDef,
     HttpDataSourceConfigTypeDef,
     LambdaAuthorizerConfigTypeDef,
     LambdaDataSourceConfigTypeDef,
     ListApiKeysResponseTypeDef,
     ListDataSourcesResponseTypeDef,
     ListDomainNamesResponseTypeDef,
     ListFunctionsResponseTypeDef,
     ListGraphqlApisResponseTypeDef,
     ListResolversByFunctionResponseTypeDef,
     ListResolversResponseTypeDef,
+    ListSourceApiAssociationsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTypesByAssociationResponseTypeDef,
     ListTypesResponseTypeDef,
     LogConfigTypeDef,
     OpenIDConnectConfigTypeDef,
     OpenSearchServiceDataSourceConfigTypeDef,
     PipelineConfigTypeDef,
     RelationalDatabaseDataSourceConfigTypeDef,
+    SourceApiAssociationConfigTypeDef,
     StartSchemaCreationResponseTypeDef,
+    StartSchemaMergeResponseTypeDef,
     SyncConfigTypeDef,
     UpdateApiCacheResponseTypeDef,
     UpdateApiKeyResponseTypeDef,
     UpdateDataSourceResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     UpdateFunctionResponseTypeDef,
     UpdateGraphqlApiResponseTypeDef,
     UpdateResolverResponseTypeDef,
+    UpdateSourceApiAssociationResponseTypeDef,
     UpdateTypeResponseTypeDef,
     UserPoolConfigTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -144,14 +157,44 @@
     async def associate_api(self, *, domainName: str, apiId: str) -> AssociateApiResponseTypeDef:
         """
         Maps an endpoint to your custom domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.associate_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#associate_api)
         """
+    async def associate_merged_graphql_api(
+        self,
+        *,
+        sourceApiIdentifier: str,
+        mergedApiIdentifier: str,
+        description: str = ...,
+        sourceApiAssociationConfig: SourceApiAssociationConfigTypeDef = ...
+    ) -> AssociateMergedGraphqlApiResponseTypeDef:
+        """
+        Creates an association between a Merged API and source API using the source
+        API's identifier.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.associate_merged_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#associate_merged_graphql_api)
+        """
+    async def associate_source_graphql_api(
+        self,
+        *,
+        mergedApiIdentifier: str,
+        sourceApiIdentifier: str,
+        description: str = ...,
+        sourceApiAssociationConfig: SourceApiAssociationConfigTypeDef = ...
+    ) -> AssociateSourceGraphqlApiResponseTypeDef:
+        """
+        Creates an association between a Merged API and source API using the Merged
+        API's identifier.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.associate_source_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#associate_source_graphql_api)
+        """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#can_paginate)
         """
@@ -246,15 +289,19 @@
         authenticationType: AuthenticationTypeType,
         logConfig: LogConfigTypeDef = ...,
         userPoolConfig: UserPoolConfigTypeDef = ...,
         openIDConnectConfig: OpenIDConnectConfigTypeDef = ...,
         tags: Mapping[str, str] = ...,
         additionalAuthenticationProviders: Sequence[AdditionalAuthenticationProviderTypeDef] = ...,
         xrayEnabled: bool = ...,
-        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...
+        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...,
+        visibility: GraphQLApiVisibilityType = ...,
+        apiType: GraphQLApiTypeType = ...,
+        mergedApiExecutionRoleArn: str = ...,
+        ownerContact: str = ...
     ) -> CreateGraphqlApiResponseTypeDef:
         """
         Creates a `GraphqlApi` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.create_graphql_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#create_graphql_api)
         """
@@ -316,15 +363,15 @@
         Deletes a custom `DomainName` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_domain_name)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#delete_domain_name)
         """
     async def delete_function(self, *, apiId: str, functionId: str) -> Dict[str, Any]:
         """
-        Deletes a `Function` .
+        Deletes a `Function`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.delete_function)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#delete_function)
         """
     async def delete_graphql_api(self, *, apiId: str) -> Dict[str, Any]:
         """
         Deletes a `GraphqlApi` object.
@@ -349,14 +396,34 @@
     async def disassociate_api(self, *, domainName: str) -> Dict[str, Any]:
         """
         Removes an `ApiAssociation` object from a custom domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.disassociate_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#disassociate_api)
         """
+    async def disassociate_merged_graphql_api(
+        self, *, sourceApiIdentifier: str, associationId: str
+    ) -> DisassociateMergedGraphqlApiResponseTypeDef:
+        """
+        Deletes an association between a Merged API and source API using the source
+        API's identifier and the association ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.disassociate_merged_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#disassociate_merged_graphql_api)
+        """
+    async def disassociate_source_graphql_api(
+        self, *, mergedApiIdentifier: str, associationId: str
+    ) -> DisassociateSourceGraphqlApiResponseTypeDef:
+        """
+        Deletes an association between a Merged API and source API using the Merged
+        API's identifier and the association ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.disassociate_source_graphql_api)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#disassociate_source_graphql_api)
+        """
     async def evaluate_code(
         self, *, runtime: AppSyncRuntimeTypeDef, code: str, context: str, function: str = ...
     ) -> EvaluateCodeResponseTypeDef:
         """
         Evaluates the given code and returns the response.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.evaluate_code)
@@ -417,15 +484,15 @@
         Retrieves a custom `DomainName` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_domain_name)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_domain_name)
         """
     async def get_function(self, *, apiId: str, functionId: str) -> GetFunctionResponseTypeDef:
         """
-        Get a `Function` .
+        Get a `Function`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_function)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_function)
         """
     async def get_graphql_api(self, *, apiId: str) -> GetGraphqlApiResponseTypeDef:
         """
         Retrieves a `GraphqlApi` object.
@@ -456,14 +523,23 @@
     ) -> GetSchemaCreationStatusResponseTypeDef:
         """
         Retrieves the current status of a schema creation operation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_schema_creation_status)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_schema_creation_status)
         """
+    async def get_source_api_association(
+        self, *, mergedApiIdentifier: str, associationId: str
+    ) -> GetSourceApiAssociationResponseTypeDef:
+        """
+        Retrieves a `SourceApiAssociation` object.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_source_api_association)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#get_source_api_association)
+        """
     async def get_type(
         self, *, apiId: str, typeName: str, format: TypeDefinitionFormatType
     ) -> GetTypeResponseTypeDef:
         """
         Retrieves a `Type` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.get_type)
@@ -502,15 +578,20 @@
         """
         List multiple functions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_functions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_functions)
         """
     async def list_graphql_apis(
-        self, *, nextToken: str = ..., maxResults: int = ...
+        self,
+        *,
+        nextToken: str = ...,
+        maxResults: int = ...,
+        apiType: GraphQLApiTypeType = ...,
+        owner: OwnershipType = ...
     ) -> ListGraphqlApisResponseTypeDef:
         """
         Lists your GraphQL APIs.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_graphql_apis)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_graphql_apis)
         """
@@ -528,14 +609,23 @@
     ) -> ListResolversByFunctionResponseTypeDef:
         """
         List the resolvers that are associated with a specific function.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_resolvers_by_function)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_resolvers_by_function)
         """
+    async def list_source_api_associations(
+        self, *, apiId: str, nextToken: str = ..., maxResults: int = ...
+    ) -> ListSourceApiAssociationsResponseTypeDef:
+        """
+        Lists the `SourceApiAssociationSummary` data.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_source_api_associations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_source_api_associations)
+        """
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags for a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_tags_for_resource)
@@ -551,23 +641,47 @@
     ) -> ListTypesResponseTypeDef:
         """
         Lists the types for a given API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_types)
         """
+    async def list_types_by_association(
+        self,
+        *,
+        mergedApiIdentifier: str,
+        associationId: str,
+        format: TypeDefinitionFormatType,
+        nextToken: str = ...,
+        maxResults: int = ...
+    ) -> ListTypesByAssociationResponseTypeDef:
+        """
+        Lists `Type` objects by the source API association ID.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.list_types_by_association)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#list_types_by_association)
+        """
     async def start_schema_creation(
         self, *, apiId: str, definition: Union[str, bytes, IO[Any], StreamingBody]
     ) -> StartSchemaCreationResponseTypeDef:
         """
         Adds a new schema to your GraphQL API.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.start_schema_creation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#start_schema_creation)
         """
+    async def start_schema_merge(
+        self, *, associationId: str, mergedApiIdentifier: str
+    ) -> StartSchemaMergeResponseTypeDef:
+        """
+        Initiates a merge operation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.start_schema_merge)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#start_schema_merge)
+        """
     async def tag_resource(self, *, resourceArn: str, tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Tags a resource with user-supplied tags.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#tag_resource)
         """
@@ -661,15 +775,17 @@
         name: str,
         logConfig: LogConfigTypeDef = ...,
         authenticationType: AuthenticationTypeType = ...,
         userPoolConfig: UserPoolConfigTypeDef = ...,
         openIDConnectConfig: OpenIDConnectConfigTypeDef = ...,
         additionalAuthenticationProviders: Sequence[AdditionalAuthenticationProviderTypeDef] = ...,
         xrayEnabled: bool = ...,
-        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...
+        lambdaAuthorizerConfig: LambdaAuthorizerConfigTypeDef = ...,
+        mergedApiExecutionRoleArn: str = ...,
+        ownerContact: str = ...
     ) -> UpdateGraphqlApiResponseTypeDef:
         """
         Updates a `GraphqlApi` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_graphql_api)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#update_graphql_api)
         """
@@ -692,14 +808,29 @@
     ) -> UpdateResolverResponseTypeDef:
         """
         Updates a `Resolver` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_resolver)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#update_resolver)
         """
+    async def update_source_api_association(
+        self,
+        *,
+        associationId: str,
+        mergedApiIdentifier: str,
+        description: str = ...,
+        sourceApiAssociationConfig: SourceApiAssociationConfigTypeDef = ...
+    ) -> UpdateSourceApiAssociationResponseTypeDef:
+        """
+        Updates some of the configuration choices of a particular source API
+        association.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_source_api_association)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/client/#update_source_api_association)
+        """
     async def update_type(
         self, *, apiId: str, typeName: str, format: TypeDefinitionFormatType, definition: str = ...
     ) -> UpdateTypeResponseTypeDef:
         """
         Updates a `Type` object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Client.update_type)
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/literals.py` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -27,26 +27,31 @@
     "AuthenticationTypeType",
     "AuthorizationTypeType",
     "ConflictDetectionTypeType",
     "ConflictHandlerTypeType",
     "DataSourceTypeType",
     "DefaultActionType",
     "FieldLogLevelType",
+    "GraphQLApiTypeType",
+    "GraphQLApiVisibilityType",
     "ListApiKeysPaginatorName",
     "ListDataSourcesPaginatorName",
     "ListFunctionsPaginatorName",
     "ListGraphqlApisPaginatorName",
     "ListResolversByFunctionPaginatorName",
     "ListResolversPaginatorName",
     "ListTypesPaginatorName",
+    "MergeTypeType",
     "OutputTypeType",
+    "OwnershipType",
     "RelationalDatabaseSourceTypeType",
     "ResolverKindType",
     "RuntimeNameType",
     "SchemaStatusType",
+    "SourceApiAssociationStatusType",
     "TypeDefinitionFormatType",
     "AppSyncServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -86,28 +91,42 @@
     "AWS_LAMBDA",
     "HTTP",
     "NONE",
     "RELATIONAL_DATABASE",
 ]
 DefaultActionType = Literal["ALLOW", "DENY"]
 FieldLogLevelType = Literal["ALL", "ERROR", "NONE"]
+GraphQLApiTypeType = Literal["GRAPHQL", "MERGED"]
+GraphQLApiVisibilityType = Literal["GLOBAL", "PRIVATE"]
 ListApiKeysPaginatorName = Literal["list_api_keys"]
 ListDataSourcesPaginatorName = Literal["list_data_sources"]
 ListFunctionsPaginatorName = Literal["list_functions"]
 ListGraphqlApisPaginatorName = Literal["list_graphql_apis"]
 ListResolversByFunctionPaginatorName = Literal["list_resolvers_by_function"]
 ListResolversPaginatorName = Literal["list_resolvers"]
 ListTypesPaginatorName = Literal["list_types"]
+MergeTypeType = Literal["AUTO_MERGE", "MANUAL_MERGE"]
 OutputTypeType = Literal["JSON", "SDL"]
+OwnershipType = Literal["CURRENT_ACCOUNT", "OTHER_ACCOUNTS"]
 RelationalDatabaseSourceTypeType = Literal["RDS_HTTP_ENDPOINT"]
 ResolverKindType = Literal["PIPELINE", "UNIT"]
 RuntimeNameType = Literal["APPSYNC_JS"]
 SchemaStatusType = Literal[
     "ACTIVE", "DELETING", "FAILED", "NOT_APPLICABLE", "PROCESSING", "SUCCESS"
 ]
+SourceApiAssociationStatusType = Literal[
+    "AUTO_MERGE_SCHEDULE_FAILED",
+    "DELETION_FAILED",
+    "DELETION_IN_PROGRESS",
+    "DELETION_SCHEDULED",
+    "MERGE_FAILED",
+    "MERGE_IN_PROGRESS",
+    "MERGE_SCHEDULED",
+    "MERGE_SUCCESS",
+]
 TypeDefinitionFormatType = Literal["JSON", "SDL"]
 AppSyncServiceName = Literal["appsync"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -164,14 +183,15 @@
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
@@ -250,14 +270,15 @@
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
@@ -268,14 +289,15 @@
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
@@ -311,14 +333,15 @@
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
@@ -337,16 +360,19 @@
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
@@ -430,15 +456,17 @@
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
@@ -472,24 +500,28 @@
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
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/literals.pyi` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -26,26 +26,31 @@
     "AuthenticationTypeType",
     "AuthorizationTypeType",
     "ConflictDetectionTypeType",
     "ConflictHandlerTypeType",
     "DataSourceTypeType",
     "DefaultActionType",
     "FieldLogLevelType",
+    "GraphQLApiTypeType",
+    "GraphQLApiVisibilityType",
     "ListApiKeysPaginatorName",
     "ListDataSourcesPaginatorName",
     "ListFunctionsPaginatorName",
     "ListGraphqlApisPaginatorName",
     "ListResolversByFunctionPaginatorName",
     "ListResolversPaginatorName",
     "ListTypesPaginatorName",
+    "MergeTypeType",
     "OutputTypeType",
+    "OwnershipType",
     "RelationalDatabaseSourceTypeType",
     "ResolverKindType",
     "RuntimeNameType",
     "SchemaStatusType",
+    "SourceApiAssociationStatusType",
     "TypeDefinitionFormatType",
     "AppSyncServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
@@ -84,28 +89,42 @@
     "AWS_LAMBDA",
     "HTTP",
     "NONE",
     "RELATIONAL_DATABASE",
 ]
 DefaultActionType = Literal["ALLOW", "DENY"]
 FieldLogLevelType = Literal["ALL", "ERROR", "NONE"]
+GraphQLApiTypeType = Literal["GRAPHQL", "MERGED"]
+GraphQLApiVisibilityType = Literal["GLOBAL", "PRIVATE"]
 ListApiKeysPaginatorName = Literal["list_api_keys"]
 ListDataSourcesPaginatorName = Literal["list_data_sources"]
 ListFunctionsPaginatorName = Literal["list_functions"]
 ListGraphqlApisPaginatorName = Literal["list_graphql_apis"]
 ListResolversByFunctionPaginatorName = Literal["list_resolvers_by_function"]
 ListResolversPaginatorName = Literal["list_resolvers"]
 ListTypesPaginatorName = Literal["list_types"]
+MergeTypeType = Literal["AUTO_MERGE", "MANUAL_MERGE"]
 OutputTypeType = Literal["JSON", "SDL"]
+OwnershipType = Literal["CURRENT_ACCOUNT", "OTHER_ACCOUNTS"]
 RelationalDatabaseSourceTypeType = Literal["RDS_HTTP_ENDPOINT"]
 ResolverKindType = Literal["PIPELINE", "UNIT"]
 RuntimeNameType = Literal["APPSYNC_JS"]
 SchemaStatusType = Literal[
     "ACTIVE", "DELETING", "FAILED", "NOT_APPLICABLE", "PROCESSING", "SUCCESS"
 ]
+SourceApiAssociationStatusType = Literal[
+    "AUTO_MERGE_SCHEDULE_FAILED",
+    "DELETION_FAILED",
+    "DELETION_IN_PROGRESS",
+    "DELETION_SCHEDULED",
+    "MERGE_FAILED",
+    "MERGE_IN_PROGRESS",
+    "MERGE_SCHEDULED",
+    "MERGE_SUCCESS",
+]
 TypeDefinitionFormatType = Literal["JSON", "SDL"]
 AppSyncServiceName = Literal["appsync"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -162,14 +181,15 @@
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
@@ -248,14 +268,15 @@
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
@@ -266,14 +287,15 @@
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
@@ -309,14 +331,15 @@
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
@@ -335,16 +358,19 @@
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
@@ -428,15 +454,17 @@
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
@@ -470,24 +498,28 @@
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
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/paginator.py` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -28,38 +28,31 @@
         list_functions_paginator: ListFunctionsPaginator = client.get_paginator("list_functions")
         list_graphql_apis_paginator: ListGraphqlApisPaginator = client.get_paginator("list_graphql_apis")
         list_resolvers_paginator: ListResolversPaginator = client.get_paginator("list_resolvers")
         list_resolvers_by_function_paginator: ListResolversByFunctionPaginator = client.get_paginator("list_resolvers_by_function")
         list_types_paginator: ListTypesPaginator = client.get_paginator("list_types")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
-from .literals import TypeDefinitionFormatType
+from .literals import GraphQLApiTypeType, OwnershipType, TypeDefinitionFormatType
 from .type_defs import (
     ListApiKeysResponseTypeDef,
     ListDataSourcesResponseTypeDef,
     ListFunctionsResponseTypeDef,
     ListGraphqlApisResponseTypeDef,
     ListResolversByFunctionResponseTypeDef,
     ListResolversResponseTypeDef,
     ListTypesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApiKeysPaginator",
     "ListDataSourcesPaginator",
     "ListFunctionsPaginator",
     "ListGraphqlApisPaginator",
     "ListResolversPaginator",
     "ListResolversByFunctionPaginator",
@@ -80,90 +73,94 @@
 class ListApiKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListApiKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listapikeyspaginator)
     """
 
     def paginate(
-        self, *, apiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApiKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListApiKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listapikeyspaginator)
         """
 
 
 class ListDataSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListDataSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listdatasourcespaginator)
     """
 
     def paginate(
-        self, *, apiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListDataSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listdatasourcespaginator)
         """
 
 
 class ListFunctionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListFunctions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listfunctionspaginator)
     """
 
     def paginate(
-        self, *, apiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListFunctions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listfunctionspaginator)
         """
 
 
 class ListGraphqlApisPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListGraphqlApis)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listgraphqlapispaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        apiType: GraphQLApiTypeType = ...,
+        owner: OwnershipType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGraphqlApisResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListGraphqlApis.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listgraphqlapispaginator)
         """
 
 
 class ListResolversPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolvers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolverspaginator)
     """
 
     def paginate(
-        self, *, apiId: str, typeName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, typeName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolversResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolvers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolverspaginator)
         """
 
 
 class ListResolversByFunctionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolversByFunction)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolversbyfunctionpaginator)
     """
 
     def paginate(
-        self, *, apiId: str, functionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, functionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolversByFunctionResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolversByFunction.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolversbyfunctionpaginator)
         """
 
 
@@ -174,13 +171,13 @@
     """
 
     def paginate(
         self,
         *,
         apiId: str,
         format: TypeDefinitionFormatType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listtypespaginator)
         """
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/paginator.pyi` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/paginator.pyi`

 * *Files 17% similar despite different names*

```diff
@@ -28,37 +28,31 @@
         list_functions_paginator: ListFunctionsPaginator = client.get_paginator("list_functions")
         list_graphql_apis_paginator: ListGraphqlApisPaginator = client.get_paginator("list_graphql_apis")
         list_resolvers_paginator: ListResolversPaginator = client.get_paginator("list_resolvers")
         list_resolvers_by_function_paginator: ListResolversByFunctionPaginator = client.get_paginator("list_resolvers_by_function")
         list_types_paginator: ListTypesPaginator = client.get_paginator("list_types")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
-from .literals import TypeDefinitionFormatType
+from .literals import GraphQLApiTypeType, OwnershipType, TypeDefinitionFormatType
 from .type_defs import (
     ListApiKeysResponseTypeDef,
     ListDataSourcesResponseTypeDef,
     ListFunctionsResponseTypeDef,
     ListGraphqlApisResponseTypeDef,
     ListResolversByFunctionResponseTypeDef,
     ListResolversResponseTypeDef,
     ListTypesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApiKeysPaginator",
     "ListDataSourcesPaginator",
     "ListFunctionsPaginator",
     "ListGraphqlApisPaginator",
     "ListResolversPaginator",
     "ListResolversByFunctionPaginator",
@@ -76,85 +70,89 @@
 class ListApiKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListApiKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listapikeyspaginator)
     """
 
     def paginate(
-        self, *, apiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApiKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListApiKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listapikeyspaginator)
         """
 
 class ListDataSourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListDataSources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listdatasourcespaginator)
     """
 
     def paginate(
-        self, *, apiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListDataSources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listdatasourcespaginator)
         """
 
 class ListFunctionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListFunctions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listfunctionspaginator)
     """
 
     def paginate(
-        self, *, apiId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListFunctions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listfunctionspaginator)
         """
 
 class ListGraphqlApisPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListGraphqlApis)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listgraphqlapispaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        apiType: GraphQLApiTypeType = ...,
+        owner: OwnershipType = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGraphqlApisResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListGraphqlApis.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listgraphqlapispaginator)
         """
 
 class ListResolversPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolvers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolverspaginator)
     """
 
     def paginate(
-        self, *, apiId: str, typeName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, typeName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolversResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolvers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolverspaginator)
         """
 
 class ListResolversByFunctionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolversByFunction)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolversbyfunctionpaginator)
     """
 
     def paginate(
-        self, *, apiId: str, functionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, apiId: str, functionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResolversByFunctionResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListResolversByFunction.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listresolversbyfunctionpaginator)
         """
 
 class ListTypesPaginator(AioPaginator):
@@ -164,13 +162,13 @@
     """
 
     def paginate(
         self,
         *,
         apiId: str,
         format: TypeDefinitionFormatType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTypesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync.Paginator.ListTypes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/paginators/#listtypespaginator)
         """
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/type_defs.py` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/type_defs.py`

 * *Files 13% similar despite different names*

```diff
@@ -8,14 +8,15 @@
     ```python
     from types_aiobotocore_appsync.type_defs import CognitoUserPoolConfigTypeDef
 
     data: CognitoUserPoolConfigTypeDef = {...}
     ```
 """
 import sys
+from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     ApiCacheStatusType,
     ApiCacheTypeType,
@@ -23,17 +24,22 @@
     AssociationStatusType,
     AuthenticationTypeType,
     ConflictDetectionTypeType,
     ConflictHandlerTypeType,
     DataSourceTypeType,
     DefaultActionType,
     FieldLogLevelType,
+    GraphQLApiTypeType,
+    GraphQLApiVisibilityType,
+    MergeTypeType,
     OutputTypeType,
+    OwnershipType,
     ResolverKindType,
     SchemaStatusType,
+    SourceApiAssociationStatusType,
     TypeDefinitionFormatType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -48,15 +54,15 @@
     "LambdaAuthorizerConfigTypeDef",
     "OpenIDConnectConfigTypeDef",
     "ApiAssociationTypeDef",
     "ApiCacheTypeDef",
     "ApiKeyTypeDef",
     "AppSyncRuntimeTypeDef",
     "AssociateApiRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "SourceApiAssociationConfigTypeDef",
     "AwsIamConfigTypeDef",
     "CachingConfigTypeDef",
     "CodeErrorLocationTypeDef",
     "CreateApiCacheRequestRequestTypeDef",
     "CreateApiKeyRequestRequestTypeDef",
     "ElasticsearchDataSourceConfigTypeDef",
     "EventBridgeDataSourceConfigTypeDef",
@@ -75,84 +81,105 @@
     "DeleteDomainNameRequestRequestTypeDef",
     "DeleteFunctionRequestRequestTypeDef",
     "DeleteGraphqlApiRequestRequestTypeDef",
     "DeleteResolverRequestRequestTypeDef",
     "DeleteTypeRequestRequestTypeDef",
     "DeltaSyncConfigTypeDef",
     "DisassociateApiRequestRequestTypeDef",
+    "DisassociateMergedGraphqlApiRequestRequestTypeDef",
+    "DisassociateMergedGraphqlApiResponseTypeDef",
+    "DisassociateSourceGraphqlApiRequestRequestTypeDef",
+    "DisassociateSourceGraphqlApiResponseTypeDef",
     "ErrorDetailTypeDef",
     "EvaluateMappingTemplateRequestRequestTypeDef",
     "FlushApiCacheRequestRequestTypeDef",
     "GetApiAssociationRequestRequestTypeDef",
     "GetApiCacheRequestRequestTypeDef",
     "GetDataSourceRequestRequestTypeDef",
     "GetDomainNameRequestRequestTypeDef",
     "GetFunctionRequestRequestTypeDef",
     "GetGraphqlApiRequestRequestTypeDef",
     "GetIntrospectionSchemaRequestRequestTypeDef",
+    "GetIntrospectionSchemaResponseTypeDef",
     "GetResolverRequestRequestTypeDef",
     "GetSchemaCreationStatusRequestRequestTypeDef",
+    "GetSchemaCreationStatusResponseTypeDef",
+    "GetSourceApiAssociationRequestRequestTypeDef",
     "GetTypeRequestRequestTypeDef",
     "LambdaConflictHandlerConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApiKeysRequestListApiKeysPaginateTypeDef",
     "ListApiKeysRequestRequestTypeDef",
+    "ListDataSourcesRequestListDataSourcesPaginateTypeDef",
     "ListDataSourcesRequestRequestTypeDef",
     "ListDomainNamesRequestRequestTypeDef",
+    "ListFunctionsRequestListFunctionsPaginateTypeDef",
     "ListFunctionsRequestRequestTypeDef",
+    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
     "ListGraphqlApisRequestRequestTypeDef",
+    "ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
     "ListResolversByFunctionRequestRequestTypeDef",
+    "ListResolversRequestListResolversPaginateTypeDef",
     "ListResolversRequestRequestTypeDef",
+    "ListSourceApiAssociationsRequestRequestTypeDef",
+    "SourceApiAssociationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTypesByAssociationRequestRequestTypeDef",
+    "ListTypesRequestListTypesPaginateTypeDef",
     "ListTypesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "RdsHttpEndpointConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartSchemaCreationRequestRequestTypeDef",
+    "StartSchemaCreationResponseTypeDef",
+    "StartSchemaMergeRequestRequestTypeDef",
+    "StartSchemaMergeResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApiCacheRequestRequestTypeDef",
     "UpdateApiKeyRequestRequestTypeDef",
     "UpdateDomainNameRequestRequestTypeDef",
     "UpdateTypeRequestRequestTypeDef",
     "AdditionalAuthenticationProviderTypeDef",
-    "EvaluateCodeRequestRequestTypeDef",
     "AssociateApiResponseTypeDef",
-    "CreateApiCacheResponseTypeDef",
-    "CreateApiKeyResponseTypeDef",
     "GetApiAssociationResponseTypeDef",
+    "CreateApiCacheResponseTypeDef",
     "GetApiCacheResponseTypeDef",
-    "GetIntrospectionSchemaResponseTypeDef",
-    "GetSchemaCreationStatusResponseTypeDef",
-    "ListApiKeysResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartSchemaCreationResponseTypeDef",
     "UpdateApiCacheResponseTypeDef",
+    "CreateApiKeyResponseTypeDef",
+    "ListApiKeysResponseTypeDef",
     "UpdateApiKeyResponseTypeDef",
+    "EvaluateCodeRequestRequestTypeDef",
+    "AssociateMergedGraphqlApiRequestRequestTypeDef",
+    "AssociateSourceGraphqlApiRequestRequestTypeDef",
+    "SourceApiAssociationTypeDef",
+    "UpdateSourceApiAssociationRequestRequestTypeDef",
     "AuthorizationConfigTypeDef",
     "CodeErrorTypeDef",
     "CreateDomainNameResponseTypeDef",
     "GetDomainNameResponseTypeDef",
     "ListDomainNamesResponseTypeDef",
     "UpdateDomainNameResponseTypeDef",
     "CreateTypeResponseTypeDef",
     "GetTypeResponseTypeDef",
+    "ListTypesByAssociationResponseTypeDef",
     "ListTypesResponseTypeDef",
     "UpdateTypeResponseTypeDef",
     "DynamodbDataSourceConfigTypeDef",
     "EvaluateMappingTemplateResponseTypeDef",
     "SyncConfigTypeDef",
-    "ListApiKeysRequestListApiKeysPaginateTypeDef",
-    "ListDataSourcesRequestListDataSourcesPaginateTypeDef",
-    "ListFunctionsRequestListFunctionsPaginateTypeDef",
-    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
-    "ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
-    "ListResolversRequestListResolversPaginateTypeDef",
-    "ListTypesRequestListTypesPaginateTypeDef",
+    "ListSourceApiAssociationsResponseTypeDef",
     "RelationalDatabaseDataSourceConfigTypeDef",
     "CreateGraphqlApiRequestRequestTypeDef",
     "GraphqlApiTypeDef",
     "UpdateGraphqlApiRequestRequestTypeDef",
+    "AssociateMergedGraphqlApiResponseTypeDef",
+    "AssociateSourceGraphqlApiResponseTypeDef",
+    "GetSourceApiAssociationResponseTypeDef",
+    "UpdateSourceApiAssociationResponseTypeDef",
     "HttpDataSourceConfigTypeDef",
     "EvaluateCodeErrorDetailTypeDef",
     "CreateFunctionRequestRequestTypeDef",
     "CreateResolverRequestRequestTypeDef",
     "FunctionConfigurationTypeDef",
     "ResolverTypeDef",
     "UpdateFunctionRequestRequestTypeDef",
@@ -294,23 +321,20 @@
     "AssociateApiRequestRequestTypeDef",
     {
         "domainName": str,
         "apiId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+SourceApiAssociationConfigTypeDef = TypedDict(
+    "SourceApiAssociationConfigTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "mergeType": MergeTypeType,
     },
+    total=False,
 )
 
 AwsIamConfigTypeDef = TypedDict(
     "AwsIamConfigTypeDef",
     {
         "signingRegion": str,
         "signingServiceName": str,
@@ -603,14 +627,46 @@
 DisassociateApiRequestRequestTypeDef = TypedDict(
     "DisassociateApiRequestRequestTypeDef",
     {
         "domainName": str,
     },
 )
 
+DisassociateMergedGraphqlApiRequestRequestTypeDef = TypedDict(
+    "DisassociateMergedGraphqlApiRequestRequestTypeDef",
+    {
+        "sourceApiIdentifier": str,
+        "associationId": str,
+    },
+)
+
+DisassociateMergedGraphqlApiResponseTypeDef = TypedDict(
+    "DisassociateMergedGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DisassociateSourceGraphqlApiRequestRequestTypeDef = TypedDict(
+    "DisassociateSourceGraphqlApiRequestRequestTypeDef",
+    {
+        "mergedApiIdentifier": str,
+        "associationId": str,
+    },
+)
+
+DisassociateSourceGraphqlApiResponseTypeDef = TypedDict(
+    "DisassociateSourceGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ErrorDetailTypeDef = TypedDict(
     "ErrorDetailTypeDef",
     {
         "message": str,
     },
     total=False,
 )
@@ -693,14 +749,22 @@
 class GetIntrospectionSchemaRequestRequestTypeDef(
     _RequiredGetIntrospectionSchemaRequestRequestTypeDef,
     _OptionalGetIntrospectionSchemaRequestRequestTypeDef,
 ):
     pass
 
 
+GetIntrospectionSchemaResponseTypeDef = TypedDict(
+    "GetIntrospectionSchemaResponseTypeDef",
+    {
+        "schema": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResolverRequestRequestTypeDef = TypedDict(
     "GetResolverRequestRequestTypeDef",
     {
         "apiId": str,
         "typeName": str,
         "fieldName": str,
     },
@@ -709,14 +773,31 @@
 GetSchemaCreationStatusRequestRequestTypeDef = TypedDict(
     "GetSchemaCreationStatusRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 
+GetSchemaCreationStatusResponseTypeDef = TypedDict(
+    "GetSchemaCreationStatusResponseTypeDef",
+    {
+        "status": SchemaStatusType,
+        "details": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSourceApiAssociationRequestRequestTypeDef = TypedDict(
+    "GetSourceApiAssociationRequestRequestTypeDef",
+    {
+        "mergedApiIdentifier": str,
+        "associationId": str,
+    },
+)
+
 GetTypeRequestRequestTypeDef = TypedDict(
     "GetTypeRequestRequestTypeDef",
     {
         "apiId": str,
         "typeName": str,
         "format": TypeDefinitionFormatType,
     },
@@ -726,24 +807,36 @@
     "LambdaConflictHandlerConfigTypeDef",
     {
         "lambdaConflictHandlerArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
+    "_RequiredListApiKeysRequestListApiKeysPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "apiId": str,
+    },
+)
+_OptionalListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
+    "_OptionalListApiKeysRequestListApiKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListApiKeysRequestListApiKeysPaginateTypeDef(
+    _RequiredListApiKeysRequestListApiKeysPaginateTypeDef,
+    _OptionalListApiKeysRequestListApiKeysPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListApiKeysRequestRequestTypeDef = TypedDict(
     "_RequiredListApiKeysRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 _OptionalListApiKeysRequestRequestTypeDef = TypedDict(
@@ -758,14 +851,36 @@
 
 class ListApiKeysRequestRequestTypeDef(
     _RequiredListApiKeysRequestRequestTypeDef, _OptionalListApiKeysRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef",
+    {
+        "apiId": str,
+    },
+)
+_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDataSourcesRequestListDataSourcesPaginateTypeDef(
+    _RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef,
+    _OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDataSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSourcesRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 _OptionalListDataSourcesRequestRequestTypeDef = TypedDict(
@@ -789,14 +904,36 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionsRequestListFunctionsPaginateTypeDef",
+    {
+        "apiId": str,
+    },
+)
+_OptionalListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionsRequestListFunctionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFunctionsRequestListFunctionsPaginateTypeDef(
+    _RequiredListFunctionsRequestListFunctionsPaginateTypeDef,
+    _OptionalListFunctionsRequestListFunctionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFunctionsRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionsRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 _OptionalListFunctionsRequestRequestTypeDef = TypedDict(
@@ -811,23 +948,58 @@
 
 class ListFunctionsRequestRequestTypeDef(
     _RequiredListFunctionsRequestRequestTypeDef, _OptionalListFunctionsRequestRequestTypeDef
 ):
     pass
 
 
+ListGraphqlApisRequestListGraphqlApisPaginateTypeDef = TypedDict(
+    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
+    {
+        "apiType": GraphQLApiTypeType,
+        "owner": OwnershipType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGraphqlApisRequestRequestTypeDef = TypedDict(
     "ListGraphqlApisRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
+        "apiType": GraphQLApiTypeType,
+        "owner": OwnershipType,
+    },
+    total=False,
+)
+
+_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
+    "_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
+    {
+        "apiId": str,
+        "functionId": str,
+    },
+)
+_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
+    "_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef(
+    _RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
+    _OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResolversByFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredListResolversByFunctionRequestRequestTypeDef",
     {
         "apiId": str,
         "functionId": str,
     },
 )
@@ -844,14 +1016,37 @@
 class ListResolversByFunctionRequestRequestTypeDef(
     _RequiredListResolversByFunctionRequestRequestTypeDef,
     _OptionalListResolversByFunctionRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListResolversRequestListResolversPaginateTypeDef = TypedDict(
+    "_RequiredListResolversRequestListResolversPaginateTypeDef",
+    {
+        "apiId": str,
+        "typeName": str,
+    },
+)
+_OptionalListResolversRequestListResolversPaginateTypeDef = TypedDict(
+    "_OptionalListResolversRequestListResolversPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResolversRequestListResolversPaginateTypeDef(
+    _RequiredListResolversRequestListResolversPaginateTypeDef,
+    _OptionalListResolversRequestListResolversPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResolversRequestRequestTypeDef = TypedDict(
     "_RequiredListResolversRequestRequestTypeDef",
     {
         "apiId": str,
         "typeName": str,
     },
 )
@@ -867,21 +1062,114 @@
 
 class ListResolversRequestRequestTypeDef(
     _RequiredListResolversRequestRequestTypeDef, _OptionalListResolversRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListSourceApiAssociationsRequestRequestTypeDef = TypedDict(
+    "_RequiredListSourceApiAssociationsRequestRequestTypeDef",
+    {
+        "apiId": str,
+    },
+)
+_OptionalListSourceApiAssociationsRequestRequestTypeDef = TypedDict(
+    "_OptionalListSourceApiAssociationsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+
+class ListSourceApiAssociationsRequestRequestTypeDef(
+    _RequiredListSourceApiAssociationsRequestRequestTypeDef,
+    _OptionalListSourceApiAssociationsRequestRequestTypeDef,
+):
+    pass
+
+
+SourceApiAssociationSummaryTypeDef = TypedDict(
+    "SourceApiAssociationSummaryTypeDef",
+    {
+        "associationId": str,
+        "associationArn": str,
+        "sourceApiId": str,
+        "sourceApiArn": str,
+        "mergedApiId": str,
+        "mergedApiArn": str,
+        "description": str,
+    },
+    total=False,
+)
+
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
+_RequiredListTypesByAssociationRequestRequestTypeDef = TypedDict(
+    "_RequiredListTypesByAssociationRequestRequestTypeDef",
+    {
+        "mergedApiIdentifier": str,
+        "associationId": str,
+        "format": TypeDefinitionFormatType,
+    },
+)
+_OptionalListTypesByAssociationRequestRequestTypeDef = TypedDict(
+    "_OptionalListTypesByAssociationRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+
+class ListTypesByAssociationRequestRequestTypeDef(
+    _RequiredListTypesByAssociationRequestRequestTypeDef,
+    _OptionalListTypesByAssociationRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredListTypesRequestListTypesPaginateTypeDef = TypedDict(
+    "_RequiredListTypesRequestListTypesPaginateTypeDef",
+    {
+        "apiId": str,
+        "format": TypeDefinitionFormatType,
+    },
+)
+_OptionalListTypesRequestListTypesPaginateTypeDef = TypedDict(
+    "_OptionalListTypesRequestListTypesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTypesRequestListTypesPaginateTypeDef(
+    _RequiredListTypesRequestListTypesPaginateTypeDef,
+    _OptionalListTypesRequestListTypesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListTypesRequestRequestTypeDef",
     {
         "apiId": str,
         "format": TypeDefinitionFormatType,
     },
 )
@@ -897,34 +1185,79 @@
 
 class ListTypesRequestRequestTypeDef(
     _RequiredListTypesRequestRequestTypeDef, _OptionalListTypesRequestRequestTypeDef
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
 RdsHttpEndpointConfigTypeDef = TypedDict(
     "RdsHttpEndpointConfigTypeDef",
     {
         "awsRegion": str,
         "dbClusterIdentifier": str,
         "databaseName": str,
         "schema": str,
         "awsSecretStoreArn": str,
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
 StartSchemaCreationRequestRequestTypeDef = TypedDict(
     "StartSchemaCreationRequestRequestTypeDef",
     {
         "apiId": str,
         "definition": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
+StartSchemaCreationResponseTypeDef = TypedDict(
+    "StartSchemaCreationResponseTypeDef",
+    {
+        "status": SchemaStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSchemaMergeRequestRequestTypeDef = TypedDict(
+    "StartSchemaMergeRequestRequestTypeDef",
+    {
+        "associationId": str,
+        "mergedApiIdentifier": str,
+    },
+)
+
+StartSchemaMergeResponseTypeDef = TypedDict(
+    "StartSchemaMergeResponseTypeDef",
+    {
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
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
@@ -1021,134 +1354,191 @@
         "openIDConnectConfig": OpenIDConnectConfigTypeDef,
         "userPoolConfig": CognitoUserPoolConfigTypeDef,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
     },
     total=False,
 )
 
-_RequiredEvaluateCodeRequestRequestTypeDef = TypedDict(
-    "_RequiredEvaluateCodeRequestRequestTypeDef",
+AssociateApiResponseTypeDef = TypedDict(
+    "AssociateApiResponseTypeDef",
     {
-        "runtime": AppSyncRuntimeTypeDef,
-        "code": str,
-        "context": str,
+        "apiAssociation": ApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalEvaluateCodeRequestRequestTypeDef = TypedDict(
-    "_OptionalEvaluateCodeRequestRequestTypeDef",
+
+GetApiAssociationResponseTypeDef = TypedDict(
+    "GetApiAssociationResponseTypeDef",
     {
-        "function": str,
+        "apiAssociation": ApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
+CreateApiCacheResponseTypeDef = TypedDict(
+    "CreateApiCacheResponseTypeDef",
+    {
+        "apiCache": ApiCacheTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-class EvaluateCodeRequestRequestTypeDef(
-    _RequiredEvaluateCodeRequestRequestTypeDef, _OptionalEvaluateCodeRequestRequestTypeDef
-):
-    pass
-
-
-AssociateApiResponseTypeDef = TypedDict(
-    "AssociateApiResponseTypeDef",
+GetApiCacheResponseTypeDef = TypedDict(
+    "GetApiCacheResponseTypeDef",
     {
-        "apiAssociation": ApiAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "apiCache": ApiCacheTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateApiCacheResponseTypeDef = TypedDict(
-    "CreateApiCacheResponseTypeDef",
+UpdateApiCacheResponseTypeDef = TypedDict(
+    "UpdateApiCacheResponseTypeDef",
     {
         "apiCache": ApiCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateApiKeyResponseTypeDef = TypedDict(
     "CreateApiKeyResponseTypeDef",
     {
         "apiKey": ApiKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetApiAssociationResponseTypeDef = TypedDict(
-    "GetApiAssociationResponseTypeDef",
+ListApiKeysResponseTypeDef = TypedDict(
+    "ListApiKeysResponseTypeDef",
     {
-        "apiAssociation": ApiAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "apiKeys": List[ApiKeyTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetApiCacheResponseTypeDef = TypedDict(
-    "GetApiCacheResponseTypeDef",
+UpdateApiKeyResponseTypeDef = TypedDict(
+    "UpdateApiKeyResponseTypeDef",
     {
-        "apiCache": ApiCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "apiKey": ApiKeyTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetIntrospectionSchemaResponseTypeDef = TypedDict(
-    "GetIntrospectionSchemaResponseTypeDef",
+_RequiredEvaluateCodeRequestRequestTypeDef = TypedDict(
+    "_RequiredEvaluateCodeRequestRequestTypeDef",
     {
-        "schema": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "runtime": AppSyncRuntimeTypeDef,
+        "code": str,
+        "context": str,
     },
 )
-
-GetSchemaCreationStatusResponseTypeDef = TypedDict(
-    "GetSchemaCreationStatusResponseTypeDef",
+_OptionalEvaluateCodeRequestRequestTypeDef = TypedDict(
+    "_OptionalEvaluateCodeRequestRequestTypeDef",
     {
-        "status": SchemaStatusType,
-        "details": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "function": str,
     },
+    total=False,
 )
 
-ListApiKeysResponseTypeDef = TypedDict(
-    "ListApiKeysResponseTypeDef",
+
+class EvaluateCodeRequestRequestTypeDef(
+    _RequiredEvaluateCodeRequestRequestTypeDef, _OptionalEvaluateCodeRequestRequestTypeDef
+):
+    pass
+
+
+_RequiredAssociateMergedGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_RequiredAssociateMergedGraphqlApiRequestRequestTypeDef",
     {
-        "apiKeys": List[ApiKeyTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sourceApiIdentifier": str,
+        "mergedApiIdentifier": str,
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_OptionalAssociateMergedGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_OptionalAssociateMergedGraphqlApiRequestRequestTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
     },
+    total=False,
 )
 
-StartSchemaCreationResponseTypeDef = TypedDict(
-    "StartSchemaCreationResponseTypeDef",
+
+class AssociateMergedGraphqlApiRequestRequestTypeDef(
+    _RequiredAssociateMergedGraphqlApiRequestRequestTypeDef,
+    _OptionalAssociateMergedGraphqlApiRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredAssociateSourceGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_RequiredAssociateSourceGraphqlApiRequestRequestTypeDef",
     {
-        "status": SchemaStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "mergedApiIdentifier": str,
+        "sourceApiIdentifier": str,
     },
 )
+_OptionalAssociateSourceGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_OptionalAssociateSourceGraphqlApiRequestRequestTypeDef",
+    {
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
+    },
+    total=False,
+)
 
-UpdateApiCacheResponseTypeDef = TypedDict(
-    "UpdateApiCacheResponseTypeDef",
+
+class AssociateSourceGraphqlApiRequestRequestTypeDef(
+    _RequiredAssociateSourceGraphqlApiRequestRequestTypeDef,
+    _OptionalAssociateSourceGraphqlApiRequestRequestTypeDef,
+):
+    pass
+
+
+SourceApiAssociationTypeDef = TypedDict(
+    "SourceApiAssociationTypeDef",
     {
-        "apiCache": ApiCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "associationId": str,
+        "associationArn": str,
+        "sourceApiId": str,
+        "sourceApiArn": str,
+        "mergedApiArn": str,
+        "mergedApiId": str,
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
+        "sourceApiAssociationStatusDetail": str,
+        "lastSuccessfulMergeDate": datetime,
     },
+    total=False,
 )
 
-UpdateApiKeyResponseTypeDef = TypedDict(
-    "UpdateApiKeyResponseTypeDef",
+_RequiredUpdateSourceApiAssociationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateSourceApiAssociationRequestRequestTypeDef",
     {
-        "apiKey": ApiKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "associationId": str,
+        "mergedApiIdentifier": str,
     },
 )
+_OptionalUpdateSourceApiAssociationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateSourceApiAssociationRequestRequestTypeDef",
+    {
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateSourceApiAssociationRequestRequestTypeDef(
+    _RequiredUpdateSourceApiAssociationRequestRequestTypeDef,
+    _OptionalUpdateSourceApiAssociationRequestRequestTypeDef,
+):
+    pass
+
 
 _RequiredAuthorizationConfigTypeDef = TypedDict(
     "_RequiredAuthorizationConfigTypeDef",
     {
         "authorizationType": Literal["AWS_IAM"],
     },
 )
@@ -1177,73 +1567,82 @@
     total=False,
 )
 
 CreateDomainNameResponseTypeDef = TypedDict(
     "CreateDomainNameResponseTypeDef",
     {
         "domainNameConfig": DomainNameConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainNameResponseTypeDef = TypedDict(
     "GetDomainNameResponseTypeDef",
     {
         "domainNameConfig": DomainNameConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainNamesResponseTypeDef = TypedDict(
     "ListDomainNamesResponseTypeDef",
     {
         "domainNameConfigs": List[DomainNameConfigTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainNameResponseTypeDef = TypedDict(
     "UpdateDomainNameResponseTypeDef",
     {
         "domainNameConfig": DomainNameConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTypeResponseTypeDef = TypedDict(
     "CreateTypeResponseTypeDef",
     {
         "type": TypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTypeResponseTypeDef = TypedDict(
     "GetTypeResponseTypeDef",
     {
         "type": TypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTypesByAssociationResponseTypeDef = TypedDict(
+    "ListTypesByAssociationResponseTypeDef",
+    {
+        "types": List[TypeTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTypesResponseTypeDef = TypedDict(
     "ListTypesResponseTypeDef",
     {
         "types": List[TypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTypeResponseTypeDef = TypedDict(
     "UpdateTypeResponseTypeDef",
     {
         "type": TypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDynamodbDataSourceConfigTypeDef = TypedDict(
     "_RequiredDynamodbDataSourceConfigTypeDef",
     {
         "tableName": str,
@@ -1269,171 +1668,37 @@
 
 EvaluateMappingTemplateResponseTypeDef = TypedDict(
     "EvaluateMappingTemplateResponseTypeDef",
     {
         "evaluationResult": str,
         "error": ErrorDetailTypeDef,
         "logs": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SyncConfigTypeDef = TypedDict(
     "SyncConfigTypeDef",
     {
         "conflictHandler": ConflictHandlerTypeType,
         "conflictDetection": ConflictDetectionTypeType,
         "lambdaConflictHandlerConfig": LambdaConflictHandlerConfigTypeDef,
     },
     total=False,
 )
 
-_RequiredListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
-    "_RequiredListApiKeysRequestListApiKeysPaginateTypeDef",
+ListSourceApiAssociationsResponseTypeDef = TypedDict(
+    "ListSourceApiAssociationsResponseTypeDef",
     {
-        "apiId": str,
-    },
-)
-_OptionalListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
-    "_OptionalListApiKeysRequestListApiKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListApiKeysRequestListApiKeysPaginateTypeDef(
-    _RequiredListApiKeysRequestListApiKeysPaginateTypeDef,
-    _OptionalListApiKeysRequestListApiKeysPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef",
-    {
-        "apiId": str,
-    },
-)
-_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDataSourcesRequestListDataSourcesPaginateTypeDef(
-    _RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef,
-    _OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionsRequestListFunctionsPaginateTypeDef",
-    {
-        "apiId": str,
-    },
-)
-_OptionalListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionsRequestListFunctionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFunctionsRequestListFunctionsPaginateTypeDef(
-    _RequiredListFunctionsRequestListFunctionsPaginateTypeDef,
-    _OptionalListFunctionsRequestListFunctionsPaginateTypeDef,
-):
-    pass
-
-
-ListGraphqlApisRequestListGraphqlApisPaginateTypeDef = TypedDict(
-    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
-    "_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
-    {
-        "apiId": str,
-        "functionId": str,
-    },
-)
-_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
-    "_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef(
-    _RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
-    _OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListResolversRequestListResolversPaginateTypeDef = TypedDict(
-    "_RequiredListResolversRequestListResolversPaginateTypeDef",
-    {
-        "apiId": str,
-        "typeName": str,
-    },
-)
-_OptionalListResolversRequestListResolversPaginateTypeDef = TypedDict(
-    "_OptionalListResolversRequestListResolversPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListResolversRequestListResolversPaginateTypeDef(
-    _RequiredListResolversRequestListResolversPaginateTypeDef,
-    _OptionalListResolversRequestListResolversPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTypesRequestListTypesPaginateTypeDef = TypedDict(
-    "_RequiredListTypesRequestListTypesPaginateTypeDef",
-    {
-        "apiId": str,
-        "format": TypeDefinitionFormatType,
-    },
-)
-_OptionalListTypesRequestListTypesPaginateTypeDef = TypedDict(
-    "_OptionalListTypesRequestListTypesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "sourceApiAssociationSummaries": List[SourceApiAssociationSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListTypesRequestListTypesPaginateTypeDef(
-    _RequiredListTypesRequestListTypesPaginateTypeDef,
-    _OptionalListTypesRequestListTypesPaginateTypeDef,
-):
-    pass
-
-
 RelationalDatabaseDataSourceConfigTypeDef = TypedDict(
     "RelationalDatabaseDataSourceConfigTypeDef",
     {
         "relationalDatabaseSourceType": Literal["RDS_HTTP_ENDPOINT"],
         "rdsHttpEndpointConfig": RdsHttpEndpointConfigTypeDef,
     },
     total=False,
@@ -1452,14 +1717,18 @@
         "logConfig": LogConfigTypeDef,
         "userPoolConfig": UserPoolConfigTypeDef,
         "openIDConnectConfig": OpenIDConnectConfigTypeDef,
         "tags": Mapping[str, str],
         "additionalAuthenticationProviders": Sequence[AdditionalAuthenticationProviderTypeDef],
         "xrayEnabled": bool,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
+        "visibility": GraphQLApiVisibilityType,
+        "apiType": GraphQLApiTypeType,
+        "mergedApiExecutionRoleArn": str,
+        "ownerContact": str,
     },
     total=False,
 )
 
 
 class CreateGraphqlApiRequestRequestTypeDef(
     _RequiredCreateGraphqlApiRequestRequestTypeDef, _OptionalCreateGraphqlApiRequestRequestTypeDef
@@ -1479,14 +1748,20 @@
         "arn": str,
         "uris": Dict[str, str],
         "tags": Dict[str, str],
         "additionalAuthenticationProviders": List[AdditionalAuthenticationProviderTypeDef],
         "xrayEnabled": bool,
         "wafWebAclArn": str,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
+        "dns": Dict[str, str],
+        "visibility": GraphQLApiVisibilityType,
+        "apiType": GraphQLApiTypeType,
+        "mergedApiExecutionRoleArn": str,
+        "owner": str,
+        "ownerContact": str,
     },
     total=False,
 )
 
 _RequiredUpdateGraphqlApiRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateGraphqlApiRequestRequestTypeDef",
     {
@@ -1500,25 +1775,59 @@
         "logConfig": LogConfigTypeDef,
         "authenticationType": AuthenticationTypeType,
         "userPoolConfig": UserPoolConfigTypeDef,
         "openIDConnectConfig": OpenIDConnectConfigTypeDef,
         "additionalAuthenticationProviders": Sequence[AdditionalAuthenticationProviderTypeDef],
         "xrayEnabled": bool,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
+        "mergedApiExecutionRoleArn": str,
+        "ownerContact": str,
     },
     total=False,
 )
 
 
 class UpdateGraphqlApiRequestRequestTypeDef(
     _RequiredUpdateGraphqlApiRequestRequestTypeDef, _OptionalUpdateGraphqlApiRequestRequestTypeDef
 ):
     pass
 
 
+AssociateMergedGraphqlApiResponseTypeDef = TypedDict(
+    "AssociateMergedGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociateSourceGraphqlApiResponseTypeDef = TypedDict(
+    "AssociateSourceGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSourceApiAssociationResponseTypeDef = TypedDict(
+    "GetSourceApiAssociationResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateSourceApiAssociationResponseTypeDef = TypedDict(
+    "UpdateSourceApiAssociationResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HttpDataSourceConfigTypeDef = TypedDict(
     "HttpDataSourceConfigTypeDef",
     {
         "endpoint": str,
         "authorizationConfig": AuthorizationConfigTypeDef,
     },
     total=False,
@@ -1697,40 +2006,40 @@
     pass
 
 
 CreateGraphqlApiResponseTypeDef = TypedDict(
     "CreateGraphqlApiResponseTypeDef",
     {
         "graphqlApi": GraphqlApiTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGraphqlApiResponseTypeDef = TypedDict(
     "GetGraphqlApiResponseTypeDef",
     {
         "graphqlApi": GraphqlApiTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGraphqlApisResponseTypeDef = TypedDict(
     "ListGraphqlApisResponseTypeDef",
     {
         "graphqlApis": List[GraphqlApiTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGraphqlApiResponseTypeDef = TypedDict(
     "UpdateGraphqlApiResponseTypeDef",
     {
         "graphqlApi": GraphqlApiTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceRequestRequestTypeDef",
     {
         "apiId": str,
@@ -1813,118 +2122,118 @@
 
 EvaluateCodeResponseTypeDef = TypedDict(
     "EvaluateCodeResponseTypeDef",
     {
         "evaluationResult": str,
         "error": EvaluateCodeErrorDetailTypeDef,
         "logs": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFunctionResponseTypeDef = TypedDict(
     "CreateFunctionResponseTypeDef",
     {
         "functionConfiguration": FunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFunctionResponseTypeDef = TypedDict(
     "GetFunctionResponseTypeDef",
     {
         "functionConfiguration": FunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionsResponseTypeDef = TypedDict(
     "ListFunctionsResponseTypeDef",
     {
         "functions": List[FunctionConfigurationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFunctionResponseTypeDef = TypedDict(
     "UpdateFunctionResponseTypeDef",
     {
         "functionConfiguration": FunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResolverResponseTypeDef = TypedDict(
     "CreateResolverResponseTypeDef",
     {
         "resolver": ResolverTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverResponseTypeDef = TypedDict(
     "GetResolverResponseTypeDef",
     {
         "resolver": ResolverTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolversByFunctionResponseTypeDef = TypedDict(
     "ListResolversByFunctionResponseTypeDef",
     {
         "resolvers": List[ResolverTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolversResponseTypeDef = TypedDict(
     "ListResolversResponseTypeDef",
     {
         "resolvers": List[ResolverTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverResponseTypeDef = TypedDict(
     "UpdateResolverResponseTypeDef",
     {
         "resolver": ResolverTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDataSourceResponseTypeDef = TypedDict(
     "CreateDataSourceResponseTypeDef",
     {
         "dataSource": DataSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataSourceResponseTypeDef = TypedDict(
     "GetDataSourceResponseTypeDef",
     {
         "dataSource": DataSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataSourcesResponseTypeDef = TypedDict(
     "ListDataSourcesResponseTypeDef",
     {
         "dataSources": List[DataSourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDataSourceResponseTypeDef = TypedDict(
     "UpdateDataSourceResponseTypeDef",
     {
         "dataSource": DataSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync/type_defs.pyi` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync/type_defs.pyi`

 * *Files 16% similar despite different names*

```diff
@@ -8,14 +8,15 @@
     ```python
     from types_aiobotocore_appsync.type_defs import CognitoUserPoolConfigTypeDef
 
     data: CognitoUserPoolConfigTypeDef = {...}
     ```
 """
 import sys
+from datetime import datetime
 from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     ApiCacheStatusType,
     ApiCacheTypeType,
@@ -23,17 +24,22 @@
     AssociationStatusType,
     AuthenticationTypeType,
     ConflictDetectionTypeType,
     ConflictHandlerTypeType,
     DataSourceTypeType,
     DefaultActionType,
     FieldLogLevelType,
+    GraphQLApiTypeType,
+    GraphQLApiVisibilityType,
+    MergeTypeType,
     OutputTypeType,
+    OwnershipType,
     ResolverKindType,
     SchemaStatusType,
+    SourceApiAssociationStatusType,
     TypeDefinitionFormatType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -47,15 +53,15 @@
     "LambdaAuthorizerConfigTypeDef",
     "OpenIDConnectConfigTypeDef",
     "ApiAssociationTypeDef",
     "ApiCacheTypeDef",
     "ApiKeyTypeDef",
     "AppSyncRuntimeTypeDef",
     "AssociateApiRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "SourceApiAssociationConfigTypeDef",
     "AwsIamConfigTypeDef",
     "CachingConfigTypeDef",
     "CodeErrorLocationTypeDef",
     "CreateApiCacheRequestRequestTypeDef",
     "CreateApiKeyRequestRequestTypeDef",
     "ElasticsearchDataSourceConfigTypeDef",
     "EventBridgeDataSourceConfigTypeDef",
@@ -74,84 +80,105 @@
     "DeleteDomainNameRequestRequestTypeDef",
     "DeleteFunctionRequestRequestTypeDef",
     "DeleteGraphqlApiRequestRequestTypeDef",
     "DeleteResolverRequestRequestTypeDef",
     "DeleteTypeRequestRequestTypeDef",
     "DeltaSyncConfigTypeDef",
     "DisassociateApiRequestRequestTypeDef",
+    "DisassociateMergedGraphqlApiRequestRequestTypeDef",
+    "DisassociateMergedGraphqlApiResponseTypeDef",
+    "DisassociateSourceGraphqlApiRequestRequestTypeDef",
+    "DisassociateSourceGraphqlApiResponseTypeDef",
     "ErrorDetailTypeDef",
     "EvaluateMappingTemplateRequestRequestTypeDef",
     "FlushApiCacheRequestRequestTypeDef",
     "GetApiAssociationRequestRequestTypeDef",
     "GetApiCacheRequestRequestTypeDef",
     "GetDataSourceRequestRequestTypeDef",
     "GetDomainNameRequestRequestTypeDef",
     "GetFunctionRequestRequestTypeDef",
     "GetGraphqlApiRequestRequestTypeDef",
     "GetIntrospectionSchemaRequestRequestTypeDef",
+    "GetIntrospectionSchemaResponseTypeDef",
     "GetResolverRequestRequestTypeDef",
     "GetSchemaCreationStatusRequestRequestTypeDef",
+    "GetSchemaCreationStatusResponseTypeDef",
+    "GetSourceApiAssociationRequestRequestTypeDef",
     "GetTypeRequestRequestTypeDef",
     "LambdaConflictHandlerConfigTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApiKeysRequestListApiKeysPaginateTypeDef",
     "ListApiKeysRequestRequestTypeDef",
+    "ListDataSourcesRequestListDataSourcesPaginateTypeDef",
     "ListDataSourcesRequestRequestTypeDef",
     "ListDomainNamesRequestRequestTypeDef",
+    "ListFunctionsRequestListFunctionsPaginateTypeDef",
     "ListFunctionsRequestRequestTypeDef",
+    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
     "ListGraphqlApisRequestRequestTypeDef",
+    "ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
     "ListResolversByFunctionRequestRequestTypeDef",
+    "ListResolversRequestListResolversPaginateTypeDef",
     "ListResolversRequestRequestTypeDef",
+    "ListSourceApiAssociationsRequestRequestTypeDef",
+    "SourceApiAssociationSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "ListTypesByAssociationRequestRequestTypeDef",
+    "ListTypesRequestListTypesPaginateTypeDef",
     "ListTypesRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "RdsHttpEndpointConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "StartSchemaCreationRequestRequestTypeDef",
+    "StartSchemaCreationResponseTypeDef",
+    "StartSchemaMergeRequestRequestTypeDef",
+    "StartSchemaMergeResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateApiCacheRequestRequestTypeDef",
     "UpdateApiKeyRequestRequestTypeDef",
     "UpdateDomainNameRequestRequestTypeDef",
     "UpdateTypeRequestRequestTypeDef",
     "AdditionalAuthenticationProviderTypeDef",
-    "EvaluateCodeRequestRequestTypeDef",
     "AssociateApiResponseTypeDef",
-    "CreateApiCacheResponseTypeDef",
-    "CreateApiKeyResponseTypeDef",
     "GetApiAssociationResponseTypeDef",
+    "CreateApiCacheResponseTypeDef",
     "GetApiCacheResponseTypeDef",
-    "GetIntrospectionSchemaResponseTypeDef",
-    "GetSchemaCreationStatusResponseTypeDef",
-    "ListApiKeysResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "StartSchemaCreationResponseTypeDef",
     "UpdateApiCacheResponseTypeDef",
+    "CreateApiKeyResponseTypeDef",
+    "ListApiKeysResponseTypeDef",
     "UpdateApiKeyResponseTypeDef",
+    "EvaluateCodeRequestRequestTypeDef",
+    "AssociateMergedGraphqlApiRequestRequestTypeDef",
+    "AssociateSourceGraphqlApiRequestRequestTypeDef",
+    "SourceApiAssociationTypeDef",
+    "UpdateSourceApiAssociationRequestRequestTypeDef",
     "AuthorizationConfigTypeDef",
     "CodeErrorTypeDef",
     "CreateDomainNameResponseTypeDef",
     "GetDomainNameResponseTypeDef",
     "ListDomainNamesResponseTypeDef",
     "UpdateDomainNameResponseTypeDef",
     "CreateTypeResponseTypeDef",
     "GetTypeResponseTypeDef",
+    "ListTypesByAssociationResponseTypeDef",
     "ListTypesResponseTypeDef",
     "UpdateTypeResponseTypeDef",
     "DynamodbDataSourceConfigTypeDef",
     "EvaluateMappingTemplateResponseTypeDef",
     "SyncConfigTypeDef",
-    "ListApiKeysRequestListApiKeysPaginateTypeDef",
-    "ListDataSourcesRequestListDataSourcesPaginateTypeDef",
-    "ListFunctionsRequestListFunctionsPaginateTypeDef",
-    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
-    "ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
-    "ListResolversRequestListResolversPaginateTypeDef",
-    "ListTypesRequestListTypesPaginateTypeDef",
+    "ListSourceApiAssociationsResponseTypeDef",
     "RelationalDatabaseDataSourceConfigTypeDef",
     "CreateGraphqlApiRequestRequestTypeDef",
     "GraphqlApiTypeDef",
     "UpdateGraphqlApiRequestRequestTypeDef",
+    "AssociateMergedGraphqlApiResponseTypeDef",
+    "AssociateSourceGraphqlApiResponseTypeDef",
+    "GetSourceApiAssociationResponseTypeDef",
+    "UpdateSourceApiAssociationResponseTypeDef",
     "HttpDataSourceConfigTypeDef",
     "EvaluateCodeErrorDetailTypeDef",
     "CreateFunctionRequestRequestTypeDef",
     "CreateResolverRequestRequestTypeDef",
     "FunctionConfigurationTypeDef",
     "ResolverTypeDef",
     "UpdateFunctionRequestRequestTypeDef",
@@ -287,23 +314,20 @@
     "AssociateApiRequestRequestTypeDef",
     {
         "domainName": str,
         "apiId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+SourceApiAssociationConfigTypeDef = TypedDict(
+    "SourceApiAssociationConfigTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "mergeType": MergeTypeType,
     },
+    total=False,
 )
 
 AwsIamConfigTypeDef = TypedDict(
     "AwsIamConfigTypeDef",
     {
         "signingRegion": str,
         "signingServiceName": str,
@@ -584,14 +608,46 @@
 DisassociateApiRequestRequestTypeDef = TypedDict(
     "DisassociateApiRequestRequestTypeDef",
     {
         "domainName": str,
     },
 )
 
+DisassociateMergedGraphqlApiRequestRequestTypeDef = TypedDict(
+    "DisassociateMergedGraphqlApiRequestRequestTypeDef",
+    {
+        "sourceApiIdentifier": str,
+        "associationId": str,
+    },
+)
+
+DisassociateMergedGraphqlApiResponseTypeDef = TypedDict(
+    "DisassociateMergedGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DisassociateSourceGraphqlApiRequestRequestTypeDef = TypedDict(
+    "DisassociateSourceGraphqlApiRequestRequestTypeDef",
+    {
+        "mergedApiIdentifier": str,
+        "associationId": str,
+    },
+)
+
+DisassociateSourceGraphqlApiResponseTypeDef = TypedDict(
+    "DisassociateSourceGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ErrorDetailTypeDef = TypedDict(
     "ErrorDetailTypeDef",
     {
         "message": str,
     },
     total=False,
 )
@@ -672,14 +728,22 @@
 
 class GetIntrospectionSchemaRequestRequestTypeDef(
     _RequiredGetIntrospectionSchemaRequestRequestTypeDef,
     _OptionalGetIntrospectionSchemaRequestRequestTypeDef,
 ):
     pass
 
+GetIntrospectionSchemaResponseTypeDef = TypedDict(
+    "GetIntrospectionSchemaResponseTypeDef",
+    {
+        "schema": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResolverRequestRequestTypeDef = TypedDict(
     "GetResolverRequestRequestTypeDef",
     {
         "apiId": str,
         "typeName": str,
         "fieldName": str,
     },
@@ -688,14 +752,31 @@
 GetSchemaCreationStatusRequestRequestTypeDef = TypedDict(
     "GetSchemaCreationStatusRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 
+GetSchemaCreationStatusResponseTypeDef = TypedDict(
+    "GetSchemaCreationStatusResponseTypeDef",
+    {
+        "status": SchemaStatusType,
+        "details": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSourceApiAssociationRequestRequestTypeDef = TypedDict(
+    "GetSourceApiAssociationRequestRequestTypeDef",
+    {
+        "mergedApiIdentifier": str,
+        "associationId": str,
+    },
+)
+
 GetTypeRequestRequestTypeDef = TypedDict(
     "GetTypeRequestRequestTypeDef",
     {
         "apiId": str,
         "typeName": str,
         "format": TypeDefinitionFormatType,
     },
@@ -705,24 +786,34 @@
     "LambdaConflictHandlerConfigTypeDef",
     {
         "lambdaConflictHandlerArn": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
+    "_RequiredListApiKeysRequestListApiKeysPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "apiId": str,
+    },
+)
+_OptionalListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
+    "_OptionalListApiKeysRequestListApiKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListApiKeysRequestListApiKeysPaginateTypeDef(
+    _RequiredListApiKeysRequestListApiKeysPaginateTypeDef,
+    _OptionalListApiKeysRequestListApiKeysPaginateTypeDef,
+):
+    pass
+
 _RequiredListApiKeysRequestRequestTypeDef = TypedDict(
     "_RequiredListApiKeysRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 _OptionalListApiKeysRequestRequestTypeDef = TypedDict(
@@ -735,14 +826,34 @@
 )
 
 class ListApiKeysRequestRequestTypeDef(
     _RequiredListApiKeysRequestRequestTypeDef, _OptionalListApiKeysRequestRequestTypeDef
 ):
     pass
 
+_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef",
+    {
+        "apiId": str,
+    },
+)
+_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDataSourcesRequestListDataSourcesPaginateTypeDef(
+    _RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef,
+    _OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDataSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSourcesRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 _OptionalListDataSourcesRequestRequestTypeDef = TypedDict(
@@ -764,14 +875,34 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionsRequestListFunctionsPaginateTypeDef",
+    {
+        "apiId": str,
+    },
+)
+_OptionalListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionsRequestListFunctionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFunctionsRequestListFunctionsPaginateTypeDef(
+    _RequiredListFunctionsRequestListFunctionsPaginateTypeDef,
+    _OptionalListFunctionsRequestListFunctionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListFunctionsRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionsRequestRequestTypeDef",
     {
         "apiId": str,
     },
 )
 _OptionalListFunctionsRequestRequestTypeDef = TypedDict(
@@ -784,23 +915,56 @@
 )
 
 class ListFunctionsRequestRequestTypeDef(
     _RequiredListFunctionsRequestRequestTypeDef, _OptionalListFunctionsRequestRequestTypeDef
 ):
     pass
 
+ListGraphqlApisRequestListGraphqlApisPaginateTypeDef = TypedDict(
+    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
+    {
+        "apiType": GraphQLApiTypeType,
+        "owner": OwnershipType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGraphqlApisRequestRequestTypeDef = TypedDict(
     "ListGraphqlApisRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
+        "apiType": GraphQLApiTypeType,
+        "owner": OwnershipType,
+    },
+    total=False,
+)
+
+_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
+    "_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
+    {
+        "apiId": str,
+        "functionId": str,
+    },
+)
+_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
+    "_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef(
+    _RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
+    _OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
+):
+    pass
+
 _RequiredListResolversByFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredListResolversByFunctionRequestRequestTypeDef",
     {
         "apiId": str,
         "functionId": str,
     },
 )
@@ -815,14 +979,35 @@
 
 class ListResolversByFunctionRequestRequestTypeDef(
     _RequiredListResolversByFunctionRequestRequestTypeDef,
     _OptionalListResolversByFunctionRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListResolversRequestListResolversPaginateTypeDef = TypedDict(
+    "_RequiredListResolversRequestListResolversPaginateTypeDef",
+    {
+        "apiId": str,
+        "typeName": str,
+    },
+)
+_OptionalListResolversRequestListResolversPaginateTypeDef = TypedDict(
+    "_OptionalListResolversRequestListResolversPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResolversRequestListResolversPaginateTypeDef(
+    _RequiredListResolversRequestListResolversPaginateTypeDef,
+    _OptionalListResolversRequestListResolversPaginateTypeDef,
+):
+    pass
+
 _RequiredListResolversRequestRequestTypeDef = TypedDict(
     "_RequiredListResolversRequestRequestTypeDef",
     {
         "apiId": str,
         "typeName": str,
     },
 )
@@ -836,21 +1021,108 @@
 )
 
 class ListResolversRequestRequestTypeDef(
     _RequiredListResolversRequestRequestTypeDef, _OptionalListResolversRequestRequestTypeDef
 ):
     pass
 
+_RequiredListSourceApiAssociationsRequestRequestTypeDef = TypedDict(
+    "_RequiredListSourceApiAssociationsRequestRequestTypeDef",
+    {
+        "apiId": str,
+    },
+)
+_OptionalListSourceApiAssociationsRequestRequestTypeDef = TypedDict(
+    "_OptionalListSourceApiAssociationsRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+class ListSourceApiAssociationsRequestRequestTypeDef(
+    _RequiredListSourceApiAssociationsRequestRequestTypeDef,
+    _OptionalListSourceApiAssociationsRequestRequestTypeDef,
+):
+    pass
+
+SourceApiAssociationSummaryTypeDef = TypedDict(
+    "SourceApiAssociationSummaryTypeDef",
+    {
+        "associationId": str,
+        "associationArn": str,
+        "sourceApiId": str,
+        "sourceApiArn": str,
+        "mergedApiId": str,
+        "mergedApiArn": str,
+        "description": str,
+    },
+    total=False,
+)
+
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
+_RequiredListTypesByAssociationRequestRequestTypeDef = TypedDict(
+    "_RequiredListTypesByAssociationRequestRequestTypeDef",
+    {
+        "mergedApiIdentifier": str,
+        "associationId": str,
+        "format": TypeDefinitionFormatType,
+    },
+)
+_OptionalListTypesByAssociationRequestRequestTypeDef = TypedDict(
+    "_OptionalListTypesByAssociationRequestRequestTypeDef",
+    {
+        "nextToken": str,
+        "maxResults": int,
+    },
+    total=False,
+)
+
+class ListTypesByAssociationRequestRequestTypeDef(
+    _RequiredListTypesByAssociationRequestRequestTypeDef,
+    _OptionalListTypesByAssociationRequestRequestTypeDef,
+):
+    pass
+
+_RequiredListTypesRequestListTypesPaginateTypeDef = TypedDict(
+    "_RequiredListTypesRequestListTypesPaginateTypeDef",
+    {
+        "apiId": str,
+        "format": TypeDefinitionFormatType,
+    },
+)
+_OptionalListTypesRequestListTypesPaginateTypeDef = TypedDict(
+    "_OptionalListTypesRequestListTypesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTypesRequestListTypesPaginateTypeDef(
+    _RequiredListTypesRequestListTypesPaginateTypeDef,
+    _OptionalListTypesRequestListTypesPaginateTypeDef,
+):
+    pass
+
 _RequiredListTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListTypesRequestRequestTypeDef",
     {
         "apiId": str,
         "format": TypeDefinitionFormatType,
     },
 )
@@ -864,34 +1136,79 @@
 )
 
 class ListTypesRequestRequestTypeDef(
     _RequiredListTypesRequestRequestTypeDef, _OptionalListTypesRequestRequestTypeDef
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
 RdsHttpEndpointConfigTypeDef = TypedDict(
     "RdsHttpEndpointConfigTypeDef",
     {
         "awsRegion": str,
         "dbClusterIdentifier": str,
         "databaseName": str,
         "schema": str,
         "awsSecretStoreArn": str,
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
 StartSchemaCreationRequestRequestTypeDef = TypedDict(
     "StartSchemaCreationRequestRequestTypeDef",
     {
         "apiId": str,
         "definition": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
+StartSchemaCreationResponseTypeDef = TypedDict(
+    "StartSchemaCreationResponseTypeDef",
+    {
+        "status": SchemaStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartSchemaMergeRequestRequestTypeDef = TypedDict(
+    "StartSchemaMergeRequestRequestTypeDef",
+    {
+        "associationId": str,
+        "mergedApiIdentifier": str,
+    },
+)
+
+StartSchemaMergeResponseTypeDef = TypedDict(
+    "StartSchemaMergeResponseTypeDef",
+    {
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
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
@@ -982,132 +1299,183 @@
         "openIDConnectConfig": OpenIDConnectConfigTypeDef,
         "userPoolConfig": CognitoUserPoolConfigTypeDef,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
     },
     total=False,
 )
 
-_RequiredEvaluateCodeRequestRequestTypeDef = TypedDict(
-    "_RequiredEvaluateCodeRequestRequestTypeDef",
+AssociateApiResponseTypeDef = TypedDict(
+    "AssociateApiResponseTypeDef",
     {
-        "runtime": AppSyncRuntimeTypeDef,
-        "code": str,
-        "context": str,
+        "apiAssociation": ApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalEvaluateCodeRequestRequestTypeDef = TypedDict(
-    "_OptionalEvaluateCodeRequestRequestTypeDef",
+
+GetApiAssociationResponseTypeDef = TypedDict(
+    "GetApiAssociationResponseTypeDef",
     {
-        "function": str,
+        "apiAssociation": ApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class EvaluateCodeRequestRequestTypeDef(
-    _RequiredEvaluateCodeRequestRequestTypeDef, _OptionalEvaluateCodeRequestRequestTypeDef
-):
-    pass
+CreateApiCacheResponseTypeDef = TypedDict(
+    "CreateApiCacheResponseTypeDef",
+    {
+        "apiCache": ApiCacheTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-AssociateApiResponseTypeDef = TypedDict(
-    "AssociateApiResponseTypeDef",
+GetApiCacheResponseTypeDef = TypedDict(
+    "GetApiCacheResponseTypeDef",
     {
-        "apiAssociation": ApiAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "apiCache": ApiCacheTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateApiCacheResponseTypeDef = TypedDict(
-    "CreateApiCacheResponseTypeDef",
+UpdateApiCacheResponseTypeDef = TypedDict(
+    "UpdateApiCacheResponseTypeDef",
     {
         "apiCache": ApiCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateApiKeyResponseTypeDef = TypedDict(
     "CreateApiKeyResponseTypeDef",
     {
         "apiKey": ApiKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetApiAssociationResponseTypeDef = TypedDict(
-    "GetApiAssociationResponseTypeDef",
+ListApiKeysResponseTypeDef = TypedDict(
+    "ListApiKeysResponseTypeDef",
     {
-        "apiAssociation": ApiAssociationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "apiKeys": List[ApiKeyTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetApiCacheResponseTypeDef = TypedDict(
-    "GetApiCacheResponseTypeDef",
+UpdateApiKeyResponseTypeDef = TypedDict(
+    "UpdateApiKeyResponseTypeDef",
     {
-        "apiCache": ApiCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "apiKey": ApiKeyTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetIntrospectionSchemaResponseTypeDef = TypedDict(
-    "GetIntrospectionSchemaResponseTypeDef",
+_RequiredEvaluateCodeRequestRequestTypeDef = TypedDict(
+    "_RequiredEvaluateCodeRequestRequestTypeDef",
     {
-        "schema": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "runtime": AppSyncRuntimeTypeDef,
+        "code": str,
+        "context": str,
     },
 )
-
-GetSchemaCreationStatusResponseTypeDef = TypedDict(
-    "GetSchemaCreationStatusResponseTypeDef",
+_OptionalEvaluateCodeRequestRequestTypeDef = TypedDict(
+    "_OptionalEvaluateCodeRequestRequestTypeDef",
     {
-        "status": SchemaStatusType,
-        "details": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "function": str,
     },
+    total=False,
 )
 
-ListApiKeysResponseTypeDef = TypedDict(
-    "ListApiKeysResponseTypeDef",
+class EvaluateCodeRequestRequestTypeDef(
+    _RequiredEvaluateCodeRequestRequestTypeDef, _OptionalEvaluateCodeRequestRequestTypeDef
+):
+    pass
+
+_RequiredAssociateMergedGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_RequiredAssociateMergedGraphqlApiRequestRequestTypeDef",
     {
-        "apiKeys": List[ApiKeyTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "sourceApiIdentifier": str,
+        "mergedApiIdentifier": str,
     },
 )
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+_OptionalAssociateMergedGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_OptionalAssociateMergedGraphqlApiRequestRequestTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
     },
+    total=False,
 )
 
-StartSchemaCreationResponseTypeDef = TypedDict(
-    "StartSchemaCreationResponseTypeDef",
+class AssociateMergedGraphqlApiRequestRequestTypeDef(
+    _RequiredAssociateMergedGraphqlApiRequestRequestTypeDef,
+    _OptionalAssociateMergedGraphqlApiRequestRequestTypeDef,
+):
+    pass
+
+_RequiredAssociateSourceGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_RequiredAssociateSourceGraphqlApiRequestRequestTypeDef",
     {
-        "status": SchemaStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "mergedApiIdentifier": str,
+        "sourceApiIdentifier": str,
+    },
+)
+_OptionalAssociateSourceGraphqlApiRequestRequestTypeDef = TypedDict(
+    "_OptionalAssociateSourceGraphqlApiRequestRequestTypeDef",
+    {
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
     },
+    total=False,
 )
 
-UpdateApiCacheResponseTypeDef = TypedDict(
-    "UpdateApiCacheResponseTypeDef",
+class AssociateSourceGraphqlApiRequestRequestTypeDef(
+    _RequiredAssociateSourceGraphqlApiRequestRequestTypeDef,
+    _OptionalAssociateSourceGraphqlApiRequestRequestTypeDef,
+):
+    pass
+
+SourceApiAssociationTypeDef = TypedDict(
+    "SourceApiAssociationTypeDef",
     {
-        "apiCache": ApiCacheTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "associationId": str,
+        "associationArn": str,
+        "sourceApiId": str,
+        "sourceApiArn": str,
+        "mergedApiArn": str,
+        "mergedApiId": str,
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
+        "sourceApiAssociationStatus": SourceApiAssociationStatusType,
+        "sourceApiAssociationStatusDetail": str,
+        "lastSuccessfulMergeDate": datetime,
     },
+    total=False,
 )
 
-UpdateApiKeyResponseTypeDef = TypedDict(
-    "UpdateApiKeyResponseTypeDef",
+_RequiredUpdateSourceApiAssociationRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateSourceApiAssociationRequestRequestTypeDef",
     {
-        "apiKey": ApiKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "associationId": str,
+        "mergedApiIdentifier": str,
     },
 )
+_OptionalUpdateSourceApiAssociationRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateSourceApiAssociationRequestRequestTypeDef",
+    {
+        "description": str,
+        "sourceApiAssociationConfig": SourceApiAssociationConfigTypeDef,
+    },
+    total=False,
+)
+
+class UpdateSourceApiAssociationRequestRequestTypeDef(
+    _RequiredUpdateSourceApiAssociationRequestRequestTypeDef,
+    _OptionalUpdateSourceApiAssociationRequestRequestTypeDef,
+):
+    pass
 
 _RequiredAuthorizationConfigTypeDef = TypedDict(
     "_RequiredAuthorizationConfigTypeDef",
     {
         "authorizationType": Literal["AWS_IAM"],
     },
 )
@@ -1134,73 +1502,82 @@
     total=False,
 )
 
 CreateDomainNameResponseTypeDef = TypedDict(
     "CreateDomainNameResponseTypeDef",
     {
         "domainNameConfig": DomainNameConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainNameResponseTypeDef = TypedDict(
     "GetDomainNameResponseTypeDef",
     {
         "domainNameConfig": DomainNameConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainNamesResponseTypeDef = TypedDict(
     "ListDomainNamesResponseTypeDef",
     {
         "domainNameConfigs": List[DomainNameConfigTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainNameResponseTypeDef = TypedDict(
     "UpdateDomainNameResponseTypeDef",
     {
         "domainNameConfig": DomainNameConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTypeResponseTypeDef = TypedDict(
     "CreateTypeResponseTypeDef",
     {
         "type": TypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTypeResponseTypeDef = TypedDict(
     "GetTypeResponseTypeDef",
     {
         "type": TypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTypesByAssociationResponseTypeDef = TypedDict(
+    "ListTypesByAssociationResponseTypeDef",
+    {
+        "types": List[TypeTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTypesResponseTypeDef = TypedDict(
     "ListTypesResponseTypeDef",
     {
         "types": List[TypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTypeResponseTypeDef = TypedDict(
     "UpdateTypeResponseTypeDef",
     {
         "type": TypeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDynamodbDataSourceConfigTypeDef = TypedDict(
     "_RequiredDynamodbDataSourceConfigTypeDef",
     {
         "tableName": str,
@@ -1224,159 +1601,37 @@
 
 EvaluateMappingTemplateResponseTypeDef = TypedDict(
     "EvaluateMappingTemplateResponseTypeDef",
     {
         "evaluationResult": str,
         "error": ErrorDetailTypeDef,
         "logs": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SyncConfigTypeDef = TypedDict(
     "SyncConfigTypeDef",
     {
         "conflictHandler": ConflictHandlerTypeType,
         "conflictDetection": ConflictDetectionTypeType,
         "lambdaConflictHandlerConfig": LambdaConflictHandlerConfigTypeDef,
     },
     total=False,
 )
 
-_RequiredListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
-    "_RequiredListApiKeysRequestListApiKeysPaginateTypeDef",
-    {
-        "apiId": str,
-    },
-)
-_OptionalListApiKeysRequestListApiKeysPaginateTypeDef = TypedDict(
-    "_OptionalListApiKeysRequestListApiKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListApiKeysRequestListApiKeysPaginateTypeDef(
-    _RequiredListApiKeysRequestListApiKeysPaginateTypeDef,
-    _OptionalListApiKeysRequestListApiKeysPaginateTypeDef,
-):
-    pass
-
-_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef",
+ListSourceApiAssociationsResponseTypeDef = TypedDict(
+    "ListSourceApiAssociationsResponseTypeDef",
     {
-        "apiId": str,
-    },
-)
-_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDataSourcesRequestListDataSourcesPaginateTypeDef(
-    _RequiredListDataSourcesRequestListDataSourcesPaginateTypeDef,
-    _OptionalListDataSourcesRequestListDataSourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionsRequestListFunctionsPaginateTypeDef",
-    {
-        "apiId": str,
-    },
-)
-_OptionalListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionsRequestListFunctionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFunctionsRequestListFunctionsPaginateTypeDef(
-    _RequiredListFunctionsRequestListFunctionsPaginateTypeDef,
-    _OptionalListFunctionsRequestListFunctionsPaginateTypeDef,
-):
-    pass
-
-ListGraphqlApisRequestListGraphqlApisPaginateTypeDef = TypedDict(
-    "ListGraphqlApisRequestListGraphqlApisPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
-    "_RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
-    {
-        "apiId": str,
-        "functionId": str,
-    },
-)
-_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef = TypedDict(
-    "_OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef(
-    _RequiredListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
-    _OptionalListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
-):
-    pass
-
-_RequiredListResolversRequestListResolversPaginateTypeDef = TypedDict(
-    "_RequiredListResolversRequestListResolversPaginateTypeDef",
-    {
-        "apiId": str,
-        "typeName": str,
-    },
-)
-_OptionalListResolversRequestListResolversPaginateTypeDef = TypedDict(
-    "_OptionalListResolversRequestListResolversPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListResolversRequestListResolversPaginateTypeDef(
-    _RequiredListResolversRequestListResolversPaginateTypeDef,
-    _OptionalListResolversRequestListResolversPaginateTypeDef,
-):
-    pass
-
-_RequiredListTypesRequestListTypesPaginateTypeDef = TypedDict(
-    "_RequiredListTypesRequestListTypesPaginateTypeDef",
-    {
-        "apiId": str,
-        "format": TypeDefinitionFormatType,
-    },
-)
-_OptionalListTypesRequestListTypesPaginateTypeDef = TypedDict(
-    "_OptionalListTypesRequestListTypesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "sourceApiAssociationSummaries": List[SourceApiAssociationSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListTypesRequestListTypesPaginateTypeDef(
-    _RequiredListTypesRequestListTypesPaginateTypeDef,
-    _OptionalListTypesRequestListTypesPaginateTypeDef,
-):
-    pass
-
 RelationalDatabaseDataSourceConfigTypeDef = TypedDict(
     "RelationalDatabaseDataSourceConfigTypeDef",
     {
         "relationalDatabaseSourceType": Literal["RDS_HTTP_ENDPOINT"],
         "rdsHttpEndpointConfig": RdsHttpEndpointConfigTypeDef,
     },
     total=False,
@@ -1395,14 +1650,18 @@
         "logConfig": LogConfigTypeDef,
         "userPoolConfig": UserPoolConfigTypeDef,
         "openIDConnectConfig": OpenIDConnectConfigTypeDef,
         "tags": Mapping[str, str],
         "additionalAuthenticationProviders": Sequence[AdditionalAuthenticationProviderTypeDef],
         "xrayEnabled": bool,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
+        "visibility": GraphQLApiVisibilityType,
+        "apiType": GraphQLApiTypeType,
+        "mergedApiExecutionRoleArn": str,
+        "ownerContact": str,
     },
     total=False,
 )
 
 class CreateGraphqlApiRequestRequestTypeDef(
     _RequiredCreateGraphqlApiRequestRequestTypeDef, _OptionalCreateGraphqlApiRequestRequestTypeDef
 ):
@@ -1420,14 +1679,20 @@
         "arn": str,
         "uris": Dict[str, str],
         "tags": Dict[str, str],
         "additionalAuthenticationProviders": List[AdditionalAuthenticationProviderTypeDef],
         "xrayEnabled": bool,
         "wafWebAclArn": str,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
+        "dns": Dict[str, str],
+        "visibility": GraphQLApiVisibilityType,
+        "apiType": GraphQLApiTypeType,
+        "mergedApiExecutionRoleArn": str,
+        "owner": str,
+        "ownerContact": str,
     },
     total=False,
 )
 
 _RequiredUpdateGraphqlApiRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateGraphqlApiRequestRequestTypeDef",
     {
@@ -1441,23 +1706,57 @@
         "logConfig": LogConfigTypeDef,
         "authenticationType": AuthenticationTypeType,
         "userPoolConfig": UserPoolConfigTypeDef,
         "openIDConnectConfig": OpenIDConnectConfigTypeDef,
         "additionalAuthenticationProviders": Sequence[AdditionalAuthenticationProviderTypeDef],
         "xrayEnabled": bool,
         "lambdaAuthorizerConfig": LambdaAuthorizerConfigTypeDef,
+        "mergedApiExecutionRoleArn": str,
+        "ownerContact": str,
     },
     total=False,
 )
 
 class UpdateGraphqlApiRequestRequestTypeDef(
     _RequiredUpdateGraphqlApiRequestRequestTypeDef, _OptionalUpdateGraphqlApiRequestRequestTypeDef
 ):
     pass
 
+AssociateMergedGraphqlApiResponseTypeDef = TypedDict(
+    "AssociateMergedGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociateSourceGraphqlApiResponseTypeDef = TypedDict(
+    "AssociateSourceGraphqlApiResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSourceApiAssociationResponseTypeDef = TypedDict(
+    "GetSourceApiAssociationResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateSourceApiAssociationResponseTypeDef = TypedDict(
+    "UpdateSourceApiAssociationResponseTypeDef",
+    {
+        "sourceApiAssociation": SourceApiAssociationTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HttpDataSourceConfigTypeDef = TypedDict(
     "HttpDataSourceConfigTypeDef",
     {
         "endpoint": str,
         "authorizationConfig": AuthorizationConfigTypeDef,
     },
     total=False,
@@ -1628,40 +1927,40 @@
 ):
     pass
 
 CreateGraphqlApiResponseTypeDef = TypedDict(
     "CreateGraphqlApiResponseTypeDef",
     {
         "graphqlApi": GraphqlApiTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGraphqlApiResponseTypeDef = TypedDict(
     "GetGraphqlApiResponseTypeDef",
     {
         "graphqlApi": GraphqlApiTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGraphqlApisResponseTypeDef = TypedDict(
     "ListGraphqlApisResponseTypeDef",
     {
         "graphqlApis": List[GraphqlApiTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGraphqlApiResponseTypeDef = TypedDict(
     "UpdateGraphqlApiResponseTypeDef",
     {
         "graphqlApi": GraphqlApiTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDataSourceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDataSourceRequestRequestTypeDef",
     {
         "apiId": str,
@@ -1740,118 +2039,118 @@
 
 EvaluateCodeResponseTypeDef = TypedDict(
     "EvaluateCodeResponseTypeDef",
     {
         "evaluationResult": str,
         "error": EvaluateCodeErrorDetailTypeDef,
         "logs": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFunctionResponseTypeDef = TypedDict(
     "CreateFunctionResponseTypeDef",
     {
         "functionConfiguration": FunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFunctionResponseTypeDef = TypedDict(
     "GetFunctionResponseTypeDef",
     {
         "functionConfiguration": FunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionsResponseTypeDef = TypedDict(
     "ListFunctionsResponseTypeDef",
     {
         "functions": List[FunctionConfigurationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFunctionResponseTypeDef = TypedDict(
     "UpdateFunctionResponseTypeDef",
     {
         "functionConfiguration": FunctionConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateResolverResponseTypeDef = TypedDict(
     "CreateResolverResponseTypeDef",
     {
         "resolver": ResolverTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResolverResponseTypeDef = TypedDict(
     "GetResolverResponseTypeDef",
     {
         "resolver": ResolverTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolversByFunctionResponseTypeDef = TypedDict(
     "ListResolversByFunctionResponseTypeDef",
     {
         "resolvers": List[ResolverTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListResolversResponseTypeDef = TypedDict(
     "ListResolversResponseTypeDef",
     {
         "resolvers": List[ResolverTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateResolverResponseTypeDef = TypedDict(
     "UpdateResolverResponseTypeDef",
     {
         "resolver": ResolverTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDataSourceResponseTypeDef = TypedDict(
     "CreateDataSourceResponseTypeDef",
     {
         "dataSource": DataSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataSourceResponseTypeDef = TypedDict(
     "GetDataSourceResponseTypeDef",
     {
         "dataSource": DataSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataSourcesResponseTypeDef = TypedDict(
     "ListDataSourcesResponseTypeDef",
     {
         "dataSources": List[DataSourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDataSourceResponseTypeDef = TypedDict(
     "UpdateDataSourceResponseTypeDef",
     {
         "dataSource": DataSourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/PKG-INFO` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-appsync
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AppSync 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AppSync 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-appsync"></a>
 
 # types-aiobotocore-appsync
 
 [![PyPI - types-aiobotocore-appsync](https://img.shields.io/pypi/v/types-aiobotocore-appsync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appsync)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-appsync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-appsync)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-appsync?color=blue)](https://pypistats.org/packages/types-aiobotocore-appsync)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AppSync 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
+[aiobotocore.AppSync 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/appsync.html#AppSync)
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
 [types-aiobotocore-appsync docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_appsync/).
 
 See how it helps to find and fix potential bugs:
 
@@ -322,26 +322,31 @@
     AuthenticationTypeType,
     AuthorizationTypeType,
     ConflictDetectionTypeType,
     ConflictHandlerTypeType,
     DataSourceTypeType,
     DefaultActionType,
     FieldLogLevelType,
+    GraphQLApiTypeType,
+    GraphQLApiVisibilityType,
     ListApiKeysPaginatorName,
     ListDataSourcesPaginatorName,
     ListFunctionsPaginatorName,
     ListGraphqlApisPaginatorName,
     ListResolversByFunctionPaginatorName,
     ListResolversPaginatorName,
     ListTypesPaginatorName,
+    MergeTypeType,
     OutputTypeType,
+    OwnershipType,
     RelationalDatabaseSourceTypeType,
     ResolverKindType,
     RuntimeNameType,
     SchemaStatusType,
+    SourceApiAssociationStatusType,
     TypeDefinitionFormatType,
     AppSyncServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
@@ -364,15 +369,15 @@
     LambdaAuthorizerConfigTypeDef,
     OpenIDConnectConfigTypeDef,
     ApiAssociationTypeDef,
     ApiCacheTypeDef,
     ApiKeyTypeDef,
     AppSyncRuntimeTypeDef,
     AssociateApiRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    SourceApiAssociationConfigTypeDef,
     AwsIamConfigTypeDef,
     CachingConfigTypeDef,
     CodeErrorLocationTypeDef,
     CreateApiCacheRequestRequestTypeDef,
     CreateApiKeyRequestRequestTypeDef,
     ElasticsearchDataSourceConfigTypeDef,
     EventBridgeDataSourceConfigTypeDef,
@@ -391,84 +396,105 @@
     DeleteDomainNameRequestRequestTypeDef,
     DeleteFunctionRequestRequestTypeDef,
     DeleteGraphqlApiRequestRequestTypeDef,
     DeleteResolverRequestRequestTypeDef,
     DeleteTypeRequestRequestTypeDef,
     DeltaSyncConfigTypeDef,
     DisassociateApiRequestRequestTypeDef,
+    DisassociateMergedGraphqlApiRequestRequestTypeDef,
+    DisassociateMergedGraphqlApiResponseTypeDef,
+    DisassociateSourceGraphqlApiRequestRequestTypeDef,
+    DisassociateSourceGraphqlApiResponseTypeDef,
     ErrorDetailTypeDef,
     EvaluateMappingTemplateRequestRequestTypeDef,
     FlushApiCacheRequestRequestTypeDef,
     GetApiAssociationRequestRequestTypeDef,
     GetApiCacheRequestRequestTypeDef,
     GetDataSourceRequestRequestTypeDef,
     GetDomainNameRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
     GetGraphqlApiRequestRequestTypeDef,
     GetIntrospectionSchemaRequestRequestTypeDef,
+    GetIntrospectionSchemaResponseTypeDef,
     GetResolverRequestRequestTypeDef,
     GetSchemaCreationStatusRequestRequestTypeDef,
+    GetSchemaCreationStatusResponseTypeDef,
+    GetSourceApiAssociationRequestRequestTypeDef,
     GetTypeRequestRequestTypeDef,
     LambdaConflictHandlerConfigTypeDef,
-    PaginatorConfigTypeDef,
+    ListApiKeysRequestListApiKeysPaginateTypeDef,
     ListApiKeysRequestRequestTypeDef,
+    ListDataSourcesRequestListDataSourcesPaginateTypeDef,
     ListDataSourcesRequestRequestTypeDef,
     ListDomainNamesRequestRequestTypeDef,
+    ListFunctionsRequestListFunctionsPaginateTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListGraphqlApisRequestListGraphqlApisPaginateTypeDef,
     ListGraphqlApisRequestRequestTypeDef,
+    ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
     ListResolversByFunctionRequestRequestTypeDef,
+    ListResolversRequestListResolversPaginateTypeDef,
     ListResolversRequestRequestTypeDef,
+    ListSourceApiAssociationsRequestRequestTypeDef,
+    SourceApiAssociationSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    ListTypesByAssociationRequestRequestTypeDef,
+    ListTypesRequestListTypesPaginateTypeDef,
     ListTypesRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     RdsHttpEndpointConfigTypeDef,
+    ResponseMetadataTypeDef,
     StartSchemaCreationRequestRequestTypeDef,
+    StartSchemaCreationResponseTypeDef,
+    StartSchemaMergeRequestRequestTypeDef,
+    StartSchemaMergeResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateApiCacheRequestRequestTypeDef,
     UpdateApiKeyRequestRequestTypeDef,
     UpdateDomainNameRequestRequestTypeDef,
     UpdateTypeRequestRequestTypeDef,
     AdditionalAuthenticationProviderTypeDef,
-    EvaluateCodeRequestRequestTypeDef,
     AssociateApiResponseTypeDef,
-    CreateApiCacheResponseTypeDef,
-    CreateApiKeyResponseTypeDef,
     GetApiAssociationResponseTypeDef,
+    CreateApiCacheResponseTypeDef,
     GetApiCacheResponseTypeDef,
-    GetIntrospectionSchemaResponseTypeDef,
-    GetSchemaCreationStatusResponseTypeDef,
-    ListApiKeysResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    StartSchemaCreationResponseTypeDef,
     UpdateApiCacheResponseTypeDef,
+    CreateApiKeyResponseTypeDef,
+    ListApiKeysResponseTypeDef,
     UpdateApiKeyResponseTypeDef,
+    EvaluateCodeRequestRequestTypeDef,
+    AssociateMergedGraphqlApiRequestRequestTypeDef,
+    AssociateSourceGraphqlApiRequestRequestTypeDef,
+    SourceApiAssociationTypeDef,
+    UpdateSourceApiAssociationRequestRequestTypeDef,
     AuthorizationConfigTypeDef,
     CodeErrorTypeDef,
     CreateDomainNameResponseTypeDef,
     GetDomainNameResponseTypeDef,
     ListDomainNamesResponseTypeDef,
     UpdateDomainNameResponseTypeDef,
     CreateTypeResponseTypeDef,
     GetTypeResponseTypeDef,
+    ListTypesByAssociationResponseTypeDef,
     ListTypesResponseTypeDef,
     UpdateTypeResponseTypeDef,
     DynamodbDataSourceConfigTypeDef,
     EvaluateMappingTemplateResponseTypeDef,
     SyncConfigTypeDef,
-    ListApiKeysRequestListApiKeysPaginateTypeDef,
-    ListDataSourcesRequestListDataSourcesPaginateTypeDef,
-    ListFunctionsRequestListFunctionsPaginateTypeDef,
-    ListGraphqlApisRequestListGraphqlApisPaginateTypeDef,
-    ListResolversByFunctionRequestListResolversByFunctionPaginateTypeDef,
-    ListResolversRequestListResolversPaginateTypeDef,
-    ListTypesRequestListTypesPaginateTypeDef,
+    ListSourceApiAssociationsResponseTypeDef,
     RelationalDatabaseDataSourceConfigTypeDef,
     CreateGraphqlApiRequestRequestTypeDef,
     GraphqlApiTypeDef,
     UpdateGraphqlApiRequestRequestTypeDef,
+    AssociateMergedGraphqlApiResponseTypeDef,
+    AssociateSourceGraphqlApiResponseTypeDef,
+    GetSourceApiAssociationResponseTypeDef,
+    UpdateSourceApiAssociationResponseTypeDef,
     HttpDataSourceConfigTypeDef,
     EvaluateCodeErrorDetailTypeDef,
     CreateFunctionRequestRequestTypeDef,
     CreateResolverRequestRequestTypeDef,
     FunctionConfigurationTypeDef,
     ResolverTypeDef,
     UpdateFunctionRequestRequestTypeDef,
@@ -504,43 +530,43 @@
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

### Comparing `types-aiobotocore-appsync-2.5.0.post1/types_aiobotocore_appsync.egg-info/SOURCES.txt` & `types-aiobotocore-appsync-2.5.1/types_aiobotocore_appsync.egg-info/SOURCES.txt`

 * *Files identical despite different names*

