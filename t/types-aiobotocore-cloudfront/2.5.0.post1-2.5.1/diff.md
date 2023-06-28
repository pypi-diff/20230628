# Comparing `tmp/types-aiobotocore-cloudfront-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cloudfront-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cloudfront-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:19 2023, max compression
+gzip compressed data, was "types-aiobotocore-cloudfront-2.5.1.tar", last modified: Wed Jun 28 01:43:13 2023, max compression
```

## Comparing `types-aiobotocore-cloudfront-2.5.0.post1.tar` & `types-aiobotocore-cloudfront-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.979024 types-aiobotocore-cloudfront-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    31194 2023-03-11 12:26:19.979024 types-aiobotocore-cloudfront-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    29611 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:19.979024 types-aiobotocore-cloudfront-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.967024 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/
--rw-r--r--   0 runner    (1001) docker     (123)     2226 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2225 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    83264 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    83142 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12224 2023-03-11 12:10:51.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12222 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5880 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5873 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   138350 2023-03-11 12:10:54.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   138087 2023-03-11 12:10:52.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     3770 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     3767 2023-03-11 12:10:50.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:19.975024 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    31194 2023-03-11 12:26:19.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      949 2023-03-11 12:26:19.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:19.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:19.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:19.000000 types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.366107 types-aiobotocore-cloudfront-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    31189 2023-06-28 01:43:13.358107 types-aiobotocore-cloudfront-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    29612 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:13.366107 types-aiobotocore-cloudfront-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.350107 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/
+-rw-r--r--   0 runner    (1001) docker     (123)     2226 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2225 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    83274 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    83152 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12472 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12470 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5768 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5762 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   138536 2023-06-28 01:27:30.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   138273 2023-06-28 01:27:29.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:26.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3770 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3767 2023-06-28 01:27:27.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:13.358107 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    31189 2023-06-28 01:43:13.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:43:13.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:13.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:13.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:13.000000 types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/LICENSE` & `types-aiobotocore-cloudfront-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cloudfront-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudfront
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudFront 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudFront 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudfront"></a>
 
 # types-aiobotocore-cloudfront
 
 [![PyPI - types-aiobotocore-cloudfront](https://img.shields.io/pypi/v/types-aiobotocore-cloudfront.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudfront)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudfront.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudfront)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudfront?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudfront)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudFront 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront)
+[aiobotocore.CloudFront 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront)
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
 [types-aiobotocore-cloudfront docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/).
 
 See how it helps to find and fix potential bugs:
 
@@ -421,15 +421,14 @@
     CloudFrontOriginAccessIdentitySummaryTypeDef,
     ConflictingAliasTypeDef,
     ContentTypeProfileTypeDef,
     StagingDistributionDnsNamesTypeDef,
     ContinuousDeploymentSingleHeaderConfigTypeDef,
     SessionStickinessConfigTypeDef,
     CopyDistributionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     FunctionConfigTypeDef,
     KeyGroupConfigTypeDef,
     OriginAccessControlConfigTypeDef,
     PublicKeyConfigTypeDef,
     CustomErrorResponseTypeDef,
     OriginCustomHeaderTypeDef,
     OriginSslProtocolsTypeDef,
@@ -448,14 +447,15 @@
     DeleteRealtimeLogConfigRequestRequestTypeDef,
     DeleteResponseHeadersPolicyRequestRequestTypeDef,
     DeleteStreamingDistributionRequestRequestTypeDef,
     DescribeFunctionRequestRequestTypeDef,
     LoggingConfigTypeDef,
     ViewerCertificateTypeDef,
     DistributionIdListTypeDef,
+    EmptyResponseMetadataTypeDef,
     FieldPatternsTypeDef,
     KinesisStreamConfigTypeDef,
     QueryStringCacheKeysTypeDef,
     FunctionAssociationTypeDef,
     FunctionMetadataTypeDef,
     GeoRestrictionTypeDef,
     GetCachePolicyConfigRequestRequestTypeDef,
@@ -468,14 +468,15 @@
     WaiterConfigTypeDef,
     GetDistributionRequestRequestTypeDef,
     GetFieldLevelEncryptionConfigRequestRequestTypeDef,
     GetFieldLevelEncryptionProfileConfigRequestRequestTypeDef,
     GetFieldLevelEncryptionProfileRequestRequestTypeDef,
     GetFieldLevelEncryptionRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
+    GetFunctionResultTypeDef,
     GetInvalidationRequestRequestTypeDef,
     GetKeyGroupConfigRequestRequestTypeDef,
     GetKeyGroupRequestRequestTypeDef,
     GetMonitoringSubscriptionRequestRequestTypeDef,
     GetOriginAccessControlConfigRequestRequestTypeDef,
     GetOriginAccessControlRequestRequestTypeDef,
     GetOriginRequestPolicyConfigRequestRequestTypeDef,
@@ -488,43 +489,47 @@
     GetStreamingDistributionConfigRequestRequestTypeDef,
     GetStreamingDistributionRequestRequestTypeDef,
     PathsTypeDef,
     InvalidationSummaryTypeDef,
     KeyPairIdsTypeDef,
     LambdaFunctionAssociationTypeDef,
     ListCachePoliciesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef,
     ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef,
     ListConflictingAliasesRequestRequestTypeDef,
     ListContinuousDeploymentPoliciesRequestRequestTypeDef,
     ListDistributionsByCachePolicyIdRequestRequestTypeDef,
     ListDistributionsByKeyGroupRequestRequestTypeDef,
     ListDistributionsByOriginRequestPolicyIdRequestRequestTypeDef,
     ListDistributionsByRealtimeLogConfigRequestRequestTypeDef,
     ListDistributionsByResponseHeadersPolicyIdRequestRequestTypeDef,
     ListDistributionsByWebACLIdRequestRequestTypeDef,
+    ListDistributionsRequestListDistributionsPaginateTypeDef,
     ListDistributionsRequestRequestTypeDef,
     ListFieldLevelEncryptionConfigsRequestRequestTypeDef,
     ListFieldLevelEncryptionProfilesRequestRequestTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListInvalidationsRequestListInvalidationsPaginateTypeDef,
     ListInvalidationsRequestRequestTypeDef,
     ListKeyGroupsRequestRequestTypeDef,
     ListOriginAccessControlsRequestRequestTypeDef,
     ListOriginRequestPoliciesRequestRequestTypeDef,
     ListPublicKeysRequestRequestTypeDef,
     ListRealtimeLogConfigsRequestRequestTypeDef,
     ListResponseHeadersPoliciesRequestRequestTypeDef,
+    ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef,
     ListStreamingDistributionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RealtimeMetricsSubscriptionConfigTypeDef,
     OriginAccessControlSummaryTypeDef,
     StatusCodesTypeDef,
     OriginGroupMemberTypeDef,
     OriginShieldTypeDef,
     S3OriginConfigTypeDef,
+    PaginatorConfigTypeDef,
     PublicKeySummaryTypeDef,
     PublishFunctionRequestRequestTypeDef,
     QueryArgProfileTypeDef,
     ResponseHeadersPolicyAccessControlAllowHeadersTypeDef,
     ResponseHeadersPolicyAccessControlAllowMethodsTypeDef,
     ResponseHeadersPolicyAccessControlAllowOriginsTypeDef,
     ResponseHeadersPolicyAccessControlExposeHeadersTypeDef,
@@ -533,14 +538,15 @@
     ResponseHeadersPolicyContentTypeOptionsTypeDef,
     ResponseHeadersPolicyCustomHeaderTypeDef,
     ResponseHeadersPolicyFrameOptionsTypeDef,
     ResponseHeadersPolicyReferrerPolicyTypeDef,
     ResponseHeadersPolicyRemoveHeaderTypeDef,
     ResponseHeadersPolicyStrictTransportSecurityTypeDef,
     ResponseHeadersPolicyXSSProtectionTypeDef,
+    ResponseMetadataTypeDef,
     S3OriginTypeDef,
     StreamingLoggingConfigTypeDef,
     TagKeysTypeDef,
     TagTypeDef,
     TestFunctionRequestRequestTypeDef,
     UpdateDistributionWithStagingConfigRequestRequestTypeDef,
     AllowedMethodsTypeDef,
@@ -549,22 +555,20 @@
     OriginRequestPolicyCookiesConfigTypeDef,
     CachePolicyHeadersConfigTypeDef,
     OriginRequestPolicyHeadersConfigTypeDef,
     CachePolicyQueryStringsConfigTypeDef,
     OriginRequestPolicyQueryStringsConfigTypeDef,
     CloudFrontOriginAccessIdentityTypeDef,
     CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef,
+    GetCloudFrontOriginAccessIdentityConfigResultTypeDef,
     UpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef,
     CloudFrontOriginAccessIdentityListTypeDef,
     ConflictingAliasesListTypeDef,
     ContentTypeProfilesTypeDef,
     ContinuousDeploymentSingleWeightConfigTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCloudFrontOriginAccessIdentityConfigResultTypeDef,
-    GetFunctionResultTypeDef,
     CreateFunctionRequestRequestTypeDef,
     UpdateFunctionRequestRequestTypeDef,
     CreateKeyGroupRequestRequestTypeDef,
     GetKeyGroupConfigResultTypeDef,
     KeyGroupTypeDef,
     UpdateKeyGroupRequestRequestTypeDef,
     CreateOriginAccessControlRequestRequestTypeDef,
@@ -591,18 +595,14 @@
     GetInvalidationRequestInvalidationCompletedWaitTypeDef,
     GetStreamingDistributionRequestStreamingDistributionDeployedWaitTypeDef,
     InvalidationBatchTypeDef,
     InvalidationListTypeDef,
     KGKeyPairIdsTypeDef,
     SignerTypeDef,
     LambdaFunctionAssociationsTypeDef,
-    ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef,
-    ListDistributionsRequestListDistributionsPaginateTypeDef,
-    ListInvalidationsRequestListInvalidationsPaginateTypeDef,
-    ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef,
     MonitoringSubscriptionTypeDef,
     OriginAccessControlListTypeDef,
     OriginGroupFailoverCriteriaTypeDef,
     OriginGroupMembersTypeDef,
     PublicKeyListTypeDef,
     QueryArgProfilesTypeDef,
     ResponseHeadersPolicyCorsConfigTypeDef,
@@ -779,43 +779,43 @@
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

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/README.md` & `types-aiobotocore-cloudfront-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cloudfront"></a>
 
 # types-aiobotocore-cloudfront
 
 [![PyPI - types-aiobotocore-cloudfront](https://img.shields.io/pypi/v/types-aiobotocore-cloudfront.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudfront)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudfront.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudfront)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudfront?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudfront)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudFront 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront)
+[aiobotocore.CloudFront 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront)
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
 [types-aiobotocore-cloudfront docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/).
 
 See how it helps to find and fix potential bugs:
 
@@ -388,15 +388,14 @@
     CloudFrontOriginAccessIdentitySummaryTypeDef,
     ConflictingAliasTypeDef,
     ContentTypeProfileTypeDef,
     StagingDistributionDnsNamesTypeDef,
     ContinuousDeploymentSingleHeaderConfigTypeDef,
     SessionStickinessConfigTypeDef,
     CopyDistributionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     FunctionConfigTypeDef,
     KeyGroupConfigTypeDef,
     OriginAccessControlConfigTypeDef,
     PublicKeyConfigTypeDef,
     CustomErrorResponseTypeDef,
     OriginCustomHeaderTypeDef,
     OriginSslProtocolsTypeDef,
@@ -415,14 +414,15 @@
     DeleteRealtimeLogConfigRequestRequestTypeDef,
     DeleteResponseHeadersPolicyRequestRequestTypeDef,
     DeleteStreamingDistributionRequestRequestTypeDef,
     DescribeFunctionRequestRequestTypeDef,
     LoggingConfigTypeDef,
     ViewerCertificateTypeDef,
     DistributionIdListTypeDef,
+    EmptyResponseMetadataTypeDef,
     FieldPatternsTypeDef,
     KinesisStreamConfigTypeDef,
     QueryStringCacheKeysTypeDef,
     FunctionAssociationTypeDef,
     FunctionMetadataTypeDef,
     GeoRestrictionTypeDef,
     GetCachePolicyConfigRequestRequestTypeDef,
@@ -435,14 +435,15 @@
     WaiterConfigTypeDef,
     GetDistributionRequestRequestTypeDef,
     GetFieldLevelEncryptionConfigRequestRequestTypeDef,
     GetFieldLevelEncryptionProfileConfigRequestRequestTypeDef,
     GetFieldLevelEncryptionProfileRequestRequestTypeDef,
     GetFieldLevelEncryptionRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
+    GetFunctionResultTypeDef,
     GetInvalidationRequestRequestTypeDef,
     GetKeyGroupConfigRequestRequestTypeDef,
     GetKeyGroupRequestRequestTypeDef,
     GetMonitoringSubscriptionRequestRequestTypeDef,
     GetOriginAccessControlConfigRequestRequestTypeDef,
     GetOriginAccessControlRequestRequestTypeDef,
     GetOriginRequestPolicyConfigRequestRequestTypeDef,
@@ -455,43 +456,47 @@
     GetStreamingDistributionConfigRequestRequestTypeDef,
     GetStreamingDistributionRequestRequestTypeDef,
     PathsTypeDef,
     InvalidationSummaryTypeDef,
     KeyPairIdsTypeDef,
     LambdaFunctionAssociationTypeDef,
     ListCachePoliciesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef,
     ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef,
     ListConflictingAliasesRequestRequestTypeDef,
     ListContinuousDeploymentPoliciesRequestRequestTypeDef,
     ListDistributionsByCachePolicyIdRequestRequestTypeDef,
     ListDistributionsByKeyGroupRequestRequestTypeDef,
     ListDistributionsByOriginRequestPolicyIdRequestRequestTypeDef,
     ListDistributionsByRealtimeLogConfigRequestRequestTypeDef,
     ListDistributionsByResponseHeadersPolicyIdRequestRequestTypeDef,
     ListDistributionsByWebACLIdRequestRequestTypeDef,
+    ListDistributionsRequestListDistributionsPaginateTypeDef,
     ListDistributionsRequestRequestTypeDef,
     ListFieldLevelEncryptionConfigsRequestRequestTypeDef,
     ListFieldLevelEncryptionProfilesRequestRequestTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListInvalidationsRequestListInvalidationsPaginateTypeDef,
     ListInvalidationsRequestRequestTypeDef,
     ListKeyGroupsRequestRequestTypeDef,
     ListOriginAccessControlsRequestRequestTypeDef,
     ListOriginRequestPoliciesRequestRequestTypeDef,
     ListPublicKeysRequestRequestTypeDef,
     ListRealtimeLogConfigsRequestRequestTypeDef,
     ListResponseHeadersPoliciesRequestRequestTypeDef,
+    ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef,
     ListStreamingDistributionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RealtimeMetricsSubscriptionConfigTypeDef,
     OriginAccessControlSummaryTypeDef,
     StatusCodesTypeDef,
     OriginGroupMemberTypeDef,
     OriginShieldTypeDef,
     S3OriginConfigTypeDef,
+    PaginatorConfigTypeDef,
     PublicKeySummaryTypeDef,
     PublishFunctionRequestRequestTypeDef,
     QueryArgProfileTypeDef,
     ResponseHeadersPolicyAccessControlAllowHeadersTypeDef,
     ResponseHeadersPolicyAccessControlAllowMethodsTypeDef,
     ResponseHeadersPolicyAccessControlAllowOriginsTypeDef,
     ResponseHeadersPolicyAccessControlExposeHeadersTypeDef,
@@ -500,14 +505,15 @@
     ResponseHeadersPolicyContentTypeOptionsTypeDef,
     ResponseHeadersPolicyCustomHeaderTypeDef,
     ResponseHeadersPolicyFrameOptionsTypeDef,
     ResponseHeadersPolicyReferrerPolicyTypeDef,
     ResponseHeadersPolicyRemoveHeaderTypeDef,
     ResponseHeadersPolicyStrictTransportSecurityTypeDef,
     ResponseHeadersPolicyXSSProtectionTypeDef,
+    ResponseMetadataTypeDef,
     S3OriginTypeDef,
     StreamingLoggingConfigTypeDef,
     TagKeysTypeDef,
     TagTypeDef,
     TestFunctionRequestRequestTypeDef,
     UpdateDistributionWithStagingConfigRequestRequestTypeDef,
     AllowedMethodsTypeDef,
@@ -516,22 +522,20 @@
     OriginRequestPolicyCookiesConfigTypeDef,
     CachePolicyHeadersConfigTypeDef,
     OriginRequestPolicyHeadersConfigTypeDef,
     CachePolicyQueryStringsConfigTypeDef,
     OriginRequestPolicyQueryStringsConfigTypeDef,
     CloudFrontOriginAccessIdentityTypeDef,
     CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef,
+    GetCloudFrontOriginAccessIdentityConfigResultTypeDef,
     UpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef,
     CloudFrontOriginAccessIdentityListTypeDef,
     ConflictingAliasesListTypeDef,
     ContentTypeProfilesTypeDef,
     ContinuousDeploymentSingleWeightConfigTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCloudFrontOriginAccessIdentityConfigResultTypeDef,
-    GetFunctionResultTypeDef,
     CreateFunctionRequestRequestTypeDef,
     UpdateFunctionRequestRequestTypeDef,
     CreateKeyGroupRequestRequestTypeDef,
     GetKeyGroupConfigResultTypeDef,
     KeyGroupTypeDef,
     UpdateKeyGroupRequestRequestTypeDef,
     CreateOriginAccessControlRequestRequestTypeDef,
@@ -558,18 +562,14 @@
     GetInvalidationRequestInvalidationCompletedWaitTypeDef,
     GetStreamingDistributionRequestStreamingDistributionDeployedWaitTypeDef,
     InvalidationBatchTypeDef,
     InvalidationListTypeDef,
     KGKeyPairIdsTypeDef,
     SignerTypeDef,
     LambdaFunctionAssociationsTypeDef,
-    ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef,
-    ListDistributionsRequestListDistributionsPaginateTypeDef,
-    ListInvalidationsRequestListInvalidationsPaginateTypeDef,
-    ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef,
     MonitoringSubscriptionTypeDef,
     OriginAccessControlListTypeDef,
     OriginGroupFailoverCriteriaTypeDef,
     OriginGroupMembersTypeDef,
     PublicKeyListTypeDef,
     QueryArgProfilesTypeDef,
     ResponseHeadersPolicyCorsConfigTypeDef,
@@ -746,43 +746,43 @@
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

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/setup.py` & `types-aiobotocore-cloudfront-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cloudfront.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cloudfront",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cloudfront"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CloudFront 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CloudFront 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/"
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

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/__init__.py` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/__init__.pyi` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/client.py` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -740,15 +740,16 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#generate_presigned_url)
         """
 
     async def get_cache_policy(self, *, Id: str) -> GetCachePolicyResultTypeDef:
         """
-        Gets a cache policy, including the following metadata * The policy's identifier.
+        Gets a cache policy, including the following metadata: * The policy's
+        identifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.get_cache_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#get_cache_policy)
         """
 
     async def get_cache_policy_config(self, *, Id: str) -> GetCachePolicyConfigResultTypeDef:
         """
@@ -917,15 +918,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.get_origin_access_control_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#get_origin_access_control_config)
         """
 
     async def get_origin_request_policy(self, *, Id: str) -> GetOriginRequestPolicyResultTypeDef:
         """
-        Gets an origin request policy, including the following metadata * The policy's
+        Gets an origin request policy, including the following metadata: * The policy's
         identifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.get_origin_request_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#get_origin_request_policy)
         """
 
     async def get_origin_request_policy_config(
```

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/client.pyi` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -696,15 +696,16 @@
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#generate_presigned_url)
         """
     async def get_cache_policy(self, *, Id: str) -> GetCachePolicyResultTypeDef:
         """
-        Gets a cache policy, including the following metadata * The policy's identifier.
+        Gets a cache policy, including the following metadata: * The policy's
+        identifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.get_cache_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#get_cache_policy)
         """
     async def get_cache_policy_config(self, *, Id: str) -> GetCachePolicyConfigResultTypeDef:
         """
         Gets a cache policy configuration.
@@ -854,15 +855,15 @@
         Gets a CloudFront origin access control configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.get_origin_access_control_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#get_origin_access_control_config)
         """
     async def get_origin_request_policy(self, *, Id: str) -> GetOriginRequestPolicyResultTypeDef:
         """
-        Gets an origin request policy, including the following metadata * The policy's
+        Gets an origin request policy, including the following metadata: * The policy's
         identifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Client.get_origin_request_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/client/#get_origin_request_policy)
         """
     async def get_origin_request_policy_config(
         self, *, Id: str
```

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/literals.py` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "CachePolicyCookieBehaviorType",
     "CachePolicyHeaderBehaviorType",
     "CachePolicyQueryStringBehaviorType",
     "CachePolicyTypeType",
     "CertificateSourceType",
     "ContinuousDeploymentPolicyTypeType",
@@ -63,15 +62,14 @@
     "CloudFrontServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
 )
 
-
 CachePolicyCookieBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 CachePolicyHeaderBehaviorType = Literal["none", "whitelist"]
 CachePolicyQueryStringBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 CachePolicyTypeType = Literal["custom", "managed"]
 CertificateSourceType = Literal["acm", "cloudfront", "iam"]
 ContinuousDeploymentPolicyTypeType = Literal["SingleHeader", "SingleWeight"]
 DistributionDeployedWaiterName = Literal["distribution_deployed"]
@@ -95,19 +93,19 @@
 MinimumProtocolVersionType = Literal[
     "SSLv3", "TLSv1", "TLSv1.1_2016", "TLSv1.2_2018", "TLSv1.2_2019", "TLSv1.2_2021", "TLSv1_2016"
 ]
 OriginAccessControlOriginTypesType = Literal["mediastore", "s3"]
 OriginAccessControlSigningBehaviorsType = Literal["always", "never", "no-override"]
 OriginAccessControlSigningProtocolsType = Literal["sigv4"]
 OriginProtocolPolicyType = Literal["http-only", "https-only", "match-viewer"]
-OriginRequestPolicyCookieBehaviorType = Literal["all", "none", "whitelist"]
+OriginRequestPolicyCookieBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 OriginRequestPolicyHeaderBehaviorType = Literal[
-    "allViewer", "allViewerAndWhitelistCloudFront", "none", "whitelist"
+    "allExcept", "allViewer", "allViewerAndWhitelistCloudFront", "none", "whitelist"
 ]
-OriginRequestPolicyQueryStringBehaviorType = Literal["all", "none", "whitelist"]
+OriginRequestPolicyQueryStringBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 OriginRequestPolicyTypeType = Literal["custom", "managed"]
 PriceClassType = Literal["PriceClass_100", "PriceClass_200", "PriceClass_All"]
 RealtimeMetricsSubscriptionStatusType = Literal["Disabled", "Enabled"]
 ReferrerPolicyListType = Literal[
     "no-referrer",
     "no-referrer-when-downgrade",
     "origin",
@@ -184,14 +182,15 @@
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
@@ -270,14 +269,15 @@
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
@@ -288,14 +288,15 @@
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
@@ -331,14 +332,15 @@
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
@@ -357,16 +359,19 @@
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
@@ -450,15 +455,17 @@
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

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/literals.pyi` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "CachePolicyCookieBehaviorType",
     "CachePolicyHeaderBehaviorType",
     "CachePolicyQueryStringBehaviorType",
     "CachePolicyTypeType",
     "CertificateSourceType",
     "ContinuousDeploymentPolicyTypeType",
@@ -62,14 +63,15 @@
     "CloudFrontServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
 )
 
+
 CachePolicyCookieBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 CachePolicyHeaderBehaviorType = Literal["none", "whitelist"]
 CachePolicyQueryStringBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 CachePolicyTypeType = Literal["custom", "managed"]
 CertificateSourceType = Literal["acm", "cloudfront", "iam"]
 ContinuousDeploymentPolicyTypeType = Literal["SingleHeader", "SingleWeight"]
 DistributionDeployedWaiterName = Literal["distribution_deployed"]
@@ -93,19 +95,19 @@
 MinimumProtocolVersionType = Literal[
     "SSLv3", "TLSv1", "TLSv1.1_2016", "TLSv1.2_2018", "TLSv1.2_2019", "TLSv1.2_2021", "TLSv1_2016"
 ]
 OriginAccessControlOriginTypesType = Literal["mediastore", "s3"]
 OriginAccessControlSigningBehaviorsType = Literal["always", "never", "no-override"]
 OriginAccessControlSigningProtocolsType = Literal["sigv4"]
 OriginProtocolPolicyType = Literal["http-only", "https-only", "match-viewer"]
-OriginRequestPolicyCookieBehaviorType = Literal["all", "none", "whitelist"]
+OriginRequestPolicyCookieBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 OriginRequestPolicyHeaderBehaviorType = Literal[
-    "allViewer", "allViewerAndWhitelistCloudFront", "none", "whitelist"
+    "allExcept", "allViewer", "allViewerAndWhitelistCloudFront", "none", "whitelist"
 ]
-OriginRequestPolicyQueryStringBehaviorType = Literal["all", "none", "whitelist"]
+OriginRequestPolicyQueryStringBehaviorType = Literal["all", "allExcept", "none", "whitelist"]
 OriginRequestPolicyTypeType = Literal["custom", "managed"]
 PriceClassType = Literal["PriceClass_100", "PriceClass_200", "PriceClass_All"]
 RealtimeMetricsSubscriptionStatusType = Literal["Disabled", "Enabled"]
 ReferrerPolicyListType = Literal[
     "no-referrer",
     "no-referrer-when-downgrade",
     "origin",
@@ -182,14 +184,15 @@
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
@@ -268,14 +271,15 @@
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
@@ -286,14 +290,15 @@
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
@@ -329,14 +334,15 @@
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
@@ -355,16 +361,19 @@
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
@@ -448,15 +457,17 @@
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

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/paginator.py` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,103 +22,90 @@
 
         list_cloud_front_origin_access_identities_paginator: ListCloudFrontOriginAccessIdentitiesPaginator = client.get_paginator("list_cloud_front_origin_access_identities")
         list_distributions_paginator: ListDistributionsPaginator = client.get_paginator("list_distributions")
         list_invalidations_paginator: ListInvalidationsPaginator = client.get_paginator("list_invalidations")
         list_streaming_distributions_paginator: ListStreamingDistributionsPaginator = client.get_paginator("list_streaming_distributions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListCloudFrontOriginAccessIdentitiesResultTypeDef,
     ListDistributionsResultTypeDef,
     ListInvalidationsResultTypeDef,
     ListStreamingDistributionsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListCloudFrontOriginAccessIdentitiesPaginator",
     "ListDistributionsPaginator",
     "ListInvalidationsPaginator",
     "ListStreamingDistributionsPaginator",
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
 class ListCloudFrontOriginAccessIdentitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListCloudFrontOriginAccessIdentities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listcloudfrontoriginaccessidentitiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCloudFrontOriginAccessIdentitiesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListCloudFrontOriginAccessIdentities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listcloudfrontoriginaccessidentitiespaginator)
         """
 
-
 class ListDistributionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListDistributions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listdistributionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDistributionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListDistributions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listdistributionspaginator)
         """
 
-
 class ListInvalidationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListInvalidations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listinvalidationspaginator)
     """
 
     def paginate(
-        self, *, DistributionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DistributionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvalidationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListInvalidations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listinvalidationspaginator)
         """
 
-
 class ListStreamingDistributionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListStreamingDistributions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#liststreamingdistributionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingDistributionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListStreamingDistributions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#liststreamingdistributionspaginator)
         """
```

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/paginator.pyi` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -22,96 +22,96 @@
 
         list_cloud_front_origin_access_identities_paginator: ListCloudFrontOriginAccessIdentitiesPaginator = client.get_paginator("list_cloud_front_origin_access_identities")
         list_distributions_paginator: ListDistributionsPaginator = client.get_paginator("list_distributions")
         list_invalidations_paginator: ListInvalidationsPaginator = client.get_paginator("list_invalidations")
         list_streaming_distributions_paginator: ListStreamingDistributionsPaginator = client.get_paginator("list_streaming_distributions")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListCloudFrontOriginAccessIdentitiesResultTypeDef,
     ListDistributionsResultTypeDef,
     ListInvalidationsResultTypeDef,
     ListStreamingDistributionsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListCloudFrontOriginAccessIdentitiesPaginator",
     "ListDistributionsPaginator",
     "ListInvalidationsPaginator",
     "ListStreamingDistributionsPaginator",
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
 class ListCloudFrontOriginAccessIdentitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListCloudFrontOriginAccessIdentities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listcloudfrontoriginaccessidentitiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCloudFrontOriginAccessIdentitiesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListCloudFrontOriginAccessIdentities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listcloudfrontoriginaccessidentitiespaginator)
         """
 
+
 class ListDistributionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListDistributions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listdistributionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDistributionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListDistributions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listdistributionspaginator)
         """
 
+
 class ListInvalidationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListInvalidations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listinvalidationspaginator)
     """
 
     def paginate(
-        self, *, DistributionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DistributionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInvalidationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListInvalidations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#listinvalidationspaginator)
         """
 
+
 class ListStreamingDistributionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListStreamingDistributions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#liststreamingdistributionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListStreamingDistributionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront.Paginator.ListStreamingDistributions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/paginators/#liststreamingdistributionspaginator)
         """
```

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/type_defs.py` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -74,15 +74,14 @@
     "CloudFrontOriginAccessIdentitySummaryTypeDef",
     "ConflictingAliasTypeDef",
     "ContentTypeProfileTypeDef",
     "StagingDistributionDnsNamesTypeDef",
     "ContinuousDeploymentSingleHeaderConfigTypeDef",
     "SessionStickinessConfigTypeDef",
     "CopyDistributionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "FunctionConfigTypeDef",
     "KeyGroupConfigTypeDef",
     "OriginAccessControlConfigTypeDef",
     "PublicKeyConfigTypeDef",
     "CustomErrorResponseTypeDef",
     "OriginCustomHeaderTypeDef",
     "OriginSslProtocolsTypeDef",
@@ -101,14 +100,15 @@
     "DeleteRealtimeLogConfigRequestRequestTypeDef",
     "DeleteResponseHeadersPolicyRequestRequestTypeDef",
     "DeleteStreamingDistributionRequestRequestTypeDef",
     "DescribeFunctionRequestRequestTypeDef",
     "LoggingConfigTypeDef",
     "ViewerCertificateTypeDef",
     "DistributionIdListTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FieldPatternsTypeDef",
     "KinesisStreamConfigTypeDef",
     "QueryStringCacheKeysTypeDef",
     "FunctionAssociationTypeDef",
     "FunctionMetadataTypeDef",
     "GeoRestrictionTypeDef",
     "GetCachePolicyConfigRequestRequestTypeDef",
@@ -121,14 +121,15 @@
     "WaiterConfigTypeDef",
     "GetDistributionRequestRequestTypeDef",
     "GetFieldLevelEncryptionConfigRequestRequestTypeDef",
     "GetFieldLevelEncryptionProfileConfigRequestRequestTypeDef",
     "GetFieldLevelEncryptionProfileRequestRequestTypeDef",
     "GetFieldLevelEncryptionRequestRequestTypeDef",
     "GetFunctionRequestRequestTypeDef",
+    "GetFunctionResultTypeDef",
     "GetInvalidationRequestRequestTypeDef",
     "GetKeyGroupConfigRequestRequestTypeDef",
     "GetKeyGroupRequestRequestTypeDef",
     "GetMonitoringSubscriptionRequestRequestTypeDef",
     "GetOriginAccessControlConfigRequestRequestTypeDef",
     "GetOriginAccessControlRequestRequestTypeDef",
     "GetOriginRequestPolicyConfigRequestRequestTypeDef",
@@ -141,43 +142,47 @@
     "GetStreamingDistributionConfigRequestRequestTypeDef",
     "GetStreamingDistributionRequestRequestTypeDef",
     "PathsTypeDef",
     "InvalidationSummaryTypeDef",
     "KeyPairIdsTypeDef",
     "LambdaFunctionAssociationTypeDef",
     "ListCachePoliciesRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
     "ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef",
     "ListConflictingAliasesRequestRequestTypeDef",
     "ListContinuousDeploymentPoliciesRequestRequestTypeDef",
     "ListDistributionsByCachePolicyIdRequestRequestTypeDef",
     "ListDistributionsByKeyGroupRequestRequestTypeDef",
     "ListDistributionsByOriginRequestPolicyIdRequestRequestTypeDef",
     "ListDistributionsByRealtimeLogConfigRequestRequestTypeDef",
     "ListDistributionsByResponseHeadersPolicyIdRequestRequestTypeDef",
     "ListDistributionsByWebACLIdRequestRequestTypeDef",
+    "ListDistributionsRequestListDistributionsPaginateTypeDef",
     "ListDistributionsRequestRequestTypeDef",
     "ListFieldLevelEncryptionConfigsRequestRequestTypeDef",
     "ListFieldLevelEncryptionProfilesRequestRequestTypeDef",
     "ListFunctionsRequestRequestTypeDef",
+    "ListInvalidationsRequestListInvalidationsPaginateTypeDef",
     "ListInvalidationsRequestRequestTypeDef",
     "ListKeyGroupsRequestRequestTypeDef",
     "ListOriginAccessControlsRequestRequestTypeDef",
     "ListOriginRequestPoliciesRequestRequestTypeDef",
     "ListPublicKeysRequestRequestTypeDef",
     "ListRealtimeLogConfigsRequestRequestTypeDef",
     "ListResponseHeadersPoliciesRequestRequestTypeDef",
+    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
     "ListStreamingDistributionsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "RealtimeMetricsSubscriptionConfigTypeDef",
     "OriginAccessControlSummaryTypeDef",
     "StatusCodesTypeDef",
     "OriginGroupMemberTypeDef",
     "OriginShieldTypeDef",
     "S3OriginConfigTypeDef",
+    "PaginatorConfigTypeDef",
     "PublicKeySummaryTypeDef",
     "PublishFunctionRequestRequestTypeDef",
     "QueryArgProfileTypeDef",
     "ResponseHeadersPolicyAccessControlAllowHeadersTypeDef",
     "ResponseHeadersPolicyAccessControlAllowMethodsTypeDef",
     "ResponseHeadersPolicyAccessControlAllowOriginsTypeDef",
     "ResponseHeadersPolicyAccessControlExposeHeadersTypeDef",
@@ -186,14 +191,15 @@
     "ResponseHeadersPolicyContentTypeOptionsTypeDef",
     "ResponseHeadersPolicyCustomHeaderTypeDef",
     "ResponseHeadersPolicyFrameOptionsTypeDef",
     "ResponseHeadersPolicyReferrerPolicyTypeDef",
     "ResponseHeadersPolicyRemoveHeaderTypeDef",
     "ResponseHeadersPolicyStrictTransportSecurityTypeDef",
     "ResponseHeadersPolicyXSSProtectionTypeDef",
+    "ResponseMetadataTypeDef",
     "S3OriginTypeDef",
     "StreamingLoggingConfigTypeDef",
     "TagKeysTypeDef",
     "TagTypeDef",
     "TestFunctionRequestRequestTypeDef",
     "UpdateDistributionWithStagingConfigRequestRequestTypeDef",
     "AllowedMethodsTypeDef",
@@ -202,22 +208,20 @@
     "OriginRequestPolicyCookiesConfigTypeDef",
     "CachePolicyHeadersConfigTypeDef",
     "OriginRequestPolicyHeadersConfigTypeDef",
     "CachePolicyQueryStringsConfigTypeDef",
     "OriginRequestPolicyQueryStringsConfigTypeDef",
     "CloudFrontOriginAccessIdentityTypeDef",
     "CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
+    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
     "UpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
     "CloudFrontOriginAccessIdentityListTypeDef",
     "ConflictingAliasesListTypeDef",
     "ContentTypeProfilesTypeDef",
     "ContinuousDeploymentSingleWeightConfigTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
-    "GetFunctionResultTypeDef",
     "CreateFunctionRequestRequestTypeDef",
     "UpdateFunctionRequestRequestTypeDef",
     "CreateKeyGroupRequestRequestTypeDef",
     "GetKeyGroupConfigResultTypeDef",
     "KeyGroupTypeDef",
     "UpdateKeyGroupRequestRequestTypeDef",
     "CreateOriginAccessControlRequestRequestTypeDef",
@@ -244,18 +248,14 @@
     "GetInvalidationRequestInvalidationCompletedWaitTypeDef",
     "GetStreamingDistributionRequestStreamingDistributionDeployedWaitTypeDef",
     "InvalidationBatchTypeDef",
     "InvalidationListTypeDef",
     "KGKeyPairIdsTypeDef",
     "SignerTypeDef",
     "LambdaFunctionAssociationsTypeDef",
-    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
-    "ListDistributionsRequestListDistributionsPaginateTypeDef",
-    "ListInvalidationsRequestListInvalidationsPaginateTypeDef",
-    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
     "MonitoringSubscriptionTypeDef",
     "OriginAccessControlListTypeDef",
     "OriginGroupFailoverCriteriaTypeDef",
     "OriginGroupMembersTypeDef",
     "PublicKeyListTypeDef",
     "QueryArgProfilesTypeDef",
     "ResponseHeadersPolicyCorsConfigTypeDef",
@@ -670,25 +670,14 @@
 
 class CopyDistributionRequestRequestTypeDef(
     _RequiredCopyDistributionRequestRequestTypeDef, _OptionalCopyDistributionRequestRequestTypeDef
 ):
     pass
 
 
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
 FunctionConfigTypeDef = TypedDict(
     "FunctionConfigTypeDef",
     {
         "Comment": str,
         "Runtime": Literal["cloudfront-js-1.0"],
     },
 )
@@ -1148,14 +1137,21 @@
 
 class DistributionIdListTypeDef(
     _RequiredDistributionIdListTypeDef, _OptionalDistributionIdListTypeDef
 ):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFieldPatternsTypeDef = TypedDict(
     "_RequiredFieldPatternsTypeDef",
     {
         "Quantity": int,
     },
 )
 _OptionalFieldPatternsTypeDef = TypedDict(
@@ -1359,14 +1355,24 @@
 
 class GetFunctionRequestRequestTypeDef(
     _RequiredGetFunctionRequestRequestTypeDef, _OptionalGetFunctionRequestRequestTypeDef
 ):
     pass
 
 
+GetFunctionResultTypeDef = TypedDict(
+    "GetFunctionResultTypeDef",
+    {
+        "FunctionCode": StreamingBody,
+        "ETag": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInvalidationRequestRequestTypeDef = TypedDict(
     "GetInvalidationRequestRequestTypeDef",
     {
         "DistributionId": str,
         "Id": str,
     },
 )
@@ -1546,20 +1552,18 @@
         "Type": CachePolicyTypeType,
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef = TypedDict(
+    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef = TypedDict(
     "ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef",
     {
@@ -1724,14 +1728,22 @@
 class ListDistributionsByWebACLIdRequestRequestTypeDef(
     _RequiredListDistributionsByWebACLIdRequestRequestTypeDef,
     _OptionalListDistributionsByWebACLIdRequestRequestTypeDef,
 ):
     pass
 
 
+ListDistributionsRequestListDistributionsPaginateTypeDef = TypedDict(
+    "ListDistributionsRequestListDistributionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDistributionsRequestRequestTypeDef = TypedDict(
     "ListDistributionsRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
@@ -1761,14 +1773,36 @@
         "Marker": str,
         "MaxItems": str,
         "Stage": FunctionStageType,
     },
     total=False,
 )
 
+_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
+    "_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef",
+    {
+        "DistributionId": str,
+    },
+)
+_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
+    "_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListInvalidationsRequestListInvalidationsPaginateTypeDef(
+    _RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef,
+    _OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListInvalidationsRequestRequestTypeDef = TypedDict(
     "_RequiredListInvalidationsRequestRequestTypeDef",
     {
         "DistributionId": str,
     },
 )
 _OptionalListInvalidationsRequestRequestTypeDef = TypedDict(
@@ -1839,14 +1873,22 @@
         "Type": ResponseHeadersPolicyTypeType,
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
 )
 
+ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef = TypedDict(
+    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStreamingDistributionsRequestRequestTypeDef = TypedDict(
     "ListStreamingDistributionsRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
@@ -1915,14 +1957,24 @@
 S3OriginConfigTypeDef = TypedDict(
     "S3OriginConfigTypeDef",
     {
         "OriginAccessIdentity": str,
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
 _RequiredPublicKeySummaryTypeDef = TypedDict(
     "_RequiredPublicKeySummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "CreatedTime": datetime,
         "EncodedKey": str,
@@ -2116,14 +2168,25 @@
 class ResponseHeadersPolicyXSSProtectionTypeDef(
     _RequiredResponseHeadersPolicyXSSProtectionTypeDef,
     _OptionalResponseHeadersPolicyXSSProtectionTypeDef,
 ):
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
 S3OriginTypeDef = TypedDict(
     "S3OriginTypeDef",
     {
         "DomainName": str,
         "OriginAccessIdentity": str,
     },
 )
@@ -2403,14 +2466,23 @@
 CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef = TypedDict(
     "CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
     {
         "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
     },
 )
 
+GetCloudFrontOriginAccessIdentityConfigResultTypeDef = TypedDict(
+    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
+    {
+        "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
+        "ETag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
     {
         "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
         "Id": str,
     },
 )
@@ -2506,40 +2578,14 @@
 class ContinuousDeploymentSingleWeightConfigTypeDef(
     _RequiredContinuousDeploymentSingleWeightConfigTypeDef,
     _OptionalContinuousDeploymentSingleWeightConfigTypeDef,
 ):
     pass
 
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCloudFrontOriginAccessIdentityConfigResultTypeDef = TypedDict(
-    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
-    {
-        "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
-        "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFunctionResultTypeDef = TypedDict(
-    "GetFunctionResultTypeDef",
-    {
-        "FunctionCode": StreamingBody,
-        "ETag": str,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateFunctionRequestRequestTypeDef = TypedDict(
     "CreateFunctionRequestRequestTypeDef",
     {
         "Name": str,
         "FunctionConfig": FunctionConfigTypeDef,
         "FunctionCode": Union[str, bytes, IO[Any], StreamingBody],
     },
@@ -2563,15 +2609,15 @@
 )
 
 GetKeyGroupConfigResultTypeDef = TypedDict(
     "GetKeyGroupConfigResultTypeDef",
     {
         "KeyGroupConfig": KeyGroupConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 KeyGroupTypeDef = TypedDict(
     "KeyGroupTypeDef",
     {
         "Id": str,
@@ -2610,15 +2656,15 @@
 )
 
 GetOriginAccessControlConfigResultTypeDef = TypedDict(
     "GetOriginAccessControlConfigResultTypeDef",
     {
         "OriginAccessControlConfig": OriginAccessControlConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOriginAccessControlTypeDef = TypedDict(
     "_RequiredOriginAccessControlTypeDef",
     {
         "Id": str,
@@ -2670,15 +2716,15 @@
 )
 
 GetPublicKeyConfigResultTypeDef = TypedDict(
     "GetPublicKeyConfigResultTypeDef",
     {
         "PublicKeyConfig": PublicKeyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PublicKeyTypeDef = TypedDict(
     "PublicKeyTypeDef",
     {
         "Id": str,
@@ -2774,39 +2820,39 @@
     pass
 
 
 ListDistributionsByCachePolicyIdResultTypeDef = TypedDict(
     "ListDistributionsByCachePolicyIdResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByKeyGroupResultTypeDef = TypedDict(
     "ListDistributionsByKeyGroupResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByOriginRequestPolicyIdResultTypeDef = TypedDict(
     "ListDistributionsByOriginRequestPolicyIdResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByResponseHeadersPolicyIdResultTypeDef = TypedDict(
     "ListDistributionsByResponseHeadersPolicyIdResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EncryptionEntityTypeDef = TypedDict(
     "EncryptionEntityTypeDef",
     {
         "PublicKeyId": str,
@@ -3016,60 +3062,14 @@
 
 class LambdaFunctionAssociationsTypeDef(
     _RequiredLambdaFunctionAssociationsTypeDef, _OptionalLambdaFunctionAssociationsTypeDef
 ):
     pass
 
 
-ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef = TypedDict(
-    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDistributionsRequestListDistributionsPaginateTypeDef = TypedDict(
-    "ListDistributionsRequestListDistributionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
-    "_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef",
-    {
-        "DistributionId": str,
-    },
-)
-_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
-    "_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListInvalidationsRequestListInvalidationsPaginateTypeDef(
-    _RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef,
-    _OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef,
-):
-    pass
-
-
-ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef = TypedDict(
-    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 MonitoringSubscriptionTypeDef = TypedDict(
     "MonitoringSubscriptionTypeDef",
     {
         "RealtimeMetricsSubscriptionConfig": RealtimeMetricsSubscriptionConfigTypeDef,
     },
     total=False,
 )
@@ -3369,49 +3369,49 @@
 
 CreateCloudFrontOriginAccessIdentityResultTypeDef = TypedDict(
     "CreateCloudFrontOriginAccessIdentityResultTypeDef",
     {
         "CloudFrontOriginAccessIdentity": CloudFrontOriginAccessIdentityTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCloudFrontOriginAccessIdentityResultTypeDef = TypedDict(
     "GetCloudFrontOriginAccessIdentityResultTypeDef",
     {
         "CloudFrontOriginAccessIdentity": CloudFrontOriginAccessIdentityTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCloudFrontOriginAccessIdentityResultTypeDef = TypedDict(
     "UpdateCloudFrontOriginAccessIdentityResultTypeDef",
     {
         "CloudFrontOriginAccessIdentity": CloudFrontOriginAccessIdentityTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCloudFrontOriginAccessIdentitiesResultTypeDef = TypedDict(
     "ListCloudFrontOriginAccessIdentitiesResultTypeDef",
     {
         "CloudFrontOriginAccessIdentityList": CloudFrontOriginAccessIdentityListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConflictingAliasesResultTypeDef = TypedDict(
     "ListConflictingAliasesResultTypeDef",
     {
         "ConflictingAliasesList": ConflictingAliasesListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredContentTypeProfileConfigTypeDef = TypedDict(
     "_RequiredContentTypeProfileConfigTypeDef",
     {
         "ForwardWhenContentTypeIsUnknown": bool,
@@ -3454,24 +3454,24 @@
 
 CreateKeyGroupResultTypeDef = TypedDict(
     "CreateKeyGroupResultTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKeyGroupResultTypeDef = TypedDict(
     "GetKeyGroupResultTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 KeyGroupSummaryTypeDef = TypedDict(
     "KeyGroupSummaryTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
@@ -3479,71 +3479,71 @@
 )
 
 UpdateKeyGroupResultTypeDef = TypedDict(
     "UpdateKeyGroupResultTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOriginAccessControlResultTypeDef = TypedDict(
     "CreateOriginAccessControlResultTypeDef",
     {
         "OriginAccessControl": OriginAccessControlTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOriginAccessControlResultTypeDef = TypedDict(
     "GetOriginAccessControlResultTypeDef",
     {
         "OriginAccessControl": OriginAccessControlTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateOriginAccessControlResultTypeDef = TypedDict(
     "UpdateOriginAccessControlResultTypeDef",
     {
         "OriginAccessControl": OriginAccessControlTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePublicKeyResultTypeDef = TypedDict(
     "CreatePublicKeyResultTypeDef",
     {
         "PublicKey": PublicKeyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPublicKeyResultTypeDef = TypedDict(
     "GetPublicKeyResultTypeDef",
     {
         "PublicKey": PublicKeyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePublicKeyResultTypeDef = TypedDict(
     "UpdatePublicKeyResultTypeDef",
     {
         "PublicKey": PublicKeyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOriginTypeDef = TypedDict(
     "_RequiredOriginTypeDef",
     {
         "Id": str,
@@ -3626,24 +3626,24 @@
 
 CreateFunctionResultTypeDef = TypedDict(
     "CreateFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFunctionResultTypeDef = TypedDict(
     "DescribeFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFunctionListTypeDef = TypedDict(
     "_RequiredFunctionListTypeDef",
     {
         "MaxItems": int,
@@ -3664,15 +3664,15 @@
     pass
 
 
 PublishFunctionResultTypeDef = TypedDict(
     "PublishFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestResultTypeDef = TypedDict(
     "TestResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
@@ -3685,15 +3685,15 @@
 )
 
 UpdateFunctionResultTypeDef = TypedDict(
     "UpdateFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInvalidationRequestRequestTypeDef = TypedDict(
     "CreateInvalidationRequestRequestTypeDef",
     {
         "DistributionId": str,
@@ -3711,15 +3711,15 @@
     },
 )
 
 ListInvalidationsResultTypeDef = TypedDict(
     "ListInvalidationsResultTypeDef",
     {
         "InvalidationList": InvalidationListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActiveTrustedKeyGroupsTypeDef = TypedDict(
     "_RequiredActiveTrustedKeyGroupsTypeDef",
     {
         "Enabled": bool,
@@ -3771,31 +3771,31 @@
     },
 )
 
 CreateMonitoringSubscriptionResultTypeDef = TypedDict(
     "CreateMonitoringSubscriptionResultTypeDef",
     {
         "MonitoringSubscription": MonitoringSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMonitoringSubscriptionResultTypeDef = TypedDict(
     "GetMonitoringSubscriptionResultTypeDef",
     {
         "MonitoringSubscription": MonitoringSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOriginAccessControlsResultTypeDef = TypedDict(
     "ListOriginAccessControlsResultTypeDef",
     {
         "OriginAccessControlList": OriginAccessControlListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginGroupTypeDef = TypedDict(
     "OriginGroupTypeDef",
     {
         "Id": str,
@@ -3804,15 +3804,15 @@
     },
 )
 
 ListPublicKeysResultTypeDef = TypedDict(
     "ListPublicKeysResultTypeDef",
     {
         "PublicKeyList": PublicKeyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredQueryArgProfileConfigTypeDef = TypedDict(
     "_RequiredQueryArgProfileConfigTypeDef",
     {
         "ForwardWhenQueryArgProfileIsUnknown": bool,
@@ -3892,15 +3892,15 @@
 )
 
 GetStreamingDistributionConfigResultTypeDef = TypedDict(
     "GetStreamingDistributionConfigResultTypeDef",
     {
         "StreamingDistributionConfig": StreamingDistributionConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateStreamingDistributionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStreamingDistributionRequestRequestTypeDef",
     {
         "StreamingDistributionConfig": StreamingDistributionConfigTypeDef,
@@ -3923,15 +3923,15 @@
     pass
 
 
 ListTagsForResourceResultTypeDef = TypedDict(
     "ListTagsForResourceResultTypeDef",
     {
         "Tags": TagsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StreamingDistributionConfigWithTagsTypeDef = TypedDict(
     "StreamingDistributionConfigWithTagsTypeDef",
     {
         "StreamingDistributionConfig": StreamingDistributionConfigTypeDef,
@@ -4053,15 +4053,15 @@
 )
 
 GetOriginRequestPolicyConfigResultTypeDef = TypedDict(
     "GetOriginRequestPolicyConfigResultTypeDef",
     {
         "OriginRequestPolicyConfig": OriginRequestPolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginRequestPolicyTypeDef = TypedDict(
     "OriginRequestPolicyTypeDef",
     {
         "Id": str,
@@ -4194,23 +4194,23 @@
     pass
 
 
 CreateRealtimeLogConfigResultTypeDef = TypedDict(
     "CreateRealtimeLogConfigResultTypeDef",
     {
         "RealtimeLogConfig": RealtimeLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRealtimeLogConfigResultTypeDef = TypedDict(
     "GetRealtimeLogConfigResultTypeDef",
     {
         "RealtimeLogConfig": RealtimeLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRealtimeLogConfigsTypeDef = TypedDict(
     "_RequiredRealtimeLogConfigsTypeDef",
     {
         "MaxItems": int,
@@ -4234,48 +4234,48 @@
     pass
 
 
 UpdateRealtimeLogConfigResultTypeDef = TypedDict(
     "UpdateRealtimeLogConfigResultTypeDef",
     {
         "RealtimeLogConfig": RealtimeLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionsResultTypeDef = TypedDict(
     "ListFunctionsResultTypeDef",
     {
         "FunctionList": FunctionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestFunctionResultTypeDef = TypedDict(
     "TestFunctionResultTypeDef",
     {
         "TestResult": TestResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInvalidationResultTypeDef = TypedDict(
     "CreateInvalidationResultTypeDef",
     {
         "Location": str,
         "Invalidation": InvalidationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInvalidationResultTypeDef = TypedDict(
     "GetInvalidationResultTypeDef",
     {
         "Invalidation": InvalidationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStreamingDistributionTypeDef = TypedDict(
     "_RequiredStreamingDistributionTypeDef",
     {
         "Id": str,
@@ -4375,15 +4375,15 @@
 )
 
 GetResponseHeadersPolicyConfigResultTypeDef = TypedDict(
     "GetResponseHeadersPolicyConfigResultTypeDef",
     {
         "ResponseHeadersPolicyConfig": ResponseHeadersPolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseHeadersPolicyTypeDef = TypedDict(
     "ResponseHeadersPolicyTypeDef",
     {
         "Id": str,
@@ -4415,15 +4415,15 @@
     pass
 
 
 ListStreamingDistributionsResultTypeDef = TypedDict(
     "ListStreamingDistributionsResultTypeDef",
     {
         "StreamingDistributionList": StreamingDistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingDistributionWithTagsRequestRequestTypeDef = TypedDict(
     "CreateStreamingDistributionWithTagsRequestRequestTypeDef",
     {
         "StreamingDistributionConfigWithTags": StreamingDistributionConfigWithTagsTypeDef,
@@ -4466,15 +4466,15 @@
 )
 
 GetCachePolicyConfigResultTypeDef = TypedDict(
     "GetCachePolicyConfigResultTypeDef",
     {
         "CachePolicyConfig": CachePolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateCachePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCachePolicyRequestRequestTypeDef",
     {
         "CachePolicyConfig": CachePolicyConfigTypeDef,
@@ -4498,24 +4498,24 @@
 
 CreateOriginRequestPolicyResultTypeDef = TypedDict(
     "CreateOriginRequestPolicyResultTypeDef",
     {
         "OriginRequestPolicy": OriginRequestPolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOriginRequestPolicyResultTypeDef = TypedDict(
     "GetOriginRequestPolicyResultTypeDef",
     {
         "OriginRequestPolicy": OriginRequestPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginRequestPolicySummaryTypeDef = TypedDict(
     "OriginRequestPolicySummaryTypeDef",
     {
         "Type": OriginRequestPolicyTypeType,
@@ -4524,15 +4524,15 @@
 )
 
 UpdateOriginRequestPolicyResultTypeDef = TypedDict(
     "UpdateOriginRequestPolicyResultTypeDef",
     {
         "OriginRequestPolicy": OriginRequestPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContinuousDeploymentPolicyTypeDef = TypedDict(
     "ContinuousDeploymentPolicyTypeDef",
     {
         "Id": str,
@@ -4549,15 +4549,15 @@
 )
 
 GetContinuousDeploymentPolicyConfigResultTypeDef = TypedDict(
     "GetContinuousDeploymentPolicyConfigResultTypeDef",
     {
         "ContinuousDeploymentPolicyConfig": ContinuousDeploymentPolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContinuousDeploymentPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContinuousDeploymentPolicyRequestRequestTypeDef",
     {
         "ContinuousDeploymentPolicyConfig": ContinuousDeploymentPolicyConfigTypeDef,
@@ -4580,15 +4580,15 @@
     pass
 
 
 ListKeyGroupsResultTypeDef = TypedDict(
     "ListKeyGroupsResultTypeDef",
     {
         "KeyGroupList": KeyGroupListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionProfileRequestRequestTypeDef = TypedDict(
     "CreateFieldLevelEncryptionProfileRequestRequestTypeDef",
     {
         "FieldLevelEncryptionProfileConfig": FieldLevelEncryptionProfileConfigTypeDef,
@@ -4605,15 +4605,15 @@
 )
 
 GetFieldLevelEncryptionProfileConfigResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionProfileConfigResultTypeDef",
     {
         "FieldLevelEncryptionProfileConfig": FieldLevelEncryptionProfileConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFieldLevelEncryptionProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFieldLevelEncryptionProfileRequestRequestTypeDef",
     {
         "FieldLevelEncryptionProfileConfig": FieldLevelEncryptionProfileConfigTypeDef,
@@ -4659,53 +4659,53 @@
     pass
 
 
 ListRealtimeLogConfigsResultTypeDef = TypedDict(
     "ListRealtimeLogConfigsResultTypeDef",
     {
         "RealtimeLogConfigs": RealtimeLogConfigsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingDistributionResultTypeDef = TypedDict(
     "CreateStreamingDistributionResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingDistributionWithTagsResultTypeDef = TypedDict(
     "CreateStreamingDistributionWithTagsResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingDistributionResultTypeDef = TypedDict(
     "GetStreamingDistributionResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStreamingDistributionResultTypeDef = TypedDict(
     "UpdateStreamingDistributionResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionConfigRequestRequestTypeDef = TypedDict(
     "CreateFieldLevelEncryptionConfigRequestRequestTypeDef",
     {
         "FieldLevelEncryptionConfig": FieldLevelEncryptionConfigTypeDef,
@@ -4722,15 +4722,15 @@
 )
 
 GetFieldLevelEncryptionConfigResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionConfigResultTypeDef",
     {
         "FieldLevelEncryptionConfig": FieldLevelEncryptionConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFieldLevelEncryptionConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFieldLevelEncryptionConfigRequestRequestTypeDef",
     {
         "FieldLevelEncryptionConfig": FieldLevelEncryptionConfigTypeDef,
@@ -4778,24 +4778,24 @@
 
 CreateResponseHeadersPolicyResultTypeDef = TypedDict(
     "CreateResponseHeadersPolicyResultTypeDef",
     {
         "ResponseHeadersPolicy": ResponseHeadersPolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResponseHeadersPolicyResultTypeDef = TypedDict(
     "GetResponseHeadersPolicyResultTypeDef",
     {
         "ResponseHeadersPolicy": ResponseHeadersPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseHeadersPolicySummaryTypeDef = TypedDict(
     "ResponseHeadersPolicySummaryTypeDef",
     {
         "Type": ResponseHeadersPolicyTypeType,
@@ -4804,15 +4804,15 @@
 )
 
 UpdateResponseHeadersPolicyResultTypeDef = TypedDict(
     "UpdateResponseHeadersPolicyResultTypeDef",
     {
         "ResponseHeadersPolicy": ResponseHeadersPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDistributionConfigTypeDef = TypedDict(
     "_RequiredDistributionConfigTypeDef",
     {
         "CallerReference": str,
@@ -4900,33 +4900,33 @@
 
 CreateCachePolicyResultTypeDef = TypedDict(
     "CreateCachePolicyResultTypeDef",
     {
         "CachePolicy": CachePolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCachePolicyResultTypeDef = TypedDict(
     "GetCachePolicyResultTypeDef",
     {
         "CachePolicy": CachePolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCachePolicyResultTypeDef = TypedDict(
     "UpdateCachePolicyResultTypeDef",
     {
         "CachePolicy": CachePolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOriginRequestPolicyListTypeDef = TypedDict(
     "_RequiredOriginRequestPolicyListTypeDef",
     {
         "MaxItems": int,
@@ -4958,105 +4958,105 @@
 
 CreateContinuousDeploymentPolicyResultTypeDef = TypedDict(
     "CreateContinuousDeploymentPolicyResultTypeDef",
     {
         "ContinuousDeploymentPolicy": ContinuousDeploymentPolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContinuousDeploymentPolicyResultTypeDef = TypedDict(
     "GetContinuousDeploymentPolicyResultTypeDef",
     {
         "ContinuousDeploymentPolicy": ContinuousDeploymentPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContinuousDeploymentPolicyResultTypeDef = TypedDict(
     "UpdateContinuousDeploymentPolicyResultTypeDef",
     {
         "ContinuousDeploymentPolicy": ContinuousDeploymentPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionProfileResultTypeDef = TypedDict(
     "CreateFieldLevelEncryptionProfileResultTypeDef",
     {
         "FieldLevelEncryptionProfile": FieldLevelEncryptionProfileTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFieldLevelEncryptionProfileResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionProfileResultTypeDef",
     {
         "FieldLevelEncryptionProfile": FieldLevelEncryptionProfileTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFieldLevelEncryptionProfileResultTypeDef = TypedDict(
     "UpdateFieldLevelEncryptionProfileResultTypeDef",
     {
         "FieldLevelEncryptionProfile": FieldLevelEncryptionProfileTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFieldLevelEncryptionProfilesResultTypeDef = TypedDict(
     "ListFieldLevelEncryptionProfilesResultTypeDef",
     {
         "FieldLevelEncryptionProfileList": FieldLevelEncryptionProfileListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionConfigResultTypeDef = TypedDict(
     "CreateFieldLevelEncryptionConfigResultTypeDef",
     {
         "FieldLevelEncryption": FieldLevelEncryptionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFieldLevelEncryptionResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionResultTypeDef",
     {
         "FieldLevelEncryption": FieldLevelEncryptionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFieldLevelEncryptionConfigResultTypeDef = TypedDict(
     "UpdateFieldLevelEncryptionConfigResultTypeDef",
     {
         "FieldLevelEncryption": FieldLevelEncryptionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFieldLevelEncryptionConfigsResultTypeDef = TypedDict(
     "ListFieldLevelEncryptionConfigsResultTypeDef",
     {
         "FieldLevelEncryptionList": FieldLevelEncryptionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResponseHeadersPolicyListTypeDef = TypedDict(
     "_RequiredResponseHeadersPolicyListTypeDef",
     {
         "MaxItems": int,
@@ -5122,15 +5122,15 @@
 
 
 GetDistributionConfigResultTypeDef = TypedDict(
     "GetDistributionConfigResultTypeDef",
     {
         "DistributionConfig": DistributionConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDistributionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDistributionRequestRequestTypeDef",
     {
         "DistributionConfig": DistributionConfigTypeDef,
@@ -5197,15 +5197,15 @@
     pass
 
 
 ListOriginRequestPoliciesResultTypeDef = TypedDict(
     "ListOriginRequestPoliciesResultTypeDef",
     {
         "OriginRequestPolicyList": OriginRequestPolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredContinuousDeploymentPolicyListTypeDef = TypedDict(
     "_RequiredContinuousDeploymentPolicyListTypeDef",
     {
         "MaxItems": int,
@@ -5228,15 +5228,15 @@
     pass
 
 
 ListResponseHeadersPoliciesResultTypeDef = TypedDict(
     "ListResponseHeadersPoliciesResultTypeDef",
     {
         "ResponseHeadersPolicyList": ResponseHeadersPolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionWithTagsRequestRequestTypeDef = TypedDict(
     "CreateDistributionWithTagsRequestRequestTypeDef",
     {
         "DistributionConfigWithTags": DistributionConfigWithTagsTypeDef,
@@ -5245,97 +5245,97 @@
 
 CopyDistributionResultTypeDef = TypedDict(
     "CopyDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionResultTypeDef = TypedDict(
     "CreateDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionWithTagsResultTypeDef = TypedDict(
     "CreateDistributionWithTagsResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionResultTypeDef = TypedDict(
     "GetDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionResultTypeDef = TypedDict(
     "UpdateDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionWithStagingConfigResultTypeDef = TypedDict(
     "UpdateDistributionWithStagingConfigResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByRealtimeLogConfigResultTypeDef = TypedDict(
     "ListDistributionsByRealtimeLogConfigResultTypeDef",
     {
         "DistributionList": DistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByWebACLIdResultTypeDef = TypedDict(
     "ListDistributionsByWebACLIdResultTypeDef",
     {
         "DistributionList": DistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsResultTypeDef = TypedDict(
     "ListDistributionsResultTypeDef",
     {
         "DistributionList": DistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCachePoliciesResultTypeDef = TypedDict(
     "ListCachePoliciesResultTypeDef",
     {
         "CachePolicyList": CachePolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListContinuousDeploymentPoliciesResultTypeDef = TypedDict(
     "ListContinuousDeploymentPoliciesResultTypeDef",
     {
         "ContinuousDeploymentPolicyList": ContinuousDeploymentPolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/type_defs.pyi` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -73,15 +73,14 @@
     "CloudFrontOriginAccessIdentitySummaryTypeDef",
     "ConflictingAliasTypeDef",
     "ContentTypeProfileTypeDef",
     "StagingDistributionDnsNamesTypeDef",
     "ContinuousDeploymentSingleHeaderConfigTypeDef",
     "SessionStickinessConfigTypeDef",
     "CopyDistributionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "FunctionConfigTypeDef",
     "KeyGroupConfigTypeDef",
     "OriginAccessControlConfigTypeDef",
     "PublicKeyConfigTypeDef",
     "CustomErrorResponseTypeDef",
     "OriginCustomHeaderTypeDef",
     "OriginSslProtocolsTypeDef",
@@ -100,14 +99,15 @@
     "DeleteRealtimeLogConfigRequestRequestTypeDef",
     "DeleteResponseHeadersPolicyRequestRequestTypeDef",
     "DeleteStreamingDistributionRequestRequestTypeDef",
     "DescribeFunctionRequestRequestTypeDef",
     "LoggingConfigTypeDef",
     "ViewerCertificateTypeDef",
     "DistributionIdListTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FieldPatternsTypeDef",
     "KinesisStreamConfigTypeDef",
     "QueryStringCacheKeysTypeDef",
     "FunctionAssociationTypeDef",
     "FunctionMetadataTypeDef",
     "GeoRestrictionTypeDef",
     "GetCachePolicyConfigRequestRequestTypeDef",
@@ -120,14 +120,15 @@
     "WaiterConfigTypeDef",
     "GetDistributionRequestRequestTypeDef",
     "GetFieldLevelEncryptionConfigRequestRequestTypeDef",
     "GetFieldLevelEncryptionProfileConfigRequestRequestTypeDef",
     "GetFieldLevelEncryptionProfileRequestRequestTypeDef",
     "GetFieldLevelEncryptionRequestRequestTypeDef",
     "GetFunctionRequestRequestTypeDef",
+    "GetFunctionResultTypeDef",
     "GetInvalidationRequestRequestTypeDef",
     "GetKeyGroupConfigRequestRequestTypeDef",
     "GetKeyGroupRequestRequestTypeDef",
     "GetMonitoringSubscriptionRequestRequestTypeDef",
     "GetOriginAccessControlConfigRequestRequestTypeDef",
     "GetOriginAccessControlRequestRequestTypeDef",
     "GetOriginRequestPolicyConfigRequestRequestTypeDef",
@@ -140,43 +141,47 @@
     "GetStreamingDistributionConfigRequestRequestTypeDef",
     "GetStreamingDistributionRequestRequestTypeDef",
     "PathsTypeDef",
     "InvalidationSummaryTypeDef",
     "KeyPairIdsTypeDef",
     "LambdaFunctionAssociationTypeDef",
     "ListCachePoliciesRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
     "ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef",
     "ListConflictingAliasesRequestRequestTypeDef",
     "ListContinuousDeploymentPoliciesRequestRequestTypeDef",
     "ListDistributionsByCachePolicyIdRequestRequestTypeDef",
     "ListDistributionsByKeyGroupRequestRequestTypeDef",
     "ListDistributionsByOriginRequestPolicyIdRequestRequestTypeDef",
     "ListDistributionsByRealtimeLogConfigRequestRequestTypeDef",
     "ListDistributionsByResponseHeadersPolicyIdRequestRequestTypeDef",
     "ListDistributionsByWebACLIdRequestRequestTypeDef",
+    "ListDistributionsRequestListDistributionsPaginateTypeDef",
     "ListDistributionsRequestRequestTypeDef",
     "ListFieldLevelEncryptionConfigsRequestRequestTypeDef",
     "ListFieldLevelEncryptionProfilesRequestRequestTypeDef",
     "ListFunctionsRequestRequestTypeDef",
+    "ListInvalidationsRequestListInvalidationsPaginateTypeDef",
     "ListInvalidationsRequestRequestTypeDef",
     "ListKeyGroupsRequestRequestTypeDef",
     "ListOriginAccessControlsRequestRequestTypeDef",
     "ListOriginRequestPoliciesRequestRequestTypeDef",
     "ListPublicKeysRequestRequestTypeDef",
     "ListRealtimeLogConfigsRequestRequestTypeDef",
     "ListResponseHeadersPoliciesRequestRequestTypeDef",
+    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
     "ListStreamingDistributionsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "RealtimeMetricsSubscriptionConfigTypeDef",
     "OriginAccessControlSummaryTypeDef",
     "StatusCodesTypeDef",
     "OriginGroupMemberTypeDef",
     "OriginShieldTypeDef",
     "S3OriginConfigTypeDef",
+    "PaginatorConfigTypeDef",
     "PublicKeySummaryTypeDef",
     "PublishFunctionRequestRequestTypeDef",
     "QueryArgProfileTypeDef",
     "ResponseHeadersPolicyAccessControlAllowHeadersTypeDef",
     "ResponseHeadersPolicyAccessControlAllowMethodsTypeDef",
     "ResponseHeadersPolicyAccessControlAllowOriginsTypeDef",
     "ResponseHeadersPolicyAccessControlExposeHeadersTypeDef",
@@ -185,14 +190,15 @@
     "ResponseHeadersPolicyContentTypeOptionsTypeDef",
     "ResponseHeadersPolicyCustomHeaderTypeDef",
     "ResponseHeadersPolicyFrameOptionsTypeDef",
     "ResponseHeadersPolicyReferrerPolicyTypeDef",
     "ResponseHeadersPolicyRemoveHeaderTypeDef",
     "ResponseHeadersPolicyStrictTransportSecurityTypeDef",
     "ResponseHeadersPolicyXSSProtectionTypeDef",
+    "ResponseMetadataTypeDef",
     "S3OriginTypeDef",
     "StreamingLoggingConfigTypeDef",
     "TagKeysTypeDef",
     "TagTypeDef",
     "TestFunctionRequestRequestTypeDef",
     "UpdateDistributionWithStagingConfigRequestRequestTypeDef",
     "AllowedMethodsTypeDef",
@@ -201,22 +207,20 @@
     "OriginRequestPolicyCookiesConfigTypeDef",
     "CachePolicyHeadersConfigTypeDef",
     "OriginRequestPolicyHeadersConfigTypeDef",
     "CachePolicyQueryStringsConfigTypeDef",
     "OriginRequestPolicyQueryStringsConfigTypeDef",
     "CloudFrontOriginAccessIdentityTypeDef",
     "CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
+    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
     "UpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
     "CloudFrontOriginAccessIdentityListTypeDef",
     "ConflictingAliasesListTypeDef",
     "ContentTypeProfilesTypeDef",
     "ContinuousDeploymentSingleWeightConfigTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
-    "GetFunctionResultTypeDef",
     "CreateFunctionRequestRequestTypeDef",
     "UpdateFunctionRequestRequestTypeDef",
     "CreateKeyGroupRequestRequestTypeDef",
     "GetKeyGroupConfigResultTypeDef",
     "KeyGroupTypeDef",
     "UpdateKeyGroupRequestRequestTypeDef",
     "CreateOriginAccessControlRequestRequestTypeDef",
@@ -243,18 +247,14 @@
     "GetInvalidationRequestInvalidationCompletedWaitTypeDef",
     "GetStreamingDistributionRequestStreamingDistributionDeployedWaitTypeDef",
     "InvalidationBatchTypeDef",
     "InvalidationListTypeDef",
     "KGKeyPairIdsTypeDef",
     "SignerTypeDef",
     "LambdaFunctionAssociationsTypeDef",
-    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
-    "ListDistributionsRequestListDistributionsPaginateTypeDef",
-    "ListInvalidationsRequestListInvalidationsPaginateTypeDef",
-    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
     "MonitoringSubscriptionTypeDef",
     "OriginAccessControlListTypeDef",
     "OriginGroupFailoverCriteriaTypeDef",
     "OriginGroupMembersTypeDef",
     "PublicKeyListTypeDef",
     "QueryArgProfilesTypeDef",
     "ResponseHeadersPolicyCorsConfigTypeDef",
@@ -651,25 +651,14 @@
 )
 
 class CopyDistributionRequestRequestTypeDef(
     _RequiredCopyDistributionRequestRequestTypeDef, _OptionalCopyDistributionRequestRequestTypeDef
 ):
     pass
 
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
 FunctionConfigTypeDef = TypedDict(
     "FunctionConfigTypeDef",
     {
         "Comment": str,
         "Runtime": Literal["cloudfront-js-1.0"],
     },
 )
@@ -1093,14 +1082,21 @@
 )
 
 class DistributionIdListTypeDef(
     _RequiredDistributionIdListTypeDef, _OptionalDistributionIdListTypeDef
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFieldPatternsTypeDef = TypedDict(
     "_RequiredFieldPatternsTypeDef",
     {
         "Quantity": int,
     },
 )
 _OptionalFieldPatternsTypeDef = TypedDict(
@@ -1294,14 +1290,24 @@
 )
 
 class GetFunctionRequestRequestTypeDef(
     _RequiredGetFunctionRequestRequestTypeDef, _OptionalGetFunctionRequestRequestTypeDef
 ):
     pass
 
+GetFunctionResultTypeDef = TypedDict(
+    "GetFunctionResultTypeDef",
+    {
+        "FunctionCode": StreamingBody,
+        "ETag": str,
+        "ContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInvalidationRequestRequestTypeDef = TypedDict(
     "GetInvalidationRequestRequestTypeDef",
     {
         "DistributionId": str,
         "Id": str,
     },
 )
@@ -1475,20 +1481,18 @@
         "Type": CachePolicyTypeType,
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef = TypedDict(
+    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef = TypedDict(
     "ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef",
     {
@@ -1641,14 +1645,22 @@
 
 class ListDistributionsByWebACLIdRequestRequestTypeDef(
     _RequiredListDistributionsByWebACLIdRequestRequestTypeDef,
     _OptionalListDistributionsByWebACLIdRequestRequestTypeDef,
 ):
     pass
 
+ListDistributionsRequestListDistributionsPaginateTypeDef = TypedDict(
+    "ListDistributionsRequestListDistributionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDistributionsRequestRequestTypeDef = TypedDict(
     "ListDistributionsRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
@@ -1678,14 +1690,34 @@
         "Marker": str,
         "MaxItems": str,
         "Stage": FunctionStageType,
     },
     total=False,
 )
 
+_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
+    "_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef",
+    {
+        "DistributionId": str,
+    },
+)
+_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
+    "_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListInvalidationsRequestListInvalidationsPaginateTypeDef(
+    _RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef,
+    _OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListInvalidationsRequestRequestTypeDef = TypedDict(
     "_RequiredListInvalidationsRequestRequestTypeDef",
     {
         "DistributionId": str,
     },
 )
 _OptionalListInvalidationsRequestRequestTypeDef = TypedDict(
@@ -1754,14 +1786,22 @@
         "Type": ResponseHeadersPolicyTypeType,
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
 )
 
+ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef = TypedDict(
+    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListStreamingDistributionsRequestRequestTypeDef = TypedDict(
     "ListStreamingDistributionsRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": str,
     },
     total=False,
@@ -1828,14 +1868,24 @@
 S3OriginConfigTypeDef = TypedDict(
     "S3OriginConfigTypeDef",
     {
         "OriginAccessIdentity": str,
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
 _RequiredPublicKeySummaryTypeDef = TypedDict(
     "_RequiredPublicKeySummaryTypeDef",
     {
         "Id": str,
         "Name": str,
         "CreatedTime": datetime,
         "EncodedKey": str,
@@ -2019,14 +2069,25 @@
 
 class ResponseHeadersPolicyXSSProtectionTypeDef(
     _RequiredResponseHeadersPolicyXSSProtectionTypeDef,
     _OptionalResponseHeadersPolicyXSSProtectionTypeDef,
 ):
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
 S3OriginTypeDef = TypedDict(
     "S3OriginTypeDef",
     {
         "DomainName": str,
         "OriginAccessIdentity": str,
     },
 )
@@ -2282,14 +2343,23 @@
 CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef = TypedDict(
     "CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
     {
         "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
     },
 )
 
+GetCloudFrontOriginAccessIdentityConfigResultTypeDef = TypedDict(
+    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
+    {
+        "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
+        "ETag": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef",
     {
         "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
         "Id": str,
     },
 )
@@ -2377,40 +2447,14 @@
 
 class ContinuousDeploymentSingleWeightConfigTypeDef(
     _RequiredContinuousDeploymentSingleWeightConfigTypeDef,
     _OptionalContinuousDeploymentSingleWeightConfigTypeDef,
 ):
     pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCloudFrontOriginAccessIdentityConfigResultTypeDef = TypedDict(
-    "GetCloudFrontOriginAccessIdentityConfigResultTypeDef",
-    {
-        "CloudFrontOriginAccessIdentityConfig": CloudFrontOriginAccessIdentityConfigTypeDef,
-        "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFunctionResultTypeDef = TypedDict(
-    "GetFunctionResultTypeDef",
-    {
-        "FunctionCode": StreamingBody,
-        "ETag": str,
-        "ContentType": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateFunctionRequestRequestTypeDef = TypedDict(
     "CreateFunctionRequestRequestTypeDef",
     {
         "Name": str,
         "FunctionConfig": FunctionConfigTypeDef,
         "FunctionCode": Union[str, bytes, IO[Any], StreamingBody],
     },
@@ -2434,15 +2478,15 @@
 )
 
 GetKeyGroupConfigResultTypeDef = TypedDict(
     "GetKeyGroupConfigResultTypeDef",
     {
         "KeyGroupConfig": KeyGroupConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 KeyGroupTypeDef = TypedDict(
     "KeyGroupTypeDef",
     {
         "Id": str,
@@ -2479,15 +2523,15 @@
 )
 
 GetOriginAccessControlConfigResultTypeDef = TypedDict(
     "GetOriginAccessControlConfigResultTypeDef",
     {
         "OriginAccessControlConfig": OriginAccessControlConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOriginAccessControlTypeDef = TypedDict(
     "_RequiredOriginAccessControlTypeDef",
     {
         "Id": str,
@@ -2535,15 +2579,15 @@
 )
 
 GetPublicKeyConfigResultTypeDef = TypedDict(
     "GetPublicKeyConfigResultTypeDef",
     {
         "PublicKeyConfig": PublicKeyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PublicKeyTypeDef = TypedDict(
     "PublicKeyTypeDef",
     {
         "Id": str,
@@ -2631,39 +2675,39 @@
 ):
     pass
 
 ListDistributionsByCachePolicyIdResultTypeDef = TypedDict(
     "ListDistributionsByCachePolicyIdResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByKeyGroupResultTypeDef = TypedDict(
     "ListDistributionsByKeyGroupResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByOriginRequestPolicyIdResultTypeDef = TypedDict(
     "ListDistributionsByOriginRequestPolicyIdResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByResponseHeadersPolicyIdResultTypeDef = TypedDict(
     "ListDistributionsByResponseHeadersPolicyIdResultTypeDef",
     {
         "DistributionIdList": DistributionIdListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EncryptionEntityTypeDef = TypedDict(
     "EncryptionEntityTypeDef",
     {
         "PublicKeyId": str,
@@ -2857,58 +2901,14 @@
 )
 
 class LambdaFunctionAssociationsTypeDef(
     _RequiredLambdaFunctionAssociationsTypeDef, _OptionalLambdaFunctionAssociationsTypeDef
 ):
     pass
 
-ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef = TypedDict(
-    "ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDistributionsRequestListDistributionsPaginateTypeDef = TypedDict(
-    "ListDistributionsRequestListDistributionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
-    "_RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef",
-    {
-        "DistributionId": str,
-    },
-)
-_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef = TypedDict(
-    "_OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListInvalidationsRequestListInvalidationsPaginateTypeDef(
-    _RequiredListInvalidationsRequestListInvalidationsPaginateTypeDef,
-    _OptionalListInvalidationsRequestListInvalidationsPaginateTypeDef,
-):
-    pass
-
-ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef = TypedDict(
-    "ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 MonitoringSubscriptionTypeDef = TypedDict(
     "MonitoringSubscriptionTypeDef",
     {
         "RealtimeMetricsSubscriptionConfig": RealtimeMetricsSubscriptionConfigTypeDef,
     },
     total=False,
 )
@@ -3188,49 +3188,49 @@
 
 CreateCloudFrontOriginAccessIdentityResultTypeDef = TypedDict(
     "CreateCloudFrontOriginAccessIdentityResultTypeDef",
     {
         "CloudFrontOriginAccessIdentity": CloudFrontOriginAccessIdentityTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCloudFrontOriginAccessIdentityResultTypeDef = TypedDict(
     "GetCloudFrontOriginAccessIdentityResultTypeDef",
     {
         "CloudFrontOriginAccessIdentity": CloudFrontOriginAccessIdentityTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCloudFrontOriginAccessIdentityResultTypeDef = TypedDict(
     "UpdateCloudFrontOriginAccessIdentityResultTypeDef",
     {
         "CloudFrontOriginAccessIdentity": CloudFrontOriginAccessIdentityTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCloudFrontOriginAccessIdentitiesResultTypeDef = TypedDict(
     "ListCloudFrontOriginAccessIdentitiesResultTypeDef",
     {
         "CloudFrontOriginAccessIdentityList": CloudFrontOriginAccessIdentityListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListConflictingAliasesResultTypeDef = TypedDict(
     "ListConflictingAliasesResultTypeDef",
     {
         "ConflictingAliasesList": ConflictingAliasesListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredContentTypeProfileConfigTypeDef = TypedDict(
     "_RequiredContentTypeProfileConfigTypeDef",
     {
         "ForwardWhenContentTypeIsUnknown": bool,
@@ -3269,24 +3269,24 @@
 
 CreateKeyGroupResultTypeDef = TypedDict(
     "CreateKeyGroupResultTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKeyGroupResultTypeDef = TypedDict(
     "GetKeyGroupResultTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 KeyGroupSummaryTypeDef = TypedDict(
     "KeyGroupSummaryTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
@@ -3294,71 +3294,71 @@
 )
 
 UpdateKeyGroupResultTypeDef = TypedDict(
     "UpdateKeyGroupResultTypeDef",
     {
         "KeyGroup": KeyGroupTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateOriginAccessControlResultTypeDef = TypedDict(
     "CreateOriginAccessControlResultTypeDef",
     {
         "OriginAccessControl": OriginAccessControlTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOriginAccessControlResultTypeDef = TypedDict(
     "GetOriginAccessControlResultTypeDef",
     {
         "OriginAccessControl": OriginAccessControlTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateOriginAccessControlResultTypeDef = TypedDict(
     "UpdateOriginAccessControlResultTypeDef",
     {
         "OriginAccessControl": OriginAccessControlTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePublicKeyResultTypeDef = TypedDict(
     "CreatePublicKeyResultTypeDef",
     {
         "PublicKey": PublicKeyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPublicKeyResultTypeDef = TypedDict(
     "GetPublicKeyResultTypeDef",
     {
         "PublicKey": PublicKeyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePublicKeyResultTypeDef = TypedDict(
     "UpdatePublicKeyResultTypeDef",
     {
         "PublicKey": PublicKeyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOriginTypeDef = TypedDict(
     "_RequiredOriginTypeDef",
     {
         "Id": str,
@@ -3437,24 +3437,24 @@
 
 CreateFunctionResultTypeDef = TypedDict(
     "CreateFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFunctionResultTypeDef = TypedDict(
     "DescribeFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFunctionListTypeDef = TypedDict(
     "_RequiredFunctionListTypeDef",
     {
         "MaxItems": int,
@@ -3473,15 +3473,15 @@
 class FunctionListTypeDef(_RequiredFunctionListTypeDef, _OptionalFunctionListTypeDef):
     pass
 
 PublishFunctionResultTypeDef = TypedDict(
     "PublishFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestResultTypeDef = TypedDict(
     "TestResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
@@ -3494,15 +3494,15 @@
 )
 
 UpdateFunctionResultTypeDef = TypedDict(
     "UpdateFunctionResultTypeDef",
     {
         "FunctionSummary": FunctionSummaryTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInvalidationRequestRequestTypeDef = TypedDict(
     "CreateInvalidationRequestRequestTypeDef",
     {
         "DistributionId": str,
@@ -3520,15 +3520,15 @@
     },
 )
 
 ListInvalidationsResultTypeDef = TypedDict(
     "ListInvalidationsResultTypeDef",
     {
         "InvalidationList": InvalidationListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActiveTrustedKeyGroupsTypeDef = TypedDict(
     "_RequiredActiveTrustedKeyGroupsTypeDef",
     {
         "Enabled": bool,
@@ -3576,31 +3576,31 @@
     },
 )
 
 CreateMonitoringSubscriptionResultTypeDef = TypedDict(
     "CreateMonitoringSubscriptionResultTypeDef",
     {
         "MonitoringSubscription": MonitoringSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMonitoringSubscriptionResultTypeDef = TypedDict(
     "GetMonitoringSubscriptionResultTypeDef",
     {
         "MonitoringSubscription": MonitoringSubscriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOriginAccessControlsResultTypeDef = TypedDict(
     "ListOriginAccessControlsResultTypeDef",
     {
         "OriginAccessControlList": OriginAccessControlListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginGroupTypeDef = TypedDict(
     "OriginGroupTypeDef",
     {
         "Id": str,
@@ -3609,15 +3609,15 @@
     },
 )
 
 ListPublicKeysResultTypeDef = TypedDict(
     "ListPublicKeysResultTypeDef",
     {
         "PublicKeyList": PublicKeyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredQueryArgProfileConfigTypeDef = TypedDict(
     "_RequiredQueryArgProfileConfigTypeDef",
     {
         "ForwardWhenQueryArgProfileIsUnknown": bool,
@@ -3691,15 +3691,15 @@
 )
 
 GetStreamingDistributionConfigResultTypeDef = TypedDict(
     "GetStreamingDistributionConfigResultTypeDef",
     {
         "StreamingDistributionConfig": StreamingDistributionConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateStreamingDistributionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateStreamingDistributionRequestRequestTypeDef",
     {
         "StreamingDistributionConfig": StreamingDistributionConfigTypeDef,
@@ -3720,15 +3720,15 @@
 ):
     pass
 
 ListTagsForResourceResultTypeDef = TypedDict(
     "ListTagsForResourceResultTypeDef",
     {
         "Tags": TagsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StreamingDistributionConfigWithTagsTypeDef = TypedDict(
     "StreamingDistributionConfigWithTagsTypeDef",
     {
         "StreamingDistributionConfig": StreamingDistributionConfigTypeDef,
@@ -3844,15 +3844,15 @@
 )
 
 GetOriginRequestPolicyConfigResultTypeDef = TypedDict(
     "GetOriginRequestPolicyConfigResultTypeDef",
     {
         "OriginRequestPolicyConfig": OriginRequestPolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginRequestPolicyTypeDef = TypedDict(
     "OriginRequestPolicyTypeDef",
     {
         "Id": str,
@@ -3975,23 +3975,23 @@
 ):
     pass
 
 CreateRealtimeLogConfigResultTypeDef = TypedDict(
     "CreateRealtimeLogConfigResultTypeDef",
     {
         "RealtimeLogConfig": RealtimeLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRealtimeLogConfigResultTypeDef = TypedDict(
     "GetRealtimeLogConfigResultTypeDef",
     {
         "RealtimeLogConfig": RealtimeLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRealtimeLogConfigsTypeDef = TypedDict(
     "_RequiredRealtimeLogConfigsTypeDef",
     {
         "MaxItems": int,
@@ -4013,48 +4013,48 @@
 ):
     pass
 
 UpdateRealtimeLogConfigResultTypeDef = TypedDict(
     "UpdateRealtimeLogConfigResultTypeDef",
     {
         "RealtimeLogConfig": RealtimeLogConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionsResultTypeDef = TypedDict(
     "ListFunctionsResultTypeDef",
     {
         "FunctionList": FunctionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestFunctionResultTypeDef = TypedDict(
     "TestFunctionResultTypeDef",
     {
         "TestResult": TestResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInvalidationResultTypeDef = TypedDict(
     "CreateInvalidationResultTypeDef",
     {
         "Location": str,
         "Invalidation": InvalidationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInvalidationResultTypeDef = TypedDict(
     "GetInvalidationResultTypeDef",
     {
         "Invalidation": InvalidationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStreamingDistributionTypeDef = TypedDict(
     "_RequiredStreamingDistributionTypeDef",
     {
         "Id": str,
@@ -4146,15 +4146,15 @@
 )
 
 GetResponseHeadersPolicyConfigResultTypeDef = TypedDict(
     "GetResponseHeadersPolicyConfigResultTypeDef",
     {
         "ResponseHeadersPolicyConfig": ResponseHeadersPolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseHeadersPolicyTypeDef = TypedDict(
     "ResponseHeadersPolicyTypeDef",
     {
         "Id": str,
@@ -4184,15 +4184,15 @@
 ):
     pass
 
 ListStreamingDistributionsResultTypeDef = TypedDict(
     "ListStreamingDistributionsResultTypeDef",
     {
         "StreamingDistributionList": StreamingDistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingDistributionWithTagsRequestRequestTypeDef = TypedDict(
     "CreateStreamingDistributionWithTagsRequestRequestTypeDef",
     {
         "StreamingDistributionConfigWithTags": StreamingDistributionConfigWithTagsTypeDef,
@@ -4233,15 +4233,15 @@
 )
 
 GetCachePolicyConfigResultTypeDef = TypedDict(
     "GetCachePolicyConfigResultTypeDef",
     {
         "CachePolicyConfig": CachePolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateCachePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateCachePolicyRequestRequestTypeDef",
     {
         "CachePolicyConfig": CachePolicyConfigTypeDef,
@@ -4263,24 +4263,24 @@
 
 CreateOriginRequestPolicyResultTypeDef = TypedDict(
     "CreateOriginRequestPolicyResultTypeDef",
     {
         "OriginRequestPolicy": OriginRequestPolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOriginRequestPolicyResultTypeDef = TypedDict(
     "GetOriginRequestPolicyResultTypeDef",
     {
         "OriginRequestPolicy": OriginRequestPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OriginRequestPolicySummaryTypeDef = TypedDict(
     "OriginRequestPolicySummaryTypeDef",
     {
         "Type": OriginRequestPolicyTypeType,
@@ -4289,15 +4289,15 @@
 )
 
 UpdateOriginRequestPolicyResultTypeDef = TypedDict(
     "UpdateOriginRequestPolicyResultTypeDef",
     {
         "OriginRequestPolicy": OriginRequestPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContinuousDeploymentPolicyTypeDef = TypedDict(
     "ContinuousDeploymentPolicyTypeDef",
     {
         "Id": str,
@@ -4314,15 +4314,15 @@
 )
 
 GetContinuousDeploymentPolicyConfigResultTypeDef = TypedDict(
     "GetContinuousDeploymentPolicyConfigResultTypeDef",
     {
         "ContinuousDeploymentPolicyConfig": ContinuousDeploymentPolicyConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContinuousDeploymentPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContinuousDeploymentPolicyRequestRequestTypeDef",
     {
         "ContinuousDeploymentPolicyConfig": ContinuousDeploymentPolicyConfigTypeDef,
@@ -4343,15 +4343,15 @@
 ):
     pass
 
 ListKeyGroupsResultTypeDef = TypedDict(
     "ListKeyGroupsResultTypeDef",
     {
         "KeyGroupList": KeyGroupListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionProfileRequestRequestTypeDef = TypedDict(
     "CreateFieldLevelEncryptionProfileRequestRequestTypeDef",
     {
         "FieldLevelEncryptionProfileConfig": FieldLevelEncryptionProfileConfigTypeDef,
@@ -4368,15 +4368,15 @@
 )
 
 GetFieldLevelEncryptionProfileConfigResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionProfileConfigResultTypeDef",
     {
         "FieldLevelEncryptionProfileConfig": FieldLevelEncryptionProfileConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFieldLevelEncryptionProfileRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFieldLevelEncryptionProfileRequestRequestTypeDef",
     {
         "FieldLevelEncryptionProfileConfig": FieldLevelEncryptionProfileConfigTypeDef,
@@ -4418,53 +4418,53 @@
 ):
     pass
 
 ListRealtimeLogConfigsResultTypeDef = TypedDict(
     "ListRealtimeLogConfigsResultTypeDef",
     {
         "RealtimeLogConfigs": RealtimeLogConfigsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingDistributionResultTypeDef = TypedDict(
     "CreateStreamingDistributionResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateStreamingDistributionWithTagsResultTypeDef = TypedDict(
     "CreateStreamingDistributionWithTagsResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStreamingDistributionResultTypeDef = TypedDict(
     "GetStreamingDistributionResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateStreamingDistributionResultTypeDef = TypedDict(
     "UpdateStreamingDistributionResultTypeDef",
     {
         "StreamingDistribution": StreamingDistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionConfigRequestRequestTypeDef = TypedDict(
     "CreateFieldLevelEncryptionConfigRequestRequestTypeDef",
     {
         "FieldLevelEncryptionConfig": FieldLevelEncryptionConfigTypeDef,
@@ -4481,15 +4481,15 @@
 )
 
 GetFieldLevelEncryptionConfigResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionConfigResultTypeDef",
     {
         "FieldLevelEncryptionConfig": FieldLevelEncryptionConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFieldLevelEncryptionConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFieldLevelEncryptionConfigRequestRequestTypeDef",
     {
         "FieldLevelEncryptionConfig": FieldLevelEncryptionConfigTypeDef,
@@ -4533,24 +4533,24 @@
 
 CreateResponseHeadersPolicyResultTypeDef = TypedDict(
     "CreateResponseHeadersPolicyResultTypeDef",
     {
         "ResponseHeadersPolicy": ResponseHeadersPolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetResponseHeadersPolicyResultTypeDef = TypedDict(
     "GetResponseHeadersPolicyResultTypeDef",
     {
         "ResponseHeadersPolicy": ResponseHeadersPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResponseHeadersPolicySummaryTypeDef = TypedDict(
     "ResponseHeadersPolicySummaryTypeDef",
     {
         "Type": ResponseHeadersPolicyTypeType,
@@ -4559,15 +4559,15 @@
 )
 
 UpdateResponseHeadersPolicyResultTypeDef = TypedDict(
     "UpdateResponseHeadersPolicyResultTypeDef",
     {
         "ResponseHeadersPolicy": ResponseHeadersPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDistributionConfigTypeDef = TypedDict(
     "_RequiredDistributionConfigTypeDef",
     {
         "CallerReference": str,
@@ -4651,33 +4651,33 @@
 
 CreateCachePolicyResultTypeDef = TypedDict(
     "CreateCachePolicyResultTypeDef",
     {
         "CachePolicy": CachePolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCachePolicyResultTypeDef = TypedDict(
     "GetCachePolicyResultTypeDef",
     {
         "CachePolicy": CachePolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCachePolicyResultTypeDef = TypedDict(
     "UpdateCachePolicyResultTypeDef",
     {
         "CachePolicy": CachePolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredOriginRequestPolicyListTypeDef = TypedDict(
     "_RequiredOriginRequestPolicyListTypeDef",
     {
         "MaxItems": int,
@@ -4707,105 +4707,105 @@
 
 CreateContinuousDeploymentPolicyResultTypeDef = TypedDict(
     "CreateContinuousDeploymentPolicyResultTypeDef",
     {
         "ContinuousDeploymentPolicy": ContinuousDeploymentPolicyTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContinuousDeploymentPolicyResultTypeDef = TypedDict(
     "GetContinuousDeploymentPolicyResultTypeDef",
     {
         "ContinuousDeploymentPolicy": ContinuousDeploymentPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContinuousDeploymentPolicyResultTypeDef = TypedDict(
     "UpdateContinuousDeploymentPolicyResultTypeDef",
     {
         "ContinuousDeploymentPolicy": ContinuousDeploymentPolicyTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionProfileResultTypeDef = TypedDict(
     "CreateFieldLevelEncryptionProfileResultTypeDef",
     {
         "FieldLevelEncryptionProfile": FieldLevelEncryptionProfileTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFieldLevelEncryptionProfileResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionProfileResultTypeDef",
     {
         "FieldLevelEncryptionProfile": FieldLevelEncryptionProfileTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFieldLevelEncryptionProfileResultTypeDef = TypedDict(
     "UpdateFieldLevelEncryptionProfileResultTypeDef",
     {
         "FieldLevelEncryptionProfile": FieldLevelEncryptionProfileTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFieldLevelEncryptionProfilesResultTypeDef = TypedDict(
     "ListFieldLevelEncryptionProfilesResultTypeDef",
     {
         "FieldLevelEncryptionProfileList": FieldLevelEncryptionProfileListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFieldLevelEncryptionConfigResultTypeDef = TypedDict(
     "CreateFieldLevelEncryptionConfigResultTypeDef",
     {
         "FieldLevelEncryption": FieldLevelEncryptionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFieldLevelEncryptionResultTypeDef = TypedDict(
     "GetFieldLevelEncryptionResultTypeDef",
     {
         "FieldLevelEncryption": FieldLevelEncryptionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateFieldLevelEncryptionConfigResultTypeDef = TypedDict(
     "UpdateFieldLevelEncryptionConfigResultTypeDef",
     {
         "FieldLevelEncryption": FieldLevelEncryptionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFieldLevelEncryptionConfigsResultTypeDef = TypedDict(
     "ListFieldLevelEncryptionConfigsResultTypeDef",
     {
         "FieldLevelEncryptionList": FieldLevelEncryptionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredResponseHeadersPolicyListTypeDef = TypedDict(
     "_RequiredResponseHeadersPolicyListTypeDef",
     {
         "MaxItems": int,
@@ -4867,15 +4867,15 @@
     pass
 
 GetDistributionConfigResultTypeDef = TypedDict(
     "GetDistributionConfigResultTypeDef",
     {
         "DistributionConfig": DistributionConfigTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDistributionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDistributionRequestRequestTypeDef",
     {
         "DistributionConfig": DistributionConfigTypeDef,
@@ -4936,15 +4936,15 @@
 class CachePolicyListTypeDef(_RequiredCachePolicyListTypeDef, _OptionalCachePolicyListTypeDef):
     pass
 
 ListOriginRequestPoliciesResultTypeDef = TypedDict(
     "ListOriginRequestPoliciesResultTypeDef",
     {
         "OriginRequestPolicyList": OriginRequestPolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredContinuousDeploymentPolicyListTypeDef = TypedDict(
     "_RequiredContinuousDeploymentPolicyListTypeDef",
     {
         "MaxItems": int,
@@ -4965,15 +4965,15 @@
 ):
     pass
 
 ListResponseHeadersPoliciesResultTypeDef = TypedDict(
     "ListResponseHeadersPoliciesResultTypeDef",
     {
         "ResponseHeadersPolicyList": ResponseHeadersPolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionWithTagsRequestRequestTypeDef = TypedDict(
     "CreateDistributionWithTagsRequestRequestTypeDef",
     {
         "DistributionConfigWithTags": DistributionConfigWithTagsTypeDef,
@@ -4982,97 +4982,97 @@
 
 CopyDistributionResultTypeDef = TypedDict(
     "CopyDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionResultTypeDef = TypedDict(
     "CreateDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionWithTagsResultTypeDef = TypedDict(
     "CreateDistributionWithTagsResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "Location": str,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionResultTypeDef = TypedDict(
     "GetDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionResultTypeDef = TypedDict(
     "UpdateDistributionResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionWithStagingConfigResultTypeDef = TypedDict(
     "UpdateDistributionWithStagingConfigResultTypeDef",
     {
         "Distribution": DistributionTypeDef,
         "ETag": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByRealtimeLogConfigResultTypeDef = TypedDict(
     "ListDistributionsByRealtimeLogConfigResultTypeDef",
     {
         "DistributionList": DistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsByWebACLIdResultTypeDef = TypedDict(
     "ListDistributionsByWebACLIdResultTypeDef",
     {
         "DistributionList": DistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDistributionsResultTypeDef = TypedDict(
     "ListDistributionsResultTypeDef",
     {
         "DistributionList": DistributionListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCachePoliciesResultTypeDef = TypedDict(
     "ListCachePoliciesResultTypeDef",
     {
         "CachePolicyList": CachePolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListContinuousDeploymentPoliciesResultTypeDef = TypedDict(
     "ListContinuousDeploymentPoliciesResultTypeDef",
     {
         "ContinuousDeploymentPolicyList": ContinuousDeploymentPolicyListTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/waiter.py` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront/waiter.pyi` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/PKG-INFO` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cloudfront
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CloudFront 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CloudFront 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cloudfront"></a>
 
 # types-aiobotocore-cloudfront
 
 [![PyPI - types-aiobotocore-cloudfront](https://img.shields.io/pypi/v/types-aiobotocore-cloudfront.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudfront)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cloudfront.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cloudfront)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cloudfront?color=blue)](https://pypistats.org/packages/types-aiobotocore-cloudfront)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CloudFront 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront)
+[aiobotocore.CloudFront 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cloudfront.html#CloudFront)
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
 [types-aiobotocore-cloudfront docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudfront/).
 
 See how it helps to find and fix potential bugs:
 
@@ -421,15 +421,14 @@
     CloudFrontOriginAccessIdentitySummaryTypeDef,
     ConflictingAliasTypeDef,
     ContentTypeProfileTypeDef,
     StagingDistributionDnsNamesTypeDef,
     ContinuousDeploymentSingleHeaderConfigTypeDef,
     SessionStickinessConfigTypeDef,
     CopyDistributionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     FunctionConfigTypeDef,
     KeyGroupConfigTypeDef,
     OriginAccessControlConfigTypeDef,
     PublicKeyConfigTypeDef,
     CustomErrorResponseTypeDef,
     OriginCustomHeaderTypeDef,
     OriginSslProtocolsTypeDef,
@@ -448,14 +447,15 @@
     DeleteRealtimeLogConfigRequestRequestTypeDef,
     DeleteResponseHeadersPolicyRequestRequestTypeDef,
     DeleteStreamingDistributionRequestRequestTypeDef,
     DescribeFunctionRequestRequestTypeDef,
     LoggingConfigTypeDef,
     ViewerCertificateTypeDef,
     DistributionIdListTypeDef,
+    EmptyResponseMetadataTypeDef,
     FieldPatternsTypeDef,
     KinesisStreamConfigTypeDef,
     QueryStringCacheKeysTypeDef,
     FunctionAssociationTypeDef,
     FunctionMetadataTypeDef,
     GeoRestrictionTypeDef,
     GetCachePolicyConfigRequestRequestTypeDef,
@@ -468,14 +468,15 @@
     WaiterConfigTypeDef,
     GetDistributionRequestRequestTypeDef,
     GetFieldLevelEncryptionConfigRequestRequestTypeDef,
     GetFieldLevelEncryptionProfileConfigRequestRequestTypeDef,
     GetFieldLevelEncryptionProfileRequestRequestTypeDef,
     GetFieldLevelEncryptionRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
+    GetFunctionResultTypeDef,
     GetInvalidationRequestRequestTypeDef,
     GetKeyGroupConfigRequestRequestTypeDef,
     GetKeyGroupRequestRequestTypeDef,
     GetMonitoringSubscriptionRequestRequestTypeDef,
     GetOriginAccessControlConfigRequestRequestTypeDef,
     GetOriginAccessControlRequestRequestTypeDef,
     GetOriginRequestPolicyConfigRequestRequestTypeDef,
@@ -488,43 +489,47 @@
     GetStreamingDistributionConfigRequestRequestTypeDef,
     GetStreamingDistributionRequestRequestTypeDef,
     PathsTypeDef,
     InvalidationSummaryTypeDef,
     KeyPairIdsTypeDef,
     LambdaFunctionAssociationTypeDef,
     ListCachePoliciesRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef,
     ListCloudFrontOriginAccessIdentitiesRequestRequestTypeDef,
     ListConflictingAliasesRequestRequestTypeDef,
     ListContinuousDeploymentPoliciesRequestRequestTypeDef,
     ListDistributionsByCachePolicyIdRequestRequestTypeDef,
     ListDistributionsByKeyGroupRequestRequestTypeDef,
     ListDistributionsByOriginRequestPolicyIdRequestRequestTypeDef,
     ListDistributionsByRealtimeLogConfigRequestRequestTypeDef,
     ListDistributionsByResponseHeadersPolicyIdRequestRequestTypeDef,
     ListDistributionsByWebACLIdRequestRequestTypeDef,
+    ListDistributionsRequestListDistributionsPaginateTypeDef,
     ListDistributionsRequestRequestTypeDef,
     ListFieldLevelEncryptionConfigsRequestRequestTypeDef,
     ListFieldLevelEncryptionProfilesRequestRequestTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListInvalidationsRequestListInvalidationsPaginateTypeDef,
     ListInvalidationsRequestRequestTypeDef,
     ListKeyGroupsRequestRequestTypeDef,
     ListOriginAccessControlsRequestRequestTypeDef,
     ListOriginRequestPoliciesRequestRequestTypeDef,
     ListPublicKeysRequestRequestTypeDef,
     ListRealtimeLogConfigsRequestRequestTypeDef,
     ListResponseHeadersPoliciesRequestRequestTypeDef,
+    ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef,
     ListStreamingDistributionsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RealtimeMetricsSubscriptionConfigTypeDef,
     OriginAccessControlSummaryTypeDef,
     StatusCodesTypeDef,
     OriginGroupMemberTypeDef,
     OriginShieldTypeDef,
     S3OriginConfigTypeDef,
+    PaginatorConfigTypeDef,
     PublicKeySummaryTypeDef,
     PublishFunctionRequestRequestTypeDef,
     QueryArgProfileTypeDef,
     ResponseHeadersPolicyAccessControlAllowHeadersTypeDef,
     ResponseHeadersPolicyAccessControlAllowMethodsTypeDef,
     ResponseHeadersPolicyAccessControlAllowOriginsTypeDef,
     ResponseHeadersPolicyAccessControlExposeHeadersTypeDef,
@@ -533,14 +538,15 @@
     ResponseHeadersPolicyContentTypeOptionsTypeDef,
     ResponseHeadersPolicyCustomHeaderTypeDef,
     ResponseHeadersPolicyFrameOptionsTypeDef,
     ResponseHeadersPolicyReferrerPolicyTypeDef,
     ResponseHeadersPolicyRemoveHeaderTypeDef,
     ResponseHeadersPolicyStrictTransportSecurityTypeDef,
     ResponseHeadersPolicyXSSProtectionTypeDef,
+    ResponseMetadataTypeDef,
     S3OriginTypeDef,
     StreamingLoggingConfigTypeDef,
     TagKeysTypeDef,
     TagTypeDef,
     TestFunctionRequestRequestTypeDef,
     UpdateDistributionWithStagingConfigRequestRequestTypeDef,
     AllowedMethodsTypeDef,
@@ -549,22 +555,20 @@
     OriginRequestPolicyCookiesConfigTypeDef,
     CachePolicyHeadersConfigTypeDef,
     OriginRequestPolicyHeadersConfigTypeDef,
     CachePolicyQueryStringsConfigTypeDef,
     OriginRequestPolicyQueryStringsConfigTypeDef,
     CloudFrontOriginAccessIdentityTypeDef,
     CreateCloudFrontOriginAccessIdentityRequestRequestTypeDef,
+    GetCloudFrontOriginAccessIdentityConfigResultTypeDef,
     UpdateCloudFrontOriginAccessIdentityRequestRequestTypeDef,
     CloudFrontOriginAccessIdentityListTypeDef,
     ConflictingAliasesListTypeDef,
     ContentTypeProfilesTypeDef,
     ContinuousDeploymentSingleWeightConfigTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetCloudFrontOriginAccessIdentityConfigResultTypeDef,
-    GetFunctionResultTypeDef,
     CreateFunctionRequestRequestTypeDef,
     UpdateFunctionRequestRequestTypeDef,
     CreateKeyGroupRequestRequestTypeDef,
     GetKeyGroupConfigResultTypeDef,
     KeyGroupTypeDef,
     UpdateKeyGroupRequestRequestTypeDef,
     CreateOriginAccessControlRequestRequestTypeDef,
@@ -591,18 +595,14 @@
     GetInvalidationRequestInvalidationCompletedWaitTypeDef,
     GetStreamingDistributionRequestStreamingDistributionDeployedWaitTypeDef,
     InvalidationBatchTypeDef,
     InvalidationListTypeDef,
     KGKeyPairIdsTypeDef,
     SignerTypeDef,
     LambdaFunctionAssociationsTypeDef,
-    ListCloudFrontOriginAccessIdentitiesRequestListCloudFrontOriginAccessIdentitiesPaginateTypeDef,
-    ListDistributionsRequestListDistributionsPaginateTypeDef,
-    ListInvalidationsRequestListInvalidationsPaginateTypeDef,
-    ListStreamingDistributionsRequestListStreamingDistributionsPaginateTypeDef,
     MonitoringSubscriptionTypeDef,
     OriginAccessControlListTypeDef,
     OriginGroupFailoverCriteriaTypeDef,
     OriginGroupMembersTypeDef,
     PublicKeyListTypeDef,
     QueryArgProfilesTypeDef,
     ResponseHeadersPolicyCorsConfigTypeDef,
@@ -779,43 +779,43 @@
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

### Comparing `types-aiobotocore-cloudfront-2.5.0.post1/types_aiobotocore_cloudfront.egg-info/SOURCES.txt` & `types-aiobotocore-cloudfront-2.5.1/types_aiobotocore_cloudfront.egg-info/SOURCES.txt`

 * *Files identical despite different names*

